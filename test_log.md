#### Test 9869411895ad6eb Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":8}}
2016-12-21 08:45:56 - INFO HttpServer: 'listening on *:3000'

2016-12-21 08:46:07 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'd135cee7-ac0b-4bde-914c-6902a32ac82d', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-12-21 08:46:07 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2016-12-21 08:48:08 - DEBUG HttpServer: 'device presented, name: 'HTC-HTC 10', uuid: '478f7661-f15b-49d1-beea-fe3a05827c64', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-12-21 08:48:08 - DEBUG TestFramework: 'device added, name: 'HTC-HTC 10''

2016-12-21 08:50:56 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_9869411895ad6eb/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-12-21 08:50:56 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2016-12-21 08:50:56 - INFO HttpServer: 'Socket to device name: 'HTC-HTC 10' disconnected, reason: 'undefined''


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!
```
###Android Logs
####Node name: thali01
Console output:
```
Stopping app on  ce061606e320561102
Uninstalling app on  ce061606e320561102

All devices are ready!

Deploying to ce061606e320561102
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce061606e320561102

Starting application ThaliTest on ce061606e320561102

App was succesfully started on ce061606e320561102

Error! Unexpected exit on device ce061606e320561102 app:com.test.thalitest code:null 
Child process exited with code null on device ce061606e320561102
Android task is completed. [FAILED]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/9869411895ad6eb_CI_sanity_check_czyzm/thali01_samsung-SM-G935F.md)

####Node name: thali02
Console output:
```
Stopping app on  ce0616068b9f212302
Uninstalling app on  ce0616068b9f212302

All devices are ready!

Deploying to ce0616068b9f212302
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce0616068b9f212302

Starting application ThaliTest on ce0616068b9f212302

App was succesfully started on ce0616068b9f212302

Error! Unexpected exit on device ce0616068b9f212302 app:com.test.thalitest code:null 
Child process exited with code null on device ce0616068b9f212302
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/9869411895ad6eb_CI_sanity_check_czyzm/thali02_samsung-SM-G930F.md)

####Node name: thali03
Console output:
```
Stopping app on  ce061606c181d71003
Uninstalling app on  ce061606c181d71003

All devices are ready!

Deploying to ce061606c181d71003
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce061606c181d71003

Starting application ThaliTest on ce061606c181d71003

App was succesfully started on ce061606c181d71003

STOP log received from ce061606c181d71003
Test has FAILED

Device test finished on ce061606c181d71003 
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/9869411895ad6eb_CI_sanity_check_czyzm/thali03_samsung-SM-G930F.md)

####Node name: thali05
Console output:
```
Stopping app on  0be0c6c6
Uninstalling app on  0be0c6c6

All devices are ready!

Deploying to 0be0c6c6
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to 0be0c6c6

Starting application ThaliTest on 0be0c6c6

App was succesfully started on 0be0c6c6

Error! Unexpected exit on device 0be0c6c6 app:com.test.thalitest code:null 
Child process exited with code null on device 0be0c6c6
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/9869411895ad6eb_CI_sanity_check_czyzm/thali05_samsung-SM-G900F.md)

####Node name: thali06
Console output:
```
Stopping app on  HT65KBP01047
Uninstalling app on  HT65KBP01047

All devices are ready!

Deploying to HT65KBP01047
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to HT65KBP01047

Starting application ThaliTest on HT65KBP01047

App was succesfully started on HT65KBP01047

STOP log received from HT65KBP01047
Test has FAILED

Device test finished on HT65KBP01047 
Android task is completed. [FAILED]
```
[HTC-HTC 10](https://github.com/ThaliTester/TestResults/blob/9869411895ad6eb_CI_sanity_check_czyzm/thali06_HTC-HTC 10.md)

####Node name: thali07
Console output:
```
Stopping app on  c5afcdcb
Uninstalling app on  c5afcdcb

All devices are ready!

Deploying to c5afcdcb
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to c5afcdcb

Starting application ThaliTest on c5afcdcb

App was succesfully started on c5afcdcb

Error! Unexpected exit on device c5afcdcb app:com.test.thalitest code:null 
Child process exited with code null on device c5afcdcb
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/9869411895ad6eb_CI_sanity_check_czyzm/thali07_samsung-SM-G900F.md)

####Node name: thali08
Console output:
```
Stopping app on  e8b8a5a8
Uninstalling app on  e8b8a5a8

All devices are ready!

Deploying to e8b8a5a8
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to e8b8a5a8

Starting application ThaliTest on e8b8a5a8

App was succesfully started on e8b8a5a8

Error! Unexpected exit on device e8b8a5a8 app:com.test.thalitest code:null 
Child process exited with code null on device e8b8a5a8
Android task is completed. [FAILED]
```
[samsung-SM-T719](https://github.com/ThaliTester/TestResults/blob/9869411895ad6eb_CI_sanity_check_czyzm/thali08_samsung-SM-T719.md)

####Node name: thali09
Console output:
```
Stopping app on  09a9416e0297d102
Uninstalling app on  09a9416e0297d102

All devices are ready!

Deploying to 09a9416e0297d102
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to 09a9416e0297d102

Starting application ThaliTest on 09a9416e0297d102

App was succesfully started on 09a9416e0297d102

STOP log received from 09a9416e0297d102
Test has FAILED

Device test finished on 09a9416e0297d102 
Android task is completed. [FAILED]
```
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/9869411895ad6eb_CI_sanity_check_czyzm/thali09_LGE-Nexus 5.md)





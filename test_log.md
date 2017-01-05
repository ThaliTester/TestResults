#### Test 98694118241dc02 Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
Thu Jan 05 2017 07:41:22 GMT+0000 (UTC) IS Running:
Thu Jan 05 2017 07:41:22 GMT+0000 (UTC) Running 'jx install'
Skipping the log for NPM since the exitCode was 0
Thu Jan 05 2017 07:42:42 GMT+0000 (UTC) > jx index.js {"devices":{"android":3}}
Thu Jan 05 2017 07:42:42 GMT+0000 (UTC) Run index.js
2017-01-05 07:42:52 - INFO HttpServer: 'listening on *:3000'

2017-01-05 07:43:04 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '66b9c317-666b-40de-870a-1d83369d21b2', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-01-05 07:43:04 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-01-05 07:44:26 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'ee14d123-14b4-4c92-a141-3ccf4e7d6e0c', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-01-05 07:44:26 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-01-05 07:47:52 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_98694118241dc02/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-01-05 07:47:52 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''

2017-01-05 07:47:52 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

[0;31merror: command 'sudo jx ______.js android' failed with code 1, file 'bash' on line 30[0m
One or more Android tests are failed.
 [0m
index.js failed [ 1 ]

```


Logs for system : 
```

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!
```
###Android Logs
####Node name: thali02
Console output:
```
Stopping app on  ce0616068b9f212302
Uninstalling app on  ce0616068b9f212302

All devices are ready!

Deploying to ce0616068b9f212302
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
Deploying to ce0616068b9f212302
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce0616068b9f212302

Starting application ThaliTest on ce0616068b9f212302

App was succesfully started on ce0616068b9f212302

STOP log received from ce0616068b9f212302
Test has FAILED

Device test finished on ce0616068b9f212302 
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/98694118241dc02_CI_sanity_check_czyzm/thali02_samsung-SM-G930F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/98694118241dc02_CI_sanity_check_czyzm/thali03_samsung-SM-G930F.md)

####Node name: thali04
Console output:
```
Stopping app on  ce061606e320561102
Uninstalling app on  ce061606e320561102

All devices are ready!

Deploying to ce061606e320561102
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
Deploying to ce061606e320561102
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce061606e320561102

Starting application ThaliTest on ce061606e320561102

App was succesfully started on ce061606e320561102

STOP log received from ce061606e320561102
Test has FAILED

Device test finished on ce061606e320561102 
Android task is completed. [FAILED]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/98694118241dc02_CI_sanity_check_czyzm/thali04_samsung-SM-G935F.md)





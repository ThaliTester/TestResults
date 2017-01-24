#### Test 1027067423e9264e Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":3}}
2017-01-24 07:03:39 - INFO HttpServer: 'listening on *:3000'

2017-01-24 07:03:43 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '233cfff4-4a93-4d36-a450-e5a9e29646a2', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-01-24 07:03:43 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-01-24 07:03:45 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '37539d4a-6668-427e-a0ba-06b807579f17', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-01-24 07:03:45 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-01-24 07:03:47 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'transport close''

2017-01-24 07:03:48 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'transport close''

2017-01-24 07:04:47 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '82e1d7d0-0120-4c1f-b754-b0962379759e', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-01-24 07:04:47 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-01-24 07:04:47 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-01-24 07:04:47 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-01-24 07:04:47 - DEBUG UnitTestFramework: 'scheduling tests'

2017-01-24 07:06:48 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'android', error: 'Error: retry count exceed', stack: 'Error: retry count exceed
    at emit (/home/pi/Test/server_1027067423e9264e/test/TestServer/Socket.js:157:16)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-01-24 07:08:39 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_1027067423e9264e/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-01-24 07:08:39 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''

[0;31merror: command 'sudo jx ______.js all' failed with code 1, file 'bash' on line 30[0m
One or more Android tests are failed.
 [0m
index.js failed [ 1 ]

```


Logs for system : 
```

ios : false

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

Error! Unexpected exit on device ce0616068b9f212302 app:com.test.thalitest code:null 
Child process exited with code null on device ce0616068b9f212302
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/1027067423e9264e_iOS_CI_sanity_check_czyzm/thali02_samsung-SM-G930F.md)

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

Error! Unexpected exit on device ce061606c181d71003 app:com.test.thalitest code:null 
Child process exited with code null on device ce061606c181d71003
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/1027067423e9264e_iOS_CI_sanity_check_czyzm/thali03_samsung-SM-G930F.md)

####Node name: thali04
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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/1027067423e9264e_iOS_CI_sanity_check_czyzm/thali04_samsung-SM-G935F.md)




###iOS Logs
[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/1027067423e9264e_iOS_CI_sanity_check_czyzm/iOS_ipad-air-2-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/1027067423e9264e_iOS_CI_sanity_check_czyzm/iOS_iphone-5s-mfts.md)

[ipad-mini-mfts](https://github.com/ThaliTester/TestResults/blob/1027067423e9264e_iOS_CI_sanity_check_czyzm/iOS_ipad-mini-mfts.md)

[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/1027067423e9264e_iOS_CI_sanity_check_czyzm/iOS_iphone-5s-1.md)



#### Test 1027067426d01702 Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":5,"android":3}}
2017-01-23 12:40:59 - INFO HttpServer: 'listening on *:3000'

2017-01-23 12:41:03 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '0f0f3513-4485-4b9d-8cbb-2843d3821354', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-01-23 12:41:03 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-01-23 12:41:03 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '4a9d841b-c4e9-42f1-b788-663f6e65d909', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-01-23 12:41:03 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-01-23 12:41:06 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'transport close''

2017-01-23 12:41:07 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'transport close''

2017-01-23 12:42:04 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'd1ca211f-eec7-4d02-8206-687a3d399693', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-01-23 12:42:04 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-01-23 12:42:04 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-01-23 12:42:04 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-01-23 12:42:04 - DEBUG UnitTestFramework: 'scheduling tests'

2017-01-23 12:44:05 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'android', error: 'Error: retry count exceed', stack: 'Error: retry count exceed
    at emit (/home/pi/Test/server_1027067426d01702/test/TestServer/Socket.js:157:16)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-01-23 12:45:59 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_1027067426d01702/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-01-23 12:45:59 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

[0;31merror: command 'sudo jx ______.js all' failed with code 1, file 'bash' on line 30[0m
One or more Android tests are failed.
 [0m
index.js failed [ 1 ]

```


Logs for system : 
```

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!

ios : Error: Command failed: true
23/1/2017@13:37:38 Getting the list of iOS devices 
23/1/2017@13:37:39 ios: device name: iphone-6-2 , device identifier:  7ed231f0829a4ace34162e6c18308bcd995bc25a
23/1/2017@13:37:39 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
23/1/2017@13:37:39 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
23/1/2017@13:37:39 ios: device name: ipad-mini-mfts , device identifier:  83aab4e7f1dde3becec287ac4c44362439d2595b
23/1/2017@13:37:39 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
23/1/2017@13:37:39 Deploying iOS test app 
23/1/2017@13:37:39 uninstalling the application 
23/1/2017@13:37:41 installing the application 
23/1/2017@13:37:41 ios: child process exited with code null on device 7ed231f0829a4ace34162e6c18308bcd995bc25a 
23/1/2017@14:00:58 ios: child process exited with code null on device 83aab4e7f1dde3becec287ac4c44362439d2595b 
true

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
App was succesfully deployed to ce0616068b9f212302

Starting application ThaliTest on ce0616068b9f212302

App was succesfully started on ce0616068b9f212302

Error! Unexpected exit on device ce0616068b9f212302 app:com.test.thalitest code:null 
Child process exited with code null on device ce0616068b9f212302
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/1027067426d01702_Magic_dot_czyzm/thali02_samsung-SM-G930F.md)

####Node name: thali03
Console output:
```
Stopping app on  ce061606c181d71003
Uninstalling app on  ce061606c181d71003

All devices are ready!

Deploying to ce061606c181d71003
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
Deploying to ce061606c181d71003
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce061606c181d71003

Starting application ThaliTest on ce061606c181d71003

App was succesfully started on ce061606c181d71003

Error! Unexpected exit on device ce061606c181d71003 app:com.test.thalitest code:null 
Child process exited with code null on device ce061606c181d71003
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/1027067426d01702_Magic_dot_czyzm/thali03_samsung-SM-G930F.md)

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

Error! Unexpected exit on device ce061606e320561102 app:com.test.thalitest code:null 
Child process exited with code null on device ce061606e320561102
Android task is completed. [FAILED]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/1027067426d01702_Magic_dot_czyzm/thali04_samsung-SM-G935F.md)


###iOS Logs
[iphone-6-2](https://github.com/ThaliTester/TestResults/blob/1027067426d01702_Magic_dot_czyzm/iOS_iphone-6-2.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/1027067426d01702_Magic_dot_czyzm/iOS_ipad-air-2-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/1027067426d01702_Magic_dot_czyzm/iOS_iphone-5s-mfts.md)

[ipad-mini-mfts](https://github.com/ThaliTester/TestResults/blob/1027067426d01702_Magic_dot_czyzm/iOS_ipad-mini-mfts.md)

[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/1027067426d01702_Magic_dot_czyzm/iOS_iphone-5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/1027067426d01702_Magic_dot_czyzm/iOS_server.md)





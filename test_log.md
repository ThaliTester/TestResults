#### Test 103282205679c014 Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":5,"android":3}}
2017-02-02 15:28:04 - INFO HttpServer: 'listening on *:3000'

2017-02-02 15:28:08 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-6-2', uuid: '812f8307-b364-4a2d-809c-0a7c8cb2864a', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-02 15:28:08 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-6-2''

2017-02-02 15:28:10 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '84fcd9a0-8630-404b-ac4b-229f4174b5be', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-02 15:28:10 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-air-2-1''

2017-02-02 15:28:18 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: '4bd845ea-079e-440f-9d31-97d48a377b88', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-02 15:28:18 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-1''

2017-02-02 15:28:20 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-mini-mfts', uuid: 'fb15767d-92ab-4fc1-8dfb-0a740def6f92', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-02 15:28:20 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-mini-mfts''

2017-02-02 15:29:26 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '16b8c521-4f62-4417-9e5e-47f26775318b', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-02 15:29:26 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-02-02 15:29:41 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '3896731a-3833-46bb-b67a-89faa19ba1c3', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-02 15:29:41 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-02-02 15:31:15 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '1754bdb6-be1d-4b91-a35d-b307d7ee9e45', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-02 15:31:15 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-02-02 15:31:15 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-02-02 15:31:15 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-02-02 15:31:15 - DEBUG UnitTestFramework: 'scheduling tests'

2017-02-02 15:31:24 - DEBUG UnitTestFramework: 'tests scheduled'

2017-02-02 15:31:24 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-02-02 15:31:58 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-02-02 15:31:58 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-02-02 15:32:01 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-02-02 15:32:01 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-02-02 15:32:08 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-02-02 15:32:09 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-02-02 15:32:16 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-02-02 15:32:16 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-02-02 15:32:22 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-02-02 15:32:22 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-02-02 15:32:23 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-02-02 15:32:23 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-02 15:32:41 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-02 15:32:41 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-02 15:33:04 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_103282205679c014/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-02-02 15:33:04 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-6-2' disconnected, reason: 'undefined''

2017-02-02 15:33:04 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-air-2-1' disconnected, reason: 'undefined''

2017-02-02 15:33:04 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-1' disconnected, reason: 'undefined''

2017-02-02 15:33:04 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-mini-mfts' disconnected, reason: 'undefined''

2017-02-02 15:33:04 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-02-02 15:33:04 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-02-02 15:33:04 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''

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
2/2/2017@16:24:43 Getting the list of iOS devices 
2/2/2017@16:24:44 ios: device name: iphone-6-2 , device identifier:  7ed231f0829a4ace34162e6c18308bcd995bc25a
2/2/2017@16:24:44 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
2/2/2017@16:24:44 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
2/2/2017@16:24:44 ios: device name: ipad-mini-mfts , device identifier:  83aab4e7f1dde3becec287ac4c44362439d2595b
2/2/2017@16:24:44 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
2/2/2017@16:24:44 Deploying iOS test app 
2/2/2017@16:24:44 uninstalling the application 
2/2/2017@16:24:45 installing the application 
2/2/2017@16:27:55 ios: child process exited with code 254 on device bffa901fefdea07f59339a6737776943349f5077 
2/2/2017@16:48:03 ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
2/2/2017@16:48:03 ios: child process exited with code null on device 83aab4e7f1dde3becec287ac4c44362439d2595b 
2/2/2017@16:48:03 ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
2/2/2017@16:48:03 ios: child process exited with code null on device 7ed231f0829a4ace34162e6c18308bcd995bc25a 
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
Deploying to ce0616068b9f212302
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce0616068b9f212302

Starting application ThaliTest on ce0616068b9f212302

App was succesfully started on ce0616068b9f212302

Error! Unexpected exit on device ce0616068b9f212302 app:com.test.thalitest code:null 
Child process exited with code null on device ce0616068b9f212302
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/103282205679c014_Fix_implemented_iOS_native-mode_functionality_dersim-davaod/thali02_samsung-SM-G930F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/103282205679c014_Fix_implemented_iOS_native-mode_functionality_dersim-davaod/thali03_samsung-SM-G930F.md)

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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/103282205679c014_Fix_implemented_iOS_native-mode_functionality_dersim-davaod/thali04_samsung-SM-G935F.md)


###iOS Logs
[iphone-6-2](https://github.com/ThaliTester/TestResults/blob/103282205679c014_Fix_implemented_iOS_native-mode_functionality_dersim-davaod/iOS_iphone-6-2.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/103282205679c014_Fix_implemented_iOS_native-mode_functionality_dersim-davaod/iOS_ipad-air-2-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/103282205679c014_Fix_implemented_iOS_native-mode_functionality_dersim-davaod/iOS_iphone-5s-mfts.md)

[ipad-mini-mfts](https://github.com/ThaliTester/TestResults/blob/103282205679c014_Fix_implemented_iOS_native-mode_functionality_dersim-davaod/iOS_ipad-mini-mfts.md)

[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/103282205679c014_Fix_implemented_iOS_native-mode_functionality_dersim-davaod/iOS_iphone-5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/103282205679c014_Fix_implemented_iOS_native-mode_functionality_dersim-davaod/iOS_server.md)





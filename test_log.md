#### Test 102585911d0c1950 Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":3}}
2017-01-23 14:34:54 - INFO HttpServer: 'listening on *:3000'

2017-01-23 14:34:54 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '3ebf4f87-d674-4be2-a9ad-8fe18b44ca02', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-01-23 14:34:54 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-01-23 14:34:57 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '5db5a732-6752-4724-9d09-2def273f1ad0', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-01-23 14:34:57 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-01-23 14:34:57 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'transport close''

2017-01-23 14:35:00 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'transport close''

2017-01-23 14:36:04 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: 'c3d69d54-cd5b-4aac-b1d7-26839891a82d', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-01-23 14:36:04 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-01-23 14:36:04 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-01-23 14:36:04 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-01-23 14:36:04 - DEBUG UnitTestFramework: 'scheduling tests'

2017-01-23 14:38:05 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'android', error: 'Error: retry count exceed', stack: 'Error: retry count exceed
    at emit (/home/pi/Test/server_102585911d0c1950/test/TestServer/Socket.js:157:16)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-01-23 14:39:54 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_102585911d0c1950/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-01-23 14:39:54 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/102585911d0c1950_Add_null_sending_in_JSON_between_Android_and_Node_evabishchevich/thali02_samsung-SM-G930F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/102585911d0c1950_Add_null_sending_in_JSON_between_Android_and_Node_evabishchevich/thali03_samsung-SM-G930F.md)

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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/102585911d0c1950_Add_null_sending_in_JSON_between_Android_and_Node_evabishchevich/thali04_samsung-SM-G935F.md)




###iOS Logs
[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/102585911d0c1950_Add_null_sending_in_JSON_between_Android_and_Node_evabishchevich/iOS_ipad-air-2-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/102585911d0c1950_Add_null_sending_in_JSON_between_Android_and_Node_evabishchevich/iOS_iphone-5s-mfts.md)

[ipad-mini-mfts](https://github.com/ThaliTester/TestResults/blob/102585911d0c1950_Add_null_sending_in_JSON_between_Android_and_Node_evabishchevich/iOS_ipad-mini-mfts.md)

[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/102585911d0c1950_Add_null_sending_in_JSON_between_Android_and_Node_evabishchevich/iOS_iphone-5s-1.md)



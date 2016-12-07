#### Test 9691894766ea5e0 Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":5,"android":2}}
2016-12-07 14:38:01 - INFO HttpServer: 'listening on *:3000'

2016-12-07 14:39:28 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-mini-mfts', uuid: '802d60da-9c89-42b7-bab2-f8ded7585993', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-12-07 14:39:28 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-mini-mfts''

2016-12-07 14:39:31 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '2e416ca0-dc34-4e75-a4a2-9a1c52119d44', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-12-07 14:39:31 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'Apple-ipad-air-2-1''

2016-12-07 14:39:31 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-air-2-1' disconnected, reason: 'client namespace disconnect''

2016-12-07 14:39:33 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-6-2', uuid: 'd1fe3774-0b5b-4589-a56a-fa9187affe77', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-12-07 14:39:33 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'Apple-iphone-6-2''

2016-12-07 14:39:33 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-6-2' disconnected, reason: 'client namespace disconnect''

2016-12-07 14:39:34 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: 'b388fa4a-aa76-47d9-885b-29d34ba5cc42', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-12-07 14:39:34 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-1''

2016-12-07 14:39:35 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: 'b663bed6-bb3f-475f-b1ae-9b5e2a0c9679', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-12-07 14:39:35 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-mfts''

2016-12-07 14:43:01 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_9691894766ea5e0/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-12-07 14:43:01 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-mini-mfts' disconnected, reason: 'undefined''

2016-12-07 14:43:01 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-1' disconnected, reason: 'undefined''

2016-12-07 14:43:01 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-mfts' disconnected, reason: 'undefined''


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!

ios : Error: Command failed: true
7/12/2016@15:36:34 Getting the list of iOS devices 
7/12/2016@15:36:35 Deploying iOS test app 
7/12/2016@15:36:35 uninstalling the application 
7/12/2016@15:36:36 installing the application 
true

```
###Android Logs
####Node name: thali05
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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/9691894766ea5e0_Implemented_iOS_native-mode_functionality__900___1585___1611_squid48/thali05_samsung-SM-G935F.md)

####Node name: thali07
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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/9691894766ea5e0_Implemented_iOS_native-mode_functionality__900___1585___1611_squid48/thali07_samsung-SM-G930F.md)


###iOS Logs
[ipad-mini-mfts](https://github.com/ThaliTester/TestResults/blob/9691894766ea5e0_Implemented_iOS_native-mode_functionality__900___1585___1611_squid48/iOS_ipad-mini-mfts.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/9691894766ea5e0_Implemented_iOS_native-mode_functionality__900___1585___1611_squid48/iOS_ipad-air-2-1.md)

[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/9691894766ea5e0_Implemented_iOS_native-mode_functionality__900___1585___1611_squid48/iOS_iphone-5s-1.md)

[iphone-6-2](https://github.com/ThaliTester/TestResults/blob/9691894766ea5e0_Implemented_iOS_native-mode_functionality__900___1585___1611_squid48/iOS_iphone-6-2.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/9691894766ea5e0_Implemented_iOS_native-mode_functionality__900___1585___1611_squid48/iOS_iphone-5s-mfts.md)





#### Test 935721679a8c53b Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":2}}
2016-11-21 16:14:26 - INFO HttpServer: 'listening on *:3000'

2016-11-21 16:15:29 - DEBUG HttpServer: 'device presented, name: 'Huawei-Nexus 6P', uuid: '2e75e48b-0bfc-482b-87b9-2c43fc275087', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-11-21 16:15:29 - DEBUG TestFramework: 'device added, name: 'Huawei-Nexus 6P''

2016-11-21 16:19:26 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_935721679a8c53b/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-11-21 16:19:26 - INFO HttpServer: 'Socket to device name: 'Huawei-Nexus 6P' disconnected, reason: 'undefined''


 
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
21/11/2016@17:11:19 Getting the list of iOS devices 
21/11/2016@17:11:20 Deploying iOS test app 
21/11/2016@17:11:20 uninstalling the application 
21/11/2016@17:11:20 installing the application 
21/11/2016@17:34:39 ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/935721679a8c53b_New_peer_generation__894__evabishchevich/thali05_samsung-SM-G935F.md)

####Node name: thali07
Console output:
```
Stopping app on  ENU7N16516000121
Uninstalling app on  ENU7N16516000121

All devices are ready!

Deploying to ENU7N16516000121
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ENU7N16516000121

Starting application ThaliTest on ENU7N16516000121

App was succesfully started on ENU7N16516000121

STOP log received from ENU7N16516000121
Test has FAILED

Device test finished on ENU7N16516000121 
Android task is completed. [FAILED]
```
[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/935721679a8c53b_New_peer_generation__894__evabishchevich/thali07_Huawei-Nexus 6P.md)


###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/935721679a8c53b_New_peer_generation__894__evabishchevich/iOS_IpadAir2-1.md)

[Iphone6-2](https://github.com/ThaliTester/TestResults/blob/935721679a8c53b_New_peer_generation__894__evabishchevich/iOS_Iphone6-2.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/935721679a8c53b_New_peer_generation__894__evabishchevich/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/935721679a8c53b_New_peer_generation__894__evabishchevich/iOS_Iphone6-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/935721679a8c53b_New_peer_generation__894__evabishchevich/iOS_server.md)





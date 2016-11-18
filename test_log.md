#### Test 93765317141d42a Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":3}}
2016-11-18 15:50:04 - INFO HttpServer: 'listening on *:3000'

2016-11-18 15:51:01 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: 'a15077eb-287f-439f-ac71-0f55adeb70e7', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-11-18 15:51:01 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G935F''

2016-11-18 15:51:01 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'client namespace disconnect''

2016-11-18 15:51:10 - DEBUG HttpServer: 'device presented, name: 'Huawei-Nexus 6P', uuid: '41a1d32d-328f-4f4f-888b-e87553a09284', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-11-18 15:51:10 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'Huawei-Nexus 6P''

2016-11-18 15:51:10 - INFO HttpServer: 'Socket to device name: 'Huawei-Nexus 6P' disconnected, reason: 'client namespace disconnect''

2016-11-18 15:55:04 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_93765317141d42a/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m



ios : Error: Command failed: true
18/11/2016@16:46:04 Getting the list of iOS devices 
18/11/2016@16:46:05 Deploying iOS test app 
18/11/2016@16:46:05 uninstalling the application 
18/11/2016@16:46:05 installing the application 
18/11/2016@17:09:24 ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
18/11/2016@17:09:24 ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
true

```
###Android Logs
####Node name: thali05
Console output:
```
Stopping app on  ce061606e320561102
Uninstalling app on  ce061606e320561102
Stopping app on  ENU7N16516000107
Uninstalling app on  ENU7N16516000107

All devices are ready!

Deploying to ce061606e320561102
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce061606e320561102

Deploying to ENU7N16516000107
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ENU7N16516000107

Starting application ThaliTest on ce061606e320561102

Starting application ThaliTest on ENU7N16516000107

App was succesfully started on ce061606e320561102

App was succesfully started on ENU7N16516000107

STOP log received from ce061606e320561102
Test has FAILED

Device test finished on ce061606e320561102 
STOP log received from ENU7N16516000107
Test has FAILED

Device test finished on ENU7N16516000107 
Android task is completed. [FAILED]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/93765317141d42a_update_thali_development_environment_larryonoff/thali05_samsung-SM-G935F.md)

[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/93765317141d42a_update_thali_development_environment_larryonoff/thali05_Huawei-Nexus 6P.md)

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
[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/93765317141d42a_update_thali_development_environment_larryonoff/thali07_Huawei-Nexus 6P.md)


###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/93765317141d42a_update_thali_development_environment_larryonoff/iOS_IpadAir2-1.md)

[Iphone6-2](https://github.com/ThaliTester/TestResults/blob/93765317141d42a_update_thali_development_environment_larryonoff/iOS_Iphone6-2.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/93765317141d42a_update_thali_development_environment_larryonoff/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/93765317141d42a_update_thali_development_environment_larryonoff/iOS_Iphone6-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/93765317141d42a_update_thali_development_environment_larryonoff/iOS_server.md)





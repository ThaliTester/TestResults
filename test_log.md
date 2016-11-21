#### Test 931424420cf4179 Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":2}}
2016-11-21 13:29:54 - INFO HttpServer: 'listening on *:3000'

2016-11-21 13:29:55 - DEBUG HttpServer: 'device presented, name: 'Apple-Iphone5s-1', uuid: '985ec5e5-e920-4e61-a4c5-4e2965dd801b', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-11-21 13:29:55 - DEBUG TestFramework: 'device added, name: 'Apple-Iphone5s-1''

2016-11-21 13:29:56 - DEBUG HttpServer: 'device presented, name: 'Apple-Iphone5s-1', uuid: '985ec5e5-e920-4e61-a4c5-4e2965dd801b', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-11-21 13:29:56 - INFO TestFramework: 'updating existing device, name: 'Apple-Iphone5s-1', uuid: '985ec5e5-e920-4e61-a4c5-4e2965dd801b', platformName: 'ios''

2016-11-21 13:30:57 - DEBUG HttpServer: 'device presented, name: 'Huawei-Nexus 6P', uuid: '8e38447e-4d60-470c-97dc-ccb2f30d385c', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-11-21 13:30:57 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'Huawei-Nexus 6P''

2016-11-21 13:30:57 - INFO HttpServer: 'Socket to device name: 'Huawei-Nexus 6P' disconnected, reason: 'client namespace disconnect''

2016-11-21 13:34:54 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_931424420cf4179/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-11-21 13:34:54 - INFO HttpServer: 'Socket to device name: 'Apple-Iphone5s-1' disconnected, reason: 'undefined''


 
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
21/11/2016@14:26:34 Getting the list of iOS devices 
21/11/2016@14:26:35 Deploying iOS test app 
21/11/2016@14:26:35 uninstalling the application 
21/11/2016@14:26:36 installing the application 
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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/931424420cf4179__897_implemented_1__3__4__5_tasks_squid48/thali05_samsung-SM-G935F.md)

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
[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/931424420cf4179__897_implemented_1__3__4__5_tasks_squid48/thali07_Huawei-Nexus 6P.md)


###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/931424420cf4179__897_implemented_1__3__4__5_tasks_squid48/iOS_IpadAir2-1.md)

[Iphone6-2](https://github.com/ThaliTester/TestResults/blob/931424420cf4179__897_implemented_1__3__4__5_tasks_squid48/iOS_Iphone6-2.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/931424420cf4179__897_implemented_1__3__4__5_tasks_squid48/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/931424420cf4179__897_implemented_1__3__4__5_tasks_squid48/iOS_Iphone6-1.md)





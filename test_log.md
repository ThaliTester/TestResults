#### Test 88123934d30a103 Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":3}}
2016-10-05 18:05:29 - INFO HttpServer: 'listening on *:3000'

2016-10-05 18:06:28 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'bac3d2a1-228d-4dfb-b2ea-0a6e96c35e97', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-05 18:06:28 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G930F''

2016-10-05 18:06:28 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'client namespace disconnect''

2016-10-05 18:06:29 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: 'a1af605a-1a56-4ab6-84d0-ea88d794e663', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-05 18:06:29 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G935F''

2016-10-05 18:06:29 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'client namespace disconnect''

2016-10-05 18:06:36 - DEBUG HttpServer: 'device presented, name: 'Huawei-Nexus 6P', uuid: '124d64df-9161-4e0a-afa6-0df8638d9c6c', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-05 18:06:36 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'Huawei-Nexus 6P''

2016-10-05 18:06:36 - INFO HttpServer: 'Socket to device name: 'Huawei-Nexus 6P' disconnected, reason: 'client namespace disconnect''

2016-10-05 18:10:29 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_88123934d30a103/test/TestServer/index.js:46:9)
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
5/10/2016@20:01:01 Getting the list of iOS devices 
5/10/2016@20:01:02 Deploying iOS test app 
5/10/2016@20:01:02 uninstalling the application 
5/10/2016@20:01:02 installing the application 
5/10/2016@20:03:43 ios: child process exited with code 254 on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
5/10/2016@20:24:21 ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
5/10/2016@20:24:21 ios: child process exited with code null on device 7ed231f0829a4ace34162e6c18308bcd995bc25a 
true

```
###Android Logs
####Node name: thali05
Console output:
```
Stopping app on  ce0616068b9f212302
Uninstalling app on  ce0616068b9f212302
Stopping app on  ce061606e320561102
Uninstalling app on  ce061606e320561102
Stopping app on  ENU7N16516000107
Uninstalling app on  ENU7N16516000107

All devices are ready!

Deploying to ce0616068b9f212302
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce0616068b9f212302

Deploying to ce061606e320561102
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce061606e320561102

Deploying to ENU7N16516000107
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ENU7N16516000107

Starting application ThaliTest on ce0616068b9f212302

Starting application ThaliTest on ce061606e320561102

Starting application ThaliTest on ENU7N16516000107

App was succesfully started on ce0616068b9f212302

App was succesfully started on ce061606e320561102

App was succesfully started on ENU7N16516000107

STOP log received from ce0616068b9f212302
Test has FAILED

STOP log received from ce061606e320561102
Test has FAILED

Device test finished on ce0616068b9f212302 
Device test finished on ce061606e320561102 
STOP log received from ENU7N16516000107
Test has FAILED

Device test finished on ENU7N16516000107 
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/88123934d30a103_Merge_wifiBasedNativeMock_into_iOS_branch_chapko/thali05_samsung-SM-G930F.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/88123934d30a103_Merge_wifiBasedNativeMock_into_iOS_branch_chapko/thali05_samsung-SM-G935F.md)

[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/88123934d30a103_Merge_wifiBasedNativeMock_into_iOS_branch_chapko/thali05_Huawei-Nexus 6P.md)


###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/88123934d30a103_Merge_wifiBasedNativeMock_into_iOS_branch_chapko/iOS_Iphone6-1.md)

[Iphone6-2](https://github.com/ThaliTester/TestResults/blob/88123934d30a103_Merge_wifiBasedNativeMock_into_iOS_branch_chapko/iOS_Iphone6-2.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/88123934d30a103_Merge_wifiBasedNativeMock_into_iOS_branch_chapko/iOS_Iphone5s-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/88123934d30a103_Merge_wifiBasedNativeMock_into_iOS_branch_chapko/iOS_IpadAir2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/88123934d30a103_Merge_wifiBasedNativeMock_into_iOS_branch_chapko/iOS_server.md)





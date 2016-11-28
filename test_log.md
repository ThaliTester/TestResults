#### Test 9510406483d1755 Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":3}}
2016-11-28 17:16:38 - INFO HttpServer: 'listening on *:3000'

2016-11-28 17:17:36 - DEBUG HttpServer: 'device presented, name: 'Huawei-Nexus 6P', uuid: 'a5ac70f0-9994-4eba-a80c-cf5f2cdc9d1b', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-11-28 17:17:36 - DEBUG TestFramework: 'device added, name: 'Huawei-Nexus 6P''

2016-11-28 17:21:38 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_9510406483d1755/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-11-28 17:21:38 - INFO HttpServer: 'Socket to device name: 'Huawei-Nexus 6P' disconnected, reason: 'undefined''


 
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
28/11/2016@18:13:13 Getting the list of iOS devices 
28/11/2016@18:13:14 Deploying iOS test app 
28/11/2016@18:13:14 uninstalling the application 
28/11/2016@18:13:14 installing the application 
28/11/2016@18:14:35 ios: child process exited with code 253 on device 2a65f58f9902a701b5c9a55b2befb18672927474 
28/11/2016@18:14:36 ios: child process exited with code 253 on device 7ed231f0829a4ace34162e6c18308bcd995bc25a 
28/11/2016@18:36:33 ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
28/11/2016@18:36:33 ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/9510406483d1755_Merge_remote-tracking_branch__origin/master__into_iOS_yaronyg/thali05_samsung-SM-G935F.md)

####Node name: thali06
Console output:
```
Stopping app on  ENU7N16516000107
Uninstalling app on  ENU7N16516000107

All devices are ready!

Deploying to ENU7N16516000107
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ENU7N16516000107

Starting application ThaliTest on ENU7N16516000107

App was succesfully started on ENU7N16516000107

STOP log received from ENU7N16516000107
Test has FAILED

Device test finished on ENU7N16516000107 
Android task is completed. [FAILED]
```
[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/9510406483d1755_Merge_remote-tracking_branch__origin/master__into_iOS_yaronyg/thali06_Huawei-Nexus 6P.md)

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
[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/9510406483d1755_Merge_remote-tracking_branch__origin/master__into_iOS_yaronyg/thali07_Huawei-Nexus 6P.md)


###iOS Logs
[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/9510406483d1755_Merge_remote-tracking_branch__origin/master__into_iOS_yaronyg/iOS_Iphone5s-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/9510406483d1755_Merge_remote-tracking_branch__origin/master__into_iOS_yaronyg/iOS_IpadAir2-1.md)

[Iphone6-2](https://github.com/ThaliTester/TestResults/blob/9510406483d1755_Merge_remote-tracking_branch__origin/master__into_iOS_yaronyg/iOS_Iphone6-2.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/9510406483d1755_Merge_remote-tracking_branch__origin/master__into_iOS_yaronyg/iOS_Iphone6-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/9510406483d1755_Merge_remote-tracking_branch__origin/master__into_iOS_yaronyg/iOS_server.md)





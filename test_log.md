#### Test 8962479671c5ab8 Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":3}}
2016-11-04 13:16:45 - INFO HttpServer: 'listening on *:3000'

2016-11-04 13:17:47 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '4e7608d9-7f3b-4cc4-afbc-9aa5c4534a31', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-11-04 13:17:47 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G935F''

2016-11-04 13:17:48 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'client namespace disconnect''

2016-11-04 13:17:56 - DEBUG HttpServer: 'device presented, name: 'Huawei-Nexus 6P', uuid: '96e480c4-9a55-4858-86f2-19ba2d1c02af', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-11-04 13:17:56 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'Huawei-Nexus 6P''

2016-11-04 13:17:56 - INFO HttpServer: 'Socket to device name: 'Huawei-Nexus 6P' disconnected, reason: 'client namespace disconnect''

2016-11-04 13:21:45 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_8962479671c5ab8/test/TestServer/index.js:46:9)
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
4/11/2016@14:12:45 Getting the list of iOS devices 
4/11/2016@14:12:46 Deploying iOS test app 
4/11/2016@14:12:46 uninstalling the application 
4/11/2016@14:12:47 installing the application 
4/11/2016@14:36:05 ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/8962479671c5ab8_Fix_issues_with_native_unit_tests_on_iOS__dersim-davaod/thali05_samsung-SM-G935F.md)

[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/8962479671c5ab8_Fix_issues_with_native_unit_tests_on_iOS__dersim-davaod/thali05_Huawei-Nexus 6P.md)

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
[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/8962479671c5ab8_Fix_issues_with_native_unit_tests_on_iOS__dersim-davaod/thali07_Huawei-Nexus 6P.md)


###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/8962479671c5ab8_Fix_issues_with_native_unit_tests_on_iOS__dersim-davaod/iOS_Iphone6-1.md)

[Iphone6-2](https://github.com/ThaliTester/TestResults/blob/8962479671c5ab8_Fix_issues_with_native_unit_tests_on_iOS__dersim-davaod/iOS_Iphone6-2.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/8962479671c5ab8_Fix_issues_with_native_unit_tests_on_iOS__dersim-davaod/iOS_Iphone5s-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/8962479671c5ab8_Fix_issues_with_native_unit_tests_on_iOS__dersim-davaod/iOS_IpadAir2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/8962479671c5ab8_Fix_issues_with_native_unit_tests_on_iOS__dersim-davaod/iOS_server.md)





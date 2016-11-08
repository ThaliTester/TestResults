#### Test 896247961682436 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":3}}
2016-11-08 16:11:37 - INFO HttpServer: 'listening on *:3000'

2016-11-08 16:12:39 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: 'bc1ac3e9-5fa2-4fa5-9572-8651ea97e6ea', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-11-08 16:12:39 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G935F''

2016-11-08 16:12:39 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'client namespace disconnect''

2016-11-08 16:12:46 - DEBUG HttpServer: 'device presented, name: 'Huawei-Nexus 6P', uuid: '051620d5-72a8-400d-954e-618866707e3e', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-11-08 16:12:46 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'Huawei-Nexus 6P''

2016-11-08 16:12:46 - INFO HttpServer: 'Socket to device name: 'Huawei-Nexus 6P' disconnected, reason: 'client namespace disconnect''


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

ios : Error: Command failed: true
8/11/2016@17:07:28 Getting the list of iOS devices 
8/11/2016@17:07:29 Deploying iOS test app 
8/11/2016@17:07:29 uninstalling the application 
8/11/2016@17:07:29 installing the application 
8/11/2016@17:10:16 ios: child process exited with code 254 on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone6-2](https://github.com/ThaliTester/TestResults/blob/896247961682436_Fix_issues_with_native_unit_tests_on_iOS__dersim-davaod/iOS_Iphone6-2.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/896247961682436_Fix_issues_with_native_unit_tests_on_iOS__dersim-davaod/iOS_Iphone5s-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/896247961682436_Fix_issues_with_native_unit_tests_on_iOS__dersim-davaod/iOS_IpadAir2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/896247961682436_Fix_issues_with_native_unit_tests_on_iOS__dersim-davaod/iOS_server.md)


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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/896247961682436_Fix_issues_with_native_unit_tests_on_iOS__dersim-davaod/thali05_samsung-SM-G935F.md)

[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/896247961682436_Fix_issues_with_native_unit_tests_on_iOS__dersim-davaod/thali05_Huawei-Nexus 6P.md)

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
[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/896247961682436_Fix_issues_with_native_unit_tests_on_iOS__dersim-davaod/thali07_Huawei-Nexus 6P.md)





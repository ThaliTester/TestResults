#### Test 896247969f429ca Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":3}}
2016-10-18 09:28:18 - INFO HttpServer: 'listening on *:3000'

2016-10-18 09:29:20 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '4293a6aa-48ba-425e-9576-02e69e97c979', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-18 09:29:20 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G935F''

2016-10-18 09:29:20 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'client namespace disconnect''

2016-10-18 09:29:21 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '42291fe2-18b7-4582-9354-d7397b0dff0f', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-18 09:29:21 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G930F''

2016-10-18 09:29:21 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'client namespace disconnect''

2016-10-18 09:29:25 - DEBUG HttpServer: 'device presented, name: 'Huawei-Nexus 6P', uuid: '9c628129-a4a7-4921-9f2d-d3126b70954f', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-18 09:29:25 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'Huawei-Nexus 6P''

2016-10-18 09:29:25 - INFO HttpServer: 'Socket to device name: 'Huawei-Nexus 6P' disconnected, reason: 'client namespace disconnect''


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

ios : Error: Command failed: true
18/10/2016@11:23:04 Getting the list of iOS devices 
18/10/2016@11:23:05 Deploying iOS test app 
18/10/2016@11:23:05 uninstalling the application 
18/10/2016@11:23:05 installing the application 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/896247969f429ca_Fix_issues_with_native_unit_tests_on_iOS__dersim-davaod/iOS_Iphone6-1.md)

[Iphone6-2](https://github.com/ThaliTester/TestResults/blob/896247969f429ca_Fix_issues_with_native_unit_tests_on_iOS__dersim-davaod/iOS_Iphone6-2.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/896247969f429ca_Fix_issues_with_native_unit_tests_on_iOS__dersim-davaod/iOS_Iphone5s-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/896247969f429ca_Fix_issues_with_native_unit_tests_on_iOS__dersim-davaod/iOS_IpadAir2-1.md)


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

STOP log received from ce061606e320561102
Test has FAILED

STOP log received from ce0616068b9f212302
Test has FAILED

Device test finished on ce061606e320561102 
Device test finished on ce0616068b9f212302 
STOP log received from ENU7N16516000107
Test has FAILED

Device test finished on ENU7N16516000107 
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/896247969f429ca_Fix_issues_with_native_unit_tests_on_iOS__dersim-davaod/thali05_samsung-SM-G930F.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/896247969f429ca_Fix_issues_with_native_unit_tests_on_iOS__dersim-davaod/thali05_samsung-SM-G935F.md)

[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/896247969f429ca_Fix_issues_with_native_unit_tests_on_iOS__dersim-davaod/thali05_Huawei-Nexus 6P.md)





#### Test 884969634f55f99 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":3}}
2016-10-18 00:58:05 - INFO HttpServer: 'listening on *:3000'

2016-10-18 00:59:07 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'cc634457-fa6b-4f71-8d8a-fb74750ec1b9', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-18 00:59:07 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G930F''

2016-10-18 00:59:07 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'client namespace disconnect''

2016-10-18 00:59:08 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: 'c7707801-3770-4d7d-abe3-54cb3f9bc87e', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-18 00:59:08 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G935F''

2016-10-18 00:59:08 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'client namespace disconnect''

2016-10-18 00:59:12 - DEBUG HttpServer: 'device presented, name: 'Huawei-Nexus 6P', uuid: '937a65ab-9abb-4f0b-b8b9-81f835ad7bc8', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-18 00:59:12 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'Huawei-Nexus 6P''

2016-10-18 00:59:12 - INFO HttpServer: 'Socket to device name: 'Huawei-Nexus 6P' disconnected, reason: 'client namespace disconnect''


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

ios : Error: Command failed: true
18/10/2016@02:53:05 Getting the list of iOS devices 
18/10/2016@02:53:06 Deploying iOS test app 
18/10/2016@02:53:06 uninstalling the application 
18/10/2016@02:53:07 installing the application 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/884969634f55f99_iOS_enabled_mock_and_low_level_tests_yaronyg/iOS_Iphone6-1.md)

[Iphone6-2](https://github.com/ThaliTester/TestResults/blob/884969634f55f99_iOS_enabled_mock_and_low_level_tests_yaronyg/iOS_Iphone6-2.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/884969634f55f99_iOS_enabled_mock_and_low_level_tests_yaronyg/iOS_Iphone5s-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/884969634f55f99_iOS_enabled_mock_and_low_level_tests_yaronyg/iOS_IpadAir2-1.md)


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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/884969634f55f99_iOS_enabled_mock_and_low_level_tests_yaronyg/thali05_samsung-SM-G930F.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/884969634f55f99_iOS_enabled_mock_and_low_level_tests_yaronyg/thali05_samsung-SM-G935F.md)

[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/884969634f55f99_iOS_enabled_mock_and_low_level_tests_yaronyg/thali05_Huawei-Nexus 6P.md)





#### Test 884969638ec0a5b Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":3}}
2016-10-15 00:18:47 - INFO HttpServer: 'listening on *:3000'

2016-10-15 00:19:51 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '37189af5-1b92-49ab-8131-be06ec4b544d', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-15 00:19:51 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G935F''

2016-10-15 00:19:51 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'client namespace disconnect''

2016-10-15 00:19:52 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'a34490be-18d8-45f7-b549-61f16e2e16da', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-15 00:19:52 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G930F''

2016-10-15 00:19:53 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'client namespace disconnect''

2016-10-15 00:19:59 - DEBUG HttpServer: 'device presented, name: 'Huawei-Nexus 6P', uuid: '7bc1552b-b9e5-4f0d-af8d-bc5dbac3a6cb', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-15 00:19:59 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'Huawei-Nexus 6P''

2016-10-15 00:19:59 - INFO HttpServer: 'Socket to device name: 'Huawei-Nexus 6P' disconnected, reason: 'client namespace disconnect''


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

ios : Error: Command failed: true
15/10/2016@02:13:52 Getting the list of iOS devices 
15/10/2016@02:13:53 Deploying iOS test app 
15/10/2016@02:13:53 uninstalling the application 
15/10/2016@02:13:53 installing the application 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/884969638ec0a5b_iOS_enabled_mock_and_low_level_tests_yaronyg/iOS_Iphone6-1.md)

[Iphone6-2](https://github.com/ThaliTester/TestResults/blob/884969638ec0a5b_iOS_enabled_mock_and_low_level_tests_yaronyg/iOS_Iphone6-2.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/884969638ec0a5b_iOS_enabled_mock_and_low_level_tests_yaronyg/iOS_Iphone5s-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/884969638ec0a5b_iOS_enabled_mock_and_low_level_tests_yaronyg/iOS_IpadAir2-1.md)


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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/884969638ec0a5b_iOS_enabled_mock_and_low_level_tests_yaronyg/thali05_samsung-SM-G930F.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/884969638ec0a5b_iOS_enabled_mock_and_low_level_tests_yaronyg/thali05_samsung-SM-G935F.md)

[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/884969638ec0a5b_iOS_enabled_mock_and_low_level_tests_yaronyg/thali05_Huawei-Nexus 6P.md)





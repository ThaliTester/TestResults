#### Test 88496963915c2f2 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":3}}
2016-10-07 20:10:13 - INFO HttpServer: 'listening on *:3000'

2016-10-07 20:11:08 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '57b76647-0d83-4277-afb3-3004ce6316fe', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-07 20:11:08 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G930F''

2016-10-07 20:11:08 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'client namespace disconnect''

2016-10-07 20:11:10 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '8e11c68e-13c2-4b23-bcbe-aa8ce3fdb6e9', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-07 20:11:10 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G935F''

2016-10-07 20:11:10 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'client namespace disconnect''

2016-10-07 20:11:25 - DEBUG HttpServer: 'device presented, name: 'Huawei-Nexus 6P', uuid: 'eb147001-54a3-4c51-af31-d0db57c39b2e', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-07 20:11:25 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'Huawei-Nexus 6P''

2016-10-07 20:11:25 - INFO HttpServer: 'Socket to device name: 'Huawei-Nexus 6P' disconnected, reason: 'client namespace disconnect''


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

ios : Error: Command failed: true
7/10/2016@22:05:27 Getting the list of iOS devices 
7/10/2016@22:05:28 Deploying iOS test app 
7/10/2016@22:05:28 uninstalling the application 
7/10/2016@22:05:29 installing the application 
7/10/2016@22:08:09 ios: child process exited with code 254 on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/88496963915c2f2_iOS_enabled_mock_and_low_level_tests_yaronyg/iOS_Iphone6-1.md)

[Iphone6-2](https://github.com/ThaliTester/TestResults/blob/88496963915c2f2_iOS_enabled_mock_and_low_level_tests_yaronyg/iOS_Iphone6-2.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/88496963915c2f2_iOS_enabled_mock_and_low_level_tests_yaronyg/iOS_Iphone5s-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/88496963915c2f2_iOS_enabled_mock_and_low_level_tests_yaronyg/iOS_IpadAir2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/88496963915c2f2_iOS_enabled_mock_and_low_level_tests_yaronyg/iOS_server.md)


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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/88496963915c2f2_iOS_enabled_mock_and_low_level_tests_yaronyg/thali05_samsung-SM-G930F.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/88496963915c2f2_iOS_enabled_mock_and_low_level_tests_yaronyg/thali05_samsung-SM-G935F.md)

[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/88496963915c2f2_iOS_enabled_mock_and_low_level_tests_yaronyg/thali05_Huawei-Nexus 6P.md)





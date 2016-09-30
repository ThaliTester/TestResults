#### Test 87463757ce3bfc1 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-09-30 12:02:28 - INFO HttpServer: 'listening on *:3000'

2016-09-30 12:04:18 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '23944751-890f-447d-840d-7f5cf08d7cb8', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-09-30 12:04:18 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G930F''

2016-09-30 12:04:18 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'client namespace disconnect''

2016-09-30 12:04:18 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: 'bb41be65-e58b-4651-8ef0-08c13d53e9ea', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-09-30 12:04:18 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G935F''

2016-09-30 12:04:18 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'client namespace disconnect''

2016-09-30 12:04:25 - DEBUG HttpServer: 'device presented, name: 'Huawei-Nexus 6P', uuid: '19ba88a3-aec8-4396-8a7f-c498b570549a', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-09-30 12:04:25 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'Huawei-Nexus 6P''

2016-09-30 12:04:26 - INFO HttpServer: 'Socket to device name: 'Huawei-Nexus 6P' disconnected, reason: 'client namespace disconnect''


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

android : No Error
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
Test has SUCCEED

STOP log received from ce061606e320561102
Test has SUCCEED

Device test finished on ce0616068b9f212302 
Device test finished on ce061606e320561102 
STOP log received from ENU7N16516000107
Test has SUCCEED

Device test finished on ENU7N16516000107 
Android task is completed. [SUCCESS]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/87463757ce3bfc1_Fix_wrong_test_report_results_for_native_and_node_tests_czyzm/thali05_samsung-SM-G930F.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/87463757ce3bfc1_Fix_wrong_test_report_results_for_native_and_node_tests_czyzm/thali05_samsung-SM-G935F.md)

[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/87463757ce3bfc1_Fix_wrong_test_report_results_for_native_and_node_tests_czyzm/thali05_Huawei-Nexus 6P.md)



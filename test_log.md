#### Test 87966432114c2fe Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-10-05 09:49:35 - INFO Server: 'listening on *:3000'

2016-10-05 09:51:25 - DEBUG Server: 'client connected'

2016-10-05 09:51:25 - DEBUG Socket: 'we are waiting for event: 'sync''

2016-10-05 09:51:25 - DEBUG Server: 'device presented, name: 'samsung-SM-G930F', uuid: '5d066113-61a6-4847-b9ea-1a1618c3c81b', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-05 09:51:25 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G930F''

2016-10-05 09:51:25 - DEBUG Socket: 'we are waiting for event: 'disqualify_confirmed''

2016-10-05 09:51:25 - DEBUG Socket: 'we are emitting data for event: 'disqualify', data: '{"uuid":"34b9359c-e94b-40bd-a4f6-54edaecf6007","content":"Native unit tests failed"}''

2016-10-05 09:51:26 - DEBUG Server: 'client connected'

2016-10-05 09:51:26 - DEBUG Socket: 'we are waiting for event: 'sync''

2016-10-05 09:51:26 - DEBUG Server: 'device presented, name: 'samsung-SM-G935F', uuid: 'c734425c-11cb-4fc5-b097-6eae968d34fa', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-05 09:51:26 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G935F''

2016-10-05 09:51:26 - DEBUG Socket: 'we are waiting for event: 'disqualify_confirmed''

2016-10-05 09:51:26 - DEBUG Socket: 'we are emitting data for event: 'disqualify', data: '{"uuid":"8ed1f2e7-452b-4174-b9cb-65766323ea2d","content":"Native unit tests failed"}''

2016-10-05 09:51:36 - DEBUG Server: 'client connected'

2016-10-05 09:51:36 - DEBUG Socket: 'we are waiting for event: 'sync''

2016-10-05 09:51:36 - DEBUG Server: 'device presented, name: 'Huawei-Nexus 6P', uuid: '7b9f59cb-d4a4-4b31-b551-246a31fbf4ad', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-05 09:51:36 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'Huawei-Nexus 6P''

2016-10-05 09:51:36 - DEBUG Socket: 'we are waiting for event: 'disqualify_confirmed''

2016-10-05 09:51:36 - DEBUG Socket: 'we are emitting data for event: 'disqualify', data: '{"uuid":"a3d2995d-570f-45ef-a769-8ff119d6fd61","content":"Native unit tests failed"}''


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/87966432114c2fe_Do_not_merge__CI_test_andrew-aladev/thali05_samsung-SM-G930F.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/87966432114c2fe_Do_not_merge__CI_test_andrew-aladev/thali05_samsung-SM-G935F.md)

[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/87966432114c2fe_Do_not_merge__CI_test_andrew-aladev/thali05_Huawei-Nexus 6P.md)





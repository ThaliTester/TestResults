#### Test 8796643214f598b Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-10-05 12:43:32 - INFO Server: 'listening on *:3000'

2016-10-05 12:45:17 - DEBUG Server: 'client connected'

2016-10-05 12:45:17 - DEBUG Socket: 'we are waiting for event: 'sync''

2016-10-05 12:45:17 - DEBUG Server: 'device presented, name: 'samsung-SM-G930F', uuid: '25c731b2-068c-4e30-95d5-bce3da69089d', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-05 12:45:17 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G930F''

2016-10-05 12:45:17 - DEBUG Socket: 'we are waiting for event: 'disqualify_confirmed''

2016-10-05 12:45:17 - DEBUG Socket: 'we are emitting data for event: 'disqualify', data: '{"uuid":"327f48bd-44f2-42a0-b86a-045053f11fad","content":"Native unit tests failed"}''

2016-10-05 12:45:18 - DEBUG Server: 'client connected'

2016-10-05 12:45:18 - DEBUG Socket: 'we are waiting for event: 'sync''

2016-10-05 12:45:18 - DEBUG Server: 'device presented, name: 'samsung-SM-G935F', uuid: 'edc646d3-9e35-493c-9cdc-7862a05edeaf', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-05 12:45:18 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G935F''

2016-10-05 12:45:18 - DEBUG Socket: 'we are waiting for event: 'disqualify_confirmed''

2016-10-05 12:45:18 - DEBUG Socket: 'we are emitting data for event: 'disqualify', data: '{"uuid":"935d6bef-45bc-44c2-b500-cca59b128413","content":"Native unit tests failed"}''

2016-10-05 12:45:28 - DEBUG Server: 'client connected'

2016-10-05 12:45:29 - DEBUG Socket: 'we are waiting for event: 'sync''

2016-10-05 12:45:29 - DEBUG Server: 'device presented, name: 'Huawei-Nexus 6P', uuid: '28aba73d-1a74-49df-a686-86219bc726e3', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-05 12:45:29 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'Huawei-Nexus 6P''

2016-10-05 12:45:29 - DEBUG Socket: 'we are waiting for event: 'disqualify_confirmed''

2016-10-05 12:45:29 - DEBUG Socket: 'we are emitting data for event: 'disqualify', data: '{"uuid":"1587be44-251a-4b40-ba0e-8a80de90170a","content":"Native unit tests failed"}''


 
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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/8796643214f598b_Do_not_merge__CI_test_andrew-aladev/thali05_samsung-SM-G930F.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/8796643214f598b_Do_not_merge__CI_test_andrew-aladev/thali05_samsung-SM-G935F.md)

[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/8796643214f598b_Do_not_merge__CI_test_andrew-aladev/thali05_Huawei-Nexus 6P.md)





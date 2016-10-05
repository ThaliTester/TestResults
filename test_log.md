#### Test 87966432bf29957 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-10-05 08:15:54 - INFO Server: 'listening on *:3000'

2016-10-05 08:17:45 - DEBUG Server: 'client connected'

2016-10-05 08:17:45 - DEBUG Socket: 'we are waiting for event: 'sync''

2016-10-05 08:17:45 - DEBUG Server: 'device presented, name: 'samsung-SM-G930F', uuid: 'e49ba485-84b8-40bb-9aaf-0a6a3625e7c3', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-05 08:17:45 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G930F''

2016-10-05 08:17:45 - DEBUG Socket: 'we are waiting for event: 'disqualify_confirmed''

2016-10-05 08:17:45 - DEBUG Socket: 'we are emitting data for event: 'disqualify', data: '{"uuid":"fe34f92a-0081-4894-b4d6-a36d40c814b0","content":"Native unit tests failed"}''

2016-10-05 08:17:46 - DEBUG Server: 'client connected'

2016-10-05 08:17:46 - DEBUG Socket: 'we are waiting for event: 'sync''

2016-10-05 08:17:46 - DEBUG Server: 'device presented, name: 'samsung-SM-G935F', uuid: '8aa7a03a-f49e-40b7-8eef-52eb8415ae1f', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-05 08:17:46 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G935F''

2016-10-05 08:17:46 - DEBUG Socket: 'we are waiting for event: 'disqualify_confirmed''

2016-10-05 08:17:46 - DEBUG Socket: 'we are emitting data for event: 'disqualify', data: '{"uuid":"10afdb90-57f6-4c68-8972-c9606e17a9f8","content":"Native unit tests failed"}''

2016-10-05 08:17:54 - DEBUG Server: 'client connected'

2016-10-05 08:17:54 - DEBUG Socket: 'we are waiting for event: 'sync''

2016-10-05 08:17:54 - DEBUG Server: 'device presented, name: 'Huawei-Nexus 6P', uuid: 'e714f967-2c59-413e-a0fd-ff56273e7938', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-05 08:17:54 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'Huawei-Nexus 6P''

2016-10-05 08:17:54 - DEBUG Socket: 'we are waiting for event: 'disqualify_confirmed''

2016-10-05 08:17:54 - DEBUG Socket: 'we are emitting data for event: 'disqualify', data: '{"uuid":"f9594504-c534-40de-8989-9a5696209121","content":"Native unit tests failed"}''


 
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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/87966432bf29957_Do_not_merge__CI_test_andrew-aladev/thali05_samsung-SM-G930F.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/87966432bf29957_Do_not_merge__CI_test_andrew-aladev/thali05_samsung-SM-G935F.md)

[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/87966432bf29957_Do_not_merge__CI_test_andrew-aladev/thali05_Huawei-Nexus 6P.md)





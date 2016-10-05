#### Test 879664320d5b49a Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-10-05 17:50:51 - INFO Server: 'listening on *:3000'

2016-10-05 17:52:37 - DEBUG Server: 'client connected'

2016-10-05 17:52:37 - DEBUG Socket: 'we are waiting for event: 'sync''

2016-10-05 17:52:37 - DEBUG Server: 'device presented, name: 'samsung-SM-G930F', uuid: 'f5f0605b-2673-4af8-8c79-0af2c04bc560', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-05 17:52:37 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G930F''

2016-10-05 17:52:37 - DEBUG Socket: 'we are waiting for event: 'disqualify_confirmed''

2016-10-05 17:52:37 - DEBUG Socket: 'we are emitting data for event: 'disqualify', data: '{"uuid":"039294e6-68e4-4ed5-8bfc-de255d847ad8","content":"Native unit tests failed"}''

2016-10-05 17:52:37 - DEBUG Server: 'client connected'

2016-10-05 17:52:37 - DEBUG Socket: 'we are waiting for event: 'sync''

2016-10-05 17:52:37 - DEBUG Server: 'device presented, name: 'samsung-SM-G935F', uuid: 'd71528d8-accd-40d1-b0ca-452abcdce79e', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-05 17:52:37 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G935F''

2016-10-05 17:52:38 - DEBUG Socket: 'we are waiting for event: 'disqualify_confirmed''

2016-10-05 17:52:38 - DEBUG Socket: 'we are emitting data for event: 'disqualify', data: '{"uuid":"1eb5cc4b-d0d0-4237-860d-43e8783bd409","content":"Native unit tests failed"}''

2016-10-05 17:52:44 - DEBUG Server: 'client connected'

2016-10-05 17:52:44 - DEBUG Socket: 'we are waiting for event: 'sync''

2016-10-05 17:52:44 - DEBUG Server: 'device presented, name: 'Huawei-Nexus 6P', uuid: 'b9be0bf5-4ff5-4a6d-9628-447f440b2514', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-05 17:52:44 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'Huawei-Nexus 6P''

2016-10-05 17:52:44 - DEBUG Socket: 'we are waiting for event: 'disqualify_confirmed''

2016-10-05 17:52:44 - DEBUG Socket: 'we are emitting data for event: 'disqualify', data: '{"uuid":"f4131821-198c-48fc-812b-350446cacd7a","content":"Native unit tests failed"}''


 
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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/879664320d5b49a_Do_not_merge__CI_test_andrew-aladev/thali05_samsung-SM-G930F.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/879664320d5b49a_Do_not_merge__CI_test_andrew-aladev/thali05_samsung-SM-G935F.md)

[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/879664320d5b49a_Do_not_merge__CI_test_andrew-aladev/thali05_Huawei-Nexus 6P.md)





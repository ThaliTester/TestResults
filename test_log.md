#### Test 87966432c4e001b Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-10-05 17:33:58 - INFO Server: 'listening on *:3000'

2016-10-05 17:35:40 - DEBUG Server: 'client connected'

2016-10-05 17:35:40 - DEBUG Socket: 'we are waiting for event: 'sync''

2016-10-05 17:35:40 - DEBUG Server: 'device presented, name: 'samsung-SM-G930F', uuid: '04be8ff2-7469-4577-a185-b1f81743d2e8', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-05 17:35:40 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G930F''

2016-10-05 17:35:40 - DEBUG Socket: 'we are waiting for event: 'disqualify_confirmed''

2016-10-05 17:35:40 - DEBUG Socket: 'we are emitting data for event: 'disqualify', data: '{"uuid":"09f2c94d-f5a0-4127-9cfc-a92188b60902","content":"Native unit tests failed"}''

2016-10-05 17:35:48 - DEBUG Server: 'client connected'

2016-10-05 17:35:48 - DEBUG Socket: 'we are waiting for event: 'sync''

2016-10-05 17:35:48 - DEBUG Server: 'device presented, name: 'samsung-SM-G935F', uuid: '775f059a-5c4a-4b23-b1ae-b9b35672e841', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-05 17:35:48 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G935F''

2016-10-05 17:35:48 - DEBUG Socket: 'we are waiting for event: 'disqualify_confirmed''

2016-10-05 17:35:48 - DEBUG Socket: 'we are emitting data for event: 'disqualify', data: '{"uuid":"9b526e88-5562-4815-b007-3f26524aff2f","content":"Native unit tests failed"}''

2016-10-05 17:35:58 - DEBUG Server: 'client connected'

2016-10-05 17:35:58 - DEBUG Socket: 'we are waiting for event: 'sync''

2016-10-05 17:35:58 - DEBUG Server: 'device presented, name: 'Huawei-Nexus 6P', uuid: '1c46b9e4-388d-427c-bcf9-f6cd8721d407', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-05 17:35:58 - DEBUG TestFramework: 'device added, name: 'Huawei-Nexus 6P''

2016-10-05 17:38:58 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_87966432c4e001b/test/TestServer/index.js:48:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!
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

Device test finished on ce0616068b9f212302 
STOP log received from ce061606e320561102
Test has FAILED

Device test finished on ce061606e320561102 
Error! Unexpected exit on device ENU7N16516000107 app:com.test.thalitest code:null 
Child process exited with code null on device ENU7N16516000107
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/87966432c4e001b_Do_not_merge__CI_test_andrew-aladev/thali05_samsung-SM-G930F.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/87966432c4e001b_Do_not_merge__CI_test_andrew-aladev/thali05_samsung-SM-G935F.md)

[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/87966432c4e001b_Do_not_merge__CI_test_andrew-aladev/thali05_Huawei-Nexus 6P.md)





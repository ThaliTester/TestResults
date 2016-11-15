#### Test 937391739bc1cf0 Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-11-15 13:06:11 - INFO HttpServer: 'listening on *:3000'

2016-11-15 13:07:49 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '8343fae3-7829-4456-840b-899cbe021c7a', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-11-15 13:07:49 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G935F''

2016-11-15 13:07:49 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'client namespace disconnect''

2016-11-15 13:07:58 - DEBUG HttpServer: 'device presented, name: 'Huawei-Nexus 6P', uuid: 'e3ee865f-ef00-4fed-baca-56629c156fc3', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-11-15 13:07:58 - DEBUG TestFramework: 'device added, name: 'Huawei-Nexus 6P''

2016-11-15 13:11:11 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_937391739bc1cf0/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-11-15 13:11:11 - INFO HttpServer: 'Socket to device name: 'Huawei-Nexus 6P' disconnected, reason: 'undefined''


 
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
Stopping app on  ce061606e320561102
Uninstalling app on  ce061606e320561102
Stopping app on  ENU7N16516000107
Uninstalling app on  ENU7N16516000107

All devices are ready!

Deploying to ce061606e320561102
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce061606e320561102

Deploying to ENU7N16516000107
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ENU7N16516000107

Starting application ThaliTest on ce061606e320561102

Starting application ThaliTest on ENU7N16516000107

App was succesfully started on ce061606e320561102

App was succesfully started on ENU7N16516000107

STOP log received from ce061606e320561102
Test has FAILED

Device test finished on ce061606e320561102 
STOP log received from ENU7N16516000107
Test has FAILED

Device test finished on ENU7N16516000107 
Android task is completed. [FAILED]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/937391739bc1cf0_DONT_MERGE_-_test_CI_larryonoff/thali05_samsung-SM-G935F.md)

[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/937391739bc1cf0_DONT_MERGE_-_test_CI_larryonoff/thali05_Huawei-Nexus 6P.md)

####Node name: thali07
Console output:
```
Stopping app on  ENU7N16516000121
Uninstalling app on  ENU7N16516000121

All devices are ready!

Deploying to ENU7N16516000121
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ENU7N16516000121

Starting application ThaliTest on ENU7N16516000121

App was succesfully started on ENU7N16516000121

Error! Unexpected exit on device ENU7N16516000121 app:com.test.thalitest code:null 
Child process exited with code null on device ENU7N16516000121
Android task is completed. [FAILED]
```
[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/937391739bc1cf0_DONT_MERGE_-_test_CI_larryonoff/thali07_Huawei-Nexus 6P.md)





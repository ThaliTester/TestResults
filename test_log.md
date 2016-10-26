#### Test 909164151d8f644 Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-10-26 20:43:23 - INFO HttpServer: 'listening on *:3000'

2016-10-26 20:45:01 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: 'f7e63f0a-9583-475e-bd1a-b509bdc1ca6f', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-26 20:45:01 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2016-10-26 20:45:11 - DEBUG HttpServer: 'device presented, name: 'Huawei-Nexus 6P', uuid: '869ca1d4-a23b-40a1-8fb5-85ea15b1bb31', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-26 20:45:11 - DEBUG TestFramework: 'device added, name: 'Huawei-Nexus 6P''

2016-10-26 20:48:23 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_909164151d8f644/test/TestServer/index.js:46:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-26 20:48:23 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''

2016-10-26 20:48:23 - INFO HttpServer: 'Socket to device name: 'Huawei-Nexus 6P' disconnected, reason: 'undefined''


 
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

STOP log received from ENU7N16516000107
Test has FAILED

STOP log received from ce061606e320561102
Test has FAILED

Device test finished on ENU7N16516000107 
Device test finished on ce061606e320561102 
Android task is completed. [FAILED]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/909164151d8f644_Testing_for_corrupt_data_yaronyg/thali05_samsung-SM-G935F.md)

[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/909164151d8f644_Testing_for_corrupt_data_yaronyg/thali05_Huawei-Nexus 6P.md)

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

STOP log received from ENU7N16516000121
Test has FAILED

Device test finished on ENU7N16516000121 
Android task is completed. [FAILED]
```
[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/909164151d8f644_Testing_for_corrupt_data_yaronyg/thali07_Huawei-Nexus 6P.md)





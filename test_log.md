#### Test 89812065450ef7b Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":3}}
2016-10-18 13:42:19 - INFO HttpServer: 'listening on *:3000'

2016-10-18 13:43:21 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'e3a9ebfe-439d-4459-8c88-2d81860f1a3c', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-18 13:43:21 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G930F''

2016-10-18 13:43:21 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'client namespace disconnect''

2016-10-18 13:43:21 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: 'f906cbbb-174e-4308-b991-e21c3700e1a1', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-18 13:43:21 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G935F''

2016-10-18 13:43:21 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'client namespace disconnect''

2016-10-18 13:43:26 - DEBUG HttpServer: 'device presented, name: 'Huawei-Nexus 6P', uuid: '6e5882c2-75d8-4abf-ab71-0e668e6bdc8b', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-18 13:43:26 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'Huawei-Nexus 6P''

2016-10-18 13:43:26 - INFO HttpServer: 'Socket to device name: 'Huawei-Nexus 6P' disconnected, reason: 'client namespace disconnect''

2016-10-18 13:47:19 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_89812065450ef7b/test/TestServer/index.js:46:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m



ios : Error: Command failed: true
18/10/2016@15:37:21 Getting the list of iOS devices 
18/10/2016@15:37:22 Deploying iOS test app 
18/10/2016@15:37:22 uninstalling the application 
18/10/2016@15:37:23 installing the application 
18/10/2016@16:00:41 ios: child process exited with code null on device 7ed231f0829a4ace34162e6c18308bcd995bc25a 
true

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


Couldn't parse the device logs for thali05
````Error: ENOENT, no such file or directory '/Users/thali/Github/CI/TMP/89812065450ef7b_skip_`Connect_port_dies_if_not_connected_to_in_time`_for_iOS_baydet/thali05_samsung-SM-G930F.md'```

###iOS Logs


Couldn't parse the iOS logs
````Error: ENOENT, no such file or directory '/Users/thali/Github/CI/TMP/89812065450ef7b_skip_`Connect_port_dies_if_not_connected_to_in_time`_for_iOS_baydet/iOS_Iphone6-1.md'```




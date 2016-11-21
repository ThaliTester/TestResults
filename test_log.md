#### Test 946263757280694 Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":2}}
2016-11-21 15:24:53 - INFO HttpServer: 'listening on *:3000'

2016-11-21 15:24:54 - DEBUG HttpServer: 'device presented, name: 'Apple-Iphone6-2', uuid: '3efde934-41fe-4132-bec4-aaf480eaed2d', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-11-21 15:24:54 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'Apple-Iphone6-2''

2016-11-21 15:24:54 - INFO HttpServer: 'Socket to device name: 'Apple-Iphone6-2' disconnected, reason: 'client namespace disconnect''

2016-11-21 15:24:55 - DEBUG HttpServer: 'device presented, name: 'Apple-Iphone5s-1', uuid: 'd7635cc2-3536-40e9-8a19-1f338541f5e0', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-11-21 15:24:55 - DEBUG TestFramework: 'device added, name: 'Apple-Iphone5s-1''

2016-11-21 15:24:56 - DEBUG HttpServer: 'device presented, name: 'Apple-Iphone5s-1', uuid: 'd7635cc2-3536-40e9-8a19-1f338541f5e0', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-11-21 15:24:56 - INFO TestFramework: 'updating existing device, name: 'Apple-Iphone5s-1', uuid: 'd7635cc2-3536-40e9-8a19-1f338541f5e0', platformName: 'ios''

2016-11-21 15:25:54 - DEBUG HttpServer: 'device presented, name: 'Huawei-Nexus 6P', uuid: 'f869cbee-c1eb-44aa-a750-f2e42ef48825', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-11-21 15:25:54 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'Huawei-Nexus 6P''

2016-11-21 15:25:54 - INFO HttpServer: 'Socket to device name: 'Huawei-Nexus 6P' disconnected, reason: 'client namespace disconnect''

2016-11-21 15:29:53 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_946263757280694/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-11-21 15:29:53 - INFO HttpServer: 'Socket to device name: 'Apple-Iphone5s-1' disconnected, reason: 'undefined''


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m



ios : Error: Command failed: true
21/11/2016@16:21:40 Getting the list of iOS devices 
21/11/2016@16:21:41 Deploying iOS test app 
21/11/2016@16:21:41 uninstalling the application 
21/11/2016@16:21:41 installing the application 
21/11/2016@16:45:00 ios: child process exited with code null on device 7ed231f0829a4ace34162e6c18308bcd995bc25a 
true

```
###Android Logs
####Node name: thali05
Console output:
```
Stopping app on  ce061606e320561102
Uninstalling app on  ce061606e320561102

All devices are ready!

Deploying to ce061606e320561102
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce061606e320561102

Starting application ThaliTest on ce061606e320561102

App was succesfully started on ce061606e320561102

STOP log received from ce061606e320561102
Test has FAILED

Device test finished on ce061606e320561102 
Android task is completed. [FAILED]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/946263757280694__897_complete_squid48/thali05_samsung-SM-G935F.md)

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
[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/946263757280694__897_complete_squid48/thali07_Huawei-Nexus 6P.md)


###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/946263757280694__897_complete_squid48/iOS_IpadAir2-1.md)

[Iphone6-2](https://github.com/ThaliTester/TestResults/blob/946263757280694__897_complete_squid48/iOS_Iphone6-2.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/946263757280694__897_complete_squid48/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/946263757280694__897_complete_squid48/iOS_Iphone6-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/946263757280694__897_complete_squid48/iOS_server.md)





#### Test 88838102571b7ae Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":3}}
2016-10-12 13:31:44 - INFO HttpServer: 'listening on *:3000'

2016-10-12 13:32:43 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '63136dc3-3e78-4d05-9cf1-01223570daea', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-12 13:32:43 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G930F''

2016-10-12 13:32:43 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'client namespace disconnect''

2016-10-12 13:32:44 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '828435fd-b60a-41a5-b34f-71a68ee7063b', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-12 13:32:44 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G935F''

2016-10-12 13:32:44 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'client namespace disconnect''

2016-10-12 13:32:51 - DEBUG HttpServer: 'device presented, name: 'Huawei-Nexus 6P', uuid: '0488b0c7-b743-45bf-9d4b-f66613f210ce', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-12 13:32:51 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'Huawei-Nexus 6P''

2016-10-12 13:32:51 - INFO HttpServer: 'Socket to device name: 'Huawei-Nexus 6P' disconnected, reason: 'client namespace disconnect''

2016-10-12 13:36:44 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_88838102571b7ae/test/TestServer/index.js:46:9)
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
12/10/2016@15:27:22 Getting the list of iOS devices 
12/10/2016@15:27:23 Deploying iOS test app 
12/10/2016@15:27:23 uninstalling the application 
12/10/2016@15:27:24 installing the application 
12/10/2016@15:50:42 ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/88838102571b7ae_MPCF_TCP/IP_binding_dersim-davaod/thali05_samsung-SM-G930F.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/88838102571b7ae_MPCF_TCP/IP_binding_dersim-davaod/thali05_samsung-SM-G935F.md)

[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/88838102571b7ae_MPCF_TCP/IP_binding_dersim-davaod/thali05_Huawei-Nexus 6P.md)


###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/88838102571b7ae_MPCF_TCP/IP_binding_dersim-davaod/iOS_Iphone6-1.md)

[Iphone6-2](https://github.com/ThaliTester/TestResults/blob/88838102571b7ae_MPCF_TCP/IP_binding_dersim-davaod/iOS_Iphone6-2.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/88838102571b7ae_MPCF_TCP/IP_binding_dersim-davaod/iOS_Iphone5s-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/88838102571b7ae_MPCF_TCP/IP_binding_dersim-davaod/iOS_IpadAir2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/88838102571b7ae_MPCF_TCP/IP_binding_dersim-davaod/iOS_server.md)





#### Test 89808901ab206e8 Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":3}}
2016-10-18 13:17:28 - INFO HttpServer: 'listening on *:3000'

2016-10-18 13:18:31 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '3a1bfb0a-a42e-4062-bdfd-a82400bcced0', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-18 13:18:31 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G930F''

2016-10-18 13:18:31 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'client namespace disconnect''

2016-10-18 13:18:31 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '6f2c5537-fb79-4dc6-965c-12dbab15a2d8', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-18 13:18:31 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G935F''

2016-10-18 13:18:31 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'client namespace disconnect''

2016-10-18 13:18:36 - DEBUG HttpServer: 'device presented, name: 'Huawei-Nexus 6P', uuid: 'c5eaaf94-f298-4f0b-81c6-ed211099a40d', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-18 13:18:36 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'Huawei-Nexus 6P''

2016-10-18 13:18:36 - INFO HttpServer: 'Socket to device name: 'Huawei-Nexus 6P' disconnected, reason: 'client namespace disconnect''

2016-10-18 13:22:28 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_89808901ab206e8/test/TestServer/index.js:46:9)
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
18/10/2016@15:12:31 Getting the list of iOS devices 
18/10/2016@15:12:32 Deploying iOS test app 
18/10/2016@15:12:32 uninstalling the application 
18/10/2016@15:12:33 installing the application 
18/10/2016@15:35:51 ios: child process exited with code null on device 7ed231f0829a4ace34162e6c18308bcd995bc25a 
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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/89808901ab206e8_Fixing_testStopListeningForConnectionsReleasesPort_dersim-davaod/thali05_samsung-SM-G930F.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/89808901ab206e8_Fixing_testStopListeningForConnectionsReleasesPort_dersim-davaod/thali05_samsung-SM-G935F.md)

[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/89808901ab206e8_Fixing_testStopListeningForConnectionsReleasesPort_dersim-davaod/thali05_Huawei-Nexus 6P.md)


###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/89808901ab206e8_Fixing_testStopListeningForConnectionsReleasesPort_dersim-davaod/iOS_Iphone6-1.md)

[Iphone6-2](https://github.com/ThaliTester/TestResults/blob/89808901ab206e8_Fixing_testStopListeningForConnectionsReleasesPort_dersim-davaod/iOS_Iphone6-2.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/89808901ab206e8_Fixing_testStopListeningForConnectionsReleasesPort_dersim-davaod/iOS_Iphone5s-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/89808901ab206e8_Fixing_testStopListeningForConnectionsReleasesPort_dersim-davaod/iOS_IpadAir2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/89808901ab206e8_Fixing_testStopListeningForConnectionsReleasesPort_dersim-davaod/iOS_server.md)





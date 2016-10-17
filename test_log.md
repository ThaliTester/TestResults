#### Test 894433142f26427 Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":3}}
2016-10-17 10:56:01 - INFO HttpServer: 'listening on *:3000'

2016-10-17 10:56:55 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '0ee0ee85-e057-49ca-8272-7421f05452e9', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-17 10:56:55 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G930F''

2016-10-17 10:56:55 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'client namespace disconnect''

2016-10-17 10:56:56 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: 'db8123ac-8dca-49c4-88b0-1cb5f700677c', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-17 10:56:56 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G935F''

2016-10-17 10:56:57 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'client namespace disconnect''

2016-10-17 10:57:01 - DEBUG HttpServer: 'device presented, name: 'Huawei-Nexus 6P', uuid: 'db67a0dc-8aea-484d-af1a-747be6a08efd', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-17 10:57:01 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'Huawei-Nexus 6P''

2016-10-17 10:57:01 - INFO HttpServer: 'Socket to device name: 'Huawei-Nexus 6P' disconnected, reason: 'client namespace disconnect''

2016-10-17 11:01:01 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_894433142f26427/test/TestServer/index.js:46:9)
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
17/10/2016@12:51:01 Getting the list of iOS devices 
17/10/2016@12:51:02 Deploying iOS test app 
17/10/2016@12:51:02 uninstalling the application 
17/10/2016@12:51:02 installing the application 
17/10/2016@13:14:21 ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
17/10/2016@13:14:21 ios: child process exited with code null on device 7ed231f0829a4ace34162e6c18308bcd995bc25a 
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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/894433142f26427__899_Update_thaliMobile_for_WiFi_and_Android__peerAvailabilityChanged__chapko/thali05_samsung-SM-G930F.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/894433142f26427__899_Update_thaliMobile_for_WiFi_and_Android__peerAvailabilityChanged__chapko/thali05_samsung-SM-G935F.md)

[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/894433142f26427__899_Update_thaliMobile_for_WiFi_and_Android__peerAvailabilityChanged__chapko/thali05_Huawei-Nexus 6P.md)


###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/894433142f26427__899_Update_thaliMobile_for_WiFi_and_Android__peerAvailabilityChanged__chapko/iOS_Iphone6-1.md)

[Iphone6-2](https://github.com/ThaliTester/TestResults/blob/894433142f26427__899_Update_thaliMobile_for_WiFi_and_Android__peerAvailabilityChanged__chapko/iOS_Iphone6-2.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/894433142f26427__899_Update_thaliMobile_for_WiFi_and_Android__peerAvailabilityChanged__chapko/iOS_Iphone5s-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/894433142f26427__899_Update_thaliMobile_for_WiFi_and_Android__peerAvailabilityChanged__chapko/iOS_IpadAir2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/894433142f26427__899_Update_thaliMobile_for_WiFi_and_Android__peerAvailabilityChanged__chapko/iOS_server.md)





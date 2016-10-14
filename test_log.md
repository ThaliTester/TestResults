#### Test 8944331487965e9 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":3}}
2016-10-14 20:07:02 - INFO HttpServer: 'listening on *:3000'

2016-10-14 20:08:00 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'c32c7a67-7c2f-4b95-84ae-da28f3edea99', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-14 20:08:00 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G930F''

2016-10-14 20:08:00 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'client namespace disconnect''

2016-10-14 20:08:01 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: 'ed2a6f1a-26d8-4b99-b107-0c69f70e4d45', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-14 20:08:01 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G935F''

2016-10-14 20:08:01 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'client namespace disconnect''

2016-10-14 20:08:07 - DEBUG HttpServer: 'device presented, name: 'Huawei-Nexus 6P', uuid: '938cd24e-5a46-43b2-a467-069a585d73dd', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-14 20:08:07 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'Huawei-Nexus 6P''

2016-10-14 20:08:07 - INFO HttpServer: 'Socket to device name: 'Huawei-Nexus 6P' disconnected, reason: 'client namespace disconnect''


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

ios : Error: Command failed: true
14/10/2016@22:02:32 Getting the list of iOS devices 
14/10/2016@22:02:33 Deploying iOS test app 
14/10/2016@22:02:33 uninstalling the application 
14/10/2016@22:02:34 installing the application 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/8944331487965e9__899_Update_thaliMobile_for_WiFi_and_Android__peerAvailabilityChanged__chapko/iOS_Iphone6-1.md)

[Iphone6-2](https://github.com/ThaliTester/TestResults/blob/8944331487965e9__899_Update_thaliMobile_for_WiFi_and_Android__peerAvailabilityChanged__chapko/iOS_Iphone6-2.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/8944331487965e9__899_Update_thaliMobile_for_WiFi_and_Android__peerAvailabilityChanged__chapko/iOS_Iphone5s-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/8944331487965e9__899_Update_thaliMobile_for_WiFi_and_Android__peerAvailabilityChanged__chapko/iOS_IpadAir2-1.md)


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
STOP log received from ENU7N16516000107
Test has FAILED

Device test finished on ENU7N16516000107 
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/8944331487965e9__899_Update_thaliMobile_for_WiFi_and_Android__peerAvailabilityChanged__chapko/thali05_samsung-SM-G930F.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/8944331487965e9__899_Update_thaliMobile_for_WiFi_and_Android__peerAvailabilityChanged__chapko/thali05_samsung-SM-G935F.md)

[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/8944331487965e9__899_Update_thaliMobile_for_WiFi_and_Android__peerAvailabilityChanged__chapko/thali05_Huawei-Nexus 6P.md)





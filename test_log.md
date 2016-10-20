#### Test 901767747b3ba04 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":3}}
2016-10-20 11:16:48 - INFO HttpServer: 'listening on *:3000'

2016-10-20 11:17:50 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'ab3bee6a-5b54-4cef-a198-075ddcd7b8af', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-20 11:17:50 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G930F''

2016-10-20 11:17:50 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'client namespace disconnect''

2016-10-20 11:17:50 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '9bea052b-e888-4aec-a2d3-0c1fdbc81345', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-20 11:17:50 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G935F''

2016-10-20 11:17:51 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'client namespace disconnect''

2016-10-20 11:17:55 - DEBUG HttpServer: 'device presented, name: 'Huawei-Nexus 6P', uuid: '7c7160a5-4dad-4cb4-9d10-f995d3160890', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-20 11:17:55 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'Huawei-Nexus 6P''

2016-10-20 11:17:55 - INFO HttpServer: 'Socket to device name: 'Huawei-Nexus 6P' disconnected, reason: 'client namespace disconnect''


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

ios : false

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/901767747b3ba04_Fixed_default_directory_for_SSDP_replacer_andrew-aladev/thali05_samsung-SM-G930F.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/901767747b3ba04_Fixed_default_directory_for_SSDP_replacer_andrew-aladev/thali05_samsung-SM-G935F.md)

[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/901767747b3ba04_Fixed_default_directory_for_SSDP_replacer_andrew-aladev/thali05_Huawei-Nexus 6P.md)




###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/901767747b3ba04_Fixed_default_directory_for_SSDP_replacer_andrew-aladev/iOS_Iphone6-1.md)

[Iphone6-2](https://github.com/ThaliTester/TestResults/blob/901767747b3ba04_Fixed_default_directory_for_SSDP_replacer_andrew-aladev/iOS_Iphone6-2.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/901767747b3ba04_Fixed_default_directory_for_SSDP_replacer_andrew-aladev/iOS_Iphone5s-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/901767747b3ba04_Fixed_default_directory_for_SSDP_replacer_andrew-aladev/iOS_IpadAir2-1.md)



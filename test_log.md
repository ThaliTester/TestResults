#### Test 8810685851ee2f9 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-10-06 12:57:03 - INFO HttpServer: 'listening on *:3000'

2016-10-06 12:58:53 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'd4da17d2-be1c-4744-ac3a-67d0d3f551b2', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-06 12:58:53 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G930F''

2016-10-06 12:58:53 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'client namespace disconnect''

2016-10-06 12:58:54 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: 'cf4f9047-6f41-4a43-9bb9-350355dc6da4', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-06 12:58:54 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G935F''

2016-10-06 12:58:54 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'client namespace disconnect''

2016-10-06 12:59:02 - DEBUG HttpServer: 'device presented, name: 'Huawei-Nexus 6P', uuid: 'f7f7dc56-50f4-4a8b-b636-12a3a2722808', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-10-06 12:59:02 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'Huawei-Nexus 6P''

2016-10-06 12:59:02 - INFO HttpServer: 'Socket to device name: 'Huawei-Nexus 6P' disconnected, reason: 'client namespace disconnect''


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/8810685851ee2f9_switch_coordination_server_from_jx_into_node_larryonoff/thali05_samsung-SM-G930F.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/8810685851ee2f9_switch_coordination_server_from_jx_into_node_larryonoff/thali05_samsung-SM-G935F.md)

[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/8810685851ee2f9_switch_coordination_server_from_jx_into_node_larryonoff/thali05_Huawei-Nexus 6P.md)





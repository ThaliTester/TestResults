#### Test 829120304df63d9 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":10}}
2016-08-30T14:20:28.655Z - info: Require 0 ios devices

2016-08-30T14:20:28.674Z - info: Require 10 android devices

2016-08-30T14:20:28.734Z - info: listening on *:3000

2016-08-30T14:20:32.586Z - debug: Device presented: samsung-SM-T719 (ba899473-8bdf-47a9-b894-ed149ad8ed92) - android 6.0.1

2016-08-30T14:20:32.597Z - debug: Device presented: samsung-SM-G900F (a187cea5-05f4-49a7-9af7-2416a972b302) - android 6.0.1

2016-08-30T14:20:32.821Z - debug: Device presented: motorola-Nexus 6 (4b8c9afc-f2b1-4684-9dd0-17a005491341) - android 6.0.1

2016-08-30T14:20:33.527Z - debug: Device presented: samsung-SM-T719 (ba899473-8bdf-47a9-b894-ed149ad8ed92) - android 6.0.1

2016-08-30T14:20:33.528Z - info: Updating existing device: samsung-SM-T719 (ba899473-8bdf-47a9-b894-ed149ad8ed92)

2016-08-30T14:20:33.591Z - debug: Device presented: samsung-SM-G900F (a187cea5-05f4-49a7-9af7-2416a972b302) - android 6.0.1

2016-08-30T14:20:33.592Z - info: Updating existing device: samsung-SM-G900F (a187cea5-05f4-49a7-9af7-2416a972b302)

2016-08-30T14:20:33.852Z - debug: Device presented: motorola-Nexus 6 (4b8c9afc-f2b1-4684-9dd0-17a005491341) - android 6.0.1

2016-08-30T14:20:33.853Z - info: Updating existing device: motorola-Nexus 6 (4b8c9afc-f2b1-4684-9dd0-17a005491341)

2016-08-30T14:40:25.323Z - info: Socket to device samsung-SM-T719 disconnected: transport close

2016-08-30T14:40:53.164Z - info: Socket to device motorola-Nexus 6 disconnected: transport close

2016-08-30T14:40:55.555Z - info: Socket to device samsung-SM-G900F disconnected: transport close


 
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
####Node name: thali01
Console output:
```

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1G429CRK 
Error! Unexpected exit on device 0be0c6c6 app:com.test.thalitest code:null 
child process exited with code null on device 0be0c6c6 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/829120304df63d9__916_Set-up_node_tests_for_Android_and_iOS_artemjackson/thali01_motorola-Nexus 6.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/829120304df63d9__916_Set-up_node_tests_for_Android_and_iOS_artemjackson/thali01_samsung-SM-G900F.md)

####Node name: thali02
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Error! Unexpected exit on device LGD855a6933058 app:com.test.thalitest code:0 
child process exited with code 0 on device LGD855a6933058 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/829120304df63d9__916_Set-up_node_tests_for_Android_and_iOS_artemjackson/thali02_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/829120304df63d9__916_Set-up_node_tests_for_Android_and_iOS_artemjackson/thali02_LGE-LG-D855.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:null 
child process exited with code null on device f56ad48d 
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:null 
child process exited with code null on device 7970f88c 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/829120304df63d9__916_Set-up_node_tests_for_Android_and_iOS_artemjackson/thali03_samsung-SM-A500FU.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/829120304df63d9__916_Set-up_node_tests_for_Android_and_iOS_artemjackson/thali03_samsung-SM-A300FU.md)

####Node name: thali04
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:null 
child process exited with code null on device 4325e43f 
Error! Unexpected exit on device HT54GYJ03048 app:com.test.thalitest code:null 
child process exited with code null on device HT54GYJ03048 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/829120304df63d9__916_Set-up_node_tests_for_Android_and_iOS_artemjackson/thali04_samsung-SM-A300FU.md)

[HTC-HTC One M9](https://github.com/ThaliTester/TestResults/blob/829120304df63d9__916_Set-up_node_tests_for_Android_and_iOS_artemjackson/thali04_HTC-HTC One M9.md)

####Node name: thali05
Console output:
```

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device e8c09bab app:com.test.thalitest code:0 
child process exited with code 0 on device e8c09bab 
Error! Unexpected exit on device ce061606e320561102 app:com.test.thalitest code:0 
child process exited with code 0 on device ce061606e320561102 
Android task is completed. [FAILED]
```
[samsung-SM-T719](https://github.com/ThaliTester/TestResults/blob/829120304df63d9__916_Set-up_node_tests_for_Android_and_iOS_artemjackson/thali05_samsung-SM-T719.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/829120304df63d9__916_Set-up_node_tests_for_Android_and_iOS_artemjackson/thali05_samsung-SM-G935F.md)





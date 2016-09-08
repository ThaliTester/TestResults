#### Test 82912030f17cf99 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":10}}
2016-09-08T14:01:38.514Z - info: Require 0 ios devices

2016-09-08T14:01:38.533Z - info: Require 10 android devices

2016-09-08T14:01:38.592Z - info: listening on *:3000

2016-09-08T14:01:41.502Z - debug: Device presented: samsung-SM-T719 (673d1759-4e59-4416-9441-1936f0f16913) - android 6.0.1

2016-09-08T14:01:42.478Z - debug: Device presented: samsung-SM-T719 (673d1759-4e59-4416-9441-1936f0f16913) - android 6.0.1

2016-09-08T14:01:42.480Z - info: Updating existing device: samsung-SM-T719 (673d1759-4e59-4416-9441-1936f0f16913)

2016-09-08T14:03:48.713Z - debug: Device presented: motorola-Nexus 6 (c2859bc6-8ab4-45db-9050-7219e8d8d1b6) - android 6.0.1

2016-09-08T14:03:49.473Z - debug: Device presented: samsung-SM-G900F (00ee7b6e-2c88-4e03-8fef-516d323a3480) - android 6.0.1

2016-09-08T14:06:06.005Z - info: HTTP get called

2016-09-08T14:21:25.032Z - info: Socket to device samsung-SM-T719 disconnected: transport close

2016-09-08T14:25:15.251Z - info: Socket to device motorola-Nexus 6 disconnected: transport close

2016-09-08T14:25:17.448Z - info: Socket to device samsung-SM-G900F disconnected: transport close


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m
Thu, 08 Sep 2016 14:06:06 GMT express deprecated res.sendfile: Use res.sendFile instead at index.js:106:7


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
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/82912030f17cf99__916_Set-up_node_tests_for_Android_and_iOS_artemjackson/thali01_motorola-Nexus 6.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/82912030f17cf99__916_Set-up_node_tests_for_Android_and_iOS_artemjackson/thali01_samsung-SM-G900F.md)

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
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/82912030f17cf99__916_Set-up_node_tests_for_Android_and_iOS_artemjackson/thali02_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/82912030f17cf99__916_Set-up_node_tests_for_Android_and_iOS_artemjackson/thali02_LGE-LG-D855.md)

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
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/82912030f17cf99__916_Set-up_node_tests_for_Android_and_iOS_artemjackson/thali03_samsung-SM-A500FU.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/82912030f17cf99__916_Set-up_node_tests_for_Android_and_iOS_artemjackson/thali03_samsung-SM-A300FU.md)

####Node name: thali04
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:null 
child process exited with code null on device 4325e43f 
Error! Unexpected exit on device HT54GYJ03048 app:com.test.thalitest code:0 
child process exited with code 0 on device HT54GYJ03048 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/82912030f17cf99__916_Set-up_node_tests_for_Android_and_iOS_artemjackson/thali04_samsung-SM-A300FU.md)

[HTC-HTC One M9](https://github.com/ThaliTester/TestResults/blob/82912030f17cf99__916_Set-up_node_tests_for_Android_and_iOS_artemjackson/thali04_HTC-HTC One M9.md)

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
[samsung-SM-T719](https://github.com/ThaliTester/TestResults/blob/82912030f17cf99__916_Set-up_node_tests_for_Android_and_iOS_artemjackson/thali05_samsung-SM-T719.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/82912030f17cf99__916_Set-up_node_tests_for_Android_and_iOS_artemjackson/thali05_samsung-SM-G935F.md)





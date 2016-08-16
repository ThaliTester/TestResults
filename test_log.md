#### Test 813219427e676a1 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":8}}
2016-08-16T17:35:10.358Z - info: Require 3 ios devices

2016-08-16T17:35:10.377Z - info: Require 3 android devices

2016-08-16T17:35:10.440Z - info: listening on *:3000

2016-08-16T17:35:13.528Z - debug: Device presented: motorola-Nexus 6 (f970ec0a-67fa-4b39-b739-72288d53ab7e) - android 6.0.1

2016-08-16T17:35:13.826Z - debug: Device presented: samsung-SM-G900F (b70f9cff-8af1-45c1-9b07-46830f811270) - android 6.0.1

2016-08-16T17:35:14.430Z - debug: Device presented: motorola-Nexus 6 (f970ec0a-67fa-4b39-b739-72288d53ab7e) - android 6.0.1

2016-08-16T17:35:14.431Z - info: Updating existing device: motorola-Nexus 6 (f970ec0a-67fa-4b39-b739-72288d53ab7e)

2016-08-16T17:35:14.799Z - debug: Device presented: samsung-SM-G900F (b70f9cff-8af1-45c1-9b07-46830f811270) - android 6.0.1

2016-08-16T17:35:14.800Z - info: Updating existing device: samsung-SM-G900F (b70f9cff-8af1-45c1-9b07-46830f811270)

2016-08-16T17:35:54.860Z - debug: Device presented: LGE-LG-D855 (93928610-86a7-47a2-ad65-463394cb9412) - android 5.0

2016-08-16T17:36:10.916Z - debug: Device presented: LGE-LG-D722 (856f7640-7ff2-4e22-996f-7ff4933f02d7) - android 5.0.2

2016-08-16T17:55:11.365Z - info: Socket to device motorola-Nexus 6 disconnected: transport close

2016-08-16T17:55:13.893Z - info: Socket to device samsung-SM-G900F disconnected: transport close

2016-08-16T17:58:37.396Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-16T17:58:39.250Z - info: Socket to device LGE-LG-D855 disconnected: transport close


 
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
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/813219427e676a1_Fixed_thaliTestMobileNative_evabishchevich/thali01_motorola-Nexus 6.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/813219427e676a1_Fixed_thaliTestMobileNative_evabishchevich/thali01_samsung-SM-G900F.md)

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
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/813219427e676a1_Fixed_thaliTestMobileNative_evabishchevich/thali02_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/813219427e676a1_Fixed_thaliTestMobileNative_evabishchevich/thali02_LGE-LG-D855.md)

####Node name: thali03
Console output:
```
STOP log received from  7970f88c Test has  SUCCEEDED
STOP log received from  f56ad48d Test has  SUCCEEDED
Device test finished on 7970f88c 
Device test finished on f56ad48d 
Android task is completed. [SUCCESS]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/813219427e676a1_Fixed_thaliTestMobileNative_evabishchevich/thali03_samsung-SM-A500FU.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/813219427e676a1_Fixed_thaliTestMobileNative_evabishchevich/thali03_samsung-SM-A300FU.md)

####Node name: thali04
Console output:
```
STOP log received from  HT54GYJ03048 Test has  SUCCEEDED
STOP log received from  4325e43f Test has  SUCCEEDED
Device test finished on 4325e43f 
Device test finished on HT54GYJ03048 
Android task is completed. [SUCCESS]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/813219427e676a1_Fixed_thaliTestMobileNative_evabishchevich/thali04_samsung-SM-A300FU.md)

[HTC-HTC One M9](https://github.com/ThaliTester/TestResults/blob/813219427e676a1_Fixed_thaliTestMobileNative_evabishchevich/thali04_HTC-HTC One M9.md)





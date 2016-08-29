#### Test 83084099a4f621d Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":12}}
2016-08-29T12:43:06.915Z - info: Require 3 ios devices

2016-08-29T12:43:06.934Z - info: Require 3 android devices

2016-08-29T12:43:06.993Z - info: listening on *:3000

2016-08-29T12:43:08.148Z - debug: Device presented: samsung-SM-A300FU (8ea6c049-d986-4896-a37e-4f24758c3ee6) - android 5.0.2

2016-08-29T12:43:08.156Z - debug: Device presented: samsung-SM-T719 (1245cf7e-efef-46d2-b94e-b0a77535f2ad) - android 6.0.1

2016-08-29T12:43:08.272Z - debug: Device presented: LGE-LG-D722 (efd70603-95da-4376-9438-ca7ab4d457e4) - android 5.0.2

2016-08-29T12:43:08.558Z - debug: Device presented: samsung-SM-A300FU (d06a7c56-d0a5-4634-82f9-03e6e775302b) - android 5.0.2

2016-08-29T12:43:09.049Z - debug: Device presented: samsung-SM-G935F (8b42cc23-4344-499b-9d11-bcff48dcd0af) - android 6.0.1

2016-08-29T12:43:09.077Z - debug: Device presented: samsung-SM-A300FU (8ea6c049-d986-4896-a37e-4f24758c3ee6) - android 5.0.2

2016-08-29T12:43:09.078Z - info: Updating existing device: samsung-SM-A300FU (8ea6c049-d986-4896-a37e-4f24758c3ee6)

2016-08-29T12:43:09.121Z - debug: Device presented: samsung-SM-T719 (1245cf7e-efef-46d2-b94e-b0a77535f2ad) - android 6.0.1

2016-08-29T12:43:09.122Z - info: Updating existing device: samsung-SM-T719 (1245cf7e-efef-46d2-b94e-b0a77535f2ad)

2016-08-29T12:43:09.194Z - debug: Device presented: LGE-LG-D722 (efd70603-95da-4376-9438-ca7ab4d457e4) - android 5.0.2

2016-08-29T12:43:09.195Z - info: Updating existing device: LGE-LG-D722 (efd70603-95da-4376-9438-ca7ab4d457e4)

2016-08-29T12:43:09.535Z - debug: Device presented: samsung-SM-A300FU (d06a7c56-d0a5-4634-82f9-03e6e775302b) - android 5.0.2

2016-08-29T12:43:09.536Z - info: Updating existing device: samsung-SM-A300FU (d06a7c56-d0a5-4634-82f9-03e6e775302b)

2016-08-29T12:43:10.045Z - debug: Device presented: samsung-SM-G935F (8b42cc23-4344-499b-9d11-bcff48dcd0af) - android 6.0.1

2016-08-29T12:43:10.046Z - info: Updating existing device: samsung-SM-G935F (8b42cc23-4344-499b-9d11-bcff48dcd0af)

2016-08-29T12:43:10.674Z - debug: Device presented: LGE-LG-D855 (c300954d-01ff-4697-98e3-6629ca52be57) - android 5.0

2016-08-29T12:43:11.552Z - debug: Device presented: samsung-SM-A500FU (d3f78844-b5e4-4c0e-ba79-f1ca06d02f94) - android 5.0.2

2016-08-29T12:43:11.668Z - debug: Device presented: LGE-LG-D855 (c300954d-01ff-4697-98e3-6629ca52be57) - android 5.0

2016-08-29T12:43:11.671Z - info: Updating existing device: LGE-LG-D855 (c300954d-01ff-4697-98e3-6629ca52be57)

2016-08-29T12:43:12.535Z - debug: Device presented: samsung-SM-A500FU (d3f78844-b5e4-4c0e-ba79-f1ca06d02f94) - android 5.0.2

2016-08-29T12:43:12.535Z - info: Updating existing device: samsung-SM-A500FU (d3f78844-b5e4-4c0e-ba79-f1ca06d02f94)

2016-08-29T12:44:59.007Z - debug: Device presented: Huawei-Nexus 6P (835c7a1a-3b4f-4b47-9ef4-d17c03860ab1) - android 6.0.1

2016-08-29T12:45:02.228Z - debug: Device presented: samsung-SM-G930F (242f9dd4-4bf0-4f72-8bfa-8a21158e246d) - android 6.0.1

2016-08-29T13:02:55.360Z - info: Socket to device samsung-SM-T719 disconnected: transport close

2016-08-29T13:02:56.731Z - info: Socket to device samsung-SM-G935F disconnected: transport close

2016-08-29T13:03:01.627Z - info: Socket to device samsung-SM-A300FU disconnected: transport close

2016-08-29T13:03:07.287Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-29T13:03:08.142Z - info: Socket to device samsung-SM-A500FU disconnected: transport close

2016-08-29T13:03:09.358Z - info: Socket to device LGE-LG-D855 disconnected: transport close

2016-08-29T13:03:10.015Z - info: Socket to device samsung-SM-A300FU disconnected: transport close

2016-08-29T13:06:33.327Z - info: Socket to device samsung-SM-G930F disconnected: transport close

2016-08-29T13:06:34.685Z - info: Socket to device Huawei-Nexus 6P disconnected: transport close


 
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
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:null 
child process exited with code null on device ZX1G429CRK 
Error! Unexpected exit on device 0be0c6c6 app:com.test.thalitest code:null 
child process exited with code null on device 0be0c6c6 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/83084099a4f621d_changed_Connection_Timed_Out_error_s_description_baydet/thali01_motorola-Nexus 6.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/83084099a4f621d_changed_Connection_Timed_Out_error_s_description_baydet/thali01_samsung-SM-G900F.md)

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
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/83084099a4f621d_changed_Connection_Timed_Out_error_s_description_baydet/thali02_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/83084099a4f621d_changed_Connection_Timed_Out_error_s_description_baydet/thali02_LGE-LG-D855.md)

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
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/83084099a4f621d_changed_Connection_Timed_Out_error_s_description_baydet/thali03_samsung-SM-A500FU.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/83084099a4f621d_changed_Connection_Timed_Out_error_s_description_baydet/thali03_samsung-SM-A300FU.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/83084099a4f621d_changed_Connection_Timed_Out_error_s_description_baydet/thali04_samsung-SM-A300FU.md)

[HTC-HTC One M9](https://github.com/ThaliTester/TestResults/blob/83084099a4f621d_changed_Connection_Timed_Out_error_s_description_baydet/thali04_HTC-HTC One M9.md)

####Node name: thali05
Console output:
```

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device e8c09bab app:com.test.thalitest code:0 
child process exited with code 0 on device e8c09bab 
Error! Unexpected exit on device ce061606e320561102 app:com.test.thalitest code:null 
child process exited with code null on device ce061606e320561102 
Android task is completed. [FAILED]
```
[samsung-SM-T719](https://github.com/ThaliTester/TestResults/blob/83084099a4f621d_changed_Connection_Timed_Out_error_s_description_baydet/thali05_samsung-SM-T719.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/83084099a4f621d_changed_Connection_Timed_Out_error_s_description_baydet/thali05_samsung-SM-G935F.md)

####Node name: thali06
Console output:
```

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ce0616068b9f212302 app:com.test.thalitest code:0 
child process exited with code 0 on device ce0616068b9f212302 
Error! Unexpected exit on device ENU7N16516000107 app:com.test.thalitest code:0 
child process exited with code 0 on device ENU7N16516000107 
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/83084099a4f621d_changed_Connection_Timed_Out_error_s_description_baydet/thali06_samsung-SM-G930F.md)

[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/83084099a4f621d_changed_Connection_Timed_Out_error_s_description_baydet/thali06_Huawei-Nexus 6P.md)





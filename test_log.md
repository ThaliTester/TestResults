#### Test 82865362e858c08 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":10}}
2016-08-30T17:20:58.650Z - info: Require 0 ios devices

2016-08-30T17:20:58.669Z - info: Require 10 android devices

2016-08-30T17:20:58.727Z - info: listening on *:3000

2016-08-30T17:20:59.249Z - debug: Device presented: samsung-SM-G935F (2b112c93-5667-4bdd-b520-2f11603770b8) - android 6.0.1

2016-08-30T17:20:59.454Z - debug: Device presented: samsung-SM-G900F (804ac8d0-d8ea-4f24-b1c0-873fdf06a6f5) - android 6.0.1

2016-08-30T17:20:59.478Z - debug: Device presented: samsung-SM-T719 (48e9a492-997c-4c6a-a815-84c909ba095c) - android 6.0.1

2016-08-30T17:21:00.233Z - debug: Device presented: samsung-SM-G935F (2b112c93-5667-4bdd-b520-2f11603770b8) - android 6.0.1

2016-08-30T17:21:00.235Z - info: Updating existing device: samsung-SM-G935F (2b112c93-5667-4bdd-b520-2f11603770b8)

2016-08-30T17:21:00.433Z - debug: Device presented: samsung-SM-G900F (804ac8d0-d8ea-4f24-b1c0-873fdf06a6f5) - android 6.0.1

2016-08-30T17:21:00.434Z - info: Updating existing device: samsung-SM-G900F (804ac8d0-d8ea-4f24-b1c0-873fdf06a6f5)

2016-08-30T17:21:00.493Z - debug: Device presented: samsung-SM-T719 (48e9a492-997c-4c6a-a815-84c909ba095c) - android 6.0.1

2016-08-30T17:21:00.495Z - info: Updating existing device: samsung-SM-T719 (48e9a492-997c-4c6a-a815-84c909ba095c)

2016-08-30T17:21:00.659Z - debug: Device presented: samsung-SM-A500FU (3b4d4c07-c6fe-4225-9650-9c3a06d6ad36) - android 5.0.2

2016-08-30T17:21:00.771Z - debug: Device presented: motorola-Nexus 6 (35521f41-2522-405e-9ba1-3cd3b621b26b) - android 6.0.1

2016-08-30T17:21:01.061Z - debug: Device presented: samsung-SM-A300FU (686d3e60-9d7f-4283-bb58-a7cbb11d87ba) - android 5.0.2

2016-08-30T17:21:01.664Z - debug: Device presented: samsung-SM-A500FU (3b4d4c07-c6fe-4225-9650-9c3a06d6ad36) - android 5.0.2

2016-08-30T17:21:01.665Z - info: Updating existing device: samsung-SM-A500FU (3b4d4c07-c6fe-4225-9650-9c3a06d6ad36)

2016-08-30T17:21:01.776Z - debug: Device presented: motorola-Nexus 6 (35521f41-2522-405e-9ba1-3cd3b621b26b) - android 6.0.1

2016-08-30T17:21:01.777Z - info: Updating existing device: motorola-Nexus 6 (35521f41-2522-405e-9ba1-3cd3b621b26b)

2016-08-30T17:21:02.030Z - debug: Device presented: samsung-SM-A300FU (686d3e60-9d7f-4283-bb58-a7cbb11d87ba) - android 5.0.2

2016-08-30T17:21:02.031Z - info: Updating existing device: samsung-SM-A300FU (686d3e60-9d7f-4283-bb58-a7cbb11d87ba)

2016-08-30T17:21:03.712Z - debug: Device presented: samsung-SM-A300FU (56e45873-7a06-41a6-9508-5df6682b33c2) - android 5.0.2

2016-08-30T17:21:04.707Z - debug: Device presented: samsung-SM-A300FU (56e45873-7a06-41a6-9508-5df6682b33c2) - android 5.0.2

2016-08-30T17:21:04.708Z - info: Updating existing device: samsung-SM-A300FU (56e45873-7a06-41a6-9508-5df6682b33c2)

2016-08-30T17:22:59.306Z - debug: Device presented: LGE-LG-D855 (b28b78ac-cb6b-4990-a38a-84473992d08d) - android 5.0

2016-08-30T17:23:13.149Z - debug: Device presented: LGE-LG-D722 (5020b4ca-c267-4cbc-8613-8b1b540b73b6) - android 5.0.2

2016-08-30T17:40:56.395Z - info: Socket to device samsung-SM-T719 disconnected: transport close

2016-08-30T17:40:58.585Z - info: Socket to device samsung-SM-G935F disconnected: transport close

2016-08-30T17:41:11.133Z - info: Socket to device samsung-SM-A300FU disconnected: transport close

2016-08-30T17:41:15.234Z - info: Socket to device samsung-SM-A500FU disconnected: transport close

2016-08-30T17:41:17.036Z - info: Socket to device samsung-SM-A300FU disconnected: transport close

2016-08-30T17:41:17.196Z - info: Socket to device motorola-Nexus 6 disconnected: transport close

2016-08-30T17:41:19.783Z - info: Socket to device samsung-SM-G900F disconnected: transport close

2016-08-30T17:44:25.702Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-30T17:44:27.920Z - info: Socket to device LGE-LG-D855 disconnected: transport close


 
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
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/82865362e858c08__934_Fixed_the_Mobile_mock_logic_artemjackson/thali01_motorola-Nexus 6.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/82865362e858c08__934_Fixed_the_Mobile_mock_logic_artemjackson/thali01_samsung-SM-G900F.md)

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
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/82865362e858c08__934_Fixed_the_Mobile_mock_logic_artemjackson/thali02_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/82865362e858c08__934_Fixed_the_Mobile_mock_logic_artemjackson/thali02_LGE-LG-D855.md)

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
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/82865362e858c08__934_Fixed_the_Mobile_mock_logic_artemjackson/thali03_samsung-SM-A500FU.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/82865362e858c08__934_Fixed_the_Mobile_mock_logic_artemjackson/thali03_samsung-SM-A300FU.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/82865362e858c08__934_Fixed_the_Mobile_mock_logic_artemjackson/thali04_samsung-SM-A300FU.md)

[HTC-HTC One M9](https://github.com/ThaliTester/TestResults/blob/82865362e858c08__934_Fixed_the_Mobile_mock_logic_artemjackson/thali04_HTC-HTC One M9.md)

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
[samsung-SM-T719](https://github.com/ThaliTester/TestResults/blob/82865362e858c08__934_Fixed_the_Mobile_mock_logic_artemjackson/thali05_samsung-SM-T719.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/82865362e858c08__934_Fixed_the_Mobile_mock_logic_artemjackson/thali05_samsung-SM-G935F.md)





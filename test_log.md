#### Test 8286536280ed803 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":10}}
2016-09-01T18:52:58.241Z - info: Require 0 ios devices

2016-09-01T18:52:58.259Z - info: Require 10 android devices

2016-09-01T18:52:58.318Z - info: listening on *:3000

2016-09-01T18:52:59.880Z - debug: Device presented: samsung-SM-A300FU (fd9a9378-0292-4b14-a796-7f5b874a5e25) - android 5.0.2

2016-09-01T18:53:00.722Z - debug: Device presented: samsung-SM-A500FU (ae515980-296a-47ae-95c9-6db970d045f0) - android 5.0.2

2016-09-01T18:53:00.841Z - debug: Device presented: samsung-SM-A300FU (fd9a9378-0292-4b14-a796-7f5b874a5e25) - android 5.0.2

2016-09-01T18:53:00.842Z - info: Updating existing device: samsung-SM-A300FU (fd9a9378-0292-4b14-a796-7f5b874a5e25)

2016-09-01T18:53:01.637Z - debug: Device presented: samsung-SM-G935F (3de5a824-c443-4478-a8af-beabcc5f7656) - android 6.0.1

2016-09-01T18:53:01.713Z - debug: Device presented: samsung-SM-A500FU (ae515980-296a-47ae-95c9-6db970d045f0) - android 5.0.2

2016-09-01T18:53:01.714Z - info: Updating existing device: samsung-SM-A500FU (ae515980-296a-47ae-95c9-6db970d045f0)

2016-09-01T18:53:01.966Z - debug: Device presented: LGE-LG-D855 (56aa6fe3-78ba-4ace-807d-e6caf181d905) - android 5.0

2016-09-01T18:53:02.577Z - debug: Device presented: samsung-SM-A300FU (506c569e-3a6d-49c5-9b03-d21b61e15266) - android 5.0.2

2016-09-01T18:53:02.696Z - debug: Device presented: samsung-SM-G935F (3de5a824-c443-4478-a8af-beabcc5f7656) - android 6.0.1

2016-09-01T18:53:02.697Z - info: Updating existing device: samsung-SM-G935F (3de5a824-c443-4478-a8af-beabcc5f7656)

2016-09-01T18:53:02.778Z - debug: Device presented: LGE-LG-D722 (4c578641-57f2-439c-89c0-aad4d3eeb909) - android 5.0.2

2016-09-01T18:53:02.969Z - debug: Device presented: LGE-LG-D855 (56aa6fe3-78ba-4ace-807d-e6caf181d905) - android 5.0

2016-09-01T18:53:02.970Z - info: Updating existing device: LGE-LG-D855 (56aa6fe3-78ba-4ace-807d-e6caf181d905)

2016-09-01T18:53:03.455Z - debug: Device presented: samsung-SM-T719 (58f927ab-2261-420e-892d-896f6eaa23c7) - android 6.0.1

2016-09-01T18:53:03.572Z - debug: Device presented: samsung-SM-A300FU (506c569e-3a6d-49c5-9b03-d21b61e15266) - android 5.0.2

2016-09-01T18:53:03.575Z - info: Updating existing device: samsung-SM-A300FU (506c569e-3a6d-49c5-9b03-d21b61e15266)

2016-09-01T18:53:03.668Z - debug: Device presented: LGE-LG-D722 (4c578641-57f2-439c-89c0-aad4d3eeb909) - android 5.0.2

2016-09-01T18:53:03.669Z - info: Updating existing device: LGE-LG-D722 (4c578641-57f2-439c-89c0-aad4d3eeb909)

2016-09-01T18:53:04.466Z - debug: Device presented: samsung-SM-T719 (58f927ab-2261-420e-892d-896f6eaa23c7) - android 6.0.1

2016-09-01T18:53:04.467Z - info: Updating existing device: samsung-SM-T719 (58f927ab-2261-420e-892d-896f6eaa23c7)

2016-09-01T18:55:01.116Z - debug: Device presented: samsung-SM-G900F (da1da30a-74af-43da-9ca4-27ce12769d89) - android 6.0.1

2016-09-01T19:13:05.716Z - info: Socket to device samsung-SM-T719 disconnected: transport close

2016-09-01T19:13:08.000Z - info: Socket to device samsung-SM-G935F disconnected: transport close

2016-09-01T19:13:23.831Z - info: Socket to device samsung-SM-A300FU disconnected: transport close

2016-09-01T19:13:26.700Z - info: Socket to device samsung-SM-A500FU disconnected: transport close

2016-09-01T19:13:28.733Z - info: Socket to device samsung-SM-A300FU disconnected: transport close

2016-09-01T19:13:34.909Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-09-01T19:13:37.381Z - info: Socket to device LGE-LG-D855 disconnected: transport close

2016-09-01T19:17:13.128Z - info: Socket to device samsung-SM-G900F disconnected: transport close


 
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
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/8286536280ed803__934_Fixed_bunch_of_bugs_from__928_artemjackson/thali01_motorola-Nexus 6.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/8286536280ed803__934_Fixed_bunch_of_bugs_from__928_artemjackson/thali01_samsung-SM-G900F.md)

####Node name: thali02
Console output:
```
Error! Unexpected exit on device LGD855a6933058 app:com.test.thalitest code:0 
child process exited with code 0 on device LGD855a6933058 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/8286536280ed803__934_Fixed_bunch_of_bugs_from__928_artemjackson/thali02_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/8286536280ed803__934_Fixed_bunch_of_bugs_from__928_artemjackson/thali02_LGE-LG-D855.md)

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
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/8286536280ed803__934_Fixed_bunch_of_bugs_from__928_artemjackson/thali03_samsung-SM-A500FU.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/8286536280ed803__934_Fixed_bunch_of_bugs_from__928_artemjackson/thali03_samsung-SM-A300FU.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/8286536280ed803__934_Fixed_bunch_of_bugs_from__928_artemjackson/thali04_samsung-SM-A300FU.md)

[HTC-HTC One M9](https://github.com/ThaliTester/TestResults/blob/8286536280ed803__934_Fixed_bunch_of_bugs_from__928_artemjackson/thali04_HTC-HTC One M9.md)

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
[samsung-SM-T719](https://github.com/ThaliTester/TestResults/blob/8286536280ed803__934_Fixed_bunch_of_bugs_from__928_artemjackson/thali05_samsung-SM-T719.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/8286536280ed803__934_Fixed_bunch_of_bugs_from__928_artemjackson/thali05_samsung-SM-G935F.md)





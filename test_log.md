#### Test 817387969f35825 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":8}}
2016-08-24T18:36:05.604Z - info: Require 3 ios devices

2016-08-24T18:36:05.623Z - info: Require 3 android devices

2016-08-24T18:36:05.683Z - info: listening on *:3000

2016-08-24T18:36:06.615Z - debug: Device presented: samsung-SM-A300FU (130e0529-92bf-4aac-95f3-a6ccc18f6ae8) - android 5.0.2

2016-08-24T18:36:06.639Z - debug: Device presented: HTC-HTC One M9 (ff89bebc-1235-458e-88a0-c30e082db56d) - android 5.1

2016-08-24T18:36:06.907Z - debug: Device presented: LGE-LG-D722 (e998cdaf-86bc-4317-822f-dda84b394c1b) - android 5.0.2

2016-08-24T18:36:07.537Z - debug: Device presented: samsung-SM-A300FU (130e0529-92bf-4aac-95f3-a6ccc18f6ae8) - android 5.0.2

2016-08-24T18:36:07.538Z - info: Updating existing device: samsung-SM-A300FU (130e0529-92bf-4aac-95f3-a6ccc18f6ae8)

2016-08-24T18:36:07.635Z - debug: Device presented: HTC-HTC One M9 (ff89bebc-1235-458e-88a0-c30e082db56d) - android 5.1

2016-08-24T18:36:07.636Z - info: Updating existing device: HTC-HTC One M9 (ff89bebc-1235-458e-88a0-c30e082db56d)

2016-08-24T18:36:07.773Z - debug: Device presented: samsung-SM-G900F (afd60764-27ba-4b4b-9d2d-359417649976) - android 6.0.1

2016-08-24T18:36:07.825Z - debug: Device presented: LGE-LG-D722 (e998cdaf-86bc-4317-822f-dda84b394c1b) - android 5.0.2

2016-08-24T18:36:07.826Z - info: Updating existing device: LGE-LG-D722 (e998cdaf-86bc-4317-822f-dda84b394c1b)

2016-08-24T18:36:08.784Z - debug: Device presented: samsung-SM-G900F (afd60764-27ba-4b4b-9d2d-359417649976) - android 6.0.1

2016-08-24T18:36:08.785Z - info: Updating existing device: samsung-SM-G900F (afd60764-27ba-4b4b-9d2d-359417649976)

2016-08-24T18:37:33.404Z - debug: Device presented: LGE-LG-D855 (6fd35707-a37a-48f9-997a-2ed4a23bade8) - android 5.0

2016-08-24T18:38:09.080Z - debug: Device presented: samsung-SM-A300FU (633ca9ea-2b7f-459e-a6c9-5c671abc3e28) - android 5.0.2

2016-08-24T18:38:10.024Z - debug: Device presented: samsung-SM-A500FU (e9973fdc-df08-4a54-a15c-bd7f0e868da3) - android 5.0.2

2016-08-24T18:42:20.994Z - info: Socket to device samsung-SM-A300FU disconnected: transport close

2016-08-24T18:43:24.333Z - info: Socket to device LGE-LG-D855 disconnected: transport close

2016-08-24T18:45:45.266Z - debug: Device presented: LGE-LG-D855 (1980d0db-75cd-45cc-b039-b992487c2ed5) - android 5.0

2016-08-24T18:45:45.268Z - info: All 8 android devices are present

2016-08-24T18:45:45.270Z - info: Disqualifying device with unsupported hardware: LGE-LG-D722

2016-08-24T18:45:45.277Z - info: Disqualifying device with unsupported hardware: LGE-LG-D855

2016-08-24T18:45:45.278Z - info: Disqualifying device with unsupported hardware: LGE-LG-D855

2016-08-24T18:45:45.286Z - info: Starting unit test run on 5 android devices

2016-08-24T18:45:46.451Z - info: Socket to device LGE-LG-D855 disconnected: transport close

2016-08-24T18:45:46.956Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-24T18:56:00.127Z - info: Socket to device samsung-SM-A300FU disconnected: transport close

2016-08-24T18:56:01.748Z - info: Socket to device HTC-HTC One M9 disconnected: transport close

2016-08-24T18:56:08.342Z - info: Socket to device samsung-SM-G900F disconnected: transport close

2016-08-24T18:59:32.357Z - info: Socket to device samsung-SM-A500FU disconnected: transport close


 
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
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/817387969f35825_Updating_to_handle_iOS_yaronyg/thali01_motorola-Nexus 6.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/817387969f35825_Updating_to_handle_iOS_yaronyg/thali01_samsung-SM-G900F.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD855a6933058 Test has  SUCCEEDED
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD855a6933058 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/817387969f35825_Updating_to_handle_iOS_yaronyg/thali02_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/817387969f35825_Updating_to_handle_iOS_yaronyg/thali02_LGE-LG-D855.md)

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
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/817387969f35825_Updating_to_handle_iOS_yaronyg/thali03_samsung-SM-A500FU.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/817387969f35825_Updating_to_handle_iOS_yaronyg/thali03_samsung-SM-A300FU.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/817387969f35825_Updating_to_handle_iOS_yaronyg/thali04_samsung-SM-A300FU.md)

[HTC-HTC One M9](https://github.com/ThaliTester/TestResults/blob/817387969f35825_Updating_to_handle_iOS_yaronyg/thali04_HTC-HTC One M9.md)





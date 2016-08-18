#### Test 81738796b06b234 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":8}}
2016-08-18T00:40:40.332Z - info: Require 3 ios devices

2016-08-18T00:40:40.350Z - info: Require 3 android devices

2016-08-18T00:40:40.409Z - info: listening on *:3000

2016-08-18T00:40:42.178Z - debug: Device presented: motorola-Nexus 6 (e0b7fb27-d7bd-477b-bc26-6d66078fca54) - android 6.0.1

2016-08-18T00:40:42.228Z - debug: Device presented: samsung-SM-A300FU (f5cc9977-5d16-491c-9151-3758fb39b2e9) - android 5.0.2

2016-08-18T00:40:42.500Z - debug: Device presented: samsung-SM-G900F (e58413ce-d52a-454f-a8a3-4ed2b53ebc14) - android 6.0.1

2016-08-18T00:40:42.684Z - debug: Device presented: samsung-SM-A500FU (3b0ac5ae-34b5-47c4-8e66-63c22d10e02e) - android 5.0.2

2016-08-18T00:40:43.128Z - debug: Device presented: motorola-Nexus 6 (e0b7fb27-d7bd-477b-bc26-6d66078fca54) - android 6.0.1

2016-08-18T00:40:43.129Z - info: Updating existing device: motorola-Nexus 6 (e0b7fb27-d7bd-477b-bc26-6d66078fca54)

2016-08-18T00:40:43.197Z - debug: Device presented: samsung-SM-A300FU (f5cc9977-5d16-491c-9151-3758fb39b2e9) - android 5.0.2

2016-08-18T00:40:43.198Z - info: Updating existing device: samsung-SM-A300FU (f5cc9977-5d16-491c-9151-3758fb39b2e9)

2016-08-18T00:40:43.511Z - debug: Device presented: samsung-SM-G900F (e58413ce-d52a-454f-a8a3-4ed2b53ebc14) - android 6.0.1

2016-08-18T00:40:43.513Z - info: Updating existing device: samsung-SM-G900F (e58413ce-d52a-454f-a8a3-4ed2b53ebc14)

2016-08-18T00:40:43.669Z - debug: Device presented: samsung-SM-A500FU (3b0ac5ae-34b5-47c4-8e66-63c22d10e02e) - android 5.0.2

2016-08-18T00:40:43.670Z - info: Updating existing device: samsung-SM-A500FU (3b0ac5ae-34b5-47c4-8e66-63c22d10e02e)

2016-08-18T00:40:44.932Z - debug: Device presented: HTC-HTC One M9 (6c31c50c-b249-42f5-a00f-373c64123cef) - android 5.1

2016-08-18T00:40:45.441Z - debug: Device presented: samsung-SM-A300FU (65d5d202-cefd-4b9e-9974-db127e3f8b7c) - android 5.0.2

2016-08-18T00:40:45.940Z - debug: Device presented: HTC-HTC One M9 (6c31c50c-b249-42f5-a00f-373c64123cef) - android 5.1

2016-08-18T00:40:45.941Z - info: Updating existing device: HTC-HTC One M9 (6c31c50c-b249-42f5-a00f-373c64123cef)

2016-08-18T00:40:46.421Z - debug: Device presented: samsung-SM-A300FU (65d5d202-cefd-4b9e-9974-db127e3f8b7c) - android 5.0.2

2016-08-18T00:40:46.422Z - info: Updating existing device: samsung-SM-A300FU (65d5d202-cefd-4b9e-9974-db127e3f8b7c)

2016-08-18T00:42:38.740Z - debug: Device presented: LGE-LG-D855 (1efbbfa5-f795-4ff8-bdca-59525127b68e) - android 5.0

2016-08-18T00:42:50.709Z - debug: Device presented: LGE-LG-D722 (f1f666cc-1115-49e1-8469-00af36618510) - android 5.0.2

2016-08-18T00:42:50.710Z - info: All 8 android devices are present

2016-08-18T00:42:50.712Z - info: Disqualifying device with unsupported hardware: LGE-LG-D855

2016-08-18T00:42:50.719Z - info: Disqualifying device with unsupported hardware: LGE-LG-D722

2016-08-18T00:42:50.727Z - info: Starting unit test run on 6 android devices

2016-08-18T00:42:51.117Z - info: Running on android test: 1. onPeerLost calls jxcore

2016-08-18T00:42:51.237Z - info: Socket to device LGE-LG-D855 disconnected: transport close

2016-08-18T00:42:52.617Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-18T00:42:53.655Z - info: Running on android test: 2. onPeerDiscovered calls jxcore

2016-08-18T00:42:56.162Z - info: Test run on android complete

2016-08-18T00:42:56.164Z - info: 

-== UNIT TEST RESULTS ==-

2016-08-18T00:42:56.167Z - info: PLATFORM: android

2016-08-18T00:42:56.169Z - info: RESULT: PASS

2016-08-18T00:42:56.170Z - info: 2 of 2 tests completed

2016-08-18T00:42:56.171Z - info: 2/2 passed (0 failures)
2016-08-18T00:42:56.172Z - info: 

-== END ==-

2016-08-18T00:42:56.815Z - info: Socket to device samsung-SM-A500FU disconnected: transport close

2016-08-18T00:42:56.861Z - info: Socket to device samsung-SM-A300FU disconnected: transport close

2016-08-18T00:42:56.903Z - info: Socket to device samsung-SM-A300FU disconnected: transport close

2016-08-18T00:42:57.223Z - info: Socket to device motorola-Nexus 6 disconnected: transport close

2016-08-18T00:42:57.241Z - info: Socket to device HTC-HTC One M9 disconnected: transport close

2016-08-18T00:42:58.124Z - info: Socket to device samsung-SM-G900F disconnected: transport close

2016-08-18T00:44:54.737Z - debug: Device presented: LGE-LG-D855 (722758c9-2ed5-4c45-bc67-c767a9808493) - android 5.0

2016-08-18T00:45:07.592Z - debug: Device presented: LGE-LG-D722 (315db0de-a609-4a19-9922-b3edc8f09d04) - android 5.0.2

2016-08-18T00:45:07.594Z - info: All 8 android devices are present

2016-08-18T00:45:07.595Z - info: Disqualifying device with unsupported hardware: LGE-LG-D855

2016-08-18T00:45:07.598Z - info: Disqualifying device with unsupported hardware: LGE-LG-D722

2016-08-18T00:45:07.600Z - info: Starting unit test run on 6 android devices

2016-08-18T00:45:07.903Z - info: Socket to device LGE-LG-D855 disconnected: transport close

2016-08-18T00:45:09.442Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-18T00:47:11.263Z - debug: Device presented: LGE-LG-D855 (41c77531-210f-426f-893b-e3cd65e150f8) - android 5.0

2016-08-18T00:47:24.458Z - debug: Device presented: LGE-LG-D722 (75d9f014-a99f-488e-9b33-7de18d513a2d) - android 5.0.2

2016-08-18T00:47:24.460Z - info: All 8 android devices are present

2016-08-18T00:47:24.461Z - info: Disqualifying device with unsupported hardware: LGE-LG-D855
2016-08-18T00:47:24.463Z - info: Disqualifying device with unsupported hardware: LGE-LG-D722
2016-08-18T00:47:24.471Z - info: Starting unit test run on 6 android devices

2016-08-18T00:47:24.929Z - info: Socket to device LGE-LG-D855 disconnected: transport close

2016-08-18T00:47:26.361Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-18T00:49:28.920Z - debug: Device presented: LGE-LG-D855 (49e11bb1-da98-4d67-a4dc-257678127311) - android 5.0

2016-08-18T00:49:41.657Z - debug: Device presented: LGE-LG-D722 (d1aceb4a-c301-4a20-9cf0-6f7c2dee86c0) - android 5.0.2

2016-08-18T00:49:41.658Z - info: All 8 android devices are present

2016-08-18T00:49:41.660Z - info: Disqualifying device with unsupported hardware: LGE-LG-D855

2016-08-18T00:49:41.662Z - info: Disqualifying device with unsupported hardware: LGE-LG-D722

2016-08-18T00:49:41.664Z - info: Starting unit test run on 6 android devices

2016-08-18T00:49:41.917Z - info: Socket to device LGE-LG-D855 disconnected: transport close

2016-08-18T00:49:43.539Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-18T00:51:45.358Z - debug: Device presented: LGE-LG-D855 (69d38ac5-9c3e-4c15-accb-77ba47b720a8) - android 5.0

2016-08-18T00:51:59.132Z - debug: Device presented: LGE-LG-D722 (9ce9d409-d0e4-4b27-9db7-65937b870e96) - android 5.0.2

2016-08-18T00:51:59.133Z - info: All 8 android devices are present

2016-08-18T00:51:59.134Z - info: Disqualifying device with unsupported hardware: LGE-LG-D855

2016-08-18T00:51:59.136Z - info: Disqualifying device with unsupported hardware: LGE-LG-D722

2016-08-18T00:51:59.138Z - info: Starting unit test run on 6 android devices

2016-08-18T00:51:59.553Z - info: Socket to device LGE-LG-D855 disconnected: transport close

2016-08-18T00:52:00.853Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-18T00:54:02.960Z - debug: Device presented: LGE-LG-D855 (4436524a-b5d3-4f15-b208-0939db2b2b58) - android 5.0

2016-08-18T00:54:15.539Z - debug: Device presented: LGE-LG-D722 (d127e72c-aff7-428f-9903-dd4a45384141) - android 5.0.2

2016-08-18T00:54:15.540Z - info: All 8 android devices are present

2016-08-18T00:54:15.541Z - info: Disqualifying device with unsupported hardware: LGE-LG-D855

2016-08-18T00:54:15.544Z - info: Disqualifying device with unsupported hardware: LGE-LG-D722

2016-08-18T00:54:15.546Z - info: Starting unit test run on 6 android devices

2016-08-18T00:54:16.046Z - info: Socket to device LGE-LG-D855 disconnected: transport close

2016-08-18T00:54:17.433Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-18T00:56:19.645Z - debug: Device presented: LGE-LG-D855 (6b0f287b-8bc6-4292-a5a7-ae61d022b59c) - android 5.0

2016-08-18T00:56:32.172Z - debug: Device presented: LGE-LG-D722 (f2f16374-767f-4baa-b2e7-72081368ff40) - android 5.0.2

2016-08-18T00:56:32.175Z - info: All 8 android devices are present

2016-08-18T00:56:32.176Z - info: Disqualifying device with unsupported hardware: LGE-LG-D855

2016-08-18T00:56:32.179Z - info: Disqualifying device with unsupported hardware: LGE-LG-D722

2016-08-18T00:56:32.181Z - info: Starting unit test run on 6 android devices

2016-08-18T00:56:32.662Z - info: Socket to device LGE-LG-D855 disconnected: transport close

2016-08-18T00:56:34.156Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-18T00:58:36.132Z - debug: Device presented: LGE-LG-D855 (02179185-31cb-4fe3-8ff2-b74abe642e85) - android 5.0

2016-08-18T00:58:49.039Z - debug: Device presented: LGE-LG-D722 (fcd92a22-0c08-43f1-b0ff-9b893704f072) - android 5.0.2

2016-08-18T00:58:49.040Z - info: All 8 android devices are present

2016-08-18T00:58:49.042Z - info: Disqualifying device with unsupported hardware: LGE-LG-D855

2016-08-18T00:58:49.045Z - info: Disqualifying device with unsupported hardware: LGE-LG-D722

2016-08-18T00:58:49.048Z - info: Starting unit test run on 6 android devices

2016-08-18T00:58:49.473Z - info: Socket to device LGE-LG-D855 disconnected: transport close

2016-08-18T00:58:50.830Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-18T01:00:53.893Z - debug: Device presented: LGE-LG-D855 (cd59255a-13e0-47b8-a00b-142314aebf86) - android 5.0

2016-08-18T01:01:05.976Z - debug: Device presented: LGE-LG-D722 (0d181195-cff4-4034-9899-53c6d9a5c2b7) - android 5.0.2

2016-08-18T01:01:05.977Z - info: All 8 android devices are present

2016-08-18T01:01:05.978Z - info: Disqualifying device with unsupported hardware: LGE-LG-D855

2016-08-18T01:01:05.980Z - info: Disqualifying device with unsupported hardware: LGE-LG-D722

2016-08-18T01:01:05.982Z - info: Starting unit test run on 6 android devices

2016-08-18T01:01:06.369Z - info: Socket to device LGE-LG-D855 disconnected: transport close

2016-08-18T01:01:07.840Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-18T01:03:10.491Z - debug: Device presented: LGE-LG-D855 (7622567c-1150-4a6b-a54f-903a407c9588) - android 5.0

2016-08-18T01:03:23.672Z - debug: Device presented: LGE-LG-D722 (6025bee4-48dd-405a-bb6c-a9d47658383b) - android 5.0.2

2016-08-18T01:03:23.673Z - info: All 8 android devices are present

2016-08-18T01:03:23.673Z - info: Disqualifying device with unsupported hardware: LGE-LG-D855

2016-08-18T01:03:23.676Z - info: Disqualifying device with unsupported hardware: LGE-LG-D722

2016-08-18T01:03:23.678Z - info: Starting unit test run on 6 android devices

2016-08-18T01:03:24.786Z - info: Socket to device LGE-LG-D855 disconnected: transport close

2016-08-18T01:03:25.550Z - info: Socket to device LGE-LG-D722 disconnected: transport close


 
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
STOP log received from  0be0c6c6 Test has  SUCCEEDED
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
Device test finished on 0be0c6c6 
Android task is completed. [SUCCESS]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/81738796b06b234_Updating_to_handle_iOS_yaronyg/thali01_motorola-Nexus 6.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/81738796b06b234_Updating_to_handle_iOS_yaronyg/thali01_samsung-SM-G900F.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD855a6933058 Test has  SUCCEEDED
Device test finished on LGD855a6933058 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/81738796b06b234_Updating_to_handle_iOS_yaronyg/thali02_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/81738796b06b234_Updating_to_handle_iOS_yaronyg/thali02_LGE-LG-D855.md)

####Node name: thali03
Console output:
```
STOP log received from  f56ad48d Test has  SUCCEEDED
STOP log received from  7970f88c Test has  SUCCEEDED
Device test finished on f56ad48d 
Device test finished on 7970f88c 
Android task is completed. [SUCCESS]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/81738796b06b234_Updating_to_handle_iOS_yaronyg/thali03_samsung-SM-A500FU.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/81738796b06b234_Updating_to_handle_iOS_yaronyg/thali03_samsung-SM-A300FU.md)

####Node name: thali04
Console output:
```
STOP log received from  4325e43f Test has  SUCCEEDED
STOP log received from  HT54GYJ03048 Test has  SUCCEEDED
Device test finished on 4325e43f 
Device test finished on HT54GYJ03048 
Android task is completed. [SUCCESS]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/81738796b06b234_Updating_to_handle_iOS_yaronyg/thali04_samsung-SM-A300FU.md)

[HTC-HTC One M9](https://github.com/ThaliTester/TestResults/blob/81738796b06b234_Updating_to_handle_iOS_yaronyg/thali04_HTC-HTC One M9.md)





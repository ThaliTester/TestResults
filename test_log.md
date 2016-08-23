#### Test 817387969d88798 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":8}}
2016-08-23T01:30:58.698Z - info: Require 3 ios devices

2016-08-23T01:30:58.717Z - info: Require 3 android devices

2016-08-23T01:30:58.776Z - info: listening on *:3000

2016-08-23T01:31:00.307Z - debug: Device presented: samsung-SM-A300FU (48c7b6d4-876b-4200-9892-4323b8586323) - android 5.0.2

2016-08-23T01:31:00.562Z - debug: Device presented: samsung-SM-A500FU (a1c0a71e-9102-4b2a-9cf5-4156046f7160) - android 5.0.2

2016-08-23T01:31:00.644Z - debug: Device presented: samsung-SM-G900F (b084940c-c8e6-4c9f-bf36-66dff3fd340e) - android 6.0.1

2016-08-23T01:31:01.247Z - debug: Device presented: samsung-SM-A300FU (48c7b6d4-876b-4200-9892-4323b8586323) - android 5.0.2

2016-08-23T01:31:01.249Z - info: Updating existing device: samsung-SM-A300FU (48c7b6d4-876b-4200-9892-4323b8586323)

2016-08-23T01:31:01.529Z - debug: Device presented: samsung-SM-A500FU (a1c0a71e-9102-4b2a-9cf5-4156046f7160) - android 5.0.2

2016-08-23T01:31:01.530Z - info: Updating existing device: samsung-SM-A500FU (a1c0a71e-9102-4b2a-9cf5-4156046f7160)

2016-08-23T01:31:01.657Z - debug: Device presented: samsung-SM-G900F (b084940c-c8e6-4c9f-bf36-66dff3fd340e) - android 6.0.1

2016-08-23T01:31:01.658Z - info: Updating existing device: samsung-SM-G900F (b084940c-c8e6-4c9f-bf36-66dff3fd340e)

2016-08-23T01:31:01.737Z - debug: Device presented: samsung-SM-A300FU (8ce1b29b-092e-41e7-95b8-4ee80c5bec98) - android 5.0.2

2016-08-23T01:31:02.613Z - debug: Device presented: HTC-HTC One M9 (33f669c6-e8b3-48c2-aa2e-7b5a67c8e52b) - android 5.1

2016-08-23T01:31:02.622Z - debug: Device presented: motorola-Nexus 6 (159004b2-a02b-40a8-b574-edc81b5a572e) - android 6.0.1

2016-08-23T01:31:02.716Z - debug: Device presented: samsung-SM-A300FU (8ce1b29b-092e-41e7-95b8-4ee80c5bec98) - android 5.0.2

2016-08-23T01:31:02.717Z - info: Updating existing device: samsung-SM-A300FU (8ce1b29b-092e-41e7-95b8-4ee80c5bec98)

2016-08-23T01:31:03.624Z - debug: Device presented: HTC-HTC One M9 (33f669c6-e8b3-48c2-aa2e-7b5a67c8e52b) - android 5.1

2016-08-23T01:31:03.625Z - info: Updating existing device: HTC-HTC One M9 (33f669c6-e8b3-48c2-aa2e-7b5a67c8e52b)

2016-08-23T01:31:03.630Z - debug: Device presented: motorola-Nexus 6 (159004b2-a02b-40a8-b574-edc81b5a572e) - android 6.0.1

2016-08-23T01:31:03.631Z - info: Updating existing device: motorola-Nexus 6 (159004b2-a02b-40a8-b574-edc81b5a572e)

2016-08-23T01:33:03.016Z - debug: Device presented: LGE-LG-D855 (05de4d89-3dab-431e-8360-4b54800d9cc7) - android 5.0

2016-08-23T01:33:09.048Z - debug: Device presented: LGE-LG-D722 (e56c53c3-5c85-4aeb-9fec-6cdb00ad4046) - android 5.0.2

2016-08-23T01:33:09.049Z - info: All 8 android devices are present

2016-08-23T01:33:09.051Z - info: Disqualifying device with unsupported hardware: LGE-LG-D855

2016-08-23T01:33:09.058Z - info: Disqualifying device with unsupported hardware: LGE-LG-D722

2016-08-23T01:33:09.065Z - info: Starting unit test run on 6 android devices

2016-08-23T01:33:10.014Z - info: Running on android test: 1. onPeerLost calls jxcore

2016-08-23T01:33:10.539Z - info: Socket to device LGE-LG-D855 disconnected: transport close

2016-08-23T01:33:10.908Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-23T01:33:13.878Z - info: Running on android test: 2. onPeerDiscovered calls jxcore

2016-08-23T01:33:17.247Z - info: Test run on android complete

2016-08-23T01:33:17.249Z - info: 

-== UNIT TEST RESULTS ==-

2016-08-23T01:33:17.251Z - info: PLATFORM: android

2016-08-23T01:33:17.252Z - info: RESULT: PASS

2016-08-23T01:33:17.253Z - info: 2 of 2 tests completed

2016-08-23T01:33:17.257Z - info: 2/2 passed (0 failures)
2016-08-23T01:33:17.258Z - info: 

-== END ==-

2016-08-23T01:33:17.920Z - info: Socket to device samsung-SM-A300FU disconnected: transport close

2016-08-23T01:33:17.943Z - info: Socket to device samsung-SM-A500FU disconnected: transport close

2016-08-23T01:33:18.086Z - info: Socket to device samsung-SM-A300FU disconnected: transport close

2016-08-23T01:33:18.174Z - info: Socket to device motorola-Nexus 6 disconnected: transport close

2016-08-23T01:33:18.296Z - info: Socket to device HTC-HTC One M9 disconnected: transport close

2016-08-23T01:33:19.100Z - info: Socket to device samsung-SM-G900F disconnected: transport close

2016-08-23T01:35:25.859Z - debug: Device presented: LGE-LG-D722 (877b91f6-5868-4c71-a362-88e9f8bcd7d2) - android 5.0.2

2016-08-23T01:54:25.682Z - info: Socket to device LGE-LG-D722 disconnected: transport close


 
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
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/817387969d88798_Updating_to_handle_iOS_yaronyg/thali01_motorola-Nexus 6.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/817387969d88798_Updating_to_handle_iOS_yaronyg/thali01_samsung-SM-G900F.md)

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
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/817387969d88798_Updating_to_handle_iOS_yaronyg/thali02_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/817387969d88798_Updating_to_handle_iOS_yaronyg/thali02_LGE-LG-D855.md)

####Node name: thali03
Console output:
```
STOP log received from  7970f88c Test has  SUCCEEDED
STOP log received from  f56ad48d Test has  SUCCEEDED
Device test finished on f56ad48d 
Device test finished on 7970f88c 
Android task is completed. [SUCCESS]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/817387969d88798_Updating_to_handle_iOS_yaronyg/thali03_samsung-SM-A500FU.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/817387969d88798_Updating_to_handle_iOS_yaronyg/thali03_samsung-SM-A300FU.md)

####Node name: thali04
Console output:
```
STOP log received from  4325e43f Test has  SUCCEEDED
STOP log received from  HT54GYJ03048 Test has  SUCCEEDED
Device test finished on 4325e43f 
Device test finished on HT54GYJ03048 
Android task is completed. [SUCCESS]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/817387969d88798_Updating_to_handle_iOS_yaronyg/thali04_samsung-SM-A300FU.md)

[HTC-HTC One M9](https://github.com/ThaliTester/TestResults/blob/817387969d88798_Updating_to_handle_iOS_yaronyg/thali04_HTC-HTC One M9.md)





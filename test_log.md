#### Test 807613749c91828 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":8}}
2016-08-17T08:25:38.342Z - info: Require 3 ios devices

2016-08-17T08:25:38.360Z - info: Require 3 android devices

2016-08-17T08:25:38.420Z - info: listening on *:3000

2016-08-17T08:25:39.270Z - debug: Device presented: samsung-SM-A300FU (8af65ba0-5221-478a-97b4-f5c04af6b215) - android 5.0.2

2016-08-17T08:25:39.423Z - debug: Device presented: HTC-HTC One M9 (cce6de7d-445d-4b03-bd47-f0b4c2608fac) - android 5.1

2016-08-17T08:25:40.218Z - debug: Device presented: samsung-SM-A300FU (8af65ba0-5221-478a-97b4-f5c04af6b215) - android 5.0.2

2016-08-17T08:25:40.219Z - info: Updating existing device: samsung-SM-A300FU (8af65ba0-5221-478a-97b4-f5c04af6b215)

2016-08-17T08:25:40.414Z - debug: Device presented: HTC-HTC One M9 (cce6de7d-445d-4b03-bd47-f0b4c2608fac) - android 5.1

2016-08-17T08:25:40.416Z - info: Updating existing device: HTC-HTC One M9 (cce6de7d-445d-4b03-bd47-f0b4c2608fac)

2016-08-17T08:25:40.673Z - debug: Device presented: samsung-SM-A300FU (e01978fb-41d9-41eb-808a-b9ca8b803295) - android 5.0.2

2016-08-17T08:25:41.096Z - debug: Device presented: samsung-SM-G900F (3075f7c9-e88b-4593-8ed0-2891ff8b1b74) - android 6.0.1

2016-08-17T08:25:41.285Z - debug: Device presented: samsung-SM-A500FU (00dc4871-a721-40c3-a9c2-f72643d2e0a8) - android 5.0.2

2016-08-17T08:25:41.623Z - debug: Device presented: motorola-Nexus 6 (a34012bf-fd6e-47db-831a-79bfc724006b) - android 6.0.1

2016-08-17T08:25:41.653Z - debug: Device presented: samsung-SM-A300FU (e01978fb-41d9-41eb-808a-b9ca8b803295) - android 5.0.2

2016-08-17T08:25:41.655Z - info: Updating existing device: samsung-SM-A300FU (e01978fb-41d9-41eb-808a-b9ca8b803295)

2016-08-17T08:25:42.130Z - debug: Device presented: samsung-SM-G900F (3075f7c9-e88b-4593-8ed0-2891ff8b1b74) - android 6.0.1

2016-08-17T08:25:42.131Z - info: Updating existing device: samsung-SM-G900F (3075f7c9-e88b-4593-8ed0-2891ff8b1b74)

2016-08-17T08:25:42.272Z - debug: Device presented: samsung-SM-A500FU (00dc4871-a721-40c3-a9c2-f72643d2e0a8) - android 5.0.2

2016-08-17T08:25:42.275Z - info: Updating existing device: samsung-SM-A500FU (00dc4871-a721-40c3-a9c2-f72643d2e0a8)

2016-08-17T08:25:42.597Z - debug: Device presented: motorola-Nexus 6 (a34012bf-fd6e-47db-831a-79bfc724006b) - android 6.0.1

2016-08-17T08:25:42.599Z - info: Updating existing device: motorola-Nexus 6 (a34012bf-fd6e-47db-831a-79bfc724006b)

2016-08-17T08:27:40.075Z - debug: Device presented: LGE-LG-D855 (970a17aa-55e0-4ff3-ac76-3d910668e389) - android 5.0

2016-08-17T08:27:48.530Z - debug: Device presented: LGE-LG-D722 (e0a34912-368f-45f5-8d06-b044f7065766) - android 5.0.2

2016-08-17T08:27:48.531Z - info: All 8 android devices are present

2016-08-17T08:27:48.533Z - info: Disqualifying device with unsupported hardware: LGE-LG-D855

2016-08-17T08:27:48.540Z - info: Disqualifying device with unsupported hardware: LGE-LG-D722

2016-08-17T08:27:48.548Z - info: Starting unit test run on 6 android devices

2016-08-17T08:27:49.167Z - info: Running on android test: 1. onPeerLost calls jxcore

2016-08-17T08:27:49.614Z - info: Socket to device LGE-LG-D855 disconnected: transport close

2016-08-17T08:27:49.635Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-17T08:27:52.822Z - info: Running on android test: 2. onPeerDiscovered calls jxcore

2016-08-17T08:27:55.999Z - info: Test run on android complete

2016-08-17T08:27:56.003Z - info: 

-== UNIT TEST RESULTS ==-

2016-08-17T08:27:56.005Z - info: PLATFORM: android

2016-08-17T08:27:56.006Z - info: RESULT: PASS

2016-08-17T08:27:56.007Z - info: 2 of 2 tests completed

2016-08-17T08:27:56.008Z - info: 2/2 passed (0 failures)
2016-08-17T08:27:56.009Z - info: 

-== END ==-

2016-08-17T08:27:56.671Z - info: Socket to device samsung-SM-A500FU disconnected: transport close

2016-08-17T08:27:56.717Z - info: Socket to device samsung-SM-A300FU disconnected: transport close

2016-08-17T08:27:56.769Z - info: Socket to device samsung-SM-A300FU disconnected: transport close

2016-08-17T08:27:56.978Z - info: Socket to device motorola-Nexus 6 disconnected: transport close

2016-08-17T08:27:57.045Z - info: Socket to device HTC-HTC One M9 disconnected: transport close

2016-08-17T08:27:57.953Z - info: Socket to device samsung-SM-G900F disconnected: transport close


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

android : No Error
```


###Android Logs
####Node name: thali01
Console output:
```

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
STOP log received from  0be0c6c6 Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
Device test finished on 0be0c6c6 
Android task is completed. [SUCCESS]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/807613749c91828__777_Additional_native_unit_tests_mlesnic/thali01_motorola-Nexus 6.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/807613749c91828__777_Additional_native_unit_tests_mlesnic/thali01_samsung-SM-G900F.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  LGD855a6933058 Test has  SUCCEEDED
Device test finished on LGD855a6933058 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/807613749c91828__777_Additional_native_unit_tests_mlesnic/thali02_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/807613749c91828__777_Additional_native_unit_tests_mlesnic/thali02_LGE-LG-D855.md)

####Node name: thali03
Console output:
```
STOP log received from  7970f88c Test has  SUCCEEDED
STOP log received from  f56ad48d Test has  SUCCEEDED
Device test finished on 7970f88c 
Device test finished on f56ad48d 
Android task is completed. [SUCCESS]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/807613749c91828__777_Additional_native_unit_tests_mlesnic/thali03_samsung-SM-A500FU.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/807613749c91828__777_Additional_native_unit_tests_mlesnic/thali03_samsung-SM-A300FU.md)

####Node name: thali04
Console output:
```
STOP log received from  4325e43f Test has  SUCCEEDED
STOP log received from  HT54GYJ03048 Test has  SUCCEEDED
Device test finished on 4325e43f 
Device test finished on HT54GYJ03048 
Android task is completed. [SUCCESS]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/807613749c91828__777_Additional_native_unit_tests_mlesnic/thali04_samsung-SM-A300FU.md)

[HTC-HTC One M9](https://github.com/ThaliTester/TestResults/blob/807613749c91828__777_Additional_native_unit_tests_mlesnic/thali04_HTC-HTC One M9.md)



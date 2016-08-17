#### Test 807688564f75085 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":8}}
2016-08-17T13:22:00.283Z - info: Require 3 ios devices

2016-08-17T13:22:00.302Z - info: Require 3 android devices

2016-08-17T13:22:00.362Z - info: listening on *:3000

2016-08-17T13:22:01.336Z - debug: Device presented: samsung-SM-A500FU (02475e9f-7afc-4bd6-9dc3-9432ad7b7baf) - android 5.0.2

2016-08-17T13:22:01.343Z - debug: Device presented: motorola-Nexus 6 (ed90412c-12f0-480a-8361-d2126fddb095) - android 6.0.1

2016-08-17T13:22:01.348Z - debug: Device presented: samsung-SM-G900F (d1599f22-93f1-4124-8193-4619d99b4066) - android 6.0.1

2016-08-17T13:22:01.471Z - debug: Device presented: samsung-SM-A300FU (b6df1297-7062-4e6e-8dd9-9f2c87881aee) - android 5.0.2

2016-08-17T13:22:02.211Z - debug: Device presented: motorola-Nexus 6 (ed90412c-12f0-480a-8361-d2126fddb095) - android 6.0.1

2016-08-17T13:22:02.214Z - info: Updating existing device: motorola-Nexus 6 (ed90412c-12f0-480a-8361-d2126fddb095)

2016-08-17T13:22:02.263Z - debug: Device presented: samsung-SM-A500FU (02475e9f-7afc-4bd6-9dc3-9432ad7b7baf) - android 5.0.2

2016-08-17T13:22:02.264Z - info: Updating existing device: samsung-SM-A500FU (02475e9f-7afc-4bd6-9dc3-9432ad7b7baf)

2016-08-17T13:22:02.324Z - debug: Device presented: samsung-SM-G900F (d1599f22-93f1-4124-8193-4619d99b4066) - android 6.0.1

2016-08-17T13:22:02.325Z - info: Updating existing device: samsung-SM-G900F (d1599f22-93f1-4124-8193-4619d99b4066)

2016-08-17T13:22:02.457Z - debug: Device presented: samsung-SM-A300FU (b6df1297-7062-4e6e-8dd9-9f2c87881aee) - android 5.0.2

2016-08-17T13:22:02.458Z - info: Updating existing device: samsung-SM-A300FU (b6df1297-7062-4e6e-8dd9-9f2c87881aee)

2016-08-17T13:22:02.606Z - debug: Device presented: samsung-SM-A300FU (b6d58db4-6beb-4c6e-84af-d797c99159d5) - android 5.0.2

2016-08-17T13:22:02.658Z - debug: Device presented: HTC-HTC One M9 (44a681e4-36f9-4a5b-a851-42b516851d53) - android 5.1

2016-08-17T13:22:03.597Z - debug: Device presented: samsung-SM-A300FU (b6d58db4-6beb-4c6e-84af-d797c99159d5) - android 5.0.2

2016-08-17T13:22:03.598Z - info: Updating existing device: samsung-SM-A300FU (b6d58db4-6beb-4c6e-84af-d797c99159d5)

2016-08-17T13:22:03.645Z - debug: Device presented: HTC-HTC One M9 (44a681e4-36f9-4a5b-a851-42b516851d53) - android 5.1

2016-08-17T13:22:03.646Z - info: Updating existing device: HTC-HTC One M9 (44a681e4-36f9-4a5b-a851-42b516851d53)

2016-08-17T13:23:58.723Z - debug: Device presented: LGE-LG-D855 (be507c39-0da7-4d45-90f7-5c655d8ec9fe) - android 5.0

2016-08-17T13:24:10.305Z - debug: Device presented: LGE-LG-D722 (95965ed6-4592-4060-a7cc-1cad5803471a) - android 5.0.2

2016-08-17T13:24:10.306Z - info: All 8 android devices are present

2016-08-17T13:24:10.309Z - info: Disqualifying device with unsupported hardware: LGE-LG-D855

2016-08-17T13:24:10.316Z - info: Disqualifying device with unsupported hardware: LGE-LG-D722

2016-08-17T13:24:10.324Z - info: Starting unit test run on 6 android devices

2016-08-17T13:24:10.704Z - info: Running on android test: 1. onPeerLost calls jxcore

2016-08-17T13:24:11.385Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-17T13:24:11.407Z - info: Socket to device LGE-LG-D855 disconnected: transport close

2016-08-17T13:24:13.288Z - info: Running on android test: 2. onPeerDiscovered calls jxcore

2016-08-17T13:24:15.751Z - info: Test run on android complete

2016-08-17T13:24:15.753Z - info: 

-== UNIT TEST RESULTS ==-

2016-08-17T13:24:15.754Z - info: PLATFORM: android

2016-08-17T13:24:15.758Z - info: RESULT: PASS

2016-08-17T13:24:15.759Z - info: 2 of 2 tests completed

2016-08-17T13:24:15.760Z - info: 2/2 passed (0 failures)
2016-08-17T13:24:15.761Z - info: 

-== END ==-

2016-08-17T13:24:16.426Z - info: Socket to device samsung-SM-A300FU disconnected: transport close

2016-08-17T13:24:16.433Z - info: Socket to device samsung-SM-A500FU disconnected: transport close

2016-08-17T13:24:16.450Z - info: Socket to device samsung-SM-A300FU disconnected: transport close

2016-08-17T13:24:17.153Z - info: Socket to device HTC-HTC One M9 disconnected: transport close

2016-08-17T13:24:17.303Z - info: Socket to device motorola-Nexus 6 disconnected: transport close

2016-08-17T13:24:17.674Z - info: Socket to device samsung-SM-G900F disconnected: transport close


 
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
STOP log received from  0be0c6c6 Test has  SUCCEEDED
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
Device test finished on 0be0c6c6 
Android task is completed. [SUCCESS]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/807688564f75085__697_Fixed_setInterval_battery_abuse_artemjackson/thali01_motorola-Nexus 6.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/807688564f75085__697_Fixed_setInterval_battery_abuse_artemjackson/thali01_samsung-SM-G900F.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  LGD855a6933058 Test has  SUCCEEDED
Device test finished on LGD855a6933058 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/807688564f75085__697_Fixed_setInterval_battery_abuse_artemjackson/thali02_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/807688564f75085__697_Fixed_setInterval_battery_abuse_artemjackson/thali02_LGE-LG-D855.md)

####Node name: thali03
Console output:
```
STOP log received from  f56ad48d Test has  SUCCEEDED
STOP log received from  7970f88c Test has  SUCCEEDED
Device test finished on 7970f88c 
Device test finished on f56ad48d 
Android task is completed. [SUCCESS]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/807688564f75085__697_Fixed_setInterval_battery_abuse_artemjackson/thali03_samsung-SM-A500FU.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/807688564f75085__697_Fixed_setInterval_battery_abuse_artemjackson/thali03_samsung-SM-A300FU.md)

####Node name: thali04
Console output:
```
STOP log received from  4325e43f Test has  SUCCEEDED
STOP log received from  HT54GYJ03048 Test has  SUCCEEDED
Device test finished on 4325e43f 
Device test finished on HT54GYJ03048 
Android task is completed. [SUCCESS]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/807688564f75085__697_Fixed_setInterval_battery_abuse_artemjackson/thali04_samsung-SM-A300FU.md)

[HTC-HTC One M9](https://github.com/ThaliTester/TestResults/blob/807688564f75085__697_Fixed_setInterval_battery_abuse_artemjackson/thali04_HTC-HTC One M9.md)



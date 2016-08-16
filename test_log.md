#### Test 80761374059c81f Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":8}}
2016-08-16T15:17:12.855Z - info: Require 3 ios devices

2016-08-16T15:17:12.874Z - info: Require 3 android devices

2016-08-16T15:17:12.935Z - info: listening on *:3000

2016-08-16T15:17:13.345Z - debug: Device presented: samsung-SM-A300FU (fdcae2a0-29a5-46b6-937b-c05404ac44ec) - android 5.0.2

2016-08-16T15:17:14.259Z - debug: Device presented: HTC-HTC One M9 (488ac546-fba4-4701-b5dd-d09bdd7ebbf9) - android 5.1

2016-08-16T15:17:14.290Z - debug: Device presented: samsung-SM-A300FU (fdcae2a0-29a5-46b6-937b-c05404ac44ec) - android 5.0.2

2016-08-16T15:17:14.291Z - info: Updating existing device: samsung-SM-A300FU (fdcae2a0-29a5-46b6-937b-c05404ac44ec)

2016-08-16T15:17:15.254Z - debug: Device presented: HTC-HTC One M9 (488ac546-fba4-4701-b5dd-d09bdd7ebbf9) - android 5.1

2016-08-16T15:17:15.255Z - info: Updating existing device: HTC-HTC One M9 (488ac546-fba4-4701-b5dd-d09bdd7ebbf9)

2016-08-16T15:17:16.465Z - debug: Device presented: samsung-SM-A300FU (e0867590-a07f-48df-8857-838b50b031ef) - android 5.0.2

2016-08-16T15:17:17.439Z - debug: Device presented: samsung-SM-A300FU (e0867590-a07f-48df-8857-838b50b031ef) - android 5.0.2

2016-08-16T15:17:17.440Z - info: Updating existing device: samsung-SM-A300FU (e0867590-a07f-48df-8857-838b50b031ef)

2016-08-16T15:17:17.456Z - debug: Device presented: samsung-SM-A500FU (f33da79d-12e4-4804-a2e1-85f68c675fe5) - android 5.0.2

2016-08-16T15:17:17.590Z - debug: Device presented: samsung-SM-G900F (c789c560-8eaa-47af-93d6-6084bcbce820) - android 6.0.1

2016-08-16T15:17:17.828Z - debug: Device presented: motorola-Nexus 6 (7af30885-a2ed-4f7a-9897-c49110fcae9f) - android 6.0.1

2016-08-16T15:17:18.437Z - debug: Device presented: samsung-SM-A500FU (f33da79d-12e4-4804-a2e1-85f68c675fe5) - android 5.0.2

2016-08-16T15:17:18.438Z - info: Updating existing device: samsung-SM-A500FU (f33da79d-12e4-4804-a2e1-85f68c675fe5)

2016-08-16T15:17:18.606Z - debug: Device presented: samsung-SM-G900F (c789c560-8eaa-47af-93d6-6084bcbce820) - android 6.0.1

2016-08-16T15:17:18.607Z - info: Updating existing device: samsung-SM-G900F (c789c560-8eaa-47af-93d6-6084bcbce820)

2016-08-16T15:17:18.824Z - debug: Device presented: motorola-Nexus 6 (7af30885-a2ed-4f7a-9897-c49110fcae9f) - android 6.0.1

2016-08-16T15:17:18.825Z - info: Updating existing device: motorola-Nexus 6 (7af30885-a2ed-4f7a-9897-c49110fcae9f)

2016-08-16T15:19:11.610Z - debug: Device presented: LGE-LG-D855 (7b265c91-7cf2-4d9d-880a-de5664f07bbe) - android 5.0

2016-08-16T15:19:23.090Z - debug: Device presented: LGE-LG-D722 (b3489fb5-fc7e-4233-bc47-13c876eadd22) - android 5.0.2

2016-08-16T15:19:23.091Z - info: All 8 android devices are present

2016-08-16T15:19:23.093Z - info: Disqualifying device with unsupported hardware: LGE-LG-D855

2016-08-16T15:19:23.101Z - info: Disqualifying device with unsupported hardware: LGE-LG-D722

2016-08-16T15:19:23.108Z - info: Starting unit test run on 6 android devices

2016-08-16T15:19:23.367Z - info: Running on android test: 1. onPeerLost calls jxcore

2016-08-16T15:19:24.022Z - info: Socket to device LGE-LG-D855 disconnected: transport close

2016-08-16T15:19:24.160Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-16T15:19:25.915Z - info: Running on android test: 2. onPeerDiscovered calls jxcore

2016-08-16T15:19:29.653Z - info: Test run on android complete

2016-08-16T15:19:29.656Z - info: 

-== UNIT TEST RESULTS ==-

2016-08-16T15:19:29.657Z - info: PLATFORM: android

2016-08-16T15:19:29.658Z - info: RESULT: PASS

2016-08-16T15:19:29.660Z - info: 2 of 2 tests completed

2016-08-16T15:19:29.663Z - info: 2/2 passed (0 failures)
2016-08-16T15:19:29.664Z - info: 

-== END ==-

2016-08-16T15:19:30.303Z - info: Socket to device samsung-SM-A300FU disconnected: transport close

2016-08-16T15:19:30.380Z - info: Socket to device samsung-SM-A300FU disconnected: transport close

2016-08-16T15:19:30.388Z - info: Socket to device samsung-SM-A500FU disconnected: transport close

2016-08-16T15:19:30.531Z - info: Socket to device HTC-HTC One M9 disconnected: transport close

2016-08-16T15:19:30.674Z - info: Socket to device motorola-Nexus 6 disconnected: transport close

2016-08-16T15:19:32.287Z - info: Socket to device samsung-SM-G900F disconnected: transport close


 
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
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/80761374059c81f__777_Additional_native_unit_tests_mlesnic/thali01_motorola-Nexus 6.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/80761374059c81f__777_Additional_native_unit_tests_mlesnic/thali01_samsung-SM-G900F.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  LGD855a6933058 Test has  SUCCEEDED
Device test finished on LGD855a6933058 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/80761374059c81f__777_Additional_native_unit_tests_mlesnic/thali02_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/80761374059c81f__777_Additional_native_unit_tests_mlesnic/thali02_LGE-LG-D855.md)

####Node name: thali03
Console output:
```
STOP log received from  7970f88c Test has  SUCCEEDED
STOP log received from  f56ad48d Test has  SUCCEEDED
Device test finished on 7970f88c 
Device test finished on f56ad48d 
Android task is completed. [SUCCESS]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/80761374059c81f__777_Additional_native_unit_tests_mlesnic/thali03_samsung-SM-A500FU.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/80761374059c81f__777_Additional_native_unit_tests_mlesnic/thali03_samsung-SM-A300FU.md)

####Node name: thali04
Console output:
```
STOP log received from  4325e43f Test has  SUCCEEDED
STOP log received from  HT54GYJ03048 Test has  SUCCEEDED
Device test finished on 4325e43f 
Device test finished on HT54GYJ03048 
Android task is completed. [SUCCESS]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/80761374059c81f__777_Additional_native_unit_tests_mlesnic/thali04_samsung-SM-A300FU.md)

[HTC-HTC One M9](https://github.com/ThaliTester/TestResults/blob/80761374059c81f__777_Additional_native_unit_tests_mlesnic/thali04_HTC-HTC One M9.md)



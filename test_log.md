#### Test 79751015f24a8ad Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":4}}
2016-08-12T15:17:48.890Z - info: Require 0 ios devices

2016-08-12T15:17:48.909Z - info: Require 4 android devices

2016-08-12T15:17:48.969Z - info: listening on *:3000

2016-08-12T15:17:50.180Z - debug: Device presented: samsung-SM-G900F (b2419731-a900-4d13-a08d-e6b17edf3b00) - android 6.0.1

2016-08-12T15:17:51.213Z - debug: Device presented: samsung-SM-G900F (b2419731-a900-4d13-a08d-e6b17edf3b00) - android 6.0.1

2016-08-12T15:17:51.215Z - info: Updating existing device: samsung-SM-G900F (b2419731-a900-4d13-a08d-e6b17edf3b00)

2016-08-12T15:17:53.553Z - debug: Device presented: motorola-Nexus 6 (8083de91-f009-4592-ae9f-dcb5f551d6a1) - android 6.0.1

2016-08-12T15:17:54.543Z - debug: Device presented: motorola-Nexus 6 (8083de91-f009-4592-ae9f-dcb5f551d6a1) - android 6.0.1

2016-08-12T15:17:54.544Z - info: Updating existing device: motorola-Nexus 6 (8083de91-f009-4592-ae9f-dcb5f551d6a1)

2016-08-12T15:18:09.270Z - debug: Device presented: LGE-LG-D855 (acf5e352-c542-4e91-913d-f58363f86bcf) - android 5.0

2016-08-12T15:18:22.989Z - debug: Device presented: LGE-LG-D722 (d431285f-af95-4dad-9caa-2881be4e9d83) - android 5.0.2

2016-08-12T15:18:22.990Z - info: All 4 android devices are present

2016-08-12T15:18:22.992Z - info: Disqualifying device with unsupported hardware: LGE-LG-D855

2016-08-12T15:18:22.999Z - info: Disqualifying device with unsupported hardware: LGE-LG-D722

2016-08-12T15:18:23.007Z - warn: Aborting unit test run for android. At least 2 devices needed, having 2 device(s)

2016-08-12T15:18:23.009Z - info: Test run on android aborted

2016-08-12T15:18:23.012Z - info: 

-== UNIT TEST RESULTS ==-

2016-08-12T15:18:23.013Z - info: PLATFORM: android

2016-08-12T15:18:23.014Z - info: RESULT: FAIL

2016-08-12T15:18:23.016Z - info: 0 of 179 tests completed

2016-08-12T15:18:23.017Z - info: 0/179 passed (179 failures)

2016-08-12T15:18:23.018Z - info: 

--- Failed tests ---

2016-08-12T15:18:23.019Z - info: 

-== END ==-

2016-08-12T15:18:23.024Z - info: Starting unit test run on 2 android devices

2016-08-12T15:18:23.874Z - info: Socket to device LGE-LG-D855 disconnected: transport close

2016-08-12T15:18:24.038Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-12T15:18:24.079Z - info: Socket to device motorola-Nexus 6 disconnected: transport close

2016-08-12T15:18:24.180Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-08-12T15:18:24.957Z - info: Socket to device samsung-SM-G900F disconnected: transport close


 
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
STOP log received from  ZX1G429CRK Test has  FAILED
STOP log received from  0be0c6c6 Test has  FAILED
Device test finished on ZX1G429CRK 
Device test finished on 0be0c6c6 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/79751015f24a8ad_Check_811_failures_in_CI_do_not_merge__czyzm/thali01_motorola-Nexus 6.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/79751015f24a8ad_Check_811_failures_in_CI_do_not_merge__czyzm/thali01_samsung-SM-G900F.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  LGD855a6933058 Test has  SUCCEEDED
Device test finished on LGD855a6933058 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/79751015f24a8ad_Check_811_failures_in_CI_do_not_merge__czyzm/thali02_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/79751015f24a8ad_Check_811_failures_in_CI_do_not_merge__czyzm/thali02_LGE-LG-D855.md)





#### Test 797510151684451 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":4}}
2016-08-12T16:39:28.035Z - info: Require 0 ios devices

2016-08-12T16:39:28.054Z - info: Require 4 android devices

2016-08-12T16:39:28.117Z - info: listening on *:3000

2016-08-12T16:39:31.078Z - debug: Device presented: samsung-SM-G900F (e338c63c-4561-4bfe-829b-112359eaf6fe) - android 6.0.1

2016-08-12T16:39:32.032Z - debug: Device presented: samsung-SM-G900F (e338c63c-4561-4bfe-829b-112359eaf6fe) - android 6.0.1

2016-08-12T16:39:32.034Z - info: Updating existing device: samsung-SM-G900F (e338c63c-4561-4bfe-829b-112359eaf6fe)

2016-08-12T16:39:32.399Z - debug: Device presented: motorola-Nexus 6 (80618e24-1a72-463f-8cf1-19c9a5a46cb7) - android 6.0.1

2016-08-12T16:39:33.347Z - debug: Device presented: motorola-Nexus 6 (80618e24-1a72-463f-8cf1-19c9a5a46cb7) - android 6.0.1

2016-08-12T16:39:33.349Z - info: Updating existing device: motorola-Nexus 6 (80618e24-1a72-463f-8cf1-19c9a5a46cb7)

2016-08-12T16:39:49.067Z - debug: Device presented: LGE-LG-D855 (d9042ebf-30de-4577-9007-bafef7deacda) - android 5.0

2016-08-12T16:40:01.614Z - debug: Device presented: LGE-LG-D722 (e9b669b8-5970-4dd5-a900-12d06aebae1c) - android 5.0.2

2016-08-12T16:40:01.616Z - info: All 4 android devices are present

2016-08-12T16:40:01.618Z - info: Disqualifying device with unsupported hardware: LGE-LG-D855

2016-08-12T16:40:01.627Z - info: Disqualifying device with unsupported hardware: LGE-LG-D722

2016-08-12T16:40:01.635Z - warn: Aborting unit test run for android. At least 2 devices needed, having 2 device(s)

2016-08-12T16:40:01.637Z - info: Test run on android aborted

2016-08-12T16:40:01.640Z - info: 

-== UNIT TEST RESULTS ==-

2016-08-12T16:40:01.641Z - info: PLATFORM: android

2016-08-12T16:40:01.642Z - info: RESULT: FAIL

2016-08-12T16:40:01.644Z - info: 0 of 179 tests completed

2016-08-12T16:40:01.645Z - info: 0/179 passed (179 failures)

2016-08-12T16:40:01.646Z - info: 

--- Failed tests ---

2016-08-12T16:40:01.647Z - info: 

-== END ==-

2016-08-12T16:40:02.455Z - info: Socket to device LGE-LG-D855 disconnected: transport close

2016-08-12T16:40:02.571Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-12T16:40:02.794Z - info: Socket to device motorola-Nexus 6 disconnected: transport close

2016-08-12T16:40:04.313Z - info: Socket to device samsung-SM-G900F disconnected: transport close


 
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
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/797510151684451_Check_811_failures_in_CI_do_not_merge__czyzm/thali01_motorola-Nexus 6.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/797510151684451_Check_811_failures_in_CI_do_not_merge__czyzm/thali01_samsung-SM-G900F.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  LGD855a6933058 Test has  SUCCEEDED
Device test finished on LGD855a6933058 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/797510151684451_Check_811_failures_in_CI_do_not_merge__czyzm/thali02_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/797510151684451_Check_811_failures_in_CI_do_not_merge__czyzm/thali02_LGE-LG-D855.md)





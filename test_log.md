#### Test 79751015007586f Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":4}}
2016-08-12T20:30:42.746Z - info: Require 0 ios devices

2016-08-12T20:30:42.764Z - info: Require 4 android devices

2016-08-12T20:30:42.824Z - info: listening on *:3000

2016-08-12T20:30:46.575Z - debug: Device presented: samsung-SM-G900F (feb7f39e-6872-4f7e-b22e-f8347ff14102) - android 6.0.1

2016-08-12T20:30:47.609Z - debug: Device presented: samsung-SM-G900F (feb7f39e-6872-4f7e-b22e-f8347ff14102) - android 6.0.1

2016-08-12T20:30:47.612Z - info: Updating existing device: samsung-SM-G900F (feb7f39e-6872-4f7e-b22e-f8347ff14102)

2016-08-12T20:30:48.148Z - debug: Device presented: motorola-Nexus 6 (2aca2333-3110-4657-a7ae-8fd3f432b1e3) - android 6.0.1

2016-08-12T20:30:49.129Z - debug: Device presented: motorola-Nexus 6 (2aca2333-3110-4657-a7ae-8fd3f432b1e3) - android 6.0.1

2016-08-12T20:30:49.131Z - info: Updating existing device: motorola-Nexus 6 (2aca2333-3110-4657-a7ae-8fd3f432b1e3)

2016-08-12T20:31:03.437Z - debug: Device presented: LGE-LG-D855 (99a94b5f-2422-4ff9-950d-884b2a45acbe) - android 5.0

2016-08-12T20:31:16.671Z - debug: Device presented: LGE-LG-D722 (e97a70cc-5b6a-420f-91a2-8fbde0c33890) - android 5.0.2

2016-08-12T20:31:16.673Z - info: All 4 android devices are present

2016-08-12T20:31:16.675Z - info: Disqualifying device on which native unit tests failed: samsung-SM-G900F

2016-08-12T20:31:16.682Z - info: Disqualifying device on which native unit tests failed: motorola-Nexus 6

2016-08-12T20:31:16.684Z - info: Disqualifying device with unsupported hardware: LGE-LG-D855

2016-08-12T20:31:16.686Z - info: Disqualifying device with unsupported hardware: LGE-LG-D722

2016-08-12T20:31:16.692Z - warn: Aborting unit test run for android. At least 2 devices needed, having 0 device(s)

2016-08-12T20:31:16.695Z - info: Test run on android aborted

2016-08-12T20:31:16.697Z - info: 

-== UNIT TEST RESULTS ==-

2016-08-12T20:31:16.698Z - info: PLATFORM: android

2016-08-12T20:31:16.699Z - info: RESULT: PASS

2016-08-12T20:31:16.700Z - info: 0 of 0 tests completed

2016-08-12T20:31:16.702Z - info: 0/0 passed (0 failures)

2016-08-12T20:31:16.703Z - info: 

-== END ==-

2016-08-12T20:31:17.554Z - info: Socket to device LGE-LG-D855 disconnected: transport close

2016-08-12T20:31:17.641Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-12T20:31:17.856Z - info: Socket to device motorola-Nexus 6 disconnected: transport close

2016-08-12T20:31:19.046Z - info: Socket to device samsung-SM-G900F disconnected: transport close


 
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
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/79751015007586f_Check_811_failures_in_CI_do_not_merge__czyzm/thali01_motorola-Nexus 6.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/79751015007586f_Check_811_failures_in_CI_do_not_merge__czyzm/thali01_samsung-SM-G900F.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  LGD855a6933058 Test has  SUCCEEDED
Device test finished on LGD855a6933058 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/79751015007586f_Check_811_failures_in_CI_do_not_merge__czyzm/thali02_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/79751015007586f_Check_811_failures_in_CI_do_not_merge__czyzm/thali02_LGE-LG-D855.md)





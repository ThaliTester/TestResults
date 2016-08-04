#### Test 797510150318bb5 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":6}}
2016-08-04T10:49:45.844Z - info: Require 3 ios devices

2016-08-04T10:49:45.863Z - info: Require 3 android devices

2016-08-04T10:49:45.922Z - info: listening on *:3000

2016-08-04T10:49:48.743Z - debug: Device presented: LGE-LG-D722 (6c9181e1-0f2e-4157-8421-c778ebaba580) - android 5.0.2

2016-08-04T10:49:48.753Z - debug: Device presented: samsung-SM-N9005 (d9063a4f-63b9-40d1-b61a-dea23e3bf730) - android 5.0

2016-08-04T10:49:49.602Z - debug: Device presented: LGE-LG-D722 (6c9181e1-0f2e-4157-8421-c778ebaba580) - android 5.0.2

2016-08-04T10:49:49.603Z - info: Updating existing device: LGE-LG-D722 (6c9181e1-0f2e-4157-8421-c778ebaba580)

2016-08-04T10:49:49.719Z - debug: Device presented: samsung-SM-N9005 (d9063a4f-63b9-40d1-b61a-dea23e3bf730) - android 5.0

2016-08-04T10:49:49.720Z - info: Updating existing device: samsung-SM-N9005 (d9063a4f-63b9-40d1-b61a-dea23e3bf730)

2016-08-04T10:49:50.733Z - debug: Device presented: LGE-LG-D855 (8aa7daef-0da2-4e0b-bfb2-a7c37302dedf) - android 5.0

2016-08-04T10:49:51.740Z - debug: Device presented: LGE-LG-D855 (8aa7daef-0da2-4e0b-bfb2-a7c37302dedf) - android 5.0

2016-08-04T10:49:51.741Z - info: Updating existing device: LGE-LG-D855 (8aa7daef-0da2-4e0b-bfb2-a7c37302dedf)

2016-08-04T10:50:25.443Z - debug: Device presented: samsung-SM-N910C (2bdb2af9-d0f2-4574-910d-bac56ba6aea3) - android 6.0.1

2016-08-04T10:50:36.584Z - debug: Device presented: samsung-SM-G900F (31419fc4-4fc0-4744-a260-a87bbf88750a) - android 6.0.1

2016-08-04T10:51:03.910Z - debug: Device presented: motorola-Nexus 6 (cd19b11b-bddf-4739-9e99-117588011af5) - android 6.0.1

2016-08-04T10:51:03.911Z - info: All 6 android devices are present

2016-08-04T10:51:03.913Z - info: Disqualifying device with unsupported hardware: LGE-LG-D722

2016-08-04T10:51:03.920Z - info: Disqualifying device with unsupported hardware: samsung-SM-N9005

2016-08-04T10:51:03.923Z - info: Disqualifying device with unsupported hardware: LGE-LG-D855

2016-08-04T10:51:03.930Z - info: Starting unit test run on 3 android devices

2016-08-04T10:51:04.750Z - info: Socket to device LGE-LG-D855 disconnected: transport close

2016-08-04T10:51:04.860Z - info: Socket to device samsung-SM-N9005 disconnected: transport close

2016-08-04T10:51:05.284Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-04T10:51:05.427Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-08-04T10:51:07.553Z - info: Running on android test: 2. emits incomingConnectionState

2016-08-04T10:51:10.918Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-08-04T10:51:12.705Z - info: Running on android test: 4. native server connections all up

2016-08-04T10:51:14.426Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-08-04T10:51:15.801Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-08-04T10:51:16.131Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-08-04T10:51:16.501Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-08-04T10:51:16.788Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-08-04T10:51:18.187Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-08-04T10:51:20.294Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-08-04T10:51:22.078Z - info: Running on android test: 12. #_doImmediateSeqUpdate - server is not there

2016-08-04T10:51:24.881Z - info: Running on android test: 13. #_doImmediateSeqUpdate - server accepts & closes connection

2016-08-04T10:51:26.781Z - info: Running on android test: 14. #_doImmediateSeqUpdate - server always returns 500

2016-08-04T10:51:27.944Z - info: Socket to device motorola-Nexus 6 disconnected: transport close

2016-08-04T10:51:28.277Z - info: Socket to device samsung-SM-N910C disconnected: transport close

2016-08-04T10:51:28.661Z - info: Socket to device samsung-SM-G900F disconnected: transport close


 
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
####Node name: thali05
Console output:
```
STOP log received from  1d6a772d Test has  SUCCEEDED
STOP log received from  LGD855a6933058 Test has  SUCCEEDED
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD855a6933058 
Device test finished on 1d6a772d 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/797510150318bb5_Check_811_failures_in_CI_do_not_merge__czyzm/thali05_samsung-SM-N9005.md)

[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/797510150318bb5_Check_811_failures_in_CI_do_not_merge__czyzm/thali05_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/797510150318bb5_Check_811_failures_in_CI_do_not_merge__czyzm/thali05_LGE-LG-D855.md)

####Node name: thali08
Console output:
```


 Marshmallow device. Granting ACCESS_COARSE_LOCATION permission


 Marshmallow device. Granting ACCESS_COARSE_LOCATION permission


 Marshmallow device. Granting ACCESS_COARSE_LOCATION permission
STOP log received from  ZX1G429CRK Test has  FAILED
STOP log received from  41006f95c8139173 Test has  FAILED
STOP log received from  0be0c6c6 Test has  FAILED
Device test finished on ZX1G429CRK 
Device test finished on 41006f95c8139173 
Device test finished on 0be0c6c6 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/797510150318bb5_Check_811_failures_in_CI_do_not_merge__czyzm/thali08_motorola-Nexus 6.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/797510150318bb5_Check_811_failures_in_CI_do_not_merge__czyzm/thali08_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/797510150318bb5_Check_811_failures_in_CI_do_not_merge__czyzm/thali08_samsung-SM-G900F.md)





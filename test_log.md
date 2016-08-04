#### Test 798805949e36f59 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":6}}
2016-08-04T10:33:16.489Z - info: Require 3 ios devices

2016-08-04T10:33:16.508Z - info: Require 3 android devices

2016-08-04T10:33:16.568Z - info: listening on *:3000

2016-08-04T10:33:17.748Z - debug: Device presented: samsung-SM-N9005 (dfd01fe5-fbc2-44f6-ae72-4568dd09e6e9) - android 5.0

2016-08-04T10:33:18.557Z - debug: Device presented: LGE-LG-D855 (5058af12-8570-487c-8377-030e4d86183b) - android 5.0

2016-08-04T10:33:18.727Z - debug: Device presented: samsung-SM-N9005 (dfd01fe5-fbc2-44f6-ae72-4568dd09e6e9) - android 5.0

2016-08-04T10:33:18.728Z - info: Updating existing device: samsung-SM-N9005 (dfd01fe5-fbc2-44f6-ae72-4568dd09e6e9)

2016-08-04T10:33:19.555Z - debug: Device presented: LGE-LG-D855 (5058af12-8570-487c-8377-030e4d86183b) - android 5.0

2016-08-04T10:33:19.556Z - info: Updating existing device: LGE-LG-D855 (5058af12-8570-487c-8377-030e4d86183b)

2016-08-04T10:33:21.612Z - debug: Device presented: LGE-LG-D722 (a947d378-17ec-4d10-902d-191899de64f1) - android 5.0.2

2016-08-04T10:33:22.519Z - debug: Device presented: LGE-LG-D722 (a947d378-17ec-4d10-902d-191899de64f1) - android 5.0.2

2016-08-04T10:33:22.520Z - info: Updating existing device: LGE-LG-D722 (a947d378-17ec-4d10-902d-191899de64f1)

2016-08-04T10:33:57.035Z - debug: Device presented: samsung-SM-N910C (48a27edd-0806-473d-87b1-ff1339d692cb) - android 6.0.1

2016-08-04T10:34:07.432Z - debug: Device presented: samsung-SM-G900F (fa8d85a9-d439-443f-9e34-f58ba492b17b) - android 6.0.1

2016-08-04T10:34:32.429Z - debug: Device presented: motorola-Nexus 6 (67bff581-fdda-44e6-a36f-31b2241a8313) - android 6.0.1

2016-08-04T10:34:32.430Z - info: All 6 android devices are present

2016-08-04T10:34:32.432Z - info: Disqualifying device with unsupported hardware: samsung-SM-N9005

2016-08-04T10:34:32.446Z - info: Disqualifying device with unsupported hardware: LGE-LG-D855

2016-08-04T10:34:32.450Z - info: Disqualifying device with unsupported hardware: LGE-LG-D722

2016-08-04T10:34:32.459Z - info: Starting unit test run on 3 android devices

2016-08-04T10:34:33.343Z - info: Socket to device LGE-LG-D855 disconnected: transport close

2016-08-04T10:34:33.499Z - info: Socket to device samsung-SM-N9005 disconnected: transport close

2016-08-04T10:34:33.782Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-08-04T10:34:34.122Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-04T10:34:35.877Z - info: Running on android test: 2. emits incomingConnectionState

2016-08-04T10:34:37.943Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-08-04T10:34:39.829Z - info: Running on android test: 4. native server connections all up

2016-08-04T10:34:41.868Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-08-04T10:34:43.953Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-08-04T10:34:45.716Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-08-04T10:34:47.163Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-08-04T10:34:47.519Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-08-04T10:34:48.806Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-08-04T10:34:52.154Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-08-04T10:35:08.713Z - info: Running on android test: 12. #_doImmediateSeqUpdate - server is not there

2016-08-04T10:35:17.883Z - info: Running on android test: 13. #_doImmediateSeqUpdate - server accepts & closes connection

2016-08-04T10:35:33.347Z - info: Running on android test: 14. #_doImmediateSeqUpdate - server always returns 500

2016-08-04T10:35:53.824Z - info: Socket to device samsung-SM-G900F disconnected: transport close

2016-08-04T10:35:56.285Z - info: Socket to device motorola-Nexus 6 disconnected: transport close

2016-08-04T10:35:57.451Z - info: Socket to device samsung-SM-N910C disconnected: transport close


 
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
[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/798805949e36f59_Fixed_typos_and_cases_in_js_files_evabishchevich/thali05_samsung-SM-N9005.md)

[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/798805949e36f59_Fixed_typos_and_cases_in_js_files_evabishchevich/thali05_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/798805949e36f59_Fixed_typos_and_cases_in_js_files_evabishchevich/thali05_LGE-LG-D855.md)

####Node name: thali08
Console output:
```


 Marshmallow device. Granting ACCESS_COARSE_LOCATION permission


 Marshmallow device. Granting ACCESS_COARSE_LOCATION permission


 Marshmallow device. Granting ACCESS_COARSE_LOCATION permission
STOP log received from  0be0c6c6 Test has  FAILED
Device test finished on 0be0c6c6 
STOP log received from  ZX1G429CRK Test has  FAILED
STOP log received from  41006f95c8139173 Test has  FAILED
Device test finished on ZX1G429CRK 
Device test finished on 41006f95c8139173 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/798805949e36f59_Fixed_typos_and_cases_in_js_files_evabishchevich/thali08_motorola-Nexus 6.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/798805949e36f59_Fixed_typos_and_cases_in_js_files_evabishchevich/thali08_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/798805949e36f59_Fixed_typos_and_cases_in_js_files_evabishchevich/thali08_samsung-SM-G900F.md)





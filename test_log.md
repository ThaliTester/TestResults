#### Test 7968977567f3672 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":6}}
2016-08-04T13:06:43.843Z - info: Require 3 ios devices

2016-08-04T13:06:43.864Z - info: Require 3 android devices

2016-08-04T13:06:43.923Z - info: listening on *:3000

2016-08-04T13:06:45.411Z - debug: Device presented: samsung-SM-N9005 (f887d837-6ebe-4b7c-81aa-44028fe84933) - android 5.0

2016-08-04T13:06:46.371Z - debug: Device presented: samsung-SM-N9005 (f887d837-6ebe-4b7c-81aa-44028fe84933) - android 5.0

2016-08-04T13:06:46.373Z - info: Updating existing device: samsung-SM-N9005 (f887d837-6ebe-4b7c-81aa-44028fe84933)

2016-08-04T13:06:46.575Z - debug: Device presented: LGE-LG-D855 (6a520553-9c80-4161-96cb-a286b27c9c17) - android 5.0

2016-08-04T13:06:47.573Z - debug: Device presented: LGE-LG-D855 (6a520553-9c80-4161-96cb-a286b27c9c17) - android 5.0

2016-08-04T13:06:47.575Z - info: Updating existing device: LGE-LG-D855 (6a520553-9c80-4161-96cb-a286b27c9c17)

2016-08-04T13:06:48.472Z - debug: Device presented: LGE-LG-D722 (6facd5ca-0441-42ae-8176-483f5abc4614) - android 5.0.2

2016-08-04T13:06:49.345Z - debug: Device presented: LGE-LG-D722 (6facd5ca-0441-42ae-8176-483f5abc4614) - android 5.0.2

2016-08-04T13:06:49.346Z - info: Updating existing device: LGE-LG-D722 (6facd5ca-0441-42ae-8176-483f5abc4614)

2016-08-04T13:07:35.015Z - debug: Device presented: samsung-SM-N910C (5159bb1f-1a47-4306-aee9-591d74aa04e3) - android 6.0.1

2016-08-04T13:07:39.755Z - debug: Device presented: motorola-Nexus 6 (8ddead86-446d-45da-a923-886441e2b59e) - android 6.0.1

2016-08-04T13:07:49.933Z - debug: Device presented: samsung-SM-G900F (b4090dba-f863-4790-b368-e12988c68d0e) - android 6.0.1

2016-08-04T13:07:49.934Z - info: All 6 android devices are present

2016-08-04T13:07:49.936Z - info: Disqualifying device with unsupported hardware: samsung-SM-N9005

2016-08-04T13:07:49.943Z - info: Disqualifying device with unsupported hardware: LGE-LG-D855

2016-08-04T13:07:49.945Z - info: Disqualifying device with unsupported hardware: LGE-LG-D722

2016-08-04T13:07:49.952Z - info: Starting unit test run on 3 android devices

2016-08-04T13:07:50.875Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-08-04T13:07:50.960Z - info: Socket to device samsung-SM-N9005 disconnected: transport close

2016-08-04T13:07:50.982Z - info: Socket to device LGE-LG-D855 disconnected: transport close

2016-08-04T13:07:51.531Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-04T13:07:55.225Z - info: Running on android test: 2. emits incomingConnectionState

2016-08-04T13:08:02.629Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-08-04T13:08:27.694Z - info: Running on android test: 4. native server connections all up

2016-08-04T13:08:49.503Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-08-04T13:08:50.903Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-08-04T13:08:51.303Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-08-04T13:08:51.620Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-08-04T13:08:51.977Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-08-04T13:08:54.885Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-08-04T13:08:57.265Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-08-04T13:08:57.832Z - info: Running on android test: 12. #_doImmediateSeqUpdate - server is not there

2016-08-04T13:08:58.346Z - info: Running on android test: 13. #_doImmediateSeqUpdate - server accepts & closes connection

2016-08-04T13:08:58.663Z - info: Running on android test: 14. #_doImmediateSeqUpdate - server always returns 500

2016-08-04T13:08:59.710Z - info: Socket to device motorola-Nexus 6 disconnected: transport close

2016-08-04T13:08:59.928Z - info: Socket to device samsung-SM-N910C disconnected: transport close

2016-08-04T13:09:00.437Z - info: Socket to device samsung-SM-G900F disconnected: transport close


 
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
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  LGD855a6933058 Test has  SUCCEEDED
Device test finished on LGD855a6933058 
Device test finished on 1d6a772d 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/7968977567f3672_PR_for_CI_test_purposes__issue_777_mlesnic/thali05_samsung-SM-N9005.md)

[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/7968977567f3672_PR_for_CI_test_purposes__issue_777_mlesnic/thali05_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/7968977567f3672_PR_for_CI_test_purposes__issue_777_mlesnic/thali05_LGE-LG-D855.md)

####Node name: thali08
Console output:
```


 Marshmallow device. Granting ACCESS_COARSE_LOCATION permission


 Marshmallow device. Granting ACCESS_COARSE_LOCATION permission


 Marshmallow device. Granting ACCESS_COARSE_LOCATION permission
STOP log received from  41006f95c8139173 Test has  FAILED
STOP log received from  ZX1G429CRK Test has  FAILED
STOP log received from  0be0c6c6 Test has  FAILED
Device test finished on ZX1G429CRK 
Device test finished on 41006f95c8139173 
Device test finished on 0be0c6c6 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/7968977567f3672_PR_for_CI_test_purposes__issue_777_mlesnic/thali08_motorola-Nexus 6.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/7968977567f3672_PR_for_CI_test_purposes__issue_777_mlesnic/thali08_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/7968977567f3672_PR_for_CI_test_purposes__issue_777_mlesnic/thali08_samsung-SM-G900F.md)





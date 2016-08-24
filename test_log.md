#### Test 81738796795e45d Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":8}}
2016-08-24T19:37:59.303Z - info: Require 3 ios devices

2016-08-24T19:37:59.329Z - info: Require 3 android devices

2016-08-24T19:37:59.387Z - info: listening on *:3000

2016-08-24T19:38:00.301Z - debug: Device presented: samsung-SM-A500FU (bf11cc63-7341-4925-b78f-b6cd889ccbd4) - android 5.0.2

2016-08-24T19:38:00.461Z - debug: Device presented: samsung-SM-A300FU (d752cccf-cfb8-44a2-bfc2-ea53608fe8be) - android 5.0.2

2016-08-24T19:38:01.260Z - debug: Device presented: samsung-SM-A500FU (bf11cc63-7341-4925-b78f-b6cd889ccbd4) - android 5.0.2

2016-08-24T19:38:01.262Z - info: Updating existing device: samsung-SM-A500FU (bf11cc63-7341-4925-b78f-b6cd889ccbd4)

2016-08-24T19:38:01.415Z - debug: Device presented: samsung-SM-A300FU (d752cccf-cfb8-44a2-bfc2-ea53608fe8be) - android 5.0.2

2016-08-24T19:38:01.417Z - info: Updating existing device: samsung-SM-A300FU (d752cccf-cfb8-44a2-bfc2-ea53608fe8be)

2016-08-24T19:38:02.522Z - debug: Device presented: HTC-HTC One M9 (1ebb4af3-b2fa-441a-88c5-8a837a67b5b2) - android 5.1

2016-08-24T19:38:02.923Z - debug: Device presented: samsung-SM-A300FU (05a1731f-8696-4313-a436-3e7ce7351cdd) - android 5.0.2

2016-08-24T19:38:03.316Z - debug: Device presented: samsung-SM-G900F (e4e8712c-b502-487e-9028-c28a163645e7) - android 6.0.1

2016-08-24T19:38:03.389Z - debug: Device presented: motorola-Nexus 6 (9295241b-334e-453b-b01e-259108c0b013) - android 6.0.1

2016-08-24T19:38:03.541Z - debug: Device presented: HTC-HTC One M9 (1ebb4af3-b2fa-441a-88c5-8a837a67b5b2) - android 5.1

2016-08-24T19:38:03.542Z - info: Updating existing device: HTC-HTC One M9 (1ebb4af3-b2fa-441a-88c5-8a837a67b5b2)

2016-08-24T19:38:03.942Z - debug: Device presented: samsung-SM-A300FU (05a1731f-8696-4313-a436-3e7ce7351cdd) - android 5.0.2

2016-08-24T19:38:03.943Z - info: Updating existing device: samsung-SM-A300FU (05a1731f-8696-4313-a436-3e7ce7351cdd)

2016-08-24T19:38:04.333Z - debug: Device presented: samsung-SM-G900F (e4e8712c-b502-487e-9028-c28a163645e7) - android 6.0.1

2016-08-24T19:38:04.334Z - info: Updating existing device: samsung-SM-G900F (e4e8712c-b502-487e-9028-c28a163645e7)

2016-08-24T19:38:04.382Z - debug: Device presented: motorola-Nexus 6 (9295241b-334e-453b-b01e-259108c0b013) - android 6.0.1

2016-08-24T19:38:04.383Z - info: Updating existing device: motorola-Nexus 6 (9295241b-334e-453b-b01e-259108c0b013)

2016-08-24T19:40:01.714Z - debug: Device presented: LGE-LG-D855 (95534ddc-186f-40e2-b633-44134ef0b0b6) - android 5.0

2016-08-24T19:40:16.134Z - debug: Device presented: LGE-LG-D722 (416e5f5c-7d17-4881-b4c3-bc094813f34d) - android 5.0.2

2016-08-24T19:40:16.135Z - info: All 8 android devices are present

2016-08-24T19:40:16.138Z - info: Disqualifying device with unsupported hardware: LGE-LG-D855

2016-08-24T19:40:16.144Z - info: Disqualifying device with unsupported hardware: LGE-LG-D722

2016-08-24T19:40:16.152Z - info: Starting unit test run on 6 android devices

2016-08-24T19:40:17.074Z - info: Socket to device LGE-LG-D855 disconnected: transport close

2016-08-24T19:40:17.151Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-24T19:40:17.494Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-08-24T19:40:19.152Z - info: Running on android test: 2. emits incomingConnectionState

2016-08-24T19:40:21.592Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-08-24T19:40:22.530Z - info: Running on android test: 4. native server connections all up

2016-08-24T19:40:24.345Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-08-24T19:40:26.136Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-08-24T19:40:28.403Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-08-24T19:40:29.100Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-08-24T19:40:29.739Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-08-24T19:40:31.666Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-08-24T19:40:31.990Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-08-24T19:40:32.479Z - info: Running on android test: 12. #_doImmediateSeqUpdate - server is not there

2016-08-24T19:40:33.082Z - info: Running on android test: 13. #_doImmediateSeqUpdate - server accepts & closes connection

2016-08-24T19:40:33.687Z - info: Running on android test: 14. #_doImmediateSeqUpdate - server always returns 500

2016-08-24T19:40:35.498Z - info: Running on android test: 15. #_doImmediateSeqUpdate - create new seq doc

2016-08-24T19:40:40.025Z - info: Running on android test: 16. #_doImmediateSeqUpdate - doc exists, need to get rev and update

2016-08-24T19:40:46.544Z - info: Running on android test: 17. #_doImmediateSeqUpdate - update seq three times

2016-08-24T19:40:49.656Z - info: Running on android test: 18. #_doImmediateSeqUpdate - rev got changed under us

2016-08-24T19:40:52.039Z - info: Running on android test: 19. #_doImmediateSeqUpdate - fail if stop is called

2016-08-24T19:40:53.660Z - info: Running on android test: 20. #_doImmediateSeqUpdate - stop after get but before put fails right

2016-08-24T19:40:55.388Z - info: Running on android test: 21. #update - fail if stop is called

2016-08-24T19:40:55.736Z - info: Running on android test: 22. #update - set seq for first time

2016-08-24T19:40:57.625Z - info: Running on android test: 23. #update - Fail on bad seq value

2016-08-24T19:40:58.950Z - info: Running on android test: 24. #update - do we cancel timer properly on an immediate?

2016-08-24T19:41:00.960Z - info: Running on android test: 25. #update - do we wait for blocked update

2016-08-24T19:41:02.868Z - info: Socket to device samsung-SM-A500FU disconnected: transport close

2016-08-24T19:41:03.095Z - info: Socket to device samsung-SM-A300FU disconnected: transport close

2016-08-24T19:41:03.120Z - info: Socket to device samsung-SM-A300FU disconnected: transport close

2016-08-24T19:58:14.407Z - info: Socket to device HTC-HTC One M9 disconnected: transport close

2016-08-24T19:58:22.870Z - info: Socket to device motorola-Nexus 6 disconnected: transport close

2016-08-24T19:58:25.362Z - info: Socket to device samsung-SM-G900F disconnected: transport close


 
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
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1G429CRK 
Error! Unexpected exit on device 0be0c6c6 app:com.test.thalitest code:null 
child process exited with code null on device 0be0c6c6 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/81738796795e45d_Updating_to_handle_iOS_yaronyg/thali01_motorola-Nexus 6.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/81738796795e45d_Updating_to_handle_iOS_yaronyg/thali01_samsung-SM-G900F.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  LGD855a6933058 Test has  SUCCEEDED
Device test finished on LGD855a6933058 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/81738796795e45d_Updating_to_handle_iOS_yaronyg/thali02_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/81738796795e45d_Updating_to_handle_iOS_yaronyg/thali02_LGE-LG-D855.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:null 
child process exited with code null on device f56ad48d 
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:null 
child process exited with code null on device 7970f88c 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/81738796795e45d_Updating_to_handle_iOS_yaronyg/thali03_samsung-SM-A500FU.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/81738796795e45d_Updating_to_handle_iOS_yaronyg/thali03_samsung-SM-A300FU.md)

####Node name: thali04
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:null 
child process exited with code null on device 4325e43f 
Error! Unexpected exit on device HT54GYJ03048 app:com.test.thalitest code:null 
child process exited with code null on device HT54GYJ03048 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/81738796795e45d_Updating_to_handle_iOS_yaronyg/thali04_samsung-SM-A300FU.md)

[HTC-HTC One M9](https://github.com/ThaliTester/TestResults/blob/81738796795e45d_Updating_to_handle_iOS_yaronyg/thali04_HTC-HTC One M9.md)





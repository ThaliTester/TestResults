#### Test 797510157fdac7f Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":4}}
2016-08-12T07:51:21.587Z - info: Require 0 ios devices

2016-08-12T07:51:21.607Z - info: Require 4 android devices

2016-08-12T07:51:21.665Z - info: listening on *:3000

2016-08-12T07:51:23.095Z - debug: Device presented: samsung-SM-N910C (979a9e90-3c56-45f0-856d-2212dee13628) - android 6.0.1

2016-08-12T07:51:24.066Z - debug: Device presented: samsung-SM-N910C (979a9e90-3c56-45f0-856d-2212dee13628) - android 6.0.1

2016-08-12T07:51:24.070Z - info: Updating existing device: samsung-SM-N910C (979a9e90-3c56-45f0-856d-2212dee13628)

2016-08-12T07:51:25.250Z - debug: Device presented: samsung-SM-G900F (5048ed5a-c802-4814-b8d4-80c3cd613771) - android 6.0.1

2016-08-12T07:51:26.271Z - debug: Device presented: samsung-SM-G900F (5048ed5a-c802-4814-b8d4-80c3cd613771) - android 6.0.1

2016-08-12T07:51:26.272Z - info: Updating existing device: samsung-SM-G900F (5048ed5a-c802-4814-b8d4-80c3cd613771)

2016-08-12T07:51:43.893Z - debug: Device presented: LGE-LG-D855 (a24b03aa-fa0c-42ee-b1af-172a1c2bc0ff) - android 5.0

2016-08-12T07:51:55.698Z - debug: Device presented: LGE-LG-D722 (b977964d-c0f9-4efa-9226-8d6cdc38c457) - android 5.0.2

2016-08-12T07:51:55.699Z - info: All 4 android devices are present

2016-08-12T07:51:55.702Z - info: Disqualifying device with unsupported hardware: LGE-LG-D855

2016-08-12T07:51:55.709Z - info: Disqualifying device with unsupported hardware: LGE-LG-D722

2016-08-12T07:51:55.716Z - info: Starting unit test run on 2 android devices

2016-08-12T07:51:56.576Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-08-12T07:51:56.657Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-12T07:51:56.873Z - info: Socket to device LGE-LG-D855 disconnected: transport close

2016-08-12T07:51:56.917Z - info: Running on android test: 2. emits incomingConnectionState

2016-08-12T07:51:57.146Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-08-12T07:51:57.411Z - info: Running on android test: 4. native server connections all up

2016-08-12T07:51:57.680Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-08-12T07:51:57.942Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-08-12T07:51:58.188Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-08-12T07:51:58.435Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-08-12T07:51:58.653Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-08-12T07:52:00.405Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-08-12T07:52:00.684Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-08-12T07:52:00.924Z - info: Running on android test: 12. #_doImmediateSeqUpdate - server is not there

2016-08-12T07:52:01.233Z - info: Running on android test: 13. #_doImmediateSeqUpdate - server accepts & closes connection

2016-08-12T07:52:01.494Z - info: Running on android test: 14. #_doImmediateSeqUpdate - server always returns 500

2016-08-12T07:52:01.859Z - info: Running on android test: 15. #_doImmediateSeqUpdate - create new seq doc

2016-08-12T07:52:04.102Z - info: Running on android test: 16. #_doImmediateSeqUpdate - doc exists, need to get rev and update

2016-08-12T07:52:04.878Z - info: Running on android test: 17. #_doImmediateSeqUpdate - update seq three times

2016-08-12T07:52:05.835Z - info: Running on android test: 18. #_doImmediateSeqUpdate - rev got changed under us

2016-08-12T07:52:06.615Z - info: Running on android test: 19. #_doImmediateSeqUpdate - fail if stop is called

2016-08-12T07:52:06.818Z - info: Running on android test: 20. #_doImmediateSeqUpdate - stop after get but before put fails right

2016-08-12T07:52:07.393Z - info: Running on android test: 21. #update - fail if stop is called

2016-08-12T07:52:07.719Z - info: Running on android test: 22. #update - set seq for first time

2016-08-12T07:52:08.620Z - info: Running on android test: 23. #update - Fail on bad seq value

2016-08-12T07:52:09.246Z - info: Running on android test: 24. #update - do we cancel timer properly on an immediate?

2016-08-12T07:52:10.020Z - info: Running on android test: 25. #update - do we wait for blocked update

2016-08-12T07:52:10.796Z - info: Running on android test: 26. #update - test that we wait long enough

2016-08-12T07:52:12.422Z - info: Running on android test: 27. #update - test that we pick up new sequences while we wait

2016-08-12T07:52:13.951Z - info: Running on android test: 28. Coordinated seq test

2016-08-12T07:52:18.178Z - info: Running on android test: 29. closeAll can close even when connections open

2016-08-12T07:52:18.495Z - info: Running on android test: 30. closeAll with promise

2016-08-12T07:52:18.846Z - info: Running on android test: 31. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-08-12T07:52:19.180Z - info: Running on android test: 32. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-08-12T07:52:19.540Z - info: Running on android test: 33. onPeerLost calls jxcore

2016-08-12T07:52:21.948Z - info: Running on android test: 34. onPeerDiscovered calls jxcore

2016-08-12T07:52:24.268Z - info: Running on android test: 35. enqueue and run in order

2016-08-12T07:52:24.706Z - info: Running on android test: 36. enqueueAtTop and run backwards

2016-08-12T07:52:24.960Z - info: Running on android test: 37. mix enqueue and enqueueAtTop

2016-08-12T07:52:25.304Z - info: Running on android test: 38. queues handled independently

2016-08-12T07:52:25.560Z - info: Running on android test: 39. basic

2016-08-12T07:52:25.740Z - info: Running on android test: 40. another

2016-08-12T07:52:25.902Z - info: Running on android test: 41. can pass data in setup

2016-08-12T07:52:26.095Z - info: Running on android test: 42. #startListeningForAdvertisements should fail if start not called

2016-08-12T07:52:26.277Z - info: Running on android test: 43. #startUpdateAdvertisingAndListening should fail if start not called

2016-08-12T07:52:26.504Z - info: Running on android test: 44. should be able to call #stopListeningForAdvertisements many times

2016-08-12T07:52:28.090Z - info: Socket to device samsung-SM-N910C disconnected: transport close

2016-08-12T07:54:25.688Z - debug: Too many emit retries to device: samsung-SM-N910C

2016-08-12T08:11:27.816Z - info: Socket to device samsung-SM-G900F disconnected: transport close


 
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
Error! Unexpected exit on device 41009dc6f26f910b app:com.test.thalitest code:0 
child process exited with code 0 on device 41009dc6f26f910b 
Error! Unexpected exit on device 0be0c6c6 app:com.test.thalitest code:null 
child process exited with code null on device 0be0c6c6 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/797510157fdac7f_Check_811_failures_in_CI_do_not_merge__czyzm/thali01_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/797510157fdac7f_Check_811_failures_in_CI_do_not_merge__czyzm/thali01_samsung-SM-G900F.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  LGD855a6933058 Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
Device test finished on LGD855a6933058 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/797510157fdac7f_Check_811_failures_in_CI_do_not_merge__czyzm/thali02_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/797510157fdac7f_Check_811_failures_in_CI_do_not_merge__czyzm/thali02_LGE-LG-D855.md)





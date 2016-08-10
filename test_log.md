#### Test 807613745de8823 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":4}}
2016-08-10T11:32:44.732Z - info: Require 3 ios devices

2016-08-10T11:32:44.752Z - info: Require 3 android devices

2016-08-10T11:32:44.810Z - info: listening on *:3000

2016-08-10T11:32:45.739Z - debug: Device presented: motorola-Nexus 6 (d285b573-6a39-4df8-9702-df528d02a94b) - android 6.0.1

2016-08-10T11:32:46.717Z - debug: Device presented: motorola-Nexus 6 (d285b573-6a39-4df8-9702-df528d02a94b) - android 6.0.1

2016-08-10T11:32:46.720Z - info: Updating existing device: motorola-Nexus 6 (d285b573-6a39-4df8-9702-df528d02a94b)

2016-08-10T11:32:46.929Z - debug: Device presented: samsung-SM-G900F (a145a2ff-be4e-480d-8725-168ac9f919ed) - android 6.0.1

2016-08-10T11:32:48.012Z - debug: Device presented: samsung-SM-G900F (a145a2ff-be4e-480d-8725-168ac9f919ed) - android 6.0.1

2016-08-10T11:32:48.013Z - info: Updating existing device: samsung-SM-G900F (a145a2ff-be4e-480d-8725-168ac9f919ed)

2016-08-10T11:34:24.785Z - debug: Device presented: LGE-LG-D855 (49eb3212-c4ed-4bf2-8c29-e78739c8a863) - android 5.0

2016-08-10T11:34:39.013Z - debug: Device presented: LGE-LG-D722 (e4f2dd62-f3ac-43aa-989f-48af3aa6732e) - android 5.0.2

2016-08-10T11:34:39.014Z - info: All 4 android devices are present

2016-08-10T11:34:39.016Z - info: Disqualifying device with unsupported hardware: LGE-LG-D855

2016-08-10T11:34:39.023Z - info: Disqualifying device with unsupported hardware: LGE-LG-D722

2016-08-10T11:34:39.030Z - info: Starting unit test run on 2 android devices

2016-08-10T11:34:40.070Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-10T11:34:40.229Z - info: Socket to device LGE-LG-D855 disconnected: transport close

2016-08-10T11:34:40.458Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-08-10T11:34:40.741Z - info: Running on android test: 2. emits incomingConnectionState

2016-08-10T11:34:40.987Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-08-10T11:34:41.334Z - info: Running on android test: 4. native server connections all up

2016-08-10T11:34:41.647Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-08-10T11:34:42.022Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-08-10T11:34:42.322Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-08-10T11:34:42.630Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-08-10T11:34:42.931Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-08-10T11:34:45.004Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-08-10T11:34:45.568Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-08-10T11:34:45.846Z - info: Running on android test: 12. #_doImmediateSeqUpdate - server is not there

2016-08-10T11:34:46.212Z - info: Running on android test: 13. #_doImmediateSeqUpdate - server accepts & closes connection

2016-08-10T11:34:46.462Z - info: Running on android test: 14. #_doImmediateSeqUpdate - server always returns 500

2016-08-10T11:34:46.825Z - info: Running on android test: 15. #_doImmediateSeqUpdate - create new seq doc

2016-08-10T11:34:48.972Z - info: Running on android test: 16. #_doImmediateSeqUpdate - doc exists, need to get rev and update

2016-08-10T11:34:49.727Z - info: Running on android test: 17. #_doImmediateSeqUpdate - update seq three times

2016-08-10T11:34:50.759Z - info: Running on android test: 18. #_doImmediateSeqUpdate - rev got changed under us

2016-08-10T11:34:51.670Z - info: Running on android test: 19. #_doImmediateSeqUpdate - fail if stop is called

2016-08-10T11:34:51.908Z - info: Running on android test: 20. #_doImmediateSeqUpdate - stop after get but before put fails right

2016-08-10T11:34:52.701Z - info: Running on android test: 21. #update - fail if stop is called

2016-08-10T11:34:53.096Z - info: Running on android test: 22. #update - set seq for first time

2016-08-10T11:34:53.743Z - info: Running on android test: 23. #update - Fail on bad seq value

2016-08-10T11:34:54.394Z - info: Running on android test: 24. #update - do we cancel timer properly on an immediate?

2016-08-10T11:34:55.177Z - info: Running on android test: 25. #update - do we wait for blocked update

2016-08-10T11:34:55.930Z - info: Running on android test: 26. #update - test that we wait long enough

2016-08-10T11:34:57.781Z - info: Running on android test: 27. #update - test that we pick up new sequences while we wait

2016-08-10T11:34:59.529Z - info: Running on android test: 28. Coordinated seq test

2016-08-10T11:40:00.018Z - warn: Failed on android test: 28. Coordinated seq test

2016-08-10T11:40:00.020Z - info: Running on android test: 29. closeAll can close even when connections open

2016-08-10T11:40:00.406Z - info: Running on android test: 30. closeAll with promise

2016-08-10T11:40:00.751Z - info: Running on android test: 31. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-08-10T11:40:01.086Z - info: Running on android test: 32. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-08-10T11:40:01.438Z - info: Running on android test: 33. onPeerLost calls jxcore

2016-08-10T11:40:03.793Z - info: Running on android test: 34. onPeerDiscovered calls jxcore

2016-08-10T11:40:06.103Z - info: Running on android test: 35. enqueue and run in order

2016-08-10T11:40:06.540Z - info: Running on android test: 36. enqueueAtTop and run backwards

2016-08-10T11:40:06.774Z - info: Running on android test: 37. mix enqueue and enqueueAtTop

2016-08-10T11:40:07.104Z - info: Running on android test: 38. queues handled independently

2016-08-10T11:40:07.315Z - info: Running on android test: 39. basic

2016-08-10T11:40:07.487Z - info: Running on android test: 40. another

2016-08-10T11:40:07.676Z - info: Running on android test: 41. can pass data in setup

2016-08-10T11:40:07.880Z - info: Running on android test: 42. #startListeningForAdvertisements should fail if start not called

2016-08-10T11:40:08.093Z - info: Running on android test: 43. #startUpdateAdvertisingAndListening should fail if start not called

2016-08-10T11:40:08.281Z - info: Running on android test: 44. should be able to call #stopListeningForAdvertisements many times

2016-08-10T11:40:08.539Z - info: Running on android test: 45. should be able to call #startListeningForAdvertisements many times

2016-08-10T11:40:10.180Z - info: Running on android test: 46. should be able to call #startUpdateAdvertisingAndListening many times

2016-08-10T11:40:11.565Z - info: Running on android test: 47. should be able to call #stopAdvertisingAndListening many times

2016-08-10T11:40:11.842Z - info: Running on android test: 48. #start should fail if called twice in a row

2016-08-10T11:40:12.087Z - info: Running on android test: 49. does not emit duplicate discoveryAdvertisingStateUpdate

2016-08-10T11:40:14.185Z - info: Running on android test: 50. does not send duplicate availability changes

2016-08-10T11:40:14.426Z - info: Running on android test: 51. can get the network status

2016-08-10T11:40:14.598Z - info: Running on android test: 52. wifi peer is marked unavailable if announcements stop

2016-08-10T11:40:16.899Z - info: Running on android test: 53. Can call start/stopListeningForAdvertisements

2016-08-10T11:40:18.580Z - info: Running on android test: 54. Calling startListeningForAdvertisements twice is NOT an error

2016-08-10T11:40:20.377Z - info: Running on android test: 55. Calling stopListeningForAdvertisements without calling start is NOT an error

2016-08-10T11:40:20.614Z - info: Running on android test: 56. Can call start/stopUpdateAdvertisingAndListening

2016-08-10T11:40:21.752Z - info: Running on android test: 57. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-08-10T11:40:23.228Z - info: Running on android test: 58. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error

2016-08-10T11:40:24.438Z - info: Running on android test: 59. cannot call connect when start listening for advertisements is not active

2016-08-10T11:40:24.750Z - info: Running on android test: 60. peerAvailabilityChange is called

2016-08-10T11:52:53.369Z - info: Socket to device motorola-Nexus 6 disconnected: transport close

2016-08-10T11:52:56.050Z - info: Socket to device samsung-SM-G900F disconnected: transport close


 
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
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/807613745de8823__777_Additional_native_unit_tests_mlesnic/thali01_motorola-Nexus 6.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/807613745de8823__777_Additional_native_unit_tests_mlesnic/thali01_samsung-SM-G900F.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  LGD855a6933058 Test has  SUCCEEDED
Device test finished on LGD855a6933058 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/807613745de8823__777_Additional_native_unit_tests_mlesnic/thali02_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/807613745de8823__777_Additional_native_unit_tests_mlesnic/thali02_LGE-LG-D855.md)





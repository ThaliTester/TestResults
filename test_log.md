#### Test 797510152cd5224 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":5}}
2016-08-05T07:54:26.980Z - info: Require 3 ios devices

2016-08-05T07:54:27.001Z - info: Require 3 android devices

2016-08-05T07:54:27.063Z - info: listening on *:3000

2016-08-05T07:54:31.421Z - debug: Device presented: motorola-Nexus 6 (0e16d1d2-3842-4c9a-8221-dcb680d14e95) - android 6.0.1

2016-08-05T07:54:32.050Z - debug: Device presented: samsung-SM-G900F (fb214a07-29c7-494d-b7a0-89d66ef4ee4f) - android 6.0.1

2016-08-05T07:54:32.392Z - debug: Device presented: motorola-Nexus 6 (0e16d1d2-3842-4c9a-8221-dcb680d14e95) - android 6.0.1

2016-08-05T07:54:32.394Z - info: Updating existing device: motorola-Nexus 6 (0e16d1d2-3842-4c9a-8221-dcb680d14e95)

2016-08-05T07:54:33.140Z - debug: Device presented: samsung-SM-G900F (fb214a07-29c7-494d-b7a0-89d66ef4ee4f) - android 6.0.1

2016-08-05T07:54:33.141Z - info: Updating existing device: samsung-SM-G900F (fb214a07-29c7-494d-b7a0-89d66ef4ee4f)

2016-08-05T07:55:05.453Z - debug: Device presented: samsung-SM-N9005 (02daa8b2-e628-45e2-b872-dbeab9b21944) - android 5.0

2016-08-05T07:55:06.487Z - debug: Device presented: LGE-LG-D855 (99980cef-d354-4451-9031-dab12e497f18) - android 5.0

2016-08-05T07:55:21.896Z - debug: Device presented: LGE-LG-D722 (9524379d-ef12-4121-be02-3f3ff2ddbcc6) - android 5.0.2

2016-08-05T07:55:21.897Z - info: All 5 android devices are present

2016-08-05T07:55:21.900Z - info: Disqualifying device with unsupported hardware: samsung-SM-N9005

2016-08-05T07:55:21.906Z - info: Disqualifying device with unsupported hardware: LGE-LG-D855

2016-08-05T07:55:21.909Z - info: Disqualifying device with unsupported hardware: LGE-LG-D722

2016-08-05T07:55:21.917Z - info: Starting unit test run on 2 android devices

2016-08-05T07:55:22.866Z - info: Socket to device LGE-LG-D855 disconnected: transport close

2016-08-05T07:55:22.885Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-08-05T07:55:22.968Z - info: Socket to device samsung-SM-N9005 disconnected: transport close

2016-08-05T07:55:22.979Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-05T07:55:23.091Z - info: Running on android test: 2. emits incomingConnectionState

2016-08-05T07:55:23.436Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-08-05T07:55:23.728Z - info: Running on android test: 4. native server connections all up

2016-08-05T07:55:24.071Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-08-05T07:55:24.350Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-08-05T07:55:24.686Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-08-05T07:55:24.994Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-08-05T07:55:25.280Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-08-05T07:55:27.254Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-08-05T07:55:27.730Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-08-05T07:55:28.053Z - info: Running on android test: 12. #_doImmediateSeqUpdate - server is not there

2016-08-05T07:55:28.437Z - info: Running on android test: 13. #_doImmediateSeqUpdate - server accepts & closes connection

2016-08-05T07:55:28.735Z - info: Running on android test: 14. #_doImmediateSeqUpdate - server always returns 500

2016-08-05T07:55:29.085Z - info: Running on android test: 15. #_doImmediateSeqUpdate - create new seq doc

2016-08-05T07:55:31.211Z - info: Running on android test: 16. #_doImmediateSeqUpdate - doc exists, need to get rev and update

2016-08-05T07:55:32.228Z - info: Running on android test: 17. #_doImmediateSeqUpdate - update seq three times

2016-08-05T07:55:34.822Z - info: Running on android test: 18. #_doImmediateSeqUpdate - rev got changed under us

2016-08-05T07:55:39.102Z - info: Running on android test: 19. #_doImmediateSeqUpdate - fail if stop is called

2016-08-05T07:55:43.692Z - info: Running on android test: 20. #_doImmediateSeqUpdate - stop after get but before put fails right

2016-08-05T07:55:47.382Z - info: Running on android test: 21. #update - fail if stop is called

2016-08-05T07:55:47.918Z - info: Running on android test: 22. #update - set seq for first time

2016-08-05T07:55:48.687Z - info: Running on android test: 23. #update - Fail on bad seq value

2016-08-05T07:55:49.324Z - info: Running on android test: 24. #update - do we cancel timer properly on an immediate?

2016-08-05T07:55:50.117Z - info: Running on android test: 25. #update - do we wait for blocked update

2016-08-05T07:55:50.838Z - info: Running on android test: 26. #update - test that we wait long enough

2016-08-05T07:55:52.792Z - info: Running on android test: 27. #update - test that we pick up new sequences while we wait

2016-08-05T07:55:54.516Z - info: Running on android test: 28. Coordinated seq test

2016-08-05T08:00:54.944Z - warn: Failed on android test: 28. Coordinated seq test

2016-08-05T08:00:54.945Z - info: Running on android test: 29. closeAll can close even when connections open

2016-08-05T08:00:55.276Z - info: Running on android test: 30. closeAll with promise

2016-08-05T08:00:55.596Z - info: Running on android test: 31. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-08-05T08:00:55.939Z - info: Running on android test: 32. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-08-05T08:00:56.234Z - info: Running on android test: 33. enqueue and run in order

2016-08-05T08:00:56.706Z - info: Running on android test: 34. enqueueAtTop and run backwards

2016-08-05T08:00:56.922Z - info: Running on android test: 35. mix enqueue and enqueueAtTop

2016-08-05T08:00:57.242Z - info: Running on android test: 36. queues handled independently

2016-08-05T08:00:57.602Z - info: Running on android test: 37. basic

2016-08-05T08:00:57.782Z - info: Running on android test: 38. another

2016-08-05T08:00:57.953Z - info: Running on android test: 39. can pass data in setup

2016-08-05T08:00:58.142Z - info: Running on android test: 40. #startListeningForAdvertisements should fail if start not called

2016-08-05T08:00:58.339Z - info: Running on android test: 41. #startUpdateAdvertisingAndListening should fail if start not called

2016-08-05T08:00:58.554Z - info: Running on android test: 42. should be able to call #stopListeningForAdvertisements many times

2016-08-05T08:00:58.861Z - info: Running on android test: 43. should be able to call #startListeningForAdvertisements many times

2016-08-05T08:01:00.491Z - info: Running on android test: 44. should be able to call #startUpdateAdvertisingAndListening many times

2016-08-05T08:01:10.006Z - info: Running on android test: 45. should be able to call #stopAdvertisingAndListening many times

2016-08-05T08:01:10.254Z - info: Running on android test: 46. #start should fail if called twice in a row

2016-08-05T08:01:10.474Z - info: Running on android test: 47. does not emit duplicate discoveryAdvertisingStateUpdate

2016-08-05T08:01:12.415Z - info: Running on android test: 48. does not send duplicate availability changes

2016-08-05T08:01:12.617Z - info: Running on android test: 49. can get the network status

2016-08-05T08:01:12.798Z - info: Running on android test: 50. wifi peer is marked unavailable if announcements stop

2016-08-05T08:01:15.061Z - info: Running on android test: 51. Can call start/stopListeningForAdvertisements

2016-08-05T08:01:16.669Z - info: Running on android test: 52. Calling startListeningForAdvertisements twice is NOT an error

2016-08-05T08:01:18.323Z - info: Running on android test: 53. Calling stopListeningForAdvertisements without calling start is NOT an error

2016-08-05T08:01:18.613Z - info: Running on android test: 54. Can call start/stopUpdateAdvertisingAndListening

2016-08-05T08:01:19.732Z - info: Running on android test: 55. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-08-05T08:01:21.506Z - info: Running on android test: 56. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error

2016-08-05T08:01:21.844Z - info: Running on android test: 57. cannot call connect when start listening for advertisements is not active

2016-08-05T08:01:22.041Z - info: Running on android test: 58. peerAvailabilityChange is called

2016-08-05T08:14:06.559Z - info: Socket to device motorola-Nexus 6 disconnected: transport close

2016-08-05T08:14:08.712Z - info: Socket to device samsung-SM-G900F disconnected: transport close


 
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
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  1d6a772d Test has  SUCCEEDED
STOP log received from  LGD855a6933058 Test has  SUCCEEDED
Device test finished on LGD855a6933058 
Device test finished on LGD7228ee9cf5b 
Device test finished on 1d6a772d 
Android task is completed. [SUCCESS]
```
[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/797510152cd5224_Check_811_failures_in_CI_do_not_merge__czyzm/thali05_samsung-SM-N9005.md)

[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/797510152cd5224_Check_811_failures_in_CI_do_not_merge__czyzm/thali05_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/797510152cd5224_Check_811_failures_in_CI_do_not_merge__czyzm/thali05_LGE-LG-D855.md)

####Node name: thali08
Console output:
```


 Marshmallow device. Granting ACCESS_COARSE_LOCATION permission


 Marshmallow device. Granting ACCESS_COARSE_LOCATION permission
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1G429CRK 
Error! Unexpected exit on device 0be0c6c6 app:com.test.thalitest code:null 
child process exited with code null on device 0be0c6c6 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/797510152cd5224_Check_811_failures_in_CI_do_not_merge__czyzm/thali08_motorola-Nexus 6.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/797510152cd5224_Check_811_failures_in_CI_do_not_merge__czyzm/thali08_samsung-SM-G900F.md)





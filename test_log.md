#### Test 79426650616b042 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":5}}
2016-08-05T13:17:09.856Z - info: Require 3 ios devices

2016-08-05T13:17:09.877Z - info: Require 3 android devices

2016-08-05T13:17:09.941Z - info: listening on *:3000

2016-08-05T13:17:14.256Z - debug: Device presented: motorola-Nexus 6 (fbd4112a-9080-4fc2-8a75-5cbdc3660083) - android 6.0.1

2016-08-05T13:17:15.074Z - debug: Device presented: samsung-SM-G900F (661f4532-35c5-4e80-9105-1dd6fc91277b) - android 6.0.1

2016-08-05T13:17:15.215Z - debug: Device presented: motorola-Nexus 6 (fbd4112a-9080-4fc2-8a75-5cbdc3660083) - android 6.0.1

2016-08-05T13:17:15.218Z - info: Updating existing device: motorola-Nexus 6 (fbd4112a-9080-4fc2-8a75-5cbdc3660083)

2016-08-05T13:17:16.097Z - debug: Device presented: samsung-SM-G900F (661f4532-35c5-4e80-9105-1dd6fc91277b) - android 6.0.1

2016-08-05T13:17:16.100Z - info: Updating existing device: samsung-SM-G900F (661f4532-35c5-4e80-9105-1dd6fc91277b)

2016-08-05T13:17:53.937Z - debug: Device presented: samsung-SM-N9005 (12df7f67-5ca1-4365-b03a-aa23812bb711) - android 5.0

2016-08-05T13:17:56.364Z - debug: Device presented: LGE-LG-D855 (d0713e07-eb6a-4d54-ad28-d5e3e984b8b8) - android 5.0

2016-08-05T13:18:10.666Z - debug: Device presented: LGE-LG-D722 (257972c9-2fc2-4ddb-ac27-7dd75866d75d) - android 5.0.2

2016-08-05T13:18:10.667Z - info: All 5 android devices are present

2016-08-05T13:18:10.669Z - info: Disqualifying device with unsupported hardware: samsung-SM-N9005

2016-08-05T13:18:10.676Z - info: Disqualifying device with unsupported hardware: LGE-LG-D855

2016-08-05T13:18:10.678Z - info: Disqualifying device with unsupported hardware: LGE-LG-D722

2016-08-05T13:18:10.685Z - info: Starting unit test run on 2 android devices

2016-08-05T13:18:11.480Z - info: Socket to device LGE-LG-D855 disconnected: transport close

2016-08-05T13:18:11.727Z - info: Socket to device samsung-SM-N9005 disconnected: transport close

2016-08-05T13:18:11.739Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-08-05T13:18:11.798Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-05T13:18:11.949Z - info: Running on android test: 2. emits incomingConnectionState

2016-08-05T13:18:12.246Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-08-05T13:18:12.547Z - info: Running on android test: 4. native server connections all up

2016-08-05T13:18:12.889Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-08-05T13:18:13.199Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-08-05T13:18:13.494Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-08-05T13:18:13.776Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-08-05T13:18:14.079Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-08-05T13:18:14.980Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-08-05T13:18:15.189Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-08-05T13:18:15.383Z - info: Running on android test: 12. #_doImmediateSeqUpdate - server is not there

2016-08-05T13:18:15.631Z - info: Running on android test: 13. #_doImmediateSeqUpdate - server accepts & closes connection

2016-08-05T13:18:15.781Z - info: Running on android test: 14. #_doImmediateSeqUpdate - server always returns 500

2016-08-05T13:18:16.031Z - info: Running on android test: 15. #_doImmediateSeqUpdate - create new seq doc

2016-08-05T13:18:18.202Z - info: Running on android test: 16. #_doImmediateSeqUpdate - doc exists, need to get rev and update

2016-08-05T13:18:19.054Z - info: Running on android test: 17. #_doImmediateSeqUpdate - update seq three times

2016-08-05T13:18:20.141Z - info: Running on android test: 18. #_doImmediateSeqUpdate - rev got changed under us

2016-08-05T13:18:21.018Z - info: Running on android test: 19. #_doImmediateSeqUpdate - fail if stop is called

2016-08-05T13:18:21.311Z - info: Running on android test: 20. #_doImmediateSeqUpdate - stop after get but before put fails right

2016-08-05T13:18:21.904Z - info: Running on android test: 21. #update - fail if stop is called

2016-08-05T13:18:22.177Z - info: Running on android test: 22. #update - set seq for first time

2016-08-05T13:18:22.843Z - info: Running on android test: 23. #update - Fail on bad seq value

2016-08-05T13:18:23.439Z - info: Running on android test: 24. #update - do we cancel timer properly on an immediate?

2016-08-05T13:18:24.245Z - info: Running on android test: 25. #update - do we wait for blocked update

2016-08-05T13:18:25.003Z - info: Running on android test: 26. #update - test that we wait long enough

2016-08-05T13:18:26.671Z - info: Running on android test: 27. #update - test that we pick up new sequences while we wait

2016-08-05T13:18:28.207Z - info: Running on android test: 28. Coordinated seq test

2016-08-05T13:23:29.119Z - warn: Failed on android test: 28. Coordinated seq test

2016-08-05T13:23:29.121Z - info: Running on android test: 29. closeAll can close even when connections open

2016-08-05T13:23:29.557Z - info: Running on android test: 30. closeAll with promise

2016-08-05T13:23:29.915Z - info: Running on android test: 31. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-08-05T13:23:30.213Z - info: Running on android test: 32. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-08-05T13:23:30.518Z - info: Running on android test: 33. enqueue and run in order

2016-08-05T13:23:30.952Z - info: Running on android test: 34. enqueueAtTop and run backwards

2016-08-05T13:23:31.157Z - info: Running on android test: 35. mix enqueue and enqueueAtTop

2016-08-05T13:23:31.463Z - info: Running on android test: 36. queues handled independently

2016-08-05T13:23:31.702Z - info: Running on android test: 37. basic

2016-08-05T13:23:31.895Z - info: Running on android test: 38. another

2016-08-05T13:23:32.098Z - info: Running on android test: 39. can pass data in setup

2016-08-05T13:23:32.288Z - info: Running on android test: 40. #startListeningForAdvertisements should fail if start not called

2016-08-05T13:23:32.466Z - info: Running on android test: 41. #startUpdateAdvertisingAndListening should fail if start not called

2016-08-05T13:23:32.663Z - info: Running on android test: 42. should be able to call #stopListeningForAdvertisements many times

2016-08-05T13:23:32.897Z - info: Running on android test: 43. should be able to call #startListeningForAdvertisements many times

2016-08-05T13:23:34.512Z - info: Running on android test: 44. should be able to call #startUpdateAdvertisingAndListening many times

2016-08-05T13:23:36.035Z - info: Running on android test: 45. should be able to call #stopAdvertisingAndListening many times

2016-08-05T13:23:38.369Z - info: Running on android test: 46. #start should fail if called twice in a row

2016-08-05T13:23:38.715Z - info: Running on android test: 47. does not emit duplicate discoveryAdvertisingStateUpdate

2016-08-05T13:23:40.668Z - info: Running on android test: 48. does not send duplicate availability changes

2016-08-05T13:23:40.829Z - info: Running on android test: 49. can get the network status

2016-08-05T13:23:41.009Z - info: Running on android test: 50. wifi peer is marked unavailable if announcements stop

2016-08-05T13:23:43.295Z - info: Running on android test: 51. Can call start/stopListeningForAdvertisements

2016-08-05T13:23:44.978Z - info: Running on android test: 52. Calling startListeningForAdvertisements twice is NOT an error

2016-08-05T13:23:46.725Z - info: Running on android test: 53. Calling stopListeningForAdvertisements without calling start is NOT an error

2016-08-05T13:23:47.014Z - info: Running on android test: 54. Can call start/stopUpdateAdvertisingAndListening

2016-08-05T13:23:48.021Z - info: Running on android test: 55. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-08-05T13:23:49.242Z - info: Running on android test: 56. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error

2016-08-05T13:23:49.493Z - info: Running on android test: 57. cannot call connect when start listening for advertisements is not active

2016-08-05T13:23:49.712Z - info: Running on android test: 58. peerAvailabilityChange is called

2016-08-05T13:36:46.325Z - info: Socket to device motorola-Nexus 6 disconnected: transport close

2016-08-05T13:36:48.793Z - info: Socket to device samsung-SM-G900F disconnected: transport close


 
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
[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/79426650616b042_Almost_to_the_top_of_the_Thali_stack_yaronyg/thali05_samsung-SM-N9005.md)

[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/79426650616b042_Almost_to_the_top_of_the_Thali_stack_yaronyg/thali05_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/79426650616b042_Almost_to_the_top_of_the_Thali_stack_yaronyg/thali05_LGE-LG-D855.md)

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
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/79426650616b042_Almost_to_the_top_of_the_Thali_stack_yaronyg/thali08_motorola-Nexus 6.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/79426650616b042_Almost_to_the_top_of_the_Thali_stack_yaronyg/thali08_samsung-SM-G900F.md)





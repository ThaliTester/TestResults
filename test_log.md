#### Test 79751015d1afc27 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":5}}
2016-08-05T09:00:00.800Z - info: Require 3 ios devices

2016-08-05T09:00:00.828Z - info: Require 3 android devices

2016-08-05T09:00:00.886Z - info: listening on *:3000

2016-08-05T09:00:03.929Z - debug: Device presented: motorola-Nexus 6 (3f0af123-4683-4410-b315-23f815614116) - android 6.0.1

2016-08-05T09:00:04.882Z - debug: Device presented: motorola-Nexus 6 (3f0af123-4683-4410-b315-23f815614116) - android 6.0.1

2016-08-05T09:00:04.884Z - info: Updating existing device: motorola-Nexus 6 (3f0af123-4683-4410-b315-23f815614116)

2016-08-05T09:00:05.396Z - debug: Device presented: samsung-SM-G900F (bd97659b-1ca7-4001-9a07-d0c25756f518) - android 6.0.1

2016-08-05T09:00:06.353Z - debug: Device presented: samsung-SM-G900F (bd97659b-1ca7-4001-9a07-d0c25756f518) - android 6.0.1

2016-08-05T09:00:06.354Z - info: Updating existing device: samsung-SM-G900F (bd97659b-1ca7-4001-9a07-d0c25756f518)

2016-08-05T09:00:44.117Z - debug: Device presented: samsung-SM-N9005 (4a199e4a-f372-4e0e-aa8b-775f0834c9aa) - android 5.0

2016-08-05T09:00:48.823Z - debug: Device presented: LGE-LG-D855 (7138e130-88b0-44af-a5e5-b17e8176db37) - android 5.0

2016-08-05T09:01:02.120Z - debug: Device presented: LGE-LG-D722 (9daf2f50-eef4-4b5b-b7c3-45b1ab26f63a) - android 5.0.2

2016-08-05T09:01:02.122Z - info: All 5 android devices are present

2016-08-05T09:01:02.123Z - info: Disqualifying device with unsupported hardware: samsung-SM-N9005

2016-08-05T09:01:02.130Z - info: Disqualifying device with unsupported hardware: LGE-LG-D855

2016-08-05T09:01:02.133Z - info: Disqualifying device with unsupported hardware: LGE-LG-D722

2016-08-05T09:01:02.139Z - info: Starting unit test run on 2 android devices

2016-08-05T09:01:03.169Z - info: Socket to device samsung-SM-N9005 disconnected: transport close

2016-08-05T09:01:03.266Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-08-05T09:01:03.297Z - info: Socket to device LGE-LG-D855 disconnected: transport close

2016-08-05T09:01:03.349Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-05T09:01:03.502Z - info: Running on android test: 2. emits incomingConnectionState

2016-08-05T09:01:03.764Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-08-05T09:01:03.986Z - info: Running on android test: 4. native server connections all up

2016-08-05T09:01:04.250Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-08-05T09:01:04.536Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-08-05T09:01:04.767Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-08-05T09:01:04.960Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-08-05T09:01:05.258Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-08-05T09:01:07.403Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-08-05T09:01:07.847Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-08-05T09:01:08.167Z - info: Running on android test: 12. #_doImmediateSeqUpdate - server is not there

2016-08-05T09:01:08.517Z - info: Running on android test: 13. #_doImmediateSeqUpdate - server accepts & closes connection

2016-08-05T09:01:08.744Z - info: Running on android test: 14. #_doImmediateSeqUpdate - server always returns 500

2016-08-05T09:01:09.080Z - info: Running on android test: 15. #_doImmediateSeqUpdate - create new seq doc

2016-08-05T09:01:11.183Z - info: Running on android test: 16. #_doImmediateSeqUpdate - doc exists, need to get rev and update

2016-08-05T09:01:11.943Z - info: Running on android test: 17. #_doImmediateSeqUpdate - update seq three times

2016-08-05T09:01:12.893Z - info: Running on android test: 18. #_doImmediateSeqUpdate - rev got changed under us

2016-08-05T09:01:13.817Z - info: Running on android test: 19. #_doImmediateSeqUpdate - fail if stop is called

2016-08-05T09:01:14.075Z - info: Running on android test: 20. #_doImmediateSeqUpdate - stop after get but before put fails right

2016-08-05T09:01:14.682Z - info: Running on android test: 21. #update - fail if stop is called

2016-08-05T09:01:14.958Z - info: Running on android test: 22. #update - set seq for first time

2016-08-05T09:01:15.663Z - info: Running on android test: 23. #update - Fail on bad seq value

2016-08-05T09:01:16.227Z - info: Running on android test: 24. #update - do we cancel timer properly on an immediate?

2016-08-05T09:01:16.990Z - info: Running on android test: 25. #update - do we wait for blocked update

2016-08-05T09:01:17.657Z - info: Running on android test: 26. #update - test that we wait long enough

2016-08-05T09:01:19.431Z - info: Running on android test: 27. #update - test that we pick up new sequences while we wait

2016-08-05T09:01:20.890Z - info: Running on android test: 28. Coordinated seq test

2016-08-05T09:06:21.330Z - warn: Failed on android test: 28. Coordinated seq test

2016-08-05T09:06:21.332Z - info: Running on android test: 29. closeAll can close even when connections open

2016-08-05T09:06:21.680Z - info: Running on android test: 30. closeAll with promise

2016-08-05T09:06:22.056Z - info: Running on android test: 31. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-08-05T09:06:22.364Z - info: Running on android test: 32. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-08-05T09:06:22.681Z - info: Running on android test: 33. enqueue and run in order

2016-08-05T09:06:23.136Z - info: Running on android test: 34. enqueueAtTop and run backwards

2016-08-05T09:06:23.326Z - info: Running on android test: 35. mix enqueue and enqueueAtTop

2016-08-05T09:06:23.640Z - info: Running on android test: 36. queues handled independently

2016-08-05T09:06:23.865Z - info: Running on android test: 37. basic

2016-08-05T09:06:24.058Z - info: Running on android test: 38. another

2016-08-05T09:06:24.257Z - info: Running on android test: 39. can pass data in setup

2016-08-05T09:06:24.452Z - info: Running on android test: 40. #startListeningForAdvertisements should fail if start not called

2016-08-05T09:06:24.645Z - info: Running on android test: 41. #startUpdateAdvertisingAndListening should fail if start not called

2016-08-05T09:06:24.922Z - info: Running on android test: 42. should be able to call #stopListeningForAdvertisements many times

2016-08-05T09:06:25.148Z - info: Running on android test: 43. should be able to call #startListeningForAdvertisements many times

2016-08-05T09:06:26.840Z - info: Running on android test: 44. should be able to call #startUpdateAdvertisingAndListening many times

2016-08-05T09:06:28.202Z - info: Running on android test: 45. should be able to call #stopAdvertisingAndListening many times

2016-08-05T09:06:28.461Z - info: Running on android test: 46. #start should fail if called twice in a row

2016-08-05T09:06:28.683Z - info: Running on android test: 47. does not emit duplicate discoveryAdvertisingStateUpdate

2016-08-05T09:06:30.578Z - info: Running on android test: 48. does not send duplicate availability changes

2016-08-05T09:06:30.779Z - info: Running on android test: 49. can get the network status

2016-08-05T09:06:31.014Z - info: Running on android test: 50. wifi peer is marked unavailable if announcements stop

2016-08-05T09:06:33.194Z - info: Running on android test: 51. Can call start/stopListeningForAdvertisements

2016-08-05T09:06:34.905Z - info: Running on android test: 52. Calling startListeningForAdvertisements twice is NOT an error

2016-08-05T09:06:36.538Z - info: Running on android test: 53. Calling stopListeningForAdvertisements without calling start is NOT an error

2016-08-05T09:06:36.779Z - info: Running on android test: 54. Can call start/stopUpdateAdvertisingAndListening

2016-08-05T09:06:37.807Z - info: Running on android test: 55. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-08-05T09:06:39.041Z - info: Running on android test: 56. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error

2016-08-05T09:06:39.240Z - info: Running on android test: 57. cannot call connect when start listening for advertisements is not active

2016-08-05T09:06:39.412Z - info: Running on android test: 58. peerAvailabilityChange is called

2016-08-05T09:19:19.285Z - info: Socket to device motorola-Nexus 6 disconnected: transport close

2016-08-05T09:19:21.829Z - info: Socket to device samsung-SM-G900F disconnected: transport close


 
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
Device test finished on LGD7228ee9cf5b 
Device test finished on 1d6a772d 
Android task is completed. [SUCCESS]
```
[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/79751015d1afc27_Check_811_failures_in_CI_do_not_merge__czyzm/thali05_samsung-SM-N9005.md)

[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/79751015d1afc27_Check_811_failures_in_CI_do_not_merge__czyzm/thali05_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/79751015d1afc27_Check_811_failures_in_CI_do_not_merge__czyzm/thali05_LGE-LG-D855.md)

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
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/79751015d1afc27_Check_811_failures_in_CI_do_not_merge__czyzm/thali08_motorola-Nexus 6.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/79751015d1afc27_Check_811_failures_in_CI_do_not_merge__czyzm/thali08_samsung-SM-G900F.md)





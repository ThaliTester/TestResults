#### Test 79751015a95812e Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":6}}
2016-08-05T06:04:49.913Z - info: Require 3 ios devices

2016-08-05T06:04:49.933Z - info: Require 3 android devices

2016-08-05T06:04:49.991Z - info: listening on *:3000

2016-08-05T06:04:51.752Z - debug: Device presented: LGE-LG-D722 (ff86b900-4b16-48b8-87ee-dc842c112d10) - android 5.0.2

2016-08-05T06:04:52.583Z - debug: Device presented: LGE-LG-D722 (ff86b900-4b16-48b8-87ee-dc842c112d10) - android 5.0.2

2016-08-05T06:04:52.585Z - info: Updating existing device: LGE-LG-D722 (ff86b900-4b16-48b8-87ee-dc842c112d10)

2016-08-05T06:04:57.535Z - debug: Device presented: LGE-LG-D855 (a44f7874-8049-4698-89fc-561f2e17dbea) - android 5.0

2016-08-05T06:04:57.639Z - debug: Device presented: samsung-SM-N9005 (5d352a7b-13e8-44ce-8dbd-da441075dc54) - android 5.0

2016-08-05T06:04:58.526Z - debug: Device presented: LGE-LG-D855 (a44f7874-8049-4698-89fc-561f2e17dbea) - android 5.0

2016-08-05T06:04:58.529Z - info: Updating existing device: LGE-LG-D855 (a44f7874-8049-4698-89fc-561f2e17dbea)

2016-08-05T06:04:58.651Z - debug: Device presented: samsung-SM-N9005 (5d352a7b-13e8-44ce-8dbd-da441075dc54) - android 5.0

2016-08-05T06:04:58.652Z - info: Updating existing device: samsung-SM-N9005 (5d352a7b-13e8-44ce-8dbd-da441075dc54)

2016-08-05T06:05:31.187Z - debug: Device presented: samsung-SM-N910C (d8d6cbe5-4f94-4cff-8df9-cfd0ea67f979) - android 6.0.1

2016-08-05T06:05:36.941Z - debug: Device presented: samsung-SM-G900F (cb212c96-b93c-4732-9a0d-83446d49dab5) - android 6.0.1

2016-08-05T06:05:59.931Z - debug: Device presented: motorola-Nexus 6 (bda10304-7616-484f-b58e-5814f76386b8) - android 6.0.1

2016-08-05T06:05:59.932Z - info: All 6 android devices are present

2016-08-05T06:05:59.935Z - info: Disqualifying device with unsupported hardware: LGE-LG-D722

2016-08-05T06:05:59.942Z - info: Disqualifying device with unsupported hardware: LGE-LG-D855

2016-08-05T06:05:59.948Z - info: Disqualifying device with unsupported hardware: samsung-SM-N9005

2016-08-05T06:05:59.955Z - info: Starting unit test run on 3 android devices

2016-08-05T06:06:00.981Z - info: Socket to device samsung-SM-N9005 disconnected: transport close

2016-08-05T06:06:01.019Z - info: Socket to device LGE-LG-D855 disconnected: transport close

2016-08-05T06:06:01.183Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-08-05T06:06:01.609Z - info: Running on android test: 2. emits incomingConnectionState

2016-08-05T06:06:01.702Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-05T06:06:02.086Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-08-05T06:06:02.602Z - info: Running on android test: 4. native server connections all up

2016-08-05T06:06:03.003Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-08-05T06:06:03.419Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-08-05T06:06:03.777Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-08-05T06:06:04.196Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-08-05T06:06:04.522Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-08-05T06:06:06.412Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-08-05T06:06:07.011Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-08-05T06:06:07.356Z - info: Running on android test: 12. #_doImmediateSeqUpdate - server is not there

2016-08-05T06:06:07.740Z - info: Running on android test: 13. #_doImmediateSeqUpdate - server accepts & closes connection

2016-08-05T06:06:08.000Z - info: Running on android test: 14. #_doImmediateSeqUpdate - server always returns 500

2016-08-05T06:06:08.325Z - info: Running on android test: 15. #_doImmediateSeqUpdate - create new seq doc

2016-08-05T06:06:10.711Z - info: Running on android test: 16. #_doImmediateSeqUpdate - doc exists, need to get rev and update

2016-08-05T06:06:11.728Z - info: Running on android test: 17. #_doImmediateSeqUpdate - update seq three times

2016-08-05T06:06:12.846Z - info: Running on android test: 18. #_doImmediateSeqUpdate - rev got changed under us

2016-08-05T06:06:13.770Z - info: Running on android test: 19. #_doImmediateSeqUpdate - fail if stop is called

2016-08-05T06:06:14.091Z - info: Running on android test: 20. #_doImmediateSeqUpdate - stop after get but before put fails right

2016-08-05T06:06:14.721Z - info: Running on android test: 21. #update - fail if stop is called

2016-08-05T06:06:15.105Z - info: Running on android test: 22. #update - set seq for first time

2016-08-05T06:06:15.918Z - info: Running on android test: 23. #update - Fail on bad seq value

2016-08-05T06:06:16.478Z - info: Running on android test: 24. #update - do we cancel timer properly on an immediate?

2016-08-05T06:06:17.225Z - info: Running on android test: 25. #update - do we wait for blocked update

2016-08-05T06:06:17.919Z - info: Running on android test: 26. #update - test that we wait long enough

2016-08-05T06:06:20.545Z - info: Running on android test: 27. #update - test that we pick up new sequences while we wait

2016-08-05T06:06:22.778Z - info: Running on android test: 28. Coordinated seq test

2016-08-05T06:11:23.444Z - warn: Failed on android test: 28. Coordinated seq test

2016-08-05T06:11:23.445Z - info: Running on android test: 29. closeAll can close even when connections open

2016-08-05T06:11:23.835Z - info: Running on android test: 30. closeAll with promise

2016-08-05T06:11:24.251Z - info: Running on android test: 31. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-08-05T06:11:24.621Z - info: Running on android test: 32. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-08-05T06:11:24.968Z - info: Running on android test: 33. enqueue and run in order

2016-08-05T06:11:25.470Z - info: Running on android test: 34. enqueueAtTop and run backwards

2016-08-05T06:11:25.775Z - info: Running on android test: 35. mix enqueue and enqueueAtTop

2016-08-05T06:11:26.139Z - info: Running on android test: 36. queues handled independently

2016-08-05T06:11:26.385Z - info: Running on android test: 37. basic

2016-08-05T06:11:26.620Z - info: Running on android test: 38. another

2016-08-05T06:11:26.879Z - info: Running on android test: 39. can pass data in setup

2016-08-05T06:11:27.130Z - info: Running on android test: 40. #startListeningForAdvertisements should fail if start not called

2016-08-05T06:11:27.364Z - info: Running on android test: 41. #startUpdateAdvertisingAndListening should fail if start not called

2016-08-05T06:11:27.567Z - info: Running on android test: 42. should be able to call #stopListeningForAdvertisements many times

2016-08-05T06:11:27.839Z - info: Running on android test: 43. should be able to call #startListeningForAdvertisements many times

2016-08-05T06:11:32.549Z - info: Running on android test: 44. should be able to call #startUpdateAdvertisingAndListening many times

2016-08-05T06:11:35.168Z - info: Running on android test: 45. should be able to call #stopAdvertisingAndListening many times

2016-08-05T06:11:35.500Z - info: Running on android test: 46. #start should fail if called twice in a row

2016-08-05T06:11:35.743Z - info: Running on android test: 47. does not emit duplicate discoveryAdvertisingStateUpdate

2016-08-05T06:11:37.712Z - info: Running on android test: 48. does not send duplicate availability changes

2016-08-05T06:11:37.921Z - info: Running on android test: 49. can get the network status

2016-08-05T06:11:38.108Z - info: Running on android test: 50. wifi peer is marked unavailable if announcements stop

2016-08-05T06:11:40.398Z - info: Running on android test: 51. Can call start/stopListeningForAdvertisements

2016-08-05T06:11:41.881Z - info: Running on android test: 52. Calling startListeningForAdvertisements twice is NOT an error

2016-08-05T06:11:43.435Z - info: Running on android test: 53. Calling stopListeningForAdvertisements without calling start is NOT an error

2016-08-05T06:11:43.729Z - info: Running on android test: 54. Can call start/stopUpdateAdvertisingAndListening

2016-08-05T06:11:44.776Z - info: Running on android test: 55. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-08-05T06:11:46.669Z - info: Running on android test: 56. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error

2016-08-05T06:13:11.672Z - info: Socket to device samsung-SM-N910C disconnected: ping timeout

2016-08-05T06:13:45.982Z - debug: Too many emit retries to device: samsung-SM-N910C

2016-08-05T06:28:43.381Z - info: Socket to device motorola-Nexus 6 disconnected: transport close

2016-08-05T06:28:48.076Z - info: Socket to device samsung-SM-G900F disconnected: transport close


 
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
[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/79751015a95812e_Check_811_failures_in_CI_do_not_merge__czyzm/thali05_samsung-SM-N9005.md)

[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/79751015a95812e_Check_811_failures_in_CI_do_not_merge__czyzm/thali05_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/79751015a95812e_Check_811_failures_in_CI_do_not_merge__czyzm/thali05_LGE-LG-D855.md)

####Node name: thali08
Console output:
```


 Marshmallow device. Granting ACCESS_COARSE_LOCATION permission


 Marshmallow device. Granting ACCESS_COARSE_LOCATION permission


 Marshmallow device. Granting ACCESS_COARSE_LOCATION permission
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1G429CRK 
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:0 
child process exited with code 0 on device 41006f95c8139173 
Error! Unexpected exit on device 0be0c6c6 app:com.test.thalitest code:null 
child process exited with code null on device 0be0c6c6 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/79751015a95812e_Check_811_failures_in_CI_do_not_merge__czyzm/thali08_motorola-Nexus 6.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/79751015a95812e_Check_811_failures_in_CI_do_not_merge__czyzm/thali08_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/79751015a95812e_Check_811_failures_in_CI_do_not_merge__czyzm/thali08_samsung-SM-G900F.md)





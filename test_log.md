#### Test 852025184f78031 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-09-14T14:24:28.844Z - info: Require 0 ios devices

2016-09-14T14:24:28.863Z - info: Require 3 android devices

2016-09-14T14:24:28.919Z - info: listening on *:3000

2016-09-14T14:26:20.672Z - debug: Device presented: samsung-SM-G930F (d731b19c-561e-459c-896e-9beccd4993d6) - android 6.0.1

2016-09-14T14:26:21.525Z - debug: Device presented: LGE-LG-H850 (6ab1e51c-449c-452f-a343-72a775a79c89) - android 6.0.1

2016-09-14T14:26:27.492Z - debug: Device presented: Huawei-Nexus 6P (27e9017f-0d32-4a90-9dde-43293e444e2c) - android 6.0.1

2016-09-14T14:26:27.493Z - info: All 3 android devices are present

2016-09-14T14:26:27.500Z - info: Starting unit test run on 3 android devices

2016-09-14T14:26:28.644Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-09-14T14:26:29.049Z - info: Running on android test: 2. emits incomingConnectionState

2016-09-14T14:26:29.391Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-09-14T14:26:29.785Z - info: Running on android test: 4. native server connections all up

2016-09-14T14:26:30.197Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-09-14T14:26:30.537Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-09-14T14:26:30.863Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-09-14T14:26:31.254Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-09-14T14:26:31.548Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-09-14T14:26:33.457Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-09-14T14:26:34.516Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-09-14T14:26:34.792Z - info: Running on android test: 12. closeAll can close even when connections open

2016-09-14T14:26:35.265Z - info: Running on android test: 13. closeAll with promise

2016-09-14T14:26:35.602Z - info: Running on android test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-09-14T14:26:35.944Z - info: Running on android test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-09-14T14:26:36.242Z - info: Running on android test: 16. onPeerLost calls jxcore

2016-09-14T14:26:38.554Z - info: Running on android test: 17. onPeerDiscovered calls jxcore

2016-09-14T14:26:40.879Z - info: Running on android test: 18. test defaultDirectory

2016-09-14T14:26:41.215Z - info: Running on android test: 19. test defaultAdapter

2016-09-14T14:26:41.689Z - info: Running on android test: 20. enqueue and run in order

2016-09-14T14:26:42.163Z - info: Running on android test: 21. enqueueAtTop and run backwards

2016-09-14T14:26:42.395Z - info: Running on android test: 22. mix enqueue and enqueueAtTop

2016-09-14T14:26:42.746Z - info: Running on android test: 23. queues handled independently

2016-09-14T14:26:43.133Z - info: Running on android test: 24. basic

2016-09-14T14:26:43.328Z - info: Running on android test: 25. another

2016-09-14T14:26:43.522Z - info: Running on android test: 26. can pass data in setup

2016-09-14T14:26:43.725Z - info: Running on android test: 27. #startListeningForAdvertisements should fail if start not called

2016-09-14T14:26:43.949Z - info: Running on android test: 28. #startUpdateAdvertisingAndListening should fail if start not called

2016-09-14T14:26:44.161Z - info: Running on android test: 29. should be able to call #stopListeningForAdvertisements many times

2016-09-14T14:26:45.605Z - info: Running on android test: 30. should be able to call #startListeningForAdvertisements many times

2016-09-14T14:26:47.135Z - info: Running on android test: 31. should be able to call #startUpdateAdvertisingAndListening many times

2016-09-14T14:26:48.426Z - info: Running on android test: 32. should be able to call #stopAdvertisingAndListening many times

2016-09-14T14:26:48.706Z - info: Running on android test: 33. #start should fail if called twice in a row

2016-09-14T14:26:48.967Z - info: Running on android test: 34. does not emit duplicate discoveryAdvertisingStateUpdate

2016-09-14T14:26:50.784Z - info: Running on android test: 35. does not send duplicate availability changes

2016-09-14T14:26:51.033Z - info: Running on android test: 36. can get the network status

2016-09-14T14:26:51.280Z - info: Running on android test: 37. wifi peer is marked unavailable if announcements stop

2016-09-14T14:26:53.502Z - info: Running on android test: 38. Client to server request coordinated

2016-09-14T14:28:59.899Z - warn: Failed on android test: 38. Client to server request coordinated

2016-09-14T14:28:59.900Z - info: Running on android test: 39. Test BEACONS_RETRIEVED_AND_PARSED locally

2016-09-14T14:29:00.448Z - info: Running on android test: 40. Test HTTP_BAD_RESPONSE locally

2016-09-14T14:29:00.934Z - info: Running on android test: 41. Test NETWORK_PROBLEM locally

2016-09-14T14:29:02.567Z - info: Running on android test: 42. Call the start two times

2016-09-14T14:29:04.687Z - info: Running on android test: 43. Call the kill before calling the start

2016-09-14T14:29:05.105Z - info: Running on android test: 44. Call the kill immediately after the start

2016-09-14T14:29:06.760Z - info: Running on android test: 45. Call the kill while waiting a response from the server

2016-09-14T14:29:10.855Z - info: Running on android test: 46. Test to exceed the max content size locally

2016-09-14T14:29:12.487Z - info: Running on android test: 47. Close the server socket while the client is waiting a response from the server. Local test.

2016-09-14T14:29:16.567Z - info: Running on android test: 48. Close the client socket while the client is waiting a response from the server. Local test.

2016-09-14T14:29:19.540Z - info: Running on android test: 49. #generatePreambleAndBeacons bad args

2016-09-14T14:29:19.844Z - info: Running on android test: 50. #generatePreambleAndBeacons empty keys to notify

2016-09-14T14:29:20.136Z - info: Running on android test: 51. #generatePreambleAndBeacons multiple keys to notify

2016-09-14T14:29:20.446Z - info: Running on android test: 52. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-09-14T14:29:20.733Z - info: Running on android test: 53. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-09-14T14:29:20.982Z - info: Running on android test: 54. #parseBeacons expiration out of range lower

2016-09-14T14:29:21.279Z - info: Running on android test: 55. #parseBeacons expiration out of range lower

2016-09-14T14:29:21.561Z - info: Running on android test: 56. #parseBeacons no beacons returns null

2016-09-14T14:29:22.854Z - info: Running on android test: 57. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!
```
###Android Logs
####Node name: thali06
Console output:
```

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
Error! Unexpected exit on device ce0616068b9f212302 app:com.test.thalitest code:null 
child process exited with code null on device ce0616068b9f212302 
Error! Unexpected exit on device ENU7N16516000107 app:com.test.thalitest code:null 
child process exited with code null on device ENU7N16516000107 
Error! Unexpected exit on device LGH85049457824 app:com.test.thalitest code:null 
child process exited with code null on device LGH85049457824 
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/852025184f78031__1031_DO_NOT_MERGE_Excluded__bad__test_files_artemjackson/thali06_samsung-SM-G930F.md)

[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/852025184f78031__1031_DO_NOT_MERGE_Excluded__bad__test_files_artemjackson/thali06_Huawei-Nexus 6P.md)

[LGE-LG-H850](https://github.com/ThaliTester/TestResults/blob/852025184f78031__1031_DO_NOT_MERGE_Excluded__bad__test_files_artemjackson/thali06_LGE-LG-H850.md)





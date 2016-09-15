#### Test 8520251856d1c3c Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-09-15T07:35:45.717Z - info: Require 0 ios devices

2016-09-15T07:35:45.736Z - info: Require 3 android devices

2016-09-15T07:35:45.792Z - info: listening on *:3000

2016-09-15T07:37:37.572Z - debug: Device presented: samsung-SM-G930F (d5ed4044-837a-4ed7-a18a-28c83c60012d) - android 6.0.1

2016-09-15T07:37:38.523Z - debug: Device presented: LGE-LG-H850 (f7a22ae9-a149-465d-82be-6ab4ef807a2e) - android 6.0.1

2016-09-15T07:37:40.387Z - debug: Device presented: Huawei-Nexus 6P (89e6618f-61a3-47e8-ac4f-5a6ad78ed99e) - android 6.0.1

2016-09-15T07:37:40.390Z - info: All 3 android devices are present

2016-09-15T07:37:40.397Z - info: Starting unit test run on 3 android devices

2016-09-15T07:37:40.901Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-09-15T07:37:41.334Z - info: Running on android test: 2. emits incomingConnectionState

2016-09-15T07:37:41.670Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-09-15T07:37:42.014Z - info: Running on android test: 4. native server connections all up

2016-09-15T07:37:42.393Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-09-15T07:37:42.752Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-09-15T07:37:43.067Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-09-15T07:37:43.409Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-09-15T07:37:43.703Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-09-15T07:37:45.572Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-09-15T07:37:45.953Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-09-15T07:37:46.254Z - info: Running on android test: 12. closeAll can close even when connections open

2016-09-15T07:37:46.597Z - info: Running on android test: 13. closeAll with promise

2016-09-15T07:37:46.952Z - info: Running on android test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-09-15T07:37:47.298Z - info: Running on android test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-09-15T07:37:47.594Z - info: Running on android test: 16. onPeerLost calls jxcore

2016-09-15T07:37:49.913Z - info: Running on android test: 17. onPeerDiscovered calls jxcore

2016-09-15T07:37:52.620Z - info: Running on android test: 18. test defaultDirectory

2016-09-15T07:37:52.887Z - info: Running on android test: 19. test defaultAdapter

2016-09-15T07:37:53.380Z - info: Running on android test: 20. enqueue and run in order

2016-09-15T07:37:53.855Z - info: Running on android test: 21. enqueueAtTop and run backwards

2016-09-15T07:37:54.089Z - info: Running on android test: 22. mix enqueue and enqueueAtTop

2016-09-15T07:37:54.425Z - info: Running on android test: 23. queues handled independently

2016-09-15T07:37:54.809Z - info: Running on android test: 24. basic

2016-09-15T07:37:55.001Z - info: Running on android test: 25. another

2016-09-15T07:37:55.207Z - info: Running on android test: 26. can pass data in setup

2016-09-15T07:37:55.386Z - info: Running on android test: 27. #startListeningForAdvertisements should fail if start not called

2016-09-15T07:37:55.611Z - info: Running on android test: 28. #startUpdateAdvertisingAndListening should fail if start not called

2016-09-15T07:37:55.823Z - info: Running on android test: 29. should be able to call #stopListeningForAdvertisements many times

2016-09-15T07:37:56.142Z - info: Running on android test: 30. should be able to call #startListeningForAdvertisements many times

2016-09-15T07:37:57.622Z - info: Running on android test: 31. should be able to call #startUpdateAdvertisingAndListening many times

2016-09-15T07:37:58.856Z - info: Running on android test: 32. should be able to call #stopAdvertisingAndListening many times

2016-09-15T07:37:59.107Z - info: Running on android test: 33. #start should fail if called twice in a row

2016-09-15T07:37:59.388Z - info: Running on android test: 34. does not emit duplicate discoveryAdvertisingStateUpdate

2016-09-15T07:38:01.015Z - info: Running on android test: 35. does not send duplicate availability changes

2016-09-15T07:38:01.261Z - info: Running on android test: 36. can get the network status

2016-09-15T07:38:01.502Z - info: Running on android test: 37. wifi peer is marked unavailable if announcements stop

2016-09-15T07:38:03.773Z - info: Running on android test: 38. Client to server request coordinated

2016-09-15T07:38:09.643Z - info: Running on android test: 39. Test BEACONS_RETRIEVED_AND_PARSED locally

2016-09-15T07:38:10.166Z - info: Running on android test: 40. Test HTTP_BAD_RESPONSE locally

2016-09-15T07:38:10.596Z - info: Running on android test: 41. Test NETWORK_PROBLEM locally

2016-09-15T07:38:11.076Z - info: Running on android test: 42. Call the start two times

2016-09-15T07:38:11.523Z - info: Running on android test: 43. Call the kill before calling the start

2016-09-15T07:38:11.835Z - info: Running on android test: 44. Call the kill immediately after the start

2016-09-15T07:38:12.197Z - info: Running on android test: 45. Call the kill while waiting a response from the server

2016-09-15T07:38:15.727Z - info: Running on android test: 46. Test to exceed the max content size locally

2016-09-15T07:38:16.269Z - info: Running on android test: 47. Close the server socket while the client is waiting a response from the server. Local test.

2016-09-15T07:38:18.694Z - info: Running on android test: 48. Close the client socket while the client is waiting a response from the server. Local test.

2016-09-15T07:38:21.040Z - info: Running on android test: 49. #generatePreambleAndBeacons bad args

2016-09-15T07:38:21.302Z - info: Running on android test: 50. #generatePreambleAndBeacons empty keys to notify

2016-09-15T07:38:21.521Z - info: Running on android test: 51. #generatePreambleAndBeacons multiple keys to notify

2016-09-15T07:38:21.817Z - info: Running on android test: 52. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-09-15T07:38:22.081Z - info: Running on android test: 53. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-09-15T07:38:22.298Z - info: Running on android test: 54. #parseBeacons expiration out of range lower

2016-09-15T07:38:22.525Z - info: Running on android test: 55. #parseBeacons expiration out of range lower

2016-09-15T07:38:22.739Z - info: Running on android test: 56. #parseBeacons no beacons returns null

2016-09-15T07:38:22.976Z - info: Running on android test: 57. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-09-15T07:38:23.188Z - info: Running on android test: 58. #parseBeacons addressBookCallback fails decrypt

2016-09-15T07:38:23.498Z - info: Running on android test: 59. #parseBeacons addressBookCallback returns no matches

2016-09-15T07:38:23.824Z - info: Running on android test: 60. #parseBeacons addressBookCallback returns spurious match

2016-09-15T07:38:24.123Z - info: Running on android test: 61. #parseBeacons addressBookCallback returns public key

2016-09-15T07:38:24.426Z - info: Running on android test: 62. validate generatePskIdentityField

2016-09-15T07:38:24.638Z - info: Running on android test: 63. validate generatePskSecret

2016-09-15T07:38:24.878Z - info: Running on android test: 64. validate generatePskSecrets

2016-09-15T07:38:25.232Z - info: Running on android test: 65. validate generateBeaconStreamAndSecrets

2016-09-15T07:38:25.550Z - info: Running on android test: 66. Add two Peers.

2016-09-15T07:38:25.857Z - info: Running on android test: 67. TCP_NATIVE peer loses DNS

2016-09-15T07:38:26.173Z - info: Running on android test: 68. Received beacons with no values for us

2016-09-15T07:38:26.658Z - info: Running on android test: 69. Resolves an action locally

2016-09-15T07:38:27.165Z - info: Running on android test: 70. Resolves an action locally using ThaliPeerPoolDefault

2016-09-15T07:38:27.648Z - info: Running on android test: 71. Action fails because of a bad hostname.

2016-09-15T07:38:34.265Z - info: Running on android test: 72. hostaddress is removed when the action is running. 

2016-09-15T07:38:36.720Z - info: Running on android test: 73. Client to server request locally

2016-09-15T07:38:37.162Z - info: Running on android test: 74. Test ThaliPskMapCache clean and expiration

2016-09-15T07:38:38.470Z - info: Running on android test: 75. Test ThaliPskMapCache getSecret and getPublic

2016-09-15T07:38:39.841Z - info: Running on android test: 76. Test ThaliPskMapCache multiple entries

2016-09-15T07:38:43.251Z - info: Running on android test: 77. Start and stop ThaliNotificationServer

2016-09-15T07:38:43.568Z - info: Running on android test: 78. Pass an empty array to ThaliNotificationServer.start

2016-09-15T07:38:43.882Z - info: Running on android test: 79. Pass a string to ThaliNotificationServer.start

2016-09-15T07:38:44.146Z - info: Running on android test: 80. Pass an empty parameter to ThaliNotificationServer.start

2016-09-15T07:38:44.463Z - info: Running on android test: 81. Make an HTTP request to /NotificationBeacons

2016-09-15T07:38:44.895Z - info: Running on android test: 82. Make an HTTP request to /NotificationBeacons (no keys)

2016-09-15T07:38:45.165Z - info: Running on android test: 83. Make an HTTP request to /NotificationBeaconsbefore calling start

2016-09-15T07:38:45.429Z - info: Running on android test: 84. #testThaliPeerAction - test getters

2016-09-15T07:38:45.642Z - info: Running on android test: 85. #testThaliPeerAction - start and kill

2016-09-15T07:38:45.835Z - info: Running on android test: 86. #testThaliPeerAction - double start

2016-09-15T07:38:46.027Z - info: Running on android test: 87. #testThaliPeerAction - start after kill

2016-09-15T07:38:46.241Z - info: Running on android test: 88. #testThaliPeerAction - make sure ids are unique

2016-09-15T07:38:46.450Z - info: Running on android test: 89. Test PeerConnectionInformation basics

2016-09-15T07:38:46.643Z - info: Running on android test: 90. Test PeerDictionary basic functionality

2016-09-15T07:38:46.858Z - info: Running on android test: 91. Test PeerDictionary with multiple entries.

2016-09-15T07:38:49.013Z - info: Running on android test: 92. RESOLVED entries are removed before WAITING state entry.

2016-09-15T07:38:49.851Z - info: Running on android test: 93. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-09-15T07:38:52.388Z - info: Running on android test: 94. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-09-15T07:38:53.679Z - info: Running on android test: 95. #ThaliPeerPoolInterface - make sure that start verifies queue length

2016-09-15T07:38:53.919Z - info: Running on android test: 96. #ThaliPeerPoolInterface - bad enqueues

2016-09-15T07:38:54.105Z - info: Running on android test: 97. #ThaliPeerPoolInterface - do not allow same object type

2016-09-15T07:38:54.339Z - info: Running on android test: 98. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-09-15T07:38:54.594Z - info: Running on android test: 99. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent

2016-09-15T07:38:54.809Z - info: Running on android test: 100. #ThaliPeerPoolInterface - make sure that stop removes all actions

2016-09-15T07:38:54.997Z - info: Running on android test: 101. Make sure peerDictionaryKey is reasonable

2016-09-15T07:38:55.175Z - info: Running on android test: 102. Make sure start works

2016-09-15T07:38:55.381Z - info: Running on android test: 103. Make sure stop works

2016-09-15T07:38:55.643Z - info: Running on android test: 104. Simple peer event

2016-09-15T07:38:55.928Z - info: Running on android test: 105. Coordinated pull replication from notification test

2016-09-15T07:38:57.359Z - info: Socket to device samsung-SM-G930F disconnected: transport close

2016-09-15T07:40:55.104Z - debug: Too many emit retries to device: samsung-SM-G930F

2016-09-15T07:59:15.385Z - info: Socket to device Huawei-Nexus 6P disconnected: transport close

2016-09-15T07:59:16.491Z - info: Socket to device LGE-LG-H850 disconnected: transport close


 
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
####Node name: thali06
Console output:
```

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ce0616068b9f212302 app:com.test.thalitest code:0 
child process exited with code 0 on device ce0616068b9f212302 
Error! Unexpected exit on device ENU7N16516000107 app:com.test.thalitest code:0 
child process exited with code 0 on device ENU7N16516000107 
Error! Unexpected exit on device LGH85049457824 app:com.test.thalitest code:0 
child process exited with code 0 on device LGH85049457824 
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/8520251856d1c3c__1031_DO_NOT_MERGE_Excluded__bad__test_files_artemjackson/thali06_samsung-SM-G930F.md)

[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/8520251856d1c3c__1031_DO_NOT_MERGE_Excluded__bad__test_files_artemjackson/thali06_Huawei-Nexus 6P.md)

[LGE-LG-H850](https://github.com/ThaliTester/TestResults/blob/8520251856d1c3c__1031_DO_NOT_MERGE_Excluded__bad__test_files_artemjackson/thali06_LGE-LG-H850.md)





#### Test 852025185ed7d1b Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-09-16T12:28:36.680Z - info: Require 0 ios devices

2016-09-16T12:28:36.699Z - info: Require 3 android devices

2016-09-16T12:28:36.755Z - info: listening on *:3000

2016-09-16T12:30:25.679Z - debug: Device presented: samsung-SM-G935F (4a5b688e-fb07-4847-9262-6eb2738ca5a8) - android 6.0.1

2016-09-16T12:30:26.268Z - debug: Device presented: samsung-SM-G930F (738a7884-2e81-4c15-9a5d-16132eea729e) - android 6.0.1

2016-09-16T12:30:30.114Z - debug: Device presented: Huawei-Nexus 6P (42fe85da-e8fa-4862-923f-959cc949929b) - android 6.0.1

2016-09-16T12:30:30.115Z - info: All 3 android devices are present

2016-09-16T12:30:30.122Z - info: Starting unit test run on 3 android devices

2016-09-16T12:30:31.389Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-09-16T12:30:31.782Z - info: Running on android test: 2. emits incomingConnectionState

2016-09-16T12:30:32.147Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-09-16T12:30:32.460Z - info: Running on android test: 4. native server connections all up

2016-09-16T12:30:32.838Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-09-16T12:30:33.304Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-09-16T12:30:33.538Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-09-16T12:30:33.865Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-09-16T12:30:34.126Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-09-16T12:30:36.323Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-09-16T12:30:37.672Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-09-16T12:30:37.906Z - info: Running on android test: 12. closeAll can close even when connections open

2016-09-16T12:30:38.204Z - info: Running on android test: 13. closeAll with promise

2016-09-16T12:30:38.497Z - info: Running on android test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-09-16T12:30:38.821Z - info: Running on android test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-09-16T12:30:39.127Z - info: Running on android test: 16. onPeerLost calls jxcore

2016-09-16T12:30:41.470Z - info: Running on android test: 17. onPeerDiscovered calls jxcore

2016-09-16T12:30:43.775Z - info: Running on android test: 18. test defaultDirectory

2016-09-16T12:30:44.020Z - info: Running on android test: 19. test defaultAdapter

2016-09-16T12:30:44.441Z - info: Running on android test: 20. enqueue and run in order

2016-09-16T12:30:44.922Z - info: Running on android test: 21. enqueueAtTop and run backwards

2016-09-16T12:30:45.128Z - info: Running on android test: 22. mix enqueue and enqueueAtTop

2016-09-16T12:30:45.441Z - info: Running on android test: 23. queues handled independently

2016-09-16T12:30:45.798Z - info: Running on android test: 24. basic

2016-09-16T12:30:45.972Z - info: Running on android test: 25. another

2016-09-16T12:30:46.151Z - info: Running on android test: 26. can pass data in setup

2016-09-16T12:30:46.359Z - info: Running on android test: 27. #startListeningForAdvertisements should fail if start not called

2016-09-16T12:30:46.581Z - info: Running on android test: 28. #startUpdateAdvertisingAndListening should fail if start not called

2016-09-16T12:30:46.778Z - info: Running on android test: 29. should be able to call #stopListeningForAdvertisements many times

2016-09-16T12:30:47.117Z - info: Running on android test: 30. should be able to call #startListeningForAdvertisements many times

2016-09-16T12:30:48.640Z - info: Running on android test: 31. should be able to call #startUpdateAdvertisingAndListening many times

2016-09-16T12:30:49.736Z - info: Running on android test: 32. should be able to call #stopAdvertisingAndListening many times

2016-09-16T12:30:49.996Z - info: Running on android test: 33. #start should fail if called twice in a row

2016-09-16T12:30:50.275Z - info: Running on android test: 34. does not emit duplicate discoveryAdvertisingStateUpdate

2016-09-16T12:30:51.996Z - info: Running on android test: 35. does not send duplicate availability changes

2016-09-16T12:30:52.215Z - info: Running on android test: 36. can get the network status

2016-09-16T12:30:52.414Z - info: Running on android test: 37. wifi peer is marked unavailable if announcements stop

2016-09-16T12:30:54.653Z - info: Running on android test: 38. Client to server request coordinated

2016-09-16T12:33:00.746Z - warn: Failed on android test: 38. Client to server request coordinated

2016-09-16T12:33:00.747Z - info: Running on android test: 39. Test BEACONS_RETRIEVED_AND_PARSED locally

2016-09-16T12:33:01.251Z - info: Running on android test: 40. Test HTTP_BAD_RESPONSE locally

2016-09-16T12:33:01.677Z - info: Running on android test: 41. Test NETWORK_PROBLEM locally

2016-09-16T12:33:02.124Z - info: Running on android test: 42. Call the start two times

2016-09-16T12:33:02.592Z - info: Running on android test: 43. Call the kill before calling the start

2016-09-16T12:33:03.011Z - info: Running on android test: 44. Call the kill immediately after the start

2016-09-16T12:33:03.371Z - info: Running on android test: 45. Call the kill while waiting a response from the server

2016-09-16T12:33:05.808Z - info: Running on android test: 46. Test to exceed the max content size locally

2016-09-16T12:33:06.284Z - info: Running on android test: 47. Close the server socket while the client is waiting a response from the server. Local test.

2016-09-16T12:33:08.610Z - info: Running on android test: 48. Close the client socket while the client is waiting a response from the server. Local test.

2016-09-16T12:33:10.978Z - info: Running on android test: 49. #generatePreambleAndBeacons bad args

2016-09-16T12:33:11.184Z - info: Running on android test: 50. #generatePreambleAndBeacons empty keys to notify

2016-09-16T12:33:11.390Z - info: Running on android test: 51. #generatePreambleAndBeacons multiple keys to notify

2016-09-16T12:33:11.682Z - info: Running on android test: 52. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-09-16T12:33:11.874Z - info: Running on android test: 53. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-09-16T12:33:12.076Z - info: Running on android test: 54. #parseBeacons expiration out of range lower

2016-09-16T12:33:12.330Z - info: Running on android test: 55. #parseBeacons expiration out of range lower

2016-09-16T12:33:12.589Z - info: Running on android test: 56. #parseBeacons no beacons returns null

2016-09-16T12:33:12.779Z - info: Running on android test: 57. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-09-16T12:33:12.968Z - info: Running on android test: 58. #parseBeacons addressBookCallback fails decrypt

2016-09-16T12:33:13.281Z - info: Running on android test: 59. #parseBeacons addressBookCallback returns no matches

2016-09-16T12:33:13.606Z - info: Running on android test: 60. #parseBeacons addressBookCallback returns spurious match

2016-09-16T12:33:13.960Z - info: Running on android test: 61. #parseBeacons addressBookCallback returns public key

2016-09-16T12:33:14.260Z - info: Running on android test: 62. validate generatePskIdentityField

2016-09-16T12:33:14.470Z - info: Running on android test: 63. validate generatePskSecret

2016-09-16T12:33:14.732Z - info: Running on android test: 64. validate generatePskSecrets

2016-09-16T12:33:15.083Z - info: Running on android test: 65. validate generateBeaconStreamAndSecrets

2016-09-16T12:33:15.405Z - info: Running on android test: 66. Add two Peers.

2016-09-16T12:33:15.715Z - info: Running on android test: 67. TCP_NATIVE peer loses DNS

2016-09-16T12:33:16.009Z - info: Running on android test: 68. Received beacons with no values for us

2016-09-16T12:33:16.429Z - info: Running on android test: 69. Resolves an action locally

2016-09-16T12:33:16.886Z - info: Running on android test: 70. Resolves an action locally using ThaliPeerPoolDefault

2016-09-16T12:33:17.349Z - info: Running on android test: 71. Action fails because of a bad hostname.

2016-09-16T12:33:27.691Z - info: Running on android test: 72. hostaddress is removed when the action is running. 

2016-09-16T12:33:30.050Z - info: Running on android test: 73. Client to server request locally

2016-09-16T12:33:30.448Z - info: Running on android test: 74. Test ThaliPskMapCache clean and expiration

2016-09-16T12:33:31.683Z - info: Running on android test: 75. Test ThaliPskMapCache getSecret and getPublic

2016-09-16T12:33:33.083Z - info: Running on android test: 76. Test ThaliPskMapCache multiple entries

2016-09-16T12:33:35.917Z - info: Running on android test: 77. Start and stop ThaliNotificationServer

2016-09-16T12:33:36.269Z - info: Running on android test: 78. Pass an empty array to ThaliNotificationServer.start

2016-09-16T12:33:36.620Z - info: Running on android test: 79. Pass a string to ThaliNotificationServer.start

2016-09-16T12:33:37.087Z - info: Running on android test: 80. Pass an empty parameter to ThaliNotificationServer.start

2016-09-16T12:33:37.361Z - info: Running on android test: 81. Make an HTTP request to /NotificationBeacons

2016-09-16T12:33:37.769Z - info: Running on android test: 82. Make an HTTP request to /NotificationBeacons (no keys)

2016-09-16T12:33:38.072Z - info: Running on android test: 83. Make an HTTP request to /NotificationBeaconsbefore calling start

2016-09-16T12:33:38.315Z - info: Running on android test: 84. #testThaliPeerAction - test getters

2016-09-16T12:33:38.506Z - info: Running on android test: 85. #testThaliPeerAction - start and kill

2016-09-16T12:33:38.678Z - info: Running on android test: 86. #testThaliPeerAction - double start

2016-09-16T12:33:38.834Z - info: Running on android test: 87. #testThaliPeerAction - start after kill

2016-09-16T12:33:39.012Z - info: Running on android test: 88. #testThaliPeerAction - make sure ids are unique

2016-09-16T12:33:39.213Z - info: Running on android test: 89. Test PeerConnectionInformation basics

2016-09-16T12:33:39.377Z - info: Running on android test: 90. Test PeerDictionary basic functionality

2016-09-16T12:33:39.597Z - info: Running on android test: 91. Test PeerDictionary with multiple entries.

2016-09-16T12:33:41.758Z - info: Running on android test: 92. RESOLVED entries are removed before WAITING state entry.

2016-09-16T12:33:42.600Z - info: Running on android test: 93. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-09-16T12:33:43.320Z - info: Running on android test: 94. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-09-16T12:33:44.023Z - info: Running on android test: 95. #ThaliPeerPoolInterface - make sure that start verifies queue length

2016-09-16T12:33:44.221Z - info: Running on android test: 96. #ThaliPeerPoolInterface - bad enqueues

2016-09-16T12:33:44.390Z - info: Running on android test: 97. #ThaliPeerPoolInterface - do not allow same object type

2016-09-16T12:33:44.589Z - info: Running on android test: 98. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-09-16T12:33:44.773Z - info: Running on android test: 99. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent

2016-09-16T12:33:44.936Z - info: Running on android test: 100. #ThaliPeerPoolInterface - make sure that stop removes all actions

2016-09-16T12:33:45.301Z - info: Socket to device samsung-SM-G930F disconnected: transport close

2016-09-16T12:35:39.084Z - debug: Device presented: samsung-SM-G930F (e14b8651-951e-4c62-ba7d-a297c975d1a7) - android 6.0.1

2016-09-16T12:52:04.122Z - info: Socket to device Huawei-Nexus 6P disconnected: transport close

2016-09-16T12:52:05.633Z - info: Socket to device samsung-SM-G935F disconnected: transport close

2016-09-16T12:52:07.064Z - info: Socket to device samsung-SM-G930F disconnected: transport close


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

android : Error: Command failed: Error: Command failed: 
Trying to deploy app to android: ENU7N16516000107

Deploying to android ENU7N16516000107

App was succesfully deployed to ENU7N16516000107

Trying to deploy app to android: ce061606e320561102

Deploying to android ce061606e320561102

App was succesfully deployed to ce061606e320561102

Trying to deploy app to android: ce0616068b9f212302

Deploying to android ce0616068b9f212302

App was succesfully deployed to ce0616068b9f212302

Trying to start application ThaliTest on ENU7N16516000107

Trying to start application ThaliTest on ce061606e320561102

Trying to start application ThaliTest on ce0616068b9f212302
TIMEOUT REACHED. KILLING the APPS
child process exited with code 0
child process exited with code 0
child process exited with code 0
Android task is completed.
Android testing process has failed
 [0m


```
###Android Logs
####Node name: thali04
Console output:
```

Trying to deploy app to android: ENU7N16516000107

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Deploying to android ENU7N16516000107

App was succesfully deployed to ENU7N16516000107

Trying to deploy app to android: ce061606e320561102

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Deploying to android ce061606e320561102

App was succesfully deployed to ce061606e320561102

Trying to deploy app to android: ce0616068b9f212302

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Deploying to android ce0616068b9f212302

App was succesfully deployed to ce0616068b9f212302

Trying to start application ThaliTest on ENU7N16516000107

Trying to start application ThaliTest on ce061606e320561102

Trying to start application ThaliTest on ce0616068b9f212302
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ENU7N16516000107 app:com.test.thalitest code:0 
child process exited with code 0
Error! Unexpected exit on device ce061606e320561102 app:com.test.thalitest code:0 
child process exited with code 0
Error! Unexpected exit on device ce0616068b9f212302 app:com.test.thalitest code:0 
child process exited with code 0
Android task is completed.
```
[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/852025185ed7d1b__1031_DO_NOT_MERGE_Excluded__bad__test_files_artemjackson/thali04_Huawei-Nexus 6P.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/852025185ed7d1b__1031_DO_NOT_MERGE_Excluded__bad__test_files_artemjackson/thali04_samsung-SM-G935F.md)

[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/852025185ed7d1b__1031_DO_NOT_MERGE_Excluded__bad__test_files_artemjackson/thali04_samsung-SM-G930F.md)





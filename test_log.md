#### Test 85202518fdcd556 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-09-16T13:41:01.982Z - info: Require 0 ios devices

2016-09-16T13:41:02.001Z - info: Require 3 android devices

2016-09-16T13:41:02.057Z - info: listening on *:3000

2016-09-16T13:42:51.018Z - debug: Device presented: samsung-SM-G935F (d74d0227-35ba-4418-a7c0-2cc43b16c39b) - android 6.0.1

2016-09-16T13:42:51.463Z - debug: Device presented: samsung-SM-G930F (e551aa57-74af-41dd-97a2-093c2354262e) - android 6.0.1

2016-09-16T13:42:55.874Z - debug: Device presented: Huawei-Nexus 6P (876d59f4-66b9-430a-be3b-3fa8cd8d9ac3) - android 6.0.1

2016-09-16T13:42:55.878Z - info: All 3 android devices are present

2016-09-16T13:42:55.885Z - info: Starting unit test run on 3 android devices

2016-09-16T13:42:57.041Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-09-16T13:42:58.891Z - info: Running on android test: 2. emits incomingConnectionState

2016-09-16T13:42:59.444Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-09-16T13:42:59.746Z - info: Running on android test: 4. native server connections all up

2016-09-16T13:43:00.107Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-09-16T13:43:00.390Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-09-16T13:43:00.688Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-09-16T13:43:01.040Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-09-16T13:43:01.293Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-09-16T13:43:03.635Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-09-16T13:43:05.383Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-09-16T13:43:07.413Z - info: Running on android test: 12. closeAll can close even when connections open

2016-09-16T13:43:09.781Z - info: Running on android test: 13. closeAll with promise

2016-09-16T13:43:11.914Z - info: Running on android test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-09-16T13:43:13.827Z - info: Running on android test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-09-16T13:43:15.805Z - info: Running on android test: 16. onPeerLost calls jxcore

2016-09-16T13:43:18.181Z - info: Running on android test: 17. onPeerDiscovered calls jxcore

2016-09-16T13:43:20.707Z - info: Running on android test: 18. test defaultDirectory

2016-09-16T13:43:21.471Z - info: Running on android test: 19. test defaultAdapter

2016-09-16T13:43:21.891Z - info: Running on android test: 20. enqueue and run in order

2016-09-16T13:43:22.332Z - info: Running on android test: 21. enqueueAtTop and run backwards

2016-09-16T13:43:22.561Z - info: Running on android test: 22. mix enqueue and enqueueAtTop

2016-09-16T13:43:22.913Z - info: Running on android test: 23. queues handled independently

2016-09-16T13:43:23.287Z - info: Running on android test: 24. basic

2016-09-16T13:43:23.469Z - info: Running on android test: 25. another

2016-09-16T13:43:23.664Z - info: Running on android test: 26. can pass data in setup

2016-09-16T13:43:23.860Z - info: Running on android test: 27. #startListeningForAdvertisements should fail if start not called

2016-09-16T13:43:24.068Z - info: Running on android test: 28. #startUpdateAdvertisingAndListening should fail if start not called

2016-09-16T13:43:24.288Z - info: Running on android test: 29. should be able to call #stopListeningForAdvertisements many times

2016-09-16T13:43:24.633Z - info: Running on android test: 30. should be able to call #startListeningForAdvertisements many times

2016-09-16T13:43:26.088Z - info: Running on android test: 31. should be able to call #startUpdateAdvertisingAndListening many times

2016-09-16T13:43:27.296Z - info: Running on android test: 32. should be able to call #stopAdvertisingAndListening many times

2016-09-16T13:43:27.520Z - info: Running on android test: 33. #start should fail if called twice in a row

2016-09-16T13:43:27.758Z - info: Running on android test: 34. does not emit duplicate discoveryAdvertisingStateUpdate

2016-09-16T13:43:29.460Z - info: Running on android test: 35. does not send duplicate availability changes

2016-09-16T13:43:29.687Z - info: Running on android test: 36. can get the network status

2016-09-16T13:43:30.034Z - info: Running on android test: 37. wifi peer is marked unavailable if announcements stop

2016-09-16T13:43:32.297Z - info: Running on android test: 38. Client to server request coordinated

2016-09-16T13:45:38.336Z - warn: Failed on android test: 38. Client to server request coordinated

2016-09-16T13:45:38.337Z - info: Running on android test: 39. Test BEACONS_RETRIEVED_AND_PARSED locally

2016-09-16T13:45:38.963Z - info: Running on android test: 40. Test HTTP_BAD_RESPONSE locally

2016-09-16T13:45:39.406Z - info: Running on android test: 41. Test NETWORK_PROBLEM locally

2016-09-16T13:45:39.942Z - info: Running on android test: 42. Call the start two times

2016-09-16T13:45:40.449Z - info: Running on android test: 43. Call the kill before calling the start

2016-09-16T13:45:40.847Z - info: Running on android test: 44. Call the kill immediately after the start

2016-09-16T13:45:41.214Z - info: Running on android test: 45. Call the kill while waiting a response from the server

2016-09-16T13:45:43.631Z - info: Running on android test: 46. Test to exceed the max content size locally

2016-09-16T13:45:44.039Z - info: Running on android test: 47. Close the server socket while the client is waiting a response from the server. Local test.

2016-09-16T13:45:46.409Z - info: Running on android test: 48. Close the client socket while the client is waiting a response from the server. Local test.

2016-09-16T13:45:48.738Z - info: Running on android test: 49. #generatePreambleAndBeacons bad args

2016-09-16T13:45:48.936Z - info: Running on android test: 50. #generatePreambleAndBeacons empty keys to notify

2016-09-16T13:45:49.123Z - info: Running on android test: 51. #generatePreambleAndBeacons multiple keys to notify

2016-09-16T13:45:49.437Z - info: Running on android test: 52. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-09-16T13:45:49.640Z - info: Running on android test: 53. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-09-16T13:45:49.924Z - info: Running on android test: 54. #parseBeacons expiration out of range lower

2016-09-16T13:45:50.150Z - info: Running on android test: 55. #parseBeacons expiration out of range lower

2016-09-16T13:45:50.340Z - info: Running on android test: 56. #parseBeacons no beacons returns null

2016-09-16T13:45:50.525Z - info: Running on android test: 57. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-09-16T13:45:50.743Z - info: Running on android test: 58. #parseBeacons addressBookCallback fails decrypt

2016-09-16T13:45:51.076Z - info: Running on android test: 59. #parseBeacons addressBookCallback returns no matches

2016-09-16T13:45:51.387Z - info: Running on android test: 60. #parseBeacons addressBookCallback returns spurious match

2016-09-16T13:45:51.695Z - info: Running on android test: 61. #parseBeacons addressBookCallback returns public key

2016-09-16T13:45:52.055Z - info: Running on android test: 62. validate generatePskIdentityField

2016-09-16T13:45:52.230Z - info: Running on android test: 63. validate generatePskSecret

2016-09-16T13:45:52.485Z - info: Running on android test: 64. validate generatePskSecrets

2016-09-16T13:45:52.793Z - info: Running on android test: 65. validate generateBeaconStreamAndSecrets

2016-09-16T13:45:53.106Z - info: Running on android test: 66. Add two Peers.

2016-09-16T13:45:53.424Z - info: Running on android test: 67. TCP_NATIVE peer loses DNS

2016-09-16T13:45:53.736Z - info: Running on android test: 68. Received beacons with no values for us

2016-09-16T13:45:54.144Z - info: Running on android test: 69. Resolves an action locally

2016-09-16T13:45:54.565Z - info: Running on android test: 70. Resolves an action locally using ThaliPeerPoolDefault

2016-09-16T13:45:55.077Z - info: Running on android test: 71. Action fails because of a bad hostname.

2016-09-16T13:46:00.359Z - info: Running on android test: 72. hostaddress is removed when the action is running. 

2016-09-16T13:46:03.748Z - info: Running on android test: 73. Client to server request locally

2016-09-16T13:46:04.278Z - info: Running on android test: 74. Test ThaliPskMapCache clean and expiration

2016-09-16T13:46:05.522Z - info: Running on android test: 75. Test ThaliPskMapCache getSecret and getPublic

2016-09-16T13:46:06.816Z - info: Running on android test: 76. Test ThaliPskMapCache multiple entries

2016-09-16T13:46:09.618Z - info: Running on android test: 77. Start and stop ThaliNotificationServer

2016-09-16T13:46:09.933Z - info: Running on android test: 78. Pass an empty array to ThaliNotificationServer.start

2016-09-16T13:46:10.199Z - info: Running on android test: 79. Pass a string to ThaliNotificationServer.start

2016-09-16T13:46:10.438Z - info: Running on android test: 80. Pass an empty parameter to ThaliNotificationServer.start

2016-09-16T13:46:10.660Z - info: Running on android test: 81. Make an HTTP request to /NotificationBeacons

2016-09-16T13:46:11.054Z - info: Running on android test: 82. Make an HTTP request to /NotificationBeacons (no keys)

2016-09-16T13:46:11.315Z - info: Running on android test: 83. Make an HTTP request to /NotificationBeaconsbefore calling start

2016-09-16T13:46:11.555Z - info: Running on android test: 84. #testThaliPeerAction - test getters

2016-09-16T13:46:11.714Z - info: Running on android test: 85. #testThaliPeerAction - start and kill

2016-09-16T13:46:11.909Z - info: Running on android test: 86. #testThaliPeerAction - double start

2016-09-16T13:46:12.097Z - info: Running on android test: 87. #testThaliPeerAction - start after kill

2016-09-16T13:46:12.318Z - info: Running on android test: 88. #testThaliPeerAction - make sure ids are unique

2016-09-16T13:46:12.512Z - info: Running on android test: 89. Test PeerConnectionInformation basics

2016-09-16T13:46:12.720Z - info: Running on android test: 90. Test PeerDictionary basic functionality

2016-09-16T13:46:12.928Z - info: Running on android test: 91. Test PeerDictionary with multiple entries.

2016-09-16T13:46:15.122Z - info: Running on android test: 92. RESOLVED entries are removed before WAITING state entry.

2016-09-16T13:46:16.933Z - info: Running on android test: 93. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-09-16T13:46:17.679Z - info: Running on android test: 94. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-09-16T13:46:18.386Z - info: Running on android test: 95. Make sure peerDictionaryKey is reasonable

2016-09-16T13:46:18.569Z - info: Running on android test: 96. Make sure start works

2016-09-16T13:46:18.784Z - info: Running on android test: 97. Make sure stop works

2016-09-16T13:46:19.079Z - info: Socket to device samsung-SM-G935F disconnected: transport close

2016-09-16T13:48:13.735Z - debug: Device presented: samsung-SM-G935F (41ac3d0e-b27a-4ab7-9344-3415720e6d49) - android 6.0.1

2016-09-16T13:48:18.018Z - debug: Too many emit retries to device: samsung-SM-G935F

2016-09-16T14:04:30.038Z - info: Socket to device Huawei-Nexus 6P disconnected: transport close

2016-09-16T14:04:31.408Z - info: Socket to device samsung-SM-G935F disconnected: transport close

2016-09-16T14:04:32.851Z - info: Socket to device samsung-SM-G930F disconnected: transport close


 
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
[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/85202518fdcd556__1031_DO_NOT_MERGE_Excluded__bad__test_files_artemjackson/thali04_Huawei-Nexus 6P.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/85202518fdcd556__1031_DO_NOT_MERGE_Excluded__bad__test_files_artemjackson/thali04_samsung-SM-G935F.md)

[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/85202518fdcd556__1031_DO_NOT_MERGE_Excluded__bad__test_files_artemjackson/thali04_samsung-SM-G930F.md)





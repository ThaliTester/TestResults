#### Test 85202518d195ad1 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-09-16T15:50:19.994Z - info: Require 0 ios devices

2016-09-16T15:50:20.015Z - info: Require 3 android devices

2016-09-16T15:50:20.072Z - info: listening on *:3000

2016-09-16T15:52:04.421Z - debug: Device presented: Huawei-Nexus 6P (d37e4893-4d50-4c55-a58c-3359420700d3) - android 6.0.1

2016-09-16T15:52:05.671Z - debug: Device presented: samsung-SM-G935F (7e1d86b5-5c69-46f5-b053-76027fab52e7) - android 6.0.1

2016-09-16T15:52:06.361Z - debug: Device presented: samsung-SM-G930F (3f5b8ceb-3fc5-492d-ad5a-d1a0fd44b11c) - android 6.0.1

2016-09-16T15:52:06.362Z - info: All 3 android devices are present

2016-09-16T15:52:06.369Z - info: Starting unit test run on 3 android devices

2016-09-16T15:52:06.890Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-09-16T15:52:07.746Z - info: Running on android test: 2. emits incomingConnectionState

2016-09-16T15:52:08.609Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-09-16T15:52:09.178Z - info: Running on android test: 4. native server connections all up

2016-09-16T15:52:09.619Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-09-16T15:52:09.919Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-09-16T15:52:10.167Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-09-16T15:52:10.511Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-09-16T15:52:10.765Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-09-16T15:52:12.390Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-09-16T15:52:14.188Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-09-16T15:52:16.228Z - info: Running on android test: 12. closeAll can close even when connections open

2016-09-16T15:52:17.542Z - info: Running on android test: 13. closeAll with promise

2016-09-16T15:52:18.344Z - info: Running on android test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-09-16T15:52:18.667Z - info: Running on android test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-09-16T15:52:18.953Z - info: Running on android test: 16. onPeerLost calls jxcore

2016-09-16T15:52:21.205Z - info: Running on android test: 17. onPeerDiscovered calls jxcore

2016-09-16T15:52:23.541Z - info: Running on android test: 18. test defaultDirectory

2016-09-16T15:52:23.800Z - info: Running on android test: 19. test defaultAdapter

2016-09-16T15:52:24.216Z - info: Running on android test: 20. enqueue and run in order

2016-09-16T15:52:24.686Z - info: Running on android test: 21. enqueueAtTop and run backwards

2016-09-16T15:52:24.887Z - info: Running on android test: 22. mix enqueue and enqueueAtTop

2016-09-16T15:52:25.207Z - info: Running on android test: 23. queues handled independently

2016-09-16T15:52:25.547Z - info: Running on android test: 24. basic

2016-09-16T15:52:25.745Z - info: Running on android test: 25. another

2016-09-16T15:52:25.915Z - info: Running on android test: 26. can pass data in setup

2016-09-16T15:52:26.083Z - info: Running on android test: 27. #startListeningForAdvertisements should fail if start not called

2016-09-16T15:52:26.269Z - info: Running on android test: 28. #startUpdateAdvertisingAndListening should fail if start not called

2016-09-16T15:52:26.447Z - info: Running on android test: 29. should be able to call #stopListeningForAdvertisements many times

2016-09-16T15:52:26.787Z - info: Running on android test: 30. should be able to call #startListeningForAdvertisements many times

2016-09-16T15:52:28.263Z - info: Running on android test: 31. should be able to call #startUpdateAdvertisingAndListening many times

2016-09-16T15:52:29.340Z - info: Running on android test: 32. should be able to call #stopAdvertisingAndListening many times

2016-09-16T15:52:29.541Z - info: Running on android test: 33. #start should fail if called twice in a row

2016-09-16T15:52:29.801Z - info: Running on android test: 34. does not emit duplicate discoveryAdvertisingStateUpdate

2016-09-16T15:52:31.511Z - info: Running on android test: 35. does not send duplicate availability changes

2016-09-16T15:52:31.850Z - info: Running on android test: 36. can get the network status

2016-09-16T15:52:32.121Z - info: Running on android test: 37. wifi peer is marked unavailable if announcements stop

2016-09-16T15:52:34.359Z - info: Running on android test: 38. Client to server request coordinated

2016-09-16T15:54:40.419Z - warn: Failed on android test: 38. Client to server request coordinated

2016-09-16T15:54:40.420Z - info: Running on android test: 39. Test BEACONS_RETRIEVED_AND_PARSED locally

2016-09-16T15:54:42.586Z - info: Running on android test: 40. Test HTTP_BAD_RESPONSE locally

2016-09-16T15:54:44.420Z - info: Running on android test: 41. Test NETWORK_PROBLEM locally

2016-09-16T15:54:46.458Z - info: Running on android test: 42. Call the start two times

2016-09-16T15:54:48.413Z - info: Running on android test: 43. Call the kill before calling the start

2016-09-16T15:54:50.462Z - info: Running on android test: 44. Call the kill immediately after the start

2016-09-16T15:54:52.299Z - info: Running on android test: 45. Call the kill while waiting a response from the server

2016-09-16T15:54:55.343Z - info: Running on android test: 46. Test to exceed the max content size locally

2016-09-16T15:54:55.777Z - info: Running on android test: 47. Close the server socket while the client is waiting a response from the server. Local test.

2016-09-16T15:54:58.135Z - info: Running on android test: 48. Close the client socket while the client is waiting a response from the server. Local test.

2016-09-16T15:55:00.457Z - info: Running on android test: 49. #generatePreambleAndBeacons bad args

2016-09-16T15:55:00.679Z - info: Running on android test: 50. #generatePreambleAndBeacons empty keys to notify

2016-09-16T15:55:00.885Z - info: Running on android test: 51. #generatePreambleAndBeacons multiple keys to notify

2016-09-16T15:55:01.166Z - info: Running on android test: 52. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-09-16T15:55:01.405Z - info: Running on android test: 53. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-09-16T15:55:01.593Z - info: Running on android test: 54. #parseBeacons expiration out of range lower

2016-09-16T15:55:01.879Z - info: Running on android test: 55. #parseBeacons expiration out of range lower

2016-09-16T15:55:02.109Z - info: Running on android test: 56. #parseBeacons no beacons returns null

2016-09-16T15:55:02.329Z - info: Running on android test: 57. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-09-16T15:55:02.537Z - info: Running on android test: 58. #parseBeacons addressBookCallback fails decrypt

2016-09-16T15:55:02.833Z - info: Running on android test: 59. #parseBeacons addressBookCallback returns no matches

2016-09-16T15:55:03.156Z - info: Running on android test: 60. #parseBeacons addressBookCallback returns spurious match

2016-09-16T15:55:03.478Z - info: Running on android test: 61. #parseBeacons addressBookCallback returns public key

2016-09-16T15:55:03.777Z - info: Running on android test: 62. validate generatePskIdentityField

2016-09-16T15:55:04.000Z - info: Running on android test: 63. validate generatePskSecret

2016-09-16T15:55:04.199Z - info: Running on android test: 64. validate generatePskSecrets

2016-09-16T15:55:04.501Z - info: Running on android test: 65. validate generateBeaconStreamAndSecrets

2016-09-16T15:55:04.809Z - info: Running on android test: 66. Add two Peers.

2016-09-16T15:55:05.128Z - info: Running on android test: 67. TCP_NATIVE peer loses DNS

2016-09-16T15:55:05.443Z - info: Running on android test: 68. Received beacons with no values for us

2016-09-16T15:55:05.886Z - info: Running on android test: 69. Resolves an action locally

2016-09-16T15:55:06.293Z - info: Running on android test: 70. Resolves an action locally using ThaliPeerPoolDefault

2016-09-16T15:55:06.767Z - info: Running on android test: 71. Action fails because of a bad hostname.

2016-09-16T15:55:12.094Z - info: Running on android test: 72. hostaddress is removed when the action is running. 

2016-09-16T15:55:14.471Z - info: Running on android test: 73. Client to server request locally

2016-09-16T15:55:14.903Z - info: Running on android test: 74. Test ThaliPskMapCache clean and expiration

2016-09-16T15:55:16.135Z - info: Running on android test: 75. Test ThaliPskMapCache getSecret and getPublic

2016-09-16T15:55:17.460Z - info: Running on android test: 76. Test ThaliPskMapCache multiple entries

2016-09-16T15:55:20.274Z - info: Running on android test: 77. Start and stop ThaliNotificationServer

2016-09-16T15:55:20.590Z - info: Running on android test: 78. Pass an empty array to ThaliNotificationServer.start

2016-09-16T15:55:20.874Z - info: Running on android test: 79. Pass a string to ThaliNotificationServer.start

2016-09-16T15:55:21.129Z - info: Running on android test: 80. Pass an empty parameter to ThaliNotificationServer.start

2016-09-16T15:55:21.357Z - info: Running on android test: 81. Make an HTTP request to /NotificationBeacons

2016-09-16T15:55:21.740Z - info: Running on android test: 82. Make an HTTP request to /NotificationBeacons (no keys)

2016-09-16T15:55:21.979Z - info: Running on android test: 83. Make an HTTP request to /NotificationBeaconsbefore calling start

2016-09-16T15:55:22.285Z - info: Running on android test: 84. #testThaliPeerAction - test getters

2016-09-16T15:55:22.457Z - info: Running on android test: 85. #testThaliPeerAction - start and kill

2016-09-16T15:55:22.653Z - info: Running on android test: 86. #testThaliPeerAction - double start

2016-09-16T15:55:22.829Z - info: Running on android test: 87. #testThaliPeerAction - start after kill

2016-09-16T15:55:23.001Z - info: Running on android test: 88. #testThaliPeerAction - make sure ids are unique

2016-09-16T15:55:23.204Z - info: Running on android test: 89. Test PeerConnectionInformation basics

2016-09-16T15:55:23.376Z - info: Running on android test: 90. Test PeerDictionary basic functionality

2016-09-16T15:55:23.628Z - info: Running on android test: 91. Test PeerDictionary with multiple entries.

2016-09-16T15:55:25.794Z - info: Running on android test: 92. RESOLVED entries are removed before WAITING state entry.

2016-09-16T15:55:26.591Z - info: Running on android test: 93. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-09-16T15:55:27.300Z - info: Running on android test: 94. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-09-16T15:55:28.020Z - info: Running on android test: 95. compareBufferArrays

2016-09-16T15:55:28.217Z - info: Running on android test: 96. Call start twice and get error

2016-09-16T15:55:28.401Z - info: Running on android test: 97. Start and make sure it runs

2016-09-16T15:55:28.568Z - info: Running on android test: 98. Make sure getTimeWhenRun is right after start

2016-09-16T15:55:28.738Z - info: Running on android test: 99. Make sure getTimeWhenRun is -1 after function is called

2016-09-16T15:55:28.934Z - info: Running on android test: 100. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-09-16T15:55:29.141Z - info: Running on android test: 101. Test TransientState

2016-09-16T15:55:29.306Z - info: Running on android test: 102. No peers and empty database

2016-09-16T15:55:29.641Z - info: Running on android test: 103. One peer and empty DB

2016-09-16T15:55:30.009Z - info: Running on android test: 104. One peer with _Local set behind current seq

2016-09-16T15:55:30.406Z - info: Running on android test: 105. One peer with _Local set equal to current seq

2016-09-16T15:55:30.851Z - info: Socket to device samsung-SM-G930F disconnected: transport close

2016-09-16T15:57:24.731Z - debug: Device presented: samsung-SM-G930F (d1a78830-0e06-4af6-ad59-540a3b73f2ea) - android 6.0.1

2016-09-16T16:13:43.773Z - info: Socket to device Huawei-Nexus 6P disconnected: transport close

2016-09-16T16:13:45.184Z - info: Socket to device samsung-SM-G935F disconnected: transport close

2016-09-16T16:13:46.599Z - info: Socket to device samsung-SM-G930F disconnected: transport close


 
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
[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/85202518d195ad1__1031_DO_NOT_MERGE_Excluded__bad__test_files_artemjackson/thali04_Huawei-Nexus 6P.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/85202518d195ad1__1031_DO_NOT_MERGE_Excluded__bad__test_files_artemjackson/thali04_samsung-SM-G935F.md)

[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/85202518d195ad1__1031_DO_NOT_MERGE_Excluded__bad__test_files_artemjackson/thali04_samsung-SM-G930F.md)





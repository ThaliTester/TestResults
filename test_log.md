#### Test 852025183d04d1f Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-09-19T12:09:36.853Z - info: Require 0 ios devices

2016-09-19T12:09:36.872Z - info: Require 3 android devices

2016-09-19T12:09:36.933Z - info: listening on *:3000

2016-09-19T12:11:26.083Z - debug: Device presented: samsung-SM-G930F (acce3f98-b4d9-4e8f-b363-4c3da0d91bc2) - android 6.0.1

2016-09-19T12:11:26.924Z - debug: Device presented: samsung-SM-G935F (e091e74c-2749-43b6-b4e2-7652ce26cebf) - android 6.0.1

2016-09-19T12:11:30.984Z - debug: Device presented: Huawei-Nexus 6P (4ac978e4-112e-4769-98b8-ab90d0d9ebc6) - android 6.0.1

2016-09-19T12:11:30.986Z - info: All 3 android devices are present

2016-09-19T12:11:30.993Z - info: Starting unit test run on 3 android devices

2016-09-19T12:11:32.116Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-09-19T12:11:32.537Z - info: Running on android test: 2. emits incomingConnectionState

2016-09-19T12:11:32.962Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-09-19T12:11:33.313Z - info: Running on android test: 4. native server connections all up

2016-09-19T12:11:33.662Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-09-19T12:11:34.033Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-09-19T12:11:34.328Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-09-19T12:11:34.714Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-09-19T12:11:35.001Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-09-19T12:11:37.490Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-09-19T12:11:39.648Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-09-19T12:11:41.474Z - info: Running on android test: 12. closeAll can close even when connections open

2016-09-19T12:11:43.411Z - info: Running on android test: 13. closeAll with promise

2016-09-19T12:11:43.849Z - info: Running on android test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-09-19T12:11:44.188Z - info: Running on android test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-09-19T12:11:44.475Z - info: Running on android test: 16. onPeerLost calls jxcore

2016-09-19T12:11:46.785Z - info: Running on android test: 17. onPeerDiscovered calls jxcore

2016-09-19T12:11:49.072Z - info: Running on android test: 18. test defaultDirectory

2016-09-19T12:11:49.348Z - info: Running on android test: 19. test defaultAdapter

2016-09-19T12:11:49.756Z - info: Running on android test: 20. enqueue and run in order

2016-09-19T12:11:50.267Z - info: Running on android test: 21. enqueueAtTop and run backwards

2016-09-19T12:11:50.468Z - info: Running on android test: 22. mix enqueue and enqueueAtTop

2016-09-19T12:11:50.801Z - info: Running on android test: 23. queues handled independently

2016-09-19T12:11:51.271Z - info: Running on android test: 24. basic

2016-09-19T12:11:51.480Z - info: Running on android test: 25. another

2016-09-19T12:11:51.659Z - info: Running on android test: 26. can pass data in setup

2016-09-19T12:11:51.851Z - info: Running on android test: 27. #startListeningForAdvertisements should fail if start not called

2016-09-19T12:11:52.085Z - info: Running on android test: 28. #startUpdateAdvertisingAndListening should fail if start not called

2016-09-19T12:11:52.259Z - info: Running on android test: 29. should be able to call #stopListeningForAdvertisements many times

2016-09-19T12:11:52.627Z - info: Running on android test: 30. should be able to call #startListeningForAdvertisements many times

2016-09-19T12:11:54.061Z - info: Running on android test: 31. should be able to call #startUpdateAdvertisingAndListening many times

2016-09-19T12:11:55.153Z - info: Running on android test: 32. should be able to call #stopAdvertisingAndListening many times

2016-09-19T12:11:55.440Z - info: Running on android test: 33. #start should fail if called twice in a row

2016-09-19T12:11:55.729Z - info: Running on android test: 34. does not emit duplicate discoveryAdvertisingStateUpdate

2016-09-19T12:11:57.487Z - info: Running on android test: 35. does not send duplicate availability changes

2016-09-19T12:11:57.808Z - info: Running on android test: 36. can get the network status

2016-09-19T12:11:58.066Z - info: Running on android test: 37. wifi peer is marked unavailable if announcements stop

2016-09-19T12:12:00.315Z - info: Running on android test: 38. Client to server request coordinated

2016-09-19T12:14:06.327Z - warn: Failed on android test: 38. Client to server request coordinated

2016-09-19T12:14:06.328Z - info: Running on android test: 39. Test BEACONS_RETRIEVED_AND_PARSED locally

2016-09-19T12:14:06.827Z - info: Running on android test: 40. Test HTTP_BAD_RESPONSE locally

2016-09-19T12:14:07.279Z - info: Running on android test: 41. Test NETWORK_PROBLEM locally

2016-09-19T12:14:07.675Z - info: Running on android test: 42. Call the start two times

2016-09-19T12:14:08.158Z - info: Running on android test: 43. Call the kill before calling the start

2016-09-19T12:14:08.521Z - info: Running on android test: 44. Call the kill immediately after the start

2016-09-19T12:14:08.878Z - info: Running on android test: 45. Call the kill while waiting a response from the server

2016-09-19T12:14:11.328Z - info: Running on android test: 46. Test to exceed the max content size locally

2016-09-19T12:14:11.740Z - info: Running on android test: 47. Close the server socket while the client is waiting a response from the server. Local test.

2016-09-19T12:14:14.960Z - info: Running on android test: 48. Close the client socket while the client is waiting a response from the server. Local test.

2016-09-19T12:14:17.325Z - info: Running on android test: 49. #generatePreambleAndBeacons bad args

2016-09-19T12:14:17.532Z - info: Running on android test: 50. #generatePreambleAndBeacons empty keys to notify

2016-09-19T12:14:17.758Z - info: Running on android test: 51. #generatePreambleAndBeacons multiple keys to notify

2016-09-19T12:14:18.080Z - info: Running on android test: 52. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-09-19T12:14:18.271Z - info: Running on android test: 53. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-09-19T12:14:18.496Z - info: Running on android test: 54. #parseBeacons expiration out of range lower

2016-09-19T12:14:18.729Z - info: Running on android test: 55. #parseBeacons expiration out of range lower

2016-09-19T12:14:18.937Z - info: Running on android test: 56. #parseBeacons no beacons returns null

2016-09-19T12:14:19.159Z - info: Running on android test: 57. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-09-19T12:14:19.355Z - info: Running on android test: 58. #parseBeacons addressBookCallback fails decrypt

2016-09-19T12:14:19.772Z - info: Running on android test: 59. #parseBeacons addressBookCallback returns no matches

2016-09-19T12:14:20.084Z - info: Running on android test: 60. #parseBeacons addressBookCallback returns spurious match

2016-09-19T12:14:20.449Z - info: Running on android test: 61. #parseBeacons addressBookCallback returns public key

2016-09-19T12:14:20.803Z - info: Running on android test: 62. validate generatePskIdentityField

2016-09-19T12:14:21.047Z - info: Running on android test: 63. validate generatePskSecret

2016-09-19T12:14:21.299Z - info: Running on android test: 64. validate generatePskSecrets

2016-09-19T12:14:21.615Z - info: Running on android test: 65. validate generateBeaconStreamAndSecrets

2016-09-19T12:14:21.945Z - info: Running on android test: 66. Add two Peers.

2016-09-19T12:14:22.338Z - info: Running on android test: 67. TCP_NATIVE peer loses DNS

2016-09-19T12:14:22.623Z - info: Running on android test: 68. Received beacons with no values for us

2016-09-19T12:14:23.007Z - info: Running on android test: 69. Resolves an action locally

2016-09-19T12:14:23.433Z - info: Running on android test: 70. Resolves an action locally using ThaliPeerPoolDefault

2016-09-19T12:14:23.871Z - info: Running on android test: 71. Action fails because of a bad hostname.

2016-09-19T12:14:29.183Z - info: Running on android test: 72. hostaddress is removed when the action is running. 

2016-09-19T12:14:31.518Z - info: Running on android test: 73. Client to server request locally

2016-09-19T12:14:31.903Z - info: Running on android test: 74. Test ThaliPskMapCache clean and expiration

2016-09-19T12:14:33.193Z - info: Running on android test: 75. Test ThaliPskMapCache getSecret and getPublic

2016-09-19T12:14:34.504Z - info: Running on android test: 76. Test ThaliPskMapCache multiple entries

2016-09-19T12:14:37.375Z - info: Running on android test: 77. Start and stop ThaliNotificationServer

2016-09-19T12:14:37.675Z - info: Running on android test: 78. Pass an empty array to ThaliNotificationServer.start

2016-09-19T12:14:37.972Z - info: Running on android test: 79. Pass a string to ThaliNotificationServer.start

2016-09-19T12:14:38.203Z - info: Running on android test: 80. Pass an empty parameter to ThaliNotificationServer.start

2016-09-19T12:14:38.439Z - info: Running on android test: 81. Make an HTTP request to /NotificationBeacons

2016-09-19T12:14:38.884Z - info: Running on android test: 82. Make an HTTP request to /NotificationBeacons (no keys)

2016-09-19T12:14:39.129Z - info: Running on android test: 83. Make an HTTP request to /NotificationBeaconsbefore calling start

2016-09-19T12:14:39.384Z - info: Running on android test: 84. #testThaliPeerAction - test getters

2016-09-19T12:14:39.586Z - info: Running on android test: 85. #testThaliPeerAction - start and kill

2016-09-19T12:14:39.851Z - info: Running on android test: 86. #testThaliPeerAction - double start

2016-09-19T12:14:40.039Z - info: Running on android test: 87. #testThaliPeerAction - start after kill

2016-09-19T12:14:40.273Z - info: Running on android test: 88. #testThaliPeerAction - make sure ids are unique

2016-09-19T12:14:40.519Z - info: Running on android test: 89. Test PeerConnectionInformation basics

2016-09-19T12:14:40.711Z - info: Running on android test: 90. Test PeerDictionary basic functionality

2016-09-19T12:14:40.920Z - info: Running on android test: 91. Test PeerDictionary with multiple entries.

2016-09-19T12:14:43.141Z - info: Running on android test: 92. RESOLVED entries are removed before WAITING state entry.

2016-09-19T12:14:43.889Z - info: Running on android test: 93. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-09-19T12:14:44.570Z - info: Running on android test: 94. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-09-19T12:14:45.287Z - info: Running on android test: 95. compareBufferArrays

2016-09-19T12:14:45.496Z - info: Running on android test: 96. Call start twice and get error

2016-09-19T12:14:45.765Z - info: Running on android test: 97. Start and make sure it runs

2016-09-19T12:14:45.976Z - info: Running on android test: 98. Make sure getTimeWhenRun is right after start

2016-09-19T12:14:46.149Z - info: Running on android test: 99. Make sure getTimeWhenRun is -1 after function is called

2016-09-19T12:14:46.344Z - info: Running on android test: 100. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-09-19T12:14:46.551Z - info: Running on android test: 101. Test TransientState

2016-09-19T12:14:46.783Z - info: Running on android test: 102. No peers and empty database

2016-09-19T12:14:47.159Z - info: Running on android test: 103. One peer and empty DB

2016-09-19T12:14:47.503Z - info: Running on android test: 104. One peer with _Local set behind current seq

2016-09-19T12:14:47.871Z - info: Running on android test: 105. One peer with _Local set equal to current seq

2016-09-19T12:14:48.247Z - info: Running on android test: 106. One peer with _Local set ahead of current seq (and no this should not happen)

2016-09-19T12:14:48.603Z - info: Running on android test: 107. Three peers, one not in DB, one behind and one ahead

2016-09-19T12:14:49.085Z - info: Running on android test: 108. More than maximum peers, make sure we only send maximum allowed

2016-09-19T12:14:49.779Z - info: Running on android test: 109. two peers with empty DB, update the doc

2016-09-19T12:14:50.237Z - info: Running on android test: 110. add doc and make sure tokens refresh when they expire

2016-09-19T12:14:50.913Z - info: Running on android test: 111. start and stop and start and stop

2016-09-19T12:14:51.270Z - info: Running on android test: 112. two identical starts in a row

2016-09-19T12:14:51.642Z - info: Running on android test: 113. two different starts in a row

2016-09-19T12:14:51.957Z - info: Running on android test: 114. two stops and a start and two stops

2016-09-19T12:14:52.296Z - info: Running on android test: 115. we properly enqueue requests so no then needed

2016-09-19T12:14:52.677Z - info: Running on android test: 116. test calculateSeqPointKeyId

2016-09-19T12:14:52.930Z - info: Running on android test: 117. can create servers manager

2016-09-19T12:14:53.117Z - info: Running on android test: 118. calling stop without start causes error

2016-09-19T12:14:53.298Z - info: Running on android test: 119. can start/stop servers manager

2016-09-19T12:14:53.464Z - info: Running on android test: 120. starting twice resolves with listening port

2016-09-19T12:14:53.980Z - info: Running on android test: 121. terminateIncomingConnection will terminate a connection

2016-09-19T12:14:56.003Z - info: Running on android test: 122. terminate an Outgoing connection will terminate the server

2016-09-19T12:14:57.848Z - info: Running on android test: 123. terminate an Outgoing connection with wrong arguments is not harmful

2016-09-19T12:15:00.025Z - info: Running on android test: 124. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-09-19T12:15:01.318Z - info: Running on android test: 125. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-09-19T12:15:01.598Z - info: Running on android test: 126. messages with invalid location or USN should be ignored

2016-09-19T12:15:01.818Z - info: Running on android test: 127. verify that Thali-specific messages are filtered correctly

2016-09-19T12:15:02.010Z - info: Running on android test: 128. #startListeningForAdvertisements should fail if start not called

2016-09-19T12:15:02.226Z - info: Running on android test: 129. #startUpdateAdvertisingAndListening should fail if start not called

2016-09-19T12:15:02.455Z - info: Running on android test: 130. #start should fail if called twice in a row

2016-09-19T12:15:02.664Z - info: Running on android test: 131. should not be started after stop is called

2016-09-19T12:15:02.862Z - info: Running on android test: 132. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-09-19T12:15:03.056Z - info: Running on android test: 133. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-09-19T12:15:03.291Z - info: Running on android test: 134. #startUpdateAdvertisingAndListening should start hosting given router object

2016-09-19T12:15:03.568Z - info: Socket to device samsung-SM-G935F disconnected: transport close

2016-09-19T12:16:57.114Z - debug: Device presented: samsung-SM-G935F (dfeb8a40-3a26-4790-9cbd-3cd171260a9f) - android 6.0.1

2016-09-19T12:17:02.465Z - debug: Too many emit retries to device: samsung-SM-G935F

2016-09-19T12:33:05.317Z - info: Socket to device Huawei-Nexus 6P disconnected: transport close

2016-09-19T12:33:06.731Z - info: Socket to device samsung-SM-G935F disconnected: transport close

2016-09-19T12:33:08.169Z - info: Socket to device samsung-SM-G930F disconnected: transport close


 
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
child process exited with code null
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
Error! Unexpected exit on device ce061606e320561102 app:com.test.thalitest code:null 
child process exited with code null
Error! Unexpected exit on device ce0616068b9f212302 app:com.test.thalitest code:0 
child process exited with code 0
Android task is completed.
```
[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/852025183d04d1f__1031_DO_NOT_MERGE_Excluded__bad__test_files_artemjackson/thali04_Huawei-Nexus 6P.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/852025183d04d1f__1031_DO_NOT_MERGE_Excluded__bad__test_files_artemjackson/thali04_samsung-SM-G935F.md)

[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/852025183d04d1f__1031_DO_NOT_MERGE_Excluded__bad__test_files_artemjackson/thali04_samsung-SM-G930F.md)





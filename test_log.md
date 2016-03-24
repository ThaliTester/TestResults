#### Test 639107048b8fbc2 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-03-24T16:38:42.575Z - info: listening on *:3000

2016-03-24T16:38:43.944Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:0

2016-03-24T16:38:44.859Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:1

2016-03-24T16:38:46.906Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:2

2016-03-24T16:38:46.907Z - info: Required number of ios devices presented (3)

2016-03-24T16:38:46.912Z - info: Starting unit test run for platform: ios

2016-03-24T16:38:47.737Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-24T16:38:47.903Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:3

2016-03-24T16:38:48.251Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-24T16:38:48.642Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-24T16:38:49.018Z - info: Running on ios test: 4. native server connections all up

2016-03-24T16:38:49.457Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-24T16:38:49.770Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:4

2016-03-24T16:38:49.908Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-24T16:38:50.290Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-24T16:38:50.685Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-24T16:38:51.069Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-24T16:38:54.546Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-24T16:38:55.252Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-24T16:38:55.784Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-24T16:38:56.139Z - info: Running on ios test: 13. closeAll with promise

2016-03-24T16:38:56.430Z - info: Running on ios test: 14. multiplex can send data

2016-03-24T16:38:56.744Z - info: Running on ios test: 15. enqueue and run in order

2016-03-24T16:38:57.265Z - info: Running on ios test: 16. enqueueAtTop and run backwards

2016-03-24T16:38:57.795Z - info: Running on ios test: 17. mix enqueue and enqueueAtTop

2016-03-24T16:38:58.235Z - info: Running on ios test: 18. queues handled independently

2016-03-24T16:38:58.663Z - info: Running on ios test: 19. basic

2016-03-24T16:38:58.987Z - info: Running on ios test: 20. another

2016-03-24T16:38:59.269Z - info: Running on ios test: 21. can pass data in setup

2016-03-24T16:38:59.614Z - info: Running on ios test: 22. #startListeningForAdvertisements should fail if start not called

2016-03-24T16:39:00.020Z - info: Running on ios test: 23. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-24T16:39:00.329Z - info: Running on ios test: 24. should be able to call #stopListeningForAdvertisements many times

2016-03-24T16:39:00.771Z - info: Running on ios test: 25. should be able to call #startListeningForAdvertisements many times

2016-03-24T16:39:04.274Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:5

2016-03-24T16:39:04.275Z - info: Required number of android devices presented (3)

2016-03-24T16:39:04.276Z - info: Starting unit test run for platform: android

2016-03-24T16:39:05.167Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-24T16:39:06.282Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-24T16:39:06.746Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-24T16:39:07.378Z - info: Running on android test: 4. native server connections all up

2016-03-24T16:39:07.956Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-24T16:39:08.442Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-24T16:39:08.994Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-24T16:39:09.486Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-24T16:39:09.920Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-24T16:39:10.790Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-24T16:39:11.252Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-24T16:39:11.860Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-24T16:39:12.320Z - info: Running on android test: 13. closeAll with promise

2016-03-24T16:39:12.738Z - info: Running on android test: 14. multiplex can send data

2016-03-24T16:39:13.196Z - info: Running on android test: 15. enqueue and run in order

2016-03-24T16:39:13.913Z - info: Running on android test: 16. enqueueAtTop and run backwards

2016-03-24T16:39:14.408Z - info: Running on android test: 17. mix enqueue and enqueueAtTop

2016-03-24T16:39:15.447Z - info: Running on android test: 18. queues handled independently

2016-03-24T16:39:15.817Z - info: Running on android test: 19. basic

2016-03-24T16:39:16.155Z - info: Running on android test: 20. another

2016-03-24T16:39:16.489Z - info: Running on android test: 21. can pass data in setup

2016-03-24T16:39:16.925Z - info: Running on android test: 22. #startListeningForAdvertisements should fail if start not called

2016-03-24T16:39:17.353Z - info: Running on android test: 23. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-24T16:39:17.786Z - info: Running on android test: 24. should be able to call #stopListeningForAdvertisements many times

2016-03-24T16:39:18.245Z - info: Running on android test: 25. should be able to call #startListeningForAdvertisements many times

2016-03-24T16:39:18.876Z - info: Running on android test: 26. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-24T16:39:20.125Z - info: Running on android test: 27. should be able to call #stopAdvertisingAndListening many times

2016-03-24T16:39:20.568Z - info: Running on android test: 28. #start should fail if called twice in a row

2016-03-24T16:39:20.977Z - info: Running on android test: 29. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-24T16:39:21.897Z - info: Running on android test: 30. does not send duplicate availability changes

2016-03-24T16:39:22.601Z - info: Running on android test: 31. can get the network status

2016-03-24T16:39:23.091Z - info: Running on android test: 32. wifi peer is marked unavailable if announcements stop

2016-03-24T16:39:25.728Z - info: Running on android test: 33. Can call start/stopListeningForAdvertisements

2016-03-24T16:39:26.291Z - info: Running on android test: 34. Calling startListeningForAdvertisements twice is NOT an error

2016-03-24T16:39:27.891Z - info: Running on android test: 35. Can call start/stopUpdateAdvertisingAndListening

2016-03-24T16:39:28.873Z - info: Running on android test: 36. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-24T16:39:29.613Z - info: Running on android test: 37. peerAvailabilityChange is called

2016-03-24T16:39:31.725Z - info: Running on android test: 38. Can connect to a remote peer

2016-03-24T16:39:57.322Z - info: Running on android test: 39. Can shift large amounts of data

2016-03-24T16:40:26.027Z - debug: Socket disconnected: ping timeout 1 (Apple-Iphone5s-1)

2016-03-24T16:40:34.406Z - info: Running on android test: 40. #startListeningForAdvertisements should fail if start not called

2016-03-24T16:40:36.760Z - info: Running on android test: 41. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-24T16:40:37.430Z - info: Running on android test: 42. should be able to call #stopListeningForAdvertisements many times

2016-03-24T16:40:37.980Z - info: Running on android test: 43. should be able to call #startListeningForAdvertisements many times

2016-03-24T16:40:38.640Z - info: Running on android test: 44. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-24T16:40:39.481Z - info: Running on android test: 45. should be able to call #stopAdvertisingAndListening many times

2016-03-24T16:40:39.898Z - info: Running on android test: 46. can get the network status before starting

2016-03-24T16:40:40.274Z - info: Running on android test: 47. error returned with bad router

2016-03-24T16:40:40.727Z - info: Running on android test: 48. all services are stopped when we call stop

2016-03-24T16:40:41.753Z - info: Running on android test: 49. make sure terminateConnection is properly hooked up

2016-03-24T16:40:42.314Z - info: Running on android test: 50. make sure terminateListener is properly hooked up

2016-03-24T16:40:43.043Z - info: Running on android test: 51. make sure we actually call kill connections properly

2016-03-24T16:40:43.486Z - info: Running on android test: 52. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received

2016-03-24T16:40:44.220Z - info: Running on android test: 53. We repeat failedConnection event when we get it from thaliTcpServersManager

2016-03-24T16:40:44.851Z - info: Running on android test: 54. we successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-24T16:40:45.863Z - warn: Failed on android test: 54. we successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-24T16:40:45.864Z - info: Running on android test: 55. can do HTTP requests between peers

2016-03-24T16:41:09.726Z - warn: Failed on android test: 55. can do HTTP requests between peers

2016-03-24T16:41:09.727Z - info: Running on android test: 56. Test BEACONS_RETRIEVED_AND_PARSED locally

2016-03-24T16:41:13.942Z - info: Running on android test: 57. Test HTTP_BAD_RESPONSE locally

2016-03-24T16:41:24.891Z - debug: Socket disconnected: transport close 2 (Apple-Iphone6-1)

2016-03-24T16:41:57.679Z - info: Running on android test: 58. Test NETWORK_PROBLEM locally

2016-03-24T16:42:21.001Z - info: Running on android test: 59. Test timeout locally

2016-03-24T16:42:40.334Z - debug: Socket disconnected: transport close 6 (NOT YET SET)

2016-03-24T16:43:22.259Z - info: Running on android test: 60. Call the start two times

2016-03-24T16:43:22.821Z - info: Running on android test: 61. Call the kill before calling the start

2016-03-24T16:43:23.330Z - info: Running on android test: 62. Call the kill immediately after the start

2016-03-24T16:43:23.851Z - info: Running on android test: 63. Call the kill while waiting a response from the server

2016-03-24T16:43:27.086Z - info: Running on android test: 64. Test to exceed the max content size locally

2016-03-24T16:43:27.570Z - info: Running on android test: 65. Close the server socket while the client is waiting a response from the server. Local test.

2016-03-24T16:43:30.197Z - info: Running on android test: 66. Close the client socket while the client is waiting a response from the server. Local test.

2016-03-24T16:43:32.755Z - info: Running on android test: 67. #generatePreambleAndBeacons bad args

2016-03-24T16:43:33.277Z - info: Running on android test: 68. #generatePreambleAndBeacons empty keys to notify

2016-03-24T16:43:33.722Z - info: Running on android test: 69. #generatePreambleAndBeacons multiple keys to notify

2016-03-24T16:43:34.301Z - info: Running on android test: 70. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-24T16:43:34.646Z - info: Running on android test: 71. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-24T16:43:35.035Z - info: Running on android test: 72. #parseBeacons expiration out of range lower

2016-03-24T16:43:35.466Z - info: Running on android test: 73. #parseBeacons expiration out of range lower

2016-03-24T16:43:35.490Z - debug: Socket disconnected: transport close 7 (NOT YET SET)

2016-03-24T16:43:35.914Z - info: Running on android test: 74. #parseBeacons no beacons returns null

2016-03-24T16:43:36.321Z - info: Running on android test: 75. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-24T16:43:36.704Z - info: Running on android test: 76. #parseBeacons addressBookCallback fails decrypt

2016-03-24T16:43:37.395Z - info: Running on android test: 77. #parseBeacons addressBookCallback returns no matches

2016-03-24T16:43:42.705Z - info: Running on android test: 78. #parseBeacons addressBookCallback returns spurious match

2016-03-24T16:43:44.635Z - info: Running on android test: 79. #parseBeacons addressBookCallback returns public key

2016-03-24T16:43:45.148Z - info: Running on android test: 80. validate generatePskIdentityField

2016-03-24T16:43:45.640Z - info: Running on android test: 81. validate generatePskSecret

2016-03-24T16:43:46.120Z - info: Running on android test: 82. Add two Peers.

2016-03-24T16:43:46.667Z - info: Running on android test: 83. TCP_NATIVE peer loses DNS

2016-03-24T16:43:47.189Z - info: Running on android test: 84. Resolves an action locally

2016-03-24T16:43:47.936Z - info: Running on android test: 85. Resolves an action locally using ThaliPeerPoolDefault

2016-03-24T16:43:48.474Z - info: Running on android test: 86. Action fails because of a bad hostname.

2016-03-24T16:43:57.251Z - info: Running on android test: 87. hostaddress is removed when the action is running. 

2016-03-24T16:44:03.090Z - info: Running on android test: 88. Start and stop ThaliNotificationServer

2016-03-24T16:44:10.281Z - info: Running on android test: 89. Pass an empty array to ThaliNotificationServer.start

2016-03-24T16:44:11.246Z - info: Running on android test: 90. Pass a string to ThaliNotificationServer.start

2016-03-24T16:44:11.779Z - info: Running on android test: 91. Pass an empty parameter to ThaliNotificationServer.start

2016-03-24T16:44:12.417Z - info: Running on android test: 92. Make an HTTP request to /NotificationBeacons

2016-03-24T16:44:13.006Z - info: Running on android test: 93. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-24T16:44:13.494Z - info: Running on android test: 94. Make an HTTP request to /NotificationBeaconsbefore calling start

2016-03-24T16:44:14.026Z - info: Running on android test: 95. #testThaliPeerAction - test getters

2016-03-24T16:44:14.432Z - info: Running on android test: 96. #testThaliPeerAction - start and kill

2016-03-24T16:44:15.908Z - info: Running on android test: 97. #testThaliPeerAction - double start

2016-03-24T16:44:16.654Z - info: Running on android test: 98. #testThaliPeerAction - start after kill

2016-03-24T16:44:17.286Z - info: Running on android test: 99. #testThaliPeerAction - make sure ids are unique

2016-03-24T16:44:18.822Z - info: Running on android test: 100. Test PeerConnectionInformation basics

2016-03-24T16:44:19.818Z - info: Running on android test: 101. Test PeerDictionary basic functionality

2016-03-24T16:44:24.838Z - info: Running on android test: 102. Test PeerDictionary with multiple entries.

2016-03-24T16:44:34.270Z - info: Running on android test: 103. RESOLVED entries are removed before WAITING state entry.

2016-03-24T16:44:40.190Z - info: Running on android test: 104. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-24T16:44:45.179Z - info: Running on android test: 105. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-24T16:44:57.266Z - info: Running on android test: 106. #ThaliPeerPoolInterface - bad enqueues

2016-03-24T16:45:45.704Z - debug: Socket disconnected: ping timeout 9 (NOT YET SET)

2016-03-24T16:46:09.731Z - info: Running on android test: 107. #ThaliPeerPoolInterface - do not allow same object type

2016-03-24T16:46:10.789Z - info: Running on android test: 108. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-24T16:46:11.915Z - info: Running on android test: 109. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent

2016-03-24T16:46:12.453Z - info: Running on android test: 110. compareBufferArrays

2016-03-24T16:46:14.379Z - info: Running on android test: 111. Call start twice and get error

2016-03-24T16:46:15.543Z - info: Running on android test: 112. Start and make sure it runs

2016-03-24T16:46:16.012Z - info: Running on android test: 113. Make sure getTimeWhenRun is right after start

2016-03-24T16:46:16.492Z - info: Running on android test: 114. Make sure getTimeWhenRun is -1 after function is called

2016-03-24T16:46:16.860Z - info: Running on android test: 115. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-24T16:46:17.441Z - info: Running on android test: 116. Test TransientState

2016-03-24T16:46:17.854Z - info: Running on android test: 117. No peers and empty database

2016-03-24T16:46:19.721Z - info: Running on android test: 118. One peer and empty DB

2016-03-24T16:46:22.052Z - info: Running on android test: 119. One peer with _Local set behind current seq

2016-03-24T16:46:25.645Z - info: Running on android test: 120. One peer with _Local set equal to current seq

2016-03-24T16:46:26.751Z - info: Running on android test: 121. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-24T16:46:30.008Z - info: Running on android test: 122. Three peers, one not in DB, one behind and one ahead

2016-03-24T16:46:32.185Z - info: Running on android test: 123. More than maximum peers, make sure we only send maximum allowed

2016-03-24T16:46:33.329Z - info: Running on android test: 124. two peers with empty DB, update the doc

2016-03-24T16:46:33.964Z - info: Running on android test: 125. add doc and make sure tokens refresh when they expire

2016-03-24T16:46:34.832Z - info: Running on android test: 126. start and stop and start and stop

2016-03-24T16:46:35.452Z - info: Running on android test: 127. two identical starts in a row

2016-03-24T16:46:36.466Z - info: Running on android test: 128. two different starts in a row

2016-03-24T16:46:37.193Z - info: Running on android test: 129. two stops and a start and two stops

2016-03-24T16:46:37.748Z - info: Running on android test: 130. we properly enqueue requests so no then needed

2016-03-24T16:46:38.393Z - info: Running on android test: 131. test calculateSeqPointKeyId

2016-03-24T16:46:38.886Z - info: Running on android test: 132. can create servers manager

2016-03-24T16:46:39.397Z - info: Running on android test: 133. calling stop without start causes error

2016-03-24T16:46:39.766Z - info: Running on android test: 134. can start/stop servers manager

2016-03-24T16:46:40.272Z - info: Running on android test: 135. starting twice resolves with listening port

2016-03-24T16:46:40.758Z - info: Running on android test: 136. terminateIncomingConnection will terminate a connection

2016-03-24T16:46:41.309Z - info: Running on android test: 137. terminate an Outgoing connection will terminate the server

2016-03-24T16:46:41.774Z - info: Running on android test: 138. terminate an Outgoing connection with wrong arguments is not harmful

2016-03-24T16:46:42.289Z - info: Running on android test: 139. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-24T16:46:42.836Z - info: Running on android test: 140. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-24T16:46:43.347Z - info: Running on android test: 141. messages with invalid location or USN should be ignored

2016-03-24T16:46:43.864Z - info: Running on android test: 142. verify that Thali-specific messages are filtered correctly

2016-03-24T16:46:44.251Z - info: Running on android test: 143. #startListeningForAdvertisements should fail if start not called

2016-03-24T16:46:44.712Z - info: Running on android test: 144. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-24T16:46:45.194Z - info: Running on android test: 145. #start should fail if called twice in a row

2016-03-24T16:46:45.597Z - info: Running on android test: 146. should not be started after stop is called

2016-03-24T16:46:46.074Z - info: Running on android test: 147. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-24T16:46:46.606Z - info: Running on android test: 148. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-24T16:46:46.986Z - info: Running on android test: 149. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-24T16:46:47.517Z - info: Running on android test: 150. #stop can be called multiple times in a row

2016-03-24T16:46:47.929Z - info: Running on android test: 151. #startListeningForAdvertisements can be called multiple times in a row

2016-03-24T16:46:48.360Z - info: Running on android test: 152. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-24T16:46:48.777Z - info: Running on android test: 153. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-24T16:46:49.185Z - info: Running on android test: 154. functions are run from a queue in the right order

2016-03-24T16:46:49.862Z - info: Running on android test: 155. #ThaliPeerPoolDefault - single action

2016-03-24T16:46:50.397Z - info: Running on android test: 156. #ThaliPeerPoolDefault - multiple actions

2016-03-24T16:46:54.306Z - info: Test run on android complete

2016-03-24T16:46:54.310Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-24T16:46:54.312Z - info: PLATFORM: android

2016-03-24T16:46:54.312Z - info: RESULT: FAIL
2016-03-24T16:46:54.313Z - info: 156 of 156 tests completed

2016-03-24T16:46:54.314Z - info: 154/156 passed (2 failures)
2016-03-24T16:46:54.315Z - info: 

--- Failed tests ---

2016-03-24T16:46:54.315Z - warn: 54. we successfully receive and replay discoveryAdvertisingStateUpdate - fail
2016-03-24T16:46:54.316Z - warn: 55. can do HTTP requests between peers - fail

2016-03-24T16:46:54.317Z - info: 

-== END ==-

2016-03-24T16:46:55.397Z - debug: Socket disconnected: transport close 5 (motorola-Nexus 6)

2016-03-24T16:46:55.736Z - debug: Socket disconnected: transport close 3 (LGE-LG-H815)

2016-03-24T16:46:56.037Z - debug: Socket disconnected: transport close 4 (samsung-SM-N910C)

2016-03-24T16:52:01.352Z - debug: Socket disconnected: ping timeout 0 (Apple-Iphone5-1)

2016-03-24T16:56:10.078Z - debug: Socket disconnected: transport close 8 (NOT YET SET)

2016-03-24T16:57:16.330Z - debug: Socket disconnected: transport close 10 (NOT YET SET)

2016-03-24T16:58:27.841Z - debug: Socket disconnected: transport close 11 (NOT YET SET)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m
2016-03-24T16:39:55.252Z - error: Too many emit retries to device: samsung-SM-N910C

2016-03-24T16:40:06.351Z - error: Too many emit retries to device: samsung-SM-N910C

2016-03-24T16:41:25.766Z - error: Too many emit retries to device: samsung-SM-N910C

2016-03-24T16:41:25.767Z - error: Too many emit retries to device: motorola-Nexus 6

2016-03-24T16:41:44.789Z - error: Too many emit retries to device: LGE-LG-H815

2016-03-24T16:41:44.792Z - error: Too many emit retries to device: motorola-Nexus 6

2016-03-24T16:42:09.676Z - error: Too many emit retries to device: samsung-SM-N910C

2016-03-24T16:42:30.037Z - error: Too many emit retries to device: motorola-Nexus 6

2016-03-24T16:43:10.360Z - error: Too many emit retries to device: motorola-Nexus 6

2016-03-24T16:45:06.299Z - error: Too many emit retries to device: LGE-LG-H815

2016-03-24T16:45:26.205Z - error: Too many emit retries to device: LGE-LG-H815

2016-03-24T16:46:09.577Z - error: Too many emit retries to device: samsung-SM-N910C


```


Logs for system : 
```

android : No Error

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true

```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/639107048b8fbc2_416_ThaliNotificationClient_juhanak/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/639107048b8fbc2_416_ThaliNotificationClient_juhanak/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/639107048b8fbc2_416_ThaliNotificationClient_juhanak/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/639107048b8fbc2_416_ThaliNotificationClient_juhanak/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/639107048b8fbc2_416_ThaliNotificationClient_juhanak/iOS_server.md)




###Android Logs
####Node name: thali07
Console output:
```
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
Device test finished on 0c6a0f3c0bdb4e77 
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Android task is completed. [SUCCESS]
```
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/639107048b8fbc2_416_ThaliNotificationClient_juhanak/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/639107048b8fbc2_416_ThaliNotificationClient_juhanak/thali07_LGE-LG-H815.md)

####Node name: thali08
Console output:
```
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Device test finished on ZX1G429CRK 
Android task is completed. [SUCCESS]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/639107048b8fbc2_416_ThaliNotificationClient_juhanak/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/639107048b8fbc2_416_ThaliNotificationClient_juhanak/thali08_motorola-Nexus 6.md)



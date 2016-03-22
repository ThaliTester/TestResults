#### Test 63680118d4cb974 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-03-22T13:38:51.450Z - info: listening on *:3000

2016-03-22T13:38:53.280Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:0

2016-03-22T13:38:53.359Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:1

2016-03-22T13:38:53.462Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:2

2016-03-22T13:38:53.467Z - info: Required number of ios devices presented (3)

2016-03-22T13:38:53.471Z - info: Starting unit test run for platform: ios

2016-03-22T13:38:54.182Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:3

2016-03-22T13:38:54.184Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-22T13:38:54.192Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:4

2016-03-22T13:38:54.273Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-22T13:38:54.865Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-22T13:38:55.294Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-22T13:38:55.680Z - info: Running on ios test: 4. native server connections all up

2016-03-22T13:38:56.207Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-22T13:38:56.700Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-22T13:38:57.011Z - debug: Socket disconnected: transport close 3 (Apple-Iphone5s-1)

2016-03-22T13:38:57.261Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-22T13:38:57.785Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-22T13:38:58.320Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-22T13:39:00.597Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:5

2016-03-22T13:39:07.109Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-22T13:39:07.321Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:6

2016-03-22T13:39:07.322Z - info: Required number of android devices presented (3)

2016-03-22T13:39:07.324Z - info: Starting unit test run for platform: android

2016-03-22T13:39:07.943Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-22T13:39:08.245Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-22T13:39:08.414Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-22T13:39:08.687Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-22T13:39:08.831Z - info: Running on ios test: 13. closeAll with promise

2016-03-22T13:39:09.863Z - info: Running on ios test: 14. multiplex can send data

2016-03-22T13:39:10.124Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-22T13:39:10.288Z - info: Running on ios test: 15. enqueue and run in order

2016-03-22T13:39:10.863Z - info: Running on ios test: 16. enqueueAtTop and run backwards

2016-03-22T13:39:11.034Z - info: Running on android test: 4. native server connections all up

2016-03-22T13:39:11.241Z - info: Running on ios test: 17. mix enqueue and enqueueAtTop

2016-03-22T13:39:11.601Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-22T13:39:11.760Z - info: Running on ios test: 18. queues handled independently

2016-03-22T13:39:12.127Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-22T13:39:12.207Z - info: Running on ios test: 19. basic

2016-03-22T13:39:12.842Z - info: Running on ios test: 20. another

2016-03-22T13:39:12.850Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-22T13:39:13.542Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-22T13:39:13.547Z - info: Running on ios test: 21. can pass data in setup

2016-03-22T13:39:14.027Z - info: Running on ios test: 22. #startListeningForAdvertisements should fail if start not called

2016-03-22T13:39:14.175Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-22T13:39:14.480Z - info: Running on ios test: 23. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-22T13:39:14.865Z - info: Running on ios test: 24. should be able to call #stopListeningForAdvertisements many times

2016-03-22T13:39:15.178Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-22T13:39:15.361Z - info: Running on ios test: 25. should be able to call #startListeningForAdvertisements many times

2016-03-22T13:39:15.832Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-22T13:39:16.081Z - info: Running on ios test: 26. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-22T13:39:16.420Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-22T13:39:16.754Z - info: Running on android test: 13. closeAll with promise

2016-03-22T13:39:17.189Z - info: Running on android test: 14. multiplex can send data

2016-03-22T13:39:17.598Z - info: Running on android test: 15. enqueue and run in order

2016-03-22T13:39:18.290Z - info: Running on ios test: 27. should be able to call #stopAdvertisingAndListening many times

2016-03-22T13:39:18.299Z - info: Running on android test: 16. enqueueAtTop and run backwards

2016-03-22T13:39:18.702Z - info: Running on android test: 17. mix enqueue and enqueueAtTop

2016-03-22T13:39:19.096Z - info: Running on ios test: 28. #start should fail if called twice in a row

2016-03-22T13:39:19.577Z - info: Running on android test: 18. queues handled independently

2016-03-22T13:39:19.706Z - info: Running on ios test: 29. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-22T13:39:20.601Z - info: Running on ios test: 30. does not send duplicate availability changes

2016-03-22T13:39:21.681Z - info: Running on ios test: 31. can get the network status

2016-03-22T13:39:23.771Z - info: Running on ios test: 32. wifi peer is marked unavailable if announcements stop

2016-03-22T13:39:24.020Z - info: Running on android test: 19. basic

2016-03-22T13:39:24.466Z - info: Running on android test: 20. another

2016-03-22T13:39:24.811Z - info: Running on android test: 21. can pass data in setup

2016-03-22T13:39:25.152Z - info: Running on android test: 22. #startListeningForAdvertisements should fail if start not called

2016-03-22T13:39:25.485Z - info: Running on ios test: 33. Can call start/stopListeningForAdvertisements

2016-03-22T13:39:25.536Z - info: Running on android test: 23. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-22T13:39:25.940Z - info: Running on android test: 24. should be able to call #stopListeningForAdvertisements many times

2016-03-22T13:39:26.074Z - info: Running on ios test: 34. Calling startListeningForAdvertisements twice is NOT an error

2016-03-22T13:39:26.610Z - info: Running on android test: 25. should be able to call #startListeningForAdvertisements many times

2016-03-22T13:39:27.532Z - info: Running on ios test: 35. Can call start/stopUpdateAdvertisingAndListening

2016-03-22T13:39:28.498Z - info: Running on android test: 26. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-22T13:39:31.175Z - info: Running on ios test: 36. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-22T13:39:31.268Z - info: Running on android test: 27. should be able to call #stopAdvertisingAndListening many times

2016-03-22T13:39:33.324Z - info: Running on android test: 28. #start should fail if called twice in a row

2016-03-22T13:39:33.641Z - info: Running on ios test: 37. peerAvailabilityChange is called

2016-03-22T13:39:33.870Z - info: Running on android test: 29. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-22T13:39:34.758Z - info: Running on android test: 30. does not send duplicate availability changes

2016-03-22T13:39:35.236Z - info: Running on android test: 31. can get the network status

2016-03-22T13:39:35.716Z - info: Running on android test: 32. wifi peer is marked unavailable if announcements stop

2016-03-22T13:39:37.518Z - info: Running on android test: 33. Can call start/stopListeningForAdvertisements

2016-03-22T13:39:38.101Z - info: Running on android test: 34. Calling startListeningForAdvertisements twice is NOT an error

2016-03-22T13:39:39.450Z - info: Running on ios test: 38. Can connect to a remote peer

2016-03-22T13:40:02.814Z - info: Running on android test: 35. Can call start/stopUpdateAdvertisingAndListening

2016-03-22T13:40:03.752Z - info: Running on android test: 36. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-22T13:40:04.764Z - info: Running on android test: 37. peerAvailabilityChange is called

2016-03-22T13:40:07.489Z - info: Running on android test: 38. Can connect to a remote peer

2016-03-22T13:40:19.044Z - info: Running on android test: 39. Can shift large amounts of data

2016-03-22T13:40:26.783Z - info: Running on android test: 40. #startListeningForAdvertisements should fail if start not called

2016-03-22T13:40:29.969Z - info: Running on android test: 41. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-22T13:40:30.923Z - info: Running on android test: 42. should be able to call #stopListeningForAdvertisements many times

2016-03-22T13:40:31.314Z - info: Running on android test: 43. should be able to call #startListeningForAdvertisements many times

2016-03-22T13:40:32.702Z - info: Running on android test: 44. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-22T13:40:34.125Z - info: Running on android test: 45. should be able to call #stopAdvertisingAndListening many times

2016-03-22T13:40:36.433Z - info: Running on android test: 46. can get the network status before starting

2016-03-22T13:40:38.176Z - info: Running on android test: 47. error returned with bad router

2016-03-22T13:40:38.829Z - info: Running on android test: 48. all services are stopped when we call stop

2016-03-22T13:40:39.501Z - info: Running on android test: 49. make sure terminateConnection is properly hooked up

2016-03-22T13:40:39.958Z - info: Running on android test: 50. make sure terminateListener is properly hooked up

2016-03-22T13:40:40.309Z - info: Running on android test: 51. make sure we actually call kill connections properly

2016-03-22T13:40:40.845Z - info: Running on android test: 52. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received

2016-03-22T13:40:41.368Z - info: Running on android test: 53. We repeat failedConnection event when we get it from thaliTcpServersManager

2016-03-22T13:40:41.873Z - info: Running on android test: 54. we successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-22T13:40:42.993Z - warn: Failed on android test: 54. we successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-22T13:40:42.994Z - info: Running on android test: 55. can do HTTP requests between peers

2016-03-22T13:40:55.739Z - info: Running on android test: 56. Test BEACONS_RETRIEVED_AND_PARSED locally

2016-03-22T13:40:56.321Z - info: Running on android test: 57. Test HTTP_BAD_RESPONSE locally

2016-03-22T13:40:56.898Z - info: Running on android test: 58. Test NETWORK_PROBLEM locally

2016-03-22T13:40:57.755Z - info: Running on android test: 59. Test timeout locally

2016-03-22T13:41:03.167Z - info: Running on android test: 60. Call the start two times

2016-03-22T13:41:04.702Z - info: Running on android test: 61. Call the kill before calling the start

2016-03-22T13:41:05.321Z - info: Running on android test: 62. Call the kill immediately after the start

2016-03-22T13:41:05.799Z - info: Running on android test: 63. Call the kill while waiting a response from the server

2016-03-22T13:41:08.270Z - info: Running on android test: 64. Test to exceed the max content size locally

2016-03-22T13:41:08.881Z - info: Running on android test: 65. Close the server socket while the client is waiting a response from the server. Local test.

2016-03-22T13:41:10.148Z - warn: Failed on ios test: 38. Can connect to a remote peer

2016-03-22T13:41:10.149Z - info: Running on ios test: 39. Can shift large amounts of data

2016-03-22T13:41:13.111Z - info: Running on android test: 66. Close the client socket while the client is waiting a response from the server. Local test.

2016-03-22T13:41:16.722Z - info: Running on android test: 67. #generatePreambleAndBeacons bad args

2016-03-22T13:41:17.285Z - info: Running on android test: 68. #generatePreambleAndBeacons empty keys to notify

2016-03-22T13:41:17.636Z - info: Running on android test: 69. #generatePreambleAndBeacons multiple keys to notify

2016-03-22T13:41:18.081Z - info: Running on android test: 70. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-22T13:41:19.445Z - info: Running on android test: 71. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-22T13:41:21.236Z - info: Running on android test: 72. #parseBeacons expiration out of range lower

2016-03-22T13:41:22.019Z - info: Running on android test: 73. #parseBeacons expiration out of range lower

2016-03-22T13:41:22.497Z - info: Running on android test: 74. #parseBeacons no beacons returns null

2016-03-22T13:41:22.995Z - info: Running on android test: 75. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-22T13:41:23.419Z - info: Running on android test: 76. #parseBeacons addressBookCallback fails decrypt

2016-03-22T13:41:24.105Z - info: Running on android test: 77. #parseBeacons addressBookCallback returns no matches

2016-03-22T13:41:24.789Z - info: Running on android test: 78. #parseBeacons addressBookCallback returns spurious match

2016-03-22T13:41:25.732Z - info: Running on android test: 79. #parseBeacons addressBookCallback returns public key

2016-03-22T13:41:31.540Z - info: Running on android test: 80. validate generatePskIdentityField

2016-03-22T13:41:32.210Z - info: Running on android test: 81. validate generatePskSecret

2016-03-22T13:41:32.770Z - info: Running on android test: 82. Start and stop ThaliNotificationServer

2016-03-22T13:41:33.335Z - info: Running on android test: 83. Pass an empty array to ThaliNotificationServer.start

2016-03-22T13:41:34.051Z - info: Running on android test: 84. Pass a string to ThaliNotificationServer.start

2016-03-22T13:41:34.653Z - info: Running on android test: 85. Pass an empty parameter to ThaliNotificationServer.start

2016-03-22T13:41:35.205Z - info: Running on android test: 86. Make an HTTP request to /NotificationBeacons

2016-03-22T13:41:35.895Z - info: Running on android test: 87. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-22T13:41:36.584Z - info: Running on android test: 88. Make an HTTP request to /NotificationBeaconsbefore calling start

2016-03-22T13:41:37.391Z - info: Running on android test: 89. #testThaliPeerAction - test getters

2016-03-22T13:41:38.885Z - info: Running on android test: 90. #testThaliPeerAction - start and kill

2016-03-22T13:41:39.347Z - info: Running on android test: 91. #testThaliPeerAction - double start

2016-03-22T13:41:39.917Z - info: Running on android test: 92. #testThaliPeerAction - start after kill

2016-03-22T13:41:40.318Z - info: Running on android test: 93. #testThaliPeerAction - make sure ids are unique

2016-03-22T13:41:40.711Z - info: Running on android test: 94. Test PeerConnectionInformation basics

2016-03-22T13:41:41.044Z - info: Running on android test: 95. Test PeerDictionary basic functionality

2016-03-22T13:41:41.483Z - info: Running on android test: 96. Test PeerDictionary with multiple entries.

2016-03-22T13:41:43.288Z - info: Running on android test: 97. RESOLVED entries are removed before WAITING state entry.

2016-03-22T13:41:44.442Z - info: Running on android test: 98. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-22T13:41:45.969Z - info: Running on android test: 99. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-22T13:41:47.106Z - info: Running on android test: 100. #ThaliPeerPoolInterface - bad enqueues

2016-03-22T13:41:47.588Z - info: Running on android test: 101. #ThaliPeerPoolInterface - do not allow same object type

2016-03-22T13:41:48.075Z - info: Running on android test: 102. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-22T13:41:48.586Z - info: Running on android test: 103. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent

2016-03-22T13:41:48.985Z - info: Running on android test: 104. compareBufferArrays

2016-03-22T13:41:49.353Z - info: Running on android test: 105. Call start twice and get error

2016-03-22T13:41:49.682Z - info: Running on android test: 106. Start and make sure it runs

2016-03-22T13:41:50.111Z - info: Running on android test: 107. Make sure getTimeWhenRun is right after start

2016-03-22T13:41:50.575Z - info: Running on android test: 108. Make sure getTimeWhenRun is -1 after function is called

2016-03-22T13:41:50.965Z - info: Running on android test: 109. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-22T13:41:51.393Z - info: Running on android test: 110. Test TransientState

2016-03-22T13:41:51.818Z - info: Running on android test: 111. No peers and empty database

2016-03-22T13:41:52.433Z - info: Running on android test: 112. One peer and empty DB

2016-03-22T13:41:53.066Z - info: Running on android test: 113. One peer with _Local set behind current seq

2016-03-22T13:41:53.811Z - info: Running on android test: 114. One peer with _Local set equal to current seq

2016-03-22T13:41:56.491Z - info: Running on android test: 115. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-22T13:41:56.983Z - info: Running on android test: 116. Three peers, one not in DB, one behind and one ahead

2016-03-22T13:41:57.721Z - info: Running on android test: 117. More than maximum peers, make sure we only send maximum allowed

2016-03-22T13:41:59.060Z - info: Running on android test: 118. two peers with empty DB, update the doc

2016-03-22T13:42:00.301Z - info: Running on android test: 119. add doc and make sure tokens refresh when they expire

2016-03-22T13:42:02.089Z - info: Running on android test: 120. start and stop and start and stop

2016-03-22T13:42:02.639Z - info: Running on android test: 121. two identical starts in a row

2016-03-22T13:42:03.306Z - info: Running on android test: 122. two different starts in a row

2016-03-22T13:42:03.992Z - info: Running on android test: 123. two stops and a start and two stops

2016-03-22T13:42:04.526Z - info: Running on android test: 124. we properly enqueue requests so no then needed

2016-03-22T13:42:05.332Z - info: Running on android test: 125. test calculateSeqPointKeyId

2016-03-22T13:42:05.915Z - info: Running on android test: 126. can create servers manager

2016-03-22T13:42:06.310Z - info: Running on android test: 127. calling stop without start causes error

2016-03-22T13:42:06.664Z - info: Running on android test: 128. can start/stop servers manager

2016-03-22T13:42:07.084Z - info: Running on android test: 129. starting twice resolves with listening port

2016-03-22T13:42:07.470Z - info: Running on android test: 130. terminateIncomingConnection will terminate a connection

2016-03-22T13:42:07.960Z - info: Running on android test: 131. terminate an Outgoing connection will terminate the server

2016-03-22T13:42:08.408Z - info: Running on android test: 132. terminate an Outgoing connection with wrong arguments is not harmful

2016-03-22T13:42:08.802Z - info: Running on android test: 133. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-22T13:42:09.232Z - info: Running on android test: 134. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-22T13:42:09.661Z - info: Running on android test: 135. messages with invalid location or USN should be ignored

2016-03-22T13:42:10.015Z - info: Running on android test: 136. verify that Thali-specific messages are filtered correctly

2016-03-22T13:42:10.339Z - info: Running on android test: 137. #startListeningForAdvertisements should fail if start not called

2016-03-22T13:42:10.828Z - info: Running on android test: 138. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-22T13:42:11.256Z - info: Running on android test: 139. #start should fail if called twice in a row

2016-03-22T13:42:11.648Z - info: Running on android test: 140. should not be started after stop is called

2016-03-22T13:42:12.104Z - info: Running on android test: 141. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-22T13:42:12.500Z - info: Running on android test: 142. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-22T13:42:12.906Z - info: Running on android test: 143. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-22T13:42:13.313Z - info: Running on android test: 144. #stop can be called multiple times in a row

2016-03-22T13:42:13.722Z - info: Running on android test: 145. #startListeningForAdvertisements can be called multiple times in a row

2016-03-22T13:42:14.151Z - info: Running on android test: 146. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-22T13:42:14.599Z - info: Running on android test: 147. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-22T13:42:15.082Z - info: Running on android test: 148. functions are run from a queue in the right order

2016-03-22T13:42:15.589Z - info: Running on android test: 149. #ThaliPeerPoolDefault - single action

2016-03-22T13:42:15.973Z - info: Running on android test: 150. #ThaliPeerPoolDefault - multiple actions

2016-03-22T13:42:16.526Z - info: Test run on android complete

2016-03-22T13:42:16.529Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-22T13:42:16.531Z - info: PLATFORM: android

2016-03-22T13:42:16.532Z - info: RESULT: FAIL

2016-03-22T13:42:16.533Z - info: 150 of 150 tests completed

2016-03-22T13:42:16.534Z - info: 149/150 passed (1 failures)

2016-03-22T13:42:16.535Z - info: 

--- Failed tests ---

2016-03-22T13:42:16.537Z - warn: 54. we successfully receive and replay discoveryAdvertisingStateUpdate - fail

2016-03-22T13:42:16.538Z - info: 

-== END ==-

2016-03-22T13:42:17.504Z - debug: Socket disconnected: transport close 5 (samsung-SM-N910C)

2016-03-22T13:42:17.828Z - debug: Socket disconnected: transport close 4 (LGE-LG-H815)

2016-03-22T13:42:18.209Z - debug: Socket disconnected: transport close 6 (motorola-Nexus 6)

2016-03-22T13:42:20.345Z - warn: Failed on ios test: 39. Can shift large amounts of data

2016-03-22T13:42:20.346Z - info: Running on ios test: 40. #startListeningForAdvertisements should fail if start not called

2016-03-22T13:42:22.074Z - info: Running on ios test: 41. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-22T13:42:22.859Z - info: Running on ios test: 42. should be able to call #stopListeningForAdvertisements many times

2016-03-22T13:42:23.576Z - info: Running on ios test: 43. should be able to call #startListeningForAdvertisements many times

2016-03-22T13:43:49.020Z - debug: Socket disconnected: ping timeout 0 (Apple-Iphone5-1)

2016-03-22T13:58:26.836Z - debug: Socket disconnected: transport close 2 (Apple-IpadAir2-1)

2016-03-22T13:58:26.880Z - debug: Socket disconnected: transport close 1 (Apple-Iphone6-1)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m
2016-03-22T13:39:47.988Z - error: Too many emit retries to device: samsung-SM-N910C

2016-03-22T13:39:47.990Z - error: Too many emit retries to device: motorola-Nexus 6

2016-03-22T13:39:48.487Z - error: Too many emit retries to device: Apple-Iphone6-1

2016-03-22T13:39:48.489Z - error: Too many emit retries to device: Apple-IpadAir2-1


```


Logs for system : 
```

android : No Error

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
true

```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/63680118d4cb974_Support_passing_data_in_coordinated_tests_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/63680118d4cb974_Support_passing_data_in_coordinated_tests_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/63680118d4cb974_Support_passing_data_in_coordinated_tests_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/63680118d4cb974_Support_passing_data_in_coordinated_tests_vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/63680118d4cb974_Support_passing_data_in_coordinated_tests_vjrantal/iOS_server.md)




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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/63680118d4cb974_Support_passing_data_in_coordinated_tests_vjrantal/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/63680118d4cb974_Support_passing_data_in_coordinated_tests_vjrantal/thali07_LGE-LG-H815.md)

####Node name: thali08
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Device test finished on ZX1G429CRK 
Android task is completed. [SUCCESS]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/63680118d4cb974_Support_passing_data_in_coordinated_tests_vjrantal/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/63680118d4cb974_Support_passing_data_in_coordinated_tests_vjrantal/thali08_motorola-Nexus 6.md)



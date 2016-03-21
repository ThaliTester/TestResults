#### Test 625481246894564 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-03-21T12:04:19.026Z - info: listening on *:3000

2016-03-21T12:04:20.633Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:0

2016-03-21T12:04:20.646Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:1

2016-03-21T12:04:20.648Z - info: Required number of ios devices presented (2)

2016-03-21T12:04:20.652Z - info: Starting unit test run for platform: ios

2016-03-21T12:04:21.359Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-21T12:04:22.043Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-21T12:04:22.181Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:2

2016-03-21T12:04:22.459Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-21T12:04:22.717Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:3

2016-03-21T12:04:22.719Z - info: Discarding surplus device: Apple-IpadAir2-1

2016-03-21T12:04:22.888Z - info: Running on ios test: 4. native server connections all up

2016-03-21T12:04:23.379Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-21T12:04:23.783Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:4

2016-03-21T12:04:23.784Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-21T12:04:23.937Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-21T12:04:24.300Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-21T12:04:24.766Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-21T12:04:25.210Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-21T12:04:25.343Z - debug: Socket disconnected: transport close 3 (Apple-IpadAir2-1)

2016-03-21T12:04:26.260Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-21T12:04:26.666Z - debug: Socket disconnected: transport close 4 (Apple-Iphone5s-1)

2016-03-21T12:04:28.046Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-21T12:04:28.493Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-21T12:04:28.954Z - info: Running on ios test: 13. closeAll with promise

2016-03-21T12:04:29.491Z - info: Running on ios test: 14. multiplex can send data

2016-03-21T12:04:29.942Z - info: Running on ios test: 15. enqueue and run in order

2016-03-21T12:04:30.534Z - info: Running on ios test: 16. enqueueAtTop and run backwards

2016-03-21T12:04:30.910Z - info: Running on ios test: 17. mix enqueue and enqueueAtTop

2016-03-21T12:04:31.160Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:5

2016-03-21T12:04:31.161Z - info: Required number of android devices presented (2)

2016-03-21T12:04:31.163Z - info: Starting unit test run for platform: android

2016-03-21T12:04:31.380Z - info: Running on ios test: 18. queues handled independently

2016-03-21T12:04:31.824Z - info: Running on ios test: 19. basic

2016-03-21T12:04:31.923Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-21T12:04:32.099Z - info: Running on ios test: 20. another

2016-03-21T12:04:32.226Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-21T12:04:32.331Z - info: Running on ios test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-21T12:04:32.679Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-21T12:04:32.686Z - info: Running on ios test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-21T12:04:33.081Z - info: Running on ios test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-21T12:04:33.203Z - info: Running on android test: 4. native server connections all up

2016-03-21T12:04:33.554Z - info: Running on ios test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-21T12:04:33.562Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-21T12:04:34.108Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-21T12:04:34.156Z - info: Running on ios test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-21T12:04:34.696Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-21T12:04:35.234Z - info: Running on ios test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-21T12:04:35.373Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-21T12:04:35.785Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-21T12:04:35.802Z - info: Running on ios test: 27. #start should fail if called twice in a row

2016-03-21T12:04:36.689Z - info: Running on ios test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-21T12:04:36.830Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-21T12:04:37.257Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-21T12:04:37.387Z - info: Running on ios test: 29. does not send duplicate availability changes

2016-03-21T12:04:37.689Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-21T12:04:38.126Z - info: Running on android test: 13. closeAll with promise

2016-03-21T12:04:38.583Z - info: Running on android test: 14. multiplex can send data

2016-03-21T12:04:38.985Z - info: Running on android test: 15. enqueue and run in order

2016-03-21T12:04:39.574Z - info: Running on android test: 16. enqueueAtTop and run backwards

2016-03-21T12:04:39.834Z - info: Running on ios test: 30. can get the network status

2016-03-21T12:04:40.585Z - info: Running on ios test: 31. wifi peer is marked unavailable if announcements stop

2016-03-21T12:04:40.696Z - info: Running on android test: 17. mix enqueue and enqueueAtTop

2016-03-21T12:04:41.185Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:6

2016-03-21T12:04:41.186Z - info: Discarding surplus device: motorola-Nexus 6

2016-03-21T12:04:41.220Z - info: Running on android test: 18. queues handled independently

2016-03-21T12:04:41.658Z - info: Running on android test: 19. basic

2016-03-21T12:04:41.840Z - debug: Socket disconnected: transport close 6 (motorola-Nexus 6)

2016-03-21T12:04:42.027Z - info: Running on android test: 20. another

2016-03-21T12:04:42.114Z - info: Running on ios test: 32. Can call start/stopListeningForAdvertisements

2016-03-21T12:04:42.409Z - info: Running on android test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-21T12:04:42.677Z - info: Running on ios test: 33. Calling startListeningForAdvertisements twice is NOT an error

2016-03-21T12:04:42.829Z - info: Running on android test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-21T12:04:43.119Z - info: Running on android test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-21T12:04:43.348Z - info: Running on ios test: 34. Can call start/stopUpdateAdvertisingAndListening

2016-03-21T12:04:44.226Z - info: Running on android test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-21T12:04:46.341Z - info: Running on ios test: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-21T12:04:46.849Z - info: Running on android test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-21T12:04:47.039Z - info: Running on ios test: 36. peerAvailabilityChange is called

2016-03-21T12:04:49.039Z - info: Running on android test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-21T12:04:53.233Z - info: Running on ios test: 37. Can connect to a remote peer

2016-03-21T12:04:56.889Z - info: Running on android test: 27. #start should fail if called twice in a row

2016-03-21T12:04:57.331Z - info: Running on android test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-21T12:04:58.386Z - info: Running on android test: 29. does not send duplicate availability changes

2016-03-21T12:04:59.525Z - info: Running on android test: 30. can get the network status

2016-03-21T12:05:00.071Z - info: Running on android test: 31. wifi peer is marked unavailable if announcements stop

2016-03-21T12:05:01.653Z - info: Running on android test: 32. Can call start/stopListeningForAdvertisements

2016-03-21T12:05:02.239Z - info: Running on android test: 33. Calling startListeningForAdvertisements twice is NOT an error

2016-03-21T12:05:03.038Z - info: Running on android test: 34. Can call start/stopUpdateAdvertisingAndListening

2016-03-21T12:05:03.843Z - info: Running on android test: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-21T12:05:04.569Z - info: Running on android test: 36. peerAvailabilityChange is called

2016-03-21T12:05:06.249Z - info: Running on android test: 37. Can connect to a remote peer

2016-03-21T12:05:18.173Z - info: Running on android test: 38. Can shift large amounts of data

2016-03-21T12:05:23.638Z - info: Running on android test: 39. #startListeningForAdvertisements should fail if start not called

2016-03-21T12:05:24.312Z - info: Running on android test: 40. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-21T12:05:24.701Z - info: Running on android test: 41. should be able to call #stopListeningForAdvertisements many times

2016-03-21T12:05:25.063Z - info: Running on android test: 42. should be able to call #startListeningForAdvertisements many times

2016-03-21T12:05:25.744Z - info: Running on android test: 43. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-21T12:05:26.555Z - info: Running on android test: 44. should be able to call #stopAdvertisingAndListening many times

2016-03-21T12:05:27.010Z - info: Running on android test: 45. can get the network status before starting

2016-03-21T12:05:28.634Z - info: Running on android test: 46. error returned with bad router

2016-03-21T12:05:29.764Z - info: Running on android test: 47. all services are stopped when we call stop

2016-03-21T12:05:30.671Z - info: Running on android test: 48. make sure terminateConnection is properly hooked up

2016-03-21T12:05:31.115Z - info: Running on android test: 49. make sure terminateListener is properly hooked up

2016-03-21T12:05:31.645Z - info: Running on android test: 50. make sure we actually call kill connections properly

2016-03-21T12:05:32.187Z - info: Running on android test: 51. can do HTTP requests between peers

2016-03-21T12:05:44.360Z - info: Running on android test: 52. Can do requests between peers after start and stop

2016-03-21T12:05:45.976Z - info: Running on android test: 53. We successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-21T12:05:46.457Z - info: Running on android test: 54. Test BEACONS_RETRIEVED_AND_PARSED locally

2016-03-21T12:05:47.029Z - info: Running on android test: 55. Test HTTP_BAD_RESPONSE locally

2016-03-21T12:05:47.503Z - info: Running on android test: 56. Test NETWORK_PROBLEM locally

2016-03-21T12:05:49.338Z - info: Running on android test: 57. Test timeout locally

2016-03-21T12:05:51.068Z - info: Running on android test: 58. Call the start two times

2016-03-21T12:05:51.571Z - info: Running on android test: 59. Call the kill before calling the start

2016-03-21T12:05:52.023Z - info: Running on android test: 60. Call the kill immediately after the start

2016-03-21T12:05:52.445Z - info: Running on android test: 61. Call the kill while waiting a response from the server

2016-03-21T12:05:54.837Z - info: Running on android test: 62. Test to exceed the max content size locally

2016-03-21T12:05:55.339Z - info: Running on android test: 63. Close the server socket while the client is waiting a response from the server. Local test.

2016-03-21T12:05:57.844Z - info: Running on android test: 64. Close the client socket while the client is waiting a response from the server. Local test.

2016-03-21T12:06:00.432Z - info: Running on android test: 65. #generatePreambleAndBeacons bad args

2016-03-21T12:06:00.761Z - info: Running on android test: 66. #generatePreambleAndBeacons empty keys to notify

2016-03-21T12:06:01.233Z - info: Running on android test: 67. #generatePreambleAndBeacons multiple keys to notify

2016-03-21T12:06:01.844Z - info: Running on android test: 68. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-21T12:06:02.343Z - info: Running on android test: 69. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-21T12:06:02.788Z - info: Running on android test: 70. #parseBeacons expiration out of range lower

2016-03-21T12:06:03.215Z - info: Running on android test: 71. #parseBeacons expiration out of range lower

2016-03-21T12:06:03.649Z - info: Running on android test: 72. #parseBeacons no beacons returns null

2016-03-21T12:06:04.075Z - info: Running on android test: 73. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-21T12:06:04.565Z - info: Running on android test: 74. #parseBeacons addressBookCallback fails decrypt

2016-03-21T12:06:05.053Z - info: Running on android test: 75. #parseBeacons addressBookCallback returns no matches

2016-03-21T12:06:05.686Z - info: Running on android test: 76. #parseBeacons addressBookCallback returns spurious match

2016-03-21T12:06:06.436Z - info: Running on android test: 77. #parseBeacons addressBookCallback returns public key

2016-03-21T12:06:06.921Z - info: Running on android test: 78. validate generatePskIdentityField

2016-03-21T12:06:07.297Z - info: Running on android test: 79. validate generatePskSecret

2016-03-21T12:06:07.679Z - info: Running on android test: 80. Start and stop ThaliNotificationServer

2016-03-21T12:06:08.041Z - info: Running on android test: 81. Pass an empty array to ThaliNotificationServer.start

2016-03-21T12:06:08.462Z - info: Running on android test: 82. Pass a string to ThaliNotificationServer.start

2016-03-21T12:06:08.840Z - info: Running on android test: 83. Pass an empty parameter to ThaliNotificationServer.start

2016-03-21T12:06:09.264Z - info: Running on android test: 84. Make an HTTP request to /NotificationBeacons

2016-03-21T12:06:09.745Z - info: Running on android test: 85. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-21T12:06:10.105Z - info: Running on android test: 86. Make an HTTP request to /NotificationBeaconsbefore calling start

2016-03-21T12:06:10.517Z - info: Running on android test: 87. #testThaliPeerAction - test getters

2016-03-21T12:06:10.764Z - info: Running on android test: 88. #testThaliPeerAction - start and kill

2016-03-21T12:06:11.041Z - info: Running on android test: 89. #testThaliPeerAction - double start

2016-03-21T12:06:11.416Z - info: Running on android test: 90. #testThaliPeerAction - start after kill

2016-03-21T12:06:11.736Z - info: Running on android test: 91. #testThaliPeerAction - make sure ids are unique

2016-03-21T12:06:11.992Z - info: Running on android test: 92. Test PeerConnectionInformation basics

2016-03-21T12:06:12.365Z - info: Running on android test: 93. Test PeerDictionary basic functionality

2016-03-21T12:06:12.760Z - info: Running on android test: 94. Test PeerDictionary with multiple entries.

2016-03-21T12:06:14.343Z - info: Running on android test: 95. RESOLVED entries are removed before WAITING state entry.

2016-03-21T12:06:15.372Z - info: Running on android test: 96. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-21T12:06:16.461Z - info: Running on android test: 97. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-21T12:06:17.574Z - info: Running on android test: 98. #ThaliPeerPoolInterface - bad enqueues

2016-03-21T12:06:17.892Z - info: Running on android test: 99. #ThaliPeerPoolInterface - do not allow same object type

2016-03-21T12:06:18.163Z - info: Running on android test: 100. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-21T12:06:18.450Z - info: Running on android test: 101. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent

2016-03-21T12:06:18.842Z - info: Running on android test: 102. compareBufferArrays

2016-03-21T12:06:19.090Z - info: Running on android test: 103. Call start twice and get error

2016-03-21T12:06:19.391Z - info: Running on android test: 104. Start and make sure it runs

2016-03-21T12:06:19.683Z - info: Running on android test: 105. Make sure getTimeWhenRun is right after start

2016-03-21T12:06:20.018Z - info: Running on android test: 106. Make sure getTimeWhenRun is -1 after function is called

2016-03-21T12:06:20.430Z - info: Running on android test: 107. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-21T12:06:20.828Z - info: Running on android test: 108. Test TransientState

2016-03-21T12:06:21.169Z - info: Running on android test: 109. No peers and empty database

2016-03-21T12:06:21.738Z - info: Running on android test: 110. One peer and empty DB

2016-03-21T12:06:22.371Z - info: Running on android test: 111. One peer with _Local set behind current seq

2016-03-21T12:06:22.894Z - info: Running on android test: 112. One peer with _Local set equal to current seq

2016-03-21T12:06:23.455Z - info: Running on android test: 113. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-21T12:06:24.099Z - info: Running on android test: 114. Three peers, one not in DB, one behind and one ahead

2016-03-21T12:06:25.030Z - info: Running on android test: 115. More than maximum peers, make sure we only send maximum allowed

2016-03-21T12:06:26.028Z - info: Running on android test: 116. two peers with empty DB, update the doc

2016-03-21T12:06:26.889Z - info: Running on android test: 117. add doc and make sure tokens refresh when they expire

2016-03-21T12:06:28.310Z - info: Running on android test: 118. start and stop and start and stop

2016-03-21T12:06:28.933Z - info: Running on android test: 119. two identical starts in a row

2016-03-21T12:06:29.501Z - info: Running on android test: 120. two different starts in a row

2016-03-21T12:06:29.940Z - info: Running on android test: 121. two stops and a start and two stops

2016-03-21T12:06:30.460Z - info: Running on android test: 122. we properly enqueue requests so no then needed

2016-03-21T12:06:31.019Z - info: Running on android test: 123. test calculateSeqPointKeyId

2016-03-21T12:06:31.688Z - info: Running on android test: 124. can create servers manager

2016-03-21T12:06:31.991Z - info: Running on android test: 125. calling stop without start causes error

2016-03-21T12:06:32.276Z - info: Running on android test: 126. can start/stop servers manager

2016-03-21T12:06:32.555Z - info: Running on android test: 127. starting twice resolves with listening port

2016-03-21T12:06:32.908Z - info: Running on android test: 128. terminateIncomingConnection will terminate a connection

2016-03-21T12:06:33.337Z - info: Running on android test: 129. terminate an Outgoing connection will terminate the server

2016-03-21T12:06:33.699Z - info: Running on android test: 130. terminate an Outgoing connection with wrong arguments is not harmful

2016-03-21T12:06:34.015Z - info: Running on android test: 131. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-21T12:06:34.404Z - info: Running on android test: 132. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-21T12:06:34.793Z - info: Running on android test: 133. messages with invalid location or USN should be ignored

2016-03-21T12:06:35.133Z - info: Running on android test: 134. verify that Thali-specific messages are filtered correctly

2016-03-21T12:06:35.401Z - info: Running on android test: 135. #startListeningForAdvertisements should fail if start not called

2016-03-21T12:06:35.723Z - info: Running on android test: 136. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-21T12:06:36.255Z - info: Running on android test: 137. #start should fail if called twice in a row

2016-03-21T12:06:36.561Z - info: Running on android test: 138. should not be started after stop is called

2016-03-21T12:06:36.871Z - info: Running on android test: 139. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-21T12:06:37.176Z - info: Running on android test: 140. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-21T12:06:37.540Z - info: Running on android test: 141. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-21T12:06:38.373Z - info: Running on android test: 142. #stop can be called multiple times in a row

2016-03-21T12:06:39.399Z - info: Running on android test: 143. #startListeningForAdvertisements can be called multiple times in a row

2016-03-21T12:06:39.873Z - info: Running on android test: 144. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-21T12:06:40.387Z - info: Running on android test: 145. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-21T12:06:40.830Z - info: Running on android test: 146. functions are run from a queue in the right order

2016-03-21T12:06:41.319Z - info: Running on android test: 147. #ThaliPeerPoolDefault - single action

2016-03-21T12:06:41.636Z - info: Running on android test: 148. #ThaliPeerPoolDefault - multiple actions

2016-03-21T12:06:41.944Z - info: Test run on android complete

2016-03-21T12:06:41.946Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-21T12:06:41.949Z - info: PLATFORM: android

2016-03-21T12:06:41.950Z - info: RESULT: PASS

2016-03-21T12:06:41.951Z - info: 148 of 148 tests completed

2016-03-21T12:06:41.952Z - info: 148/148 passed (0 failures)
2016-03-21T12:06:41.952Z - info: --- Test Details ---



2016-03-21T12:06:41.953Z - info: 1. calling createNativeListener directly rejects - pass

2016-03-21T12:06:41.954Z - info: 2. emits incomingConnectionState - pass
2016-03-21T12:06:41.955Z - info: 3. emits routerPortConnectionFailed - pass

2016-03-21T12:06:41.956Z - info: 4. native server connections all up - pass
2016-03-21T12:06:41.957Z - info: 5. native server - closing incoming stream cleans outgoing socket - pass

2016-03-21T12:06:41.957Z - info: 6. native server - closing incoming connection cleans outgoing socket - pass
2016-03-21T12:06:41.958Z - info: 7. native server - closing outgoing socket cleans associated mux stream - pass

2016-03-21T12:06:41.959Z - info: 8. native server - closing the whole server cleans everything up - pass

2016-03-21T12:06:41.960Z - info: 9. native server - we can get a ton of connections and data through and still clean up the server completely - pass
2016-03-21T12:06:41.960Z - info: 10. native server - simulate mux failure, make sure everything is cleaned up - pass

2016-03-21T12:06:41.961Z - info: 11. native server - timing out the incoming connection cleans everything up - pass
2016-03-21T12:06:41.962Z - info: 12. closeAll can close even when connections open - pass

2016-03-21T12:06:41.962Z - info: 13. closeAll with promise - pass
2016-03-21T12:06:41.963Z - info: 14. multiplex can send data - pass

2016-03-21T12:06:41.964Z - info: 15. enqueue and run in order - pass
2016-03-21T12:06:41.964Z - info: 16. enqueueAtTop and run backwards - pass

2016-03-21T12:06:41.965Z - info: 17. mix enqueue and enqueueAtTop - pass

2016-03-21T12:06:41.966Z - info: 18. queues handled independently - pass
2016-03-21T12:06:41.967Z - info: 19. basic - pass

2016-03-21T12:06:41.967Z - info: 20. another - pass
2016-03-21T12:06:41.968Z - info: 21. #startListeningForAdvertisements should fail if start not called - pass

2016-03-21T12:06:41.969Z - info: 22. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-21T12:06:41.970Z - info: 23. should be able to call #stopListeningForAdvertisements many times - pass

2016-03-21T12:06:41.970Z - info: 24. should be able to call #startListeningForAdvertisements many times - pass
2016-03-21T12:06:41.971Z - info: 25. should be able to call #startUpdateAdvertisingAndListening many times - pass

2016-03-21T12:06:41.972Z - info: 26. should be able to call #stopAdvertisingAndListening many times - pass
2016-03-21T12:06:41.973Z - info: 27. #start should fail if called twice in a row - pass

2016-03-21T12:06:41.973Z - info: 28. does not emit duplicate discoveryAdvertisingStateUpdate - pass

2016-03-21T12:06:41.974Z - info: 29. does not send duplicate availability changes - pass
2016-03-21T12:06:41.975Z - info: 30. can get the network status - pass

2016-03-21T12:06:41.975Z - info: 31. wifi peer is marked unavailable if announcements stop - pass
2016-03-21T12:06:41.976Z - info: 32. Can call start/stopListeningForAdvertisements - pass

2016-03-21T12:06:41.977Z - info: 33. Calling startListeningForAdvertisements twice is NOT an error - pass
2016-03-21T12:06:41.978Z - info: 34. Can call start/stopUpdateAdvertisingAndListening - pass

2016-03-21T12:06:41.978Z - info: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error - pass
2016-03-21T12:06:41.979Z - info: 36. peerAvailabilityChange is called - pass

2016-03-21T12:06:41.980Z - info: 37. Can connect to a remote peer - pass

2016-03-21T12:06:41.980Z - info: 38. Can shift large amounts of data - pass
2016-03-21T12:06:41.981Z - info: 39. #startListeningForAdvertisements should fail if start not called - pass

2016-03-21T12:06:41.982Z - info: 40. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-21T12:06:41.983Z - info: 41. should be able to call #stopListeningForAdvertisements many times - pass

2016-03-21T12:06:41.983Z - info: 42. should be able to call #startListeningForAdvertisements many times - pass
2016-03-21T12:06:41.984Z - info: 43. should be able to call #startUpdateAdvertisingAndListening many times - pass

2016-03-21T12:06:41.985Z - info: 44. should be able to call #stopAdvertisingAndListening many times - pass
2016-03-21T12:06:41.985Z - info: 45. can get the network status before starting - pass

2016-03-21T12:06:41.986Z - info: 46. error returned with bad router - pass
2016-03-21T12:06:41.987Z - info: 47. all services are stopped when we call stop - pass

2016-03-21T12:06:41.987Z - info: 48. make sure terminateConnection is properly hooked up - pass
2016-03-21T12:06:41.988Z - info: 49. make sure terminateListener is properly hooked up - pass

2016-03-21T12:06:41.989Z - info: 50. make sure we actually call kill connections properly - pass
2016-03-21T12:06:41.989Z - info: 51. can do HTTP requests between peers - pass

2016-03-21T12:06:41.990Z - info: 52. Can do requests between peers after start and stop - pass

2016-03-21T12:06:41.991Z - info: 53. We successfully receive and replay discoveryAdvertisingStateUpdate - pass
2016-03-21T12:06:41.992Z - info: 54. Test BEACONS_RETRIEVED_AND_PARSED locally - pass

2016-03-21T12:06:41.992Z - info: 55. Test HTTP_BAD_RESPONSE locally - pass
2016-03-21T12:06:41.993Z - info: 56. Test NETWORK_PROBLEM locally - pass

2016-03-21T12:06:41.994Z - info: 57. Test timeout locally - pass
2016-03-21T12:06:41.995Z - info: 58. Call the start two times - pass

2016-03-21T12:06:41.995Z - info: 59. Call the kill before calling the start - pass
2016-03-21T12:06:41.996Z - info: 60. Call the kill immediately after the start - pass

2016-03-21T12:06:41.997Z - info: 61. Call the kill while waiting a response from the server - pass

2016-03-21T12:06:41.997Z - info: 62. Test to exceed the max content size locally - pass
2016-03-21T12:06:41.998Z - info: 63. Close the server socket while the client is waiting a response from the server. Local test. - pass

2016-03-21T12:06:41.999Z - info: 64. Close the client socket while the client is waiting a response from the server. Local test. - pass
2016-03-21T12:06:42.000Z - info: 65. #generatePreambleAndBeacons bad args - pass

2016-03-21T12:06:42.000Z - info: 66. #generatePreambleAndBeacons empty keys to notify - pass
2016-03-21T12:06:42.001Z - info: 67. #generatePreambleAndBeacons multiple keys to notify - pass

2016-03-21T12:06:42.002Z - info: 68. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass
2016-03-21T12:06:42.002Z - info: 69. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass

2016-03-21T12:06:42.003Z - info: 70. #parseBeacons expiration out of range lower - pass
2016-03-21T12:06:42.004Z - info: 71. #parseBeacons expiration out of range lower - pass

2016-03-21T12:06:42.004Z - info: 72. #parseBeacons no beacons returns null - pass
2016-03-21T12:06:42.005Z - info: 73. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass

2016-03-21T12:06:42.006Z - info: 74. #parseBeacons addressBookCallback fails decrypt - pass
2016-03-21T12:06:42.006Z - info: 75. #parseBeacons addressBookCallback returns no matches - pass

2016-03-21T12:06:42.007Z - info: 76. #parseBeacons addressBookCallback returns spurious match - pass

2016-03-21T12:06:42.008Z - info: 77. #parseBeacons addressBookCallback returns public key - pass
2016-03-21T12:06:42.009Z - info: 78. validate generatePskIdentityField - pass
2016-03-21T12:06:42.010Z - info: 79. validate generatePskSecret - pass
2016-03-21T12:06:42.010Z - info: 80. Start and stop ThaliNotificationServer - pass
2016-03-21T12:06:42.011Z - info: 81. Pass an empty array to ThaliNotificationServer.start - pass

2016-03-21T12:06:42.012Z - info: 82. Pass a string to ThaliNotificationServer.start - pass
2016-03-21T12:06:42.012Z - info: 83. Pass an empty parameter to ThaliNotificationServer.start - pass

2016-03-21T12:06:42.017Z - info: 84. Make an HTTP request to /NotificationBeacons - pass

2016-03-21T12:06:42.017Z - info: 85. Make an HTTP request to /NotificationBeacons (no keys) - pass

2016-03-21T12:06:42.018Z - info: 86. Make an HTTP request to /NotificationBeaconsbefore calling start - pass
2016-03-21T12:06:42.019Z - info: 87. #testThaliPeerAction - test getters - pass

2016-03-21T12:06:42.020Z - info: 88. #testThaliPeerAction - start and kill - pass

2016-03-21T12:06:42.021Z - info: 89. #testThaliPeerAction - double start - pass
2016-03-21T12:06:42.021Z - info: 90. #testThaliPeerAction - start after kill - pass

2016-03-21T12:06:42.022Z - info: 91. #testThaliPeerAction - make sure ids are unique - pass

2016-03-21T12:06:42.023Z - info: 92. Test PeerConnectionInformation basics - pass
2016-03-21T12:06:42.024Z - info: 93. Test PeerDictionary basic functionality - pass

2016-03-21T12:06:42.024Z - info: 94. Test PeerDictionary with multiple entries. - pass

2016-03-21T12:06:42.025Z - info: 95. RESOLVED entries are removed before WAITING state entry. - pass
2016-03-21T12:06:42.026Z - info: 96. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass

2016-03-21T12:06:42.026Z - info: 97. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass
2016-03-21T12:06:42.027Z - info: 98. #ThaliPeerPoolInterface - bad enqueues - pass

2016-03-21T12:06:42.028Z - info: 99. #ThaliPeerPoolInterface - do not allow same object type - pass

2016-03-21T12:06:42.028Z - info: 100. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass
2016-03-21T12:06:42.029Z - info: 101. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent - pass

2016-03-21T12:06:42.030Z - info: 102. compareBufferArrays - pass

2016-03-21T12:06:42.031Z - info: 103. Call start twice and get error - pass
2016-03-21T12:06:42.031Z - info: 104. Start and make sure it runs - pass

2016-03-21T12:06:42.032Z - info: 105. Make sure getTimeWhenRun is right after start - pass

2016-03-21T12:06:42.033Z - info: 106. Make sure getTimeWhenRun is -1 after function is called - pass
2016-03-21T12:06:42.033Z - info: 107. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass

2016-03-21T12:06:42.034Z - info: 108. Test TransientState - pass

2016-03-21T12:06:42.035Z - info: 109. No peers and empty database - pass

2016-03-21T12:06:42.036Z - info: 110. One peer and empty DB - pass
2016-03-21T12:06:42.037Z - info: 111. One peer with _Local set behind current seq - pass
2016-03-21T12:06:42.037Z - info: 112. One peer with _Local set equal to current seq - pass
2016-03-21T12:06:42.038Z - info: 113. One peer with _Local set ahead of current seq (and no this should not happen) - pass
2016-03-21T12:06:42.039Z - info: 114. Three peers, one not in DB, one behind and one ahead - pass
2016-03-21T12:06:42.039Z - info: 115. More than maximum peers, make sure we only send maximum allowed - pass
2016-03-21T12:06:42.040Z - info: 116. two peers with empty DB, update the doc - pass
2016-03-21T12:06:42.041Z - info: 117. add doc and make sure tokens refresh when they expire - pass
2016-03-21T12:06:42.041Z - info: 118. start and stop and start and stop - pass
2016-03-21T12:06:42.042Z - info: 119. two identical starts in a row - pass
2016-03-21T12:06:42.042Z - info: 120. two different starts in a row - pass
2016-03-21T12:06:42.043Z - info: 121. two stops and a start and two stops - pass
2016-03-21T12:06:42.044Z - info: 122. we properly enqueue requests so no then needed - pass
2016-03-21T12:06:42.044Z - info: 123. test calculateSeqPointKeyId - pass
2016-03-21T12:06:42.045Z - info: 124. can create servers manager - pass
2016-03-21T12:06:42.045Z - info: 125. calling stop without start causes error - pass
2016-03-21T12:06:42.046Z - info: 126. can start/stop servers manager - pass
2016-03-21T12:06:42.046Z - info: 127. starting twice resolves with listening port - pass
2016-03-21T12:06:42.047Z - info: 128. terminateIncomingConnection will terminate a connection - pass
2016-03-21T12:06:42.047Z - info: 129. terminate an Outgoing connection will terminate the server - pass
2016-03-21T12:06:42.048Z - info: 130. terminate an Outgoing connection with wrong arguments is not harmful - pass
2016-03-21T12:06:42.049Z - info: 131. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass
2016-03-21T12:06:42.049Z - info: 132. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass
2016-03-21T12:06:42.050Z - info: 133. messages with invalid location or USN should be ignored - pass
2016-03-21T12:06:42.051Z - info: 134. verify that Thali-specific messages are filtered correctly - pass

2016-03-21T12:06:42.051Z - info: 135. #startListeningForAdvertisements should fail if start not called - pass
2016-03-21T12:06:42.052Z - info: 136. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-21T12:06:42.053Z - info: 137. #start should fail if called twice in a row - pass

2016-03-21T12:06:42.054Z - info: 138. should not be started after stop is called - pass
2016-03-21T12:06:42.054Z - info: 139. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass

2016-03-21T12:06:42.055Z - info: 140. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass

2016-03-21T12:06:42.056Z - info: 141. #startUpdateAdvertisingAndListening should start hosting given router object - pass
2016-03-21T12:06:42.057Z - info: 142. #stop can be called multiple times in a row - pass

2016-03-21T12:06:42.057Z - info: 143. #startListeningForAdvertisements can be called multiple times in a row - pass

2016-03-21T12:06:42.058Z - info: 144. #stopListeningForAdvertisements can be called multiple times in a row - pass
2016-03-21T12:06:42.059Z - info: 145. #stopAdvertisingAndListening can be called multiple times in a row - pass

2016-03-21T12:06:42.060Z - info: 146. functions are run from a queue in the right order - pass

2016-03-21T12:06:42.060Z - info: 147. #ThaliPeerPoolDefault - single action - pass

2016-03-21T12:06:42.061Z - info: 148. #ThaliPeerPoolDefault - multiple actions - pass
2016-03-21T12:06:42.062Z - info: 

-== END ==-

2016-03-21T12:06:42.920Z - debug: Socket disconnected: transport close 2 (LGE-LG-H815)

2016-03-21T12:06:42.994Z - debug: Socket disconnected: transport close 5 (samsung-SM-N910C)

2016-03-21T12:07:05.521Z - info: Running on ios test: 38. Can shift large amounts of data

2016-03-21T12:08:15.415Z - info: Running on ios test: 39. #startListeningForAdvertisements should fail if start not called

2016-03-21T12:08:15.780Z - info: Running on ios test: 40. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-21T12:08:16.242Z - info: Running on ios test: 41. should be able to call #stopListeningForAdvertisements many times

2016-03-21T12:08:16.777Z - info: Running on ios test: 42. should be able to call #startListeningForAdvertisements many times

2016-03-21T12:08:17.387Z - info: Running on ios test: 43. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-21T12:08:18.459Z - info: Running on ios test: 44. should be able to call #stopAdvertisingAndListening many times

2016-03-21T12:08:19.161Z - info: Running on ios test: 45. can get the network status before starting

2016-03-21T12:08:20.634Z - info: Running on ios test: 46. error returned with bad router

2016-03-21T12:08:21.398Z - info: Running on ios test: 47. all services are stopped when we call stop

2016-03-21T12:08:21.982Z - info: Running on ios test: 48. make sure terminateConnection is properly hooked up

2016-03-21T12:08:22.457Z - info: Running on ios test: 49. make sure terminateListener is properly hooked up

2016-03-21T12:08:22.802Z - info: Running on ios test: 50. make sure we actually call kill connections properly

2016-03-21T12:24:04.074Z - debug: Socket disconnected: transport close 1 (Apple-Iphone6-1)

2016-03-21T12:24:04.081Z - debug: Socket disconnected: transport close 0 (Apple-Iphone5-1)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

android : No Error

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
true

```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/625481246894564_More_thaliMobileNativeWrapper_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/625481246894564_More_thaliMobileNativeWrapper_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/625481246894564_More_thaliMobileNativeWrapper_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/625481246894564_More_thaliMobileNativeWrapper_vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/625481246894564_More_thaliMobileNativeWrapper_vjrantal/iOS_server.md)




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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/625481246894564_More_thaliMobileNativeWrapper_vjrantal/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/625481246894564_More_thaliMobileNativeWrapper_vjrantal/thali07_LGE-LG-H815.md)

####Node name: thali08
Console output:
```
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Android task is completed. [SUCCESS]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/625481246894564_More_thaliMobileNativeWrapper_vjrantal/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/625481246894564_More_thaliMobileNativeWrapper_vjrantal/thali08_motorola-Nexus 6.md)



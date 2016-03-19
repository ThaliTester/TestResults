#### Test 62548124ca582f4 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":9}}
2016-03-19T10:47:37.750Z - info: listening on *:3000

2016-03-19T10:47:38.767Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:0

2016-03-19T10:47:38.812Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:1

2016-03-19T10:47:39.053Z - debug: Device presented: samsung-SM-A300FU (android) unittest socket:2

2016-03-19T10:47:39.056Z - info: Required number of android devices presented (2)

2016-03-19T10:47:39.060Z - info: Starting unit test run for platform: android

2016-03-19T10:47:39.321Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:3

2016-03-19T10:47:39.323Z - info: Required number of ios devices presented (2)

2016-03-19T10:47:39.324Z - info: Starting unit test run for platform: ios

2016-03-19T10:47:39.736Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-19T10:47:40.069Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-19T10:47:40.380Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:5

2016-03-19T10:47:40.381Z - info: Discarding surplus device: Apple-Iphone6-1

2016-03-19T10:47:40.870Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-19T10:47:41.093Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-19T10:47:41.466Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-19T10:47:41.761Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-19T10:47:42.082Z - info: Running on ios test: 4. native server connections all up

2016-03-19T10:47:42.508Z - info: Running on android test: 4. native server connections all up

2016-03-19T10:47:42.930Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-19T10:47:43.027Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:4

2016-03-19T10:47:43.028Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-19T10:47:43.142Z - debug: Socket disconnected: transport close 5 (Apple-Iphone6-1)

2016-03-19T10:47:43.233Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-19T10:47:43.979Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-19T10:47:44.246Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-19T10:47:44.663Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-19T10:47:44.821Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-19T10:47:45.280Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-19T10:47:45.391Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-19T10:47:45.848Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-19T10:47:46.004Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-19T10:47:46.940Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-19T10:47:47.130Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-19T10:47:47.585Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-19T10:47:48.265Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-19T10:47:48.785Z - debug: Socket disconnected: transport close 4 (Apple-Iphone5s-1)

2016-03-19T10:47:49.582Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-19T10:47:49.660Z - info: Running on android test: 13. closeAll with promise

2016-03-19T10:47:50.836Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-19T10:47:50.930Z - info: Running on android test: 14. multiplex can send data

2016-03-19T10:47:51.699Z - info: Running on ios test: 13. closeAll with promise

2016-03-19T10:47:51.703Z - info: Running on android test: 15. enqueue and run in order

2016-03-19T10:47:52.369Z - info: Running on ios test: 14. multiplex can send data

2016-03-19T10:47:52.651Z - info: Running on android test: 16. enqueueAtTop and run backwards

2016-03-19T10:47:53.010Z - info: Running on ios test: 15. enqueue and run in order

2016-03-19T10:47:53.252Z - info: Running on android test: 17. mix enqueue and enqueueAtTop

2016-03-19T10:47:53.802Z - info: Running on ios test: 16. enqueueAtTop and run backwards

2016-03-19T10:47:53.982Z - info: Running on android test: 18. queues handled independently

2016-03-19T10:47:54.323Z - info: Running on ios test: 17. mix enqueue and enqueueAtTop

2016-03-19T10:47:54.483Z - info: Running on android test: 19. basic

2016-03-19T10:47:54.887Z - info: Running on android test: 20. another

2016-03-19T10:47:54.892Z - info: Running on ios test: 18. queues handled independently

2016-03-19T10:47:55.352Z - info: Running on android test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-19T10:47:55.405Z - info: Running on ios test: 19. basic

2016-03-19T10:47:55.812Z - info: Running on android test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-19T10:47:56.081Z - info: Running on ios test: 20. another

2016-03-19T10:47:56.378Z - info: Running on android test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-19T10:47:56.848Z - info: Running on ios test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-19T10:47:57.333Z - info: Running on ios test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-19T10:47:57.413Z - info: Running on android test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-19T10:47:57.879Z - info: Running on ios test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-19T10:47:58.259Z - info: Running on android test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-19T10:47:58.604Z - info: Running on ios test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-19T10:47:59.265Z - info: Running on android test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-19T10:47:59.420Z - info: Running on ios test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-19T10:47:59.747Z - info: Running on android test: 27. #start should fail if called twice in a row

2016-03-19T10:48:00.285Z - info: Running on android test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-19T10:48:00.877Z - info: Running on ios test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-19T10:48:01.504Z - info: Running on android test: 29. does not send duplicate availability changes

2016-03-19T10:48:01.855Z - info: Running on ios test: 27. #start should fail if called twice in a row

2016-03-19T10:48:01.921Z - info: Running on android test: 30. can get the network status

2016-03-19T10:48:02.445Z - info: Running on android test: 31. wifi peer is marked unavailable if announcements stop

2016-03-19T10:48:02.553Z - info: Running on ios test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-19T10:48:03.403Z - info: Running on ios test: 29. does not send duplicate availability changes

2016-03-19T10:48:03.916Z - info: Running on android test: 32. Can call start/stopListeningForAdvertisements

2016-03-19T10:48:03.938Z - info: Running on ios test: 30. can get the network status

2016-03-19T10:48:04.845Z - info: Running on android test: 33. Calling startListeningForAdvertisements twice is NOT an error

2016-03-19T10:48:05.639Z - info: Running on ios test: 31. wifi peer is marked unavailable if announcements stop

2016-03-19T10:48:06.283Z - info: Running on android test: 34. Can call start/stopUpdateAdvertisingAndListening

2016-03-19T10:48:06.761Z - info: Running on android test: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-19T10:48:07.416Z - info: Running on android test: 36. peerAvailabilityChange is called

2016-03-19T10:48:08.121Z - info: Running on ios test: 32. Can call start/stopListeningForAdvertisements

2016-03-19T10:48:08.579Z - info: Running on android test: 37. Can connect to a remote peer

2016-03-19T10:48:08.719Z - info: Running on ios test: 33. Calling startListeningForAdvertisements twice is NOT an error

2016-03-19T10:48:09.422Z - info: Running on ios test: 34. Can call start/stopUpdateAdvertisingAndListening

2016-03-19T10:48:10.366Z - info: Running on ios test: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-19T10:48:10.835Z - info: Running on ios test: 36. peerAvailabilityChange is called

2016-03-19T10:48:12.896Z - info: Running on ios test: 37. Can connect to a remote peer

2016-03-19T10:48:57.742Z - info: Running on android test: 38. Can shift large amounts of data

2016-03-19T10:49:02.375Z - info: Running on android test: 39. #startListeningForAdvertisements should fail if start not called

2016-03-19T10:49:03.129Z - info: Running on android test: 40. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-19T10:49:03.699Z - info: Running on android test: 41. should be able to call #stopListeningForAdvertisements many times

2016-03-19T10:49:04.257Z - info: Running on android test: 42. should be able to call #startListeningForAdvertisements many times

2016-03-19T10:49:05.121Z - info: Running on android test: 43. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-19T10:49:07.052Z - info: Running on android test: 44. should be able to call #stopAdvertisingAndListening many times

2016-03-19T10:49:07.438Z - info: Running on android test: 45. can get the network status before starting

2016-03-19T10:49:07.954Z - info: Running on android test: 46. error returned with bad router

2016-03-19T10:49:08.368Z - info: Running on android test: 47. can do HTTP requests between peers

2016-03-19T10:49:14.912Z - info: Running on android test: 48. Can do requests between peers after start and stop

2016-03-19T10:49:15.579Z - info: Running on android test: 49. We successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-19T10:49:16.160Z - info: Running on android test: 50. Test BEACONS_RETRIEVED_AND_PARSED locally

2016-03-19T10:49:16.768Z - info: Running on android test: 51. Test HTTP_BAD_RESPONSE locally

2016-03-19T10:49:17.663Z - info: Running on android test: 52. Test NETWORK_PROBLEM locally

2016-03-19T10:49:19.339Z - info: Running on android test: 53. Test timeout locally

2016-03-19T10:49:20.798Z - info: Running on android test: 54. Call the start two times

2016-03-19T10:49:21.383Z - info: Running on android test: 55. Call the kill before calling the start

2016-03-19T10:49:21.782Z - info: Running on android test: 56. Call the kill immediately after the start

2016-03-19T10:49:22.567Z - info: Running on android test: 57. Call the kill while waiting a response from the server

2016-03-19T10:49:25.534Z - info: Running on android test: 58. Test to exceed the max content size locally

2016-03-19T10:49:26.089Z - info: Running on android test: 59. Close the server socket while the client is waiting a response from the server. Local test.

2016-03-19T10:49:28.589Z - info: Running on android test: 60. Close the client socket while the client is waiting a response from the server. Local test.

2016-03-19T10:49:31.259Z - info: Running on android test: 61. #generatePreambleAndBeacons bad args

2016-03-19T10:49:31.757Z - info: Running on android test: 62. #generatePreambleAndBeacons empty keys to notify

2016-03-19T10:49:32.351Z - info: Running on android test: 63. #generatePreambleAndBeacons multiple keys to notify

2016-03-19T10:49:33.137Z - info: Running on android test: 64. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-19T10:49:33.614Z - info: Running on android test: 65. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-19T10:49:34.153Z - info: Running on android test: 66. #parseBeacons expiration out of range lower

2016-03-19T10:49:34.827Z - info: Running on android test: 67. #parseBeacons expiration out of range lower

2016-03-19T10:49:35.681Z - info: Running on android test: 68. #parseBeacons no beacons returns null

2016-03-19T10:49:36.247Z - info: Running on android test: 69. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-19T10:49:36.779Z - info: Running on android test: 70. #parseBeacons addressBookCallback fails decrypt

2016-03-19T10:49:37.358Z - info: Running on android test: 71. #parseBeacons addressBookCallback returns no matches

2016-03-19T10:49:38.141Z - info: Running on android test: 72. #parseBeacons addressBookCallback returns spurious match

2016-03-19T10:49:39.126Z - info: Running on android test: 73. #parseBeacons addressBookCallback returns public key

2016-03-19T10:49:40.435Z - info: Running on android test: 74. validate generatePskIdentityField

2016-03-19T10:49:40.846Z - info: Running on android test: 75. validate generatePskSecret

2016-03-19T10:49:41.418Z - info: Running on android test: 76. Start and stop ThaliNotificationServer

2016-03-19T10:49:42.016Z - info: Running on android test: 77. Pass an empty array to ThaliNotificationServer.start

2016-03-19T10:49:42.538Z - info: Running on android test: 78. Pass a string to ThaliNotificationServer.start

2016-03-19T10:49:43.330Z - info: Running on android test: 79. Pass an empty parameter to ThaliNotificationServer.start

2016-03-19T10:49:43.923Z - info: Running on android test: 80. Make an HTTP request to /NotificationBeacons

2016-03-19T10:49:44.601Z - info: Running on android test: 81. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-19T10:49:45.011Z - info: Running on android test: 82. Make an HTTP request to /NotificationBeaconsbefore calling start

2016-03-19T10:49:45.527Z - info: Running on android test: 83. #testThaliPeerAction - test getters

2016-03-19T10:49:45.848Z - info: Running on android test: 84. #testThaliPeerAction - start and kill

2016-03-19T10:49:46.168Z - info: Running on android test: 85. #testThaliPeerAction - double start

2016-03-19T10:49:46.465Z - info: Running on android test: 86. #testThaliPeerAction - start after kill

2016-03-19T10:49:46.825Z - info: Running on android test: 87. #testThaliPeerAction - make sure ids are unique

2016-03-19T10:49:47.190Z - info: Running on android test: 88. Test PeerConnectionInformation basics

2016-03-19T10:49:47.754Z - info: Running on android test: 89. Test PeerDictionary basic functionality

2016-03-19T10:49:48.653Z - info: Running on android test: 90. Test PeerDictionary with multiple entries.

2016-03-19T10:49:51.627Z - info: Running on android test: 91. RESOLVED entries are removed before WAITING state entry.

2016-03-19T10:49:53.794Z - info: Running on android test: 92. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-19T10:49:55.366Z - info: Running on android test: 93. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-19T10:49:56.893Z - info: Running on android test: 94. #ThaliPeerPoolInterface - bad enqueues

2016-03-19T10:49:57.342Z - info: Running on android test: 95. #ThaliPeerPoolInterface - do not allow same object type

2016-03-19T10:49:58.180Z - info: Running on android test: 96. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-19T10:49:59.304Z - info: Running on android test: 97. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent

2016-03-19T10:49:59.844Z - info: Running on android test: 98. compareBufferArrays

2016-03-19T10:50:00.274Z - info: Running on android test: 99. Call start twice and get error

2016-03-19T10:50:00.766Z - info: Running on android test: 100. Start and make sure it runs

2016-03-19T10:50:02.116Z - info: Running on android test: 101. Make sure getTimeWhenRun is right after start

2016-03-19T10:50:03.302Z - info: Running on android test: 102. Make sure getTimeWhenRun is -1 after function is called

2016-03-19T10:50:03.911Z - info: Running on android test: 103. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-19T10:50:04.118Z - info: Running on ios test: 38. Can shift large amounts of data

2016-03-19T10:50:04.741Z - info: Running on android test: 104. Test TransientState

2016-03-19T10:50:05.287Z - info: Running on android test: 105. No peers and empty database

2016-03-19T10:50:06.043Z - info: Running on android test: 106. One peer and empty DB

2016-03-19T10:50:07.043Z - info: Running on android test: 107. One peer with _Local set behind current seq

2016-03-19T10:50:08.314Z - info: Running on android test: 108. One peer with _Local set equal to current seq

2016-03-19T10:50:08.944Z - info: Running on android test: 109. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-19T10:50:09.537Z - info: Running on android test: 110. Three peers, one not in DB, one behind and one ahead

2016-03-19T10:50:10.374Z - info: Running on android test: 111. More than maximum peers, make sure we only send maximum allowed

2016-03-19T10:50:12.007Z - info: Running on android test: 112. two peers with empty DB, update the doc

2016-03-19T10:50:12.748Z - info: Running on android test: 113. add doc and make sure tokens refresh when they expire

2016-03-19T10:50:13.793Z - info: Running on android test: 114. start and stop and start and stop

2016-03-19T10:50:15.205Z - info: Running on android test: 115. two identical starts in a row

2016-03-19T10:50:16.862Z - info: Running on android test: 116. two different starts in a row

2016-03-19T10:50:17.699Z - info: Running on android test: 117. two stops and a start and two stops

2016-03-19T10:50:19.008Z - info: Running on android test: 118. we properly enqueue requests so no then needed

2016-03-19T10:50:20.216Z - info: Running on android test: 119. test calculateSeqPointKeyId

2016-03-19T10:50:21.110Z - info: Running on android test: 120. can create servers manager

2016-03-19T10:50:21.561Z - info: Running on android test: 121. calling stop without start causes error

2016-03-19T10:50:22.319Z - info: Running on android test: 122. can start/stop servers manager

2016-03-19T10:50:23.180Z - info: Running on android test: 123. starting twice resolves with listening port

2016-03-19T10:50:23.863Z - info: Running on android test: 124. terminateIncomingConnection will terminate a connection

2016-03-19T10:50:24.740Z - info: Running on android test: 125. terminate an Outgoing connection will terminate the server

2016-03-19T10:50:25.892Z - info: Running on android test: 126. terminate an Outgoing connection with wrong arguments is not harmful

2016-03-19T10:50:27.017Z - info: Running on android test: 127. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-19T10:50:27.855Z - info: Running on android test: 128. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-19T10:50:28.607Z - info: Running on android test: 129. messages with invalid location or USN should be ignored

2016-03-19T10:50:29.119Z - info: Running on android test: 130. verify that Thali-specific messages are filtered correctly

2016-03-19T10:50:29.737Z - info: Running on android test: 131. #startListeningForAdvertisements should fail if start not called

2016-03-19T10:50:30.734Z - info: Running on android test: 132. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-19T10:50:31.369Z - info: Running on android test: 133. #start should fail if called twice in a row

2016-03-19T10:50:31.846Z - info: Running on android test: 134. should not be started after stop is called

2016-03-19T10:50:32.367Z - info: Running on android test: 135. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-19T10:50:32.794Z - info: Running on android test: 136. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-19T10:50:33.800Z - info: Running on android test: 137. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-19T10:50:34.400Z - info: Running on android test: 138. #stop can be called multiple times in a row

2016-03-19T10:50:35.008Z - info: Running on android test: 139. #startListeningForAdvertisements can be called multiple times in a row

2016-03-19T10:50:35.484Z - info: Running on android test: 140. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-19T10:50:35.902Z - info: Running on android test: 141. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-19T10:50:36.357Z - info: Running on android test: 142. functions are run from a queue in the right order

2016-03-19T10:50:36.652Z - info: Running on android test: 143. #ThaliPeerPoolDefault - single action

2016-03-19T10:50:37.099Z - info: Running on android test: 144. #ThaliPeerPoolDefault - multiple actions

2016-03-19T10:50:37.569Z - info: Test run on android complete

2016-03-19T10:50:37.571Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-19T10:50:37.573Z - info: PLATFORM: android

2016-03-19T10:50:37.573Z - info: RESULT: PASS

2016-03-19T10:50:37.574Z - info: 144 of 144 tests completed
2016-03-19T10:50:37.575Z - info: 144/144 passed (0 failures)

2016-03-19T10:50:37.576Z - info: --- Test Details ---



2016-03-19T10:50:37.577Z - info: 1. calling createNativeListener directly rejects - pass
2016-03-19T10:50:37.577Z - info: 2. emits incomingConnectionState - pass

2016-03-19T10:50:37.578Z - info: 3. emits routerPortConnectionFailed - pass

2016-03-19T10:50:37.579Z - info: 4. native server connections all up - pass
2016-03-19T10:50:37.579Z - info: 5. native server - closing incoming stream cleans outgoing socket - pass

2016-03-19T10:50:37.580Z - info: 6. native server - closing incoming connection cleans outgoing socket - pass
2016-03-19T10:50:37.581Z - info: 7. native server - closing outgoing socket cleans associated mux stream - pass

2016-03-19T10:50:37.581Z - info: 8. native server - closing the whole server cleans everything up - pass
2016-03-19T10:50:37.582Z - info: 9. native server - we can get a ton of connections and data through and still clean up the server completely - pass

2016-03-19T10:50:37.582Z - info: 10. native server - simulate mux failure, make sure everything is cleaned up - pass

2016-03-19T10:50:37.583Z - info: 11. native server - timing out the incoming connection cleans everything up - pass
2016-03-19T10:50:37.584Z - info: 12. closeAll can close even when connections open - pass

2016-03-19T10:50:37.584Z - info: 13. closeAll with promise - pass
2016-03-19T10:50:37.585Z - info: 14. multiplex can send data - pass

2016-03-19T10:50:37.586Z - info: 15. enqueue and run in order - pass

2016-03-19T10:50:37.586Z - info: 16. enqueueAtTop and run backwards - pass
2016-03-19T10:50:37.587Z - info: 17. mix enqueue and enqueueAtTop - pass

2016-03-19T10:50:37.587Z - info: 18. queues handled independently - pass
2016-03-19T10:50:37.588Z - info: 19. basic - pass

2016-03-19T10:50:37.589Z - info: 20. another - pass

2016-03-19T10:50:37.589Z - info: 21. #startListeningForAdvertisements should fail if start not called - pass
2016-03-19T10:50:37.590Z - info: 22. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-19T10:50:37.591Z - info: 23. should be able to call #stopListeningForAdvertisements many times - pass
2016-03-19T10:50:37.591Z - info: 24. should be able to call #startListeningForAdvertisements many times - pass

2016-03-19T10:50:37.592Z - info: 25. should be able to call #startUpdateAdvertisingAndListening many times - pass
2016-03-19T10:50:37.592Z - info: 26. should be able to call #stopAdvertisingAndListening many times - pass

2016-03-19T10:50:37.593Z - info: 27. #start should fail if called twice in a row - pass

2016-03-19T10:50:37.594Z - info: 28. does not emit duplicate discoveryAdvertisingStateUpdate - pass
2016-03-19T10:50:37.594Z - info: 29. does not send duplicate availability changes - pass

2016-03-19T10:50:37.595Z - info: 30. can get the network status - pass
2016-03-19T10:50:37.595Z - info: 31. wifi peer is marked unavailable if announcements stop - pass

2016-03-19T10:50:37.596Z - info: 32. Can call start/stopListeningForAdvertisements - pass

2016-03-19T10:50:37.597Z - info: 33. Calling startListeningForAdvertisements twice is NOT an error - pass
2016-03-19T10:50:37.597Z - info: 34. Can call start/stopUpdateAdvertisingAndListening - pass

2016-03-19T10:50:37.598Z - info: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error - pass
2016-03-19T10:50:37.598Z - info: 36. peerAvailabilityChange is called - pass

2016-03-19T10:50:37.599Z - info: 37. Can connect to a remote peer - pass
2016-03-19T10:50:37.600Z - info: 38. Can shift large amounts of data - pass

2016-03-19T10:50:37.600Z - info: 39. #startListeningForAdvertisements should fail if start not called - pass

2016-03-19T10:50:37.601Z - info: 40. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-19T10:50:37.602Z - info: 41. should be able to call #stopListeningForAdvertisements many times - pass

2016-03-19T10:50:37.602Z - info: 42. should be able to call #startListeningForAdvertisements many times - pass
2016-03-19T10:50:37.603Z - info: 43. should be able to call #startUpdateAdvertisingAndListening many times - pass

2016-03-19T10:50:37.603Z - info: 44. should be able to call #stopAdvertisingAndListening many times - pass

2016-03-19T10:50:37.604Z - info: 45. can get the network status before starting - pass
2016-03-19T10:50:37.605Z - info: 46. error returned with bad router - pass

2016-03-19T10:50:37.605Z - info: 47. can do HTTP requests between peers - pass
2016-03-19T10:50:37.606Z - info: 48. Can do requests between peers after start and stop - pass

2016-03-19T10:50:37.607Z - info: 49. We successfully receive and replay discoveryAdvertisingStateUpdate - pass
2016-03-19T10:50:37.607Z - info: 50. Test BEACONS_RETRIEVED_AND_PARSED locally - pass

2016-03-19T10:50:37.608Z - info: 51. Test HTTP_BAD_RESPONSE locally - pass

2016-03-19T10:50:37.608Z - info: 52. Test NETWORK_PROBLEM locally - pass
2016-03-19T10:50:37.609Z - info: 53. Test timeout locally - pass

2016-03-19T10:50:37.610Z - info: 54. Call the start two times - pass
2016-03-19T10:50:37.610Z - info: 55. Call the kill before calling the start - pass

2016-03-19T10:50:37.611Z - info: 56. Call the kill immediately after the start - pass

2016-03-19T10:50:37.612Z - info: 57. Call the kill while waiting a response from the server - pass
2016-03-19T10:50:37.612Z - info: 58. Test to exceed the max content size locally - pass

2016-03-19T10:50:37.613Z - info: 59. Close the server socket while the client is waiting a response from the server. Local test. - pass

2016-03-19T10:50:37.614Z - info: 60. Close the client socket while the client is waiting a response from the server. Local test. - pass
2016-03-19T10:50:37.614Z - info: 61. #generatePreambleAndBeacons bad args - pass

2016-03-19T10:50:37.615Z - info: 62. #generatePreambleAndBeacons empty keys to notify - pass
2016-03-19T10:50:37.615Z - info: 63. #generatePreambleAndBeacons multiple keys to notify - pass
2016-03-19T10:50:37.616Z - info: 64. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass
2016-03-19T10:50:37.617Z - info: 65. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass
2016-03-19T10:50:37.617Z - info: 66. #parseBeacons expiration out of range lower - pass

2016-03-19T10:50:37.618Z - info: 67. #parseBeacons expiration out of range lower - pass
2016-03-19T10:50:37.619Z - info: 68. #parseBeacons no beacons returns null - pass

2016-03-19T10:50:37.619Z - info: 69. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass
2016-03-19T10:50:37.620Z - info: 70. #parseBeacons addressBookCallback fails decrypt - pass

2016-03-19T10:50:37.620Z - info: 71. #parseBeacons addressBookCallback returns no matches - pass
2016-03-19T10:50:37.621Z - info: 72. #parseBeacons addressBookCallback returns spurious match - pass

2016-03-19T10:50:37.622Z - info: 73. #parseBeacons addressBookCallback returns public key - pass

2016-03-19T10:50:37.622Z - info: 74. validate generatePskIdentityField - pass
2016-03-19T10:50:37.623Z - info: 75. validate generatePskSecret - pass

2016-03-19T10:50:37.624Z - info: 76. Start and stop ThaliNotificationServer - pass
2016-03-19T10:50:37.624Z - info: 77. Pass an empty array to ThaliNotificationServer.start - pass

2016-03-19T10:50:37.625Z - info: 78. Pass a string to ThaliNotificationServer.start - pass
2016-03-19T10:50:37.625Z - info: 79. Pass an empty parameter to ThaliNotificationServer.start - pass

2016-03-19T10:50:37.626Z - info: 80. Make an HTTP request to /NotificationBeacons - pass

2016-03-19T10:50:37.627Z - info: 81. Make an HTTP request to /NotificationBeacons (no keys) - pass
2016-03-19T10:50:37.627Z - info: 82. Make an HTTP request to /NotificationBeaconsbefore calling start - pass

2016-03-19T10:50:37.628Z - info: 83. #testThaliPeerAction - test getters - pass
2016-03-19T10:50:37.629Z - info: 84. #testThaliPeerAction - start and kill - pass

2016-03-19T10:50:37.629Z - info: 85. #testThaliPeerAction - double start - pass
2016-03-19T10:50:37.630Z - info: 86. #testThaliPeerAction - start after kill - pass

2016-03-19T10:50:37.630Z - info: 87. #testThaliPeerAction - make sure ids are unique - pass
2016-03-19T10:50:37.631Z - info: 88. Test PeerConnectionInformation basics - pass

2016-03-19T10:50:37.632Z - info: 89. Test PeerDictionary basic functionality - pass
2016-03-19T10:50:37.632Z - info: 90. Test PeerDictionary with multiple entries. - pass

2016-03-19T10:50:37.633Z - info: 91. RESOLVED entries are removed before WAITING state entry. - pass
2016-03-19T10:50:37.637Z - info: 92. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass
2016-03-19T10:50:37.637Z - info: 93. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass
2016-03-19T10:50:37.638Z - info: 94. #ThaliPeerPoolInterface - bad enqueues - pass
2016-03-19T10:50:37.639Z - info: 95. #ThaliPeerPoolInterface - do not allow same object type - pass
2016-03-19T10:50:37.639Z - info: 96. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass
2016-03-19T10:50:37.640Z - info: 97. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent - pass
2016-03-19T10:50:37.640Z - info: 98. compareBufferArrays - pass
2016-03-19T10:50:37.641Z - info: 99. Call start twice and get error - pass
2016-03-19T10:50:37.641Z - info: 100. Start and make sure it runs - pass
2016-03-19T10:50:37.642Z - info: 101. Make sure getTimeWhenRun is right after start - pass
2016-03-19T10:50:37.642Z - info: 102. Make sure getTimeWhenRun is -1 after function is called - pass
2016-03-19T10:50:37.643Z - info: 103. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass
2016-03-19T10:50:37.643Z - info: 104. Test TransientState - pass
2016-03-19T10:50:37.644Z - info: 105. No peers and empty database - pass
2016-03-19T10:50:37.644Z - info: 106. One peer and empty DB - pass
2016-03-19T10:50:37.645Z - info: 107. One peer with _Local set behind current seq - pass
2016-03-19T10:50:37.645Z - info: 108. One peer with _Local set equal to current seq - pass
2016-03-19T10:50:37.646Z - info: 109. One peer with _Local set ahead of current seq (and no this should not happen) - pass
2016-03-19T10:50:37.646Z - info: 110. Three peers, one not in DB, one behind and one ahead - pass

2016-03-19T10:50:37.647Z - info: 111. More than maximum peers, make sure we only send maximum allowed - pass
2016-03-19T10:50:37.648Z - info: 112. two peers with empty DB, update the doc - pass

2016-03-19T10:50:37.648Z - info: 113. add doc and make sure tokens refresh when they expire - pass
2016-03-19T10:50:37.649Z - info: 114. start and stop and start and stop - pass

2016-03-19T10:50:37.650Z - info: 115. two identical starts in a row - pass
2016-03-19T10:50:37.650Z - info: 116. two different starts in a row - pass

2016-03-19T10:50:37.651Z - info: 117. two stops and a start and two stops - pass

2016-03-19T10:50:37.652Z - info: 118. we properly enqueue requests so no then needed - pass
2016-03-19T10:50:37.652Z - info: 119. test calculateSeqPointKeyId - pass

2016-03-19T10:50:37.653Z - info: 120. can create servers manager - pass
2016-03-19T10:50:37.653Z - info: 121. calling stop without start causes error - pass

2016-03-19T10:50:37.654Z - info: 122. can start/stop servers manager - pass
2016-03-19T10:50:37.655Z - info: 123. starting twice resolves with listening port - pass

2016-03-19T10:50:37.655Z - info: 124. terminateIncomingConnection will terminate a connection - pass
2016-03-19T10:50:37.656Z - info: 125. terminate an Outgoing connection will terminate the server - pass

2016-03-19T10:50:37.656Z - info: 126. terminate an Outgoing connection with wrong arguments is not harmful - pass

2016-03-19T10:50:37.657Z - info: 127. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass
2016-03-19T10:50:37.658Z - info: 128. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-03-19T10:50:37.658Z - info: 129. messages with invalid location or USN should be ignored - pass
2016-03-19T10:50:37.659Z - info: 130. verify that Thali-specific messages are filtered correctly - pass

2016-03-19T10:50:37.660Z - info: 131. #startListeningForAdvertisements should fail if start not called - pass

2016-03-19T10:50:37.660Z - info: 132. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-19T10:50:37.661Z - info: 133. #start should fail if called twice in a row - pass

2016-03-19T10:50:37.662Z - info: 134. should not be started after stop is called - pass
2016-03-19T10:50:37.662Z - info: 135. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass

2016-03-19T10:50:37.663Z - info: 136. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass

2016-03-19T10:50:37.663Z - info: 137. #startUpdateAdvertisingAndListening should start hosting given router object - pass
2016-03-19T10:50:37.664Z - info: 138. #stop can be called multiple times in a row - pass

2016-03-19T10:50:37.665Z - info: 139. #startListeningForAdvertisements can be called multiple times in a row - pass
2016-03-19T10:50:37.665Z - info: 140. #stopListeningForAdvertisements can be called multiple times in a row - pass

2016-03-19T10:50:37.666Z - info: 141. #stopAdvertisingAndListening can be called multiple times in a row - pass
2016-03-19T10:50:37.666Z - info: 142. functions are run from a queue in the right order - pass

2016-03-19T10:50:37.667Z - info: 143. #ThaliPeerPoolDefault - single action - pass
2016-03-19T10:50:37.668Z - info: 144. #ThaliPeerPoolDefault - multiple actions - pass

2016-03-19T10:50:37.668Z - info: 

-== END ==-

2016-03-19T10:50:38.577Z - debug: Socket disconnected: transport close 1 (samsung-SM-N910C)

2016-03-19T10:51:12.647Z - info: Running on ios test: 39. #startListeningForAdvertisements should fail if start not called

2016-03-19T10:51:13.859Z - info: Running on ios test: 40. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-19T10:51:14.950Z - info: Running on ios test: 41. should be able to call #stopListeningForAdvertisements many times

2016-03-19T10:51:16.943Z - info: Running on ios test: 42. should be able to call #startListeningForAdvertisements many times

2016-03-19T10:52:43.339Z - debug: Socket disconnected: ping timeout 3 (Apple-Iphone5-1)

2016-03-19T11:06:07.568Z - debug: Socket disconnected: transport close 0 (Apple-IpadAir2-1)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/62548124ca582f4_More_thaliMobileNativeWrapper_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/62548124ca582f4_More_thaliMobileNativeWrapper_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/62548124ca582f4_More_thaliMobileNativeWrapper_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/62548124ca582f4_More_thaliMobileNativeWrapper_vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/62548124ca582f4_More_thaliMobileNativeWrapper_vjrantal/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  f56ad48d Test has  SUCCEEDED
Device test finished on f56ad48d 
Android task is completed. [SUCCESS]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62548124ca582f4_More_thaliMobileNativeWrapper_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:0 
child process exited with code 0 on device 7970f88c 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62548124ca582f4_More_thaliMobileNativeWrapper_vjrantal/thali02_samsung-SM-A300FU.md)

[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/62548124ca582f4_More_thaliMobileNativeWrapper_vjrantal/thali02_LGE-LG-D722.md)

####Node name: thali03
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Android task is completed. [SUCCESS]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/62548124ca582f4_More_thaliMobileNativeWrapper_vjrantal/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on ZX1C223JKW 
Android task is completed. [SUCCESS]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/62548124ca582f4_More_thaliMobileNativeWrapper_vjrantal/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:0 
child process exited with code 0 on device LGH8153b36be34 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/62548124ca582f4_More_thaliMobileNativeWrapper_vjrantal/thali05_LGE-LG-H815.md)

####Node name: thali06
Console output:
```
STOP log received from  FA55PYS00566 Test has  SUCCEEDED
Device test finished on FA55PYS00566 
Android task is completed. [SUCCESS]
```
[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/62548124ca582f4_More_thaliMobileNativeWrapper_vjrantal/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
STOP log received from  4db5c8cc Test has  SUCCEEDED
Device test finished on 4db5c8cc 
Android task is completed. [SUCCESS]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62548124ca582f4_More_thaliMobileNativeWrapper_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:0 
child process exited with code 0 on device 4325e43f 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62548124ca582f4_More_thaliMobileNativeWrapper_vjrantal/thali08_samsung-SM-A300FU.md)





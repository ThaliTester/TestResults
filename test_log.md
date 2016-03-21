#### Test 62548124bd1cdb6 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":9}}
2016-03-21T06:35:50.646Z - info: listening on *:3000

2016-03-21T06:35:52.696Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:0

2016-03-21T06:35:52.710Z - debug: Device presented: samsung-SM-A500FU (android) unittest socket:1

2016-03-21T06:35:53.632Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:2

2016-03-21T06:35:53.636Z - info: Required number of android devices presented (2)

2016-03-21T06:35:53.639Z - info: Starting unit test run for platform: android

2016-03-21T06:35:54.232Z - debug: Device presented: HTC-HTC One M8s (android) unittest socket:3

2016-03-21T06:35:54.234Z - info: Discarding surplus device: HTC-HTC One M8s

2016-03-21T06:35:54.328Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:4

2016-03-21T06:35:54.330Z - info: Required number of ios devices presented (2)

2016-03-21T06:35:54.331Z - info: Starting unit test run for platform: ios

2016-03-21T06:35:54.481Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-21T06:35:54.637Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:5

2016-03-21T06:35:54.638Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-21T06:35:54.921Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-21T06:35:54.944Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-21T06:35:54.973Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:6

2016-03-21T06:35:54.974Z - info: Discarding surplus device: LGE-LG-H815

2016-03-21T06:35:55.226Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-21T06:35:55.381Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-21T06:35:55.586Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-21T06:35:55.648Z - debug: Socket disconnected: transport close 3 (HTC-HTC One M8s)

2016-03-21T06:35:55.688Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:7

2016-03-21T06:35:55.689Z - info: Discarding surplus device: Apple-Iphone5-1

2016-03-21T06:35:55.801Z - info: Running on android test: 4. native server connections all up

2016-03-21T06:35:55.838Z - debug: Socket disconnected: transport close 6 (LGE-LG-H815)

2016-03-21T06:35:55.961Z - info: Running on ios test: 4. native server connections all up

2016-03-21T06:35:56.169Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-21T06:35:56.609Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-21T06:35:56.929Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-21T06:35:57.172Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-21T06:35:57.195Z - debug: Socket disconnected: transport close 5 (Apple-Iphone5s-1)

2016-03-21T06:35:57.449Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-21T06:35:57.651Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-21T06:35:58.081Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-21T06:35:58.143Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-21T06:35:58.598Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-21T06:35:58.604Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-21T06:35:58.893Z - debug: Socket disconnected: transport close 7 (Apple-Iphone5-1)

2016-03-21T06:35:59.522Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-21T06:35:59.889Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-21T06:36:00.325Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-21T06:36:00.777Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-21T06:36:01.136Z - info: Running on android test: 13. closeAll with promise

2016-03-21T06:36:01.558Z - info: Running on android test: 14. multiplex can send data

2016-03-21T06:36:01.885Z - info: Running on android test: 15. enqueue and run in order

2016-03-21T06:36:02.520Z - info: Running on android test: 16. enqueueAtTop and run backwards

2016-03-21T06:36:03.012Z - info: Running on android test: 17. mix enqueue and enqueueAtTop

2016-03-21T06:36:03.682Z - info: Running on android test: 18. queues handled independently

2016-03-21T06:36:04.051Z - info: Running on android test: 19. basic

2016-03-21T06:36:04.322Z - info: Running on android test: 20. another

2016-03-21T06:36:04.957Z - info: Running on android test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-21T06:36:05.287Z - info: Running on android test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-21T06:36:05.628Z - info: Running on android test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-21T06:36:06.091Z - info: Running on android test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-21T06:36:06.756Z - info: Running on android test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-21T06:36:07.476Z - info: Running on android test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-21T06:36:07.608Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-21T06:36:08.463Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-21T06:36:08.466Z - info: Running on android test: 27. #start should fail if called twice in a row

2016-03-21T06:36:08.843Z - info: Running on ios test: 13. closeAll with promise

2016-03-21T06:36:08.904Z - info: Running on android test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-21T06:36:09.252Z - info: Running on ios test: 14. multiplex can send data

2016-03-21T06:36:09.604Z - info: Running on android test: 29. does not send duplicate availability changes

2016-03-21T06:36:09.611Z - info: Running on ios test: 15. enqueue and run in order

2016-03-21T06:36:10.122Z - info: Running on android test: 30. can get the network status

2016-03-21T06:36:10.381Z - info: Running on ios test: 16. enqueueAtTop and run backwards

2016-03-21T06:36:10.744Z - info: Running on android test: 31. wifi peer is marked unavailable if announcements stop

2016-03-21T06:36:10.975Z - info: Running on ios test: 17. mix enqueue and enqueueAtTop

2016-03-21T06:36:11.519Z - info: Running on ios test: 18. queues handled independently

2016-03-21T06:36:12.207Z - info: Running on android test: 32. Can call start/stopListeningForAdvertisements

2016-03-21T06:36:12.348Z - info: Running on ios test: 19. basic

2016-03-21T06:36:12.599Z - info: Running on android test: 33. Calling startListeningForAdvertisements twice is NOT an error

2016-03-21T06:36:12.725Z - info: Running on ios test: 20. another

2016-03-21T06:36:13.052Z - info: Running on ios test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-21T06:36:13.243Z - info: Running on android test: 34. Can call start/stopUpdateAdvertisingAndListening

2016-03-21T06:36:13.360Z - info: Running on ios test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-21T06:36:13.724Z - info: Running on ios test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-21T06:36:13.927Z - info: Running on android test: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-21T06:36:14.142Z - info: Running on ios test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-21T06:36:14.712Z - info: Running on ios test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-21T06:36:14.758Z - info: Running on android test: 36. peerAvailabilityChange is called

2016-03-21T06:36:15.364Z - info: Running on ios test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-21T06:36:18.401Z - info: Running on android test: 37. Can connect to a remote peer

2016-03-21T06:36:20.213Z - info: Running on ios test: 27. #start should fail if called twice in a row

2016-03-21T06:36:20.660Z - info: Running on ios test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-21T06:36:21.179Z - info: Running on ios test: 29. does not send duplicate availability changes

2016-03-21T06:36:21.741Z - info: Running on ios test: 30. can get the network status

2016-03-21T06:36:24.653Z - info: Running on ios test: 31. wifi peer is marked unavailable if announcements stop

2016-03-21T06:36:26.356Z - info: Running on ios test: 32. Can call start/stopListeningForAdvertisements

2016-03-21T06:36:26.807Z - info: Running on ios test: 33. Calling startListeningForAdvertisements twice is NOT an error

2016-03-21T06:36:27.378Z - info: Running on ios test: 34. Can call start/stopUpdateAdvertisingAndListening

2016-03-21T06:36:28.298Z - info: Running on ios test: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-21T06:36:29.020Z - info: Running on ios test: 36. peerAvailabilityChange is called

2016-03-21T06:36:29.556Z - info: Running on android test: 38. Can shift large amounts of data

2016-03-21T06:36:31.498Z - info: Running on ios test: 37. Can connect to a remote peer

2016-03-21T06:36:35.059Z - info: Running on android test: 39. #startListeningForAdvertisements should fail if start not called

2016-03-21T06:36:35.858Z - info: Running on android test: 40. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-21T06:36:36.489Z - info: Running on android test: 41. should be able to call #stopListeningForAdvertisements many times

2016-03-21T06:36:37.223Z - info: Running on android test: 42. should be able to call #startListeningForAdvertisements many times

2016-03-21T06:36:39.529Z - info: Running on android test: 43. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-21T06:36:40.303Z - info: Running on android test: 44. should be able to call #stopAdvertisingAndListening many times

2016-03-21T06:36:40.931Z - info: Running on android test: 45. can get the network status before starting

2016-03-21T06:36:41.311Z - info: Running on android test: 46. error returned with bad router

2016-03-21T06:36:41.678Z - info: Running on android test: 47. can do HTTP requests between peers

2016-03-21T06:36:57.472Z - info: Running on android test: 48. Can do requests between peers after start and stop

2016-03-21T06:36:57.877Z - info: Running on android test: 49. We successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-21T06:36:58.278Z - info: Running on android test: 50. Test BEACONS_RETRIEVED_AND_PARSED locally

2016-03-21T06:36:58.825Z - info: Running on android test: 51. Test HTTP_BAD_RESPONSE locally

2016-03-21T06:36:59.397Z - info: Running on android test: 52. Test NETWORK_PROBLEM locally

2016-03-21T06:37:00.202Z - info: Running on android test: 53. Test timeout locally

2016-03-21T06:37:01.653Z - info: Running on android test: 54. Call the start two times

2016-03-21T06:37:02.106Z - info: Running on android test: 55. Call the kill before calling the start

2016-03-21T06:37:02.441Z - info: Running on android test: 56. Call the kill immediately after the start

2016-03-21T06:37:02.715Z - info: Running on android test: 57. Call the kill while waiting a response from the server

2016-03-21T06:37:05.066Z - info: Running on android test: 58. Test to exceed the max content size locally

2016-03-21T06:37:05.467Z - info: Running on android test: 59. Close the server socket while the client is waiting a response from the server. Local test.

2016-03-21T06:37:07.821Z - info: Running on android test: 60. Close the client socket while the client is waiting a response from the server. Local test.

2016-03-21T06:37:10.530Z - info: Running on android test: 61. #generatePreambleAndBeacons bad args

2016-03-21T06:37:10.810Z - info: Running on android test: 62. #generatePreambleAndBeacons empty keys to notify

2016-03-21T06:37:10.993Z - info: Running on android test: 63. #generatePreambleAndBeacons multiple keys to notify

2016-03-21T06:37:11.301Z - info: Running on android test: 64. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-21T06:37:11.550Z - info: Running on android test: 65. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-21T06:37:11.792Z - info: Running on android test: 66. #parseBeacons expiration out of range lower

2016-03-21T06:37:12.045Z - info: Running on android test: 67. #parseBeacons expiration out of range lower

2016-03-21T06:37:12.685Z - info: Running on android test: 68. #parseBeacons no beacons returns null

2016-03-21T06:37:13.211Z - info: Running on android test: 69. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-21T06:37:13.465Z - info: Running on android test: 70. #parseBeacons addressBookCallback fails decrypt

2016-03-21T06:37:13.980Z - info: Running on android test: 71. #parseBeacons addressBookCallback returns no matches

2016-03-21T06:37:14.388Z - info: Running on android test: 72. #parseBeacons addressBookCallback returns spurious match

2016-03-21T06:37:14.860Z - info: Running on android test: 73. #parseBeacons addressBookCallback returns public key

2016-03-21T06:37:15.413Z - info: Running on android test: 74. validate generatePskIdentityField

2016-03-21T06:37:15.701Z - info: Running on android test: 75. validate generatePskSecret

2016-03-21T06:37:16.265Z - info: Running on android test: 76. Start and stop ThaliNotificationServer

2016-03-21T06:37:16.669Z - info: Running on android test: 77. Pass an empty array to ThaliNotificationServer.start

2016-03-21T06:37:17.002Z - info: Running on android test: 78. Pass a string to ThaliNotificationServer.start

2016-03-21T06:37:17.385Z - info: Running on android test: 79. Pass an empty parameter to ThaliNotificationServer.start

2016-03-21T06:37:17.662Z - info: Running on android test: 80. Make an HTTP request to /NotificationBeacons

2016-03-21T06:37:18.110Z - info: Running on android test: 81. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-21T06:37:18.755Z - info: Running on android test: 82. Make an HTTP request to /NotificationBeaconsbefore calling start

2016-03-21T06:37:19.076Z - info: Running on android test: 83. #testThaliPeerAction - test getters

2016-03-21T06:37:19.346Z - info: Running on android test: 84. #testThaliPeerAction - start and kill

2016-03-21T06:37:19.619Z - info: Running on android test: 85. #testThaliPeerAction - double start

2016-03-21T06:37:19.910Z - info: Running on android test: 86. #testThaliPeerAction - start after kill

2016-03-21T06:37:20.289Z - info: Running on android test: 87. #testThaliPeerAction - make sure ids are unique

2016-03-21T06:37:20.970Z - info: Running on android test: 88. Test PeerConnectionInformation basics

2016-03-21T06:37:21.214Z - info: Running on android test: 89. Test PeerDictionary basic functionality

2016-03-21T06:37:21.612Z - info: Running on android test: 90. Test PeerDictionary with multiple entries.

2016-03-21T06:37:24.594Z - info: Running on android test: 91. RESOLVED entries are removed before WAITING state entry.

2016-03-21T06:37:26.003Z - info: Running on android test: 92. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-21T06:37:27.434Z - info: Running on android test: 93. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-21T06:37:28.882Z - info: Running on android test: 94. #ThaliPeerPoolInterface - bad enqueues

2016-03-21T06:37:29.470Z - info: Running on android test: 95. #ThaliPeerPoolInterface - do not allow same object type

2016-03-21T06:37:29.742Z - info: Running on android test: 96. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-21T06:37:30.039Z - info: Running on android test: 97. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent

2016-03-21T06:37:30.313Z - info: Running on android test: 98. compareBufferArrays

2016-03-21T06:37:30.629Z - info: Running on android test: 99. Call start twice and get error

2016-03-21T06:37:30.944Z - info: Running on android test: 100. Start and make sure it runs

2016-03-21T06:37:31.257Z - info: Running on android test: 101. Make sure getTimeWhenRun is right after start

2016-03-21T06:37:31.541Z - info: Running on android test: 102. Make sure getTimeWhenRun is -1 after function is called

2016-03-21T06:37:31.773Z - info: Running on android test: 103. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-21T06:37:32.057Z - info: Running on android test: 104. Test TransientState

2016-03-21T06:37:32.253Z - info: Running on android test: 105. No peers and empty database

2016-03-21T06:37:32.592Z - info: Running on android test: 106. One peer and empty DB

2016-03-21T06:37:33.100Z - info: Running on android test: 107. One peer with _Local set behind current seq

2016-03-21T06:37:33.587Z - info: Running on android test: 108. One peer with _Local set equal to current seq

2016-03-21T06:37:34.079Z - info: Running on android test: 109. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-21T06:37:34.535Z - info: Running on android test: 110. Three peers, one not in DB, one behind and one ahead

2016-03-21T06:37:35.110Z - info: Running on android test: 111. More than maximum peers, make sure we only send maximum allowed

2016-03-21T06:37:36.448Z - info: Running on android test: 112. two peers with empty DB, update the doc

2016-03-21T06:37:37.122Z - info: Running on android test: 113. add doc and make sure tokens refresh when they expire

2016-03-21T06:37:37.926Z - info: Running on android test: 114. start and stop and start and stop

2016-03-21T06:37:38.396Z - info: Running on android test: 115. two identical starts in a row

2016-03-21T06:37:38.878Z - info: Running on android test: 116. two different starts in a row

2016-03-21T06:37:39.585Z - info: Running on android test: 117. two stops and a start and two stops

2016-03-21T06:37:40.125Z - info: Running on android test: 118. we properly enqueue requests so no then needed

2016-03-21T06:37:40.574Z - info: Running on android test: 119. test calculateSeqPointKeyId

2016-03-21T06:37:40.957Z - info: Running on android test: 120. can create servers manager

2016-03-21T06:37:41.262Z - info: Running on android test: 121. calling stop without start causes error

2016-03-21T06:37:41.494Z - info: Running on android test: 122. can start/stop servers manager

2016-03-21T06:37:42.175Z - info: Running on android test: 123. starting twice resolves with listening port

2016-03-21T06:37:43.072Z - info: Running on android test: 124. terminateIncomingConnection will terminate a connection

2016-03-21T06:37:44.590Z - info: Running on android test: 125. terminate an Outgoing connection will terminate the server

2016-03-21T06:37:47.201Z - info: Running on android test: 126. terminate an Outgoing connection with wrong arguments is not harmful

2016-03-21T06:37:48.083Z - info: Running on android test: 127. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-21T06:37:48.445Z - info: Running on android test: 128. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-21T06:37:48.790Z - info: Running on android test: 129. messages with invalid location or USN should be ignored

2016-03-21T06:37:49.061Z - info: Running on android test: 130. verify that Thali-specific messages are filtered correctly

2016-03-21T06:37:49.386Z - info: Running on android test: 131. #startListeningForAdvertisements should fail if start not called

2016-03-21T06:37:49.668Z - info: Running on android test: 132. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-21T06:37:49.996Z - info: Running on android test: 133. #start should fail if called twice in a row

2016-03-21T06:37:50.417Z - info: Running on android test: 134. should not be started after stop is called

2016-03-21T06:37:50.762Z - info: Running on android test: 135. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-21T06:37:51.057Z - info: Running on android test: 136. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-21T06:37:51.369Z - info: Running on android test: 137. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-21T06:37:51.609Z - info: Running on android test: 138. #stop can be called multiple times in a row

2016-03-21T06:37:51.899Z - info: Running on android test: 139. #startListeningForAdvertisements can be called multiple times in a row

2016-03-21T06:37:52.213Z - info: Running on android test: 140. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-21T06:37:52.513Z - info: Running on android test: 141. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-21T06:37:52.792Z - info: Running on android test: 142. functions are run from a queue in the right order

2016-03-21T06:37:53.108Z - info: Running on android test: 143. #ThaliPeerPoolDefault - single action

2016-03-21T06:37:53.453Z - info: Running on android test: 144. #ThaliPeerPoolDefault - multiple actions

2016-03-21T06:37:53.705Z - info: Test run on android complete

2016-03-21T06:37:53.707Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-21T06:37:53.710Z - info: PLATFORM: android

2016-03-21T06:37:53.710Z - info: RESULT: PASS

2016-03-21T06:37:53.712Z - info: 144 of 144 tests completed

2016-03-21T06:37:53.713Z - info: 144/144 passed (0 failures)

2016-03-21T06:37:53.714Z - info: --- Test Details ---



2016-03-21T06:37:53.715Z - info: 1. calling createNativeListener directly rejects - pass

2016-03-21T06:37:53.716Z - info: 2. emits incomingConnectionState - pass

2016-03-21T06:37:53.717Z - info: 3. emits routerPortConnectionFailed - pass

2016-03-21T06:37:53.718Z - info: 4. native server connections all up - pass

2016-03-21T06:37:53.719Z - info: 5. native server - closing incoming stream cleans outgoing socket - pass

2016-03-21T06:37:53.720Z - info: 6. native server - closing incoming connection cleans outgoing socket - pass
2016-03-21T06:37:53.721Z - info: 7. native server - closing outgoing socket cleans associated mux stream - pass

2016-03-21T06:37:53.722Z - info: 8. native server - closing the whole server cleans everything up - pass

2016-03-21T06:37:53.723Z - info: 9. native server - we can get a ton of connections and data through and still clean up the server completely - pass

2016-03-21T06:37:53.723Z - info: 10. native server - simulate mux failure, make sure everything is cleaned up - pass

2016-03-21T06:37:53.724Z - info: 11. native server - timing out the incoming connection cleans everything up - pass
2016-03-21T06:37:53.725Z - info: 12. closeAll can close even when connections open - pass

2016-03-21T06:37:53.726Z - info: 13. closeAll with promise - pass

2016-03-21T06:37:53.727Z - info: 14. multiplex can send data - pass

2016-03-21T06:37:53.728Z - info: 15. enqueue and run in order - pass

2016-03-21T06:37:53.729Z - info: 16. enqueueAtTop and run backwards - pass

2016-03-21T06:37:53.730Z - info: 17. mix enqueue and enqueueAtTop - pass

2016-03-21T06:37:53.731Z - info: 18. queues handled independently - pass
2016-03-21T06:37:53.732Z - info: 19. basic - pass

2016-03-21T06:37:53.732Z - info: 20. another - pass

2016-03-21T06:37:53.733Z - info: 21. #startListeningForAdvertisements should fail if start not called - pass

2016-03-21T06:37:53.734Z - info: 22. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-21T06:37:53.735Z - info: 23. should be able to call #stopListeningForAdvertisements many times - pass

2016-03-21T06:37:53.736Z - info: 24. should be able to call #startListeningForAdvertisements many times - pass
2016-03-21T06:37:53.737Z - info: 25. should be able to call #startUpdateAdvertisingAndListening many times - pass

2016-03-21T06:37:53.738Z - info: 26. should be able to call #stopAdvertisingAndListening many times - pass

2016-03-21T06:37:53.739Z - info: 27. #start should fail if called twice in a row - pass

2016-03-21T06:37:53.739Z - info: 28. does not emit duplicate discoveryAdvertisingStateUpdate - pass

2016-03-21T06:37:53.740Z - info: 29. does not send duplicate availability changes - pass

2016-03-21T06:37:53.742Z - info: 30. can get the network status - pass

2016-03-21T06:37:53.742Z - info: 31. wifi peer is marked unavailable if announcements stop - pass

2016-03-21T06:37:53.743Z - info: 32. Can call start/stopListeningForAdvertisements - pass

2016-03-21T06:37:53.744Z - info: 33. Calling startListeningForAdvertisements twice is NOT an error - pass
2016-03-21T06:37:53.745Z - info: 34. Can call start/stopUpdateAdvertisingAndListening - pass

2016-03-21T06:37:53.746Z - info: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error - pass

2016-03-21T06:37:53.747Z - info: 36. peerAvailabilityChange is called - pass
2016-03-21T06:37:53.748Z - info: 37. Can connect to a remote peer - pass
2016-03-21T06:37:53.749Z - info: 38. Can shift large amounts of data - pass
2016-03-21T06:37:53.750Z - info: 39. #startListeningForAdvertisements should fail if start not called - pass

2016-03-21T06:37:53.750Z - info: 40. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-21T06:37:53.751Z - info: 41. should be able to call #stopListeningForAdvertisements many times - pass

2016-03-21T06:37:53.752Z - info: 42. should be able to call #startListeningForAdvertisements many times - pass

2016-03-21T06:37:53.753Z - info: 43. should be able to call #startUpdateAdvertisingAndListening many times - pass
2016-03-21T06:37:53.754Z - info: 44. should be able to call #stopAdvertisingAndListening many times - pass

2016-03-21T06:37:53.755Z - info: 45. can get the network status before starting - pass

2016-03-21T06:37:53.756Z - info: 46. error returned with bad router - pass

2016-03-21T06:37:53.757Z - info: 47. can do HTTP requests between peers - pass

2016-03-21T06:37:53.758Z - info: 48. Can do requests between peers after start and stop - pass

2016-03-21T06:37:53.759Z - info: 49. We successfully receive and replay discoveryAdvertisingStateUpdate - pass
2016-03-21T06:37:53.760Z - info: 50. Test BEACONS_RETRIEVED_AND_PARSED locally - pass

2016-03-21T06:37:53.761Z - info: 51. Test HTTP_BAD_RESPONSE locally - pass

2016-03-21T06:37:53.761Z - info: 52. Test NETWORK_PROBLEM locally - pass

2016-03-21T06:37:53.762Z - info: 53. Test timeout locally - pass

2016-03-21T06:37:53.763Z - info: 54. Call the start two times - pass

2016-03-21T06:37:53.764Z - info: 55. Call the kill before calling the start - pass
2016-03-21T06:37:53.765Z - info: 56. Call the kill immediately after the start - pass
2016-03-21T06:37:53.766Z - info: 57. Call the kill while waiting a response from the server - pass
2016-03-21T06:37:53.766Z - info: 58. Test to exceed the max content size locally - pass
2016-03-21T06:37:53.767Z - info: 59. Close the server socket while the client is waiting a response from the server. Local test. - pass
2016-03-21T06:37:53.768Z - info: 60. Close the client socket while the client is waiting a response from the server. Local test. - pass
2016-03-21T06:37:53.769Z - info: 61. #generatePreambleAndBeacons bad args - pass
2016-03-21T06:37:53.769Z - info: 62. #generatePreambleAndBeacons empty keys to notify - pass
2016-03-21T06:37:53.770Z - info: 63. #generatePreambleAndBeacons multiple keys to notify - pass
2016-03-21T06:37:53.771Z - info: 64. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass
2016-03-21T06:37:53.771Z - info: 65. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass
2016-03-21T06:37:53.772Z - info: 66. #parseBeacons expiration out of range lower - pass
2016-03-21T06:37:53.773Z - info: 67. #parseBeacons expiration out of range lower - pass
2016-03-21T06:37:53.773Z - info: 68. #parseBeacons no beacons returns null - pass
2016-03-21T06:37:53.774Z - info: 69. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass
2016-03-21T06:37:53.774Z - info: 70. #parseBeacons addressBookCallback fails decrypt - pass
2016-03-21T06:37:53.775Z - info: 71. #parseBeacons addressBookCallback returns no matches - pass
2016-03-21T06:37:53.775Z - info: 72. #parseBeacons addressBookCallback returns spurious match - pass
2016-03-21T06:37:53.776Z - info: 73. #parseBeacons addressBookCallback returns public key - pass
2016-03-21T06:37:53.777Z - info: 74. validate generatePskIdentityField - pass
2016-03-21T06:37:53.777Z - info: 75. validate generatePskSecret - pass
2016-03-21T06:37:53.778Z - info: 76. Start and stop ThaliNotificationServer - pass
2016-03-21T06:37:53.779Z - info: 77. Pass an empty array to ThaliNotificationServer.start - pass

2016-03-21T06:37:53.780Z - info: 78. Pass a string to ThaliNotificationServer.start - pass
2016-03-21T06:37:53.780Z - info: 79. Pass an empty parameter to ThaliNotificationServer.start - pass

2016-03-21T06:37:53.781Z - info: 80. Make an HTTP request to /NotificationBeacons - pass

2016-03-21T06:37:53.782Z - info: 81. Make an HTTP request to /NotificationBeacons (no keys) - pass

2016-03-21T06:37:53.783Z - info: 82. Make an HTTP request to /NotificationBeaconsbefore calling start - pass

2016-03-21T06:37:53.788Z - info: 83. #testThaliPeerAction - test getters - pass

2016-03-21T06:37:53.789Z - info: 84. #testThaliPeerAction - start and kill - pass

2016-03-21T06:37:53.790Z - info: 85. #testThaliPeerAction - double start - pass
2016-03-21T06:37:53.790Z - info: 86. #testThaliPeerAction - start after kill - pass

2016-03-21T06:37:53.791Z - info: 87. #testThaliPeerAction - make sure ids are unique - pass

2016-03-21T06:37:53.792Z - info: 88. Test PeerConnectionInformation basics - pass

2016-03-21T06:37:53.793Z - info: 89. Test PeerDictionary basic functionality - pass

2016-03-21T06:37:53.794Z - info: 90. Test PeerDictionary with multiple entries. - pass

2016-03-21T06:37:53.795Z - info: 91. RESOLVED entries are removed before WAITING state entry. - pass

2016-03-21T06:37:53.796Z - info: 92. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass

2016-03-21T06:37:53.797Z - info: 93. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass
2016-03-21T06:37:53.798Z - info: 94. #ThaliPeerPoolInterface - bad enqueues - pass

2016-03-21T06:37:53.799Z - info: 95. #ThaliPeerPoolInterface - do not allow same object type - pass

2016-03-21T06:37:53.800Z - info: 96. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass

2016-03-21T06:37:53.801Z - info: 97. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent - pass
2016-03-21T06:37:53.802Z - info: 98. compareBufferArrays - pass

2016-03-21T06:37:53.803Z - info: 99. Call start twice and get error - pass

2016-03-21T06:37:53.803Z - info: 100. Start and make sure it runs - pass

2016-03-21T06:37:53.804Z - info: 101. Make sure getTimeWhenRun is right after start - pass

2016-03-21T06:37:53.805Z - info: 102. Make sure getTimeWhenRun is -1 after function is called - pass

2016-03-21T06:37:53.806Z - info: 103. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass

2016-03-21T06:37:53.807Z - info: 104. Test TransientState - pass
2016-03-21T06:37:53.808Z - info: 105. No peers and empty database - pass

2016-03-21T06:37:53.809Z - info: 106. One peer and empty DB - pass

2016-03-21T06:37:53.810Z - info: 107. One peer with _Local set behind current seq - pass

2016-03-21T06:37:53.811Z - info: 108. One peer with _Local set equal to current seq - pass

2016-03-21T06:37:53.811Z - info: 109. One peer with _Local set ahead of current seq (and no this should not happen) - pass

2016-03-21T06:37:53.812Z - info: 110. Three peers, one not in DB, one behind and one ahead - pass
2016-03-21T06:37:53.813Z - info: 111. More than maximum peers, make sure we only send maximum allowed - pass

2016-03-21T06:37:53.814Z - info: 112. two peers with empty DB, update the doc - pass

2016-03-21T06:37:53.815Z - info: 113. add doc and make sure tokens refresh when they expire - pass

2016-03-21T06:37:53.816Z - info: 114. start and stop and start and stop - pass

2016-03-21T06:37:53.817Z - info: 115. two identical starts in a row - pass

2016-03-21T06:37:53.818Z - info: 116. two different starts in a row - pass

2016-03-21T06:37:53.819Z - info: 117. two stops and a start and two stops - pass
2016-03-21T06:37:53.820Z - info: 118. we properly enqueue requests so no then needed - pass

2016-03-21T06:37:53.821Z - info: 119. test calculateSeqPointKeyId - pass

2016-03-21T06:37:53.822Z - info: 120. can create servers manager - pass

2016-03-21T06:37:53.822Z - info: 121. calling stop without start causes error - pass

2016-03-21T06:37:53.823Z - info: 122. can start/stop servers manager - pass

2016-03-21T06:37:53.824Z - info: 123. starting twice resolves with listening port - pass
2016-03-21T06:37:53.825Z - info: 124. terminateIncomingConnection will terminate a connection - pass

2016-03-21T06:37:53.826Z - info: 125. terminate an Outgoing connection will terminate the server - pass

2016-03-21T06:37:53.827Z - info: 126. terminate an Outgoing connection with wrong arguments is not harmful - pass

2016-03-21T06:37:53.828Z - info: 127. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass
2016-03-21T06:37:53.829Z - info: 128. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-03-21T06:37:53.829Z - info: 129. messages with invalid location or USN should be ignored - pass

2016-03-21T06:37:53.830Z - info: 130. verify that Thali-specific messages are filtered correctly - pass

2016-03-21T06:37:53.831Z - info: 131. #startListeningForAdvertisements should fail if start not called - pass

2016-03-21T06:37:53.832Z - info: 132. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-21T06:37:53.833Z - info: 133. #start should fail if called twice in a row - pass

2016-03-21T06:37:53.834Z - info: 134. should not be started after stop is called - pass

2016-03-21T06:37:53.835Z - info: 135. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass
2016-03-21T06:37:53.836Z - info: 136. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass

2016-03-21T06:37:53.837Z - info: 137. #startUpdateAdvertisingAndListening should start hosting given router object - pass

2016-03-21T06:37:53.838Z - info: 138. #stop can be called multiple times in a row - pass

2016-03-21T06:37:53.839Z - info: 139. #startListeningForAdvertisements can be called multiple times in a row - pass

2016-03-21T06:37:53.840Z - info: 140. #stopListeningForAdvertisements can be called multiple times in a row - pass

2016-03-21T06:37:53.840Z - info: 141. #stopAdvertisingAndListening can be called multiple times in a row - pass

2016-03-21T06:37:53.841Z - info: 142. functions are run from a queue in the right order - pass

2016-03-21T06:37:53.842Z - info: 143. #ThaliPeerPoolDefault - single action - pass

2016-03-21T06:37:53.843Z - info: 144. #ThaliPeerPoolDefault - multiple actions - pass
2016-03-21T06:37:53.844Z - info: 

-== END ==-

2016-03-21T06:37:54.614Z - debug: Socket disconnected: transport close 2 (samsung-SM-N910C)

2016-03-21T06:38:39.879Z - info: Running on ios test: 38. Can shift large amounts of data

2016-03-21T06:39:48.450Z - info: Running on ios test: 39. #startListeningForAdvertisements should fail if start not called

2016-03-21T06:39:48.711Z - info: Running on ios test: 40. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-21T06:39:49.007Z - info: Running on ios test: 41. should be able to call #stopListeningForAdvertisements many times

2016-03-21T06:39:49.528Z - info: Running on ios test: 42. should be able to call #startListeningForAdvertisements many times

2016-03-21T06:41:14.687Z - debug: Socket disconnected: ping timeout 0 (Apple-Iphone6-1)

2016-03-21T06:53:31.779Z - debug: Socket disconnected: transport close 4 (Apple-IpadAir2-1)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m



ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
true

```
###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  f56ad48d Test has  SUCCEEDED
Device test finished on f56ad48d 
Android task is completed. [SUCCESS]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62548124bd1cdb6_More_thaliMobileNativeWrapper_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  7970f88c Test has  SUCCEEDED
Device test finished on 7970f88c 
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62548124bd1cdb6_More_thaliMobileNativeWrapper_vjrantal/thali02_samsung-SM-A300FU.md)

[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/62548124bd1cdb6_More_thaliMobileNativeWrapper_vjrantal/thali02_LGE-LG-D722.md)

####Node name: thali03
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Android task is completed. [SUCCESS]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/62548124bd1cdb6_More_thaliMobileNativeWrapper_vjrantal/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on ZX1C223JKW 
Android task is completed. [SUCCESS]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/62548124bd1cdb6_More_thaliMobileNativeWrapper_vjrantal/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Android task is completed. [SUCCESS]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/62548124bd1cdb6_More_thaliMobileNativeWrapper_vjrantal/thali05_LGE-LG-H815.md)

####Node name: thali06
Console output:
```
STOP log received from  FA55PYS00566 Test has  SUCCEEDED
Device test finished on FA55PYS00566 
Android task is completed. [SUCCESS]
```
[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/62548124bd1cdb6_More_thaliMobileNativeWrapper_vjrantal/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:0 
child process exited with code 0 on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62548124bd1cdb6_More_thaliMobileNativeWrapper_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
STOP log received from  4325e43f Test has  SUCCEEDED
Device test finished on 4325e43f 
Android task is completed. [SUCCESS]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62548124bd1cdb6_More_thaliMobileNativeWrapper_vjrantal/thali08_samsung-SM-A300FU.md)


###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/62548124bd1cdb6_More_thaliMobileNativeWrapper_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/62548124bd1cdb6_More_thaliMobileNativeWrapper_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/62548124bd1cdb6_More_thaliMobileNativeWrapper_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/62548124bd1cdb6_More_thaliMobileNativeWrapper_vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/62548124bd1cdb6_More_thaliMobileNativeWrapper_vjrantal/iOS_server.md)





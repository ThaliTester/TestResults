#### Test 625481240f1d9b8 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-03-21T15:45:57.059Z - info: listening on *:3000

2016-03-21T15:45:59.864Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:0

2016-03-21T15:46:00.895Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:1

2016-03-21T15:46:00.897Z - info: Required number of ios devices presented (2)

2016-03-21T15:46:00.901Z - info: Starting unit test run for platform: ios

2016-03-21T15:46:01.439Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:2

2016-03-21T15:46:01.618Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-21T15:46:01.894Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:3

2016-03-21T15:46:01.895Z - info: Discarding surplus device: Apple-IpadAir2-1

2016-03-21T15:46:01.981Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-21T15:46:02.357Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-21T15:46:02.776Z - info: Running on ios test: 4. native server connections all up

2016-03-21T15:46:03.224Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-21T15:46:03.652Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:4

2016-03-21T15:46:03.653Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-21T15:46:03.676Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-21T15:46:04.159Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-21T15:46:04.367Z - debug: Socket disconnected: transport close 3 (Apple-IpadAir2-1)

2016-03-21T15:46:04.752Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-21T15:46:05.309Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-21T15:46:06.261Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-21T15:46:06.462Z - debug: Socket disconnected: transport close 4 (Apple-Iphone5s-1)

2016-03-21T15:46:07.373Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:5

2016-03-21T15:46:07.374Z - info: Required number of android devices presented (2)

2016-03-21T15:46:07.376Z - info: Starting unit test run for platform: android

2016-03-21T15:46:07.857Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-21T15:46:08.030Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-21T15:46:08.269Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-21T15:46:08.422Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-21T15:46:08.564Z - info: Running on ios test: 13. closeAll with promise

2016-03-21T15:46:08.793Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-21T15:46:08.871Z - info: Running on ios test: 14. multiplex can send data

2016-03-21T15:46:09.221Z - info: Running on ios test: 15. enqueue and run in order

2016-03-21T15:46:09.242Z - info: Running on android test: 4. native server connections all up

2016-03-21T15:46:09.722Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-21T15:46:09.779Z - info: Running on ios test: 16. enqueueAtTop and run backwards

2016-03-21T15:46:10.072Z - info: Running on ios test: 17. mix enqueue and enqueueAtTop

2016-03-21T15:46:10.148Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-21T15:46:10.502Z - info: Running on ios test: 18. queues handled independently

2016-03-21T15:46:10.602Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-21T15:46:10.834Z - info: Running on ios test: 19. basic

2016-03-21T15:46:11.004Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-21T15:46:11.119Z - info: Running on ios test: 20. another

2016-03-21T15:46:11.417Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-21T15:46:11.423Z - info: Running on ios test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-21T15:46:11.738Z - info: Running on ios test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-21T15:46:12.001Z - info: Running on ios test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-21T15:46:12.311Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-21T15:46:12.395Z - info: Running on ios test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-21T15:46:12.699Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-21T15:46:12.996Z - info: Running on ios test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-21T15:46:13.135Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-21T15:46:13.563Z - info: Running on android test: 13. closeAll with promise

2016-03-21T15:46:13.933Z - info: Running on ios test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-21T15:46:13.936Z - info: Running on android test: 14. multiplex can send data

2016-03-21T15:46:14.475Z - info: Running on android test: 15. enqueue and run in order

2016-03-21T15:46:14.728Z - info: Running on ios test: 27. #start should fail if called twice in a row

2016-03-21T15:46:15.405Z - info: Running on android test: 16. enqueueAtTop and run backwards

2016-03-21T15:46:15.706Z - info: Running on ios test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-21T15:46:15.842Z - info: Running on android test: 17. mix enqueue and enqueueAtTop

2016-03-21T15:46:16.320Z - info: Running on android test: 18. queues handled independently

2016-03-21T15:46:16.494Z - info: Running on ios test: 29. does not send duplicate availability changes

2016-03-21T15:46:16.643Z - info: Running on android test: 19. basic

2016-03-21T15:46:16.918Z - info: Running on android test: 20. another

2016-03-21T15:46:17.027Z - info: Running on ios test: 30. can get the network status

2016-03-21T15:46:17.229Z - info: Running on android test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-21T15:46:17.621Z - info: Running on android test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-21T15:46:18.116Z - info: Running on ios test: 31. wifi peer is marked unavailable if announcements stop

2016-03-21T15:46:21.018Z - info: Running on android test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-21T15:46:21.127Z - info: Running on ios test: 32. Can call start/stopListeningForAdvertisements

2016-03-21T15:46:21.570Z - info: Running on android test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-21T15:46:21.863Z - info: Running on ios test: 33. Calling startListeningForAdvertisements twice is NOT an error

2016-03-21T15:46:22.399Z - info: Running on android test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-21T15:46:23.986Z - info: Running on ios test: 34. Can call start/stopUpdateAdvertisingAndListening

2016-03-21T15:46:24.441Z - info: Running on android test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-21T15:46:24.922Z - info: Running on ios test: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-21T15:46:25.096Z - info: Running on android test: 27. #start should fail if called twice in a row

2016-03-21T15:46:25.707Z - info: Running on android test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-21T15:46:25.831Z - info: Running on ios test: 36. peerAvailabilityChange is called

2016-03-21T15:46:26.763Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:6

2016-03-21T15:46:26.764Z - info: Discarding surplus device: motorola-Nexus 6

2016-03-21T15:46:27.069Z - info: Running on android test: 29. does not send duplicate availability changes

2016-03-21T15:46:27.591Z - debug: Socket disconnected: transport close 6 (motorola-Nexus 6)

2016-03-21T15:46:29.986Z - info: Running on android test: 30. can get the network status

2016-03-21T15:46:30.104Z - info: Running on ios test: 37. Can connect to a remote peer

2016-03-21T15:46:31.700Z - info: Running on android test: 31. wifi peer is marked unavailable if announcements stop

2016-03-21T15:46:33.001Z - info: Running on android test: 32. Can call start/stopListeningForAdvertisements

2016-03-21T15:46:33.512Z - info: Running on android test: 33. Calling startListeningForAdvertisements twice is NOT an error

2016-03-21T15:46:34.298Z - info: Running on android test: 34. Can call start/stopUpdateAdvertisingAndListening

2016-03-21T15:46:35.020Z - info: Running on android test: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-21T15:46:35.777Z - info: Running on android test: 36. peerAvailabilityChange is called

2016-03-21T15:46:37.492Z - info: Running on android test: 37. Can connect to a remote peer

2016-03-21T15:46:47.066Z - info: Running on android test: 38. Can shift large amounts of data

2016-03-21T15:46:52.011Z - info: Running on android test: 39. #startListeningForAdvertisements should fail if start not called

2016-03-21T15:46:52.360Z - info: Running on android test: 40. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-21T15:46:52.683Z - info: Running on android test: 41. should be able to call #stopListeningForAdvertisements many times

2016-03-21T15:46:53.065Z - info: Running on android test: 42. should be able to call #startListeningForAdvertisements many times

2016-03-21T15:46:53.645Z - info: Running on android test: 43. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-21T15:46:54.238Z - info: Running on android test: 44. should be able to call #stopAdvertisingAndListening many times

2016-03-21T15:46:54.608Z - info: Running on android test: 45. can get the network status before starting

2016-03-21T15:46:55.052Z - info: Running on android test: 46. error returned with bad router

2016-03-21T15:46:55.419Z - info: Running on android test: 47. all services are stopped when we call stop

2016-03-21T15:46:56.538Z - info: Running on android test: 48. make sure terminateConnection is properly hooked up

2016-03-21T15:46:58.360Z - info: Running on android test: 49. make sure terminateListener is properly hooked up

2016-03-21T15:46:58.848Z - info: Running on android test: 50. make sure we actually call kill connections properly

2016-03-21T15:46:59.485Z - info: Running on android test: 51. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received

2016-03-21T15:46:59.955Z - info: Running on android test: 52. We repeat failedConnection event when we get it from thaliTcpServersManager

2016-03-21T15:47:00.413Z - info: Running on android test: 53. we successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-21T15:47:01.515Z - info: Running on android test: 54. can do HTTP requests between peers

2016-03-21T15:47:13.842Z - info: Running on android test: 55. Test BEACONS_RETRIEVED_AND_PARSED locally

2016-03-21T15:47:14.526Z - info: Running on android test: 56. Test HTTP_BAD_RESPONSE locally

2016-03-21T15:47:15.292Z - info: Running on android test: 57. Test NETWORK_PROBLEM locally

2016-03-21T15:47:17.225Z - info: Running on android test: 58. Test timeout locally

2016-03-21T15:47:19.285Z - info: Running on android test: 59. Call the start two times

2016-03-21T15:47:19.769Z - info: Running on android test: 60. Call the kill before calling the start

2016-03-21T15:47:20.146Z - info: Running on android test: 61. Call the kill immediately after the start

2016-03-21T15:47:20.524Z - info: Running on android test: 62. Call the kill while waiting a response from the server

2016-03-21T15:47:23.014Z - info: Running on android test: 63. Test to exceed the max content size locally

2016-03-21T15:47:23.500Z - info: Running on android test: 64. Close the server socket while the client is waiting a response from the server. Local test.

2016-03-21T15:47:26.035Z - info: Running on android test: 65. Close the client socket while the client is waiting a response from the server. Local test.

2016-03-21T15:47:28.512Z - info: Running on android test: 66. #generatePreambleAndBeacons bad args

2016-03-21T15:47:28.955Z - info: Running on android test: 67. #generatePreambleAndBeacons empty keys to notify

2016-03-21T15:47:29.444Z - info: Running on android test: 68. #generatePreambleAndBeacons multiple keys to notify

2016-03-21T15:47:30.020Z - info: Running on android test: 69. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-21T15:47:30.351Z - info: Running on android test: 70. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-21T15:47:30.822Z - info: Running on android test: 71. #parseBeacons expiration out of range lower

2016-03-21T15:47:31.168Z - info: Running on android test: 72. #parseBeacons expiration out of range lower

2016-03-21T15:47:31.539Z - info: Running on android test: 73. #parseBeacons no beacons returns null

2016-03-21T15:47:31.904Z - info: Running on android test: 74. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-21T15:47:32.298Z - info: Running on android test: 75. #parseBeacons addressBookCallback fails decrypt

2016-03-21T15:47:33.219Z - info: Running on android test: 76. #parseBeacons addressBookCallback returns no matches

2016-03-21T15:47:33.686Z - info: Running on android test: 77. #parseBeacons addressBookCallback returns spurious match

2016-03-21T15:47:34.261Z - info: Running on android test: 78. #parseBeacons addressBookCallback returns public key

2016-03-21T15:47:34.768Z - info: Running on android test: 79. validate generatePskIdentityField

2016-03-21T15:47:35.269Z - info: Running on android test: 80. validate generatePskSecret

2016-03-21T15:47:36.209Z - info: Running on android test: 81. Start and stop ThaliNotificationServer

2016-03-21T15:47:37.495Z - info: Running on android test: 82. Pass an empty array to ThaliNotificationServer.start

2016-03-21T15:47:38.047Z - info: Running on android test: 83. Pass a string to ThaliNotificationServer.start

2016-03-21T15:47:38.377Z - info: Running on android test: 84. Pass an empty parameter to ThaliNotificationServer.start

2016-03-21T15:47:38.851Z - info: Running on android test: 85. Make an HTTP request to /NotificationBeacons

2016-03-21T15:47:40.658Z - info: Running on android test: 86. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-21T15:47:41.568Z - info: Running on android test: 87. Make an HTTP request to /NotificationBeaconsbefore calling start

2016-03-21T15:47:42.075Z - info: Running on android test: 88. #testThaliPeerAction - test getters

2016-03-21T15:47:42.385Z - info: Running on android test: 89. #testThaliPeerAction - start and kill

2016-03-21T15:47:42.724Z - info: Running on android test: 90. #testThaliPeerAction - double start

2016-03-21T15:47:43.060Z - info: Running on android test: 91. #testThaliPeerAction - start after kill

2016-03-21T15:47:43.432Z - info: Running on android test: 92. #testThaliPeerAction - make sure ids are unique

2016-03-21T15:47:43.801Z - info: Running on android test: 93. Test PeerConnectionInformation basics

2016-03-21T15:47:44.135Z - info: Running on android test: 94. Test PeerDictionary basic functionality

2016-03-21T15:47:44.700Z - info: Running on android test: 95. Test PeerDictionary with multiple entries.

2016-03-21T15:47:46.388Z - info: Running on android test: 96. RESOLVED entries are removed before WAITING state entry.

2016-03-21T15:47:47.627Z - info: Running on android test: 97. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-21T15:47:48.680Z - info: Running on android test: 98. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-21T15:47:49.841Z - info: Running on android test: 99. #ThaliPeerPoolInterface - bad enqueues

2016-03-21T15:47:50.333Z - info: Running on android test: 100. #ThaliPeerPoolInterface - do not allow same object type

2016-03-21T15:47:50.780Z - info: Running on android test: 101. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-21T15:47:51.421Z - info: Running on android test: 102. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent

2016-03-21T15:47:51.943Z - info: Running on android test: 103. compareBufferArrays

2016-03-21T15:47:52.322Z - info: Running on android test: 104. Call start twice and get error

2016-03-21T15:47:52.987Z - info: Running on android test: 105. Start and make sure it runs

2016-03-21T15:47:54.137Z - info: Running on android test: 106. Make sure getTimeWhenRun is right after start

2016-03-21T15:47:55.519Z - info: Running on android test: 107. Make sure getTimeWhenRun is -1 after function is called

2016-03-21T15:47:56.033Z - info: Running on android test: 108. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-21T15:47:56.659Z - info: Running on android test: 109. Test TransientState

2016-03-21T15:47:57.685Z - info: Running on android test: 110. No peers and empty database

2016-03-21T15:47:58.482Z - info: Running on android test: 111. One peer and empty DB

2016-03-21T15:47:59.387Z - info: Running on android test: 112. One peer with _Local set behind current seq

2016-03-21T15:48:00.791Z - info: Running on android test: 113. One peer with _Local set equal to current seq

2016-03-21T15:48:01.839Z - info: Running on android test: 114. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-21T15:48:02.685Z - info: Running on android test: 115. Three peers, one not in DB, one behind and one ahead

2016-03-21T15:48:03.533Z - info: Running on android test: 116. More than maximum peers, make sure we only send maximum allowed

2016-03-21T15:48:04.699Z - info: Running on android test: 117. two peers with empty DB, update the doc

2016-03-21T15:48:05.579Z - info: Running on android test: 118. add doc and make sure tokens refresh when they expire

2016-03-21T15:48:06.612Z - info: Running on android test: 119. start and stop and start and stop

2016-03-21T15:48:07.488Z - info: Running on android test: 120. two identical starts in a row

2016-03-21T15:48:08.183Z - info: Running on android test: 121. two different starts in a row

2016-03-21T15:48:09.428Z - info: Running on android test: 122. two stops and a start and two stops

2016-03-21T15:48:10.813Z - info: Running on android test: 123. we properly enqueue requests so no then needed

2016-03-21T15:48:11.364Z - info: Running on android test: 124. test calculateSeqPointKeyId

2016-03-21T15:48:11.912Z - info: Running on android test: 125. can create servers manager

2016-03-21T15:48:12.366Z - info: Running on android test: 126. calling stop without start causes error

2016-03-21T15:48:12.709Z - info: Running on android test: 127. can start/stop servers manager

2016-03-21T15:48:13.172Z - info: Running on android test: 128. starting twice resolves with listening port

2016-03-21T15:48:13.563Z - info: Running on android test: 129. terminateIncomingConnection will terminate a connection

2016-03-21T15:48:13.977Z - info: Running on android test: 130. terminate an Outgoing connection will terminate the server

2016-03-21T15:48:14.504Z - info: Running on android test: 131. terminate an Outgoing connection with wrong arguments is not harmful

2016-03-21T15:48:14.933Z - info: Running on android test: 132. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-21T15:48:15.576Z - info: Running on android test: 133. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-21T15:48:16.141Z - info: Running on android test: 134. messages with invalid location or USN should be ignored

2016-03-21T15:48:16.530Z - info: Running on android test: 135. verify that Thali-specific messages are filtered correctly

2016-03-21T15:48:17.047Z - info: Running on android test: 136. #startListeningForAdvertisements should fail if start not called

2016-03-21T15:48:17.436Z - info: Running on android test: 137. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-21T15:48:17.897Z - info: Running on android test: 138. #start should fail if called twice in a row

2016-03-21T15:48:18.370Z - info: Running on android test: 139. should not be started after stop is called

2016-03-21T15:48:18.956Z - info: Running on android test: 140. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-21T15:48:19.470Z - info: Running on android test: 141. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-21T15:48:20.087Z - info: Running on android test: 142. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-21T15:48:20.682Z - info: Running on android test: 143. #stop can be called multiple times in a row

2016-03-21T15:48:21.083Z - info: Running on android test: 144. #startListeningForAdvertisements can be called multiple times in a row

2016-03-21T15:48:21.669Z - info: Running on android test: 145. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-21T15:48:22.324Z - info: Running on android test: 146. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-21T15:48:22.832Z - info: Running on android test: 147. functions are run from a queue in the right order

2016-03-21T15:48:23.517Z - info: Running on android test: 148. #ThaliPeerPoolDefault - single action

2016-03-21T15:48:24.153Z - info: Running on android test: 149. #ThaliPeerPoolDefault - multiple actions

2016-03-21T15:48:24.841Z - info: Test run on android complete

2016-03-21T15:48:24.844Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-21T15:48:24.846Z - info: PLATFORM: android

2016-03-21T15:48:24.847Z - info: RESULT: FAIL

2016-03-21T15:48:24.848Z - info: 149 of 149 tests completed

2016-03-21T15:48:24.849Z - info: 148/149 passed (1 failures)

2016-03-21T15:48:24.850Z - info: --- Test Details ---



2016-03-21T15:48:24.851Z - info: 1. calling createNativeListener directly rejects - pass

2016-03-21T15:48:24.853Z - info: 2. emits incomingConnectionState - pass

2016-03-21T15:48:24.854Z - info: 3. emits routerPortConnectionFailed - pass

2016-03-21T15:48:24.855Z - info: 4. native server connections all up - pass

2016-03-21T15:48:24.855Z - info: 5. native server - closing incoming stream cleans outgoing socket - pass

2016-03-21T15:48:24.856Z - info: 6. native server - closing incoming connection cleans outgoing socket - pass

2016-03-21T15:48:24.857Z - info: 7. native server - closing outgoing socket cleans associated mux stream - pass

2016-03-21T15:48:24.858Z - info: 8. native server - closing the whole server cleans everything up - pass

2016-03-21T15:48:24.859Z - info: 9. native server - we can get a ton of connections and data through and still clean up the server completely - pass

2016-03-21T15:48:24.860Z - info: 10. native server - simulate mux failure, make sure everything is cleaned up - pass

2016-03-21T15:48:24.861Z - info: 11. native server - timing out the incoming connection cleans everything up - pass

2016-03-21T15:48:24.862Z - info: 12. closeAll can close even when connections open - pass

2016-03-21T15:48:24.863Z - info: 13. closeAll with promise - pass

2016-03-21T15:48:24.864Z - info: 14. multiplex can send data - pass

2016-03-21T15:48:24.865Z - info: 15. enqueue and run in order - pass
2016-03-21T15:48:24.866Z - info: 16. enqueueAtTop and run backwards - pass

2016-03-21T15:48:24.867Z - info: 17. mix enqueue and enqueueAtTop - pass

2016-03-21T15:48:24.868Z - info: 18. queues handled independently - pass

2016-03-21T15:48:24.869Z - info: 19. basic - pass

2016-03-21T15:48:24.870Z - info: 20. another - pass

2016-03-21T15:48:24.871Z - info: 21. #startListeningForAdvertisements should fail if start not called - pass

2016-03-21T15:48:24.872Z - info: 22. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-21T15:48:24.872Z - info: 23. should be able to call #stopListeningForAdvertisements many times - pass

2016-03-21T15:48:24.873Z - info: 24. should be able to call #startListeningForAdvertisements many times - pass

2016-03-21T15:48:24.874Z - info: 25. should be able to call #startUpdateAdvertisingAndListening many times - pass

2016-03-21T15:48:24.875Z - info: 26. should be able to call #stopAdvertisingAndListening many times - pass

2016-03-21T15:48:24.876Z - info: 27. #start should fail if called twice in a row - pass
2016-03-21T15:48:24.877Z - info: 28. does not emit duplicate discoveryAdvertisingStateUpdate - pass

2016-03-21T15:48:24.878Z - info: 29. does not send duplicate availability changes - pass

2016-03-21T15:48:24.879Z - info: 30. can get the network status - pass

2016-03-21T15:48:24.880Z - info: 31. wifi peer is marked unavailable if announcements stop - pass

2016-03-21T15:48:24.881Z - info: 32. Can call start/stopListeningForAdvertisements - pass

2016-03-21T15:48:24.882Z - info: 33. Calling startListeningForAdvertisements twice is NOT an error - pass

2016-03-21T15:48:24.883Z - info: 34. Can call start/stopUpdateAdvertisingAndListening - pass

2016-03-21T15:48:24.884Z - info: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error - pass

2016-03-21T15:48:24.884Z - info: 36. peerAvailabilityChange is called - pass

2016-03-21T15:48:24.885Z - info: 37. Can connect to a remote peer - pass

2016-03-21T15:48:24.886Z - info: 38. Can shift large amounts of data - pass

2016-03-21T15:48:24.887Z - info: 39. #startListeningForAdvertisements should fail if start not called - pass

2016-03-21T15:48:24.888Z - info: 40. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-21T15:48:24.889Z - info: 41. should be able to call #stopListeningForAdvertisements many times - pass
2016-03-21T15:48:24.890Z - info: 42. should be able to call #startListeningForAdvertisements many times - pass

2016-03-21T15:48:24.891Z - info: 43. should be able to call #startUpdateAdvertisingAndListening many times - pass

2016-03-21T15:48:24.892Z - info: 44. should be able to call #stopAdvertisingAndListening many times - pass
2016-03-21T15:48:24.893Z - info: 45. can get the network status before starting - pass
2016-03-21T15:48:24.894Z - info: 46. error returned with bad router - pass

2016-03-21T15:48:24.895Z - info: 47. all services are stopped when we call stop - pass

2016-03-21T15:48:24.895Z - info: 48. make sure terminateConnection is properly hooked up - pass
2016-03-21T15:48:24.896Z - info: 49. make sure terminateListener is properly hooked up - pass

2016-03-21T15:48:24.897Z - info: 50. make sure we actually call kill connections properly - pass

2016-03-21T15:48:24.898Z - info: 51. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received - pass

2016-03-21T15:48:24.899Z - info: 52. We repeat failedConnection event when we get it from thaliTcpServersManager - pass

2016-03-21T15:48:24.900Z - info: 53. we successfully receive and replay discoveryAdvertisingStateUpdate - fail

2016-03-21T15:48:24.901Z - info: 54. can do HTTP requests between peers - pass

2016-03-21T15:48:24.902Z - info: 55. Test BEACONS_RETRIEVED_AND_PARSED locally - pass

2016-03-21T15:48:24.903Z - info: 56. Test HTTP_BAD_RESPONSE locally - pass

2016-03-21T15:48:24.904Z - info: 57. Test NETWORK_PROBLEM locally - pass
2016-03-21T15:48:24.905Z - info: 58. Test timeout locally - pass

2016-03-21T15:48:24.906Z - info: 59. Call the start two times - pass

2016-03-21T15:48:24.907Z - info: 60. Call the kill before calling the start - pass

2016-03-21T15:48:24.908Z - info: 61. Call the kill immediately after the start - pass

2016-03-21T15:48:24.909Z - info: 62. Call the kill while waiting a response from the server - pass

2016-03-21T15:48:24.910Z - info: 63. Test to exceed the max content size locally - pass

2016-03-21T15:48:24.911Z - info: 64. Close the server socket while the client is waiting a response from the server. Local test. - pass

2016-03-21T15:48:24.912Z - info: 65. Close the client socket while the client is waiting a response from the server. Local test. - pass

2016-03-21T15:48:24.913Z - info: 66. #generatePreambleAndBeacons bad args - pass

2016-03-21T15:48:24.913Z - info: 67. #generatePreambleAndBeacons empty keys to notify - pass
2016-03-21T15:48:24.914Z - info: 68. #generatePreambleAndBeacons multiple keys to notify - pass

2016-03-21T15:48:24.915Z - info: 69. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass
2016-03-21T15:48:24.916Z - info: 70. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass
2016-03-21T15:48:24.917Z - info: 71. #parseBeacons expiration out of range lower - pass
2016-03-21T15:48:24.917Z - info: 72. #parseBeacons expiration out of range lower - pass
2016-03-21T15:48:24.918Z - info: 73. #parseBeacons no beacons returns null - pass
2016-03-21T15:48:24.919Z - info: 74. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass
2016-03-21T15:48:24.919Z - info: 75. #parseBeacons addressBookCallback fails decrypt - pass
2016-03-21T15:48:24.920Z - info: 76. #parseBeacons addressBookCallback returns no matches - pass
2016-03-21T15:48:24.921Z - info: 77. #parseBeacons addressBookCallback returns spurious match - pass
2016-03-21T15:48:24.921Z - info: 78. #parseBeacons addressBookCallback returns public key - pass
2016-03-21T15:48:24.922Z - info: 79. validate generatePskIdentityField - pass
2016-03-21T15:48:24.922Z - info: 80. validate generatePskSecret - pass
2016-03-21T15:48:24.923Z - info: 81. Start and stop ThaliNotificationServer - pass
2016-03-21T15:48:24.923Z - info: 82. Pass an empty array to ThaliNotificationServer.start - pass
2016-03-21T15:48:24.927Z - info: 83. Pass a string to ThaliNotificationServer.start - pass
2016-03-21T15:48:24.927Z - info: 84. Pass an empty parameter to ThaliNotificationServer.start - pass
2016-03-21T15:48:24.928Z - info: 85. Make an HTTP request to /NotificationBeacons - pass
2016-03-21T15:48:24.929Z - info: 86. Make an HTTP request to /NotificationBeacons (no keys) - pass

2016-03-21T15:48:24.930Z - info: 87. Make an HTTP request to /NotificationBeaconsbefore calling start - pass
2016-03-21T15:48:24.930Z - info: 88. #testThaliPeerAction - test getters - pass

2016-03-21T15:48:24.931Z - info: 89. #testThaliPeerAction - start and kill - pass

2016-03-21T15:48:24.932Z - info: 90. #testThaliPeerAction - double start - pass

2016-03-21T15:48:24.933Z - info: 91. #testThaliPeerAction - start after kill - pass

2016-03-21T15:48:24.934Z - info: 92. #testThaliPeerAction - make sure ids are unique - pass
2016-03-21T15:48:24.935Z - info: 93. Test PeerConnectionInformation basics - pass

2016-03-21T15:48:24.936Z - info: 94. Test PeerDictionary basic functionality - pass

2016-03-21T15:48:24.937Z - info: 95. Test PeerDictionary with multiple entries. - pass

2016-03-21T15:48:24.937Z - info: 96. RESOLVED entries are removed before WAITING state entry. - pass

2016-03-21T15:48:24.938Z - info: 97. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass
2016-03-21T15:48:24.939Z - info: 98. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass

2016-03-21T15:48:24.940Z - info: 99. #ThaliPeerPoolInterface - bad enqueues - pass

2016-03-21T15:48:24.941Z - info: 100. #ThaliPeerPoolInterface - do not allow same object type - pass

2016-03-21T15:48:24.941Z - info: 101. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass

2016-03-21T15:48:24.942Z - info: 102. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent - pass
2016-03-21T15:48:24.943Z - info: 103. compareBufferArrays - pass

2016-03-21T15:48:24.944Z - info: 104. Call start twice and get error - pass

2016-03-21T15:48:24.944Z - info: 105. Start and make sure it runs - pass

2016-03-21T15:48:24.945Z - info: 106. Make sure getTimeWhenRun is right after start - pass
2016-03-21T15:48:24.946Z - info: 107. Make sure getTimeWhenRun is -1 after function is called - pass

2016-03-21T15:48:24.947Z - info: 108. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass

2016-03-21T15:48:24.948Z - info: 109. Test TransientState - pass

2016-03-21T15:48:24.949Z - info: 110. No peers and empty database - pass

2016-03-21T15:48:24.949Z - info: 111. One peer and empty DB - pass

2016-03-21T15:48:24.950Z - info: 112. One peer with _Local set behind current seq - pass
2016-03-21T15:48:24.951Z - info: 113. One peer with _Local set equal to current seq - pass

2016-03-21T15:48:24.952Z - info: 114. One peer with _Local set ahead of current seq (and no this should not happen) - pass

2016-03-21T15:48:24.953Z - info: 115. Three peers, one not in DB, one behind and one ahead - pass
2016-03-21T15:48:24.954Z - info: 116. More than maximum peers, make sure we only send maximum allowed - pass
2016-03-21T15:48:24.954Z - info: 117. two peers with empty DB, update the doc - pass

2016-03-21T15:48:24.955Z - info: 118. add doc and make sure tokens refresh when they expire - pass
2016-03-21T15:48:24.956Z - info: 119. start and stop and start and stop - pass

2016-03-21T15:48:24.956Z - info: 120. two identical starts in a row - pass

2016-03-21T15:48:24.957Z - info: 121. two different starts in a row - pass

2016-03-21T15:48:24.958Z - info: 122. two stops and a start and two stops - pass

2016-03-21T15:48:24.959Z - info: 123. we properly enqueue requests so no then needed - pass
2016-03-21T15:48:24.960Z - info: 124. test calculateSeqPointKeyId - pass

2016-03-21T15:48:24.961Z - info: 125. can create servers manager - pass

2016-03-21T15:48:24.962Z - info: 126. calling stop without start causes error - pass

2016-03-21T15:48:24.963Z - info: 127. can start/stop servers manager - pass

2016-03-21T15:48:24.963Z - info: 128. starting twice resolves with listening port - pass
2016-03-21T15:48:24.964Z - info: 129. terminateIncomingConnection will terminate a connection - pass

2016-03-21T15:48:24.965Z - info: 130. terminate an Outgoing connection will terminate the server - pass

2016-03-21T15:48:24.966Z - info: 131. terminate an Outgoing connection with wrong arguments is not harmful - pass

2016-03-21T15:48:24.967Z - info: 132. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass

2016-03-21T15:48:24.967Z - info: 133. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-03-21T15:48:24.968Z - info: 134. messages with invalid location or USN should be ignored - pass

2016-03-21T15:48:24.969Z - info: 135. verify that Thali-specific messages are filtered correctly - pass
2016-03-21T15:48:24.970Z - info: 136. #startListeningForAdvertisements should fail if start not called - pass

2016-03-21T15:48:24.971Z - info: 137. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-21T15:48:24.972Z - info: 138. #start should fail if called twice in a row - pass

2016-03-21T15:48:24.973Z - info: 139. should not be started after stop is called - pass

2016-03-21T15:48:24.973Z - info: 140. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass
2016-03-21T15:48:24.974Z - info: 141. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass

2016-03-21T15:48:24.975Z - info: 142. #startUpdateAdvertisingAndListening should start hosting given router object - pass

2016-03-21T15:48:24.976Z - info: 143. #stop can be called multiple times in a row - pass

2016-03-21T15:48:24.977Z - info: 144. #startListeningForAdvertisements can be called multiple times in a row - pass

2016-03-21T15:48:24.977Z - info: 145. #stopListeningForAdvertisements can be called multiple times in a row - pass
2016-03-21T15:48:24.978Z - info: 146. #stopAdvertisingAndListening can be called multiple times in a row - pass

2016-03-21T15:48:24.979Z - info: 147. functions are run from a queue in the right order - pass

2016-03-21T15:48:24.980Z - info: 148. #ThaliPeerPoolDefault - single action - pass

2016-03-21T15:48:24.981Z - info: 149. #ThaliPeerPoolDefault - multiple actions - pass
2016-03-21T15:48:24.982Z - info: 

-== END ==-

2016-03-21T15:48:25.918Z - debug: Socket disconnected: transport close 2 (LGE-LG-H815)

2016-03-21T15:48:25.999Z - debug: Socket disconnected: transport close 5 (samsung-SM-N910C)

2016-03-21T15:48:41.167Z - info: Running on ios test: 38. Can shift large amounts of data

2016-03-21T16:05:41.215Z - debug: Socket disconnected: transport close 0 (Apple-Iphone5-1)

2016-03-21T16:05:41.523Z - debug: Socket disconnected: transport close 1 (Apple-Iphone6-1)


 
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
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/625481240f1d9b8_More_thaliMobileNativeWrapper_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/625481240f1d9b8_More_thaliMobileNativeWrapper_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/625481240f1d9b8_More_thaliMobileNativeWrapper_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/625481240f1d9b8_More_thaliMobileNativeWrapper_vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/625481240f1d9b8_More_thaliMobileNativeWrapper_vjrantal/iOS_server.md)




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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/625481240f1d9b8_More_thaliMobileNativeWrapper_vjrantal/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/625481240f1d9b8_More_thaliMobileNativeWrapper_vjrantal/thali07_LGE-LG-H815.md)

####Node name: thali08
Console output:
```
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Android task is completed. [SUCCESS]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/625481240f1d9b8_More_thaliMobileNativeWrapper_vjrantal/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/625481240f1d9b8_More_thaliMobileNativeWrapper_vjrantal/thali08_motorola-Nexus 6.md)



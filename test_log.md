#### Test 63848581358a1d8 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-03-23T10:47:37.857Z - info: listening on *:3000

2016-03-23T10:47:39.834Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:0

2016-03-23T10:47:39.896Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:1

2016-03-23T10:47:41.273Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:2

2016-03-23T10:47:41.274Z - info: Required number of ios devices presented (3)

2016-03-23T10:47:41.279Z - info: Starting unit test run for platform: ios

2016-03-23T10:47:41.349Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:3

2016-03-23T10:47:41.350Z - info: Discarding surplus device: Apple-Iphone5-1

2016-03-23T10:47:41.809Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-23T10:47:42.690Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-23T10:47:42.856Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:4

2016-03-23T10:47:43.124Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-23T10:47:43.534Z - info: Running on ios test: 4. native server connections all up

2016-03-23T10:47:44.129Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-23T10:47:44.692Z - debug: Socket disconnected: transport close 3 (Apple-Iphone5-1)

2016-03-23T10:47:44.725Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-23T10:47:45.243Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-23T10:47:45.837Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-23T10:47:46.340Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-23T10:47:50.332Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:5

2016-03-23T10:47:55.174Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-23T10:47:57.752Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-23T10:47:58.234Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-23T10:47:58.706Z - info: Running on ios test: 13. closeAll with promise

2016-03-23T10:47:59.104Z - info: Running on ios test: 14. multiplex can send data

2016-03-23T10:47:59.571Z - info: Running on ios test: 15. enqueue and run in order

2016-03-23T10:48:00.216Z - info: Running on ios test: 16. enqueueAtTop and run backwards

2016-03-23T10:48:00.709Z - info: Running on ios test: 17. mix enqueue and enqueueAtTop

2016-03-23T10:48:01.263Z - info: Running on ios test: 18. queues handled independently

2016-03-23T10:48:01.654Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:6

2016-03-23T10:48:01.659Z - info: Required number of android devices presented (3)

2016-03-23T10:48:01.660Z - info: Starting unit test run for platform: android

2016-03-23T10:48:01.712Z - info: Running on ios test: 19. basic

2016-03-23T10:48:02.133Z - info: Running on ios test: 20. another

2016-03-23T10:48:02.510Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-23T10:48:02.608Z - info: Running on ios test: 21. can pass data in setup

2016-03-23T10:48:03.362Z - info: Running on ios test: 22. #startListeningForAdvertisements should fail if start not called

2016-03-23T10:48:03.746Z - info: Running on ios test: 23. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-23T10:48:03.967Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-23T10:48:04.178Z - info: Running on ios test: 24. should be able to call #stopListeningForAdvertisements many times

2016-03-23T10:48:04.522Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-23T10:48:04.659Z - info: Running on ios test: 25. should be able to call #startListeningForAdvertisements many times

2016-03-23T10:48:05.072Z - info: Running on android test: 4. native server connections all up

2016-03-23T10:48:05.657Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-23T10:48:06.166Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-23T10:48:06.604Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-23T10:48:06.746Z - info: Running on ios test: 26. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-23T10:48:07.147Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-23T10:48:07.714Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-23T10:48:08.729Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-23T10:48:09.445Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-23T10:48:10.011Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-23T10:48:10.546Z - info: Running on android test: 13. closeAll with promise

2016-03-23T10:48:10.999Z - info: Running on android test: 14. multiplex can send data

2016-03-23T10:48:11.857Z - info: Running on android test: 15. enqueue and run in order

2016-03-23T10:48:12.052Z - info: Running on ios test: 27. should be able to call #stopAdvertisingAndListening many times

2016-03-23T10:48:13.393Z - info: Running on android test: 16. enqueueAtTop and run backwards

2016-03-23T10:48:15.037Z - info: Running on android test: 17. mix enqueue and enqueueAtTop

2016-03-23T10:48:19.741Z - info: Running on android test: 18. queues handled independently

2016-03-23T10:48:27.034Z - info: Running on android test: 19. basic

2016-03-23T10:48:27.757Z - info: Running on android test: 20. another

2016-03-23T10:48:28.634Z - info: Running on android test: 21. can pass data in setup

2016-03-23T10:48:29.085Z - info: Running on android test: 22. #startListeningForAdvertisements should fail if start not called

2016-03-23T10:48:29.700Z - info: Running on android test: 23. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-23T10:48:29.850Z - info: Running on ios test: 28. #start should fail if called twice in a row

2016-03-23T10:48:30.144Z - info: Running on android test: 24. should be able to call #stopListeningForAdvertisements many times

2016-03-23T10:48:30.667Z - info: Running on android test: 25. should be able to call #startListeningForAdvertisements many times

2016-03-23T10:48:31.579Z - info: Running on android test: 26. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-23T10:48:32.501Z - info: Running on android test: 27. should be able to call #stopAdvertisingAndListening many times

2016-03-23T10:48:33.238Z - info: Running on android test: 28. #start should fail if called twice in a row

2016-03-23T10:48:33.751Z - info: Running on android test: 29. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-23T10:48:34.349Z - info: Running on ios test: 29. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-23T10:48:35.197Z - info: Running on android test: 30. does not send duplicate availability changes

2016-03-23T10:48:35.581Z - info: Running on ios test: 30. does not send duplicate availability changes

2016-03-23T10:48:35.704Z - info: Running on android test: 31. can get the network status

2016-03-23T10:48:36.101Z - info: Running on android test: 32. wifi peer is marked unavailable if announcements stop

2016-03-23T10:48:36.192Z - info: Running on ios test: 31. can get the network status

2016-03-23T10:48:38.861Z - info: Running on android test: 33. Can call start/stopListeningForAdvertisements

2016-03-23T10:48:39.233Z - info: Running on ios test: 32. wifi peer is marked unavailable if announcements stop

2016-03-23T10:48:39.595Z - info: Running on android test: 34. Calling startListeningForAdvertisements twice is NOT an error

2016-03-23T10:48:40.389Z - info: Running on android test: 35. Can call start/stopUpdateAdvertisingAndListening

2016-03-23T10:48:41.817Z - info: Running on android test: 36. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-23T10:48:43.848Z - info: Running on android test: 37. peerAvailabilityChange is called

2016-03-23T10:48:43.956Z - info: Running on ios test: 33. Can call start/stopListeningForAdvertisements

2016-03-23T10:48:44.651Z - info: Running on ios test: 34. Calling startListeningForAdvertisements twice is NOT an error

2016-03-23T10:48:46.761Z - info: Running on ios test: 35. Can call start/stopUpdateAdvertisingAndListening

2016-03-23T10:48:46.765Z - info: Running on android test: 38. Can connect to a remote peer

2016-03-23T10:48:47.721Z - info: Running on ios test: 36. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-23T10:48:48.429Z - info: Running on ios test: 37. peerAvailabilityChange is called

2016-03-23T10:48:52.479Z - info: Running on ios test: 38. Can connect to a remote peer

2016-03-23T10:48:54.543Z - info: Running on android test: 39. Can shift large amounts of data

2016-03-23T10:49:34.907Z - info: Running on android test: 40. #startListeningForAdvertisements should fail if start not called

2016-03-23T10:50:15.081Z - info: Running on android test: 41. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-23T10:50:15.526Z - info: Running on android test: 42. should be able to call #stopListeningForAdvertisements many times

2016-03-23T10:50:16.065Z - info: Running on android test: 43. should be able to call #startListeningForAdvertisements many times

2016-03-23T10:50:16.989Z - info: Running on android test: 44. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-23T10:50:18.114Z - info: Running on android test: 45. should be able to call #stopAdvertisingAndListening many times

2016-03-23T10:50:18.659Z - info: Running on android test: 46. can get the network status before starting

2016-03-23T10:50:19.101Z - info: Running on android test: 47. error returned with bad router

2016-03-23T10:50:19.518Z - info: Running on android test: 48. all services are stopped when we call stop

2016-03-23T10:50:20.949Z - info: Running on android test: 49. make sure terminateConnection is properly hooked up

2016-03-23T10:50:23.115Z - info: Running on android test: 50. make sure terminateListener is properly hooked up

2016-03-23T10:50:24.788Z - info: Running on android test: 51. make sure we actually call kill connections properly

2016-03-23T10:50:25.774Z - info: Running on android test: 52. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received

2016-03-23T10:50:26.320Z - info: Running on android test: 53. We repeat failedConnection event when we get it from thaliTcpServersManager

2016-03-23T10:50:26.856Z - info: Running on android test: 54. we successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-23T10:50:28.240Z - warn: Failed on android test: 54. we successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-23T10:50:28.241Z - info: Running on android test: 55. can do HTTP requests between peers

2016-03-23T10:50:37.521Z - warn: Failed on android test: 55. can do HTTP requests between peers

2016-03-23T10:50:37.522Z - info: Running on android test: 56. Test BEACONS_RETRIEVED_AND_PARSED locally

2016-03-23T10:50:39.514Z - info: Running on android test: 57. Test HTTP_BAD_RESPONSE locally

2016-03-23T10:50:40.093Z - info: Running on android test: 58. Test NETWORK_PROBLEM locally

2016-03-23T10:50:40.867Z - info: Running on android test: 59. Test timeout locally

2016-03-23T10:50:42.448Z - info: Running on android test: 60. Call the start two times

2016-03-23T10:50:43.025Z - info: Running on android test: 61. Call the kill before calling the start

2016-03-23T10:50:43.563Z - info: Running on android test: 62. Call the kill immediately after the start

2016-03-23T10:50:44.839Z - info: Running on android test: 63. Call the kill while waiting a response from the server

2016-03-23T10:50:47.520Z - info: Running on android test: 64. Test to exceed the max content size locally

2016-03-23T10:50:48.172Z - info: Running on android test: 65. Close the server socket while the client is waiting a response from the server. Local test.

2016-03-23T10:50:50.841Z - info: Running on android test: 66. Close the client socket while the client is waiting a response from the server. Local test.

2016-03-23T10:50:53.425Z - info: Running on android test: 67. #generatePreambleAndBeacons bad args

2016-03-23T10:50:53.904Z - info: Running on android test: 68. #generatePreambleAndBeacons empty keys to notify

2016-03-23T10:50:54.432Z - info: Running on android test: 69. #generatePreambleAndBeacons multiple keys to notify

2016-03-23T10:50:55.481Z - info: Running on android test: 70. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-23T10:50:57.350Z - info: Running on android test: 71. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-23T10:50:59.180Z - info: Running on android test: 72. #parseBeacons expiration out of range lower

2016-03-23T10:51:00.895Z - info: Running on android test: 73. #parseBeacons expiration out of range lower

2016-03-23T10:51:01.809Z - info: Running on android test: 74. #parseBeacons no beacons returns null

2016-03-23T10:51:02.246Z - info: Running on android test: 75. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-23T10:51:02.796Z - info: Running on android test: 76. #parseBeacons addressBookCallback fails decrypt

2016-03-23T10:51:03.337Z - info: Running on android test: 77. #parseBeacons addressBookCallback returns no matches

2016-03-23T10:51:03.800Z - info: Running on android test: 78. #parseBeacons addressBookCallback returns spurious match

2016-03-23T10:51:04.574Z - info: Running on android test: 79. #parseBeacons addressBookCallback returns public key

2016-03-23T10:51:05.293Z - info: Running on android test: 80. validate generatePskIdentityField

2016-03-23T10:51:05.747Z - info: Running on android test: 81. validate generatePskSecret

2016-03-23T10:51:06.165Z - info: Running on android test: 82. Start and stop ThaliNotificationServer

2016-03-23T10:51:06.700Z - info: Running on android test: 83. Pass an empty array to ThaliNotificationServer.start

2016-03-23T10:51:07.786Z - info: Running on android test: 84. Pass a string to ThaliNotificationServer.start

2016-03-23T10:51:08.285Z - info: Running on android test: 85. Pass an empty parameter to ThaliNotificationServer.start

2016-03-23T10:51:08.874Z - info: Running on android test: 86. Make an HTTP request to /NotificationBeacons

2016-03-23T10:51:09.810Z - info: Running on android test: 87. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-23T10:51:10.379Z - info: Running on android test: 88. Make an HTTP request to /NotificationBeaconsbefore calling start

2016-03-23T10:51:11.234Z - info: Running on android test: 89. #testThaliPeerAction - test getters

2016-03-23T10:51:11.874Z - info: Running on android test: 90. #testThaliPeerAction - start and kill

2016-03-23T10:51:12.242Z - info: Running on android test: 91. #testThaliPeerAction - double start

2016-03-23T10:51:12.735Z - info: Running on android test: 92. #testThaliPeerAction - start after kill

2016-03-23T10:51:13.080Z - info: Running on android test: 93. #testThaliPeerAction - make sure ids are unique

2016-03-23T10:51:13.448Z - info: Running on android test: 94. Test PeerConnectionInformation basics

2016-03-23T10:51:13.905Z - info: Running on android test: 95. Test PeerDictionary basic functionality

2016-03-23T10:51:14.315Z - info: Running on android test: 96. Test PeerDictionary with multiple entries.

2016-03-23T10:51:16.486Z - info: Running on android test: 97. RESOLVED entries are removed before WAITING state entry.

2016-03-23T10:51:18.195Z - info: Running on android test: 98. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-23T10:51:19.376Z - info: Running on android test: 99. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-23T10:51:20.975Z - info: Running on android test: 100. #ThaliPeerPoolInterface - bad enqueues

2016-03-23T10:51:21.825Z - info: Running on android test: 101. #ThaliPeerPoolInterface - do not allow same object type

2016-03-23T10:51:22.270Z - info: Running on android test: 102. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-23T10:51:22.721Z - info: Running on android test: 103. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent

2016-03-23T10:51:23.573Z - info: Running on android test: 104. compareBufferArrays

2016-03-23T10:51:24.032Z - warn: Failed on ios test: 38. Can connect to a remote peer

2016-03-23T10:51:24.033Z - info: Running on ios test: 39. Can shift large amounts of data

2016-03-23T10:51:24.322Z - info: Running on android test: 105. Call start twice and get error

2016-03-23T10:51:25.295Z - info: Running on android test: 106. Start and make sure it runs

2016-03-23T10:51:26.120Z - info: Running on android test: 107. Make sure getTimeWhenRun is right after start

2016-03-23T10:51:26.646Z - info: Running on android test: 108. Make sure getTimeWhenRun is -1 after function is called

2016-03-23T10:51:28.222Z - info: Running on android test: 109. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-23T10:51:28.718Z - info: Running on android test: 110. Test TransientState

2016-03-23T10:51:29.176Z - info: Running on android test: 111. No peers and empty database

2016-03-23T10:51:30.086Z - info: Running on android test: 112. One peer and empty DB

2016-03-23T10:51:31.028Z - info: Running on android test: 113. One peer with _Local set behind current seq

2016-03-23T10:51:32.025Z - info: Running on android test: 114. One peer with _Local set equal to current seq

2016-03-23T10:51:33.052Z - info: Running on android test: 115. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-23T10:51:34.663Z - info: Running on android test: 116. Three peers, one not in DB, one behind and one ahead

2016-03-23T10:51:35.730Z - info: Running on android test: 117. More than maximum peers, make sure we only send maximum allowed

2016-03-23T10:51:36.990Z - info: Running on android test: 118. two peers with empty DB, update the doc

2016-03-23T10:51:37.851Z - info: Running on android test: 119. add doc and make sure tokens refresh when they expire

2016-03-23T10:51:38.783Z - info: Running on android test: 120. start and stop and start and stop

2016-03-23T10:51:39.405Z - info: Running on android test: 121. two identical starts in a row

2016-03-23T10:51:40.499Z - info: Running on android test: 122. two different starts in a row

2016-03-23T10:51:41.567Z - info: Running on android test: 123. two stops and a start and two stops

2016-03-23T10:51:42.232Z - info: Running on android test: 124. we properly enqueue requests so no then needed

2016-03-23T10:51:42.836Z - info: Running on android test: 125. test calculateSeqPointKeyId

2016-03-23T10:51:43.472Z - info: Running on android test: 126. can create servers manager

2016-03-23T10:51:43.881Z - info: Running on android test: 127. calling stop without start causes error

2016-03-23T10:51:44.326Z - info: Running on android test: 128. can start/stop servers manager

2016-03-23T10:51:44.798Z - info: Running on android test: 129. starting twice resolves with listening port

2016-03-23T10:51:45.207Z - info: Running on android test: 130. terminateIncomingConnection will terminate a connection

2016-03-23T10:51:45.601Z - info: Running on android test: 131. terminate an Outgoing connection will terminate the server

2016-03-23T10:51:46.087Z - info: Running on android test: 132. terminate an Outgoing connection with wrong arguments is not harmful

2016-03-23T10:51:46.558Z - info: Running on android test: 133. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-23T10:51:47.092Z - info: Running on android test: 134. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-23T10:51:47.609Z - info: Running on android test: 135. messages with invalid location or USN should be ignored

2016-03-23T10:51:48.136Z - info: Running on android test: 136. verify that Thali-specific messages are filtered correctly

2016-03-23T10:51:48.537Z - info: Running on android test: 137. #startListeningForAdvertisements should fail if start not called

2016-03-23T10:51:48.990Z - info: Running on android test: 138. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-23T10:51:49.418Z - info: Running on android test: 139. #start should fail if called twice in a row

2016-03-23T10:51:49.936Z - info: Running on android test: 140. should not be started after stop is called

2016-03-23T10:51:50.418Z - info: Running on android test: 141. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-23T10:51:51.014Z - info: Running on android test: 142. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-23T10:51:51.434Z - info: Running on android test: 143. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-23T10:51:51.960Z - info: Running on android test: 144. #stop can be called multiple times in a row

2016-03-23T10:51:52.440Z - info: Running on android test: 145. #startListeningForAdvertisements can be called multiple times in a row

2016-03-23T10:51:52.910Z - info: Running on android test: 146. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-23T10:51:53.289Z - info: Running on android test: 147. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-23T10:51:53.756Z - info: Running on android test: 148. functions are run from a queue in the right order

2016-03-23T10:51:54.228Z - info: Running on android test: 149. #ThaliPeerPoolDefault - single action

2016-03-23T10:51:54.700Z - info: Running on android test: 150. #ThaliPeerPoolDefault - multiple actions

2016-03-23T10:51:55.089Z - info: Test run on android complete

2016-03-23T10:51:55.091Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-23T10:51:55.093Z - info: PLATFORM: android

2016-03-23T10:51:55.094Z - info: RESULT: FAIL

2016-03-23T10:51:55.095Z - info: 150 of 150 tests completed

2016-03-23T10:51:55.096Z - info: 148/150 passed (2 failures)
2016-03-23T10:51:55.097Z - info: 

--- Failed tests ---

2016-03-23T10:51:55.098Z - warn: 54. we successfully receive and replay discoveryAdvertisingStateUpdate - fail

2016-03-23T10:51:55.099Z - warn: 55. can do HTTP requests between peers - fail

2016-03-23T10:51:55.100Z - info: 

-== END ==-

2016-03-23T10:51:55.901Z - debug: Socket disconnected: transport close 6 (motorola-Nexus 6)

2016-03-23T10:51:56.043Z - debug: Socket disconnected: transport close 5 (samsung-SM-N910C)

2016-03-23T10:51:56.103Z - debug: Socket disconnected: transport close 4 (LGE-LG-H815)

2016-03-23T10:52:34.471Z - warn: Failed on ios test: 39. Can shift large amounts of data

2016-03-23T10:52:34.472Z - info: Running on ios test: 40. #startListeningForAdvertisements should fail if start not called

2016-03-23T10:52:40.486Z - info: Running on ios test: 41. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-23T10:52:41.367Z - info: Running on ios test: 42. should be able to call #stopListeningForAdvertisements many times

2016-03-23T10:52:41.893Z - info: Running on ios test: 43. should be able to call #startListeningForAdvertisements many times

2016-03-23T10:52:42.421Z - info: Running on ios test: 44. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-23T10:52:43.035Z - info: Running on ios test: 45. should be able to call #stopAdvertisingAndListening many times

2016-03-23T10:52:47.709Z - info: Running on ios test: 46. can get the network status before starting

2016-03-23T10:52:48.416Z - info: Running on ios test: 47. error returned with bad router

2016-03-23T10:52:48.915Z - info: Running on ios test: 48. all services are stopped when we call stop

2016-03-23T10:52:49.515Z - info: Running on ios test: 49. make sure terminateConnection is properly hooked up

2016-03-23T10:52:50.110Z - info: Running on ios test: 50. make sure terminateListener is properly hooked up

2016-03-23T10:52:54.762Z - info: Running on ios test: 51. make sure we actually call kill connections properly

2016-03-23T10:52:57.109Z - warn: Failed on ios test: 51. make sure we actually call kill connections properly

2016-03-23T10:52:57.110Z - info: Running on ios test: 52. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received

2016-03-23T10:52:57.700Z - info: Running on ios test: 53. We repeat failedConnection event when we get it from thaliTcpServersManager

2016-03-23T10:52:58.193Z - info: Running on ios test: 54. we successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-23T11:07:23.733Z - debug: Socket disconnected: transport close 1 (Apple-IpadAir2-1)

2016-03-23T11:07:23.740Z - debug: Socket disconnected: transport close 0 (Apple-Iphone6-1)

2016-03-23T11:07:23.767Z - debug: Socket disconnected: transport close 2 (Apple-Iphone5s-1)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m
2016-03-23T10:48:21.075Z - error: Too many emit retries to device: Apple-Iphone6-1

2016-03-23T10:49:08.968Z - error: Too many emit retries to device: Apple-Iphone6-1

2016-03-23T10:49:08.974Z - error: Too many emit retries to device: Apple-IpadAir2-1

2016-03-23T10:49:08.976Z - error: Too many emit retries to device: Apple-Iphone5s-1

2016-03-23T10:49:17.961Z - error: Too many emit retries to device: samsung-SM-N910C

2016-03-23T10:49:43.945Z - error: Too many emit retries to device: samsung-SM-N910C

2016-03-23T10:49:43.948Z - error: Too many emit retries to device: motorola-Nexus 6


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
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
true

```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/63848581358a1d8_Fixes_for_thaliMobile_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/63848581358a1d8_Fixes_for_thaliMobile_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/63848581358a1d8_Fixes_for_thaliMobile_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/63848581358a1d8_Fixes_for_thaliMobile_vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/63848581358a1d8_Fixes_for_thaliMobile_vjrantal/iOS_server.md)




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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/63848581358a1d8_Fixes_for_thaliMobile_vjrantal/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/63848581358a1d8_Fixes_for_thaliMobile_vjrantal/thali07_LGE-LG-H815.md)

####Node name: thali08
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Device test finished on ZX1G429CRK 
Android task is completed. [SUCCESS]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/63848581358a1d8_Fixes_for_thaliMobile_vjrantal/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/63848581358a1d8_Fixes_for_thaliMobile_vjrantal/thali08_motorola-Nexus 6.md)



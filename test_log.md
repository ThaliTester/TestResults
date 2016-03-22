#### Test 636801181df08af Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-03-22T08:07:22.810Z - info: listening on *:3000

2016-03-22T08:07:24.861Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:0

2016-03-22T08:07:26.194Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:1

2016-03-22T08:07:26.197Z - info: Required number of ios devices presented (2)

2016-03-22T08:07:26.201Z - info: Starting unit test run for platform: ios

2016-03-22T08:07:26.486Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:2

2016-03-22T08:07:26.791Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-22T08:07:26.822Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:3

2016-03-22T08:07:26.824Z - info: Discarding surplus device: Apple-Iphone5-1

2016-03-22T08:07:27.037Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-22T08:07:27.353Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-22T08:07:27.749Z - info: Running on ios test: 4. native server connections all up

2016-03-22T08:07:27.944Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:4

2016-03-22T08:07:27.945Z - info: Discarding surplus device: Apple-IpadAir2-1

2016-03-22T08:07:28.305Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-22T08:07:28.811Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-22T08:07:29.205Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-22T08:07:29.663Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-22T08:07:29.936Z - debug: Socket disconnected: transport close 3 (Apple-Iphone5-1)

2016-03-22T08:07:30.159Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-22T08:07:30.539Z - debug: Socket disconnected: transport close 4 (Apple-IpadAir2-1)

2016-03-22T08:07:31.031Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-22T08:07:33.852Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:5

2016-03-22T08:07:33.854Z - info: Required number of android devices presented (2)

2016-03-22T08:07:33.860Z - info: Starting unit test run for platform: android

2016-03-22T08:07:34.461Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-22T08:07:34.835Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-22T08:07:34.960Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-22T08:07:35.425Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-22T08:07:35.663Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-22T08:07:35.925Z - info: Running on android test: 4. native server connections all up

2016-03-22T08:07:36.001Z - info: Running on ios test: 13. closeAll with promise

2016-03-22T08:07:36.331Z - info: Running on ios test: 14. multiplex can send data

2016-03-22T08:07:36.384Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-22T08:07:36.631Z - info: Running on ios test: 15. enqueue and run in order

2016-03-22T08:07:36.815Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-22T08:07:37.161Z - info: Running on ios test: 16. enqueueAtTop and run backwards

2016-03-22T08:07:37.166Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-22T08:07:37.557Z - info: Running on ios test: 17. mix enqueue and enqueueAtTop

2016-03-22T08:07:37.695Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-22T08:07:38.017Z - info: Running on ios test: 18. queues handled independently

2016-03-22T08:07:38.057Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-22T08:07:38.453Z - info: Running on ios test: 19. basic

2016-03-22T08:07:38.794Z - info: Running on ios test: 20. another

2016-03-22T08:07:38.939Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-22T08:07:39.128Z - info: Running on ios test: 21. can pass data in setup

2016-03-22T08:07:39.398Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-22T08:07:39.472Z - info: Running on ios test: 22. #startListeningForAdvertisements should fail if start not called

2016-03-22T08:07:39.889Z - info: Running on ios test: 23. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-22T08:07:39.909Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-22T08:07:40.290Z - info: Running on ios test: 24. should be able to call #stopListeningForAdvertisements many times

2016-03-22T08:07:40.392Z - info: Running on android test: 13. closeAll with promise

2016-03-22T08:07:40.883Z - info: Running on android test: 14. multiplex can send data

2016-03-22T08:07:41.062Z - info: Running on ios test: 25. should be able to call #startListeningForAdvertisements many times

2016-03-22T08:07:41.404Z - info: Running on android test: 15. enqueue and run in order

2016-03-22T08:07:42.103Z - info: Running on ios test: 26. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-22T08:07:42.514Z - info: Running on android test: 16. enqueueAtTop and run backwards

2016-03-22T08:07:43.203Z - info: Running on android test: 17. mix enqueue and enqueueAtTop

2016-03-22T08:07:43.209Z - info: Running on ios test: 27. should be able to call #stopAdvertisingAndListening many times

2016-03-22T08:07:43.580Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:6

2016-03-22T08:07:43.581Z - info: Discarding surplus device: motorola-Nexus 6

2016-03-22T08:07:43.774Z - info: Running on android test: 18. queues handled independently

2016-03-22T08:07:43.877Z - info: Running on ios test: 28. #start should fail if called twice in a row

2016-03-22T08:07:44.124Z - info: Running on android test: 19. basic

2016-03-22T08:07:44.241Z - debug: Socket disconnected: transport close 6 (motorola-Nexus 6)

2016-03-22T08:07:44.403Z - info: Running on ios test: 29. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-22T08:07:44.466Z - info: Running on android test: 20. another

2016-03-22T08:07:44.770Z - info: Running on android test: 21. can pass data in setup

2016-03-22T08:07:45.045Z - info: Running on android test: 22. #startListeningForAdvertisements should fail if start not called

2016-03-22T08:07:45.382Z - info: Running on android test: 23. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-22T08:07:45.715Z - info: Running on ios test: 30. does not send duplicate availability changes

2016-03-22T08:07:45.805Z - info: Running on android test: 24. should be able to call #stopListeningForAdvertisements many times

2016-03-22T08:07:46.341Z - info: Running on android test: 25. should be able to call #startListeningForAdvertisements many times

2016-03-22T08:07:46.512Z - info: Running on ios test: 31. can get the network status

2016-03-22T08:07:47.596Z - info: Running on android test: 26. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-22T08:07:49.093Z - info: Running on android test: 27. should be able to call #stopAdvertisingAndListening many times

2016-03-22T08:07:49.678Z - info: Running on ios test: 32. wifi peer is marked unavailable if announcements stop

2016-03-22T08:07:50.017Z - info: Running on android test: 28. #start should fail if called twice in a row

2016-03-22T08:07:50.389Z - info: Running on android test: 29. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-22T08:07:51.139Z - info: Running on ios test: 33. Can call start/stopListeningForAdvertisements

2016-03-22T08:07:51.147Z - info: Running on android test: 30. does not send duplicate availability changes

2016-03-22T08:07:51.456Z - info: Running on android test: 31. can get the network status

2016-03-22T08:07:51.635Z - info: Running on ios test: 34. Calling startListeningForAdvertisements twice is NOT an error

2016-03-22T08:07:51.863Z - info: Running on android test: 32. wifi peer is marked unavailable if announcements stop

2016-03-22T08:07:52.652Z - info: Running on ios test: 35. Can call start/stopUpdateAdvertisingAndListening

2016-03-22T08:07:53.202Z - info: Running on android test: 33. Can call start/stopListeningForAdvertisements

2016-03-22T08:07:53.225Z - info: Running on ios test: 36. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-22T08:07:54.181Z - info: Running on android test: 34. Calling startListeningForAdvertisements twice is NOT an error

2016-03-22T08:07:55.207Z - info: Running on ios test: 37. peerAvailabilityChange is called

2016-03-22T08:07:55.315Z - info: Running on android test: 35. Can call start/stopUpdateAdvertisingAndListening

2016-03-22T08:07:56.172Z - info: Running on android test: 36. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-22T08:07:56.547Z - info: Running on ios test: 38. Can connect to a remote peer

2016-03-22T08:07:57.591Z - info: Running on android test: 37. peerAvailabilityChange is called

2016-03-22T08:07:59.397Z - info: Running on android test: 38. Can connect to a remote peer

2016-03-22T08:08:08.125Z - info: Running on android test: 39. Can shift large amounts of data

2016-03-22T08:08:13.025Z - info: Running on android test: 40. #startListeningForAdvertisements should fail if start not called

2016-03-22T08:08:13.296Z - info: Running on android test: 41. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-22T08:08:13.604Z - info: Running on android test: 42. should be able to call #stopListeningForAdvertisements many times

2016-03-22T08:08:14.075Z - info: Running on android test: 43. should be able to call #startListeningForAdvertisements many times

2016-03-22T08:08:14.691Z - info: Running on android test: 44. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-22T08:08:15.405Z - info: Running on android test: 45. should be able to call #stopAdvertisingAndListening many times

2016-03-22T08:08:15.837Z - info: Running on android test: 46. can get the network status before starting

2016-03-22T08:08:16.268Z - info: Running on android test: 47. error returned with bad router

2016-03-22T08:08:16.725Z - info: Running on android test: 48. all services are stopped when we call stop

2016-03-22T08:08:19.020Z - info: Running on android test: 49. make sure terminateConnection is properly hooked up

2016-03-22T08:08:19.465Z - info: Running on android test: 50. make sure terminateListener is properly hooked up

2016-03-22T08:08:19.829Z - info: Running on android test: 51. make sure we actually call kill connections properly

2016-03-22T08:08:20.165Z - info: Running on android test: 52. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received

2016-03-22T08:08:20.597Z - info: Running on android test: 53. We repeat failedConnection event when we get it from thaliTcpServersManager

2016-03-22T08:08:21.099Z - info: Running on android test: 54. we successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-22T08:08:22.013Z - info: Running on android test: 55. can do HTTP requests between peers

2016-03-22T08:08:33.629Z - info: Running on android test: 56. Test BEACONS_RETRIEVED_AND_PARSED locally

2016-03-22T08:08:34.128Z - info: Running on android test: 57. Test HTTP_BAD_RESPONSE locally

2016-03-22T08:08:34.511Z - info: Running on android test: 58. Test NETWORK_PROBLEM locally

2016-03-22T08:08:35.219Z - info: Running on android test: 59. Test timeout locally

2016-03-22T08:08:36.743Z - info: Running on android test: 60. Call the start two times

2016-03-22T08:08:37.263Z - info: Running on android test: 61. Call the kill before calling the start

2016-03-22T08:08:37.756Z - info: Running on android test: 62. Call the kill immediately after the start

2016-03-22T08:08:38.176Z - info: Running on android test: 63. Call the kill while waiting a response from the server

2016-03-22T08:08:40.631Z - info: Running on android test: 64. Test to exceed the max content size locally

2016-03-22T08:08:41.172Z - info: Running on android test: 65. Close the server socket while the client is waiting a response from the server. Local test.

2016-03-22T08:08:43.862Z - info: Running on android test: 66. Close the client socket while the client is waiting a response from the server. Local test.

2016-03-22T08:08:46.461Z - info: Running on android test: 67. #generatePreambleAndBeacons bad args

2016-03-22T08:08:46.851Z - info: Running on android test: 68. #generatePreambleAndBeacons empty keys to notify

2016-03-22T08:08:47.256Z - info: Running on android test: 69. #generatePreambleAndBeacons multiple keys to notify

2016-03-22T08:08:47.818Z - info: Running on android test: 70. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-22T08:08:48.254Z - info: Running on android test: 71. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-22T08:08:48.741Z - info: Running on android test: 72. #parseBeacons expiration out of range lower

2016-03-22T08:08:49.176Z - info: Running on android test: 73. #parseBeacons expiration out of range lower

2016-03-22T08:08:49.479Z - info: Running on android test: 74. #parseBeacons no beacons returns null

2016-03-22T08:08:49.776Z - info: Running on android test: 75. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-22T08:08:50.113Z - info: Running on android test: 76. #parseBeacons addressBookCallback fails decrypt

2016-03-22T08:08:50.630Z - info: Running on android test: 77. #parseBeacons addressBookCallback returns no matches

2016-03-22T08:08:51.219Z - info: Running on android test: 78. #parseBeacons addressBookCallback returns spurious match

2016-03-22T08:08:51.699Z - info: Running on android test: 79. #parseBeacons addressBookCallback returns public key

2016-03-22T08:08:52.147Z - info: Running on android test: 80. validate generatePskIdentityField

2016-03-22T08:08:52.420Z - info: Running on android test: 81. validate generatePskSecret

2016-03-22T08:08:52.743Z - info: Running on android test: 82. Start and stop ThaliNotificationServer

2016-03-22T08:08:53.247Z - info: Running on android test: 83. Pass an empty array to ThaliNotificationServer.start

2016-03-22T08:08:53.736Z - info: Running on android test: 84. Pass a string to ThaliNotificationServer.start

2016-03-22T08:08:54.220Z - info: Running on android test: 85. Pass an empty parameter to ThaliNotificationServer.start

2016-03-22T08:08:54.604Z - info: Running on android test: 86. Make an HTTP request to /NotificationBeacons

2016-03-22T08:08:55.164Z - info: Running on android test: 87. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-22T08:08:55.514Z - info: Running on android test: 88. Make an HTTP request to /NotificationBeaconsbefore calling start

2016-03-22T08:08:55.826Z - info: Running on android test: 89. #testThaliPeerAction - test getters

2016-03-22T08:08:56.093Z - info: Running on android test: 90. #testThaliPeerAction - start and kill

2016-03-22T08:08:56.422Z - info: Running on android test: 91. #testThaliPeerAction - double start

2016-03-22T08:08:56.710Z - info: Running on android test: 92. #testThaliPeerAction - start after kill

2016-03-22T08:08:57.013Z - info: Running on android test: 93. #testThaliPeerAction - make sure ids are unique

2016-03-22T08:08:57.341Z - info: Running on android test: 94. Test PeerConnectionInformation basics

2016-03-22T08:08:57.633Z - info: Running on android test: 95. Test PeerDictionary basic functionality

2016-03-22T08:08:57.945Z - info: Running on android test: 96. Test PeerDictionary with multiple entries.

2016-03-22T08:08:59.570Z - info: Running on android test: 97. RESOLVED entries are removed before WAITING state entry.

2016-03-22T08:09:00.616Z - info: Running on android test: 98. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-22T08:09:01.719Z - info: Running on android test: 99. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-22T08:09:02.721Z - info: Running on android test: 100. #ThaliPeerPoolInterface - bad enqueues

2016-03-22T08:09:03.013Z - info: Running on android test: 101. #ThaliPeerPoolInterface - do not allow same object type

2016-03-22T08:09:03.304Z - info: Running on android test: 102. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-22T08:09:03.586Z - info: Running on android test: 103. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent

2016-03-22T08:09:03.884Z - info: Running on android test: 104. compareBufferArrays

2016-03-22T08:09:04.132Z - info: Running on android test: 105. Call start twice and get error

2016-03-22T08:09:04.405Z - info: Running on android test: 106. Start and make sure it runs

2016-03-22T08:09:04.666Z - info: Running on android test: 107. Make sure getTimeWhenRun is right after start

2016-03-22T08:09:04.889Z - info: Running on android test: 108. Make sure getTimeWhenRun is -1 after function is called

2016-03-22T08:09:05.211Z - info: Running on android test: 109. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-22T08:09:05.518Z - info: Running on ios test: 39. Can shift large amounts of data

2016-03-22T08:09:05.577Z - info: Running on android test: 110. Test TransientState

2016-03-22T08:09:05.873Z - info: Running on android test: 111. No peers and empty database

2016-03-22T08:09:06.287Z - info: Running on android test: 112. One peer and empty DB

2016-03-22T08:09:06.775Z - info: Running on android test: 113. One peer with _Local set behind current seq

2016-03-22T08:09:07.227Z - info: Running on android test: 114. One peer with _Local set equal to current seq

2016-03-22T08:09:07.920Z - info: Running on android test: 115. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-22T08:09:08.357Z - info: Running on android test: 116. Three peers, one not in DB, one behind and one ahead

2016-03-22T08:09:09.255Z - info: Running on android test: 117. More than maximum peers, make sure we only send maximum allowed

2016-03-22T08:09:10.271Z - info: Running on android test: 118. two peers with empty DB, update the doc

2016-03-22T08:09:11.037Z - info: Running on android test: 119. add doc and make sure tokens refresh when they expire

2016-03-22T08:09:12.055Z - info: Running on android test: 120. start and stop and start and stop

2016-03-22T08:09:12.479Z - info: Running on android test: 121. two identical starts in a row

2016-03-22T08:09:12.909Z - info: Running on android test: 122. two different starts in a row

2016-03-22T08:09:13.415Z - info: Running on android test: 123. two stops and a start and two stops

2016-03-22T08:09:14.090Z - info: Running on android test: 124. we properly enqueue requests so no then needed

2016-03-22T08:09:14.655Z - info: Running on android test: 125. test calculateSeqPointKeyId

2016-03-22T08:09:15.101Z - info: Running on android test: 126. can create servers manager

2016-03-22T08:09:15.385Z - info: Running on android test: 127. calling stop without start causes error

2016-03-22T08:09:15.710Z - info: Running on android test: 128. can start/stop servers manager

2016-03-22T08:09:16.020Z - info: Running on android test: 129. starting twice resolves with listening port

2016-03-22T08:09:16.324Z - info: Running on android test: 130. terminateIncomingConnection will terminate a connection

2016-03-22T08:09:16.739Z - info: Running on android test: 131. terminate an Outgoing connection will terminate the server

2016-03-22T08:09:17.024Z - info: Running on android test: 132. terminate an Outgoing connection with wrong arguments is not harmful

2016-03-22T08:09:17.374Z - info: Running on android test: 133. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-22T08:09:17.719Z - info: Running on android test: 134. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-22T08:09:18.146Z - info: Running on android test: 135. messages with invalid location or USN should be ignored

2016-03-22T08:09:18.400Z - info: Running on android test: 136. verify that Thali-specific messages are filtered correctly

2016-03-22T08:09:18.766Z - info: Running on android test: 137. #startListeningForAdvertisements should fail if start not called

2016-03-22T08:09:18.972Z - info: Running on android test: 138. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-22T08:09:19.304Z - info: Running on android test: 139. #start should fail if called twice in a row

2016-03-22T08:09:19.583Z - info: Running on android test: 140. should not be started after stop is called

2016-03-22T08:09:19.853Z - info: Running on android test: 141. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-22T08:09:20.219Z - info: Running on android test: 142. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-22T08:09:20.481Z - info: Running on android test: 143. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-22T08:09:20.882Z - info: Running on android test: 144. #stop can be called multiple times in a row

2016-03-22T08:09:21.177Z - info: Running on android test: 145. #startListeningForAdvertisements can be called multiple times in a row

2016-03-22T08:09:21.479Z - info: Running on android test: 146. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-22T08:09:21.767Z - info: Running on android test: 147. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-22T08:09:22.107Z - info: Running on android test: 148. functions are run from a queue in the right order

2016-03-22T08:09:22.413Z - info: Running on android test: 149. #ThaliPeerPoolDefault - single action

2016-03-22T08:09:22.712Z - info: Running on android test: 150. #ThaliPeerPoolDefault - multiple actions

2016-03-22T08:09:22.937Z - info: Test run on android complete

2016-03-22T08:09:22.939Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-22T08:09:22.942Z - info: PLATFORM: android

2016-03-22T08:09:22.942Z - info: RESULT: FAIL

2016-03-22T08:09:22.943Z - info: 150 of 150 tests completed

2016-03-22T08:09:22.944Z - info: 149/150 passed (1 failures)
2016-03-22T08:09:22.945Z - info: 

--- Failed tests ---

2016-03-22T08:09:22.947Z - warn: 54. we successfully receive and replay discoveryAdvertisingStateUpdate - fail

2016-03-22T08:09:22.948Z - info: 

-== END ==-

2016-03-22T08:09:23.700Z - debug: Socket disconnected: transport close 5 (samsung-SM-N910C)

2016-03-22T08:09:23.799Z - debug: Socket disconnected: transport close 2 (LGE-LG-H815)

2016-03-22T08:11:14.034Z - info: Running on ios test: 40. #startListeningForAdvertisements should fail if start not called

2016-03-22T08:11:14.603Z - info: Running on ios test: 41. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-22T08:11:15.160Z - info: Running on ios test: 42. should be able to call #stopListeningForAdvertisements many times

2016-03-22T08:11:15.942Z - info: Running on ios test: 43. should be able to call #startListeningForAdvertisements many times

2016-03-22T08:11:16.568Z - info: Running on ios test: 44. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-22T08:11:17.113Z - info: Running on ios test: 45. should be able to call #stopAdvertisingAndListening many times

2016-03-22T08:11:18.224Z - info: Running on ios test: 46. can get the network status before starting

2016-03-22T08:11:18.825Z - info: Running on ios test: 47. error returned with bad router

2016-03-22T08:11:23.504Z - info: Running on ios test: 48. all services are stopped when we call stop

2016-03-22T08:12:48.840Z - debug: Socket disconnected: ping timeout 0 (Apple-Iphone5s-1)

2016-03-22T08:12:48.845Z - debug: Socket disconnected: ping timeout 1 (Apple-Iphone6-1)


 
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
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
true

```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/636801181df08af_Support_passing_data_in_coordinated_tests_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/636801181df08af_Support_passing_data_in_coordinated_tests_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/636801181df08af_Support_passing_data_in_coordinated_tests_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/636801181df08af_Support_passing_data_in_coordinated_tests_vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/636801181df08af_Support_passing_data_in_coordinated_tests_vjrantal/iOS_server.md)




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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/636801181df08af_Support_passing_data_in_coordinated_tests_vjrantal/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/636801181df08af_Support_passing_data_in_coordinated_tests_vjrantal/thali07_LGE-LG-H815.md)

####Node name: thali08
Console output:
```
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Android task is completed. [SUCCESS]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/636801181df08af_Support_passing_data_in_coordinated_tests_vjrantal/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/636801181df08af_Support_passing_data_in_coordinated_tests_vjrantal/thali08_motorola-Nexus 6.md)



#### Test 639107046ed3de5 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-03-24T15:45:37.453Z - info: listening on *:3000

2016-03-24T15:45:38.790Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:0

2016-03-24T15:45:40.921Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:1

2016-03-24T15:45:40.985Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:2

2016-03-24T15:45:41.666Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:3

2016-03-24T15:45:41.668Z - info: Required number of ios devices presented (3)

2016-03-24T15:45:41.674Z - info: Starting unit test run for platform: ios

2016-03-24T15:45:42.469Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-24T15:45:42.883Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-24T15:45:43.231Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-24T15:45:43.720Z - info: Running on ios test: 4. native server connections all up

2016-03-24T15:45:44.122Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-24T15:45:44.575Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-24T15:45:45.032Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-24T15:45:45.608Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-24T15:45:46.106Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-24T15:45:47.617Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:4

2016-03-24T15:45:48.115Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-24T15:45:48.765Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-24T15:45:49.232Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-24T15:45:49.642Z - info: Running on ios test: 13. closeAll with promise

2016-03-24T15:45:50.010Z - info: Running on ios test: 14. multiplex can send data

2016-03-24T15:45:50.347Z - info: Running on ios test: 15. enqueue and run in order

2016-03-24T15:45:51.035Z - info: Running on ios test: 16. enqueueAtTop and run backwards

2016-03-24T15:45:51.461Z - info: Running on ios test: 17. mix enqueue and enqueueAtTop

2016-03-24T15:45:52.016Z - info: Running on ios test: 18. queues handled independently

2016-03-24T15:45:52.401Z - info: Running on ios test: 19. basic

2016-03-24T15:45:52.770Z - info: Running on ios test: 20. another

2016-03-24T15:45:53.124Z - info: Running on ios test: 21. can pass data in setup

2016-03-24T15:45:53.532Z - info: Running on ios test: 22. #startListeningForAdvertisements should fail if start not called

2016-03-24T15:45:53.957Z - info: Running on ios test: 23. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-24T15:45:54.442Z - info: Running on ios test: 24. should be able to call #stopListeningForAdvertisements many times

2016-03-24T15:45:54.886Z - info: Running on ios test: 25. should be able to call #startListeningForAdvertisements many times

2016-03-24T15:45:56.107Z - info: Running on ios test: 26. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-24T15:45:59.704Z - info: Running on ios test: 27. should be able to call #stopAdvertisingAndListening many times

2016-03-24T15:46:00.474Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:5

2016-03-24T15:46:00.476Z - info: Required number of android devices presented (3)

2016-03-24T15:46:00.477Z - info: Starting unit test run for platform: android

2016-03-24T15:46:01.412Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-24T15:46:01.780Z - info: Running on ios test: 28. #start should fail if called twice in a row

2016-03-24T15:46:01.988Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-24T15:46:02.361Z - info: Running on ios test: 29. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-24T15:46:03.360Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-24T15:46:03.830Z - info: Running on ios test: 30. does not send duplicate availability changes

2016-03-24T15:46:04.139Z - info: Running on android test: 4. native server connections all up

2016-03-24T15:46:04.407Z - info: Running on ios test: 31. can get the network status

2016-03-24T15:46:04.715Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-24T15:46:05.481Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-24T15:46:06.173Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-24T15:46:06.777Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-24T15:46:07.562Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-24T15:46:10.060Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-24T15:46:12.135Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-24T15:46:14.045Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-24T15:46:15.504Z - info: Running on android test: 13. closeAll with promise

2016-03-24T15:46:20.906Z - info: Running on android test: 14. multiplex can send data

2016-03-24T15:46:25.447Z - info: Running on android test: 15. enqueue and run in order

2016-03-24T15:46:28.696Z - info: Running on android test: 16. enqueueAtTop and run backwards

2016-03-24T15:46:28.911Z - info: Running on ios test: 32. wifi peer is marked unavailable if announcements stop

2016-03-24T15:46:29.223Z - info: Running on android test: 17. mix enqueue and enqueueAtTop

2016-03-24T15:46:29.960Z - info: Running on android test: 18. queues handled independently

2016-03-24T15:46:30.393Z - info: Running on android test: 19. basic

2016-03-24T15:46:30.882Z - info: Running on android test: 20. another

2016-03-24T15:46:31.425Z - info: Running on android test: 21. can pass data in setup

2016-03-24T15:46:31.814Z - info: Running on android test: 22. #startListeningForAdvertisements should fail if start not called

2016-03-24T15:46:32.194Z - info: Running on android test: 23. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-24T15:46:32.992Z - info: Running on android test: 24. should be able to call #stopListeningForAdvertisements many times

2016-03-24T15:46:33.571Z - info: Running on ios test: 33. Can call start/stopListeningForAdvertisements

2016-03-24T15:46:33.581Z - info: Running on android test: 25. should be able to call #startListeningForAdvertisements many times

2016-03-24T15:46:34.185Z - info: Running on ios test: 34. Calling startListeningForAdvertisements twice is NOT an error

2016-03-24T15:46:34.491Z - info: Running on android test: 26. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-24T15:46:34.858Z - info: Running on ios test: 35. Can call start/stopUpdateAdvertisingAndListening

2016-03-24T15:46:35.444Z - info: Running on android test: 27. should be able to call #stopAdvertisingAndListening many times

2016-03-24T15:46:37.112Z - info: Running on android test: 28. #start should fail if called twice in a row

2016-03-24T15:46:40.725Z - info: Running on android test: 29. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-24T15:46:43.291Z - info: Running on android test: 30. does not send duplicate availability changes

2016-03-24T15:46:47.331Z - info: Running on android test: 31. can get the network status

2016-03-24T15:46:53.568Z - info: Running on android test: 32. wifi peer is marked unavailable if announcements stop

2016-03-24T15:47:00.445Z - info: Running on android test: 33. Can call start/stopListeningForAdvertisements

2016-03-24T15:47:05.893Z - info: Running on android test: 34. Calling startListeningForAdvertisements twice is NOT an error

2016-03-24T15:47:13.463Z - info: Running on android test: 35. Can call start/stopUpdateAdvertisingAndListening

2016-03-24T15:47:22.727Z - info: Running on android test: 36. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-24T15:47:30.013Z - info: Running on ios test: 36. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-24T15:48:01.218Z - info: Running on android test: 37. peerAvailabilityChange is called

2016-03-24T15:48:06.493Z - info: Running on android test: 38. Can connect to a remote peer

2016-03-24T15:48:17.853Z - info: Running on android test: 39. Can shift large amounts of data

2016-03-24T15:48:21.916Z - info: Running on ios test: 37. peerAvailabilityChange is called

2016-03-24T15:48:26.329Z - info: Running on android test: 40. #startListeningForAdvertisements should fail if start not called

2016-03-24T15:48:29.003Z - info: Running on android test: 41. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-24T15:48:29.383Z - info: Running on android test: 42. should be able to call #stopListeningForAdvertisements many times

2016-03-24T15:48:29.871Z - info: Running on android test: 43. should be able to call #startListeningForAdvertisements many times

2016-03-24T15:48:31.216Z - info: Running on android test: 44. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-24T15:48:33.022Z - info: Running on android test: 45. should be able to call #stopAdvertisingAndListening many times

2016-03-24T15:48:33.573Z - info: Running on android test: 46. can get the network status before starting

2016-03-24T15:48:34.008Z - info: Running on android test: 47. error returned with bad router

2016-03-24T15:48:34.938Z - info: Running on android test: 48. all services are stopped when we call stop

2016-03-24T15:48:35.953Z - info: Running on android test: 49. make sure terminateConnection is properly hooked up

2016-03-24T15:48:36.442Z - info: Running on android test: 50. make sure terminateListener is properly hooked up

2016-03-24T15:48:36.911Z - info: Running on android test: 51. make sure we actually call kill connections properly

2016-03-24T15:48:37.263Z - info: Running on android test: 52. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received

2016-03-24T15:48:37.710Z - info: Running on android test: 53. We repeat failedConnection event when we get it from thaliTcpServersManager

2016-03-24T15:48:38.121Z - info: Running on android test: 54. we successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-24T15:48:39.261Z - warn: Failed on android test: 54. we successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-24T15:48:39.262Z - info: Running on android test: 55. can do HTTP requests between peers

2016-03-24T15:48:39.655Z - info: Running on ios test: 38. Can connect to a remote peer

2016-03-24T15:48:47.125Z - info: Running on android test: 56. Test BEACONS_RETRIEVED_AND_PARSED locally

2016-03-24T15:48:51.381Z - info: Running on android test: 57. Test HTTP_BAD_RESPONSE locally

2016-03-24T15:48:51.994Z - info: Running on android test: 58. Test NETWORK_PROBLEM locally

2016-03-24T15:48:52.692Z - info: Running on android test: 59. Test timeout locally

2016-03-24T15:48:54.334Z - info: Running on android test: 60. Call the start two times

2016-03-24T15:48:54.912Z - info: Running on android test: 61. Call the kill before calling the start

2016-03-24T15:48:55.430Z - info: Running on android test: 62. Call the kill immediately after the start

2016-03-24T15:48:55.990Z - info: Running on android test: 63. Call the kill while waiting a response from the server

2016-03-24T15:48:58.905Z - info: Running on android test: 64. Test to exceed the max content size locally

2016-03-24T15:49:00.769Z - info: Running on android test: 65. Close the server socket while the client is waiting a response from the server. Local test.

2016-03-24T15:49:03.410Z - info: Running on android test: 66. Close the client socket while the client is waiting a response from the server. Local test.

2016-03-24T15:49:05.930Z - info: Running on android test: 67. #generatePreambleAndBeacons bad args

2016-03-24T15:49:06.390Z - info: Running on android test: 68. #generatePreambleAndBeacons empty keys to notify

2016-03-24T15:49:06.743Z - info: Running on android test: 69. #generatePreambleAndBeacons multiple keys to notify

2016-03-24T15:49:07.194Z - info: Running on android test: 70. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-24T15:49:07.608Z - info: Running on android test: 71. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-24T15:49:08.102Z - info: Running on android test: 72. #parseBeacons expiration out of range lower

2016-03-24T15:49:08.580Z - info: Running on android test: 73. #parseBeacons expiration out of range lower

2016-03-24T15:49:09.151Z - info: Running on android test: 74. #parseBeacons no beacons returns null

2016-03-24T15:49:09.567Z - info: Running on android test: 75. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-24T15:49:09.939Z - info: Running on android test: 76. #parseBeacons addressBookCallback fails decrypt

2016-03-24T15:49:10.518Z - info: Running on android test: 77. #parseBeacons addressBookCallback returns no matches

2016-03-24T15:49:11.424Z - info: Running on android test: 78. #parseBeacons addressBookCallback returns spurious match

2016-03-24T15:49:11.995Z - info: Running on android test: 79. #parseBeacons addressBookCallback returns public key

2016-03-24T15:49:14.298Z - info: Running on android test: 80. validate generatePskIdentityField

2016-03-24T15:49:15.604Z - info: Running on android test: 81. validate generatePskSecret

2016-03-24T15:49:16.212Z - info: Running on android test: 82. Add two Peers.

2016-03-24T15:49:17.561Z - info: Running on android test: 83. TCP_NATIVE peer loses DNS

2016-03-24T15:49:18.222Z - info: Running on android test: 84. Resolves an action locally

2016-03-24T15:49:18.895Z - info: Running on android test: 85. Resolves an action locally using ThaliPeerPoolDefault

2016-03-24T15:49:20.110Z - info: Running on android test: 86. Action fails because of a bad hostname.

2016-03-24T15:49:25.834Z - info: Running on android test: 87. hostaddress is removed when the action is running. 

2016-03-24T15:49:28.624Z - info: Running on android test: 88. Start and stop ThaliNotificationServer

2016-03-24T15:49:29.299Z - info: Running on android test: 89. Pass an empty array to ThaliNotificationServer.start

2016-03-24T15:49:29.934Z - info: Running on android test: 90. Pass a string to ThaliNotificationServer.start

2016-03-24T15:49:32.782Z - info: Running on android test: 91. Pass an empty parameter to ThaliNotificationServer.start

2016-03-24T15:49:33.319Z - info: Running on android test: 92. Make an HTTP request to /NotificationBeacons

2016-03-24T15:49:33.995Z - info: Running on android test: 93. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-24T15:49:34.508Z - info: Running on android test: 94. Make an HTTP request to /NotificationBeaconsbefore calling start

2016-03-24T15:49:34.988Z - info: Running on android test: 95. #testThaliPeerAction - test getters

2016-03-24T15:49:35.570Z - info: Running on android test: 96. #testThaliPeerAction - start and kill

2016-03-24T15:49:35.989Z - info: Running on android test: 97. #testThaliPeerAction - double start

2016-03-24T15:49:36.516Z - info: Running on android test: 98. #testThaliPeerAction - start after kill

2016-03-24T15:49:36.972Z - info: Running on android test: 99. #testThaliPeerAction - make sure ids are unique

2016-03-24T15:49:37.338Z - info: Running on android test: 100. Test PeerConnectionInformation basics

2016-03-24T15:49:37.850Z - info: Running on android test: 101. Test PeerDictionary basic functionality

2016-03-24T15:49:38.330Z - info: Running on android test: 102. Test PeerDictionary with multiple entries.

2016-03-24T15:49:40.212Z - info: Running on android test: 103. RESOLVED entries are removed before WAITING state entry.

2016-03-24T15:49:42.090Z - info: Running on android test: 104. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-24T15:49:43.404Z - info: Running on android test: 105. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-24T15:49:44.531Z - info: Running on android test: 106. #ThaliPeerPoolInterface - bad enqueues

2016-03-24T15:49:45.244Z - info: Running on android test: 107. #ThaliPeerPoolInterface - do not allow same object type

2016-03-24T15:49:45.823Z - info: Running on android test: 108. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-24T15:49:46.342Z - info: Running on android test: 109. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent

2016-03-24T15:49:46.904Z - info: Running on android test: 110. compareBufferArrays

2016-03-24T15:49:47.393Z - info: Running on android test: 111. Call start twice and get error

2016-03-24T15:49:47.842Z - info: Running on android test: 112. Start and make sure it runs

2016-03-24T15:49:48.344Z - info: Running on android test: 113. Make sure getTimeWhenRun is right after start

2016-03-24T15:49:48.766Z - info: Running on android test: 114. Make sure getTimeWhenRun is -1 after function is called

2016-03-24T15:49:49.180Z - info: Running on android test: 115. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-24T15:49:49.634Z - info: Running on android test: 116. Test TransientState

2016-03-24T15:49:49.985Z - info: Running on android test: 117. No peers and empty database

2016-03-24T15:49:52.657Z - info: Running on android test: 118. One peer and empty DB

2016-03-24T15:49:56.728Z - info: Running on android test: 119. One peer with _Local set behind current seq

2016-03-24T15:49:58.077Z - info: Running on android test: 120. One peer with _Local set equal to current seq

2016-03-24T15:49:58.959Z - info: Running on android test: 121. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-24T15:50:01.077Z - info: Running on android test: 122. Three peers, one not in DB, one behind and one ahead

2016-03-24T15:50:02.900Z - info: Running on android test: 123. More than maximum peers, make sure we only send maximum allowed

2016-03-24T15:50:04.881Z - info: Running on android test: 124. two peers with empty DB, update the doc

2016-03-24T15:50:06.337Z - info: Running on android test: 125. add doc and make sure tokens refresh when they expire

2016-03-24T15:50:07.424Z - info: Running on android test: 126. start and stop and start and stop

2016-03-24T15:50:08.440Z - info: Running on android test: 127. two identical starts in a row

2016-03-24T15:50:10.035Z - info: Running on android test: 128. two different starts in a row

2016-03-24T15:50:11.199Z - info: Running on android test: 129. two stops and a start and two stops

2016-03-24T15:50:11.868Z - info: Running on android test: 130. we properly enqueue requests so no then needed

2016-03-24T15:50:12.681Z - info: Running on android test: 131. test calculateSeqPointKeyId

2016-03-24T15:50:13.586Z - info: Running on android test: 132. can create servers manager

2016-03-24T15:50:14.426Z - info: Running on android test: 133. calling stop without start causes error

2016-03-24T15:50:15.112Z - info: Running on android test: 134. can start/stop servers manager

2016-03-24T15:50:15.610Z - info: Running on android test: 135. starting twice resolves with listening port

2016-03-24T15:50:16.770Z - info: Running on android test: 136. terminateIncomingConnection will terminate a connection

2016-03-24T15:50:17.411Z - info: Running on android test: 137. terminate an Outgoing connection will terminate the server

2016-03-24T15:50:17.939Z - info: Running on android test: 138. terminate an Outgoing connection with wrong arguments is not harmful

2016-03-24T15:50:18.365Z - info: Running on android test: 139. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-24T15:50:18.874Z - info: Running on android test: 140. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-24T15:50:19.680Z - info: Running on android test: 141. messages with invalid location or USN should be ignored

2016-03-24T15:50:20.232Z - info: Running on android test: 142. verify that Thali-specific messages are filtered correctly

2016-03-24T15:50:20.897Z - info: Running on android test: 143. #startListeningForAdvertisements should fail if start not called

2016-03-24T15:50:21.380Z - info: Running on android test: 144. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-24T15:50:21.926Z - info: Running on android test: 145. #start should fail if called twice in a row

2016-03-24T15:50:22.372Z - info: Running on android test: 146. should not be started after stop is called

2016-03-24T15:50:22.894Z - info: Running on android test: 147. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-24T15:50:25.519Z - info: Running on android test: 148. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-24T15:50:26.014Z - info: Running on android test: 149. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-24T15:50:26.457Z - info: Running on android test: 150. #stop can be called multiple times in a row

2016-03-24T15:50:26.809Z - info: Running on android test: 151. #startListeningForAdvertisements can be called multiple times in a row

2016-03-24T15:50:27.229Z - info: Running on android test: 152. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-24T15:50:27.658Z - info: Running on android test: 153. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-24T15:50:28.127Z - info: Running on android test: 154. functions are run from a queue in the right order

2016-03-24T15:50:29.284Z - info: Running on android test: 155. #ThaliPeerPoolDefault - single action

2016-03-24T15:50:29.794Z - info: Running on android test: 156. #ThaliPeerPoolDefault - multiple actions

2016-03-24T15:50:30.198Z - info: Test run on android complete

2016-03-24T15:50:30.200Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-24T15:50:30.203Z - info: PLATFORM: android

2016-03-24T15:50:30.203Z - info: RESULT: FAIL

2016-03-24T15:50:30.205Z - info: 156 of 156 tests completed

2016-03-24T15:50:30.206Z - info: 155/156 passed (1 failures)

2016-03-24T15:50:30.207Z - info: 

--- Failed tests ---

2016-03-24T15:50:30.208Z - warn: 54. we successfully receive and replay discoveryAdvertisingStateUpdate - fail

2016-03-24T15:50:30.210Z - info: 

-== END ==-

2016-03-24T15:50:31.012Z - debug: Socket disconnected: transport close 5 (motorola-Nexus 6)

2016-03-24T15:50:31.105Z - debug: Socket disconnected: transport close 1 (LGE-LG-H815)

2016-03-24T15:50:31.205Z - debug: Socket disconnected: transport close 4 (samsung-SM-N910C)

2016-03-24T15:52:29.982Z - warn: Failed on ios test: 38. Can connect to a remote peer

2016-03-24T15:52:29.983Z - info: Running on ios test: 39. Can shift large amounts of data

2016-03-24T15:54:40.201Z - warn: Failed on ios test: 39. Can shift large amounts of data

2016-03-24T15:54:40.202Z - info: Running on ios test: 40. #startListeningForAdvertisements should fail if start not called

2016-03-24T15:54:41.526Z - info: Running on ios test: 41. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-24T15:54:42.123Z - info: Running on ios test: 42. should be able to call #stopListeningForAdvertisements many times

2016-03-24T15:54:46.679Z - info: Running on ios test: 43. should be able to call #startListeningForAdvertisements many times

2016-03-24T15:54:47.951Z - info: Running on ios test: 44. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-24T15:54:52.909Z - debug: Socket disconnected: transport close 0 (Apple-Iphone5-1)

2016-03-24T16:05:30.137Z - debug: Socket disconnected: transport close 2 (Apple-Iphone6-1)

2016-03-24T16:05:30.160Z - debug: Socket disconnected: transport close 3 (Apple-Iphone5s-1)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m
2016-03-24T15:46:14.141Z - error: Too many emit retries to device: Apple-Iphone5s-1

2016-03-24T15:46:47.384Z - error: Too many emit retries to device: Apple-Iphone5s-1

2016-03-24T15:47:31.749Z - error: Too many emit retries to device: LGE-LG-H815

2016-03-24T15:47:39.045Z - error: Too many emit retries to device: Apple-Iphone5-1

2016-03-24T15:47:39.049Z - error: Too many emit retries to device: Apple-Iphone5s-1


```


Logs for system : 
```

android : No Error

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code 254 on device 17df3859480c382d3b761fa2643dde395ced1bd8 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
true

```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/639107046ed3de5_416_ThaliNotificationClient_juhanak/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/639107046ed3de5_416_ThaliNotificationClient_juhanak/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/639107046ed3de5_416_ThaliNotificationClient_juhanak/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/639107046ed3de5_416_ThaliNotificationClient_juhanak/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/639107046ed3de5_416_ThaliNotificationClient_juhanak/iOS_server.md)




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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/639107046ed3de5_416_ThaliNotificationClient_juhanak/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/639107046ed3de5_416_ThaliNotificationClient_juhanak/thali07_LGE-LG-H815.md)

####Node name: thali08
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Device test finished on ZX1G429CRK 
Android task is completed. [SUCCESS]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/639107046ed3de5_416_ThaliNotificationClient_juhanak/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/639107046ed3de5_416_ThaliNotificationClient_juhanak/thali08_motorola-Nexus 6.md)



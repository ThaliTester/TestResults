#### Test 639808773799dbd Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-03-24T21:50:27.874Z - info: listening on *:3000

2016-03-24T21:50:31.390Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:0

2016-03-24T21:50:31.608Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:1

2016-03-24T21:50:31.819Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:2

2016-03-24T21:50:32.131Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:3

2016-03-24T21:50:32.133Z - info: Required number of ios devices presented (3)

2016-03-24T21:50:32.137Z - info: Starting unit test run for platform: ios

2016-03-24T21:50:32.793Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-24T21:50:33.252Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-24T21:50:33.605Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-24T21:50:34.108Z - info: Running on ios test: 4. native server connections all up

2016-03-24T21:50:34.567Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-24T21:50:34.954Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-24T21:50:35.397Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-24T21:50:35.972Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-24T21:50:36.477Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-24T21:50:36.893Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:4

2016-03-24T21:50:45.582Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-24T21:50:46.189Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-24T21:50:46.613Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-24T21:50:46.971Z - info: Running on ios test: 13. closeAll with promise

2016-03-24T21:50:47.415Z - info: Running on ios test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-03-24T21:50:47.916Z - info: Running on ios test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-03-24T21:50:48.495Z - info: Running on ios test: 16. multiplex can send data

2016-03-24T21:50:48.681Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:5

2016-03-24T21:50:48.683Z - info: Required number of android devices presented (3)

2016-03-24T21:50:48.684Z - info: Starting unit test run for platform: android

2016-03-24T21:50:49.084Z - info: Running on ios test: 17. enqueue and run in order

2016-03-24T21:50:49.517Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-24T21:50:49.691Z - info: Running on ios test: 18. enqueueAtTop and run backwards

2016-03-24T21:50:50.107Z - info: Running on ios test: 19. mix enqueue and enqueueAtTop

2016-03-24T21:50:50.623Z - info: Running on ios test: 20. queues handled independently

2016-03-24T21:50:50.669Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-24T21:50:51.057Z - info: Running on ios test: 21. basic

2016-03-24T21:50:51.389Z - info: Running on ios test: 22. another

2016-03-24T21:50:51.605Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-24T21:50:51.796Z - info: Running on ios test: 23. can pass data in setup

2016-03-24T21:50:52.145Z - info: Running on ios test: 24. #startListeningForAdvertisements should fail if start not called

2016-03-24T21:50:52.159Z - info: Running on android test: 4. native server connections all up

2016-03-24T21:50:52.620Z - info: Running on ios test: 25. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-24T21:50:52.783Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-24T21:50:53.097Z - info: Running on ios test: 26. should be able to call #stopListeningForAdvertisements many times

2016-03-24T21:50:53.237Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-24T21:50:53.472Z - info: Running on ios test: 27. should be able to call #startListeningForAdvertisements many times

2016-03-24T21:50:53.672Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-24T21:50:54.086Z - info: Running on ios test: 28. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-24T21:50:54.093Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-24T21:50:54.765Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-24T21:50:55.563Z - info: Running on ios test: 29. should be able to call #stopAdvertisingAndListening many times

2016-03-24T21:50:55.871Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-24T21:50:56.267Z - info: Running on ios test: 30. #start should fail if called twice in a row

2016-03-24T21:50:56.547Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-24T21:50:57.061Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-24T21:50:57.096Z - info: Running on ios test: 31. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-24T21:50:57.420Z - info: Running on android test: 13. closeAll with promise

2016-03-24T21:50:57.764Z - info: Running on ios test: 32. does not send duplicate availability changes

2016-03-24T21:50:57.794Z - info: Running on android test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-03-24T21:50:58.175Z - info: Running on android test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-03-24T21:50:58.334Z - info: Running on ios test: 33. can get the network status

2016-03-24T21:50:58.586Z - info: Running on android test: 16. multiplex can send data

2016-03-24T21:51:02.704Z - info: Running on android test: 17. enqueue and run in order

2016-03-24T21:51:04.746Z - info: Running on android test: 18. enqueueAtTop and run backwards

2016-03-24T21:51:06.297Z - info: Running on android test: 19. mix enqueue and enqueueAtTop

2016-03-24T21:51:13.600Z - info: Running on android test: 20. queues handled independently

2016-03-24T21:51:15.838Z - info: Running on android test: 21. basic

2016-03-24T21:51:16.541Z - info: Running on android test: 22. another

2016-03-24T21:51:17.248Z - info: Running on android test: 23. can pass data in setup

2016-03-24T21:51:19.596Z - info: Running on android test: 24. #startListeningForAdvertisements should fail if start not called

2016-03-24T21:51:20.735Z - info: Running on android test: 25. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-24T21:51:22.521Z - info: Running on android test: 26. should be able to call #stopListeningForAdvertisements many times

2016-03-24T21:51:26.185Z - info: Running on android test: 27. should be able to call #startListeningForAdvertisements many times

2016-03-24T21:51:29.066Z - info: Running on android test: 28. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-24T21:51:30.072Z - info: Running on android test: 29. should be able to call #stopAdvertisingAndListening many times

2016-03-24T21:51:30.142Z - info: Running on ios test: 34. wifi peer is marked unavailable if announcements stop

2016-03-24T21:51:30.538Z - info: Running on android test: 30. #start should fail if called twice in a row

2016-03-24T21:51:31.132Z - info: Running on android test: 31. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-24T21:51:32.163Z - info: Running on android test: 32. does not send duplicate availability changes

2016-03-24T21:51:32.597Z - info: Running on android test: 33. can get the network status

2016-03-24T21:51:33.042Z - info: Running on ios test: 35. Can call start/stopListeningForAdvertisements

2016-03-24T21:51:33.046Z - info: Running on android test: 34. wifi peer is marked unavailable if announcements stop

2016-03-24T21:51:33.594Z - info: Running on ios test: 36. Calling startListeningForAdvertisements twice is NOT an error

2016-03-24T21:51:34.255Z - info: Running on ios test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-03-24T21:51:35.617Z - info: Running on android test: 35. Can call start/stopListeningForAdvertisements

2016-03-24T21:51:38.219Z - info: Running on android test: 36. Calling startListeningForAdvertisements twice is NOT an error

2016-03-24T21:51:38.387Z - debug: Socket disconnected: transport close 2 (Apple-Iphone6-1)

2016-03-24T21:51:47.226Z - info: Running on android test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-03-24T21:51:52.550Z - info: Running on android test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-24T21:51:54.913Z - info: Running on android test: 39. peerAvailabilityChange is called

2016-03-24T21:51:57.317Z - info: Running on android test: 40. Can connect to a remote peer

2016-03-24T21:52:10.162Z - info: Running on android test: 41. Can shift large amounts of data

2016-03-24T21:52:22.115Z - info: Running on android test: 42. #startListeningForAdvertisements should fail if start not called

2016-03-24T21:52:23.527Z - info: Running on android test: 43. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-24T21:52:27.014Z - info: Running on android test: 44. should be able to call #stopListeningForAdvertisements many times

2016-03-24T21:52:28.250Z - info: Running on android test: 45. should be able to call #startListeningForAdvertisements many times

2016-03-24T21:52:29.385Z - info: Running on android test: 46. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-24T21:52:30.315Z - info: Running on android test: 47. should be able to call #stopAdvertisingAndListening many times

2016-03-24T21:52:31.137Z - info: Running on android test: 48. can get the network status before starting

2016-03-24T21:52:31.483Z - info: Running on android test: 49. error returned with bad router

2016-03-24T21:52:31.995Z - info: Running on android test: 50. all services are stopped when we call stop

2016-03-24T21:52:32.885Z - info: Running on android test: 51. make sure terminateConnection is properly hooked up

2016-03-24T21:52:33.368Z - info: Running on android test: 52. make sure terminateListener is properly hooked up

2016-03-24T21:52:33.836Z - info: Running on android test: 53. make sure we actually call kill connections properly

2016-03-24T21:52:34.223Z - info: Running on android test: 54. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received

2016-03-24T21:52:34.778Z - info: Running on android test: 55. We repeat failedConnection event when we get it from thaliTcpServersManager

2016-03-24T21:52:35.303Z - info: Running on android test: 56. we successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-24T21:52:36.456Z - warn: Failed on android test: 56. we successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-24T21:52:36.457Z - info: Running on android test: 57. can do HTTP requests between peers

2016-03-24T21:52:50.232Z - info: Running on android test: 58. will fail bad PSK connection between peers

2016-03-24T21:52:53.840Z - info: Running on android test: 59. Test BEACONS_RETRIEVED_AND_PARSED locally

2016-03-24T21:52:54.553Z - info: Running on android test: 60. Test HTTP_BAD_RESPONSE locally

2016-03-24T21:52:55.024Z - info: Running on android test: 61. Test NETWORK_PROBLEM locally

2016-03-24T21:52:56.291Z - info: Running on android test: 62. Test timeout locally

2016-03-24T21:52:58.477Z - info: Running on android test: 63. Call the start two times

2016-03-24T21:53:00.286Z - info: Running on android test: 64. Call the kill before calling the start

2016-03-24T21:53:01.309Z - info: Running on android test: 65. Call the kill immediately after the start

2016-03-24T21:53:01.814Z - info: Running on android test: 66. Call the kill while waiting a response from the server

2016-03-24T21:53:04.466Z - info: Running on android test: 67. Test to exceed the max content size locally

2016-03-24T21:53:05.017Z - info: Running on android test: 68. Close the server socket while the client is waiting a response from the server. Local test.

2016-03-24T21:53:07.497Z - info: Running on android test: 69. Close the client socket while the client is waiting a response from the server. Local test.

2016-03-24T21:53:10.058Z - info: Running on android test: 70. #generatePreambleAndBeacons bad args

2016-03-24T21:53:10.567Z - info: Running on android test: 71. #generatePreambleAndBeacons empty keys to notify

2016-03-24T21:53:11.022Z - info: Running on android test: 72. #generatePreambleAndBeacons multiple keys to notify

2016-03-24T21:53:11.542Z - info: Running on android test: 73. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-24T21:53:11.991Z - info: Running on android test: 74. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-24T21:53:12.391Z - info: Running on android test: 75. #parseBeacons expiration out of range lower

2016-03-24T21:53:12.788Z - info: Running on android test: 76. #parseBeacons expiration out of range lower

2016-03-24T21:53:13.186Z - info: Running on android test: 77. #parseBeacons no beacons returns null

2016-03-24T21:53:13.572Z - info: Running on android test: 78. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-24T21:53:13.950Z - info: Running on android test: 79. #parseBeacons addressBookCallback fails decrypt

2016-03-24T21:53:14.490Z - info: Running on android test: 80. #parseBeacons addressBookCallback returns no matches

2016-03-24T21:53:14.967Z - info: Running on android test: 81. #parseBeacons addressBookCallback returns spurious match

2016-03-24T21:53:15.434Z - info: Running on android test: 82. #parseBeacons addressBookCallback returns public key

2016-03-24T21:53:15.920Z - info: Running on android test: 83. validate generatePskIdentityField

2016-03-24T21:53:16.295Z - info: Running on android test: 84. validate generatePskSecret

2016-03-24T21:53:16.715Z - info: Running on android test: 85. validate generatePskSecrets

2016-03-24T21:53:18.407Z - info: Running on android test: 86. validate generateBeaconStreamAndSecrets

2016-03-24T21:53:19.057Z - info: Running on android test: 87. Start and stop ThaliNotificationServer

2016-03-24T21:53:19.630Z - info: Running on android test: 88. Pass an empty array to ThaliNotificationServer.start

2016-03-24T21:53:20.131Z - info: Running on android test: 89. Pass a string to ThaliNotificationServer.start

2016-03-24T21:53:20.544Z - info: Running on android test: 90. Pass an empty parameter to ThaliNotificationServer.start

2016-03-24T21:53:21.047Z - info: Running on android test: 91. Make an HTTP request to /NotificationBeacons

2016-03-24T21:53:21.644Z - info: Running on android test: 92. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-24T21:53:22.100Z - info: Running on android test: 93. Make an HTTP request to /NotificationBeaconsbefore calling start

2016-03-24T21:53:22.576Z - info: Running on android test: 94. #testThaliPeerAction - test getters

2016-03-24T21:53:22.986Z - info: Running on android test: 95. #testThaliPeerAction - start and kill

2016-03-24T21:53:23.400Z - info: Running on android test: 96. #testThaliPeerAction - double start

2016-03-24T21:53:23.760Z - info: Running on android test: 97. #testThaliPeerAction - start after kill

2016-03-24T21:53:24.183Z - info: Running on android test: 98. #testThaliPeerAction - make sure ids are unique

2016-03-24T21:53:24.596Z - info: Running on android test: 99. Test PeerConnectionInformation basics

2016-03-24T21:53:25.005Z - info: Running on android test: 100. Test PeerDictionary basic functionality

2016-03-24T21:53:25.407Z - info: Running on android test: 101. Test PeerDictionary with multiple entries.

2016-03-24T21:53:27.245Z - info: Running on android test: 102. RESOLVED entries are removed before WAITING state entry.

2016-03-24T21:53:28.382Z - info: Running on android test: 103. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-24T21:53:29.567Z - info: Running on android test: 104. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-24T21:53:30.616Z - info: Running on android test: 105. #ThaliPeerPoolInterface - bad enqueues

2016-03-24T21:53:31.088Z - info: Running on android test: 106. #ThaliPeerPoolInterface - do not allow same object type

2016-03-24T21:53:31.541Z - info: Running on android test: 107. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-24T21:53:32.032Z - info: Running on android test: 108. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent

2016-03-24T21:53:32.504Z - info: Running on android test: 109. compareBufferArrays

2016-03-24T21:53:32.890Z - info: Running on android test: 110. Call start twice and get error

2016-03-24T21:53:33.278Z - info: Running on android test: 111. Start and make sure it runs

2016-03-24T21:53:33.654Z - info: Running on android test: 112. Make sure getTimeWhenRun is right after start

2016-03-24T21:53:34.075Z - info: Running on android test: 113. Make sure getTimeWhenRun is -1 after function is called

2016-03-24T21:53:34.431Z - info: Running on android test: 114. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-24T21:53:34.811Z - info: Running on android test: 115. Test TransientState

2016-03-24T21:53:35.161Z - info: Running on android test: 116. No peers and empty database

2016-03-24T21:53:39.180Z - info: Running on android test: 117. One peer and empty DB

2016-03-24T21:53:39.913Z - info: Running on android test: 118. One peer with _Local set behind current seq

2016-03-24T21:53:40.720Z - info: Running on android test: 119. One peer with _Local set equal to current seq

2016-03-24T21:53:41.582Z - info: Running on android test: 120. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-24T21:53:42.449Z - info: Running on android test: 121. Three peers, one not in DB, one behind and one ahead

2016-03-24T21:53:43.920Z - info: Running on android test: 122. More than maximum peers, make sure we only send maximum allowed

2016-03-24T21:53:45.230Z - info: Running on android test: 123. two peers with empty DB, update the doc

2016-03-24T21:53:46.153Z - info: Running on android test: 124. add doc and make sure tokens refresh when they expire

2016-03-24T21:53:47.619Z - info: Running on android test: 125. start and stop and start and stop

2016-03-24T21:53:48.494Z - info: Running on android test: 126. two identical starts in a row

2016-03-24T21:53:49.192Z - info: Running on android test: 127. two different starts in a row

2016-03-24T21:53:49.802Z - info: Running on android test: 128. two stops and a start and two stops

2016-03-24T21:53:50.361Z - info: Running on android test: 129. we properly enqueue requests so no then needed

2016-03-24T21:53:50.889Z - info: Running on android test: 130. test calculateSeqPointKeyId

2016-03-24T21:53:51.374Z - info: Running on android test: 131. can create servers manager

2016-03-24T21:53:51.804Z - info: Running on android test: 132. calling stop without start causes error

2016-03-24T21:53:52.229Z - info: Running on android test: 133. can start/stop servers manager

2016-03-24T21:53:52.636Z - info: Running on android test: 134. starting twice resolves with listening port

2016-03-24T21:53:53.038Z - info: Running on android test: 135. terminateIncomingConnection will terminate a connection

2016-03-24T21:53:53.566Z - info: Running on android test: 136. terminate an Outgoing connection will terminate the server

2016-03-24T21:53:54.068Z - info: Running on android test: 137. terminate an Outgoing connection with wrong arguments is not harmful

2016-03-24T21:53:54.534Z - info: Running on android test: 138. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-24T21:53:55.025Z - info: Running on android test: 139. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-24T21:53:55.528Z - info: Running on android test: 140. messages with invalid location or USN should be ignored

2016-03-24T21:53:55.992Z - info: Running on android test: 141. verify that Thali-specific messages are filtered correctly

2016-03-24T21:53:56.409Z - info: Running on android test: 142. #startListeningForAdvertisements should fail if start not called

2016-03-24T21:53:56.848Z - info: Running on android test: 143. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-24T21:53:57.275Z - info: Running on android test: 144. #start should fail if called twice in a row

2016-03-24T21:53:57.754Z - info: Running on android test: 145. should not be started after stop is called

2016-03-24T21:53:58.190Z - info: Running on android test: 146. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-24T21:53:58.686Z - info: Running on android test: 147. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-24T21:53:59.255Z - info: Running on android test: 148. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-24T21:53:59.767Z - info: Running on android test: 149. #startUpdateAdvertisingAndListening bad psk should be rejected object

2016-03-24T21:54:00.234Z - info: Running on android test: 150. #stop can be called multiple times in a row

2016-03-24T21:54:00.755Z - info: Running on android test: 151. #startListeningForAdvertisements can be called multiple times in a row

2016-03-24T21:54:01.198Z - info: Running on android test: 152. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-24T21:54:01.641Z - info: Running on android test: 153. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-24T21:54:02.086Z - info: Running on android test: 154. functions are run from a queue in the right order

2016-03-24T21:54:02.528Z - info: Running on android test: 155. #ThaliPeerPoolDefault - single action

2016-03-24T21:54:02.932Z - info: Running on android test: 156. #ThaliPeerPoolDefault - multiple actions

2016-03-24T21:54:03.372Z - info: Test run on android complete

2016-03-24T21:54:03.374Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-24T21:54:03.376Z - info: PLATFORM: android

2016-03-24T21:54:03.377Z - info: RESULT: FAIL
2016-03-24T21:54:03.378Z - info: 156 of 156 tests completed

2016-03-24T21:54:03.378Z - info: 155/156 passed (1 failures)
2016-03-24T21:54:03.379Z - info: 

--- Failed tests ---

2016-03-24T21:54:03.380Z - warn: 56. we successfully receive and replay discoveryAdvertisingStateUpdate - fail

2016-03-24T21:54:03.381Z - info: 

-== END ==-

2016-03-24T21:54:04.108Z - debug: Socket disconnected: transport close 5 (motorola-Nexus 6)

2016-03-24T21:54:04.300Z - debug: Socket disconnected: transport close 0 (LGE-LG-H815)

2016-03-24T21:54:04.431Z - debug: Socket disconnected: transport close 4 (samsung-SM-N910C)

2016-03-24T22:10:07.623Z - debug: Socket disconnected: transport close 3 (Apple-Iphone5s-1)

2016-03-24T22:10:07.654Z - debug: Socket disconnected: transport close 1 (Apple-Iphone5-1)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m
2016-03-24T21:51:09.308Z - error: Too many emit retries to device: Apple-Iphone6-1

2016-03-24T21:51:09.314Z - error: Too many emit retries to device: Apple-Iphone5s-1

2016-03-24T21:51:24.662Z - error: Too many emit retries to device: Apple-Iphone5s-1

2016-03-24T21:51:44.536Z - error: Too many emit retries to device: Apple-Iphone5-1

2016-03-24T21:51:44.539Z - error: Too many emit retries to device: Apple-Iphone5s-1


```


Logs for system : 
```

android : No Error

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code 254 on device 2a65f58f9902a701b5c9a55b2befb18672927474 
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true

```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/639808773799dbd_PSK_Support_yaronyg/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/639808773799dbd_PSK_Support_yaronyg/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/639808773799dbd_PSK_Support_yaronyg/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/639808773799dbd_PSK_Support_yaronyg/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/639808773799dbd_PSK_Support_yaronyg/iOS_server.md)




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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/639808773799dbd_PSK_Support_yaronyg/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/639808773799dbd_PSK_Support_yaronyg/thali07_LGE-LG-H815.md)

####Node name: thali08
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Device test finished on ZX1G429CRK 
Android task is completed. [SUCCESS]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/639808773799dbd_PSK_Support_yaronyg/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/639808773799dbd_PSK_Support_yaronyg/thali08_motorola-Nexus 6.md)



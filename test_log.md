#### Test 639107046bb5f66 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-03-23T16:56:14.620Z - info: listening on *:3000

2016-03-23T16:56:15.434Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:0

2016-03-23T16:56:16.213Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:1

2016-03-23T16:56:16.530Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:2

2016-03-23T16:56:19.655Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:3

2016-03-23T16:56:19.658Z - info: Required number of ios devices presented (3)

2016-03-23T16:56:19.664Z - info: Starting unit test run for platform: ios

2016-03-23T16:56:21.075Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-23T16:56:21.631Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-23T16:56:22.026Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-23T16:56:22.446Z - info: Running on ios test: 4. native server connections all up

2016-03-23T16:56:22.915Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-23T16:56:23.883Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-23T16:56:24.394Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-23T16:56:24.765Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:4

2016-03-23T16:56:24.953Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-23T16:56:25.489Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-23T16:56:27.624Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-23T16:56:28.152Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-23T16:56:28.700Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-23T16:56:29.071Z - info: Running on ios test: 13. closeAll with promise

2016-03-23T16:56:29.471Z - info: Running on ios test: 14. multiplex can send data

2016-03-23T16:56:29.898Z - info: Running on ios test: 15. enqueue and run in order

2016-03-23T16:56:30.463Z - info: Running on ios test: 16. enqueueAtTop and run backwards

2016-03-23T16:56:30.857Z - info: Running on ios test: 17. mix enqueue and enqueueAtTop

2016-03-23T16:56:31.352Z - info: Running on ios test: 18. queues handled independently

2016-03-23T16:56:31.761Z - info: Running on ios test: 19. basic

2016-03-23T16:56:32.170Z - info: Running on ios test: 20. another

2016-03-23T16:56:32.557Z - info: Running on ios test: 21. can pass data in setup

2016-03-23T16:56:32.959Z - info: Running on ios test: 22. #startListeningForAdvertisements should fail if start not called

2016-03-23T16:56:33.401Z - info: Running on ios test: 23. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-23T16:56:33.748Z - info: Running on ios test: 24. should be able to call #stopListeningForAdvertisements many times

2016-03-23T16:56:34.206Z - info: Running on ios test: 25. should be able to call #startListeningForAdvertisements many times

2016-03-23T16:56:34.852Z - info: Running on ios test: 26. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-23T16:56:43.148Z - info: Running on ios test: 27. should be able to call #stopAdvertisingAndListening many times

2016-03-23T16:56:46.229Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:5

2016-03-23T16:56:46.232Z - info: Required number of android devices presented (3)

2016-03-23T16:56:46.237Z - info: Starting unit test run for platform: android

2016-03-23T16:56:52.648Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-23T16:56:57.623Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-23T16:57:00.971Z - info: Running on ios test: 28. #start should fail if called twice in a row

2016-03-23T16:57:01.569Z - info: Running on ios test: 29. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-23T16:57:01.770Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-23T16:57:02.070Z - info: Running on ios test: 30. does not send duplicate availability changes

2016-03-23T16:57:02.881Z - info: Running on android test: 4. native server connections all up

2016-03-23T16:57:02.929Z - info: Running on ios test: 31. can get the network status

2016-03-23T16:57:05.980Z - info: Running on ios test: 32. wifi peer is marked unavailable if announcements stop

2016-03-23T16:57:06.088Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-23T16:57:07.199Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-23T16:57:07.851Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-23T16:57:08.338Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-23T16:57:08.574Z - info: Running on ios test: 33. Can call start/stopListeningForAdvertisements

2016-03-23T16:57:08.844Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-23T16:57:10.157Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-23T16:57:10.635Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-23T16:57:11.136Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-23T16:57:11.614Z - info: Running on android test: 13. closeAll with promise

2016-03-23T16:57:11.957Z - info: Running on android test: 14. multiplex can send data

2016-03-23T16:57:12.498Z - info: Running on android test: 15. enqueue and run in order

2016-03-23T16:57:13.335Z - info: Running on android test: 16. enqueueAtTop and run backwards

2016-03-23T16:57:13.897Z - info: Running on android test: 17. mix enqueue and enqueueAtTop

2016-03-23T16:57:14.347Z - info: Running on android test: 18. queues handled independently

2016-03-23T16:57:14.702Z - info: Running on android test: 19. basic

2016-03-23T16:57:15.060Z - info: Running on android test: 20. another

2016-03-23T16:57:15.557Z - info: Running on android test: 21. can pass data in setup

2016-03-23T16:57:15.947Z - info: Running on android test: 22. #startListeningForAdvertisements should fail if start not called

2016-03-23T16:57:16.342Z - info: Running on android test: 23. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-23T16:57:16.835Z - info: Running on android test: 24. should be able to call #stopListeningForAdvertisements many times

2016-03-23T16:57:17.282Z - info: Running on android test: 25. should be able to call #startListeningForAdvertisements many times

2016-03-23T16:57:18.037Z - info: Running on android test: 26. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-23T16:57:18.892Z - info: Running on android test: 27. should be able to call #stopAdvertisingAndListening many times

2016-03-23T16:57:19.233Z - info: Running on android test: 28. #start should fail if called twice in a row

2016-03-23T16:57:19.567Z - info: Running on android test: 29. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-23T16:57:20.456Z - info: Running on android test: 30. does not send duplicate availability changes

2016-03-23T16:57:20.832Z - info: Running on android test: 31. can get the network status

2016-03-23T16:57:21.155Z - info: Running on android test: 32. wifi peer is marked unavailable if announcements stop

2016-03-23T16:57:23.578Z - info: Running on android test: 33. Can call start/stopListeningForAdvertisements

2016-03-23T16:57:24.013Z - info: Running on android test: 34. Calling startListeningForAdvertisements twice is NOT an error

2016-03-23T16:57:24.673Z - info: Running on android test: 35. Can call start/stopUpdateAdvertisingAndListening

2016-03-23T16:57:25.257Z - info: Running on android test: 36. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-23T16:57:26.067Z - info: Running on android test: 37. peerAvailabilityChange is called

2016-03-23T16:57:27.716Z - info: Running on android test: 38. Can connect to a remote peer

2016-03-23T16:57:41.066Z - info: Running on android test: 39. Can shift large amounts of data

2016-03-23T16:57:54.086Z - info: Running on android test: 40. #startListeningForAdvertisements should fail if start not called

2016-03-23T16:57:54.931Z - info: Running on android test: 41. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-23T16:57:55.428Z - info: Running on android test: 42. should be able to call #stopListeningForAdvertisements many times

2016-03-23T16:57:55.865Z - info: Running on android test: 43. should be able to call #startListeningForAdvertisements many times

2016-03-23T16:57:56.424Z - info: Running on android test: 44. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-23T16:57:57.471Z - info: Running on android test: 45. should be able to call #stopAdvertisingAndListening many times

2016-03-23T16:57:58.778Z - info: Running on android test: 46. can get the network status before starting

2016-03-23T16:57:59.262Z - info: Running on android test: 47. error returned with bad router

2016-03-23T16:57:59.600Z - info: Running on android test: 48. all services are stopped when we call stop

2016-03-23T16:58:00.414Z - info: Running on android test: 49. make sure terminateConnection is properly hooked up

2016-03-23T16:58:00.791Z - info: Running on android test: 50. make sure terminateListener is properly hooked up

2016-03-23T16:58:01.191Z - info: Running on android test: 51. make sure we actually call kill connections properly

2016-03-23T16:58:01.661Z - info: Running on android test: 52. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received

2016-03-23T16:58:02.090Z - info: Running on android test: 53. We repeat failedConnection event when we get it from thaliTcpServersManager

2016-03-23T16:58:02.470Z - info: Running on android test: 54. we successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-23T16:58:03.618Z - warn: Failed on android test: 54. we successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-23T16:58:03.619Z - info: Running on android test: 55. can do HTTP requests between peers

2016-03-23T16:58:13.480Z - info: Running on android test: 56. Test BEACONS_RETRIEVED_AND_PARSED locally

2016-03-23T16:58:15.788Z - info: Running on android test: 57. Test HTTP_BAD_RESPONSE locally

2016-03-23T16:58:16.352Z - info: Running on android test: 58. Test NETWORK_PROBLEM locally

2016-03-23T16:58:17.682Z - info: Running on android test: 59. Test timeout locally

2016-03-23T16:58:19.169Z - info: Running on android test: 60. Call the start two times

2016-03-23T16:58:19.693Z - info: Running on android test: 61. Call the kill before calling the start

2016-03-23T16:58:20.249Z - info: Running on android test: 62. Call the kill immediately after the start

2016-03-23T16:58:20.876Z - info: Running on android test: 63. Call the kill while waiting a response from the server

2016-03-23T16:58:23.408Z - info: Running on android test: 64. Test to exceed the max content size locally

2016-03-23T16:58:24.012Z - info: Running on android test: 65. Close the server socket while the client is waiting a response from the server. Local test.

2016-03-23T16:58:26.513Z - info: Running on android test: 66. Close the client socket while the client is waiting a response from the server. Local test.

2016-03-23T16:58:29.061Z - info: Running on android test: 67. #generatePreambleAndBeacons bad args

2016-03-23T16:58:29.381Z - info: Running on android test: 68. #generatePreambleAndBeacons empty keys to notify

2016-03-23T16:58:29.826Z - info: Running on android test: 69. #generatePreambleAndBeacons multiple keys to notify

2016-03-23T16:58:30.355Z - info: Running on android test: 70. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-23T16:58:30.834Z - info: Running on android test: 71. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-23T16:58:31.230Z - info: Running on android test: 72. #parseBeacons expiration out of range lower

2016-03-23T16:58:31.682Z - info: Running on android test: 73. #parseBeacons expiration out of range lower

2016-03-23T16:58:32.100Z - info: Running on android test: 74. #parseBeacons no beacons returns null

2016-03-23T16:58:32.417Z - info: Running on android test: 75. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-23T16:58:32.860Z - info: Running on android test: 76. #parseBeacons addressBookCallback fails decrypt

2016-03-23T16:58:33.387Z - info: Running on android test: 77. #parseBeacons addressBookCallback returns no matches

2016-03-23T16:58:34.452Z - debug: Socket disconnected: ping timeout 3 (Apple-Iphone6-1)

2016-03-23T16:58:37.499Z - info: Running on android test: 78. #parseBeacons addressBookCallback returns spurious match

2016-03-23T16:58:38.289Z - info: Running on android test: 79. #parseBeacons addressBookCallback returns public key

2016-03-23T16:58:38.834Z - info: Running on android test: 80. validate generatePskIdentityField

2016-03-23T16:58:39.199Z - info: Running on android test: 81. validate generatePskSecret

2016-03-23T16:58:39.632Z - info: Running on android test: 82. Add two Peers.

2016-03-23T16:58:40.113Z - info: Running on android test: 83. TCP_NATIVE peer loses DNS

2016-03-23T16:58:40.596Z - info: Running on android test: 84. Resolves an action locally

2016-03-23T16:58:41.180Z - info: Running on android test: 85. Resolves an action locally using ThaliPeerPoolDefault

2016-03-23T16:58:41.723Z - info: Running on android test: 86. Action fails because of a bad hostname.

2016-03-23T16:58:51.769Z - info: Running on android test: 87. hostaddress is removed when the action is running. 

2016-03-23T16:58:54.318Z - info: Running on android test: 88. Start and stop ThaliNotificationServer

2016-03-23T16:58:54.862Z - info: Running on android test: 89. Pass an empty array to ThaliNotificationServer.start

2016-03-23T16:58:55.327Z - info: Running on android test: 90. Pass a string to ThaliNotificationServer.start

2016-03-23T16:58:55.811Z - info: Running on android test: 91. Pass an empty parameter to ThaliNotificationServer.start

2016-03-23T16:58:56.237Z - info: Running on android test: 92. Make an HTTP request to /NotificationBeacons

2016-03-23T16:58:56.885Z - info: Running on android test: 93. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-23T16:58:57.354Z - info: Running on android test: 94. Make an HTTP request to /NotificationBeaconsbefore calling start

2016-03-23T16:58:57.801Z - info: Running on android test: 95. #testThaliPeerAction - test getters

2016-03-23T16:58:58.168Z - info: Running on android test: 96. #testThaliPeerAction - start and kill

2016-03-23T16:58:58.579Z - info: Running on android test: 97. #testThaliPeerAction - double start

2016-03-23T16:58:58.925Z - info: Running on android test: 98. #testThaliPeerAction - start after kill

2016-03-23T16:58:59.372Z - info: Running on android test: 99. #testThaliPeerAction - make sure ids are unique

2016-03-23T16:58:59.737Z - info: Running on android test: 100. Test PeerConnectionInformation basics

2016-03-23T16:59:00.123Z - info: Running on android test: 101. Test PeerDictionary basic functionality

2016-03-23T16:59:00.564Z - info: Running on android test: 102. Test PeerDictionary with multiple entries.

2016-03-23T16:59:02.391Z - info: Running on android test: 103. RESOLVED entries are removed before WAITING state entry.

2016-03-23T16:59:03.420Z - info: Running on android test: 104. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-23T16:59:04.458Z - info: Running on android test: 105. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-23T16:59:05.510Z - info: Running on android test: 106. #ThaliPeerPoolInterface - bad enqueues

2016-03-23T16:59:05.922Z - info: Running on android test: 107. #ThaliPeerPoolInterface - do not allow same object type

2016-03-23T16:59:06.375Z - info: Running on android test: 108. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-23T16:59:06.753Z - info: Running on android test: 109. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent

2016-03-23T16:59:07.220Z - info: Running on android test: 110. compareBufferArrays

2016-03-23T16:59:07.578Z - info: Running on android test: 111. Call start twice and get error

2016-03-23T16:59:07.942Z - info: Running on android test: 112. Start and make sure it runs

2016-03-23T16:59:08.325Z - info: Running on android test: 113. Make sure getTimeWhenRun is right after start

2016-03-23T16:59:08.683Z - info: Running on android test: 114. Make sure getTimeWhenRun is -1 after function is called

2016-03-23T16:59:09.069Z - info: Running on android test: 115. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-23T16:59:09.485Z - info: Running on android test: 116. Test TransientState

2016-03-23T16:59:09.895Z - info: Running on android test: 117. No peers and empty database

2016-03-23T16:59:10.791Z - info: Running on android test: 118. One peer and empty DB

2016-03-23T16:59:15.080Z - info: Running on android test: 119. One peer with _Local set behind current seq

2016-03-23T16:59:15.907Z - info: Running on android test: 120. One peer with _Local set equal to current seq

2016-03-23T16:59:17.022Z - info: Running on android test: 121. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-23T16:59:18.245Z - info: Running on android test: 122. Three peers, one not in DB, one behind and one ahead

2016-03-23T16:59:19.319Z - info: Running on android test: 123. More than maximum peers, make sure we only send maximum allowed

2016-03-23T16:59:20.388Z - info: Running on android test: 124. two peers with empty DB, update the doc

2016-03-23T16:59:21.335Z - info: Running on android test: 125. add doc and make sure tokens refresh when they expire

2016-03-23T16:59:22.334Z - info: Running on android test: 126. start and stop and start and stop

2016-03-23T16:59:23.288Z - info: Running on android test: 127. two identical starts in a row

2016-03-23T16:59:24.102Z - info: Running on android test: 128. two different starts in a row

2016-03-23T16:59:24.823Z - info: Running on android test: 129. two stops and a start and two stops

2016-03-23T16:59:25.348Z - info: Running on android test: 130. we properly enqueue requests so no then needed

2016-03-23T16:59:25.858Z - info: Running on android test: 131. test calculateSeqPointKeyId

2016-03-23T16:59:26.434Z - info: Running on android test: 132. can create servers manager

2016-03-23T16:59:26.790Z - info: Running on android test: 133. calling stop without start causes error

2016-03-23T16:59:27.211Z - info: Running on android test: 134. can start/stop servers manager

2016-03-23T16:59:27.673Z - info: Running on android test: 135. starting twice resolves with listening port

2016-03-23T16:59:28.114Z - info: Running on android test: 136. terminateIncomingConnection will terminate a connection

2016-03-23T16:59:28.553Z - info: Running on android test: 137. terminate an Outgoing connection will terminate the server

2016-03-23T16:59:28.943Z - info: Running on android test: 138. terminate an Outgoing connection with wrong arguments is not harmful

2016-03-23T16:59:29.434Z - info: Running on android test: 139. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-23T16:59:29.830Z - info: Running on android test: 140. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-23T16:59:30.336Z - info: Running on android test: 141. messages with invalid location or USN should be ignored

2016-03-23T16:59:30.779Z - info: Running on android test: 142. verify that Thali-specific messages are filtered correctly

2016-03-23T16:59:31.203Z - info: Running on android test: 143. #startListeningForAdvertisements should fail if start not called

2016-03-23T16:59:31.587Z - info: Running on android test: 144. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-23T16:59:32.013Z - info: Running on android test: 145. #start should fail if called twice in a row

2016-03-23T16:59:32.451Z - info: Running on android test: 146. should not be started after stop is called

2016-03-23T16:59:33.088Z - info: Running on android test: 147. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-23T16:59:33.514Z - info: Running on android test: 148. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-23T16:59:33.959Z - info: Running on android test: 149. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-23T16:59:34.411Z - info: Running on android test: 150. #stop can be called multiple times in a row

2016-03-23T16:59:34.827Z - info: Running on android test: 151. #startListeningForAdvertisements can be called multiple times in a row

2016-03-23T16:59:35.301Z - info: Running on android test: 152. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-23T16:59:35.830Z - info: Running on android test: 153. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-23T16:59:36.411Z - info: Running on android test: 154. functions are run from a queue in the right order

2016-03-23T16:59:36.859Z - info: Running on android test: 155. #ThaliPeerPoolDefault - single action

2016-03-23T16:59:37.262Z - info: Running on android test: 156. #ThaliPeerPoolDefault - multiple actions

2016-03-23T16:59:37.837Z - info: Test run on android complete

2016-03-23T16:59:37.839Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-23T16:59:37.842Z - info: PLATFORM: android

2016-03-23T16:59:37.843Z - info: RESULT: FAIL

2016-03-23T16:59:37.844Z - info: 156 of 156 tests completed

2016-03-23T16:59:37.845Z - info: 155/156 passed (1 failures)

2016-03-23T16:59:37.846Z - info: 

--- Failed tests ---

2016-03-23T16:59:37.847Z - warn: 54. we successfully receive and replay discoveryAdvertisingStateUpdate - fail

2016-03-23T16:59:37.849Z - info: 

-== END ==-

2016-03-23T16:59:38.590Z - debug: Socket disconnected: transport close 5 (motorola-Nexus 6)

2016-03-23T16:59:38.673Z - debug: Socket disconnected: transport close 1 (LGE-LG-H815)

2016-03-23T16:59:38.705Z - debug: Socket disconnected: transport close 4 (samsung-SM-N910C)

2016-03-23T17:15:55.778Z - debug: Socket disconnected: transport close 0 (Apple-Iphone5-1)

2016-03-23T17:15:55.784Z - debug: Socket disconnected: transport close 2 (Apple-Iphone5s-1)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m
2016-03-23T16:56:52.185Z - error: Too many emit retries to device: Apple-Iphone5-1


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
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
true

```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/639107046bb5f66_416_ThaliNotificationClient_juhanak/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/639107046bb5f66_416_ThaliNotificationClient_juhanak/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/639107046bb5f66_416_ThaliNotificationClient_juhanak/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/639107046bb5f66_416_ThaliNotificationClient_juhanak/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/639107046bb5f66_416_ThaliNotificationClient_juhanak/iOS_server.md)




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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/639107046bb5f66_416_ThaliNotificationClient_juhanak/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/639107046bb5f66_416_ThaliNotificationClient_juhanak/thali07_LGE-LG-H815.md)

####Node name: thali08
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Device test finished on ZX1G429CRK 
Android task is completed. [SUCCESS]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/639107046bb5f66_416_ThaliNotificationClient_juhanak/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/639107046bb5f66_416_ThaliNotificationClient_juhanak/thali08_motorola-Nexus 6.md)



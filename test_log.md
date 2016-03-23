#### Test 63848581b00dd7c Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-03-23T12:05:48.086Z - info: listening on *:3000

2016-03-23T12:05:48.711Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:0

2016-03-23T12:05:48.822Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:1

2016-03-23T12:05:49.931Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:2

2016-03-23T12:05:52.084Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:3

2016-03-23T12:05:52.085Z - info: Required number of ios devices presented (3)

2016-03-23T12:05:52.091Z - info: Starting unit test run for platform: ios

2016-03-23T12:05:52.472Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:4

2016-03-23T12:05:52.473Z - info: Discarding surplus device: Apple-Iphone6-1

2016-03-23T12:05:52.900Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-23T12:05:55.158Z - debug: Socket disconnected: transport close 4 (Apple-Iphone6-1)

2016-03-23T12:05:57.119Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:5

2016-03-23T12:05:58.402Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-23T12:06:02.593Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-23T12:06:04.227Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:6

2016-03-23T12:06:04.228Z - info: Required number of android devices presented (3)

2016-03-23T12:06:04.230Z - info: Starting unit test run for platform: android

2016-03-23T12:06:04.991Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-23T12:06:05.487Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-23T12:06:05.954Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-23T12:06:06.444Z - info: Running on android test: 4. native server connections all up

2016-03-23T12:06:07.066Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-23T12:06:07.402Z - info: Running on ios test: 4. native server connections all up

2016-03-23T12:06:07.545Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-23T12:06:08.027Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-23T12:06:08.224Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-23T12:06:08.654Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-23T12:06:08.869Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-23T12:06:09.152Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-23T12:06:09.413Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-23T12:06:09.938Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-23T12:06:10.091Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-23T12:06:10.406Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-23T12:06:10.567Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-23T12:06:11.179Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-23T12:06:11.582Z - info: Running on android test: 13. closeAll with promise

2016-03-23T12:06:12.048Z - info: Running on android test: 14. multiplex can send data

2016-03-23T12:06:12.456Z - info: Running on android test: 15. enqueue and run in order

2016-03-23T12:06:12.613Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-23T12:06:13.154Z - info: Running on android test: 16. enqueueAtTop and run backwards

2016-03-23T12:06:13.672Z - info: Running on android test: 17. mix enqueue and enqueueAtTop

2016-03-23T12:06:14.286Z - info: Running on android test: 18. queues handled independently

2016-03-23T12:06:15.222Z - info: Running on android test: 19. basic

2016-03-23T12:06:15.227Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-23T12:06:15.926Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-23T12:06:16.085Z - info: Running on android test: 20. another

2016-03-23T12:06:16.440Z - info: Running on ios test: 13. closeAll with promise

2016-03-23T12:06:16.625Z - info: Running on android test: 21. can pass data in setup

2016-03-23T12:06:16.957Z - info: Running on ios test: 14. multiplex can send data

2016-03-23T12:06:17.102Z - info: Running on android test: 22. #startListeningForAdvertisements should fail if start not called

2016-03-23T12:06:17.620Z - info: Running on ios test: 15. enqueue and run in order

2016-03-23T12:06:17.650Z - info: Running on android test: 23. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-23T12:06:18.535Z - info: Running on ios test: 16. enqueueAtTop and run backwards

2016-03-23T12:06:18.717Z - info: Running on android test: 24. should be able to call #stopListeningForAdvertisements many times

2016-03-23T12:06:19.102Z - info: Running on ios test: 17. mix enqueue and enqueueAtTop

2016-03-23T12:06:20.009Z - info: Running on ios test: 18. queues handled independently

2016-03-23T12:06:20.154Z - info: Running on android test: 25. should be able to call #startListeningForAdvertisements many times

2016-03-23T12:06:20.643Z - info: Running on ios test: 19. basic

2016-03-23T12:06:21.148Z - info: Running on ios test: 20. another

2016-03-23T12:06:21.220Z - info: Running on android test: 26. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-23T12:06:21.523Z - info: Running on ios test: 21. can pass data in setup

2016-03-23T12:06:21.975Z - info: Running on ios test: 22. #startListeningForAdvertisements should fail if start not called

2016-03-23T12:06:22.213Z - info: Running on android test: 27. should be able to call #stopAdvertisingAndListening many times

2016-03-23T12:06:22.347Z - info: Running on ios test: 23. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-23T12:06:22.689Z - info: Running on android test: 28. #start should fail if called twice in a row

2016-03-23T12:06:22.755Z - info: Running on ios test: 24. should be able to call #stopListeningForAdvertisements many times

2016-03-23T12:06:23.155Z - info: Running on android test: 29. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-23T12:06:23.210Z - info: Running on ios test: 25. should be able to call #startListeningForAdvertisements many times

2016-03-23T12:06:26.115Z - info: Running on ios test: 26. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-23T12:06:26.136Z - info: Running on android test: 30. does not send duplicate availability changes

2016-03-23T12:06:29.234Z - info: Running on ios test: 27. should be able to call #stopAdvertisingAndListening many times

2016-03-23T12:06:29.799Z - info: Running on android test: 31. can get the network status

2016-03-23T12:06:30.291Z - info: Running on android test: 32. wifi peer is marked unavailable if announcements stop

2016-03-23T12:06:32.440Z - info: Running on ios test: 28. #start should fail if called twice in a row

2016-03-23T12:06:32.749Z - info: Running on android test: 33. Can call start/stopListeningForAdvertisements

2016-03-23T12:06:33.320Z - info: Running on android test: 34. Calling startListeningForAdvertisements twice is NOT an error

2016-03-23T12:06:34.204Z - info: Running on android test: 35. Can call start/stopUpdateAdvertisingAndListening

2016-03-23T12:06:34.968Z - info: Running on ios test: 29. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-23T12:06:35.256Z - info: Running on android test: 36. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-23T12:06:35.656Z - info: Running on ios test: 30. does not send duplicate availability changes

2016-03-23T12:06:36.266Z - info: Running on android test: 37. peerAvailabilityChange is called

2016-03-23T12:06:36.758Z - info: Running on ios test: 31. can get the network status

2016-03-23T12:06:39.013Z - info: Running on android test: 38. Can connect to a remote peer

2016-03-23T12:06:39.300Z - info: Running on ios test: 32. wifi peer is marked unavailable if announcements stop

2016-03-23T12:06:43.454Z - info: Running on ios test: 33. Can call start/stopListeningForAdvertisements

2016-03-23T12:06:47.071Z - info: Running on ios test: 34. Calling startListeningForAdvertisements twice is NOT an error

2016-03-23T12:06:48.554Z - info: Running on ios test: 35. Can call start/stopUpdateAdvertisingAndListening

2016-03-23T12:06:49.725Z - info: Running on ios test: 36. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-23T12:06:50.345Z - info: Running on ios test: 37. peerAvailabilityChange is called

2016-03-23T12:06:52.248Z - info: Running on ios test: 38. Can connect to a remote peer

2016-03-23T12:06:53.776Z - info: Running on android test: 39. Can shift large amounts of data

2016-03-23T12:07:03.009Z - info: Running on android test: 40. #startListeningForAdvertisements should fail if start not called

2016-03-23T12:07:03.913Z - info: Running on android test: 41. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-23T12:07:04.529Z - info: Running on android test: 42. should be able to call #stopListeningForAdvertisements many times

2016-03-23T12:07:04.971Z - info: Running on android test: 43. should be able to call #startListeningForAdvertisements many times

2016-03-23T12:07:05.802Z - info: Running on android test: 44. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-23T12:07:06.862Z - info: Running on android test: 45. should be able to call #stopAdvertisingAndListening many times

2016-03-23T12:07:07.412Z - info: Running on android test: 46. can get the network status before starting

2016-03-23T12:07:07.895Z - info: Running on android test: 47. error returned with bad router

2016-03-23T12:07:08.269Z - info: Running on android test: 48. all services are stopped when we call stop

2016-03-23T12:07:09.207Z - info: Running on android test: 49. make sure terminateConnection is properly hooked up

2016-03-23T12:07:11.726Z - info: Running on android test: 50. make sure terminateListener is properly hooked up

2016-03-23T12:07:12.225Z - info: Running on android test: 51. make sure we actually call kill connections properly

2016-03-23T12:07:12.622Z - info: Running on android test: 52. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received

2016-03-23T12:07:13.093Z - info: Running on android test: 53. We repeat failedConnection event when we get it from thaliTcpServersManager

2016-03-23T12:07:13.607Z - info: Running on android test: 54. we successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-23T12:07:14.699Z - warn: Failed on android test: 54. we successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-23T12:07:14.701Z - info: Running on android test: 55. can do HTTP requests between peers

2016-03-23T12:07:36.685Z - warn: Failed on android test: 55. can do HTTP requests between peers

2016-03-23T12:07:36.686Z - info: Running on android test: 56. Test BEACONS_RETRIEVED_AND_PARSED locally

2016-03-23T12:07:39.038Z - info: Running on android test: 57. Test HTTP_BAD_RESPONSE locally

2016-03-23T12:07:40.121Z - info: Running on android test: 58. Test NETWORK_PROBLEM locally

2016-03-23T12:07:43.919Z - info: Running on android test: 59. Test timeout locally

2016-03-23T12:07:46.875Z - info: Running on android test: 60. Call the start two times

2016-03-23T12:07:47.428Z - info: Running on android test: 61. Call the kill before calling the start

2016-03-23T12:07:48.055Z - info: Running on android test: 62. Call the kill immediately after the start

2016-03-23T12:07:48.535Z - info: Running on android test: 63. Call the kill while waiting a response from the server

2016-03-23T12:07:50.971Z - info: Running on android test: 64. Test to exceed the max content size locally

2016-03-23T12:07:51.503Z - info: Running on android test: 65. Close the server socket while the client is waiting a response from the server. Local test.

2016-03-23T12:07:54.050Z - info: Running on android test: 66. Close the client socket while the client is waiting a response from the server. Local test.

2016-03-23T12:07:56.702Z - info: Running on android test: 67. #generatePreambleAndBeacons bad args

2016-03-23T12:07:57.291Z - info: Running on android test: 68. #generatePreambleAndBeacons empty keys to notify

2016-03-23T12:07:57.824Z - info: Running on android test: 69. #generatePreambleAndBeacons multiple keys to notify

2016-03-23T12:07:58.640Z - info: Running on android test: 70. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-23T12:07:59.053Z - info: Running on android test: 71. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-23T12:07:59.421Z - info: Running on android test: 72. #parseBeacons expiration out of range lower

2016-03-23T12:07:59.877Z - info: Running on android test: 73. #parseBeacons expiration out of range lower

2016-03-23T12:08:00.284Z - info: Running on android test: 74. #parseBeacons no beacons returns null

2016-03-23T12:08:00.590Z - info: Running on android test: 75. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-23T12:08:01.029Z - info: Running on android test: 76. #parseBeacons addressBookCallback fails decrypt

2016-03-23T12:08:01.322Z - warn: Failed on ios test: 38. Can connect to a remote peer

2016-03-23T12:08:01.325Z - info: Running on ios test: 39. Can shift large amounts of data

2016-03-23T12:08:01.530Z - info: Running on android test: 77. #parseBeacons addressBookCallback returns no matches

2016-03-23T12:08:03.153Z - info: Running on android test: 78. #parseBeacons addressBookCallback returns spurious match

2016-03-23T12:08:07.120Z - info: Running on android test: 79. #parseBeacons addressBookCallback returns public key

2016-03-23T12:08:08.058Z - info: Running on android test: 80. validate generatePskIdentityField

2016-03-23T12:08:08.495Z - info: Running on android test: 81. validate generatePskSecret

2016-03-23T12:08:08.886Z - info: Running on android test: 82. Start and stop ThaliNotificationServer

2016-03-23T12:08:09.332Z - info: Running on android test: 83. Pass an empty array to ThaliNotificationServer.start

2016-03-23T12:08:09.787Z - info: Running on android test: 84. Pass a string to ThaliNotificationServer.start

2016-03-23T12:08:10.114Z - info: Running on android test: 85. Pass an empty parameter to ThaliNotificationServer.start

2016-03-23T12:08:10.421Z - info: Running on android test: 86. Make an HTTP request to /NotificationBeacons

2016-03-23T12:08:11.184Z - info: Running on android test: 87. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-23T12:08:12.232Z - info: Running on android test: 88. Make an HTTP request to /NotificationBeaconsbefore calling start

2016-03-23T12:08:12.607Z - info: Running on android test: 89. #testThaliPeerAction - test getters

2016-03-23T12:08:13.018Z - info: Running on android test: 90. #testThaliPeerAction - start and kill

2016-03-23T12:08:13.488Z - info: Running on android test: 91. #testThaliPeerAction - double start

2016-03-23T12:08:14.264Z - info: Running on android test: 92. #testThaliPeerAction - start after kill

2016-03-23T12:08:14.809Z - info: Running on android test: 93. #testThaliPeerAction - make sure ids are unique

2016-03-23T12:08:15.168Z - info: Running on android test: 94. Test PeerConnectionInformation basics

2016-03-23T12:08:15.524Z - info: Running on android test: 95. Test PeerDictionary basic functionality

2016-03-23T12:08:15.947Z - info: Running on android test: 96. Test PeerDictionary with multiple entries.

2016-03-23T12:08:17.771Z - info: Running on android test: 97. RESOLVED entries are removed before WAITING state entry.

2016-03-23T12:08:18.877Z - info: Running on android test: 98. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-23T12:08:19.932Z - info: Running on android test: 99. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-23T12:08:21.152Z - info: Running on android test: 100. #ThaliPeerPoolInterface - bad enqueues

2016-03-23T12:08:21.533Z - info: Running on android test: 101. #ThaliPeerPoolInterface - do not allow same object type

2016-03-23T12:08:22.061Z - info: Running on android test: 102. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-23T12:08:23.769Z - info: Running on android test: 103. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent

2016-03-23T12:08:25.766Z - info: Running on android test: 104. compareBufferArrays

2016-03-23T12:08:26.778Z - info: Running on android test: 105. Call start twice and get error

2016-03-23T12:08:27.140Z - info: Running on android test: 106. Start and make sure it runs

2016-03-23T12:08:27.616Z - info: Running on android test: 107. Make sure getTimeWhenRun is right after start

2016-03-23T12:08:28.104Z - info: Running on android test: 108. Make sure getTimeWhenRun is -1 after function is called

2016-03-23T12:08:28.463Z - info: Running on android test: 109. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-23T12:08:28.844Z - info: Running on android test: 110. Test TransientState

2016-03-23T12:08:29.261Z - info: Running on android test: 111. No peers and empty database

2016-03-23T12:08:29.768Z - info: Running on android test: 112. One peer and empty DB

2016-03-23T12:08:30.585Z - info: Running on android test: 113. One peer with _Local set behind current seq

2016-03-23T12:08:31.287Z - info: Running on android test: 114. One peer with _Local set equal to current seq

2016-03-23T12:08:31.857Z - info: Running on android test: 115. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-23T12:08:32.452Z - info: Running on android test: 116. Three peers, one not in DB, one behind and one ahead

2016-03-23T12:08:33.236Z - info: Running on android test: 117. More than maximum peers, make sure we only send maximum allowed

2016-03-23T12:08:34.403Z - info: Running on android test: 118. two peers with empty DB, update the doc

2016-03-23T12:08:35.375Z - info: Running on android test: 119. add doc and make sure tokens refresh when they expire

2016-03-23T12:08:39.199Z - info: Running on android test: 120. start and stop and start and stop

2016-03-23T12:08:43.743Z - info: Running on android test: 121. two identical starts in a row

2016-03-23T12:08:45.741Z - info: Running on android test: 122. two different starts in a row

2016-03-23T12:08:47.898Z - info: Running on android test: 123. two stops and a start and two stops

2016-03-23T12:08:51.454Z - info: Running on android test: 124. we properly enqueue requests so no then needed

2016-03-23T12:08:53.623Z - info: Running on android test: 125. test calculateSeqPointKeyId

2016-03-23T12:08:55.467Z - info: Running on android test: 126. can create servers manager

2016-03-23T12:08:56.800Z - info: Running on android test: 127. calling stop without start causes error

2016-03-23T12:08:58.067Z - info: Running on android test: 128. can start/stop servers manager

2016-03-23T12:08:58.776Z - info: Running on android test: 129. starting twice resolves with listening port

2016-03-23T12:08:59.218Z - info: Running on android test: 130. terminateIncomingConnection will terminate a connection

2016-03-23T12:08:59.758Z - info: Running on android test: 131. terminate an Outgoing connection will terminate the server

2016-03-23T12:09:00.161Z - info: Running on android test: 132. terminate an Outgoing connection with wrong arguments is not harmful

2016-03-23T12:09:00.654Z - info: Running on android test: 133. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-23T12:09:01.145Z - info: Running on android test: 134. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-23T12:09:01.684Z - info: Running on android test: 135. messages with invalid location or USN should be ignored

2016-03-23T12:09:02.013Z - info: Running on android test: 136. verify that Thali-specific messages are filtered correctly

2016-03-23T12:09:02.462Z - info: Running on android test: 137. #startListeningForAdvertisements should fail if start not called

2016-03-23T12:09:02.930Z - info: Running on android test: 138. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-23T12:09:03.405Z - info: Running on android test: 139. #start should fail if called twice in a row

2016-03-23T12:09:03.843Z - info: Running on android test: 140. should not be started after stop is called

2016-03-23T12:09:04.198Z - info: Running on android test: 141. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-23T12:09:04.606Z - info: Running on android test: 142. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-23T12:09:05.017Z - info: Running on android test: 143. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-23T12:09:05.502Z - info: Running on android test: 144. #stop can be called multiple times in a row

2016-03-23T12:09:06.173Z - info: Running on android test: 145. #startListeningForAdvertisements can be called multiple times in a row

2016-03-23T12:09:06.716Z - info: Running on android test: 146. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-23T12:09:07.200Z - info: Running on android test: 147. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-23T12:09:07.547Z - info: Running on android test: 148. functions are run from a queue in the right order

2016-03-23T12:09:07.986Z - info: Running on android test: 149. #ThaliPeerPoolDefault - single action

2016-03-23T12:09:08.360Z - info: Running on android test: 150. #ThaliPeerPoolDefault - multiple actions

2016-03-23T12:09:08.807Z - info: Test run on android complete

2016-03-23T12:09:08.811Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-23T12:09:08.814Z - info: PLATFORM: android

2016-03-23T12:09:08.814Z - info: RESULT: FAIL

2016-03-23T12:09:08.816Z - info: 150 of 150 tests completed

2016-03-23T12:09:08.817Z - info: 148/150 passed (2 failures)

2016-03-23T12:09:08.818Z - info: 

--- Failed tests ---

2016-03-23T12:09:08.820Z - warn: 54. we successfully receive and replay discoveryAdvertisingStateUpdate - fail

2016-03-23T12:09:08.821Z - warn: 55. can do HTTP requests between peers - fail

2016-03-23T12:09:08.823Z - info: 

-== END ==-

2016-03-23T12:09:09.495Z - debug: Socket disconnected: transport close 6 (motorola-Nexus 6)

2016-03-23T12:09:09.701Z - debug: Socket disconnected: transport close 5 (samsung-SM-N910C)

2016-03-23T12:09:09.771Z - debug: Socket disconnected: transport close 0 (LGE-LG-H815)

2016-03-23T12:10:16.898Z - warn: Failed on ios test: 39. Can shift large amounts of data

2016-03-23T12:10:16.899Z - info: Running on ios test: 40. #startListeningForAdvertisements should fail if start not called

2016-03-23T12:10:18.855Z - info: Running on ios test: 41. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-23T12:10:20.529Z - info: Running on ios test: 42. should be able to call #stopListeningForAdvertisements many times

2016-03-23T12:10:21.603Z - info: Running on ios test: 43. should be able to call #startListeningForAdvertisements many times

2016-03-23T12:10:22.466Z - info: Running on ios test: 44. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-23T12:10:23.236Z - info: Running on ios test: 45. should be able to call #stopAdvertisingAndListening many times

2016-03-23T12:10:24.948Z - info: Running on ios test: 46. can get the network status before starting

2016-03-23T12:10:28.467Z - info: Running on ios test: 47. error returned with bad router

2016-03-23T12:10:29.980Z - info: Running on ios test: 48. all services are stopped when we call stop

2016-03-23T12:10:31.557Z - info: Running on ios test: 49. make sure terminateConnection is properly hooked up

2016-03-23T12:10:37.691Z - info: Running on ios test: 50. make sure terminateListener is properly hooked up

2016-03-23T12:10:38.128Z - info: Running on ios test: 51. make sure we actually call kill connections properly

2016-03-23T12:10:38.636Z - warn: Failed on ios test: 51. make sure we actually call kill connections properly

2016-03-23T12:10:38.637Z - info: Running on ios test: 52. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received

2016-03-23T12:10:39.200Z - info: Running on ios test: 53. We repeat failedConnection event when we get it from thaliTcpServersManager

2016-03-23T12:10:39.588Z - info: Running on ios test: 54. we successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-23T12:25:28.338Z - debug: Socket disconnected: transport close 3 (Apple-IpadAir2-1)

2016-03-23T12:25:28.344Z - debug: Socket disconnected: transport close 1 (Apple-Iphone5-1)

2016-03-23T12:25:28.351Z - debug: Socket disconnected: transport close 2 (Apple-Iphone5s-1)


 
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
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
true

```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/63848581b00dd7c_Fixes_for_thaliMobile_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/63848581b00dd7c_Fixes_for_thaliMobile_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/63848581b00dd7c_Fixes_for_thaliMobile_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/63848581b00dd7c_Fixes_for_thaliMobile_vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/63848581b00dd7c_Fixes_for_thaliMobile_vjrantal/iOS_server.md)




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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/63848581b00dd7c_Fixes_for_thaliMobile_vjrantal/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/63848581b00dd7c_Fixes_for_thaliMobile_vjrantal/thali07_LGE-LG-H815.md)

####Node name: thali08
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Device test finished on ZX1G429CRK 
Android task is completed. [SUCCESS]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/63848581b00dd7c_Fixes_for_thaliMobile_vjrantal/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/63848581b00dd7c_Fixes_for_thaliMobile_vjrantal/thali08_motorola-Nexus 6.md)



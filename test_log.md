#### Test 625090941eef958 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":8}}
2016-03-17T07:39:41.522Z - info: listening on *:3000

2016-03-17T07:39:44.048Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:1

2016-03-17T07:39:44.061Z - debug: Device presented: HTC-HTC One M8s (android) unittest socket:0

2016-03-17T07:39:45.918Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:3

2016-03-17T07:39:45.921Z - info: Required number of ios devices presented (2)

2016-03-17T07:39:45.925Z - info: Starting unit test run for platform: ios

2016-03-17T07:39:46.230Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:4

2016-03-17T07:39:46.232Z - info: Discarding surplus device: Apple-IpadAir2-1

2016-03-17T07:39:46.512Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:5

2016-03-17T07:39:46.513Z - info: Required number of android devices presented (2)

2016-03-17T07:39:46.515Z - info: Starting unit test run for platform: android

2016-03-17T07:39:46.590Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-17T07:39:46.858Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:2

2016-03-17T07:39:46.859Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-17T07:39:47.112Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-17T07:39:47.186Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-17T07:39:47.602Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-17T07:39:47.651Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-17T07:39:48.065Z - info: Running on ios test: 4. native server connections all up

2016-03-17T07:39:48.215Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-17T07:39:48.619Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-17T07:39:48.790Z - info: Running on android test: 4. native server connections all up

2016-03-17T07:39:48.920Z - debug: Socket disconnected: transport close 4 (Apple-IpadAir2-1)

2016-03-17T07:39:49.156Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-17T07:39:49.364Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-17T07:39:49.648Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-17T07:39:49.905Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-17T07:39:50.629Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-17T07:39:51.034Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-17T07:39:51.131Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-17T07:39:51.482Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-17T07:39:52.027Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-17T07:39:52.049Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-17T07:39:52.535Z - debug: Socket disconnected: transport close 2 (Apple-Iphone5s-1)

2016-03-17T07:39:52.981Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-17T07:39:53.111Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-17T07:39:53.619Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-17T07:39:53.928Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-17T07:39:54.209Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-17T07:39:54.525Z - info: Running on ios test: 13. closeAll with promise

2016-03-17T07:39:54.673Z - info: Running on android test: 13. closeAll with promise

2016-03-17T07:39:55.007Z - info: Running on ios test: 14. multiplex can send data

2016-03-17T07:39:55.254Z - info: Running on android test: 14. multiplex can send data

2016-03-17T07:39:55.606Z - info: Running on ios test: 15. enqueue and run in order

2016-03-17T07:39:55.845Z - info: Running on android test: 15. enqueue and run in order

2016-03-17T07:39:56.262Z - info: Running on ios test: 16. enqueueAtTop and run backwards

2016-03-17T07:39:56.534Z - info: Running on android test: 16. enqueueAtTop and run backwards

2016-03-17T07:39:56.757Z - info: Running on ios test: 17. mix enqueue and enqueueAtTop

2016-03-17T07:39:57.122Z - info: Running on android test: 17. mix enqueue and enqueueAtTop

2016-03-17T07:39:57.189Z - info: Running on ios test: 18. queues handled independently

2016-03-17T07:39:57.550Z - info: Running on ios test: 19. basic

2016-03-17T07:39:57.647Z - info: Running on android test: 18. queues handled independently

2016-03-17T07:39:58.007Z - info: Running on ios test: 20. another

2016-03-17T07:39:58.104Z - info: Running on android test: 19. basic

2016-03-17T07:39:58.351Z - info: Running on ios test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-17T07:39:58.469Z - info: Running on android test: 20. another

2016-03-17T07:39:58.704Z - info: Running on ios test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-17T07:39:58.856Z - info: Running on android test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-17T07:39:59.155Z - info: Running on ios test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-17T07:39:59.343Z - info: Running on android test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-17T07:39:59.796Z - info: Running on ios test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-17T07:40:00.024Z - info: Running on android test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-17T07:40:00.877Z - info: Running on ios test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-17T07:40:01.077Z - info: Running on android test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-17T07:40:01.431Z - info: Running on ios test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-17T07:40:01.562Z - info: Running on android test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-17T07:40:01.965Z - info: Running on ios test: 27. #start should fail if called twice in a row

2016-03-17T07:40:02.217Z - info: Running on android test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-17T07:40:02.444Z - info: Running on ios test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-17T07:40:02.711Z - info: Running on android test: 27. #start should fail if called twice in a row

2016-03-17T07:40:02.895Z - info: Running on ios test: 29. does not send duplicate availability changes

2016-03-17T07:40:03.248Z - info: Running on android test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-17T07:40:03.343Z - info: Running on ios test: 30. can get the network status

2016-03-17T07:40:03.779Z - info: Running on ios test: 31. wifi peer is marked unavailable if announcements stop

2016-03-17T07:40:03.819Z - info: Running on android test: 29. does not send duplicate availability changes

2016-03-17T07:40:04.336Z - info: Running on android test: 30. can get the network status

2016-03-17T07:40:04.652Z - info: Running on android test: 31. wifi peer is marked unavailable if announcements stop

2016-03-17T07:40:05.582Z - info: Running on ios test: 32. Can call start/stopListeningForAdvertisements

2016-03-17T07:40:06.095Z - info: Running on android test: 32. Can call start/stopListeningForAdvertisements

2016-03-17T07:40:06.218Z - info: Running on ios test: 33. Calling startListeningForAdvertisements twice is NOT an error

2016-03-17T07:40:07.141Z - info: Running on ios test: 34. Can call start/stopUpdateAdvertisingAndListening

2016-03-17T07:40:07.725Z - info: Running on ios test: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-17T07:40:08.638Z - info: Running on ios test: 36. peerAvailabilityChange is called

2016-03-17T07:40:09.588Z - info: Running on android test: 33. Calling startListeningForAdvertisements twice is NOT an error

2016-03-17T07:40:11.262Z - info: Running on ios test: 37. Can connect to a remote peer

2016-03-17T07:40:16.290Z - info: Running on android test: 34. Can call start/stopUpdateAdvertisingAndListening

2016-03-17T07:40:19.945Z - info: Running on android test: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-17T07:40:26.616Z - info: Running on android test: 36. peerAvailabilityChange is called

2016-03-17T07:40:34.593Z - info: Running on ios test: 38. Can shift large amounts of data

2016-03-17T07:40:59.638Z - info: Running on ios test: 39. can get the network status before starting

2016-03-17T07:41:01.270Z - info: Running on ios test: 40. #generatePreambleAndBeacons bad args

2016-03-17T07:41:02.677Z - info: Running on ios test: 41. #generatePreambleAndBeacons empty keys to notify

2016-03-17T07:41:11.247Z - info: Running on ios test: 42. #generatePreambleAndBeacons multiple keys to notify

2016-03-17T07:41:12.566Z - info: Running on ios test: 43. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-17T07:41:13.922Z - info: Running on ios test: 44. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-17T07:41:17.432Z - info: Running on ios test: 45. #parseBeacons expiration out of range lower

2016-03-17T07:41:18.947Z - info: Running on ios test: 46. #parseBeacons expiration out of range lower

2016-03-17T07:41:22.416Z - info: Running on ios test: 47. #parseBeacons no beacons returns null

2016-03-17T07:41:23.244Z - info: Running on ios test: 48. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-17T07:41:24.521Z - info: Running on ios test: 49. #parseBeacons addressBookCallback fails decrypt

2016-03-17T07:41:25.746Z - info: Running on ios test: 50. #parseBeacons addressBookCallback returns no matches

2016-03-17T07:41:26.610Z - info: Running on ios test: 51. #parseBeacons addressBookCallback returns spurious match

2016-03-17T07:41:27.470Z - info: Running on ios test: 52. #parseBeacons addressBookCallback returns public key

2016-03-17T07:41:28.334Z - info: Running on ios test: 53. #parseBeacons with beacons both for and not for the user

2016-03-17T07:41:29.355Z - info: Running on ios test: 54. Start and stop ThaliNotificationServer

2016-03-17T07:41:29.993Z - info: Running on ios test: 55. Pass an empty array to ThaliNotificationServer.start

2016-03-17T07:41:30.604Z - info: Running on ios test: 56. Pass a string to ThaliNotificationServer.start

2016-03-17T07:41:31.174Z - info: Running on ios test: 57. Pass an empty parameter to ThaliNotificationServer.start

2016-03-17T07:41:31.685Z - info: Running on ios test: 58. Make an HTTP request to /NotificationBeacons

2016-03-17T07:41:32.374Z - info: Running on ios test: 59. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-17T07:41:32.794Z - info: Running on ios test: 60. Make an HTTP request to /NotificationBeacons before calling start

2016-03-17T07:41:33.358Z - info: Running on ios test: 61. #testThaliPeerAction - test getters

2016-03-17T07:41:33.816Z - info: Running on ios test: 62. #testThaliPeerAction - start and kill

2016-03-17T07:41:34.343Z - info: Running on ios test: 63. #testThaliPeerAction - double start

2016-03-17T07:41:34.888Z - info: Running on ios test: 64. #testThaliPeerAction - start after kill

2016-03-17T07:41:35.396Z - info: Running on ios test: 65. #testThaliPeerAction - make sure ids are unique

2016-03-17T07:41:35.832Z - info: Running on ios test: 66. Test PeerConnectionInformation basics

2016-03-17T07:41:36.338Z - info: Running on ios test: 67. Test PeerDictionary basic functionality

2016-03-17T07:41:36.745Z - info: Running on ios test: 68. Test PeerDictionary with multiple entries.

2016-03-17T07:41:39.162Z - info: Running on ios test: 69. RESOLVED entries are removed before WAITING state entry.

2016-03-17T07:41:40.788Z - info: Running on ios test: 70. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-17T07:41:42.207Z - info: Running on ios test: 71. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-17T07:41:43.791Z - info: Running on ios test: 72. #ThaliPeerPoolInterface - bad enqueues

2016-03-17T07:41:44.310Z - info: Running on ios test: 73. #ThaliPeerPoolInterface - do not allow same object type

2016-03-17T07:41:44.826Z - info: Running on ios test: 74. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-17T07:41:45.320Z - info: Running on ios test: 75. compareBufferArrays

2016-03-17T07:41:46.016Z - info: Running on ios test: 76. Call start twice and get error

2016-03-17T07:41:46.676Z - info: Running on ios test: 77. Start and make sure it runs

2016-03-17T07:41:47.331Z - info: Running on ios test: 78. Make sure getTimeWhenRun is right after start

2016-03-17T07:41:47.790Z - info: Running on ios test: 79. Make sure getTimeWhenRun is -1 after function is called

2016-03-17T07:41:48.269Z - info: Running on ios test: 80. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-17T07:41:48.910Z - info: Running on ios test: 81. Test TransientState

2016-03-17T07:41:49.793Z - info: Running on ios test: 82. No peers and empty database

2016-03-17T07:41:50.579Z - info: Running on ios test: 83. One peer and empty DB

2016-03-17T07:41:51.446Z - info: Running on ios test: 84. One peer with _Local set behind current seq

2016-03-17T07:41:52.345Z - info: Running on ios test: 85. One peer with _Local set equal to current seq

2016-03-17T07:41:53.019Z - info: Running on ios test: 86. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-17T07:41:53.885Z - info: Running on ios test: 87. Three peers, one not in DB, one behind and one ahead

2016-03-17T07:41:54.803Z - info: Running on ios test: 88. More than maximum peers, make sure we only send maximum allowed

2016-03-17T07:41:56.535Z - info: Running on ios test: 89. two peers with empty DB, update the doc

2016-03-17T07:41:57.756Z - info: Running on ios test: 90. add doc and make sure tokens refresh when they expire

2016-03-17T07:41:59.104Z - info: Running on ios test: 91. start and stop and start and stop

2016-03-17T07:41:59.921Z - info: Running on ios test: 92. two identical starts in a row

2016-03-17T07:42:00.889Z - info: Running on ios test: 93. two different starts in a row

2016-03-17T07:42:02.270Z - info: Running on ios test: 94. two stops and a start and two stops

2016-03-17T07:42:03.283Z - info: Running on ios test: 95. we properly enqueue requests so no then needed

2016-03-17T07:42:04.009Z - info: Running on ios test: 96. test calculateSeqPointKeyId

2016-03-17T07:42:04.539Z - info: Running on ios test: 97. can create servers manager

2016-03-17T07:42:05.125Z - info: Running on ios test: 98. calling stop without start causes error

2016-03-17T07:42:05.657Z - info: Running on ios test: 99. can start/stop servers manager

2016-03-17T07:42:06.493Z - info: Running on ios test: 100. starting twice resolves with listening port

2016-03-17T07:42:06.883Z - info: Running on ios test: 101. terminateIncomingConnection will terminate a connection

2016-03-17T07:42:07.446Z - info: Running on ios test: 102. terminate an Outgoing connection will terminate the server

2016-03-17T07:42:08.064Z - info: Running on ios test: 103. terminate an Outgoing connection with wrong arguments is not harmful

2016-03-17T07:42:08.514Z - info: Running on ios test: 104. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-17T07:42:09.195Z - info: Running on ios test: 105. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-17T07:42:09.776Z - info: Running on ios test: 106. messages with invalid location or USN should be ignored

2016-03-17T07:42:10.339Z - info: Running on ios test: 107. verify that Thali-specific messages are filtered correctly

2016-03-17T07:42:10.812Z - info: Running on ios test: 108. #startListeningForAdvertisements should fail if start not called

2016-03-17T07:42:11.352Z - info: Running on ios test: 109. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-17T07:42:11.708Z - info: Running on ios test: 110. #start should fail if called twice in a row

2016-03-17T07:42:12.306Z - info: Running on ios test: 111. should not be started after stop is called

2016-03-17T07:42:13.271Z - info: Running on ios test: 112. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-17T07:42:13.904Z - info: Running on ios test: 113. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-17T07:42:14.466Z - info: Running on ios test: 114. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-17T07:42:15.362Z - info: Running on ios test: 115. #stop can be called multiple times in a row

2016-03-17T07:42:15.784Z - info: Running on ios test: 116. #startListeningForAdvertisements can be called multiple times in a row

2016-03-17T07:42:16.240Z - info: Running on ios test: 117. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-17T07:42:16.619Z - info: Running on ios test: 118. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-17T07:42:16.947Z - info: Running on ios test: 119. functions are run from a queue in the right order

2016-03-17T07:42:17.407Z - info: Running on ios test: 120. #ThaliPeerPoolDefault - single action

2016-03-17T07:42:17.930Z - info: Running on ios test: 121. #ThaliPeerPoolDefault - multiple actions

2016-03-17T07:42:18.475Z - info: Test run on ios complete

2016-03-17T07:42:18.477Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-17T07:42:18.479Z - info: PLATFORM: ios

2016-03-17T07:42:18.480Z - info: RESULT: PASS

2016-03-17T07:42:18.481Z - info: 121 of 121 tests completed
2016-03-17T07:42:18.482Z - info: 121/121 passed (0 failures)

2016-03-17T07:42:18.483Z - info: --- Test Details ---



2016-03-17T07:42:18.484Z - info: 1. calling createNativeListener directly rejects - pass
2016-03-17T07:42:18.485Z - info: 2. emits incomingConnectionState - pass

2016-03-17T07:42:18.486Z - info: 3. emits routerPortConnectionFailed - pass

2016-03-17T07:42:18.486Z - info: 4. native server connections all up - pass
2016-03-17T07:42:18.487Z - info: 5. native server - closing incoming stream cleans outgoing socket - pass

2016-03-17T07:42:18.488Z - info: 6. native server - closing incoming connection cleans outgoing socket - pass
2016-03-17T07:42:18.489Z - info: 7. native server - closing outgoing socket cleans associated mux stream - pass
2016-03-17T07:42:18.489Z - info: 8. native server - closing the whole server cleans everything up - pass
2016-03-17T07:42:18.490Z - info: 9. native server - we can get a ton of connections and data through and still clean up the server completely - pass
2016-03-17T07:42:18.490Z - info: 10. native server - simulate mux failure, make sure everything is cleaned up - pass
2016-03-17T07:42:18.491Z - info: 11. native server - timing out the incoming connection cleans everything up - pass
2016-03-17T07:42:18.492Z - info: 12. closeAll can close even when connections open - pass
2016-03-17T07:42:18.492Z - info: 13. closeAll with promise - pass
2016-03-17T07:42:18.493Z - info: 14. multiplex can send data - pass
2016-03-17T07:42:18.494Z - info: 15. enqueue and run in order - pass
2016-03-17T07:42:18.494Z - info: 16. enqueueAtTop and run backwards - pass
2016-03-17T07:42:18.495Z - info: 17. mix enqueue and enqueueAtTop - pass
2016-03-17T07:42:18.495Z - info: 18. queues handled independently - pass
2016-03-17T07:42:18.496Z - info: 19. basic - pass
2016-03-17T07:42:18.497Z - info: 20. another - pass
2016-03-17T07:42:18.497Z - info: 21. #startListeningForAdvertisements should fail if start not called - pass
2016-03-17T07:42:18.497Z - info: 22. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-17T07:42:18.498Z - info: 23. should be able to call #stopListeningForAdvertisements many times - pass
2016-03-17T07:42:18.499Z - info: 24. should be able to call #startListeningForAdvertisements many times - pass
2016-03-17T07:42:18.499Z - info: 25. should be able to call #startUpdateAdvertisingAndListening many times - pass
2016-03-17T07:42:18.500Z - info: 26. should be able to call #stopAdvertisingAndListening many times - pass
2016-03-17T07:42:18.501Z - info: 27. #start should fail if called twice in a row - pass
2016-03-17T07:42:18.501Z - info: 28. does not emit duplicate discoveryAdvertisingStateUpdate - pass
2016-03-17T07:42:18.502Z - info: 29. does not send duplicate availability changes - pass
2016-03-17T07:42:18.503Z - info: 30. can get the network status - pass

2016-03-17T07:42:18.503Z - info: 31. wifi peer is marked unavailable if announcements stop - pass
2016-03-17T07:42:18.504Z - info: 32. Can call start/stopListeningForAdvertisements - pass
2016-03-17T07:42:18.505Z - info: 33. Calling startListeningForAdvertisements twice is NOT an error - pass

2016-03-17T07:42:18.505Z - info: 34. Can call start/stopUpdateAdvertisingAndListening - pass
2016-03-17T07:42:18.506Z - info: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error - pass

2016-03-17T07:42:18.507Z - info: 36. peerAvailabilityChange is called - pass
2016-03-17T07:42:18.508Z - info: 37. Can connect to a remote peer - pass

2016-03-17T07:42:18.508Z - info: 38. Can shift large amounts of data - pass
2016-03-17T07:42:18.509Z - info: 39. can get the network status before starting - pass

2016-03-17T07:42:18.510Z - info: 40. #generatePreambleAndBeacons bad args - pass
2016-03-17T07:42:18.511Z - info: 41. #generatePreambleAndBeacons empty keys to notify - pass
2016-03-17T07:42:18.511Z - info: 42. #generatePreambleAndBeacons multiple keys to notify - pass
2016-03-17T07:42:18.512Z - info: 43. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass
2016-03-17T07:42:18.512Z - info: 44. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass
2016-03-17T07:42:18.513Z - info: 45. #parseBeacons expiration out of range lower - pass
2016-03-17T07:42:18.514Z - info: 46. #parseBeacons expiration out of range lower - pass
2016-03-17T07:42:18.514Z - info: 47. #parseBeacons no beacons returns null - pass
2016-03-17T07:42:18.515Z - info: 48. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass

2016-03-17T07:42:18.516Z - info: 49. #parseBeacons addressBookCallback fails decrypt - pass
2016-03-17T07:42:18.517Z - info: 50. #parseBeacons addressBookCallback returns no matches - pass

2016-03-17T07:42:18.517Z - info: 51. #parseBeacons addressBookCallback returns spurious match - pass

2016-03-17T07:42:18.518Z - info: 52. #parseBeacons addressBookCallback returns public key - pass
2016-03-17T07:42:18.519Z - info: 53. #parseBeacons with beacons both for and not for the user - pass

2016-03-17T07:42:18.519Z - info: 54. Start and stop ThaliNotificationServer - pass
2016-03-17T07:42:18.520Z - info: 55. Pass an empty array to ThaliNotificationServer.start - pass

2016-03-17T07:42:18.521Z - info: 56. Pass a string to ThaliNotificationServer.start - pass
2016-03-17T07:42:18.522Z - info: 57. Pass an empty parameter to ThaliNotificationServer.start - pass

2016-03-17T07:42:18.522Z - info: 58. Make an HTTP request to /NotificationBeacons - pass
2016-03-17T07:42:18.523Z - info: 59. Make an HTTP request to /NotificationBeacons (no keys) - pass

2016-03-17T07:42:18.524Z - info: 60. Make an HTTP request to /NotificationBeacons before calling start - pass
2016-03-17T07:42:18.525Z - info: 61. #testThaliPeerAction - test getters - pass

2016-03-17T07:42:18.525Z - info: 62. #testThaliPeerAction - start and kill - pass

2016-03-17T07:42:18.526Z - info: 63. #testThaliPeerAction - double start - pass
2016-03-17T07:42:18.527Z - info: 64. #testThaliPeerAction - start after kill - pass
2016-03-17T07:42:18.527Z - info: 65. #testThaliPeerAction - make sure ids are unique - pass
2016-03-17T07:42:18.528Z - info: 66. Test PeerConnectionInformation basics - pass

2016-03-17T07:42:18.529Z - info: 67. Test PeerDictionary basic functionality - pass
2016-03-17T07:42:18.530Z - info: 68. Test PeerDictionary with multiple entries. - pass

2016-03-17T07:42:18.530Z - info: 69. RESOLVED entries are removed before WAITING state entry. - pass
2016-03-17T07:42:18.531Z - info: 70. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass

2016-03-17T07:42:18.532Z - info: 71. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass

2016-03-17T07:42:18.532Z - info: 72. #ThaliPeerPoolInterface - bad enqueues - pass
2016-03-17T07:42:18.533Z - info: 73. #ThaliPeerPoolInterface - do not allow same object type - pass

2016-03-17T07:42:18.534Z - info: 74. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass
2016-03-17T07:42:18.535Z - info: 75. compareBufferArrays - pass

2016-03-17T07:42:18.535Z - info: 76. Call start twice and get error - pass
2016-03-17T07:42:18.536Z - info: 77. Start and make sure it runs - pass

2016-03-17T07:42:18.537Z - info: 78. Make sure getTimeWhenRun is right after start - pass
2016-03-17T07:42:18.538Z - info: 79. Make sure getTimeWhenRun is -1 after function is called - pass

2016-03-17T07:42:18.538Z - info: 80. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass
2016-03-17T07:42:18.539Z - info: 81. Test TransientState - pass

2016-03-17T07:42:18.540Z - info: 82. No peers and empty database - pass

2016-03-17T07:42:18.540Z - info: 83. One peer and empty DB - pass
2016-03-17T07:42:18.541Z - info: 84. One peer with _Local set behind current seq - pass

2016-03-17T07:42:18.542Z - info: 85. One peer with _Local set equal to current seq - pass

2016-03-17T07:42:18.543Z - info: 86. One peer with _Local set ahead of current seq (and no this should not happen) - pass
2016-03-17T07:42:18.544Z - info: 87. Three peers, one not in DB, one behind and one ahead - pass

2016-03-17T07:42:18.544Z - info: 88. More than maximum peers, make sure we only send maximum allowed - pass
2016-03-17T07:42:18.545Z - info: 89. two peers with empty DB, update the doc - pass

2016-03-17T07:42:18.546Z - info: 90. add doc and make sure tokens refresh when they expire - pass
2016-03-17T07:42:18.546Z - info: 91. start and stop and start and stop - pass

2016-03-17T07:42:18.547Z - info: 92. two identical starts in a row - pass
2016-03-17T07:42:18.548Z - info: 93. two different starts in a row - pass

2016-03-17T07:42:18.549Z - info: 94. two stops and a start and two stops - pass
2016-03-17T07:42:18.549Z - info: 95. we properly enqueue requests so no then needed - pass

2016-03-17T07:42:18.550Z - info: 96. test calculateSeqPointKeyId - pass
2016-03-17T07:42:18.551Z - info: 97. can create servers manager - pass

2016-03-17T07:42:18.551Z - info: 98. calling stop without start causes error - pass

2016-03-17T07:42:18.552Z - info: 99. can start/stop servers manager - pass
2016-03-17T07:42:18.553Z - info: 100. starting twice resolves with listening port - pass

2016-03-17T07:42:18.553Z - info: 101. terminateIncomingConnection will terminate a connection - pass
2016-03-17T07:42:18.554Z - info: 102. terminate an Outgoing connection will terminate the server - pass

2016-03-17T07:42:18.555Z - info: 103. terminate an Outgoing connection with wrong arguments is not harmful - pass
2016-03-17T07:42:18.556Z - info: 104. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass

2016-03-17T07:42:18.556Z - info: 105. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass
2016-03-17T07:42:18.557Z - info: 106. messages with invalid location or USN should be ignored - pass

2016-03-17T07:42:18.558Z - info: 107. verify that Thali-specific messages are filtered correctly - pass
2016-03-17T07:42:18.559Z - info: 108. #startListeningForAdvertisements should fail if start not called - pass

2016-03-17T07:42:18.559Z - info: 109. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-17T07:42:18.560Z - info: 110. #start should fail if called twice in a row - pass
2016-03-17T07:42:18.561Z - info: 111. should not be started after stop is called - pass

2016-03-17T07:42:18.561Z - info: 112. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass
2016-03-17T07:42:18.562Z - info: 113. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass

2016-03-17T07:42:18.563Z - info: 114. #startUpdateAdvertisingAndListening should start hosting given router object - pass
2016-03-17T07:42:18.564Z - info: 115. #stop can be called multiple times in a row - pass

2016-03-17T07:42:18.564Z - info: 116. #startListeningForAdvertisements can be called multiple times in a row - pass

2016-03-17T07:42:18.569Z - info: 117. #stopListeningForAdvertisements can be called multiple times in a row - pass

2016-03-17T07:42:18.570Z - info: 118. #stopAdvertisingAndListening can be called multiple times in a row - pass
2016-03-17T07:42:18.570Z - info: 119. functions are run from a queue in the right order - pass

2016-03-17T07:42:18.571Z - info: 120. #ThaliPeerPoolDefault - single action - pass
2016-03-17T07:42:18.572Z - info: 121. #ThaliPeerPoolDefault - multiple actions - pass

2016-03-17T07:42:18.573Z - info: 

-== END ==-

2016-03-17T07:42:21.183Z - debug: Socket disconnected: transport close 3 (Apple-Iphone6-1)

2016-03-17T07:42:22.255Z - debug: Socket disconnected: transport close 1 (Apple-Iphone5-1)

2016-03-17T07:59:17.996Z - debug: Socket disconnected: transport close 5 (samsung-SM-N910C)

2016-03-17T08:00:05.181Z - debug: Socket disconnected: transport close 0 (HTC-HTC One M8s)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

ios : false

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  f56ad48d Test has  SUCCEEDED
Device test finished on f56ad48d 
Android task is completed. [SUCCESS]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/625090941eef958_Make_CI_build_and_unit_tests_pass_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/625090941eef958_Make_CI_build_and_unit_tests_pass_vjrantal/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on ZX1C223JKW 
Android task is completed. [SUCCESS]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/625090941eef958_Make_CI_build_and_unit_tests_pass_vjrantal/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:0 
child process exited with code 0 on device LGH8153b36be34 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/625090941eef958_Make_CI_build_and_unit_tests_pass_vjrantal/thali05_LGE-LG-H815.md)

####Node name: thali06
Console output:
```
STOP log received from  7970f88c Test has  SUCCEEDED
Device test finished on 7970f88c 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:null 
child process exited with code null on device FA55PYS00566 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/625090941eef958_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/625090941eef958_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
STOP log received from  4db5c8cc Test has  SUCCEEDED
Device test finished on 4db5c8cc 
Android task is completed. [SUCCESS]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/625090941eef958_Make_CI_build_and_unit_tests_pass_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
STOP log received from  4325e43f Test has  SUCCEEDED
Device test finished on 4325e43f 
Android task is completed. [SUCCESS]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/625090941eef958_Make_CI_build_and_unit_tests_pass_vjrantal/thali08_samsung-SM-A300FU.md)




###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/625090941eef958_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/625090941eef958_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/625090941eef958_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/625090941eef958_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5s-1.md)



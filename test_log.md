#### Test 63012666c2ddc84 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":8}}
2016-03-16T05:32:10.883Z - info: listening on *:3000

2016-03-16T05:32:13.767Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:0

2016-03-16T05:32:14.021Z - debug: Device presented: samsung-SM-A300FU (android) unittest socket:1

2016-03-16T05:32:14.024Z - info: Required number of android devices presented (2)

2016-03-16T05:32:14.027Z - info: Starting unit test run for platform: android

2016-03-16T05:32:14.070Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:2

2016-03-16T05:32:14.555Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-16T05:32:14.637Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:3

2016-03-16T05:32:14.638Z - info: Required number of ios devices presented (2)

2016-03-16T05:32:14.640Z - info: Starting unit test run for platform: ios

2016-03-16T05:32:14.961Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-16T05:32:14.974Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:4

2016-03-16T05:32:14.975Z - info: Discarding surplus device: Apple-Iphone6-1

2016-03-16T05:32:15.223Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-16T05:32:15.350Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-16T05:32:15.574Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:5

2016-03-16T05:32:15.576Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-16T05:32:15.648Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-16T05:32:15.783Z - info: Running on android test: 4. native server connections all up

2016-03-16T05:32:15.869Z - debug: Device presented: samsung-SM-A500FU (android) unittest socket:6

2016-03-16T05:32:15.870Z - info: Discarding surplus device: samsung-SM-A500FU

2016-03-16T05:32:16.073Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-16T05:32:16.456Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-16T05:32:16.545Z - info: Running on ios test: 4. native server connections all up

2016-03-16T05:32:16.833Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-16T05:32:16.950Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-16T05:32:17.249Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-16T05:32:17.390Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-16T05:32:17.437Z - debug: Socket disconnected: transport close 4 (Apple-Iphone6-1)

2016-03-16T05:32:17.694Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-16T05:32:17.750Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-16T05:32:18.079Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-16T05:32:18.146Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-16T05:32:18.384Z - debug: Socket disconnected: transport close 5 (Apple-Iphone5s-1)

2016-03-16T05:32:18.534Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-16T05:32:18.845Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-16T05:32:19.201Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-16T05:32:19.477Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-16T05:32:19.557Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-16T05:32:19.857Z - info: Running on android test: 13. closeAll with promise

2016-03-16T05:32:19.978Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-16T05:32:20.158Z - info: Running on android test: 14. multiplex can send data

2016-03-16T05:32:20.366Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-16T05:32:20.501Z - info: Running on android test: 15. enqueue and run in order

2016-03-16T05:32:20.712Z - info: Running on ios test: 13. closeAll with promise

2016-03-16T05:32:21.007Z - info: Running on ios test: 14. multiplex can send data

2016-03-16T05:32:21.304Z - info: Running on android test: 16. enqueueAtTop and run backwards

2016-03-16T05:32:21.393Z - info: Running on ios test: 15. enqueue and run in order

2016-03-16T05:32:21.670Z - info: Running on android test: 17. mix enqueue and enqueueAtTop

2016-03-16T05:32:21.966Z - info: Running on ios test: 16. enqueueAtTop and run backwards

2016-03-16T05:32:22.178Z - info: Running on android test: 18. queues handled independently

2016-03-16T05:32:22.280Z - info: Running on ios test: 17. mix enqueue and enqueueAtTop

2016-03-16T05:32:22.507Z - info: Running on android test: 19. basic

2016-03-16T05:32:22.663Z - info: Running on ios test: 18. queues handled independently

2016-03-16T05:32:22.773Z - info: Running on android test: 20. another

2016-03-16T05:32:23.036Z - info: Running on android test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-16T05:32:23.052Z - info: Running on ios test: 19. basic

2016-03-16T05:32:23.292Z - info: Running on android test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-16T05:32:23.324Z - info: Running on ios test: 20. another

2016-03-16T05:32:23.471Z - info: Running on android test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-16T05:32:23.588Z - info: Running on ios test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-16T05:32:23.729Z - info: Running on android test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-16T05:32:23.920Z - info: Running on ios test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-16T05:32:24.062Z - info: Running on android test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-16T05:32:24.259Z - info: Running on ios test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-16T05:32:24.386Z - info: Running on android test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-16T05:32:24.543Z - info: Running on ios test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-16T05:32:24.591Z - info: Running on android test: 27. #start should fail if called twice in a row

2016-03-16T05:32:24.803Z - info: Running on ios test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-16T05:32:24.859Z - info: Running on android test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-16T05:32:25.115Z - info: Running on ios test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-16T05:32:25.193Z - info: Running on android test: 29. does not send duplicate availability changes

2016-03-16T05:32:25.443Z - info: Running on ios test: 27. #start should fail if called twice in a row

2016-03-16T05:32:25.582Z - info: Running on android test: 30. can get the network status

2016-03-16T05:32:25.818Z - info: Running on ios test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-16T05:32:25.939Z - info: Running on android test: 31. wifi peer is marked unavailable if announcements stop

2016-03-16T05:32:26.281Z - info: Running on ios test: 29. does not send duplicate availability changes

2016-03-16T05:32:26.565Z - info: Running on ios test: 30. can get the network status

2016-03-16T05:32:26.831Z - info: Running on ios test: 31. wifi peer is marked unavailable if announcements stop

2016-03-16T05:32:27.250Z - info: Running on android test: 32. Can call start/stopListeningForAdvertisements

2016-03-16T05:32:27.638Z - info: Running on android test: 33. Calling startListeningForAdvertisements twice is NOT an error

2016-03-16T05:32:28.201Z - info: Running on android test: 34. Can call start/stopUpdateAdvertisingAndListening

2016-03-16T05:32:28.252Z - info: Running on ios test: 32. Can call start/stopListeningForAdvertisements

2016-03-16T05:32:28.677Z - info: Running on android test: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-16T05:32:28.747Z - info: Running on ios test: 33. Calling startListeningForAdvertisements twice is NOT an error

2016-03-16T05:32:29.267Z - info: Running on android test: 36. peerAvailabilityChange is called

2016-03-16T05:32:29.371Z - info: Running on ios test: 34. Can call start/stopUpdateAdvertisingAndListening

2016-03-16T05:32:30.360Z - info: Running on ios test: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-16T05:32:30.827Z - info: Running on android test: 37. Can connect to a remote peer

2016-03-16T05:32:30.897Z - info: Running on ios test: 36. peerAvailabilityChange is called

2016-03-16T05:32:32.422Z - info: Running on ios test: 37. Can connect to a remote peer

2016-03-16T05:32:57.988Z - info: Running on ios test: 38. Can shift large amounts of data

2016-03-16T05:34:03.585Z - info: Running on ios test: 39. can get the network status before starting

2016-03-16T05:34:06.177Z - info: Running on ios test: 40. #generatePreambleAndBeacons bad args

2016-03-16T05:34:06.733Z - info: Running on ios test: 41. #generatePreambleAndBeacons empty keys to notify

2016-03-16T05:34:07.303Z - info: Running on ios test: 42. #generatePreambleAndBeacons multiple keys to notify

2016-03-16T05:34:07.910Z - info: Running on ios test: 43. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-16T05:34:10.701Z - info: Running on ios test: 44. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-16T05:34:11.777Z - info: Running on ios test: 45. #parseBeacons expiration out of range lower

2016-03-16T05:34:13.180Z - info: Running on ios test: 46. #parseBeacons expiration out of range lower

2016-03-16T05:34:18.968Z - info: Running on ios test: 47. #parseBeacons no beacons returns null

2016-03-16T05:34:25.479Z - info: Running on ios test: 48. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-16T05:34:27.207Z - info: Running on ios test: 49. #parseBeacons addressBookCallback fails decrypt

2016-03-16T05:34:28.031Z - info: Running on ios test: 50. #parseBeacons addressBookCallback returns no matches

2016-03-16T05:34:31.965Z - info: Running on ios test: 51. #parseBeacons addressBookCallback returns spurious match

2016-03-16T05:34:32.407Z - info: Running on ios test: 52. #parseBeacons addressBookCallback returns public key

2016-03-16T05:34:32.978Z - info: Running on ios test: 53. #parseBeacons with beacons both for and not for the user

2016-03-16T05:34:33.943Z - info: Running on ios test: 54. Start and stop ThaliNotificationServer

2016-03-16T05:34:34.726Z - info: Running on ios test: 55. Pass an empty array to ThaliNotificationServer.start

2016-03-16T05:34:36.372Z - info: Running on ios test: 56. Pass a string to ThaliNotificationServer.start

2016-03-16T05:34:37.236Z - info: Running on ios test: 57. Pass an empty parameter to ThaliNotificationServer.start

2016-03-16T05:34:37.625Z - info: Running on ios test: 58. Make an HTTP request to /NotificationBeacons

2016-03-16T05:34:38.263Z - info: Running on ios test: 59. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-16T05:34:39.563Z - info: Running on ios test: 60. Make an HTTP request to /NotificationBeacons before calling start

2016-03-16T05:34:40.567Z - info: Running on ios test: 61. #testThaliPeerAction - test getters

2016-03-16T05:34:40.917Z - info: Running on ios test: 62. #testThaliPeerAction - start and kill

2016-03-16T05:34:41.400Z - info: Running on ios test: 63. #testThaliPeerAction - double start

2016-03-16T05:34:41.728Z - info: Running on ios test: 64. #testThaliPeerAction - start after kill

2016-03-16T05:34:42.030Z - info: Running on ios test: 65. #testThaliPeerAction - make sure ids are unique

2016-03-16T05:34:42.541Z - info: Running on ios test: 66. Test PeerConnectionInformation basics

2016-03-16T05:34:42.895Z - info: Running on ios test: 67. Test PeerDictionary basic functionality

2016-03-16T05:34:43.339Z - info: Running on ios test: 68. Test PeerDictionary with multiple entries.

2016-03-16T05:34:45.721Z - info: Running on ios test: 69. RESOLVED entries are removed before WAITING state entry.

2016-03-16T05:34:47.296Z - info: Running on ios test: 70. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-16T05:34:49.530Z - info: Running on ios test: 71. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-16T05:34:52.511Z - info: Running on ios test: 72. #ThaliPeerPoolInterface - bad enqueues

2016-03-16T05:34:53.917Z - info: Running on ios test: 73. #ThaliPeerPoolInterface - do not allow same object type

2016-03-16T05:34:54.611Z - info: Running on ios test: 74. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-16T05:34:55.457Z - info: Running on ios test: 75. compareBufferArrays

2016-03-16T05:34:55.948Z - info: Running on ios test: 76. Call start twice and get error

2016-03-16T05:34:56.876Z - info: Running on ios test: 77. Start and make sure it runs

2016-03-16T05:34:57.168Z - info: Running on ios test: 78. Make sure getTimeWhenRun is right after start

2016-03-16T05:34:57.618Z - info: Running on ios test: 79. Make sure getTimeWhenRun is -1 after function is called

2016-03-16T05:34:58.009Z - info: Running on ios test: 80. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-16T05:34:58.548Z - info: Running on ios test: 81. Test TransientState

2016-03-16T05:34:59.188Z - info: Running on ios test: 82. No peers and empty database

2016-03-16T05:35:00.525Z - info: Running on ios test: 83. One peer and empty DB

2016-03-16T05:35:01.196Z - info: Running on ios test: 84. One peer with _Local set behind current seq

2016-03-16T05:35:01.756Z - info: Running on ios test: 85. One peer with _Local set equal to current seq

2016-03-16T05:35:02.358Z - info: Running on ios test: 86. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-16T05:35:05.752Z - info: Running on ios test: 87. Three peers, one not in DB, one behind and one ahead

2016-03-16T05:35:06.999Z - info: Running on ios test: 88. More than maximum peers, make sure we only send maximum allowed

2016-03-16T05:35:09.449Z - info: Running on ios test: 89. two peers with empty DB, update the doc

2016-03-16T05:35:11.055Z - info: Running on ios test: 90. add doc and make sure tokens refresh when they expire

2016-03-16T05:35:12.402Z - info: Running on ios test: 91. start and stop and start and stop

2016-03-16T05:35:13.996Z - info: Running on ios test: 92. two identical starts in a row

2016-03-16T05:35:16.190Z - info: Running on ios test: 93. two different starts in a row

2016-03-16T05:35:16.975Z - info: Running on ios test: 94. two stops and a start and two stops

2016-03-16T05:35:18.098Z - info: Running on ios test: 95. we properly enqueue requests so no then needed

2016-03-16T05:35:18.896Z - info: Running on ios test: 96. test calculateSeqPointKeyId

2016-03-16T05:35:19.412Z - info: Running on ios test: 97. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-16T05:35:20.623Z - info: Running on ios test: 98. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-16T05:35:21.151Z - info: Running on ios test: 99. messages with invalid location or USN should be ignored

2016-03-16T05:35:21.511Z - info: Running on ios test: 100. verify that Thali-specific messages are filtered correctly

2016-03-16T05:35:22.479Z - info: Running on ios test: 101. #startListeningForAdvertisements should fail if start not called

2016-03-16T05:35:25.663Z - info: Running on ios test: 102. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-16T05:35:26.390Z - info: Running on ios test: 103. #start should fail if called twice in a row

2016-03-16T05:35:26.866Z - info: Running on ios test: 104. should not be started after stop is called

2016-03-16T05:35:29.117Z - info: Running on ios test: 105. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-16T05:35:30.633Z - info: Running on ios test: 106. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-16T05:35:30.965Z - info: Running on ios test: 107. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-16T05:35:31.792Z - info: Running on ios test: 108. #stop can be called multiple times in a row

2016-03-16T05:35:32.362Z - info: Running on ios test: 109. #startListeningForAdvertisements can be called multiple times in a row

2016-03-16T05:35:33.423Z - info: Running on ios test: 110. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-16T05:35:34.415Z - info: Running on ios test: 111. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-16T05:35:34.986Z - info: Running on ios test: 112. functions are run from a queue in the right order

2016-03-16T05:35:35.284Z - info: Running on ios test: 113. #ThaliPeerPoolDefault - single action

2016-03-16T05:35:35.505Z - info: Running on ios test: 114. #ThaliPeerPoolDefault - multiple actions

2016-03-16T05:35:35.937Z - info: Test run on ios complete

2016-03-16T05:35:35.940Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-16T05:35:35.942Z - info: PLATFORM: ios

2016-03-16T05:35:35.943Z - info: RESULT: FAIL

2016-03-16T05:35:35.944Z - info: 114 of 114 tests completed

2016-03-16T05:35:35.945Z - info: 113/114 passed (1 failures)

2016-03-16T05:35:35.946Z - info: --- Test Details ---



2016-03-16T05:35:35.947Z - info: 1. calling createNativeListener directly rejects - pass

2016-03-16T05:35:35.949Z - info: 2. emits incomingConnectionState - pass

2016-03-16T05:35:35.950Z - info: 3. emits routerPortConnectionFailed - pass

2016-03-16T05:35:35.951Z - info: 4. native server connections all up - pass

2016-03-16T05:35:35.952Z - info: 5. native server - closing incoming stream cleans outgoing socket - pass

2016-03-16T05:35:35.952Z - info: 6. native server - closing incoming connection cleans outgoing socket - pass

2016-03-16T05:35:35.953Z - info: 7. native server - closing outgoing socket cleans associated mux stream - pass
2016-03-16T05:35:35.954Z - info: 8. native server - closing the whole server cleans everything up - pass
2016-03-16T05:35:35.955Z - info: 9. native server - we can get a ton of connections and data through and still clean up the server completely - pass
2016-03-16T05:35:35.956Z - info: 10. native server - simulate mux failure, make sure everything is cleaned up - pass
2016-03-16T05:35:35.956Z - info: 11. native server - timing out the incoming connection cleans everything up - pass
2016-03-16T05:35:35.957Z - info: 12. closeAll can close even when connections open - pass
2016-03-16T05:35:35.958Z - info: 13. closeAll with promise - pass
2016-03-16T05:35:35.959Z - info: 14. multiplex can send data - pass
2016-03-16T05:35:35.959Z - info: 15. enqueue and run in order - pass
2016-03-16T05:35:35.960Z - info: 16. enqueueAtTop and run backwards - pass
2016-03-16T05:35:35.960Z - info: 17. mix enqueue and enqueueAtTop - pass
2016-03-16T05:35:35.961Z - info: 18. queues handled independently - pass
2016-03-16T05:35:35.961Z - info: 19. basic - pass
2016-03-16T05:35:35.962Z - info: 20. another - pass
2016-03-16T05:35:35.962Z - info: 21. #startListeningForAdvertisements should fail if start not called - pass
2016-03-16T05:35:35.963Z - info: 22. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-16T05:35:35.964Z - info: 23. should be able to call #stopListeningForAdvertisements many times - pass
2016-03-16T05:35:35.964Z - info: 24. should be able to call #startListeningForAdvertisements many times - pass
2016-03-16T05:35:35.965Z - info: 25. should be able to call #startUpdateAdvertisingAndListening many times - pass
2016-03-16T05:35:35.966Z - info: 26. should be able to call #stopAdvertisingAndListening many times - pass
2016-03-16T05:35:35.966Z - info: 27. #start should fail if called twice in a row - pass
2016-03-16T05:35:35.967Z - info: 28. does not emit duplicate discoveryAdvertisingStateUpdate - pass

2016-03-16T05:35:35.968Z - info: 29. does not send duplicate availability changes - pass
2016-03-16T05:35:35.968Z - info: 30. can get the network status - pass
2016-03-16T05:35:35.969Z - info: 31. wifi peer is marked unavailable if announcements stop - pass

2016-03-16T05:35:35.970Z - info: 32. Can call start/stopListeningForAdvertisements - pass

2016-03-16T05:35:35.971Z - info: 33. Calling startListeningForAdvertisements twice is NOT an error - pass

2016-03-16T05:35:35.972Z - info: 34. Can call start/stopUpdateAdvertisingAndListening - pass

2016-03-16T05:35:35.973Z - info: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error - pass
2016-03-16T05:35:35.974Z - info: 36. peerAvailabilityChange is called - pass
2016-03-16T05:35:35.974Z - info: 37. Can connect to a remote peer - fail
2016-03-16T05:35:35.975Z - info: 38. Can shift large amounts of data - pass
2016-03-16T05:35:35.976Z - info: 39. can get the network status before starting - pass
2016-03-16T05:35:35.976Z - info: 40. #generatePreambleAndBeacons bad args - pass
2016-03-16T05:35:35.977Z - info: 41. #generatePreambleAndBeacons empty keys to notify - pass
2016-03-16T05:35:35.978Z - info: 42. #generatePreambleAndBeacons multiple keys to notify - pass

2016-03-16T05:35:35.978Z - info: 43. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass
2016-03-16T05:35:35.979Z - info: 44. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass

2016-03-16T05:35:35.980Z - info: 45. #parseBeacons expiration out of range lower - pass

2016-03-16T05:35:35.981Z - info: 46. #parseBeacons expiration out of range lower - pass

2016-03-16T05:35:35.982Z - info: 47. #parseBeacons no beacons returns null - pass
2016-03-16T05:35:35.983Z - info: 48. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass

2016-03-16T05:35:35.984Z - info: 49. #parseBeacons addressBookCallback fails decrypt - pass

2016-03-16T05:35:35.985Z - info: 50. #parseBeacons addressBookCallback returns no matches - pass

2016-03-16T05:35:35.986Z - info: 51. #parseBeacons addressBookCallback returns spurious match - pass

2016-03-16T05:35:35.987Z - info: 52. #parseBeacons addressBookCallback returns public key - pass

2016-03-16T05:35:35.988Z - info: 53. #parseBeacons with beacons both for and not for the user - pass
2016-03-16T05:35:35.989Z - info: 54. Start and stop ThaliNotificationServer - pass
2016-03-16T05:35:35.989Z - info: 55. Pass an empty array to ThaliNotificationServer.start - pass

2016-03-16T05:35:35.990Z - info: 56. Pass a string to ThaliNotificationServer.start - pass

2016-03-16T05:35:35.991Z - info: 57. Pass an empty parameter to ThaliNotificationServer.start - pass

2016-03-16T05:35:35.992Z - info: 58. Make an HTTP request to /NotificationBeacons - pass

2016-03-16T05:35:35.993Z - info: 59. Make an HTTP request to /NotificationBeacons (no keys) - pass
2016-03-16T05:35:35.994Z - info: 60. Make an HTTP request to /NotificationBeacons before calling start - pass

2016-03-16T05:35:35.995Z - info: 61. #testThaliPeerAction - test getters - pass

2016-03-16T05:35:35.996Z - info: 62. #testThaliPeerAction - start and kill - pass

2016-03-16T05:35:35.997Z - info: 63. #testThaliPeerAction - double start - pass

2016-03-16T05:35:35.997Z - info: 64. #testThaliPeerAction - start after kill - pass

2016-03-16T05:35:35.999Z - info: 65. #testThaliPeerAction - make sure ids are unique - pass
2016-03-16T05:35:35.999Z - info: 66. Test PeerConnectionInformation basics - pass

2016-03-16T05:35:36.000Z - info: 67. Test PeerDictionary basic functionality - pass

2016-03-16T05:35:36.001Z - info: 68. Test PeerDictionary with multiple entries. - pass

2016-03-16T05:35:36.002Z - info: 69. RESOLVED entries are removed before WAITING state entry. - pass

2016-03-16T05:35:36.003Z - info: 70. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass

2016-03-16T05:35:36.004Z - info: 71. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass

2016-03-16T05:35:36.005Z - info: 72. #ThaliPeerPoolInterface - bad enqueues - pass

2016-03-16T05:35:36.006Z - info: 73. #ThaliPeerPoolInterface - do not allow same object type - pass

2016-03-16T05:35:36.007Z - info: 74. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass
2016-03-16T05:35:36.008Z - info: 75. compareBufferArrays - pass

2016-03-16T05:35:36.009Z - info: 76. Call start twice and get error - pass

2016-03-16T05:35:36.010Z - info: 77. Start and make sure it runs - pass

2016-03-16T05:35:36.011Z - info: 78. Make sure getTimeWhenRun is right after start - pass

2016-03-16T05:35:36.011Z - info: 79. Make sure getTimeWhenRun is -1 after function is called - pass

2016-03-16T05:35:36.012Z - info: 80. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass

2016-03-16T05:35:36.013Z - info: 81. Test TransientState - pass

2016-03-16T05:35:36.014Z - info: 82. No peers and empty database - pass

2016-03-16T05:35:36.016Z - info: 83. One peer and empty DB - pass

2016-03-16T05:35:36.016Z - info: 84. One peer with _Local set behind current seq - pass

2016-03-16T05:35:36.017Z - info: 85. One peer with _Local set equal to current seq - pass

2016-03-16T05:35:36.018Z - info: 86. One peer with _Local set ahead of current seq (and no this should not happen) - pass

2016-03-16T05:35:36.020Z - info: 87. Three peers, one not in DB, one behind and one ahead - pass

2016-03-16T05:35:36.021Z - info: 88. More than maximum peers, make sure we only send maximum allowed - pass

2016-03-16T05:35:36.021Z - info: 89. two peers with empty DB, update the doc - pass

2016-03-16T05:35:36.022Z - info: 90. add doc and make sure tokens refresh when they expire - pass

2016-03-16T05:35:36.023Z - info: 91. start and stop and start and stop - pass

2016-03-16T05:35:36.024Z - info: 92. two identical starts in a row - pass
2016-03-16T05:35:36.025Z - info: 93. two different starts in a row - pass

2016-03-16T05:35:36.026Z - info: 94. two stops and a start and two stops - pass

2016-03-16T05:35:36.027Z - info: 95. we properly enqueue requests so no then needed - pass

2016-03-16T05:35:36.028Z - info: 96. test calculateSeqPointKeyId - pass

2016-03-16T05:35:36.029Z - info: 97. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass

2016-03-16T05:35:36.030Z - info: 98. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-03-16T05:35:36.031Z - info: 99. messages with invalid location or USN should be ignored - pass

2016-03-16T05:35:36.032Z - info: 100. verify that Thali-specific messages are filtered correctly - pass

2016-03-16T05:35:36.033Z - info: 101. #startListeningForAdvertisements should fail if start not called - pass

2016-03-16T05:35:36.034Z - info: 102. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-16T05:35:36.034Z - info: 103. #start should fail if called twice in a row - pass

2016-03-16T05:35:36.035Z - info: 104. should not be started after stop is called - pass

2016-03-16T05:35:36.036Z - info: 105. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass
2016-03-16T05:35:36.037Z - info: 106. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass
2016-03-16T05:35:36.038Z - info: 107. #startUpdateAdvertisingAndListening should start hosting given router object - pass
2016-03-16T05:35:36.039Z - info: 108. #stop can be called multiple times in a row - pass

2016-03-16T05:35:36.040Z - info: 109. #startListeningForAdvertisements can be called multiple times in a row - pass
2016-03-16T05:35:36.041Z - info: 110. #stopListeningForAdvertisements can be called multiple times in a row - pass

2016-03-16T05:35:36.042Z - info: 111. #stopAdvertisingAndListening can be called multiple times in a row - pass

2016-03-16T05:35:36.043Z - info: 112. functions are run from a queue in the right order - pass

2016-03-16T05:35:36.044Z - info: 113. #ThaliPeerPoolDefault - single action - pass

2016-03-16T05:35:36.044Z - info: 114. #ThaliPeerPoolDefault - multiple actions - pass

2016-03-16T05:35:36.045Z - info: 

-== END ==-

2016-03-16T05:35:39.015Z - debug: Socket disconnected: transport close 2 (Apple-IpadAir2-1)

2016-03-16T05:35:39.913Z - debug: Socket disconnected: transport close 3 (Apple-Iphone5-1)

2016-03-16T05:52:12.257Z - debug: Socket disconnected: transport close 0 (LGE-LG-H815)


 
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
STOP log received from  f56ad48d Test has  FAILED
Device test finished on f56ad48d 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/63012666c2ddc84_Merge_back_timeout_reverse_connections_tobybrad/thali01_samsung-SM-A500FU.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/63012666c2ddc84_Merge_back_timeout_reverse_connections_tobybrad/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
STOP log received from  ZX1C223JKW Test has  FAILED
Device test finished on ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/63012666c2ddc84_Merge_back_timeout_reverse_connections_tobybrad/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:0 
child process exited with code 0 on device LGH8153b36be34 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/63012666c2ddc84_Merge_back_timeout_reverse_connections_tobybrad/thali05_LGE-LG-H815.md)

####Node name: thali06
Console output:
```
STOP log received from  7970f88c Test has  FAILED
STOP log received from  FA55PYS00566 Test has  FAILED
Device test finished on 7970f88c 
Device test finished on FA55PYS00566 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/63012666c2ddc84_Merge_back_timeout_reverse_connections_tobybrad/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/63012666c2ddc84_Merge_back_timeout_reverse_connections_tobybrad/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:0 
child process exited with code 0 on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/63012666c2ddc84_Merge_back_timeout_reverse_connections_tobybrad/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:0 
child process exited with code 0 on device 4325e43f 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/63012666c2ddc84_Merge_back_timeout_reverse_connections_tobybrad/thali08_samsung-SM-A300FU.md)




###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/63012666c2ddc84_Merge_back_timeout_reverse_connections_tobybrad/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/63012666c2ddc84_Merge_back_timeout_reverse_connections_tobybrad/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/63012666c2ddc84_Merge_back_timeout_reverse_connections_tobybrad/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/63012666c2ddc84_Merge_back_timeout_reverse_connections_tobybrad/iOS_Iphone5s-1.md)



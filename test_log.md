#### Test 62509094c147163 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":8}}
2016-03-16T07:37:16.043Z - info: listening on *:3000

2016-03-16T07:37:17.382Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:0

2016-03-16T07:37:17.449Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:2

2016-03-16T07:37:17.451Z - info: Required number of ios devices presented (2)

2016-03-16T07:37:17.455Z - info: Starting unit test run for platform: ios

2016-03-16T07:37:17.495Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:1

2016-03-16T07:37:17.497Z - info: Discarding surplus device: Apple-Iphone6-1

2016-03-16T07:37:18.004Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-16T07:37:18.159Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:3

2016-03-16T07:37:18.160Z - info: Discarding surplus device: Apple-IpadAir2-1

2016-03-16T07:37:18.492Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-16T07:37:18.992Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-16T07:37:19.528Z - info: Running on ios test: 4. native server connections all up

2016-03-16T07:37:20.169Z - debug: Socket disconnected: transport close 1 (Apple-Iphone6-1)

2016-03-16T07:37:20.222Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-16T07:37:20.692Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:4

2016-03-16T07:37:20.840Z - debug: Socket disconnected: transport close 3 (Apple-IpadAir2-1)

2016-03-16T07:37:20.854Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-16T07:37:21.303Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-16T07:37:21.343Z - debug: Device presented: samsung-SM-A300FU (android) unittest socket:5

2016-03-16T07:37:21.344Z - info: Required number of android devices presented (2)

2016-03-16T07:37:21.346Z - info: Starting unit test run for platform: android

2016-03-16T07:37:21.792Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-16T07:37:22.086Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-16T07:37:22.447Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-16T07:37:22.844Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-16T07:37:23.395Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-16T07:37:23.532Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-16T07:37:23.890Z - info: Running on android test: 4. native server connections all up

2016-03-16T07:37:24.559Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-16T07:37:25.166Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-16T07:37:25.807Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-16T07:37:25.970Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-16T07:37:26.540Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-16T07:37:26.821Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-16T07:37:27.098Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-16T07:37:27.430Z - info: Running on ios test: 13. closeAll with promise

2016-03-16T07:37:27.963Z - info: Running on ios test: 14. multiplex can send data

2016-03-16T07:37:28.293Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-16T07:37:28.477Z - info: Running on ios test: 15. enqueue and run in order

2016-03-16T07:37:28.837Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-16T07:37:29.171Z - info: Running on ios test: 16. enqueueAtTop and run backwards

2016-03-16T07:37:29.296Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-16T07:37:29.662Z - info: Running on ios test: 17. mix enqueue and enqueueAtTop

2016-03-16T07:37:29.804Z - info: Running on android test: 13. closeAll with promise

2016-03-16T07:37:30.218Z - info: Running on android test: 14. multiplex can send data

2016-03-16T07:37:30.266Z - info: Running on ios test: 18. queues handled independently

2016-03-16T07:37:30.745Z - info: Running on android test: 15. enqueue and run in order

2016-03-16T07:37:30.906Z - info: Running on ios test: 19. basic

2016-03-16T07:37:31.522Z - info: Running on ios test: 20. another

2016-03-16T07:37:31.784Z - info: Running on android test: 16. enqueueAtTop and run backwards

2016-03-16T07:37:32.003Z - info: Running on ios test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-16T07:37:32.553Z - info: Running on android test: 17. mix enqueue and enqueueAtTop

2016-03-16T07:37:32.640Z - info: Running on ios test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-16T07:37:33.111Z - info: Running on ios test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-16T07:37:33.169Z - info: Running on android test: 18. queues handled independently

2016-03-16T07:37:33.747Z - info: Running on ios test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-16T07:37:34.034Z - info: Running on android test: 19. basic

2016-03-16T07:37:34.253Z - info: Running on ios test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-16T07:37:34.640Z - info: Running on android test: 20. another

2016-03-16T07:37:35.108Z - info: Running on ios test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-16T07:37:35.291Z - info: Running on android test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-16T07:37:35.706Z - info: Running on ios test: 27. #start should fail if called twice in a row

2016-03-16T07:37:35.841Z - info: Running on android test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-16T07:37:36.195Z - info: Running on ios test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-16T07:37:36.311Z - info: Running on android test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-16T07:37:36.712Z - info: Running on ios test: 29. does not send duplicate availability changes

2016-03-16T07:37:36.809Z - info: Running on android test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-16T07:37:37.329Z - info: Running on ios test: 30. can get the network status

2016-03-16T07:37:37.355Z - info: Running on android test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-16T07:37:37.836Z - info: Running on ios test: 31. wifi peer is marked unavailable if announcements stop

2016-03-16T07:37:37.944Z - info: Running on android test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-16T07:37:38.466Z - info: Running on android test: 27. #start should fail if called twice in a row

2016-03-16T07:37:38.976Z - info: Running on android test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-16T07:37:40.161Z - info: Running on ios test: 32. Can call start/stopListeningForAdvertisements

2016-03-16T07:37:40.320Z - info: Running on android test: 29. does not send duplicate availability changes

2016-03-16T07:37:40.757Z - info: Running on android test: 30. can get the network status

2016-03-16T07:37:41.322Z - info: Running on ios test: 33. Calling startListeningForAdvertisements twice is NOT an error

2016-03-16T07:37:41.508Z - info: Running on android test: 31. wifi peer is marked unavailable if announcements stop

2016-03-16T07:37:42.607Z - info: Running on ios test: 34. Can call start/stopUpdateAdvertisingAndListening

2016-03-16T07:37:43.120Z - info: Running on android test: 32. Can call start/stopListeningForAdvertisements

2016-03-16T07:37:43.399Z - info: Running on ios test: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-16T07:37:44.019Z - info: Running on android test: 33. Calling startListeningForAdvertisements twice is NOT an error

2016-03-16T07:37:44.168Z - info: Running on ios test: 36. peerAvailabilityChange is called

2016-03-16T07:37:45.033Z - info: Running on android test: 34. Can call start/stopUpdateAdvertisingAndListening

2016-03-16T07:37:45.862Z - info: Running on android test: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-16T07:37:47.225Z - info: Running on android test: 36. peerAvailabilityChange is called

2016-03-16T07:37:48.055Z - info: Running on ios test: 37. Can connect to a remote peer

2016-03-16T07:37:48.971Z - info: Running on android test: 37. Can connect to a remote peer

2016-03-16T07:38:07.596Z - info: Running on android test: 38. Can shift large amounts of data

2016-03-16T07:38:18.174Z - info: Running on android test: 39. can get the network status before starting

2016-03-16T07:38:18.455Z - info: Running on android test: 40. #generatePreambleAndBeacons bad args

2016-03-16T07:38:18.923Z - info: Running on android test: 41. #generatePreambleAndBeacons empty keys to notify

2016-03-16T07:38:19.379Z - info: Running on android test: 42. #generatePreambleAndBeacons multiple keys to notify

2016-03-16T07:38:20.063Z - info: Running on android test: 43. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-16T07:38:20.577Z - info: Running on android test: 44. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-16T07:38:21.188Z - info: Running on android test: 45. #parseBeacons expiration out of range lower

2016-03-16T07:38:21.806Z - info: Running on android test: 46. #parseBeacons expiration out of range lower

2016-03-16T07:38:22.440Z - info: Running on android test: 47. #parseBeacons no beacons returns null

2016-03-16T07:38:23.264Z - info: Running on android test: 48. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-16T07:38:23.667Z - info: Running on android test: 49. #parseBeacons addressBookCallback fails decrypt

2016-03-16T07:38:24.179Z - info: Running on android test: 50. #parseBeacons addressBookCallback returns no matches

2016-03-16T07:38:25.061Z - info: Running on android test: 51. #parseBeacons addressBookCallback returns spurious match

2016-03-16T07:38:25.670Z - info: Running on android test: 52. #parseBeacons addressBookCallback returns public key

2016-03-16T07:38:26.304Z - info: Running on android test: 53. #parseBeacons with beacons both for and not for the user

2016-03-16T07:38:26.761Z - info: Running on android test: 54. Start and stop ThaliNotificationServer

2016-03-16T07:38:27.306Z - info: Running on android test: 55. Pass an empty array to ThaliNotificationServer.start

2016-03-16T07:38:28.146Z - info: Running on android test: 56. Pass a string to ThaliNotificationServer.start

2016-03-16T07:38:28.691Z - info: Running on android test: 57. Pass an empty parameter to ThaliNotificationServer.start

2016-03-16T07:38:29.100Z - info: Running on android test: 58. Make an HTTP request to /NotificationBeacons

2016-03-16T07:38:29.720Z - info: Running on android test: 59. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-16T07:38:30.548Z - info: Running on android test: 60. Make an HTTP request to /NotificationBeacons before calling start

2016-03-16T07:38:31.101Z - info: Running on android test: 61. #testThaliPeerAction - test getters

2016-03-16T07:38:31.609Z - info: Running on android test: 62. #testThaliPeerAction - start and kill

2016-03-16T07:38:32.061Z - info: Running on android test: 63. #testThaliPeerAction - double start

2016-03-16T07:38:32.532Z - info: Running on android test: 64. #testThaliPeerAction - start after kill

2016-03-16T07:38:32.916Z - info: Running on android test: 65. #testThaliPeerAction - make sure ids are unique

2016-03-16T07:38:33.294Z - info: Running on android test: 66. Test PeerConnectionInformation basics

2016-03-16T07:38:34.160Z - info: Running on android test: 67. Test PeerDictionary basic functionality

2016-03-16T07:38:35.093Z - info: Running on android test: 68. Test PeerDictionary with multiple entries.

2016-03-16T07:38:38.725Z - info: Running on android test: 69. RESOLVED entries are removed before WAITING state entry.

2016-03-16T07:38:40.815Z - info: Running on android test: 70. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-16T07:38:42.737Z - info: Running on android test: 71. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-16T07:38:44.838Z - info: Running on android test: 72. #ThaliPeerPoolInterface - bad enqueues

2016-03-16T07:38:45.444Z - info: Running on android test: 73. #ThaliPeerPoolInterface - do not allow same object type

2016-03-16T07:38:46.047Z - info: Running on android test: 74. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-16T07:38:46.444Z - info: Running on android test: 75. compareBufferArrays

2016-03-16T07:38:46.907Z - info: Running on android test: 76. Call start twice and get error

2016-03-16T07:38:47.355Z - info: Running on android test: 77. Start and make sure it runs

2016-03-16T07:38:48.363Z - info: Running on android test: 78. Make sure getTimeWhenRun is right after start

2016-03-16T07:38:49.082Z - info: Running on android test: 79. Make sure getTimeWhenRun is -1 after function is called

2016-03-16T07:38:50.726Z - info: Running on android test: 80. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-16T07:38:52.056Z - info: Running on android test: 81. Test TransientState

2016-03-16T07:38:53.146Z - info: Running on android test: 82. No peers and empty database

2016-03-16T07:38:54.286Z - info: Running on android test: 83. One peer and empty DB

2016-03-16T07:38:55.261Z - info: Running on android test: 84. One peer with _Local set behind current seq

2016-03-16T07:38:55.830Z - info: Running on android test: 85. One peer with _Local set equal to current seq

2016-03-16T07:38:56.856Z - info: Running on android test: 86. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-16T07:38:58.773Z - info: Running on android test: 87. Three peers, one not in DB, one behind and one ahead

2016-03-16T07:38:59.565Z - info: Running on android test: 88. More than maximum peers, make sure we only send maximum allowed

2016-03-16T07:39:01.150Z - info: Running on android test: 89. two peers with empty DB, update the doc

2016-03-16T07:39:01.834Z - info: Running on android test: 90. add doc and make sure tokens refresh when they expire

2016-03-16T07:39:02.738Z - info: Running on android test: 91. start and stop and start and stop

2016-03-16T07:39:03.582Z - info: Running on android test: 92. two identical starts in a row

2016-03-16T07:39:04.556Z - info: Running on android test: 93. two different starts in a row

2016-03-16T07:39:05.542Z - info: Running on android test: 94. two stops and a start and two stops

2016-03-16T07:39:05.981Z - info: Running on android test: 95. we properly enqueue requests so no then needed

2016-03-16T07:39:06.467Z - info: Running on android test: 96. test calculateSeqPointKeyId

2016-03-16T07:39:06.964Z - info: Running on android test: 97. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-16T07:39:07.264Z - info: Running on android test: 98. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-16T07:39:07.897Z - info: Running on android test: 99. messages with invalid location or USN should be ignored

2016-03-16T07:39:08.251Z - info: Running on android test: 100. verify that Thali-specific messages are filtered correctly

2016-03-16T07:39:08.658Z - info: Running on android test: 101. #startListeningForAdvertisements should fail if start not called

2016-03-16T07:39:09.188Z - info: Running on android test: 102. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-16T07:39:09.688Z - info: Running on android test: 103. #start should fail if called twice in a row

2016-03-16T07:39:10.214Z - info: Running on android test: 104. should not be started after stop is called

2016-03-16T07:39:10.571Z - info: Running on android test: 105. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-16T07:39:11.029Z - info: Running on android test: 106. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-16T07:39:11.574Z - info: Running on android test: 107. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-16T07:39:12.342Z - info: Running on android test: 108. #stop can be called multiple times in a row

2016-03-16T07:39:12.658Z - info: Running on android test: 109. #startListeningForAdvertisements can be called multiple times in a row

2016-03-16T07:39:13.198Z - info: Running on android test: 110. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-16T07:39:13.782Z - info: Running on android test: 111. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-16T07:39:14.229Z - info: Running on android test: 112. functions are run from a queue in the right order

2016-03-16T07:39:14.605Z - info: Running on android test: 113. #ThaliPeerPoolDefault - single action

2016-03-16T07:39:14.898Z - info: Running on android test: 114. #ThaliPeerPoolDefault - multiple actions

2016-03-16T07:39:15.211Z - info: Test run on android complete

2016-03-16T07:39:15.215Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-16T07:39:15.219Z - info: PLATFORM: android

2016-03-16T07:39:15.221Z - info: RESULT: FAIL

2016-03-16T07:39:15.223Z - info: 114 of 114 tests completed

2016-03-16T07:39:15.226Z - info: 112/114 passed (2 failures)

2016-03-16T07:39:15.227Z - info: --- Test Details ---



2016-03-16T07:39:15.228Z - info: 1. calling createNativeListener directly rejects - pass

2016-03-16T07:39:15.229Z - info: 2. emits incomingConnectionState - pass
2016-03-16T07:39:15.230Z - info: 3. emits routerPortConnectionFailed - pass

2016-03-16T07:39:15.231Z - info: 4. native server connections all up - pass
2016-03-16T07:39:15.232Z - info: 5. native server - closing incoming stream cleans outgoing socket - pass

2016-03-16T07:39:15.232Z - info: 6. native server - closing incoming connection cleans outgoing socket - pass

2016-03-16T07:39:15.233Z - info: 7. native server - closing outgoing socket cleans associated mux stream - pass
2016-03-16T07:39:15.234Z - info: 8. native server - closing the whole server cleans everything up - pass

2016-03-16T07:39:15.234Z - info: 9. native server - we can get a ton of connections and data through and still clean up the server completely - pass
2016-03-16T07:39:15.235Z - info: 10. native server - simulate mux failure, make sure everything is cleaned up - pass

2016-03-16T07:39:15.236Z - info: 11. native server - timing out the incoming connection cleans everything up - pass
2016-03-16T07:39:15.237Z - info: 12. closeAll can close even when connections open - pass

2016-03-16T07:39:15.237Z - info: 13. closeAll with promise - pass
2016-03-16T07:39:15.238Z - info: 14. multiplex can send data - pass

2016-03-16T07:39:15.239Z - info: 15. enqueue and run in order - pass
2016-03-16T07:39:15.240Z - info: 16. enqueueAtTop and run backwards - pass
2016-03-16T07:39:15.240Z - info: 17. mix enqueue and enqueueAtTop - pass
2016-03-16T07:39:15.241Z - info: 18. queues handled independently - pass
2016-03-16T07:39:15.242Z - info: 19. basic - pass
2016-03-16T07:39:15.243Z - info: 20. another - pass
2016-03-16T07:39:15.244Z - info: 21. #startListeningForAdvertisements should fail if start not called - pass
2016-03-16T07:39:15.244Z - info: 22. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-16T07:39:15.245Z - info: 23. should be able to call #stopListeningForAdvertisements many times - pass
2016-03-16T07:39:15.246Z - info: 24. should be able to call #startListeningForAdvertisements many times - pass
2016-03-16T07:39:15.246Z - info: 25. should be able to call #startUpdateAdvertisingAndListening many times - pass
2016-03-16T07:39:15.247Z - info: 26. should be able to call #stopAdvertisingAndListening many times - pass
2016-03-16T07:39:15.247Z - info: 27. #start should fail if called twice in a row - pass
2016-03-16T07:39:15.248Z - info: 28. does not emit duplicate discoveryAdvertisingStateUpdate - pass
2016-03-16T07:39:15.248Z - info: 29. does not send duplicate availability changes - pass
2016-03-16T07:39:15.249Z - info: 30. can get the network status - pass
2016-03-16T07:39:15.250Z - info: 31. wifi peer is marked unavailable if announcements stop - pass
2016-03-16T07:39:15.251Z - info: 32. Can call start/stopListeningForAdvertisements - pass
2016-03-16T07:39:15.251Z - info: 33. Calling startListeningForAdvertisements twice is NOT an error - pass

2016-03-16T07:39:15.252Z - info: 34. Can call start/stopUpdateAdvertisingAndListening - pass

2016-03-16T07:39:15.263Z - info: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error - pass

2016-03-16T07:39:15.270Z - info: 36. peerAvailabilityChange is called - pass

2016-03-16T07:39:15.271Z - info: 37. Can connect to a remote peer - fail
2016-03-16T07:39:15.272Z - info: 38. Can shift large amounts of data - fail

2016-03-16T07:39:15.273Z - info: 39. can get the network status before starting - pass
2016-03-16T07:39:15.274Z - info: 40. #generatePreambleAndBeacons bad args - pass
2016-03-16T07:39:15.274Z - info: 41. #generatePreambleAndBeacons empty keys to notify - pass
2016-03-16T07:39:15.275Z - info: 42. #generatePreambleAndBeacons multiple keys to notify - pass
2016-03-16T07:39:15.276Z - info: 43. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass
2016-03-16T07:39:15.276Z - info: 44. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass
2016-03-16T07:39:15.277Z - info: 45. #parseBeacons expiration out of range lower - pass
2016-03-16T07:39:15.278Z - info: 46. #parseBeacons expiration out of range lower - pass

2016-03-16T07:39:15.279Z - info: 47. #parseBeacons no beacons returns null - pass
2016-03-16T07:39:15.279Z - info: 48. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass

2016-03-16T07:39:15.280Z - info: 49. #parseBeacons addressBookCallback fails decrypt - pass
2016-03-16T07:39:15.281Z - info: 50. #parseBeacons addressBookCallback returns no matches - pass

2016-03-16T07:39:15.282Z - info: 51. #parseBeacons addressBookCallback returns spurious match - pass

2016-03-16T07:39:15.282Z - info: 52. #parseBeacons addressBookCallback returns public key - pass
2016-03-16T07:39:15.283Z - info: 53. #parseBeacons with beacons both for and not for the user - pass

2016-03-16T07:39:15.284Z - info: 54. Start and stop ThaliNotificationServer - pass
2016-03-16T07:39:15.284Z - info: 55. Pass an empty array to ThaliNotificationServer.start - pass

2016-03-16T07:39:15.285Z - info: 56. Pass a string to ThaliNotificationServer.start - pass
2016-03-16T07:39:15.286Z - info: 57. Pass an empty parameter to ThaliNotificationServer.start - pass

2016-03-16T07:39:15.287Z - info: 58. Make an HTTP request to /NotificationBeacons - pass

2016-03-16T07:39:15.287Z - info: 59. Make an HTTP request to /NotificationBeacons (no keys) - pass
2016-03-16T07:39:15.288Z - info: 60. Make an HTTP request to /NotificationBeacons before calling start - pass

2016-03-16T07:39:15.289Z - info: 61. #testThaliPeerAction - test getters - pass
2016-03-16T07:39:15.290Z - info: 62. #testThaliPeerAction - start and kill - pass
2016-03-16T07:39:15.290Z - info: 63. #testThaliPeerAction - double start - pass

2016-03-16T07:39:15.291Z - info: 64. #testThaliPeerAction - start after kill - pass
2016-03-16T07:39:15.292Z - info: 65. #testThaliPeerAction - make sure ids are unique - pass

2016-03-16T07:39:15.293Z - info: 66. Test PeerConnectionInformation basics - pass
2016-03-16T07:39:15.293Z - info: 67. Test PeerDictionary basic functionality - pass

2016-03-16T07:39:15.294Z - info: 68. Test PeerDictionary with multiple entries. - pass
2016-03-16T07:39:15.295Z - info: 69. RESOLVED entries are removed before WAITING state entry. - pass

2016-03-16T07:39:15.296Z - info: 70. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass
2016-03-16T07:39:15.296Z - info: 71. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass

2016-03-16T07:39:15.297Z - info: 72. #ThaliPeerPoolInterface - bad enqueues - pass

2016-03-16T07:39:15.298Z - info: 73. #ThaliPeerPoolInterface - do not allow same object type - pass
2016-03-16T07:39:15.298Z - info: 74. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass

2016-03-16T07:39:15.299Z - info: 75. compareBufferArrays - pass
2016-03-16T07:39:15.300Z - info: 76. Call start twice and get error - pass

2016-03-16T07:39:15.301Z - info: 77. Start and make sure it runs - pass
2016-03-16T07:39:15.301Z - info: 78. Make sure getTimeWhenRun is right after start - pass

2016-03-16T07:39:15.302Z - info: 79. Make sure getTimeWhenRun is -1 after function is called - pass

2016-03-16T07:39:15.303Z - info: 80. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass
2016-03-16T07:39:15.304Z - info: 81. Test TransientState - pass

2016-03-16T07:39:15.304Z - info: 82. No peers and empty database - pass
2016-03-16T07:39:15.305Z - info: 83. One peer and empty DB - pass

2016-03-16T07:39:15.306Z - info: 84. One peer with _Local set behind current seq - pass
2016-03-16T07:39:15.306Z - info: 85. One peer with _Local set equal to current seq - pass

2016-03-16T07:39:15.307Z - info: 86. One peer with _Local set ahead of current seq (and no this should not happen) - pass

2016-03-16T07:39:15.308Z - info: 87. Three peers, one not in DB, one behind and one ahead - pass
2016-03-16T07:39:15.309Z - info: 88. More than maximum peers, make sure we only send maximum allowed - pass

2016-03-16T07:39:15.310Z - info: 89. two peers with empty DB, update the doc - pass

2016-03-16T07:39:15.311Z - info: 90. add doc and make sure tokens refresh when they expire - pass
2016-03-16T07:39:15.311Z - info: 91. start and stop and start and stop - pass

2016-03-16T07:39:15.312Z - info: 92. two identical starts in a row - pass
2016-03-16T07:39:15.313Z - info: 93. two different starts in a row - pass

2016-03-16T07:39:15.314Z - info: 94. two stops and a start and two stops - pass
2016-03-16T07:39:15.314Z - info: 95. we properly enqueue requests so no then needed - pass

2016-03-16T07:39:15.315Z - info: 96. test calculateSeqPointKeyId - pass
2016-03-16T07:39:15.316Z - info: 97. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass

2016-03-16T07:39:15.316Z - info: 98. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-03-16T07:39:15.317Z - info: 99. messages with invalid location or USN should be ignored - pass
2016-03-16T07:39:15.318Z - info: 100. verify that Thali-specific messages are filtered correctly - pass

2016-03-16T07:39:15.319Z - info: 101. #startListeningForAdvertisements should fail if start not called - pass
2016-03-16T07:39:15.319Z - info: 102. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-16T07:39:15.320Z - info: 103. #start should fail if called twice in a row - pass

2016-03-16T07:39:15.321Z - info: 104. should not be started after stop is called - pass
2016-03-16T07:39:15.322Z - info: 105. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass

2016-03-16T07:39:15.322Z - info: 106. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass
2016-03-16T07:39:15.323Z - info: 107. #startUpdateAdvertisingAndListening should start hosting given router object - pass

2016-03-16T07:39:15.324Z - info: 108. #stop can be called multiple times in a row - pass
2016-03-16T07:39:15.324Z - info: 109. #startListeningForAdvertisements can be called multiple times in a row - pass

2016-03-16T07:39:15.325Z - info: 110. #stopListeningForAdvertisements can be called multiple times in a row - pass

2016-03-16T07:39:15.326Z - info: 111. #stopAdvertisingAndListening can be called multiple times in a row - pass
2016-03-16T07:39:15.327Z - info: 112. functions are run from a queue in the right order - pass

2016-03-16T07:39:15.327Z - info: 113. #ThaliPeerPoolDefault - single action - pass
2016-03-16T07:39:15.328Z - info: 114. #ThaliPeerPoolDefault - multiple actions - pass

2016-03-16T07:39:15.329Z - info: 

-== END ==-

2016-03-16T07:39:16.173Z - debug: Socket disconnected: transport close 4 (LGE-LG-H815)

2016-03-16T07:55:09.977Z - debug: Socket disconnected: transport close 0 (Apple-Iphone5-1)

2016-03-16T07:55:10.027Z - debug: Socket disconnected: transport close 2 (Apple-Iphone5s-1)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/62509094c147163_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/62509094c147163_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/62509094c147163_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/62509094c147163_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/62509094c147163_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  f56ad48d Test has  FAILED
Device test finished on f56ad48d 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62509094c147163_Make_CI_build_and_unit_tests_pass_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/62509094c147163_Make_CI_build_and_unit_tests_pass_vjrantal/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
STOP log received from  ZX1C223JKW Test has  FAILED
Device test finished on ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/62509094c147163_Make_CI_build_and_unit_tests_pass_vjrantal/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Android task is completed. [SUCCESS]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/62509094c147163_Make_CI_build_and_unit_tests_pass_vjrantal/thali05_LGE-LG-H815.md)

####Node name: thali06
Console output:
```
STOP log received from  7970f88c Test has  FAILED
Device test finished on 7970f88c 
STOP log received from  FA55PYS00566 Test has  FAILED
Device test finished on FA55PYS00566 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62509094c147163_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/62509094c147163_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
STOP log received from  4db5c8cc Test has  FAILED
Device test finished on 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62509094c147163_Make_CI_build_and_unit_tests_pass_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:0 
child process exited with code 0 on device 4325e43f 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62509094c147163_Make_CI_build_and_unit_tests_pass_vjrantal/thali08_samsung-SM-A300FU.md)





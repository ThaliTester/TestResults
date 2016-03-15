#### Test 62509094c453ee6 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":8}}
2016-03-15T10:02:01.781Z - info: listening on *:3000

2016-03-15T10:02:03.348Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:0

2016-03-15T10:02:04.897Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:1

2016-03-15T10:02:05.193Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:2

2016-03-15T10:02:05.197Z - info: Required number of android devices presented (2)

2016-03-15T10:02:05.202Z - info: Starting unit test run for platform: android

2016-03-15T10:02:05.570Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:3

2016-03-15T10:02:05.571Z - info: Required number of ios devices presented (2)

2016-03-15T10:02:05.573Z - info: Starting unit test run for platform: ios

2016-03-15T10:02:05.727Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-15T10:02:05.773Z - debug: Device presented: samsung-SM-A300FU (android) unittest socket:4

2016-03-15T10:02:05.774Z - info: Discarding surplus device: samsung-SM-A300FU

2016-03-15T10:02:06.020Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-15T10:02:06.187Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-15T10:02:06.388Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-15T10:02:06.397Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:5

2016-03-15T10:02:06.399Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-15T10:02:06.662Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-15T10:02:06.833Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-15T10:02:07.265Z - info: Running on android test: 4. native server connections all up

2016-03-15T10:02:07.292Z - info: Running on ios test: 4. native server connections all up

2016-03-15T10:02:07.392Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:6

2016-03-15T10:02:07.393Z - info: Discarding surplus device: Apple-Iphone5-1

2016-03-15T10:02:07.726Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-15T10:02:07.814Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-15T10:02:08.207Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-15T10:02:08.234Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-15T10:02:08.727Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-15T10:02:08.743Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-15T10:02:08.972Z - debug: Socket disconnected: transport close 5 (Apple-Iphone5s-1)

2016-03-15T10:02:09.255Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-15T10:02:09.258Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-15T10:02:10.090Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-15T10:02:10.219Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-15T10:02:10.609Z - debug: Socket disconnected: transport close 6 (Apple-Iphone5-1)

2016-03-15T10:02:11.005Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-15T10:02:11.243Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-15T10:02:11.746Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-15T10:02:12.254Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-15T10:02:12.529Z - info: Running on android test: 13. closeAll with promise

2016-03-15T10:02:12.580Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-15T10:02:12.804Z - info: Running on android test: 14. multiplex can send data

2016-03-15T10:02:12.913Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-15T10:02:13.255Z - info: Running on android test: 15. enqueue and run in order

2016-03-15T10:02:13.371Z - info: Running on ios test: 13. closeAll with promise

2016-03-15T10:02:13.709Z - info: Running on ios test: 14. multiplex can send data

2016-03-15T10:02:13.820Z - info: Running on android test: 16. enqueueAtTop and run backwards

2016-03-15T10:02:14.033Z - info: Running on ios test: 15. enqueue and run in order

2016-03-15T10:02:14.241Z - info: Running on android test: 17. mix enqueue and enqueueAtTop

2016-03-15T10:02:14.582Z - info: Running on ios test: 16. enqueueAtTop and run backwards

2016-03-15T10:02:14.893Z - info: Running on android test: 18. queues handled independently

2016-03-15T10:02:15.256Z - info: Running on ios test: 17. mix enqueue and enqueueAtTop

2016-03-15T10:02:15.476Z - info: Running on android test: 19. basic

2016-03-15T10:02:15.838Z - info: Running on ios test: 18. queues handled independently

2016-03-15T10:02:15.922Z - info: Running on android test: 20. another

2016-03-15T10:02:16.223Z - info: Running on ios test: 19. basic

2016-03-15T10:02:16.336Z - info: Running on android test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-15T10:02:16.596Z - info: Running on ios test: 20. another

2016-03-15T10:02:16.747Z - info: Running on android test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-15T10:02:17.169Z - info: Running on android test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-15T10:02:17.182Z - info: Running on ios test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-15T10:02:17.544Z - info: Running on ios test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-15T10:02:17.553Z - info: Running on android test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-15T10:02:17.894Z - info: Running on ios test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-15T10:02:17.942Z - info: Running on android test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-15T10:02:18.245Z - info: Running on ios test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-15T10:02:18.419Z - info: Running on android test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-15T10:02:18.636Z - info: Running on ios test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-15T10:02:18.816Z - info: Running on android test: 27. #start should fail if called twice in a row

2016-03-15T10:02:19.099Z - info: Running on ios test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-15T10:02:19.192Z - info: Running on android test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-15T10:02:19.460Z - info: Running on ios test: 27. #start should fail if called twice in a row

2016-03-15T10:02:19.659Z - info: Running on android test: 29. does not send duplicate availability changes

2016-03-15T10:02:19.770Z - info: Running on ios test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-15T10:02:19.984Z - info: Running on android test: 30. can get the network status

2016-03-15T10:02:20.170Z - info: Running on ios test: 29. does not send duplicate availability changes

2016-03-15T10:02:20.499Z - info: Running on android test: 31. wifi peer is marked unavailable if announcements stop

2016-03-15T10:02:20.608Z - info: Running on ios test: 30. can get the network status

2016-03-15T10:02:20.880Z - info: Running on ios test: 31. wifi peer is marked unavailable if announcements stop

2016-03-15T10:02:21.832Z - info: Running on android test: 32. can get the network status before starting

2016-03-15T10:02:22.187Z - info: Running on android test: 33. #generatePreambleAndBeacons bad args

2016-03-15T10:02:22.325Z - info: Running on ios test: 32. can get the network status before starting

2016-03-15T10:02:22.683Z - info: Running on ios test: 33. #generatePreambleAndBeacons bad args

2016-03-15T10:02:22.687Z - info: Running on android test: 34. #generatePreambleAndBeacons empty keys to notify

2016-03-15T10:02:23.118Z - info: Running on android test: 35. #generatePreambleAndBeacons multiple keys to notify

2016-03-15T10:02:23.156Z - info: Running on ios test: 34. #generatePreambleAndBeacons empty keys to notify

2016-03-15T10:02:23.522Z - info: Running on ios test: 35. #generatePreambleAndBeacons multiple keys to notify

2016-03-15T10:02:23.657Z - info: Running on android test: 36. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-15T10:02:23.974Z - info: Running on ios test: 36. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-15T10:02:24.022Z - info: Running on android test: 37. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-15T10:02:24.264Z - info: Running on ios test: 37. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-15T10:02:24.392Z - info: Running on android test: 38. #parseBeacons expiration out of range lower

2016-03-15T10:02:24.494Z - info: Running on ios test: 38. #parseBeacons expiration out of range lower

2016-03-15T10:02:24.681Z - info: Running on android test: 39. #parseBeacons expiration out of range lower

2016-03-15T10:02:24.808Z - info: Running on ios test: 39. #parseBeacons expiration out of range lower

2016-03-15T10:02:25.086Z - info: Running on android test: 40. #parseBeacons no beacons returns null

2016-03-15T10:02:25.145Z - info: Running on ios test: 40. #parseBeacons no beacons returns null

2016-03-15T10:02:25.465Z - info: Running on android test: 41. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-15T10:02:25.630Z - info: Running on ios test: 41. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-15T10:02:25.975Z - info: Running on android test: 42. #parseBeacons addressBookCallback fails decrypt

2016-03-15T10:02:26.025Z - info: Running on ios test: 42. #parseBeacons addressBookCallback fails decrypt

2016-03-15T10:02:26.488Z - info: Running on android test: 43. #parseBeacons addressBookCallback returns no matches

2016-03-15T10:02:26.506Z - info: Running on ios test: 43. #parseBeacons addressBookCallback returns no matches

2016-03-15T10:02:27.059Z - info: Running on android test: 44. #parseBeacons addressBookCallback returns spurious match

2016-03-15T10:02:27.720Z - info: Running on android test: 45. #parseBeacons addressBookCallback returns public key

2016-03-15T10:02:28.361Z - info: Running on android test: 46. #parseBeacons with beacons both for and not for the user

2016-03-15T10:02:28.879Z - info: Running on android test: 47. Start and stop ThaliNotificationServer

2016-03-15T10:02:29.631Z - info: Running on android test: 48. Pass an empty array to ThaliNotificationServer.start

2016-03-15T10:02:30.349Z - info: Running on android test: 49. Pass a string to ThaliNotificationServer.start

2016-03-15T10:02:30.464Z - info: Running on ios test: 44. #parseBeacons addressBookCallback returns spurious match

2016-03-15T10:02:30.993Z - info: Running on android test: 50. Pass an empty parameter to ThaliNotificationServer.start

2016-03-15T10:02:31.449Z - info: Running on android test: 51. Make an HTTP request to /NotificationBeacons

2016-03-15T10:02:32.083Z - info: Running on android test: 52. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-15T10:02:32.526Z - info: Running on android test: 53. Make an HTTP request to /NotificationBeacons before calling start

2016-03-15T10:02:33.000Z - info: Running on android test: 54. #testThaliPeerAction - test getters

2016-03-15T10:02:33.341Z - info: Running on android test: 55. #testThaliPeerAction - start and kill

2016-03-15T10:02:33.633Z - info: Running on android test: 56. #testThaliPeerAction - double start

2016-03-15T10:02:33.928Z - info: Running on android test: 57. #testThaliPeerAction - start after kill

2016-03-15T10:02:34.215Z - info: Running on android test: 58. #testThaliPeerAction - make sure ids are unique

2016-03-15T10:02:34.482Z - info: Running on android test: 59. Test PeerConnectionInformation basics

2016-03-15T10:02:34.864Z - info: Running on android test: 60. Test PeerDictionary basic functionality

2016-03-15T10:02:35.190Z - info: Running on ios test: 45. #parseBeacons addressBookCallback returns public key

2016-03-15T10:02:35.343Z - info: Running on android test: 61. Test PeerDictionary with multiple entries.

2016-03-15T10:02:35.589Z - info: Running on ios test: 46. #parseBeacons with beacons both for and not for the user

2016-03-15T10:02:36.065Z - info: Running on ios test: 47. Start and stop ThaliNotificationServer

2016-03-15T10:02:36.410Z - info: Running on ios test: 48. Pass an empty array to ThaliNotificationServer.start

2016-03-15T10:02:36.700Z - info: Running on ios test: 49. Pass a string to ThaliNotificationServer.start

2016-03-15T10:02:36.958Z - info: Running on android test: 62. RESOLVED entries are removed before WAITING state entry.

2016-03-15T10:02:37.059Z - info: Running on ios test: 50. Pass an empty parameter to ThaliNotificationServer.start

2016-03-15T10:02:37.471Z - info: Running on ios test: 51. Make an HTTP request to /NotificationBeacons

2016-03-15T10:02:37.984Z - info: Running on ios test: 52. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-15T10:02:37.992Z - info: Running on android test: 63. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-15T10:02:38.382Z - info: Running on ios test: 53. Make an HTTP request to /NotificationBeacons before calling start

2016-03-15T10:02:38.812Z - info: Running on ios test: 54. #testThaliPeerAction - test getters

2016-03-15T10:02:39.073Z - info: Running on android test: 64. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-15T10:02:39.094Z - info: Running on ios test: 55. #testThaliPeerAction - start and kill

2016-03-15T10:02:39.388Z - info: Running on ios test: 56. #testThaliPeerAction - double start

2016-03-15T10:02:39.687Z - info: Running on ios test: 57. #testThaliPeerAction - start after kill

2016-03-15T10:02:39.960Z - info: Running on ios test: 58. #testThaliPeerAction - make sure ids are unique

2016-03-15T10:02:40.029Z - info: Running on android test: 65. #ThaliPeerPoolInterface - bad enqueues

2016-03-15T10:02:40.234Z - info: Running on ios test: 59. Test PeerConnectionInformation basics

2016-03-15T10:02:40.401Z - info: Running on android test: 66. #ThaliPeerPoolInterface - do not allow same object type

2016-03-15T10:02:40.562Z - info: Running on ios test: 60. Test PeerDictionary basic functionality

2016-03-15T10:02:40.771Z - info: Running on android test: 67. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-15T10:02:40.892Z - info: Running on ios test: 61. Test PeerDictionary with multiple entries.

2016-03-15T10:02:41.204Z - info: Running on android test: 68. compareBufferArrays

2016-03-15T10:02:41.480Z - info: Running on android test: 69. Call start twice and get error

2016-03-15T10:02:41.854Z - info: Running on android test: 70. Start and make sure it runs

2016-03-15T10:02:42.251Z - info: Running on android test: 71. Make sure getTimeWhenRun is right after start

2016-03-15T10:02:42.483Z - info: Running on ios test: 62. RESOLVED entries are removed before WAITING state entry.

2016-03-15T10:02:42.558Z - info: Running on android test: 72. Make sure getTimeWhenRun is -1 after function is called

2016-03-15T10:02:42.944Z - info: Running on android test: 73. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-15T10:02:43.426Z - info: Running on android test: 74. Test TransientState

2016-03-15T10:02:43.702Z - info: Running on ios test: 63. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-15T10:02:44.019Z - info: Running on android test: 75. No peers and empty database

2016-03-15T10:02:44.797Z - info: Running on ios test: 64. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-15T10:02:44.987Z - info: Running on android test: 76. One peer and empty DB

2016-03-15T10:02:45.756Z - info: Running on ios test: 65. #ThaliPeerPoolInterface - bad enqueues

2016-03-15T10:02:46.108Z - info: Running on ios test: 66. #ThaliPeerPoolInterface - do not allow same object type

2016-03-15T10:02:46.117Z - info: Running on android test: 77. One peer with _Local set behind current seq

2016-03-15T10:02:46.410Z - info: Running on ios test: 67. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-15T10:02:46.876Z - info: Running on ios test: 68. compareBufferArrays

2016-03-15T10:02:46.892Z - info: Running on android test: 78. One peer with _Local set equal to current seq

2016-03-15T10:02:47.238Z - info: Running on ios test: 69. Call start twice and get error

2016-03-15T10:02:47.489Z - info: Running on android test: 79. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-15T10:02:47.716Z - info: Running on ios test: 70. Start and make sure it runs

2016-03-15T10:02:47.963Z - info: Running on ios test: 71. Make sure getTimeWhenRun is right after start

2016-03-15T10:02:48.081Z - info: Running on android test: 80. Three peers, one not in DB, one behind and one ahead

2016-03-15T10:02:48.284Z - info: Running on ios test: 72. Make sure getTimeWhenRun is -1 after function is called

2016-03-15T10:02:48.572Z - info: Running on ios test: 73. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-15T10:02:48.686Z - info: Running on android test: 81. More than maximum peers, make sure we only send maximum allowed

2016-03-15T10:02:48.897Z - info: Running on ios test: 74. Test TransientState

2016-03-15T10:02:49.229Z - info: Running on ios test: 75. No peers and empty database

2016-03-15T10:02:49.637Z - info: Running on ios test: 76. One peer and empty DB

2016-03-15T10:02:49.673Z - info: Running on android test: 82. two peers with empty DB, update the doc

2016-03-15T10:02:50.028Z - info: Running on ios test: 77. One peer with _Local set behind current seq

2016-03-15T10:02:50.556Z - info: Running on ios test: 78. One peer with _Local set equal to current seq

2016-03-15T10:02:51.072Z - debug: Socket disconnected: transport close 0 (LGE-LG-H815)

2016-03-15T10:02:51.151Z - info: Running on ios test: 79. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-15T10:02:51.674Z - info: Running on ios test: 80. Three peers, one not in DB, one behind and one ahead

2016-03-15T10:02:52.070Z - debug: Device presented: HTC-HTC One M8s (android) unittest socket:7

2016-03-15T10:02:52.071Z - info: Discarding surplus device: HTC-HTC One M8s

2016-03-15T10:02:52.331Z - info: Running on ios test: 81. More than maximum peers, make sure we only send maximum allowed

2016-03-15T10:02:53.041Z - debug: Socket disconnected: transport close 7 (HTC-HTC One M8s)

2016-03-15T10:02:53.259Z - info: Running on ios test: 82. two peers with empty DB, update the doc

2016-03-15T10:02:53.821Z - info: Running on ios test: 83. add doc and make sure tokens refresh when they expire

2016-03-15T10:02:54.721Z - info: Running on ios test: 84. start and stop and start and stop

2016-03-15T10:02:55.439Z - info: Running on ios test: 85. two identical starts in a row

2016-03-15T10:02:55.890Z - info: Running on ios test: 86. two different starts in a row

2016-03-15T10:02:56.463Z - info: Running on ios test: 87. two stops and a start and two stops

2016-03-15T10:02:56.973Z - info: Running on ios test: 88. we properly enqueue requests so no then needed

2016-03-15T10:02:57.517Z - info: Running on ios test: 89. test calculateSeqPointKeyId

2016-03-15T10:02:57.814Z - info: Running on ios test: 90. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-15T10:02:58.151Z - info: Running on ios test: 91. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-15T10:02:58.576Z - info: Running on ios test: 92. messages with invalid location or USN should be ignored

2016-03-15T10:02:58.932Z - info: Running on ios test: 93. verify that Thali-specific messages are filtered correctly

2016-03-15T10:02:59.299Z - info: Running on ios test: 94. #startListeningForAdvertisements should fail if start not called

2016-03-15T10:02:59.607Z - info: Running on ios test: 95. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-15T10:02:59.921Z - info: Running on ios test: 96. #start should fail if called twice in a row

2016-03-15T10:03:00.296Z - info: Running on ios test: 97. should not be started after stop is called

2016-03-15T10:03:00.609Z - info: Running on ios test: 98. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-15T10:03:01.024Z - info: Running on ios test: 99. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-15T10:03:01.351Z - info: Running on ios test: 100. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-15T10:03:01.713Z - info: Running on ios test: 101. #stop can be called multiple times in a row

2016-03-15T10:03:02.055Z - info: Running on ios test: 102. #startListeningForAdvertisements can be called multiple times in a row

2016-03-15T10:03:02.434Z - info: Running on ios test: 103. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-15T10:03:02.674Z - info: Running on ios test: 104. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-15T10:03:03.038Z - info: Running on ios test: 105. functions are run from a queue in the right order

2016-03-15T10:03:03.487Z - info: Running on ios test: 106. #ThaliPeerPoolDefault - single action

2016-03-15T10:03:03.818Z - info: Running on ios test: 107. #ThaliPeerPoolDefault - multiple actions

2016-03-15T10:03:04.244Z - info: Test run on ios complete

2016-03-15T10:03:04.247Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-15T10:03:04.249Z - info: PLATFORM: ios

2016-03-15T10:03:04.250Z - info: RESULT: PASS

2016-03-15T10:03:04.251Z - info: 107 of 107 tests completed

2016-03-15T10:03:04.252Z - info: 107/107 passed (0 failures)

2016-03-15T10:03:04.253Z - info: --- Test Details ---



2016-03-15T10:03:04.254Z - info: 1. calling createNativeListener directly rejects - pass

2016-03-15T10:03:04.255Z - info: 2. emits incomingConnectionState - pass

2016-03-15T10:03:04.256Z - info: 3. emits routerPortConnectionFailed - pass

2016-03-15T10:03:04.257Z - info: 4. native server connections all up - pass

2016-03-15T10:03:04.258Z - info: 5. native server - closing incoming stream cleans outgoing socket - pass

2016-03-15T10:03:04.259Z - info: 6. native server - closing incoming connection cleans outgoing socket - pass

2016-03-15T10:03:04.260Z - info: 7. native server - closing outgoing socket cleans associated mux stream - pass

2016-03-15T10:03:04.261Z - info: 8. native server - closing the whole server cleans everything up - pass
2016-03-15T10:03:04.262Z - info: 9. native server - we can get a ton of connections and data through and still clean up the server completely - pass

2016-03-15T10:03:04.263Z - info: 10. native server - simulate mux failure, make sure everything is cleaned up - pass

2016-03-15T10:03:04.264Z - info: 11. native server - timing out the incoming connection cleans everything up - pass

2016-03-15T10:03:04.264Z - info: 12. closeAll can close even when connections open - pass

2016-03-15T10:03:04.265Z - info: 13. closeAll with promise - pass

2016-03-15T10:03:04.266Z - info: 14. multiplex can send data - pass

2016-03-15T10:03:04.267Z - info: 15. enqueue and run in order - pass

2016-03-15T10:03:04.268Z - info: 16. enqueueAtTop and run backwards - pass

2016-03-15T10:03:04.269Z - info: 17. mix enqueue and enqueueAtTop - pass

2016-03-15T10:03:04.270Z - info: 18. queues handled independently - pass
2016-03-15T10:03:04.271Z - info: 19. basic - pass

2016-03-15T10:03:04.272Z - info: 20. another - pass

2016-03-15T10:03:04.273Z - info: 21. #startListeningForAdvertisements should fail if start not called - pass

2016-03-15T10:03:04.274Z - info: 22. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-15T10:03:04.274Z - info: 23. should be able to call #stopListeningForAdvertisements many times - pass

2016-03-15T10:03:04.275Z - info: 24. should be able to call #startListeningForAdvertisements many times - pass

2016-03-15T10:03:04.276Z - info: 25. should be able to call #startUpdateAdvertisingAndListening many times - pass
2016-03-15T10:03:04.277Z - info: 26. should be able to call #stopAdvertisingAndListening many times - pass

2016-03-15T10:03:04.278Z - info: 27. #start should fail if called twice in a row - pass

2016-03-15T10:03:04.279Z - info: 28. does not emit duplicate discoveryAdvertisingStateUpdate - pass
2016-03-15T10:03:04.280Z - info: 29. does not send duplicate availability changes - pass
2016-03-15T10:03:04.281Z - info: 30. can get the network status - pass
2016-03-15T10:03:04.282Z - info: 31. wifi peer is marked unavailable if announcements stop - pass

2016-03-15T10:03:04.282Z - info: 32. can get the network status before starting - pass

2016-03-15T10:03:04.283Z - info: 33. #generatePreambleAndBeacons bad args - pass

2016-03-15T10:03:04.284Z - info: 34. #generatePreambleAndBeacons empty keys to notify - pass
2016-03-15T10:03:04.285Z - info: 35. #generatePreambleAndBeacons multiple keys to notify - pass

2016-03-15T10:03:04.286Z - info: 36. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass

2016-03-15T10:03:04.287Z - info: 37. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass

2016-03-15T10:03:04.288Z - info: 38. #parseBeacons expiration out of range lower - pass

2016-03-15T10:03:04.289Z - info: 39. #parseBeacons expiration out of range lower - pass

2016-03-15T10:03:04.290Z - info: 40. #parseBeacons no beacons returns null - pass
2016-03-15T10:03:04.290Z - info: 41. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass

2016-03-15T10:03:04.291Z - info: 42. #parseBeacons addressBookCallback fails decrypt - pass

2016-03-15T10:03:04.292Z - info: 43. #parseBeacons addressBookCallback returns no matches - pass

2016-03-15T10:03:04.293Z - info: 44. #parseBeacons addressBookCallback returns spurious match - pass

2016-03-15T10:03:04.294Z - info: 45. #parseBeacons addressBookCallback returns public key - pass

2016-03-15T10:03:04.295Z - info: 46. #parseBeacons with beacons both for and not for the user - pass
2016-03-15T10:03:04.296Z - info: 47. Start and stop ThaliNotificationServer - pass

2016-03-15T10:03:04.297Z - info: 48. Pass an empty array to ThaliNotificationServer.start - pass

2016-03-15T10:03:04.298Z - info: 49. Pass a string to ThaliNotificationServer.start - pass
2016-03-15T10:03:04.298Z - info: 50. Pass an empty parameter to ThaliNotificationServer.start - pass
2016-03-15T10:03:04.299Z - info: 51. Make an HTTP request to /NotificationBeacons - pass
2016-03-15T10:03:04.300Z - info: 52. Make an HTTP request to /NotificationBeacons (no keys) - pass
2016-03-15T10:03:04.301Z - info: 53. Make an HTTP request to /NotificationBeacons before calling start - pass
2016-03-15T10:03:04.301Z - info: 54. #testThaliPeerAction - test getters - pass
2016-03-15T10:03:04.302Z - info: 55. #testThaliPeerAction - start and kill - pass
2016-03-15T10:03:04.303Z - info: 56. #testThaliPeerAction - double start - pass
2016-03-15T10:03:04.303Z - info: 57. #testThaliPeerAction - start after kill - pass
2016-03-15T10:03:04.304Z - info: 58. #testThaliPeerAction - make sure ids are unique - pass
2016-03-15T10:03:04.304Z - info: 59. Test PeerConnectionInformation basics - pass
2016-03-15T10:03:04.305Z - info: 60. Test PeerDictionary basic functionality - pass
2016-03-15T10:03:04.306Z - info: 61. Test PeerDictionary with multiple entries. - pass
2016-03-15T10:03:04.306Z - info: 62. RESOLVED entries are removed before WAITING state entry. - pass
2016-03-15T10:03:04.307Z - info: 63. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass
2016-03-15T10:03:04.307Z - info: 64. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass
2016-03-15T10:03:04.308Z - info: 65. #ThaliPeerPoolInterface - bad enqueues - pass
2016-03-15T10:03:04.309Z - info: 66. #ThaliPeerPoolInterface - do not allow same object type - pass
2016-03-15T10:03:04.309Z - info: 67. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass
2016-03-15T10:03:04.310Z - info: 68. compareBufferArrays - pass
2016-03-15T10:03:04.310Z - info: 69. Call start twice and get error - pass

2016-03-15T10:03:04.311Z - info: 70. Start and make sure it runs - pass
2016-03-15T10:03:04.312Z - info: 71. Make sure getTimeWhenRun is right after start - pass

2016-03-15T10:03:04.313Z - info: 72. Make sure getTimeWhenRun is -1 after function is called - pass

2016-03-15T10:03:04.314Z - info: 73. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass
2016-03-15T10:03:04.315Z - info: 74. Test TransientState - pass

2016-03-15T10:03:04.319Z - info: 75. No peers and empty database - pass

2016-03-15T10:03:04.320Z - info: 76. One peer and empty DB - pass

2016-03-15T10:03:04.321Z - info: 77. One peer with _Local set behind current seq - pass
2016-03-15T10:03:04.322Z - info: 78. One peer with _Local set equal to current seq - pass

2016-03-15T10:03:04.323Z - info: 79. One peer with _Local set ahead of current seq (and no this should not happen) - pass

2016-03-15T10:03:04.324Z - info: 80. Three peers, one not in DB, one behind and one ahead - pass

2016-03-15T10:03:04.325Z - info: 81. More than maximum peers, make sure we only send maximum allowed - pass
2016-03-15T10:03:04.326Z - info: 82. two peers with empty DB, update the doc - pass

2016-03-15T10:03:04.326Z - info: 83. add doc and make sure tokens refresh when they expire - pass

2016-03-15T10:03:04.327Z - info: 84. start and stop and start and stop - pass

2016-03-15T10:03:04.328Z - info: 85. two identical starts in a row - pass

2016-03-15T10:03:04.329Z - info: 86. two different starts in a row - pass

2016-03-15T10:03:04.330Z - info: 87. two stops and a start and two stops - pass

2016-03-15T10:03:04.331Z - info: 88. we properly enqueue requests so no then needed - pass

2016-03-15T10:03:04.332Z - info: 89. test calculateSeqPointKeyId - pass

2016-03-15T10:03:04.333Z - info: 90. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass

2016-03-15T10:03:04.334Z - info: 91. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-03-15T10:03:04.335Z - info: 92. messages with invalid location or USN should be ignored - pass

2016-03-15T10:03:04.336Z - info: 93. verify that Thali-specific messages are filtered correctly - pass

2016-03-15T10:03:04.337Z - info: 94. #startListeningForAdvertisements should fail if start not called - pass

2016-03-15T10:03:04.338Z - info: 95. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-15T10:03:04.339Z - info: 96. #start should fail if called twice in a row - pass

2016-03-15T10:03:04.340Z - info: 97. should not be started after stop is called - pass

2016-03-15T10:03:04.341Z - info: 98. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass

2016-03-15T10:03:04.342Z - info: 99. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass

2016-03-15T10:03:04.343Z - info: 100. #startUpdateAdvertisingAndListening should start hosting given router object - pass

2016-03-15T10:03:04.343Z - info: 101. #stop can be called multiple times in a row - pass

2016-03-15T10:03:04.344Z - info: 102. #startListeningForAdvertisements can be called multiple times in a row - pass

2016-03-15T10:03:04.345Z - info: 103. #stopListeningForAdvertisements can be called multiple times in a row - pass

2016-03-15T10:03:04.346Z - info: 104. #stopAdvertisingAndListening can be called multiple times in a row - pass

2016-03-15T10:03:04.347Z - info: 105. functions are run from a queue in the right order - pass

2016-03-15T10:03:04.348Z - info: 106. #ThaliPeerPoolDefault - single action - pass

2016-03-15T10:03:04.350Z - info: 107. #ThaliPeerPoolDefault - multiple actions - pass

2016-03-15T10:03:04.351Z - info: 

-== END ==-

2016-03-15T10:03:04.444Z - debug: Socket disconnected: transport close 2 (samsung-SM-N910C)

2016-03-15T10:03:05.385Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:8

2016-03-15T10:03:05.386Z - info: Discarding surplus device: LGE-LG-H815

2016-03-15T10:03:06.623Z - debug: Socket disconnected: transport close 8 (LGE-LG-H815)

2016-03-15T10:03:06.915Z - debug: Socket disconnected: transport close 1 (Apple-Iphone6-1)

2016-03-15T10:03:06.941Z - debug: Socket disconnected: transport close 3 (Apple-IpadAir2-1)


 
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
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62509094c453ee6_Make_CI_build_and_unit_tests_pass_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/62509094c453ee6_Make_CI_build_and_unit_tests_pass_vjrantal/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
STOP log received from  ZX1C223JKW Test has  FAILED
Device test finished on ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/62509094c453ee6_Make_CI_build_and_unit_tests_pass_vjrantal/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Android task is completed. [SUCCESS]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/62509094c453ee6_Make_CI_build_and_unit_tests_pass_vjrantal/thali05_LGE-LG-H815.md)

####Node name: thali06
Console output:
```
STOP log received from  FA55PYS00566 Test has  SUCCEEDED
Device test finished on FA55PYS00566 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:0 
child process exited with code 0 on device 7970f88c 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62509094c453ee6_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/62509094c453ee6_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
STOP log received from  4db5c8cc Test has  FAILED
Device test finished on 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62509094c453ee6_Make_CI_build_and_unit_tests_pass_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:0 
child process exited with code 0 on device 4325e43f 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62509094c453ee6_Make_CI_build_and_unit_tests_pass_vjrantal/thali08_samsung-SM-A300FU.md)




###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/62509094c453ee6_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/62509094c453ee6_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/62509094c453ee6_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/62509094c453ee6_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5s-1.md)



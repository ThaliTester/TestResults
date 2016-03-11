#### Test 62560673e7cbba2 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":10}}
2016-03-11T16:30:24.699Z - info: listening on *:3000

2016-03-11T16:30:26.194Z - debug: Device presented: samsung-SM-A500FU (android) unittest socket:0

2016-03-11T16:30:26.208Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:1

2016-03-11T16:30:26.210Z - info: Required number of android devices presented (2)

2016-03-11T16:30:26.214Z - info: Starting unit test run for platform: android

2016-03-11T16:30:26.339Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:2

2016-03-11T16:30:26.726Z - info: Running on android test: 1. closeAll can close even when connections open

2016-03-11T16:30:26.787Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:3

2016-03-11T16:30:26.788Z - info: Required number of ios devices presented (2)

2016-03-11T16:30:26.790Z - info: Starting unit test run for platform: ios

2016-03-11T16:30:27.138Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:4

2016-03-11T16:30:27.139Z - info: Discarding surplus device: LGE-LG-H815

2016-03-11T16:30:27.256Z - info: Running on android test: 2. closeAll with promise

2016-03-11T16:30:27.329Z - info: Running on ios test: 1. closeAll can close even when connections open

2016-03-11T16:30:27.664Z - info: Running on android test: 3. multiplex can send data

2016-03-11T16:30:27.878Z - info: Running on ios test: 2. closeAll with promise

2016-03-11T16:30:28.115Z - info: Running on android test: 4. enqueue and run in order

2016-03-11T16:30:28.279Z - info: Running on ios test: 3. multiplex can send data

2016-03-11T16:30:28.379Z - debug: Socket disconnected: transport close 4 (LGE-LG-H815)

2016-03-11T16:30:28.616Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:5

2016-03-11T16:30:28.617Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-11T16:30:28.695Z - info: Running on ios test: 4. enqueue and run in order

2016-03-11T16:30:29.147Z - debug: Device presented: motorola-XT1072 (android) unittest socket:6

2016-03-11T16:30:29.148Z - info: Discarding surplus device: motorola-XT1072

2016-03-11T16:30:29.162Z - info: Running on android test: 5. enqueueAtTop and run backwards

2016-03-11T16:30:29.356Z - info: Running on ios test: 5. enqueueAtTop and run backwards

2016-03-11T16:30:29.604Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:7

2016-03-11T16:30:29.605Z - info: Discarding surplus device: Apple-Iphone6-1

2016-03-11T16:30:29.699Z - info: Running on android test: 6. mix enqueue and enqueueAtTop

2016-03-11T16:30:29.746Z - info: Running on ios test: 6. mix enqueue and enqueueAtTop

2016-03-11T16:30:30.216Z - info: Running on android test: 7. queues handled independently

2016-03-11T16:30:30.249Z - info: Running on ios test: 7. queues handled independently

2016-03-11T16:30:30.328Z - debug: Socket disconnected: transport close 6 (motorola-XT1072)

2016-03-11T16:30:30.618Z - info: Running on android test: 8. basic

2016-03-11T16:30:30.677Z - info: Running on ios test: 8. basic

2016-03-11T16:30:30.966Z - info: Running on android test: 9. another

2016-03-11T16:30:31.020Z - info: Running on ios test: 9. another

2016-03-11T16:30:31.253Z - info: Running on android test: 10. #startListeningForAdvertisements should fail if start not called

2016-03-11T16:30:31.338Z - info: Running on ios test: 10. #startListeningForAdvertisements should fail if start not called

2016-03-11T16:30:31.405Z - debug: Socket disconnected: transport close 5 (Apple-Iphone5s-1)

2016-03-11T16:30:31.572Z - info: Running on android test: 11. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-11T16:30:31.768Z - info: Running on ios test: 11. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-11T16:30:32.000Z - info: Running on android test: 12. should be able to call #stopListeningForAdvertisements many times

2016-03-11T16:30:32.103Z - info: Running on ios test: 12. should be able to call #stopListeningForAdvertisements many times

2016-03-11T16:30:32.349Z - debug: Socket disconnected: transport close 7 (Apple-Iphone6-1)

2016-03-11T16:30:32.525Z - info: Running on android test: 13. should be able to call #startListeningForAdvertisements many times

2016-03-11T16:30:32.684Z - info: Running on ios test: 13. should be able to call #startListeningForAdvertisements many times

2016-03-11T16:30:33.033Z - info: Running on ios test: 14. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-11T16:30:33.037Z - info: Running on android test: 14. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-11T16:30:33.371Z - info: Running on ios test: 15. should be able to call #stopAdvertisingAndListening many times

2016-03-11T16:30:33.393Z - info: Running on android test: 15. should be able to call #stopAdvertisingAndListening many times

2016-03-11T16:30:33.729Z - info: Running on ios test: 16. #start should fail if called twice in a row

2016-03-11T16:30:33.756Z - info: Running on android test: 16. #start should fail if called twice in a row

2016-03-11T16:30:34.062Z - info: Running on ios test: 17. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-11T16:30:34.187Z - info: Running on android test: 17. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-11T16:30:34.444Z - info: Running on ios test: 18. does not send duplicate availability changes

2016-03-11T16:30:34.598Z - info: Running on android test: 18. does not send duplicate availability changes

2016-03-11T16:30:34.725Z - info: Running on ios test: 19. can get the network status

2016-03-11T16:30:35.087Z - info: Running on android test: 19. can get the network status

2016-03-11T16:30:35.209Z - info: Running on ios test: 20. wifi peer is marked unavailable if announcements stop

2016-03-11T16:30:35.579Z - info: Running on android test: 20. wifi peer is marked unavailable if announcements stop

2016-03-11T16:30:36.703Z - info: Running on ios test: 21. can get the network status before starting

2016-03-11T16:30:37.155Z - info: Running on android test: 21. can get the network status before starting

2016-03-11T16:30:37.220Z - info: Running on ios test: 22. #generatePreambleAndBeacons bad args

2016-03-11T16:30:37.495Z - info: Running on android test: 22. #generatePreambleAndBeacons bad args

2016-03-11T16:30:37.628Z - info: Running on ios test: 23. #generatePreambleAndBeacons empty keys to notify

2016-03-11T16:30:37.914Z - info: Running on android test: 23. #generatePreambleAndBeacons empty keys to notify

2016-03-11T16:30:37.968Z - info: Running on ios test: 24. #generatePreambleAndBeacons multiple keys to notify

2016-03-11T16:30:38.188Z - info: Running on android test: 24. #generatePreambleAndBeacons multiple keys to notify

2016-03-11T16:30:38.440Z - info: Running on ios test: 25. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-11T16:30:38.673Z - info: Running on android test: 25. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-11T16:30:38.773Z - info: Running on ios test: 26. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-11T16:30:39.124Z - info: Running on android test: 26. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-11T16:30:39.229Z - info: Running on ios test: 27. #parseBeacons expiration out of range lower

2016-03-11T16:30:39.474Z - info: Running on android test: 27. #parseBeacons expiration out of range lower

2016-03-11T16:30:39.580Z - info: Running on ios test: 28. #parseBeacons expiration out of range lower

2016-03-11T16:30:39.821Z - info: Running on android test: 28. #parseBeacons expiration out of range lower

2016-03-11T16:30:39.981Z - info: Running on ios test: 29. #parseBeacons no beacons returns null

2016-03-11T16:30:40.619Z - info: Running on android test: 29. #parseBeacons no beacons returns null

2016-03-11T16:30:40.913Z - info: Running on ios test: 30. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-11T16:30:41.172Z - info: Running on android test: 30. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-11T16:30:41.221Z - info: Running on ios test: 31. #parseBeacons addressBookCallback fails decrypt

2016-03-11T16:30:41.476Z - info: Running on android test: 31. #parseBeacons addressBookCallback fails decrypt

2016-03-11T16:30:41.630Z - info: Running on ios test: 32. #parseBeacons addressBookCallback returns no matches

2016-03-11T16:30:41.904Z - info: Running on android test: 32. #parseBeacons addressBookCallback returns no matches

2016-03-11T16:30:42.060Z - info: Running on ios test: 33. #parseBeacons addressBookCallback returns spurious match

2016-03-11T16:30:42.335Z - info: Running on android test: 33. #parseBeacons addressBookCallback returns spurious match

2016-03-11T16:30:42.456Z - info: Running on ios test: 34. #parseBeacons addressBookCallback returns public key

2016-03-11T16:30:42.841Z - info: Running on android test: 34. #parseBeacons addressBookCallback returns public key

2016-03-11T16:30:42.844Z - info: Running on ios test: 35. #parseBeacons with beacons both for and not for the user

2016-03-11T16:30:43.223Z - info: Running on android test: 35. #parseBeacons with beacons both for and not for the user

2016-03-11T16:30:43.375Z - info: Running on ios test: 36. Start and stop ThaliNotificationServer

2016-03-11T16:30:43.540Z - info: Running on android test: 36. Start and stop ThaliNotificationServer

2016-03-11T16:30:43.787Z - info: Running on ios test: 37. Pass an empty array to ThaliNotificationServer.start

2016-03-11T16:30:44.005Z - info: Running on android test: 37. Pass an empty array to ThaliNotificationServer.start

2016-03-11T16:30:44.237Z - info: Running on ios test: 38. Pass a string to ThaliNotificationServer.start

2016-03-11T16:30:44.396Z - info: Running on android test: 38. Pass a string to ThaliNotificationServer.start

2016-03-11T16:30:44.574Z - info: Running on ios test: 39. Pass an empty parameter to ThaliNotificationServer.start

2016-03-11T16:30:44.752Z - info: Running on android test: 39. Pass an empty parameter to ThaliNotificationServer.start

2016-03-11T16:30:44.887Z - info: Running on ios test: 40. Make an HTTP request to /NotificationBeacons

2016-03-11T16:30:45.173Z - info: Running on android test: 40. Make an HTTP request to /NotificationBeacons

2016-03-11T16:30:45.465Z - info: Running on ios test: 41. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-11T16:30:45.784Z - info: Running on ios test: 42. Make an HTTP request to /NotificationBeacons before calling start

2016-03-11T16:30:46.160Z - info: Running on ios test: 43. #testThaliPeerAction - test getters

2016-03-11T16:30:46.364Z - info: Running on android test: 41. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-11T16:30:46.507Z - info: Running on ios test: 44. #testThaliPeerAction - start and kill

2016-03-11T16:30:46.800Z - info: Running on android test: 42. Make an HTTP request to /NotificationBeacons before calling start

2016-03-11T16:30:46.818Z - info: Running on ios test: 45. #testThaliPeerAction - double start

2016-03-11T16:30:47.200Z - info: Running on ios test: 46. #testThaliPeerAction - start after kill

2016-03-11T16:30:47.588Z - info: Running on ios test: 47. #testThaliPeerAction - make sure ids are unique

2016-03-11T16:30:47.786Z - info: Running on android test: 43. #testThaliPeerAction - test getters

2016-03-11T16:30:47.821Z - info: Running on ios test: 48. Test PeerConnectionInformation basics

2016-03-11T16:30:48.057Z - info: Running on ios test: 49. Test PeerDictionary basic functionality

2016-03-11T16:30:48.060Z - info: Running on android test: 44. #testThaliPeerAction - start and kill

2016-03-11T16:30:48.394Z - info: Running on android test: 45. #testThaliPeerAction - double start

2016-03-11T16:30:48.400Z - info: Running on ios test: 50. Test PeerDictionary with multiple entries.

2016-03-11T16:30:48.694Z - info: Running on android test: 46. #testThaliPeerAction - start after kill

2016-03-11T16:30:49.002Z - info: Running on android test: 47. #testThaliPeerAction - make sure ids are unique

2016-03-11T16:30:49.362Z - info: Running on android test: 48. Test PeerConnectionInformation basics

2016-03-11T16:30:49.877Z - info: Running on android test: 49. Test PeerDictionary basic functionality

2016-03-11T16:30:50.333Z - info: Running on android test: 50. Test PeerDictionary with multiple entries.

2016-03-11T16:30:51.627Z - info: Running on ios test: 51. RESOLVED entries are removed before WAITING state entry.

2016-03-11T16:30:52.873Z - info: Running on ios test: 52. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-11T16:30:53.248Z - info: Running on android test: 51. RESOLVED entries are removed before WAITING state entry.

2016-03-11T16:30:54.306Z - info: Running on ios test: 53. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-11T16:30:54.727Z - info: Running on android test: 52. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-11T16:30:55.645Z - info: Running on ios test: 54. #ThaliPeerPoolInterface - bad enqueues

2016-03-11T16:30:55.944Z - info: Running on ios test: 55. #ThaliPeerPoolInterface - do not allow same object type

2016-03-11T16:30:56.212Z - info: Running on android test: 53. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-11T16:30:56.349Z - info: Running on ios test: 56. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-11T16:30:56.719Z - info: Running on ios test: 57. compareBufferArrays

2016-03-11T16:30:57.033Z - info: Running on ios test: 58. Call start twice and get error

2016-03-11T16:30:57.292Z - info: Running on ios test: 59. Start and make sure it runs

2016-03-11T16:30:57.580Z - info: Running on ios test: 60. Make sure getTimeWhenRun is right after start

2016-03-11T16:30:57.687Z - info: Running on android test: 54. #ThaliPeerPoolInterface - bad enqueues

2016-03-11T16:30:57.891Z - info: Running on ios test: 61. Make sure getTimeWhenRun is -1 after function is called

2016-03-11T16:30:58.058Z - info: Running on android test: 55. #ThaliPeerPoolInterface - do not allow same object type

2016-03-11T16:30:58.252Z - info: Running on ios test: 62. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-11T16:30:58.358Z - info: Running on android test: 56. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-11T16:30:58.534Z - info: Running on ios test: 63. Test TransientState

2016-03-11T16:30:58.676Z - info: Running on android test: 57. compareBufferArrays

2016-03-11T16:30:58.849Z - info: Running on ios test: 64. No peers and empty database

2016-03-11T16:30:58.990Z - info: Running on android test: 58. Call start twice and get error

2016-03-11T16:30:59.427Z - info: Running on android test: 59. Start and make sure it runs

2016-03-11T16:30:59.522Z - info: Running on ios test: 65. One peer and empty DB

2016-03-11T16:30:59.819Z - info: Running on android test: 60. Make sure getTimeWhenRun is right after start

2016-03-11T16:31:00.133Z - info: Running on ios test: 66. One peer with _Local set behind current seq

2016-03-11T16:31:00.195Z - info: Running on android test: 61. Make sure getTimeWhenRun is -1 after function is called

2016-03-11T16:31:00.616Z - info: Running on android test: 62. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-11T16:31:00.779Z - info: Running on ios test: 67. One peer with _Local set equal to current seq

2016-03-11T16:31:00.975Z - info: Running on android test: 63. Test TransientState

2016-03-11T16:31:01.271Z - info: Running on android test: 64. No peers and empty database

2016-03-11T16:31:01.488Z - info: Running on ios test: 68. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-11T16:31:01.826Z - info: Running on android test: 65. One peer and empty DB

2016-03-11T16:31:02.261Z - info: Running on ios test: 69. Three peers, one not in DB, one behind and one ahead

2016-03-11T16:31:02.534Z - info: Running on android test: 66. One peer with _Local set behind current seq

2016-03-11T16:31:03.172Z - info: Running on android test: 67. One peer with _Local set equal to current seq

2016-03-11T16:31:03.226Z - info: Running on ios test: 70. More than maximum peers, make sure we only send maximum allowed

2016-03-11T16:31:03.837Z - info: Running on android test: 68. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-11T16:31:04.443Z - info: Running on android test: 69. Three peers, one not in DB, one behind and one ahead

2016-03-11T16:31:04.839Z - info: Running on ios test: 71. two peers with empty DB, update the doc

2016-03-11T16:31:05.249Z - info: Running on android test: 70. More than maximum peers, make sure we only send maximum allowed

2016-03-11T16:31:05.757Z - info: Running on ios test: 72. add doc and make sure tokens refresh when they expire

2016-03-11T16:31:06.683Z - info: Running on android test: 71. two peers with empty DB, update the doc

2016-03-11T16:31:06.975Z - info: Running on ios test: 73. start and stop and start and stop

2016-03-11T16:31:07.428Z - info: Running on android test: 72. add doc and make sure tokens refresh when they expire

2016-03-11T16:31:07.692Z - info: Running on ios test: 74. two identical starts in a row

2016-03-11T16:31:08.278Z - info: Running on ios test: 75. two different starts in a row

2016-03-11T16:31:08.306Z - info: Running on android test: 73. start and stop and start and stop

2016-03-11T16:31:08.899Z - info: Running on android test: 74. two identical starts in a row

2016-03-11T16:31:08.963Z - info: Running on ios test: 76. two stops and a start and two stops

2016-03-11T16:31:09.585Z - info: Running on android test: 75. two different starts in a row

2016-03-11T16:31:09.613Z - info: Running on ios test: 77. we properly enqueue requests so no then needed

2016-03-11T16:31:10.056Z - info: Running on android test: 76. two stops and a start and two stops

2016-03-11T16:31:10.262Z - info: Running on ios test: 78. test calculateSeqPointKeyId

2016-03-11T16:31:10.581Z - info: Running on android test: 77. we properly enqueue requests so no then needed

2016-03-11T16:31:10.625Z - info: Running on ios test: 79. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-11T16:31:10.935Z - info: Running on ios test: 80. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-11T16:31:11.015Z - info: Running on android test: 78. test calculateSeqPointKeyId

2016-03-11T16:31:11.372Z - info: Running on ios test: 81. messages with invalid location or USN should be ignored

2016-03-11T16:31:11.435Z - info: Running on android test: 79. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-11T16:31:11.673Z - info: Running on ios test: 82. verify that Thali-specific messages are filtered correctly

2016-03-11T16:31:11.721Z - info: Running on android test: 80. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-11T16:31:11.918Z - info: Running on ios test: 83. #startListeningForAdvertisements should fail if start not called

2016-03-11T16:31:12.018Z - info: Running on android test: 81. messages with invalid location or USN should be ignored

2016-03-11T16:31:12.237Z - info: Running on ios test: 84. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-11T16:31:12.321Z - info: Running on android test: 82. verify that Thali-specific messages are filtered correctly

2016-03-11T16:31:12.513Z - info: Running on ios test: 85. #start should fail if called twice in a row

2016-03-11T16:31:12.650Z - info: Running on android test: 83. #startListeningForAdvertisements should fail if start not called

2016-03-11T16:31:12.861Z - info: Running on ios test: 86. should not be started after stop is called

2016-03-11T16:31:12.946Z - info: Running on android test: 84. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-11T16:31:13.132Z - info: Running on ios test: 87. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-11T16:31:13.263Z - info: Running on android test: 85. #start should fail if called twice in a row

2016-03-11T16:31:13.388Z - info: Running on ios test: 88. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-11T16:31:13.547Z - info: Running on android test: 86. should not be started after stop is called

2016-03-11T16:31:13.633Z - info: Running on ios test: 89. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-11T16:31:13.782Z - info: Running on android test: 87. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-11T16:31:14.075Z - info: Running on ios test: 90. #stop can be called multiple times in a row

2016-03-11T16:31:14.111Z - info: Running on android test: 88. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-11T16:31:14.420Z - info: Running on ios test: 91. #startListeningForAdvertisements can be called multiple times in a row

2016-03-11T16:31:14.542Z - info: Running on android test: 89. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-11T16:31:14.694Z - info: Running on ios test: 92. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-11T16:31:14.853Z - info: Running on android test: 90. #stop can be called multiple times in a row

2016-03-11T16:31:15.001Z - info: Running on ios test: 93. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-11T16:31:15.229Z - info: Running on android test: 91. #startListeningForAdvertisements can be called multiple times in a row

2016-03-11T16:31:15.360Z - info: Running on ios test: 94. functions are run from a queue in the right order

2016-03-11T16:31:15.591Z - info: Running on android test: 92. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-11T16:31:15.736Z - info: Running on ios test: 95. #ThaliPeerPoolDefault - single action

2016-03-11T16:31:15.894Z - info: Running on android test: 93. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-11T16:31:16.073Z - info: Running on ios test: 96. #ThaliPeerPoolDefault - multiple actions

2016-03-11T16:31:16.154Z - info: Running on android test: 94. functions are run from a queue in the right order

2016-03-11T16:31:16.490Z - info: Test run on ios complete

2016-03-11T16:31:16.492Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-11T16:31:16.493Z - info: PLATFORM: ios

2016-03-11T16:31:16.494Z - info: RESULT: PASS
2016-03-11T16:31:16.495Z - info: 96 of 96 tests completed

2016-03-11T16:31:16.496Z - info: 96/96 passed (0 failures)
2016-03-11T16:31:16.497Z - info: --- Test Details ---



2016-03-11T16:31:16.497Z - info: 1. closeAll can close even when connections open - pass
2016-03-11T16:31:16.498Z - info: 2. closeAll with promise - pass
2016-03-11T16:31:16.499Z - info: 3. multiplex can send data - pass

2016-03-11T16:31:16.499Z - info: 4. enqueue and run in order - pass
2016-03-11T16:31:16.500Z - info: 5. enqueueAtTop and run backwards - pass
2016-03-11T16:31:16.500Z - info: 6. mix enqueue and enqueueAtTop - pass

2016-03-11T16:31:16.501Z - info: 7. queues handled independently - pass
2016-03-11T16:31:16.501Z - info: 8. basic - pass

2016-03-11T16:31:16.502Z - info: 9. another - pass
2016-03-11T16:31:16.502Z - info: 10. #startListeningForAdvertisements should fail if start not called - pass
2016-03-11T16:31:16.503Z - info: 11. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-11T16:31:16.504Z - info: 12. should be able to call #stopListeningForAdvertisements many times - pass
2016-03-11T16:31:16.504Z - info: 13. should be able to call #startListeningForAdvertisements many times - pass
2016-03-11T16:31:16.505Z - info: 14. should be able to call #startUpdateAdvertisingAndListening many times - pass
2016-03-11T16:31:16.505Z - info: 15. should be able to call #stopAdvertisingAndListening many times - pass

2016-03-11T16:31:16.506Z - info: 16. #start should fail if called twice in a row - pass
2016-03-11T16:31:16.506Z - info: 17. does not emit duplicate discoveryAdvertisingStateUpdate - pass
2016-03-11T16:31:16.507Z - info: 18. does not send duplicate availability changes - pass

2016-03-11T16:31:16.507Z - info: 19. can get the network status - pass
2016-03-11T16:31:16.508Z - info: 20. wifi peer is marked unavailable if announcements stop - pass

2016-03-11T16:31:16.509Z - info: 21. can get the network status before starting - pass
2016-03-11T16:31:16.509Z - info: 22. #generatePreambleAndBeacons bad args - pass
2016-03-11T16:31:16.510Z - info: 23. #generatePreambleAndBeacons empty keys to notify - pass

2016-03-11T16:31:16.510Z - info: 24. #generatePreambleAndBeacons multiple keys to notify - pass
2016-03-11T16:31:16.511Z - info: 25. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass
2016-03-11T16:31:16.511Z - info: 26. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass

2016-03-11T16:31:16.512Z - info: 27. #parseBeacons expiration out of range lower - pass
2016-03-11T16:31:16.512Z - info: 28. #parseBeacons expiration out of range lower - pass
2016-03-11T16:31:16.513Z - info: 29. #parseBeacons no beacons returns null - pass

2016-03-11T16:31:16.513Z - info: 30. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass
2016-03-11T16:31:16.514Z - info: 31. #parseBeacons addressBookCallback fails decrypt - pass

2016-03-11T16:31:16.515Z - info: 32. #parseBeacons addressBookCallback returns no matches - pass
2016-03-11T16:31:16.515Z - info: 33. #parseBeacons addressBookCallback returns spurious match - pass
2016-03-11T16:31:16.516Z - info: 34. #parseBeacons addressBookCallback returns public key - pass

2016-03-11T16:31:16.516Z - info: 35. #parseBeacons with beacons both for and not for the user - pass
2016-03-11T16:31:16.517Z - info: 36. Start and stop ThaliNotificationServer - pass

2016-03-11T16:31:16.517Z - info: 37. Pass an empty array to ThaliNotificationServer.start - pass
2016-03-11T16:31:16.518Z - info: 38. Pass a string to ThaliNotificationServer.start - pass
2016-03-11T16:31:16.518Z - info: 39. Pass an empty parameter to ThaliNotificationServer.start - pass
2016-03-11T16:31:16.519Z - info: 40. Make an HTTP request to /NotificationBeacons - pass

2016-03-11T16:31:16.520Z - info: 41. Make an HTTP request to /NotificationBeacons (no keys) - pass
2016-03-11T16:31:16.520Z - info: 42. Make an HTTP request to /NotificationBeacons before calling start - pass

2016-03-11T16:31:16.521Z - info: 43. #testThaliPeerAction - test getters - pass
2016-03-11T16:31:16.521Z - info: 44. #testThaliPeerAction - start and kill - pass
2016-03-11T16:31:16.522Z - info: 45. #testThaliPeerAction - double start - pass

2016-03-11T16:31:16.522Z - info: 46. #testThaliPeerAction - start after kill - pass
2016-03-11T16:31:16.523Z - info: 47. #testThaliPeerAction - make sure ids are unique - pass

2016-03-11T16:31:16.524Z - info: 48. Test PeerConnectionInformation basics - pass
2016-03-11T16:31:16.524Z - info: 49. Test PeerDictionary basic functionality - pass
2016-03-11T16:31:16.525Z - info: 50. Test PeerDictionary with multiple entries. - pass

2016-03-11T16:31:16.525Z - info: 51. RESOLVED entries are removed before WAITING state entry. - pass
2016-03-11T16:31:16.526Z - info: 52. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass

2016-03-11T16:31:16.526Z - info: 53. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass
2016-03-11T16:31:16.527Z - info: 54. #ThaliPeerPoolInterface - bad enqueues - pass
2016-03-11T16:31:16.528Z - info: 55. #ThaliPeerPoolInterface - do not allow same object type - pass

2016-03-11T16:31:16.528Z - info: 56. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass
2016-03-11T16:31:16.529Z - info: 57. compareBufferArrays - pass
2016-03-11T16:31:16.529Z - info: 58. Call start twice and get error - pass

2016-03-11T16:31:16.530Z - info: 59. Start and make sure it runs - pass
2016-03-11T16:31:16.530Z - info: 60. Make sure getTimeWhenRun is right after start - pass
2016-03-11T16:31:16.531Z - info: 61. Make sure getTimeWhenRun is -1 after function is called - pass
2016-03-11T16:31:16.531Z - info: 62. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass
2016-03-11T16:31:16.532Z - info: 63. Test TransientState - pass
2016-03-11T16:31:16.532Z - info: 64. No peers and empty database - pass
2016-03-11T16:31:16.533Z - info: 65. One peer and empty DB - pass

2016-03-11T16:31:16.534Z - info: 66. One peer with _Local set behind current seq - pass
2016-03-11T16:31:16.534Z - info: 67. One peer with _Local set equal to current seq - pass
2016-03-11T16:31:16.535Z - info: 68. One peer with _Local set ahead of current seq (and no this should not happen) - pass

2016-03-11T16:31:16.535Z - info: 69. Three peers, one not in DB, one behind and one ahead - pass
2016-03-11T16:31:16.536Z - info: 70. More than maximum peers, make sure we only send maximum allowed - pass
2016-03-11T16:31:16.536Z - info: 71. two peers with empty DB, update the doc - pass

2016-03-11T16:31:16.537Z - info: 72. add doc and make sure tokens refresh when they expire - pass
2016-03-11T16:31:16.538Z - info: 73. start and stop and start and stop - pass

2016-03-11T16:31:16.541Z - info: 74. two identical starts in a row - pass

2016-03-11T16:31:16.542Z - info: 75. two different starts in a row - pass
2016-03-11T16:31:16.543Z - info: 76. two stops and a start and two stops - pass

2016-03-11T16:31:16.543Z - info: 77. we properly enqueue requests so no then needed - pass
2016-03-11T16:31:16.544Z - info: 78. test calculateSeqPointKeyId - pass
2016-03-11T16:31:16.544Z - info: 79. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass

2016-03-11T16:31:16.545Z - info: 80. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass
2016-03-11T16:31:16.546Z - info: 81. messages with invalid location or USN should be ignored - pass
2016-03-11T16:31:16.546Z - info: 82. verify that Thali-specific messages are filtered correctly - pass

2016-03-11T16:31:16.547Z - info: 83. #startListeningForAdvertisements should fail if start not called - pass
2016-03-11T16:31:16.547Z - info: 84. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-11T16:31:16.548Z - info: 85. #start should fail if called twice in a row - pass
2016-03-11T16:31:16.549Z - info: 86. should not be started after stop is called - pass
2016-03-11T16:31:16.549Z - info: 87. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass

2016-03-11T16:31:16.550Z - info: 88. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass
2016-03-11T16:31:16.550Z - info: 89. #startUpdateAdvertisingAndListening should start hosting given router object - pass

2016-03-11T16:31:16.551Z - info: 90. #stop can be called multiple times in a row - pass
2016-03-11T16:31:16.551Z - info: 91. #startListeningForAdvertisements can be called multiple times in a row - pass
2016-03-11T16:31:16.552Z - info: 92. #stopListeningForAdvertisements can be called multiple times in a row - pass

2016-03-11T16:31:16.553Z - info: 93. #stopAdvertisingAndListening can be called multiple times in a row - pass
2016-03-11T16:31:16.553Z - info: 94. functions are run from a queue in the right order - pass

2016-03-11T16:31:16.554Z - info: 95. #ThaliPeerPoolDefault - single action - pass
2016-03-11T16:31:16.554Z - info: 96. #ThaliPeerPoolDefault - multiple actions - pass
2016-03-11T16:31:16.555Z - info: 

-== END ==-

2016-03-11T16:31:16.570Z - info: Running on android test: 95. #ThaliPeerPoolDefault - single action

2016-03-11T16:31:16.878Z - info: Running on android test: 96. #ThaliPeerPoolDefault - multiple actions

2016-03-11T16:31:17.215Z - info: Test run on android complete

2016-03-11T16:31:17.216Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-11T16:31:17.217Z - info: PLATFORM: android
2016-03-11T16:31:17.218Z - info: RESULT: PASS

2016-03-11T16:31:17.219Z - info: 96 of 96 tests completed
2016-03-11T16:31:17.220Z - info: 96/96 passed (0 failures)

2016-03-11T16:31:17.220Z - info: --- Test Details ---


2016-03-11T16:31:17.221Z - info: 1. closeAll can close even when connections open - pass

2016-03-11T16:31:17.221Z - info: 2. closeAll with promise - pass
2016-03-11T16:31:17.222Z - info: 3. multiplex can send data - pass
2016-03-11T16:31:17.223Z - info: 4. enqueue and run in order - pass

2016-03-11T16:31:17.223Z - info: 5. enqueueAtTop and run backwards - pass
2016-03-11T16:31:17.224Z - info: 6. mix enqueue and enqueueAtTop - pass
2016-03-11T16:31:17.224Z - info: 7. queues handled independently - pass

2016-03-11T16:31:17.225Z - info: 8. basic - pass
2016-03-11T16:31:17.225Z - info: 9. another - pass

2016-03-11T16:31:17.226Z - info: 10. #startListeningForAdvertisements should fail if start not called - pass
2016-03-11T16:31:17.226Z - info: 11. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-11T16:31:17.227Z - info: 12. should be able to call #stopListeningForAdvertisements many times - pass

2016-03-11T16:31:17.228Z - info: 13. should be able to call #startListeningForAdvertisements many times - pass
2016-03-11T16:31:17.228Z - info: 14. should be able to call #startUpdateAdvertisingAndListening many times - pass
2016-03-11T16:31:17.229Z - info: 15. should be able to call #stopAdvertisingAndListening many times - pass

2016-03-11T16:31:17.229Z - info: 16. #start should fail if called twice in a row - pass
2016-03-11T16:31:17.230Z - info: 17. does not emit duplicate discoveryAdvertisingStateUpdate - pass

2016-03-11T16:31:17.230Z - info: 18. does not send duplicate availability changes - pass
2016-03-11T16:31:17.231Z - info: 19. can get the network status - pass
2016-03-11T16:31:17.232Z - info: 20. wifi peer is marked unavailable if announcements stop - pass

2016-03-11T16:31:17.232Z - info: 21. can get the network status before starting - pass
2016-03-11T16:31:17.233Z - info: 22. #generatePreambleAndBeacons bad args - pass

2016-03-11T16:31:17.233Z - info: 23. #generatePreambleAndBeacons empty keys to notify - pass
2016-03-11T16:31:17.234Z - info: 24. #generatePreambleAndBeacons multiple keys to notify - pass

2016-03-11T16:31:17.234Z - info: 25. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass
2016-03-11T16:31:17.235Z - info: 26. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass

2016-03-11T16:31:17.236Z - info: 27. #parseBeacons expiration out of range lower - pass
2016-03-11T16:31:17.236Z - info: 28. #parseBeacons expiration out of range lower - pass
2016-03-11T16:31:17.237Z - info: 29. #parseBeacons no beacons returns null - pass

2016-03-11T16:31:17.237Z - info: 30. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass
2016-03-11T16:31:17.238Z - info: 31. #parseBeacons addressBookCallback fails decrypt - pass
2016-03-11T16:31:17.238Z - info: 32. #parseBeacons addressBookCallback returns no matches - pass

2016-03-11T16:31:17.239Z - info: 33. #parseBeacons addressBookCallback returns spurious match - pass
2016-03-11T16:31:17.240Z - info: 34. #parseBeacons addressBookCallback returns public key - pass

2016-03-11T16:31:17.240Z - info: 35. #parseBeacons with beacons both for and not for the user - pass
2016-03-11T16:31:17.241Z - info: 36. Start and stop ThaliNotificationServer - pass

2016-03-11T16:31:17.241Z - info: 37. Pass an empty array to ThaliNotificationServer.start - pass
2016-03-11T16:31:17.242Z - info: 38. Pass a string to ThaliNotificationServer.start - pass

2016-03-11T16:31:17.242Z - info: 39. Pass an empty parameter to ThaliNotificationServer.start - pass
2016-03-11T16:31:17.243Z - info: 40. Make an HTTP request to /NotificationBeacons - pass
2016-03-11T16:31:17.243Z - info: 41. Make an HTTP request to /NotificationBeacons (no keys) - pass

2016-03-11T16:31:17.244Z - info: 42. Make an HTTP request to /NotificationBeacons before calling start - pass
2016-03-11T16:31:17.244Z - info: 43. #testThaliPeerAction - test getters - pass

2016-03-11T16:31:17.245Z - info: 44. #testThaliPeerAction - start and kill - pass
2016-03-11T16:31:17.246Z - info: 45. #testThaliPeerAction - double start - pass
2016-03-11T16:31:17.246Z - info: 46. #testThaliPeerAction - start after kill - pass

2016-03-11T16:31:17.247Z - info: 47. #testThaliPeerAction - make sure ids are unique - pass
2016-03-11T16:31:17.247Z - info: 48. Test PeerConnectionInformation basics - pass

2016-03-11T16:31:17.248Z - info: 49. Test PeerDictionary basic functionality - pass
2016-03-11T16:31:17.249Z - info: 50. Test PeerDictionary with multiple entries. - pass

2016-03-11T16:31:17.249Z - info: 51. RESOLVED entries are removed before WAITING state entry. - pass
2016-03-11T16:31:17.250Z - info: 52. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass
2016-03-11T16:31:17.250Z - info: 53. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass

2016-03-11T16:31:17.251Z - info: 54. #ThaliPeerPoolInterface - bad enqueues - pass

2016-03-11T16:31:17.251Z - info: 55. #ThaliPeerPoolInterface - do not allow same object type - pass
2016-03-11T16:31:17.253Z - info: 56. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass

2016-03-11T16:31:17.254Z - info: 57. compareBufferArrays - pass

2016-03-11T16:31:17.254Z - info: 58. Call start twice and get error - pass

2016-03-11T16:31:17.261Z - info: 59. Start and make sure it runs - pass
2016-03-11T16:31:17.262Z - info: 60. Make sure getTimeWhenRun is right after start - pass

2016-03-11T16:31:17.263Z - info: 61. Make sure getTimeWhenRun is -1 after function is called - pass
2016-03-11T16:31:17.263Z - info: 62. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass

2016-03-11T16:31:17.264Z - info: 63. Test TransientState - pass
2016-03-11T16:31:17.264Z - info: 64. No peers and empty database - pass
2016-03-11T16:31:17.265Z - info: 65. One peer and empty DB - pass

2016-03-11T16:31:17.266Z - info: 66. One peer with _Local set behind current seq - pass
2016-03-11T16:31:17.266Z - info: 67. One peer with _Local set equal to current seq - pass

2016-03-11T16:31:17.267Z - info: 68. One peer with _Local set ahead of current seq (and no this should not happen) - pass
2016-03-11T16:31:17.267Z - info: 69. Three peers, one not in DB, one behind and one ahead - pass

2016-03-11T16:31:17.299Z - info: 70. More than maximum peers, make sure we only send maximum allowed - pass

2016-03-11T16:31:17.301Z - info: 71. two peers with empty DB, update the doc - pass
2016-03-11T16:31:17.301Z - info: 72. add doc and make sure tokens refresh when they expire - pass

2016-03-11T16:31:17.302Z - info: 73. start and stop and start and stop - pass
2016-03-11T16:31:17.302Z - info: 74. two identical starts in a row - pass
2016-03-11T16:31:17.303Z - info: 75. two different starts in a row - pass

2016-03-11T16:31:17.304Z - info: 76. two stops and a start and two stops - pass
2016-03-11T16:31:17.304Z - info: 77. we properly enqueue requests so no then needed - pass

2016-03-11T16:31:17.305Z - info: 78. test calculateSeqPointKeyId - pass
2016-03-11T16:31:17.305Z - info: 79. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass
2016-03-11T16:31:17.306Z - info: 80. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-03-11T16:31:17.306Z - info: 81. messages with invalid location or USN should be ignored - pass
2016-03-11T16:31:17.307Z - info: 82. verify that Thali-specific messages are filtered correctly - pass

2016-03-11T16:31:17.308Z - info: 83. #startListeningForAdvertisements should fail if start not called - pass
2016-03-11T16:31:17.308Z - info: 84. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-11T16:31:17.309Z - info: 85. #start should fail if called twice in a row - pass
2016-03-11T16:31:17.309Z - info: 86. should not be started after stop is called - pass
2016-03-11T16:31:17.310Z - info: 87. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass

2016-03-11T16:31:17.310Z - info: 88. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass
2016-03-11T16:31:17.311Z - info: 89. #startUpdateAdvertisingAndListening should start hosting given router object - pass

2016-03-11T16:31:17.311Z - info: 90. #stop can be called multiple times in a row - pass
2016-03-11T16:31:17.312Z - info: 91. #startListeningForAdvertisements can be called multiple times in a row - pass
2016-03-11T16:31:17.312Z - info: 92. #stopListeningForAdvertisements can be called multiple times in a row - pass

2016-03-11T16:31:17.313Z - info: 93. #stopAdvertisingAndListening can be called multiple times in a row - pass
2016-03-11T16:31:17.313Z - info: 94. functions are run from a queue in the right order - pass

2016-03-11T16:31:17.314Z - info: 95. #ThaliPeerPoolDefault - single action - pass
2016-03-11T16:31:17.314Z - info: 96. #ThaliPeerPoolDefault - multiple actions - pass

2016-03-11T16:31:17.315Z - info: 

-== END ==-


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
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:0 
child process exited with code 0 on device f56ad48d 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62560673e7cbba2_Fixed_the_state_error_and_updated_the_Bluetooth_connector_library_version_tompaana/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/62560673e7cbba2_Fixed_the_state_error_and_updated_the_Bluetooth_connector_library_version_tompaana/thali02_LGE-LG-D722.md)

####Node name: thali03
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Android task is completed. [SUCCESS]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/62560673e7cbba2_Fixed_the_state_error_and_updated_the_Bluetooth_connector_library_version_tompaana/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on ZX1C223JKW 
Android task is completed. [SUCCESS]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/62560673e7cbba2_Fixed_the_state_error_and_updated_the_Bluetooth_connector_library_version_tompaana/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Android task is completed. [SUCCESS]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/62560673e7cbba2_Fixed_the_state_error_and_updated_the_Bluetooth_connector_library_version_tompaana/thali05_LGE-LG-H815.md)

####Node name: thali06
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:0 
child process exited with code 0 on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:null 
child process exited with code null on device FA55PYS00566 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62560673e7cbba2_Fixed_the_state_error_and_updated_the_Bluetooth_connector_library_version_tompaana/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/62560673e7cbba2_Fixed_the_state_error_and_updated_the_Bluetooth_connector_library_version_tompaana/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:0 
child process exited with code 0 on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62560673e7cbba2_Fixed_the_state_error_and_updated_the_Bluetooth_connector_library_version_tompaana/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:0 
child process exited with code 0 on device 4325e43f 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62560673e7cbba2_Fixed_the_state_error_and_updated_the_Bluetooth_connector_library_version_tompaana/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 09a9416e0297d102 app:com.test.thalitest code:0 
child process exited with code 0 on device 09a9416e0297d102 
Android task is completed. [FAILED]
```
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/62560673e7cbba2_Fixed_the_state_error_and_updated_the_Bluetooth_connector_library_version_tompaana/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/62560673e7cbba2_Fixed_the_state_error_and_updated_the_Bluetooth_connector_library_version_tompaana/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/62560673e7cbba2_Fixed_the_state_error_and_updated_the_Bluetooth_connector_library_version_tompaana/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/62560673e7cbba2_Fixed_the_state_error_and_updated_the_Bluetooth_connector_library_version_tompaana/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/62560673e7cbba2_Fixed_the_state_error_and_updated_the_Bluetooth_connector_library_version_tompaana/iOS_IpadAir2-1.md)



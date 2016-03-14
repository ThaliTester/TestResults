#### Test 625090943f585e4 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":8}}
2016-03-14T16:19:51.133Z - info: listening on *:3000

2016-03-14T16:19:52.786Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:0

2016-03-14T16:19:53.408Z - debug: Device presented: samsung-SM-A500FU (android) unittest socket:1

2016-03-14T16:19:53.632Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:2

2016-03-14T16:19:53.635Z - info: Required number of ios devices presented (2)

2016-03-14T16:19:53.638Z - info: Starting unit test run for platform: ios

2016-03-14T16:19:54.168Z - info: Running on ios test: 1. closeAll can close even when connections open

2016-03-14T16:19:54.583Z - info: Running on ios test: 2. closeAll with promise

2016-03-14T16:19:54.881Z - info: Running on ios test: 3. multiplex can send data

2016-03-14T16:19:54.954Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:3

2016-03-14T16:19:54.955Z - info: Discarding surplus device: Apple-Iphone5-1

2016-03-14T16:19:55.334Z - info: Running on ios test: 4. enqueue and run in order

2016-03-14T16:19:55.846Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:4

2016-03-14T16:19:55.849Z - info: Required number of android devices presented (2)

2016-03-14T16:19:55.851Z - info: Starting unit test run for platform: android

2016-03-14T16:19:56.097Z - info: Running on ios test: 5. enqueueAtTop and run backwards

2016-03-14T16:19:56.372Z - info: Running on android test: 1. closeAll can close even when connections open

2016-03-14T16:19:56.459Z - info: Running on ios test: 6. mix enqueue and enqueueAtTop

2016-03-14T16:19:56.783Z - info: Running on android test: 2. closeAll with promise

2016-03-14T16:19:56.925Z - info: Running on ios test: 7. queues handled independently

2016-03-14T16:19:57.180Z - info: Running on android test: 3. multiplex can send data

2016-03-14T16:19:57.331Z - info: Running on ios test: 8. basic

2016-03-14T16:19:57.630Z - info: Running on android test: 4. enqueue and run in order

2016-03-14T16:19:57.760Z - info: Running on ios test: 9. another

2016-03-14T16:19:58.068Z - debug: Socket disconnected: transport close 3 (Apple-Iphone5-1)

2016-03-14T16:19:58.214Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:5

2016-03-14T16:19:58.216Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-14T16:19:58.294Z - info: Running on ios test: 10. #startListeningForAdvertisements should fail if start not called

2016-03-14T16:19:58.332Z - info: Running on android test: 5. enqueueAtTop and run backwards

2016-03-14T16:19:58.782Z - info: Running on ios test: 11. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-14T16:19:58.790Z - info: Running on android test: 6. mix enqueue and enqueueAtTop

2016-03-14T16:19:59.169Z - info: Running on ios test: 12. should be able to call #stopListeningForAdvertisements many times

2016-03-14T16:19:59.288Z - info: Running on android test: 7. queues handled independently

2016-03-14T16:19:59.566Z - info: Running on ios test: 13. should be able to call #startListeningForAdvertisements many times

2016-03-14T16:19:59.702Z - info: Running on android test: 8. basic

2016-03-14T16:20:00.017Z - info: Running on ios test: 14. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-14T16:20:00.116Z - info: Running on android test: 9. another

2016-03-14T16:20:00.458Z - info: Running on android test: 10. #startListeningForAdvertisements should fail if start not called

2016-03-14T16:20:00.469Z - info: Running on ios test: 15. should be able to call #stopAdvertisingAndListening many times

2016-03-14T16:20:00.992Z - info: Running on android test: 11. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-14T16:20:00.998Z - debug: Socket disconnected: transport close 5 (Apple-Iphone5s-1)

2016-03-14T16:20:01.093Z - info: Running on ios test: 16. #start should fail if called twice in a row

2016-03-14T16:20:01.463Z - info: Running on android test: 12. should be able to call #stopListeningForAdvertisements many times

2016-03-14T16:20:01.513Z - info: Running on ios test: 17. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-14T16:20:01.924Z - info: Running on android test: 13. should be able to call #startListeningForAdvertisements many times

2016-03-14T16:20:01.954Z - info: Running on ios test: 18. does not send duplicate availability changes

2016-03-14T16:20:02.475Z - info: Running on android test: 14. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-14T16:20:02.489Z - info: Running on ios test: 19. can get the network status

2016-03-14T16:20:03.093Z - info: Running on ios test: 20. wifi peer is marked unavailable if announcements stop

2016-03-14T16:20:03.096Z - info: Running on android test: 15. should be able to call #stopAdvertisingAndListening many times

2016-03-14T16:20:03.594Z - info: Running on android test: 16. #start should fail if called twice in a row

2016-03-14T16:20:04.192Z - info: Running on android test: 17. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-14T16:20:04.565Z - info: Running on ios test: 21. can get the network status before starting

2016-03-14T16:20:04.691Z - info: Running on android test: 18. does not send duplicate availability changes

2016-03-14T16:20:05.055Z - info: Running on ios test: 22. #generatePreambleAndBeacons bad args

2016-03-14T16:20:05.214Z - info: Running on android test: 19. can get the network status

2016-03-14T16:20:05.528Z - info: Running on ios test: 23. #generatePreambleAndBeacons empty keys to notify

2016-03-14T16:20:05.702Z - info: Running on android test: 20. wifi peer is marked unavailable if announcements stop

2016-03-14T16:20:06.000Z - info: Running on ios test: 24. #generatePreambleAndBeacons multiple keys to notify

2016-03-14T16:20:06.555Z - info: Running on ios test: 25. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-14T16:20:07.089Z - info: Running on ios test: 26. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-14T16:20:07.238Z - info: Running on android test: 21. can get the network status before starting

2016-03-14T16:20:07.864Z - info: Running on android test: 22. #generatePreambleAndBeacons bad args

2016-03-14T16:20:08.038Z - info: Running on ios test: 27. #parseBeacons expiration out of range lower

2016-03-14T16:20:08.212Z - info: Running on android test: 23. #generatePreambleAndBeacons empty keys to notify

2016-03-14T16:20:08.994Z - info: Running on ios test: 28. #parseBeacons expiration out of range lower

2016-03-14T16:20:09.061Z - info: Running on android test: 24. #generatePreambleAndBeacons multiple keys to notify

2016-03-14T16:20:09.440Z - info: Running on ios test: 29. #parseBeacons no beacons returns null

2016-03-14T16:20:09.610Z - info: Running on android test: 25. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-14T16:20:09.919Z - info: Running on ios test: 30. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-14T16:20:10.122Z - info: Running on android test: 26. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-14T16:20:10.301Z - info: Running on ios test: 31. #parseBeacons addressBookCallback fails decrypt

2016-03-14T16:20:10.523Z - info: Running on android test: 27. #parseBeacons expiration out of range lower

2016-03-14T16:20:10.763Z - info: Running on ios test: 32. #parseBeacons addressBookCallback returns no matches

2016-03-14T16:20:10.971Z - info: Running on android test: 28. #parseBeacons expiration out of range lower

2016-03-14T16:20:11.114Z - info: Running on ios test: 33. #parseBeacons addressBookCallback returns spurious match

2016-03-14T16:20:11.421Z - info: Running on android test: 29. #parseBeacons no beacons returns null

2016-03-14T16:20:11.548Z - info: Running on ios test: 34. #parseBeacons addressBookCallback returns public key

2016-03-14T16:20:11.809Z - info: Running on android test: 30. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-14T16:20:11.983Z - info: Running on ios test: 35. #parseBeacons with beacons both for and not for the user

2016-03-14T16:20:12.219Z - info: Running on android test: 31. #parseBeacons addressBookCallback fails decrypt

2016-03-14T16:20:12.355Z - info: Running on ios test: 36. Start and stop ThaliNotificationServer

2016-03-14T16:20:12.797Z - info: Running on ios test: 37. Pass an empty array to ThaliNotificationServer.start

2016-03-14T16:20:12.830Z - info: Running on android test: 32. #parseBeacons addressBookCallback returns no matches

2016-03-14T16:20:13.260Z - info: Running on ios test: 38. Pass a string to ThaliNotificationServer.start

2016-03-14T16:20:13.324Z - info: Running on android test: 33. #parseBeacons addressBookCallback returns spurious match

2016-03-14T16:20:13.658Z - info: Running on ios test: 39. Pass an empty parameter to ThaliNotificationServer.start

2016-03-14T16:20:13.939Z - info: Running on android test: 34. #parseBeacons addressBookCallback returns public key

2016-03-14T16:20:14.153Z - info: Running on ios test: 40. Make an HTTP request to /NotificationBeacons

2016-03-14T16:20:14.535Z - info: Running on android test: 35. #parseBeacons with beacons both for and not for the user

2016-03-14T16:20:14.694Z - info: Running on ios test: 41. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-14T16:20:14.950Z - info: Running on android test: 36. Start and stop ThaliNotificationServer

2016-03-14T16:20:15.055Z - info: Running on ios test: 42. Make an HTTP request to /NotificationBeacons before calling start

2016-03-14T16:20:15.488Z - info: Running on android test: 37. Pass an empty array to ThaliNotificationServer.start

2016-03-14T16:20:15.576Z - info: Running on ios test: 43. #testThaliPeerAction - test getters

2016-03-14T16:20:15.881Z - info: Running on ios test: 44. #testThaliPeerAction - start and kill

2016-03-14T16:20:15.889Z - info: Running on android test: 38. Pass a string to ThaliNotificationServer.start

2016-03-14T16:20:16.206Z - info: Running on ios test: 45. #testThaliPeerAction - double start

2016-03-14T16:20:16.255Z - info: Running on android test: 39. Pass an empty parameter to ThaliNotificationServer.start

2016-03-14T16:20:16.553Z - info: Running on ios test: 46. #testThaliPeerAction - start after kill

2016-03-14T16:20:16.627Z - info: Running on android test: 40. Make an HTTP request to /NotificationBeacons

2016-03-14T16:20:17.000Z - info: Running on ios test: 47. #testThaliPeerAction - make sure ids are unique

2016-03-14T16:20:17.345Z - info: Running on android test: 41. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-14T16:20:17.433Z - info: Running on ios test: 48. Test PeerConnectionInformation basics

2016-03-14T16:20:17.742Z - info: Running on ios test: 49. Test PeerDictionary basic functionality

2016-03-14T16:20:17.820Z - info: Running on android test: 42. Make an HTTP request to /NotificationBeacons before calling start

2016-03-14T16:20:18.182Z - info: Running on ios test: 50. Test PeerDictionary with multiple entries.

2016-03-14T16:20:18.315Z - info: Running on android test: 43. #testThaliPeerAction - test getters

2016-03-14T16:20:18.678Z - info: Running on android test: 44. #testThaliPeerAction - start and kill

2016-03-14T16:20:19.060Z - info: Running on android test: 45. #testThaliPeerAction - double start

2016-03-14T16:20:19.468Z - info: Running on android test: 46. #testThaliPeerAction - start after kill

2016-03-14T16:20:19.920Z - info: Running on android test: 47. #testThaliPeerAction - make sure ids are unique

2016-03-14T16:20:19.929Z - info: Running on ios test: 51. RESOLVED entries are removed before WAITING state entry.

2016-03-14T16:20:20.265Z - info: Running on android test: 48. Test PeerConnectionInformation basics

2016-03-14T16:20:20.573Z - info: Running on android test: 49. Test PeerDictionary basic functionality

2016-03-14T16:20:20.861Z - info: Running on android test: 50. Test PeerDictionary with multiple entries.

2016-03-14T16:20:21.216Z - info: Running on ios test: 52. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-14T16:20:22.272Z - info: Running on ios test: 53. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-14T16:20:23.267Z - info: Running on ios test: 54. #ThaliPeerPoolInterface - bad enqueues

2016-03-14T16:20:23.665Z - info: Running on ios test: 55. #ThaliPeerPoolInterface - do not allow same object type

2016-03-14T16:20:24.018Z - info: Running on android test: 51. RESOLVED entries are removed before WAITING state entry.

2016-03-14T16:20:24.056Z - info: Running on ios test: 56. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-14T16:20:24.457Z - info: Running on ios test: 57. compareBufferArrays

2016-03-14T16:20:24.806Z - info: Running on ios test: 58. Call start twice and get error

2016-03-14T16:20:25.174Z - info: Running on ios test: 59. Start and make sure it runs

2016-03-14T16:20:25.664Z - info: Running on ios test: 60. Make sure getTimeWhenRun is right after start

2016-03-14T16:20:26.090Z - info: Running on android test: 52. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-14T16:20:26.260Z - info: Running on ios test: 61. Make sure getTimeWhenRun is -1 after function is called

2016-03-14T16:20:27.098Z - info: Running on ios test: 62. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-14T16:20:27.536Z - info: Running on ios test: 63. Test TransientState

2016-03-14T16:20:27.664Z - info: Running on android test: 53. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-14T16:20:28.164Z - info: Running on ios test: 64. No peers and empty database

2016-03-14T16:20:28.847Z - info: Running on ios test: 65. One peer and empty DB

2016-03-14T16:20:29.444Z - info: Running on ios test: 66. One peer with _Local set behind current seq

2016-03-14T16:20:29.520Z - info: Running on android test: 54. #ThaliPeerPoolInterface - bad enqueues

2016-03-14T16:20:29.967Z - info: Running on android test: 55. #ThaliPeerPoolInterface - do not allow same object type

2016-03-14T16:20:30.113Z - info: Running on ios test: 67. One peer with _Local set equal to current seq

2016-03-14T16:20:30.354Z - info: Running on android test: 56. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-14T16:20:30.810Z - info: Running on ios test: 68. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-14T16:20:30.865Z - info: Running on android test: 57. compareBufferArrays

2016-03-14T16:20:31.248Z - info: Running on android test: 58. Call start twice and get error

2016-03-14T16:20:31.429Z - info: Running on ios test: 69. Three peers, one not in DB, one behind and one ahead

2016-03-14T16:20:31.652Z - info: Running on android test: 59. Start and make sure it runs

2016-03-14T16:20:32.148Z - info: Running on ios test: 70. More than maximum peers, make sure we only send maximum allowed

2016-03-14T16:20:32.949Z - info: Running on android test: 60. Make sure getTimeWhenRun is right after start

2016-03-14T16:20:33.367Z - info: Running on ios test: 71. two peers with empty DB, update the doc

2016-03-14T16:20:33.453Z - info: Running on android test: 61. Make sure getTimeWhenRun is -1 after function is called

2016-03-14T16:20:33.999Z - info: Running on android test: 62. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-14T16:20:34.346Z - info: Running on ios test: 72. add doc and make sure tokens refresh when they expire

2016-03-14T16:20:34.705Z - info: Running on android test: 63. Test TransientState

2016-03-14T16:20:35.372Z - info: Running on android test: 64. No peers and empty database

2016-03-14T16:20:35.560Z - info: Running on ios test: 73. start and stop and start and stop

2016-03-14T16:20:36.189Z - info: Running on ios test: 74. two identical starts in a row

2016-03-14T16:20:36.238Z - info: Running on android test: 65. One peer and empty DB

2016-03-14T16:20:36.772Z - info: Running on android test: 66. One peer with _Local set behind current seq

2016-03-14T16:20:36.781Z - info: Running on ios test: 75. two different starts in a row

2016-03-14T16:20:37.403Z - info: Running on ios test: 76. two stops and a start and two stops

2016-03-14T16:20:37.559Z - info: Running on android test: 67. One peer with _Local set equal to current seq

2016-03-14T16:20:38.023Z - info: Running on ios test: 77. we properly enqueue requests so no then needed

2016-03-14T16:20:38.228Z - info: Running on android test: 68. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-14T16:20:38.778Z - info: Running on android test: 69. Three peers, one not in DB, one behind and one ahead

2016-03-14T16:20:38.843Z - info: Running on ios test: 78. test calculateSeqPointKeyId

2016-03-14T16:20:39.295Z - info: Running on ios test: 79. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-14T16:20:39.619Z - info: Running on android test: 70. More than maximum peers, make sure we only send maximum allowed

2016-03-14T16:20:39.757Z - info: Running on ios test: 80. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-14T16:20:40.303Z - info: Running on ios test: 81. messages with invalid location or USN should be ignored

2016-03-14T16:20:40.686Z - info: Running on ios test: 82. verify that Thali-specific messages are filtered correctly

2016-03-14T16:20:41.044Z - info: Running on android test: 71. two peers with empty DB, update the doc

2016-03-14T16:20:41.048Z - info: Running on ios test: 83. #startListeningForAdvertisements should fail if start not called

2016-03-14T16:20:41.397Z - info: Running on ios test: 84. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-14T16:20:41.772Z - info: Running on ios test: 85. #start should fail if called twice in a row

2016-03-14T16:20:41.885Z - info: Running on android test: 72. add doc and make sure tokens refresh when they expire

2016-03-14T16:20:42.164Z - info: Running on ios test: 86. should not be started after stop is called

2016-03-14T16:20:42.614Z - info: Running on ios test: 87. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-14T16:20:43.045Z - info: Running on ios test: 88. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-14T16:20:43.409Z - info: Running on android test: 73. start and stop and start and stop

2016-03-14T16:20:43.522Z - info: Running on ios test: 89. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-14T16:20:44.046Z - debug: Device presented: HTC-HTC One M8s (android) unittest socket:6

2016-03-14T16:20:44.047Z - info: Discarding surplus device: HTC-HTC One M8s

2016-03-14T16:20:44.302Z - info: Running on ios test: 90. #stop can be called multiple times in a row

2016-03-14T16:20:44.525Z - info: Running on android test: 74. two identical starts in a row

2016-03-14T16:20:44.978Z - debug: Socket disconnected: transport close 6 (HTC-HTC One M8s)

2016-03-14T16:20:45.164Z - info: Running on android test: 75. two different starts in a row

2016-03-14T16:20:45.679Z - info: Running on android test: 76. two stops and a start and two stops

2016-03-14T16:20:47.068Z - debug: Socket disconnected: transport close 4 (LGE-LG-H815)

2016-03-14T16:20:47.106Z - info: Running on ios test: 91. #startListeningForAdvertisements can be called multiple times in a row

2016-03-14T16:20:47.721Z - debug: Socket disconnected: transport close 1 (samsung-SM-A500FU)

2016-03-14T16:20:47.823Z - info: Running on ios test: 92. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-14T16:20:48.251Z - info: Running on ios test: 93. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-14T16:20:48.736Z - info: Running on ios test: 94. functions are run from a queue in the right order

2016-03-14T16:20:49.151Z - info: Running on ios test: 95. #ThaliPeerPoolDefault - single action

2016-03-14T16:20:49.557Z - info: Running on ios test: 96. #ThaliPeerPoolDefault - multiple actions

2016-03-14T16:20:49.902Z - info: Test run on ios complete

2016-03-14T16:20:49.904Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-14T16:20:49.906Z - info: PLATFORM: ios

2016-03-14T16:20:49.907Z - info: RESULT: PASS
2016-03-14T16:20:49.908Z - info: 96 of 96 tests completed

2016-03-14T16:20:49.909Z - info: 96/96 passed (0 failures)

2016-03-14T16:20:49.910Z - info: --- Test Details ---



2016-03-14T16:20:49.911Z - info: 1. closeAll can close even when connections open - pass

2016-03-14T16:20:49.912Z - info: 2. closeAll with promise - pass
2016-03-14T16:20:49.913Z - info: 3. multiplex can send data - pass

2016-03-14T16:20:49.913Z - info: 4. enqueue and run in order - pass

2016-03-14T16:20:49.914Z - info: 5. enqueueAtTop and run backwards - pass

2016-03-14T16:20:49.915Z - info: 6. mix enqueue and enqueueAtTop - pass

2016-03-14T16:20:49.916Z - info: 7. queues handled independently - pass
2016-03-14T16:20:49.917Z - info: 8. basic - pass

2016-03-14T16:20:49.918Z - info: 9. another - pass

2016-03-14T16:20:49.918Z - info: 10. #startListeningForAdvertisements should fail if start not called - pass

2016-03-14T16:20:49.919Z - info: 11. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-14T16:20:49.920Z - info: 12. should be able to call #stopListeningForAdvertisements many times - pass
2016-03-14T16:20:49.921Z - info: 13. should be able to call #startListeningForAdvertisements many times - pass

2016-03-14T16:20:49.921Z - info: 14. should be able to call #startUpdateAdvertisingAndListening many times - pass

2016-03-14T16:20:49.922Z - info: 15. should be able to call #stopAdvertisingAndListening many times - pass

2016-03-14T16:20:49.923Z - info: 16. #start should fail if called twice in a row - pass
2016-03-14T16:20:49.924Z - info: 17. does not emit duplicate discoveryAdvertisingStateUpdate - pass

2016-03-14T16:20:49.925Z - info: 18. does not send duplicate availability changes - pass

2016-03-14T16:20:49.926Z - info: 19. can get the network status - pass

2016-03-14T16:20:49.926Z - info: 20. wifi peer is marked unavailable if announcements stop - pass
2016-03-14T16:20:49.927Z - info: 21. can get the network status before starting - pass

2016-03-14T16:20:49.928Z - info: 22. #generatePreambleAndBeacons bad args - pass

2016-03-14T16:20:49.929Z - info: 23. #generatePreambleAndBeacons empty keys to notify - pass

2016-03-14T16:20:49.930Z - info: 24. #generatePreambleAndBeacons multiple keys to notify - pass

2016-03-14T16:20:49.930Z - info: 25. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass
2016-03-14T16:20:49.931Z - info: 26. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass

2016-03-14T16:20:49.932Z - info: 27. #parseBeacons expiration out of range lower - pass

2016-03-14T16:20:49.933Z - info: 28. #parseBeacons expiration out of range lower - pass

2016-03-14T16:20:49.934Z - info: 29. #parseBeacons no beacons returns null - pass
2016-03-14T16:20:49.934Z - info: 30. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass

2016-03-14T16:20:49.935Z - info: 31. #parseBeacons addressBookCallback fails decrypt - pass

2016-03-14T16:20:49.936Z - info: 32. #parseBeacons addressBookCallback returns no matches - pass

2016-03-14T16:20:49.937Z - info: 33. #parseBeacons addressBookCallback returns spurious match - pass

2016-03-14T16:20:49.938Z - info: 34. #parseBeacons addressBookCallback returns public key - pass
2016-03-14T16:20:49.938Z - info: 35. #parseBeacons with beacons both for and not for the user - pass

2016-03-14T16:20:49.939Z - info: 36. Start and stop ThaliNotificationServer - pass

2016-03-14T16:20:49.940Z - info: 37. Pass an empty array to ThaliNotificationServer.start - pass

2016-03-14T16:20:49.941Z - info: 38. Pass a string to ThaliNotificationServer.start - pass

2016-03-14T16:20:49.942Z - info: 39. Pass an empty parameter to ThaliNotificationServer.start - pass
2016-03-14T16:20:49.942Z - info: 40. Make an HTTP request to /NotificationBeacons - pass

2016-03-14T16:20:49.943Z - info: 41. Make an HTTP request to /NotificationBeacons (no keys) - pass

2016-03-14T16:20:49.944Z - info: 42. Make an HTTP request to /NotificationBeacons before calling start - pass

2016-03-14T16:20:49.945Z - info: 43. #testThaliPeerAction - test getters - pass

2016-03-14T16:20:49.946Z - info: 44. #testThaliPeerAction - start and kill - pass
2016-03-14T16:20:49.946Z - info: 45. #testThaliPeerAction - double start - pass

2016-03-14T16:20:49.947Z - info: 46. #testThaliPeerAction - start after kill - pass

2016-03-14T16:20:49.948Z - info: 47. #testThaliPeerAction - make sure ids are unique - pass

2016-03-14T16:20:49.949Z - info: 48. Test PeerConnectionInformation basics - pass

2016-03-14T16:20:49.950Z - info: 49. Test PeerDictionary basic functionality - pass
2016-03-14T16:20:49.951Z - info: 50. Test PeerDictionary with multiple entries. - pass

2016-03-14T16:20:49.951Z - info: 51. RESOLVED entries are removed before WAITING state entry. - pass

2016-03-14T16:20:49.952Z - info: 52. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass

2016-03-14T16:20:49.953Z - info: 53. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass

2016-03-14T16:20:49.954Z - info: 54. #ThaliPeerPoolInterface - bad enqueues - pass
2016-03-14T16:20:49.954Z - info: 55. #ThaliPeerPoolInterface - do not allow same object type - pass

2016-03-14T16:20:49.955Z - info: 56. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass
2016-03-14T16:20:49.956Z - info: 57. compareBufferArrays - pass
2016-03-14T16:20:49.957Z - info: 58. Call start twice and get error - pass
2016-03-14T16:20:49.958Z - info: 59. Start and make sure it runs - pass

2016-03-14T16:20:49.958Z - info: 60. Make sure getTimeWhenRun is right after start - pass
2016-03-14T16:20:49.959Z - info: 61. Make sure getTimeWhenRun is -1 after function is called - pass

2016-03-14T16:20:49.960Z - info: 62. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass

2016-03-14T16:20:49.960Z - info: 63. Test TransientState - pass

2016-03-14T16:20:49.961Z - info: 64. No peers and empty database - pass

2016-03-14T16:20:49.962Z - info: 65. One peer and empty DB - pass

2016-03-14T16:20:49.963Z - info: 66. One peer with _Local set behind current seq - pass
2016-03-14T16:20:49.964Z - info: 67. One peer with _Local set equal to current seq - pass

2016-03-14T16:20:49.965Z - info: 68. One peer with _Local set ahead of current seq (and no this should not happen) - pass

2016-03-14T16:20:49.965Z - info: 69. Three peers, one not in DB, one behind and one ahead - pass

2016-03-14T16:20:49.966Z - info: 70. More than maximum peers, make sure we only send maximum allowed - pass
2016-03-14T16:20:49.967Z - info: 71. two peers with empty DB, update the doc - pass

2016-03-14T16:20:49.968Z - info: 72. add doc and make sure tokens refresh when they expire - pass

2016-03-14T16:20:49.969Z - info: 73. start and stop and start and stop - pass
2016-03-14T16:20:49.969Z - info: 74. two identical starts in a row - pass

2016-03-14T16:20:49.970Z - info: 75. two different starts in a row - pass

2016-03-14T16:20:49.971Z - info: 76. two stops and a start and two stops - pass

2016-03-14T16:20:49.972Z - info: 77. we properly enqueue requests so no then needed - pass
2016-03-14T16:20:49.972Z - info: 78. test calculateSeqPointKeyId - pass

2016-03-14T16:20:49.973Z - info: 79. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass
2016-03-14T16:20:49.974Z - info: 80. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass
2016-03-14T16:20:49.974Z - info: 81. messages with invalid location or USN should be ignored - pass
2016-03-14T16:20:49.975Z - info: 82. verify that Thali-specific messages are filtered correctly - pass
2016-03-14T16:20:49.976Z - info: 83. #startListeningForAdvertisements should fail if start not called - pass
2016-03-14T16:20:49.976Z - info: 84. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-14T16:20:49.977Z - info: 85. #start should fail if called twice in a row - pass
2016-03-14T16:20:49.977Z - info: 86. should not be started after stop is called - pass
2016-03-14T16:20:49.978Z - info: 87. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass
2016-03-14T16:20:49.978Z - info: 88. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass
2016-03-14T16:20:49.979Z - info: 89. #startUpdateAdvertisingAndListening should start hosting given router object - pass
2016-03-14T16:20:49.980Z - info: 90. #stop can be called multiple times in a row - pass
2016-03-14T16:20:49.980Z - info: 91. #startListeningForAdvertisements can be called multiple times in a row - pass
2016-03-14T16:20:49.981Z - info: 92. #stopListeningForAdvertisements can be called multiple times in a row - pass
2016-03-14T16:20:49.981Z - info: 93. #stopAdvertisingAndListening can be called multiple times in a row - pass
2016-03-14T16:20:49.982Z - info: 94. functions are run from a queue in the right order - pass
2016-03-14T16:20:49.985Z - info: 95. #ThaliPeerPoolDefault - single action - pass

2016-03-14T16:20:49.986Z - info: 96. #ThaliPeerPoolDefault - multiple actions - pass
2016-03-14T16:20:49.987Z - info: 

-== END ==-

2016-03-14T16:20:52.684Z - debug: Socket disconnected: transport close 0 (Apple-IpadAir2-1)

2016-03-14T16:20:52.819Z - debug: Socket disconnected: transport close 2 (Apple-Iphone6-1)

2016-03-14T16:21:01.531Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:7

2016-03-14T16:21:01.531Z - info: Discarding surplus device: LGE-LG-H815

2016-03-14T16:21:02.529Z - debug: Socket disconnected: transport close 7 (LGE-LG-H815)


 
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
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:0 
child process exited with code 0 on device f56ad48d 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/625090943f585e4_Make_CI_build_and_unit_tests_pass_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/625090943f585e4_Make_CI_build_and_unit_tests_pass_vjrantal/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
STOP log received from  ZX1C223JKW Test has  FAILED
Device test finished on ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/625090943f585e4_Make_CI_build_and_unit_tests_pass_vjrantal/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Android task is completed. [SUCCESS]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/625090943f585e4_Make_CI_build_and_unit_tests_pass_vjrantal/thali05_LGE-LG-H815.md)

####Node name: thali06
Console output:
```
STOP log received from  7970f88c Test has  FAILED
Device test finished on 7970f88c 
STOP log received from  FA55PYS00566 Test has  SUCCEEDED
Device test finished on FA55PYS00566 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/625090943f585e4_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/625090943f585e4_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
STOP log received from  4db5c8cc Test has  FAILED
Device test finished on 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/625090943f585e4_Make_CI_build_and_unit_tests_pass_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
STOP log received from  4325e43f Test has  FAILED
Device test finished on 4325e43f 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/625090943f585e4_Make_CI_build_and_unit_tests_pass_vjrantal/thali08_samsung-SM-A300FU.md)




###iOS Logs
[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/625090943f585e4_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/625090943f585e4_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/625090943f585e4_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/625090943f585e4_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_IpadAir2-1.md)



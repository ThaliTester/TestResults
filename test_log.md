#### Test 6275440319c4f54 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":8}}
2016-03-14T15:15:15.680Z - info: listening on *:3000

2016-03-14T15:15:16.421Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:0

2016-03-14T15:15:16.539Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:1

2016-03-14T15:15:16.541Z - info: Required number of ios devices presented (2)

2016-03-14T15:15:16.545Z - info: Starting unit test run for platform: ios

2016-03-14T15:15:16.975Z - info: Running on ios test: 1. closeAll can close even when connections open

2016-03-14T15:15:17.443Z - info: Running on ios test: 2. closeAll with promise

2016-03-14T15:15:17.835Z - info: Running on ios test: 3. multiplex can send data

2016-03-14T15:15:18.006Z - debug: Device presented: samsung-SM-A300FU (android) unittest socket:2

2016-03-14T15:15:18.233Z - info: Running on ios test: 4. enqueue and run in order

2016-03-14T15:15:18.890Z - info: Running on ios test: 5. enqueueAtTop and run backwards

2016-03-14T15:15:19.095Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:3

2016-03-14T15:15:19.096Z - info: Required number of android devices presented (2)

2016-03-14T15:15:19.098Z - info: Starting unit test run for platform: android

2016-03-14T15:15:19.307Z - info: Running on ios test: 6. mix enqueue and enqueueAtTop

2016-03-14T15:15:19.676Z - info: Running on ios test: 7. queues handled independently

2016-03-14T15:15:19.810Z - info: Running on android test: 1. closeAll can close even when connections open

2016-03-14T15:15:19.837Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:4

2016-03-14T15:15:19.838Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-14T15:15:19.954Z - info: Running on ios test: 8. basic

2016-03-14T15:15:20.233Z - info: Running on ios test: 9. another

2016-03-14T15:15:20.310Z - info: Running on android test: 2. closeAll with promise

2016-03-14T15:15:20.354Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:5

2016-03-14T15:15:20.363Z - info: Discarding surplus device: Apple-Iphone5-1

2016-03-14T15:15:20.511Z - info: Running on ios test: 10. #startListeningForAdvertisements should fail if start not called

2016-03-14T15:15:20.601Z - info: Running on android test: 3. multiplex can send data

2016-03-14T15:15:20.919Z - info: Running on ios test: 11. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-14T15:15:21.001Z - info: Running on android test: 4. enqueue and run in order

2016-03-14T15:15:21.232Z - info: Running on ios test: 12. should be able to call #stopListeningForAdvertisements many times

2016-03-14T15:15:21.596Z - info: Running on ios test: 13. should be able to call #startListeningForAdvertisements many times

2016-03-14T15:15:21.782Z - info: Running on android test: 5. enqueueAtTop and run backwards

2016-03-14T15:15:21.930Z - info: Running on ios test: 14. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-14T15:15:22.163Z - info: Running on android test: 6. mix enqueue and enqueueAtTop

2016-03-14T15:15:22.289Z - info: Running on ios test: 15. should be able to call #stopAdvertisingAndListening many times

2016-03-14T15:15:22.399Z - debug: Socket disconnected: transport close 4 (Apple-Iphone5s-1)

2016-03-14T15:15:22.593Z - info: Running on android test: 7. queues handled independently

2016-03-14T15:15:22.669Z - info: Running on ios test: 16. #start should fail if called twice in a row

2016-03-14T15:15:23.039Z - info: Running on android test: 8. basic

2016-03-14T15:15:23.061Z - info: Running on ios test: 17. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-14T15:15:23.338Z - info: Running on android test: 9. another

2016-03-14T15:15:23.386Z - info: Running on ios test: 18. does not send duplicate availability changes

2016-03-14T15:15:23.456Z - debug: Socket disconnected: transport close 5 (Apple-Iphone5-1)

2016-03-14T15:15:23.655Z - info: Running on android test: 10. #startListeningForAdvertisements should fail if start not called

2016-03-14T15:15:23.710Z - info: Running on ios test: 19. can get the network status

2016-03-14T15:15:24.057Z - info: Running on ios test: 20. wifi peer is marked unavailable if announcements stop

2016-03-14T15:15:24.062Z - info: Running on android test: 11. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-14T15:15:24.423Z - info: Running on android test: 12. should be able to call #stopListeningForAdvertisements many times

2016-03-14T15:15:24.783Z - info: Running on android test: 13. should be able to call #startListeningForAdvertisements many times

2016-03-14T15:15:25.170Z - info: Running on android test: 14. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-14T15:15:25.573Z - info: Running on android test: 15. should be able to call #stopAdvertisingAndListening many times

2016-03-14T15:15:25.634Z - info: Running on ios test: 21. can get the network status before starting

2016-03-14T15:15:25.968Z - info: Running on android test: 16. #start should fail if called twice in a row

2016-03-14T15:15:25.979Z - info: Running on ios test: 22. Test BEACONS_RETRIEVED_AND_PARSED locally

2016-03-14T15:15:26.231Z - info: Running on android test: 17. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-14T15:15:26.331Z - info: Running on ios test: 23. Test HTTP_BAD_RESPONSE locally

2016-03-14T15:15:26.585Z - info: Running on android test: 18. does not send duplicate availability changes

2016-03-14T15:15:26.632Z - info: Running on ios test: 24. Test NETWORK_PROBLEM locally

2016-03-14T15:15:26.904Z - info: Running on android test: 19. can get the network status

2016-03-14T15:15:27.208Z - info: Running on android test: 20. wifi peer is marked unavailable if announcements stop

2016-03-14T15:15:27.363Z - info: Running on ios test: 25. Test timeout locally

2016-03-14T15:15:28.636Z - info: Running on android test: 21. can get the network status before starting

2016-03-14T15:15:28.856Z - info: Running on ios test: 26. Call the start two times

2016-03-14T15:15:28.959Z - info: Running on android test: 22. Test BEACONS_RETRIEVED_AND_PARSED locally

2016-03-14T15:15:29.401Z - info: Running on android test: 23. Test HTTP_BAD_RESPONSE locally

2016-03-14T15:15:29.405Z - info: Running on ios test: 27. Call the kill before calling the start

2016-03-14T15:15:29.799Z - info: Running on ios test: 28. Call the kill immediately after the start

2016-03-14T15:15:30.023Z - info: Running on android test: 24. Test NETWORK_PROBLEM locally

2016-03-14T15:15:30.324Z - info: Running on ios test: 29. Call the kill while waiting a response from the server

2016-03-14T15:15:30.962Z - info: Running on android test: 25. Test timeout locally

2016-03-14T15:15:32.586Z - info: Running on android test: 26. Call the start two times

2016-03-14T15:15:32.912Z - info: Running on ios test: 30. Test to exceed the max content size locally

2016-03-14T15:15:33.315Z - info: Running on android test: 27. Call the kill before calling the start

2016-03-14T15:15:33.743Z - info: Running on ios test: 31. #generatePreambleAndBeacons bad args

2016-03-14T15:15:34.075Z - info: Running on android test: 28. Call the kill immediately after the start

2016-03-14T15:15:34.181Z - info: Running on ios test: 32. #generatePreambleAndBeacons empty keys to notify

2016-03-14T15:15:34.454Z - info: Running on android test: 29. Call the kill while waiting a response from the server

2016-03-14T15:15:34.530Z - info: Running on ios test: 33. #generatePreambleAndBeacons multiple keys to notify

2016-03-14T15:15:35.119Z - info: Running on ios test: 34. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-14T15:15:35.533Z - info: Running on ios test: 35. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-14T15:15:35.838Z - info: Running on ios test: 36. #parseBeacons expiration out of range lower

2016-03-14T15:15:36.224Z - info: Running on ios test: 37. #parseBeacons expiration out of range lower

2016-03-14T15:15:36.539Z - info: Running on ios test: 38. #parseBeacons no beacons returns null

2016-03-14T15:15:36.874Z - info: Running on ios test: 39. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-14T15:15:36.975Z - info: Running on android test: 30. Test to exceed the max content size locally

2016-03-14T15:15:37.221Z - info: Running on ios test: 40. #parseBeacons addressBookCallback fails decrypt

2016-03-14T15:15:37.467Z - info: Running on android test: 31. #generatePreambleAndBeacons bad args

2016-03-14T15:15:37.641Z - info: Running on ios test: 41. #parseBeacons addressBookCallback returns no matches

2016-03-14T15:15:37.776Z - info: Running on android test: 32. #generatePreambleAndBeacons empty keys to notify

2016-03-14T15:15:37.997Z - info: Running on ios test: 42. #parseBeacons addressBookCallback returns spurious match

2016-03-14T15:15:38.089Z - info: Running on android test: 33. #generatePreambleAndBeacons multiple keys to notify

2016-03-14T15:15:38.258Z - info: Running on ios test: 43. #parseBeacons addressBookCallback returns public key

2016-03-14T15:15:38.581Z - info: Running on ios test: 44. #parseBeacons with beacons both for and not for the user

2016-03-14T15:15:38.809Z - info: Running on ios test: 45. Start and stop ThaliNotificationServer

2016-03-14T15:15:39.080Z - info: Running on ios test: 46. Pass an empty array to ThaliNotificationServer.start

2016-03-14T15:15:39.085Z - info: Running on android test: 34. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-14T15:15:39.362Z - info: Running on ios test: 47. Pass a string to ThaliNotificationServer.start

2016-03-14T15:15:39.366Z - info: Running on android test: 35. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-14T15:15:39.642Z - info: Running on android test: 36. #parseBeacons expiration out of range lower

2016-03-14T15:15:39.645Z - info: Running on ios test: 48. Pass an empty parameter to ThaliNotificationServer.start

2016-03-14T15:15:39.952Z - info: Running on android test: 37. #parseBeacons expiration out of range lower

2016-03-14T15:15:40.071Z - info: Running on ios test: 49. Make an HTTP request to /NotificationBeacons

2016-03-14T15:15:40.370Z - info: Running on android test: 38. #parseBeacons no beacons returns null

2016-03-14T15:15:40.569Z - info: Running on ios test: 50. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-14T15:15:40.702Z - info: Running on android test: 39. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-14T15:15:40.935Z - info: Running on ios test: 51. Make an HTTP request to /NotificationBeacons before calling start

2016-03-14T15:15:41.047Z - info: Running on android test: 40. #parseBeacons addressBookCallback fails decrypt

2016-03-14T15:15:41.366Z - info: Running on ios test: 52. #testThaliPeerAction - test getters

2016-03-14T15:15:41.489Z - info: Running on android test: 41. #parseBeacons addressBookCallback returns no matches

2016-03-14T15:15:41.709Z - info: Running on ios test: 53. #testThaliPeerAction - start and kill

2016-03-14T15:15:41.947Z - info: Running on android test: 42. #parseBeacons addressBookCallback returns spurious match

2016-03-14T15:15:42.034Z - info: Running on ios test: 54. #testThaliPeerAction - double start

2016-03-14T15:15:42.270Z - info: Running on ios test: 55. #testThaliPeerAction - start after kill

2016-03-14T15:15:42.349Z - info: Running on android test: 43. #parseBeacons addressBookCallback returns public key

2016-03-14T15:15:42.581Z - info: Running on ios test: 56. #testThaliPeerAction - make sure ids are unique

2016-03-14T15:15:42.703Z - info: Running on android test: 44. #parseBeacons with beacons both for and not for the user

2016-03-14T15:15:42.916Z - info: Running on ios test: 57. Test PeerConnectionInformation basics

2016-03-14T15:15:43.204Z - info: Running on android test: 45. Start and stop ThaliNotificationServer

2016-03-14T15:15:43.266Z - info: Running on ios test: 58. Test PeerDictionary basic functionality

2016-03-14T15:15:43.554Z - info: Running on ios test: 59. Test PeerDictionary with multiple entries.

2016-03-14T15:15:43.590Z - info: Running on android test: 46. Pass an empty array to ThaliNotificationServer.start

2016-03-14T15:15:43.901Z - info: Running on android test: 47. Pass a string to ThaliNotificationServer.start

2016-03-14T15:15:44.175Z - info: Running on android test: 48. Pass an empty parameter to ThaliNotificationServer.start

2016-03-14T15:15:44.494Z - info: Running on android test: 49. Make an HTTP request to /NotificationBeacons

2016-03-14T15:15:45.010Z - info: Running on android test: 50. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-14T15:15:45.102Z - info: Running on ios test: 60. RESOLVED entries are removed before WAITING state entry.

2016-03-14T15:15:45.403Z - info: Running on android test: 51. Make an HTTP request to /NotificationBeacons before calling start

2016-03-14T15:15:45.813Z - info: Running on android test: 52. #testThaliPeerAction - test getters

2016-03-14T15:15:45.994Z - info: Running on ios test: 61. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-14T15:15:46.107Z - info: Running on android test: 53. #testThaliPeerAction - start and kill

2016-03-14T15:15:46.438Z - info: Running on android test: 54. #testThaliPeerAction - double start

2016-03-14T15:15:46.776Z - info: Running on android test: 55. #testThaliPeerAction - start after kill

2016-03-14T15:15:46.791Z - info: Running on ios test: 62. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-14T15:15:47.053Z - info: Running on android test: 56. #testThaliPeerAction - make sure ids are unique

2016-03-14T15:15:47.428Z - info: Running on android test: 57. Test PeerConnectionInformation basics

2016-03-14T15:15:47.618Z - info: Running on ios test: 63. #ThaliPeerPoolInterface - bad enqueues

2016-03-14T15:15:47.826Z - info: Running on android test: 58. Test PeerDictionary basic functionality

2016-03-14T15:15:47.964Z - info: Running on ios test: 64. #ThaliPeerPoolInterface - do not allow same object type

2016-03-14T15:15:48.202Z - info: Running on android test: 59. Test PeerDictionary with multiple entries.

2016-03-14T15:15:48.344Z - info: Running on ios test: 65. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-14T15:15:48.658Z - info: Running on ios test: 66. compareBufferArrays

2016-03-14T15:15:48.907Z - info: Running on ios test: 67. Call start twice and get error

2016-03-14T15:15:49.192Z - info: Running on ios test: 68. Start and make sure it runs

2016-03-14T15:15:49.420Z - info: Running on ios test: 69. Make sure getTimeWhenRun is right after start

2016-03-14T15:15:49.696Z - info: Running on ios test: 70. Make sure getTimeWhenRun is -1 after function is called

2016-03-14T15:15:49.949Z - info: Running on ios test: 71. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-14T15:15:50.224Z - info: Running on ios test: 72. Test TransientState

2016-03-14T15:15:50.515Z - info: Running on ios test: 73. No peers and empty database

2016-03-14T15:15:51.074Z - info: Running on android test: 60. RESOLVED entries are removed before WAITING state entry.

2016-03-14T15:15:51.102Z - info: Running on ios test: 74. One peer and empty DB

2016-03-14T15:15:51.646Z - info: Running on ios test: 75. One peer with _Local set behind current seq

2016-03-14T15:15:52.217Z - info: Running on ios test: 76. One peer with _Local set equal to current seq

2016-03-14T15:15:52.825Z - info: Running on ios test: 77. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-14T15:15:53.109Z - info: Running on android test: 61. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-14T15:15:53.424Z - info: Running on ios test: 78. Three peers, one not in DB, one behind and one ahead

2016-03-14T15:15:54.258Z - info: Running on ios test: 79. More than maximum peers, make sure we only send maximum allowed

2016-03-14T15:15:54.963Z - info: Running on android test: 62. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-14T15:15:55.583Z - info: Running on ios test: 80. two peers with empty DB, update the doc

2016-03-14T15:15:56.424Z - info: Running on android test: 63. #ThaliPeerPoolInterface - bad enqueues

2016-03-14T15:15:56.581Z - info: Running on ios test: 81. add doc and make sure tokens refresh when they expire

2016-03-14T15:15:56.846Z - info: Running on android test: 64. #ThaliPeerPoolInterface - do not allow same object type

2016-03-14T15:15:57.186Z - info: Running on android test: 65. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-14T15:15:57.602Z - info: Running on android test: 66. compareBufferArrays

2016-03-14T15:15:57.655Z - info: Running on ios test: 82. start and stop and start and stop

2016-03-14T15:15:58.089Z - info: Running on android test: 67. Call start twice and get error

2016-03-14T15:15:58.322Z - info: Running on ios test: 83. two identical starts in a row

2016-03-14T15:15:58.429Z - info: Running on android test: 68. Start and make sure it runs

2016-03-14T15:15:58.687Z - info: Running on android test: 69. Make sure getTimeWhenRun is right after start

2016-03-14T15:15:58.831Z - info: Running on ios test: 84. two different starts in a row

2016-03-14T15:15:58.958Z - info: Running on android test: 70. Make sure getTimeWhenRun is -1 after function is called

2016-03-14T15:15:59.292Z - info: Running on android test: 71. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-14T15:15:59.361Z - info: Running on ios test: 85. two stops and a start and two stops

2016-03-14T15:15:59.680Z - info: Running on android test: 72. Test TransientState

2016-03-14T15:15:59.853Z - info: Running on ios test: 86. we properly enqueue requests so no then needed

2016-03-14T15:15:59.921Z - info: Running on android test: 73. No peers and empty database

2016-03-14T15:16:00.412Z - info: Running on ios test: 87. test calculateSeqPointKeyId

2016-03-14T15:16:00.504Z - info: Running on android test: 74. One peer and empty DB

2016-03-14T15:16:00.709Z - info: Running on ios test: 88. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-14T15:16:01.002Z - info: Running on android test: 75. One peer with _Local set behind current seq

2016-03-14T15:16:01.119Z - info: Running on ios test: 89. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-14T15:16:01.542Z - info: Running on ios test: 90. messages with invalid location or USN should be ignored

2016-03-14T15:16:01.833Z - info: Running on android test: 76. One peer with _Local set equal to current seq

2016-03-14T15:16:01.911Z - info: Running on ios test: 91. verify that Thali-specific messages are filtered correctly

2016-03-14T15:16:02.157Z - info: Running on ios test: 92. #startListeningForAdvertisements should fail if start not called

2016-03-14T15:16:02.433Z - info: Running on ios test: 93. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-14T15:16:02.690Z - info: Running on ios test: 94. #start should fail if called twice in a row

2016-03-14T15:16:02.750Z - info: Running on android test: 77. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-14T15:16:03.004Z - info: Running on ios test: 95. should not be started after stop is called

2016-03-14T15:16:03.394Z - info: Running on android test: 78. Three peers, one not in DB, one behind and one ahead

2016-03-14T15:16:03.406Z - info: Running on ios test: 96. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-14T15:16:03.712Z - info: Running on ios test: 97. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-14T15:16:03.860Z - debug: Device presented: HTC-HTC One M8s (android) unittest socket:6

2016-03-14T15:16:03.861Z - info: Discarding surplus device: HTC-HTC One M8s

2016-03-14T15:16:04.062Z - info: Running on ios test: 98. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-14T15:16:04.178Z - info: Running on android test: 79. More than maximum peers, make sure we only send maximum allowed

2016-03-14T15:16:04.446Z - info: Running on ios test: 99. #stop can be called multiple times in a row

2016-03-14T15:16:04.725Z - info: Running on ios test: 100. #startListeningForAdvertisements can be called multiple times in a row

2016-03-14T15:16:05.166Z - info: Running on ios test: 101. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-14T15:16:05.187Z - debug: Socket disconnected: transport close 6 (HTC-HTC One M8s)

2016-03-14T15:16:05.509Z - info: Running on ios test: 102. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-14T15:16:05.587Z - info: Running on android test: 80. two peers with empty DB, update the doc

2016-03-14T15:16:05.787Z - info: Running on ios test: 103. functions are run from a queue in the right order

2016-03-14T15:16:06.166Z - info: Running on ios test: 104. #ThaliPeerPoolDefault - single action

2016-03-14T15:16:06.383Z - info: Running on android test: 81. add doc and make sure tokens refresh when they expire

2016-03-14T15:16:06.388Z - info: Running on ios test: 105. #ThaliPeerPoolDefault - multiple actions

2016-03-14T15:16:06.653Z - info: Test run on ios complete

2016-03-14T15:16:06.655Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-14T15:16:06.657Z - info: PLATFORM: ios

2016-03-14T15:16:06.658Z - info: RESULT: PASS

2016-03-14T15:16:06.659Z - info: 105 of 105 tests completed
2016-03-14T15:16:06.660Z - info: 105/105 passed (0 failures)

2016-03-14T15:16:06.660Z - info: --- Test Details ---


2016-03-14T15:16:06.661Z - info: 1. closeAll can close even when connections open - pass

2016-03-14T15:16:06.662Z - info: 2. closeAll with promise - pass
2016-03-14T15:16:06.663Z - info: 3. multiplex can send data - pass

2016-03-14T15:16:06.663Z - info: 4. enqueue and run in order - pass
2016-03-14T15:16:06.664Z - info: 5. enqueueAtTop and run backwards - pass

2016-03-14T15:16:06.665Z - info: 6. mix enqueue and enqueueAtTop - pass
2016-03-14T15:16:06.665Z - info: 7. queues handled independently - pass

2016-03-14T15:16:06.666Z - info: 8. basic - pass
2016-03-14T15:16:06.667Z - info: 9. another - pass

2016-03-14T15:16:06.667Z - info: 10. #startListeningForAdvertisements should fail if start not called - pass
2016-03-14T15:16:06.668Z - info: 11. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-14T15:16:06.669Z - info: 12. should be able to call #stopListeningForAdvertisements many times - pass
2016-03-14T15:16:06.669Z - info: 13. should be able to call #startListeningForAdvertisements many times - pass

2016-03-14T15:16:06.670Z - info: 14. should be able to call #startUpdateAdvertisingAndListening many times - pass
2016-03-14T15:16:06.671Z - info: 15. should be able to call #stopAdvertisingAndListening many times - pass
2016-03-14T15:16:06.671Z - info: 16. #start should fail if called twice in a row - pass

2016-03-14T15:16:06.672Z - info: 17. does not emit duplicate discoveryAdvertisingStateUpdate - pass
2016-03-14T15:16:06.673Z - info: 18. does not send duplicate availability changes - pass

2016-03-14T15:16:06.673Z - info: 19. can get the network status - pass
2016-03-14T15:16:06.674Z - info: 20. wifi peer is marked unavailable if announcements stop - pass

2016-03-14T15:16:06.674Z - info: 21. can get the network status before starting - pass
2016-03-14T15:16:06.675Z - info: 22. Test BEACONS_RETRIEVED_AND_PARSED locally - pass

2016-03-14T15:16:06.676Z - info: 23. Test HTTP_BAD_RESPONSE locally - pass
2016-03-14T15:16:06.676Z - info: 24. Test NETWORK_PROBLEM locally - pass

2016-03-14T15:16:06.677Z - info: 25. Test timeout locally - pass
2016-03-14T15:16:06.678Z - info: 26. Call the start two times - pass

2016-03-14T15:16:06.679Z - info: 27. Call the kill before calling the start - pass
2016-03-14T15:16:06.679Z - info: 28. Call the kill immediately after the start - pass

2016-03-14T15:16:06.680Z - info: 29. Call the kill while waiting a response from the server - pass
2016-03-14T15:16:06.681Z - info: 30. Test to exceed the max content size locally - pass

2016-03-14T15:16:06.681Z - info: 31. #generatePreambleAndBeacons bad args - pass
2016-03-14T15:16:06.682Z - info: 32. #generatePreambleAndBeacons empty keys to notify - pass

2016-03-14T15:16:06.683Z - info: 33. #generatePreambleAndBeacons multiple keys to notify - pass
2016-03-14T15:16:06.683Z - info: 34. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass

2016-03-14T15:16:06.684Z - info: 35. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass
2016-03-14T15:16:06.684Z - info: 36. #parseBeacons expiration out of range lower - pass

2016-03-14T15:16:06.685Z - info: 37. #parseBeacons expiration out of range lower - pass
2016-03-14T15:16:06.686Z - info: 38. #parseBeacons no beacons returns null - pass

2016-03-14T15:16:06.687Z - info: 39. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass
2016-03-14T15:16:06.687Z - info: 40. #parseBeacons addressBookCallback fails decrypt - pass

2016-03-14T15:16:06.688Z - info: 41. #parseBeacons addressBookCallback returns no matches - pass
2016-03-14T15:16:06.689Z - info: 42. #parseBeacons addressBookCallback returns spurious match - pass

2016-03-14T15:16:06.689Z - info: 43. #parseBeacons addressBookCallback returns public key - pass
2016-03-14T15:16:06.690Z - info: 44. #parseBeacons with beacons both for and not for the user - pass

2016-03-14T15:16:06.690Z - info: 45. Start and stop ThaliNotificationServer - pass
2016-03-14T15:16:06.691Z - info: 46. Pass an empty array to ThaliNotificationServer.start - pass

2016-03-14T15:16:06.692Z - info: 47. Pass a string to ThaliNotificationServer.start - pass
2016-03-14T15:16:06.693Z - info: 48. Pass an empty parameter to ThaliNotificationServer.start - pass

2016-03-14T15:16:06.693Z - info: 49. Make an HTTP request to /NotificationBeacons - pass
2016-03-14T15:16:06.694Z - info: 50. Make an HTTP request to /NotificationBeacons (no keys) - pass

2016-03-14T15:16:06.695Z - info: 51. Make an HTTP request to /NotificationBeacons before calling start - pass

2016-03-14T15:16:06.695Z - info: 52. #testThaliPeerAction - test getters - pass
2016-03-14T15:16:06.696Z - info: 53. #testThaliPeerAction - start and kill - pass

2016-03-14T15:16:06.697Z - info: 54. #testThaliPeerAction - double start - pass
2016-03-14T15:16:06.697Z - info: 55. #testThaliPeerAction - start after kill - pass
2016-03-14T15:16:06.698Z - info: 56. #testThaliPeerAction - make sure ids are unique - pass

2016-03-14T15:16:06.699Z - info: 57. Test PeerConnectionInformation basics - pass

2016-03-14T15:16:06.700Z - info: 58. Test PeerDictionary basic functionality - pass
2016-03-14T15:16:06.700Z - info: 59. Test PeerDictionary with multiple entries. - pass

2016-03-14T15:16:06.701Z - info: 60. RESOLVED entries are removed before WAITING state entry. - pass
2016-03-14T15:16:06.701Z - info: 61. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass

2016-03-14T15:16:06.702Z - info: 62. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass
2016-03-14T15:16:06.703Z - info: 63. #ThaliPeerPoolInterface - bad enqueues - pass
2016-03-14T15:16:06.703Z - info: 64. #ThaliPeerPoolInterface - do not allow same object type - pass

2016-03-14T15:16:06.704Z - info: 65. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass
2016-03-14T15:16:06.705Z - info: 66. compareBufferArrays - pass
2016-03-14T15:16:06.705Z - info: 67. Call start twice and get error - pass
2016-03-14T15:16:06.706Z - info: 68. Start and make sure it runs - pass

2016-03-14T15:16:06.707Z - info: 69. Make sure getTimeWhenRun is right after start - pass
2016-03-14T15:16:06.708Z - info: 70. Make sure getTimeWhenRun is -1 after function is called - pass

2016-03-14T15:16:06.708Z - info: 71. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass
2016-03-14T15:16:06.709Z - info: 72. Test TransientState - pass
2016-03-14T15:16:06.710Z - info: 73. No peers and empty database - pass

2016-03-14T15:16:06.710Z - info: 74. One peer and empty DB - pass
2016-03-14T15:16:06.711Z - info: 75. One peer with _Local set behind current seq - pass

2016-03-14T15:16:06.712Z - info: 76. One peer with _Local set equal to current seq - pass

2016-03-14T15:16:06.712Z - info: 77. One peer with _Local set ahead of current seq (and no this should not happen) - pass
2016-03-14T15:16:06.713Z - info: 78. Three peers, one not in DB, one behind and one ahead - pass

2016-03-14T15:16:06.714Z - info: 79. More than maximum peers, make sure we only send maximum allowed - pass
2016-03-14T15:16:06.714Z - info: 80. two peers with empty DB, update the doc - pass

2016-03-14T15:16:06.715Z - info: 81. add doc and make sure tokens refresh when they expire - pass
2016-03-14T15:16:06.716Z - info: 82. start and stop and start and stop - pass

2016-03-14T15:16:06.720Z - info: 83. two identical starts in a row - pass

2016-03-14T15:16:06.721Z - info: 84. two different starts in a row - pass
2016-03-14T15:16:06.721Z - info: 85. two stops and a start and two stops - pass

2016-03-14T15:16:06.722Z - info: 86. we properly enqueue requests so no then needed - pass
2016-03-14T15:16:06.723Z - info: 87. test calculateSeqPointKeyId - pass

2016-03-14T15:16:06.723Z - info: 88. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass
2016-03-14T15:16:06.724Z - info: 89. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-03-14T15:16:06.725Z - info: 90. messages with invalid location or USN should be ignored - pass
2016-03-14T15:16:06.725Z - info: 91. verify that Thali-specific messages are filtered correctly - pass

2016-03-14T15:16:06.726Z - info: 92. #startListeningForAdvertisements should fail if start not called - pass
2016-03-14T15:16:06.727Z - info: 93. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-14T15:16:06.727Z - info: 94. #start should fail if called twice in a row - pass
2016-03-14T15:16:06.728Z - info: 95. should not be started after stop is called - pass

2016-03-14T15:16:06.729Z - info: 96. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass
2016-03-14T15:16:06.729Z - info: 97. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass
2016-03-14T15:16:06.730Z - info: 98. #startUpdateAdvertisingAndListening should start hosting given router object - pass
2016-03-14T15:16:06.731Z - info: 99. #stop can be called multiple times in a row - pass
2016-03-14T15:16:06.731Z - info: 100. #startListeningForAdvertisements can be called multiple times in a row - pass
2016-03-14T15:16:06.732Z - info: 101. #stopListeningForAdvertisements can be called multiple times in a row - pass
2016-03-14T15:16:06.733Z - info: 102. #stopAdvertisingAndListening can be called multiple times in a row - pass
2016-03-14T15:16:06.733Z - info: 103. functions are run from a queue in the right order - pass
2016-03-14T15:16:06.734Z - info: 104. #ThaliPeerPoolDefault - single action - pass
2016-03-14T15:16:06.735Z - info: 105. #ThaliPeerPoolDefault - multiple actions - pass
2016-03-14T15:16:06.735Z - info: 

-== END ==-

2016-03-14T15:16:07.182Z - info: Running on android test: 82. start and stop and start and stop

2016-03-14T15:16:07.689Z - info: Running on android test: 83. two identical starts in a row

2016-03-14T15:16:08.223Z - info: Running on android test: 84. two different starts in a row

2016-03-14T15:16:08.644Z - info: Running on android test: 85. two stops and a start and two stops

2016-03-14T15:16:09.106Z - info: Running on android test: 86. we properly enqueue requests so no then needed

2016-03-14T15:16:09.420Z - debug: Socket disconnected: transport close 0 (Apple-IpadAir2-1)

2016-03-14T15:16:09.496Z - debug: Socket disconnected: transport close 1 (Apple-Iphone6-1)

2016-03-14T15:16:09.590Z - info: Running on android test: 87. test calculateSeqPointKeyId

2016-03-14T15:16:09.856Z - info: Running on android test: 88. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-14T15:16:10.223Z - info: Running on android test: 89. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-14T15:16:10.705Z - info: Running on android test: 90. messages with invalid location or USN should be ignored

2016-03-14T15:16:11.114Z - info: Running on android test: 91. verify that Thali-specific messages are filtered correctly

2016-03-14T15:16:11.512Z - info: Running on android test: 92. #startListeningForAdvertisements should fail if start not called

2016-03-14T15:16:11.891Z - info: Running on android test: 93. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-14T15:16:12.292Z - info: Running on android test: 94. #start should fail if called twice in a row

2016-03-14T15:16:12.627Z - info: Running on android test: 95. should not be started after stop is called

2016-03-14T15:16:12.995Z - info: Running on android test: 96. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-14T15:16:13.346Z - info: Running on android test: 97. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-14T15:16:13.748Z - info: Running on android test: 98. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-14T15:16:14.133Z - info: Running on android test: 99. #stop can be called multiple times in a row

2016-03-14T15:16:14.461Z - info: Running on android test: 100. #startListeningForAdvertisements can be called multiple times in a row

2016-03-14T15:16:14.815Z - info: Running on android test: 101. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-14T15:16:15.310Z - info: Running on android test: 102. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-14T15:16:15.840Z - info: Running on android test: 103. functions are run from a queue in the right order

2016-03-14T15:16:16.243Z - info: Running on android test: 104. #ThaliPeerPoolDefault - single action

2016-03-14T15:16:16.621Z - info: Running on android test: 105. #ThaliPeerPoolDefault - multiple actions

2016-03-14T15:16:17.001Z - info: Test run on android complete

2016-03-14T15:16:17.002Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-14T15:16:17.004Z - info: PLATFORM: android

2016-03-14T15:16:17.004Z - info: RESULT: PASS

2016-03-14T15:16:17.005Z - info: 105 of 105 tests completed
2016-03-14T15:16:17.006Z - info: 105/105 passed (0 failures)

2016-03-14T15:16:17.007Z - info: --- Test Details ---



2016-03-14T15:16:17.008Z - info: 1. closeAll can close even when connections open - pass
2016-03-14T15:16:17.009Z - info: 2. closeAll with promise - pass

2016-03-14T15:16:17.009Z - info: 3. multiplex can send data - pass

2016-03-14T15:16:17.010Z - info: 4. enqueue and run in order - pass
2016-03-14T15:16:17.010Z - info: 5. enqueueAtTop and run backwards - pass

2016-03-14T15:16:17.011Z - info: 6. mix enqueue and enqueueAtTop - pass
2016-03-14T15:16:17.012Z - info: 7. queues handled independently - pass

2016-03-14T15:16:17.012Z - info: 8. basic - pass

2016-03-14T15:16:17.013Z - info: 9. another - pass
2016-03-14T15:16:17.013Z - info: 10. #startListeningForAdvertisements should fail if start not called - pass

2016-03-14T15:16:17.014Z - info: 11. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-14T15:16:17.015Z - info: 12. should be able to call #stopListeningForAdvertisements many times - pass

2016-03-14T15:16:17.015Z - info: 13. should be able to call #startListeningForAdvertisements many times - pass

2016-03-14T15:16:17.016Z - info: 14. should be able to call #startUpdateAdvertisingAndListening many times - pass
2016-03-14T15:16:17.017Z - info: 15. should be able to call #stopAdvertisingAndListening many times - pass

2016-03-14T15:16:17.017Z - info: 16. #start should fail if called twice in a row - pass
2016-03-14T15:16:17.018Z - info: 17. does not emit duplicate discoveryAdvertisingStateUpdate - pass

2016-03-14T15:16:17.018Z - info: 18. does not send duplicate availability changes - pass
2016-03-14T15:16:17.019Z - info: 19. can get the network status - pass

2016-03-14T15:16:17.020Z - info: 20. wifi peer is marked unavailable if announcements stop - pass

2016-03-14T15:16:17.020Z - info: 21. can get the network status before starting - pass
2016-03-14T15:16:17.021Z - info: 22. Test BEACONS_RETRIEVED_AND_PARSED locally - pass

2016-03-14T15:16:17.021Z - info: 23. Test HTTP_BAD_RESPONSE locally - pass
2016-03-14T15:16:17.022Z - info: 24. Test NETWORK_PROBLEM locally - pass

2016-03-14T15:16:17.023Z - info: 25. Test timeout locally - pass

2016-03-14T15:16:17.023Z - info: 26. Call the start two times - pass
2016-03-14T15:16:17.024Z - info: 27. Call the kill before calling the start - pass

2016-03-14T15:16:17.024Z - info: 28. Call the kill immediately after the start - pass

2016-03-14T15:16:17.025Z - info: 29. Call the kill while waiting a response from the server - pass

2016-03-14T15:16:17.027Z - info: 30. Test to exceed the max content size locally - pass

2016-03-14T15:16:17.028Z - info: 31. #generatePreambleAndBeacons bad args - pass

2016-03-14T15:16:17.028Z - info: 32. #generatePreambleAndBeacons empty keys to notify - pass

2016-03-14T15:16:17.036Z - info: 33. #generatePreambleAndBeacons multiple keys to notify - pass

2016-03-14T15:16:17.036Z - info: 34. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass
2016-03-14T15:16:17.037Z - info: 35. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass

2016-03-14T15:16:17.038Z - info: 36. #parseBeacons expiration out of range lower - pass
2016-03-14T15:16:17.038Z - info: 37. #parseBeacons expiration out of range lower - pass

2016-03-14T15:16:17.039Z - info: 38. #parseBeacons no beacons returns null - pass
2016-03-14T15:16:17.040Z - info: 39. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass

2016-03-14T15:16:17.040Z - info: 40. #parseBeacons addressBookCallback fails decrypt - pass

2016-03-14T15:16:17.041Z - info: 41. #parseBeacons addressBookCallback returns no matches - pass
2016-03-14T15:16:17.042Z - info: 42. #parseBeacons addressBookCallback returns spurious match - pass

2016-03-14T15:16:17.042Z - info: 43. #parseBeacons addressBookCallback returns public key - pass

2016-03-14T15:16:17.073Z - info: 44. #parseBeacons with beacons both for and not for the user - pass

2016-03-14T15:16:17.075Z - info: 45. Start and stop ThaliNotificationServer - pass

2016-03-14T15:16:17.075Z - info: 46. Pass an empty array to ThaliNotificationServer.start - pass
2016-03-14T15:16:17.076Z - info: 47. Pass a string to ThaliNotificationServer.start - pass

2016-03-14T15:16:17.077Z - info: 48. Pass an empty parameter to ThaliNotificationServer.start - pass
2016-03-14T15:16:17.077Z - info: 49. Make an HTTP request to /NotificationBeacons - pass
2016-03-14T15:16:17.078Z - info: 50. Make an HTTP request to /NotificationBeacons (no keys) - pass
2016-03-14T15:16:17.078Z - info: 51. Make an HTTP request to /NotificationBeacons before calling start - pass

2016-03-14T15:16:17.079Z - info: 52. #testThaliPeerAction - test getters - pass
2016-03-14T15:16:17.079Z - info: 53. #testThaliPeerAction - start and kill - pass

2016-03-14T15:16:17.080Z - info: 54. #testThaliPeerAction - double start - pass
2016-03-14T15:16:17.081Z - info: 55. #testThaliPeerAction - start after kill - pass
2016-03-14T15:16:17.081Z - info: 56. #testThaliPeerAction - make sure ids are unique - pass

2016-03-14T15:16:17.082Z - info: 57. Test PeerConnectionInformation basics - pass
2016-03-14T15:16:17.082Z - info: 58. Test PeerDictionary basic functionality - pass

2016-03-14T15:16:17.083Z - info: 59. Test PeerDictionary with multiple entries. - pass
2016-03-14T15:16:17.083Z - info: 60. RESOLVED entries are removed before WAITING state entry. - pass
2016-03-14T15:16:17.084Z - info: 61. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass

2016-03-14T15:16:17.084Z - info: 62. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass
2016-03-14T15:16:17.085Z - info: 63. #ThaliPeerPoolInterface - bad enqueues - pass

2016-03-14T15:16:17.085Z - info: 64. #ThaliPeerPoolInterface - do not allow same object type - pass
2016-03-14T15:16:17.086Z - info: 65. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass
2016-03-14T15:16:17.087Z - info: 66. compareBufferArrays - pass

2016-03-14T15:16:17.087Z - info: 67. Call start twice and get error - pass
2016-03-14T15:16:17.088Z - info: 68. Start and make sure it runs - pass

2016-03-14T15:16:17.088Z - info: 69. Make sure getTimeWhenRun is right after start - pass
2016-03-14T15:16:17.089Z - info: 70. Make sure getTimeWhenRun is -1 after function is called - pass
2016-03-14T15:16:17.090Z - info: 71. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass

2016-03-14T15:16:17.090Z - info: 72. Test TransientState - pass
2016-03-14T15:16:17.091Z - info: 73. No peers and empty database - pass

2016-03-14T15:16:17.091Z - info: 74. One peer and empty DB - pass
2016-03-14T15:16:17.092Z - info: 75. One peer with _Local set behind current seq - pass

2016-03-14T15:16:17.092Z - info: 76. One peer with _Local set equal to current seq - pass
2016-03-14T15:16:17.093Z - info: 77. One peer with _Local set ahead of current seq (and no this should not happen) - pass

2016-03-14T15:16:17.094Z - info: 78. Three peers, one not in DB, one behind and one ahead - pass
2016-03-14T15:16:17.094Z - info: 79. More than maximum peers, make sure we only send maximum allowed - pass
2016-03-14T15:16:17.095Z - info: 80. two peers with empty DB, update the doc - pass

2016-03-14T15:16:17.095Z - info: 81. add doc and make sure tokens refresh when they expire - pass
2016-03-14T15:16:17.096Z - info: 82. start and stop and start and stop - pass

2016-03-14T15:16:17.096Z - info: 83. two identical starts in a row - pass
2016-03-14T15:16:17.097Z - info: 84. two different starts in a row - pass

2016-03-14T15:16:17.098Z - info: 85. two stops and a start and two stops - pass
2016-03-14T15:16:17.098Z - info: 86. we properly enqueue requests so no then needed - pass
2016-03-14T15:16:17.099Z - info: 87. test calculateSeqPointKeyId - pass

2016-03-14T15:16:17.099Z - info: 88. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass
2016-03-14T15:16:17.100Z - info: 89. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-03-14T15:16:17.100Z - info: 90. messages with invalid location or USN should be ignored - pass
2016-03-14T15:16:17.101Z - info: 91. verify that Thali-specific messages are filtered correctly - pass

2016-03-14T15:16:17.102Z - info: 92. #startListeningForAdvertisements should fail if start not called - pass
2016-03-14T15:16:17.102Z - info: 93. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-14T15:16:17.103Z - info: 94. #start should fail if called twice in a row - pass

2016-03-14T15:16:17.103Z - info: 95. should not be started after stop is called - pass
2016-03-14T15:16:17.104Z - info: 96. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass

2016-03-14T15:16:17.104Z - info: 97. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass
2016-03-14T15:16:17.105Z - info: 98. #startUpdateAdvertisingAndListening should start hosting given router object - pass

2016-03-14T15:16:17.106Z - info: 99. #stop can be called multiple times in a row - pass
2016-03-14T15:16:17.106Z - info: 100. #startListeningForAdvertisements can be called multiple times in a row - pass
2016-03-14T15:16:17.107Z - info: 101. #stopListeningForAdvertisements can be called multiple times in a row - pass

2016-03-14T15:16:17.107Z - info: 102. #stopAdvertisingAndListening can be called multiple times in a row - pass
2016-03-14T15:16:17.108Z - info: 103. functions are run from a queue in the right order - pass

2016-03-14T15:16:17.108Z - info: 104. #ThaliPeerPoolDefault - single action - pass
2016-03-14T15:16:17.109Z - info: 105. #ThaliPeerPoolDefault - multiple actions - pass

2016-03-14T15:16:17.110Z - info: 

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
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/6275440319c4f54_416__Implementation_of_ThalinotificationAction_juhanak/thali01_samsung-SM-A500FU.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/6275440319c4f54_416__Implementation_of_ThalinotificationAction_juhanak/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/6275440319c4f54_416__Implementation_of_ThalinotificationAction_juhanak/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Android task is completed. [SUCCESS]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/6275440319c4f54_416__Implementation_of_ThalinotificationAction_juhanak/thali05_LGE-LG-H815.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/6275440319c4f54_416__Implementation_of_ThalinotificationAction_juhanak/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/6275440319c4f54_416__Implementation_of_ThalinotificationAction_juhanak/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:0 
child process exited with code 0 on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/6275440319c4f54_416__Implementation_of_ThalinotificationAction_juhanak/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:0 
child process exited with code 0 on device 4325e43f 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/6275440319c4f54_416__Implementation_of_ThalinotificationAction_juhanak/thali08_samsung-SM-A300FU.md)




###iOS Logs
[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/6275440319c4f54_416__Implementation_of_ThalinotificationAction_juhanak/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/6275440319c4f54_416__Implementation_of_ThalinotificationAction_juhanak/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/6275440319c4f54_416__Implementation_of_ThalinotificationAction_juhanak/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/6275440319c4f54_416__Implementation_of_ThalinotificationAction_juhanak/iOS_IpadAir2-1.md)



#### Test 62509094aba5909 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":10}}
2016-03-11T08:58:37.981Z - info: listening on *:3000

2016-03-11T08:58:38.849Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:0

2016-03-11T08:58:39.988Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:1

2016-03-11T08:58:39.991Z - info: Required number of ios devices presented (2)

2016-03-11T08:58:39.995Z - info: Starting unit test run for platform: ios

2016-03-11T08:58:40.411Z - info: Running on ios test: 1. closeAll can close even when connections open

2016-03-11T08:58:40.785Z - info: Running on ios test: 2. closeAll with promise

2016-03-11T08:58:41.024Z - info: Running on ios test: 3. multiplex can send data

2016-03-11T08:58:41.297Z - info: Running on ios test: 4. enqueue and run in order

2016-03-11T08:58:41.730Z - info: Running on ios test: 5. enqueueAtTop and run backwards

2016-03-11T08:58:42.013Z - info: Running on ios test: 6. mix enqueue and enqueueAtTop

2016-03-11T08:58:42.384Z - info: Running on ios test: 7. queues handled independently

2016-03-11T08:58:42.490Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:2

2016-03-11T08:58:42.491Z - info: Discarding surplus device: Apple-Iphone5-1

2016-03-11T08:58:42.659Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:3

2016-03-11T08:58:42.811Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:4

2016-03-11T08:58:42.812Z - info: Required number of android devices presented (2)

2016-03-11T08:58:42.814Z - info: Starting unit test run for platform: android

2016-03-11T08:58:42.846Z - info: Running on ios test: 8. basic

2016-03-11T08:58:43.218Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:5

2016-03-11T08:58:43.219Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-11T08:58:43.271Z - info: Running on ios test: 9. another

2016-03-11T08:58:43.571Z - info: Running on ios test: 10. #startListeningForAdvertisements should fail if start not called

2016-03-11T08:58:43.986Z - info: Running on ios test: 11. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-11T08:58:44.262Z - info: Running on ios test: 12. should be able to call #stopListeningForAdvertisements many times

2016-03-11T08:58:44.443Z - debug: Socket disconnected: transport close 4 (LGE-LG-H815)

2016-03-11T08:58:44.644Z - info: Running on ios test: 13. should be able to call #startListeningForAdvertisements many times

2016-03-11T08:58:45.011Z - info: Running on ios test: 14. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-11T08:58:45.410Z - info: Running on ios test: 15. should be able to call #stopAdvertisingAndListening many times

2016-03-11T08:58:45.566Z - debug: Socket disconnected: transport close 2 (Apple-Iphone5-1)

2016-03-11T08:58:45.836Z - info: Running on ios test: 16. #start should fail if called twice in a row

2016-03-11T08:58:45.976Z - debug: Socket disconnected: transport close 5 (Apple-Iphone5s-1)

2016-03-11T08:58:46.183Z - info: Running on ios test: 17. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-11T08:58:46.511Z - info: Running on ios test: 18. does not send duplicate availability changes

2016-03-11T08:58:46.798Z - info: Running on ios test: 19. can get the network status

2016-03-11T08:58:47.151Z - info: Running on ios test: 20. wifi peer is marked unavailable if announcements stop

2016-03-11T08:58:49.116Z - info: Running on ios test: 21. can get the network status before starting

2016-03-11T08:58:50.503Z - info: Running on ios test: 22. #generatePreambleAndBeacons bad args

2016-03-11T08:58:50.981Z - info: Running on ios test: 23. #generatePreambleAndBeacons empty keys to notify

2016-03-11T08:58:51.302Z - info: Running on ios test: 24. #generatePreambleAndBeacons multiple keys to notify

2016-03-11T08:58:51.660Z - info: Running on ios test: 25. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-11T08:58:51.969Z - info: Running on ios test: 26. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-11T08:58:52.289Z - info: Running on ios test: 27. #parseBeacons expiration out of range lower

2016-03-11T08:58:52.650Z - info: Running on ios test: 28. #parseBeacons expiration out of range lower

2016-03-11T08:58:52.930Z - info: Running on ios test: 29. #parseBeacons no beacons returns null

2016-03-11T08:58:53.277Z - info: Running on ios test: 30. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-11T08:58:53.575Z - info: Running on ios test: 31. #parseBeacons addressBookCallback fails decrypt

2016-03-11T08:58:53.980Z - info: Running on ios test: 32. #parseBeacons addressBookCallback returns no matches

2016-03-11T08:58:54.358Z - info: Running on ios test: 33. #parseBeacons addressBookCallback returns spurious match

2016-03-11T08:58:54.687Z - info: Running on ios test: 34. #parseBeacons addressBookCallback returns public key

2016-03-11T08:58:57.135Z - debug: Socket disconnected: transport close 3 (samsung-SM-N910C)

2016-03-11T08:58:58.576Z - info: Running on ios test: 35. #parseBeacons with beacons both for and not for the user

2016-03-11T08:58:59.086Z - info: Running on ios test: 36. Start and stop ThaliNotificationServer

2016-03-11T08:58:59.377Z - info: Running on ios test: 37. Pass an empty array to ThaliNotificationServer.start

2016-03-11T08:58:59.645Z - info: Running on ios test: 38. Pass a string to ThaliNotificationServer.start

2016-03-11T08:58:59.883Z - info: Running on ios test: 39. Pass an empty parameter to ThaliNotificationServer.start

2016-03-11T08:59:00.167Z - info: Running on ios test: 40. Make an HTTP request to /NotificationBeacons

2016-03-11T08:59:00.557Z - info: Running on ios test: 41. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-11T08:59:00.940Z - info: Running on ios test: 42. Make an HTTP request to /NotificationBeacons before calling start

2016-03-11T08:59:01.375Z - info: Running on ios test: 43. #testThaliPeerAction - test getters

2016-03-11T08:59:01.694Z - info: Running on ios test: 44. #testThaliPeerAction - start and kill

2016-03-11T08:59:02.032Z - info: Running on ios test: 45. #testThaliPeerAction - double start

2016-03-11T08:59:02.346Z - info: Running on ios test: 46. #testThaliPeerAction - start after kill

2016-03-11T08:59:02.589Z - info: Running on ios test: 47. #testThaliPeerAction - make sure ids are unique

2016-03-11T08:59:02.815Z - info: Running on ios test: 48. Test PeerConnectionInformation basics

2016-03-11T08:59:03.040Z - info: Running on ios test: 49. Test PeerDictionary basic functionality

2016-03-11T08:59:03.356Z - info: Running on ios test: 50. Test PeerDictionary with multiple entries.

2016-03-11T08:59:04.802Z - info: Running on ios test: 51. RESOLVED entries are removed before WAITING state entry.

2016-03-11T08:59:05.545Z - info: Running on ios test: 52. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-11T08:59:06.432Z - info: Running on ios test: 53. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-11T08:59:07.148Z - info: Running on ios test: 54. #ThaliPeerPoolInterface - bad enqueues

2016-03-11T08:59:07.375Z - info: Running on ios test: 55. #ThaliPeerPoolInterface - do not allow same object type

2016-03-11T08:59:07.460Z - debug: Device presented: samsung-SM-A300FU (android) unittest socket:6

2016-03-11T08:59:07.461Z - info: Discarding surplus device: samsung-SM-A300FU

2016-03-11T08:59:07.649Z - info: Running on ios test: 56. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-11T08:59:08.029Z - info: Running on ios test: 57. compareBufferArrays

2016-03-11T08:59:08.316Z - info: Running on ios test: 58. Call start twice and get error

2016-03-11T08:59:08.365Z - debug: Socket disconnected: transport close 6 (samsung-SM-A300FU)

2016-03-11T08:59:08.649Z - info: Running on ios test: 59. Start and make sure it runs

2016-03-11T08:59:09.207Z - info: Running on ios test: 60. Make sure getTimeWhenRun is right after start

2016-03-11T08:59:09.556Z - info: Running on ios test: 61. Make sure getTimeWhenRun is -1 after function is called

2016-03-11T08:59:09.902Z - info: Running on ios test: 62. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-11T08:59:10.208Z - info: Running on ios test: 63. Test TransientState

2016-03-11T08:59:10.467Z - info: Running on ios test: 64. No peers and empty database

2016-03-11T08:59:10.947Z - info: Running on ios test: 65. One peer and empty DB

2016-03-11T08:59:11.430Z - info: Running on ios test: 66. One peer with _Local set behind current seq

2016-03-11T08:59:12.049Z - info: Running on ios test: 67. One peer with _Local set equal to current seq

2016-03-11T08:59:12.515Z - info: Running on ios test: 68. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-11T08:59:13.038Z - info: Running on ios test: 69. Three peers, one not in DB, one behind and one ahead

2016-03-11T08:59:13.589Z - info: Running on ios test: 70. More than maximum peers, make sure we only send maximum allowed

2016-03-11T08:59:14.450Z - info: Running on ios test: 71. two peers with empty DB, update the doc

2016-03-11T08:59:14.994Z - info: Running on ios test: 72. add doc and make sure tokens refresh when they expire

2016-03-11T08:59:15.882Z - info: Running on ios test: 73. start and stop and start and stop

2016-03-11T08:59:16.472Z - info: Running on ios test: 74. two identical starts in a row

2016-03-11T08:59:16.945Z - info: Running on ios test: 75. two different starts in a row

2016-03-11T08:59:17.396Z - info: Running on ios test: 76. two stops and a start and two stops

2016-03-11T08:59:17.904Z - info: Running on ios test: 77. we properly enqueue requests so no then needed

2016-03-11T08:59:18.437Z - info: Running on ios test: 78. test calculateSeqPointKeyId

2016-03-11T08:59:19.306Z - info: Running on ios test: 79. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-11T08:59:19.813Z - info: Running on ios test: 80. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-11T08:59:20.248Z - info: Running on ios test: 81. messages with invalid location or USN should be ignored

2016-03-11T08:59:20.732Z - info: Running on ios test: 82. verify that Thali-specific messages are filtered correctly

2016-03-11T08:59:21.000Z - info: Running on ios test: 83. #startListeningForAdvertisements should fail if start not called

2016-03-11T08:59:21.285Z - info: Running on ios test: 84. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-11T08:59:21.589Z - info: Running on ios test: 85. #start should fail if called twice in a row

2016-03-11T08:59:21.822Z - info: Running on ios test: 86. should not be started after stop is called

2016-03-11T08:59:22.113Z - info: Running on ios test: 87. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-11T08:59:22.357Z - info: Running on ios test: 88. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-11T08:59:22.621Z - info: Running on ios test: 89. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-11T08:59:23.093Z - info: Running on ios test: 90. #stop can be called multiple times in a row

2016-03-11T08:59:23.440Z - info: Running on ios test: 91. #startListeningForAdvertisements can be called multiple times in a row

2016-03-11T08:59:23.693Z - info: Running on ios test: 92. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-11T08:59:23.928Z - info: Running on ios test: 93. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-11T08:59:24.220Z - info: Running on ios test: 94. functions are run from a queue in the right order

2016-03-11T08:59:24.497Z - info: Running on ios test: 95. #ThaliPeerPoolDefault - single action

2016-03-11T08:59:24.700Z - info: Running on ios test: 96. #ThaliPeerPoolDefault - multiple actions

2016-03-11T08:59:24.913Z - info: Test run on ios complete

2016-03-11T08:59:24.918Z - info: 

-== UNIT TEST RESULTS ==-
2016-03-11T08:59:24.920Z - info: PLATFORM: ios
2016-03-11T08:59:24.921Z - info: RESULT: PASS
2016-03-11T08:59:24.921Z - info: 96 of 96 tests completed
2016-03-11T08:59:24.922Z - info: 96/96 passed (0 failures)
2016-03-11T08:59:24.923Z - info: --- Test Details ---


2016-03-11T08:59:24.924Z - info: 1. closeAll can close even when connections open - pass
2016-03-11T08:59:24.924Z - info: 2. closeAll with promise - pass
2016-03-11T08:59:24.925Z - info: 3. multiplex can send data - pass
2016-03-11T08:59:24.926Z - info: 4. enqueue and run in order - pass
2016-03-11T08:59:24.926Z - info: 5. enqueueAtTop and run backwards - pass
2016-03-11T08:59:24.927Z - info: 6. mix enqueue and enqueueAtTop - pass
2016-03-11T08:59:24.927Z - info: 7. queues handled independently - pass
2016-03-11T08:59:24.928Z - info: 8. basic - pass

2016-03-11T08:59:24.930Z - info: 9. another - pass

2016-03-11T08:59:24.934Z - info: 10. #startListeningForAdvertisements should fail if start not called - pass
2016-03-11T08:59:24.935Z - info: 11. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-11T08:59:24.935Z - info: 12. should be able to call #stopListeningForAdvertisements many times - pass
2016-03-11T08:59:24.936Z - info: 13. should be able to call #startListeningForAdvertisements many times - pass

2016-03-11T08:59:24.937Z - info: 14. should be able to call #startUpdateAdvertisingAndListening many times - pass
2016-03-11T08:59:24.937Z - info: 15. should be able to call #stopAdvertisingAndListening many times - pass
2016-03-11T08:59:24.938Z - info: 16. #start should fail if called twice in a row - pass
2016-03-11T08:59:24.939Z - info: 17. does not emit duplicate discoveryAdvertisingStateUpdate - pass
2016-03-11T08:59:24.939Z - info: 18. does not send duplicate availability changes - pass
2016-03-11T08:59:24.940Z - info: 19. can get the network status - pass
2016-03-11T08:59:24.940Z - info: 20. wifi peer is marked unavailable if announcements stop - pass

2016-03-11T08:59:24.941Z - info: 21. can get the network status before starting - pass
2016-03-11T08:59:24.942Z - info: 22. #generatePreambleAndBeacons bad args - pass

2016-03-11T08:59:24.942Z - info: 23. #generatePreambleAndBeacons empty keys to notify - pass
2016-03-11T08:59:24.943Z - info: 24. #generatePreambleAndBeacons multiple keys to notify - pass

2016-03-11T08:59:24.944Z - info: 25. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass

2016-03-11T08:59:24.944Z - info: 26. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass

2016-03-11T08:59:24.952Z - info: 27. #parseBeacons expiration out of range lower - pass

2016-03-11T08:59:24.953Z - info: 28. #parseBeacons expiration out of range lower - pass
2016-03-11T08:59:24.954Z - info: 29. #parseBeacons no beacons returns null - pass

2016-03-11T08:59:24.954Z - info: 30. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass
2016-03-11T08:59:24.955Z - info: 31. #parseBeacons addressBookCallback fails decrypt - pass
2016-03-11T08:59:24.956Z - info: 32. #parseBeacons addressBookCallback returns no matches - pass
2016-03-11T08:59:24.956Z - info: 33. #parseBeacons addressBookCallback returns spurious match - pass
2016-03-11T08:59:24.957Z - info: 34. #parseBeacons addressBookCallback returns public key - pass

2016-03-11T08:59:24.958Z - info: 35. #parseBeacons with beacons both for and not for the user - pass
2016-03-11T08:59:24.958Z - info: 36. Start and stop ThaliNotificationServer - pass

2016-03-11T08:59:24.959Z - info: 37. Pass an empty array to ThaliNotificationServer.start - pass
2016-03-11T08:59:24.960Z - info: 38. Pass a string to ThaliNotificationServer.start - pass

2016-03-11T08:59:24.960Z - info: 39. Pass an empty parameter to ThaliNotificationServer.start - pass
2016-03-11T08:59:24.961Z - info: 40. Make an HTTP request to /NotificationBeacons - pass

2016-03-11T08:59:24.961Z - info: 41. Make an HTTP request to /NotificationBeacons (no keys) - pass
2016-03-11T08:59:24.962Z - info: 42. Make an HTTP request to /NotificationBeacons before calling start - pass
2016-03-11T08:59:24.963Z - info: 43. #testThaliPeerAction - test getters - pass
2016-03-11T08:59:24.963Z - info: 44. #testThaliPeerAction - start and kill - pass
2016-03-11T08:59:24.964Z - info: 45. #testThaliPeerAction - double start - pass
2016-03-11T08:59:24.964Z - info: 46. #testThaliPeerAction - start after kill - pass
2016-03-11T08:59:24.965Z - info: 47. #testThaliPeerAction - make sure ids are unique - pass
2016-03-11T08:59:24.966Z - info: 48. Test PeerConnectionInformation basics - pass
2016-03-11T08:59:24.966Z - info: 49. Test PeerDictionary basic functionality - pass
2016-03-11T08:59:24.967Z - info: 50. Test PeerDictionary with multiple entries. - pass
2016-03-11T08:59:24.968Z - info: 51. RESOLVED entries are removed before WAITING state entry. - pass
2016-03-11T08:59:24.968Z - info: 52. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass
2016-03-11T08:59:24.969Z - info: 53. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass

2016-03-11T08:59:24.970Z - info: 54. #ThaliPeerPoolInterface - bad enqueues - pass

2016-03-11T08:59:24.970Z - info: 55. #ThaliPeerPoolInterface - do not allow same object type - pass
2016-03-11T08:59:24.979Z - info: 56. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass
2016-03-11T08:59:24.979Z - info: 57. compareBufferArrays - pass
2016-03-11T08:59:24.980Z - info: 58. Call start twice and get error - pass

2016-03-11T08:59:24.981Z - info: 59. Start and make sure it runs - pass
2016-03-11T08:59:24.981Z - info: 60. Make sure getTimeWhenRun is right after start - pass

2016-03-11T08:59:24.982Z - info: 61. Make sure getTimeWhenRun is -1 after function is called - pass
2016-03-11T08:59:24.983Z - info: 62. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass

2016-03-11T08:59:24.983Z - info: 63. Test TransientState - pass

2016-03-11T08:59:24.984Z - info: 64. No peers and empty database - pass
2016-03-11T08:59:24.985Z - info: 65. One peer and empty DB - pass

2016-03-11T08:59:24.985Z - info: 66. One peer with _Local set behind current seq - pass
2016-03-11T08:59:24.986Z - info: 67. One peer with _Local set equal to current seq - pass

2016-03-11T08:59:24.987Z - info: 68. One peer with _Local set ahead of current seq (and no this should not happen) - pass

2016-03-11T08:59:24.987Z - info: 69. Three peers, one not in DB, one behind and one ahead - pass
2016-03-11T08:59:24.988Z - info: 70. More than maximum peers, make sure we only send maximum allowed - pass

2016-03-11T08:59:24.989Z - info: 71. two peers with empty DB, update the doc - pass
2016-03-11T08:59:24.989Z - info: 72. add doc and make sure tokens refresh when they expire - pass

2016-03-11T08:59:24.990Z - info: 73. start and stop and start and stop - pass

2016-03-11T08:59:24.991Z - info: 74. two identical starts in a row - pass
2016-03-11T08:59:24.991Z - info: 75. two different starts in a row - pass

2016-03-11T08:59:24.992Z - info: 76. two stops and a start and two stops - pass
2016-03-11T08:59:24.992Z - info: 77. we properly enqueue requests so no then needed - pass

2016-03-11T08:59:24.993Z - info: 78. test calculateSeqPointKeyId - pass
2016-03-11T08:59:24.994Z - info: 79. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass

2016-03-11T08:59:24.994Z - info: 80. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-03-11T08:59:24.995Z - info: 81. messages with invalid location or USN should be ignored - pass
2016-03-11T08:59:24.995Z - info: 82. verify that Thali-specific messages are filtered correctly - pass

2016-03-11T08:59:24.996Z - info: 83. #startListeningForAdvertisements should fail if start not called - pass
2016-03-11T08:59:24.997Z - info: 84. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-11T08:59:24.997Z - info: 85. #start should fail if called twice in a row - pass

2016-03-11T08:59:24.998Z - info: 86. should not be started after stop is called - pass
2016-03-11T08:59:24.999Z - info: 87. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass

2016-03-11T08:59:24.999Z - info: 88. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass
2016-03-11T08:59:25.000Z - info: 89. #startUpdateAdvertisingAndListening should start hosting given router object - pass

2016-03-11T08:59:25.000Z - info: 90. #stop can be called multiple times in a row - pass
2016-03-11T08:59:25.001Z - info: 91. #startListeningForAdvertisements can be called multiple times in a row - pass

2016-03-11T08:59:25.002Z - info: 92. #stopListeningForAdvertisements can be called multiple times in a row - pass

2016-03-11T08:59:25.002Z - info: 93. #stopAdvertisingAndListening can be called multiple times in a row - pass
2016-03-11T08:59:25.003Z - info: 94. functions are run from a queue in the right order - pass

2016-03-11T08:59:25.004Z - info: 95. #ThaliPeerPoolDefault - single action - pass
2016-03-11T08:59:25.004Z - info: 96. #ThaliPeerPoolDefault - multiple actions - pass

2016-03-11T08:59:25.005Z - info: 

-== END ==-

2016-03-11T08:59:27.495Z - debug: Socket disconnected: transport close 0 (Apple-IpadAir2-1)

2016-03-11T08:59:28.089Z - debug: Socket disconnected: transport close 1 (Apple-Iphone6-1)


 
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
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62509094aba5909_Make_CI_build_and_unit_tests_pass_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/62509094aba5909_Make_CI_build_and_unit_tests_pass_vjrantal/thali02_LGE-LG-D722.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/62509094aba5909_Make_CI_build_and_unit_tests_pass_vjrantal/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/62509094aba5909_Make_CI_build_and_unit_tests_pass_vjrantal/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:0 
child process exited with code 0 on device LGH8153b36be34 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/62509094aba5909_Make_CI_build_and_unit_tests_pass_vjrantal/thali05_LGE-LG-H815.md)

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
[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/62509094aba5909_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_HTC-HTC One M8s.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62509094aba5909_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_samsung-SM-A300FU.md)

####Node name: thali07
Console output:
```
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:0 
child process exited with code 0 on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62509094aba5909_Make_CI_build_and_unit_tests_pass_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:0 
child process exited with code 0 on device 4325e43f 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62509094aba5909_Make_CI_build_and_unit_tests_pass_vjrantal/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 09a9416e0297d102 app:com.test.thalitest code:0 
child process exited with code 0 on device 09a9416e0297d102 
Android task is completed. [FAILED]
```
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/62509094aba5909_Make_CI_build_and_unit_tests_pass_vjrantal/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/62509094aba5909_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/62509094aba5909_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/62509094aba5909_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/62509094aba5909_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone6-1.md)



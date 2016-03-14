#### Test 625090944a5472b Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":10}}
2016-03-14T07:53:15.032Z - info: listening on *:3000

2016-03-14T07:53:15.749Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:1

2016-03-14T07:53:15.927Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:2

2016-03-14T07:53:16.460Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:3

2016-03-14T07:53:16.462Z - info: Required number of ios devices presented (2)

2016-03-14T07:53:16.466Z - info: Starting unit test run for platform: ios

2016-03-14T07:53:16.540Z - debug: Device presented: samsung-SM-A500FU (android) unittest socket:4

2016-03-14T07:53:16.542Z - info: Required number of android devices presented (2)

2016-03-14T07:53:16.543Z - info: Starting unit test run for platform: android

2016-03-14T07:53:17.008Z - info: Running on ios test: 1. closeAll can close even when connections open

2016-03-14T07:53:17.342Z - info: Running on ios test: 2. closeAll with promise

2016-03-14T07:53:17.590Z - info: Running on ios test: 3. multiplex can send data

2016-03-14T07:53:17.917Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:0

2016-03-14T07:53:17.918Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-14T07:53:17.931Z - info: Running on ios test: 4. enqueue and run in order

2016-03-14T07:53:18.439Z - info: Running on ios test: 5. enqueueAtTop and run backwards

2016-03-14T07:53:18.538Z - debug: Socket disconnected: transport close 4 (samsung-SM-A500FU)

2016-03-14T07:53:18.743Z - info: Running on ios test: 6. mix enqueue and enqueueAtTop

2016-03-14T07:53:19.136Z - info: Running on ios test: 7. queues handled independently

2016-03-14T07:53:19.486Z - info: Running on ios test: 8. basic

2016-03-14T07:53:19.711Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:5

2016-03-14T07:53:19.712Z - info: Discarding surplus device: LGE-LG-H815

2016-03-14T07:53:19.803Z - info: Running on ios test: 9. another

2016-03-14T07:53:20.205Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:6

2016-03-14T07:53:20.206Z - info: Discarding surplus device: Apple-IpadAir2-1

2016-03-14T07:53:20.377Z - info: Running on ios test: 10. #startListeningForAdvertisements should fail if start not called

2016-03-14T07:53:20.688Z - info: Running on ios test: 11. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-14T07:53:20.738Z - debug: Socket disconnected: transport close 0 (Apple-Iphone5s-1)

2016-03-14T07:53:20.898Z - debug: Socket disconnected: transport close 5 (LGE-LG-H815)

2016-03-14T07:53:21.009Z - info: Running on ios test: 12. should be able to call #stopListeningForAdvertisements many times

2016-03-14T07:53:21.334Z - info: Running on ios test: 13. should be able to call #startListeningForAdvertisements many times

2016-03-14T07:53:21.708Z - info: Running on ios test: 14. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-14T07:53:22.101Z - info: Running on ios test: 15. should be able to call #stopAdvertisingAndListening many times

2016-03-14T07:53:22.432Z - info: Running on ios test: 16. #start should fail if called twice in a row

2016-03-14T07:53:22.696Z - info: Running on ios test: 17. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-14T07:53:22.848Z - debug: Socket disconnected: transport close 6 (Apple-IpadAir2-1)

2016-03-14T07:53:22.994Z - info: Running on ios test: 18. does not send duplicate availability changes

2016-03-14T07:53:23.248Z - info: Running on ios test: 19. can get the network status

2016-03-14T07:53:23.538Z - info: Running on ios test: 20. wifi peer is marked unavailable if announcements stop

2016-03-14T07:53:24.858Z - info: Running on ios test: 21. can get the network status before starting

2016-03-14T07:53:25.095Z - info: Running on ios test: 22. #generatePreambleAndBeacons bad args

2016-03-14T07:53:25.362Z - info: Running on ios test: 23. #generatePreambleAndBeacons empty keys to notify

2016-03-14T07:53:25.615Z - info: Running on ios test: 24. #generatePreambleAndBeacons multiple keys to notify

2016-03-14T07:53:26.160Z - info: Running on ios test: 25. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-14T07:53:26.416Z - info: Running on ios test: 26. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-14T07:53:26.723Z - info: Running on ios test: 27. #parseBeacons expiration out of range lower

2016-03-14T07:53:26.987Z - info: Running on ios test: 28. #parseBeacons expiration out of range lower

2016-03-14T07:53:27.246Z - info: Running on ios test: 29. #parseBeacons no beacons returns null

2016-03-14T07:53:27.508Z - info: Running on ios test: 30. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-14T07:53:28.150Z - info: Running on ios test: 31. #parseBeacons addressBookCallback fails decrypt

2016-03-14T07:53:28.564Z - info: Running on ios test: 32. #parseBeacons addressBookCallback returns no matches

2016-03-14T07:53:28.921Z - info: Running on ios test: 33. #parseBeacons addressBookCallback returns spurious match

2016-03-14T07:53:29.448Z - info: Running on ios test: 34. #parseBeacons addressBookCallback returns public key

2016-03-14T07:53:29.868Z - info: Running on ios test: 35. #parseBeacons with beacons both for and not for the user

2016-03-14T07:53:30.252Z - info: Running on ios test: 36. Start and stop ThaliNotificationServer

2016-03-14T07:53:30.644Z - info: Running on ios test: 37. Pass an empty array to ThaliNotificationServer.start

2016-03-14T07:53:31.012Z - info: Running on ios test: 38. Pass a string to ThaliNotificationServer.start

2016-03-14T07:53:31.021Z - debug: Socket disconnected: transport close 1 (samsung-SM-N910C)

2016-03-14T07:53:31.353Z - info: Running on ios test: 39. Pass an empty parameter to ThaliNotificationServer.start

2016-03-14T07:53:31.829Z - info: Running on ios test: 40. Make an HTTP request to /NotificationBeacons

2016-03-14T07:53:32.356Z - info: Running on ios test: 41. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-14T07:53:32.747Z - info: Running on ios test: 42. Make an HTTP request to /NotificationBeacons before calling start

2016-03-14T07:53:33.078Z - info: Running on ios test: 43. #testThaliPeerAction - test getters

2016-03-14T07:53:33.352Z - info: Running on ios test: 44. #testThaliPeerAction - start and kill

2016-03-14T07:53:33.629Z - info: Running on ios test: 45. #testThaliPeerAction - double start

2016-03-14T07:53:33.917Z - info: Running on ios test: 46. #testThaliPeerAction - start after kill

2016-03-14T07:53:34.209Z - info: Running on ios test: 47. #testThaliPeerAction - make sure ids are unique

2016-03-14T07:53:34.457Z - info: Running on ios test: 48. Test PeerConnectionInformation basics

2016-03-14T07:53:34.757Z - info: Running on ios test: 49. Test PeerDictionary basic functionality

2016-03-14T07:53:35.094Z - info: Running on ios test: 50. Test PeerDictionary with multiple entries.

2016-03-14T07:53:37.362Z - info: Running on ios test: 51. RESOLVED entries are removed before WAITING state entry.

2016-03-14T07:53:38.599Z - info: Running on ios test: 52. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-14T07:53:39.818Z - info: Running on ios test: 53. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-14T07:53:41.154Z - info: Running on ios test: 54. #ThaliPeerPoolInterface - bad enqueues

2016-03-14T07:53:41.505Z - info: Running on ios test: 55. #ThaliPeerPoolInterface - do not allow same object type

2016-03-14T07:53:41.798Z - info: Running on ios test: 56. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-14T07:53:42.112Z - info: Running on ios test: 57. compareBufferArrays

2016-03-14T07:53:42.453Z - info: Running on ios test: 58. Call start twice and get error

2016-03-14T07:53:42.691Z - info: Running on ios test: 59. Start and make sure it runs

2016-03-14T07:53:42.959Z - info: Running on ios test: 60. Make sure getTimeWhenRun is right after start

2016-03-14T07:53:43.249Z - info: Running on ios test: 61. Make sure getTimeWhenRun is -1 after function is called

2016-03-14T07:53:43.498Z - info: Running on ios test: 62. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-14T07:53:43.805Z - info: Running on ios test: 63. Test TransientState

2016-03-14T07:53:44.073Z - info: Running on ios test: 64. No peers and empty database

2016-03-14T07:53:44.559Z - info: Running on ios test: 65. One peer and empty DB

2016-03-14T07:53:45.098Z - info: Running on ios test: 66. One peer with _Local set behind current seq

2016-03-14T07:53:45.699Z - info: Running on ios test: 67. One peer with _Local set equal to current seq

2016-03-14T07:53:46.296Z - info: Running on ios test: 68. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-14T07:53:49.571Z - info: Running on ios test: 69. Three peers, one not in DB, one behind and one ahead

2016-03-14T07:53:51.610Z - info: Running on ios test: 70. More than maximum peers, make sure we only send maximum allowed

2016-03-14T07:53:53.080Z - info: Running on ios test: 71. two peers with empty DB, update the doc

2016-03-14T07:53:53.722Z - info: Running on ios test: 72. add doc and make sure tokens refresh when they expire

2016-03-14T07:53:54.982Z - info: Running on ios test: 73. start and stop and start and stop

2016-03-14T07:53:55.549Z - info: Running on ios test: 74. two identical starts in a row

2016-03-14T07:53:56.093Z - info: Running on ios test: 75. two different starts in a row

2016-03-14T07:53:56.618Z - info: Running on ios test: 76. two stops and a start and two stops

2016-03-14T07:53:57.152Z - info: Running on ios test: 77. we properly enqueue requests so no then needed

2016-03-14T07:53:57.697Z - info: Running on ios test: 78. test calculateSeqPointKeyId

2016-03-14T07:53:58.014Z - info: Running on ios test: 79. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-14T07:53:58.327Z - info: Running on ios test: 80. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-14T07:53:58.726Z - info: Running on ios test: 81. messages with invalid location or USN should be ignored

2016-03-14T07:53:59.015Z - info: Running on ios test: 82. verify that Thali-specific messages are filtered correctly

2016-03-14T07:53:59.281Z - info: Running on ios test: 83. #startListeningForAdvertisements should fail if start not called

2016-03-14T07:53:59.553Z - info: Running on ios test: 84. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-14T07:53:59.809Z - info: Running on ios test: 85. #start should fail if called twice in a row

2016-03-14T07:54:00.103Z - info: Running on ios test: 86. should not be started after stop is called

2016-03-14T07:54:00.403Z - info: Running on ios test: 87. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-14T07:54:00.683Z - info: Running on ios test: 88. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-14T07:54:00.988Z - info: Running on ios test: 89. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-14T07:54:01.357Z - info: Running on ios test: 90. #stop can be called multiple times in a row

2016-03-14T07:54:01.620Z - info: Running on ios test: 91. #startListeningForAdvertisements can be called multiple times in a row

2016-03-14T07:54:01.882Z - info: Running on ios test: 92. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-14T07:54:02.204Z - info: Running on ios test: 93. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-14T07:54:02.482Z - info: Running on ios test: 94. functions are run from a queue in the right order

2016-03-14T07:54:02.816Z - info: Running on ios test: 95. #ThaliPeerPoolDefault - single action

2016-03-14T07:54:03.068Z - info: Running on ios test: 96. #ThaliPeerPoolDefault - multiple actions

2016-03-14T07:54:03.379Z - info: Test run on ios complete

2016-03-14T07:54:03.384Z - info: 

-== UNIT TEST RESULTS ==-
2016-03-14T07:54:03.386Z - info: PLATFORM: ios
2016-03-14T07:54:03.387Z - info: RESULT: PASS
2016-03-14T07:54:03.388Z - info: 96 of 96 tests completed
2016-03-14T07:54:03.389Z - info: 96/96 passed (0 failures)
2016-03-14T07:54:03.390Z - info: --- Test Details ---


2016-03-14T07:54:03.391Z - info: 1. closeAll can close even when connections open - pass
2016-03-14T07:54:03.392Z - info: 2. closeAll with promise - pass
2016-03-14T07:54:03.392Z - info: 3. multiplex can send data - pass
2016-03-14T07:54:03.393Z - info: 4. enqueue and run in order - pass
2016-03-14T07:54:03.394Z - info: 5. enqueueAtTop and run backwards - pass
2016-03-14T07:54:03.394Z - info: 6. mix enqueue and enqueueAtTop - pass
2016-03-14T07:54:03.395Z - info: 7. queues handled independently - pass
2016-03-14T07:54:03.396Z - info: 8. basic - pass

2016-03-14T07:54:03.398Z - info: 9. another - pass

2016-03-14T07:54:03.402Z - info: 10. #startListeningForAdvertisements should fail if start not called - pass

2016-03-14T07:54:03.403Z - info: 11. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-14T07:54:03.404Z - info: 12. should be able to call #stopListeningForAdvertisements many times - pass
2016-03-14T07:54:03.405Z - info: 13. should be able to call #startListeningForAdvertisements many times - pass
2016-03-14T07:54:03.406Z - info: 14. should be able to call #startUpdateAdvertisingAndListening many times - pass
2016-03-14T07:54:03.407Z - info: 15. should be able to call #stopAdvertisingAndListening many times - pass
2016-03-14T07:54:03.407Z - info: 16. #start should fail if called twice in a row - pass

2016-03-14T07:54:03.408Z - info: 17. does not emit duplicate discoveryAdvertisingStateUpdate - pass
2016-03-14T07:54:03.409Z - info: 18. does not send duplicate availability changes - pass

2016-03-14T07:54:03.410Z - info: 19. can get the network status - pass

2016-03-14T07:54:03.411Z - info: 20. wifi peer is marked unavailable if announcements stop - pass

2016-03-14T07:54:03.412Z - info: 21. can get the network status before starting - pass
2016-03-14T07:54:03.413Z - info: 22. #generatePreambleAndBeacons bad args - pass

2016-03-14T07:54:03.414Z - info: 23. #generatePreambleAndBeacons empty keys to notify - pass

2016-03-14T07:54:03.414Z - info: 24. #generatePreambleAndBeacons multiple keys to notify - pass

2016-03-14T07:54:03.415Z - info: 25. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass
2016-03-14T07:54:03.416Z - info: 26. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass
2016-03-14T07:54:03.417Z - info: 27. #parseBeacons expiration out of range lower - pass
2016-03-14T07:54:03.418Z - info: 28. #parseBeacons expiration out of range lower - pass

2016-03-14T07:54:03.419Z - info: 29. #parseBeacons no beacons returns null - pass

2016-03-14T07:54:03.420Z - info: 30. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass
2016-03-14T07:54:03.421Z - info: 31. #parseBeacons addressBookCallback fails decrypt - pass

2016-03-14T07:54:03.421Z - info: 32. #parseBeacons addressBookCallback returns no matches - pass

2016-03-14T07:54:03.422Z - info: 33. #parseBeacons addressBookCallback returns spurious match - pass
2016-03-14T07:54:03.423Z - info: 34. #parseBeacons addressBookCallback returns public key - pass
2016-03-14T07:54:03.424Z - info: 35. #parseBeacons with beacons both for and not for the user - pass
2016-03-14T07:54:03.425Z - info: 36. Start and stop ThaliNotificationServer - pass
2016-03-14T07:54:03.425Z - info: 37. Pass an empty array to ThaliNotificationServer.start - pass
2016-03-14T07:54:03.426Z - info: 38. Pass a string to ThaliNotificationServer.start - pass
2016-03-14T07:54:03.426Z - info: 39. Pass an empty parameter to ThaliNotificationServer.start - pass
2016-03-14T07:54:03.427Z - info: 40. Make an HTTP request to /NotificationBeacons - pass
2016-03-14T07:54:03.428Z - info: 41. Make an HTTP request to /NotificationBeacons (no keys) - pass
2016-03-14T07:54:03.428Z - info: 42. Make an HTTP request to /NotificationBeacons before calling start - pass
2016-03-14T07:54:03.429Z - info: 43. #testThaliPeerAction - test getters - pass
2016-03-14T07:54:03.430Z - info: 44. #testThaliPeerAction - start and kill - pass

2016-03-14T07:54:03.431Z - info: 45. #testThaliPeerAction - double start - pass
2016-03-14T07:54:03.431Z - info: 46. #testThaliPeerAction - start after kill - pass

2016-03-14T07:54:03.432Z - info: 47. #testThaliPeerAction - make sure ids are unique - pass

2016-03-14T07:54:03.433Z - info: 48. Test PeerConnectionInformation basics - pass
2016-03-14T07:54:03.434Z - info: 49. Test PeerDictionary basic functionality - pass

2016-03-14T07:54:03.435Z - info: 50. Test PeerDictionary with multiple entries. - pass
2016-03-14T07:54:03.436Z - info: 51. RESOLVED entries are removed before WAITING state entry. - pass
2016-03-14T07:54:03.437Z - info: 52. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass
2016-03-14T07:54:03.437Z - info: 53. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass
2016-03-14T07:54:03.438Z - info: 54. #ThaliPeerPoolInterface - bad enqueues - pass

2016-03-14T07:54:03.439Z - info: 55. #ThaliPeerPoolInterface - do not allow same object type - pass

2016-03-14T07:54:03.448Z - info: 56. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass

2016-03-14T07:54:03.449Z - info: 57. compareBufferArrays - pass

2016-03-14T07:54:03.450Z - info: 58. Call start twice and get error - pass

2016-03-14T07:54:03.450Z - info: 59. Start and make sure it runs - pass
2016-03-14T07:54:03.451Z - info: 60. Make sure getTimeWhenRun is right after start - pass

2016-03-14T07:54:03.452Z - info: 61. Make sure getTimeWhenRun is -1 after function is called - pass

2016-03-14T07:54:03.453Z - info: 62. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass

2016-03-14T07:54:03.454Z - info: 63. Test TransientState - pass

2016-03-14T07:54:03.455Z - info: 64. No peers and empty database - pass

2016-03-14T07:54:03.456Z - info: 65. One peer and empty DB - pass

2016-03-14T07:54:03.457Z - info: 66. One peer with _Local set behind current seq - pass

2016-03-14T07:54:03.458Z - info: 67. One peer with _Local set equal to current seq - pass
2016-03-14T07:54:03.459Z - info: 68. One peer with _Local set ahead of current seq (and no this should not happen) - pass

2016-03-14T07:54:03.460Z - info: 69. Three peers, one not in DB, one behind and one ahead - pass

2016-03-14T07:54:03.461Z - info: 70. More than maximum peers, make sure we only send maximum allowed - pass

2016-03-14T07:54:03.462Z - info: 71. two peers with empty DB, update the doc - pass

2016-03-14T07:54:03.462Z - info: 72. add doc and make sure tokens refresh when they expire - pass

2016-03-14T07:54:03.463Z - info: 73. start and stop and start and stop - pass

2016-03-14T07:54:03.464Z - info: 74. two identical starts in a row - pass
2016-03-14T07:54:03.465Z - info: 75. two different starts in a row - pass

2016-03-14T07:54:03.466Z - info: 76. two stops and a start and two stops - pass

2016-03-14T07:54:03.467Z - info: 77. we properly enqueue requests so no then needed - pass

2016-03-14T07:54:03.468Z - info: 78. test calculateSeqPointKeyId - pass

2016-03-14T07:54:03.469Z - info: 79. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass

2016-03-14T07:54:03.470Z - info: 80. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-03-14T07:54:03.471Z - info: 81. messages with invalid location or USN should be ignored - pass

2016-03-14T07:54:03.472Z - info: 82. verify that Thali-specific messages are filtered correctly - pass

2016-03-14T07:54:03.473Z - info: 83. #startListeningForAdvertisements should fail if start not called - pass

2016-03-14T07:54:03.474Z - info: 84. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-14T07:54:03.475Z - info: 85. #start should fail if called twice in a row - pass
2016-03-14T07:54:03.476Z - info: 86. should not be started after stop is called - pass

2016-03-14T07:54:03.477Z - info: 87. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass

2016-03-14T07:54:03.478Z - info: 88. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass

2016-03-14T07:54:03.479Z - info: 89. #startUpdateAdvertisingAndListening should start hosting given router object - pass

2016-03-14T07:54:03.480Z - info: 90. #stop can be called multiple times in a row - pass

2016-03-14T07:54:03.480Z - info: 91. #startListeningForAdvertisements can be called multiple times in a row - pass

2016-03-14T07:54:03.481Z - info: 92. #stopListeningForAdvertisements can be called multiple times in a row - pass
2016-03-14T07:54:03.482Z - info: 93. #stopAdvertisingAndListening can be called multiple times in a row - pass

2016-03-14T07:54:03.483Z - info: 94. functions are run from a queue in the right order - pass

2016-03-14T07:54:03.484Z - info: 95. #ThaliPeerPoolDefault - single action - pass

2016-03-14T07:54:03.485Z - info: 96. #ThaliPeerPoolDefault - multiple actions - pass

2016-03-14T07:54:03.486Z - info: 

-== END ==-

2016-03-14T07:54:06.016Z - debug: Socket disconnected: transport close 3 (Apple-Iphone6-1)

2016-03-14T07:54:07.039Z - debug: Socket disconnected: transport close 2 (Apple-Iphone5-1)


 
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
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/625090944a5472b_Make_CI_build_and_unit_tests_pass_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/625090944a5472b_Make_CI_build_and_unit_tests_pass_vjrantal/thali02_LGE-LG-D722.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/625090944a5472b_Make_CI_build_and_unit_tests_pass_vjrantal/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on ZX1C223JKW 
Android task is completed. [SUCCESS]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/625090944a5472b_Make_CI_build_and_unit_tests_pass_vjrantal/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Android task is completed. [SUCCESS]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/625090944a5472b_Make_CI_build_and_unit_tests_pass_vjrantal/thali05_LGE-LG-H815.md)

####Node name: thali06
Console output:
```
STOP log received from  7970f88c Test has  FAILED
STOP log received from  FA55PYS00566 Test has  FAILED
Device test finished on 7970f88c 
Device test finished on FA55PYS00566 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/625090944a5472b_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/625090944a5472b_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
STOP log received from  4db5c8cc Test has  FAILED
Device test finished on 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/625090944a5472b_Make_CI_build_and_unit_tests_pass_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
STOP log received from  4325e43f Test has  FAILED
Device test finished on 4325e43f 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/625090944a5472b_Make_CI_build_and_unit_tests_pass_vjrantal/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 09a9416e0297d102 app:com.test.thalitest code:0 
child process exited with code 0 on device 09a9416e0297d102 
Android task is completed. [FAILED]
```
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/625090944a5472b_Make_CI_build_and_unit_tests_pass_vjrantal/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/625090944a5472b_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/625090944a5472b_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/625090944a5472b_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/625090944a5472b_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_IpadAir2-1.md)



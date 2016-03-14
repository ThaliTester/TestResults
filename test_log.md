#### Test 62509094588eeb1 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":8}}
2016-03-14T12:42:17.966Z - info: listening on *:3000

2016-03-14T12:42:20.655Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:1

2016-03-14T12:42:20.727Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:2

2016-03-14T12:42:20.997Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:3

2016-03-14T12:42:20.999Z - info: Required number of android devices presented (2)

2016-03-14T12:42:21.002Z - info: Starting unit test run for platform: android

2016-03-14T12:42:21.712Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:4

2016-03-14T12:42:21.713Z - info: Required number of ios devices presented (2)

2016-03-14T12:42:21.715Z - info: Starting unit test run for platform: ios

2016-03-14T12:42:21.801Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:5

2016-03-14T12:42:21.802Z - info: Discarding surplus device: Apple-Iphone6-1

2016-03-14T12:42:22.228Z - info: Running on ios test: 1. closeAll can close even when connections open

2016-03-14T12:42:22.609Z - info: Running on ios test: 2. closeAll with promise

2016-03-14T12:42:22.916Z - info: Running on ios test: 3. multiplex can send data

2016-03-14T12:42:22.994Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:0

2016-03-14T12:42:22.995Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-14T12:42:23.131Z - debug: Socket disconnected: transport close 1 (LGE-LG-H815)

2016-03-14T12:42:24.297Z - debug: Socket disconnected: transport close 5 (Apple-Iphone6-1)

2016-03-14T12:42:25.502Z - debug: Socket disconnected: transport close 0 (Apple-Iphone5s-1)

2016-03-14T12:42:33.590Z - info: Running on ios test: 4. enqueue and run in order

2016-03-14T12:42:34.296Z - info: Running on ios test: 5. enqueueAtTop and run backwards

2016-03-14T12:42:34.618Z - info: Running on ios test: 6. mix enqueue and enqueueAtTop

2016-03-14T12:42:35.078Z - info: Running on ios test: 7. queues handled independently

2016-03-14T12:42:35.458Z - info: Running on ios test: 8. basic

2016-03-14T12:42:35.643Z - debug: Socket disconnected: transport close 3 (samsung-SM-N910C)

2016-03-14T12:42:35.840Z - info: Running on ios test: 9. another

2016-03-14T12:42:36.303Z - info: Running on ios test: 10. #startListeningForAdvertisements should fail if start not called

2016-03-14T12:42:36.781Z - info: Running on ios test: 11. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-14T12:42:37.197Z - info: Running on ios test: 12. should be able to call #stopListeningForAdvertisements many times

2016-03-14T12:42:37.559Z - info: Running on ios test: 13. should be able to call #startListeningForAdvertisements many times

2016-03-14T12:42:37.865Z - info: Running on ios test: 14. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-14T12:42:38.158Z - info: Running on ios test: 15. should be able to call #stopAdvertisingAndListening many times

2016-03-14T12:42:38.506Z - info: Running on ios test: 16. #start should fail if called twice in a row

2016-03-14T12:42:38.808Z - info: Running on ios test: 17. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-14T12:42:39.151Z - info: Running on ios test: 18. does not send duplicate availability changes

2016-03-14T12:42:39.426Z - info: Running on ios test: 19. can get the network status

2016-03-14T12:42:40.204Z - info: Running on ios test: 20. wifi peer is marked unavailable if announcements stop

2016-03-14T12:42:41.808Z - info: Running on ios test: 21. can get the network status before starting

2016-03-14T12:42:42.074Z - info: Running on ios test: 22. #generatePreambleAndBeacons bad args

2016-03-14T12:42:42.316Z - info: Running on ios test: 23. #generatePreambleAndBeacons empty keys to notify

2016-03-14T12:42:42.651Z - info: Running on ios test: 24. #generatePreambleAndBeacons multiple keys to notify

2016-03-14T12:42:43.048Z - info: Running on ios test: 25. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-14T12:42:43.388Z - info: Running on ios test: 26. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-14T12:42:43.716Z - info: Running on ios test: 27. #parseBeacons expiration out of range lower

2016-03-14T12:42:44.073Z - info: Running on ios test: 28. #parseBeacons expiration out of range lower

2016-03-14T12:42:44.412Z - info: Running on ios test: 29. #parseBeacons no beacons returns null

2016-03-14T12:42:44.903Z - info: Running on ios test: 30. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-14T12:42:45.318Z - info: Running on ios test: 31. #parseBeacons addressBookCallback fails decrypt

2016-03-14T12:42:45.808Z - info: Running on ios test: 32. #parseBeacons addressBookCallback returns no matches

2016-03-14T12:42:46.202Z - info: Running on ios test: 33. #parseBeacons addressBookCallback returns spurious match

2016-03-14T12:42:46.705Z - info: Running on ios test: 34. #parseBeacons addressBookCallback returns public key

2016-03-14T12:42:47.244Z - info: Running on ios test: 35. #parseBeacons with beacons both for and not for the user

2016-03-14T12:42:47.902Z - info: Running on ios test: 36. Start and stop ThaliNotificationServer

2016-03-14T12:42:48.386Z - info: Running on ios test: 37. Pass an empty array to ThaliNotificationServer.start

2016-03-14T12:42:48.758Z - info: Running on ios test: 38. Pass a string to ThaliNotificationServer.start

2016-03-14T12:42:49.096Z - info: Running on ios test: 39. Pass an empty parameter to ThaliNotificationServer.start

2016-03-14T12:42:49.450Z - info: Running on ios test: 40. Make an HTTP request to /NotificationBeacons

2016-03-14T12:42:50.046Z - info: Running on ios test: 41. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-14T12:42:50.480Z - info: Running on ios test: 42. Make an HTTP request to /NotificationBeacons before calling start

2016-03-14T12:42:51.257Z - info: Running on ios test: 43. #testThaliPeerAction - test getters

2016-03-14T12:42:51.605Z - info: Running on ios test: 44. #testThaliPeerAction - start and kill

2016-03-14T12:42:51.871Z - info: Running on ios test: 45. #testThaliPeerAction - double start

2016-03-14T12:42:52.147Z - info: Running on ios test: 46. #testThaliPeerAction - start after kill

2016-03-14T12:42:52.397Z - info: Running on ios test: 47. #testThaliPeerAction - make sure ids are unique

2016-03-14T12:42:52.632Z - info: Running on ios test: 48. Test PeerConnectionInformation basics

2016-03-14T12:42:53.116Z - info: Running on ios test: 49. Test PeerDictionary basic functionality

2016-03-14T12:42:53.565Z - info: Running on ios test: 50. Test PeerDictionary with multiple entries.

2016-03-14T12:42:55.942Z - info: Running on ios test: 51. RESOLVED entries are removed before WAITING state entry.

2016-03-14T12:42:57.202Z - info: Running on ios test: 52. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-14T12:42:58.514Z - info: Running on ios test: 53. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-14T12:42:59.731Z - info: Running on ios test: 54. #ThaliPeerPoolInterface - bad enqueues

2016-03-14T12:43:00.008Z - info: Running on ios test: 55. #ThaliPeerPoolInterface - do not allow same object type

2016-03-14T12:43:00.331Z - info: Running on ios test: 56. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-14T12:43:00.716Z - info: Running on ios test: 57. compareBufferArrays

2016-03-14T12:43:01.223Z - info: Running on ios test: 58. Call start twice and get error

2016-03-14T12:43:01.526Z - info: Running on ios test: 59. Start and make sure it runs

2016-03-14T12:43:01.809Z - info: Running on ios test: 60. Make sure getTimeWhenRun is right after start

2016-03-14T12:43:02.418Z - info: Running on ios test: 61. Make sure getTimeWhenRun is -1 after function is called

2016-03-14T12:43:02.735Z - info: Running on ios test: 62. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-14T12:43:03.106Z - info: Running on ios test: 63. Test TransientState

2016-03-14T12:43:03.402Z - info: Running on ios test: 64. No peers and empty database

2016-03-14T12:43:03.888Z - info: Running on ios test: 65. One peer and empty DB

2016-03-14T12:43:04.441Z - info: Running on ios test: 66. One peer with _Local set behind current seq

2016-03-14T12:43:05.145Z - info: Running on ios test: 67. One peer with _Local set equal to current seq

2016-03-14T12:43:05.991Z - info: Running on ios test: 68. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-14T12:43:06.744Z - info: Running on ios test: 69. Three peers, one not in DB, one behind and one ahead

2016-03-14T12:43:07.559Z - info: Running on ios test: 70. More than maximum peers, make sure we only send maximum allowed

2016-03-14T12:43:08.929Z - info: Running on ios test: 71. two peers with empty DB, update the doc

2016-03-14T12:43:09.618Z - info: Running on ios test: 72. add doc and make sure tokens refresh when they expire

2016-03-14T12:43:10.623Z - info: Running on ios test: 73. start and stop and start and stop

2016-03-14T12:43:11.225Z - info: Running on ios test: 74. two identical starts in a row

2016-03-14T12:43:11.829Z - info: Running on ios test: 75. two different starts in a row

2016-03-14T12:43:12.538Z - info: Running on ios test: 76. two stops and a start and two stops

2016-03-14T12:43:13.166Z - info: Running on ios test: 77. we properly enqueue requests so no then needed

2016-03-14T12:43:13.746Z - info: Running on ios test: 78. test calculateSeqPointKeyId

2016-03-14T12:43:14.034Z - info: Running on ios test: 79. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-14T12:43:14.485Z - info: Running on ios test: 80. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-14T12:43:14.908Z - info: Running on ios test: 81. messages with invalid location or USN should be ignored

2016-03-14T12:43:15.276Z - info: Running on ios test: 82. verify that Thali-specific messages are filtered correctly

2016-03-14T12:43:15.687Z - info: Running on ios test: 83. #startListeningForAdvertisements should fail if start not called

2016-03-14T12:43:16.279Z - info: Running on ios test: 84. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-14T12:43:16.888Z - info: Running on ios test: 85. #start should fail if called twice in a row

2016-03-14T12:43:17.308Z - info: Running on ios test: 86. should not be started after stop is called

2016-03-14T12:43:17.707Z - info: Running on ios test: 87. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-14T12:43:18.052Z - info: Running on ios test: 88. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-14T12:43:18.369Z - info: Running on ios test: 89. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-14T12:43:18.746Z - info: Running on ios test: 90. #stop can be called multiple times in a row

2016-03-14T12:43:19.037Z - info: Running on ios test: 91. #startListeningForAdvertisements can be called multiple times in a row

2016-03-14T12:43:19.496Z - info: Running on ios test: 92. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-14T12:43:19.830Z - info: Running on ios test: 93. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-14T12:43:20.160Z - info: Running on ios test: 94. functions are run from a queue in the right order

2016-03-14T12:43:20.495Z - info: Running on ios test: 95. #ThaliPeerPoolDefault - single action

2016-03-14T12:43:20.914Z - info: Running on ios test: 96. #ThaliPeerPoolDefault - multiple actions

2016-03-14T12:43:21.460Z - info: Test run on ios complete

2016-03-14T12:43:21.462Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-14T12:43:21.464Z - info: PLATFORM: ios

2016-03-14T12:43:21.468Z - info: RESULT: PASS
2016-03-14T12:43:21.469Z - info: 96 of 96 tests completed
2016-03-14T12:43:21.470Z - info: 96/96 passed (0 failures)

2016-03-14T12:43:21.471Z - info: --- Test Details ---



2016-03-14T12:43:21.472Z - info: 1. closeAll can close even when connections open - pass
2016-03-14T12:43:21.474Z - info: 2. closeAll with promise - pass
2016-03-14T12:43:21.474Z - info: 3. multiplex can send data - pass
2016-03-14T12:43:21.475Z - info: 4. enqueue and run in order - pass
2016-03-14T12:43:21.476Z - info: 5. enqueueAtTop and run backwards - pass
2016-03-14T12:43:21.476Z - info: 6. mix enqueue and enqueueAtTop - pass
2016-03-14T12:43:21.477Z - info: 7. queues handled independently - pass
2016-03-14T12:43:21.478Z - info: 8. basic - pass
2016-03-14T12:43:21.478Z - info: 9. another - pass
2016-03-14T12:43:21.479Z - info: 10. #startListeningForAdvertisements should fail if start not called - pass
2016-03-14T12:43:21.482Z - info: 11. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-14T12:43:21.485Z - info: 12. should be able to call #stopListeningForAdvertisements many times - pass
2016-03-14T12:43:21.486Z - info: 13. should be able to call #startListeningForAdvertisements many times - pass
2016-03-14T12:43:21.487Z - info: 14. should be able to call #startUpdateAdvertisingAndListening many times - pass

2016-03-14T12:43:21.488Z - info: 15. should be able to call #stopAdvertisingAndListening many times - pass
2016-03-14T12:43:21.488Z - info: 16. #start should fail if called twice in a row - pass
2016-03-14T12:43:21.489Z - info: 17. does not emit duplicate discoveryAdvertisingStateUpdate - pass

2016-03-14T12:43:21.490Z - info: 18. does not send duplicate availability changes - pass

2016-03-14T12:43:21.491Z - info: 19. can get the network status - pass

2016-03-14T12:43:21.492Z - info: 20. wifi peer is marked unavailable if announcements stop - pass
2016-03-14T12:43:21.493Z - info: 21. can get the network status before starting - pass
2016-03-14T12:43:21.493Z - info: 22. #generatePreambleAndBeacons bad args - pass
2016-03-14T12:43:21.494Z - info: 23. #generatePreambleAndBeacons empty keys to notify - pass
2016-03-14T12:43:21.494Z - info: 24. #generatePreambleAndBeacons multiple keys to notify - pass
2016-03-14T12:43:21.495Z - info: 25. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass

2016-03-14T12:43:21.496Z - info: 26. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass
2016-03-14T12:43:21.497Z - info: 27. #parseBeacons expiration out of range lower - pass

2016-03-14T12:43:21.498Z - info: 28. #parseBeacons expiration out of range lower - pass
2016-03-14T12:43:21.499Z - info: 29. #parseBeacons no beacons returns null - pass
2016-03-14T12:43:21.499Z - info: 30. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass
2016-03-14T12:43:21.500Z - info: 31. #parseBeacons addressBookCallback fails decrypt - pass

2016-03-14T12:43:21.501Z - info: 32. #parseBeacons addressBookCallback returns no matches - pass
2016-03-14T12:43:21.502Z - info: 33. #parseBeacons addressBookCallback returns spurious match - pass

2016-03-14T12:43:21.503Z - info: 34. #parseBeacons addressBookCallback returns public key - pass

2016-03-14T12:43:21.504Z - info: 35. #parseBeacons with beacons both for and not for the user - pass
2016-03-14T12:43:21.504Z - info: 36. Start and stop ThaliNotificationServer - pass
2016-03-14T12:43:21.505Z - info: 37. Pass an empty array to ThaliNotificationServer.start - pass

2016-03-14T12:43:21.506Z - info: 38. Pass a string to ThaliNotificationServer.start - pass
2016-03-14T12:43:21.507Z - info: 39. Pass an empty parameter to ThaliNotificationServer.start - pass
2016-03-14T12:43:21.508Z - info: 40. Make an HTTP request to /NotificationBeacons - pass
2016-03-14T12:43:21.508Z - info: 41. Make an HTTP request to /NotificationBeacons (no keys) - pass
2016-03-14T12:43:21.509Z - info: 42. Make an HTTP request to /NotificationBeacons before calling start - pass

2016-03-14T12:43:21.510Z - info: 43. #testThaliPeerAction - test getters - pass
2016-03-14T12:43:21.511Z - info: 44. #testThaliPeerAction - start and kill - pass

2016-03-14T12:43:21.512Z - info: 45. #testThaliPeerAction - double start - pass

2016-03-14T12:43:21.513Z - info: 46. #testThaliPeerAction - start after kill - pass
2016-03-14T12:43:21.513Z - info: 47. #testThaliPeerAction - make sure ids are unique - pass
2016-03-14T12:43:21.514Z - info: 48. Test PeerConnectionInformation basics - pass
2016-03-14T12:43:21.515Z - info: 49. Test PeerDictionary basic functionality - pass
2016-03-14T12:43:21.515Z - info: 50. Test PeerDictionary with multiple entries. - pass
2016-03-14T12:43:21.516Z - info: 51. RESOLVED entries are removed before WAITING state entry. - pass
2016-03-14T12:43:21.517Z - info: 52. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass

2016-03-14T12:43:21.517Z - info: 53. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass

2016-03-14T12:43:21.525Z - info: 54. #ThaliPeerPoolInterface - bad enqueues - pass

2016-03-14T12:43:21.526Z - info: 55. #ThaliPeerPoolInterface - do not allow same object type - pass

2016-03-14T12:43:21.527Z - info: 56. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass

2016-03-14T12:43:21.528Z - info: 57. compareBufferArrays - pass

2016-03-14T12:43:21.529Z - info: 58. Call start twice and get error - pass

2016-03-14T12:43:21.530Z - info: 59. Start and make sure it runs - pass

2016-03-14T12:43:21.531Z - info: 60. Make sure getTimeWhenRun is right after start - pass
2016-03-14T12:43:21.532Z - info: 61. Make sure getTimeWhenRun is -1 after function is called - pass

2016-03-14T12:43:21.533Z - info: 62. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass

2016-03-14T12:43:21.534Z - info: 63. Test TransientState - pass

2016-03-14T12:43:21.534Z - info: 64. No peers and empty database - pass

2016-03-14T12:43:21.535Z - info: 65. One peer and empty DB - pass

2016-03-14T12:43:21.536Z - info: 66. One peer with _Local set behind current seq - pass

2016-03-14T12:43:21.537Z - info: 67. One peer with _Local set equal to current seq - pass
2016-03-14T12:43:21.538Z - info: 68. One peer with _Local set ahead of current seq (and no this should not happen) - pass
2016-03-14T12:43:21.539Z - info: 69. Three peers, one not in DB, one behind and one ahead - pass
2016-03-14T12:43:21.540Z - info: 70. More than maximum peers, make sure we only send maximum allowed - pass
2016-03-14T12:43:21.541Z - info: 71. two peers with empty DB, update the doc - pass
2016-03-14T12:43:21.542Z - info: 72. add doc and make sure tokens refresh when they expire - pass
2016-03-14T12:43:21.542Z - info: 73. start and stop and start and stop - pass
2016-03-14T12:43:21.543Z - info: 74. two identical starts in a row - pass
2016-03-14T12:43:21.544Z - info: 75. two different starts in a row - pass
2016-03-14T12:43:21.545Z - info: 76. two stops and a start and two stops - pass
2016-03-14T12:43:21.546Z - info: 77. we properly enqueue requests so no then needed - pass
2016-03-14T12:43:21.547Z - info: 78. test calculateSeqPointKeyId - pass

2016-03-14T12:43:21.547Z - info: 79. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass
2016-03-14T12:43:21.548Z - info: 80. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-03-14T12:43:21.549Z - info: 81. messages with invalid location or USN should be ignored - pass

2016-03-14T12:43:21.550Z - info: 82. verify that Thali-specific messages are filtered correctly - pass
2016-03-14T12:43:21.551Z - info: 83. #startListeningForAdvertisements should fail if start not called - pass

2016-03-14T12:43:21.552Z - info: 84. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-14T12:43:21.553Z - info: 85. #start should fail if called twice in a row - pass

2016-03-14T12:43:21.554Z - info: 86. should not be started after stop is called - pass

2016-03-14T12:43:21.554Z - info: 87. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass

2016-03-14T12:43:21.555Z - info: 88. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass
2016-03-14T12:43:21.556Z - info: 89. #startUpdateAdvertisingAndListening should start hosting given router object - pass

2016-03-14T12:43:21.557Z - info: 90. #stop can be called multiple times in a row - pass

2016-03-14T12:43:21.558Z - info: 91. #startListeningForAdvertisements can be called multiple times in a row - pass
2016-03-14T12:43:21.559Z - info: 92. #stopListeningForAdvertisements can be called multiple times in a row - pass

2016-03-14T12:43:21.559Z - info: 93. #stopAdvertisingAndListening can be called multiple times in a row - pass

2016-03-14T12:43:21.560Z - info: 94. functions are run from a queue in the right order - pass

2016-03-14T12:43:21.561Z - info: 95. #ThaliPeerPoolDefault - single action - pass

2016-03-14T12:43:21.562Z - info: 96. #ThaliPeerPoolDefault - multiple actions - pass
2016-03-14T12:43:21.563Z - info: 

-== END ==-

2016-03-14T12:43:24.076Z - debug: Socket disconnected: transport close 2 (Apple-IpadAir2-1)

2016-03-14T12:43:25.093Z - debug: Socket disconnected: transport close 4 (Apple-Iphone5-1)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m
2016-03-14T12:42:31.963Z - error: test server: Device Apple-Iphone5-1


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
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62509094588eeb1_Make_CI_build_and_unit_tests_pass_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/62509094588eeb1_Make_CI_build_and_unit_tests_pass_vjrantal/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on ZX1C223JKW 
Android task is completed. [SUCCESS]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/62509094588eeb1_Make_CI_build_and_unit_tests_pass_vjrantal/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:0 
child process exited with code 0 on device LGH8153b36be34 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/62509094588eeb1_Make_CI_build_and_unit_tests_pass_vjrantal/thali05_LGE-LG-H815.md)

####Node name: thali06
Console output:
```
STOP log received from  7970f88c Test has  FAILED
STOP log received from  FA55PYS00566 Test has  FAILED
Device test finished on 7970f88c 
Device test finished on FA55PYS00566 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62509094588eeb1_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/62509094588eeb1_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
STOP log received from  4db5c8cc Test has  FAILED
Device test finished on 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62509094588eeb1_Make_CI_build_and_unit_tests_pass_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
STOP log received from  4325e43f Test has  FAILED
Device test finished on 4325e43f 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62509094588eeb1_Make_CI_build_and_unit_tests_pass_vjrantal/thali08_samsung-SM-A300FU.md)




###iOS Logs
[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/62509094588eeb1_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/62509094588eeb1_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/62509094588eeb1_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/62509094588eeb1_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_IpadAir2-1.md)



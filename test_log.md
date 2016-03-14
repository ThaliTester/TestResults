#### Test 6250909442642cd Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":10}}
2016-03-14T06:40:23.412Z - info: listening on *:3000

2016-03-14T06:40:24.425Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:0

2016-03-14T06:40:24.815Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:1

2016-03-14T06:40:24.818Z - info: Required number of ios devices presented (2)

2016-03-14T06:40:24.822Z - info: Starting unit test run for platform: ios

2016-03-14T06:40:24.963Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:2

2016-03-14T06:40:24.970Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:3

2016-03-14T06:40:24.971Z - info: Discarding surplus device: Apple-Iphone5-1

2016-03-14T06:40:25.254Z - info: Running on ios test: 1. closeAll can close even when connections open

2016-03-14T06:40:25.484Z - info: Running on ios test: 2. closeAll with promise

2016-03-14T06:40:25.742Z - info: Running on ios test: 3. multiplex can send data

2016-03-14T06:40:25.754Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:4

2016-03-14T06:40:25.755Z - info: Discarding surplus device: Apple-Iphone6-1

2016-03-14T06:40:26.084Z - info: Running on ios test: 4. enqueue and run in order

2016-03-14T06:40:26.594Z - info: Running on ios test: 5. enqueueAtTop and run backwards

2016-03-14T06:40:26.936Z - info: Running on ios test: 6. mix enqueue and enqueueAtTop

2016-03-14T06:40:27.309Z - info: Running on ios test: 7. queues handled independently

2016-03-14T06:40:27.597Z - info: Running on ios test: 8. basic

2016-03-14T06:40:27.815Z - info: Running on ios test: 9. another

2016-03-14T06:40:28.050Z - debug: Socket disconnected: transport close 3 (Apple-Iphone5-1)

2016-03-14T06:40:28.111Z - info: Running on ios test: 10. #startListeningForAdvertisements should fail if start not called

2016-03-14T06:40:28.205Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:5

2016-03-14T06:40:28.207Z - info: Required number of android devices presented (2)

2016-03-14T06:40:28.209Z - info: Starting unit test run for platform: android

2016-03-14T06:40:28.386Z - info: Running on ios test: 11. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-14T06:40:28.452Z - debug: Socket disconnected: transport close 4 (Apple-Iphone6-1)

2016-03-14T06:40:28.684Z - info: Running on ios test: 12. should be able to call #stopListeningForAdvertisements many times

2016-03-14T06:40:28.967Z - info: Running on ios test: 13. should be able to call #startListeningForAdvertisements many times

2016-03-14T06:40:29.222Z - info: Running on ios test: 14. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-14T06:40:29.545Z - info: Running on ios test: 15. should be able to call #stopAdvertisingAndListening many times

2016-03-14T06:40:29.665Z - debug: Socket disconnected: transport close 5 (LGE-LG-H815)

2016-03-14T06:40:29.788Z - info: Running on ios test: 16. #start should fail if called twice in a row

2016-03-14T06:40:30.041Z - info: Running on ios test: 17. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-14T06:40:30.320Z - info: Running on ios test: 18. does not send duplicate availability changes

2016-03-14T06:40:30.610Z - info: Running on ios test: 19. can get the network status

2016-03-14T06:40:30.846Z - info: Running on ios test: 20. wifi peer is marked unavailable if announcements stop

2016-03-14T06:40:32.138Z - info: Running on ios test: 21. can get the network status before starting

2016-03-14T06:40:32.415Z - info: Running on ios test: 22. #generatePreambleAndBeacons bad args

2016-03-14T06:40:32.777Z - info: Running on ios test: 23. #generatePreambleAndBeacons empty keys to notify

2016-03-14T06:40:33.083Z - info: Running on ios test: 24. #generatePreambleAndBeacons multiple keys to notify

2016-03-14T06:40:33.576Z - info: Running on ios test: 25. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-14T06:40:33.959Z - info: Running on ios test: 26. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-14T06:40:34.266Z - info: Running on ios test: 27. #parseBeacons expiration out of range lower

2016-03-14T06:40:34.543Z - info: Running on ios test: 28. #parseBeacons expiration out of range lower

2016-03-14T06:40:34.860Z - info: Running on ios test: 29. #parseBeacons no beacons returns null

2016-03-14T06:40:35.146Z - info: Running on ios test: 30. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-14T06:40:35.402Z - info: Running on ios test: 31. #parseBeacons addressBookCallback fails decrypt

2016-03-14T06:40:35.783Z - info: Running on ios test: 32. #parseBeacons addressBookCallback returns no matches

2016-03-14T06:40:36.059Z - info: Running on ios test: 33. #parseBeacons addressBookCallback returns spurious match

2016-03-14T06:40:36.368Z - info: Running on ios test: 34. #parseBeacons addressBookCallback returns public key

2016-03-14T06:40:36.650Z - info: Running on ios test: 35. #parseBeacons with beacons both for and not for the user

2016-03-14T06:40:36.982Z - info: Running on ios test: 36. Start and stop ThaliNotificationServer

2016-03-14T06:40:37.299Z - info: Running on ios test: 37. Pass an empty array to ThaliNotificationServer.start

2016-03-14T06:40:37.552Z - info: Running on ios test: 38. Pass a string to ThaliNotificationServer.start

2016-03-14T06:40:37.805Z - info: Running on ios test: 39. Pass an empty parameter to ThaliNotificationServer.start

2016-03-14T06:40:38.076Z - info: Running on ios test: 40. Make an HTTP request to /NotificationBeacons

2016-03-14T06:40:38.538Z - info: Running on ios test: 41. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-14T06:40:38.793Z - info: Running on ios test: 42. Make an HTTP request to /NotificationBeacons before calling start

2016-03-14T06:40:39.115Z - info: Running on ios test: 43. #testThaliPeerAction - test getters

2016-03-14T06:40:39.351Z - info: Running on ios test: 44. #testThaliPeerAction - start and kill

2016-03-14T06:40:39.591Z - info: Running on ios test: 45. #testThaliPeerAction - double start

2016-03-14T06:40:39.831Z - info: Running on ios test: 46. #testThaliPeerAction - start after kill

2016-03-14T06:40:40.083Z - info: Running on ios test: 47. #testThaliPeerAction - make sure ids are unique

2016-03-14T06:40:40.311Z - info: Running on ios test: 48. Test PeerConnectionInformation basics

2016-03-14T06:40:40.588Z - info: Running on ios test: 49. Test PeerDictionary basic functionality

2016-03-14T06:40:41.243Z - info: Running on ios test: 50. Test PeerDictionary with multiple entries.

2016-03-14T06:40:42.282Z - debug: Socket disconnected: transport close 2 (samsung-SM-N910C)

2016-03-14T06:40:42.590Z - info: Running on ios test: 51. RESOLVED entries are removed before WAITING state entry.

2016-03-14T06:40:43.310Z - info: Running on ios test: 52. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-14T06:40:44.030Z - info: Running on ios test: 53. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-14T06:40:44.769Z - info: Running on ios test: 54. #ThaliPeerPoolInterface - bad enqueues

2016-03-14T06:40:44.986Z - info: Running on ios test: 55. #ThaliPeerPoolInterface - do not allow same object type

2016-03-14T06:40:45.182Z - info: Running on ios test: 56. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-14T06:40:45.441Z - info: Running on ios test: 57. compareBufferArrays

2016-03-14T06:40:45.685Z - info: Running on ios test: 58. Call start twice and get error

2016-03-14T06:40:45.934Z - info: Running on ios test: 59. Start and make sure it runs

2016-03-14T06:40:46.325Z - info: Running on ios test: 60. Make sure getTimeWhenRun is right after start

2016-03-14T06:40:46.552Z - info: Running on ios test: 61. Make sure getTimeWhenRun is -1 after function is called

2016-03-14T06:40:46.776Z - info: Running on ios test: 62. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-14T06:40:47.006Z - info: Running on ios test: 63. Test TransientState

2016-03-14T06:40:47.260Z - info: Running on ios test: 64. No peers and empty database

2016-03-14T06:40:47.697Z - info: Running on ios test: 65. One peer and empty DB

2016-03-14T06:40:48.247Z - info: Running on ios test: 66. One peer with _Local set behind current seq

2016-03-14T06:40:48.746Z - info: Running on ios test: 67. One peer with _Local set equal to current seq

2016-03-14T06:40:49.204Z - info: Running on ios test: 68. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-14T06:40:49.661Z - info: Running on ios test: 69. Three peers, one not in DB, one behind and one ahead

2016-03-14T06:40:50.264Z - info: Running on ios test: 70. More than maximum peers, make sure we only send maximum allowed

2016-03-14T06:40:51.177Z - info: Running on ios test: 71. two peers with empty DB, update the doc

2016-03-14T06:40:51.823Z - info: Running on ios test: 72. add doc and make sure tokens refresh when they expire

2016-03-14T06:40:52.977Z - info: Running on ios test: 73. start and stop and start and stop

2016-03-14T06:40:53.528Z - info: Running on ios test: 74. two identical starts in a row

2016-03-14T06:40:54.514Z - info: Running on ios test: 75. two different starts in a row

2016-03-14T06:40:55.241Z - info: Running on ios test: 76. two stops and a start and two stops

2016-03-14T06:40:55.894Z - info: Running on ios test: 77. we properly enqueue requests so no then needed

2016-03-14T06:40:56.566Z - info: Running on ios test: 78. test calculateSeqPointKeyId

2016-03-14T06:40:57.134Z - info: Running on ios test: 79. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-14T06:40:57.772Z - info: Running on ios test: 80. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-14T06:40:58.404Z - info: Running on ios test: 81. messages with invalid location or USN should be ignored

2016-03-14T06:40:58.954Z - info: Running on ios test: 82. verify that Thali-specific messages are filtered correctly

2016-03-14T06:40:59.367Z - info: Running on ios test: 83. #startListeningForAdvertisements should fail if start not called

2016-03-14T06:40:59.804Z - info: Running on ios test: 84. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-14T06:41:00.286Z - info: Running on ios test: 85. #start should fail if called twice in a row

2016-03-14T06:41:00.832Z - info: Running on ios test: 86. should not be started after stop is called

2016-03-14T06:41:01.501Z - info: Running on ios test: 87. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-14T06:41:02.125Z - info: Running on ios test: 88. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-14T06:41:05.102Z - info: Running on ios test: 89. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-14T06:41:06.048Z - info: Running on ios test: 90. #stop can be called multiple times in a row

2016-03-14T06:41:06.404Z - info: Running on ios test: 91. #startListeningForAdvertisements can be called multiple times in a row

2016-03-14T06:41:06.926Z - info: Running on ios test: 92. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-14T06:41:07.308Z - info: Running on ios test: 93. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-14T06:41:07.757Z - info: Running on ios test: 94. functions are run from a queue in the right order

2016-03-14T06:41:08.157Z - info: Running on ios test: 95. #ThaliPeerPoolDefault - single action

2016-03-14T06:41:08.580Z - info: Running on ios test: 96. #ThaliPeerPoolDefault - multiple actions

2016-03-14T06:41:08.919Z - info: Test run on ios complete

2016-03-14T06:41:08.921Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-14T06:41:08.925Z - info: PLATFORM: ios

2016-03-14T06:41:08.926Z - info: RESULT: PASS
2016-03-14T06:41:08.933Z - info: 96 of 96 tests completed

2016-03-14T06:41:08.934Z - info: 96/96 passed (0 failures)
2016-03-14T06:41:08.935Z - info: --- Test Details ---


2016-03-14T06:41:08.936Z - info: 1. closeAll can close even when connections open - pass
2016-03-14T06:41:08.937Z - info: 2. closeAll with promise - pass
2016-03-14T06:41:08.937Z - info: 3. multiplex can send data - pass
2016-03-14T06:41:08.938Z - info: 4. enqueue and run in order - pass
2016-03-14T06:41:08.939Z - info: 5. enqueueAtTop and run backwards - pass
2016-03-14T06:41:08.939Z - info: 6. mix enqueue and enqueueAtTop - pass
2016-03-14T06:41:08.941Z - info: 7. queues handled independently - pass
2016-03-14T06:41:08.942Z - info: 8. basic - pass
2016-03-14T06:41:08.942Z - info: 9. another - pass
2016-03-14T06:41:08.943Z - info: 10. #startListeningForAdvertisements should fail if start not called - pass
2016-03-14T06:41:08.944Z - info: 11. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-14T06:41:08.947Z - info: 12. should be able to call #stopListeningForAdvertisements many times - pass
2016-03-14T06:41:08.951Z - info: 13. should be able to call #startListeningForAdvertisements many times - pass

2016-03-14T06:41:08.952Z - info: 14. should be able to call #startUpdateAdvertisingAndListening many times - pass

2016-03-14T06:41:08.953Z - info: 15. should be able to call #stopAdvertisingAndListening many times - pass

2016-03-14T06:41:08.954Z - info: 16. #start should fail if called twice in a row - pass
2016-03-14T06:41:08.955Z - info: 17. does not emit duplicate discoveryAdvertisingStateUpdate - pass
2016-03-14T06:41:08.956Z - info: 18. does not send duplicate availability changes - pass
2016-03-14T06:41:08.956Z - info: 19. can get the network status - pass
2016-03-14T06:41:08.957Z - info: 20. wifi peer is marked unavailable if announcements stop - pass

2016-03-14T06:41:08.958Z - info: 21. can get the network status before starting - pass
2016-03-14T06:41:08.959Z - info: 22. #generatePreambleAndBeacons bad args - pass

2016-03-14T06:41:08.960Z - info: 23. #generatePreambleAndBeacons empty keys to notify - pass

2016-03-14T06:41:08.961Z - info: 24. #generatePreambleAndBeacons multiple keys to notify - pass

2016-03-14T06:41:08.962Z - info: 25. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass

2016-03-14T06:41:08.963Z - info: 26. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass

2016-03-14T06:41:08.963Z - info: 27. #parseBeacons expiration out of range lower - pass
2016-03-14T06:41:08.964Z - info: 28. #parseBeacons expiration out of range lower - pass

2016-03-14T06:41:08.965Z - info: 29. #parseBeacons no beacons returns null - pass
2016-03-14T06:41:08.966Z - info: 30. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass
2016-03-14T06:41:08.967Z - info: 31. #parseBeacons addressBookCallback fails decrypt - pass

2016-03-14T06:41:08.968Z - info: 32. #parseBeacons addressBookCallback returns no matches - pass

2016-03-14T06:41:08.972Z - info: 33. #parseBeacons addressBookCallback returns spurious match - pass

2016-03-14T06:41:08.973Z - info: 34. #parseBeacons addressBookCallback returns public key - pass

2016-03-14T06:41:08.974Z - info: 35. #parseBeacons with beacons both for and not for the user - pass
2016-03-14T06:41:08.975Z - info: 36. Start and stop ThaliNotificationServer - pass

2016-03-14T06:41:08.976Z - info: 37. Pass an empty array to ThaliNotificationServer.start - pass

2016-03-14T06:41:08.989Z - info: 38. Pass a string to ThaliNotificationServer.start - pass

2016-03-14T06:41:08.996Z - info: 39. Pass an empty parameter to ThaliNotificationServer.start - pass

2016-03-14T06:41:08.997Z - info: 40. Make an HTTP request to /NotificationBeacons - pass
2016-03-14T06:41:08.998Z - info: 41. Make an HTTP request to /NotificationBeacons (no keys) - pass

2016-03-14T06:41:08.999Z - info: 42. Make an HTTP request to /NotificationBeacons before calling start - pass
2016-03-14T06:41:08.999Z - info: 43. #testThaliPeerAction - test getters - pass

2016-03-14T06:41:09.000Z - info: 44. #testThaliPeerAction - start and kill - pass
2016-03-14T06:41:09.001Z - info: 45. #testThaliPeerAction - double start - pass
2016-03-14T06:41:09.001Z - info: 46. #testThaliPeerAction - start after kill - pass
2016-03-14T06:41:09.002Z - info: 47. #testThaliPeerAction - make sure ids are unique - pass
2016-03-14T06:41:09.003Z - info: 48. Test PeerConnectionInformation basics - pass
2016-03-14T06:41:09.003Z - info: 49. Test PeerDictionary basic functionality - pass
2016-03-14T06:41:09.004Z - info: 50. Test PeerDictionary with multiple entries. - pass
2016-03-14T06:41:09.005Z - info: 51. RESOLVED entries are removed before WAITING state entry. - pass
2016-03-14T06:41:09.006Z - info: 52. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass
2016-03-14T06:41:09.006Z - info: 53. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass
2016-03-14T06:41:09.007Z - info: 54. #ThaliPeerPoolInterface - bad enqueues - pass
2016-03-14T06:41:09.008Z - info: 55. #ThaliPeerPoolInterface - do not allow same object type - pass
2016-03-14T06:41:09.008Z - info: 56. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass
2016-03-14T06:41:09.010Z - info: 57. compareBufferArrays - pass

2016-03-14T06:41:09.011Z - info: 58. Call start twice and get error - pass
2016-03-14T06:41:09.012Z - info: 59. Start and make sure it runs - pass

2016-03-14T06:41:09.013Z - info: 60. Make sure getTimeWhenRun is right after start - pass
2016-03-14T06:41:09.013Z - info: 61. Make sure getTimeWhenRun is -1 after function is called - pass

2016-03-14T06:41:09.014Z - info: 62. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass

2016-03-14T06:41:09.015Z - info: 63. Test TransientState - pass

2016-03-14T06:41:09.022Z - info: 64. No peers and empty database - pass

2016-03-14T06:41:09.023Z - info: 65. One peer and empty DB - pass
2016-03-14T06:41:09.024Z - info: 66. One peer with _Local set behind current seq - pass

2016-03-14T06:41:09.025Z - info: 67. One peer with _Local set equal to current seq - pass

2016-03-14T06:41:09.026Z - info: 68. One peer with _Local set ahead of current seq (and no this should not happen) - pass
2016-03-14T06:41:09.026Z - info: 69. Three peers, one not in DB, one behind and one ahead - pass

2016-03-14T06:41:09.028Z - info: 70. More than maximum peers, make sure we only send maximum allowed - pass

2016-03-14T06:41:09.029Z - info: 71. two peers with empty DB, update the doc - pass

2016-03-14T06:41:09.030Z - info: 72. add doc and make sure tokens refresh when they expire - pass
2016-03-14T06:41:09.030Z - info: 73. start and stop and start and stop - pass

2016-03-14T06:41:09.031Z - info: 74. two identical starts in a row - pass
2016-03-14T06:41:09.032Z - info: 75. two different starts in a row - pass

2016-03-14T06:41:09.033Z - info: 76. two stops and a start and two stops - pass

2016-03-14T06:41:09.034Z - info: 77. we properly enqueue requests so no then needed - pass

2016-03-14T06:41:09.034Z - info: 78. test calculateSeqPointKeyId - pass
2016-03-14T06:41:09.035Z - info: 79. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass

2016-03-14T06:41:09.036Z - info: 80. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-03-14T06:41:09.037Z - info: 81. messages with invalid location or USN should be ignored - pass
2016-03-14T06:41:09.037Z - info: 82. verify that Thali-specific messages are filtered correctly - pass

2016-03-14T06:41:09.038Z - info: 83. #startListeningForAdvertisements should fail if start not called - pass

2016-03-14T06:41:09.039Z - info: 84. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-14T06:41:09.040Z - info: 85. #start should fail if called twice in a row - pass

2016-03-14T06:41:09.041Z - info: 86. should not be started after stop is called - pass

2016-03-14T06:41:09.041Z - info: 87. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass

2016-03-14T06:41:09.042Z - info: 88. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass
2016-03-14T06:41:09.043Z - info: 89. #startUpdateAdvertisingAndListening should start hosting given router object - pass

2016-03-14T06:41:09.044Z - info: 90. #stop can be called multiple times in a row - pass

2016-03-14T06:41:09.044Z - info: 91. #startListeningForAdvertisements can be called multiple times in a row - pass
2016-03-14T06:41:09.045Z - info: 92. #stopListeningForAdvertisements can be called multiple times in a row - pass

2016-03-14T06:41:09.048Z - info: 93. #stopAdvertisingAndListening can be called multiple times in a row - pass

2016-03-14T06:41:09.049Z - info: 94. functions are run from a queue in the right order - pass

2016-03-14T06:41:09.050Z - info: 95. #ThaliPeerPoolDefault - single action - pass
2016-03-14T06:41:09.051Z - info: 96. #ThaliPeerPoolDefault - multiple actions - pass

2016-03-14T06:41:09.052Z - info: 

-== END ==-

2016-03-14T06:41:11.751Z - debug: Socket disconnected: transport close 0 (Apple-IpadAir2-1)

2016-03-14T06:41:11.959Z - debug: Socket disconnected: transport close 1 (Apple-Iphone5s-1)


 
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
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/6250909442642cd_Make_CI_build_and_unit_tests_pass_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/6250909442642cd_Make_CI_build_and_unit_tests_pass_vjrantal/thali02_LGE-LG-D722.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/6250909442642cd_Make_CI_build_and_unit_tests_pass_vjrantal/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
STOP log received from  ZX1C223JKW Test has  FAILED
Device test finished on ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/6250909442642cd_Make_CI_build_and_unit_tests_pass_vjrantal/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:0 
child process exited with code 0 on device LGH8153b36be34 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/6250909442642cd_Make_CI_build_and_unit_tests_pass_vjrantal/thali05_LGE-LG-H815.md)

####Node name: thali06
Console output:
```
STOP log received from  7970f88c Test has  FAILED
Device test finished on 7970f88c 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:0 
child process exited with code 0 on device FA55PYS00566 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/6250909442642cd_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/6250909442642cd_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
STOP log received from  4db5c8cc Test has  FAILED
Device test finished on 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/6250909442642cd_Make_CI_build_and_unit_tests_pass_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
STOP log received from  4325e43f Test has  FAILED
Device test finished on 4325e43f 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/6250909442642cd_Make_CI_build_and_unit_tests_pass_vjrantal/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 09a9416e0297d102 app:com.test.thalitest code:0 
child process exited with code 0 on device 09a9416e0297d102 
Android task is completed. [FAILED]
```
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/6250909442642cd_Make_CI_build_and_unit_tests_pass_vjrantal/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/6250909442642cd_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/6250909442642cd_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/6250909442642cd_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/6250909442642cd_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_IpadAir2-1.md)



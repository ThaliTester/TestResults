#### Test 625090942f85e77 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":10}}
2016-03-11T16:01:45.131Z - info: listening on *:3000

2016-03-11T16:01:45.741Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:0

2016-03-11T16:01:47.553Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:1

2016-03-11T16:01:47.556Z - info: Required number of ios devices presented (2)

2016-03-11T16:01:47.559Z - info: Starting unit test run for platform: ios

2016-03-11T16:01:48.035Z - info: Running on ios test: 1. closeAll can close even when connections open

2016-03-11T16:01:48.529Z - info: Running on ios test: 2. closeAll with promise

2016-03-11T16:01:48.909Z - info: Running on ios test: 3. multiplex can send data

2016-03-11T16:01:49.034Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:2

2016-03-11T16:01:49.274Z - info: Running on ios test: 4. enqueue and run in order

2016-03-11T16:01:49.494Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:3

2016-03-11T16:01:49.495Z - info: Discarding surplus device: Apple-Iphone5-1

2016-03-11T16:01:49.943Z - info: Running on ios test: 5. enqueueAtTop and run backwards

2016-03-11T16:01:50.282Z - info: Running on ios test: 6. mix enqueue and enqueueAtTop

2016-03-11T16:01:50.421Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:4

2016-03-11T16:01:50.424Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-11T16:01:50.681Z - info: Running on ios test: 7. queues handled independently

2016-03-11T16:01:50.981Z - info: Running on ios test: 8. basic

2016-03-11T16:01:51.349Z - info: Running on ios test: 9. another

2016-03-11T16:01:51.746Z - info: Running on ios test: 10. #startListeningForAdvertisements should fail if start not called

2016-03-11T16:01:52.161Z - info: Running on ios test: 11. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-11T16:01:52.794Z - info: Running on ios test: 12. should be able to call #stopListeningForAdvertisements many times

2016-03-11T16:01:52.810Z - debug: Socket disconnected: transport close 3 (Apple-Iphone5-1)

2016-03-11T16:01:52.928Z - debug: Socket disconnected: transport close 4 (Apple-Iphone5s-1)

2016-03-11T16:01:53.722Z - info: Running on ios test: 13. should be able to call #startListeningForAdvertisements many times

2016-03-11T16:01:54.202Z - info: Running on ios test: 14. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-11T16:01:54.901Z - info: Running on ios test: 15. should be able to call #stopAdvertisingAndListening many times

2016-03-11T16:01:55.484Z - info: Running on ios test: 16. #start should fail if called twice in a row

2016-03-11T16:01:56.131Z - info: Running on ios test: 17. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-11T16:01:56.699Z - info: Running on ios test: 18. does not send duplicate availability changes

2016-03-11T16:01:57.261Z - info: Running on ios test: 19. can get the network status

2016-03-11T16:01:57.874Z - info: Running on ios test: 20. wifi peer is marked unavailable if announcements stop

2016-03-11T16:01:59.264Z - info: Running on ios test: 21. can get the network status before starting

2016-03-11T16:01:59.643Z - info: Running on ios test: 22. #generatePreambleAndBeacons bad args

2016-03-11T16:02:00.019Z - info: Running on ios test: 23. #generatePreambleAndBeacons empty keys to notify

2016-03-11T16:02:00.440Z - info: Running on ios test: 24. #generatePreambleAndBeacons multiple keys to notify

2016-03-11T16:02:00.901Z - info: Running on ios test: 25. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-11T16:02:01.313Z - info: Running on ios test: 26. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-11T16:02:01.791Z - info: Running on ios test: 27. #parseBeacons expiration out of range lower

2016-03-11T16:02:02.268Z - info: Running on ios test: 28. #parseBeacons expiration out of range lower

2016-03-11T16:02:02.674Z - info: Running on ios test: 29. #parseBeacons no beacons returns null

2016-03-11T16:02:03.406Z - info: Running on ios test: 30. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-11T16:02:03.955Z - info: Running on ios test: 31. #parseBeacons addressBookCallback fails decrypt

2016-03-11T16:02:04.413Z - info: Running on ios test: 32. #parseBeacons addressBookCallback returns no matches

2016-03-11T16:02:04.932Z - info: Running on ios test: 33. #parseBeacons addressBookCallback returns spurious match

2016-03-11T16:02:05.505Z - info: Running on ios test: 34. #parseBeacons addressBookCallback returns public key

2016-03-11T16:02:06.291Z - info: Running on ios test: 35. #parseBeacons with beacons both for and not for the user

2016-03-11T16:02:06.958Z - info: Running on ios test: 36. Start and stop ThaliNotificationServer

2016-03-11T16:02:07.505Z - info: Running on ios test: 37. Pass an empty array to ThaliNotificationServer.start

2016-03-11T16:02:08.130Z - info: Running on ios test: 38. Pass a string to ThaliNotificationServer.start

2016-03-11T16:02:08.627Z - info: Running on ios test: 39. Pass an empty parameter to ThaliNotificationServer.start

2016-03-11T16:02:09.141Z - info: Running on ios test: 40. Make an HTTP request to /NotificationBeacons

2016-03-11T16:02:09.693Z - info: Running on ios test: 41. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-11T16:02:10.151Z - info: Running on ios test: 42. Make an HTTP request to /NotificationBeacons before calling start

2016-03-11T16:02:10.646Z - info: Running on ios test: 43. #testThaliPeerAction - test getters

2016-03-11T16:02:11.093Z - info: Running on ios test: 44. #testThaliPeerAction - start and kill

2016-03-11T16:02:11.486Z - info: Running on ios test: 45. #testThaliPeerAction - double start

2016-03-11T16:02:11.957Z - info: Running on ios test: 46. #testThaliPeerAction - start after kill

2016-03-11T16:02:12.506Z - info: Running on ios test: 47. #testThaliPeerAction - make sure ids are unique

2016-03-11T16:02:13.004Z - info: Running on ios test: 48. Test PeerConnectionInformation basics

2016-03-11T16:02:13.478Z - info: Running on ios test: 49. Test PeerDictionary basic functionality

2016-03-11T16:02:13.982Z - info: Running on ios test: 50. Test PeerDictionary with multiple entries.

2016-03-11T16:02:15.685Z - info: Running on ios test: 51. RESOLVED entries are removed before WAITING state entry.

2016-03-11T16:02:16.740Z - info: Running on ios test: 52. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-11T16:02:17.568Z - info: Running on ios test: 53. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-11T16:02:18.527Z - info: Running on ios test: 54. #ThaliPeerPoolInterface - bad enqueues

2016-03-11T16:02:19.054Z - info: Running on ios test: 55. #ThaliPeerPoolInterface - do not allow same object type

2016-03-11T16:02:19.574Z - info: Running on ios test: 56. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-11T16:02:20.087Z - info: Running on ios test: 57. compareBufferArrays

2016-03-11T16:02:20.635Z - info: Running on ios test: 58. Call start twice and get error

2016-03-11T16:02:21.230Z - info: Running on ios test: 59. Start and make sure it runs

2016-03-11T16:02:21.625Z - info: Running on ios test: 60. Make sure getTimeWhenRun is right after start

2016-03-11T16:02:22.011Z - info: Running on ios test: 61. Make sure getTimeWhenRun is -1 after function is called

2016-03-11T16:02:22.369Z - info: Running on ios test: 62. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-11T16:02:22.829Z - info: Running on ios test: 63. Test TransientState

2016-03-11T16:02:23.247Z - info: Running on ios test: 64. No peers and empty database

2016-03-11T16:02:23.864Z - info: Running on ios test: 65. One peer and empty DB

2016-03-11T16:02:24.425Z - info: Running on ios test: 66. One peer with _Local set behind current seq

2016-03-11T16:02:25.097Z - info: Running on ios test: 67. One peer with _Local set equal to current seq

2016-03-11T16:02:25.892Z - info: Running on ios test: 68. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-11T16:02:27.003Z - info: Running on ios test: 69. Three peers, one not in DB, one behind and one ahead

2016-03-11T16:02:27.696Z - info: Running on ios test: 70. More than maximum peers, make sure we only send maximum allowed

2016-03-11T16:02:28.866Z - info: Running on ios test: 71. two peers with empty DB, update the doc

2016-03-11T16:02:29.626Z - info: Running on ios test: 72. add doc and make sure tokens refresh when they expire

2016-03-11T16:02:30.706Z - info: Running on ios test: 73. start and stop and start and stop

2016-03-11T16:02:31.277Z - info: Running on ios test: 74. two identical starts in a row

2016-03-11T16:02:31.910Z - info: Running on ios test: 75. two different starts in a row

2016-03-11T16:02:32.683Z - info: Running on ios test: 76. two stops and a start and two stops

2016-03-11T16:02:33.238Z - info: Running on ios test: 77. we properly enqueue requests so no then needed

2016-03-11T16:02:33.868Z - info: Running on ios test: 78. test calculateSeqPointKeyId

2016-03-11T16:02:34.311Z - info: Running on ios test: 79. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-11T16:02:34.999Z - info: Running on ios test: 80. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-11T16:02:36.018Z - info: Running on ios test: 81. messages with invalid location or USN should be ignored

2016-03-11T16:02:36.597Z - info: Running on ios test: 82. verify that Thali-specific messages are filtered correctly

2016-03-11T16:02:37.078Z - info: Running on ios test: 83. #startListeningForAdvertisements should fail if start not called

2016-03-11T16:02:37.442Z - info: Running on ios test: 84. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-11T16:02:37.829Z - info: Running on ios test: 85. #start should fail if called twice in a row

2016-03-11T16:02:38.201Z - info: Running on ios test: 86. should not be started after stop is called

2016-03-11T16:02:38.522Z - info: Running on ios test: 87. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-11T16:02:38.885Z - info: Running on ios test: 88. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-11T16:02:39.335Z - info: Running on ios test: 89. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-11T16:02:39.922Z - info: Running on ios test: 90. #stop can be called multiple times in a row

2016-03-11T16:02:40.261Z - info: Running on ios test: 91. #startListeningForAdvertisements can be called multiple times in a row

2016-03-11T16:02:40.734Z - info: Running on ios test: 92. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-11T16:02:41.147Z - info: Running on ios test: 93. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-11T16:02:41.688Z - info: Running on ios test: 94. functions are run from a queue in the right order

2016-03-11T16:02:42.253Z - info: Running on ios test: 95. #ThaliPeerPoolDefault - single action

2016-03-11T16:02:42.711Z - info: Running on ios test: 96. #ThaliPeerPoolDefault - multiple actions

2016-03-11T16:02:51.757Z - info: Test run on ios complete

2016-03-11T16:02:51.759Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-11T16:02:51.761Z - info: PLATFORM: ios
2016-03-11T16:02:51.762Z - info: RESULT: PASS
2016-03-11T16:02:51.763Z - info: 96 of 96 tests completed
2016-03-11T16:02:51.764Z - info: 96/96 passed (0 failures)
2016-03-11T16:02:51.764Z - info: --- Test Details ---


2016-03-11T16:02:51.765Z - info: 1. closeAll can close even when connections open - pass

2016-03-11T16:02:51.766Z - info: 2. closeAll with promise - pass

2016-03-11T16:02:51.771Z - info: 3. multiplex can send data - pass

2016-03-11T16:02:51.772Z - info: 4. enqueue and run in order - pass
2016-03-11T16:02:51.773Z - info: 5. enqueueAtTop and run backwards - pass

2016-03-11T16:02:51.774Z - info: 6. mix enqueue and enqueueAtTop - pass
2016-03-11T16:02:51.775Z - info: 7. queues handled independently - pass
2016-03-11T16:02:51.776Z - info: 8. basic - pass

2016-03-11T16:02:51.777Z - info: 9. another - pass
2016-03-11T16:02:51.777Z - info: 10. #startListeningForAdvertisements should fail if start not called - pass

2016-03-11T16:02:51.778Z - info: 11. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-11T16:02:51.779Z - info: 12. should be able to call #stopListeningForAdvertisements many times - pass
2016-03-11T16:02:51.780Z - info: 13. should be able to call #startListeningForAdvertisements many times - pass
2016-03-11T16:02:51.781Z - info: 14. should be able to call #startUpdateAdvertisingAndListening many times - pass
2016-03-11T16:02:51.781Z - info: 15. should be able to call #stopAdvertisingAndListening many times - pass

2016-03-11T16:02:51.782Z - info: 16. #start should fail if called twice in a row - pass
2016-03-11T16:02:51.784Z - info: 17. does not emit duplicate discoveryAdvertisingStateUpdate - pass
2016-03-11T16:02:51.788Z - info: 18. does not send duplicate availability changes - pass
2016-03-11T16:02:51.789Z - info: 19. can get the network status - pass
2016-03-11T16:02:51.790Z - info: 20. wifi peer is marked unavailable if announcements stop - pass
2016-03-11T16:02:51.791Z - info: 21. can get the network status before starting - pass
2016-03-11T16:02:51.791Z - info: 22. #generatePreambleAndBeacons bad args - pass
2016-03-11T16:02:51.792Z - info: 23. #generatePreambleAndBeacons empty keys to notify - pass
2016-03-11T16:02:51.793Z - info: 24. #generatePreambleAndBeacons multiple keys to notify - pass
2016-03-11T16:02:51.793Z - info: 25. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass
2016-03-11T16:02:51.794Z - info: 26. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass
2016-03-11T16:02:51.795Z - info: 27. #parseBeacons expiration out of range lower - pass
2016-03-11T16:02:51.795Z - info: 28. #parseBeacons expiration out of range lower - pass
2016-03-11T16:02:51.796Z - info: 29. #parseBeacons no beacons returns null - pass
2016-03-11T16:02:51.796Z - info: 30. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass
2016-03-11T16:02:51.797Z - info: 31. #parseBeacons addressBookCallback fails decrypt - pass

2016-03-11T16:02:51.798Z - info: 32. #parseBeacons addressBookCallback returns no matches - pass
2016-03-11T16:02:51.798Z - info: 33. #parseBeacons addressBookCallback returns spurious match - pass

2016-03-11T16:02:51.799Z - info: 34. #parseBeacons addressBookCallback returns public key - pass

2016-03-11T16:02:51.800Z - info: 35. #parseBeacons with beacons both for and not for the user - pass
2016-03-11T16:02:51.801Z - info: 36. Start and stop ThaliNotificationServer - pass

2016-03-11T16:02:51.802Z - info: 37. Pass an empty array to ThaliNotificationServer.start - pass
2016-03-11T16:02:51.803Z - info: 38. Pass a string to ThaliNotificationServer.start - pass
2016-03-11T16:02:51.804Z - info: 39. Pass an empty parameter to ThaliNotificationServer.start - pass
2016-03-11T16:02:51.804Z - info: 40. Make an HTTP request to /NotificationBeacons - pass
2016-03-11T16:02:51.805Z - info: 41. Make an HTTP request to /NotificationBeacons (no keys) - pass

2016-03-11T16:02:51.806Z - info: 42. Make an HTTP request to /NotificationBeacons before calling start - pass

2016-03-11T16:02:51.807Z - info: 43. #testThaliPeerAction - test getters - pass

2016-03-11T16:02:51.808Z - info: 44. #testThaliPeerAction - start and kill - pass
2016-03-11T16:02:51.809Z - info: 45. #testThaliPeerAction - double start - pass

2016-03-11T16:02:51.810Z - info: 46. #testThaliPeerAction - start after kill - pass

2016-03-11T16:02:51.811Z - info: 47. #testThaliPeerAction - make sure ids are unique - pass

2016-03-11T16:02:51.812Z - info: 48. Test PeerConnectionInformation basics - pass

2016-03-11T16:02:51.813Z - info: 49. Test PeerDictionary basic functionality - pass
2016-03-11T16:02:51.814Z - info: 50. Test PeerDictionary with multiple entries. - pass
2016-03-11T16:02:51.814Z - info: 51. RESOLVED entries are removed before WAITING state entry. - pass
2016-03-11T16:02:51.815Z - info: 52. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass

2016-03-11T16:02:51.816Z - info: 53. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass

2016-03-11T16:02:51.817Z - info: 54. #ThaliPeerPoolInterface - bad enqueues - pass
2016-03-11T16:02:51.818Z - info: 55. #ThaliPeerPoolInterface - do not allow same object type - pass

2016-03-11T16:02:51.818Z - info: 56. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass
2016-03-11T16:02:51.819Z - info: 57. compareBufferArrays - pass

2016-03-11T16:02:51.820Z - info: 58. Call start twice and get error - pass
2016-03-11T16:02:51.821Z - info: 59. Start and make sure it runs - pass
2016-03-11T16:02:51.822Z - info: 60. Make sure getTimeWhenRun is right after start - pass
2016-03-11T16:02:51.822Z - info: 61. Make sure getTimeWhenRun is -1 after function is called - pass
2016-03-11T16:02:51.823Z - info: 62. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass
2016-03-11T16:02:51.824Z - info: 63. Test TransientState - pass
2016-03-11T16:02:51.824Z - info: 64. No peers and empty database - pass
2016-03-11T16:02:51.825Z - info: 65. One peer and empty DB - pass
2016-03-11T16:02:51.826Z - info: 66. One peer with _Local set behind current seq - pass
2016-03-11T16:02:51.827Z - info: 67. One peer with _Local set equal to current seq - pass
2016-03-11T16:02:51.827Z - info: 68. One peer with _Local set ahead of current seq (and no this should not happen) - pass

2016-03-11T16:02:51.828Z - info: 69. Three peers, one not in DB, one behind and one ahead - pass
2016-03-11T16:02:51.829Z - info: 70. More than maximum peers, make sure we only send maximum allowed - pass

2016-03-11T16:02:51.829Z - info: 71. two peers with empty DB, update the doc - pass
2016-03-11T16:02:51.830Z - info: 72. add doc and make sure tokens refresh when they expire - pass
2016-03-11T16:02:51.831Z - info: 73. start and stop and start and stop - pass
2016-03-11T16:02:51.832Z - info: 74. two identical starts in a row - pass
2016-03-11T16:02:51.832Z - info: 75. two different starts in a row - pass
2016-03-11T16:02:51.833Z - info: 76. two stops and a start and two stops - pass
2016-03-11T16:02:51.834Z - info: 77. we properly enqueue requests so no then needed - pass
2016-03-11T16:02:51.834Z - info: 78. test calculateSeqPointKeyId - pass
2016-03-11T16:02:51.835Z - info: 79. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass
2016-03-11T16:02:51.836Z - info: 80. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass
2016-03-11T16:02:51.837Z - info: 81. messages with invalid location or USN should be ignored - pass
2016-03-11T16:02:51.837Z - info: 82. verify that Thali-specific messages are filtered correctly - pass
2016-03-11T16:02:51.838Z - info: 83. #startListeningForAdvertisements should fail if start not called - pass
2016-03-11T16:02:51.839Z - info: 84. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-11T16:02:51.839Z - info: 85. #start should fail if called twice in a row - pass

2016-03-11T16:02:51.840Z - info: 86. should not be started after stop is called - pass
2016-03-11T16:02:51.841Z - info: 87. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass

2016-03-11T16:02:51.842Z - info: 88. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass

2016-03-11T16:02:51.843Z - info: 89. #startUpdateAdvertisingAndListening should start hosting given router object - pass

2016-03-11T16:02:51.844Z - info: 90. #stop can be called multiple times in a row - pass

2016-03-11T16:02:51.844Z - info: 91. #startListeningForAdvertisements can be called multiple times in a row - pass
2016-03-11T16:02:51.845Z - info: 92. #stopListeningForAdvertisements can be called multiple times in a row - pass

2016-03-11T16:02:51.846Z - info: 93. #stopAdvertisingAndListening can be called multiple times in a row - pass

2016-03-11T16:02:51.847Z - info: 94. functions are run from a queue in the right order - pass

2016-03-11T16:02:51.848Z - info: 95. #ThaliPeerPoolDefault - single action - pass

2016-03-11T16:02:51.849Z - info: 96. #ThaliPeerPoolDefault - multiple actions - pass
2016-03-11T16:02:51.850Z - info: 

-== END ==-

2016-03-11T16:02:54.720Z - debug: Socket disconnected: transport close 1 (Apple-IpadAir2-1)

2016-03-11T16:02:54.728Z - debug: Socket disconnected: transport close 0 (Apple-Iphone6-1)

2016-03-11T16:21:56.568Z - debug: Socket disconnected: transport close 2 (LGE-LG-H815)


 
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
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/625090942f85e77_Make_CI_build_and_unit_tests_pass_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/625090942f85e77_Make_CI_build_and_unit_tests_pass_vjrantal/thali02_LGE-LG-D722.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/625090942f85e77_Make_CI_build_and_unit_tests_pass_vjrantal/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
STOP log received from  ZX1C223JKW Test has  FAILED
Device test finished on ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/625090942f85e77_Make_CI_build_and_unit_tests_pass_vjrantal/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:0 
child process exited with code 0 on device LGH8153b36be34 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/625090942f85e77_Make_CI_build_and_unit_tests_pass_vjrantal/thali05_LGE-LG-H815.md)

####Node name: thali06
Console output:
```
STOP log received from  7970f88c Test has  FAILED
Device test finished on 7970f88c 
STOP log received from  FA55PYS00566 Test has  FAILED
Device test finished on FA55PYS00566 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/625090942f85e77_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/625090942f85e77_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
STOP log received from  4db5c8cc Test has  FAILED
Device test finished on 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/625090942f85e77_Make_CI_build_and_unit_tests_pass_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
STOP log received from  4325e43f Test has  FAILED
Device test finished on 4325e43f 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/625090942f85e77_Make_CI_build_and_unit_tests_pass_vjrantal/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 09a9416e0297d102 app:com.test.thalitest code:0 
child process exited with code 0 on device 09a9416e0297d102 
Android task is completed. [FAILED]
```
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/625090942f85e77_Make_CI_build_and_unit_tests_pass_vjrantal/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/625090942f85e77_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/625090942f85e77_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/625090942f85e77_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/625090942f85e77_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_IpadAir2-1.md)



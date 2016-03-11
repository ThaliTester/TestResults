#### Test 62509094e6af764 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":10}}
2016-03-11T11:22:33.741Z - info: listening on *:3000

2016-03-11T11:22:34.605Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:0

2016-03-11T11:22:36.751Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:1

2016-03-11T11:22:38.137Z - debug: Device presented: samsung-SM-A500FU (android) unittest socket:3

2016-03-11T11:22:38.139Z - info: Required number of android devices presented (2)

2016-03-11T11:22:38.143Z - info: Starting unit test run for platform: android

2016-03-11T11:22:38.169Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:2

2016-03-11T11:22:38.171Z - info: Required number of ios devices presented (2)

2016-03-11T11:22:38.173Z - info: Starting unit test run for platform: ios

2016-03-11T11:22:38.394Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:4

2016-03-11T11:22:38.395Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-11T11:22:38.742Z - info: Running on ios test: 1. closeAll can close even when connections open

2016-03-11T11:22:39.002Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:5

2016-03-11T11:22:39.003Z - info: Discarding surplus device: Apple-Iphone6-1

2016-03-11T11:22:39.111Z - debug: Device presented: samsung-SM-A300FU (android) unittest socket:6

2016-03-11T11:22:39.112Z - info: Discarding surplus device: samsung-SM-A300FU

2016-03-11T11:22:39.333Z - info: Running on ios test: 2. closeAll with promise

2016-03-11T11:22:39.762Z - info: Running on ios test: 3. multiplex can send data

2016-03-11T11:22:39.846Z - debug: Socket disconnected: transport close 1 (LGE-LG-H815)

2016-03-11T11:22:40.168Z - debug: Socket disconnected: transport close 3 (samsung-SM-A500FU)

2016-03-11T11:22:40.175Z - info: Running on ios test: 4. enqueue and run in order

2016-03-11T11:22:40.802Z - info: Running on ios test: 5. enqueueAtTop and run backwards

2016-03-11T11:22:41.312Z - debug: Socket disconnected: transport close 4 (Apple-Iphone5s-1)

2016-03-11T11:22:41.338Z - info: Running on ios test: 6. mix enqueue and enqueueAtTop

2016-03-11T11:22:41.906Z - debug: Socket disconnected: transport close 5 (Apple-Iphone6-1)

2016-03-11T11:22:42.182Z - info: Running on ios test: 7. queues handled independently

2016-03-11T11:22:43.099Z - info: Running on ios test: 8. basic

2016-03-11T11:22:44.094Z - info: Running on ios test: 9. another

2016-03-11T11:22:45.139Z - info: Running on ios test: 10. #startListeningForAdvertisements should fail if start not called

2016-03-11T11:22:45.561Z - info: Running on ios test: 11. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-11T11:22:46.079Z - info: Running on ios test: 12. should be able to call #stopListeningForAdvertisements many times

2016-03-11T11:22:46.591Z - info: Running on ios test: 13. should be able to call #startListeningForAdvertisements many times

2016-03-11T11:22:47.115Z - info: Running on ios test: 14. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-11T11:22:47.458Z - info: Running on ios test: 15. should be able to call #stopAdvertisingAndListening many times

2016-03-11T11:22:48.036Z - info: Running on ios test: 16. #start should fail if called twice in a row

2016-03-11T11:22:48.524Z - info: Running on ios test: 17. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-11T11:22:48.929Z - info: Running on ios test: 18. does not send duplicate availability changes

2016-03-11T11:22:49.494Z - info: Running on ios test: 19. can get the network status

2016-03-11T11:22:50.019Z - info: Running on ios test: 20. wifi peer is marked unavailable if announcements stop

2016-03-11T11:22:51.562Z - info: Running on ios test: 21. can get the network status before starting

2016-03-11T11:22:51.895Z - info: Running on ios test: 22. #generatePreambleAndBeacons bad args

2016-03-11T11:22:52.405Z - info: Running on ios test: 23. #generatePreambleAndBeacons empty keys to notify

2016-03-11T11:22:52.733Z - info: Running on ios test: 24. #generatePreambleAndBeacons multiple keys to notify

2016-03-11T11:22:53.393Z - info: Running on ios test: 25. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-11T11:22:54.628Z - info: Running on ios test: 26. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-11T11:22:56.335Z - info: Running on ios test: 27. #parseBeacons expiration out of range lower

2016-03-11T11:22:57.175Z - info: Running on ios test: 28. #parseBeacons expiration out of range lower

2016-03-11T11:22:57.659Z - info: Running on ios test: 29. #parseBeacons no beacons returns null

2016-03-11T11:22:58.097Z - info: Running on ios test: 30. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-11T11:22:58.648Z - info: Running on ios test: 31. #parseBeacons addressBookCallback fails decrypt

2016-03-11T11:22:59.400Z - info: Running on ios test: 32. #parseBeacons addressBookCallback returns no matches

2016-03-11T11:23:00.022Z - info: Running on ios test: 33. #parseBeacons addressBookCallback returns spurious match

2016-03-11T11:23:00.595Z - info: Running on ios test: 34. #parseBeacons addressBookCallback returns public key

2016-03-11T11:23:01.193Z - info: Running on ios test: 35. #parseBeacons with beacons both for and not for the user

2016-03-11T11:23:01.680Z - info: Running on ios test: 36. Start and stop ThaliNotificationServer

2016-03-11T11:23:02.279Z - info: Running on ios test: 37. Pass an empty array to ThaliNotificationServer.start

2016-03-11T11:23:03.734Z - info: Running on ios test: 38. Pass a string to ThaliNotificationServer.start

2016-03-11T11:23:04.250Z - info: Running on ios test: 39. Pass an empty parameter to ThaliNotificationServer.start

2016-03-11T11:23:04.651Z - info: Running on ios test: 40. Make an HTTP request to /NotificationBeacons

2016-03-11T11:23:05.301Z - info: Running on ios test: 41. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-11T11:23:05.627Z - info: Running on ios test: 42. Make an HTTP request to /NotificationBeacons before calling start

2016-03-11T11:23:05.981Z - info: Running on ios test: 43. #testThaliPeerAction - test getters

2016-03-11T11:23:06.243Z - info: Running on ios test: 44. #testThaliPeerAction - start and kill

2016-03-11T11:23:06.485Z - info: Running on ios test: 45. #testThaliPeerAction - double start

2016-03-11T11:23:06.760Z - info: Running on ios test: 46. #testThaliPeerAction - start after kill

2016-03-11T11:23:07.069Z - info: Running on ios test: 47. #testThaliPeerAction - make sure ids are unique

2016-03-11T11:23:07.348Z - info: Running on ios test: 48. Test PeerConnectionInformation basics

2016-03-11T11:23:07.635Z - info: Running on ios test: 49. Test PeerDictionary basic functionality

2016-03-11T11:23:08.199Z - info: Running on ios test: 50. Test PeerDictionary with multiple entries.

2016-03-11T11:23:12.447Z - info: Running on ios test: 51. RESOLVED entries are removed before WAITING state entry.

2016-03-11T11:23:14.488Z - info: Running on ios test: 52. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-11T11:23:15.693Z - info: Running on ios test: 53. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-11T11:23:17.090Z - info: Running on ios test: 54. #ThaliPeerPoolInterface - bad enqueues

2016-03-11T11:23:17.546Z - info: Running on ios test: 55. #ThaliPeerPoolInterface - do not allow same object type

2016-03-11T11:23:17.947Z - info: Running on ios test: 56. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-11T11:23:18.313Z - info: Running on ios test: 57. compareBufferArrays

2016-03-11T11:23:18.776Z - info: Running on ios test: 58. Call start twice and get error

2016-03-11T11:23:19.071Z - info: Running on ios test: 59. Start and make sure it runs

2016-03-11T11:23:19.350Z - info: Running on ios test: 60. Make sure getTimeWhenRun is right after start

2016-03-11T11:23:19.917Z - info: Running on ios test: 61. Make sure getTimeWhenRun is -1 after function is called

2016-03-11T11:23:20.428Z - info: Running on ios test: 62. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-11T11:23:21.650Z - info: Running on ios test: 63. Test TransientState

2016-03-11T11:23:22.490Z - info: Running on ios test: 64. No peers and empty database

2016-03-11T11:23:23.197Z - info: Running on ios test: 65. One peer and empty DB

2016-03-11T11:23:23.917Z - info: Running on ios test: 66. One peer with _Local set behind current seq

2016-03-11T11:23:24.672Z - info: Running on ios test: 67. One peer with _Local set equal to current seq

2016-03-11T11:23:25.311Z - info: Running on ios test: 68. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-11T11:23:26.135Z - info: Running on ios test: 69. Three peers, one not in DB, one behind and one ahead

2016-03-11T11:23:27.081Z - info: Running on ios test: 70. More than maximum peers, make sure we only send maximum allowed

2016-03-11T11:23:28.516Z - info: Running on ios test: 71. two peers with empty DB, update the doc

2016-03-11T11:23:29.151Z - info: Running on ios test: 72. add doc and make sure tokens refresh when they expire

2016-03-11T11:23:30.209Z - info: Running on ios test: 73. start and stop and start and stop

2016-03-11T11:23:30.755Z - info: Running on ios test: 74. two identical starts in a row

2016-03-11T11:23:31.368Z - info: Running on ios test: 75. two different starts in a row

2016-03-11T11:23:32.210Z - info: Running on ios test: 76. two stops and a start and two stops

2016-03-11T11:23:33.039Z - info: Running on ios test: 77. we properly enqueue requests so no then needed

2016-03-11T11:23:33.837Z - info: Running on ios test: 78. test calculateSeqPointKeyId

2016-03-11T11:23:34.308Z - info: Running on ios test: 79. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-11T11:23:34.652Z - info: Running on ios test: 80. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-11T11:23:35.073Z - info: Running on ios test: 81. messages with invalid location or USN should be ignored

2016-03-11T11:23:35.383Z - info: Running on ios test: 82. verify that Thali-specific messages are filtered correctly

2016-03-11T11:23:35.624Z - info: Running on ios test: 83. #startListeningForAdvertisements should fail if start not called

2016-03-11T11:23:35.876Z - info: Running on ios test: 84. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-11T11:23:36.220Z - info: Running on ios test: 85. #start should fail if called twice in a row

2016-03-11T11:23:36.540Z - info: Running on ios test: 86. should not be started after stop is called

2016-03-11T11:23:36.912Z - info: Running on ios test: 87. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-11T11:23:37.251Z - info: Running on ios test: 88. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-11T11:23:37.763Z - info: Running on ios test: 89. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-11T11:23:38.255Z - info: Running on ios test: 90. #stop can be called multiple times in a row

2016-03-11T11:23:38.568Z - info: Running on ios test: 91. #startListeningForAdvertisements can be called multiple times in a row

2016-03-11T11:23:38.878Z - info: Running on ios test: 92. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-11T11:23:39.275Z - info: Running on ios test: 93. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-11T11:23:39.873Z - info: Running on ios test: 94. functions are run from a queue in the right order

2016-03-11T11:23:40.465Z - info: Running on ios test: 95. #ThaliPeerPoolDefault - single action

2016-03-11T11:23:40.816Z - info: Running on ios test: 96. #ThaliPeerPoolDefault - multiple actions

2016-03-11T11:23:41.211Z - info: Test run on ios complete

2016-03-11T11:23:41.214Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-11T11:23:41.219Z - info: PLATFORM: ios
2016-03-11T11:23:41.220Z - info: RESULT: PASS
2016-03-11T11:23:41.221Z - info: 96 of 96 tests completed
2016-03-11T11:23:41.222Z - info: 96/96 passed (0 failures)
2016-03-11T11:23:41.222Z - info: --- Test Details ---


2016-03-11T11:23:41.223Z - info: 1. closeAll can close even when connections open - pass
2016-03-11T11:23:41.224Z - info: 2. closeAll with promise - pass
2016-03-11T11:23:41.225Z - info: 3. multiplex can send data - pass
2016-03-11T11:23:41.226Z - info: 4. enqueue and run in order - pass
2016-03-11T11:23:41.226Z - info: 5. enqueueAtTop and run backwards - pass
2016-03-11T11:23:41.227Z - info: 6. mix enqueue and enqueueAtTop - pass
2016-03-11T11:23:41.228Z - info: 7. queues handled independently - pass
2016-03-11T11:23:41.228Z - info: 8. basic - pass
2016-03-11T11:23:41.229Z - info: 9. another - pass

2016-03-11T11:23:41.232Z - info: 10. #startListeningForAdvertisements should fail if start not called - pass

2016-03-11T11:23:41.236Z - info: 11. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-11T11:23:41.237Z - info: 12. should be able to call #stopListeningForAdvertisements many times - pass

2016-03-11T11:23:41.238Z - info: 13. should be able to call #startListeningForAdvertisements many times - pass
2016-03-11T11:23:41.239Z - info: 14. should be able to call #startUpdateAdvertisingAndListening many times - pass
2016-03-11T11:23:41.240Z - info: 15. should be able to call #stopAdvertisingAndListening many times - pass
2016-03-11T11:23:41.240Z - info: 16. #start should fail if called twice in a row - pass
2016-03-11T11:23:41.241Z - info: 17. does not emit duplicate discoveryAdvertisingStateUpdate - pass
2016-03-11T11:23:41.242Z - info: 18. does not send duplicate availability changes - pass

2016-03-11T11:23:41.243Z - info: 19. can get the network status - pass

2016-03-11T11:23:41.244Z - info: 20. wifi peer is marked unavailable if announcements stop - pass

2016-03-11T11:23:41.244Z - info: 21. can get the network status before starting - pass
2016-03-11T11:23:41.245Z - info: 22. #generatePreambleAndBeacons bad args - pass

2016-03-11T11:23:41.246Z - info: 23. #generatePreambleAndBeacons empty keys to notify - pass

2016-03-11T11:23:41.247Z - info: 24. #generatePreambleAndBeacons multiple keys to notify - pass

2016-03-11T11:23:41.248Z - info: 25. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass

2016-03-11T11:23:41.249Z - info: 26. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass
2016-03-11T11:23:41.250Z - info: 27. #parseBeacons expiration out of range lower - pass
2016-03-11T11:23:41.251Z - info: 28. #parseBeacons expiration out of range lower - pass
2016-03-11T11:23:41.251Z - info: 29. #parseBeacons no beacons returns null - pass

2016-03-11T11:23:41.252Z - info: 30. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass
2016-03-11T11:23:41.253Z - info: 31. #parseBeacons addressBookCallback fails decrypt - pass

2016-03-11T11:23:41.254Z - info: 32. #parseBeacons addressBookCallback returns no matches - pass

2016-03-11T11:23:41.255Z - info: 33. #parseBeacons addressBookCallback returns spurious match - pass

2016-03-11T11:23:41.256Z - info: 34. #parseBeacons addressBookCallback returns public key - pass
2016-03-11T11:23:41.257Z - info: 35. #parseBeacons with beacons both for and not for the user - pass
2016-03-11T11:23:41.257Z - info: 36. Start and stop ThaliNotificationServer - pass
2016-03-11T11:23:41.258Z - info: 37. Pass an empty array to ThaliNotificationServer.start - pass
2016-03-11T11:23:41.259Z - info: 38. Pass a string to ThaliNotificationServer.start - pass
2016-03-11T11:23:41.259Z - info: 39. Pass an empty parameter to ThaliNotificationServer.start - pass
2016-03-11T11:23:41.260Z - info: 40. Make an HTTP request to /NotificationBeacons - pass
2016-03-11T11:23:41.261Z - info: 41. Make an HTTP request to /NotificationBeacons (no keys) - pass
2016-03-11T11:23:41.261Z - info: 42. Make an HTTP request to /NotificationBeacons before calling start - pass
2016-03-11T11:23:41.262Z - info: 43. #testThaliPeerAction - test getters - pass
2016-03-11T11:23:41.263Z - info: 44. #testThaliPeerAction - start and kill - pass
2016-03-11T11:23:41.264Z - info: 45. #testThaliPeerAction - double start - pass

2016-03-11T11:23:41.264Z - info: 46. #testThaliPeerAction - start after kill - pass
2016-03-11T11:23:41.265Z - info: 47. #testThaliPeerAction - make sure ids are unique - pass

2016-03-11T11:23:41.266Z - info: 48. Test PeerConnectionInformation basics - pass

2016-03-11T11:23:41.267Z - info: 49. Test PeerDictionary basic functionality - pass

2016-03-11T11:23:41.268Z - info: 50. Test PeerDictionary with multiple entries. - pass
2016-03-11T11:23:41.269Z - info: 51. RESOLVED entries are removed before WAITING state entry. - pass

2016-03-11T11:23:41.270Z - info: 52. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass
2016-03-11T11:23:41.271Z - info: 53. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass

2016-03-11T11:23:41.279Z - info: 54. #ThaliPeerPoolInterface - bad enqueues - pass
2016-03-11T11:23:41.280Z - info: 55. #ThaliPeerPoolInterface - do not allow same object type - pass

2016-03-11T11:23:41.281Z - info: 56. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass

2016-03-11T11:23:41.282Z - info: 57. compareBufferArrays - pass

2016-03-11T11:23:41.283Z - info: 58. Call start twice and get error - pass

2016-03-11T11:23:41.284Z - info: 59. Start and make sure it runs - pass

2016-03-11T11:23:41.285Z - info: 60. Make sure getTimeWhenRun is right after start - pass

2016-03-11T11:23:41.286Z - info: 61. Make sure getTimeWhenRun is -1 after function is called - pass
2016-03-11T11:23:41.287Z - info: 62. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass

2016-03-11T11:23:41.288Z - info: 63. Test TransientState - pass

2016-03-11T11:23:41.289Z - info: 64. No peers and empty database - pass

2016-03-11T11:23:41.290Z - info: 65. One peer and empty DB - pass

2016-03-11T11:23:41.290Z - info: 66. One peer with _Local set behind current seq - pass
2016-03-11T11:23:41.291Z - info: 67. One peer with _Local set equal to current seq - pass

2016-03-11T11:23:41.292Z - info: 68. One peer with _Local set ahead of current seq (and no this should not happen) - pass

2016-03-11T11:23:41.293Z - info: 69. Three peers, one not in DB, one behind and one ahead - pass

2016-03-11T11:23:41.295Z - info: 70. More than maximum peers, make sure we only send maximum allowed - pass

2016-03-11T11:23:41.296Z - info: 71. two peers with empty DB, update the doc - pass

2016-03-11T11:23:41.297Z - info: 72. add doc and make sure tokens refresh when they expire - pass
2016-03-11T11:23:41.298Z - info: 73. start and stop and start and stop - pass

2016-03-11T11:23:41.299Z - info: 74. two identical starts in a row - pass

2016-03-11T11:23:41.300Z - info: 75. two different starts in a row - pass

2016-03-11T11:23:41.300Z - info: 76. two stops and a start and two stops - pass

2016-03-11T11:23:41.301Z - info: 77. we properly enqueue requests so no then needed - pass
2016-03-11T11:23:41.302Z - info: 78. test calculateSeqPointKeyId - pass

2016-03-11T11:23:41.303Z - info: 79. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass

2016-03-11T11:23:41.304Z - info: 80. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-03-11T11:23:41.305Z - info: 81. messages with invalid location or USN should be ignored - pass

2016-03-11T11:23:41.306Z - info: 82. verify that Thali-specific messages are filtered correctly - pass

2016-03-11T11:23:41.307Z - info: 83. #startListeningForAdvertisements should fail if start not called - pass

2016-03-11T11:23:41.308Z - info: 84. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-11T11:23:41.309Z - info: 85. #start should fail if called twice in a row - pass

2016-03-11T11:23:41.310Z - info: 86. should not be started after stop is called - pass

2016-03-11T11:23:41.310Z - info: 87. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass

2016-03-11T11:23:41.311Z - info: 88. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass

2016-03-11T11:23:41.312Z - info: 89. #startUpdateAdvertisingAndListening should start hosting given router object - pass

2016-03-11T11:23:41.313Z - info: 90. #stop can be called multiple times in a row - pass

2016-03-11T11:23:41.314Z - info: 91. #startListeningForAdvertisements can be called multiple times in a row - pass
2016-03-11T11:23:41.315Z - info: 92. #stopListeningForAdvertisements can be called multiple times in a row - pass

2016-03-11T11:23:41.316Z - info: 93. #stopAdvertisingAndListening can be called multiple times in a row - pass

2016-03-11T11:23:41.317Z - info: 94. functions are run from a queue in the right order - pass
2016-03-11T11:23:41.317Z - info: 95. #ThaliPeerPoolDefault - single action - pass

2016-03-11T11:23:41.318Z - info: 96. #ThaliPeerPoolDefault - multiple actions - pass
2016-03-11T11:23:41.319Z - info: 

-== END ==-

2016-03-11T11:23:44.253Z - debug: Socket disconnected: transport close 0 (Apple-IpadAir2-1)

2016-03-11T11:23:44.867Z - debug: Socket disconnected: transport close 2 (Apple-Iphone5-1)


 
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
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62509094e6af764_Make_CI_build_and_unit_tests_pass_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/62509094e6af764_Make_CI_build_and_unit_tests_pass_vjrantal/thali02_LGE-LG-D722.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/62509094e6af764_Make_CI_build_and_unit_tests_pass_vjrantal/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/62509094e6af764_Make_CI_build_and_unit_tests_pass_vjrantal/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:0 
child process exited with code 0 on device LGH8153b36be34 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/62509094e6af764_Make_CI_build_and_unit_tests_pass_vjrantal/thali05_LGE-LG-H815.md)

####Node name: thali06
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:null 
child process exited with code null on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:null 
child process exited with code null on device FA55PYS00566 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62509094e6af764_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/62509094e6af764_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:0 
child process exited with code 0 on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62509094e6af764_Make_CI_build_and_unit_tests_pass_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:0 
child process exited with code 0 on device 4325e43f 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62509094e6af764_Make_CI_build_and_unit_tests_pass_vjrantal/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 09a9416e0297d102 app:com.test.thalitest code:0 
child process exited with code 0 on device 09a9416e0297d102 
Android task is completed. [FAILED]
```
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/62509094e6af764_Make_CI_build_and_unit_tests_pass_vjrantal/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/62509094e6af764_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/62509094e6af764_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/62509094e6af764_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/62509094e6af764_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone6-1.md)



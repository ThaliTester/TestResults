#### Test 62509094cfda267 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":10}}
2016-03-14T08:54:47.985Z - info: listening on *:3000

2016-03-14T08:54:49.425Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:1

2016-03-14T08:54:50.366Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:2

2016-03-14T08:54:50.870Z - debug: Device presented: samsung-SM-A300FU (android) unittest socket:3

2016-03-14T08:54:50.872Z - info: Required number of android devices presented (2)

2016-03-14T08:54:50.876Z - info: Starting unit test run for platform: android

2016-03-14T08:54:51.274Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:0

2016-03-14T08:54:51.275Z - info: Required number of ios devices presented (2)

2016-03-14T08:54:51.277Z - info: Starting unit test run for platform: ios

2016-03-14T08:54:51.774Z - info: Running on ios test: 1. closeAll can close even when connections open

2016-03-14T08:54:52.179Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:4

2016-03-14T08:54:52.180Z - info: Discarding surplus device: Apple-Iphone5-1

2016-03-14T08:54:52.226Z - info: Running on ios test: 2. closeAll with promise

2016-03-14T08:54:52.358Z - debug: Socket disconnected: transport close 1 (LGE-LG-H815)

2016-03-14T08:54:52.519Z - info: Running on ios test: 3. multiplex can send data

2016-03-14T08:54:52.727Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:5

2016-03-14T08:54:52.728Z - info: Discarding surplus device: Apple-Iphone6-1

2016-03-14T08:54:52.913Z - info: Running on ios test: 4. enqueue and run in order

2016-03-14T08:54:53.438Z - info: Running on ios test: 5. enqueueAtTop and run backwards

2016-03-14T08:54:53.722Z - info: Running on ios test: 6. mix enqueue and enqueueAtTop

2016-03-14T08:54:54.166Z - info: Running on ios test: 7. queues handled independently

2016-03-14T08:54:54.471Z - info: Running on ios test: 8. basic

2016-03-14T08:54:54.779Z - info: Running on ios test: 9. another

2016-03-14T08:54:55.110Z - info: Running on ios test: 10. #startListeningForAdvertisements should fail if start not called

2016-03-14T08:54:55.278Z - debug: Socket disconnected: transport close 4 (Apple-Iphone5-1)

2016-03-14T08:54:55.428Z - debug: Socket disconnected: transport close 5 (Apple-Iphone6-1)

2016-03-14T08:54:55.538Z - info: Running on ios test: 11. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-14T08:54:55.785Z - info: Running on ios test: 12. should be able to call #stopListeningForAdvertisements many times

2016-03-14T08:54:56.053Z - info: Running on ios test: 13. should be able to call #startListeningForAdvertisements many times

2016-03-14T08:54:56.417Z - info: Running on ios test: 14. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-14T08:54:56.769Z - info: Running on ios test: 15. should be able to call #stopAdvertisingAndListening many times

2016-03-14T08:54:57.050Z - info: Running on ios test: 16. #start should fail if called twice in a row

2016-03-14T08:54:57.378Z - info: Running on ios test: 17. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-14T08:54:57.779Z - info: Running on ios test: 18. does not send duplicate availability changes

2016-03-14T08:54:58.030Z - info: Running on ios test: 19. can get the network status

2016-03-14T08:54:58.309Z - info: Running on ios test: 20. wifi peer is marked unavailable if announcements stop

2016-03-14T08:54:59.546Z - info: Running on ios test: 21. can get the network status before starting

2016-03-14T08:54:59.802Z - info: Running on ios test: 22. #generatePreambleAndBeacons bad args

2016-03-14T08:55:00.074Z - info: Running on ios test: 23. #generatePreambleAndBeacons empty keys to notify

2016-03-14T08:55:00.408Z - info: Running on ios test: 24. #generatePreambleAndBeacons multiple keys to notify

2016-03-14T08:55:00.701Z - info: Running on ios test: 25. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-14T08:55:01.025Z - info: Running on ios test: 26. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-14T08:55:01.310Z - info: Running on ios test: 27. #parseBeacons expiration out of range lower

2016-03-14T08:55:01.653Z - info: Running on ios test: 28. #parseBeacons expiration out of range lower

2016-03-14T08:55:01.951Z - info: Running on ios test: 29. #parseBeacons no beacons returns null

2016-03-14T08:55:02.187Z - info: Running on ios test: 30. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-14T08:55:02.458Z - info: Running on ios test: 31. #parseBeacons addressBookCallback fails decrypt

2016-03-14T08:55:02.825Z - info: Running on ios test: 32. #parseBeacons addressBookCallback returns no matches

2016-03-14T08:55:03.134Z - info: Running on ios test: 33. #parseBeacons addressBookCallback returns spurious match

2016-03-14T08:55:03.431Z - info: Running on ios test: 34. #parseBeacons addressBookCallback returns public key

2016-03-14T08:55:03.710Z - info: Running on ios test: 35. #parseBeacons with beacons both for and not for the user

2016-03-14T08:55:03.993Z - info: Running on ios test: 36. Start and stop ThaliNotificationServer

2016-03-14T08:55:04.303Z - info: Running on ios test: 37. Pass an empty array to ThaliNotificationServer.start

2016-03-14T08:55:04.733Z - info: Running on ios test: 38. Pass a string to ThaliNotificationServer.start

2016-03-14T08:55:04.927Z - debug: Socket disconnected: transport close 3 (samsung-SM-A300FU)

2016-03-14T08:55:05.020Z - info: Running on ios test: 39. Pass an empty parameter to ThaliNotificationServer.start

2016-03-14T08:55:05.316Z - info: Running on ios test: 40. Make an HTTP request to /NotificationBeacons

2016-03-14T08:55:05.708Z - info: Running on ios test: 41. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-14T08:55:05.968Z - info: Running on ios test: 42. Make an HTTP request to /NotificationBeacons before calling start

2016-03-14T08:55:06.268Z - info: Running on ios test: 43. #testThaliPeerAction - test getters

2016-03-14T08:55:06.618Z - info: Running on ios test: 44. #testThaliPeerAction - start and kill

2016-03-14T08:55:06.892Z - info: Running on ios test: 45. #testThaliPeerAction - double start

2016-03-14T08:55:07.231Z - info: Running on ios test: 46. #testThaliPeerAction - start after kill

2016-03-14T08:55:07.557Z - info: Running on ios test: 47. #testThaliPeerAction - make sure ids are unique

2016-03-14T08:55:07.917Z - info: Running on ios test: 48. Test PeerConnectionInformation basics

2016-03-14T08:55:08.193Z - info: Running on ios test: 49. Test PeerDictionary basic functionality

2016-03-14T08:55:08.618Z - info: Running on ios test: 50. Test PeerDictionary with multiple entries.

2016-03-14T08:55:10.017Z - info: Running on ios test: 51. RESOLVED entries are removed before WAITING state entry.

2016-03-14T08:55:10.930Z - info: Running on ios test: 52. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-14T08:55:11.714Z - info: Running on ios test: 53. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-14T08:55:12.447Z - info: Running on ios test: 54. #ThaliPeerPoolInterface - bad enqueues

2016-03-14T08:55:12.659Z - info: Running on ios test: 55. #ThaliPeerPoolInterface - do not allow same object type

2016-03-14T08:55:12.951Z - info: Running on ios test: 56. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-14T08:55:13.236Z - info: Running on ios test: 57. compareBufferArrays

2016-03-14T08:55:13.652Z - info: Running on ios test: 58. Call start twice and get error

2016-03-14T08:55:13.871Z - info: Running on ios test: 59. Start and make sure it runs

2016-03-14T08:55:14.126Z - info: Running on ios test: 60. Make sure getTimeWhenRun is right after start

2016-03-14T08:55:14.405Z - info: Running on ios test: 61. Make sure getTimeWhenRun is -1 after function is called

2016-03-14T08:55:14.707Z - info: Running on ios test: 62. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-14T08:55:15.141Z - info: Running on ios test: 63. Test TransientState

2016-03-14T08:55:15.406Z - info: Running on ios test: 64. No peers and empty database

2016-03-14T08:55:15.856Z - info: Running on ios test: 65. One peer and empty DB

2016-03-14T08:55:16.238Z - info: Running on ios test: 66. One peer with _Local set behind current seq

2016-03-14T08:55:16.727Z - info: Running on ios test: 67. One peer with _Local set equal to current seq

2016-03-14T08:55:17.201Z - info: Running on ios test: 68. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-14T08:55:17.658Z - info: Running on ios test: 69. Three peers, one not in DB, one behind and one ahead

2016-03-14T08:55:18.360Z - info: Running on ios test: 70. More than maximum peers, make sure we only send maximum allowed

2016-03-14T08:55:19.423Z - info: Running on ios test: 71. two peers with empty DB, update the doc

2016-03-14T08:55:20.006Z - info: Running on ios test: 72. add doc and make sure tokens refresh when they expire

2016-03-14T08:55:20.860Z - info: Running on ios test: 73. start and stop and start and stop

2016-03-14T08:55:21.365Z - info: Running on ios test: 74. two identical starts in a row

2016-03-14T08:55:21.777Z - info: Running on ios test: 75. two different starts in a row

2016-03-14T08:55:22.237Z - info: Running on ios test: 76. two stops and a start and two stops

2016-03-14T08:55:22.707Z - info: Running on ios test: 77. we properly enqueue requests so no then needed

2016-03-14T08:55:23.212Z - info: Running on ios test: 78. test calculateSeqPointKeyId

2016-03-14T08:55:23.471Z - info: Running on ios test: 79. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-14T08:55:23.729Z - info: Running on ios test: 80. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-14T08:55:24.114Z - info: Running on ios test: 81. messages with invalid location or USN should be ignored

2016-03-14T08:55:24.343Z - info: Running on ios test: 82. verify that Thali-specific messages are filtered correctly

2016-03-14T08:55:24.565Z - info: Running on ios test: 83. #startListeningForAdvertisements should fail if start not called

2016-03-14T08:55:24.814Z - info: Running on ios test: 84. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-14T08:55:25.031Z - info: Running on ios test: 85. #start should fail if called twice in a row

2016-03-14T08:55:25.290Z - info: Running on ios test: 86. should not be started after stop is called

2016-03-14T08:55:25.512Z - info: Running on ios test: 87. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-14T08:55:25.745Z - info: Running on ios test: 88. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-14T08:55:26.039Z - info: Running on ios test: 89. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-14T08:55:26.386Z - info: Running on ios test: 90. #stop can be called multiple times in a row

2016-03-14T08:55:26.603Z - info: Running on ios test: 91. #startListeningForAdvertisements can be called multiple times in a row

2016-03-14T08:55:26.830Z - info: Running on ios test: 92. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-14T08:55:27.062Z - info: Running on ios test: 93. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-14T08:55:27.310Z - info: Running on ios test: 94. functions are run from a queue in the right order

2016-03-14T08:55:27.580Z - info: Running on ios test: 95. #ThaliPeerPoolDefault - single action

2016-03-14T08:55:27.790Z - info: Running on ios test: 96. #ThaliPeerPoolDefault - multiple actions

2016-03-14T08:55:28.008Z - info: Test run on ios complete

2016-03-14T08:55:28.010Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-14T08:55:28.012Z - info: PLATFORM: ios

2016-03-14T08:55:28.013Z - info: RESULT: PASS

2016-03-14T08:55:28.019Z - info: 96 of 96 tests completed
2016-03-14T08:55:28.019Z - info: 96/96 passed (0 failures)
2016-03-14T08:55:28.020Z - info: --- Test Details ---


2016-03-14T08:55:28.021Z - info: 1. closeAll can close even when connections open - pass
2016-03-14T08:55:28.022Z - info: 2. closeAll with promise - pass
2016-03-14T08:55:28.023Z - info: 3. multiplex can send data - pass
2016-03-14T08:55:28.023Z - info: 4. enqueue and run in order - pass
2016-03-14T08:55:28.024Z - info: 5. enqueueAtTop and run backwards - pass
2016-03-14T08:55:28.024Z - info: 6. mix enqueue and enqueueAtTop - pass
2016-03-14T08:55:28.025Z - info: 7. queues handled independently - pass
2016-03-14T08:55:28.026Z - info: 8. basic - pass
2016-03-14T08:55:28.027Z - info: 9. another - pass
2016-03-14T08:55:28.028Z - info: 10. #startListeningForAdvertisements should fail if start not called - pass
2016-03-14T08:55:28.028Z - info: 11. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-14T08:55:28.031Z - info: 12. should be able to call #stopListeningForAdvertisements many times - pass

2016-03-14T08:55:28.035Z - info: 13. should be able to call #startListeningForAdvertisements many times - pass
2016-03-14T08:55:28.036Z - info: 14. should be able to call #startUpdateAdvertisingAndListening many times - pass

2016-03-14T08:55:28.037Z - info: 15. should be able to call #stopAdvertisingAndListening many times - pass

2016-03-14T08:55:28.038Z - info: 16. #start should fail if called twice in a row - pass
2016-03-14T08:55:28.038Z - info: 17. does not emit duplicate discoveryAdvertisingStateUpdate - pass
2016-03-14T08:55:28.039Z - info: 18. does not send duplicate availability changes - pass
2016-03-14T08:55:28.040Z - info: 19. can get the network status - pass
2016-03-14T08:55:28.040Z - info: 20. wifi peer is marked unavailable if announcements stop - pass

2016-03-14T08:55:28.041Z - info: 21. can get the network status before starting - pass
2016-03-14T08:55:28.042Z - info: 22. #generatePreambleAndBeacons bad args - pass

2016-03-14T08:55:28.043Z - info: 23. #generatePreambleAndBeacons empty keys to notify - pass

2016-03-14T08:55:28.044Z - info: 24. #generatePreambleAndBeacons multiple keys to notify - pass

2016-03-14T08:55:28.045Z - info: 25. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass

2016-03-14T08:55:28.046Z - info: 26. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass

2016-03-14T08:55:28.047Z - info: 27. #parseBeacons expiration out of range lower - pass
2016-03-14T08:55:28.048Z - info: 28. #parseBeacons expiration out of range lower - pass

2016-03-14T08:55:28.049Z - info: 29. #parseBeacons no beacons returns null - pass
2016-03-14T08:55:28.050Z - info: 30. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass
2016-03-14T08:55:28.051Z - info: 31. #parseBeacons addressBookCallback fails decrypt - pass

2016-03-14T08:55:28.052Z - info: 32. #parseBeacons addressBookCallback returns no matches - pass
2016-03-14T08:55:28.052Z - info: 33. #parseBeacons addressBookCallback returns spurious match - pass

2016-03-14T08:55:28.053Z - info: 34. #parseBeacons addressBookCallback returns public key - pass

2016-03-14T08:55:28.054Z - info: 35. #parseBeacons with beacons both for and not for the user - pass
2016-03-14T08:55:28.055Z - info: 36. Start and stop ThaliNotificationServer - pass

2016-03-14T08:55:28.056Z - info: 37. Pass an empty array to ThaliNotificationServer.start - pass
2016-03-14T08:55:28.057Z - info: 38. Pass a string to ThaliNotificationServer.start - pass

2016-03-14T08:55:28.058Z - info: 39. Pass an empty parameter to ThaliNotificationServer.start - pass

2016-03-14T08:55:28.073Z - info: 40. Make an HTTP request to /NotificationBeacons - pass

2016-03-14T08:55:28.080Z - info: 41. Make an HTTP request to /NotificationBeacons (no keys) - pass

2016-03-14T08:55:28.081Z - info: 42. Make an HTTP request to /NotificationBeacons before calling start - pass

2016-03-14T08:55:28.082Z - info: 43. #testThaliPeerAction - test getters - pass
2016-03-14T08:55:28.083Z - info: 44. #testThaliPeerAction - start and kill - pass
2016-03-14T08:55:28.084Z - info: 45. #testThaliPeerAction - double start - pass
2016-03-14T08:55:28.085Z - info: 46. #testThaliPeerAction - start after kill - pass
2016-03-14T08:55:28.086Z - info: 47. #testThaliPeerAction - make sure ids are unique - pass
2016-03-14T08:55:28.087Z - info: 48. Test PeerConnectionInformation basics - pass
2016-03-14T08:55:28.088Z - info: 49. Test PeerDictionary basic functionality - pass
2016-03-14T08:55:28.089Z - info: 50. Test PeerDictionary with multiple entries. - pass
2016-03-14T08:55:28.089Z - info: 51. RESOLVED entries are removed before WAITING state entry. - pass
2016-03-14T08:55:28.090Z - info: 52. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass
2016-03-14T08:55:28.091Z - info: 53. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass
2016-03-14T08:55:28.092Z - info: 54. #ThaliPeerPoolInterface - bad enqueues - pass

2016-03-14T08:55:28.092Z - info: 55. #ThaliPeerPoolInterface - do not allow same object type - pass
2016-03-14T08:55:28.093Z - info: 56. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass
2016-03-14T08:55:28.094Z - info: 57. compareBufferArrays - pass

2016-03-14T08:55:28.095Z - info: 58. Call start twice and get error - pass

2016-03-14T08:55:28.096Z - info: 59. Start and make sure it runs - pass

2016-03-14T08:55:28.097Z - info: 60. Make sure getTimeWhenRun is right after start - pass

2016-03-14T08:55:28.098Z - info: 61. Make sure getTimeWhenRun is -1 after function is called - pass

2016-03-14T08:55:28.099Z - info: 62. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass

2016-03-14T08:55:28.100Z - info: 63. Test TransientState - pass

2016-03-14T08:55:28.101Z - info: 64. No peers and empty database - pass

2016-03-14T08:55:28.102Z - info: 65. One peer and empty DB - pass

2016-03-14T08:55:28.109Z - info: 66. One peer with _Local set behind current seq - pass

2016-03-14T08:55:28.110Z - info: 67. One peer with _Local set equal to current seq - pass

2016-03-14T08:55:28.111Z - info: 68. One peer with _Local set ahead of current seq (and no this should not happen) - pass

2016-03-14T08:55:28.112Z - info: 69. Three peers, one not in DB, one behind and one ahead - pass

2016-03-14T08:55:28.113Z - info: 70. More than maximum peers, make sure we only send maximum allowed - pass

2016-03-14T08:55:28.114Z - info: 71. two peers with empty DB, update the doc - pass

2016-03-14T08:55:28.115Z - info: 72. add doc and make sure tokens refresh when they expire - pass

2016-03-14T08:55:28.116Z - info: 73. start and stop and start and stop - pass

2016-03-14T08:55:28.117Z - info: 74. two identical starts in a row - pass

2016-03-14T08:55:28.118Z - info: 75. two different starts in a row - pass
2016-03-14T08:55:28.119Z - info: 76. two stops and a start and two stops - pass

2016-03-14T08:55:28.120Z - info: 77. we properly enqueue requests so no then needed - pass

2016-03-14T08:55:28.121Z - info: 78. test calculateSeqPointKeyId - pass

2016-03-14T08:55:28.122Z - info: 79. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass

2016-03-14T08:55:28.123Z - info: 80. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-03-14T08:55:28.124Z - info: 81. messages with invalid location or USN should be ignored - pass

2016-03-14T08:55:28.125Z - info: 82. verify that Thali-specific messages are filtered correctly - pass

2016-03-14T08:55:28.126Z - info: 83. #startListeningForAdvertisements should fail if start not called - pass

2016-03-14T08:55:28.127Z - info: 84. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-14T08:55:28.128Z - info: 85. #start should fail if called twice in a row - pass

2016-03-14T08:55:28.128Z - info: 86. should not be started after stop is called - pass

2016-03-14T08:55:28.129Z - info: 87. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass

2016-03-14T08:55:28.130Z - info: 88. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass

2016-03-14T08:55:28.131Z - info: 89. #startUpdateAdvertisingAndListening should start hosting given router object - pass
2016-03-14T08:55:28.132Z - info: 90. #stop can be called multiple times in a row - pass

2016-03-14T08:55:28.133Z - info: 91. #startListeningForAdvertisements can be called multiple times in a row - pass

2016-03-14T08:55:28.133Z - info: 92. #stopListeningForAdvertisements can be called multiple times in a row - pass

2016-03-14T08:55:28.134Z - info: 93. #stopAdvertisingAndListening can be called multiple times in a row - pass
2016-03-14T08:55:28.135Z - info: 94. functions are run from a queue in the right order - pass

2016-03-14T08:55:28.136Z - info: 95. #ThaliPeerPoolDefault - single action - pass

2016-03-14T08:55:28.137Z - info: 96. #ThaliPeerPoolDefault - multiple actions - pass

2016-03-14T08:55:28.138Z - info: 

-== END ==-

2016-03-14T08:55:30.928Z - debug: Socket disconnected: transport close 2 (Apple-IpadAir2-1)

2016-03-14T08:55:31.416Z - debug: Socket disconnected: transport close 0 (Apple-Iphone5s-1)


 
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
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62509094cfda267_Make_CI_build_and_unit_tests_pass_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/62509094cfda267_Make_CI_build_and_unit_tests_pass_vjrantal/thali02_LGE-LG-D722.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/62509094cfda267_Make_CI_build_and_unit_tests_pass_vjrantal/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
STOP log received from  ZX1C223JKW Test has  FAILED
Device test finished on ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/62509094cfda267_Make_CI_build_and_unit_tests_pass_vjrantal/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:0 
child process exited with code 0 on device LGH8153b36be34 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/62509094cfda267_Make_CI_build_and_unit_tests_pass_vjrantal/thali05_LGE-LG-H815.md)

####Node name: thali06
Console output:
```
STOP log received from  FA55PYS00566 Test has  FAILED
Device test finished on FA55PYS00566 
STOP log received from  7970f88c Test has  FAILED
Device test finished on 7970f88c 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62509094cfda267_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/62509094cfda267_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
STOP log received from  4db5c8cc Test has  FAILED
Device test finished on 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62509094cfda267_Make_CI_build_and_unit_tests_pass_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:0 
child process exited with code 0 on device 4325e43f 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62509094cfda267_Make_CI_build_and_unit_tests_pass_vjrantal/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 09a9416e0297d102 app:com.test.thalitest code:0 
child process exited with code 0 on device 09a9416e0297d102 
Android task is completed. [FAILED]
```
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/62509094cfda267_Make_CI_build_and_unit_tests_pass_vjrantal/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/62509094cfda267_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/62509094cfda267_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/62509094cfda267_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/62509094cfda267_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_IpadAir2-1.md)



#### Test 62509094c3227b2 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":10}}
2016-03-14T05:46:43.767Z - info: listening on *:3000

2016-03-14T05:46:44.597Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:0

2016-03-14T05:46:45.568Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:1

2016-03-14T05:46:46.399Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:2

2016-03-14T05:46:46.401Z - info: Required number of ios devices presented (2)

2016-03-14T05:46:46.406Z - info: Starting unit test run for platform: ios

2016-03-14T05:46:46.736Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:3

2016-03-14T05:46:46.737Z - info: Discarding surplus device: Apple-Iphone6-1

2016-03-14T05:46:46.892Z - info: Running on ios test: 1. closeAll can close even when connections open

2016-03-14T05:46:47.292Z - info: Running on ios test: 2. closeAll with promise

2016-03-14T05:46:47.519Z - info: Running on ios test: 3. multiplex can send data

2016-03-14T05:46:47.834Z - info: Running on ios test: 4. enqueue and run in order

2016-03-14T05:46:48.318Z - info: Running on ios test: 5. enqueueAtTop and run backwards

2016-03-14T05:46:48.552Z - info: Running on ios test: 6. mix enqueue and enqueueAtTop

2016-03-14T05:46:48.715Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:4

2016-03-14T05:46:48.716Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-14T05:46:48.841Z - info: Running on ios test: 7. queues handled independently

2016-03-14T05:46:49.083Z - info: Running on ios test: 8. basic

2016-03-14T05:46:49.317Z - info: Running on ios test: 9. another

2016-03-14T05:46:49.423Z - debug: Socket disconnected: transport close 3 (Apple-Iphone6-1)

2016-03-14T05:46:49.657Z - info: Running on ios test: 10. #startListeningForAdvertisements should fail if start not called

2016-03-14T05:46:49.924Z - info: Running on ios test: 11. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-14T05:46:50.274Z - info: Running on ios test: 12. should be able to call #stopListeningForAdvertisements many times

2016-03-14T05:46:50.691Z - info: Running on ios test: 13. should be able to call #startListeningForAdvertisements many times

2016-03-14T05:46:51.034Z - info: Running on ios test: 14. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-14T05:46:51.226Z - debug: Socket disconnected: transport close 4 (Apple-Iphone5s-1)

2016-03-14T05:46:51.347Z - info: Running on ios test: 15. should be able to call #stopAdvertisingAndListening many times

2016-03-14T05:46:51.653Z - info: Running on ios test: 16. #start should fail if called twice in a row

2016-03-14T05:46:52.002Z - info: Running on ios test: 17. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-14T05:46:52.278Z - info: Running on ios test: 18. does not send duplicate availability changes

2016-03-14T05:46:52.524Z - info: Running on ios test: 19. can get the network status

2016-03-14T05:46:52.753Z - info: Running on ios test: 20. wifi peer is marked unavailable if announcements stop

2016-03-14T05:46:54.013Z - info: Running on ios test: 21. can get the network status before starting

2016-03-14T05:46:54.284Z - info: Running on ios test: 22. #generatePreambleAndBeacons bad args

2016-03-14T05:46:54.569Z - info: Running on ios test: 23. #generatePreambleAndBeacons empty keys to notify

2016-03-14T05:46:54.854Z - info: Running on ios test: 24. #generatePreambleAndBeacons multiple keys to notify

2016-03-14T05:46:55.225Z - info: Running on ios test: 25. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-14T05:46:55.499Z - info: Running on ios test: 26. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-14T05:46:55.812Z - info: Running on ios test: 27. #parseBeacons expiration out of range lower

2016-03-14T05:46:56.087Z - info: Running on ios test: 28. #parseBeacons expiration out of range lower

2016-03-14T05:46:56.375Z - info: Running on ios test: 29. #parseBeacons no beacons returns null

2016-03-14T05:46:56.664Z - info: Running on ios test: 30. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-14T05:46:56.918Z - info: Running on ios test: 31. #parseBeacons addressBookCallback fails decrypt

2016-03-14T05:46:57.245Z - info: Running on ios test: 32. #parseBeacons addressBookCallback returns no matches

2016-03-14T05:46:57.551Z - info: Running on ios test: 33. #parseBeacons addressBookCallback returns spurious match

2016-03-14T05:46:58.048Z - info: Running on ios test: 34. #parseBeacons addressBookCallback returns public key

2016-03-14T05:46:58.382Z - info: Running on ios test: 35. #parseBeacons with beacons both for and not for the user

2016-03-14T05:46:58.762Z - info: Running on ios test: 36. Start and stop ThaliNotificationServer

2016-03-14T05:46:59.106Z - info: Running on ios test: 37. Pass an empty array to ThaliNotificationServer.start

2016-03-14T05:46:59.434Z - info: Running on ios test: 38. Pass a string to ThaliNotificationServer.start

2016-03-14T05:46:59.741Z - info: Running on ios test: 39. Pass an empty parameter to ThaliNotificationServer.start

2016-03-14T05:47:00.026Z - info: Running on ios test: 40. Make an HTTP request to /NotificationBeacons

2016-03-14T05:47:00.522Z - info: Running on ios test: 41. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-14T05:47:00.846Z - info: Running on ios test: 42. Make an HTTP request to /NotificationBeacons before calling start

2016-03-14T05:47:01.215Z - info: Running on ios test: 43. #testThaliPeerAction - test getters

2016-03-14T05:47:01.465Z - info: Running on ios test: 44. #testThaliPeerAction - start and kill

2016-03-14T05:47:01.700Z - info: Running on ios test: 45. #testThaliPeerAction - double start

2016-03-14T05:47:02.006Z - info: Running on ios test: 46. #testThaliPeerAction - start after kill

2016-03-14T05:47:02.262Z - info: Running on ios test: 47. #testThaliPeerAction - make sure ids are unique

2016-03-14T05:47:02.614Z - info: Running on ios test: 48. Test PeerConnectionInformation basics

2016-03-14T05:47:02.906Z - info: Running on ios test: 49. Test PeerDictionary basic functionality

2016-03-14T05:47:03.311Z - info: Running on ios test: 50. Test PeerDictionary with multiple entries.

2016-03-14T05:47:06.459Z - info: Running on ios test: 51. RESOLVED entries are removed before WAITING state entry.

2016-03-14T05:47:07.939Z - info: Running on ios test: 52. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-14T05:47:09.193Z - info: Running on ios test: 53. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-14T05:47:10.430Z - info: Running on ios test: 54. #ThaliPeerPoolInterface - bad enqueues

2016-03-14T05:47:10.713Z - info: Running on ios test: 55. #ThaliPeerPoolInterface - do not allow same object type

2016-03-14T05:47:11.060Z - info: Running on ios test: 56. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-14T05:47:11.509Z - info: Running on ios test: 57. compareBufferArrays

2016-03-14T05:47:11.928Z - info: Running on ios test: 58. Call start twice and get error

2016-03-14T05:47:12.259Z - info: Running on ios test: 59. Start and make sure it runs

2016-03-14T05:47:12.560Z - info: Running on ios test: 60. Make sure getTimeWhenRun is right after start

2016-03-14T05:47:12.963Z - info: Running on ios test: 61. Make sure getTimeWhenRun is -1 after function is called

2016-03-14T05:47:13.356Z - info: Running on ios test: 62. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-14T05:47:13.772Z - info: Running on ios test: 63. Test TransientState

2016-03-14T05:47:14.125Z - info: Running on ios test: 64. No peers and empty database

2016-03-14T05:47:14.594Z - info: Running on ios test: 65. One peer and empty DB

2016-03-14T05:47:15.119Z - info: Running on ios test: 66. One peer with _Local set behind current seq

2016-03-14T05:47:15.830Z - info: Running on ios test: 67. One peer with _Local set equal to current seq

2016-03-14T05:47:16.545Z - info: Running on ios test: 68. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-14T05:47:17.173Z - info: Running on ios test: 69. Three peers, one not in DB, one behind and one ahead

2016-03-14T05:47:17.972Z - info: Running on ios test: 70. More than maximum peers, make sure we only send maximum allowed

2016-03-14T05:47:19.233Z - info: Running on ios test: 71. two peers with empty DB, update the doc

2016-03-14T05:47:19.940Z - info: Running on ios test: 72. add doc and make sure tokens refresh when they expire

2016-03-14T05:47:20.966Z - info: Running on ios test: 73. start and stop and start and stop

2016-03-14T05:47:21.598Z - info: Running on ios test: 74. two identical starts in a row

2016-03-14T05:47:22.200Z - info: Running on ios test: 75. two different starts in a row

2016-03-14T05:47:22.833Z - info: Running on ios test: 76. two stops and a start and two stops

2016-03-14T05:47:23.399Z - info: Running on ios test: 77. we properly enqueue requests so no then needed

2016-03-14T05:47:24.091Z - info: Running on ios test: 78. test calculateSeqPointKeyId

2016-03-14T05:47:24.437Z - info: Running on ios test: 79. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-14T05:47:24.839Z - info: Running on ios test: 80. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-14T05:47:25.301Z - info: Running on ios test: 81. messages with invalid location or USN should be ignored

2016-03-14T05:47:25.695Z - info: Running on ios test: 82. verify that Thali-specific messages are filtered correctly

2016-03-14T05:47:26.094Z - info: Running on ios test: 83. #startListeningForAdvertisements should fail if start not called

2016-03-14T05:47:26.443Z - info: Running on ios test: 84. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-14T05:47:26.759Z - info: Running on ios test: 85. #start should fail if called twice in a row

2016-03-14T05:47:27.092Z - info: Running on ios test: 86. should not be started after stop is called

2016-03-14T05:47:27.435Z - info: Running on ios test: 87. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-14T05:47:27.776Z - info: Running on ios test: 88. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-14T05:47:28.134Z - info: Running on ios test: 89. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-14T05:47:28.619Z - info: Running on ios test: 90. #stop can be called multiple times in a row

2016-03-14T05:47:28.902Z - info: Running on ios test: 91. #startListeningForAdvertisements can be called multiple times in a row

2016-03-14T05:47:29.291Z - info: Running on ios test: 92. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-14T05:47:29.683Z - info: Running on ios test: 93. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-14T05:47:29.998Z - info: Running on ios test: 94. functions are run from a queue in the right order

2016-03-14T05:47:30.435Z - info: Running on ios test: 95. #ThaliPeerPoolDefault - single action

2016-03-14T05:47:31.431Z - info: Running on ios test: 96. #ThaliPeerPoolDefault - multiple actions

2016-03-14T05:47:31.835Z - info: Test run on ios complete

2016-03-14T05:47:31.838Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-14T05:47:31.840Z - info: PLATFORM: ios
2016-03-14T05:47:31.841Z - info: RESULT: PASS
2016-03-14T05:47:31.842Z - info: 96 of 96 tests completed
2016-03-14T05:47:31.842Z - info: 96/96 passed (0 failures)
2016-03-14T05:47:31.843Z - info: --- Test Details ---


2016-03-14T05:47:31.844Z - info: 1. closeAll can close even when connections open - pass

2016-03-14T05:47:31.845Z - info: 2. closeAll with promise - pass

2016-03-14T05:47:31.850Z - info: 3. multiplex can send data - pass

2016-03-14T05:47:31.851Z - info: 4. enqueue and run in order - pass
2016-03-14T05:47:31.852Z - info: 5. enqueueAtTop and run backwards - pass

2016-03-14T05:47:31.852Z - info: 6. mix enqueue and enqueueAtTop - pass
2016-03-14T05:47:31.853Z - info: 7. queues handled independently - pass
2016-03-14T05:47:31.854Z - info: 8. basic - pass
2016-03-14T05:47:31.855Z - info: 9. another - pass

2016-03-14T05:47:31.855Z - info: 10. #startListeningForAdvertisements should fail if start not called - pass

2016-03-14T05:47:31.856Z - info: 11. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-14T05:47:31.857Z - info: 12. should be able to call #stopListeningForAdvertisements many times - pass
2016-03-14T05:47:31.858Z - info: 13. should be able to call #startListeningForAdvertisements many times - pass
2016-03-14T05:47:31.859Z - info: 14. should be able to call #startUpdateAdvertisingAndListening many times - pass
2016-03-14T05:47:31.860Z - info: 15. should be able to call #stopAdvertisingAndListening many times - pass

2016-03-14T05:47:31.860Z - info: 16. #start should fail if called twice in a row - pass
2016-03-14T05:47:31.863Z - info: 17. does not emit duplicate discoveryAdvertisingStateUpdate - pass
2016-03-14T05:47:31.867Z - info: 18. does not send duplicate availability changes - pass
2016-03-14T05:47:31.868Z - info: 19. can get the network status - pass
2016-03-14T05:47:31.868Z - info: 20. wifi peer is marked unavailable if announcements stop - pass
2016-03-14T05:47:31.869Z - info: 21. can get the network status before starting - pass
2016-03-14T05:47:31.870Z - info: 22. #generatePreambleAndBeacons bad args - pass
2016-03-14T05:47:31.870Z - info: 23. #generatePreambleAndBeacons empty keys to notify - pass
2016-03-14T05:47:31.871Z - info: 24. #generatePreambleAndBeacons multiple keys to notify - pass
2016-03-14T05:47:31.872Z - info: 25. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass
2016-03-14T05:47:31.872Z - info: 26. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass
2016-03-14T05:47:31.873Z - info: 27. #parseBeacons expiration out of range lower - pass
2016-03-14T05:47:31.874Z - info: 28. #parseBeacons expiration out of range lower - pass
2016-03-14T05:47:31.874Z - info: 29. #parseBeacons no beacons returns null - pass
2016-03-14T05:47:31.875Z - info: 30. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass

2016-03-14T05:47:31.875Z - info: 31. #parseBeacons addressBookCallback fails decrypt - pass
2016-03-14T05:47:31.876Z - info: 32. #parseBeacons addressBookCallback returns no matches - pass

2016-03-14T05:47:31.877Z - info: 33. #parseBeacons addressBookCallback returns spurious match - pass

2016-03-14T05:47:31.878Z - info: 34. #parseBeacons addressBookCallback returns public key - pass
2016-03-14T05:47:31.879Z - info: 35. #parseBeacons with beacons both for and not for the user - pass

2016-03-14T05:47:31.880Z - info: 36. Start and stop ThaliNotificationServer - pass
2016-03-14T05:47:31.881Z - info: 37. Pass an empty array to ThaliNotificationServer.start - pass
2016-03-14T05:47:31.881Z - info: 38. Pass a string to ThaliNotificationServer.start - pass
2016-03-14T05:47:31.882Z - info: 39. Pass an empty parameter to ThaliNotificationServer.start - pass
2016-03-14T05:47:31.883Z - info: 40. Make an HTTP request to /NotificationBeacons - pass

2016-03-14T05:47:31.884Z - info: 41. Make an HTTP request to /NotificationBeacons (no keys) - pass

2016-03-14T05:47:31.884Z - info: 42. Make an HTTP request to /NotificationBeacons before calling start - pass

2016-03-14T05:47:31.886Z - info: 43. #testThaliPeerAction - test getters - pass

2016-03-14T05:47:31.886Z - info: 44. #testThaliPeerAction - start and kill - pass

2016-03-14T05:47:31.887Z - info: 45. #testThaliPeerAction - double start - pass

2016-03-14T05:47:31.889Z - info: 46. #testThaliPeerAction - start after kill - pass

2016-03-14T05:47:31.890Z - info: 47. #testThaliPeerAction - make sure ids are unique - pass
2016-03-14T05:47:31.890Z - info: 48. Test PeerConnectionInformation basics - pass
2016-03-14T05:47:31.891Z - info: 49. Test PeerDictionary basic functionality - pass
2016-03-14T05:47:31.892Z - info: 50. Test PeerDictionary with multiple entries. - pass

2016-03-14T05:47:31.893Z - info: 51. RESOLVED entries are removed before WAITING state entry. - pass

2016-03-14T05:47:31.894Z - info: 52. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass
2016-03-14T05:47:31.895Z - info: 53. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass

2016-03-14T05:47:31.896Z - info: 54. #ThaliPeerPoolInterface - bad enqueues - pass

2016-03-14T05:47:31.897Z - info: 55. #ThaliPeerPoolInterface - do not allow same object type - pass
2016-03-14T05:47:31.897Z - info: 56. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass
2016-03-14T05:47:31.898Z - info: 57. compareBufferArrays - pass
2016-03-14T05:47:31.899Z - info: 58. Call start twice and get error - pass
2016-03-14T05:47:31.899Z - info: 59. Start and make sure it runs - pass
2016-03-14T05:47:31.900Z - info: 60. Make sure getTimeWhenRun is right after start - pass
2016-03-14T05:47:31.900Z - info: 61. Make sure getTimeWhenRun is -1 after function is called - pass
2016-03-14T05:47:31.901Z - info: 62. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass
2016-03-14T05:47:31.902Z - info: 63. Test TransientState - pass
2016-03-14T05:47:31.902Z - info: 64. No peers and empty database - pass
2016-03-14T05:47:31.903Z - info: 65. One peer and empty DB - pass

2016-03-14T05:47:31.904Z - info: 66. One peer with _Local set behind current seq - pass
2016-03-14T05:47:31.905Z - info: 67. One peer with _Local set equal to current seq - pass

2016-03-14T05:47:31.906Z - info: 68. One peer with _Local set ahead of current seq (and no this should not happen) - pass
2016-03-14T05:47:31.907Z - info: 69. Three peers, one not in DB, one behind and one ahead - pass
2016-03-14T05:47:31.908Z - info: 70. More than maximum peers, make sure we only send maximum allowed - pass
2016-03-14T05:47:31.908Z - info: 71. two peers with empty DB, update the doc - pass
2016-03-14T05:47:31.909Z - info: 72. add doc and make sure tokens refresh when they expire - pass
2016-03-14T05:47:31.910Z - info: 73. start and stop and start and stop - pass
2016-03-14T05:47:31.911Z - info: 74. two identical starts in a row - pass
2016-03-14T05:47:31.912Z - info: 75. two different starts in a row - pass
2016-03-14T05:47:31.913Z - info: 76. two stops and a start and two stops - pass
2016-03-14T05:47:31.913Z - info: 77. we properly enqueue requests so no then needed - pass
2016-03-14T05:47:31.915Z - info: 78. test calculateSeqPointKeyId - pass

2016-03-14T05:47:31.916Z - info: 79. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass
2016-03-14T05:47:31.917Z - info: 80. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-03-14T05:47:31.918Z - info: 81. messages with invalid location or USN should be ignored - pass

2016-03-14T05:47:31.919Z - info: 82. verify that Thali-specific messages are filtered correctly - pass

2016-03-14T05:47:31.919Z - info: 83. #startListeningForAdvertisements should fail if start not called - pass
2016-03-14T05:47:31.920Z - info: 84. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-14T05:47:31.921Z - info: 85. #start should fail if called twice in a row - pass

2016-03-14T05:47:31.922Z - info: 86. should not be started after stop is called - pass

2016-03-14T05:47:31.923Z - info: 87. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass
2016-03-14T05:47:31.923Z - info: 88. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass

2016-03-14T05:47:31.924Z - info: 89. #startUpdateAdvertisingAndListening should start hosting given router object - pass

2016-03-14T05:47:31.925Z - info: 90. #stop can be called multiple times in a row - pass

2016-03-14T05:47:31.926Z - info: 91. #startListeningForAdvertisements can be called multiple times in a row - pass
2016-03-14T05:47:31.927Z - info: 92. #stopListeningForAdvertisements can be called multiple times in a row - pass

2016-03-14T05:47:31.927Z - info: 93. #stopAdvertisingAndListening can be called multiple times in a row - pass

2016-03-14T05:47:31.928Z - info: 94. functions are run from a queue in the right order - pass

2016-03-14T05:47:31.929Z - info: 95. #ThaliPeerPoolDefault - single action - pass

2016-03-14T05:47:31.930Z - info: 96. #ThaliPeerPoolDefault - multiple actions - pass

2016-03-14T05:47:31.931Z - info: 

-== END ==-

2016-03-14T05:47:34.731Z - debug: Socket disconnected: transport close 0 (Apple-IpadAir2-1)

2016-03-14T05:47:35.203Z - debug: Socket disconnected: transport close 2 (Apple-Iphone5-1)

2016-03-14T06:06:51.717Z - debug: Socket disconnected: transport close 1 (LGE-LG-H815)


 
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
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62509094c3227b2_Make_CI_build_and_unit_tests_pass_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/62509094c3227b2_Make_CI_build_and_unit_tests_pass_vjrantal/thali02_LGE-LG-D722.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/62509094c3227b2_Make_CI_build_and_unit_tests_pass_vjrantal/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
STOP log received from  ZX1C223JKW Test has  FAILED
Device test finished on ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/62509094c3227b2_Make_CI_build_and_unit_tests_pass_vjrantal/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:0 
child process exited with code 0 on device LGH8153b36be34 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/62509094c3227b2_Make_CI_build_and_unit_tests_pass_vjrantal/thali05_LGE-LG-H815.md)

####Node name: thali06
Console output:
```
STOP log received from  FA55PYS00566 Test has  FAILED
STOP log received from  7970f88c Test has  FAILED
Device test finished on FA55PYS00566 
Device test finished on 7970f88c 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62509094c3227b2_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/62509094c3227b2_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
STOP log received from  4db5c8cc Test has  FAILED
Device test finished on 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62509094c3227b2_Make_CI_build_and_unit_tests_pass_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
STOP log received from  4325e43f Test has  FAILED
Device test finished on 4325e43f 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62509094c3227b2_Make_CI_build_and_unit_tests_pass_vjrantal/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 09a9416e0297d102 app:com.test.thalitest code:0 
child process exited with code 0 on device 09a9416e0297d102 
Android task is completed. [FAILED]
```
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/62509094c3227b2_Make_CI_build_and_unit_tests_pass_vjrantal/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/62509094c3227b2_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/62509094c3227b2_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/62509094c3227b2_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/62509094c3227b2_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_IpadAir2-1.md)



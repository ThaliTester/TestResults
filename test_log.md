#### Test 62509094ffd3875 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":10}}
2016-03-11T10:07:45.340Z - info: listening on *:3000

2016-03-11T10:07:46.614Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:0

2016-03-11T10:07:46.842Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:1

2016-03-11T10:07:46.844Z - info: Required number of ios devices presented (2)

2016-03-11T10:07:46.848Z - info: Starting unit test run for platform: ios

2016-03-11T10:07:47.238Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:2

2016-03-11T10:07:47.299Z - info: Running on ios test: 1. closeAll can close even when connections open

2016-03-11T10:07:47.747Z - info: Running on ios test: 2. closeAll with promise

2016-03-11T10:07:48.060Z - info: Running on ios test: 3. multiplex can send data

2016-03-11T10:07:48.406Z - info: Running on ios test: 4. enqueue and run in order

2016-03-11T10:07:48.994Z - info: Running on ios test: 5. enqueueAtTop and run backwards

2016-03-11T10:07:49.643Z - info: Running on ios test: 6. mix enqueue and enqueueAtTop

2016-03-11T10:07:49.975Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:4

2016-03-11T10:07:49.976Z - info: Discarding surplus device: Apple-Iphone5-1

2016-03-11T10:07:49.982Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:3

2016-03-11T10:07:49.983Z - info: Discarding surplus device: Apple-IpadAir2-1

2016-03-11T10:07:50.508Z - info: Running on ios test: 7. queues handled independently

2016-03-11T10:07:51.217Z - info: Running on ios test: 8. basic

2016-03-11T10:07:52.431Z - info: Running on ios test: 9. another

2016-03-11T10:07:52.618Z - debug: Socket disconnected: transport close 3 (Apple-IpadAir2-1)

2016-03-11T10:07:53.166Z - debug: Socket disconnected: transport close 4 (Apple-Iphone5-1)

2016-03-11T10:07:53.176Z - info: Running on ios test: 10. #startListeningForAdvertisements should fail if start not called

2016-03-11T10:07:54.426Z - info: Running on ios test: 11. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-11T10:07:55.198Z - info: Running on ios test: 12. should be able to call #stopListeningForAdvertisements many times

2016-03-11T10:07:55.598Z - info: Running on ios test: 13. should be able to call #startListeningForAdvertisements many times

2016-03-11T10:07:55.902Z - info: Running on ios test: 14. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-11T10:07:56.332Z - info: Running on ios test: 15. should be able to call #stopAdvertisingAndListening many times

2016-03-11T10:07:56.679Z - info: Running on ios test: 16. #start should fail if called twice in a row

2016-03-11T10:07:57.190Z - info: Running on ios test: 17. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-11T10:07:57.638Z - info: Running on ios test: 18. does not send duplicate availability changes

2016-03-11T10:07:57.990Z - info: Running on ios test: 19. can get the network status

2016-03-11T10:07:58.370Z - info: Running on ios test: 20. wifi peer is marked unavailable if announcements stop

2016-03-11T10:07:59.877Z - info: Running on ios test: 21. can get the network status before starting

2016-03-11T10:08:00.295Z - info: Running on ios test: 22. #generatePreambleAndBeacons bad args

2016-03-11T10:08:00.737Z - info: Running on ios test: 23. #generatePreambleAndBeacons empty keys to notify

2016-03-11T10:08:01.248Z - info: Running on ios test: 24. #generatePreambleAndBeacons multiple keys to notify

2016-03-11T10:08:01.823Z - info: Running on ios test: 25. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-11T10:08:02.039Z - info: Running on ios test: 26. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-11T10:08:02.362Z - info: Running on ios test: 27. #parseBeacons expiration out of range lower

2016-03-11T10:08:02.636Z - info: Running on ios test: 28. #parseBeacons expiration out of range lower

2016-03-11T10:08:02.958Z - info: Running on ios test: 29. #parseBeacons no beacons returns null

2016-03-11T10:08:03.438Z - info: Running on ios test: 30. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-11T10:08:03.898Z - info: Running on ios test: 31. #parseBeacons addressBookCallback fails decrypt

2016-03-11T10:08:04.461Z - info: Running on ios test: 32. #parseBeacons addressBookCallback returns no matches

2016-03-11T10:08:05.056Z - info: Running on ios test: 33. #parseBeacons addressBookCallback returns spurious match

2016-03-11T10:08:05.469Z - info: Running on ios test: 34. #parseBeacons addressBookCallback returns public key

2016-03-11T10:08:05.895Z - info: Running on ios test: 35. #parseBeacons with beacons both for and not for the user

2016-03-11T10:08:06.444Z - info: Running on ios test: 36. Start and stop ThaliNotificationServer

2016-03-11T10:08:06.909Z - info: Running on ios test: 37. Pass an empty array to ThaliNotificationServer.start

2016-03-11T10:08:07.367Z - info: Running on ios test: 38. Pass a string to ThaliNotificationServer.start

2016-03-11T10:08:07.655Z - info: Running on ios test: 39. Pass an empty parameter to ThaliNotificationServer.start

2016-03-11T10:08:07.947Z - info: Running on ios test: 40. Make an HTTP request to /NotificationBeacons

2016-03-11T10:08:08.432Z - info: Running on ios test: 41. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-11T10:08:08.765Z - info: Running on ios test: 42. Make an HTTP request to /NotificationBeacons before calling start

2016-03-11T10:08:09.310Z - info: Running on ios test: 43. #testThaliPeerAction - test getters

2016-03-11T10:08:09.886Z - info: Running on ios test: 44. #testThaliPeerAction - start and kill

2016-03-11T10:08:10.521Z - info: Running on ios test: 45. #testThaliPeerAction - double start

2016-03-11T10:08:11.056Z - info: Running on ios test: 46. #testThaliPeerAction - start after kill

2016-03-11T10:08:11.917Z - info: Running on ios test: 47. #testThaliPeerAction - make sure ids are unique

2016-03-11T10:08:12.510Z - info: Running on ios test: 48. Test PeerConnectionInformation basics

2016-03-11T10:08:13.058Z - info: Running on ios test: 49. Test PeerDictionary basic functionality

2016-03-11T10:08:13.601Z - info: Running on ios test: 50. Test PeerDictionary with multiple entries.

2016-03-11T10:08:15.217Z - info: Running on ios test: 51. RESOLVED entries are removed before WAITING state entry.

2016-03-11T10:08:16.372Z - info: Running on ios test: 52. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-11T10:08:17.648Z - info: Running on ios test: 53. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-11T10:08:19.421Z - info: Running on ios test: 54. #ThaliPeerPoolInterface - bad enqueues

2016-03-11T10:08:19.760Z - info: Running on ios test: 55. #ThaliPeerPoolInterface - do not allow same object type

2016-03-11T10:08:20.189Z - info: Running on ios test: 56. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-11T10:08:20.856Z - info: Running on ios test: 57. compareBufferArrays

2016-03-11T10:08:21.446Z - info: Running on ios test: 58. Call start twice and get error

2016-03-11T10:08:21.780Z - info: Running on ios test: 59. Start and make sure it runs

2016-03-11T10:08:22.058Z - info: Running on ios test: 60. Make sure getTimeWhenRun is right after start

2016-03-11T10:08:22.473Z - info: Running on ios test: 61. Make sure getTimeWhenRun is -1 after function is called

2016-03-11T10:08:22.795Z - info: Running on ios test: 62. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-11T10:08:23.087Z - info: Running on ios test: 63. Test TransientState

2016-03-11T10:08:23.458Z - info: Running on ios test: 64. No peers and empty database

2016-03-11T10:08:24.026Z - info: Running on ios test: 65. One peer and empty DB

2016-03-11T10:08:24.479Z - info: Running on ios test: 66. One peer with _Local set behind current seq

2016-03-11T10:08:24.971Z - info: Running on ios test: 67. One peer with _Local set equal to current seq

2016-03-11T10:08:25.653Z - info: Running on ios test: 68. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-11T10:08:26.253Z - info: Running on ios test: 69. Three peers, one not in DB, one behind and one ahead

2016-03-11T10:08:27.079Z - info: Running on ios test: 70. More than maximum peers, make sure we only send maximum allowed

2016-03-11T10:08:28.130Z - info: Running on ios test: 71. two peers with empty DB, update the doc

2016-03-11T10:08:28.807Z - info: Running on ios test: 72. add doc and make sure tokens refresh when they expire

2016-03-11T10:08:29.794Z - info: Running on ios test: 73. start and stop and start and stop

2016-03-11T10:08:30.468Z - info: Running on ios test: 74. two identical starts in a row

2016-03-11T10:08:30.925Z - info: Running on ios test: 75. two different starts in a row

2016-03-11T10:08:31.417Z - info: Running on ios test: 76. two stops and a start and two stops

2016-03-11T10:08:31.854Z - info: Running on ios test: 77. we properly enqueue requests so no then needed

2016-03-11T10:08:32.280Z - info: Running on ios test: 78. test calculateSeqPointKeyId

2016-03-11T10:08:32.591Z - info: Running on ios test: 79. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-11T10:08:33.017Z - info: Running on ios test: 80. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-11T10:08:33.413Z - info: Running on ios test: 81. messages with invalid location or USN should be ignored

2016-03-11T10:08:33.770Z - info: Running on ios test: 82. verify that Thali-specific messages are filtered correctly

2016-03-11T10:08:34.228Z - info: Running on ios test: 83. #startListeningForAdvertisements should fail if start not called

2016-03-11T10:08:34.721Z - info: Running on ios test: 84. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-11T10:08:35.011Z - info: Running on ios test: 85. #start should fail if called twice in a row

2016-03-11T10:08:35.292Z - info: Running on ios test: 86. should not be started after stop is called

2016-03-11T10:08:35.569Z - info: Running on ios test: 87. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-11T10:08:35.846Z - info: Running on ios test: 88. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-11T10:08:36.278Z - info: Running on ios test: 89. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-11T10:08:36.615Z - info: Running on ios test: 90. #stop can be called multiple times in a row

2016-03-11T10:08:36.891Z - info: Running on ios test: 91. #startListeningForAdvertisements can be called multiple times in a row

2016-03-11T10:08:37.212Z - info: Running on ios test: 92. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-11T10:08:37.469Z - info: Running on ios test: 93. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-11T10:08:37.751Z - info: Running on ios test: 94. functions are run from a queue in the right order

2016-03-11T10:08:38.052Z - info: Running on ios test: 95. #ThaliPeerPoolDefault - single action

2016-03-11T10:08:38.299Z - info: Running on ios test: 96. #ThaliPeerPoolDefault - multiple actions

2016-03-11T10:08:38.590Z - info: Test run on ios complete

2016-03-11T10:08:38.592Z - info: 

-== UNIT TEST RESULTS ==-
2016-03-11T10:08:38.594Z - info: PLATFORM: ios

2016-03-11T10:08:38.594Z - info: RESULT: PASS
2016-03-11T10:08:38.595Z - info: 96 of 96 tests completed
2016-03-11T10:08:38.596Z - info: 96/96 passed (0 failures)
2016-03-11T10:08:38.597Z - info: --- Test Details ---


2016-03-11T10:08:38.598Z - info: 1. closeAll can close even when connections open - pass

2016-03-11T10:08:38.598Z - info: 2. closeAll with promise - pass

2016-03-11T10:08:38.603Z - info: 3. multiplex can send data - pass

2016-03-11T10:08:38.604Z - info: 4. enqueue and run in order - pass
2016-03-11T10:08:38.605Z - info: 5. enqueueAtTop and run backwards - pass

2016-03-11T10:08:38.605Z - info: 6. mix enqueue and enqueueAtTop - pass
2016-03-11T10:08:38.606Z - info: 7. queues handled independently - pass
2016-03-11T10:08:38.607Z - info: 8. basic - pass
2016-03-11T10:08:38.608Z - info: 9. another - pass

2016-03-11T10:08:38.608Z - info: 10. #startListeningForAdvertisements should fail if start not called - pass
2016-03-11T10:08:38.609Z - info: 11. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-11T10:08:38.610Z - info: 12. should be able to call #stopListeningForAdvertisements many times - pass
2016-03-11T10:08:38.610Z - info: 13. should be able to call #startListeningForAdvertisements many times - pass
2016-03-11T10:08:38.611Z - info: 14. should be able to call #startUpdateAdvertisingAndListening many times - pass
2016-03-11T10:08:38.612Z - info: 15. should be able to call #stopAdvertisingAndListening many times - pass
2016-03-11T10:08:38.613Z - info: 16. #start should fail if called twice in a row - pass

2016-03-11T10:08:38.615Z - info: 17. does not emit duplicate discoveryAdvertisingStateUpdate - pass
2016-03-11T10:08:38.620Z - info: 18. does not send duplicate availability changes - pass
2016-03-11T10:08:38.621Z - info: 19. can get the network status - pass
2016-03-11T10:08:38.622Z - info: 20. wifi peer is marked unavailable if announcements stop - pass
2016-03-11T10:08:38.622Z - info: 21. can get the network status before starting - pass
2016-03-11T10:08:38.623Z - info: 22. #generatePreambleAndBeacons bad args - pass
2016-03-11T10:08:38.623Z - info: 23. #generatePreambleAndBeacons empty keys to notify - pass
2016-03-11T10:08:38.624Z - info: 24. #generatePreambleAndBeacons multiple keys to notify - pass
2016-03-11T10:08:38.625Z - info: 25. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass
2016-03-11T10:08:38.625Z - info: 26. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass
2016-03-11T10:08:38.626Z - info: 27. #parseBeacons expiration out of range lower - pass
2016-03-11T10:08:38.626Z - info: 28. #parseBeacons expiration out of range lower - pass
2016-03-11T10:08:38.627Z - info: 29. #parseBeacons no beacons returns null - pass
2016-03-11T10:08:38.628Z - info: 30. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass

2016-03-11T10:08:38.628Z - info: 31. #parseBeacons addressBookCallback fails decrypt - pass
2016-03-11T10:08:38.629Z - info: 32. #parseBeacons addressBookCallback returns no matches - pass
2016-03-11T10:08:38.629Z - info: 33. #parseBeacons addressBookCallback returns spurious match - pass

2016-03-11T10:08:38.630Z - info: 34. #parseBeacons addressBookCallback returns public key - pass

2016-03-11T10:08:38.631Z - info: 35. #parseBeacons with beacons both for and not for the user - pass
2016-03-11T10:08:38.632Z - info: 36. Start and stop ThaliNotificationServer - pass

2016-03-11T10:08:38.633Z - info: 37. Pass an empty array to ThaliNotificationServer.start - pass
2016-03-11T10:08:38.633Z - info: 38. Pass a string to ThaliNotificationServer.start - pass
2016-03-11T10:08:38.634Z - info: 39. Pass an empty parameter to ThaliNotificationServer.start - pass
2016-03-11T10:08:38.635Z - info: 40. Make an HTTP request to /NotificationBeacons - pass
2016-03-11T10:08:38.635Z - info: 41. Make an HTTP request to /NotificationBeacons (no keys) - pass

2016-03-11T10:08:38.636Z - info: 42. Make an HTTP request to /NotificationBeacons before calling start - pass
2016-03-11T10:08:38.637Z - info: 43. #testThaliPeerAction - test getters - pass

2016-03-11T10:08:38.638Z - info: 44. #testThaliPeerAction - start and kill - pass

2016-03-11T10:08:38.639Z - info: 45. #testThaliPeerAction - double start - pass

2016-03-11T10:08:38.640Z - info: 46. #testThaliPeerAction - start after kill - pass
2016-03-11T10:08:38.640Z - info: 47. #testThaliPeerAction - make sure ids are unique - pass

2016-03-11T10:08:38.641Z - info: 48. Test PeerConnectionInformation basics - pass

2016-03-11T10:08:38.642Z - info: 49. Test PeerDictionary basic functionality - pass

2016-03-11T10:08:38.643Z - info: 50. Test PeerDictionary with multiple entries. - pass
2016-03-11T10:08:38.644Z - info: 51. RESOLVED entries are removed before WAITING state entry. - pass
2016-03-11T10:08:38.644Z - info: 52. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass
2016-03-11T10:08:38.645Z - info: 53. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass

2016-03-11T10:08:38.646Z - info: 54. #ThaliPeerPoolInterface - bad enqueues - pass
2016-03-11T10:08:38.646Z - info: 55. #ThaliPeerPoolInterface - do not allow same object type - pass

2016-03-11T10:08:38.647Z - info: 56. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass

2016-03-11T10:08:38.648Z - info: 57. compareBufferArrays - pass
2016-03-11T10:08:38.649Z - info: 58. Call start twice and get error - pass

2016-03-11T10:08:38.650Z - info: 59. Start and make sure it runs - pass
2016-03-11T10:08:38.650Z - info: 60. Make sure getTimeWhenRun is right after start - pass
2016-03-11T10:08:38.651Z - info: 61. Make sure getTimeWhenRun is -1 after function is called - pass
2016-03-11T10:08:38.652Z - info: 62. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass
2016-03-11T10:08:38.652Z - info: 63. Test TransientState - pass
2016-03-11T10:08:38.653Z - info: 64. No peers and empty database - pass
2016-03-11T10:08:38.653Z - info: 65. One peer and empty DB - pass
2016-03-11T10:08:38.654Z - info: 66. One peer with _Local set behind current seq - pass
2016-03-11T10:08:38.654Z - info: 67. One peer with _Local set equal to current seq - pass
2016-03-11T10:08:38.655Z - info: 68. One peer with _Local set ahead of current seq (and no this should not happen) - pass
2016-03-11T10:08:38.655Z - info: 69. Three peers, one not in DB, one behind and one ahead - pass
2016-03-11T10:08:38.656Z - info: 70. More than maximum peers, make sure we only send maximum allowed - pass

2016-03-11T10:08:38.657Z - info: 71. two peers with empty DB, update the doc - pass

2016-03-11T10:08:38.664Z - info: 72. add doc and make sure tokens refresh when they expire - pass
2016-03-11T10:08:38.665Z - info: 73. start and stop and start and stop - pass
2016-03-11T10:08:38.666Z - info: 74. two identical starts in a row - pass
2016-03-11T10:08:38.666Z - info: 75. two different starts in a row - pass
2016-03-11T10:08:38.667Z - info: 76. two stops and a start and two stops - pass
2016-03-11T10:08:38.668Z - info: 77. we properly enqueue requests so no then needed - pass
2016-03-11T10:08:38.670Z - info: 78. test calculateSeqPointKeyId - pass
2016-03-11T10:08:38.671Z - info: 79. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass
2016-03-11T10:08:38.671Z - info: 80. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass
2016-03-11T10:08:38.672Z - info: 81. messages with invalid location or USN should be ignored - pass
2016-03-11T10:08:38.673Z - info: 82. verify that Thali-specific messages are filtered correctly - pass
2016-03-11T10:08:38.673Z - info: 83. #startListeningForAdvertisements should fail if start not called - pass

2016-03-11T10:08:38.674Z - info: 84. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-11T10:08:38.675Z - info: 85. #start should fail if called twice in a row - pass

2016-03-11T10:08:38.676Z - info: 86. should not be started after stop is called - pass

2016-03-11T10:08:38.677Z - info: 87. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass
2016-03-11T10:08:38.677Z - info: 88. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass

2016-03-11T10:08:38.678Z - info: 89. #startUpdateAdvertisingAndListening should start hosting given router object - pass

2016-03-11T10:08:38.679Z - info: 90. #stop can be called multiple times in a row - pass

2016-03-11T10:08:38.680Z - info: 91. #startListeningForAdvertisements can be called multiple times in a row - pass
2016-03-11T10:08:38.681Z - info: 92. #stopListeningForAdvertisements can be called multiple times in a row - pass

2016-03-11T10:08:38.681Z - info: 93. #stopAdvertisingAndListening can be called multiple times in a row - pass

2016-03-11T10:08:38.682Z - info: 94. functions are run from a queue in the right order - pass

2016-03-11T10:08:38.683Z - info: 95. #ThaliPeerPoolDefault - single action - pass

2016-03-11T10:08:38.684Z - info: 96. #ThaliPeerPoolDefault - multiple actions - pass

2016-03-11T10:08:38.685Z - info: 

-== END ==-

2016-03-11T10:08:41.180Z - debug: Socket disconnected: transport close 0 (Apple-Iphone6-1)

2016-03-11T10:08:41.539Z - debug: Socket disconnected: transport close 1 (Apple-Iphone5s-1)

2016-03-11T10:28:13.826Z - debug: Socket disconnected: transport close 2 (LGE-LG-H815)


 
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
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62509094ffd3875_Make_CI_build_and_unit_tests_pass_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/62509094ffd3875_Make_CI_build_and_unit_tests_pass_vjrantal/thali02_LGE-LG-D722.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/62509094ffd3875_Make_CI_build_and_unit_tests_pass_vjrantal/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/62509094ffd3875_Make_CI_build_and_unit_tests_pass_vjrantal/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:0 
child process exited with code 0 on device LGH8153b36be34 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/62509094ffd3875_Make_CI_build_and_unit_tests_pass_vjrantal/thali05_LGE-LG-H815.md)

####Node name: thali06
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:0 
child process exited with code 0 on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:null 
child process exited with code null on device FA55PYS00566 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62509094ffd3875_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/62509094ffd3875_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:0 
child process exited with code 0 on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62509094ffd3875_Make_CI_build_and_unit_tests_pass_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:0 
child process exited with code 0 on device 4325e43f 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62509094ffd3875_Make_CI_build_and_unit_tests_pass_vjrantal/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 09a9416e0297d102 app:com.test.thalitest code:0 
child process exited with code 0 on device 09a9416e0297d102 
Android task is completed. [FAILED]
```
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/62509094ffd3875_Make_CI_build_and_unit_tests_pass_vjrantal/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/62509094ffd3875_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/62509094ffd3875_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/62509094ffd3875_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/62509094ffd3875_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone6-1.md)



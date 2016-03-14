#### Test 62560673a3c76e9 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":10}}
2016-03-14T11:18:46.011Z - info: listening on *:3000

2016-03-14T11:18:48.057Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:1

2016-03-14T11:18:49.643Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:0

2016-03-14T11:18:50.064Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:2

2016-03-14T11:18:50.066Z - info: Required number of android devices presented (2)

2016-03-14T11:18:50.070Z - info: Starting unit test run for platform: android

2016-03-14T11:18:50.110Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:3

2016-03-14T11:18:50.111Z - info: Required number of ios devices presented (2)

2016-03-14T11:18:50.113Z - info: Starting unit test run for platform: ios

2016-03-14T11:18:50.182Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:4

2016-03-14T11:18:50.183Z - info: Discarding surplus device: Apple-IpadAir2-1

2016-03-14T11:18:50.653Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:5

2016-03-14T11:18:50.654Z - info: Discarding surplus device: Apple-Iphone6-1

2016-03-14T11:18:50.769Z - info: Running on android test: 1. closeAll can close even when connections open

2016-03-14T11:18:51.347Z - info: Running on android test: 2. closeAll with promise

2016-03-14T11:18:51.946Z - info: Running on android test: 3. multiplex can send data

2016-03-14T11:18:52.414Z - info: Running on android test: 4. enqueue and run in order

2016-03-14T11:18:52.630Z - debug: Socket disconnected: transport close 4 (Apple-IpadAir2-1)

2016-03-14T11:18:53.096Z - debug: Socket disconnected: transport close 5 (Apple-Iphone6-1)

2016-03-14T11:18:53.205Z - info: Running on android test: 5. enqueueAtTop and run backwards

2016-03-14T11:18:53.269Z - info: Running on ios test: 1. closeAll can close even when connections open

2016-03-14T11:18:53.587Z - info: Running on android test: 6. mix enqueue and enqueueAtTop

2016-03-14T11:18:53.746Z - info: Running on ios test: 2. closeAll with promise

2016-03-14T11:18:54.057Z - info: Running on android test: 7. queues handled independently

2016-03-14T11:18:54.438Z - info: Running on android test: 8. basic

2016-03-14T11:18:54.757Z - info: Running on android test: 9. another

2016-03-14T11:18:54.823Z - info: Running on ios test: 3. multiplex can send data

2016-03-14T11:18:55.121Z - info: Running on android test: 10. #startListeningForAdvertisements should fail if start not called

2016-03-14T11:18:55.261Z - info: Running on ios test: 4. enqueue and run in order

2016-03-14T11:18:55.539Z - info: Running on android test: 11. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-14T11:18:55.776Z - info: Running on ios test: 5. enqueueAtTop and run backwards

2016-03-14T11:18:55.897Z - info: Running on android test: 12. should be able to call #stopListeningForAdvertisements many times

2016-03-14T11:18:56.067Z - info: Running on ios test: 6. mix enqueue and enqueueAtTop

2016-03-14T11:18:56.234Z - info: Running on android test: 13. should be able to call #startListeningForAdvertisements many times

2016-03-14T11:18:56.842Z - info: Running on ios test: 7. queues handled independently

2016-03-14T11:18:56.956Z - info: Running on android test: 14. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-14T11:18:58.164Z - info: Running on android test: 15. should be able to call #stopAdvertisingAndListening many times

2016-03-14T11:18:58.250Z - info: Running on ios test: 8. basic

2016-03-14T11:18:58.596Z - info: Running on android test: 16. #start should fail if called twice in a row

2016-03-14T11:18:58.675Z - info: Running on ios test: 9. another

2016-03-14T11:18:58.990Z - info: Running on ios test: 10. #startListeningForAdvertisements should fail if start not called

2016-03-14T11:18:59.020Z - info: Running on android test: 17. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-14T11:18:59.317Z - info: Running on ios test: 11. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-14T11:18:59.466Z - info: Running on android test: 18. does not send duplicate availability changes

2016-03-14T11:18:59.626Z - info: Running on ios test: 12. should be able to call #stopListeningForAdvertisements many times

2016-03-14T11:18:59.815Z - info: Running on android test: 19. can get the network status

2016-03-14T11:19:00.226Z - info: Running on android test: 20. wifi peer is marked unavailable if announcements stop

2016-03-14T11:19:00.826Z - info: Running on ios test: 13. should be able to call #startListeningForAdvertisements many times

2016-03-14T11:19:01.184Z - info: Running on ios test: 14. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-14T11:19:01.670Z - info: Running on android test: 21. can get the network status before starting

2016-03-14T11:19:02.168Z - info: Running on android test: 22. #generatePreambleAndBeacons bad args

2016-03-14T11:19:02.307Z - info: Running on ios test: 15. should be able to call #stopAdvertisingAndListening many times

2016-03-14T11:19:03.100Z - info: Running on android test: 23. #generatePreambleAndBeacons empty keys to notify

2016-03-14T11:19:03.408Z - info: Running on android test: 24. #generatePreambleAndBeacons multiple keys to notify

2016-03-14T11:19:03.930Z - info: Running on android test: 25. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-14T11:19:04.310Z - info: Running on android test: 26. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-14T11:19:04.793Z - info: Running on android test: 27. #parseBeacons expiration out of range lower

2016-03-14T11:19:05.319Z - info: Running on android test: 28. #parseBeacons expiration out of range lower

2016-03-14T11:19:05.685Z - info: Running on android test: 29. #parseBeacons no beacons returns null

2016-03-14T11:19:06.044Z - info: Running on android test: 30. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-14T11:19:06.280Z - info: Running on android test: 31. #parseBeacons addressBookCallback fails decrypt

2016-03-14T11:19:06.752Z - info: Running on android test: 32. #parseBeacons addressBookCallback returns no matches

2016-03-14T11:19:07.742Z - info: Running on android test: 33. #parseBeacons addressBookCallback returns spurious match

2016-03-14T11:19:08.137Z - info: Running on ios test: 16. #start should fail if called twice in a row

2016-03-14T11:19:08.441Z - info: Running on android test: 34. #parseBeacons addressBookCallback returns public key

2016-03-14T11:19:08.879Z - info: Running on android test: 35. #parseBeacons with beacons both for and not for the user

2016-03-14T11:19:09.296Z - info: Running on android test: 36. Start and stop ThaliNotificationServer

2016-03-14T11:19:09.422Z - debug: Device presented: samsung-SM-A300FU (android) unittest socket:6

2016-03-14T11:19:09.423Z - info: Discarding surplus device: samsung-SM-A300FU

2016-03-14T11:19:09.799Z - info: Running on android test: 37. Pass an empty array to ThaliNotificationServer.start

2016-03-14T11:19:10.100Z - debug: Socket disconnected: transport close 6 (samsung-SM-A300FU)

2016-03-14T11:19:10.247Z - info: Running on android test: 38. Pass a string to ThaliNotificationServer.start

2016-03-14T11:19:10.627Z - info: Running on android test: 39. Pass an empty parameter to ThaliNotificationServer.start

2016-03-14T11:19:10.951Z - info: Running on android test: 40. Make an HTTP request to /NotificationBeacons

2016-03-14T11:19:11.147Z - info: Running on ios test: 17. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-14T11:19:11.484Z - info: Running on ios test: 18. does not send duplicate availability changes

2016-03-14T11:19:11.859Z - info: Running on android test: 41. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-14T11:19:11.864Z - info: Running on ios test: 19. can get the network status

2016-03-14T11:19:12.337Z - info: Running on ios test: 20. wifi peer is marked unavailable if announcements stop

2016-03-14T11:19:12.346Z - info: Running on android test: 42. Make an HTTP request to /NotificationBeacons before calling start

2016-03-14T11:19:12.771Z - info: Running on android test: 43. #testThaliPeerAction - test getters

2016-03-14T11:19:13.059Z - info: Running on android test: 44. #testThaliPeerAction - start and kill

2016-03-14T11:19:13.371Z - info: Running on android test: 45. #testThaliPeerAction - double start

2016-03-14T11:19:13.718Z - info: Running on android test: 46. #testThaliPeerAction - start after kill

2016-03-14T11:19:13.997Z - info: Running on ios test: 21. can get the network status before starting

2016-03-14T11:19:14.084Z - info: Running on android test: 47. #testThaliPeerAction - make sure ids are unique

2016-03-14T11:19:14.389Z - info: Running on android test: 48. Test PeerConnectionInformation basics

2016-03-14T11:19:14.392Z - info: Running on ios test: 22. #generatePreambleAndBeacons bad args

2016-03-14T11:19:14.671Z - info: Running on ios test: 23. #generatePreambleAndBeacons empty keys to notify

2016-03-14T11:19:14.679Z - info: Running on android test: 49. Test PeerDictionary basic functionality

2016-03-14T11:19:14.952Z - info: Running on ios test: 24. #generatePreambleAndBeacons multiple keys to notify

2016-03-14T11:19:14.962Z - info: Running on android test: 50. Test PeerDictionary with multiple entries.

2016-03-14T11:19:15.392Z - info: Running on ios test: 25. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-14T11:19:15.675Z - info: Running on ios test: 26. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-14T11:19:15.998Z - info: Running on ios test: 27. #parseBeacons expiration out of range lower

2016-03-14T11:19:16.267Z - info: Running on ios test: 28. #parseBeacons expiration out of range lower

2016-03-14T11:19:16.493Z - info: Running on android test: 51. RESOLVED entries are removed before WAITING state entry.

2016-03-14T11:19:16.593Z - info: Running on ios test: 29. #parseBeacons no beacons returns null

2016-03-14T11:19:17.089Z - info: Running on ios test: 30. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-14T11:19:17.434Z - info: Running on ios test: 31. #parseBeacons addressBookCallback fails decrypt

2016-03-14T11:19:17.873Z - info: Running on android test: 52. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-14T11:19:18.639Z - info: Running on ios test: 32. #parseBeacons addressBookCallback returns no matches

2016-03-14T11:19:18.949Z - info: Running on android test: 53. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-14T11:19:20.021Z - info: Running on android test: 54. #ThaliPeerPoolInterface - bad enqueues

2016-03-14T11:19:20.463Z - info: Running on android test: 55. #ThaliPeerPoolInterface - do not allow same object type

2016-03-14T11:19:20.817Z - info: Running on android test: 56. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-14T11:19:21.210Z - info: Running on android test: 57. compareBufferArrays

2016-03-14T11:19:21.564Z - info: Running on android test: 58. Call start twice and get error

2016-03-14T11:19:21.581Z - info: Running on ios test: 33. #parseBeacons addressBookCallback returns spurious match

2016-03-14T11:19:21.933Z - info: Running on android test: 59. Start and make sure it runs

2016-03-14T11:19:22.385Z - info: Running on android test: 60. Make sure getTimeWhenRun is right after start

2016-03-14T11:19:22.713Z - info: Running on android test: 61. Make sure getTimeWhenRun is -1 after function is called

2016-03-14T11:19:23.095Z - info: Running on android test: 62. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-14T11:19:23.490Z - info: Running on android test: 63. Test TransientState

2016-03-14T11:19:23.910Z - info: Running on android test: 64. No peers and empty database

2016-03-14T11:19:24.707Z - info: Running on android test: 65. One peer and empty DB

2016-03-14T11:19:25.045Z - info: Running on ios test: 34. #parseBeacons addressBookCallback returns public key

2016-03-14T11:19:25.314Z - info: Running on android test: 66. One peer with _Local set behind current seq

2016-03-14T11:19:25.846Z - info: Running on ios test: 35. #parseBeacons with beacons both for and not for the user

2016-03-14T11:19:26.195Z - info: Running on android test: 67. One peer with _Local set equal to current seq

2016-03-14T11:19:26.420Z - info: Running on ios test: 36. Start and stop ThaliNotificationServer

2016-03-14T11:19:27.144Z - info: Running on android test: 68. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-14T11:19:27.842Z - info: Running on android test: 69. Three peers, one not in DB, one behind and one ahead

2016-03-14T11:19:28.717Z - info: Running on android test: 70. More than maximum peers, make sure we only send maximum allowed

2016-03-14T11:19:29.810Z - info: Running on android test: 71. two peers with empty DB, update the doc

2016-03-14T11:19:30.046Z - info: Running on ios test: 37. Pass an empty array to ThaliNotificationServer.start

2016-03-14T11:19:30.690Z - info: Running on android test: 72. add doc and make sure tokens refresh when they expire

2016-03-14T11:19:32.754Z - info: Running on android test: 73. start and stop and start and stop

2016-03-14T11:19:33.255Z - info: Running on ios test: 38. Pass a string to ThaliNotificationServer.start

2016-03-14T11:19:33.396Z - info: Running on android test: 74. two identical starts in a row

2016-03-14T11:19:34.432Z - info: Running on android test: 75. two different starts in a row

2016-03-14T11:19:35.292Z - info: Running on android test: 76. two stops and a start and two stops

2016-03-14T11:19:35.926Z - info: Running on android test: 77. we properly enqueue requests so no then needed

2016-03-14T11:19:36.485Z - info: Running on android test: 78. test calculateSeqPointKeyId

2016-03-14T11:19:36.912Z - info: Running on android test: 79. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-14T11:19:37.303Z - info: Running on ios test: 39. Pass an empty parameter to ThaliNotificationServer.start

2016-03-14T11:19:37.307Z - info: Running on android test: 80. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-14T11:19:37.969Z - info: Running on android test: 81. messages with invalid location or USN should be ignored

2016-03-14T11:19:38.294Z - info: Running on android test: 82. verify that Thali-specific messages are filtered correctly

2016-03-14T11:19:38.650Z - info: Running on android test: 83. #startListeningForAdvertisements should fail if start not called

2016-03-14T11:19:39.057Z - info: Running on android test: 84. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-14T11:19:39.423Z - info: Running on android test: 85. #start should fail if called twice in a row

2016-03-14T11:19:39.647Z - info: Running on ios test: 40. Make an HTTP request to /NotificationBeacons

2016-03-14T11:19:39.781Z - info: Running on android test: 86. should not be started after stop is called

2016-03-14T11:19:40.132Z - info: Running on android test: 87. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-14T11:19:40.501Z - info: Running on android test: 88. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-14T11:19:40.736Z - info: Running on ios test: 41. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-14T11:19:40.826Z - info: Running on android test: 89. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-14T11:19:41.164Z - info: Running on ios test: 42. Make an HTTP request to /NotificationBeacons before calling start

2016-03-14T11:19:41.227Z - info: Running on android test: 90. #stop can be called multiple times in a row

2016-03-14T11:19:41.553Z - info: Running on android test: 91. #startListeningForAdvertisements can be called multiple times in a row

2016-03-14T11:19:41.565Z - info: Running on ios test: 43. #testThaliPeerAction - test getters

2016-03-14T11:19:41.940Z - info: Running on ios test: 44. #testThaliPeerAction - start and kill

2016-03-14T11:19:41.947Z - info: Running on android test: 92. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-14T11:19:42.283Z - info: Running on ios test: 45. #testThaliPeerAction - double start

2016-03-14T11:19:42.286Z - info: Running on android test: 93. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-14T11:19:42.681Z - info: Running on android test: 94. functions are run from a queue in the right order

2016-03-14T11:19:42.763Z - info: Running on ios test: 46. #testThaliPeerAction - start after kill

2016-03-14T11:19:43.200Z - info: Running on android test: 95. #ThaliPeerPoolDefault - single action

2016-03-14T11:19:43.256Z - info: Running on ios test: 47. #testThaliPeerAction - make sure ids are unique

2016-03-14T11:19:43.603Z - info: Running on android test: 96. #ThaliPeerPoolDefault - multiple actions

2016-03-14T11:19:43.650Z - info: Running on ios test: 48. Test PeerConnectionInformation basics

2016-03-14T11:19:43.942Z - info: Test run on android complete

2016-03-14T11:19:43.945Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-14T11:19:43.947Z - info: PLATFORM: android

2016-03-14T11:19:43.948Z - info: RESULT: PASS

2016-03-14T11:19:43.949Z - info: 96 of 96 tests completed

2016-03-14T11:19:43.950Z - info: 96/96 passed (0 failures)

2016-03-14T11:19:43.951Z - info: --- Test Details ---



2016-03-14T11:19:43.952Z - info: 1. closeAll can close even when connections open - pass

2016-03-14T11:19:43.953Z - info: 2. closeAll with promise - pass

2016-03-14T11:19:43.954Z - info: 3. multiplex can send data - pass

2016-03-14T11:19:43.955Z - info: 4. enqueue and run in order - pass

2016-03-14T11:19:43.956Z - info: 5. enqueueAtTop and run backwards - pass

2016-03-14T11:19:43.957Z - info: 6. mix enqueue and enqueueAtTop - pass

2016-03-14T11:19:43.958Z - info: 7. queues handled independently - pass

2016-03-14T11:19:43.959Z - info: 8. basic - pass

2016-03-14T11:19:43.960Z - info: 9. another - pass
2016-03-14T11:19:43.961Z - info: 10. #startListeningForAdvertisements should fail if start not called - pass

2016-03-14T11:19:43.962Z - info: 11. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-14T11:19:43.963Z - info: 12. should be able to call #stopListeningForAdvertisements many times - pass
2016-03-14T11:19:43.964Z - info: 13. should be able to call #startListeningForAdvertisements many times - pass
2016-03-14T11:19:43.964Z - info: 14. should be able to call #startUpdateAdvertisingAndListening many times - pass
2016-03-14T11:19:43.965Z - info: 15. should be able to call #stopAdvertisingAndListening many times - pass
2016-03-14T11:19:43.965Z - info: 16. #start should fail if called twice in a row - pass
2016-03-14T11:19:43.966Z - info: 17. does not emit duplicate discoveryAdvertisingStateUpdate - pass
2016-03-14T11:19:43.967Z - info: 18. does not send duplicate availability changes - pass
2016-03-14T11:19:43.967Z - info: 19. can get the network status - pass
2016-03-14T11:19:43.968Z - info: 20. wifi peer is marked unavailable if announcements stop - pass
2016-03-14T11:19:43.969Z - info: 21. can get the network status before starting - pass
2016-03-14T11:19:43.969Z - info: 22. #generatePreambleAndBeacons bad args - pass
2016-03-14T11:19:43.970Z - info: 23. #generatePreambleAndBeacons empty keys to notify - pass
2016-03-14T11:19:43.970Z - info: 24. #generatePreambleAndBeacons multiple keys to notify - pass
2016-03-14T11:19:43.971Z - info: 25. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass
2016-03-14T11:19:43.972Z - info: 26. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass
2016-03-14T11:19:43.972Z - info: 27. #parseBeacons expiration out of range lower - pass
2016-03-14T11:19:43.973Z - info: 28. #parseBeacons expiration out of range lower - pass
2016-03-14T11:19:43.974Z - info: 29. #parseBeacons no beacons returns null - pass
2016-03-14T11:19:43.974Z - info: 30. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass
2016-03-14T11:19:43.975Z - info: 31. #parseBeacons addressBookCallback fails decrypt - pass
2016-03-14T11:19:43.976Z - info: 32. #parseBeacons addressBookCallback returns no matches - pass

2016-03-14T11:19:43.976Z - info: 33. #parseBeacons addressBookCallback returns spurious match - pass
2016-03-14T11:19:43.977Z - info: 34. #parseBeacons addressBookCallback returns public key - pass

2016-03-14T11:19:43.978Z - info: 35. #parseBeacons with beacons both for and not for the user - pass
2016-03-14T11:19:43.979Z - info: 36. Start and stop ThaliNotificationServer - pass

2016-03-14T11:19:43.980Z - info: 37. Pass an empty array to ThaliNotificationServer.start - pass

2016-03-14T11:19:43.981Z - info: 38. Pass a string to ThaliNotificationServer.start - pass

2016-03-14T11:19:43.982Z - info: 39. Pass an empty parameter to ThaliNotificationServer.start - pass

2016-03-14T11:19:43.983Z - info: 40. Make an HTTP request to /NotificationBeacons - pass
2016-03-14T11:19:43.983Z - info: 41. Make an HTTP request to /NotificationBeacons (no keys) - pass
2016-03-14T11:19:43.984Z - info: 42. Make an HTTP request to /NotificationBeacons before calling start - pass
2016-03-14T11:19:43.985Z - info: 43. #testThaliPeerAction - test getters - pass
2016-03-14T11:19:43.985Z - info: 44. #testThaliPeerAction - start and kill - pass
2016-03-14T11:19:43.986Z - info: 45. #testThaliPeerAction - double start - pass
2016-03-14T11:19:43.987Z - info: 46. #testThaliPeerAction - start after kill - pass
2016-03-14T11:19:43.987Z - info: 47. #testThaliPeerAction - make sure ids are unique - pass

2016-03-14T11:19:43.988Z - info: 48. Test PeerConnectionInformation basics - pass

2016-03-14T11:19:43.989Z - info: 49. Test PeerDictionary basic functionality - pass
2016-03-14T11:19:43.990Z - info: 50. Test PeerDictionary with multiple entries. - pass

2016-03-14T11:19:43.991Z - info: 51. RESOLVED entries are removed before WAITING state entry. - pass

2016-03-14T11:19:43.992Z - info: 52. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass

2016-03-14T11:19:43.993Z - info: 53. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass

2016-03-14T11:19:43.994Z - info: 54. #ThaliPeerPoolInterface - bad enqueues - pass

2016-03-14T11:19:43.995Z - info: 55. #ThaliPeerPoolInterface - do not allow same object type - pass

2016-03-14T11:19:43.996Z - info: 56. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass

2016-03-14T11:19:43.997Z - info: 57. compareBufferArrays - pass
2016-03-14T11:19:43.998Z - info: 58. Call start twice and get error - pass

2016-03-14T11:19:43.999Z - info: 59. Start and make sure it runs - pass

2016-03-14T11:19:43.999Z - info: 60. Make sure getTimeWhenRun is right after start - pass
2016-03-14T11:19:44.000Z - info: 61. Make sure getTimeWhenRun is -1 after function is called - pass
2016-03-14T11:19:44.001Z - info: 62. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass

2016-03-14T11:19:44.002Z - info: 63. Test TransientState - pass

2016-03-14T11:19:44.003Z - info: 64. No peers and empty database - pass

2016-03-14T11:19:44.004Z - info: 65. One peer and empty DB - pass

2016-03-14T11:19:44.005Z - info: 66. One peer with _Local set behind current seq - pass

2016-03-14T11:19:44.006Z - info: 67. One peer with _Local set equal to current seq - pass
2016-03-14T11:19:44.006Z - info: 68. One peer with _Local set ahead of current seq (and no this should not happen) - pass

2016-03-14T11:19:44.007Z - info: 69. Three peers, one not in DB, one behind and one ahead - pass

2016-03-14T11:19:44.008Z - info: 70. More than maximum peers, make sure we only send maximum allowed - pass

2016-03-14T11:19:44.009Z - info: 71. two peers with empty DB, update the doc - pass

2016-03-14T11:19:44.010Z - info: 72. add doc and make sure tokens refresh when they expire - pass

2016-03-14T11:19:44.011Z - info: 73. start and stop and start and stop - pass

2016-03-14T11:19:44.012Z - info: 74. two identical starts in a row - pass

2016-03-14T11:19:44.013Z - info: 75. two different starts in a row - pass

2016-03-14T11:19:44.014Z - info: 76. two stops and a start and two stops - pass

2016-03-14T11:19:44.015Z - info: 77. we properly enqueue requests so no then needed - pass
2016-03-14T11:19:44.016Z - info: 78. test calculateSeqPointKeyId - pass

2016-03-14T11:19:44.017Z - info: 79. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass

2016-03-14T11:19:44.018Z - info: 80. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-03-14T11:19:44.018Z - info: 81. messages with invalid location or USN should be ignored - pass

2016-03-14T11:19:44.019Z - info: 82. verify that Thali-specific messages are filtered correctly - pass

2016-03-14T11:19:44.020Z - info: 83. #startListeningForAdvertisements should fail if start not called - pass
2016-03-14T11:19:44.021Z - info: 84. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-14T11:19:44.022Z - info: 85. #start should fail if called twice in a row - pass

2016-03-14T11:19:44.023Z - info: 86. should not be started after stop is called - pass

2016-03-14T11:19:44.024Z - info: 87. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass

2016-03-14T11:19:44.025Z - info: 88. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass

2016-03-14T11:19:44.026Z - info: 89. #startUpdateAdvertisingAndListening should start hosting given router object - pass

2016-03-14T11:19:44.027Z - info: 90. #stop can be called multiple times in a row - pass

2016-03-14T11:19:44.028Z - info: 91. #startListeningForAdvertisements can be called multiple times in a row - pass

2016-03-14T11:19:44.029Z - info: 92. #stopListeningForAdvertisements can be called multiple times in a row - pass

2016-03-14T11:19:44.030Z - info: 93. #stopAdvertisingAndListening can be called multiple times in a row - pass

2016-03-14T11:19:44.031Z - info: 94. functions are run from a queue in the right order - pass

2016-03-14T11:19:44.032Z - info: 95. #ThaliPeerPoolDefault - single action - pass

2016-03-14T11:19:44.033Z - info: 96. #ThaliPeerPoolDefault - multiple actions - pass

2016-03-14T11:19:44.034Z - info: 

-== END ==-

2016-03-14T11:19:44.269Z - info: Running on ios test: 49. Test PeerDictionary basic functionality

2016-03-14T11:19:44.552Z - info: Running on ios test: 50. Test PeerDictionary with multiple entries.

2016-03-14T11:19:44.896Z - debug: Socket disconnected: transport close 2 (samsung-SM-N910C)

2016-03-14T11:19:44.903Z - debug: Socket disconnected: transport close 1 (LGE-LG-H815)

2016-03-14T11:19:49.308Z - info: Running on ios test: 51. RESOLVED entries are removed before WAITING state entry.

2016-03-14T11:20:01.863Z - info: Running on ios test: 52. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-14T11:20:09.462Z - info: Running on ios test: 53. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-14T11:20:16.264Z - info: Running on ios test: 54. #ThaliPeerPoolInterface - bad enqueues

2016-03-14T11:20:23.740Z - info: Running on ios test: 55. #ThaliPeerPoolInterface - do not allow same object type

2016-03-14T11:20:28.341Z - info: Running on ios test: 56. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-14T11:20:33.519Z - info: Running on ios test: 57. compareBufferArrays

2016-03-14T11:20:33.993Z - info: Running on ios test: 58. Call start twice and get error

2016-03-14T11:20:34.362Z - info: Running on ios test: 59. Start and make sure it runs

2016-03-14T11:20:34.646Z - info: Running on ios test: 60. Make sure getTimeWhenRun is right after start

2016-03-14T11:20:34.926Z - info: Running on ios test: 61. Make sure getTimeWhenRun is -1 after function is called

2016-03-14T11:20:35.323Z - info: Running on ios test: 62. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-14T11:20:35.720Z - info: Running on ios test: 63. Test TransientState

2016-03-14T11:20:36.138Z - info: Running on ios test: 64. No peers and empty database

2016-03-14T11:20:39.232Z - info: Running on ios test: 65. One peer and empty DB

2016-03-14T11:20:43.504Z - info: Running on ios test: 66. One peer with _Local set behind current seq

2016-03-14T11:20:44.219Z - info: Running on ios test: 67. One peer with _Local set equal to current seq

2016-03-14T11:20:45.063Z - info: Running on ios test: 68. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-14T11:20:45.825Z - info: Running on ios test: 69. Three peers, one not in DB, one behind and one ahead

2016-03-14T11:20:46.916Z - info: Running on ios test: 70. More than maximum peers, make sure we only send maximum allowed

2016-03-14T11:20:50.297Z - info: Running on ios test: 71. two peers with empty DB, update the doc

2016-03-14T11:20:52.264Z - info: Running on ios test: 72. add doc and make sure tokens refresh when they expire

2016-03-14T11:20:53.720Z - info: Running on ios test: 73. start and stop and start and stop

2016-03-14T11:20:58.378Z - info: Running on ios test: 74. two identical starts in a row

2016-03-14T11:20:59.029Z - info: Running on ios test: 75. two different starts in a row

2016-03-14T11:20:59.624Z - info: Running on ios test: 76. two stops and a start and two stops

2016-03-14T11:21:03.121Z - info: Running on ios test: 77. we properly enqueue requests so no then needed

2016-03-14T11:21:03.733Z - info: Running on ios test: 78. test calculateSeqPointKeyId

2016-03-14T11:21:04.080Z - info: Running on ios test: 79. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-14T11:21:08.166Z - info: Running on ios test: 80. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-14T11:21:12.469Z - info: Running on ios test: 81. messages with invalid location or USN should be ignored

2016-03-14T11:21:12.800Z - info: Running on ios test: 82. verify that Thali-specific messages are filtered correctly

2016-03-14T11:21:13.088Z - info: Running on ios test: 83. #startListeningForAdvertisements should fail if start not called

2016-03-14T11:21:13.412Z - info: Running on ios test: 84. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-14T11:21:13.683Z - info: Running on ios test: 85. #start should fail if called twice in a row

2016-03-14T11:21:14.110Z - info: Running on ios test: 86. should not be started after stop is called

2016-03-14T11:21:14.454Z - info: Running on ios test: 87. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-14T11:21:14.843Z - info: Running on ios test: 88. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-14T11:21:15.234Z - info: Running on ios test: 89. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-14T11:21:15.644Z - info: Running on ios test: 90. #stop can be called multiple times in a row

2016-03-14T11:21:16.003Z - info: Running on ios test: 91. #startListeningForAdvertisements can be called multiple times in a row

2016-03-14T11:21:16.405Z - info: Running on ios test: 92. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-14T11:21:16.662Z - info: Running on ios test: 93. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-14T11:21:16.992Z - info: Running on ios test: 94. functions are run from a queue in the right order

2016-03-14T11:21:17.321Z - info: Running on ios test: 95. #ThaliPeerPoolDefault - single action

2016-03-14T11:21:17.626Z - info: Running on ios test: 96. #ThaliPeerPoolDefault - multiple actions

2016-03-14T11:21:18.639Z - info: Test run on ios complete

2016-03-14T11:21:18.640Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-14T11:21:18.642Z - info: PLATFORM: ios

2016-03-14T11:21:18.643Z - info: RESULT: PASS

2016-03-14T11:21:18.644Z - info: 96 of 96 tests completed

2016-03-14T11:21:18.646Z - info: 96/96 passed (0 failures)

2016-03-14T11:21:18.647Z - info: --- Test Details ---



2016-03-14T11:21:18.648Z - info: 1. closeAll can close even when connections open - pass

2016-03-14T11:21:18.649Z - info: 2. closeAll with promise - pass

2016-03-14T11:21:18.649Z - info: 3. multiplex can send data - pass
2016-03-14T11:21:18.650Z - info: 4. enqueue and run in order - pass

2016-03-14T11:21:18.651Z - info: 5. enqueueAtTop and run backwards - pass

2016-03-14T11:21:18.652Z - info: 6. mix enqueue and enqueueAtTop - pass

2016-03-14T11:21:18.653Z - info: 7. queues handled independently - pass

2016-03-14T11:21:18.653Z - info: 8. basic - pass

2016-03-14T11:21:18.654Z - info: 9. another - pass
2016-03-14T11:21:18.655Z - info: 10. #startListeningForAdvertisements should fail if start not called - pass

2016-03-14T11:21:18.656Z - info: 11. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-14T11:21:18.657Z - info: 12. should be able to call #stopListeningForAdvertisements many times - pass

2016-03-14T11:21:18.658Z - info: 13. should be able to call #startListeningForAdvertisements many times - pass

2016-03-14T11:21:18.659Z - info: 14. should be able to call #startUpdateAdvertisingAndListening many times - pass
2016-03-14T11:21:18.659Z - info: 15. should be able to call #stopAdvertisingAndListening many times - pass

2016-03-14T11:21:18.660Z - info: 16. #start should fail if called twice in a row - pass

2016-03-14T11:21:18.661Z - info: 17. does not emit duplicate discoveryAdvertisingStateUpdate - pass

2016-03-14T11:21:18.662Z - info: 18. does not send duplicate availability changes - pass

2016-03-14T11:21:18.663Z - info: 19. can get the network status - pass

2016-03-14T11:21:18.664Z - info: 20. wifi peer is marked unavailable if announcements stop - pass
2016-03-14T11:21:18.664Z - info: 21. can get the network status before starting - pass

2016-03-14T11:21:18.665Z - info: 22. #generatePreambleAndBeacons bad args - pass

2016-03-14T11:21:18.666Z - info: 23. #generatePreambleAndBeacons empty keys to notify - pass

2016-03-14T11:21:18.667Z - info: 24. #generatePreambleAndBeacons multiple keys to notify - pass

2016-03-14T11:21:18.668Z - info: 25. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass

2016-03-14T11:21:18.669Z - info: 26. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass
2016-03-14T11:21:18.669Z - info: 27. #parseBeacons expiration out of range lower - pass

2016-03-14T11:21:18.670Z - info: 28. #parseBeacons expiration out of range lower - pass

2016-03-14T11:21:18.671Z - info: 29. #parseBeacons no beacons returns null - pass

2016-03-14T11:21:18.672Z - info: 30. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass

2016-03-14T11:21:18.673Z - info: 31. #parseBeacons addressBookCallback fails decrypt - pass

2016-03-14T11:21:18.674Z - info: 32. #parseBeacons addressBookCallback returns no matches - pass
2016-03-14T11:21:18.675Z - info: 33. #parseBeacons addressBookCallback returns spurious match - pass

2016-03-14T11:21:18.675Z - info: 34. #parseBeacons addressBookCallback returns public key - pass

2016-03-14T11:21:18.676Z - info: 35. #parseBeacons with beacons both for and not for the user - pass

2016-03-14T11:21:18.677Z - info: 36. Start and stop ThaliNotificationServer - pass

2016-03-14T11:21:18.678Z - info: 37. Pass an empty array to ThaliNotificationServer.start - pass

2016-03-14T11:21:18.679Z - info: 38. Pass a string to ThaliNotificationServer.start - pass
2016-03-14T11:21:18.680Z - info: 39. Pass an empty parameter to ThaliNotificationServer.start - pass

2016-03-14T11:21:18.681Z - info: 40. Make an HTTP request to /NotificationBeacons - pass

2016-03-14T11:21:18.681Z - info: 41. Make an HTTP request to /NotificationBeacons (no keys) - pass

2016-03-14T11:21:18.682Z - info: 42. Make an HTTP request to /NotificationBeacons before calling start - pass

2016-03-14T11:21:18.683Z - info: 43. #testThaliPeerAction - test getters - pass
2016-03-14T11:21:18.684Z - info: 44. #testThaliPeerAction - start and kill - pass

2016-03-14T11:21:18.685Z - info: 45. #testThaliPeerAction - double start - pass

2016-03-14T11:21:18.685Z - info: 46. #testThaliPeerAction - start after kill - pass

2016-03-14T11:21:18.686Z - info: 47. #testThaliPeerAction - make sure ids are unique - pass

2016-03-14T11:21:18.687Z - info: 48. Test PeerConnectionInformation basics - pass
2016-03-14T11:21:18.688Z - info: 49. Test PeerDictionary basic functionality - pass

2016-03-14T11:21:18.689Z - info: 50. Test PeerDictionary with multiple entries. - pass

2016-03-14T11:21:18.690Z - info: 51. RESOLVED entries are removed before WAITING state entry. - pass

2016-03-14T11:21:18.691Z - info: 52. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass

2016-03-14T11:21:18.691Z - info: 53. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass

2016-03-14T11:21:18.692Z - info: 54. #ThaliPeerPoolInterface - bad enqueues - pass
2016-03-14T11:21:18.693Z - info: 55. #ThaliPeerPoolInterface - do not allow same object type - pass

2016-03-14T11:21:18.694Z - info: 56. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass

2016-03-14T11:21:18.696Z - info: 57. compareBufferArrays - pass

2016-03-14T11:21:18.697Z - info: 58. Call start twice and get error - pass

2016-03-14T11:21:18.698Z - info: 59. Start and make sure it runs - pass

2016-03-14T11:21:18.705Z - info: 60. Make sure getTimeWhenRun is right after start - pass

2016-03-14T11:21:18.706Z - info: 61. Make sure getTimeWhenRun is -1 after function is called - pass

2016-03-14T11:21:18.707Z - info: 62. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass
2016-03-14T11:21:18.708Z - info: 63. Test TransientState - pass

2016-03-14T11:21:18.709Z - info: 64. No peers and empty database - pass

2016-03-14T11:21:18.710Z - info: 65. One peer and empty DB - pass

2016-03-14T11:21:18.711Z - info: 66. One peer with _Local set behind current seq - pass

2016-03-14T11:21:18.711Z - info: 67. One peer with _Local set equal to current seq - pass

2016-03-14T11:21:18.712Z - info: 68. One peer with _Local set ahead of current seq (and no this should not happen) - pass
2016-03-14T11:21:18.713Z - info: 69. Three peers, one not in DB, one behind and one ahead - pass

2016-03-14T11:21:18.714Z - info: 70. More than maximum peers, make sure we only send maximum allowed - pass

2016-03-14T11:21:18.746Z - info: 71. two peers with empty DB, update the doc - pass

2016-03-14T11:21:18.747Z - info: 72. add doc and make sure tokens refresh when they expire - pass

2016-03-14T11:21:18.748Z - info: 73. start and stop and start and stop - pass

2016-03-14T11:21:18.749Z - info: 74. two identical starts in a row - pass
2016-03-14T11:21:18.750Z - info: 75. two different starts in a row - pass

2016-03-14T11:21:18.751Z - info: 76. two stops and a start and two stops - pass

2016-03-14T11:21:18.751Z - info: 77. we properly enqueue requests so no then needed - pass

2016-03-14T11:21:18.752Z - info: 78. test calculateSeqPointKeyId - pass

2016-03-14T11:21:18.753Z - info: 79. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass
2016-03-14T11:21:18.754Z - info: 80. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-03-14T11:21:18.755Z - info: 81. messages with invalid location or USN should be ignored - pass

2016-03-14T11:21:18.755Z - info: 82. verify that Thali-specific messages are filtered correctly - pass

2016-03-14T11:21:18.756Z - info: 83. #startListeningForAdvertisements should fail if start not called - pass

2016-03-14T11:21:18.757Z - info: 84. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-14T11:21:18.758Z - info: 85. #start should fail if called twice in a row - pass

2016-03-14T11:21:18.759Z - info: 86. should not be started after stop is called - pass

2016-03-14T11:21:18.759Z - info: 87. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass

2016-03-14T11:21:18.760Z - info: 88. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass
2016-03-14T11:21:18.761Z - info: 89. #startUpdateAdvertisingAndListening should start hosting given router object - pass

2016-03-14T11:21:18.762Z - info: 90. #stop can be called multiple times in a row - pass

2016-03-14T11:21:18.763Z - info: 91. #startListeningForAdvertisements can be called multiple times in a row - pass

2016-03-14T11:21:18.763Z - info: 92. #stopListeningForAdvertisements can be called multiple times in a row - pass

2016-03-14T11:21:18.764Z - info: 93. #stopAdvertisingAndListening can be called multiple times in a row - pass
2016-03-14T11:21:18.765Z - info: 94. functions are run from a queue in the right order - pass

2016-03-14T11:21:18.766Z - info: 95. #ThaliPeerPoolDefault - single action - pass

2016-03-14T11:21:18.767Z - info: 96. #ThaliPeerPoolDefault - multiple actions - pass

2016-03-14T11:21:18.767Z - info: 

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
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62560673a3c76e9_Fixed_the_state_error_and_updated_the_Bluetooth_connector_library_version_tompaana/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/62560673a3c76e9_Fixed_the_state_error_and_updated_the_Bluetooth_connector_library_version_tompaana/thali02_LGE-LG-D722.md)

####Node name: thali03
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Android task is completed. [SUCCESS]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/62560673a3c76e9_Fixed_the_state_error_and_updated_the_Bluetooth_connector_library_version_tompaana/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/62560673a3c76e9_Fixed_the_state_error_and_updated_the_Bluetooth_connector_library_version_tompaana/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Android task is completed. [SUCCESS]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/62560673a3c76e9_Fixed_the_state_error_and_updated_the_Bluetooth_connector_library_version_tompaana/thali05_LGE-LG-H815.md)

####Node name: thali06
Console output:
```
STOP log received from  7970f88c Test has  SUCCEEDED
Device test finished on 7970f88c 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:0 
child process exited with code 0 on device FA55PYS00566 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62560673a3c76e9_Fixed_the_state_error_and_updated_the_Bluetooth_connector_library_version_tompaana/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/62560673a3c76e9_Fixed_the_state_error_and_updated_the_Bluetooth_connector_library_version_tompaana/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:0 
child process exited with code 0 on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62560673a3c76e9_Fixed_the_state_error_and_updated_the_Bluetooth_connector_library_version_tompaana/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:0 
child process exited with code 0 on device 4325e43f 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62560673a3c76e9_Fixed_the_state_error_and_updated_the_Bluetooth_connector_library_version_tompaana/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 09a9416e0297d102 app:com.test.thalitest code:0 
child process exited with code 0 on device 09a9416e0297d102 
Android task is completed. [FAILED]
```
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/62560673a3c76e9_Fixed_the_state_error_and_updated_the_Bluetooth_connector_library_version_tompaana/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/62560673a3c76e9_Fixed_the_state_error_and_updated_the_Bluetooth_connector_library_version_tompaana/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/62560673a3c76e9_Fixed_the_state_error_and_updated_the_Bluetooth_connector_library_version_tompaana/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/62560673a3c76e9_Fixed_the_state_error_and_updated_the_Bluetooth_connector_library_version_tompaana/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/62560673a3c76e9_Fixed_the_state_error_and_updated_the_Bluetooth_connector_library_version_tompaana/iOS_IpadAir2-1.md)



#### Test 6136236661fd38c Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":22}}
2016-03-03T14:02:00.312Z - info: listening on *:3000

2016-03-03T14:02:01.283Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:0

2016-03-03T14:02:02.921Z - debug: Device presented: samsung-SM-A300FU (android) unittest socket:1

2016-03-03T14:02:03.267Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:2

2016-03-03T14:02:03.270Z - info: Required number of android devices presented (2)

2016-03-03T14:02:03.274Z - info: Starting unit test run for platform: android

2016-03-03T14:02:03.890Z - info: Running on android test: 1. multiplex can send data

2016-03-03T14:02:03.906Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:3

2016-03-03T14:02:03.907Z - info: Required number of ios devices presented (2)

2016-03-03T14:02:03.910Z - info: Starting unit test run for platform: ios

2016-03-03T14:02:04.341Z - info: Running on ios test: 1. multiplex can send data

2016-03-03T14:02:04.445Z - info: Running on android test: 2. enqueue and run in order

2016-03-03T14:02:04.827Z - info: Running on ios test: 2. enqueue and run in order

2016-03-03T14:02:04.842Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:4

2016-03-03T14:02:04.843Z - info: Discarding surplus device: Apple-Iphone5-1

2016-03-03T14:02:05.438Z - info: Running on android test: 3. enqueueAtTop and run backwards

2016-03-03T14:02:05.605Z - info: Running on ios test: 3. enqueueAtTop and run backwards

2016-03-03T14:02:06.130Z - info: Running on android test: 4. mix enqueue and enqueueAtTop

2016-03-03T14:02:06.156Z - info: Running on ios test: 4. mix enqueue and enqueueAtTop

2016-03-03T14:02:06.695Z - info: Running on ios test: 5. queues handled independently

2016-03-03T14:02:06.726Z - info: Running on android test: 5. queues handled independently

2016-03-03T14:02:07.218Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:5

2016-03-03T14:02:07.222Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-03T14:02:07.253Z - info: Running on ios test: 6. basic

2016-03-03T14:02:07.258Z - info: Running on android test: 6. basic

2016-03-03T14:02:07.649Z - info: Running on android test: 7. another

2016-03-03T14:02:07.693Z - info: Running on ios test: 7. another

2016-03-03T14:02:08.036Z - info: Running on android test: 8. #startListeningForAdvertisements should fail if start not called

2016-03-03T14:02:08.122Z - debug: Socket disconnected: transport close 4 (Apple-Iphone5-1)

2016-03-03T14:02:08.500Z - info: Running on android test: 9. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-03T14:02:08.505Z - info: Running on ios test: 8. #startListeningForAdvertisements should fail if start not called

2016-03-03T14:02:08.946Z - info: Running on android test: 10. should be able to call #stopListeningForAdvertisements many times

2016-03-03T14:02:08.979Z - info: Running on ios test: 9. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-03T14:02:09.381Z - info: Running on ios test: 10. should be able to call #stopListeningForAdvertisements many times

2016-03-03T14:02:09.505Z - info: Running on android test: 11. should be able to call #startListeningForAdvertisements many times

2016-03-03T14:02:09.846Z - info: Running on ios test: 11. should be able to call #startListeningForAdvertisements many times

2016-03-03T14:02:10.033Z - debug: Socket disconnected: transport close 5 (Apple-Iphone5s-1)

2016-03-03T14:02:10.299Z - info: Running on ios test: 12. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-03T14:02:10.447Z - info: Running on android test: 12. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-03T14:02:10.980Z - info: Running on ios test: 13. should be able to call #stopAdvertisingAndListening many times

2016-03-03T14:02:11.791Z - info: Running on ios test: 14. #start should fail if called twice in a row

2016-03-03T14:02:11.898Z - info: Running on android test: 13. should be able to call #stopAdvertisingAndListening many times

2016-03-03T14:02:12.488Z - info: Running on ios test: 15. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-03T14:02:12.523Z - info: Running on android test: 14. #start should fail if called twice in a row

2016-03-03T14:02:12.941Z - info: Running on ios test: 16. does not send duplicate availability changes

2016-03-03T14:02:13.092Z - info: Running on android test: 15. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-03T14:02:13.305Z - info: Running on ios test: 17. can get the network status

2016-03-03T14:02:13.819Z - info: Running on android test: 16. does not send duplicate availability changes

2016-03-03T14:02:13.953Z - info: Running on ios test: 18. wifi peer is marked unavailable if announcements stop

2016-03-03T14:02:15.063Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:6

2016-03-03T14:02:15.064Z - info: Discarding surplus device: samsung-SM-N910C

2016-03-03T14:02:15.127Z - info: Running on android test: 17. can get the network status

2016-03-03T14:02:15.549Z - info: Running on ios test: 19. can get the network status before starting

2016-03-03T14:02:15.623Z - info: Running on android test: 18. wifi peer is marked unavailable if announcements stop

2016-03-03T14:02:15.986Z - debug: Socket disconnected: transport close 6 (samsung-SM-N910C)

2016-03-03T14:02:16.062Z - info: Running on ios test: 20. #generatePreambleAndBeacons bad args

2016-03-03T14:02:16.686Z - info: Running on ios test: 21. #generatePreambleAndBeacons empty keys to notify

2016-03-03T14:02:17.045Z - info: Running on ios test: 22. #generatePreambleAndBeacons multiple keys to notify

2016-03-03T14:02:17.451Z - info: Running on android test: 19. can get the network status before starting

2016-03-03T14:02:17.563Z - info: Running on ios test: 23. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-03T14:02:18.000Z - info: Running on ios test: 24. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-03T14:02:18.274Z - info: Running on android test: 20. #generatePreambleAndBeacons bad args

2016-03-03T14:02:18.398Z - info: Running on ios test: 25. #parseBeacons expiration out of range lower

2016-03-03T14:02:18.903Z - info: Running on ios test: 26. #parseBeacons expiration out of range lower

2016-03-03T14:02:19.101Z - info: Running on android test: 21. #generatePreambleAndBeacons empty keys to notify

2016-03-03T14:02:19.336Z - info: Running on ios test: 27. #parseBeacons no beacons returns null

2016-03-03T14:02:19.664Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:7

2016-03-03T14:02:19.665Z - info: Discarding surplus device: samsung-SM-G900F

2016-03-03T14:02:19.835Z - info: Running on android test: 22. #generatePreambleAndBeacons multiple keys to notify

2016-03-03T14:02:19.855Z - info: Running on ios test: 28. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-03T14:02:20.430Z - info: Running on ios test: 29. #parseBeacons addressBookCallback fails decrypt

2016-03-03T14:02:20.708Z - info: Running on android test: 23. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-03T14:02:20.789Z - debug: Socket disconnected: transport close 7 (samsung-SM-G900F)

2016-03-03T14:02:21.437Z - info: Running on android test: 24. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-03T14:02:22.696Z - info: Running on android test: 25. #parseBeacons expiration out of range lower

2016-03-03T14:02:23.218Z - info: Running on android test: 26. #parseBeacons expiration out of range lower

2016-03-03T14:02:23.891Z - info: Running on android test: 27. #parseBeacons no beacons returns null

2016-03-03T14:02:24.211Z - info: Running on ios test: 30. #parseBeacons addressBookCallback returns no matches

2016-03-03T14:02:25.119Z - info: Running on android test: 28. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-03T14:02:25.504Z - info: Running on ios test: 31. #parseBeacons addressBookCallback returns spurious match

2016-03-03T14:02:25.772Z - info: Running on android test: 29. #parseBeacons addressBookCallback fails decrypt

2016-03-03T14:02:26.159Z - info: Running on ios test: 32. #parseBeacons addressBookCallback returns public key

2016-03-03T14:02:27.201Z - info: Running on android test: 30. #parseBeacons addressBookCallback returns no matches

2016-03-03T14:02:27.884Z - info: Running on ios test: 33. #parseBeacons with beacons both for and not for the user

2016-03-03T14:02:28.333Z - info: Running on ios test: 34. Start and stop ThaliNotificationServer

2016-03-03T14:02:28.513Z - info: Running on android test: 31. #parseBeacons addressBookCallback returns spurious match

2016-03-03T14:02:28.795Z - info: Running on ios test: 35. Pass an empty array to ThaliNotificationServer.start

2016-03-03T14:02:29.748Z - info: Running on android test: 32. #parseBeacons addressBookCallback returns public key

2016-03-03T14:02:30.102Z - info: Running on ios test: 36. Pass a string to ThaliNotificationServer.start

2016-03-03T14:02:30.627Z - info: Running on ios test: 37. Pass an empty parameter to ThaliNotificationServer.start

2016-03-03T14:02:30.960Z - info: Running on android test: 33. #parseBeacons with beacons both for and not for the user

2016-03-03T14:02:31.092Z - info: Running on ios test: 38. Make an HTTP request to /NotificationBeacons

2016-03-03T14:02:36.530Z - info: Running on ios test: 39. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-03T14:02:36.937Z - info: Running on android test: 34. Start and stop ThaliNotificationServer

2016-03-03T14:02:37.513Z - info: Running on android test: 35. Pass an empty array to ThaliNotificationServer.start

2016-03-03T14:02:38.261Z - info: Running on android test: 36. Pass a string to ThaliNotificationServer.start

2016-03-03T14:02:38.689Z - info: Running on ios test: 40. Make an HTTP request to /NotificationBeacons before calling start

2016-03-03T14:02:39.715Z - info: Running on ios test: 41. #testThaliPeerAction - test getters

2016-03-03T14:02:40.166Z - info: Running on android test: 37. Pass an empty parameter to ThaliNotificationServer.start

2016-03-03T14:02:40.220Z - info: Running on ios test: 42. #testThaliPeerAction - start and kill

2016-03-03T14:02:40.750Z - info: Running on ios test: 43. #testThaliPeerAction - double start

2016-03-03T14:02:41.235Z - info: Running on ios test: 44. #testThaliPeerAction - start after kill

2016-03-03T14:02:41.238Z - info: Running on android test: 38. Make an HTTP request to /NotificationBeacons

2016-03-03T14:02:41.798Z - info: Running on ios test: 45. #testThaliPeerAction - make sure ids are unique

2016-03-03T14:02:42.342Z - info: Running on ios test: 46. #ThaliPeerPoolInterface - bad enqueues

2016-03-03T14:02:42.745Z - info: Running on ios test: 47. #ThaliPeerPoolInterface - do not allow same object type

2016-03-03T14:02:42.952Z - info: Running on android test: 39. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-03T14:02:43.150Z - info: Running on ios test: 48. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-03T14:02:43.489Z - info: Running on ios test: 49. compareBufferArrays

2016-03-03T14:02:43.551Z - info: Running on android test: 40. Make an HTTP request to /NotificationBeacons before calling start

2016-03-03T14:02:43.846Z - info: Running on ios test: 50. Call start twice and get error

2016-03-03T14:02:43.998Z - info: Running on android test: 41. #testThaliPeerAction - test getters

2016-03-03T14:02:44.274Z - info: Running on ios test: 51. Start and make sure it runs

2016-03-03T14:02:44.454Z - info: Running on android test: 42. #testThaliPeerAction - start and kill

2016-03-03T14:02:44.704Z - info: Running on ios test: 52. Make sure getTimeWhenRun is right after start

2016-03-03T14:02:44.942Z - info: Running on android test: 43. #testThaliPeerAction - double start

2016-03-03T14:02:45.186Z - info: Running on ios test: 53. Make sure getTimeWhenRun is -1 after function is called

2016-03-03T14:02:45.595Z - info: Running on android test: 44. #testThaliPeerAction - start after kill

2016-03-03T14:02:45.702Z - info: Running on ios test: 54. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-03T14:02:46.086Z - info: Running on android test: 45. #testThaliPeerAction - make sure ids are unique

2016-03-03T14:02:46.191Z - info: Running on ios test: 55. Test TransientState

2016-03-03T14:02:47.542Z - info: Running on android test: 46. #ThaliPeerPoolInterface - bad enqueues

2016-03-03T14:02:47.822Z - info: Running on ios test: 56. No peers and empty database

2016-03-03T14:02:48.198Z - info: Running on android test: 47. #ThaliPeerPoolInterface - do not allow same object type

2016-03-03T14:02:48.608Z - info: Running on ios test: 57. One peer and empty DB

2016-03-03T14:02:48.715Z - info: Running on android test: 48. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-03T14:02:49.074Z - info: Running on android test: 49. compareBufferArrays

2016-03-03T14:02:49.133Z - info: Running on ios test: 58. One peer with _Local set behind current seq

2016-03-03T14:02:49.651Z - info: Running on android test: 50. Call start twice and get error

2016-03-03T14:02:49.991Z - info: Running on ios test: 59. One peer with _Local set equal to current seq

2016-03-03T14:02:50.637Z - info: Running on android test: 51. Start and make sure it runs

2016-03-03T14:02:51.191Z - info: Running on android test: 52. Make sure getTimeWhenRun is right after start

2016-03-03T14:02:51.506Z - info: Running on ios test: 60. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-03T14:02:51.869Z - info: Running on android test: 53. Make sure getTimeWhenRun is -1 after function is called

2016-03-03T14:02:52.289Z - info: Running on ios test: 61. Three peers, one not in DB, one behind and one ahead

2016-03-03T14:02:52.406Z - info: Running on android test: 54. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-03T14:02:52.779Z - info: Running on android test: 55. Test TransientState

2016-03-03T14:02:53.121Z - info: Running on ios test: 62. More than maximum peers, make sure we only send maximum allowed

2016-03-03T14:02:53.198Z - info: Running on android test: 56. No peers and empty database

2016-03-03T14:02:53.656Z - info: Running on android test: 57. One peer and empty DB

2016-03-03T14:02:54.549Z - info: Running on ios test: 63. two peers with empty DB, update the doc

2016-03-03T14:02:54.570Z - info: Running on android test: 58. One peer with _Local set behind current seq

2016-03-03T14:02:55.151Z - info: Running on android test: 59. One peer with _Local set equal to current seq

2016-03-03T14:02:55.281Z - info: Running on ios test: 64. add doc and make sure tokens refresh when they expire

2016-03-03T14:02:55.705Z - info: Running on android test: 60. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-03T14:02:56.280Z - info: Running on android test: 61. Three peers, one not in DB, one behind and one ahead

2016-03-03T14:02:56.313Z - info: Running on ios test: 65. start and stop and start and stop

2016-03-03T14:02:57.028Z - info: Running on ios test: 66. two identical starts in a row

2016-03-03T14:02:57.185Z - info: Running on android test: 62. More than maximum peers, make sure we only send maximum allowed

2016-03-03T14:02:57.623Z - info: Running on ios test: 67. two different starts in a row

2016-03-03T14:02:58.333Z - info: Running on ios test: 68. two stops and a start and two stops

2016-03-03T14:02:58.686Z - info: Running on android test: 63. two peers with empty DB, update the doc

2016-03-03T14:02:59.116Z - info: Running on ios test: 69. we properly enqueue requests so no then needed

2016-03-03T14:02:59.542Z - info: Running on android test: 64. add doc and make sure tokens refresh when they expire

2016-03-03T14:02:59.799Z - info: Running on ios test: 70. test calculateSeqPointKeyId

2016-03-03T14:03:00.363Z - info: Running on ios test: 71. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-03T14:03:00.560Z - info: Running on android test: 65. start and stop and start and stop

2016-03-03T14:03:00.989Z - info: Running on ios test: 72. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-03T14:03:01.380Z - info: Running on android test: 66. two identical starts in a row

2016-03-03T14:03:01.680Z - info: Running on ios test: 73. messages with invalid location or USN should be ignored

2016-03-03T14:03:02.116Z - info: Running on ios test: 74. verify that Thali-specific messages are filtered correctly

2016-03-03T14:03:02.340Z - info: Running on android test: 67. two different starts in a row

2016-03-03T14:03:02.577Z - info: Running on ios test: 75. #startListeningForAdvertisements should fail if start not called

2016-03-03T14:03:03.205Z - info: Running on android test: 68. two stops and a start and two stops

2016-03-03T14:03:03.428Z - info: Running on ios test: 76. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-03T14:03:03.956Z - info: Running on ios test: 77. #start should fail if called twice in a row

2016-03-03T14:03:04.140Z - info: Running on android test: 69. we properly enqueue requests so no then needed

2016-03-03T14:03:04.415Z - info: Running on ios test: 78. should not be started after stop is called

2016-03-03T14:03:05.050Z - info: Running on ios test: 79. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-03T14:03:05.067Z - info: Running on android test: 70. test calculateSeqPointKeyId

2016-03-03T14:03:05.457Z - info: Running on ios test: 80. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-03T14:03:05.660Z - info: Running on android test: 71. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-03T14:03:05.895Z - info: Running on ios test: 81. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-03T14:03:06.223Z - info: Running on android test: 72. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-03T14:03:06.466Z - info: Running on ios test: 82. #stop can be called multiple times in a row

2016-03-03T14:03:06.983Z - info: Running on android test: 73. messages with invalid location or USN should be ignored

2016-03-03T14:03:07.019Z - info: Running on ios test: 83. #startListeningForAdvertisements can be called multiple times in a row

2016-03-03T14:03:07.552Z - info: Running on ios test: 84. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-03T14:03:07.557Z - info: Running on android test: 74. verify that Thali-specific messages are filtered correctly

2016-03-03T14:03:08.186Z - info: Running on ios test: 85. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-03T14:03:08.442Z - info: Running on android test: 75. #startListeningForAdvertisements should fail if start not called

2016-03-03T14:03:08.719Z - info: Running on ios test: 86. functions are run from a queue in the right order

2016-03-03T14:03:09.151Z - info: Test run on ios complete

2016-03-03T14:03:09.153Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-03T14:03:09.155Z - info: PLATFORM: ios
2016-03-03T14:03:09.156Z - info: RESULT: PASS
2016-03-03T14:03:09.157Z - info: 86 of 86 tests completed
2016-03-03T14:03:09.157Z - info: 86/86 passed (0 failures)
2016-03-03T14:03:09.158Z - info: --- Test Details ---



2016-03-03T14:03:09.159Z - info: 1. multiplex can send data - pass

2016-03-03T14:03:09.160Z - info: 2. enqueue and run in order - pass

2016-03-03T14:03:09.163Z - info: 3. enqueueAtTop and run backwards - pass

2016-03-03T14:03:09.163Z - info: 4. mix enqueue and enqueueAtTop - pass
2016-03-03T14:03:09.164Z - info: 5. queues handled independently - pass

2016-03-03T14:03:09.165Z - info: 6. basic - pass

2016-03-03T14:03:09.166Z - info: 7. another - pass

2016-03-03T14:03:09.167Z - info: 8. #startListeningForAdvertisements should fail if start not called - pass

2016-03-03T14:03:09.168Z - info: 9. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-03T14:03:09.169Z - info: 10. should be able to call #stopListeningForAdvertisements many times - pass

2016-03-03T14:03:09.170Z - info: 11. should be able to call #startListeningForAdvertisements many times - pass

2016-03-03T14:03:09.171Z - info: 12. should be able to call #startUpdateAdvertisingAndListening many times - pass
2016-03-03T14:03:09.172Z - info: 13. should be able to call #stopAdvertisingAndListening many times - pass
2016-03-03T14:03:09.173Z - info: 14. #start should fail if called twice in a row - pass

2016-03-03T14:03:09.173Z - info: 15. does not emit duplicate discoveryAdvertisingStateUpdate - pass
2016-03-03T14:03:09.174Z - info: 16. does not send duplicate availability changes - pass

2016-03-03T14:03:09.175Z - info: 17. can get the network status - pass

2016-03-03T14:03:09.176Z - info: 18. wifi peer is marked unavailable if announcements stop - pass

2016-03-03T14:03:09.177Z - info: 19. can get the network status before starting - pass

2016-03-03T14:03:09.178Z - info: 20. #generatePreambleAndBeacons bad args - pass

2016-03-03T14:03:09.179Z - info: 21. #generatePreambleAndBeacons empty keys to notify - pass
2016-03-03T14:03:09.180Z - info: 22. #generatePreambleAndBeacons multiple keys to notify - pass

2016-03-03T14:03:09.180Z - info: 23. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass

2016-03-03T14:03:09.181Z - info: 24. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass

2016-03-03T14:03:09.182Z - info: 25. #parseBeacons expiration out of range lower - pass

2016-03-03T14:03:09.183Z - info: 26. #parseBeacons expiration out of range lower - pass

2016-03-03T14:03:09.184Z - info: 27. #parseBeacons no beacons returns null - pass

2016-03-03T14:03:09.185Z - info: 28. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass
2016-03-03T14:03:09.186Z - info: 29. #parseBeacons addressBookCallback fails decrypt - pass

2016-03-03T14:03:09.187Z - info: 30. #parseBeacons addressBookCallback returns no matches - pass

2016-03-03T14:03:09.188Z - info: 31. #parseBeacons addressBookCallback returns spurious match - pass

2016-03-03T14:03:09.189Z - info: 32. #parseBeacons addressBookCallback returns public key - pass

2016-03-03T14:03:09.189Z - info: 33. #parseBeacons with beacons both for and not for the user - pass
2016-03-03T14:03:09.190Z - info: 34. Start and stop ThaliNotificationServer - pass

2016-03-03T14:03:09.191Z - info: 35. Pass an empty array to ThaliNotificationServer.start - pass

2016-03-03T14:03:09.192Z - info: 36. Pass a string to ThaliNotificationServer.start - pass

2016-03-03T14:03:09.193Z - info: 37. Pass an empty parameter to ThaliNotificationServer.start - pass

2016-03-03T14:03:09.194Z - info: 38. Make an HTTP request to /NotificationBeacons - pass

2016-03-03T14:03:09.195Z - info: 39. Make an HTTP request to /NotificationBeacons (no keys) - pass
2016-03-03T14:03:09.196Z - info: 40. Make an HTTP request to /NotificationBeacons before calling start - pass

2016-03-03T14:03:09.196Z - info: 41. #testThaliPeerAction - test getters - pass

2016-03-03T14:03:09.197Z - info: 42. #testThaliPeerAction - start and kill - pass

2016-03-03T14:03:09.198Z - info: 43. #testThaliPeerAction - double start - pass

2016-03-03T14:03:09.199Z - info: 44. #testThaliPeerAction - start after kill - pass
2016-03-03T14:03:09.199Z - info: 45. #testThaliPeerAction - make sure ids are unique - pass

2016-03-03T14:03:09.200Z - info: 46. #ThaliPeerPoolInterface - bad enqueues - pass

2016-03-03T14:03:09.201Z - info: 47. #ThaliPeerPoolInterface - do not allow same object type - pass

2016-03-03T14:03:09.202Z - info: 48. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass

2016-03-03T14:03:09.203Z - info: 49. compareBufferArrays - pass
2016-03-03T14:03:09.204Z - info: 50. Call start twice and get error - pass

2016-03-03T14:03:09.204Z - info: 51. Start and make sure it runs - pass

2016-03-03T14:03:09.205Z - info: 52. Make sure getTimeWhenRun is right after start - pass

2016-03-03T14:03:09.206Z - info: 53. Make sure getTimeWhenRun is -1 after function is called - pass
2016-03-03T14:03:09.207Z - info: 54. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass

2016-03-03T14:03:09.208Z - info: 55. Test TransientState - pass

2016-03-03T14:03:09.208Z - info: 56. No peers and empty database - pass

2016-03-03T14:03:09.209Z - info: 57. One peer and empty DB - pass

2016-03-03T14:03:09.210Z - info: 58. One peer with _Local set behind current seq - pass
2016-03-03T14:03:09.211Z - info: 59. One peer with _Local set equal to current seq - pass

2016-03-03T14:03:09.212Z - info: 60. One peer with _Local set ahead of current seq (and no this should not happen) - pass

2016-03-03T14:03:09.213Z - info: 61. Three peers, one not in DB, one behind and one ahead - pass

2016-03-03T14:03:09.213Z - info: 62. More than maximum peers, make sure we only send maximum allowed - pass

2016-03-03T14:03:09.214Z - info: 63. two peers with empty DB, update the doc - pass
2016-03-03T14:03:09.215Z - info: 64. add doc and make sure tokens refresh when they expire - pass

2016-03-03T14:03:09.216Z - info: 65. start and stop and start and stop - pass

2016-03-03T14:03:09.217Z - info: 66. two identical starts in a row - pass
2016-03-03T14:03:09.217Z - info: 67. two different starts in a row - pass
2016-03-03T14:03:09.218Z - info: 68. two stops and a start and two stops - pass
2016-03-03T14:03:09.219Z - info: 69. we properly enqueue requests so no then needed - pass

2016-03-03T14:03:09.219Z - info: 70. test calculateSeqPointKeyId - pass
2016-03-03T14:03:09.220Z - info: 71. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass

2016-03-03T14:03:09.221Z - info: 72. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-03-03T14:03:09.222Z - info: 73. messages with invalid location or USN should be ignored - pass

2016-03-03T14:03:09.223Z - info: 74. verify that Thali-specific messages are filtered correctly - pass

2016-03-03T14:03:09.224Z - info: 75. #startListeningForAdvertisements should fail if start not called - pass

2016-03-03T14:03:09.225Z - info: 76. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-03T14:03:09.226Z - info: 77. #start should fail if called twice in a row - pass

2016-03-03T14:03:09.226Z - info: 78. should not be started after stop is called - pass

2016-03-03T14:03:09.227Z - info: 79. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass

2016-03-03T14:03:09.228Z - info: 80. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass

2016-03-03T14:03:09.229Z - info: 81. #startUpdateAdvertisingAndListening should start hosting given router object - pass
2016-03-03T14:03:09.230Z - info: 82. #stop can be called multiple times in a row - pass

2016-03-03T14:03:09.230Z - info: 83. #startListeningForAdvertisements can be called multiple times in a row - pass

2016-03-03T14:03:09.231Z - info: 84. #stopListeningForAdvertisements can be called multiple times in a row - pass

2016-03-03T14:03:09.232Z - info: 85. #stopAdvertisingAndListening can be called multiple times in a row - pass
2016-03-03T14:03:09.233Z - info: 86. functions are run from a queue in the right order - pass
2016-03-03T14:03:09.233Z - info: 

-== END ==-
2016-03-03T14:03:09.245Z - info: Running on android test: 76. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-03T14:03:09.633Z - info: Running on android test: 77. #start should fail if called twice in a row

2016-03-03T14:03:10.127Z - info: Running on android test: 78. should not be started after stop is called

2016-03-03T14:03:10.547Z - info: Running on android test: 79. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-03T14:03:11.407Z - info: Running on android test: 80. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-03T14:03:11.808Z - debug: Socket disconnected: transport close 3 (Apple-IpadAir2-1)

2016-03-03T14:03:12.151Z - info: Running on android test: 81. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-03T14:03:12.510Z - debug: Socket disconnected: transport close 0 (Apple-Iphone6-1)

2016-03-03T14:03:12.802Z - info: Running on android test: 82. #stop can be called multiple times in a row

2016-03-03T14:03:13.174Z - info: Running on android test: 83. #startListeningForAdvertisements can be called multiple times in a row

2016-03-03T14:03:13.587Z - info: Running on android test: 84. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-03T14:03:15.949Z - info: Running on android test: 85. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-03T14:03:16.713Z - info: Running on android test: 86. functions are run from a queue in the right order

2016-03-03T14:03:17.238Z - info: Test run on android complete

2016-03-03T14:03:17.239Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-03T14:03:17.244Z - info: PLATFORM: android

2016-03-03T14:03:17.245Z - info: RESULT: PASS

2016-03-03T14:03:17.246Z - info: 86 of 86 tests completed

2016-03-03T14:03:17.248Z - info: 86/86 passed (0 failures)

2016-03-03T14:03:17.249Z - info: --- Test Details ---



2016-03-03T14:03:17.250Z - info: 1. multiplex can send data - pass

2016-03-03T14:03:17.251Z - info: 2. enqueue and run in order - pass

2016-03-03T14:03:17.251Z - info: 3. enqueueAtTop and run backwards - pass

2016-03-03T14:03:17.252Z - info: 4. mix enqueue and enqueueAtTop - pass

2016-03-03T14:03:17.253Z - info: 5. queues handled independently - pass

2016-03-03T14:03:17.254Z - info: 6. basic - pass

2016-03-03T14:03:17.255Z - info: 7. another - pass

2016-03-03T14:03:17.256Z - info: 8. #startListeningForAdvertisements should fail if start not called - pass

2016-03-03T14:03:17.257Z - info: 9. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-03T14:03:17.258Z - info: 10. should be able to call #stopListeningForAdvertisements many times - pass

2016-03-03T14:03:17.259Z - info: 11. should be able to call #startListeningForAdvertisements many times - pass

2016-03-03T14:03:17.260Z - info: 12. should be able to call #startUpdateAdvertisingAndListening many times - pass

2016-03-03T14:03:17.261Z - info: 13. should be able to call #stopAdvertisingAndListening many times - pass

2016-03-03T14:03:17.262Z - info: 14. #start should fail if called twice in a row - pass
2016-03-03T14:03:17.263Z - info: 15. does not emit duplicate discoveryAdvertisingStateUpdate - pass

2016-03-03T14:03:17.264Z - info: 16. does not send duplicate availability changes - pass

2016-03-03T14:03:17.265Z - info: 17. can get the network status - pass

2016-03-03T14:03:17.265Z - info: 18. wifi peer is marked unavailable if announcements stop - pass

2016-03-03T14:03:17.266Z - info: 19. can get the network status before starting - pass

2016-03-03T14:03:17.267Z - info: 20. #generatePreambleAndBeacons bad args - pass

2016-03-03T14:03:17.268Z - info: 21. #generatePreambleAndBeacons empty keys to notify - pass

2016-03-03T14:03:17.269Z - info: 22. #generatePreambleAndBeacons multiple keys to notify - pass
2016-03-03T14:03:17.270Z - info: 23. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass

2016-03-03T14:03:17.271Z - info: 24. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass

2016-03-03T14:03:17.272Z - info: 25. #parseBeacons expiration out of range lower - pass

2016-03-03T14:03:17.273Z - info: 26. #parseBeacons expiration out of range lower - pass

2016-03-03T14:03:17.274Z - info: 27. #parseBeacons no beacons returns null - pass

2016-03-03T14:03:17.275Z - info: 28. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass

2016-03-03T14:03:17.276Z - info: 29. #parseBeacons addressBookCallback fails decrypt - pass

2016-03-03T14:03:17.277Z - info: 30. #parseBeacons addressBookCallback returns no matches - pass

2016-03-03T14:03:17.278Z - info: 31. #parseBeacons addressBookCallback returns spurious match - pass

2016-03-03T14:03:17.278Z - info: 32. #parseBeacons addressBookCallback returns public key - pass

2016-03-03T14:03:17.279Z - info: 33. #parseBeacons with beacons both for and not for the user - pass

2016-03-03T14:03:17.280Z - info: 34. Start and stop ThaliNotificationServer - pass

2016-03-03T14:03:17.281Z - info: 35. Pass an empty array to ThaliNotificationServer.start - pass

2016-03-03T14:03:17.282Z - info: 36. Pass a string to ThaliNotificationServer.start - pass

2016-03-03T14:03:17.283Z - info: 37. Pass an empty parameter to ThaliNotificationServer.start - pass

2016-03-03T14:03:17.284Z - info: 38. Make an HTTP request to /NotificationBeacons - pass
2016-03-03T14:03:17.285Z - info: 39. Make an HTTP request to /NotificationBeacons (no keys) - pass

2016-03-03T14:03:17.286Z - info: 40. Make an HTTP request to /NotificationBeacons before calling start - pass

2016-03-03T14:03:17.287Z - info: 41. #testThaliPeerAction - test getters - pass

2016-03-03T14:03:17.288Z - info: 42. #testThaliPeerAction - start and kill - pass

2016-03-03T14:03:17.289Z - info: 43. #testThaliPeerAction - double start - pass

2016-03-03T14:03:17.289Z - info: 44. #testThaliPeerAction - start after kill - pass

2016-03-03T14:03:17.290Z - info: 45. #testThaliPeerAction - make sure ids are unique - pass

2016-03-03T14:03:17.291Z - info: 46. #ThaliPeerPoolInterface - bad enqueues - pass

2016-03-03T14:03:17.292Z - info: 47. #ThaliPeerPoolInterface - do not allow same object type - pass

2016-03-03T14:03:17.294Z - info: 48. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass

2016-03-03T14:03:17.294Z - info: 49. compareBufferArrays - pass

2016-03-03T14:03:17.295Z - info: 50. Call start twice and get error - pass

2016-03-03T14:03:17.296Z - info: 51. Start and make sure it runs - pass

2016-03-03T14:03:17.297Z - info: 52. Make sure getTimeWhenRun is right after start - pass

2016-03-03T14:03:17.298Z - info: 53. Make sure getTimeWhenRun is -1 after function is called - pass

2016-03-03T14:03:17.299Z - info: 54. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass

2016-03-03T14:03:17.300Z - info: 55. Test TransientState - pass

2016-03-03T14:03:17.301Z - info: 56. No peers and empty database - pass

2016-03-03T14:03:17.302Z - info: 57. One peer and empty DB - pass

2016-03-03T14:03:17.303Z - info: 58. One peer with _Local set behind current seq - pass

2016-03-03T14:03:17.304Z - info: 59. One peer with _Local set equal to current seq - pass
2016-03-03T14:03:17.305Z - info: 60. One peer with _Local set ahead of current seq (and no this should not happen) - pass

2016-03-03T14:03:17.306Z - info: 61. Three peers, one not in DB, one behind and one ahead - pass

2016-03-03T14:03:17.307Z - info: 62. More than maximum peers, make sure we only send maximum allowed - pass

2016-03-03T14:03:17.308Z - info: 63. two peers with empty DB, update the doc - pass

2016-03-03T14:03:17.309Z - info: 64. add doc and make sure tokens refresh when they expire - pass

2016-03-03T14:03:17.310Z - info: 65. start and stop and start and stop - pass

2016-03-03T14:03:17.311Z - info: 66. two identical starts in a row - pass

2016-03-03T14:03:17.312Z - info: 67. two different starts in a row - pass

2016-03-03T14:03:17.313Z - info: 68. two stops and a start and two stops - pass

2016-03-03T14:03:17.314Z - info: 69. we properly enqueue requests so no then needed - pass

2016-03-03T14:03:17.315Z - info: 70. test calculateSeqPointKeyId - pass

2016-03-03T14:03:17.315Z - info: 71. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass

2016-03-03T14:03:17.316Z - info: 72. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-03-03T14:03:17.317Z - info: 73. messages with invalid location or USN should be ignored - pass

2016-03-03T14:03:17.318Z - info: 74. verify that Thali-specific messages are filtered correctly - pass

2016-03-03T14:03:17.319Z - info: 75. #startListeningForAdvertisements should fail if start not called - pass

2016-03-03T14:03:17.320Z - info: 76. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-03T14:03:17.321Z - info: 77. #start should fail if called twice in a row - pass

2016-03-03T14:03:17.322Z - info: 78. should not be started after stop is called - pass

2016-03-03T14:03:17.323Z - info: 79. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass

2016-03-03T14:03:17.324Z - info: 80. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass
2016-03-03T14:03:17.325Z - info: 81. #startUpdateAdvertisingAndListening should start hosting given router object - pass

2016-03-03T14:03:17.326Z - info: 82. #stop can be called multiple times in a row - pass

2016-03-03T14:03:17.327Z - info: 83. #startListeningForAdvertisements can be called multiple times in a row - pass

2016-03-03T14:03:17.329Z - info: 84. #stopListeningForAdvertisements can be called multiple times in a row - pass

2016-03-03T14:03:17.329Z - info: 85. #stopAdvertisingAndListening can be called multiple times in a row - pass

2016-03-03T14:03:17.330Z - info: 86. functions are run from a queue in the right order - pass

2016-03-03T14:03:17.338Z - info: 

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
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:null 
child process exited with code null on device f56ad48d 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/6136236661fd38c_Make_CI_build_and_unit_tests_pass_vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/6136236661fd38c_Make_CI_build_and_unit_tests_pass_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 09a9416e0297d102 app:com.test.thalitest code:0 
child process exited with code 0 on device 09a9416e0297d102 
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Android task is completed. [FAILED]
```
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/6136236661fd38c_Make_CI_build_and_unit_tests_pass_vjrantal/thali02_LGE-Nexus 5.md)

[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/6136236661fd38c_Make_CI_build_and_unit_tests_pass_vjrantal/thali02_LGE-LG-D722.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD8553bed2d08 app:com.test.thalitest code:0 
child process exited with code 0 on device LGD8553bed2d08 
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:0 
child process exited with code 0 on device 320414cd475f91e3 
Android task is completed. [FAILED]
```
[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/6136236661fd38c_Make_CI_build_and_unit_tests_pass_vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/6136236661fd38c_Make_CI_build_and_unit_tests_pass_vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
STOP log received from  0be0c6c6 Test has  SUCCEEDED
Device test finished on 0be0c6c6 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/6136236661fd38c_Make_CI_build_and_unit_tests_pass_vjrantal/thali04_samsung-SM-G900F.md)

[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/6136236661fd38c_Make_CI_build_and_unit_tests_pass_vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/6136236661fd38c_Make_CI_build_and_unit_tests_pass_vjrantal/thali04_samsung-SM-N910C.md)

####Node name: thali05
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device HT4BLJT02274 app:com.test.thalitest code:0 
child process exited with code 0 on device HT4BLJT02274 
Error! Unexpected exit on device 1d6a772d app:com.test.thalitest code:null 
child process exited with code null on device 1d6a772d 
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1G429CRK 
Error! Unexpected exit on device 954a12ed app:com.test.thalitest code:0 
child process exited with code 0 on device 954a12ed 
Android task is completed. [FAILED]
```
[htc-Nexus 9](https://github.com/ThaliTester/TestResults/blob/6136236661fd38c_Make_CI_build_and_unit_tests_pass_vjrantal/thali05_htc-Nexus 9.md)

[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/6136236661fd38c_Make_CI_build_and_unit_tests_pass_vjrantal/thali05_samsung-SM-N9005.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/6136236661fd38c_Make_CI_build_and_unit_tests_pass_vjrantal/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/6136236661fd38c_Make_CI_build_and_unit_tests_pass_vjrantal/thali05_samsung-SM-G800H.md)

####Node name: thali06
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:0 
child process exited with code 0 on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:0 
child process exited with code 0 on device FA55PYS00566 
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:0 
child process exited with code 0 on device 022678fb504e29b0 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/6136236661fd38c_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/6136236661fd38c_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/6136236661fd38c_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:0 
child process exited with code 0 on device 4db5c8cc 
Error! Unexpected exit on device c5afcdcb app:com.test.thalitest code:null 
child process exited with code null on device c5afcdcb 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/6136236661fd38c_Make_CI_build_and_unit_tests_pass_vjrantal/thali07_samsung-SM-A500FU.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/6136236661fd38c_Make_CI_build_and_unit_tests_pass_vjrantal/thali07_samsung-SM-G900F.md)

####Node name: thali08
Console output:
```
STOP log received from  4325e43f Test has  SUCCEEDED
Device test finished on 4325e43f 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device HT574YC04723 app:com.test.thalitest code:null 
child process exited with code null on device HT574YC04723 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/6136236661fd38c_Make_CI_build_and_unit_tests_pass_vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/6136236661fd38c_Make_CI_build_and_unit_tests_pass_vjrantal/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device CC51WYC03425 app:com.test.thalitest code:0 
child process exited with code 0 on device CC51WYC03425 
Error! Unexpected exit on device 0c6a0f3c0bdb4e77 app:com.test.thalitest code:0 
child process exited with code 0 on device 0c6a0f3c0bdb4e77 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/6136236661fd38c_Make_CI_build_and_unit_tests_pass_vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/6136236661fd38c_Make_CI_build_and_unit_tests_pass_vjrantal/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/6136236661fd38c_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/6136236661fd38c_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/6136236661fd38c_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/6136236661fd38c_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone6-1.md)



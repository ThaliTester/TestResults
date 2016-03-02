#### Test 61362366121daa0 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":22}}
2016-03-02T13:39:34.308Z - info: listening on *:3000

2016-03-02T13:39:34.956Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:0

2016-03-02T13:39:36.882Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:1

2016-03-02T13:39:38.018Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:2

2016-03-02T13:39:38.020Z - info: Required number of android devices presented (2)

2016-03-02T13:39:38.024Z - info: Starting unit test run for platform: android

2016-03-02T13:39:38.590Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:3

2016-03-02T13:39:38.592Z - info: Discarding surplus device: LGE-LG-H815

2016-03-02T13:39:38.681Z - info: Running on android test: 1. multiplex can send data

2016-03-02T13:39:39.147Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:4

2016-03-02T13:39:39.150Z - info: Required number of ios devices presented (2)

2016-03-02T13:39:39.153Z - info: Starting unit test run for platform: ios

2016-03-02T13:39:39.325Z - info: Running on android test: 2. enqueue and run in order

2016-03-02T13:39:39.333Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:6

2016-03-02T13:39:39.334Z - info: Discarding surplus device: Apple-IpadAir2-1

2016-03-02T13:39:39.728Z - info: Running on ios test: 1. multiplex can send data

2016-03-02T13:39:39.803Z - debug: Socket disconnected: transport close 3 (LGE-LG-H815)

2016-03-02T13:39:40.187Z - info: Running on android test: 3. enqueueAtTop and run backwards

2016-03-02T13:39:40.406Z - info: Running on ios test: 2. enqueue and run in order

2016-03-02T13:39:40.647Z - info: Running on android test: 4. mix enqueue and enqueueAtTop

2016-03-02T13:39:40.921Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:5

2016-03-02T13:39:40.922Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-02T13:39:41.000Z - info: Running on ios test: 3. enqueueAtTop and run backwards

2016-03-02T13:39:41.275Z - info: Running on android test: 5. queues handled independently

2016-03-02T13:39:41.381Z - info: Running on ios test: 4. mix enqueue and enqueueAtTop

2016-03-02T13:39:41.703Z - info: Running on android test: 6. basic

2016-03-02T13:39:41.895Z - debug: Socket disconnected: transport close 6 (Apple-IpadAir2-1)

2016-03-02T13:39:41.919Z - info: Running on ios test: 5. queues handled independently

2016-03-02T13:39:42.108Z - info: Running on android test: 7. another

2016-03-02T13:39:42.322Z - info: Running on ios test: 6. basic

2016-03-02T13:39:42.621Z - info: Running on android test: 8. #startListeningForAdvertisements should fail if start not called

2016-03-02T13:39:42.682Z - info: Running on ios test: 7. another

2016-03-02T13:39:43.072Z - info: Running on ios test: 8. #startListeningForAdvertisements should fail if start not called

2016-03-02T13:39:43.077Z - info: Running on android test: 9. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-02T13:39:43.435Z - info: Running on ios test: 9. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-02T13:39:43.532Z - info: Running on android test: 10. should be able to call #stopListeningForAdvertisements many times

2016-03-02T13:39:43.536Z - debug: Socket disconnected: transport close 5 (Apple-Iphone5s-1)

2016-03-02T13:39:43.826Z - info: Running on ios test: 10. should be able to call #stopListeningForAdvertisements many times

2016-03-02T13:39:44.035Z - info: Running on android test: 11. should be able to call #startListeningForAdvertisements many times

2016-03-02T13:39:44.224Z - info: Running on ios test: 11. should be able to call #startListeningForAdvertisements many times

2016-03-02T13:39:44.493Z - info: Running on android test: 12. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-02T13:39:44.561Z - info: Running on ios test: 12. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-02T13:39:44.924Z - info: Running on ios test: 13. should be able to call #stopAdvertisingAndListening many times

2016-03-02T13:39:45.014Z - info: Running on android test: 13. should be able to call #stopAdvertisingAndListening many times

2016-03-02T13:39:45.232Z - info: Running on ios test: 14. #start should fail if called twice in a row

2016-03-02T13:39:45.378Z - info: Running on android test: 14. #start should fail if called twice in a row

2016-03-02T13:39:45.592Z - info: Running on ios test: 15. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-02T13:39:45.805Z - info: Running on android test: 15. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-02T13:39:45.923Z - info: Running on ios test: 16. does not send duplicate availability changes

2016-03-02T13:39:46.226Z - info: Running on ios test: 17. can get the network status

2016-03-02T13:39:46.241Z - info: Running on android test: 16. does not send duplicate availability changes

2016-03-02T13:39:46.663Z - info: Running on ios test: 18. wifi peer is marked unavailable if announcements stop

2016-03-02T13:39:46.670Z - info: Running on android test: 17. can get the network status

2016-03-02T13:39:47.079Z - info: Running on android test: 18. wifi peer is marked unavailable if announcements stop

2016-03-02T13:39:48.042Z - info: Running on ios test: 19. can get the network status before starting

2016-03-02T13:39:48.316Z - info: Running on ios test: 20. #generatePreambleAndBeacons bad args

2016-03-02T13:39:48.516Z - info: Running on android test: 19. can get the network status before starting

2016-03-02T13:39:48.628Z - info: Running on ios test: 21. #generatePreambleAndBeacons empty keys to notify

2016-03-02T13:39:48.866Z - info: Running on android test: 20. #generatePreambleAndBeacons bad args

2016-03-02T13:39:48.975Z - info: Running on ios test: 22. #generatePreambleAndBeacons multiple keys to notify

2016-03-02T13:39:49.325Z - info: Running on android test: 21. #generatePreambleAndBeacons empty keys to notify

2016-03-02T13:39:49.476Z - info: Running on ios test: 23. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-02T13:39:49.770Z - info: Running on android test: 22. #generatePreambleAndBeacons multiple keys to notify

2016-03-02T13:39:50.008Z - info: Running on ios test: 24. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-02T13:39:50.483Z - info: Running on android test: 23. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-02T13:39:50.556Z - info: Running on ios test: 25. #parseBeacons expiration out of range lower

2016-03-02T13:39:50.950Z - info: Running on ios test: 26. #parseBeacons expiration out of range lower

2016-03-02T13:39:51.023Z - info: Running on android test: 24. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-02T13:39:51.594Z - info: Running on ios test: 27. #parseBeacons no beacons returns null

2016-03-02T13:39:51.699Z - info: Running on android test: 25. #parseBeacons expiration out of range lower

2016-03-02T13:39:52.170Z - info: Running on ios test: 28. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-02T13:39:52.487Z - info: Running on android test: 26. #parseBeacons expiration out of range lower

2016-03-02T13:39:52.693Z - info: Running on ios test: 29. #parseBeacons addressBookCallback fails decrypt

2016-03-02T13:39:53.116Z - info: Running on android test: 27. #parseBeacons no beacons returns null

2016-03-02T13:39:53.192Z - info: Running on ios test: 30. #parseBeacons addressBookCallback returns no matches

2016-03-02T13:39:53.594Z - info: Running on android test: 28. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-02T13:39:53.656Z - info: Running on ios test: 31. #parseBeacons addressBookCallback returns spurious match

2016-03-02T13:39:54.101Z - info: Running on android test: 29. #parseBeacons addressBookCallback fails decrypt

2016-03-02T13:39:54.267Z - info: Running on ios test: 32. #parseBeacons addressBookCallback returns public key

2016-03-02T13:39:54.946Z - info: Running on ios test: 33. #parseBeacons with beacons both for and not for the user

2016-03-02T13:39:55.045Z - info: Running on android test: 30. #parseBeacons addressBookCallback returns no matches

2016-03-02T13:39:55.414Z - info: Running on ios test: 34. Start and stop ThaliNotificationServer

2016-03-02T13:39:55.728Z - info: Running on android test: 31. #parseBeacons addressBookCallback returns spurious match

2016-03-02T13:39:55.961Z - info: Running on ios test: 35. Pass an empty array to ThaliNotificationServer.start

2016-03-02T13:39:56.393Z - info: Running on android test: 32. #parseBeacons addressBookCallback returns public key

2016-03-02T13:39:56.524Z - info: Running on ios test: 36. Pass a string to ThaliNotificationServer.start

2016-03-02T13:39:56.899Z - info: Running on ios test: 37. Pass an empty parameter to ThaliNotificationServer.start

2016-03-02T13:39:57.029Z - info: Running on android test: 33. #parseBeacons with beacons both for and not for the user

2016-03-02T13:39:57.299Z - info: Running on ios test: 38. Make an HTTP request to /NotificationBeacons

2016-03-02T13:39:57.459Z - info: Running on android test: 34. Start and stop ThaliNotificationServer

2016-03-02T13:39:57.544Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:7

2016-03-02T13:39:57.545Z - info: Discarding surplus device: motorola-Nexus 6

2016-03-02T13:39:57.811Z - info: Running on ios test: 39. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-02T13:39:58.047Z - info: Running on android test: 35. Pass an empty array to ThaliNotificationServer.start

2016-03-02T13:39:58.191Z - info: Running on ios test: 40. Make an HTTP request to /NotificationBeacons before calling start

2016-03-02T13:39:58.346Z - debug: Socket disconnected: transport close 7 (motorola-Nexus 6)

2016-03-02T13:39:58.580Z - info: Running on android test: 36. Pass a string to ThaliNotificationServer.start

2016-03-02T13:39:58.661Z - info: Running on ios test: 41. #testThaliPeerAction - test getters

2016-03-02T13:39:59.052Z - info: Running on android test: 37. Pass an empty parameter to ThaliNotificationServer.start

2016-03-02T13:39:59.062Z - info: Running on ios test: 42. #testThaliPeerAction - start and kill

2016-03-02T13:39:59.389Z - info: Running on ios test: 43. #testThaliPeerAction - double start

2016-03-02T13:39:59.421Z - info: Running on android test: 38. Make an HTTP request to /NotificationBeacons

2016-03-02T13:39:59.689Z - info: Running on ios test: 44. #testThaliPeerAction - start after kill

2016-03-02T13:39:59.949Z - info: Running on ios test: 45. #testThaliPeerAction - make sure ids are unique

2016-03-02T13:40:00.041Z - info: Running on android test: 39. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-02T13:40:00.306Z - info: Running on ios test: 46. #ThaliPeerPoolInterface - bad enqueues

2016-03-02T13:40:00.504Z - info: Running on android test: 40. Make an HTTP request to /NotificationBeacons before calling start

2016-03-02T13:40:00.629Z - info: Running on ios test: 47. #ThaliPeerPoolInterface - do not allow same object type

2016-03-02T13:40:00.951Z - info: Running on ios test: 48. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-02T13:40:00.993Z - info: Running on android test: 41. #testThaliPeerAction - test getters

2016-03-02T13:40:01.302Z - info: Running on ios test: 49. compareBufferArrays

2016-03-02T13:40:01.318Z - info: Running on android test: 42. #testThaliPeerAction - start and kill

2016-03-02T13:40:01.692Z - info: Running on ios test: 50. Call start twice and get error

2016-03-02T13:40:01.835Z - info: Running on android test: 43. #testThaliPeerAction - double start

2016-03-02T13:40:02.029Z - info: Running on ios test: 51. Start and make sure it runs

2016-03-02T13:40:02.162Z - info: Running on android test: 44. #testThaliPeerAction - start after kill

2016-03-02T13:40:02.333Z - info: Running on ios test: 52. Make sure getTimeWhenRun is right after start

2016-03-02T13:40:02.551Z - info: Running on android test: 45. #testThaliPeerAction - make sure ids are unique

2016-03-02T13:40:02.736Z - info: Running on ios test: 53. Make sure getTimeWhenRun is -1 after function is called

2016-03-02T13:40:03.150Z - info: Running on android test: 46. #ThaliPeerPoolInterface - bad enqueues

2016-03-02T13:40:03.202Z - info: Running on ios test: 54. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-02T13:40:03.616Z - info: Running on ios test: 55. Test TransientState

2016-03-02T13:40:03.619Z - info: Running on android test: 47. #ThaliPeerPoolInterface - do not allow same object type

2016-03-02T13:40:04.054Z - info: Running on ios test: 56. No peers and empty database

2016-03-02T13:40:04.077Z - info: Running on android test: 48. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-02T13:40:04.570Z - info: Running on android test: 49. compareBufferArrays

2016-03-02T13:40:04.607Z - info: Running on ios test: 57. One peer and empty DB

2016-03-02T13:40:05.052Z - info: Running on android test: 50. Call start twice and get error

2016-03-02T13:40:05.251Z - info: Running on ios test: 58. One peer with _Local set behind current seq

2016-03-02T13:40:05.525Z - info: Running on android test: 51. Start and make sure it runs

2016-03-02T13:40:05.964Z - info: Running on android test: 52. Make sure getTimeWhenRun is right after start

2016-03-02T13:40:06.083Z - info: Running on ios test: 59. One peer with _Local set equal to current seq

2016-03-02T13:40:06.314Z - info: Running on android test: 53. Make sure getTimeWhenRun is -1 after function is called

2016-03-02T13:40:06.754Z - info: Running on android test: 54. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-02T13:40:06.770Z - info: Running on ios test: 60. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-02T13:40:07.265Z - info: Running on android test: 55. Test TransientState

2016-03-02T13:40:07.535Z - info: Running on ios test: 61. Three peers, one not in DB, one behind and one ahead

2016-03-02T13:40:07.648Z - info: Running on android test: 56. No peers and empty database

2016-03-02T13:40:08.224Z - info: Running on android test: 57. One peer and empty DB

2016-03-02T13:40:08.456Z - info: Running on ios test: 62. More than maximum peers, make sure we only send maximum allowed

2016-03-02T13:40:08.806Z - info: Running on android test: 58. One peer with _Local set behind current seq

2016-03-02T13:40:09.441Z - info: Running on android test: 59. One peer with _Local set equal to current seq

2016-03-02T13:40:09.767Z - info: Running on ios test: 63. two peers with empty DB, update the doc

2016-03-02T13:40:10.092Z - info: Running on android test: 60. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-02T13:40:10.519Z - info: Running on ios test: 64. add doc and make sure tokens refresh when they expire

2016-03-02T13:40:10.721Z - info: Running on android test: 61. Three peers, one not in DB, one behind and one ahead

2016-03-02T13:40:11.435Z - info: Running on android test: 62. More than maximum peers, make sure we only send maximum allowed

2016-03-02T13:40:11.550Z - info: Running on ios test: 65. start and stop and start and stop

2016-03-02T13:40:12.164Z - info: Running on ios test: 66. two identical starts in a row

2016-03-02T13:40:12.553Z - info: Running on android test: 63. two peers with empty DB, update the doc

2016-03-02T13:40:12.791Z - info: Running on ios test: 67. two different starts in a row

2016-03-02T13:40:13.385Z - info: Running on android test: 64. add doc and make sure tokens refresh when they expire

2016-03-02T13:40:13.493Z - info: Running on ios test: 68. two stops and a start and two stops

2016-03-02T13:40:14.117Z - info: Running on ios test: 69. we properly enqueue requests so no then needed

2016-03-02T13:40:14.327Z - info: Running on android test: 65. start and stop and start and stop

2016-03-02T13:40:14.670Z - info: Running on ios test: 70. test calculateSeqPointKeyId

2016-03-02T13:40:15.121Z - info: Running on ios test: 71. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-02T13:40:15.161Z - info: Running on android test: 66. two identical starts in a row

2016-03-02T13:40:15.492Z - info: Running on ios test: 72. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-02T13:40:15.723Z - info: Running on android test: 67. two different starts in a row

2016-03-02T13:40:15.954Z - info: Running on ios test: 73. messages with invalid location or USN should be ignored

2016-03-02T13:40:16.281Z - info: Running on ios test: 74. verify that Thali-specific messages are filtered correctly

2016-03-02T13:40:16.300Z - info: Running on android test: 68. two stops and a start and two stops

2016-03-02T13:40:16.687Z - info: Running on ios test: 75. #startListeningForAdvertisements should fail if start not called

2016-03-02T13:40:16.879Z - info: Running on android test: 69. we properly enqueue requests so no then needed

2016-03-02T13:40:17.048Z - info: Running on ios test: 76. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-02T13:40:17.297Z - info: Running on ios test: 77. #start should fail if called twice in a row

2016-03-02T13:40:17.506Z - info: Running on android test: 70. test calculateSeqPointKeyId

2016-03-02T13:40:17.635Z - info: Running on ios test: 78. should not be started after stop is called

2016-03-02T13:40:18.108Z - info: Running on android test: 71. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-02T13:40:18.195Z - info: Running on ios test: 79. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-02T13:40:18.640Z - info: Running on android test: 72. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-02T13:40:18.646Z - info: Running on ios test: 80. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-02T13:40:18.981Z - info: Running on ios test: 81. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-02T13:40:19.102Z - info: Running on android test: 73. messages with invalid location or USN should be ignored

2016-03-02T13:40:19.468Z - info: Running on ios test: 82. #stop can be called multiple times in a row

2016-03-02T13:40:19.604Z - info: Running on android test: 74. verify that Thali-specific messages are filtered correctly

2016-03-02T13:40:19.912Z - info: Running on ios test: 83. #startListeningForAdvertisements can be called multiple times in a row

2016-03-02T13:40:20.080Z - info: Running on android test: 75. #startListeningForAdvertisements should fail if start not called

2016-03-02T13:40:20.273Z - info: Running on ios test: 84. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-02T13:40:20.481Z - info: Running on android test: 76. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-02T13:40:20.661Z - info: Running on ios test: 85. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-02T13:40:21.078Z - info: Running on android test: 77. #start should fail if called twice in a row

2016-03-02T13:40:21.101Z - info: Running on ios test: 86. functions are run from a queue in the right order

2016-03-02T13:40:21.537Z - info: Running on android test: 78. should not be started after stop is called

2016-03-02T13:40:21.579Z - info: Test run on ios complete

2016-03-02T13:40:21.581Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-02T13:40:21.583Z - info: PLATFORM: ios

2016-03-02T13:40:21.584Z - info: RESULT: PASS

2016-03-02T13:40:21.585Z - info: 86 of 86 tests completed

2016-03-02T13:40:21.586Z - info: 86/86 passed (0 failures)

2016-03-02T13:40:21.588Z - info: --- Test Details ---



2016-03-02T13:40:21.589Z - info: 1. multiplex can send data - pass

2016-03-02T13:40:21.590Z - info: 2. enqueue and run in order - pass

2016-03-02T13:40:21.591Z - info: 3. enqueueAtTop and run backwards - pass

2016-03-02T13:40:21.592Z - info: 4. mix enqueue and enqueueAtTop - pass
2016-03-02T13:40:21.593Z - info: 5. queues handled independently - pass
2016-03-02T13:40:21.593Z - info: 6. basic - pass
2016-03-02T13:40:21.594Z - info: 7. another - pass

2016-03-02T13:40:21.595Z - info: 8. #startListeningForAdvertisements should fail if start not called - pass

2016-03-02T13:40:21.596Z - info: 9. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-02T13:40:21.596Z - info: 10. should be able to call #stopListeningForAdvertisements many times - pass
2016-03-02T13:40:21.597Z - info: 11. should be able to call #startListeningForAdvertisements many times - pass

2016-03-02T13:40:21.598Z - info: 12. should be able to call #startUpdateAdvertisingAndListening many times - pass

2016-03-02T13:40:21.599Z - info: 13. should be able to call #stopAdvertisingAndListening many times - pass

2016-03-02T13:40:21.600Z - info: 14. #start should fail if called twice in a row - pass

2016-03-02T13:40:21.601Z - info: 15. does not emit duplicate discoveryAdvertisingStateUpdate - pass
2016-03-02T13:40:21.601Z - info: 16. does not send duplicate availability changes - pass

2016-03-02T13:40:21.602Z - info: 17. can get the network status - pass

2016-03-02T13:40:21.603Z - info: 18. wifi peer is marked unavailable if announcements stop - pass

2016-03-02T13:40:21.604Z - info: 19. can get the network status before starting - pass

2016-03-02T13:40:21.605Z - info: 20. #generatePreambleAndBeacons bad args - pass
2016-03-02T13:40:21.606Z - info: 21. #generatePreambleAndBeacons empty keys to notify - pass

2016-03-02T13:40:21.606Z - info: 22. #generatePreambleAndBeacons multiple keys to notify - pass

2016-03-02T13:40:21.607Z - info: 23. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass

2016-03-02T13:40:21.608Z - info: 24. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass

2016-03-02T13:40:21.609Z - info: 25. #parseBeacons expiration out of range lower - pass
2016-03-02T13:40:21.610Z - info: 26. #parseBeacons expiration out of range lower - pass

2016-03-02T13:40:21.610Z - info: 27. #parseBeacons no beacons returns null - pass

2016-03-02T13:40:21.611Z - info: 28. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass

2016-03-02T13:40:21.612Z - info: 29. #parseBeacons addressBookCallback fails decrypt - pass

2016-03-02T13:40:21.613Z - info: 30. #parseBeacons addressBookCallback returns no matches - pass
2016-03-02T13:40:21.614Z - info: 31. #parseBeacons addressBookCallback returns spurious match - pass

2016-03-02T13:40:21.615Z - info: 32. #parseBeacons addressBookCallback returns public key - pass

2016-03-02T13:40:21.615Z - info: 33. #parseBeacons with beacons both for and not for the user - pass

2016-03-02T13:40:21.616Z - info: 34. Start and stop ThaliNotificationServer - pass

2016-03-02T13:40:21.617Z - info: 35. Pass an empty array to ThaliNotificationServer.start - pass
2016-03-02T13:40:21.618Z - info: 36. Pass a string to ThaliNotificationServer.start - pass

2016-03-02T13:40:21.619Z - info: 37. Pass an empty parameter to ThaliNotificationServer.start - pass

2016-03-02T13:40:21.619Z - info: 38. Make an HTTP request to /NotificationBeacons - pass

2016-03-02T13:40:21.620Z - info: 39. Make an HTTP request to /NotificationBeacons (no keys) - pass

2016-03-02T13:40:21.621Z - info: 40. Make an HTTP request to /NotificationBeacons before calling start - pass
2016-03-02T13:40:21.622Z - info: 41. #testThaliPeerAction - test getters - pass

2016-03-02T13:40:21.623Z - info: 42. #testThaliPeerAction - start and kill - pass

2016-03-02T13:40:21.624Z - info: 43. #testThaliPeerAction - double start - pass

2016-03-02T13:40:21.624Z - info: 44. #testThaliPeerAction - start after kill - pass

2016-03-02T13:40:21.625Z - info: 45. #testThaliPeerAction - make sure ids are unique - pass
2016-03-02T13:40:21.626Z - info: 46. #ThaliPeerPoolInterface - bad enqueues - pass

2016-03-02T13:40:21.627Z - info: 47. #ThaliPeerPoolInterface - do not allow same object type - pass

2016-03-02T13:40:21.628Z - info: 48. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass

2016-03-02T13:40:21.628Z - info: 49. compareBufferArrays - pass

2016-03-02T13:40:21.629Z - info: 50. Call start twice and get error - pass
2016-03-02T13:40:21.630Z - info: 51. Start and make sure it runs - pass

2016-03-02T13:40:21.631Z - info: 52. Make sure getTimeWhenRun is right after start - pass

2016-03-02T13:40:21.632Z - info: 53. Make sure getTimeWhenRun is -1 after function is called - pass

2016-03-02T13:40:21.633Z - info: 54. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass

2016-03-02T13:40:21.634Z - info: 55. Test TransientState - pass

2016-03-02T13:40:21.634Z - info: 56. No peers and empty database - pass
2016-03-02T13:40:21.635Z - info: 57. One peer and empty DB - pass

2016-03-02T13:40:21.636Z - info: 58. One peer with _Local set behind current seq - pass

2016-03-02T13:40:21.643Z - info: 59. One peer with _Local set equal to current seq - pass

2016-03-02T13:40:21.644Z - info: 60. One peer with _Local set ahead of current seq (and no this should not happen) - pass

2016-03-02T13:40:21.645Z - info: 61. Three peers, one not in DB, one behind and one ahead - pass
2016-03-02T13:40:21.646Z - info: 62. More than maximum peers, make sure we only send maximum allowed - pass

2016-03-02T13:40:21.647Z - info: 63. two peers with empty DB, update the doc - pass

2016-03-02T13:40:21.647Z - info: 64. add doc and make sure tokens refresh when they expire - pass

2016-03-02T13:40:21.648Z - info: 65. start and stop and start and stop - pass
2016-03-02T13:40:21.649Z - info: 66. two identical starts in a row - pass

2016-03-02T13:40:21.650Z - info: 67. two different starts in a row - pass

2016-03-02T13:40:21.651Z - info: 68. two stops and a start and two stops - pass

2016-03-02T13:40:21.651Z - info: 69. we properly enqueue requests so no then needed - pass

2016-03-02T13:40:21.652Z - info: 70. test calculateSeqPointKeyId - pass

2016-03-02T13:40:21.653Z - info: 71. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass

2016-03-02T13:40:21.654Z - info: 72. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass
2016-03-02T13:40:21.655Z - info: 73. messages with invalid location or USN should be ignored - pass

2016-03-02T13:40:21.656Z - info: 74. verify that Thali-specific messages are filtered correctly - pass

2016-03-02T13:40:21.657Z - info: 75. #startListeningForAdvertisements should fail if start not called - pass
2016-03-02T13:40:21.658Z - info: 76. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-02T13:40:21.658Z - info: 77. #start should fail if called twice in a row - pass
2016-03-02T13:40:21.659Z - info: 78. should not be started after stop is called - pass
2016-03-02T13:40:21.660Z - info: 79. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass
2016-03-02T13:40:21.661Z - info: 80. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass
2016-03-02T13:40:21.661Z - info: 81. #startUpdateAdvertisingAndListening should start hosting given router object - pass
2016-03-02T13:40:21.662Z - info: 82. #stop can be called multiple times in a row - pass
2016-03-02T13:40:21.663Z - info: 83. #startListeningForAdvertisements can be called multiple times in a row - pass
2016-03-02T13:40:21.663Z - info: 84. #stopListeningForAdvertisements can be called multiple times in a row - pass
2016-03-02T13:40:21.664Z - info: 85. #stopAdvertisingAndListening can be called multiple times in a row - pass
2016-03-02T13:40:21.664Z - info: 86. functions are run from a queue in the right order - pass
2016-03-02T13:40:21.665Z - info: 

-== END ==-

2016-03-02T13:40:22.028Z - info: Running on android test: 79. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-02T13:40:22.431Z - info: Running on android test: 80. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-02T13:40:22.887Z - info: Running on android test: 81. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-02T13:40:23.530Z - info: Running on android test: 82. #stop can be called multiple times in a row

2016-03-02T13:40:24.219Z - info: Running on android test: 83. #startListeningForAdvertisements can be called multiple times in a row

2016-03-02T13:40:24.272Z - debug: Socket disconnected: transport close 1 (Apple-Iphone6-1)

2016-03-02T13:40:24.762Z - info: Running on android test: 84. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-02T13:40:25.117Z - debug: Socket disconnected: transport close 4 (Apple-Iphone5-1)

2016-03-02T13:40:25.245Z - info: Running on android test: 85. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-02T13:40:25.760Z - info: Running on android test: 86. functions are run from a queue in the right order

2016-03-02T13:40:26.277Z - info: Test run on android complete

2016-03-02T13:40:26.278Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-02T13:40:26.283Z - info: PLATFORM: android

2016-03-02T13:40:26.284Z - info: RESULT: PASS

2016-03-02T13:40:26.285Z - info: 86 of 86 tests completed

2016-03-02T13:40:26.286Z - info: 86/86 passed (0 failures)

2016-03-02T13:40:26.287Z - info: --- Test Details ---



2016-03-02T13:40:26.289Z - info: 1. multiplex can send data - pass

2016-03-02T13:40:26.290Z - info: 2. enqueue and run in order - pass

2016-03-02T13:40:26.291Z - info: 3. enqueueAtTop and run backwards - pass

2016-03-02T13:40:26.292Z - info: 4. mix enqueue and enqueueAtTop - pass
2016-03-02T13:40:26.293Z - info: 5. queues handled independently - pass

2016-03-02T13:40:26.293Z - info: 6. basic - pass

2016-03-02T13:40:26.294Z - info: 7. another - pass

2016-03-02T13:40:26.295Z - info: 8. #startListeningForAdvertisements should fail if start not called - pass

2016-03-02T13:40:26.296Z - info: 9. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-02T13:40:26.297Z - info: 10. should be able to call #stopListeningForAdvertisements many times - pass

2016-03-02T13:40:26.298Z - info: 11. should be able to call #startListeningForAdvertisements many times - pass

2016-03-02T13:40:26.298Z - info: 12. should be able to call #startUpdateAdvertisingAndListening many times - pass

2016-03-02T13:40:26.299Z - info: 13. should be able to call #stopAdvertisingAndListening many times - pass

2016-03-02T13:40:26.300Z - info: 14. #start should fail if called twice in a row - pass
2016-03-02T13:40:26.301Z - info: 15. does not emit duplicate discoveryAdvertisingStateUpdate - pass

2016-03-02T13:40:26.302Z - info: 16. does not send duplicate availability changes - pass

2016-03-02T13:40:26.302Z - info: 17. can get the network status - pass

2016-03-02T13:40:26.303Z - info: 18. wifi peer is marked unavailable if announcements stop - pass
2016-03-02T13:40:26.304Z - info: 19. can get the network status before starting - pass

2016-03-02T13:40:26.305Z - info: 20. #generatePreambleAndBeacons bad args - pass

2016-03-02T13:40:26.306Z - info: 21. #generatePreambleAndBeacons empty keys to notify - pass

2016-03-02T13:40:26.306Z - info: 22. #generatePreambleAndBeacons multiple keys to notify - pass

2016-03-02T13:40:26.307Z - info: 23. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass
2016-03-02T13:40:26.308Z - info: 24. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass

2016-03-02T13:40:26.309Z - info: 25. #parseBeacons expiration out of range lower - pass

2016-03-02T13:40:26.310Z - info: 26. #parseBeacons expiration out of range lower - pass

2016-03-02T13:40:26.310Z - info: 27. #parseBeacons no beacons returns null - pass

2016-03-02T13:40:26.311Z - info: 28. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass
2016-03-02T13:40:26.312Z - info: 29. #parseBeacons addressBookCallback fails decrypt - pass

2016-03-02T13:40:26.313Z - info: 30. #parseBeacons addressBookCallback returns no matches - pass

2016-03-02T13:40:26.314Z - info: 31. #parseBeacons addressBookCallback returns spurious match - pass

2016-03-02T13:40:26.315Z - info: 32. #parseBeacons addressBookCallback returns public key - pass

2016-03-02T13:40:26.315Z - info: 33. #parseBeacons with beacons both for and not for the user - pass
2016-03-02T13:40:26.316Z - info: 34. Start and stop ThaliNotificationServer - pass

2016-03-02T13:40:26.317Z - info: 35. Pass an empty array to ThaliNotificationServer.start - pass

2016-03-02T13:40:26.318Z - info: 36. Pass a string to ThaliNotificationServer.start - pass

2016-03-02T13:40:26.318Z - info: 37. Pass an empty parameter to ThaliNotificationServer.start - pass
2016-03-02T13:40:26.319Z - info: 38. Make an HTTP request to /NotificationBeacons - pass

2016-03-02T13:40:26.320Z - info: 39. Make an HTTP request to /NotificationBeacons (no keys) - pass

2016-03-02T13:40:26.321Z - info: 40. Make an HTTP request to /NotificationBeacons before calling start - pass

2016-03-02T13:40:26.322Z - info: 41. #testThaliPeerAction - test getters - pass

2016-03-02T13:40:26.322Z - info: 42. #testThaliPeerAction - start and kill - pass
2016-03-02T13:40:26.323Z - info: 43. #testThaliPeerAction - double start - pass

2016-03-02T13:40:26.324Z - info: 44. #testThaliPeerAction - start after kill - pass

2016-03-02T13:40:26.325Z - info: 45. #testThaliPeerAction - make sure ids are unique - pass

2016-03-02T13:40:26.326Z - info: 46. #ThaliPeerPoolInterface - bad enqueues - pass
2016-03-02T13:40:26.326Z - info: 47. #ThaliPeerPoolInterface - do not allow same object type - pass

2016-03-02T13:40:26.327Z - info: 48. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass

2016-03-02T13:40:26.328Z - info: 49. compareBufferArrays - pass

2016-03-02T13:40:26.329Z - info: 50. Call start twice and get error - pass

2016-03-02T13:40:26.330Z - info: 51. Start and make sure it runs - pass
2016-03-02T13:40:26.330Z - info: 52. Make sure getTimeWhenRun is right after start - pass

2016-03-02T13:40:26.331Z - info: 53. Make sure getTimeWhenRun is -1 after function is called - pass

2016-03-02T13:40:26.332Z - info: 54. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass

2016-03-02T13:40:26.333Z - info: 55. Test TransientState - pass
2016-03-02T13:40:26.334Z - info: 56. No peers and empty database - pass

2016-03-02T13:40:26.334Z - info: 57. One peer and empty DB - pass

2016-03-02T13:40:26.335Z - info: 58. One peer with _Local set behind current seq - pass

2016-03-02T13:40:26.336Z - info: 59. One peer with _Local set equal to current seq - pass
2016-03-02T13:40:26.337Z - info: 60. One peer with _Local set ahead of current seq (and no this should not happen) - pass

2016-03-02T13:40:26.338Z - info: 61. Three peers, one not in DB, one behind and one ahead - pass

2016-03-02T13:40:26.338Z - info: 62. More than maximum peers, make sure we only send maximum allowed - pass

2016-03-02T13:40:26.339Z - info: 63. two peers with empty DB, update the doc - pass

2016-03-02T13:40:26.340Z - info: 64. add doc and make sure tokens refresh when they expire - pass
2016-03-02T13:40:26.341Z - info: 65. start and stop and start and stop - pass

2016-03-02T13:40:26.342Z - info: 66. two identical starts in a row - pass

2016-03-02T13:40:26.342Z - info: 67. two different starts in a row - pass

2016-03-02T13:40:26.343Z - info: 68. two stops and a start and two stops - pass
2016-03-02T13:40:26.344Z - info: 69. we properly enqueue requests so no then needed - pass

2016-03-02T13:40:26.345Z - info: 70. test calculateSeqPointKeyId - pass

2016-03-02T13:40:26.346Z - info: 71. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass

2016-03-02T13:40:26.347Z - info: 72. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-03-02T13:40:26.347Z - info: 73. messages with invalid location or USN should be ignored - pass
2016-03-02T13:40:26.348Z - info: 74. verify that Thali-specific messages are filtered correctly - pass

2016-03-02T13:40:26.349Z - info: 75. #startListeningForAdvertisements should fail if start not called - pass

2016-03-02T13:40:26.350Z - info: 76. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-02T13:40:26.351Z - info: 77. #start should fail if called twice in a row - pass
2016-03-02T13:40:26.351Z - info: 78. should not be started after stop is called - pass

2016-03-02T13:40:26.352Z - info: 79. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass

2016-03-02T13:40:26.353Z - info: 80. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass

2016-03-02T13:40:26.354Z - info: 81. #startUpdateAdvertisingAndListening should start hosting given router object - pass

2016-03-02T13:40:26.355Z - info: 82. #stop can be called multiple times in a row - pass

2016-03-02T13:40:26.356Z - info: 83. #startListeningForAdvertisements can be called multiple times in a row - pass

2016-03-02T13:40:26.358Z - info: 84. #stopListeningForAdvertisements can be called multiple times in a row - pass

2016-03-02T13:40:26.358Z - info: 85. #stopAdvertisingAndListening can be called multiple times in a row - pass

2016-03-02T13:40:26.359Z - info: 86. functions are run from a queue in the right order - pass

2016-03-02T13:40:26.367Z - info: 

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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/61362366121daa0_Make_CI_build_and_unit_tests_pass_vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/61362366121daa0_Make_CI_build_and_unit_tests_pass_vjrantal/thali01_samsung-SM-A500FU.md)

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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/61362366121daa0_Make_CI_build_and_unit_tests_pass_vjrantal/thali02_LGE-Nexus 5.md)

[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/61362366121daa0_Make_CI_build_and_unit_tests_pass_vjrantal/thali02_LGE-LG-D722.md)

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
[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/61362366121daa0_Make_CI_build_and_unit_tests_pass_vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/61362366121daa0_Make_CI_build_and_unit_tests_pass_vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
STOP log received from  0be0c6c6 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Device test finished on 0be0c6c6 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/61362366121daa0_Make_CI_build_and_unit_tests_pass_vjrantal/thali04_samsung-SM-G900F.md)

[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/61362366121daa0_Make_CI_build_and_unit_tests_pass_vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/61362366121daa0_Make_CI_build_and_unit_tests_pass_vjrantal/thali04_samsung-SM-N910C.md)

####Node name: thali05
Console output:
```
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device HT4BLJT02274 app:com.test.thalitest code:0 
child process exited with code 0 on device HT4BLJT02274 
Error! Unexpected exit on device 1d6a772d app:com.test.thalitest code:null 
child process exited with code null on device 1d6a772d 
Error! Unexpected exit on device 954a12ed app:com.test.thalitest code:0 
child process exited with code 0 on device 954a12ed 
Android task is completed. [FAILED]
```
[htc-Nexus 9](https://github.com/ThaliTester/TestResults/blob/61362366121daa0_Make_CI_build_and_unit_tests_pass_vjrantal/thali05_htc-Nexus 9.md)

[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/61362366121daa0_Make_CI_build_and_unit_tests_pass_vjrantal/thali05_samsung-SM-N9005.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/61362366121daa0_Make_CI_build_and_unit_tests_pass_vjrantal/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/61362366121daa0_Make_CI_build_and_unit_tests_pass_vjrantal/thali05_samsung-SM-G800H.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/61362366121daa0_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/61362366121daa0_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/61362366121daa0_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_LGE-LG-D802.md)

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
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/61362366121daa0_Make_CI_build_and_unit_tests_pass_vjrantal/thali07_samsung-SM-A500FU.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/61362366121daa0_Make_CI_build_and_unit_tests_pass_vjrantal/thali07_samsung-SM-G900F.md)

####Node name: thali08
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device HT574YC04723 app:com.test.thalitest code:0 
child process exited with code 0 on device HT574YC04723 
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:null 
child process exited with code null on device 4325e43f 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/61362366121daa0_Make_CI_build_and_unit_tests_pass_vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/61362366121daa0_Make_CI_build_and_unit_tests_pass_vjrantal/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/61362366121daa0_Make_CI_build_and_unit_tests_pass_vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/61362366121daa0_Make_CI_build_and_unit_tests_pass_vjrantal/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/61362366121daa0_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/61362366121daa0_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/61362366121daa0_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/61362366121daa0_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone6-1.md)



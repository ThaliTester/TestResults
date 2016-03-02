#### Test 613623661dfc74c Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":22}}
2016-03-02T12:06:30.049Z - info: listening on *:3000

2016-03-02T12:06:30.686Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:0

2016-03-02T12:06:31.442Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:1

2016-03-02T12:06:31.447Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:2

2016-03-02T12:06:31.449Z - info: Required number of ios devices presented (2)

2016-03-02T12:06:31.453Z - info: Starting unit test run for platform: ios

2016-03-02T12:06:31.960Z - info: Running on ios test: 1. multiplex can send data

2016-03-02T12:06:32.431Z - info: Running on ios test: 2. enqueue and run in order

2016-03-02T12:06:32.832Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:3

2016-03-02T12:06:32.833Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-02T12:06:33.026Z - info: Running on ios test: 3. enqueueAtTop and run backwards

2016-03-02T12:06:33.391Z - info: Running on ios test: 4. mix enqueue and enqueueAtTop

2016-03-02T12:06:33.916Z - info: Running on ios test: 5. queues handled independently

2016-03-02T12:06:34.235Z - info: Running on ios test: 6. basic

2016-03-02T12:06:34.519Z - info: Running on ios test: 7. another

2016-03-02T12:06:34.874Z - info: Running on ios test: 8. #startListeningForAdvertisements should fail if start not called

2016-03-02T12:06:34.979Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:4

2016-03-02T12:06:34.980Z - info: Discarding surplus device: Apple-IpadAir2-1

2016-03-02T12:06:35.463Z - info: Running on ios test: 9. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-02T12:06:35.650Z - debug: Socket disconnected: transport close 3 (Apple-Iphone5s-1)

2016-03-02T12:06:35.822Z - info: Running on ios test: 10. should be able to call #stopListeningForAdvertisements many times

2016-03-02T12:06:36.107Z - info: Running on ios test: 11. should be able to call #startListeningForAdvertisements many times

2016-03-02T12:06:36.463Z - info: Running on ios test: 12. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-02T12:06:36.865Z - info: Running on ios test: 13. should be able to call #stopAdvertisingAndListening many times

2016-03-02T12:06:37.203Z - info: Running on ios test: 14. #start should fail if called twice in a row

2016-03-02T12:06:37.548Z - info: Running on ios test: 15. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-02T12:06:37.633Z - debug: Socket disconnected: transport close 4 (Apple-IpadAir2-1)

2016-03-02T12:06:37.988Z - info: Running on ios test: 16. does not send duplicate availability changes

2016-03-02T12:06:38.291Z - info: Running on ios test: 17. can get the network status

2016-03-02T12:06:38.690Z - info: Running on ios test: 18. wifi peer is marked unavailable if announcements stop

2016-03-02T12:06:40.277Z - info: Running on ios test: 19. can get the network status before starting

2016-03-02T12:06:40.774Z - info: Running on ios test: 20. #generatePreambleAndBeacons bad args

2016-03-02T12:06:41.238Z - info: Running on ios test: 21. #generatePreambleAndBeacons empty keys to notify

2016-03-02T12:06:41.607Z - info: Running on ios test: 22. #generatePreambleAndBeacons multiple keys to notify

2016-03-02T12:06:42.169Z - info: Running on ios test: 23. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-02T12:06:42.512Z - info: Running on ios test: 24. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-02T12:06:43.005Z - info: Running on ios test: 25. #parseBeacons expiration out of range lower

2016-03-02T12:06:43.365Z - info: Running on ios test: 26. #parseBeacons expiration out of range lower

2016-03-02T12:06:43.758Z - info: Running on ios test: 27. #parseBeacons no beacons returns null

2016-03-02T12:06:44.071Z - info: Running on ios test: 28. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-02T12:06:44.430Z - info: Running on ios test: 29. #parseBeacons addressBookCallback fails decrypt

2016-03-02T12:06:44.903Z - info: Running on ios test: 30. #parseBeacons addressBookCallback returns no matches

2016-03-02T12:06:45.361Z - info: Running on ios test: 31. #parseBeacons addressBookCallback returns spurious match

2016-03-02T12:06:45.786Z - info: Running on ios test: 32. #parseBeacons addressBookCallback returns public key

2016-03-02T12:06:46.216Z - info: Running on ios test: 33. #parseBeacons with beacons both for and not for the user

2016-03-02T12:06:46.746Z - info: Running on ios test: 34. Start and stop ThaliNotificationServer

2016-03-02T12:06:47.262Z - info: Running on ios test: 35. Pass an empty array to ThaliNotificationServer.start

2016-03-02T12:06:47.384Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:5

2016-03-02T12:06:47.386Z - info: Required number of android devices presented (2)

2016-03-02T12:06:47.387Z - info: Starting unit test run for platform: android

2016-03-02T12:06:47.934Z - info: Running on android test: 1. multiplex can send data

2016-03-02T12:06:48.504Z - info: Running on android test: 2. enqueue and run in order

2016-03-02T12:06:49.371Z - info: Running on ios test: 36. Pass a string to ThaliNotificationServer.start

2016-03-02T12:06:49.422Z - info: Running on android test: 3. enqueueAtTop and run backwards

2016-03-02T12:06:49.872Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:6

2016-03-02T12:06:49.873Z - info: Discarding surplus device: samsung-SM-G900F

2016-03-02T12:06:50.010Z - info: Running on ios test: 37. Pass an empty parameter to ThaliNotificationServer.start

2016-03-02T12:06:50.057Z - info: Running on android test: 4. mix enqueue and enqueueAtTop

2016-03-02T12:06:50.499Z - info: Running on ios test: 38. Make an HTTP request to /NotificationBeacons

2016-03-02T12:06:50.652Z - info: Running on android test: 5. queues handled independently

2016-03-02T12:06:51.014Z - info: Running on android test: 6. basic

2016-03-02T12:06:51.061Z - debug: Socket disconnected: transport close 6 (samsung-SM-G900F)

2016-03-02T12:06:51.072Z - info: Running on ios test: 39. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-02T12:06:51.382Z - info: Running on android test: 7. another

2016-03-02T12:06:51.516Z - info: Running on ios test: 40. Make an HTTP request to /NotificationBeacons before calling start

2016-03-02T12:06:51.834Z - info: Running on android test: 8. #startListeningForAdvertisements should fail if start not called

2016-03-02T12:06:52.129Z - info: Running on ios test: 41. #testThaliPeerAction - test getters

2016-03-02T12:06:52.261Z - info: Running on android test: 9. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-02T12:06:52.440Z - info: Running on ios test: 42. #testThaliPeerAction - start and kill

2016-03-02T12:06:52.582Z - info: Running on android test: 10. should be able to call #stopListeningForAdvertisements many times

2016-03-02T12:06:52.760Z - info: Running on ios test: 43. #testThaliPeerAction - double start

2016-03-02T12:06:52.968Z - info: Running on android test: 11. should be able to call #startListeningForAdvertisements many times

2016-03-02T12:06:53.112Z - info: Running on ios test: 44. #testThaliPeerAction - start after kill

2016-03-02T12:06:53.420Z - info: Running on android test: 12. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-02T12:06:53.647Z - info: Running on ios test: 45. #testThaliPeerAction - make sure ids are unique

2016-03-02T12:06:54.095Z - info: Running on android test: 13. should be able to call #stopAdvertisingAndListening many times

2016-03-02T12:06:54.191Z - info: Running on ios test: 46. #ThaliPeerPoolInterface - bad enqueues

2016-03-02T12:06:54.576Z - info: Running on android test: 14. #start should fail if called twice in a row

2016-03-02T12:06:54.677Z - info: Running on ios test: 47. #ThaliPeerPoolInterface - do not allow same object type

2016-03-02T12:06:55.157Z - info: Running on ios test: 48. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-02T12:06:55.227Z - info: Running on android test: 15. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-02T12:06:55.586Z - info: Running on ios test: 49. compareBufferArrays

2016-03-02T12:06:55.679Z - info: Running on android test: 16. does not send duplicate availability changes

2016-03-02T12:06:56.098Z - info: Running on ios test: 50. Call start twice and get error

2016-03-02T12:06:56.103Z - info: Running on android test: 17. can get the network status

2016-03-02T12:06:56.711Z - info: Running on ios test: 51. Start and make sure it runs

2016-03-02T12:06:56.766Z - info: Running on android test: 18. wifi peer is marked unavailable if announcements stop

2016-03-02T12:06:57.265Z - info: Running on ios test: 52. Make sure getTimeWhenRun is right after start

2016-03-02T12:06:57.772Z - info: Running on ios test: 53. Make sure getTimeWhenRun is -1 after function is called

2016-03-02T12:06:58.276Z - info: Running on ios test: 54. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-02T12:06:58.306Z - info: Running on android test: 19. can get the network status before starting

2016-03-02T12:06:58.894Z - info: Running on android test: 20. #generatePreambleAndBeacons bad args

2016-03-02T12:06:58.900Z - info: Running on ios test: 55. Test TransientState

2016-03-02T12:06:59.359Z - info: Running on ios test: 56. No peers and empty database

2016-03-02T12:06:59.393Z - info: Running on android test: 21. #generatePreambleAndBeacons empty keys to notify

2016-03-02T12:06:59.755Z - info: Running on android test: 22. #generatePreambleAndBeacons multiple keys to notify

2016-03-02T12:07:00.033Z - info: Running on ios test: 57. One peer and empty DB

2016-03-02T12:07:00.310Z - info: Running on android test: 23. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-02T12:07:00.696Z - info: Running on ios test: 58. One peer with _Local set behind current seq

2016-03-02T12:07:00.702Z - info: Running on android test: 24. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-02T12:07:01.172Z - info: Running on android test: 25. #parseBeacons expiration out of range lower

2016-03-02T12:07:01.477Z - info: Running on ios test: 59. One peer with _Local set equal to current seq

2016-03-02T12:07:01.633Z - info: Running on android test: 26. #parseBeacons expiration out of range lower

2016-03-02T12:07:02.050Z - info: Running on android test: 27. #parseBeacons no beacons returns null

2016-03-02T12:07:02.095Z - info: Running on ios test: 60. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-02T12:07:02.491Z - info: Running on android test: 28. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-02T12:07:02.861Z - info: Running on android test: 29. #parseBeacons addressBookCallback fails decrypt

2016-03-02T12:07:02.917Z - info: Running on ios test: 61. Three peers, one not in DB, one behind and one ahead

2016-03-02T12:07:03.391Z - info: Running on android test: 30. #parseBeacons addressBookCallback returns no matches

2016-03-02T12:07:03.871Z - info: Running on ios test: 62. More than maximum peers, make sure we only send maximum allowed

2016-03-02T12:07:03.971Z - info: Running on android test: 31. #parseBeacons addressBookCallback returns spurious match

2016-03-02T12:07:04.459Z - info: Running on android test: 32. #parseBeacons addressBookCallback returns public key

2016-03-02T12:07:05.046Z - info: Running on android test: 33. #parseBeacons with beacons both for and not for the user

2016-03-02T12:07:05.579Z - info: Running on android test: 34. Start and stop ThaliNotificationServer

2016-03-02T12:07:05.735Z - info: Running on ios test: 63. two peers with empty DB, update the doc

2016-03-02T12:07:06.095Z - info: Running on android test: 35. Pass an empty array to ThaliNotificationServer.start

2016-03-02T12:07:06.586Z - info: Running on android test: 36. Pass a string to ThaliNotificationServer.start

2016-03-02T12:07:06.618Z - info: Running on ios test: 64. add doc and make sure tokens refresh when they expire

2016-03-02T12:07:06.988Z - info: Running on android test: 37. Pass an empty parameter to ThaliNotificationServer.start

2016-03-02T12:07:07.300Z - info: Running on android test: 38. Make an HTTP request to /NotificationBeacons

2016-03-02T12:07:07.582Z - info: Running on ios test: 65. start and stop and start and stop

2016-03-02T12:07:07.835Z - info: Running on android test: 39. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-02T12:07:08.139Z - info: Running on android test: 40. Make an HTTP request to /NotificationBeacons before calling start

2016-03-02T12:07:08.145Z - info: Running on ios test: 66. two identical starts in a row

2016-03-02T12:07:08.662Z - info: Running on android test: 41. #testThaliPeerAction - test getters

2016-03-02T12:07:08.723Z - info: Running on ios test: 67. two different starts in a row

2016-03-02T12:07:08.974Z - info: Running on android test: 42. #testThaliPeerAction - start and kill

2016-03-02T12:07:09.397Z - info: Running on ios test: 68. two stops and a start and two stops

2016-03-02T12:07:09.444Z - info: Running on android test: 43. #testThaliPeerAction - double start

2016-03-02T12:07:10.022Z - info: Running on android test: 44. #testThaliPeerAction - start after kill

2016-03-02T12:07:10.181Z - info: Running on ios test: 69. we properly enqueue requests so no then needed

2016-03-02T12:07:10.607Z - info: Running on android test: 45. #testThaliPeerAction - make sure ids are unique

2016-03-02T12:07:10.900Z - info: Running on ios test: 70. test calculateSeqPointKeyId

2016-03-02T12:07:10.921Z - info: Running on android test: 46. #ThaliPeerPoolInterface - bad enqueues

2016-03-02T12:07:11.251Z - info: Running on android test: 47. #ThaliPeerPoolInterface - do not allow same object type

2016-03-02T12:07:11.349Z - info: Running on ios test: 71. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-02T12:07:11.690Z - info: Running on android test: 48. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-02T12:07:11.823Z - info: Running on ios test: 72. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-02T12:07:12.071Z - info: Running on android test: 49. compareBufferArrays

2016-03-02T12:07:12.181Z - info: Running on ios test: 73. messages with invalid location or USN should be ignored

2016-03-02T12:07:12.451Z - info: Running on android test: 50. Call start twice and get error

2016-03-02T12:07:12.486Z - info: Running on ios test: 74. verify that Thali-specific messages are filtered correctly

2016-03-02T12:07:12.731Z - info: Running on android test: 51. Start and make sure it runs

2016-03-02T12:07:12.789Z - info: Running on ios test: 75. #startListeningForAdvertisements should fail if start not called

2016-03-02T12:07:13.095Z - info: Running on ios test: 76. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-02T12:07:13.138Z - info: Running on android test: 52. Make sure getTimeWhenRun is right after start

2016-03-02T12:07:13.478Z - info: Running on ios test: 77. #start should fail if called twice in a row

2016-03-02T12:07:13.484Z - info: Running on android test: 53. Make sure getTimeWhenRun is -1 after function is called

2016-03-02T12:07:13.831Z - info: Running on ios test: 78. should not be started after stop is called

2016-03-02T12:07:13.923Z - info: Running on android test: 54. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-02T12:07:14.194Z - info: Running on ios test: 79. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-02T12:07:14.335Z - info: Running on android test: 55. Test TransientState

2016-03-02T12:07:14.526Z - info: Running on ios test: 80. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-02T12:07:14.796Z - info: Running on android test: 56. No peers and empty database

2016-03-02T12:07:14.968Z - info: Running on ios test: 81. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-02T12:07:15.391Z - info: Running on android test: 57. One peer and empty DB

2016-03-02T12:07:15.459Z - info: Running on ios test: 82. #stop can be called multiple times in a row

2016-03-02T12:07:15.871Z - info: Running on ios test: 83. #startListeningForAdvertisements can be called multiple times in a row

2016-03-02T12:07:16.035Z - info: Running on android test: 58. One peer with _Local set behind current seq

2016-03-02T12:07:16.231Z - info: Running on ios test: 84. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-02T12:07:16.578Z - info: Running on ios test: 85. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-02T12:07:16.639Z - info: Running on android test: 59. One peer with _Local set equal to current seq

2016-03-02T12:07:16.985Z - info: Running on ios test: 86. functions are run from a queue in the right order

2016-03-02T12:07:17.104Z - info: Running on android test: 60. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-02T12:07:17.281Z - info: Test run on ios complete

2016-03-02T12:07:17.284Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-02T12:07:17.285Z - info: PLATFORM: ios

2016-03-02T12:07:17.286Z - info: RESULT: PASS

2016-03-02T12:07:17.287Z - info: 86 of 86 tests completed

2016-03-02T12:07:17.288Z - info: 86/86 passed (0 failures)

2016-03-02T12:07:17.289Z - info: --- Test Details ---



2016-03-02T12:07:17.290Z - info: 1. multiplex can send data - pass

2016-03-02T12:07:17.291Z - info: 2. enqueue and run in order - pass
2016-03-02T12:07:17.292Z - info: 3. enqueueAtTop and run backwards - pass

2016-03-02T12:07:17.293Z - info: 4. mix enqueue and enqueueAtTop - pass

2016-03-02T12:07:17.294Z - info: 5. queues handled independently - pass

2016-03-02T12:07:17.295Z - info: 6. basic - pass
2016-03-02T12:07:17.296Z - info: 7. another - pass

2016-03-02T12:07:17.296Z - info: 8. #startListeningForAdvertisements should fail if start not called - pass

2016-03-02T12:07:17.297Z - info: 9. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-02T12:07:17.298Z - info: 10. should be able to call #stopListeningForAdvertisements many times - pass

2016-03-02T12:07:17.299Z - info: 11. should be able to call #startListeningForAdvertisements many times - pass
2016-03-02T12:07:17.300Z - info: 12. should be able to call #startUpdateAdvertisingAndListening many times - pass
2016-03-02T12:07:17.300Z - info: 13. should be able to call #stopAdvertisingAndListening many times - pass
2016-03-02T12:07:17.301Z - info: 14. #start should fail if called twice in a row - pass
2016-03-02T12:07:17.302Z - info: 15. does not emit duplicate discoveryAdvertisingStateUpdate - pass
2016-03-02T12:07:17.302Z - info: 16. does not send duplicate availability changes - pass
2016-03-02T12:07:17.303Z - info: 17. can get the network status - pass
2016-03-02T12:07:17.303Z - info: 18. wifi peer is marked unavailable if announcements stop - pass
2016-03-02T12:07:17.304Z - info: 19. can get the network status before starting - pass
2016-03-02T12:07:17.304Z - info: 20. #generatePreambleAndBeacons bad args - pass
2016-03-02T12:07:17.305Z - info: 21. #generatePreambleAndBeacons empty keys to notify - pass
2016-03-02T12:07:17.305Z - info: 22. #generatePreambleAndBeacons multiple keys to notify - pass
2016-03-02T12:07:17.306Z - info: 23. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass
2016-03-02T12:07:17.306Z - info: 24. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass
2016-03-02T12:07:17.307Z - info: 25. #parseBeacons expiration out of range lower - pass
2016-03-02T12:07:17.307Z - info: 26. #parseBeacons expiration out of range lower - pass
2016-03-02T12:07:17.308Z - info: 27. #parseBeacons no beacons returns null - pass
2016-03-02T12:07:17.308Z - info: 28. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass
2016-03-02T12:07:17.309Z - info: 29. #parseBeacons addressBookCallback fails decrypt - pass
2016-03-02T12:07:17.310Z - info: 30. #parseBeacons addressBookCallback returns no matches - pass
2016-03-02T12:07:17.310Z - info: 31. #parseBeacons addressBookCallback returns spurious match - pass
2016-03-02T12:07:17.311Z - info: 32. #parseBeacons addressBookCallback returns public key - pass
2016-03-02T12:07:17.311Z - info: 33. #parseBeacons with beacons both for and not for the user - pass
2016-03-02T12:07:17.312Z - info: 34. Start and stop ThaliNotificationServer - pass
2016-03-02T12:07:17.313Z - info: 35. Pass an empty array to ThaliNotificationServer.start - pass

2016-03-02T12:07:17.313Z - info: 36. Pass a string to ThaliNotificationServer.start - pass
2016-03-02T12:07:17.314Z - info: 37. Pass an empty parameter to ThaliNotificationServer.start - pass
2016-03-02T12:07:17.315Z - info: 38. Make an HTTP request to /NotificationBeacons - pass

2016-03-02T12:07:17.316Z - info: 39. Make an HTTP request to /NotificationBeacons (no keys) - pass

2016-03-02T12:07:17.316Z - info: 40. Make an HTTP request to /NotificationBeacons before calling start - pass

2016-03-02T12:07:17.317Z - info: 41. #testThaliPeerAction - test getters - pass
2016-03-02T12:07:17.318Z - info: 42. #testThaliPeerAction - start and kill - pass

2016-03-02T12:07:17.319Z - info: 43. #testThaliPeerAction - double start - pass

2016-03-02T12:07:17.320Z - info: 44. #testThaliPeerAction - start after kill - pass
2016-03-02T12:07:17.320Z - info: 45. #testThaliPeerAction - make sure ids are unique - pass
2016-03-02T12:07:17.321Z - info: 46. #ThaliPeerPoolInterface - bad enqueues - pass
2016-03-02T12:07:17.321Z - info: 47. #ThaliPeerPoolInterface - do not allow same object type - pass
2016-03-02T12:07:17.322Z - info: 48. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass
2016-03-02T12:07:17.323Z - info: 49. compareBufferArrays - pass
2016-03-02T12:07:17.323Z - info: 50. Call start twice and get error - pass
2016-03-02T12:07:17.324Z - info: 51. Start and make sure it runs - pass
2016-03-02T12:07:17.324Z - info: 52. Make sure getTimeWhenRun is right after start - pass

2016-03-02T12:07:17.325Z - info: 53. Make sure getTimeWhenRun is -1 after function is called - pass

2016-03-02T12:07:17.326Z - info: 54. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass
2016-03-02T12:07:17.327Z - info: 55. Test TransientState - pass

2016-03-02T12:07:17.328Z - info: 56. No peers and empty database - pass

2016-03-02T12:07:17.329Z - info: 57. One peer and empty DB - pass

2016-03-02T12:07:17.329Z - info: 58. One peer with _Local set behind current seq - pass

2016-03-02T12:07:17.330Z - info: 59. One peer with _Local set equal to current seq - pass

2016-03-02T12:07:17.331Z - info: 60. One peer with _Local set ahead of current seq (and no this should not happen) - pass

2016-03-02T12:07:17.332Z - info: 61. Three peers, one not in DB, one behind and one ahead - pass
2016-03-02T12:07:17.333Z - info: 62. More than maximum peers, make sure we only send maximum allowed - pass

2016-03-02T12:07:17.334Z - info: 63. two peers with empty DB, update the doc - pass

2016-03-02T12:07:17.334Z - info: 64. add doc and make sure tokens refresh when they expire - pass

2016-03-02T12:07:17.335Z - info: 65. start and stop and start and stop - pass
2016-03-02T12:07:17.336Z - info: 66. two identical starts in a row - pass
2016-03-02T12:07:17.337Z - info: 67. two different starts in a row - pass

2016-03-02T12:07:17.337Z - info: 68. two stops and a start and two stops - pass
2016-03-02T12:07:17.338Z - info: 69. we properly enqueue requests so no then needed - pass

2016-03-02T12:07:17.339Z - info: 70. test calculateSeqPointKeyId - pass

2016-03-02T12:07:17.340Z - info: 71. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass

2016-03-02T12:07:17.341Z - info: 72. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-03-02T12:07:17.342Z - info: 73. messages with invalid location or USN should be ignored - pass

2016-03-02T12:07:17.352Z - info: 74. verify that Thali-specific messages are filtered correctly - pass

2016-03-02T12:07:17.359Z - info: 75. #startListeningForAdvertisements should fail if start not called - pass

2016-03-02T12:07:17.360Z - info: 76. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-02T12:07:17.361Z - info: 77. #start should fail if called twice in a row - pass

2016-03-02T12:07:17.362Z - info: 78. should not be started after stop is called - pass

2016-03-02T12:07:17.363Z - info: 79. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass
2016-03-02T12:07:17.364Z - info: 80. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass

2016-03-02T12:07:17.364Z - info: 81. #startUpdateAdvertisingAndListening should start hosting given router object - pass

2016-03-02T12:07:17.365Z - info: 82. #stop can be called multiple times in a row - pass

2016-03-02T12:07:17.366Z - info: 83. #startListeningForAdvertisements can be called multiple times in a row - pass

2016-03-02T12:07:17.367Z - info: 84. #stopListeningForAdvertisements can be called multiple times in a row - pass
2016-03-02T12:07:17.368Z - info: 85. #stopAdvertisingAndListening can be called multiple times in a row - pass

2016-03-02T12:07:17.369Z - info: 86. functions are run from a queue in the right order - pass

2016-03-02T12:07:17.369Z - info: 

-== END ==-

2016-03-02T12:07:17.644Z - info: Running on android test: 61. Three peers, one not in DB, one behind and one ahead

2016-03-02T12:07:18.379Z - info: Running on android test: 62. More than maximum peers, make sure we only send maximum allowed

2016-03-02T12:07:20.003Z - info: Running on android test: 63. two peers with empty DB, update the doc

2016-03-02T12:07:20.177Z - debug: Socket disconnected: transport close 0 (Apple-Iphone6-1)

2016-03-02T12:07:20.515Z - debug: Socket disconnected: transport close 2 (Apple-Iphone5-1)

2016-03-02T12:07:20.835Z - info: Running on android test: 64. add doc and make sure tokens refresh when they expire

2016-03-02T12:07:21.808Z - info: Running on android test: 65. start and stop and start and stop

2016-03-02T12:07:22.459Z - info: Running on android test: 66. two identical starts in a row

2016-03-02T12:07:23.030Z - info: Running on android test: 67. two different starts in a row

2016-03-02T12:07:23.882Z - info: Running on android test: 68. two stops and a start and two stops

2016-03-02T12:07:24.433Z - info: Running on android test: 69. we properly enqueue requests so no then needed

2016-03-02T12:07:24.967Z - info: Running on android test: 70. test calculateSeqPointKeyId

2016-03-02T12:07:25.507Z - info: Running on android test: 71. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-02T12:07:26.112Z - info: Running on android test: 72. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-02T12:07:26.826Z - info: Running on android test: 73. messages with invalid location or USN should be ignored

2016-03-02T12:07:27.231Z - info: Running on android test: 74. verify that Thali-specific messages are filtered correctly

2016-03-02T12:07:27.592Z - info: Running on android test: 75. #startListeningForAdvertisements should fail if start not called

2016-03-02T12:07:27.925Z - info: Running on android test: 76. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-02T12:07:28.393Z - info: Running on android test: 77. #start should fail if called twice in a row

2016-03-02T12:07:28.895Z - info: Running on android test: 78. should not be started after stop is called

2016-03-02T12:07:29.316Z - info: Running on android test: 79. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-02T12:07:29.703Z - info: Running on android test: 80. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-02T12:07:30.132Z - info: Running on android test: 81. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-02T12:07:30.649Z - info: Running on android test: 82. #stop can be called multiple times in a row

2016-03-02T12:07:31.030Z - info: Running on android test: 83. #startListeningForAdvertisements can be called multiple times in a row

2016-03-02T12:07:31.363Z - info: Running on android test: 84. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-02T12:07:31.682Z - info: Running on android test: 85. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-02T12:07:32.060Z - info: Running on android test: 86. functions are run from a queue in the right order

2016-03-02T12:07:32.574Z - info: Test run on android complete

2016-03-02T12:07:32.574Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-02T12:07:32.576Z - info: PLATFORM: android
2016-03-02T12:07:32.576Z - info: RESULT: PASS

2016-03-02T12:07:32.577Z - info: 86 of 86 tests completed

2016-03-02T12:07:32.578Z - info: 86/86 passed (0 failures)

2016-03-02T12:07:32.579Z - info: --- Test Details ---



2016-03-02T12:07:32.583Z - info: 1. multiplex can send data - pass

2016-03-02T12:07:32.584Z - info: 2. enqueue and run in order - pass
2016-03-02T12:07:32.584Z - info: 3. enqueueAtTop and run backwards - pass

2016-03-02T12:07:32.585Z - info: 4. mix enqueue and enqueueAtTop - pass
2016-03-02T12:07:32.586Z - info: 5. queues handled independently - pass

2016-03-02T12:07:32.586Z - info: 6. basic - pass
2016-03-02T12:07:32.587Z - info: 7. another - pass
2016-03-02T12:07:32.588Z - info: 8. #startListeningForAdvertisements should fail if start not called - pass
2016-03-02T12:07:32.588Z - info: 9. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-02T12:07:32.589Z - info: 10. should be able to call #stopListeningForAdvertisements many times - pass
2016-03-02T12:07:32.589Z - info: 11. should be able to call #startListeningForAdvertisements many times - pass
2016-03-02T12:07:32.590Z - info: 12. should be able to call #startUpdateAdvertisingAndListening many times - pass
2016-03-02T12:07:32.590Z - info: 13. should be able to call #stopAdvertisingAndListening many times - pass
2016-03-02T12:07:32.591Z - info: 14. #start should fail if called twice in a row - pass
2016-03-02T12:07:32.592Z - info: 15. does not emit duplicate discoveryAdvertisingStateUpdate - pass
2016-03-02T12:07:32.592Z - info: 16. does not send duplicate availability changes - pass
2016-03-02T12:07:32.593Z - info: 17. can get the network status - pass
2016-03-02T12:07:32.593Z - info: 18. wifi peer is marked unavailable if announcements stop - pass
2016-03-02T12:07:32.594Z - info: 19. can get the network status before starting - pass
2016-03-02T12:07:32.594Z - info: 20. #generatePreambleAndBeacons bad args - pass
2016-03-02T12:07:32.595Z - info: 21. #generatePreambleAndBeacons empty keys to notify - pass
2016-03-02T12:07:32.595Z - info: 22. #generatePreambleAndBeacons multiple keys to notify - pass
2016-03-02T12:07:32.596Z - info: 23. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass
2016-03-02T12:07:32.596Z - info: 24. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass
2016-03-02T12:07:32.597Z - info: 25. #parseBeacons expiration out of range lower - pass
2016-03-02T12:07:32.597Z - info: 26. #parseBeacons expiration out of range lower - pass
2016-03-02T12:07:32.598Z - info: 27. #parseBeacons no beacons returns null - pass
2016-03-02T12:07:32.598Z - info: 28. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass
2016-03-02T12:07:32.599Z - info: 29. #parseBeacons addressBookCallback fails decrypt - pass
2016-03-02T12:07:32.599Z - info: 30. #parseBeacons addressBookCallback returns no matches - pass

2016-03-02T12:07:32.600Z - info: 31. #parseBeacons addressBookCallback returns spurious match - pass
2016-03-02T12:07:32.601Z - info: 32. #parseBeacons addressBookCallback returns public key - pass
2016-03-02T12:07:32.601Z - info: 33. #parseBeacons with beacons both for and not for the user - pass

2016-03-02T12:07:32.602Z - info: 34. Start and stop ThaliNotificationServer - pass
2016-03-02T12:07:32.603Z - info: 35. Pass an empty array to ThaliNotificationServer.start - pass

2016-03-02T12:07:32.603Z - info: 36. Pass a string to ThaliNotificationServer.start - pass
2016-03-02T12:07:32.604Z - info: 37. Pass an empty parameter to ThaliNotificationServer.start - pass

2016-03-02T12:07:32.604Z - info: 38. Make an HTTP request to /NotificationBeacons - pass
2016-03-02T12:07:32.605Z - info: 39. Make an HTTP request to /NotificationBeacons (no keys) - pass

2016-03-02T12:07:32.606Z - info: 40. Make an HTTP request to /NotificationBeacons before calling start - pass

2016-03-02T12:07:32.606Z - info: 41. #testThaliPeerAction - test getters - pass
2016-03-02T12:07:32.607Z - info: 42. #testThaliPeerAction - start and kill - pass

2016-03-02T12:07:32.607Z - info: 43. #testThaliPeerAction - double start - pass
2016-03-02T12:07:32.608Z - info: 44. #testThaliPeerAction - start after kill - pass

2016-03-02T12:07:32.609Z - info: 45. #testThaliPeerAction - make sure ids are unique - pass
2016-03-02T12:07:32.609Z - info: 46. #ThaliPeerPoolInterface - bad enqueues - pass

2016-03-02T12:07:32.610Z - info: 47. #ThaliPeerPoolInterface - do not allow same object type - pass
2016-03-02T12:07:32.610Z - info: 48. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass

2016-03-02T12:07:32.611Z - info: 49. compareBufferArrays - pass
2016-03-02T12:07:32.612Z - info: 50. Call start twice and get error - pass

2016-03-02T12:07:32.612Z - info: 51. Start and make sure it runs - pass
2016-03-02T12:07:32.613Z - info: 52. Make sure getTimeWhenRun is right after start - pass

2016-03-02T12:07:32.614Z - info: 53. Make sure getTimeWhenRun is -1 after function is called - pass

2016-03-02T12:07:32.614Z - info: 54. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass
2016-03-02T12:07:32.615Z - info: 55. Test TransientState - pass

2016-03-02T12:07:32.615Z - info: 56. No peers and empty database - pass
2016-03-02T12:07:32.616Z - info: 57. One peer and empty DB - pass

2016-03-02T12:07:32.617Z - info: 58. One peer with _Local set behind current seq - pass
2016-03-02T12:07:32.617Z - info: 59. One peer with _Local set equal to current seq - pass

2016-03-02T12:07:32.618Z - info: 60. One peer with _Local set ahead of current seq (and no this should not happen) - pass
2016-03-02T12:07:32.618Z - info: 61. Three peers, one not in DB, one behind and one ahead - pass

2016-03-02T12:07:32.619Z - info: 62. More than maximum peers, make sure we only send maximum allowed - pass
2016-03-02T12:07:32.620Z - info: 63. two peers with empty DB, update the doc - pass

2016-03-02T12:07:32.620Z - info: 64. add doc and make sure tokens refresh when they expire - pass
2016-03-02T12:07:32.621Z - info: 65. start and stop and start and stop - pass

2016-03-02T12:07:32.621Z - info: 66. two identical starts in a row - pass

2016-03-02T12:07:32.622Z - info: 67. two different starts in a row - pass
2016-03-02T12:07:32.623Z - info: 68. two stops and a start and two stops - pass

2016-03-02T12:07:32.623Z - info: 69. we properly enqueue requests so no then needed - pass
2016-03-02T12:07:32.624Z - info: 70. test calculateSeqPointKeyId - pass

2016-03-02T12:07:32.625Z - info: 71. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass
2016-03-02T12:07:32.625Z - info: 72. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-03-02T12:07:32.626Z - info: 73. messages with invalid location or USN should be ignored - pass

2016-03-02T12:07:32.626Z - info: 74. verify that Thali-specific messages are filtered correctly - pass
2016-03-02T12:07:32.627Z - info: 75. #startListeningForAdvertisements should fail if start not called - pass

2016-03-02T12:07:32.628Z - info: 76. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-02T12:07:32.628Z - info: 77. #start should fail if called twice in a row - pass

2016-03-02T12:07:32.629Z - info: 78. should not be started after stop is called - pass
2016-03-02T12:07:32.629Z - info: 79. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass

2016-03-02T12:07:32.630Z - info: 80. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass

2016-03-02T12:07:32.631Z - info: 81. #startUpdateAdvertisingAndListening should start hosting given router object - pass
2016-03-02T12:07:32.631Z - info: 82. #stop can be called multiple times in a row - pass

2016-03-02T12:07:32.632Z - info: 83. #startListeningForAdvertisements can be called multiple times in a row - pass
2016-03-02T12:07:32.632Z - info: 84. #stopListeningForAdvertisements can be called multiple times in a row - pass

2016-03-02T12:07:32.633Z - info: 85. #stopAdvertisingAndListening can be called multiple times in a row - pass

2016-03-02T12:07:32.634Z - info: 86. functions are run from a queue in the right order - pass

2016-03-02T12:07:32.635Z - info: 

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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/613623661dfc74c_Make_CI_build_and_unit_tests_pass_vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/613623661dfc74c_Make_CI_build_and_unit_tests_pass_vjrantal/thali01_samsung-SM-A500FU.md)

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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/613623661dfc74c_Make_CI_build_and_unit_tests_pass_vjrantal/thali02_LGE-Nexus 5.md)

[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/613623661dfc74c_Make_CI_build_and_unit_tests_pass_vjrantal/thali02_LGE-LG-D722.md)

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
[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/613623661dfc74c_Make_CI_build_and_unit_tests_pass_vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/613623661dfc74c_Make_CI_build_and_unit_tests_pass_vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  0be0c6c6 Test has  SUCCEEDED
Device test finished on 0be0c6c6 
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/613623661dfc74c_Make_CI_build_and_unit_tests_pass_vjrantal/thali04_samsung-SM-G900F.md)

[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/613623661dfc74c_Make_CI_build_and_unit_tests_pass_vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/613623661dfc74c_Make_CI_build_and_unit_tests_pass_vjrantal/thali04_samsung-SM-N910C.md)

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
[htc-Nexus 9](https://github.com/ThaliTester/TestResults/blob/613623661dfc74c_Make_CI_build_and_unit_tests_pass_vjrantal/thali05_htc-Nexus 9.md)

[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/613623661dfc74c_Make_CI_build_and_unit_tests_pass_vjrantal/thali05_samsung-SM-N9005.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/613623661dfc74c_Make_CI_build_and_unit_tests_pass_vjrantal/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/613623661dfc74c_Make_CI_build_and_unit_tests_pass_vjrantal/thali05_samsung-SM-G800H.md)

####Node name: thali06
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:0 
child process exited with code 0 on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:null 
child process exited with code null on device FA55PYS00566 
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:0 
child process exited with code 0 on device 022678fb504e29b0 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/613623661dfc74c_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/613623661dfc74c_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/613623661dfc74c_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:0 
child process exited with code 0 on device 4db5c8cc 
Error! Unexpected exit on device c5afcdcb app:com.test.thalitest code:0 
child process exited with code 0 on device c5afcdcb 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/613623661dfc74c_Make_CI_build_and_unit_tests_pass_vjrantal/thali07_samsung-SM-A500FU.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/613623661dfc74c_Make_CI_build_and_unit_tests_pass_vjrantal/thali07_samsung-SM-G900F.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/613623661dfc74c_Make_CI_build_and_unit_tests_pass_vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/613623661dfc74c_Make_CI_build_and_unit_tests_pass_vjrantal/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/613623661dfc74c_Make_CI_build_and_unit_tests_pass_vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/613623661dfc74c_Make_CI_build_and_unit_tests_pass_vjrantal/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/613623661dfc74c_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/613623661dfc74c_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/613623661dfc74c_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/613623661dfc74c_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone6-1.md)



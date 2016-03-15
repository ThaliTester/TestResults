#### Test 62947189e430ee9 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":8}}
2016-03-15T18:14:45.363Z - info: listening on *:3000

2016-03-15T18:14:46.580Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:0

2016-03-15T18:14:48.515Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:1

2016-03-15T18:14:48.978Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:2

2016-03-15T18:14:48.981Z - info: Required number of ios devices presented (2)

2016-03-15T18:14:48.985Z - info: Starting unit test run for platform: ios

2016-03-15T18:14:49.079Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:3

2016-03-15T18:14:49.082Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-15T18:14:49.603Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:4

2016-03-15T18:14:49.606Z - info: Required number of android devices presented (2)

2016-03-15T18:14:49.609Z - info: Starting unit test run for platform: android

2016-03-15T18:14:49.771Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-15T18:14:50.304Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-15T18:14:50.324Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:5

2016-03-15T18:14:50.325Z - info: Discarding surplus device: Apple-IpadAir2-1

2016-03-15T18:14:50.537Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-15T18:14:50.814Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-15T18:14:51.024Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-15T18:14:51.503Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-15T18:14:51.667Z - info: Running on ios test: 4. native server connections all up

2016-03-15T18:14:51.743Z - debug: Socket disconnected: transport close 3 (Apple-Iphone5s-1)

2016-03-15T18:14:52.046Z - info: Running on android test: 4. native server connections all up

2016-03-15T18:14:52.302Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-15T18:14:52.656Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-15T18:14:52.830Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-15T18:14:53.074Z - debug: Socket disconnected: transport close 5 (Apple-IpadAir2-1)

2016-03-15T18:14:53.196Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-15T18:14:53.284Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-15T18:14:53.647Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-15T18:14:53.746Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-15T18:14:54.081Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-15T18:14:54.192Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-15T18:14:54.583Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-15T18:14:55.224Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-15T18:14:55.520Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-15T18:14:55.940Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-15T18:14:56.102Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-15T18:14:56.473Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-15T18:14:56.545Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-15T18:14:56.796Z - info: Running on ios test: 13. closeAll with promise

2016-03-15T18:14:57.003Z - info: Running on android test: 13. closeAll with promise

2016-03-15T18:14:57.292Z - info: Running on ios test: 14. multiplex can send data

2016-03-15T18:14:57.484Z - info: Running on android test: 14. multiplex can send data

2016-03-15T18:14:57.854Z - info: Running on ios test: 15. enqueue and run in order

2016-03-15T18:14:57.989Z - info: Running on android test: 15. enqueue and run in order

2016-03-15T18:14:58.529Z - info: Running on ios test: 16. enqueueAtTop and run backwards

2016-03-15T18:14:58.752Z - info: Running on android test: 16. enqueueAtTop and run backwards

2016-03-15T18:14:59.319Z - info: Running on android test: 17. mix enqueue and enqueueAtTop

2016-03-15T18:14:59.331Z - info: Running on ios test: 17. mix enqueue and enqueueAtTop

2016-03-15T18:14:59.981Z - info: Running on android test: 18. queues handled independently

2016-03-15T18:15:00.008Z - info: Running on ios test: 18. queues handled independently

2016-03-15T18:15:00.593Z - info: Running on android test: 19. basic

2016-03-15T18:15:00.598Z - info: Running on ios test: 19. basic

2016-03-15T18:15:01.124Z - info: Running on android test: 20. another

2016-03-15T18:15:01.129Z - info: Running on ios test: 20. another

2016-03-15T18:15:01.694Z - info: Running on ios test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-15T18:15:01.698Z - info: Running on android test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-15T18:15:02.227Z - info: Running on ios test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-15T18:15:02.754Z - info: Running on android test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-15T18:15:02.891Z - info: Running on ios test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-15T18:15:03.244Z - info: Running on android test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-15T18:15:03.409Z - info: Running on ios test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-15T18:15:03.784Z - info: Running on android test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-15T18:15:03.961Z - info: Running on ios test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-15T18:15:04.278Z - info: Running on android test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-15T18:15:05.077Z - info: Running on android test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-15T18:15:05.765Z - info: Running on android test: 27. #start should fail if called twice in a row

2016-03-15T18:15:06.167Z - info: Running on android test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-15T18:15:07.005Z - info: Running on android test: 29. does not send duplicate availability changes

2016-03-15T18:15:07.891Z - info: Running on android test: 30. can get the network status

2016-03-15T18:15:08.341Z - info: Running on ios test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-15T18:15:08.438Z - info: Running on android test: 31. wifi peer is marked unavailable if announcements stop

2016-03-15T18:15:08.740Z - info: Running on ios test: 27. #start should fail if called twice in a row

2016-03-15T18:15:09.253Z - info: Running on ios test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-15T18:15:09.754Z - info: Running on ios test: 29. does not send duplicate availability changes

2016-03-15T18:15:09.986Z - info: Running on android test: 32. can get the network status before starting

2016-03-15T18:15:10.378Z - info: Running on ios test: 30. can get the network status

2016-03-15T18:15:10.659Z - info: Running on android test: 33. #generatePreambleAndBeacons bad args

2016-03-15T18:15:10.876Z - info: Running on ios test: 31. wifi peer is marked unavailable if announcements stop

2016-03-15T18:15:11.329Z - info: Running on android test: 34. #generatePreambleAndBeacons empty keys to notify

2016-03-15T18:15:11.912Z - info: Running on android test: 35. #generatePreambleAndBeacons multiple keys to notify

2016-03-15T18:15:12.430Z - info: Running on android test: 36. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-15T18:15:12.504Z - info: Running on ios test: 32. can get the network status before starting

2016-03-15T18:15:12.923Z - info: Running on android test: 37. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-15T18:15:13.077Z - info: Running on ios test: 33. #generatePreambleAndBeacons bad args

2016-03-15T18:15:13.359Z - info: Running on android test: 38. #parseBeacons expiration out of range lower

2016-03-15T18:15:13.482Z - info: Running on ios test: 34. #generatePreambleAndBeacons empty keys to notify

2016-03-15T18:15:13.754Z - info: Running on android test: 39. #parseBeacons expiration out of range lower

2016-03-15T18:15:13.872Z - info: Running on ios test: 35. #generatePreambleAndBeacons multiple keys to notify

2016-03-15T18:15:14.259Z - info: Running on android test: 40. #parseBeacons no beacons returns null

2016-03-15T18:15:14.512Z - info: Running on ios test: 36. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-15T18:15:14.697Z - info: Running on android test: 41. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-15T18:15:15.118Z - info: Running on ios test: 37. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-15T18:15:15.234Z - info: Running on android test: 42. #parseBeacons addressBookCallback fails decrypt

2016-03-15T18:15:15.620Z - info: Running on ios test: 38. #parseBeacons expiration out of range lower

2016-03-15T18:15:15.832Z - info: Running on android test: 43. #parseBeacons addressBookCallback returns no matches

2016-03-15T18:15:16.073Z - info: Running on ios test: 39. #parseBeacons expiration out of range lower

2016-03-15T18:15:16.405Z - info: Running on android test: 44. #parseBeacons addressBookCallback returns spurious match

2016-03-15T18:15:16.410Z - info: Running on ios test: 40. #parseBeacons no beacons returns null

2016-03-15T18:15:16.820Z - info: Running on ios test: 41. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-15T18:15:16.951Z - info: Running on android test: 45. #parseBeacons addressBookCallback returns public key

2016-03-15T18:15:17.225Z - info: Running on ios test: 42. #parseBeacons addressBookCallback fails decrypt

2016-03-15T18:15:17.488Z - info: Running on android test: 46. #parseBeacons with beacons both for and not for the user

2016-03-15T18:15:17.747Z - info: Running on ios test: 43. #parseBeacons addressBookCallback returns no matches

2016-03-15T18:15:17.955Z - info: Running on android test: 47. Start and stop ThaliNotificationServer

2016-03-15T18:15:18.280Z - info: Running on ios test: 44. #parseBeacons addressBookCallback returns spurious match

2016-03-15T18:15:18.534Z - info: Running on android test: 48. Pass an empty array to ThaliNotificationServer.start

2016-03-15T18:15:18.832Z - info: Running on ios test: 45. #parseBeacons addressBookCallback returns public key

2016-03-15T18:15:19.075Z - info: Running on android test: 49. Pass a string to ThaliNotificationServer.start

2016-03-15T18:15:19.375Z - info: Running on ios test: 46. #parseBeacons with beacons both for and not for the user

2016-03-15T18:15:19.517Z - info: Running on android test: 50. Pass an empty parameter to ThaliNotificationServer.start

2016-03-15T18:15:19.903Z - info: Running on ios test: 47. Start and stop ThaliNotificationServer

2016-03-15T18:15:20.032Z - info: Running on android test: 51. Make an HTTP request to /NotificationBeacons

2016-03-15T18:15:20.412Z - info: Running on ios test: 48. Pass an empty array to ThaliNotificationServer.start

2016-03-15T18:15:20.705Z - info: Running on android test: 52. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-15T18:15:20.807Z - info: Running on ios test: 49. Pass a string to ThaliNotificationServer.start

2016-03-15T18:15:21.118Z - info: Running on android test: 53. Make an HTTP request to /NotificationBeacons before calling start

2016-03-15T18:15:21.175Z - info: Running on ios test: 50. Pass an empty parameter to ThaliNotificationServer.start

2016-03-15T18:15:21.566Z - info: Running on ios test: 51. Make an HTTP request to /NotificationBeacons

2016-03-15T18:15:21.570Z - info: Running on android test: 54. #testThaliPeerAction - test getters

2016-03-15T18:15:21.999Z - info: Running on android test: 55. #testThaliPeerAction - start and kill

2016-03-15T18:15:22.220Z - info: Running on ios test: 52. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-15T18:15:22.471Z - info: Running on android test: 56. #testThaliPeerAction - double start

2016-03-15T18:15:22.716Z - info: Running on ios test: 53. Make an HTTP request to /NotificationBeacons before calling start

2016-03-15T18:15:22.855Z - info: Running on android test: 57. #testThaliPeerAction - start after kill

2016-03-15T18:15:23.209Z - info: Running on ios test: 54. #testThaliPeerAction - test getters

2016-03-15T18:15:23.257Z - info: Running on android test: 58. #testThaliPeerAction - make sure ids are unique

2016-03-15T18:15:23.685Z - info: Running on ios test: 55. #testThaliPeerAction - start and kill

2016-03-15T18:15:23.820Z - info: Running on android test: 59. Test PeerConnectionInformation basics

2016-03-15T18:15:24.336Z - info: Running on ios test: 56. #testThaliPeerAction - double start

2016-03-15T18:15:24.342Z - info: Running on android test: 60. Test PeerDictionary basic functionality

2016-03-15T18:15:24.885Z - info: Running on ios test: 57. #testThaliPeerAction - start after kill

2016-03-15T18:15:24.891Z - info: Running on android test: 61. Test PeerDictionary with multiple entries.

2016-03-15T18:15:26.831Z - info: Running on android test: 62. RESOLVED entries are removed before WAITING state entry.

2016-03-15T18:15:27.940Z - info: Running on android test: 63. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-15T18:15:29.141Z - info: Running on android test: 64. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-15T18:15:30.357Z - info: Running on android test: 65. #ThaliPeerPoolInterface - bad enqueues

2016-03-15T18:15:30.881Z - info: Running on android test: 66. #ThaliPeerPoolInterface - do not allow same object type

2016-03-15T18:15:31.330Z - info: Running on android test: 67. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-15T18:15:31.710Z - info: Running on android test: 68. compareBufferArrays

2016-03-15T18:15:32.068Z - info: Running on android test: 69. Call start twice and get error

2016-03-15T18:15:32.498Z - info: Running on android test: 70. Start and make sure it runs

2016-03-15T18:15:32.864Z - info: Running on android test: 71. Make sure getTimeWhenRun is right after start

2016-03-15T18:15:33.305Z - info: Running on android test: 72. Make sure getTimeWhenRun is -1 after function is called

2016-03-15T18:15:33.685Z - info: Running on android test: 73. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-15T18:15:34.037Z - info: Running on android test: 74. Test TransientState

2016-03-15T18:15:35.133Z - info: Running on android test: 75. No peers and empty database

2016-03-15T18:15:35.785Z - info: Running on android test: 76. One peer and empty DB

2016-03-15T18:15:35.849Z - info: Running on ios test: 58. #testThaliPeerAction - make sure ids are unique

2016-03-15T18:15:36.301Z - info: Running on ios test: 59. Test PeerConnectionInformation basics

2016-03-15T18:15:36.431Z - info: Running on android test: 77. One peer with _Local set behind current seq

2016-03-15T18:15:36.827Z - info: Running on ios test: 60. Test PeerDictionary basic functionality

2016-03-15T18:15:37.287Z - info: Running on ios test: 61. Test PeerDictionary with multiple entries.

2016-03-15T18:15:37.427Z - info: Running on android test: 78. One peer with _Local set equal to current seq

2016-03-15T18:15:39.329Z - info: Running on android test: 79. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-15T18:15:39.761Z - info: Running on ios test: 62. RESOLVED entries are removed before WAITING state entry.

2016-03-15T18:15:39.890Z - info: Running on android test: 80. Three peers, one not in DB, one behind and one ahead

2016-03-15T18:15:40.818Z - info: Running on android test: 81. More than maximum peers, make sure we only send maximum allowed

2016-03-15T18:15:41.302Z - info: Running on ios test: 63. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-15T18:15:42.030Z - info: Running on android test: 82. two peers with empty DB, update the doc

2016-03-15T18:15:42.775Z - info: Running on ios test: 64. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-15T18:15:42.947Z - info: Running on android test: 83. add doc and make sure tokens refresh when they expire

2016-03-15T18:15:43.868Z - info: Running on android test: 84. start and stop and start and stop

2016-03-15T18:15:44.121Z - info: Running on ios test: 65. #ThaliPeerPoolInterface - bad enqueues

2016-03-15T18:15:44.521Z - info: Running on ios test: 66. #ThaliPeerPoolInterface - do not allow same object type

2016-03-15T18:15:44.776Z - info: Running on android test: 85. two identical starts in a row

2016-03-15T18:15:45.019Z - info: Running on ios test: 67. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-15T18:15:45.554Z - info: Running on android test: 86. two different starts in a row

2016-03-15T18:15:45.680Z - info: Running on ios test: 68. compareBufferArrays

2016-03-15T18:15:46.115Z - info: Running on ios test: 69. Call start twice and get error

2016-03-15T18:15:46.381Z - info: Running on android test: 87. two stops and a start and two stops

2016-03-15T18:15:46.568Z - info: Running on ios test: 70. Start and make sure it runs

2016-03-15T18:15:46.987Z - info: Running on android test: 88. we properly enqueue requests so no then needed

2016-03-15T18:15:46.993Z - info: Running on ios test: 71. Make sure getTimeWhenRun is right after start

2016-03-15T18:15:47.632Z - info: Running on ios test: 72. Make sure getTimeWhenRun is -1 after function is called

2016-03-15T18:15:47.930Z - info: Running on android test: 89. test calculateSeqPointKeyId

2016-03-15T18:15:48.243Z - info: Running on ios test: 73. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-15T18:15:48.585Z - info: Running on android test: 90. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-15T18:15:49.058Z - info: Running on ios test: 74. Test TransientState

2016-03-15T18:15:49.282Z - info: Running on android test: 91. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-15T18:15:49.437Z - info: Running on ios test: 75. No peers and empty database

2016-03-15T18:15:49.774Z - info: Running on android test: 92. messages with invalid location or USN should be ignored

2016-03-15T18:15:50.080Z - info: Running on ios test: 76. One peer and empty DB

2016-03-15T18:15:50.416Z - info: Running on android test: 93. verify that Thali-specific messages are filtered correctly

2016-03-15T18:15:50.819Z - info: Running on ios test: 77. One peer with _Local set behind current seq

2016-03-15T18:15:50.823Z - info: Running on android test: 94. #startListeningForAdvertisements should fail if start not called

2016-03-15T18:15:51.243Z - info: Running on android test: 95. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-15T18:15:51.623Z - info: Running on ios test: 78. One peer with _Local set equal to current seq

2016-03-15T18:15:51.715Z - info: Running on android test: 96. #start should fail if called twice in a row

2016-03-15T18:15:52.157Z - info: Running on android test: 97. should not be started after stop is called

2016-03-15T18:15:52.456Z - info: Running on ios test: 79. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-15T18:15:52.531Z - info: Running on android test: 98. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-15T18:15:53.171Z - info: Running on android test: 99. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-15T18:15:53.643Z - info: Running on ios test: 80. Three peers, one not in DB, one behind and one ahead

2016-03-15T18:15:54.124Z - info: Running on android test: 100. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-15T18:15:54.623Z - info: Running on android test: 101. #stop can be called multiple times in a row

2016-03-15T18:15:54.697Z - info: Running on ios test: 81. More than maximum peers, make sure we only send maximum allowed

2016-03-15T18:15:55.097Z - info: Running on android test: 102. #startListeningForAdvertisements can be called multiple times in a row

2016-03-15T18:15:55.635Z - info: Running on android test: 103. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-15T18:15:56.071Z - info: Running on ios test: 82. two peers with empty DB, update the doc

2016-03-15T18:15:56.188Z - info: Running on android test: 104. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-15T18:15:56.935Z - info: Running on android test: 105. functions are run from a queue in the right order

2016-03-15T18:15:57.055Z - info: Running on ios test: 83. add doc and make sure tokens refresh when they expire

2016-03-15T18:15:57.475Z - info: Running on android test: 106. #ThaliPeerPoolDefault - single action

2016-03-15T18:15:58.157Z - info: Running on android test: 107. #ThaliPeerPoolDefault - multiple actions

2016-03-15T18:15:58.271Z - info: Running on ios test: 84. start and stop and start and stop

2016-03-15T18:15:58.626Z - info: Test run on android complete

2016-03-15T18:15:58.629Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-15T18:15:58.631Z - info: PLATFORM: android

2016-03-15T18:15:58.632Z - info: RESULT: PASS

2016-03-15T18:15:58.633Z - info: 107 of 107 tests completed

2016-03-15T18:15:58.634Z - info: 107/107 passed (0 failures)

2016-03-15T18:15:58.635Z - info: --- Test Details ---



2016-03-15T18:15:58.636Z - info: 1. calling createNativeListener directly rejects - pass

2016-03-15T18:15:58.637Z - info: 2. emits incomingConnectionState - pass

2016-03-15T18:15:58.639Z - info: 3. emits routerPortConnectionFailed - pass

2016-03-15T18:15:58.639Z - info: 4. native server connections all up - pass

2016-03-15T18:15:58.640Z - info: 5. native server - closing incoming stream cleans outgoing socket - pass

2016-03-15T18:15:58.641Z - info: 6. native server - closing incoming connection cleans outgoing socket - pass

2016-03-15T18:15:58.642Z - info: 7. native server - closing outgoing socket cleans associated mux stream - pass

2016-03-15T18:15:58.643Z - info: 8. native server - closing the whole server cleans everything up - pass
2016-03-15T18:15:58.644Z - info: 9. native server - we can get a ton of connections and data through and still clean up the server completely - pass

2016-03-15T18:15:58.645Z - info: 10. native server - simulate mux failure, make sure everything is cleaned up - pass

2016-03-15T18:15:58.646Z - info: 11. native server - timing out the incoming connection cleans everything up - pass

2016-03-15T18:15:58.647Z - info: 12. closeAll can close even when connections open - pass

2016-03-15T18:15:58.647Z - info: 13. closeAll with promise - pass

2016-03-15T18:15:58.648Z - info: 14. multiplex can send data - pass

2016-03-15T18:15:58.649Z - info: 15. enqueue and run in order - pass

2016-03-15T18:15:58.650Z - info: 16. enqueueAtTop and run backwards - pass
2016-03-15T18:15:58.651Z - info: 17. mix enqueue and enqueueAtTop - pass

2016-03-15T18:15:58.652Z - info: 18. queues handled independently - pass

2016-03-15T18:15:58.653Z - info: 19. basic - pass

2016-03-15T18:15:58.654Z - info: 20. another - pass

2016-03-15T18:15:58.655Z - info: 21. #startListeningForAdvertisements should fail if start not called - pass

2016-03-15T18:15:58.656Z - info: 22. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-15T18:15:58.657Z - info: 23. should be able to call #stopListeningForAdvertisements many times - pass

2016-03-15T18:15:58.658Z - info: 24. should be able to call #startListeningForAdvertisements many times - pass
2016-03-15T18:15:58.659Z - info: 25. should be able to call #startUpdateAdvertisingAndListening many times - pass

2016-03-15T18:15:58.660Z - info: 26. should be able to call #stopAdvertisingAndListening many times - pass

2016-03-15T18:15:58.660Z - info: 27. #start should fail if called twice in a row - pass

2016-03-15T18:15:58.661Z - info: 28. does not emit duplicate discoveryAdvertisingStateUpdate - pass

2016-03-15T18:15:58.662Z - info: 29. does not send duplicate availability changes - pass

2016-03-15T18:15:58.663Z - info: 30. can get the network status - pass

2016-03-15T18:15:58.664Z - info: 31. wifi peer is marked unavailable if announcements stop - pass
2016-03-15T18:15:58.665Z - info: 32. can get the network status before starting - pass
2016-03-15T18:15:58.666Z - info: 33. #generatePreambleAndBeacons bad args - pass
2016-03-15T18:15:58.667Z - info: 34. #generatePreambleAndBeacons empty keys to notify - pass

2016-03-15T18:15:58.667Z - info: 35. #generatePreambleAndBeacons multiple keys to notify - pass
2016-03-15T18:15:58.668Z - info: 36. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass

2016-03-15T18:15:58.669Z - info: 37. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass
2016-03-15T18:15:58.670Z - info: 38. #parseBeacons expiration out of range lower - pass

2016-03-15T18:15:58.671Z - info: 39. #parseBeacons expiration out of range lower - pass

2016-03-15T18:15:58.671Z - info: 40. #parseBeacons no beacons returns null - pass

2016-03-15T18:15:58.672Z - info: 41. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass

2016-03-15T18:15:58.673Z - info: 42. #parseBeacons addressBookCallback fails decrypt - pass

2016-03-15T18:15:58.674Z - info: 43. #parseBeacons addressBookCallback returns no matches - pass
2016-03-15T18:15:58.675Z - info: 44. #parseBeacons addressBookCallback returns spurious match - pass

2016-03-15T18:15:58.676Z - info: 45. #parseBeacons addressBookCallback returns public key - pass

2016-03-15T18:15:58.677Z - info: 46. #parseBeacons with beacons both for and not for the user - pass

2016-03-15T18:15:58.678Z - info: 47. Start and stop ThaliNotificationServer - pass

2016-03-15T18:15:58.679Z - info: 48. Pass an empty array to ThaliNotificationServer.start - pass

2016-03-15T18:15:58.680Z - info: 49. Pass a string to ThaliNotificationServer.start - pass

2016-03-15T18:15:58.681Z - info: 50. Pass an empty parameter to ThaliNotificationServer.start - pass
2016-03-15T18:15:58.682Z - info: 51. Make an HTTP request to /NotificationBeacons - pass

2016-03-15T18:15:58.683Z - info: 52. Make an HTTP request to /NotificationBeacons (no keys) - pass

2016-03-15T18:15:58.684Z - info: 53. Make an HTTP request to /NotificationBeacons before calling start - pass
2016-03-15T18:15:58.684Z - info: 54. #testThaliPeerAction - test getters - pass
2016-03-15T18:15:58.685Z - info: 55. #testThaliPeerAction - start and kill - pass
2016-03-15T18:15:58.686Z - info: 56. #testThaliPeerAction - double start - pass
2016-03-15T18:15:58.686Z - info: 57. #testThaliPeerAction - start after kill - pass
2016-03-15T18:15:58.687Z - info: 58. #testThaliPeerAction - make sure ids are unique - pass
2016-03-15T18:15:58.688Z - info: 59. Test PeerConnectionInformation basics - pass
2016-03-15T18:15:58.688Z - info: 60. Test PeerDictionary basic functionality - pass
2016-03-15T18:15:58.689Z - info: 61. Test PeerDictionary with multiple entries. - pass
2016-03-15T18:15:58.690Z - info: 62. RESOLVED entries are removed before WAITING state entry. - pass
2016-03-15T18:15:58.690Z - info: 63. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass
2016-03-15T18:15:58.691Z - info: 64. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass
2016-03-15T18:15:58.691Z - info: 65. #ThaliPeerPoolInterface - bad enqueues - pass
2016-03-15T18:15:58.692Z - info: 66. #ThaliPeerPoolInterface - do not allow same object type - pass
2016-03-15T18:15:58.692Z - info: 67. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass
2016-03-15T18:15:58.693Z - info: 68. compareBufferArrays - pass
2016-03-15T18:15:58.694Z - info: 69. Call start twice and get error - pass
2016-03-15T18:15:58.694Z - info: 70. Start and make sure it runs - pass
2016-03-15T18:15:58.695Z - info: 71. Make sure getTimeWhenRun is right after start - pass
2016-03-15T18:15:58.695Z - info: 72. Make sure getTimeWhenRun is -1 after function is called - pass
2016-03-15T18:15:58.696Z - info: 73. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass

2016-03-15T18:15:58.697Z - info: 74. Test TransientState - pass
2016-03-15T18:15:58.698Z - info: 75. No peers and empty database - pass
2016-03-15T18:15:58.698Z - info: 76. One peer and empty DB - pass

2016-03-15T18:15:58.699Z - info: 77. One peer with _Local set behind current seq - pass

2016-03-15T18:15:58.700Z - info: 78. One peer with _Local set equal to current seq - pass

2016-03-15T18:15:58.701Z - info: 79. One peer with _Local set ahead of current seq (and no this should not happen) - pass
2016-03-15T18:15:58.702Z - info: 80. Three peers, one not in DB, one behind and one ahead - pass

2016-03-15T18:15:58.703Z - info: 81. More than maximum peers, make sure we only send maximum allowed - pass

2016-03-15T18:15:58.707Z - info: 82. two peers with empty DB, update the doc - pass

2016-03-15T18:15:58.708Z - info: 83. add doc and make sure tokens refresh when they expire - pass

2016-03-15T18:15:58.709Z - info: 84. start and stop and start and stop - pass
2016-03-15T18:15:58.710Z - info: 85. two identical starts in a row - pass

2016-03-15T18:15:58.711Z - info: 86. two different starts in a row - pass

2016-03-15T18:15:58.712Z - info: 87. two stops and a start and two stops - pass

2016-03-15T18:15:58.713Z - info: 88. we properly enqueue requests so no then needed - pass

2016-03-15T18:15:58.714Z - info: 89. test calculateSeqPointKeyId - pass

2016-03-15T18:15:58.715Z - info: 90. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass

2016-03-15T18:15:58.716Z - info: 91. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass
2016-03-15T18:15:58.716Z - info: 92. messages with invalid location or USN should be ignored - pass

2016-03-15T18:15:58.717Z - info: 93. verify that Thali-specific messages are filtered correctly - pass

2016-03-15T18:15:58.718Z - info: 94. #startListeningForAdvertisements should fail if start not called - pass

2016-03-15T18:15:58.719Z - info: 95. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-15T18:15:58.720Z - info: 96. #start should fail if called twice in a row - pass

2016-03-15T18:15:58.721Z - info: 97. should not be started after stop is called - pass
2016-03-15T18:15:58.722Z - info: 98. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass

2016-03-15T18:15:58.723Z - info: 99. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass

2016-03-15T18:15:58.724Z - info: 100. #startUpdateAdvertisingAndListening should start hosting given router object - pass

2016-03-15T18:15:58.724Z - info: 101. #stop can be called multiple times in a row - pass
2016-03-15T18:15:58.725Z - info: 102. #startListeningForAdvertisements can be called multiple times in a row - pass
2016-03-15T18:15:58.726Z - info: 103. #stopListeningForAdvertisements can be called multiple times in a row - pass
2016-03-15T18:15:58.726Z - info: 104. #stopAdvertisingAndListening can be called multiple times in a row - pass

2016-03-15T18:15:58.727Z - info: 105. functions are run from a queue in the right order - pass
2016-03-15T18:15:58.728Z - info: 106. #ThaliPeerPoolDefault - single action - pass

2016-03-15T18:15:58.729Z - info: 107. #ThaliPeerPoolDefault - multiple actions - pass

2016-03-15T18:15:58.730Z - info: 

-== END ==-

2016-03-15T18:15:59.135Z - info: Running on ios test: 85. two identical starts in a row

2016-03-15T18:15:59.518Z - debug: Socket disconnected: transport close 4 (samsung-SM-N910C)

2016-03-15T18:15:59.619Z - debug: Socket disconnected: transport close 1 (LGE-LG-H815)

2016-03-15T18:15:59.902Z - info: Running on ios test: 86. two different starts in a row

2016-03-15T18:16:00.640Z - info: Running on ios test: 87. two stops and a start and two stops

2016-03-15T18:16:01.443Z - info: Running on ios test: 88. we properly enqueue requests so no then needed

2016-03-15T18:16:02.137Z - info: Running on ios test: 89. test calculateSeqPointKeyId

2016-03-15T18:16:02.657Z - info: Running on ios test: 90. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-15T18:16:03.048Z - info: Running on ios test: 91. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-15T18:16:03.461Z - info: Running on ios test: 92. messages with invalid location or USN should be ignored

2016-03-15T18:16:03.823Z - info: Running on ios test: 93. verify that Thali-specific messages are filtered correctly

2016-03-15T18:16:04.288Z - info: Running on ios test: 94. #startListeningForAdvertisements should fail if start not called

2016-03-15T18:16:04.552Z - info: Running on ios test: 95. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-15T18:16:04.901Z - info: Running on ios test: 96. #start should fail if called twice in a row

2016-03-15T18:16:05.308Z - info: Running on ios test: 97. should not be started after stop is called

2016-03-15T18:16:05.718Z - info: Running on ios test: 98. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-15T18:16:06.216Z - info: Running on ios test: 99. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-15T18:16:06.655Z - info: Running on ios test: 100. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-15T18:16:07.128Z - info: Running on ios test: 101. #stop can be called multiple times in a row

2016-03-15T18:16:07.613Z - info: Running on ios test: 102. #startListeningForAdvertisements can be called multiple times in a row

2016-03-15T18:16:08.126Z - info: Running on ios test: 103. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-15T18:16:08.569Z - info: Running on ios test: 104. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-15T18:16:08.996Z - info: Running on ios test: 105. functions are run from a queue in the right order

2016-03-15T18:16:09.438Z - info: Running on ios test: 106. #ThaliPeerPoolDefault - single action

2016-03-15T18:16:09.862Z - info: Running on ios test: 107. #ThaliPeerPoolDefault - multiple actions

2016-03-15T18:16:10.330Z - info: Test run on ios complete

2016-03-15T18:16:10.331Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-15T18:16:10.333Z - info: PLATFORM: ios

2016-03-15T18:16:10.334Z - info: RESULT: PASS

2016-03-15T18:16:10.335Z - info: 107 of 107 tests completed

2016-03-15T18:16:10.336Z - info: 107/107 passed (0 failures)

2016-03-15T18:16:10.337Z - info: --- Test Details ---



2016-03-15T18:16:10.339Z - info: 1. calling createNativeListener directly rejects - pass

2016-03-15T18:16:10.339Z - info: 2. emits incomingConnectionState - pass

2016-03-15T18:16:10.340Z - info: 3. emits routerPortConnectionFailed - pass
2016-03-15T18:16:10.341Z - info: 4. native server connections all up - pass

2016-03-15T18:16:10.342Z - info: 5. native server - closing incoming stream cleans outgoing socket - pass

2016-03-15T18:16:10.343Z - info: 6. native server - closing incoming connection cleans outgoing socket - pass

2016-03-15T18:16:10.344Z - info: 7. native server - closing outgoing socket cleans associated mux stream - pass

2016-03-15T18:16:10.345Z - info: 8. native server - closing the whole server cleans everything up - pass

2016-03-15T18:16:10.346Z - info: 9. native server - we can get a ton of connections and data through and still clean up the server completely - pass

2016-03-15T18:16:10.347Z - info: 10. native server - simulate mux failure, make sure everything is cleaned up - pass

2016-03-15T18:16:10.348Z - info: 11. native server - timing out the incoming connection cleans everything up - pass
2016-03-15T18:16:10.349Z - info: 12. closeAll can close even when connections open - pass

2016-03-15T18:16:10.350Z - info: 13. closeAll with promise - pass

2016-03-15T18:16:10.351Z - info: 14. multiplex can send data - pass

2016-03-15T18:16:10.351Z - info: 15. enqueue and run in order - pass

2016-03-15T18:16:10.352Z - info: 16. enqueueAtTop and run backwards - pass

2016-03-15T18:16:10.353Z - info: 17. mix enqueue and enqueueAtTop - pass

2016-03-15T18:16:10.354Z - info: 18. queues handled independently - pass
2016-03-15T18:16:10.355Z - info: 19. basic - pass

2016-03-15T18:16:10.356Z - info: 20. another - pass

2016-03-15T18:16:10.357Z - info: 21. #startListeningForAdvertisements should fail if start not called - pass

2016-03-15T18:16:10.358Z - info: 22. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-15T18:16:10.359Z - info: 23. should be able to call #stopListeningForAdvertisements many times - pass

2016-03-15T18:16:10.360Z - info: 24. should be able to call #startListeningForAdvertisements many times - pass

2016-03-15T18:16:10.361Z - info: 25. should be able to call #startUpdateAdvertisingAndListening many times - pass

2016-03-15T18:16:10.364Z - info: 26. should be able to call #stopAdvertisingAndListening many times - pass

2016-03-15T18:16:10.364Z - info: 27. #start should fail if called twice in a row - pass

2016-03-15T18:16:10.365Z - info: 28. does not emit duplicate discoveryAdvertisingStateUpdate - pass

2016-03-15T18:16:10.373Z - info: 29. does not send duplicate availability changes - pass

2016-03-15T18:16:10.374Z - info: 30. can get the network status - pass

2016-03-15T18:16:10.375Z - info: 31. wifi peer is marked unavailable if announcements stop - pass

2016-03-15T18:16:10.376Z - info: 32. can get the network status before starting - pass

2016-03-15T18:16:10.377Z - info: 33. #generatePreambleAndBeacons bad args - pass

2016-03-15T18:16:10.378Z - info: 34. #generatePreambleAndBeacons empty keys to notify - pass

2016-03-15T18:16:10.379Z - info: 35. #generatePreambleAndBeacons multiple keys to notify - pass
2016-03-15T18:16:10.380Z - info: 36. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass

2016-03-15T18:16:10.381Z - info: 37. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass

2016-03-15T18:16:10.385Z - info: 38. #parseBeacons expiration out of range lower - pass

2016-03-15T18:16:10.386Z - info: 39. #parseBeacons expiration out of range lower - pass

2016-03-15T18:16:10.414Z - info: 40. #parseBeacons no beacons returns null - pass

2016-03-15T18:16:10.415Z - info: 41. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass

2016-03-15T18:16:10.416Z - info: 42. #parseBeacons addressBookCallback fails decrypt - pass

2016-03-15T18:16:10.417Z - info: 43. #parseBeacons addressBookCallback returns no matches - pass

2016-03-15T18:16:10.418Z - info: 44. #parseBeacons addressBookCallback returns spurious match - pass
2016-03-15T18:16:10.419Z - info: 45. #parseBeacons addressBookCallback returns public key - pass

2016-03-15T18:16:10.420Z - info: 46. #parseBeacons with beacons both for and not for the user - pass

2016-03-15T18:16:10.420Z - info: 47. Start and stop ThaliNotificationServer - pass

2016-03-15T18:16:10.421Z - info: 48. Pass an empty array to ThaliNotificationServer.start - pass
2016-03-15T18:16:10.422Z - info: 49. Pass a string to ThaliNotificationServer.start - pass

2016-03-15T18:16:10.423Z - info: 50. Pass an empty parameter to ThaliNotificationServer.start - pass

2016-03-15T18:16:10.423Z - info: 51. Make an HTTP request to /NotificationBeacons - pass

2016-03-15T18:16:10.424Z - info: 52. Make an HTTP request to /NotificationBeacons (no keys) - pass

2016-03-15T18:16:10.425Z - info: 53. Make an HTTP request to /NotificationBeacons before calling start - pass
2016-03-15T18:16:10.426Z - info: 54. #testThaliPeerAction - test getters - pass

2016-03-15T18:16:10.427Z - info: 55. #testThaliPeerAction - start and kill - pass

2016-03-15T18:16:10.427Z - info: 56. #testThaliPeerAction - double start - pass

2016-03-15T18:16:10.428Z - info: 57. #testThaliPeerAction - start after kill - pass

2016-03-15T18:16:10.429Z - info: 58. #testThaliPeerAction - make sure ids are unique - pass

2016-03-15T18:16:10.430Z - info: 59. Test PeerConnectionInformation basics - pass
2016-03-15T18:16:10.431Z - info: 60. Test PeerDictionary basic functionality - pass

2016-03-15T18:16:10.432Z - info: 61. Test PeerDictionary with multiple entries. - pass

2016-03-15T18:16:10.432Z - info: 62. RESOLVED entries are removed before WAITING state entry. - pass

2016-03-15T18:16:10.433Z - info: 63. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass

2016-03-15T18:16:10.434Z - info: 64. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass
2016-03-15T18:16:10.435Z - info: 65. #ThaliPeerPoolInterface - bad enqueues - pass

2016-03-15T18:16:10.436Z - info: 66. #ThaliPeerPoolInterface - do not allow same object type - pass

2016-03-15T18:16:10.436Z - info: 67. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass

2016-03-15T18:16:10.437Z - info: 68. compareBufferArrays - pass
2016-03-15T18:16:10.438Z - info: 69. Call start twice and get error - pass

2016-03-15T18:16:10.439Z - info: 70. Start and make sure it runs - pass

2016-03-15T18:16:10.439Z - info: 71. Make sure getTimeWhenRun is right after start - pass

2016-03-15T18:16:10.440Z - info: 72. Make sure getTimeWhenRun is -1 after function is called - pass
2016-03-15T18:16:10.441Z - info: 73. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass
2016-03-15T18:16:10.442Z - info: 74. Test TransientState - pass
2016-03-15T18:16:10.443Z - info: 75. No peers and empty database - pass
2016-03-15T18:16:10.443Z - info: 76. One peer and empty DB - pass
2016-03-15T18:16:10.444Z - info: 77. One peer with _Local set behind current seq - pass
2016-03-15T18:16:10.444Z - info: 78. One peer with _Local set equal to current seq - pass

2016-03-15T18:16:10.445Z - info: 79. One peer with _Local set ahead of current seq (and no this should not happen) - pass
2016-03-15T18:16:10.445Z - info: 80. Three peers, one not in DB, one behind and one ahead - pass
2016-03-15T18:16:10.446Z - info: 81. More than maximum peers, make sure we only send maximum allowed - pass
2016-03-15T18:16:10.447Z - info: 82. two peers with empty DB, update the doc - pass
2016-03-15T18:16:10.448Z - info: 83. add doc and make sure tokens refresh when they expire - pass

2016-03-15T18:16:10.448Z - info: 84. start and stop and start and stop - pass
2016-03-15T18:16:10.449Z - info: 85. two identical starts in a row - pass

2016-03-15T18:16:10.450Z - info: 86. two different starts in a row - pass

2016-03-15T18:16:10.450Z - info: 87. two stops and a start and two stops - pass

2016-03-15T18:16:10.451Z - info: 88. we properly enqueue requests so no then needed - pass
2016-03-15T18:16:10.452Z - info: 89. test calculateSeqPointKeyId - pass

2016-03-15T18:16:10.453Z - info: 90. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass
2016-03-15T18:16:10.454Z - info: 91. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass
2016-03-15T18:16:10.454Z - info: 92. messages with invalid location or USN should be ignored - pass
2016-03-15T18:16:10.455Z - info: 93. verify that Thali-specific messages are filtered correctly - pass
2016-03-15T18:16:10.455Z - info: 94. #startListeningForAdvertisements should fail if start not called - pass
2016-03-15T18:16:10.456Z - info: 95. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-15T18:16:10.456Z - info: 96. #start should fail if called twice in a row - pass
2016-03-15T18:16:10.457Z - info: 97. should not be started after stop is called - pass
2016-03-15T18:16:10.458Z - info: 98. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass
2016-03-15T18:16:10.458Z - info: 99. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass
2016-03-15T18:16:10.459Z - info: 100. #startUpdateAdvertisingAndListening should start hosting given router object - pass
2016-03-15T18:16:10.459Z - info: 101. #stop can be called multiple times in a row - pass
2016-03-15T18:16:10.460Z - info: 102. #startListeningForAdvertisements can be called multiple times in a row - pass
2016-03-15T18:16:10.460Z - info: 103. #stopListeningForAdvertisements can be called multiple times in a row - pass
2016-03-15T18:16:10.461Z - info: 104. #stopAdvertisingAndListening can be called multiple times in a row - pass
2016-03-15T18:16:10.461Z - info: 105. functions are run from a queue in the right order - pass
2016-03-15T18:16:10.462Z - info: 106. #ThaliPeerPoolDefault - single action - pass
2016-03-15T18:16:10.462Z - info: 107. #ThaliPeerPoolDefault - multiple actions - pass
2016-03-15T18:16:10.463Z - info: 

-== END ==-

2016-03-15T18:15:34.392Z - error: test server: Device Apple-Iphone6-1


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
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62947189e430ee9_Run_one_test_file_through_the_coordinator_at_a_time_yaronyg/thali01_samsung-SM-A500FU.md)

####Node name: thali03
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Android task is completed. [SUCCESS]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/62947189e430ee9_Run_one_test_file_through_the_coordinator_at_a_time_yaronyg/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/62947189e430ee9_Run_one_test_file_through_the_coordinator_at_a_time_yaronyg/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Android task is completed. [SUCCESS]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/62947189e430ee9_Run_one_test_file_through_the_coordinator_at_a_time_yaronyg/thali05_LGE-LG-H815.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62947189e430ee9_Run_one_test_file_through_the_coordinator_at_a_time_yaronyg/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/62947189e430ee9_Run_one_test_file_through_the_coordinator_at_a_time_yaronyg/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:0 
child process exited with code 0 on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62947189e430ee9_Run_one_test_file_through_the_coordinator_at_a_time_yaronyg/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:0 
child process exited with code 0 on device 4325e43f 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62947189e430ee9_Run_one_test_file_through_the_coordinator_at_a_time_yaronyg/thali08_samsung-SM-A300FU.md)




###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/62947189e430ee9_Run_one_test_file_through_the_coordinator_at_a_time_yaronyg/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/62947189e430ee9_Run_one_test_file_through_the_coordinator_at_a_time_yaronyg/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/62947189e430ee9_Run_one_test_file_through_the_coordinator_at_a_time_yaronyg/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/62947189e430ee9_Run_one_test_file_through_the_coordinator_at_a_time_yaronyg/iOS_Iphone5s-1.md)



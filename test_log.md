#### Test 62885377aa56850 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":8}}
2016-03-15T11:15:18.408Z - info: listening on *:3000

2016-03-15T11:15:19.199Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:0

2016-03-15T11:15:20.520Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:1

2016-03-15T11:15:20.761Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:2

2016-03-15T11:15:20.763Z - info: Required number of ios devices presented (2)

2016-03-15T11:15:20.767Z - info: Starting unit test run for platform: ios

2016-03-15T11:15:20.999Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:3

2016-03-15T11:15:21.002Z - info: Discarding surplus device: Apple-Iphone6-1

2016-03-15T11:15:21.340Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-15T11:15:21.726Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-15T11:15:22.171Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-15T11:15:22.550Z - info: Running on ios test: 4. native server connections all up

2016-03-15T11:15:22.712Z - debug: Device presented: motorola-XT1072 (android) unittest socket:4

2016-03-15T11:15:22.713Z - info: Required number of android devices presented (2)

2016-03-15T11:15:22.715Z - info: Starting unit test run for platform: android

2016-03-15T11:15:23.027Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-15T11:15:23.449Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-15T11:15:23.475Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-15T11:15:23.703Z - debug: Socket disconnected: transport close 3 (Apple-Iphone6-1)

2016-03-15T11:15:23.840Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:5

2016-03-15T11:15:23.841Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-15T11:15:23.854Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-15T11:15:23.961Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-15T11:15:24.240Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-15T11:15:24.339Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-15T11:15:24.681Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-15T11:15:24.811Z - info: Running on android test: 4. native server connections all up

2016-03-15T11:15:25.194Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-15T11:15:25.439Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-15T11:15:25.597Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-15T11:15:26.674Z - debug: Socket disconnected: transport close 5 (Apple-Iphone5s-1)

2016-03-15T11:15:26.712Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-15T11:15:27.045Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-15T11:15:27.380Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-15T11:15:27.637Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-15T11:15:28.097Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-15T11:15:28.127Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-15T11:15:28.341Z - info: Running on ios test: 13. closeAll with promise

2016-03-15T11:15:28.437Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-15T11:15:28.662Z - info: Running on ios test: 14. multiplex can send data

2016-03-15T11:15:28.866Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-15T11:15:29.068Z - info: Running on ios test: 15. enqueue and run in order

2016-03-15T11:15:29.192Z - info: Running on android test: 13. closeAll with promise

2016-03-15T11:15:29.469Z - info: Running on android test: 14. multiplex can send data

2016-03-15T11:15:29.725Z - info: Running on android test: 15. enqueue and run in order

2016-03-15T11:15:30.460Z - info: Running on android test: 16. enqueueAtTop and run backwards

2016-03-15T11:15:30.480Z - info: Running on ios test: 16. enqueueAtTop and run backwards

2016-03-15T11:15:30.785Z - info: Running on android test: 17. mix enqueue and enqueueAtTop

2016-03-15T11:15:31.154Z - info: Running on ios test: 17. mix enqueue and enqueueAtTop

2016-03-15T11:15:31.292Z - info: Running on android test: 18. queues handled independently

2016-03-15T11:15:31.556Z - info: Running on ios test: 18. queues handled independently

2016-03-15T11:15:31.582Z - info: Running on android test: 19. basic

2016-03-15T11:15:31.834Z - info: Running on android test: 20. another

2016-03-15T11:15:31.853Z - info: Running on ios test: 19. basic

2016-03-15T11:15:32.108Z - info: Running on android test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-15T11:15:32.176Z - info: Running on ios test: 20. another

2016-03-15T11:15:32.364Z - info: Running on android test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-15T11:15:32.474Z - info: Running on ios test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-15T11:15:32.653Z - info: Running on android test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-15T11:15:32.738Z - info: Running on ios test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-15T11:15:32.989Z - info: Running on android test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-15T11:15:33.272Z - info: Running on ios test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-15T11:15:33.359Z - info: Running on android test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-15T11:15:33.817Z - info: Running on android test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-15T11:15:34.160Z - info: Running on android test: 27. #start should fail if called twice in a row

2016-03-15T11:15:34.316Z - info: Running on ios test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-15T11:15:34.490Z - info: Running on android test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-15T11:15:34.687Z - info: Running on ios test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-15T11:15:35.077Z - info: Running on ios test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-15T11:15:35.190Z - info: Running on android test: 29. does not send duplicate availability changes

2016-03-15T11:15:35.348Z - info: Running on ios test: 27. #start should fail if called twice in a row

2016-03-15T11:15:35.600Z - info: Running on ios test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-15T11:15:35.964Z - info: Running on ios test: 29. does not send duplicate availability changes

2016-03-15T11:15:35.970Z - info: Running on android test: 30. can get the network status

2016-03-15T11:15:36.267Z - info: Running on ios test: 30. can get the network status

2016-03-15T11:15:36.271Z - info: Running on android test: 31. wifi peer is marked unavailable if announcements stop

2016-03-15T11:15:36.594Z - info: Running on ios test: 31. wifi peer is marked unavailable if announcements stop

2016-03-15T11:15:37.652Z - info: Running on android test: 32. can get the network status before starting

2016-03-15T11:15:37.862Z - info: Running on ios test: 32. can get the network status before starting

2016-03-15T11:15:37.910Z - info: Running on android test: 33. #generatePreambleAndBeacons bad args

2016-03-15T11:15:38.104Z - info: Running on ios test: 33. #generatePreambleAndBeacons bad args

2016-03-15T11:15:38.233Z - info: Running on android test: 34. #generatePreambleAndBeacons empty keys to notify

2016-03-15T11:15:38.437Z - info: Running on ios test: 34. #generatePreambleAndBeacons empty keys to notify

2016-03-15T11:15:38.508Z - info: Running on android test: 35. #generatePreambleAndBeacons multiple keys to notify

2016-03-15T11:15:38.709Z - info: Running on ios test: 35. #generatePreambleAndBeacons multiple keys to notify

2016-03-15T11:15:38.912Z - info: Running on android test: 36. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-15T11:15:39.067Z - info: Running on ios test: 36. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-15T11:15:39.206Z - info: Running on android test: 37. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-15T11:15:39.332Z - info: Running on ios test: 37. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-15T11:15:39.460Z - info: Running on android test: 38. #parseBeacons expiration out of range lower

2016-03-15T11:15:39.717Z - info: Running on ios test: 38. #parseBeacons expiration out of range lower

2016-03-15T11:15:39.811Z - info: Running on android test: 39. #parseBeacons expiration out of range lower

2016-03-15T11:15:40.030Z - info: Running on ios test: 39. #parseBeacons expiration out of range lower

2016-03-15T11:15:40.154Z - info: Running on android test: 40. #parseBeacons no beacons returns null

2016-03-15T11:15:40.353Z - info: Running on ios test: 40. #parseBeacons no beacons returns null

2016-03-15T11:15:40.481Z - info: Running on android test: 41. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-15T11:15:40.603Z - info: Running on ios test: 41. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-15T11:15:40.735Z - info: Running on android test: 42. #parseBeacons addressBookCallback fails decrypt

2016-03-15T11:15:40.922Z - info: Running on ios test: 42. #parseBeacons addressBookCallback fails decrypt

2016-03-15T11:15:41.236Z - info: Running on android test: 43. #parseBeacons addressBookCallback returns no matches

2016-03-15T11:15:41.662Z - info: Running on android test: 44. #parseBeacons addressBookCallback returns spurious match

2016-03-15T11:15:42.064Z - info: Running on android test: 45. #parseBeacons addressBookCallback returns public key

2016-03-15T11:15:42.067Z - info: Running on ios test: 43. #parseBeacons addressBookCallback returns no matches

2016-03-15T11:15:42.409Z - info: Running on ios test: 44. #parseBeacons addressBookCallback returns spurious match

2016-03-15T11:15:42.503Z - info: Running on android test: 46. #parseBeacons with beacons both for and not for the user

2016-03-15T11:15:42.761Z - info: Running on ios test: 45. #parseBeacons addressBookCallback returns public key

2016-03-15T11:15:42.870Z - info: Running on android test: 47. Start and stop ThaliNotificationServer

2016-03-15T11:15:43.084Z - info: Running on ios test: 46. #parseBeacons with beacons both for and not for the user

2016-03-15T11:15:43.306Z - info: Running on android test: 48. Pass an empty array to ThaliNotificationServer.start

2016-03-15T11:15:43.435Z - info: Running on ios test: 47. Start and stop ThaliNotificationServer

2016-03-15T11:15:43.711Z - info: Running on android test: 49. Pass a string to ThaliNotificationServer.start

2016-03-15T11:15:43.826Z - info: Running on ios test: 48. Pass an empty array to ThaliNotificationServer.start

2016-03-15T11:15:44.089Z - info: Running on android test: 50. Pass an empty parameter to ThaliNotificationServer.start

2016-03-15T11:15:44.297Z - info: Running on ios test: 49. Pass a string to ThaliNotificationServer.start

2016-03-15T11:15:44.540Z - info: Running on android test: 51. Make an HTTP request to /NotificationBeacons

2016-03-15T11:15:44.781Z - info: Running on ios test: 50. Pass an empty parameter to ThaliNotificationServer.start

2016-03-15T11:15:45.177Z - info: Running on android test: 52. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-15T11:15:45.306Z - info: Running on ios test: 51. Make an HTTP request to /NotificationBeacons

2016-03-15T11:15:45.758Z - info: Running on android test: 53. Make an HTTP request to /NotificationBeacons before calling start

2016-03-15T11:15:45.898Z - info: Running on ios test: 52. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-15T11:15:46.183Z - info: Running on android test: 54. #testThaliPeerAction - test getters

2016-03-15T11:15:46.486Z - info: Running on android test: 55. #testThaliPeerAction - start and kill

2016-03-15T11:15:46.692Z - info: Running on android test: 56. #testThaliPeerAction - double start

2016-03-15T11:15:46.879Z - info: Running on android test: 57. #testThaliPeerAction - start after kill

2016-03-15T11:15:47.158Z - info: Running on ios test: 53. Make an HTTP request to /NotificationBeacons before calling start

2016-03-15T11:15:47.192Z - info: Running on android test: 58. #testThaliPeerAction - make sure ids are unique

2016-03-15T11:15:47.425Z - info: Running on android test: 59. Test PeerConnectionInformation basics

2016-03-15T11:15:47.530Z - info: Running on ios test: 54. #testThaliPeerAction - test getters

2016-03-15T11:15:47.712Z - info: Running on android test: 60. Test PeerDictionary basic functionality

2016-03-15T11:15:47.767Z - info: Running on ios test: 55. #testThaliPeerAction - start and kill

2016-03-15T11:15:48.021Z - info: Running on android test: 61. Test PeerDictionary with multiple entries.

2016-03-15T11:15:48.076Z - info: Running on ios test: 56. #testThaliPeerAction - double start

2016-03-15T11:15:48.404Z - info: Running on ios test: 57. #testThaliPeerAction - start after kill

2016-03-15T11:15:49.105Z - info: Running on ios test: 58. #testThaliPeerAction - make sure ids are unique

2016-03-15T11:15:49.588Z - info: Running on ios test: 59. Test PeerConnectionInformation basics

2016-03-15T11:15:50.175Z - info: Running on ios test: 60. Test PeerDictionary basic functionality

2016-03-15T11:15:50.510Z - info: Running on ios test: 61. Test PeerDictionary with multiple entries.

2016-03-15T11:15:51.565Z - info: Running on android test: 62. RESOLVED entries are removed before WAITING state entry.

2016-03-15T11:15:52.744Z - info: Running on ios test: 62. RESOLVED entries are removed before WAITING state entry.

2016-03-15T11:15:53.510Z - info: Running on android test: 63. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-15T11:15:54.067Z - info: Running on ios test: 63. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-15T11:15:55.299Z - info: Running on ios test: 64. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-15T11:15:55.384Z - info: Running on android test: 64. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-15T11:15:56.536Z - info: Running on ios test: 65. #ThaliPeerPoolInterface - bad enqueues

2016-03-15T11:15:56.774Z - info: Running on ios test: 66. #ThaliPeerPoolInterface - do not allow same object type

2016-03-15T11:15:57.034Z - info: Running on ios test: 67. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-15T11:15:57.110Z - info: Running on android test: 65. #ThaliPeerPoolInterface - bad enqueues

2016-03-15T11:15:57.322Z - info: Running on ios test: 68. compareBufferArrays

2016-03-15T11:15:57.363Z - info: Running on android test: 66. #ThaliPeerPoolInterface - do not allow same object type

2016-03-15T11:15:57.574Z - info: Running on ios test: 69. Call start twice and get error

2016-03-15T11:15:57.599Z - info: Running on android test: 67. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-15T11:15:57.825Z - info: Running on android test: 68. compareBufferArrays

2016-03-15T11:15:58.043Z - info: Running on android test: 69. Call start twice and get error

2016-03-15T11:15:58.243Z - info: Running on android test: 70. Start and make sure it runs

2016-03-15T11:15:58.513Z - info: Running on ios test: 70. Start and make sure it runs

2016-03-15T11:15:58.539Z - info: Running on android test: 71. Make sure getTimeWhenRun is right after start

2016-03-15T11:15:58.770Z - info: Running on android test: 72. Make sure getTimeWhenRun is -1 after function is called

2016-03-15T11:15:58.773Z - info: Running on ios test: 71. Make sure getTimeWhenRun is right after start

2016-03-15T11:15:59.048Z - info: Running on android test: 73. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-15T11:15:59.051Z - info: Running on ios test: 72. Make sure getTimeWhenRun is -1 after function is called

2016-03-15T11:15:59.436Z - info: Running on android test: 74. Test TransientState

2016-03-15T11:15:59.440Z - info: Running on ios test: 73. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-15T11:15:59.724Z - info: Running on ios test: 74. Test TransientState

2016-03-15T11:15:59.732Z - info: Running on android test: 75. No peers and empty database

2016-03-15T11:16:00.003Z - info: Running on ios test: 75. No peers and empty database

2016-03-15T11:16:00.576Z - info: Running on android test: 76. One peer and empty DB

2016-03-15T11:16:00.621Z - info: Running on ios test: 76. One peer and empty DB

2016-03-15T11:16:01.149Z - info: Running on ios test: 77. One peer with _Local set behind current seq

2016-03-15T11:16:01.786Z - info: Running on ios test: 78. One peer with _Local set equal to current seq

2016-03-15T11:16:01.805Z - info: Running on android test: 77. One peer with _Local set behind current seq

2016-03-15T11:16:02.315Z - info: Running on ios test: 79. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-15T11:16:02.907Z - info: Running on ios test: 80. Three peers, one not in DB, one behind and one ahead

2016-03-15T11:16:03.043Z - info: Running on android test: 78. One peer with _Local set equal to current seq

2016-03-15T11:16:03.672Z - info: Running on ios test: 81. More than maximum peers, make sure we only send maximum allowed

2016-03-15T11:16:03.700Z - info: Running on android test: 79. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-15T11:16:04.169Z - info: Running on android test: 80. Three peers, one not in DB, one behind and one ahead

2016-03-15T11:16:04.754Z - info: Running on android test: 81. More than maximum peers, make sure we only send maximum allowed

2016-03-15T11:16:05.041Z - info: Running on ios test: 82. two peers with empty DB, update the doc

2016-03-15T11:16:05.790Z - info: Running on ios test: 83. add doc and make sure tokens refresh when they expire

2016-03-15T11:16:06.331Z - info: Running on android test: 82. two peers with empty DB, update the doc

2016-03-15T11:16:06.944Z - info: Running on android test: 83. add doc and make sure tokens refresh when they expire

2016-03-15T11:16:06.949Z - info: Running on ios test: 84. start and stop and start and stop

2016-03-15T11:16:07.529Z - info: Running on ios test: 85. two identical starts in a row

2016-03-15T11:16:07.873Z - info: Running on android test: 84. start and stop and start and stop

2016-03-15T11:16:08.031Z - info: Running on ios test: 86. two different starts in a row

2016-03-15T11:16:08.343Z - info: Running on android test: 85. two identical starts in a row

2016-03-15T11:16:08.541Z - info: Running on ios test: 87. two stops and a start and two stops

2016-03-15T11:16:08.789Z - info: Running on android test: 86. two different starts in a row

2016-03-15T11:16:09.045Z - info: Running on ios test: 88. we properly enqueue requests so no then needed

2016-03-15T11:16:09.339Z - info: Running on android test: 87. two stops and a start and two stops

2016-03-15T11:16:09.659Z - info: Running on ios test: 89. test calculateSeqPointKeyId

2016-03-15T11:16:09.854Z - info: Running on android test: 88. we properly enqueue requests so no then needed

2016-03-15T11:16:09.960Z - info: Running on ios test: 90. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-15T11:16:10.303Z - info: Running on ios test: 91. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-15T11:16:10.334Z - info: Running on android test: 89. test calculateSeqPointKeyId

2016-03-15T11:16:10.667Z - info: Running on android test: 90. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-15T11:16:11.014Z - info: Running on android test: 91. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-15T11:16:11.252Z - info: Running on ios test: 92. messages with invalid location or USN should be ignored

2016-03-15T11:16:11.410Z - info: Running on android test: 92. messages with invalid location or USN should be ignored

2016-03-15T11:16:11.580Z - info: Running on ios test: 93. verify that Thali-specific messages are filtered correctly

2016-03-15T11:16:11.814Z - info: Running on android test: 93. verify that Thali-specific messages are filtered correctly

2016-03-15T11:16:11.902Z - info: Running on ios test: 94. #startListeningForAdvertisements should fail if start not called

2016-03-15T11:16:12.091Z - info: Running on android test: 94. #startListeningForAdvertisements should fail if start not called

2016-03-15T11:16:12.196Z - info: Running on ios test: 95. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-15T11:16:12.440Z - info: Running on android test: 95. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-15T11:16:12.617Z - info: Running on ios test: 96. #start should fail if called twice in a row

2016-03-15T11:16:12.823Z - info: Running on android test: 96. #start should fail if called twice in a row

2016-03-15T11:16:12.910Z - info: Running on ios test: 97. should not be started after stop is called

2016-03-15T11:16:13.106Z - info: Running on android test: 97. should not be started after stop is called

2016-03-15T11:16:13.212Z - info: Running on ios test: 98. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-15T11:16:13.420Z - info: Running on android test: 98. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-15T11:16:13.552Z - info: Running on ios test: 99. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-15T11:16:13.744Z - info: Running on android test: 99. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-15T11:16:14.017Z - info: Running on ios test: 100. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-15T11:16:14.026Z - info: Running on android test: 100. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-15T11:16:14.332Z - info: Running on android test: 101. #stop can be called multiple times in a row

2016-03-15T11:16:14.344Z - info: Running on ios test: 101. #stop can be called multiple times in a row

2016-03-15T11:16:14.598Z - info: Running on android test: 102. #startListeningForAdvertisements can be called multiple times in a row

2016-03-15T11:16:14.657Z - info: Running on ios test: 102. #startListeningForAdvertisements can be called multiple times in a row

2016-03-15T11:16:14.974Z - info: Running on android test: 103. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-15T11:16:15.048Z - info: Running on ios test: 103. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-15T11:16:15.329Z - info: Running on android test: 104. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-15T11:16:15.335Z - info: Running on ios test: 104. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-15T11:16:15.622Z - info: Running on android test: 105. functions are run from a queue in the right order

2016-03-15T11:16:15.637Z - info: Running on ios test: 105. functions are run from a queue in the right order

2016-03-15T11:16:16.009Z - info: Running on android test: 106. #ThaliPeerPoolDefault - single action

2016-03-15T11:16:16.014Z - info: Running on ios test: 106. #ThaliPeerPoolDefault - single action

2016-03-15T11:16:16.324Z - info: Running on android test: 107. #ThaliPeerPoolDefault - multiple actions

2016-03-15T11:16:16.365Z - info: Running on ios test: 107. #ThaliPeerPoolDefault - multiple actions

2016-03-15T11:16:16.606Z - info: Test run on android complete

2016-03-15T11:16:16.609Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-15T11:16:16.611Z - info: PLATFORM: android

2016-03-15T11:16:16.612Z - info: RESULT: PASS

2016-03-15T11:16:16.612Z - info: 107 of 107 tests completed

2016-03-15T11:16:16.614Z - info: 107/107 passed (0 failures)
2016-03-15T11:16:16.614Z - info: --- Test Details ---



2016-03-15T11:16:16.615Z - info: 1. calling createNativeListener directly rejects - pass

2016-03-15T11:16:16.616Z - info: 2. emits incomingConnectionState - pass

2016-03-15T11:16:16.617Z - info: 3. emits routerPortConnectionFailed - pass
2016-03-15T11:16:16.618Z - info: 4. native server connections all up - pass

2016-03-15T11:16:16.619Z - info: 5. native server - closing incoming stream cleans outgoing socket - pass

2016-03-15T11:16:16.620Z - info: 6. native server - closing incoming connection cleans outgoing socket - pass
2016-03-15T11:16:16.620Z - info: 7. native server - closing outgoing socket cleans associated mux stream - pass

2016-03-15T11:16:16.621Z - info: 8. native server - closing the whole server cleans everything up - pass

2016-03-15T11:16:16.622Z - info: 9. native server - we can get a ton of connections and data through and still clean up the server completely - pass
2016-03-15T11:16:16.623Z - info: 10. native server - simulate mux failure, make sure everything is cleaned up - pass
2016-03-15T11:16:16.624Z - info: 11. native server - timing out the incoming connection cleans everything up - pass
2016-03-15T11:16:16.624Z - info: 12. closeAll can close even when connections open - pass

2016-03-15T11:16:16.625Z - info: 13. closeAll with promise - pass
2016-03-15T11:16:16.625Z - info: 14. multiplex can send data - pass

2016-03-15T11:16:16.626Z - info: 15. enqueue and run in order - pass

2016-03-15T11:16:16.627Z - info: 16. enqueueAtTop and run backwards - pass
2016-03-15T11:16:16.628Z - info: 17. mix enqueue and enqueueAtTop - pass

2016-03-15T11:16:16.629Z - info: 18. queues handled independently - pass

2016-03-15T11:16:16.630Z - info: 19. basic - pass

2016-03-15T11:16:16.630Z - info: 20. another - pass
2016-03-15T11:16:16.631Z - info: 21. #startListeningForAdvertisements should fail if start not called - pass

2016-03-15T11:16:16.632Z - info: 22. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-15T11:16:16.633Z - info: 23. should be able to call #stopListeningForAdvertisements many times - pass

2016-03-15T11:16:16.634Z - info: 24. should be able to call #startListeningForAdvertisements many times - pass
2016-03-15T11:16:16.635Z - info: 25. should be able to call #startUpdateAdvertisingAndListening many times - pass

2016-03-15T11:16:16.635Z - info: 26. should be able to call #stopAdvertisingAndListening many times - pass

2016-03-15T11:16:16.636Z - info: 27. #start should fail if called twice in a row - pass

2016-03-15T11:16:16.638Z - info: 28. does not emit duplicate discoveryAdvertisingStateUpdate - pass

2016-03-15T11:16:16.639Z - info: 29. does not send duplicate availability changes - pass

2016-03-15T11:16:16.639Z - info: 30. can get the network status - pass
2016-03-15T11:16:16.640Z - info: 31. wifi peer is marked unavailable if announcements stop - pass

2016-03-15T11:16:16.641Z - info: 32. can get the network status before starting - pass
2016-03-15T11:16:16.642Z - info: 33. #generatePreambleAndBeacons bad args - pass
2016-03-15T11:16:16.642Z - info: 34. #generatePreambleAndBeacons empty keys to notify - pass
2016-03-15T11:16:16.643Z - info: 35. #generatePreambleAndBeacons multiple keys to notify - pass
2016-03-15T11:16:16.643Z - info: 36. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass
2016-03-15T11:16:16.644Z - info: 37. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass
2016-03-15T11:16:16.644Z - info: 38. #parseBeacons expiration out of range lower - pass
2016-03-15T11:16:16.645Z - info: 39. #parseBeacons expiration out of range lower - pass
2016-03-15T11:16:16.646Z - info: 40. #parseBeacons no beacons returns null - pass
2016-03-15T11:16:16.646Z - info: 41. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass
2016-03-15T11:16:16.647Z - info: 42. #parseBeacons addressBookCallback fails decrypt - pass
2016-03-15T11:16:16.647Z - info: 43. #parseBeacons addressBookCallback returns no matches - pass
2016-03-15T11:16:16.648Z - info: 44. #parseBeacons addressBookCallback returns spurious match - pass
2016-03-15T11:16:16.648Z - info: 45. #parseBeacons addressBookCallback returns public key - pass
2016-03-15T11:16:16.649Z - info: 46. #parseBeacons with beacons both for and not for the user - pass
2016-03-15T11:16:16.649Z - info: 47. Start and stop ThaliNotificationServer - pass
2016-03-15T11:16:16.650Z - info: 48. Pass an empty array to ThaliNotificationServer.start - pass
2016-03-15T11:16:16.650Z - info: 49. Pass a string to ThaliNotificationServer.start - pass
2016-03-15T11:16:16.651Z - info: 50. Pass an empty parameter to ThaliNotificationServer.start - pass
2016-03-15T11:16:16.651Z - info: 51. Make an HTTP request to /NotificationBeacons - pass
2016-03-15T11:16:16.652Z - info: 52. Make an HTTP request to /NotificationBeacons (no keys) - pass
2016-03-15T11:16:16.652Z - info: 53. Make an HTTP request to /NotificationBeacons before calling start - pass
2016-03-15T11:16:16.653Z - info: 54. #testThaliPeerAction - test getters - pass
2016-03-15T11:16:16.653Z - info: 55. #testThaliPeerAction - start and kill - pass
2016-03-15T11:16:16.654Z - info: 56. #testThaliPeerAction - double start - pass

2016-03-15T11:16:16.655Z - info: 57. #testThaliPeerAction - start after kill - pass
2016-03-15T11:16:16.655Z - info: 58. #testThaliPeerAction - make sure ids are unique - pass

2016-03-15T11:16:16.656Z - info: 59. Test PeerConnectionInformation basics - pass

2016-03-15T11:16:16.661Z - info: 60. Test PeerDictionary basic functionality - pass

2016-03-15T11:16:16.662Z - info: 61. Test PeerDictionary with multiple entries. - pass

2016-03-15T11:16:16.662Z - info: 62. RESOLVED entries are removed before WAITING state entry. - pass
2016-03-15T11:16:16.663Z - info: 63. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass

2016-03-15T11:16:16.664Z - info: 64. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass

2016-03-15T11:16:16.665Z - info: 65. #ThaliPeerPoolInterface - bad enqueues - pass
2016-03-15T11:16:16.666Z - info: 66. #ThaliPeerPoolInterface - do not allow same object type - pass

2016-03-15T11:16:16.666Z - info: 67. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass

2016-03-15T11:16:16.667Z - info: 68. compareBufferArrays - pass

2016-03-15T11:16:16.668Z - info: 69. Call start twice and get error - pass

2016-03-15T11:16:16.669Z - info: 70. Start and make sure it runs - pass

2016-03-15T11:16:16.670Z - info: 71. Make sure getTimeWhenRun is right after start - pass
2016-03-15T11:16:16.671Z - info: 72. Make sure getTimeWhenRun is -1 after function is called - pass

2016-03-15T11:16:16.671Z - info: 73. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass

2016-03-15T11:16:16.672Z - info: 74. Test TransientState - pass

2016-03-15T11:16:16.673Z - info: 75. No peers and empty database - pass

2016-03-15T11:16:16.674Z - info: 76. One peer and empty DB - pass
2016-03-15T11:16:16.675Z - info: 77. One peer with _Local set behind current seq - pass

2016-03-15T11:16:16.675Z - info: 78. One peer with _Local set equal to current seq - pass

2016-03-15T11:16:16.676Z - info: 79. One peer with _Local set ahead of current seq (and no this should not happen) - pass

2016-03-15T11:16:16.677Z - info: 80. Three peers, one not in DB, one behind and one ahead - pass

2016-03-15T11:16:16.678Z - info: 81. More than maximum peers, make sure we only send maximum allowed - pass
2016-03-15T11:16:16.679Z - info: 82. two peers with empty DB, update the doc - pass

2016-03-15T11:16:16.680Z - info: 83. add doc and make sure tokens refresh when they expire - pass

2016-03-15T11:16:16.680Z - info: 84. start and stop and start and stop - pass

2016-03-15T11:16:16.681Z - info: 85. two identical starts in a row - pass

2016-03-15T11:16:16.682Z - info: 86. two different starts in a row - pass
2016-03-15T11:16:16.683Z - info: 87. two stops and a start and two stops - pass

2016-03-15T11:16:16.684Z - info: 88. we properly enqueue requests so no then needed - pass

2016-03-15T11:16:16.685Z - info: 89. test calculateSeqPointKeyId - pass

2016-03-15T11:16:16.685Z - info: 90. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass

2016-03-15T11:16:16.686Z - info: 91. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass
2016-03-15T11:16:16.687Z - info: 92. messages with invalid location or USN should be ignored - pass

2016-03-15T11:16:16.688Z - info: 93. verify that Thali-specific messages are filtered correctly - pass

2016-03-15T11:16:16.689Z - info: 94. #startListeningForAdvertisements should fail if start not called - pass

2016-03-15T11:16:16.690Z - info: 95. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-15T11:16:16.691Z - info: 96. #start should fail if called twice in a row - pass

2016-03-15T11:16:16.691Z - info: 97. should not be started after stop is called - pass

2016-03-15T11:16:16.692Z - info: 98. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass

2016-03-15T11:16:16.693Z - info: 99. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass
2016-03-15T11:16:16.694Z - info: 100. #startUpdateAdvertisingAndListening should start hosting given router object - pass

2016-03-15T11:16:16.695Z - info: 101. #stop can be called multiple times in a row - pass

2016-03-15T11:16:16.695Z - info: 102. #startListeningForAdvertisements can be called multiple times in a row - pass

2016-03-15T11:16:16.696Z - info: 103. #stopListeningForAdvertisements can be called multiple times in a row - pass
2016-03-15T11:16:16.697Z - info: 104. #stopAdvertisingAndListening can be called multiple times in a row - pass

2016-03-15T11:16:16.698Z - info: 105. functions are run from a queue in the right order - pass

2016-03-15T11:16:16.699Z - info: 106. #ThaliPeerPoolDefault - single action - pass

2016-03-15T11:16:16.699Z - info: 107. #ThaliPeerPoolDefault - multiple actions - pass
2016-03-15T11:16:16.700Z - info: 

-== END ==-

2016-03-15T11:16:16.712Z - info: Test run on ios complete

2016-03-15T11:16:16.713Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-15T11:16:16.715Z - info: PLATFORM: ios

2016-03-15T11:16:16.716Z - info: RESULT: PASS

2016-03-15T11:16:16.717Z - info: 107 of 107 tests completed

2016-03-15T11:16:16.718Z - info: 107/107 passed (0 failures)

2016-03-15T11:16:16.719Z - info: --- Test Details ---



2016-03-15T11:16:16.720Z - info: 1. calling createNativeListener directly rejects - pass

2016-03-15T11:16:16.721Z - info: 2. emits incomingConnectionState - pass
2016-03-15T11:16:16.722Z - info: 3. emits routerPortConnectionFailed - pass

2016-03-15T11:16:16.723Z - info: 4. native server connections all up - pass

2016-03-15T11:16:16.724Z - info: 5. native server - closing incoming stream cleans outgoing socket - pass

2016-03-15T11:16:16.724Z - info: 6. native server - closing incoming connection cleans outgoing socket - pass
2016-03-15T11:16:16.725Z - info: 7. native server - closing outgoing socket cleans associated mux stream - pass

2016-03-15T11:16:16.726Z - info: 8. native server - closing the whole server cleans everything up - pass

2016-03-15T11:16:16.727Z - info: 9. native server - we can get a ton of connections and data through and still clean up the server completely - pass

2016-03-15T11:16:16.728Z - info: 10. native server - simulate mux failure, make sure everything is cleaned up - pass

2016-03-15T11:16:16.729Z - info: 11. native server - timing out the incoming connection cleans everything up - pass
2016-03-15T11:16:16.729Z - info: 12. closeAll can close even when connections open - pass

2016-03-15T11:16:16.730Z - info: 13. closeAll with promise - pass

2016-03-15T11:16:16.731Z - info: 14. multiplex can send data - pass
2016-03-15T11:16:16.732Z - info: 15. enqueue and run in order - pass

2016-03-15T11:16:16.732Z - info: 16. enqueueAtTop and run backwards - pass

2016-03-15T11:16:16.733Z - info: 17. mix enqueue and enqueueAtTop - pass
2016-03-15T11:16:16.734Z - info: 18. queues handled independently - pass

2016-03-15T11:16:16.735Z - info: 19. basic - pass

2016-03-15T11:16:16.736Z - info: 20. another - pass

2016-03-15T11:16:16.737Z - info: 21. #startListeningForAdvertisements should fail if start not called - pass

2016-03-15T11:16:16.737Z - info: 22. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-15T11:16:16.738Z - info: 23. should be able to call #stopListeningForAdvertisements many times - pass

2016-03-15T11:16:16.739Z - info: 24. should be able to call #startListeningForAdvertisements many times - pass

2016-03-15T11:16:16.740Z - info: 25. should be able to call #startUpdateAdvertisingAndListening many times - pass

2016-03-15T11:16:16.741Z - info: 26. should be able to call #stopAdvertisingAndListening many times - pass
2016-03-15T11:16:16.741Z - info: 27. #start should fail if called twice in a row - pass

2016-03-15T11:16:16.742Z - info: 28. does not emit duplicate discoveryAdvertisingStateUpdate - pass

2016-03-15T11:16:16.744Z - info: 29. does not send duplicate availability changes - pass

2016-03-15T11:16:16.745Z - info: 30. can get the network status - pass

2016-03-15T11:16:16.746Z - info: 31. wifi peer is marked unavailable if announcements stop - pass

2016-03-15T11:16:16.754Z - info: 32. can get the network status before starting - pass

2016-03-15T11:16:16.754Z - info: 33. #generatePreambleAndBeacons bad args - pass
2016-03-15T11:16:16.755Z - info: 34. #generatePreambleAndBeacons empty keys to notify - pass

2016-03-15T11:16:16.756Z - info: 35. #generatePreambleAndBeacons multiple keys to notify - pass

2016-03-15T11:16:16.757Z - info: 36. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass

2016-03-15T11:16:16.758Z - info: 37. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass
2016-03-15T11:16:16.759Z - info: 38. #parseBeacons expiration out of range lower - pass

2016-03-15T11:16:16.759Z - info: 39. #parseBeacons expiration out of range lower - pass

2016-03-15T11:16:16.760Z - info: 40. #parseBeacons no beacons returns null - pass

2016-03-15T11:16:16.761Z - info: 41. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass

2016-03-15T11:16:16.762Z - info: 42. #parseBeacons addressBookCallback fails decrypt - pass

2016-03-15T11:16:16.794Z - info: 43. #parseBeacons addressBookCallback returns no matches - pass

2016-03-15T11:16:16.795Z - info: 44. #parseBeacons addressBookCallback returns spurious match - pass

2016-03-15T11:16:16.796Z - info: 45. #parseBeacons addressBookCallback returns public key - pass
2016-03-15T11:16:16.797Z - info: 46. #parseBeacons with beacons both for and not for the user - pass

2016-03-15T11:16:16.798Z - info: 47. Start and stop ThaliNotificationServer - pass

2016-03-15T11:16:16.799Z - info: 48. Pass an empty array to ThaliNotificationServer.start - pass

2016-03-15T11:16:16.799Z - info: 49. Pass a string to ThaliNotificationServer.start - pass
2016-03-15T11:16:16.800Z - info: 50. Pass an empty parameter to ThaliNotificationServer.start - pass

2016-03-15T11:16:16.801Z - info: 51. Make an HTTP request to /NotificationBeacons - pass

2016-03-15T11:16:16.802Z - info: 52. Make an HTTP request to /NotificationBeacons (no keys) - pass

2016-03-15T11:16:16.802Z - info: 53. Make an HTTP request to /NotificationBeacons before calling start - pass
2016-03-15T11:16:16.803Z - info: 54. #testThaliPeerAction - test getters - pass

2016-03-15T11:16:16.804Z - info: 55. #testThaliPeerAction - start and kill - pass

2016-03-15T11:16:16.805Z - info: 56. #testThaliPeerAction - double start - pass
2016-03-15T11:16:16.805Z - info: 57. #testThaliPeerAction - start after kill - pass

2016-03-15T11:16:16.806Z - info: 58. #testThaliPeerAction - make sure ids are unique - pass

2016-03-15T11:16:16.807Z - info: 59. Test PeerConnectionInformation basics - pass

2016-03-15T11:16:16.808Z - info: 60. Test PeerDictionary basic functionality - pass
2016-03-15T11:16:16.809Z - info: 61. Test PeerDictionary with multiple entries. - pass

2016-03-15T11:16:16.809Z - info: 62. RESOLVED entries are removed before WAITING state entry. - pass

2016-03-15T11:16:16.810Z - info: 63. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass

2016-03-15T11:16:16.811Z - info: 64. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass
2016-03-15T11:16:16.812Z - info: 65. #ThaliPeerPoolInterface - bad enqueues - pass

2016-03-15T11:16:16.813Z - info: 66. #ThaliPeerPoolInterface - do not allow same object type - pass

2016-03-15T11:16:16.813Z - info: 67. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass

2016-03-15T11:16:16.814Z - info: 68. compareBufferArrays - pass
2016-03-15T11:16:16.815Z - info: 69. Call start twice and get error - pass

2016-03-15T11:16:16.816Z - info: 70. Start and make sure it runs - pass

2016-03-15T11:16:16.816Z - info: 71. Make sure getTimeWhenRun is right after start - pass
2016-03-15T11:16:16.817Z - info: 72. Make sure getTimeWhenRun is -1 after function is called - pass

2016-03-15T11:16:16.818Z - info: 73. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass

2016-03-15T11:16:16.819Z - info: 74. Test TransientState - pass

2016-03-15T11:16:16.820Z - info: 75. No peers and empty database - pass
2016-03-15T11:16:16.820Z - info: 76. One peer and empty DB - pass

2016-03-15T11:16:16.821Z - info: 77. One peer with _Local set behind current seq - pass

2016-03-15T11:16:16.822Z - info: 78. One peer with _Local set equal to current seq - pass
2016-03-15T11:16:16.823Z - info: 79. One peer with _Local set ahead of current seq (and no this should not happen) - pass

2016-03-15T11:16:16.823Z - info: 80. Three peers, one not in DB, one behind and one ahead - pass

2016-03-15T11:16:16.824Z - info: 81. More than maximum peers, make sure we only send maximum allowed - pass

2016-03-15T11:16:16.825Z - info: 82. two peers with empty DB, update the doc - pass
2016-03-15T11:16:16.826Z - info: 83. add doc and make sure tokens refresh when they expire - pass

2016-03-15T11:16:16.826Z - info: 84. start and stop and start and stop - pass

2016-03-15T11:16:16.827Z - info: 85. two identical starts in a row - pass
2016-03-15T11:16:16.828Z - info: 86. two different starts in a row - pass

2016-03-15T11:16:16.829Z - info: 87. two stops and a start and two stops - pass

2016-03-15T11:16:16.830Z - info: 88. we properly enqueue requests so no then needed - pass
2016-03-15T11:16:16.830Z - info: 89. test calculateSeqPointKeyId - pass

2016-03-15T11:16:16.831Z - info: 90. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass

2016-03-15T11:16:16.832Z - info: 91. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-03-15T11:16:16.832Z - info: 92. messages with invalid location or USN should be ignored - pass
2016-03-15T11:16:16.833Z - info: 93. verify that Thali-specific messages are filtered correctly - pass

2016-03-15T11:16:16.834Z - info: 94. #startListeningForAdvertisements should fail if start not called - pass

2016-03-15T11:16:16.835Z - info: 95. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-15T11:16:16.836Z - info: 96. #start should fail if called twice in a row - pass
2016-03-15T11:16:16.836Z - info: 97. should not be started after stop is called - pass
2016-03-15T11:16:16.837Z - info: 98. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass
2016-03-15T11:16:16.837Z - info: 99. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass
2016-03-15T11:16:16.838Z - info: 100. #startUpdateAdvertisingAndListening should start hosting given router object - pass
2016-03-15T11:16:16.839Z - info: 101. #stop can be called multiple times in a row - pass

2016-03-15T11:16:16.839Z - info: 102. #startListeningForAdvertisements can be called multiple times in a row - pass
2016-03-15T11:16:16.840Z - info: 103. #stopListeningForAdvertisements can be called multiple times in a row - pass
2016-03-15T11:16:16.840Z - info: 104. #stopAdvertisingAndListening can be called multiple times in a row - pass
2016-03-15T11:16:16.841Z - info: 105. functions are run from a queue in the right order - pass
2016-03-15T11:16:16.841Z - info: 106. #ThaliPeerPoolDefault - single action - pass
2016-03-15T11:16:16.842Z - info: 107. #ThaliPeerPoolDefault - multiple actions - pass
2016-03-15T11:16:16.842Z - info: 

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
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62885377aa56850_Fix_to_issue__622__Network_events_are_not_always_fired_on_Android_tompaana/thali01_samsung-SM-A500FU.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/62885377aa56850_Fix_to_issue__622__Network_events_are_not_always_fired_on_Android_tompaana/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on ZX1C223JKW 
Android task is completed. [SUCCESS]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/62885377aa56850_Fix_to_issue__622__Network_events_are_not_always_fired_on_Android_tompaana/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Android task is completed. [SUCCESS]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/62885377aa56850_Fix_to_issue__622__Network_events_are_not_always_fired_on_Android_tompaana/thali05_LGE-LG-H815.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62885377aa56850_Fix_to_issue__622__Network_events_are_not_always_fired_on_Android_tompaana/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/62885377aa56850_Fix_to_issue__622__Network_events_are_not_always_fired_on_Android_tompaana/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:0 
child process exited with code 0 on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62885377aa56850_Fix_to_issue__622__Network_events_are_not_always_fired_on_Android_tompaana/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:0 
child process exited with code 0 on device 4325e43f 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62885377aa56850_Fix_to_issue__622__Network_events_are_not_always_fired_on_Android_tompaana/thali08_samsung-SM-A300FU.md)




###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/62885377aa56850_Fix_to_issue__622__Network_events_are_not_always_fired_on_Android_tompaana/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/62885377aa56850_Fix_to_issue__622__Network_events_are_not_always_fired_on_Android_tompaana/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/62885377aa56850_Fix_to_issue__622__Network_events_are_not_always_fired_on_Android_tompaana/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/62885377aa56850_Fix_to_issue__622__Network_events_are_not_always_fired_on_Android_tompaana/iOS_Iphone5s-1.md)



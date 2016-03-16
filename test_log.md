#### Test 63008475d624ed8 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":8}}
2016-03-16T11:23:38.645Z - info: listening on *:3000

2016-03-16T11:23:39.737Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:0

2016-03-16T11:23:40.955Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:1

2016-03-16T11:23:40.958Z - info: Required number of ios devices presented (2)

2016-03-16T11:23:40.962Z - info: Starting unit test run for platform: ios

2016-03-16T11:23:40.989Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:2

2016-03-16T11:23:40.990Z - info: Discarding surplus device: Apple-IpadAir2-1

2016-03-16T11:23:41.626Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-16T11:23:41.926Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:3

2016-03-16T11:23:41.927Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-16T11:23:42.015Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:4

2016-03-16T11:23:42.022Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:5

2016-03-16T11:23:42.023Z - info: Required number of android devices presented (2)

2016-03-16T11:23:42.024Z - info: Starting unit test run for platform: android

2016-03-16T11:23:42.295Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-16T11:23:42.546Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-16T11:23:42.722Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-16T11:23:43.001Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-16T11:23:43.118Z - info: Running on ios test: 4. native server connections all up

2016-03-16T11:23:43.358Z - debug: Device presented: samsung-SM-A500FU (android) unittest socket:6

2016-03-16T11:23:43.359Z - info: Discarding surplus device: samsung-SM-A500FU

2016-03-16T11:23:43.379Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-16T11:23:43.584Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-16T11:23:43.660Z - debug: Socket disconnected: transport close 2 (Apple-IpadAir2-1)

2016-03-16T11:23:43.903Z - info: Running on android test: 4. native server connections all up

2016-03-16T11:23:44.169Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-16T11:23:44.632Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-16T11:23:44.785Z - debug: Socket disconnected: transport close 3 (Apple-Iphone5s-1)

2016-03-16T11:23:44.824Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-16T11:23:45.256Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-16T11:23:45.366Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-16T11:23:45.679Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-16T11:23:45.820Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-16T11:23:46.133Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-16T11:23:46.654Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-16T11:23:46.822Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-16T11:23:47.262Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-16T11:23:47.543Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-16T11:23:47.706Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-16T11:23:47.942Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-16T11:23:48.043Z - info: Running on ios test: 13. closeAll with promise

2016-03-16T11:23:48.340Z - info: Running on ios test: 14. multiplex can send data

2016-03-16T11:23:48.450Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-16T11:23:48.742Z - info: Running on ios test: 15. enqueue and run in order

2016-03-16T11:23:48.796Z - info: Running on android test: 13. closeAll with promise

2016-03-16T11:23:49.045Z - info: Running on android test: 14. multiplex can send data

2016-03-16T11:23:49.218Z - info: Running on ios test: 16. enqueueAtTop and run backwards

2016-03-16T11:23:49.352Z - info: Running on android test: 15. enqueue and run in order

2016-03-16T11:23:49.513Z - info: Running on ios test: 17. mix enqueue and enqueueAtTop

2016-03-16T11:23:49.941Z - info: Running on ios test: 18. queues handled independently

2016-03-16T11:23:49.996Z - info: Running on android test: 16. enqueueAtTop and run backwards

2016-03-16T11:23:50.289Z - info: Running on ios test: 19. basic

2016-03-16T11:23:50.352Z - info: Running on android test: 17. mix enqueue and enqueueAtTop

2016-03-16T11:23:50.706Z - info: Running on ios test: 20. another

2016-03-16T11:23:50.913Z - info: Running on android test: 18. queues handled independently

2016-03-16T11:23:51.134Z - info: Running on ios test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-16T11:23:51.357Z - info: Running on android test: 19. basic

2016-03-16T11:23:51.628Z - info: Running on ios test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-16T11:23:51.778Z - info: Running on android test: 20. another

2016-03-16T11:23:52.106Z - info: Running on ios test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-16T11:23:52.192Z - info: Running on android test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-16T11:23:52.505Z - info: Running on ios test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-16T11:23:52.596Z - info: Running on android test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-16T11:23:52.861Z - info: Running on ios test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-16T11:23:52.945Z - info: Running on android test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-16T11:23:53.262Z - info: Running on ios test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-16T11:23:53.333Z - info: Running on android test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-16T11:23:53.564Z - info: Running on ios test: 27. #start should fail if called twice in a row

2016-03-16T11:23:53.700Z - info: Running on android test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-16T11:23:53.907Z - info: Running on ios test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-16T11:23:54.081Z - info: Running on android test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-16T11:23:54.216Z - info: Running on ios test: 29. does not send duplicate availability changes

2016-03-16T11:23:54.444Z - info: Running on android test: 27. #start should fail if called twice in a row

2016-03-16T11:23:54.533Z - info: Running on ios test: 30. can get the network status

2016-03-16T11:23:54.792Z - info: Running on android test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-16T11:23:54.853Z - info: Running on ios test: 31. wifi peer is marked unavailable if announcements stop

2016-03-16T11:23:55.131Z - info: Running on android test: 29. does not send duplicate availability changes

2016-03-16T11:23:55.419Z - info: Running on android test: 30. can get the network status

2016-03-16T11:23:55.666Z - info: Running on android test: 31. wifi peer is marked unavailable if announcements stop

2016-03-16T11:23:56.196Z - info: Running on ios test: 32. can get the network status before starting

2016-03-16T11:23:56.551Z - info: Running on ios test: 33. #generatePreambleAndBeacons bad args

2016-03-16T11:23:56.880Z - info: Running on ios test: 34. #generatePreambleAndBeacons empty keys to notify

2016-03-16T11:23:57.169Z - info: Running on android test: 32. can get the network status before starting

2016-03-16T11:23:57.273Z - info: Running on ios test: 35. #generatePreambleAndBeacons multiple keys to notify

2016-03-16T11:23:57.471Z - info: Running on android test: 33. #generatePreambleAndBeacons bad args

2016-03-16T11:23:57.686Z - info: Running on ios test: 36. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-16T11:23:57.719Z - info: Running on android test: 34. #generatePreambleAndBeacons empty keys to notify

2016-03-16T11:23:57.923Z - info: Running on ios test: 37. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-16T11:23:58.061Z - info: Running on android test: 35. #generatePreambleAndBeacons multiple keys to notify

2016-03-16T11:23:58.243Z - info: Running on ios test: 38. #parseBeacons expiration out of range lower

2016-03-16T11:23:58.444Z - info: Running on android test: 36. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-16T11:23:58.509Z - info: Running on ios test: 39. #parseBeacons expiration out of range lower

2016-03-16T11:23:58.843Z - info: Running on android test: 37. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-16T11:23:58.914Z - info: Running on ios test: 40. #parseBeacons no beacons returns null

2016-03-16T11:23:59.147Z - info: Running on android test: 38. #parseBeacons expiration out of range lower

2016-03-16T11:23:59.204Z - info: Running on ios test: 41. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-16T11:23:59.384Z - info: Running on android test: 39. #parseBeacons expiration out of range lower

2016-03-16T11:23:59.428Z - info: Running on ios test: 42. #parseBeacons addressBookCallback fails decrypt

2016-03-16T11:23:59.725Z - info: Running on android test: 40. #parseBeacons no beacons returns null

2016-03-16T11:23:59.804Z - info: Running on ios test: 43. #parseBeacons addressBookCallback returns no matches

2016-03-16T11:24:00.058Z - info: Running on android test: 41. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-16T11:24:00.222Z - info: Running on ios test: 44. #parseBeacons addressBookCallback returns spurious match

2016-03-16T11:24:00.330Z - info: Running on android test: 42. #parseBeacons addressBookCallback fails decrypt

2016-03-16T11:24:00.620Z - info: Running on ios test: 45. #parseBeacons addressBookCallback returns public key

2016-03-16T11:24:00.820Z - info: Running on android test: 43. #parseBeacons addressBookCallback returns no matches

2016-03-16T11:24:01.065Z - info: Running on ios test: 46. #parseBeacons with beacons both for and not for the user

2016-03-16T11:24:01.300Z - info: Running on android test: 44. #parseBeacons addressBookCallback returns spurious match

2016-03-16T11:24:01.392Z - info: Running on ios test: 47. Start and stop ThaliNotificationServer

2016-03-16T11:24:01.760Z - info: Running on android test: 45. #parseBeacons addressBookCallback returns public key

2016-03-16T11:24:01.766Z - info: Running on ios test: 48. Pass an empty array to ThaliNotificationServer.start

2016-03-16T11:24:02.178Z - info: Running on ios test: 49. Pass a string to ThaliNotificationServer.start

2016-03-16T11:24:02.228Z - info: Running on android test: 46. #parseBeacons with beacons both for and not for the user

2016-03-16T11:24:02.533Z - info: Running on ios test: 50. Pass an empty parameter to ThaliNotificationServer.start

2016-03-16T11:24:02.654Z - info: Running on android test: 47. Start and stop ThaliNotificationServer

2016-03-16T11:24:02.849Z - info: Running on ios test: 51. Make an HTTP request to /NotificationBeacons

2016-03-16T11:24:03.123Z - info: Running on android test: 48. Pass an empty array to ThaliNotificationServer.start

2016-03-16T11:24:03.542Z - info: Running on android test: 49. Pass a string to ThaliNotificationServer.start

2016-03-16T11:24:03.898Z - info: Running on android test: 50. Pass an empty parameter to ThaliNotificationServer.start

2016-03-16T11:24:04.224Z - info: Running on android test: 51. Make an HTTP request to /NotificationBeacons

2016-03-16T11:24:04.496Z - info: Running on ios test: 52. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-16T11:24:04.882Z - info: Running on android test: 52. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-16T11:24:05.109Z - info: Running on ios test: 53. Make an HTTP request to /NotificationBeacons before calling start

2016-03-16T11:24:05.333Z - info: Running on android test: 53. Make an HTTP request to /NotificationBeacons before calling start

2016-03-16T11:24:05.656Z - info: Running on ios test: 54. #testThaliPeerAction - test getters

2016-03-16T11:24:05.879Z - info: Running on android test: 54. #testThaliPeerAction - test getters

2016-03-16T11:24:06.105Z - info: Running on ios test: 55. #testThaliPeerAction - start and kill

2016-03-16T11:24:06.344Z - info: Running on android test: 55. #testThaliPeerAction - start and kill

2016-03-16T11:24:06.626Z - info: Running on ios test: 56. #testThaliPeerAction - double start

2016-03-16T11:24:06.742Z - info: Running on android test: 56. #testThaliPeerAction - double start

2016-03-16T11:24:06.981Z - info: Running on ios test: 57. #testThaliPeerAction - start after kill

2016-03-16T11:24:07.145Z - info: Running on android test: 57. #testThaliPeerAction - start after kill

2016-03-16T11:24:07.405Z - info: Running on ios test: 58. #testThaliPeerAction - make sure ids are unique

2016-03-16T11:24:07.482Z - info: Running on android test: 58. #testThaliPeerAction - make sure ids are unique

2016-03-16T11:24:07.746Z - info: Running on android test: 59. Test PeerConnectionInformation basics

2016-03-16T11:24:07.749Z - info: Running on ios test: 59. Test PeerConnectionInformation basics

2016-03-16T11:24:08.086Z - info: Running on android test: 60. Test PeerDictionary basic functionality

2016-03-16T11:24:08.089Z - info: Running on ios test: 60. Test PeerDictionary basic functionality

2016-03-16T11:24:08.465Z - info: Running on ios test: 61. Test PeerDictionary with multiple entries.

2016-03-16T11:24:08.539Z - info: Running on android test: 61. Test PeerDictionary with multiple entries.

2016-03-16T11:24:10.113Z - info: Running on android test: 62. RESOLVED entries are removed before WAITING state entry.

2016-03-16T11:24:11.117Z - info: Running on android test: 63. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-16T11:24:12.278Z - info: Running on android test: 64. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-16T11:24:13.385Z - info: Running on android test: 65. #ThaliPeerPoolInterface - bad enqueues

2016-03-16T11:24:13.734Z - info: Running on android test: 66. #ThaliPeerPoolInterface - do not allow same object type

2016-03-16T11:24:14.028Z - info: Running on android test: 67. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-16T11:24:14.359Z - info: Running on android test: 68. compareBufferArrays

2016-03-16T11:24:14.769Z - info: Running on android test: 69. Call start twice and get error

2016-03-16T11:24:15.237Z - info: Running on android test: 70. Start and make sure it runs

2016-03-16T11:24:15.583Z - info: Running on android test: 71. Make sure getTimeWhenRun is right after start

2016-03-16T11:24:16.016Z - info: Running on android test: 72. Make sure getTimeWhenRun is -1 after function is called

2016-03-16T11:24:16.065Z - info: Running on ios test: 62. RESOLVED entries are removed before WAITING state entry.

2016-03-16T11:24:16.411Z - info: Running on android test: 73. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-16T11:24:16.783Z - info: Running on android test: 74. Test TransientState

2016-03-16T11:24:17.171Z - info: Running on android test: 75. No peers and empty database

2016-03-16T11:24:17.582Z - info: Running on ios test: 63. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-16T11:24:17.838Z - info: Running on android test: 76. One peer and empty DB

2016-03-16T11:24:18.384Z - info: Running on android test: 77. One peer with _Local set behind current seq

2016-03-16T11:24:19.050Z - info: Running on ios test: 64. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-16T11:24:19.128Z - info: Running on android test: 78. One peer with _Local set equal to current seq

2016-03-16T11:24:19.716Z - info: Running on android test: 79. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-16T11:24:20.287Z - info: Running on android test: 80. Three peers, one not in DB, one behind and one ahead

2016-03-16T11:24:20.349Z - info: Running on ios test: 65. #ThaliPeerPoolInterface - bad enqueues

2016-03-16T11:24:20.710Z - info: Running on ios test: 66. #ThaliPeerPoolInterface - do not allow same object type

2016-03-16T11:24:21.041Z - info: Running on android test: 81. More than maximum peers, make sure we only send maximum allowed

2016-03-16T11:24:21.157Z - info: Running on ios test: 67. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-16T11:24:21.646Z - info: Running on ios test: 68. compareBufferArrays

2016-03-16T11:24:22.093Z - info: Running on ios test: 69. Call start twice and get error

2016-03-16T11:24:22.234Z - info: Running on android test: 82. two peers with empty DB, update the doc

2016-03-16T11:24:22.586Z - info: Running on ios test: 70. Start and make sure it runs

2016-03-16T11:24:22.943Z - info: Running on android test: 83. add doc and make sure tokens refresh when they expire

2016-03-16T11:24:22.967Z - info: Running on ios test: 71. Make sure getTimeWhenRun is right after start

2016-03-16T11:24:23.480Z - info: Running on ios test: 72. Make sure getTimeWhenRun is -1 after function is called

2016-03-16T11:24:23.773Z - info: Running on ios test: 73. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-16T11:24:24.001Z - info: Running on android test: 84. start and stop and start and stop

2016-03-16T11:24:24.071Z - info: Running on ios test: 74. Test TransientState

2016-03-16T11:24:24.437Z - info: Running on ios test: 75. No peers and empty database

2016-03-16T11:24:24.520Z - info: Running on android test: 85. two identical starts in a row

2016-03-16T11:24:24.936Z - info: Running on ios test: 76. One peer and empty DB

2016-03-16T11:24:25.066Z - info: Running on android test: 86. two different starts in a row

2016-03-16T11:24:25.603Z - info: Running on ios test: 77. One peer with _Local set behind current seq

2016-03-16T11:24:25.611Z - info: Running on android test: 87. two stops and a start and two stops

2016-03-16T11:24:26.408Z - info: Running on android test: 88. we properly enqueue requests so no then needed

2016-03-16T11:24:26.432Z - info: Running on ios test: 78. One peer with _Local set equal to current seq

2016-03-16T11:24:26.981Z - info: Running on android test: 89. test calculateSeqPointKeyId

2016-03-16T11:24:27.119Z - info: Running on ios test: 79. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-16T11:24:27.401Z - info: Running on android test: 90. can create servers manager

2016-03-16T11:24:27.742Z - info: Running on ios test: 80. Three peers, one not in DB, one behind and one ahead

2016-03-16T11:24:27.783Z - info: Running on android test: 91. calling stop without start causes error

2016-03-16T11:24:28.124Z - info: Running on android test: 92. can start/stop servers manager

2016-03-16T11:24:28.574Z - info: Running on android test: 93. starting twice resolves with listening port

2016-03-16T11:24:28.861Z - info: Running on ios test: 81. More than maximum peers, make sure we only send maximum allowed

2016-03-16T11:24:28.896Z - info: Running on android test: 94. terminateIncomingConnection will terminate a connection

2016-03-16T11:24:29.266Z - info: Running on android test: 95. terminate an Outgoing connection will terminate the server

2016-03-16T11:24:29.592Z - info: Running on android test: 96. terminate an Outgoing connection with wrong arguments is not harmful

2016-03-16T11:24:29.951Z - info: Running on android test: 97. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-16T11:24:30.233Z - info: Running on ios test: 82. two peers with empty DB, update the doc

2016-03-16T11:24:30.325Z - info: Running on android test: 98. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-16T11:24:30.640Z - info: Running on android test: 99. messages with invalid location or USN should be ignored

2016-03-16T11:24:31.019Z - info: Running on android test: 100. verify that Thali-specific messages are filtered correctly

2016-03-16T11:24:31.085Z - info: Running on ios test: 83. add doc and make sure tokens refresh when they expire

2016-03-16T11:24:31.357Z - info: Running on android test: 101. #startListeningForAdvertisements should fail if start not called

2016-03-16T11:24:31.617Z - info: Running on android test: 102. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-16T11:24:31.875Z - info: Running on android test: 103. #start should fail if called twice in a row

2016-03-16T11:24:32.053Z - info: Running on ios test: 84. start and stop and start and stop

2016-03-16T11:24:32.235Z - info: Running on android test: 104. should not be started after stop is called

2016-03-16T11:24:32.592Z - info: Running on android test: 105. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-16T11:24:32.723Z - info: Running on ios test: 85. two identical starts in a row

2016-03-16T11:24:32.922Z - info: Running on android test: 106. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-16T11:24:33.456Z - info: Running on ios test: 86. two different starts in a row

2016-03-16T11:24:33.465Z - info: Running on android test: 107. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-16T11:24:33.926Z - info: Running on android test: 108. #stop can be called multiple times in a row

2016-03-16T11:24:34.288Z - info: Running on android test: 109. #startListeningForAdvertisements can be called multiple times in a row

2016-03-16T11:24:34.376Z - info: Running on ios test: 87. two stops and a start and two stops

2016-03-16T11:24:34.684Z - info: Running on android test: 110. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-16T11:24:34.991Z - info: Running on ios test: 88. we properly enqueue requests so no then needed

2016-03-16T11:24:35.034Z - info: Running on android test: 111. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-16T11:24:35.385Z - info: Running on android test: 112. functions are run from a queue in the right order

2016-03-16T11:24:35.529Z - info: Running on ios test: 89. test calculateSeqPointKeyId

2016-03-16T11:24:35.696Z - info: Running on android test: 113. #ThaliPeerPoolDefault - single action

2016-03-16T11:24:35.816Z - info: Running on ios test: 90. can create servers manager

2016-03-16T11:24:36.011Z - info: Running on android test: 114. #ThaliPeerPoolDefault - multiple actions

2016-03-16T11:24:36.084Z - info: Running on ios test: 91. calling stop without start causes error

2016-03-16T11:24:36.361Z - info: Test run on android complete

2016-03-16T11:24:36.363Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-16T11:24:36.365Z - info: PLATFORM: android

2016-03-16T11:24:36.366Z - info: RESULT: PASS

2016-03-16T11:24:36.367Z - info: 114 of 114 tests completed

2016-03-16T11:24:36.368Z - info: 114/114 passed (0 failures)

2016-03-16T11:24:36.369Z - info: --- Test Details ---



2016-03-16T11:24:36.370Z - info: 1. calling createNativeListener directly rejects - pass

2016-03-16T11:24:36.371Z - info: 2. emits incomingConnectionState - pass

2016-03-16T11:24:36.372Z - info: 3. emits routerPortConnectionFailed - pass
2016-03-16T11:24:36.373Z - info: 4. native server connections all up - pass

2016-03-16T11:24:36.373Z - info: 5. native server - closing incoming stream cleans outgoing socket - pass

2016-03-16T11:24:36.374Z - info: 6. native server - closing incoming connection cleans outgoing socket - pass

2016-03-16T11:24:36.375Z - info: 7. native server - closing outgoing socket cleans associated mux stream - pass

2016-03-16T11:24:36.376Z - info: 8. native server - closing the whole server cleans everything up - pass

2016-03-16T11:24:36.377Z - info: 9. native server - we can get a ton of connections and data through and still clean up the server completely - pass
2016-03-16T11:24:36.378Z - info: 10. native server - simulate mux failure, make sure everything is cleaned up - pass

2016-03-16T11:24:36.379Z - info: 11. native server - timing out the incoming connection cleans everything up - pass

2016-03-16T11:24:36.379Z - info: 12. closeAll can close even when connections open - pass

2016-03-16T11:24:36.380Z - info: 13. closeAll with promise - pass

2016-03-16T11:24:36.381Z - info: 14. multiplex can send data - pass
2016-03-16T11:24:36.382Z - info: 15. enqueue and run in order - pass

2016-03-16T11:24:36.383Z - info: 16. enqueueAtTop and run backwards - pass
2016-03-16T11:24:36.383Z - info: 17. mix enqueue and enqueueAtTop - pass
2016-03-16T11:24:36.384Z - info: 18. queues handled independently - pass
2016-03-16T11:24:36.385Z - info: 19. basic - pass

2016-03-16T11:24:36.385Z - info: 20. another - pass
2016-03-16T11:24:36.386Z - info: 21. #startListeningForAdvertisements should fail if start not called - pass

2016-03-16T11:24:36.387Z - info: 22. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-16T11:24:36.388Z - info: 23. should be able to call #stopListeningForAdvertisements many times - pass

2016-03-16T11:24:36.389Z - info: 24. should be able to call #startListeningForAdvertisements many times - pass
2016-03-16T11:24:36.389Z - info: 25. should be able to call #startUpdateAdvertisingAndListening many times - pass

2016-03-16T11:24:36.390Z - info: 26. should be able to call #stopAdvertisingAndListening many times - pass

2016-03-16T11:24:36.391Z - info: 27. #start should fail if called twice in a row - pass

2016-03-16T11:24:36.392Z - info: 28. does not emit duplicate discoveryAdvertisingStateUpdate - pass

2016-03-16T11:24:36.393Z - info: 29. does not send duplicate availability changes - pass
2016-03-16T11:24:36.393Z - info: 30. can get the network status - pass

2016-03-16T11:24:36.394Z - info: 31. wifi peer is marked unavailable if announcements stop - pass

2016-03-16T11:24:36.395Z - info: 32. can get the network status before starting - pass

2016-03-16T11:24:36.396Z - info: 33. #generatePreambleAndBeacons bad args - pass

2016-03-16T11:24:36.397Z - info: 34. #generatePreambleAndBeacons empty keys to notify - pass

2016-03-16T11:24:36.398Z - info: 35. #generatePreambleAndBeacons multiple keys to notify - pass

2016-03-16T11:24:36.399Z - info: 36. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass
2016-03-16T11:24:36.400Z - info: 37. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass

2016-03-16T11:24:36.401Z - info: 38. #parseBeacons expiration out of range lower - pass
2016-03-16T11:24:36.401Z - info: 39. #parseBeacons expiration out of range lower - pass
2016-03-16T11:24:36.402Z - info: 40. #parseBeacons no beacons returns null - pass
2016-03-16T11:24:36.402Z - info: 41. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass
2016-03-16T11:24:36.403Z - info: 42. #parseBeacons addressBookCallback fails decrypt - pass
2016-03-16T11:24:36.413Z - info: 43. #parseBeacons addressBookCallback returns no matches - pass

2016-03-16T11:24:36.414Z - info: 44. #parseBeacons addressBookCallback returns spurious match - pass

2016-03-16T11:24:36.415Z - info: 45. #parseBeacons addressBookCallback returns public key - pass

2016-03-16T11:24:36.416Z - info: 46. #parseBeacons with beacons both for and not for the user - pass
2016-03-16T11:24:36.417Z - info: 47. Start and stop ThaliNotificationServer - pass

2016-03-16T11:24:36.417Z - info: 48. Pass an empty array to ThaliNotificationServer.start - pass

2016-03-16T11:24:36.418Z - info: 49. Pass a string to ThaliNotificationServer.start - pass
2016-03-16T11:24:36.419Z - info: 50. Pass an empty parameter to ThaliNotificationServer.start - pass

2016-03-16T11:24:36.420Z - info: 51. Make an HTTP request to /NotificationBeacons - pass

2016-03-16T11:24:36.421Z - info: 52. Make an HTTP request to /NotificationBeacons (no keys) - pass

2016-03-16T11:24:36.421Z - info: 53. Make an HTTP request to /NotificationBeacons before calling start - pass
2016-03-16T11:24:36.422Z - info: 54. #testThaliPeerAction - test getters - pass

2016-03-16T11:24:36.423Z - info: 55. #testThaliPeerAction - start and kill - pass

2016-03-16T11:24:36.424Z - info: 56. #testThaliPeerAction - double start - pass

2016-03-16T11:24:36.425Z - info: 57. #testThaliPeerAction - start after kill - pass
2016-03-16T11:24:36.425Z - info: 58. #testThaliPeerAction - make sure ids are unique - pass

2016-03-16T11:24:36.426Z - info: 59. Test PeerConnectionInformation basics - pass

2016-03-16T11:24:36.427Z - info: 60. Test PeerDictionary basic functionality - pass

2016-03-16T11:24:36.428Z - info: 61. Test PeerDictionary with multiple entries. - pass
2016-03-16T11:24:36.428Z - info: 62. RESOLVED entries are removed before WAITING state entry. - pass

2016-03-16T11:24:36.429Z - info: 63. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass

2016-03-16T11:24:36.430Z - info: 64. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass

2016-03-16T11:24:36.434Z - info: 65. #ThaliPeerPoolInterface - bad enqueues - pass

2016-03-16T11:24:36.435Z - info: 66. #ThaliPeerPoolInterface - do not allow same object type - pass

2016-03-16T11:24:36.436Z - info: 67. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass
2016-03-16T11:24:36.437Z - info: 68. compareBufferArrays - pass

2016-03-16T11:24:36.438Z - info: 69. Call start twice and get error - pass

2016-03-16T11:24:36.439Z - info: 70. Start and make sure it runs - pass

2016-03-16T11:24:36.439Z - info: 71. Make sure getTimeWhenRun is right after start - pass

2016-03-16T11:24:36.440Z - info: 72. Make sure getTimeWhenRun is -1 after function is called - pass

2016-03-16T11:24:36.441Z - info: 73. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass
2016-03-16T11:24:36.442Z - info: 74. Test TransientState - pass

2016-03-16T11:24:36.443Z - info: 75. No peers and empty database - pass

2016-03-16T11:24:36.443Z - info: 76. One peer and empty DB - pass

2016-03-16T11:24:36.444Z - info: 77. One peer with _Local set behind current seq - pass

2016-03-16T11:24:36.445Z - info: 78. One peer with _Local set equal to current seq - pass
2016-03-16T11:24:36.446Z - info: 79. One peer with _Local set ahead of current seq (and no this should not happen) - pass

2016-03-16T11:24:36.447Z - info: 80. Three peers, one not in DB, one behind and one ahead - pass

2016-03-16T11:24:36.447Z - info: 81. More than maximum peers, make sure we only send maximum allowed - pass

2016-03-16T11:24:36.448Z - info: 82. two peers with empty DB, update the doc - pass
2016-03-16T11:24:36.449Z - info: 83. add doc and make sure tokens refresh when they expire - pass

2016-03-16T11:24:36.450Z - info: 84. start and stop and start and stop - pass

2016-03-16T11:24:36.450Z - info: 85. two identical starts in a row - pass

2016-03-16T11:24:36.451Z - info: 86. two different starts in a row - pass
2016-03-16T11:24:36.452Z - info: 87. two stops and a start and two stops - pass

2016-03-16T11:24:36.453Z - info: 88. we properly enqueue requests so no then needed - pass

2016-03-16T11:24:36.453Z - info: 89. test calculateSeqPointKeyId - pass

2016-03-16T11:24:36.454Z - info: 90. can create servers manager - pass

2016-03-16T11:24:36.455Z - info: 91. calling stop without start causes error - pass
2016-03-16T11:24:36.456Z - info: 92. can start/stop servers manager - pass

2016-03-16T11:24:36.457Z - info: 93. starting twice resolves with listening port - pass

2016-03-16T11:24:36.458Z - info: 94. terminateIncomingConnection will terminate a connection - pass

2016-03-16T11:24:36.458Z - info: 95. terminate an Outgoing connection will terminate the server - pass

2016-03-16T11:24:36.459Z - info: 96. terminate an Outgoing connection with wrong arguments is not harmful - pass
2016-03-16T11:24:36.460Z - info: 97. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass

2016-03-16T11:24:36.461Z - info: 98. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-03-16T11:24:36.462Z - info: 99. messages with invalid location or USN should be ignored - pass

2016-03-16T11:24:36.462Z - info: 100. verify that Thali-specific messages are filtered correctly - pass
2016-03-16T11:24:36.463Z - info: 101. #startListeningForAdvertisements should fail if start not called - pass

2016-03-16T11:24:36.464Z - info: 102. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-16T11:24:36.465Z - info: 103. #start should fail if called twice in a row - pass

2016-03-16T11:24:36.466Z - info: 104. should not be started after stop is called - pass
2016-03-16T11:24:36.466Z - info: 105. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass

2016-03-16T11:24:36.467Z - info: 106. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass

2016-03-16T11:24:36.468Z - info: 107. #startUpdateAdvertisingAndListening should start hosting given router object - pass
2016-03-16T11:24:36.469Z - info: 108. #stop can be called multiple times in a row - pass

2016-03-16T11:24:36.469Z - info: 109. #startListeningForAdvertisements can be called multiple times in a row - pass
2016-03-16T11:24:36.470Z - info: 110. #stopListeningForAdvertisements can be called multiple times in a row - pass

2016-03-16T11:24:36.471Z - info: 111. #stopAdvertisingAndListening can be called multiple times in a row - pass

2016-03-16T11:24:36.472Z - info: 112. functions are run from a queue in the right order - pass
2016-03-16T11:24:36.472Z - info: 113. #ThaliPeerPoolDefault - single action - pass

2016-03-16T11:24:36.473Z - info: 114. #ThaliPeerPoolDefault - multiple actions - pass

2016-03-16T11:24:36.474Z - info: 

-== END ==-

2016-03-16T11:24:36.487Z - info: Running on ios test: 92. can start/stop servers manager

2016-03-16T11:24:36.934Z - info: Running on ios test: 93. starting twice resolves with listening port

2016-03-16T11:24:37.282Z - info: Running on ios test: 94. terminateIncomingConnection will terminate a connection

2016-03-16T11:24:37.372Z - debug: Socket disconnected: transport close 4 (LGE-LG-H815)

2016-03-16T11:24:37.684Z - info: Running on ios test: 95. terminate an Outgoing connection will terminate the server

2016-03-16T11:24:37.979Z - debug: Socket disconnected: transport close 5 (samsung-SM-N910C)

2016-03-16T11:24:37.999Z - info: Running on ios test: 96. terminate an Outgoing connection with wrong arguments is not harmful

2016-03-16T11:24:38.370Z - info: Running on ios test: 97. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-16T11:24:38.695Z - info: Running on ios test: 98. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-16T11:24:39.084Z - info: Running on ios test: 99. messages with invalid location or USN should be ignored

2016-03-16T11:24:39.347Z - info: Running on ios test: 100. verify that Thali-specific messages are filtered correctly

2016-03-16T11:24:39.692Z - info: Running on ios test: 101. #startListeningForAdvertisements should fail if start not called

2016-03-16T11:24:40.033Z - info: Running on ios test: 102. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-16T11:24:40.416Z - info: Running on ios test: 103. #start should fail if called twice in a row

2016-03-16T11:24:40.794Z - info: Running on ios test: 104. should not be started after stop is called

2016-03-16T11:24:41.079Z - info: Running on ios test: 105. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-16T11:24:41.391Z - info: Running on ios test: 106. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-16T11:24:41.812Z - info: Running on ios test: 107. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-16T11:24:42.361Z - info: Running on ios test: 108. #stop can be called multiple times in a row

2016-03-16T11:24:42.707Z - info: Running on ios test: 109. #startListeningForAdvertisements can be called multiple times in a row

2016-03-16T11:24:43.097Z - info: Running on ios test: 110. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-16T11:24:43.579Z - info: Running on ios test: 111. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-16T11:24:43.832Z - info: Running on ios test: 112. functions are run from a queue in the right order

2016-03-16T11:24:44.092Z - info: Running on ios test: 113. #ThaliPeerPoolDefault - single action

2016-03-16T11:24:44.457Z - info: Running on ios test: 114. #ThaliPeerPoolDefault - multiple actions

2016-03-16T11:24:44.693Z - info: Test run on ios complete

2016-03-16T11:24:44.694Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-16T11:24:44.696Z - info: PLATFORM: ios

2016-03-16T11:24:44.697Z - info: RESULT: PASS

2016-03-16T11:24:44.698Z - info: 114 of 114 tests completed

2016-03-16T11:24:44.699Z - info: 114/114 passed (0 failures)

2016-03-16T11:24:44.700Z - info: --- Test Details ---


2016-03-16T11:24:44.701Z - info: 1. calling createNativeListener directly rejects - pass

2016-03-16T11:24:44.702Z - info: 2. emits incomingConnectionState - pass

2016-03-16T11:24:44.702Z - info: 3. emits routerPortConnectionFailed - pass

2016-03-16T11:24:44.704Z - info: 4. native server connections all up - pass

2016-03-16T11:24:44.705Z - info: 5. native server - closing incoming stream cleans outgoing socket - pass

2016-03-16T11:24:44.706Z - info: 6. native server - closing incoming connection cleans outgoing socket - pass

2016-03-16T11:24:44.714Z - info: 7. native server - closing outgoing socket cleans associated mux stream - pass
2016-03-16T11:24:44.714Z - info: 8. native server - closing the whole server cleans everything up - pass

2016-03-16T11:24:44.715Z - info: 9. native server - we can get a ton of connections and data through and still clean up the server completely - pass
2016-03-16T11:24:44.716Z - info: 10. native server - simulate mux failure, make sure everything is cleaned up - pass

2016-03-16T11:24:44.717Z - info: 11. native server - timing out the incoming connection cleans everything up - pass

2016-03-16T11:24:44.717Z - info: 12. closeAll can close even when connections open - pass
2016-03-16T11:24:44.718Z - info: 13. closeAll with promise - pass

2016-03-16T11:24:44.719Z - info: 14. multiplex can send data - pass

2016-03-16T11:24:44.720Z - info: 15. enqueue and run in order - pass
2016-03-16T11:24:44.721Z - info: 16. enqueueAtTop and run backwards - pass

2016-03-16T11:24:44.721Z - info: 17. mix enqueue and enqueueAtTop - pass

2016-03-16T11:24:44.753Z - info: 18. queues handled independently - pass

2016-03-16T11:24:44.754Z - info: 19. basic - pass
2016-03-16T11:24:44.755Z - info: 20. another - pass

2016-03-16T11:24:44.756Z - info: 21. #startListeningForAdvertisements should fail if start not called - pass

2016-03-16T11:24:44.757Z - info: 22. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-16T11:24:44.757Z - info: 23. should be able to call #stopListeningForAdvertisements many times - pass

2016-03-16T11:24:44.758Z - info: 24. should be able to call #startListeningForAdvertisements many times - pass
2016-03-16T11:24:44.759Z - info: 25. should be able to call #startUpdateAdvertisingAndListening many times - pass

2016-03-16T11:24:44.760Z - info: 26. should be able to call #stopAdvertisingAndListening many times - pass

2016-03-16T11:24:44.761Z - info: 27. #start should fail if called twice in a row - pass

2016-03-16T11:24:44.761Z - info: 28. does not emit duplicate discoveryAdvertisingStateUpdate - pass
2016-03-16T11:24:44.762Z - info: 29. does not send duplicate availability changes - pass

2016-03-16T11:24:44.763Z - info: 30. can get the network status - pass

2016-03-16T11:24:44.763Z - info: 31. wifi peer is marked unavailable if announcements stop - pass

2016-03-16T11:24:44.764Z - info: 32. can get the network status before starting - pass
2016-03-16T11:24:44.765Z - info: 33. #generatePreambleAndBeacons bad args - pass

2016-03-16T11:24:44.766Z - info: 34. #generatePreambleAndBeacons empty keys to notify - pass

2016-03-16T11:24:44.766Z - info: 35. #generatePreambleAndBeacons multiple keys to notify - pass
2016-03-16T11:24:44.767Z - info: 36. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass

2016-03-16T11:24:44.768Z - info: 37. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass

2016-03-16T11:24:44.769Z - info: 38. #parseBeacons expiration out of range lower - pass

2016-03-16T11:24:44.770Z - info: 39. #parseBeacons expiration out of range lower - pass
2016-03-16T11:24:44.770Z - info: 40. #parseBeacons no beacons returns null - pass

2016-03-16T11:24:44.771Z - info: 41. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass

2016-03-16T11:24:44.772Z - info: 42. #parseBeacons addressBookCallback fails decrypt - pass

2016-03-16T11:24:44.773Z - info: 43. #parseBeacons addressBookCallback returns no matches - pass
2016-03-16T11:24:44.773Z - info: 44. #parseBeacons addressBookCallback returns spurious match - pass

2016-03-16T11:24:44.774Z - info: 45. #parseBeacons addressBookCallback returns public key - pass
2016-03-16T11:24:44.775Z - info: 46. #parseBeacons with beacons both for and not for the user - pass
2016-03-16T11:24:44.776Z - info: 47. Start and stop ThaliNotificationServer - pass
2016-03-16T11:24:44.776Z - info: 48. Pass an empty array to ThaliNotificationServer.start - pass
2016-03-16T11:24:44.777Z - info: 49. Pass a string to ThaliNotificationServer.start - pass
2016-03-16T11:24:44.777Z - info: 50. Pass an empty parameter to ThaliNotificationServer.start - pass
2016-03-16T11:24:44.778Z - info: 51. Make an HTTP request to /NotificationBeacons - pass

2016-03-16T11:24:44.778Z - info: 52. Make an HTTP request to /NotificationBeacons (no keys) - pass
2016-03-16T11:24:44.779Z - info: 53. Make an HTTP request to /NotificationBeacons before calling start - pass
2016-03-16T11:24:44.779Z - info: 54. #testThaliPeerAction - test getters - pass
2016-03-16T11:24:44.780Z - info: 55. #testThaliPeerAction - start and kill - pass
2016-03-16T11:24:44.780Z - info: 56. #testThaliPeerAction - double start - pass
2016-03-16T11:24:44.781Z - info: 57. #testThaliPeerAction - start after kill - pass
2016-03-16T11:24:44.781Z - info: 58. #testThaliPeerAction - make sure ids are unique - pass
2016-03-16T11:24:44.782Z - info: 59. Test PeerConnectionInformation basics - pass
2016-03-16T11:24:44.782Z - info: 60. Test PeerDictionary basic functionality - pass
2016-03-16T11:24:44.783Z - info: 61. Test PeerDictionary with multiple entries. - pass
2016-03-16T11:24:44.783Z - info: 62. RESOLVED entries are removed before WAITING state entry. - pass
2016-03-16T11:24:44.784Z - info: 63. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass
2016-03-16T11:24:44.784Z - info: 64. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass
2016-03-16T11:24:44.785Z - info: 65. #ThaliPeerPoolInterface - bad enqueues - pass
2016-03-16T11:24:44.785Z - info: 66. #ThaliPeerPoolInterface - do not allow same object type - pass
2016-03-16T11:24:44.786Z - info: 67. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass
2016-03-16T11:24:44.786Z - info: 68. compareBufferArrays - pass
2016-03-16T11:24:44.787Z - info: 69. Call start twice and get error - pass
2016-03-16T11:24:44.787Z - info: 70. Start and make sure it runs - pass
2016-03-16T11:24:44.788Z - info: 71. Make sure getTimeWhenRun is right after start - pass
2016-03-16T11:24:44.788Z - info: 72. Make sure getTimeWhenRun is -1 after function is called - pass
2016-03-16T11:24:44.789Z - info: 73. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass
2016-03-16T11:24:44.789Z - info: 74. Test TransientState - pass
2016-03-16T11:24:44.790Z - info: 75. No peers and empty database - pass
2016-03-16T11:24:44.790Z - info: 76. One peer and empty DB - pass
2016-03-16T11:24:44.791Z - info: 77. One peer with _Local set behind current seq - pass
2016-03-16T11:24:44.791Z - info: 78. One peer with _Local set equal to current seq - pass
2016-03-16T11:24:44.792Z - info: 79. One peer with _Local set ahead of current seq (and no this should not happen) - pass
2016-03-16T11:24:44.792Z - info: 80. Three peers, one not in DB, one behind and one ahead - pass
2016-03-16T11:24:44.793Z - info: 81. More than maximum peers, make sure we only send maximum allowed - pass
2016-03-16T11:24:44.793Z - info: 82. two peers with empty DB, update the doc - pass
2016-03-16T11:24:44.794Z - info: 83. add doc and make sure tokens refresh when they expire - pass
2016-03-16T11:24:44.794Z - info: 84. start and stop and start and stop - pass
2016-03-16T11:24:44.795Z - info: 85. two identical starts in a row - pass
2016-03-16T11:24:44.795Z - info: 86. two different starts in a row - pass
2016-03-16T11:24:44.796Z - info: 87. two stops and a start and two stops - pass
2016-03-16T11:24:44.796Z - info: 88. we properly enqueue requests so no then needed - pass
2016-03-16T11:24:44.797Z - info: 89. test calculateSeqPointKeyId - pass
2016-03-16T11:24:44.797Z - info: 90. can create servers manager - pass
2016-03-16T11:24:44.797Z - info: 91. calling stop without start causes error - pass
2016-03-16T11:24:44.798Z - info: 92. can start/stop servers manager - pass
2016-03-16T11:24:44.798Z - info: 93. starting twice resolves with listening port - pass
2016-03-16T11:24:44.799Z - info: 94. terminateIncomingConnection will terminate a connection - pass
2016-03-16T11:24:44.799Z - info: 95. terminate an Outgoing connection will terminate the server - pass
2016-03-16T11:24:44.800Z - info: 96. terminate an Outgoing connection with wrong arguments is not harmful - pass
2016-03-16T11:24:44.800Z - info: 97. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass
2016-03-16T11:24:44.801Z - info: 98. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass
2016-03-16T11:24:44.801Z - info: 99. messages with invalid location or USN should be ignored - pass
2016-03-16T11:24:44.802Z - info: 100. verify that Thali-specific messages are filtered correctly - pass
2016-03-16T11:24:44.802Z - info: 101. #startListeningForAdvertisements should fail if start not called - pass
2016-03-16T11:24:44.803Z - info: 102. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-16T11:24:44.803Z - info: 103. #start should fail if called twice in a row - pass
2016-03-16T11:24:44.804Z - info: 104. should not be started after stop is called - pass

2016-03-16T11:24:44.805Z - info: 105. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass
2016-03-16T11:24:44.805Z - info: 106. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass
2016-03-16T11:24:44.806Z - info: 107. #startUpdateAdvertisingAndListening should start hosting given router object - pass
2016-03-16T11:24:44.806Z - info: 108. #stop can be called multiple times in a row - pass

2016-03-16T11:24:44.807Z - info: 109. #startListeningForAdvertisements can be called multiple times in a row - pass

2016-03-16T11:24:44.808Z - info: 110. #stopListeningForAdvertisements can be called multiple times in a row - pass
2016-03-16T11:24:44.809Z - info: 111. #stopAdvertisingAndListening can be called multiple times in a row - pass

2016-03-16T11:24:44.810Z - info: 112. functions are run from a queue in the right order - pass

2016-03-16T11:24:44.811Z - info: 113. #ThaliPeerPoolDefault - single action - pass
2016-03-16T11:24:44.811Z - info: 114. #ThaliPeerPoolDefault - multiple actions - pass
2016-03-16T11:24:44.812Z - info: 

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
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/63008475d624ed8_Slightly_less_bad_yaronyg/thali01_samsung-SM-A500FU.md)

####Node name: thali03
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Android task is completed. [SUCCESS]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/63008475d624ed8_Slightly_less_bad_yaronyg/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/63008475d624ed8_Slightly_less_bad_yaronyg/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Android task is completed. [SUCCESS]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/63008475d624ed8_Slightly_less_bad_yaronyg/thali05_LGE-LG-H815.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/63008475d624ed8_Slightly_less_bad_yaronyg/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/63008475d624ed8_Slightly_less_bad_yaronyg/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:0 
child process exited with code 0 on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/63008475d624ed8_Slightly_less_bad_yaronyg/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:0 
child process exited with code 0 on device 4325e43f 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/63008475d624ed8_Slightly_less_bad_yaronyg/thali08_samsung-SM-A300FU.md)




###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/63008475d624ed8_Slightly_less_bad_yaronyg/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/63008475d624ed8_Slightly_less_bad_yaronyg/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/63008475d624ed8_Slightly_less_bad_yaronyg/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/63008475d624ed8_Slightly_less_bad_yaronyg/iOS_Iphone5s-1.md)



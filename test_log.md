#### Test 63036995fb62ea7 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":8}}
2016-03-17T06:13:50.780Z - info: listening on *:3000

2016-03-17T06:13:51.444Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:0

2016-03-17T06:13:51.716Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:1

2016-03-17T06:13:51.932Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:2

2016-03-17T06:13:51.935Z - info: Required number of ios devices presented (2)

2016-03-17T06:13:51.939Z - info: Starting unit test run for platform: ios

2016-03-17T06:13:52.204Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:3

2016-03-17T06:13:52.207Z - info: Required number of android devices presented (2)

2016-03-17T06:13:52.210Z - info: Starting unit test run for platform: android

2016-03-17T06:13:52.534Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-17T06:13:52.681Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-17T06:13:53.012Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-17T06:13:53.075Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-17T06:13:53.245Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:4

2016-03-17T06:13:53.248Z - info: Discarding surplus device: Apple-Iphone6-1

2016-03-17T06:13:53.352Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-17T06:13:53.455Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-17T06:13:53.653Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:5

2016-03-17T06:13:53.655Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-17T06:13:53.732Z - info: Running on ios test: 4. native server connections all up

2016-03-17T06:13:53.962Z - info: Running on android test: 4. native server connections all up

2016-03-17T06:13:54.190Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-17T06:13:54.400Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-17T06:13:54.549Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-17T06:13:54.729Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-17T06:13:54.919Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-17T06:13:55.048Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-17T06:13:55.284Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-17T06:13:55.369Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-17T06:13:55.704Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-17T06:13:55.773Z - debug: Device presented: samsung-SM-A500FU (android) unittest socket:6

2016-03-17T06:13:55.775Z - info: Discarding surplus device: samsung-SM-A500FU

2016-03-17T06:13:55.785Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-17T06:13:55.971Z - debug: Socket disconnected: transport close 4 (Apple-Iphone6-1)

2016-03-17T06:13:56.168Z - debug: Socket disconnected: transport close 5 (Apple-Iphone5s-1)

2016-03-17T06:13:56.464Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-17T06:13:56.971Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-17T06:13:57.506Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-17T06:13:57.912Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-17T06:13:58.130Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-17T06:13:58.248Z - info: Running on android test: 13. closeAll with promise

2016-03-17T06:13:58.454Z - info: Running on android test: 14. multiplex can send data

2016-03-17T06:13:58.504Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-17T06:13:58.717Z - info: Running on android test: 15. enqueue and run in order

2016-03-17T06:13:58.824Z - info: Running on ios test: 13. closeAll with promise

2016-03-17T06:13:59.077Z - info: Running on ios test: 14. multiplex can send data

2016-03-17T06:13:59.368Z - info: Running on ios test: 15. enqueue and run in order

2016-03-17T06:13:59.398Z - info: Running on android test: 16. enqueueAtTop and run backwards

2016-03-17T06:13:59.748Z - info: Running on android test: 17. mix enqueue and enqueueAtTop

2016-03-17T06:13:59.966Z - info: Running on ios test: 16. enqueueAtTop and run backwards

2016-03-17T06:14:00.238Z - info: Running on android test: 18. queues handled independently

2016-03-17T06:14:00.282Z - info: Running on ios test: 17. mix enqueue and enqueueAtTop

2016-03-17T06:14:00.530Z - info: Running on android test: 19. basic

2016-03-17T06:14:00.641Z - info: Running on ios test: 18. queues handled independently

2016-03-17T06:14:00.792Z - info: Running on android test: 20. another

2016-03-17T06:14:00.898Z - info: Running on ios test: 19. basic

2016-03-17T06:14:01.029Z - info: Running on android test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-17T06:14:01.194Z - info: Running on ios test: 20. another

2016-03-17T06:14:01.302Z - info: Running on android test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-17T06:14:01.469Z - info: Running on ios test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-17T06:14:01.595Z - info: Running on android test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-17T06:14:01.826Z - info: Running on ios test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-17T06:14:01.971Z - info: Running on android test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-17T06:14:02.104Z - info: Running on ios test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-17T06:14:02.362Z - info: Running on android test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-17T06:14:02.366Z - info: Running on ios test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-17T06:14:02.760Z - info: Running on android test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-17T06:14:02.764Z - info: Running on ios test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-17T06:14:03.113Z - info: Running on android test: 27. #start should fail if called twice in a row

2016-03-17T06:14:03.205Z - info: Running on ios test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-17T06:14:03.431Z - info: Running on android test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-17T06:14:03.532Z - info: Running on ios test: 27. #start should fail if called twice in a row

2016-03-17T06:14:03.796Z - info: Running on android test: 29. does not send duplicate availability changes

2016-03-17T06:14:03.803Z - info: Running on ios test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-17T06:14:04.185Z - info: Running on ios test: 29. does not send duplicate availability changes

2016-03-17T06:14:04.189Z - info: Running on android test: 30. can get the network status

2016-03-17T06:14:04.641Z - info: Running on android test: 31. wifi peer is marked unavailable if announcements stop

2016-03-17T06:14:04.646Z - info: Running on ios test: 30. can get the network status

2016-03-17T06:14:04.955Z - info: Running on ios test: 31. wifi peer is marked unavailable if announcements stop

2016-03-17T06:14:06.032Z - info: Running on android test: 32. can get the network status before starting

2016-03-17T06:14:06.207Z - info: Running on ios test: 32. can get the network status before starting

2016-03-17T06:14:06.321Z - info: Running on android test: 33. #generatePreambleAndBeacons bad args

2016-03-17T06:14:06.462Z - info: Running on ios test: 33. #generatePreambleAndBeacons bad args

2016-03-17T06:14:06.729Z - info: Running on android test: 34. #generatePreambleAndBeacons empty keys to notify

2016-03-17T06:14:06.827Z - info: Running on ios test: 34. #generatePreambleAndBeacons empty keys to notify

2016-03-17T06:14:07.024Z - info: Running on android test: 35. #generatePreambleAndBeacons multiple keys to notify

2016-03-17T06:14:07.139Z - info: Running on ios test: 35. #generatePreambleAndBeacons multiple keys to notify

2016-03-17T06:14:07.480Z - info: Running on android test: 36. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-17T06:14:07.524Z - info: Running on ios test: 36. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-17T06:14:07.809Z - info: Running on android test: 37. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-17T06:14:07.815Z - info: Running on ios test: 37. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-17T06:14:08.137Z - info: Running on android test: 38. #parseBeacons expiration out of range lower

2016-03-17T06:14:08.142Z - info: Running on ios test: 38. #parseBeacons expiration out of range lower

2016-03-17T06:14:08.601Z - info: Running on android test: 39. #parseBeacons expiration out of range lower

2016-03-17T06:14:08.604Z - info: Running on ios test: 39. #parseBeacons expiration out of range lower

2016-03-17T06:14:09.129Z - info: Running on ios test: 40. #parseBeacons no beacons returns null

2016-03-17T06:14:09.135Z - info: Running on android test: 40. #parseBeacons no beacons returns null

2016-03-17T06:14:09.674Z - info: Running on ios test: 41. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-17T06:14:09.782Z - info: Running on android test: 41. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-17T06:14:10.021Z - info: Running on ios test: 42. #parseBeacons addressBookCallback fails decrypt

2016-03-17T06:14:10.124Z - info: Running on android test: 42. #parseBeacons addressBookCallback fails decrypt

2016-03-17T06:14:10.395Z - info: Running on ios test: 43. #parseBeacons addressBookCallback returns no matches

2016-03-17T06:14:10.529Z - info: Running on android test: 43. #parseBeacons addressBookCallback returns no matches

2016-03-17T06:14:10.739Z - info: Running on ios test: 44. #parseBeacons addressBookCallback returns spurious match

2016-03-17T06:14:10.990Z - info: Running on android test: 44. #parseBeacons addressBookCallback returns spurious match

2016-03-17T06:14:11.222Z - info: Running on ios test: 45. #parseBeacons addressBookCallback returns public key

2016-03-17T06:14:11.532Z - info: Running on android test: 45. #parseBeacons addressBookCallback returns public key

2016-03-17T06:14:11.676Z - info: Running on ios test: 46. #parseBeacons with beacons both for and not for the user

2016-03-17T06:14:12.029Z - info: Running on android test: 46. #parseBeacons with beacons both for and not for the user

2016-03-17T06:14:12.120Z - info: Running on ios test: 47. Start and stop ThaliNotificationServer

2016-03-17T06:14:12.475Z - info: Running on android test: 47. Start and stop ThaliNotificationServer

2016-03-17T06:14:12.538Z - info: Running on ios test: 48. Pass an empty array to ThaliNotificationServer.start

2016-03-17T06:14:12.934Z - info: Running on ios test: 49. Pass a string to ThaliNotificationServer.start

2016-03-17T06:14:12.999Z - info: Running on android test: 48. Pass an empty array to ThaliNotificationServer.start

2016-03-17T06:14:13.233Z - info: Running on ios test: 50. Pass an empty parameter to ThaliNotificationServer.start

2016-03-17T06:14:13.471Z - info: Running on android test: 49. Pass a string to ThaliNotificationServer.start

2016-03-17T06:14:13.544Z - info: Running on ios test: 51. Make an HTTP request to /NotificationBeacons

2016-03-17T06:14:13.773Z - info: Running on android test: 50. Pass an empty parameter to ThaliNotificationServer.start

2016-03-17T06:14:14.098Z - info: Running on android test: 51. Make an HTTP request to /NotificationBeacons

2016-03-17T06:14:14.450Z - info: Running on ios test: 52. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-17T06:14:14.594Z - info: Running on android test: 52. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-17T06:14:14.850Z - info: Running on ios test: 53. Make an HTTP request to /NotificationBeacons before calling start

2016-03-17T06:14:14.939Z - info: Running on android test: 53. Make an HTTP request to /NotificationBeacons before calling start

2016-03-17T06:14:15.148Z - info: Running on ios test: 54. #testThaliPeerAction - test getters

2016-03-17T06:14:15.231Z - info: Running on android test: 54. #testThaliPeerAction - test getters

2016-03-17T06:14:15.436Z - info: Running on ios test: 55. #testThaliPeerAction - start and kill

2016-03-17T06:14:15.559Z - info: Running on android test: 55. #testThaliPeerAction - start and kill

2016-03-17T06:14:15.691Z - info: Running on ios test: 56. #testThaliPeerAction - double start

2016-03-17T06:14:15.792Z - info: Running on android test: 56. #testThaliPeerAction - double start

2016-03-17T06:14:15.993Z - info: Running on ios test: 57. #testThaliPeerAction - start after kill

2016-03-17T06:14:16.140Z - info: Running on android test: 57. #testThaliPeerAction - start after kill

2016-03-17T06:14:16.231Z - info: Running on ios test: 58. #testThaliPeerAction - make sure ids are unique

2016-03-17T06:14:16.422Z - info: Running on android test: 58. #testThaliPeerAction - make sure ids are unique

2016-03-17T06:14:16.460Z - info: Running on ios test: 59. Test PeerConnectionInformation basics

2016-03-17T06:14:16.675Z - info: Running on android test: 59. Test PeerConnectionInformation basics

2016-03-17T06:14:16.680Z - info: Running on ios test: 60. Test PeerDictionary basic functionality

2016-03-17T06:14:16.930Z - info: Running on android test: 60. Test PeerDictionary basic functionality

2016-03-17T06:14:16.989Z - info: Running on ios test: 61. Test PeerDictionary with multiple entries.

2016-03-17T06:14:17.247Z - info: Running on android test: 61. Test PeerDictionary with multiple entries.

2016-03-17T06:14:18.799Z - info: Running on android test: 62. RESOLVED entries are removed before WAITING state entry.

2016-03-17T06:14:19.424Z - info: Running on ios test: 62. RESOLVED entries are removed before WAITING state entry.

2016-03-17T06:14:19.810Z - info: Running on android test: 63. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-17T06:14:20.739Z - info: Running on ios test: 63. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-17T06:14:20.814Z - info: Running on android test: 64. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-17T06:14:21.767Z - info: Running on android test: 65. #ThaliPeerPoolInterface - bad enqueues

2016-03-17T06:14:21.991Z - info: Running on ios test: 64. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-17T06:14:22.031Z - info: Running on android test: 66. #ThaliPeerPoolInterface - do not allow same object type

2016-03-17T06:14:22.332Z - info: Running on android test: 67. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-17T06:14:22.669Z - info: Running on android test: 68. compareBufferArrays

2016-03-17T06:14:22.985Z - info: Running on android test: 69. Call start twice and get error

2016-03-17T06:14:23.204Z - info: Running on ios test: 65. #ThaliPeerPoolInterface - bad enqueues

2016-03-17T06:14:23.336Z - info: Running on android test: 70. Start and make sure it runs

2016-03-17T06:14:23.539Z - info: Running on ios test: 66. #ThaliPeerPoolInterface - do not allow same object type

2016-03-17T06:14:23.575Z - info: Running on android test: 71. Make sure getTimeWhenRun is right after start

2016-03-17T06:14:23.785Z - info: Running on ios test: 67. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-17T06:14:23.870Z - info: Running on android test: 72. Make sure getTimeWhenRun is -1 after function is called

2016-03-17T06:14:24.080Z - info: Running on ios test: 68. compareBufferArrays

2016-03-17T06:14:24.186Z - info: Running on android test: 73. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-17T06:14:24.387Z - info: Running on ios test: 69. Call start twice and get error

2016-03-17T06:14:24.513Z - info: Running on android test: 74. Test TransientState

2016-03-17T06:14:24.701Z - info: Running on ios test: 70. Start and make sure it runs

2016-03-17T06:14:24.778Z - info: Running on android test: 75. No peers and empty database

2016-03-17T06:14:24.965Z - info: Running on ios test: 71. Make sure getTimeWhenRun is right after start

2016-03-17T06:14:25.317Z - info: Running on ios test: 72. Make sure getTimeWhenRun is -1 after function is called

2016-03-17T06:14:25.543Z - info: Running on android test: 76. One peer and empty DB

2016-03-17T06:14:25.647Z - info: Running on ios test: 73. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-17T06:14:25.922Z - info: Running on ios test: 74. Test TransientState

2016-03-17T06:14:26.048Z - info: Running on android test: 77. One peer with _Local set behind current seq

2016-03-17T06:14:26.206Z - info: Running on ios test: 75. No peers and empty database

2016-03-17T06:14:26.612Z - info: Running on android test: 78. One peer with _Local set equal to current seq

2016-03-17T06:14:26.700Z - info: Running on ios test: 76. One peer and empty DB

2016-03-17T06:14:27.144Z - info: Running on android test: 79. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-17T06:14:27.227Z - info: Running on ios test: 77. One peer with _Local set behind current seq

2016-03-17T06:14:27.622Z - info: Running on android test: 80. Three peers, one not in DB, one behind and one ahead

2016-03-17T06:14:28.373Z - info: Running on android test: 81. More than maximum peers, make sure we only send maximum allowed

2016-03-17T06:14:29.329Z - info: Running on android test: 82. two peers with empty DB, update the doc

2016-03-17T06:14:29.933Z - info: Running on android test: 83. add doc and make sure tokens refresh when they expire

2016-03-17T06:14:30.727Z - info: Running on android test: 84. start and stop and start and stop

2016-03-17T06:14:31.378Z - info: Running on android test: 85. two identical starts in a row

2016-03-17T06:14:31.706Z - info: Running on ios test: 78. One peer with _Local set equal to current seq

2016-03-17T06:14:31.861Z - info: Running on android test: 86. two different starts in a row

2016-03-17T06:14:32.288Z - info: Running on android test: 87. two stops and a start and two stops

2016-03-17T06:14:32.521Z - info: Running on ios test: 79. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-17T06:14:32.689Z - info: Running on android test: 88. we properly enqueue requests so no then needed

2016-03-17T06:14:33.087Z - info: Running on ios test: 80. Three peers, one not in DB, one behind and one ahead

2016-03-17T06:14:33.162Z - info: Running on android test: 89. test calculateSeqPointKeyId

2016-03-17T06:14:33.509Z - info: Running on android test: 90. can create servers manager

2016-03-17T06:14:33.940Z - info: Running on ios test: 81. More than maximum peers, make sure we only send maximum allowed

2016-03-17T06:14:33.964Z - info: Running on android test: 91. calling stop without start causes error

2016-03-17T06:14:34.300Z - info: Running on android test: 92. can start/stop servers manager

2016-03-17T06:14:34.614Z - info: Running on android test: 93. starting twice resolves with listening port

2016-03-17T06:14:34.972Z - info: Running on android test: 94. terminateIncomingConnection will terminate a connection

2016-03-17T06:14:35.190Z - info: Running on ios test: 82. two peers with empty DB, update the doc

2016-03-17T06:14:35.338Z - info: Running on android test: 95. terminate an Outgoing connection will terminate the server

2016-03-17T06:14:35.598Z - info: Running on android test: 96. terminate an Outgoing connection with wrong arguments is not harmful

2016-03-17T06:14:35.833Z - info: Running on android test: 97. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-17T06:14:35.914Z - info: Running on ios test: 83. add doc and make sure tokens refresh when they expire

2016-03-17T06:14:36.150Z - info: Running on android test: 98. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-17T06:14:36.504Z - info: Running on android test: 99. messages with invalid location or USN should be ignored

2016-03-17T06:14:36.861Z - info: Running on android test: 100. verify that Thali-specific messages are filtered correctly

2016-03-17T06:14:36.881Z - info: Running on ios test: 84. start and stop and start and stop

2016-03-17T06:14:37.142Z - info: Running on android test: 101. #startListeningForAdvertisements should fail if start not called

2016-03-17T06:14:37.445Z - info: Running on android test: 102. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-17T06:14:37.549Z - info: Running on ios test: 85. two identical starts in a row

2016-03-17T06:14:37.726Z - info: Running on android test: 103. #start should fail if called twice in a row

2016-03-17T06:14:38.033Z - info: Running on android test: 104. should not be started after stop is called

2016-03-17T06:14:38.165Z - info: Running on ios test: 86. two different starts in a row

2016-03-17T06:14:38.301Z - info: Running on android test: 105. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-17T06:14:38.612Z - info: Running on android test: 106. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-17T06:14:38.850Z - info: Running on ios test: 87. two stops and a start and two stops

2016-03-17T06:14:38.944Z - info: Running on android test: 107. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-17T06:14:39.343Z - info: Running on android test: 108. #stop can be called multiple times in a row

2016-03-17T06:14:39.383Z - info: Running on ios test: 88. we properly enqueue requests so no then needed

2016-03-17T06:14:39.647Z - info: Running on android test: 109. #startListeningForAdvertisements can be called multiple times in a row

2016-03-17T06:14:39.959Z - info: Running on android test: 110. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-17T06:14:40.010Z - info: Running on ios test: 89. test calculateSeqPointKeyId

2016-03-17T06:14:40.340Z - info: Running on ios test: 90. can create servers manager

2016-03-17T06:14:40.348Z - info: Running on android test: 111. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-17T06:14:40.658Z - info: Running on ios test: 91. calling stop without start causes error

2016-03-17T06:14:40.674Z - info: Running on android test: 112. functions are run from a queue in the right order

2016-03-17T06:14:40.942Z - info: Running on ios test: 92. can start/stop servers manager

2016-03-17T06:14:41.101Z - info: Running on android test: 113. #ThaliPeerPoolDefault - single action

2016-03-17T06:14:41.277Z - info: Running on ios test: 93. starting twice resolves with listening port

2016-03-17T06:14:41.366Z - info: Running on android test: 114. #ThaliPeerPoolDefault - multiple actions

2016-03-17T06:14:41.544Z - info: Running on ios test: 94. terminateIncomingConnection will terminate a connection

2016-03-17T06:14:41.747Z - info: Test run on android complete

2016-03-17T06:14:41.750Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-17T06:14:41.752Z - info: PLATFORM: android

2016-03-17T06:14:41.752Z - info: RESULT: PASS

2016-03-17T06:14:41.753Z - info: 114 of 114 tests completed

2016-03-17T06:14:41.754Z - info: 114/114 passed (0 failures)

2016-03-17T06:14:41.755Z - info: --- Test Details ---


2016-03-17T06:14:41.756Z - info: 1. calling createNativeListener directly rejects - pass

2016-03-17T06:14:41.757Z - info: 2. emits incomingConnectionState - pass

2016-03-17T06:14:41.758Z - info: 3. emits routerPortConnectionFailed - pass
2016-03-17T06:14:41.759Z - info: 4. native server connections all up - pass

2016-03-17T06:14:41.760Z - info: 5. native server - closing incoming stream cleans outgoing socket - pass

2016-03-17T06:14:41.761Z - info: 6. native server - closing incoming connection cleans outgoing socket - pass

2016-03-17T06:14:41.761Z - info: 7. native server - closing outgoing socket cleans associated mux stream - pass
2016-03-17T06:14:41.762Z - info: 8. native server - closing the whole server cleans everything up - pass

2016-03-17T06:14:41.763Z - info: 9. native server - we can get a ton of connections and data through and still clean up the server completely - pass

2016-03-17T06:14:41.764Z - info: 10. native server - simulate mux failure, make sure everything is cleaned up - pass

2016-03-17T06:14:41.765Z - info: 11. native server - timing out the incoming connection cleans everything up - pass

2016-03-17T06:14:41.765Z - info: 12. closeAll can close even when connections open - pass
2016-03-17T06:14:41.766Z - info: 13. closeAll with promise - pass

2016-03-17T06:14:41.767Z - info: 14. multiplex can send data - pass
2016-03-17T06:14:41.768Z - info: 15. enqueue and run in order - pass
2016-03-17T06:14:41.769Z - info: 16. enqueueAtTop and run backwards - pass
2016-03-17T06:14:41.769Z - info: 17. mix enqueue and enqueueAtTop - pass

2016-03-17T06:14:41.770Z - info: 18. queues handled independently - pass

2016-03-17T06:14:41.771Z - info: 19. basic - pass

2016-03-17T06:14:41.772Z - info: 20. another - pass

2016-03-17T06:14:41.773Z - info: 21. #startListeningForAdvertisements should fail if start not called - pass

2016-03-17T06:14:41.774Z - info: 22. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-17T06:14:41.775Z - info: 23. should be able to call #stopListeningForAdvertisements many times - pass

2016-03-17T06:14:41.775Z - info: 24. should be able to call #startListeningForAdvertisements many times - pass

2016-03-17T06:14:41.776Z - info: 25. should be able to call #startUpdateAdvertisingAndListening many times - pass

2016-03-17T06:14:41.777Z - info: 26. should be able to call #stopAdvertisingAndListening many times - pass

2016-03-17T06:14:41.778Z - info: 27. #start should fail if called twice in a row - pass

2016-03-17T06:14:41.788Z - info: 28. does not emit duplicate discoveryAdvertisingStateUpdate - pass

2016-03-17T06:14:41.789Z - info: 29. does not send duplicate availability changes - pass

2016-03-17T06:14:41.790Z - info: 30. can get the network status - pass

2016-03-17T06:14:41.791Z - info: 31. wifi peer is marked unavailable if announcements stop - pass
2016-03-17T06:14:41.792Z - info: 32. can get the network status before starting - pass

2016-03-17T06:14:41.793Z - info: 33. #generatePreambleAndBeacons bad args - pass

2016-03-17T06:14:41.793Z - info: 34. #generatePreambleAndBeacons empty keys to notify - pass
2016-03-17T06:14:41.794Z - info: 35. #generatePreambleAndBeacons multiple keys to notify - pass
2016-03-17T06:14:41.795Z - info: 36. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass
2016-03-17T06:14:41.795Z - info: 37. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass
2016-03-17T06:14:41.796Z - info: 38. #parseBeacons expiration out of range lower - pass
2016-03-17T06:14:41.797Z - info: 39. #parseBeacons expiration out of range lower - pass
2016-03-17T06:14:41.797Z - info: 40. #parseBeacons no beacons returns null - pass
2016-03-17T06:14:41.798Z - info: 41. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass
2016-03-17T06:14:41.798Z - info: 42. #parseBeacons addressBookCallback fails decrypt - pass
2016-03-17T06:14:41.799Z - info: 43. #parseBeacons addressBookCallback returns no matches - pass
2016-03-17T06:14:41.799Z - info: 44. #parseBeacons addressBookCallback returns spurious match - pass
2016-03-17T06:14:41.800Z - info: 45. #parseBeacons addressBookCallback returns public key - pass
2016-03-17T06:14:41.800Z - info: 46. #parseBeacons with beacons both for and not for the user - pass
2016-03-17T06:14:41.801Z - info: 47. Start and stop ThaliNotificationServer - pass
2016-03-17T06:14:41.801Z - info: 48. Pass an empty array to ThaliNotificationServer.start - pass
2016-03-17T06:14:41.802Z - info: 49. Pass a string to ThaliNotificationServer.start - pass
2016-03-17T06:14:41.802Z - info: 50. Pass an empty parameter to ThaliNotificationServer.start - pass
2016-03-17T06:14:41.803Z - info: 51. Make an HTTP request to /NotificationBeacons - pass
2016-03-17T06:14:41.803Z - info: 52. Make an HTTP request to /NotificationBeacons (no keys) - pass
2016-03-17T06:14:41.804Z - info: 53. Make an HTTP request to /NotificationBeacons before calling start - pass
2016-03-17T06:14:41.804Z - info: 54. #testThaliPeerAction - test getters - pass
2016-03-17T06:14:41.805Z - info: 55. #testThaliPeerAction - start and kill - pass
2016-03-17T06:14:41.805Z - info: 56. #testThaliPeerAction - double start - pass
2016-03-17T06:14:41.806Z - info: 57. #testThaliPeerAction - start after kill - pass
2016-03-17T06:14:41.806Z - info: 58. #testThaliPeerAction - make sure ids are unique - pass

2016-03-17T06:14:41.807Z - info: 59. Test PeerConnectionInformation basics - pass

2016-03-17T06:14:41.809Z - info: 60. Test PeerDictionary basic functionality - pass

2016-03-17T06:14:41.810Z - info: 61. Test PeerDictionary with multiple entries. - pass

2016-03-17T06:14:41.814Z - info: 62. RESOLVED entries are removed before WAITING state entry. - pass

2016-03-17T06:14:41.815Z - info: 63. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass

2016-03-17T06:14:41.816Z - info: 64. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass

2016-03-17T06:14:41.817Z - info: 65. #ThaliPeerPoolInterface - bad enqueues - pass
2016-03-17T06:14:41.818Z - info: 66. #ThaliPeerPoolInterface - do not allow same object type - pass

2016-03-17T06:14:41.819Z - info: 67. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass

2016-03-17T06:14:41.820Z - info: 68. compareBufferArrays - pass

2016-03-17T06:14:41.821Z - info: 69. Call start twice and get error - pass

2016-03-17T06:14:41.822Z - info: 70. Start and make sure it runs - pass

2016-03-17T06:14:41.823Z - info: 71. Make sure getTimeWhenRun is right after start - pass
2016-03-17T06:14:41.823Z - info: 72. Make sure getTimeWhenRun is -1 after function is called - pass

2016-03-17T06:14:41.824Z - info: 73. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass

2016-03-17T06:14:41.825Z - info: 74. Test TransientState - pass

2016-03-17T06:14:41.826Z - info: 75. No peers and empty database - pass

2016-03-17T06:14:41.827Z - info: 76. One peer and empty DB - pass
2016-03-17T06:14:41.827Z - info: 77. One peer with _Local set behind current seq - pass

2016-03-17T06:14:41.828Z - info: 78. One peer with _Local set equal to current seq - pass

2016-03-17T06:14:41.830Z - info: 79. One peer with _Local set ahead of current seq (and no this should not happen) - pass

2016-03-17T06:14:41.831Z - info: 80. Three peers, one not in DB, one behind and one ahead - pass

2016-03-17T06:14:41.831Z - info: 81. More than maximum peers, make sure we only send maximum allowed - pass
2016-03-17T06:14:41.832Z - info: 82. two peers with empty DB, update the doc - pass

2016-03-17T06:14:41.833Z - info: 83. add doc and make sure tokens refresh when they expire - pass

2016-03-17T06:14:41.834Z - info: 84. start and stop and start and stop - pass

2016-03-17T06:14:41.834Z - info: 85. two identical starts in a row - pass
2016-03-17T06:14:41.835Z - info: 86. two different starts in a row - pass

2016-03-17T06:14:41.836Z - info: 87. two stops and a start and two stops - pass

2016-03-17T06:14:41.837Z - info: 88. we properly enqueue requests so no then needed - pass

2016-03-17T06:14:41.838Z - info: 89. test calculateSeqPointKeyId - pass
2016-03-17T06:14:41.838Z - info: 90. can create servers manager - pass

2016-03-17T06:14:41.839Z - info: 91. calling stop without start causes error - pass

2016-03-17T06:14:41.840Z - info: 92. can start/stop servers manager - pass

2016-03-17T06:14:41.841Z - info: 93. starting twice resolves with listening port - pass
2016-03-17T06:14:41.842Z - info: 94. terminateIncomingConnection will terminate a connection - pass

2016-03-17T06:14:41.842Z - info: 95. terminate an Outgoing connection will terminate the server - pass

2016-03-17T06:14:41.843Z - info: 96. terminate an Outgoing connection with wrong arguments is not harmful - pass

2016-03-17T06:14:41.844Z - info: 97. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass
2016-03-17T06:14:41.845Z - info: 98. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-03-17T06:14:41.846Z - info: 99. messages with invalid location or USN should be ignored - pass

2016-03-17T06:14:41.846Z - info: 100. verify that Thali-specific messages are filtered correctly - pass

2016-03-17T06:14:41.847Z - info: 101. #startListeningForAdvertisements should fail if start not called - pass
2016-03-17T06:14:41.848Z - info: 102. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-17T06:14:41.849Z - info: 103. #start should fail if called twice in a row - pass

2016-03-17T06:14:41.850Z - info: 104. should not be started after stop is called - pass

2016-03-17T06:14:41.850Z - info: 105. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass
2016-03-17T06:14:41.851Z - info: 106. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass

2016-03-17T06:14:41.852Z - info: 107. #startUpdateAdvertisingAndListening should start hosting given router object - pass

2016-03-17T06:14:41.853Z - info: 108. #stop can be called multiple times in a row - pass

2016-03-17T06:14:41.854Z - info: 109. #startListeningForAdvertisements can be called multiple times in a row - pass
2016-03-17T06:14:41.854Z - info: 110. #stopListeningForAdvertisements can be called multiple times in a row - pass

2016-03-17T06:14:41.855Z - info: 111. #stopAdvertisingAndListening can be called multiple times in a row - pass

2016-03-17T06:14:41.856Z - info: 112. functions are run from a queue in the right order - pass

2016-03-17T06:14:41.857Z - info: 113. #ThaliPeerPoolDefault - single action - pass
2016-03-17T06:14:41.857Z - info: 114. #ThaliPeerPoolDefault - multiple actions - pass

2016-03-17T06:14:41.859Z - info: 

-== END ==-

2016-03-17T06:14:41.961Z - info: Running on ios test: 95. terminate an Outgoing connection will terminate the server

2016-03-17T06:14:42.304Z - info: Running on ios test: 96. terminate an Outgoing connection with wrong arguments is not harmful

2016-03-17T06:14:42.667Z - info: Running on ios test: 97. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-17T06:14:42.717Z - debug: Socket disconnected: transport close 3 (LGE-LG-H815)

2016-03-17T06:14:42.748Z - debug: Socket disconnected: transport close 0 (samsung-SM-N910C)

2016-03-17T06:14:43.057Z - info: Running on ios test: 98. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-17T06:14:43.504Z - info: Running on ios test: 99. messages with invalid location or USN should be ignored

2016-03-17T06:14:43.726Z - info: Running on ios test: 100. verify that Thali-specific messages are filtered correctly

2016-03-17T06:14:44.015Z - info: Running on ios test: 101. #startListeningForAdvertisements should fail if start not called

2016-03-17T06:14:44.329Z - info: Running on ios test: 102. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-17T06:14:44.640Z - info: Running on ios test: 103. #start should fail if called twice in a row

2016-03-17T06:14:44.970Z - info: Running on ios test: 104. should not be started after stop is called

2016-03-17T06:14:45.231Z - info: Running on ios test: 105. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-17T06:14:45.653Z - info: Running on ios test: 106. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-17T06:14:46.010Z - info: Running on ios test: 107. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-17T06:14:46.370Z - info: Running on ios test: 108. #stop can be called multiple times in a row

2016-03-17T06:14:46.716Z - info: Running on ios test: 109. #startListeningForAdvertisements can be called multiple times in a row

2016-03-17T06:14:46.988Z - info: Running on ios test: 110. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-17T06:14:47.264Z - info: Running on ios test: 111. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-17T06:14:47.522Z - info: Running on ios test: 112. functions are run from a queue in the right order

2016-03-17T06:14:47.807Z - info: Running on ios test: 113. #ThaliPeerPoolDefault - single action

2016-03-17T06:14:48.026Z - info: Running on ios test: 114. #ThaliPeerPoolDefault - multiple actions

2016-03-17T06:14:48.294Z - info: Test run on ios complete

2016-03-17T06:14:48.295Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-17T06:14:48.297Z - info: PLATFORM: ios

2016-03-17T06:14:48.298Z - info: RESULT: PASS

2016-03-17T06:14:48.299Z - info: 114 of 114 tests completed

2016-03-17T06:14:48.301Z - info: 114/114 passed (0 failures)

2016-03-17T06:14:48.301Z - info: --- Test Details ---



2016-03-17T06:14:48.302Z - info: 1. calling createNativeListener directly rejects - pass

2016-03-17T06:14:48.303Z - info: 2. emits incomingConnectionState - pass

2016-03-17T06:14:48.304Z - info: 3. emits routerPortConnectionFailed - pass

2016-03-17T06:14:48.306Z - info: 4. native server connections all up - pass

2016-03-17T06:14:48.307Z - info: 5. native server - closing incoming stream cleans outgoing socket - pass

2016-03-17T06:14:48.308Z - info: 6. native server - closing incoming connection cleans outgoing socket - pass

2016-03-17T06:14:48.315Z - info: 7. native server - closing outgoing socket cleans associated mux stream - pass

2016-03-17T06:14:48.316Z - info: 8. native server - closing the whole server cleans everything up - pass
2016-03-17T06:14:48.317Z - info: 9. native server - we can get a ton of connections and data through and still clean up the server completely - pass

2016-03-17T06:14:48.318Z - info: 10. native server - simulate mux failure, make sure everything is cleaned up - pass

2016-03-17T06:14:48.319Z - info: 11. native server - timing out the incoming connection cleans everything up - pass

2016-03-17T06:14:48.319Z - info: 12. closeAll can close even when connections open - pass
2016-03-17T06:14:48.320Z - info: 13. closeAll with promise - pass

2016-03-17T06:14:48.321Z - info: 14. multiplex can send data - pass

2016-03-17T06:14:48.322Z - info: 15. enqueue and run in order - pass

2016-03-17T06:14:48.323Z - info: 16. enqueueAtTop and run backwards - pass
2016-03-17T06:14:48.323Z - info: 17. mix enqueue and enqueueAtTop - pass

2016-03-17T06:14:48.355Z - info: 18. queues handled independently - pass

2016-03-17T06:14:48.356Z - info: 19. basic - pass

2016-03-17T06:14:48.357Z - info: 20. another - pass
2016-03-17T06:14:48.358Z - info: 21. #startListeningForAdvertisements should fail if start not called - pass

2016-03-17T06:14:48.359Z - info: 22. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-17T06:14:48.359Z - info: 23. should be able to call #stopListeningForAdvertisements many times - pass

2016-03-17T06:14:48.360Z - info: 24. should be able to call #startListeningForAdvertisements many times - pass
2016-03-17T06:14:48.361Z - info: 25. should be able to call #startUpdateAdvertisingAndListening many times - pass

2016-03-17T06:14:48.362Z - info: 26. should be able to call #stopAdvertisingAndListening many times - pass

2016-03-17T06:14:48.362Z - info: 27. #start should fail if called twice in a row - pass

2016-03-17T06:14:48.363Z - info: 28. does not emit duplicate discoveryAdvertisingStateUpdate - pass
2016-03-17T06:14:48.364Z - info: 29. does not send duplicate availability changes - pass

2016-03-17T06:14:48.365Z - info: 30. can get the network status - pass

2016-03-17T06:14:48.366Z - info: 31. wifi peer is marked unavailable if announcements stop - pass

2016-03-17T06:14:48.366Z - info: 32. can get the network status before starting - pass
2016-03-17T06:14:48.367Z - info: 33. #generatePreambleAndBeacons bad args - pass

2016-03-17T06:14:48.368Z - info: 34. #generatePreambleAndBeacons empty keys to notify - pass

2016-03-17T06:14:48.369Z - info: 35. #generatePreambleAndBeacons multiple keys to notify - pass

2016-03-17T06:14:48.370Z - info: 36. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass
2016-03-17T06:14:48.370Z - info: 37. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass

2016-03-17T06:14:48.371Z - info: 38. #parseBeacons expiration out of range lower - pass

2016-03-17T06:14:48.372Z - info: 39. #parseBeacons expiration out of range lower - pass

2016-03-17T06:14:48.373Z - info: 40. #parseBeacons no beacons returns null - pass
2016-03-17T06:14:48.373Z - info: 41. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass

2016-03-17T06:14:48.374Z - info: 42. #parseBeacons addressBookCallback fails decrypt - pass

2016-03-17T06:14:48.375Z - info: 43. #parseBeacons addressBookCallback returns no matches - pass
2016-03-17T06:14:48.376Z - info: 44. #parseBeacons addressBookCallback returns spurious match - pass

2016-03-17T06:14:48.376Z - info: 45. #parseBeacons addressBookCallback returns public key - pass

2016-03-17T06:14:48.377Z - info: 46. #parseBeacons with beacons both for and not for the user - pass

2016-03-17T06:14:48.378Z - info: 47. Start and stop ThaliNotificationServer - pass
2016-03-17T06:14:48.379Z - info: 48. Pass an empty array to ThaliNotificationServer.start - pass

2016-03-17T06:14:48.379Z - info: 49. Pass a string to ThaliNotificationServer.start - pass

2016-03-17T06:14:48.380Z - info: 50. Pass an empty parameter to ThaliNotificationServer.start - pass

2016-03-17T06:14:48.381Z - info: 51. Make an HTTP request to /NotificationBeacons - pass
2016-03-17T06:14:48.382Z - info: 52. Make an HTTP request to /NotificationBeacons (no keys) - pass

2016-03-17T06:14:48.383Z - info: 53. Make an HTTP request to /NotificationBeacons before calling start - pass

2016-03-17T06:14:48.383Z - info: 54. #testThaliPeerAction - test getters - pass
2016-03-17T06:14:48.384Z - info: 55. #testThaliPeerAction - start and kill - pass

2016-03-17T06:14:48.385Z - info: 56. #testThaliPeerAction - double start - pass

2016-03-17T06:14:48.385Z - info: 57. #testThaliPeerAction - start after kill - pass
2016-03-17T06:14:48.386Z - info: 58. #testThaliPeerAction - make sure ids are unique - pass

2016-03-17T06:14:48.387Z - info: 59. Test PeerConnectionInformation basics - pass
2016-03-17T06:14:48.388Z - info: 60. Test PeerDictionary basic functionality - pass
2016-03-17T06:14:48.389Z - info: 61. Test PeerDictionary with multiple entries. - pass
2016-03-17T06:14:48.389Z - info: 62. RESOLVED entries are removed before WAITING state entry. - pass
2016-03-17T06:14:48.390Z - info: 63. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass
2016-03-17T06:14:48.390Z - info: 64. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass
2016-03-17T06:14:48.391Z - info: 65. #ThaliPeerPoolInterface - bad enqueues - pass

2016-03-17T06:14:48.391Z - info: 66. #ThaliPeerPoolInterface - do not allow same object type - pass
2016-03-17T06:14:48.392Z - info: 67. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass
2016-03-17T06:14:48.392Z - info: 68. compareBufferArrays - pass
2016-03-17T06:14:48.393Z - info: 69. Call start twice and get error - pass
2016-03-17T06:14:48.393Z - info: 70. Start and make sure it runs - pass
2016-03-17T06:14:48.394Z - info: 71. Make sure getTimeWhenRun is right after start - pass
2016-03-17T06:14:48.394Z - info: 72. Make sure getTimeWhenRun is -1 after function is called - pass
2016-03-17T06:14:48.395Z - info: 73. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass
2016-03-17T06:14:48.395Z - info: 74. Test TransientState - pass
2016-03-17T06:14:48.396Z - info: 75. No peers and empty database - pass
2016-03-17T06:14:48.396Z - info: 76. One peer and empty DB - pass
2016-03-17T06:14:48.397Z - info: 77. One peer with _Local set behind current seq - pass
2016-03-17T06:14:48.397Z - info: 78. One peer with _Local set equal to current seq - pass
2016-03-17T06:14:48.398Z - info: 79. One peer with _Local set ahead of current seq (and no this should not happen) - pass
2016-03-17T06:14:48.398Z - info: 80. Three peers, one not in DB, one behind and one ahead - pass
2016-03-17T06:14:48.399Z - info: 81. More than maximum peers, make sure we only send maximum allowed - pass
2016-03-17T06:14:48.399Z - info: 82. two peers with empty DB, update the doc - pass
2016-03-17T06:14:48.400Z - info: 83. add doc and make sure tokens refresh when they expire - pass
2016-03-17T06:14:48.400Z - info: 84. start and stop and start and stop - pass
2016-03-17T06:14:48.401Z - info: 85. two identical starts in a row - pass
2016-03-17T06:14:48.401Z - info: 86. two different starts in a row - pass
2016-03-17T06:14:48.402Z - info: 87. two stops and a start and two stops - pass
2016-03-17T06:14:48.402Z - info: 88. we properly enqueue requests so no then needed - pass
2016-03-17T06:14:48.403Z - info: 89. test calculateSeqPointKeyId - pass
2016-03-17T06:14:48.403Z - info: 90. can create servers manager - pass
2016-03-17T06:14:48.404Z - info: 91. calling stop without start causes error - pass
2016-03-17T06:14:48.404Z - info: 92. can start/stop servers manager - pass
2016-03-17T06:14:48.405Z - info: 93. starting twice resolves with listening port - pass
2016-03-17T06:14:48.405Z - info: 94. terminateIncomingConnection will terminate a connection - pass
2016-03-17T06:14:48.406Z - info: 95. terminate an Outgoing connection will terminate the server - pass
2016-03-17T06:14:48.406Z - info: 96. terminate an Outgoing connection with wrong arguments is not harmful - pass
2016-03-17T06:14:48.407Z - info: 97. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass
2016-03-17T06:14:48.408Z - info: 98. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass
2016-03-17T06:14:48.408Z - info: 99. messages with invalid location or USN should be ignored - pass
2016-03-17T06:14:48.409Z - info: 100. verify that Thali-specific messages are filtered correctly - pass
2016-03-17T06:14:48.409Z - info: 101. #startListeningForAdvertisements should fail if start not called - pass
2016-03-17T06:14:48.410Z - info: 102. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-17T06:14:48.410Z - info: 103. #start should fail if called twice in a row - pass
2016-03-17T06:14:48.411Z - info: 104. should not be started after stop is called - pass
2016-03-17T06:14:48.411Z - info: 105. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass
2016-03-17T06:14:48.411Z - info: 106. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass
2016-03-17T06:14:48.412Z - info: 107. #startUpdateAdvertisingAndListening should start hosting given router object - pass
2016-03-17T06:14:48.412Z - info: 108. #stop can be called multiple times in a row - pass
2016-03-17T06:14:48.413Z - info: 109. #startListeningForAdvertisements can be called multiple times in a row - pass
2016-03-17T06:14:48.413Z - info: 110. #stopListeningForAdvertisements can be called multiple times in a row - pass
2016-03-17T06:14:48.414Z - info: 111. #stopAdvertisingAndListening can be called multiple times in a row - pass
2016-03-17T06:14:48.414Z - info: 112. functions are run from a queue in the right order - pass
2016-03-17T06:14:48.415Z - info: 113. #ThaliPeerPoolDefault - single action - pass
2016-03-17T06:14:48.415Z - info: 114. #ThaliPeerPoolDefault - multiple actions - pass
2016-03-17T06:14:48.416Z - info: 

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
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/63036995fb62ea7_Use_a_custom_build_of_jxcore-cordova_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali03
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Android task is completed. [SUCCESS]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/63036995fb62ea7_Use_a_custom_build_of_jxcore-cordova_vjrantal/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/63036995fb62ea7_Use_a_custom_build_of_jxcore-cordova_vjrantal/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Android task is completed. [SUCCESS]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/63036995fb62ea7_Use_a_custom_build_of_jxcore-cordova_vjrantal/thali05_LGE-LG-H815.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/63036995fb62ea7_Use_a_custom_build_of_jxcore-cordova_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/63036995fb62ea7_Use_a_custom_build_of_jxcore-cordova_vjrantal/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:0 
child process exited with code 0 on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/63036995fb62ea7_Use_a_custom_build_of_jxcore-cordova_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:0 
child process exited with code 0 on device 4325e43f 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/63036995fb62ea7_Use_a_custom_build_of_jxcore-cordova_vjrantal/thali08_samsung-SM-A300FU.md)




###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/63036995fb62ea7_Use_a_custom_build_of_jxcore-cordova_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/63036995fb62ea7_Use_a_custom_build_of_jxcore-cordova_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/63036995fb62ea7_Use_a_custom_build_of_jxcore-cordova_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/63036995fb62ea7_Use_a_custom_build_of_jxcore-cordova_vjrantal/iOS_Iphone5s-1.md)



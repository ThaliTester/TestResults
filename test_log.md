#### Test 630369953a3bebd Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":8}}
2016-03-16T10:20:33.189Z - info: listening on *:3000

2016-03-16T10:20:35.124Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:0

2016-03-16T10:20:35.339Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:1

2016-03-16T10:20:36.289Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:2

2016-03-16T10:20:36.292Z - info: Required number of ios devices presented (2)

2016-03-16T10:20:36.295Z - info: Starting unit test run for platform: ios

2016-03-16T10:20:36.522Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:3

2016-03-16T10:20:36.523Z - info: Discarding surplus device: Apple-Iphone5-1

2016-03-16T10:20:36.813Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-16T10:20:37.408Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-16T10:20:37.806Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-16T10:20:38.219Z - info: Running on ios test: 4. native server connections all up

2016-03-16T10:20:38.290Z - debug: Device presented: motorola-XT1072 (android) unittest socket:5

2016-03-16T10:20:38.291Z - info: Required number of android devices presented (2)

2016-03-16T10:20:38.294Z - info: Starting unit test run for platform: android

2016-03-16T10:20:38.683Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:6

2016-03-16T10:20:38.685Z - info: Discarding surplus device: samsung-SM-N910C

2016-03-16T10:20:38.850Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-16T10:20:39.089Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-16T10:20:39.464Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:4

2016-03-16T10:20:39.467Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-16T10:20:39.536Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-16T10:20:39.634Z - debug: Socket disconnected: transport close 6 (samsung-SM-N910C)

2016-03-16T10:20:39.657Z - debug: Socket disconnected: transport close 3 (Apple-Iphone5-1)

2016-03-16T10:20:40.302Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-16T10:20:40.540Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-16T10:20:40.678Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-16T10:20:41.033Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-16T10:20:41.088Z - info: Running on android test: 4. native server connections all up

2016-03-16T10:20:41.530Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-16T10:20:41.605Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-16T10:20:42.022Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-16T10:20:42.258Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-16T10:20:42.401Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-16T10:20:42.747Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-16T10:20:43.149Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-16T10:20:43.986Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-16T10:20:44.331Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-16T10:20:44.618Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-16T10:20:44.732Z - debug: Socket disconnected: transport close 4 (Apple-Iphone5s-1)

2016-03-16T10:20:45.136Z - info: Running on ios test: 13. closeAll with promise

2016-03-16T10:20:45.433Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-16T10:20:45.992Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-16T10:20:46.060Z - info: Running on ios test: 14. multiplex can send data

2016-03-16T10:20:46.333Z - info: Running on android test: 13. closeAll with promise

2016-03-16T10:20:46.479Z - info: Running on ios test: 15. enqueue and run in order

2016-03-16T10:20:46.763Z - info: Running on android test: 14. multiplex can send data

2016-03-16T10:20:47.236Z - info: Running on android test: 15. enqueue and run in order

2016-03-16T10:20:47.241Z - info: Running on ios test: 16. enqueueAtTop and run backwards

2016-03-16T10:20:47.640Z - info: Running on ios test: 17. mix enqueue and enqueueAtTop

2016-03-16T10:20:48.126Z - info: Running on android test: 16. enqueueAtTop and run backwards

2016-03-16T10:20:48.244Z - info: Running on ios test: 18. queues handled independently

2016-03-16T10:20:48.675Z - info: Running on ios test: 19. basic

2016-03-16T10:20:49.247Z - info: Running on ios test: 20. another

2016-03-16T10:20:49.411Z - info: Running on android test: 17. mix enqueue and enqueueAtTop

2016-03-16T10:20:49.705Z - info: Running on ios test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-16T10:20:50.120Z - info: Running on android test: 18. queues handled independently

2016-03-16T10:20:50.293Z - info: Running on ios test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-16T10:20:50.462Z - info: Running on android test: 19. basic

2016-03-16T10:20:50.613Z - info: Running on ios test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-16T10:20:50.777Z - info: Running on android test: 20. another

2016-03-16T10:20:51.022Z - info: Running on ios test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-16T10:20:51.147Z - info: Running on android test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-16T10:20:51.480Z - info: Running on ios test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-16T10:20:51.651Z - info: Running on android test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-16T10:20:52.396Z - info: Running on ios test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-16T10:20:52.933Z - info: Running on android test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-16T10:20:53.003Z - info: Running on ios test: 27. #start should fail if called twice in a row

2016-03-16T10:20:53.382Z - info: Running on android test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-16T10:20:53.551Z - info: Running on ios test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-16T10:20:53.876Z - info: Running on android test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-16T10:20:54.071Z - info: Running on ios test: 29. does not send duplicate availability changes

2016-03-16T10:20:54.388Z - info: Running on android test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-16T10:20:54.493Z - info: Running on ios test: 30. can get the network status

2016-03-16T10:20:54.999Z - info: Running on ios test: 31. wifi peer is marked unavailable if announcements stop

2016-03-16T10:20:55.179Z - info: Running on android test: 27. #start should fail if called twice in a row

2016-03-16T10:20:55.822Z - info: Running on android test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-16T10:20:56.707Z - info: Running on ios test: 32. can get the network status before starting

2016-03-16T10:20:56.783Z - info: Running on android test: 29. does not send duplicate availability changes

2016-03-16T10:20:57.218Z - info: Running on ios test: 33. #generatePreambleAndBeacons bad args

2016-03-16T10:20:57.449Z - info: Running on android test: 30. can get the network status

2016-03-16T10:20:57.627Z - info: Running on ios test: 34. #generatePreambleAndBeacons empty keys to notify

2016-03-16T10:20:57.866Z - info: Running on android test: 31. wifi peer is marked unavailable if announcements stop

2016-03-16T10:20:58.044Z - info: Running on ios test: 35. #generatePreambleAndBeacons multiple keys to notify

2016-03-16T10:20:58.556Z - info: Running on ios test: 36. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-16T10:20:59.138Z - info: Running on ios test: 37. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-16T10:20:59.311Z - info: Running on android test: 32. can get the network status before starting

2016-03-16T10:20:59.572Z - info: Running on ios test: 38. #parseBeacons expiration out of range lower

2016-03-16T10:20:59.826Z - info: Running on android test: 33. #generatePreambleAndBeacons bad args

2016-03-16T10:21:00.018Z - info: Running on ios test: 39. #parseBeacons expiration out of range lower

2016-03-16T10:21:00.314Z - info: Running on android test: 34. #generatePreambleAndBeacons empty keys to notify

2016-03-16T10:21:00.530Z - info: Running on ios test: 40. #parseBeacons no beacons returns null

2016-03-16T10:21:00.725Z - info: Running on android test: 35. #generatePreambleAndBeacons multiple keys to notify

2016-03-16T10:21:00.918Z - info: Running on ios test: 41. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-16T10:21:01.149Z - info: Running on android test: 36. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-16T10:21:01.207Z - info: Running on ios test: 42. #parseBeacons addressBookCallback fails decrypt

2016-03-16T10:21:01.484Z - info: Running on android test: 37. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-16T10:21:01.637Z - info: Running on ios test: 43. #parseBeacons addressBookCallback returns no matches

2016-03-16T10:21:01.921Z - info: Running on android test: 38. #parseBeacons expiration out of range lower

2016-03-16T10:21:02.050Z - info: Running on ios test: 44. #parseBeacons addressBookCallback returns spurious match

2016-03-16T10:21:02.221Z - info: Running on android test: 39. #parseBeacons expiration out of range lower

2016-03-16T10:21:02.405Z - info: Running on ios test: 45. #parseBeacons addressBookCallback returns public key

2016-03-16T10:21:02.544Z - info: Running on android test: 40. #parseBeacons no beacons returns null

2016-03-16T10:21:02.848Z - info: Running on ios test: 46. #parseBeacons with beacons both for and not for the user

2016-03-16T10:21:02.952Z - info: Running on android test: 41. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-16T10:21:03.207Z - info: Running on ios test: 47. Start and stop ThaliNotificationServer

2016-03-16T10:21:03.327Z - info: Running on android test: 42. #parseBeacons addressBookCallback fails decrypt

2016-03-16T10:21:03.558Z - info: Running on ios test: 48. Pass an empty array to ThaliNotificationServer.start

2016-03-16T10:21:03.903Z - info: Running on android test: 43. #parseBeacons addressBookCallback returns no matches

2016-03-16T10:21:04.549Z - info: Running on android test: 44. #parseBeacons addressBookCallback returns spurious match

2016-03-16T10:21:05.149Z - info: Running on android test: 45. #parseBeacons addressBookCallback returns public key

2016-03-16T10:21:05.665Z - info: Running on android test: 46. #parseBeacons with beacons both for and not for the user

2016-03-16T10:21:06.104Z - info: Running on android test: 47. Start and stop ThaliNotificationServer

2016-03-16T10:21:06.626Z - info: Running on android test: 48. Pass an empty array to ThaliNotificationServer.start

2016-03-16T10:21:07.404Z - info: Running on android test: 49. Pass a string to ThaliNotificationServer.start

2016-03-16T10:21:08.273Z - info: Running on android test: 50. Pass an empty parameter to ThaliNotificationServer.start

2016-03-16T10:21:08.717Z - info: Running on android test: 51. Make an HTTP request to /NotificationBeacons

2016-03-16T10:21:09.248Z - info: Running on android test: 52. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-16T10:21:09.552Z - info: Running on android test: 53. Make an HTTP request to /NotificationBeacons before calling start

2016-03-16T10:21:09.934Z - info: Running on android test: 54. #testThaliPeerAction - test getters

2016-03-16T10:21:10.444Z - info: Running on android test: 55. #testThaliPeerAction - start and kill

2016-03-16T10:21:10.893Z - info: Running on android test: 56. #testThaliPeerAction - double start

2016-03-16T10:21:10.964Z - info: Running on ios test: 49. Pass a string to ThaliNotificationServer.start

2016-03-16T10:21:11.255Z - info: Running on android test: 57. #testThaliPeerAction - start after kill

2016-03-16T10:21:11.544Z - info: Running on ios test: 50. Pass an empty parameter to ThaliNotificationServer.start

2016-03-16T10:21:11.661Z - info: Running on android test: 58. #testThaliPeerAction - make sure ids are unique

2016-03-16T10:21:12.038Z - info: Running on ios test: 51. Make an HTTP request to /NotificationBeacons

2016-03-16T10:21:12.126Z - info: Running on android test: 59. Test PeerConnectionInformation basics

2016-03-16T10:21:12.442Z - info: Running on android test: 60. Test PeerDictionary basic functionality

2016-03-16T10:21:12.586Z - info: Running on ios test: 52. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-16T10:21:12.875Z - info: Running on android test: 61. Test PeerDictionary with multiple entries.

2016-03-16T10:21:13.050Z - info: Running on ios test: 53. Make an HTTP request to /NotificationBeacons before calling start

2016-03-16T10:21:13.614Z - info: Running on ios test: 54. #testThaliPeerAction - test getters

2016-03-16T10:21:14.015Z - info: Running on ios test: 55. #testThaliPeerAction - start and kill

2016-03-16T10:21:14.398Z - info: Running on ios test: 56. #testThaliPeerAction - double start

2016-03-16T10:21:14.945Z - info: Running on ios test: 57. #testThaliPeerAction - start after kill

2016-03-16T10:21:15.436Z - info: Running on ios test: 58. #testThaliPeerAction - make sure ids are unique

2016-03-16T10:21:15.838Z - info: Running on ios test: 59. Test PeerConnectionInformation basics

2016-03-16T10:21:16.150Z - info: Running on ios test: 60. Test PeerDictionary basic functionality

2016-03-16T10:21:16.564Z - info: Running on android test: 62. RESOLVED entries are removed before WAITING state entry.

2016-03-16T10:21:16.569Z - info: Running on ios test: 61. Test PeerDictionary with multiple entries.

2016-03-16T10:21:18.265Z - info: Running on ios test: 62. RESOLVED entries are removed before WAITING state entry.

2016-03-16T10:21:18.699Z - info: Running on android test: 63. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-16T10:21:19.024Z - info: Running on ios test: 63. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-16T10:21:19.813Z - info: Running on ios test: 64. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-16T10:21:20.536Z - info: Running on android test: 64. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-16T10:21:20.764Z - info: Running on ios test: 65. #ThaliPeerPoolInterface - bad enqueues

2016-03-16T10:21:21.070Z - info: Running on ios test: 66. #ThaliPeerPoolInterface - do not allow same object type

2016-03-16T10:21:21.448Z - info: Running on ios test: 67. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-16T10:21:21.849Z - info: Running on ios test: 68. compareBufferArrays

2016-03-16T10:21:22.215Z - info: Running on ios test: 69. Call start twice and get error

2016-03-16T10:21:22.478Z - info: Running on android test: 65. #ThaliPeerPoolInterface - bad enqueues

2016-03-16T10:21:22.567Z - info: Running on ios test: 70. Start and make sure it runs

2016-03-16T10:21:22.876Z - info: Running on ios test: 71. Make sure getTimeWhenRun is right after start

2016-03-16T10:21:23.181Z - info: Running on ios test: 72. Make sure getTimeWhenRun is -1 after function is called

2016-03-16T10:21:23.453Z - info: Running on android test: 66. #ThaliPeerPoolInterface - do not allow same object type

2016-03-16T10:21:23.497Z - info: Running on ios test: 73. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-16T10:21:23.802Z - info: Running on ios test: 74. Test TransientState

2016-03-16T10:21:23.807Z - info: Running on android test: 67. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-16T10:21:24.132Z - info: Running on ios test: 75. No peers and empty database

2016-03-16T10:21:24.140Z - info: Running on android test: 68. compareBufferArrays

2016-03-16T10:21:24.523Z - info: Running on android test: 69. Call start twice and get error

2016-03-16T10:21:24.631Z - info: Running on ios test: 76. One peer and empty DB

2016-03-16T10:21:24.874Z - info: Running on android test: 70. Start and make sure it runs

2016-03-16T10:21:25.126Z - info: Running on ios test: 77. One peer with _Local set behind current seq

2016-03-16T10:21:25.179Z - info: Running on android test: 71. Make sure getTimeWhenRun is right after start

2016-03-16T10:21:25.452Z - info: Running on android test: 72. Make sure getTimeWhenRun is -1 after function is called

2016-03-16T10:21:25.681Z - info: Running on ios test: 78. One peer with _Local set equal to current seq

2016-03-16T10:21:25.822Z - info: Running on android test: 73. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-16T10:21:26.328Z - info: Running on android test: 74. Test TransientState

2016-03-16T10:21:26.371Z - info: Running on ios test: 79. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-16T10:21:26.681Z - info: Running on android test: 75. No peers and empty database

2016-03-16T10:21:26.987Z - info: Running on ios test: 80. Three peers, one not in DB, one behind and one ahead

2016-03-16T10:21:27.230Z - info: Running on android test: 76. One peer and empty DB

2016-03-16T10:21:27.547Z - info: Running on ios test: 81. More than maximum peers, make sure we only send maximum allowed

2016-03-16T10:21:27.717Z - info: Running on android test: 77. One peer with _Local set behind current seq

2016-03-16T10:21:28.584Z - info: Running on android test: 78. One peer with _Local set equal to current seq

2016-03-16T10:21:28.780Z - info: Running on ios test: 82. two peers with empty DB, update the doc

2016-03-16T10:21:29.479Z - info: Running on ios test: 83. add doc and make sure tokens refresh when they expire

2016-03-16T10:21:29.622Z - info: Running on android test: 79. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-16T10:21:30.302Z - info: Running on android test: 80. Three peers, one not in DB, one behind and one ahead

2016-03-16T10:21:30.518Z - info: Running on ios test: 84. start and stop and start and stop

2016-03-16T10:21:31.185Z - info: Running on android test: 81. More than maximum peers, make sure we only send maximum allowed

2016-03-16T10:21:31.290Z - info: Running on ios test: 85. two identical starts in a row

2016-03-16T10:21:31.841Z - info: Running on ios test: 86. two different starts in a row

2016-03-16T10:21:32.482Z - info: Running on ios test: 87. two stops and a start and two stops

2016-03-16T10:21:32.824Z - info: Running on android test: 82. two peers with empty DB, update the doc

2016-03-16T10:21:33.002Z - info: Running on ios test: 88. we properly enqueue requests so no then needed

2016-03-16T10:21:33.452Z - info: Running on ios test: 89. test calculateSeqPointKeyId

2016-03-16T10:21:33.624Z - info: Running on android test: 83. add doc and make sure tokens refresh when they expire

2016-03-16T10:21:33.770Z - info: Running on ios test: 90. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-16T10:21:34.109Z - info: Running on ios test: 91. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-16T10:21:34.464Z - info: Running on ios test: 92. messages with invalid location or USN should be ignored

2016-03-16T10:21:34.736Z - info: Running on ios test: 93. verify that Thali-specific messages are filtered correctly

2016-03-16T10:21:34.834Z - info: Running on android test: 84. start and stop and start and stop

2016-03-16T10:21:35.015Z - info: Running on ios test: 94. #startListeningForAdvertisements should fail if start not called

2016-03-16T10:21:35.318Z - info: Running on ios test: 95. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-16T10:21:35.506Z - info: Running on android test: 85. two identical starts in a row

2016-03-16T10:21:35.823Z - info: Running on ios test: 96. #start should fail if called twice in a row

2016-03-16T10:21:36.149Z - info: Running on ios test: 97. should not be started after stop is called

2016-03-16T10:21:36.152Z - info: Running on android test: 86. two different starts in a row

2016-03-16T10:21:36.489Z - info: Running on ios test: 98. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-16T10:21:36.771Z - info: Running on android test: 87. two stops and a start and two stops

2016-03-16T10:21:36.912Z - info: Running on ios test: 99. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-16T10:21:37.340Z - info: Running on ios test: 100. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-16T10:21:37.503Z - info: Running on android test: 88. we properly enqueue requests so no then needed

2016-03-16T10:21:37.835Z - info: Running on ios test: 101. #stop can be called multiple times in a row

2016-03-16T10:21:38.140Z - info: Running on android test: 89. test calculateSeqPointKeyId

2016-03-16T10:21:38.400Z - info: Running on ios test: 102. #startListeningForAdvertisements can be called multiple times in a row

2016-03-16T10:21:38.586Z - info: Running on android test: 90. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-16T10:21:38.845Z - info: Running on ios test: 103. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-16T10:21:38.963Z - info: Running on android test: 91. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-16T10:21:39.288Z - info: Running on ios test: 104. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-16T10:21:39.682Z - info: Running on ios test: 105. functions are run from a queue in the right order

2016-03-16T10:21:39.904Z - info: Running on android test: 92. messages with invalid location or USN should be ignored

2016-03-16T10:21:40.219Z - info: Running on ios test: 106. #ThaliPeerPoolDefault - single action

2016-03-16T10:21:40.345Z - info: Running on android test: 93. verify that Thali-specific messages are filtered correctly

2016-03-16T10:21:40.676Z - info: Running on ios test: 107. #ThaliPeerPoolDefault - multiple actions

2016-03-16T10:21:40.957Z - info: Running on android test: 94. #startListeningForAdvertisements should fail if start not called

2016-03-16T10:21:41.147Z - info: Test run on ios complete

2016-03-16T10:21:41.149Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-16T10:21:41.152Z - info: PLATFORM: ios

2016-03-16T10:21:41.152Z - info: RESULT: PASS

2016-03-16T10:21:41.154Z - info: 107 of 107 tests completed

2016-03-16T10:21:41.155Z - info: 107/107 passed (0 failures)
2016-03-16T10:21:41.155Z - info: --- Test Details ---



2016-03-16T10:21:41.156Z - info: 1. calling createNativeListener directly rejects - pass

2016-03-16T10:21:41.157Z - info: 2. emits incomingConnectionState - pass
2016-03-16T10:21:41.158Z - info: 3. emits routerPortConnectionFailed - pass

2016-03-16T10:21:41.159Z - info: 4. native server connections all up - pass

2016-03-16T10:21:41.160Z - info: 5. native server - closing incoming stream cleans outgoing socket - pass
2016-03-16T10:21:41.160Z - info: 6. native server - closing incoming connection cleans outgoing socket - pass

2016-03-16T10:21:41.161Z - info: 7. native server - closing outgoing socket cleans associated mux stream - pass
2016-03-16T10:21:41.162Z - info: 8. native server - closing the whole server cleans everything up - pass

2016-03-16T10:21:41.163Z - info: 9. native server - we can get a ton of connections and data through and still clean up the server completely - pass

2016-03-16T10:21:41.163Z - info: 10. native server - simulate mux failure, make sure everything is cleaned up - pass
2016-03-16T10:21:41.164Z - info: 11. native server - timing out the incoming connection cleans everything up - pass

2016-03-16T10:21:41.165Z - info: 12. closeAll can close even when connections open - pass
2016-03-16T10:21:41.166Z - info: 13. closeAll with promise - pass

2016-03-16T10:21:41.166Z - info: 14. multiplex can send data - pass
2016-03-16T10:21:41.167Z - info: 15. enqueue and run in order - pass

2016-03-16T10:21:41.168Z - info: 16. enqueueAtTop and run backwards - pass

2016-03-16T10:21:41.169Z - info: 17. mix enqueue and enqueueAtTop - pass
2016-03-16T10:21:41.169Z - info: 18. queues handled independently - pass

2016-03-16T10:21:41.170Z - info: 19. basic - pass
2016-03-16T10:21:41.171Z - info: 20. another - pass

2016-03-16T10:21:41.172Z - info: 21. #startListeningForAdvertisements should fail if start not called - pass

2016-03-16T10:21:41.172Z - info: 22. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-16T10:21:41.173Z - info: 23. should be able to call #stopListeningForAdvertisements many times - pass

2016-03-16T10:21:41.174Z - info: 24. should be able to call #startListeningForAdvertisements many times - pass
2016-03-16T10:21:41.175Z - info: 25. should be able to call #startUpdateAdvertisingAndListening many times - pass

2016-03-16T10:21:41.175Z - info: 26. should be able to call #stopAdvertisingAndListening many times - pass
2016-03-16T10:21:41.176Z - info: 27. #start should fail if called twice in a row - pass

2016-03-16T10:21:41.177Z - info: 28. does not emit duplicate discoveryAdvertisingStateUpdate - pass
2016-03-16T10:21:41.178Z - info: 29. does not send duplicate availability changes - pass
2016-03-16T10:21:41.178Z - info: 30. can get the network status - pass
2016-03-16T10:21:41.179Z - info: 31. wifi peer is marked unavailable if announcements stop - pass

2016-03-16T10:21:41.180Z - info: 32. can get the network status before starting - pass
2016-03-16T10:21:41.181Z - info: 33. #generatePreambleAndBeacons bad args - pass

2016-03-16T10:21:41.181Z - info: 34. #generatePreambleAndBeacons empty keys to notify - pass
2016-03-16T10:21:41.182Z - info: 35. #generatePreambleAndBeacons multiple keys to notify - pass

2016-03-16T10:21:41.183Z - info: 36. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass

2016-03-16T10:21:41.184Z - info: 37. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass
2016-03-16T10:21:41.185Z - info: 38. #parseBeacons expiration out of range lower - pass

2016-03-16T10:21:41.185Z - info: 39. #parseBeacons expiration out of range lower - pass

2016-03-16T10:21:41.186Z - info: 40. #parseBeacons no beacons returns null - pass
2016-03-16T10:21:41.187Z - info: 41. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass

2016-03-16T10:21:41.188Z - info: 42. #parseBeacons addressBookCallback fails decrypt - pass
2016-03-16T10:21:41.188Z - info: 43. #parseBeacons addressBookCallback returns no matches - pass

2016-03-16T10:21:41.189Z - info: 44. #parseBeacons addressBookCallback returns spurious match - pass
2016-03-16T10:21:41.190Z - info: 45. #parseBeacons addressBookCallback returns public key - pass

2016-03-16T10:21:41.191Z - info: 46. #parseBeacons with beacons both for and not for the user - pass
2016-03-16T10:21:41.191Z - info: 47. Start and stop ThaliNotificationServer - pass

2016-03-16T10:21:41.192Z - info: 48. Pass an empty array to ThaliNotificationServer.start - pass
2016-03-16T10:21:41.193Z - info: 49. Pass a string to ThaliNotificationServer.start - pass

2016-03-16T10:21:41.193Z - info: 50. Pass an empty parameter to ThaliNotificationServer.start - pass
2016-03-16T10:21:41.194Z - info: 51. Make an HTTP request to /NotificationBeacons - pass

2016-03-16T10:21:41.195Z - info: 52. Make an HTTP request to /NotificationBeacons (no keys) - pass
2016-03-16T10:21:41.195Z - info: 53. Make an HTTP request to /NotificationBeacons before calling start - pass

2016-03-16T10:21:41.196Z - info: 54. #testThaliPeerAction - test getters - pass

2016-03-16T10:21:41.197Z - info: 55. #testThaliPeerAction - start and kill - pass
2016-03-16T10:21:41.198Z - info: 56. #testThaliPeerAction - double start - pass

2016-03-16T10:21:41.198Z - info: 57. #testThaliPeerAction - start after kill - pass
2016-03-16T10:21:41.199Z - info: 58. #testThaliPeerAction - make sure ids are unique - pass
2016-03-16T10:21:41.200Z - info: 59. Test PeerConnectionInformation basics - pass
2016-03-16T10:21:41.201Z - info: 60. Test PeerDictionary basic functionality - pass
2016-03-16T10:21:41.201Z - info: 61. Test PeerDictionary with multiple entries. - pass
2016-03-16T10:21:41.202Z - info: 62. RESOLVED entries are removed before WAITING state entry. - pass
2016-03-16T10:21:41.203Z - info: 63. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass
2016-03-16T10:21:41.203Z - info: 64. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass
2016-03-16T10:21:41.204Z - info: 65. #ThaliPeerPoolInterface - bad enqueues - pass
2016-03-16T10:21:41.205Z - info: 66. #ThaliPeerPoolInterface - do not allow same object type - pass
2016-03-16T10:21:41.205Z - info: 67. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass
2016-03-16T10:21:41.209Z - info: 68. compareBufferArrays - pass
2016-03-16T10:21:41.210Z - info: 69. Call start twice and get error - pass
2016-03-16T10:21:41.211Z - info: 70. Start and make sure it runs - pass

2016-03-16T10:21:41.212Z - info: 71. Make sure getTimeWhenRun is right after start - pass
2016-03-16T10:21:41.212Z - info: 72. Make sure getTimeWhenRun is -1 after function is called - pass

2016-03-16T10:21:41.213Z - info: 73. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass
2016-03-16T10:21:41.214Z - info: 74. Test TransientState - pass

2016-03-16T10:21:41.215Z - info: 75. No peers and empty database - pass

2016-03-16T10:21:41.216Z - info: 76. One peer and empty DB - pass

2016-03-16T10:21:41.216Z - info: 77. One peer with _Local set behind current seq - pass
2016-03-16T10:21:41.217Z - info: 78. One peer with _Local set equal to current seq - pass

2016-03-16T10:21:41.218Z - info: 79. One peer with _Local set ahead of current seq (and no this should not happen) - pass
2016-03-16T10:21:41.218Z - info: 80. Three peers, one not in DB, one behind and one ahead - pass

2016-03-16T10:21:41.219Z - info: 81. More than maximum peers, make sure we only send maximum allowed - pass

2016-03-16T10:21:41.220Z - info: 82. two peers with empty DB, update the doc - pass

2016-03-16T10:21:41.221Z - info: 83. add doc and make sure tokens refresh when they expire - pass
2016-03-16T10:21:41.221Z - info: 84. start and stop and start and stop - pass

2016-03-16T10:21:41.222Z - info: 85. two identical starts in a row - pass

2016-03-16T10:21:41.223Z - info: 86. two different starts in a row - pass

2016-03-16T10:21:41.224Z - info: 87. two stops and a start and two stops - pass
2016-03-16T10:21:41.224Z - info: 88. we properly enqueue requests so no then needed - pass

2016-03-16T10:21:41.225Z - info: 89. test calculateSeqPointKeyId - pass

2016-03-16T10:21:41.226Z - info: 90. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass
2016-03-16T10:21:41.226Z - info: 91. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-03-16T10:21:41.227Z - info: 92. messages with invalid location or USN should be ignored - pass

2016-03-16T10:21:41.228Z - info: 93. verify that Thali-specific messages are filtered correctly - pass

2016-03-16T10:21:41.229Z - info: 94. #startListeningForAdvertisements should fail if start not called - pass
2016-03-16T10:21:41.229Z - info: 95. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-16T10:21:41.230Z - info: 96. #start should fail if called twice in a row - pass

2016-03-16T10:21:41.231Z - info: 97. should not be started after stop is called - pass

2016-03-16T10:21:41.232Z - info: 98. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass
2016-03-16T10:21:41.232Z - info: 99. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass

2016-03-16T10:21:41.233Z - info: 100. #startUpdateAdvertisingAndListening should start hosting given router object - pass

2016-03-16T10:21:41.234Z - info: 101. #stop can be called multiple times in a row - pass

2016-03-16T10:21:41.235Z - info: 102. #startListeningForAdvertisements can be called multiple times in a row - pass
2016-03-16T10:21:41.235Z - info: 103. #stopListeningForAdvertisements can be called multiple times in a row - pass

2016-03-16T10:21:41.236Z - info: 104. #stopAdvertisingAndListening can be called multiple times in a row - pass

2016-03-16T10:21:41.237Z - info: 105. functions are run from a queue in the right order - pass
2016-03-16T10:21:41.237Z - info: 106. #ThaliPeerPoolDefault - single action - pass

2016-03-16T10:21:41.238Z - info: 107. #ThaliPeerPoolDefault - multiple actions - pass

2016-03-16T10:21:41.239Z - info: 

-== END ==-

2016-03-16T10:21:41.894Z - info: Running on android test: 95. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-16T10:21:42.171Z - info: Running on android test: 96. #start should fail if called twice in a row

2016-03-16T10:21:42.701Z - info: Running on android test: 97. should not be started after stop is called

2016-03-16T10:21:42.991Z - info: Running on android test: 98. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-16T10:21:43.322Z - info: Running on android test: 99. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-16T10:21:43.754Z - info: Running on android test: 100. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-16T10:21:43.788Z - debug: Socket disconnected: transport close 2 (Apple-Iphone6-1)

2016-03-16T10:21:44.049Z - debug: Socket disconnected: transport close 1 (Apple-IpadAir2-1)

2016-03-16T10:21:44.193Z - info: Running on android test: 101. #stop can be called multiple times in a row

2016-03-16T10:21:44.663Z - info: Running on android test: 102. #startListeningForAdvertisements can be called multiple times in a row

2016-03-16T10:21:45.087Z - info: Running on android test: 103. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-16T10:21:45.497Z - info: Running on android test: 104. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-16T10:21:46.114Z - info: Running on android test: 105. functions are run from a queue in the right order

2016-03-16T10:21:46.478Z - info: Running on android test: 106. #ThaliPeerPoolDefault - single action

2016-03-16T10:21:46.824Z - info: Running on android test: 107. #ThaliPeerPoolDefault - multiple actions

2016-03-16T10:21:47.195Z - info: Test run on android complete

2016-03-16T10:21:47.196Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-16T10:21:47.197Z - info: PLATFORM: android

2016-03-16T10:21:47.198Z - info: RESULT: PASS

2016-03-16T10:21:47.200Z - info: 107 of 107 tests completed

2016-03-16T10:21:47.201Z - info: 107/107 passed (0 failures)

2016-03-16T10:21:47.202Z - info: --- Test Details ---



2016-03-16T10:21:47.202Z - info: 1. calling createNativeListener directly rejects - pass

2016-03-16T10:21:47.203Z - info: 2. emits incomingConnectionState - pass

2016-03-16T10:21:47.204Z - info: 3. emits routerPortConnectionFailed - pass
2016-03-16T10:21:47.205Z - info: 4. native server connections all up - pass

2016-03-16T10:21:47.206Z - info: 5. native server - closing incoming stream cleans outgoing socket - pass

2016-03-16T10:21:47.207Z - info: 6. native server - closing incoming connection cleans outgoing socket - pass

2016-03-16T10:21:47.207Z - info: 7. native server - closing outgoing socket cleans associated mux stream - pass

2016-03-16T10:21:47.208Z - info: 8. native server - closing the whole server cleans everything up - pass
2016-03-16T10:21:47.209Z - info: 9. native server - we can get a ton of connections and data through and still clean up the server completely - pass

2016-03-16T10:21:47.210Z - info: 10. native server - simulate mux failure, make sure everything is cleaned up - pass

2016-03-16T10:21:47.210Z - info: 11. native server - timing out the incoming connection cleans everything up - pass

2016-03-16T10:21:47.211Z - info: 12. closeAll can close even when connections open - pass
2016-03-16T10:21:47.212Z - info: 13. closeAll with promise - pass

2016-03-16T10:21:47.213Z - info: 14. multiplex can send data - pass

2016-03-16T10:21:47.214Z - info: 15. enqueue and run in order - pass

2016-03-16T10:21:47.215Z - info: 16. enqueueAtTop and run backwards - pass

2016-03-16T10:21:47.216Z - info: 17. mix enqueue and enqueueAtTop - pass

2016-03-16T10:21:47.216Z - info: 18. queues handled independently - pass
2016-03-16T10:21:47.217Z - info: 19. basic - pass

2016-03-16T10:21:47.218Z - info: 20. another - pass

2016-03-16T10:21:47.219Z - info: 21. #startListeningForAdvertisements should fail if start not called - pass

2016-03-16T10:21:47.220Z - info: 22. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-16T10:21:47.220Z - info: 23. should be able to call #stopListeningForAdvertisements many times - pass

2016-03-16T10:21:47.222Z - info: 24. should be able to call #startListeningForAdvertisements many times - pass

2016-03-16T10:21:47.223Z - info: 25. should be able to call #startUpdateAdvertisingAndListening many times - pass

2016-03-16T10:21:47.224Z - info: 26. should be able to call #stopAdvertisingAndListening many times - pass

2016-03-16T10:21:47.232Z - info: 27. #start should fail if called twice in a row - pass

2016-03-16T10:21:47.233Z - info: 28. does not emit duplicate discoveryAdvertisingStateUpdate - pass

2016-03-16T10:21:47.234Z - info: 29. does not send duplicate availability changes - pass
2016-03-16T10:21:47.234Z - info: 30. can get the network status - pass

2016-03-16T10:21:47.235Z - info: 31. wifi peer is marked unavailable if announcements stop - pass

2016-03-16T10:21:47.236Z - info: 32. can get the network status before starting - pass

2016-03-16T10:21:47.237Z - info: 33. #generatePreambleAndBeacons bad args - pass

2016-03-16T10:21:47.238Z - info: 34. #generatePreambleAndBeacons empty keys to notify - pass
2016-03-16T10:21:47.239Z - info: 35. #generatePreambleAndBeacons multiple keys to notify - pass

2016-03-16T10:21:47.239Z - info: 36. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass

2016-03-16T10:21:47.240Z - info: 37. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass

2016-03-16T10:21:47.273Z - info: 38. #parseBeacons expiration out of range lower - pass

2016-03-16T10:21:47.274Z - info: 39. #parseBeacons expiration out of range lower - pass

2016-03-16T10:21:47.275Z - info: 40. #parseBeacons no beacons returns null - pass

2016-03-16T10:21:47.276Z - info: 41. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass
2016-03-16T10:21:47.277Z - info: 42. #parseBeacons addressBookCallback fails decrypt - pass

2016-03-16T10:21:47.278Z - info: 43. #parseBeacons addressBookCallback returns no matches - pass

2016-03-16T10:21:47.279Z - info: 44. #parseBeacons addressBookCallback returns spurious match - pass

2016-03-16T10:21:47.279Z - info: 45. #parseBeacons addressBookCallback returns public key - pass
2016-03-16T10:21:47.280Z - info: 46. #parseBeacons with beacons both for and not for the user - pass

2016-03-16T10:21:47.281Z - info: 47. Start and stop ThaliNotificationServer - pass

2016-03-16T10:21:47.282Z - info: 48. Pass an empty array to ThaliNotificationServer.start - pass

2016-03-16T10:21:47.282Z - info: 49. Pass a string to ThaliNotificationServer.start - pass
2016-03-16T10:21:47.283Z - info: 50. Pass an empty parameter to ThaliNotificationServer.start - pass

2016-03-16T10:21:47.284Z - info: 51. Make an HTTP request to /NotificationBeacons - pass

2016-03-16T10:21:47.285Z - info: 52. Make an HTTP request to /NotificationBeacons (no keys) - pass

2016-03-16T10:21:47.285Z - info: 53. Make an HTTP request to /NotificationBeacons before calling start - pass
2016-03-16T10:21:47.286Z - info: 54. #testThaliPeerAction - test getters - pass

2016-03-16T10:21:47.287Z - info: 55. #testThaliPeerAction - start and kill - pass

2016-03-16T10:21:47.288Z - info: 56. #testThaliPeerAction - double start - pass

2016-03-16T10:21:47.288Z - info: 57. #testThaliPeerAction - start after kill - pass
2016-03-16T10:21:47.289Z - info: 58. #testThaliPeerAction - make sure ids are unique - pass

2016-03-16T10:21:47.290Z - info: 59. Test PeerConnectionInformation basics - pass

2016-03-16T10:21:47.291Z - info: 60. Test PeerDictionary basic functionality - pass

2016-03-16T10:21:47.291Z - info: 61. Test PeerDictionary with multiple entries. - pass
2016-03-16T10:21:47.292Z - info: 62. RESOLVED entries are removed before WAITING state entry. - pass

2016-03-16T10:21:47.293Z - info: 63. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass

2016-03-16T10:21:47.294Z - info: 64. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass

2016-03-16T10:21:47.295Z - info: 65. #ThaliPeerPoolInterface - bad enqueues - pass

2016-03-16T10:21:47.295Z - info: 66. #ThaliPeerPoolInterface - do not allow same object type - pass
2016-03-16T10:21:47.296Z - info: 67. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass

2016-03-16T10:21:47.297Z - info: 68. compareBufferArrays - pass

2016-03-16T10:21:47.298Z - info: 69. Call start twice and get error - pass

2016-03-16T10:21:47.298Z - info: 70. Start and make sure it runs - pass
2016-03-16T10:21:47.299Z - info: 71. Make sure getTimeWhenRun is right after start - pass

2016-03-16T10:21:47.300Z - info: 72. Make sure getTimeWhenRun is -1 after function is called - pass

2016-03-16T10:21:47.301Z - info: 73. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass

2016-03-16T10:21:47.301Z - info: 74. Test TransientState - pass
2016-03-16T10:21:47.302Z - info: 75. No peers and empty database - pass

2016-03-16T10:21:47.303Z - info: 76. One peer and empty DB - pass

2016-03-16T10:21:47.304Z - info: 77. One peer with _Local set behind current seq - pass

2016-03-16T10:21:47.304Z - info: 78. One peer with _Local set equal to current seq - pass

2016-03-16T10:21:47.305Z - info: 79. One peer with _Local set ahead of current seq (and no this should not happen) - pass
2016-03-16T10:21:47.306Z - info: 80. Three peers, one not in DB, one behind and one ahead - pass

2016-03-16T10:21:47.307Z - info: 81. More than maximum peers, make sure we only send maximum allowed - pass

2016-03-16T10:21:47.307Z - info: 82. two peers with empty DB, update the doc - pass
2016-03-16T10:21:47.308Z - info: 83. add doc and make sure tokens refresh when they expire - pass

2016-03-16T10:21:47.309Z - info: 84. start and stop and start and stop - pass

2016-03-16T10:21:47.310Z - info: 85. two identical starts in a row - pass

2016-03-16T10:21:47.311Z - info: 86. two different starts in a row - pass
2016-03-16T10:21:47.311Z - info: 87. two stops and a start and two stops - pass

2016-03-16T10:21:47.312Z - info: 88. we properly enqueue requests so no then needed - pass
2016-03-16T10:21:47.313Z - info: 89. test calculateSeqPointKeyId - pass
2016-03-16T10:21:47.314Z - info: 90. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass
2016-03-16T10:21:47.314Z - info: 91. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass
2016-03-16T10:21:47.315Z - info: 92. messages with invalid location or USN should be ignored - pass
2016-03-16T10:21:47.315Z - info: 93. verify that Thali-specific messages are filtered correctly - pass
2016-03-16T10:21:47.316Z - info: 94. #startListeningForAdvertisements should fail if start not called - pass

2016-03-16T10:21:47.316Z - info: 95. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-16T10:21:47.317Z - info: 96. #start should fail if called twice in a row - pass
2016-03-16T10:21:47.317Z - info: 97. should not be started after stop is called - pass
2016-03-16T10:21:47.318Z - info: 98. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass
2016-03-16T10:21:47.319Z - info: 99. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass
2016-03-16T10:21:47.319Z - info: 100. #startUpdateAdvertisingAndListening should start hosting given router object - pass
2016-03-16T10:21:47.320Z - info: 101. #stop can be called multiple times in a row - pass
2016-03-16T10:21:47.320Z - info: 102. #startListeningForAdvertisements can be called multiple times in a row - pass
2016-03-16T10:21:47.321Z - info: 103. #stopListeningForAdvertisements can be called multiple times in a row - pass
2016-03-16T10:21:47.321Z - info: 104. #stopAdvertisingAndListening can be called multiple times in a row - pass
2016-03-16T10:21:47.322Z - info: 105. functions are run from a queue in the right order - pass
2016-03-16T10:21:47.322Z - info: 106. #ThaliPeerPoolDefault - single action - pass
2016-03-16T10:21:47.323Z - info: 107. #ThaliPeerPoolDefault - multiple actions - pass
2016-03-16T10:21:47.323Z - info: 

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
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/630369953a3bebd_Use_a_custom_build_of_jxcore-cordova_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali03
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Android task is completed. [SUCCESS]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/630369953a3bebd_Use_a_custom_build_of_jxcore-cordova_vjrantal/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on ZX1C223JKW 
Android task is completed. [SUCCESS]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/630369953a3bebd_Use_a_custom_build_of_jxcore-cordova_vjrantal/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Android task is completed. [SUCCESS]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/630369953a3bebd_Use_a_custom_build_of_jxcore-cordova_vjrantal/thali05_LGE-LG-H815.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/630369953a3bebd_Use_a_custom_build_of_jxcore-cordova_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/630369953a3bebd_Use_a_custom_build_of_jxcore-cordova_vjrantal/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:0 
child process exited with code 0 on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/630369953a3bebd_Use_a_custom_build_of_jxcore-cordova_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:0 
child process exited with code 0 on device 4325e43f 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/630369953a3bebd_Use_a_custom_build_of_jxcore-cordova_vjrantal/thali08_samsung-SM-A300FU.md)




###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/630369953a3bebd_Use_a_custom_build_of_jxcore-cordova_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/630369953a3bebd_Use_a_custom_build_of_jxcore-cordova_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/630369953a3bebd_Use_a_custom_build_of_jxcore-cordova_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/630369953a3bebd_Use_a_custom_build_of_jxcore-cordova_vjrantal/iOS_Iphone5s-1.md)



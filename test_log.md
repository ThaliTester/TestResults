#### Test 627544039ea0a99 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":8}}
2016-03-17T11:58:39.901Z - info: listening on *:3000

2016-03-17T11:58:40.713Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:0

2016-03-17T11:58:42.140Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:1

2016-03-17T11:58:42.143Z - info: Required number of ios devices presented (2)

2016-03-17T11:58:42.147Z - info: Starting unit test run for platform: ios

2016-03-17T11:58:42.439Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:2

2016-03-17T11:58:42.440Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-17T11:58:42.752Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-17T11:58:44.305Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:3

2016-03-17T11:58:44.874Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:4

2016-03-17T11:58:44.876Z - info: Required number of android devices presented (2)

2016-03-17T11:58:44.877Z - info: Starting unit test run for platform: android

2016-03-17T11:58:45.020Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-17T11:58:45.231Z - debug: Socket disconnected: transport close 2 (Apple-Iphone5s-1)

2016-03-17T11:58:45.370Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-17T11:58:45.545Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-17T11:58:45.744Z - info: Running on ios test: 4. native server connections all up

2016-03-17T11:58:45.971Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-17T11:58:46.717Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-17T11:58:46.800Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-17T11:58:47.665Z - info: Running on android test: 4. native server connections all up

2016-03-17T11:58:47.859Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-17T11:58:48.315Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-17T11:58:48.872Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-17T11:58:49.335Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-17T11:58:49.506Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-17T11:58:50.424Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-17T11:58:51.448Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-17T11:58:51.472Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-17T11:58:52.454Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-17T11:58:52.847Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-17T11:58:53.004Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-17T11:58:53.284Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-17T11:58:53.628Z - info: Running on android test: 13. closeAll with promise

2016-03-17T11:58:53.792Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-17T11:58:53.864Z - info: Running on android test: 14. multiplex can send data

2016-03-17T11:58:54.108Z - info: Running on android test: 15. enqueue and run in order

2016-03-17T11:58:54.903Z - info: Running on android test: 16. enqueueAtTop and run backwards

2016-03-17T11:58:55.274Z - info: Running on android test: 17. mix enqueue and enqueueAtTop

2016-03-17T11:58:55.842Z - info: Running on android test: 18. queues handled independently

2016-03-17T11:58:56.199Z - info: Running on android test: 19. basic

2016-03-17T11:58:56.574Z - info: Running on android test: 20. another

2016-03-17T11:58:58.288Z - info: Running on android test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-17T11:58:58.632Z - info: Running on android test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-17T11:59:00.127Z - info: Running on android test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-17T11:59:00.481Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-17T11:59:02.797Z - info: Running on android test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-17T11:59:04.448Z - info: Running on android test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-17T11:59:04.973Z - info: Running on android test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-17T11:59:05.301Z - info: Running on android test: 27. #start should fail if called twice in a row

2016-03-17T11:59:05.707Z - info: Running on android test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-17T11:59:06.141Z - info: Running on android test: 29. does not send duplicate availability changes

2016-03-17T11:59:06.410Z - info: Running on android test: 30. can get the network status

2016-03-17T11:59:06.704Z - info: Running on android test: 31. wifi peer is marked unavailable if announcements stop

2016-03-17T11:59:07.980Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-17T11:59:08.024Z - info: Running on android test: 32. can get the network status before starting

2016-03-17T11:59:08.300Z - info: Running on android test: 33. Test BEACONS_RETRIEVED_AND_PARSED locally

2016-03-17T11:59:09.412Z - info: Running on android test: 34. Test HTTP_BAD_RESPONSE locally

2016-03-17T11:59:11.390Z - info: Running on android test: 35. Test NETWORK_PROBLEM locally

2016-03-17T11:59:12.585Z - info: Running on android test: 36. Test timeout locally

2016-03-17T11:59:14.136Z - info: Running on android test: 37. Call the start two times

2016-03-17T11:59:14.417Z - info: Running on ios test: 13. closeAll with promise

2016-03-17T11:59:14.672Z - info: Running on android test: 38. Call the kill before calling the start

2016-03-17T11:59:15.943Z - info: Running on android test: 39. Call the kill immediately after the start

2016-03-17T11:59:16.248Z - info: Running on ios test: 14. multiplex can send data

2016-03-17T11:59:16.429Z - info: Running on android test: 40. Call the kill while waiting a response from the server

2016-03-17T11:59:16.784Z - info: Running on ios test: 15. enqueue and run in order

2016-03-17T11:59:17.349Z - info: Running on ios test: 16. enqueueAtTop and run backwards

2016-03-17T11:59:17.730Z - info: Running on ios test: 17. mix enqueue and enqueueAtTop

2016-03-17T11:59:18.213Z - info: Running on ios test: 18. queues handled independently

2016-03-17T11:59:18.612Z - info: Running on ios test: 19. basic

2016-03-17T11:59:18.931Z - info: Running on android test: 41. Test to exceed the max content size locally

2016-03-17T11:59:18.949Z - info: Running on ios test: 20. another

2016-03-17T11:59:19.296Z - info: Running on ios test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-17T11:59:19.523Z - info: Running on android test: 42. Close the server socket while the client is waiting a response from the server. Local test.

2016-03-17T11:59:19.716Z - info: Running on ios test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-17T11:59:20.123Z - info: Running on ios test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-17T11:59:20.463Z - info: Running on ios test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-17T11:59:20.856Z - info: Running on ios test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-17T11:59:21.225Z - info: Running on ios test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-17T11:59:21.537Z - info: Running on ios test: 27. #start should fail if called twice in a row

2016-03-17T11:59:21.871Z - info: Running on ios test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-17T11:59:22.047Z - info: Running on android test: 43. Close the client socket while the client is waiting a response from the server. Local test.

2016-03-17T11:59:22.214Z - info: Running on ios test: 29. does not send duplicate availability changes

2016-03-17T11:59:22.528Z - info: Running on ios test: 30. can get the network status

2016-03-17T11:59:22.827Z - info: Running on ios test: 31. wifi peer is marked unavailable if announcements stop

2016-03-17T11:59:24.295Z - info: Running on ios test: 32. can get the network status before starting

2016-03-17T11:59:24.656Z - info: Running on ios test: 33. Test BEACONS_RETRIEVED_AND_PARSED locally

2016-03-17T11:59:24.919Z - info: Running on android test: 44. #generatePreambleAndBeacons bad args

2016-03-17T11:59:25.179Z - info: Running on ios test: 34. Test HTTP_BAD_RESPONSE locally

2016-03-17T11:59:25.317Z - info: Running on android test: 45. #generatePreambleAndBeacons empty keys to notify

2016-03-17T11:59:25.639Z - info: Running on ios test: 35. Test NETWORK_PROBLEM locally

2016-03-17T11:59:25.692Z - info: Running on android test: 46. #generatePreambleAndBeacons multiple keys to notify

2016-03-17T11:59:26.239Z - info: Running on android test: 47. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-17T11:59:26.589Z - info: Running on android test: 48. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-17T11:59:26.974Z - info: Running on android test: 49. #parseBeacons expiration out of range lower

2016-03-17T11:59:27.285Z - info: Running on ios test: 36. Test timeout locally

2016-03-17T11:59:27.363Z - info: Running on android test: 50. #parseBeacons expiration out of range lower

2016-03-17T11:59:27.653Z - info: Running on android test: 51. #parseBeacons no beacons returns null

2016-03-17T11:59:27.934Z - info: Running on android test: 52. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-17T11:59:28.824Z - info: Running on ios test: 37. Call the start two times

2016-03-17T11:59:29.125Z - info: Running on android test: 53. #parseBeacons addressBookCallback fails decrypt

2016-03-17T11:59:29.275Z - info: Running on ios test: 38. Call the kill before calling the start

2016-03-17T11:59:29.514Z - info: Running on android test: 54. #parseBeacons addressBookCallback returns no matches

2016-03-17T11:59:29.653Z - info: Running on ios test: 39. Call the kill immediately after the start

2016-03-17T11:59:29.977Z - info: Running on ios test: 40. Call the kill while waiting a response from the server

2016-03-17T11:59:29.981Z - info: Running on android test: 55. #parseBeacons addressBookCallback returns spurious match

2016-03-17T11:59:30.431Z - info: Running on android test: 56. #parseBeacons addressBookCallback returns public key

2016-03-17T11:59:30.965Z - info: Running on android test: 57. validate generatePskIdentityField

2016-03-17T11:59:31.355Z - info: Running on android test: 58. validate generatePskSecret

2016-03-17T11:59:31.814Z - info: Running on android test: 59. Start and stop ThaliNotificationServer

2016-03-17T11:59:32.417Z - info: Running on ios test: 41. Test to exceed the max content size locally

2016-03-17T11:59:32.466Z - info: Running on android test: 60. Pass an empty array to ThaliNotificationServer.start

2016-03-17T11:59:32.862Z - info: Running on ios test: 42. Close the server socket while the client is waiting a response from the server. Local test.

2016-03-17T11:59:32.895Z - info: Running on android test: 61. Pass a string to ThaliNotificationServer.start

2016-03-17T11:59:33.251Z - info: Running on android test: 62. Pass an empty parameter to ThaliNotificationServer.start

2016-03-17T11:59:33.731Z - info: Running on android test: 63. Make an HTTP request to /NotificationBeacons

2016-03-17T11:59:34.543Z - info: Running on android test: 64. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-17T11:59:34.889Z - info: Running on android test: 65. Make an HTTP request to /NotificationBeaconsbefore calling start

2016-03-17T11:59:35.205Z - info: Running on android test: 66. #testThaliPeerAction - test getters

2016-03-17T11:59:35.394Z - info: Running on ios test: 43. Close the client socket while the client is waiting a response from the server. Local test.

2016-03-17T11:59:35.577Z - info: Running on android test: 67. #testThaliPeerAction - start and kill

2016-03-17T11:59:36.111Z - info: Running on android test: 68. #testThaliPeerAction - double start

2016-03-17T11:59:36.661Z - info: Running on android test: 69. #testThaliPeerAction - start after kill

2016-03-17T11:59:37.090Z - info: Running on android test: 70. #testThaliPeerAction - make sure ids are unique

2016-03-17T11:59:37.489Z - info: Running on android test: 71. Test PeerConnectionInformation basics

2016-03-17T11:59:37.754Z - info: Running on android test: 72. Test PeerDictionary basic functionality

2016-03-17T11:59:38.069Z - info: Running on ios test: 44. #generatePreambleAndBeacons bad args

2016-03-17T11:59:38.139Z - info: Running on android test: 73. Test PeerDictionary with multiple entries.

2016-03-17T11:59:38.865Z - info: Running on ios test: 45. #generatePreambleAndBeacons empty keys to notify

2016-03-17T11:59:39.134Z - info: Running on ios test: 46. #generatePreambleAndBeacons multiple keys to notify

2016-03-17T11:59:39.528Z - info: Running on ios test: 47. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-17T11:59:39.716Z - info: Running on android test: 74. RESOLVED entries are removed before WAITING state entry.

2016-03-17T11:59:40.159Z - info: Running on ios test: 48. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-17T11:59:40.587Z - info: Running on ios test: 49. #parseBeacons expiration out of range lower

2016-03-17T11:59:40.773Z - info: Running on android test: 75. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-17T11:59:41.020Z - info: Running on ios test: 50. #parseBeacons expiration out of range lower

2016-03-17T11:59:41.355Z - info: Running on ios test: 51. #parseBeacons no beacons returns null

2016-03-17T11:59:41.774Z - info: Running on ios test: 52. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-17T11:59:42.133Z - info: Running on ios test: 53. #parseBeacons addressBookCallback fails decrypt

2016-03-17T11:59:42.322Z - info: Running on android test: 76. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-17T11:59:42.577Z - info: Running on ios test: 54. #parseBeacons addressBookCallback returns no matches

2016-03-17T11:59:42.975Z - info: Running on ios test: 55. #parseBeacons addressBookCallback returns spurious match

2016-03-17T11:59:43.233Z - info: Running on android test: 77. #ThaliPeerPoolInterface - bad enqueues

2016-03-17T11:59:43.467Z - info: Running on android test: 78. #ThaliPeerPoolInterface - do not allow same object type

2016-03-17T11:59:44.138Z - info: Running on android test: 79. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-17T11:59:44.395Z - info: Running on android test: 80. compareBufferArrays

2016-03-17T11:59:44.656Z - info: Running on android test: 81. Call start twice and get error

2016-03-17T11:59:44.953Z - info: Running on ios test: 56. #parseBeacons addressBookCallback returns public key

2016-03-17T11:59:45.086Z - info: Running on android test: 82. Start and make sure it runs

2016-03-17T11:59:45.396Z - info: Running on android test: 83. Make sure getTimeWhenRun is right after start

2016-03-17T11:59:45.922Z - info: Running on android test: 84. Make sure getTimeWhenRun is -1 after function is called

2016-03-17T11:59:46.257Z - info: Running on ios test: 57. validate generatePskIdentityField

2016-03-17T11:59:46.327Z - info: Running on android test: 85. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-17T11:59:46.684Z - info: Running on ios test: 58. validate generatePskSecret

2016-03-17T11:59:46.825Z - info: Running on android test: 86. Test TransientState

2016-03-17T11:59:47.648Z - info: Running on android test: 87. No peers and empty database

2016-03-17T11:59:48.226Z - info: Running on android test: 88. One peer and empty DB

2016-03-17T11:59:49.623Z - info: Running on android test: 89. One peer with _Local set behind current seq

2016-03-17T11:59:50.648Z - info: Running on ios test: 59. Start and stop ThaliNotificationServer

2016-03-17T11:59:51.337Z - info: Running on android test: 90. One peer with _Local set equal to current seq

2016-03-17T11:59:51.974Z - info: Running on android test: 91. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-17T11:59:52.550Z - info: Running on android test: 92. Three peers, one not in DB, one behind and one ahead

2016-03-17T11:59:52.878Z - info: Running on ios test: 60. Pass an empty array to ThaliNotificationServer.start

2016-03-17T11:59:53.775Z - info: Running on android test: 93. More than maximum peers, make sure we only send maximum allowed

2016-03-17T11:59:58.847Z - info: Running on android test: 94. two peers with empty DB, update the doc

2016-03-17T12:00:00.203Z - info: Running on ios test: 61. Pass a string to ThaliNotificationServer.start

2016-03-17T12:00:00.412Z - info: Running on android test: 95. add doc and make sure tokens refresh when they expire

2016-03-17T12:00:00.683Z - info: Running on ios test: 62. Pass an empty parameter to ThaliNotificationServer.start

2016-03-17T12:00:01.282Z - info: Running on ios test: 63. Make an HTTP request to /NotificationBeacons

2016-03-17T12:00:01.450Z - info: Running on android test: 96. start and stop and start and stop

2016-03-17T12:00:02.178Z - info: Running on android test: 97. two identical starts in a row

2016-03-17T12:00:02.226Z - info: Running on ios test: 64. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-17T12:00:02.766Z - info: Running on ios test: 65. Make an HTTP request to /NotificationBeaconsbefore calling start

2016-03-17T12:00:02.841Z - info: Running on android test: 98. two different starts in a row

2016-03-17T12:00:03.471Z - info: Running on ios test: 66. #testThaliPeerAction - test getters

2016-03-17T12:00:03.583Z - info: Running on android test: 99. two stops and a start and two stops

2016-03-17T12:00:03.854Z - info: Running on ios test: 67. #testThaliPeerAction - start and kill

2016-03-17T12:00:04.626Z - info: Running on android test: 100. we properly enqueue requests so no then needed

2016-03-17T12:00:04.713Z - info: Running on ios test: 68. #testThaliPeerAction - double start

2016-03-17T12:00:04.978Z - info: Running on ios test: 69. #testThaliPeerAction - start after kill

2016-03-17T12:00:05.137Z - info: Running on android test: 101. test calculateSeqPointKeyId

2016-03-17T12:00:05.350Z - info: Running on ios test: 70. #testThaliPeerAction - make sure ids are unique

2016-03-17T12:00:05.483Z - info: Running on android test: 102. can create servers manager

2016-03-17T12:00:05.785Z - info: Running on ios test: 71. Test PeerConnectionInformation basics

2016-03-17T12:00:05.902Z - info: Running on android test: 103. calling stop without start causes error

2016-03-17T12:00:06.142Z - info: Running on ios test: 72. Test PeerDictionary basic functionality

2016-03-17T12:00:06.253Z - info: Running on android test: 104. can start/stop servers manager

2016-03-17T12:00:07.077Z - info: Running on android test: 105. starting twice resolves with listening port

2016-03-17T12:00:07.272Z - info: Running on ios test: 73. Test PeerDictionary with multiple entries.

2016-03-17T12:00:07.580Z - info: Running on android test: 106. terminateIncomingConnection will terminate a connection

2016-03-17T12:00:08.038Z - info: Running on android test: 107. terminate an Outgoing connection will terminate the server

2016-03-17T12:00:08.418Z - info: Running on android test: 108. terminate an Outgoing connection with wrong arguments is not harmful

2016-03-17T12:00:08.864Z - info: Running on android test: 109. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-17T12:00:09.350Z - info: Running on android test: 110. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-17T12:00:09.816Z - info: Running on android test: 111. messages with invalid location or USN should be ignored

2016-03-17T12:00:10.123Z - info: Running on ios test: 74. RESOLVED entries are removed before WAITING state entry.

2016-03-17T12:00:10.426Z - info: Running on android test: 112. verify that Thali-specific messages are filtered correctly

2016-03-17T12:00:11.091Z - info: Running on android test: 113. #startListeningForAdvertisements should fail if start not called

2016-03-17T12:00:11.429Z - info: Running on android test: 114. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-17T12:00:11.637Z - info: Running on ios test: 75. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-17T12:00:11.841Z - info: Running on android test: 115. #start should fail if called twice in a row

2016-03-17T12:00:12.161Z - info: Running on android test: 116. should not be started after stop is called

2016-03-17T12:00:12.443Z - info: Running on android test: 117. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-17T12:00:12.708Z - info: Running on android test: 118. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-17T12:00:12.918Z - info: Running on ios test: 76. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-17T12:00:13.042Z - info: Running on android test: 119. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-17T12:00:13.544Z - info: Running on android test: 120. #stop can be called multiple times in a row

2016-03-17T12:00:13.991Z - info: Running on android test: 121. #startListeningForAdvertisements can be called multiple times in a row

2016-03-17T12:00:14.316Z - info: Running on ios test: 77. #ThaliPeerPoolInterface - bad enqueues

2016-03-17T12:00:14.406Z - info: Running on android test: 122. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-17T12:00:15.223Z - info: Running on android test: 123. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-17T12:00:15.279Z - info: Running on ios test: 78. #ThaliPeerPoolInterface - do not allow same object type

2016-03-17T12:00:15.611Z - info: Running on android test: 124. functions are run from a queue in the right order

2016-03-17T12:00:16.264Z - info: Running on ios test: 79. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-17T12:00:16.400Z - info: Running on android test: 125. #ThaliPeerPoolDefault - single action

2016-03-17T12:00:16.598Z - info: Running on ios test: 80. compareBufferArrays

2016-03-17T12:00:16.706Z - info: Running on android test: 126. #ThaliPeerPoolDefault - multiple actions

2016-03-17T12:00:16.929Z - info: Running on ios test: 81. Call start twice and get error

2016-03-17T12:00:17.123Z - info: Test run on android complete

2016-03-17T12:00:17.125Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-17T12:00:17.127Z - info: PLATFORM: android

2016-03-17T12:00:17.128Z - info: RESULT: PASS

2016-03-17T12:00:17.129Z - info: 126 of 126 tests completed
2016-03-17T12:00:17.130Z - info: 126/126 passed (0 failures)

2016-03-17T12:00:17.130Z - info: --- Test Details ---


2016-03-17T12:00:17.131Z - info: 1. calling createNativeListener directly rejects - pass

2016-03-17T12:00:17.132Z - info: 2. emits incomingConnectionState - pass

2016-03-17T12:00:17.132Z - info: 3. emits routerPortConnectionFailed - pass
2016-03-17T12:00:17.133Z - info: 4. native server connections all up - pass
2016-03-17T12:00:17.133Z - info: 5. native server - closing incoming stream cleans outgoing socket - pass

2016-03-17T12:00:17.134Z - info: 6. native server - closing incoming connection cleans outgoing socket - pass
2016-03-17T12:00:17.135Z - info: 7. native server - closing outgoing socket cleans associated mux stream - pass

2016-03-17T12:00:17.135Z - info: 8. native server - closing the whole server cleans everything up - pass

2016-03-17T12:00:17.136Z - info: 9. native server - we can get a ton of connections and data through and still clean up the server completely - pass
2016-03-17T12:00:17.136Z - info: 10. native server - simulate mux failure, make sure everything is cleaned up - pass

2016-03-17T12:00:17.137Z - info: 11. native server - timing out the incoming connection cleans everything up - pass
2016-03-17T12:00:17.138Z - info: 12. closeAll can close even when connections open - pass

2016-03-17T12:00:17.138Z - info: 13. closeAll with promise - pass
2016-03-17T12:00:17.139Z - info: 14. multiplex can send data - pass
2016-03-17T12:00:17.139Z - info: 15. enqueue and run in order - pass

2016-03-17T12:00:17.140Z - info: 16. enqueueAtTop and run backwards - pass
2016-03-17T12:00:17.140Z - info: 17. mix enqueue and enqueueAtTop - pass

2016-03-17T12:00:17.141Z - info: 18. queues handled independently - pass

2016-03-17T12:00:17.142Z - info: 19. basic - pass
2016-03-17T12:00:17.142Z - info: 20. another - pass

2016-03-17T12:00:17.143Z - info: 21. #startListeningForAdvertisements should fail if start not called - pass
2016-03-17T12:00:17.143Z - info: 22. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-17T12:00:17.144Z - info: 23. should be able to call #stopListeningForAdvertisements many times - pass
2016-03-17T12:00:17.144Z - info: 24. should be able to call #startListeningForAdvertisements many times - pass

2016-03-17T12:00:17.145Z - info: 25. should be able to call #startUpdateAdvertisingAndListening many times - pass
2016-03-17T12:00:17.146Z - info: 26. should be able to call #stopAdvertisingAndListening many times - pass

2016-03-17T12:00:17.146Z - info: 27. #start should fail if called twice in a row - pass
2016-03-17T12:00:17.147Z - info: 28. does not emit duplicate discoveryAdvertisingStateUpdate - pass

2016-03-17T12:00:17.147Z - info: 29. does not send duplicate availability changes - pass
2016-03-17T12:00:17.148Z - info: 30. can get the network status - pass

2016-03-17T12:00:17.149Z - info: 31. wifi peer is marked unavailable if announcements stop - pass
2016-03-17T12:00:17.149Z - info: 32. can get the network status before starting - pass
2016-03-17T12:00:17.150Z - info: 33. Test BEACONS_RETRIEVED_AND_PARSED locally - pass

2016-03-17T12:00:17.150Z - info: 34. Test HTTP_BAD_RESPONSE locally - pass
2016-03-17T12:00:17.151Z - info: 35. Test NETWORK_PROBLEM locally - pass
2016-03-17T12:00:17.152Z - info: 36. Test timeout locally - pass
2016-03-17T12:00:17.152Z - info: 37. Call the start two times - pass
2016-03-17T12:00:17.153Z - info: 38. Call the kill before calling the start - pass

2016-03-17T12:00:17.153Z - info: 39. Call the kill immediately after the start - pass
2016-03-17T12:00:17.154Z - info: 40. Call the kill while waiting a response from the server - pass

2016-03-17T12:00:17.155Z - info: 41. Test to exceed the max content size locally - pass
2016-03-17T12:00:17.155Z - info: 42. Close the server socket while the client is waiting a response from the server. Local test. - pass

2016-03-17T12:00:17.156Z - info: 43. Close the client socket while the client is waiting a response from the server. Local test. - pass
2016-03-17T12:00:17.156Z - info: 44. #generatePreambleAndBeacons bad args - pass
2016-03-17T12:00:17.157Z - info: 45. #generatePreambleAndBeacons empty keys to notify - pass

2016-03-17T12:00:17.158Z - info: 46. #generatePreambleAndBeacons multiple keys to notify - pass
2016-03-17T12:00:17.158Z - info: 47. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass

2016-03-17T12:00:17.159Z - info: 48. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass
2016-03-17T12:00:17.159Z - info: 49. #parseBeacons expiration out of range lower - pass

2016-03-17T12:00:17.160Z - info: 50. #parseBeacons expiration out of range lower - pass
2016-03-17T12:00:17.161Z - info: 51. #parseBeacons no beacons returns null - pass

2016-03-17T12:00:17.161Z - info: 52. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass
2016-03-17T12:00:17.162Z - info: 53. #parseBeacons addressBookCallback fails decrypt - pass

2016-03-17T12:00:17.162Z - info: 54. #parseBeacons addressBookCallback returns no matches - pass
2016-03-17T12:00:17.163Z - info: 55. #parseBeacons addressBookCallback returns spurious match - pass

2016-03-17T12:00:17.163Z - info: 56. #parseBeacons addressBookCallback returns public key - pass
2016-03-17T12:00:17.164Z - info: 57. validate generatePskIdentityField - pass

2016-03-17T12:00:17.164Z - info: 58. validate generatePskSecret - pass
2016-03-17T12:00:17.165Z - info: 59. Start and stop ThaliNotificationServer - pass

2016-03-17T12:00:17.166Z - info: 60. Pass an empty array to ThaliNotificationServer.start - pass
2016-03-17T12:00:17.166Z - info: 61. Pass a string to ThaliNotificationServer.start - pass

2016-03-17T12:00:17.167Z - info: 62. Pass an empty parameter to ThaliNotificationServer.start - pass
2016-03-17T12:00:17.167Z - info: 63. Make an HTTP request to /NotificationBeacons - pass

2016-03-17T12:00:17.168Z - info: 64. Make an HTTP request to /NotificationBeacons (no keys) - pass
2016-03-17T12:00:17.169Z - info: 65. Make an HTTP request to /NotificationBeaconsbefore calling start - pass

2016-03-17T12:00:17.169Z - info: 66. #testThaliPeerAction - test getters - pass
2016-03-17T12:00:17.170Z - info: 67. #testThaliPeerAction - start and kill - pass

2016-03-17T12:00:17.170Z - info: 68. #testThaliPeerAction - double start - pass
2016-03-17T12:00:17.171Z - info: 69. #testThaliPeerAction - start after kill - pass
2016-03-17T12:00:17.171Z - info: 70. #testThaliPeerAction - make sure ids are unique - pass
2016-03-17T12:00:17.172Z - info: 71. Test PeerConnectionInformation basics - pass
2016-03-17T12:00:17.176Z - info: 72. Test PeerDictionary basic functionality - pass
2016-03-17T12:00:17.176Z - info: 73. Test PeerDictionary with multiple entries. - pass
2016-03-17T12:00:17.177Z - info: 74. RESOLVED entries are removed before WAITING state entry. - pass
2016-03-17T12:00:17.178Z - info: 75. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass
2016-03-17T12:00:17.178Z - info: 76. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass
2016-03-17T12:00:17.179Z - info: 77. #ThaliPeerPoolInterface - bad enqueues - pass
2016-03-17T12:00:17.179Z - info: 78. #ThaliPeerPoolInterface - do not allow same object type - pass
2016-03-17T12:00:17.180Z - info: 79. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass
2016-03-17T12:00:17.180Z - info: 80. compareBufferArrays - pass
2016-03-17T12:00:17.181Z - info: 81. Call start twice and get error - pass
2016-03-17T12:00:17.181Z - info: 82. Start and make sure it runs - pass
2016-03-17T12:00:17.182Z - info: 83. Make sure getTimeWhenRun is right after start - pass
2016-03-17T12:00:17.182Z - info: 84. Make sure getTimeWhenRun is -1 after function is called - pass
2016-03-17T12:00:17.183Z - info: 85. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass
2016-03-17T12:00:17.183Z - info: 86. Test TransientState - pass
2016-03-17T12:00:17.184Z - info: 87. No peers and empty database - pass
2016-03-17T12:00:17.184Z - info: 88. One peer and empty DB - pass
2016-03-17T12:00:17.185Z - info: 89. One peer with _Local set behind current seq - pass
2016-03-17T12:00:17.185Z - info: 90. One peer with _Local set equal to current seq - pass
2016-03-17T12:00:17.186Z - info: 91. One peer with _Local set ahead of current seq (and no this should not happen) - pass

2016-03-17T12:00:17.186Z - info: 92. Three peers, one not in DB, one behind and one ahead - pass
2016-03-17T12:00:17.187Z - info: 93. More than maximum peers, make sure we only send maximum allowed - pass
2016-03-17T12:00:17.188Z - info: 94. two peers with empty DB, update the doc - pass

2016-03-17T12:00:17.188Z - info: 95. add doc and make sure tokens refresh when they expire - pass
2016-03-17T12:00:17.189Z - info: 96. start and stop and start and stop - pass

2016-03-17T12:00:17.190Z - info: 97. two identical starts in a row - pass
2016-03-17T12:00:17.190Z - info: 98. two different starts in a row - pass

2016-03-17T12:00:17.191Z - info: 99. two stops and a start and two stops - pass
2016-03-17T12:00:17.191Z - info: 100. we properly enqueue requests so no then needed - pass

2016-03-17T12:00:17.192Z - info: 101. test calculateSeqPointKeyId - pass
2016-03-17T12:00:17.192Z - info: 102. can create servers manager - pass

2016-03-17T12:00:17.193Z - info: 103. calling stop without start causes error - pass
2016-03-17T12:00:17.194Z - info: 104. can start/stop servers manager - pass

2016-03-17T12:00:17.194Z - info: 105. starting twice resolves with listening port - pass
2016-03-17T12:00:17.195Z - info: 106. terminateIncomingConnection will terminate a connection - pass

2016-03-17T12:00:17.195Z - info: 107. terminate an Outgoing connection will terminate the server - pass
2016-03-17T12:00:17.196Z - info: 108. terminate an Outgoing connection with wrong arguments is not harmful - pass

2016-03-17T12:00:17.196Z - info: 109. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass
2016-03-17T12:00:17.197Z - info: 110. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-03-17T12:00:17.198Z - info: 111. messages with invalid location or USN should be ignored - pass
2016-03-17T12:00:17.198Z - info: 112. verify that Thali-specific messages are filtered correctly - pass

2016-03-17T12:00:17.199Z - info: 113. #startListeningForAdvertisements should fail if start not called - pass
2016-03-17T12:00:17.199Z - info: 114. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-17T12:00:17.200Z - info: 115. #start should fail if called twice in a row - pass
2016-03-17T12:00:17.201Z - info: 116. should not be started after stop is called - pass

2016-03-17T12:00:17.201Z - info: 117. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass
2016-03-17T12:00:17.202Z - info: 118. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass

2016-03-17T12:00:17.202Z - info: 119. #startUpdateAdvertisingAndListening should start hosting given router object - pass
2016-03-17T12:00:17.203Z - info: 120. #stop can be called multiple times in a row - pass

2016-03-17T12:00:17.203Z - info: 121. #startListeningForAdvertisements can be called multiple times in a row - pass
2016-03-17T12:00:17.204Z - info: 122. #stopListeningForAdvertisements can be called multiple times in a row - pass

2016-03-17T12:00:17.205Z - info: 123. #stopAdvertisingAndListening can be called multiple times in a row - pass
2016-03-17T12:00:17.205Z - info: 124. functions are run from a queue in the right order - pass

2016-03-17T12:00:17.206Z - info: 125. #ThaliPeerPoolDefault - single action - pass
2016-03-17T12:00:17.206Z - info: 126. #ThaliPeerPoolDefault - multiple actions - pass

2016-03-17T12:00:17.207Z - info: 

-== END ==-

2016-03-17T12:00:17.699Z - info: Running on ios test: 82. Start and make sure it runs

2016-03-17T12:00:18.034Z - info: Running on ios test: 83. Make sure getTimeWhenRun is right after start

2016-03-17T12:00:18.315Z - info: Running on ios test: 84. Make sure getTimeWhenRun is -1 after function is called

2016-03-17T12:00:18.488Z - debug: Socket disconnected: transport close 4 (LGE-LG-H815)

2016-03-17T12:00:18.563Z - debug: Socket disconnected: transport close 3 (samsung-SM-N910C)

2016-03-17T12:00:18.596Z - info: Running on ios test: 85. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-17T12:00:19.013Z - info: Running on ios test: 86. Test TransientState

2016-03-17T12:00:19.487Z - info: Running on ios test: 87. No peers and empty database

2016-03-17T12:00:21.347Z - info: Running on ios test: 88. One peer and empty DB

2016-03-17T12:00:22.185Z - info: Running on ios test: 89. One peer with _Local set behind current seq

2016-03-17T12:00:23.111Z - info: Running on ios test: 90. One peer with _Local set equal to current seq

2016-03-17T12:00:24.444Z - info: Running on ios test: 91. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-17T12:00:25.077Z - info: Running on ios test: 92. Three peers, one not in DB, one behind and one ahead

2016-03-17T12:00:25.872Z - info: Running on ios test: 93. More than maximum peers, make sure we only send maximum allowed

2016-03-17T12:00:27.730Z - info: Running on ios test: 94. two peers with empty DB, update the doc

2016-03-17T12:00:28.648Z - info: Running on ios test: 95. add doc and make sure tokens refresh when they expire

2016-03-17T12:00:32.841Z - info: Running on ios test: 96. start and stop and start and stop

2016-03-17T12:00:34.898Z - info: Running on ios test: 97. two identical starts in a row

2016-03-17T12:00:35.530Z - info: Running on ios test: 98. two different starts in a row

2016-03-17T12:00:36.221Z - info: Running on ios test: 99. two stops and a start and two stops

2016-03-17T12:00:36.979Z - info: Running on ios test: 100. we properly enqueue requests so no then needed

2016-03-17T12:00:40.818Z - info: Running on ios test: 101. test calculateSeqPointKeyId

2016-03-17T12:00:49.573Z - info: Running on ios test: 102. can create servers manager

2016-03-17T12:00:51.368Z - info: Running on ios test: 103. calling stop without start causes error

2016-03-17T12:00:51.897Z - info: Running on ios test: 104. can start/stop servers manager

2016-03-17T12:00:53.097Z - info: Running on ios test: 105. starting twice resolves with listening port

2016-03-17T12:00:56.139Z - info: Running on ios test: 106. terminateIncomingConnection will terminate a connection

2016-03-17T12:00:56.487Z - info: Running on ios test: 107. terminate an Outgoing connection will terminate the server

2016-03-17T12:00:57.471Z - info: Running on ios test: 108. terminate an Outgoing connection with wrong arguments is not harmful

2016-03-17T12:00:57.844Z - info: Running on ios test: 109. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-17T12:00:58.195Z - info: Running on ios test: 110. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-17T12:00:58.636Z - info: Running on ios test: 111. messages with invalid location or USN should be ignored

2016-03-17T12:00:59.008Z - info: Running on ios test: 112. verify that Thali-specific messages are filtered correctly

2016-03-17T12:00:59.351Z - info: Running on ios test: 113. #startListeningForAdvertisements should fail if start not called

2016-03-17T12:00:59.593Z - info: Running on ios test: 114. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-17T12:00:59.966Z - info: Running on ios test: 115. #start should fail if called twice in a row

2016-03-17T12:01:00.310Z - info: Running on ios test: 116. should not be started after stop is called

2016-03-17T12:01:00.676Z - info: Running on ios test: 117. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-17T12:01:01.437Z - info: Running on ios test: 118. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-17T12:01:01.773Z - info: Running on ios test: 119. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-17T12:01:02.279Z - info: Running on ios test: 120. #stop can be called multiple times in a row

2016-03-17T12:01:02.565Z - info: Running on ios test: 121. #startListeningForAdvertisements can be called multiple times in a row

2016-03-17T12:01:02.953Z - info: Running on ios test: 122. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-17T12:01:03.253Z - info: Running on ios test: 123. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-17T12:01:03.548Z - info: Running on ios test: 124. functions are run from a queue in the right order

2016-03-17T12:01:03.875Z - info: Running on ios test: 125. #ThaliPeerPoolDefault - single action

2016-03-17T12:01:04.232Z - info: Running on ios test: 126. #ThaliPeerPoolDefault - multiple actions

2016-03-17T12:01:04.537Z - info: Test run on ios complete

2016-03-17T12:01:04.538Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-17T12:01:04.540Z - info: PLATFORM: ios

2016-03-17T12:01:04.541Z - info: RESULT: PASS

2016-03-17T12:01:04.542Z - info: 126 of 126 tests completed

2016-03-17T12:01:04.543Z - info: 126/126 passed (0 failures)

2016-03-17T12:01:04.544Z - info: --- Test Details ---



2016-03-17T12:01:04.545Z - info: 1. calling createNativeListener directly rejects - pass

2016-03-17T12:01:04.546Z - info: 2. emits incomingConnectionState - pass

2016-03-17T12:01:04.547Z - info: 3. emits routerPortConnectionFailed - pass
2016-03-17T12:01:04.548Z - info: 4. native server connections all up - pass

2016-03-17T12:01:04.549Z - info: 5. native server - closing incoming stream cleans outgoing socket - pass

2016-03-17T12:01:04.550Z - info: 6. native server - closing incoming connection cleans outgoing socket - pass

2016-03-17T12:01:04.551Z - info: 7. native server - closing outgoing socket cleans associated mux stream - pass

2016-03-17T12:01:04.552Z - info: 8. native server - closing the whole server cleans everything up - pass

2016-03-17T12:01:04.552Z - info: 9. native server - we can get a ton of connections and data through and still clean up the server completely - pass
2016-03-17T12:01:04.553Z - info: 10. native server - simulate mux failure, make sure everything is cleaned up - pass

2016-03-17T12:01:04.554Z - info: 11. native server - timing out the incoming connection cleans everything up - pass

2016-03-17T12:01:04.555Z - info: 12. closeAll can close even when connections open - pass

2016-03-17T12:01:04.556Z - info: 13. closeAll with promise - pass

2016-03-17T12:01:04.557Z - info: 14. multiplex can send data - pass

2016-03-17T12:01:04.558Z - info: 15. enqueue and run in order - pass
2016-03-17T12:01:04.559Z - info: 16. enqueueAtTop and run backwards - pass

2016-03-17T12:01:04.559Z - info: 17. mix enqueue and enqueueAtTop - pass

2016-03-17T12:01:04.560Z - info: 18. queues handled independently - pass

2016-03-17T12:01:04.561Z - info: 19. basic - pass

2016-03-17T12:01:04.562Z - info: 20. another - pass
2016-03-17T12:01:04.563Z - info: 21. #startListeningForAdvertisements should fail if start not called - pass

2016-03-17T12:01:04.564Z - info: 22. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-17T12:01:04.564Z - info: 23. should be able to call #stopListeningForAdvertisements many times - pass

2016-03-17T12:01:04.565Z - info: 24. should be able to call #startListeningForAdvertisements many times - pass

2016-03-17T12:01:04.566Z - info: 25. should be able to call #startUpdateAdvertisingAndListening many times - pass

2016-03-17T12:01:04.567Z - info: 26. should be able to call #stopAdvertisingAndListening many times - pass

2016-03-17T12:01:04.568Z - info: 27. #start should fail if called twice in a row - pass
2016-03-17T12:01:04.569Z - info: 28. does not emit duplicate discoveryAdvertisingStateUpdate - pass

2016-03-17T12:01:04.570Z - info: 29. does not send duplicate availability changes - pass

2016-03-17T12:01:04.571Z - info: 30. can get the network status - pass

2016-03-17T12:01:04.571Z - info: 31. wifi peer is marked unavailable if announcements stop - pass

2016-03-17T12:01:04.572Z - info: 32. can get the network status before starting - pass

2016-03-17T12:01:04.573Z - info: 33. Test BEACONS_RETRIEVED_AND_PARSED locally - pass

2016-03-17T12:01:04.574Z - info: 34. Test HTTP_BAD_RESPONSE locally - pass

2016-03-17T12:01:04.575Z - info: 35. Test NETWORK_PROBLEM locally - pass

2016-03-17T12:01:04.576Z - info: 36. Test timeout locally - pass
2016-03-17T12:01:04.577Z - info: 37. Call the start two times - pass

2016-03-17T12:01:04.578Z - info: 38. Call the kill before calling the start - pass

2016-03-17T12:01:04.579Z - info: 39. Call the kill immediately after the start - pass

2016-03-17T12:01:04.579Z - info: 40. Call the kill while waiting a response from the server - pass

2016-03-17T12:01:04.580Z - info: 41. Test to exceed the max content size locally - pass

2016-03-17T12:01:04.581Z - info: 42. Close the server socket while the client is waiting a response from the server. Local test. - pass

2016-03-17T12:01:04.582Z - info: 43. Close the client socket while the client is waiting a response from the server. Local test. - pass

2016-03-17T12:01:04.583Z - info: 44. #generatePreambleAndBeacons bad args - pass

2016-03-17T12:01:04.584Z - info: 45. #generatePreambleAndBeacons empty keys to notify - pass

2016-03-17T12:01:04.585Z - info: 46. #generatePreambleAndBeacons multiple keys to notify - pass

2016-03-17T12:01:04.586Z - info: 47. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass
2016-03-17T12:01:04.587Z - info: 48. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass

2016-03-17T12:01:04.588Z - info: 49. #parseBeacons expiration out of range lower - pass

2016-03-17T12:01:04.589Z - info: 50. #parseBeacons expiration out of range lower - pass

2016-03-17T12:01:04.589Z - info: 51. #parseBeacons no beacons returns null - pass

2016-03-17T12:01:04.590Z - info: 52. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass

2016-03-17T12:01:04.591Z - info: 53. #parseBeacons addressBookCallback fails decrypt - pass

2016-03-17T12:01:04.592Z - info: 54. #parseBeacons addressBookCallback returns no matches - pass
2016-03-17T12:01:04.593Z - info: 55. #parseBeacons addressBookCallback returns spurious match - pass
2016-03-17T12:01:04.594Z - info: 56. #parseBeacons addressBookCallback returns public key - pass
2016-03-17T12:01:04.594Z - info: 57. validate generatePskIdentityField - pass
2016-03-17T12:01:04.595Z - info: 58. validate generatePskSecret - pass
2016-03-17T12:01:04.596Z - info: 59. Start and stop ThaliNotificationServer - pass
2016-03-17T12:01:04.596Z - info: 60. Pass an empty array to ThaliNotificationServer.start - pass

2016-03-17T12:01:04.597Z - info: 61. Pass a string to ThaliNotificationServer.start - pass
2016-03-17T12:01:04.597Z - info: 62. Pass an empty parameter to ThaliNotificationServer.start - pass
2016-03-17T12:01:04.598Z - info: 63. Make an HTTP request to /NotificationBeacons - pass
2016-03-17T12:01:04.599Z - info: 64. Make an HTTP request to /NotificationBeacons (no keys) - pass
2016-03-17T12:01:04.599Z - info: 65. Make an HTTP request to /NotificationBeaconsbefore calling start - pass
2016-03-17T12:01:04.600Z - info: 66. #testThaliPeerAction - test getters - pass
2016-03-17T12:01:04.601Z - info: 67. #testThaliPeerAction - start and kill - pass
2016-03-17T12:01:04.601Z - info: 68. #testThaliPeerAction - double start - pass
2016-03-17T12:01:04.602Z - info: 69. #testThaliPeerAction - start after kill - pass
2016-03-17T12:01:04.602Z - info: 70. #testThaliPeerAction - make sure ids are unique - pass
2016-03-17T12:01:04.603Z - info: 71. Test PeerConnectionInformation basics - pass
2016-03-17T12:01:04.603Z - info: 72. Test PeerDictionary basic functionality - pass
2016-03-17T12:01:04.604Z - info: 73. Test PeerDictionary with multiple entries. - pass
2016-03-17T12:01:04.605Z - info: 74. RESOLVED entries are removed before WAITING state entry. - pass
2016-03-17T12:01:04.605Z - info: 75. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass
2016-03-17T12:01:04.606Z - info: 76. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass
2016-03-17T12:01:04.606Z - info: 77. #ThaliPeerPoolInterface - bad enqueues - pass
2016-03-17T12:01:04.607Z - info: 78. #ThaliPeerPoolInterface - do not allow same object type - pass
2016-03-17T12:01:04.607Z - info: 79. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass
2016-03-17T12:01:04.608Z - info: 80. compareBufferArrays - pass
2016-03-17T12:01:04.608Z - info: 81. Call start twice and get error - pass
2016-03-17T12:01:04.609Z - info: 82. Start and make sure it runs - pass
2016-03-17T12:01:04.610Z - info: 83. Make sure getTimeWhenRun is right after start - pass
2016-03-17T12:01:04.610Z - info: 84. Make sure getTimeWhenRun is -1 after function is called - pass
2016-03-17T12:01:04.611Z - info: 85. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass
2016-03-17T12:01:04.611Z - info: 86. Test TransientState - pass
2016-03-17T12:01:04.612Z - info: 87. No peers and empty database - pass
2016-03-17T12:01:04.613Z - info: 88. One peer and empty DB - pass
2016-03-17T12:01:04.613Z - info: 89. One peer with _Local set behind current seq - pass
2016-03-17T12:01:04.614Z - info: 90. One peer with _Local set equal to current seq - pass
2016-03-17T12:01:04.615Z - info: 91. One peer with _Local set ahead of current seq (and no this should not happen) - pass
2016-03-17T12:01:04.615Z - info: 92. Three peers, one not in DB, one behind and one ahead - pass
2016-03-17T12:01:04.616Z - info: 93. More than maximum peers, make sure we only send maximum allowed - pass
2016-03-17T12:01:04.616Z - info: 94. two peers with empty DB, update the doc - pass
2016-03-17T12:01:04.617Z - info: 95. add doc and make sure tokens refresh when they expire - pass
2016-03-17T12:01:04.617Z - info: 96. start and stop and start and stop - pass
2016-03-17T12:01:04.618Z - info: 97. two identical starts in a row - pass
2016-03-17T12:01:04.619Z - info: 98. two different starts in a row - pass
2016-03-17T12:01:04.619Z - info: 99. two stops and a start and two stops - pass
2016-03-17T12:01:04.620Z - info: 100. we properly enqueue requests so no then needed - pass
2016-03-17T12:01:04.620Z - info: 101. test calculateSeqPointKeyId - pass
2016-03-17T12:01:04.621Z - info: 102. can create servers manager - pass
2016-03-17T12:01:04.621Z - info: 103. calling stop without start causes error - pass
2016-03-17T12:01:04.622Z - info: 104. can start/stop servers manager - pass
2016-03-17T12:01:04.622Z - info: 105. starting twice resolves with listening port - pass
2016-03-17T12:01:04.623Z - info: 106. terminateIncomingConnection will terminate a connection - pass
2016-03-17T12:01:04.623Z - info: 107. terminate an Outgoing connection will terminate the server - pass
2016-03-17T12:01:04.624Z - info: 108. terminate an Outgoing connection with wrong arguments is not harmful - pass
2016-03-17T12:01:04.625Z - info: 109. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass

2016-03-17T12:01:04.626Z - info: 110. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass
2016-03-17T12:01:04.626Z - info: 111. messages with invalid location or USN should be ignored - pass
2016-03-17T12:01:04.627Z - info: 112. verify that Thali-specific messages are filtered correctly - pass

2016-03-17T12:01:04.628Z - info: 113. #startListeningForAdvertisements should fail if start not called - pass

2016-03-17T12:01:04.629Z - info: 114. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-17T12:01:04.630Z - info: 115. #start should fail if called twice in a row - pass

2016-03-17T12:01:04.631Z - info: 116. should not be started after stop is called - pass
2016-03-17T12:01:04.632Z - info: 117. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass
2016-03-17T12:01:04.633Z - info: 118. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass
2016-03-17T12:01:04.633Z - info: 119. #startUpdateAdvertisingAndListening should start hosting given router object - pass
2016-03-17T12:01:04.634Z - info: 120. #stop can be called multiple times in a row - pass
2016-03-17T12:01:04.635Z - info: 121. #startListeningForAdvertisements can be called multiple times in a row - pass
2016-03-17T12:01:04.635Z - info: 122. #stopListeningForAdvertisements can be called multiple times in a row - pass
2016-03-17T12:01:04.636Z - info: 123. #stopAdvertisingAndListening can be called multiple times in a row - pass
2016-03-17T12:01:04.636Z - info: 124. functions are run from a queue in the right order - pass
2016-03-17T12:01:04.637Z - info: 125. #ThaliPeerPoolDefault - single action - pass
2016-03-17T12:01:04.638Z - info: 126. #ThaliPeerPoolDefault - multiple actions - pass
2016-03-17T12:01:04.638Z - info: 

-== END ==-


```


Logs for system : 
```

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/627544039ea0a99_416__Implementation_of_ThalinotificationAction_juhanak/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/627544039ea0a99_416__Implementation_of_ThalinotificationAction_juhanak/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/627544039ea0a99_416__Implementation_of_ThalinotificationAction_juhanak/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/627544039ea0a99_416__Implementation_of_ThalinotificationAction_juhanak/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/627544039ea0a99_416__Implementation_of_ThalinotificationAction_juhanak/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:0 
child process exited with code 0 on device f56ad48d 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/627544039ea0a99_416__Implementation_of_ThalinotificationAction_juhanak/thali01_samsung-SM-A500FU.md)

####Node name: thali03
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Android task is completed. [SUCCESS]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/627544039ea0a99_416__Implementation_of_ThalinotificationAction_juhanak/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/627544039ea0a99_416__Implementation_of_ThalinotificationAction_juhanak/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Android task is completed. [SUCCESS]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/627544039ea0a99_416__Implementation_of_ThalinotificationAction_juhanak/thali05_LGE-LG-H815.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/627544039ea0a99_416__Implementation_of_ThalinotificationAction_juhanak/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/627544039ea0a99_416__Implementation_of_ThalinotificationAction_juhanak/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:0 
child process exited with code 0 on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/627544039ea0a99_416__Implementation_of_ThalinotificationAction_juhanak/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:0 
child process exited with code 0 on device 4325e43f 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/627544039ea0a99_416__Implementation_of_ThalinotificationAction_juhanak/thali08_samsung-SM-A300FU.md)





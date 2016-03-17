#### Test 62754403d2f0346 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":8}}
2016-03-17T12:28:58.069Z - info: listening on *:3000

2016-03-17T12:28:59.106Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:0

2016-03-17T12:28:59.441Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:1

2016-03-17T12:28:59.444Z - info: Required number of ios devices presented (2)

2016-03-17T12:28:59.448Z - info: Starting unit test run for platform: ios

2016-03-17T12:28:59.558Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:2

2016-03-17T12:28:59.560Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-17T12:28:59.984Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-17T12:29:00.297Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-17T12:29:00.715Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-17T12:29:01.126Z - info: Running on ios test: 4. native server connections all up

2016-03-17T12:29:01.720Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-17T12:29:01.733Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:3

2016-03-17T12:29:01.735Z - info: Discarding surplus device: Apple-Iphone5-1

2016-03-17T12:29:02.162Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-17T12:29:02.226Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:4

2016-03-17T12:29:02.375Z - debug: Socket disconnected: transport close 2 (Apple-Iphone5s-1)

2016-03-17T12:29:02.560Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-17T12:29:03.005Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-17T12:29:03.431Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-17T12:29:04.155Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-17T12:29:04.980Z - debug: Socket disconnected: transport close 3 (Apple-Iphone5-1)

2016-03-17T12:29:05.926Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-17T12:29:06.332Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-17T12:29:06.662Z - info: Running on ios test: 13. closeAll with promise

2016-03-17T12:29:06.961Z - info: Running on ios test: 14. multiplex can send data

2016-03-17T12:29:07.264Z - info: Running on ios test: 15. enqueue and run in order

2016-03-17T12:29:07.786Z - info: Running on ios test: 16. enqueueAtTop and run backwards

2016-03-17T12:29:08.085Z - info: Running on ios test: 17. mix enqueue and enqueueAtTop

2016-03-17T12:29:08.464Z - info: Running on ios test: 18. queues handled independently

2016-03-17T12:29:08.800Z - info: Running on ios test: 19. basic

2016-03-17T12:29:09.235Z - info: Running on ios test: 20. another

2016-03-17T12:29:09.600Z - info: Running on ios test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-17T12:29:09.957Z - info: Running on ios test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-17T12:29:10.389Z - info: Running on ios test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-17T12:29:10.732Z - info: Running on ios test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-17T12:29:11.115Z - info: Running on ios test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-17T12:29:11.537Z - info: Running on ios test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-17T12:29:11.929Z - info: Running on ios test: 27. #start should fail if called twice in a row

2016-03-17T12:29:12.230Z - info: Running on ios test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-17T12:29:12.624Z - info: Running on ios test: 29. does not send duplicate availability changes

2016-03-17T12:29:13.033Z - info: Running on ios test: 30. can get the network status

2016-03-17T12:29:13.340Z - info: Running on ios test: 31. wifi peer is marked unavailable if announcements stop

2016-03-17T12:29:14.681Z - info: Running on ios test: 32. can get the network status before starting

2016-03-17T12:29:14.979Z - info: Running on ios test: 33. Test BEACONS_RETRIEVED_AND_PARSED locally

2016-03-17T12:29:15.505Z - info: Running on ios test: 34. Test HTTP_BAD_RESPONSE locally

2016-03-17T12:29:15.858Z - info: Running on ios test: 35. Test NETWORK_PROBLEM locally

2016-03-17T12:29:16.344Z - info: Running on ios test: 36. Test timeout locally

2016-03-17T12:29:17.729Z - info: Running on ios test: 37. Call the start two times

2016-03-17T12:29:18.077Z - info: Running on ios test: 38. Call the kill before calling the start

2016-03-17T12:29:18.345Z - info: Running on ios test: 39. Call the kill immediately after the start

2016-03-17T12:29:18.585Z - info: Running on ios test: 40. Call the kill while waiting a response from the server

2016-03-17T12:29:20.859Z - info: Running on ios test: 41. Test to exceed the max content size locally

2016-03-17T12:29:21.227Z - info: Running on ios test: 42. Close the server socket while the client is waiting a response from the server. Local test.

2016-03-17T12:29:23.570Z - info: Running on ios test: 43. Close the client socket while the client is waiting a response from the server. Local test.

2016-03-17T12:29:26.102Z - info: Running on ios test: 44. #generatePreambleAndBeacons bad args

2016-03-17T12:29:26.656Z - info: Running on ios test: 45. #generatePreambleAndBeacons empty keys to notify

2016-03-17T12:29:27.220Z - info: Running on ios test: 46. #generatePreambleAndBeacons multiple keys to notify

2016-03-17T12:29:27.633Z - info: Running on ios test: 47. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-17T12:29:28.046Z - info: Running on ios test: 48. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-17T12:29:28.466Z - info: Running on ios test: 49. #parseBeacons expiration out of range lower

2016-03-17T12:29:28.979Z - info: Running on ios test: 50. #parseBeacons expiration out of range lower

2016-03-17T12:29:29.315Z - info: Running on ios test: 51. #parseBeacons no beacons returns null

2016-03-17T12:29:29.672Z - info: Running on ios test: 52. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-17T12:29:29.976Z - info: Running on ios test: 53. #parseBeacons addressBookCallback fails decrypt

2016-03-17T12:29:30.384Z - info: Running on ios test: 54. #parseBeacons addressBookCallback returns no matches

2016-03-17T12:29:30.669Z - info: Running on ios test: 55. #parseBeacons addressBookCallback returns spurious match

2016-03-17T12:29:30.941Z - info: Running on ios test: 56. #parseBeacons addressBookCallback returns public key

2016-03-17T12:29:31.249Z - info: Running on ios test: 57. validate generatePskIdentityField

2016-03-17T12:29:31.522Z - info: Running on ios test: 58. validate generatePskSecret

2016-03-17T12:29:31.817Z - info: Running on ios test: 59. Start and stop ThaliNotificationServer

2016-03-17T12:29:32.147Z - info: Running on ios test: 60. Pass an empty array to ThaliNotificationServer.start

2016-03-17T12:29:32.638Z - info: Running on ios test: 61. Pass a string to ThaliNotificationServer.start

2016-03-17T12:29:32.906Z - info: Running on ios test: 62. Pass an empty parameter to ThaliNotificationServer.start

2016-03-17T12:29:33.193Z - info: Running on ios test: 63. Make an HTTP request to /NotificationBeacons

2016-03-17T12:29:33.624Z - info: Running on ios test: 64. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-17T12:29:34.015Z - info: Running on ios test: 65. Make an HTTP request to /NotificationBeaconsbefore calling start

2016-03-17T12:29:34.389Z - info: Running on ios test: 66. #testThaliPeerAction - test getters

2016-03-17T12:29:34.645Z - info: Running on ios test: 67. #testThaliPeerAction - start and kill

2016-03-17T12:29:34.936Z - info: Running on ios test: 68. #testThaliPeerAction - double start

2016-03-17T12:29:35.227Z - info: Running on ios test: 69. #testThaliPeerAction - start after kill

2016-03-17T12:29:35.429Z - info: Running on ios test: 70. #testThaliPeerAction - make sure ids are unique

2016-03-17T12:29:35.705Z - info: Running on ios test: 71. Test PeerConnectionInformation basics

2016-03-17T12:29:36.030Z - info: Running on ios test: 72. Test PeerDictionary basic functionality

2016-03-17T12:29:36.473Z - info: Running on ios test: 73. Test PeerDictionary with multiple entries.

2016-03-17T12:29:37.863Z - info: Running on ios test: 74. RESOLVED entries are removed before WAITING state entry.

2016-03-17T12:29:38.783Z - info: Running on ios test: 75. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-17T12:29:39.772Z - info: Running on ios test: 76. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-17T12:29:40.805Z - info: Running on ios test: 77. #ThaliPeerPoolInterface - bad enqueues

2016-03-17T12:29:41.081Z - info: Running on ios test: 78. #ThaliPeerPoolInterface - do not allow same object type

2016-03-17T12:29:41.431Z - info: Running on ios test: 79. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-17T12:29:41.816Z - info: Running on ios test: 80. compareBufferArrays

2016-03-17T12:29:42.371Z - info: Running on ios test: 81. Call start twice and get error

2016-03-17T12:29:42.635Z - info: Running on ios test: 82. Start and make sure it runs

2016-03-17T12:29:42.937Z - info: Running on ios test: 83. Make sure getTimeWhenRun is right after start

2016-03-17T12:29:43.158Z - info: Running on ios test: 84. Make sure getTimeWhenRun is -1 after function is called

2016-03-17T12:29:43.427Z - info: Running on ios test: 85. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-17T12:29:43.732Z - info: Running on ios test: 86. Test TransientState

2016-03-17T12:29:43.995Z - info: Running on ios test: 87. No peers and empty database

2016-03-17T12:29:44.498Z - info: Running on ios test: 88. One peer and empty DB

2016-03-17T12:29:45.021Z - info: Running on ios test: 89. One peer with _Local set behind current seq

2016-03-17T12:29:45.618Z - info: Running on ios test: 90. One peer with _Local set equal to current seq

2016-03-17T12:29:46.222Z - info: Running on ios test: 91. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-17T12:29:46.776Z - info: Running on ios test: 92. Three peers, one not in DB, one behind and one ahead

2016-03-17T12:29:47.356Z - info: Running on ios test: 93. More than maximum peers, make sure we only send maximum allowed

2016-03-17T12:29:48.420Z - info: Running on ios test: 94. two peers with empty DB, update the doc

2016-03-17T12:29:49.223Z - info: Running on ios test: 95. add doc and make sure tokens refresh when they expire

2016-03-17T12:29:50.082Z - info: Running on ios test: 96. start and stop and start and stop

2016-03-17T12:29:50.596Z - info: Running on ios test: 97. two identical starts in a row

2016-03-17T12:29:51.073Z - info: Running on ios test: 98. two different starts in a row

2016-03-17T12:29:51.563Z - info: Running on ios test: 99. two stops and a start and two stops

2016-03-17T12:29:52.053Z - info: Running on ios test: 100. we properly enqueue requests so no then needed

2016-03-17T12:29:52.567Z - info: Running on ios test: 101. test calculateSeqPointKeyId

2016-03-17T12:29:52.843Z - info: Running on ios test: 102. can create servers manager

2016-03-17T12:29:53.084Z - info: Running on ios test: 103. calling stop without start causes error

2016-03-17T12:29:53.382Z - info: Running on ios test: 104. can start/stop servers manager

2016-03-17T12:29:53.618Z - info: Running on ios test: 105. starting twice resolves with listening port

2016-03-17T12:29:53.895Z - info: Running on ios test: 106. terminateIncomingConnection will terminate a connection

2016-03-17T12:29:54.148Z - info: Running on ios test: 107. terminate an Outgoing connection will terminate the server

2016-03-17T12:29:54.461Z - info: Running on ios test: 108. terminate an Outgoing connection with wrong arguments is not harmful

2016-03-17T12:29:54.726Z - info: Running on ios test: 109. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-17T12:29:55.198Z - info: Running on ios test: 110. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-17T12:29:55.567Z - info: Running on ios test: 111. messages with invalid location or USN should be ignored

2016-03-17T12:29:55.885Z - info: Running on ios test: 112. verify that Thali-specific messages are filtered correctly

2016-03-17T12:29:56.401Z - info: Running on ios test: 113. #startListeningForAdvertisements should fail if start not called

2016-03-17T12:29:56.924Z - info: Running on ios test: 114. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-17T12:29:57.428Z - info: Running on ios test: 115. #start should fail if called twice in a row

2016-03-17T12:29:57.855Z - info: Running on ios test: 116. should not be started after stop is called

2016-03-17T12:29:58.168Z - info: Running on ios test: 117. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-17T12:29:58.651Z - info: Running on ios test: 118. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-17T12:29:58.990Z - info: Running on ios test: 119. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-17T12:29:59.380Z - info: Running on ios test: 120. #stop can be called multiple times in a row

2016-03-17T12:29:59.651Z - info: Running on ios test: 121. #startListeningForAdvertisements can be called multiple times in a row

2016-03-17T12:29:59.920Z - info: Running on ios test: 122. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-17T12:30:00.268Z - info: Running on ios test: 123. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-17T12:30:00.550Z - info: Running on ios test: 124. functions are run from a queue in the right order

2016-03-17T12:30:00.894Z - info: Running on ios test: 125. #ThaliPeerPoolDefault - single action

2016-03-17T12:30:01.337Z - info: Running on ios test: 126. #ThaliPeerPoolDefault - multiple actions

2016-03-17T12:30:01.912Z - info: Test run on ios complete

2016-03-17T12:30:01.915Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-17T12:30:01.917Z - info: PLATFORM: ios

2016-03-17T12:30:01.918Z - info: RESULT: PASS

2016-03-17T12:30:01.920Z - info: 126 of 126 tests completed

2016-03-17T12:30:01.921Z - info: 126/126 passed (0 failures)

2016-03-17T12:30:01.923Z - info: --- Test Details ---



2016-03-17T12:30:01.924Z - info: 1. calling createNativeListener directly rejects - pass

2016-03-17T12:30:01.925Z - info: 2. emits incomingConnectionState - pass

2016-03-17T12:30:01.926Z - info: 3. emits routerPortConnectionFailed - pass

2016-03-17T12:30:01.928Z - info: 4. native server connections all up - pass

2016-03-17T12:30:01.928Z - info: 5. native server - closing incoming stream cleans outgoing socket - pass

2016-03-17T12:30:01.929Z - info: 6. native server - closing incoming connection cleans outgoing socket - pass
2016-03-17T12:30:01.930Z - info: 7. native server - closing outgoing socket cleans associated mux stream - pass
2016-03-17T12:30:01.930Z - info: 8. native server - closing the whole server cleans everything up - pass
2016-03-17T12:30:01.931Z - info: 9. native server - we can get a ton of connections and data through and still clean up the server completely - pass
2016-03-17T12:30:01.932Z - info: 10. native server - simulate mux failure, make sure everything is cleaned up - pass
2016-03-17T12:30:01.932Z - info: 11. native server - timing out the incoming connection cleans everything up - pass
2016-03-17T12:30:01.933Z - info: 12. closeAll can close even when connections open - pass
2016-03-17T12:30:01.934Z - info: 13. closeAll with promise - pass
2016-03-17T12:30:01.934Z - info: 14. multiplex can send data - pass
2016-03-17T12:30:01.935Z - info: 15. enqueue and run in order - pass
2016-03-17T12:30:01.936Z - info: 16. enqueueAtTop and run backwards - pass
2016-03-17T12:30:01.937Z - info: 17. mix enqueue and enqueueAtTop - pass
2016-03-17T12:30:01.937Z - info: 18. queues handled independently - pass
2016-03-17T12:30:01.938Z - info: 19. basic - pass
2016-03-17T12:30:01.938Z - info: 20. another - pass
2016-03-17T12:30:01.939Z - info: 21. #startListeningForAdvertisements should fail if start not called - pass
2016-03-17T12:30:01.940Z - info: 22. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-17T12:30:01.940Z - info: 23. should be able to call #stopListeningForAdvertisements many times - pass
2016-03-17T12:30:01.941Z - info: 24. should be able to call #startListeningForAdvertisements many times - pass

2016-03-17T12:30:01.942Z - info: 25. should be able to call #startUpdateAdvertisingAndListening many times - pass

2016-03-17T12:30:01.942Z - info: 26. should be able to call #stopAdvertisingAndListening many times - pass

2016-03-17T12:30:01.943Z - info: 27. #start should fail if called twice in a row - pass
2016-03-17T12:30:01.944Z - info: 28. does not emit duplicate discoveryAdvertisingStateUpdate - pass

2016-03-17T12:30:01.944Z - info: 29. does not send duplicate availability changes - pass

2016-03-17T12:30:01.945Z - info: 30. can get the network status - pass

2016-03-17T12:30:01.946Z - info: 31. wifi peer is marked unavailable if announcements stop - pass

2016-03-17T12:30:01.946Z - info: 32. can get the network status before starting - pass
2016-03-17T12:30:01.947Z - info: 33. Test BEACONS_RETRIEVED_AND_PARSED locally - pass

2016-03-17T12:30:01.948Z - info: 34. Test HTTP_BAD_RESPONSE locally - pass

2016-03-17T12:30:01.948Z - info: 35. Test NETWORK_PROBLEM locally - pass

2016-03-17T12:30:01.949Z - info: 36. Test timeout locally - pass

2016-03-17T12:30:01.950Z - info: 37. Call the start two times - pass

2016-03-17T12:30:01.950Z - info: 38. Call the kill before calling the start - pass
2016-03-17T12:30:01.951Z - info: 39. Call the kill immediately after the start - pass

2016-03-17T12:30:01.952Z - info: 40. Call the kill while waiting a response from the server - pass

2016-03-17T12:30:01.952Z - info: 41. Test to exceed the max content size locally - pass

2016-03-17T12:30:01.953Z - info: 42. Close the server socket while the client is waiting a response from the server. Local test. - pass

2016-03-17T12:30:01.954Z - info: 43. Close the client socket while the client is waiting a response from the server. Local test. - pass

2016-03-17T12:30:01.954Z - info: 44. #generatePreambleAndBeacons bad args - pass
2016-03-17T12:30:01.955Z - info: 45. #generatePreambleAndBeacons empty keys to notify - pass

2016-03-17T12:30:01.956Z - info: 46. #generatePreambleAndBeacons multiple keys to notify - pass

2016-03-17T12:30:01.956Z - info: 47. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass

2016-03-17T12:30:01.957Z - info: 48. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass

2016-03-17T12:30:01.958Z - info: 49. #parseBeacons expiration out of range lower - pass
2016-03-17T12:30:01.958Z - info: 50. #parseBeacons expiration out of range lower - pass

2016-03-17T12:30:01.959Z - info: 51. #parseBeacons no beacons returns null - pass

2016-03-17T12:30:01.960Z - info: 52. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass

2016-03-17T12:30:01.960Z - info: 53. #parseBeacons addressBookCallback fails decrypt - pass

2016-03-17T12:30:01.961Z - info: 54. #parseBeacons addressBookCallback returns no matches - pass
2016-03-17T12:30:01.962Z - info: 55. #parseBeacons addressBookCallback returns spurious match - pass

2016-03-17T12:30:01.962Z - info: 56. #parseBeacons addressBookCallback returns public key - pass

2016-03-17T12:30:01.963Z - info: 57. validate generatePskIdentityField - pass

2016-03-17T12:30:01.964Z - info: 58. validate generatePskSecret - pass

2016-03-17T12:30:01.964Z - info: 59. Start and stop ThaliNotificationServer - pass
2016-03-17T12:30:01.965Z - info: 60. Pass an empty array to ThaliNotificationServer.start - pass

2016-03-17T12:30:01.966Z - info: 61. Pass a string to ThaliNotificationServer.start - pass
2016-03-17T12:30:01.966Z - info: 62. Pass an empty parameter to ThaliNotificationServer.start - pass
2016-03-17T12:30:01.967Z - info: 63. Make an HTTP request to /NotificationBeacons - pass
2016-03-17T12:30:01.967Z - info: 64. Make an HTTP request to /NotificationBeacons (no keys) - pass
2016-03-17T12:30:01.968Z - info: 65. Make an HTTP request to /NotificationBeaconsbefore calling start - pass
2016-03-17T12:30:01.969Z - info: 66. #testThaliPeerAction - test getters - pass
2016-03-17T12:30:01.969Z - info: 67. #testThaliPeerAction - start and kill - pass
2016-03-17T12:30:01.970Z - info: 68. #testThaliPeerAction - double start - pass
2016-03-17T12:30:01.970Z - info: 69. #testThaliPeerAction - start after kill - pass
2016-03-17T12:30:01.971Z - info: 70. #testThaliPeerAction - make sure ids are unique - pass
2016-03-17T12:30:01.971Z - info: 71. Test PeerConnectionInformation basics - pass
2016-03-17T12:30:01.972Z - info: 72. Test PeerDictionary basic functionality - pass
2016-03-17T12:30:01.973Z - info: 73. Test PeerDictionary with multiple entries. - pass
2016-03-17T12:30:01.973Z - info: 74. RESOLVED entries are removed before WAITING state entry. - pass
2016-03-17T12:30:01.974Z - info: 75. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass
2016-03-17T12:30:01.974Z - info: 76. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass
2016-03-17T12:30:01.974Z - info: 77. #ThaliPeerPoolInterface - bad enqueues - pass
2016-03-17T12:30:01.975Z - info: 78. #ThaliPeerPoolInterface - do not allow same object type - pass
2016-03-17T12:30:01.975Z - info: 79. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass
2016-03-17T12:30:01.976Z - info: 80. compareBufferArrays - pass

2016-03-17T12:30:01.983Z - info: 81. Call start twice and get error - pass

2016-03-17T12:30:01.984Z - info: 82. Start and make sure it runs - pass

2016-03-17T12:30:01.984Z - info: 83. Make sure getTimeWhenRun is right after start - pass

2016-03-17T12:30:01.985Z - info: 84. Make sure getTimeWhenRun is -1 after function is called - pass
2016-03-17T12:30:01.986Z - info: 85. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass

2016-03-17T12:30:01.986Z - info: 86. Test TransientState - pass
2016-03-17T12:30:01.987Z - info: 87. No peers and empty database - pass
2016-03-17T12:30:01.988Z - info: 88. One peer and empty DB - pass
2016-03-17T12:30:01.988Z - info: 89. One peer with _Local set behind current seq - pass
2016-03-17T12:30:01.989Z - info: 90. One peer with _Local set equal to current seq - pass
2016-03-17T12:30:01.989Z - info: 91. One peer with _Local set ahead of current seq (and no this should not happen) - pass
2016-03-17T12:30:01.990Z - info: 92. Three peers, one not in DB, one behind and one ahead - pass
2016-03-17T12:30:01.990Z - info: 93. More than maximum peers, make sure we only send maximum allowed - pass
2016-03-17T12:30:01.991Z - info: 94. two peers with empty DB, update the doc - pass
2016-03-17T12:30:01.992Z - info: 95. add doc and make sure tokens refresh when they expire - pass

2016-03-17T12:30:01.992Z - info: 96. start and stop and start and stop - pass

2016-03-17T12:30:01.993Z - info: 97. two identical starts in a row - pass

2016-03-17T12:30:01.994Z - info: 98. two different starts in a row - pass
2016-03-17T12:30:01.994Z - info: 99. two stops and a start and two stops - pass

2016-03-17T12:30:01.995Z - info: 100. we properly enqueue requests so no then needed - pass

2016-03-17T12:30:01.996Z - info: 101. test calculateSeqPointKeyId - pass

2016-03-17T12:30:01.996Z - info: 102. can create servers manager - pass

2016-03-17T12:30:01.997Z - info: 103. calling stop without start causes error - pass

2016-03-17T12:30:01.998Z - info: 104. can start/stop servers manager - pass

2016-03-17T12:30:01.998Z - info: 105. starting twice resolves with listening port - pass
2016-03-17T12:30:01.999Z - info: 106. terminateIncomingConnection will terminate a connection - pass
2016-03-17T12:30:02.000Z - info: 107. terminate an Outgoing connection will terminate the server - pass

2016-03-17T12:30:02.000Z - info: 108. terminate an Outgoing connection with wrong arguments is not harmful - pass
2016-03-17T12:30:02.001Z - info: 109. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass

2016-03-17T12:30:02.002Z - info: 110. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-03-17T12:30:02.002Z - info: 111. messages with invalid location or USN should be ignored - pass

2016-03-17T12:30:02.003Z - info: 112. verify that Thali-specific messages are filtered correctly - pass

2016-03-17T12:30:02.004Z - info: 113. #startListeningForAdvertisements should fail if start not called - pass

2016-03-17T12:30:02.004Z - info: 114. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-17T12:30:02.005Z - info: 115. #start should fail if called twice in a row - pass

2016-03-17T12:30:02.006Z - info: 116. should not be started after stop is called - pass

2016-03-17T12:30:02.006Z - info: 117. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass

2016-03-17T12:30:02.010Z - info: 118. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass

2016-03-17T12:30:02.011Z - info: 119. #startUpdateAdvertisingAndListening should start hosting given router object - pass

2016-03-17T12:30:02.011Z - info: 120. #stop can be called multiple times in a row - pass

2016-03-17T12:30:02.012Z - info: 121. #startListeningForAdvertisements can be called multiple times in a row - pass
2016-03-17T12:30:02.013Z - info: 122. #stopListeningForAdvertisements can be called multiple times in a row - pass

2016-03-17T12:30:02.013Z - info: 123. #stopAdvertisingAndListening can be called multiple times in a row - pass

2016-03-17T12:30:02.014Z - info: 124. functions are run from a queue in the right order - pass

2016-03-17T12:30:02.015Z - info: 125. #ThaliPeerPoolDefault - single action - pass

2016-03-17T12:30:02.015Z - info: 126. #ThaliPeerPoolDefault - multiple actions - pass

2016-03-17T12:30:02.016Z - info: 

-== END ==-

2016-03-17T12:30:04.590Z - debug: Socket disconnected: transport close 0 (Apple-IpadAir2-1)

2016-03-17T12:30:04.944Z - debug: Socket disconnected: transport close 1 (Apple-Iphone6-1)

2016-03-17T12:49:32.262Z - debug: Socket disconnected: transport close 4 (LGE-LG-H815)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

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
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62754403d2f0346_416__Implementation_of_ThalinotificationAction_juhanak/thali01_samsung-SM-A500FU.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/62754403d2f0346_416__Implementation_of_ThalinotificationAction_juhanak/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/62754403d2f0346_416__Implementation_of_ThalinotificationAction_juhanak/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:0 
child process exited with code 0 on device LGH8153b36be34 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/62754403d2f0346_416__Implementation_of_ThalinotificationAction_juhanak/thali05_LGE-LG-H815.md)

####Node name: thali06
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:0 
child process exited with code 0 on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:0 
child process exited with code 0 on device FA55PYS00566 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62754403d2f0346_416__Implementation_of_ThalinotificationAction_juhanak/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/62754403d2f0346_416__Implementation_of_ThalinotificationAction_juhanak/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:0 
child process exited with code 0 on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62754403d2f0346_416__Implementation_of_ThalinotificationAction_juhanak/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:0 
child process exited with code 0 on device 4325e43f 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62754403d2f0346_416__Implementation_of_ThalinotificationAction_juhanak/thali08_samsung-SM-A300FU.md)




###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/62754403d2f0346_416__Implementation_of_ThalinotificationAction_juhanak/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/62754403d2f0346_416__Implementation_of_ThalinotificationAction_juhanak/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/62754403d2f0346_416__Implementation_of_ThalinotificationAction_juhanak/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/62754403d2f0346_416__Implementation_of_ThalinotificationAction_juhanak/iOS_Iphone5s-1.md)



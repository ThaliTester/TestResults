#### Test 62548124d9c0fd9 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":9}}
2016-03-19T11:54:50.562Z - info: listening on *:3000

2016-03-19T11:54:51.597Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:0

2016-03-19T11:54:52.983Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:1

2016-03-19T11:54:54.020Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:2

2016-03-19T11:54:54.024Z - info: Required number of ios devices presented (2)

2016-03-19T11:54:54.028Z - info: Starting unit test run for platform: ios

2016-03-19T11:54:54.057Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:3

2016-03-19T11:54:54.058Z - info: Discarding surplus device: Apple-IpadAir2-1

2016-03-19T11:54:55.476Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:4

2016-03-19T11:54:55.479Z - info: Required number of android devices presented (2)

2016-03-19T11:54:55.482Z - info: Starting unit test run for platform: android

2016-03-19T11:54:56.034Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-19T11:54:56.157Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-19T11:54:56.310Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:5

2016-03-19T11:54:56.311Z - info: Discarding surplus device: Apple-Iphone6-1

2016-03-19T11:54:56.646Z - debug: Socket disconnected: transport close 3 (Apple-IpadAir2-1)

2016-03-19T11:54:56.837Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-19T11:54:57.879Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-19T11:54:58.533Z - info: Running on android test: 4. native server connections all up

2016-03-19T11:54:59.042Z - debug: Socket disconnected: transport close 5 (Apple-Iphone6-1)

2016-03-19T11:54:59.051Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-19T11:54:59.233Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-19T11:54:59.523Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-19T11:54:59.822Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-19T11:55:00.072Z - info: Running on ios test: 4. native server connections all up

2016-03-19T11:55:00.379Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-19T11:55:00.660Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-19T11:55:00.886Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-19T11:55:01.233Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-19T11:55:01.339Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-19T11:55:01.740Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-19T11:55:02.115Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-19T11:55:02.267Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-19T11:55:02.582Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-19T11:55:02.798Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-19T11:55:03.211Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-19T11:55:03.462Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-19T11:55:03.500Z - info: Running on android test: 13. closeAll with promise

2016-03-19T11:55:03.825Z - info: Running on android test: 14. multiplex can send data

2016-03-19T11:55:04.776Z - info: Running on android test: 15. enqueue and run in order

2016-03-19T11:55:05.574Z - info: Running on android test: 16. enqueueAtTop and run backwards

2016-03-19T11:55:06.077Z - info: Running on android test: 17. mix enqueue and enqueueAtTop

2016-03-19T11:55:06.636Z - info: Running on android test: 18. queues handled independently

2016-03-19T11:55:07.088Z - info: Running on android test: 19. basic

2016-03-19T11:55:07.093Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-19T11:55:07.646Z - info: Running on android test: 20. another

2016-03-19T11:55:07.841Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-19T11:55:08.178Z - info: Running on android test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-19T11:55:08.386Z - info: Running on ios test: 13. closeAll with promise

2016-03-19T11:55:08.731Z - info: Running on android test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-19T11:55:08.938Z - info: Running on ios test: 14. multiplex can send data

2016-03-19T11:55:09.251Z - info: Running on android test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-19T11:55:09.776Z - info: Running on android test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-19T11:55:10.073Z - info: Running on ios test: 15. enqueue and run in order

2016-03-19T11:55:10.548Z - info: Running on android test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-19T11:55:10.701Z - info: Running on ios test: 16. enqueueAtTop and run backwards

2016-03-19T11:55:11.171Z - info: Running on ios test: 17. mix enqueue and enqueueAtTop

2016-03-19T11:55:11.766Z - info: Running on ios test: 18. queues handled independently

2016-03-19T11:55:11.799Z - info: Running on android test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-19T11:55:12.178Z - info: Running on ios test: 19. basic

2016-03-19T11:55:12.281Z - info: Running on android test: 27. #start should fail if called twice in a row

2016-03-19T11:55:12.934Z - info: Running on ios test: 20. another

2016-03-19T11:55:13.425Z - info: Running on ios test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-19T11:55:13.910Z - info: Running on ios test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-19T11:55:14.246Z - info: Running on android test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-19T11:55:14.422Z - info: Running on ios test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-19T11:55:15.413Z - info: Running on ios test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-19T11:55:15.616Z - info: Running on android test: 29. does not send duplicate availability changes

2016-03-19T11:55:16.547Z - info: Running on android test: 30. can get the network status

2016-03-19T11:55:17.118Z - info: Running on android test: 31. wifi peer is marked unavailable if announcements stop

2016-03-19T11:55:18.611Z - info: Running on android test: 32. Can call start/stopListeningForAdvertisements

2016-03-19T11:55:19.304Z - info: Running on android test: 33. Calling startListeningForAdvertisements twice is NOT an error

2016-03-19T11:55:20.345Z - info: Running on android test: 34. Can call start/stopUpdateAdvertisingAndListening

2016-03-19T11:55:21.464Z - info: Running on android test: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-19T11:55:24.013Z - info: Running on android test: 36. peerAvailabilityChange is called

2016-03-19T11:55:26.340Z - info: Running on android test: 37. Can connect to a remote peer

2016-03-19T11:55:37.355Z - info: Running on android test: 38. Can shift large amounts of data

2016-03-19T11:55:42.757Z - info: Running on android test: 39. #startListeningForAdvertisements should fail if start not called

2016-03-19T11:55:43.350Z - info: Running on android test: 40. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-19T11:55:43.893Z - info: Running on android test: 41. should be able to call #stopListeningForAdvertisements many times

2016-03-19T11:55:45.126Z - info: Running on android test: 42. should be able to call #startListeningForAdvertisements many times

2016-03-19T11:55:46.713Z - info: Running on android test: 43. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-19T11:55:48.153Z - info: Running on android test: 44. should be able to call #stopAdvertisingAndListening many times

2016-03-19T11:55:49.635Z - info: Running on android test: 45. can get the network status before starting

2016-03-19T11:55:51.417Z - info: Running on android test: 46. error returned with bad router

2016-03-19T11:55:52.211Z - info: Running on android test: 47. can do HTTP requests between peers

2016-03-19T11:56:00.342Z - info: Running on android test: 48. Can do requests between peers after start and stop

2016-03-19T11:56:01.452Z - info: Running on android test: 49. We successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-19T11:56:03.001Z - info: Running on android test: 50. Test BEACONS_RETRIEVED_AND_PARSED locally

2016-03-19T11:56:03.872Z - info: Running on android test: 51. Test HTTP_BAD_RESPONSE locally

2016-03-19T11:56:04.801Z - info: Running on android test: 52. Test NETWORK_PROBLEM locally

2016-03-19T11:56:06.647Z - info: Running on android test: 53. Test timeout locally

2016-03-19T11:56:08.255Z - info: Running on android test: 54. Call the start two times

2016-03-19T11:56:08.899Z - info: Running on android test: 55. Call the kill before calling the start

2016-03-19T11:56:09.403Z - info: Running on android test: 56. Call the kill immediately after the start

2016-03-19T11:56:10.020Z - info: Running on android test: 57. Call the kill while waiting a response from the server

2016-03-19T11:56:12.594Z - info: Running on android test: 58. Test to exceed the max content size locally

2016-03-19T11:56:13.279Z - info: Running on android test: 59. Close the server socket while the client is waiting a response from the server. Local test.

2016-03-19T11:56:16.118Z - info: Running on android test: 60. Close the client socket while the client is waiting a response from the server. Local test.

2016-03-19T11:56:18.889Z - info: Running on android test: 61. #generatePreambleAndBeacons bad args

2016-03-19T11:56:19.529Z - info: Running on android test: 62. #generatePreambleAndBeacons empty keys to notify

2016-03-19T11:56:20.603Z - info: Running on android test: 63. #generatePreambleAndBeacons multiple keys to notify

2016-03-19T11:56:21.236Z - info: Running on android test: 64. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-19T11:56:21.758Z - info: Running on android test: 65. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-19T11:56:22.194Z - info: Running on android test: 66. #parseBeacons expiration out of range lower

2016-03-19T11:56:22.716Z - info: Running on android test: 67. #parseBeacons expiration out of range lower

2016-03-19T11:56:23.153Z - info: Running on android test: 68. #parseBeacons no beacons returns null

2016-03-19T11:56:23.559Z - info: Running on android test: 69. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-19T11:56:24.095Z - info: Running on android test: 70. #parseBeacons addressBookCallback fails decrypt

2016-03-19T11:56:24.636Z - info: Running on android test: 71. #parseBeacons addressBookCallback returns no matches

2016-03-19T11:56:25.379Z - info: Running on android test: 72. #parseBeacons addressBookCallback returns spurious match

2016-03-19T11:56:25.967Z - info: Running on android test: 73. #parseBeacons addressBookCallback returns public key

2016-03-19T11:56:26.507Z - info: Running on android test: 74. validate generatePskIdentityField

2016-03-19T11:56:26.896Z - info: Running on android test: 75. validate generatePskSecret

2016-03-19T11:56:27.309Z - info: Running on android test: 76. Start and stop ThaliNotificationServer

2016-03-19T11:56:27.878Z - info: Running on android test: 77. Pass an empty array to ThaliNotificationServer.start

2016-03-19T11:56:28.464Z - info: Running on android test: 78. Pass a string to ThaliNotificationServer.start

2016-03-19T11:56:29.059Z - info: Running on android test: 79. Pass an empty parameter to ThaliNotificationServer.start

2016-03-19T11:56:29.930Z - info: Running on android test: 80. Make an HTTP request to /NotificationBeacons

2016-03-19T11:56:30.794Z - info: Running on android test: 81. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-19T11:56:31.461Z - info: Running on android test: 82. Make an HTTP request to /NotificationBeaconsbefore calling start

2016-03-19T11:56:32.084Z - info: Running on android test: 83. #testThaliPeerAction - test getters

2016-03-19T11:56:32.687Z - info: Running on android test: 84. #testThaliPeerAction - start and kill

2016-03-19T11:56:33.252Z - info: Running on android test: 85. #testThaliPeerAction - double start

2016-03-19T11:56:33.713Z - info: Running on android test: 86. #testThaliPeerAction - start after kill

2016-03-19T11:56:34.195Z - info: Running on android test: 87. #testThaliPeerAction - make sure ids are unique

2016-03-19T11:56:34.688Z - info: Running on android test: 88. Test PeerConnectionInformation basics

2016-03-19T11:56:35.163Z - info: Running on android test: 89. Test PeerDictionary basic functionality

2016-03-19T11:56:35.880Z - info: Running on android test: 90. Test PeerDictionary with multiple entries.

2016-03-19T11:56:37.858Z - info: Running on android test: 91. RESOLVED entries are removed before WAITING state entry.

2016-03-19T11:56:39.132Z - info: Running on android test: 92. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-19T11:56:40.257Z - info: Running on android test: 93. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-19T11:56:40.996Z - debug: Socket disconnected: ping timeout 1 (Apple-Iphone5s-1)

2016-03-19T11:56:41.365Z - info: Running on android test: 94. #ThaliPeerPoolInterface - bad enqueues

2016-03-19T11:56:41.819Z - info: Running on android test: 95. #ThaliPeerPoolInterface - do not allow same object type

2016-03-19T11:56:42.756Z - info: Running on android test: 96. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-19T11:56:44.091Z - info: Running on android test: 97. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent

2016-03-19T11:56:45.598Z - info: Running on android test: 98. compareBufferArrays

2016-03-19T11:56:47.253Z - info: Running on android test: 99. Call start twice and get error

2016-03-19T11:56:47.760Z - info: Running on android test: 100. Start and make sure it runs

2016-03-19T11:56:48.541Z - info: Running on android test: 101. Make sure getTimeWhenRun is right after start

2016-03-19T11:56:49.344Z - info: Running on android test: 102. Make sure getTimeWhenRun is -1 after function is called

2016-03-19T11:56:50.354Z - info: Running on android test: 103. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-19T11:56:51.831Z - info: Running on android test: 104. Test TransientState

2016-03-19T11:56:52.678Z - info: Running on android test: 105. No peers and empty database

2016-03-19T11:56:53.347Z - info: Running on android test: 106. One peer and empty DB

2016-03-19T11:56:54.308Z - info: Running on android test: 107. One peer with _Local set behind current seq

2016-03-19T11:56:55.194Z - info: Running on android test: 108. One peer with _Local set equal to current seq

2016-03-19T11:56:55.867Z - info: Running on android test: 109. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-19T11:56:56.783Z - info: Running on android test: 110. Three peers, one not in DB, one behind and one ahead

2016-03-19T11:56:57.594Z - info: Running on android test: 111. More than maximum peers, make sure we only send maximum allowed

2016-03-19T11:56:59.268Z - info: Running on android test: 112. two peers with empty DB, update the doc

2016-03-19T11:57:00.574Z - info: Running on android test: 113. add doc and make sure tokens refresh when they expire

2016-03-19T11:57:02.808Z - info: Running on android test: 114. start and stop and start and stop

2016-03-19T11:57:04.341Z - info: Running on android test: 115. two identical starts in a row

2016-03-19T11:57:05.185Z - info: Running on android test: 116. two different starts in a row

2016-03-19T11:57:06.395Z - info: Running on android test: 117. two stops and a start and two stops

2016-03-19T11:57:07.283Z - info: Running on android test: 118. we properly enqueue requests so no then needed

2016-03-19T11:57:08.960Z - info: Running on android test: 119. test calculateSeqPointKeyId

2016-03-19T11:57:09.734Z - info: Running on android test: 120. can create servers manager

2016-03-19T11:57:10.221Z - info: Running on android test: 121. calling stop without start causes error

2016-03-19T11:57:10.601Z - info: Running on android test: 122. can start/stop servers manager

2016-03-19T11:57:10.977Z - info: Running on android test: 123. starting twice resolves with listening port

2016-03-19T11:57:11.390Z - info: Running on android test: 124. terminateIncomingConnection will terminate a connection

2016-03-19T11:57:11.966Z - info: Running on android test: 125. terminate an Outgoing connection will terminate the server

2016-03-19T11:57:12.547Z - info: Running on android test: 126. terminate an Outgoing connection with wrong arguments is not harmful

2016-03-19T11:57:13.176Z - info: Running on android test: 127. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-19T11:57:13.785Z - info: Running on android test: 128. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-19T11:57:14.260Z - info: Running on android test: 129. messages with invalid location or USN should be ignored

2016-03-19T11:57:14.699Z - info: Running on android test: 130. verify that Thali-specific messages are filtered correctly

2016-03-19T11:57:15.161Z - info: Running on android test: 131. #startListeningForAdvertisements should fail if start not called

2016-03-19T11:57:15.534Z - info: Running on android test: 132. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-19T11:57:16.099Z - info: Running on android test: 133. #start should fail if called twice in a row

2016-03-19T11:57:16.679Z - info: Running on android test: 134. should not be started after stop is called

2016-03-19T11:57:17.349Z - info: Running on android test: 135. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-19T11:57:17.859Z - info: Running on android test: 136. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-19T11:57:18.701Z - info: Running on android test: 137. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-19T11:57:19.469Z - info: Running on android test: 138. #stop can be called multiple times in a row

2016-03-19T11:57:19.919Z - info: Running on android test: 139. #startListeningForAdvertisements can be called multiple times in a row

2016-03-19T11:57:20.355Z - info: Running on android test: 140. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-19T11:57:20.729Z - info: Running on android test: 141. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-19T11:57:21.107Z - info: Running on android test: 142. functions are run from a queue in the right order

2016-03-19T11:57:21.522Z - info: Running on android test: 143. #ThaliPeerPoolDefault - single action

2016-03-19T11:57:21.902Z - info: Running on android test: 144. #ThaliPeerPoolDefault - multiple actions

2016-03-19T11:57:22.312Z - info: Test run on android complete

2016-03-19T11:57:22.314Z - info: 

-== UNIT TEST RESULTS ==-
2016-03-19T11:57:22.316Z - info: PLATFORM: android
2016-03-19T11:57:22.317Z - info: RESULT: FAIL
2016-03-19T11:57:22.317Z - info: 144 of 144 tests completed

2016-03-19T11:57:22.319Z - info: 143/144 passed (1 failures)

2016-03-19T11:57:22.319Z - info: --- Test Details ---



2016-03-19T11:57:22.321Z - info: 1. calling createNativeListener directly rejects - pass

2016-03-19T11:57:22.323Z - info: 2. emits incomingConnectionState - pass

2016-03-19T11:57:22.323Z - info: 3. emits routerPortConnectionFailed - pass

2016-03-19T11:57:22.324Z - info: 4. native server connections all up - pass
2016-03-19T11:57:22.325Z - info: 5. native server - closing incoming stream cleans outgoing socket - pass

2016-03-19T11:57:22.326Z - info: 6. native server - closing incoming connection cleans outgoing socket - pass

2016-03-19T11:57:22.327Z - info: 7. native server - closing outgoing socket cleans associated mux stream - pass

2016-03-19T11:57:22.328Z - info: 8. native server - closing the whole server cleans everything up - pass
2016-03-19T11:57:22.328Z - info: 9. native server - we can get a ton of connections and data through and still clean up the server completely - pass

2016-03-19T11:57:22.329Z - info: 10. native server - simulate mux failure, make sure everything is cleaned up - pass
2016-03-19T11:57:22.330Z - info: 11. native server - timing out the incoming connection cleans everything up - pass
2016-03-19T11:57:22.331Z - info: 12. closeAll can close even when connections open - pass

2016-03-19T11:57:22.331Z - info: 13. closeAll with promise - pass

2016-03-19T11:57:22.332Z - info: 14. multiplex can send data - pass

2016-03-19T11:57:22.333Z - info: 15. enqueue and run in order - pass
2016-03-19T11:57:22.334Z - info: 16. enqueueAtTop and run backwards - pass

2016-03-19T11:57:22.335Z - info: 17. mix enqueue and enqueueAtTop - pass

2016-03-19T11:57:22.335Z - info: 18. queues handled independently - pass

2016-03-19T11:57:22.336Z - info: 19. basic - pass

2016-03-19T11:57:22.337Z - info: 20. another - pass

2016-03-19T11:57:22.349Z - info: 21. #startListeningForAdvertisements should fail if start not called - pass

2016-03-19T11:57:22.350Z - info: 22. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-19T11:57:22.350Z - info: 23. should be able to call #stopListeningForAdvertisements many times - pass

2016-03-19T11:57:22.351Z - info: 24. should be able to call #startListeningForAdvertisements many times - pass

2016-03-19T11:57:22.352Z - info: 25. should be able to call #startUpdateAdvertisingAndListening many times - pass

2016-03-19T11:57:22.353Z - info: 26. should be able to call #stopAdvertisingAndListening many times - pass

2016-03-19T11:57:22.354Z - info: 27. #start should fail if called twice in a row - pass
2016-03-19T11:57:22.354Z - info: 28. does not emit duplicate discoveryAdvertisingStateUpdate - pass

2016-03-19T11:57:22.355Z - info: 29. does not send duplicate availability changes - pass

2016-03-19T11:57:22.356Z - info: 30. can get the network status - pass

2016-03-19T11:57:22.357Z - info: 31. wifi peer is marked unavailable if announcements stop - pass

2016-03-19T11:57:22.358Z - info: 32. Can call start/stopListeningForAdvertisements - pass
2016-03-19T11:57:22.358Z - info: 33. Calling startListeningForAdvertisements twice is NOT an error - pass

2016-03-19T11:57:22.359Z - info: 34. Can call start/stopUpdateAdvertisingAndListening - pass

2016-03-19T11:57:22.360Z - info: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error - pass

2016-03-19T11:57:22.361Z - info: 36. peerAvailabilityChange is called - pass

2016-03-19T11:57:22.362Z - info: 37. Can connect to a remote peer - pass
2016-03-19T11:57:22.362Z - info: 38. Can shift large amounts of data - pass

2016-03-19T11:57:22.363Z - info: 39. #startListeningForAdvertisements should fail if start not called - pass

2016-03-19T11:57:22.364Z - info: 40. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-19T11:57:22.365Z - info: 41. should be able to call #stopListeningForAdvertisements many times - pass
2016-03-19T11:57:22.366Z - info: 42. should be able to call #startListeningForAdvertisements many times - pass

2016-03-19T11:57:22.366Z - info: 43. should be able to call #startUpdateAdvertisingAndListening many times - pass

2016-03-19T11:57:22.367Z - info: 44. should be able to call #stopAdvertisingAndListening many times - pass

2016-03-19T11:57:22.368Z - info: 45. can get the network status before starting - pass

2016-03-19T11:57:22.369Z - info: 46. error returned with bad router - pass
2016-03-19T11:57:22.370Z - info: 47. can do HTTP requests between peers - fail

2016-03-19T11:57:22.371Z - info: 48. Can do requests between peers after start and stop - pass

2016-03-19T11:57:22.371Z - info: 49. We successfully receive and replay discoveryAdvertisingStateUpdate - pass

2016-03-19T11:57:22.372Z - info: 50. Test BEACONS_RETRIEVED_AND_PARSED locally - pass

2016-03-19T11:57:22.373Z - info: 51. Test HTTP_BAD_RESPONSE locally - pass
2016-03-19T11:57:22.374Z - info: 52. Test NETWORK_PROBLEM locally - pass

2016-03-19T11:57:22.375Z - info: 53. Test timeout locally - pass

2016-03-19T11:57:22.375Z - info: 54. Call the start two times - pass

2016-03-19T11:57:22.376Z - info: 55. Call the kill before calling the start - pass

2016-03-19T11:57:22.377Z - info: 56. Call the kill immediately after the start - pass

2016-03-19T11:57:22.378Z - info: 57. Call the kill while waiting a response from the server - pass

2016-03-19T11:57:22.379Z - info: 58. Test to exceed the max content size locally - pass
2016-03-19T11:57:22.380Z - info: 59. Close the server socket while the client is waiting a response from the server. Local test. - pass

2016-03-19T11:57:22.380Z - info: 60. Close the client socket while the client is waiting a response from the server. Local test. - pass

2016-03-19T11:57:22.381Z - info: 61. #generatePreambleAndBeacons bad args - pass

2016-03-19T11:57:22.382Z - info: 62. #generatePreambleAndBeacons empty keys to notify - pass
2016-03-19T11:57:22.383Z - info: 63. #generatePreambleAndBeacons multiple keys to notify - pass

2016-03-19T11:57:22.384Z - info: 64. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass

2016-03-19T11:57:22.385Z - info: 65. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass

2016-03-19T11:57:22.385Z - info: 66. #parseBeacons expiration out of range lower - pass
2016-03-19T11:57:22.386Z - info: 67. #parseBeacons expiration out of range lower - pass
2016-03-19T11:57:22.387Z - info: 68. #parseBeacons no beacons returns null - pass
2016-03-19T11:57:22.388Z - info: 69. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass

2016-03-19T11:57:22.388Z - info: 70. #parseBeacons addressBookCallback fails decrypt - pass
2016-03-19T11:57:22.389Z - info: 71. #parseBeacons addressBookCallback returns no matches - pass

2016-03-19T11:57:22.390Z - info: 72. #parseBeacons addressBookCallback returns spurious match - pass

2016-03-19T11:57:22.391Z - info: 73. #parseBeacons addressBookCallback returns public key - pass
2016-03-19T11:57:22.392Z - info: 74. validate generatePskIdentityField - pass

2016-03-19T11:57:22.392Z - info: 75. validate generatePskSecret - pass

2016-03-19T11:57:22.393Z - info: 76. Start and stop ThaliNotificationServer - pass

2016-03-19T11:57:22.394Z - info: 77. Pass an empty array to ThaliNotificationServer.start - pass
2016-03-19T11:57:22.395Z - info: 78. Pass a string to ThaliNotificationServer.start - pass

2016-03-19T11:57:22.395Z - info: 79. Pass an empty parameter to ThaliNotificationServer.start - pass

2016-03-19T11:57:22.396Z - info: 80. Make an HTTP request to /NotificationBeacons - pass

2016-03-19T11:57:22.397Z - info: 81. Make an HTTP request to /NotificationBeacons (no keys) - pass
2016-03-19T11:57:22.398Z - info: 82. Make an HTTP request to /NotificationBeaconsbefore calling start - pass

2016-03-19T11:57:22.399Z - info: 83. #testThaliPeerAction - test getters - pass

2016-03-19T11:57:22.399Z - info: 84. #testThaliPeerAction - start and kill - pass

2016-03-19T11:57:22.400Z - info: 85. #testThaliPeerAction - double start - pass
2016-03-19T11:57:22.401Z - info: 86. #testThaliPeerAction - start after kill - pass

2016-03-19T11:57:22.402Z - info: 87. #testThaliPeerAction - make sure ids are unique - pass

2016-03-19T11:57:22.403Z - info: 88. Test PeerConnectionInformation basics - pass
2016-03-19T11:57:22.403Z - info: 89. Test PeerDictionary basic functionality - pass
2016-03-19T11:57:22.404Z - info: 90. Test PeerDictionary with multiple entries. - pass
2016-03-19T11:57:22.404Z - info: 91. RESOLVED entries are removed before WAITING state entry. - pass
2016-03-19T11:57:22.405Z - info: 92. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass
2016-03-19T11:57:22.406Z - info: 93. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass
2016-03-19T11:57:22.406Z - info: 94. #ThaliPeerPoolInterface - bad enqueues - pass
2016-03-19T11:57:22.407Z - info: 95. #ThaliPeerPoolInterface - do not allow same object type - pass
2016-03-19T11:57:22.407Z - info: 96. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass
2016-03-19T11:57:22.408Z - info: 97. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent - pass
2016-03-19T11:57:22.409Z - info: 98. compareBufferArrays - pass
2016-03-19T11:57:22.409Z - info: 99. Call start twice and get error - pass
2016-03-19T11:57:22.410Z - info: 100. Start and make sure it runs - pass
2016-03-19T11:57:22.410Z - info: 101. Make sure getTimeWhenRun is right after start - pass
2016-03-19T11:57:22.411Z - info: 102. Make sure getTimeWhenRun is -1 after function is called - pass
2016-03-19T11:57:22.411Z - info: 103. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass
2016-03-19T11:57:22.412Z - info: 104. Test TransientState - pass
2016-03-19T11:57:22.415Z - info: 105. No peers and empty database - pass
2016-03-19T11:57:22.416Z - info: 106. One peer and empty DB - pass

2016-03-19T11:57:22.417Z - info: 107. One peer with _Local set behind current seq - pass
2016-03-19T11:57:22.418Z - info: 108. One peer with _Local set equal to current seq - pass

2016-03-19T11:57:22.419Z - info: 109. One peer with _Local set ahead of current seq (and no this should not happen) - pass

2016-03-19T11:57:22.420Z - info: 110. Three peers, one not in DB, one behind and one ahead - pass
2016-03-19T11:57:22.420Z - info: 111. More than maximum peers, make sure we only send maximum allowed - pass

2016-03-19T11:57:22.421Z - info: 112. two peers with empty DB, update the doc - pass

2016-03-19T11:57:22.422Z - info: 113. add doc and make sure tokens refresh when they expire - pass

2016-03-19T11:57:22.423Z - info: 114. start and stop and start and stop - pass
2016-03-19T11:57:22.424Z - info: 115. two identical starts in a row - pass

2016-03-19T11:57:22.424Z - info: 116. two different starts in a row - pass

2016-03-19T11:57:22.425Z - info: 117. two stops and a start and two stops - pass

2016-03-19T11:57:22.426Z - info: 118. we properly enqueue requests so no then needed - pass
2016-03-19T11:57:22.427Z - info: 119. test calculateSeqPointKeyId - pass

2016-03-19T11:57:22.428Z - info: 120. can create servers manager - pass

2016-03-19T11:57:22.428Z - info: 121. calling stop without start causes error - pass

2016-03-19T11:57:22.429Z - info: 122. can start/stop servers manager - pass
2016-03-19T11:57:22.430Z - info: 123. starting twice resolves with listening port - pass

2016-03-19T11:57:22.431Z - info: 124. terminateIncomingConnection will terminate a connection - pass

2016-03-19T11:57:22.432Z - info: 125. terminate an Outgoing connection will terminate the server - pass

2016-03-19T11:57:22.433Z - info: 126. terminate an Outgoing connection with wrong arguments is not harmful - pass

2016-03-19T11:57:22.433Z - info: 127. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass
2016-03-19T11:57:22.434Z - info: 128. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-03-19T11:57:22.435Z - info: 129. messages with invalid location or USN should be ignored - pass

2016-03-19T11:57:22.436Z - info: 130. verify that Thali-specific messages are filtered correctly - pass

2016-03-19T11:57:22.437Z - info: 131. #startListeningForAdvertisements should fail if start not called - pass

2016-03-19T11:57:22.437Z - info: 132. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-19T11:57:22.438Z - info: 133. #start should fail if called twice in a row - pass

2016-03-19T11:57:22.439Z - info: 134. should not be started after stop is called - pass

2016-03-19T11:57:22.440Z - info: 135. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass

2016-03-19T11:57:22.441Z - info: 136. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass
2016-03-19T11:57:22.441Z - info: 137. #startUpdateAdvertisingAndListening should start hosting given router object - pass

2016-03-19T11:57:22.442Z - info: 138. #stop can be called multiple times in a row - pass

2016-03-19T11:57:22.443Z - info: 139. #startListeningForAdvertisements can be called multiple times in a row - pass

2016-03-19T11:57:22.444Z - info: 140. #stopListeningForAdvertisements can be called multiple times in a row - pass
2016-03-19T11:57:22.445Z - info: 141. #stopAdvertisingAndListening can be called multiple times in a row - pass

2016-03-19T11:57:22.445Z - info: 142. functions are run from a queue in the right order - pass

2016-03-19T11:57:22.446Z - info: 143. #ThaliPeerPoolDefault - single action - pass

2016-03-19T11:57:22.447Z - info: 144. #ThaliPeerPoolDefault - multiple actions - pass

2016-03-19T11:57:22.448Z - info: 

-== END ==-

2016-03-19T11:57:23.355Z - debug: Socket disconnected: transport close 0 (samsung-SM-N910C)

2016-03-19T11:57:23.506Z - debug: Socket disconnected: transport close 4 (LGE-LG-H815)

2016-03-19T11:57:35.272Z - debug: Device presented: LGE-VS986 (android) unittest socket:6

2016-03-19T11:57:35.275Z - info: Discarding surplus device: LGE-VS986

2016-03-19T11:59:18.747Z - debug: Socket disconnected: transport close 6 (LGE-VS986)

2016-03-19T12:13:18.083Z - debug: Socket disconnected: transport close 2 (Apple-Iphone5-1)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/62548124d9c0fd9_More_thaliMobileNativeWrapper_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/62548124d9c0fd9_More_thaliMobileNativeWrapper_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/62548124d9c0fd9_More_thaliMobileNativeWrapper_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/62548124d9c0fd9_More_thaliMobileNativeWrapper_vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/62548124d9c0fd9_More_thaliMobileNativeWrapper_vjrantal/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```
Install debug:
null
	pkg: /data/local/tmp/android_0_62548124d9c0fd9.apk
Success

5127 KB/s (42409116 bytes in 8.077s)

STOP log received from  f56ad48d Test has  SUCCEEDED
Device test finished on f56ad48d 
Android task is completed. [SUCCESS]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62548124d9c0fd9_More_thaliMobileNativeWrapper_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
Install debug:
null
	pkg: /data/local/tmp/android_0_62548124d9c0fd9.apk

2654 KB/s (42409116 bytes in 15.603s)
- waiting for device -

Install debug:
null
	pkg: /data/local/tmp/android_0_62548124d9c0fd9.apk
Success

3316 KB/s (42409116 bytes in 12.488s)

STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:0 
child process exited with code 0 on device 7970f88c 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62548124d9c0fd9_More_thaliMobileNativeWrapper_vjrantal/thali02_samsung-SM-A300FU.md)

[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/62548124d9c0fd9_More_thaliMobileNativeWrapper_vjrantal/thali02_LGE-LG-D722.md)

####Node name: thali03
Console output:
```
Install debug:
null
	pkg: /data/local/tmp/android_0_62548124d9c0fd9.apk

4922 KB/s (42409116 bytes in 8.412s)
- waiting for device -

STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Android task is completed. [SUCCESS]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/62548124d9c0fd9_More_thaliMobileNativeWrapper_vjrantal/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
Install debug:
null
	pkg: /data/local/tmp/android_0_62548124d9c0fd9.apk
Success

3320 KB/s (42409116 bytes in 12.473s)

STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on ZX1C223JKW 
Android task is completed. [SUCCESS]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/62548124d9c0fd9_More_thaliMobileNativeWrapper_vjrantal/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
Install debug:
null
	pkg: /data/local/tmp/android_0_62548124d9c0fd9.apk
Success

4518 KB/s (42409116 bytes in 9.164s)

STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Android task is completed. [SUCCESS]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/62548124d9c0fd9_More_thaliMobileNativeWrapper_vjrantal/thali05_LGE-LG-H815.md)

####Node name: thali06
Console output:
```
Install debug:
null
	pkg: /data/local/tmp/android_0_62548124d9c0fd9.apk
Success

1926 KB/s (42409116 bytes in 21.492s)

STOP log received from  FA55PYS00566 Test has  SUCCEEDED
Device test finished on FA55PYS00566 
Android task is completed. [SUCCESS]
```
[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/62548124d9c0fd9_More_thaliMobileNativeWrapper_vjrantal/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
Install debug:
null
	pkg: /data/local/tmp/android_0_62548124d9c0fd9.apk
Success

4847 KB/s (42409116 bytes in 8.543s)

STOP log received from  4db5c8cc Test has  SUCCEEDED
Device test finished on 4db5c8cc 
Android task is completed. [SUCCESS]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62548124d9c0fd9_More_thaliMobileNativeWrapper_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
Install debug:
null
	pkg: /data/local/tmp/android_0_62548124d9c0fd9.apk
Success

4840 KB/s (42409116 bytes in 8.556s)

STOP log received from  4325e43f Test has  SUCCEEDED
Device test finished on 4325e43f 
Android task is completed. [SUCCESS]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62548124d9c0fd9_More_thaliMobileNativeWrapper_vjrantal/thali08_samsung-SM-A300FU.md)





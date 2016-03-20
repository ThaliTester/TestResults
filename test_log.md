#### Test 625481245382a4d Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":9}}
2016-03-20T11:42:55.219Z - info: listening on *:3000

2016-03-20T11:42:57.497Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:0

2016-03-20T11:42:57.547Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:1

2016-03-20T11:42:57.747Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:2

2016-03-20T11:42:57.751Z - info: Required number of ios devices presented (2)

2016-03-20T11:42:57.757Z - info: Starting unit test run for platform: ios

2016-03-20T11:42:58.555Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-20T11:42:59.170Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-20T11:42:59.497Z - debug: Device presented: HTC-HTC One M8s (android) unittest socket:4

2016-03-20T11:42:59.498Z - info: Required number of android devices presented (2)

2016-03-20T11:42:59.500Z - info: Starting unit test run for platform: android

2016-03-20T11:42:59.524Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:3

2016-03-20T11:42:59.525Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-20T11:42:59.639Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-20T11:43:00.067Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-20T11:43:00.223Z - info: Running on ios test: 4. native server connections all up

2016-03-20T11:43:00.729Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:5

2016-03-20T11:43:00.730Z - info: Discarding surplus device: LGE-LG-H815

2016-03-20T11:43:01.378Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-20T11:43:01.704Z - debug: Socket disconnected: transport close 5 (LGE-LG-H815)

2016-03-20T11:43:01.856Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-20T11:43:01.931Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-20T11:43:02.171Z - debug: Socket disconnected: transport close 3 (Apple-Iphone5s-1)

2016-03-20T11:43:02.426Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-20T11:43:02.553Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-20T11:43:02.916Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-20T11:43:03.095Z - info: Running on android test: 4. native server connections all up

2016-03-20T11:43:03.528Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-20T11:43:03.673Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-20T11:43:04.174Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-20T11:43:04.520Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-20T11:43:04.702Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-20T11:43:05.206Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-20T11:43:05.667Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-20T11:43:06.218Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-20T11:43:06.684Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-20T11:43:06.700Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-20T11:43:07.065Z - info: Running on ios test: 13. closeAll with promise

2016-03-20T11:43:07.200Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-20T11:43:07.511Z - info: Running on ios test: 14. multiplex can send data

2016-03-20T11:43:07.697Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-20T11:43:08.004Z - info: Running on ios test: 15. enqueue and run in order

2016-03-20T11:43:08.153Z - info: Running on android test: 13. closeAll with promise

2016-03-20T11:43:08.606Z - info: Running on android test: 14. multiplex can send data

2016-03-20T11:43:08.738Z - info: Running on ios test: 16. enqueueAtTop and run backwards

2016-03-20T11:43:08.974Z - info: Running on android test: 15. enqueue and run in order

2016-03-20T11:43:09.119Z - info: Running on ios test: 17. mix enqueue and enqueueAtTop

2016-03-20T11:43:09.703Z - info: Running on android test: 16. enqueueAtTop and run backwards

2016-03-20T11:43:09.758Z - info: Running on ios test: 18. queues handled independently

2016-03-20T11:43:10.266Z - info: Running on ios test: 19. basic

2016-03-20T11:43:10.269Z - info: Running on android test: 17. mix enqueue and enqueueAtTop

2016-03-20T11:43:10.849Z - info: Running on ios test: 20. another

2016-03-20T11:43:10.872Z - info: Running on android test: 18. queues handled independently

2016-03-20T11:43:11.397Z - info: Running on android test: 19. basic

2016-03-20T11:43:11.407Z - info: Running on ios test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-20T11:43:11.876Z - info: Running on android test: 20. another

2016-03-20T11:43:11.985Z - info: Running on ios test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-20T11:43:12.419Z - info: Running on android test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-20T11:43:12.637Z - info: Running on ios test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-20T11:43:13.045Z - info: Running on android test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-20T11:43:13.185Z - info: Running on ios test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-20T11:43:13.541Z - info: Running on android test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-20T11:43:13.928Z - info: Running on ios test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-20T11:43:14.213Z - info: Running on android test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-20T11:43:15.423Z - info: Running on ios test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-20T11:43:16.821Z - info: Running on ios test: 27. #start should fail if called twice in a row

2016-03-20T11:43:18.302Z - info: Running on ios test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-20T11:43:18.993Z - info: Running on ios test: 29. does not send duplicate availability changes

2016-03-20T11:43:19.771Z - info: Running on ios test: 30. can get the network status

2016-03-20T11:43:21.225Z - info: Running on android test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-20T11:43:22.528Z - info: Running on ios test: 31. wifi peer is marked unavailable if announcements stop

2016-03-20T11:43:24.354Z - info: Running on ios test: 32. Can call start/stopListeningForAdvertisements

2016-03-20T11:43:24.997Z - info: Running on ios test: 33. Calling startListeningForAdvertisements twice is NOT an error

2016-03-20T11:43:26.111Z - info: Running on ios test: 34. Can call start/stopUpdateAdvertisingAndListening

2016-03-20T11:43:28.710Z - info: Running on android test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-20T11:43:28.817Z - info: Running on ios test: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-20T11:43:29.408Z - info: Running on android test: 27. #start should fail if called twice in a row

2016-03-20T11:43:29.672Z - info: Running on ios test: 36. peerAvailabilityChange is called

2016-03-20T11:43:30.100Z - info: Running on android test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-20T11:43:33.328Z - info: Running on ios test: 37. Can connect to a remote peer

2016-03-20T11:43:36.771Z - info: Running on android test: 29. does not send duplicate availability changes

2016-03-20T11:43:37.289Z - info: Running on android test: 30. can get the network status

2016-03-20T11:43:37.785Z - info: Running on android test: 31. wifi peer is marked unavailable if announcements stop

2016-03-20T11:43:39.342Z - info: Running on android test: 32. Can call start/stopListeningForAdvertisements

2016-03-20T11:43:42.825Z - info: Running on android test: 33. Calling startListeningForAdvertisements twice is NOT an error

2016-03-20T11:43:49.525Z - info: Running on android test: 34. Can call start/stopUpdateAdvertisingAndListening

2016-03-20T11:43:51.023Z - debug: Socket disconnected: transport close 7 (NOT YET SET)

2016-03-20T11:43:51.139Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:6

2016-03-20T11:43:51.140Z - info: Discarding surplus device: Apple-Iphone6-1

2016-03-20T11:43:53.068Z - info: Running on android test: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-20T11:43:53.925Z - debug: Socket disconnected: transport close 6 (Apple-Iphone6-1)

2016-03-20T11:44:00.051Z - info: Running on android test: 36. peerAvailabilityChange is called

2016-03-20T11:45:43.751Z - info: Running on ios test: 38. Can shift large amounts of data

2016-03-20T11:46:53.389Z - info: Running on ios test: 39. #startListeningForAdvertisements should fail if start not called

2016-03-20T11:46:54.107Z - info: Running on ios test: 40. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-20T11:46:54.618Z - info: Running on ios test: 41. should be able to call #stopListeningForAdvertisements many times

2016-03-20T11:46:55.108Z - info: Running on ios test: 42. should be able to call #startListeningForAdvertisements many times

2016-03-20T11:46:55.686Z - info: Running on ios test: 43. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-20T11:46:56.345Z - info: Running on ios test: 44. should be able to call #stopAdvertisingAndListening many times

2016-03-20T11:46:57.249Z - info: Running on ios test: 45. can get the network status before starting

2016-03-20T11:46:58.679Z - info: Running on ios test: 46. error returned with bad router

2016-03-20T11:46:59.314Z - info: Running on ios test: 47. can do HTTP requests between peers

2016-03-20T11:47:11.934Z - info: Running on ios test: 48. Can do requests between peers after start and stop

2016-03-20T11:47:12.956Z - info: Running on ios test: 49. We successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-20T11:47:13.944Z - info: Running on ios test: 50. Test BEACONS_RETRIEVED_AND_PARSED locally

2016-03-20T11:47:16.230Z - info: Running on ios test: 51. Test HTTP_BAD_RESPONSE locally

2016-03-20T11:47:19.253Z - info: Running on ios test: 52. Test NETWORK_PROBLEM locally

2016-03-20T11:47:20.868Z - info: Running on ios test: 53. Test timeout locally

2016-03-20T11:47:23.490Z - info: Running on ios test: 54. Call the start two times

2016-03-20T11:47:24.646Z - info: Running on ios test: 55. Call the kill before calling the start

2016-03-20T11:47:28.311Z - info: Running on ios test: 56. Call the kill immediately after the start

2016-03-20T11:47:29.055Z - info: Running on ios test: 57. Call the kill while waiting a response from the server

2016-03-20T11:47:35.498Z - info: Running on ios test: 58. Test to exceed the max content size locally

2016-03-20T11:47:36.328Z - info: Running on ios test: 59. Close the server socket while the client is waiting a response from the server. Local test.

2016-03-20T11:47:38.940Z - info: Running on ios test: 60. Close the client socket while the client is waiting a response from the server. Local test.

2016-03-20T11:47:41.638Z - info: Running on ios test: 61. #generatePreambleAndBeacons bad args

2016-03-20T11:47:42.193Z - info: Running on ios test: 62. #generatePreambleAndBeacons empty keys to notify

2016-03-20T11:47:42.655Z - info: Running on ios test: 63. #generatePreambleAndBeacons multiple keys to notify

2016-03-20T11:47:43.276Z - info: Running on ios test: 64. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-20T11:47:43.799Z - info: Running on ios test: 65. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-20T11:47:44.396Z - info: Running on ios test: 66. #parseBeacons expiration out of range lower

2016-03-20T11:47:44.943Z - info: Running on ios test: 67. #parseBeacons expiration out of range lower

2016-03-20T11:47:45.523Z - info: Running on ios test: 68. #parseBeacons no beacons returns null

2016-03-20T11:47:46.145Z - info: Running on ios test: 69. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-20T11:47:46.657Z - info: Running on ios test: 70. #parseBeacons addressBookCallback fails decrypt

2016-03-20T11:47:47.267Z - info: Running on ios test: 71. #parseBeacons addressBookCallback returns no matches

2016-03-20T11:47:47.812Z - info: Running on ios test: 72. #parseBeacons addressBookCallback returns spurious match

2016-03-20T11:47:48.334Z - info: Running on ios test: 73. #parseBeacons addressBookCallback returns public key

2016-03-20T11:47:48.783Z - info: Running on ios test: 74. validate generatePskIdentityField

2016-03-20T11:47:49.198Z - info: Running on ios test: 75. validate generatePskSecret

2016-03-20T11:47:49.826Z - info: Running on ios test: 76. Start and stop ThaliNotificationServer

2016-03-20T11:47:52.422Z - info: Running on ios test: 77. Pass an empty array to ThaliNotificationServer.start

2016-03-20T11:47:53.191Z - info: Running on ios test: 78. Pass a string to ThaliNotificationServer.start

2016-03-20T11:47:53.929Z - info: Running on ios test: 79. Pass an empty parameter to ThaliNotificationServer.start

2016-03-20T11:47:54.446Z - info: Running on ios test: 80. Make an HTTP request to /NotificationBeacons

2016-03-20T11:47:55.085Z - info: Running on ios test: 81. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-20T11:47:55.506Z - info: Running on ios test: 82. Make an HTTP request to /NotificationBeaconsbefore calling start

2016-03-20T11:47:56.049Z - info: Running on ios test: 83. #testThaliPeerAction - test getters

2016-03-20T11:47:56.848Z - info: Running on ios test: 84. #testThaliPeerAction - start and kill

2016-03-20T11:47:57.905Z - info: Running on ios test: 85. #testThaliPeerAction - double start

2016-03-20T11:47:58.484Z - info: Running on ios test: 86. #testThaliPeerAction - start after kill

2016-03-20T11:47:59.113Z - info: Running on ios test: 87. #testThaliPeerAction - make sure ids are unique

2016-03-20T11:47:59.851Z - info: Running on ios test: 88. Test PeerConnectionInformation basics

2016-03-20T11:48:00.266Z - info: Running on ios test: 89. Test PeerDictionary basic functionality

2016-03-20T11:48:00.753Z - info: Running on ios test: 90. Test PeerDictionary with multiple entries.

2016-03-20T11:48:03.246Z - info: Running on ios test: 91. RESOLVED entries are removed before WAITING state entry.

2016-03-20T11:48:04.710Z - info: Running on ios test: 92. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-20T11:48:06.293Z - info: Running on ios test: 93. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-20T11:48:07.932Z - info: Running on ios test: 94. #ThaliPeerPoolInterface - bad enqueues

2016-03-20T11:48:08.373Z - info: Running on ios test: 95. #ThaliPeerPoolInterface - do not allow same object type

2016-03-20T11:48:08.847Z - info: Running on ios test: 96. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-20T11:48:10.050Z - info: Running on ios test: 97. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent

2016-03-20T11:48:10.721Z - info: Running on ios test: 98. compareBufferArrays

2016-03-20T11:48:11.341Z - info: Running on ios test: 99. Call start twice and get error

2016-03-20T11:48:11.978Z - info: Running on ios test: 100. Start and make sure it runs

2016-03-20T11:48:12.801Z - info: Running on ios test: 101. Make sure getTimeWhenRun is right after start

2016-03-20T11:48:13.357Z - info: Running on ios test: 102. Make sure getTimeWhenRun is -1 after function is called

2016-03-20T11:48:13.800Z - info: Running on ios test: 103. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-20T11:48:14.315Z - info: Running on ios test: 104. Test TransientState

2016-03-20T11:48:14.825Z - info: Running on ios test: 105. No peers and empty database

2016-03-20T11:48:15.519Z - info: Running on ios test: 106. One peer and empty DB

2016-03-20T11:48:16.219Z - info: Running on ios test: 107. One peer with _Local set behind current seq

2016-03-20T11:48:16.935Z - info: Running on ios test: 108. One peer with _Local set equal to current seq

2016-03-20T11:48:17.780Z - info: Running on ios test: 109. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-20T11:48:18.566Z - info: Running on ios test: 110. Three peers, one not in DB, one behind and one ahead

2016-03-20T11:48:19.508Z - info: Running on ios test: 111. More than maximum peers, make sure we only send maximum allowed

2016-03-20T11:48:21.280Z - info: Running on ios test: 112. two peers with empty DB, update the doc

2016-03-20T11:48:22.466Z - info: Running on ios test: 113. add doc and make sure tokens refresh when they expire

2016-03-20T11:48:23.917Z - info: Running on ios test: 114. start and stop and start and stop

2016-03-20T11:48:25.163Z - info: Running on ios test: 115. two identical starts in a row

2016-03-20T11:48:26.151Z - info: Running on ios test: 116. two different starts in a row

2016-03-20T11:48:27.175Z - info: Running on ios test: 117. two stops and a start and two stops

2016-03-20T11:48:28.061Z - info: Running on ios test: 118. we properly enqueue requests so no then needed

2016-03-20T11:48:29.073Z - info: Running on ios test: 119. test calculateSeqPointKeyId

2016-03-20T11:48:29.515Z - info: Running on ios test: 120. can create servers manager

2016-03-20T11:48:29.942Z - info: Running on ios test: 121. calling stop without start causes error

2016-03-20T11:48:30.391Z - info: Running on ios test: 122. can start/stop servers manager

2016-03-20T11:48:30.932Z - info: Running on ios test: 123. starting twice resolves with listening port

2016-03-20T11:48:31.556Z - info: Running on ios test: 124. terminateIncomingConnection will terminate a connection

2016-03-20T11:48:32.292Z - info: Running on ios test: 125. terminate an Outgoing connection will terminate the server

2016-03-20T11:48:32.932Z - info: Running on ios test: 126. terminate an Outgoing connection with wrong arguments is not harmful

2016-03-20T11:48:33.461Z - info: Running on ios test: 127. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-20T11:48:34.009Z - info: Running on ios test: 128. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-20T11:48:34.767Z - info: Running on ios test: 129. messages with invalid location or USN should be ignored

2016-03-20T11:48:35.280Z - info: Running on ios test: 130. verify that Thali-specific messages are filtered correctly

2016-03-20T11:48:35.921Z - info: Running on ios test: 131. #startListeningForAdvertisements should fail if start not called

2016-03-20T11:48:36.687Z - info: Running on ios test: 132. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-20T11:48:37.846Z - info: Running on ios test: 133. #start should fail if called twice in a row

2016-03-20T11:48:38.389Z - info: Running on ios test: 134. should not be started after stop is called

2016-03-20T11:48:38.852Z - info: Running on ios test: 135. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-20T11:48:39.300Z - info: Running on ios test: 136. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-20T11:48:40.421Z - info: Running on ios test: 137. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-20T11:48:40.916Z - info: Running on ios test: 138. #stop can be called multiple times in a row

2016-03-20T11:48:41.429Z - info: Running on ios test: 139. #startListeningForAdvertisements can be called multiple times in a row

2016-03-20T11:48:42.020Z - info: Running on ios test: 140. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-20T11:48:42.591Z - info: Running on ios test: 141. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-20T11:48:43.056Z - info: Running on ios test: 142. functions are run from a queue in the right order

2016-03-20T11:48:43.598Z - info: Running on ios test: 143. #ThaliPeerPoolDefault - single action

2016-03-20T11:48:44.079Z - info: Running on ios test: 144. #ThaliPeerPoolDefault - multiple actions

2016-03-20T11:48:44.536Z - info: Test run on ios complete

2016-03-20T11:48:44.538Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-20T11:48:44.540Z - info: PLATFORM: ios

2016-03-20T11:48:44.541Z - info: RESULT: FAIL

2016-03-20T11:48:44.541Z - info: 144 of 144 tests completed

2016-03-20T11:48:44.542Z - info: 141/144 passed (3 failures)
2016-03-20T11:48:44.543Z - info: --- Test Details ---



2016-03-20T11:48:44.544Z - info: 1. calling createNativeListener directly rejects - pass

2016-03-20T11:48:44.545Z - info: 2. emits incomingConnectionState - pass
2016-03-20T11:48:44.545Z - info: 3. emits routerPortConnectionFailed - pass

2016-03-20T11:48:44.546Z - info: 4. native server connections all up - pass

2016-03-20T11:48:44.546Z - info: 5. native server - closing incoming stream cleans outgoing socket - pass
2016-03-20T11:48:44.547Z - info: 6. native server - closing incoming connection cleans outgoing socket - pass

2016-03-20T11:48:44.548Z - info: 7. native server - closing outgoing socket cleans associated mux stream - pass

2016-03-20T11:48:44.549Z - info: 8. native server - closing the whole server cleans everything up - pass
2016-03-20T11:48:44.549Z - info: 9. native server - we can get a ton of connections and data through and still clean up the server completely - pass

2016-03-20T11:48:44.550Z - info: 10. native server - simulate mux failure, make sure everything is cleaned up - pass

2016-03-20T11:48:44.550Z - info: 11. native server - timing out the incoming connection cleans everything up - pass
2016-03-20T11:48:44.551Z - info: 12. closeAll can close even when connections open - pass

2016-03-20T11:48:44.552Z - info: 13. closeAll with promise - pass

2016-03-20T11:48:44.552Z - info: 14. multiplex can send data - pass
2016-03-20T11:48:44.553Z - info: 15. enqueue and run in order - pass

2016-03-20T11:48:44.554Z - info: 16. enqueueAtTop and run backwards - pass

2016-03-20T11:48:44.554Z - info: 17. mix enqueue and enqueueAtTop - pass
2016-03-20T11:48:44.555Z - info: 18. queues handled independently - pass

2016-03-20T11:48:44.555Z - info: 19. basic - pass

2016-03-20T11:48:44.556Z - info: 20. another - pass
2016-03-20T11:48:44.557Z - info: 21. #startListeningForAdvertisements should fail if start not called - pass

2016-03-20T11:48:44.557Z - info: 22. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-20T11:48:44.558Z - info: 23. should be able to call #stopListeningForAdvertisements many times - pass

2016-03-20T11:48:44.559Z - info: 24. should be able to call #startListeningForAdvertisements many times - pass
2016-03-20T11:48:44.559Z - info: 25. should be able to call #startUpdateAdvertisingAndListening many times - pass

2016-03-20T11:48:44.560Z - info: 26. should be able to call #stopAdvertisingAndListening many times - pass
2016-03-20T11:48:44.561Z - info: 27. #start should fail if called twice in a row - pass

2016-03-20T11:48:44.561Z - info: 28. does not emit duplicate discoveryAdvertisingStateUpdate - pass

2016-03-20T11:48:44.562Z - info: 29. does not send duplicate availability changes - pass
2016-03-20T11:48:44.562Z - info: 30. can get the network status - pass

2016-03-20T11:48:44.563Z - info: 31. wifi peer is marked unavailable if announcements stop - pass

2016-03-20T11:48:44.564Z - info: 32. Can call start/stopListeningForAdvertisements - pass
2016-03-20T11:48:44.564Z - info: 33. Calling startListeningForAdvertisements twice is NOT an error - pass

2016-03-20T11:48:44.565Z - info: 34. Can call start/stopUpdateAdvertisingAndListening - pass

2016-03-20T11:48:44.566Z - info: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error - pass
2016-03-20T11:48:44.566Z - info: 36. peerAvailabilityChange is called - pass

2016-03-20T11:48:44.567Z - info: 37. Can connect to a remote peer - fail

2016-03-20T11:48:44.567Z - info: 38. Can shift large amounts of data - fail
2016-03-20T11:48:44.568Z - info: 39. #startListeningForAdvertisements should fail if start not called - pass

2016-03-20T11:48:44.569Z - info: 40. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-20T11:48:44.569Z - info: 41. should be able to call #stopListeningForAdvertisements many times - pass

2016-03-20T11:48:44.570Z - info: 42. should be able to call #startListeningForAdvertisements many times - pass
2016-03-20T11:48:44.571Z - info: 43. should be able to call #startUpdateAdvertisingAndListening many times - pass

2016-03-20T11:48:44.571Z - info: 44. should be able to call #stopAdvertisingAndListening many times - pass
2016-03-20T11:48:44.572Z - info: 45. can get the network status before starting - pass

2016-03-20T11:48:44.573Z - info: 46. error returned with bad router - pass

2016-03-20T11:48:44.573Z - info: 47. can do HTTP requests between peers - fail
2016-03-20T11:48:44.574Z - info: 48. Can do requests between peers after start and stop - pass

2016-03-20T11:48:44.574Z - info: 49. We successfully receive and replay discoveryAdvertisingStateUpdate - pass

2016-03-20T11:48:44.575Z - info: 50. Test BEACONS_RETRIEVED_AND_PARSED locally - pass
2016-03-20T11:48:44.576Z - info: 51. Test HTTP_BAD_RESPONSE locally - pass

2016-03-20T11:48:44.576Z - info: 52. Test NETWORK_PROBLEM locally - pass
2016-03-20T11:48:44.577Z - info: 53. Test timeout locally - pass
2016-03-20T11:48:44.578Z - info: 54. Call the start two times - pass
2016-03-20T11:48:44.578Z - info: 55. Call the kill before calling the start - pass
2016-03-20T11:48:44.579Z - info: 56. Call the kill immediately after the start - pass

2016-03-20T11:48:44.580Z - info: 57. Call the kill while waiting a response from the server - pass

2016-03-20T11:48:44.580Z - info: 58. Test to exceed the max content size locally - pass

2016-03-20T11:48:44.581Z - info: 59. Close the server socket while the client is waiting a response from the server. Local test. - pass
2016-03-20T11:48:44.582Z - info: 60. Close the client socket while the client is waiting a response from the server. Local test. - pass

2016-03-20T11:48:44.582Z - info: 61. #generatePreambleAndBeacons bad args - pass

2016-03-20T11:48:44.583Z - info: 62. #generatePreambleAndBeacons empty keys to notify - pass
2016-03-20T11:48:44.584Z - info: 63. #generatePreambleAndBeacons multiple keys to notify - pass

2016-03-20T11:48:44.584Z - info: 64. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass
2016-03-20T11:48:44.585Z - info: 65. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass

2016-03-20T11:48:44.585Z - info: 66. #parseBeacons expiration out of range lower - pass

2016-03-20T11:48:44.586Z - info: 67. #parseBeacons expiration out of range lower - pass
2016-03-20T11:48:44.587Z - info: 68. #parseBeacons no beacons returns null - pass

2016-03-20T11:48:44.587Z - info: 69. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass
2016-03-20T11:48:44.588Z - info: 70. #parseBeacons addressBookCallback fails decrypt - pass

2016-03-20T11:48:44.589Z - info: 71. #parseBeacons addressBookCallback returns no matches - pass

2016-03-20T11:48:44.589Z - info: 72. #parseBeacons addressBookCallback returns spurious match - pass
2016-03-20T11:48:44.590Z - info: 73. #parseBeacons addressBookCallback returns public key - pass

2016-03-20T11:48:44.591Z - info: 74. validate generatePskIdentityField - pass

2016-03-20T11:48:44.591Z - info: 75. validate generatePskSecret - pass
2016-03-20T11:48:44.592Z - info: 76. Start and stop ThaliNotificationServer - pass

2016-03-20T11:48:44.592Z - info: 77. Pass an empty array to ThaliNotificationServer.start - pass
2016-03-20T11:48:44.593Z - info: 78. Pass a string to ThaliNotificationServer.start - pass
2016-03-20T11:48:44.594Z - info: 79. Pass an empty parameter to ThaliNotificationServer.start - pass
2016-03-20T11:48:44.594Z - info: 80. Make an HTTP request to /NotificationBeacons - pass
2016-03-20T11:48:44.595Z - info: 81. Make an HTTP request to /NotificationBeacons (no keys) - pass
2016-03-20T11:48:44.595Z - info: 82. Make an HTTP request to /NotificationBeaconsbefore calling start - pass
2016-03-20T11:48:44.596Z - info: 83. #testThaliPeerAction - test getters - pass
2016-03-20T11:48:44.596Z - info: 84. #testThaliPeerAction - start and kill - pass
2016-03-20T11:48:44.597Z - info: 85. #testThaliPeerAction - double start - pass
2016-03-20T11:48:44.601Z - info: 86. #testThaliPeerAction - start after kill - pass
2016-03-20T11:48:44.601Z - info: 87. #testThaliPeerAction - make sure ids are unique - pass
2016-03-20T11:48:44.602Z - info: 88. Test PeerConnectionInformation basics - pass
2016-03-20T11:48:44.603Z - info: 89. Test PeerDictionary basic functionality - pass
2016-03-20T11:48:44.603Z - info: 90. Test PeerDictionary with multiple entries. - pass
2016-03-20T11:48:44.604Z - info: 91. RESOLVED entries are removed before WAITING state entry. - pass
2016-03-20T11:48:44.604Z - info: 92. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass
2016-03-20T11:48:44.605Z - info: 93. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass
2016-03-20T11:48:44.605Z - info: 94. #ThaliPeerPoolInterface - bad enqueues - pass
2016-03-20T11:48:44.606Z - info: 95. #ThaliPeerPoolInterface - do not allow same object type - pass

2016-03-20T11:48:44.607Z - info: 96. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass
2016-03-20T11:48:44.607Z - info: 97. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent - pass

2016-03-20T11:48:44.608Z - info: 98. compareBufferArrays - pass
2016-03-20T11:48:44.609Z - info: 99. Call start twice and get error - pass

2016-03-20T11:48:44.609Z - info: 100. Start and make sure it runs - pass

2016-03-20T11:48:44.610Z - info: 101. Make sure getTimeWhenRun is right after start - pass
2016-03-20T11:48:44.611Z - info: 102. Make sure getTimeWhenRun is -1 after function is called - pass

2016-03-20T11:48:44.611Z - info: 103. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass

2016-03-20T11:48:44.612Z - info: 104. Test TransientState - pass
2016-03-20T11:48:44.613Z - info: 105. No peers and empty database - pass

2016-03-20T11:48:44.613Z - info: 106. One peer and empty DB - pass

2016-03-20T11:48:44.614Z - info: 107. One peer with _Local set behind current seq - pass
2016-03-20T11:48:44.614Z - info: 108. One peer with _Local set equal to current seq - pass

2016-03-20T11:48:44.615Z - info: 109. One peer with _Local set ahead of current seq (and no this should not happen) - pass

2016-03-20T11:48:44.616Z - info: 110. Three peers, one not in DB, one behind and one ahead - pass
2016-03-20T11:48:44.616Z - info: 111. More than maximum peers, make sure we only send maximum allowed - pass

2016-03-20T11:48:44.617Z - info: 112. two peers with empty DB, update the doc - pass
2016-03-20T11:48:44.617Z - info: 113. add doc and make sure tokens refresh when they expire - pass

2016-03-20T11:48:44.618Z - info: 114. start and stop and start and stop - pass

2016-03-20T11:48:44.619Z - info: 115. two identical starts in a row - pass

2016-03-20T11:48:44.620Z - info: 116. two different starts in a row - pass
2016-03-20T11:48:44.620Z - info: 117. two stops and a start and two stops - pass

2016-03-20T11:48:44.621Z - info: 118. we properly enqueue requests so no then needed - pass
2016-03-20T11:48:44.621Z - info: 119. test calculateSeqPointKeyId - pass

2016-03-20T11:48:44.622Z - info: 120. can create servers manager - pass

2016-03-20T11:48:44.623Z - info: 121. calling stop without start causes error - pass
2016-03-20T11:48:44.623Z - info: 122. can start/stop servers manager - pass

2016-03-20T11:48:44.624Z - info: 123. starting twice resolves with listening port - pass

2016-03-20T11:48:44.624Z - info: 124. terminateIncomingConnection will terminate a connection - pass
2016-03-20T11:48:44.625Z - info: 125. terminate an Outgoing connection will terminate the server - pass

2016-03-20T11:48:44.626Z - info: 126. terminate an Outgoing connection with wrong arguments is not harmful - pass

2016-03-20T11:48:44.626Z - info: 127. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass
2016-03-20T11:48:44.627Z - info: 128. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-03-20T11:48:44.628Z - info: 129. messages with invalid location or USN should be ignored - pass

2016-03-20T11:48:44.628Z - info: 130. verify that Thali-specific messages are filtered correctly - pass
2016-03-20T11:48:44.629Z - info: 131. #startListeningForAdvertisements should fail if start not called - pass

2016-03-20T11:48:44.630Z - info: 132. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-20T11:48:44.630Z - info: 133. #start should fail if called twice in a row - pass
2016-03-20T11:48:44.631Z - info: 134. should not be started after stop is called - pass

2016-03-20T11:48:44.631Z - info: 135. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass

2016-03-20T11:48:44.632Z - info: 136. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass
2016-03-20T11:48:44.633Z - info: 137. #startUpdateAdvertisingAndListening should start hosting given router object - pass

2016-03-20T11:48:44.633Z - info: 138. #stop can be called multiple times in a row - pass

2016-03-20T11:48:44.634Z - info: 139. #startListeningForAdvertisements can be called multiple times in a row - pass
2016-03-20T11:48:44.635Z - info: 140. #stopListeningForAdvertisements can be called multiple times in a row - pass

2016-03-20T11:48:44.635Z - info: 141. #stopAdvertisingAndListening can be called multiple times in a row - pass
2016-03-20T11:48:44.636Z - info: 142. functions are run from a queue in the right order - pass

2016-03-20T11:48:44.636Z - info: 143. #ThaliPeerPoolDefault - single action - pass

2016-03-20T11:48:44.637Z - info: 144. #ThaliPeerPoolDefault - multiple actions - pass

2016-03-20T11:48:44.638Z - info: 

-== END ==-

2016-03-20T11:48:47.428Z - debug: Socket disconnected: transport close 2 (Apple-IpadAir2-1)

2016-03-20T11:48:48.330Z - debug: Socket disconnected: transport close 1 (Apple-Iphone5-1)

2016-03-20T12:03:13.531Z - debug: Socket disconnected: transport close 0 (samsung-SM-N910C)

2016-03-20T12:03:28.685Z - debug: Socket disconnected: transport close 4 (HTC-HTC One M8s)


 
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
Install debug:
null
	pkg: /data/local/tmp/android_0_625481245382a4d.apk
Success

4855 KB/s (42409244 bytes in 8.530s)

STOP log received from  f56ad48d Test has  SUCCEEDED
Device test finished on f56ad48d 
Android task is completed. [SUCCESS]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/625481245382a4d_More_thaliMobileNativeWrapper_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
Install debug:
Error: Command failed: - waiting for device -

rm: /data/local/tmp/android_0_625481245382a4d.apk: No such file or directory

- waiting for device -

Install debug:
null
	pkg: /data/local/tmp/android_0_625481245382a4d.apk
Success

2948 KB/s (42409244 bytes in 14.046s)

Install debug:
null
	pkg: /data/local/tmp/android_0_625481245382a4d.apk
Success

3487 KB/s (42409244 bytes in 11.875s)

STOP log received from  7970f88c Test has  SUCCEEDED
Device test finished on 7970f88c 
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/625481245382a4d_More_thaliMobileNativeWrapper_vjrantal/thali02_samsung-SM-A300FU.md)

[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/625481245382a4d_More_thaliMobileNativeWrapper_vjrantal/thali02_LGE-LG-D722.md)

####Node name: thali03
Console output:
```
Install debug:
null
	pkg: /data/local/tmp/android_0_625481245382a4d.apk
Success

4867 KB/s (42409244 bytes in 8.509s)

TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/625481245382a4d_More_thaliMobileNativeWrapper_vjrantal/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
Install debug:
null
	pkg: /data/local/tmp/android_0_625481245382a4d.apk
Success

2547 KB/s (42409244 bytes in 16.257s)

STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on ZX1C223JKW 
Android task is completed. [SUCCESS]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/625481245382a4d_More_thaliMobileNativeWrapper_vjrantal/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
Install debug:
null
	pkg: /data/local/tmp/android_0_625481245382a4d.apk
Success

4534 KB/s (42409244 bytes in 9.132s)

STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Android task is completed. [SUCCESS]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/625481245382a4d_More_thaliMobileNativeWrapper_vjrantal/thali05_LGE-LG-H815.md)

####Node name: thali06
Console output:
```
Install debug:
null
	pkg: /data/local/tmp/android_0_625481245382a4d.apk
Success

1978 KB/s (42409244 bytes in 20.936s)

TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:null 
child process exited with code null on device FA55PYS00566 
Android task is completed. [FAILED]
```
[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/625481245382a4d_More_thaliMobileNativeWrapper_vjrantal/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
Install debug:
null
	pkg: /data/local/tmp/android_0_625481245382a4d.apk
Success

4734 KB/s (42409244 bytes in 8.748s)

STOP log received from  4db5c8cc Test has  SUCCEEDED
Device test finished on 4db5c8cc 
Android task is completed. [SUCCESS]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/625481245382a4d_More_thaliMobileNativeWrapper_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
Install debug:
null
	pkg: /data/local/tmp/android_0_625481245382a4d.apk
Success

4728 KB/s (42409244 bytes in 8.758s)

STOP log received from  4325e43f Test has  SUCCEEDED
Device test finished on 4325e43f 
Android task is completed. [SUCCESS]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/625481245382a4d_More_thaliMobileNativeWrapper_vjrantal/thali08_samsung-SM-A300FU.md)




###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/625481245382a4d_More_thaliMobileNativeWrapper_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/625481245382a4d_More_thaliMobileNativeWrapper_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/625481245382a4d_More_thaliMobileNativeWrapper_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/625481245382a4d_More_thaliMobileNativeWrapper_vjrantal/iOS_Iphone5s-1.md)



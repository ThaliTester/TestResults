#### Test 63377149f0d5e10 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":7}}
2016-03-18T14:50:29.188Z - info: listening on *:3000

2016-03-18T14:50:31.851Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:0

2016-03-18T14:50:32.604Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:1

2016-03-18T14:50:33.172Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:2

2016-03-18T14:50:33.174Z - info: Required number of android devices presented (2)

2016-03-18T14:50:33.178Z - info: Starting unit test run for platform: android

2016-03-18T14:50:33.610Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:3

2016-03-18T14:50:33.611Z - info: Required number of ios devices presented (2)

2016-03-18T14:50:33.613Z - info: Starting unit test run for platform: ios

2016-03-18T14:50:33.712Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-18T14:50:34.058Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:4

2016-03-18T14:50:34.059Z - info: Discarding surplus device: Apple-IpadAir2-1

2016-03-18T14:50:34.210Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-18T14:50:34.586Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-18T14:50:35.029Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-18T14:50:35.066Z - info: Running on android test: 4. native server connections all up

2016-03-18T14:50:35.570Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-18T14:50:35.876Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-18T14:50:36.067Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-18T14:50:36.254Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-18T14:50:36.397Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-18T14:50:36.526Z - debug: Socket disconnected: transport close 4 (Apple-IpadAir2-1)

2016-03-18T14:50:36.676Z - info: Running on ios test: 4. native server connections all up

2016-03-18T14:50:36.889Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-18T14:50:37.183Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-18T14:50:37.347Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-18T14:50:37.734Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-18T14:50:38.224Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-18T14:50:38.814Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-18T14:50:39.425Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-18T14:50:39.477Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-18T14:50:40.092Z - info: Running on android test: 13. closeAll with promise

2016-03-18T14:50:40.499Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-18T14:50:40.886Z - info: Running on android test: 14. multiplex can send data

2016-03-18T14:50:41.541Z - info: Running on android test: 15. enqueue and run in order

2016-03-18T14:50:41.963Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-18T14:50:42.524Z - info: Running on android test: 16. enqueueAtTop and run backwards

2016-03-18T14:50:43.070Z - info: Running on android test: 17. mix enqueue and enqueueAtTop

2016-03-18T14:50:44.478Z - info: Running on android test: 18. queues handled independently

2016-03-18T14:50:44.758Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-18T14:50:44.978Z - info: Running on android test: 19. basic

2016-03-18T14:50:45.290Z - info: Running on android test: 20. another

2016-03-18T14:50:45.473Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-18T14:50:45.712Z - info: Running on android test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-18T14:50:46.129Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-18T14:50:46.247Z - info: Running on android test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-18T14:50:46.513Z - info: Running on ios test: 13. closeAll with promise

2016-03-18T14:50:46.655Z - info: Running on android test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-18T14:50:46.884Z - info: Running on ios test: 14. multiplex can send data

2016-03-18T14:50:46.990Z - info: Running on android test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-18T14:50:47.200Z - info: Running on ios test: 15. enqueue and run in order

2016-03-18T14:50:47.415Z - info: Running on android test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-18T14:50:47.804Z - info: Running on ios test: 16. enqueueAtTop and run backwards

2016-03-18T14:50:48.024Z - info: Running on android test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-18T14:50:48.257Z - info: Running on ios test: 17. mix enqueue and enqueueAtTop

2016-03-18T14:50:48.501Z - info: Running on android test: 27. #start should fail if called twice in a row

2016-03-18T14:50:48.830Z - info: Running on ios test: 18. queues handled independently

2016-03-18T14:50:48.878Z - info: Running on android test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-18T14:50:49.201Z - info: Running on ios test: 19. basic

2016-03-18T14:50:49.335Z - info: Running on android test: 29. does not send duplicate availability changes

2016-03-18T14:50:49.603Z - info: Running on ios test: 20. another

2016-03-18T14:50:49.719Z - info: Running on android test: 30. can get the network status

2016-03-18T14:50:50.006Z - info: Running on ios test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-18T14:50:50.145Z - info: Running on android test: 31. wifi peer is marked unavailable if announcements stop

2016-03-18T14:50:50.392Z - info: Running on ios test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-18T14:50:50.809Z - info: Running on ios test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-18T14:50:51.274Z - info: Running on ios test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-18T14:50:51.624Z - info: Running on android test: 32. Can call start/stopListeningForAdvertisements

2016-03-18T14:50:51.826Z - info: Running on ios test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-18T14:50:52.222Z - info: Running on android test: 33. Calling startListeningForAdvertisements twice is NOT an error

2016-03-18T14:50:52.439Z - info: Running on ios test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-18T14:50:52.879Z - info: Running on ios test: 27. #start should fail if called twice in a row

2016-03-18T14:50:53.014Z - info: Running on android test: 34. Can call start/stopUpdateAdvertisingAndListening

2016-03-18T14:50:53.316Z - info: Running on ios test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-18T14:50:53.553Z - info: Running on android test: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-18T14:50:53.694Z - info: Running on ios test: 29. does not send duplicate availability changes

2016-03-18T14:50:54.068Z - info: Running on ios test: 30. can get the network status

2016-03-18T14:50:54.471Z - info: Running on ios test: 31. wifi peer is marked unavailable if announcements stop

2016-03-18T14:50:54.628Z - info: Running on android test: 36. peerAvailabilityChange is called

2016-03-18T14:50:55.666Z - info: Running on android test: 37. Can connect to a remote peer

2016-03-18T14:50:56.030Z - info: Running on ios test: 32. Can call start/stopListeningForAdvertisements

2016-03-18T14:50:56.550Z - info: Running on ios test: 33. Calling startListeningForAdvertisements twice is NOT an error

2016-03-18T14:50:57.206Z - info: Running on ios test: 34. Can call start/stopUpdateAdvertisingAndListening

2016-03-18T14:51:00.366Z - info: Running on ios test: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-18T14:51:01.140Z - info: Running on ios test: 36. peerAvailabilityChange is called

2016-03-18T14:51:06.090Z - info: Running on ios test: 37. Can connect to a remote peer

2016-03-18T14:51:11.382Z - info: Running on android test: 38. Can shift large amounts of data

2016-03-18T14:51:18.853Z - info: Running on android test: 39. can get the network status before starting

2016-03-18T14:51:19.334Z - info: Running on android test: 40. Test BEACONS_RETRIEVED_AND_PARSED locally

2016-03-18T14:51:21.186Z - info: Running on android test: 41. Test HTTP_BAD_RESPONSE locally

2016-03-18T14:51:21.730Z - info: Running on android test: 42. Test NETWORK_PROBLEM locally

2016-03-18T14:51:24.532Z - info: Running on android test: 43. Test timeout locally

2016-03-18T14:51:26.213Z - info: Running on android test: 44. Call the start two times

2016-03-18T14:51:26.846Z - info: Running on android test: 45. Call the kill before calling the start

2016-03-18T14:51:27.552Z - info: Running on android test: 46. Call the kill immediately after the start

2016-03-18T14:51:28.218Z - info: Running on android test: 47. Call the kill while waiting a response from the server

2016-03-18T14:51:30.753Z - info: Running on android test: 48. Test to exceed the max content size locally

2016-03-18T14:51:31.386Z - info: Running on android test: 49. Close the server socket while the client is waiting a response from the server. Local test.

2016-03-18T14:51:33.952Z - info: Running on android test: 50. Close the client socket while the client is waiting a response from the server. Local test.

2016-03-18T14:51:36.438Z - info: Running on android test: 51. #generatePreambleAndBeacons bad args

2016-03-18T14:51:36.744Z - info: Running on android test: 52. #generatePreambleAndBeacons empty keys to notify

2016-03-18T14:51:37.045Z - info: Running on android test: 53. #generatePreambleAndBeacons multiple keys to notify

2016-03-18T14:51:37.445Z - info: Running on android test: 54. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-18T14:51:37.876Z - info: Running on android test: 55. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-18T14:51:38.305Z - info: Running on android test: 56. #parseBeacons expiration out of range lower

2016-03-18T14:51:38.633Z - info: Running on android test: 57. #parseBeacons expiration out of range lower

2016-03-18T14:51:38.940Z - info: Running on android test: 58. #parseBeacons no beacons returns null

2016-03-18T14:51:39.380Z - info: Running on android test: 59. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-18T14:51:39.739Z - info: Running on android test: 60. #parseBeacons addressBookCallback fails decrypt

2016-03-18T14:51:40.217Z - info: Running on android test: 61. #parseBeacons addressBookCallback returns no matches

2016-03-18T14:51:40.823Z - info: Running on android test: 62. #parseBeacons addressBookCallback returns spurious match

2016-03-18T14:51:41.533Z - info: Running on android test: 63. #parseBeacons addressBookCallback returns public key

2016-03-18T14:51:42.162Z - info: Running on android test: 64. validate generatePskIdentityField

2016-03-18T14:51:42.582Z - info: Running on android test: 65. validate generatePskSecret

2016-03-18T14:51:43.072Z - info: Running on android test: 66. Start and stop ThaliNotificationServer

2016-03-18T14:51:43.560Z - info: Running on android test: 67. Pass an empty array to ThaliNotificationServer.start

2016-03-18T14:51:44.243Z - info: Running on android test: 68. Pass a string to ThaliNotificationServer.start

2016-03-18T14:51:44.765Z - info: Running on android test: 69. Pass an empty parameter to ThaliNotificationServer.start

2016-03-18T14:51:45.251Z - info: Running on android test: 70. Make an HTTP request to /NotificationBeacons

2016-03-18T14:51:45.753Z - info: Running on android test: 71. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-18T14:51:46.259Z - info: Running on android test: 72. Make an HTTP request to /NotificationBeaconsbefore calling start

2016-03-18T14:51:46.750Z - info: Running on android test: 73. #testThaliPeerAction - test getters

2016-03-18T14:51:47.166Z - info: Running on android test: 74. #testThaliPeerAction - start and kill

2016-03-18T14:51:47.637Z - info: Running on android test: 75. #testThaliPeerAction - double start

2016-03-18T14:51:48.119Z - info: Running on android test: 76. #testThaliPeerAction - start after kill

2016-03-18T14:51:49.264Z - info: Running on android test: 77. #testThaliPeerAction - make sure ids are unique

2016-03-18T14:51:49.685Z - info: Running on android test: 78. Test PeerConnectionInformation basics

2016-03-18T14:51:50.158Z - info: Running on android test: 79. Test PeerDictionary basic functionality

2016-03-18T14:51:50.780Z - info: Running on android test: 80. Test PeerDictionary with multiple entries.

2016-03-18T14:51:52.445Z - info: Running on android test: 81. RESOLVED entries are removed before WAITING state entry.

2016-03-18T14:51:53.545Z - info: Running on android test: 82. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-18T14:51:54.559Z - info: Running on android test: 83. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-18T14:51:55.650Z - info: Running on android test: 84. #ThaliPeerPoolInterface - bad enqueues

2016-03-18T14:51:56.125Z - info: Running on android test: 85. #ThaliPeerPoolInterface - do not allow same object type

2016-03-18T14:51:56.678Z - info: Running on android test: 86. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-18T14:51:57.177Z - info: Running on android test: 87. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent

2016-03-18T14:51:57.611Z - info: Running on android test: 88. compareBufferArrays

2016-03-18T14:51:58.105Z - info: Running on android test: 89. Call start twice and get error

2016-03-18T14:51:58.581Z - info: Running on android test: 90. Start and make sure it runs

2016-03-18T14:51:59.349Z - info: Running on android test: 91. Make sure getTimeWhenRun is right after start

2016-03-18T14:51:59.956Z - info: Running on android test: 92. Make sure getTimeWhenRun is -1 after function is called

2016-03-18T14:52:00.378Z - info: Running on android test: 93. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-18T14:52:00.757Z - info: Running on android test: 94. Test TransientState

2016-03-18T14:52:01.315Z - info: Running on android test: 95. No peers and empty database

2016-03-18T14:52:02.413Z - info: Running on android test: 96. One peer and empty DB

2016-03-18T14:52:03.507Z - info: Running on android test: 97. One peer with _Local set behind current seq

2016-03-18T14:52:04.602Z - info: Running on android test: 98. One peer with _Local set equal to current seq

2016-03-18T14:52:05.575Z - info: Running on android test: 99. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-18T14:52:06.107Z - info: Running on android test: 100. Three peers, one not in DB, one behind and one ahead

2016-03-18T14:52:06.717Z - info: Running on android test: 101. More than maximum peers, make sure we only send maximum allowed

2016-03-18T14:52:07.714Z - info: Running on android test: 102. two peers with empty DB, update the doc

2016-03-18T14:52:08.424Z - info: Running on android test: 103. add doc and make sure tokens refresh when they expire

2016-03-18T14:52:09.433Z - info: Running on android test: 104. start and stop and start and stop

2016-03-18T14:52:10.236Z - info: Running on android test: 105. two identical starts in a row

2016-03-18T14:52:11.126Z - info: Running on android test: 106. two different starts in a row

2016-03-18T14:52:11.883Z - info: Running on android test: 107. two stops and a start and two stops

2016-03-18T14:52:12.532Z - info: Running on android test: 108. we properly enqueue requests so no then needed

2016-03-18T14:52:13.066Z - info: Running on android test: 109. test calculateSeqPointKeyId

2016-03-18T14:52:13.539Z - info: Running on android test: 110. can create servers manager

2016-03-18T14:52:13.908Z - info: Running on android test: 111. calling stop without start causes error

2016-03-18T14:52:14.329Z - info: Running on android test: 112. can start/stop servers manager

2016-03-18T14:52:14.653Z - info: Running on android test: 113. starting twice resolves with listening port

2016-03-18T14:52:14.937Z - info: Running on android test: 114. terminateIncomingConnection will terminate a connection

2016-03-18T14:52:15.305Z - info: Running on android test: 115. terminate an Outgoing connection will terminate the server

2016-03-18T14:52:15.650Z - info: Running on android test: 116. terminate an Outgoing connection with wrong arguments is not harmful

2016-03-18T14:52:16.070Z - info: Running on android test: 117. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-18T14:52:16.607Z - info: Running on android test: 118. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-18T14:52:17.149Z - info: Running on android test: 119. messages with invalid location or USN should be ignored

2016-03-18T14:52:17.492Z - info: Running on android test: 120. verify that Thali-specific messages are filtered correctly

2016-03-18T14:52:17.870Z - info: Running on android test: 121. #startListeningForAdvertisements should fail if start not called

2016-03-18T14:52:18.234Z - info: Running on android test: 122. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-18T14:52:18.756Z - info: Running on android test: 123. #start should fail if called twice in a row

2016-03-18T14:52:19.274Z - info: Running on android test: 124. should not be started after stop is called

2016-03-18T14:52:19.877Z - info: Running on android test: 125. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-18T14:52:20.891Z - info: Running on android test: 126. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-18T14:52:21.311Z - info: Running on android test: 127. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-18T14:52:21.860Z - info: Running on android test: 128. #stop can be called multiple times in a row

2016-03-18T14:52:22.545Z - info: Running on android test: 129. #startListeningForAdvertisements can be called multiple times in a row

2016-03-18T14:52:23.062Z - info: Running on android test: 130. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-18T14:52:23.505Z - info: Running on android test: 131. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-18T14:52:23.788Z - info: Running on android test: 132. functions are run from a queue in the right order

2016-03-18T14:52:24.150Z - info: Running on android test: 133. #ThaliPeerPoolDefault - single action

2016-03-18T14:52:24.525Z - info: Running on android test: 134. #ThaliPeerPoolDefault - multiple actions

2016-03-18T14:52:24.962Z - info: Test run on android complete

2016-03-18T14:52:24.964Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-18T14:52:24.966Z - info: PLATFORM: android
2016-03-18T14:52:24.967Z - info: RESULT: PASS
2016-03-18T14:52:24.968Z - info: 134 of 134 tests completed
2016-03-18T14:52:24.969Z - info: 134/134 passed (0 failures)
2016-03-18T14:52:24.969Z - info: --- Test Details ---


2016-03-18T14:52:24.970Z - info: 1. calling createNativeListener directly rejects - pass

2016-03-18T14:52:24.971Z - info: 2. emits incomingConnectionState - pass

2016-03-18T14:52:24.972Z - info: 3. emits routerPortConnectionFailed - pass
2016-03-18T14:52:24.972Z - info: 4. native server connections all up - pass

2016-03-18T14:52:24.973Z - info: 5. native server - closing incoming stream cleans outgoing socket - pass

2016-03-18T14:52:24.974Z - info: 6. native server - closing incoming connection cleans outgoing socket - pass

2016-03-18T14:52:24.975Z - info: 7. native server - closing outgoing socket cleans associated mux stream - pass
2016-03-18T14:52:24.976Z - info: 8. native server - closing the whole server cleans everything up - pass

2016-03-18T14:52:24.977Z - info: 9. native server - we can get a ton of connections and data through and still clean up the server completely - pass

2016-03-18T14:52:24.977Z - info: 10. native server - simulate mux failure, make sure everything is cleaned up - pass
2016-03-18T14:52:24.978Z - info: 11. native server - timing out the incoming connection cleans everything up - pass

2016-03-18T14:52:24.979Z - info: 12. closeAll can close even when connections open - pass

2016-03-18T14:52:24.980Z - info: 13. closeAll with promise - pass

2016-03-18T14:52:24.980Z - info: 14. multiplex can send data - pass

2016-03-18T14:52:24.981Z - info: 15. enqueue and run in order - pass

2016-03-18T14:52:24.982Z - info: 16. enqueueAtTop and run backwards - pass

2016-03-18T14:52:24.983Z - info: 17. mix enqueue and enqueueAtTop - pass

2016-03-18T14:52:24.993Z - info: 18. queues handled independently - pass

2016-03-18T14:52:24.994Z - info: 19. basic - pass

2016-03-18T14:52:24.995Z - info: 20. another - pass
2016-03-18T14:52:24.996Z - info: 21. #startListeningForAdvertisements should fail if start not called - pass

2016-03-18T14:52:24.997Z - info: 22. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-18T14:52:24.998Z - info: 23. should be able to call #stopListeningForAdvertisements many times - pass
2016-03-18T14:52:24.999Z - info: 24. should be able to call #startListeningForAdvertisements many times - pass

2016-03-18T14:52:24.999Z - info: 25. should be able to call #startUpdateAdvertisingAndListening many times - pass

2016-03-18T14:52:25.000Z - info: 26. should be able to call #stopAdvertisingAndListening many times - pass

2016-03-18T14:52:25.001Z - info: 27. #start should fail if called twice in a row - pass

2016-03-18T14:52:25.002Z - info: 28. does not emit duplicate discoveryAdvertisingStateUpdate - pass
2016-03-18T14:52:25.003Z - info: 29. does not send duplicate availability changes - pass

2016-03-18T14:52:25.003Z - info: 30. can get the network status - pass

2016-03-18T14:52:25.004Z - info: 31. wifi peer is marked unavailable if announcements stop - pass

2016-03-18T14:52:25.005Z - info: 32. Can call start/stopListeningForAdvertisements - pass
2016-03-18T14:52:25.006Z - info: 33. Calling startListeningForAdvertisements twice is NOT an error - pass

2016-03-18T14:52:25.007Z - info: 34. Can call start/stopUpdateAdvertisingAndListening - pass

2016-03-18T14:52:25.007Z - info: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error - pass

2016-03-18T14:52:25.008Z - info: 36. peerAvailabilityChange is called - pass
2016-03-18T14:52:25.009Z - info: 37. Can connect to a remote peer - pass

2016-03-18T14:52:25.010Z - info: 38. Can shift large amounts of data - pass

2016-03-18T14:52:25.010Z - info: 39. can get the network status before starting - pass

2016-03-18T14:52:25.011Z - info: 40. Test BEACONS_RETRIEVED_AND_PARSED locally - pass
2016-03-18T14:52:25.012Z - info: 41. Test HTTP_BAD_RESPONSE locally - pass

2016-03-18T14:52:25.013Z - info: 42. Test NETWORK_PROBLEM locally - pass

2016-03-18T14:52:25.014Z - info: 43. Test timeout locally - pass

2016-03-18T14:52:25.014Z - info: 44. Call the start two times - pass
2016-03-18T14:52:25.015Z - info: 45. Call the kill before calling the start - pass

2016-03-18T14:52:25.016Z - info: 46. Call the kill immediately after the start - pass

2016-03-18T14:52:25.017Z - info: 47. Call the kill while waiting a response from the server - pass

2016-03-18T14:52:25.018Z - info: 48. Test to exceed the max content size locally - pass
2016-03-18T14:52:25.018Z - info: 49. Close the server socket while the client is waiting a response from the server. Local test. - pass

2016-03-18T14:52:25.019Z - info: 50. Close the client socket while the client is waiting a response from the server. Local test. - pass

2016-03-18T14:52:25.020Z - info: 51. #generatePreambleAndBeacons bad args - pass

2016-03-18T14:52:25.021Z - info: 52. #generatePreambleAndBeacons empty keys to notify - pass
2016-03-18T14:52:25.022Z - info: 53. #generatePreambleAndBeacons multiple keys to notify - pass

2016-03-18T14:52:25.022Z - info: 54. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass

2016-03-18T14:52:25.023Z - info: 55. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass

2016-03-18T14:52:25.024Z - info: 56. #parseBeacons expiration out of range lower - pass
2016-03-18T14:52:25.025Z - info: 57. #parseBeacons expiration out of range lower - pass

2016-03-18T14:52:25.026Z - info: 58. #parseBeacons no beacons returns null - pass

2016-03-18T14:52:25.026Z - info: 59. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass

2016-03-18T14:52:25.027Z - info: 60. #parseBeacons addressBookCallback fails decrypt - pass

2016-03-18T14:52:25.028Z - info: 61. #parseBeacons addressBookCallback returns no matches - pass
2016-03-18T14:52:25.029Z - info: 62. #parseBeacons addressBookCallback returns spurious match - pass

2016-03-18T14:52:25.030Z - info: 63. #parseBeacons addressBookCallback returns public key - pass

2016-03-18T14:52:25.030Z - info: 64. validate generatePskIdentityField - pass
2016-03-18T14:52:25.031Z - info: 65. validate generatePskSecret - pass

2016-03-18T14:52:25.032Z - info: 66. Start and stop ThaliNotificationServer - pass

2016-03-18T14:52:25.033Z - info: 67. Pass an empty array to ThaliNotificationServer.start - pass

2016-03-18T14:52:25.033Z - info: 68. Pass a string to ThaliNotificationServer.start - pass

2016-03-18T14:52:25.034Z - info: 69. Pass an empty parameter to ThaliNotificationServer.start - pass
2016-03-18T14:52:25.035Z - info: 70. Make an HTTP request to /NotificationBeacons - pass

2016-03-18T14:52:25.036Z - info: 71. Make an HTTP request to /NotificationBeacons (no keys) - pass

2016-03-18T14:52:25.037Z - info: 72. Make an HTTP request to /NotificationBeaconsbefore calling start - pass
2016-03-18T14:52:25.038Z - info: 73. #testThaliPeerAction - test getters - pass
2016-03-18T14:52:25.039Z - info: 74. #testThaliPeerAction - start and kill - pass
2016-03-18T14:52:25.039Z - info: 75. #testThaliPeerAction - double start - pass

2016-03-18T14:52:25.040Z - info: 76. #testThaliPeerAction - start after kill - pass
2016-03-18T14:52:25.040Z - info: 77. #testThaliPeerAction - make sure ids are unique - pass

2016-03-18T14:52:25.041Z - info: 78. Test PeerConnectionInformation basics - pass

2016-03-18T14:52:25.042Z - info: 79. Test PeerDictionary basic functionality - pass
2016-03-18T14:52:25.043Z - info: 80. Test PeerDictionary with multiple entries. - pass

2016-03-18T14:52:25.044Z - info: 81. RESOLVED entries are removed before WAITING state entry. - pass

2016-03-18T14:52:25.044Z - info: 82. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass

2016-03-18T14:52:25.045Z - info: 83. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass
2016-03-18T14:52:25.046Z - info: 84. #ThaliPeerPoolInterface - bad enqueues - pass

2016-03-18T14:52:25.047Z - info: 85. #ThaliPeerPoolInterface - do not allow same object type - pass

2016-03-18T14:52:25.048Z - info: 86. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass

2016-03-18T14:52:25.048Z - info: 87. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent - pass
2016-03-18T14:52:25.049Z - info: 88. compareBufferArrays - pass

2016-03-18T14:52:25.050Z - info: 89. Call start twice and get error - pass

2016-03-18T14:52:25.051Z - info: 90. Start and make sure it runs - pass

2016-03-18T14:52:25.052Z - info: 91. Make sure getTimeWhenRun is right after start - pass
2016-03-18T14:52:25.052Z - info: 92. Make sure getTimeWhenRun is -1 after function is called - pass

2016-03-18T14:52:25.053Z - info: 93. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass

2016-03-18T14:52:25.054Z - info: 94. Test TransientState - pass

2016-03-18T14:52:25.055Z - info: 95. No peers and empty database - pass
2016-03-18T14:52:25.055Z - info: 96. One peer and empty DB - pass
2016-03-18T14:52:25.056Z - info: 97. One peer with _Local set behind current seq - pass
2016-03-18T14:52:25.057Z - info: 98. One peer with _Local set equal to current seq - pass
2016-03-18T14:52:25.057Z - info: 99. One peer with _Local set ahead of current seq (and no this should not happen) - pass
2016-03-18T14:52:25.058Z - info: 100. Three peers, one not in DB, one behind and one ahead - pass
2016-03-18T14:52:25.059Z - info: 101. More than maximum peers, make sure we only send maximum allowed - pass
2016-03-18T14:52:25.059Z - info: 102. two peers with empty DB, update the doc - pass
2016-03-18T14:52:25.060Z - info: 103. add doc and make sure tokens refresh when they expire - pass
2016-03-18T14:52:25.060Z - info: 104. start and stop and start and stop - pass
2016-03-18T14:52:25.061Z - info: 105. two identical starts in a row - pass
2016-03-18T14:52:25.061Z - info: 106. two different starts in a row - pass
2016-03-18T14:52:25.065Z - info: 107. two stops and a start and two stops - pass
2016-03-18T14:52:25.066Z - info: 108. we properly enqueue requests so no then needed - pass
2016-03-18T14:52:25.066Z - info: 109. test calculateSeqPointKeyId - pass
2016-03-18T14:52:25.067Z - info: 110. can create servers manager - pass
2016-03-18T14:52:25.067Z - info: 111. calling stop without start causes error - pass
2016-03-18T14:52:25.068Z - info: 112. can start/stop servers manager - pass
2016-03-18T14:52:25.068Z - info: 113. starting twice resolves with listening port - pass

2016-03-18T14:52:25.069Z - info: 114. terminateIncomingConnection will terminate a connection - pass
2016-03-18T14:52:25.070Z - info: 115. terminate an Outgoing connection will terminate the server - pass

2016-03-18T14:52:25.071Z - info: 116. terminate an Outgoing connection with wrong arguments is not harmful - pass
2016-03-18T14:52:25.072Z - info: 117. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass

2016-03-18T14:52:25.073Z - info: 118. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-03-18T14:52:25.073Z - info: 119. messages with invalid location or USN should be ignored - pass

2016-03-18T14:52:25.074Z - info: 120. verify that Thali-specific messages are filtered correctly - pass
2016-03-18T14:52:25.075Z - info: 121. #startListeningForAdvertisements should fail if start not called - pass

2016-03-18T14:52:25.076Z - info: 122. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-18T14:52:25.076Z - info: 123. #start should fail if called twice in a row - pass
2016-03-18T14:52:25.077Z - info: 124. should not be started after stop is called - pass

2016-03-18T14:52:25.078Z - info: 125. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass

2016-03-18T14:52:25.079Z - info: 126. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass

2016-03-18T14:52:25.080Z - info: 127. #startUpdateAdvertisingAndListening should start hosting given router object - pass

2016-03-18T14:52:25.081Z - info: 128. #stop can be called multiple times in a row - pass
2016-03-18T14:52:25.081Z - info: 129. #startListeningForAdvertisements can be called multiple times in a row - pass

2016-03-18T14:52:25.082Z - info: 130. #stopListeningForAdvertisements can be called multiple times in a row - pass

2016-03-18T14:52:25.083Z - info: 131. #stopAdvertisingAndListening can be called multiple times in a row - pass

2016-03-18T14:52:25.084Z - info: 132. functions are run from a queue in the right order - pass

2016-03-18T14:52:25.085Z - info: 133. #ThaliPeerPoolDefault - single action - pass
2016-03-18T14:52:25.085Z - info: 134. #ThaliPeerPoolDefault - multiple actions - pass

2016-03-18T14:52:25.086Z - info: 

-== END ==-

2016-03-18T14:52:25.969Z - debug: Socket disconnected: transport close 2 (LGE-LG-H815)

2016-03-18T15:09:10.772Z - debug: Socket disconnected: transport close 0 (Apple-Iphone5-1)

2016-03-18T15:09:10.779Z - debug: Socket disconnected: transport close 3 (Apple-Iphone5s-1)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m
2016-03-18T14:51:15.119Z - error: test server: Device Apple-Iphone5s-1


```


Logs for system : 
```

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m



ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
true

```
###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  f56ad48d Test has  SUCCEEDED
Device test finished on f56ad48d 
Android task is completed. [SUCCESS]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/63377149f0d5e10_Fix_for_service_data_issue_seen_on_some_devices_tompaana/thali01_samsung-SM-A500FU.md)

####Node name: thali03
Console output:
```
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:0 
child process exited with code 0 on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/63377149f0d5e10_Fix_for_service_data_issue_seen_on_some_devices_tompaana/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on ZX1C223JKW 
Android task is completed. [SUCCESS]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/63377149f0d5e10_Fix_for_service_data_issue_seen_on_some_devices_tompaana/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Android task is completed. [SUCCESS]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/63377149f0d5e10_Fix_for_service_data_issue_seen_on_some_devices_tompaana/thali05_LGE-LG-H815.md)

####Node name: thali06
Console output:
```
STOP log received from  FA55PYS00566 Test has  SUCCEEDED
Device test finished on FA55PYS00566 
Android task is completed. [SUCCESS]
```
[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/63377149f0d5e10_Fix_for_service_data_issue_seen_on_some_devices_tompaana/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
STOP log received from  4db5c8cc Test has  SUCCEEDED
Device test finished on 4db5c8cc 
Android task is completed. [SUCCESS]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/63377149f0d5e10_Fix_for_service_data_issue_seen_on_some_devices_tompaana/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
STOP log received from  4325e43f Test has  SUCCEEDED
Device test finished on 4325e43f 
Android task is completed. [SUCCESS]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/63377149f0d5e10_Fix_for_service_data_issue_seen_on_some_devices_tompaana/thali08_samsung-SM-A300FU.md)


###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/63377149f0d5e10_Fix_for_service_data_issue_seen_on_some_devices_tompaana/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/63377149f0d5e10_Fix_for_service_data_issue_seen_on_some_devices_tompaana/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/63377149f0d5e10_Fix_for_service_data_issue_seen_on_some_devices_tompaana/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/63377149f0d5e10_Fix_for_service_data_issue_seen_on_some_devices_tompaana/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/63377149f0d5e10_Fix_for_service_data_issue_seen_on_some_devices_tompaana/iOS_server.md)





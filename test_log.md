#### Test 6275440391a6bae Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":8}}
2016-03-15T19:38:07.134Z - info: listening on *:3000

2016-03-15T19:38:09.597Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:0

2016-03-15T19:38:10.176Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:1

2016-03-15T19:38:10.641Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:2

2016-03-15T19:38:10.643Z - info: Required number of ios devices presented (2)

2016-03-15T19:38:10.647Z - info: Starting unit test run for platform: ios

2016-03-15T19:38:10.768Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:3

2016-03-15T19:38:10.769Z - info: Discarding surplus device: Apple-Iphone5-1

2016-03-15T19:38:11.262Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-15T19:38:11.921Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-15T19:38:12.301Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-15T19:38:12.656Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:4

2016-03-15T19:38:12.660Z - info: Discarding surplus device: Apple-Iphone6-1

2016-03-15T19:38:12.897Z - info: Running on ios test: 4. native server connections all up

2016-03-15T19:38:13.530Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-15T19:38:13.956Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-15T19:38:13.995Z - debug: Socket disconnected: transport close 3 (Apple-Iphone5-1)

2016-03-15T19:38:14.317Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-15T19:38:14.877Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-15T19:38:15.304Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-15T19:38:15.348Z - debug: Socket disconnected: transport close 4 (Apple-Iphone6-1)

2016-03-15T19:38:16.379Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-15T19:38:17.159Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-15T19:38:17.587Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-15T19:38:18.029Z - info: Running on ios test: 13. closeAll with promise

2016-03-15T19:38:18.380Z - info: Running on ios test: 14. multiplex can send data

2016-03-15T19:38:18.744Z - info: Running on ios test: 15. enqueue and run in order

2016-03-15T19:38:19.326Z - info: Running on ios test: 16. enqueueAtTop and run backwards

2016-03-15T19:38:19.722Z - info: Running on ios test: 17. mix enqueue and enqueueAtTop

2016-03-15T19:38:20.362Z - info: Running on ios test: 18. queues handled independently

2016-03-15T19:38:20.767Z - info: Running on ios test: 19. basic

2016-03-15T19:38:21.065Z - info: Running on ios test: 20. another

2016-03-15T19:38:21.544Z - info: Running on ios test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-15T19:38:21.985Z - info: Running on ios test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-15T19:38:22.268Z - info: Running on ios test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-15T19:38:22.684Z - info: Running on ios test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-15T19:38:23.095Z - info: Running on ios test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-15T19:38:23.441Z - info: Running on ios test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-15T19:38:23.759Z - info: Running on ios test: 27. #start should fail if called twice in a row

2016-03-15T19:38:24.123Z - info: Running on ios test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-15T19:38:24.553Z - info: Running on ios test: 29. does not send duplicate availability changes

2016-03-15T19:38:24.932Z - info: Running on ios test: 30. can get the network status

2016-03-15T19:38:25.299Z - info: Running on ios test: 31. wifi peer is marked unavailable if announcements stop

2016-03-15T19:38:26.629Z - info: Running on ios test: 32. can get the network status before starting

2016-03-15T19:38:26.996Z - info: Running on ios test: 33. Test BEACONS_RETRIEVED_AND_PARSED locally

2016-03-15T19:38:27.491Z - info: Running on ios test: 34. Test HTTP_BAD_RESPONSE locally

2016-03-15T19:38:27.905Z - info: Running on ios test: 35. Test NETWORK_PROBLEM locally

2016-03-15T19:38:29.029Z - info: Running on ios test: 36. Test timeout locally

2016-03-15T19:38:30.617Z - info: Running on ios test: 37. Call the start two times

2016-03-15T19:38:31.001Z - info: Running on ios test: 38. Call the kill before calling the start

2016-03-15T19:38:31.344Z - info: Running on ios test: 39. Call the kill immediately after the start

2016-03-15T19:38:31.685Z - info: Running on ios test: 40. Call the kill while waiting a response from the server

2016-03-15T19:38:34.052Z - info: Running on ios test: 41. Test to exceed the max content size locally

2016-03-15T19:38:34.542Z - info: Running on ios test: 42. Close the server socket while the client is waiting a responsefrom the server. Local test.

2016-03-15T19:38:37.076Z - info: Running on ios test: 43. #generatePreambleAndBeacons bad args

2016-03-15T19:38:37.400Z - info: Running on ios test: 44. #generatePreambleAndBeacons empty keys to notify

2016-03-15T19:38:37.767Z - info: Running on ios test: 45. #generatePreambleAndBeacons multiple keys to notify

2016-03-15T19:38:38.351Z - info: Running on ios test: 46. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-15T19:38:38.708Z - info: Running on ios test: 47. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-15T19:38:39.124Z - info: Running on ios test: 48. #parseBeacons expiration out of range lower

2016-03-15T19:38:39.564Z - info: Running on ios test: 49. #parseBeacons expiration out of range lower

2016-03-15T19:38:40.033Z - info: Running on ios test: 50. #parseBeacons no beacons returns null

2016-03-15T19:38:40.345Z - info: Running on ios test: 51. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-15T19:38:40.693Z - info: Running on ios test: 52. #parseBeacons addressBookCallback fails decrypt

2016-03-15T19:38:41.092Z - info: Running on ios test: 53. #parseBeacons addressBookCallback returns no matches

2016-03-15T19:38:41.462Z - info: Running on ios test: 54. #parseBeacons addressBookCallback returns spurious match

2016-03-15T19:38:41.853Z - info: Running on ios test: 55. #parseBeacons addressBookCallback returns public key

2016-03-15T19:38:42.248Z - info: Running on ios test: 56. validate generatePskIdentityField

2016-03-15T19:38:42.565Z - info: Running on ios test: 57. validate generatePskSecret

2016-03-15T19:38:42.905Z - info: Running on ios test: 58. Start and stop ThaliNotificationServer

2016-03-15T19:38:43.250Z - info: Running on ios test: 59. Pass an empty array to ThaliNotificationServer.start

2016-03-15T19:38:43.774Z - info: Running on ios test: 60. Pass a string to ThaliNotificationServer.start

2016-03-15T19:38:44.091Z - info: Running on ios test: 61. Pass an empty parameter to ThaliNotificationServer.start

2016-03-15T19:38:44.463Z - info: Running on ios test: 62. Make an HTTP request to /NotificationBeacons

2016-03-15T19:38:44.906Z - info: Running on ios test: 63. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-15T19:38:45.261Z - info: Running on ios test: 64. Make an HTTP request to /NotificationBeaconsbefore calling start

2016-03-15T19:38:45.623Z - info: Running on ios test: 65. #testThaliPeerAction - test getters

2016-03-15T19:38:45.908Z - info: Running on ios test: 66. #testThaliPeerAction - start and kill

2016-03-15T19:38:46.264Z - info: Running on ios test: 67. #testThaliPeerAction - double start

2016-03-15T19:38:46.662Z - info: Running on ios test: 68. #testThaliPeerAction - start after kill

2016-03-15T19:38:47.111Z - info: Running on ios test: 69. #testThaliPeerAction - make sure ids are unique

2016-03-15T19:38:47.535Z - info: Running on ios test: 70. Test PeerConnectionInformation basics

2016-03-15T19:38:47.827Z - info: Running on ios test: 71. Test PeerDictionary basic functionality

2016-03-15T19:38:48.136Z - info: Running on ios test: 72. Test PeerDictionary with multiple entries.

2016-03-15T19:38:49.583Z - info: Running on ios test: 73. RESOLVED entries are removed before WAITING state entry.

2016-03-15T19:38:50.524Z - info: Running on ios test: 74. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-15T19:38:51.398Z - info: Running on ios test: 75. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-15T19:38:52.300Z - info: Running on ios test: 76. #ThaliPeerPoolInterface - bad enqueues

2016-03-15T19:38:52.597Z - info: Running on ios test: 77. #ThaliPeerPoolInterface - do not allow same object type

2016-03-15T19:38:53.003Z - info: Running on ios test: 78. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-15T19:38:53.287Z - info: Running on ios test: 79. compareBufferArrays

2016-03-15T19:38:53.595Z - info: Running on ios test: 80. Call start twice and get error

2016-03-15T19:38:53.885Z - info: Running on ios test: 81. Start and make sure it runs

2016-03-15T19:38:54.302Z - info: Running on ios test: 82. Make sure getTimeWhenRun is right after start

2016-03-15T19:38:54.636Z - info: Running on ios test: 83. Make sure getTimeWhenRun is -1 after function is called

2016-03-15T19:38:54.974Z - info: Running on ios test: 84. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-15T19:38:55.377Z - info: Running on ios test: 85. Test TransientState

2016-03-15T19:38:55.726Z - info: Running on ios test: 86. No peers and empty database

2016-03-15T19:38:56.222Z - info: Running on ios test: 87. One peer and empty DB

2016-03-15T19:38:56.715Z - info: Running on ios test: 88. One peer with _Local set behind current seq

2016-03-15T19:38:57.263Z - info: Running on ios test: 89. One peer with _Local set equal to current seq

2016-03-15T19:38:58.025Z - info: Running on ios test: 90. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-15T19:39:00.908Z - info: Running on ios test: 91. Three peers, one not in DB, one behind and one ahead

2016-03-15T19:39:01.577Z - info: Running on ios test: 92. More than maximum peers, make sure we only send maximum allowed

2016-03-15T19:39:02.618Z - info: Running on ios test: 93. two peers with empty DB, update the doc

2016-03-15T19:39:03.284Z - info: Running on ios test: 94. add doc and make sure tokens refresh when they expire

2016-03-15T19:39:04.404Z - info: Running on ios test: 95. start and stop and start and stop

2016-03-15T19:39:05.013Z - info: Running on ios test: 96. two identical starts in a row

2016-03-15T19:39:05.600Z - info: Running on ios test: 97. two different starts in a row

2016-03-15T19:39:06.202Z - info: Running on ios test: 98. two stops and a start and two stops

2016-03-15T19:39:06.839Z - info: Running on ios test: 99. we properly enqueue requests so no then needed

2016-03-15T19:39:07.320Z - info: Running on ios test: 100. test calculateSeqPointKeyId

2016-03-15T19:39:07.690Z - info: Running on ios test: 101. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-15T19:39:08.005Z - info: Running on ios test: 102. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-15T19:39:08.471Z - info: Running on ios test: 103. messages with invalid location or USN should be ignored

2016-03-15T19:39:08.862Z - info: Running on ios test: 104. verify that Thali-specific messages are filtered correctly

2016-03-15T19:39:09.228Z - info: Running on ios test: 105. #startListeningForAdvertisements should fail if start not called

2016-03-15T19:39:09.609Z - info: Running on ios test: 106. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-15T19:39:09.964Z - info: Running on ios test: 107. #start should fail if called twice in a row

2016-03-15T19:39:10.373Z - info: Running on ios test: 108. should not be started after stop is called

2016-03-15T19:39:10.818Z - info: Running on ios test: 109. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-15T19:39:11.346Z - info: Running on ios test: 110. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-15T19:39:11.824Z - info: Running on ios test: 111. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-15T19:39:12.234Z - info: Running on ios test: 112. #stop can be called multiple times in a row

2016-03-15T19:39:12.539Z - info: Running on ios test: 113. #startListeningForAdvertisements can be called multiple times in a row

2016-03-15T19:39:17.292Z - info: Running on ios test: 114. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-15T19:39:17.719Z - info: Running on ios test: 115. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-15T19:39:18.056Z - info: Running on ios test: 116. functions are run from a queue in the right order

2016-03-15T19:39:18.363Z - info: Running on ios test: 117. #ThaliPeerPoolDefault - single action

2016-03-15T19:39:18.775Z - info: Running on ios test: 118. #ThaliPeerPoolDefault - multiple actions

2016-03-15T19:39:19.202Z - info: Test run on ios complete

2016-03-15T19:39:19.206Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-15T19:39:19.211Z - info: PLATFORM: ios
2016-03-15T19:39:19.211Z - info: RESULT: PASS
2016-03-15T19:39:19.212Z - info: 118 of 118 tests completed
2016-03-15T19:39:19.213Z - info: 118/118 passed (0 failures)
2016-03-15T19:39:19.213Z - info: --- Test Details ---


2016-03-15T19:39:19.214Z - info: 1. calling createNativeListener directly rejects - pass
2016-03-15T19:39:19.215Z - info: 2. emits incomingConnectionState - pass
2016-03-15T19:39:19.215Z - info: 3. emits routerPortConnectionFailed - pass
2016-03-15T19:39:19.216Z - info: 4. native server connections all up - pass
2016-03-15T19:39:19.217Z - info: 5. native server - closing incoming stream cleans outgoing socket - pass
2016-03-15T19:39:19.218Z - info: 6. native server - closing incoming connection cleans outgoing socket - pass

2016-03-15T19:39:19.218Z - info: 7. native server - closing outgoing socket cleans associated mux stream - pass

2016-03-15T19:39:19.219Z - info: 8. native server - closing the whole server cleans everything up - pass

2016-03-15T19:39:19.220Z - info: 9. native server - we can get a ton of connections and data through and still clean up the server completely - pass

2016-03-15T19:39:19.221Z - info: 10. native server - simulate mux failure, make sure everything is cleaned up - pass

2016-03-15T19:39:19.222Z - info: 11. native server - timing out the incoming connection cleans everything up - pass

2016-03-15T19:39:19.223Z - info: 12. closeAll can close even when connections open - pass

2016-03-15T19:39:19.224Z - info: 13. closeAll with promise - pass

2016-03-15T19:39:19.225Z - info: 14. multiplex can send data - pass

2016-03-15T19:39:19.226Z - info: 15. enqueue and run in order - pass

2016-03-15T19:39:19.227Z - info: 16. enqueueAtTop and run backwards - pass

2016-03-15T19:39:19.227Z - info: 17. mix enqueue and enqueueAtTop - pass

2016-03-15T19:39:19.228Z - info: 18. queues handled independently - pass

2016-03-15T19:39:19.229Z - info: 19. basic - pass

2016-03-15T19:39:19.230Z - info: 20. another - pass

2016-03-15T19:39:19.231Z - info: 21. #startListeningForAdvertisements should fail if start not called - pass

2016-03-15T19:39:19.232Z - info: 22. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-15T19:39:19.233Z - info: 23. should be able to call #stopListeningForAdvertisements many times - pass

2016-03-15T19:39:19.234Z - info: 24. should be able to call #startListeningForAdvertisements many times - pass
2016-03-15T19:39:19.235Z - info: 25. should be able to call #startUpdateAdvertisingAndListening many times - pass
2016-03-15T19:39:19.235Z - info: 26. should be able to call #stopAdvertisingAndListening many times - pass
2016-03-15T19:39:19.236Z - info: 27. #start should fail if called twice in a row - pass
2016-03-15T19:39:19.237Z - info: 28. does not emit duplicate discoveryAdvertisingStateUpdate - pass
2016-03-15T19:39:19.237Z - info: 29. does not send duplicate availability changes - pass
2016-03-15T19:39:19.238Z - info: 30. can get the network status - pass
2016-03-15T19:39:19.239Z - info: 31. wifi peer is marked unavailable if announcements stop - pass
2016-03-15T19:39:19.240Z - info: 32. can get the network status before starting - pass
2016-03-15T19:39:19.241Z - info: 33. Test BEACONS_RETRIEVED_AND_PARSED locally - pass
2016-03-15T19:39:19.241Z - info: 34. Test HTTP_BAD_RESPONSE locally - pass
2016-03-15T19:39:19.242Z - info: 35. Test NETWORK_PROBLEM locally - pass
2016-03-15T19:39:19.242Z - info: 36. Test timeout locally - pass
2016-03-15T19:39:19.243Z - info: 37. Call the start two times - pass
2016-03-15T19:39:19.243Z - info: 38. Call the kill before calling the start - pass

2016-03-15T19:39:19.244Z - info: 39. Call the kill immediately after the start - pass

2016-03-15T19:39:19.245Z - info: 40. Call the kill while waiting a response from the server - pass

2016-03-15T19:39:19.245Z - info: 41. Test to exceed the max content size locally - pass

2016-03-15T19:39:19.247Z - info: 42. Close the server socket while the client is waiting a responsefrom the server. Local test. - pass

2016-03-15T19:39:19.247Z - info: 43. #generatePreambleAndBeacons bad args - pass

2016-03-15T19:39:19.249Z - info: 44. #generatePreambleAndBeacons empty keys to notify - pass

2016-03-15T19:39:19.250Z - info: 45. #generatePreambleAndBeacons multiple keys to notify - pass

2016-03-15T19:39:19.250Z - info: 46. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass

2016-03-15T19:39:19.251Z - info: 47. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass

2016-03-15T19:39:19.252Z - info: 48. #parseBeacons expiration out of range lower - pass

2016-03-15T19:39:19.253Z - info: 49. #parseBeacons expiration out of range lower - pass

2016-03-15T19:39:19.254Z - info: 50. #parseBeacons no beacons returns null - pass

2016-03-15T19:39:19.255Z - info: 51. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass

2016-03-15T19:39:19.256Z - info: 52. #parseBeacons addressBookCallback fails decrypt - pass

2016-03-15T19:39:19.257Z - info: 53. #parseBeacons addressBookCallback returns no matches - pass

2016-03-15T19:39:19.258Z - info: 54. #parseBeacons addressBookCallback returns spurious match - pass

2016-03-15T19:39:19.259Z - info: 55. #parseBeacons addressBookCallback returns public key - pass

2016-03-15T19:39:19.259Z - info: 56. validate generatePskIdentityField - pass

2016-03-15T19:39:19.260Z - info: 57. validate generatePskSecret - pass

2016-03-15T19:39:19.261Z - info: 58. Start and stop ThaliNotificationServer - pass

2016-03-15T19:39:19.262Z - info: 59. Pass an empty array to ThaliNotificationServer.start - pass

2016-03-15T19:39:19.263Z - info: 60. Pass a string to ThaliNotificationServer.start - pass

2016-03-15T19:39:19.264Z - info: 61. Pass an empty parameter to ThaliNotificationServer.start - pass

2016-03-15T19:39:19.265Z - info: 62. Make an HTTP request to /NotificationBeacons - pass

2016-03-15T19:39:19.265Z - info: 63. Make an HTTP request to /NotificationBeacons (no keys) - pass

2016-03-15T19:39:19.266Z - info: 64. Make an HTTP request to /NotificationBeaconsbefore calling start - pass

2016-03-15T19:39:19.267Z - info: 65. #testThaliPeerAction - test getters - pass

2016-03-15T19:39:19.270Z - info: 66. #testThaliPeerAction - start and kill - pass

2016-03-15T19:39:19.270Z - info: 67. #testThaliPeerAction - double start - pass

2016-03-15T19:39:19.271Z - info: 68. #testThaliPeerAction - start after kill - pass

2016-03-15T19:39:19.272Z - info: 69. #testThaliPeerAction - make sure ids are unique - pass
2016-03-15T19:39:19.273Z - info: 70. Test PeerConnectionInformation basics - pass
2016-03-15T19:39:19.274Z - info: 71. Test PeerDictionary basic functionality - pass
2016-03-15T19:39:19.274Z - info: 72. Test PeerDictionary with multiple entries. - pass
2016-03-15T19:39:19.275Z - info: 73. RESOLVED entries are removed before WAITING state entry. - pass
2016-03-15T19:39:19.275Z - info: 74. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass
2016-03-15T19:39:19.276Z - info: 75. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass
2016-03-15T19:39:19.276Z - info: 76. #ThaliPeerPoolInterface - bad enqueues - pass
2016-03-15T19:39:19.277Z - info: 77. #ThaliPeerPoolInterface - do not allow same object type - pass
2016-03-15T19:39:19.277Z - info: 78. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass
2016-03-15T19:39:19.278Z - info: 79. compareBufferArrays - pass
2016-03-15T19:39:19.279Z - info: 80. Call start twice and get error - pass
2016-03-15T19:39:19.279Z - info: 81. Start and make sure it runs - pass
2016-03-15T19:39:19.280Z - info: 82. Make sure getTimeWhenRun is right after start - pass
2016-03-15T19:39:19.280Z - info: 83. Make sure getTimeWhenRun is -1 after function is called - pass
2016-03-15T19:39:19.281Z - info: 84. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass
2016-03-15T19:39:19.281Z - info: 85. Test TransientState - pass
2016-03-15T19:39:19.282Z - info: 86. No peers and empty database - pass
2016-03-15T19:39:19.282Z - info: 87. One peer and empty DB - pass
2016-03-15T19:39:19.283Z - info: 88. One peer with _Local set behind current seq - pass
2016-03-15T19:39:19.283Z - info: 89. One peer with _Local set equal to current seq - pass
2016-03-15T19:39:19.284Z - info: 90. One peer with _Local set ahead of current seq (and no this should not happen) - pass
2016-03-15T19:39:19.284Z - info: 91. Three peers, one not in DB, one behind and one ahead - pass
2016-03-15T19:39:19.285Z - info: 92. More than maximum peers, make sure we only send maximum allowed - pass
2016-03-15T19:39:19.285Z - info: 93. two peers with empty DB, update the doc - pass
2016-03-15T19:39:19.286Z - info: 94. add doc and make sure tokens refresh when they expire - pass
2016-03-15T19:39:19.286Z - info: 95. start and stop and start and stop - pass
2016-03-15T19:39:19.287Z - info: 96. two identical starts in a row - pass
2016-03-15T19:39:19.288Z - info: 97. two different starts in a row - pass

2016-03-15T19:39:19.288Z - info: 98. two stops and a start and two stops - pass
2016-03-15T19:39:19.289Z - info: 99. we properly enqueue requests so no then needed - pass

2016-03-15T19:39:19.289Z - info: 100. test calculateSeqPointKeyId - pass

2016-03-15T19:39:19.291Z - info: 101. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass

2016-03-15T19:39:19.291Z - info: 102. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-03-15T19:39:19.292Z - info: 103. messages with invalid location or USN should be ignored - pass
2016-03-15T19:39:19.293Z - info: 104. verify that Thali-specific messages are filtered correctly - pass
2016-03-15T19:39:19.294Z - info: 105. #startListeningForAdvertisements should fail if start not called - pass
2016-03-15T19:39:19.294Z - info: 106. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-15T19:39:19.295Z - info: 107. #start should fail if called twice in a row - pass
2016-03-15T19:39:19.295Z - info: 108. should not be started after stop is called - pass
2016-03-15T19:39:19.296Z - info: 109. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass
2016-03-15T19:39:19.297Z - info: 110. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass

2016-03-15T19:39:19.297Z - info: 111. #startUpdateAdvertisingAndListening should start hosting given router object - pass

2016-03-15T19:39:19.298Z - info: 112. #stop can be called multiple times in a row - pass

2016-03-15T19:39:19.299Z - info: 113. #startListeningForAdvertisements can be called multiple times in a row - pass

2016-03-15T19:39:19.300Z - info: 114. #stopListeningForAdvertisements can be called multiple times in a row - pass

2016-03-15T19:39:19.301Z - info: 115. #stopAdvertisingAndListening can be called multiple times in a row - pass

2016-03-15T19:39:19.302Z - info: 116. functions are run from a queue in the right order - pass

2016-03-15T19:39:19.303Z - info: 117. #ThaliPeerPoolDefault - single action - pass

2016-03-15T19:39:19.304Z - info: 118. #ThaliPeerPoolDefault - multiple actions - pass

2016-03-15T19:39:19.305Z - info: 

-== END ==-

2016-03-15T19:39:21.898Z - debug: Socket disconnected: transport close 0 (Apple-Iphone5s-1)

2016-03-15T19:39:22.005Z - debug: Socket disconnected: transport close 2 (Apple-IpadAir2-1)

2016-03-15T19:58:16.013Z - debug: Socket disconnected: transport close 1 (LGE-LG-H815)


 
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
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/6275440391a6bae_416__Implementation_of_ThalinotificationAction_juhanak/thali01_samsung-SM-A500FU.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/6275440391a6bae_416__Implementation_of_ThalinotificationAction_juhanak/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/6275440391a6bae_416__Implementation_of_ThalinotificationAction_juhanak/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:0 
child process exited with code 0 on device LGH8153b36be34 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/6275440391a6bae_416__Implementation_of_ThalinotificationAction_juhanak/thali05_LGE-LG-H815.md)

####Node name: thali06
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:null 
child process exited with code null on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:0 
child process exited with code 0 on device FA55PYS00566 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/6275440391a6bae_416__Implementation_of_ThalinotificationAction_juhanak/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/6275440391a6bae_416__Implementation_of_ThalinotificationAction_juhanak/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:0 
child process exited with code 0 on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/6275440391a6bae_416__Implementation_of_ThalinotificationAction_juhanak/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:0 
child process exited with code 0 on device 4325e43f 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/6275440391a6bae_416__Implementation_of_ThalinotificationAction_juhanak/thali08_samsung-SM-A300FU.md)




###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/6275440391a6bae_416__Implementation_of_ThalinotificationAction_juhanak/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/6275440391a6bae_416__Implementation_of_ThalinotificationAction_juhanak/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/6275440391a6bae_416__Implementation_of_ThalinotificationAction_juhanak/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/6275440391a6bae_416__Implementation_of_ThalinotificationAction_juhanak/iOS_Iphone5s-1.md)



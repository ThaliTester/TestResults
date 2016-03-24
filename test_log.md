#### Test 63968542e6bfc69 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-03-24T20:16:11.586Z - info: listening on *:3000

2016-03-24T20:16:11.992Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:0

2016-03-24T20:16:14.078Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:1

2016-03-24T20:16:15.748Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:2

2016-03-24T20:16:17.011Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:3

2016-03-24T20:16:17.013Z - info: Required number of ios devices presented (3)

2016-03-24T20:16:17.017Z - info: Starting unit test run for platform: ios

2016-03-24T20:16:17.678Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-24T20:16:18.103Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-24T20:16:18.560Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-24T20:16:19.044Z - info: Running on ios test: 4. native server connections all up

2016-03-24T20:16:19.477Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-24T20:16:19.917Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-24T20:16:20.287Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-24T20:16:20.768Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-24T20:16:21.159Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-24T20:16:21.646Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:4

2016-03-24T20:16:23.510Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-24T20:16:23.977Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-24T20:16:24.420Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-24T20:16:24.773Z - info: Running on ios test: 13. closeAll with promise

2016-03-24T20:16:25.127Z - info: Running on ios test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-03-24T20:16:25.505Z - info: Running on ios test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-03-24T20:16:25.882Z - info: Running on ios test: 16. multiplex can send data

2016-03-24T20:16:26.347Z - info: Running on ios test: 17. enqueue and run in order

2016-03-24T20:16:27.065Z - info: Running on ios test: 18. enqueueAtTop and run backwards

2016-03-24T20:16:27.610Z - info: Running on ios test: 19. mix enqueue and enqueueAtTop

2016-03-24T20:16:28.231Z - info: Running on ios test: 20. queues handled independently

2016-03-24T20:16:28.855Z - info: Running on ios test: 21. basic

2016-03-24T20:16:29.445Z - info: Running on ios test: 22. another

2016-03-24T20:16:30.006Z - info: Running on ios test: 23. can pass data in setup

2016-03-24T20:16:30.478Z - info: Running on ios test: 24. #startListeningForAdvertisements should fail if start not called

2016-03-24T20:16:31.000Z - info: Running on ios test: 25. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-24T20:16:32.149Z - info: Running on ios test: 26. should be able to call #stopListeningForAdvertisements many times

2016-03-24T20:16:32.686Z - info: Running on ios test: 27. should be able to call #startListeningForAdvertisements many times

2016-03-24T20:16:34.009Z - info: Running on ios test: 28. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-24T20:16:40.403Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:5

2016-03-24T20:16:40.407Z - info: Required number of android devices presented (3)

2016-03-24T20:16:40.410Z - info: Starting unit test run for platform: android

2016-03-24T20:16:41.346Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-24T20:16:46.072Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-24T20:16:49.385Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-24T20:16:55.866Z - info: Running on android test: 4. native server connections all up

2016-03-24T20:17:03.179Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-24T20:17:13.536Z - info: Running on ios test: 29. should be able to call #stopAdvertisingAndListening many times

2016-03-24T20:17:15.997Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-24T20:17:16.652Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-24T20:17:17.242Z - info: Running on ios test: 30. #start should fail if called twice in a row

2016-03-24T20:17:17.751Z - info: Running on ios test: 31. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-24T20:17:22.307Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-24T20:17:22.899Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-24T20:17:28.463Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-24T20:17:28.983Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-24T20:17:29.493Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-24T20:17:29.916Z - info: Running on android test: 13. closeAll with promise

2016-03-24T20:17:30.335Z - info: Running on android test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-03-24T20:17:30.677Z - info: Running on android test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-03-24T20:17:31.083Z - info: Running on android test: 16. multiplex can send data

2016-03-24T20:17:31.491Z - info: Running on android test: 17. enqueue and run in order

2016-03-24T20:17:32.327Z - info: Running on android test: 18. enqueueAtTop and run backwards

2016-03-24T20:17:33.128Z - info: Running on android test: 19. mix enqueue and enqueueAtTop

2016-03-24T20:17:33.624Z - info: Running on android test: 20. queues handled independently

2016-03-24T20:17:34.082Z - info: Running on android test: 21. basic

2016-03-24T20:17:34.542Z - info: Running on android test: 22. another

2016-03-24T20:17:35.024Z - info: Running on android test: 23. can pass data in setup

2016-03-24T20:17:36.633Z - info: Running on android test: 24. #startListeningForAdvertisements should fail if start not called

2016-03-24T20:17:37.237Z - info: Running on android test: 25. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-24T20:17:37.576Z - info: Running on android test: 26. should be able to call #stopListeningForAdvertisements many times

2016-03-24T20:17:38.198Z - info: Running on android test: 27. should be able to call #startListeningForAdvertisements many times

2016-03-24T20:17:38.994Z - info: Running on android test: 28. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-24T20:17:41.546Z - info: Running on android test: 29. should be able to call #stopAdvertisingAndListening many times

2016-03-24T20:17:44.024Z - info: Running on android test: 30. #start should fail if called twice in a row

2016-03-24T20:17:45.855Z - info: Running on android test: 31. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-24T20:17:48.143Z - info: Running on android test: 32. does not send duplicate availability changes

2016-03-24T20:17:48.717Z - info: Running on android test: 33. can get the network status

2016-03-24T20:17:49.105Z - info: Running on android test: 34. wifi peer is marked unavailable if announcements stop

2016-03-24T20:17:51.655Z - info: Running on android test: 35. Can call start/stopListeningForAdvertisements

2016-03-24T20:17:52.447Z - info: Running on android test: 36. Calling startListeningForAdvertisements twice is NOT an error

2016-03-24T20:17:53.559Z - info: Running on android test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-03-24T20:17:55.174Z - info: Running on android test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-24T20:17:56.385Z - info: Running on android test: 39. peerAvailabilityChange is called

2016-03-24T20:17:58.598Z - info: Running on android test: 40. Can connect to a remote peer

2016-03-24T20:18:07.297Z - info: Running on android test: 41. Can shift large amounts of data

2016-03-24T20:18:16.320Z - info: Running on android test: 42. #startListeningForAdvertisements should fail if start not called

2016-03-24T20:18:19.453Z - info: Running on android test: 43. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-24T20:18:20.447Z - info: Running on android test: 44. should be able to call #stopListeningForAdvertisements many times

2016-03-24T20:18:22.542Z - info: Running on android test: 45. should be able to call #startListeningForAdvertisements many times

2016-03-24T20:18:23.544Z - info: Running on android test: 46. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-24T20:18:24.593Z - info: Running on android test: 47. should be able to call #stopAdvertisingAndListening many times

2016-03-24T20:18:25.111Z - info: Running on android test: 48. can get the network status before starting

2016-03-24T20:18:25.520Z - info: Running on android test: 49. error returned with bad router

2016-03-24T20:18:26.206Z - info: Running on android test: 50. all services are stopped when we call stop

2016-03-24T20:18:27.196Z - info: Running on android test: 51. make sure terminateConnection is properly hooked up

2016-03-24T20:18:28.963Z - info: Running on android test: 52. make sure terminateListener is properly hooked up

2016-03-24T20:18:29.581Z - info: Running on android test: 53. make sure we actually call kill connections properly

2016-03-24T20:18:30.020Z - info: Running on android test: 54. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received

2016-03-24T20:18:30.467Z - info: Running on android test: 55. We repeat failedConnection event when we get it from thaliTcpServersManager

2016-03-24T20:18:30.914Z - info: Running on android test: 56. we successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-24T20:18:31.985Z - warn: Failed on android test: 56. we successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-24T20:18:31.986Z - info: Running on android test: 57. can do HTTP requests between peers

2016-03-24T20:18:41.602Z - info: Running on android test: 58. Test BEACONS_RETRIEVED_AND_PARSED locally

2016-03-24T20:18:43.024Z - debug: Socket disconnected: ping timeout 3 (Apple-Iphone5s-1)

2016-03-24T20:18:43.944Z - info: Running on android test: 59. Test HTTP_BAD_RESPONSE locally

2016-03-24T20:18:45.469Z - info: Running on android test: 60. Test NETWORK_PROBLEM locally

2016-03-24T20:18:47.597Z - info: Running on android test: 61. Test timeout locally

2016-03-24T20:18:49.660Z - info: Running on android test: 62. Call the start two times

2016-03-24T20:18:50.271Z - info: Running on android test: 63. Call the kill before calling the start

2016-03-24T20:18:50.840Z - info: Running on android test: 64. Call the kill immediately after the start

2016-03-24T20:18:51.365Z - info: Running on android test: 65. Call the kill while waiting a response from the server

2016-03-24T20:18:53.964Z - info: Running on android test: 66. Test to exceed the max content size locally

2016-03-24T20:18:54.496Z - info: Running on android test: 67. Close the server socket while the client is waiting a response from the server. Local test.

2016-03-24T20:18:57.072Z - info: Running on android test: 68. Close the client socket while the client is waiting a response from the server. Local test.

2016-03-24T20:18:59.689Z - info: Running on android test: 69. #generatePreambleAndBeacons bad args

2016-03-24T20:19:00.054Z - info: Running on android test: 70. #generatePreambleAndBeacons empty keys to notify

2016-03-24T20:19:00.546Z - info: Running on android test: 71. #generatePreambleAndBeacons multiple keys to notify

2016-03-24T20:19:01.148Z - info: Running on android test: 72. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-24T20:19:01.704Z - info: Running on android test: 73. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-24T20:19:02.148Z - info: Running on android test: 74. #parseBeacons expiration out of range lower

2016-03-24T20:19:02.643Z - info: Running on android test: 75. #parseBeacons expiration out of range lower

2016-03-24T20:19:04.168Z - info: Running on android test: 76. #parseBeacons no beacons returns null

2016-03-24T20:19:04.561Z - info: Running on android test: 77. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-24T20:19:05.068Z - info: Running on android test: 78. #parseBeacons addressBookCallback fails decrypt

2016-03-24T20:19:06.232Z - info: Running on android test: 79. #parseBeacons addressBookCallback returns no matches

2016-03-24T20:19:08.185Z - info: Running on android test: 80. #parseBeacons addressBookCallback returns spurious match

2016-03-24T20:19:10.441Z - info: Running on android test: 81. #parseBeacons addressBookCallback returns public key

2016-03-24T20:19:11.496Z - info: Running on android test: 82. validate generatePskIdentityField

2016-03-24T20:19:14.204Z - info: Running on android test: 83. validate generatePskSecret

2016-03-24T20:19:14.736Z - info: Running on android test: 84. Start and stop ThaliNotificationServer

2016-03-24T20:19:15.308Z - info: Running on android test: 85. Pass an empty array to ThaliNotificationServer.start

2016-03-24T20:19:19.457Z - info: Running on android test: 86. Pass a string to ThaliNotificationServer.start

2016-03-24T20:19:20.649Z - info: Running on android test: 87. Pass an empty parameter to ThaliNotificationServer.start

2016-03-24T20:19:21.472Z - info: Running on android test: 88. Make an HTTP request to /NotificationBeacons

2016-03-24T20:19:22.116Z - info: Running on android test: 89. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-24T20:19:22.650Z - info: Running on android test: 90. Make an HTTP request to /NotificationBeaconsbefore calling start

2016-03-24T20:19:23.087Z - info: Running on android test: 91. #testThaliPeerAction - test getters

2016-03-24T20:19:23.467Z - info: Running on android test: 92. #testThaliPeerAction - start and kill

2016-03-24T20:19:23.826Z - info: Running on android test: 93. #testThaliPeerAction - double start

2016-03-24T20:19:24.213Z - info: Running on android test: 94. #testThaliPeerAction - start after kill

2016-03-24T20:19:24.724Z - info: Running on android test: 95. #testThaliPeerAction - make sure ids are unique

2016-03-24T20:19:25.076Z - info: Running on android test: 96. Test PeerConnectionInformation basics

2016-03-24T20:19:25.475Z - info: Running on android test: 97. Test PeerDictionary basic functionality

2016-03-24T20:19:25.886Z - info: Running on android test: 98. Test PeerDictionary with multiple entries.

2016-03-24T20:19:27.671Z - info: Running on android test: 99. RESOLVED entries are removed before WAITING state entry.

2016-03-24T20:19:28.841Z - info: Running on android test: 100. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-24T20:19:30.054Z - info: Running on android test: 101. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-24T20:19:31.139Z - info: Running on android test: 102. #ThaliPeerPoolInterface - bad enqueues

2016-03-24T20:19:31.606Z - info: Running on android test: 103. #ThaliPeerPoolInterface - do not allow same object type

2016-03-24T20:19:32.045Z - info: Running on android test: 104. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-24T20:19:32.507Z - info: Running on android test: 105. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent

2016-03-24T20:19:32.961Z - info: Running on android test: 106. compareBufferArrays

2016-03-24T20:19:33.403Z - info: Running on android test: 107. Call start twice and get error

2016-03-24T20:19:33.879Z - info: Running on android test: 108. Start and make sure it runs

2016-03-24T20:19:34.436Z - info: Running on android test: 109. Make sure getTimeWhenRun is right after start

2016-03-24T20:19:34.829Z - info: Running on android test: 110. Make sure getTimeWhenRun is -1 after function is called

2016-03-24T20:19:35.180Z - info: Running on android test: 111. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-24T20:19:35.624Z - info: Running on android test: 112. Test TransientState

2016-03-24T20:19:36.272Z - info: Running on android test: 113. No peers and empty database

2016-03-24T20:19:40.143Z - info: Running on android test: 114. One peer and empty DB

2016-03-24T20:19:42.401Z - info: Running on android test: 115. One peer with _Local set behind current seq

2016-03-24T20:19:43.105Z - info: Running on android test: 116. One peer with _Local set equal to current seq

2016-03-24T20:19:44.013Z - info: Running on android test: 117. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-24T20:19:49.415Z - info: Running on android test: 118. Three peers, one not in DB, one behind and one ahead

2016-03-24T20:19:51.750Z - info: Running on android test: 119. More than maximum peers, make sure we only send maximum allowed

2016-03-24T20:19:52.939Z - info: Running on android test: 120. two peers with empty DB, update the doc

2016-03-24T20:19:54.592Z - info: Running on android test: 121. add doc and make sure tokens refresh when they expire

2016-03-24T20:19:55.722Z - info: Running on android test: 122. start and stop and start and stop

2016-03-24T20:19:56.579Z - info: Running on android test: 123. two identical starts in a row

2016-03-24T20:19:57.912Z - info: Running on android test: 124. two different starts in a row

2016-03-24T20:19:59.281Z - info: Running on android test: 125. two stops and a start and two stops

2016-03-24T20:20:00.060Z - info: Running on android test: 126. we properly enqueue requests so no then needed

2016-03-24T20:20:01.018Z - info: Running on android test: 127. test calculateSeqPointKeyId

2016-03-24T20:20:02.234Z - info: Running on android test: 128. can create servers manager

2016-03-24T20:20:02.625Z - info: Running on android test: 129. calling stop without start causes error

2016-03-24T20:20:03.031Z - info: Running on android test: 130. can start/stop servers manager

2016-03-24T20:20:03.562Z - info: Running on android test: 131. starting twice resolves with listening port

2016-03-24T20:20:04.110Z - info: Running on android test: 132. terminateIncomingConnection will terminate a connection

2016-03-24T20:20:04.703Z - info: Running on android test: 133. terminate an Outgoing connection will terminate the server

2016-03-24T20:20:08.113Z - info: Running on android test: 134. terminate an Outgoing connection with wrong arguments is not harmful

2016-03-24T20:20:09.675Z - info: Running on android test: 135. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-24T20:20:11.154Z - info: Running on android test: 136. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-24T20:20:11.598Z - info: Running on android test: 137. messages with invalid location or USN should be ignored

2016-03-24T20:20:12.057Z - info: Running on android test: 138. verify that Thali-specific messages are filtered correctly

2016-03-24T20:20:12.440Z - info: Running on android test: 139. #startListeningForAdvertisements should fail if start not called

2016-03-24T20:20:12.908Z - info: Running on android test: 140. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-24T20:20:13.577Z - info: Running on android test: 141. #start should fail if called twice in a row

2016-03-24T20:20:13.947Z - info: Running on android test: 142. should not be started after stop is called

2016-03-24T20:20:14.351Z - info: Running on android test: 143. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-24T20:20:14.756Z - info: Running on android test: 144. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-24T20:20:15.172Z - info: Running on android test: 145. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-24T20:20:15.581Z - info: Running on android test: 146. #stop can be called multiple times in a row

2016-03-24T20:20:15.955Z - info: Running on android test: 147. #startListeningForAdvertisements can be called multiple times in a row

2016-03-24T20:20:18.802Z - info: Running on android test: 148. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-24T20:20:20.677Z - info: Running on android test: 149. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-24T20:20:23.751Z - info: Running on android test: 150. functions are run from a queue in the right order

2016-03-24T20:20:25.718Z - info: Running on android test: 151. #ThaliPeerPoolDefault - single action

2016-03-24T20:20:26.192Z - info: Running on android test: 152. #ThaliPeerPoolDefault - multiple actions

2016-03-24T20:20:26.575Z - info: Test run on android complete

2016-03-24T20:20:26.578Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-24T20:20:26.580Z - info: PLATFORM: android

2016-03-24T20:20:26.581Z - info: RESULT: FAIL

2016-03-24T20:20:26.582Z - info: 152 of 152 tests completed
2016-03-24T20:20:26.583Z - info: 151/152 passed (1 failures)

2016-03-24T20:20:26.583Z - info: 

--- Failed tests ---

2016-03-24T20:20:26.585Z - warn: 56. we successfully receive and replay discoveryAdvertisingStateUpdate - fail

2016-03-24T20:20:26.586Z - info: 

-== END ==-

2016-03-24T20:20:27.314Z - debug: Socket disconnected: transport close 5 (motorola-Nexus 6)

2016-03-24T20:20:27.445Z - debug: Socket disconnected: transport close 4 (samsung-SM-N910C)

2016-03-24T20:20:27.722Z - debug: Socket disconnected: transport close 0 (LGE-LG-H815)

2016-03-24T20:36:06.074Z - debug: Socket disconnected: transport close 2 (Apple-Iphone6-1)

2016-03-24T20:36:06.124Z - debug: Socket disconnected: transport close 1 (Apple-Iphone5-1)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m
2016-03-24T20:16:52.156Z - error: Too many emit retries to device: Apple-Iphone5s-1

2016-03-24T20:17:12.216Z - error: Too many emit retries to device: samsung-SM-N910C


```


Logs for system : 
```

android : No Error

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
true

```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/63968542e6bfc69_A_lot_of_cleanup_yaronyg/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/63968542e6bfc69_A_lot_of_cleanup_yaronyg/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/63968542e6bfc69_A_lot_of_cleanup_yaronyg/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/63968542e6bfc69_A_lot_of_cleanup_yaronyg/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/63968542e6bfc69_A_lot_of_cleanup_yaronyg/iOS_server.md)




###Android Logs
####Node name: thali07
Console output:
```
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
Device test finished on 0c6a0f3c0bdb4e77 
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Android task is completed. [SUCCESS]
```
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/63968542e6bfc69_A_lot_of_cleanup_yaronyg/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/63968542e6bfc69_A_lot_of_cleanup_yaronyg/thali07_LGE-LG-H815.md)

####Node name: thali08
Console output:
```
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Device test finished on ZX1G429CRK 
Android task is completed. [SUCCESS]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/63968542e6bfc69_A_lot_of_cleanup_yaronyg/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/63968542e6bfc69_A_lot_of_cleanup_yaronyg/thali08_motorola-Nexus 6.md)



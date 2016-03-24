#### Test 640346198400100 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-03-24T14:03:56.854Z - info: listening on *:3000

2016-03-24T14:03:58.320Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:0

2016-03-24T14:04:00.396Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:1

2016-03-24T14:04:01.105Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:2

2016-03-24T14:04:02.425Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:3

2016-03-24T14:04:02.427Z - info: Required number of ios devices presented (3)

2016-03-24T14:04:02.431Z - info: Starting unit test run for platform: ios

2016-03-24T14:04:03.888Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-24T14:04:04.753Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:4

2016-03-24T14:04:06.966Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-24T14:04:07.413Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-24T14:04:07.785Z - info: Running on ios test: 4. native server connections all up

2016-03-24T14:04:08.355Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-24T14:04:08.755Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-24T14:04:09.191Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-24T14:04:09.601Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-24T14:04:10.087Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-24T14:04:13.560Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-24T14:04:14.231Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-24T14:04:14.599Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-24T14:04:14.977Z - info: Running on ios test: 13. closeAll with promise

2016-03-24T14:04:15.367Z - info: Running on ios test: 14. multiplex can send data

2016-03-24T14:04:15.835Z - info: Running on ios test: 15. enqueue and run in order

2016-03-24T14:04:16.459Z - info: Running on ios test: 16. enqueueAtTop and run backwards

2016-03-24T14:04:16.909Z - info: Running on ios test: 17. mix enqueue and enqueueAtTop

2016-03-24T14:04:17.452Z - info: Running on ios test: 18. queues handled independently

2016-03-24T14:04:17.805Z - info: Running on ios test: 19. basic

2016-03-24T14:04:18.165Z - info: Running on ios test: 20. another

2016-03-24T14:04:18.462Z - info: Running on ios test: 21. can pass data in setup

2016-03-24T14:04:18.789Z - info: Running on ios test: 22. #startListeningForAdvertisements should fail if start not called

2016-03-24T14:04:18.802Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:5

2016-03-24T14:04:18.803Z - info: Required number of android devices presented (3)

2016-03-24T14:04:18.805Z - info: Starting unit test run for platform: android

2016-03-24T14:04:19.123Z - info: Running on ios test: 23. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-24T14:04:19.480Z - info: Running on ios test: 24. should be able to call #stopListeningForAdvertisements many times

2016-03-24T14:04:19.518Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-24T14:04:19.824Z - info: Running on ios test: 25. should be able to call #startListeningForAdvertisements many times

2016-03-24T14:04:19.920Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-24T14:04:20.297Z - info: Running on ios test: 26. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-24T14:04:20.313Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-24T14:04:20.755Z - info: Running on android test: 4. native server connections all up

2016-03-24T14:04:20.933Z - info: Running on ios test: 27. should be able to call #stopAdvertisingAndListening many times

2016-03-24T14:04:21.221Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-24T14:04:35.124Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-24T14:04:41.006Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-24T14:04:41.675Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-24T14:04:42.173Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-24T14:04:43.580Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-24T14:04:45.047Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-24T14:04:45.712Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-24T14:04:46.068Z - info: Running on android test: 13. closeAll with promise

2016-03-24T14:04:46.567Z - info: Running on android test: 14. multiplex can send data

2016-03-24T14:04:47.027Z - info: Running on android test: 15. enqueue and run in order

2016-03-24T14:04:47.933Z - info: Running on android test: 16. enqueueAtTop and run backwards

2016-03-24T14:04:48.473Z - info: Running on android test: 17. mix enqueue and enqueueAtTop

2016-03-24T14:04:49.026Z - info: Running on android test: 18. queues handled independently

2016-03-24T14:04:49.456Z - info: Running on android test: 19. basic

2016-03-24T14:04:49.822Z - info: Running on android test: 20. another

2016-03-24T14:04:50.414Z - info: Running on android test: 21. can pass data in setup

2016-03-24T14:04:50.761Z - info: Running on android test: 22. #startListeningForAdvertisements should fail if start not called

2016-03-24T14:04:51.205Z - info: Running on android test: 23. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-24T14:04:51.704Z - info: Running on android test: 24. should be able to call #stopListeningForAdvertisements many times

2016-03-24T14:04:52.234Z - info: Running on android test: 25. should be able to call #startListeningForAdvertisements many times

2016-03-24T14:04:53.023Z - info: Running on android test: 26. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-24T14:04:53.783Z - info: Running on android test: 27. should be able to call #stopAdvertisingAndListening many times

2016-03-24T14:04:54.216Z - info: Running on android test: 28. #start should fail if called twice in a row

2016-03-24T14:04:54.636Z - info: Running on android test: 29. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-24T14:04:55.826Z - info: Running on android test: 30. does not send duplicate availability changes

2016-03-24T14:04:56.218Z - info: Running on android test: 31. can get the network status

2016-03-24T14:04:56.736Z - info: Running on android test: 32. wifi peer is marked unavailable if announcements stop

2016-03-24T14:04:59.168Z - info: Running on android test: 33. Can call start/stopListeningForAdvertisements

2016-03-24T14:04:59.708Z - info: Running on android test: 34. Calling startListeningForAdvertisements twice is NOT an error

2016-03-24T14:05:00.413Z - info: Running on android test: 35. Can call start/stopUpdateAdvertisingAndListening

2016-03-24T14:05:01.209Z - info: Running on android test: 36. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-24T14:05:02.830Z - info: Running on android test: 37. peerAvailabilityChange is called

2016-03-24T14:05:04.999Z - info: Running on android test: 38. Can connect to a remote peer

2016-03-24T14:05:12.967Z - info: Running on android test: 39. Can shift large amounts of data

2016-03-24T14:05:24.021Z - info: Running on android test: 40. #startListeningForAdvertisements should fail if start not called

2016-03-24T14:05:24.644Z - info: Running on android test: 41. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-24T14:05:25.196Z - info: Running on android test: 42. should be able to call #stopListeningForAdvertisements many times

2016-03-24T14:05:25.729Z - info: Running on android test: 43. should be able to call #startListeningForAdvertisements many times

2016-03-24T14:05:26.405Z - info: Running on android test: 44. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-24T14:05:27.481Z - info: Running on android test: 45. should be able to call #stopAdvertisingAndListening many times

2016-03-24T14:05:27.967Z - info: Running on android test: 46. can get the network status before starting

2016-03-24T14:05:28.434Z - info: Running on android test: 47. error returned with bad router

2016-03-24T14:05:28.922Z - info: Running on android test: 48. all services are stopped when we call stop

2016-03-24T14:05:29.759Z - info: Running on android test: 49. make sure terminateConnection is properly hooked up

2016-03-24T14:05:30.226Z - info: Running on android test: 50. make sure terminateListener is properly hooked up

2016-03-24T14:05:30.650Z - info: Running on android test: 51. make sure we actually call kill connections properly

2016-03-24T14:05:31.054Z - info: Running on android test: 52. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received

2016-03-24T14:05:31.565Z - info: Running on android test: 53. We repeat failedConnection event when we get it from thaliTcpServersManager

2016-03-24T14:05:32.057Z - info: Running on android test: 54. we successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-24T14:05:33.149Z - warn: Failed on android test: 54. we successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-24T14:05:33.150Z - info: Running on android test: 55. can do HTTP requests between peers

2016-03-24T14:05:42.718Z - info: Running on android test: 56. Test BEACONS_RETRIEVED_AND_PARSED locally

2016-03-24T14:05:43.452Z - info: Running on android test: 57. Test HTTP_BAD_RESPONSE locally

2016-03-24T14:05:43.996Z - info: Running on android test: 58. Test NETWORK_PROBLEM locally

2016-03-24T14:05:46.053Z - info: Running on android test: 59. Test timeout locally

2016-03-24T14:05:48.244Z - info: Running on android test: 60. Call the start two times

2016-03-24T14:05:48.750Z - info: Running on android test: 61. Call the kill before calling the start

2016-03-24T14:05:49.258Z - info: Running on android test: 62. Call the kill immediately after the start

2016-03-24T14:05:50.245Z - info: Running on android test: 63. Call the kill while waiting a response from the server

2016-03-24T14:05:52.882Z - info: Running on android test: 64. Test to exceed the max content size locally

2016-03-24T14:05:53.609Z - info: Running on android test: 65. Close the server socket while the client is waiting a response from the server. Local test.

2016-03-24T14:05:56.173Z - info: Running on android test: 66. Close the client socket while the client is waiting a response from the server. Local test.

2016-03-24T14:05:58.703Z - info: Running on android test: 67. #generatePreambleAndBeacons bad args

2016-03-24T14:05:59.158Z - info: Running on android test: 68. #generatePreambleAndBeacons empty keys to notify

2016-03-24T14:05:59.594Z - info: Running on android test: 69. #generatePreambleAndBeacons multiple keys to notify

2016-03-24T14:06:00.146Z - info: Running on android test: 70. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-24T14:06:00.607Z - info: Running on android test: 71. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-24T14:06:00.966Z - info: Running on android test: 72. #parseBeacons expiration out of range lower

2016-03-24T14:06:01.442Z - info: Running on android test: 73. #parseBeacons expiration out of range lower

2016-03-24T14:06:01.997Z - info: Running on android test: 74. #parseBeacons no beacons returns null

2016-03-24T14:06:02.480Z - info: Running on android test: 75. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-24T14:06:02.952Z - info: Running on android test: 76. #parseBeacons addressBookCallback fails decrypt

2016-03-24T14:06:03.628Z - info: Running on android test: 77. #parseBeacons addressBookCallback returns no matches

2016-03-24T14:06:04.227Z - info: Running on android test: 78. #parseBeacons addressBookCallback returns spurious match

2016-03-24T14:06:07.231Z - info: Running on android test: 79. #parseBeacons addressBookCallback returns public key

2016-03-24T14:06:08.150Z - info: Running on android test: 80. validate generatePskIdentityField

2016-03-24T14:06:08.588Z - info: Running on android test: 81. validate generatePskSecret

2016-03-24T14:06:08.994Z - info: Running on android test: 82. Start and stop ThaliNotificationServer

2016-03-24T14:06:09.501Z - info: Running on android test: 83. Pass an empty array to ThaliNotificationServer.start

2016-03-24T14:06:10.040Z - info: Running on android test: 84. Pass a string to ThaliNotificationServer.start

2016-03-24T14:06:10.462Z - info: Running on android test: 85. Pass an empty parameter to ThaliNotificationServer.start

2016-03-24T14:06:10.933Z - info: Running on android test: 86. Make an HTTP request to /NotificationBeacons

2016-03-24T14:06:11.501Z - info: Running on android test: 87. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-24T14:06:11.957Z - info: Running on android test: 88. Make an HTTP request to /NotificationBeaconsbefore calling start

2016-03-24T14:06:12.420Z - info: Running on android test: 89. #testThaliPeerAction - test getters

2016-03-24T14:06:12.866Z - info: Running on android test: 90. #testThaliPeerAction - start and kill

2016-03-24T14:06:13.415Z - info: Running on android test: 91. #testThaliPeerAction - double start

2016-03-24T14:06:13.861Z - info: Running on android test: 92. #testThaliPeerAction - start after kill

2016-03-24T14:06:14.261Z - info: Running on android test: 93. #testThaliPeerAction - make sure ids are unique

2016-03-24T14:06:14.724Z - info: Running on android test: 94. Test PeerConnectionInformation basics

2016-03-24T14:06:15.469Z - info: Running on android test: 95. Test PeerDictionary basic functionality

2016-03-24T14:06:16.068Z - info: Running on android test: 96. Test PeerDictionary with multiple entries.

2016-03-24T14:06:18.227Z - info: Running on android test: 97. RESOLVED entries are removed before WAITING state entry.

2016-03-24T14:06:18.797Z - debug: Socket disconnected: ping timeout 2 (Apple-Iphone5s-1)

2016-03-24T14:06:19.719Z - info: Running on android test: 98. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-24T14:06:21.259Z - info: Running on android test: 99. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-24T14:06:22.755Z - info: Running on android test: 100. #ThaliPeerPoolInterface - bad enqueues

2016-03-24T14:06:23.272Z - info: Running on android test: 101. #ThaliPeerPoolInterface - do not allow same object type

2016-03-24T14:06:23.753Z - info: Running on android test: 102. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-24T14:06:24.275Z - info: Running on android test: 103. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent

2016-03-24T14:06:25.232Z - info: Running on android test: 104. compareBufferArrays

2016-03-24T14:06:25.622Z - info: Running on android test: 105. Call start twice and get error

2016-03-24T14:06:26.041Z - info: Running on android test: 106. Start and make sure it runs

2016-03-24T14:06:26.388Z - info: Running on android test: 107. Make sure getTimeWhenRun is right after start

2016-03-24T14:06:26.761Z - info: Running on android test: 108. Make sure getTimeWhenRun is -1 after function is called

2016-03-24T14:06:27.249Z - info: Running on android test: 109. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-24T14:06:27.588Z - info: Running on android test: 110. Test TransientState

2016-03-24T14:06:27.966Z - info: Running on android test: 111. No peers and empty database

2016-03-24T14:06:28.732Z - info: Running on android test: 112. One peer and empty DB

2016-03-24T14:06:29.672Z - info: Running on android test: 113. One peer with _Local set behind current seq

2016-03-24T14:06:34.382Z - info: Running on android test: 114. One peer with _Local set equal to current seq

2016-03-24T14:06:35.230Z - info: Running on android test: 115. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-24T14:06:35.779Z - info: Running on android test: 116. Three peers, one not in DB, one behind and one ahead

2016-03-24T14:06:36.734Z - info: Running on android test: 117. More than maximum peers, make sure we only send maximum allowed

2016-03-24T14:06:37.846Z - info: Running on android test: 118. two peers with empty DB, update the doc

2016-03-24T14:06:38.777Z - info: Running on android test: 119. add doc and make sure tokens refresh when they expire

2016-03-24T14:06:40.519Z - info: Running on android test: 120. start and stop and start and stop

2016-03-24T14:06:41.683Z - info: Running on android test: 121. two identical starts in a row

2016-03-24T14:06:42.417Z - info: Running on android test: 122. two different starts in a row

2016-03-24T14:06:43.167Z - info: Running on android test: 123. two stops and a start and two stops

2016-03-24T14:06:44.074Z - info: Running on android test: 124. we properly enqueue requests so no then needed

2016-03-24T14:06:44.772Z - info: Running on android test: 125. test calculateSeqPointKeyId

2016-03-24T14:06:45.305Z - info: Running on android test: 126. can create servers manager

2016-03-24T14:06:45.992Z - info: Running on android test: 127. calling stop without start causes error

2016-03-24T14:06:46.695Z - info: Running on android test: 128. can start/stop servers manager

2016-03-24T14:06:47.409Z - info: Running on android test: 129. starting twice resolves with listening port

2016-03-24T14:06:47.812Z - info: Running on android test: 130. terminateIncomingConnection will terminate a connection

2016-03-24T14:06:48.354Z - info: Running on android test: 131. terminate an Outgoing connection will terminate the server

2016-03-24T14:06:48.753Z - info: Running on android test: 132. terminate an Outgoing connection with wrong arguments is not harmful

2016-03-24T14:06:49.256Z - info: Running on android test: 133. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-24T14:06:49.594Z - info: Running on android test: 134. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-24T14:06:50.066Z - info: Running on android test: 135. messages with invalid location or USN should be ignored

2016-03-24T14:06:50.468Z - info: Running on android test: 136. verify that Thali-specific messages are filtered correctly

2016-03-24T14:06:52.313Z - info: Running on android test: 137. #startListeningForAdvertisements should fail if start not called

2016-03-24T14:06:53.443Z - info: Running on android test: 138. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-24T14:06:54.492Z - info: Running on android test: 139. #start should fail if called twice in a row

2016-03-24T14:06:55.014Z - info: Running on android test: 140. should not be started after stop is called

2016-03-24T14:06:55.402Z - info: Running on android test: 141. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-24T14:06:56.909Z - info: Running on android test: 142. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-24T14:06:57.792Z - info: Running on android test: 143. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-24T14:06:58.302Z - info: Running on android test: 144. #stop can be called multiple times in a row

2016-03-24T14:06:58.763Z - info: Running on android test: 145. #startListeningForAdvertisements can be called multiple times in a row

2016-03-24T14:06:59.230Z - info: Running on android test: 146. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-24T14:06:59.665Z - info: Running on android test: 147. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-24T14:07:00.048Z - info: Running on android test: 148. functions are run from a queue in the right order

2016-03-24T14:07:00.614Z - info: Running on android test: 149. #ThaliPeerPoolDefault - single action

2016-03-24T14:07:01.114Z - info: Running on android test: 150. #ThaliPeerPoolDefault - multiple actions

2016-03-24T14:07:01.450Z - info: Test run on android complete

2016-03-24T14:07:01.452Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-24T14:07:01.454Z - info: PLATFORM: android

2016-03-24T14:07:01.455Z - info: RESULT: FAIL
2016-03-24T14:07:01.456Z - info: 150 of 150 tests completed

2016-03-24T14:07:01.457Z - info: 149/150 passed (1 failures)
2016-03-24T14:07:01.457Z - info: 

--- Failed tests ---

2016-03-24T14:07:01.459Z - warn: 54. we successfully receive and replay discoveryAdvertisingStateUpdate - fail

2016-03-24T14:07:01.460Z - info: 

-== END ==-

2016-03-24T14:07:02.202Z - debug: Socket disconnected: transport close 5 (motorola-Nexus 6)

2016-03-24T14:07:02.275Z - debug: Socket disconnected: transport close 4 (samsung-SM-N910C)

2016-03-24T14:07:02.348Z - debug: Socket disconnected: transport close 1 (LGE-LG-H815)

2016-03-24T14:23:48.264Z - debug: Socket disconnected: transport close 0 (Apple-Iphone6-1)

2016-03-24T14:23:48.286Z - debug: Socket disconnected: transport close 3 (Apple-Iphone5-1)

2016-03-24T14:23:48.292Z - debug: Socket disconnected: transport close 6 (NOT YET SET)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m
2016-03-24T14:04:35.111Z - error: Too many emit retries to device: Apple-Iphone6-1

2016-03-24T14:04:35.118Z - error: Too many emit retries to device: Apple-Iphone5s-1

2016-03-24T14:04:53.576Z - error: Too many emit retries to device: Apple-Iphone5s-1


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
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/640346198400100_Peer_unavailable_event_when_port_changes_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/640346198400100_Peer_unavailable_event_when_port_changes_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/640346198400100_Peer_unavailable_event_when_port_changes_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/640346198400100_Peer_unavailable_event_when_port_changes_vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/640346198400100_Peer_unavailable_event_when_port_changes_vjrantal/iOS_server.md)




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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/640346198400100_Peer_unavailable_event_when_port_changes_vjrantal/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/640346198400100_Peer_unavailable_event_when_port_changes_vjrantal/thali07_LGE-LG-H815.md)

####Node name: thali08
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
Device test finished on 41006f95c8139173 
Android task is completed. [SUCCESS]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/640346198400100_Peer_unavailable_event_when_port_changes_vjrantal/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/640346198400100_Peer_unavailable_event_when_port_changes_vjrantal/thali08_motorola-Nexus 6.md)



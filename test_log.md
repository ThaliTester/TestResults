#### Test 63998117be38304 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-03-24T07:47:36.200Z - info: listening on *:3000

2016-03-24T07:47:36.849Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:0

2016-03-24T07:47:36.872Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:1

2016-03-24T07:47:39.687Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:2

2016-03-24T07:47:41.582Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:3

2016-03-24T07:47:41.584Z - info: Required number of ios devices presented (3)

2016-03-24T07:47:41.588Z - info: Starting unit test run for platform: ios

2016-03-24T07:47:42.338Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-24T07:47:43.157Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:4

2016-03-24T07:47:43.923Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-24T07:47:44.275Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-24T07:47:44.721Z - info: Running on ios test: 4. native server connections all up

2016-03-24T07:47:45.219Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-24T07:47:45.635Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-24T07:47:46.172Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-24T07:47:46.640Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-24T07:47:47.039Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-24T07:47:49.768Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-24T07:47:50.389Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-24T07:47:51.018Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-24T07:47:51.373Z - info: Running on ios test: 13. closeAll with promise

2016-03-24T07:47:51.732Z - info: Running on ios test: 14. multiplex can send data

2016-03-24T07:47:52.217Z - info: Running on ios test: 15. enqueue and run in order

2016-03-24T07:47:52.787Z - info: Running on ios test: 16. enqueueAtTop and run backwards

2016-03-24T07:47:53.210Z - info: Running on ios test: 17. mix enqueue and enqueueAtTop

2016-03-24T07:47:53.825Z - info: Running on ios test: 18. queues handled independently

2016-03-24T07:47:54.360Z - info: Running on ios test: 19. basic

2016-03-24T07:47:54.736Z - info: Running on ios test: 20. another

2016-03-24T07:47:55.231Z - info: Running on ios test: 21. can pass data in setup

2016-03-24T07:47:55.625Z - info: Running on ios test: 22. #startListeningForAdvertisements should fail if start not called

2016-03-24T07:47:56.007Z - info: Running on ios test: 23. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-24T07:47:56.348Z - info: Running on ios test: 24. should be able to call #stopListeningForAdvertisements many times

2016-03-24T07:47:56.811Z - info: Running on ios test: 25. should be able to call #startListeningForAdvertisements many times

2016-03-24T07:47:57.518Z - info: Running on ios test: 26. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-24T07:48:09.392Z - debug: Socket disconnected: transport close 2 (Apple-Iphone6-1)

2016-03-24T07:48:14.934Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:5

2016-03-24T07:48:14.938Z - info: Required number of android devices presented (3)

2016-03-24T07:48:14.943Z - info: Starting unit test run for platform: android

2016-03-24T07:48:19.791Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-24T07:48:35.720Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-24T07:48:38.630Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-24T07:48:39.103Z - info: Running on android test: 4. native server connections all up

2016-03-24T07:48:39.623Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-24T07:48:42.184Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-24T07:48:43.448Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-24T07:48:44.046Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-24T07:48:44.526Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-24T07:48:45.452Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-24T07:48:45.949Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-24T07:48:46.370Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-24T07:48:46.782Z - info: Running on android test: 13. closeAll with promise

2016-03-24T07:48:47.057Z - info: Running on android test: 14. multiplex can send data

2016-03-24T07:48:47.399Z - info: Running on android test: 15. enqueue and run in order

2016-03-24T07:48:48.120Z - info: Running on android test: 16. enqueueAtTop and run backwards

2016-03-24T07:48:48.504Z - info: Running on android test: 17. mix enqueue and enqueueAtTop

2016-03-24T07:48:49.029Z - info: Running on android test: 18. queues handled independently

2016-03-24T07:48:49.393Z - info: Running on android test: 19. basic

2016-03-24T07:48:49.804Z - info: Running on android test: 20. another

2016-03-24T07:48:50.154Z - info: Running on android test: 21. can pass data in setup

2016-03-24T07:48:50.457Z - info: Running on android test: 22. #startListeningForAdvertisements should fail if start not called

2016-03-24T07:48:50.858Z - info: Running on android test: 23. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-24T07:48:51.248Z - info: Running on android test: 24. should be able to call #stopListeningForAdvertisements many times

2016-03-24T07:48:51.674Z - info: Running on android test: 25. should be able to call #startListeningForAdvertisements many times

2016-03-24T07:48:56.538Z - info: Running on android test: 26. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-24T07:48:57.688Z - info: Running on android test: 27. should be able to call #stopAdvertisingAndListening many times

2016-03-24T07:48:58.134Z - info: Running on android test: 28. #start should fail if called twice in a row

2016-03-24T07:48:58.509Z - info: Running on android test: 29. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-24T07:49:00.810Z - info: Running on android test: 30. does not send duplicate availability changes

2016-03-24T07:49:01.151Z - info: Running on android test: 31. can get the network status

2016-03-24T07:49:01.466Z - info: Running on android test: 32. wifi peer is marked unavailable if announcements stop

2016-03-24T07:49:03.837Z - info: Running on android test: 33. Can call start/stopListeningForAdvertisements

2016-03-24T07:49:04.378Z - info: Running on android test: 34. Calling startListeningForAdvertisements twice is NOT an error

2016-03-24T07:49:05.016Z - info: Running on android test: 35. Can call start/stopUpdateAdvertisingAndListening

2016-03-24T07:49:05.573Z - info: Running on android test: 36. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-24T07:49:06.912Z - info: Running on android test: 37. peerAvailabilityChange is called

2016-03-24T07:49:08.977Z - info: Running on android test: 38. Can connect to a remote peer

2016-03-24T07:49:19.387Z - info: Running on android test: 39. Can shift large amounts of data

2016-03-24T07:49:26.692Z - debug: Socket disconnected: ping timeout 0 (Apple-Iphone5-1)

2016-03-24T07:49:29.216Z - info: Running on android test: 40. #startListeningForAdvertisements should fail if start not called

2016-03-24T07:49:33.309Z - info: Running on android test: 41. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-24T07:49:45.525Z - info: Running on android test: 42. should be able to call #stopListeningForAdvertisements many times

2016-03-24T07:49:50.623Z - info: Running on android test: 43. should be able to call #startListeningForAdvertisements many times

2016-03-24T07:49:54.661Z - info: Running on android test: 44. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-24T07:49:57.047Z - info: Running on android test: 45. should be able to call #stopAdvertisingAndListening many times

2016-03-24T07:49:57.644Z - info: Running on android test: 46. can get the network status before starting

2016-03-24T07:49:59.704Z - info: Running on android test: 47. error returned with bad router

2016-03-24T07:50:00.300Z - info: Running on android test: 48. all services are stopped when we call stop

2016-03-24T07:50:01.337Z - info: Running on android test: 49. make sure terminateConnection is properly hooked up

2016-03-24T07:50:01.781Z - info: Running on android test: 50. make sure terminateListener is properly hooked up

2016-03-24T07:50:02.398Z - info: Running on android test: 51. make sure we actually call kill connections properly

2016-03-24T07:50:02.784Z - info: Running on android test: 52. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received

2016-03-24T07:50:03.291Z - info: Running on android test: 53. We repeat failedConnection event when we get it from thaliTcpServersManager

2016-03-24T07:50:03.646Z - info: Running on android test: 54. we successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-24T07:50:04.549Z - warn: Failed on android test: 54. we successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-24T07:50:04.550Z - info: Running on android test: 55. can do HTTP requests between peers

2016-03-24T07:50:14.419Z - info: Running on android test: 56. can still do HTTP requests between peers

2016-03-24T07:50:27.589Z - info: Running on android test: 57. Test BEACONS_RETRIEVED_AND_PARSED locally

2016-03-24T07:50:32.168Z - info: Running on android test: 58. Test HTTP_BAD_RESPONSE locally

2016-03-24T07:50:36.126Z - info: Running on android test: 59. Test NETWORK_PROBLEM locally

2016-03-24T07:50:38.416Z - info: Running on android test: 60. Test timeout locally

2016-03-24T07:50:41.407Z - info: Running on android test: 61. Call the start two times

2016-03-24T07:50:42.279Z - info: Running on android test: 62. Call the kill before calling the start

2016-03-24T07:50:42.850Z - info: Running on android test: 63. Call the kill immediately after the start

2016-03-24T07:50:43.335Z - info: Running on android test: 64. Call the kill while waiting a response from the server

2016-03-24T07:50:45.899Z - info: Running on android test: 65. Test to exceed the max content size locally

2016-03-24T07:50:46.482Z - info: Running on android test: 66. Close the server socket while the client is waiting a response from the server. Local test.

2016-03-24T07:50:49.064Z - info: Running on android test: 67. Close the client socket while the client is waiting a response from the server. Local test.

2016-03-24T07:50:51.631Z - info: Running on android test: 68. #generatePreambleAndBeacons bad args

2016-03-24T07:50:52.294Z - info: Running on android test: 69. #generatePreambleAndBeacons empty keys to notify

2016-03-24T07:50:54.716Z - info: Running on android test: 70. #generatePreambleAndBeacons multiple keys to notify

2016-03-24T07:50:56.181Z - info: Running on android test: 71. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-24T07:50:56.546Z - info: Running on android test: 72. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-24T07:50:56.945Z - info: Running on android test: 73. #parseBeacons expiration out of range lower

2016-03-24T07:50:57.376Z - info: Running on android test: 74. #parseBeacons expiration out of range lower

2016-03-24T07:50:57.836Z - info: Running on android test: 75. #parseBeacons no beacons returns null

2016-03-24T07:50:58.184Z - info: Running on android test: 76. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-24T07:50:59.809Z - info: Running on android test: 77. #parseBeacons addressBookCallback fails decrypt

2016-03-24T07:51:00.327Z - info: Running on android test: 78. #parseBeacons addressBookCallback returns no matches

2016-03-24T07:51:00.770Z - info: Running on android test: 79. #parseBeacons addressBookCallback returns spurious match

2016-03-24T07:51:01.312Z - info: Running on android test: 80. #parseBeacons addressBookCallback returns public key

2016-03-24T07:51:01.812Z - info: Running on android test: 81. validate generatePskIdentityField

2016-03-24T07:51:02.164Z - info: Running on android test: 82. validate generatePskSecret

2016-03-24T07:51:02.628Z - info: Running on android test: 83. Start and stop ThaliNotificationServer

2016-03-24T07:51:03.106Z - info: Running on android test: 84. Pass an empty array to ThaliNotificationServer.start

2016-03-24T07:51:03.667Z - info: Running on android test: 85. Pass a string to ThaliNotificationServer.start

2016-03-24T07:51:04.140Z - info: Running on android test: 86. Pass an empty parameter to ThaliNotificationServer.start

2016-03-24T07:51:04.622Z - info: Running on android test: 87. Make an HTTP request to /NotificationBeacons

2016-03-24T07:51:05.242Z - info: Running on android test: 88. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-24T07:51:07.747Z - info: Running on android test: 89. Make an HTTP request to /NotificationBeaconsbefore calling start

2016-03-24T07:51:09.561Z - info: Running on android test: 90. #testThaliPeerAction - test getters

2016-03-24T07:51:10.250Z - info: Running on android test: 91. #testThaliPeerAction - start and kill

2016-03-24T07:51:10.579Z - info: Running on android test: 92. #testThaliPeerAction - double start

2016-03-24T07:51:10.943Z - info: Running on android test: 93. #testThaliPeerAction - start after kill

2016-03-24T07:51:11.247Z - info: Running on android test: 94. #testThaliPeerAction - make sure ids are unique

2016-03-24T07:51:11.642Z - info: Running on android test: 95. Test PeerConnectionInformation basics

2016-03-24T07:51:12.066Z - info: Running on android test: 96. Test PeerDictionary basic functionality

2016-03-24T07:51:12.508Z - info: Running on android test: 97. Test PeerDictionary with multiple entries.

2016-03-24T07:51:14.274Z - info: Running on android test: 98. RESOLVED entries are removed before WAITING state entry.

2016-03-24T07:51:15.697Z - info: Running on android test: 99. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-24T07:51:17.939Z - info: Running on android test: 100. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-24T07:51:19.331Z - info: Running on android test: 101. #ThaliPeerPoolInterface - bad enqueues

2016-03-24T07:51:19.674Z - info: Running on android test: 102. #ThaliPeerPoolInterface - do not allow same object type

2016-03-24T07:51:20.031Z - info: Running on android test: 103. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-24T07:51:20.397Z - info: Running on android test: 104. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent

2016-03-24T07:51:20.702Z - info: Running on android test: 105. compareBufferArrays

2016-03-24T07:51:21.115Z - info: Running on android test: 106. Call start twice and get error

2016-03-24T07:51:21.516Z - info: Running on android test: 107. Start and make sure it runs

2016-03-24T07:51:21.918Z - info: Running on android test: 108. Make sure getTimeWhenRun is right after start

2016-03-24T07:51:22.384Z - info: Running on android test: 109. Make sure getTimeWhenRun is -1 after function is called

2016-03-24T07:51:22.663Z - info: Running on android test: 110. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-24T07:51:23.025Z - info: Running on android test: 111. Test TransientState

2016-03-24T07:51:23.502Z - info: Running on android test: 112. No peers and empty database

2016-03-24T07:51:24.347Z - info: Running on android test: 113. One peer and empty DB

2016-03-24T07:51:28.490Z - info: Running on android test: 114. One peer with _Local set behind current seq

2016-03-24T07:51:29.312Z - info: Running on android test: 115. One peer with _Local set equal to current seq

2016-03-24T07:51:29.840Z - info: Running on android test: 116. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-24T07:51:30.939Z - info: Running on android test: 117. Three peers, one not in DB, one behind and one ahead

2016-03-24T07:51:31.980Z - info: Running on android test: 118. More than maximum peers, make sure we only send maximum allowed

2016-03-24T07:51:34.723Z - info: Running on android test: 119. two peers with empty DB, update the doc

2016-03-24T07:51:35.740Z - info: Running on android test: 120. add doc and make sure tokens refresh when they expire

2016-03-24T07:51:36.680Z - info: Running on android test: 121. start and stop and start and stop

2016-03-24T07:51:37.559Z - info: Running on android test: 122. two identical starts in a row

2016-03-24T07:51:38.830Z - info: Running on android test: 123. two different starts in a row

2016-03-24T07:51:39.581Z - info: Running on android test: 124. two stops and a start and two stops

2016-03-24T07:51:40.125Z - info: Running on android test: 125. we properly enqueue requests so no then needed

2016-03-24T07:51:40.588Z - info: Running on android test: 126. test calculateSeqPointKeyId

2016-03-24T07:51:40.922Z - info: Running on android test: 127. can create servers manager

2016-03-24T07:51:41.339Z - info: Running on android test: 128. calling stop without start causes error

2016-03-24T07:51:41.721Z - info: Running on android test: 129. can start/stop servers manager

2016-03-24T07:51:42.234Z - info: Running on android test: 130. starting twice resolves with listening port

2016-03-24T07:51:42.738Z - info: Running on android test: 131. terminateIncomingConnection will terminate a connection

2016-03-24T07:51:44.537Z - info: Running on android test: 132. terminate an Outgoing connection will terminate the server

2016-03-24T07:51:46.366Z - info: Running on android test: 133. terminate an Outgoing connection with wrong arguments is not harmful

2016-03-24T07:51:48.922Z - info: Running on android test: 134. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-24T07:51:53.121Z - info: Running on android test: 135. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-24T07:51:53.792Z - info: Running on android test: 136. messages with invalid location or USN should be ignored

2016-03-24T07:51:54.264Z - info: Running on android test: 137. verify that Thali-specific messages are filtered correctly

2016-03-24T07:51:54.828Z - info: Running on android test: 138. #startListeningForAdvertisements should fail if start not called

2016-03-24T07:51:55.318Z - info: Running on android test: 139. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-24T07:51:55.830Z - info: Running on android test: 140. #start should fail if called twice in a row

2016-03-24T07:51:56.372Z - info: Running on android test: 141. should not be started after stop is called

2016-03-24T07:51:56.752Z - info: Running on android test: 142. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-24T07:51:57.160Z - info: Running on android test: 143. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-24T07:51:57.636Z - info: Running on android test: 144. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-24T07:51:58.045Z - info: Running on android test: 145. #stop can be called multiple times in a row

2016-03-24T07:51:58.458Z - info: Running on android test: 146. #startListeningForAdvertisements can be called multiple times in a row

2016-03-24T07:51:58.963Z - info: Running on android test: 147. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-24T07:51:59.317Z - info: Running on android test: 148. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-24T07:51:59.686Z - info: Running on android test: 149. functions are run from a queue in the right order

2016-03-24T07:52:00.072Z - info: Running on android test: 150. #ThaliPeerPoolDefault - single action

2016-03-24T07:52:00.484Z - info: Running on android test: 151. #ThaliPeerPoolDefault - multiple actions

2016-03-24T07:52:00.830Z - info: Test run on android complete

2016-03-24T07:52:00.833Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-24T07:52:00.835Z - info: PLATFORM: android

2016-03-24T07:52:00.835Z - info: RESULT: FAIL
2016-03-24T07:52:00.836Z - info: 151 of 151 tests completed

2016-03-24T07:52:00.837Z - info: 150/151 passed (1 failures)
2016-03-24T07:52:00.837Z - info: 

--- Failed tests ---
2016-03-24T07:52:00.838Z - warn: 54. we successfully receive and replay discoveryAdvertisingStateUpdate - fail

2016-03-24T07:52:00.839Z - info: 

-== END ==-

2016-03-24T07:52:01.562Z - debug: Socket disconnected: transport close 5 (motorola-Nexus 6)

2016-03-24T07:52:01.696Z - debug: Socket disconnected: transport close 4 (samsung-SM-N910C)

2016-03-24T07:52:01.897Z - debug: Socket disconnected: transport close 1 (LGE-LG-H815)

2016-03-24T07:57:51.426Z - debug: Socket disconnected: ping timeout 3 (Apple-Iphone5s-1)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

android : No Error

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code 254 on device 2a65f58f9902a701b5c9a55b2befb18672927474 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
true

```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/63998117be38304_More_tests_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/63998117be38304_More_tests_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/63998117be38304_More_tests_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/63998117be38304_More_tests_vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/63998117be38304_More_tests_vjrantal/iOS_server.md)




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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/63998117be38304_More_tests_vjrantal/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/63998117be38304_More_tests_vjrantal/thali07_LGE-LG-H815.md)

####Node name: thali08
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
Device test finished on 41006f95c8139173 
Android task is completed. [SUCCESS]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/63998117be38304_More_tests_vjrantal/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/63998117be38304_More_tests_vjrantal/thali08_motorola-Nexus 6.md)



#### Test 63680118f1433de Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-03-22T14:40:07.411Z - info: listening on *:3000

2016-03-22T14:40:11.720Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:0

2016-03-22T14:40:12.379Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:1

2016-03-22T14:40:12.820Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:2

2016-03-22T14:40:20.716Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:3

2016-03-22T14:40:31.211Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:4

2016-03-22T14:40:31.212Z - info: Required number of android devices presented (3)

2016-03-22T14:40:31.217Z - info: Starting unit test run for platform: android

2016-03-22T14:40:32.090Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-22T14:40:33.571Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-22T14:40:34.705Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-22T14:40:35.755Z - info: Running on android test: 4. native server connections all up

2016-03-22T14:40:36.315Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-22T14:40:36.752Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-22T14:40:37.163Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-22T14:40:37.559Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-22T14:40:38.025Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-22T14:40:38.899Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-22T14:40:39.301Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-22T14:40:39.767Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-22T14:40:40.163Z - info: Running on android test: 13. closeAll with promise

2016-03-22T14:40:40.627Z - info: Running on android test: 14. multiplex can send data

2016-03-22T14:40:41.069Z - info: Running on android test: 15. enqueue and run in order

2016-03-22T14:40:41.913Z - info: Running on android test: 16. enqueueAtTop and run backwards

2016-03-22T14:40:42.693Z - info: Running on android test: 17. mix enqueue and enqueueAtTop

2016-03-22T14:40:43.245Z - info: Running on android test: 18. queues handled independently

2016-03-22T14:40:43.629Z - info: Running on android test: 19. basic

2016-03-22T14:40:44.030Z - info: Running on android test: 20. another

2016-03-22T14:40:44.401Z - info: Running on android test: 21. can pass data in setup

2016-03-22T14:40:44.865Z - info: Running on android test: 22. #startListeningForAdvertisements should fail if start not called

2016-03-22T14:40:45.308Z - info: Running on android test: 23. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-22T14:40:45.746Z - info: Running on android test: 24. should be able to call #stopListeningForAdvertisements many times

2016-03-22T14:40:46.278Z - info: Running on android test: 25. should be able to call #startListeningForAdvertisements many times

2016-03-22T14:40:47.001Z - info: Running on android test: 26. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-22T14:40:48.187Z - info: Running on android test: 27. should be able to call #stopAdvertisingAndListening many times

2016-03-22T14:40:48.768Z - info: Running on android test: 28. #start should fail if called twice in a row

2016-03-22T14:40:49.336Z - info: Running on android test: 29. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-22T14:40:50.637Z - info: Running on android test: 30. does not send duplicate availability changes

2016-03-22T14:40:51.390Z - info: Running on android test: 31. can get the network status

2016-03-22T14:40:51.863Z - info: Running on android test: 32. wifi peer is marked unavailable if announcements stop

2016-03-22T14:40:53.328Z - info: Running on android test: 33. Can call start/stopListeningForAdvertisements

2016-03-22T14:40:53.806Z - info: Running on android test: 34. Calling startListeningForAdvertisements twice is NOT an error

2016-03-22T14:40:54.400Z - info: Running on android test: 35. Can call start/stopUpdateAdvertisingAndListening

2016-03-22T14:40:55.342Z - info: Running on android test: 36. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-22T14:40:56.437Z - info: Running on android test: 37. peerAvailabilityChange is called

2016-03-22T14:40:58.516Z - info: Running on android test: 38. Can connect to a remote peer

2016-03-22T14:41:10.884Z - info: Running on android test: 39. Can shift large amounts of data

2016-03-22T14:41:58.450Z - info: Running on android test: 40. #startListeningForAdvertisements should fail if start not called

2016-03-22T14:41:59.551Z - info: Running on android test: 41. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-22T14:41:59.975Z - info: Running on android test: 42. should be able to call #stopListeningForAdvertisements many times

2016-03-22T14:42:00.483Z - info: Running on android test: 43. should be able to call #startListeningForAdvertisements many times

2016-03-22T14:42:01.518Z - info: Running on android test: 44. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-22T14:42:03.479Z - info: Running on android test: 45. should be able to call #stopAdvertisingAndListening many times

2016-03-22T14:42:05.718Z - info: Running on android test: 46. can get the network status before starting

2016-03-22T14:42:06.514Z - info: Running on android test: 47. error returned with bad router

2016-03-22T14:42:07.330Z - info: Running on android test: 48. all services are stopped when we call stop

2016-03-22T14:42:08.060Z - info: Running on android test: 49. make sure terminateConnection is properly hooked up

2016-03-22T14:42:08.519Z - info: Running on android test: 50. make sure terminateListener is properly hooked up

2016-03-22T14:42:08.969Z - info: Running on android test: 51. make sure we actually call kill connections properly

2016-03-22T14:42:09.420Z - info: Running on android test: 52. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received

2016-03-22T14:42:09.917Z - info: Running on android test: 53. We repeat failedConnection event when we get it from thaliTcpServersManager

2016-03-22T14:42:10.352Z - info: Running on android test: 54. we successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-22T14:42:11.416Z - warn: Failed on android test: 54. we successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-22T14:42:11.417Z - info: Running on android test: 55. can do HTTP requests between peers

2016-03-22T14:42:22.014Z - info: Running on android test: 56. Test BEACONS_RETRIEVED_AND_PARSED locally

2016-03-22T14:42:23.072Z - info: Running on android test: 57. Test HTTP_BAD_RESPONSE locally

2016-03-22T14:42:23.581Z - info: Running on android test: 58. Test NETWORK_PROBLEM locally

2016-03-22T14:42:24.976Z - info: Running on android test: 59. Test timeout locally

2016-03-22T14:42:26.677Z - info: Running on android test: 60. Call the start two times

2016-03-22T14:42:27.194Z - info: Running on android test: 61. Call the kill before calling the start

2016-03-22T14:42:27.650Z - info: Running on android test: 62. Call the kill immediately after the start

2016-03-22T14:42:28.096Z - info: Running on android test: 63. Call the kill while waiting a response from the server

2016-03-22T14:42:30.603Z - info: Running on android test: 64. Test to exceed the max content size locally

2016-03-22T14:42:31.119Z - info: Running on android test: 65. Close the server socket while the client is waiting a response from the server. Local test.

2016-03-22T14:42:33.618Z - info: Running on android test: 66. Close the client socket while the client is waiting a response from the server. Local test.

2016-03-22T14:42:36.121Z - info: Running on android test: 67. #generatePreambleAndBeacons bad args

2016-03-22T14:42:36.592Z - info: Running on android test: 68. #generatePreambleAndBeacons empty keys to notify

2016-03-22T14:42:36.970Z - info: Running on android test: 69. #generatePreambleAndBeacons multiple keys to notify

2016-03-22T14:42:37.504Z - info: Running on android test: 70. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-22T14:42:37.905Z - info: Running on android test: 71. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-22T14:42:38.252Z - info: Running on android test: 72. #parseBeacons expiration out of range lower

2016-03-22T14:42:38.694Z - info: Running on android test: 73. #parseBeacons expiration out of range lower

2016-03-22T14:42:39.138Z - info: Running on android test: 74. #parseBeacons no beacons returns null

2016-03-22T14:42:39.644Z - info: Running on android test: 75. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-22T14:42:40.149Z - info: Running on android test: 76. #parseBeacons addressBookCallback fails decrypt

2016-03-22T14:42:44.385Z - info: Running on android test: 77. #parseBeacons addressBookCallback returns no matches

2016-03-22T14:42:45.526Z - info: Running on android test: 78. #parseBeacons addressBookCallback returns spurious match

2016-03-22T14:42:46.560Z - info: Running on android test: 79. #parseBeacons addressBookCallback returns public key

2016-03-22T14:42:47.059Z - info: Running on android test: 80. validate generatePskIdentityField

2016-03-22T14:42:47.561Z - info: Running on android test: 81. validate generatePskSecret

2016-03-22T14:42:47.958Z - info: Running on android test: 82. Start and stop ThaliNotificationServer

2016-03-22T14:42:48.471Z - info: Running on android test: 83. Pass an empty array to ThaliNotificationServer.start

2016-03-22T14:42:49.082Z - info: Running on android test: 84. Pass a string to ThaliNotificationServer.start

2016-03-22T14:42:49.567Z - info: Running on android test: 85. Pass an empty parameter to ThaliNotificationServer.start

2016-03-22T14:42:49.943Z - info: Running on android test: 86. Make an HTTP request to /NotificationBeacons

2016-03-22T14:42:50.464Z - info: Running on android test: 87. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-22T14:42:50.857Z - info: Running on android test: 88. Make an HTTP request to /NotificationBeaconsbefore calling start

2016-03-22T14:42:51.381Z - info: Running on android test: 89. #testThaliPeerAction - test getters

2016-03-22T14:42:51.719Z - info: Running on android test: 90. #testThaliPeerAction - start and kill

2016-03-22T14:42:52.036Z - info: Running on android test: 91. #testThaliPeerAction - double start

2016-03-22T14:42:52.390Z - info: Running on android test: 92. #testThaliPeerAction - start after kill

2016-03-22T14:42:52.706Z - info: Running on android test: 93. #testThaliPeerAction - make sure ids are unique

2016-03-22T14:42:53.126Z - info: Running on android test: 94. Test PeerConnectionInformation basics

2016-03-22T14:42:53.441Z - info: Running on android test: 95. Test PeerDictionary basic functionality

2016-03-22T14:42:53.744Z - info: Running on android test: 96. Test PeerDictionary with multiple entries.

2016-03-22T14:42:55.923Z - info: Running on android test: 97. RESOLVED entries are removed before WAITING state entry.

2016-03-22T14:42:57.235Z - info: Running on android test: 98. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-22T14:42:58.305Z - info: Running on android test: 99. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-22T14:43:00.075Z - info: Running on android test: 100. #ThaliPeerPoolInterface - bad enqueues

2016-03-22T14:43:00.507Z - info: Running on android test: 101. #ThaliPeerPoolInterface - do not allow same object type

2016-03-22T14:43:00.933Z - info: Running on android test: 102. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-22T14:43:01.929Z - info: Running on android test: 103. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent

2016-03-22T14:43:02.329Z - info: Running on android test: 104. compareBufferArrays

2016-03-22T14:43:02.757Z - info: Running on android test: 105. Call start twice and get error

2016-03-22T14:43:03.183Z - info: Running on android test: 106. Start and make sure it runs

2016-03-22T14:43:03.500Z - info: Running on android test: 107. Make sure getTimeWhenRun is right after start

2016-03-22T14:43:03.912Z - info: Running on android test: 108. Make sure getTimeWhenRun is -1 after function is called

2016-03-22T14:43:04.389Z - info: Running on android test: 109. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-22T14:43:04.751Z - info: Running on android test: 110. Test TransientState

2016-03-22T14:43:05.166Z - info: Running on android test: 111. No peers and empty database

2016-03-22T14:43:05.672Z - info: Running on android test: 112. One peer and empty DB

2016-03-22T14:43:06.251Z - info: Running on android test: 113. One peer with _Local set behind current seq

2016-03-22T14:43:06.730Z - info: Running on android test: 114. One peer with _Local set equal to current seq

2016-03-22T14:43:07.382Z - info: Running on android test: 115. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-22T14:43:08.124Z - info: Running on android test: 116. Three peers, one not in DB, one behind and one ahead

2016-03-22T14:43:11.346Z - info: Running on android test: 117. More than maximum peers, make sure we only send maximum allowed

2016-03-22T14:43:12.320Z - info: Running on android test: 118. two peers with empty DB, update the doc

2016-03-22T14:43:12.961Z - info: Running on android test: 119. add doc and make sure tokens refresh when they expire

2016-03-22T14:43:13.909Z - info: Running on android test: 120. start and stop and start and stop

2016-03-22T14:43:14.451Z - info: Running on android test: 121. two identical starts in a row

2016-03-22T14:43:14.931Z - info: Running on android test: 122. two different starts in a row

2016-03-22T14:43:15.404Z - info: Running on android test: 123. two stops and a start and two stops

2016-03-22T14:43:15.880Z - info: Running on android test: 124. we properly enqueue requests so no then needed

2016-03-22T14:43:16.393Z - info: Running on android test: 125. test calculateSeqPointKeyId

2016-03-22T14:43:16.848Z - info: Running on android test: 126. can create servers manager

2016-03-22T14:43:17.209Z - info: Running on android test: 127. calling stop without start causes error

2016-03-22T14:43:17.583Z - info: Running on android test: 128. can start/stop servers manager

2016-03-22T14:43:17.979Z - info: Running on android test: 129. starting twice resolves with listening port

2016-03-22T14:43:18.372Z - info: Running on android test: 130. terminateIncomingConnection will terminate a connection

2016-03-22T14:43:18.732Z - info: Running on android test: 131. terminate an Outgoing connection will terminate the server

2016-03-22T14:43:19.136Z - info: Running on android test: 132. terminate an Outgoing connection with wrong arguments is not harmful

2016-03-22T14:43:19.587Z - info: Running on android test: 133. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-22T14:43:19.965Z - info: Running on android test: 134. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-22T14:43:20.396Z - info: Running on android test: 135. messages with invalid location or USN should be ignored

2016-03-22T14:43:20.869Z - info: Running on android test: 136. verify that Thali-specific messages are filtered correctly

2016-03-22T14:43:21.368Z - info: Running on android test: 137. #startListeningForAdvertisements should fail if start not called

2016-03-22T14:43:21.851Z - info: Running on android test: 138. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-22T14:43:22.320Z - info: Running on android test: 139. #start should fail if called twice in a row

2016-03-22T14:43:22.690Z - info: Running on android test: 140. should not be started after stop is called

2016-03-22T14:43:23.030Z - info: Running on android test: 141. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-22T14:43:23.317Z - info: Running on android test: 142. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-22T14:43:23.722Z - info: Running on android test: 143. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-22T14:43:24.169Z - info: Running on android test: 144. #stop can be called multiple times in a row

2016-03-22T14:43:24.539Z - info: Running on android test: 145. #startListeningForAdvertisements can be called multiple times in a row

2016-03-22T14:43:24.949Z - info: Running on android test: 146. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-22T14:43:25.451Z - info: Running on android test: 147. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-22T14:43:25.952Z - info: Running on android test: 148. functions are run from a queue in the right order

2016-03-22T14:43:26.335Z - info: Running on android test: 149. #ThaliPeerPoolDefault - single action

2016-03-22T14:43:26.862Z - info: Running on android test: 150. #ThaliPeerPoolDefault - multiple actions

2016-03-22T14:43:27.260Z - info: Test run on android complete

2016-03-22T14:43:27.262Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-22T14:43:27.265Z - info: PLATFORM: android

2016-03-22T14:43:27.266Z - info: RESULT: FAIL

2016-03-22T14:43:27.267Z - info: 150 of 150 tests completed

2016-03-22T14:43:27.267Z - info: 149/150 passed (1 failures)

2016-03-22T14:43:27.268Z - info: 

--- Failed tests ---

2016-03-22T14:43:27.269Z - warn: 54. we successfully receive and replay discoveryAdvertisingStateUpdate - fail

2016-03-22T14:43:27.270Z - info: 

-== END ==-

2016-03-22T14:43:27.998Z - debug: Socket disconnected: transport close 4 (motorola-Nexus 6)

2016-03-22T14:43:28.028Z - debug: Socket disconnected: transport close 0 (LGE-LG-H815)

2016-03-22T14:43:28.184Z - debug: Socket disconnected: transport close 3 (samsung-SM-N910C)

2016-03-22T14:56:19.617Z - debug: Socket disconnected: ping timeout 1 (Apple-Iphone5-1)

2016-03-22T14:56:19.650Z - debug: Socket disconnected: ping timeout 2 (Apple-Iphone5s-1)


 
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
ios: child process exited with code 254 on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
true

```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/63680118f1433de_Support_passing_data_in_coordinated_tests_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/63680118f1433de_Support_passing_data_in_coordinated_tests_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/63680118f1433de_Support_passing_data_in_coordinated_tests_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/63680118f1433de_Support_passing_data_in_coordinated_tests_vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/63680118f1433de_Support_passing_data_in_coordinated_tests_vjrantal/iOS_server.md)




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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/63680118f1433de_Support_passing_data_in_coordinated_tests_vjrantal/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/63680118f1433de_Support_passing_data_in_coordinated_tests_vjrantal/thali07_LGE-LG-H815.md)

####Node name: thali08
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Device test finished on ZX1G429CRK 
Android task is completed. [SUCCESS]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/63680118f1433de_Support_passing_data_in_coordinated_tests_vjrantal/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/63680118f1433de_Support_passing_data_in_coordinated_tests_vjrantal/thali08_motorola-Nexus 6.md)



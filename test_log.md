#### Test 797510159390029 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":4}}
2016-08-10T06:50:03.823Z - info: Require NaN ios devices

2016-08-10T06:50:03.842Z - info: Require 4 android devices

2016-08-10T06:50:03.899Z - info: listening on *:3000

2016-08-10T06:50:05.668Z - debug: Device presented: motorola-Nexus 6 (e364418c-7fde-485f-aae3-c7909e9b3631) - android 6.0.1

2016-08-10T06:50:06.003Z - debug: Device presented: samsung-SM-G900F (96be7c43-4f22-4c7f-ae0b-534d82c3b29d) - android 6.0.1

2016-08-10T06:50:06.616Z - debug: Device presented: motorola-Nexus 6 (e364418c-7fde-485f-aae3-c7909e9b3631) - android 6.0.1

2016-08-10T06:50:06.617Z - info: Updating existing device: motorola-Nexus 6 (e364418c-7fde-485f-aae3-c7909e9b3631)

2016-08-10T06:50:06.999Z - debug: Device presented: samsung-SM-G900F (96be7c43-4f22-4c7f-ae0b-534d82c3b29d) - android 6.0.1

2016-08-10T06:50:07.000Z - info: Updating existing device: samsung-SM-G900F (96be7c43-4f22-4c7f-ae0b-534d82c3b29d)

2016-08-10T06:50:48.587Z - debug: Device presented: LGE-LG-D855 (44f4241d-cc9e-4bf9-bc8d-ad03e4241835) - android 5.0

2016-08-10T06:51:05.311Z - debug: Device presented: LGE-LG-D722 (d7e3e9cf-2b84-491f-9b8a-af1b8684ce52) - android 5.0.2

2016-08-10T06:51:05.313Z - info: All 4 android devices are present

2016-08-10T06:51:05.315Z - info: Disqualifying device with unsupported hardware: LGE-LG-D855

2016-08-10T06:51:05.322Z - info: Disqualifying device with unsupported hardware: LGE-LG-D722

2016-08-10T06:51:05.330Z - info: Starting unit test run on 2 android devices

2016-08-10T06:51:06.340Z - info: Socket to device LGE-LG-D855 disconnected: transport close

2016-08-10T06:51:06.361Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-08-10T06:51:06.548Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-10T06:51:06.812Z - info: Running on android test: 2. emits incomingConnectionState

2016-08-10T06:51:07.196Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-08-10T06:51:07.507Z - info: Running on android test: 4. native server connections all up

2016-08-10T06:51:07.813Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-08-10T06:51:08.123Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-08-10T06:51:08.431Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-08-10T06:51:08.796Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-08-10T06:51:09.093Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-08-10T06:51:11.085Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-08-10T06:51:11.439Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-08-10T06:51:11.703Z - info: Running on android test: 12. #_doImmediateSeqUpdate - server is not there

2016-08-10T06:51:12.099Z - info: Running on android test: 13. #_doImmediateSeqUpdate - server accepts & closes connection

2016-08-10T06:51:12.365Z - info: Running on android test: 14. #_doImmediateSeqUpdate - server always returns 500

2016-08-10T06:51:12.715Z - info: Running on android test: 15. #_doImmediateSeqUpdate - create new seq doc

2016-08-10T06:51:14.854Z - info: Running on android test: 16. #_doImmediateSeqUpdate - doc exists, need to get rev and update

2016-08-10T06:51:15.720Z - info: Running on android test: 17. #_doImmediateSeqUpdate - update seq three times

2016-08-10T06:51:17.919Z - info: Running on android test: 18. #_doImmediateSeqUpdate - rev got changed under us

2016-08-10T06:51:19.029Z - info: Running on android test: 19. #_doImmediateSeqUpdate - fail if stop is called

2016-08-10T06:51:19.554Z - info: Running on android test: 20. #_doImmediateSeqUpdate - stop after get but before put fails right

2016-08-10T06:51:20.077Z - info: Running on android test: 21. #update - fail if stop is called

2016-08-10T06:51:20.382Z - info: Running on android test: 22. #update - set seq for first time

2016-08-10T06:51:21.203Z - info: Running on android test: 23. #update - Fail on bad seq value

2016-08-10T06:51:21.847Z - info: Running on android test: 24. #update - do we cancel timer properly on an immediate?

2016-08-10T06:51:22.675Z - info: Running on android test: 25. #update - do we wait for blocked update

2016-08-10T06:51:23.393Z - info: Running on android test: 26. #update - test that we wait long enough

2016-08-10T06:51:25.202Z - info: Running on android test: 27. #update - test that we pick up new sequences while we wait

2016-08-10T06:51:26.736Z - info: Running on android test: 28. Coordinated seq test

2016-08-10T06:56:27.303Z - warn: Failed on android test: 28. Coordinated seq test

2016-08-10T06:56:27.304Z - info: Running on android test: 29. closeAll can close even when connections open

2016-08-10T06:56:27.694Z - info: Running on android test: 30. closeAll with promise

2016-08-10T06:56:28.036Z - info: Running on android test: 31. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-08-10T06:56:28.348Z - info: Running on android test: 32. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-08-10T06:56:28.742Z - info: Running on android test: 33. enqueue and run in order

2016-08-10T06:56:29.231Z - info: Running on android test: 34. enqueueAtTop and run backwards

2016-08-10T06:56:29.452Z - info: Running on android test: 35. mix enqueue and enqueueAtTop

2016-08-10T06:56:29.797Z - info: Running on android test: 36. queues handled independently

2016-08-10T06:56:30.024Z - info: Running on android test: 37. basic

2016-08-10T06:56:30.250Z - info: Running on android test: 38. another

2016-08-10T06:56:30.423Z - info: Running on android test: 39. can pass data in setup

2016-08-10T06:56:30.612Z - info: Running on android test: 40. #startListeningForAdvertisements should fail if start not called

2016-08-10T06:56:30.801Z - info: Running on android test: 41. #startUpdateAdvertisingAndListening should fail if start not called

2016-08-10T06:56:31.079Z - info: Running on android test: 42. should be able to call #stopListeningForAdvertisements many times

2016-08-10T06:56:31.352Z - info: Running on android test: 43. should be able to call #startListeningForAdvertisements many times

2016-08-10T06:56:32.986Z - info: Running on android test: 44. should be able to call #startUpdateAdvertisingAndListening many times

2016-08-10T06:56:34.399Z - info: Running on android test: 45. should be able to call #stopAdvertisingAndListening many times

2016-08-10T06:56:35.847Z - info: Running on android test: 46. #start should fail if called twice in a row

2016-08-10T06:56:36.101Z - info: Running on android test: 47. does not emit duplicate discoveryAdvertisingStateUpdate

2016-08-10T06:56:38.074Z - info: Running on android test: 48. does not send duplicate availability changes

2016-08-10T06:56:38.262Z - info: Running on android test: 49. can get the network status

2016-08-10T06:56:38.458Z - info: Running on android test: 50. wifi peer is marked unavailable if announcements stop

2016-08-10T06:56:40.737Z - info: Running on android test: 51. Can call start/stopListeningForAdvertisements

2016-08-10T06:56:42.356Z - info: Running on android test: 52. Client to server request coordinated

2016-08-10T06:58:48.648Z - warn: Failed on android test: 52. Client to server request coordinated

2016-08-10T06:58:48.649Z - info: Running on android test: 53. Test BEACONS_RETRIEVED_AND_PARSED locally

2016-08-10T06:58:49.419Z - info: Running on android test: 54. Test HTTP_BAD_RESPONSE locally

2016-08-10T06:58:49.776Z - info: Running on android test: 55. Test NETWORK_PROBLEM locally

2016-08-10T06:58:50.155Z - info: Running on android test: 56. Call the start two times

2016-08-10T06:58:50.629Z - info: Running on android test: 57. Call the kill before calling the start

2016-08-10T06:58:50.965Z - info: Running on android test: 58. Call the kill immediately after the start

2016-08-10T06:58:51.290Z - info: Running on android test: 59. Call the kill while waiting a response from the server

2016-08-10T06:58:53.659Z - info: Running on android test: 60. Test to exceed the max content size locally

2016-08-10T06:58:54.106Z - info: Running on android test: 61. Close the server socket while the client is waiting a response from the server. Local test.

2016-08-10T06:58:56.496Z - info: Running on android test: 62. Close the client socket while the client is waiting a response from the server. Local test.

2016-08-10T06:58:58.863Z - info: Running on android test: 63. #generatePreambleAndBeacons bad args

2016-08-10T06:58:59.093Z - info: Running on android test: 64. #generatePreambleAndBeacons empty keys to notify

2016-08-10T06:58:59.287Z - info: Running on android test: 65. #generatePreambleAndBeacons multiple keys to notify

2016-08-10T06:58:59.588Z - info: Running on android test: 66. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-08-10T06:58:59.781Z - info: Running on android test: 67. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-08-10T06:59:00.029Z - info: Running on android test: 68. #parseBeacons expiration out of range lower

2016-08-10T06:59:00.256Z - info: Running on android test: 69. #parseBeacons expiration out of range lower

2016-08-10T06:59:00.513Z - info: Running on android test: 70. #parseBeacons no beacons returns null

2016-08-10T06:59:02.044Z - info: Running on android test: 71. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-08-10T06:59:02.418Z - info: Running on android test: 72. #parseBeacons addressBookCallback fails decrypt

2016-08-10T06:59:02.761Z - info: Running on android test: 73. #parseBeacons addressBookCallback returns no matches

2016-08-10T06:59:03.122Z - info: Running on android test: 74. #parseBeacons addressBookCallback returns spurious match

2016-08-10T06:59:03.511Z - info: Running on android test: 75. #parseBeacons addressBookCallback returns public key

2016-08-10T06:59:03.875Z - info: Running on android test: 76. validate generatePskIdentityField

2016-08-10T06:59:04.042Z - info: Running on android test: 77. validate generatePskSecret

2016-08-10T06:59:04.273Z - info: Running on android test: 78. validate generatePskSecrets

2016-08-10T06:59:04.699Z - info: Running on android test: 79. validate generateBeaconStreamAndSecrets

2016-08-10T06:59:04.983Z - info: Running on android test: 80. Add two Peers.

2016-08-10T06:59:05.225Z - info: Running on android test: 81. TCP_NATIVE peer loses DNS

2016-08-10T06:59:05.529Z - info: Running on android test: 82. Received beacons with no values for us

2016-08-10T06:59:05.969Z - info: Running on android test: 83. Resolves an action locally

2016-08-10T06:59:06.445Z - info: Running on android test: 84. Resolves an action locally using ThaliPeerPoolDefault

2016-08-10T06:59:06.885Z - info: Running on android test: 85. Action fails because of a bad hostname.

2016-08-10T06:59:12.217Z - info: Running on android test: 86. hostaddress is removed when the action is running. 

2016-08-10T06:59:14.619Z - info: Running on android test: 87. Client to server request locally

2016-08-10T06:59:15.092Z - info: Running on android test: 88. Test ThaliPskMapCache clean and expiration

2016-08-10T06:59:16.372Z - info: Running on android test: 89. Test ThaliPskMapCache getSecret and getPublic

2016-08-10T06:59:17.805Z - info: Running on android test: 90. Test ThaliPskMapCache multiple entries

2016-08-10T06:59:20.682Z - info: Running on android test: 91. Start and stop ThaliNotificationServer

2016-08-10T06:59:21.026Z - info: Running on android test: 92. Pass an empty array to ThaliNotificationServer.start

2016-08-10T06:59:21.290Z - info: Running on android test: 93. Pass a string to ThaliNotificationServer.start

2016-08-10T06:59:21.512Z - info: Running on android test: 94. Pass an empty parameter to ThaliNotificationServer.start

2016-08-10T06:59:21.786Z - info: Running on android test: 95. Make an HTTP request to /NotificationBeacons

2016-08-10T06:59:22.208Z - info: Running on android test: 96. Make an HTTP request to /NotificationBeacons (no keys)

2016-08-10T06:59:22.449Z - info: Running on android test: 97. Make an HTTP request to /NotificationBeaconsbefore calling start

2016-08-10T06:59:22.683Z - info: Running on android test: 98. #testThaliPeerAction - test getters

2016-08-10T06:59:22.834Z - info: Running on android test: 99. #testThaliPeerAction - start and kill

2016-08-10T06:59:22.997Z - info: Running on android test: 100. #testThaliPeerAction - double start

2016-08-10T06:59:23.159Z - info: Running on android test: 101. #testThaliPeerAction - start after kill

2016-08-10T06:59:23.313Z - info: Running on android test: 102. #testThaliPeerAction - make sure ids are unique

2016-08-10T06:59:23.508Z - info: Running on android test: 103. Test PeerConnectionInformation basics

2016-08-10T06:59:23.705Z - info: Running on android test: 104. Test PeerDictionary basic functionality

2016-08-10T06:59:23.945Z - info: Running on android test: 105. Test PeerDictionary with multiple entries.

2016-08-10T06:59:25.779Z - info: Running on android test: 106. RESOLVED entries are removed before WAITING state entry.

2016-08-10T06:59:26.677Z - info: Running on android test: 107. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-08-10T06:59:27.500Z - info: Running on android test: 108. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-08-10T06:59:28.290Z - info: Running on android test: 109. #ThaliPeerPoolInterface - bad enqueues

2016-08-10T06:59:28.426Z - info: Running on android test: 110. #ThaliPeerPoolInterface - do not allow same object type

2016-08-10T06:59:28.637Z - info: Running on android test: 111. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-08-10T06:59:28.846Z - info: Running on android test: 112. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent

2016-08-10T06:59:29.028Z - info: Running on android test: 113. Make sure peerDictionaryKey is reasonable

2016-08-10T06:59:29.223Z - info: Running on android test: 114. Make sure start works

2016-08-10T06:59:29.437Z - info: Running on android test: 115. Make sure stop works

2016-08-10T06:59:29.645Z - info: Running on android test: 116. Simple peer event

2016-08-10T06:59:29.876Z - info: Running on android test: 117. Coordinated pull replication from notification test

2016-08-10T07:04:30.576Z - warn: Failed on android test: 117. Coordinated pull replication from notification test

2016-08-10T07:04:30.577Z - info: Running on android test: 118. Server is not there

2016-08-10T07:04:30.998Z - info: Running on android test: 119. Server accepts & closes connection

2016-08-10T07:04:31.316Z - info: Running on android test: 120. Server always returns 500

2016-08-10T07:04:31.962Z - info: Running on android test: 121. Server always returns 401

2016-08-10T07:04:32.305Z - info: Running on android test: 122. Server always returns 403

2016-08-10T07:04:32.614Z - info: Running on android test: 123. Make sure docs replicate

2016-08-10T07:04:34.550Z - info: Running on android test: 124. Do nothing and make sure we time out

2016-08-10T07:04:36.947Z - info: Running on android test: 125. Do something and make sure we time out

2016-08-10T07:04:40.542Z - info: Running on android test: 126. Start replicating and then catch error when server goes

2016-08-10T07:04:41.382Z - info: Running on android test: 127. compareBufferArrays

2016-08-10T07:04:41.499Z - info: Running on android test: 128. Call start twice and get error

2016-08-10T07:04:41.622Z - info: Running on android test: 129. Start and make sure it runs

2016-08-10T07:04:41.788Z - info: Running on android test: 130. Make sure getTimeWhenRun is right after start

2016-08-10T07:04:41.961Z - info: Running on android test: 131. Make sure getTimeWhenRun is -1 after function is called

2016-08-10T07:04:42.125Z - info: Running on android test: 132. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-08-10T07:04:42.331Z - info: Running on android test: 133. Test TransientState

2016-08-10T07:04:42.611Z - info: Running on android test: 134. No peers and empty database

2016-08-10T07:04:42.968Z - info: Running on android test: 135. One peer and empty DB

2016-08-10T07:04:43.302Z - info: Running on android test: 136. One peer with _Local set behind current seq

2016-08-10T07:04:43.692Z - info: Running on android test: 137. One peer with _Local set equal to current seq

2016-08-10T07:04:44.066Z - info: Running on android test: 138. One peer with _Local set ahead of current seq (and no this should not happen)

2016-08-10T07:04:44.413Z - info: Running on android test: 139. Three peers, one not in DB, one behind and one ahead

2016-08-10T07:04:44.863Z - info: Running on android test: 140. More than maximum peers, make sure we only send maximum allowed

2016-08-10T07:04:45.785Z - info: Running on android test: 141. two peers with empty DB, update the doc

2016-08-10T07:04:46.143Z - info: Running on android test: 142. add doc and make sure tokens refresh when they expire

2016-08-10T07:04:46.779Z - info: Running on android test: 143. start and stop and start and stop

2016-08-10T07:04:47.141Z - info: Running on android test: 144. two identical starts in a row

2016-08-10T07:04:47.541Z - info: Running on android test: 145. two different starts in a row

2016-08-10T07:04:47.910Z - info: Running on android test: 146. two stops and a start and two stops

2016-08-10T07:04:48.277Z - info: Running on android test: 147. we properly enqueue requests so no then needed

2016-08-10T07:04:48.674Z - info: Running on android test: 148. test calculateSeqPointKeyId

2016-08-10T07:04:48.869Z - info: Running on android test: 149. can create servers manager

2016-08-10T07:04:49.019Z - info: Running on android test: 150. calling stop without start causes error

2016-08-10T07:04:49.185Z - info: Running on android test: 151. can start/stop servers manager

2016-08-10T07:04:49.343Z - info: Running on android test: 152. starting twice resolves with listening port

2016-08-10T07:04:49.510Z - info: Running on android test: 153. terminateIncomingConnection will terminate a connection

2016-08-10T07:04:49.719Z - info: Running on android test: 154. terminate an Outgoing connection will terminate the server

2016-08-10T07:04:49.883Z - info: Running on android test: 155. terminate an Outgoing connection with wrong arguments is not harmful

2016-08-10T07:04:50.110Z - info: Running on android test: 156. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-08-10T07:04:50.415Z - info: Running on android test: 157. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-08-10T07:04:50.687Z - info: Running on android test: 158. messages with invalid location or USN should be ignored

2016-08-10T07:04:50.890Z - info: Running on android test: 159. verify that Thali-specific messages are filtered correctly

2016-08-10T07:04:51.070Z - info: Running on android test: 160. #startListeningForAdvertisements should fail if start not called

2016-08-10T07:04:51.271Z - info: Running on android test: 161. #startUpdateAdvertisingAndListening should fail if start not called

2016-08-10T07:04:51.553Z - info: Running on android test: 162. #start should fail if called twice in a row

2016-08-10T07:04:51.773Z - info: Running on android test: 163. should not be started after stop is called

2016-08-10T07:04:51.949Z - info: Running on android test: 164. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-08-10T07:04:52.146Z - info: Running on android test: 165. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-08-10T07:04:52.346Z - info: Running on android test: 166. #startUpdateAdvertisingAndListening should start hosting given router object

2016-08-10T07:04:52.697Z - info: Running on android test: 167. #startUpdateAdvertisingAndListening bad psk should be rejected object

2016-08-10T07:04:52.972Z - info: Running on android test: 168. #stop can be called multiple times in a row

2016-08-10T07:04:53.180Z - info: Running on android test: 169. #startListeningForAdvertisements can be called multiple times in a row

2016-08-10T07:04:53.385Z - info: Running on android test: 170. #stopListeningForAdvertisements can be called multiple times in a row

2016-08-10T07:04:53.615Z - info: Running on android test: 171. #stopAdvertisingAndListening can be called multiple times in a row

2016-08-10T07:04:53.804Z - info: Running on android test: 172. functions are run from a queue in the right order

2016-08-10T07:04:54.033Z - info: Running on android test: 173. does not get peer changes from self

2016-08-10T07:04:56.302Z - info: Running on android test: 174. #ThaliPeerPoolDefault - single action

2016-08-10T07:04:56.547Z - info: Running on android test: 175. #ThaliPeerPoolDefault - multiple actions

2016-08-10T07:04:56.747Z - info: Running on android test: 176. #ThaliPeerPoolDefault - PSK Pool works

2016-08-10T07:04:57.054Z - info: Running on android test: 177. #ThaliPeerPoolDefault - stop

2016-08-10T07:04:57.223Z - info: Test run on android complete

2016-08-10T07:04:57.226Z - info: 

-== UNIT TEST RESULTS ==-

2016-08-10T07:04:57.228Z - info: PLATFORM: android

2016-08-10T07:04:57.229Z - info: RESULT: FAIL

2016-08-10T07:04:57.230Z - info: 177 of 177 tests completed

2016-08-10T07:04:57.231Z - info: 174/177 passed (3 failures)

2016-08-10T07:04:57.232Z - info: 

--- Failed tests ---

2016-08-10T07:04:57.234Z - warn: 28. Coordinated seq test - fail

2016-08-10T07:04:57.235Z - warn: 52. Client to server request coordinated - fail

2016-08-10T07:04:57.236Z - warn: 117. Coordinated pull replication from notification test - fail

2016-08-10T07:04:57.237Z - info: 

-== END ==-

2016-08-10T07:04:58.217Z - info: Socket to device motorola-Nexus 6 disconnected: transport close

2016-08-10T07:04:59.191Z - info: Socket to device samsung-SM-G900F disconnected: transport close


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###Android Logs
####Node name: thali01
Console output:
```

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
STOP log received from  ZX1G429CRK Test has  FAILED
STOP log received from  0be0c6c6 Test has  FAILED
Device test finished on ZX1G429CRK 
Device test finished on 0be0c6c6 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/797510159390029_Check_811_failures_in_CI_do_not_merge__czyzm/thali01_motorola-Nexus 6.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/797510159390029_Check_811_failures_in_CI_do_not_merge__czyzm/thali01_samsung-SM-G900F.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  LGD855a6933058 Test has  SUCCEEDED
Device test finished on LGD855a6933058 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/797510159390029_Check_811_failures_in_CI_do_not_merge__czyzm/thali02_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/797510159390029_Check_811_failures_in_CI_do_not_merge__czyzm/thali02_LGE-LG-D855.md)





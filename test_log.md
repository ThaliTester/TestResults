#### Test 79689775403ec48 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-08-09T15:22:43.044Z - info: Require 3 ios devices

2016-08-09T15:22:43.063Z - info: Require 3 android devices

2016-08-09T15:22:43.120Z - info: listening on *:3000

2016-08-09T15:24:23.958Z - debug: Device presented: LGE-LG-D855 (82d23e8e-2828-4733-b895-997251996aa1) - android 5.0

2016-08-09T15:24:33.966Z - debug: Device presented: samsung-SM-G900F (c000eb49-89e0-4e30-8625-8f7f358c755e) - android 6.0.1

2016-08-09T15:24:37.478Z - debug: Device presented: LGE-LG-D722 (7720274a-0604-4153-b1be-7e21a5d5af75) - android 5.0.2

2016-08-09T15:24:37.479Z - info: All 3 android devices are present

2016-08-09T15:24:37.481Z - info: Disqualifying device with unsupported hardware: LGE-LG-D855

2016-08-09T15:24:37.488Z - info: Disqualifying device with unsupported hardware: LGE-LG-D722

2016-08-09T15:24:37.495Z - info: Starting unit test run on 1 android devices

2016-08-09T15:24:38.451Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-09T15:24:38.600Z - info: Socket to device LGE-LG-D855 disconnected: transport close

2016-08-09T15:24:38.731Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-08-09T15:24:38.858Z - info: Running on android test: 2. emits incomingConnectionState

2016-08-09T15:24:39.031Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-08-09T15:24:39.189Z - info: Running on android test: 4. native server connections all up

2016-08-09T15:24:39.391Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-08-09T15:24:39.612Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-08-09T15:24:39.859Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-08-09T15:24:40.180Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-08-09T15:24:40.395Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-08-09T15:24:42.380Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-08-09T15:24:42.694Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-08-09T15:24:42.942Z - info: Running on android test: 12. #_doImmediateSeqUpdate - server is not there

2016-08-09T15:24:43.241Z - info: Running on android test: 13. #_doImmediateSeqUpdate - server accepts & closes connection

2016-08-09T15:24:43.495Z - info: Running on android test: 14. #_doImmediateSeqUpdate - server always returns 500

2016-08-09T15:24:43.769Z - info: Running on android test: 15. #_doImmediateSeqUpdate - create new seq doc

2016-08-09T15:24:45.868Z - info: Running on android test: 16. #_doImmediateSeqUpdate - doc exists, need to get rev and update

2016-08-09T15:24:46.588Z - info: Running on android test: 17. #_doImmediateSeqUpdate - update seq three times

2016-08-09T15:24:47.682Z - info: Running on android test: 18. #_doImmediateSeqUpdate - rev got changed under us

2016-08-09T15:24:48.505Z - info: Running on android test: 19. #_doImmediateSeqUpdate - fail if stop is called

2016-08-09T15:24:48.755Z - info: Running on android test: 20. #_doImmediateSeqUpdate - stop after get but before put fails right

2016-08-09T15:24:49.195Z - info: Running on android test: 21. #update - fail if stop is called

2016-08-09T15:24:49.451Z - info: Running on android test: 22. #update - set seq for first time

2016-08-09T15:24:50.088Z - info: Running on android test: 23. #update - Fail on bad seq value

2016-08-09T15:24:50.594Z - info: Running on android test: 24. #update - do we cancel timer properly on an immediate?

2016-08-09T15:24:51.334Z - info: Running on android test: 25. #update - do we wait for blocked update

2016-08-09T15:24:51.943Z - info: Running on android test: 26. #update - test that we wait long enough

2016-08-09T15:24:53.521Z - info: Running on android test: 27. #update - test that we pick up new sequences while we wait

2016-08-09T15:24:55.063Z - info: Running on android test: 28. Coordinated seq test

2016-08-09T15:29:55.455Z - warn: Failed on android test: 28. Coordinated seq test

2016-08-09T15:29:55.456Z - info: Running on android test: 29. closeAll can close even when connections open

2016-08-09T15:29:55.798Z - info: Running on android test: 30. closeAll with promise

2016-08-09T15:29:56.137Z - info: Running on android test: 31. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-08-09T15:29:56.477Z - info: Running on android test: 32. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-08-09T15:29:56.798Z - info: Running on android test: 33. onPeerLost calls jxcore

2016-08-09T15:29:59.196Z - info: Running on android test: 34. onPeerDiscovered calls jxcore

2016-08-09T15:30:01.534Z - info: Running on android test: 35. enqueue and run in order

2016-08-09T15:30:01.960Z - info: Running on android test: 36. enqueueAtTop and run backwards

2016-08-09T15:30:02.158Z - info: Running on android test: 37. mix enqueue and enqueueAtTop

2016-08-09T15:30:02.477Z - info: Running on android test: 38. queues handled independently

2016-08-09T15:30:02.709Z - info: Running on android test: 39. basic

2016-08-09T15:30:02.889Z - info: Running on android test: 40. another

2016-08-09T15:30:03.079Z - info: Running on android test: 41. can pass data in setup

2016-08-09T15:30:03.281Z - info: Running on android test: 42. #startListeningForAdvertisements should fail if start not called

2016-08-09T15:30:03.459Z - info: Running on android test: 43. #startUpdateAdvertisingAndListening should fail if start not called

2016-08-09T15:30:03.659Z - info: Running on android test: 44. should be able to call #stopListeningForAdvertisements many times

2016-08-09T15:30:03.884Z - info: Running on android test: 45. should be able to call #startListeningForAdvertisements many times

2016-08-09T15:30:05.526Z - info: Running on android test: 46. should be able to call #startUpdateAdvertisingAndListening many times

2016-08-09T15:30:06.795Z - info: Running on android test: 47. should be able to call #stopAdvertisingAndListening many times

2016-08-09T15:30:06.938Z - info: Running on android test: 48. #start should fail if called twice in a row

2016-08-09T15:30:07.124Z - info: Running on android test: 49. does not emit duplicate discoveryAdvertisingStateUpdate

2016-08-09T15:30:08.392Z - info: Running on android test: 50. does not send duplicate availability changes

2016-08-09T15:30:08.534Z - info: Running on android test: 51. can get the network status

2016-08-09T15:30:08.688Z - info: Running on android test: 52. wifi peer is marked unavailable if announcements stop

2016-08-09T15:30:10.969Z - info: Running on android test: 53. Can call start/stopListeningForAdvertisements

2016-08-09T15:30:12.546Z - info: Running on android test: 54. Calling startListeningForAdvertisements twice is NOT an error

2016-08-09T15:30:14.119Z - info: Running on android test: 55. Calling stopListeningForAdvertisements without calling start is NOT an error

2016-08-09T15:30:14.334Z - info: Running on android test: 56. Can call start/stopUpdateAdvertisingAndListening

2016-08-09T15:30:15.328Z - info: Running on android test: 57. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-08-09T15:30:16.480Z - info: Running on android test: 58. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error

2016-08-09T15:30:16.626Z - info: Running on android test: 59. cannot call connect when start listening for advertisements is not active

2016-08-09T15:30:16.965Z - info: Running on android test: 60. Client to server request coordinated

2016-08-09T15:30:17.170Z - info: Running on android test: 61. Test BEACONS_RETRIEVED_AND_PARSED locally

2016-08-09T15:30:17.568Z - info: Running on android test: 62. Test HTTP_BAD_RESPONSE locally

2016-08-09T15:30:17.868Z - info: Running on android test: 63. Test NETWORK_PROBLEM locally

2016-08-09T15:30:18.307Z - info: Running on android test: 64. Call the start two times

2016-08-09T15:30:19.160Z - info: Running on android test: 65. Call the kill before calling the start

2016-08-09T15:30:19.313Z - info: Running on android test: 66. Call the kill immediately after the start

2016-08-09T15:30:19.493Z - info: Running on android test: 67. Call the kill while waiting a response from the server

2016-08-09T15:30:21.759Z - info: Running on android test: 68. Test to exceed the max content size locally

2016-08-09T15:30:22.133Z - info: Running on android test: 69. Close the server socket while the client is waiting a response from the server. Local test.

2016-08-09T15:30:24.535Z - info: Running on android test: 70. Close the client socket while the client is waiting a response from the server. Local test.

2016-08-09T15:30:26.892Z - info: Running on android test: 71. #generatePreambleAndBeacons bad args

2016-08-09T15:30:27.099Z - info: Running on android test: 72. #generatePreambleAndBeacons empty keys to notify

2016-08-09T15:30:27.308Z - info: Running on android test: 73. #generatePreambleAndBeacons multiple keys to notify

2016-08-09T15:30:27.633Z - info: Running on android test: 74. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-08-09T15:30:28.530Z - info: Running on android test: 75. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-08-09T15:30:28.730Z - info: Running on android test: 76. #parseBeacons expiration out of range lower

2016-08-09T15:30:28.930Z - info: Running on android test: 77. #parseBeacons expiration out of range lower

2016-08-09T15:30:30.053Z - info: Running on android test: 78. #parseBeacons no beacons returns null

2016-08-09T15:30:30.151Z - info: Running on android test: 79. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-08-09T15:30:30.331Z - info: Running on android test: 80. #parseBeacons addressBookCallback fails decrypt

2016-08-09T15:30:30.654Z - info: Running on android test: 81. #parseBeacons addressBookCallback returns no matches

2016-08-09T15:30:30.929Z - info: Running on android test: 82. #parseBeacons addressBookCallback returns spurious match

2016-08-09T15:30:31.250Z - info: Running on android test: 83. #parseBeacons addressBookCallback returns public key

2016-08-09T15:30:31.567Z - info: Running on android test: 84. validate generatePskIdentityField

2016-08-09T15:30:31.702Z - info: Running on android test: 85. validate generatePskSecret

2016-08-09T15:30:31.901Z - info: Running on android test: 86. validate generatePskSecrets

2016-08-09T15:30:32.245Z - info: Running on android test: 87. validate generateBeaconStreamAndSecrets

2016-08-09T15:30:32.496Z - info: Running on android test: 88. Add two Peers.

2016-08-09T15:30:32.746Z - info: Running on android test: 89. TCP_NATIVE peer loses DNS

2016-08-09T15:30:33.496Z - info: Running on android test: 90. Received beacons with no values for us

2016-08-09T15:30:33.880Z - info: Running on android test: 91. Resolves an action locally

2016-08-09T15:30:34.332Z - info: Running on android test: 92. Resolves an action locally using ThaliPeerPoolDefault

2016-08-09T15:30:34.780Z - info: Running on android test: 93. Action fails because of a bad hostname.

2016-08-09T15:30:40.108Z - info: Running on android test: 94. hostaddress is removed when the action is running. 

2016-08-09T15:30:42.478Z - info: Running on android test: 95. Client to server request locally

2016-08-09T15:30:42.887Z - info: Running on android test: 96. Test ThaliPskMapCache clean and expiration

2016-08-09T15:30:44.124Z - info: Running on android test: 97. Test ThaliPskMapCache getSecret and getPublic

2016-08-09T15:30:45.508Z - info: Running on android test: 98. Test ThaliPskMapCache multiple entries

2016-08-09T15:30:48.432Z - info: Running on android test: 99. Start and stop ThaliNotificationServer

2016-08-09T15:30:48.762Z - info: Running on android test: 100. Pass an empty array to ThaliNotificationServer.start

2016-08-09T15:30:49.053Z - info: Running on android test: 101. Pass a string to ThaliNotificationServer.start

2016-08-09T15:30:49.246Z - info: Running on android test: 102. Pass an empty parameter to ThaliNotificationServer.start

2016-08-09T15:30:49.428Z - info: Running on android test: 103. Make an HTTP request to /NotificationBeacons

2016-08-09T15:30:49.852Z - info: Running on android test: 104. Make an HTTP request to /NotificationBeacons (no keys)

2016-08-09T15:30:50.067Z - info: Running on android test: 105. Make an HTTP request to /NotificationBeaconsbefore calling start

2016-08-09T15:30:50.342Z - info: Running on android test: 106. #testThaliPeerAction - test getters

2016-08-09T15:30:50.494Z - info: Running on android test: 107. #testThaliPeerAction - start and kill

2016-08-09T15:30:50.735Z - info: Running on android test: 108. #testThaliPeerAction - double start

2016-08-09T15:30:50.895Z - info: Running on android test: 109. #testThaliPeerAction - start after kill

2016-08-09T15:30:51.052Z - info: Running on android test: 110. #testThaliPeerAction - make sure ids are unique

2016-08-09T15:30:51.223Z - info: Running on android test: 111. Test PeerConnectionInformation basics

2016-08-09T15:30:51.381Z - info: Running on android test: 112. Test PeerDictionary basic functionality

2016-08-09T15:30:51.578Z - info: Running on android test: 113. Test PeerDictionary with multiple entries.

2016-08-09T15:30:53.396Z - info: Running on android test: 114. RESOLVED entries are removed before WAITING state entry.

2016-08-09T15:30:54.177Z - info: Running on android test: 115. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-08-09T15:30:54.958Z - info: Running on android test: 116. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-08-09T15:30:55.756Z - info: Running on android test: 117. #ThaliPeerPoolInterface - bad enqueues

2016-08-09T15:30:55.885Z - info: Running on android test: 118. #ThaliPeerPoolInterface - do not allow same object type

2016-08-09T15:30:55.987Z - info: Running on android test: 119. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-08-09T15:30:56.105Z - info: Running on android test: 120. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent

2016-08-09T15:30:56.278Z - info: Running on android test: 121. Make sure peerDictionaryKey is reasonable

2016-08-09T15:30:56.908Z - info: Running on android test: 122. Make sure start works

2016-08-09T15:30:57.561Z - info: Running on android test: 123. Make sure stop works

2016-08-09T15:30:57.747Z - info: Running on android test: 124. Simple peer event

2016-08-09T15:30:57.963Z - info: Running on android test: 125. Coordinated pull replication from notification test

2016-08-09T15:35:58.357Z - warn: Failed on android test: 125. Coordinated pull replication from notification test

2016-08-09T15:35:58.357Z - info: Running on android test: 126. Server is not there

2016-08-09T15:35:58.600Z - info: Running on android test: 127. Server accepts & closes connection

2016-08-09T15:35:58.802Z - info: Running on android test: 128. Server always returns 500

2016-08-09T15:35:59.078Z - info: Running on android test: 129. Server always returns 401

2016-08-09T15:35:59.366Z - info: Running on android test: 130. Server always returns 403

2016-08-09T15:35:59.642Z - info: Running on android test: 131. Make sure docs replicate

2016-08-09T15:36:01.509Z - info: Running on android test: 132. Do nothing and make sure we time out

2016-08-09T15:36:03.907Z - info: Running on android test: 133. Do something and make sure we time out

2016-08-09T15:36:07.369Z - info: Running on android test: 134. Start replicating and then catch error when server goes

2016-08-09T15:36:08.090Z - info: Running on android test: 135. Coordinated replication action test

2016-08-09T15:41:08.482Z - warn: Failed on android test: 135. Coordinated replication action test

2016-08-09T15:41:08.483Z - info: Running on android test: 136. compareBufferArrays

2016-08-09T15:41:08.620Z - info: Running on android test: 137. Call start twice and get error

2016-08-09T15:41:08.759Z - info: Running on android test: 138. Start and make sure it runs

2016-08-09T15:41:08.908Z - info: Running on android test: 139. Make sure getTimeWhenRun is right after start

2016-08-09T15:41:09.060Z - info: Running on android test: 140. Make sure getTimeWhenRun is -1 after function is called

2016-08-09T15:41:09.235Z - info: Running on android test: 141. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-08-09T15:41:09.392Z - info: Running on android test: 142. Test TransientState

2016-08-09T15:41:09.561Z - info: Running on android test: 143. No peers and empty database

2016-08-09T15:41:09.846Z - info: Running on android test: 144. One peer and empty DB

2016-08-09T15:41:10.186Z - info: Running on android test: 145. One peer with _Local set behind current seq

2016-08-09T15:41:10.913Z - info: Running on android test: 146. One peer with _Local set equal to current seq

2016-08-09T15:41:11.300Z - info: Running on android test: 147. One peer with _Local set ahead of current seq (and no this should not happen)

2016-08-09T15:41:11.618Z - info: Running on android test: 148. Three peers, one not in DB, one behind and one ahead

2016-08-09T15:41:12.025Z - info: Running on android test: 149. More than maximum peers, make sure we only send maximum allowed

2016-08-09T15:41:12.848Z - info: Running on android test: 150. two peers with empty DB, update the doc

2016-08-09T15:41:13.140Z - info: Running on android test: 151. add doc and make sure tokens refresh when they expire

2016-08-09T15:41:13.759Z - info: Running on android test: 152. start and stop and start and stop

2016-08-09T15:41:14.128Z - info: Running on android test: 153. two identical starts in a row

2016-08-09T15:41:14.449Z - info: Running on android test: 154. two different starts in a row

2016-08-09T15:41:14.783Z - info: Running on android test: 155. two stops and a start and two stops

2016-08-09T15:41:15.130Z - info: Running on android test: 156. we properly enqueue requests so no then needed

2016-08-09T15:41:15.498Z - info: Running on android test: 157. test calculateSeqPointKeyId

2016-08-09T15:41:15.720Z - info: Running on android test: 158. can create servers manager

2016-08-09T15:41:15.847Z - info: Running on android test: 159. calling stop without start causes error

2016-08-09T15:41:16.011Z - info: Running on android test: 160. can start/stop servers manager

2016-08-09T15:41:16.290Z - info: Running on android test: 161. starting twice resolves with listening port

2016-08-09T15:41:16.430Z - info: Running on android test: 162. terminateIncomingConnection will terminate a connection

2016-08-09T15:41:16.623Z - info: Running on android test: 163. terminate an Outgoing connection will terminate the server

2016-08-09T15:41:16.783Z - info: Running on android test: 164. terminate an Outgoing connection with wrong arguments is not harmful

2016-08-09T15:41:16.935Z - info: Running on android test: 165. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-08-09T15:41:17.145Z - info: Running on android test: 166. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-08-09T15:41:17.346Z - info: Running on android test: 167. messages with invalid location or USN should be ignored

2016-08-09T15:41:17.467Z - info: Running on android test: 168. verify that Thali-specific messages are filtered correctly

2016-08-09T15:41:17.599Z - info: Running on android test: 169. #startListeningForAdvertisements should fail if start not called

2016-08-09T15:41:17.738Z - info: Running on android test: 170. #startUpdateAdvertisingAndListening should fail if start not called

2016-08-09T15:41:17.888Z - info: Running on android test: 171. #start should fail if called twice in a row

2016-08-09T15:41:18.881Z - info: Running on android test: 172. should not be started after stop is called

2016-08-09T15:41:19.058Z - info: Running on android test: 173. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-08-09T15:41:20.453Z - info: Running on android test: 174. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-08-09T15:41:20.675Z - info: Running on android test: 175. #startUpdateAdvertisingAndListening should start hosting given router object

2016-08-09T15:41:20.986Z - info: Running on android test: 176. #startUpdateAdvertisingAndListening bad psk should be rejected object

2016-08-09T15:41:21.234Z - info: Running on android test: 177. #stop can be called multiple times in a row

2016-08-09T15:41:21.372Z - info: Running on android test: 178. #startListeningForAdvertisements can be called multiple times in a row

2016-08-09T15:41:21.541Z - info: Running on android test: 179. #stopListeningForAdvertisements can be called multiple times in a row

2016-08-09T15:41:21.722Z - info: Running on android test: 180. #stopAdvertisingAndListening can be called multiple times in a row

2016-08-09T15:41:21.898Z - info: Running on android test: 181. functions are run from a queue in the right order

2016-08-09T15:41:22.100Z - info: Running on android test: 182. does not get peer changes from self

2016-08-09T15:41:24.301Z - info: Running on android test: 183. #ThaliPeerPoolDefault - single action

2016-08-09T15:41:24.479Z - info: Running on android test: 184. #ThaliPeerPoolDefault - multiple actions

2016-08-09T15:41:24.627Z - info: Running on android test: 185. #ThaliPeerPoolDefault - PSK Pool works

2016-08-09T15:41:24.921Z - info: Running on android test: 186. #ThaliPeerPoolDefault - stop

2016-08-09T15:41:25.087Z - info: Test run on android complete

2016-08-09T15:41:25.090Z - info: 

-== UNIT TEST RESULTS ==-

2016-08-09T15:41:25.092Z - info: PLATFORM: android

2016-08-09T15:41:25.093Z - info: RESULT: FAIL

2016-08-09T15:41:25.094Z - info: 186 of 186 tests completed

2016-08-09T15:41:25.096Z - info: 183/186 passed (3 failures)

2016-08-09T15:41:25.097Z - info: 

--- Failed tests ---

2016-08-09T15:41:25.098Z - warn: 28. Coordinated seq test - fail

2016-08-09T15:41:25.099Z - warn: 125. Coordinated pull replication from notification test - fail

2016-08-09T15:41:25.100Z - warn: 135. Coordinated replication action test - fail

2016-08-09T15:41:25.101Z - info: 

-== END ==-

2016-08-09T15:41:26.862Z - info: Socket to device samsung-SM-G900F disconnected: transport close


 
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
####Node name: thali05
Console output:
```

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  LGD855a6933058 Test has  SUCCEEDED
Device test finished on LGD855a6933058 
Device test finished on LGD7228ee9cf5b 
STOP log received from  0be0c6c6 Test has  FAILED
Device test finished on 0be0c6c6 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/79689775403ec48_PR_for_CI_test_purposes__issue_777_mlesnic/thali05_samsung-SM-G900F.md)

[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/79689775403ec48_PR_for_CI_test_purposes__issue_777_mlesnic/thali05_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/79689775403ec48_PR_for_CI_test_purposes__issue_777_mlesnic/thali05_LGE-LG-D855.md)





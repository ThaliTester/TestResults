#### Test 79751015e87fad4 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":5}}
2016-08-05T12:14:06.858Z - info: Require 3 ios devices

2016-08-05T12:14:06.885Z - info: Require 3 android devices

2016-08-05T12:14:06.944Z - info: listening on *:3000

2016-08-05T12:14:07.578Z - debug: Device presented: motorola-Nexus 6 (43be89a2-2f51-417d-bfb2-c8acc2706bfa) - android 6.0.1

2016-08-05T12:14:07.604Z - debug: Device presented: samsung-SM-G900F (a755f412-5fa8-47eb-b816-a336de846e52) - android 6.0.1

2016-08-05T12:14:08.513Z - debug: Device presented: motorola-Nexus 6 (43be89a2-2f51-417d-bfb2-c8acc2706bfa) - android 6.0.1

2016-08-05T12:14:08.514Z - info: Updating existing device: motorola-Nexus 6 (43be89a2-2f51-417d-bfb2-c8acc2706bfa)

2016-08-05T12:14:08.566Z - debug: Device presented: samsung-SM-G900F (a755f412-5fa8-47eb-b816-a336de846e52) - android 6.0.1

2016-08-05T12:14:08.567Z - info: Updating existing device: samsung-SM-G900F (a755f412-5fa8-47eb-b816-a336de846e52)

2016-08-05T12:14:51.136Z - debug: Device presented: samsung-SM-N9005 (6501a5c8-4e9e-49a6-a936-c9678f494069) - android 5.0

2016-08-05T12:14:51.310Z - debug: Device presented: LGE-LG-D855 (777eeb2b-eed2-408c-9ae4-b21d944e23f0) - android 5.0

2016-08-05T12:15:07.762Z - debug: Device presented: LGE-LG-D722 (5614ce56-f490-4ad1-a59e-93b99a8317f8) - android 5.0.2

2016-08-05T12:15:07.765Z - info: All 5 android devices are present

2016-08-05T12:15:07.768Z - info: Disqualifying device with unsupported hardware: samsung-SM-N9005

2016-08-05T12:15:07.775Z - info: Disqualifying device with unsupported hardware: LGE-LG-D855

2016-08-05T12:15:07.779Z - info: Disqualifying device with unsupported hardware: LGE-LG-D722

2016-08-05T12:15:07.787Z - info: Starting unit test run on 2 android devices

2016-08-05T12:15:08.603Z - info: Socket to device LGE-LG-D855 disconnected: transport close

2016-08-05T12:15:08.849Z - info: Socket to device samsung-SM-N9005 disconnected: transport close

2016-08-05T12:15:09.056Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-05T12:15:09.569Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-08-05T12:15:11.073Z - info: Running on android test: 2. emits incomingConnectionState

2016-08-05T12:15:11.411Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-08-05T12:15:11.714Z - info: Running on android test: 4. native server connections all up

2016-08-05T12:15:12.044Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-08-05T12:15:12.364Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-08-05T12:15:12.733Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-08-05T12:15:13.021Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-08-05T12:15:13.345Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-08-05T12:15:14.423Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-08-05T12:15:14.791Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-08-05T12:15:15.064Z - info: Running on android test: 12. #_doImmediateSeqUpdate - server is not there

2016-08-05T12:15:15.464Z - info: Running on android test: 13. #_doImmediateSeqUpdate - server accepts & closes connection

2016-08-05T12:15:15.613Z - info: Running on android test: 14. #_doImmediateSeqUpdate - server always returns 500

2016-08-05T12:15:15.968Z - info: Running on android test: 15. #_doImmediateSeqUpdate - create new seq doc

2016-08-05T12:15:18.068Z - info: Running on android test: 16. #_doImmediateSeqUpdate - doc exists, need to get rev and update

2016-08-05T12:15:19.013Z - info: Running on android test: 17. #_doImmediateSeqUpdate - update seq three times

2016-08-05T12:15:20.079Z - info: Running on android test: 18. #_doImmediateSeqUpdate - rev got changed under us

2016-08-05T12:15:20.968Z - info: Running on android test: 19. #_doImmediateSeqUpdate - fail if stop is called

2016-08-05T12:15:21.219Z - info: Running on android test: 20. #_doImmediateSeqUpdate - stop after get but before put fails right

2016-08-05T12:15:21.745Z - info: Running on android test: 21. #update - fail if stop is called

2016-08-05T12:15:21.982Z - info: Running on android test: 22. #update - set seq for first time

2016-08-05T12:15:22.754Z - info: Running on android test: 23. #update - Fail on bad seq value

2016-08-05T12:15:23.439Z - info: Running on android test: 24. #update - do we cancel timer properly on an immediate?

2016-08-05T12:15:24.276Z - info: Running on android test: 25. #update - do we wait for blocked update

2016-08-05T12:15:25.073Z - info: Running on android test: 26. #update - test that we wait long enough

2016-08-05T12:15:26.943Z - info: Running on android test: 27. #update - test that we pick up new sequences while we wait

2016-08-05T12:15:28.512Z - info: Running on android test: 28. Coordinated seq test

2016-08-05T12:20:29.128Z - warn: Failed on android test: 28. Coordinated seq test

2016-08-05T12:20:29.130Z - info: Running on android test: 29. closeAll can close even when connections open

2016-08-05T12:20:29.610Z - info: Running on android test: 30. closeAll with promise

2016-08-05T12:20:29.944Z - info: Running on android test: 31. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-08-05T12:20:30.259Z - info: Running on android test: 32. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-08-05T12:20:30.602Z - info: Running on android test: 33. enqueue and run in order

2016-08-05T12:20:31.058Z - info: Running on android test: 34. enqueueAtTop and run backwards

2016-08-05T12:20:31.283Z - info: Running on android test: 35. mix enqueue and enqueueAtTop

2016-08-05T12:20:31.631Z - info: Running on android test: 36. queues handled independently

2016-08-05T12:20:31.857Z - info: Running on android test: 37. basic

2016-08-05T12:20:32.044Z - info: Running on android test: 38. another

2016-08-05T12:20:32.262Z - info: Running on android test: 39. can pass data in setup

2016-08-05T12:20:32.470Z - info: Running on android test: 40. #startListeningForAdvertisements should fail if start not called

2016-08-05T12:20:32.657Z - info: Running on android test: 41. #startUpdateAdvertisingAndListening should fail if start not called

2016-08-05T12:20:32.857Z - info: Running on android test: 42. should be able to call #stopListeningForAdvertisements many times

2016-08-05T12:20:33.096Z - info: Running on android test: 43. should be able to call #startListeningForAdvertisements many times

2016-08-05T12:20:34.777Z - info: Running on android test: 44. should be able to call #startUpdateAdvertisingAndListening many times

2016-08-05T12:20:36.628Z - info: Running on android test: 45. should be able to call #stopAdvertisingAndListening many times

2016-08-05T12:20:36.868Z - info: Running on android test: 46. #start should fail if called twice in a row

2016-08-05T12:20:37.115Z - info: Running on android test: 47. does not emit duplicate discoveryAdvertisingStateUpdate

2016-08-05T12:20:39.026Z - info: Running on android test: 48. does not send duplicate availability changes

2016-08-05T12:20:39.214Z - info: Running on android test: 49. can get the network status

2016-08-05T12:20:39.424Z - info: Running on android test: 50. wifi peer is marked unavailable if announcements stop

2016-08-05T12:20:41.690Z - info: Running on android test: 51. Can call start/stopListeningForAdvertisements

2016-08-05T12:20:43.336Z - info: Running on android test: 52. Client to server request coordinated

2016-08-05T12:20:59.317Z - info: Running on android test: 53. Test BEACONS_RETRIEVED_AND_PARSED locally

2016-08-05T12:20:59.736Z - info: Running on android test: 54. Test HTTP_BAD_RESPONSE locally

2016-08-05T12:21:00.165Z - info: Running on android test: 55. Test NETWORK_PROBLEM locally

2016-08-05T12:21:00.641Z - info: Running on android test: 56. Call the start two times

2016-08-05T12:21:01.195Z - info: Running on android test: 57. Call the kill before calling the start

2016-08-05T12:21:01.569Z - info: Running on android test: 58. Call the kill immediately after the start

2016-08-05T12:21:01.952Z - info: Running on android test: 59. Call the kill while waiting a response from the server

2016-08-05T12:21:04.446Z - info: Running on android test: 60. Test to exceed the max content size locally

2016-08-05T12:21:06.295Z - info: Running on android test: 61. Close the server socket while the client is waiting a response from the server. Local test.

2016-08-05T12:21:08.734Z - info: Running on android test: 62. Close the client socket while the client is waiting a response from the server. Local test.

2016-08-05T12:21:11.113Z - info: Running on android test: 63. #generatePreambleAndBeacons bad args

2016-08-05T12:21:11.344Z - info: Running on android test: 64. #generatePreambleAndBeacons empty keys to notify

2016-08-05T12:21:11.592Z - info: Running on android test: 65. #generatePreambleAndBeacons multiple keys to notify

2016-08-05T12:21:12.226Z - info: Running on android test: 66. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-08-05T12:21:12.454Z - info: Running on android test: 67. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-08-05T12:21:12.697Z - info: Running on android test: 68. #parseBeacons expiration out of range lower

2016-08-05T12:21:12.896Z - info: Running on android test: 69. #parseBeacons expiration out of range lower

2016-08-05T12:21:13.095Z - info: Running on android test: 70. #parseBeacons no beacons returns null

2016-08-05T12:21:13.263Z - info: Running on android test: 71. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-08-05T12:21:13.494Z - info: Running on android test: 72. #parseBeacons addressBookCallback fails decrypt

2016-08-05T12:21:13.859Z - info: Running on android test: 73. #parseBeacons addressBookCallback returns no matches

2016-08-05T12:21:14.186Z - info: Running on android test: 74. #parseBeacons addressBookCallback returns spurious match

2016-08-05T12:21:14.537Z - info: Running on android test: 75. #parseBeacons addressBookCallback returns public key

2016-08-05T12:21:14.871Z - info: Running on android test: 76. validate generatePskIdentityField

2016-08-05T12:21:15.040Z - info: Running on android test: 77. validate generatePskSecret

2016-08-05T12:21:15.256Z - info: Running on android test: 78. validate generatePskSecrets

2016-08-05T12:21:19.489Z - info: Running on android test: 79. validate generateBeaconStreamAndSecrets

2016-08-05T12:21:20.970Z - info: Running on android test: 80. Add two Peers.

2016-08-05T12:21:21.263Z - info: Running on android test: 81. TCP_NATIVE peer loses DNS

2016-08-05T12:21:21.546Z - info: Running on android test: 82. Received beacons with no values for us

2016-08-05T12:21:22.446Z - info: Running on android test: 83. Resolves an action locally

2016-08-05T12:21:22.936Z - info: Running on android test: 84. Resolves an action locally using ThaliPeerPoolDefault

2016-08-05T12:21:23.360Z - info: Running on android test: 85. Action fails because of a bad hostname.

2016-08-05T12:21:28.727Z - info: Running on android test: 86. hostaddress is removed when the action is running. 

2016-08-05T12:21:31.084Z - info: Running on android test: 87. Client to server request locally

2016-08-05T12:21:31.523Z - info: Running on android test: 88. Test ThaliPskMapCache clean and expiration

2016-08-05T12:21:32.770Z - info: Running on android test: 89. Test ThaliPskMapCache getSecret and getPublic

2016-08-05T12:21:34.319Z - info: Running on android test: 90. Test ThaliPskMapCache multiple entries

2016-08-05T12:21:37.517Z - info: Running on android test: 91. Start and stop ThaliNotificationServer

2016-08-05T12:21:37.849Z - info: Running on android test: 92. Pass an empty array to ThaliNotificationServer.start

2016-08-05T12:21:38.123Z - info: Running on android test: 93. Pass a string to ThaliNotificationServer.start

2016-08-05T12:21:38.366Z - info: Running on android test: 94. Pass an empty parameter to ThaliNotificationServer.start

2016-08-05T12:21:38.591Z - info: Running on android test: 95. Make an HTTP request to /NotificationBeacons

2016-08-05T12:21:39.026Z - info: Running on android test: 96. Make an HTTP request to /NotificationBeacons (no keys)

2016-08-05T12:21:39.250Z - info: Running on android test: 97. Make an HTTP request to /NotificationBeaconsbefore calling start

2016-08-05T12:21:39.521Z - info: Running on android test: 98. #testThaliPeerAction - test getters

2016-08-05T12:21:39.691Z - info: Running on android test: 99. #testThaliPeerAction - start and kill

2016-08-05T12:21:39.853Z - info: Running on android test: 100. #testThaliPeerAction - double start

2016-08-05T12:21:40.004Z - info: Running on android test: 101. #testThaliPeerAction - start after kill

2016-08-05T12:21:40.166Z - info: Running on android test: 102. #testThaliPeerAction - make sure ids are unique

2016-08-05T12:21:40.327Z - info: Running on android test: 103. Test PeerConnectionInformation basics

2016-08-05T12:21:40.508Z - info: Running on android test: 104. Test PeerDictionary basic functionality

2016-08-05T12:21:40.783Z - info: Running on android test: 105. Test PeerDictionary with multiple entries.

2016-08-05T12:21:42.808Z - info: Running on android test: 106. RESOLVED entries are removed before WAITING state entry.

2016-08-05T12:21:43.842Z - info: Running on android test: 107. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-08-05T12:21:44.786Z - info: Running on android test: 108. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-08-05T12:21:45.726Z - info: Running on android test: 109. #ThaliPeerPoolInterface - bad enqueues

2016-08-05T12:21:45.906Z - info: Running on android test: 110. #ThaliPeerPoolInterface - do not allow same object type

2016-08-05T12:21:46.082Z - info: Running on android test: 111. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-08-05T12:21:46.265Z - info: Running on android test: 112. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent

2016-08-05T12:21:46.428Z - info: Running on android test: 113. Make sure peerDictionaryKey is reasonable

2016-08-05T12:21:46.597Z - info: Running on android test: 114. Make sure start works

2016-08-05T12:21:46.806Z - info: Running on android test: 115. Make sure stop works

2016-08-05T12:21:47.030Z - info: Running on android test: 116. Simple peer event

2016-08-05T12:21:48.686Z - info: Running on android test: 117. Coordinated pull replication from notification test

2016-08-05T12:26:49.270Z - warn: Failed on android test: 117. Coordinated pull replication from notification test

2016-08-05T12:26:49.273Z - info: Running on android test: 118. Server is not there

2016-08-05T12:26:49.579Z - info: Running on android test: 119. Server accepts & closes connection

2016-08-05T12:26:49.951Z - info: Running on android test: 120. Server always returns 500

2016-08-05T12:26:50.288Z - info: Running on android test: 121. Server always returns 401

2016-08-05T12:26:50.623Z - info: Running on android test: 122. Server always returns 403

2016-08-05T12:26:50.956Z - info: Running on android test: 123. Make sure docs replicate

2016-08-05T12:26:53.038Z - info: Running on android test: 124. Do nothing and make sure we time out

2016-08-05T12:26:55.504Z - info: Running on android test: 125. Do something and make sure we time out

2016-08-05T12:26:59.065Z - info: Running on android test: 126. Start replicating and then catch error when server goes

2016-08-05T12:26:59.902Z - info: Running on android test: 127. compareBufferArrays

2016-08-05T12:27:00.032Z - info: Running on android test: 128. Call start twice and get error

2016-08-05T12:27:00.235Z - info: Running on android test: 129. Start and make sure it runs

2016-08-05T12:27:00.438Z - info: Running on android test: 130. Make sure getTimeWhenRun is right after start

2016-08-05T12:27:00.606Z - info: Running on android test: 131. Make sure getTimeWhenRun is -1 after function is called

2016-08-05T12:27:00.769Z - info: Running on android test: 132. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-08-05T12:27:00.998Z - info: Running on android test: 133. Test TransientState

2016-08-05T12:27:01.165Z - info: Running on android test: 134. No peers and empty database

2016-08-05T12:27:01.452Z - info: Running on android test: 135. One peer and empty DB

2016-08-05T12:27:01.812Z - info: Running on android test: 136. One peer with _Local set behind current seq

2016-08-05T12:27:02.401Z - info: Running on android test: 137. One peer with _Local set equal to current seq

2016-08-05T12:27:03.897Z - info: Running on android test: 138. One peer with _Local set ahead of current seq (and no this should not happen)

2016-08-05T12:27:04.301Z - info: Running on android test: 139. Three peers, one not in DB, one behind and one ahead

2016-08-05T12:27:04.776Z - info: Running on android test: 140. More than maximum peers, make sure we only send maximum allowed

2016-08-05T12:27:05.727Z - info: Running on android test: 141. two peers with empty DB, update the doc

2016-08-05T12:27:06.106Z - info: Running on android test: 142. add doc and make sure tokens refresh when they expire

2016-08-05T12:27:06.836Z - info: Running on android test: 143. start and stop and start and stop

2016-08-05T12:27:07.221Z - info: Running on android test: 144. two identical starts in a row

2016-08-05T12:27:07.578Z - info: Running on android test: 145. two different starts in a row

2016-08-05T12:27:08.014Z - info: Running on android test: 146. two stops and a start and two stops

2016-08-05T12:27:08.403Z - info: Running on android test: 147. we properly enqueue requests so no then needed

2016-08-05T12:27:08.814Z - info: Running on android test: 148. test calculateSeqPointKeyId

2016-08-05T12:27:09.050Z - info: Running on android test: 149. can create servers manager

2016-08-05T12:27:09.232Z - info: Running on android test: 150. calling stop without start causes error

2016-08-05T12:27:09.397Z - info: Running on android test: 151. can start/stop servers manager

2016-08-05T12:27:09.567Z - info: Running on android test: 152. starting twice resolves with listening port

2016-08-05T12:27:09.732Z - info: Running on android test: 153. terminateIncomingConnection will terminate a connection

2016-08-05T12:27:09.959Z - info: Running on android test: 154. terminate an Outgoing connection will terminate the server

2016-08-05T12:27:10.170Z - info: Running on android test: 155. terminate an Outgoing connection with wrong arguments is not harmful

2016-08-05T12:27:10.343Z - info: Running on android test: 156. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-08-05T12:27:10.577Z - info: Running on android test: 157. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-08-05T12:27:10.820Z - info: Running on android test: 158. messages with invalid location or USN should be ignored

2016-08-05T12:27:11.014Z - info: Running on android test: 159. verify that Thali-specific messages are filtered correctly

2016-08-05T12:27:11.195Z - info: Running on android test: 160. #startListeningForAdvertisements should fail if start not called

2016-08-05T12:27:11.367Z - info: Running on android test: 161. #startUpdateAdvertisingAndListening should fail if start not called

2016-08-05T12:27:11.663Z - info: Running on android test: 162. #start should fail if called twice in a row

2016-08-05T12:27:11.822Z - info: Running on android test: 163. should not be started after stop is called

2016-08-05T12:27:12.020Z - info: Running on android test: 164. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-08-05T12:27:12.219Z - info: Running on android test: 165. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-08-05T12:27:12.446Z - info: Running on android test: 166. #startUpdateAdvertisingAndListening should start hosting given router object

2016-08-05T12:27:12.730Z - info: Running on android test: 167. #startUpdateAdvertisingAndListening bad psk should be rejected object

2016-08-05T12:27:12.994Z - info: Running on android test: 168. #stop can be called multiple times in a row

2016-08-05T12:27:13.181Z - info: Running on android test: 169. #startListeningForAdvertisements can be called multiple times in a row

2016-08-05T12:27:13.372Z - info: Running on android test: 170. #stopListeningForAdvertisements can be called multiple times in a row

2016-08-05T12:27:13.574Z - info: Running on android test: 171. #stopAdvertisingAndListening can be called multiple times in a row

2016-08-05T12:27:13.784Z - info: Running on android test: 172. functions are run from a queue in the right order

2016-08-05T12:27:13.998Z - info: Running on android test: 173. does not get peer changes from self

2016-08-05T12:27:16.226Z - info: Running on android test: 174. #ThaliPeerPoolDefault - single action

2016-08-05T12:27:16.413Z - info: Running on android test: 175. #ThaliPeerPoolDefault - multiple actions

2016-08-05T12:27:16.570Z - info: Running on android test: 176. #ThaliPeerPoolDefault - PSK Pool works

2016-08-05T12:27:16.871Z - info: Running on android test: 177. #ThaliPeerPoolDefault - stop

2016-08-05T12:27:17.037Z - info: Test run on android complete

2016-08-05T12:27:17.040Z - info: 

-== UNIT TEST RESULTS ==-

2016-08-05T12:27:17.042Z - info: PLATFORM: android

2016-08-05T12:27:17.043Z - info: RESULT: FAIL

2016-08-05T12:27:17.044Z - info: 177 of 177 tests completed
2016-08-05T12:27:17.045Z - info: 175/177 passed (2 failures)

2016-08-05T12:27:17.046Z - info: 

--- Failed tests ---

2016-08-05T12:27:17.047Z - warn: 28. Coordinated seq test - fail

2016-08-05T12:27:17.048Z - warn: 117. Coordinated pull replication from notification test - fail
2016-08-05T12:27:17.049Z - info: 

-== END ==-

2016-08-05T12:27:17.983Z - info: Socket to device motorola-Nexus 6 disconnected: transport close

2016-08-05T12:27:18.775Z - info: Socket to device samsung-SM-G900F disconnected: transport close


 
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
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  1d6a772d Test has  SUCCEEDED
STOP log received from  LGD855a6933058 Test has  SUCCEEDED
Device test finished on LGD855a6933058 
Device test finished on 1d6a772d 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/79751015e87fad4_Check_811_failures_in_CI_do_not_merge__czyzm/thali05_samsung-SM-N9005.md)

[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/79751015e87fad4_Check_811_failures_in_CI_do_not_merge__czyzm/thali05_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/79751015e87fad4_Check_811_failures_in_CI_do_not_merge__czyzm/thali05_LGE-LG-D855.md)

####Node name: thali08
Console output:
```


 Marshmallow device. Granting ACCESS_COARSE_LOCATION permission


 Marshmallow device. Granting ACCESS_COARSE_LOCATION permission
STOP log received from  0be0c6c6 Test has  SUCCEEDED
STOP log received from  ZX1G429CRK Test has  FAILED
Device test finished on ZX1G429CRK 
Device test finished on 0be0c6c6 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/79751015e87fad4_Check_811_failures_in_CI_do_not_merge__czyzm/thali08_motorola-Nexus 6.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/79751015e87fad4_Check_811_failures_in_CI_do_not_merge__czyzm/thali08_samsung-SM-G900F.md)





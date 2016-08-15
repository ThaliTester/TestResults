#### Test 81321942665e562 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":4}}
2016-08-15T15:20:23.409Z - info: Require 3 ios devices

2016-08-15T15:20:23.427Z - info: Require 3 android devices

2016-08-15T15:20:23.486Z - info: listening on *:3000

2016-08-15T15:20:26.658Z - debug: Device presented: motorola-Nexus 6 (9abb4d17-a5ae-47aa-8381-e83fb0208d2f) - android 6.0.1

2016-08-15T15:20:27.622Z - debug: Device presented: motorola-Nexus 6 (9abb4d17-a5ae-47aa-8381-e83fb0208d2f) - android 6.0.1

2016-08-15T15:20:27.626Z - info: Updating existing device: motorola-Nexus 6 (9abb4d17-a5ae-47aa-8381-e83fb0208d2f)

2016-08-15T15:20:27.953Z - debug: Device presented: samsung-SM-G900F (63cd6f14-8909-41ba-bf01-6b3a79ee8f23) - android 6.0.1

2016-08-15T15:20:28.924Z - debug: Device presented: samsung-SM-G900F (63cd6f14-8909-41ba-bf01-6b3a79ee8f23) - android 6.0.1

2016-08-15T15:20:28.925Z - info: Updating existing device: samsung-SM-G900F (63cd6f14-8909-41ba-bf01-6b3a79ee8f23)

2016-08-15T15:21:17.308Z - debug: Device presented: LGE-LG-D855 (0654640b-2a68-457c-8933-8ee22aa269b8) - android 5.0

2016-08-15T15:21:24.679Z - debug: Device presented: LGE-LG-D722 (c45c715a-bd5e-4fcc-8ab8-17b649c9630b) - android 5.0.2

2016-08-15T15:21:24.682Z - info: All 4 android devices are present

2016-08-15T15:21:24.684Z - info: Disqualifying device with unsupported hardware: LGE-LG-D855

2016-08-15T15:21:24.691Z - info: Disqualifying device with unsupported hardware: LGE-LG-D722

2016-08-15T15:21:24.698Z - info: Starting unit test run on 2 android devices

2016-08-15T15:21:25.388Z - info: Socket to device LGE-LG-D855 disconnected: transport close

2016-08-15T15:21:25.552Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-08-15T15:21:25.752Z - info: Running on android test: 2. emits incomingConnectionState

2016-08-15T15:21:25.999Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-08-15T15:21:26.066Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-15T15:21:26.321Z - info: Running on android test: 4. native server connections all up

2016-08-15T15:21:26.647Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-08-15T15:21:26.965Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-08-15T15:21:27.365Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-08-15T15:21:27.731Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-08-15T15:21:28.028Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-08-15T15:21:29.974Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-08-15T15:21:30.457Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-08-15T15:21:30.800Z - info: Running on android test: 12. #_doImmediateSeqUpdate - server is not there

2016-08-15T15:21:31.205Z - info: Running on android test: 13. #_doImmediateSeqUpdate - server accepts & closes connection

2016-08-15T15:21:31.507Z - info: Running on android test: 14. #_doImmediateSeqUpdate - server always returns 500

2016-08-15T15:21:31.890Z - info: Running on android test: 15. #_doImmediateSeqUpdate - create new seq doc

2016-08-15T15:21:34.051Z - info: Running on android test: 16. #_doImmediateSeqUpdate - doc exists, need to get rev and update

2016-08-15T15:21:35.051Z - info: Running on android test: 17. #_doImmediateSeqUpdate - update seq three times

2016-08-15T15:21:36.083Z - info: Running on android test: 18. #_doImmediateSeqUpdate - rev got changed under us

2016-08-15T15:21:36.971Z - info: Running on android test: 19. #_doImmediateSeqUpdate - fail if stop is called

2016-08-15T15:21:37.226Z - info: Running on android test: 20. #_doImmediateSeqUpdate - stop after get but before put fails right

2016-08-15T15:21:37.716Z - info: Running on android test: 21. #update - fail if stop is called

2016-08-15T15:21:37.956Z - info: Running on android test: 22. #update - set seq for first time

2016-08-15T15:21:38.633Z - info: Running on android test: 23. #update - Fail on bad seq value

2016-08-15T15:21:39.222Z - info: Running on android test: 24. #update - do we cancel timer properly on an immediate?

2016-08-15T15:21:40.025Z - info: Running on android test: 25. #update - do we wait for blocked update

2016-08-15T15:21:40.725Z - info: Running on android test: 26. #update - test that we wait long enough

2016-08-15T15:21:42.470Z - info: Running on android test: 27. #update - test that we pick up new sequences while we wait

2016-08-15T15:21:44.058Z - info: Running on android test: 28. Coordinated seq test

2016-08-15T15:21:58.661Z - info: Running on android test: 29. closeAll can close even when connections open

2016-08-15T15:21:59.035Z - info: Running on android test: 30. closeAll with promise

2016-08-15T15:21:59.385Z - info: Running on android test: 31. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-08-15T15:21:59.722Z - info: Running on android test: 32. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-08-15T15:22:00.053Z - info: Running on android test: 33. enqueue and run in order

2016-08-15T15:22:00.842Z - info: Running on android test: 34. enqueueAtTop and run backwards

2016-08-15T15:22:03.726Z - info: Running on android test: 35. mix enqueue and enqueueAtTop

2016-08-15T15:22:06.526Z - info: Running on android test: 36. queues handled independently

2016-08-15T15:22:07.202Z - info: Running on android test: 37. basic

2016-08-15T15:22:08.712Z - info: Running on android test: 38. another

2016-08-15T15:22:08.885Z - info: Running on android test: 39. can pass data in setup

2016-08-15T15:22:09.086Z - info: Running on android test: 40. #startListeningForAdvertisements should fail if start not called

2016-08-15T15:22:09.281Z - info: Running on android test: 41. #startUpdateAdvertisingAndListening should fail if start not called

2016-08-15T15:22:09.489Z - info: Running on android test: 42. should be able to call #stopListeningForAdvertisements many times

2016-08-15T15:22:09.753Z - info: Running on android test: 43. should be able to call #startListeningForAdvertisements many times

2016-08-15T15:22:11.430Z - info: Running on android test: 44. should be able to call #startUpdateAdvertisingAndListening many times

2016-08-15T15:22:12.807Z - info: Running on android test: 45. should be able to call #stopAdvertisingAndListening many times

2016-08-15T15:22:13.113Z - info: Running on android test: 46. #start should fail if called twice in a row

2016-08-15T15:22:13.366Z - info: Running on android test: 47. does not emit duplicate discoveryAdvertisingStateUpdate

2016-08-15T15:22:15.435Z - info: Running on android test: 48. does not send duplicate availability changes

2016-08-15T15:22:15.611Z - info: Running on android test: 49. can get the network status

2016-08-15T15:22:15.838Z - info: Running on android test: 50. wifi peer is marked unavailable if announcements stop

2016-08-15T15:22:18.117Z - info: Running on android test: 51. Can call start/stopListeningForAdvertisements

2016-08-15T15:22:19.861Z - info: Running on android test: 52. Calling startListeningForAdvertisements twice is NOT an error

2016-08-15T15:22:21.575Z - info: Running on android test: 53. Calling stopListeningForAdvertisements without calling start is NOT an error

2016-08-15T15:22:21.828Z - info: Running on android test: 54. Can call start/stopUpdateAdvertisingAndListening

2016-08-15T15:22:22.916Z - info: Running on android test: 55. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-08-15T15:22:24.240Z - info: Running on android test: 56. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error

2016-08-15T15:22:24.555Z - info: Running on android test: 57. cannot call connect when start listening for advertisements is not active

2016-08-15T15:22:24.763Z - info: Running on android test: 58. peerAvailabilityChange is called

2016-08-15T15:22:28.998Z - info: Running on android test: 59. Can connect to a remote peer

2016-08-15T15:22:44.335Z - info: Running on android test: 60. Get error when trying to double connect to a peer

2016-08-15T15:23:11.657Z - info: Running on android test: 61. Connect port dies if not connected to in time

2016-08-15T15:23:12.063Z - info: Running on android test: 62. Can shift large amounts of data

2016-08-15T15:23:40.579Z - info: Running on android test: 63. #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection

2016-08-15T15:24:07.543Z - info: Running on android test: 64. #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection

2016-08-15T15:24:25.046Z - info: Running on android test: 65. #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer

2016-08-15T15:24:36.522Z - info: Running on android test: 66. #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer

2016-08-15T15:24:41.658Z - info: Running on android test: 67. We do not emit peerAvailabilityChanged events until one of the start methods is called

2016-08-15T15:24:50.610Z - info: Running on android test: 68. Test updating advertising and parallel data transfer

2016-08-15T15:25:24.350Z - info: Running on android test: 69. Client to server request coordinated

2016-08-15T15:27:30.702Z - warn: Failed on android test: 69. Client to server request coordinated

2016-08-15T15:27:30.703Z - info: Running on android test: 70. Test BEACONS_RETRIEVED_AND_PARSED locally

2016-08-15T15:27:31.139Z - info: Running on android test: 71. Test HTTP_BAD_RESPONSE locally

2016-08-15T15:27:31.472Z - info: Running on android test: 72. Test NETWORK_PROBLEM locally

2016-08-15T15:27:31.866Z - info: Running on android test: 73. Call the start two times

2016-08-15T15:27:32.441Z - info: Running on android test: 74. Call the kill before calling the start

2016-08-15T15:27:32.767Z - info: Running on android test: 75. Call the kill immediately after the start

2016-08-15T15:27:33.108Z - info: Running on android test: 76. Call the kill while waiting a response from the server

2016-08-15T15:27:35.502Z - info: Running on android test: 77. Test to exceed the max content size locally

2016-08-15T15:27:35.918Z - info: Running on android test: 78. Close the server socket while the client is waiting a response from the server. Local test.

2016-08-15T15:27:38.339Z - info: Running on android test: 79. Close the client socket while the client is waiting a response from the server. Local test.

2016-08-15T15:27:40.713Z - info: Running on android test: 80. #generatePreambleAndBeacons bad args

2016-08-15T15:27:40.915Z - info: Running on android test: 81. #generatePreambleAndBeacons empty keys to notify

2016-08-15T15:27:41.115Z - info: Running on android test: 82. #generatePreambleAndBeacons multiple keys to notify

2016-08-15T15:27:41.443Z - info: Running on android test: 83. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-08-15T15:27:41.616Z - info: Running on android test: 84. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-08-15T15:27:41.804Z - info: Running on android test: 85. #parseBeacons expiration out of range lower

2016-08-15T15:27:42.012Z - info: Running on android test: 86. #parseBeacons expiration out of range lower

2016-08-15T15:27:42.227Z - info: Running on android test: 87. #parseBeacons no beacons returns null

2016-08-15T15:27:42.405Z - info: Running on android test: 88. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-08-15T15:27:42.590Z - info: Running on android test: 89. #parseBeacons addressBookCallback fails decrypt

2016-08-15T15:27:42.924Z - info: Running on android test: 90. #parseBeacons addressBookCallback returns no matches

2016-08-15T15:27:43.223Z - info: Running on android test: 91. #parseBeacons addressBookCallback returns spurious match

2016-08-15T15:27:43.576Z - info: Running on android test: 92. #parseBeacons addressBookCallback returns public key

2016-08-15T15:27:43.925Z - info: Running on android test: 93. validate generatePskIdentityField

2016-08-15T15:27:44.108Z - info: Running on android test: 94. validate generatePskSecret

2016-08-15T15:27:44.349Z - info: Running on android test: 95. validate generatePskSecrets

2016-08-15T15:27:44.782Z - info: Running on android test: 96. validate generateBeaconStreamAndSecrets

2016-08-15T15:27:45.112Z - info: Running on android test: 97. Add two Peers.

2016-08-15T15:27:45.418Z - info: Running on android test: 98. TCP_NATIVE peer loses DNS

2016-08-15T15:27:45.672Z - info: Running on android test: 99. Received beacons with no values for us

2016-08-15T15:27:46.093Z - info: Running on android test: 100. Resolves an action locally

2016-08-15T15:27:46.515Z - info: Running on android test: 101. Resolves an action locally using ThaliPeerPoolDefault

2016-08-15T15:27:46.933Z - info: Running on android test: 102. Action fails because of a bad hostname.

2016-08-15T15:27:52.275Z - info: Running on android test: 103. hostaddress is removed when the action is running. 

2016-08-15T15:27:54.625Z - info: Running on android test: 104. Client to server request locally

2016-08-15T15:27:55.065Z - info: Running on android test: 105. Test ThaliPskMapCache clean and expiration

2016-08-15T15:27:56.341Z - info: Running on android test: 106. Test ThaliPskMapCache getSecret and getPublic

2016-08-15T15:27:57.754Z - info: Running on android test: 107. Test ThaliPskMapCache multiple entries

2016-08-15T15:28:00.700Z - info: Running on android test: 108. Start and stop ThaliNotificationServer

2016-08-15T15:28:01.051Z - info: Running on android test: 109. Pass an empty array to ThaliNotificationServer.start

2016-08-15T15:28:01.326Z - info: Running on android test: 110. Pass a string to ThaliNotificationServer.start

2016-08-15T15:28:01.538Z - info: Running on android test: 111. Pass an empty parameter to ThaliNotificationServer.start

2016-08-15T15:28:01.811Z - info: Running on android test: 112. Make an HTTP request to /NotificationBeacons

2016-08-15T15:28:02.276Z - info: Running on android test: 113. Make an HTTP request to /NotificationBeacons (no keys)

2016-08-15T15:28:02.466Z - info: Running on android test: 114. Make an HTTP request to /NotificationBeaconsbefore calling start

2016-08-15T15:28:02.702Z - info: Running on android test: 115. #testThaliPeerAction - test getters

2016-08-15T15:28:02.875Z - info: Running on android test: 116. #testThaliPeerAction - start and kill

2016-08-15T15:28:03.050Z - info: Running on android test: 117. #testThaliPeerAction - double start

2016-08-15T15:28:03.207Z - info: Running on android test: 118. #testThaliPeerAction - start after kill

2016-08-15T15:28:03.361Z - info: Running on android test: 119. #testThaliPeerAction - make sure ids are unique

2016-08-15T15:28:03.513Z - info: Running on android test: 120. Test PeerConnectionInformation basics

2016-08-15T15:28:03.685Z - info: Running on android test: 121. Test PeerDictionary basic functionality

2016-08-15T15:28:03.876Z - info: Running on android test: 122. Test PeerDictionary with multiple entries.

2016-08-15T15:28:05.713Z - info: Running on android test: 123. RESOLVED entries are removed before WAITING state entry.

2016-08-15T15:28:06.532Z - info: Running on android test: 124. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-08-15T15:28:08.613Z - info: Running on android test: 125. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-08-15T15:28:09.723Z - info: Running on android test: 126. #ThaliPeerPoolInterface - bad enqueues

2016-08-15T15:28:09.862Z - info: Running on android test: 127. #ThaliPeerPoolInterface - do not allow same object type

2016-08-15T15:28:10.008Z - info: Running on android test: 128. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-08-15T15:28:10.187Z - info: Running on android test: 129. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent

2016-08-15T15:28:10.344Z - info: Running on android test: 130. Make sure peerDictionaryKey is reasonable

2016-08-15T15:28:10.553Z - info: Running on android test: 131. Make sure start works

2016-08-15T15:28:10.770Z - info: Running on android test: 132. Make sure stop works

2016-08-15T15:28:10.978Z - info: Running on android test: 133. Simple peer event

2016-08-15T15:28:11.247Z - info: Running on android test: 134. Coordinated pull replication from notification test

2016-08-15T15:33:11.819Z - warn: Failed on android test: 134. Coordinated pull replication from notification test

2016-08-15T15:33:11.820Z - info: Running on android test: 135. Server is not there

2016-08-15T15:33:12.407Z - info: Running on android test: 136. Server accepts & closes connection

2016-08-15T15:33:12.773Z - info: Running on android test: 137. Server always returns 500

2016-08-15T15:33:13.176Z - info: Running on android test: 138. Server always returns 401

2016-08-15T15:33:13.516Z - info: Running on android test: 139. Server always returns 403

2016-08-15T15:33:13.830Z - info: Running on android test: 140. Make sure docs replicate

2016-08-15T15:33:15.975Z - info: Running on android test: 141. Do nothing and make sure we time out

2016-08-15T15:33:19.526Z - info: Running on android test: 142. Do something and make sure we time out

2016-08-15T15:33:23.346Z - info: Running on android test: 143. Start replicating and then catch error when server goes

2016-08-15T15:33:24.155Z - info: Running on android test: 144. Coordinated replication action test

2016-08-15T15:38:24.596Z - warn: Failed on android test: 144. Coordinated replication action test

2016-08-15T15:38:24.597Z - info: Running on android test: 145. compareBufferArrays

2016-08-15T15:38:24.891Z - info: Running on android test: 146. Call start twice and get error

2016-08-15T15:38:25.102Z - info: Running on android test: 147. Start and make sure it runs

2016-08-15T15:38:25.293Z - info: Running on android test: 148. Make sure getTimeWhenRun is right after start

2016-08-15T15:38:25.507Z - info: Running on android test: 149. Make sure getTimeWhenRun is -1 after function is called

2016-08-15T15:38:25.720Z - info: Running on android test: 150. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-08-15T15:38:25.966Z - info: Running on android test: 151. Test TransientState

2016-08-15T15:38:26.158Z - info: Running on android test: 152. No peers and empty database

2016-08-15T15:38:26.516Z - info: Running on android test: 153. One peer and empty DB

2016-08-15T15:38:27.149Z - info: Running on android test: 154. One peer with _Local set behind current seq

2016-08-15T15:38:27.545Z - info: Running on android test: 155. One peer with _Local set equal to current seq

2016-08-15T15:38:27.952Z - info: Running on android test: 156. One peer with _Local set ahead of current seq (and no this should not happen)

2016-08-15T15:38:28.346Z - info: Running on android test: 157. Three peers, one not in DB, one behind and one ahead

2016-08-15T15:38:28.843Z - info: Running on android test: 158. More than maximum peers, make sure we only send maximum allowed

2016-08-15T15:38:33.737Z - info: Running on android test: 159. two peers with empty DB, update the doc

2016-08-15T15:38:34.266Z - info: Running on android test: 160. start and stop and start and stop

2016-08-15T15:38:34.640Z - info: Running on android test: 161. two identical starts in a row

2016-08-15T15:38:34.990Z - info: Running on android test: 162. two different starts in a row

2016-08-15T15:38:35.401Z - info: Running on android test: 163. two stops and a start and two stops

2016-08-15T15:38:35.770Z - info: Running on android test: 164. we properly enqueue requests so no then needed

2016-08-15T15:38:36.093Z - info: Running on android test: 165. test calculateSeqPointKeyId

2016-08-15T15:38:36.318Z - info: Running on android test: 166. can create servers manager

2016-08-15T15:38:36.522Z - info: Running on android test: 167. calling stop without start causes error

2016-08-15T15:38:36.686Z - info: Running on android test: 168. can start/stop servers manager

2016-08-15T15:38:36.848Z - info: Running on android test: 169. starting twice resolves with listening port

2016-08-15T15:38:37.020Z - info: Running on android test: 170. terminateIncomingConnection will terminate a connection

2016-08-15T15:38:37.284Z - info: Running on android test: 171. terminate an Outgoing connection will terminate the server

2016-08-15T15:38:37.509Z - info: Running on android test: 172. terminate an Outgoing connection with wrong arguments is not harmful

2016-08-15T15:38:37.723Z - info: Running on android test: 173. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-08-15T15:38:37.972Z - info: Running on android test: 174. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-08-15T15:38:38.247Z - info: Running on android test: 175. messages with invalid location or USN should be ignored

2016-08-15T15:38:38.513Z - info: Running on android test: 176. verify that Thali-specific messages are filtered correctly

2016-08-15T15:38:38.753Z - info: Running on android test: 177. #startListeningForAdvertisements should fail if start not called

2016-08-15T15:38:38.963Z - info: Running on android test: 178. #startUpdateAdvertisingAndListening should fail if start not called

2016-08-15T15:38:39.217Z - info: Running on android test: 179. #start should fail if called twice in a row

2016-08-15T15:38:39.444Z - info: Running on android test: 180. should not be started after stop is called

2016-08-15T15:38:39.681Z - info: Running on android test: 181. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-08-15T15:38:39.900Z - info: Running on android test: 182. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-08-15T15:38:40.099Z - info: Running on android test: 183. #startUpdateAdvertisingAndListening should start hosting given router object

2016-08-15T15:38:40.398Z - info: Running on android test: 184. #startUpdateAdvertisingAndListening bad psk should be rejected object

2016-08-15T15:38:40.677Z - info: Running on android test: 185. #stop can be called multiple times in a row

2016-08-15T15:38:40.870Z - info: Running on android test: 186. #startListeningForAdvertisements can be called multiple times in a row

2016-08-15T15:38:41.083Z - info: Running on android test: 187. #stopListeningForAdvertisements can be called multiple times in a row

2016-08-15T15:38:41.277Z - info: Running on android test: 188. #stopAdvertisingAndListening can be called multiple times in a row

2016-08-15T15:38:41.578Z - info: Running on android test: 189. functions are run from a queue in the right order

2016-08-15T15:38:41.851Z - info: Running on android test: 190. does not get peer changes from self

2016-08-15T15:38:44.128Z - info: Running on android test: 191. #ThaliPeerPoolDefault - single action

2016-08-15T15:38:44.409Z - info: Running on android test: 192. #ThaliPeerPoolDefault - multiple actions

2016-08-15T15:38:44.686Z - info: Running on android test: 193. #ThaliPeerPoolDefault - PSK Pool works

2016-08-15T15:38:44.974Z - info: Running on android test: 194. #ThaliPeerPoolDefault - stop

2016-08-15T15:38:45.141Z - info: Test run on android complete

2016-08-15T15:38:45.143Z - info: 

-== UNIT TEST RESULTS ==-

2016-08-15T15:38:45.146Z - info: PLATFORM: android

2016-08-15T15:38:45.146Z - info: RESULT: FAIL

2016-08-15T15:38:45.148Z - info: 194 of 194 tests completed

2016-08-15T15:38:45.149Z - info: 191/194 passed (3 failures)

2016-08-15T15:38:45.150Z - info: 

--- Failed tests ---

2016-08-15T15:38:45.151Z - warn: 69. Client to server request coordinated - fail

2016-08-15T15:38:45.152Z - warn: 134. Coordinated pull replication from notification test - fail

2016-08-15T15:38:45.153Z - warn: 144. Coordinated replication action test - fail

2016-08-15T15:38:45.154Z - info: 

-== END ==-

2016-08-15T15:38:46.183Z - info: Socket to device motorola-Nexus 6 disconnected: transport close

2016-08-15T15:38:47.185Z - info: Socket to device samsung-SM-G900F disconnected: transport close


 
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
STOP log received from  0be0c6c6 Test has  FAILED
STOP log received from  ZX1G429CRK Test has  FAILED
Device test finished on ZX1G429CRK 
Device test finished on 0be0c6c6 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/81321942665e562_Fixed_thaliTestMobileNative_evabishchevich/thali01_motorola-Nexus 6.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/81321942665e562_Fixed_thaliTestMobileNative_evabishchevich/thali01_samsung-SM-G900F.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  LGD855a6933058 Test has  SUCCEEDED
Device test finished on LGD855a6933058 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/81321942665e562_Fixed_thaliTestMobileNative_evabishchevich/thali02_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/81321942665e562_Fixed_thaliTestMobileNative_evabishchevich/thali02_LGE-LG-D855.md)





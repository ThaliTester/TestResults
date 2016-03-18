#### Test 62548124b8ccb9f Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":7}}
2016-03-18T16:18:18.187Z - info: listening on *:3000

2016-03-18T16:18:18.763Z - debug: Device presented: samsung-SM-A300FU (android) unittest socket:1

2016-03-18T16:18:18.797Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:2

2016-03-18T16:18:18.800Z - info: Required number of android devices presented (2)

2016-03-18T16:18:18.803Z - info: Starting unit test run for platform: android

2016-03-18T16:18:18.831Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:0

2016-03-18T16:18:19.682Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-18T16:18:19.872Z - debug: Device presented: samsung-SM-A500FU (android) unittest socket:3

2016-03-18T16:18:19.876Z - info: Discarding surplus device: samsung-SM-A500FU

2016-03-18T16:18:20.480Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-18T16:18:20.649Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:4

2016-03-18T16:18:20.650Z - info: Required number of ios devices presented (2)

2016-03-18T16:18:20.651Z - info: Starting unit test run for platform: ios

2016-03-18T16:18:20.830Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-18T16:18:20.979Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:5

2016-03-18T16:18:20.980Z - info: Discarding surplus device: samsung-SM-N910C

2016-03-18T16:18:21.174Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-18T16:18:21.201Z - info: Running on android test: 4. native server connections all up

2016-03-18T16:18:21.497Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-18T16:18:21.565Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-18T16:18:21.866Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-18T16:18:21.871Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-18T16:18:22.022Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:6

2016-03-18T16:18:22.023Z - info: Discarding surplus device: Apple-IpadAir2-1

2016-03-18T16:18:22.207Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-18T16:18:22.266Z - info: Running on ios test: 4. native server connections all up

2016-03-18T16:18:22.276Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:7

2016-03-18T16:18:22.277Z - info: Discarding surplus device: Apple-Iphone5-1

2016-03-18T16:18:22.548Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-18T16:18:22.705Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-18T16:18:22.893Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-18T16:18:23.159Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-18T16:18:23.517Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-18T16:18:23.718Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-18T16:18:23.986Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-18T16:18:24.021Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-18T16:18:24.380Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-18T16:18:24.386Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-18T16:18:24.450Z - debug: Socket disconnected: transport close 6 (Apple-IpadAir2-1)

2016-03-18T16:18:24.645Z - info: Running on android test: 13. closeAll with promise

2016-03-18T16:18:24.857Z - info: Running on android test: 14. multiplex can send data

2016-03-18T16:18:25.165Z - info: Running on android test: 15. enqueue and run in order

2016-03-18T16:18:25.351Z - debug: Socket disconnected: transport close 7 (Apple-Iphone5-1)

2016-03-18T16:18:25.425Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-18T16:18:25.918Z - info: Running on android test: 16. enqueueAtTop and run backwards

2016-03-18T16:18:26.012Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-18T16:18:26.499Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-18T16:18:26.936Z - info: Running on ios test: 13. closeAll with promise

2016-03-18T16:18:26.968Z - info: Running on android test: 17. mix enqueue and enqueueAtTop

2016-03-18T16:18:27.449Z - info: Running on ios test: 14. multiplex can send data

2016-03-18T16:18:27.749Z - info: Running on android test: 18. queues handled independently

2016-03-18T16:18:27.818Z - info: Running on ios test: 15. enqueue and run in order

2016-03-18T16:18:28.258Z - info: Running on android test: 19. basic

2016-03-18T16:18:28.377Z - info: Running on ios test: 16. enqueueAtTop and run backwards

2016-03-18T16:18:28.548Z - info: Running on android test: 20. another

2016-03-18T16:18:28.696Z - info: Running on ios test: 17. mix enqueue and enqueueAtTop

2016-03-18T16:18:28.926Z - info: Running on android test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-18T16:18:29.153Z - info: Running on ios test: 18. queues handled independently

2016-03-18T16:18:29.313Z - info: Running on android test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-18T16:18:29.602Z - info: Running on ios test: 19. basic

2016-03-18T16:18:29.686Z - info: Running on android test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-18T16:18:29.971Z - info: Running on ios test: 20. another

2016-03-18T16:18:30.071Z - info: Running on android test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-18T16:18:30.425Z - info: Running on ios test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-18T16:18:30.592Z - info: Running on android test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-18T16:18:30.741Z - info: Running on ios test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-18T16:18:31.064Z - info: Running on ios test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-18T16:18:31.224Z - info: Running on android test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-18T16:18:31.453Z - info: Running on ios test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-18T16:18:31.570Z - info: Running on android test: 27. #start should fail if called twice in a row

2016-03-18T16:18:31.974Z - info: Running on ios test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-18T16:18:32.035Z - info: Running on android test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-18T16:18:32.685Z - info: Running on android test: 29. does not send duplicate availability changes

2016-03-18T16:18:33.855Z - info: Running on android test: 30. can get the network status

2016-03-18T16:18:33.872Z - info: Running on ios test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-18T16:18:34.225Z - info: Running on android test: 31. wifi peer is marked unavailable if announcements stop

2016-03-18T16:18:34.659Z - info: Running on ios test: 27. #start should fail if called twice in a row

2016-03-18T16:18:35.152Z - info: Running on ios test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-18T16:18:35.564Z - info: Running on android test: 32. Can call start/stopListeningForAdvertisements

2016-03-18T16:18:35.719Z - info: Running on ios test: 29. does not send duplicate availability changes

2016-03-18T16:18:35.925Z - info: Running on android test: 33. Calling startListeningForAdvertisements twice is NOT an error

2016-03-18T16:18:36.203Z - info: Running on ios test: 30. can get the network status

2016-03-18T16:18:36.336Z - info: Running on android test: 34. Can call start/stopUpdateAdvertisingAndListening

2016-03-18T16:18:36.708Z - info: Running on ios test: 31. wifi peer is marked unavailable if announcements stop

2016-03-18T16:18:36.712Z - info: Running on android test: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-18T16:18:39.339Z - info: Running on android test: 36. peerAvailabilityChange is called

2016-03-18T16:18:42.652Z - info: Running on ios test: 32. Can call start/stopListeningForAdvertisements

2016-03-18T16:18:45.277Z - info: Running on android test: 37. Can connect to a remote peer

2016-03-18T16:18:46.093Z - info: Running on ios test: 33. Calling startListeningForAdvertisements twice is NOT an error

2016-03-18T16:18:46.917Z - info: Running on ios test: 34. Can call start/stopUpdateAdvertisingAndListening

2016-03-18T16:18:47.899Z - info: Running on ios test: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-18T16:18:49.027Z - info: Running on ios test: 36. peerAvailabilityChange is called

2016-03-18T16:18:59.934Z - info: Running on ios test: 37. Can connect to a remote peer

2016-03-18T16:20:23.115Z - info: Running on android test: 38. Can shift large amounts of data

2016-03-18T16:20:48.192Z - info: Running on ios test: 38. Can shift large amounts of data

2016-03-18T16:21:57.074Z - info: Running on ios test: 39. #startListeningForAdvertisements should fail if start not called

2016-03-18T16:21:58.538Z - info: Running on ios test: 40. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-18T16:21:58.680Z - info: Running on android test: 39. #startListeningForAdvertisements should fail if start not called

2016-03-18T16:21:58.869Z - info: Running on ios test: 41. should be able to call #stopListeningForAdvertisements many times

2016-03-18T16:21:59.049Z - info: Running on android test: 40. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-18T16:21:59.530Z - info: Running on ios test: 42. should be able to call #startListeningForAdvertisements many times

2016-03-18T16:21:59.539Z - info: Running on android test: 41. should be able to call #stopListeningForAdvertisements many times

2016-03-18T16:21:59.889Z - info: Running on android test: 42. should be able to call #startListeningForAdvertisements many times

2016-03-18T16:21:59.909Z - info: Running on ios test: 43. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-18T16:22:00.632Z - info: Running on ios test: 44. should be able to call #stopAdvertisingAndListening many times

2016-03-18T16:22:00.635Z - info: Running on android test: 43. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-18T16:22:01.261Z - info: Running on ios test: 45. can get the network status before starting

2016-03-18T16:22:01.560Z - info: Running on android test: 44. should be able to call #stopAdvertisingAndListening many times

2016-03-18T16:22:01.741Z - info: Running on ios test: 46. error returned with bad router

2016-03-18T16:22:02.012Z - info: Running on android test: 45. can get the network status before starting

2016-03-18T16:22:02.420Z - info: Running on android test: 46. error returned with bad router

2016-03-18T16:22:03.268Z - info: Running on ios test: 47. can do HTTP requests between peers

2016-03-18T16:22:04.255Z - info: Running on android test: 47. can do HTTP requests between peers

2016-03-18T16:22:10.458Z - info: Running on ios test: 48. Can do requests between peers after start and stop

2016-03-18T16:22:11.222Z - info: Running on ios test: 49. We successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-18T16:22:12.245Z - info: Running on ios test: 50. Test BEACONS_RETRIEVED_AND_PARSED locally

2016-03-18T16:22:13.823Z - info: Running on ios test: 51. Test HTTP_BAD_RESPONSE locally

2016-03-18T16:22:14.322Z - info: Running on android test: 48. Can do requests between peers after start and stop

2016-03-18T16:22:14.790Z - info: Running on android test: 49. We successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-18T16:22:14.801Z - info: Running on ios test: 52. Test NETWORK_PROBLEM locally

2016-03-18T16:22:15.010Z - info: Running on android test: 50. Test BEACONS_RETRIEVED_AND_PARSED locally

2016-03-18T16:22:15.986Z - info: Running on android test: 51. Test HTTP_BAD_RESPONSE locally

2016-03-18T16:22:16.664Z - info: Running on android test: 52. Test NETWORK_PROBLEM locally

2016-03-18T16:22:17.573Z - info: Running on android test: 53. Test timeout locally

2016-03-18T16:22:19.218Z - info: Running on android test: 54. Call the start two times

2016-03-18T16:22:19.237Z - info: Running on ios test: 53. Test timeout locally

2016-03-18T16:22:19.769Z - info: Running on android test: 55. Call the kill before calling the start

2016-03-18T16:22:20.199Z - info: Running on android test: 56. Call the kill immediately after the start

2016-03-18T16:22:20.630Z - info: Running on android test: 57. Call the kill while waiting a response from the server

2016-03-18T16:22:21.812Z - info: Running on ios test: 54. Call the start two times

2016-03-18T16:22:23.381Z - info: Running on android test: 58. Test to exceed the max content size locally

2016-03-18T16:22:23.779Z - info: Running on ios test: 55. Call the kill before calling the start

2016-03-18T16:22:24.336Z - info: Running on android test: 59. Close the server socket while the client is waiting a response from the server. Local test.

2016-03-18T16:22:26.785Z - info: Running on ios test: 56. Call the kill immediately after the start

2016-03-18T16:22:29.007Z - info: Running on android test: 60. Close the client socket while the client is waiting a response from the server. Local test.

2016-03-18T16:22:30.313Z - info: Running on ios test: 57. Call the kill while waiting a response from the server

2016-03-18T16:22:31.539Z - info: Running on android test: 61. #generatePreambleAndBeacons bad args

2016-03-18T16:22:31.861Z - info: Running on android test: 62. #generatePreambleAndBeacons empty keys to notify

2016-03-18T16:22:32.157Z - info: Running on android test: 63. #generatePreambleAndBeacons multiple keys to notify

2016-03-18T16:22:32.728Z - info: Running on android test: 64. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-18T16:22:33.065Z - info: Running on android test: 65. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-18T16:22:33.962Z - info: Running on android test: 66. #parseBeacons expiration out of range lower

2016-03-18T16:22:34.035Z - info: Running on ios test: 58. Test to exceed the max content size locally

2016-03-18T16:22:35.766Z - info: Running on android test: 67. #parseBeacons expiration out of range lower

2016-03-18T16:22:36.520Z - info: Running on android test: 68. #parseBeacons no beacons returns null

2016-03-18T16:22:36.803Z - info: Running on android test: 69. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-18T16:22:37.140Z - info: Running on android test: 70. #parseBeacons addressBookCallback fails decrypt

2016-03-18T16:22:37.586Z - info: Running on android test: 71. #parseBeacons addressBookCallback returns no matches

2016-03-18T16:22:37.959Z - info: Running on android test: 72. #parseBeacons addressBookCallback returns spurious match

2016-03-18T16:22:37.963Z - info: Running on ios test: 59. Close the server socket while the client is waiting a response from the server. Local test.

2016-03-18T16:22:38.398Z - info: Running on android test: 73. #parseBeacons addressBookCallback returns public key

2016-03-18T16:22:38.854Z - info: Running on android test: 74. validate generatePskIdentityField

2016-03-18T16:22:39.115Z - info: Running on android test: 75. validate generatePskSecret

2016-03-18T16:22:39.418Z - info: Running on android test: 76. Start and stop ThaliNotificationServer

2016-03-18T16:22:39.914Z - info: Running on android test: 77. Pass an empty array to ThaliNotificationServer.start

2016-03-18T16:22:40.283Z - info: Running on android test: 78. Pass a string to ThaliNotificationServer.start

2016-03-18T16:22:40.488Z - info: Running on ios test: 60. Close the client socket while the client is waiting a response from the server. Local test.

2016-03-18T16:22:40.692Z - info: Running on android test: 79. Pass an empty parameter to ThaliNotificationServer.start

2016-03-18T16:22:41.067Z - info: Running on android test: 80. Make an HTTP request to /NotificationBeacons

2016-03-18T16:22:41.596Z - info: Running on android test: 81. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-18T16:22:41.963Z - info: Running on android test: 82. Make an HTTP request to /NotificationBeaconsbefore calling start

2016-03-18T16:22:42.372Z - info: Running on android test: 83. #testThaliPeerAction - test getters

2016-03-18T16:22:42.664Z - info: Running on android test: 84. #testThaliPeerAction - start and kill

2016-03-18T16:22:42.966Z - info: Running on android test: 85. #testThaliPeerAction - double start

2016-03-18T16:22:42.975Z - info: Running on ios test: 61. #generatePreambleAndBeacons bad args

2016-03-18T16:22:43.293Z - info: Running on android test: 86. #testThaliPeerAction - start after kill

2016-03-18T16:22:43.336Z - info: Running on ios test: 62. #generatePreambleAndBeacons empty keys to notify

2016-03-18T16:22:43.646Z - info: Running on android test: 87. #testThaliPeerAction - make sure ids are unique

2016-03-18T16:22:43.809Z - info: Running on ios test: 63. #generatePreambleAndBeacons multiple keys to notify

2016-03-18T16:22:44.004Z - info: Running on android test: 88. Test PeerConnectionInformation basics

2016-03-18T16:22:44.346Z - info: Running on ios test: 64. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-18T16:22:44.431Z - info: Running on android test: 89. Test PeerDictionary basic functionality

2016-03-18T16:22:44.728Z - info: Running on ios test: 65. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-18T16:22:44.841Z - info: Running on android test: 90. Test PeerDictionary with multiple entries.

2016-03-18T16:22:45.464Z - info: Running on ios test: 66. #parseBeacons expiration out of range lower

2016-03-18T16:22:45.820Z - info: Running on ios test: 67. #parseBeacons expiration out of range lower

2016-03-18T16:22:46.127Z - info: Running on ios test: 68. #parseBeacons no beacons returns null

2016-03-18T16:22:46.424Z - info: Running on ios test: 69. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-18T16:22:46.759Z - info: Running on ios test: 70. #parseBeacons addressBookCallback fails decrypt

2016-03-18T16:22:47.193Z - info: Running on ios test: 71. #parseBeacons addressBookCallback returns no matches

2016-03-18T16:22:47.552Z - info: Running on ios test: 72. #parseBeacons addressBookCallback returns spurious match

2016-03-18T16:22:47.886Z - info: Running on android test: 91. RESOLVED entries are removed before WAITING state entry.

2016-03-18T16:22:47.891Z - info: Running on ios test: 73. #parseBeacons addressBookCallback returns public key

2016-03-18T16:22:48.207Z - info: Running on ios test: 74. validate generatePskIdentityField

2016-03-18T16:22:48.526Z - info: Running on ios test: 75. validate generatePskSecret

2016-03-18T16:22:48.911Z - info: Running on ios test: 76. Start and stop ThaliNotificationServer

2016-03-18T16:22:49.299Z - info: Running on ios test: 77. Pass an empty array to ThaliNotificationServer.start

2016-03-18T16:22:49.421Z - info: Running on android test: 92. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-18T16:22:49.657Z - info: Running on ios test: 78. Pass a string to ThaliNotificationServer.start

2016-03-18T16:22:49.987Z - info: Running on ios test: 79. Pass an empty parameter to ThaliNotificationServer.start

2016-03-18T16:22:50.359Z - info: Running on ios test: 80. Make an HTTP request to /NotificationBeacons

2016-03-18T16:22:50.815Z - info: Running on android test: 93. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-18T16:22:50.862Z - info: Running on ios test: 81. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-18T16:22:51.383Z - info: Running on ios test: 82. Make an HTTP request to /NotificationBeaconsbefore calling start

2016-03-18T16:22:51.781Z - info: Running on ios test: 83. #testThaliPeerAction - test getters

2016-03-18T16:22:52.077Z - info: Running on ios test: 84. #testThaliPeerAction - start and kill

2016-03-18T16:22:52.399Z - info: Running on ios test: 85. #testThaliPeerAction - double start

2016-03-18T16:22:52.572Z - info: Running on android test: 94. #ThaliPeerPoolInterface - bad enqueues

2016-03-18T16:22:52.732Z - info: Running on ios test: 86. #testThaliPeerAction - start after kill

2016-03-18T16:22:53.109Z - info: Running on ios test: 87. #testThaliPeerAction - make sure ids are unique

2016-03-18T16:22:53.492Z - info: Running on ios test: 88. Test PeerConnectionInformation basics

2016-03-18T16:22:53.609Z - info: Running on android test: 95. #ThaliPeerPoolInterface - do not allow same object type

2016-03-18T16:22:53.874Z - info: Running on ios test: 89. Test PeerDictionary basic functionality

2016-03-18T16:22:54.010Z - info: Running on android test: 96. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-18T16:22:54.283Z - info: Running on android test: 97. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent

2016-03-18T16:22:54.600Z - info: Running on android test: 98. compareBufferArrays

2016-03-18T16:22:54.807Z - info: Running on ios test: 90. Test PeerDictionary with multiple entries.

2016-03-18T16:22:54.832Z - info: Running on android test: 99. Call start twice and get error

2016-03-18T16:22:55.160Z - info: Running on android test: 100. Start and make sure it runs

2016-03-18T16:22:55.418Z - info: Running on android test: 101. Make sure getTimeWhenRun is right after start

2016-03-18T16:22:55.676Z - info: Running on android test: 102. Make sure getTimeWhenRun is -1 after function is called

2016-03-18T16:22:55.979Z - info: Running on android test: 103. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-18T16:22:56.267Z - info: Running on ios test: 91. RESOLVED entries are removed before WAITING state entry.

2016-03-18T16:22:56.270Z - info: Running on android test: 104. Test TransientState

2016-03-18T16:22:56.488Z - info: Running on android test: 105. No peers and empty database

2016-03-18T16:22:57.237Z - info: Running on ios test: 92. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-18T16:22:57.273Z - info: Running on android test: 106. One peer and empty DB

2016-03-18T16:22:57.700Z - info: Running on android test: 107. One peer with _Local set behind current seq

2016-03-18T16:22:58.046Z - info: Running on ios test: 93. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-18T16:22:58.164Z - info: Running on android test: 108. One peer with _Local set equal to current seq

2016-03-18T16:22:58.924Z - info: Running on android test: 109. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-18T16:22:58.955Z - info: Running on ios test: 94. #ThaliPeerPoolInterface - bad enqueues

2016-03-18T16:23:00.023Z - info: Running on android test: 110. Three peers, one not in DB, one behind and one ahead

2016-03-18T16:23:00.790Z - info: Running on android test: 111. More than maximum peers, make sure we only send maximum allowed

2016-03-18T16:23:01.692Z - info: Running on ios test: 95. #ThaliPeerPoolInterface - do not allow same object type

2016-03-18T16:23:02.082Z - info: Running on ios test: 96. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-18T16:23:02.189Z - info: Running on android test: 112. two peers with empty DB, update the doc

2016-03-18T16:23:02.433Z - info: Running on ios test: 97. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent

2016-03-18T16:23:02.760Z - info: Running on ios test: 98. compareBufferArrays

2016-03-18T16:23:02.913Z - info: Running on android test: 113. add doc and make sure tokens refresh when they expire

2016-03-18T16:23:03.109Z - info: Running on ios test: 99. Call start twice and get error

2016-03-18T16:23:03.354Z - info: Running on ios test: 100. Start and make sure it runs

2016-03-18T16:23:03.619Z - info: Running on ios test: 101. Make sure getTimeWhenRun is right after start

2016-03-18T16:23:03.771Z - info: Running on android test: 114. start and stop and start and stop

2016-03-18T16:23:03.856Z - info: Running on ios test: 102. Make sure getTimeWhenRun is -1 after function is called

2016-03-18T16:23:04.068Z - info: Running on ios test: 103. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-18T16:23:04.308Z - info: Running on android test: 115. two identical starts in a row

2016-03-18T16:23:04.385Z - info: Running on ios test: 104. Test TransientState

2016-03-18T16:23:04.699Z - info: Running on ios test: 105. No peers and empty database

2016-03-18T16:23:04.803Z - info: Running on android test: 116. two different starts in a row

2016-03-18T16:23:05.206Z - info: Running on ios test: 106. One peer and empty DB

2016-03-18T16:23:05.505Z - info: Running on android test: 117. two stops and a start and two stops

2016-03-18T16:23:05.902Z - info: Running on ios test: 107. One peer with _Local set behind current seq

2016-03-18T16:23:05.986Z - info: Running on android test: 118. we properly enqueue requests so no then needed

2016-03-18T16:23:06.449Z - info: Running on android test: 119. test calculateSeqPointKeyId

2016-03-18T16:23:06.452Z - info: Running on ios test: 108. One peer with _Local set equal to current seq

2016-03-18T16:23:06.688Z - info: Running on android test: 120. can create servers manager

2016-03-18T16:23:06.948Z - info: Running on ios test: 109. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-18T16:23:06.976Z - info: Running on android test: 121. calling stop without start causes error

2016-03-18T16:23:07.244Z - info: Running on android test: 122. can start/stop servers manager

2016-03-18T16:23:07.512Z - info: Running on ios test: 110. Three peers, one not in DB, one behind and one ahead

2016-03-18T16:23:07.569Z - info: Running on android test: 123. starting twice resolves with listening port

2016-03-18T16:23:07.937Z - info: Running on android test: 124. terminateIncomingConnection will terminate a connection

2016-03-18T16:23:08.379Z - info: Running on ios test: 111. More than maximum peers, make sure we only send maximum allowed

2016-03-18T16:23:08.609Z - info: Running on android test: 125. terminate an Outgoing connection will terminate the server

2016-03-18T16:23:09.049Z - info: Running on android test: 126. terminate an Outgoing connection with wrong arguments is not harmful

2016-03-18T16:23:09.379Z - info: Running on android test: 127. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-18T16:23:09.777Z - info: Running on android test: 128. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-18T16:23:09.845Z - info: Running on ios test: 112. two peers with empty DB, update the doc

2016-03-18T16:23:10.276Z - info: Running on android test: 129. messages with invalid location or USN should be ignored

2016-03-18T16:23:10.554Z - info: Running on ios test: 113. add doc and make sure tokens refresh when they expire

2016-03-18T16:23:10.875Z - info: Running on android test: 130. verify that Thali-specific messages are filtered correctly

2016-03-18T16:23:11.318Z - info: Running on android test: 131. #startListeningForAdvertisements should fail if start not called

2016-03-18T16:23:11.682Z - info: Running on android test: 132. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-18T16:23:12.015Z - info: Running on android test: 133. #start should fail if called twice in a row

2016-03-18T16:23:12.194Z - info: Running on ios test: 114. start and stop and start and stop

2016-03-18T16:23:12.456Z - info: Running on android test: 134. should not be started after stop is called

2016-03-18T16:23:12.913Z - info: Running on android test: 135. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-18T16:23:13.438Z - info: Running on android test: 136. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-18T16:23:13.813Z - info: Running on android test: 137. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-18T16:23:13.820Z - info: Running on ios test: 115. two identical starts in a row

2016-03-18T16:23:14.076Z - info: Running on android test: 138. #stop can be called multiple times in a row

2016-03-18T16:23:14.288Z - info: Running on ios test: 116. two different starts in a row

2016-03-18T16:23:14.377Z - info: Running on android test: 139. #startListeningForAdvertisements can be called multiple times in a row

2016-03-18T16:23:14.697Z - info: Running on android test: 140. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-18T16:23:14.938Z - info: Running on ios test: 117. two stops and a start and two stops

2016-03-18T16:23:15.062Z - info: Running on android test: 141. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-18T16:23:15.337Z - info: Running on android test: 142. functions are run from a queue in the right order

2016-03-18T16:23:15.413Z - info: Running on ios test: 118. we properly enqueue requests so no then needed

2016-03-18T16:23:15.631Z - info: Running on android test: 143. #ThaliPeerPoolDefault - single action

2016-03-18T16:23:15.987Z - info: Running on ios test: 119. test calculateSeqPointKeyId

2016-03-18T16:23:15.991Z - info: Running on android test: 144. #ThaliPeerPoolDefault - multiple actions

2016-03-18T16:23:16.345Z - info: Running on ios test: 120. can create servers manager

2016-03-18T16:23:16.349Z - info: Test run on android complete

2016-03-18T16:23:16.351Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-18T16:23:16.354Z - info: PLATFORM: android

2016-03-18T16:23:16.354Z - info: RESULT: FAIL

2016-03-18T16:23:16.356Z - info: 144 of 144 tests completed

2016-03-18T16:23:16.356Z - info: 141/144 passed (3 failures)

2016-03-18T16:23:16.357Z - info: --- Test Details ---



2016-03-18T16:23:16.359Z - info: 1. calling createNativeListener directly rejects - pass

2016-03-18T16:23:16.363Z - info: 2. emits incomingConnectionState - pass

2016-03-18T16:23:16.364Z - info: 3. emits routerPortConnectionFailed - pass

2016-03-18T16:23:16.365Z - info: 4. native server connections all up - pass
2016-03-18T16:23:16.366Z - info: 5. native server - closing incoming stream cleans outgoing socket - pass

2016-03-18T16:23:16.367Z - info: 6. native server - closing incoming connection cleans outgoing socket - pass

2016-03-18T16:23:16.367Z - info: 7. native server - closing outgoing socket cleans associated mux stream - pass

2016-03-18T16:23:16.368Z - info: 8. native server - closing the whole server cleans everything up - pass

2016-03-18T16:23:16.369Z - info: 9. native server - we can get a ton of connections and data through and still clean up the server completely - pass
2016-03-18T16:23:16.370Z - info: 10. native server - simulate mux failure, make sure everything is cleaned up - pass

2016-03-18T16:23:16.371Z - info: 11. native server - timing out the incoming connection cleans everything up - pass

2016-03-18T16:23:16.372Z - info: 12. closeAll can close even when connections open - pass

2016-03-18T16:23:16.372Z - info: 13. closeAll with promise - pass

2016-03-18T16:23:16.373Z - info: 14. multiplex can send data - pass
2016-03-18T16:23:16.374Z - info: 15. enqueue and run in order - pass

2016-03-18T16:23:16.375Z - info: 16. enqueueAtTop and run backwards - pass

2016-03-18T16:23:16.376Z - info: 17. mix enqueue and enqueueAtTop - pass

2016-03-18T16:23:16.377Z - info: 18. queues handled independently - pass

2016-03-18T16:23:16.377Z - info: 19. basic - pass

2016-03-18T16:23:16.378Z - info: 20. another - pass
2016-03-18T16:23:16.379Z - info: 21. #startListeningForAdvertisements should fail if start not called - pass

2016-03-18T16:23:16.380Z - info: 22. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-18T16:23:16.381Z - info: 23. should be able to call #stopListeningForAdvertisements many times - pass

2016-03-18T16:23:16.382Z - info: 24. should be able to call #startListeningForAdvertisements many times - pass

2016-03-18T16:23:16.383Z - info: 25. should be able to call #startUpdateAdvertisingAndListening many times - pass

2016-03-18T16:23:16.384Z - info: 26. should be able to call #stopAdvertisingAndListening many times - pass
2016-03-18T16:23:16.384Z - info: 27. #start should fail if called twice in a row - pass

2016-03-18T16:23:16.385Z - info: 28. does not emit duplicate discoveryAdvertisingStateUpdate - pass

2016-03-18T16:23:16.386Z - info: 29. does not send duplicate availability changes - pass

2016-03-18T16:23:16.387Z - info: 30. can get the network status - pass

2016-03-18T16:23:16.388Z - info: 31. wifi peer is marked unavailable if announcements stop - pass
2016-03-18T16:23:16.389Z - info: 32. Can call start/stopListeningForAdvertisements - pass

2016-03-18T16:23:16.389Z - info: 33. Calling startListeningForAdvertisements twice is NOT an error - pass

2016-03-18T16:23:16.390Z - info: 34. Can call start/stopUpdateAdvertisingAndListening - pass

2016-03-18T16:23:16.391Z - info: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error - pass

2016-03-18T16:23:16.392Z - info: 36. peerAvailabilityChange is called - pass
2016-03-18T16:23:16.393Z - info: 37. Can connect to a remote peer - fail

2016-03-18T16:23:16.393Z - info: 38. Can shift large amounts of data - fail

2016-03-18T16:23:16.394Z - info: 39. #startListeningForAdvertisements should fail if start not called - pass

2016-03-18T16:23:16.395Z - info: 40. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-18T16:23:16.396Z - info: 41. should be able to call #stopListeningForAdvertisements many times - pass

2016-03-18T16:23:16.397Z - info: 42. should be able to call #startListeningForAdvertisements many times - pass
2016-03-18T16:23:16.398Z - info: 43. should be able to call #startUpdateAdvertisingAndListening many times - pass

2016-03-18T16:23:16.399Z - info: 44. should be able to call #stopAdvertisingAndListening many times - pass

2016-03-18T16:23:16.400Z - info: 45. can get the network status before starting - pass

2016-03-18T16:23:16.400Z - info: 46. error returned with bad router - pass

2016-03-18T16:23:16.401Z - info: 47. can do HTTP requests between peers - fail

2016-03-18T16:23:16.402Z - info: 48. Can do requests between peers after start and stop - pass

2016-03-18T16:23:16.403Z - info: 49. We successfully receive and replay discoveryAdvertisingStateUpdate - pass

2016-03-18T16:23:16.404Z - info: 50. Test BEACONS_RETRIEVED_AND_PARSED locally - pass

2016-03-18T16:23:16.405Z - info: 51. Test HTTP_BAD_RESPONSE locally - pass

2016-03-18T16:23:16.406Z - info: 52. Test NETWORK_PROBLEM locally - pass

2016-03-18T16:23:16.407Z - info: 53. Test timeout locally - pass

2016-03-18T16:23:16.408Z - info: 54. Call the start two times - pass

2016-03-18T16:23:16.409Z - info: 55. Call the kill before calling the start - pass

2016-03-18T16:23:16.410Z - info: 56. Call the kill immediately after the start - pass

2016-03-18T16:23:16.410Z - info: 57. Call the kill while waiting a response from the server - pass

2016-03-18T16:23:16.411Z - info: 58. Test to exceed the max content size locally - pass

2016-03-18T16:23:16.412Z - info: 59. Close the server socket while the client is waiting a response from the server. Local test. - pass

2016-03-18T16:23:16.413Z - info: 60. Close the client socket while the client is waiting a response from the server. Local test. - pass

2016-03-18T16:23:16.414Z - info: 61. #generatePreambleAndBeacons bad args - pass

2016-03-18T16:23:16.415Z - info: 62. #generatePreambleAndBeacons empty keys to notify - pass

2016-03-18T16:23:16.416Z - info: 63. #generatePreambleAndBeacons multiple keys to notify - pass

2016-03-18T16:23:16.417Z - info: 64. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass

2016-03-18T16:23:16.418Z - info: 65. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass

2016-03-18T16:23:16.419Z - info: 66. #parseBeacons expiration out of range lower - pass

2016-03-18T16:23:16.420Z - info: 67. #parseBeacons expiration out of range lower - pass

2016-03-18T16:23:16.420Z - info: 68. #parseBeacons no beacons returns null - pass

2016-03-18T16:23:16.421Z - info: 69. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass

2016-03-18T16:23:16.422Z - info: 70. #parseBeacons addressBookCallback fails decrypt - pass

2016-03-18T16:23:16.423Z - info: 71. #parseBeacons addressBookCallback returns no matches - pass

2016-03-18T16:23:16.424Z - info: 72. #parseBeacons addressBookCallback returns spurious match - pass

2016-03-18T16:23:16.425Z - info: 73. #parseBeacons addressBookCallback returns public key - pass

2016-03-18T16:23:16.426Z - info: 74. validate generatePskIdentityField - pass

2016-03-18T16:23:16.427Z - info: 75. validate generatePskSecret - pass

2016-03-18T16:23:16.428Z - info: 76. Start and stop ThaliNotificationServer - pass

2016-03-18T16:23:16.429Z - info: 77. Pass an empty array to ThaliNotificationServer.start - pass

2016-03-18T16:23:16.430Z - info: 78. Pass a string to ThaliNotificationServer.start - pass

2016-03-18T16:23:16.431Z - info: 79. Pass an empty parameter to ThaliNotificationServer.start - pass

2016-03-18T16:23:16.431Z - info: 80. Make an HTTP request to /NotificationBeacons - pass

2016-03-18T16:23:16.432Z - info: 81. Make an HTTP request to /NotificationBeacons (no keys) - pass

2016-03-18T16:23:16.433Z - info: 82. Make an HTTP request to /NotificationBeaconsbefore calling start - pass

2016-03-18T16:23:16.434Z - info: 83. #testThaliPeerAction - test getters - pass

2016-03-18T16:23:16.435Z - info: 84. #testThaliPeerAction - start and kill - pass

2016-03-18T16:23:16.436Z - info: 85. #testThaliPeerAction - double start - pass

2016-03-18T16:23:16.437Z - info: 86. #testThaliPeerAction - start after kill - pass

2016-03-18T16:23:16.438Z - info: 87. #testThaliPeerAction - make sure ids are unique - pass

2016-03-18T16:23:16.441Z - info: 88. Test PeerConnectionInformation basics - pass

2016-03-18T16:23:16.442Z - info: 89. Test PeerDictionary basic functionality - pass

2016-03-18T16:23:16.444Z - info: 90. Test PeerDictionary with multiple entries. - pass

2016-03-18T16:23:16.445Z - info: 91. RESOLVED entries are removed before WAITING state entry. - pass

2016-03-18T16:23:16.446Z - info: 92. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass

2016-03-18T16:23:16.453Z - info: 93. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass

2016-03-18T16:23:16.454Z - info: 94. #ThaliPeerPoolInterface - bad enqueues - pass
2016-03-18T16:23:16.456Z - info: 95. #ThaliPeerPoolInterface - do not allow same object type - pass
2016-03-18T16:23:16.456Z - info: 96. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass
2016-03-18T16:23:16.457Z - info: 97. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent - pass
2016-03-18T16:23:16.457Z - info: 98. compareBufferArrays - pass
2016-03-18T16:23:16.458Z - info: 99. Call start twice and get error - pass

2016-03-18T16:23:16.458Z - info: 100. Start and make sure it runs - pass
2016-03-18T16:23:16.459Z - info: 101. Make sure getTimeWhenRun is right after start - pass
2016-03-18T16:23:16.459Z - info: 102. Make sure getTimeWhenRun is -1 after function is called - pass
2016-03-18T16:23:16.460Z - info: 103. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass

2016-03-18T16:23:16.495Z - info: 104. Test TransientState - pass

2016-03-18T16:23:16.496Z - info: 105. No peers and empty database - pass

2016-03-18T16:23:16.499Z - info: 106. One peer and empty DB - pass

2016-03-18T16:23:16.500Z - info: 107. One peer with _Local set behind current seq - pass

2016-03-18T16:23:16.500Z - info: 108. One peer with _Local set equal to current seq - pass
2016-03-18T16:23:16.501Z - info: 109. One peer with _Local set ahead of current seq (and no this should not happen) - pass
2016-03-18T16:23:16.502Z - info: 110. Three peers, one not in DB, one behind and one ahead - pass
2016-03-18T16:23:16.502Z - info: 111. More than maximum peers, make sure we only send maximum allowed - pass
2016-03-18T16:23:16.503Z - info: 112. two peers with empty DB, update the doc - pass
2016-03-18T16:23:16.503Z - info: 113. add doc and make sure tokens refresh when they expire - pass
2016-03-18T16:23:16.504Z - info: 114. start and stop and start and stop - pass
2016-03-18T16:23:16.504Z - info: 115. two identical starts in a row - pass
2016-03-18T16:23:16.505Z - info: 116. two different starts in a row - pass
2016-03-18T16:23:16.506Z - info: 117. two stops and a start and two stops - pass
2016-03-18T16:23:16.506Z - info: 118. we properly enqueue requests so no then needed - pass
2016-03-18T16:23:16.507Z - info: 119. test calculateSeqPointKeyId - pass
2016-03-18T16:23:16.507Z - info: 120. can create servers manager - pass
2016-03-18T16:23:16.508Z - info: 121. calling stop without start causes error - pass
2016-03-18T16:23:16.508Z - info: 122. can start/stop servers manager - pass
2016-03-18T16:23:16.509Z - info: 123. starting twice resolves with listening port - pass
2016-03-18T16:23:16.509Z - info: 124. terminateIncomingConnection will terminate a connection - pass
2016-03-18T16:23:16.510Z - info: 125. terminate an Outgoing connection will terminate the server - pass
2016-03-18T16:23:16.510Z - info: 126. terminate an Outgoing connection with wrong arguments is not harmful - pass
2016-03-18T16:23:16.511Z - info: 127. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass
2016-03-18T16:23:16.511Z - info: 128. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass
2016-03-18T16:23:16.512Z - info: 129. messages with invalid location or USN should be ignored - pass
2016-03-18T16:23:16.512Z - info: 130. verify that Thali-specific messages are filtered correctly - pass
2016-03-18T16:23:16.513Z - info: 131. #startListeningForAdvertisements should fail if start not called - pass
2016-03-18T16:23:16.513Z - info: 132. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-18T16:23:16.514Z - info: 133. #start should fail if called twice in a row - pass
2016-03-18T16:23:16.514Z - info: 134. should not be started after stop is called - pass
2016-03-18T16:23:16.515Z - info: 135. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass
2016-03-18T16:23:16.515Z - info: 136. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass
2016-03-18T16:23:16.516Z - info: 137. #startUpdateAdvertisingAndListening should start hosting given router object - pass
2016-03-18T16:23:16.516Z - info: 138. #stop can be called multiple times in a row - pass
2016-03-18T16:23:16.517Z - info: 139. #startListeningForAdvertisements can be called multiple times in a row - pass
2016-03-18T16:23:16.517Z - info: 140. #stopListeningForAdvertisements can be called multiple times in a row - pass
2016-03-18T16:23:16.518Z - info: 141. #stopAdvertisingAndListening can be called multiple times in a row - pass
2016-03-18T16:23:16.518Z - info: 142. functions are run from a queue in the right order - pass
2016-03-18T16:23:16.519Z - info: 143. #ThaliPeerPoolDefault - single action - pass
2016-03-18T16:23:16.519Z - info: 144. #ThaliPeerPoolDefault - multiple actions - pass
2016-03-18T16:23:16.520Z - info: 

-== END ==-

2016-03-18T16:23:16.880Z - info: Running on ios test: 121. calling stop without start causes error

2016-03-18T16:23:17.225Z - info: Running on ios test: 122. can start/stop servers manager

2016-03-18T16:23:17.406Z - debug: Socket disconnected: transport close 2 (LGE-LG-H815)

2016-03-18T16:23:17.504Z - info: Running on ios test: 123. starting twice resolves with listening port

2016-03-18T16:23:17.932Z - info: Running on ios test: 124. terminateIncomingConnection will terminate a connection

2016-03-18T16:23:18.353Z - info: Running on ios test: 125. terminate an Outgoing connection will terminate the server

2016-03-18T16:23:18.696Z - info: Running on ios test: 126. terminate an Outgoing connection with wrong arguments is not harmful

2016-03-18T16:23:19.089Z - info: Running on ios test: 127. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-18T16:23:19.639Z - info: Running on ios test: 128. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-18T16:23:20.148Z - info: Running on ios test: 129. messages with invalid location or USN should be ignored

2016-03-18T16:23:20.590Z - info: Running on ios test: 130. verify that Thali-specific messages are filtered correctly

2016-03-18T16:23:21.046Z - info: Running on ios test: 131. #startListeningForAdvertisements should fail if start not called

2016-03-18T16:23:21.477Z - info: Running on ios test: 132. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-18T16:23:21.813Z - info: Running on ios test: 133. #start should fail if called twice in a row

2016-03-18T16:23:22.341Z - info: Running on ios test: 134. should not be started after stop is called

2016-03-18T16:23:22.740Z - info: Running on ios test: 135. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-18T16:23:23.106Z - info: Running on ios test: 136. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-18T16:23:23.625Z - info: Running on ios test: 137. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-18T16:23:24.226Z - info: Running on ios test: 138. #stop can be called multiple times in a row

2016-03-18T16:23:24.791Z - info: Running on ios test: 139. #startListeningForAdvertisements can be called multiple times in a row

2016-03-18T16:23:25.098Z - info: Running on ios test: 140. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-18T16:23:25.505Z - info: Running on ios test: 141. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-18T16:23:25.940Z - info: Running on ios test: 142. functions are run from a queue in the right order

2016-03-18T16:23:26.337Z - info: Running on ios test: 143. #ThaliPeerPoolDefault - single action

2016-03-18T16:23:26.662Z - info: Running on ios test: 144. #ThaliPeerPoolDefault - multiple actions

2016-03-18T16:23:27.093Z - info: Test run on ios complete

2016-03-18T16:23:27.094Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-18T16:23:27.096Z - info: PLATFORM: ios

2016-03-18T16:23:27.097Z - info: RESULT: FAIL

2016-03-18T16:23:27.099Z - info: 144 of 144 tests completed

2016-03-18T16:23:27.099Z - info: 141/144 passed (3 failures)

2016-03-18T16:23:27.100Z - info: --- Test Details ---



2016-03-18T16:23:27.101Z - info: 1. calling createNativeListener directly rejects - pass

2016-03-18T16:23:27.102Z - info: 2. emits incomingConnectionState - pass

2016-03-18T16:23:27.113Z - info: 3. emits routerPortConnectionFailed - pass

2016-03-18T16:23:27.114Z - info: 4. native server connections all up - pass

2016-03-18T16:23:27.115Z - info: 5. native server - closing incoming stream cleans outgoing socket - pass

2016-03-18T16:23:27.116Z - info: 6. native server - closing incoming connection cleans outgoing socket - pass

2016-03-18T16:23:27.117Z - info: 7. native server - closing outgoing socket cleans associated mux stream - pass

2016-03-18T16:23:27.118Z - info: 8. native server - closing the whole server cleans everything up - pass

2016-03-18T16:23:27.119Z - info: 9. native server - we can get a ton of connections and data through and still clean up the server completely - pass

2016-03-18T16:23:27.120Z - info: 10. native server - simulate mux failure, make sure everything is cleaned up - pass

2016-03-18T16:23:27.120Z - info: 11. native server - timing out the incoming connection cleans everything up - pass

2016-03-18T16:23:27.121Z - info: 12. closeAll can close even when connections open - pass

2016-03-18T16:23:27.122Z - info: 13. closeAll with promise - pass

2016-03-18T16:23:27.123Z - info: 14. multiplex can send data - pass

2016-03-18T16:23:27.124Z - info: 15. enqueue and run in order - pass

2016-03-18T16:23:27.125Z - info: 16. enqueueAtTop and run backwards - pass

2016-03-18T16:23:27.132Z - info: 17. mix enqueue and enqueueAtTop - pass

2016-03-18T16:23:27.133Z - info: 18. queues handled independently - pass

2016-03-18T16:23:27.134Z - info: 19. basic - pass

2016-03-18T16:23:27.135Z - info: 20. another - pass

2016-03-18T16:23:27.136Z - info: 21. #startListeningForAdvertisements should fail if start not called - pass

2016-03-18T16:23:27.137Z - info: 22. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-18T16:23:27.137Z - info: 23. should be able to call #stopListeningForAdvertisements many times - pass

2016-03-18T16:23:27.138Z - info: 24. should be able to call #startListeningForAdvertisements many times - pass

2016-03-18T16:23:27.139Z - info: 25. should be able to call #startUpdateAdvertisingAndListening many times - pass

2016-03-18T16:23:27.140Z - info: 26. should be able to call #stopAdvertisingAndListening many times - pass

2016-03-18T16:23:27.141Z - info: 27. #start should fail if called twice in a row - pass

2016-03-18T16:23:27.142Z - info: 28. does not emit duplicate discoveryAdvertisingStateUpdate - pass

2016-03-18T16:23:27.142Z - info: 29. does not send duplicate availability changes - pass

2016-03-18T16:23:27.143Z - info: 30. can get the network status - pass

2016-03-18T16:23:27.144Z - info: 31. wifi peer is marked unavailable if announcements stop - pass

2016-03-18T16:23:27.145Z - info: 32. Can call start/stopListeningForAdvertisements - pass

2016-03-18T16:23:27.146Z - info: 33. Calling startListeningForAdvertisements twice is NOT an error - pass

2016-03-18T16:23:27.147Z - info: 34. Can call start/stopUpdateAdvertisingAndListening - pass

2016-03-18T16:23:27.147Z - info: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error - pass

2016-03-18T16:23:27.148Z - info: 36. peerAvailabilityChange is called - pass

2016-03-18T16:23:27.149Z - info: 37. Can connect to a remote peer - fail

2016-03-18T16:23:27.150Z - info: 38. Can shift large amounts of data - fail

2016-03-18T16:23:27.151Z - info: 39. #startListeningForAdvertisements should fail if start not called - pass

2016-03-18T16:23:27.152Z - info: 40. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-18T16:23:27.153Z - info: 41. should be able to call #stopListeningForAdvertisements many times - pass

2016-03-18T16:23:27.154Z - info: 42. should be able to call #startListeningForAdvertisements many times - pass

2016-03-18T16:23:27.154Z - info: 43. should be able to call #startUpdateAdvertisingAndListening many times - pass

2016-03-18T16:23:27.155Z - info: 44. should be able to call #stopAdvertisingAndListening many times - pass

2016-03-18T16:23:27.156Z - info: 45. can get the network status before starting - pass

2016-03-18T16:23:27.157Z - info: 46. error returned with bad router - pass

2016-03-18T16:23:27.158Z - info: 47. can do HTTP requests between peers - fail

2016-03-18T16:23:27.159Z - info: 48. Can do requests between peers after start and stop - pass

2016-03-18T16:23:27.159Z - info: 49. We successfully receive and replay discoveryAdvertisingStateUpdate - pass

2016-03-18T16:23:27.160Z - info: 50. Test BEACONS_RETRIEVED_AND_PARSED locally - pass

2016-03-18T16:23:27.161Z - info: 51. Test HTTP_BAD_RESPONSE locally - pass

2016-03-18T16:23:27.162Z - info: 52. Test NETWORK_PROBLEM locally - pass

2016-03-18T16:23:27.163Z - info: 53. Test timeout locally - pass

2016-03-18T16:23:27.164Z - info: 54. Call the start two times - pass

2016-03-18T16:23:27.164Z - info: 55. Call the kill before calling the start - pass

2016-03-18T16:23:27.165Z - info: 56. Call the kill immediately after the start - pass

2016-03-18T16:23:27.166Z - info: 57. Call the kill while waiting a response from the server - pass

2016-03-18T16:23:27.167Z - info: 58. Test to exceed the max content size locally - pass

2016-03-18T16:23:27.168Z - info: 59. Close the server socket while the client is waiting a response from the server. Local test. - pass

2016-03-18T16:23:27.169Z - info: 60. Close the client socket while the client is waiting a response from the server. Local test. - pass

2016-03-18T16:23:27.170Z - info: 61. #generatePreambleAndBeacons bad args - pass

2016-03-18T16:23:27.171Z - info: 62. #generatePreambleAndBeacons empty keys to notify - pass

2016-03-18T16:23:27.172Z - info: 63. #generatePreambleAndBeacons multiple keys to notify - pass

2016-03-18T16:23:27.172Z - info: 64. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass

2016-03-18T16:23:27.173Z - info: 65. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass

2016-03-18T16:23:27.174Z - info: 66. #parseBeacons expiration out of range lower - pass

2016-03-18T16:23:27.175Z - info: 67. #parseBeacons expiration out of range lower - pass

2016-03-18T16:23:27.176Z - info: 68. #parseBeacons no beacons returns null - pass

2016-03-18T16:23:27.177Z - info: 69. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass

2016-03-18T16:23:27.177Z - info: 70. #parseBeacons addressBookCallback fails decrypt - pass

2016-03-18T16:23:27.178Z - info: 71. #parseBeacons addressBookCallback returns no matches - pass

2016-03-18T16:23:27.179Z - info: 72. #parseBeacons addressBookCallback returns spurious match - pass

2016-03-18T16:23:27.180Z - info: 73. #parseBeacons addressBookCallback returns public key - pass

2016-03-18T16:23:27.181Z - info: 74. validate generatePskIdentityField - pass

2016-03-18T16:23:27.182Z - info: 75. validate generatePskSecret - pass

2016-03-18T16:23:27.183Z - info: 76. Start and stop ThaliNotificationServer - pass

2016-03-18T16:23:27.183Z - info: 77. Pass an empty array to ThaliNotificationServer.start - pass

2016-03-18T16:23:27.184Z - info: 78. Pass a string to ThaliNotificationServer.start - pass

2016-03-18T16:23:27.185Z - info: 79. Pass an empty parameter to ThaliNotificationServer.start - pass

2016-03-18T16:23:27.186Z - info: 80. Make an HTTP request to /NotificationBeacons - pass

2016-03-18T16:23:27.187Z - info: 81. Make an HTTP request to /NotificationBeacons (no keys) - pass

2016-03-18T16:23:27.188Z - info: 82. Make an HTTP request to /NotificationBeaconsbefore calling start - pass

2016-03-18T16:23:27.189Z - info: 83. #testThaliPeerAction - test getters - pass

2016-03-18T16:23:27.189Z - info: 84. #testThaliPeerAction - start and kill - pass

2016-03-18T16:23:27.190Z - info: 85. #testThaliPeerAction - double start - pass

2016-03-18T16:23:27.191Z - info: 86. #testThaliPeerAction - start after kill - pass

2016-03-18T16:23:27.192Z - info: 87. #testThaliPeerAction - make sure ids are unique - pass

2016-03-18T16:23:27.193Z - info: 88. Test PeerConnectionInformation basics - pass

2016-03-18T16:23:27.194Z - info: 89. Test PeerDictionary basic functionality - pass

2016-03-18T16:23:27.194Z - info: 90. Test PeerDictionary with multiple entries. - pass

2016-03-18T16:23:27.195Z - info: 91. RESOLVED entries are removed before WAITING state entry. - pass

2016-03-18T16:23:27.196Z - info: 92. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass

2016-03-18T16:23:27.197Z - info: 93. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass

2016-03-18T16:23:27.198Z - info: 94. #ThaliPeerPoolInterface - bad enqueues - pass

2016-03-18T16:23:27.199Z - info: 95. #ThaliPeerPoolInterface - do not allow same object type - pass

2016-03-18T16:23:27.200Z - info: 96. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass

2016-03-18T16:23:27.200Z - info: 97. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent - pass

2016-03-18T16:23:27.201Z - info: 98. compareBufferArrays - pass

2016-03-18T16:23:27.202Z - info: 99. Call start twice and get error - pass

2016-03-18T16:23:27.203Z - info: 100. Start and make sure it runs - pass

2016-03-18T16:23:27.204Z - info: 101. Make sure getTimeWhenRun is right after start - pass

2016-03-18T16:23:27.204Z - info: 102. Make sure getTimeWhenRun is -1 after function is called - pass

2016-03-18T16:23:27.205Z - info: 103. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass

2016-03-18T16:23:27.206Z - info: 104. Test TransientState - pass

2016-03-18T16:23:27.207Z - info: 105. No peers and empty database - pass

2016-03-18T16:23:27.208Z - info: 106. One peer and empty DB - pass

2016-03-18T16:23:27.209Z - info: 107. One peer with _Local set behind current seq - pass

2016-03-18T16:23:27.210Z - info: 108. One peer with _Local set equal to current seq - pass

2016-03-18T16:23:27.211Z - info: 109. One peer with _Local set ahead of current seq (and no this should not happen) - pass

2016-03-18T16:23:27.211Z - info: 110. Three peers, one not in DB, one behind and one ahead - pass

2016-03-18T16:23:27.212Z - info: 111. More than maximum peers, make sure we only send maximum allowed - pass

2016-03-18T16:23:27.213Z - info: 112. two peers with empty DB, update the doc - pass

2016-03-18T16:23:27.214Z - info: 113. add doc and make sure tokens refresh when they expire - pass

2016-03-18T16:23:27.215Z - info: 114. start and stop and start and stop - pass

2016-03-18T16:23:27.216Z - info: 115. two identical starts in a row - pass

2016-03-18T16:23:27.216Z - info: 116. two different starts in a row - pass

2016-03-18T16:23:27.217Z - info: 117. two stops and a start and two stops - pass

2016-03-18T16:23:27.218Z - info: 118. we properly enqueue requests so no then needed - pass

2016-03-18T16:23:27.219Z - info: 119. test calculateSeqPointKeyId - pass

2016-03-18T16:23:27.220Z - info: 120. can create servers manager - pass

2016-03-18T16:23:27.221Z - info: 121. calling stop without start causes error - pass

2016-03-18T16:23:27.222Z - info: 122. can start/stop servers manager - pass

2016-03-18T16:23:27.222Z - info: 123. starting twice resolves with listening port - pass

2016-03-18T16:23:27.223Z - info: 124. terminateIncomingConnection will terminate a connection - pass

2016-03-18T16:23:27.224Z - info: 125. terminate an Outgoing connection will terminate the server - pass

2016-03-18T16:23:27.225Z - info: 126. terminate an Outgoing connection with wrong arguments is not harmful - pass

2016-03-18T16:23:27.226Z - info: 127. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass

2016-03-18T16:23:27.227Z - info: 128. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-03-18T16:23:27.227Z - info: 129. messages with invalid location or USN should be ignored - pass

2016-03-18T16:23:27.228Z - info: 130. verify that Thali-specific messages are filtered correctly - pass

2016-03-18T16:23:27.229Z - info: 131. #startListeningForAdvertisements should fail if start not called - pass

2016-03-18T16:23:27.230Z - info: 132. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-18T16:23:27.231Z - info: 133. #start should fail if called twice in a row - pass

2016-03-18T16:23:27.232Z - info: 134. should not be started after stop is called - pass

2016-03-18T16:23:27.233Z - info: 135. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass

2016-03-18T16:23:27.233Z - info: 136. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass

2016-03-18T16:23:27.234Z - info: 137. #startUpdateAdvertisingAndListening should start hosting given router object - pass

2016-03-18T16:23:27.235Z - info: 138. #stop can be called multiple times in a row - pass

2016-03-18T16:23:27.236Z - info: 139. #startListeningForAdvertisements can be called multiple times in a row - pass

2016-03-18T16:23:27.237Z - info: 140. #stopListeningForAdvertisements can be called multiple times in a row - pass

2016-03-18T16:23:27.238Z - info: 141. #stopAdvertisingAndListening can be called multiple times in a row - pass

2016-03-18T16:23:27.239Z - info: 142. functions are run from a queue in the right order - pass

2016-03-18T16:23:27.240Z - info: 143. #ThaliPeerPoolDefault - single action - pass

2016-03-18T16:23:27.240Z - info: 144. #ThaliPeerPoolDefault - multiple actions - pass

2016-03-18T16:23:27.241Z - info: 

-== END ==-


```


Logs for system : 
```

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m



ios : false
```
###Android Logs
####Node name: thali01
Console output:
```
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:0 
child process exited with code 0 on device f56ad48d 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62548124b8ccb9f_More_thaliMobileNativeWrapper_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali03
Console output:
```
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:0 
child process exited with code 0 on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/62548124b8ccb9f_More_thaliMobileNativeWrapper_vjrantal/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on ZX1C223JKW 
Android task is completed. [SUCCESS]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/62548124b8ccb9f_More_thaliMobileNativeWrapper_vjrantal/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Android task is completed. [SUCCESS]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/62548124b8ccb9f_More_thaliMobileNativeWrapper_vjrantal/thali05_LGE-LG-H815.md)

####Node name: thali06
Console output:
```
STOP log received from  FA55PYS00566 Test has  SUCCEEDED
Device test finished on FA55PYS00566 
Android task is completed. [SUCCESS]
```
[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/62548124b8ccb9f_More_thaliMobileNativeWrapper_vjrantal/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
STOP log received from  4db5c8cc Test has  SUCCEEDED
Device test finished on 4db5c8cc 
Android task is completed. [SUCCESS]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62548124b8ccb9f_More_thaliMobileNativeWrapper_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:0 
child process exited with code 0 on device 4325e43f 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62548124b8ccb9f_More_thaliMobileNativeWrapper_vjrantal/thali08_samsung-SM-A300FU.md)




###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/62548124b8ccb9f_More_thaliMobileNativeWrapper_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/62548124b8ccb9f_More_thaliMobileNativeWrapper_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/62548124b8ccb9f_More_thaliMobileNativeWrapper_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/62548124b8ccb9f_More_thaliMobileNativeWrapper_vjrantal/iOS_Iphone5s-1.md)



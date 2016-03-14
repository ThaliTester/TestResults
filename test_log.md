#### Test 62754403b276699 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":8}}
2016-03-14T17:19:27.277Z - info: listening on *:3000

2016-03-14T17:19:27.825Z - debug: Device presented: samsung-SM-A500FU (android) unittest socket:0

2016-03-14T17:19:28.206Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:1

2016-03-14T17:19:28.209Z - info: Required number of android devices presented (2)

2016-03-14T17:19:28.213Z - info: Starting unit test run for platform: android

2016-03-14T17:19:28.768Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:2

2016-03-14T17:19:28.836Z - info: Running on android test: 1. closeAll can close even when connections open

2016-03-14T17:19:28.896Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:3

2016-03-14T17:19:28.898Z - info: Discarding surplus device: samsung-SM-N910C

2016-03-14T17:19:29.187Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:4

2016-03-14T17:19:29.188Z - info: Required number of ios devices presented (2)

2016-03-14T17:19:29.190Z - info: Starting unit test run for platform: ios

2016-03-14T17:19:29.218Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:5

2016-03-14T17:19:29.219Z - info: Discarding surplus device: Apple-Iphone6-1

2016-03-14T17:19:29.315Z - debug: Device presented: samsung-SM-A500FU (android) unittest socket:6

2016-03-14T17:19:29.316Z - info: Discarding surplus device: samsung-SM-A500FU

2016-03-14T17:19:29.544Z - info: Running on android test: 2. closeAll with promise

2016-03-14T17:19:29.828Z - debug: Socket disconnected: transport close 3 (samsung-SM-N910C)

2016-03-14T17:19:29.862Z - info: Running on ios test: 1. closeAll can close even when connections open

2016-03-14T17:19:30.009Z - info: Running on android test: 3. multiplex can send data

2016-03-14T17:19:30.454Z - info: Running on android test: 4. enqueue and run in order

2016-03-14T17:19:30.458Z - info: Running on ios test: 2. closeAll with promise

2016-03-14T17:19:30.923Z - info: Running on ios test: 3. multiplex can send data

2016-03-14T17:19:31.176Z - info: Running on android test: 5. enqueueAtTop and run backwards

2016-03-14T17:19:31.520Z - info: Running on ios test: 4. enqueue and run in order

2016-03-14T17:19:31.700Z - info: Running on android test: 6. mix enqueue and enqueueAtTop

2016-03-14T17:19:31.738Z - debug: Socket disconnected: transport close 5 (Apple-Iphone6-1)

2016-03-14T17:19:32.191Z - info: Running on ios test: 5. enqueueAtTop and run backwards

2016-03-14T17:19:32.284Z - info: Running on android test: 7. queues handled independently

2016-03-14T17:19:32.595Z - info: Running on ios test: 6. mix enqueue and enqueueAtTop

2016-03-14T17:19:32.768Z - info: Running on android test: 8. basic

2016-03-14T17:19:33.078Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:7

2016-03-14T17:19:33.079Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-14T17:19:33.201Z - info: Running on android test: 9. another

2016-03-14T17:19:33.210Z - info: Running on ios test: 7. queues handled independently

2016-03-14T17:19:33.680Z - info: Running on android test: 10. #startListeningForAdvertisements should fail if start not called

2016-03-14T17:19:33.738Z - info: Running on ios test: 8. basic

2016-03-14T17:19:34.207Z - info: Running on android test: 11. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-14T17:19:34.553Z - info: Running on ios test: 9. another

2016-03-14T17:19:34.691Z - info: Running on android test: 12. should be able to call #stopListeningForAdvertisements many times

2016-03-14T17:19:35.036Z - info: Running on ios test: 10. #startListeningForAdvertisements should fail if start not called

2016-03-14T17:19:35.062Z - info: Running on android test: 13. should be able to call #startListeningForAdvertisements many times

2016-03-14T17:19:35.464Z - info: Running on ios test: 11. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-14T17:19:35.490Z - info: Running on android test: 14. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-14T17:19:35.644Z - debug: Socket disconnected: transport close 7 (Apple-Iphone5s-1)

2016-03-14T17:19:35.827Z - info: Running on ios test: 12. should be able to call #stopListeningForAdvertisements many times

2016-03-14T17:19:35.949Z - info: Running on android test: 15. should be able to call #stopAdvertisingAndListening many times

2016-03-14T17:19:36.243Z - info: Running on ios test: 13. should be able to call #startListeningForAdvertisements many times

2016-03-14T17:19:36.383Z - info: Running on android test: 16. #start should fail if called twice in a row

2016-03-14T17:19:36.718Z - info: Running on ios test: 14. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-14T17:19:36.844Z - info: Running on android test: 17. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-14T17:19:37.211Z - info: Running on ios test: 15. should be able to call #stopAdvertisingAndListening many times

2016-03-14T17:19:37.386Z - info: Running on android test: 18. does not send duplicate availability changes

2016-03-14T17:19:37.782Z - info: Running on ios test: 16. #start should fail if called twice in a row

2016-03-14T17:19:37.938Z - info: Running on android test: 19. can get the network status

2016-03-14T17:19:38.378Z - info: Running on ios test: 17. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-14T17:19:38.524Z - info: Running on android test: 20. wifi peer is marked unavailable if announcements stop

2016-03-14T17:19:38.900Z - info: Running on ios test: 18. does not send duplicate availability changes

2016-03-14T17:19:39.244Z - info: Running on ios test: 19. can get the network status

2016-03-14T17:19:39.630Z - info: Running on ios test: 20. wifi peer is marked unavailable if announcements stop

2016-03-14T17:19:40.021Z - info: Running on android test: 21. can get the network status before starting

2016-03-14T17:19:40.415Z - info: Running on android test: 22. Test BEACONS_RETRIEVED_AND_PARSED locally

2016-03-14T17:19:40.995Z - info: Running on android test: 23. Test HTTP_BAD_RESPONSE locally

2016-03-14T17:19:41.186Z - info: Running on ios test: 21. can get the network status before starting

2016-03-14T17:19:41.462Z - info: Running on android test: 24. Test NETWORK_PROBLEM locally

2016-03-14T17:19:41.499Z - info: Running on ios test: 22. Test BEACONS_RETRIEVED_AND_PARSED locally

2016-03-14T17:19:42.167Z - info: Running on ios test: 23. Test HTTP_BAD_RESPONSE locally

2016-03-14T17:19:42.769Z - info: Running on ios test: 24. Test NETWORK_PROBLEM locally

2016-03-14T17:19:42.783Z - info: Running on android test: 25. Test timeout locally

2016-03-14T17:19:43.815Z - info: Running on ios test: 25. Test timeout locally

2016-03-14T17:19:44.372Z - info: Running on android test: 26. Call the start two times

2016-03-14T17:19:44.935Z - info: Running on android test: 27. Call the kill before calling the start

2016-03-14T17:19:45.321Z - info: Running on ios test: 26. Call the start two times

2016-03-14T17:19:45.465Z - info: Running on android test: 28. Call the kill immediately after the start

2016-03-14T17:19:45.859Z - info: Running on ios test: 27. Call the kill before calling the start

2016-03-14T17:19:46.068Z - info: Running on android test: 29. Call the kill while waiting a response from the server

2016-03-14T17:19:46.247Z - info: Running on ios test: 28. Call the kill immediately after the start

2016-03-14T17:19:46.737Z - info: Running on ios test: 29. Call the kill while waiting a response from the server

2016-03-14T17:19:48.549Z - info: Running on android test: 30. Test to exceed the max content size locally

2016-03-14T17:19:49.539Z - info: Running on ios test: 30. Test to exceed the max content size locally

2016-03-14T17:19:49.719Z - info: Running on android test: 31. #generatePreambleAndBeacons bad args

2016-03-14T17:19:50.152Z - info: Running on android test: 32. #generatePreambleAndBeacons empty keys to notify

2016-03-14T17:19:50.235Z - info: Running on ios test: 31. #generatePreambleAndBeacons bad args

2016-03-14T17:19:50.676Z - info: Running on ios test: 32. #generatePreambleAndBeacons empty keys to notify

2016-03-14T17:19:51.107Z - info: Running on ios test: 33. #generatePreambleAndBeacons multiple keys to notify

2016-03-14T17:19:51.124Z - info: Running on android test: 33. #generatePreambleAndBeacons multiple keys to notify

2016-03-14T17:19:51.544Z - info: Running on ios test: 34. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-14T17:19:51.735Z - info: Running on android test: 34. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-14T17:19:51.996Z - info: Running on ios test: 35. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-14T17:19:52.121Z - info: Running on android test: 35. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-14T17:19:52.529Z - info: Running on ios test: 36. #parseBeacons expiration out of range lower

2016-03-14T17:19:52.679Z - info: Running on android test: 36. #parseBeacons expiration out of range lower

2016-03-14T17:19:52.910Z - info: Running on ios test: 37. #parseBeacons expiration out of range lower

2016-03-14T17:19:53.420Z - info: Running on ios test: 38. #parseBeacons no beacons returns null

2016-03-14T17:19:53.498Z - info: Running on android test: 37. #parseBeacons expiration out of range lower

2016-03-14T17:19:53.830Z - info: Running on ios test: 39. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-14T17:19:54.257Z - info: Running on android test: 38. #parseBeacons no beacons returns null

2016-03-14T17:19:54.279Z - info: Running on ios test: 40. #parseBeacons addressBookCallback fails decrypt

2016-03-14T17:19:54.687Z - info: Running on android test: 39. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-14T17:19:54.805Z - info: Running on ios test: 41. #parseBeacons addressBookCallback returns no matches

2016-03-14T17:19:55.167Z - info: Running on android test: 40. #parseBeacons addressBookCallback fails decrypt

2016-03-14T17:19:55.409Z - info: Running on ios test: 42. #parseBeacons addressBookCallback returns spurious match

2016-03-14T17:19:55.781Z - info: Running on android test: 41. #parseBeacons addressBookCallback returns no matches

2016-03-14T17:19:55.941Z - info: Running on ios test: 43. #parseBeacons addressBookCallback returns public key

2016-03-14T17:19:56.456Z - info: Running on android test: 42. #parseBeacons addressBookCallback returns spurious match

2016-03-14T17:19:56.669Z - info: Running on ios test: 44. #parseBeacons with beacons both for and not for the user

2016-03-14T17:19:57.387Z - info: Running on ios test: 45. Start and stop ThaliNotificationServer

2016-03-14T17:19:57.681Z - info: Running on android test: 43. #parseBeacons addressBookCallback returns public key

2016-03-14T17:19:57.865Z - info: Running on ios test: 46. Pass an empty array to ThaliNotificationServer.start

2016-03-14T17:19:58.238Z - info: Running on android test: 44. #parseBeacons with beacons both for and not for the user

2016-03-14T17:19:58.293Z - info: Running on ios test: 47. Pass a string to ThaliNotificationServer.start

2016-03-14T17:19:58.685Z - info: Running on android test: 45. Start and stop ThaliNotificationServer

2016-03-14T17:19:58.690Z - info: Running on ios test: 48. Pass an empty parameter to ThaliNotificationServer.start

2016-03-14T17:19:59.181Z - info: Running on ios test: 49. Make an HTTP request to /NotificationBeacons

2016-03-14T17:19:59.224Z - info: Running on android test: 46. Pass an empty array to ThaliNotificationServer.start

2016-03-14T17:19:59.795Z - info: Running on android test: 47. Pass a string to ThaliNotificationServer.start

2016-03-14T17:20:00.236Z - info: Running on ios test: 50. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-14T17:20:00.264Z - info: Running on android test: 48. Pass an empty parameter to ThaliNotificationServer.start

2016-03-14T17:20:01.000Z - info: Running on ios test: 51. Make an HTTP request to /NotificationBeacons before calling start

2016-03-14T17:20:01.045Z - info: Running on android test: 49. Make an HTTP request to /NotificationBeacons

2016-03-14T17:20:01.536Z - info: Running on ios test: 52. #testThaliPeerAction - test getters

2016-03-14T17:20:01.726Z - info: Running on android test: 50. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-14T17:20:02.083Z - info: Running on ios test: 53. #testThaliPeerAction - start and kill

2016-03-14T17:20:02.337Z - info: Running on android test: 51. Make an HTTP request to /NotificationBeacons before calling start

2016-03-14T17:20:02.523Z - info: Running on ios test: 54. #testThaliPeerAction - double start

2016-03-14T17:20:02.917Z - info: Running on android test: 52. #testThaliPeerAction - test getters

2016-03-14T17:20:03.101Z - info: Running on ios test: 55. #testThaliPeerAction - start after kill

2016-03-14T17:20:03.329Z - info: Running on android test: 53. #testThaliPeerAction - start and kill

2016-03-14T17:20:03.464Z - info: Running on ios test: 56. #testThaliPeerAction - make sure ids are unique

2016-03-14T17:20:03.681Z - info: Running on android test: 54. #testThaliPeerAction - double start

2016-03-14T17:20:03.857Z - info: Running on ios test: 57. Test PeerConnectionInformation basics

2016-03-14T17:20:04.143Z - info: Running on android test: 55. #testThaliPeerAction - start after kill

2016-03-14T17:20:04.264Z - info: Running on ios test: 58. Test PeerDictionary basic functionality

2016-03-14T17:20:04.514Z - info: Running on android test: 56. #testThaliPeerAction - make sure ids are unique

2016-03-14T17:20:04.663Z - info: Running on ios test: 59. Test PeerDictionary with multiple entries.

2016-03-14T17:20:04.908Z - info: Running on android test: 57. Test PeerConnectionInformation basics

2016-03-14T17:20:05.323Z - info: Running on android test: 58. Test PeerDictionary basic functionality

2016-03-14T17:20:05.790Z - info: Running on android test: 59. Test PeerDictionary with multiple entries.

2016-03-14T17:20:08.974Z - info: Running on android test: 60. RESOLVED entries are removed before WAITING state entry.

2016-03-14T17:20:08.979Z - info: Running on ios test: 60. RESOLVED entries are removed before WAITING state entry.

2016-03-14T17:20:10.890Z - info: Running on android test: 61. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-14T17:20:10.974Z - info: Running on ios test: 61. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-03-14T17:20:12.584Z - info: Running on ios test: 62. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-14T17:20:12.588Z - info: Running on android test: 62. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-03-14T17:20:14.030Z - info: Running on ios test: 63. #ThaliPeerPoolInterface - bad enqueues

2016-03-14T17:20:14.216Z - info: Running on android test: 63. #ThaliPeerPoolInterface - bad enqueues

2016-03-14T17:20:14.440Z - info: Running on ios test: 64. #ThaliPeerPoolInterface - do not allow same object type

2016-03-14T17:20:14.753Z - info: Running on android test: 64. #ThaliPeerPoolInterface - do not allow same object type

2016-03-14T17:20:15.138Z - info: Running on android test: 65. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-14T17:20:15.345Z - info: Running on ios test: 65. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-14T17:20:15.520Z - info: Running on android test: 66. compareBufferArrays

2016-03-14T17:20:15.861Z - info: Running on android test: 67. Call start twice and get error

2016-03-14T17:20:15.864Z - info: Running on ios test: 66. compareBufferArrays

2016-03-14T17:20:16.274Z - info: Running on android test: 68. Start and make sure it runs

2016-03-14T17:20:16.278Z - info: Running on ios test: 67. Call start twice and get error

2016-03-14T17:20:16.765Z - info: Running on android test: 69. Make sure getTimeWhenRun is right after start

2016-03-14T17:20:16.773Z - info: Running on ios test: 68. Start and make sure it runs

2016-03-14T17:20:17.193Z - info: Running on android test: 70. Make sure getTimeWhenRun is -1 after function is called

2016-03-14T17:20:17.251Z - info: Running on ios test: 69. Make sure getTimeWhenRun is right after start

2016-03-14T17:20:17.676Z - info: Running on android test: 71. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-14T17:20:17.756Z - info: Running on ios test: 70. Make sure getTimeWhenRun is -1 after function is called

2016-03-14T17:20:18.175Z - info: Running on android test: 72. Test TransientState

2016-03-14T17:20:18.296Z - info: Running on ios test: 71. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-14T17:20:18.541Z - info: Running on android test: 73. No peers and empty database

2016-03-14T17:20:18.692Z - info: Running on ios test: 72. Test TransientState

2016-03-14T17:20:18.962Z - info: Running on android test: 74. One peer and empty DB

2016-03-14T17:20:19.002Z - info: Running on ios test: 73. No peers and empty database

2016-03-14T17:20:19.510Z - info: Running on android test: 75. One peer with _Local set behind current seq

2016-03-14T17:20:19.705Z - info: Running on ios test: 74. One peer and empty DB

2016-03-14T17:20:20.047Z - info: Running on android test: 76. One peer with _Local set equal to current seq

2016-03-14T17:20:20.245Z - info: Running on ios test: 75. One peer with _Local set behind current seq

2016-03-14T17:20:20.574Z - info: Running on android test: 77. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-14T17:20:21.315Z - info: Running on android test: 78. Three peers, one not in DB, one behind and one ahead

2016-03-14T17:20:22.685Z - info: Running on android test: 79. More than maximum peers, make sure we only send maximum allowed

2016-03-14T17:20:23.971Z - info: Running on android test: 80. two peers with empty DB, update the doc

2016-03-14T17:20:24.076Z - info: Running on ios test: 76. One peer with _Local set equal to current seq

2016-03-14T17:20:24.570Z - info: Running on android test: 81. add doc and make sure tokens refresh when they expire

2016-03-14T17:20:25.281Z - info: Running on ios test: 77. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-14T17:20:25.732Z - info: Running on android test: 82. start and stop and start and stop

2016-03-14T17:20:26.404Z - info: Running on android test: 83. two identical starts in a row

2016-03-14T17:20:26.838Z - info: Running on ios test: 78. Three peers, one not in DB, one behind and one ahead

2016-03-14T17:20:26.956Z - info: Running on android test: 84. two different starts in a row

2016-03-14T17:20:27.507Z - info: Running on android test: 85. two stops and a start and two stops

2016-03-14T17:20:27.728Z - info: Running on ios test: 79. More than maximum peers, make sure we only send maximum allowed

2016-03-14T17:20:28.105Z - info: Running on android test: 86. we properly enqueue requests so no then needed

2016-03-14T17:20:28.620Z - info: Running on android test: 87. test calculateSeqPointKeyId

2016-03-14T17:20:28.998Z - info: Running on android test: 88. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-14T17:20:29.183Z - info: Running on ios test: 80. two peers with empty DB, update the doc

2016-03-14T17:20:29.437Z - info: Running on android test: 89. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-14T17:20:30.073Z - info: Running on android test: 90. messages with invalid location or USN should be ignored

2016-03-14T17:20:30.077Z - info: Running on ios test: 81. add doc and make sure tokens refresh when they expire

2016-03-14T17:20:30.498Z - info: Running on android test: 91. verify that Thali-specific messages are filtered correctly

2016-03-14T17:20:30.959Z - info: Running on android test: 92. #startListeningForAdvertisements should fail if start not called

2016-03-14T17:20:31.337Z - info: Running on ios test: 82. start and stop and start and stop

2016-03-14T17:20:31.569Z - info: Running on android test: 93. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-14T17:20:31.937Z - info: Running on android test: 94. #start should fail if called twice in a row

2016-03-14T17:20:32.260Z - info: Running on ios test: 83. two identical starts in a row

2016-03-14T17:20:32.282Z - info: Running on android test: 95. should not be started after stop is called

2016-03-14T17:20:32.588Z - info: Running on android test: 96. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-14T17:20:32.910Z - info: Running on ios test: 84. two different starts in a row

2016-03-14T17:20:32.991Z - info: Running on android test: 97. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-14T17:20:33.353Z - info: Running on android test: 98. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-14T17:20:33.685Z - info: Running on ios test: 85. two stops and a start and two stops

2016-03-14T17:20:33.791Z - info: Running on android test: 99. #stop can be called multiple times in a row

2016-03-14T17:20:34.261Z - info: Running on android test: 100. #startListeningForAdvertisements can be called multiple times in a row

2016-03-14T17:20:34.516Z - info: Running on ios test: 86. we properly enqueue requests so no then needed

2016-03-14T17:20:34.712Z - info: Running on android test: 101. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-14T17:20:35.207Z - info: Running on android test: 102. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-14T17:20:35.283Z - info: Running on ios test: 87. test calculateSeqPointKeyId

2016-03-14T17:20:35.905Z - info: Running on android test: 103. functions are run from a queue in the right order

2016-03-14T17:20:35.982Z - info: Running on ios test: 88. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-14T17:20:36.420Z - info: Running on android test: 104. #ThaliPeerPoolDefault - single action

2016-03-14T17:20:36.548Z - info: Running on ios test: 89. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-14T17:20:36.885Z - info: Running on android test: 105. #ThaliPeerPoolDefault - multiple actions

2016-03-14T17:20:37.069Z - info: Running on ios test: 90. messages with invalid location or USN should be ignored

2016-03-14T17:20:37.325Z - info: Test run on android complete

2016-03-14T17:20:37.328Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-14T17:20:37.330Z - info: PLATFORM: android

2016-03-14T17:20:37.331Z - info: RESULT: PASS

2016-03-14T17:20:37.333Z - info: 105 of 105 tests completed

2016-03-14T17:20:37.334Z - info: 105/105 passed (0 failures)

2016-03-14T17:20:37.335Z - info: --- Test Details ---



2016-03-14T17:20:37.337Z - info: 1. closeAll can close even when connections open - pass

2016-03-14T17:20:37.338Z - info: 2. closeAll with promise - pass

2016-03-14T17:20:37.339Z - info: 3. multiplex can send data - pass

2016-03-14T17:20:37.341Z - info: 4. enqueue and run in order - pass

2016-03-14T17:20:37.342Z - info: 5. enqueueAtTop and run backwards - pass

2016-03-14T17:20:37.343Z - info: 6. mix enqueue and enqueueAtTop - pass

2016-03-14T17:20:37.344Z - info: 7. queues handled independently - pass

2016-03-14T17:20:37.345Z - info: 8. basic - pass

2016-03-14T17:20:37.347Z - info: 9. another - pass

2016-03-14T17:20:37.348Z - info: 10. #startListeningForAdvertisements should fail if start not called - pass

2016-03-14T17:20:37.349Z - info: 11. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-14T17:20:37.350Z - info: 12. should be able to call #stopListeningForAdvertisements many times - pass

2016-03-14T17:20:37.352Z - info: 13. should be able to call #startListeningForAdvertisements many times - pass

2016-03-14T17:20:37.353Z - info: 14. should be able to call #startUpdateAdvertisingAndListening many times - pass

2016-03-14T17:20:37.354Z - info: 15. should be able to call #stopAdvertisingAndListening many times - pass

2016-03-14T17:20:37.355Z - info: 16. #start should fail if called twice in a row - pass

2016-03-14T17:20:37.357Z - info: 17. does not emit duplicate discoveryAdvertisingStateUpdate - pass

2016-03-14T17:20:37.358Z - info: 18. does not send duplicate availability changes - pass

2016-03-14T17:20:37.359Z - info: 19. can get the network status - pass

2016-03-14T17:20:37.360Z - info: 20. wifi peer is marked unavailable if announcements stop - pass
2016-03-14T17:20:37.362Z - info: 21. can get the network status before starting - pass
2016-03-14T17:20:37.362Z - info: 22. Test BEACONS_RETRIEVED_AND_PARSED locally - pass

2016-03-14T17:20:37.363Z - info: 23. Test HTTP_BAD_RESPONSE locally - pass

2016-03-14T17:20:37.363Z - info: 24. Test NETWORK_PROBLEM locally - pass

2016-03-14T17:20:37.366Z - info: 25. Test timeout locally - pass

2016-03-14T17:20:37.367Z - info: 26. Call the start two times - pass

2016-03-14T17:20:37.367Z - info: 27. Call the kill before calling the start - pass

2016-03-14T17:20:37.368Z - info: 28. Call the kill immediately after the start - pass
2016-03-14T17:20:37.369Z - info: 29. Call the kill while waiting a response from the server - pass

2016-03-14T17:20:37.370Z - info: 30. Test to exceed the max content size locally - pass

2016-03-14T17:20:37.370Z - info: 31. #generatePreambleAndBeacons bad args - pass

2016-03-14T17:20:37.371Z - info: 32. #generatePreambleAndBeacons empty keys to notify - pass
2016-03-14T17:20:37.372Z - info: 33. #generatePreambleAndBeacons multiple keys to notify - pass

2016-03-14T17:20:37.372Z - info: 34. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass

2016-03-14T17:20:37.373Z - info: 35. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass
2016-03-14T17:20:37.374Z - info: 36. #parseBeacons expiration out of range lower - pass

2016-03-14T17:20:37.374Z - info: 37. #parseBeacons expiration out of range lower - pass

2016-03-14T17:20:37.375Z - info: 38. #parseBeacons no beacons returns null - pass

2016-03-14T17:20:37.376Z - info: 39. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass
2016-03-14T17:20:37.376Z - info: 40. #parseBeacons addressBookCallback fails decrypt - pass

2016-03-14T17:20:37.377Z - info: 41. #parseBeacons addressBookCallback returns no matches - pass
2016-03-14T17:20:37.378Z - info: 42. #parseBeacons addressBookCallback returns spurious match - pass
2016-03-14T17:20:37.378Z - info: 43. #parseBeacons addressBookCallback returns public key - pass
2016-03-14T17:20:37.379Z - info: 44. #parseBeacons with beacons both for and not for the user - pass
2016-03-14T17:20:37.380Z - info: 45. Start and stop ThaliNotificationServer - pass
2016-03-14T17:20:37.380Z - info: 46. Pass an empty array to ThaliNotificationServer.start - pass
2016-03-14T17:20:37.381Z - info: 47. Pass a string to ThaliNotificationServer.start - pass
2016-03-14T17:20:37.381Z - info: 48. Pass an empty parameter to ThaliNotificationServer.start - pass
2016-03-14T17:20:37.382Z - info: 49. Make an HTTP request to /NotificationBeacons - pass
2016-03-14T17:20:37.383Z - info: 50. Make an HTTP request to /NotificationBeacons (no keys) - pass
2016-03-14T17:20:37.383Z - info: 51. Make an HTTP request to /NotificationBeacons before calling start - pass
2016-03-14T17:20:37.384Z - info: 52. #testThaliPeerAction - test getters - pass
2016-03-14T17:20:37.384Z - info: 53. #testThaliPeerAction - start and kill - pass
2016-03-14T17:20:37.385Z - info: 54. #testThaliPeerAction - double start - pass
2016-03-14T17:20:37.385Z - info: 55. #testThaliPeerAction - start after kill - pass
2016-03-14T17:20:37.386Z - info: 56. #testThaliPeerAction - make sure ids are unique - pass
2016-03-14T17:20:37.386Z - info: 57. Test PeerConnectionInformation basics - pass
2016-03-14T17:20:37.387Z - info: 58. Test PeerDictionary basic functionality - pass
2016-03-14T17:20:37.387Z - info: 59. Test PeerDictionary with multiple entries. - pass
2016-03-14T17:20:37.388Z - info: 60. RESOLVED entries are removed before WAITING state entry. - pass
2016-03-14T17:20:37.388Z - info: 61. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass
2016-03-14T17:20:37.389Z - info: 62. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass
2016-03-14T17:20:37.389Z - info: 63. #ThaliPeerPoolInterface - bad enqueues - pass
2016-03-14T17:20:37.390Z - info: 64. #ThaliPeerPoolInterface - do not allow same object type - pass
2016-03-14T17:20:37.390Z - info: 65. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass
2016-03-14T17:20:37.391Z - info: 66. compareBufferArrays - pass

2016-03-14T17:20:37.392Z - info: 67. Call start twice and get error - pass
2016-03-14T17:20:37.392Z - info: 68. Start and make sure it runs - pass

2016-03-14T17:20:37.393Z - info: 69. Make sure getTimeWhenRun is right after start - pass

2016-03-14T17:20:37.397Z - info: 70. Make sure getTimeWhenRun is -1 after function is called - pass

2016-03-14T17:20:37.398Z - info: 71. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass

2016-03-14T17:20:37.399Z - info: 72. Test TransientState - pass

2016-03-14T17:20:37.399Z - info: 73. No peers and empty database - pass

2016-03-14T17:20:37.400Z - info: 74. One peer and empty DB - pass
2016-03-14T17:20:37.401Z - info: 75. One peer with _Local set behind current seq - pass

2016-03-14T17:20:37.402Z - info: 76. One peer with _Local set equal to current seq - pass

2016-03-14T17:20:37.402Z - info: 77. One peer with _Local set ahead of current seq (and no this should not happen) - pass

2016-03-14T17:20:37.403Z - info: 78. Three peers, one not in DB, one behind and one ahead - pass

2016-03-14T17:20:37.404Z - info: 79. More than maximum peers, make sure we only send maximum allowed - pass
2016-03-14T17:20:37.404Z - info: 80. two peers with empty DB, update the doc - pass

2016-03-14T17:20:37.405Z - info: 81. add doc and make sure tokens refresh when they expire - pass

2016-03-14T17:20:37.406Z - info: 82. start and stop and start and stop - pass

2016-03-14T17:20:37.407Z - info: 83. two identical starts in a row - pass

2016-03-14T17:20:37.407Z - info: 84. two different starts in a row - pass

2016-03-14T17:20:37.408Z - info: 85. two stops and a start and two stops - pass

2016-03-14T17:20:37.409Z - info: 86. we properly enqueue requests so no then needed - pass

2016-03-14T17:20:37.409Z - info: 87. test calculateSeqPointKeyId - pass

2016-03-14T17:20:37.410Z - info: 88. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass

2016-03-14T17:20:37.411Z - info: 89. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-03-14T17:20:37.411Z - info: 90. messages with invalid location or USN should be ignored - pass

2016-03-14T17:20:37.412Z - info: 91. verify that Thali-specific messages are filtered correctly - pass

2016-03-14T17:20:37.413Z - info: 92. #startListeningForAdvertisements should fail if start not called - pass

2016-03-14T17:20:37.414Z - info: 93. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-14T17:20:37.414Z - info: 94. #start should fail if called twice in a row - pass

2016-03-14T17:20:37.415Z - info: 95. should not be started after stop is called - pass

2016-03-14T17:20:37.416Z - info: 96. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass

2016-03-14T17:20:37.416Z - info: 97. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass

2016-03-14T17:20:37.417Z - info: 98. #startUpdateAdvertisingAndListening should start hosting given router object - pass

2016-03-14T17:20:37.418Z - info: 99. #stop can be called multiple times in a row - pass

2016-03-14T17:20:37.418Z - info: 100. #startListeningForAdvertisements can be called multiple times in a row - pass

2016-03-14T17:20:37.419Z - info: 101. #stopListeningForAdvertisements can be called multiple times in a row - pass

2016-03-14T17:20:37.420Z - info: 102. #stopAdvertisingAndListening can be called multiple times in a row - pass

2016-03-14T17:20:37.421Z - info: 103. functions are run from a queue in the right order - pass

2016-03-14T17:20:37.421Z - info: 104. #ThaliPeerPoolDefault - single action - pass

2016-03-14T17:20:37.431Z - info: 105. #ThaliPeerPoolDefault - multiple actions - pass

2016-03-14T17:20:37.438Z - info: 

-== END ==-

2016-03-14T17:20:37.618Z - info: Running on ios test: 91. verify that Thali-specific messages are filtered correctly

2016-03-14T17:20:38.446Z - debug: Socket disconnected: transport close 1 (LGE-LG-H815)

2016-03-14T17:20:38.823Z - info: Running on ios test: 92. #startListeningForAdvertisements should fail if start not called

2016-03-14T17:20:39.882Z - info: Running on ios test: 93. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-14T17:20:40.609Z - info: Running on ios test: 94. #start should fail if called twice in a row

2016-03-14T17:20:41.303Z - info: Running on ios test: 95. should not be started after stop is called

2016-03-14T17:20:42.195Z - info: Running on ios test: 96. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-14T17:20:42.844Z - info: Running on ios test: 97. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-14T17:20:43.409Z - info: Running on ios test: 98. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-14T17:20:44.014Z - info: Running on ios test: 99. #stop can be called multiple times in a row

2016-03-14T17:20:44.451Z - info: Running on ios test: 100. #startListeningForAdvertisements can be called multiple times in a row

2016-03-14T17:20:45.194Z - info: Running on ios test: 101. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-14T17:20:45.569Z - info: Running on ios test: 102. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-14T17:20:45.949Z - info: Running on ios test: 103. functions are run from a queue in the right order

2016-03-14T17:20:46.458Z - info: Running on ios test: 104. #ThaliPeerPoolDefault - single action

2016-03-14T17:20:46.955Z - info: Running on ios test: 105. #ThaliPeerPoolDefault - multiple actions

2016-03-14T17:20:47.495Z - info: Test run on ios complete

2016-03-14T17:20:47.496Z - info: 

-== UNIT TEST RESULTS ==-

2016-03-14T17:20:47.498Z - info: PLATFORM: ios

2016-03-14T17:20:47.499Z - info: RESULT: PASS

2016-03-14T17:20:47.500Z - info: 105 of 105 tests completed

2016-03-14T17:20:47.501Z - info: 105/105 passed (0 failures)

2016-03-14T17:20:47.502Z - info: --- Test Details ---



2016-03-14T17:20:47.503Z - info: 1. closeAll can close even when connections open - pass

2016-03-14T17:20:47.504Z - info: 2. closeAll with promise - pass

2016-03-14T17:20:47.505Z - info: 3. multiplex can send data - pass

2016-03-14T17:20:47.506Z - info: 4. enqueue and run in order - pass

2016-03-14T17:20:47.507Z - info: 5. enqueueAtTop and run backwards - pass

2016-03-14T17:20:47.508Z - info: 6. mix enqueue and enqueueAtTop - pass

2016-03-14T17:20:47.509Z - info: 7. queues handled independently - pass

2016-03-14T17:20:47.510Z - info: 8. basic - pass

2016-03-14T17:20:47.511Z - info: 9. another - pass

2016-03-14T17:20:47.512Z - info: 10. #startListeningForAdvertisements should fail if start not called - pass

2016-03-14T17:20:47.513Z - info: 11. #startUpdateAdvertisingAndListening should fail if start not called - pass

2016-03-14T17:20:47.513Z - info: 12. should be able to call #stopListeningForAdvertisements many times - pass

2016-03-14T17:20:47.514Z - info: 13. should be able to call #startListeningForAdvertisements many times - pass

2016-03-14T17:20:47.515Z - info: 14. should be able to call #startUpdateAdvertisingAndListening many times - pass

2016-03-14T17:20:47.516Z - info: 15. should be able to call #stopAdvertisingAndListening many times - pass

2016-03-14T17:20:47.517Z - info: 16. #start should fail if called twice in a row - pass

2016-03-14T17:20:47.518Z - info: 17. does not emit duplicate discoveryAdvertisingStateUpdate - pass

2016-03-14T17:20:47.519Z - info: 18. does not send duplicate availability changes - pass

2016-03-14T17:20:47.520Z - info: 19. can get the network status - pass

2016-03-14T17:20:47.521Z - info: 20. wifi peer is marked unavailable if announcements stop - pass

2016-03-14T17:20:47.522Z - info: 21. can get the network status before starting - pass

2016-03-14T17:20:47.522Z - info: 22. Test BEACONS_RETRIEVED_AND_PARSED locally - pass

2016-03-14T17:20:47.523Z - info: 23. Test HTTP_BAD_RESPONSE locally - pass

2016-03-14T17:20:47.524Z - info: 24. Test NETWORK_PROBLEM locally - pass

2016-03-14T17:20:47.525Z - info: 25. Test timeout locally - pass

2016-03-14T17:20:47.527Z - info: 26. Call the start two times - pass

2016-03-14T17:20:47.529Z - info: 27. Call the kill before calling the start - pass

2016-03-14T17:20:47.530Z - info: 28. Call the kill immediately after the start - pass

2016-03-14T17:20:47.533Z - info: 29. Call the kill while waiting a response from the server - pass

2016-03-14T17:20:47.535Z - info: 30. Test to exceed the max content size locally - pass

2016-03-14T17:20:47.537Z - info: 31. #generatePreambleAndBeacons bad args - pass

2016-03-14T17:20:47.545Z - info: 32. #generatePreambleAndBeacons empty keys to notify - pass

2016-03-14T17:20:47.547Z - info: 33. #generatePreambleAndBeacons multiple keys to notify - pass

2016-03-14T17:20:47.549Z - info: 34. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass

2016-03-14T17:20:47.550Z - info: 35. #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass

2016-03-14T17:20:47.552Z - info: 36. #parseBeacons expiration out of range lower - pass

2016-03-14T17:20:47.554Z - info: 37. #parseBeacons expiration out of range lower - pass

2016-03-14T17:20:47.555Z - info: 38. #parseBeacons no beacons returns null - pass

2016-03-14T17:20:47.557Z - info: 39. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass

2016-03-14T17:20:47.559Z - info: 40. #parseBeacons addressBookCallback fails decrypt - pass

2016-03-14T17:20:47.560Z - info: 41. #parseBeacons addressBookCallback returns no matches - pass

2016-03-14T17:20:47.562Z - info: 42. #parseBeacons addressBookCallback returns spurious match - pass

2016-03-14T17:20:47.594Z - info: 43. #parseBeacons addressBookCallback returns public key - pass

2016-03-14T17:20:47.597Z - info: 44. #parseBeacons with beacons both for and not for the user - pass

2016-03-14T17:20:47.599Z - info: 45. Start and stop ThaliNotificationServer - pass

2016-03-14T17:20:47.601Z - info: 46. Pass an empty array to ThaliNotificationServer.start - pass

2016-03-14T17:20:47.602Z - info: 47. Pass a string to ThaliNotificationServer.start - pass

2016-03-14T17:20:47.604Z - info: 48. Pass an empty parameter to ThaliNotificationServer.start - pass

2016-03-14T17:20:47.606Z - info: 49. Make an HTTP request to /NotificationBeacons - pass

2016-03-14T17:20:47.607Z - info: 50. Make an HTTP request to /NotificationBeacons (no keys) - pass

2016-03-14T17:20:47.609Z - info: 51. Make an HTTP request to /NotificationBeacons before calling start - pass

2016-03-14T17:20:47.610Z - info: 52. #testThaliPeerAction - test getters - pass

2016-03-14T17:20:47.612Z - info: 53. #testThaliPeerAction - start and kill - pass

2016-03-14T17:20:47.614Z - info: 54. #testThaliPeerAction - double start - pass

2016-03-14T17:20:47.615Z - info: 55. #testThaliPeerAction - start after kill - pass

2016-03-14T17:20:47.617Z - info: 56. #testThaliPeerAction - make sure ids are unique - pass

2016-03-14T17:20:47.619Z - info: 57. Test PeerConnectionInformation basics - pass

2016-03-14T17:20:47.620Z - info: 58. Test PeerDictionary basic functionality - pass

2016-03-14T17:20:47.625Z - info: 59. Test PeerDictionary with multiple entries. - pass

2016-03-14T17:20:47.627Z - info: 60. RESOLVED entries are removed before WAITING state entry. - pass
2016-03-14T17:20:47.627Z - info: 61. WAITING entries are removed before CONTROLLED_BY_POOL state entry. - pass
2016-03-14T17:20:47.628Z - info: 62. When CONTROLLED_BY_POOL entry is removed and kill is called. - pass
2016-03-14T17:20:47.629Z - info: 63. #ThaliPeerPoolInterface - bad enqueues - pass
2016-03-14T17:20:47.629Z - info: 64. #ThaliPeerPoolInterface - do not allow same object type - pass
2016-03-14T17:20:47.630Z - info: 65. #ThaliPeerPoolInterface - make sure we catch kill and dequeue - pass
2016-03-14T17:20:47.630Z - info: 66. compareBufferArrays - pass
2016-03-14T17:20:47.631Z - info: 67. Call start twice and get error - pass
2016-03-14T17:20:47.631Z - info: 68. Start and make sure it runs - pass
2016-03-14T17:20:47.632Z - info: 69. Make sure getTimeWhenRun is right after start - pass
2016-03-14T17:20:47.632Z - info: 70. Make sure getTimeWhenRun is -1 after function is called - pass
2016-03-14T17:20:47.633Z - info: 71. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running - pass
2016-03-14T17:20:47.633Z - info: 72. Test TransientState - pass
2016-03-14T17:20:47.634Z - info: 73. No peers and empty database - pass
2016-03-14T17:20:47.634Z - info: 74. One peer and empty DB - pass
2016-03-14T17:20:47.634Z - info: 75. One peer with _Local set behind current seq - pass
2016-03-14T17:20:47.635Z - info: 76. One peer with _Local set equal to current seq - pass
2016-03-14T17:20:47.635Z - info: 77. One peer with _Local set ahead of current seq (and no this should not happen) - pass
2016-03-14T17:20:47.636Z - info: 78. Three peers, one not in DB, one behind and one ahead - pass
2016-03-14T17:20:47.636Z - info: 79. More than maximum peers, make sure we only send maximum allowed - pass
2016-03-14T17:20:47.637Z - info: 80. two peers with empty DB, update the doc - pass
2016-03-14T17:20:47.638Z - info: 81. add doc and make sure tokens refresh when they expire - pass
2016-03-14T17:20:47.640Z - info: 82. start and stop and start and stop - pass
2016-03-14T17:20:47.641Z - info: 83. two identical starts in a row - pass
2016-03-14T17:20:47.642Z - info: 84. two different starts in a row - pass
2016-03-14T17:20:47.642Z - info: 85. two stops and a start and two stops - pass
2016-03-14T17:20:47.643Z - info: 86. we properly enqueue requests so no then needed - pass
2016-03-14T17:20:47.643Z - info: 87. test calculateSeqPointKeyId - pass
2016-03-14T17:20:47.644Z - info: 88. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass
2016-03-14T17:20:47.644Z - info: 89. #startUpdateAdvertisingAndListening should use different USN after every invocation - pass
2016-03-14T17:20:47.645Z - info: 90. messages with invalid location or USN should be ignored - pass
2016-03-14T17:20:47.646Z - info: 91. verify that Thali-specific messages are filtered correctly - pass
2016-03-14T17:20:47.646Z - info: 92. #startListeningForAdvertisements should fail if start not called - pass
2016-03-14T17:20:47.647Z - info: 93. #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-03-14T17:20:47.647Z - info: 94. #start should fail if called twice in a row - pass
2016-03-14T17:20:47.647Z - info: 95. should not be started after stop is called - pass
2016-03-14T17:20:47.648Z - info: 96. #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass
2016-03-14T17:20:47.648Z - info: 97. #startUpdateAdvertisingAndListening should fail if router server starting fails - pass
2016-03-14T17:20:47.649Z - info: 98. #startUpdateAdvertisingAndListening should start hosting given router object - pass
2016-03-14T17:20:47.650Z - info: 99. #stop can be called multiple times in a row - pass
2016-03-14T17:20:47.650Z - info: 100. #startListeningForAdvertisements can be called multiple times in a row - pass

2016-03-14T17:20:47.651Z - info: 101. #stopListeningForAdvertisements can be called multiple times in a row - pass

2016-03-14T17:20:47.652Z - info: 102. #stopAdvertisingAndListening can be called multiple times in a row - pass

2016-03-14T17:20:47.654Z - info: 103. functions are run from a queue in the right order - pass

2016-03-14T17:20:47.655Z - info: 104. #ThaliPeerPoolDefault - single action - pass

2016-03-14T17:20:47.656Z - info: 105. #ThaliPeerPoolDefault - multiple actions - pass
2016-03-14T17:20:47.657Z - info: 

-== END ==-


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
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62754403b276699_416__Implementation_of_ThalinotificationAction_juhanak/thali01_samsung-SM-A500FU.md)

####Node name: thali03
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Android task is completed. [SUCCESS]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/62754403b276699_416__Implementation_of_ThalinotificationAction_juhanak/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/62754403b276699_416__Implementation_of_ThalinotificationAction_juhanak/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Android task is completed. [SUCCESS]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/62754403b276699_416__Implementation_of_ThalinotificationAction_juhanak/thali05_LGE-LG-H815.md)

####Node name: thali06
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:0 
child process exited with code 0 on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:null 
child process exited with code null on device FA55PYS00566 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62754403b276699_416__Implementation_of_ThalinotificationAction_juhanak/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/62754403b276699_416__Implementation_of_ThalinotificationAction_juhanak/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:0 
child process exited with code 0 on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62754403b276699_416__Implementation_of_ThalinotificationAction_juhanak/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:0 
child process exited with code 0 on device 4325e43f 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62754403b276699_416__Implementation_of_ThalinotificationAction_juhanak/thali08_samsung-SM-A300FU.md)




###iOS Logs
[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/62754403b276699_416__Implementation_of_ThalinotificationAction_juhanak/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/62754403b276699_416__Implementation_of_ThalinotificationAction_juhanak/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/62754403b276699_416__Implementation_of_ThalinotificationAction_juhanak/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/62754403b276699_416__Implementation_of_ThalinotificationAction_juhanak/iOS_IpadAir2-1.md)



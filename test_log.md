#### Test 79751015d1e118e Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":5}}
2016-08-05T11:15:48.349Z - info: Require 3 ios devices

2016-08-05T11:15:48.384Z - info: Require 3 android devices

2016-08-05T11:15:48.441Z - info: listening on *:3000

2016-08-05T11:15:49.118Z - debug: Device presented: motorola-Nexus 6 (18e3ce40-8e3b-4f3b-8885-8896e0281d8a) - android 6.0.1

2016-08-05T11:15:50.082Z - debug: Device presented: motorola-Nexus 6 (18e3ce40-8e3b-4f3b-8885-8896e0281d8a) - android 6.0.1

2016-08-05T11:15:50.088Z - info: Updating existing device: motorola-Nexus 6 (18e3ce40-8e3b-4f3b-8885-8896e0281d8a)

2016-08-05T11:15:52.313Z - debug: Device presented: samsung-SM-G900F (2378f8fe-4053-4f0a-a154-1b7bab7a2152) - android 6.0.1

2016-08-05T11:15:53.339Z - debug: Device presented: samsung-SM-G900F (2378f8fe-4053-4f0a-a154-1b7bab7a2152) - android 6.0.1

2016-08-05T11:15:53.340Z - info: Updating existing device: samsung-SM-G900F (2378f8fe-4053-4f0a-a154-1b7bab7a2152)

2016-08-05T11:16:33.189Z - debug: Device presented: samsung-SM-N9005 (1160510f-3880-40a1-b166-1817bbb7743c) - android 5.0

2016-08-05T11:16:34.224Z - debug: Device presented: LGE-LG-D855 (88b463a9-ffe8-44bf-8d06-998bd1f5b679) - android 5.0

2016-08-05T11:16:49.174Z - debug: Device presented: LGE-LG-D722 (488dc8c2-b8ab-4408-b79c-c12b3f07c99f) - android 5.0.2

2016-08-05T11:16:49.175Z - info: All 5 android devices are present

2016-08-05T11:16:49.178Z - info: Disqualifying device with unsupported hardware: samsung-SM-N9005

2016-08-05T11:16:49.185Z - info: Disqualifying device with unsupported hardware: LGE-LG-D855

2016-08-05T11:16:49.187Z - info: Disqualifying device with unsupported hardware: LGE-LG-D722

2016-08-05T11:16:49.194Z - info: Starting unit test run on 2 android devices

2016-08-05T11:16:50.200Z - info: Socket to device samsung-SM-N9005 disconnected: transport close

2016-08-05T11:16:50.238Z - info: Socket to device LGE-LG-D855 disconnected: transport close

2016-08-05T11:16:50.326Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-08-05T11:16:50.379Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-05T11:16:50.693Z - info: Running on android test: 2. emits incomingConnectionState

2016-08-05T11:16:50.997Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-08-05T11:16:51.281Z - info: Running on android test: 4. native server connections all up

2016-08-05T11:16:51.600Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-08-05T11:16:51.904Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-08-05T11:16:52.249Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-08-05T11:16:52.548Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-08-05T11:16:52.854Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-08-05T11:16:53.769Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-08-05T11:16:54.003Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-08-05T11:16:54.352Z - info: Running on android test: 12. #_doImmediateSeqUpdate - server is not there

2016-08-05T11:16:54.707Z - info: Running on android test: 13. #_doImmediateSeqUpdate - server accepts & closes connection

2016-08-05T11:16:54.950Z - info: Running on android test: 14. #_doImmediateSeqUpdate - server always returns 500

2016-08-05T11:16:55.286Z - info: Running on android test: 15. #_doImmediateSeqUpdate - create new seq doc

2016-08-05T11:16:57.452Z - info: Running on android test: 16. #_doImmediateSeqUpdate - doc exists, need to get rev and update

2016-08-05T11:16:58.307Z - info: Running on android test: 17. #_doImmediateSeqUpdate - update seq three times

2016-08-05T11:16:59.422Z - info: Running on android test: 18. #_doImmediateSeqUpdate - rev got changed under us

2016-08-05T11:17:00.305Z - info: Running on android test: 19. #_doImmediateSeqUpdate - fail if stop is called

2016-08-05T11:17:00.565Z - info: Running on android test: 20. #_doImmediateSeqUpdate - stop after get but before put fails right

2016-08-05T11:17:01.078Z - info: Running on android test: 21. #update - fail if stop is called

2016-08-05T11:17:01.334Z - info: Running on android test: 22. #update - set seq for first time

2016-08-05T11:17:03.128Z - info: Running on android test: 23. #update - Fail on bad seq value

2016-08-05T11:17:03.901Z - info: Running on android test: 24. #update - do we cancel timer properly on an immediate?

2016-08-05T11:17:04.766Z - info: Running on android test: 25. #update - do we wait for blocked update

2016-08-05T11:17:05.471Z - info: Running on android test: 26. #update - test that we wait long enough

2016-08-05T11:17:07.381Z - info: Running on android test: 27. #update - test that we pick up new sequences while we wait

2016-08-05T11:17:09.080Z - info: Running on android test: 28. Coordinated seq test

2016-08-05T11:22:09.832Z - warn: Failed on android test: 28. Coordinated seq test

2016-08-05T11:22:09.833Z - info: Running on android test: 29. closeAll can close even when connections open

2016-08-05T11:22:10.792Z - info: Running on android test: 30. closeAll with promise

2016-08-05T11:22:11.567Z - info: Running on android test: 31. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-08-05T11:22:18.627Z - info: Running on android test: 32. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-08-05T11:22:18.953Z - info: Running on android test: 33. enqueue and run in order

2016-08-05T11:22:19.424Z - info: Running on android test: 34. enqueueAtTop and run backwards

2016-08-05T11:22:19.621Z - info: Running on android test: 35. mix enqueue and enqueueAtTop

2016-08-05T11:22:19.967Z - info: Running on android test: 36. queues handled independently

2016-08-05T11:22:20.237Z - info: Running on android test: 37. basic

2016-08-05T11:22:20.445Z - info: Running on android test: 38. another

2016-08-05T11:22:20.647Z - info: Running on android test: 39. can pass data in setup

2016-08-05T11:22:20.853Z - info: Running on android test: 40. #startListeningForAdvertisements should fail if start not called

2016-08-05T11:22:21.065Z - info: Running on android test: 41. #startUpdateAdvertisingAndListening should fail if start not called

2016-08-05T11:22:21.305Z - info: Running on android test: 42. should be able to call #stopListeningForAdvertisements many times

2016-08-05T11:22:21.569Z - info: Running on android test: 43. should be able to call #startListeningForAdvertisements many times

2016-08-05T11:22:23.232Z - info: Running on android test: 44. should be able to call #startUpdateAdvertisingAndListening many times

2016-08-05T11:22:24.546Z - info: Running on android test: 45. should be able to call #stopAdvertisingAndListening many times

2016-08-05T11:22:24.843Z - info: Running on android test: 46. #start should fail if called twice in a row

2016-08-05T11:22:25.080Z - info: Running on android test: 47. does not emit duplicate discoveryAdvertisingStateUpdate

2016-08-05T11:22:27.046Z - info: Running on android test: 48. does not send duplicate availability changes

2016-08-05T11:22:27.237Z - info: Running on android test: 49. can get the network status

2016-08-05T11:22:27.417Z - info: Running on android test: 50. wifi peer is marked unavailable if announcements stop

2016-08-05T11:22:29.667Z - info: Running on android test: 51. Can call start/stopListeningForAdvertisements

2016-08-05T11:22:31.348Z - info: Running on android test: 52. Client to server request coordinated

2016-08-05T11:24:37.416Z - warn: Failed on android test: 52. Client to server request coordinated

2016-08-05T11:24:37.417Z - info: Running on android test: 53. Test BEACONS_RETRIEVED_AND_PARSED locally

2016-08-05T11:24:37.850Z - info: Running on android test: 54. Test HTTP_BAD_RESPONSE locally

2016-08-05T11:24:38.199Z - info: Running on android test: 55. Test NETWORK_PROBLEM locally

2016-08-05T11:24:38.648Z - info: Running on android test: 56. Call the start two times

2016-08-05T11:24:39.548Z - info: Running on android test: 57. Call the kill before calling the start

2016-08-05T11:24:39.809Z - info: Running on android test: 58. Call the kill immediately after the start

2016-08-05T11:24:40.069Z - info: Running on android test: 59. Call the kill while waiting a response from the server

2016-08-05T11:24:42.484Z - info: Running on android test: 60. Test to exceed the max content size locally

2016-08-05T11:24:42.903Z - info: Running on android test: 61. Close the server socket while the client is waiting a response from the server. Local test.

2016-08-05T11:24:45.348Z - info: Running on android test: 62. Close the client socket while the client is waiting a response from the server. Local test.

2016-08-05T11:24:47.806Z - info: Running on android test: 63. #generatePreambleAndBeacons bad args

2016-08-05T11:24:48.043Z - info: Running on android test: 64. #generatePreambleAndBeacons empty keys to notify

2016-08-05T11:24:48.234Z - info: Running on android test: 65. #generatePreambleAndBeacons multiple keys to notify

2016-08-05T11:24:48.547Z - info: Running on android test: 66. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-08-05T11:24:48.767Z - info: Running on android test: 67. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-08-05T11:24:48.993Z - info: Running on android test: 68. #parseBeacons expiration out of range lower

2016-08-05T11:24:49.285Z - info: Running on android test: 69. #parseBeacons expiration out of range lower

2016-08-05T11:24:49.555Z - info: Running on android test: 70. #parseBeacons no beacons returns null

2016-08-05T11:24:49.737Z - info: Running on android test: 71. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-08-05T11:24:49.935Z - info: Running on android test: 72. #parseBeacons addressBookCallback fails decrypt

2016-08-05T11:24:50.274Z - info: Running on android test: 73. #parseBeacons addressBookCallback returns no matches

2016-08-05T11:24:50.676Z - info: Running on android test: 74. #parseBeacons addressBookCallback returns spurious match

2016-08-05T11:24:51.025Z - info: Running on android test: 75. #parseBeacons addressBookCallback returns public key

2016-08-05T11:24:51.429Z - info: Running on android test: 76. validate generatePskIdentityField

2016-08-05T11:24:51.704Z - info: Running on android test: 77. validate generatePskSecret

2016-08-05T11:24:51.964Z - info: Running on android test: 78. validate generatePskSecrets

2016-08-05T11:24:52.362Z - info: Running on android test: 79. validate generateBeaconStreamAndSecrets

2016-08-05T11:24:52.645Z - info: Running on android test: 80. Add two Peers.

2016-08-05T11:24:52.930Z - info: Running on android test: 81. TCP_NATIVE peer loses DNS

2016-08-05T11:24:53.202Z - info: Running on android test: 82. Received beacons with no values for us

2016-08-05T11:24:53.629Z - info: Running on android test: 83. Resolves an action locally

2016-08-05T11:24:54.028Z - info: Running on android test: 84. Resolves an action locally using ThaliPeerPoolDefault

2016-08-05T11:24:54.466Z - info: Running on android test: 85. Action fails because of a bad hostname.

2016-08-05T11:24:59.807Z - info: Running on android test: 86. hostaddress is removed when the action is running. 

2016-08-05T11:25:02.182Z - info: Running on android test: 87. Client to server request locally

2016-08-05T11:25:02.581Z - info: Running on android test: 88. Test ThaliPskMapCache clean and expiration

2016-08-05T11:25:03.819Z - info: Running on android test: 89. Test ThaliPskMapCache getSecret and getPublic

2016-08-05T11:25:05.262Z - info: Running on android test: 90. Test ThaliPskMapCache multiple entries

2016-08-05T11:25:08.187Z - info: Running on android test: 91. Start and stop ThaliNotificationServer

2016-08-05T11:25:08.506Z - info: Running on android test: 92. Pass an empty array to ThaliNotificationServer.start

2016-08-05T11:25:08.759Z - info: Running on android test: 93. Pass a string to ThaliNotificationServer.start

2016-08-05T11:25:08.986Z - info: Running on android test: 94. Pass an empty parameter to ThaliNotificationServer.start

2016-08-05T11:25:09.193Z - info: Running on android test: 95. Make an HTTP request to /NotificationBeacons

2016-08-05T11:25:09.654Z - info: Running on android test: 96. Make an HTTP request to /NotificationBeacons (no keys)

2016-08-05T11:25:09.904Z - info: Running on android test: 97. Make an HTTP request to /NotificationBeaconsbefore calling start

2016-08-05T11:25:10.168Z - info: Running on android test: 98. #testThaliPeerAction - test getters

2016-08-05T11:25:10.365Z - info: Running on android test: 99. #testThaliPeerAction - start and kill

2016-08-05T11:25:10.524Z - info: Running on android test: 100. #testThaliPeerAction - double start

2016-08-05T11:25:10.681Z - info: Running on android test: 101. #testThaliPeerAction - start after kill

2016-08-05T11:25:10.902Z - info: Running on android test: 102. #testThaliPeerAction - make sure ids are unique

2016-08-05T11:25:11.059Z - info: Running on android test: 103. Test PeerConnectionInformation basics

2016-08-05T11:25:11.217Z - info: Running on android test: 104. Test PeerDictionary basic functionality

2016-08-05T11:25:11.436Z - info: Running on android test: 105. Test PeerDictionary with multiple entries.

2016-08-05T11:25:13.450Z - info: Running on android test: 106. RESOLVED entries are removed before WAITING state entry.

2016-08-05T11:25:14.237Z - info: Running on android test: 107. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

2016-08-05T11:25:15.020Z - info: Running on android test: 108. When CONTROLLED_BY_POOL entry is removed and kill is called.

2016-08-05T11:25:15.808Z - info: Running on android test: 109. #ThaliPeerPoolInterface - bad enqueues

2016-08-05T11:25:15.949Z - info: Running on android test: 110. #ThaliPeerPoolInterface - do not allow same object type

2016-08-05T11:25:16.172Z - info: Running on android test: 111. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-08-05T11:25:16.379Z - info: Running on android test: 112. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent

2016-08-05T11:25:16.597Z - info: Running on android test: 113. Make sure peerDictionaryKey is reasonable

2016-08-05T11:25:16.768Z - info: Running on android test: 114. Make sure start works

2016-08-05T11:25:16.969Z - info: Running on android test: 115. Make sure stop works

2016-08-05T11:25:17.198Z - info: Running on android test: 116. Simple peer event

2016-08-05T11:25:17.476Z - info: Running on android test: 117. Coordinated pull replication from notification test

2016-08-05T11:30:17.925Z - warn: Failed on android test: 117. Coordinated pull replication from notification test

2016-08-05T11:30:17.928Z - info: Running on android test: 118. Server is not there

2016-08-05T11:30:18.275Z - info: Running on android test: 119. Server accepts & closes connection

2016-08-05T11:30:18.588Z - info: Running on android test: 120. Server always returns 500

2016-08-05T11:30:19.015Z - info: Running on android test: 121. Server always returns 401

2016-08-05T11:30:19.342Z - info: Running on android test: 122. Server always returns 403

2016-08-05T11:30:19.655Z - info: Running on android test: 123. Make sure docs replicate

2016-08-05T11:30:22.012Z - info: Running on android test: 124. Do nothing and make sure we time out

2016-08-05T11:30:24.553Z - info: Running on android test: 125. Do something and make sure we time out

2016-08-05T11:30:28.191Z - info: Running on android test: 126. Start replicating and then catch error when server goes

2016-08-05T11:30:29.011Z - info: Running on android test: 127. Coordinated replication action test

2016-08-05T11:35:29.166Z - info: Socket to device motorola-Nexus 6 disconnected: transport close

2016-08-05T11:35:31.803Z - info: Socket to device samsung-SM-G900F disconnected: transport close


 
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
[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/79751015d1e118e_Check_811_failures_in_CI_do_not_merge__czyzm/thali05_samsung-SM-N9005.md)

[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/79751015d1e118e_Check_811_failures_in_CI_do_not_merge__czyzm/thali05_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/79751015d1e118e_Check_811_failures_in_CI_do_not_merge__czyzm/thali05_LGE-LG-D855.md)

####Node name: thali08
Console output:
```


 Marshmallow device. Granting ACCESS_COARSE_LOCATION permission


 Marshmallow device. Granting ACCESS_COARSE_LOCATION permission
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1G429CRK 
Error! Unexpected exit on device 0be0c6c6 app:com.test.thalitest code:null 
child process exited with code null on device 0be0c6c6 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/79751015d1e118e_Check_811_failures_in_CI_do_not_merge__czyzm/thali08_motorola-Nexus 6.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/79751015d1e118e_Check_811_failures_in_CI_do_not_merge__czyzm/thali08_samsung-SM-G900F.md)





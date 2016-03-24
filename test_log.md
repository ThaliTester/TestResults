#### Test 639107040172e2e Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-03-24T21:21:36.424Z - info: listening on *:3000

2016-03-24T21:21:37.429Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:0

2016-03-24T21:21:37.495Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:1

2016-03-24T21:21:39.540Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:2

2016-03-24T21:21:41.672Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:3

2016-03-24T21:21:41.673Z - info: Required number of ios devices presented (3)

2016-03-24T21:21:41.678Z - info: Starting unit test run for platform: ios

2016-03-24T21:21:42.378Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-24T21:21:42.978Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-24T21:21:43.364Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-24T21:21:43.764Z - info: Running on ios test: 4. native server connections all up

2016-03-24T21:21:43.795Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:4

2016-03-24T21:21:44.430Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-24T21:21:44.888Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-24T21:21:45.281Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-24T21:21:45.751Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-24T21:21:46.293Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-24T21:21:55.239Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-24T21:21:55.887Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-24T21:21:56.404Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-24T21:21:56.842Z - info: Running on ios test: 13. closeAll with promise

2016-03-24T21:21:57.235Z - info: Running on ios test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-03-24T21:21:57.657Z - info: Running on ios test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-03-24T21:21:58.080Z - info: Running on ios test: 16. multiplex can send data

2016-03-24T21:21:58.327Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:5

2016-03-24T21:21:58.331Z - info: Required number of android devices presented (3)

2016-03-24T21:21:58.333Z - info: Starting unit test run for platform: android

2016-03-24T21:21:58.578Z - info: Running on ios test: 17. enqueue and run in order

2016-03-24T21:21:59.194Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-24T21:21:59.381Z - info: Running on ios test: 18. enqueueAtTop and run backwards

2016-03-24T21:21:59.938Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-24T21:22:00.055Z - info: Running on ios test: 19. mix enqueue and enqueueAtTop

2016-03-24T21:22:01.046Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-24T21:22:02.288Z - info: Running on android test: 4. native server connections all up

2016-03-24T21:22:03.300Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-24T21:22:04.715Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-24T21:22:05.662Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-24T21:22:06.141Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-24T21:22:06.552Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-24T21:22:07.084Z - info: Running on ios test: 20. queues handled independently

2016-03-24T21:22:07.425Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-24T21:22:07.504Z - info: Running on ios test: 21. basic

2016-03-24T21:22:07.912Z - info: Running on ios test: 22. another

2016-03-24T21:22:08.016Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-24T21:22:08.266Z - info: Running on ios test: 23. can pass data in setup

2016-03-24T21:22:08.685Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-24T21:22:08.702Z - info: Running on ios test: 24. #startListeningForAdvertisements should fail if start not called

2016-03-24T21:22:09.094Z - info: Running on ios test: 25. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-24T21:22:09.150Z - info: Running on android test: 13. closeAll with promise

2016-03-24T21:22:09.501Z - info: Running on ios test: 26. should be able to call #stopListeningForAdvertisements many times

2016-03-24T21:22:09.558Z - info: Running on android test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-03-24T21:22:09.891Z - info: Running on ios test: 27. should be able to call #startListeningForAdvertisements many times

2016-03-24T21:22:09.977Z - info: Running on android test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-03-24T21:22:10.480Z - info: Running on android test: 16. multiplex can send data

2016-03-24T21:22:10.509Z - info: Running on ios test: 28. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-24T21:22:10.878Z - info: Running on android test: 17. enqueue and run in order

2016-03-24T21:22:11.727Z - info: Running on android test: 18. enqueueAtTop and run backwards

2016-03-24T21:22:13.449Z - info: Running on android test: 19. mix enqueue and enqueueAtTop

2016-03-24T21:22:14.109Z - info: Running on ios test: 29. should be able to call #stopAdvertisingAndListening many times

2016-03-24T21:22:20.438Z - info: Running on android test: 20. queues handled independently

2016-03-24T21:22:25.184Z - info: Running on android test: 21. basic

2016-03-24T21:22:29.572Z - info: Running on android test: 22. another

2016-03-24T21:22:32.458Z - info: Running on android test: 23. can pass data in setup

2016-03-24T21:22:32.891Z - info: Running on android test: 24. #startListeningForAdvertisements should fail if start not called

2016-03-24T21:22:32.894Z - info: Running on ios test: 30. #start should fail if called twice in a row

2016-03-24T21:22:33.284Z - info: Running on android test: 25. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-24T21:22:33.697Z - info: Running on android test: 26. should be able to call #stopListeningForAdvertisements many times

2016-03-24T21:22:34.089Z - info: Running on android test: 27. should be able to call #startListeningForAdvertisements many times

2016-03-24T21:22:34.841Z - info: Running on android test: 28. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-24T21:22:36.174Z - info: Running on android test: 29. should be able to call #stopAdvertisingAndListening many times

2016-03-24T21:22:36.572Z - info: Running on android test: 30. #start should fail if called twice in a row

2016-03-24T21:22:36.990Z - info: Running on android test: 31. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-24T21:22:38.582Z - info: Running on ios test: 31. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-24T21:22:39.209Z - info: Running on ios test: 32. does not send duplicate availability changes

2016-03-24T21:22:39.348Z - info: Running on android test: 32. does not send duplicate availability changes

2016-03-24T21:22:39.763Z - info: Running on ios test: 33. can get the network status

2016-03-24T21:22:39.768Z - info: Running on android test: 33. can get the network status

2016-03-24T21:22:40.222Z - info: Running on android test: 34. wifi peer is marked unavailable if announcements stop

2016-03-24T21:22:42.717Z - info: Running on android test: 35. Can call start/stopListeningForAdvertisements

2016-03-24T21:22:43.271Z - info: Running on android test: 36. Calling startListeningForAdvertisements twice is NOT an error

2016-03-24T21:22:43.938Z - info: Running on android test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-03-24T21:22:44.801Z - info: Running on android test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-24T21:22:45.841Z - info: Running on android test: 39. peerAvailabilityChange is called

2016-03-24T21:22:48.074Z - info: Running on android test: 40. Can connect to a remote peer

2016-03-24T21:23:01.886Z - info: Running on android test: 41. Can shift large amounts of data

2016-03-24T21:23:07.964Z - info: Running on android test: 42. #startListeningForAdvertisements should fail if start not called

2016-03-24T21:23:09.016Z - info: Running on android test: 43. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-24T21:23:12.197Z - info: Running on android test: 44. should be able to call #stopListeningForAdvertisements many times

2016-03-24T21:23:13.772Z - info: Running on android test: 45. should be able to call #startListeningForAdvertisements many times

2016-03-24T21:23:14.400Z - info: Running on android test: 46. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-24T21:23:16.483Z - info: Running on android test: 47. should be able to call #stopAdvertisingAndListening many times

2016-03-24T21:23:18.468Z - info: Running on android test: 48. can get the network status before starting

2016-03-24T21:23:18.921Z - info: Running on android test: 49. error returned with bad router

2016-03-24T21:23:19.327Z - info: Running on android test: 50. all services are stopped when we call stop

2016-03-24T21:23:20.999Z - info: Running on android test: 51. make sure terminateConnection is properly hooked up

2016-03-24T21:23:21.616Z - info: Running on android test: 52. make sure terminateListener is properly hooked up

2016-03-24T21:23:22.147Z - info: Running on android test: 53. make sure we actually call kill connections properly

2016-03-24T21:23:22.700Z - info: Running on android test: 54. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received

2016-03-24T21:23:23.276Z - info: Running on android test: 55. We repeat failedConnection event when we get it from thaliTcpServersManager

2016-03-24T21:23:23.829Z - info: Running on android test: 56. we successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-24T21:23:24.985Z - warn: Failed on android test: 56. we successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-24T21:23:24.986Z - info: Running on android test: 57. can do HTTP requests between peers

2016-03-24T21:23:35.080Z - info: Running on android test: 58. Test BEACONS_RETRIEVED_AND_PARSED locally

2016-03-24T21:23:38.587Z - info: Running on android test: 59. Test HTTP_BAD_RESPONSE locally

2016-03-24T21:23:39.174Z - info: Running on android test: 60. Test NETWORK_PROBLEM locally

2016-03-24T21:23:40.903Z - info: Running on android test: 61. Test timeout locally

2016-03-24T21:23:42.507Z - info: Running on android test: 62. Call the start two times

2016-03-24T21:23:43.128Z - info: Running on android test: 63. Call the kill before calling the start

2016-03-24T21:23:43.685Z - info: Running on android test: 64. Call the kill immediately after the start

2016-03-24T21:23:44.406Z - info: Running on android test: 65. Call the kill while waiting a response from the server

2016-03-24T21:23:44.618Z - info: Running on ios test: 34. wifi peer is marked unavailable if announcements stop

2016-03-24T21:23:47.160Z - info: Running on android test: 66. Test to exceed the max content size locally

2016-03-24T21:23:47.852Z - info: Running on android test: 67. Close the server socket while the client is waiting a response from the server. Local test.

2016-03-24T21:23:50.522Z - info: Running on android test: 68. Close the client socket while the client is waiting a response from the server. Local test.

2016-03-24T21:23:52.702Z - info: Running on ios test: 35. Can call start/stopListeningForAdvertisements

2016-03-24T21:23:53.076Z - info: Running on android test: 69. #generatePreambleAndBeacons bad args

2016-03-24T21:23:53.600Z - info: Running on ios test: 36. Calling startListeningForAdvertisements twice is NOT an error

2016-03-24T21:23:56.581Z - info: Running on android test: 70. #generatePreambleAndBeacons empty keys to notify

2016-03-24T21:23:59.287Z - info: Running on android test: 71. #generatePreambleAndBeacons multiple keys to notify

2016-03-24T21:24:00.237Z - info: Running on android test: 72. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-24T21:24:01.145Z - info: Running on android test: 73. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-24T21:24:02.003Z - info: Running on android test: 74. #parseBeacons expiration out of range lower

2016-03-24T21:24:03.469Z - info: Running on android test: 75. #parseBeacons expiration out of range lower

2016-03-24T21:24:04.314Z - info: Running on android test: 76. #parseBeacons no beacons returns null

2016-03-24T21:24:08.108Z - info: Running on android test: 77. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-24T21:24:12.045Z - info: Running on android test: 78. #parseBeacons addressBookCallback fails decrypt

2016-03-24T21:24:14.702Z - info: Running on android test: 79. #parseBeacons addressBookCallback returns no matches

2016-03-24T21:24:20.177Z - info: Running on android test: 80. #parseBeacons addressBookCallback returns spurious match

2016-03-24T21:24:29.322Z - info: Running on android test: 81. #parseBeacons addressBookCallback returns public key

2016-03-24T21:24:33.677Z - info: Running on android test: 82. validate generatePskIdentityField

2016-03-24T21:24:44.239Z - info: Running on android test: 83. validate generatePskSecret

2016-03-24T21:24:45.163Z - info: Running on android test: 84. Add two Peers.

2016-03-24T21:24:45.810Z - info: Running on android test: 85. TCP_NATIVE peer loses DNS

2016-03-24T21:24:46.375Z - info: Running on android test: 86. Resolves an action locally

2016-03-24T21:24:47.421Z - info: Running on android test: 87. Resolves an action locally using ThaliPeerPoolDefault

2016-03-24T21:24:47.519Z - info: Running on ios test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-03-24T21:24:48.230Z - info: Running on ios test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-24T21:24:48.892Z - info: Running on ios test: 39. peerAvailabilityChange is called

2016-03-24T21:24:49.814Z - info: Running on android test: 88. Action fails because of a bad hostname.

2016-03-24T21:25:03.694Z - info: Running on android test: 89. hostaddress is removed when the action is running. 

2016-03-24T21:25:27.137Z - info: Running on android test: 90. Start and stop ThaliNotificationServer

2016-03-24T21:25:46.673Z - info: Running on android test: 91. Pass an empty array to ThaliNotificationServer.start

2016-03-24T21:26:52.338Z - debug: Socket disconnected: ping timeout 0 (Apple-Iphone5s-1)

2016-03-24T21:27:00.735Z - debug: Socket disconnected: ping timeout 3 (Apple-Iphone6-1)

2016-03-24T21:27:29.544Z - debug: Socket disconnected: transport close 5 (motorola-Nexus 6)

2016-03-24T21:27:51.191Z - debug: Socket disconnected: transport close 6 (NOT YET SET)

2016-03-24T21:28:12.542Z - debug: Socket disconnected: transport close 9 (NOT YET SET)

2016-03-24T21:28:17.618Z - debug: Socket disconnected: transport close 7 (NOT YET SET)

2016-03-24T21:28:34.603Z - debug: Socket disconnected: transport close 12 (NOT YET SET)

2016-03-24T21:41:12.399Z - debug: Socket disconnected: transport close 10 (NOT YET SET)

2016-03-24T21:41:12.439Z - debug: Socket disconnected: transport close 1 (Apple-Iphone5-1)

2016-03-24T21:41:12.453Z - debug: Socket disconnected: transport close 11 (NOT YET SET)

2016-03-24T21:42:59.868Z - debug: Socket disconnected: transport close 2 (LGE-LG-H815)

2016-03-24T21:45:09.282Z - debug: Socket disconnected: transport close 4 (samsung-SM-N910C)

2016-03-24T21:45:11.128Z - debug: Socket disconnected: transport close 8 (NOT YET SET)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m
2016-03-24T21:22:23.134Z - error: Too many emit retries to device: Apple-Iphone6-1

2016-03-24T21:22:49.444Z - error: Too many emit retries to device: Apple-Iphone5s-1

2016-03-24T21:23:24.899Z - error: Too many emit retries to device: Apple-Iphone5s-1

2016-03-24T21:24:02.864Z - error: Too many emit retries to device: Apple-Iphone5s-1

2016-03-24T21:24:58.706Z - error: Too many emit retries to device: Apple-Iphone5s-1

2016-03-24T21:24:58.711Z - error: Too many emit retries to device: Apple-Iphone6-1

2016-03-24T21:25:36.177Z - error: Too many emit retries to device: motorola-Nexus 6

2016-03-24T21:25:36.337Z - error: Too many emit retries to device: Apple-Iphone5s-1

2016-03-24T21:25:36.339Z - error: Too many emit retries to device: Apple-Iphone5-1

2016-03-24T21:25:36.341Z - error: Too many emit retries to device: Apple-Iphone6-1

2016-03-24T21:25:59.530Z - error: Too many emit retries to device: samsung-SM-N910C

2016-03-24T21:26:33.555Z - error: Too many emit retries to device: samsung-SM-N910C

2016-03-24T21:26:33.558Z - error: Too many emit retries to device: motorola-Nexus 6


```


Logs for system : 
```

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


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/639107040172e2e_416_ThaliNotificationClient_juhanak/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/639107040172e2e_416_ThaliNotificationClient_juhanak/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/639107040172e2e_416_ThaliNotificationClient_juhanak/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/639107040172e2e_416_ThaliNotificationClient_juhanak/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/639107040172e2e_416_ThaliNotificationClient_juhanak/iOS_server.md)


###Android Logs
####Node name: thali07
Console output:
```
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
Device test finished on 0c6a0f3c0bdb4e77 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:0 
child process exited with code 0 on device LGH8153b36be34 
Android task is completed. [FAILED]
```
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/639107040172e2e_416_ThaliNotificationClient_juhanak/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/639107040172e2e_416_ThaliNotificationClient_juhanak/thali07_LGE-LG-H815.md)

####Node name: thali08
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1G429CRK 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/639107040172e2e_416_ThaliNotificationClient_juhanak/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/639107040172e2e_416_ThaliNotificationClient_juhanak/thali08_motorola-Nexus 6.md)





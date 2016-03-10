#### Test 62328822054c831 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":10}}
2016-03-10T20:40:26.369Z - info: listening on *:3000

2016-03-10T20:40:27.170Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:0

2016-03-10T20:40:28.550Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:1

2016-03-10T20:40:28.710Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:2

2016-03-10T20:40:28.714Z - info: Required number of ios devices presented (2)

2016-03-10T20:40:28.717Z - info: Starting unit test run for platform: ios

2016-03-10T20:40:29.226Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-10T20:40:29.462Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:3

2016-03-10T20:40:29.463Z - info: Discarding surplus device: Apple-Iphone5-1

2016-03-10T20:40:29.634Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-10T20:40:30.003Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-10T20:40:30.224Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:4

2016-03-10T20:40:30.225Z - info: Required number of android devices presented (2)

2016-03-10T20:40:30.227Z - info: Starting unit test run for platform: android

2016-03-10T20:40:30.404Z - info: Running on ios test: 4. native server connections all up

2016-03-10T20:40:30.844Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-10T20:40:30.984Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-10T20:40:31.365Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-10T20:40:31.559Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-10T20:40:31.951Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-10T20:40:32.201Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-10T20:40:32.318Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:5

2016-03-10T20:40:32.320Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-10T20:40:32.459Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-10T20:40:32.746Z - debug: Socket disconnected: transport close 3 (Apple-Iphone5-1)

2016-03-10T20:40:32.784Z - info: Running on android test: 4. native server connections all up

2016-03-10T20:40:32.918Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-10T20:40:33.381Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-10T20:40:33.661Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-10T20:40:33.848Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-10T20:40:34.139Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-10T20:40:34.442Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-10T20:40:34.663Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-10T20:40:34.897Z - debug: Socket disconnected: transport close 5 (Apple-Iphone5s-1)

2016-03-10T20:40:34.938Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-10T20:40:35.018Z - info: Running on ios test: 13. closeAll with promise

2016-03-10T20:40:35.418Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-10T20:40:35.429Z - info: Running on ios test: 14. multiplex can send data

2016-03-10T20:40:35.851Z - info: Running on ios test: 15. enqueue and run in order

2016-03-10T20:40:36.521Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-10T20:40:36.559Z - info: Running on ios test: 16. enqueueAtTop and run backwards

2016-03-10T20:40:36.830Z - info: Running on ios test: 17. mix enqueue and enqueueAtTop

2016-03-10T20:40:36.939Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-10T20:40:37.387Z - info: Running on ios test: 18. queues handled independently

2016-03-10T20:40:37.411Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-10T20:40:37.750Z - info: Running on ios test: 19. basic

2016-03-10T20:40:37.822Z - info: Running on android test: 13. closeAll with promise

2016-03-10T20:40:38.184Z - info: Running on ios test: 20. another

2016-03-10T20:40:38.382Z - info: Running on android test: 14. multiplex can send data

2016-03-10T20:40:38.608Z - info: Running on ios test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-10T20:40:38.664Z - info: Running on android test: 15. enqueue and run in order

2016-03-10T20:40:38.927Z - info: Running on ios test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-10T20:40:39.250Z - info: Running on ios test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-10T20:40:39.490Z - info: Running on android test: 16. enqueueAtTop and run backwards

2016-03-10T20:40:39.613Z - info: Running on ios test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-10T20:40:39.967Z - info: Running on ios test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-10T20:40:40.038Z - info: Running on android test: 17. mix enqueue and enqueueAtTop

2016-03-10T20:40:40.424Z - info: Running on ios test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-10T20:40:40.671Z - info: Running on android test: 18. queues handled independently

2016-03-10T20:40:40.978Z - info: Running on ios test: 27. #start should fail if called twice in a row

2016-03-10T20:40:41.239Z - info: Running on android test: 19. basic

2016-03-10T20:40:41.500Z - info: Running on ios test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-10T20:40:41.791Z - info: Running on android test: 20. another

2016-03-10T20:40:42.239Z - info: Running on ios test: 29. does not send duplicate availability changes

2016-03-10T20:40:42.456Z - info: Running on android test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-10T20:40:42.699Z - info: Running on ios test: 30. can get the network status

2016-03-10T20:40:42.979Z - info: Running on android test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-10T20:40:43.130Z - info: Running on ios test: 31. wifi peer is marked unavailable if announcements stop

2016-03-10T20:40:43.734Z - info: Running on android test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-10T20:40:44.221Z - info: Running on android test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-10T20:40:44.667Z - info: Running on android test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-10T20:40:45.117Z - info: Running on android test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-10T20:40:45.609Z - info: Running on android test: 27. #start should fail if called twice in a row

2016-03-10T20:40:46.118Z - info: Running on android test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-10T20:40:46.777Z - info: Running on android test: 29. does not send duplicate availability changes

2016-03-10T20:40:47.216Z - info: Running on android test: 30. can get the network status

2016-03-10T20:40:47.778Z - info: Running on android test: 31. wifi peer is marked unavailable if announcements stop

2016-03-10T20:40:49.301Z - info: Running on android test: 32. can get the network status before starting

2016-03-10T20:40:49.847Z - info: Running on android test: 33. #generatePreambleAndBeacons bad args

2016-03-10T20:40:50.379Z - info: Running on android test: 34. #generatePreambleAndBeacons empty keys to notify

2016-03-10T20:40:50.985Z - info: Running on android test: 35. #generatePreambleAndBeacons multiple keys to notify

2016-03-10T20:40:51.550Z - info: Running on android test: 36. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-03-10T20:40:51.961Z - info: Running on android test: 37. #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-03-10T20:40:52.394Z - info: Running on android test: 38. #parseBeacons expiration out of range lower

2016-03-10T20:40:52.808Z - info: Running on android test: 39. #parseBeacons expiration out of range lower

2016-03-10T20:40:53.296Z - info: Running on android test: 40. #parseBeacons no beacons returns null

2016-03-10T20:40:53.811Z - info: Running on android test: 41. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-03-10T20:40:54.271Z - info: Running on android test: 42. #parseBeacons addressBookCallback fails decrypt

2016-03-10T20:40:54.767Z - info: Running on android test: 43. #parseBeacons addressBookCallback returns no matches

2016-03-10T20:40:55.306Z - info: Running on android test: 44. #parseBeacons addressBookCallback returns spurious match

2016-03-10T20:40:55.975Z - info: Running on android test: 45. #parseBeacons addressBookCallback returns public key

2016-03-10T20:40:56.609Z - info: Running on android test: 46. #parseBeacons with beacons both for and not for the user

2016-03-10T20:40:57.333Z - info: Running on android test: 47. Start and stop ThaliNotificationServer

2016-03-10T20:40:58.002Z - info: Running on android test: 48. Pass an empty array to ThaliNotificationServer.start

2016-03-10T20:40:58.788Z - info: Running on android test: 49. Pass a string to ThaliNotificationServer.start

2016-03-10T20:40:59.324Z - info: Running on android test: 50. Pass an empty parameter to ThaliNotificationServer.start

2016-03-10T20:40:59.893Z - info: Running on android test: 51. Make an HTTP request to /NotificationBeacons

2016-03-10T20:41:00.763Z - info: Running on android test: 52. Make an HTTP request to /NotificationBeacons (no keys)

2016-03-10T20:41:01.649Z - info: Running on android test: 53. Make an HTTP request to /NotificationBeacons before calling start

2016-03-10T20:41:02.746Z - info: Running on android test: 54. #testThaliPeerAction - test getters

2016-03-10T20:41:03.608Z - info: Running on android test: 55. #testThaliPeerAction - start and kill

2016-03-10T20:41:04.051Z - info: Running on android test: 56. #testThaliPeerAction - double start

2016-03-10T20:41:04.993Z - info: Running on android test: 57. #testThaliPeerAction - start after kill

2016-03-10T20:41:05.512Z - info: Running on android test: 58. #testThaliPeerAction - make sure ids are unique

2016-03-10T20:41:05.891Z - info: Running on android test: 59. #ThaliPeerPoolInterface - bad enqueues

2016-03-10T20:41:06.351Z - info: Running on android test: 60. #ThaliPeerPoolInterface - do not allow same object type

2016-03-10T20:41:06.682Z - info: Running on android test: 61. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

2016-03-10T20:41:07.130Z - info: Running on android test: 62. compareBufferArrays

2016-03-10T20:41:07.565Z - info: Running on android test: 63. Call start twice and get error

2016-03-10T20:41:07.906Z - info: Running on android test: 64. Start and make sure it runs

2016-03-10T20:41:08.162Z - info: Running on android test: 65. Make sure getTimeWhenRun is right after start

2016-03-10T20:41:08.521Z - info: Running on android test: 66. Make sure getTimeWhenRun is -1 after function is called

2016-03-10T20:41:08.874Z - info: Running on android test: 67. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

2016-03-10T20:41:09.303Z - info: Running on android test: 68. Test TransientState

2016-03-10T20:41:09.714Z - info: Running on android test: 69. No peers and empty database

2016-03-10T20:41:10.631Z - info: Running on android test: 70. One peer and empty DB

2016-03-10T20:41:11.287Z - info: Running on android test: 71. One peer with _Local set behind current seq

2016-03-10T20:41:12.168Z - info: Running on android test: 72. One peer with _Local set equal to current seq

2016-03-10T20:41:13.074Z - info: Running on android test: 73. One peer with _Local set ahead of current seq (and no this should not happen)

2016-03-10T20:41:13.785Z - info: Running on android test: 74. Three peers, one not in DB, one behind and one ahead

2016-03-10T20:41:14.578Z - info: Running on android test: 75. More than maximum peers, make sure we only send maximum allowed

2016-03-10T20:41:15.978Z - info: Running on android test: 76. two peers with empty DB, update the doc

2016-03-10T20:41:16.911Z - info: Running on android test: 77. add doc and make sure tokens refresh when they expire

2016-03-10T20:41:18.254Z - info: Running on android test: 78. start and stop and start and stop

2016-03-10T20:41:19.474Z - info: Running on android test: 79. two identical starts in a row

2016-03-10T20:41:20.240Z - info: Running on android test: 80. two different starts in a row

2016-03-10T20:41:20.996Z - info: Running on android test: 81. two stops and a start and two stops

2016-03-10T20:41:21.739Z - info: Running on android test: 82. we properly enqueue requests so no then needed

2016-03-10T20:41:22.485Z - info: Running on android test: 83. test calculateSeqPointKeyId

2016-03-10T20:41:23.197Z - info: Running on android test: 84. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-03-10T20:41:23.930Z - info: Running on android test: 85. #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-03-10T20:41:24.453Z - info: Running on android test: 86. messages with invalid location or USN should be ignored

2016-03-10T20:41:25.094Z - info: Running on android test: 87. verify that Thali-specific messages are filtered correctly

2016-03-10T20:41:25.566Z - info: Running on android test: 88. #startListeningForAdvertisements should fail if start not called

2016-03-10T20:41:26.392Z - info: Running on android test: 89. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-10T20:41:26.994Z - info: Running on android test: 90. #start should fail if called twice in a row

2016-03-10T20:41:27.784Z - info: Running on android test: 91. should not be started after stop is called

2016-03-10T20:41:28.762Z - info: Running on android test: 92. #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-03-10T20:41:29.297Z - info: Running on android test: 93. #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-03-10T20:41:29.756Z - info: Running on android test: 94. #startUpdateAdvertisingAndListening should start hosting given router object

2016-03-10T20:41:30.267Z - info: Running on android test: 95. #stop can be called multiple times in a row

2016-03-10T20:41:30.879Z - info: Running on android test: 96. #startListeningForAdvertisements can be called multiple times in a row

2016-03-10T20:41:31.408Z - info: Running on android test: 97. #stopListeningForAdvertisements can be called multiple times in a row

2016-03-10T20:41:31.870Z - info: Running on android test: 98. #stopAdvertisingAndListening can be called multiple times in a row

2016-03-10T20:41:32.818Z - info: Running on android test: 99. functions are run from a queue in the right order

2016-03-10T20:41:33.647Z - info: Running on android test: 100. network changes are ignored while stopping

2016-03-10T20:42:59.550Z - debug: Socket disconnected: ping timeout 0 (LGE-LG-H815)

2016-03-10T20:54:45.678Z - debug: Socket disconnected: transport close 1 (Apple-IpadAir2-1)

2016-03-10T20:54:45.695Z - debug: Socket disconnected: transport close 2 (Apple-Iphone6-1)

2016-03-10T20:57:32.648Z - debug: Socket disconnected: transport close 6 (NOT YET SET)

2016-03-10T20:57:39.551Z - debug: Socket disconnected: transport close 4 (samsung-SM-N910C)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/62328822054c831_Get_native_tests_working_in_coordinator_yaronyg/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/62328822054c831_Get_native_tests_working_in_coordinator_yaronyg/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/62328822054c831_Get_native_tests_working_in_coordinator_yaronyg/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/62328822054c831_Get_native_tests_working_in_coordinator_yaronyg/iOS_Iphone6-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/62328822054c831_Get_native_tests_working_in_coordinator_yaronyg/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:0 
child process exited with code 0 on device f56ad48d 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62328822054c831_Get_native_tests_working_in_coordinator_yaronyg/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/62328822054c831_Get_native_tests_working_in_coordinator_yaronyg/thali02_LGE-LG-D722.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/62328822054c831_Get_native_tests_working_in_coordinator_yaronyg/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/62328822054c831_Get_native_tests_working_in_coordinator_yaronyg/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:0 
child process exited with code 0 on device LGH8153b36be34 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/62328822054c831_Get_native_tests_working_in_coordinator_yaronyg/thali05_LGE-LG-H815.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62328822054c831_Get_native_tests_working_in_coordinator_yaronyg/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/62328822054c831_Get_native_tests_working_in_coordinator_yaronyg/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:0 
child process exited with code 0 on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62328822054c831_Get_native_tests_working_in_coordinator_yaronyg/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:0 
child process exited with code 0 on device 4325e43f 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62328822054c831_Get_native_tests_working_in_coordinator_yaronyg/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 09a9416e0297d102 app:com.test.thalitest code:0 
child process exited with code 0 on device 09a9416e0297d102 
Android task is completed. [FAILED]
```
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/62328822054c831_Get_native_tests_working_in_coordinator_yaronyg/thali09_LGE-Nexus 5.md)





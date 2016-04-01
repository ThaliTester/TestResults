#### Test 64613803d18c8d9 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-04-01T05:19:37.998Z - info: Require 3 ios devices

2016-04-01T05:19:38.017Z - info: Require 3 android devices

2016-04-01T05:19:38.076Z - info: listening on *:3000

2016-04-01T05:19:39.252Z - debug: Device presented: samsung-SM-N910C (5e672ddd-3890-4765-9da5-1c6f961d5adb) - android 5.1.1

2016-04-01T05:19:39.407Z - debug: Device presented: Apple-Iphone5-1 (0aa21398-7b4c-4999-b9cc-207fff665ddf) - ios Version 9.1 (Build 13B143)

2016-04-01T05:19:39.987Z - debug: Device presented: Apple-Iphone5s-1 (fb907fa7-6bbb-4685-a83b-630e712f1cec) - ios Version 9.1 (Build 13B143)

2016-04-01T05:19:40.199Z - debug: Device presented: samsung-SM-N910C (5e672ddd-3890-4765-9da5-1c6f961d5adb) - android 5.1.1

2016-04-01T05:19:40.201Z - info: Updating existing device: samsung-SM-N910C (5e672ddd-3890-4765-9da5-1c6f961d5adb)

2016-04-01T05:19:40.391Z - debug: Device presented: Apple-Iphone5-1 (0aa21398-7b4c-4999-b9cc-207fff665ddf) - ios Version 9.1 (Build 13B143)

2016-04-01T05:19:40.392Z - info: Updating existing device: Apple-Iphone5-1 (0aa21398-7b4c-4999-b9cc-207fff665ddf)

2016-04-01T05:19:41.039Z - debug: Device presented: Apple-IpadAir2-1 (096b47f0-b3ca-42e2-86de-efb223a755a4) - ios Version 9.1 (Build 13B143)

2016-04-01T05:19:41.047Z - debug: Device presented: Apple-Iphone5s-1 (fb907fa7-6bbb-4685-a83b-630e712f1cec) - ios Version 9.1 (Build 13B143)

2016-04-01T05:19:41.048Z - info: Updating existing device: Apple-Iphone5s-1 (fb907fa7-6bbb-4685-a83b-630e712f1cec)

2016-04-01T05:19:41.408Z - debug: Device presented: Apple-Iphone6-1 (2116515a-89f8-4ac6-81c4-f1910b261345) - ios Version 9.1 (Build 13B143)

2016-04-01T05:19:41.409Z - info: All 4 ios devices are present

2016-04-01T05:19:41.417Z - info: Starting unit test run on 4 ios devices

2016-04-01T05:19:42.183Z - debug: Device presented: Apple-IpadAir2-1 (096b47f0-b3ca-42e2-86de-efb223a755a4) - ios Version 9.1 (Build 13B143)

2016-04-01T05:19:42.184Z - info: Updating existing device: Apple-IpadAir2-1 (096b47f0-b3ca-42e2-86de-efb223a755a4)

2016-04-01T05:19:42.439Z - debug: Device presented: Apple-Iphone6-1 (2116515a-89f8-4ac6-81c4-f1910b261345) - ios Version 9.1 (Build 13B143)

2016-04-01T05:19:42.440Z - info: Updating existing device: Apple-Iphone6-1 (2116515a-89f8-4ac6-81c4-f1910b261345)

2016-04-01T05:19:43.956Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-04-01T05:19:46.392Z - info: Running on ios test: 2. emits incomingConnectionState

2016-04-01T05:19:46.778Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-04-01T05:19:46.810Z - debug: Device presented: LGE-LG-H815 (299ce567-2c65-4c01-b512-2c8e8a843807) - android 5.1

2016-04-01T05:19:47.170Z - info: Running on ios test: 4. native server connections all up

2016-04-01T05:19:47.440Z - debug: Device presented: motorola-Nexus 6 (631f865d-be6a-4c1b-9be2-b0f1f510f809) - android 5.1.1

2016-04-01T05:19:47.620Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-04-01T05:19:48.022Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-04-01T05:19:48.405Z - debug: Device presented: motorola-Nexus 6 (631f865d-be6a-4c1b-9be2-b0f1f510f809) - android 5.1.1

2016-04-01T05:19:48.406Z - info: Updating existing device: motorola-Nexus 6 (631f865d-be6a-4c1b-9be2-b0f1f510f809)

2016-04-01T05:19:48.452Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-04-01T05:19:48.857Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-04-01T05:19:49.270Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-04-01T05:19:51.253Z - debug: Device presented: LGE-Nexus 5 (2e6dcbf9-cc8b-4374-96c3-82c60d778d9b) - android 5.1.1

2016-04-01T05:19:51.254Z - info: All 4 android devices are present

2016-04-01T05:19:51.256Z - info: Disqualifying device with unsupported hardware: LGE-Nexus 5

2016-04-01T05:19:51.259Z - info: Starting unit test run on 3 android devices

2016-04-01T05:19:51.808Z - info: Socket to device LGE-Nexus 5 disconnected: transport close

2016-04-01T05:19:52.037Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-04-01T05:19:52.347Z - info: Running on android test: 2. emits incomingConnectionState

2016-04-01T05:19:53.075Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-04-01T05:19:53.242Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-04-01T05:19:53.911Z - info: Running on android test: 4. native server connections all up

2016-04-01T05:19:54.492Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-04-01T05:19:56.385Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-04-01T05:19:59.104Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-04-01T05:20:00.266Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-04-01T05:20:04.345Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-04-01T05:20:04.693Z - info: Running on ios test: 13. closeAll with promise

2016-04-01T05:20:09.447Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-04-01T05:20:18.684Z - info: Running on ios test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-04-01T05:20:36.774Z - info: Running on ios test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-04-01T05:20:39.870Z - info: Running on ios test: 16. enqueue and run in order

2016-04-01T05:20:40.550Z - info: Running on ios test: 17. enqueueAtTop and run backwards

2016-04-01T05:20:40.871Z - info: Running on ios test: 18. mix enqueue and enqueueAtTop

2016-04-01T05:20:41.259Z - info: Running on ios test: 19. queues handled independently

2016-04-01T05:20:41.338Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-04-01T05:20:41.594Z - info: Running on ios test: 20. basic

2016-04-01T05:20:41.966Z - info: Running on ios test: 21. another

2016-04-01T05:20:42.299Z - info: Running on ios test: 22. can pass data in setup

2016-04-01T05:20:42.313Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-04-01T05:20:42.566Z - info: Running on ios test: 23. #startListeningForAdvertisements should fail if start not called

2016-04-01T05:20:42.707Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-04-01T05:20:42.874Z - info: Running on ios test: 24. #startUpdateAdvertisingAndListening should fail if start not called

2016-04-01T05:20:43.145Z - info: Running on android test: 12. closeAll can close even when connections open

2016-04-01T05:20:43.189Z - info: Running on ios test: 25. should be able to call #stopListeningForAdvertisements many times

2016-04-01T05:20:43.476Z - info: Running on android test: 13. closeAll with promise

2016-04-01T05:20:43.720Z - info: Running on ios test: 26. should be able to call #startListeningForAdvertisements many times

2016-04-01T05:20:43.830Z - info: Running on android test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-04-01T05:20:44.234Z - info: Running on android test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-04-01T05:20:44.393Z - info: Running on ios test: 27. should be able to call #startUpdateAdvertisingAndListening many times

2016-04-01T05:20:44.644Z - info: Running on android test: 16. enqueue and run in order

2016-04-01T05:20:45.500Z - info: Running on android test: 17. enqueueAtTop and run backwards

2016-04-01T05:20:45.774Z - info: Running on ios test: 28. should be able to call #stopAdvertisingAndListening many times

2016-04-01T05:20:47.596Z - info: Running on android test: 18. mix enqueue and enqueueAtTop

2016-04-01T05:20:48.526Z - info: Running on android test: 19. queues handled independently

2016-04-01T05:20:49.096Z - info: Running on android test: 20. basic

2016-04-01T05:20:49.595Z - info: Running on android test: 21. another

2016-04-01T05:20:49.980Z - info: Running on android test: 22. can pass data in setup

2016-04-01T05:20:50.331Z - info: Running on android test: 23. #startListeningForAdvertisements should fail if start not called

2016-04-01T05:20:50.601Z - info: Running on android test: 24. #startUpdateAdvertisingAndListening should fail if start not called

2016-04-01T05:20:50.892Z - info: Running on android test: 25. should be able to call #stopListeningForAdvertisements many times

2016-04-01T05:20:51.353Z - info: Running on android test: 26. should be able to call #startListeningForAdvertisements many times

2016-04-01T05:20:52.136Z - info: Running on android test: 27. should be able to call #startUpdateAdvertisingAndListening many times

2016-04-01T05:20:53.678Z - info: Running on android test: 28. should be able to call #stopAdvertisingAndListening many times

2016-04-01T05:20:58.421Z - info: Running on android test: 29. #start should fail if called twice in a row

2016-04-01T05:20:58.863Z - info: Running on android test: 30. does not emit duplicate discoveryAdvertisingStateUpdate

2016-04-01T05:21:01.212Z - info: Running on android test: 31. does not send duplicate availability changes

2016-04-01T05:21:01.624Z - info: Running on android test: 32. can get the network status

2016-04-01T05:21:01.928Z - info: Running on android test: 33. wifi peer is marked unavailable if announcements stop

2016-04-01T05:21:04.312Z - info: Running on android test: 34. Can call start/stopListeningForAdvertisements

2016-04-01T05:21:04.807Z - info: Running on ios test: 29. #start should fail if called twice in a row

2016-04-01T05:21:04.846Z - info: Running on android test: 35. Calling startListeningForAdvertisements twice is NOT an error

2016-04-01T05:21:05.344Z - info: Running on ios test: 30. does not emit duplicate discoveryAdvertisingStateUpdate

2016-04-01T05:21:05.502Z - info: Running on android test: 36. Calling stopListeningForAdvertisements without calling start is NOT an error

2016-04-01T05:21:05.881Z - info: Running on android test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-04-01T05:21:06.865Z - info: Running on ios test: 31. does not send duplicate availability changes

2016-04-01T05:21:08.368Z - info: Running on android test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-04-01T05:21:13.203Z - info: Running on android test: 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error

2016-04-01T05:21:32.403Z - info: Running on android test: 40. cannot call connect when start listening for advertisements is not active

2016-04-01T05:21:33.771Z - info: Running on android test: 41. peerAvailabilityChange is called

2016-04-01T05:21:34.729Z - info: Running on ios test: 32. can get the network status

2016-04-01T05:21:35.976Z - info: Running on ios test: 33. wifi peer is marked unavailable if announcements stop

2016-04-01T05:21:36.095Z - info: Running on android test: 42. Can connect to a remote peer

2016-04-01T05:21:40.787Z - info: Running on ios test: 34. Can call start/stopListeningForAdvertisements

2016-04-01T05:21:41.442Z - info: Running on ios test: 35. Calling startListeningForAdvertisements twice is NOT an error

2016-04-01T05:21:43.490Z - info: Running on ios test: 36. Calling stopListeningForAdvertisements without calling start is NOT an error

2016-04-01T05:21:44.152Z - info: Running on ios test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-04-01T05:21:44.665Z - info: Running on ios test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-04-01T05:21:45.155Z - info: Running on ios test: 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error

2016-04-01T05:21:51.622Z - info: Running on android test: 43. Get error when trying to double connect to a peer

2016-04-01T05:22:07.438Z - warn: Failed on android test: 43. Get error when trying to double connect to a peer

2016-04-01T05:22:07.440Z - info: Running on android test: 44. Connect port dies if not connected to in in time

2016-04-01T05:22:12.801Z - info: Running on ios test: 40. cannot call connect when start listening for advertisements is not active

2016-04-01T05:22:20.015Z - warn: Failed on ios test: 40. cannot call connect when start listening for advertisements is not active

2016-04-01T05:22:20.016Z - info: Running on ios test: 41. peerAvailabilityChange is called

2016-04-01T05:22:24.130Z - info: Running on ios test: 42. Can connect to a remote peer

2016-04-01T05:24:05.425Z - warn: Failed on ios test: 42. Can connect to a remote peer

2016-04-01T05:24:05.426Z - info: Running on ios test: 43. Get error when trying to double connect to a peer

2016-04-01T05:39:24.347Z - info: Socket to device Apple-Iphone5s-1 disconnected: transport close

2016-04-01T05:39:24.357Z - info: Socket to device Apple-IpadAir2-1 disconnected: transport close

2016-04-01T05:39:24.363Z - info: Socket to device Apple-Iphone6-1 disconnected: transport close

2016-04-01T05:39:29.123Z - info: Socket to device Apple-Iphone5-1 disconnected: transport close

2016-04-01T05:41:15.187Z - info: Socket to device samsung-SM-N910C disconnected: transport close

2016-04-01T05:41:17.062Z - info: Socket to device motorola-Nexus 6 disconnected: transport close

2016-04-01T05:43:04.353Z - info: Socket to device LGE-LG-H815 disconnected: transport close


 
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
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/64613803d18c8d9_Test_framework_improvements_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/64613803d18c8d9_Test_framework_improvements_vjrantal/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/64613803d18c8d9_Test_framework_improvements_vjrantal/iOS_Iphone5-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/64613803d18c8d9_Test_framework_improvements_vjrantal/iOS_Iphone6-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/64613803d18c8d9_Test_framework_improvements_vjrantal/iOS_server.md)


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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/64613803d18c8d9_Test_framework_improvements_vjrantal/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/64613803d18c8d9_Test_framework_improvements_vjrantal/thali07_LGE-LG-H815.md)

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
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/64613803d18c8d9_Test_framework_improvements_vjrantal/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/64613803d18c8d9_Test_framework_improvements_vjrantal/thali08_motorola-Nexus 6.md)





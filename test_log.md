#### Test 64531254841497d Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-03-29T21:42:45.993Z - info: listening on *:3000

2016-03-29T21:42:48.417Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:0

2016-03-29T21:42:48.477Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:1

2016-03-29T21:42:50.610Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:2

2016-03-29T21:42:50.942Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:4

2016-03-29T21:42:50.944Z - info: Required number of ios devices presented (3)

2016-03-29T21:42:50.948Z - info: Starting unit test run for platform: ios

2016-03-29T21:42:51.001Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:3

2016-03-29T21:42:51.694Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-29T21:42:52.325Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-29T21:42:52.758Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-29T21:42:53.282Z - info: Running on ios test: 4. native server connections all up

2016-03-29T21:42:53.884Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-29T21:42:54.432Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-29T21:42:54.906Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-29T21:42:55.403Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-29T21:42:55.892Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-29T21:43:02.263Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:5

2016-03-29T21:43:02.265Z - info: Required number of android devices presented (3)

2016-03-29T21:43:02.268Z - info: Starting unit test run for platform: android

2016-03-29T21:43:03.262Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-29T21:43:03.960Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-29T21:43:04.352Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-29T21:43:04.424Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-29T21:43:05.113Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-29T21:43:05.122Z - info: Running on android test: 4. native server connections all up

2016-03-29T21:43:05.945Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-29T21:43:06.161Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-29T21:43:06.387Z - info: Running on ios test: 13. closeAll with promise

2016-03-29T21:43:06.843Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-29T21:43:06.847Z - info: Running on ios test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-03-29T21:43:07.222Z - info: Running on ios test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-03-29T21:43:07.304Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-29T21:43:07.685Z - info: Running on ios test: 16. enqueue and run in order

2016-03-29T21:43:07.868Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-29T21:43:08.241Z - info: Running on ios test: 17. enqueueAtTop and run backwards

2016-03-29T21:43:08.442Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-29T21:43:08.577Z - info: Running on ios test: 18. mix enqueue and enqueueAtTop

2016-03-29T21:43:09.123Z - info: Running on ios test: 19. queues handled independently

2016-03-29T21:43:09.389Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-29T21:43:09.516Z - info: Running on ios test: 20. basic

2016-03-29T21:43:09.802Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-29T21:43:09.851Z - info: Running on ios test: 21. another

2016-03-29T21:43:10.376Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-29T21:43:10.387Z - info: Running on ios test: 22. can pass data in setup

2016-03-29T21:43:10.765Z - info: Running on ios test: 23. #startListeningForAdvertisements should fail if start not called

2016-03-29T21:43:10.842Z - info: Running on android test: 13. closeAll with promise

2016-03-29T21:43:11.275Z - info: Running on ios test: 24. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-29T21:43:11.413Z - info: Running on android test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-03-29T21:43:11.692Z - info: Running on ios test: 25. should be able to call #stopListeningForAdvertisements many times

2016-03-29T21:43:11.840Z - info: Running on android test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-03-29T21:43:12.179Z - info: Running on ios test: 26. should be able to call #startListeningForAdvertisements many times

2016-03-29T21:43:12.287Z - info: Running on android test: 16. enqueue and run in order

2016-03-29T21:43:12.769Z - info: Running on ios test: 27. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-29T21:43:12.941Z - info: Running on android test: 17. enqueueAtTop and run backwards

2016-03-29T21:43:13.344Z - info: Running on android test: 18. mix enqueue and enqueueAtTop

2016-03-29T21:43:18.173Z - info: Running on android test: 19. queues handled independently

2016-03-29T21:43:25.991Z - info: Running on ios test: 28. should be able to call #stopAdvertisingAndListening many times

2016-03-29T21:43:36.778Z - info: Running on android test: 20. basic

2016-03-29T21:43:37.466Z - info: Running on android test: 21. another

2016-03-29T21:43:38.325Z - info: Running on android test: 22. can pass data in setup

2016-03-29T21:43:39.631Z - info: Running on android test: 23. #startListeningForAdvertisements should fail if start not called

2016-03-29T21:43:40.350Z - info: Running on android test: 24. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-29T21:43:40.730Z - info: Running on android test: 25. should be able to call #stopListeningForAdvertisements many times

2016-03-29T21:43:41.796Z - info: Running on android test: 26. should be able to call #startListeningForAdvertisements many times

2016-03-29T21:43:42.673Z - info: Running on ios test: 29. #start should fail if called twice in a row

2016-03-29T21:43:42.677Z - info: Running on android test: 27. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-29T21:43:43.074Z - info: Running on ios test: 30. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-29T21:43:43.780Z - info: Running on ios test: 31. does not send duplicate availability changes

2016-03-29T21:43:44.738Z - info: Running on ios test: 32. can get the network status

2016-03-29T21:43:45.766Z - info: Running on android test: 28. should be able to call #stopAdvertisingAndListening many times

2016-03-29T21:43:53.712Z - info: Running on android test: 29. #start should fail if called twice in a row

2016-03-29T21:44:04.583Z - info: Running on android test: 30. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-29T21:44:07.427Z - info: Running on android test: 31. does not send duplicate availability changes

2016-03-29T21:44:07.972Z - info: Running on android test: 32. can get the network status

2016-03-29T21:44:08.397Z - info: Running on android test: 33. wifi peer is marked unavailable if announcements stop

2016-03-29T21:44:10.936Z - info: Running on android test: 34. Can call start/stopListeningForAdvertisements

2016-03-29T21:44:11.506Z - info: Running on android test: 35. Calling startListeningForAdvertisements twice is NOT an error

2016-03-29T21:44:12.106Z - info: Running on android test: 36. Calling stopListeningForAdvertisements without calling start is NOT an error

2016-03-29T21:44:12.496Z - info: Running on android test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-03-29T21:44:13.155Z - info: Running on android test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-29T21:44:13.973Z - info: Running on android test: 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error

2016-03-29T21:44:14.357Z - info: Running on android test: 40. cannot call connect when start listening for advertisements is not active

2016-03-29T21:44:14.766Z - info: Running on android test: 41. peerAvailabilityChange is called

2016-03-29T21:44:16.426Z - info: Running on android test: 42. Can connect to a remote peer

2016-03-29T21:44:20.681Z - info: Running on ios test: 33. wifi peer is marked unavailable if announcements stop

2016-03-29T21:44:25.129Z - info: Running on ios test: 34. Can call start/stopListeningForAdvertisements

2016-03-29T21:44:25.697Z - info: Running on android test: 43. Can shift large amounts of data

2016-03-29T21:44:26.214Z - info: Running on ios test: 35. Calling startListeningForAdvertisements twice is NOT an error

2016-03-29T21:44:46.250Z - info: Running on ios test: 36. Calling stopListeningForAdvertisements without calling start is NOT an error

2016-03-29T21:44:47.157Z - info: Running on android test: 44. #startUpdateAdvertisingAndListening - killing remote peers connection kills the local connection

2016-03-29T21:44:57.202Z - info: Running on ios test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-03-29T21:45:03.732Z - info: Running on ios test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-29T21:45:32.795Z - info: Running on android test: 45. #startUpdateAdvertisingAndListening - killing the local connection kills the connection to the remote peer

2016-03-29T21:45:33.247Z - info: Running on ios test: 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error

2016-03-29T21:45:59.704Z - info: Running on ios test: 40. cannot call connect when start listening for advertisements is not active

2016-03-29T21:46:00.309Z - warn: Failed on ios test: 40. cannot call connect when start listening for advertisements is not active

2016-03-29T21:46:00.311Z - info: Running on ios test: 41. peerAvailabilityChange is called

2016-03-29T21:46:04.114Z - info: Running on ios test: 42. Can connect to a remote peer

2016-03-29T21:46:30.545Z - warn: Failed on android test: 45. #startUpdateAdvertisingAndListening - killing the local connection kills the connection to the remote peer

2016-03-29T21:46:30.547Z - info: Running on android test: 46. We do not emit peerAvailabilityChanged events until one of the start methods is called

2016-03-29T21:46:40.783Z - info: Running on android test: 47. Test updating advertising and parallel data transfer

2016-03-29T21:47:14.831Z - warn: Failed on ios test: 42. Can connect to a remote peer

2016-03-29T21:47:14.832Z - info: Running on ios test: 43. Can shift large amounts of data

2016-03-29T21:48:24.660Z - warn: Failed on ios test: 43. Can shift large amounts of data

2016-03-29T21:48:24.661Z - info: Running on ios test: 44. #startUpdateAdvertisingAndListening - killing remote peers connection kills the local connection

2016-03-29T21:49:34.461Z - warn: Failed on ios test: 44. #startUpdateAdvertisingAndListening - killing remote peers connection kills the local connection

2016-03-29T21:49:34.463Z - info: Running on ios test: 45. #startUpdateAdvertisingAndListening - killing the local connection kills the connection to the remote peer

2016-03-29T21:51:18.609Z - warn: Failed on ios test: 45. #startUpdateAdvertisingAndListening - killing the local connection kills the connection to the remote peer

2016-03-29T21:51:18.610Z - info: Running on ios test: 46. We do not emit peerAvailabilityChanged events until one of the start methods is called

2016-03-29T21:51:26.613Z - info: Running on ios test: 47. Test updating advertising and parallel data transfer

2016-03-29T22:02:23.855Z - debug: Socket disconnected: transport close 4 (Apple-Iphone6-1)

2016-03-29T22:02:23.887Z - debug: Socket disconnected: transport close 2 (Apple-Iphone5-1)

2016-03-29T22:02:23.944Z - debug: Socket disconnected: transport close 1 (Apple-Iphone5s-1)

2016-03-29T22:04:01.370Z - debug: Socket disconnected: transport close 0 (LGE-LG-H815)

2016-03-29T22:06:12.587Z - debug: Socket disconnected: transport close 3 (samsung-SM-N910C)

2016-03-29T22:06:14.568Z - debug: Socket disconnected: transport close 5 (motorola-Nexus 6)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m
2016-03-29T21:43:22.402Z - error: Too many emit retries to device: Apple-Iphone5s-1

2016-03-29T21:43:32.370Z - error: Too many emit retries to device: samsung-SM-N910C

2016-03-29T21:43:53.765Z - error: Too many emit retries to device: Apple-Iphone6-1

2016-03-29T21:44:02.744Z - error: Too many emit retries to device: motorola-Nexus 6

2016-03-29T21:44:38.566Z - error: Too many emit retries to device: Apple-Iphone5s-1

2016-03-29T21:44:38.569Z - error: Too many emit retries to device: Apple-Iphone5-1

2016-03-29T21:45:16.780Z - error: Too many emit retries to device: Apple-Iphone5-1

2016-03-29T21:45:42.275Z - error: Too many emit retries to device: Apple-Iphone5s-1

2016-03-29T21:45:42.277Z - error: Too many emit retries to device: Apple-Iphone5-1

2016-03-29T21:45:45.304Z - error: Too many emit retries to device: samsung-SM-N910C

2016-03-29T21:45:54.249Z - error: Too many emit retries to device: Apple-Iphone5s-1


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
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/64531254841497d_More_native_level_testing_yaronyg/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/64531254841497d_More_native_level_testing_yaronyg/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/64531254841497d_More_native_level_testing_yaronyg/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/64531254841497d_More_native_level_testing_yaronyg/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/64531254841497d_More_native_level_testing_yaronyg/iOS_server.md)


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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/64531254841497d_More_native_level_testing_yaronyg/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/64531254841497d_More_native_level_testing_yaronyg/thali07_LGE-LG-H815.md)

####Node name: thali08
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:null 
child process exited with code null on device ZX1G429CRK 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/64531254841497d_More_native_level_testing_yaronyg/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/64531254841497d_More_native_level_testing_yaronyg/thali08_motorola-Nexus 6.md)





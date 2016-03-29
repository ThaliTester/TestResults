#### Test 64423763d6e7601 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-03-29T07:51:27.740Z - info: listening on *:3000

2016-03-29T07:51:28.716Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:0

2016-03-29T07:51:30.854Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:1

2016-03-29T07:51:31.118Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:2

2016-03-29T07:51:31.120Z - info: Required number of ios devices presented (3)

2016-03-29T07:51:31.124Z - info: Starting unit test run for platform: ios

2016-03-29T07:51:31.441Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:3

2016-03-29T07:51:31.854Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-29T07:51:36.691Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:4

2016-03-29T07:51:55.071Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-29T07:51:55.579Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-29T07:51:55.963Z - info: Running on ios test: 4. native server connections all up

2016-03-29T07:51:56.415Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-29T07:51:56.921Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-29T07:51:57.539Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-29T07:51:57.980Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-29T07:51:58.558Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-29T07:52:00.599Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-29T07:52:02.102Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-29T07:52:02.741Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-29T07:52:02.756Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:5

2016-03-29T07:52:02.758Z - info: Required number of android devices presented (3)

2016-03-29T07:52:02.759Z - info: Starting unit test run for platform: android

2016-03-29T07:52:03.766Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-29T07:52:04.053Z - info: Running on ios test: 13. closeAll with promise

2016-03-29T07:52:04.145Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-29T07:52:04.582Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-29T07:52:04.745Z - info: Running on ios test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-03-29T07:52:05.132Z - info: Running on android test: 4. native server connections all up

2016-03-29T07:52:05.245Z - info: Running on ios test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-03-29T07:52:05.710Z - info: Running on ios test: 16. multiplex can send data

2016-03-29T07:52:05.765Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-29T07:52:06.186Z - info: Running on ios test: 17. enqueue and run in order

2016-03-29T07:52:06.363Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-29T07:52:06.978Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-29T07:52:07.008Z - info: Running on ios test: 18. enqueueAtTop and run backwards

2016-03-29T07:52:07.401Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-29T07:52:07.510Z - info: Running on ios test: 19. mix enqueue and enqueueAtTop

2016-03-29T07:52:07.957Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-29T07:52:08.718Z - info: Running on ios test: 20. queues handled independently

2016-03-29T07:52:08.895Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-29T07:52:09.191Z - info: Running on ios test: 21. basic

2016-03-29T07:52:09.421Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-29T07:52:09.988Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-29T07:52:10.006Z - info: Running on ios test: 22. another

2016-03-29T07:52:10.423Z - info: Running on android test: 13. closeAll with promise

2016-03-29T07:52:10.429Z - info: Running on ios test: 23. can pass data in setup

2016-03-29T07:52:10.876Z - info: Running on android test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-03-29T07:52:11.112Z - info: Running on ios test: 24. #startListeningForAdvertisements should fail if start not called

2016-03-29T07:52:11.345Z - info: Running on android test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-03-29T07:52:11.584Z - info: Running on ios test: 25. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-29T07:52:11.942Z - info: Running on android test: 16. multiplex can send data

2016-03-29T07:52:12.177Z - info: Running on ios test: 26. should be able to call #stopListeningForAdvertisements many times

2016-03-29T07:52:12.487Z - info: Running on android test: 17. enqueue and run in order

2016-03-29T07:52:13.197Z - info: Running on ios test: 27. should be able to call #startListeningForAdvertisements many times

2016-03-29T07:52:13.203Z - info: Running on android test: 18. enqueueAtTop and run backwards

2016-03-29T07:52:14.315Z - info: Running on android test: 19. mix enqueue and enqueueAtTop

2016-03-29T07:52:15.540Z - info: Running on android test: 20. queues handled independently

2016-03-29T07:52:17.000Z - info: Running on android test: 21. basic

2016-03-29T07:52:18.090Z - info: Running on android test: 22. another

2016-03-29T07:52:18.531Z - info: Running on android test: 23. can pass data in setup

2016-03-29T07:52:20.406Z - info: Running on android test: 24. #startListeningForAdvertisements should fail if start not called

2016-03-29T07:52:42.800Z - info: Running on android test: 25. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-29T07:52:43.342Z - info: Running on ios test: 28. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-29T07:52:47.182Z - info: Running on android test: 26. should be able to call #stopListeningForAdvertisements many times

2016-03-29T07:52:49.799Z - info: Running on android test: 27. should be able to call #startListeningForAdvertisements many times

2016-03-29T07:52:50.474Z - info: Running on android test: 28. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-29T07:52:52.341Z - info: Running on android test: 29. should be able to call #stopAdvertisingAndListening many times

2016-03-29T07:52:54.084Z - info: Running on android test: 30. #start should fail if called twice in a row

2016-03-29T07:52:54.594Z - info: Running on android test: 31. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-29T07:52:55.502Z - info: Running on ios test: 29. should be able to call #stopAdvertisingAndListening many times

2016-03-29T07:52:57.457Z - info: Running on android test: 32. does not send duplicate availability changes

2016-03-29T07:52:59.300Z - info: Running on android test: 33. can get the network status

2016-03-29T07:52:59.683Z - info: Running on android test: 34. wifi peer is marked unavailable if announcements stop

2016-03-29T07:53:02.132Z - info: Running on android test: 35. Can call start/stopListeningForAdvertisements

2016-03-29T07:53:02.367Z - info: Running on ios test: 30. #start should fail if called twice in a row

2016-03-29T07:53:02.681Z - info: Running on android test: 36. Calling startListeningForAdvertisements twice is NOT an error

2016-03-29T07:53:03.877Z - info: Running on android test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-03-29T07:53:04.954Z - info: Running on ios test: 31. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-29T07:53:04.958Z - info: Running on android test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-29T07:53:05.596Z - info: Running on ios test: 32. does not send duplicate availability changes

2016-03-29T07:53:06.171Z - info: Running on ios test: 33. can get the network status

2016-03-29T07:53:13.441Z - info: Running on android test: 39. peerAvailabilityChange is called

2016-03-29T07:53:42.085Z - info: Running on android test: 40. Can connect to a remote peer

2016-03-29T07:53:42.225Z - info: Running on ios test: 34. wifi peer is marked unavailable if announcements stop

2016-03-29T07:53:45.576Z - info: Running on ios test: 35. Can call start/stopListeningForAdvertisements

2016-03-29T07:53:46.661Z - info: Running on ios test: 36. Calling startListeningForAdvertisements twice is NOT an error

2016-03-29T07:53:54.400Z - info: Running on android test: 41. Can shift large amounts of data

2016-03-29T07:54:44.253Z - info: Running on android test: 42. #startListeningForAdvertisements should fail if start not called

2016-03-29T07:54:47.295Z - info: Running on android test: 43. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-29T07:54:48.726Z - info: Running on android test: 44. should be able to call #stopListeningForAdvertisements many times

2016-03-29T07:54:49.156Z - info: Running on android test: 45. should be able to call #startListeningForAdvertisements many times

2016-03-29T07:54:49.996Z - info: Running on android test: 46. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-29T07:54:51.660Z - info: Running on android test: 47. should be able to call #stopAdvertisingAndListening many times

2016-03-29T07:54:52.571Z - info: Running on android test: 48. can get the network status before starting

2016-03-29T07:54:52.990Z - info: Running on android test: 49. error returned with bad router

2016-03-29T07:54:53.449Z - info: Running on android test: 50. all services are stopped when we call stop

2016-03-29T07:54:54.749Z - info: Running on android test: 51. make sure terminateConnection is properly hooked up

2016-03-29T07:54:55.641Z - info: Running on android test: 52. make sure terminateListener is properly hooked up

2016-03-29T07:54:56.141Z - info: Running on android test: 53. make sure we actually call kill connections properly

2016-03-29T07:54:56.618Z - info: Running on android test: 54. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received

2016-03-29T07:54:57.212Z - info: Running on android test: 55. We repeat failedConnection event when we get it from thaliTcpServersManager

2016-03-29T07:54:57.711Z - info: Running on android test: 56. we successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-29T07:54:58.983Z - warn: Failed on android test: 56. we successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-29T07:54:58.984Z - info: Running on android test: 57. can do HTTP requests between peers

2016-03-29T07:55:20.957Z - warn: Failed on android test: 57. can do HTTP requests between peers

2016-03-29T07:55:20.959Z - info: Running on android test: 58. Client to server request locally

2016-03-29T07:55:21.588Z - info: Running on android test: 59. Client to server request coordinated

2016-03-29T07:55:24.109Z - debug: Socket disconnected: transport close 3 (LGE-LG-H815)

2016-03-29T07:55:32.146Z - debug: Socket disconnected: ping timeout 1 (Apple-Iphone6-1)

2016-03-29T07:56:50.054Z - debug: Socket disconnected: transport close 6 (NOT YET SET)

2016-03-29T07:57:27.590Z - debug: Socket disconnected: transport close 7 (NOT YET SET)

2016-03-29T07:58:05.950Z - debug: Socket disconnected: transport close 9 (NOT YET SET)

2016-03-29T07:59:56.086Z - debug: Socket disconnected: ping timeout 8 (NOT YET SET)

2016-03-29T08:01:06.339Z - debug: Socket disconnected: transport close 11 (NOT YET SET)

2016-03-29T08:05:31.706Z - debug: Socket disconnected: transport close 10 (NOT YET SET)

2016-03-29T08:06:24.702Z - debug: Socket disconnected: transport close 13 (NOT YET SET)

2016-03-29T08:06:28.722Z - debug: Socket disconnected: transport close 12 (NOT YET SET)

2016-03-29T08:06:45.505Z - debug: Socket disconnected: transport close 14 (NOT YET SET)

2016-03-29T08:07:08.353Z - debug: Socket disconnected: transport close 15 (NOT YET SET)

2016-03-29T08:07:36.067Z - debug: Socket disconnected: transport close 17 (NOT YET SET)

2016-03-29T08:11:25.797Z - debug: Socket disconnected: transport close 2 (Apple-Iphone5s-1)

2016-03-29T08:11:25.813Z - debug: Socket disconnected: transport close 0 (Apple-Iphone5-1)

2016-03-29T08:11:45.869Z - debug: Socket disconnected: transport close 16 (NOT YET SET)

2016-03-29T08:15:13.484Z - debug: Socket disconnected: transport close 4 (samsung-SM-N910C)

2016-03-29T08:15:15.262Z - debug: Socket disconnected: transport close 5 (motorola-Nexus 6)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m
2016-03-29T07:51:43.073Z - error: Too many emit retries to device: Apple-Iphone5s-1

2016-03-29T07:52:22.588Z - error: Too many emit retries to device: Apple-Iphone5s-1

2016-03-29T07:52:39.812Z - error: Too many emit retries to device: Apple-Iphone5-1

2016-03-29T07:52:40.593Z - error: Too many emit retries to device: motorola-Nexus 6

2016-03-29T07:53:16.724Z - error: Too many emit retries to device: Apple-Iphone5-1

2016-03-29T07:53:16.729Z - error: Too many emit retries to device: Apple-Iphone6-1

2016-03-29T07:53:16.738Z - error: Too many emit retries to device: Apple-Iphone5s-1

2016-03-29T07:53:28.013Z - error: Too many emit retries to device: motorola-Nexus 6

2016-03-29T07:53:55.794Z - error: Too many emit retries to device: Apple-Iphone6-1

2016-03-29T07:54:03.435Z - error: Too many emit retries to device: motorola-Nexus 6

2016-03-29T07:54:15.024Z - error: Too many emit retries to device: Apple-Iphone6-1

2016-03-29T07:54:15.028Z - error: Too many emit retries to device: Apple-Iphone5s-1


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
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/64423763d6e7601_Avoid_emitting_peer_unavailable_from_self_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/64423763d6e7601_Avoid_emitting_peer_unavailable_from_self_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/64423763d6e7601_Avoid_emitting_peer_unavailable_from_self_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/64423763d6e7601_Avoid_emitting_peer_unavailable_from_self_vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/64423763d6e7601_Avoid_emitting_peer_unavailable_from_self_vjrantal/iOS_server.md)


###Android Logs
####Node name: thali07
Console output:
```
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
Device test finished on 0c6a0f3c0bdb4e77 
STOP log received from  LGH8153b36be34 Test has  FAILED
Device test finished on LGH8153b36be34 
Android task is completed. [FAILED]
```
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/64423763d6e7601_Avoid_emitting_peer_unavailable_from_self_vjrantal/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/64423763d6e7601_Avoid_emitting_peer_unavailable_from_self_vjrantal/thali07_LGE-LG-H815.md)

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
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/64423763d6e7601_Avoid_emitting_peer_unavailable_from_self_vjrantal/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/64423763d6e7601_Avoid_emitting_peer_unavailable_from_self_vjrantal/thali08_motorola-Nexus 6.md)





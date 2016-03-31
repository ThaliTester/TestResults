#### Test 648099369ce4518 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-03-31T16:06:02.737Z - info: listening on *:3000

2016-03-31T16:06:04.052Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:0

2016-03-31T16:06:05.398Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:1

2016-03-31T16:06:05.892Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:2

2016-03-31T16:06:05.894Z - info: Required number of ios devices presented (3)

2016-03-31T16:06:05.897Z - info: Starting unit test run for platform: ios

2016-03-31T16:06:06.689Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:3

2016-03-31T16:06:06.690Z - info: Discarding surplus device: Apple-IpadAir2-1

2016-03-31T16:06:07.823Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:4

2016-03-31T16:06:08.489Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-31T16:06:09.093Z - debug: Socket disconnected: transport close 3 (Apple-IpadAir2-1)

2016-03-31T16:06:11.644Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-31T16:06:12.043Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-31T16:06:12.453Z - info: Running on ios test: 4. native server connections all up

2016-03-31T16:06:12.915Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-31T16:06:13.233Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:5

2016-03-31T16:06:13.437Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-31T16:06:13.840Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-31T16:06:14.327Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-31T16:06:14.749Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-31T16:06:18.126Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-31T16:06:18.635Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-31T16:06:19.058Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-31T16:06:19.398Z - info: Running on ios test: 13. closeAll with promise

2016-03-31T16:06:19.703Z - info: Running on ios test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-03-31T16:06:20.183Z - info: Running on ios test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-03-31T16:06:20.573Z - info: Running on ios test: 16. multiplex can send data

2016-03-31T16:06:20.982Z - info: Running on ios test: 17. enqueue and run in order

2016-03-31T16:06:21.581Z - info: Running on ios test: 18. enqueueAtTop and run backwards

2016-03-31T16:06:22.128Z - info: Running on ios test: 19. mix enqueue and enqueueAtTop

2016-03-31T16:06:22.733Z - info: Running on ios test: 20. queues handled independently

2016-03-31T16:06:23.096Z - info: Running on ios test: 21. basic

2016-03-31T16:06:23.585Z - info: Running on ios test: 22. another

2016-03-31T16:06:24.054Z - info: Running on ios test: 23. can pass data in setup

2016-03-31T16:06:24.391Z - info: Running on ios test: 24. #startListeningForAdvertisements should fail if start not called

2016-03-31T16:06:24.786Z - info: Running on ios test: 25. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-31T16:06:25.150Z - info: Running on ios test: 26. should be able to call #stopListeningForAdvertisements many times

2016-03-31T16:06:25.559Z - info: Running on ios test: 27. should be able to call #startListeningForAdvertisements many times

2016-03-31T16:06:26.006Z - info: Running on ios test: 28. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-31T16:06:26.642Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:6

2016-03-31T16:06:26.643Z - info: Required number of android devices presented (3)

2016-03-31T16:06:26.646Z - info: Starting unit test run for platform: android

2016-03-31T16:06:26.811Z - info: Running on ios test: 29. should be able to call #stopAdvertisingAndListening many times

2016-03-31T16:06:27.473Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-31T16:06:30.394Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-31T16:06:32.598Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-31T16:06:33.499Z - info: Running on android test: 4. native server connections all up

2016-03-31T16:06:34.747Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-31T16:06:37.212Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-31T16:06:38.174Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-31T16:06:38.689Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-31T16:06:39.181Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-31T16:06:41.291Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-31T16:06:42.265Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-31T16:06:43.214Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-31T16:06:46.060Z - info: Running on android test: 13. closeAll with promise

2016-03-31T16:06:51.610Z - info: Running on android test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-03-31T16:06:55.049Z - info: Running on android test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-03-31T16:06:57.982Z - info: Running on android test: 16. multiplex can send data

2016-03-31T16:07:00.262Z - info: Running on ios test: 30. #start should fail if called twice in a row

2016-03-31T16:07:01.496Z - info: Running on android test: 17. enqueue and run in order

2016-03-31T16:07:03.813Z - info: Running on android test: 18. enqueueAtTop and run backwards

2016-03-31T16:07:04.227Z - info: Running on android test: 19. mix enqueue and enqueueAtTop

2016-03-31T16:07:04.767Z - info: Running on android test: 20. queues handled independently

2016-03-31T16:07:05.198Z - info: Running on android test: 21. basic

2016-03-31T16:07:05.211Z - info: Running on ios test: 31. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-31T16:07:05.623Z - info: Running on android test: 22. another

2016-03-31T16:07:05.941Z - info: Running on ios test: 32. does not send duplicate availability changes

2016-03-31T16:07:06.070Z - info: Running on android test: 23. can pass data in setup

2016-03-31T16:07:06.466Z - info: Running on android test: 24. #startListeningForAdvertisements should fail if start not called

2016-03-31T16:07:06.576Z - info: Running on ios test: 33. can get the network status

2016-03-31T16:07:06.847Z - info: Running on android test: 25. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-31T16:07:07.513Z - info: Running on android test: 26. should be able to call #stopListeningForAdvertisements many times

2016-03-31T16:07:09.786Z - info: Running on android test: 27. should be able to call #startListeningForAdvertisements many times

2016-03-31T16:07:11.319Z - info: Running on android test: 28. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-31T16:07:12.642Z - info: Running on android test: 29. should be able to call #stopAdvertisingAndListening many times

2016-03-31T16:07:14.681Z - info: Running on android test: 30. #start should fail if called twice in a row

2016-03-31T16:07:16.664Z - info: Running on android test: 31. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-31T16:07:18.895Z - info: Running on android test: 32. does not send duplicate availability changes

2016-03-31T16:07:24.513Z - info: Running on ios test: 34. wifi peer is marked unavailable if announcements stop

2016-03-31T16:07:24.819Z - info: Running on android test: 33. can get the network status

2016-03-31T16:07:29.223Z - info: Running on android test: 34. wifi peer is marked unavailable if announcements stop

2016-03-31T16:07:32.118Z - info: Running on android test: 35. Can call start/stopListeningForAdvertisements

2016-03-31T16:07:33.898Z - info: Running on android test: 36. Calling startListeningForAdvertisements twice is NOT an error

2016-03-31T16:07:36.661Z - info: Running on android test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-03-31T16:07:38.230Z - info: Running on android test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-31T16:07:40.499Z - info: Running on android test: 39. peerAvailabilityChange is called

2016-03-31T16:07:41.282Z - info: Running on ios test: 35. Can call start/stopListeningForAdvertisements

2016-03-31T16:07:43.491Z - info: Running on android test: 40. Can connect to a remote peer

2016-03-31T16:07:54.223Z - info: Running on ios test: 36. Calling startListeningForAdvertisements twice is NOT an error

2016-03-31T16:07:59.884Z - info: Running on android test: 41. Can shift large amounts of data

2016-03-31T16:08:01.007Z - info: Running on ios test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-03-31T16:08:01.803Z - info: Running on ios test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-31T16:08:02.624Z - info: Running on ios test: 39. peerAvailabilityChange is called

2016-03-31T16:08:08.313Z - info: Running on ios test: 40. Can connect to a remote peer

2016-03-31T16:08:08.575Z - info: Running on android test: 42. #startListeningForAdvertisements should fail if start not called

2016-03-31T16:08:09.137Z - info: Running on android test: 43. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-31T16:08:09.704Z - info: Running on android test: 44. should be able to call #stopListeningForAdvertisements many times

2016-03-31T16:08:10.291Z - info: Running on android test: 45. should be able to call #startListeningForAdvertisements many times

2016-03-31T16:08:11.141Z - info: Running on android test: 46. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-31T16:08:13.582Z - info: Running on android test: 47. should be able to call #stopAdvertisingAndListening many times

2016-03-31T16:08:14.697Z - info: Running on android test: 48. can get the network status before starting

2016-03-31T16:08:16.437Z - info: Running on android test: 49. error returned with bad router

2016-03-31T16:08:17.524Z - info: Running on android test: 50. all services are stopped when we call stop

2016-03-31T16:08:18.789Z - info: Running on android test: 51. make sure terminateConnection is properly hooked up

2016-03-31T16:08:19.182Z - info: Running on android test: 52. make sure terminateListener is properly hooked up

2016-03-31T16:08:19.596Z - info: Running on android test: 53. make sure we actually call kill connections properly

2016-03-31T16:08:19.997Z - info: Running on android test: 54. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received

2016-03-31T16:08:20.524Z - info: Running on android test: 55. We repeat failedConnection event when we get it from thaliTcpServersManager

2016-03-31T16:08:20.984Z - info: Running on android test: 56. we successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-31T16:08:22.160Z - debug: Socket disconnected: transport close 6 (motorola-Nexus 6)

2016-03-31T16:08:22.169Z - debug: Socket disconnected: transport close 4 (LGE-LG-H815)

2016-03-31T16:08:22.643Z - debug: Socket disconnected: transport close 5 (samsung-SM-N910C)

2016-03-31T16:09:50.765Z - debug: Socket disconnected: ping timeout 2 (Apple-Iphone5-1)

2016-03-31T16:25:42.471Z - debug: Socket disconnected: transport close 0 (Apple-Iphone6-1)

2016-03-31T16:25:42.479Z - debug: Socket disconnected: transport close 1 (Apple-Iphone5s-1)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m
2016-03-31T16:06:39.802Z - error: Too many emit retries to device: Apple-Iphone5-1

2016-03-31T16:06:50.474Z - error: Too many emit retries to device: Apple-Iphone5-1

2016-03-31T16:07:22.398Z - error: Too many emit retries to device: Apple-Iphone5-1

2016-03-31T16:07:35.863Z - error: Too many emit retries to device: Apple-Iphone5-1

2016-03-31T16:07:50.754Z - error: Too many emit retries to device: Apple-Iphone5s-1

2016-03-31T16:08:31.408Z - error: Too many emit retries to device: LGE-LG-H815

2016-03-31T16:08:31.410Z - error: Too many emit retries to device: motorola-Nexus 6


```


Logs for system : 
```

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m



ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
true

```
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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/648099369ce4518_416_Notification_final_juhanak/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/648099369ce4518_416_Notification_final_juhanak/thali07_LGE-LG-H815.md)

####Node name: thali08
Console output:
```
STOP log received from  ZX1G429CRK Test has  FAILED
STOP log received from  41006f95c8139173 Test has  FAILED
Device test finished on 41006f95c8139173 
Device test finished on ZX1G429CRK 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/648099369ce4518_416_Notification_final_juhanak/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/648099369ce4518_416_Notification_final_juhanak/thali08_motorola-Nexus 6.md)


###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/648099369ce4518_416_Notification_final_juhanak/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/648099369ce4518_416_Notification_final_juhanak/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/648099369ce4518_416_Notification_final_juhanak/iOS_Iphone5-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/648099369ce4518_416_Notification_final_juhanak/iOS_Iphone6-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/648099369ce4518_416_Notification_final_juhanak/iOS_server.md)





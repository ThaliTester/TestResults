#### Test 64746945aaa3c62 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-03-31T08:12:41.043Z - info: listening on *:3000

2016-03-31T08:12:41.581Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:0

2016-03-31T08:12:42.912Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:1

2016-03-31T08:12:44.819Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:3

2016-03-31T08:12:44.847Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:2

2016-03-31T08:12:44.848Z - info: Required number of ios devices presented (3)

2016-03-31T08:12:44.853Z - info: Starting unit test run for platform: ios

2016-03-31T08:12:45.652Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-31T08:12:46.172Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-31T08:12:46.605Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-31T08:12:46.998Z - info: Running on ios test: 4. native server connections all up

2016-03-31T08:12:47.523Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-31T08:12:47.957Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-31T08:12:48.398Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-31T08:12:48.631Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:4

2016-03-31T08:12:48.888Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-31T08:12:49.400Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-31T08:12:58.356Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-31T08:12:59.066Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-31T08:12:59.545Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-31T08:12:59.931Z - info: Running on ios test: 13. closeAll with promise

2016-03-31T08:13:00.130Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:5

2016-03-31T08:13:00.131Z - info: Required number of android devices presented (3)

2016-03-31T08:13:00.135Z - info: Starting unit test run for platform: android

2016-03-31T08:13:00.371Z - info: Running on ios test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-03-31T08:13:00.776Z - info: Running on ios test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-03-31T08:13:00.977Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-31T08:13:01.140Z - info: Running on ios test: 16. multiplex can send data

2016-03-31T08:13:01.499Z - info: Running on ios test: 17. enqueue and run in order

2016-03-31T08:13:01.770Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-31T08:13:02.019Z - info: Running on ios test: 18. enqueueAtTop and run backwards

2016-03-31T08:13:02.135Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-31T08:13:02.428Z - info: Running on ios test: 19. mix enqueue and enqueueAtTop

2016-03-31T08:13:02.721Z - info: Running on android test: 4. native server connections all up

2016-03-31T08:13:02.899Z - info: Running on ios test: 20. queues handled independently

2016-03-31T08:13:03.199Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-31T08:13:03.374Z - info: Running on ios test: 21. basic

2016-03-31T08:13:03.684Z - info: Running on ios test: 22. another

2016-03-31T08:13:03.734Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-31T08:13:03.990Z - info: Running on ios test: 23. can pass data in setup

2016-03-31T08:13:04.178Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-31T08:13:04.352Z - info: Running on ios test: 24. #startListeningForAdvertisements should fail if start not called

2016-03-31T08:13:04.647Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-31T08:13:04.754Z - info: Running on ios test: 25. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-31T08:13:05.068Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-31T08:13:05.096Z - info: Running on ios test: 26. should be able to call #stopListeningForAdvertisements many times

2016-03-31T08:13:05.579Z - info: Running on ios test: 27. should be able to call #startListeningForAdvertisements many times

2016-03-31T08:13:05.999Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-31T08:13:06.400Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-31T08:13:06.805Z - info: Running on ios test: 28. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-31T08:13:06.834Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-31T08:13:07.173Z - info: Running on android test: 13. closeAll with promise

2016-03-31T08:13:08.212Z - info: Running on ios test: 29. should be able to call #stopAdvertisingAndListening many times

2016-03-31T08:13:08.404Z - info: Running on android test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-03-31T08:13:08.778Z - info: Running on android test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-03-31T08:13:08.890Z - info: Running on ios test: 30. #start should fail if called twice in a row

2016-03-31T08:13:09.264Z - info: Running on android test: 16. multiplex can send data

2016-03-31T08:13:09.471Z - info: Running on ios test: 31. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-31T08:13:09.800Z - info: Running on android test: 17. enqueue and run in order

2016-03-31T08:13:10.303Z - info: Running on ios test: 32. does not send duplicate availability changes

2016-03-31T08:13:10.604Z - info: Running on android test: 18. enqueueAtTop and run backwards

2016-03-31T08:13:11.148Z - info: Running on android test: 19. mix enqueue and enqueueAtTop

2016-03-31T08:13:11.872Z - info: Running on ios test: 33. can get the network status

2016-03-31T08:13:12.528Z - info: Running on android test: 20. queues handled independently

2016-03-31T08:13:14.297Z - info: Running on android test: 21. basic

2016-03-31T08:13:14.785Z - info: Running on android test: 22. another

2016-03-31T08:13:16.254Z - info: Running on android test: 23. can pass data in setup

2016-03-31T08:13:17.212Z - info: Running on android test: 24. #startListeningForAdvertisements should fail if start not called

2016-03-31T08:13:21.845Z - info: Running on android test: 25. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-31T08:13:25.327Z - info: Running on android test: 26. should be able to call #stopListeningForAdvertisements many times

2016-03-31T08:13:28.798Z - info: Running on android test: 27. should be able to call #startListeningForAdvertisements many times

2016-03-31T08:13:30.678Z - info: Running on android test: 28. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-31T08:13:32.664Z - info: Running on ios test: 34. wifi peer is marked unavailable if announcements stop

2016-03-31T08:13:33.817Z - info: Running on android test: 29. should be able to call #stopAdvertisingAndListening many times

2016-03-31T08:13:34.311Z - info: Running on android test: 30. #start should fail if called twice in a row

2016-03-31T08:13:34.892Z - info: Running on android test: 31. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-31T08:13:35.937Z - info: Running on android test: 32. does not send duplicate availability changes

2016-03-31T08:13:37.385Z - info: Running on android test: 33. can get the network status

2016-03-31T08:13:37.708Z - info: Running on ios test: 35. Can call start/stopListeningForAdvertisements

2016-03-31T08:13:38.031Z - info: Running on android test: 34. wifi peer is marked unavailable if announcements stop

2016-03-31T08:13:40.531Z - info: Running on android test: 35. Can call start/stopListeningForAdvertisements

2016-03-31T08:13:41.748Z - info: Running on android test: 36. Calling startListeningForAdvertisements twice is NOT an error

2016-03-31T08:13:42.997Z - info: Running on android test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-03-31T08:13:45.037Z - info: Running on android test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-31T08:13:46.559Z - info: Running on android test: 39. peerAvailabilityChange is called

2016-03-31T08:13:48.365Z - info: Running on android test: 40. Can connect to a remote peer

2016-03-31T08:13:59.162Z - info: Running on ios test: 36. Calling startListeningForAdvertisements twice is NOT an error

2016-03-31T08:14:01.162Z - info: Running on android test: 41. Can shift large amounts of data

2016-03-31T08:14:09.523Z - info: Running on android test: 42. #startListeningForAdvertisements should fail if start not called

2016-03-31T08:14:10.873Z - info: Running on android test: 43. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-31T08:14:12.516Z - info: Running on android test: 44. should be able to call #stopListeningForAdvertisements many times

2016-03-31T08:14:13.673Z - info: Running on android test: 45. should be able to call #startListeningForAdvertisements many times

2016-03-31T08:14:14.471Z - info: Running on android test: 46. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-31T08:14:15.403Z - info: Running on android test: 47. should be able to call #stopAdvertisingAndListening many times

2016-03-31T08:14:15.862Z - info: Running on android test: 48. can get the network status before starting

2016-03-31T08:14:16.294Z - info: Running on android test: 49. error returned with bad router

2016-03-31T08:14:16.721Z - info: Running on android test: 50. all services are stopped when we call stop

2016-03-31T08:14:17.780Z - info: Running on android test: 51. make sure terminateConnection is properly hooked up

2016-03-31T08:14:18.353Z - info: Running on android test: 52. make sure terminateListener is properly hooked up

2016-03-31T08:14:19.967Z - info: Running on android test: 53. make sure we actually call kill connections properly

2016-03-31T08:14:21.062Z - info: Running on ios test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-03-31T08:14:21.188Z - info: Running on android test: 54. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received

2016-03-31T08:14:22.811Z - info: Running on android test: 55. We repeat failedConnection event when we get it from thaliTcpServersManager

2016-03-31T08:14:24.254Z - info: Running on android test: 56. we successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-31T08:14:25.513Z - debug: Socket disconnected: transport close 5 (motorola-Nexus 6)

2016-03-31T08:14:25.535Z - debug: Socket disconnected: transport close 3 (LGE-LG-H815)

2016-03-31T08:14:25.843Z - debug: Socket disconnected: transport close 4 (samsung-SM-N910C)

2016-03-31T08:16:12.409Z - info: Running on ios test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-31T08:16:16.000Z - info: Running on ios test: 39. peerAvailabilityChange is called

2016-03-31T08:16:18.351Z - info: Running on ios test: 40. Can connect to a remote peer

2016-03-31T08:18:31.344Z - warn: Failed on ios test: 40. Can connect to a remote peer

2016-03-31T08:18:31.346Z - info: Running on ios test: 41. Can shift large amounts of data

2016-03-31T08:20:41.604Z - warn: Failed on ios test: 41. Can shift large amounts of data

2016-03-31T08:20:41.607Z - info: Running on ios test: 42. #startListeningForAdvertisements should fail if start not called

2016-03-31T08:20:44.365Z - info: Running on ios test: 43. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-31T08:20:45.610Z - info: Running on ios test: 44. should be able to call #stopListeningForAdvertisements many times

2016-03-31T08:20:48.132Z - info: Running on ios test: 45. should be able to call #startListeningForAdvertisements many times

2016-03-31T08:22:24.208Z - debug: Socket disconnected: ping timeout 2 (Apple-Iphone5s-1)

2016-03-31T08:32:19.177Z - debug: Socket disconnected: transport close 0 (Apple-Iphone6-1)

2016-03-31T08:32:19.246Z - debug: Socket disconnected: transport close 1 (Apple-Iphone5-1)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m
2016-03-31T08:13:24.044Z - error: Too many emit retries to device: Apple-Iphone6-1

2016-03-31T08:13:24.053Z - error: Too many emit retries to device: Apple-Iphone5-1

2016-03-31T08:13:53.685Z - error: Too many emit retries to device: Apple-Iphone5-1

2016-03-31T08:14:08.188Z - error: Too many emit retries to device: Apple-Iphone6-1

2016-03-31T08:14:17.525Z - error: Too many emit retries to device: Apple-Iphone6-1

2016-03-31T08:14:36.079Z - error: Too many emit retries to device: Apple-Iphone5s-1

2016-03-31T08:15:00.945Z - error: Too many emit retries to device: Apple-Iphone5s-1

2016-03-31T08:20:57.827Z - error: Too many emit retries to device: Apple-Iphone5s-1


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
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/64746945aaa3c62_Fixes_coordinated_test_colors_juhanak/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/64746945aaa3c62_Fixes_coordinated_test_colors_juhanak/thali07_LGE-LG-H815.md)

####Node name: thali08
Console output:
```
STOP log received from  ZX1G429CRK Test has  FAILED
STOP log received from  41006f95c8139173 Test has  FAILED
Device test finished on ZX1G429CRK 
Device test finished on 41006f95c8139173 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/64746945aaa3c62_Fixes_coordinated_test_colors_juhanak/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/64746945aaa3c62_Fixes_coordinated_test_colors_juhanak/thali08_motorola-Nexus 6.md)


###iOS Logs
[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/64746945aaa3c62_Fixes_coordinated_test_colors_juhanak/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/64746945aaa3c62_Fixes_coordinated_test_colors_juhanak/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/64746945aaa3c62_Fixes_coordinated_test_colors_juhanak/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/64746945aaa3c62_Fixes_coordinated_test_colors_juhanak/iOS_Iphone6-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/64746945aaa3c62_Fixes_coordinated_test_colors_juhanak/iOS_server.md)





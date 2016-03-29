#### Test 63998117d1f6a2b Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-03-29T11:29:36.707Z - info: listening on *:3000

2016-03-29T11:29:38.259Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:0

2016-03-29T11:29:40.508Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:1

2016-03-29T11:29:41.024Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:2

2016-03-29T11:29:41.638Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:3

2016-03-29T11:29:41.639Z - info: Required number of ios devices presented (3)

2016-03-29T11:29:41.643Z - info: Starting unit test run for platform: ios

2016-03-29T11:29:44.015Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-29T11:29:44.946Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-29T11:29:45.507Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:4

2016-03-29T11:29:45.630Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-29T11:29:46.162Z - info: Running on ios test: 4. native server connections all up

2016-03-29T11:29:46.961Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-29T11:29:47.428Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-29T11:29:47.863Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-29T11:29:48.360Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-29T11:29:48.767Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-29T11:29:54.022Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:5

2016-03-29T11:29:54.023Z - info: Required number of android devices presented (3)

2016-03-29T11:29:54.025Z - info: Starting unit test run for platform: android

2016-03-29T11:29:55.100Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-29T11:29:55.609Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-29T11:29:56.112Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-29T11:29:56.601Z - info: Running on android test: 4. native server connections all up

2016-03-29T11:29:57.122Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-29T11:29:57.481Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-29T11:29:57.647Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-29T11:29:58.168Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-29T11:29:58.625Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-29T11:29:59.228Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-29T11:29:59.246Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-29T11:29:59.725Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-29T11:30:00.434Z - info: Running on ios test: 13. closeAll with promise

2016-03-29T11:30:00.735Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-29T11:30:01.067Z - info: Running on ios test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-03-29T11:30:01.495Z - info: Running on ios test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-03-29T11:30:02.026Z - info: Running on ios test: 16. multiplex can send data

2016-03-29T11:30:02.488Z - info: Running on ios test: 17. enqueue and run in order

2016-03-29T11:30:03.123Z - info: Running on ios test: 18. enqueueAtTop and run backwards

2016-03-29T11:30:03.623Z - info: Running on ios test: 19. mix enqueue and enqueueAtTop

2016-03-29T11:30:04.217Z - info: Running on ios test: 20. queues handled independently

2016-03-29T11:30:04.418Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-29T11:30:04.640Z - info: Running on ios test: 21. basic

2016-03-29T11:30:05.061Z - info: Running on ios test: 22. another

2016-03-29T11:30:05.066Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-29T11:30:05.513Z - info: Running on ios test: 23. can pass data in setup

2016-03-29T11:30:05.536Z - info: Running on android test: 13. closeAll with promise

2016-03-29T11:30:05.900Z - info: Running on ios test: 24. #startListeningForAdvertisements should fail if start not called

2016-03-29T11:30:06.108Z - info: Running on android test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-03-29T11:30:06.439Z - info: Running on ios test: 25. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-29T11:30:06.632Z - info: Running on android test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-03-29T11:30:06.833Z - info: Running on ios test: 26. should be able to call #stopListeningForAdvertisements many times

2016-03-29T11:30:07.139Z - info: Running on android test: 16. multiplex can send data

2016-03-29T11:30:07.328Z - info: Running on ios test: 27. should be able to call #startListeningForAdvertisements many times

2016-03-29T11:30:07.713Z - info: Running on android test: 17. enqueue and run in order

2016-03-29T11:30:08.018Z - info: Running on ios test: 28. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-29T11:30:08.518Z - info: Running on android test: 18. enqueueAtTop and run backwards

2016-03-29T11:30:08.910Z - info: Running on android test: 19. mix enqueue and enqueueAtTop

2016-03-29T11:30:09.784Z - info: Running on android test: 20. queues handled independently

2016-03-29T11:30:10.068Z - info: Running on ios test: 29. should be able to call #stopAdvertisingAndListening many times

2016-03-29T11:30:10.326Z - info: Running on android test: 21. basic

2016-03-29T11:30:10.788Z - info: Running on ios test: 30. #start should fail if called twice in a row

2016-03-29T11:30:10.851Z - info: Running on android test: 22. another

2016-03-29T11:30:11.234Z - info: Running on android test: 23. can pass data in setup

2016-03-29T11:30:11.541Z - info: Running on ios test: 31. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-29T11:30:11.620Z - info: Running on android test: 24. #startListeningForAdvertisements should fail if start not called

2016-03-29T11:30:12.016Z - info: Running on android test: 25. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-29T11:30:12.170Z - info: Running on ios test: 32. does not send duplicate availability changes

2016-03-29T11:30:12.373Z - info: Running on android test: 26. should be able to call #stopListeningForAdvertisements many times

2016-03-29T11:30:12.674Z - info: Running on ios test: 33. can get the network status

2016-03-29T11:30:12.856Z - info: Running on android test: 27. should be able to call #startListeningForAdvertisements many times

2016-03-29T11:30:15.703Z - info: Running on android test: 28. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-29T11:30:19.236Z - info: Running on android test: 29. should be able to call #stopAdvertisingAndListening many times

2016-03-29T11:30:25.667Z - info: Running on ios test: 34. wifi peer is marked unavailable if announcements stop

2016-03-29T11:30:32.217Z - info: Running on ios test: 35. Can call start/stopListeningForAdvertisements

2016-03-29T11:30:32.375Z - info: Running on android test: 30. #start should fail if called twice in a row

2016-03-29T11:30:33.511Z - info: Running on android test: 31. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-29T11:30:34.759Z - debug: Socket disconnected: transport close 0 (Apple-Iphone5s-1)

2016-03-29T11:30:36.993Z - info: Running on android test: 32. does not send duplicate availability changes

2016-03-29T11:30:39.972Z - info: Running on android test: 33. can get the network status

2016-03-29T11:30:46.143Z - info: Running on android test: 34. wifi peer is marked unavailable if announcements stop

2016-03-29T11:30:49.309Z - info: Running on android test: 35. Can call start/stopListeningForAdvertisements

2016-03-29T11:30:49.974Z - info: Running on android test: 36. Calling startListeningForAdvertisements twice is NOT an error

2016-03-29T11:30:51.293Z - info: Running on android test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-03-29T11:30:52.033Z - info: Running on android test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-29T11:30:53.976Z - info: Running on android test: 39. peerAvailabilityChange is called

2016-03-29T11:30:56.283Z - info: Running on android test: 40. Can connect to a remote peer

2016-03-29T11:31:08.491Z - info: Running on android test: 41. Can shift large amounts of data

2016-03-29T11:31:16.261Z - info: Running on android test: 42. #startListeningForAdvertisements should fail if start not called

2016-03-29T11:31:18.032Z - info: Running on android test: 43. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-29T11:31:20.729Z - info: Running on android test: 44. should be able to call #stopListeningForAdvertisements many times

2016-03-29T11:31:21.259Z - info: Running on android test: 45. should be able to call #startListeningForAdvertisements many times

2016-03-29T11:31:22.038Z - info: Running on android test: 46. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-29T11:31:23.073Z - info: Running on android test: 47. should be able to call #stopAdvertisingAndListening many times

2016-03-29T11:31:23.718Z - info: Running on android test: 48. can get the network status before starting

2016-03-29T11:31:24.262Z - info: Running on android test: 49. error returned with bad router

2016-03-29T11:31:24.725Z - info: Running on android test: 50. all services are stopped when we call stop

2016-03-29T11:31:26.061Z - info: Running on android test: 51. make sure terminateConnection is properly hooked up

2016-03-29T11:31:26.531Z - info: Running on android test: 52. make sure terminateListener is properly hooked up

2016-03-29T11:31:27.025Z - info: Running on android test: 53. make sure we actually call kill connections properly

2016-03-29T11:31:27.478Z - info: Running on android test: 54. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received

2016-03-29T11:31:27.988Z - info: Running on android test: 55. We repeat failedConnection event when we get it from thaliTcpServersManager

2016-03-29T11:31:28.540Z - info: Running on android test: 56. we successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-29T11:31:29.851Z - debug: Socket disconnected: transport close 2 (LGE-LG-H815)

2016-03-29T11:31:29.871Z - debug: Socket disconnected: transport close 5 (motorola-Nexus 6)

2016-03-29T11:31:30.041Z - debug: Socket disconnected: transport close 4 (samsung-SM-N910C)

2016-03-29T11:49:13.590Z - debug: Socket disconnected: transport close 1 (Apple-Iphone6-1)

2016-03-29T11:49:13.603Z - debug: Socket disconnected: transport close 3 (Apple-Iphone5-1)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m
2016-03-29T11:30:22.547Z - error: Too many emit retries to device: Apple-Iphone5s-1

2016-03-29T11:30:29.398Z - error: Too many emit retries to device: LGE-LG-H815

2016-03-29T11:31:38.385Z - error: Too many emit retries to device: motorola-Nexus 6


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
ios: child process exited with code 254 on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/63998117d1f6a2b_More_tests_vjrantal/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/63998117d1f6a2b_More_tests_vjrantal/thali07_LGE-LG-H815.md)

####Node name: thali08
Console output:
```
STOP log received from  ZX1G429CRK Test has  FAILED
STOP log received from  41006f95c8139173 Test has  FAILED
Device test finished on 41006f95c8139173 
Device test finished on ZX1G429CRK 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/63998117d1f6a2b_More_tests_vjrantal/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/63998117d1f6a2b_More_tests_vjrantal/thali08_motorola-Nexus 6.md)


###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/63998117d1f6a2b_More_tests_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/63998117d1f6a2b_More_tests_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/63998117d1f6a2b_More_tests_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/63998117d1f6a2b_More_tests_vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/63998117d1f6a2b_More_tests_vjrantal/iOS_server.md)





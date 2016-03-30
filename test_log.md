#### Test 646862831c69957 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-03-30T20:19:22.767Z - info: listening on *:3000

2016-03-30T20:19:25.870Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:0

2016-03-30T20:19:27.355Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:1

2016-03-30T20:19:27.514Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:2

2016-03-30T20:19:27.515Z - info: Required number of ios devices presented (3)

2016-03-30T20:19:27.520Z - info: Starting unit test run for platform: ios

2016-03-30T20:19:28.147Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:3

2016-03-30T20:19:28.353Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-30T20:19:29.051Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-30T20:19:29.512Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-30T20:19:30.009Z - info: Running on ios test: 4. native server connections all up

2016-03-30T20:19:30.684Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-30T20:19:31.314Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-30T20:19:31.524Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:4

2016-03-30T20:19:31.945Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-30T20:19:32.494Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-30T20:19:33.084Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-30T20:19:37.027Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-30T20:19:37.794Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-30T20:19:38.307Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-30T20:19:38.751Z - info: Running on ios test: 13. closeAll with promise

2016-03-30T20:19:39.165Z - info: Running on ios test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-03-30T20:19:39.802Z - info: Running on ios test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-03-30T20:19:40.206Z - info: Running on ios test: 16. multiplex can send data

2016-03-30T20:19:40.688Z - info: Running on ios test: 17. enqueue and run in order

2016-03-30T20:19:41.349Z - info: Running on ios test: 18. enqueueAtTop and run backwards

2016-03-30T20:19:41.729Z - info: Running on ios test: 19. mix enqueue and enqueueAtTop

2016-03-30T20:19:42.321Z - info: Running on ios test: 20. queues handled independently

2016-03-30T20:19:42.742Z - info: Running on ios test: 21. basic

2016-03-30T20:19:43.189Z - info: Running on ios test: 22. another

2016-03-30T20:19:43.686Z - info: Running on ios test: 23. can pass data in setup

2016-03-30T20:19:44.147Z - info: Running on ios test: 24. #startListeningForAdvertisements should fail if start not called

2016-03-30T20:19:44.542Z - info: Running on ios test: 25. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-30T20:19:45.027Z - info: Running on ios test: 26. should be able to call #stopListeningForAdvertisements many times

2016-03-30T20:19:45.570Z - info: Running on ios test: 27. should be able to call #startListeningForAdvertisements many times

2016-03-30T20:19:46.298Z - info: Running on ios test: 28. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-30T20:19:48.221Z - info: Running on ios test: 29. should be able to call #stopAdvertisingAndListening many times

2016-03-30T20:19:49.853Z - info: Running on ios test: 30. #start should fail if called twice in a row

2016-03-30T20:19:50.419Z - info: Running on ios test: 31. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-30T20:19:51.576Z - info: Running on ios test: 32. does not send duplicate availability changes

2016-03-30T20:19:52.072Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:5

2016-03-30T20:19:52.073Z - info: Required number of android devices presented (3)

2016-03-30T20:19:52.075Z - info: Starting unit test run for platform: android

2016-03-30T20:19:53.205Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-30T20:19:53.445Z - info: Running on ios test: 33. can get the network status

2016-03-30T20:19:53.794Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-30T20:19:55.745Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-30T20:19:56.887Z - info: Running on android test: 4. native server connections all up

2016-03-30T20:19:57.534Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-30T20:19:58.654Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-30T20:19:59.485Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-30T20:20:01.098Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-30T20:20:02.153Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-30T20:20:03.415Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-30T20:20:04.069Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-30T20:20:04.527Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-30T20:20:05.092Z - info: Running on android test: 13. closeAll with promise

2016-03-30T20:20:06.313Z - info: Running on android test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-03-30T20:20:06.879Z - info: Running on android test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-03-30T20:20:07.415Z - info: Running on android test: 16. multiplex can send data

2016-03-30T20:20:07.943Z - info: Running on android test: 17. enqueue and run in order

2016-03-30T20:20:09.126Z - info: Running on android test: 18. enqueueAtTop and run backwards

2016-03-30T20:20:09.631Z - info: Running on android test: 19. mix enqueue and enqueueAtTop

2016-03-30T20:20:10.155Z - info: Running on android test: 20. queues handled independently

2016-03-30T20:20:10.588Z - info: Running on android test: 21. basic

2016-03-30T20:20:11.004Z - info: Running on android test: 22. another

2016-03-30T20:20:11.513Z - info: Running on android test: 23. can pass data in setup

2016-03-30T20:20:11.758Z - info: Running on ios test: 34. wifi peer is marked unavailable if announcements stop

2016-03-30T20:20:11.855Z - info: Running on android test: 24. #startListeningForAdvertisements should fail if start not called

2016-03-30T20:20:12.362Z - info: Running on android test: 25. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-30T20:20:12.855Z - info: Running on android test: 26. should be able to call #stopListeningForAdvertisements many times

2016-03-30T20:20:13.489Z - info: Running on android test: 27. should be able to call #startListeningForAdvertisements many times

2016-03-30T20:20:14.293Z - info: Running on android test: 28. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-30T20:20:15.290Z - info: Running on ios test: 35. Can call start/stopListeningForAdvertisements

2016-03-30T20:20:15.299Z - info: Running on android test: 29. should be able to call #stopAdvertisingAndListening many times

2016-03-30T20:20:15.824Z - info: Running on android test: 30. #start should fail if called twice in a row

2016-03-30T20:20:16.360Z - info: Running on android test: 31. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-30T20:20:16.801Z - info: Running on ios test: 36. Calling startListeningForAdvertisements twice is NOT an error

2016-03-30T20:20:17.432Z - info: Running on ios test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-03-30T20:20:17.540Z - info: Running on android test: 32. does not send duplicate availability changes

2016-03-30T20:20:18.669Z - info: Running on ios test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-30T20:20:19.198Z - info: Running on android test: 33. can get the network status

2016-03-30T20:20:19.256Z - info: Running on ios test: 39. peerAvailabilityChange is called

2016-03-30T20:20:19.707Z - info: Running on android test: 34. wifi peer is marked unavailable if announcements stop

2016-03-30T20:20:21.871Z - info: Running on ios test: 40. Can connect to a remote peer

2016-03-30T20:20:22.319Z - info: Running on android test: 35. Can call start/stopListeningForAdvertisements

2016-03-30T20:20:23.451Z - info: Running on android test: 36. Calling startListeningForAdvertisements twice is NOT an error

2016-03-30T20:20:24.134Z - info: Running on android test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-03-30T20:20:25.044Z - info: Running on android test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-30T20:20:26.553Z - info: Running on android test: 39. peerAvailabilityChange is called

2016-03-30T20:20:29.058Z - info: Running on android test: 40. Can connect to a remote peer

2016-03-30T20:20:38.554Z - info: Running on android test: 41. Can shift large amounts of data

2016-03-30T20:20:49.481Z - info: Running on android test: 42. #startListeningForAdvertisements should fail if start not called

2016-03-30T20:20:53.063Z - info: Running on android test: 43. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-30T20:20:53.670Z - info: Running on android test: 44. should be able to call #stopListeningForAdvertisements many times

2016-03-30T20:20:54.164Z - info: Running on android test: 45. should be able to call #startListeningForAdvertisements many times

2016-03-30T20:20:54.953Z - info: Running on android test: 46. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-30T20:20:56.287Z - info: Running on android test: 47. should be able to call #stopAdvertisingAndListening many times

2016-03-30T20:20:56.933Z - info: Running on android test: 48. can get the network status before starting

2016-03-30T20:20:58.868Z - info: Running on android test: 49. error returned with bad router

2016-03-30T20:20:59.457Z - info: Running on android test: 50. all services are stopped when we call stop

2016-03-30T20:21:00.562Z - info: Running on android test: 51. make sure terminateConnection is properly hooked up

2016-03-30T20:21:02.404Z - info: Running on android test: 52. make sure terminateListener is properly hooked up

2016-03-30T20:21:03.035Z - info: Running on android test: 53. make sure we actually call kill connections properly

2016-03-30T20:21:03.529Z - info: Running on android test: 54. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received

2016-03-30T20:21:04.298Z - info: Running on android test: 55. We repeat failedConnection event when we get it from thaliTcpServersManager

2016-03-30T20:21:05.001Z - info: Running on android test: 56. we successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-30T20:21:06.266Z - debug: Socket disconnected: transport close 3 (LGE-LG-H815)

2016-03-30T20:21:06.343Z - debug: Socket disconnected: transport close 5 (motorola-Nexus 6)

2016-03-30T20:21:06.603Z - debug: Socket disconnected: transport close 4 (samsung-SM-N910C)

2016-03-30T20:22:33.681Z - warn: Failed on ios test: 40. Can connect to a remote peer

2016-03-30T20:22:33.682Z - info: Running on ios test: 41. Can shift large amounts of data

2016-03-30T20:24:55.288Z - warn: Failed on ios test: 41. Can shift large amounts of data

2016-03-30T20:24:55.289Z - info: Running on ios test: 42. #startListeningForAdvertisements should fail if start not called

2016-03-30T20:25:03.958Z - info: Running on ios test: 43. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-30T20:25:23.778Z - info: Running on ios test: 44. should be able to call #stopListeningForAdvertisements many times

2016-03-30T20:25:25.720Z - info: Running on ios test: 45. should be able to call #startListeningForAdvertisements many times

2016-03-30T20:25:26.961Z - info: Running on ios test: 46. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-30T20:25:29.337Z - info: Running on ios test: 47. should be able to call #stopAdvertisingAndListening many times

2016-03-30T20:25:30.886Z - info: Running on ios test: 48. can get the network status before starting

2016-03-30T20:26:01.364Z - info: Running on ios test: 49. error returned with bad router

2016-03-30T20:26:08.201Z - info: Running on ios test: 50. all services are stopped when we call stop

2016-03-30T20:26:09.627Z - info: Running on ios test: 51. make sure terminateConnection is properly hooked up

2016-03-30T20:26:14.438Z - info: Running on ios test: 52. make sure terminateListener is properly hooked up

2016-03-30T20:26:24.908Z - info: Running on ios test: 53. make sure we actually call kill connections properly

2016-03-30T20:26:25.344Z - warn: Failed on ios test: 53. make sure we actually call kill connections properly

2016-03-30T20:26:25.346Z - info: Running on ios test: 54. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received

2016-03-30T20:26:25.721Z - info: Running on ios test: 55. We repeat failedConnection event when we get it from thaliTcpServersManager

2016-03-30T20:26:26.303Z - info: Running on ios test: 56. we successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-30T20:27:51.829Z - debug: Socket disconnected: ping timeout 1 (Apple-Iphone5s-1)

2016-03-30T20:39:12.623Z - debug: Socket disconnected: transport close 2 (Apple-Iphone6-1)

2016-03-30T20:39:12.631Z - debug: Socket disconnected: transport close 0 (Apple-Iphone5-1)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m
2016-03-30T20:20:08.885Z - error: Too many emit retries to device: Apple-Iphone5s-1

2016-03-30T20:24:52.217Z - error: Too many emit retries to device: Apple-Iphone5s-1

2016-03-30T20:25:14.308Z - error: Too many emit retries to device: Apple-Iphone5s-1

2016-03-30T20:25:41.483Z - error: Too many emit retries to device: Apple-Iphone5s-1


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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/646862831c69957_SHA256_the_PSK_Identity_yaronyg/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/646862831c69957_SHA256_the_PSK_Identity_yaronyg/thali07_LGE-LG-H815.md)

####Node name: thali08
Console output:
```
STOP log received from  ZX1G429CRK Test has  FAILED
STOP log received from  41006f95c8139173 Test has  FAILED
Device test finished on 41006f95c8139173 
Device test finished on ZX1G429CRK 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/646862831c69957_SHA256_the_PSK_Identity_yaronyg/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/646862831c69957_SHA256_the_PSK_Identity_yaronyg/thali08_motorola-Nexus 6.md)


###iOS Logs
[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/646862831c69957_SHA256_the_PSK_Identity_yaronyg/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/646862831c69957_SHA256_the_PSK_Identity_yaronyg/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/646862831c69957_SHA256_the_PSK_Identity_yaronyg/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/646862831c69957_SHA256_the_PSK_Identity_yaronyg/iOS_Iphone6-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/646862831c69957_SHA256_the_PSK_Identity_yaronyg/iOS_server.md)





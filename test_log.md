#### Test 63998117de3e24f Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-03-29T14:22:33.697Z - info: listening on *:3000

2016-03-29T14:22:34.352Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:0

2016-03-29T14:22:34.742Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:1

2016-03-29T14:22:37.731Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:2

2016-03-29T14:22:39.438Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:3

2016-03-29T14:22:39.440Z - info: Required number of ios devices presented (3)

2016-03-29T14:22:39.444Z - info: Starting unit test run for platform: ios

2016-03-29T14:22:40.183Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-29T14:22:40.690Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-29T14:22:41.093Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-29T14:22:41.499Z - info: Running on ios test: 4. native server connections all up

2016-03-29T14:22:42.016Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-29T14:22:42.332Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:4

2016-03-29T14:22:42.583Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-29T14:22:42.996Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-29T14:22:43.621Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-29T14:22:44.698Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-29T14:22:46.715Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-29T14:22:49.858Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-29T14:22:52.302Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-29T14:22:52.670Z - info: Running on ios test: 13. closeAll with promise

2016-03-29T14:22:52.961Z - info: Running on ios test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-03-29T14:22:53.367Z - info: Running on ios test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-03-29T14:22:53.777Z - info: Running on ios test: 16. multiplex can send data

2016-03-29T14:22:54.197Z - info: Running on ios test: 17. enqueue and run in order

2016-03-29T14:22:54.799Z - info: Running on ios test: 18. enqueueAtTop and run backwards

2016-03-29T14:22:55.205Z - info: Running on ios test: 19. mix enqueue and enqueueAtTop

2016-03-29T14:22:55.729Z - info: Running on ios test: 20. queues handled independently

2016-03-29T14:22:56.224Z - info: Running on ios test: 21. basic

2016-03-29T14:22:56.645Z - info: Running on ios test: 22. another

2016-03-29T14:22:56.924Z - info: Running on ios test: 23. can pass data in setup

2016-03-29T14:22:57.229Z - info: Running on ios test: 24. #startListeningForAdvertisements should fail if start not called

2016-03-29T14:22:57.533Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:5

2016-03-29T14:22:57.536Z - info: Required number of android devices presented (3)

2016-03-29T14:22:57.539Z - info: Starting unit test run for platform: android

2016-03-29T14:22:57.615Z - info: Running on ios test: 25. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-29T14:22:58.156Z - info: Running on ios test: 26. should be able to call #stopListeningForAdvertisements many times

2016-03-29T14:22:58.467Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-29T14:22:58.604Z - info: Running on ios test: 27. should be able to call #startListeningForAdvertisements many times

2016-03-29T14:22:59.274Z - info: Running on ios test: 28. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-29T14:22:59.585Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-29T14:23:02.396Z - info: Running on ios test: 29. should be able to call #stopAdvertisingAndListening many times

2016-03-29T14:23:02.614Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-29T14:23:03.035Z - info: Running on ios test: 30. #start should fail if called twice in a row

2016-03-29T14:23:03.555Z - info: Running on android test: 4. native server connections all up

2016-03-29T14:23:03.775Z - info: Running on ios test: 31. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-29T14:23:04.187Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-29T14:23:04.571Z - info: Running on ios test: 32. does not send duplicate availability changes

2016-03-29T14:23:04.742Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-29T14:23:05.053Z - info: Running on ios test: 33. can get the network status

2016-03-29T14:23:05.184Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-29T14:23:09.949Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-29T14:23:23.325Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-29T14:23:24.567Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-29T14:23:25.107Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-29T14:23:25.694Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-29T14:23:26.325Z - info: Running on android test: 13. closeAll with promise

2016-03-29T14:23:27.148Z - info: Running on android test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-03-29T14:23:27.916Z - info: Running on android test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-03-29T14:23:28.287Z - info: Running on android test: 16. multiplex can send data

2016-03-29T14:23:28.725Z - info: Running on android test: 17. enqueue and run in order

2016-03-29T14:23:29.859Z - info: Running on android test: 18. enqueueAtTop and run backwards

2016-03-29T14:23:30.719Z - info: Running on android test: 19. mix enqueue and enqueueAtTop

2016-03-29T14:23:31.206Z - info: Running on android test: 20. queues handled independently

2016-03-29T14:23:31.652Z - info: Running on android test: 21. basic

2016-03-29T14:23:32.141Z - info: Running on android test: 22. another

2016-03-29T14:23:32.601Z - info: Running on android test: 23. can pass data in setup

2016-03-29T14:23:32.953Z - info: Running on android test: 24. #startListeningForAdvertisements should fail if start not called

2016-03-29T14:23:33.527Z - info: Running on android test: 25. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-29T14:23:33.909Z - info: Running on android test: 26. should be able to call #stopListeningForAdvertisements many times

2016-03-29T14:23:34.514Z - info: Running on android test: 27. should be able to call #startListeningForAdvertisements many times

2016-03-29T14:23:35.245Z - info: Running on android test: 28. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-29T14:23:37.657Z - info: Running on android test: 29. should be able to call #stopAdvertisingAndListening many times

2016-03-29T14:23:38.144Z - info: Running on android test: 30. #start should fail if called twice in a row

2016-03-29T14:23:38.632Z - info: Running on android test: 31. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-29T14:23:39.655Z - info: Running on android test: 32. does not send duplicate availability changes

2016-03-29T14:23:40.072Z - info: Running on android test: 33. can get the network status

2016-03-29T14:23:40.434Z - info: Running on android test: 34. wifi peer is marked unavailable if announcements stop

2016-03-29T14:23:42.919Z - info: Running on android test: 35. Can call start/stopListeningForAdvertisements

2016-03-29T14:23:43.589Z - info: Running on android test: 36. Calling startListeningForAdvertisements twice is NOT an error

2016-03-29T14:23:44.269Z - info: Running on android test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-03-29T14:23:45.193Z - info: Running on android test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-29T14:23:47.708Z - info: Running on android test: 39. peerAvailabilityChange is called

2016-03-29T14:23:50.667Z - info: Running on android test: 40. Can connect to a remote peer

2016-03-29T14:24:00.705Z - info: Running on android test: 41. Can shift large amounts of data

2016-03-29T14:24:10.001Z - info: Running on android test: 42. #startListeningForAdvertisements should fail if start not called

2016-03-29T14:24:12.140Z - info: Running on android test: 43. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-29T14:24:12.859Z - info: Running on android test: 44. should be able to call #stopListeningForAdvertisements many times

2016-03-29T14:24:13.297Z - info: Running on android test: 45. should be able to call #startListeningForAdvertisements many times

2016-03-29T14:24:14.143Z - info: Running on android test: 46. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-29T14:24:15.556Z - info: Running on android test: 47. should be able to call #stopAdvertisingAndListening many times

2016-03-29T14:24:16.496Z - info: Running on android test: 48. can get the network status before starting

2016-03-29T14:24:17.027Z - info: Running on android test: 49. error returned with bad router

2016-03-29T14:24:17.512Z - info: Running on android test: 50. all services are stopped when we call stop

2016-03-29T14:24:18.536Z - info: Running on android test: 51. make sure terminateConnection is properly hooked up

2016-03-29T14:24:19.807Z - info: Running on android test: 52. make sure terminateListener is properly hooked up

2016-03-29T14:24:20.297Z - info: Running on android test: 53. make sure we actually call kill connections properly

2016-03-29T14:24:20.830Z - info: Running on android test: 54. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received

2016-03-29T14:24:21.421Z - info: Running on android test: 55. We repeat failedConnection event when we get it from thaliTcpServersManager

2016-03-29T14:24:21.945Z - info: Running on android test: 56. we successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-29T14:24:23.092Z - debug: Socket disconnected: transport close 5 (motorola-Nexus 6)

2016-03-29T14:24:23.189Z - debug: Socket disconnected: transport close 0 (LGE-LG-H815)

2016-03-29T14:24:23.480Z - debug: Socket disconnected: transport close 4 (samsung-SM-N910C)

2016-03-29T14:24:25.075Z - debug: Socket disconnected: transport error 1 (Apple-Iphone6-1)

2016-03-29T14:42:14.445Z - debug: Socket disconnected: transport close 6 (NOT YET SET)

2016-03-29T14:42:14.460Z - debug: Socket disconnected: transport close 3 (Apple-Iphone5s-1)

2016-03-29T14:42:14.481Z - debug: Socket disconnected: transport close 2 (Apple-Iphone5-1)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m
2016-03-29T14:23:14.877Z - error: Too many emit retries to device: Apple-Iphone6-1

2016-03-29T14:24:31.721Z - error: Too many emit retries to device: LGE-LG-H815
2016-03-29T14:24:31.722Z - error: Too many emit retries to device: motorola-Nexus 6

2016-03-29T14:24:34.088Z - error: Too many emit retries to device: Apple-Iphone6-1


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
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/63998117de3e24f_More_tests_vjrantal/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/63998117de3e24f_More_tests_vjrantal/thali07_LGE-LG-H815.md)

####Node name: thali08
Console output:
```
STOP log received from  ZX1G429CRK Test has  FAILED
STOP log received from  41006f95c8139173 Test has  FAILED
Device test finished on 41006f95c8139173 
Device test finished on ZX1G429CRK 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/63998117de3e24f_More_tests_vjrantal/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/63998117de3e24f_More_tests_vjrantal/thali08_motorola-Nexus 6.md)


###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/63998117de3e24f_More_tests_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/63998117de3e24f_More_tests_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/63998117de3e24f_More_tests_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/63998117de3e24f_More_tests_vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/63998117de3e24f_More_tests_vjrantal/iOS_server.md)





#### Test 64613803f00187f Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-03-30T12:13:54.058Z - info: listening on *:3000

2016-03-30T12:13:55.130Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket: 0

2016-03-30T12:13:55.140Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket: 0

2016-03-30T12:13:58.440Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket: 1

2016-03-30T12:13:58.443Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket: 1

2016-03-30T12:13:58.444Z - info: Updating existing device: Apple-Iphone6-1 (undefined)

2016-03-30T12:13:58.777Z - debug: Device presented: LGE-LG-H815 (android) unittest socket: 2

2016-03-30T12:13:58.779Z - debug: Device presented: LGE-LG-H815 (android) unittest socket: 2

2016-03-30T12:13:59.571Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket: 3

2016-03-30T12:13:59.572Z - info: All 4 ios devices are present

2016-03-30T12:13:59.580Z - info: Starting unit test run on 4 ios devices

2016-03-30T12:13:59.616Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket: 3

2016-03-30T12:13:59.617Z - info: Updating existing device: Apple-Iphone6-1 (undefined)

2016-03-30T12:14:01.800Z - debug: Device presented: samsung-SM-N910C (android) unittest socket: 4

2016-03-30T12:14:08.229Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket: 5

2016-03-30T12:14:08.230Z - info: All 4 android devices are present

2016-03-30T12:14:08.232Z - info: Starting unit test run on 4 android devices

2016-03-30T12:14:09.001Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-30T12:14:09.460Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-30T12:14:09.934Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-30T12:14:10.564Z - info: Running on android test: 4. native server connections all up

2016-03-30T12:14:11.214Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-30T12:14:11.633Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-30T12:14:12.111Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-30T12:14:12.866Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-30T12:14:13.612Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-30T12:14:14.613Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-30T12:14:15.213Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-30T12:14:15.712Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-30T12:14:16.139Z - info: Running on android test: 13. closeAll with promise

2016-03-30T12:14:16.576Z - info: Running on android test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-03-30T12:14:17.069Z - info: Running on android test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-03-30T12:14:17.577Z - info: Running on android test: 16. multiplex can send data

2016-03-30T12:14:18.014Z - info: Running on android test: 17. enqueue and run in order

2016-03-30T12:14:18.852Z - info: Running on android test: 18. enqueueAtTop and run backwards

2016-03-30T12:14:19.673Z - info: Running on android test: 19. mix enqueue and enqueueAtTop

2016-03-30T12:14:20.266Z - info: Running on android test: 20. queues handled independently

2016-03-30T12:14:20.746Z - info: Running on android test: 21. basic

2016-03-30T12:14:21.363Z - info: Running on android test: 22. another

2016-03-30T12:14:21.779Z - info: Running on android test: 23. can pass data in setup

2016-03-30T12:14:22.459Z - warn: Failed on android test: 23. can pass data in setup

2016-03-30T12:14:22.461Z - info: Running on android test: 24. #startListeningForAdvertisements should fail if start not called

2016-03-30T12:14:23.013Z - info: Running on android test: 25. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-30T12:14:23.482Z - info: Running on android test: 26. should be able to call #stopListeningForAdvertisements many times

2016-03-30T12:14:24.143Z - info: Running on android test: 27. should be able to call #startListeningForAdvertisements many times

2016-03-30T12:14:24.920Z - info: Running on android test: 28. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-30T12:14:25.742Z - info: Running on android test: 29. should be able to call #stopAdvertisingAndListening many times

2016-03-30T12:14:26.162Z - info: Running on android test: 30. #start should fail if called twice in a row

2016-03-30T12:14:27.894Z - info: Running on android test: 31. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-30T12:14:30.205Z - info: Running on android test: 32. does not send duplicate availability changes

2016-03-30T12:14:30.641Z - info: Running on android test: 33. can get the network status

2016-03-30T12:14:30.973Z - info: Running on android test: 34. wifi peer is marked unavailable if announcements stop

2016-03-30T12:14:33.939Z - info: Running on android test: 35. Can call start/stopListeningForAdvertisements

2016-03-30T12:14:34.542Z - info: Running on android test: 36. Calling startListeningForAdvertisements twice is NOT an error

2016-03-30T12:14:35.212Z - info: Running on android test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-03-30T12:14:35.941Z - info: Running on android test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-30T12:14:37.024Z - info: Running on android test: 39. peerAvailabilityChange is called

2016-03-30T12:14:39.513Z - info: Running on android test: 40. Can connect to a remote peer

2016-03-30T12:14:53.077Z - info: Running on android test: 41. Can shift large amounts of data

2016-03-30T12:15:02.465Z - info: Running on android test: 42. #startListeningForAdvertisements should fail if start not called

2016-03-30T12:15:06.211Z - info: Running on android test: 43. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-30T12:15:08.242Z - info: Running on android test: 44. should be able to call #stopListeningForAdvertisements many times

2016-03-30T12:15:09.370Z - info: Running on android test: 45. should be able to call #startListeningForAdvertisements many times

2016-03-30T12:15:10.540Z - info: Running on android test: 46. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-30T12:15:11.863Z - info: Running on android test: 47. should be able to call #stopAdvertisingAndListening many times

2016-03-30T12:15:12.945Z - info: Running on android test: 48. can get the network status before starting

2016-03-30T12:15:13.403Z - info: Running on android test: 49. error returned with bad router

2016-03-30T12:15:13.832Z - info: Running on android test: 50. all services are stopped when we call stop

2016-03-30T12:15:14.938Z - info: Running on android test: 51. make sure terminateConnection is properly hooked up

2016-03-30T12:15:15.558Z - info: Running on android test: 52. make sure terminateListener is properly hooked up

2016-03-30T12:15:16.039Z - info: Running on android test: 53. make sure we actually call kill connections properly

2016-03-30T12:15:16.516Z - info: Running on android test: 54. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received

2016-03-30T12:15:16.962Z - info: Running on android test: 55. We repeat failedConnection event when we get it from thaliTcpServersManager

2016-03-30T12:15:17.494Z - info: Running on android test: 56. we successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-30T12:15:18.651Z - info: Socket disconnected: transport close 5 (motorola-Nexus 6)

2016-03-30T12:15:18.688Z - info: Socket disconnected: transport close 2 (LGE-LG-H815)

2016-03-30T12:15:18.995Z - info: Socket disconnected: transport close 4 (samsung-SM-N910C)

2016-03-30T12:33:23.401Z - info: Socket disconnected: transport close 0 (Apple-Iphone6-1)

2016-03-30T12:33:23.424Z - info: Socket disconnected: transport close 3 (Apple-Iphone6-1)

2016-03-30T12:33:23.458Z - info: Socket disconnected: transport close 1 (Apple-Iphone6-1)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m
2016-03-30T12:15:27.261Z - error: Too many emit retries to device: LGE-LG-H815

2016-03-30T12:15:27.263Z - error: Too many emit retries to device: LGE-LG-H815


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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/64613803f00187f_Test_framework_improvements_vjrantal/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/64613803f00187f_Test_framework_improvements_vjrantal/thali07_LGE-LG-H815.md)

####Node name: thali08
Console output:
```
STOP log received from  ZX1G429CRK Test has  FAILED
STOP log received from  41006f95c8139173 Test has  FAILED
Device test finished on 41006f95c8139173 
Device test finished on ZX1G429CRK 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/64613803f00187f_Test_framework_improvements_vjrantal/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/64613803f00187f_Test_framework_improvements_vjrantal/thali08_motorola-Nexus 6.md)


###iOS Logs
[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/64613803f00187f_Test_framework_improvements_vjrantal/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/64613803f00187f_Test_framework_improvements_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/64613803f00187f_Test_framework_improvements_vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/64613803f00187f_Test_framework_improvements_vjrantal/iOS_Iphone6-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/64613803f00187f_Test_framework_improvements_vjrantal/iOS_server.md)





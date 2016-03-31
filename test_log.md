#### Test 64613803adf70b9 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-03-31T14:28:58.197Z - info: Require 3 ios devices

2016-03-31T14:28:58.216Z - info: Require 3 android devices

2016-03-31T14:28:58.275Z - info: listening on *:3000

2016-03-31T14:29:00.866Z - debug: Device presented: Apple-Iphone6-1 (6e29bb36-795a-40a4-b8f8-92fec7ac3044) - ios Version 9.1 (Build 13B143)

2016-03-31T14:29:00.929Z - debug: Device presented: Apple-Iphone5-1 (d41f7d6f-4179-4b49-a13d-3a3136ac0d20) - ios Version 9.1 (Build 13B143)

2016-03-31T14:29:01.363Z - debug: Device presented: LGE-LG-H815 (18d69230-3e98-40c1-aeb6-4768d8d99ac3) - android 5.1

2016-03-31T14:29:01.754Z - debug: Device presented: Apple-Iphone6-1 (6e29bb36-795a-40a4-b8f8-92fec7ac3044) - ios Version 9.1 (Build 13B143)

2016-03-31T14:29:01.755Z - info: Updating existing device: Apple-Iphone6-1 (6e29bb36-795a-40a4-b8f8-92fec7ac3044)

2016-03-31T14:29:01.963Z - debug: Device presented: Apple-Iphone5-1 (d41f7d6f-4179-4b49-a13d-3a3136ac0d20) - ios Version 9.1 (Build 13B143)

2016-03-31T14:29:01.964Z - info: Updating existing device: Apple-Iphone5-1 (d41f7d6f-4179-4b49-a13d-3a3136ac0d20)

2016-03-31T14:29:02.388Z - debug: Device presented: LGE-LG-H815 (18d69230-3e98-40c1-aeb6-4768d8d99ac3) - android 5.1

2016-03-31T14:29:02.389Z - info: Updating existing device: LGE-LG-H815 (18d69230-3e98-40c1-aeb6-4768d8d99ac3)

2016-03-31T14:29:02.868Z - debug: Device presented: Apple-Iphone5s-1 (62a5ca9b-7b14-4166-9d1c-c9878615440b) - ios Version 9.1 (Build 13B143)

2016-03-31T14:29:02.873Z - debug: Device presented: LGE-Nexus 5 (ed3d2f50-eb9b-448c-aa19-b294e3a865a7) - android 5.1.1

2016-03-31T14:29:03.843Z - debug: Device presented: Apple-Iphone5s-1 (62a5ca9b-7b14-4166-9d1c-c9878615440b) - ios Version 9.1 (Build 13B143)

2016-03-31T14:29:03.845Z - info: Updating existing device: Apple-Iphone5s-1 (62a5ca9b-7b14-4166-9d1c-c9878615440b)

2016-03-31T14:29:03.893Z - debug: Device presented: LGE-Nexus 5 (ed3d2f50-eb9b-448c-aa19-b294e3a865a7) - android 5.1.1

2016-03-31T14:29:03.894Z - info: Updating existing device: LGE-Nexus 5 (ed3d2f50-eb9b-448c-aa19-b294e3a865a7)

2016-03-31T14:29:06.740Z - debug: Device presented: samsung-SM-N910C (225be878-d40d-41a8-b923-e9d5889e0944) - android 5.1.1

2016-03-31T14:29:26.926Z - debug: Device presented: motorola-Nexus 6 (e53a4725-b258-4357-b9c9-4ce37336a0f4) - android 5.1.1

2016-03-31T14:29:26.928Z - info: All 4 android devices are present

2016-03-31T14:29:26.930Z - info: Disqualifying device with unsupported hardware: LGE-Nexus 5

2016-03-31T14:29:26.943Z - info: Starting unit test run on 3 android devices

2016-03-31T14:29:27.838Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-31T14:29:28.002Z - info: Socket to device LGE-Nexus 5 disconnected: transport close

2016-03-31T14:29:28.467Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-31T14:29:28.963Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-31T14:29:29.752Z - info: Running on android test: 4. native server connections all up

2016-03-31T14:29:30.545Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-31T14:29:31.387Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-31T14:29:33.001Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-31T14:29:35.821Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-31T14:29:39.737Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-31T14:29:45.572Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-31T14:29:49.778Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-31T14:29:57.314Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-31T14:29:58.460Z - info: Running on android test: 13. closeAll with promise

2016-03-31T14:29:58.947Z - info: Running on android test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-03-31T14:29:59.447Z - info: Running on android test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-03-31T14:29:59.914Z - info: Running on android test: 16. multiplex can send data

2016-03-31T14:30:00.309Z - info: Running on android test: 17. enqueue and run in order

2016-03-31T14:30:01.094Z - info: Running on android test: 18. enqueueAtTop and run backwards

2016-03-31T14:30:01.531Z - info: Running on android test: 19. mix enqueue and enqueueAtTop

2016-03-31T14:30:02.151Z - info: Running on android test: 20. queues handled independently

2016-03-31T14:30:03.573Z - info: Running on android test: 21. basic

2016-03-31T14:30:04.193Z - info: Running on android test: 22. another

2016-03-31T14:30:04.535Z - info: Running on android test: 23. can pass data in setup

2016-03-31T14:30:04.957Z - info: Running on android test: 24. #startListeningForAdvertisements should fail if start not called

2016-03-31T14:30:05.302Z - info: Running on android test: 25. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-31T14:30:05.711Z - info: Running on android test: 26. should be able to call #stopListeningForAdvertisements many times

2016-03-31T14:30:06.360Z - info: Running on android test: 27. should be able to call #startListeningForAdvertisements many times

2016-03-31T14:30:07.146Z - info: Running on android test: 28. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-31T14:30:09.924Z - info: Running on android test: 29. should be able to call #stopAdvertisingAndListening many times

2016-03-31T14:30:10.462Z - info: Running on android test: 30. #start should fail if called twice in a row

2016-03-31T14:30:10.894Z - info: Running on android test: 31. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-31T14:30:11.855Z - info: Running on android test: 32. does not send duplicate availability changes

2016-03-31T14:30:12.280Z - info: Running on android test: 33. can get the network status

2016-03-31T14:30:12.697Z - info: Running on android test: 34. wifi peer is marked unavailable if announcements stop

2016-03-31T14:30:15.230Z - info: Running on android test: 35. Can call start/stopListeningForAdvertisements

2016-03-31T14:30:15.810Z - info: Running on android test: 36. Calling startListeningForAdvertisements twice is NOT an error

2016-03-31T14:30:16.378Z - info: Running on android test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-03-31T14:30:17.177Z - info: Running on android test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-31T14:30:18.702Z - info: Running on android test: 39. peerAvailabilityChange is called

2016-03-31T14:30:20.356Z - info: Running on android test: 40. Can connect to a remote peer

2016-03-31T14:30:31.370Z - info: Running on android test: 41. Can shift large amounts of data

2016-03-31T14:30:42.516Z - info: Running on android test: 42. #startListeningForAdvertisements should fail if start not called

2016-03-31T14:30:43.025Z - info: Running on android test: 43. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-31T14:30:43.461Z - info: Running on android test: 44. should be able to call #stopListeningForAdvertisements many times

2016-03-31T14:30:43.997Z - info: Running on android test: 45. should be able to call #startListeningForAdvertisements many times

2016-03-31T14:30:44.728Z - info: Running on android test: 46. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-31T14:30:46.039Z - info: Running on android test: 47. should be able to call #stopAdvertisingAndListening many times

2016-03-31T14:30:48.433Z - info: Running on android test: 48. can get the network status before starting

2016-03-31T14:30:48.792Z - info: Running on android test: 49. error returned with bad router

2016-03-31T14:30:49.197Z - info: Running on android test: 50. all services are stopped when we call stop

2016-03-31T14:30:50.287Z - info: Running on android test: 51. make sure terminateConnection is properly hooked up

2016-03-31T14:30:51.586Z - info: Running on android test: 52. make sure terminateListener is properly hooked up

2016-03-31T14:30:52.733Z - info: Running on android test: 53. make sure we actually call kill connections properly

2016-03-31T14:30:53.878Z - info: Running on android test: 54. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received

2016-03-31T14:30:54.564Z - info: Running on android test: 55. We repeat failedConnection event when we get it from thaliTcpServersManager

2016-03-31T14:30:55.095Z - info: Running on android test: 56. we successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-31T14:30:56.138Z - info: Socket to device motorola-Nexus 6 disconnected: transport close

2016-03-31T14:30:56.220Z - info: Socket to device LGE-LG-H815 disconnected: transport close

2016-03-31T14:30:56.636Z - info: Socket to device samsung-SM-N910C disconnected: transport close

2016-03-31T14:32:55.138Z - debug: Too many emit retries to device: LGE-LG-H815

2016-03-31T14:32:55.140Z - debug: Too many emit retries to device: motorola-Nexus 6

2016-03-31T14:48:41.585Z - info: Socket to device Apple-Iphone6-1 disconnected: transport close

2016-03-31T14:48:41.615Z - info: Socket to device Apple-Iphone5-1 disconnected: transport close

2016-03-31T14:48:41.621Z - info: Socket to device Apple-Iphone5s-1 disconnected: transport close


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/64613803adf70b9_Test_framework_improvements_vjrantal/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/64613803adf70b9_Test_framework_improvements_vjrantal/thali07_LGE-LG-H815.md)

####Node name: thali08
Console output:
```
STOP log received from  ZX1G429CRK Test has  FAILED
STOP log received from  41006f95c8139173 Test has  FAILED
Device test finished on 41006f95c8139173 
Device test finished on ZX1G429CRK 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/64613803adf70b9_Test_framework_improvements_vjrantal/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/64613803adf70b9_Test_framework_improvements_vjrantal/thali08_motorola-Nexus 6.md)


###iOS Logs
[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/64613803adf70b9_Test_framework_improvements_vjrantal/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/64613803adf70b9_Test_framework_improvements_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/64613803adf70b9_Test_framework_improvements_vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/64613803adf70b9_Test_framework_improvements_vjrantal/iOS_Iphone6-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/64613803adf70b9_Test_framework_improvements_vjrantal/iOS_server.md)





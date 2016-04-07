#### Test 6568167646f0d89 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-04-07T19:54:19.770Z - info: Require 3 ios devices

2016-04-07T19:54:19.790Z - info: Require 3 android devices

2016-04-07T19:54:19.850Z - info: listening on *:3000

2016-04-07T19:54:20.802Z - debug: Device presented: LGE-Nexus 5 (dee2061a-cd00-4cc0-b6ba-2bce8f353e80) - android 5.1.1

2016-04-07T19:54:20.891Z - debug: Device presented: Apple-Iphone5s-1 (0a5569ba-1ed4-436a-9411-0f7974f7bbc6) - ios Version 9.1 (Build 13B143)

2016-04-07T19:54:21.559Z - debug: Device presented: Apple-Iphone5-1 (dcb5d381-cae6-4f05-8e4a-e2d4f542730f) - ios Version 9.1 (Build 13B143)

2016-04-07T19:54:21.750Z - debug: Device presented: LGE-Nexus 5 (dee2061a-cd00-4cc0-b6ba-2bce8f353e80) - android 5.1.1

2016-04-07T19:54:21.751Z - info: Updating existing device: LGE-Nexus 5 (dee2061a-cd00-4cc0-b6ba-2bce8f353e80)

2016-04-07T19:54:21.869Z - debug: Device presented: Apple-Iphone5s-1 (0a5569ba-1ed4-436a-9411-0f7974f7bbc6) - ios Version 9.1 (Build 13B143)

2016-04-07T19:54:21.870Z - info: Updating existing device: Apple-Iphone5s-1 (0a5569ba-1ed4-436a-9411-0f7974f7bbc6)

2016-04-07T19:54:22.407Z - debug: Device presented: LGE-LG-H815 (0ee09bc4-d1ba-44b1-9083-48a251039996) - android 5.1

2016-04-07T19:54:22.438Z - debug: Device presented: Apple-Iphone6-1 (a01448f3-8faa-4a3b-be30-b4d35e539833) - ios Version 9.1 (Build 13B143)

2016-04-07T19:54:22.578Z - debug: Device presented: Apple-Iphone5-1 (dcb5d381-cae6-4f05-8e4a-e2d4f542730f) - ios Version 9.1 (Build 13B143)

2016-04-07T19:54:22.580Z - info: Updating existing device: Apple-Iphone5-1 (dcb5d381-cae6-4f05-8e4a-e2d4f542730f)

2016-04-07T19:54:23.394Z - debug: Device presented: LGE-LG-H815 (0ee09bc4-d1ba-44b1-9083-48a251039996) - android 5.1

2016-04-07T19:54:23.395Z - info: Updating existing device: LGE-LG-H815 (0ee09bc4-d1ba-44b1-9083-48a251039996)

2016-04-07T19:54:23.452Z - debug: Device presented: Apple-Iphone6-1 (a01448f3-8faa-4a3b-be30-b4d35e539833) - ios Version 9.1 (Build 13B143)

2016-04-07T19:54:23.453Z - info: Updating existing device: Apple-Iphone6-1 (a01448f3-8faa-4a3b-be30-b4d35e539833)

2016-04-07T19:54:24.717Z - debug: Device presented: Apple-IpadAir2-1 (6d9c6404-32a9-487f-ab25-46f5222cb94f) - ios Version 9.1 (Build 13B143)

2016-04-07T19:54:24.718Z - info: All 4 ios devices are present

2016-04-07T19:54:24.725Z - info: Starting unit test run on 4 ios devices

2016-04-07T19:54:25.730Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-04-07T19:54:25.761Z - debug: Device presented: Apple-IpadAir2-1 (6d9c6404-32a9-487f-ab25-46f5222cb94f) - ios Version 9.1 (Build 13B143)

2016-04-07T19:54:25.763Z - info: Updating existing device: Apple-IpadAir2-1 (6d9c6404-32a9-487f-ab25-46f5222cb94f)

2016-04-07T19:54:26.194Z - info: Running on ios test: 2. emits incomingConnectionState

2016-04-07T19:54:26.607Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-04-07T19:54:26.948Z - info: Running on ios test: 4. native server connections all up

2016-04-07T19:54:27.367Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-04-07T19:54:27.735Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-04-07T19:54:28.247Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-04-07T19:54:28.627Z - debug: Device presented: samsung-SM-N910C (135118ba-8416-489b-9d4d-7b6b1a1aa8a1) - android 5.1.1

2016-04-07T19:54:28.630Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-04-07T19:54:28.976Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-04-07T19:54:30.827Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-04-07T19:54:31.338Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-04-07T19:54:31.763Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-04-07T19:54:32.282Z - info: Running on ios test: 13. closeAll with promise

2016-04-07T19:54:32.640Z - info: Running on ios test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-04-07T19:54:33.008Z - info: Running on ios test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-04-07T19:54:33.412Z - info: Running on ios test: 16. enqueue and run in order

2016-04-07T19:54:33.892Z - info: Running on ios test: 17. enqueueAtTop and run backwards

2016-04-07T19:54:34.187Z - info: Running on ios test: 18. mix enqueue and enqueueAtTop

2016-04-07T19:54:34.573Z - info: Running on ios test: 19. queues handled independently

2016-04-07T19:54:34.866Z - info: Running on ios test: 20. basic

2016-04-07T19:54:35.151Z - info: Running on ios test: 21. another

2016-04-07T19:54:35.473Z - info: Running on ios test: 22. can pass data in setup

2016-04-07T19:54:35.844Z - info: Running on ios test: 23. #startListeningForAdvertisements should fail if start not called

2016-04-07T19:54:36.144Z - info: Running on ios test: 24. #startUpdateAdvertisingAndListening should fail if start not called

2016-04-07T19:54:36.384Z - debug: Device presented: motorola-Nexus 6 (33c56910-03e3-4a06-89e3-592791094893) - android 5.1.1

2016-04-07T19:54:36.386Z - info: All 4 android devices are present

2016-04-07T19:54:36.387Z - info: Disqualifying device with unsupported hardware: LGE-Nexus 5

2016-04-07T19:54:36.390Z - info: Starting unit test run on 3 android devices

2016-04-07T19:54:36.464Z - info: Running on ios test: 25. should be able to call #stopListeningForAdvertisements many times

2016-04-07T19:54:36.849Z - info: Running on ios test: 26. should be able to call #startListeningForAdvertisements many times

2016-04-07T19:54:37.222Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-04-07T19:54:37.360Z - info: Running on ios test: 27. should be able to call #startUpdateAdvertisingAndListening many times

2016-04-07T19:54:37.436Z - info: Socket to device LGE-Nexus 5 disconnected: transport close

2016-04-07T19:54:37.594Z - info: Running on android test: 2. emits incomingConnectionState

2016-04-07T19:54:37.949Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-04-07T19:54:38.020Z - info: Running on ios test: 28. should be able to call #stopAdvertisingAndListening many times

2016-04-07T19:54:38.355Z - info: Running on android test: 4. native server connections all up

2016-04-07T19:54:44.968Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-04-07T19:54:53.182Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-04-07T19:54:58.348Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-04-07T19:55:02.160Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-04-07T19:55:02.578Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-04-07T19:55:04.450Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-04-07T19:55:05.126Z - info: Running on ios test: 29. #start should fail if called twice in a row

2016-04-07T19:55:05.224Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-04-07T19:55:05.568Z - info: Running on android test: 12. closeAll can close even when connections open

2016-04-07T19:55:05.573Z - info: Running on ios test: 30. does not emit duplicate discoveryAdvertisingStateUpdate

2016-04-07T19:55:06.020Z - info: Running on android test: 13. closeAll with promise

2016-04-07T19:55:06.031Z - info: Running on ios test: 31. does not send duplicate availability changes

2016-04-07T19:55:06.449Z - info: Running on android test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-04-07T19:55:06.597Z - info: Running on ios test: 32. can get the network status

2016-04-07T19:55:06.865Z - info: Running on android test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-04-07T19:55:15.928Z - info: Running on android test: 16. enqueue and run in order

2016-04-07T19:55:17.540Z - info: Running on android test: 17. enqueueAtTop and run backwards

2016-04-07T19:55:19.677Z - info: Running on ios test: 33. wifi peer is marked unavailable if announcements stop

2016-04-07T19:55:26.595Z - info: Running on android test: 18. mix enqueue and enqueueAtTop

2016-04-07T19:55:29.526Z - info: Running on android test: 19. queues handled independently

2016-04-07T19:55:32.885Z - info: Running on android test: 20. basic

2016-04-07T19:55:37.055Z - info: Running on android test: 21. another

2016-04-07T19:55:42.614Z - info: Running on android test: 22. can pass data in setup

2016-04-07T19:55:49.200Z - info: Running on android test: 23. #startListeningForAdvertisements should fail if start not called

2016-04-07T19:55:53.142Z - info: Running on android test: 24. #startUpdateAdvertisingAndListening should fail if start not called

2016-04-07T19:55:53.653Z - info: Running on android test: 25. should be able to call #stopListeningForAdvertisements many times

2016-04-07T19:55:54.097Z - info: Running on android test: 26. should be able to call #startListeningForAdvertisements many times

2016-04-07T19:55:54.785Z - info: Running on android test: 27. should be able to call #startUpdateAdvertisingAndListening many times

2016-04-07T19:55:55.798Z - info: Running on android test: 28. should be able to call #stopAdvertisingAndListening many times

2016-04-07T19:55:56.112Z - info: Running on android test: 29. #start should fail if called twice in a row

2016-04-07T19:55:56.351Z - info: Running on ios test: 34. Can call start/stopListeningForAdvertisements

2016-04-07T19:55:56.479Z - info: Running on android test: 30. does not emit duplicate discoveryAdvertisingStateUpdate

2016-04-07T19:55:57.000Z - info: Running on ios test: 35. Calling startListeningForAdvertisements twice is NOT an error

2016-04-07T19:55:57.436Z - info: Running on android test: 31. does not send duplicate availability changes

2016-04-07T19:55:57.981Z - info: Running on android test: 32. can get the network status

2016-04-07T19:55:57.985Z - info: Running on ios test: 36. Calling stopListeningForAdvertisements without calling start is NOT an error

2016-04-07T19:56:02.304Z - info: Running on android test: 33. wifi peer is marked unavailable if announcements stop

2016-04-07T19:56:14.336Z - info: Running on android test: 34. Can call start/stopListeningForAdvertisements

2016-04-07T19:56:19.067Z - info: Running on android test: 35. Calling startListeningForAdvertisements twice is NOT an error

2016-04-07T19:56:22.603Z - info: Running on ios test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-04-07T19:56:23.085Z - info: Running on ios test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-04-07T19:56:23.465Z - info: Running on android test: 36. Calling stopListeningForAdvertisements without calling start is NOT an error

2016-04-07T19:56:23.664Z - info: Running on ios test: 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error

2016-04-07T19:56:24.010Z - info: Running on android test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-04-07T19:56:40.372Z - info: Running on android test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-04-07T19:56:56.752Z - info: Running on android test: 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error

2016-04-07T19:57:08.406Z - info: Running on android test: 40. cannot call connect when start listening for advertisements is not active

2016-04-07T19:57:08.911Z - info: Running on android test: 41. peerAvailabilityChange is called

2016-04-07T19:57:09.465Z - info: Running on ios test: 40. cannot call connect when start listening for advertisements is not active

2016-04-07T19:57:10.622Z - info: Running on android test: 42. Can connect to a remote peer

2016-04-07T19:57:16.484Z - warn: Failed on ios test: 40. cannot call connect when start listening for advertisements is not active

2016-04-07T19:57:16.485Z - info: Running on ios test: 41. peerAvailabilityChange is called

2016-04-07T19:57:20.062Z - info: Running on ios test: 42. Can connect to a remote peer

2016-04-07T19:57:24.659Z - info: Running on android test: 43. Get error when trying to double connect to a peer

2016-04-07T19:57:32.050Z - warn: Failed on android test: 43. Get error when trying to double connect to a peer

2016-04-07T19:57:32.051Z - info: Running on android test: 44. Connect port dies if not connected to in in time

2016-04-07T20:00:51.729Z - warn: Failed on ios test: 42. Can connect to a remote peer

2016-04-07T20:00:51.730Z - info: Running on ios test: 43. Get error when trying to double connect to a peer

2016-04-07T20:13:54.796Z - info: Socket to device Apple-IpadAir2-1 disconnected: transport close

2016-04-07T20:13:54.860Z - info: Socket to device Apple-Iphone5s-1 disconnected: transport close

2016-04-07T20:13:54.974Z - info: Socket to device Apple-Iphone6-1 disconnected: transport close

2016-04-07T20:13:54.979Z - info: Socket to device Apple-Iphone5-1 disconnected: transport close

2016-04-07T20:15:46.089Z - info: Socket to device LGE-LG-H815 disconnected: transport close

2016-04-07T20:17:46.675Z - info: Socket to device samsung-SM-N910C disconnected: transport close

2016-04-07T20:17:48.428Z - info: Socket to device motorola-Nexus 6 disconnected: transport close


 
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
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/6568167646f0d89_fix_build_cicorias/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/6568167646f0d89_fix_build_cicorias/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/6568167646f0d89_fix_build_cicorias/iOS_Iphone5-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/6568167646f0d89_fix_build_cicorias/iOS_Iphone6-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/6568167646f0d89_fix_build_cicorias/iOS_server.md)


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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/6568167646f0d89_fix_build_cicorias/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/6568167646f0d89_fix_build_cicorias/thali07_LGE-LG-H815.md)

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
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/6568167646f0d89_fix_build_cicorias/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/6568167646f0d89_fix_build_cicorias/thali08_motorola-Nexus 6.md)





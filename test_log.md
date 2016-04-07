#### Test 656816764cf5745 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-04-07T19:25:18.830Z - info: Require 3 ios devices

2016-04-07T19:25:18.849Z - info: Require 3 android devices

2016-04-07T19:25:18.910Z - info: listening on *:3000

2016-04-07T19:25:19.579Z - debug: Device presented: Apple-Iphone5-1 (cc977dc9-3774-4da7-8114-07bc6d4a1955) - ios Version 9.1 (Build 13B143)

2016-04-07T19:25:19.711Z - debug: Device presented: LGE-Nexus 5 (4d8b97d1-3959-4f7b-b32d-ddc098c90e72) - android 5.1.1

2016-04-07T19:25:20.490Z - debug: Device presented: Apple-Iphone5-1 (cc977dc9-3774-4da7-8114-07bc6d4a1955) - ios Version 9.1 (Build 13B143)

2016-04-07T19:25:20.492Z - info: Updating existing device: Apple-Iphone5-1 (cc977dc9-3774-4da7-8114-07bc6d4a1955)

2016-04-07T19:25:20.568Z - debug: Device presented: Apple-Iphone5s-1 (03445e62-5e92-48cc-8875-30b0fdcb1b59) - ios Version 9.1 (Build 13B143)

2016-04-07T19:25:20.727Z - debug: Device presented: LGE-Nexus 5 (4d8b97d1-3959-4f7b-b32d-ddc098c90e72) - android 5.1.1

2016-04-07T19:25:20.728Z - info: Updating existing device: LGE-Nexus 5 (4d8b97d1-3959-4f7b-b32d-ddc098c90e72)

2016-04-07T19:25:20.906Z - debug: Device presented: Apple-Iphone6-1 (856d22a5-0926-412e-b7a9-ad2877c2c912) - ios Version 9.1 (Build 13B143)

2016-04-07T19:25:21.571Z - debug: Device presented: Apple-Iphone5s-1 (03445e62-5e92-48cc-8875-30b0fdcb1b59) - ios Version 9.1 (Build 13B143)

2016-04-07T19:25:21.572Z - info: Updating existing device: Apple-Iphone5s-1 (03445e62-5e92-48cc-8875-30b0fdcb1b59)

2016-04-07T19:25:21.875Z - debug: Device presented: Apple-Iphone6-1 (856d22a5-0926-412e-b7a9-ad2877c2c912) - ios Version 9.1 (Build 13B143)

2016-04-07T19:25:21.876Z - info: Updating existing device: Apple-Iphone6-1 (856d22a5-0926-412e-b7a9-ad2877c2c912)

2016-04-07T19:25:22.178Z - debug: Device presented: LGE-LG-H815 (b28975ae-7a8c-44a5-8157-e978276288d9) - android 5.1

2016-04-07T19:25:23.162Z - debug: Device presented: LGE-LG-H815 (b28975ae-7a8c-44a5-8157-e978276288d9) - android 5.1

2016-04-07T19:25:23.167Z - info: Updating existing device: LGE-LG-H815 (b28975ae-7a8c-44a5-8157-e978276288d9)

2016-04-07T19:25:23.870Z - debug: Device presented: Apple-IpadAir2-1 (1019d4f9-108b-42a3-b511-e8f2013d3ebb) - ios Version 9.1 (Build 13B143)

2016-04-07T19:25:23.871Z - info: All 4 ios devices are present

2016-04-07T19:25:23.879Z - info: Starting unit test run on 4 ios devices

2016-04-07T19:25:24.922Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-04-07T19:25:24.945Z - debug: Device presented: Apple-IpadAir2-1 (1019d4f9-108b-42a3-b511-e8f2013d3ebb) - ios Version 9.1 (Build 13B143)

2016-04-07T19:25:24.946Z - info: Updating existing device: Apple-IpadAir2-1 (1019d4f9-108b-42a3-b511-e8f2013d3ebb)

2016-04-07T19:25:25.295Z - info: Running on ios test: 2. emits incomingConnectionState

2016-04-07T19:25:25.617Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-04-07T19:25:25.941Z - info: Running on ios test: 4. native server connections all up

2016-04-07T19:25:26.393Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-04-07T19:25:26.531Z - debug: Device presented: samsung-SM-N910C (bd8de379-268c-4761-bc83-1f25c4f385d5) - android 5.1.1

2016-04-07T19:25:26.832Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-04-07T19:25:27.183Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-04-07T19:25:27.601Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-04-07T19:25:28.058Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-04-07T19:25:31.566Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-04-07T19:25:32.156Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-04-07T19:25:32.542Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-04-07T19:25:32.921Z - info: Running on ios test: 13. closeAll with promise

2016-04-07T19:25:33.319Z - info: Running on ios test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-04-07T19:25:33.721Z - info: Running on ios test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-04-07T19:25:34.105Z - info: Running on ios test: 16. enqueue and run in order

2016-04-07T19:25:34.643Z - info: Running on ios test: 17. enqueueAtTop and run backwards

2016-04-07T19:25:34.946Z - info: Running on ios test: 18. mix enqueue and enqueueAtTop

2016-04-07T19:25:35.363Z - info: Running on ios test: 19. queues handled independently

2016-04-07T19:25:35.643Z - info: Running on ios test: 20. basic

2016-04-07T19:25:35.893Z - info: Running on ios test: 21. another

2016-04-07T19:25:36.228Z - info: Running on ios test: 22. can pass data in setup

2016-04-07T19:25:36.496Z - info: Running on ios test: 23. #startListeningForAdvertisements should fail if start not called

2016-04-07T19:25:36.981Z - info: Running on ios test: 24. #startUpdateAdvertisingAndListening should fail if start not called

2016-04-07T19:25:37.234Z - info: Running on ios test: 25. should be able to call #stopListeningForAdvertisements many times

2016-04-07T19:25:37.626Z - info: Running on ios test: 26. should be able to call #startListeningForAdvertisements many times

2016-04-07T19:25:38.165Z - info: Running on ios test: 27. should be able to call #startUpdateAdvertisingAndListening many times

2016-04-07T19:25:41.181Z - info: Running on ios test: 28. should be able to call #stopAdvertisingAndListening many times

2016-04-07T19:25:42.208Z - info: Running on ios test: 29. #start should fail if called twice in a row

2016-04-07T19:25:42.742Z - info: Running on ios test: 30. does not emit duplicate discoveryAdvertisingStateUpdate

2016-04-07T19:25:43.324Z - info: Running on ios test: 31. does not send duplicate availability changes

2016-04-07T19:25:43.858Z - info: Running on ios test: 32. can get the network status

2016-04-07T19:25:44.842Z - info: Running on ios test: 33. wifi peer is marked unavailable if announcements stop

2016-04-07T19:25:46.955Z - debug: Device presented: motorola-Nexus 6 (5ec147a6-a00c-4655-aed7-54a53b71c0b8) - android 5.1.1

2016-04-07T19:25:46.957Z - info: All 4 android devices are present
2016-04-07T19:25:46.958Z - info: Disqualifying device with unsupported hardware: LGE-Nexus 5
2016-04-07T19:25:46.961Z - info: Starting unit test run on 3 android devices

2016-04-07T19:25:48.023Z - info: Socket to device LGE-Nexus 5 disconnected: transport close

2016-04-07T19:25:48.554Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-04-07T19:25:56.837Z - info: Running on ios test: 34. Can call start/stopListeningForAdvertisements

2016-04-07T19:26:00.918Z - info: Running on android test: 2. emits incomingConnectionState

2016-04-07T19:26:01.587Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-04-07T19:26:02.372Z - info: Running on android test: 4. native server connections all up

2016-04-07T19:26:03.920Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-04-07T19:26:05.936Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-04-07T19:26:10.468Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-04-07T19:26:16.370Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-04-07T19:26:26.125Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-04-07T19:26:30.568Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-04-07T19:26:34.846Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-04-07T19:26:35.203Z - info: Running on android test: 12. closeAll can close even when connections open

2016-04-07T19:26:35.820Z - info: Running on android test: 13. closeAll with promise

2016-04-07T19:26:36.319Z - info: Running on android test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-04-07T19:26:36.905Z - info: Running on android test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-04-07T19:26:37.158Z - info: Running on ios test: 35. Calling startListeningForAdvertisements twice is NOT an error

2016-04-07T19:26:37.561Z - info: Running on android test: 16. enqueue and run in order

2016-04-07T19:26:39.485Z - info: Running on android test: 17. enqueueAtTop and run backwards

2016-04-07T19:26:40.626Z - info: Running on android test: 18. mix enqueue and enqueueAtTop

2016-04-07T19:26:41.133Z - info: Running on android test: 19. queues handled independently

2016-04-07T19:26:41.543Z - info: Running on android test: 20. basic

2016-04-07T19:26:41.874Z - info: Running on android test: 21. another

2016-04-07T19:26:42.224Z - info: Running on android test: 22. can pass data in setup

2016-04-07T19:26:42.528Z - info: Running on android test: 23. #startListeningForAdvertisements should fail if start not called

2016-04-07T19:26:42.914Z - info: Running on android test: 24. #startUpdateAdvertisingAndListening should fail if start not called

2016-04-07T19:26:43.245Z - info: Running on android test: 25. should be able to call #stopListeningForAdvertisements many times

2016-04-07T19:26:44.125Z - info: Running on android test: 26. should be able to call #startListeningForAdvertisements many times

2016-04-07T19:26:46.238Z - info: Running on android test: 27. should be able to call #startUpdateAdvertisingAndListening many times

2016-04-07T19:26:49.289Z - info: Running on android test: 28. should be able to call #stopAdvertisingAndListening many times

2016-04-07T19:26:49.709Z - info: Running on android test: 29. #start should fail if called twice in a row

2016-04-07T19:26:51.446Z - info: Running on android test: 30. does not emit duplicate discoveryAdvertisingStateUpdate

2016-04-07T19:26:54.570Z - info: Running on android test: 31. does not send duplicate availability changes

2016-04-07T19:26:54.870Z - info: Running on android test: 32. can get the network status

2016-04-07T19:26:55.424Z - info: Running on android test: 33. wifi peer is marked unavailable if announcements stop

2016-04-07T19:26:56.977Z - info: Running on ios test: 36. Calling stopListeningForAdvertisements without calling start is NOT an error

2016-04-07T19:27:05.611Z - info: Running on android test: 34. Can call start/stopListeningForAdvertisements

2016-04-07T19:27:07.743Z - info: Running on android test: 35. Calling startListeningForAdvertisements twice is NOT an error

2016-04-07T19:27:15.854Z - info: Running on android test: 36. Calling stopListeningForAdvertisements without calling start is NOT an error

2016-04-07T19:27:21.196Z - info: Running on android test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-04-07T19:27:21.301Z - info: Running on ios test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-04-07T19:27:21.754Z - info: Running on android test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-04-07T19:27:21.835Z - info: Running on ios test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-04-07T19:27:22.471Z - info: Running on ios test: 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error

2016-04-07T19:27:35.071Z - info: Running on android test: 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error

2016-04-07T19:27:40.905Z - info: Running on android test: 40. cannot call connect when start listening for advertisements is not active

2016-04-07T19:27:43.654Z - info: Running on android test: 41. peerAvailabilityChange is called

2016-04-07T19:27:45.585Z - info: Running on android test: 42. Can connect to a remote peer

2016-04-07T19:27:55.302Z - info: Running on ios test: 40. cannot call connect when start listening for advertisements is not active

2016-04-07T19:27:55.707Z - warn: Failed on ios test: 40. cannot call connect when start listening for advertisements is not active

2016-04-07T19:27:55.708Z - info: Running on ios test: 41. peerAvailabilityChange is called

2016-04-07T19:28:04.025Z - info: Running on android test: 43. Get error when trying to double connect to a peer

2016-04-07T19:28:30.507Z - info: Running on ios test: 42. Can connect to a remote peer

2016-04-07T19:28:46.583Z - warn: Failed on android test: 43. Get error when trying to double connect to a peer

2016-04-07T19:28:46.585Z - info: Running on android test: 44. Connect port dies if not connected to in in time

2016-04-07T19:30:42.667Z - warn: Failed on ios test: 42. Can connect to a remote peer

2016-04-07T19:30:42.668Z - info: Running on ios test: 43. Get error when trying to double connect to a peer

2016-04-07T19:44:57.434Z - info: Socket to device Apple-Iphone6-1 disconnected: transport close

2016-04-07T19:44:57.472Z - info: Socket to device Apple-Iphone5-1 disconnected: transport close

2016-04-07T19:44:57.608Z - info: Socket to device Apple-Iphone5s-1 disconnected: transport close

2016-04-07T19:44:57.614Z - info: Socket to device Apple-IpadAir2-1 disconnected: transport close

2016-04-07T19:46:46.757Z - info: Socket to device LGE-LG-H815 disconnected: transport close

2016-04-07T19:48:56.879Z - info: Socket to device samsung-SM-N910C disconnected: transport close

2016-04-07T19:48:58.675Z - info: Socket to device motorola-Nexus 6 disconnected: transport close


 
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
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/656816764cf5745_fix_build_cicorias/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/656816764cf5745_fix_build_cicorias/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/656816764cf5745_fix_build_cicorias/iOS_Iphone5-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/656816764cf5745_fix_build_cicorias/iOS_Iphone6-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/656816764cf5745_fix_build_cicorias/iOS_server.md)


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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/656816764cf5745_fix_build_cicorias/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/656816764cf5745_fix_build_cicorias/thali07_LGE-LG-H815.md)

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
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/656816764cf5745_fix_build_cicorias/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/656816764cf5745_fix_build_cicorias/thali08_motorola-Nexus 6.md)





#### Test 6539483973f7970 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-04-06T01:12:19.692Z - info: Require 3 ios devices

2016-04-06T01:12:19.711Z - info: Require 3 android devices

2016-04-06T01:12:19.772Z - info: listening on *:3000

2016-04-06T01:12:20.502Z - debug: Device presented: Apple-IpadAir2-1 (b9648362-bd7c-4ccf-8c9e-e657f2368bf5) - ios Version 9.1 (Build 13B143)

2016-04-06T01:12:20.512Z - debug: Device presented: Apple-Iphone6-1 (1e708892-c95f-4713-9eb4-ebedb0ff7757) - ios Version 9.1 (Build 13B143)

2016-04-06T01:12:20.721Z - debug: Device presented: Apple-Iphone5-1 (23004744-777a-4286-80e8-7c39ced52031) - ios Version 9.1 (Build 13B143)

2016-04-06T01:12:21.378Z - debug: Device presented: Apple-IpadAir2-1 (b9648362-bd7c-4ccf-8c9e-e657f2368bf5) - ios Version 9.1 (Build 13B143)

2016-04-06T01:12:21.379Z - info: Updating existing device: Apple-IpadAir2-1 (b9648362-bd7c-4ccf-8c9e-e657f2368bf5)

2016-04-06T01:12:21.384Z - debug: Device presented: Apple-Iphone6-1 (1e708892-c95f-4713-9eb4-ebedb0ff7757) - ios Version 9.1 (Build 13B143)

2016-04-06T01:12:21.386Z - info: Updating existing device: Apple-Iphone6-1 (1e708892-c95f-4713-9eb4-ebedb0ff7757)

2016-04-06T01:12:21.436Z - debug: Device presented: Apple-Iphone5s-1 (c99173ba-aafb-407b-a44f-72a198cb56d8) - ios Version 9.1 (Build 13B143)

2016-04-06T01:12:21.437Z - info: All 4 ios devices are present

2016-04-06T01:12:21.444Z - info: Starting unit test run on 4 ios devices

2016-04-06T01:12:21.682Z - debug: Device presented: Apple-Iphone5-1 (23004744-777a-4286-80e8-7c39ced52031) - ios Version 9.1 (Build 13B143)

2016-04-06T01:12:21.683Z - info: Updating existing device: Apple-Iphone5-1 (23004744-777a-4286-80e8-7c39ced52031)

2016-04-06T01:12:22.456Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-04-06T01:12:22.604Z - debug: Device presented: Apple-Iphone5s-1 (c99173ba-aafb-407b-a44f-72a198cb56d8) - ios Version 9.1 (Build 13B143)

2016-04-06T01:12:22.605Z - info: Updating existing device: Apple-Iphone5s-1 (c99173ba-aafb-407b-a44f-72a198cb56d8)

2016-04-06T01:12:22.797Z - debug: Device presented: LGE-Nexus 5 (8df366e9-f833-4c85-9fab-24eb6b615915) - android 5.1.1

2016-04-06T01:12:22.865Z - info: Running on ios test: 2. emits incomingConnectionState

2016-04-06T01:12:23.144Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-04-06T01:12:23.464Z - info: Running on ios test: 4. native server connections all up

2016-04-06T01:12:23.856Z - debug: Device presented: LGE-Nexus 5 (8df366e9-f833-4c85-9fab-24eb6b615915) - android 5.1.1

2016-04-06T01:12:23.857Z - info: Updating existing device: LGE-Nexus 5 (8df366e9-f833-4c85-9fab-24eb6b615915)

2016-04-06T01:12:23.895Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-04-06T01:12:24.322Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-04-06T01:12:24.719Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-04-06T01:12:25.075Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-04-06T01:12:25.123Z - debug: Device presented: LGE-LG-H815 (64b18bdd-1907-4dbe-85e1-ca3ed6ec76b9) - android 5.1

2016-04-06T01:12:25.436Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-04-06T01:12:26.123Z - debug: Device presented: LGE-LG-H815 (64b18bdd-1907-4dbe-85e1-ca3ed6ec76b9) - android 5.1

2016-04-06T01:12:26.124Z - info: Updating existing device: LGE-LG-H815 (64b18bdd-1907-4dbe-85e1-ca3ed6ec76b9)

2016-04-06T01:12:27.909Z - debug: Device presented: samsung-SM-N910C (49367318-8deb-4b18-94b6-89063ed2d8b7) - android 5.1.1

2016-04-06T01:12:28.625Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-04-06T01:12:30.320Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-04-06T01:12:30.755Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-04-06T01:12:31.419Z - info: Running on ios test: 13. closeAll with promise

2016-04-06T01:12:34.058Z - info: Running on ios test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-04-06T01:12:34.537Z - info: Running on ios test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-04-06T01:12:34.993Z - info: Running on ios test: 16. enqueue and run in order

2016-04-06T01:12:37.078Z - debug: Device presented: motorola-Nexus 6 (b722aa6d-9758-487c-a6ff-364372366bcc) - android 5.1.1

2016-04-06T01:12:37.080Z - info: All 4 android devices are present

2016-04-06T01:12:37.082Z - info: Disqualifying device with unsupported hardware: LGE-Nexus 5

2016-04-06T01:12:37.085Z - info: Starting unit test run on 3 android devices

2016-04-06T01:12:37.819Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-04-06T01:12:37.878Z - info: Socket to device LGE-Nexus 5 disconnected: transport close

2016-04-06T01:12:38.119Z - info: Running on ios test: 17. enqueueAtTop and run backwards

2016-04-06T01:12:38.346Z - info: Running on android test: 2. emits incomingConnectionState

2016-04-06T01:12:38.489Z - info: Running on ios test: 18. mix enqueue and enqueueAtTop

2016-04-06T01:12:39.403Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-04-06T01:12:41.025Z - info: Running on android test: 4. native server connections all up

2016-04-06T01:12:41.737Z - info: Running on ios test: 19. queues handled independently

2016-04-06T01:12:45.006Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-04-06T01:12:47.045Z - info: Running on ios test: 20. basic

2016-04-06T01:12:49.348Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-04-06T01:12:51.573Z - info: Running on ios test: 21. another

2016-04-06T01:12:53.713Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-04-06T01:13:00.578Z - info: Running on ios test: 22. can pass data in setup

2016-04-06T01:13:06.874Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-04-06T01:13:18.143Z - info: Running on ios test: 23. #startListeningForAdvertisements should fail if start not called

2016-04-06T01:13:21.552Z - info: Running on ios test: 24. #startUpdateAdvertisingAndListening should fail if start not called

2016-04-06T01:13:21.857Z - info: Running on ios test: 25. should be able to call #stopListeningForAdvertisements many times

2016-04-06T01:13:22.330Z - info: Running on ios test: 26. should be able to call #startListeningForAdvertisements many times

2016-04-06T01:13:22.859Z - info: Running on ios test: 27. should be able to call #startUpdateAdvertisingAndListening many times

2016-04-06T01:13:23.482Z - info: Running on ios test: 28. should be able to call #stopAdvertisingAndListening many times

2016-04-06T01:13:48.518Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-04-06T01:13:57.109Z - info: Running on ios test: 29. #start should fail if called twice in a row

2016-04-06T01:13:59.068Z - info: Running on ios test: 30. does not emit duplicate discoveryAdvertisingStateUpdate

2016-04-06T01:13:59.523Z - info: Running on ios test: 31. does not send duplicate availability changes

2016-04-06T01:14:00.107Z - info: Running on ios test: 32. can get the network status

2016-04-06T01:14:09.359Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-04-06T01:14:19.783Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-04-06T01:14:20.191Z - info: Running on android test: 12. closeAll can close even when connections open

2016-04-06T01:14:20.608Z - info: Running on android test: 13. closeAll with promise

2016-04-06T01:14:22.295Z - info: Running on android test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-04-06T01:14:23.698Z - info: Running on android test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-04-06T01:14:31.360Z - info: Running on android test: 16. enqueue and run in order

2016-04-06T01:14:33.484Z - info: Running on android test: 17. enqueueAtTop and run backwards

2016-04-06T01:14:36.649Z - info: Running on android test: 18. mix enqueue and enqueueAtTop

2016-04-06T01:14:38.426Z - info: Running on android test: 19. queues handled independently

2016-04-06T01:14:38.697Z - info: Running on android test: 20. basic

2016-04-06T01:14:38.959Z - info: Running on ios test: 33. wifi peer is marked unavailable if announcements stop

2016-04-06T01:14:39.012Z - info: Running on android test: 21. another

2016-04-06T01:14:39.273Z - info: Running on android test: 22. can pass data in setup

2016-04-06T01:14:39.520Z - info: Running on android test: 23. #startListeningForAdvertisements should fail if start not called

2016-04-06T01:14:39.790Z - info: Running on android test: 24. #startUpdateAdvertisingAndListening should fail if start not called

2016-04-06T01:14:40.055Z - info: Running on android test: 25. should be able to call #stopListeningForAdvertisements many times

2016-04-06T01:14:40.465Z - info: Running on android test: 26. should be able to call #startListeningForAdvertisements many times

2016-04-06T01:14:41.116Z - info: Running on android test: 27. should be able to call #startUpdateAdvertisingAndListening many times

2016-04-06T01:14:41.870Z - info: Running on android test: 28. should be able to call #stopAdvertisingAndListening many times

2016-04-06T01:14:42.170Z - info: Running on android test: 29. #start should fail if called twice in a row

2016-04-06T01:14:42.445Z - info: Running on android test: 30. does not emit duplicate discoveryAdvertisingStateUpdate

2016-04-06T01:14:43.859Z - info: Running on android test: 31. does not send duplicate availability changes

2016-04-06T01:14:44.283Z - info: Running on android test: 32. can get the network status

2016-04-06T01:14:44.572Z - info: Running on android test: 33. wifi peer is marked unavailable if announcements stop

2016-04-06T01:14:45.855Z - info: Running on ios test: 34. Can call start/stopListeningForAdvertisements

2016-04-06T01:14:46.387Z - info: Running on ios test: 35. Calling startListeningForAdvertisements twice is NOT an error

2016-04-06T01:14:46.911Z - info: Running on ios test: 36. Calling stopListeningForAdvertisements without calling start is NOT an error

2016-04-06T01:14:46.954Z - info: Running on android test: 34. Can call start/stopListeningForAdvertisements

2016-04-06T01:14:47.351Z - info: Running on android test: 35. Calling startListeningForAdvertisements twice is NOT an error

2016-04-06T01:14:48.429Z - info: Running on android test: 36. Calling stopListeningForAdvertisements without calling start is NOT an error

2016-04-06T01:14:53.060Z - info: Running on android test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-04-06T01:14:55.557Z - info: Running on android test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-04-06T01:15:04.274Z - info: Running on android test: 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error

2016-04-06T01:15:06.517Z - info: Running on ios test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-04-06T01:15:34.196Z - info: Running on ios test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-04-06T01:15:45.286Z - info: Running on android test: 40. cannot call connect when start listening for advertisements is not active

2016-04-06T01:15:59.286Z - info: Running on android test: 41. peerAvailabilityChange is called

2016-04-06T01:16:02.219Z - info: Running on android test: 42. Can connect to a remote peer

2016-04-06T01:16:14.561Z - info: Running on android test: 43. Get error when trying to double connect to a peer

2016-04-06T01:16:26.270Z - warn: Failed on android test: 43. Get error when trying to double connect to a peer

2016-04-06T01:16:26.273Z - info: Running on android test: 44. Connect port dies if not connected to in in time

2016-04-06T01:16:37.806Z - info: Running on ios test: 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error

2016-04-06T01:16:38.178Z - info: Running on ios test: 40. cannot call connect when start listening for advertisements is not active

2016-04-06T01:16:38.523Z - warn: Failed on ios test: 40. cannot call connect when start listening for advertisements is not active

2016-04-06T01:16:38.526Z - info: Running on ios test: 41. peerAvailabilityChange is called

2016-04-06T01:16:46.733Z - info: Running on ios test: 42. Can connect to a remote peer

2016-04-06T01:18:56.201Z - warn: Failed on ios test: 42. Can connect to a remote peer

2016-04-06T01:18:56.203Z - info: Running on ios test: 43. Get error when trying to double connect to a peer

2016-04-06T01:31:53.227Z - info: Socket to device Apple-Iphone5s-1 disconnected: transport close

2016-04-06T01:31:53.243Z - info: Socket to device Apple-Iphone6-1 disconnected: transport close

2016-04-06T01:31:53.282Z - info: Socket to device Apple-IpadAir2-1 disconnected: transport close

2016-04-06T01:31:53.288Z - info: Socket to device Apple-Iphone5-1 disconnected: transport close

2016-04-06T01:33:48.886Z - info: Socket to device LGE-LG-H815 disconnected: transport close

2016-04-06T01:35:47.000Z - info: Socket to device samsung-SM-N910C disconnected: transport close

2016-04-06T01:35:48.863Z - info: Socket to device motorola-Nexus 6 disconnected: transport close


 
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
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/6539483973f7970__696_Recreate_listeners_yaronyg/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/6539483973f7970__696_Recreate_listeners_yaronyg/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/6539483973f7970__696_Recreate_listeners_yaronyg/iOS_Iphone5-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/6539483973f7970__696_Recreate_listeners_yaronyg/iOS_Iphone6-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/6539483973f7970__696_Recreate_listeners_yaronyg/iOS_server.md)


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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/6539483973f7970__696_Recreate_listeners_yaronyg/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/6539483973f7970__696_Recreate_listeners_yaronyg/thali07_LGE-LG-H815.md)

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
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/6539483973f7970__696_Recreate_listeners_yaronyg/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/6539483973f7970__696_Recreate_listeners_yaronyg/thali08_motorola-Nexus 6.md)





#### Test 681021307227906 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-04-28T19:27:35.201Z - info: Require 3 ios devices

2016-04-28T19:27:35.220Z - info: Require 3 android devices

2016-04-28T19:27:35.279Z - info: listening on *:3000

2016-04-28T19:27:36.449Z - debug: Device presented: samsung-SM-N910C (20bf36eb-1803-47c5-b80a-259c80e8cc95) - android 5.1.1

2016-04-28T19:27:36.463Z - debug: Device presented: LGE-LG-H815 (ae32d682-5a59-44d2-85c1-867966dc69ff) - android 5.1

2016-04-28T19:27:37.001Z - debug: Device presented: Apple-Iphone6-1 (749167e2-4f0b-4861-8dc7-f1c6b8b47666) - ios Version 9.1 (Build 13B143)

2016-04-28T19:27:37.449Z - debug: Device presented: LGE-LG-H815 (ae32d682-5a59-44d2-85c1-867966dc69ff) - android 5.1

2016-04-28T19:27:37.450Z - info: Updating existing device: LGE-LG-H815 (ae32d682-5a59-44d2-85c1-867966dc69ff)

2016-04-28T19:27:37.458Z - debug: Device presented: LGE-Nexus 5 (808271a5-c802-407c-9895-ad17db031801) - android 5.1.1

2016-04-28T19:27:37.469Z - debug: Device presented: Apple-Iphone5s-1 (199e0e2c-9092-4104-af67-e71ad2ae16f8) - ios Version 9.1 (Build 13B143)

2016-04-28T19:27:38.024Z - debug: Device presented: Apple-Iphone6-1 (749167e2-4f0b-4861-8dc7-f1c6b8b47666) - ios Version 9.1 (Build 13B143)

2016-04-28T19:27:38.025Z - info: Updating existing device: Apple-Iphone6-1 (749167e2-4f0b-4861-8dc7-f1c6b8b47666)

2016-04-28T19:27:38.045Z - debug: Device presented: Apple-IpadAir2-1 (76d70763-019d-486c-be48-b3480c768092) - ios Version 9.1 (Build 13B143)

2016-04-28T19:27:38.406Z - debug: Device presented: LGE-Nexus 5 (808271a5-c802-407c-9895-ad17db031801) - android 5.1.1

2016-04-28T19:27:38.408Z - info: Updating existing device: LGE-Nexus 5 (808271a5-c802-407c-9895-ad17db031801)

2016-04-28T19:27:38.483Z - debug: Device presented: Apple-Iphone5s-1 (199e0e2c-9092-4104-af67-e71ad2ae16f8) - ios Version 9.1 (Build 13B143)

2016-04-28T19:27:38.486Z - info: Updating existing device: Apple-Iphone5s-1 (199e0e2c-9092-4104-af67-e71ad2ae16f8)

2016-04-28T19:27:38.506Z - debug: Device presented: Apple-Iphone5-1 (12b0fe5c-5358-4bd1-a579-798f1c8d590d) - ios Version 9.1 (Build 13B143)

2016-04-28T19:27:38.507Z - info: All 4 ios devices are present

2016-04-28T19:27:38.514Z - info: Starting unit test run on 4 ios devices

2016-04-28T19:27:39.155Z - debug: Device presented: Apple-IpadAir2-1 (76d70763-019d-486c-be48-b3480c768092) - ios Version 9.1 (Build 13B143)

2016-04-28T19:27:39.158Z - info: Updating existing device: Apple-IpadAir2-1 (76d70763-019d-486c-be48-b3480c768092)

2016-04-28T19:27:39.290Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-04-28T19:27:39.518Z - debug: Device presented: Apple-Iphone5-1 (12b0fe5c-5358-4bd1-a579-798f1c8d590d) - ios Version 9.1 (Build 13B143)

2016-04-28T19:27:39.519Z - info: Updating existing device: Apple-Iphone5-1 (12b0fe5c-5358-4bd1-a579-798f1c8d590d)

2016-04-28T19:27:42.304Z - info: Running on ios test: 2. emits incomingConnectionState

2016-04-28T19:27:42.371Z - debug: Device presented: motorola-Nexus 6 (8e4c5c53-b1cc-4c01-935f-5e86a62b80aa) - android 5.1.1

2016-04-28T19:27:42.372Z - info: All 4 android devices are present

2016-04-28T19:27:42.373Z - info: Disqualifying device with unsupported hardware: LGE-Nexus 5

2016-04-28T19:27:42.376Z - info: Starting unit test run on 3 android devices

2016-04-28T19:27:42.719Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-04-28T19:27:43.119Z - info: Running on ios test: 4. native server connections all up

2016-04-28T19:27:43.201Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-04-28T19:27:43.328Z - info: Socket to device LGE-Nexus 5 disconnected: transport close

2016-04-28T19:27:43.511Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-04-28T19:27:43.602Z - info: Running on android test: 2. emits incomingConnectionState

2016-04-28T19:27:43.986Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-04-28T19:27:44.031Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-04-28T19:27:44.435Z - info: Running on android test: 4. native server connections all up

2016-04-28T19:27:44.468Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-04-28T19:27:44.958Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-04-28T19:27:44.990Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-04-28T19:27:45.376Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-04-28T19:27:45.384Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-04-28T19:27:45.785Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-04-28T19:27:46.231Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-04-28T19:27:46.597Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-04-28T19:27:47.454Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-04-28T19:27:47.765Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-04-28T19:27:47.910Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-04-28T19:27:48.381Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-04-28T19:27:48.386Z - info: Running on android test: 12. closeAll can close even when connections open

2016-04-28T19:27:48.971Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-04-28T19:27:48.979Z - info: Running on android test: 13. closeAll with promise

2016-04-28T19:27:49.463Z - info: Running on ios test: 13. closeAll with promise

2016-04-28T19:27:49.508Z - info: Running on android test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-04-28T19:27:49.892Z - info: Running on ios test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-04-28T19:27:49.930Z - info: Running on android test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-04-28T19:27:50.276Z - info: Running on ios test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-04-28T19:27:50.312Z - info: Running on android test: 16. enqueue and run in order

2016-04-28T19:27:50.726Z - info: Running on ios test: 16. enqueue and run in order

2016-04-28T19:27:51.074Z - info: Running on android test: 17. enqueueAtTop and run backwards

2016-04-28T19:27:51.211Z - info: Running on ios test: 17. enqueueAtTop and run backwards

2016-04-28T19:27:51.427Z - info: Running on android test: 18. mix enqueue and enqueueAtTop

2016-04-28T19:27:51.510Z - info: Running on ios test: 18. mix enqueue and enqueueAtTop

2016-04-28T19:27:51.904Z - info: Running on android test: 19. queues handled independently

2016-04-28T19:27:51.909Z - info: Running on ios test: 19. queues handled independently

2016-04-28T19:27:52.250Z - info: Running on ios test: 20. basic

2016-04-28T19:27:52.259Z - info: Running on android test: 20. basic

2016-04-28T19:27:52.572Z - info: Running on android test: 21. another

2016-04-28T19:27:52.697Z - info: Running on ios test: 21. another

2016-04-28T19:27:52.881Z - info: Running on android test: 22. can pass data in setup

2016-04-28T19:27:52.996Z - info: Running on ios test: 22. can pass data in setup

2016-04-28T19:27:53.190Z - info: Running on android test: 23. #startListeningForAdvertisements should fail if start not called

2016-04-28T19:27:53.299Z - info: Running on ios test: 23. #startListeningForAdvertisements should fail if start not called

2016-04-28T19:27:53.499Z - info: Running on android test: 24. #startUpdateAdvertisingAndListening should fail if start not called

2016-04-28T19:27:53.622Z - info: Running on ios test: 24. #startUpdateAdvertisingAndListening should fail if start not called

2016-04-28T19:27:53.758Z - info: Running on android test: 25. should be able to call #stopListeningForAdvertisements many times

2016-04-28T19:27:53.901Z - info: Running on ios test: 25. should be able to call #stopListeningForAdvertisements many times

2016-04-28T19:27:54.159Z - info: Running on android test: 26. should be able to call #startListeningForAdvertisements many times

2016-04-28T19:27:54.329Z - info: Running on ios test: 26. should be able to call #startListeningForAdvertisements many times

2016-04-28T19:27:54.896Z - info: Running on ios test: 27. should be able to call #startUpdateAdvertisingAndListening many times

2016-04-28T19:27:55.846Z - info: Running on android test: 27. should be able to call #startUpdateAdvertisingAndListening many times

2016-04-28T19:27:56.244Z - info: Running on ios test: 28. should be able to call #stopAdvertisingAndListening many times

2016-04-28T19:27:57.171Z - info: Running on android test: 28. should be able to call #stopAdvertisingAndListening many times

2016-04-28T19:27:57.592Z - info: Running on android test: 29. #start should fail if called twice in a row

2016-04-28T19:27:58.038Z - info: Running on android test: 30. does not emit duplicate discoveryAdvertisingStateUpdate

2016-04-28T19:27:59.924Z - info: Running on android test: 31. does not send duplicate availability changes

2016-04-28T19:28:00.224Z - info: Running on android test: 32. can get the network status

2016-04-28T19:28:00.593Z - info: Running on android test: 33. wifi peer is marked unavailable if announcements stop

2016-04-28T19:28:02.048Z - info: Running on ios test: 29. #start should fail if called twice in a row

2016-04-28T19:28:02.599Z - info: Running on ios test: 30. does not emit duplicate discoveryAdvertisingStateUpdate

2016-04-28T19:28:03.074Z - info: Running on android test: 34. Can call start/stopListeningForAdvertisements

2016-04-28T19:28:03.100Z - info: Running on ios test: 31. does not send duplicate availability changes

2016-04-28T19:28:03.702Z - info: Running on ios test: 32. can get the network status

2016-04-28T19:28:05.190Z - info: Running on android test: 35. Calling startListeningForAdvertisements twice is NOT an error

2016-04-28T19:28:08.298Z - info: Running on ios test: 33. wifi peer is marked unavailable if announcements stop

2016-04-28T19:28:10.113Z - info: Running on android test: 36. Calling stopListeningForAdvertisements without calling start is NOT an error

2016-04-28T19:28:10.718Z - info: Running on ios test: 34. Can call start/stopListeningForAdvertisements

2016-04-28T19:28:11.207Z - info: Running on android test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-04-28T19:28:11.326Z - info: Running on ios test: 35. Calling startListeningForAdvertisements twice is NOT an error

2016-04-28T19:28:12.330Z - info: Running on android test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-04-28T19:28:20.044Z - info: Running on ios test: 36. Calling stopListeningForAdvertisements without calling start is NOT an error

2016-04-28T19:28:22.998Z - info: Running on android test: 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error

2016-04-28T19:28:28.481Z - info: Running on android test: 40. cannot call connect when start listening for advertisements is not active

2016-04-28T19:28:28.777Z - info: Running on android test: 41. peerAvailabilityChange is called

2016-04-28T19:28:28.838Z - info: Running on ios test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-04-28T19:28:31.956Z - info: Running on ios test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-04-28T19:28:32.033Z - info: Running on android test: 42. Can connect to a remote peer

2016-04-28T19:28:36.217Z - info: Running on ios test: 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error

2016-04-28T19:28:38.885Z - info: Running on ios test: 40. cannot call connect when start listening for advertisements is not active

2016-04-28T19:28:48.262Z - info: Running on android test: 43. Get error when trying to double connect to a peer

2016-04-28T19:28:57.573Z - warn: Failed on ios test: 40. cannot call connect when start listening for advertisements is not active

2016-04-28T19:28:57.575Z - info: Running on ios test: 41. peerAvailabilityChange is called

2016-04-28T19:29:04.440Z - info: Running on ios test: 42. Can connect to a remote peer

2016-04-28T19:29:09.314Z - info: Running on android test: 44. Connect port dies if not connected to in time

2016-04-28T19:29:13.711Z - info: Running on android test: 45. Can shift large amounts of data

2016-04-28T19:29:29.799Z - info: Running on android test: 46. #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection

2016-04-28T19:29:36.802Z - info: Running on android test: 47. #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection

2016-04-28T19:29:53.330Z - info: Running on android test: 48. #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer

2016-04-28T19:30:02.981Z - info: Running on android test: 49. #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer

2016-04-28T19:30:17.832Z - info: Running on android test: 50. We do not emit peerAvailabilityChanged events until one of the start methods is called

2016-04-28T19:30:27.725Z - info: Running on android test: 51. Test updating advertising and parallel data transfer

2016-04-28T19:30:56.833Z - info: Socket to device LGE-LG-H815 disconnected: transport close

2016-04-28T19:31:12.403Z - debug: Device presented: LGE-LG-H815 (0d312d7b-a1f0-4fdd-8d07-b11bf1b493dd) - android 5.1

2016-04-28T19:31:12.409Z - info: All 4 android devices are present

2016-04-28T19:31:12.411Z - info: Starting unit test run on 4 android devices

2016-04-28T19:31:18.466Z - info: Socket to device motorola-Nexus 6 disconnected: transport close

2016-04-28T19:31:18.567Z - warn: Failed on ios test: 42. Can connect to a remote peer

2016-04-28T19:31:18.570Z - info: Running on ios test: 43. Get error when trying to double connect to a peer

2016-04-28T19:47:03.740Z - info: Socket to device Apple-IpadAir2-1 disconnected: transport close

2016-04-28T19:47:03.801Z - info: Socket to device Apple-Iphone5-1 disconnected: transport close

2016-04-28T19:47:03.831Z - info: Socket to device Apple-Iphone6-1 disconnected: transport close

2016-04-28T19:47:03.838Z - info: Socket to device Apple-Iphone5s-1 disconnected: transport close

2016-04-28T19:48:39.022Z - info: Socket to device LGE-LG-H815 disconnected: transport close

2016-04-28T19:50:55.553Z - info: Socket to device samsung-SM-N910C disconnected: transport close


 
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
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/681021307227906_Fixes_and_hardening_tompaana/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/681021307227906_Fixes_and_hardening_tompaana/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/681021307227906_Fixes_and_hardening_tompaana/iOS_Iphone5-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/681021307227906_Fixes_and_hardening_tompaana/iOS_Iphone6-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/681021307227906_Fixes_and_hardening_tompaana/iOS_server.md)


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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/681021307227906_Fixes_and_hardening_tompaana/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/681021307227906_Fixes_and_hardening_tompaana/thali07_LGE-LG-H815.md)

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
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/681021307227906_Fixes_and_hardening_tompaana/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/681021307227906_Fixes_and_hardening_tompaana/thali08_motorola-Nexus 6.md)





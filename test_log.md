#### Test 68102130aff19f4 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-04-28T15:16:49.359Z - info: Require 3 ios devices

2016-04-28T15:16:49.377Z - info: Require 3 android devices

2016-04-28T15:16:49.437Z - info: listening on *:3000

2016-04-28T15:16:50.779Z - debug: Device presented: samsung-SM-N910C (61de8c53-0398-450c-bac4-ce878e36da93) - android 5.1.1

2016-04-28T15:16:51.721Z - debug: Device presented: samsung-SM-N910C (61de8c53-0398-450c-bac4-ce878e36da93) - android 5.1.1

2016-04-28T15:16:51.723Z - info: Updating existing device: samsung-SM-N910C (61de8c53-0398-450c-bac4-ce878e36da93)

2016-04-28T15:16:53.932Z - debug: Device presented: motorola-Nexus 6 (14da5aa6-c6c5-4385-9886-d1d946cf0ae7) - android 5.1.1

2016-04-28T15:16:54.158Z - debug: Device presented: LGE-Nexus 5 (d2a54eff-026e-4739-bbbb-d50dbaa9a161) - android 5.1.1

2016-04-28T15:16:54.727Z - debug: Device presented: Apple-IpadAir2-1 (459efb75-4cda-4d3d-a3fd-156785c33151) - ios Version 9.1 (Build 13B143)

2016-04-28T15:16:54.787Z - debug: Device presented: LGE-LG-H815 (20c3b98c-999e-4e4d-9ab2-a83873e99d2a) - android 5.1

2016-04-28T15:16:54.788Z - info: All 4 android devices are present

2016-04-28T15:16:54.790Z - info: Disqualifying device with unsupported hardware: LGE-Nexus 5

2016-04-28T15:16:54.803Z - info: Starting unit test run on 3 android devices

2016-04-28T15:16:55.049Z - debug: Device presented: Apple-Iphone5-1 (424dcc42-6622-4bce-8b32-e8eb093d9551) - ios Version 9.1 (Build 13B143)

2016-04-28T15:16:55.163Z - debug: Device presented: LGE-Nexus 5 (d2a54eff-026e-4739-bbbb-d50dbaa9a161) - android 5.1.1

2016-04-28T15:16:55.164Z - info: All 4 android devices are present

2016-04-28T15:16:55.165Z - info: Disqualifying device with unsupported hardware: LGE-Nexus 5

2016-04-28T15:16:55.171Z - info: Starting unit test run on 3 android devices

2016-04-28T15:16:55.677Z - debug: Device presented: Apple-IpadAir2-1 (459efb75-4cda-4d3d-a3fd-156785c33151) - ios Version 9.1 (Build 13B143)

2016-04-28T15:16:55.678Z - info: Updating existing device: Apple-IpadAir2-1 (459efb75-4cda-4d3d-a3fd-156785c33151)

2016-04-28T15:16:55.688Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-04-28T15:16:55.692Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-04-28T15:16:55.755Z - info: Socket to device LGE-Nexus 5 disconnected: transport close

2016-04-28T15:16:55.801Z - debug: Device presented: LGE-LG-H815 (20c3b98c-999e-4e4d-9ab2-a83873e99d2a) - android 5.1

2016-04-28T15:16:55.802Z - info: Updating existing device: LGE-LG-H815 (20c3b98c-999e-4e4d-9ab2-a83873e99d2a)

2016-04-28T15:16:56.046Z - debug: Device presented: Apple-Iphone5-1 (424dcc42-6622-4bce-8b32-e8eb093d9551) - ios Version 9.1 (Build 13B143)

2016-04-28T15:16:56.047Z - info: Updating existing device: Apple-Iphone5-1 (424dcc42-6622-4bce-8b32-e8eb093d9551)

2016-04-28T15:16:56.174Z - info: Running on android test: 2. emits incomingConnectionState

2016-04-28T15:16:56.177Z - info: Running on android test: 2. emits incomingConnectionState

2016-04-28T15:16:56.710Z - debug: Device presented: Apple-Iphone5s-1 (0d2f76f8-a697-4c1a-a400-d436c413fa72) - ios Version 9.1 (Build 13B143)

2016-04-28T15:16:57.241Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-04-28T15:16:57.245Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-04-28T15:16:57.658Z - debug: Device presented: Apple-Iphone5s-1 (0d2f76f8-a697-4c1a-a400-d436c413fa72) - ios Version 9.1 (Build 13B143)

2016-04-28T15:16:57.659Z - info: Updating existing device: Apple-Iphone5s-1 (0d2f76f8-a697-4c1a-a400-d436c413fa72)

2016-04-28T15:16:59.789Z - info: Running on android test: 4. native server connections all up

2016-04-28T15:16:59.792Z - info: Running on android test: 4. native server connections all up

2016-04-28T15:17:01.457Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-04-28T15:17:01.459Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-04-28T15:17:17.848Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-04-28T15:17:17.853Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-04-28T15:17:26.741Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-04-28T15:17:26.744Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-04-28T15:17:27.906Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-04-28T15:17:27.908Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-04-28T15:17:28.276Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-04-28T15:17:28.278Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-04-28T15:17:29.150Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-04-28T15:17:29.153Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-04-28T15:17:29.498Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-04-28T15:17:29.502Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-04-28T15:17:29.922Z - info: Running on android test: 12. closeAll can close even when connections open

2016-04-28T15:17:29.925Z - info: Running on android test: 12. closeAll can close even when connections open

2016-04-28T15:17:30.466Z - info: Running on android test: 13. closeAll with promise

2016-04-28T15:17:30.469Z - info: Running on android test: 13. closeAll with promise

2016-04-28T15:17:31.047Z - info: Running on android test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-04-28T15:17:31.059Z - info: Running on android test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-04-28T15:17:31.751Z - info: Running on android test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-04-28T15:17:31.756Z - info: Running on android test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-04-28T15:17:33.211Z - info: Running on android test: 16. enqueue and run in order

2016-04-28T15:17:33.214Z - info: Running on android test: 16. enqueue and run in order

2016-04-28T15:17:33.999Z - info: Running on android test: 17. enqueueAtTop and run backwards

2016-04-28T15:17:34.001Z - info: Running on android test: 17. enqueueAtTop and run backwards

2016-04-28T15:17:34.339Z - info: Running on android test: 18. mix enqueue and enqueueAtTop

2016-04-28T15:17:34.341Z - info: Running on android test: 18. mix enqueue and enqueueAtTop

2016-04-28T15:17:34.905Z - info: Running on android test: 19. queues handled independently

2016-04-28T15:17:34.907Z - info: Running on android test: 19. queues handled independently

2016-04-28T15:17:35.410Z - info: Running on android test: 20. basic

2016-04-28T15:17:35.413Z - info: Running on android test: 20. basic

2016-04-28T15:17:35.721Z - info: Running on android test: 21. another

2016-04-28T15:17:35.725Z - info: Running on android test: 21. another

2016-04-28T15:17:36.023Z - info: Running on android test: 22. can pass data in setup

2016-04-28T15:17:36.025Z - info: Running on android test: 22. can pass data in setup

2016-04-28T15:17:36.333Z - info: Running on android test: 23. #startListeningForAdvertisements should fail if start not called

2016-04-28T15:17:36.335Z - info: Running on android test: 23. #startListeningForAdvertisements should fail if start not called

2016-04-28T15:17:36.760Z - info: Running on android test: 24. #startUpdateAdvertisingAndListening should fail if start not called

2016-04-28T15:17:36.762Z - info: Running on android test: 24. #startUpdateAdvertisingAndListening should fail if start not called

2016-04-28T15:17:37.241Z - info: Running on android test: 25. should be able to call #stopListeningForAdvertisements many times

2016-04-28T15:17:37.243Z - info: Running on android test: 25. should be able to call #stopListeningForAdvertisements many times

2016-04-28T15:17:37.744Z - info: Running on android test: 26. should be able to call #startListeningForAdvertisements many times

2016-04-28T15:17:37.746Z - info: Running on android test: 26. should be able to call #startListeningForAdvertisements many times

2016-04-28T15:17:39.419Z - info: Running on android test: 27. should be able to call #startUpdateAdvertisingAndListening many times

2016-04-28T15:17:39.421Z - info: Running on android test: 27. should be able to call #startUpdateAdvertisingAndListening many times

2016-04-28T15:17:40.695Z - info: Running on android test: 28. should be able to call #stopAdvertisingAndListening many times

2016-04-28T15:17:40.696Z - info: Running on android test: 28. should be able to call #stopAdvertisingAndListening many times

2016-04-28T15:17:41.278Z - info: Running on android test: 29. #start should fail if called twice in a row

2016-04-28T15:17:41.280Z - info: Running on android test: 29. #start should fail if called twice in a row

2016-04-28T15:17:41.636Z - info: Running on android test: 30. does not emit duplicate discoveryAdvertisingStateUpdate

2016-04-28T15:17:41.641Z - info: Running on android test: 30. does not emit duplicate discoveryAdvertisingStateUpdate

2016-04-28T15:17:43.513Z - info: Running on android test: 31. does not send duplicate availability changes

2016-04-28T15:17:43.515Z - info: Running on android test: 31. does not send duplicate availability changes

2016-04-28T15:17:44.000Z - info: Running on android test: 32. can get the network status

2016-04-28T15:17:44.002Z - info: Running on android test: 32. can get the network status

2016-04-28T15:17:44.314Z - info: Running on android test: 33. wifi peer is marked unavailable if announcements stop

2016-04-28T15:17:44.316Z - info: Running on android test: 33. wifi peer is marked unavailable if announcements stop

2016-04-28T15:17:46.662Z - info: Running on android test: 34. Can call start/stopListeningForAdvertisements

2016-04-28T15:17:46.664Z - info: Running on android test: 34. Can call start/stopListeningForAdvertisements

2016-04-28T15:17:48.735Z - info: Running on android test: 35. Calling startListeningForAdvertisements twice is NOT an error

2016-04-28T15:17:48.737Z - info: Running on android test: 35. Calling startListeningForAdvertisements twice is NOT an error

2016-04-28T15:17:50.788Z - info: Running on android test: 36. Calling stopListeningForAdvertisements without calling start is NOT an error

2016-04-28T15:17:50.790Z - info: Running on android test: 36. Calling stopListeningForAdvertisements without calling start is NOT an error

2016-04-28T15:17:51.267Z - info: Running on android test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-04-28T15:17:51.269Z - info: Running on android test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-04-28T15:17:52.407Z - info: Running on android test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-04-28T15:17:52.409Z - info: Running on android test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-04-28T15:17:53.638Z - info: Running on android test: 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error

2016-04-28T15:17:53.640Z - info: Running on android test: 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error

2016-04-28T15:17:54.014Z - info: Running on android test: 40. cannot call connect when start listening for advertisements is not active

2016-04-28T15:17:54.016Z - info: Running on android test: 40. cannot call connect when start listening for advertisements is not active

2016-04-28T15:17:54.385Z - info: Running on android test: 41. peerAvailabilityChange is called

2016-04-28T15:17:54.387Z - info: Running on android test: 41. peerAvailabilityChange is called

2016-04-28T15:17:57.622Z - info: Running on android test: 42. Can connect to a remote peer

2016-04-28T15:17:57.632Z - info: Running on android test: 42. Can connect to a remote peer

2016-04-28T15:18:07.631Z - info: Running on android test: 43. Get error when trying to double connect to a peer

2016-04-28T15:18:07.634Z - info: Running on android test: 43. Get error when trying to double connect to a peer

2016-04-28T15:18:18.304Z - info: Running on android test: 44. Connect port dies if not connected to in time

2016-04-28T15:18:18.307Z - info: Running on android test: 44. Connect port dies if not connected to in time

2016-04-28T15:18:21.152Z - info: Running on android test: 45. Can shift large amounts of data

2016-04-28T15:18:21.159Z - info: Running on android test: 45. Can shift large amounts of data

2016-04-28T15:18:35.983Z - info: Running on android test: 46. #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection

2016-04-28T15:18:35.986Z - info: Running on android test: 46. #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection

2016-04-28T15:18:45.670Z - info: Running on android test: 47. #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection

2016-04-28T15:18:45.673Z - info: Running on android test: 47. #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection

2016-04-28T15:18:56.394Z - info: Running on android test: 48. #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer

2016-04-28T15:18:56.398Z - info: Running on android test: 48. #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer

2016-04-28T15:19:13.762Z - info: Running on android test: 49. #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer

2016-04-28T15:19:13.766Z - info: Running on android test: 49. #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer

2016-04-28T15:19:20.709Z - info: Running on android test: 50. We do not emit peerAvailabilityChanged events until one of the start methods is called

2016-04-28T15:19:20.712Z - info: Running on android test: 50. We do not emit peerAvailabilityChanged events until one of the start methods is called

2016-04-28T15:19:30.136Z - info: Running on android test: 51. Test updating advertising and parallel data transfer

2016-04-28T15:19:30.139Z - info: Running on android test: 51. Test updating advertising and parallel data transfer

2016-04-28T15:20:25.054Z - info: Socket to device motorola-Nexus 6 disconnected: transport close

2016-04-28T15:20:43.097Z - info: Socket to device LGE-LG-H815 disconnected: transport close

2016-04-28T15:20:59.040Z - debug: Device presented: LGE-LG-H815 (e5090ced-4a71-4105-8998-9e47e9609e28) - android 5.1

2016-04-28T15:20:59.041Z - info: All 4 android devices are present

2016-04-28T15:20:59.042Z - info: Starting unit test run on 4 android devices

2016-04-28T15:36:11.296Z - info: Socket to device Apple-IpadAir2-1 disconnected: transport close

2016-04-28T15:36:11.363Z - info: Socket to device Apple-Iphone5-1 disconnected: transport close

2016-04-28T15:36:11.369Z - info: Socket to device Apple-Iphone5s-1 disconnected: transport close

2016-04-28T15:37:45.373Z - info: Socket to device LGE-LG-H815 disconnected: transport close

2016-04-28T15:40:05.383Z - info: Socket to device samsung-SM-N910C disconnected: transport close


 
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
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/68102130aff19f4_Fixes_and_hardening_tompaana/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/68102130aff19f4_Fixes_and_hardening_tompaana/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/68102130aff19f4_Fixes_and_hardening_tompaana/iOS_Iphone5-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/68102130aff19f4_Fixes_and_hardening_tompaana/iOS_Iphone6-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/68102130aff19f4_Fixes_and_hardening_tompaana/iOS_server.md)


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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/68102130aff19f4_Fixes_and_hardening_tompaana/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/68102130aff19f4_Fixes_and_hardening_tompaana/thali07_LGE-LG-H815.md)

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
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/68102130aff19f4_Fixes_and_hardening_tompaana/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/68102130aff19f4_Fixes_and_hardening_tompaana/thali08_motorola-Nexus 6.md)





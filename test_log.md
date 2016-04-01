#### Test 64809936b717dd3 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-04-01T19:40:46.191Z - info: Require 3 ios devices

2016-04-01T19:40:46.210Z - info: Require 3 android devices

2016-04-01T19:40:46.269Z - info: listening on *:3000

2016-04-01T19:40:47.302Z - debug: Device presented: LGE-Nexus 5 (4166d7f3-1250-4221-a418-98d53687112c) - android 5.1.1

2016-04-01T19:40:48.222Z - debug: Device presented: LGE-Nexus 5 (4166d7f3-1250-4221-a418-98d53687112c) - android 5.1.1

2016-04-01T19:40:48.224Z - info: Updating existing device: LGE-Nexus 5 (4166d7f3-1250-4221-a418-98d53687112c)

2016-04-01T19:40:48.340Z - debug: Device presented: Apple-Iphone6-1 (71212020-3711-4e83-8c26-eb77c3161f1f) - ios Version 9.1 (Build 13B143)

2016-04-01T19:40:48.347Z - debug: Device presented: LGE-LG-H815 (922f68b1-620d-4434-af96-ce86215edd41) - android 5.1

2016-04-01T19:40:48.575Z - debug: Device presented: Apple-IpadAir2-1 (781e75ab-492d-4c57-a9b5-e79b28f4dac4) - ios Version 9.1 (Build 13B143)

2016-04-01T19:40:49.400Z - debug: Device presented: LGE-LG-H815 (922f68b1-620d-4434-af96-ce86215edd41) - android 5.1

2016-04-01T19:40:49.402Z - info: Updating existing device: LGE-LG-H815 (922f68b1-620d-4434-af96-ce86215edd41)

2016-04-01T19:40:49.407Z - debug: Device presented: Apple-Iphone6-1 (71212020-3711-4e83-8c26-eb77c3161f1f) - ios Version 9.1 (Build 13B143)

2016-04-01T19:40:49.408Z - info: Updating existing device: Apple-Iphone6-1 (71212020-3711-4e83-8c26-eb77c3161f1f)

2016-04-01T19:40:49.601Z - debug: Device presented: Apple-IpadAir2-1 (781e75ab-492d-4c57-a9b5-e79b28f4dac4) - ios Version 9.1 (Build 13B143)

2016-04-01T19:40:49.602Z - info: Updating existing device: Apple-IpadAir2-1 (781e75ab-492d-4c57-a9b5-e79b28f4dac4)

2016-04-01T19:40:49.683Z - debug: Device presented: Apple-Iphone5-1 (77b52145-0791-400a-8350-26a1cbcd3861) - ios Version 9.1 (Build 13B143)

2016-04-01T19:40:49.865Z - debug: Device presented: Apple-Iphone5s-1 (607e847f-5349-4071-93a2-04e41c612560) - ios Version 9.1 (Build 13B143)

2016-04-01T19:40:49.866Z - info: All 4 ios devices are present

2016-04-01T19:40:49.873Z - info: Starting unit test run on 4 ios devices

2016-04-01T19:40:50.688Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-04-01T19:40:50.747Z - debug: Device presented: Apple-Iphone5-1 (77b52145-0791-400a-8350-26a1cbcd3861) - ios Version 9.1 (Build 13B143)

2016-04-01T19:40:50.748Z - info: Updating existing device: Apple-Iphone5-1 (77b52145-0791-400a-8350-26a1cbcd3861)

2016-04-01T19:40:50.887Z - debug: Device presented: Apple-Iphone5s-1 (607e847f-5349-4071-93a2-04e41c612560) - ios Version 9.1 (Build 13B143)

2016-04-01T19:40:50.888Z - info: Updating existing device: Apple-Iphone5s-1 (607e847f-5349-4071-93a2-04e41c612560)

2016-04-01T19:40:51.237Z - info: Running on ios test: 2. emits incomingConnectionState

2016-04-01T19:40:51.699Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-04-01T19:40:52.157Z - info: Running on ios test: 4. native server connections all up

2016-04-01T19:40:52.692Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-04-01T19:40:53.241Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-04-01T19:40:53.751Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-04-01T19:40:53.774Z - debug: Device presented: samsung-SM-N910C (765cd4a9-7485-46fa-8393-d69c2874b1f1) - android 5.1.1

2016-04-01T19:40:54.304Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-04-01T19:40:54.790Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-04-01T19:40:59.506Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-04-01T19:41:03.587Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-04-01T19:41:04.161Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-04-01T19:41:04.500Z - info: Running on ios test: 13. closeAll with promise

2016-04-01T19:41:04.907Z - info: Running on ios test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-04-01T19:41:05.307Z - info: Running on ios test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-04-01T19:41:05.693Z - info: Running on ios test: 16. enqueue and run in order

2016-04-01T19:41:06.400Z - info: Running on ios test: 17. enqueueAtTop and run backwards

2016-04-01T19:41:08.423Z - info: Running on ios test: 18. mix enqueue and enqueueAtTop

2016-04-01T19:41:09.118Z - info: Running on ios test: 19. queues handled independently

2016-04-01T19:41:09.533Z - info: Running on ios test: 20. basic

2016-04-01T19:41:09.966Z - info: Running on ios test: 21. another

2016-04-01T19:41:10.323Z - info: Running on ios test: 22. can pass data in setup

2016-04-01T19:41:10.676Z - info: Running on ios test: 23. #startListeningForAdvertisements should fail if start not called

2016-04-01T19:41:11.151Z - info: Running on ios test: 24. #startUpdateAdvertisingAndListening should fail if start not called

2016-04-01T19:41:11.562Z - info: Running on ios test: 25. should be able to call #stopListeningForAdvertisements many times

2016-04-01T19:41:12.032Z - info: Running on ios test: 26. should be able to call #startListeningForAdvertisements many times

2016-04-01T19:41:12.653Z - info: Running on ios test: 27. should be able to call #startUpdateAdvertisingAndListening many times

2016-04-01T19:41:13.456Z - debug: Device presented: motorola-Nexus 6 (cf33405a-2ef4-4396-9f46-faa1ca3328e4) - android 5.1.1

2016-04-01T19:41:13.457Z - info: All 4 android devices are present

2016-04-01T19:41:13.458Z - info: Disqualifying device with unsupported hardware: LGE-Nexus 5

2016-04-01T19:41:13.461Z - info: Starting unit test run on 3 android devices

2016-04-01T19:41:14.396Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-04-01T19:41:14.608Z - info: Socket to device LGE-Nexus 5 disconnected: transport close

2016-04-01T19:41:14.808Z - info: Running on android test: 2. emits incomingConnectionState

2016-04-01T19:41:15.278Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-04-01T19:41:15.352Z - info: Running on ios test: 28. should be able to call #stopAdvertisingAndListening many times

2016-04-01T19:41:15.815Z - info: Running on android test: 4. native server connections all up

2016-04-01T19:41:16.369Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-04-01T19:41:16.665Z - info: Running on ios test: 29. #start should fail if called twice in a row

2016-04-01T19:41:17.004Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-04-01T19:41:17.314Z - info: Running on ios test: 30. does not emit duplicate discoveryAdvertisingStateUpdate

2016-04-01T19:41:17.419Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-04-01T19:41:17.949Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-04-01T19:41:18.018Z - info: Running on ios test: 31. does not send duplicate availability changes

2016-04-01T19:41:18.688Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-04-01T19:41:21.373Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-04-01T19:41:23.933Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-04-01T19:41:25.786Z - info: Running on android test: 12. closeAll can close even when connections open

2016-04-01T19:41:26.795Z - info: Running on ios test: 32. can get the network status

2016-04-01T19:41:27.177Z - info: Running on android test: 13. closeAll with promise

2016-04-01T19:41:28.249Z - info: Running on android test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-04-01T19:41:30.451Z - info: Running on android test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-04-01T19:41:31.045Z - info: Running on android test: 16. enqueue and run in order

2016-04-01T19:41:36.060Z - info: Running on android test: 17. enqueueAtTop and run backwards

2016-04-01T19:41:41.477Z - info: Running on android test: 18. mix enqueue and enqueueAtTop

2016-04-01T19:41:45.833Z - info: Running on android test: 19. queues handled independently

2016-04-01T19:41:46.900Z - info: Running on android test: 20. basic

2016-04-01T19:41:47.392Z - info: Running on android test: 21. another

2016-04-01T19:41:47.799Z - info: Running on ios test: 33. wifi peer is marked unavailable if announcements stop

2016-04-01T19:41:47.865Z - info: Running on android test: 22. can pass data in setup

2016-04-01T19:41:48.296Z - info: Running on android test: 23. #startListeningForAdvertisements should fail if start not called

2016-04-01T19:41:48.723Z - info: Running on android test: 24. #startUpdateAdvertisingAndListening should fail if start not called

2016-04-01T19:41:49.147Z - info: Running on android test: 25. should be able to call #stopListeningForAdvertisements many times

2016-04-01T19:41:50.021Z - info: Running on android test: 26. should be able to call #startListeningForAdvertisements many times

2016-04-01T19:41:51.303Z - info: Running on android test: 27. should be able to call #startUpdateAdvertisingAndListening many times

2016-04-01T19:41:52.223Z - info: Running on android test: 28. should be able to call #stopAdvertisingAndListening many times

2016-04-01T19:41:52.722Z - info: Running on android test: 29. #start should fail if called twice in a row

2016-04-01T19:41:53.309Z - info: Running on android test: 30. does not emit duplicate discoveryAdvertisingStateUpdate

2016-04-01T19:41:54.404Z - info: Running on ios test: 34. Can call start/stopListeningForAdvertisements

2016-04-01T19:41:54.416Z - info: Running on android test: 31. does not send duplicate availability changes

2016-04-01T19:41:54.878Z - info: Running on android test: 32. can get the network status

2016-04-01T19:41:55.067Z - info: Running on ios test: 35. Calling startListeningForAdvertisements twice is NOT an error

2016-04-01T19:41:55.272Z - info: Running on android test: 33. wifi peer is marked unavailable if announcements stop

2016-04-01T19:41:58.350Z - info: Running on android test: 34. Can call start/stopListeningForAdvertisements

2016-04-01T19:42:00.660Z - info: Running on android test: 35. Calling startListeningForAdvertisements twice is NOT an error

2016-04-01T19:42:10.004Z - info: Running on android test: 36. Calling stopListeningForAdvertisements without calling start is NOT an error

2016-04-01T19:42:19.562Z - info: Running on android test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-04-01T19:42:56.357Z - info: Running on android test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-04-01T19:43:31.947Z - info: Running on android test: 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error

2016-04-01T19:43:34.700Z - info: Running on android test: 40. cannot call connect when start listening for advertisements is not active

2016-04-01T19:43:36.563Z - info: Running on android test: 41. peerAvailabilityChange is called

2016-04-01T19:43:40.001Z - info: Socket to device Apple-Iphone5-1 disconnected: ping timeout

2016-04-01T19:43:42.450Z - info: Running on android test: 42. Can connect to a remote peer

2016-04-01T19:43:58.134Z - debug: Device presented: Apple-Iphone5-1 (77b52145-0791-400a-8350-26a1cbcd3861) - ios Version 9.1 (Build 13B143)

2016-04-01T19:43:58.135Z - info: Updating existing device: Apple-Iphone5-1 (77b52145-0791-400a-8350-26a1cbcd3861)

2016-04-01T19:43:59.109Z - debug: Device presented: Apple-Iphone5-1 (77b52145-0791-400a-8350-26a1cbcd3861) - ios Version 9.1 (Build 13B143)

2016-04-01T19:43:59.112Z - info: Updating existing device: Apple-Iphone5-1 (77b52145-0791-400a-8350-26a1cbcd3861)

2016-04-01T19:43:59.928Z - info: Running on android test: 43. Get error when trying to double connect to a peer

2016-04-01T19:44:07.626Z - warn: Failed on android test: 43. Get error when trying to double connect to a peer

2016-04-01T19:44:07.628Z - info: Running on android test: 44. Connect port dies if not connected to in in time

2016-04-01T19:44:14.246Z - debug: Too many emit retries to device: Apple-Iphone5-1

2016-04-01T20:00:27.668Z - info: Socket to device Apple-Iphone6-1 disconnected: transport close

2016-04-01T20:00:27.675Z - info: Socket to device Apple-IpadAir2-1 disconnected: transport close

2016-04-01T20:00:27.706Z - info: Socket to device Apple-Iphone5s-1 disconnected: transport close

2016-04-01T20:00:27.735Z - info: Socket to device Apple-Iphone5-1 disconnected: transport close

2016-04-01T20:02:10.878Z - info: Socket to device LGE-LG-H815 disconnected: transport close

2016-04-01T20:04:24.361Z - info: Socket to device samsung-SM-N910C disconnected: transport close

2016-04-01T20:04:26.367Z - info: Socket to device motorola-Nexus 6 disconnected: transport close


 
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
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/64809936b717dd3_416_Notification_final_juhanak/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/64809936b717dd3_416_Notification_final_juhanak/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/64809936b717dd3_416_Notification_final_juhanak/iOS_Iphone5-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/64809936b717dd3_416_Notification_final_juhanak/iOS_Iphone6-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/64809936b717dd3_416_Notification_final_juhanak/iOS_server.md)


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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/64809936b717dd3_416_Notification_final_juhanak/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/64809936b717dd3_416_Notification_final_juhanak/thali07_LGE-LG-H815.md)

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
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/64809936b717dd3_416_Notification_final_juhanak/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/64809936b717dd3_416_Notification_final_juhanak/thali08_motorola-Nexus 6.md)





#### Test 64809936d936b9e Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-04-03T19:09:31.346Z - info: Require 3 ios devices

2016-04-03T19:09:31.366Z - info: Require 3 android devices

2016-04-03T19:09:31.425Z - info: listening on *:3000

2016-04-03T19:09:32.043Z - debug: Device presented: Apple-Iphone6-1 (09cac296-ea8d-47c3-aafb-b2ba98d948de) - ios Version 9.1 (Build 13B143)

2016-04-03T19:09:32.932Z - debug: Device presented: Apple-Iphone5-1 (7f465dac-b5fc-4fa0-aece-e506c38feb66) - ios Version 9.1 (Build 13B143)

2016-04-03T19:09:32.942Z - debug: Device presented: Apple-Iphone5s-1 (24de18a5-460b-493f-8720-a0ac5fddea1c) - ios Version 9.1 (Build 13B143)

2016-04-03T19:09:32.948Z - debug: Device presented: LGE-LG-H815 (2f8a51e9-a07c-475b-8011-89a76fff0dc0) - android 5.1

2016-04-03T19:09:33.012Z - debug: Device presented: Apple-Iphone6-1 (09cac296-ea8d-47c3-aafb-b2ba98d948de) - ios Version 9.1 (Build 13B143)

2016-04-03T19:09:33.013Z - info: Updating existing device: Apple-Iphone6-1 (09cac296-ea8d-47c3-aafb-b2ba98d948de)

2016-04-03T19:09:33.355Z - debug: Device presented: Apple-IpadAir2-1 (f6d73446-5000-4d78-b1ff-7f7cf59b2a18) - ios Version 9.1 (Build 13B143)

2016-04-03T19:09:33.356Z - info: All 4 ios devices are present

2016-04-03T19:09:33.363Z - info: Starting unit test run on 4 ios devices

2016-04-03T19:09:33.420Z - debug: Device presented: LGE-Nexus 5 (bd539f59-ac8b-46cd-a53f-d8a6e93d099d) - android 5.1.1

2016-04-03T19:09:33.977Z - debug: Device presented: LGE-LG-H815 (2f8a51e9-a07c-475b-8011-89a76fff0dc0) - android 5.1

2016-04-03T19:09:33.978Z - info: Updating existing device: LGE-LG-H815 (2f8a51e9-a07c-475b-8011-89a76fff0dc0)

2016-04-03T19:09:33.988Z - debug: Device presented: Apple-Iphone5s-1 (24de18a5-460b-493f-8720-a0ac5fddea1c) - ios Version 9.1 (Build 13B143)

2016-04-03T19:09:33.989Z - info: Updating existing device: Apple-Iphone5s-1 (24de18a5-460b-493f-8720-a0ac5fddea1c)

2016-04-03T19:09:34.231Z - debug: Device presented: Apple-IpadAir2-1 (f6d73446-5000-4d78-b1ff-7f7cf59b2a18) - ios Version 9.1 (Build 13B143)

2016-04-03T19:09:34.232Z - info: Updating existing device: Apple-IpadAir2-1 (f6d73446-5000-4d78-b1ff-7f7cf59b2a18)

2016-04-03T19:09:34.238Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-04-03T19:09:34.304Z - debug: Device presented: Apple-Iphone5-1 (7f465dac-b5fc-4fa0-aece-e506c38feb66) - ios Version 9.1 (Build 13B143)

2016-04-03T19:09:34.305Z - info: Updating existing device: Apple-Iphone5-1 (7f465dac-b5fc-4fa0-aece-e506c38feb66)

2016-04-03T19:09:34.404Z - debug: Device presented: LGE-Nexus 5 (bd539f59-ac8b-46cd-a53f-d8a6e93d099d) - android 5.1.1

2016-04-03T19:09:34.405Z - info: Updating existing device: LGE-Nexus 5 (bd539f59-ac8b-46cd-a53f-d8a6e93d099d)

2016-04-03T19:09:36.842Z - info: Running on ios test: 2. emits incomingConnectionState

2016-04-03T19:09:37.267Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-04-03T19:09:37.658Z - info: Running on ios test: 4. native server connections all up

2016-04-03T19:09:38.207Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-04-03T19:09:38.651Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-04-03T19:09:39.129Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-04-03T19:09:39.587Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-04-03T19:09:39.603Z - debug: Device presented: samsung-SM-N910C (64cf6f90-0e50-4195-8d73-a582cdace5da) - android 5.1.1

2016-04-03T19:09:40.061Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-04-03T19:09:45.001Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-04-03T19:09:46.271Z - debug: Device presented: motorola-Nexus 6 (230a951a-669e-416d-ac9a-09d6a8324c5e) - android 5.1.1

2016-04-03T19:09:46.272Z - info: All 4 android devices are present

2016-04-03T19:09:46.273Z - info: Disqualifying device with unsupported hardware: LGE-Nexus 5

2016-04-03T19:09:46.277Z - info: Starting unit test run on 3 android devices

2016-04-03T19:09:47.077Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-04-03T19:09:47.126Z - info: Socket to device LGE-Nexus 5 disconnected: transport close

2016-04-03T19:09:47.304Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-04-03T19:09:47.546Z - info: Running on android test: 2. emits incomingConnectionState

2016-04-03T19:09:48.082Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-04-03T19:09:48.495Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-04-03T19:09:48.741Z - info: Running on android test: 4. native server connections all up

2016-04-03T19:09:50.143Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-04-03T19:09:50.456Z - info: Running on ios test: 13. closeAll with promise

2016-04-03T19:09:51.053Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-04-03T19:09:51.162Z - info: Running on ios test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-04-03T19:09:52.941Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-04-03T19:09:55.162Z - info: Running on ios test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-04-03T19:09:55.452Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-04-03T19:09:57.198Z - info: Running on ios test: 16. enqueue and run in order

2016-04-03T19:09:59.209Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-04-03T19:10:00.358Z - info: Running on ios test: 17. enqueueAtTop and run backwards

2016-04-03T19:10:04.192Z - info: Running on ios test: 18. mix enqueue and enqueueAtTop

2016-04-03T19:10:05.471Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-04-03T19:10:08.691Z - info: Running on ios test: 19. queues handled independently

2016-04-03T19:10:27.897Z - info: Running on ios test: 20. basic

2016-04-03T19:10:35.661Z - info: Running on ios test: 21. another

2016-04-03T19:10:37.016Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-04-03T19:10:37.544Z - info: Running on android test: 12. closeAll can close even when connections open

2016-04-03T19:10:37.586Z - info: Running on ios test: 22. can pass data in setup

2016-04-03T19:10:38.215Z - info: Running on android test: 13. closeAll with promise

2016-04-03T19:10:38.758Z - info: Running on android test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-04-03T19:10:39.312Z - info: Running on android test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-04-03T19:10:39.875Z - info: Running on android test: 16. enqueue and run in order

2016-04-03T19:10:40.876Z - info: Running on android test: 17. enqueueAtTop and run backwards

2016-04-03T19:10:41.269Z - info: Running on android test: 18. mix enqueue and enqueueAtTop

2016-04-03T19:10:41.349Z - info: Running on ios test: 23. #startListeningForAdvertisements should fail if start not called

2016-04-03T19:10:41.734Z - info: Running on ios test: 24. #startUpdateAdvertisingAndListening should fail if start not called

2016-04-03T19:10:41.842Z - info: Running on android test: 19. queues handled independently

2016-04-03T19:10:42.023Z - info: Running on ios test: 25. should be able to call #stopListeningForAdvertisements many times

2016-04-03T19:10:42.263Z - info: Running on android test: 20. basic

2016-04-03T19:10:42.636Z - info: Running on android test: 21. another

2016-04-03T19:10:42.646Z - info: Running on ios test: 26. should be able to call #startListeningForAdvertisements many times

2016-04-03T19:10:42.938Z - info: Running on android test: 22. can pass data in setup

2016-04-03T19:10:43.363Z - info: Running on android test: 23. #startListeningForAdvertisements should fail if start not called

2016-04-03T19:10:43.683Z - info: Running on ios test: 27. should be able to call #startUpdateAdvertisingAndListening many times

2016-04-03T19:10:43.755Z - info: Running on android test: 24. #startUpdateAdvertisingAndListening should fail if start not called

2016-04-03T19:10:44.121Z - info: Running on android test: 25. should be able to call #stopListeningForAdvertisements many times

2016-04-03T19:10:44.403Z - info: Running on ios test: 28. should be able to call #stopAdvertisingAndListening many times

2016-04-03T19:10:44.597Z - info: Running on android test: 26. should be able to call #startListeningForAdvertisements many times

2016-04-03T19:10:45.156Z - info: Running on ios test: 29. #start should fail if called twice in a row

2016-04-03T19:10:45.401Z - info: Running on android test: 27. should be able to call #startUpdateAdvertisingAndListening many times

2016-04-03T19:10:46.243Z - info: Running on ios test: 30. does not emit duplicate discoveryAdvertisingStateUpdate

2016-04-03T19:10:46.594Z - info: Running on android test: 28. should be able to call #stopAdvertisingAndListening many times

2016-04-03T19:10:47.145Z - info: Running on android test: 29. #start should fail if called twice in a row

2016-04-03T19:10:47.337Z - info: Running on ios test: 31. does not send duplicate availability changes

2016-04-03T19:10:47.606Z - info: Running on android test: 30. does not emit duplicate discoveryAdvertisingStateUpdate

2016-04-03T19:10:48.217Z - info: Running on ios test: 32. can get the network status

2016-04-03T19:10:51.501Z - info: Running on android test: 31. does not send duplicate availability changes

2016-04-03T19:11:28.025Z - info: Running on android test: 32. can get the network status

2016-04-03T19:11:28.913Z - info: Running on android test: 33. wifi peer is marked unavailable if announcements stop

2016-04-03T19:11:31.464Z - info: Running on android test: 34. Can call start/stopListeningForAdvertisements

2016-04-03T19:11:32.142Z - info: Running on android test: 35. Calling startListeningForAdvertisements twice is NOT an error

2016-04-03T19:11:32.798Z - info: Running on android test: 36. Calling stopListeningForAdvertisements without calling start is NOT an error

2016-04-03T19:11:33.219Z - info: Running on android test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-04-03T19:11:33.860Z - info: Running on android test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-04-03T19:11:34.584Z - info: Running on android test: 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error

2016-04-03T19:11:34.909Z - info: Running on android test: 40. cannot call connect when start listening for advertisements is not active

2016-04-03T19:11:35.306Z - info: Running on android test: 41. peerAvailabilityChange is called

2016-04-03T19:11:37.113Z - info: Running on android test: 42. Can connect to a remote peer

2016-04-03T19:11:43.666Z - info: Running on ios test: 33. wifi peer is marked unavailable if announcements stop

2016-04-03T19:11:48.283Z - info: Running on android test: 43. Get error when trying to double connect to a peer

2016-04-03T19:11:48.643Z - info: Running on ios test: 34. Can call start/stopListeningForAdvertisements

2016-04-03T19:11:49.286Z - info: Running on ios test: 35. Calling startListeningForAdvertisements twice is NOT an error

2016-04-03T19:11:49.890Z - info: Running on ios test: 36. Calling stopListeningForAdvertisements without calling start is NOT an error

2016-04-03T19:11:56.678Z - warn: Failed on android test: 43. Get error when trying to double connect to a peer

2016-04-03T19:11:56.679Z - info: Running on android test: 44. Connect port dies if not connected to in in time

2016-04-03T19:12:19.852Z - info: Running on ios test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-04-03T19:12:51.158Z - info: Running on ios test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-04-03T19:13:47.363Z - info: Running on ios test: 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error

2016-04-03T19:13:48.011Z - info: Running on ios test: 40. cannot call connect when start listening for advertisements is not active

2016-04-03T19:14:32.187Z - warn: Failed on ios test: 40. cannot call connect when start listening for advertisements is not active

2016-04-03T19:14:32.188Z - info: Running on ios test: 41. peerAvailabilityChange is called

2016-04-03T19:14:34.862Z - info: Running on ios test: 42. Can connect to a remote peer

2016-04-03T19:16:43.560Z - warn: Failed on ios test: 42. Can connect to a remote peer

2016-04-03T19:16:43.561Z - info: Running on ios test: 43. Get error when trying to double connect to a peer

2016-04-03T19:29:07.987Z - info: Socket to device Apple-IpadAir2-1 disconnected: transport close

2016-04-03T19:29:08.057Z - info: Socket to device Apple-Iphone6-1 disconnected: transport close

2016-04-03T19:29:08.065Z - info: Socket to device Apple-Iphone5s-1 disconnected: transport close

2016-04-03T19:29:08.077Z - info: Socket to device Apple-Iphone5-1 disconnected: transport close

2016-04-03T19:30:44.302Z - info: Socket to device LGE-LG-H815 disconnected: transport close

2016-04-03T19:32:58.280Z - info: Socket to device samsung-SM-N910C disconnected: transport close

2016-04-03T19:33:00.189Z - info: Socket to device motorola-Nexus 6 disconnected: transport close


 
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
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/64809936d936b9e_416_Notification_final_juhanak/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/64809936d936b9e_416_Notification_final_juhanak/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/64809936d936b9e_416_Notification_final_juhanak/iOS_Iphone5-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/64809936d936b9e_416_Notification_final_juhanak/iOS_Iphone6-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/64809936d936b9e_416_Notification_final_juhanak/iOS_server.md)


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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/64809936d936b9e_416_Notification_final_juhanak/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/64809936d936b9e_416_Notification_final_juhanak/thali07_LGE-LG-H815.md)

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
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/64809936d936b9e_416_Notification_final_juhanak/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/64809936d936b9e_416_Notification_final_juhanak/thali08_motorola-Nexus 6.md)





#### Test 6480993629f6128 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-04-01T21:49:46.710Z - info: Require 3 ios devices

2016-04-01T21:49:46.729Z - info: Require 3 android devices

2016-04-01T21:49:46.788Z - info: listening on *:3000

2016-04-01T21:49:47.321Z - debug: Device presented: LGE-LG-H815 (c539655c-4144-4be4-989c-1535e82c6b4e) - android 5.1

2016-04-01T21:49:47.877Z - debug: Device presented: Apple-IpadAir2-1 (3559cc27-6402-432b-bcfd-c285802596a6) - ios Version 9.1 (Build 13B143)

2016-04-01T21:49:48.246Z - debug: Device presented: LGE-LG-H815 (c539655c-4144-4be4-989c-1535e82c6b4e) - android 5.1

2016-04-01T21:49:48.248Z - info: Updating existing device: LGE-LG-H815 (c539655c-4144-4be4-989c-1535e82c6b4e)

2016-04-01T21:49:48.862Z - debug: Device presented: Apple-Iphone5s-1 (7299c1cd-4325-4a34-90c1-c1db833eeee1) - ios Version 9.1 (Build 13B143)

2016-04-01T21:49:48.871Z - debug: Device presented: Apple-IpadAir2-1 (3559cc27-6402-432b-bcfd-c285802596a6) - ios Version 9.1 (Build 13B143)

2016-04-01T21:49:48.873Z - info: Updating existing device: Apple-IpadAir2-1 (3559cc27-6402-432b-bcfd-c285802596a6)

2016-04-01T21:49:48.894Z - debug: Device presented: LGE-Nexus 5 (1bda5118-afe3-4207-99d9-59db7e66f01d) - android 5.1.1

2016-04-01T21:49:49.697Z - debug: Device presented: samsung-SM-N910C (f9fa5ce7-71af-4f49-94eb-4c284641b3ec) - android 5.1.1

2016-04-01T21:49:49.866Z - debug: Device presented: Apple-Iphone5s-1 (7299c1cd-4325-4a34-90c1-c1db833eeee1) - ios Version 9.1 (Build 13B143)

2016-04-01T21:49:49.867Z - info: Updating existing device: Apple-Iphone5s-1 (7299c1cd-4325-4a34-90c1-c1db833eeee1)

2016-04-01T21:49:49.967Z - debug: Device presented: LGE-Nexus 5 (1bda5118-afe3-4207-99d9-59db7e66f01d) - android 5.1.1

2016-04-01T21:49:49.968Z - info: Updating existing device: LGE-Nexus 5 (1bda5118-afe3-4207-99d9-59db7e66f01d)

2016-04-01T21:49:50.703Z - debug: Device presented: Apple-Iphone5-1 (c7e38397-c90d-4e48-845d-977d1574ba6e) - ios Version 9.1 (Build 13B143)

2016-04-01T21:49:50.919Z - debug: Device presented: Apple-Iphone6-1 (8f481545-2d3c-4c34-90c0-6602bf93a785) - ios Version 9.1 (Build 13B143)

2016-04-01T21:49:50.920Z - info: All 4 ios devices are present

2016-04-01T21:49:50.927Z - info: Starting unit test run on 4 ios devices

2016-04-01T21:49:51.871Z - debug: Device presented: Apple-Iphone5-1 (c7e38397-c90d-4e48-845d-977d1574ba6e) - ios Version 9.1 (Build 13B143)

2016-04-01T21:49:51.875Z - info: Updating existing device: Apple-Iphone5-1 (c7e38397-c90d-4e48-845d-977d1574ba6e)

2016-04-01T21:49:51.923Z - debug: Device presented: Apple-Iphone6-1 (8f481545-2d3c-4c34-90c0-6602bf93a785) - ios Version 9.1 (Build 13B143)

2016-04-01T21:49:51.924Z - info: Updating existing device: Apple-Iphone6-1 (8f481545-2d3c-4c34-90c0-6602bf93a785)

2016-04-01T21:49:53.377Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-04-01T21:49:53.831Z - info: Running on ios test: 2. emits incomingConnectionState

2016-04-01T21:49:54.205Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-04-01T21:49:54.639Z - info: Running on ios test: 4. native server connections all up

2016-04-01T21:49:55.105Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-04-01T21:49:55.534Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-04-01T21:49:55.979Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-04-01T21:49:56.370Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-04-01T21:49:56.795Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-04-01T21:49:59.114Z - debug: Device presented: motorola-Nexus 6 (0a23d640-682e-4dc8-9eae-c6d4d2cb3384) - android 5.1.1

2016-04-01T21:49:59.115Z - info: All 4 android devices are present

2016-04-01T21:49:59.116Z - info: Disqualifying device with unsupported hardware: LGE-Nexus 5

2016-04-01T21:49:59.126Z - info: Starting unit test run on 3 android devices

2016-04-01T21:49:59.881Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-04-01T21:49:59.984Z - info: Socket to device LGE-Nexus 5 disconnected: transport close

2016-04-01T21:50:00.005Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-04-01T21:50:00.419Z - info: Running on android test: 2. emits incomingConnectionState

2016-04-01T21:50:00.835Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-04-01T21:50:01.170Z - info: Running on android test: 4. native server connections all up

2016-04-01T21:50:01.629Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-04-01T21:50:01.968Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-04-01T21:50:01.997Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-04-01T21:50:02.466Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-04-01T21:50:02.895Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-04-01T21:50:03.169Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-04-01T21:50:03.260Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-04-01T21:50:03.493Z - info: Running on ios test: 13. closeAll with promise

2016-04-01T21:50:03.834Z - info: Running on ios test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-04-01T21:50:04.781Z - info: Running on ios test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-04-01T21:50:04.796Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-04-01T21:50:05.167Z - info: Running on ios test: 16. enqueue and run in order

2016-04-01T21:50:05.308Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-04-01T21:50:05.693Z - info: Running on android test: 12. closeAll can close even when connections open

2016-04-01T21:50:05.859Z - info: Running on ios test: 17. enqueueAtTop and run backwards

2016-04-01T21:50:06.035Z - info: Running on android test: 13. closeAll with promise

2016-04-01T21:50:06.160Z - info: Running on ios test: 18. mix enqueue and enqueueAtTop

2016-04-01T21:50:06.323Z - info: Running on android test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-04-01T21:50:06.576Z - info: Running on ios test: 19. queues handled independently

2016-04-01T21:50:06.677Z - info: Running on android test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-04-01T21:50:06.879Z - info: Running on ios test: 20. basic

2016-04-01T21:50:07.083Z - info: Running on android test: 16. enqueue and run in order

2016-04-01T21:50:07.246Z - info: Running on ios test: 21. another

2016-04-01T21:50:07.571Z - info: Running on ios test: 22. can pass data in setup

2016-04-01T21:50:07.864Z - info: Running on android test: 17. enqueueAtTop and run backwards

2016-04-01T21:50:07.987Z - info: Running on ios test: 23. #startListeningForAdvertisements should fail if start not called

2016-04-01T21:50:08.214Z - info: Running on android test: 18. mix enqueue and enqueueAtTop

2016-04-01T21:50:08.318Z - info: Running on ios test: 24. #startUpdateAdvertisingAndListening should fail if start not called

2016-04-01T21:50:08.673Z - info: Running on android test: 19. queues handled independently

2016-04-01T21:50:09.086Z - info: Running on android test: 20. basic

2016-04-01T21:50:09.404Z - info: Running on android test: 21. another

2016-04-01T21:50:09.742Z - info: Running on android test: 22. can pass data in setup

2016-04-01T21:50:10.062Z - info: Running on android test: 23. #startListeningForAdvertisements should fail if start not called

2016-04-01T21:50:10.444Z - info: Running on android test: 24. #startUpdateAdvertisingAndListening should fail if start not called

2016-04-01T21:50:10.838Z - info: Running on android test: 25. should be able to call #stopListeningForAdvertisements many times

2016-04-01T21:50:11.292Z - info: Running on android test: 26. should be able to call #startListeningForAdvertisements many times

2016-04-01T21:50:11.928Z - info: Running on android test: 27. should be able to call #startUpdateAdvertisingAndListening many times

2016-04-01T21:50:14.154Z - info: Running on android test: 28. should be able to call #stopAdvertisingAndListening many times

2016-04-01T21:50:14.486Z - info: Running on android test: 29. #start should fail if called twice in a row

2016-04-01T21:50:14.811Z - info: Running on android test: 30. does not emit duplicate discoveryAdvertisingStateUpdate

2016-04-01T21:50:15.759Z - info: Running on ios test: 25. should be able to call #stopListeningForAdvertisements many times

2016-04-01T21:50:17.274Z - info: Running on android test: 31. does not send duplicate availability changes

2016-04-01T21:50:18.306Z - info: Running on android test: 32. can get the network status

2016-04-01T21:50:18.397Z - info: Running on ios test: 26. should be able to call #startListeningForAdvertisements many times

2016-04-01T21:50:19.321Z - info: Running on android test: 33. wifi peer is marked unavailable if announcements stop

2016-04-01T21:50:19.517Z - info: Running on ios test: 27. should be able to call #startUpdateAdvertisingAndListening many times

2016-04-01T21:50:22.985Z - info: Running on android test: 34. Can call start/stopListeningForAdvertisements

2016-04-01T21:50:25.577Z - info: Running on android test: 35. Calling startListeningForAdvertisements twice is NOT an error

2016-04-01T21:50:31.952Z - info: Running on android test: 36. Calling stopListeningForAdvertisements without calling start is NOT an error

2016-04-01T21:50:32.383Z - info: Running on android test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-04-01T21:50:33.278Z - info: Running on android test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-04-01T21:50:34.295Z - info: Running on android test: 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error

2016-04-01T21:50:34.896Z - info: Running on android test: 40. cannot call connect when start listening for advertisements is not active

2016-04-01T21:50:35.339Z - info: Running on android test: 41. peerAvailabilityChange is called

2016-04-01T21:50:39.549Z - info: Running on android test: 42. Can connect to a remote peer

2016-04-01T21:50:40.131Z - info: Running on ios test: 28. should be able to call #stopAdvertisingAndListening many times

2016-04-01T21:50:56.552Z - info: Running on ios test: 29. #start should fail if called twice in a row

2016-04-01T21:50:57.513Z - info: Running on ios test: 30. does not emit duplicate discoveryAdvertisingStateUpdate

2016-04-01T21:50:58.257Z - info: Running on ios test: 31. does not send duplicate availability changes

2016-04-01T21:51:01.943Z - info: Running on ios test: 32. can get the network status

2016-04-01T21:51:24.925Z - info: Running on ios test: 33. wifi peer is marked unavailable if announcements stop

2016-04-01T21:51:25.644Z - info: Running on android test: 43. Get error when trying to double connect to a peer

2016-04-01T21:51:27.479Z - info: Running on ios test: 34. Can call start/stopListeningForAdvertisements

2016-04-01T21:51:28.058Z - info: Running on ios test: 35. Calling startListeningForAdvertisements twice is NOT an error

2016-04-01T21:51:28.759Z - info: Running on ios test: 36. Calling stopListeningForAdvertisements without calling start is NOT an error

2016-04-01T21:51:31.895Z - warn: Failed on android test: 43. Get error when trying to double connect to a peer

2016-04-01T21:51:31.896Z - info: Running on android test: 44. Connect port dies if not connected to in in time

2016-04-01T21:51:52.050Z - info: Running on ios test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-04-01T21:51:52.738Z - info: Running on ios test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-04-01T21:51:53.791Z - info: Running on ios test: 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error

2016-04-01T21:51:56.445Z - info: Running on ios test: 40. cannot call connect when start listening for advertisements is not active

2016-04-01T21:51:57.774Z - warn: Failed on ios test: 40. cannot call connect when start listening for advertisements is not active

2016-04-01T21:51:57.775Z - info: Running on ios test: 41. peerAvailabilityChange is called

2016-04-01T21:52:15.073Z - info: Running on ios test: 42. Can connect to a remote peer

2016-04-01T21:53:34.405Z - warn: Failed on ios test: 42. Can connect to a remote peer

2016-04-01T21:53:34.406Z - info: Running on ios test: 43. Get error when trying to double connect to a peer

2016-04-01T22:09:13.101Z - info: Socket to device Apple-IpadAir2-1 disconnected: transport close

2016-04-01T22:09:13.122Z - info: Socket to device Apple-Iphone5-1 disconnected: transport close

2016-04-01T22:09:13.130Z - info: Socket to device Apple-Iphone6-1 disconnected: transport close

2016-04-01T22:09:19.238Z - info: Socket to device Apple-Iphone5s-1 disconnected: transport close

2016-04-01T22:10:49.893Z - info: Socket to device LGE-LG-H815 disconnected: transport close

2016-04-01T22:13:09.963Z - info: Socket to device samsung-SM-N910C disconnected: transport close

2016-04-01T22:13:11.678Z - info: Socket to device motorola-Nexus 6 disconnected: transport close


 
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
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/6480993629f6128_416_Notification_final_juhanak/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/6480993629f6128_416_Notification_final_juhanak/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/6480993629f6128_416_Notification_final_juhanak/iOS_Iphone5-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/6480993629f6128_416_Notification_final_juhanak/iOS_Iphone6-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/6480993629f6128_416_Notification_final_juhanak/iOS_server.md)


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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/6480993629f6128_416_Notification_final_juhanak/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/6480993629f6128_416_Notification_final_juhanak/thali07_LGE-LG-H815.md)

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
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/6480993629f6128_416_Notification_final_juhanak/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/6480993629f6128_416_Notification_final_juhanak/thali08_motorola-Nexus 6.md)





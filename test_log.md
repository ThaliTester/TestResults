#### Test 657450204f13c43 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-04-08T07:32:07.089Z - info: Require 3 ios devices

2016-04-08T07:32:07.107Z - info: Require 3 android devices

2016-04-08T07:32:07.167Z - info: listening on *:3000

2016-04-08T07:32:07.682Z - debug: Device presented: Apple-Iphone5-1 (e825a612-6c5c-4d54-afc9-816449e93798) - ios Version 9.1 (Build 13B143)

2016-04-08T07:32:07.725Z - debug: Device presented: Apple-Iphone6-1 (6bac6588-a6e4-44a8-b2ac-e4b77439f88c) - ios Version 9.1 (Build 13B143)

2016-04-08T07:32:08.533Z - debug: Device presented: LGE-LG-H815 (70a49e30-0ae6-4353-a058-5cc45e9b15fd) - android 5.1

2016-04-08T07:32:08.608Z - debug: Device presented: Apple-Iphone5s-1 (981e6d0f-5d06-4f4c-bdce-22c4d8fdd816) - ios Version 9.1 (Build 13B143)

2016-04-08T07:32:08.615Z - debug: Device presented: Apple-Iphone5-1 (e825a612-6c5c-4d54-afc9-816449e93798) - ios Version 9.1 (Build 13B143)

2016-04-08T07:32:08.616Z - info: Updating existing device: Apple-Iphone5-1 (e825a612-6c5c-4d54-afc9-816449e93798)

2016-04-08T07:32:08.717Z - debug: Device presented: Apple-Iphone6-1 (6bac6588-a6e4-44a8-b2ac-e4b77439f88c) - ios Version 9.1 (Build 13B143)

2016-04-08T07:32:08.718Z - info: Updating existing device: Apple-Iphone6-1 (6bac6588-a6e4-44a8-b2ac-e4b77439f88c)

2016-04-08T07:32:09.050Z - debug: Device presented: Apple-IpadAir2-1 (281113d3-0e97-4786-a620-6936cd6b2a37) - ios Version 9.1 (Build 13B143)

2016-04-08T07:32:09.051Z - info: All 4 ios devices are present

2016-04-08T07:32:09.059Z - info: Starting unit test run on 4 ios devices

2016-04-08T07:32:09.500Z - debug: Device presented: LGE-LG-H815 (70a49e30-0ae6-4353-a058-5cc45e9b15fd) - android 5.1

2016-04-08T07:32:09.501Z - info: Updating existing device: LGE-LG-H815 (70a49e30-0ae6-4353-a058-5cc45e9b15fd)

2016-04-08T07:32:09.619Z - debug: Device presented: Apple-Iphone5s-1 (981e6d0f-5d06-4f4c-bdce-22c4d8fdd816) - ios Version 9.1 (Build 13B143)

2016-04-08T07:32:09.621Z - info: Updating existing device: Apple-Iphone5s-1 (981e6d0f-5d06-4f4c-bdce-22c4d8fdd816)

2016-04-08T07:32:09.652Z - debug: Device presented: LGE-Nexus 5 (70a8a9ef-425f-4de3-9b44-14b6ac948ca5) - android 5.1.1

2016-04-08T07:32:10.080Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-04-08T07:32:10.168Z - debug: Device presented: Apple-IpadAir2-1 (281113d3-0e97-4786-a620-6936cd6b2a37) - ios Version 9.1 (Build 13B143)

2016-04-08T07:32:10.169Z - info: Updating existing device: Apple-IpadAir2-1 (281113d3-0e97-4786-a620-6936cd6b2a37)

2016-04-08T07:32:10.558Z - info: Running on ios test: 2. emits incomingConnectionState

2016-04-08T07:32:10.705Z - debug: Device presented: LGE-Nexus 5 (70a8a9ef-425f-4de3-9b44-14b6ac948ca5) - android 5.1.1

2016-04-08T07:32:10.706Z - info: Updating existing device: LGE-Nexus 5 (70a8a9ef-425f-4de3-9b44-14b6ac948ca5)

2016-04-08T07:32:10.952Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-04-08T07:32:11.309Z - info: Running on ios test: 4. native server connections all up

2016-04-08T07:32:11.719Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-04-08T07:32:12.081Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-04-08T07:32:12.442Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-04-08T07:32:12.900Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-04-08T07:32:13.218Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-04-08T07:32:13.790Z - debug: Device presented: samsung-SM-N910C (47f6ff86-156b-4c9a-b87c-c5a4a8e9c524) - android 5.1.1

2016-04-08T07:32:16.780Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-04-08T07:32:17.311Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-04-08T07:32:17.654Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-04-08T07:32:18.061Z - info: Running on ios test: 13. closeAll with promise

2016-04-08T07:32:18.446Z - info: Running on ios test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-04-08T07:32:18.802Z - info: Running on ios test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-04-08T07:32:19.154Z - info: Running on ios test: 16. enqueue and run in order

2016-04-08T07:32:19.684Z - info: Running on ios test: 17. enqueueAtTop and run backwards

2016-04-08T07:32:19.962Z - info: Running on ios test: 18. mix enqueue and enqueueAtTop

2016-04-08T07:32:20.478Z - info: Running on ios test: 19. queues handled independently

2016-04-08T07:32:20.769Z - info: Running on ios test: 20. basic

2016-04-08T07:32:21.041Z - info: Running on ios test: 21. another

2016-04-08T07:32:21.323Z - debug: Device presented: motorola-Nexus 6 (eb58f9fb-2777-48f4-8610-9eab09970371) - android 5.1.1

2016-04-08T07:32:21.325Z - info: All 4 android devices are present

2016-04-08T07:32:21.326Z - info: Disqualifying device with unsupported hardware: LGE-Nexus 5

2016-04-08T07:32:21.329Z - info: Starting unit test run on 3 android devices

2016-04-08T07:32:21.491Z - info: Running on ios test: 22. can pass data in setup

2016-04-08T07:32:21.821Z - info: Running on ios test: 23. #startListeningForAdvertisements should fail if start not called

2016-04-08T07:32:22.058Z - info: Running on ios test: 24. #startUpdateAdvertisingAndListening should fail if start not called

2016-04-08T07:32:22.338Z - info: Socket to device LGE-Nexus 5 disconnected: transport close

2016-04-08T07:32:22.371Z - info: Running on ios test: 25. should be able to call #stopListeningForAdvertisements many times

2016-04-08T07:32:22.381Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-04-08T07:32:22.721Z - info: Running on android test: 2. emits incomingConnectionState

2016-04-08T07:32:22.755Z - info: Running on ios test: 26. should be able to call #startListeningForAdvertisements many times

2016-04-08T07:32:23.202Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-04-08T07:32:23.249Z - info: Running on ios test: 27. should be able to call #startUpdateAdvertisingAndListening many times

2016-04-08T07:32:23.558Z - info: Running on android test: 4. native server connections all up

2016-04-08T07:32:23.904Z - info: Running on ios test: 28. should be able to call #stopAdvertisingAndListening many times

2016-04-08T07:32:24.014Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-04-08T07:32:28.480Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-04-08T07:32:33.713Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-04-08T07:32:40.770Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-04-08T07:32:48.254Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-04-08T07:33:06.249Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-04-08T07:33:12.191Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-04-08T07:33:12.556Z - info: Running on android test: 12. closeAll can close even when connections open

2016-04-08T07:33:13.089Z - info: Running on android test: 13. closeAll with promise

2016-04-08T07:33:13.582Z - info: Running on android test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-04-08T07:33:13.979Z - info: Running on android test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-04-08T07:33:14.434Z - info: Running on android test: 16. enqueue and run in order

2016-04-08T07:33:15.161Z - info: Running on android test: 17. enqueueAtTop and run backwards

2016-04-08T07:33:16.168Z - info: Running on android test: 18. mix enqueue and enqueueAtTop

2016-04-08T07:33:16.564Z - info: Running on android test: 19. queues handled independently

2016-04-08T07:33:16.915Z - info: Running on android test: 20. basic

2016-04-08T07:33:17.252Z - info: Running on android test: 21. another

2016-04-08T07:33:17.609Z - info: Running on android test: 22. can pass data in setup

2016-04-08T07:33:17.978Z - info: Running on android test: 23. #startListeningForAdvertisements should fail if start not called

2016-04-08T07:33:18.317Z - info: Running on android test: 24. #startUpdateAdvertisingAndListening should fail if start not called

2016-04-08T07:33:18.631Z - info: Running on android test: 25. should be able to call #stopListeningForAdvertisements many times

2016-04-08T07:33:19.154Z - info: Running on android test: 26. should be able to call #startListeningForAdvertisements many times

2016-04-08T07:33:19.806Z - info: Running on android test: 27. should be able to call #startUpdateAdvertisingAndListening many times

2016-04-08T07:33:20.675Z - info: Running on android test: 28. should be able to call #stopAdvertisingAndListening many times

2016-04-08T07:33:21.049Z - info: Running on android test: 29. #start should fail if called twice in a row

2016-04-08T07:33:21.405Z - info: Running on android test: 30. does not emit duplicate discoveryAdvertisingStateUpdate

2016-04-08T07:33:22.164Z - info: Running on android test: 31. does not send duplicate availability changes

2016-04-08T07:33:22.560Z - info: Running on android test: 32. can get the network status

2016-04-08T07:33:22.858Z - info: Running on android test: 33. wifi peer is marked unavailable if announcements stop

2016-04-08T07:33:25.204Z - info: Running on android test: 34. Can call start/stopListeningForAdvertisements

2016-04-08T07:33:25.752Z - info: Running on android test: 35. Calling startListeningForAdvertisements twice is NOT an error

2016-04-08T07:33:26.336Z - info: Running on android test: 36. Calling stopListeningForAdvertisements without calling start is NOT an error

2016-04-08T07:33:26.512Z - info: Running on ios test: 29. #start should fail if called twice in a row

2016-04-08T07:33:26.688Z - info: Running on android test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-04-08T07:33:27.080Z - info: Running on ios test: 30. does not emit duplicate discoveryAdvertisingStateUpdate

2016-04-08T07:33:27.303Z - info: Running on android test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-04-08T07:33:27.626Z - info: Running on ios test: 31. does not send duplicate availability changes

2016-04-08T07:33:29.928Z - info: Running on android test: 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error

2016-04-08T07:33:33.453Z - info: Running on android test: 40. cannot call connect when start listening for advertisements is not active

2016-04-08T07:33:33.983Z - info: Running on android test: 41. peerAvailabilityChange is called

2016-04-08T07:33:36.047Z - info: Running on android test: 42. Can connect to a remote peer

2016-04-08T07:33:50.154Z - info: Running on ios test: 32. can get the network status

2016-04-08T07:33:50.675Z - info: Running on ios test: 33. wifi peer is marked unavailable if announcements stop

2016-04-08T07:33:53.088Z - info: Running on ios test: 34. Can call start/stopListeningForAdvertisements

2016-04-08T07:33:54.962Z - info: Running on android test: 43. Get error when trying to double connect to a peer

2016-04-08T07:34:01.956Z - info: Running on ios test: 35. Calling startListeningForAdvertisements twice is NOT an error

2016-04-08T07:34:12.571Z - warn: Failed on android test: 43. Get error when trying to double connect to a peer

2016-04-08T07:34:12.573Z - info: Running on android test: 44. Connect port dies if not connected to in in time

2016-04-08T07:34:51.123Z - info: Running on ios test: 36. Calling stopListeningForAdvertisements without calling start is NOT an error

2016-04-08T07:34:52.856Z - info: Running on ios test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-04-08T07:34:53.264Z - info: Running on ios test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-04-08T07:34:53.788Z - info: Running on ios test: 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error

2016-04-08T07:35:16.421Z - info: Running on ios test: 40. cannot call connect when start listening for advertisements is not active

2016-04-08T07:35:16.768Z - warn: Failed on ios test: 40. cannot call connect when start listening for advertisements is not active

2016-04-08T07:35:16.770Z - info: Running on ios test: 41. peerAvailabilityChange is called

2016-04-08T07:35:33.374Z - info: Running on ios test: 42. Can connect to a remote peer

2016-04-08T07:36:15.678Z - warn: Failed on ios test: 42. Can connect to a remote peer

2016-04-08T07:36:15.681Z - info: Running on ios test: 43. Get error when trying to double connect to a peer

2016-04-08T07:51:24.375Z - info: Socket to device Apple-Iphone5s-1 disconnected: transport close

2016-04-08T07:51:24.385Z - info: Socket to device Apple-Iphone6-1 disconnected: transport close

2016-04-08T07:51:24.399Z - info: Socket to device Apple-IpadAir2-1 disconnected: transport close

2016-04-08T07:51:24.419Z - info: Socket to device Apple-Iphone5-1 disconnected: transport close

2016-04-08T07:53:02.082Z - info: Socket to device LGE-LG-H815 disconnected: transport close

2016-04-08T07:55:32.679Z - info: Socket to device samsung-SM-N910C disconnected: transport close

2016-04-08T07:55:34.619Z - info: Socket to device motorola-Nexus 6 disconnected: transport close


 
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
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/657450204f13c43_Change_gradle_download_URL_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/657450204f13c43_Change_gradle_download_URL_vjrantal/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/657450204f13c43_Change_gradle_download_URL_vjrantal/iOS_Iphone5-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/657450204f13c43_Change_gradle_download_URL_vjrantal/iOS_Iphone6-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/657450204f13c43_Change_gradle_download_URL_vjrantal/iOS_server.md)


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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/657450204f13c43_Change_gradle_download_URL_vjrantal/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/657450204f13c43_Change_gradle_download_URL_vjrantal/thali07_LGE-LG-H815.md)

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
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/657450204f13c43_Change_gradle_download_URL_vjrantal/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/657450204f13c43_Change_gradle_download_URL_vjrantal/thali08_motorola-Nexus 6.md)





#### Test 65745020fc66909 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-04-08T08:11:18.394Z - info: Require 3 ios devices

2016-04-08T08:11:18.414Z - info: Require 3 android devices

2016-04-08T08:11:18.479Z - info: listening on *:3000

2016-04-08T08:11:20.514Z - debug: Device presented: LGE-LG-H815 (3a75deb5-321d-4475-ae1f-87651179cf71) - android 5.1

2016-04-08T08:11:20.586Z - debug: Device presented: Apple-Iphone6-1 (954a9fdb-faef-45fa-8c4a-e2bfb48a901a) - ios Version 9.1 (Build 13B143)

2016-04-08T08:11:21.194Z - debug: Device presented: Apple-IpadAir2-1 (310bd762-5c41-4013-ba98-1cdb5e69f42c) - ios Version 9.1 (Build 13B143)

2016-04-08T08:11:21.383Z - debug: Device presented: LGE-LG-H815 (3a75deb5-321d-4475-ae1f-87651179cf71) - android 5.1

2016-04-08T08:11:21.384Z - info: Updating existing device: LGE-LG-H815 (3a75deb5-321d-4475-ae1f-87651179cf71)

2016-04-08T08:11:21.559Z - debug: Device presented: Apple-Iphone6-1 (954a9fdb-faef-45fa-8c4a-e2bfb48a901a) - ios Version 9.1 (Build 13B143)

2016-04-08T08:11:21.561Z - info: Updating existing device: Apple-Iphone6-1 (954a9fdb-faef-45fa-8c4a-e2bfb48a901a)

2016-04-08T08:11:22.258Z - debug: Device presented: Apple-IpadAir2-1 (310bd762-5c41-4013-ba98-1cdb5e69f42c) - ios Version 9.1 (Build 13B143)

2016-04-08T08:11:22.259Z - info: Updating existing device: Apple-IpadAir2-1 (310bd762-5c41-4013-ba98-1cdb5e69f42c)

2016-04-08T08:11:23.293Z - debug: Device presented: LGE-Nexus 5 (902b4af0-a7e0-48b3-aed6-9f08444ee33d) - android 5.1.1

2016-04-08T08:11:23.307Z - debug: Device presented: Apple-Iphone5-1 (11a5596c-0abf-49aa-b899-484cc8fc4f8f) - ios Version 9.1 (Build 13B143)

2016-04-08T08:11:23.421Z - debug: Device presented: Apple-Iphone5s-1 (81db905b-3019-4407-af41-b12970730dfa) - ios Version 9.1 (Build 13B143)

2016-04-08T08:11:23.422Z - info: All 4 ios devices are present

2016-04-08T08:11:23.430Z - info: Starting unit test run on 4 ios devices

2016-04-08T08:11:24.192Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-04-08T08:11:24.319Z - debug: Device presented: LGE-Nexus 5 (902b4af0-a7e0-48b3-aed6-9f08444ee33d) - android 5.1.1

2016-04-08T08:11:24.320Z - info: Updating existing device: LGE-Nexus 5 (902b4af0-a7e0-48b3-aed6-9f08444ee33d)

2016-04-08T08:11:24.539Z - debug: Device presented: Apple-Iphone5-1 (11a5596c-0abf-49aa-b899-484cc8fc4f8f) - ios Version 9.1 (Build 13B143)

2016-04-08T08:11:24.540Z - info: Updating existing device: Apple-Iphone5-1 (11a5596c-0abf-49aa-b899-484cc8fc4f8f)

2016-04-08T08:11:24.577Z - debug: Device presented: Apple-Iphone5s-1 (81db905b-3019-4407-af41-b12970730dfa) - ios Version 9.1 (Build 13B143)

2016-04-08T08:11:24.579Z - info: Updating existing device: Apple-Iphone5s-1 (81db905b-3019-4407-af41-b12970730dfa)

2016-04-08T08:11:24.889Z - debug: Device presented: samsung-SM-N910C (d4120d53-e0b3-4f70-a212-93f54908c875) - android 5.1.1

2016-04-08T08:11:24.894Z - info: Running on ios test: 2. emits incomingConnectionState

2016-04-08T08:11:25.235Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-04-08T08:11:25.676Z - info: Running on ios test: 4. native server connections all up

2016-04-08T08:11:26.236Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-04-08T08:11:26.672Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-04-08T08:11:27.194Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-04-08T08:11:27.571Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-04-08T08:11:28.151Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-04-08T08:11:31.842Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-04-08T08:11:32.551Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-04-08T08:11:32.933Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-04-08T08:11:33.331Z - info: Running on ios test: 13. closeAll with promise

2016-04-08T08:11:33.800Z - info: Running on ios test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-04-08T08:11:34.182Z - info: Running on ios test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-04-08T08:11:34.564Z - info: Running on ios test: 16. enqueue and run in order

2016-04-08T08:11:35.154Z - info: Running on ios test: 17. enqueueAtTop and run backwards

2016-04-08T08:11:35.185Z - debug: Device presented: motorola-Nexus 6 (9b1eb508-6ace-4d88-a795-369611cc0eee) - android 5.1.1

2016-04-08T08:11:35.187Z - info: All 4 android devices are present

2016-04-08T08:11:35.189Z - info: Disqualifying device with unsupported hardware: LGE-Nexus 5

2016-04-08T08:11:35.192Z - info: Starting unit test run on 3 android devices

2016-04-08T08:11:35.453Z - info: Running on ios test: 18. mix enqueue and enqueueAtTop

2016-04-08T08:11:35.845Z - info: Running on ios test: 19. queues handled independently

2016-04-08T08:11:35.973Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-04-08T08:11:36.267Z - info: Running on ios test: 20. basic

2016-04-08T08:11:36.332Z - info: Socket to device LGE-Nexus 5 disconnected: transport close

2016-04-08T08:11:36.589Z - info: Running on android test: 2. emits incomingConnectionState

2016-04-08T08:11:36.734Z - info: Running on ios test: 21. another

2016-04-08T08:11:36.952Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-04-08T08:11:37.033Z - info: Running on ios test: 22. can pass data in setup

2016-04-08T08:11:37.840Z - info: Running on android test: 4. native server connections all up

2016-04-08T08:11:38.287Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-04-08T08:11:39.672Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-04-08T08:11:40.939Z - info: Running on ios test: 23. #startListeningForAdvertisements should fail if start not called

2016-04-08T08:11:41.222Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-04-08T08:11:42.820Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-04-08T08:11:44.401Z - info: Running on ios test: 24. #startUpdateAdvertisingAndListening should fail if start not called

2016-04-08T08:11:45.218Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-04-08T08:11:48.000Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-04-08T08:11:49.467Z - info: Running on ios test: 25. should be able to call #stopListeningForAdvertisements many times

2016-04-08T08:11:51.447Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-04-08T08:11:52.113Z - info: Running on ios test: 26. should be able to call #startListeningForAdvertisements many times

2016-04-08T08:11:59.219Z - info: Running on android test: 12. closeAll can close even when connections open

2016-04-08T08:12:36.670Z - info: Running on ios test: 27. should be able to call #startUpdateAdvertisingAndListening many times

2016-04-08T08:12:47.800Z - info: Running on android test: 13. closeAll with promise

2016-04-08T08:12:50.795Z - info: Running on android test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-04-08T08:12:51.440Z - info: Running on android test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-04-08T08:12:57.814Z - info: Running on android test: 16. enqueue and run in order

2016-04-08T08:14:26.292Z - info: Running on ios test: 28. should be able to call #stopAdvertisingAndListening many times

2016-04-08T08:14:28.483Z - info: Running on ios test: 29. #start should fail if called twice in a row

2016-04-08T08:14:28.933Z - info: Running on ios test: 30. does not emit duplicate discoveryAdvertisingStateUpdate

2016-04-08T08:15:01.131Z - info: Running on android test: 17. enqueueAtTop and run backwards

2016-04-08T08:15:01.546Z - info: Running on android test: 18. mix enqueue and enqueueAtTop

2016-04-08T08:15:02.108Z - info: Running on android test: 19. queues handled independently

2016-04-08T08:15:02.512Z - info: Running on android test: 20. basic

2016-04-08T08:15:02.875Z - info: Running on android test: 21. another

2016-04-08T08:15:03.172Z - info: Running on android test: 22. can pass data in setup

2016-04-08T08:15:03.520Z - info: Running on android test: 23. #startListeningForAdvertisements should fail if start not called

2016-04-08T08:15:03.834Z - info: Running on android test: 24. #startUpdateAdvertisingAndListening should fail if start not called

2016-04-08T08:15:04.235Z - info: Running on android test: 25. should be able to call #stopListeningForAdvertisements many times

2016-04-08T08:15:04.711Z - info: Running on android test: 26. should be able to call #startListeningForAdvertisements many times

2016-04-08T08:15:05.581Z - info: Running on android test: 27. should be able to call #startUpdateAdvertisingAndListening many times

2016-04-08T08:15:06.341Z - info: Running on android test: 28. should be able to call #stopAdvertisingAndListening many times

2016-04-08T08:15:06.804Z - info: Running on android test: 29. #start should fail if called twice in a row

2016-04-08T08:15:07.353Z - info: Running on android test: 30. does not emit duplicate discoveryAdvertisingStateUpdate

2016-04-08T08:15:08.121Z - info: Running on android test: 31. does not send duplicate availability changes

2016-04-08T08:15:08.445Z - info: Running on android test: 32. can get the network status

2016-04-08T08:15:08.789Z - info: Running on android test: 33. wifi peer is marked unavailable if announcements stop

2016-04-08T08:15:11.276Z - info: Running on android test: 34. Can call start/stopListeningForAdvertisements

2016-04-08T08:15:12.398Z - info: Running on android test: 35. Calling startListeningForAdvertisements twice is NOT an error

2016-04-08T08:15:13.198Z - info: Running on android test: 36. Calling stopListeningForAdvertisements without calling start is NOT an error

2016-04-08T08:15:13.936Z - info: Running on android test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-04-08T08:15:15.365Z - info: Running on android test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-04-08T08:15:16.693Z - info: Running on android test: 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error

2016-04-08T08:15:17.152Z - info: Running on android test: 40. cannot call connect when start listening for advertisements is not active

2016-04-08T08:15:17.507Z - info: Running on android test: 41. peerAvailabilityChange is called

2016-04-08T08:15:20.163Z - info: Running on android test: 42. Can connect to a remote peer

2016-04-08T08:15:30.732Z - info: Running on android test: 43. Get error when trying to double connect to a peer

2016-04-08T08:15:43.615Z - warn: Failed on android test: 43. Get error when trying to double connect to a peer

2016-04-08T08:15:43.616Z - info: Running on android test: 44. Connect port dies if not connected to in in time

2016-04-08T08:15:54.089Z - info: Socket to device Apple-Iphone5s-1 disconnected: ping timeout

2016-04-08T08:15:54.104Z - info: Socket to device Apple-IpadAir2-1 disconnected: ping timeout

2016-04-08T08:17:22.422Z - info: Socket to device motorola-Nexus 6 disconnected: ping timeout

2016-04-08T08:17:23.834Z - debug: Device presented: motorola-Nexus 6 (9b1eb508-6ace-4d88-a795-369611cc0eee) - android 5.1.1

2016-04-08T08:17:23.835Z - info: Updating existing device: motorola-Nexus 6 (9b1eb508-6ace-4d88-a795-369611cc0eee)

2016-04-08T08:17:24.879Z - debug: Device presented: motorola-Nexus 6 (9b1eb508-6ace-4d88-a795-369611cc0eee) - android 5.1.1

2016-04-08T08:17:24.880Z - info: Updating existing device: motorola-Nexus 6 (9b1eb508-6ace-4d88-a795-369611cc0eee)

2016-04-08T08:30:53.261Z - info: Socket to device Apple-Iphone6-1 disconnected: transport close

2016-04-08T08:30:53.646Z - info: Socket to device Apple-Iphone5-1 disconnected: transport close

2016-04-08T08:32:34.067Z - info: Socket to device LGE-LG-H815 disconnected: transport close

2016-04-08T08:34:45.288Z - info: Socket to device samsung-SM-N910C disconnected: transport close

2016-04-08T08:34:47.314Z - info: Socket to device motorola-Nexus 6 disconnected: transport close


 
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
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/65745020fc66909_Change_gradle_download_URL_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/65745020fc66909_Change_gradle_download_URL_vjrantal/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/65745020fc66909_Change_gradle_download_URL_vjrantal/iOS_Iphone5-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/65745020fc66909_Change_gradle_download_URL_vjrantal/iOS_Iphone6-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/65745020fc66909_Change_gradle_download_URL_vjrantal/iOS_server.md)


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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/65745020fc66909_Change_gradle_download_URL_vjrantal/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/65745020fc66909_Change_gradle_download_URL_vjrantal/thali07_LGE-LG-H815.md)

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
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/65745020fc66909_Change_gradle_download_URL_vjrantal/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/65745020fc66909_Change_gradle_download_URL_vjrantal/thali08_motorola-Nexus 6.md)





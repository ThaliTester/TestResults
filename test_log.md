#### Test 67111490059a058 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-04-20T02:49:49.581Z - info: Require 3 ios devices

2016-04-20T02:49:49.600Z - info: Require 3 android devices

2016-04-20T02:49:49.661Z - info: listening on *:3000

2016-04-20T02:49:50.370Z - debug: Device presented: Apple-Iphone5-1 (bfdc7c82-3e48-4c76-97f8-19cc4d017af4) - ios Version 9.1 (Build 13B143)

2016-04-20T02:49:50.818Z - debug: Device presented: Apple-Iphone6-1 (06642e6b-b55e-487b-9d1a-ac467e3aa68a) - ios Version 9.1 (Build 13B143)

2016-04-20T02:49:51.479Z - debug: Device presented: Apple-Iphone5-1 (bfdc7c82-3e48-4c76-97f8-19cc4d017af4) - ios Version 9.1 (Build 13B143)

2016-04-20T02:49:51.481Z - info: Updating existing device: Apple-Iphone5-1 (bfdc7c82-3e48-4c76-97f8-19cc4d017af4)

2016-04-20T02:49:51.567Z - debug: Device presented: LGE-Nexus 5 (406548e9-9c15-4f85-b1fd-bf558fe9ca8f) - android 5.1.1

2016-04-20T02:49:51.924Z - debug: Device presented: Apple-Iphone6-1 (06642e6b-b55e-487b-9d1a-ac467e3aa68a) - ios Version 9.1 (Build 13B143)

2016-04-20T02:49:51.926Z - info: Updating existing device: Apple-Iphone6-1 (06642e6b-b55e-487b-9d1a-ac467e3aa68a)

2016-04-20T02:49:52.552Z - debug: Device presented: LGE-Nexus 5 (406548e9-9c15-4f85-b1fd-bf558fe9ca8f) - android 5.1.1

2016-04-20T02:49:52.554Z - info: Updating existing device: LGE-Nexus 5 (406548e9-9c15-4f85-b1fd-bf558fe9ca8f)

2016-04-20T02:49:53.886Z - debug: Device presented: Apple-Iphone5s-1 (193381e1-e38b-4d7e-b0af-8de5815cb621) - ios Version 9.1 (Build 13B143)

2016-04-20T02:49:54.309Z - debug: Device presented: Apple-IpadAir2-1 (da57b363-146c-4326-bcf1-87fd4d08657a) - ios Version 9.1 (Build 13B143)

2016-04-20T02:49:54.312Z - info: All 4 ios devices are present

2016-04-20T02:49:54.319Z - info: Starting unit test run on 4 ios devices

2016-04-20T02:49:54.673Z - debug: Device presented: LGE-LG-H815 (916faaf3-c58f-48b8-b117-0e9ca26fdf68) - android 5.1

2016-04-20T02:49:55.224Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-04-20T02:49:55.263Z - debug: Device presented: Apple-IpadAir2-1 (da57b363-146c-4326-bcf1-87fd4d08657a) - ios Version 9.1 (Build 13B143)

2016-04-20T02:49:55.265Z - info: Updating existing device: Apple-IpadAir2-1 (da57b363-146c-4326-bcf1-87fd4d08657a)

2016-04-20T02:49:55.283Z - debug: Device presented: Apple-Iphone5s-1 (193381e1-e38b-4d7e-b0af-8de5815cb621) - ios Version 9.1 (Build 13B143)

2016-04-20T02:49:55.284Z - info: Updating existing device: Apple-Iphone5s-1 (193381e1-e38b-4d7e-b0af-8de5815cb621)

2016-04-20T02:49:55.519Z - info: Running on ios test: 2. emits incomingConnectionState

2016-04-20T02:49:55.680Z - debug: Device presented: LGE-LG-H815 (916faaf3-c58f-48b8-b117-0e9ca26fdf68) - android 5.1

2016-04-20T02:49:55.681Z - info: Updating existing device: LGE-LG-H815 (916faaf3-c58f-48b8-b117-0e9ca26fdf68)

2016-04-20T02:49:55.885Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-04-20T02:49:56.254Z - info: Running on ios test: 4. native server connections all up

2016-04-20T02:49:56.732Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-04-20T02:49:57.096Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-04-20T02:49:57.132Z - debug: Device presented: samsung-SM-N910C (3eec1129-ce8d-4569-8a76-43aa839bf38b) - android 5.1.1

2016-04-20T02:49:57.449Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-04-20T02:49:57.790Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-04-20T02:49:58.167Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-04-20T02:50:01.396Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-04-20T02:50:01.938Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-04-20T02:50:02.309Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-04-20T02:50:02.659Z - info: Running on ios test: 13. closeAll with promise

2016-04-20T02:50:02.995Z - info: Running on ios test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-04-20T02:50:03.350Z - info: Running on ios test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-04-20T02:50:03.709Z - info: Running on ios test: 16. enqueue and run in order

2016-04-20T02:50:04.269Z - info: Running on ios test: 17. enqueueAtTop and run backwards

2016-04-20T02:50:04.516Z - info: Running on ios test: 18. mix enqueue and enqueueAtTop

2016-04-20T02:50:04.902Z - info: Running on ios test: 19. queues handled independently

2016-04-20T02:50:04.961Z - debug: Device presented: motorola-Nexus 6 (36896084-5ba2-48ca-9657-62dd11bf4c72) - android 5.1.1

2016-04-20T02:50:04.962Z - info: All 4 android devices are present

2016-04-20T02:50:04.963Z - info: Disqualifying device with unsupported hardware: LGE-Nexus 5

2016-04-20T02:50:04.967Z - info: Starting unit test run on 3 android devices

2016-04-20T02:50:05.214Z - info: Running on ios test: 20. basic

2016-04-20T02:50:05.477Z - info: Running on ios test: 21. another

2016-04-20T02:50:05.726Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-04-20T02:50:05.850Z - info: Running on ios test: 22. can pass data in setup

2016-04-20T02:50:05.893Z - info: Socket to device LGE-Nexus 5 disconnected: transport close

2016-04-20T02:50:06.126Z - info: Running on android test: 2. emits incomingConnectionState

2016-04-20T02:50:06.227Z - info: Running on ios test: 23. #startListeningForAdvertisements should fail if start not called

2016-04-20T02:50:06.542Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-04-20T02:50:06.549Z - info: Running on ios test: 24. #startUpdateAdvertisingAndListening should fail if start not called

2016-04-20T02:50:06.828Z - info: Running on ios test: 25. should be able to call #stopListeningForAdvertisements many times

2016-04-20T02:50:06.892Z - info: Running on android test: 4. native server connections all up

2016-04-20T02:50:07.229Z - info: Running on ios test: 26. should be able to call #startListeningForAdvertisements many times

2016-04-20T02:50:07.284Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-04-20T02:50:07.747Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-04-20T02:50:07.778Z - info: Running on ios test: 27. should be able to call #startUpdateAdvertisingAndListening many times

2016-04-20T02:50:08.205Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-04-20T02:50:08.543Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-04-20T02:50:09.017Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-04-20T02:50:12.242Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-04-20T02:50:19.125Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-04-20T02:50:27.847Z - info: Running on android test: 12. closeAll can close even when connections open

2016-04-20T02:50:28.262Z - info: Running on android test: 13. closeAll with promise

2016-04-20T02:50:28.721Z - info: Running on android test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-04-20T02:50:29.175Z - info: Running on android test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-04-20T02:50:29.535Z - info: Running on android test: 16. enqueue and run in order

2016-04-20T02:50:30.092Z - info: Running on android test: 17. enqueueAtTop and run backwards

2016-04-20T02:50:30.352Z - info: Running on android test: 18. mix enqueue and enqueueAtTop

2016-04-20T02:50:30.800Z - info: Running on android test: 19. queues handled independently

2016-04-20T02:50:31.090Z - info: Running on android test: 20. basic

2016-04-20T02:50:31.367Z - info: Running on android test: 21. another

2016-04-20T02:50:31.685Z - info: Running on android test: 22. can pass data in setup

2016-04-20T02:50:32.036Z - info: Running on android test: 23. #startListeningForAdvertisements should fail if start not called

2016-04-20T02:50:32.368Z - info: Running on android test: 24. #startUpdateAdvertisingAndListening should fail if start not called

2016-04-20T02:50:32.660Z - info: Running on android test: 25. should be able to call #stopListeningForAdvertisements many times

2016-04-20T02:50:33.149Z - info: Running on android test: 26. should be able to call #startListeningForAdvertisements many times

2016-04-20T02:50:33.711Z - info: Running on android test: 27. should be able to call #startUpdateAdvertisingAndListening many times

2016-04-20T02:50:34.321Z - info: Running on android test: 28. should be able to call #stopAdvertisingAndListening many times

2016-04-20T02:50:34.599Z - info: Running on android test: 29. #start should fail if called twice in a row

2016-04-20T02:50:34.876Z - info: Running on android test: 30. does not emit duplicate discoveryAdvertisingStateUpdate

2016-04-20T02:50:36.732Z - info: Running on android test: 31. does not send duplicate availability changes

2016-04-20T02:50:37.675Z - info: Running on android test: 32. can get the network status

2016-04-20T02:50:37.833Z - info: Running on android test: 33. wifi peer is marked unavailable if announcements stop

2016-04-20T02:50:40.101Z - info: Running on android test: 34. Can call start/stopListeningForAdvertisements

2016-04-20T02:50:40.442Z - info: Running on android test: 35. Calling startListeningForAdvertisements twice is NOT an error

2016-04-20T02:50:40.859Z - info: Running on android test: 36. Calling stopListeningForAdvertisements without calling start is NOT an error

2016-04-20T02:50:41.101Z - info: Running on android test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-04-20T02:50:41.532Z - info: Running on android test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-04-20T02:50:42.633Z - info: Running on android test: 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error

2016-04-20T02:50:43.317Z - info: Running on android test: 40. cannot call connect when start listening for advertisements is not active

2016-04-20T02:50:43.550Z - info: Running on android test: 41. peerAvailabilityChange is called

2016-04-20T02:50:45.078Z - info: Running on android test: 42. Can connect to a remote peer

2016-04-20T02:50:50.622Z - info: Running on ios test: 28. should be able to call #stopAdvertisingAndListening many times

2016-04-20T02:50:51.257Z - info: Running on ios test: 29. #start should fail if called twice in a row

2016-04-20T02:50:51.580Z - info: Running on ios test: 30. does not emit duplicate discoveryAdvertisingStateUpdate

2016-04-20T02:50:58.105Z - info: Running on android test: 43. Get error when trying to double connect to a peer

2016-04-20T02:51:11.012Z - warn: Failed on android test: 43. Get error when trying to double connect to a peer

2016-04-20T02:51:11.013Z - info: Running on android test: 44. Connect port dies if not connected to in in time

2016-04-20T02:52:16.770Z - info: Socket to device Apple-Iphone5s-1 disconnected: ping timeout

2016-04-20T03:09:09.836Z - info: Socket to device Apple-IpadAir2-1 disconnected: transport close

2016-04-20T03:09:09.889Z - info: Socket to device Apple-Iphone5-1 disconnected: transport close

2016-04-20T03:09:09.902Z - info: Socket to device Apple-Iphone6-1 disconnected: transport close

2016-04-20T03:10:50.536Z - info: Socket to device LGE-LG-H815 disconnected: transport close

2016-04-20T03:13:15.820Z - info: Socket to device samsung-SM-N910C disconnected: transport close

2016-04-20T03:13:17.812Z - info: Socket to device motorola-Nexus 6 disconnected: transport close


 
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
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/67111490059a058__708_-_Fix_environment_variables_yaronyg/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/67111490059a058__708_-_Fix_environment_variables_yaronyg/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/67111490059a058__708_-_Fix_environment_variables_yaronyg/iOS_Iphone5-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/67111490059a058__708_-_Fix_environment_variables_yaronyg/iOS_Iphone6-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/67111490059a058__708_-_Fix_environment_variables_yaronyg/iOS_server.md)


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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/67111490059a058__708_-_Fix_environment_variables_yaronyg/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/67111490059a058__708_-_Fix_environment_variables_yaronyg/thali07_LGE-LG-H815.md)

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
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/67111490059a058__708_-_Fix_environment_variables_yaronyg/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/67111490059a058__708_-_Fix_environment_variables_yaronyg/thali08_motorola-Nexus 6.md)





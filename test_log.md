#### Test 672996567f6295f Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-04-21T06:04:37.844Z - info: Require 3 ios devices

2016-04-21T06:04:37.862Z - info: Require 3 android devices

2016-04-21T06:04:37.922Z - info: listening on *:3000

2016-04-21T06:04:39.459Z - debug: Device presented: Apple-Iphone5-1 (cf90b6ac-3d97-4f3a-bd72-d66d06b66e31) - ios Version 9.1 (Build 13B143)

2016-04-21T06:04:40.010Z - debug: Device presented: LGE-LG-H815 (66d209c1-9315-4289-bd0a-38bf0cdbaba3) - android 5.1

2016-04-21T06:04:40.528Z - debug: Device presented: Apple-Iphone5-1 (cf90b6ac-3d97-4f3a-bd72-d66d06b66e31) - ios Version 9.1 (Build 13B143)

2016-04-21T06:04:40.530Z - info: Updating existing device: Apple-Iphone5-1 (cf90b6ac-3d97-4f3a-bd72-d66d06b66e31)

2016-04-21T06:04:40.841Z - debug: Device presented: samsung-SM-N910C (5caa9ee4-033f-4c80-b60b-8964084038a0) - android 5.1.1

2016-04-21T06:04:40.998Z - debug: Device presented: LGE-LG-H815 (66d209c1-9315-4289-bd0a-38bf0cdbaba3) - android 5.1

2016-04-21T06:04:40.999Z - info: Updating existing device: LGE-LG-H815 (66d209c1-9315-4289-bd0a-38bf0cdbaba3)

2016-04-21T06:04:41.142Z - debug: Device presented: Apple-Iphone5s-1 (5e4df3c2-f602-4178-a13a-81c93a9ba829) - ios Version 9.1 (Build 13B143)

2016-04-21T06:04:41.959Z - debug: Device presented: LGE-Nexus 5 (e4b2e1e1-477a-4938-a36e-b65ff0a99889) - android 5.1.1

2016-04-21T06:04:42.324Z - debug: Device presented: Apple-Iphone5s-1 (5e4df3c2-f602-4178-a13a-81c93a9ba829) - ios Version 9.1 (Build 13B143)

2016-04-21T06:04:42.327Z - info: Updating existing device: Apple-Iphone5s-1 (5e4df3c2-f602-4178-a13a-81c93a9ba829)

2016-04-21T06:04:42.871Z - debug: Device presented: Apple-IpadAir2-1 (4f97eb7e-6659-4f2d-bf17-e6c7b4687532) - ios Version 9.1 (Build 13B143)

2016-04-21T06:04:42.989Z - debug: Device presented: LGE-Nexus 5 (e4b2e1e1-477a-4938-a36e-b65ff0a99889) - android 5.1.1

2016-04-21T06:04:42.990Z - info: Updating existing device: LGE-Nexus 5 (e4b2e1e1-477a-4938-a36e-b65ff0a99889)

2016-04-21T06:04:43.958Z - debug: Device presented: Apple-IpadAir2-1 (4f97eb7e-6659-4f2d-bf17-e6c7b4687532) - ios Version 9.1 (Build 13B143)

2016-04-21T06:04:43.959Z - info: Updating existing device: Apple-IpadAir2-1 (4f97eb7e-6659-4f2d-bf17-e6c7b4687532)

2016-04-21T06:04:47.395Z - debug: Device presented: motorola-Nexus 6 (740e53ee-c3b1-4987-af3d-09f7e8b75912) - android 5.1.1

2016-04-21T06:04:47.398Z - info: All 4 android devices are present

2016-04-21T06:04:47.401Z - info: Disqualifying device with unsupported hardware: LGE-Nexus 5

2016-04-21T06:04:47.413Z - info: Starting unit test run on 3 android devices

2016-04-21T06:04:48.310Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-04-21T06:04:48.471Z - info: Socket to device LGE-Nexus 5 disconnected: transport close

2016-04-21T06:04:49.845Z - info: Running on android test: 2. emits incomingConnectionState

2016-04-21T06:04:51.247Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-04-21T06:04:53.090Z - info: Running on android test: 4. native server connections all up

2016-04-21T06:04:55.321Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-04-21T06:05:19.046Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-04-21T06:05:19.807Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-04-21T06:05:20.252Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-04-21T06:05:20.615Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-04-21T06:05:21.450Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-04-21T06:05:21.754Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-04-21T06:05:22.138Z - info: Running on android test: 12. closeAll can close even when connections open

2016-04-21T06:05:22.541Z - info: Running on android test: 13. closeAll with promise

2016-04-21T06:05:22.909Z - info: Running on android test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-04-21T06:05:23.339Z - info: Running on android test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-04-21T06:05:23.933Z - info: Running on android test: 16. enqueue and run in order

2016-04-21T06:05:24.461Z - info: Running on android test: 17. enqueueAtTop and run backwards

2016-04-21T06:05:24.795Z - info: Running on android test: 18. mix enqueue and enqueueAtTop

2016-04-21T06:05:25.199Z - info: Running on android test: 19. queues handled independently

2016-04-21T06:05:25.550Z - info: Running on android test: 20. basic

2016-04-21T06:05:25.854Z - info: Running on android test: 21. another

2016-04-21T06:05:26.155Z - info: Running on android test: 22. can pass data in setup

2016-04-21T06:05:26.505Z - info: Running on android test: 23. #startListeningForAdvertisements should fail if start not called

2016-04-21T06:05:26.803Z - info: Running on android test: 24. #startUpdateAdvertisingAndListening should fail if start not called

2016-04-21T06:05:27.027Z - info: Running on android test: 25. should be able to call #stopListeningForAdvertisements many times

2016-04-21T06:05:27.490Z - info: Running on android test: 26. should be able to call #startListeningForAdvertisements many times

2016-04-21T06:05:28.137Z - info: Running on android test: 27. should be able to call #startUpdateAdvertisingAndListening many times

2016-04-21T06:05:30.022Z - info: Running on android test: 28. should be able to call #stopAdvertisingAndListening many times

2016-04-21T06:05:30.314Z - info: Running on android test: 29. #start should fail if called twice in a row

2016-04-21T06:05:30.633Z - info: Running on android test: 30. does not emit duplicate discoveryAdvertisingStateUpdate

2016-04-21T06:05:32.269Z - info: Running on android test: 31. does not send duplicate availability changes

2016-04-21T06:05:32.621Z - info: Running on android test: 32. can get the network status

2016-04-21T06:05:32.967Z - info: Running on android test: 33. wifi peer is marked unavailable if announcements stop

2016-04-21T06:05:35.305Z - info: Running on android test: 34. Can call start/stopListeningForAdvertisements

2016-04-21T06:05:35.812Z - info: Running on android test: 35. Calling startListeningForAdvertisements twice is NOT an error

2016-04-21T06:05:36.347Z - info: Running on android test: 36. Calling stopListeningForAdvertisements without calling start is NOT an error

2016-04-21T06:05:36.633Z - info: Running on android test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-04-21T06:05:37.399Z - info: Running on android test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-04-21T06:05:38.291Z - info: Running on android test: 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error

2016-04-21T06:05:38.544Z - info: Running on android test: 40. cannot call connect when start listening for advertisements is not active

2016-04-21T06:05:38.835Z - info: Running on android test: 41. peerAvailabilityChange is called

2016-04-21T06:05:40.571Z - info: Running on android test: 42. Can connect to a remote peer

2016-04-21T06:05:51.919Z - info: Running on android test: 43. Get error when trying to double connect to a peer

2016-04-21T06:05:59.316Z - warn: Failed on android test: 43. Get error when trying to double connect to a peer

2016-04-21T06:05:59.319Z - info: Running on android test: 44. Connect port dies if not connected to in in time

2016-04-21T06:24:02.489Z - info: Socket to device Apple-IpadAir2-1 disconnected: transport close

2016-04-21T06:24:02.542Z - info: Socket to device Apple-Iphone5-1 disconnected: transport close

2016-04-21T06:24:02.637Z - info: Socket to device Apple-Iphone5s-1 disconnected: transport close

2016-04-21T06:25:42.916Z - info: Socket to device LGE-LG-H815 disconnected: transport close

2016-04-21T06:27:59.061Z - info: Socket to device samsung-SM-N910C disconnected: transport close

2016-04-21T06:28:00.820Z - info: Socket to device motorola-Nexus 6 disconnected: transport close


 
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
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/672996567f6295f_Fix_for__711_-_added_jxcore_url_to_configuration_file_czyzm/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/672996567f6295f_Fix_for__711_-_added_jxcore_url_to_configuration_file_czyzm/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/672996567f6295f_Fix_for__711_-_added_jxcore_url_to_configuration_file_czyzm/iOS_Iphone5-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/672996567f6295f_Fix_for__711_-_added_jxcore_url_to_configuration_file_czyzm/iOS_Iphone6-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/672996567f6295f_Fix_for__711_-_added_jxcore_url_to_configuration_file_czyzm/iOS_server.md)


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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/672996567f6295f_Fix_for__711_-_added_jxcore_url_to_configuration_file_czyzm/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/672996567f6295f_Fix_for__711_-_added_jxcore_url_to_configuration_file_czyzm/thali07_LGE-LG-H815.md)

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
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/672996567f6295f_Fix_for__711_-_added_jxcore_url_to_configuration_file_czyzm/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/672996567f6295f_Fix_for__711_-_added_jxcore_url_to_configuration_file_czyzm/thali08_motorola-Nexus 6.md)





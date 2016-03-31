#### Test 646138038b5bc7c Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-03-31T15:41:02.438Z - info: Require 3 ios devices

2016-03-31T15:41:02.456Z - info: Require 3 android devices

2016-03-31T15:41:02.516Z - info: listening on *:3000

2016-03-31T15:41:04.947Z - debug: Device presented: LGE-Nexus 5 (fada9800-dec4-455b-bdc7-dabe29d404e9) - android 5.1.1

2016-03-31T15:41:05.222Z - debug: Device presented: LGE-LG-H815 (09df9b58-c00e-441d-95dd-ac84f3a5a575) - android 5.1

2016-03-31T15:41:05.799Z - debug: Device presented: Apple-IpadAir2-1 (d360614e-eafc-47a4-b232-9db4049e83cd) - ios Version 9.1 (Build 13B143)

2016-03-31T15:41:05.930Z - debug: Device presented: LGE-Nexus 5 (fada9800-dec4-455b-bdc7-dabe29d404e9) - android 5.1.1

2016-03-31T15:41:05.931Z - info: Updating existing device: LGE-Nexus 5 (fada9800-dec4-455b-bdc7-dabe29d404e9)

2016-03-31T15:41:06.204Z - debug: Device presented: LGE-LG-H815 (09df9b58-c00e-441d-95dd-ac84f3a5a575) - android 5.1

2016-03-31T15:41:06.205Z - info: Updating existing device: LGE-LG-H815 (09df9b58-c00e-441d-95dd-ac84f3a5a575)

2016-03-31T15:41:06.783Z - debug: Device presented: Apple-IpadAir2-1 (d360614e-eafc-47a4-b232-9db4049e83cd) - ios Version 9.1 (Build 13B143)

2016-03-31T15:41:06.784Z - info: Updating existing device: Apple-IpadAir2-1 (d360614e-eafc-47a4-b232-9db4049e83cd)

2016-03-31T15:41:07.457Z - debug: Device presented: Apple-Iphone6-1 (93b06dd5-4156-4a62-b430-5e379b5bf668) - ios Version 9.1 (Build 13B143)

2016-03-31T15:41:07.462Z - debug: Device presented: Apple-Iphone5-1 (2d44cdcc-6331-4fd1-8321-40772b7965dd) - ios Version 9.1 (Build 13B143)

2016-03-31T15:41:08.135Z - debug: Device presented: Apple-Iphone5s-1 (5a159754-f32d-49c6-9977-dc42c1fa4a99) - ios Version 9.1 (Build 13B143)

2016-03-31T15:41:08.137Z - info: All 4 ios devices are present

2016-03-31T15:41:08.144Z - info: Starting unit test run on 4 ios devices

2016-03-31T15:41:08.442Z - debug: Device presented: Apple-Iphone6-1 (93b06dd5-4156-4a62-b430-5e379b5bf668) - ios Version 9.1 (Build 13B143)

2016-03-31T15:41:08.443Z - info: Updating existing device: Apple-Iphone6-1 (93b06dd5-4156-4a62-b430-5e379b5bf668)

2016-03-31T15:41:08.449Z - debug: Device presented: Apple-Iphone5-1 (2d44cdcc-6331-4fd1-8321-40772b7965dd) - ios Version 9.1 (Build 13B143)

2016-03-31T15:41:08.450Z - info: Updating existing device: Apple-Iphone5-1 (2d44cdcc-6331-4fd1-8321-40772b7965dd)

2016-03-31T15:41:08.927Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-31T15:41:09.157Z - debug: Device presented: Apple-Iphone5s-1 (5a159754-f32d-49c6-9977-dc42c1fa4a99) - ios Version 9.1 (Build 13B143)

2016-03-31T15:41:09.159Z - info: Updating existing device: Apple-Iphone5s-1 (5a159754-f32d-49c6-9977-dc42c1fa4a99)

2016-03-31T15:41:09.476Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-31T15:41:09.899Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-31T15:41:10.391Z - info: Running on ios test: 4. native server connections all up

2016-03-31T15:41:10.568Z - debug: Device presented: samsung-SM-N910C (7c0b9993-3f94-46a9-bcae-bea2585a8ff8) - android 5.1.1

2016-03-31T15:41:10.891Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-31T15:41:11.493Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-31T15:41:12.044Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-31T15:41:12.533Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-31T15:41:13.010Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-31T15:41:20.806Z - debug: Device presented: motorola-Nexus 6 (7e0fbac2-01ae-4b38-8d07-95fc9ca257ca) - android 5.1.1

2016-03-31T15:41:20.807Z - info: All 4 android devices are present

2016-03-31T15:41:20.809Z - info: Disqualifying device with unsupported hardware: LGE-Nexus 5

2016-03-31T15:41:20.813Z - info: Starting unit test run on 3 android devices

2016-03-31T15:41:21.302Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-31T15:41:21.596Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-31T15:41:21.779Z - debug: Device presented: motorola-Nexus 6 (7e0fbac2-01ae-4b38-8d07-95fc9ca257ca) - android 5.1.1

2016-03-31T15:41:21.780Z - info: Updating existing device: motorola-Nexus 6 (7e0fbac2-01ae-4b38-8d07-95fc9ca257ca)

2016-03-31T15:41:21.985Z - info: Socket to device LGE-Nexus 5 disconnected: transport close

2016-03-31T15:41:22.139Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-31T15:41:22.201Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-31T15:41:22.658Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-31T15:41:22.677Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-31T15:41:23.051Z - info: Running on ios test: 13. closeAll with promise

2016-03-31T15:41:23.128Z - info: Running on android test: 4. native server connections all up

2016-03-31T15:41:23.541Z - info: Running on ios test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-03-31T15:41:23.771Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-31T15:41:23.903Z - info: Running on ios test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-03-31T15:41:24.208Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-31T15:41:24.266Z - info: Running on ios test: 16. multiplex can send data

2016-03-31T15:41:24.758Z - info: Running on ios test: 17. enqueue and run in order

2016-03-31T15:41:24.772Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-31T15:41:25.193Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-31T15:41:25.296Z - info: Running on ios test: 18. enqueueAtTop and run backwards

2016-03-31T15:41:25.643Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-31T15:41:25.658Z - info: Running on ios test: 19. mix enqueue and enqueueAtTop

2016-03-31T15:41:26.250Z - info: Running on ios test: 20. queues handled independently

2016-03-31T15:41:26.667Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-31T15:41:26.807Z - info: Running on ios test: 21. basic

2016-03-31T15:41:27.110Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-31T15:41:27.147Z - info: Running on ios test: 22. another

2016-03-31T15:41:27.827Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-31T15:41:30.571Z - info: Running on android test: 13. closeAll with promise

2016-03-31T15:41:30.696Z - info: Running on ios test: 23. can pass data in setup

2016-03-31T15:41:30.994Z - info: Running on android test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-03-31T15:41:31.540Z - info: Running on android test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-03-31T15:41:31.638Z - info: Running on ios test: 24. #startListeningForAdvertisements should fail if start not called

2016-03-31T15:41:32.073Z - info: Running on android test: 16. multiplex can send data

2016-03-31T15:41:32.105Z - info: Running on ios test: 25. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-31T15:41:32.468Z - info: Running on ios test: 26. should be able to call #stopListeningForAdvertisements many times

2016-03-31T15:41:32.527Z - info: Running on android test: 17. enqueue and run in order

2016-03-31T15:41:32.956Z - info: Running on ios test: 27. should be able to call #startListeningForAdvertisements many times

2016-03-31T15:41:33.193Z - info: Running on android test: 18. enqueueAtTop and run backwards

2016-03-31T15:41:33.595Z - info: Running on android test: 19. mix enqueue and enqueueAtTop

2016-03-31T15:41:33.648Z - info: Running on ios test: 28. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-31T15:41:34.086Z - info: Running on android test: 20. queues handled independently

2016-03-31T15:41:34.864Z - info: Running on android test: 21. basic

2016-03-31T15:41:38.669Z - info: Running on ios test: 29. should be able to call #stopAdvertisingAndListening many times

2016-03-31T15:41:40.798Z - info: Running on android test: 22. another

2016-03-31T15:41:40.860Z - info: Running on ios test: 30. #start should fail if called twice in a row

2016-03-31T15:41:42.698Z - info: Running on android test: 23. can pass data in setup

2016-03-31T15:41:43.165Z - info: Running on android test: 24. #startListeningForAdvertisements should fail if start not called

2016-03-31T15:41:43.732Z - info: Running on android test: 25. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-31T15:41:44.189Z - info: Running on android test: 26. should be able to call #stopListeningForAdvertisements many times

2016-03-31T15:41:45.045Z - info: Running on android test: 27. should be able to call #startListeningForAdvertisements many times

2016-03-31T15:41:46.001Z - info: Running on android test: 28. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-31T15:41:46.905Z - info: Running on android test: 29. should be able to call #stopAdvertisingAndListening many times

2016-03-31T15:41:47.408Z - info: Running on android test: 30. #start should fail if called twice in a row

2016-03-31T15:41:47.947Z - info: Running on android test: 31. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-31T15:41:48.790Z - info: Running on android test: 32. does not send duplicate availability changes

2016-03-31T15:41:49.293Z - info: Running on android test: 33. can get the network status

2016-03-31T15:41:49.696Z - info: Running on android test: 34. wifi peer is marked unavailable if announcements stop

2016-03-31T15:41:52.126Z - info: Running on android test: 35. Can call start/stopListeningForAdvertisements

2016-03-31T15:41:52.677Z - info: Running on android test: 36. Calling startListeningForAdvertisements twice is NOT an error

2016-03-31T15:41:53.284Z - info: Running on android test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-03-31T15:41:53.940Z - info: Running on android test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-31T15:41:54.795Z - info: Running on android test: 39. peerAvailabilityChange is called

2016-03-31T15:41:55.968Z - info: Running on ios test: 31. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-31T15:41:56.520Z - info: Running on ios test: 32. does not send duplicate availability changes

2016-03-31T15:41:56.781Z - info: Running on android test: 40. Can connect to a remote peer

2016-03-31T15:41:57.041Z - info: Running on ios test: 33. can get the network status

2016-03-31T15:42:21.766Z - info: Running on ios test: 34. wifi peer is marked unavailable if announcements stop

2016-03-31T15:42:26.600Z - info: Running on android test: 41. Can shift large amounts of data

2016-03-31T15:42:37.606Z - info: Running on android test: 42. #startListeningForAdvertisements should fail if start not called

2016-03-31T15:42:39.035Z - info: Running on ios test: 35. Can call start/stopListeningForAdvertisements

2016-03-31T15:42:39.512Z - info: Running on android test: 43. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-31T15:42:39.761Z - info: Running on ios test: 36. Calling startListeningForAdvertisements twice is NOT an error

2016-03-31T15:42:42.980Z - info: Running on android test: 44. should be able to call #stopListeningForAdvertisements many times

2016-03-31T15:42:44.640Z - info: Running on android test: 45. should be able to call #startListeningForAdvertisements many times

2016-03-31T15:42:45.422Z - info: Running on android test: 46. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-31T15:42:48.482Z - info: Running on ios test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-03-31T15:42:49.845Z - info: Running on android test: 47. should be able to call #stopAdvertisingAndListening many times

2016-03-31T15:42:50.450Z - info: Running on android test: 48. can get the network status before starting

2016-03-31T15:42:50.905Z - info: Running on android test: 49. error returned with bad router

2016-03-31T15:42:51.326Z - info: Running on android test: 50. all services are stopped when we call stop

2016-03-31T15:42:52.370Z - info: Running on android test: 51. make sure terminateConnection is properly hooked up

2016-03-31T15:42:52.807Z - info: Running on android test: 52. make sure terminateListener is properly hooked up

2016-03-31T15:42:53.481Z - info: Running on android test: 53. make sure we actually call kill connections properly

2016-03-31T15:42:53.811Z - info: Running on ios test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-31T15:42:54.065Z - info: Running on android test: 54. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received

2016-03-31T15:42:55.256Z - info: Running on android test: 55. We repeat failedConnection event when we get it from thaliTcpServersManager

2016-03-31T15:42:55.735Z - info: Running on android test: 56. we successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-31T15:42:56.882Z - info: Socket to device motorola-Nexus 6 disconnected: transport close

2016-03-31T15:42:56.987Z - info: Socket to device LGE-LG-H815 disconnected: transport close

2016-03-31T15:42:57.373Z - info: Socket to device samsung-SM-N910C disconnected: transport close

2016-03-31T15:43:02.484Z - info: Running on ios test: 39. peerAvailabilityChange is called

2016-03-31T15:43:21.522Z - info: Running on ios test: 40. Can connect to a remote peer

2016-03-31T15:44:55.775Z - debug: Too many emit retries to device: motorola-Nexus 6

2016-03-31T15:44:55.780Z - debug: Too many emit retries to device: LGE-LG-H815

2016-03-31T15:45:32.712Z - warn: Failed on ios test: 40. Can connect to a remote peer

2016-03-31T15:45:32.714Z - info: Running on ios test: 41. Can shift large amounts of data

2016-03-31T15:50:09.950Z - warn: Failed on ios test: 41. Can shift large amounts of data

2016-03-31T15:50:09.953Z - info: Running on ios test: 42. #startListeningForAdvertisements should fail if start not called

2016-03-31T15:50:23.463Z - info: Running on ios test: 43. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-31T15:50:24.836Z - info: Running on ios test: 44. should be able to call #stopListeningForAdvertisements many times

2016-03-31T15:50:32.225Z - info: Running on ios test: 45. should be able to call #startListeningForAdvertisements many times

2016-03-31T15:51:14.455Z - info: Running on ios test: 46. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-31T15:51:32.114Z - info: Socket to device Apple-Iphone6-1 disconnected: transport close

2016-03-31T15:53:28.493Z - debug: Too many emit retries to device: Apple-Iphone6-1

2016-03-31T16:00:51.954Z - info: Socket to device Apple-IpadAir2-1 disconnected: transport close

2016-03-31T16:00:51.976Z - info: Socket to device Apple-Iphone5s-1 disconnected: transport close

2016-03-31T16:00:52.012Z - info: Socket to device Apple-Iphone5-1 disconnected: transport close


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m



ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code 254 on device 2a65f58f9902a701b5c9a55b2befb18672927474 
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true

```
###Android Logs
####Node name: thali07
Console output:
```
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
Device test finished on 0c6a0f3c0bdb4e77 
STOP log received from  LGH8153b36be34 Test has  FAILED
Device test finished on LGH8153b36be34 
Android task is completed. [FAILED]
```
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/646138038b5bc7c_Test_framework_improvements_vjrantal/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/646138038b5bc7c_Test_framework_improvements_vjrantal/thali07_LGE-LG-H815.md)

####Node name: thali08
Console output:
```
STOP log received from  ZX1G429CRK Test has  FAILED
STOP log received from  41006f95c8139173 Test has  FAILED
Device test finished on ZX1G429CRK 
Device test finished on 41006f95c8139173 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/646138038b5bc7c_Test_framework_improvements_vjrantal/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/646138038b5bc7c_Test_framework_improvements_vjrantal/thali08_motorola-Nexus 6.md)


###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/646138038b5bc7c_Test_framework_improvements_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/646138038b5bc7c_Test_framework_improvements_vjrantal/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/646138038b5bc7c_Test_framework_improvements_vjrantal/iOS_Iphone5-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/646138038b5bc7c_Test_framework_improvements_vjrantal/iOS_Iphone6-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/646138038b5bc7c_Test_framework_improvements_vjrantal/iOS_server.md)





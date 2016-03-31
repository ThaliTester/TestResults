#### Test 64613803717efd7 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-03-31T10:59:41.228Z - info: Require 3 ios devices

2016-03-31T10:59:41.246Z - info: Require 3 android devices

2016-03-31T10:59:41.306Z - info: listening on *:3000

2016-03-31T10:59:42.426Z - debug: Device presented: Apple-Iphone5-1 (ios) 16b2f6e7-7b28-47c9-a6dd-2f6af825100d

2016-03-31T10:59:43.352Z - debug: Device presented: Apple-Iphone5-1 (ios) 16b2f6e7-7b28-47c9-a6dd-2f6af825100d

2016-03-31T10:59:43.354Z - info: Updating existing device: Apple-Iphone5-1 (16b2f6e7-7b28-47c9-a6dd-2f6af825100d)

2016-03-31T10:59:44.966Z - debug: Device presented: Apple-Iphone6-1 (ios) 1580834d-f04e-4b35-8565-f3dded4a38c3

2016-03-31T10:59:45.697Z - debug: Device presented: LGE-LG-H815 (android) 0801153d-cb21-4b69-ae10-cc9025041f1c

2016-03-31T10:59:45.805Z - debug: Device presented: LGE-Nexus 5 (android) fdc4e373-2605-4aa9-85fe-95957ff6982a

2016-03-31T10:59:45.920Z - debug: Device presented: Apple-Iphone6-1 (ios) 1580834d-f04e-4b35-8565-f3dded4a38c3

2016-03-31T10:59:45.921Z - info: Updating existing device: Apple-Iphone6-1 (1580834d-f04e-4b35-8565-f3dded4a38c3)

2016-03-31T10:59:46.624Z - debug: Device presented: LGE-LG-H815 (android) 0801153d-cb21-4b69-ae10-cc9025041f1c

2016-03-31T10:59:46.629Z - info: Updating existing device: LGE-LG-H815 (0801153d-cb21-4b69-ae10-cc9025041f1c)

2016-03-31T10:59:46.807Z - debug: Device presented: LGE-Nexus 5 (android) fdc4e373-2605-4aa9-85fe-95957ff6982a

2016-03-31T10:59:46.808Z - info: Updating existing device: LGE-Nexus 5 (fdc4e373-2605-4aa9-85fe-95957ff6982a)

2016-03-31T10:59:49.930Z - debug: Device presented: Apple-Iphone5s-1 (ios) b0b86f5b-6b42-46b8-b718-676141bbad87

2016-03-31T10:59:50.542Z - debug: Device presented: samsung-SM-N910C (android) 6b5d8d06-647f-425d-badb-69df4a5f8f84

2016-03-31T10:59:50.909Z - debug: Device presented: Apple-Iphone5s-1 (ios) b0b86f5b-6b42-46b8-b718-676141bbad87

2016-03-31T10:59:50.910Z - info: Updating existing device: Apple-Iphone5s-1 (b0b86f5b-6b42-46b8-b718-676141bbad87)

2016-03-31T11:00:07.891Z - debug: Device presented: motorola-Nexus 6 (android) ee1607fb-b6c1-4c59-970d-20fad78ae487

2016-03-31T11:00:07.892Z - info: All 4 android devices are present

2016-03-31T11:00:07.894Z - info: Disqualifying device with unsupported hardware: LGE-Nexus 5

2016-03-31T11:00:07.906Z - info: Starting unit test run on 3 android devices

2016-03-31T11:00:08.688Z - info: Socket to device LGE-Nexus 5 disconnected: transport close

2016-03-31T11:00:08.720Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-31T11:00:09.878Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-31T11:00:10.512Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-31T11:00:11.123Z - info: Running on android test: 4. native server connections all up

2016-03-31T11:00:12.185Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-31T11:00:13.005Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-31T11:00:13.384Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-31T11:00:13.949Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-31T11:00:14.470Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-31T11:00:15.392Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-31T11:00:15.860Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-31T11:00:16.322Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-31T11:00:16.664Z - info: Running on android test: 13. closeAll with promise

2016-03-31T11:00:17.036Z - info: Running on android test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-03-31T11:00:17.491Z - info: Running on android test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-03-31T11:00:18.159Z - info: Running on android test: 16. multiplex can send data

2016-03-31T11:00:18.584Z - info: Running on android test: 17. enqueue and run in order

2016-03-31T11:00:19.262Z - info: Running on android test: 18. enqueueAtTop and run backwards

2016-03-31T11:00:19.633Z - info: Running on android test: 19. mix enqueue and enqueueAtTop

2016-03-31T11:00:20.127Z - info: Running on android test: 20. queues handled independently

2016-03-31T11:00:20.701Z - info: Running on android test: 21. basic

2016-03-31T11:00:21.563Z - info: Running on android test: 22. another

2016-03-31T11:00:22.198Z - info: Running on android test: 23. can pass data in setup

2016-03-31T11:00:22.645Z - info: Running on android test: 24. #startListeningForAdvertisements should fail if start not called

2016-03-31T11:00:23.106Z - info: Running on android test: 25. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-31T11:00:23.575Z - info: Running on android test: 26. should be able to call #stopListeningForAdvertisements many times

2016-03-31T11:00:24.145Z - info: Running on android test: 27. should be able to call #startListeningForAdvertisements many times

2016-03-31T11:00:25.057Z - info: Running on android test: 28. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-31T11:00:28.635Z - info: Running on android test: 29. should be able to call #stopAdvertisingAndListening many times

2016-03-31T11:00:29.376Z - info: Running on android test: 30. #start should fail if called twice in a row

2016-03-31T11:00:30.419Z - info: Running on android test: 31. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-31T11:00:31.237Z - info: Running on android test: 32. does not send duplicate availability changes

2016-03-31T11:00:31.709Z - info: Running on android test: 33. can get the network status

2016-03-31T11:00:33.211Z - info: Running on android test: 34. wifi peer is marked unavailable if announcements stop

2016-03-31T11:00:35.577Z - info: Running on android test: 35. Can call start/stopListeningForAdvertisements

2016-03-31T11:00:36.160Z - info: Running on android test: 36. Calling startListeningForAdvertisements twice is NOT an error

2016-03-31T11:00:36.826Z - info: Running on android test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-03-31T11:00:37.792Z - info: Running on android test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-31T11:00:38.717Z - info: Running on android test: 39. peerAvailabilityChange is called

2016-03-31T11:00:40.888Z - info: Running on android test: 40. Can connect to a remote peer

2016-03-31T11:00:49.219Z - info: Running on android test: 41. Can shift large amounts of data

2016-03-31T11:00:55.891Z - info: Running on android test: 42. #startListeningForAdvertisements should fail if start not called

2016-03-31T11:00:56.380Z - info: Running on android test: 43. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-31T11:00:56.985Z - info: Running on android test: 44. should be able to call #stopListeningForAdvertisements many times

2016-03-31T11:00:58.098Z - info: Running on android test: 45. should be able to call #startListeningForAdvertisements many times

2016-03-31T11:00:58.835Z - info: Running on android test: 46. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-31T11:01:00.982Z - info: Running on android test: 47. should be able to call #stopAdvertisingAndListening many times

2016-03-31T11:01:01.388Z - info: Running on android test: 48. can get the network status before starting

2016-03-31T11:01:01.740Z - info: Running on android test: 49. error returned with bad router

2016-03-31T11:01:02.168Z - info: Running on android test: 50. all services are stopped when we call stop

2016-03-31T11:01:03.235Z - info: Running on android test: 51. make sure terminateConnection is properly hooked up

2016-03-31T11:01:04.674Z - info: Running on android test: 52. make sure terminateListener is properly hooked up

2016-03-31T11:01:05.303Z - info: Running on android test: 53. make sure we actually call kill connections properly

2016-03-31T11:01:05.771Z - info: Running on android test: 54. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received

2016-03-31T11:01:06.234Z - info: Running on android test: 55. We repeat failedConnection event when we get it from thaliTcpServersManager

2016-03-31T11:01:06.619Z - info: Running on android test: 56. we successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-31T11:01:07.788Z - info: Socket to device motorola-Nexus 6 disconnected: transport close

2016-03-31T11:01:07.823Z - info: Socket to device LGE-LG-H815 disconnected: transport close

2016-03-31T11:01:08.117Z - info: Socket to device samsung-SM-N910C disconnected: transport close

2016-03-31T11:19:29.439Z - info: Socket to device Apple-Iphone6-1 disconnected: transport close

2016-03-31T11:19:29.450Z - info: Socket to device Apple-Iphone5s-1 disconnected: transport close

2016-03-31T11:19:29.457Z - info: Socket to device Apple-Iphone5-1 disconnected: transport close


 
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
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/64613803717efd7_Test_framework_improvements_vjrantal/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/64613803717efd7_Test_framework_improvements_vjrantal/thali07_LGE-LG-H815.md)

####Node name: thali08
Console output:
```
STOP log received from  ZX1G429CRK Test has  FAILED
STOP log received from  41006f95c8139173 Test has  FAILED
Device test finished on 41006f95c8139173 
Device test finished on ZX1G429CRK 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/64613803717efd7_Test_framework_improvements_vjrantal/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/64613803717efd7_Test_framework_improvements_vjrantal/thali08_motorola-Nexus 6.md)


###iOS Logs
[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/64613803717efd7_Test_framework_improvements_vjrantal/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/64613803717efd7_Test_framework_improvements_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/64613803717efd7_Test_framework_improvements_vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/64613803717efd7_Test_framework_improvements_vjrantal/iOS_Iphone6-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/64613803717efd7_Test_framework_improvements_vjrantal/iOS_server.md)





#### Test 62509094058a2d4 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":8}}
2016-03-15T12:19:03.813Z - info: listening on *:3000

2016-03-15T12:19:08.235Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:0

2016-03-15T12:19:08.323Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:1

2016-03-15T12:19:09.085Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:3

2016-03-15T12:19:09.088Z - info: Required number of ios devices presented (2)

2016-03-15T12:19:09.092Z - info: Starting unit test run for platform: ios

2016-03-15T12:19:09.375Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:2

2016-03-15T12:19:09.376Z - info: Discarding surplus device: Apple-Iphone5-1

2016-03-15T12:19:09.627Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-15T12:19:09.873Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-15T12:19:10.182Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-15T12:19:10.540Z - info: Running on ios test: 4. native server connections all up

2016-03-15T12:19:10.977Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-15T12:19:11.434Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-15T12:19:11.630Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:4

2016-03-15T12:19:11.631Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-15T12:19:11.803Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-15T12:19:12.359Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-15T12:19:12.645Z - debug: Socket disconnected: transport close 2 (Apple-Iphone5-1)

2016-03-15T12:19:12.711Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-15T12:19:13.451Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-15T12:19:14.904Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-15T12:19:15.335Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-15T12:19:15.705Z - info: Running on ios test: 13. closeAll with promise

2016-03-15T12:19:15.989Z - info: Running on ios test: 14. multiplex can send data

2016-03-15T12:19:16.383Z - info: Running on ios test: 15. enqueue and run in order

2016-03-15T12:19:16.709Z - debug: Socket disconnected: transport close 4 (Apple-Iphone5s-1)

2016-03-15T12:19:17.058Z - info: Running on ios test: 16. enqueueAtTop and run backwards

2016-03-15T12:19:17.491Z - info: Running on ios test: 17. mix enqueue and enqueueAtTop

2016-03-15T12:19:17.962Z - info: Running on ios test: 18. queues handled independently

2016-03-15T12:19:18.341Z - info: Running on ios test: 19. basic

2016-03-15T12:19:18.681Z - info: Running on ios test: 20. another

2016-03-15T12:19:19.062Z - info: Running on ios test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-15T12:19:19.368Z - info: Running on ios test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-15T12:19:19.652Z - info: Running on ios test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-15T12:19:20.032Z - info: Running on ios test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-15T12:19:20.338Z - info: Running on ios test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-15T12:19:20.681Z - info: Running on ios test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-15T12:19:20.980Z - info: Running on ios test: 27. #start should fail if called twice in a row

2016-03-15T12:19:21.238Z - info: Running on ios test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-15T12:19:21.824Z - info: Running on ios test: 29. does not send duplicate availability changes

2016-03-15T12:19:22.222Z - info: Running on ios test: 30. can get the network status

2016-03-15T12:19:22.582Z - info: Running on ios test: 31. wifi peer is marked unavailable if announcements stop

2016-03-15T12:19:24.043Z - info: Running on ios test: 32. Can call start/stopListeningForAdvertisements

2016-03-15T12:19:24.529Z - info: Running on ios test: 33. Calling startListeningForAdvertisements twice is NOT an error

2016-03-15T12:19:25.165Z - info: Running on ios test: 34. Can call start/stopUpdateAdvertisingAndListening

2016-03-15T12:19:26.724Z - info: Running on ios test: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-15T12:19:27.352Z - info: Running on ios test: 36. peerAvailabilityChange is called

2016-03-15T12:19:29.811Z - info: Running on ios test: 37. Can connect to a remote peer

2016-03-15T12:20:00.824Z - info: Running on ios test: 38. Can shift large amounts of data

2016-03-15T12:36:54.318Z - debug: Socket disconnected: transport close 1 (Apple-Iphone6-1)

2016-03-15T12:36:54.325Z - debug: Socket disconnected: transport close 3 (Apple-IpadAir2-1)

2016-03-15T12:39:15.116Z - debug: Socket disconnected: transport close 0 (LGE-LG-H815)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m
2016-03-15T12:19:38.855Z - error: test server: Device Apple-Iphone6-1

2016-03-15T12:19:38.858Z - error: test server: Device Apple-IpadAir2-1


```


Logs for system : 
```

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/62509094058a2d4_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/62509094058a2d4_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/62509094058a2d4_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/62509094058a2d4_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/62509094058a2d4_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  f56ad48d Test has  FAILED
Device test finished on f56ad48d 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62509094058a2d4_Make_CI_build_and_unit_tests_pass_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/62509094058a2d4_Make_CI_build_and_unit_tests_pass_vjrantal/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
STOP log received from  ZX1C223JKW Test has  FAILED
Device test finished on ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/62509094058a2d4_Make_CI_build_and_unit_tests_pass_vjrantal/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:0 
child process exited with code 0 on device LGH8153b36be34 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/62509094058a2d4_Make_CI_build_and_unit_tests_pass_vjrantal/thali05_LGE-LG-H815.md)

####Node name: thali06
Console output:
```
STOP log received from  7970f88c Test has  FAILED
Device test finished on 7970f88c 
STOP log received from  FA55PYS00566 Test has  FAILED
Device test finished on FA55PYS00566 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62509094058a2d4_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/62509094058a2d4_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
STOP log received from  4db5c8cc Test has  FAILED
Device test finished on 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62509094058a2d4_Make_CI_build_and_unit_tests_pass_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
STOP log received from  4325e43f Test has  FAILED
Device test finished on 4325e43f 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62509094058a2d4_Make_CI_build_and_unit_tests_pass_vjrantal/thali08_samsung-SM-A300FU.md)





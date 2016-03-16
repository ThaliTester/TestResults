#### Test 62509094c3ee53f Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":8}}
2016-03-16T09:41:34.893Z - info: listening on *:3000

2016-03-16T09:41:35.473Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:0

2016-03-16T09:41:36.485Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:1

2016-03-16T09:41:36.488Z - info: Required number of ios devices presented (2)

2016-03-16T09:41:36.492Z - info: Starting unit test run for platform: ios

2016-03-16T09:41:37.147Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:2

2016-03-16T09:41:37.148Z - info: Discarding surplus device: Apple-Iphone6-1

2016-03-16T09:41:37.175Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-16T09:41:37.638Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:3

2016-03-16T09:41:37.651Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-16T09:41:38.005Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-16T09:41:38.229Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:4

2016-03-16T09:41:38.230Z - info: Required number of android devices presented (2)

2016-03-16T09:41:38.231Z - info: Starting unit test run for platform: android

2016-03-16T09:41:38.426Z - info: Running on ios test: 4. native server connections all up

2016-03-16T09:41:38.506Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:5

2016-03-16T09:41:38.507Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-16T09:41:38.719Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-16T09:41:38.859Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-16T09:41:39.134Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-16T09:41:39.308Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-16T09:41:39.557Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-16T09:41:39.747Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-16T09:41:39.864Z - debug: Socket disconnected: transport close 2 (Apple-Iphone6-1)

2016-03-16T09:41:39.998Z - info: Running on android test: 4. native server connections all up

2016-03-16T09:41:40.198Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-16T09:41:40.475Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-16T09:41:40.622Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-16T09:41:40.936Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-16T09:41:41.314Z - debug: Socket disconnected: transport close 5 (Apple-Iphone5s-1)

2016-03-16T09:41:41.401Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-16T09:41:41.611Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-16T09:41:41.922Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-16T09:41:42.115Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-16T09:41:42.341Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-16T09:41:42.513Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-16T09:41:42.889Z - info: Running on ios test: 13. closeAll with promise

2016-03-16T09:41:43.173Z - info: Running on ios test: 14. multiplex can send data

2016-03-16T09:41:43.297Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-16T09:41:43.522Z - info: Running on ios test: 15. enqueue and run in order

2016-03-16T09:41:43.691Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-16T09:41:44.072Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-16T09:41:44.076Z - info: Running on ios test: 16. enqueueAtTop and run backwards

2016-03-16T09:41:44.505Z - info: Running on android test: 13. closeAll with promise

2016-03-16T09:41:44.511Z - info: Running on ios test: 17. mix enqueue and enqueueAtTop

2016-03-16T09:41:44.967Z - info: Running on android test: 14. multiplex can send data

2016-03-16T09:41:44.974Z - info: Running on ios test: 18. queues handled independently

2016-03-16T09:41:45.271Z - info: Running on ios test: 19. basic

2016-03-16T09:41:45.325Z - info: Running on android test: 15. enqueue and run in order

2016-03-16T09:41:45.654Z - info: Running on ios test: 20. another

2016-03-16T09:41:45.944Z - info: Running on ios test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-16T09:41:46.093Z - info: Running on android test: 16. enqueueAtTop and run backwards

2016-03-16T09:41:46.212Z - info: Running on ios test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-16T09:41:46.600Z - info: Running on android test: 17. mix enqueue and enqueueAtTop

2016-03-16T09:41:46.607Z - info: Running on ios test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-16T09:41:47.010Z - info: Running on ios test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-16T09:41:47.171Z - info: Running on android test: 18. queues handled independently

2016-03-16T09:41:47.400Z - info: Running on ios test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-16T09:41:47.626Z - info: Running on android test: 19. basic

2016-03-16T09:41:47.805Z - info: Running on ios test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-16T09:41:47.889Z - info: Running on android test: 20. another

2016-03-16T09:41:48.065Z - info: Running on ios test: 27. #start should fail if called twice in a row

2016-03-16T09:41:48.187Z - info: Running on android test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-16T09:41:48.396Z - info: Running on ios test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-16T09:41:48.626Z - info: Running on android test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-16T09:41:48.669Z - info: Running on ios test: 29. does not send duplicate availability changes

2016-03-16T09:41:48.892Z - info: Running on android test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-16T09:41:48.919Z - info: Running on ios test: 30. can get the network status

2016-03-16T09:41:49.258Z - info: Running on ios test: 31. wifi peer is marked unavailable if announcements stop

2016-03-16T09:41:49.290Z - info: Running on android test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-16T09:41:49.651Z - info: Running on android test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-16T09:41:49.939Z - debug: Device presented: HTC-HTC One M8s (android) unittest socket:6

2016-03-16T09:41:49.941Z - info: Discarding surplus device: HTC-HTC One M8s

2016-03-16T09:41:50.103Z - info: Running on android test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-16T09:41:50.473Z - info: Running on android test: 27. #start should fail if called twice in a row

2016-03-16T09:41:50.812Z - info: Running on android test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-16T09:41:50.817Z - info: Running on ios test: 32. Can call start/stopListeningForAdvertisements

2016-03-16T09:41:51.283Z - info: Running on android test: 29. does not send duplicate availability changes

2016-03-16T09:41:51.396Z - debug: Socket disconnected: transport close 6 (HTC-HTC One M8s)

2016-03-16T09:41:51.679Z - info: Running on android test: 30. can get the network status

2016-03-16T09:41:52.086Z - info: Running on android test: 31. wifi peer is marked unavailable if announcements stop

2016-03-16T09:41:52.994Z - info: Running on ios test: 33. Calling startListeningForAdvertisements twice is NOT an error

2016-03-16T09:41:53.448Z - info: Running on android test: 32. Can call start/stopListeningForAdvertisements

2016-03-16T09:41:53.634Z - info: Running on ios test: 34. Can call start/stopUpdateAdvertisingAndListening

2016-03-16T09:41:55.119Z - info: Running on ios test: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-16T09:41:55.440Z - info: Running on android test: 33. Calling startListeningForAdvertisements twice is NOT an error

2016-03-16T09:41:56.026Z - info: Running on ios test: 36. peerAvailabilityChange is called

2016-03-16T09:41:56.102Z - info: Running on android test: 34. Can call start/stopUpdateAdvertisingAndListening

2016-03-16T09:41:58.609Z - info: Running on ios test: 37. Can connect to a remote peer

2016-03-16T09:42:00.313Z - info: Running on android test: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-16T09:42:07.259Z - info: Running on android test: 36. peerAvailabilityChange is called

2016-03-16T09:59:48.978Z - debug: Socket disconnected: transport close 0 (Apple-Iphone5-1)

2016-03-16T09:59:48.998Z - debug: Socket disconnected: transport close 1 (Apple-IpadAir2-1)

2016-03-16T10:02:02.221Z - debug: Socket disconnected: transport close 3 (samsung-SM-N910C)

2016-03-16T10:02:04.430Z - debug: Socket disconnected: transport close 4 (LGE-LG-H815)


 
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
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/62509094c3ee53f_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/62509094c3ee53f_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/62509094c3ee53f_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/62509094c3ee53f_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/62509094c3ee53f_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  f56ad48d Test has  FAILED
Device test finished on f56ad48d 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62509094c3ee53f_Make_CI_build_and_unit_tests_pass_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/62509094c3ee53f_Make_CI_build_and_unit_tests_pass_vjrantal/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
STOP log received from  ZX1C223JKW Test has  FAILED
Device test finished on ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/62509094c3ee53f_Make_CI_build_and_unit_tests_pass_vjrantal/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:0 
child process exited with code 0 on device LGH8153b36be34 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/62509094c3ee53f_Make_CI_build_and_unit_tests_pass_vjrantal/thali05_LGE-LG-H815.md)

####Node name: thali06
Console output:
```
STOP log received from  7970f88c Test has  FAILED
Device test finished on 7970f88c 
STOP log received from  FA55PYS00566 Test has  SUCCEEDED
Device test finished on FA55PYS00566 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62509094c3ee53f_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/62509094c3ee53f_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
STOP log received from  4db5c8cc Test has  FAILED
Device test finished on 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62509094c3ee53f_Make_CI_build_and_unit_tests_pass_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
STOP log received from  4325e43f Test has  FAILED
Device test finished on 4325e43f 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62509094c3ee53f_Make_CI_build_and_unit_tests_pass_vjrantal/thali08_samsung-SM-A300FU.md)





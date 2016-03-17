#### Test 62509094141ff10 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":6}}
2016-03-17T10:19:31.030Z - info: listening on *:3000

2016-03-17T10:19:33.998Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:0

2016-03-17T10:19:34.418Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:1

2016-03-17T10:19:34.420Z - info: Required number of ios devices presented (2)

2016-03-17T10:19:34.424Z - info: Starting unit test run for platform: ios

2016-03-17T10:19:34.497Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:3

2016-03-17T10:19:34.499Z - info: Discarding surplus device: Apple-IpadAir2-1

2016-03-17T10:19:34.526Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:2

2016-03-17T10:19:34.527Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-17T10:19:34.696Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:4

2016-03-17T10:19:35.057Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-17T10:19:35.539Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-17T10:19:35.653Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:5

2016-03-17T10:19:35.654Z - info: Required number of android devices presented (2)

2016-03-17T10:19:35.656Z - info: Starting unit test run for platform: android

2016-03-17T10:19:36.110Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-17T10:19:36.278Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-17T10:19:36.477Z - info: Running on ios test: 4. native server connections all up

2016-03-17T10:19:36.727Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-17T10:19:36.876Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-17T10:19:37.100Z - debug: Socket disconnected: transport close 2 (Apple-Iphone5s-1)

2016-03-17T10:19:37.150Z - debug: Socket disconnected: transport close 3 (Apple-IpadAir2-1)

2016-03-17T10:19:37.158Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-17T10:19:37.375Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-17T10:19:37.603Z - info: Running on android test: 4. native server connections all up

2016-03-17T10:19:37.849Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-17T10:19:38.123Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-17T10:19:38.372Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-17T10:19:38.562Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-17T10:19:38.779Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-17T10:19:39.030Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-17T10:19:39.440Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-17T10:19:39.720Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-17T10:19:39.832Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-17T10:19:40.738Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-17T10:19:41.227Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-17T10:19:41.420Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-17T10:19:41.672Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-17T10:19:41.833Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-17T10:19:42.070Z - info: Running on android test: 13. closeAll with promise

2016-03-17T10:19:42.299Z - info: Running on ios test: 13. closeAll with promise

2016-03-17T10:19:42.559Z - info: Running on android test: 14. multiplex can send data

2016-03-17T10:19:42.754Z - info: Running on ios test: 14. multiplex can send data

2016-03-17T10:19:43.055Z - info: Running on android test: 15. enqueue and run in order

2016-03-17T10:19:43.385Z - info: Running on ios test: 15. enqueue and run in order

2016-03-17T10:19:44.151Z - info: Running on android test: 16. enqueueAtTop and run backwards

2016-03-17T10:19:44.647Z - info: Running on android test: 17. mix enqueue and enqueueAtTop

2016-03-17T10:19:44.671Z - info: Running on ios test: 16. enqueueAtTop and run backwards

2016-03-17T10:19:45.074Z - info: Running on ios test: 17. mix enqueue and enqueueAtTop

2016-03-17T10:19:45.230Z - info: Running on android test: 18. queues handled independently

2016-03-17T10:19:45.588Z - info: Running on ios test: 18. queues handled independently

2016-03-17T10:19:45.643Z - info: Running on android test: 19. basic

2016-03-17T10:19:45.935Z - info: Running on ios test: 19. basic

2016-03-17T10:19:45.981Z - info: Running on android test: 20. another

2016-03-17T10:19:46.212Z - info: Running on ios test: 20. another

2016-03-17T10:19:46.281Z - info: Running on android test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-17T10:19:46.481Z - info: Running on ios test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-17T10:19:46.603Z - info: Running on android test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-17T10:19:46.756Z - info: Running on ios test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-17T10:19:46.888Z - info: Running on android test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-17T10:19:47.143Z - info: Running on ios test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-17T10:19:47.281Z - info: Running on android test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-17T10:19:47.519Z - info: Running on ios test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-17T10:19:47.759Z - info: Running on android test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-17T10:19:47.880Z - info: Running on ios test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-17T10:19:48.235Z - info: Running on android test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-17T10:19:48.370Z - info: Running on ios test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-17T10:19:48.631Z - info: Running on android test: 27. #start should fail if called twice in a row

2016-03-17T10:19:48.719Z - info: Running on ios test: 27. #start should fail if called twice in a row

2016-03-17T10:19:49.038Z - info: Running on android test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-17T10:19:49.093Z - info: Running on ios test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-17T10:19:49.556Z - info: Running on ios test: 29. does not send duplicate availability changes

2016-03-17T10:19:49.949Z - info: Running on ios test: 30. can get the network status

2016-03-17T10:19:49.956Z - info: Running on android test: 29. does not send duplicate availability changes

2016-03-17T10:19:50.275Z - info: Running on ios test: 31. wifi peer is marked unavailable if announcements stop

2016-03-17T10:19:50.279Z - info: Running on android test: 30. can get the network status

2016-03-17T10:19:50.500Z - info: Running on android test: 31. wifi peer is marked unavailable if announcements stop

2016-03-17T10:19:51.549Z - info: Running on ios test: 32. Can call start/stopListeningForAdvertisements

2016-03-17T10:19:51.934Z - info: Running on android test: 32. Can call start/stopListeningForAdvertisements

2016-03-17T10:19:52.132Z - info: Running on ios test: 33. Calling startListeningForAdvertisements twice is NOT an error

2016-03-17T10:19:52.786Z - info: Running on ios test: 34. Can call start/stopUpdateAdvertisingAndListening

2016-03-17T10:19:52.885Z - info: Running on android test: 33. Calling startListeningForAdvertisements twice is NOT an error

2016-03-17T10:19:53.420Z - info: Running on android test: 34. Can call start/stopUpdateAdvertisingAndListening

2016-03-17T10:19:54.273Z - info: Running on ios test: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-17T10:19:54.874Z - info: Running on ios test: 36. peerAvailabilityChange is called

2016-03-17T10:19:57.465Z - info: Running on android test: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-17T10:19:59.467Z - info: Running on ios test: 37. Can connect to a remote peer

2016-03-17T10:20:04.348Z - info: Running on android test: 36. peerAvailabilityChange is called

2016-03-17T10:20:17.465Z - info: Running on ios test: 38. Can shift large amounts of data

2016-03-17T10:38:19.409Z - debug: Socket disconnected: transport close 1 (Apple-Iphone6-1)

2016-03-17T10:38:19.417Z - debug: Socket disconnected: transport close 0 (Apple-Iphone5-1)

2016-03-17T10:40:05.522Z - debug: Socket disconnected: transport close 5 (LGE-LG-H815)

2016-03-17T10:40:09.854Z - debug: Socket disconnected: transport close 4 (samsung-SM-N910C)


 
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
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/62509094141ff10_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/62509094141ff10_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/62509094141ff10_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/62509094141ff10_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/62509094141ff10_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_server.md)


###Android Logs
####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/62509094141ff10_Make_CI_build_and_unit_tests_pass_vjrantal/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on ZX1C223JKW 
Android task is completed. [SUCCESS]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/62509094141ff10_Make_CI_build_and_unit_tests_pass_vjrantal/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:0 
child process exited with code 0 on device LGH8153b36be34 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/62509094141ff10_Make_CI_build_and_unit_tests_pass_vjrantal/thali05_LGE-LG-H815.md)

####Node name: thali06
Console output:
```
STOP log received from  7970f88c Test has  SUCCEEDED
Device test finished on 7970f88c 
STOP log received from  FA55PYS00566 Test has  SUCCEEDED
Device test finished on FA55PYS00566 
Android task is completed. [SUCCESS]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62509094141ff10_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/62509094141ff10_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_HTC-HTC One M8s.md)

####Node name: thali08
Console output:
```
STOP log received from  4325e43f Test has  SUCCEEDED
Device test finished on 4325e43f 
Android task is completed. [SUCCESS]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62509094141ff10_Make_CI_build_and_unit_tests_pass_vjrantal/thali08_samsung-SM-A300FU.md)





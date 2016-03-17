#### Test 62509094b685d58 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":8}}
2016-03-17T11:31:15.222Z - info: listening on *:3000

2016-03-17T11:31:16.055Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:0

2016-03-17T11:31:16.305Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:1

2016-03-17T11:31:16.308Z - info: Required number of ios devices presented (2)

2016-03-17T11:31:16.311Z - info: Starting unit test run for platform: ios

2016-03-17T11:31:16.352Z - debug: Device presented: samsung-SM-A500FU (android) unittest socket:2

2016-03-17T11:31:16.831Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:3

2016-03-17T11:31:16.832Z - info: Discarding surplus device: Apple-Iphone5-1

2016-03-17T11:31:16.847Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-17T11:31:17.121Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-17T11:31:17.452Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-17T11:31:17.754Z - info: Running on ios test: 4. native server connections all up

2016-03-17T11:31:18.147Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-17T11:31:18.194Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:4

2016-03-17T11:31:18.196Z - info: Required number of android devices presented (2)

2016-03-17T11:31:18.197Z - info: Starting unit test run for platform: android

2016-03-17T11:31:18.386Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:5

2016-03-17T11:31:18.387Z - info: Discarding surplus device: Apple-Iphone6-1

2016-03-17T11:31:18.474Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-17T11:31:18.783Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-17T11:31:18.805Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-17T11:31:19.160Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-17T11:31:19.206Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-17T11:31:19.258Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:6

2016-03-17T11:31:19.269Z - info: Discarding surplus device: samsung-SM-N910C

2016-03-17T11:31:19.495Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-17T11:31:19.599Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-17T11:31:19.792Z - info: Running on android test: 4. native server connections all up

2016-03-17T11:31:19.861Z - debug: Socket disconnected: transport close 3 (Apple-Iphone5-1)

2016-03-17T11:31:20.213Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-17T11:31:20.379Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-17T11:31:20.495Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-17T11:31:20.771Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-17T11:31:21.033Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-17T11:31:21.042Z - debug: Socket disconnected: transport close 5 (Apple-Iphone6-1)

2016-03-17T11:31:21.411Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-17T11:31:21.885Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-17T11:31:22.315Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-17T11:31:22.319Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-17T11:31:22.649Z - info: Running on ios test: 13. closeAll with promise

2016-03-17T11:31:22.677Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-17T11:31:22.992Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-17T11:31:23.113Z - info: Running on ios test: 14. multiplex can send data

2016-03-17T11:31:23.413Z - info: Running on android test: 13. closeAll with promise

2016-03-17T11:31:23.492Z - info: Running on ios test: 15. enqueue and run in order

2016-03-17T11:31:23.695Z - info: Running on android test: 14. multiplex can send data

2016-03-17T11:31:23.935Z - info: Running on android test: 15. enqueue and run in order

2016-03-17T11:31:23.990Z - info: Running on ios test: 16. enqueueAtTop and run backwards

2016-03-17T11:31:24.293Z - info: Running on ios test: 17. mix enqueue and enqueueAtTop

2016-03-17T11:31:24.658Z - info: Running on ios test: 18. queues handled independently

2016-03-17T11:31:24.724Z - info: Running on android test: 16. enqueueAtTop and run backwards

2016-03-17T11:31:24.953Z - info: Running on ios test: 19. basic

2016-03-17T11:31:25.093Z - info: Running on android test: 17. mix enqueue and enqueueAtTop

2016-03-17T11:31:25.185Z - info: Running on ios test: 20. another

2016-03-17T11:31:25.459Z - info: Running on ios test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-17T11:31:25.480Z - info: Running on android test: 18. queues handled independently

2016-03-17T11:31:25.703Z - info: Running on android test: 19. basic

2016-03-17T11:31:25.713Z - info: Running on ios test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-17T11:31:25.904Z - info: Running on android test: 20. another

2016-03-17T11:31:25.989Z - info: Running on ios test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-17T11:31:26.114Z - info: Running on android test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-17T11:31:26.261Z - info: Running on ios test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-17T11:31:26.384Z - info: Running on android test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-17T11:31:26.634Z - info: Running on ios test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-17T11:31:26.691Z - info: Running on android test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-17T11:31:26.924Z - info: Running on android test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-17T11:31:27.070Z - info: Running on ios test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-17T11:31:27.265Z - info: Running on android test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-17T11:31:27.345Z - info: Running on ios test: 27. #start should fail if called twice in a row

2016-03-17T11:31:27.612Z - info: Running on android test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-17T11:31:27.669Z - info: Running on ios test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-17T11:31:27.897Z - info: Running on android test: 27. #start should fail if called twice in a row

2016-03-17T11:31:27.992Z - info: Running on ios test: 29. does not send duplicate availability changes

2016-03-17T11:31:28.184Z - info: Running on android test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-17T11:31:28.410Z - info: Running on ios test: 30. can get the network status

2016-03-17T11:31:28.609Z - info: Running on android test: 29. does not send duplicate availability changes

2016-03-17T11:31:28.699Z - info: Running on ios test: 31. wifi peer is marked unavailable if announcements stop

2016-03-17T11:31:28.805Z - info: Running on android test: 30. can get the network status

2016-03-17T11:31:28.990Z - info: Running on android test: 31. wifi peer is marked unavailable if announcements stop

2016-03-17T11:31:30.033Z - info: Running on ios test: 32. Can call start/stopListeningForAdvertisements

2016-03-17T11:31:30.277Z - info: Running on android test: 32. Can call start/stopListeningForAdvertisements

2016-03-17T11:31:30.537Z - info: Running on ios test: 33. Calling startListeningForAdvertisements twice is NOT an error

2016-03-17T11:31:30.787Z - info: Running on android test: 33. Calling startListeningForAdvertisements twice is NOT an error

2016-03-17T11:31:32.289Z - info: Running on ios test: 34. Can call start/stopUpdateAdvertisingAndListening

2016-03-17T11:31:32.809Z - info: Running on android test: 34. Can call start/stopUpdateAdvertisingAndListening

2016-03-17T11:31:33.090Z - info: Running on ios test: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-17T11:31:34.862Z - info: Running on android test: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-17T11:31:34.930Z - info: Running on ios test: 36. peerAvailabilityChange is called

2016-03-17T11:31:35.594Z - info: Running on android test: 36. peerAvailabilityChange is called

2016-03-17T11:31:38.522Z - info: Running on ios test: 37. Can connect to a remote peer

2016-03-17T11:31:41.380Z - info: Running on android test: 37. Can connect to a remote peer

2016-03-17T11:49:41.680Z - debug: Socket disconnected: transport close 1 (Apple-IpadAir2-1)

2016-03-17T11:49:41.688Z - debug: Socket disconnected: transport close 0 (Apple-Iphone5s-1)

2016-03-17T11:51:56.322Z - debug: Socket disconnected: transport close 4 (LGE-LG-H815)


 
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
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/62509094b685d58_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/62509094b685d58_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/62509094b685d58_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/62509094b685d58_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/62509094b685d58_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:0 
child process exited with code 0 on device f56ad48d 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62509094b685d58_Make_CI_build_and_unit_tests_pass_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali03
Console output:
```
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:0 
child process exited with code 0 on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/62509094b685d58_Make_CI_build_and_unit_tests_pass_vjrantal/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on ZX1C223JKW 
Android task is completed. [SUCCESS]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/62509094b685d58_Make_CI_build_and_unit_tests_pass_vjrantal/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:0 
child process exited with code 0 on device LGH8153b36be34 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/62509094b685d58_Make_CI_build_and_unit_tests_pass_vjrantal/thali05_LGE-LG-H815.md)

####Node name: thali06
Console output:
```
STOP log received from  7970f88c Test has  SUCCEEDED
STOP log received from  FA55PYS00566 Test has  SUCCEEDED
Device test finished on 7970f88c 
Device test finished on FA55PYS00566 
Android task is completed. [SUCCESS]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62509094b685d58_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/62509094b685d58_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
STOP log received from  4db5c8cc Test has  SUCCEEDED
Device test finished on 4db5c8cc 
Android task is completed. [SUCCESS]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62509094b685d58_Make_CI_build_and_unit_tests_pass_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
STOP log received from  4325e43f Test has  SUCCEEDED
Device test finished on 4325e43f 
Android task is completed. [SUCCESS]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62509094b685d58_Make_CI_build_and_unit_tests_pass_vjrantal/thali08_samsung-SM-A300FU.md)





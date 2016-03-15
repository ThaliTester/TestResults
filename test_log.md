#### Test 625481247d7767b Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":8}}
2016-03-15T14:04:07.755Z - info: listening on *:3000

2016-03-15T14:04:09.943Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:0

2016-03-15T14:04:10.786Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:1

2016-03-15T14:04:10.789Z - info: Required number of ios devices presented (2)

2016-03-15T14:04:10.793Z - info: Starting unit test run for platform: ios

2016-03-15T14:04:10.847Z - debug: Device presented: motorola-XT1072 (android) unittest socket:2

2016-03-15T14:04:10.854Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:3

2016-03-15T14:04:10.855Z - info: Discarding surplus device: Apple-Iphone5-1

2016-03-15T14:04:11.308Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-15T14:04:11.993Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-15T14:04:12.544Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:4

2016-03-15T14:04:12.545Z - info: Required number of android devices presented (2)

2016-03-15T14:04:12.546Z - info: Starting unit test run for platform: android

2016-03-15T14:04:12.688Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-15T14:04:12.710Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:5

2016-03-15T14:04:12.711Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-15T14:04:13.105Z - info: Running on ios test: 4. native server connections all up

2016-03-15T14:04:13.456Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-15T14:04:13.679Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-15T14:04:14.074Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-15T14:04:14.182Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-15T14:04:14.481Z - debug: Socket disconnected: transport close 3 (Apple-Iphone5-1)

2016-03-15T14:04:14.825Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-15T14:04:14.900Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-15T14:04:15.495Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-15T14:04:15.585Z - debug: Socket disconnected: transport close 5 (Apple-Iphone5s-1)

2016-03-15T14:04:15.638Z - info: Running on android test: 4. native server connections all up

2016-03-15T14:04:16.078Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-15T14:04:16.677Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-15T14:04:17.067Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-15T14:04:17.229Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-15T14:04:17.655Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-15T14:04:17.785Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-15T14:04:18.091Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-15T14:04:18.241Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-15T14:04:18.424Z - info: Running on ios test: 13. closeAll with promise

2016-03-15T14:04:18.721Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-15T14:04:18.769Z - info: Running on ios test: 14. multiplex can send data

2016-03-15T14:04:19.152Z - info: Running on ios test: 15. enqueue and run in order

2016-03-15T14:04:19.594Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-15T14:04:19.930Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-15T14:04:20.785Z - info: Running on ios test: 16. enqueueAtTop and run backwards

2016-03-15T14:04:20.885Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-15T14:04:22.241Z - info: Running on ios test: 17. mix enqueue and enqueueAtTop

2016-03-15T14:04:22.445Z - info: Running on android test: 13. closeAll with promise

2016-03-15T14:04:22.690Z - info: Running on ios test: 18. queues handled independently

2016-03-15T14:04:22.904Z - info: Running on android test: 14. multiplex can send data

2016-03-15T14:04:23.168Z - info: Running on ios test: 19. basic

2016-03-15T14:04:23.596Z - info: Running on android test: 15. enqueue and run in order

2016-03-15T14:04:23.837Z - info: Running on ios test: 20. another

2016-03-15T14:04:24.386Z - info: Running on ios test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-15T14:04:24.821Z - info: Running on ios test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-15T14:04:25.083Z - info: Running on android test: 16. enqueueAtTop and run backwards

2016-03-15T14:04:25.336Z - info: Running on ios test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-15T14:04:25.750Z - info: Running on android test: 17. mix enqueue and enqueueAtTop

2016-03-15T14:04:26.023Z - info: Running on ios test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-15T14:04:26.454Z - info: Running on android test: 18. queues handled independently

2016-03-15T14:04:26.618Z - info: Running on ios test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-15T14:04:27.396Z - info: Running on android test: 19. basic

2016-03-15T14:04:28.295Z - info: Running on ios test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-15T14:04:28.541Z - info: Running on android test: 20. another

2016-03-15T14:04:28.964Z - info: Running on android test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-15T14:04:29.245Z - info: Running on ios test: 27. #start should fail if called twice in a row

2016-03-15T14:04:29.505Z - info: Running on android test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-15T14:04:30.118Z - info: Running on android test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-15T14:04:30.129Z - info: Running on ios test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-15T14:04:30.723Z - info: Running on android test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-15T14:04:30.785Z - info: Running on ios test: 29. does not send duplicate availability changes

2016-03-15T14:04:31.379Z - info: Running on ios test: 30. can get the network status

2016-03-15T14:04:32.193Z - debug: Socket disconnected: transport close 4 (LGE-LG-H815)

2016-03-15T14:04:34.406Z - info: Running on ios test: 31. wifi peer is marked unavailable if announcements stop

2016-03-15T14:04:36.791Z - info: Running on ios test: 32. Can call start/stopListeningForAdvertisements

2016-03-15T14:04:38.141Z - info: Running on ios test: 33. Calling startListeningForAdvertisements twice is NOT an error

2016-03-15T14:04:39.461Z - info: Running on ios test: 34. Can call start/stopUpdateAdvertisingAndListening

2016-03-15T14:04:40.285Z - info: Running on ios test: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-15T14:04:42.215Z - info: Running on ios test: 36. peerAvailabilityChange is called

2016-03-15T14:04:45.021Z - info: Running on ios test: 37. Can connect to a remote peer

2016-03-15T14:21:58.426Z - debug: Socket disconnected: transport close 0 (Apple-Iphone6-1)

2016-03-15T14:21:58.434Z - debug: Socket disconnected: transport close 1 (Apple-IpadAir2-1)

2016-03-15T14:25:14.005Z - debug: Socket disconnected: transport close 2 (motorola-XT1072)


 
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
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/625481247d7767b_More_thaliMobileNativeWrapper_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/625481247d7767b_More_thaliMobileNativeWrapper_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/625481247d7767b_More_thaliMobileNativeWrapper_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/625481247d7767b_More_thaliMobileNativeWrapper_vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/625481247d7767b_More_thaliMobileNativeWrapper_vjrantal/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:0 
child process exited with code 0 on device f56ad48d 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/625481247d7767b_More_thaliMobileNativeWrapper_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/625481247d7767b_More_thaliMobileNativeWrapper_vjrantal/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/625481247d7767b_More_thaliMobileNativeWrapper_vjrantal/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:0 
child process exited with code 0 on device LGH8153b36be34 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/625481247d7767b_More_thaliMobileNativeWrapper_vjrantal/thali05_LGE-LG-H815.md)

####Node name: thali06
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:null 
child process exited with code null on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:null 
child process exited with code null on device FA55PYS00566 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/625481247d7767b_More_thaliMobileNativeWrapper_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/625481247d7767b_More_thaliMobileNativeWrapper_vjrantal/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:0 
child process exited with code 0 on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/625481247d7767b_More_thaliMobileNativeWrapper_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:0 
child process exited with code 0 on device 4325e43f 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/625481247d7767b_More_thaliMobileNativeWrapper_vjrantal/thali08_samsung-SM-A300FU.md)





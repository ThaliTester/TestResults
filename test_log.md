#### Test 625481246b04bc0 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":8}}
2016-03-15T11:48:21.782Z - info: listening on *:3000

2016-03-15T11:48:22.453Z - debug: Device presented: samsung-SM-A300FU (android) unittest socket:0

2016-03-15T11:48:23.431Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:1

2016-03-15T11:48:23.434Z - info: Required number of android devices presented (2)

2016-03-15T11:48:23.437Z - info: Starting unit test run for platform: android

2016-03-15T11:48:24.224Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-15T11:48:24.811Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-15T11:48:24.862Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:2

2016-03-15T11:48:24.973Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:3

2016-03-15T11:48:24.975Z - info: Required number of ios devices presented (2)

2016-03-15T11:48:24.976Z - info: Starting unit test run for platform: ios

2016-03-15T11:48:25.188Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-15T11:48:25.449Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-15T11:48:25.727Z - info: Running on android test: 4. native server connections all up

2016-03-15T11:48:25.932Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-15T11:48:26.048Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-15T11:48:26.299Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-15T11:48:26.554Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-15T11:48:26.773Z - info: Running on ios test: 4. native server connections all up

2016-03-15T11:48:26.851Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:4

2016-03-15T11:48:26.852Z - info: Discarding surplus device: Apple-Iphone6-1

2016-03-15T11:48:27.162Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-15T11:48:27.176Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:5

2016-03-15T11:48:27.186Z - info: Discarding surplus device: Apple-Iphone5-1

2016-03-15T11:48:27.340Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-15T11:48:27.672Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-15T11:48:27.857Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-15T11:48:28.144Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-15T11:48:28.252Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-15T11:48:28.607Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-15T11:48:28.966Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-15T11:48:29.078Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-15T11:48:29.353Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-15T11:48:29.534Z - debug: Socket disconnected: transport close 4 (Apple-Iphone6-1)

2016-03-15T11:48:29.680Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-15T11:48:29.804Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-15T11:48:30.115Z - info: Running on android test: 13. closeAll with promise

2016-03-15T11:48:30.440Z - debug: Socket disconnected: transport close 5 (Apple-Iphone5-1)

2016-03-15T11:48:30.589Z - info: Running on android test: 14. multiplex can send data

2016-03-15T11:48:30.993Z - info: Running on android test: 15. enqueue and run in order

2016-03-15T11:48:31.838Z - info: Running on android test: 16. enqueueAtTop and run backwards

2016-03-15T11:48:32.294Z - info: Running on android test: 17. mix enqueue and enqueueAtTop

2016-03-15T11:48:32.727Z - info: Running on android test: 18. queues handled independently

2016-03-15T11:48:33.001Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-15T11:48:33.089Z - info: Running on android test: 19. basic

2016-03-15T11:48:33.460Z - info: Running on android test: 20. another

2016-03-15T11:48:33.496Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-15T11:48:33.836Z - info: Running on android test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-15T11:48:33.953Z - info: Running on ios test: 13. closeAll with promise

2016-03-15T11:48:34.163Z - info: Running on android test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-15T11:48:34.309Z - info: Running on ios test: 14. multiplex can send data

2016-03-15T11:48:34.544Z - info: Running on android test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-15T11:48:34.665Z - info: Running on ios test: 15. enqueue and run in order

2016-03-15T11:48:35.389Z - info: Running on ios test: 16. enqueueAtTop and run backwards

2016-03-15T11:48:35.694Z - info: Running on ios test: 17. mix enqueue and enqueueAtTop

2016-03-15T11:48:36.123Z - debug: Socket disconnected: transport close 1 (LGE-LG-H815)

2016-03-15T11:48:36.482Z - info: Running on ios test: 18. queues handled independently

2016-03-15T11:48:36.849Z - info: Running on ios test: 19. basic

2016-03-15T11:48:37.159Z - info: Running on ios test: 20. another

2016-03-15T11:48:37.431Z - info: Running on ios test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-15T11:48:37.733Z - info: Running on ios test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-15T11:48:38.078Z - info: Running on ios test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-15T11:48:38.572Z - info: Running on ios test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-15T11:48:40.136Z - info: Running on ios test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-15T11:48:41.614Z - info: Running on ios test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-15T11:48:42.207Z - info: Running on ios test: 27. #start should fail if called twice in a row

2016-03-15T11:48:50.142Z - info: Running on ios test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-15T11:48:50.609Z - info: Running on ios test: 29. does not send duplicate availability changes

2016-03-15T11:48:51.186Z - info: Running on ios test: 30. can get the network status

2016-03-15T11:48:52.214Z - info: Running on ios test: 31. wifi peer is marked unavailable if announcements stop

2016-03-15T11:49:00.552Z - info: Running on ios test: 32. Can call start/stopListeningForAdvertisements

2016-03-15T11:49:01.205Z - info: Running on ios test: 33. Calling startListeningForAdvertisements twice is NOT an error

2016-03-15T11:49:01.824Z - info: Running on ios test: 34. Can call start/stopUpdateAdvertisingAndListening

2016-03-15T11:49:03.221Z - info: Running on ios test: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-15T11:49:03.719Z - info: Running on ios test: 36. peerAvailabilityChange is called

2016-03-15T11:49:06.208Z - info: Running on ios test: 37. Can connect to a remote peer

2016-03-15T11:49:12.314Z - info: Running on ios test: 38. Can shift large amounts of data

2016-03-15T12:06:14.354Z - debug: Socket disconnected: transport close 2 (Apple-IpadAir2-1)

2016-03-15T12:06:14.392Z - debug: Socket disconnected: transport close 3 (Apple-Iphone5s-1)


 
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
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/625481246b04bc0_More_thaliMobileNativeWrapper_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/625481246b04bc0_More_thaliMobileNativeWrapper_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/625481246b04bc0_More_thaliMobileNativeWrapper_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/625481246b04bc0_More_thaliMobileNativeWrapper_vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/625481246b04bc0_More_thaliMobileNativeWrapper_vjrantal/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:0 
child process exited with code 0 on device f56ad48d 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/625481246b04bc0_More_thaliMobileNativeWrapper_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/625481246b04bc0_More_thaliMobileNativeWrapper_vjrantal/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/625481246b04bc0_More_thaliMobileNativeWrapper_vjrantal/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:0 
child process exited with code 0 on device LGH8153b36be34 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/625481246b04bc0_More_thaliMobileNativeWrapper_vjrantal/thali05_LGE-LG-H815.md)

####Node name: thali06
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:0 
child process exited with code 0 on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:0 
child process exited with code 0 on device FA55PYS00566 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/625481246b04bc0_More_thaliMobileNativeWrapper_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/625481246b04bc0_More_thaliMobileNativeWrapper_vjrantal/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:0 
child process exited with code 0 on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/625481246b04bc0_More_thaliMobileNativeWrapper_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:0 
child process exited with code 0 on device 4325e43f 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/625481246b04bc0_More_thaliMobileNativeWrapper_vjrantal/thali08_samsung-SM-A300FU.md)





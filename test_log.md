#### Test 635253937ae73fc Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":8}}
2016-03-21T07:38:48.468Z - info: listening on *:3000

2016-03-21T07:38:49.661Z - debug: Device presented: HTC-HTC One M8s (android) unittest socket:0

2016-03-21T07:38:49.673Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:1

2016-03-21T07:38:49.676Z - info: Required number of android devices presented (2)

2016-03-21T07:38:49.680Z - info: Starting unit test run for platform: android

2016-03-21T07:38:50.100Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:2

2016-03-21T07:38:50.331Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:3

2016-03-21T07:38:50.332Z - info: Discarding surplus device: LGE-LG-H815

2016-03-21T07:38:50.783Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:4

2016-03-21T07:38:50.786Z - info: Required number of ios devices presented (2)

2016-03-21T07:38:50.787Z - info: Starting unit test run for platform: ios

2016-03-21T07:38:50.901Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-21T07:38:51.358Z - debug: Socket disconnected: transport close 3 (LGE-LG-H815)

2016-03-21T07:38:51.380Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-21T07:38:51.543Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-21T07:38:51.828Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-21T07:38:52.151Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-21T07:38:52.239Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-21T07:38:52.290Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:5

2016-03-21T07:38:52.291Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-21T07:38:52.659Z - info: Running on android test: 4. native server connections all up

2016-03-21T07:38:52.703Z - info: Running on ios test: 4. native server connections all up

2016-03-21T07:38:53.132Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-21T07:38:53.165Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-21T07:38:53.742Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-21T07:38:54.111Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-21T07:38:54.389Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:6

2016-03-21T07:38:54.393Z - info: Discarding surplus device: Apple-Iphone5-1

2016-03-21T07:38:54.950Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-21T07:38:55.090Z - debug: Socket disconnected: transport close 5 (Apple-Iphone5s-1)

2016-03-21T07:38:55.961Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-21T07:38:56.914Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-21T07:38:57.898Z - debug: Socket disconnected: transport close 6 (Apple-Iphone5-1)

2016-03-21T07:38:58.604Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-21T07:38:58.749Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-21T07:39:01.494Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-21T07:39:02.378Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-21T07:39:05.820Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-21T07:39:06.344Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-21T07:39:07.827Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-21T07:39:08.259Z - info: Running on ios test: 13. closeAll with promise

2016-03-21T07:39:08.614Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-21T07:39:08.666Z - info: Running on ios test: 14. multiplex can send data

2016-03-21T07:39:08.972Z - info: Running on ios test: 15. enqueue and run in order

2016-03-21T07:39:09.055Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-21T07:39:09.494Z - info: Running on android test: 13. closeAll with promise

2016-03-21T07:39:09.521Z - info: Running on ios test: 16. enqueueAtTop and run backwards

2016-03-21T07:39:09.754Z - info: Running on ios test: 17. mix enqueue and enqueueAtTop

2016-03-21T07:39:09.844Z - info: Running on android test: 14. multiplex can send data

2016-03-21T07:39:10.173Z - info: Running on ios test: 18. queues handled independently

2016-03-21T07:39:10.177Z - info: Running on android test: 15. enqueue and run in order

2016-03-21T07:39:10.531Z - info: Running on ios test: 19. basic

2016-03-21T07:39:10.759Z - info: Running on android test: 16. enqueueAtTop and run backwards

2016-03-21T07:39:10.831Z - info: Running on ios test: 20. another

2016-03-21T07:39:11.171Z - info: Running on ios test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-21T07:39:11.917Z - info: Running on ios test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-21T07:39:12.180Z - info: Running on android test: 17. mix enqueue and enqueueAtTop

2016-03-21T07:39:12.355Z - info: Running on ios test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-21T07:39:12.711Z - info: Running on ios test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-21T07:39:12.971Z - info: Running on ios test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-21T07:39:13.017Z - info: Running on android test: 18. queues handled independently

2016-03-21T07:39:13.352Z - info: Running on ios test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-21T07:39:13.541Z - info: Running on android test: 19. basic

2016-03-21T07:39:13.713Z - info: Running on ios test: 27. #start should fail if called twice in a row

2016-03-21T07:39:13.977Z - info: Running on android test: 20. another

2016-03-21T07:39:14.034Z - info: Running on ios test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-21T07:39:14.334Z - info: Running on ios test: 29. does not send duplicate availability changes

2016-03-21T07:39:14.402Z - info: Running on android test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-21T07:39:14.742Z - info: Running on ios test: 30. can get the network status

2016-03-21T07:39:15.000Z - info: Running on android test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-21T07:39:15.119Z - info: Running on ios test: 31. wifi peer is marked unavailable if announcements stop

2016-03-21T07:39:15.457Z - info: Running on android test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-21T07:39:16.612Z - info: Running on android test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-21T07:39:16.674Z - info: Running on ios test: 32. Can call start/stopListeningForAdvertisements

2016-03-21T07:39:17.205Z - info: Running on android test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-21T07:39:17.473Z - info: Running on ios test: 33. Calling startListeningForAdvertisements twice is NOT an error

2016-03-21T07:39:18.013Z - info: Running on android test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-21T07:39:19.356Z - info: Running on android test: 27. #start should fail if called twice in a row

2016-03-21T07:39:19.427Z - info: Running on ios test: 34. Can call start/stopUpdateAdvertisingAndListening

2016-03-21T07:39:20.003Z - info: Running on android test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-21T07:39:20.473Z - info: Running on ios test: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-21T07:39:21.260Z - info: Running on android test: 29. does not send duplicate availability changes

2016-03-21T07:39:21.586Z - info: Running on ios test: 36. peerAvailabilityChange is called

2016-03-21T07:39:21.864Z - info: Running on android test: 30. can get the network status

2016-03-21T07:39:22.486Z - info: Running on android test: 31. wifi peer is marked unavailable if announcements stop

2016-03-21T07:39:23.964Z - info: Running on android test: 32. Can call start/stopListeningForAdvertisements

2016-03-21T07:39:24.181Z - info: Running on ios test: 37. Can connect to a remote peer

2016-03-21T07:39:29.588Z - info: Running on android test: 33. Calling startListeningForAdvertisements twice is NOT an error

2016-03-21T07:39:36.116Z - info: Running on android test: 34. Can call start/stopUpdateAdvertisingAndListening

2016-03-21T07:39:39.623Z - info: Running on android test: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-21T07:39:46.270Z - info: Running on android test: 36. peerAvailabilityChange is called

2016-03-21T07:57:20.040Z - debug: Socket disconnected: transport close 2 (Apple-IpadAir2-1)

2016-03-21T07:57:20.078Z - debug: Socket disconnected: transport close 4 (Apple-Iphone6-1)

2016-03-21T07:59:44.768Z - debug: Socket disconnected: transport close 1 (samsung-SM-N910C)

2016-03-21T07:59:58.790Z - debug: Socket disconnected: transport close 0 (HTC-HTC One M8s)


 
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
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/635253937ae73fc_Adds_a_typedef_for_peerAvailabilityChanged_event_s_object_juhanak/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/635253937ae73fc_Adds_a_typedef_for_peerAvailabilityChanged_event_s_object_juhanak/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/635253937ae73fc_Adds_a_typedef_for_peerAvailabilityChanged_event_s_object_juhanak/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/635253937ae73fc_Adds_a_typedef_for_peerAvailabilityChanged_event_s_object_juhanak/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/635253937ae73fc_Adds_a_typedef_for_peerAvailabilityChanged_event_s_object_juhanak/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  f56ad48d Test has  SUCCEEDED
Device test finished on f56ad48d 
Android task is completed. [SUCCESS]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/635253937ae73fc_Adds_a_typedef_for_peerAvailabilityChanged_event_s_object_juhanak/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/635253937ae73fc_Adds_a_typedef_for_peerAvailabilityChanged_event_s_object_juhanak/thali02_LGE-LG-D722.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/635253937ae73fc_Adds_a_typedef_for_peerAvailabilityChanged_event_s_object_juhanak/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on ZX1C223JKW 
Android task is completed. [SUCCESS]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/635253937ae73fc_Adds_a_typedef_for_peerAvailabilityChanged_event_s_object_juhanak/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Android task is completed. [SUCCESS]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/635253937ae73fc_Adds_a_typedef_for_peerAvailabilityChanged_event_s_object_juhanak/thali05_LGE-LG-H815.md)

####Node name: thali06
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:0 
child process exited with code 0 on device FA55PYS00566 
Android task is completed. [FAILED]
```
[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/635253937ae73fc_Adds_a_typedef_for_peerAvailabilityChanged_event_s_object_juhanak/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
STOP log received from  4db5c8cc Test has  SUCCEEDED
Device test finished on 4db5c8cc 
Android task is completed. [SUCCESS]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/635253937ae73fc_Adds_a_typedef_for_peerAvailabilityChanged_event_s_object_juhanak/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
STOP log received from  4325e43f Test has  SUCCEEDED
Device test finished on 4325e43f 
Android task is completed. [SUCCESS]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/635253937ae73fc_Adds_a_typedef_for_peerAvailabilityChanged_event_s_object_juhanak/thali08_samsung-SM-A300FU.md)





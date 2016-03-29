#### Test 639981175e54a40 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-03-29T07:22:53.621Z - info: listening on *:3000

2016-03-29T07:22:55.477Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:0

2016-03-29T07:22:57.742Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:1

2016-03-29T07:22:58.257Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:3

2016-03-29T07:22:59.012Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:2

2016-03-29T07:22:59.013Z - info: Required number of ios devices presented (3)

2016-03-29T07:22:59.018Z - info: Starting unit test run for platform: ios

2016-03-29T07:23:00.721Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-29T07:23:00.933Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:4

2016-03-29T07:23:03.322Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-29T07:23:03.935Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-29T07:23:04.420Z - info: Running on ios test: 4. native server connections all up

2016-03-29T07:23:04.933Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-29T07:23:05.610Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-29T07:23:06.231Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-29T07:23:06.654Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-29T07:23:07.049Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-29T07:23:07.557Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:5

2016-03-29T07:23:07.559Z - info: Required number of android devices presented (3)

2016-03-29T07:23:07.560Z - info: Starting unit test run for platform: android

2016-03-29T07:23:08.352Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-29T07:23:08.803Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-29T07:23:09.284Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-29T07:23:09.864Z - info: Running on android test: 4. native server connections all up

2016-03-29T07:23:10.385Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-29T07:23:10.810Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-29T07:23:11.248Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-29T07:23:11.662Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-29T07:23:12.167Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-29T07:23:13.039Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-29T07:23:13.528Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-29T07:23:14.036Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-29T07:23:14.404Z - info: Running on android test: 13. closeAll with promise

2016-03-29T07:23:14.771Z - info: Running on android test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-03-29T07:23:15.231Z - info: Running on android test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-03-29T07:23:15.665Z - info: Running on android test: 16. multiplex can send data

2016-03-29T07:23:16.118Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-29T07:23:16.126Z - info: Running on android test: 17. enqueue and run in order

2016-03-29T07:23:16.719Z - info: Running on android test: 18. enqueueAtTop and run backwards

2016-03-29T07:23:17.169Z - info: Running on android test: 19. mix enqueue and enqueueAtTop

2016-03-29T07:23:17.673Z - info: Running on android test: 20. queues handled independently

2016-03-29T07:23:18.097Z - info: Running on android test: 21. basic

2016-03-29T07:23:18.148Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-29T07:23:18.485Z - info: Running on android test: 22. another

2016-03-29T07:23:18.607Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-29T07:23:18.842Z - info: Running on android test: 23. can pass data in setup

2016-03-29T07:23:19.135Z - info: Running on ios test: 13. closeAll with promise

2016-03-29T07:23:19.395Z - info: Running on android test: 24. #startListeningForAdvertisements should fail if start not called

2016-03-29T07:23:19.719Z - info: Running on ios test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-03-29T07:23:19.969Z - info: Running on android test: 25. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-29T07:23:20.204Z - info: Running on ios test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-03-29T07:23:20.382Z - info: Running on android test: 26. should be able to call #stopListeningForAdvertisements many times

2016-03-29T07:23:20.836Z - info: Running on android test: 27. should be able to call #startListeningForAdvertisements many times

2016-03-29T07:23:21.107Z - info: Running on ios test: 16. multiplex can send data

2016-03-29T07:23:21.514Z - info: Running on ios test: 17. enqueue and run in order

2016-03-29T07:23:21.579Z - info: Running on android test: 28. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-29T07:23:22.315Z - info: Running on ios test: 18. enqueueAtTop and run backwards

2016-03-29T07:23:22.648Z - info: Running on ios test: 19. mix enqueue and enqueueAtTop

2016-03-29T07:23:23.187Z - info: Running on ios test: 20. queues handled independently

2016-03-29T07:23:23.514Z - info: Running on ios test: 21. basic

2016-03-29T07:23:23.944Z - info: Running on ios test: 22. another

2016-03-29T07:23:24.433Z - info: Running on android test: 29. should be able to call #stopAdvertisingAndListening many times

2016-03-29T07:23:25.269Z - info: Running on ios test: 23. can pass data in setup

2016-03-29T07:23:25.772Z - info: Running on ios test: 24. #startListeningForAdvertisements should fail if start not called

2016-03-29T07:23:26.230Z - info: Running on ios test: 25. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-29T07:23:26.303Z - info: Running on android test: 30. #start should fail if called twice in a row

2016-03-29T07:23:26.579Z - info: Running on ios test: 26. should be able to call #stopListeningForAdvertisements many times

2016-03-29T07:23:26.904Z - info: Running on android test: 31. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-29T07:23:27.595Z - info: Running on ios test: 27. should be able to call #startListeningForAdvertisements many times

2016-03-29T07:23:28.629Z - info: Running on android test: 32. does not send duplicate availability changes

2016-03-29T07:23:28.755Z - info: Running on ios test: 28. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-29T07:23:29.078Z - info: Running on android test: 33. can get the network status

2016-03-29T07:23:30.033Z - info: Running on android test: 34. wifi peer is marked unavailable if announcements stop

2016-03-29T07:23:32.511Z - info: Running on ios test: 29. should be able to call #stopAdvertisingAndListening many times

2016-03-29T07:23:35.676Z - info: Running on android test: 35. Can call start/stopListeningForAdvertisements

2016-03-29T07:23:36.258Z - info: Running on android test: 36. Calling startListeningForAdvertisements twice is NOT an error

2016-03-29T07:23:37.123Z - info: Running on android test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-03-29T07:23:37.560Z - info: Running on ios test: 30. #start should fail if called twice in a row

2016-03-29T07:23:38.224Z - info: Running on ios test: 31. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-29T07:23:38.286Z - info: Running on android test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-29T07:23:39.769Z - info: Running on android test: 39. peerAvailabilityChange is called

2016-03-29T07:23:41.630Z - info: Running on android test: 40. Can connect to a remote peer

2016-03-29T07:23:41.634Z - info: Running on ios test: 32. does not send duplicate availability changes

2016-03-29T07:23:43.423Z - info: Running on ios test: 33. can get the network status

2016-03-29T07:23:44.907Z - info: Running on ios test: 34. wifi peer is marked unavailable if announcements stop

2016-03-29T07:23:47.232Z - info: Running on ios test: 35. Can call start/stopListeningForAdvertisements

2016-03-29T07:23:48.304Z - info: Running on ios test: 36. Calling startListeningForAdvertisements twice is NOT an error

2016-03-29T07:23:49.334Z - info: Running on android test: 41. Can shift large amounts of data

2016-03-29T07:23:52.124Z - info: Running on ios test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-03-29T07:24:18.389Z - debug: Socket disconnected: transport close 3 (Apple-Iphone6-1)

2016-03-29T07:42:21.948Z - debug: Socket disconnected: transport close 2 (Apple-Iphone5s-1)

2016-03-29T07:42:21.991Z - debug: Socket disconnected: transport close 0 (Apple-Iphone5-1)

2016-03-29T07:44:11.379Z - debug: Socket disconnected: transport close 1 (LGE-LG-H815)

2016-03-29T07:46:19.647Z - debug: Socket disconnected: transport close 4 (samsung-SM-N910C)

2016-03-29T07:46:21.491Z - debug: Socket disconnected: transport close 5 (motorola-Nexus 6)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m
2016-03-29T07:24:03.860Z - error: Too many emit retries to device: Apple-Iphone6-1

2016-03-29T07:24:03.864Z - error: Too many emit retries to device: Apple-Iphone5s-1


```


Logs for system : 
```

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code 254 on device 2a65f58f9902a701b5c9a55b2befb18672927474 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/639981175e54a40_More_tests_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/639981175e54a40_More_tests_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/639981175e54a40_More_tests_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/639981175e54a40_More_tests_vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/639981175e54a40_More_tests_vjrantal/iOS_server.md)


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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/639981175e54a40_More_tests_vjrantal/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/639981175e54a40_More_tests_vjrantal/thali07_LGE-LG-H815.md)

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
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/639981175e54a40_More_tests_vjrantal/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/639981175e54a40_More_tests_vjrantal/thali08_motorola-Nexus 6.md)





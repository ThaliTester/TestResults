#### Test 6391070405f2a33 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-03-24T14:29:09.663Z - info: listening on *:3000

2016-03-24T14:29:11.560Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:0

2016-03-24T14:29:13.222Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:2

2016-03-24T14:29:13.896Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:3

2016-03-24T14:29:15.507Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:1

2016-03-24T14:29:15.510Z - info: Required number of ios devices presented (3)

2016-03-24T14:29:15.514Z - info: Starting unit test run for platform: ios

2016-03-24T14:29:16.281Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-24T14:29:18.795Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-24T14:29:19.173Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-24T14:29:19.997Z - info: Running on ios test: 4. native server connections all up

2016-03-24T14:29:22.933Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-24T14:29:23.400Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-24T14:29:23.525Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:4

2016-03-24T14:29:23.835Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-24T14:29:24.240Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-24T14:29:24.687Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-24T14:29:28.437Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-24T14:29:29.160Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-24T14:29:29.695Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-24T14:29:30.153Z - info: Running on ios test: 13. closeAll with promise

2016-03-24T14:29:30.502Z - info: Running on ios test: 14. multiplex can send data

2016-03-24T14:29:30.906Z - info: Running on ios test: 15. enqueue and run in order

2016-03-24T14:29:31.608Z - info: Running on ios test: 16. enqueueAtTop and run backwards

2016-03-24T14:29:31.980Z - info: Running on ios test: 17. mix enqueue and enqueueAtTop

2016-03-24T14:29:32.381Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:5

2016-03-24T14:29:32.382Z - info: Required number of android devices presented (3)

2016-03-24T14:29:32.384Z - info: Starting unit test run for platform: android

2016-03-24T14:29:32.427Z - info: Running on ios test: 18. queues handled independently

2016-03-24T14:29:32.885Z - info: Running on ios test: 19. basic

2016-03-24T14:29:33.096Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-24T14:29:33.220Z - info: Running on ios test: 20. another

2016-03-24T14:29:33.630Z - info: Running on ios test: 21. can pass data in setup

2016-03-24T14:29:33.942Z - info: Running on ios test: 22. #startListeningForAdvertisements should fail if start not called

2016-03-24T14:29:34.284Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-24T14:29:34.288Z - info: Running on ios test: 23. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-24T14:29:34.713Z - info: Running on ios test: 24. should be able to call #stopListeningForAdvertisements many times

2016-03-24T14:29:34.884Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-24T14:29:35.093Z - info: Running on ios test: 25. should be able to call #startListeningForAdvertisements many times

2016-03-24T14:29:35.411Z - info: Running on android test: 4. native server connections all up

2016-03-24T14:29:35.611Z - info: Running on ios test: 26. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-24T14:29:35.965Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-24T14:29:36.415Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-24T14:29:36.582Z - info: Running on ios test: 27. should be able to call #stopAdvertisingAndListening many times

2016-03-24T14:29:37.411Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-24T14:29:41.890Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-24T14:29:47.718Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-24T14:30:02.809Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-24T14:30:16.938Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-24T14:30:18.897Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-24T14:30:19.542Z - info: Running on android test: 13. closeAll with promise

2016-03-24T14:30:19.970Z - info: Running on android test: 14. multiplex can send data

2016-03-24T14:30:20.401Z - info: Running on android test: 15. enqueue and run in order

2016-03-24T14:30:21.213Z - info: Running on android test: 16. enqueueAtTop and run backwards

2016-03-24T14:30:21.634Z - info: Running on android test: 17. mix enqueue and enqueueAtTop

2016-03-24T14:30:22.188Z - info: Running on android test: 18. queues handled independently

2016-03-24T14:30:22.614Z - info: Running on android test: 19. basic

2016-03-24T14:30:22.964Z - info: Running on android test: 20. another

2016-03-24T14:30:23.469Z - info: Running on android test: 21. can pass data in setup

2016-03-24T14:30:24.015Z - info: Running on android test: 22. #startListeningForAdvertisements should fail if start not called

2016-03-24T14:30:24.405Z - info: Running on android test: 23. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-24T14:30:24.921Z - info: Running on android test: 24. should be able to call #stopListeningForAdvertisements many times

2016-03-24T14:30:25.454Z - info: Running on android test: 25. should be able to call #startListeningForAdvertisements many times

2016-03-24T14:30:27.750Z - info: Running on android test: 26. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-24T14:30:30.110Z - info: Running on android test: 27. should be able to call #stopAdvertisingAndListening many times

2016-03-24T14:30:30.655Z - info: Running on android test: 28. #start should fail if called twice in a row

2016-03-24T14:30:31.091Z - info: Running on android test: 29. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-24T14:30:32.157Z - info: Running on android test: 30. does not send duplicate availability changes

2016-03-24T14:30:32.622Z - info: Running on android test: 31. can get the network status

2016-03-24T14:30:33.069Z - info: Running on android test: 32. wifi peer is marked unavailable if announcements stop

2016-03-24T14:30:35.459Z - info: Running on android test: 33. Can call start/stopListeningForAdvertisements

2016-03-24T14:30:35.890Z - info: Running on android test: 34. Calling startListeningForAdvertisements twice is NOT an error

2016-03-24T14:30:36.511Z - info: Running on android test: 35. Can call start/stopUpdateAdvertisingAndListening

2016-03-24T14:30:37.727Z - info: Running on android test: 36. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-24T14:30:38.577Z - info: Running on android test: 37. peerAvailabilityChange is called

2016-03-24T14:30:40.471Z - info: Running on android test: 38. Can connect to a remote peer

2016-03-24T14:30:46.576Z - info: Running on ios test: 28. #start should fail if called twice in a row

2016-03-24T14:30:47.121Z - info: Running on ios test: 29. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-24T14:30:47.806Z - info: Running on ios test: 30. does not send duplicate availability changes

2016-03-24T14:30:48.741Z - info: Running on ios test: 31. can get the network status

2016-03-24T14:30:51.068Z - info: Running on android test: 39. Can shift large amounts of data

2016-03-24T14:30:51.600Z - info: Running on ios test: 32. wifi peer is marked unavailable if announcements stop

2016-03-24T14:30:54.218Z - info: Running on ios test: 33. Can call start/stopListeningForAdvertisements

2016-03-24T14:30:55.212Z - info: Running on ios test: 34. Calling startListeningForAdvertisements twice is NOT an error

2016-03-24T14:31:05.483Z - info: Running on android test: 40. #startListeningForAdvertisements should fail if start not called

2016-03-24T14:31:23.236Z - info: Running on android test: 41. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-24T14:31:56.763Z - info: Running on ios test: 35. Can call start/stopUpdateAdvertisingAndListening

2016-03-24T14:32:58.975Z - debug: Socket disconnected: ping timeout 4 (samsung-SM-N910C)

2016-03-24T14:33:48.423Z - debug: Socket disconnected: ping timeout 3 (Apple-Iphone5-1)

2016-03-24T14:48:43.957Z - debug: Socket disconnected: transport close 2 (Apple-Iphone6-1)

2016-03-24T14:48:43.967Z - debug: Socket disconnected: transport close 1 (Apple-Iphone5s-1)

2016-03-24T14:48:44.010Z - debug: Socket disconnected: transport close 7 (NOT YET SET)

2016-03-24T14:50:29.333Z - debug: Socket disconnected: transport close 0 (LGE-LG-H815)

2016-03-24T14:52:43.220Z - debug: Socket disconnected: transport close 6 (NOT YET SET)

2016-03-24T14:52:45.043Z - debug: Socket disconnected: transport close 5 (motorola-Nexus 6)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m
2016-03-24T14:29:45.617Z - error: Too many emit retries to device: Apple-Iphone5-1

2016-03-24T14:29:45.620Z - error: Too many emit retries to device: Apple-Iphone5s-1

2016-03-24T14:30:02.243Z - error: Too many emit retries to device: Apple-Iphone5-1

2016-03-24T14:30:02.247Z - error: Too many emit retries to device: Apple-Iphone5s-1

2016-03-24T14:30:11.845Z - error: Too many emit retries to device: LGE-LG-H815

2016-03-24T14:31:11.325Z - error: Too many emit retries to device: Apple-Iphone6-1

2016-03-24T14:31:11.328Z - error: Too many emit retries to device: Apple-Iphone5-1

2016-03-24T14:31:11.333Z - error: Too many emit retries to device: Apple-Iphone5s-1

2016-03-24T14:31:32.263Z - error: Too many emit retries to device: samsung-SM-N910C

2016-03-24T14:31:42.996Z - error: Too many emit retries to device: LGE-LG-H815

2016-03-24T14:31:42.999Z - error: Too many emit retries to device: samsung-SM-N910C

2016-03-24T14:32:09.128Z - error: Too many emit retries to device: Apple-Iphone5-1

2016-03-24T14:32:32.460Z - error: Too many emit retries to device: Apple-Iphone6-1

2016-03-24T14:32:32.465Z - error: Too many emit retries to device: Apple-Iphone5-1

2016-03-24T14:32:32.469Z - error: Too many emit retries to device: Apple-Iphone5s-1


```


Logs for system : 
```

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/6391070405f2a33_416_ThaliNotificationClient_juhanak/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/6391070405f2a33_416_ThaliNotificationClient_juhanak/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/6391070405f2a33_416_ThaliNotificationClient_juhanak/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/6391070405f2a33_416_ThaliNotificationClient_juhanak/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/6391070405f2a33_416_ThaliNotificationClient_juhanak/iOS_server.md)


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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/6391070405f2a33_416_ThaliNotificationClient_juhanak/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/6391070405f2a33_416_ThaliNotificationClient_juhanak/thali07_LGE-LG-H815.md)

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
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/6391070405f2a33_416_ThaliNotificationClient_juhanak/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/6391070405f2a33_416_ThaliNotificationClient_juhanak/thali08_motorola-Nexus 6.md)





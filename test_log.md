#### Test 64065450860dd96 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-03-24T17:26:11.156Z - info: listening on *:3000

2016-03-24T17:26:13.000Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:0

2016-03-24T17:26:14.621Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:1

2016-03-24T17:26:16.090Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:2

2016-03-24T17:26:16.091Z - info: Required number of ios devices presented (3)

2016-03-24T17:26:16.096Z - info: Starting unit test run for platform: ios

2016-03-24T17:26:16.444Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:3

2016-03-24T17:26:17.417Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-24T17:26:18.015Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-24T17:26:18.507Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-24T17:26:19.101Z - info: Running on ios test: 4. native server connections all up

2016-03-24T17:26:19.523Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-24T17:26:19.922Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-24T17:26:20.394Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-24T17:26:20.831Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-24T17:26:21.418Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-24T17:26:22.373Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:4

2016-03-24T17:26:23.361Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-24T17:26:24.342Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-24T17:26:24.925Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-24T17:26:25.365Z - info: Running on ios test: 13. closeAll with promise

2016-03-24T17:26:25.840Z - info: Running on ios test: 14. multiplex can send data

2016-03-24T17:26:26.284Z - info: Running on ios test: 15. enqueue and run in order

2016-03-24T17:26:26.944Z - info: Running on ios test: 16. enqueueAtTop and run backwards

2016-03-24T17:26:27.348Z - info: Running on ios test: 17. mix enqueue and enqueueAtTop

2016-03-24T17:26:27.874Z - info: Running on ios test: 18. queues handled independently

2016-03-24T17:26:28.295Z - info: Running on ios test: 19. basic

2016-03-24T17:26:28.705Z - info: Running on ios test: 20. another

2016-03-24T17:26:29.126Z - info: Running on ios test: 21. can pass data in setup

2016-03-24T17:26:29.587Z - info: Running on ios test: 22. #startListeningForAdvertisements should fail if start not called

2016-03-24T17:26:30.043Z - info: Running on ios test: 23. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-24T17:26:30.562Z - info: Running on ios test: 24. should be able to call #stopListeningForAdvertisements many times

2016-03-24T17:26:31.029Z - info: Running on ios test: 25. should be able to call #startListeningForAdvertisements many times

2016-03-24T17:26:31.790Z - info: Running on ios test: 26. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-24T17:26:32.778Z - info: Running on ios test: 27. should be able to call #stopAdvertisingAndListening many times

2016-03-24T17:26:33.256Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:5

2016-03-24T17:26:33.257Z - info: Required number of android devices presented (3)

2016-03-24T17:26:33.258Z - info: Starting unit test run for platform: android

2016-03-24T17:26:33.733Z - info: Running on ios test: 28. #start should fail if called twice in a row

2016-03-24T17:26:34.083Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-24T17:26:34.646Z - info: Running on ios test: 29. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-24T17:26:35.443Z - info: Running on ios test: 30. does not send duplicate availability changes

2016-03-24T17:26:35.533Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-24T17:26:35.970Z - info: Running on ios test: 31. can get the network status

2016-03-24T17:26:36.056Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-24T17:26:40.871Z - info: Running on android test: 4. native server connections all up

2016-03-24T17:26:44.651Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-24T17:26:47.671Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-24T17:26:52.559Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-24T17:26:54.422Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-24T17:26:54.481Z - info: Running on ios test: 32. wifi peer is marked unavailable if announcements stop

2016-03-24T17:26:54.857Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-24T17:26:55.733Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-24T17:26:56.307Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-24T17:26:56.819Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-24T17:26:57.127Z - info: Running on android test: 13. closeAll with promise

2016-03-24T17:26:57.207Z - info: Running on ios test: 33. Can call start/stopListeningForAdvertisements

2016-03-24T17:26:57.513Z - info: Running on android test: 14. multiplex can send data

2016-03-24T17:26:57.740Z - info: Running on ios test: 34. Calling startListeningForAdvertisements twice is NOT an error

2016-03-24T17:26:57.913Z - info: Running on android test: 15. enqueue and run in order

2016-03-24T17:26:58.353Z - info: Running on ios test: 35. Can call start/stopUpdateAdvertisingAndListening

2016-03-24T17:26:58.499Z - info: Running on android test: 16. enqueueAtTop and run backwards

2016-03-24T17:26:59.394Z - info: Running on android test: 17. mix enqueue and enqueueAtTop

2016-03-24T17:27:00.049Z - info: Running on android test: 18. queues handled independently

2016-03-24T17:27:00.391Z - info: Running on android test: 19. basic

2016-03-24T17:27:00.536Z - info: Running on ios test: 36. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-24T17:27:00.813Z - info: Running on android test: 20. another

2016-03-24T17:27:01.261Z - info: Running on android test: 21. can pass data in setup

2016-03-24T17:27:01.363Z - info: Running on ios test: 37. peerAvailabilityChange is called

2016-03-24T17:27:01.591Z - info: Running on android test: 22. #startListeningForAdvertisements should fail if start not called

2016-03-24T17:27:02.078Z - info: Running on android test: 23. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-24T17:27:05.186Z - info: Running on android test: 24. should be able to call #stopListeningForAdvertisements many times

2016-03-24T17:27:10.156Z - info: Running on android test: 25. should be able to call #startListeningForAdvertisements many times

2016-03-24T17:27:32.687Z - info: Running on android test: 26. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-24T17:27:35.151Z - info: Running on android test: 27. should be able to call #stopAdvertisingAndListening many times

2016-03-24T17:27:37.134Z - info: Running on android test: 28. #start should fail if called twice in a row

2016-03-24T17:27:37.612Z - info: Running on ios test: 38. Can connect to a remote peer

2016-03-24T17:27:40.017Z - info: Running on android test: 29. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-24T17:27:42.300Z - info: Running on android test: 30. does not send duplicate availability changes

2016-03-24T17:27:42.756Z - info: Running on android test: 31. can get the network status

2016-03-24T17:27:43.196Z - info: Running on android test: 32. wifi peer is marked unavailable if announcements stop

2016-03-24T17:27:45.849Z - info: Running on android test: 33. Can call start/stopListeningForAdvertisements

2016-03-24T17:27:46.747Z - info: Running on android test: 34. Calling startListeningForAdvertisements twice is NOT an error

2016-03-24T17:27:48.445Z - info: Running on android test: 35. Can call start/stopUpdateAdvertisingAndListening

2016-03-24T17:27:50.752Z - info: Running on ios test: 39. Can shift large amounts of data

2016-03-24T17:27:51.446Z - info: Running on android test: 36. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-24T17:27:54.171Z - info: Running on android test: 37. peerAvailabilityChange is called

2016-03-24T17:27:56.222Z - info: Running on android test: 38. Can connect to a remote peer

2016-03-24T17:28:14.401Z - info: Running on android test: 39. Can shift large amounts of data

2016-03-24T17:28:22.890Z - info: Running on android test: 40. #startListeningForAdvertisements should fail if start not called

2016-03-24T17:28:26.463Z - info: Running on android test: 41. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-24T17:28:27.646Z - info: Running on android test: 42. should be able to call #stopListeningForAdvertisements many times

2016-03-24T17:28:28.975Z - info: Running on android test: 43. should be able to call #startListeningForAdvertisements many times

2016-03-24T17:28:29.983Z - info: Running on android test: 44. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-24T17:28:31.065Z - info: Running on android test: 45. should be able to call #stopAdvertisingAndListening many times

2016-03-24T17:28:31.490Z - info: Running on android test: 46. can get the network status before starting

2016-03-24T17:28:32.112Z - info: Running on android test: 47. error returned with bad router

2016-03-24T17:28:32.626Z - info: Running on android test: 48. all services are stopped when we call stop

2016-03-24T17:28:33.442Z - info: Running on android test: 49. make sure terminateConnection is properly hooked up

2016-03-24T17:28:33.934Z - info: Running on android test: 50. make sure terminateListener is properly hooked up

2016-03-24T17:28:34.413Z - info: Running on android test: 51. make sure we actually call kill connections properly

2016-03-24T17:28:34.891Z - info: Running on android test: 52. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received

2016-03-24T17:28:35.270Z - info: Running on android test: 53. We repeat failedConnection event when we get it from thaliTcpServersManager

2016-03-24T17:28:35.832Z - info: Running on android test: 54. we successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-24T17:28:39.312Z - warn: Failed on android test: 54. we successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-24T17:28:39.315Z - info: Running on android test: 55. can do HTTP requests between peers

2016-03-24T17:28:49.566Z - info: Running on android test: 56. Client to server request locally

2016-03-24T17:28:50.675Z - info: Running on android test: 57. Client to server request coordinated

2016-03-24T17:28:52.251Z - debug: Socket disconnected: transport close 3 (LGE-LG-H815)

2016-03-24T17:28:53.077Z - debug: Socket disconnected: transport close 4 (samsung-SM-N910C)

2016-03-24T17:29:06.337Z - debug: Socket disconnected: transport close 5 (motorola-Nexus 6)

2016-03-24T17:29:28.389Z - debug: Socket disconnected: transport close 1 (Apple-Iphone5-1)

2016-03-24T17:29:45.719Z - debug: Socket disconnected: transport close 6 (NOT YET SET)

2016-03-24T17:38:20.207Z - debug: Socket disconnected: ping timeout 7 (NOT YET SET)

2016-03-24T17:39:31.939Z - debug: Socket disconnected: transport close 9 (NOT YET SET)

2016-03-24T17:45:46.975Z - debug: Socket disconnected: transport close 2 (Apple-Iphone6-1)

2016-03-24T17:45:46.982Z - debug: Socket disconnected: transport close 0 (Apple-Iphone5s-1)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m
2016-03-24T17:26:50.432Z - error: Too many emit retries to device: Apple-Iphone5s-1

2016-03-24T17:27:14.799Z - error: Too many emit retries to device: Apple-Iphone5s-1

2016-03-24T17:27:30.693Z - error: Too many emit retries to device: samsung-SM-N910C

2016-03-24T17:30:08.031Z - error: Too many emit retries to device: Apple-Iphone5-1


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
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/64065450860dd96_416_Thali_notification_end_to_end_tests_juhanak/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/64065450860dd96_416_Thali_notification_end_to_end_tests_juhanak/thali07_LGE-LG-H815.md)

####Node name: thali08
Console output:
```
STOP log received from  41006f95c8139173 Test has  FAILED
Device test finished on 41006f95c8139173 
STOP log received from  ZX1G429CRK Test has  FAILED
Device test finished on ZX1G429CRK 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/64065450860dd96_416_Thali_notification_end_to_end_tests_juhanak/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/64065450860dd96_416_Thali_notification_end_to_end_tests_juhanak/thali08_motorola-Nexus 6.md)


###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/64065450860dd96_416_Thali_notification_end_to_end_tests_juhanak/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/64065450860dd96_416_Thali_notification_end_to_end_tests_juhanak/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/64065450860dd96_416_Thali_notification_end_to_end_tests_juhanak/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/64065450860dd96_416_Thali_notification_end_to_end_tests_juhanak/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/64065450860dd96_416_Thali_notification_end_to_end_tests_juhanak/iOS_server.md)





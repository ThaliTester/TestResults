#### Test 639808779d5bfaa Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-03-29T09:06:59.523Z - info: listening on *:3000

2016-03-29T09:07:00.313Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:0

2016-03-29T09:07:00.326Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:1

2016-03-29T09:07:02.613Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:2

2016-03-29T09:07:05.127Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:3

2016-03-29T09:07:05.129Z - info: Required number of ios devices presented (3)

2016-03-29T09:07:05.133Z - info: Starting unit test run for platform: ios

2016-03-29T09:07:05.815Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-29T09:07:06.901Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:4

2016-03-29T09:07:08.396Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-29T09:07:08.802Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-29T09:07:09.224Z - info: Running on ios test: 4. native server connections all up

2016-03-29T09:07:09.764Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-29T09:07:10.232Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-29T09:07:10.800Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-29T09:07:11.384Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-29T09:07:11.859Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-29T09:07:20.253Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:5

2016-03-29T09:07:20.255Z - info: Required number of android devices presented (3)

2016-03-29T09:07:20.257Z - info: Starting unit test run for platform: android

2016-03-29T09:07:20.848Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-29T09:07:21.183Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-29T09:07:22.367Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-29T09:07:22.730Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-29T09:07:22.834Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-29T09:07:23.277Z - info: Running on ios test: 13. closeAll with promise

2016-03-29T09:07:23.657Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-29T09:07:23.790Z - info: Running on ios test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-03-29T09:07:24.094Z - info: Running on android test: 4. native server connections all up

2016-03-29T09:07:24.145Z - info: Running on ios test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-03-29T09:07:24.451Z - info: Running on ios test: 16. multiplex can send data

2016-03-29T09:07:24.643Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-29T09:07:24.831Z - info: Running on ios test: 17. enqueue and run in order

2016-03-29T09:07:25.247Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-29T09:07:25.482Z - info: Running on ios test: 18. enqueueAtTop and run backwards

2016-03-29T09:07:25.702Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-29T09:07:25.871Z - info: Running on ios test: 19. mix enqueue and enqueueAtTop

2016-03-29T09:07:26.271Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-29T09:07:26.359Z - info: Running on ios test: 20. queues handled independently

2016-03-29T09:07:26.796Z - info: Running on ios test: 21. basic

2016-03-29T09:07:26.815Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-29T09:07:27.167Z - info: Running on ios test: 22. another

2016-03-29T09:07:27.628Z - info: Running on ios test: 23. can pass data in setup

2016-03-29T09:07:27.891Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-29T09:07:28.070Z - info: Running on ios test: 24. #startListeningForAdvertisements should fail if start not called

2016-03-29T09:07:28.488Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-29T09:07:28.563Z - info: Running on ios test: 25. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-29T09:07:29.060Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-29T09:07:29.100Z - info: Running on ios test: 26. should be able to call #stopListeningForAdvertisements many times

2016-03-29T09:07:29.523Z - info: Running on android test: 13. closeAll with promise

2016-03-29T09:07:29.734Z - info: Running on ios test: 27. should be able to call #startListeningForAdvertisements many times

2016-03-29T09:07:29.996Z - info: Running on android test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-03-29T09:07:30.496Z - info: Running on android test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-03-29T09:07:30.881Z - info: Running on ios test: 28. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-29T09:07:30.946Z - info: Running on android test: 16. multiplex can send data

2016-03-29T09:07:37.485Z - info: Running on android test: 17. enqueue and run in order

2016-03-29T09:07:44.343Z - info: Running on android test: 18. enqueueAtTop and run backwards

2016-03-29T09:07:51.408Z - info: Running on android test: 19. mix enqueue and enqueueAtTop

2016-03-29T09:08:07.614Z - info: Running on android test: 20. queues handled independently

2016-03-29T09:08:37.103Z - info: Running on android test: 21. basic

2016-03-29T09:08:45.682Z - info: Running on ios test: 29. should be able to call #stopAdvertisingAndListening many times

2016-03-29T09:08:46.650Z - info: Running on ios test: 30. #start should fail if called twice in a row

2016-03-29T09:08:47.035Z - info: Running on ios test: 31. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-29T09:08:47.489Z - info: Running on ios test: 32. does not send duplicate availability changes

2016-03-29T09:08:48.163Z - info: Running on ios test: 33. can get the network status

2016-03-29T09:09:32.154Z - info: Running on ios test: 34. wifi peer is marked unavailable if announcements stop

2016-03-29T09:09:40.138Z - info: Running on ios test: 35. Can call start/stopListeningForAdvertisements

2016-03-29T09:09:40.666Z - info: Running on ios test: 36. Calling startListeningForAdvertisements twice is NOT an error

2016-03-29T09:09:55.804Z - debug: Socket disconnected: transport close 5 (motorola-Nexus 6)

2016-03-29T09:10:14.951Z - info: Running on ios test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-03-29T09:10:52.125Z - info: Running on ios test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-29T09:10:55.601Z - info: Running on ios test: 39. peerAvailabilityChange is called

2016-03-29T09:11:32.874Z - info: Running on ios test: 40. Can connect to a remote peer

2016-03-29T09:13:42.511Z - warn: Failed on ios test: 40. Can connect to a remote peer

2016-03-29T09:13:42.514Z - info: Running on ios test: 41. Can shift large amounts of data

2016-03-29T09:15:23.900Z - warn: Failed on ios test: 41. Can shift large amounts of data

2016-03-29T09:15:23.903Z - info: Running on ios test: 42. #startListeningForAdvertisements should fail if start not called

2016-03-29T09:15:24.370Z - info: Running on ios test: 43. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-29T09:15:25.384Z - info: Running on ios test: 44. should be able to call #stopListeningForAdvertisements many times

2016-03-29T09:15:26.202Z - info: Running on ios test: 45. should be able to call #startListeningForAdvertisements many times

2016-03-29T09:15:26.846Z - info: Running on ios test: 46. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-29T09:15:27.324Z - info: Running on ios test: 47. should be able to call #stopAdvertisingAndListening many times

2016-03-29T09:15:29.696Z - info: Running on ios test: 48. can get the network status before starting

2016-03-29T09:16:14.499Z - info: Running on ios test: 49. error returned with bad router

2016-03-29T09:16:15.635Z - info: Running on ios test: 50. all services are stopped when we call stop

2016-03-29T09:16:19.578Z - info: Running on ios test: 51. make sure terminateConnection is properly hooked up

2016-03-29T09:16:57.775Z - info: Running on ios test: 52. make sure terminateListener is properly hooked up

2016-03-29T09:17:00.817Z - info: Running on ios test: 53. make sure we actually call kill connections properly

2016-03-29T09:17:01.884Z - warn: Failed on ios test: 53. make sure we actually call kill connections properly

2016-03-29T09:17:01.885Z - info: Running on ios test: 54. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received

2016-03-29T09:17:05.543Z - info: Running on ios test: 55. We repeat failedConnection event when we get it from thaliTcpServersManager

2016-03-29T09:17:14.483Z - info: Running on ios test: 56. we successfully receive and replay discoveryAdvertisingStateUpdate

2016-03-29T09:26:50.331Z - debug: Socket disconnected: transport close 1 (Apple-Iphone6-1)

2016-03-29T09:26:50.428Z - debug: Socket disconnected: transport close 0 (Apple-Iphone5-1)

2016-03-29T09:26:50.435Z - debug: Socket disconnected: transport close 3 (Apple-Iphone5s-1)

2016-03-29T09:28:43.490Z - debug: Socket disconnected: transport close 2 (LGE-LG-H815)

2016-03-29T09:30:26.394Z - debug: Socket disconnected: transport close 4 (samsung-SM-N910C)

2016-03-29T09:30:28.312Z - debug: Socket disconnected: transport close 6 (NOT YET SET)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m
2016-03-29T09:07:47.302Z - error: Too many emit retries to device: Apple-Iphone5-1

2016-03-29T09:07:47.309Z - error: Too many emit retries to device: Apple-Iphone5s-1

2016-03-29T09:08:07.121Z - error: Too many emit retries to device: samsung-SM-N910C

2016-03-29T09:08:31.541Z - error: Too many emit retries to device: LGE-LG-H815

2016-03-29T09:08:31.544Z - error: Too many emit retries to device: motorola-Nexus 6

2016-03-29T09:08:46.145Z - error: Too many emit retries to device: LGE-LG-H815

2016-03-29T09:08:46.149Z - error: Too many emit retries to device: samsung-SM-N910C

2016-03-29T09:08:46.152Z - error: Too many emit retries to device: motorola-Nexus 6

2016-03-29T09:08:58.553Z - error: Too many emit retries to device: Apple-Iphone6-1

2016-03-29T09:08:58.556Z - error: Too many emit retries to device: Apple-Iphone5s-1

2016-03-29T09:09:49.700Z - error: Too many emit retries to device: Apple-Iphone5s-1

2016-03-29T09:10:00.023Z - error: Too many emit retries to device: Apple-Iphone6-1

2016-03-29T09:10:00.026Z - error: Too many emit retries to device: Apple-Iphone5s-1

2016-03-29T09:10:13.295Z - error: Too many emit retries to device: Apple-Iphone6-1

2016-03-29T09:10:23.992Z - error: Too many emit retries to device: Apple-Iphone5s-1

2016-03-29T09:10:35.934Z - error: Too many emit retries to device: Apple-Iphone5s-1

2016-03-29T09:11:06.268Z - error: Too many emit retries to device: Apple-Iphone6-1

2016-03-29T09:15:44.630Z - error: Too many emit retries to device: Apple-Iphone5-1

2016-03-29T09:15:44.634Z - error: Too many emit retries to device: Apple-Iphone5s-1

2016-03-29T09:16:29.412Z - error: Too many emit retries to device: Apple-Iphone5s-1

2016-03-29T09:16:38.448Z - error: Too many emit retries to device: Apple-Iphone5s-1


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
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/639808779d5bfaa_PSK_Support_yaronyg/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/639808779d5bfaa_PSK_Support_yaronyg/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/639808779d5bfaa_PSK_Support_yaronyg/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/639808779d5bfaa_PSK_Support_yaronyg/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/639808779d5bfaa_PSK_Support_yaronyg/iOS_server.md)


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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/639808779d5bfaa_PSK_Support_yaronyg/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/639808779d5bfaa_PSK_Support_yaronyg/thali07_LGE-LG-H815.md)

####Node name: thali08
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1G429CRK 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/639808779d5bfaa_PSK_Support_yaronyg/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/639808779d5bfaa_PSK_Support_yaronyg/thali08_motorola-Nexus 6.md)





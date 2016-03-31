#### Test 645312549bcf247 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-03-30T23:50:03.719Z - info: listening on *:3000

2016-03-30T23:50:04.856Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:0

2016-03-30T23:50:06.568Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:1

2016-03-30T23:50:07.385Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:2

2016-03-30T23:50:07.386Z - info: Required number of ios devices presented (3)

2016-03-30T23:50:07.390Z - info: Starting unit test run for platform: ios

2016-03-30T23:50:07.685Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:3

2016-03-30T23:50:08.230Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-30T23:50:10.563Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-30T23:50:10.927Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-30T23:50:11.250Z - info: Running on ios test: 4. native server connections all up

2016-03-30T23:50:11.646Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-30T23:50:12.155Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-30T23:50:12.518Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-30T23:50:12.756Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:4

2016-03-30T23:50:12.894Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-30T23:50:13.270Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-30T23:50:15.240Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-30T23:50:15.842Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-30T23:50:16.240Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-30T23:50:16.674Z - info: Running on ios test: 13. closeAll with promise

2016-03-30T23:50:16.997Z - info: Running on ios test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-03-30T23:50:17.343Z - info: Running on ios test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-03-30T23:50:17.764Z - info: Running on ios test: 16. enqueue and run in order

2016-03-30T23:50:18.333Z - info: Running on ios test: 17. enqueueAtTop and run backwards

2016-03-30T23:50:18.391Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:5

2016-03-30T23:50:18.392Z - info: Required number of android devices presented (3)

2016-03-30T23:50:18.394Z - info: Starting unit test run for platform: android

2016-03-30T23:50:18.731Z - info: Running on ios test: 18. mix enqueue and enqueueAtTop

2016-03-30T23:50:19.137Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-30T23:50:19.273Z - info: Running on ios test: 19. queues handled independently

2016-03-30T23:50:19.594Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-30T23:50:19.665Z - info: Running on ios test: 20. basic

2016-03-30T23:50:20.196Z - info: Running on ios test: 21. another

2016-03-30T23:50:20.205Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-30T23:50:20.552Z - info: Running on ios test: 22. can pass data in setup

2016-03-30T23:50:20.703Z - info: Running on android test: 4. native server connections all up

2016-03-30T23:50:20.963Z - info: Running on ios test: 23. #startListeningForAdvertisements should fail if start not called

2016-03-30T23:50:21.322Z - info: Running on ios test: 24. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-30T23:50:21.342Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-30T23:50:21.784Z - info: Running on ios test: 25. should be able to call #stopListeningForAdvertisements many times

2016-03-30T23:50:21.836Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-30T23:50:22.330Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-30T23:50:22.337Z - info: Running on ios test: 26. should be able to call #startListeningForAdvertisements many times

2016-03-30T23:50:22.849Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-30T23:50:23.269Z - info: Running on ios test: 27. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-30T23:50:23.336Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-30T23:50:24.949Z - info: Running on ios test: 28. should be able to call #stopAdvertisingAndListening many times

2016-03-30T23:50:25.611Z - info: Running on ios test: 29. #start should fail if called twice in a row

2016-03-30T23:50:27.232Z - info: Running on ios test: 30. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-30T23:50:27.908Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-30T23:50:28.010Z - info: Running on ios test: 31. does not send duplicate availability changes

2016-03-30T23:50:28.966Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-30T23:50:29.293Z - info: Running on ios test: 32. can get the network status

2016-03-30T23:50:30.181Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-30T23:50:31.934Z - info: Running on android test: 13. closeAll with promise

2016-03-30T23:50:33.672Z - info: Running on android test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-03-30T23:50:36.467Z - info: Running on android test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-03-30T23:50:38.926Z - info: Running on android test: 16. enqueue and run in order

2016-03-30T23:50:41.946Z - info: Running on android test: 17. enqueueAtTop and run backwards

2016-03-30T23:50:48.914Z - info: Running on android test: 18. mix enqueue and enqueueAtTop

2016-03-30T23:50:48.925Z - info: Running on ios test: 33. wifi peer is marked unavailable if announcements stop

2016-03-30T23:50:51.250Z - info: Running on android test: 19. queues handled independently

2016-03-30T23:50:52.390Z - info: Running on android test: 20. basic

2016-03-30T23:50:53.204Z - info: Running on android test: 21. another

2016-03-30T23:50:53.565Z - info: Running on android test: 22. can pass data in setup

2016-03-30T23:50:53.810Z - info: Running on android test: 23. #startListeningForAdvertisements should fail if start not called

2016-03-30T23:50:54.229Z - info: Running on android test: 24. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-30T23:50:54.613Z - info: Running on android test: 25. should be able to call #stopListeningForAdvertisements many times

2016-03-30T23:50:55.024Z - info: Running on android test: 26. should be able to call #startListeningForAdvertisements many times

2016-03-30T23:50:55.731Z - info: Running on android test: 27. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-30T23:50:56.773Z - info: Running on android test: 28. should be able to call #stopAdvertisingAndListening many times

2016-03-30T23:50:57.086Z - info: Running on ios test: 34. Can call start/stopListeningForAdvertisements

2016-03-30T23:50:57.489Z - info: Running on android test: 29. #start should fail if called twice in a row

2016-03-30T23:50:57.701Z - info: Running on ios test: 35. Calling startListeningForAdvertisements twice is NOT an error

2016-03-30T23:50:58.047Z - info: Running on android test: 30. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-30T23:50:58.323Z - info: Running on ios test: 36. Calling stopListeningForAdvertisements without calling start is NOT an error

2016-03-30T23:50:59.327Z - info: Running on android test: 31. does not send duplicate availability changes

2016-03-30T23:51:00.703Z - info: Running on android test: 32. can get the network status

2016-03-30T23:51:01.271Z - info: Running on android test: 33. wifi peer is marked unavailable if announcements stop

2016-03-30T23:51:03.745Z - info: Running on android test: 34. Can call start/stopListeningForAdvertisements

2016-03-30T23:51:04.406Z - info: Running on android test: 35. Calling startListeningForAdvertisements twice is NOT an error

2016-03-30T23:51:05.148Z - info: Running on android test: 36. Calling stopListeningForAdvertisements without calling start is NOT an error

2016-03-30T23:51:05.561Z - info: Running on android test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-03-30T23:51:06.579Z - info: Running on android test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-30T23:51:09.308Z - info: Running on android test: 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error

2016-03-30T23:51:09.696Z - info: Running on android test: 40. cannot call connect when start listening for advertisements is not active

2016-03-30T23:51:10.230Z - info: Running on android test: 41. peerAvailabilityChange is called

2016-03-30T23:51:12.817Z - info: Running on android test: 42. Can connect to a remote peer

2016-03-30T23:51:18.518Z - info: Running on ios test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-03-30T23:51:18.972Z - info: Running on ios test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-30T23:51:19.652Z - info: Running on ios test: 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error

2016-03-30T23:51:22.769Z - info: Running on android test: 43. Get error when trying to double connect to a peer

2016-03-30T23:51:30.148Z - warn: Failed on android test: 43. Get error when trying to double connect to a peer

2016-03-30T23:51:30.149Z - info: Running on android test: 44. Connect port dies if not connected to in in time

2016-03-30T23:51:38.267Z - info: Running on ios test: 40. cannot call connect when start listening for advertisements is not active

2016-03-30T23:51:38.641Z - warn: Failed on ios test: 40. cannot call connect when start listening for advertisements is not active

2016-03-30T23:51:38.642Z - info: Running on ios test: 41. peerAvailabilityChange is called

2016-03-30T23:51:43.411Z - info: Running on ios test: 42. Can connect to a remote peer

2016-03-30T23:52:53.792Z - warn: Failed on ios test: 42. Can connect to a remote peer

2016-03-30T23:52:53.794Z - info: Running on ios test: 43. Get error when trying to double connect to a peer

2016-03-31T00:09:40.927Z - debug: Socket disconnected: transport close 1 (Apple-Iphone5-1)

2016-03-31T00:09:40.964Z - debug: Socket disconnected: transport close 2 (Apple-Iphone5s-1)

2016-03-31T00:09:40.972Z - debug: Socket disconnected: transport close 0 (Apple-Iphone6-1)

2016-03-31T00:11:30.824Z - debug: Socket disconnected: transport close 3 (LGE-LG-H815)

2016-03-31T00:13:31.581Z - debug: Socket disconnected: transport close 4 (samsung-SM-N910C)

2016-03-31T00:13:33.616Z - debug: Socket disconnected: transport close 5 (motorola-Nexus 6)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m
2016-03-30T23:50:44.504Z - error: Too many emit retries to device: Apple-Iphone6-1

2016-03-30T23:50:44.508Z - error: Too many emit retries to device: Apple-Iphone5-1

2016-03-30T23:51:07.349Z - error: Too many emit retries to device: Apple-Iphone5s-1

2016-03-30T23:51:31.012Z - error: Too many emit retries to device: Apple-Iphone6-1

2016-03-30T23:51:31.016Z - error: Too many emit retries to device: Apple-Iphone5-1

2016-03-30T23:51:31.020Z - error: Too many emit retries to device: Apple-Iphone5s-1


```


Logs for system : 
```

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/645312549bcf247_More_native_level_testing_yaronyg/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/645312549bcf247_More_native_level_testing_yaronyg/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/645312549bcf247_More_native_level_testing_yaronyg/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/645312549bcf247_More_native_level_testing_yaronyg/iOS_Iphone6-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/645312549bcf247_More_native_level_testing_yaronyg/iOS_server.md)


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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/645312549bcf247_More_native_level_testing_yaronyg/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/645312549bcf247_More_native_level_testing_yaronyg/thali07_LGE-LG-H815.md)

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
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/645312549bcf247_More_native_level_testing_yaronyg/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/645312549bcf247_More_native_level_testing_yaronyg/thali08_motorola-Nexus 6.md)





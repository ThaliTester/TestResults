#### Test 63186632d456b18 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":8}}
2016-03-17T08:52:24.542Z - info: listening on *:3000

2016-03-17T08:52:25.687Z - debug: Device presented: samsung-SM-A500FU (android) unittest socket:0

2016-03-17T08:52:27.158Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:1

2016-03-17T08:52:27.892Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:2

2016-03-17T08:52:27.894Z - info: Required number of android devices presented (2)

2016-03-17T08:52:27.898Z - info: Starting unit test run for platform: android

2016-03-17T08:52:28.543Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-17T08:52:28.559Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:3

2016-03-17T08:52:28.560Z - info: Required number of ios devices presented (2)

2016-03-17T08:52:28.562Z - info: Starting unit test run for platform: ios

2016-03-17T08:52:28.977Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-17T08:52:29.131Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:4

2016-03-17T08:52:29.132Z - info: Discarding surplus device: Apple-Iphone6-1

2016-03-17T08:52:29.461Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-17T08:52:29.590Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:5

2016-03-17T08:52:29.591Z - info: Discarding surplus device: samsung-SM-N910C

2016-03-17T08:52:30.184Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:6

2016-03-17T08:52:30.187Z - info: Discarding surplus device: Apple-IpadAir2-1

2016-03-17T08:52:30.284Z - info: Running on android test: 4. native server connections all up

2016-03-17T08:52:30.683Z - debug: Socket disconnected: transport close 5 (samsung-SM-N910C)

2016-03-17T08:52:30.785Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-17T08:52:31.123Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-17T08:52:31.609Z - debug: Socket disconnected: transport close 4 (Apple-Iphone6-1)

2016-03-17T08:52:32.464Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-17T08:52:32.605Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-17T08:52:32.923Z - debug: Socket disconnected: transport close 6 (Apple-IpadAir2-1)

2016-03-17T08:52:33.099Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-17T08:52:33.636Z - info: Running on ios test: 4. native server connections all up

2016-03-17T08:52:33.698Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-17T08:52:34.246Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-17T08:52:34.272Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-17T08:52:34.994Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-17T08:52:35.471Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-17T08:52:35.869Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-17T08:52:35.937Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-17T08:52:36.347Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-17T08:52:36.399Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-17T08:52:36.856Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-17T08:52:36.859Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-17T08:52:37.222Z - info: Running on android test: 13. closeAll with promise

2016-03-17T08:52:37.569Z - info: Running on android test: 14. multiplex can send data

2016-03-17T08:52:37.804Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-17T08:52:37.892Z - info: Running on android test: 15. enqueue and run in order

2016-03-17T08:52:38.517Z - info: Running on android test: 16. enqueueAtTop and run backwards

2016-03-17T08:52:39.038Z - info: Running on android test: 17. mix enqueue and enqueueAtTop

2016-03-17T08:52:39.540Z - info: Running on android test: 18. queues handled independently

2016-03-17T08:52:40.005Z - info: Running on android test: 19. basic

2016-03-17T08:52:40.429Z - info: Running on android test: 20. another

2016-03-17T08:52:40.712Z - info: Running on android test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-17T08:52:41.038Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-17T08:52:41.104Z - info: Running on android test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-17T08:52:41.581Z - info: Running on android test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-17T08:52:41.585Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-17T08:52:42.013Z - info: Running on ios test: 13. closeAll with promise

2016-03-17T08:52:42.018Z - info: Running on android test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-17T08:52:42.369Z - info: Running on ios test: 14. multiplex can send data

2016-03-17T08:52:42.377Z - info: Running on android test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-17T08:52:42.938Z - info: Running on android test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-17T08:52:42.942Z - info: Running on ios test: 15. enqueue and run in order

2016-03-17T08:52:43.444Z - info: Running on android test: 27. #start should fail if called twice in a row

2016-03-17T08:52:43.587Z - info: Running on ios test: 16. enqueueAtTop and run backwards

2016-03-17T08:52:43.797Z - info: Running on android test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-17T08:52:43.924Z - info: Running on ios test: 17. mix enqueue and enqueueAtTop

2016-03-17T08:52:44.174Z - info: Running on android test: 29. does not send duplicate availability changes

2016-03-17T08:52:44.332Z - info: Running on ios test: 18. queues handled independently

2016-03-17T08:52:44.457Z - info: Running on android test: 30. can get the network status

2016-03-17T08:52:44.702Z - info: Running on ios test: 19. basic

2016-03-17T08:52:44.816Z - info: Running on android test: 31. wifi peer is marked unavailable if announcements stop

2016-03-17T08:52:45.003Z - info: Running on ios test: 20. another

2016-03-17T08:52:45.338Z - info: Running on ios test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-17T08:52:45.725Z - info: Running on ios test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-17T08:52:46.244Z - info: Running on android test: 32. Can call start/stopListeningForAdvertisements

2016-03-17T08:52:46.280Z - info: Running on ios test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-17T08:52:46.814Z - info: Running on ios test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-17T08:52:47.250Z - info: Running on ios test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-17T08:52:47.312Z - info: Running on android test: 33. Calling startListeningForAdvertisements twice is NOT an error

2016-03-17T08:52:47.782Z - info: Running on ios test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-17T08:52:48.092Z - info: Running on android test: 34. Can call start/stopUpdateAdvertisingAndListening

2016-03-17T08:52:48.406Z - info: Running on ios test: 27. #start should fail if called twice in a row

2016-03-17T08:52:49.181Z - info: Running on android test: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-17T08:52:49.572Z - info: Running on ios test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-17T08:52:49.985Z - info: Running on ios test: 29. does not send duplicate availability changes

2016-03-17T08:52:50.295Z - info: Running on ios test: 30. can get the network status

2016-03-17T08:52:50.417Z - info: Running on android test: 36. peerAvailabilityChange is called

2016-03-17T08:52:50.663Z - info: Running on ios test: 31. wifi peer is marked unavailable if announcements stop

2016-03-17T08:52:52.082Z - info: Running on ios test: 32. Can call start/stopListeningForAdvertisements

2016-03-17T08:52:52.458Z - info: Running on ios test: 33. Calling startListeningForAdvertisements twice is NOT an error

2016-03-17T08:52:53.559Z - info: Running on ios test: 34. Can call start/stopUpdateAdvertisingAndListening

2016-03-17T08:52:54.137Z - info: Running on android test: 37. Can connect to a remote peer

2016-03-17T08:52:54.257Z - info: Running on ios test: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-17T08:52:56.527Z - info: Running on ios test: 36. peerAvailabilityChange is called

2016-03-17T08:52:59.562Z - info: Running on ios test: 37. Can connect to a remote peer

2016-03-17T09:10:47.537Z - debug: Socket disconnected: transport close 1 (Apple-Iphone5s-1)

2016-03-17T09:10:47.547Z - debug: Socket disconnected: transport close 3 (Apple-Iphone5-1)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

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
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
true

```
###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  f56ad48d Test has  SUCCEEDED
Device test finished on f56ad48d 
Android task is completed. [SUCCESS]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/63186632d456b18_Temporary_test_-_do_not_merge_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali03
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Android task is completed. [SUCCESS]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/63186632d456b18_Temporary_test_-_do_not_merge_vjrantal/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on ZX1C223JKW 
Android task is completed. [SUCCESS]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/63186632d456b18_Temporary_test_-_do_not_merge_vjrantal/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/63186632d456b18_Temporary_test_-_do_not_merge_vjrantal/thali05_LGE-LG-H815.md)

####Node name: thali06
Console output:
```
STOP log received from  7970f88c Test has  SUCCEEDED
STOP log received from  FA55PYS00566 Test has  SUCCEEDED
Device test finished on 7970f88c 
Device test finished on FA55PYS00566 
Android task is completed. [SUCCESS]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/63186632d456b18_Temporary_test_-_do_not_merge_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/63186632d456b18_Temporary_test_-_do_not_merge_vjrantal/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:0 
child process exited with code 0 on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/63186632d456b18_Temporary_test_-_do_not_merge_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
STOP log received from  4325e43f Test has  SUCCEEDED
Device test finished on 4325e43f 
Android task is completed. [SUCCESS]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/63186632d456b18_Temporary_test_-_do_not_merge_vjrantal/thali08_samsung-SM-A300FU.md)


###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/63186632d456b18_Temporary_test_-_do_not_merge_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/63186632d456b18_Temporary_test_-_do_not_merge_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/63186632d456b18_Temporary_test_-_do_not_merge_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/63186632d456b18_Temporary_test_-_do_not_merge_vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/63186632d456b18_Temporary_test_-_do_not_merge_vjrantal/iOS_server.md)





#### Test 625481247756efd Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":10}}
2016-03-11T15:09:23.287Z - info: listening on *:3000

2016-03-11T15:09:24.330Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:0

2016-03-11T15:09:24.603Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:1

2016-03-11T15:09:24.606Z - info: Required number of android devices presented (2)

2016-03-11T15:09:24.609Z - info: Starting unit test run for platform: android

2016-03-11T15:09:25.219Z - info: Running on android test: 1. closeAll can close even when connections open

2016-03-11T15:09:25.755Z - info: Running on android test: 2. closeAll with promise

2016-03-11T15:09:26.142Z - info: Running on android test: 3. multiplex can send data

2016-03-11T15:09:26.270Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:2

2016-03-11T15:09:26.392Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:3

2016-03-11T15:09:26.394Z - info: Required number of ios devices presented (2)

2016-03-11T15:09:26.396Z - info: Starting unit test run for platform: ios

2016-03-11T15:09:26.563Z - info: Running on android test: 4. enqueue and run in order

2016-03-11T15:09:26.819Z - info: Running on ios test: 1. closeAll can close even when connections open

2016-03-11T15:09:27.034Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:4

2016-03-11T15:09:27.037Z - info: Discarding surplus device: Apple-Iphone5-1

2016-03-11T15:09:27.213Z - info: Running on ios test: 2. closeAll with promise

2016-03-11T15:09:27.331Z - info: Running on android test: 5. enqueueAtTop and run backwards

2016-03-11T15:09:27.550Z - info: Running on ios test: 3. multiplex can send data

2016-03-11T15:09:27.723Z - info: Running on android test: 6. mix enqueue and enqueueAtTop

2016-03-11T15:09:27.952Z - info: Running on ios test: 4. enqueue and run in order

2016-03-11T15:09:28.024Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:5

2016-03-11T15:09:28.027Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-11T15:09:28.174Z - info: Running on android test: 7. queues handled independently

2016-03-11T15:09:28.456Z - info: Running on ios test: 5. enqueueAtTop and run backwards

2016-03-11T15:09:28.576Z - info: Running on android test: 8. basic

2016-03-11T15:09:28.821Z - info: Running on ios test: 6. mix enqueue and enqueueAtTop

2016-03-11T15:09:28.956Z - info: Running on android test: 9. another

2016-03-11T15:09:29.667Z - info: Running on ios test: 7. queues handled independently

2016-03-11T15:09:29.903Z - info: Running on android test: 10. #startListeningForAdvertisements should fail if start not called

2016-03-11T15:09:30.112Z - info: Running on ios test: 8. basic

2016-03-11T15:09:30.312Z - debug: Socket disconnected: transport close 4 (Apple-Iphone5-1)

2016-03-11T15:09:30.334Z - info: Running on android test: 11. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-11T15:09:30.515Z - debug: Socket disconnected: transport close 5 (Apple-Iphone5s-1)

2016-03-11T15:09:30.794Z - info: Running on ios test: 9. another

2016-03-11T15:09:31.100Z - info: Running on ios test: 10. #startListeningForAdvertisements should fail if start not called

2016-03-11T15:09:31.413Z - info: Running on ios test: 11. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-11T15:09:31.735Z - info: Running on android test: 12. should be able to call #stopListeningForAdvertisements many times

2016-03-11T15:09:31.818Z - info: Running on ios test: 12. should be able to call #stopListeningForAdvertisements many times

2016-03-11T15:09:32.181Z - info: Running on android test: 13. should be able to call #startListeningForAdvertisements many times

2016-03-11T15:09:32.315Z - info: Running on ios test: 13. should be able to call #startListeningForAdvertisements many times

2016-03-11T15:09:32.918Z - info: Running on ios test: 14. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-11T15:09:33.582Z - info: Running on ios test: 15. should be able to call #stopAdvertisingAndListening many times

2016-03-11T15:09:34.514Z - info: Running on ios test: 16. #start should fail if called twice in a row

2016-03-11T15:09:36.435Z - info: Running on ios test: 17. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-11T15:09:37.170Z - info: Running on ios test: 18. does not send duplicate availability changes

2016-03-11T15:09:37.622Z - info: Running on ios test: 19. can get the network status

2016-03-11T15:09:38.169Z - info: Running on ios test: 20. wifi peer is marked unavailable if announcements stop

2016-03-11T15:09:39.827Z - info: Running on ios test: 21. Can call start/stopListeningForAdvertisements

2016-03-11T15:09:44.909Z - info: Running on android test: 14. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-11T15:09:46.312Z - info: Running on android test: 15. should be able to call #stopAdvertisingAndListening many times

2016-03-11T15:09:46.986Z - info: Running on android test: 16. #start should fail if called twice in a row

2016-03-11T15:09:47.420Z - info: Running on android test: 17. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-11T15:09:50.558Z - info: Running on ios test: 22. Calling startListeningForAdvertisements twice is NOT an error

2016-03-11T15:09:51.163Z - info: Running on ios test: 23. Can call start/stopUpdateAdvertisingAndListening

2016-03-11T15:09:52.112Z - info: Running on ios test: 24. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-11T15:09:53.164Z - info: Running on ios test: 25. peerAvailabilityChange is called

2016-03-11T15:09:57.025Z - info: Running on android test: 18. does not send duplicate availability changes

2016-03-11T15:09:58.047Z - info: Running on ios test: 26. Can connect to a remote peer

2016-03-11T15:09:58.528Z - info: Running on android test: 19. can get the network status

2016-03-11T15:10:03.074Z - info: Running on android test: 20. wifi peer is marked unavailable if announcements stop

2016-03-11T15:10:07.597Z - info: Running on android test: 21. Can call start/stopListeningForAdvertisements

2016-03-11T15:10:14.360Z - info: Running on android test: 22. Calling startListeningForAdvertisements twice is NOT an error

2016-03-11T15:10:23.207Z - info: Running on android test: 23. Can call start/stopUpdateAdvertisingAndListening

2016-03-11T15:10:23.919Z - info: Running on android test: 24. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-11T15:10:24.744Z - info: Running on android test: 25. peerAvailabilityChange is called

2016-03-11T15:26:55.556Z - debug: Socket disconnected: transport close 3 (Apple-IpadAir2-1)

2016-03-11T15:26:55.652Z - debug: Socket disconnected: transport close 2 (Apple-Iphone6-1)

2016-03-11T15:29:37.699Z - debug: Socket disconnected: transport close 0 (LGE-LG-H815)

2016-03-11T15:29:44.759Z - debug: Socket disconnected: transport close 1 (samsung-SM-N910C)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m
2016-03-11T15:09:48.871Z - error: test server: Device Apple-Iphone6-1

2016-03-11T15:10:07.070Z - error: test server: Device Apple-IpadAir2-1


```


Logs for system : 
```

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/625481247756efd_More_thaliMobileNativeWrapper_vjrantal/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/625481247756efd_More_thaliMobileNativeWrapper_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/625481247756efd_More_thaliMobileNativeWrapper_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/625481247756efd_More_thaliMobileNativeWrapper_vjrantal/iOS_IpadAir2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/625481247756efd_More_thaliMobileNativeWrapper_vjrantal/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:0 
child process exited with code 0 on device f56ad48d 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/625481247756efd_More_thaliMobileNativeWrapper_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/625481247756efd_More_thaliMobileNativeWrapper_vjrantal/thali02_LGE-LG-D722.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/625481247756efd_More_thaliMobileNativeWrapper_vjrantal/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/625481247756efd_More_thaliMobileNativeWrapper_vjrantal/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:0 
child process exited with code 0 on device LGH8153b36be34 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/625481247756efd_More_thaliMobileNativeWrapper_vjrantal/thali05_LGE-LG-H815.md)

####Node name: thali06
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:null 
child process exited with code null on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:0 
child process exited with code 0 on device FA55PYS00566 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/625481247756efd_More_thaliMobileNativeWrapper_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/625481247756efd_More_thaliMobileNativeWrapper_vjrantal/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:0 
child process exited with code 0 on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/625481247756efd_More_thaliMobileNativeWrapper_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:0 
child process exited with code 0 on device 4325e43f 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/625481247756efd_More_thaliMobileNativeWrapper_vjrantal/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 09a9416e0297d102 app:com.test.thalitest code:0 
child process exited with code 0 on device 09a9416e0297d102 
Android task is completed. [FAILED]
```
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/625481247756efd_More_thaliMobileNativeWrapper_vjrantal/thali09_LGE-Nexus 5.md)





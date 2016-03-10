#### Test 61362366b6c9a6f Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":10}}
2016-03-10T08:40:14.065Z - info: listening on *:3000

2016-03-10T08:40:15.230Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:0

2016-03-10T08:40:15.617Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:1

2016-03-10T08:40:15.620Z - info: Required number of ios devices presented (2)

2016-03-10T08:40:15.623Z - info: Starting unit test run for platform: ios

2016-03-10T08:40:19.537Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:2

2016-03-10T08:40:19.538Z - info: Discarding surplus device: Apple-IpadAir2-1

2016-03-10T08:40:19.579Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:3

2016-03-10T08:40:19.580Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-10T08:40:19.590Z - debug: Device presented: HTC-HTC One M8s (android) unittest socket:5

2016-03-10T08:40:19.835Z - info: Running on ios test: 1. multiplex can send data

2016-03-10T08:40:19.854Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:4

2016-03-10T08:40:19.855Z - info: Required number of android devices presented (2)

2016-03-10T08:40:19.857Z - info: Starting unit test run for platform: android

2016-03-10T08:40:20.330Z - info: Running on android test: 1. multiplex can send data

2016-03-10T08:40:20.533Z - info: Running on ios test: 2. enqueue and run in order

2016-03-10T08:40:20.936Z - info: Running on android test: 2. enqueue and run in order

2016-03-10T08:40:21.281Z - info: Running on ios test: 3. enqueueAtTop and run backwards

2016-03-10T08:40:21.677Z - info: Running on ios test: 4. mix enqueue and enqueueAtTop

2016-03-10T08:40:21.885Z - info: Running on android test: 3. enqueueAtTop and run backwards

2016-03-10T08:40:22.000Z - debug: Socket disconnected: transport close 2 (Apple-IpadAir2-1)

2016-03-10T08:40:22.145Z - info: Running on ios test: 5. queues handled independently

2016-03-10T08:40:22.296Z - info: Running on android test: 4. mix enqueue and enqueueAtTop

2016-03-10T08:40:22.497Z - debug: Socket disconnected: transport close 3 (Apple-Iphone5s-1)

2016-03-10T08:40:22.587Z - info: Running on ios test: 6. basic

2016-03-10T08:40:23.048Z - info: Running on android test: 5. queues handled independently

2016-03-10T08:40:23.141Z - info: Running on ios test: 7. another

2016-03-10T08:40:23.708Z - info: Running on ios test: 8. #startListeningForAdvertisements should fail if start not called

2016-03-10T08:40:23.712Z - info: Running on android test: 6. basic

2016-03-10T08:40:24.129Z - info: Running on android test: 7. another

2016-03-10T08:40:24.179Z - info: Running on ios test: 9. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-10T08:40:24.438Z - info: Running on android test: 8. #startListeningForAdvertisements should fail if start not called

2016-03-10T08:40:24.506Z - info: Running on ios test: 10. should be able to call #stopListeningForAdvertisements many times

2016-03-10T08:40:24.753Z - info: Running on android test: 9. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-10T08:40:24.838Z - info: Running on ios test: 11. should be able to call #startListeningForAdvertisements many times

2016-03-10T08:40:25.082Z - info: Running on android test: 10. should be able to call #stopListeningForAdvertisements many times

2016-03-10T08:40:25.193Z - info: Running on ios test: 12. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-10T08:40:25.537Z - info: Running on android test: 11. should be able to call #startListeningForAdvertisements many times

2016-03-10T08:40:25.664Z - info: Running on ios test: 13. should be able to call #stopAdvertisingAndListening many times

2016-03-10T08:40:26.022Z - info: Running on android test: 12. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-10T08:40:26.187Z - info: Running on ios test: 14. #start should fail if called twice in a row

2016-03-10T08:40:26.551Z - info: Running on android test: 13. should be able to call #stopAdvertisingAndListening many times

2016-03-10T08:40:26.643Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:6

2016-03-10T08:40:26.647Z - info: Discarding surplus device: samsung-SM-N910C

2016-03-10T08:40:26.706Z - info: Running on ios test: 15. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-10T08:40:26.999Z - info: Running on android test: 14. #start should fail if called twice in a row

2016-03-10T08:40:27.033Z - info: Running on ios test: 16. does not send duplicate availability changes

2016-03-10T08:40:27.192Z - debug: Socket disconnected: transport close 6 (samsung-SM-N910C)

2016-03-10T08:40:27.542Z - info: Running on ios test: 17. can get the network status

2016-03-10T08:40:27.548Z - info: Running on android test: 15. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-10T08:40:27.960Z - info: Running on android test: 16. does not send duplicate availability changes

2016-03-10T08:40:27.965Z - info: Running on ios test: 18. wifi peer is marked unavailable if announcements stop

2016-03-10T08:40:28.479Z - info: Running on android test: 17. can get the network status

2016-03-10T08:40:28.936Z - info: Running on android test: 18. wifi peer is marked unavailable if announcements stop

2016-03-10T08:40:29.507Z - info: Running on ios test: 19. Can call start/stopListeningForAdvertisements

2016-03-10T08:40:29.979Z - info: Running on ios test: 20. Calling startListeningForAdvertisements twice is NOT an error

2016-03-10T08:40:30.275Z - info: Running on android test: 19. Can call start/stopListeningForAdvertisements

2016-03-10T08:40:30.701Z - info: Running on ios test: 21. Can call start/stopUpdateAdvertisingAndListening

2016-03-10T08:40:33.619Z - info: Running on ios test: 22. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-10T08:40:34.040Z - info: Running on android test: 20. Calling startListeningForAdvertisements twice is NOT an error

2016-03-10T08:40:34.229Z - info: Running on ios test: 23. peerAvailabilityChange is called

2016-03-10T08:40:38.557Z - info: Running on ios test: 24. Can connect to a remote peer

2016-03-10T08:40:40.825Z - info: Running on android test: 21. Can call start/stopUpdateAdvertisingAndListening

2016-03-10T08:40:44.421Z - info: Running on android test: 22. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-10T08:40:51.276Z - info: Running on android test: 23. peerAvailabilityChange is called

2016-03-10T08:57:50.436Z - debug: Socket disconnected: transport close 0 (Apple-Iphone5-1)

2016-03-10T08:57:50.446Z - debug: Socket disconnected: transport close 1 (Apple-Iphone6-1)

2016-03-10T09:00:28.964Z - debug: Socket disconnected: transport close 4 (LGE-LG-H815)

2016-03-10T09:01:09.018Z - debug: Socket disconnected: transport close 5 (HTC-HTC One M8s)


 
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
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/61362366b6c9a6f_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/61362366b6c9a6f_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/61362366b6c9a6f_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/61362366b6c9a6f_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone6-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/61362366b6c9a6f_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:0 
child process exited with code 0 on device LGH8153b36be34 
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:null 
child process exited with code null on device f56ad48d 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/61362366b6c9a6f_Make_CI_build_and_unit_tests_pass_vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/61362366b6c9a6f_Make_CI_build_and_unit_tests_pass_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 09a9416e0297d102 app:com.test.thalitest code:0 
child process exited with code 0 on device 09a9416e0297d102 
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Android task is completed. [FAILED]
```
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/61362366b6c9a6f_Make_CI_build_and_unit_tests_pass_vjrantal/thali02_LGE-Nexus 5.md)

[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/61362366b6c9a6f_Make_CI_build_and_unit_tests_pass_vjrantal/thali02_LGE-LG-D722.md)

####Node name: thali04
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/61362366b6c9a6f_Make_CI_build_and_unit_tests_pass_vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/61362366b6c9a6f_Make_CI_build_and_unit_tests_pass_vjrantal/thali04_samsung-SM-N910C.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/61362366b6c9a6f_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/61362366b6c9a6f_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:0 
child process exited with code 0 on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/61362366b6c9a6f_Make_CI_build_and_unit_tests_pass_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:0 
child process exited with code 0 on device 4325e43f 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/61362366b6c9a6f_Make_CI_build_and_unit_tests_pass_vjrantal/thali08_samsung-SM-A300FU.md)





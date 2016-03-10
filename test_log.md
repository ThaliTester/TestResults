#### Test 613623667b1a8f4 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":10}}
2016-03-10T15:25:54.628Z - info: listening on *:3000

2016-03-10T15:25:56.705Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:0

2016-03-10T15:25:57.213Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:1

2016-03-10T15:25:58.028Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:3

2016-03-10T15:25:58.032Z - info: Required number of ios devices presented (2)

2016-03-10T15:25:58.036Z - info: Starting unit test run for platform: ios

2016-03-10T15:25:58.062Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:2

2016-03-10T15:25:58.063Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-10T15:25:58.600Z - info: Running on ios test: 1. multiplex can send data

2016-03-10T15:25:58.940Z - info: Running on ios test: 2. enqueue and run in order

2016-03-10T15:25:59.691Z - info: Running on ios test: 3. enqueueAtTop and run backwards

2016-03-10T15:25:59.935Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:4

2016-03-10T15:25:59.936Z - info: Required number of android devices presented (2)

2016-03-10T15:25:59.937Z - info: Starting unit test run for platform: android

2016-03-10T15:26:00.008Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:5

2016-03-10T15:26:00.010Z - info: Discarding surplus device: Apple-Iphone5-1

2016-03-10T15:26:00.228Z - info: Running on ios test: 4. mix enqueue and enqueueAtTop

2016-03-10T15:26:00.559Z - info: Running on android test: 1. multiplex can send data

2016-03-10T15:26:00.655Z - info: Running on ios test: 5. queues handled independently

2016-03-10T15:26:00.996Z - debug: Socket disconnected: transport close 2 (Apple-Iphone5s-1)

2016-03-10T15:26:01.016Z - info: Running on ios test: 6. basic

2016-03-10T15:26:01.089Z - info: Running on android test: 2. enqueue and run in order

2016-03-10T15:26:01.421Z - info: Running on ios test: 7. another

2016-03-10T15:26:01.805Z - info: Running on ios test: 8. #startListeningForAdvertisements should fail if start not called

2016-03-10T15:26:01.934Z - info: Running on android test: 3. enqueueAtTop and run backwards

2016-03-10T15:26:02.269Z - info: Running on ios test: 9. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-10T15:26:02.491Z - info: Running on android test: 4. mix enqueue and enqueueAtTop

2016-03-10T15:26:02.795Z - info: Running on ios test: 10. should be able to call #stopListeningForAdvertisements many times

2016-03-10T15:26:03.202Z - info: Running on android test: 5. queues handled independently

2016-03-10T15:26:03.221Z - info: Running on ios test: 11. should be able to call #startListeningForAdvertisements many times

2016-03-10T15:26:03.273Z - debug: Socket disconnected: transport close 5 (Apple-Iphone5-1)

2016-03-10T15:26:03.715Z - info: Running on android test: 6. basic

2016-03-10T15:26:03.734Z - info: Running on ios test: 12. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-10T15:26:04.079Z - info: Running on android test: 7. another

2016-03-10T15:26:04.123Z - info: Running on ios test: 13. should be able to call #stopAdvertisingAndListening many times

2016-03-10T15:26:04.457Z - info: Running on android test: 8. #startListeningForAdvertisements should fail if start not called

2016-03-10T15:26:04.551Z - info: Running on ios test: 14. #start should fail if called twice in a row

2016-03-10T15:26:04.922Z - info: Running on android test: 9. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-10T15:26:05.011Z - info: Running on ios test: 15. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-10T15:26:05.232Z - info: Running on android test: 10. should be able to call #stopListeningForAdvertisements many times

2016-03-10T15:26:05.316Z - info: Running on ios test: 16. does not send duplicate availability changes

2016-03-10T15:26:05.552Z - info: Running on android test: 11. should be able to call #startListeningForAdvertisements many times

2016-03-10T15:26:05.662Z - info: Running on ios test: 17. can get the network status

2016-03-10T15:26:05.867Z - info: Running on android test: 12. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-10T15:26:05.986Z - info: Running on ios test: 18. wifi peer is marked unavailable if announcements stop

2016-03-10T15:26:06.313Z - info: Running on android test: 13. should be able to call #stopAdvertisingAndListening many times

2016-03-10T15:26:06.729Z - info: Running on android test: 14. #start should fail if called twice in a row

2016-03-10T15:26:07.213Z - info: Running on android test: 15. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-10T15:26:07.385Z - info: Running on ios test: 19. Can call start/stopListeningForAdvertisements

2016-03-10T15:26:07.724Z - info: Running on android test: 16. does not send duplicate availability changes

2016-03-10T15:26:07.979Z - info: Running on ios test: 20. Calling startListeningForAdvertisements twice is NOT an error

2016-03-10T15:26:08.280Z - info: Running on android test: 17. can get the network status

2016-03-10T15:26:08.733Z - info: Running on android test: 18. wifi peer is marked unavailable if announcements stop

2016-03-10T15:26:08.949Z - info: Running on ios test: 21. Can call start/stopUpdateAdvertisingAndListening

2016-03-10T15:26:09.628Z - info: Running on ios test: 22. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-10T15:26:10.172Z - info: Running on android test: 19. Can call start/stopListeningForAdvertisements

2016-03-10T15:26:10.390Z - info: Running on ios test: 23. peerAvailabilityChange is called

2016-03-10T15:26:12.581Z - info: Running on ios test: 24. Can connect to a remote peer

2016-03-10T15:26:14.066Z - info: Running on android test: 20. Calling startListeningForAdvertisements twice is NOT an error

2016-03-10T15:26:21.517Z - info: Running on android test: 21. Can call start/stopUpdateAdvertisingAndListening

2016-03-10T15:26:23.620Z - info: Running on android test: 22. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-10T15:26:24.464Z - info: Running on android test: 23. peerAvailabilityChange is called

2016-03-10T15:43:54.231Z - debug: Socket disconnected: transport close 3 (Apple-IpadAir2-1)

2016-03-10T15:43:54.296Z - debug: Socket disconnected: transport close 1 (Apple-Iphone6-1)

2016-03-10T15:46:32.457Z - debug: Socket disconnected: transport close 0 (LGE-LG-H815)

2016-03-10T15:46:35.664Z - debug: Socket disconnected: transport close 4 (samsung-SM-N910C)


 
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
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/613623667b1a8f4_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/613623667b1a8f4_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/613623667b1a8f4_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/613623667b1a8f4_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone6-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/613623667b1a8f4_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:0 
child process exited with code 0 on device f56ad48d 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/613623667b1a8f4_Make_CI_build_and_unit_tests_pass_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/613623667b1a8f4_Make_CI_build_and_unit_tests_pass_vjrantal/thali02_LGE-LG-D722.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/613623667b1a8f4_Make_CI_build_and_unit_tests_pass_vjrantal/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/613623667b1a8f4_Make_CI_build_and_unit_tests_pass_vjrantal/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:0 
child process exited with code 0 on device LGH8153b36be34 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/613623667b1a8f4_Make_CI_build_and_unit_tests_pass_vjrantal/thali05_LGE-LG-H815.md)

####Node name: thali06
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:0 
child process exited with code 0 on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:null 
child process exited with code null on device FA55PYS00566 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/613623667b1a8f4_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/613623667b1a8f4_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:0 
child process exited with code 0 on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/613623667b1a8f4_Make_CI_build_and_unit_tests_pass_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:0 
child process exited with code 0 on device 4325e43f 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/613623667b1a8f4_Make_CI_build_and_unit_tests_pass_vjrantal/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 09a9416e0297d102 app:com.test.thalitest code:0 
child process exited with code 0 on device 09a9416e0297d102 
Android task is completed. [FAILED]
```
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/613623667b1a8f4_Make_CI_build_and_unit_tests_pass_vjrantal/thali09_LGE-Nexus 5.md)





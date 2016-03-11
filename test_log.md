#### Test 62509094a319d1d Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":10}}
2016-03-11T14:38:47.297Z - info: listening on *:3000

2016-03-11T14:38:48.435Z - debug: Device presented: samsung-SM-A500FU (android) unittest socket:2

2016-03-11T14:38:48.446Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:1

2016-03-11T14:38:48.496Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:0

2016-03-11T14:38:48.499Z - info: Required number of ios devices presented (2)

2016-03-11T14:38:48.502Z - info: Starting unit test run for platform: ios

2016-03-11T14:38:48.526Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:3

2016-03-11T14:38:48.527Z - info: Required number of android devices presented (2)

2016-03-11T14:38:48.529Z - info: Starting unit test run for platform: android

2016-03-11T14:38:48.850Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:4

2016-03-11T14:38:48.851Z - info: Discarding surplus device: Apple-IpadAir2-1

2016-03-11T14:38:49.018Z - debug: Device presented: samsung-SM-A300FU (android) unittest socket:5

2016-03-11T14:38:49.019Z - info: Discarding surplus device: samsung-SM-A300FU

2016-03-11T14:38:49.053Z - info: Running on android test: 1. closeAll can close even when connections open

2016-03-11T14:38:49.207Z - info: Running on ios test: 1. closeAll can close even when connections open

2016-03-11T14:38:49.594Z - info: Running on android test: 2. closeAll with promise

2016-03-11T14:38:49.746Z - info: Running on ios test: 2. closeAll with promise

2016-03-11T14:38:49.779Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:6

2016-03-11T14:38:49.780Z - info: Discarding surplus device: samsung-SM-N910C

2016-03-11T14:38:50.174Z - info: Running on android test: 3. multiplex can send data

2016-03-11T14:38:50.391Z - info: Running on ios test: 3. multiplex can send data

2016-03-11T14:38:50.882Z - info: Running on android test: 4. enqueue and run in order

2016-03-11T14:38:51.289Z - debug: Socket disconnected: transport close 6 (samsung-SM-N910C)

2016-03-11T14:38:51.497Z - debug: Socket disconnected: transport close 4 (Apple-IpadAir2-1)

2016-03-11T14:38:51.558Z - info: Running on ios test: 4. enqueue and run in order

2016-03-11T14:38:52.282Z - info: Running on android test: 5. enqueueAtTop and run backwards

2016-03-11T14:38:52.422Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:7

2016-03-11T14:38:52.423Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-11T14:38:52.538Z - debug: Device presented: samsung-SM-A500FU (android) unittest socket:8

2016-03-11T14:38:52.539Z - info: Discarding surplus device: samsung-SM-A500FU

2016-03-11T14:38:54.032Z - info: Running on ios test: 5. enqueueAtTop and run backwards

2016-03-11T14:38:54.775Z - info: Running on android test: 6. mix enqueue and enqueueAtTop

2016-03-11T14:38:55.311Z - info: Running on android test: 7. queues handled independently

2016-03-11T14:38:55.719Z - info: Running on android test: 8. basic

2016-03-11T14:38:56.194Z - info: Running on android test: 9. another

2016-03-11T14:38:57.257Z - info: Running on ios test: 6. mix enqueue and enqueueAtTop

2016-03-11T14:38:57.391Z - info: Running on android test: 10. #startListeningForAdvertisements should fail if start not called

2016-03-11T14:38:58.094Z - debug: Socket disconnected: transport close 7 (Apple-Iphone5s-1)

2016-03-11T14:38:58.167Z - info: Running on ios test: 7. queues handled independently

2016-03-11T14:38:58.526Z - info: Running on android test: 11. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-11T14:38:58.726Z - info: Running on ios test: 8. basic

2016-03-11T14:38:58.940Z - info: Running on android test: 12. should be able to call #stopListeningForAdvertisements many times

2016-03-11T14:38:59.159Z - info: Running on ios test: 9. another

2016-03-11T14:38:59.574Z - info: Running on ios test: 10. #startListeningForAdvertisements should fail if start not called

2016-03-11T14:38:59.944Z - info: Running on android test: 13. should be able to call #startListeningForAdvertisements many times

2016-03-11T14:39:00.156Z - info: Running on ios test: 11. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-11T14:39:00.726Z - info: Running on android test: 14. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-11T14:39:01.003Z - info: Running on ios test: 12. should be able to call #stopListeningForAdvertisements many times

2016-03-11T14:39:01.255Z - info: Running on android test: 15. should be able to call #stopAdvertisingAndListening many times

2016-03-11T14:39:01.501Z - info: Running on ios test: 13. should be able to call #startListeningForAdvertisements many times

2016-03-11T14:39:01.945Z - info: Running on android test: 16. #start should fail if called twice in a row

2016-03-11T14:39:02.120Z - info: Running on ios test: 14. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-11T14:39:02.629Z - info: Running on android test: 17. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-11T14:39:02.730Z - info: Running on ios test: 15. should be able to call #stopAdvertisingAndListening many times

2016-03-11T14:39:03.397Z - info: Running on android test: 18. does not send duplicate availability changes

2016-03-11T14:39:03.763Z - info: Running on ios test: 16. #start should fail if called twice in a row

2016-03-11T14:39:03.861Z - info: Running on android test: 19. can get the network status

2016-03-11T14:39:05.043Z - info: Running on android test: 20. wifi peer is marked unavailable if announcements stop

2016-03-11T14:39:05.811Z - debug: Device presented: samsung-SM-A300FU (android) unittest socket:9

2016-03-11T14:39:05.813Z - info: Discarding surplus device: samsung-SM-A300FU

2016-03-11T14:39:05.823Z - info: Running on ios test: 17. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-11T14:39:06.567Z - info: Running on ios test: 18. does not send duplicate availability changes

2016-03-11T14:39:06.659Z - debug: Socket disconnected: transport close 9 (samsung-SM-A300FU)

2016-03-11T14:39:06.819Z - info: Running on android test: 21. can get the network status before starting

2016-03-11T14:39:07.301Z - info: Running on ios test: 19. can get the network status

2016-03-11T14:39:07.943Z - info: Running on android test: 22. #generatePreambleAndBeacons bad args

2016-03-11T14:39:08.458Z - info: Running on ios test: 20. wifi peer is marked unavailable if announcements stop

2016-03-11T14:39:09.310Z - debug: Socket disconnected: transport close 3 (LGE-LG-H815)

2016-03-11T14:39:09.867Z - info: Running on ios test: 21. can get the network status before starting

2016-03-11T14:39:10.087Z - debug: Device presented: HTC-HTC One M8s (android) unittest socket:10

2016-03-11T14:39:10.090Z - info: Discarding surplus device: HTC-HTC One M8s

2016-03-11T14:39:10.236Z - info: Running on ios test: 22. #generatePreambleAndBeacons bad args

2016-03-11T14:39:10.983Z - debug: Socket disconnected: transport close 10 (HTC-HTC One M8s)

2016-03-11T14:39:13.207Z - debug: Socket disconnected: transport close 0 (Apple-Iphone6-1)

2016-03-11T14:39:13.556Z - debug: Socket disconnected: transport close 1 (Apple-Iphone5-1)

2016-03-11T14:40:13.547Z - debug: Socket disconnected: transport close 2 (samsung-SM-A500FU)


 
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
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/62509094a319d1d_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/62509094a319d1d_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/62509094a319d1d_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/62509094a319d1d_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_IpadAir2-1.md)


###Android Logs
####Node name: thali01
Console output:
```
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:0 
child process exited with code 0 on device f56ad48d 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62509094a319d1d_Make_CI_build_and_unit_tests_pass_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/62509094a319d1d_Make_CI_build_and_unit_tests_pass_vjrantal/thali02_LGE-LG-D722.md)

####Node name: thali03
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Android task is completed. [SUCCESS]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/62509094a319d1d_Make_CI_build_and_unit_tests_pass_vjrantal/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on ZX1C223JKW 
Android task is completed. [SUCCESS]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/62509094a319d1d_Make_CI_build_and_unit_tests_pass_vjrantal/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
STOP log received from  LGH8153b36be34 Test has  FAILED
Device test finished on LGH8153b36be34 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/62509094a319d1d_Make_CI_build_and_unit_tests_pass_vjrantal/thali05_LGE-LG-H815.md)

####Node name: thali06
Console output:
```
STOP log received from  7970f88c Test has  SUCCEEDED
Device test finished on 7970f88c 
STOP log received from  FA55PYS00566 Test has  SUCCEEDED
Device test finished on FA55PYS00566 
Android task is completed. [SUCCESS]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62509094a319d1d_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/62509094a319d1d_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:0 
child process exited with code 0 on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/62509094a319d1d_Make_CI_build_and_unit_tests_pass_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:0 
child process exited with code 0 on device 4325e43f 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/62509094a319d1d_Make_CI_build_and_unit_tests_pass_vjrantal/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 09a9416e0297d102 app:com.test.thalitest code:0 
child process exited with code 0 on device 09a9416e0297d102 
Android task is completed. [FAILED]
```
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/62509094a319d1d_Make_CI_build_and_unit_tests_pass_vjrantal/thali09_LGE-Nexus 5.md)





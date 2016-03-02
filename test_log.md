#### Test 613623660556c10 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":22}}
2016-03-02T08:57:59.189Z - info: listening on *:3000

2016-03-02T08:57:59.811Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:1

2016-03-02T08:57:59.832Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:0

2016-03-02T08:57:59.835Z - info: Required number of android devices presented (2)

2016-03-02T08:57:59.838Z - info: Starting unit test run for platform: android

2016-03-02T08:58:00.194Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:2

2016-03-02T08:58:00.195Z - info: Discarding surplus device: LGE-Nexus 5

2016-03-02T08:58:00.469Z - info: Running on android test: 1. multiplex can send data

2016-03-02T08:58:00.733Z - debug: Socket disconnected: transport close 2 (LGE-Nexus 5)

2016-03-02T08:58:00.891Z - info: Running on android test: 2. enqueue and run in order

2016-03-02T08:58:01.560Z - info: Running on android test: 3. enqueueAtTop and run backwards

2016-03-02T08:58:01.915Z - info: Running on android test: 4. mix enqueue and enqueueAtTop

2016-03-02T08:58:02.348Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:3

2016-03-02T08:58:02.360Z - info: Running on android test: 5. queues handled independently

2016-03-02T08:58:02.371Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:4

2016-03-02T08:58:02.372Z - info: Discarding surplus device: LGE-LG-D855

2016-03-02T08:58:02.620Z - info: Running on android test: 6. basic

2016-03-02T08:58:02.889Z - info: Running on android test: 7. another

2016-03-02T08:58:02.902Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:5

2016-03-02T08:58:02.903Z - info: Required number of ios devices presented (2)

2016-03-02T08:58:02.904Z - info: Starting unit test run for platform: ios

2016-03-02T08:58:03.062Z - debug: Socket disconnected: transport close 4 (LGE-LG-D855)

2016-03-02T08:58:03.081Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:6

2016-03-02T08:58:03.084Z - info: Discarding surplus device: Apple-Iphone5-1

2016-03-02T08:58:03.166Z - info: Running on android test: 8. #startListeningForAdvertisements should fail if start not called

2016-03-02T08:58:03.503Z - info: Running on android test: 9. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-02T08:58:03.697Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:7

2016-03-02T08:58:03.698Z - info: Discarding surplus device: Apple-Iphone6-1

2016-03-02T08:58:03.821Z - info: Running on android test: 10. should be able to call #stopListeningForAdvertisements many times

2016-03-02T08:58:04.073Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:8

2016-03-02T08:58:04.075Z - info: Discarding surplus device: LGE-LG-H815

2016-03-02T08:58:04.272Z - info: Running on android test: 11. should be able to call #startListeningForAdvertisements many times

2016-03-02T08:58:04.293Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:9

2016-03-02T08:58:04.294Z - info: Discarding surplus device: LGE-LG-D722

2016-03-02T08:58:04.375Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:10

2016-03-02T08:58:04.376Z - info: Discarding surplus device: samsung-SM-G900F

2016-03-02T08:58:04.841Z - info: Running on android test: 12. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-02T08:58:04.988Z - info: Running on ios test: 1. multiplex can send data

2016-03-02T08:58:05.126Z - debug: Socket disconnected: transport close 8 (LGE-LG-H815)

2016-03-02T08:58:05.365Z - info: Running on android test: 13. should be able to call #stopAdvertisingAndListening many times

2016-03-02T08:58:05.451Z - debug: Socket disconnected: transport close 9 (LGE-LG-D722)

2016-03-02T08:58:05.636Z - debug: Socket disconnected: transport close 10 (samsung-SM-G900F)

2016-03-02T08:58:05.701Z - info: Running on ios test: 2. enqueue and run in order

2016-03-02T08:58:05.757Z - info: Running on android test: 14. #start should fail if called twice in a row

2016-03-02T08:58:06.194Z - info: Running on android test: 15. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-02T08:58:06.262Z - info: Running on ios test: 3. enqueueAtTop and run backwards

2016-03-02T08:58:06.293Z - debug: Socket disconnected: transport close 6 (Apple-Iphone5-1)

2016-03-02T08:58:06.433Z - debug: Socket disconnected: transport close 7 (Apple-Iphone6-1)

2016-03-02T08:58:06.526Z - info: Running on ios test: 4. mix enqueue and enqueueAtTop

2016-03-02T08:58:06.579Z - info: Running on android test: 16. does not send duplicate availability changes

2016-03-02T08:58:06.851Z - info: Running on ios test: 5. queues handled independently

2016-03-02T08:58:06.900Z - info: Running on android test: 17. can get the network status

2016-03-02T08:58:07.139Z - info: Running on ios test: 6. basic

2016-03-02T08:58:07.196Z - info: Running on android test: 18. wifi peer is marked unavailable if announcements stop

2016-03-02T08:58:07.450Z - info: Running on ios test: 7. another

2016-03-02T08:58:07.772Z - info: Running on ios test: 8. #startListeningForAdvertisements should fail if start not called

2016-03-02T08:58:08.118Z - info: Running on ios test: 9. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-02T08:58:08.460Z - info: Running on ios test: 10. should be able to call #stopListeningForAdvertisements many times

2016-03-02T08:58:08.586Z - info: Running on android test: 19. Can call start/stopListeningForAdvertisements

2016-03-02T08:58:08.836Z - info: Running on ios test: 11. should be able to call #startListeningForAdvertisements many times

2016-03-02T08:58:09.157Z - info: Running on ios test: 12. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-02T08:58:09.239Z - info: Running on android test: 20. Calling startListeningForAdvertisements twice is an error

2016-03-02T08:58:09.479Z - info: Running on ios test: 13. should be able to call #stopAdvertisingAndListening many times

2016-03-02T08:58:09.830Z - info: Running on android test: 21. Can call start/stopUpdateAdvertisingAndListening

2016-03-02T08:58:09.843Z - info: Running on ios test: 14. #start should fail if called twice in a row

2016-03-02T08:58:10.101Z - info: Running on ios test: 15. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-02T08:58:10.313Z - info: Running on android test: 22. Calling startUpdateAdvertisingAndListening twice is NOT and error

2016-03-02T08:58:10.407Z - info: Running on ios test: 16. does not send duplicate availability changes

2016-03-02T08:58:10.714Z - info: Running on ios test: 17. can get the network status

2016-03-02T08:58:10.839Z - info: Running on android test: 23. peerAvailabilityChange is called

2016-03-02T08:58:11.078Z - info: Running on ios test: 18. wifi peer is marked unavailable if announcements stop

2016-03-02T08:58:21.634Z - debug: Device presented: samsung-SM-N9005 (android) unittest socket:11

2016-03-02T08:58:21.635Z - info: Discarding surplus device: samsung-SM-N9005

2016-03-02T08:58:22.431Z - debug: Socket disconnected: transport close 11 (samsung-SM-N9005)

2016-03-02T09:11:14.593Z - debug: Socket disconnected: transport close 5 (Apple-IpadAir2-1)

2016-03-02T09:11:14.670Z - debug: Socket disconnected: transport close 3 (Apple-Iphone5s-1)

2016-03-02T09:16:02.756Z - debug: Socket disconnected: transport close 0 (samsung-SM-G900F)

2016-03-02T09:16:06.965Z - debug: Socket disconnected: transport close 1 (samsung-SM-N910C)


 
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
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/613623660556c10_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/613623660556c10_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/613623660556c10_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/613623660556c10_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone6-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/613623660556c10_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:null 
child process exited with code null on device f56ad48d 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/613623660556c10_Make_CI_build_and_unit_tests_pass_vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/613623660556c10_Make_CI_build_and_unit_tests_pass_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/613623660556c10_Make_CI_build_and_unit_tests_pass_vjrantal/thali02_LGE-Nexus 5.md)

[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/613623660556c10_Make_CI_build_and_unit_tests_pass_vjrantal/thali02_LGE-LG-D722.md)

####Node name: thali03
Console output:
```
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:0 
child process exited with code 0 on device 320414cd475f91e3 
Android task is completed. [FAILED]
```
[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/613623660556c10_Make_CI_build_and_unit_tests_pass_vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/613623660556c10_Make_CI_build_and_unit_tests_pass_vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 0be0c6c6 app:com.test.thalitest code:null 
child process exited with code null on device 0be0c6c6 
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/613623660556c10_Make_CI_build_and_unit_tests_pass_vjrantal/thali04_samsung-SM-G900F.md)

[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/613623660556c10_Make_CI_build_and_unit_tests_pass_vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/613623660556c10_Make_CI_build_and_unit_tests_pass_vjrantal/thali04_samsung-SM-N910C.md)

####Node name: thali05
Console output:
```
STOP log received from  1d6a772d Test has  SUCCEEDED
Device test finished on 1d6a772d 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device HT4BLJT02274 app:com.test.thalitest code:0 
child process exited with code 0 on device HT4BLJT02274 
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1G429CRK 
Error! Unexpected exit on device 954a12ed app:com.test.thalitest code:0 
child process exited with code 0 on device 954a12ed 
Android task is completed. [FAILED]
```
[htc-Nexus 9](https://github.com/ThaliTester/TestResults/blob/613623660556c10_Make_CI_build_and_unit_tests_pass_vjrantal/thali05_htc-Nexus 9.md)

[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/613623660556c10_Make_CI_build_and_unit_tests_pass_vjrantal/thali05_samsung-SM-N9005.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/613623660556c10_Make_CI_build_and_unit_tests_pass_vjrantal/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/613623660556c10_Make_CI_build_and_unit_tests_pass_vjrantal/thali05_samsung-SM-G800H.md)

####Node name: thali06
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:0 
child process exited with code 0 on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:null 
child process exited with code null on device FA55PYS00566 
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:0 
child process exited with code 0 on device 022678fb504e29b0 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/613623660556c10_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/613623660556c10_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/613623660556c10_Make_CI_build_and_unit_tests_pass_vjrantal/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
STOP log received from  c5afcdcb Test has  SUCCEEDED
Device test finished on c5afcdcb 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:0 
child process exited with code 0 on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/613623660556c10_Make_CI_build_and_unit_tests_pass_vjrantal/thali07_samsung-SM-A500FU.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/613623660556c10_Make_CI_build_and_unit_tests_pass_vjrantal/thali07_samsung-SM-G900F.md)

####Node name: thali08
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device HT574YC04723 app:com.test.thalitest code:null 
child process exited with code null on device HT574YC04723 
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:null 
child process exited with code null on device 4325e43f 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/613623660556c10_Make_CI_build_and_unit_tests_pass_vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/613623660556c10_Make_CI_build_and_unit_tests_pass_vjrantal/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device CC51WYC03425 app:com.test.thalitest code:null 
child process exited with code null on device CC51WYC03425 
Error! Unexpected exit on device 0c6a0f3c0bdb4e77 app:com.test.thalitest code:0 
child process exited with code 0 on device 0c6a0f3c0bdb4e77 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/613623660556c10_Make_CI_build_and_unit_tests_pass_vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/613623660556c10_Make_CI_build_and_unit_tests_pass_vjrantal/thali09_LGE-Nexus 5.md)





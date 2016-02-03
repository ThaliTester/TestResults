#### Test 58135655c662d33 Logs

#### Test Server Logs
```
Error: Command failed: 
/home/pi/Test/server_58135655c662d33/test/TestServer/UnitTestFramework.js:97

            throw new Error("Unrecoverable error - Device not responding");
                  ^


Error: Unrecoverable error - Device not responding
    at _emit [as _onTimeout] (/home/pi/Test/server_58135655c662d33/test/TestServer/UnitTestFramework.js:97:19)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)

IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":21}}
2016-02-03T18:15:29.361Z - info: listening on *:3000

2016-02-03T18:15:29.738Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:0

2016-02-03T18:15:29.764Z - debug: Device presented: HTC-HTC One M8s (android) unittest socket:1

2016-02-03T18:15:29.767Z - info: Required number of android devices presented (2)

2016-02-03T18:15:29.771Z - info: Starting unit test run for platform: android

2016-02-03T18:15:30.114Z - info: Running on android test: multiplex can send data

emit: setup_multiplex can send data

emit: setup_multiplex can send data

2016-02-03T18:15:30.137Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:2

2016-02-03T18:15:30.138Z - info: Discarding surplus device: LGE-LG-H815

emit: teardown_multiplex can send data

emit: teardown_multiplex can send data

2016-02-03T18:15:30.708Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:3

2016-02-03T18:15:30.709Z - info: Discarding surplus device: LGE-Nexus 5

emit: setup_multiplex can send data

emit: setup_multiplex can send data

2016-02-03T18:15:31.168Z - debug: Socket disconnected: transport close 3 (LGE-Nexus 5)

2016-02-03T18:15:31.188Z - debug: Socket disconnected: transport close 2 (LGE-LG-H815)

2016-02-03T18:15:31.236Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:4

2016-02-03T18:15:31.322Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:5

2016-02-03T18:15:31.324Z - info: Discarding surplus device: motorola-Nexus 6

emit: teardown_multiplex can send data

emit: teardown_multiplex can send data

2016-02-03T18:15:31.540Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:6

2016-02-03T18:15:31.541Z - info: Discarding surplus device: LGE-LG-D855

2016-02-03T18:15:31.931Z - debug: Socket disconnected: transport close 5 (motorola-Nexus 6)

emit: setup_multiplex can send data

emit: setup_multiplex can send data

emit: teardown_multiplex can send data

emit: teardown_multiplex can send data

2016-02-03T18:15:32.522Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:7

2016-02-03T18:15:32.523Z - info: Required number of ios devices presented (2)

2016-02-03T18:15:32.525Z - info: Starting unit test run for platform: ios

2016-02-03T18:15:32.938Z - debug: Socket disconnected: transport close 6 (LGE-LG-D855)

emit: setup_multiplex can send data

emit: setup_multiplex can send data

2016-02-03T18:15:33.176Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:9

2016-02-03T18:15:33.177Z - info: Discarding surplus device: samsung-SM-N910C

emit: teardown_multiplex can send data

emit: teardown_multiplex can send data

2016-02-03T18:15:33.976Z - debug: Socket disconnected: transport close 9 (samsung-SM-N910C)

2016-02-03T18:15:34.062Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:8

2016-02-03T18:15:34.065Z - info: Discarding surplus device: Apple-Iphone5-1

emit: setup_multiplex can send data

emit: setup_multiplex can send data

emit: teardown_multiplex can send data

emit: teardown_multiplex can send data

2016-02-03T18:15:34.563Z - info: Running on ios test: multiplex can send data

emit: setup_multiplex can send data

emit: setup_multiplex can send data

emit: setup_multiplex can send data

emit: setup_multiplex can send data

emit: teardown_multiplex can send data

emit: teardown_multiplex can send data

emit: setup_multiplex can send data

emit: setup_multiplex can send data

emit: setup_multiplex can send data

emit: setup_multiplex can send data

emit: teardown_multiplex can send data

emit: teardown_multiplex can send data

emit: setup_multiplex can send data

emit: setup_multiplex can send data

emit: setup_multiplex can send data

emit: setup_multiplex can send data

emit: teardown_multiplex can send data

emit: teardown_multiplex can send data

emit: setup_multiplex can send data

emit: setup_multiplex can send data

2016-02-03T18:15:37.751Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:10

2016-02-03T18:15:37.752Z - info: Discarding surplus device: samsung-SM-G900F

emit: setup_multiplex can send data

emit: setup_multiplex can send data

2016-02-03T18:15:38.423Z - debug: Socket disconnected: transport close 10 (samsung-SM-G900F)

emit: teardown_multiplex can send data

emit: teardown_multiplex can send data

emit: setup_multiplex can send data

emit: setup_multiplex can send data

emit: setup_multiplex can send data


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

/home/pi/Test/server_58135655c662d33/test/TestServer/UnitTestFramework.js:97

            throw new Error("Unrecoverable error - Device not responding");
                  ^


Error: Unrecoverable error - Device not responding
    at _emit [as _onTimeout] (/home/pi/Test/server_58135655c662d33/test/TestServer/UnitTestFramework.js:97:19)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)


```


Logs for system : 
```

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true

```
###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:null 
child process exited with code null on device f56ad48d 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/58135655c662d33_Remove_race_in_tests_tobybrad/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/58135655c662d33_Remove_race_in_tests_tobybrad/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:null 
child process exited with code null on device LGD7228ee9cf5b 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/58135655c662d33_Remove_race_in_tests_tobybrad/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/58135655c662d33_Remove_race_in_tests_tobybrad/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
Error! Unexpected exit on device TA4750HV7I app:com.test.thalitest code:null 
child process exited with code null on device TA4750HV7I 
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:null 
child process exited with code null on device 320414cd475f91e3 
Android task is completed. [FAILED]
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/58135655c662d33_Remove_race_in_tests_tobybrad/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/58135655c662d33_Remove_race_in_tests_tobybrad/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/58135655c662d33_Remove_race_in_tests_tobybrad/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
STOP log received from  0be0c6c6 Test has  SUCCEEDED
Device test finished on 0be0c6c6 
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:null 
child process exited with code null on device ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/58135655c662d33_Remove_race_in_tests_tobybrad/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/58135655c662d33_Remove_race_in_tests_tobybrad/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/58135655c662d33_Remove_race_in_tests_tobybrad/thali04_samsung-SM-G900F.md)

####Node name: thali05
Console output:
```
Error! Unexpected exit on device 954a12ed app:com.test.thalitest code:0 
child process exited with code 0 on device 954a12ed 
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/58135655c662d33_Remove_race_in_tests_tobybrad/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/58135655c662d33_Remove_race_in_tests_tobybrad/thali05_samsung-SM-G800H.md)

####Node name: thali06
Console output:
```
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:null 
child process exited with code null on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:null 
child process exited with code null on device FA55PYS00566 
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:null 
child process exited with code null on device 022678fb504e29b0 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/58135655c662d33_Remove_race_in_tests_tobybrad/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/58135655c662d33_Remove_race_in_tests_tobybrad/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/58135655c662d33_Remove_race_in_tests_tobybrad/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:null 
child process exited with code null on device 4db5c8cc 
Error! Unexpected exit on device c5afcdcb app:com.test.thalitest code:null 
child process exited with code null on device c5afcdcb 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/58135655c662d33_Remove_race_in_tests_tobybrad/thali07_samsung-SM-A500FU.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/58135655c662d33_Remove_race_in_tests_tobybrad/thali07_samsung-SM-G900F.md)

####Node name: thali08
Console output:
```
Error! Unexpected exit on device HT574YC04723 app:com.test.thalitest code:null 
child process exited with code null on device HT574YC04723 
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:null 
child process exited with code null on device 4325e43f 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/58135655c662d33_Remove_race_in_tests_tobybrad/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/58135655c662d33_Remove_race_in_tests_tobybrad/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
Error! Unexpected exit on device CC51WYC03425 app:com.test.thalitest code:null 
child process exited with code null on device CC51WYC03425 
Error! Unexpected exit on device 0c6a0f3c0bdb4e77 app:com.test.thalitest code:null 
child process exited with code null on device 0c6a0f3c0bdb4e77 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/58135655c662d33_Remove_race_in_tests_tobybrad/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/58135655c662d33_Remove_race_in_tests_tobybrad/thali09_LGE-Nexus 5.md)


###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/58135655c662d33_Remove_race_in_tests_tobybrad/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/58135655c662d33_Remove_race_in_tests_tobybrad/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/58135655c662d33_Remove_race_in_tests_tobybrad/iOS_Iphone5-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/58135655c662d33_Remove_race_in_tests_tobybrad/iOS_server.md)





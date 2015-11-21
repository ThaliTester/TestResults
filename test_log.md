#### Test 51335028aa5f981 Logs

Status: 
```

ios : false

server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":15}}
Android tests will start after waiting for 300 seconds

Test ID 0 configuration: testSendData.js, server timeout : 1600000, data : {"timeout":"1500000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}
iOS tests will start after waiting for 300 seconds
Test ID 0 configuration: testSendData.js, server timeout : 1600000, data : {"timeout":"1500000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}

listening on *:3000

Seconds since start: 0.679 - Android LGE-LG-D855_PT7598 added (current device count 1)

Seconds since start: 0.696 - Android HTC-HTC Desire 820_PT511 added (current device count 2)

Seconds since start: 0.746 - Android samsung-SM-A500FU_PT6164 added (current device count 3)

Seconds since start: 1.351 - Android HTC-HTC Desire 820_PT2141 added (current device count 4)

Seconds since start: 1.679 - Android LGE-Nexus 5_PT5726 added (current device count 5)

Seconds since start: 1.831 - iOS Apple-IpadAir2-1_PT437 added (current device count 1)

Seconds since start: 2.183 - Android HUAWEI-ALE-L21_PT1144 added (current device count 6)

Seconds since start: 2.352 - Android LGE-LG-D722_PT2554 added (current device count 7)

Seconds since start: 2.376 - Android samsung-SM-N9005_PT2503 added (current device count 8)

Seconds since start: 2.977 - Android motorola-Nexus 6_PT4471 added (current device count 9)

Seconds since start: 3.161 - Android LGE-LG-H815_PT2441 added (current device count 10)

Seconds since start: 3.475 - Android LGE-Nexus 5_PT5048 added (current device count 11)

Seconds since start: 4.116 - Android HTC-HTC One_M8_PT296 added (current device count 12)

Seconds since start: 4.259 - iOS Apple-Iphone5-1_PT9936 added (current device count 2)

Seconds since start: 4.708 - iOS Apple-Iphone5s-1_PT7804 added (current device count 3)

Seconds since start: 4.792 - Android samsung-SM-A300FU_PT410 added (current device count 13)

Seconds since start: 4.848 - iOS Apple-Iphone6-1_PT1827 added (current device count 4)

Seconds since start: 5.261 - Android samsung-SM-G800F_PT348 added (current device count 14)

Seconds since start: 15.315 - Android motorola-XT1039_PT8322 added (current device count 15)

-------------- We got wait done, now starting the testing process ------------------

Seconds since start: 300.061 - Android start testing now with 15 devices

Seconds since start: 300.092 - iOS start testing now with 4 devices

Seconds since start: 311.256 - iOS Apple-Iphone6-1_PT1827 test took 11161ms - results peers[0], reConnects[0], sendData[3]

Seconds since start: 311.262 - iOS Apple-Iphone5s-1_PT7804 test took 11169ms - results peers[0], reConnects[0], sendData[3]

Seconds since start: 312.8 - iOS Apple-IpadAir2-1_PT437 test took 12708ms - results peers[0], reConnects[0], sendData[3]

Seconds since start: 317.112 - iOS Apple-Iphone5-1_PT9936 test took 17019ms - results peers[0], reConnects[0], sendData[3]

Seconds since start: 317.113 - iOS test ID 0 done now

Seconds since start: 317.12 - iOS All tests are done, preparing test report

--------------- test report ---------------------

--------------- Apple-IpadAir2-1_PT437 --------------------- : 1

sendList : 100% : 4057 ms, 99% : 4057 ms, 95 : 4057 ms, 90% : 4057 ms.

Result count 3, range 3146 ms to  4057 ms.

sendList failed peers count : 0 [0 %]

sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5-1_PT9936 --------------------- : 2

sendList : 100% : 9602 ms, 99% : 9602 ms, 95 : 9602 ms, 90% : 9602 ms.
Result count 3, range 2823 ms to  9602 ms.
sendList failed peers count : 0 [0 %]

sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5s-1_PT7804 --------------------- : 3

sendList : 100% : 3658 ms, 99% : 3658 ms, 95 : 3658 ms, 90% : 3658 ms.
Result count 3, range 2916 ms to  3658 ms.
sendList failed peers count : 0 [0 %]

sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1_PT1827 --------------------- : 4

sendList : 100% : 4183 ms, 99% : 4183 ms, 95 : 4183 ms, 90% : 4183 ms.
Result count 3, range 2692 ms to  4183 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- Combined ---------------------

sendList : 100% : 9602 ms, 99% : 9602 ms, 95 : 4183 ms, 90% : 4183 ms.

--------------- end of test report ---------------------

Seconds since start: 337.506 - Android HTC-HTC Desire 820_PT511 got re-connected event

Seconds since start: 386.103 - Android HTC-HTC Desire 820_PT511 got disconnected

Seconds since start: 387.462 - Android LGE-Nexus 5_PT5726 got disconnected

Seconds since start: 390.853 - Android samsung-SM-G800F_PT348 got disconnected

Seconds since start: 416.507 - Android samsung-SM-A300FU_PT410 got disconnected

Seconds since start: 566.003 - Android samsung-SM-A500FU_PT6164 got disconnected

Seconds since start: 582.395 - Android LGE-LG-D855_PT7598 got disconnected

Seconds since start: 585.733 - Android motorola-Nexus 6_PT4471 test took 285656ms - results peers[0], reConnects[0], sendData[14]

Seconds since start: 665.836 - Android LGE-LG-D722_PT2554 got disconnected

Seconds since start: 677.817 - Android HTC-HTC Desire 820_PT2141 got disconnected

Seconds since start: 691.237 - Android motorola-XT1039_PT8322 got disconnected

Seconds since start: 720.904 - Android motorola-XT1039_PT8322 got re-connected event

Seconds since start: 739.234 - Android LGE-LG-H815_PT2441 test took 439156ms - results peers[0], reConnects[0], sendData[14]

Seconds since start: 872.136 - Android motorola-XT1039_PT8322 got re-connected event

Seconds since start: 881.433 - Android motorola-XT1039_PT8322 got disconnected

Seconds since start: 915.96 - Android motorola-XT1039_PT8322 got re-connected event

Seconds since start: 957.137 - Android motorola-XT1039_PT8322 got disconnected

Seconds since start: 1067.605 - Android motorola-XT1039_PT8322 got disconnected

Seconds since start: 1068.978 - Android motorola-XT1039_PT8322 got re-connected event

Seconds since start: 1128.579 - Android motorola-XT1039_PT8322 got re-connected event

Seconds since start: 1153.979 - Android motorola-XT1039_PT8322 got disconnected

Seconds since start: 1176.734 - Android HTC-HTC Desire 820_PT2141 got re-connected event

Seconds since start: 1241.257 - Android motorola-XT1039_PT8322 got re-connected event

Seconds since start: 1288.694 - Android motorola-XT1039_PT8322 got disconnected

Seconds since start: 1611.788 - Android LGE-Nexus 5_PT5048 got disconnected

Seconds since start: 1620.74 - Android HTC-HTC Desire 820_PT2141 got disconnected

Seconds since start: 1640.326 - Android LGE-LG-H815_PT2441 got disconnected

Seconds since start: 1642.535 - Android HUAWEI-ALE-L21_PT1144 got disconnected

Seconds since start: 1644.468 - Android HTC-HTC Desire 820_PT511 got disconnected

Seconds since start: 1680.892 - Android samsung-SM-N9005_PT2503 got disconnected


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!
```
###Android Logs
####Node name: thali01
####Node name: thali02
####Node name: thali03
Console output:
```
Error! Unexpected exit on device TA4750HV7I app:com.test.thalitest code:null 
child process exited with code null on device TA4750HV7I 
Error! Unexpected exit on device LGD8553bed2d08 app:com.test.thalitest code:null 
child process exited with code null on device LGD8553bed2d08 
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:null 
child process exited with code null on device 320414cd475f91e3 
Android task is completed 
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/51335028aa5f981_Work_in_progress__vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/51335028aa5f981_Work_in_progress__vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/51335028aa5f981_Work_in_progress__vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali04
####Node name: thali05
Console output:
```
Android task is completed 
```
####Node name: thali06
####Node name: thali07
####Node name: thali08
####Node name: thali09



###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/51335028aa5f981_Work_in_progress__vjrantal/iOS_Iphone5-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/51335028aa5f981_Work_in_progress__vjrantal/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/51335028aa5f981_Work_in_progress__vjrantal/iOS_Iphone6-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/51335028aa5f981_Work_in_progress__vjrantal/iOS_IpadAir2-1.md)


#### Integration Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":15}}
Android tests will start after waiting for 300 seconds

Test ID 0 configuration: testSendData.js, server timeout : 1600000, data : {"timeout":"1500000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}
iOS tests will start after waiting for 300 seconds
Test ID 0 configuration: testSendData.js, server timeout : 1600000, data : {"timeout":"1500000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}

listening on *:3000

Seconds since start: 0.679 - Android LGE-LG-D855_PT7598 added (current device count 1)

Seconds since start: 0.696 - Android HTC-HTC Desire 820_PT511 added (current device count 2)

Seconds since start: 0.746 - Android samsung-SM-A500FU_PT6164 added (current device count 3)

Seconds since start: 1.351 - Android HTC-HTC Desire 820_PT2141 added (current device count 4)

Seconds since start: 1.679 - Android LGE-Nexus 5_PT5726 added (current device count 5)

Seconds since start: 1.831 - iOS Apple-IpadAir2-1_PT437 added (current device count 1)

Seconds since start: 2.183 - Android HUAWEI-ALE-L21_PT1144 added (current device count 6)

Seconds since start: 2.352 - Android LGE-LG-D722_PT2554 added (current device count 7)

Seconds since start: 2.376 - Android samsung-SM-N9005_PT2503 added (current device count 8)

Seconds since start: 2.977 - Android motorola-Nexus 6_PT4471 added (current device count 9)

Seconds since start: 3.161 - Android LGE-LG-H815_PT2441 added (current device count 10)

Seconds since start: 3.475 - Android LGE-Nexus 5_PT5048 added (current device count 11)

Seconds since start: 4.116 - Android HTC-HTC One_M8_PT296 added (current device count 12)

Seconds since start: 4.259 - iOS Apple-Iphone5-1_PT9936 added (current device count 2)

Seconds since start: 4.708 - iOS Apple-Iphone5s-1_PT7804 added (current device count 3)

Seconds since start: 4.792 - Android samsung-SM-A300FU_PT410 added (current device count 13)

Seconds since start: 4.848 - iOS Apple-Iphone6-1_PT1827 added (current device count 4)

Seconds since start: 5.261 - Android samsung-SM-G800F_PT348 added (current device count 14)

Seconds since start: 15.315 - Android motorola-XT1039_PT8322 added (current device count 15)

-------------- We got wait done, now starting the testing process ------------------

Seconds since start: 300.061 - Android start testing now with 15 devices

Seconds since start: 300.092 - iOS start testing now with 4 devices

Seconds since start: 311.256 - iOS Apple-Iphone6-1_PT1827 test took 11161ms - results peers[0], reConnects[0], sendData[3]

Seconds since start: 311.262 - iOS Apple-Iphone5s-1_PT7804 test took 11169ms - results peers[0], reConnects[0], sendData[3]

Seconds since start: 312.8 - iOS Apple-IpadAir2-1_PT437 test took 12708ms - results peers[0], reConnects[0], sendData[3]

Seconds since start: 317.112 - iOS Apple-Iphone5-1_PT9936 test took 17019ms - results peers[0], reConnects[0], sendData[3]

Seconds since start: 317.113 - iOS test ID 0 done now

Seconds since start: 317.12 - iOS All tests are done, preparing test report

--------------- test report ---------------------

--------------- Apple-IpadAir2-1_PT437 --------------------- : 1

sendList : 100% : 4057 ms, 99% : 4057 ms, 95 : 4057 ms, 90% : 4057 ms.

Result count 3, range 3146 ms to  4057 ms.

sendList failed peers count : 0 [0 %]

sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5-1_PT9936 --------------------- : 2

sendList : 100% : 9602 ms, 99% : 9602 ms, 95 : 9602 ms, 90% : 9602 ms.
Result count 3, range 2823 ms to  9602 ms.
sendList failed peers count : 0 [0 %]

sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5s-1_PT7804 --------------------- : 3

sendList : 100% : 3658 ms, 99% : 3658 ms, 95 : 3658 ms, 90% : 3658 ms.
Result count 3, range 2916 ms to  3658 ms.
sendList failed peers count : 0 [0 %]

sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1_PT1827 --------------------- : 4

sendList : 100% : 4183 ms, 99% : 4183 ms, 95 : 4183 ms, 90% : 4183 ms.
Result count 3, range 2692 ms to  4183 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- Combined ---------------------

sendList : 100% : 9602 ms, 99% : 9602 ms, 95 : 4183 ms, 90% : 4183 ms.

--------------- end of test report ---------------------

Seconds since start: 337.506 - Android HTC-HTC Desire 820_PT511 got re-connected event

Seconds since start: 386.103 - Android HTC-HTC Desire 820_PT511 got disconnected

Seconds since start: 387.462 - Android LGE-Nexus 5_PT5726 got disconnected

Seconds since start: 390.853 - Android samsung-SM-G800F_PT348 got disconnected

Seconds since start: 416.507 - Android samsung-SM-A300FU_PT410 got disconnected

Seconds since start: 566.003 - Android samsung-SM-A500FU_PT6164 got disconnected

Seconds since start: 582.395 - Android LGE-LG-D855_PT7598 got disconnected

Seconds since start: 585.733 - Android motorola-Nexus 6_PT4471 test took 285656ms - results peers[0], reConnects[0], sendData[14]

Seconds since start: 665.836 - Android LGE-LG-D722_PT2554 got disconnected

Seconds since start: 677.817 - Android HTC-HTC Desire 820_PT2141 got disconnected

Seconds since start: 691.237 - Android motorola-XT1039_PT8322 got disconnected

Seconds since start: 720.904 - Android motorola-XT1039_PT8322 got re-connected event

Seconds since start: 739.234 - Android LGE-LG-H815_PT2441 test took 439156ms - results peers[0], reConnects[0], sendData[14]

Seconds since start: 872.136 - Android motorola-XT1039_PT8322 got re-connected event

Seconds since start: 881.433 - Android motorola-XT1039_PT8322 got disconnected

Seconds since start: 915.96 - Android motorola-XT1039_PT8322 got re-connected event

Seconds since start: 957.137 - Android motorola-XT1039_PT8322 got disconnected

Seconds since start: 1067.605 - Android motorola-XT1039_PT8322 got disconnected

Seconds since start: 1068.978 - Android motorola-XT1039_PT8322 got re-connected event

Seconds since start: 1128.579 - Android motorola-XT1039_PT8322 got re-connected event

Seconds since start: 1153.979 - Android motorola-XT1039_PT8322 got disconnected

Seconds since start: 1176.734 - Android HTC-HTC Desire 820_PT2141 got re-connected event

Seconds since start: 1241.257 - Android motorola-XT1039_PT8322 got re-connected event

Seconds since start: 1288.694 - Android motorola-XT1039_PT8322 got disconnected

Seconds since start: 1611.788 - Android LGE-Nexus 5_PT5048 got disconnected

Seconds since start: 1620.74 - Android HTC-HTC Desire 820_PT2141 got disconnected

Seconds since start: 1640.326 - Android LGE-LG-H815_PT2441 got disconnected

Seconds since start: 1642.535 - Android HUAWEI-ALE-L21_PT1144 got disconnected

Seconds since start: 1644.468 - Android HTC-HTC Desire 820_PT511 got disconnected

Seconds since start: 1680.892 - Android samsung-SM-N9005_PT2503 got disconnected


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


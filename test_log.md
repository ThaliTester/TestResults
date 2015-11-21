#### Test 5133502858c0449 Logs

Status: 
```

ios : false

server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":21}}
Android tests will start after waiting for 300 seconds

Test ID 0 configuration: testSendData.js, server timeout : 1200000, data : {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}
iOS tests will start after waiting for 300 seconds
Test ID 0 configuration: testSendData.js, server timeout : 1200000, data : {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}

listening on *:3000

Seconds since start: 0.613 - Android LGE-Nexus 5_PT5095 added (current device count 1)

Seconds since start: 0.754 - Android samsung-SM-N9005_PT8584 added (current device count 2)

Seconds since start: 0.757 - Android LGE-LG-D855_PT5235 added (current device count 3)

Seconds since start: 0.825 - Android motorola-XT1072_PT7511 added (current device count 4)

Seconds since start: 1.098 - Android LGE-LG-D802_PT9258 added (current device count 5)

Seconds since start: 1.532 - Android HTC-HTC One_M8_PT2237 added (current device count 6)

Seconds since start: 2.079 - Android samsung-SM-A300FU_PT6814 added (current device count 7)

Seconds since start: 2.089 - Android samsung-SM-A500FU_PT2749 added (current device count 8)

Seconds since start: 2.231 - Android HTC-HTC One M8s_PT8695 added (current device count 9)

Seconds since start: 2.259 - iOS Apple-Iphone5-1_PT8098 added (current device count 1)

Seconds since start: 2.365 - Android samsung-SM-G900F_PT6240 added (current device count 10)

Seconds since start: 2.393 - Android samsung-SM-A300FU_PT756 added (current device count 11)

Seconds since start: 2.479 - Android LGE-LG-D722_PT6174 added (current device count 12)

Seconds since start: 2.485 - iOS Apple-Iphone6-1_PT3409 added (current device count 2)

Seconds since start: 2.872 - Android LGE-LG-H815_PT9509 added (current device count 13)

Seconds since start: 3.056 - Android HTC-HTC Desire 820_PT4767 added (current device count 14)

Seconds since start: 3.114 - iOS Apple-Iphone5s-1_PT497 added (current device count 3)

Seconds since start: 3.225 - Android LGE-Nexus 5_PT9251 added (current device count 15)

Seconds since start: 3.239 - Android samsung-SM-N910C_PT142 added (current device count 16)

Seconds since start: 3.455 - Android HTC-HTC Desire 820_PT3246 added (current device count 17)

Seconds since start: 3.955 - Android HUAWEI-ALE-L21_PT1463 added (current device count 18)

Seconds since start: 3.988 - Android motorola-Nexus 6_PT4751 added (current device count 19)

Seconds since start: 4.496 - iOS Apple-IpadAir2-1_PT1308 added (current device count 4)

Seconds since start: 6.152 - Android motorola-XT1039_PT4204 added (current device count 20)

Seconds since start: 6.458 - Android samsung-SM-G800F_PT6553 added (current device count 21)

-------------- We got wait done, now starting the testing process ------------------

Seconds since start: 300.065 - Android start testing now with 21 devices

Seconds since start: 300.099 - iOS start testing now with 4 devices

Seconds since start: 313.364 - iOS Apple-Iphone5s-1_PT497 test took 13262ms - results peers[0], reConnects[0], sendData[3]

Seconds since start: 313.445 - iOS Apple-Iphone5-1_PT8098 test took 13345ms - results peers[0], reConnects[0], sendData[3]

Seconds since start: 316.494 - iOS Apple-IpadAir2-1_PT1308 test took 16393ms - results peers[0], reConnects[0], sendData[3]

Seconds since start: 389.341 - Android LGE-Nexus 5_PT9251 got disconnected

Seconds since start: 412.62 - Android samsung-SM-A300FU_PT6814 got disconnected

Seconds since start: 419.864 - Android LGE-LG-D802_PT9258 got disconnected

Seconds since start: 442.514 - Android samsung-SM-G800F_PT6553 got disconnected

Seconds since start: 447.617 - iOS Apple-Iphone6-1_PT3409 test took 147517ms - results peers[0], reConnects[0], sendData[3]

Seconds since start: 447.618 - iOS test ID 0 done now

Seconds since start: 447.625 - iOS All tests are done, preparing test report

--------------- test report ---------------------

--------------- Apple-Iphone5-1_PT8098 --------------------- : 1

sendList : 100% : 4732 ms, 99% : 4732 ms, 95 : 4732 ms, 90% : 4732 ms.

Result count 3, range 3323 ms to  4732 ms.

sendList failed peers count : 0 [0 %]

sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone6-1_PT3409 --------------------- : 2
sendList : 100% : 2983 ms, 99% : 2983 ms, 95 : 2983 ms, 90% : 2983 ms.
Result count 2, range 2973 ms to  2983 ms.

sendList failed peers count : 1 [33.333333333333336 %]

- Peer ID : Apple-Iphone6-1_PT1827.PMdwog==, Tried : 5

sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5s-1_PT497 --------------------- : 3

sendList : 100% : 4220 ms, 99% : 4220 ms, 95 : 4220 ms, 90% : 4220 ms.
Result count 3, range 2806 ms to  4220 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- Apple-IpadAir2-1_PT1308 --------------------- : 4
sendList : 100% : 5119 ms, 99% : 5119 ms, 95 : 5119 ms, 90% : 5119 ms.

Result count 3, range 4296 ms to  5119 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- Combined ---------------------

sendList : 100% : 5119 ms, 99% : 5119 ms, 95 : 4864 ms, 90% : 4864 ms.

--------------- end of test report ---------------------

Seconds since start: 469.346 - Android HTC-HTC One_M8_PT2237 got re-connected event

Seconds since start: 540.933 - Android HTC-HTC One_M8_PT2237 got disconnected

Seconds since start: 571.745 - Android motorola-XT1039_PT4204 got disconnected

Seconds since start: 571.75 - Android motorola-XT1039_PT4204 got re-connected event

Seconds since start: 593.297 - Android LGE-LG-D722_PT6174 got re-connected event

Seconds since start: 597.849 - Android HTC-HTC One M8s_PT8695 got disconnected

Seconds since start: 613.477 - Android LGE-Nexus 5_PT9251 got re-connected event

Seconds since start: 617.484 - Android HTC-HTC One_M8_PT2237 got re-connected event

Seconds since start: 639.981 - Android samsung-SM-N910C_PT142 got disconnected

Seconds since start: 641.398 - Android LGE-LG-D722_PT6174 got disconnected

Seconds since start: 643.809 - Android samsung-SM-A300FU_PT756 got disconnected

Seconds since start: 683.177 - Android HTC-HTC Desire 820_PT3246 got disconnected

Seconds since start: 684.293 - Android HTC-HTC One_M8_PT2237 got disconnected

Seconds since start: 723.31 - Android LGE-Nexus 5_PT9251 got disconnected

Seconds since start: 882.419 - Android LGE-LG-D855_PT5235 got disconnected

Seconds since start: 933.561 - Android motorola-XT1072_PT7511 got disconnected

Seconds since start: 933.907 - Android motorola-XT1072_PT7511 got re-connected event

Seconds since start: 999.375 - Android samsung-SM-A500FU_PT2749 got disconnected

Seconds since start: 1081.436 - Android motorola-Nexus 6_PT4751 got re-connected event

Seconds since start: 1141.724 - Android motorola-Nexus 6_PT4751 got disconnected

Seconds since start: 1284.207 - Android HTC-HTC One M8s_PT8695 got re-connected event

Seconds since start: 1300.412 - Android motorola-Nexus 6_PT4751 test took 1000321ms - results peers[0], reConnects[0], sendData[20]

Seconds since start: 1300.536 - Android LGE-Nexus 5_PT5095 test took 1000461ms - results peers[0], reConnects[0], sendData[20]

Seconds since start: 1300.612 - Android HTC-HTC One_M8_PT2237 test took 1000532ms - results peers[0], reConnects[0], sendData[20]

Seconds since start: 1300.69 - Android samsung-SM-N9005_PT8584 test took 1000613ms - results peers[0], reConnects[0], sendData[20]

Seconds since start: 1300.725 - Android motorola-XT1072_PT7511 test took 1000646ms - results peers[0], reConnects[0], sendData[20]

Seconds since start: 1300.789 - Android HTC-HTC One M8s_PT8695 test took 1000705ms - results peers[0], reConnects[0], sendData[20]

Seconds since start: 1300.906 - Android motorola-XT1039_PT4204 test took 1000814ms - results peers[0], reConnects[0], sendData[20]

Seconds since start: 1301.507 - Android HTC-HTC Desire 820_PT4767 test took 1001419ms - results peers[0], reConnects[0], sendData[20]

Seconds since start: 1302.259 - Android LGE-LG-H815_PT9509 test took 1002172ms - results peers[0], reConnects[0], sendData[20]

Seconds since start: 1302.71 - Android samsung-SM-G900F_PT6240 test took 1002625ms - results peers[0], reConnects[0], sendData[20]

Seconds since start: 1304.798 - Android LGE-LG-D722_PT6174 test took 1004711ms - results peers[0], reConnects[0], sendData[20]

Seconds since start: 1311.571 - Android HUAWEI-ALE-L21_PT1463 test took 1011480ms - results peers[0], reConnects[0], sendData[20]

Seconds since start: 1500.098 - Server timeout reached!

Seconds since start: 1500.099 - Send timeout to LGE-LG-D855_PT5235
Seconds since start: 1500.099 - Send timeout to LGE-LG-D802_PT9258

Seconds since start: 1500.1 - Send timeout to samsung-SM-A300FU_PT6814

Seconds since start: 1500.108 - Send timeout to samsung-SM-A500FU_PT2749

Seconds since start: 1500.109 - Send timeout to samsung-SM-A300FU_PT756
Seconds since start: 1500.11 - Send timeout to LGE-Nexus 5_PT9251

Seconds since start: 1500.111 - Send timeout to samsung-SM-N910C_PT142

Seconds since start: 1500.112 - Send timeout to HTC-HTC Desire 820_PT3246
Seconds since start: 1500.112 - Send timeout to samsung-SM-G800F_PT6553

Seconds since start: 1560.116 - Did not get reports from all devices, but forcing tests to finish!

LGE-LG-D855_PT5235 did not have results at the end of tests - check the device logs about why!!

LGE-LG-D802_PT9258 did not have results at the end of tests - check the device logs about why!!

samsung-SM-A300FU_PT6814 did not have results at the end of tests - check the device logs about why!!

samsung-SM-A500FU_PT2749 did not have results at the end of tests - check the device logs about why!!

samsung-SM-A300FU_PT756 did not have results at the end of tests - check the device logs about why!!

LGE-Nexus 5_PT9251 did not have results at the end of tests - check the device logs about why!!

samsung-SM-N910C_PT142 did not have results at the end of tests - check the device logs about why!!
HTC-HTC Desire 820_PT3246 did not have results at the end of tests - check the device logs about why!!

samsung-SM-G800F_PT6553 did not have results at the end of tests - check the device logs about why!!

Seconds since start: 1560.138 - Android All tests are done, preparing test report

--------------- test report ---------------------

--------------- LGE-Nexus 5_PT5095 --------------------- : 1
sendList : 100% : 75097 ms, 99% : 75097 ms, 95 : 73568 ms, 90% : 48900 ms.
Result count 17, range 2496 ms to  75097 ms.

sendList failed peers count : 3 [15 %]
- Peer ID : 08:EC:A9:50:75:41, Tried : 3
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 2
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 3
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-N9005_PT8584 --------------------- : 2
sendList : 100% : 86569 ms, 99% : 86569 ms, 95 : 86569 ms, 90% : 44905 ms.
Result count 9, range 3408 ms to  86569 ms.
sendList failed peers count : 5 [35.714285714285715 %]
- Peer ID : 50:2E:6C:AC:21:50, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1

- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
sendList never tried peers count : 6 [30 %]
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : 90:E7:C4:F6:69:77
- Peer ID : F8:95:C7:87:85:54
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 7C:F9:0E:37:96:AB
--------------- motorola-XT1072_PT7511 --------------------- : 3
sendList : 100% : 107773 ms, 99% : 107773 ms, 95 : 105644 ms, 90% : 105644 ms.
Result count 15, range 4500 ms to  107773 ms.
sendList failed peers count : 5 [25 %]
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 2
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 2
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 2
- Peer ID : 34:FC:EF:11:B1:66, Tried : 2
sendList never tried peers count : 0 [0 %]
--------------- HTC-HTC One_M8_PT2237 --------------------- : 4
sendList : 100% : 151599 ms, 99% : 151599 ms, 95 : 64101 ms, 90% : 60489 ms.
Result count 17, range 3262 ms to  151599 ms.
sendList failed peers count : 3 [15 %]
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 3
- Peer ID : 08:EC:A9:50:75:41, Tried : 2
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 3
sendList never tried peers count : 0 [0 %]

--------------- HTC-HTC One M8s_PT8695 --------------------- : 5
sendList : 100% : 152580 ms, 99% : 152580 ms, 95 : 92018 ms, 90% : 92018 ms.
Result count 13, range 3480 ms to  152580 ms.
sendList failed peers count : 7 [35 %]

- Peer ID : F8:95:C7:87:3C:51, Tried : 2
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1

- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-G900F_PT6240 --------------------- : 6

sendList : 100% : 72607 ms, 99% : 72607 ms, 95 : 48414 ms, 90% : 40034 ms.
Result count 19, range 2829 ms to  72607 ms.
sendList failed peers count : 1 [5 %]
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 8
sendList never tried peers count : 0 [0 %]
--------------- LGE-LG-D722_PT6174 --------------------- : 7
sendList : 100% : 34303 ms, 99% : 34303 ms, 95 : 33738 ms, 90% : 33738 ms.
Result count 15, range 3675 ms to  34303 ms.
sendList failed peers count : 5 [25 %]

- Peer ID : 7C:F9:0E:37:96:AB, Tried : 3
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 2
- Peer ID : 44:80:EB:7B:5A:05, Tried : 2
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 2
- Peer ID : 34:FC:EF:11:B1:66, Tried : 2
sendList never tried peers count : 0 [0 %]

--------------- LGE-LG-H815_PT9509 --------------------- : 8
sendList : 100% : 71652 ms, 99% : 71652 ms, 95 : 50481 ms, 90% : 50090 ms.
Result count 18, range 2691 ms to  71652 ms.
sendList failed peers count : 2 [10 %]
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 3
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 2
sendList never tried peers count : 0 [0 %]
--------------- HTC-HTC Desire 820_PT4767 --------------------- : 9
sendList : 100% : 90938 ms, 99% : 90938 ms, 95 : 36283 ms, 90% : 31654 ms.

Result count 17, range 2678 ms to  90938 ms.
sendList failed peers count : 3 [15 %]
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 4
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 3
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 4
sendList never tried peers count : 0 [0 %]
--------------- HUAWEI-ALE-L21_PT1463 --------------------- : 10
sendList : 100% : 118193 ms, 99% : 118193 ms, 95 : 85712 ms, 90% : 85712 ms.
Result count 15, range 4069 ms to  118193 ms.
sendList failed peers count : 5 [25 %]
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 2
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 2
- Peer ID : 34:FC:EF:11:B1:66, Tried : 2
sendList never tried peers count : 0 [0 %]
--------------- motorola-Nexus 6_PT4751 --------------------- : 11
sendList : 100% : 68255 ms, 99% : 68255 ms, 95 : 65594 ms, 90% : 51610 ms.
Result count 18, range 2020 ms to  68255 ms.
sendList failed peers count : 2 [10 %]
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 6
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- motorola-XT1039_PT4204 --------------------- : 12
sendList : 100% : 100035 ms, 99% : 100035 ms, 95 : 80076 ms, 90% : 80076 ms.
Result count 12, range 1989 ms to  100035 ms.
sendList failed peers count : 7 [36.8421052631579 %]
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
sendList never tried peers count : 1 [5 %]
- Peer ID : 00:F4:6F:30:E0:6C
--------------- Combined ---------------------
sendList : 100% : 152580 ms, 99% : 118193 ms, 95 : 85712 ms, 90% : 68255 ms.

--------------- end of test report ---------------------


 
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
Error! Unexpected exit on device LGD8553bed2d08 app:com.test.thalitest code:null 
child process exited with code null on device LGD8553bed2d08 
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:null 
child process exited with code null on device 320414cd475f91e3 
Android task is completed 
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/5133502858c0449_Work_in_progress__vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/5133502858c0449_Work_in_progress__vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/5133502858c0449_Work_in_progress__vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed 
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/5133502858c0449_Work_in_progress__vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/5133502858c0449_Work_in_progress__vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/5133502858c0449_Work_in_progress__vjrantal/thali04_samsung-SM-G900F.md)

####Node name: thali05
####Node name: thali06


Couldn't parse the device logs for thali06
````SyntaxError: Unexpected end of input```
####Node name: thali07
####Node name: thali08
####Node name: thali09



###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/5133502858c0449_Work_in_progress__vjrantal/iOS_Iphone5-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/5133502858c0449_Work_in_progress__vjrantal/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/5133502858c0449_Work_in_progress__vjrantal/iOS_Iphone6-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/5133502858c0449_Work_in_progress__vjrantal/iOS_IpadAir2-1.md)


#### Integration Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":21}}
Android tests will start after waiting for 300 seconds

Test ID 0 configuration: testSendData.js, server timeout : 1200000, data : {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}
iOS tests will start after waiting for 300 seconds
Test ID 0 configuration: testSendData.js, server timeout : 1200000, data : {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}

listening on *:3000

Seconds since start: 0.613 - Android LGE-Nexus 5_PT5095 added (current device count 1)

Seconds since start: 0.754 - Android samsung-SM-N9005_PT8584 added (current device count 2)

Seconds since start: 0.757 - Android LGE-LG-D855_PT5235 added (current device count 3)

Seconds since start: 0.825 - Android motorola-XT1072_PT7511 added (current device count 4)

Seconds since start: 1.098 - Android LGE-LG-D802_PT9258 added (current device count 5)

Seconds since start: 1.532 - Android HTC-HTC One_M8_PT2237 added (current device count 6)

Seconds since start: 2.079 - Android samsung-SM-A300FU_PT6814 added (current device count 7)

Seconds since start: 2.089 - Android samsung-SM-A500FU_PT2749 added (current device count 8)

Seconds since start: 2.231 - Android HTC-HTC One M8s_PT8695 added (current device count 9)

Seconds since start: 2.259 - iOS Apple-Iphone5-1_PT8098 added (current device count 1)

Seconds since start: 2.365 - Android samsung-SM-G900F_PT6240 added (current device count 10)

Seconds since start: 2.393 - Android samsung-SM-A300FU_PT756 added (current device count 11)

Seconds since start: 2.479 - Android LGE-LG-D722_PT6174 added (current device count 12)

Seconds since start: 2.485 - iOS Apple-Iphone6-1_PT3409 added (current device count 2)

Seconds since start: 2.872 - Android LGE-LG-H815_PT9509 added (current device count 13)

Seconds since start: 3.056 - Android HTC-HTC Desire 820_PT4767 added (current device count 14)

Seconds since start: 3.114 - iOS Apple-Iphone5s-1_PT497 added (current device count 3)

Seconds since start: 3.225 - Android LGE-Nexus 5_PT9251 added (current device count 15)

Seconds since start: 3.239 - Android samsung-SM-N910C_PT142 added (current device count 16)

Seconds since start: 3.455 - Android HTC-HTC Desire 820_PT3246 added (current device count 17)

Seconds since start: 3.955 - Android HUAWEI-ALE-L21_PT1463 added (current device count 18)

Seconds since start: 3.988 - Android motorola-Nexus 6_PT4751 added (current device count 19)

Seconds since start: 4.496 - iOS Apple-IpadAir2-1_PT1308 added (current device count 4)

Seconds since start: 6.152 - Android motorola-XT1039_PT4204 added (current device count 20)

Seconds since start: 6.458 - Android samsung-SM-G800F_PT6553 added (current device count 21)

-------------- We got wait done, now starting the testing process ------------------

Seconds since start: 300.065 - Android start testing now with 21 devices

Seconds since start: 300.099 - iOS start testing now with 4 devices

Seconds since start: 313.364 - iOS Apple-Iphone5s-1_PT497 test took 13262ms - results peers[0], reConnects[0], sendData[3]

Seconds since start: 313.445 - iOS Apple-Iphone5-1_PT8098 test took 13345ms - results peers[0], reConnects[0], sendData[3]

Seconds since start: 316.494 - iOS Apple-IpadAir2-1_PT1308 test took 16393ms - results peers[0], reConnects[0], sendData[3]

Seconds since start: 389.341 - Android LGE-Nexus 5_PT9251 got disconnected

Seconds since start: 412.62 - Android samsung-SM-A300FU_PT6814 got disconnected

Seconds since start: 419.864 - Android LGE-LG-D802_PT9258 got disconnected

Seconds since start: 442.514 - Android samsung-SM-G800F_PT6553 got disconnected

Seconds since start: 447.617 - iOS Apple-Iphone6-1_PT3409 test took 147517ms - results peers[0], reConnects[0], sendData[3]

Seconds since start: 447.618 - iOS test ID 0 done now

Seconds since start: 447.625 - iOS All tests are done, preparing test report

--------------- test report ---------------------

--------------- Apple-Iphone5-1_PT8098 --------------------- : 1

sendList : 100% : 4732 ms, 99% : 4732 ms, 95 : 4732 ms, 90% : 4732 ms.

Result count 3, range 3323 ms to  4732 ms.

sendList failed peers count : 0 [0 %]

sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone6-1_PT3409 --------------------- : 2
sendList : 100% : 2983 ms, 99% : 2983 ms, 95 : 2983 ms, 90% : 2983 ms.
Result count 2, range 2973 ms to  2983 ms.

sendList failed peers count : 1 [33.333333333333336 %]

- Peer ID : Apple-Iphone6-1_PT1827.PMdwog==, Tried : 5

sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5s-1_PT497 --------------------- : 3

sendList : 100% : 4220 ms, 99% : 4220 ms, 95 : 4220 ms, 90% : 4220 ms.
Result count 3, range 2806 ms to  4220 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- Apple-IpadAir2-1_PT1308 --------------------- : 4
sendList : 100% : 5119 ms, 99% : 5119 ms, 95 : 5119 ms, 90% : 5119 ms.

Result count 3, range 4296 ms to  5119 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- Combined ---------------------

sendList : 100% : 5119 ms, 99% : 5119 ms, 95 : 4864 ms, 90% : 4864 ms.

--------------- end of test report ---------------------

Seconds since start: 469.346 - Android HTC-HTC One_M8_PT2237 got re-connected event

Seconds since start: 540.933 - Android HTC-HTC One_M8_PT2237 got disconnected

Seconds since start: 571.745 - Android motorola-XT1039_PT4204 got disconnected

Seconds since start: 571.75 - Android motorola-XT1039_PT4204 got re-connected event

Seconds since start: 593.297 - Android LGE-LG-D722_PT6174 got re-connected event

Seconds since start: 597.849 - Android HTC-HTC One M8s_PT8695 got disconnected

Seconds since start: 613.477 - Android LGE-Nexus 5_PT9251 got re-connected event

Seconds since start: 617.484 - Android HTC-HTC One_M8_PT2237 got re-connected event

Seconds since start: 639.981 - Android samsung-SM-N910C_PT142 got disconnected

Seconds since start: 641.398 - Android LGE-LG-D722_PT6174 got disconnected

Seconds since start: 643.809 - Android samsung-SM-A300FU_PT756 got disconnected

Seconds since start: 683.177 - Android HTC-HTC Desire 820_PT3246 got disconnected

Seconds since start: 684.293 - Android HTC-HTC One_M8_PT2237 got disconnected

Seconds since start: 723.31 - Android LGE-Nexus 5_PT9251 got disconnected

Seconds since start: 882.419 - Android LGE-LG-D855_PT5235 got disconnected

Seconds since start: 933.561 - Android motorola-XT1072_PT7511 got disconnected

Seconds since start: 933.907 - Android motorola-XT1072_PT7511 got re-connected event

Seconds since start: 999.375 - Android samsung-SM-A500FU_PT2749 got disconnected

Seconds since start: 1081.436 - Android motorola-Nexus 6_PT4751 got re-connected event

Seconds since start: 1141.724 - Android motorola-Nexus 6_PT4751 got disconnected

Seconds since start: 1284.207 - Android HTC-HTC One M8s_PT8695 got re-connected event

Seconds since start: 1300.412 - Android motorola-Nexus 6_PT4751 test took 1000321ms - results peers[0], reConnects[0], sendData[20]

Seconds since start: 1300.536 - Android LGE-Nexus 5_PT5095 test took 1000461ms - results peers[0], reConnects[0], sendData[20]

Seconds since start: 1300.612 - Android HTC-HTC One_M8_PT2237 test took 1000532ms - results peers[0], reConnects[0], sendData[20]

Seconds since start: 1300.69 - Android samsung-SM-N9005_PT8584 test took 1000613ms - results peers[0], reConnects[0], sendData[20]

Seconds since start: 1300.725 - Android motorola-XT1072_PT7511 test took 1000646ms - results peers[0], reConnects[0], sendData[20]

Seconds since start: 1300.789 - Android HTC-HTC One M8s_PT8695 test took 1000705ms - results peers[0], reConnects[0], sendData[20]

Seconds since start: 1300.906 - Android motorola-XT1039_PT4204 test took 1000814ms - results peers[0], reConnects[0], sendData[20]

Seconds since start: 1301.507 - Android HTC-HTC Desire 820_PT4767 test took 1001419ms - results peers[0], reConnects[0], sendData[20]

Seconds since start: 1302.259 - Android LGE-LG-H815_PT9509 test took 1002172ms - results peers[0], reConnects[0], sendData[20]

Seconds since start: 1302.71 - Android samsung-SM-G900F_PT6240 test took 1002625ms - results peers[0], reConnects[0], sendData[20]

Seconds since start: 1304.798 - Android LGE-LG-D722_PT6174 test took 1004711ms - results peers[0], reConnects[0], sendData[20]

Seconds since start: 1311.571 - Android HUAWEI-ALE-L21_PT1463 test took 1011480ms - results peers[0], reConnects[0], sendData[20]

Seconds since start: 1500.098 - Server timeout reached!

Seconds since start: 1500.099 - Send timeout to LGE-LG-D855_PT5235
Seconds since start: 1500.099 - Send timeout to LGE-LG-D802_PT9258

Seconds since start: 1500.1 - Send timeout to samsung-SM-A300FU_PT6814

Seconds since start: 1500.108 - Send timeout to samsung-SM-A500FU_PT2749

Seconds since start: 1500.109 - Send timeout to samsung-SM-A300FU_PT756
Seconds since start: 1500.11 - Send timeout to LGE-Nexus 5_PT9251

Seconds since start: 1500.111 - Send timeout to samsung-SM-N910C_PT142

Seconds since start: 1500.112 - Send timeout to HTC-HTC Desire 820_PT3246
Seconds since start: 1500.112 - Send timeout to samsung-SM-G800F_PT6553

Seconds since start: 1560.116 - Did not get reports from all devices, but forcing tests to finish!

LGE-LG-D855_PT5235 did not have results at the end of tests - check the device logs about why!!

LGE-LG-D802_PT9258 did not have results at the end of tests - check the device logs about why!!

samsung-SM-A300FU_PT6814 did not have results at the end of tests - check the device logs about why!!

samsung-SM-A500FU_PT2749 did not have results at the end of tests - check the device logs about why!!

samsung-SM-A300FU_PT756 did not have results at the end of tests - check the device logs about why!!

LGE-Nexus 5_PT9251 did not have results at the end of tests - check the device logs about why!!

samsung-SM-N910C_PT142 did not have results at the end of tests - check the device logs about why!!
HTC-HTC Desire 820_PT3246 did not have results at the end of tests - check the device logs about why!!

samsung-SM-G800F_PT6553 did not have results at the end of tests - check the device logs about why!!

Seconds since start: 1560.138 - Android All tests are done, preparing test report

--------------- test report ---------------------

--------------- LGE-Nexus 5_PT5095 --------------------- : 1
sendList : 100% : 75097 ms, 99% : 75097 ms, 95 : 73568 ms, 90% : 48900 ms.
Result count 17, range 2496 ms to  75097 ms.

sendList failed peers count : 3 [15 %]
- Peer ID : 08:EC:A9:50:75:41, Tried : 3
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 2
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 3
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-N9005_PT8584 --------------------- : 2
sendList : 100% : 86569 ms, 99% : 86569 ms, 95 : 86569 ms, 90% : 44905 ms.
Result count 9, range 3408 ms to  86569 ms.
sendList failed peers count : 5 [35.714285714285715 %]
- Peer ID : 50:2E:6C:AC:21:50, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1

- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
sendList never tried peers count : 6 [30 %]
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : 90:E7:C4:F6:69:77
- Peer ID : F8:95:C7:87:85:54
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 7C:F9:0E:37:96:AB
--------------- motorola-XT1072_PT7511 --------------------- : 3
sendList : 100% : 107773 ms, 99% : 107773 ms, 95 : 105644 ms, 90% : 105644 ms.
Result count 15, range 4500 ms to  107773 ms.
sendList failed peers count : 5 [25 %]
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 2
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 2
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 2
- Peer ID : 34:FC:EF:11:B1:66, Tried : 2
sendList never tried peers count : 0 [0 %]
--------------- HTC-HTC One_M8_PT2237 --------------------- : 4
sendList : 100% : 151599 ms, 99% : 151599 ms, 95 : 64101 ms, 90% : 60489 ms.
Result count 17, range 3262 ms to  151599 ms.
sendList failed peers count : 3 [15 %]
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 3
- Peer ID : 08:EC:A9:50:75:41, Tried : 2
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 3
sendList never tried peers count : 0 [0 %]

--------------- HTC-HTC One M8s_PT8695 --------------------- : 5
sendList : 100% : 152580 ms, 99% : 152580 ms, 95 : 92018 ms, 90% : 92018 ms.
Result count 13, range 3480 ms to  152580 ms.
sendList failed peers count : 7 [35 %]

- Peer ID : F8:95:C7:87:3C:51, Tried : 2
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1

- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-G900F_PT6240 --------------------- : 6

sendList : 100% : 72607 ms, 99% : 72607 ms, 95 : 48414 ms, 90% : 40034 ms.
Result count 19, range 2829 ms to  72607 ms.
sendList failed peers count : 1 [5 %]
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 8
sendList never tried peers count : 0 [0 %]
--------------- LGE-LG-D722_PT6174 --------------------- : 7
sendList : 100% : 34303 ms, 99% : 34303 ms, 95 : 33738 ms, 90% : 33738 ms.
Result count 15, range 3675 ms to  34303 ms.
sendList failed peers count : 5 [25 %]

- Peer ID : 7C:F9:0E:37:96:AB, Tried : 3
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 2
- Peer ID : 44:80:EB:7B:5A:05, Tried : 2
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 2
- Peer ID : 34:FC:EF:11:B1:66, Tried : 2
sendList never tried peers count : 0 [0 %]

--------------- LGE-LG-H815_PT9509 --------------------- : 8
sendList : 100% : 71652 ms, 99% : 71652 ms, 95 : 50481 ms, 90% : 50090 ms.
Result count 18, range 2691 ms to  71652 ms.
sendList failed peers count : 2 [10 %]
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 3
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 2
sendList never tried peers count : 0 [0 %]
--------------- HTC-HTC Desire 820_PT4767 --------------------- : 9
sendList : 100% : 90938 ms, 99% : 90938 ms, 95 : 36283 ms, 90% : 31654 ms.

Result count 17, range 2678 ms to  90938 ms.
sendList failed peers count : 3 [15 %]
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 4
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 3
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 4
sendList never tried peers count : 0 [0 %]
--------------- HUAWEI-ALE-L21_PT1463 --------------------- : 10
sendList : 100% : 118193 ms, 99% : 118193 ms, 95 : 85712 ms, 90% : 85712 ms.
Result count 15, range 4069 ms to  118193 ms.
sendList failed peers count : 5 [25 %]
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 2
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 2
- Peer ID : 34:FC:EF:11:B1:66, Tried : 2
sendList never tried peers count : 0 [0 %]
--------------- motorola-Nexus 6_PT4751 --------------------- : 11
sendList : 100% : 68255 ms, 99% : 68255 ms, 95 : 65594 ms, 90% : 51610 ms.
Result count 18, range 2020 ms to  68255 ms.
sendList failed peers count : 2 [10 %]
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 6
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- motorola-XT1039_PT4204 --------------------- : 12
sendList : 100% : 100035 ms, 99% : 100035 ms, 95 : 80076 ms, 90% : 80076 ms.
Result count 12, range 1989 ms to  100035 ms.
sendList failed peers count : 7 [36.8421052631579 %]
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
sendList never tried peers count : 1 [5 %]
- Peer ID : 00:F4:6F:30:E0:6C
--------------- Combined ---------------------
sendList : 100% : 152580 ms, 99% : 118193 ms, 95 : 85712 ms, 90% : 68255 ms.

--------------- end of test report ---------------------


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


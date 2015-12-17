#### Test 539786639813e59 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":22}}
Test ID 0 configuration: testSendData.js, server timeout: 1200000, data:

{ timeout: 1000000,
  rounds: 1,
  dataTimeout: 20000,
  dataAmount: 100000,
  conReTryTimeout: 5000,
  conReTryCount: 5 }

2015-12-17T14:14:43.199Z (0 sec) - Android tests will start after waiting for 120 seconds

Test ID 0 configuration: testSendData.js, server timeout: 1200000, data:

{ timeout: 1000000,
  rounds: 1,
  dataTimeout: 20000,
  dataAmount: 100000,
  conReTryTimeout: 5000,
  conReTryCount: 5 }

2015-12-17T14:14:43.204Z (0 sec) - iOS tests will start after waiting for 120 seconds

listening on *:3000

2015-12-17T14:14:44.545Z (1 sec) - iOS Apple-IpadAir2-1_PT1563 added (current device count 1)

2015-12-17T14:14:44.796Z (2 sec) - iOS Apple-Iphone6-1_PT1480 added (current device count 2)

2015-12-17T14:14:44.842Z (2 sec) - iOS Apple-Iphone5s-1_PT1370 added (current device count 3)

2015-12-17T14:14:44.884Z (2 sec) - Android samsung-SM-A500FU_PT1654 added (current device count 1)

2015-12-17T14:14:44.931Z (2 sec) - Android LGE-LG-D855_PT1108 added (current device count 2)

2015-12-17T14:14:45.171Z (2 sec) - Android LGE-LG-D722_PT8193 added (current device count 3)

2015-12-17T14:14:45.483Z (2 sec) - Android samsung-SM-G900F_PT793 added (current device count 4)

2015-12-17T14:14:45.745Z (3 sec) - Android motorola-Nexus 6_PT6358 added (current device count 5)

2015-12-17T14:14:46.109Z (3 sec) - Android LGE-Nexus 5_PT7166 added (current device count 6)

2015-12-17T14:14:46.210Z (3 sec) - Android LGE-LG-H815_PT1016 added (current device count 7)

2015-12-17T14:14:46.683Z (4 sec) - Android samsung-SM-A300FU_PT9642 added (current device count 8)

2015-12-17T14:14:47.187Z (4 sec) - iOS Apple-Iphone5-1_PT5479 added (current device count 4)

2015-12-17T14:14:47.421Z (4 sec) - Android HTC-HTC One M8s_PT7778 added (current device count 9)

2015-12-17T14:14:47.911Z (5 sec) - Android samsung-SM-G900F_PT7309 added (current device count 10)

2015-12-17T14:14:47.943Z (5 sec) - Android samsung-SM-A500FU_PT4673 added (current device count 11)

2015-12-17T14:14:47.997Z (5 sec) - Android samsung-SM-A300FU_PT7181 added (current device count 12)

2015-12-17T14:14:48.375Z (5 sec) - Android samsung-SM-N9005_PT2526 added (current device count 13)

2015-12-17T14:14:49.175Z (6 sec) - Android motorola-XT1072_PT4451 added (current device count 14)

2015-12-17T14:14:55.640Z (12 sec) - Android samsung-SM-N910C_PT9551 added (current device count 15)

-------------- We got wait done, now starting the testing process ------------------

2015-12-17T14:16:43.430Z (120 sec) - Android start testing now with 15 devices

2015-12-17T14:16:43.456Z (120 sec) - iOS start testing now with 4 devices

2015-12-17T14:16:58.010Z (135 sec) - iOS Apple-Iphone6-1_PT1480 test took 14551ms - results peers[0], reConnects[0], sendData[3]

2015-12-17T14:17:00.169Z (137 sec) - iOS Apple-IpadAir2-1_PT1563 test took 16711ms - results peers[0], reConnects[0], sendData[3]

2015-12-17T14:17:01.022Z (138 sec) - iOS Apple-Iphone5s-1_PT1370 test took 17564ms - results peers[0], reConnects[0], sendData[3]

2015-12-17T14:17:04.887Z (142 sec) - iOS Apple-Iphone5-1_PT5479 test took 21428ms - results peers[0], reConnects[0], sendData[3]

2015-12-17T14:17:04.887Z (142 sec) - iOS test ID 0 done now

2015-12-17T14:17:04.894Z (142 sec) - iOS All tests are done, preparing test report

--------------- test report ---------------------

--------------- Apple-IpadAir2-1_PT1563 --------------------- : 1

sendList : 100% : 6498 ms, 99% : 6498 ms, 95 : 6498 ms, 90% : 6498 ms.

Average data rate: 0.02 MB/s

Result count 3, range 3754 ms to  6498 ms.

sendList failed peers count : 0 [0 %]

sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone6-1_PT1480 --------------------- : 2
sendList : 100% : 4470 ms, 99% : 4470 ms, 95 : 4470 ms, 90% : 4470 ms.

Average data rate: 0.025 MB/s
Result count 3, range 3829 ms to  4470 ms.
sendList failed peers count : 0 [0 %]

sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5s-1_PT1370 --------------------- : 3
sendList : 100% : 5935 ms, 99% : 5935 ms, 95 : 5935 ms, 90% : 5935 ms.
Average data rate: 0.021 MB/s

Result count 3, range 3031 ms to  5935 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5-1_PT5479 --------------------- : 4
sendList : 100% : 8827 ms, 99% : 8827 ms, 95 : 8827 ms, 90% : 8827 ms.
Average data rate: 0.017 MB/s
Result count 3, range 3540 ms to  8827 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------

sendList : 100% : 8827 ms, 99% : 8827 ms, 95 : 6498 ms, 90% : 6498 ms.
Average data rate: 0.02 MB/s
--------------- end of test report ---------------------

2015-12-17T14:17:06.208Z (143 sec) - iOS Apple-IpadAir2-1_PT1563 got disconnected

2015-12-17T14:17:07.257Z (144 sec) - iOS Apple-Iphone6-1_PT1480 got disconnected

2015-12-17T14:17:07.336Z (144 sec) - iOS Apple-Iphone5-1_PT5479 got disconnected

2015-12-17T14:17:24.446Z (161 sec) - iOS Apple-Iphone5s-1_PT1370 got disconnected

too late arrival

2015-12-17T14:17:50.069Z (187 sec) - Android LGE-LG-D855_PT1108 got disconnected

2015-12-17T14:18:15.835Z (213 sec) - Android samsung-SM-G900F_PT793 got disconnected

2015-12-17T14:18:18.182Z (215 sec) - Android samsung-SM-G900F_PT7309 got disconnected

2015-12-17T14:18:18.229Z (215 sec) - Android samsung-SM-A300FU_PT7181 got disconnected

2015-12-17T14:18:18.338Z (215 sec) - Android samsung-SM-A500FU_PT4673 got disconnected

2015-12-17T14:18:18.705Z (216 sec) - Android samsung-SM-N9005_PT2526 got disconnected

2015-12-17T14:18:27.514Z (224 sec) - Android samsung-SM-N910C_PT9551 got disconnected

2015-12-17T14:19:31.204Z (288 sec) - Android motorola-Nexus 6_PT6358 got disconnected

2015-12-17T14:20:21.192Z (338 sec) - Android motorola-XT1072_PT4451 got disconnected

2015-12-17T14:21:19.632Z (396 sec) - Android HTC-HTC One M8s_PT7778 got disconnected

2015-12-17T14:33:23.889Z (1121 sec) - Android LGE-LG-D722_PT8193 test took 1000450ms - results peers[0], reConnects[0], sendData[14]

2015-12-17T14:33:24.088Z (1121 sec) - Android LGE-Nexus 5_PT7166 test took 1000647ms - results peers[0], reConnects[0], sendData[14]

2015-12-17T14:33:24.220Z (1121 sec) - Android samsung-SM-A500FU_PT1654 test took 1000785ms - results peers[0], reConnects[0], sendData[14]

2015-12-17T14:33:24.293Z (1121 sec) - Android samsung-SM-A300FU_PT9642 test took 1000850ms - results peers[0], reConnects[0], sendData[14]

2015-12-17T14:33:25.123Z (1122 sec) - Android LGE-LG-H815_PT1016 test took 1001682ms - results peers[0], reConnects[0], sendData[14]

2015-12-17T14:36:43.452Z (1320 sec) - Server timeout reached!

2015-12-17T14:36:43.454Z (1320 sec) - Send timeout to LGE-LG-D855_PT1108

2015-12-17T14:36:43.457Z (1320 sec) - Send timeout to samsung-SM-G900F_PT793

2015-12-17T14:36:43.459Z (1320 sec) - Send timeout to motorola-Nexus 6_PT6358

2015-12-17T14:36:43.461Z (1320 sec) - Send timeout to HTC-HTC One M8s_PT7778

2015-12-17T14:36:43.463Z (1320 sec) - Send timeout to samsung-SM-G900F_PT7309

2015-12-17T14:36:43.463Z (1320 sec) - Send timeout to samsung-SM-A500FU_PT4673
2015-12-17T14:36:43.464Z (1320 sec) - Send timeout to samsung-SM-A300FU_PT7181

2015-12-17T14:36:43.464Z (1320 sec) - Send timeout to samsung-SM-N9005_PT2526
2015-12-17T14:36:43.465Z (1320 sec) - Send timeout to motorola-XT1072_PT4451

2015-12-17T14:36:43.466Z (1320 sec) - Send timeout to samsung-SM-N910C_PT9551

2015-12-17T14:37:43.472Z (1380 sec) - Did not get reports from all devices, but forcing tests to finish!

LGE-LG-D855_PT1108 did not have results at the end of tests - check the device logs about why!!

samsung-SM-G900F_PT793 did not have results at the end of tests - check the device logs about why!!

motorola-Nexus 6_PT6358 did not have results at the end of tests - check the device logs about why!!

HTC-HTC One M8s_PT7778 did not have results at the end of tests - check the device logs about why!!

samsung-SM-G900F_PT7309 did not have results at the end of tests - check the device logs about why!!
samsung-SM-A500FU_PT4673 did not have results at the end of tests - check the device logs about why!!

samsung-SM-A300FU_PT7181 did not have results at the end of tests - check the device logs about why!!
samsung-SM-N9005_PT2526 did not have results at the end of tests - check the device logs about why!!

motorola-XT1072_PT4451 did not have results at the end of tests - check the device logs about why!!
samsung-SM-N910C_PT9551 did not have results at the end of tests - check the device logs about why!!

2015-12-17T14:37:43.487Z (1380 sec) - Android All tests are done, preparing test report
--------------- test report ---------------------

--------------- samsung-SM-A500FU_PT1654 --------------------- : 1
sendList : 100% : 10679 ms, 99% : 10679 ms, 95 : 10679 ms, 90% : 10679 ms.

Average data rate: 0.012 MB/s
Result count 3, range 6515 ms to  10679 ms.
sendList failed peers count : 4 [57.142857142857146 %]

- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : 7C:F9:0E:51:18:22, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
sendList never tried peers count : 7 [50 %]

- Peer ID : 90:E7:C4:F6:69:77
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : 58:3F:54:73:64:C0

- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : E0:DB:10:1F:C9:5E
--------------- LGE-LG-D722_PT8193 --------------------- : 2

sendList : 100% : 20058 ms, 99% : 20058 ms, 95 : 20058 ms, 90% : 20058 ms.
Average data rate: 0.015 MB/s
Result count 5, range 1958 ms to  20058 ms.
sendList failed peers count : 9 [64.28571428571429 %]
- Peer ID : 90:E7:C4:F6:69:77, Tried : 1

- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1

- Peer ID : 7C:F9:0E:51:18:22, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
sendList never tried peers count : 0 [0 %]
--------------- LGE-Nexus 5_PT7166 --------------------- : 3
sendList : 100% : 53342 ms, 99% : 53342 ms, 95 : 53342 ms, 90% : 53342 ms.

Average data rate: 0.004 MB/s
Result count 3, range 3106 ms to  53342 ms.

sendList failed peers count : 1 [25 %]

- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
sendList never tried peers count : 10 [71.42857142857143 %]
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : F8:95:C7:87:3C:51

- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : F8:95:C7:87:85:54
- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : F8:CF:C5:D9:E5:61

- Peer ID : 08:EC:A9:50:76:27
--------------- LGE-LG-H815_PT1016 --------------------- : 4
sendList : 100% : 44922 ms, 99% : 44922 ms, 95 : 44922 ms, 90% : 44922 ms.
Average data rate: 0.003 MB/s
Result count 2, range 24118 ms to  44922 ms.

sendList failed peers count : 2 [50 %]
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
sendList never tried peers count : 10 [71.42857142857143 %]
- Peer ID : F8:95:C7:87:85:54

- Peer ID : 08:EC:A9:50:75:41
- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : E0:DB:10:1F:C9:5E
- Peer ID : 90:E7:C4:F6:69:77
- Peer ID : F8:CF:C5:D9:E5:61
- Peer ID : E0:DB:10:14:E2:C0

- Peer ID : 58:3F:54:73:64:C0
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 7C:F9:0E:37:96:AB
--------------- samsung-SM-A300FU_PT9642 --------------------- : 5
sendList : 100% : 8298 ms, 99% : 8298 ms, 95 : 8298 ms, 90% : 8298 ms.

Average data rate: 0.016 MB/s
Result count 3, range 3596 ms to  8298 ms.
sendList failed peers count : 4 [57.142857142857146 %]
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 7C:F9:0E:51:18:22, Tried : 1

- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
sendList never tried peers count : 7 [50 %]
- Peer ID : F8:CF:C5:D9:E5:61
- Peer ID : 08:EC:A9:50:76:27

- Peer ID : F8:95:C7:87:3C:51
- Peer ID : E0:DB:10:1F:C9:5E
- Peer ID : 90:E7:C4:F6:69:77
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 7C:F9:0E:37:96:AB

--------------- Combined ---------------------
sendList : 100% : 53342 ms, 99% : 53342 ms, 95 : 44922 ms, 90% : 24118 ms.
Average data rate: 0.007 MB/s
--------------- end of test report ---------------------

2015-12-17T14:37:43.862Z (1381 sec) - Android LGE-Nexus 5_PT7166 got disconnected

2015-12-17T14:37:43.994Z (1381 sec) - Android LGE-LG-H815_PT1016 got disconnected

2015-12-17T14:37:44.034Z (1381 sec) - Android LGE-LG-D722_PT8193 got disconnected

2015-12-17T14:37:44.108Z (1381 sec) - Android samsung-SM-A300FU_PT9642 got disconnected

2015-12-17T14:37:44.192Z (1381 sec) - Android samsung-SM-A500FU_PT1654 got disconnected


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

ios : false

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
STOP log received from  f56ad48d Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Device test finished on f56ad48d 
Android task is completed. [SUCCESS]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/539786639813e59_Story_001_tompaana_354_tompaana/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/539786639813e59_Story_001_tompaana_354_tompaana/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/539786639813e59_Story_001_tompaana_354_tompaana/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/539786639813e59_Story_001_tompaana_354_tompaana/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
STOP log received from  LGD8553bed2d08 Test has  FAILED
Device test finished on LGD8553bed2d08 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device TA4750HV7I app:com.test.thalitest code:0 
child process exited with code 0 on device TA4750HV7I 
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:null 
child process exited with code null on device 320414cd475f91e3 
Android task is completed. [FAILED]
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/539786639813e59_Story_001_tompaana_354_tompaana/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/539786639813e59_Story_001_tompaana_354_tompaana/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/539786639813e59_Story_001_tompaana_354_tompaana/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Error! Unexpected exit on device 0be0c6c6 app:com.test.thalitest code:null 
child process exited with code null on device 0be0c6c6 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/539786639813e59_Story_001_tompaana_354_tompaana/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/539786639813e59_Story_001_tompaana_354_tompaana/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/539786639813e59_Story_001_tompaana_354_tompaana/thali04_samsung-SM-G900F.md)

####Node name: thali05
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 1d6a772d app:com.test.thalitest code:null 
child process exited with code null on device 1d6a772d 
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:null 
child process exited with code null on device ZX1G429CRK 
Error! Unexpected exit on device 954a12ed app:com.test.thalitest code:0 
child process exited with code 0 on device 954a12ed 
Android task is completed. [FAILED]
```
[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/539786639813e59_Story_001_tompaana_354_tompaana/thali05_samsung-SM-N9005.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/539786639813e59_Story_001_tompaana_354_tompaana/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/539786639813e59_Story_001_tompaana_354_tompaana/thali05_samsung-SM-G800H.md)

####Node name: thali06
Console output:
```
STOP log received from  7970f88c Test has  SUCCEEDED
Device test finished on 7970f88c 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:null 
child process exited with code null on device FA55PYS00566 
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:0 
child process exited with code 0 on device 022678fb504e29b0 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/539786639813e59_Story_001_tompaana_354_tompaana/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/539786639813e59_Story_001_tompaana_354_tompaana/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/539786639813e59_Story_001_tompaana_354_tompaana/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device c5afcdcb app:com.test.thalitest code:null 
child process exited with code null on device c5afcdcb 
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:0 
child process exited with code 0 on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/539786639813e59_Story_001_tompaana_354_tompaana/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/539786639813e59_Story_001_tompaana_354_tompaana/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/539786639813e59_Story_001_tompaana_354_tompaana/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/539786639813e59_Story_001_tompaana_354_tompaana/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device CC51WYC03425 app:com.test.thalitest code:0 
child process exited with code 0 on device CC51WYC03425 
Error! Unexpected exit on device 0c6a0f3c0bdb4e77 app:com.test.thalitest code:0 
child process exited with code 0 on device 0c6a0f3c0bdb4e77 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/539786639813e59_Story_001_tompaana_354_tompaana/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/539786639813e59_Story_001_tompaana_354_tompaana/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/539786639813e59_Story_001_tompaana_354_tompaana/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/539786639813e59_Story_001_tompaana_354_tompaana/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/539786639813e59_Story_001_tompaana_354_tompaana/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/539786639813e59_Story_001_tompaana_354_tompaana/iOS_Iphone5s-1.md)



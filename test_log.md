#### Test 539786637913587 Logs

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

2015-12-18T12:51:31.884Z (0 sec) - Android tests will start after waiting for 120 seconds

Test ID 0 configuration: testSendData.js, server timeout: 1200000, data:

{ timeout: 1000000,
  rounds: 1,
  dataTimeout: 20000,
  dataAmount: 100000,
  conReTryTimeout: 5000,
  conReTryCount: 5 }

2015-12-18T12:51:31.889Z (0 sec) - iOS tests will start after waiting for 120 seconds

listening on *:3000

2015-12-18T12:51:32.521Z (1 sec) - Android HTC-HTC One M8s_PT9205 added (current device count 1)

2015-12-18T12:51:32.885Z (1 sec) - Android LGE-Nexus 5_PT8301 added (current device count 2)

2015-12-18T12:51:33.027Z (1 sec) - Android LGE-LG-D855_PT5199 added (current device count 3)

2015-12-18T12:51:33.111Z (1 sec) - Android samsung-SM-A300FU_PT103 added (current device count 4)

2015-12-18T12:51:33.734Z (2 sec) - Android samsung-SM-N910C_PT3932 added (current device count 5)

2015-12-18T12:51:34.123Z (2 sec) - Android motorola-Nexus 6_PT9351 added (current device count 6)

2015-12-18T12:51:34.872Z (3 sec) - Android samsung-SM-G900F_PT3110 added (current device count 7)

2015-12-18T12:51:35.059Z (3 sec) - Android motorola-XT1072_PT5087 added (current device count 8)

2015-12-18T12:51:35.194Z (3 sec) - iOS Apple-Iphone5-1_PT724 added (current device count 1)

2015-12-18T12:51:35.731Z (4 sec) - Android LGE-LG-H815_PT9700 added (current device count 9)

2015-12-18T12:51:35.773Z (4 sec) - Android samsung-SM-A500FU_PT3565 added (current device count 10)

2015-12-18T12:51:35.810Z (4 sec) - Android samsung-SM-G900F_PT4778 added (current device count 11)

2015-12-18T12:51:35.869Z (4 sec) - Android samsung-SM-N9005_PT9178 added (current device count 12)

2015-12-18T12:51:36.291Z (4 sec) - Android samsung-SM-A500FU_PT4523 added (current device count 13)

2015-12-18T12:51:36.446Z (5 sec) - iOS Apple-IpadAir2-1_PT1412 added (current device count 2)

2015-12-18T12:51:36.453Z (5 sec) - iOS Apple-Iphone6-1_PT215 added (current device count 3)

2015-12-18T12:51:36.586Z (5 sec) - Android LGE-LG-D722_PT3638 added (current device count 14)

2015-12-18T12:51:36.808Z (5 sec) - Android samsung-SM-A300FU_PT548 added (current device count 15)

2015-12-18T12:51:37.116Z (5 sec) - iOS Apple-Iphone5s-1_PT4751 added (current device count 4)

2015-12-18T12:51:39.436Z (8 sec) - Android samsung-SM-G800F_PT7064 added (current device count 16)

2015-12-18T12:52:08.997Z (37 sec) - Android motorola-XT1039_PT9097 added (current device count 17)

-------------- We got wait done, now starting the testing process ------------------

2015-12-18T12:53:31.940Z (120 sec) - Android start testing now with 17 devices

2015-12-18T12:53:31.962Z (120 sec) - iOS start testing now with 4 devices

2015-12-18T12:53:45.314Z (133 sec) - iOS Apple-Iphone5s-1_PT4751 test took 13349ms - results peers[0], reConnects[0], sendData[3]

2015-12-18T12:53:47.237Z (135 sec) - iOS Apple-Iphone5-1_PT724 test took 15274ms - results peers[0], reConnects[0], sendData[3]

2015-12-18T12:53:49.434Z (138 sec) - iOS Apple-IpadAir2-1_PT1412 test took 17470ms - results peers[0], reConnects[0], sendData[3]

2015-12-18T12:54:39.274Z (187 sec) - iOS Apple-Iphone6-1_PT215 test took 67310ms - results peers[0], reConnects[0], sendData[3]

2015-12-18T12:54:39.275Z (187 sec) - iOS test ID 0 done now

2015-12-18T12:54:39.282Z (187 sec) - iOS All tests are done, preparing test report

--------------- test report ---------------------

--------------- Apple-Iphone5-1_PT724 --------------------- : 1

sendList : 100% : 4467 ms, 99% : 4467 ms, 95 : 4467 ms, 90% : 4467 ms.

Average data rate: 0.023 MB/s

Result count 3, range 4254 ms to  4467 ms.

sendList failed peers count : 0 [0 %]

sendList never tried peers count : 0 [0 %]

--------------- Apple-IpadAir2-1_PT1412 --------------------- : 2
sendList : 100% : 4490 ms, 99% : 4490 ms, 95 : 4490 ms, 90% : 4490 ms.
Average data rate: 0.023 MB/s

Result count 3, range 4227 ms to  4490 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone6-1_PT215 --------------------- : 3
sendList : 100% : 14096 ms, 99% : 14096 ms, 95 : 14096 ms, 90% : 14096 ms.

Average data rate: 0.011 MB/s
Result count 2, range 4159 ms to  14096 ms.
sendList failed peers count : 1 [33.333333333333336 %]
- Peer ID : Apple-IpadAir2-1_PT6115.GXbC4w==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5s-1_PT4751 --------------------- : 4
sendList : 100% : 4130 ms, 99% : 4130 ms, 95 : 4130 ms, 90% : 4130 ms.
Average data rate: 0.026 MB/s
Result count 3, range 3591 ms to  4130 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- Combined ---------------------

sendList : 100% : 14096 ms, 99% : 14096 ms, 95 : 4490 ms, 90% : 4490 ms.
Average data rate: 0.02 MB/s
--------------- end of test report ---------------------

2015-12-18T12:54:40.643Z (189 sec) - iOS Apple-Iphone6-1_PT215 got disconnected

2015-12-18T12:54:40.853Z (189 sec) - iOS Apple-IpadAir2-1_PT1412 got disconnected

2015-12-18T12:54:44.376Z (193 sec) - iOS Apple-Iphone5-1_PT724 got disconnected

2015-12-18T12:54:53.818Z (202 sec) - iOS Apple-Iphone5s-1_PT4751 got disconnected

2015-12-18T12:55:05.355Z (214 sec) - Android samsung-SM-G900F_PT3110 got disconnected

2015-12-18T12:55:28.091Z (236 sec) - Android HTC-HTC One M8s_PT9205 got disconnected

2015-12-18T12:55:28.578Z (237 sec) - Android samsung-SM-A300FU_PT103 got disconnected

2015-12-18T12:55:40.893Z (249 sec) - Android LGE-LG-D722_PT3638 got re-connected event

2015-12-18T12:55:55.438Z (264 sec) - Android motorola-XT1072_PT5087 got disconnected

2015-12-18T12:55:58.366Z (267 sec) - Android samsung-SM-A500FU_PT3565 got disconnected

2015-12-18T12:56:22.059Z (290 sec) - Android LGE-LG-D722_PT3638 got disconnected

2015-12-18T12:56:23.904Z (292 sec) - Android samsung-SM-A300FU_PT548 got disconnected

2015-12-18T12:56:25.665Z (294 sec) - Android samsung-SM-A500FU_PT4523 got disconnected

2015-12-18T12:56:35.917Z (304 sec) - Android motorola-Nexus 6_PT9351 got re-connected event

2015-12-18T12:57:10.620Z (339 sec) - Android samsung-SM-N910C_PT3932 got disconnected

2015-12-18T12:57:34.900Z (363 sec) - Android motorola-Nexus 6_PT9351 got disconnected

2015-12-18T12:58:22.154Z (410 sec) - Android motorola-Nexus 6_PT9351 got re-connected event

2015-12-18T12:59:16.037Z (464 sec) - Android motorola-Nexus 6_PT9351 got disconnected

2015-12-18T12:59:41.804Z (490 sec) - Android samsung-SM-N9005_PT9178 got disconnected

2015-12-18T13:08:58.451Z (1047 sec) - Android motorola-Nexus 6_PT9351 got disconnected

2015-12-18T13:10:12.291Z (1120 sec) - Android LGE-Nexus 5_PT8301 test took 1000344ms - results peers[0], reConnects[0], sendData[16]

2015-12-18T13:10:12.746Z (1121 sec) - Android LGE-LG-D855_PT5199 test took 1000798ms - results peers[0], reConnects[0], sendData[16]

2015-12-18T13:10:12.841Z (1121 sec) - Android LGE-LG-D722_PT3638 test took 1000885ms - results peers[0], reConnects[0], sendData[16]

2015-12-18T13:10:14.354Z (1123 sec) - Android samsung-SM-G900F_PT4778 test took 1002400ms - results peers[0], reConnects[0], sendData[16]

2015-12-18T13:10:15.254Z (1123 sec) - Android LGE-LG-H815_PT9700 test took 1003301ms - results peers[0], reConnects[0], sendData[16]

2015-12-18T13:13:31.961Z (1320 sec) - Server timeout reached!

2015-12-18T13:13:31.964Z (1320 sec) - Send timeout to HTC-HTC One M8s_PT9205

2015-12-18T13:13:31.966Z (1320 sec) - Send timeout to samsung-SM-A300FU_PT103

2015-12-18T13:13:31.968Z (1320 sec) - Send timeout to samsung-SM-N910C_PT3932

2015-12-18T13:13:31.968Z (1320 sec) - Send timeout to motorola-Nexus 6_PT9351
2015-12-18T13:13:31.969Z (1320 sec) - Send timeout to samsung-SM-G900F_PT3110

2015-12-18T13:13:31.970Z (1320 sec) - Send timeout to motorola-XT1072_PT5087
2015-12-18T13:13:31.970Z (1320 sec) - Send timeout to samsung-SM-A500FU_PT3565
2015-12-18T13:13:31.971Z (1320 sec) - Send timeout to samsung-SM-N9005_PT9178

2015-12-18T13:13:31.971Z (1320 sec) - Send timeout to samsung-SM-A500FU_PT4523
2015-12-18T13:13:31.972Z (1320 sec) - Send timeout to samsung-SM-A300FU_PT548

2015-12-18T13:13:31.972Z (1320 sec) - Send timeout to samsung-SM-G800F_PT7064
2015-12-18T13:13:31.973Z (1320 sec) - Send timeout to motorola-XT1039_PT9097

2015-12-18T13:14:31.974Z (1380 sec) - Did not get reports from all devices, but forcing tests to finish!

HTC-HTC One M8s_PT9205 did not have results at the end of tests - check the device logs about why!!

samsung-SM-A300FU_PT103 did not have results at the end of tests - check the device logs about why!!

samsung-SM-N910C_PT3932 did not have results at the end of tests - check the device logs about why!!
motorola-Nexus 6_PT9351 did not have results at the end of tests - check the device logs about why!!

samsung-SM-G900F_PT3110 did not have results at the end of tests - check the device logs about why!!
motorola-XT1072_PT5087 did not have results at the end of tests - check the device logs about why!!

samsung-SM-A500FU_PT3565 did not have results at the end of tests - check the device logs about why!!

samsung-SM-N9005_PT9178 did not have results at the end of tests - check the device logs about why!!
samsung-SM-A500FU_PT4523 did not have results at the end of tests - check the device logs about why!!

samsung-SM-A300FU_PT548 did not have results at the end of tests - check the device logs about why!!
samsung-SM-G800F_PT7064 did not have results at the end of tests - check the device logs about why!!

motorola-XT1039_PT9097 did not have results at the end of tests - check the device logs about why!!
2015-12-18T13:14:31.990Z (1380 sec) - Android All tests are done, preparing test report

--------------- test report ---------------------
--------------- LGE-Nexus 5_PT8301 --------------------- : 1

sendList : 100% : 81364 ms, 99% : 81364 ms, 95 : 81364 ms, 90% : 13693 ms.
Average data rate: 0.005 MB/s
Result count 6, range 6265 ms to  81364 ms.

sendList failed peers count : 4 [40 %]
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1

sendList never tried peers count : 6 [37.5 %]
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : B0:C5:59:3F:75:69

- Peer ID : 90:E7:C4:F6:69:77
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : F4:F1:E1:5C:3B:E2
--------------- LGE-LG-D855_PT5199 --------------------- : 2
sendList : 100% : 45465 ms, 99% : 45465 ms, 95 : 45465 ms, 90% : 45465 ms.

Average data rate: 0.005 MB/s
Result count 3, range 5560 ms to  45465 ms.
sendList failed peers count : 3 [50 %]
- Peer ID : 7C:F9:0E:51:18:22, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : 90:E7:C4:F6:69:77, Tried : 1

sendList never tried peers count : 10 [62.5 %]
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : F8:CF:C5:D9:E5:61
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : F8:95:C7:87:85:54
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : F8:95:C7:87:3C:51

- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 00:F4:6F:30:E0:6C
--------------- LGE-LG-H815_PT9700 --------------------- : 3
sendList : 100% : 19708 ms, 99% : 19708 ms, 95 : 19708 ms, 90% : 14186 ms.

Average data rate: 0.012 MB/s
Result count 7, range 4037 ms to  19708 ms.
sendList failed peers count : 9 [56.25 %]
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 2
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 90:E7:C4:F6:69:77, Tried : 1

- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 2
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 2
- Peer ID : 7C:F9:0E:51:18:22, Tried : 2
- Peer ID : 08:EC:A9:50:75:41, Tried : 2

sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-G900F_PT4778 --------------------- : 4
sendList : 100% : 59122 ms, 99% : 59122 ms, 95 : 59122 ms, 90% : 13572 ms.
Average data rate: 0.007 MB/s
Result count 7, range 2990 ms to  59122 ms.

sendList failed peers count : 7 [50 %]
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1

- Peer ID : 90:E7:C4:F6:69:77, Tried : 1
sendList never tried peers count : 2 [12.5 %]
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : 7C:F9:0E:51:18:22
--------------- LGE-LG-D722_PT3638 --------------------- : 5
sendList : 100% : 33734 ms, 99% : 33734 ms, 95 : 33734 ms, 90% : 33734 ms.

Average data rate: 0.005 MB/s
Result count 5, range 9064 ms to  33734 ms.
sendList failed peers count : 5 [50 %]
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1

- Peer ID : 7C:F9:0E:51:18:22, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
sendList never tried peers count : 6 [37.5 %]
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 08:EC:A9:50:75:41

- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 44:80:EB:7B:5A:05
--------------- Combined ---------------------
sendList : 100% : 81364 ms, 99% : 81364 ms, 95 : 59122 ms, 90% : 33734 ms.

Average data rate: 0.006 MB/s
--------------- end of test report ---------------------

2015-12-18T13:14:32.381Z (1381 sec) - Android LGE-LG-D722_PT3638 got disconnected

2015-12-18T13:14:32.472Z (1381 sec) - Android LGE-Nexus 5_PT8301 got disconnected

2015-12-18T13:14:33.181Z (1381 sec) - Android LGE-LG-H815_PT9700 got disconnected

2015-12-18T13:14:35.196Z (1383 sec) - Android LGE-LG-D855_PT5199 got disconnected

2015-12-18T13:15:35.842Z (1444 sec) - Android samsung-SM-G900F_PT4778 got disconnected


 
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
Device test finished on LGH8153b36be34 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:null 
child process exited with code null on device f56ad48d 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/539786637913587_Story_001_tompaana_354_tompaana/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/539786637913587_Story_001_tompaana_354_tompaana/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/539786637913587_Story_001_tompaana_354_tompaana/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/539786637913587_Story_001_tompaana_354_tompaana/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device TA4750HV7I app:com.test.thalitest code:0 
child process exited with code 0 on device TA4750HV7I 
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:null 
child process exited with code null on device 320414cd475f91e3 
Android task is completed. [FAILED]
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/539786637913587_Story_001_tompaana_354_tompaana/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/539786637913587_Story_001_tompaana_354_tompaana/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/539786637913587_Story_001_tompaana_354_tompaana/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  0be0c6c6 Test has  SUCCEEDED
Device test finished on 0be0c6c6 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/539786637913587_Story_001_tompaana_354_tompaana/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/539786637913587_Story_001_tompaana_354_tompaana/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/539786637913587_Story_001_tompaana_354_tompaana/thali04_samsung-SM-G900F.md)

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
[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/539786637913587_Story_001_tompaana_354_tompaana/thali05_samsung-SM-N9005.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/539786637913587_Story_001_tompaana_354_tompaana/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/539786637913587_Story_001_tompaana_354_tompaana/thali05_samsung-SM-G800H.md)

####Node name: thali06
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:null 
child process exited with code null on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:0 
child process exited with code 0 on device FA55PYS00566 
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:0 
child process exited with code 0 on device 022678fb504e29b0 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/539786637913587_Story_001_tompaana_354_tompaana/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/539786637913587_Story_001_tompaana_354_tompaana/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/539786637913587_Story_001_tompaana_354_tompaana/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/539786637913587_Story_001_tompaana_354_tompaana/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/539786637913587_Story_001_tompaana_354_tompaana/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/539786637913587_Story_001_tompaana_354_tompaana/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/539786637913587_Story_001_tompaana_354_tompaana/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/539786637913587_Story_001_tompaana_354_tompaana/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/539786637913587_Story_001_tompaana_354_tompaana/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/539786637913587_Story_001_tompaana_354_tompaana/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/539786637913587_Story_001_tompaana_354_tompaana/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/539786637913587_Story_001_tompaana_354_tompaana/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/539786637913587_Story_001_tompaana_354_tompaana/iOS_Iphone5s-1.md)



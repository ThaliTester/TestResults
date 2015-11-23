#### Test 513350284d87320 Logs

Status: 
```

ios : false

server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":21}}
Test ID 0 configuration: testSendData.js, server timeout: 1200000, data:

{ timeout: '1000000',
  rounds: '1',
  dataTimeout: '10000',
  dataAmount: '100000',
  conReTryTimeout: '5000',
  conReTryCount: '5' }

2015-11-23T10:29:07.163Z (0 sec) - Android tests will start after waiting for 120 seconds

Test ID 0 configuration: testSendData.js, server timeout: 1200000, data:

{ timeout: '1000000',
  rounds: '1',
  dataTimeout: '10000',
  dataAmount: '100000',
  conReTryTimeout: '5000',
  conReTryCount: '5' }

2015-11-23T10:29:07.169Z (0 sec) - iOS tests will start after waiting for 120 seconds

listening on *:3000

2015-11-23T10:29:07.531Z (0 sec) - Android LGE-Nexus 5_PT8960 added (current device count 1)

2015-11-23T10:29:07.762Z (1 sec) - Android samsung-SM-G800F_PT5812 added (current device count 2)

2015-11-23T10:29:07.782Z (1 sec) - iOS Apple-IpadAir2-1_PT9757 added (current device count 1)

2015-11-23T10:29:07.928Z (1 sec) - Android LGE-Nexus 5_PT5103 added (current device count 3)

2015-11-23T10:29:08.088Z (1 sec) - Android LGE-LG-D722_PT9740 added (current device count 4)

2015-11-23T10:29:08.356Z (1 sec) - iOS Apple-Iphone5s-1_PT574 added (current device count 2)

2015-11-23T10:29:08.374Z (1 sec) - Android motorola-Nexus 6_PT5015 added (current device count 5)

2015-11-23T10:29:08.563Z (1 sec) - iOS Apple-Iphone5-1_PT1979 added (current device count 3)

2015-11-23T10:29:09.289Z (2 sec) - Android motorola-XT1039_PT1020 added (current device count 6)

2015-11-23T10:29:09.376Z (2 sec) - Android HTC-HTC Desire 820_PT1378 added (current device count 7)

2015-11-23T10:29:09.384Z (2 sec) - Android samsung-SM-A300FU_PT3495 added (current device count 8)

2015-11-23T10:29:09.740Z (3 sec) - Android LGE-LG-D855_PT6848 added (current device count 9)

2015-11-23T10:29:10.389Z (3 sec) - iOS Apple-Iphone6-1_PT4695 added (current device count 4)

2015-11-23T10:29:10.707Z (4 sec) - Android samsung-SM-N910C_PT5515 added (current device count 10)

2015-11-23T10:29:10.824Z (4 sec) - Android HTC-HTC Desire 820_PT515 added (current device count 11)

2015-11-23T10:29:11.204Z (4 sec) - Android samsung-SM-A300FU_PT7946 added (current device count 12)

2015-11-23T10:29:11.579Z (4 sec) - Android LGE-LG-H815_PT7555 added (current device count 13)

2015-11-23T10:29:11.585Z (4 sec) - Android samsung-SM-G900F_PT2678 added (current device count 14)

2015-11-23T10:29:11.757Z (5 sec) - Android HTC-HTC One M8s_PT178 added (current device count 15)

2015-11-23T10:29:11.869Z (5 sec) - Android samsung-SM-A500FU_PT9488 added (current device count 16)

2015-11-23T10:29:11.920Z (5 sec) - Android LGE-LG-D802_PT4760 added (current device count 17)

2015-11-23T10:29:11.956Z (5 sec) - Android samsung-SM-N9005_PT3041 added (current device count 18)

2015-11-23T10:29:12.043Z (5 sec) - Android HUAWEI-ALE-L21_PT9509 added (current device count 19)

2015-11-23T10:29:12.210Z (5 sec) - Android HTC-HTC One_M8_PT4597 added (current device count 20)

2015-11-23T10:29:13.555Z (6 sec) - Android motorola-XT1072_PT3044 added (current device count 21)

-------------- We got wait done, now starting the testing process ------------------

2015-11-23T10:31:07.214Z (120 sec) - Android start testing now with 21 devices

2015-11-23T10:31:07.246Z (120 sec) - iOS start testing now with 4 devices

2015-11-23T10:31:19.344Z (132 sec) - iOS Apple-Iphone5s-1_PT574 test took 12097ms - results peers[0], reConnects[0], sendData[3]

2015-11-23T10:31:20.441Z (133 sec) - iOS Apple-Iphone5-1_PT1979 test took 13193ms - results peers[0], reConnects[0], sendData[3]

2015-11-23T10:31:21.491Z (134 sec) - iOS Apple-Iphone6-1_PT4695 test took 14243ms - results peers[0], reConnects[0], sendData[3]

2015-11-23T10:31:34.004Z (147 sec) - iOS Apple-IpadAir2-1_PT9757 test took 26757ms - results peers[0], reConnects[0], sendData[3]

2015-11-23T10:31:34.005Z (147 sec) - iOS test ID 0 done now

2015-11-23T10:31:34.013Z (147 sec) - iOS All tests are done, preparing test report

--------------- test report ---------------------

--------------- Apple-IpadAir2-1_PT9757 --------------------- : 1

sendList : 100% : 12076 ms, 99% : 12076 ms, 95 : 12076 ms, 90% : 12076 ms.

Result count 3, range 3237 ms to  12076 ms.

sendList failed peers count : 0 [0 %]

sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5s-1_PT574 --------------------- : 2

sendList : 100% : 5017 ms, 99% : 5017 ms, 95 : 5017 ms, 90% : 5017 ms.
Result count 3, range 2604 ms to  5017 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5-1_PT1979 --------------------- : 3
sendList : 100% : 5844 ms, 99% : 5844 ms, 95 : 5844 ms, 90% : 5844 ms.
Result count 3, range 2954 ms to  5844 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1_PT4695 --------------------- : 4

sendList : 100% : 6047 ms, 99% : 6047 ms, 95 : 6047 ms, 90% : 6047 ms.
Result count 3, range 2679 ms to  6047 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- Combined ---------------------

sendList : 100% : 12076 ms, 99% : 12076 ms, 95 : 6047 ms, 90% : 6047 ms.

--------------- end of test report ---------------------

2015-11-23T10:32:20.110Z (193 sec) - Android HTC-HTC One_M8_PT4597 got re-connected event

2015-11-23T10:32:28.934Z (202 sec) - Android LGE-LG-D802_PT4760 got re-connected event

2015-11-23T10:32:37.857Z (211 sec) - Android LGE-Nexus 5_PT8960 got disconnected

2015-11-23T10:32:37.925Z (211 sec) - Android samsung-SM-G800F_PT5812 got disconnected

2015-11-23T10:32:41.551Z (214 sec) - Android samsung-SM-N910C_PT5515 got disconnected

2015-11-23T10:33:06.519Z (239 sec) - Android HTC-HTC Desire 820_PT515 got disconnected

2015-11-23T10:33:07.159Z (240 sec) - Android LGE-LG-D802_PT4760 got disconnected

2015-11-23T10:33:07.832Z (241 sec) - Android HTC-HTC One_M8_PT4597 got disconnected

2015-11-23T10:33:54.024Z (287 sec) - Android LGE-LG-H815_PT7555 got re-connected event

2015-11-23T10:34:51.556Z (344 sec) - Android LGE-LG-H815_PT7555 got disconnected

2015-11-23T10:35:10.258Z (363 sec) - Android motorola-XT1039_PT1020 got disconnected

2015-11-23T10:35:13.733Z (367 sec) - Android LGE-Nexus 5_PT8960 got re-connected event

2015-11-23T10:35:26.111Z (379 sec) - Android motorola-XT1039_PT1020 got re-connected event

2015-11-23T10:35:37.670Z (391 sec) - Android HTC-HTC Desire 820_PT1378 got disconnected

2015-11-23T10:35:46.440Z (399 sec) - Android motorola-XT1072_PT3044 got disconnected

2015-11-23T10:36:01.500Z (414 sec) - Android LGE-Nexus 5_PT8960 got re-connected event

2015-11-23T10:36:29.395Z (442 sec) - Android LGE-LG-D722_PT9740 got disconnected

2015-11-23T10:36:38.738Z (452 sec) - Android LGE-Nexus 5_PT8960 got disconnected

2015-11-23T10:37:14.563Z (487 sec) - Android samsung-SM-A300FU_PT7946 got disconnected

2015-11-23T10:37:19.097Z (492 sec) - Android LGE-LG-H815_PT7555 got re-connected event

2015-11-23T10:37:26.501Z (499 sec) - Android LGE-Nexus 5_PT8960 got disconnected

2015-11-23T10:38:08.224Z (541 sec) - Android motorola-XT1039_PT1020 got disconnected

2015-11-23T10:38:15.825Z (549 sec) - Android LGE-LG-H815_PT7555 got disconnected

2015-11-23T10:38:30.607Z (563 sec) - Android HTC-HTC One M8s_PT178 got disconnected

2015-11-23T10:38:41.182Z (574 sec) - Android samsung-SM-A500FU_PT9488 got disconnected

2015-11-23T10:38:49.689Z (583 sec) - Android HTC-HTC One M8s_PT178 got re-connected event

2015-11-23T10:38:54.639Z (588 sec) - Android LGE-Nexus 5_PT8960 got re-connected event

2015-11-23T10:39:40.713Z (634 sec) - Android HTC-HTC One_M8_PT4597 got disconnected

2015-11-23T10:40:19.644Z (673 sec) - Android LGE-Nexus 5_PT8960 got disconnected

2015-11-23T10:40:40.402Z (693 sec) - Android HTC-HTC One M8s_PT178 got disconnected

2015-11-23T10:41:40.370Z (753 sec) - Android LGE-LG-H815_PT7555 got disconnected

2015-11-23T10:42:27.307Z (800 sec) - Android LGE-Nexus 5_PT8960 got re-connected event

2015-11-23T10:42:43.544Z (816 sec) - Android LGE-LG-D855_PT6848 got disconnected

2015-11-23T10:43:52.308Z (885 sec) - Android LGE-Nexus 5_PT8960 got disconnected

2015-11-23T10:47:47.612Z (1120 sec) - Android samsung-SM-N9005_PT3041 test took 1000374ms - results peers[0], reConnects[0], sendData[20]

2015-11-23T10:47:47.623Z (1121 sec) - Android LGE-Nexus 5_PT5103 test took 1000397ms - results peers[0], reConnects[0], sendData[20]

2015-11-23T10:47:47.756Z (1121 sec) - Android motorola-Nexus 6_PT5015 test took 1000528ms - results peers[0], reConnects[0], sendData[20]

2015-11-23T10:47:48.595Z (1121 sec) - Android HUAWEI-ALE-L21_PT9509 test took 1001356ms - results peers[0], reConnects[0], sendData[20]

2015-11-23T10:47:48.832Z (1122 sec) - Android samsung-SM-A300FU_PT3495 test took 1001601ms - results peers[0], reConnects[0], sendData[20]

2015-11-23T10:47:50.534Z (1123 sec) - Android samsung-SM-G900F_PT2678 test took 1003298ms - results peers[0], reConnects[0], sendData[20]

2015-11-23T10:47:51.076Z (1124 sec) - Android LGE-LG-D802_PT4760 test took 1003838ms - results peers[0], reConnects[0], sendData[20]

2015-11-23T10:48:38.462Z (1171 sec) - Android LGE-Nexus 5_PT8960 got re-connected event

2015-11-23T10:48:38.466Z (1171 sec) - Android LGE-Nexus 5_PT8960 test took 1051244ms - results peers[0], reConnects[0], sendData[20]

2015-11-23T10:51:07.252Z (1320 sec) - Server timeout reached!

2015-11-23T10:51:07.253Z (1320 sec) - Send timeout to samsung-SM-G800F_PT5812

2015-11-23T10:51:07.254Z (1320 sec) - Send timeout to LGE-LG-D722_PT9740
2015-11-23T10:51:07.255Z (1320 sec) - Send timeout to motorola-XT1039_PT1020

2015-11-23T10:51:07.256Z (1320 sec) - Send timeout to HTC-HTC Desire 820_PT1378

2015-11-23T10:51:07.257Z (1320 sec) - Send timeout to LGE-LG-D855_PT6848

2015-11-23T10:51:07.258Z (1320 sec) - Send timeout to samsung-SM-N910C_PT5515
2015-11-23T10:51:07.259Z (1320 sec) - Send timeout to HTC-HTC Desire 820_PT515

2015-11-23T10:51:07.260Z (1320 sec) - Send timeout to samsung-SM-A300FU_PT7946

2015-11-23T10:51:07.260Z (1320 sec) - Send timeout to LGE-LG-H815_PT7555

2015-11-23T10:51:07.261Z (1320 sec) - Send timeout to HTC-HTC One M8s_PT178

2015-11-23T10:51:07.262Z (1320 sec) - Send timeout to samsung-SM-A500FU_PT9488
2015-11-23T10:51:07.263Z (1320 sec) - Send timeout to HTC-HTC One_M8_PT4597

2015-11-23T10:51:07.264Z (1320 sec) - Send timeout to motorola-XT1072_PT3044

2015-11-23T10:52:07.266Z (1380 sec) - Did not get reports from all devices, but forcing tests to finish!

samsung-SM-G800F_PT5812 did not have results at the end of tests - check the device logs about why!!

LGE-LG-D722_PT9740 did not have results at the end of tests - check the device logs about why!!

motorola-XT1039_PT1020 did not have results at the end of tests - check the device logs about why!!
HTC-HTC Desire 820_PT1378 did not have results at the end of tests - check the device logs about why!!
LGE-LG-D855_PT6848 did not have results at the end of tests - check the device logs about why!!
samsung-SM-N910C_PT5515 did not have results at the end of tests - check the device logs about why!!
HTC-HTC Desire 820_PT515 did not have results at the end of tests - check the device logs about why!!
samsung-SM-A300FU_PT7946 did not have results at the end of tests - check the device logs about why!!
LGE-LG-H815_PT7555 did not have results at the end of tests - check the device logs about why!!

HTC-HTC One M8s_PT178 did not have results at the end of tests - check the device logs about why!!

samsung-SM-A500FU_PT9488 did not have results at the end of tests - check the device logs about why!!

HTC-HTC One_M8_PT4597 did not have results at the end of tests - check the device logs about why!!

motorola-XT1072_PT3044 did not have results at the end of tests - check the device logs about why!!
2015-11-23T10:52:07.288Z (1380 sec) - Android All tests are done, preparing test report

--------------- test report ---------------------
--------------- LGE-Nexus 5_PT8960 --------------------- : 1
sendList : 100% : 133955 ms, 99% : 133955 ms, 95 : 106122 ms, 90% : 106122 ms.

Result count 13, range 3741 ms to  133955 ms.
sendList failed peers count : 6 [31.57894736842105 %]
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 50:2E:6C:AC:21:50, Tried : 1
- Peer ID : 90:E7:C4:F6:69:77, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
sendList never tried peers count : 1 [5 %]
- Peer ID : F8:95:C7:87:85:54
--------------- LGE-Nexus 5_PT5103 --------------------- : 2
sendList : 100% : 224404 ms, 99% : 224404 ms, 95 : 224404 ms, 90% : 146321 ms.

Result count 8, range 1513 ms to  224404 ms.
sendList failed peers count : 7 [46.666666666666664 %]
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 50:2E:6C:AC:21:50, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : 90:E7:C4:F6:69:77, Tried : 1
sendList never tried peers count : 5 [25 %]
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : F8:95:C7:87:85:54
- Peer ID : E0:DB:10:1F:C9:5E
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 00:F4:6F:30:E0:6C
--------------- motorola-Nexus 6_PT5015 --------------------- : 3
sendList : 100% : 111811 ms, 99% : 111811 ms, 95 : 49441 ms, 90% : 47327 ms.
Result count 16, range 2315 ms to  111811 ms.
sendList failed peers count : 4 [20 %]
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 2
- Peer ID : 50:2E:6C:AC:21:50, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 90:E7:C4:F6:69:77, Tried : 1
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-A300FU_PT3495 --------------------- : 4
sendList : 100% : 79944 ms, 99% : 79944 ms, 95 : 74617 ms, 90% : 55055 ms.
Result count 16, range 3168 ms to  79944 ms.
sendList failed peers count : 4 [20 %]
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 3
- Peer ID : 50:2E:6C:AC:21:50, Tried : 2
- Peer ID : 90:E7:C4:F6:69:77, Tried : 2
- Peer ID : 80:01:84:8A:B3:68, Tried : 2
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-G900F_PT2678 --------------------- : 5
sendList : 100% : 135835 ms, 99% : 135835 ms, 95 : 135835 ms, 90% : 107900 ms.
Result count 10, range 5407 ms to  135835 ms.
sendList failed peers count : 6 [37.5 %]
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 90:E7:C4:F6:69:77, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
sendList never tried peers count : 4 [20 %]
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 34:FC:EF:9D:93:0B
--------------- LGE-LG-D802_PT4760 --------------------- : 6
sendList : 100% : 54230 ms, 99% : 54230 ms, 95 : 35917 ms, 90% : 34880 ms.
Result count 17, range 4074 ms to  54230 ms.
sendList failed peers count : 3 [15 %]
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 4
- Peer ID : 90:E7:C4:F6:69:77, Tried : 3
- Peer ID : 80:01:84:8A:B3:68, Tried : 4

sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-N9005_PT3041 --------------------- : 7
sendList : 100% : 103839 ms, 99% : 103839 ms, 95 : 93814 ms, 90% : 52246 ms.
Result count 16, range 3416 ms to  103839 ms.
sendList failed peers count : 4 [20 %]
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 2
- Peer ID : 50:2E:6C:AC:21:50, Tried : 1

- Peer ID : 58:2A:F7:ED:96:BE, Tried : 2
- Peer ID : 80:01:84:8A:B3:68, Tried : 2
sendList never tried peers count : 0 [0 %]
--------------- HUAWEI-ALE-L21_PT9509 --------------------- : 8

sendList : 100% : 92511 ms, 99% : 92511 ms, 95 : 92511 ms, 90% : 92511 ms.
Result count 1, range 92511 ms to  92511 ms.
sendList failed peers count : 19 [95 %]
- Peer ID : 58:3F:54:73:64:C0, Tried : 2

- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 90:E7:C4:F6:69:77, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : 50:2E:6C:AC:21:50, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 2
- Peer ID : 80:01:84:8A:B3:68, Tried : 2

sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------

sendList : 100% : 224404 ms, 99% : 146321 ms, 95 : 107900 ms, 90% : 79944 ms.

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
Error! Unexpected exit on device TA4750HV7I app:com.test.thalitest code:null 
child process exited with code null on device TA4750HV7I 
Error! Unexpected exit on device LGD8553bed2d08 app:com.test.thalitest code:null 
child process exited with code null on device LGD8553bed2d08 
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:null 
child process exited with code null on device 320414cd475f91e3 
Android task is completed 
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/513350284d87320_Work_in_progress__vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/513350284d87320_Work_in_progress__vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/513350284d87320_Work_in_progress__vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:null 
child process exited with code null on device ZX1C223JKW 
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed 
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/513350284d87320_Work_in_progress__vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/513350284d87320_Work_in_progress__vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/513350284d87320_Work_in_progress__vjrantal/thali04_samsung-SM-G900F.md)

####Node name: thali05
Console output:
```
Error! Unexpected exit on device SH47FWM00508 app:com.test.thalitest code:null 
child process exited with code null on device SH47FWM00508 
Android task is completed 
```
[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/513350284d87320_Work_in_progress__vjrantal/thali05_samsung-SM-N9005.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/513350284d87320_Work_in_progress__vjrantal/thali05_motorola-Nexus 6.md)

[HTC-HTC One_M8](https://github.com/ThaliTester/TestResults/blob/513350284d87320_Work_in_progress__vjrantal/thali05_HTC-HTC One_M8.md)

####Node name: thali06
####Node name: thali07
####Node name: thali08
####Node name: thali09



###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/513350284d87320_Work_in_progress__vjrantal/iOS_Iphone5-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/513350284d87320_Work_in_progress__vjrantal/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/513350284d87320_Work_in_progress__vjrantal/iOS_Iphone6-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/513350284d87320_Work_in_progress__vjrantal/iOS_IpadAir2-1.md)


#### Integration Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":21}}
Test ID 0 configuration: testSendData.js, server timeout: 1200000, data:

{ timeout: '1000000',
  rounds: '1',
  dataTimeout: '10000',
  dataAmount: '100000',
  conReTryTimeout: '5000',
  conReTryCount: '5' }

2015-11-23T10:29:07.163Z (0 sec) - Android tests will start after waiting for 120 seconds

Test ID 0 configuration: testSendData.js, server timeout: 1200000, data:

{ timeout: '1000000',
  rounds: '1',
  dataTimeout: '10000',
  dataAmount: '100000',
  conReTryTimeout: '5000',
  conReTryCount: '5' }

2015-11-23T10:29:07.169Z (0 sec) - iOS tests will start after waiting for 120 seconds

listening on *:3000

2015-11-23T10:29:07.531Z (0 sec) - Android LGE-Nexus 5_PT8960 added (current device count 1)

2015-11-23T10:29:07.762Z (1 sec) - Android samsung-SM-G800F_PT5812 added (current device count 2)

2015-11-23T10:29:07.782Z (1 sec) - iOS Apple-IpadAir2-1_PT9757 added (current device count 1)

2015-11-23T10:29:07.928Z (1 sec) - Android LGE-Nexus 5_PT5103 added (current device count 3)

2015-11-23T10:29:08.088Z (1 sec) - Android LGE-LG-D722_PT9740 added (current device count 4)

2015-11-23T10:29:08.356Z (1 sec) - iOS Apple-Iphone5s-1_PT574 added (current device count 2)

2015-11-23T10:29:08.374Z (1 sec) - Android motorola-Nexus 6_PT5015 added (current device count 5)

2015-11-23T10:29:08.563Z (1 sec) - iOS Apple-Iphone5-1_PT1979 added (current device count 3)

2015-11-23T10:29:09.289Z (2 sec) - Android motorola-XT1039_PT1020 added (current device count 6)

2015-11-23T10:29:09.376Z (2 sec) - Android HTC-HTC Desire 820_PT1378 added (current device count 7)

2015-11-23T10:29:09.384Z (2 sec) - Android samsung-SM-A300FU_PT3495 added (current device count 8)

2015-11-23T10:29:09.740Z (3 sec) - Android LGE-LG-D855_PT6848 added (current device count 9)

2015-11-23T10:29:10.389Z (3 sec) - iOS Apple-Iphone6-1_PT4695 added (current device count 4)

2015-11-23T10:29:10.707Z (4 sec) - Android samsung-SM-N910C_PT5515 added (current device count 10)

2015-11-23T10:29:10.824Z (4 sec) - Android HTC-HTC Desire 820_PT515 added (current device count 11)

2015-11-23T10:29:11.204Z (4 sec) - Android samsung-SM-A300FU_PT7946 added (current device count 12)

2015-11-23T10:29:11.579Z (4 sec) - Android LGE-LG-H815_PT7555 added (current device count 13)

2015-11-23T10:29:11.585Z (4 sec) - Android samsung-SM-G900F_PT2678 added (current device count 14)

2015-11-23T10:29:11.757Z (5 sec) - Android HTC-HTC One M8s_PT178 added (current device count 15)

2015-11-23T10:29:11.869Z (5 sec) - Android samsung-SM-A500FU_PT9488 added (current device count 16)

2015-11-23T10:29:11.920Z (5 sec) - Android LGE-LG-D802_PT4760 added (current device count 17)

2015-11-23T10:29:11.956Z (5 sec) - Android samsung-SM-N9005_PT3041 added (current device count 18)

2015-11-23T10:29:12.043Z (5 sec) - Android HUAWEI-ALE-L21_PT9509 added (current device count 19)

2015-11-23T10:29:12.210Z (5 sec) - Android HTC-HTC One_M8_PT4597 added (current device count 20)

2015-11-23T10:29:13.555Z (6 sec) - Android motorola-XT1072_PT3044 added (current device count 21)

-------------- We got wait done, now starting the testing process ------------------

2015-11-23T10:31:07.214Z (120 sec) - Android start testing now with 21 devices

2015-11-23T10:31:07.246Z (120 sec) - iOS start testing now with 4 devices

2015-11-23T10:31:19.344Z (132 sec) - iOS Apple-Iphone5s-1_PT574 test took 12097ms - results peers[0], reConnects[0], sendData[3]

2015-11-23T10:31:20.441Z (133 sec) - iOS Apple-Iphone5-1_PT1979 test took 13193ms - results peers[0], reConnects[0], sendData[3]

2015-11-23T10:31:21.491Z (134 sec) - iOS Apple-Iphone6-1_PT4695 test took 14243ms - results peers[0], reConnects[0], sendData[3]

2015-11-23T10:31:34.004Z (147 sec) - iOS Apple-IpadAir2-1_PT9757 test took 26757ms - results peers[0], reConnects[0], sendData[3]

2015-11-23T10:31:34.005Z (147 sec) - iOS test ID 0 done now

2015-11-23T10:31:34.013Z (147 sec) - iOS All tests are done, preparing test report

--------------- test report ---------------------

--------------- Apple-IpadAir2-1_PT9757 --------------------- : 1

sendList : 100% : 12076 ms, 99% : 12076 ms, 95 : 12076 ms, 90% : 12076 ms.

Result count 3, range 3237 ms to  12076 ms.

sendList failed peers count : 0 [0 %]

sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5s-1_PT574 --------------------- : 2

sendList : 100% : 5017 ms, 99% : 5017 ms, 95 : 5017 ms, 90% : 5017 ms.
Result count 3, range 2604 ms to  5017 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5-1_PT1979 --------------------- : 3
sendList : 100% : 5844 ms, 99% : 5844 ms, 95 : 5844 ms, 90% : 5844 ms.
Result count 3, range 2954 ms to  5844 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1_PT4695 --------------------- : 4

sendList : 100% : 6047 ms, 99% : 6047 ms, 95 : 6047 ms, 90% : 6047 ms.
Result count 3, range 2679 ms to  6047 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- Combined ---------------------

sendList : 100% : 12076 ms, 99% : 12076 ms, 95 : 6047 ms, 90% : 6047 ms.

--------------- end of test report ---------------------

2015-11-23T10:32:20.110Z (193 sec) - Android HTC-HTC One_M8_PT4597 got re-connected event

2015-11-23T10:32:28.934Z (202 sec) - Android LGE-LG-D802_PT4760 got re-connected event

2015-11-23T10:32:37.857Z (211 sec) - Android LGE-Nexus 5_PT8960 got disconnected

2015-11-23T10:32:37.925Z (211 sec) - Android samsung-SM-G800F_PT5812 got disconnected

2015-11-23T10:32:41.551Z (214 sec) - Android samsung-SM-N910C_PT5515 got disconnected

2015-11-23T10:33:06.519Z (239 sec) - Android HTC-HTC Desire 820_PT515 got disconnected

2015-11-23T10:33:07.159Z (240 sec) - Android LGE-LG-D802_PT4760 got disconnected

2015-11-23T10:33:07.832Z (241 sec) - Android HTC-HTC One_M8_PT4597 got disconnected

2015-11-23T10:33:54.024Z (287 sec) - Android LGE-LG-H815_PT7555 got re-connected event

2015-11-23T10:34:51.556Z (344 sec) - Android LGE-LG-H815_PT7555 got disconnected

2015-11-23T10:35:10.258Z (363 sec) - Android motorola-XT1039_PT1020 got disconnected

2015-11-23T10:35:13.733Z (367 sec) - Android LGE-Nexus 5_PT8960 got re-connected event

2015-11-23T10:35:26.111Z (379 sec) - Android motorola-XT1039_PT1020 got re-connected event

2015-11-23T10:35:37.670Z (391 sec) - Android HTC-HTC Desire 820_PT1378 got disconnected

2015-11-23T10:35:46.440Z (399 sec) - Android motorola-XT1072_PT3044 got disconnected

2015-11-23T10:36:01.500Z (414 sec) - Android LGE-Nexus 5_PT8960 got re-connected event

2015-11-23T10:36:29.395Z (442 sec) - Android LGE-LG-D722_PT9740 got disconnected

2015-11-23T10:36:38.738Z (452 sec) - Android LGE-Nexus 5_PT8960 got disconnected

2015-11-23T10:37:14.563Z (487 sec) - Android samsung-SM-A300FU_PT7946 got disconnected

2015-11-23T10:37:19.097Z (492 sec) - Android LGE-LG-H815_PT7555 got re-connected event

2015-11-23T10:37:26.501Z (499 sec) - Android LGE-Nexus 5_PT8960 got disconnected

2015-11-23T10:38:08.224Z (541 sec) - Android motorola-XT1039_PT1020 got disconnected

2015-11-23T10:38:15.825Z (549 sec) - Android LGE-LG-H815_PT7555 got disconnected

2015-11-23T10:38:30.607Z (563 sec) - Android HTC-HTC One M8s_PT178 got disconnected

2015-11-23T10:38:41.182Z (574 sec) - Android samsung-SM-A500FU_PT9488 got disconnected

2015-11-23T10:38:49.689Z (583 sec) - Android HTC-HTC One M8s_PT178 got re-connected event

2015-11-23T10:38:54.639Z (588 sec) - Android LGE-Nexus 5_PT8960 got re-connected event

2015-11-23T10:39:40.713Z (634 sec) - Android HTC-HTC One_M8_PT4597 got disconnected

2015-11-23T10:40:19.644Z (673 sec) - Android LGE-Nexus 5_PT8960 got disconnected

2015-11-23T10:40:40.402Z (693 sec) - Android HTC-HTC One M8s_PT178 got disconnected

2015-11-23T10:41:40.370Z (753 sec) - Android LGE-LG-H815_PT7555 got disconnected

2015-11-23T10:42:27.307Z (800 sec) - Android LGE-Nexus 5_PT8960 got re-connected event

2015-11-23T10:42:43.544Z (816 sec) - Android LGE-LG-D855_PT6848 got disconnected

2015-11-23T10:43:52.308Z (885 sec) - Android LGE-Nexus 5_PT8960 got disconnected

2015-11-23T10:47:47.612Z (1120 sec) - Android samsung-SM-N9005_PT3041 test took 1000374ms - results peers[0], reConnects[0], sendData[20]

2015-11-23T10:47:47.623Z (1121 sec) - Android LGE-Nexus 5_PT5103 test took 1000397ms - results peers[0], reConnects[0], sendData[20]

2015-11-23T10:47:47.756Z (1121 sec) - Android motorola-Nexus 6_PT5015 test took 1000528ms - results peers[0], reConnects[0], sendData[20]

2015-11-23T10:47:48.595Z (1121 sec) - Android HUAWEI-ALE-L21_PT9509 test took 1001356ms - results peers[0], reConnects[0], sendData[20]

2015-11-23T10:47:48.832Z (1122 sec) - Android samsung-SM-A300FU_PT3495 test took 1001601ms - results peers[0], reConnects[0], sendData[20]

2015-11-23T10:47:50.534Z (1123 sec) - Android samsung-SM-G900F_PT2678 test took 1003298ms - results peers[0], reConnects[0], sendData[20]

2015-11-23T10:47:51.076Z (1124 sec) - Android LGE-LG-D802_PT4760 test took 1003838ms - results peers[0], reConnects[0], sendData[20]

2015-11-23T10:48:38.462Z (1171 sec) - Android LGE-Nexus 5_PT8960 got re-connected event

2015-11-23T10:48:38.466Z (1171 sec) - Android LGE-Nexus 5_PT8960 test took 1051244ms - results peers[0], reConnects[0], sendData[20]

2015-11-23T10:51:07.252Z (1320 sec) - Server timeout reached!

2015-11-23T10:51:07.253Z (1320 sec) - Send timeout to samsung-SM-G800F_PT5812

2015-11-23T10:51:07.254Z (1320 sec) - Send timeout to LGE-LG-D722_PT9740
2015-11-23T10:51:07.255Z (1320 sec) - Send timeout to motorola-XT1039_PT1020

2015-11-23T10:51:07.256Z (1320 sec) - Send timeout to HTC-HTC Desire 820_PT1378

2015-11-23T10:51:07.257Z (1320 sec) - Send timeout to LGE-LG-D855_PT6848

2015-11-23T10:51:07.258Z (1320 sec) - Send timeout to samsung-SM-N910C_PT5515
2015-11-23T10:51:07.259Z (1320 sec) - Send timeout to HTC-HTC Desire 820_PT515

2015-11-23T10:51:07.260Z (1320 sec) - Send timeout to samsung-SM-A300FU_PT7946

2015-11-23T10:51:07.260Z (1320 sec) - Send timeout to LGE-LG-H815_PT7555

2015-11-23T10:51:07.261Z (1320 sec) - Send timeout to HTC-HTC One M8s_PT178

2015-11-23T10:51:07.262Z (1320 sec) - Send timeout to samsung-SM-A500FU_PT9488
2015-11-23T10:51:07.263Z (1320 sec) - Send timeout to HTC-HTC One_M8_PT4597

2015-11-23T10:51:07.264Z (1320 sec) - Send timeout to motorola-XT1072_PT3044

2015-11-23T10:52:07.266Z (1380 sec) - Did not get reports from all devices, but forcing tests to finish!

samsung-SM-G800F_PT5812 did not have results at the end of tests - check the device logs about why!!

LGE-LG-D722_PT9740 did not have results at the end of tests - check the device logs about why!!

motorola-XT1039_PT1020 did not have results at the end of tests - check the device logs about why!!
HTC-HTC Desire 820_PT1378 did not have results at the end of tests - check the device logs about why!!
LGE-LG-D855_PT6848 did not have results at the end of tests - check the device logs about why!!
samsung-SM-N910C_PT5515 did not have results at the end of tests - check the device logs about why!!
HTC-HTC Desire 820_PT515 did not have results at the end of tests - check the device logs about why!!
samsung-SM-A300FU_PT7946 did not have results at the end of tests - check the device logs about why!!
LGE-LG-H815_PT7555 did not have results at the end of tests - check the device logs about why!!

HTC-HTC One M8s_PT178 did not have results at the end of tests - check the device logs about why!!

samsung-SM-A500FU_PT9488 did not have results at the end of tests - check the device logs about why!!

HTC-HTC One_M8_PT4597 did not have results at the end of tests - check the device logs about why!!

motorola-XT1072_PT3044 did not have results at the end of tests - check the device logs about why!!
2015-11-23T10:52:07.288Z (1380 sec) - Android All tests are done, preparing test report

--------------- test report ---------------------
--------------- LGE-Nexus 5_PT8960 --------------------- : 1
sendList : 100% : 133955 ms, 99% : 133955 ms, 95 : 106122 ms, 90% : 106122 ms.

Result count 13, range 3741 ms to  133955 ms.
sendList failed peers count : 6 [31.57894736842105 %]
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 50:2E:6C:AC:21:50, Tried : 1
- Peer ID : 90:E7:C4:F6:69:77, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
sendList never tried peers count : 1 [5 %]
- Peer ID : F8:95:C7:87:85:54
--------------- LGE-Nexus 5_PT5103 --------------------- : 2
sendList : 100% : 224404 ms, 99% : 224404 ms, 95 : 224404 ms, 90% : 146321 ms.

Result count 8, range 1513 ms to  224404 ms.
sendList failed peers count : 7 [46.666666666666664 %]
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 50:2E:6C:AC:21:50, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : 90:E7:C4:F6:69:77, Tried : 1
sendList never tried peers count : 5 [25 %]
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : F8:95:C7:87:85:54
- Peer ID : E0:DB:10:1F:C9:5E
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 00:F4:6F:30:E0:6C
--------------- motorola-Nexus 6_PT5015 --------------------- : 3
sendList : 100% : 111811 ms, 99% : 111811 ms, 95 : 49441 ms, 90% : 47327 ms.
Result count 16, range 2315 ms to  111811 ms.
sendList failed peers count : 4 [20 %]
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 2
- Peer ID : 50:2E:6C:AC:21:50, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 90:E7:C4:F6:69:77, Tried : 1
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-A300FU_PT3495 --------------------- : 4
sendList : 100% : 79944 ms, 99% : 79944 ms, 95 : 74617 ms, 90% : 55055 ms.
Result count 16, range 3168 ms to  79944 ms.
sendList failed peers count : 4 [20 %]
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 3
- Peer ID : 50:2E:6C:AC:21:50, Tried : 2
- Peer ID : 90:E7:C4:F6:69:77, Tried : 2
- Peer ID : 80:01:84:8A:B3:68, Tried : 2
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-G900F_PT2678 --------------------- : 5
sendList : 100% : 135835 ms, 99% : 135835 ms, 95 : 135835 ms, 90% : 107900 ms.
Result count 10, range 5407 ms to  135835 ms.
sendList failed peers count : 6 [37.5 %]
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 90:E7:C4:F6:69:77, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
sendList never tried peers count : 4 [20 %]
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 34:FC:EF:9D:93:0B
--------------- LGE-LG-D802_PT4760 --------------------- : 6
sendList : 100% : 54230 ms, 99% : 54230 ms, 95 : 35917 ms, 90% : 34880 ms.
Result count 17, range 4074 ms to  54230 ms.
sendList failed peers count : 3 [15 %]
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 4
- Peer ID : 90:E7:C4:F6:69:77, Tried : 3
- Peer ID : 80:01:84:8A:B3:68, Tried : 4

sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-N9005_PT3041 --------------------- : 7
sendList : 100% : 103839 ms, 99% : 103839 ms, 95 : 93814 ms, 90% : 52246 ms.
Result count 16, range 3416 ms to  103839 ms.
sendList failed peers count : 4 [20 %]
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 2
- Peer ID : 50:2E:6C:AC:21:50, Tried : 1

- Peer ID : 58:2A:F7:ED:96:BE, Tried : 2
- Peer ID : 80:01:84:8A:B3:68, Tried : 2
sendList never tried peers count : 0 [0 %]
--------------- HUAWEI-ALE-L21_PT9509 --------------------- : 8

sendList : 100% : 92511 ms, 99% : 92511 ms, 95 : 92511 ms, 90% : 92511 ms.
Result count 1, range 92511 ms to  92511 ms.
sendList failed peers count : 19 [95 %]
- Peer ID : 58:3F:54:73:64:C0, Tried : 2

- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 90:E7:C4:F6:69:77, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : 50:2E:6C:AC:21:50, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 2
- Peer ID : 80:01:84:8A:B3:68, Tried : 2

sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------

sendList : 100% : 224404 ms, 99% : 146321 ms, 95 : 107900 ms, 90% : 79944 ms.

--------------- end of test report ---------------------


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


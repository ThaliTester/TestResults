#### Test 51335028c93db41 Logs

Status: 
```

ios : false

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m



server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":23}}
Test ID 0 configuration: testSendData.js, server timeout: 1200000, data:

{ timeout: 1000000,
  rounds: 1,
  dataTimeout: 10000,
  dataAmount: 100000,
  conReTryTimeout: 5000,
  conReTryCount: 5 }

2015-11-25T12:51:10.114Z (0 sec) - Android tests will start after waiting for 120 seconds

Test ID 0 configuration: testSendData.js, server timeout: 1200000, data:

{ timeout: 1000000,
  rounds: 1,
  dataTimeout: 10000,
  dataAmount: 100000,
  conReTryTimeout: 5000,
  conReTryCount: 5 }

2015-11-25T12:51:10.120Z (0 sec) - iOS tests will start after waiting for 120 seconds

listening on *:3000

2015-11-25T12:51:10.602Z (1 sec) - Android LGE-LG-H815_PT1856 added (current device count 1)

2015-11-25T12:51:10.674Z (1 sec) - iOS Apple-Iphone5s-1_PT5807 added (current device count 1)

2015-11-25T12:51:10.888Z (1 sec) - Android LGE-LG-D802_PT7336 added (current device count 2)

2015-11-25T12:51:11.016Z (1 sec) - Android HUAWEI-ALE-L21_PT9922 added (current device count 3)

2015-11-25T12:51:11.336Z (1 sec) - Android LGE-Nexus 5_PT1775 added (current device count 4)

2015-11-25T12:51:11.506Z (1 sec) - Android samsung-SM-A300FU_PT5188 added (current device count 5)

2015-11-25T12:51:11.553Z (1 sec) - Android LGE-LG-D855_PT4436 added (current device count 6)

2015-11-25T12:51:11.889Z (2 sec) - Android samsung-SM-A500FU_PT3573 added (current device count 7)

2015-11-25T12:51:11.907Z (2 sec) - Android motorola-XT1039_PT9305 added (current device count 8)

2015-11-25T12:51:12.049Z (2 sec) - Android HTC-HTC One_M8_PT2939 added (current device count 9)

2015-11-25T12:51:12.434Z (2 sec) - iOS Apple-IpadAir2-1_PT7357 added (current device count 2)

2015-11-25T12:51:12.450Z (2 sec) - Android samsung-SM-G900F_PT4845 added (current device count 10)

2015-11-25T12:51:12.721Z (3 sec) - Android samsung-SM-N9005_PT1333 added (current device count 11)

2015-11-25T12:51:12.768Z (3 sec) - iOS Apple-Iphone6-1_PT8750 added (current device count 3)

2015-11-25T12:51:13.170Z (3 sec) - Android samsung-SM-N910C_PT3817 added (current device count 12)

2015-11-25T12:51:13.307Z (3 sec) - iOS Apple-Iphone5-1_PT9701 added (current device count 4)

2015-11-25T12:51:13.884Z (4 sec) - Android samsung-SM-G800F_PT8819 added (current device count 13)

2015-11-25T12:51:14.088Z (4 sec) - Android LGE-LG-D722_PT9505 added (current device count 14)

2015-11-25T12:51:14.200Z (4 sec) - Android samsung-SM-A300FU_PT7895 added (current device count 15)

2015-11-25T12:51:14.496Z (4 sec) - Android LGE-Nexus 5_PT7844 added (current device count 16)

2015-11-25T12:51:14.537Z (4 sec) - Android motorola-Nexus 6_PT2615 added (current device count 17)

2015-11-25T12:51:14.698Z (5 sec) - Android HTC-HTC Desire 820_PT6694 added (current device count 18)

2015-11-25T12:51:14.895Z (5 sec) - Android samsung-SM-A500FU_PT2993 added (current device count 19)

2015-11-25T12:51:14.928Z (5 sec) - Android HTC-HTC Desire 820_PT3971 added (current device count 20)

2015-11-25T12:51:14.945Z (5 sec) - Android samsung-SM-G900F_PT3994 added (current device count 21)

2015-11-25T12:51:20.593Z (11 sec) - Android motorola-XT1072_PT1876 added (current device count 22)

-------------- We got wait done, now starting the testing process ------------------

2015-11-25T12:53:10.167Z (120 sec) - Android start testing now with 22 devices

2015-11-25T12:53:10.195Z (120 sec) - iOS start testing now with 4 devices

2015-11-25T12:53:20.416Z (130 sec) - iOS Apple-Iphone6-1_PT8750 test took 10219ms - results peers[0], reConnects[0], sendData[3]

2015-11-25T12:53:22.112Z (132 sec) - iOS Apple-Iphone5s-1_PT5807 test took 11915ms - results peers[0], reConnects[0], sendData[3]

2015-11-25T12:53:23.898Z (134 sec) - iOS Apple-IpadAir2-1_PT7357 test took 13702ms - results peers[0], reConnects[0], sendData[3]

2015-11-25T12:53:24.086Z (134 sec) - iOS Apple-Iphone5-1_PT9701 test took 13889ms - results peers[0], reConnects[0], sendData[3]

2015-11-25T12:53:24.087Z (134 sec) - iOS test ID 0 done now

2015-11-25T12:53:24.096Z (134 sec) - iOS All tests are done, preparing test report

--------------- test report ---------------------

--------------- Apple-Iphone5s-1_PT5807 --------------------- : 1

sendList : 100% : 4699 ms, 99% : 4699 ms, 95 : 4699 ms, 90% : 4699 ms.

Average data rate: 0.028 MB/s

Result count 3, range 2813 ms to  4699 ms.

sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- Apple-IpadAir2-1_PT7357 --------------------- : 2

sendList : 100% : 4670 ms, 99% : 4670 ms, 95 : 4670 ms, 90% : 4670 ms.
Average data rate: 0.024 MB/s
Result count 3, range 3819 ms to  4670 ms.
sendList failed peers count : 0 [0 %]

sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1_PT8750 --------------------- : 3
sendList : 100% : 3276 ms, 99% : 3276 ms, 95 : 3276 ms, 90% : 3276 ms.

Average data rate: 0.033 MB/s
Result count 3, range 2922 ms to  3276 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5-1_PT9701 --------------------- : 4

sendList : 100% : 6797 ms, 99% : 6797 ms, 95 : 6797 ms, 90% : 6797 ms.

Average data rate: 0.023 MB/s
Result count 3, range 2674 ms to  6797 ms.

sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------

sendList : 100% : 6797 ms, 99% : 6797 ms, 95 : 4699 ms, 90% : 4699 ms.

Average data rate: 0.026 MB/s
--------------- end of test report ---------------------

2015-11-25T12:53:24.418Z (134 sec) - iOS Apple-Iphone6-1_PT8750 got disconnected

2015-11-25T12:53:24.954Z (135 sec) - iOS Apple-IpadAir2-1_PT7357 got disconnected

2015-11-25T12:53:25.169Z (135 sec) - iOS Apple-Iphone5-1_PT9701 got disconnected

2015-11-25T12:53:29.478Z (139 sec) - iOS Apple-Iphone5s-1_PT5807 got disconnected

2015-11-25T12:53:58.541Z (168 sec) - Android LGE-LG-D802_PT7336 got re-connected event

2015-11-25T12:54:41.135Z (211 sec) - Android LGE-LG-D802_PT7336 got disconnected

2015-11-25T12:54:44.047Z (214 sec) - Android samsung-SM-G800F_PT8819 got disconnected

2015-11-25T12:54:47.725Z (218 sec) - Android LGE-Nexus 5_PT7844 got disconnected

2015-11-25T12:54:48.672Z (219 sec) - Android HTC-HTC Desire 820_PT3971 got disconnected

2015-11-25T12:54:49.074Z (219 sec) - Android HTC-HTC Desire 820_PT6694 got disconnected

2015-11-25T12:55:14.420Z (244 sec) - Android LGE-LG-D722_PT9505 got disconnected

2015-11-25T12:55:33.255Z (263 sec) - Android LGE-Nexus 5_PT7844 got re-connected event

2015-11-25T12:55:34.099Z (264 sec) - Android samsung-SM-N910C_PT3817 got disconnected

2015-11-25T12:55:59.559Z (289 sec) - Android samsung-SM-A300FU_PT7895 got disconnected

2015-11-25T12:56:51.945Z (342 sec) - Android LGE-LG-D802_PT7336 got re-connected event

2015-11-25T12:56:55.273Z (345 sec) - Android LGE-Nexus 5_PT7844 got re-connected event

2015-11-25T12:57:22.574Z (372 sec) - Android LGE-Nexus 5_PT7844 got disconnected

2015-11-25T12:57:34.746Z (385 sec) - Android LGE-LG-D802_PT7336 got disconnected

2015-11-25T12:58:44.920Z (455 sec) - Android LGE-Nexus 5_PT7844 got disconnected

2015-11-25T12:59:02.550Z (472 sec) - Android HTC-HTC One_M8_PT2939 got re-connected event

2015-11-25T12:59:32.578Z (503 sec) - Android LGE-LG-D802_PT7336 got re-connected event

2015-11-25T12:59:41.467Z (511 sec) - Android LGE-LG-D802_PT7336 got disconnected

2015-11-25T13:00:15.300Z (545 sec) - Android HTC-HTC One_M8_PT2939 got disconnected

2015-11-25T13:01:07.551Z (597 sec) - Android samsung-SM-A500FU_PT3573 got disconnected

2015-11-25T13:02:08.758Z (659 sec) - Android HTC-HTC One_M8_PT2939 got re-connected event

2015-11-25T13:03:00.707Z (711 sec) - Android HTC-HTC One_M8_PT2939 got disconnected

2015-11-25T13:04:08.629Z (779 sec) - Android motorola-XT1039_PT9305 got disconnected

2015-11-25T13:04:19.281Z (789 sec) - Android motorola-XT1039_PT9305 got re-connected event

2015-11-25T13:06:48.254Z (938 sec) - Android LGE-LG-D855_PT4436 got disconnected

2015-11-25T13:06:49.471Z (939 sec) - Android LGE-LG-D855_PT4436 got re-connected event

2015-11-25T13:09:50.536Z (1120 sec) - Android LGE-LG-D855_PT4436 test took 1000357ms - results peers[0], reConnects[0], sendData[21]

2015-11-25T13:09:50.622Z (1121 sec) - Android motorola-XT1039_PT9305 test took 1000441ms - results peers[0], reConnects[0], sendData[21]

2015-11-25T13:09:50.634Z (1121 sec) - Android LGE-LG-H815_PT1856 test took 1000462ms - results peers[0], reConnects[0], sendData[21]

2015-11-25T13:09:50.686Z (1121 sec) - Android motorola-Nexus 6_PT2615 test took 1000498ms - results peers[0], reConnects[0], sendData[21]

2015-11-25T13:09:50.722Z (1121 sec) - Android HTC-HTC One_M8_PT2939 test took 1000540ms - results peers[0], reConnects[0], sendData[21]

2015-11-25T13:09:50.735Z (1121 sec) - Android samsung-SM-N9005_PT1333 test took 1000552ms - results peers[0], reConnects[0], sendData[21]

2015-11-25T13:09:50.801Z (1121 sec) - Android samsung-SM-A300FU_PT5188 test took 1000624ms - results peers[0], reConnects[0], sendData[21]

2015-11-25T13:09:51.098Z (1121 sec) - Android LGE-Nexus 5_PT1775 test took 1000921ms - results peers[0], reConnects[0], sendData[21]

2015-11-25T13:09:51.293Z (1121 sec) - Android samsung-SM-A500FU_PT2993 test took 1001105ms - results peers[0], reConnects[0], sendData[21]

2015-11-25T13:09:52.289Z (1122 sec) - Android samsung-SM-G900F_PT3994 test took 1002100ms - results peers[0], reConnects[0], sendData[21]

2015-11-25T13:09:52.720Z (1123 sec) - Android samsung-SM-G900F_PT4845 test took 1002538ms - results peers[0], reConnects[0], sendData[21]

2015-11-25T13:09:53.830Z (1124 sec) - Android motorola-XT1072_PT1876 test took 1003640ms - results peers[0], reConnects[0], sendData[21]

2015-11-25T13:09:56.430Z (1126 sec) - Android HUAWEI-ALE-L21_PT9922 test took 1006254ms - results peers[0], reConnects[0], sendData[21]

2015-11-25T13:09:59.303Z (1129 sec) - Android LGE-LG-D802_PT7336 test took 1009128ms - results peers[0], reConnects[0], sendData[21]

2015-11-25T13:13:10.194Z (1320 sec) - Server timeout reached!

2015-11-25T13:13:10.194Z (1320 sec) - Send timeout to samsung-SM-A500FU_PT3573

2015-11-25T13:13:10.195Z (1320 sec) - Send timeout to samsung-SM-N910C_PT3817
2015-11-25T13:13:10.196Z (1320 sec) - Send timeout to samsung-SM-G800F_PT8819

2015-11-25T13:13:10.197Z (1320 sec) - Send timeout to LGE-LG-D722_PT9505

2015-11-25T13:13:10.198Z (1320 sec) - Send timeout to samsung-SM-A300FU_PT7895
2015-11-25T13:13:10.199Z (1320 sec) - Send timeout to LGE-Nexus 5_PT7844

2015-11-25T13:13:10.200Z (1320 sec) - Send timeout to HTC-HTC Desire 820_PT6694

2015-11-25T13:13:10.201Z (1320 sec) - Send timeout to HTC-HTC Desire 820_PT3971

2015-11-25T13:14:10.206Z (1380 sec) - Did not get reports from all devices, but forcing tests to finish!

samsung-SM-A500FU_PT3573 did not have results at the end of tests - check the device logs about why!!

samsung-SM-N910C_PT3817 did not have results at the end of tests - check the device logs about why!!
samsung-SM-G800F_PT8819 did not have results at the end of tests - check the device logs about why!!
LGE-LG-D722_PT9505 did not have results at the end of tests - check the device logs about why!!

samsung-SM-A300FU_PT7895 did not have results at the end of tests - check the device logs about why!!

LGE-Nexus 5_PT7844 did not have results at the end of tests - check the device logs about why!!

HTC-HTC Desire 820_PT6694 did not have results at the end of tests - check the device logs about why!!

HTC-HTC Desire 820_PT3971 did not have results at the end of tests - check the device logs about why!!

2015-11-25T13:14:10.237Z (1380 sec) - Android All tests are done, preparing test report

--------------- test report ---------------------

--------------- LGE-LG-H815_PT1856 --------------------- : 1
sendList : 100% : 47495 ms, 99% : 47495 ms, 95 : 47495 ms, 90% : 46157 ms.
Average data rate: 0.004 MB/s
Result count 8, range 6118 ms to  47495 ms.
sendList failed peers count : 11 [57.89473684210526 %]
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
sendList never tried peers count : 2 [9.523809523809524 %]
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : E0:DB:10:1F:C9:5E
--------------- LGE-LG-D802_PT7336 --------------------- : 2
sendList : 100% : 91081 ms, 99% : 91081 ms, 95 : 91081 ms, 90% : 62982 ms.
Average data rate: 0.003 MB/s
Result count 7, range 2845 ms to  91081 ms.
sendList failed peers count : 9 [56.25 %]
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 50:2E:6C:AC:21:50, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
sendList never tried peers count : 5 [23.80952380952381 %]
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : E0:DB:10:1F:C9:5E
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : 44:80:EB:7B:5A:05
--------------- HUAWEI-ALE-L21_PT9922 --------------------- : 3
sendList : 100% : 24241 ms, 99% : 24241 ms, 95 : 24241 ms, 90% : 24241 ms.
Average data rate: 0.004 MB/s
Result count 2, range 20968 ms to  24241 ms.
sendList failed peers count : 19 [90.47619047619048 %]
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 2
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1

- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 7C:F9:0E:51:18:22, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1

- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 50:2E:6C:AC:21:50, Tried : 1
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1

- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 2
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 2
sendList never tried peers count : 0 [0 %]

--------------- LGE-Nexus 5_PT1775 --------------------- : 4
sendList : 100% : 17538 ms, 99% : 17538 ms, 95 : 11397 ms, 90% : 11397 ms.
Average data rate: 0.014 MB/s
Result count 11, range 1853 ms to  17538 ms.
sendList failed peers count : 10 [47.61904761904762 %]
- Peer ID : 80:01:84:8A:B3:68, Tried : 2
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 7C:F9:0E:51:18:22, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 2
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 2

sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-A300FU_PT5188 --------------------- : 5
sendList : 100% : 73452 ms, 99% : 73452 ms, 95 : 45272 ms, 90% : 45272 ms.
Average data rate: 0.006 MB/s

Result count 13, range 3667 ms to  73452 ms.
sendList failed peers count : 8 [38.095238095238095 %]
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 2

- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1

- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 2
- Peer ID : E0:DB:10:14:E2:C0, Tried : 2

sendList never tried peers count : 0 [0 %]
--------------- LGE-LG-D855_PT4436 --------------------- : 6
sendList : 100% : 59453 ms, 99% : 59453 ms, 95 : 48073 ms, 90% : 48073 ms.

Average data rate: 0.006 MB/s
Result count 13, range 2338 ms to  59453 ms.
sendList failed peers count : 8 [38.095238095238095 %]
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 2

- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 7C:F9:0E:51:18:22, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1

- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 2
- Peer ID : F8:95:C7:87:85:54, Tried : 2
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 2

sendList never tried peers count : 0 [0 %]
--------------- motorola-XT1039_PT9305 --------------------- : 7
sendList : 100% : 86914 ms, 99% : 86914 ms, 95 : 84869 ms, 90% : 84869 ms.

Average data rate: 0.003 MB/s
Result count 12, range 1965 ms to  86914 ms.
sendList failed peers count : 8 [40 %]

- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
sendList never tried peers count : 1 [4.761904761904762 %]
- Peer ID : 50:2E:6C:AC:21:50
--------------- HTC-HTC One_M8_PT2939 --------------------- : 8
sendList : 100% : 82488 ms, 99% : 82488 ms, 95 : 82488 ms, 90% : 65112 ms.
Average data rate: 0.003 MB/s
Result count 7, range 3968 ms to  82488 ms.
sendList failed peers count : 11 [61.111111111111114 %]
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
sendList never tried peers count : 3 [14.285714285714286 %]
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : F8:CF:C5:D9:E5:61
- Peer ID : 7C:F9:0E:51:18:22
--------------- samsung-SM-G900F_PT4845 --------------------- : 9
sendList : 100% : 77310 ms, 99% : 77310 ms, 95 : 40399 ms, 90% : 40399 ms.
Average data rate: 0.006 MB/s
Result count 14, range 3744 ms to  77310 ms.
sendList failed peers count : 7 [33.333333333333336 %]

- Peer ID : 34:FC:EF:9D:93:0B, Tried : 2
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 2
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 2
- Peer ID : 08:EC:A9:50:75:41, Tried : 2
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 2
- Peer ID : E0:DB:10:14:E2:C0, Tried : 2

sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-N9005_PT1333 --------------------- : 10
sendList : 100% : 72979 ms, 99% : 72979 ms, 95 : 72979 ms, 90% : 72979 ms.

Average data rate: 0.005 MB/s
Result count 5, range 2203 ms to  72979 ms.
sendList failed peers count : 10 [66.66666666666667 %]

- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1

- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1

- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
sendList never tried peers count : 6 [28.571428571428573 %]

- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 7C:F9:0E:51:18:22

- Peer ID : 50:2E:6C:AC:21:50
- Peer ID : F8:CF:C5:D9:E5:61
- Peer ID : 7C:F9:0E:34:8A:A0
--------------- motorola-Nexus 6_PT2615 --------------------- : 11

sendList : 100% : 79711 ms, 99% : 79711 ms, 95 : 55951 ms, 90% : 55951 ms.
Average data rate: 0.005 MB/s

Result count 12, range 1818 ms to  79711 ms.
sendList failed peers count : 9 [42.857142857142854 %]
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 2
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1

- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1

- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 50:2E:6C:AC:21:50, Tried : 1

sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-A500FU_PT2993 --------------------- : 12
sendList : 100% : 122020 ms, 99% : 122020 ms, 95 : 122020 ms, 90% : 44933 ms.

Average data rate: 0.004 MB/s
Result count 10, range 2177 ms to  122020 ms.
sendList failed peers count : 11 [52.38095238095238 %]

- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 2
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1

- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1

- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
sendList never tried peers count : 0 [0 %]

--------------- samsung-SM-G900F_PT3994 --------------------- : 13
sendList : 100% : 71037 ms, 99% : 71037 ms, 95 : 69110 ms, 90% : 69110 ms.

Average data rate: 0.004 MB/s
Result count 12, range 3237 ms to  71037 ms.
sendList failed peers count : 9 [42.857142857142854 %]
- Peer ID : E0:DB:10:14:E2:C0, Tried : 2

- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1

- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 7C:F9:0E:51:18:22, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 2

- Peer ID : 58:2A:F7:ED:96:BE, Tried : 2
sendList never tried peers count : 0 [0 %]
--------------- motorola-XT1072_PT1876 --------------------- : 14
sendList : 100% : 70043 ms, 99% : 70043 ms, 95 : 61505 ms, 90% : 61505 ms.
Average data rate: 0.004 MB/s
Result count 13, range 2874 ms to  70043 ms.
sendList failed peers count : 8 [38.095238095238095 %]
- Peer ID : E0:DB:10:14:E2:C0, Tried : 2
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 7C:F9:0E:51:18:22, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------
sendList : 100% : 122020 ms, 99% : 91081 ms, 95 : 77310 ms, 90% : 62982 ms.
Average data rate: 0.004 MB/s
--------------- end of test report ---------------------

2015-11-25T13:14:10.598Z (1381 sec) - Android motorola-Nexus 6_PT2615 got disconnected

2015-11-25T13:14:10.719Z (1381 sec) - Android samsung-SM-N9005_PT1333 got disconnected

2015-11-25T13:14:10.726Z (1381 sec) - Android HTC-HTC One_M8_PT2939 got disconnected

2015-11-25T13:14:10.764Z (1381 sec) - Android samsung-SM-G900F_PT4845 got disconnected

2015-11-25T13:14:10.770Z (1381 sec) - Android LGE-LG-D802_PT7336 got disconnected

2015-11-25T13:14:10.898Z (1381 sec) - Android samsung-SM-A500FU_PT2993 got disconnected

2015-11-25T13:14:11.061Z (1381 sec) - Android samsung-SM-G900F_PT3994 got disconnected

2015-11-25T13:14:11.106Z (1381 sec) - Android LGE-Nexus 5_PT1775 got disconnected

2015-11-25T13:14:11.138Z (1381 sec) - Android motorola-XT1072_PT1876 got disconnected

2015-11-25T13:14:11.371Z (1381 sec) - Android HUAWEI-ALE-L21_PT9922 got disconnected

2015-11-25T13:14:11.534Z (1381 sec) - Android LGE-LG-H815_PT1856 got disconnected

2015-11-25T13:14:18.018Z (1388 sec) - Android LGE-LG-D855_PT4436 got disconnected

2015-11-25T13:15:26.598Z (1457 sec) - Android samsung-SM-A300FU_PT5188 got disconnected

2015-11-25T13:15:30.022Z (1460 sec) - Android motorola-XT1039_PT9305 got disconnected


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```
###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  f56ad48d Test has  SUCCEEDED
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
STOP log received from  W3D7N15428022572 Test has  SUCCEEDED
Device test finished on f56ad48d 
Device test finished on LGH8153b36be34 
Device test finished on W3D7N15428022572 
Android task is completed. [SUCCESS]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/51335028c93db41_Work_in_progress__vjrantal/thali01_LGE-LG-H815.md)

[HUAWEI-ALE-L21](https://github.com/ThaliTester/TestResults/blob/51335028c93db41_Work_in_progress__vjrantal/thali01_HUAWEI-ALE-L21.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/51335028c93db41_Work_in_progress__vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/51335028c93db41_Work_in_progress__vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/51335028c93db41_Work_in_progress__vjrantal/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
STOP log received from  TA4750HV7I Test has  SUCCEEDED
Device test finished on TA4750HV7I 
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:null 
child process exited with code null on device 320414cd475f91e3 
Android task is completed. [FAILED]
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/51335028c93db41_Work_in_progress__vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/51335028c93db41_Work_in_progress__vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/51335028c93db41_Work_in_progress__vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
STOP log received from  0be0c6c6 Test has  SUCCEEDED
Device test finished on ZX1C223JKW 
Device test finished on 0be0c6c6 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/51335028c93db41_Work_in_progress__vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/51335028c93db41_Work_in_progress__vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/51335028c93db41_Work_in_progress__vjrantal/thali04_samsung-SM-G900F.md)

####Node name: thali05
Console output:
```
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
STOP log received from  1d6a772d Test has  SUCCEEDED
STOP log received from  SH47FWM00508 Test has  SUCCEEDED
Device test finished on 1d6a772d 
Device test finished on SH47FWM00508 
Device test finished on ZX1G429CRK 
Android task is completed. [SUCCESS]
```
[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/51335028c93db41_Work_in_progress__vjrantal/thali05_samsung-SM-N9005.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/51335028c93db41_Work_in_progress__vjrantal/thali05_motorola-Nexus 6.md)

[HTC-HTC One_M8](https://github.com/ThaliTester/TestResults/blob/51335028c93db41_Work_in_progress__vjrantal/thali05_HTC-HTC One_M8.md)

####Node name: thali06
Console output:
```
STOP log received from  022678fb504e29b0 Test has  SUCCEEDED
Device test finished on 022678fb504e29b0 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:0 
child process exited with code 0 on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:null 
child process exited with code null on device FA55PYS00566 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/51335028c93db41_Work_in_progress__vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/51335028c93db41_Work_in_progress__vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/51335028c93db41_Work_in_progress__vjrantal/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/51335028c93db41_Work_in_progress__vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/51335028c93db41_Work_in_progress__vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
STOP log received from  4325e43f Test has  SUCCEEDED
Device test finished on 4325e43f 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device HT574YC04723 app:com.test.thalitest code:0 
child process exited with code 0 on device HT574YC04723 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/51335028c93db41_Work_in_progress__vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/51335028c93db41_Work_in_progress__vjrantal/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/51335028c93db41_Work_in_progress__vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/51335028c93db41_Work_in_progress__vjrantal/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/51335028c93db41_Work_in_progress__vjrantal/iOS_Iphone5-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/51335028c93db41_Work_in_progress__vjrantal/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/51335028c93db41_Work_in_progress__vjrantal/iOS_Iphone6-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/51335028c93db41_Work_in_progress__vjrantal/iOS_IpadAir2-1.md)


#### Integration Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":23}}
Test ID 0 configuration: testSendData.js, server timeout: 1200000, data:

{ timeout: 1000000,
  rounds: 1,
  dataTimeout: 10000,
  dataAmount: 100000,
  conReTryTimeout: 5000,
  conReTryCount: 5 }

2015-11-25T12:51:10.114Z (0 sec) - Android tests will start after waiting for 120 seconds

Test ID 0 configuration: testSendData.js, server timeout: 1200000, data:

{ timeout: 1000000,
  rounds: 1,
  dataTimeout: 10000,
  dataAmount: 100000,
  conReTryTimeout: 5000,
  conReTryCount: 5 }

2015-11-25T12:51:10.120Z (0 sec) - iOS tests will start after waiting for 120 seconds

listening on *:3000

2015-11-25T12:51:10.602Z (1 sec) - Android LGE-LG-H815_PT1856 added (current device count 1)

2015-11-25T12:51:10.674Z (1 sec) - iOS Apple-Iphone5s-1_PT5807 added (current device count 1)

2015-11-25T12:51:10.888Z (1 sec) - Android LGE-LG-D802_PT7336 added (current device count 2)

2015-11-25T12:51:11.016Z (1 sec) - Android HUAWEI-ALE-L21_PT9922 added (current device count 3)

2015-11-25T12:51:11.336Z (1 sec) - Android LGE-Nexus 5_PT1775 added (current device count 4)

2015-11-25T12:51:11.506Z (1 sec) - Android samsung-SM-A300FU_PT5188 added (current device count 5)

2015-11-25T12:51:11.553Z (1 sec) - Android LGE-LG-D855_PT4436 added (current device count 6)

2015-11-25T12:51:11.889Z (2 sec) - Android samsung-SM-A500FU_PT3573 added (current device count 7)

2015-11-25T12:51:11.907Z (2 sec) - Android motorola-XT1039_PT9305 added (current device count 8)

2015-11-25T12:51:12.049Z (2 sec) - Android HTC-HTC One_M8_PT2939 added (current device count 9)

2015-11-25T12:51:12.434Z (2 sec) - iOS Apple-IpadAir2-1_PT7357 added (current device count 2)

2015-11-25T12:51:12.450Z (2 sec) - Android samsung-SM-G900F_PT4845 added (current device count 10)

2015-11-25T12:51:12.721Z (3 sec) - Android samsung-SM-N9005_PT1333 added (current device count 11)

2015-11-25T12:51:12.768Z (3 sec) - iOS Apple-Iphone6-1_PT8750 added (current device count 3)

2015-11-25T12:51:13.170Z (3 sec) - Android samsung-SM-N910C_PT3817 added (current device count 12)

2015-11-25T12:51:13.307Z (3 sec) - iOS Apple-Iphone5-1_PT9701 added (current device count 4)

2015-11-25T12:51:13.884Z (4 sec) - Android samsung-SM-G800F_PT8819 added (current device count 13)

2015-11-25T12:51:14.088Z (4 sec) - Android LGE-LG-D722_PT9505 added (current device count 14)

2015-11-25T12:51:14.200Z (4 sec) - Android samsung-SM-A300FU_PT7895 added (current device count 15)

2015-11-25T12:51:14.496Z (4 sec) - Android LGE-Nexus 5_PT7844 added (current device count 16)

2015-11-25T12:51:14.537Z (4 sec) - Android motorola-Nexus 6_PT2615 added (current device count 17)

2015-11-25T12:51:14.698Z (5 sec) - Android HTC-HTC Desire 820_PT6694 added (current device count 18)

2015-11-25T12:51:14.895Z (5 sec) - Android samsung-SM-A500FU_PT2993 added (current device count 19)

2015-11-25T12:51:14.928Z (5 sec) - Android HTC-HTC Desire 820_PT3971 added (current device count 20)

2015-11-25T12:51:14.945Z (5 sec) - Android samsung-SM-G900F_PT3994 added (current device count 21)

2015-11-25T12:51:20.593Z (11 sec) - Android motorola-XT1072_PT1876 added (current device count 22)

-------------- We got wait done, now starting the testing process ------------------

2015-11-25T12:53:10.167Z (120 sec) - Android start testing now with 22 devices

2015-11-25T12:53:10.195Z (120 sec) - iOS start testing now with 4 devices

2015-11-25T12:53:20.416Z (130 sec) - iOS Apple-Iphone6-1_PT8750 test took 10219ms - results peers[0], reConnects[0], sendData[3]

2015-11-25T12:53:22.112Z (132 sec) - iOS Apple-Iphone5s-1_PT5807 test took 11915ms - results peers[0], reConnects[0], sendData[3]

2015-11-25T12:53:23.898Z (134 sec) - iOS Apple-IpadAir2-1_PT7357 test took 13702ms - results peers[0], reConnects[0], sendData[3]

2015-11-25T12:53:24.086Z (134 sec) - iOS Apple-Iphone5-1_PT9701 test took 13889ms - results peers[0], reConnects[0], sendData[3]

2015-11-25T12:53:24.087Z (134 sec) - iOS test ID 0 done now

2015-11-25T12:53:24.096Z (134 sec) - iOS All tests are done, preparing test report

--------------- test report ---------------------

--------------- Apple-Iphone5s-1_PT5807 --------------------- : 1

sendList : 100% : 4699 ms, 99% : 4699 ms, 95 : 4699 ms, 90% : 4699 ms.

Average data rate: 0.028 MB/s

Result count 3, range 2813 ms to  4699 ms.

sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- Apple-IpadAir2-1_PT7357 --------------------- : 2

sendList : 100% : 4670 ms, 99% : 4670 ms, 95 : 4670 ms, 90% : 4670 ms.
Average data rate: 0.024 MB/s
Result count 3, range 3819 ms to  4670 ms.
sendList failed peers count : 0 [0 %]

sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1_PT8750 --------------------- : 3
sendList : 100% : 3276 ms, 99% : 3276 ms, 95 : 3276 ms, 90% : 3276 ms.

Average data rate: 0.033 MB/s
Result count 3, range 2922 ms to  3276 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5-1_PT9701 --------------------- : 4

sendList : 100% : 6797 ms, 99% : 6797 ms, 95 : 6797 ms, 90% : 6797 ms.

Average data rate: 0.023 MB/s
Result count 3, range 2674 ms to  6797 ms.

sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------

sendList : 100% : 6797 ms, 99% : 6797 ms, 95 : 4699 ms, 90% : 4699 ms.

Average data rate: 0.026 MB/s
--------------- end of test report ---------------------

2015-11-25T12:53:24.418Z (134 sec) - iOS Apple-Iphone6-1_PT8750 got disconnected

2015-11-25T12:53:24.954Z (135 sec) - iOS Apple-IpadAir2-1_PT7357 got disconnected

2015-11-25T12:53:25.169Z (135 sec) - iOS Apple-Iphone5-1_PT9701 got disconnected

2015-11-25T12:53:29.478Z (139 sec) - iOS Apple-Iphone5s-1_PT5807 got disconnected

2015-11-25T12:53:58.541Z (168 sec) - Android LGE-LG-D802_PT7336 got re-connected event

2015-11-25T12:54:41.135Z (211 sec) - Android LGE-LG-D802_PT7336 got disconnected

2015-11-25T12:54:44.047Z (214 sec) - Android samsung-SM-G800F_PT8819 got disconnected

2015-11-25T12:54:47.725Z (218 sec) - Android LGE-Nexus 5_PT7844 got disconnected

2015-11-25T12:54:48.672Z (219 sec) - Android HTC-HTC Desire 820_PT3971 got disconnected

2015-11-25T12:54:49.074Z (219 sec) - Android HTC-HTC Desire 820_PT6694 got disconnected

2015-11-25T12:55:14.420Z (244 sec) - Android LGE-LG-D722_PT9505 got disconnected

2015-11-25T12:55:33.255Z (263 sec) - Android LGE-Nexus 5_PT7844 got re-connected event

2015-11-25T12:55:34.099Z (264 sec) - Android samsung-SM-N910C_PT3817 got disconnected

2015-11-25T12:55:59.559Z (289 sec) - Android samsung-SM-A300FU_PT7895 got disconnected

2015-11-25T12:56:51.945Z (342 sec) - Android LGE-LG-D802_PT7336 got re-connected event

2015-11-25T12:56:55.273Z (345 sec) - Android LGE-Nexus 5_PT7844 got re-connected event

2015-11-25T12:57:22.574Z (372 sec) - Android LGE-Nexus 5_PT7844 got disconnected

2015-11-25T12:57:34.746Z (385 sec) - Android LGE-LG-D802_PT7336 got disconnected

2015-11-25T12:58:44.920Z (455 sec) - Android LGE-Nexus 5_PT7844 got disconnected

2015-11-25T12:59:02.550Z (472 sec) - Android HTC-HTC One_M8_PT2939 got re-connected event

2015-11-25T12:59:32.578Z (503 sec) - Android LGE-LG-D802_PT7336 got re-connected event

2015-11-25T12:59:41.467Z (511 sec) - Android LGE-LG-D802_PT7336 got disconnected

2015-11-25T13:00:15.300Z (545 sec) - Android HTC-HTC One_M8_PT2939 got disconnected

2015-11-25T13:01:07.551Z (597 sec) - Android samsung-SM-A500FU_PT3573 got disconnected

2015-11-25T13:02:08.758Z (659 sec) - Android HTC-HTC One_M8_PT2939 got re-connected event

2015-11-25T13:03:00.707Z (711 sec) - Android HTC-HTC One_M8_PT2939 got disconnected

2015-11-25T13:04:08.629Z (779 sec) - Android motorola-XT1039_PT9305 got disconnected

2015-11-25T13:04:19.281Z (789 sec) - Android motorola-XT1039_PT9305 got re-connected event

2015-11-25T13:06:48.254Z (938 sec) - Android LGE-LG-D855_PT4436 got disconnected

2015-11-25T13:06:49.471Z (939 sec) - Android LGE-LG-D855_PT4436 got re-connected event

2015-11-25T13:09:50.536Z (1120 sec) - Android LGE-LG-D855_PT4436 test took 1000357ms - results peers[0], reConnects[0], sendData[21]

2015-11-25T13:09:50.622Z (1121 sec) - Android motorola-XT1039_PT9305 test took 1000441ms - results peers[0], reConnects[0], sendData[21]

2015-11-25T13:09:50.634Z (1121 sec) - Android LGE-LG-H815_PT1856 test took 1000462ms - results peers[0], reConnects[0], sendData[21]

2015-11-25T13:09:50.686Z (1121 sec) - Android motorola-Nexus 6_PT2615 test took 1000498ms - results peers[0], reConnects[0], sendData[21]

2015-11-25T13:09:50.722Z (1121 sec) - Android HTC-HTC One_M8_PT2939 test took 1000540ms - results peers[0], reConnects[0], sendData[21]

2015-11-25T13:09:50.735Z (1121 sec) - Android samsung-SM-N9005_PT1333 test took 1000552ms - results peers[0], reConnects[0], sendData[21]

2015-11-25T13:09:50.801Z (1121 sec) - Android samsung-SM-A300FU_PT5188 test took 1000624ms - results peers[0], reConnects[0], sendData[21]

2015-11-25T13:09:51.098Z (1121 sec) - Android LGE-Nexus 5_PT1775 test took 1000921ms - results peers[0], reConnects[0], sendData[21]

2015-11-25T13:09:51.293Z (1121 sec) - Android samsung-SM-A500FU_PT2993 test took 1001105ms - results peers[0], reConnects[0], sendData[21]

2015-11-25T13:09:52.289Z (1122 sec) - Android samsung-SM-G900F_PT3994 test took 1002100ms - results peers[0], reConnects[0], sendData[21]

2015-11-25T13:09:52.720Z (1123 sec) - Android samsung-SM-G900F_PT4845 test took 1002538ms - results peers[0], reConnects[0], sendData[21]

2015-11-25T13:09:53.830Z (1124 sec) - Android motorola-XT1072_PT1876 test took 1003640ms - results peers[0], reConnects[0], sendData[21]

2015-11-25T13:09:56.430Z (1126 sec) - Android HUAWEI-ALE-L21_PT9922 test took 1006254ms - results peers[0], reConnects[0], sendData[21]

2015-11-25T13:09:59.303Z (1129 sec) - Android LGE-LG-D802_PT7336 test took 1009128ms - results peers[0], reConnects[0], sendData[21]

2015-11-25T13:13:10.194Z (1320 sec) - Server timeout reached!

2015-11-25T13:13:10.194Z (1320 sec) - Send timeout to samsung-SM-A500FU_PT3573

2015-11-25T13:13:10.195Z (1320 sec) - Send timeout to samsung-SM-N910C_PT3817
2015-11-25T13:13:10.196Z (1320 sec) - Send timeout to samsung-SM-G800F_PT8819

2015-11-25T13:13:10.197Z (1320 sec) - Send timeout to LGE-LG-D722_PT9505

2015-11-25T13:13:10.198Z (1320 sec) - Send timeout to samsung-SM-A300FU_PT7895
2015-11-25T13:13:10.199Z (1320 sec) - Send timeout to LGE-Nexus 5_PT7844

2015-11-25T13:13:10.200Z (1320 sec) - Send timeout to HTC-HTC Desire 820_PT6694

2015-11-25T13:13:10.201Z (1320 sec) - Send timeout to HTC-HTC Desire 820_PT3971

2015-11-25T13:14:10.206Z (1380 sec) - Did not get reports from all devices, but forcing tests to finish!

samsung-SM-A500FU_PT3573 did not have results at the end of tests - check the device logs about why!!

samsung-SM-N910C_PT3817 did not have results at the end of tests - check the device logs about why!!
samsung-SM-G800F_PT8819 did not have results at the end of tests - check the device logs about why!!
LGE-LG-D722_PT9505 did not have results at the end of tests - check the device logs about why!!

samsung-SM-A300FU_PT7895 did not have results at the end of tests - check the device logs about why!!

LGE-Nexus 5_PT7844 did not have results at the end of tests - check the device logs about why!!

HTC-HTC Desire 820_PT6694 did not have results at the end of tests - check the device logs about why!!

HTC-HTC Desire 820_PT3971 did not have results at the end of tests - check the device logs about why!!

2015-11-25T13:14:10.237Z (1380 sec) - Android All tests are done, preparing test report

--------------- test report ---------------------

--------------- LGE-LG-H815_PT1856 --------------------- : 1
sendList : 100% : 47495 ms, 99% : 47495 ms, 95 : 47495 ms, 90% : 46157 ms.
Average data rate: 0.004 MB/s
Result count 8, range 6118 ms to  47495 ms.
sendList failed peers count : 11 [57.89473684210526 %]
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
sendList never tried peers count : 2 [9.523809523809524 %]
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : E0:DB:10:1F:C9:5E
--------------- LGE-LG-D802_PT7336 --------------------- : 2
sendList : 100% : 91081 ms, 99% : 91081 ms, 95 : 91081 ms, 90% : 62982 ms.
Average data rate: 0.003 MB/s
Result count 7, range 2845 ms to  91081 ms.
sendList failed peers count : 9 [56.25 %]
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 50:2E:6C:AC:21:50, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
sendList never tried peers count : 5 [23.80952380952381 %]
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : E0:DB:10:1F:C9:5E
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : 44:80:EB:7B:5A:05
--------------- HUAWEI-ALE-L21_PT9922 --------------------- : 3
sendList : 100% : 24241 ms, 99% : 24241 ms, 95 : 24241 ms, 90% : 24241 ms.
Average data rate: 0.004 MB/s
Result count 2, range 20968 ms to  24241 ms.
sendList failed peers count : 19 [90.47619047619048 %]
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 2
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1

- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 7C:F9:0E:51:18:22, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1

- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 50:2E:6C:AC:21:50, Tried : 1
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1

- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 2
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 2
sendList never tried peers count : 0 [0 %]

--------------- LGE-Nexus 5_PT1775 --------------------- : 4
sendList : 100% : 17538 ms, 99% : 17538 ms, 95 : 11397 ms, 90% : 11397 ms.
Average data rate: 0.014 MB/s
Result count 11, range 1853 ms to  17538 ms.
sendList failed peers count : 10 [47.61904761904762 %]
- Peer ID : 80:01:84:8A:B3:68, Tried : 2
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 7C:F9:0E:51:18:22, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 2
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 2

sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-A300FU_PT5188 --------------------- : 5
sendList : 100% : 73452 ms, 99% : 73452 ms, 95 : 45272 ms, 90% : 45272 ms.
Average data rate: 0.006 MB/s

Result count 13, range 3667 ms to  73452 ms.
sendList failed peers count : 8 [38.095238095238095 %]
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 2

- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1

- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 2
- Peer ID : E0:DB:10:14:E2:C0, Tried : 2

sendList never tried peers count : 0 [0 %]
--------------- LGE-LG-D855_PT4436 --------------------- : 6
sendList : 100% : 59453 ms, 99% : 59453 ms, 95 : 48073 ms, 90% : 48073 ms.

Average data rate: 0.006 MB/s
Result count 13, range 2338 ms to  59453 ms.
sendList failed peers count : 8 [38.095238095238095 %]
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 2

- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 7C:F9:0E:51:18:22, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1

- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 2
- Peer ID : F8:95:C7:87:85:54, Tried : 2
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 2

sendList never tried peers count : 0 [0 %]
--------------- motorola-XT1039_PT9305 --------------------- : 7
sendList : 100% : 86914 ms, 99% : 86914 ms, 95 : 84869 ms, 90% : 84869 ms.

Average data rate: 0.003 MB/s
Result count 12, range 1965 ms to  86914 ms.
sendList failed peers count : 8 [40 %]

- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
sendList never tried peers count : 1 [4.761904761904762 %]
- Peer ID : 50:2E:6C:AC:21:50
--------------- HTC-HTC One_M8_PT2939 --------------------- : 8
sendList : 100% : 82488 ms, 99% : 82488 ms, 95 : 82488 ms, 90% : 65112 ms.
Average data rate: 0.003 MB/s
Result count 7, range 3968 ms to  82488 ms.
sendList failed peers count : 11 [61.111111111111114 %]
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
sendList never tried peers count : 3 [14.285714285714286 %]
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : F8:CF:C5:D9:E5:61
- Peer ID : 7C:F9:0E:51:18:22
--------------- samsung-SM-G900F_PT4845 --------------------- : 9
sendList : 100% : 77310 ms, 99% : 77310 ms, 95 : 40399 ms, 90% : 40399 ms.
Average data rate: 0.006 MB/s
Result count 14, range 3744 ms to  77310 ms.
sendList failed peers count : 7 [33.333333333333336 %]

- Peer ID : 34:FC:EF:9D:93:0B, Tried : 2
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 2
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 2
- Peer ID : 08:EC:A9:50:75:41, Tried : 2
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 2
- Peer ID : E0:DB:10:14:E2:C0, Tried : 2

sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-N9005_PT1333 --------------------- : 10
sendList : 100% : 72979 ms, 99% : 72979 ms, 95 : 72979 ms, 90% : 72979 ms.

Average data rate: 0.005 MB/s
Result count 5, range 2203 ms to  72979 ms.
sendList failed peers count : 10 [66.66666666666667 %]

- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1

- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1

- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
sendList never tried peers count : 6 [28.571428571428573 %]

- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 7C:F9:0E:51:18:22

- Peer ID : 50:2E:6C:AC:21:50
- Peer ID : F8:CF:C5:D9:E5:61
- Peer ID : 7C:F9:0E:34:8A:A0
--------------- motorola-Nexus 6_PT2615 --------------------- : 11

sendList : 100% : 79711 ms, 99% : 79711 ms, 95 : 55951 ms, 90% : 55951 ms.
Average data rate: 0.005 MB/s

Result count 12, range 1818 ms to  79711 ms.
sendList failed peers count : 9 [42.857142857142854 %]
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 2
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1

- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1

- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 50:2E:6C:AC:21:50, Tried : 1

sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-A500FU_PT2993 --------------------- : 12
sendList : 100% : 122020 ms, 99% : 122020 ms, 95 : 122020 ms, 90% : 44933 ms.

Average data rate: 0.004 MB/s
Result count 10, range 2177 ms to  122020 ms.
sendList failed peers count : 11 [52.38095238095238 %]

- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 2
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1

- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1

- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
sendList never tried peers count : 0 [0 %]

--------------- samsung-SM-G900F_PT3994 --------------------- : 13
sendList : 100% : 71037 ms, 99% : 71037 ms, 95 : 69110 ms, 90% : 69110 ms.

Average data rate: 0.004 MB/s
Result count 12, range 3237 ms to  71037 ms.
sendList failed peers count : 9 [42.857142857142854 %]
- Peer ID : E0:DB:10:14:E2:C0, Tried : 2

- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1

- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 7C:F9:0E:51:18:22, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 2

- Peer ID : 58:2A:F7:ED:96:BE, Tried : 2
sendList never tried peers count : 0 [0 %]
--------------- motorola-XT1072_PT1876 --------------------- : 14
sendList : 100% : 70043 ms, 99% : 70043 ms, 95 : 61505 ms, 90% : 61505 ms.
Average data rate: 0.004 MB/s
Result count 13, range 2874 ms to  70043 ms.
sendList failed peers count : 8 [38.095238095238095 %]
- Peer ID : E0:DB:10:14:E2:C0, Tried : 2
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 7C:F9:0E:51:18:22, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------
sendList : 100% : 122020 ms, 99% : 91081 ms, 95 : 77310 ms, 90% : 62982 ms.
Average data rate: 0.004 MB/s
--------------- end of test report ---------------------

2015-11-25T13:14:10.598Z (1381 sec) - Android motorola-Nexus 6_PT2615 got disconnected

2015-11-25T13:14:10.719Z (1381 sec) - Android samsung-SM-N9005_PT1333 got disconnected

2015-11-25T13:14:10.726Z (1381 sec) - Android HTC-HTC One_M8_PT2939 got disconnected

2015-11-25T13:14:10.764Z (1381 sec) - Android samsung-SM-G900F_PT4845 got disconnected

2015-11-25T13:14:10.770Z (1381 sec) - Android LGE-LG-D802_PT7336 got disconnected

2015-11-25T13:14:10.898Z (1381 sec) - Android samsung-SM-A500FU_PT2993 got disconnected

2015-11-25T13:14:11.061Z (1381 sec) - Android samsung-SM-G900F_PT3994 got disconnected

2015-11-25T13:14:11.106Z (1381 sec) - Android LGE-Nexus 5_PT1775 got disconnected

2015-11-25T13:14:11.138Z (1381 sec) - Android motorola-XT1072_PT1876 got disconnected

2015-11-25T13:14:11.371Z (1381 sec) - Android HUAWEI-ALE-L21_PT9922 got disconnected

2015-11-25T13:14:11.534Z (1381 sec) - Android LGE-LG-H815_PT1856 got disconnected

2015-11-25T13:14:18.018Z (1388 sec) - Android LGE-LG-D855_PT4436 got disconnected

2015-11-25T13:15:26.598Z (1457 sec) - Android samsung-SM-A300FU_PT5188 got disconnected

2015-11-25T13:15:30.022Z (1460 sec) - Android motorola-XT1039_PT9305 got disconnected


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


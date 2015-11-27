#### Test 51986340bb0815b Logs

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

2015-11-27T12:14:20.338Z (0 sec) - Android tests will start after waiting for 120 seconds

Test ID 0 configuration: testSendData.js, server timeout: 1200000, data:

{ timeout: 1000000,
  rounds: 1,
  dataTimeout: 10000,
  dataAmount: 100000,
  conReTryTimeout: 5000,
  conReTryCount: 5 }

2015-11-27T12:14:20.344Z (0 sec) - iOS tests will start after waiting for 120 seconds

listening on *:3000

2015-11-27T12:14:20.907Z (1 sec) - Android LGE-LG-H815_PT1997 added (current device count 1)

2015-11-27T12:14:20.925Z (1 sec) - Android HTC-HTC Desire 820_PT603 added (current device count 2)

2015-11-27T12:14:20.986Z (1 sec) - Android samsung-SM-N9005_PT4232 added (current device count 3)

2015-11-27T12:14:20.996Z (1 sec) - iOS Apple-Iphone5s-1_PT8509 added (current device count 1)

2015-11-27T12:14:21.757Z (1 sec) - Android LGE-LG-D802_PT7474 added (current device count 4)

2015-11-27T12:14:22.342Z (2 sec) - Android LGE-LG-D722_PT9286 added (current device count 5)

2015-11-27T12:14:22.384Z (2 sec) - Android HTC-HTC Desire 820_PT8519 added (current device count 6)

2015-11-27T12:14:22.467Z (2 sec) - iOS Apple-Iphone5-1_PT1479 added (current device count 2)

2015-11-27T12:14:22.635Z (2 sec) - iOS Apple-Iphone6-1_PT6911 added (current device count 3)

2015-11-27T12:14:22.641Z (2 sec) - Android motorola-Nexus 6_PT9280 added (current device count 7)

2015-11-27T12:14:23.527Z (3 sec) - Android LGE-LG-D855_PT6524 added (current device count 8)

2015-11-27T12:14:23.621Z (3 sec) - Android samsung-SM-A300FU_PT1809 added (current device count 9)

2015-11-27T12:14:23.673Z (3 sec) - Android samsung-SM-G800F_PT3153 added (current device count 10)

2015-11-27T12:14:23.750Z (3 sec) - iOS Apple-IpadAir2-1_PT3767 added (current device count 4)

2015-11-27T12:14:24.582Z (4 sec) - Android LGE-Nexus 5_PT6174 added (current device count 11)

2015-11-27T12:14:24.719Z (4 sec) - Android samsung-SM-A300FU_PT4975 added (current device count 12)

2015-11-27T12:14:24.810Z (5 sec) - Android motorola-XT1039_PT82 added (current device count 13)

2015-11-27T12:14:24.902Z (5 sec) - Android HUAWEI-ALE-L21_PT5942 added (current device count 14)

2015-11-27T12:14:25.055Z (5 sec) - Android HTC-HTC One_M8_PT8107 added (current device count 15)

2015-11-27T12:14:25.124Z (5 sec) - Android samsung-SM-G900F_PT6267 added (current device count 16)

2015-11-27T12:14:25.310Z (5 sec) - Android samsung-SM-G900F_PT3260 added (current device count 17)

2015-11-27T12:14:25.321Z (5 sec) - Android LGE-Nexus 5_PT227 added (current device count 18)

2015-11-27T12:14:25.501Z (5 sec) - Android samsung-SM-A500FU_PT5912 added (current device count 19)

2015-11-27T12:14:28.892Z (9 sec) - Android samsung-SM-N910C_PT8283 added (current device count 20)

2015-11-27T12:14:29.763Z (9 sec) - Android motorola-XT1072_PT8734 added (current device count 21)

-------------- We got wait done, now starting the testing process ------------------

2015-11-27T12:16:20.387Z (120 sec) - Android start testing now with 21 devices

2015-11-27T12:16:20.415Z (120 sec) - iOS start testing now with 4 devices

2015-11-27T12:16:32.954Z (133 sec) - iOS Apple-IpadAir2-1_PT3767 test took 12537ms - results peers[0], reConnects[0], sendData[3]

2015-11-27T12:17:27.237Z (187 sec) - Android LGE-Nexus 5_PT6174 got re-connected event

2015-11-27T12:17:55.029Z (215 sec) - Android LGE-Nexus 5_PT6174 got disconnected

2015-11-27T12:18:11.569Z (231 sec) - iOS Apple-Iphone5s-1_PT8509 test took 111153ms - results peers[0], reConnects[0], sendData[3]

2015-11-27T12:18:16.144Z (236 sec) - iOS Apple-Iphone6-1_PT6911 test took 115727ms - results peers[0], reConnects[0], sendData[3]

2015-11-27T12:19:17.260Z (297 sec) - Android LGE-Nexus 5_PT6174 got disconnected

2015-11-27T12:19:56.787Z (336 sec) - iOS Apple-Iphone5-1_PT1479 test took 216371ms - results peers[0], reConnects[0], sendData[3]

2015-11-27T12:19:56.788Z (336 sec) - iOS test ID 0 done now

2015-11-27T12:19:56.796Z (336 sec) - iOS All tests are done, preparing test report

--------------- test report ---------------------

--------------- Apple-Iphone5s-1_PT8509 --------------------- : 1

sendList : 100% : 3967 ms, 99% : 3967 ms, 95 : 3967 ms, 90% : 3967 ms.

Average data rate: 0.028 MB/s

Result count 2, range 3294 ms to  3967 ms.

sendList failed peers count : 1 [33.333333333333336 %]

- Peer ID : Apple-Iphone5-1_PT1479.RH8WAQ==, Tried : 5

sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5-1_PT1479 --------------------- : 2

sendList : 100% : 5133 ms, 99% : 5133 ms, 95 : 5133 ms, 90% : 5133 ms.
Average data rate: 0.019 MB/s
Result count 1, range 5133 ms to  5133 ms.
sendList failed peers count : 2 [66.66666666666667 %]
- Peer ID : Apple-Iphone6-1_PT6911.ZjHo2g==, Tried : 5
- Peer ID : Apple-Iphone5s-1_PT8509.17j4Hw==, Tried : 5

sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1_PT6911 --------------------- : 3

sendList : 100% : 3661 ms, 99% : 3661 ms, 95 : 3661 ms, 90% : 3661 ms.
Average data rate: 0.029 MB/s
Result count 2, range 3248 ms to  3661 ms.
sendList failed peers count : 1 [33.333333333333336 %]

- Peer ID : Apple-IpadAir2-1_PT3767.CF0kqQ==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Apple-IpadAir2-1_PT3767 --------------------- : 4
sendList : 100% : 4084 ms, 99% : 4084 ms, 95 : 4084 ms, 90% : 4084 ms.
Average data rate: 0.028 MB/s
Result count 3, range 3256 ms to  4084 ms.

sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------

sendList : 100% : 5133 ms, 99% : 5133 ms, 95 : 5133 ms, 90% : 4084 ms.
Average data rate: 0.027 MB/s
--------------- end of test report ---------------------

2015-11-27T12:19:57.016Z (337 sec) - iOS Apple-Iphone6-1_PT6911 got disconnected

2015-11-27T12:19:57.446Z (337 sec) - iOS Apple-IpadAir2-1_PT3767 got disconnected

2015-11-27T12:19:57.517Z (337 sec) - iOS Apple-Iphone5s-1_PT8509 got disconnected

2015-11-27T12:20:04.458Z (344 sec) - Android samsung-SM-N910C_PT8283 got disconnected

2015-11-27T12:20:05.154Z (345 sec) - iOS Apple-Iphone5-1_PT1479 got disconnected

2015-11-27T12:20:28.044Z (368 sec) - Android LGE-LG-H815_PT1997 got re-connected event

2015-11-27T12:20:28.264Z (368 sec) - Android motorola-XT1039_PT82 got re-connected event

2015-11-27T12:21:14.884Z (415 sec) - Android LGE-LG-H815_PT1997 got disconnected

2015-11-27T12:21:15.761Z (415 sec) - Android samsung-SM-G800F_PT3153 got disconnected

2015-11-27T12:21:17.018Z (417 sec) - Android motorola-XT1039_PT82 got disconnected

2015-11-27T12:21:17.918Z (418 sec) - Android motorola-Nexus 6_PT9280 got re-connected event

2015-11-27T12:21:31.353Z (431 sec) - Android LGE-Nexus 5_PT6174 got re-connected event

2015-11-27T12:22:03.081Z (463 sec) - Android LGE-Nexus 5_PT6174 got re-connected event

2015-11-27T12:22:28.600Z (488 sec) - Android motorola-Nexus 6_PT9280 got disconnected

2015-11-27T12:22:56.365Z (516 sec) - Android LGE-Nexus 5_PT6174 got disconnected

2015-11-27T12:23:17.759Z (537 sec) - Android motorola-Nexus 6_PT9280 got re-connected event

2015-11-27T12:23:23.572Z (543 sec) - Android samsung-SM-A300FU_PT1809 got disconnected

2015-11-27T12:23:52.972Z (573 sec) - Android LGE-Nexus 5_PT6174 got disconnected

2015-11-27T12:24:23.053Z (603 sec) - Android motorola-Nexus 6_PT9280 got disconnected

2015-11-27T12:25:56.400Z (696 sec) - Android LGE-Nexus 5_PT6174 got re-connected event

2015-11-27T12:26:20.934Z (721 sec) - Android samsung-SM-A300FU_PT4975 got disconnected

2015-11-27T12:27:35.948Z (796 sec) - Android LGE-Nexus 5_PT6174 got re-connected event

2015-11-27T12:27:41.962Z (802 sec) - Android motorola-XT1039_PT82 got disconnected

2015-11-27T12:27:46.114Z (806 sec) - Android LGE-Nexus 5_PT6174 got disconnected

2015-11-27T12:28:29.452Z (849 sec) - Android LGE-Nexus 5_PT6174 got re-connected event

2015-11-27T12:28:30.473Z (850 sec) - Android HTC-HTC Desire 820_PT8519 got disconnected

2015-11-27T12:28:34.637Z (854 sec) - Android motorola-XT1072_PT8734 got disconnected

2015-11-27T12:28:54.821Z (875 sec) - Android HTC-HTC Desire 820_PT8519 got re-connected event

2015-11-27T12:29:00.949Z (881 sec) - Android LGE-Nexus 5_PT6174 got disconnected

2015-11-27T12:29:30.879Z (911 sec) - Android motorola-XT1072_PT8734 got re-connected event

2015-11-27T12:29:54.454Z (934 sec) - Android LGE-Nexus 5_PT6174 got disconnected

2015-11-27T12:30:10.433Z (950 sec) - Android motorola-XT1039_PT82 got re-connected event

2015-11-27T12:30:44.807Z (985 sec) - Android HTC-HTC Desire 820_PT8519 got disconnected

2015-11-27T12:31:16.945Z (1017 sec) - Android HTC-HTC Desire 820_PT8519 got re-connected event

2015-11-27T12:32:36.175Z (1096 sec) - Android LGE-LG-D802_PT7474 got disconnected

2015-11-27T12:32:41.948Z (1102 sec) - Android HTC-HTC Desire 820_PT8519 got disconnected

2015-11-27T12:33:00.820Z (1121 sec) - Android HTC-HTC One_M8_PT8107 test took 1000414ms - results peers[0], reConnects[0], sendData[20]

2015-11-27T12:33:00.874Z (1121 sec) - Android motorola-Nexus 6_PT9280 test took 1000475ms - results peers[0], reConnects[0], sendData[20]

2015-11-27T12:33:00.906Z (1121 sec) - Android samsung-SM-N9005_PT4232 test took 1000510ms - results peers[0], reConnects[0], sendData[20]

2015-11-27T12:33:00.993Z (1121 sec) - Android samsung-SM-G900F_PT6267 test took 1000586ms - results peers[0], reConnects[0], sendData[20]

2015-11-27T12:33:01.010Z (1121 sec) - Android samsung-SM-G900F_PT3260 test took 1000603ms - results peers[0], reConnects[0], sendData[20]

2015-11-27T12:33:01.048Z (1121 sec) - Android LGE-Nexus 5_PT227 test took 1000639ms - results peers[0], reConnects[0], sendData[20]

2015-11-27T12:33:01.135Z (1121 sec) - Android samsung-SM-A500FU_PT5912 test took 1000726ms - results peers[0], reConnects[0], sendData[20]

2015-11-27T12:33:01.357Z (1121 sec) - Android HUAWEI-ALE-L21_PT5942 test took 1000952ms - results peers[0], reConnects[0], sendData[20]

2015-11-27T12:33:01.478Z (1121 sec) - Android LGE-LG-H815_PT1997 test took 1001086ms - results peers[0], reConnects[0], sendData[20]

2015-11-27T12:33:02.610Z (1122 sec) - Android LGE-LG-D722_PT9286 test took 1002213ms - results peers[0], reConnects[0], sendData[20]

2015-11-27T12:33:02.676Z (1122 sec) - Android LGE-LG-D855_PT6524 test took 1002275ms - results peers[0], reConnects[0], sendData[20]

2015-11-27T12:33:03.081Z (1123 sec) - Android HTC-HTC Desire 820_PT603 test took 1002686ms - results peers[0], reConnects[0], sendData[20]

2015-11-27T12:33:06.419Z (1126 sec) - Android motorola-XT1072_PT8734 got disconnected

2015-11-27T12:33:20.205Z (1140 sec) - Android HTC-HTC Desire 820_PT8519 got re-connected event

2015-11-27T12:33:20.227Z (1140 sec) - Android HTC-HTC Desire 820_PT8519 test took 1019829ms - results peers[0], reConnects[0], sendData[20]

2015-11-27T12:33:41.535Z (1161 sec) - Android motorola-XT1039_PT82 got disconnected

2015-11-27T12:33:45.634Z (1165 sec) - Android LGE-LG-D802_PT7474 got re-connected event

2015-11-27T12:33:45.638Z (1165 sec) - Android LGE-LG-D802_PT7474 test took 1045241ms - results peers[0], reConnects[0], sendData[20]

2015-11-27T12:33:59.247Z (1179 sec) - Android motorola-XT1072_PT8734 got re-connected event

2015-11-27T12:33:59.281Z (1179 sec) - Android motorola-XT1072_PT8734 test took 1058871ms - results peers[0], reConnects[0], sendData[20]

2015-11-27T12:36:20.414Z (1320 sec) - Server timeout reached!

2015-11-27T12:36:20.415Z (1320 sec) - Send timeout to samsung-SM-A300FU_PT1809
2015-11-27T12:36:20.415Z (1320 sec) - Send timeout to samsung-SM-G800F_PT3153
2015-11-27T12:36:20.416Z (1320 sec) - Send timeout to LGE-Nexus 5_PT6174
2015-11-27T12:36:20.417Z (1320 sec) - Send timeout to samsung-SM-A300FU_PT4975
2015-11-27T12:36:20.418Z (1320 sec) - Send timeout to motorola-XT1039_PT82
2015-11-27T12:36:20.419Z (1320 sec) - Send timeout to samsung-SM-N910C_PT8283

2015-11-27T12:36:34.733Z (1334 sec) - Android motorola-Nexus 6_PT9280 got re-connected event

2015-11-27T12:36:48.829Z (1349 sec) - Android HTC-HTC One_M8_PT8107 got re-connected event

2015-11-27T12:37:20.421Z (1380 sec) - Did not get reports from all devices, but forcing tests to finish!

samsung-SM-A300FU_PT1809 did not have results at the end of tests - check the device logs about why!!

samsung-SM-G800F_PT3153 did not have results at the end of tests - check the device logs about why!!
LGE-Nexus 5_PT6174 did not have results at the end of tests - check the device logs about why!!
samsung-SM-A300FU_PT4975 did not have results at the end of tests - check the device logs about why!!
motorola-XT1039_PT82 did not have results at the end of tests - check the device logs about why!!

samsung-SM-N910C_PT8283 did not have results at the end of tests - check the device logs about why!!

2015-11-27T12:37:20.440Z (1380 sec) - Android All tests are done, preparing test report

--------------- test report ---------------------

--------------- LGE-LG-H815_PT1997 --------------------- : 1
sendList : 100% : 7454 ms, 99% : 7454 ms, 95 : 7454 ms, 90% : 7454 ms.
Average data rate: 0.013 MB/s

Result count 1, range 7454 ms to  7454 ms.
sendList failed peers count : 9 [90 %]
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1

- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1

- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : 50:2E:6C:AC:21:50, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
sendList never tried peers count : 10 [50 %]

- Peer ID : 7C:F9:0E:34:8A:A0

- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : E0:DB:10:1F:C9:5E
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : F8:95:C7:87:85:54

- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 58:2A:F7:ED:96:BE

--------------- HTC-HTC Desire 820_PT603 --------------------- : 2
sendList : 100% : 3161 ms, 99% : 3161 ms, 95 : 3161 ms, 90% : 3161 ms.
Average data rate: 0.032 MB/s
Result count 1, range 3161 ms to  3161 ms.
sendList failed peers count : 10 [90.9090909090909 %]
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 50:2E:6C:AC:21:50, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
sendList never tried peers count : 9 [45 %]
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : E0:DB:10:1F:C9:5E
- Peer ID : 58:2A:F7:ED:96:BE
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : F8:CF:C5:D9:E5:61
- Peer ID : B4:CE:F6:AB:A4:6A
--------------- samsung-SM-N9005_PT4232 --------------------- : 3
sendList : 100% : 18972 ms, 99% : 18972 ms, 95 : 18972 ms, 90% : 18972 ms.
Average data rate: 0.005 MB/s
Result count 1, range 18972 ms to  18972 ms.
sendList failed peers count : 10 [90.9090909090909 %]
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1

sendList never tried peers count : 9 [45 %]
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 58:3F:54:73:64:C0

- Peer ID : 50:2E:6C:AC:21:50
- Peer ID : 58:2A:F7:ED:96:BE
- Peer ID : 34:FC:EF:9D:93:0B
--------------- LGE-LG-D802_PT7474 --------------------- : 4

sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s

Results list does not contain any items
sendList failed peers count : 10 [100 %]
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1

- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1

- Peer ID : 50:2E:6C:AC:21:50, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1

- Peer ID : F8:95:C7:87:85:54, Tried : 1
sendList never tried peers count : 10 [50 %]
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : F8:95:C7:87:3C:51

- Peer ID : 58:2A:F7:ED:96:BE
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : F8:CF:C5:D9:E5:61
- Peer ID : 7C:F9:0E:34:8A:A0

- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : E0:DB:10:14:E2:C0

--------------- LGE-LG-D722_PT9286 --------------------- : 5
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s

Results list does not contain any items
sendList failed peers count : 9 [100 %]
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1

- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 50:2E:6C:AC:21:50, Tried : 1

- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1

- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
sendList never tried peers count : 11 [55 %]
- Peer ID : 7C:F9:0E:34:8A:A0

- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : 7C:F9:0E:37:96:AB

- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : E0:DB:10:14:E2:C0

- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 00:F4:6F:30:E0:6C
--------------- HTC-HTC Desire 820_PT8519 --------------------- : 6
sendList : 100% : 3859 ms, 99% : 3859 ms, 95 : 3859 ms, 90% : 3859 ms.

Average data rate: 0.026 MB/s
Result count 1, range 3859 ms to  3859 ms.
sendList failed peers count : 9 [90 %]
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1

- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1

- Peer ID : 50:2E:6C:AC:21:50, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1

sendList never tried peers count : 10 [50 %]
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : 58:2A:F7:ED:96:BE

- Peer ID : F8:CF:C5:D9:E5:61
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : E0:DB:10:1F:C9:5E
- Peer ID : 80:01:84:8A:B3:68

- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : B0:C5:59:3F:75:69

- Peer ID : 08:EC:A9:50:75:41
--------------- motorola-Nexus 6_PT9280 --------------------- : 7
sendList : 100% : 3787 ms, 99% : 3787 ms, 95 : 3787 ms, 90% : 3787 ms.

Average data rate: 0.026 MB/s
Result count 1, range 3787 ms to  3787 ms.
sendList failed peers count : 11 [91.66666666666667 %]

- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
sendList never tried peers count : 8 [40 %]
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : F8:95:C7:87:85:54
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 50:2E:6C:AC:21:50
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : E0:DB:10:14:E2:C0
--------------- LGE-LG-D855_PT6524 --------------------- : 8
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 9 [100 %]
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 50:2E:6C:AC:21:50, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
sendList never tried peers count : 11 [55 %]
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : 34:FC:EF:11:AE:67

- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : F8:95:C7:87:85:54
- Peer ID : 7C:F9:0E:34:8A:A0
--------------- HUAWEI-ALE-L21_PT5942 --------------------- : 9
sendList : 100% : 66049 ms, 99% : 66049 ms, 95 : 66049 ms, 90% : 66049 ms.

Average data rate: 0.003 MB/s
Result count 4, range 10570 ms to  66049 ms.

sendList failed peers count : 8 [66.66666666666667 %]
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1

- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1

- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
sendList never tried peers count : 8 [40 %]

- Peer ID : B0:C5:59:3F:75:69
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 34:FC:EF:11:B1:66

- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : B4:CE:F6:AB:A4:6A

- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : E0:DB:10:1F:C9:5E
--------------- HTC-HTC One_M8_PT8107 --------------------- : 10

sendList : 100% : 16515 ms, 99% : 16515 ms, 95 : 16515 ms, 90% : 16515 ms.
Average data rate: 0.007 MB/s
Result count 2, range 12540 ms to  16515 ms.

sendList failed peers count : 10 [83.33333333333333 %]
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1

- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1

- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1

- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
sendList never tried peers count : 8 [40 %]
- Peer ID : 58:2A:F7:ED:96:BE

- Peer ID : F8:95:C7:87:85:54

- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : E0:DB:10:1F:C9:5E

- Peer ID : 08:EC:A9:50:76:27
--------------- samsung-SM-G900F_PT6267 --------------------- : 11
sendList : 100% : 63970 ms, 99% : 63970 ms, 95 : 63970 ms, 90% : 63970 ms.
Average data rate: 0.002 MB/s

Result count 2, range 23497 ms to  63970 ms.
sendList failed peers count : 8 [80 %]
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1

- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1

- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
sendList never tried peers count : 10 [50 %]

- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 50:2E:6C:AC:21:50
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : E0:DB:10:1F:C9:5E
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : F8:CF:C5:D9:E5:61
- Peer ID : B4:CE:F6:AB:A4:6A
--------------- samsung-SM-G900F_PT3260 --------------------- : 12
sendList : 100% : 9842 ms, 99% : 9842 ms, 95 : 9842 ms, 90% : 9842 ms.
Average data rate: 0.01 MB/s
Result count 1, range 9842 ms to  9842 ms.
sendList failed peers count : 8 [88.88888888888889 %]
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
sendList never tried peers count : 11 [55 %]
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : F8:CF:C5:D9:E5:61
- Peer ID : 50:2E:6C:AC:21:50
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : F4:F1:E1:5C:3B:E2
--------------- LGE-Nexus 5_PT227 --------------------- : 13
sendList : 100% : 21710 ms, 99% : 21710 ms, 95 : 21710 ms, 90% : 21710 ms.
Average data rate: 0.008 MB/s
Result count 2, range 4491 ms to  21710 ms.
sendList failed peers count : 10 [83.33333333333333 %]
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 50:2E:6C:AC:21:50, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
sendList never tried peers count : 8 [40 %]
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : F8:95:C7:87:85:54
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : E0:DB:10:1F:C9:5E
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : 44:80:EB:7B:5A:05
--------------- samsung-SM-A500FU_PT5912 --------------------- : 14
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 9 [100 %]
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : 50:2E:6C:AC:21:50, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
sendList never tried peers count : 11 [55 %]
- Peer ID : F8:CF:C5:D9:E5:61
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 58:2A:F7:ED:96:BE
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 34:FC:EF:9D:93:0B

- Peer ID : 58:3F:54:73:64:C0
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 80:01:84:8A:B3:68
--------------- motorola-XT1072_PT8734 --------------------- : 15
sendList : 100% : 9682 ms, 99% : 9682 ms, 95 : 9682 ms, 90% : 9682 ms.
Average data rate: 0.013 MB/s
Result count 2, range 5322 ms to  9682 ms.
sendList failed peers count : 8 [80 %]

- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1

- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1

- Peer ID : 80:01:84:8A:B3:68, Tried : 1
sendList never tried peers count : 10 [50 %]
- Peer ID : 50:2E:6C:AC:21:50
- Peer ID : 34:FC:EF:11:AE:67

- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : E0:DB:10:1F:C9:5E
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : F8:95:C7:87:85:54
- Peer ID : B4:CE:F6:AB:A4:6A
--------------- Combined ---------------------

sendList : 100% : 66049 ms, 99% : 66049 ms, 95 : 63970 ms, 90% : 58900 ms.
Average data rate: 0.005 MB/s
--------------- end of test report ---------------------

2015-11-27T12:37:20.711Z (1380 sec) - Android motorola-Nexus 6_PT9280 got disconnected

2015-11-27T12:37:20.925Z (1381 sec) - Android LGE-LG-H815_PT1997 got disconnected

2015-11-27T12:37:20.949Z (1381 sec) - Android HUAWEI-ALE-L21_PT5942 got disconnected

2015-11-27T12:37:20.978Z (1381 sec) - Android LGE-LG-D855_PT6524 got disconnected

2015-11-27T12:37:21.056Z (1381 sec) - Android LGE-Nexus 5_PT227 got disconnected

2015-11-27T12:37:21.062Z (1381 sec) - Android samsung-SM-G900F_PT3260 got disconnected

2015-11-27T12:37:21.068Z (1381 sec) - Android samsung-SM-G900F_PT6267 got disconnected

2015-11-27T12:37:21.132Z (1381 sec) - Android samsung-SM-N9005_PT4232 got disconnected

2015-11-27T12:37:21.205Z (1381 sec) - Android LGE-LG-D722_PT9286 got disconnected

2015-11-27T12:37:21.232Z (1381 sec) - Android samsung-SM-A500FU_PT5912 got disconnected

2015-11-27T12:37:26.950Z (1387 sec) - Android motorola-XT1072_PT8734 got disconnected

2015-11-27T12:37:40.395Z (1400 sec) - Android motorola-Nexus 6_PT9280 got disconnected

2015-11-27T12:37:43.699Z (1403 sec) - Android HTC-HTC One_M8_PT8107 got disconnected

2015-11-27T12:38:31.554Z (1451 sec) - Android LGE-LG-D802_PT7474 got disconnected

2015-11-27T12:38:32.784Z (1452 sec) - Android HTC-HTC Desire 820_PT8519 got disconnected

2015-11-27T12:38:33.691Z (1453 sec) - Android HTC-HTC Desire 820_PT603 got disconnected

2015-11-27T12:38:38.717Z (1458 sec) - Android HTC-HTC One_M8_PT8107 got disconnected


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```
###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
STOP log received from  f56ad48d Test has  SUCCEEDED
STOP log received from  W3D7N15428022572 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Device test finished on f56ad48d 
Device test finished on W3D7N15428022572 
Android task is completed. [SUCCESS]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/51986340bb0815b_CI_TEST_-_DO_NOT_MERGE_vjrantal/thali01_LGE-LG-H815.md)

[HUAWEI-ALE-L21](https://github.com/ThaliTester/TestResults/blob/51986340bb0815b_CI_TEST_-_DO_NOT_MERGE_vjrantal/thali01_HUAWEI-ALE-L21.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/51986340bb0815b_CI_TEST_-_DO_NOT_MERGE_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/51986340bb0815b_CI_TEST_-_DO_NOT_MERGE_vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/51986340bb0815b_CI_TEST_-_DO_NOT_MERGE_vjrantal/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/51986340bb0815b_CI_TEST_-_DO_NOT_MERGE_vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/51986340bb0815b_CI_TEST_-_DO_NOT_MERGE_vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/51986340bb0815b_CI_TEST_-_DO_NOT_MERGE_vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  0be0c6c6 Test has  SUCCEEDED
Device test finished on 0be0c6c6 
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on ZX1C223JKW 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/51986340bb0815b_CI_TEST_-_DO_NOT_MERGE_vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/51986340bb0815b_CI_TEST_-_DO_NOT_MERGE_vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/51986340bb0815b_CI_TEST_-_DO_NOT_MERGE_vjrantal/thali04_samsung-SM-G900F.md)

####Node name: thali05
Console output:
```
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
STOP log received from  1d6a772d Test has  SUCCEEDED
STOP log received from  SH47FWM00508 Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
Device test finished on 1d6a772d 
Device test finished on SH47FWM00508 
Android task is completed. [SUCCESS]
```
[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/51986340bb0815b_CI_TEST_-_DO_NOT_MERGE_vjrantal/thali05_samsung-SM-N9005.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/51986340bb0815b_CI_TEST_-_DO_NOT_MERGE_vjrantal/thali05_motorola-Nexus 6.md)

[HTC-HTC One_M8](https://github.com/ThaliTester/TestResults/blob/51986340bb0815b_CI_TEST_-_DO_NOT_MERGE_vjrantal/thali05_HTC-HTC One_M8.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/51986340bb0815b_CI_TEST_-_DO_NOT_MERGE_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/51986340bb0815b_CI_TEST_-_DO_NOT_MERGE_vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/51986340bb0815b_CI_TEST_-_DO_NOT_MERGE_vjrantal/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/51986340bb0815b_CI_TEST_-_DO_NOT_MERGE_vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/51986340bb0815b_CI_TEST_-_DO_NOT_MERGE_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
STOP log received from  HT574YC04723 Test has  SUCCEEDED
Device test finished on HT574YC04723 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:null 
child process exited with code null on device 4325e43f 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/51986340bb0815b_CI_TEST_-_DO_NOT_MERGE_vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/51986340bb0815b_CI_TEST_-_DO_NOT_MERGE_vjrantal/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
Error! Unexpected exit on device 0c6a0f3c0bdb4e77 app:com.test.thalitest code:0 
child process exited with code 0 on device 0c6a0f3c0bdb4e77 
STOP log received from  CC51WYC03425 Test has  SUCCEEDED
Device test finished on CC51WYC03425 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/51986340bb0815b_CI_TEST_-_DO_NOT_MERGE_vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/51986340bb0815b_CI_TEST_-_DO_NOT_MERGE_vjrantal/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/51986340bb0815b_CI_TEST_-_DO_NOT_MERGE_vjrantal/iOS_Iphone5-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/51986340bb0815b_CI_TEST_-_DO_NOT_MERGE_vjrantal/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/51986340bb0815b_CI_TEST_-_DO_NOT_MERGE_vjrantal/iOS_Iphone6-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/51986340bb0815b_CI_TEST_-_DO_NOT_MERGE_vjrantal/iOS_IpadAir2-1.md)


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

2015-11-27T12:14:20.338Z (0 sec) - Android tests will start after waiting for 120 seconds

Test ID 0 configuration: testSendData.js, server timeout: 1200000, data:

{ timeout: 1000000,
  rounds: 1,
  dataTimeout: 10000,
  dataAmount: 100000,
  conReTryTimeout: 5000,
  conReTryCount: 5 }

2015-11-27T12:14:20.344Z (0 sec) - iOS tests will start after waiting for 120 seconds

listening on *:3000

2015-11-27T12:14:20.907Z (1 sec) - Android LGE-LG-H815_PT1997 added (current device count 1)

2015-11-27T12:14:20.925Z (1 sec) - Android HTC-HTC Desire 820_PT603 added (current device count 2)

2015-11-27T12:14:20.986Z (1 sec) - Android samsung-SM-N9005_PT4232 added (current device count 3)

2015-11-27T12:14:20.996Z (1 sec) - iOS Apple-Iphone5s-1_PT8509 added (current device count 1)

2015-11-27T12:14:21.757Z (1 sec) - Android LGE-LG-D802_PT7474 added (current device count 4)

2015-11-27T12:14:22.342Z (2 sec) - Android LGE-LG-D722_PT9286 added (current device count 5)

2015-11-27T12:14:22.384Z (2 sec) - Android HTC-HTC Desire 820_PT8519 added (current device count 6)

2015-11-27T12:14:22.467Z (2 sec) - iOS Apple-Iphone5-1_PT1479 added (current device count 2)

2015-11-27T12:14:22.635Z (2 sec) - iOS Apple-Iphone6-1_PT6911 added (current device count 3)

2015-11-27T12:14:22.641Z (2 sec) - Android motorola-Nexus 6_PT9280 added (current device count 7)

2015-11-27T12:14:23.527Z (3 sec) - Android LGE-LG-D855_PT6524 added (current device count 8)

2015-11-27T12:14:23.621Z (3 sec) - Android samsung-SM-A300FU_PT1809 added (current device count 9)

2015-11-27T12:14:23.673Z (3 sec) - Android samsung-SM-G800F_PT3153 added (current device count 10)

2015-11-27T12:14:23.750Z (3 sec) - iOS Apple-IpadAir2-1_PT3767 added (current device count 4)

2015-11-27T12:14:24.582Z (4 sec) - Android LGE-Nexus 5_PT6174 added (current device count 11)

2015-11-27T12:14:24.719Z (4 sec) - Android samsung-SM-A300FU_PT4975 added (current device count 12)

2015-11-27T12:14:24.810Z (5 sec) - Android motorola-XT1039_PT82 added (current device count 13)

2015-11-27T12:14:24.902Z (5 sec) - Android HUAWEI-ALE-L21_PT5942 added (current device count 14)

2015-11-27T12:14:25.055Z (5 sec) - Android HTC-HTC One_M8_PT8107 added (current device count 15)

2015-11-27T12:14:25.124Z (5 sec) - Android samsung-SM-G900F_PT6267 added (current device count 16)

2015-11-27T12:14:25.310Z (5 sec) - Android samsung-SM-G900F_PT3260 added (current device count 17)

2015-11-27T12:14:25.321Z (5 sec) - Android LGE-Nexus 5_PT227 added (current device count 18)

2015-11-27T12:14:25.501Z (5 sec) - Android samsung-SM-A500FU_PT5912 added (current device count 19)

2015-11-27T12:14:28.892Z (9 sec) - Android samsung-SM-N910C_PT8283 added (current device count 20)

2015-11-27T12:14:29.763Z (9 sec) - Android motorola-XT1072_PT8734 added (current device count 21)

-------------- We got wait done, now starting the testing process ------------------

2015-11-27T12:16:20.387Z (120 sec) - Android start testing now with 21 devices

2015-11-27T12:16:20.415Z (120 sec) - iOS start testing now with 4 devices

2015-11-27T12:16:32.954Z (133 sec) - iOS Apple-IpadAir2-1_PT3767 test took 12537ms - results peers[0], reConnects[0], sendData[3]

2015-11-27T12:17:27.237Z (187 sec) - Android LGE-Nexus 5_PT6174 got re-connected event

2015-11-27T12:17:55.029Z (215 sec) - Android LGE-Nexus 5_PT6174 got disconnected

2015-11-27T12:18:11.569Z (231 sec) - iOS Apple-Iphone5s-1_PT8509 test took 111153ms - results peers[0], reConnects[0], sendData[3]

2015-11-27T12:18:16.144Z (236 sec) - iOS Apple-Iphone6-1_PT6911 test took 115727ms - results peers[0], reConnects[0], sendData[3]

2015-11-27T12:19:17.260Z (297 sec) - Android LGE-Nexus 5_PT6174 got disconnected

2015-11-27T12:19:56.787Z (336 sec) - iOS Apple-Iphone5-1_PT1479 test took 216371ms - results peers[0], reConnects[0], sendData[3]

2015-11-27T12:19:56.788Z (336 sec) - iOS test ID 0 done now

2015-11-27T12:19:56.796Z (336 sec) - iOS All tests are done, preparing test report

--------------- test report ---------------------

--------------- Apple-Iphone5s-1_PT8509 --------------------- : 1

sendList : 100% : 3967 ms, 99% : 3967 ms, 95 : 3967 ms, 90% : 3967 ms.

Average data rate: 0.028 MB/s

Result count 2, range 3294 ms to  3967 ms.

sendList failed peers count : 1 [33.333333333333336 %]

- Peer ID : Apple-Iphone5-1_PT1479.RH8WAQ==, Tried : 5

sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5-1_PT1479 --------------------- : 2

sendList : 100% : 5133 ms, 99% : 5133 ms, 95 : 5133 ms, 90% : 5133 ms.
Average data rate: 0.019 MB/s
Result count 1, range 5133 ms to  5133 ms.
sendList failed peers count : 2 [66.66666666666667 %]
- Peer ID : Apple-Iphone6-1_PT6911.ZjHo2g==, Tried : 5
- Peer ID : Apple-Iphone5s-1_PT8509.17j4Hw==, Tried : 5

sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1_PT6911 --------------------- : 3

sendList : 100% : 3661 ms, 99% : 3661 ms, 95 : 3661 ms, 90% : 3661 ms.
Average data rate: 0.029 MB/s
Result count 2, range 3248 ms to  3661 ms.
sendList failed peers count : 1 [33.333333333333336 %]

- Peer ID : Apple-IpadAir2-1_PT3767.CF0kqQ==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Apple-IpadAir2-1_PT3767 --------------------- : 4
sendList : 100% : 4084 ms, 99% : 4084 ms, 95 : 4084 ms, 90% : 4084 ms.
Average data rate: 0.028 MB/s
Result count 3, range 3256 ms to  4084 ms.

sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------

sendList : 100% : 5133 ms, 99% : 5133 ms, 95 : 5133 ms, 90% : 4084 ms.
Average data rate: 0.027 MB/s
--------------- end of test report ---------------------

2015-11-27T12:19:57.016Z (337 sec) - iOS Apple-Iphone6-1_PT6911 got disconnected

2015-11-27T12:19:57.446Z (337 sec) - iOS Apple-IpadAir2-1_PT3767 got disconnected

2015-11-27T12:19:57.517Z (337 sec) - iOS Apple-Iphone5s-1_PT8509 got disconnected

2015-11-27T12:20:04.458Z (344 sec) - Android samsung-SM-N910C_PT8283 got disconnected

2015-11-27T12:20:05.154Z (345 sec) - iOS Apple-Iphone5-1_PT1479 got disconnected

2015-11-27T12:20:28.044Z (368 sec) - Android LGE-LG-H815_PT1997 got re-connected event

2015-11-27T12:20:28.264Z (368 sec) - Android motorola-XT1039_PT82 got re-connected event

2015-11-27T12:21:14.884Z (415 sec) - Android LGE-LG-H815_PT1997 got disconnected

2015-11-27T12:21:15.761Z (415 sec) - Android samsung-SM-G800F_PT3153 got disconnected

2015-11-27T12:21:17.018Z (417 sec) - Android motorola-XT1039_PT82 got disconnected

2015-11-27T12:21:17.918Z (418 sec) - Android motorola-Nexus 6_PT9280 got re-connected event

2015-11-27T12:21:31.353Z (431 sec) - Android LGE-Nexus 5_PT6174 got re-connected event

2015-11-27T12:22:03.081Z (463 sec) - Android LGE-Nexus 5_PT6174 got re-connected event

2015-11-27T12:22:28.600Z (488 sec) - Android motorola-Nexus 6_PT9280 got disconnected

2015-11-27T12:22:56.365Z (516 sec) - Android LGE-Nexus 5_PT6174 got disconnected

2015-11-27T12:23:17.759Z (537 sec) - Android motorola-Nexus 6_PT9280 got re-connected event

2015-11-27T12:23:23.572Z (543 sec) - Android samsung-SM-A300FU_PT1809 got disconnected

2015-11-27T12:23:52.972Z (573 sec) - Android LGE-Nexus 5_PT6174 got disconnected

2015-11-27T12:24:23.053Z (603 sec) - Android motorola-Nexus 6_PT9280 got disconnected

2015-11-27T12:25:56.400Z (696 sec) - Android LGE-Nexus 5_PT6174 got re-connected event

2015-11-27T12:26:20.934Z (721 sec) - Android samsung-SM-A300FU_PT4975 got disconnected

2015-11-27T12:27:35.948Z (796 sec) - Android LGE-Nexus 5_PT6174 got re-connected event

2015-11-27T12:27:41.962Z (802 sec) - Android motorola-XT1039_PT82 got disconnected

2015-11-27T12:27:46.114Z (806 sec) - Android LGE-Nexus 5_PT6174 got disconnected

2015-11-27T12:28:29.452Z (849 sec) - Android LGE-Nexus 5_PT6174 got re-connected event

2015-11-27T12:28:30.473Z (850 sec) - Android HTC-HTC Desire 820_PT8519 got disconnected

2015-11-27T12:28:34.637Z (854 sec) - Android motorola-XT1072_PT8734 got disconnected

2015-11-27T12:28:54.821Z (875 sec) - Android HTC-HTC Desire 820_PT8519 got re-connected event

2015-11-27T12:29:00.949Z (881 sec) - Android LGE-Nexus 5_PT6174 got disconnected

2015-11-27T12:29:30.879Z (911 sec) - Android motorola-XT1072_PT8734 got re-connected event

2015-11-27T12:29:54.454Z (934 sec) - Android LGE-Nexus 5_PT6174 got disconnected

2015-11-27T12:30:10.433Z (950 sec) - Android motorola-XT1039_PT82 got re-connected event

2015-11-27T12:30:44.807Z (985 sec) - Android HTC-HTC Desire 820_PT8519 got disconnected

2015-11-27T12:31:16.945Z (1017 sec) - Android HTC-HTC Desire 820_PT8519 got re-connected event

2015-11-27T12:32:36.175Z (1096 sec) - Android LGE-LG-D802_PT7474 got disconnected

2015-11-27T12:32:41.948Z (1102 sec) - Android HTC-HTC Desire 820_PT8519 got disconnected

2015-11-27T12:33:00.820Z (1121 sec) - Android HTC-HTC One_M8_PT8107 test took 1000414ms - results peers[0], reConnects[0], sendData[20]

2015-11-27T12:33:00.874Z (1121 sec) - Android motorola-Nexus 6_PT9280 test took 1000475ms - results peers[0], reConnects[0], sendData[20]

2015-11-27T12:33:00.906Z (1121 sec) - Android samsung-SM-N9005_PT4232 test took 1000510ms - results peers[0], reConnects[0], sendData[20]

2015-11-27T12:33:00.993Z (1121 sec) - Android samsung-SM-G900F_PT6267 test took 1000586ms - results peers[0], reConnects[0], sendData[20]

2015-11-27T12:33:01.010Z (1121 sec) - Android samsung-SM-G900F_PT3260 test took 1000603ms - results peers[0], reConnects[0], sendData[20]

2015-11-27T12:33:01.048Z (1121 sec) - Android LGE-Nexus 5_PT227 test took 1000639ms - results peers[0], reConnects[0], sendData[20]

2015-11-27T12:33:01.135Z (1121 sec) - Android samsung-SM-A500FU_PT5912 test took 1000726ms - results peers[0], reConnects[0], sendData[20]

2015-11-27T12:33:01.357Z (1121 sec) - Android HUAWEI-ALE-L21_PT5942 test took 1000952ms - results peers[0], reConnects[0], sendData[20]

2015-11-27T12:33:01.478Z (1121 sec) - Android LGE-LG-H815_PT1997 test took 1001086ms - results peers[0], reConnects[0], sendData[20]

2015-11-27T12:33:02.610Z (1122 sec) - Android LGE-LG-D722_PT9286 test took 1002213ms - results peers[0], reConnects[0], sendData[20]

2015-11-27T12:33:02.676Z (1122 sec) - Android LGE-LG-D855_PT6524 test took 1002275ms - results peers[0], reConnects[0], sendData[20]

2015-11-27T12:33:03.081Z (1123 sec) - Android HTC-HTC Desire 820_PT603 test took 1002686ms - results peers[0], reConnects[0], sendData[20]

2015-11-27T12:33:06.419Z (1126 sec) - Android motorola-XT1072_PT8734 got disconnected

2015-11-27T12:33:20.205Z (1140 sec) - Android HTC-HTC Desire 820_PT8519 got re-connected event

2015-11-27T12:33:20.227Z (1140 sec) - Android HTC-HTC Desire 820_PT8519 test took 1019829ms - results peers[0], reConnects[0], sendData[20]

2015-11-27T12:33:41.535Z (1161 sec) - Android motorola-XT1039_PT82 got disconnected

2015-11-27T12:33:45.634Z (1165 sec) - Android LGE-LG-D802_PT7474 got re-connected event

2015-11-27T12:33:45.638Z (1165 sec) - Android LGE-LG-D802_PT7474 test took 1045241ms - results peers[0], reConnects[0], sendData[20]

2015-11-27T12:33:59.247Z (1179 sec) - Android motorola-XT1072_PT8734 got re-connected event

2015-11-27T12:33:59.281Z (1179 sec) - Android motorola-XT1072_PT8734 test took 1058871ms - results peers[0], reConnects[0], sendData[20]

2015-11-27T12:36:20.414Z (1320 sec) - Server timeout reached!

2015-11-27T12:36:20.415Z (1320 sec) - Send timeout to samsung-SM-A300FU_PT1809
2015-11-27T12:36:20.415Z (1320 sec) - Send timeout to samsung-SM-G800F_PT3153
2015-11-27T12:36:20.416Z (1320 sec) - Send timeout to LGE-Nexus 5_PT6174
2015-11-27T12:36:20.417Z (1320 sec) - Send timeout to samsung-SM-A300FU_PT4975
2015-11-27T12:36:20.418Z (1320 sec) - Send timeout to motorola-XT1039_PT82
2015-11-27T12:36:20.419Z (1320 sec) - Send timeout to samsung-SM-N910C_PT8283

2015-11-27T12:36:34.733Z (1334 sec) - Android motorola-Nexus 6_PT9280 got re-connected event

2015-11-27T12:36:48.829Z (1349 sec) - Android HTC-HTC One_M8_PT8107 got re-connected event

2015-11-27T12:37:20.421Z (1380 sec) - Did not get reports from all devices, but forcing tests to finish!

samsung-SM-A300FU_PT1809 did not have results at the end of tests - check the device logs about why!!

samsung-SM-G800F_PT3153 did not have results at the end of tests - check the device logs about why!!
LGE-Nexus 5_PT6174 did not have results at the end of tests - check the device logs about why!!
samsung-SM-A300FU_PT4975 did not have results at the end of tests - check the device logs about why!!
motorola-XT1039_PT82 did not have results at the end of tests - check the device logs about why!!

samsung-SM-N910C_PT8283 did not have results at the end of tests - check the device logs about why!!

2015-11-27T12:37:20.440Z (1380 sec) - Android All tests are done, preparing test report

--------------- test report ---------------------

--------------- LGE-LG-H815_PT1997 --------------------- : 1
sendList : 100% : 7454 ms, 99% : 7454 ms, 95 : 7454 ms, 90% : 7454 ms.
Average data rate: 0.013 MB/s

Result count 1, range 7454 ms to  7454 ms.
sendList failed peers count : 9 [90 %]
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1

- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1

- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : 50:2E:6C:AC:21:50, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
sendList never tried peers count : 10 [50 %]

- Peer ID : 7C:F9:0E:34:8A:A0

- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : E0:DB:10:1F:C9:5E
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : F8:95:C7:87:85:54

- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 58:2A:F7:ED:96:BE

--------------- HTC-HTC Desire 820_PT603 --------------------- : 2
sendList : 100% : 3161 ms, 99% : 3161 ms, 95 : 3161 ms, 90% : 3161 ms.
Average data rate: 0.032 MB/s
Result count 1, range 3161 ms to  3161 ms.
sendList failed peers count : 10 [90.9090909090909 %]
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 50:2E:6C:AC:21:50, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
sendList never tried peers count : 9 [45 %]
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : E0:DB:10:1F:C9:5E
- Peer ID : 58:2A:F7:ED:96:BE
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : F8:CF:C5:D9:E5:61
- Peer ID : B4:CE:F6:AB:A4:6A
--------------- samsung-SM-N9005_PT4232 --------------------- : 3
sendList : 100% : 18972 ms, 99% : 18972 ms, 95 : 18972 ms, 90% : 18972 ms.
Average data rate: 0.005 MB/s
Result count 1, range 18972 ms to  18972 ms.
sendList failed peers count : 10 [90.9090909090909 %]
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1

sendList never tried peers count : 9 [45 %]
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 58:3F:54:73:64:C0

- Peer ID : 50:2E:6C:AC:21:50
- Peer ID : 58:2A:F7:ED:96:BE
- Peer ID : 34:FC:EF:9D:93:0B
--------------- LGE-LG-D802_PT7474 --------------------- : 4

sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s

Results list does not contain any items
sendList failed peers count : 10 [100 %]
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1

- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1

- Peer ID : 50:2E:6C:AC:21:50, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1

- Peer ID : F8:95:C7:87:85:54, Tried : 1
sendList never tried peers count : 10 [50 %]
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : F8:95:C7:87:3C:51

- Peer ID : 58:2A:F7:ED:96:BE
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : F8:CF:C5:D9:E5:61
- Peer ID : 7C:F9:0E:34:8A:A0

- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : E0:DB:10:14:E2:C0

--------------- LGE-LG-D722_PT9286 --------------------- : 5
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s

Results list does not contain any items
sendList failed peers count : 9 [100 %]
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1

- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 50:2E:6C:AC:21:50, Tried : 1

- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1

- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
sendList never tried peers count : 11 [55 %]
- Peer ID : 7C:F9:0E:34:8A:A0

- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : 7C:F9:0E:37:96:AB

- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : E0:DB:10:14:E2:C0

- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 00:F4:6F:30:E0:6C
--------------- HTC-HTC Desire 820_PT8519 --------------------- : 6
sendList : 100% : 3859 ms, 99% : 3859 ms, 95 : 3859 ms, 90% : 3859 ms.

Average data rate: 0.026 MB/s
Result count 1, range 3859 ms to  3859 ms.
sendList failed peers count : 9 [90 %]
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1

- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1

- Peer ID : 50:2E:6C:AC:21:50, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1

sendList never tried peers count : 10 [50 %]
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : 58:2A:F7:ED:96:BE

- Peer ID : F8:CF:C5:D9:E5:61
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : E0:DB:10:1F:C9:5E
- Peer ID : 80:01:84:8A:B3:68

- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : B0:C5:59:3F:75:69

- Peer ID : 08:EC:A9:50:75:41
--------------- motorola-Nexus 6_PT9280 --------------------- : 7
sendList : 100% : 3787 ms, 99% : 3787 ms, 95 : 3787 ms, 90% : 3787 ms.

Average data rate: 0.026 MB/s
Result count 1, range 3787 ms to  3787 ms.
sendList failed peers count : 11 [91.66666666666667 %]

- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
sendList never tried peers count : 8 [40 %]
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : F8:95:C7:87:85:54
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 50:2E:6C:AC:21:50
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : E0:DB:10:14:E2:C0
--------------- LGE-LG-D855_PT6524 --------------------- : 8
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 9 [100 %]
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 50:2E:6C:AC:21:50, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
sendList never tried peers count : 11 [55 %]
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : 34:FC:EF:11:AE:67

- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : F8:95:C7:87:85:54
- Peer ID : 7C:F9:0E:34:8A:A0
--------------- HUAWEI-ALE-L21_PT5942 --------------------- : 9
sendList : 100% : 66049 ms, 99% : 66049 ms, 95 : 66049 ms, 90% : 66049 ms.

Average data rate: 0.003 MB/s
Result count 4, range 10570 ms to  66049 ms.

sendList failed peers count : 8 [66.66666666666667 %]
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1

- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1

- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
sendList never tried peers count : 8 [40 %]

- Peer ID : B0:C5:59:3F:75:69
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 34:FC:EF:11:B1:66

- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : B4:CE:F6:AB:A4:6A

- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : E0:DB:10:1F:C9:5E
--------------- HTC-HTC One_M8_PT8107 --------------------- : 10

sendList : 100% : 16515 ms, 99% : 16515 ms, 95 : 16515 ms, 90% : 16515 ms.
Average data rate: 0.007 MB/s
Result count 2, range 12540 ms to  16515 ms.

sendList failed peers count : 10 [83.33333333333333 %]
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1

- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1

- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1

- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
sendList never tried peers count : 8 [40 %]
- Peer ID : 58:2A:F7:ED:96:BE

- Peer ID : F8:95:C7:87:85:54

- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : E0:DB:10:1F:C9:5E

- Peer ID : 08:EC:A9:50:76:27
--------------- samsung-SM-G900F_PT6267 --------------------- : 11
sendList : 100% : 63970 ms, 99% : 63970 ms, 95 : 63970 ms, 90% : 63970 ms.
Average data rate: 0.002 MB/s

Result count 2, range 23497 ms to  63970 ms.
sendList failed peers count : 8 [80 %]
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1

- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1

- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
sendList never tried peers count : 10 [50 %]

- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 50:2E:6C:AC:21:50
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : E0:DB:10:1F:C9:5E
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : F8:CF:C5:D9:E5:61
- Peer ID : B4:CE:F6:AB:A4:6A
--------------- samsung-SM-G900F_PT3260 --------------------- : 12
sendList : 100% : 9842 ms, 99% : 9842 ms, 95 : 9842 ms, 90% : 9842 ms.
Average data rate: 0.01 MB/s
Result count 1, range 9842 ms to  9842 ms.
sendList failed peers count : 8 [88.88888888888889 %]
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
sendList never tried peers count : 11 [55 %]
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : F8:CF:C5:D9:E5:61
- Peer ID : 50:2E:6C:AC:21:50
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : F4:F1:E1:5C:3B:E2
--------------- LGE-Nexus 5_PT227 --------------------- : 13
sendList : 100% : 21710 ms, 99% : 21710 ms, 95 : 21710 ms, 90% : 21710 ms.
Average data rate: 0.008 MB/s
Result count 2, range 4491 ms to  21710 ms.
sendList failed peers count : 10 [83.33333333333333 %]
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 50:2E:6C:AC:21:50, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
sendList never tried peers count : 8 [40 %]
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : F8:95:C7:87:85:54
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : E0:DB:10:1F:C9:5E
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : 44:80:EB:7B:5A:05
--------------- samsung-SM-A500FU_PT5912 --------------------- : 14
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 9 [100 %]
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : 50:2E:6C:AC:21:50, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
sendList never tried peers count : 11 [55 %]
- Peer ID : F8:CF:C5:D9:E5:61
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 58:2A:F7:ED:96:BE
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 34:FC:EF:9D:93:0B

- Peer ID : 58:3F:54:73:64:C0
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 80:01:84:8A:B3:68
--------------- motorola-XT1072_PT8734 --------------------- : 15
sendList : 100% : 9682 ms, 99% : 9682 ms, 95 : 9682 ms, 90% : 9682 ms.
Average data rate: 0.013 MB/s
Result count 2, range 5322 ms to  9682 ms.
sendList failed peers count : 8 [80 %]

- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1

- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1

- Peer ID : 80:01:84:8A:B3:68, Tried : 1
sendList never tried peers count : 10 [50 %]
- Peer ID : 50:2E:6C:AC:21:50
- Peer ID : 34:FC:EF:11:AE:67

- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : E0:DB:10:1F:C9:5E
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : F8:95:C7:87:85:54
- Peer ID : B4:CE:F6:AB:A4:6A
--------------- Combined ---------------------

sendList : 100% : 66049 ms, 99% : 66049 ms, 95 : 63970 ms, 90% : 58900 ms.
Average data rate: 0.005 MB/s
--------------- end of test report ---------------------

2015-11-27T12:37:20.711Z (1380 sec) - Android motorola-Nexus 6_PT9280 got disconnected

2015-11-27T12:37:20.925Z (1381 sec) - Android LGE-LG-H815_PT1997 got disconnected

2015-11-27T12:37:20.949Z (1381 sec) - Android HUAWEI-ALE-L21_PT5942 got disconnected

2015-11-27T12:37:20.978Z (1381 sec) - Android LGE-LG-D855_PT6524 got disconnected

2015-11-27T12:37:21.056Z (1381 sec) - Android LGE-Nexus 5_PT227 got disconnected

2015-11-27T12:37:21.062Z (1381 sec) - Android samsung-SM-G900F_PT3260 got disconnected

2015-11-27T12:37:21.068Z (1381 sec) - Android samsung-SM-G900F_PT6267 got disconnected

2015-11-27T12:37:21.132Z (1381 sec) - Android samsung-SM-N9005_PT4232 got disconnected

2015-11-27T12:37:21.205Z (1381 sec) - Android LGE-LG-D722_PT9286 got disconnected

2015-11-27T12:37:21.232Z (1381 sec) - Android samsung-SM-A500FU_PT5912 got disconnected

2015-11-27T12:37:26.950Z (1387 sec) - Android motorola-XT1072_PT8734 got disconnected

2015-11-27T12:37:40.395Z (1400 sec) - Android motorola-Nexus 6_PT9280 got disconnected

2015-11-27T12:37:43.699Z (1403 sec) - Android HTC-HTC One_M8_PT8107 got disconnected

2015-11-27T12:38:31.554Z (1451 sec) - Android LGE-LG-D802_PT7474 got disconnected

2015-11-27T12:38:32.784Z (1452 sec) - Android HTC-HTC Desire 820_PT8519 got disconnected

2015-11-27T12:38:33.691Z (1453 sec) - Android HTC-HTC Desire 820_PT603 got disconnected

2015-11-27T12:38:38.717Z (1458 sec) - Android HTC-HTC One_M8_PT8107 got disconnected


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


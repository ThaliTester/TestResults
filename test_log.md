#### Test 513350283842813 Logs

Status: 
```

ios : false

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m



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

2015-11-25T09:24:49.042Z (0 sec) - Android tests will start after waiting for 120 seconds

Test ID 0 configuration: testSendData.js, server timeout: 1200000, data:

{ timeout: '1000000',
  rounds: '1',
  dataTimeout: '10000',
  dataAmount: '100000',
  conReTryTimeout: '5000',
  conReTryCount: '5' }

2015-11-25T09:24:49.048Z (0 sec) - iOS tests will start after waiting for 120 seconds

listening on *:3000

2015-11-25T09:24:49.598Z (1 sec) - Android LGE-LG-H815_PT8316 added (current device count 1)

2015-11-25T09:24:49.652Z (1 sec) - Android HTC-HTC One_M8_PT7367 added (current device count 2)

2015-11-25T09:24:49.846Z (1 sec) - iOS Apple-Iphone6-1_PT8682 added (current device count 1)

2015-11-25T09:24:50.200Z (1 sec) - Android samsung-SM-A300FU_PT4190 added (current device count 3)

2015-11-25T09:24:50.205Z (1 sec) - Android motorola-Nexus 6_PT8656 added (current device count 4)

2015-11-25T09:24:50.258Z (1 sec) - Android HUAWEI-ALE-L21_PT5854 added (current device count 5)

2015-11-25T09:24:50.342Z (1 sec) - Android samsung-SM-A300FU_PT7055 added (current device count 6)

2015-11-25T09:24:50.442Z (1 sec) - iOS Apple-Iphone5s-1_PT1341 added (current device count 2)

2015-11-25T09:24:51.879Z (3 sec) - iOS Apple-IpadAir2-1_PT7460 added (current device count 3)

2015-11-25T09:24:52.445Z (3 sec) - iOS Apple-Iphone5-1_PT138 added (current device count 4)

2015-11-25T09:24:52.454Z (3 sec) - Android samsung-SM-G800F_PT4559 added (current device count 7)

2015-11-25T09:24:52.645Z (4 sec) - Android LGE-Nexus 5_PT3721 added (current device count 8)

2015-11-25T09:24:52.730Z (4 sec) - Android samsung-SM-G900F_PT8206 added (current device count 9)

2015-11-25T09:24:52.885Z (4 sec) - Android motorola-XT1039_PT124 added (current device count 10)

2015-11-25T09:24:53.242Z (4 sec) - Android samsung-SM-A500FU_PT6627 added (current device count 11)

2015-11-25T09:24:53.335Z (4 sec) - Android HTC-HTC Desire 820_PT8406 added (current device count 12)

2015-11-25T09:24:53.391Z (4 sec) - Android LGE-Nexus 5_PT9129 added (current device count 13)

2015-11-25T09:24:53.507Z (5 sec) - Android LGE-LG-D802_PT4529 added (current device count 14)

2015-11-25T09:24:53.709Z (5 sec) - Android samsung-SM-N9005_PT2740 added (current device count 15)

2015-11-25T09:24:53.713Z (5 sec) - Android LGE-LG-D722_PT6069 added (current device count 16)

2015-11-25T09:24:54.053Z (5 sec) - Android HTC-HTC Desire 820_PT3716 added (current device count 17)

2015-11-25T09:24:54.208Z (5 sec) - Android LGE-LG-D855_PT5918 added (current device count 18)

2015-11-25T09:24:54.938Z (6 sec) - Android samsung-SM-N910C_PT1533 added (current device count 19)

2015-11-25T09:24:59.177Z (10 sec) - Android motorola-XT1072_PT7901 added (current device count 20)

-------------- We got wait done, now starting the testing process ------------------

2015-11-25T09:26:49.089Z (120 sec) - Android start testing now with 20 devices

2015-11-25T09:26:49.121Z (120 sec) - iOS start testing now with 4 devices

2015-11-25T09:27:00.923Z (132 sec) - iOS Apple-Iphone5s-1_PT1341 test took 11799ms - results peers[0], reConnects[0], sendData[3]

2015-11-25T09:27:02.446Z (133 sec) - iOS Apple-Iphone6-1_PT8682 test took 13324ms - results peers[0], reConnects[0], sendData[3]

2015-11-25T09:27:04.800Z (136 sec) - iOS Apple-IpadAir2-1_PT7460 test took 15676ms - results peers[0], reConnects[0], sendData[3]

2015-11-25T09:27:04.857Z (136 sec) - iOS Apple-Iphone5-1_PT138 test took 15734ms - results peers[0], reConnects[0], sendData[3]

2015-11-25T09:27:04.858Z (136 sec) - iOS test ID 0 done now

2015-11-25T09:27:04.866Z (136 sec) - iOS All tests are done, preparing test report

--------------- test report ---------------------

--------------- Apple-Iphone6-1_PT8682 --------------------- : 1

sendList : 100% : 6177 ms, 99% : 6177 ms, 95 : 6177 ms, 90% : 6177 ms.

Result count 3, range 2613 ms to  6177 ms.

sendList failed peers count : 0 [0 %]

sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5s-1_PT1341 --------------------- : 2

sendList : 100% : 4473 ms, 99% : 4473 ms, 95 : 4473 ms, 90% : 4473 ms.

Result count 3, range 2752 ms to  4473 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- Apple-IpadAir2-1_PT7460 --------------------- : 3
sendList : 100% : 6202 ms, 99% : 6202 ms, 95 : 6202 ms, 90% : 6202 ms.
Result count 3, range 3651 ms to  6202 ms.

sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5-1_PT138 --------------------- : 4
sendList : 100% : 6632 ms, 99% : 6632 ms, 95 : 6632 ms, 90% : 6632 ms.

Result count 3, range 2854 ms to  6632 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- Combined ---------------------

sendList : 100% : 6632 ms, 99% : 6632 ms, 95 : 6202 ms, 90% : 6202 ms.

--------------- end of test report ---------------------

2015-11-25T09:27:58.581Z (190 sec) - Android LGE-Nexus 5_PT9129 got disconnected

2015-11-25T09:28:56.201Z (247 sec) - Android LGE-LG-D855_PT5918 got disconnected

2015-11-25T09:28:58.174Z (249 sec) - Android LGE-LG-D855_PT5918 got re-connected event

2015-11-25T09:29:26.141Z (277 sec) - Android LGE-Nexus 5_PT9129 got re-connected event

2015-11-25T09:29:40.752Z (292 sec) - Android samsung-SM-N910C_PT1533 got disconnected

2015-11-25T09:29:49.614Z (301 sec) - Android motorola-XT1072_PT7901 got disconnected

2015-11-25T09:30:03.356Z (314 sec) - Android samsung-SM-G800F_PT4559 got disconnected

2015-11-25T09:30:29.699Z (341 sec) - Android LGE-LG-D722_PT6069 got disconnected

2015-11-25T09:30:30.660Z (342 sec) - Android LGE-Nexus 5_PT9129 got re-connected event

2015-11-25T09:30:51.143Z (362 sec) - Android LGE-Nexus 5_PT9129 got disconnected

2015-11-25T09:30:59.351Z (370 sec) - Android HTC-HTC Desire 820_PT8406 got disconnected

2015-11-25T09:31:19.401Z (390 sec) - Android LGE-Nexus 5_PT9129 got re-connected event

2015-11-25T09:31:55.667Z (427 sec) - Android LGE-Nexus 5_PT9129 got disconnected

2015-11-25T09:32:05.593Z (437 sec) - Android HTC-HTC One_M8_PT7367 got re-connected event

2015-11-25T09:32:10.911Z (442 sec) - Android LGE-Nexus 5_PT9129 got re-connected event

2015-11-25T09:32:23.624Z (455 sec) - Android samsung-SM-A300FU_PT4190 got disconnected

2015-11-25T09:33:02.603Z (494 sec) - Android samsung-SM-A500FU_PT6627 got disconnected

2015-11-25T09:33:05.762Z (497 sec) - Android HTC-HTC One_M8_PT7367 got disconnected

2015-11-25T09:33:07.905Z (499 sec) - Android LGE-Nexus 5_PT9129 got re-connected event

2015-11-25T09:33:09.415Z (500 sec) - Android LGE-Nexus 5_PT9129 got disconnected

2015-11-25T09:33:35.918Z (527 sec) - Android LGE-Nexus 5_PT9129 got disconnected

2015-11-25T09:33:52.477Z (543 sec) - Android LGE-Nexus 5_PT9129 got re-connected event

2015-11-25T09:33:53.153Z (544 sec) - Android motorola-XT1039_PT124 got re-connected event

2015-11-25T09:34:01.725Z (553 sec) - Android motorola-XT1039_PT124 got disconnected

2015-11-25T09:34:32.909Z (584 sec) - Android LGE-Nexus 5_PT9129 got disconnected

2015-11-25T09:34:43.750Z (595 sec) - Android LGE-Nexus 5_PT9129 got re-connected event

2015-11-25T09:35:11.780Z (623 sec) - Android LGE-Nexus 5_PT9129 got re-connected event

2015-11-25T09:35:17.478Z (628 sec) - Android LGE-Nexus 5_PT9129 got disconnected

2015-11-25T09:35:24.000Z (635 sec) - Android HTC-HTC Desire 820_PT8406 got re-connected event

2015-11-25T09:35:46.059Z (657 sec) - Android HTC-HTC Desire 820_PT3716 got re-connected event

2015-11-25T09:36:08.751Z (680 sec) - Android LGE-Nexus 5_PT9129 got disconnected

2015-11-25T09:36:12.632Z (684 sec) - Android LGE-Nexus 5_PT9129 got re-connected event

2015-11-25T09:36:37.406Z (708 sec) - Android HTC-HTC Desire 820_PT3716 got disconnected

2015-11-25T09:37:01.732Z (733 sec) - Android LGE-Nexus 5_PT9129 got disconnected

2015-11-25T09:37:26.185Z (757 sec) - Android LGE-Nexus 5_PT9129 got re-connected event

2015-11-25T09:38:27.735Z (819 sec) - Android LGE-Nexus 5_PT9129 got disconnected

2015-11-25T09:38:32.628Z (824 sec) - Android LGE-Nexus 5_PT9129 got re-connected event

2015-11-25T09:39:16.140Z (867 sec) - Android LGE-Nexus 5_PT9129 got disconnected

2015-11-25T09:39:52.546Z (904 sec) - Android LGE-Nexus 5_PT9129 got re-connected event

2015-11-25T09:40:29.359Z (940 sec) - Android LGE-Nexus 5_PT9129 got re-connected event

2015-11-25T09:40:47.897Z (959 sec) - Android LGE-Nexus 5_PT9129 got disconnected

2015-11-25T09:41:17.548Z (989 sec) - Android LGE-Nexus 5_PT9129 got disconnected

2015-11-25T09:41:20.501Z (991 sec) - Android HTC-HTC Desire 820_PT3716 got re-connected event

2015-11-25T09:41:41.507Z (1013 sec) - Android LGE-Nexus 5_PT9129 got re-connected event

2015-11-25T09:41:48.942Z (1020 sec) - Android HTC-HTC Desire 820_PT3716 got disconnected

2015-11-25T09:41:56.306Z (1027 sec) - Android HTC-HTC Desire 820_PT8406 got re-connected event

2015-11-25T09:42:18.397Z (1049 sec) - Android LGE-Nexus 5_PT9129 got disconnected

2015-11-25T09:42:27.533Z (1059 sec) - Android LGE-Nexus 5_PT9129 got re-connected event

2015-11-25T09:42:43.062Z (1074 sec) - Android HTC-HTC Desire 820_PT8406 got disconnected

2015-11-25T09:43:29.556Z (1121 sec) - Android samsung-SM-N9005_PT2740 test took 1000443ms - results peers[0], reConnects[0], sendData[19]

2015-11-25T09:43:29.721Z (1121 sec) - Android motorola-XT1039_PT124 test took 1000613ms - results peers[0], reConnects[0], sendData[19]

2015-11-25T09:43:29.740Z (1121 sec) - Android motorola-Nexus 6_PT8656 test took 1000636ms - results peers[0], reConnects[0], sendData[19]

2015-11-25T09:43:29.812Z (1121 sec) - Android samsung-SM-A300FU_PT7055 test took 1000708ms - results peers[0], reConnects[0], sendData[19]

2015-11-25T09:43:29.843Z (1121 sec) - Android LGE-Nexus 5_PT3721 test took 1000736ms - results peers[0], reConnects[0], sendData[19]

2015-11-25T09:43:29.850Z (1121 sec) - Android LGE-LG-D802_PT4529 test took 1000738ms - results peers[0], reConnects[0], sendData[19]

2015-11-25T09:43:29.932Z (1121 sec) - Android LGE-LG-H815_PT8316 test took 1000834ms - results peers[0], reConnects[0], sendData[19]

2015-11-25T09:43:29.974Z (1121 sec) - Android LGE-LG-D855_PT5918 test took 1000860ms - results peers[0], reConnects[0], sendData[19]

2015-11-25T09:43:31.157Z (1122 sec) - Android HUAWEI-ALE-L21_PT5854 test took 1002052ms - results peers[0], reConnects[0], sendData[19]

2015-11-25T09:43:31.598Z (1123 sec) - Android LGE-Nexus 5_PT9129 got disconnected

2015-11-25T09:43:32.319Z (1123 sec) - Android samsung-SM-G900F_PT8206 test took 1003211ms - results peers[0], reConnects[0], sendData[19]

2015-11-25T09:43:33.408Z (1124 sec) - Android HTC-HTC One_M8_PT7367 test took 1004307ms - results peers[0], reConnects[0], sendData[19]

2015-11-25T09:43:35.280Z (1126 sec) - Android HTC-HTC Desire 820_PT3716 test took 1006166ms - results peers[0], reConnects[0], sendData[19]

2015-11-25T09:43:36.059Z (1127 sec) - Android HTC-HTC Desire 820_PT8406 test took 1006949ms - results peers[0], reConnects[0], sendData[19]

2015-11-25T09:43:59.230Z (1150 sec) - Android LGE-Nexus 5_PT9129 got re-connected event

2015-11-25T09:44:17.526Z (1169 sec) - Android LGE-Nexus 5_PT9129 got disconnected

2015-11-25T09:44:49.549Z (1201 sec) - Android LGE-Nexus 5_PT9129 got re-connected event

2015-11-25T09:45:49.206Z (1260 sec) - Android LGE-Nexus 5_PT9129 got disconnected

2015-11-25T09:46:49.121Z (1320 sec) - Server timeout reached!

2015-11-25T09:46:49.122Z (1320 sec) - Send timeout to samsung-SM-A300FU_PT4190
2015-11-25T09:46:49.123Z (1320 sec) - Send timeout to samsung-SM-G800F_PT4559
2015-11-25T09:46:49.124Z (1320 sec) - Send timeout to samsung-SM-A500FU_PT6627
2015-11-25T09:46:49.124Z (1320 sec) - Send timeout to LGE-Nexus 5_PT9129

2015-11-25T09:46:49.126Z (1320 sec) - Send timeout to LGE-LG-D722_PT6069

2015-11-25T09:46:49.127Z (1320 sec) - Send timeout to samsung-SM-N910C_PT1533

2015-11-25T09:46:49.128Z (1320 sec) - Send timeout to motorola-XT1072_PT7901

2015-11-25T09:47:49.130Z (1380 sec) - Did not get reports from all devices, but forcing tests to finish!

samsung-SM-A300FU_PT4190 did not have results at the end of tests - check the device logs about why!!

samsung-SM-G800F_PT4559 did not have results at the end of tests - check the device logs about why!!

samsung-SM-A500FU_PT6627 did not have results at the end of tests - check the device logs about why!!

LGE-Nexus 5_PT9129 did not have results at the end of tests - check the device logs about why!!

LGE-LG-D722_PT6069 did not have results at the end of tests - check the device logs about why!!

samsung-SM-N910C_PT1533 did not have results at the end of tests - check the device logs about why!!

motorola-XT1072_PT7901 did not have results at the end of tests - check the device logs about why!!
2015-11-25T09:47:49.169Z (1380 sec) - Android All tests are done, preparing test report
--------------- test report ---------------------
--------------- LGE-LG-H815_PT8316 --------------------- : 1
sendList : 100% : 78916 ms, 99% : 78916 ms, 95 : 49508 ms, 90% : 49508 ms.
Result count 12, range 4428 ms to  78916 ms.
sendList failed peers count : 7 [36.8421052631579 %]
- Peer ID : 34:FC:EF:11:B1:66, Tried : 2
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 2
- Peer ID : 44:80:EB:7B:5A:05, Tried : 2
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 2
sendList never tried peers count : 0 [0 %]
--------------- HTC-HTC One_M8_PT7367 --------------------- : 2
sendList : 100% : 88917 ms, 99% : 88917 ms, 95 : 70991 ms, 90% : 70991 ms.
Result count 14, range 3552 ms to  88917 ms.
sendList failed peers count : 5 [26.31578947368421 %]
- Peer ID : 58:3F:54:73:64:C0, Tried : 2
- Peer ID : 44:80:EB:7B:5A:05, Tried : 2
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 2
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 2
- Peer ID : 34:FC:EF:11:B1:66, Tried : 2
sendList never tried peers count : 0 [0 %]
--------------- motorola-Nexus 6_PT8656 --------------------- : 3

sendList : 100% : 61065 ms, 99% : 61065 ms, 95 : 20096 ms, 90% : 19682 ms.
Result count 16, range 3740 ms to  61065 ms.
sendList failed peers count : 3 [15.789473684210526 %]
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 6
- Peer ID : 44:80:EB:7B:5A:05, Tried : 5
- Peer ID : 34:FC:EF:11:B1:66, Tried : 6
sendList never tried peers count : 0 [0 %]
--------------- HUAWEI-ALE-L21_PT5854 --------------------- : 4

sendList : 100% : 22417 ms, 99% : 22417 ms, 95 : 22417 ms, 90% : 22417 ms.
Result count 5, range 5339 ms to  22417 ms.
sendList failed peers count : 6 [54.54545454545455 %]
- Peer ID : 50:2E:6C:AC:21:50, Tried : 1

- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1

- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1

sendList never tried peers count : 8 [42.10526315789474 %]

- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 7C:F9:0E:34:8A:A0

- Peer ID : F8:CF:C5:D9:E5:61
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 08:EC:A9:50:75:41

--------------- samsung-SM-A300FU_PT7055 --------------------- : 5
sendList : 100% : 54697 ms, 99% : 54697 ms, 95 : 44694 ms, 90% : 44694 ms.
Result count 11, range 2483 ms to  54697 ms.

sendList failed peers count : 8 [42.10526315789474 %]
- Peer ID : 08:EC:A9:50:76:27, Tried : 2
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1

- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 2
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 2

sendList never tried peers count : 0 [0 %]
--------------- LGE-Nexus 5_PT3721 --------------------- : 6
sendList : 100% : 87524 ms, 99% : 87524 ms, 95 : 35440 ms, 90% : 35440 ms.

Result count 15, range 2905 ms to  87524 ms.
sendList failed peers count : 4 [21.05263157894737 %]
- Peer ID : 34:FC:EF:11:B1:66, Tried : 4
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 3

- Peer ID : 44:80:EB:7B:5A:05, Tried : 3
- Peer ID : F8:95:C7:87:85:54, Tried : 3
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-G900F_PT8206 --------------------- : 7

sendList : 100% : 52389 ms, 99% : 52389 ms, 95 : 43415 ms, 90% : 38969 ms.
Result count 17, range 2819 ms to  52389 ms.
sendList failed peers count : 2 [10.526315789473685 %]

- Peer ID : 58:2A:F7:ED:96:BE, Tried : 6
- Peer ID : 34:FC:EF:11:B1:66, Tried : 6
sendList never tried peers count : 0 [0 %]
--------------- motorola-XT1039_PT124 --------------------- : 8

sendList : 100% : 52022 ms, 99% : 52022 ms, 95 : 32953 ms, 90% : 32953 ms.
Result count 12, range 2219 ms to  52022 ms.
sendList failed peers count : 7 [36.8421052631579 %]

- Peer ID : 08:EC:A9:50:76:27, Tried : 2
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 2

- Peer ID : 34:FC:EF:11:B1:66, Tried : 2
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 2
sendList never tried peers count : 0 [0 %]
--------------- HTC-HTC Desire 820_PT8406 --------------------- : 9

sendList : 100% : 33646 ms, 99% : 33646 ms, 95 : 26845 ms, 90% : 26845 ms.
Result count 11, range 2953 ms to  33646 ms.
sendList failed peers count : 8 [42.10526315789474 %]

- Peer ID : 58:3F:54:73:64:C0, Tried : 2
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1

- Peer ID : 34:FC:EF:11:B1:66, Tried : 2
- Peer ID : F8:95:C7:87:85:54, Tried : 2
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 2
- Peer ID : 44:80:EB:7B:5A:05, Tried : 2

sendList never tried peers count : 0 [0 %]
--------------- LGE-LG-D802_PT4529 --------------------- : 10
sendList : 100% : 32183 ms, 99% : 32183 ms, 95 : 30319 ms, 90% : 30319 ms.

Result count 13, range 4221 ms to  32183 ms.
sendList failed peers count : 6 [31.57894736842105 %]
- Peer ID : 58:3F:54:73:64:C0, Tried : 2
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 2
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 2

- Peer ID : F8:95:C7:87:85:54, Tried : 2
- Peer ID : 34:FC:EF:11:B1:66, Tried : 2
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 2
sendList never tried peers count : 0 [0 %]

--------------- samsung-SM-N9005_PT2740 --------------------- : 11

sendList : 100% : 69105 ms, 99% : 69105 ms, 95 : 42909 ms, 90% : 42909 ms.

Result count 13, range 2358 ms to  69105 ms.
sendList failed peers count : 6 [31.57894736842105 %]
- Peer ID : 34:FC:EF:11:B1:66, Tried : 3
- Peer ID : F8:95:C7:87:85:54, Tried : 2
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 2
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 2
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 2
- Peer ID : 44:80:EB:7B:5A:05, Tried : 2
sendList never tried peers count : 0 [0 %]
--------------- HTC-HTC Desire 820_PT3716 --------------------- : 12
sendList : 100% : 70690 ms, 99% : 70690 ms, 95 : 58226 ms, 90% : 58226 ms.
Result count 14, range 1974 ms to  70690 ms.
sendList failed peers count : 5 [26.31578947368421 %]
- Peer ID : 34:FC:EF:11:B1:66, Tried : 2
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 2
- Peer ID : 08:EC:A9:50:76:27, Tried : 2
- Peer ID : F8:95:C7:87:85:54, Tried : 2
sendList never tried peers count : 0 [0 %]
--------------- LGE-LG-D855_PT5918 --------------------- : 13
sendList : 100% : 77174 ms, 99% : 77174 ms, 95 : 77174 ms, 90% : 65948 ms.
Result count 7, range 6814 ms to  77174 ms.
sendList failed peers count : 7 [50 %]
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
sendList never tried peers count : 5 [26.31578947368421 %]
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : F8:CF:C5:D9:E5:61
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 34:FC:EF:9D:93:0B
--------------- Combined ---------------------
sendList : 100% : 88917 ms, 99% : 78916 ms, 95 : 61136 ms, 90% : 49508 ms.

--------------- end of test report ---------------------


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```
###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
STOP log received from  W3D7N15428022572 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Device test finished on W3D7N15428022572 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:null 
child process exited with code null on device f56ad48d 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/513350283842813_Work_in_progress__vjrantal/thali01_LGE-LG-H815.md)

[HUAWEI-ALE-L21](https://github.com/ThaliTester/TestResults/blob/513350283842813_Work_in_progress__vjrantal/thali01_HUAWEI-ALE-L21.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/513350283842813_Work_in_progress__vjrantal/thali01_samsung-SM-A500FU.md)

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
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/513350283842813_Work_in_progress__vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/513350283842813_Work_in_progress__vjrantal/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/513350283842813_Work_in_progress__vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/513350283842813_Work_in_progress__vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/513350283842813_Work_in_progress__vjrantal/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/513350283842813_Work_in_progress__vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/513350283842813_Work_in_progress__vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/513350283842813_Work_in_progress__vjrantal/thali04_samsung-SM-G900F.md)

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
[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/513350283842813_Work_in_progress__vjrantal/thali05_samsung-SM-N9005.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/513350283842813_Work_in_progress__vjrantal/thali05_motorola-Nexus 6.md)

[HTC-HTC One_M8](https://github.com/ThaliTester/TestResults/blob/513350283842813_Work_in_progress__vjrantal/thali05_HTC-HTC One_M8.md)

####Node name: thali06
Console output:
```
STOP log received from  022678fb504e29b0 Test has  SUCCEEDED
STOP log received from  7970f88c Test has  SUCCEEDED
Device test finished on 022678fb504e29b0 
Device test finished on 7970f88c 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:0 
child process exited with code 0 on device FA55PYS00566 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/513350283842813_Work_in_progress__vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/513350283842813_Work_in_progress__vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/513350283842813_Work_in_progress__vjrantal/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
Error: problem deploying Android apk(/home/pi/test/builder/builds/513350283842813/build_android/android_0_513350283842813.apk) to device 4db5c8cc Error: Command failed: protocol failure
- waiting for device -



Test on this node has failed but the reason wasn't the test application itself.
 Cancelling the test result on this node.

```
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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/513350283842813_Work_in_progress__vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/513350283842813_Work_in_progress__vjrantal/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
STOP log received from  CC51WYC03425 Test has  SUCCEEDED
Device test finished on 0c6a0f3c0bdb4e77 
Device test finished on CC51WYC03425 
Android task is completed. [SUCCESS]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/513350283842813_Work_in_progress__vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/513350283842813_Work_in_progress__vjrantal/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/513350283842813_Work_in_progress__vjrantal/iOS_Iphone5-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/513350283842813_Work_in_progress__vjrantal/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/513350283842813_Work_in_progress__vjrantal/iOS_Iphone6-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/513350283842813_Work_in_progress__vjrantal/iOS_IpadAir2-1.md)


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

2015-11-25T09:24:49.042Z (0 sec) - Android tests will start after waiting for 120 seconds

Test ID 0 configuration: testSendData.js, server timeout: 1200000, data:

{ timeout: '1000000',
  rounds: '1',
  dataTimeout: '10000',
  dataAmount: '100000',
  conReTryTimeout: '5000',
  conReTryCount: '5' }

2015-11-25T09:24:49.048Z (0 sec) - iOS tests will start after waiting for 120 seconds

listening on *:3000

2015-11-25T09:24:49.598Z (1 sec) - Android LGE-LG-H815_PT8316 added (current device count 1)

2015-11-25T09:24:49.652Z (1 sec) - Android HTC-HTC One_M8_PT7367 added (current device count 2)

2015-11-25T09:24:49.846Z (1 sec) - iOS Apple-Iphone6-1_PT8682 added (current device count 1)

2015-11-25T09:24:50.200Z (1 sec) - Android samsung-SM-A300FU_PT4190 added (current device count 3)

2015-11-25T09:24:50.205Z (1 sec) - Android motorola-Nexus 6_PT8656 added (current device count 4)

2015-11-25T09:24:50.258Z (1 sec) - Android HUAWEI-ALE-L21_PT5854 added (current device count 5)

2015-11-25T09:24:50.342Z (1 sec) - Android samsung-SM-A300FU_PT7055 added (current device count 6)

2015-11-25T09:24:50.442Z (1 sec) - iOS Apple-Iphone5s-1_PT1341 added (current device count 2)

2015-11-25T09:24:51.879Z (3 sec) - iOS Apple-IpadAir2-1_PT7460 added (current device count 3)

2015-11-25T09:24:52.445Z (3 sec) - iOS Apple-Iphone5-1_PT138 added (current device count 4)

2015-11-25T09:24:52.454Z (3 sec) - Android samsung-SM-G800F_PT4559 added (current device count 7)

2015-11-25T09:24:52.645Z (4 sec) - Android LGE-Nexus 5_PT3721 added (current device count 8)

2015-11-25T09:24:52.730Z (4 sec) - Android samsung-SM-G900F_PT8206 added (current device count 9)

2015-11-25T09:24:52.885Z (4 sec) - Android motorola-XT1039_PT124 added (current device count 10)

2015-11-25T09:24:53.242Z (4 sec) - Android samsung-SM-A500FU_PT6627 added (current device count 11)

2015-11-25T09:24:53.335Z (4 sec) - Android HTC-HTC Desire 820_PT8406 added (current device count 12)

2015-11-25T09:24:53.391Z (4 sec) - Android LGE-Nexus 5_PT9129 added (current device count 13)

2015-11-25T09:24:53.507Z (5 sec) - Android LGE-LG-D802_PT4529 added (current device count 14)

2015-11-25T09:24:53.709Z (5 sec) - Android samsung-SM-N9005_PT2740 added (current device count 15)

2015-11-25T09:24:53.713Z (5 sec) - Android LGE-LG-D722_PT6069 added (current device count 16)

2015-11-25T09:24:54.053Z (5 sec) - Android HTC-HTC Desire 820_PT3716 added (current device count 17)

2015-11-25T09:24:54.208Z (5 sec) - Android LGE-LG-D855_PT5918 added (current device count 18)

2015-11-25T09:24:54.938Z (6 sec) - Android samsung-SM-N910C_PT1533 added (current device count 19)

2015-11-25T09:24:59.177Z (10 sec) - Android motorola-XT1072_PT7901 added (current device count 20)

-------------- We got wait done, now starting the testing process ------------------

2015-11-25T09:26:49.089Z (120 sec) - Android start testing now with 20 devices

2015-11-25T09:26:49.121Z (120 sec) - iOS start testing now with 4 devices

2015-11-25T09:27:00.923Z (132 sec) - iOS Apple-Iphone5s-1_PT1341 test took 11799ms - results peers[0], reConnects[0], sendData[3]

2015-11-25T09:27:02.446Z (133 sec) - iOS Apple-Iphone6-1_PT8682 test took 13324ms - results peers[0], reConnects[0], sendData[3]

2015-11-25T09:27:04.800Z (136 sec) - iOS Apple-IpadAir2-1_PT7460 test took 15676ms - results peers[0], reConnects[0], sendData[3]

2015-11-25T09:27:04.857Z (136 sec) - iOS Apple-Iphone5-1_PT138 test took 15734ms - results peers[0], reConnects[0], sendData[3]

2015-11-25T09:27:04.858Z (136 sec) - iOS test ID 0 done now

2015-11-25T09:27:04.866Z (136 sec) - iOS All tests are done, preparing test report

--------------- test report ---------------------

--------------- Apple-Iphone6-1_PT8682 --------------------- : 1

sendList : 100% : 6177 ms, 99% : 6177 ms, 95 : 6177 ms, 90% : 6177 ms.

Result count 3, range 2613 ms to  6177 ms.

sendList failed peers count : 0 [0 %]

sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5s-1_PT1341 --------------------- : 2

sendList : 100% : 4473 ms, 99% : 4473 ms, 95 : 4473 ms, 90% : 4473 ms.

Result count 3, range 2752 ms to  4473 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- Apple-IpadAir2-1_PT7460 --------------------- : 3
sendList : 100% : 6202 ms, 99% : 6202 ms, 95 : 6202 ms, 90% : 6202 ms.
Result count 3, range 3651 ms to  6202 ms.

sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5-1_PT138 --------------------- : 4
sendList : 100% : 6632 ms, 99% : 6632 ms, 95 : 6632 ms, 90% : 6632 ms.

Result count 3, range 2854 ms to  6632 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- Combined ---------------------

sendList : 100% : 6632 ms, 99% : 6632 ms, 95 : 6202 ms, 90% : 6202 ms.

--------------- end of test report ---------------------

2015-11-25T09:27:58.581Z (190 sec) - Android LGE-Nexus 5_PT9129 got disconnected

2015-11-25T09:28:56.201Z (247 sec) - Android LGE-LG-D855_PT5918 got disconnected

2015-11-25T09:28:58.174Z (249 sec) - Android LGE-LG-D855_PT5918 got re-connected event

2015-11-25T09:29:26.141Z (277 sec) - Android LGE-Nexus 5_PT9129 got re-connected event

2015-11-25T09:29:40.752Z (292 sec) - Android samsung-SM-N910C_PT1533 got disconnected

2015-11-25T09:29:49.614Z (301 sec) - Android motorola-XT1072_PT7901 got disconnected

2015-11-25T09:30:03.356Z (314 sec) - Android samsung-SM-G800F_PT4559 got disconnected

2015-11-25T09:30:29.699Z (341 sec) - Android LGE-LG-D722_PT6069 got disconnected

2015-11-25T09:30:30.660Z (342 sec) - Android LGE-Nexus 5_PT9129 got re-connected event

2015-11-25T09:30:51.143Z (362 sec) - Android LGE-Nexus 5_PT9129 got disconnected

2015-11-25T09:30:59.351Z (370 sec) - Android HTC-HTC Desire 820_PT8406 got disconnected

2015-11-25T09:31:19.401Z (390 sec) - Android LGE-Nexus 5_PT9129 got re-connected event

2015-11-25T09:31:55.667Z (427 sec) - Android LGE-Nexus 5_PT9129 got disconnected

2015-11-25T09:32:05.593Z (437 sec) - Android HTC-HTC One_M8_PT7367 got re-connected event

2015-11-25T09:32:10.911Z (442 sec) - Android LGE-Nexus 5_PT9129 got re-connected event

2015-11-25T09:32:23.624Z (455 sec) - Android samsung-SM-A300FU_PT4190 got disconnected

2015-11-25T09:33:02.603Z (494 sec) - Android samsung-SM-A500FU_PT6627 got disconnected

2015-11-25T09:33:05.762Z (497 sec) - Android HTC-HTC One_M8_PT7367 got disconnected

2015-11-25T09:33:07.905Z (499 sec) - Android LGE-Nexus 5_PT9129 got re-connected event

2015-11-25T09:33:09.415Z (500 sec) - Android LGE-Nexus 5_PT9129 got disconnected

2015-11-25T09:33:35.918Z (527 sec) - Android LGE-Nexus 5_PT9129 got disconnected

2015-11-25T09:33:52.477Z (543 sec) - Android LGE-Nexus 5_PT9129 got re-connected event

2015-11-25T09:33:53.153Z (544 sec) - Android motorola-XT1039_PT124 got re-connected event

2015-11-25T09:34:01.725Z (553 sec) - Android motorola-XT1039_PT124 got disconnected

2015-11-25T09:34:32.909Z (584 sec) - Android LGE-Nexus 5_PT9129 got disconnected

2015-11-25T09:34:43.750Z (595 sec) - Android LGE-Nexus 5_PT9129 got re-connected event

2015-11-25T09:35:11.780Z (623 sec) - Android LGE-Nexus 5_PT9129 got re-connected event

2015-11-25T09:35:17.478Z (628 sec) - Android LGE-Nexus 5_PT9129 got disconnected

2015-11-25T09:35:24.000Z (635 sec) - Android HTC-HTC Desire 820_PT8406 got re-connected event

2015-11-25T09:35:46.059Z (657 sec) - Android HTC-HTC Desire 820_PT3716 got re-connected event

2015-11-25T09:36:08.751Z (680 sec) - Android LGE-Nexus 5_PT9129 got disconnected

2015-11-25T09:36:12.632Z (684 sec) - Android LGE-Nexus 5_PT9129 got re-connected event

2015-11-25T09:36:37.406Z (708 sec) - Android HTC-HTC Desire 820_PT3716 got disconnected

2015-11-25T09:37:01.732Z (733 sec) - Android LGE-Nexus 5_PT9129 got disconnected

2015-11-25T09:37:26.185Z (757 sec) - Android LGE-Nexus 5_PT9129 got re-connected event

2015-11-25T09:38:27.735Z (819 sec) - Android LGE-Nexus 5_PT9129 got disconnected

2015-11-25T09:38:32.628Z (824 sec) - Android LGE-Nexus 5_PT9129 got re-connected event

2015-11-25T09:39:16.140Z (867 sec) - Android LGE-Nexus 5_PT9129 got disconnected

2015-11-25T09:39:52.546Z (904 sec) - Android LGE-Nexus 5_PT9129 got re-connected event

2015-11-25T09:40:29.359Z (940 sec) - Android LGE-Nexus 5_PT9129 got re-connected event

2015-11-25T09:40:47.897Z (959 sec) - Android LGE-Nexus 5_PT9129 got disconnected

2015-11-25T09:41:17.548Z (989 sec) - Android LGE-Nexus 5_PT9129 got disconnected

2015-11-25T09:41:20.501Z (991 sec) - Android HTC-HTC Desire 820_PT3716 got re-connected event

2015-11-25T09:41:41.507Z (1013 sec) - Android LGE-Nexus 5_PT9129 got re-connected event

2015-11-25T09:41:48.942Z (1020 sec) - Android HTC-HTC Desire 820_PT3716 got disconnected

2015-11-25T09:41:56.306Z (1027 sec) - Android HTC-HTC Desire 820_PT8406 got re-connected event

2015-11-25T09:42:18.397Z (1049 sec) - Android LGE-Nexus 5_PT9129 got disconnected

2015-11-25T09:42:27.533Z (1059 sec) - Android LGE-Nexus 5_PT9129 got re-connected event

2015-11-25T09:42:43.062Z (1074 sec) - Android HTC-HTC Desire 820_PT8406 got disconnected

2015-11-25T09:43:29.556Z (1121 sec) - Android samsung-SM-N9005_PT2740 test took 1000443ms - results peers[0], reConnects[0], sendData[19]

2015-11-25T09:43:29.721Z (1121 sec) - Android motorola-XT1039_PT124 test took 1000613ms - results peers[0], reConnects[0], sendData[19]

2015-11-25T09:43:29.740Z (1121 sec) - Android motorola-Nexus 6_PT8656 test took 1000636ms - results peers[0], reConnects[0], sendData[19]

2015-11-25T09:43:29.812Z (1121 sec) - Android samsung-SM-A300FU_PT7055 test took 1000708ms - results peers[0], reConnects[0], sendData[19]

2015-11-25T09:43:29.843Z (1121 sec) - Android LGE-Nexus 5_PT3721 test took 1000736ms - results peers[0], reConnects[0], sendData[19]

2015-11-25T09:43:29.850Z (1121 sec) - Android LGE-LG-D802_PT4529 test took 1000738ms - results peers[0], reConnects[0], sendData[19]

2015-11-25T09:43:29.932Z (1121 sec) - Android LGE-LG-H815_PT8316 test took 1000834ms - results peers[0], reConnects[0], sendData[19]

2015-11-25T09:43:29.974Z (1121 sec) - Android LGE-LG-D855_PT5918 test took 1000860ms - results peers[0], reConnects[0], sendData[19]

2015-11-25T09:43:31.157Z (1122 sec) - Android HUAWEI-ALE-L21_PT5854 test took 1002052ms - results peers[0], reConnects[0], sendData[19]

2015-11-25T09:43:31.598Z (1123 sec) - Android LGE-Nexus 5_PT9129 got disconnected

2015-11-25T09:43:32.319Z (1123 sec) - Android samsung-SM-G900F_PT8206 test took 1003211ms - results peers[0], reConnects[0], sendData[19]

2015-11-25T09:43:33.408Z (1124 sec) - Android HTC-HTC One_M8_PT7367 test took 1004307ms - results peers[0], reConnects[0], sendData[19]

2015-11-25T09:43:35.280Z (1126 sec) - Android HTC-HTC Desire 820_PT3716 test took 1006166ms - results peers[0], reConnects[0], sendData[19]

2015-11-25T09:43:36.059Z (1127 sec) - Android HTC-HTC Desire 820_PT8406 test took 1006949ms - results peers[0], reConnects[0], sendData[19]

2015-11-25T09:43:59.230Z (1150 sec) - Android LGE-Nexus 5_PT9129 got re-connected event

2015-11-25T09:44:17.526Z (1169 sec) - Android LGE-Nexus 5_PT9129 got disconnected

2015-11-25T09:44:49.549Z (1201 sec) - Android LGE-Nexus 5_PT9129 got re-connected event

2015-11-25T09:45:49.206Z (1260 sec) - Android LGE-Nexus 5_PT9129 got disconnected

2015-11-25T09:46:49.121Z (1320 sec) - Server timeout reached!

2015-11-25T09:46:49.122Z (1320 sec) - Send timeout to samsung-SM-A300FU_PT4190
2015-11-25T09:46:49.123Z (1320 sec) - Send timeout to samsung-SM-G800F_PT4559
2015-11-25T09:46:49.124Z (1320 sec) - Send timeout to samsung-SM-A500FU_PT6627
2015-11-25T09:46:49.124Z (1320 sec) - Send timeout to LGE-Nexus 5_PT9129

2015-11-25T09:46:49.126Z (1320 sec) - Send timeout to LGE-LG-D722_PT6069

2015-11-25T09:46:49.127Z (1320 sec) - Send timeout to samsung-SM-N910C_PT1533

2015-11-25T09:46:49.128Z (1320 sec) - Send timeout to motorola-XT1072_PT7901

2015-11-25T09:47:49.130Z (1380 sec) - Did not get reports from all devices, but forcing tests to finish!

samsung-SM-A300FU_PT4190 did not have results at the end of tests - check the device logs about why!!

samsung-SM-G800F_PT4559 did not have results at the end of tests - check the device logs about why!!

samsung-SM-A500FU_PT6627 did not have results at the end of tests - check the device logs about why!!

LGE-Nexus 5_PT9129 did not have results at the end of tests - check the device logs about why!!

LGE-LG-D722_PT6069 did not have results at the end of tests - check the device logs about why!!

samsung-SM-N910C_PT1533 did not have results at the end of tests - check the device logs about why!!

motorola-XT1072_PT7901 did not have results at the end of tests - check the device logs about why!!
2015-11-25T09:47:49.169Z (1380 sec) - Android All tests are done, preparing test report
--------------- test report ---------------------
--------------- LGE-LG-H815_PT8316 --------------------- : 1
sendList : 100% : 78916 ms, 99% : 78916 ms, 95 : 49508 ms, 90% : 49508 ms.
Result count 12, range 4428 ms to  78916 ms.
sendList failed peers count : 7 [36.8421052631579 %]
- Peer ID : 34:FC:EF:11:B1:66, Tried : 2
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 2
- Peer ID : 44:80:EB:7B:5A:05, Tried : 2
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 2
sendList never tried peers count : 0 [0 %]
--------------- HTC-HTC One_M8_PT7367 --------------------- : 2
sendList : 100% : 88917 ms, 99% : 88917 ms, 95 : 70991 ms, 90% : 70991 ms.
Result count 14, range 3552 ms to  88917 ms.
sendList failed peers count : 5 [26.31578947368421 %]
- Peer ID : 58:3F:54:73:64:C0, Tried : 2
- Peer ID : 44:80:EB:7B:5A:05, Tried : 2
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 2
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 2
- Peer ID : 34:FC:EF:11:B1:66, Tried : 2
sendList never tried peers count : 0 [0 %]
--------------- motorola-Nexus 6_PT8656 --------------------- : 3

sendList : 100% : 61065 ms, 99% : 61065 ms, 95 : 20096 ms, 90% : 19682 ms.
Result count 16, range 3740 ms to  61065 ms.
sendList failed peers count : 3 [15.789473684210526 %]
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 6
- Peer ID : 44:80:EB:7B:5A:05, Tried : 5
- Peer ID : 34:FC:EF:11:B1:66, Tried : 6
sendList never tried peers count : 0 [0 %]
--------------- HUAWEI-ALE-L21_PT5854 --------------------- : 4

sendList : 100% : 22417 ms, 99% : 22417 ms, 95 : 22417 ms, 90% : 22417 ms.
Result count 5, range 5339 ms to  22417 ms.
sendList failed peers count : 6 [54.54545454545455 %]
- Peer ID : 50:2E:6C:AC:21:50, Tried : 1

- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1

- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1

sendList never tried peers count : 8 [42.10526315789474 %]

- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 7C:F9:0E:34:8A:A0

- Peer ID : F8:CF:C5:D9:E5:61
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 08:EC:A9:50:75:41

--------------- samsung-SM-A300FU_PT7055 --------------------- : 5
sendList : 100% : 54697 ms, 99% : 54697 ms, 95 : 44694 ms, 90% : 44694 ms.
Result count 11, range 2483 ms to  54697 ms.

sendList failed peers count : 8 [42.10526315789474 %]
- Peer ID : 08:EC:A9:50:76:27, Tried : 2
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1

- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 2
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 2

sendList never tried peers count : 0 [0 %]
--------------- LGE-Nexus 5_PT3721 --------------------- : 6
sendList : 100% : 87524 ms, 99% : 87524 ms, 95 : 35440 ms, 90% : 35440 ms.

Result count 15, range 2905 ms to  87524 ms.
sendList failed peers count : 4 [21.05263157894737 %]
- Peer ID : 34:FC:EF:11:B1:66, Tried : 4
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 3

- Peer ID : 44:80:EB:7B:5A:05, Tried : 3
- Peer ID : F8:95:C7:87:85:54, Tried : 3
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-G900F_PT8206 --------------------- : 7

sendList : 100% : 52389 ms, 99% : 52389 ms, 95 : 43415 ms, 90% : 38969 ms.
Result count 17, range 2819 ms to  52389 ms.
sendList failed peers count : 2 [10.526315789473685 %]

- Peer ID : 58:2A:F7:ED:96:BE, Tried : 6
- Peer ID : 34:FC:EF:11:B1:66, Tried : 6
sendList never tried peers count : 0 [0 %]
--------------- motorola-XT1039_PT124 --------------------- : 8

sendList : 100% : 52022 ms, 99% : 52022 ms, 95 : 32953 ms, 90% : 32953 ms.
Result count 12, range 2219 ms to  52022 ms.
sendList failed peers count : 7 [36.8421052631579 %]

- Peer ID : 08:EC:A9:50:76:27, Tried : 2
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 2

- Peer ID : 34:FC:EF:11:B1:66, Tried : 2
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 2
sendList never tried peers count : 0 [0 %]
--------------- HTC-HTC Desire 820_PT8406 --------------------- : 9

sendList : 100% : 33646 ms, 99% : 33646 ms, 95 : 26845 ms, 90% : 26845 ms.
Result count 11, range 2953 ms to  33646 ms.
sendList failed peers count : 8 [42.10526315789474 %]

- Peer ID : 58:3F:54:73:64:C0, Tried : 2
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1

- Peer ID : 34:FC:EF:11:B1:66, Tried : 2
- Peer ID : F8:95:C7:87:85:54, Tried : 2
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 2
- Peer ID : 44:80:EB:7B:5A:05, Tried : 2

sendList never tried peers count : 0 [0 %]
--------------- LGE-LG-D802_PT4529 --------------------- : 10
sendList : 100% : 32183 ms, 99% : 32183 ms, 95 : 30319 ms, 90% : 30319 ms.

Result count 13, range 4221 ms to  32183 ms.
sendList failed peers count : 6 [31.57894736842105 %]
- Peer ID : 58:3F:54:73:64:C0, Tried : 2
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 2
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 2

- Peer ID : F8:95:C7:87:85:54, Tried : 2
- Peer ID : 34:FC:EF:11:B1:66, Tried : 2
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 2
sendList never tried peers count : 0 [0 %]

--------------- samsung-SM-N9005_PT2740 --------------------- : 11

sendList : 100% : 69105 ms, 99% : 69105 ms, 95 : 42909 ms, 90% : 42909 ms.

Result count 13, range 2358 ms to  69105 ms.
sendList failed peers count : 6 [31.57894736842105 %]
- Peer ID : 34:FC:EF:11:B1:66, Tried : 3
- Peer ID : F8:95:C7:87:85:54, Tried : 2
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 2
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 2
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 2
- Peer ID : 44:80:EB:7B:5A:05, Tried : 2
sendList never tried peers count : 0 [0 %]
--------------- HTC-HTC Desire 820_PT3716 --------------------- : 12
sendList : 100% : 70690 ms, 99% : 70690 ms, 95 : 58226 ms, 90% : 58226 ms.
Result count 14, range 1974 ms to  70690 ms.
sendList failed peers count : 5 [26.31578947368421 %]
- Peer ID : 34:FC:EF:11:B1:66, Tried : 2
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 2
- Peer ID : 08:EC:A9:50:76:27, Tried : 2
- Peer ID : F8:95:C7:87:85:54, Tried : 2
sendList never tried peers count : 0 [0 %]
--------------- LGE-LG-D855_PT5918 --------------------- : 13
sendList : 100% : 77174 ms, 99% : 77174 ms, 95 : 77174 ms, 90% : 65948 ms.
Result count 7, range 6814 ms to  77174 ms.
sendList failed peers count : 7 [50 %]
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
sendList never tried peers count : 5 [26.31578947368421 %]
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : F8:CF:C5:D9:E5:61
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 34:FC:EF:9D:93:0B
--------------- Combined ---------------------
sendList : 100% : 88917 ms, 99% : 78916 ms, 95 : 61136 ms, 90% : 49508 ms.

--------------- end of test report ---------------------


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


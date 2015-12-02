#### Test 5227736558f1fb0 Logs

Status: 
```

ios : false

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m



server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":20}}
Test ID 0 configuration: testSendData.js, server timeout: 1200000, data:

{ timeout: 1000000,
  rounds: 1,
  dataTimeout: 10000,
  dataAmount: 100000,
  conReTryTimeout: 5000,
  conReTryCount: 5 }

2015-12-02T17:10:37.425Z (0 sec) - Android tests will start after waiting for 120 seconds

Test ID 0 configuration: testSendData.js, server timeout: 1200000, data:

{ timeout: 1000000,
  rounds: 1,
  dataTimeout: 10000,
  dataAmount: 100000,
  conReTryTimeout: 5000,
  conReTryCount: 5 }

2015-12-02T17:10:37.431Z (0 sec) - iOS tests will start after waiting for 120 seconds

listening on *:3000

2015-12-02T17:10:38.136Z (1 sec) - Android samsung-SM-A500FU_PT3412 added (current device count 1)

2015-12-02T17:10:38.455Z (1 sec) - Android samsung-SM-A300FU_PT7144 added (current device count 2)

2015-12-02T17:10:38.539Z (1 sec) - Android LGE-Nexus 5_PT5840 added (current device count 3)

2015-12-02T17:10:38.547Z (1 sec) - Android samsung-SM-G800F_PT4415 added (current device count 4)

2015-12-02T17:10:39.071Z (2 sec) - Android LGE-LG-D722_PT7815 added (current device count 5)

2015-12-02T17:10:39.423Z (2 sec) - Android HTC-HTC Desire 820_PT8680 added (current device count 6)

2015-12-02T17:10:39.446Z (2 sec) - Android samsung-SM-A300FU_PT9092 added (current device count 7)

2015-12-02T17:10:40.006Z (3 sec) - iOS Apple-Iphone6-1_PT5992 added (current device count 1)

2015-12-02T17:10:40.211Z (3 sec) - iOS Apple-IpadAir2-1_PT2754 added (current device count 2)

2015-12-02T17:10:40.521Z (3 sec) - Android LGE-Nexus 5_PT3826 added (current device count 8)

2015-12-02T17:10:40.811Z (3 sec) - Android samsung-SM-A500FU_PT7553 added (current device count 9)

2015-12-02T17:10:40.982Z (4 sec) - Android HUAWEI-ALE-L21_PT194 added (current device count 10)

2015-12-02T17:10:41.085Z (4 sec) - Android HTC-HTC Desire 820_PT4030 added (current device count 11)

2015-12-02T17:10:41.363Z (4 sec) - Android LGE-LG-D855_PT1610 added (current device count 12)

2015-12-02T17:10:41.754Z (4 sec) - Android LGE-LG-H815_PT5092 added (current device count 13)

2015-12-02T17:10:41.876Z (4 sec) - Android samsung-SM-G900F_PT1925 added (current device count 14)

2015-12-02T17:10:41.961Z (5 sec) - Android samsung-SM-G900F_PT9809 added (current device count 15)

2015-12-02T17:10:42.183Z (5 sec) - Android motorola-XT1039_PT9827 added (current device count 16)

2015-12-02T17:10:42.195Z (5 sec) - iOS Apple-Iphone5-1_PT9787 added (current device count 3)

2015-12-02T17:10:42.272Z (5 sec) - iOS Apple-Iphone5s-1_PT367 added (current device count 4)

2015-12-02T17:10:42.342Z (5 sec) - Android LGE-LG-D802_PT6776 added (current device count 17)

2015-12-02T17:10:42.541Z (5 sec) - Android motorola-XT1072_PT8055 added (current device count 18)

2015-12-02T17:10:43.580Z (6 sec) - Android samsung-SM-N910C_PT6682 added (current device count 19)

-------------- We got wait done, now starting the testing process ------------------

2015-12-02T17:12:37.477Z (120 sec) - Android start testing now with 19 devices

2015-12-02T17:12:37.503Z (120 sec) - iOS start testing now with 4 devices

2015-12-02T17:12:49.705Z (132 sec) - iOS Apple-Iphone6-1_PT5992 test took 12200ms - results peers[0], reConnects[0], sendData[3]

2015-12-02T17:12:50.576Z (133 sec) - iOS Apple-Iphone5-1_PT9787 test took 13070ms - results peers[0], reConnects[0], sendData[3]

2015-12-02T17:12:50.700Z (133 sec) - iOS Apple-IpadAir2-1_PT2754 test took 13196ms - results peers[0], reConnects[0], sendData[3]

2015-12-02T17:12:57.517Z (140 sec) - iOS Apple-Iphone5s-1_PT367 test took 20012ms - results peers[0], reConnects[0], sendData[3]

2015-12-02T17:12:57.517Z (140 sec) - iOS test ID 0 done now

2015-12-02T17:12:57.525Z (140 sec) - iOS All tests are done, preparing test report

--------------- test report ---------------------

--------------- Apple-Iphone6-1_PT5992 --------------------- : 1

sendList : 100% : 4590 ms, 99% : 4590 ms, 95 : 4590 ms, 90% : 4590 ms.

Average data rate: 0.029 MB/s

Result count 3, range 2747 ms to  4590 ms.

sendList failed peers count : 0 [0 %]

sendList never tried peers count : 0 [0 %]

--------------- Apple-IpadAir2-1_PT2754 --------------------- : 2
sendList : 100% : 5049 ms, 99% : 5049 ms, 95 : 5049 ms, 90% : 5049 ms.

Average data rate: 0.025 MB/s
Result count 3, range 3503 ms to  5049 ms.
sendList failed peers count : 0 [0 %]

sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5-1_PT9787 --------------------- : 3

sendList : 100% : 4117 ms, 99% : 4117 ms, 95 : 4117 ms, 90% : 4117 ms.
Average data rate: 0.026 MB/s
Result count 3, range 3687 ms to  4117 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5s-1_PT367 --------------------- : 4
sendList : 100% : 8381 ms, 99% : 8381 ms, 95 : 8381 ms, 90% : 8381 ms.

Average data rate: 0.019 MB/s
Result count 3, range 3544 ms to  8381 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------

sendList : 100% : 8381 ms, 99% : 8381 ms, 95 : 5049 ms, 90% : 5049 ms.

Average data rate: 0.024 MB/s
--------------- end of test report ---------------------

2015-12-02T17:12:58.049Z (141 sec) - iOS Apple-Iphone6-1_PT5992 got disconnected

2015-12-02T17:12:58.069Z (141 sec) - iOS Apple-Iphone5-1_PT9787 got disconnected

2015-12-02T17:12:58.075Z (141 sec) - iOS Apple-Iphone5s-1_PT367 got disconnected

2015-12-02T17:12:58.385Z (141 sec) - iOS Apple-IpadAir2-1_PT2754 got disconnected

2015-12-02T17:13:29.360Z (172 sec) - Android LGE-LG-D722_PT7815 got re-connected event

2015-12-02T17:13:38.258Z (181 sec) - Android LGE-Nexus 5_PT5840 got re-connected event

2015-12-02T17:14:08.776Z (211 sec) - Android samsung-SM-G800F_PT4415 got disconnected

2015-12-02T17:14:08.885Z (212 sec) - Android LGE-Nexus 5_PT5840 got disconnected

2015-12-02T17:14:09.154Z (212 sec) - Android LGE-LG-D722_PT7815 got disconnected

2015-12-02T17:14:26.028Z (229 sec) - Android LGE-LG-D722_PT7815 got re-connected event

2015-12-02T17:14:29.228Z (232 sec) - Android LGE-LG-D722_PT7815 got disconnected

2015-12-02T17:14:37.721Z (240 sec) - Android motorola-XT1039_PT9827 got disconnected

2015-12-02T17:14:43.528Z (246 sec) - Android LGE-LG-D802_PT6776 got re-connected event

2015-12-02T17:15:03.262Z (266 sec) - Android LGE-Nexus 5_PT5840 got disconnected

2015-12-02T17:15:03.635Z (266 sec) - Android LGE-LG-D802_PT6776 got disconnected

2015-12-02T17:15:05.401Z (268 sec) - Android LGE-LG-D855_PT1610 got re-connected event

2015-12-02T17:15:32.298Z (295 sec) - Android motorola-XT1072_PT8055 got re-connected event

2015-12-02T17:15:58.245Z (321 sec) - Android LGE-LG-D855_PT1610 got disconnected

2015-12-02T17:16:16.672Z (339 sec) - Android LGE-LG-D722_PT7815 got re-connected event

2015-12-02T17:16:22.965Z (346 sec) - Android motorola-XT1039_PT9827 got re-connected event

2015-12-02T17:16:23.396Z (346 sec) - Android motorola-XT1072_PT8055 got disconnected

2015-12-02T17:17:06.868Z (389 sec) - Android LGE-LG-D722_PT7815 got disconnected

2015-12-02T17:17:35.180Z (418 sec) - Android HTC-HTC Desire 820_PT4030 got disconnected

2015-12-02T17:17:41.676Z (424 sec) - Android LGE-LG-D722_PT7815 got disconnected

2015-12-02T17:18:08.939Z (452 sec) - Android motorola-XT1039_PT9827 got disconnected

2015-12-02T17:18:10.904Z (454 sec) - Android motorola-XT1039_PT9827 got re-connected event

2015-12-02T17:18:13.560Z (456 sec) - Android LGE-LG-D722_PT7815 got re-connected event

2015-12-02T17:18:15.766Z (458 sec) - Android samsung-SM-G900F_PT9809 test took 338270ms - results peers[0], reConnects[0], sendData[18]

2015-12-02T17:18:25.283Z (468 sec) - Android samsung-SM-N910C_PT6682 got disconnected

2015-12-02T17:19:14.103Z (517 sec) - Android LGE-LG-D722_PT7815 got re-connected event

2015-12-02T17:19:14.184Z (517 sec) - Android HTC-HTC Desire 820_PT8680 got disconnected

2015-12-02T17:19:29.287Z (532 sec) - Android HTC-HTC Desire 820_PT8680 got re-connected event

2015-12-02T17:19:32.102Z (535 sec) - Android LGE-Nexus 5_PT5840 got re-connected event

2015-12-02T17:20:03.565Z (566 sec) - Android LGE-LG-D722_PT7815 got disconnected

2015-12-02T17:20:10.409Z (573 sec) - Android HTC-HTC Desire 820_PT4030 got re-connected event

2015-12-02T17:20:16.454Z (579 sec) - Android LGE-LG-D722_PT7815 got re-connected event

2015-12-02T17:20:35.257Z (598 sec) - Android motorola-XT1039_PT9827 got re-connected event

2015-12-02T17:21:04.615Z (627 sec) - Android LGE-LG-D722_PT7815 got disconnected

2015-12-02T17:21:18.897Z (642 sec) - Android motorola-XT1039_PT9827 got disconnected

2015-12-02T17:21:47.218Z (670 sec) - Android LGE-Nexus 5_PT5840 got disconnected

2015-12-02T17:21:49.061Z (672 sec) - Android LGE-LG-D802_PT6776 got disconnected

2015-12-02T17:21:52.470Z (675 sec) - Android samsung-SM-A500FU_PT7553 got disconnected

2015-12-02T17:22:09.041Z (692 sec) - Android LGE-LG-D802_PT6776 got re-connected event

2015-12-02T17:24:07.399Z (810 sec) - Android LGE-LG-D855_PT1610 got disconnected

2015-12-02T17:24:21.042Z (824 sec) - Android LGE-LG-D722_PT7815 got re-connected event

2015-12-02T17:24:36.856Z (839 sec) - Android HTC-HTC Desire 820_PT4030 got disconnected

2015-12-02T17:25:15.473Z (878 sec) - Android LGE-LG-D722_PT7815 got disconnected

2015-12-02T17:25:17.983Z (881 sec) - Android LGE-LG-D855_PT1610 got re-connected event

2015-12-02T17:25:20.255Z (883 sec) - Android HTC-HTC Desire 820_PT4030 got re-connected event

2015-12-02T17:25:38.942Z (902 sec) - Android samsung-SM-A300FU_PT9092 got disconnected

2015-12-02T17:25:57.598Z (920 sec) - Android LGE-Nexus 5_PT5840 got re-connected event

2015-12-02T17:26:40.314Z (963 sec) - Android LGE-LG-D722_PT7815 got re-connected event

2015-12-02T17:27:28.314Z (1011 sec) - Android LGE-LG-D722_PT7815 got disconnected

2015-12-02T17:27:36.503Z (1019 sec) - Android motorola-XT1039_PT9827 got disconnected

2015-12-02T17:28:04.072Z (1047 sec) - Android HTC-HTC Desire 820_PT4030 got disconnected

2015-12-02T17:28:05.176Z (1048 sec) - Android HTC-HTC Desire 820_PT4030 got re-connected event

2015-12-02T17:28:12.981Z (1056 sec) - Android LGE-LG-D722_PT7815 got re-connected event

2015-12-02T17:28:12.995Z (1056 sec) - Android LGE-Nexus 5_PT5840 got disconnected

2015-12-02T17:28:44.779Z (1087 sec) - Android LGE-LG-D802_PT6776 got re-connected event

2015-12-02T17:28:44.883Z (1087 sec) - Android samsung-SM-G900F_PT1925 got disconnected

2015-12-02T17:28:48.548Z (1091 sec) - Android LGE-LG-D855_PT1610 got re-connected event

2015-12-02T17:28:55.383Z (1098 sec) - Android motorola-XT1039_PT9827 got re-connected event

2015-12-02T17:29:15.264Z (1118 sec) - Android HTC-HTC Desire 820_PT4030 got re-connected event

2015-12-02T17:29:17.776Z (1120 sec) - Android samsung-SM-A500FU_PT3412 test took 1000293ms - results peers[0], reConnects[0], sendData[18]

2015-12-02T17:29:17.905Z (1121 sec) - Android LGE-Nexus 5_PT3826 test took 1000414ms - results peers[0], reConnects[0], sendData[18]

2015-12-02T17:29:18.055Z (1121 sec) - Android samsung-SM-A300FU_PT7144 test took 1000570ms - results peers[0], reConnects[0], sendData[18]

2015-12-02T17:29:18.279Z (1121 sec) - Android HTC-HTC Desire 820_PT4030 test took 1000786ms - results peers[0], reConnects[0], sendData[18]

2015-12-02T17:29:18.535Z (1121 sec) - Android LGE-LG-H815_PT5092 test took 1001041ms - results peers[0], reConnects[0], sendData[18]

2015-12-02T17:29:19.409Z (1122 sec) - Android HUAWEI-ALE-L21_PT194 test took 1001917ms - results peers[0], reConnects[0], sendData[18]

2015-12-02T17:29:20.331Z (1123 sec) - Android LGE-LG-D722_PT7815 got disconnected

2015-12-02T17:29:20.667Z (1123 sec) - Android HTC-HTC Desire 820_PT8680 test took 1003179ms - results peers[0], reConnects[0], sendData[18]

2015-12-02T17:29:21.293Z (1124 sec) - Android LGE-LG-D802_PT6776 test took 1003795ms - results peers[0], reConnects[0], sendData[18]

2015-12-02T17:29:25.370Z (1128 sec) - Android LGE-LG-D855_PT1610 test took 1007877ms - results peers[0], reConnects[0], sendData[18]

2015-12-02T17:29:27.244Z (1130 sec) - Android LGE-LG-D802_PT6776 got disconnected

2015-12-02T17:29:30.121Z (1133 sec) - Android LGE-LG-D722_PT7815 got re-connected event

2015-12-02T17:29:30.145Z (1133 sec) - Android LGE-LG-D722_PT7815 test took 1012658ms - results peers[0], reConnects[0], sendData[18]

2015-12-02T17:29:32.303Z (1135 sec) - Android motorola-XT1072_PT8055 got disconnected

2015-12-02T17:29:43.853Z (1146 sec) - Android motorola-XT1072_PT8055 got re-connected event

2015-12-02T17:29:43.869Z (1146 sec) - Android motorola-XT1072_PT8055 test took 1026372ms - results peers[0], reConnects[0], sendData[18]

2015-12-02T17:29:43.871Z (1146 sec) - Android LGE-LG-D855_PT1610 got disconnected

2015-12-02T17:29:48.961Z (1152 sec) - Android motorola-XT1039_PT9827 got re-connected event

2015-12-02T17:29:48.991Z (1152 sec) - Android motorola-XT1039_PT9827 test took 1031495ms - results peers[0], reConnects[0], sendData[18]

2015-12-02T17:29:55.436Z (1158 sec) - Android HTC-HTC Desire 820_PT4030 got disconnected

2015-12-02T17:30:20.383Z (1183 sec) - Android motorola-XT1039_PT9827 got disconnected

2015-12-02T17:30:28.027Z (1191 sec) - Android LGE-LG-D722_PT7815 got disconnected

2015-12-02T17:32:31.400Z (1314 sec) - Android LGE-Nexus 5_PT5840 got re-connected event

2015-12-02T17:32:31.424Z (1314 sec) - Android LGE-Nexus 5_PT5840 test took 1193938ms - results peers[0], reConnects[0], sendData[18]

2015-12-02T17:32:37.500Z (1320 sec) - Server timeout reached!

2015-12-02T17:32:37.501Z (1320 sec) - Send timeout to samsung-SM-G800F_PT4415

2015-12-02T17:32:37.507Z (1320 sec) - Send timeout to samsung-SM-A300FU_PT9092

2015-12-02T17:32:37.508Z (1320 sec) - Send timeout to samsung-SM-A500FU_PT7553

2015-12-02T17:32:37.511Z (1320 sec) - Send timeout to samsung-SM-G900F_PT1925
2015-12-02T17:32:37.512Z (1320 sec) - Send timeout to samsung-SM-N910C_PT6682

2015-12-02T17:33:37.514Z (1380 sec) - Did not get reports from all devices, but forcing tests to finish!

samsung-SM-G800F_PT4415 did not have results at the end of tests - check the device logs about why!!

samsung-SM-A300FU_PT9092 did not have results at the end of tests - check the device logs about why!!

samsung-SM-A500FU_PT7553 did not have results at the end of tests - check the device logs about why!!

samsung-SM-G900F_PT1925 did not have results at the end of tests - check the device logs about why!!

samsung-SM-N910C_PT6682 did not have results at the end of tests - check the device logs about why!!

2015-12-02T17:33:37.540Z (1380 sec) - Android All tests are done, preparing test report

--------------- test report ---------------------

--------------- samsung-SM-A500FU_PT3412 --------------------- : 1
sendList : 100% : 97832 ms, 99% : 97832 ms, 95 : 79553 ms, 90% : 70565 ms.

Average data rate: 0.003 MB/s
Result count 16, range 3555 ms to  97832 ms.
sendList failed peers count : 2 [11.11111111111111 %]

- Peer ID : F8:95:C7:87:3C:51, Tried : 3

- Peer ID : 58:2A:F7:ED:96:BE, Tried : 2
sendList never tried peers count : 0 [0 %]

--------------- samsung-SM-A300FU_PT7144 --------------------- : 2
sendList : 100% : 86142 ms, 99% : 86142 ms, 95 : 72469 ms, 90% : 71704 ms.

Average data rate: 0.003 MB/s
Result count 16, range 2110 ms to  86142 ms.
sendList failed peers count : 2 [11.11111111111111 %]

- Peer ID : 58:2A:F7:ED:96:BE, Tried : 3
- Peer ID : F8:95:C7:87:3C:51, Tried : 3
sendList never tried peers count : 0 [0 %]

--------------- LGE-Nexus 5_PT5840 --------------------- : 3
sendList : 100% : 59225 ms, 99% : 59225 ms, 95 : 42922 ms, 90% : 42922 ms.

Average data rate: 0.007 MB/s
Result count 15, range 2516 ms to  59225 ms.
sendList failed peers count : 3 [16.666666666666668 %]

- Peer ID : 08:EC:A9:50:76:27, Tried : 4
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 3
- Peer ID : F8:95:C7:87:3C:51, Tried : 4

sendList never tried peers count : 0 [0 %]
--------------- LGE-LG-D722_PT7815 --------------------- : 4
sendList : 100% : 65779 ms, 99% : 65779 ms, 95 : 59019 ms, 90% : 53643 ms.

Average data rate: 0.004 MB/s
Result count 16, range 6447 ms to  65779 ms.
sendList failed peers count : 2 [11.11111111111111 %]

- Peer ID : F8:95:C7:87:3C:51, Tried : 4
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 4
sendList never tried peers count : 0 [0 %]

--------------- HTC-HTC Desire 820_PT8680 --------------------- : 5
sendList : 100% : 63363 ms, 99% : 63363 ms, 95 : 57378 ms, 90% : 57378 ms.

Average data rate: 0.004 MB/s
Result count 15, range 2146 ms to  63363 ms.
sendList failed peers count : 3 [16.666666666666668 %]

- Peer ID : 58:2A:F7:ED:96:BE, Tried : 3
- Peer ID : F8:95:C7:87:3C:51, Tried : 3
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 3
sendList never tried peers count : 0 [0 %]

--------------- LGE-Nexus 5_PT3826 --------------------- : 6
sendList : 100% : 79390 ms, 99% : 79390 ms, 95 : 41967 ms, 90% : 41553 ms.
Average data rate: 0.005 MB/s
Result count 16, range 3214 ms to  79390 ms.
sendList failed peers count : 2 [11.11111111111111 %]
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 5
- Peer ID : F8:95:C7:87:3C:51, Tried : 4
sendList never tried peers count : 0 [0 %]
--------------- HUAWEI-ALE-L21_PT194 --------------------- : 7
sendList : 100% : 104527 ms, 99% : 104527 ms, 95 : 104527 ms, 90% : 104527 ms.
Average data rate: 0.002 MB/s
Result count 5, range 8504 ms to  104527 ms.
sendList failed peers count : 8 [61.53846153846154 %]
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 7C:F9:0E:51:18:22, Tried : 1
sendList never tried peers count : 5 [27.77777777777778 %]
- Peer ID : 08:EC:A9:50:76:27

- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : B4:CE:F6:AB:A4:6A
--------------- HTC-HTC Desire 820_PT4030 --------------------- : 8

sendList : 100% : 85528 ms, 99% : 85528 ms, 95 : 77132 ms, 90% : 75392 ms.

Average data rate: 0.004 MB/s
Result count 16, range 3550 ms to  85528 ms.
sendList failed peers count : 2 [11.11111111111111 %]
- Peer ID : F8:95:C7:87:3C:51, Tried : 4
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 4

sendList never tried peers count : 0 [0 %]
--------------- LGE-LG-D855_PT1610 --------------------- : 9

sendList : 100% : 103273 ms, 99% : 103273 ms, 95 : 53386 ms, 90% : 43079 ms.
Average data rate: 0.004 MB/s
Result count 16, range 4747 ms to  103273 ms.

sendList failed peers count : 2 [11.11111111111111 %]
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 3
- Peer ID : F8:95:C7:87:3C:51, Tried : 3
sendList never tried peers count : 0 [0 %]

--------------- LGE-LG-H815_PT5092 --------------------- : 10
sendList : 100% : 17683 ms, 99% : 17683 ms, 95 : 17683 ms, 90% : 17683 ms.

Average data rate: 0.009 MB/s
Result count 5, range 3326 ms to  17683 ms.
sendList failed peers count : 11 [68.75 %]
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1

- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1

- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1

- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 7C:F9:0E:51:18:22, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
sendList never tried peers count : 2 [11.11111111111111 %]
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 08:EC:A9:50:76:27
--------------- samsung-SM-G900F_PT9809 --------------------- : 11
sendList : 100% : 47646 ms, 99% : 47646 ms, 95 : 37563 ms, 90% : 36868 ms.
Average data rate: 0.005 MB/s
Result count 18, range 2944 ms to  47646 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- motorola-XT1039_PT9827 --------------------- : 12
sendList : 100% : 45476 ms, 99% : 45476 ms, 95 : 43157 ms, 90% : 30618 ms.
Average data rate: 0.006 MB/s
Result count 16, range 2665 ms to  45476 ms.
sendList failed peers count : 2 [11.11111111111111 %]
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 6
- Peer ID : F8:95:C7:87:3C:51, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- LGE-LG-D802_PT6776 --------------------- : 13
sendList : 100% : 55173 ms, 99% : 55173 ms, 95 : 40248 ms, 90% : 30989 ms.
Average data rate: 0.005 MB/s
Result count 16, range 3951 ms to  55173 ms.
sendList failed peers count : 2 [11.11111111111111 %]
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 4
- Peer ID : F8:95:C7:87:3C:51, Tried : 4
sendList never tried peers count : 0 [0 %]
--------------- motorola-XT1072_PT8055 --------------------- : 14
sendList : 100% : 104483 ms, 99% : 104483 ms, 95 : 102560 ms, 90% : 89600 ms.
Average data rate: 0.003 MB/s
Result count 16, range 4774 ms to  104483 ms.
sendList failed peers count : 2 [11.11111111111111 %]
- Peer ID : F8:95:C7:87:3C:51, Tried : 3
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 3
sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------
sendList : 100% : 104527 ms, 99% : 103273 ms, 95 : 77132 ms, 90% : 59019 ms.
Average data rate: 0.004 MB/s
--------------- end of test report ---------------------

2015-12-02T17:33:37.809Z (1380 sec) - Android samsung-SM-A500FU_PT3412 got disconnected

2015-12-02T17:33:37.836Z (1380 sec) - Android samsung-SM-A300FU_PT7144 got disconnected

2015-12-02T17:33:37.934Z (1381 sec) - Android LGE-Nexus 5_PT5840 got disconnected

2015-12-02T17:33:37.952Z (1381 sec) - Android samsung-SM-G900F_PT9809 got disconnected

2015-12-02T17:33:37.997Z (1381 sec) - Android LGE-LG-D802_PT6776 got disconnected

2015-12-02T17:33:38.007Z (1381 sec) - Android LGE-LG-H815_PT5092 got disconnected

2015-12-02T17:33:38.060Z (1381 sec) - Android HUAWEI-ALE-L21_PT194 got disconnected

2015-12-02T17:33:38.128Z (1381 sec) - Android LGE-Nexus 5_PT3826 got disconnected

2015-12-02T17:33:38.360Z (1381 sec) - Android LGE-LG-D855_PT1610 got disconnected

2015-12-02T17:33:38.438Z (1381 sec) - Android motorola-XT1072_PT8055 got disconnected

2015-12-02T17:34:41.311Z (1444 sec) - Android LGE-LG-D722_PT7815 got disconnected

2015-12-02T17:34:52.622Z (1455 sec) - Android HTC-HTC Desire 820_PT4030 got disconnected

2015-12-02T17:34:58.278Z (1461 sec) - Android HTC-HTC Desire 820_PT8680 got disconnected

2015-12-02T17:35:00.024Z (1463 sec) - Android motorola-XT1039_PT9827 got disconnected


 
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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/5227736558f1fb0_Story_001_tompaana_345_tompaana/thali01_LGE-LG-H815.md)

[HUAWEI-ALE-L21](https://github.com/ThaliTester/TestResults/blob/5227736558f1fb0_Story_001_tompaana_345_tompaana/thali01_HUAWEI-ALE-L21.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/5227736558f1fb0_Story_001_tompaana_345_tompaana/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/5227736558f1fb0_Story_001_tompaana_345_tompaana/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/5227736558f1fb0_Story_001_tompaana_345_tompaana/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
STOP log received from  TA4750HV7I Test has  SUCCEEDED
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
Device test finished on TA4750HV7I 
Device test finished on LGD8553bed2d08 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:null 
child process exited with code null on device 320414cd475f91e3 
Android task is completed. [FAILED]
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/5227736558f1fb0_Story_001_tompaana_345_tompaana/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/5227736558f1fb0_Story_001_tompaana_345_tompaana/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/5227736558f1fb0_Story_001_tompaana_345_tompaana/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on ZX1C223JKW 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Error! Unexpected exit on device 0be0c6c6 app:com.test.thalitest code:null 
child process exited with code null on device 0be0c6c6 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/5227736558f1fb0_Story_001_tompaana_345_tompaana/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/5227736558f1fb0_Story_001_tompaana_345_tompaana/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/5227736558f1fb0_Story_001_tompaana_345_tompaana/thali04_samsung-SM-G900F.md)

####Node name: thali06
Console output:
```
STOP log received from  7970f88c Test has  SUCCEEDED
STOP log received from  022678fb504e29b0 Test has  SUCCEEDED
Device test finished on 7970f88c 
Device test finished on 022678fb504e29b0 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:0 
child process exited with code 0 on device FA55PYS00566 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/5227736558f1fb0_Story_001_tompaana_345_tompaana/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/5227736558f1fb0_Story_001_tompaana_345_tompaana/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/5227736558f1fb0_Story_001_tompaana_345_tompaana/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
STOP log received from  4db5c8cc Test has  SUCCEEDED
STOP log received from  c5afcdcb Test has  SUCCEEDED
Device test finished on 4db5c8cc 
Device test finished on c5afcdcb 
Android task is completed. [SUCCESS]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/5227736558f1fb0_Story_001_tompaana_345_tompaana/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/5227736558f1fb0_Story_001_tompaana_345_tompaana/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/5227736558f1fb0_Story_001_tompaana_345_tompaana/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/5227736558f1fb0_Story_001_tompaana_345_tompaana/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
Device test finished on 0c6a0f3c0bdb4e77 
STOP log received from  CC51WYC03425 Test has  SUCCEEDED
Device test finished on CC51WYC03425 
Android task is completed. [SUCCESS]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/5227736558f1fb0_Story_001_tompaana_345_tompaana/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/5227736558f1fb0_Story_001_tompaana_345_tompaana/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/5227736558f1fb0_Story_001_tompaana_345_tompaana/iOS_Iphone5-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/5227736558f1fb0_Story_001_tompaana_345_tompaana/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/5227736558f1fb0_Story_001_tompaana_345_tompaana/iOS_Iphone6-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/5227736558f1fb0_Story_001_tompaana_345_tompaana/iOS_IpadAir2-1.md)


#### Integration Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":20}}
Test ID 0 configuration: testSendData.js, server timeout: 1200000, data:

{ timeout: 1000000,
  rounds: 1,
  dataTimeout: 10000,
  dataAmount: 100000,
  conReTryTimeout: 5000,
  conReTryCount: 5 }

2015-12-02T17:10:37.425Z (0 sec) - Android tests will start after waiting for 120 seconds

Test ID 0 configuration: testSendData.js, server timeout: 1200000, data:

{ timeout: 1000000,
  rounds: 1,
  dataTimeout: 10000,
  dataAmount: 100000,
  conReTryTimeout: 5000,
  conReTryCount: 5 }

2015-12-02T17:10:37.431Z (0 sec) - iOS tests will start after waiting for 120 seconds

listening on *:3000

2015-12-02T17:10:38.136Z (1 sec) - Android samsung-SM-A500FU_PT3412 added (current device count 1)

2015-12-02T17:10:38.455Z (1 sec) - Android samsung-SM-A300FU_PT7144 added (current device count 2)

2015-12-02T17:10:38.539Z (1 sec) - Android LGE-Nexus 5_PT5840 added (current device count 3)

2015-12-02T17:10:38.547Z (1 sec) - Android samsung-SM-G800F_PT4415 added (current device count 4)

2015-12-02T17:10:39.071Z (2 sec) - Android LGE-LG-D722_PT7815 added (current device count 5)

2015-12-02T17:10:39.423Z (2 sec) - Android HTC-HTC Desire 820_PT8680 added (current device count 6)

2015-12-02T17:10:39.446Z (2 sec) - Android samsung-SM-A300FU_PT9092 added (current device count 7)

2015-12-02T17:10:40.006Z (3 sec) - iOS Apple-Iphone6-1_PT5992 added (current device count 1)

2015-12-02T17:10:40.211Z (3 sec) - iOS Apple-IpadAir2-1_PT2754 added (current device count 2)

2015-12-02T17:10:40.521Z (3 sec) - Android LGE-Nexus 5_PT3826 added (current device count 8)

2015-12-02T17:10:40.811Z (3 sec) - Android samsung-SM-A500FU_PT7553 added (current device count 9)

2015-12-02T17:10:40.982Z (4 sec) - Android HUAWEI-ALE-L21_PT194 added (current device count 10)

2015-12-02T17:10:41.085Z (4 sec) - Android HTC-HTC Desire 820_PT4030 added (current device count 11)

2015-12-02T17:10:41.363Z (4 sec) - Android LGE-LG-D855_PT1610 added (current device count 12)

2015-12-02T17:10:41.754Z (4 sec) - Android LGE-LG-H815_PT5092 added (current device count 13)

2015-12-02T17:10:41.876Z (4 sec) - Android samsung-SM-G900F_PT1925 added (current device count 14)

2015-12-02T17:10:41.961Z (5 sec) - Android samsung-SM-G900F_PT9809 added (current device count 15)

2015-12-02T17:10:42.183Z (5 sec) - Android motorola-XT1039_PT9827 added (current device count 16)

2015-12-02T17:10:42.195Z (5 sec) - iOS Apple-Iphone5-1_PT9787 added (current device count 3)

2015-12-02T17:10:42.272Z (5 sec) - iOS Apple-Iphone5s-1_PT367 added (current device count 4)

2015-12-02T17:10:42.342Z (5 sec) - Android LGE-LG-D802_PT6776 added (current device count 17)

2015-12-02T17:10:42.541Z (5 sec) - Android motorola-XT1072_PT8055 added (current device count 18)

2015-12-02T17:10:43.580Z (6 sec) - Android samsung-SM-N910C_PT6682 added (current device count 19)

-------------- We got wait done, now starting the testing process ------------------

2015-12-02T17:12:37.477Z (120 sec) - Android start testing now with 19 devices

2015-12-02T17:12:37.503Z (120 sec) - iOS start testing now with 4 devices

2015-12-02T17:12:49.705Z (132 sec) - iOS Apple-Iphone6-1_PT5992 test took 12200ms - results peers[0], reConnects[0], sendData[3]

2015-12-02T17:12:50.576Z (133 sec) - iOS Apple-Iphone5-1_PT9787 test took 13070ms - results peers[0], reConnects[0], sendData[3]

2015-12-02T17:12:50.700Z (133 sec) - iOS Apple-IpadAir2-1_PT2754 test took 13196ms - results peers[0], reConnects[0], sendData[3]

2015-12-02T17:12:57.517Z (140 sec) - iOS Apple-Iphone5s-1_PT367 test took 20012ms - results peers[0], reConnects[0], sendData[3]

2015-12-02T17:12:57.517Z (140 sec) - iOS test ID 0 done now

2015-12-02T17:12:57.525Z (140 sec) - iOS All tests are done, preparing test report

--------------- test report ---------------------

--------------- Apple-Iphone6-1_PT5992 --------------------- : 1

sendList : 100% : 4590 ms, 99% : 4590 ms, 95 : 4590 ms, 90% : 4590 ms.

Average data rate: 0.029 MB/s

Result count 3, range 2747 ms to  4590 ms.

sendList failed peers count : 0 [0 %]

sendList never tried peers count : 0 [0 %]

--------------- Apple-IpadAir2-1_PT2754 --------------------- : 2
sendList : 100% : 5049 ms, 99% : 5049 ms, 95 : 5049 ms, 90% : 5049 ms.

Average data rate: 0.025 MB/s
Result count 3, range 3503 ms to  5049 ms.
sendList failed peers count : 0 [0 %]

sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5-1_PT9787 --------------------- : 3

sendList : 100% : 4117 ms, 99% : 4117 ms, 95 : 4117 ms, 90% : 4117 ms.
Average data rate: 0.026 MB/s
Result count 3, range 3687 ms to  4117 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5s-1_PT367 --------------------- : 4
sendList : 100% : 8381 ms, 99% : 8381 ms, 95 : 8381 ms, 90% : 8381 ms.

Average data rate: 0.019 MB/s
Result count 3, range 3544 ms to  8381 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------

sendList : 100% : 8381 ms, 99% : 8381 ms, 95 : 5049 ms, 90% : 5049 ms.

Average data rate: 0.024 MB/s
--------------- end of test report ---------------------

2015-12-02T17:12:58.049Z (141 sec) - iOS Apple-Iphone6-1_PT5992 got disconnected

2015-12-02T17:12:58.069Z (141 sec) - iOS Apple-Iphone5-1_PT9787 got disconnected

2015-12-02T17:12:58.075Z (141 sec) - iOS Apple-Iphone5s-1_PT367 got disconnected

2015-12-02T17:12:58.385Z (141 sec) - iOS Apple-IpadAir2-1_PT2754 got disconnected

2015-12-02T17:13:29.360Z (172 sec) - Android LGE-LG-D722_PT7815 got re-connected event

2015-12-02T17:13:38.258Z (181 sec) - Android LGE-Nexus 5_PT5840 got re-connected event

2015-12-02T17:14:08.776Z (211 sec) - Android samsung-SM-G800F_PT4415 got disconnected

2015-12-02T17:14:08.885Z (212 sec) - Android LGE-Nexus 5_PT5840 got disconnected

2015-12-02T17:14:09.154Z (212 sec) - Android LGE-LG-D722_PT7815 got disconnected

2015-12-02T17:14:26.028Z (229 sec) - Android LGE-LG-D722_PT7815 got re-connected event

2015-12-02T17:14:29.228Z (232 sec) - Android LGE-LG-D722_PT7815 got disconnected

2015-12-02T17:14:37.721Z (240 sec) - Android motorola-XT1039_PT9827 got disconnected

2015-12-02T17:14:43.528Z (246 sec) - Android LGE-LG-D802_PT6776 got re-connected event

2015-12-02T17:15:03.262Z (266 sec) - Android LGE-Nexus 5_PT5840 got disconnected

2015-12-02T17:15:03.635Z (266 sec) - Android LGE-LG-D802_PT6776 got disconnected

2015-12-02T17:15:05.401Z (268 sec) - Android LGE-LG-D855_PT1610 got re-connected event

2015-12-02T17:15:32.298Z (295 sec) - Android motorola-XT1072_PT8055 got re-connected event

2015-12-02T17:15:58.245Z (321 sec) - Android LGE-LG-D855_PT1610 got disconnected

2015-12-02T17:16:16.672Z (339 sec) - Android LGE-LG-D722_PT7815 got re-connected event

2015-12-02T17:16:22.965Z (346 sec) - Android motorola-XT1039_PT9827 got re-connected event

2015-12-02T17:16:23.396Z (346 sec) - Android motorola-XT1072_PT8055 got disconnected

2015-12-02T17:17:06.868Z (389 sec) - Android LGE-LG-D722_PT7815 got disconnected

2015-12-02T17:17:35.180Z (418 sec) - Android HTC-HTC Desire 820_PT4030 got disconnected

2015-12-02T17:17:41.676Z (424 sec) - Android LGE-LG-D722_PT7815 got disconnected

2015-12-02T17:18:08.939Z (452 sec) - Android motorola-XT1039_PT9827 got disconnected

2015-12-02T17:18:10.904Z (454 sec) - Android motorola-XT1039_PT9827 got re-connected event

2015-12-02T17:18:13.560Z (456 sec) - Android LGE-LG-D722_PT7815 got re-connected event

2015-12-02T17:18:15.766Z (458 sec) - Android samsung-SM-G900F_PT9809 test took 338270ms - results peers[0], reConnects[0], sendData[18]

2015-12-02T17:18:25.283Z (468 sec) - Android samsung-SM-N910C_PT6682 got disconnected

2015-12-02T17:19:14.103Z (517 sec) - Android LGE-LG-D722_PT7815 got re-connected event

2015-12-02T17:19:14.184Z (517 sec) - Android HTC-HTC Desire 820_PT8680 got disconnected

2015-12-02T17:19:29.287Z (532 sec) - Android HTC-HTC Desire 820_PT8680 got re-connected event

2015-12-02T17:19:32.102Z (535 sec) - Android LGE-Nexus 5_PT5840 got re-connected event

2015-12-02T17:20:03.565Z (566 sec) - Android LGE-LG-D722_PT7815 got disconnected

2015-12-02T17:20:10.409Z (573 sec) - Android HTC-HTC Desire 820_PT4030 got re-connected event

2015-12-02T17:20:16.454Z (579 sec) - Android LGE-LG-D722_PT7815 got re-connected event

2015-12-02T17:20:35.257Z (598 sec) - Android motorola-XT1039_PT9827 got re-connected event

2015-12-02T17:21:04.615Z (627 sec) - Android LGE-LG-D722_PT7815 got disconnected

2015-12-02T17:21:18.897Z (642 sec) - Android motorola-XT1039_PT9827 got disconnected

2015-12-02T17:21:47.218Z (670 sec) - Android LGE-Nexus 5_PT5840 got disconnected

2015-12-02T17:21:49.061Z (672 sec) - Android LGE-LG-D802_PT6776 got disconnected

2015-12-02T17:21:52.470Z (675 sec) - Android samsung-SM-A500FU_PT7553 got disconnected

2015-12-02T17:22:09.041Z (692 sec) - Android LGE-LG-D802_PT6776 got re-connected event

2015-12-02T17:24:07.399Z (810 sec) - Android LGE-LG-D855_PT1610 got disconnected

2015-12-02T17:24:21.042Z (824 sec) - Android LGE-LG-D722_PT7815 got re-connected event

2015-12-02T17:24:36.856Z (839 sec) - Android HTC-HTC Desire 820_PT4030 got disconnected

2015-12-02T17:25:15.473Z (878 sec) - Android LGE-LG-D722_PT7815 got disconnected

2015-12-02T17:25:17.983Z (881 sec) - Android LGE-LG-D855_PT1610 got re-connected event

2015-12-02T17:25:20.255Z (883 sec) - Android HTC-HTC Desire 820_PT4030 got re-connected event

2015-12-02T17:25:38.942Z (902 sec) - Android samsung-SM-A300FU_PT9092 got disconnected

2015-12-02T17:25:57.598Z (920 sec) - Android LGE-Nexus 5_PT5840 got re-connected event

2015-12-02T17:26:40.314Z (963 sec) - Android LGE-LG-D722_PT7815 got re-connected event

2015-12-02T17:27:28.314Z (1011 sec) - Android LGE-LG-D722_PT7815 got disconnected

2015-12-02T17:27:36.503Z (1019 sec) - Android motorola-XT1039_PT9827 got disconnected

2015-12-02T17:28:04.072Z (1047 sec) - Android HTC-HTC Desire 820_PT4030 got disconnected

2015-12-02T17:28:05.176Z (1048 sec) - Android HTC-HTC Desire 820_PT4030 got re-connected event

2015-12-02T17:28:12.981Z (1056 sec) - Android LGE-LG-D722_PT7815 got re-connected event

2015-12-02T17:28:12.995Z (1056 sec) - Android LGE-Nexus 5_PT5840 got disconnected

2015-12-02T17:28:44.779Z (1087 sec) - Android LGE-LG-D802_PT6776 got re-connected event

2015-12-02T17:28:44.883Z (1087 sec) - Android samsung-SM-G900F_PT1925 got disconnected

2015-12-02T17:28:48.548Z (1091 sec) - Android LGE-LG-D855_PT1610 got re-connected event

2015-12-02T17:28:55.383Z (1098 sec) - Android motorola-XT1039_PT9827 got re-connected event

2015-12-02T17:29:15.264Z (1118 sec) - Android HTC-HTC Desire 820_PT4030 got re-connected event

2015-12-02T17:29:17.776Z (1120 sec) - Android samsung-SM-A500FU_PT3412 test took 1000293ms - results peers[0], reConnects[0], sendData[18]

2015-12-02T17:29:17.905Z (1121 sec) - Android LGE-Nexus 5_PT3826 test took 1000414ms - results peers[0], reConnects[0], sendData[18]

2015-12-02T17:29:18.055Z (1121 sec) - Android samsung-SM-A300FU_PT7144 test took 1000570ms - results peers[0], reConnects[0], sendData[18]

2015-12-02T17:29:18.279Z (1121 sec) - Android HTC-HTC Desire 820_PT4030 test took 1000786ms - results peers[0], reConnects[0], sendData[18]

2015-12-02T17:29:18.535Z (1121 sec) - Android LGE-LG-H815_PT5092 test took 1001041ms - results peers[0], reConnects[0], sendData[18]

2015-12-02T17:29:19.409Z (1122 sec) - Android HUAWEI-ALE-L21_PT194 test took 1001917ms - results peers[0], reConnects[0], sendData[18]

2015-12-02T17:29:20.331Z (1123 sec) - Android LGE-LG-D722_PT7815 got disconnected

2015-12-02T17:29:20.667Z (1123 sec) - Android HTC-HTC Desire 820_PT8680 test took 1003179ms - results peers[0], reConnects[0], sendData[18]

2015-12-02T17:29:21.293Z (1124 sec) - Android LGE-LG-D802_PT6776 test took 1003795ms - results peers[0], reConnects[0], sendData[18]

2015-12-02T17:29:25.370Z (1128 sec) - Android LGE-LG-D855_PT1610 test took 1007877ms - results peers[0], reConnects[0], sendData[18]

2015-12-02T17:29:27.244Z (1130 sec) - Android LGE-LG-D802_PT6776 got disconnected

2015-12-02T17:29:30.121Z (1133 sec) - Android LGE-LG-D722_PT7815 got re-connected event

2015-12-02T17:29:30.145Z (1133 sec) - Android LGE-LG-D722_PT7815 test took 1012658ms - results peers[0], reConnects[0], sendData[18]

2015-12-02T17:29:32.303Z (1135 sec) - Android motorola-XT1072_PT8055 got disconnected

2015-12-02T17:29:43.853Z (1146 sec) - Android motorola-XT1072_PT8055 got re-connected event

2015-12-02T17:29:43.869Z (1146 sec) - Android motorola-XT1072_PT8055 test took 1026372ms - results peers[0], reConnects[0], sendData[18]

2015-12-02T17:29:43.871Z (1146 sec) - Android LGE-LG-D855_PT1610 got disconnected

2015-12-02T17:29:48.961Z (1152 sec) - Android motorola-XT1039_PT9827 got re-connected event

2015-12-02T17:29:48.991Z (1152 sec) - Android motorola-XT1039_PT9827 test took 1031495ms - results peers[0], reConnects[0], sendData[18]

2015-12-02T17:29:55.436Z (1158 sec) - Android HTC-HTC Desire 820_PT4030 got disconnected

2015-12-02T17:30:20.383Z (1183 sec) - Android motorola-XT1039_PT9827 got disconnected

2015-12-02T17:30:28.027Z (1191 sec) - Android LGE-LG-D722_PT7815 got disconnected

2015-12-02T17:32:31.400Z (1314 sec) - Android LGE-Nexus 5_PT5840 got re-connected event

2015-12-02T17:32:31.424Z (1314 sec) - Android LGE-Nexus 5_PT5840 test took 1193938ms - results peers[0], reConnects[0], sendData[18]

2015-12-02T17:32:37.500Z (1320 sec) - Server timeout reached!

2015-12-02T17:32:37.501Z (1320 sec) - Send timeout to samsung-SM-G800F_PT4415

2015-12-02T17:32:37.507Z (1320 sec) - Send timeout to samsung-SM-A300FU_PT9092

2015-12-02T17:32:37.508Z (1320 sec) - Send timeout to samsung-SM-A500FU_PT7553

2015-12-02T17:32:37.511Z (1320 sec) - Send timeout to samsung-SM-G900F_PT1925
2015-12-02T17:32:37.512Z (1320 sec) - Send timeout to samsung-SM-N910C_PT6682

2015-12-02T17:33:37.514Z (1380 sec) - Did not get reports from all devices, but forcing tests to finish!

samsung-SM-G800F_PT4415 did not have results at the end of tests - check the device logs about why!!

samsung-SM-A300FU_PT9092 did not have results at the end of tests - check the device logs about why!!

samsung-SM-A500FU_PT7553 did not have results at the end of tests - check the device logs about why!!

samsung-SM-G900F_PT1925 did not have results at the end of tests - check the device logs about why!!

samsung-SM-N910C_PT6682 did not have results at the end of tests - check the device logs about why!!

2015-12-02T17:33:37.540Z (1380 sec) - Android All tests are done, preparing test report

--------------- test report ---------------------

--------------- samsung-SM-A500FU_PT3412 --------------------- : 1
sendList : 100% : 97832 ms, 99% : 97832 ms, 95 : 79553 ms, 90% : 70565 ms.

Average data rate: 0.003 MB/s
Result count 16, range 3555 ms to  97832 ms.
sendList failed peers count : 2 [11.11111111111111 %]

- Peer ID : F8:95:C7:87:3C:51, Tried : 3

- Peer ID : 58:2A:F7:ED:96:BE, Tried : 2
sendList never tried peers count : 0 [0 %]

--------------- samsung-SM-A300FU_PT7144 --------------------- : 2
sendList : 100% : 86142 ms, 99% : 86142 ms, 95 : 72469 ms, 90% : 71704 ms.

Average data rate: 0.003 MB/s
Result count 16, range 2110 ms to  86142 ms.
sendList failed peers count : 2 [11.11111111111111 %]

- Peer ID : 58:2A:F7:ED:96:BE, Tried : 3
- Peer ID : F8:95:C7:87:3C:51, Tried : 3
sendList never tried peers count : 0 [0 %]

--------------- LGE-Nexus 5_PT5840 --------------------- : 3
sendList : 100% : 59225 ms, 99% : 59225 ms, 95 : 42922 ms, 90% : 42922 ms.

Average data rate: 0.007 MB/s
Result count 15, range 2516 ms to  59225 ms.
sendList failed peers count : 3 [16.666666666666668 %]

- Peer ID : 08:EC:A9:50:76:27, Tried : 4
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 3
- Peer ID : F8:95:C7:87:3C:51, Tried : 4

sendList never tried peers count : 0 [0 %]
--------------- LGE-LG-D722_PT7815 --------------------- : 4
sendList : 100% : 65779 ms, 99% : 65779 ms, 95 : 59019 ms, 90% : 53643 ms.

Average data rate: 0.004 MB/s
Result count 16, range 6447 ms to  65779 ms.
sendList failed peers count : 2 [11.11111111111111 %]

- Peer ID : F8:95:C7:87:3C:51, Tried : 4
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 4
sendList never tried peers count : 0 [0 %]

--------------- HTC-HTC Desire 820_PT8680 --------------------- : 5
sendList : 100% : 63363 ms, 99% : 63363 ms, 95 : 57378 ms, 90% : 57378 ms.

Average data rate: 0.004 MB/s
Result count 15, range 2146 ms to  63363 ms.
sendList failed peers count : 3 [16.666666666666668 %]

- Peer ID : 58:2A:F7:ED:96:BE, Tried : 3
- Peer ID : F8:95:C7:87:3C:51, Tried : 3
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 3
sendList never tried peers count : 0 [0 %]

--------------- LGE-Nexus 5_PT3826 --------------------- : 6
sendList : 100% : 79390 ms, 99% : 79390 ms, 95 : 41967 ms, 90% : 41553 ms.
Average data rate: 0.005 MB/s
Result count 16, range 3214 ms to  79390 ms.
sendList failed peers count : 2 [11.11111111111111 %]
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 5
- Peer ID : F8:95:C7:87:3C:51, Tried : 4
sendList never tried peers count : 0 [0 %]
--------------- HUAWEI-ALE-L21_PT194 --------------------- : 7
sendList : 100% : 104527 ms, 99% : 104527 ms, 95 : 104527 ms, 90% : 104527 ms.
Average data rate: 0.002 MB/s
Result count 5, range 8504 ms to  104527 ms.
sendList failed peers count : 8 [61.53846153846154 %]
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 7C:F9:0E:51:18:22, Tried : 1
sendList never tried peers count : 5 [27.77777777777778 %]
- Peer ID : 08:EC:A9:50:76:27

- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : B4:CE:F6:AB:A4:6A
--------------- HTC-HTC Desire 820_PT4030 --------------------- : 8

sendList : 100% : 85528 ms, 99% : 85528 ms, 95 : 77132 ms, 90% : 75392 ms.

Average data rate: 0.004 MB/s
Result count 16, range 3550 ms to  85528 ms.
sendList failed peers count : 2 [11.11111111111111 %]
- Peer ID : F8:95:C7:87:3C:51, Tried : 4
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 4

sendList never tried peers count : 0 [0 %]
--------------- LGE-LG-D855_PT1610 --------------------- : 9

sendList : 100% : 103273 ms, 99% : 103273 ms, 95 : 53386 ms, 90% : 43079 ms.
Average data rate: 0.004 MB/s
Result count 16, range 4747 ms to  103273 ms.

sendList failed peers count : 2 [11.11111111111111 %]
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 3
- Peer ID : F8:95:C7:87:3C:51, Tried : 3
sendList never tried peers count : 0 [0 %]

--------------- LGE-LG-H815_PT5092 --------------------- : 10
sendList : 100% : 17683 ms, 99% : 17683 ms, 95 : 17683 ms, 90% : 17683 ms.

Average data rate: 0.009 MB/s
Result count 5, range 3326 ms to  17683 ms.
sendList failed peers count : 11 [68.75 %]
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1

- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1

- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1

- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 7C:F9:0E:51:18:22, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
sendList never tried peers count : 2 [11.11111111111111 %]
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 08:EC:A9:50:76:27
--------------- samsung-SM-G900F_PT9809 --------------------- : 11
sendList : 100% : 47646 ms, 99% : 47646 ms, 95 : 37563 ms, 90% : 36868 ms.
Average data rate: 0.005 MB/s
Result count 18, range 2944 ms to  47646 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- motorola-XT1039_PT9827 --------------------- : 12
sendList : 100% : 45476 ms, 99% : 45476 ms, 95 : 43157 ms, 90% : 30618 ms.
Average data rate: 0.006 MB/s
Result count 16, range 2665 ms to  45476 ms.
sendList failed peers count : 2 [11.11111111111111 %]
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 6
- Peer ID : F8:95:C7:87:3C:51, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- LGE-LG-D802_PT6776 --------------------- : 13
sendList : 100% : 55173 ms, 99% : 55173 ms, 95 : 40248 ms, 90% : 30989 ms.
Average data rate: 0.005 MB/s
Result count 16, range 3951 ms to  55173 ms.
sendList failed peers count : 2 [11.11111111111111 %]
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 4
- Peer ID : F8:95:C7:87:3C:51, Tried : 4
sendList never tried peers count : 0 [0 %]
--------------- motorola-XT1072_PT8055 --------------------- : 14
sendList : 100% : 104483 ms, 99% : 104483 ms, 95 : 102560 ms, 90% : 89600 ms.
Average data rate: 0.003 MB/s
Result count 16, range 4774 ms to  104483 ms.
sendList failed peers count : 2 [11.11111111111111 %]
- Peer ID : F8:95:C7:87:3C:51, Tried : 3
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 3
sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------
sendList : 100% : 104527 ms, 99% : 103273 ms, 95 : 77132 ms, 90% : 59019 ms.
Average data rate: 0.004 MB/s
--------------- end of test report ---------------------

2015-12-02T17:33:37.809Z (1380 sec) - Android samsung-SM-A500FU_PT3412 got disconnected

2015-12-02T17:33:37.836Z (1380 sec) - Android samsung-SM-A300FU_PT7144 got disconnected

2015-12-02T17:33:37.934Z (1381 sec) - Android LGE-Nexus 5_PT5840 got disconnected

2015-12-02T17:33:37.952Z (1381 sec) - Android samsung-SM-G900F_PT9809 got disconnected

2015-12-02T17:33:37.997Z (1381 sec) - Android LGE-LG-D802_PT6776 got disconnected

2015-12-02T17:33:38.007Z (1381 sec) - Android LGE-LG-H815_PT5092 got disconnected

2015-12-02T17:33:38.060Z (1381 sec) - Android HUAWEI-ALE-L21_PT194 got disconnected

2015-12-02T17:33:38.128Z (1381 sec) - Android LGE-Nexus 5_PT3826 got disconnected

2015-12-02T17:33:38.360Z (1381 sec) - Android LGE-LG-D855_PT1610 got disconnected

2015-12-02T17:33:38.438Z (1381 sec) - Android motorola-XT1072_PT8055 got disconnected

2015-12-02T17:34:41.311Z (1444 sec) - Android LGE-LG-D722_PT7815 got disconnected

2015-12-02T17:34:52.622Z (1455 sec) - Android HTC-HTC Desire 820_PT4030 got disconnected

2015-12-02T17:34:58.278Z (1461 sec) - Android HTC-HTC Desire 820_PT8680 got disconnected

2015-12-02T17:35:00.024Z (1463 sec) - Android motorola-XT1039_PT9827 got disconnected


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


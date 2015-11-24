#### Test 5133502802397d9 Logs

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

2015-11-24T16:08:23.288Z (0 sec) - Android tests will start after waiting for 120 seconds

Test ID 0 configuration: testSendData.js, server timeout: 1200000, data:

{ timeout: '1000000',
  rounds: '1',
  dataTimeout: '10000',
  dataAmount: '100000',
  conReTryTimeout: '5000',
  conReTryCount: '5' }

2015-11-24T16:08:23.294Z (0 sec) - iOS tests will start after waiting for 120 seconds

listening on *:3000

2015-11-24T16:08:23.689Z (0 sec) - Android LGE-LG-H815_PT7587 added (current device count 1)

2015-11-24T16:08:23.734Z (0 sec) - Android LGE-LG-D722_PT6211 added (current device count 2)

2015-11-24T16:08:23.945Z (1 sec) - Android HTC-HTC Desire 820_PT6452 added (current device count 3)

2015-11-24T16:08:24.114Z (1 sec) - Android LGE-Nexus 5_PT7505 added (current device count 4)

2015-11-24T16:08:24.432Z (1 sec) - Android LGE-Nexus 5_PT474 added (current device count 5)

2015-11-24T16:08:24.516Z (1 sec) - Android motorola-XT1039_PT1668 added (current device count 6)

2015-11-24T16:08:24.662Z (1 sec) - Android HTC-HTC Desire 820_PT9043 added (current device count 7)

2015-11-24T16:08:25.246Z (2 sec) - Android samsung-SM-A300FU_PT2521 added (current device count 8)

2015-11-24T16:08:25.506Z (2 sec) - Android samsung-SM-N9005_PT1336 added (current device count 9)

2015-11-24T16:08:25.631Z (2 sec) - Android LGE-LG-D855_PT6302 added (current device count 10)

2015-11-24T16:08:26.075Z (3 sec) - iOS Apple-IpadAir2-1_PT7208 added (current device count 1)

2015-11-24T16:08:26.155Z (3 sec) - Android samsung-SM-N910C_PT4262 added (current device count 11)

2015-11-24T16:08:26.178Z (3 sec) - Android HUAWEI-ALE-L21_PT5583 added (current device count 12)

2015-11-24T16:08:26.632Z (3 sec) - Android motorola-Nexus 6_PT5708 added (current device count 13)

2015-11-24T16:08:26.953Z (4 sec) - Android samsung-SM-A300FU_PT5340 added (current device count 14)

2015-11-24T16:08:27.258Z (4 sec) - iOS Apple-Iphone5s-1_PT8445 added (current device count 2)

2015-11-24T16:08:27.340Z (4 sec) - iOS Apple-Iphone5-1_PT7498 added (current device count 3)

2015-11-24T16:08:27.343Z (4 sec) - Android LGE-LG-D802_PT2047 added (current device count 15)

2015-11-24T16:08:27.542Z (4 sec) - iOS Apple-Iphone6-1_PT1630 added (current device count 4)

2015-11-24T16:08:27.730Z (4 sec) - Android samsung-SM-G800F_PT6450 added (current device count 16)

2015-11-24T16:08:28.047Z (5 sec) - Android samsung-SM-A500FU_PT6662 added (current device count 17)

2015-11-24T16:08:28.235Z (5 sec) - Android samsung-SM-G900F_PT2346 added (current device count 18)

2015-11-24T16:08:28.440Z (5 sec) - Android HTC-HTC One_M8_PT4451 added (current device count 19)

2015-11-24T16:08:34.049Z (11 sec) - Android motorola-XT1072_PT1910 added (current device count 20)

-------------- We got wait done, now starting the testing process ------------------

2015-11-24T16:10:23.335Z (120 sec) - Android start testing now with 20 devices

2015-11-24T16:10:23.366Z (120 sec) - iOS start testing now with 4 devices

2015-11-24T16:10:35.321Z (132 sec) - iOS Apple-Iphone6-1_PT1630 test took 11952ms - results peers[0], reConnects[0], sendData[3]

2015-11-24T16:10:35.732Z (132 sec) - iOS Apple-Iphone5s-1_PT8445 test took 12365ms - results peers[0], reConnects[0], sendData[3]

2015-11-24T16:10:39.709Z (136 sec) - iOS Apple-Iphone5-1_PT7498 test took 16341ms - results peers[0], reConnects[0], sendData[3]

2015-11-24T16:10:40.158Z (137 sec) - iOS Apple-IpadAir2-1_PT7208 test took 16791ms - results peers[0], reConnects[0], sendData[3]

2015-11-24T16:10:40.158Z (137 sec) - iOS test ID 0 done now

2015-11-24T16:10:40.168Z (137 sec) - iOS All tests are done, preparing test report

--------------- test report ---------------------

--------------- Apple-IpadAir2-1_PT7208 --------------------- : 1

sendList : 100% : 7047 ms, 99% : 7047 ms, 95 : 7047 ms, 90% : 7047 ms.

Result count 3, range 3397 ms to  7047 ms.

sendList failed peers count : 0 [0 %]

sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5s-1_PT8445 --------------------- : 2
sendList : 100% : 5907 ms, 99% : 5907 ms, 95 : 5907 ms, 90% : 5907 ms.

Result count 3, range 2721 ms to  5907 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5-1_PT7498 --------------------- : 3
sendList : 100% : 9136 ms, 99% : 9136 ms, 95 : 9136 ms, 90% : 9136 ms.

Result count 3, range 2935 ms to  9136 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1_PT1630 --------------------- : 4
sendList : 100% : 4431 ms, 99% : 4431 ms, 95 : 4431 ms, 90% : 4431 ms.

Result count 3, range 2803 ms to  4431 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- Combined ---------------------

sendList : 100% : 9136 ms, 99% : 9136 ms, 95 : 7047 ms, 90% : 7047 ms.

--------------- end of test report ---------------------

2015-11-24T16:11:05.804Z (163 sec) - Android LGE-Nexus 5_PT7505 got disconnected

2015-11-24T16:11:07.862Z (165 sec) - Android LGE-Nexus 5_PT7505 got re-connected event

2015-11-24T16:11:32.032Z (189 sec) - Android samsung-SM-A300FU_PT5340 got disconnected

2015-11-24T16:11:55.091Z (212 sec) - Android HTC-HTC One_M8_PT4451 got re-connected event

2015-11-24T16:11:55.152Z (212 sec) - Android motorola-XT1039_PT1668 got disconnected

2015-11-24T16:11:56.741Z (213 sec) - Android HTC-HTC Desire 820_PT9043 got disconnected

2015-11-24T16:12:09.647Z (226 sec) - Android LGE-Nexus 5_PT7505 got re-connected event

2015-11-24T16:12:48.827Z (266 sec) - Android HTC-HTC One_M8_PT4451 got disconnected

2015-11-24T16:12:57.576Z (274 sec) - Android LGE-Nexus 5_PT7505 got disconnected

2015-11-24T16:12:57.603Z (274 sec) - Android motorola-XT1072_PT1910 got disconnected

2015-11-24T16:12:59.034Z (276 sec) - Android HTC-HTC One_M8_PT4451 got re-connected event

2015-11-24T16:13:09.486Z (286 sec) - Android LGE-Nexus 5_PT7505 got re-connected event

2015-11-24T16:13:14.141Z (291 sec) - Android samsung-SM-A500FU_PT6662 got disconnected

2015-11-24T16:13:18.056Z (295 sec) - Android samsung-SM-G800F_PT6450 got disconnected

2015-11-24T16:13:34.648Z (311 sec) - Android LGE-Nexus 5_PT7505 got disconnected

2015-11-24T16:13:45.082Z (322 sec) - Android HTC-HTC One_M8_PT4451 got disconnected

2015-11-24T16:14:00.879Z (338 sec) - Android motorola-XT1039_PT1668 got re-connected event

2015-11-24T16:14:11.379Z (348 sec) - Android LGE-Nexus 5_PT7505 got re-connected event

2015-11-24T16:14:14.548Z (351 sec) - Android LGE-LG-D722_PT6211 got re-connected event

2015-11-24T16:14:59.404Z (396 sec) - Android LGE-Nexus 5_PT7505 got disconnected

2015-11-24T16:15:15.044Z (412 sec) - Android LGE-LG-D722_PT6211 got disconnected

2015-11-24T16:15:32.247Z (429 sec) - Android LGE-Nexus 5_PT7505 got re-connected event

2015-11-24T16:16:01.361Z (458 sec) - Android LGE-Nexus 5_PT7505 got disconnected

2015-11-24T16:16:29.600Z (486 sec) - Android LGE-LG-D722_PT6211 got disconnected

2015-11-24T16:16:37.785Z (495 sec) - Android LGE-Nexus 5_PT7505 got re-connected event

2015-11-24T16:17:22.442Z (539 sec) - Android LGE-Nexus 5_PT7505 got disconnected

2015-11-24T16:17:31.486Z (548 sec) - Android LGE-Nexus 5_PT7505 got re-connected event

2015-11-24T16:18:14.405Z (591 sec) - Android LGE-Nexus 5_PT7505 got re-connected event

2015-11-24T16:18:27.747Z (604 sec) - Android LGE-Nexus 5_PT7505 got disconnected

2015-11-24T16:19:05.981Z (643 sec) - Android samsung-SM-N910C_PT4262 got disconnected

2015-11-24T16:19:21.423Z (658 sec) - Android LGE-Nexus 5_PT7505 got disconnected

2015-11-24T16:19:49.403Z (686 sec) - Android LGE-Nexus 5_PT7505 got re-connected event

2015-11-24T16:20:29.434Z (726 sec) - Android LGE-Nexus 5_PT7505 got disconnected

2015-11-24T16:20:50.985Z (748 sec) - Android LGE-Nexus 5_PT7505 got re-connected event

2015-11-24T16:21:20.474Z (777 sec) - Android LGE-Nexus 5_PT7505 got re-connected event

2015-11-24T16:21:39.366Z (796 sec) - Android LGE-Nexus 5_PT7505 got disconnected

2015-11-24T16:22:15.987Z (833 sec) - Android LGE-Nexus 5_PT7505 got disconnected

2015-11-24T16:22:36.314Z (853 sec) - Android LGE-Nexus 5_PT7505 got re-connected event

2015-11-24T16:23:35.562Z (912 sec) - Android LGE-Nexus 5_PT7505 got disconnected

2015-11-24T16:23:54.564Z (931 sec) - Android LGE-Nexus 5_PT7505 got re-connected event

2015-11-24T16:24:01.315Z (938 sec) - Android LGE-Nexus 5_PT7505 got disconnected

2015-11-24T16:24:23.302Z (960 sec) - Android LGE-Nexus 5_PT7505 got re-connected event

2015-11-24T16:24:53.346Z (990 sec) - Android samsung-SM-N9005_PT1336 got disconnected

2015-11-24T16:25:19.567Z (1016 sec) - Android LGE-Nexus 5_PT7505 got disconnected

2015-11-24T16:25:48.309Z (1045 sec) - Android LGE-Nexus 5_PT7505 got disconnected

2015-11-24T16:25:59.104Z (1056 sec) - Android motorola-XT1039_PT1668 got disconnected

2015-11-24T16:26:02.047Z (1059 sec) - Android LGE-Nexus 5_PT7505 got re-connected event

2015-11-24T16:27:03.625Z (1120 sec) - Android HUAWEI-ALE-L21_PT5583 test took 1000269ms - results peers[0], reConnects[0], sendData[19]

2015-11-24T16:27:03.689Z (1120 sec) - Android HTC-HTC One_M8_PT4451 test took 1000329ms - results peers[0], reConnects[0], sendData[19]

2015-11-24T16:27:03.869Z (1121 sec) - Android LGE-LG-D855_PT6302 test took 1000515ms - results peers[0], reConnects[0], sendData[19]

2015-11-24T16:27:03.962Z (1121 sec) - Android samsung-SM-G900F_PT2346 test took 1000603ms - results peers[0], reConnects[0], sendData[19]

2015-11-24T16:27:03.966Z (1121 sec) - Android LGE-Nexus 5_PT474 test took 1000617ms - results peers[0], reConnects[0], sendData[19]

2015-11-24T16:27:04.041Z (1121 sec) - Android motorola-Nexus 6_PT5708 test took 1000684ms - results peers[0], reConnects[0], sendData[19]

2015-11-24T16:27:05.992Z (1123 sec) - Android LGE-LG-H815_PT7587 test took 1002648ms - results peers[0], reConnects[0], sendData[19]

2015-11-24T16:27:08.752Z (1126 sec) - Android HTC-HTC Desire 820_PT6452 test took 1005404ms - results peers[0], reConnects[0], sendData[19]

2015-11-24T16:27:10.346Z (1127 sec) - Android LGE-LG-D802_PT2047 test took 1006989ms - results peers[0], reConnects[0], sendData[19]

2015-11-24T16:27:10.873Z (1128 sec) - Android samsung-SM-A300FU_PT2521 test took 1007521ms - results peers[0], reConnects[0], sendData[19]

2015-11-24T16:27:11.011Z (1128 sec) - Android LGE-Nexus 5_PT7505 got re-connected event

2015-11-24T16:27:27.063Z (1144 sec) - Android LGE-Nexus 5_PT7505 got disconnected

2015-11-24T16:30:23.367Z (1320 sec) - Server timeout reached!

2015-11-24T16:30:23.370Z (1320 sec) - Send timeout to LGE-LG-D722_PT6211

2015-11-24T16:30:23.372Z (1320 sec) - Send timeout to LGE-Nexus 5_PT7505

2015-11-24T16:30:23.374Z (1320 sec) - Send timeout to motorola-XT1039_PT1668
2015-11-24T16:30:23.375Z (1320 sec) - Send timeout to HTC-HTC Desire 820_PT9043

2015-11-24T16:30:23.375Z (1320 sec) - Send timeout to samsung-SM-N9005_PT1336
2015-11-24T16:30:23.376Z (1320 sec) - Send timeout to samsung-SM-N910C_PT4262
2015-11-24T16:30:23.377Z (1320 sec) - Send timeout to samsung-SM-A300FU_PT5340
2015-11-24T16:30:23.378Z (1320 sec) - Send timeout to samsung-SM-G800F_PT6450
2015-11-24T16:30:23.378Z (1320 sec) - Send timeout to samsung-SM-A500FU_PT6662
2015-11-24T16:30:23.379Z (1320 sec) - Send timeout to motorola-XT1072_PT1910

2015-11-24T16:31:23.382Z (1380 sec) - Did not get reports from all devices, but forcing tests to finish!

LGE-LG-D722_PT6211 did not have results at the end of tests - check the device logs about why!!

LGE-Nexus 5_PT7505 did not have results at the end of tests - check the device logs about why!!

motorola-XT1039_PT1668 did not have results at the end of tests - check the device logs about why!!

HTC-HTC Desire 820_PT9043 did not have results at the end of tests - check the device logs about why!!
samsung-SM-N9005_PT1336 did not have results at the end of tests - check the device logs about why!!
samsung-SM-N910C_PT4262 did not have results at the end of tests - check the device logs about why!!

samsung-SM-A300FU_PT5340 did not have results at the end of tests - check the device logs about why!!
samsung-SM-G800F_PT6450 did not have results at the end of tests - check the device logs about why!!

samsung-SM-A500FU_PT6662 did not have results at the end of tests - check the device logs about why!!

motorola-XT1072_PT1910 did not have results at the end of tests - check the device logs about why!!

2015-11-24T16:31:23.405Z (1380 sec) - Android All tests are done, preparing test report

--------------- test report ---------------------
--------------- LGE-LG-H815_PT7587 --------------------- : 1
sendList : 100% : 60637 ms, 99% : 60637 ms, 95 : 42933 ms, 90% : 42933 ms.

Result count 11, range 4835 ms to  60637 ms.
sendList failed peers count : 8 [42.10526315789474 %]
- Peer ID : 44:80:EB:7B:5A:05, Tried : 2

- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 2
- Peer ID : 34:FC:EF:11:B1:66, Tried : 2

sendList never tried peers count : 0 [0 %]
--------------- HTC-HTC Desire 820_PT6452 --------------------- : 2
sendList : 100% : 159060 ms, 99% : 159060 ms, 95 : 31686 ms, 90% : 31686 ms.
Result count 12, range 4160 ms to  159060 ms.
sendList failed peers count : 7 [36.8421052631579 %]
- Peer ID : 34:FC:EF:11:AE:67, Tried : 2

- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 2
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 2
- Peer ID : 80:01:84:8A:B3:68, Tried : 2
- Peer ID : 44:80:EB:7B:5A:05, Tried : 2
- Peer ID : 34:FC:EF:11:B1:66, Tried : 2

sendList never tried peers count : 0 [0 %]
--------------- LGE-Nexus 5_PT474 --------------------- : 3
sendList : 100% : 104695 ms, 99% : 104695 ms, 95 : 104695 ms, 90% : 50345 ms.
Result count 6, range 3088 ms to  104695 ms.
sendList failed peers count : 11 [64.70588235294117 %]
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1

- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
sendList never tried peers count : 2 [10.526315789473685 %]
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 08:EC:A9:50:76:27
--------------- samsung-SM-A300FU_PT2521 --------------------- : 4
sendList : 100% : 77389 ms, 99% : 77389 ms, 95 : 31270 ms, 90% : 31270 ms.
Result count 15, range 2245 ms to  77389 ms.
sendList failed peers count : 4 [21.05263157894737 %]
- Peer ID : 44:80:EB:7B:5A:05, Tried : 4
- Peer ID : 80:01:84:8A:B3:68, Tried : 3
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 3
- Peer ID : 34:FC:EF:11:B1:66, Tried : 4
sendList never tried peers count : 0 [0 %]
--------------- LGE-LG-D855_PT6302 --------------------- : 5
sendList : 100% : 72366 ms, 99% : 72366 ms, 95 : 60257 ms, 90% : 60257 ms.
Result count 14, range 3550 ms to  72366 ms.
sendList failed peers count : 5 [26.31578947368421 %]
- Peer ID : 80:01:84:8A:B3:68, Tried : 3
- Peer ID : 34:FC:EF:11:B1:66, Tried : 2
- Peer ID : 34:FC:EF:11:AE:67, Tried : 2
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 2
- Peer ID : 08:EC:A9:50:75:41, Tried : 2
sendList never tried peers count : 0 [0 %]
--------------- HUAWEI-ALE-L21_PT5583 --------------------- : 6
sendList : 100% : 42308 ms, 99% : 42308 ms, 95 : 42308 ms, 90% : 26031 ms.
Result count 7, range 14353 ms to  42308 ms.
sendList failed peers count : 7 [50 %]
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
sendList never tried peers count : 5 [26.31578947368421 %]
- Peer ID : E0:DB:10:1F:C9:5E

- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 50:2E:6C:AC:21:50
--------------- motorola-Nexus 6_PT5708 --------------------- : 7
sendList : 100% : 66911 ms, 99% : 66911 ms, 95 : 51474 ms, 90% : 51474 ms.
Result count 15, range 2386 ms to  66911 ms.
sendList failed peers count : 4 [21.05263157894737 %]
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 3
- Peer ID : 34:FC:EF:11:B1:66, Tried : 3
- Peer ID : 80:01:84:8A:B3:68, Tried : 3
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 3
sendList never tried peers count : 0 [0 %]
--------------- LGE-LG-D802_PT2047 --------------------- : 8
sendList : 100% : 76601 ms, 99% : 76601 ms, 95 : 67259 ms, 90% : 67259 ms.

Result count 11, range 8479 ms to  76601 ms.
sendList failed peers count : 8 [42.10526315789474 %]
- Peer ID : 34:FC:EF:11:AE:67, Tried : 2
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1

- Peer ID : 80:01:84:8A:B3:68, Tried : 2
- Peer ID : 34:FC:EF:11:B1:66, Tried : 2
- Peer ID : F8:95:C7:87:85:54, Tried : 2
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 2
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-G900F_PT2346 --------------------- : 9

sendList : 100% : 50708 ms, 99% : 50708 ms, 95 : 26773 ms, 90% : 26773 ms.
Result count 11, range 4190 ms to  50708 ms.
sendList failed peers count : 8 [42.10526315789474 %]
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 2
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1

- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 2
- Peer ID : 44:80:EB:7B:5A:05, Tried : 2
- Peer ID : 34:FC:EF:11:AE:67, Tried : 2
- Peer ID : F8:95:C7:87:85:54, Tried : 2
sendList never tried peers count : 0 [0 %]

--------------- HTC-HTC One_M8_PT4451 --------------------- : 10
sendList : 100% : 47740 ms, 99% : 47740 ms, 95 : 47740 ms, 90% : 47740 ms.
Result count 3, range 4771 ms to  47740 ms.
sendList failed peers count : 1 [25 %]
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
sendList never tried peers count : 15 [78.94736842105263 %]

- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : F8:95:C7:87:85:54
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 44:80:EB:7B:5A:05

- Peer ID : E0:DB:10:1F:C9:5E
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 34:FC:EF:9D:93:0B

- Peer ID : 00:F4:6F:30:E0:6C
--------------- Combined ---------------------

sendList : 100% : 159060 ms, 99% : 104695 ms, 95 : 67259 ms, 90% : 51474 ms.

--------------- end of test report ---------------------


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```
###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  W3D7N15428022572 Test has  SUCCEEDED
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Device test finished on W3D7N15428022572 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:null 
child process exited with code null on device f56ad48d 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/5133502802397d9_Work_in_progress__vjrantal/thali01_LGE-LG-H815.md)

[HUAWEI-ALE-L21](https://github.com/ThaliTester/TestResults/blob/5133502802397d9_Work_in_progress__vjrantal/thali01_HUAWEI-ALE-L21.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/5133502802397d9_Work_in_progress__vjrantal/thali01_samsung-SM-A500FU.md)

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
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/5133502802397d9_Work_in_progress__vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/5133502802397d9_Work_in_progress__vjrantal/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/5133502802397d9_Work_in_progress__vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/5133502802397d9_Work_in_progress__vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/5133502802397d9_Work_in_progress__vjrantal/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/5133502802397d9_Work_in_progress__vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/5133502802397d9_Work_in_progress__vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/5133502802397d9_Work_in_progress__vjrantal/thali04_samsung-SM-G900F.md)

####Node name: thali05
Console output:
```
STOP log received from  SH47FWM00508 Test has  SUCCEEDED
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on SH47FWM00508 
Device test finished on ZX1G429CRK 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 1d6a772d app:com.test.thalitest code:null 
child process exited with code null on device 1d6a772d 
Android task is completed. [FAILED]
```
[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/5133502802397d9_Work_in_progress__vjrantal/thali05_samsung-SM-N9005.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/5133502802397d9_Work_in_progress__vjrantal/thali05_motorola-Nexus 6.md)

[HTC-HTC One_M8](https://github.com/ThaliTester/TestResults/blob/5133502802397d9_Work_in_progress__vjrantal/thali05_HTC-HTC One_M8.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/5133502802397d9_Work_in_progress__vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/5133502802397d9_Work_in_progress__vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/5133502802397d9_Work_in_progress__vjrantal/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
Error: problem deploying Android apk(/home/pi/test/builder/builds/5133502802397d9/build_android/android_0_5133502802397d9.apk) to device 4db5c8cc protocol failure
- waiting for device -
rm: /data/local/tmp/android_0_5133502802397d9.apk: No such file or directory



Test on this node has failed but the reason wasn't the test application itself.
 Cancelling the test result on this node.

```
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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/5133502802397d9_Work_in_progress__vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/5133502802397d9_Work_in_progress__vjrantal/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
Device test finished on 0c6a0f3c0bdb4e77 
STOP log received from  CC51WYC03425 Test has  SUCCEEDED
Device test finished on CC51WYC03425 
Android task is completed. [SUCCESS]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/5133502802397d9_Work_in_progress__vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/5133502802397d9_Work_in_progress__vjrantal/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/5133502802397d9_Work_in_progress__vjrantal/iOS_Iphone5-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/5133502802397d9_Work_in_progress__vjrantal/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/5133502802397d9_Work_in_progress__vjrantal/iOS_Iphone6-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/5133502802397d9_Work_in_progress__vjrantal/iOS_IpadAir2-1.md)


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

2015-11-24T16:08:23.288Z (0 sec) - Android tests will start after waiting for 120 seconds

Test ID 0 configuration: testSendData.js, server timeout: 1200000, data:

{ timeout: '1000000',
  rounds: '1',
  dataTimeout: '10000',
  dataAmount: '100000',
  conReTryTimeout: '5000',
  conReTryCount: '5' }

2015-11-24T16:08:23.294Z (0 sec) - iOS tests will start after waiting for 120 seconds

listening on *:3000

2015-11-24T16:08:23.689Z (0 sec) - Android LGE-LG-H815_PT7587 added (current device count 1)

2015-11-24T16:08:23.734Z (0 sec) - Android LGE-LG-D722_PT6211 added (current device count 2)

2015-11-24T16:08:23.945Z (1 sec) - Android HTC-HTC Desire 820_PT6452 added (current device count 3)

2015-11-24T16:08:24.114Z (1 sec) - Android LGE-Nexus 5_PT7505 added (current device count 4)

2015-11-24T16:08:24.432Z (1 sec) - Android LGE-Nexus 5_PT474 added (current device count 5)

2015-11-24T16:08:24.516Z (1 sec) - Android motorola-XT1039_PT1668 added (current device count 6)

2015-11-24T16:08:24.662Z (1 sec) - Android HTC-HTC Desire 820_PT9043 added (current device count 7)

2015-11-24T16:08:25.246Z (2 sec) - Android samsung-SM-A300FU_PT2521 added (current device count 8)

2015-11-24T16:08:25.506Z (2 sec) - Android samsung-SM-N9005_PT1336 added (current device count 9)

2015-11-24T16:08:25.631Z (2 sec) - Android LGE-LG-D855_PT6302 added (current device count 10)

2015-11-24T16:08:26.075Z (3 sec) - iOS Apple-IpadAir2-1_PT7208 added (current device count 1)

2015-11-24T16:08:26.155Z (3 sec) - Android samsung-SM-N910C_PT4262 added (current device count 11)

2015-11-24T16:08:26.178Z (3 sec) - Android HUAWEI-ALE-L21_PT5583 added (current device count 12)

2015-11-24T16:08:26.632Z (3 sec) - Android motorola-Nexus 6_PT5708 added (current device count 13)

2015-11-24T16:08:26.953Z (4 sec) - Android samsung-SM-A300FU_PT5340 added (current device count 14)

2015-11-24T16:08:27.258Z (4 sec) - iOS Apple-Iphone5s-1_PT8445 added (current device count 2)

2015-11-24T16:08:27.340Z (4 sec) - iOS Apple-Iphone5-1_PT7498 added (current device count 3)

2015-11-24T16:08:27.343Z (4 sec) - Android LGE-LG-D802_PT2047 added (current device count 15)

2015-11-24T16:08:27.542Z (4 sec) - iOS Apple-Iphone6-1_PT1630 added (current device count 4)

2015-11-24T16:08:27.730Z (4 sec) - Android samsung-SM-G800F_PT6450 added (current device count 16)

2015-11-24T16:08:28.047Z (5 sec) - Android samsung-SM-A500FU_PT6662 added (current device count 17)

2015-11-24T16:08:28.235Z (5 sec) - Android samsung-SM-G900F_PT2346 added (current device count 18)

2015-11-24T16:08:28.440Z (5 sec) - Android HTC-HTC One_M8_PT4451 added (current device count 19)

2015-11-24T16:08:34.049Z (11 sec) - Android motorola-XT1072_PT1910 added (current device count 20)

-------------- We got wait done, now starting the testing process ------------------

2015-11-24T16:10:23.335Z (120 sec) - Android start testing now with 20 devices

2015-11-24T16:10:23.366Z (120 sec) - iOS start testing now with 4 devices

2015-11-24T16:10:35.321Z (132 sec) - iOS Apple-Iphone6-1_PT1630 test took 11952ms - results peers[0], reConnects[0], sendData[3]

2015-11-24T16:10:35.732Z (132 sec) - iOS Apple-Iphone5s-1_PT8445 test took 12365ms - results peers[0], reConnects[0], sendData[3]

2015-11-24T16:10:39.709Z (136 sec) - iOS Apple-Iphone5-1_PT7498 test took 16341ms - results peers[0], reConnects[0], sendData[3]

2015-11-24T16:10:40.158Z (137 sec) - iOS Apple-IpadAir2-1_PT7208 test took 16791ms - results peers[0], reConnects[0], sendData[3]

2015-11-24T16:10:40.158Z (137 sec) - iOS test ID 0 done now

2015-11-24T16:10:40.168Z (137 sec) - iOS All tests are done, preparing test report

--------------- test report ---------------------

--------------- Apple-IpadAir2-1_PT7208 --------------------- : 1

sendList : 100% : 7047 ms, 99% : 7047 ms, 95 : 7047 ms, 90% : 7047 ms.

Result count 3, range 3397 ms to  7047 ms.

sendList failed peers count : 0 [0 %]

sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5s-1_PT8445 --------------------- : 2
sendList : 100% : 5907 ms, 99% : 5907 ms, 95 : 5907 ms, 90% : 5907 ms.

Result count 3, range 2721 ms to  5907 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5-1_PT7498 --------------------- : 3
sendList : 100% : 9136 ms, 99% : 9136 ms, 95 : 9136 ms, 90% : 9136 ms.

Result count 3, range 2935 ms to  9136 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1_PT1630 --------------------- : 4
sendList : 100% : 4431 ms, 99% : 4431 ms, 95 : 4431 ms, 90% : 4431 ms.

Result count 3, range 2803 ms to  4431 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- Combined ---------------------

sendList : 100% : 9136 ms, 99% : 9136 ms, 95 : 7047 ms, 90% : 7047 ms.

--------------- end of test report ---------------------

2015-11-24T16:11:05.804Z (163 sec) - Android LGE-Nexus 5_PT7505 got disconnected

2015-11-24T16:11:07.862Z (165 sec) - Android LGE-Nexus 5_PT7505 got re-connected event

2015-11-24T16:11:32.032Z (189 sec) - Android samsung-SM-A300FU_PT5340 got disconnected

2015-11-24T16:11:55.091Z (212 sec) - Android HTC-HTC One_M8_PT4451 got re-connected event

2015-11-24T16:11:55.152Z (212 sec) - Android motorola-XT1039_PT1668 got disconnected

2015-11-24T16:11:56.741Z (213 sec) - Android HTC-HTC Desire 820_PT9043 got disconnected

2015-11-24T16:12:09.647Z (226 sec) - Android LGE-Nexus 5_PT7505 got re-connected event

2015-11-24T16:12:48.827Z (266 sec) - Android HTC-HTC One_M8_PT4451 got disconnected

2015-11-24T16:12:57.576Z (274 sec) - Android LGE-Nexus 5_PT7505 got disconnected

2015-11-24T16:12:57.603Z (274 sec) - Android motorola-XT1072_PT1910 got disconnected

2015-11-24T16:12:59.034Z (276 sec) - Android HTC-HTC One_M8_PT4451 got re-connected event

2015-11-24T16:13:09.486Z (286 sec) - Android LGE-Nexus 5_PT7505 got re-connected event

2015-11-24T16:13:14.141Z (291 sec) - Android samsung-SM-A500FU_PT6662 got disconnected

2015-11-24T16:13:18.056Z (295 sec) - Android samsung-SM-G800F_PT6450 got disconnected

2015-11-24T16:13:34.648Z (311 sec) - Android LGE-Nexus 5_PT7505 got disconnected

2015-11-24T16:13:45.082Z (322 sec) - Android HTC-HTC One_M8_PT4451 got disconnected

2015-11-24T16:14:00.879Z (338 sec) - Android motorola-XT1039_PT1668 got re-connected event

2015-11-24T16:14:11.379Z (348 sec) - Android LGE-Nexus 5_PT7505 got re-connected event

2015-11-24T16:14:14.548Z (351 sec) - Android LGE-LG-D722_PT6211 got re-connected event

2015-11-24T16:14:59.404Z (396 sec) - Android LGE-Nexus 5_PT7505 got disconnected

2015-11-24T16:15:15.044Z (412 sec) - Android LGE-LG-D722_PT6211 got disconnected

2015-11-24T16:15:32.247Z (429 sec) - Android LGE-Nexus 5_PT7505 got re-connected event

2015-11-24T16:16:01.361Z (458 sec) - Android LGE-Nexus 5_PT7505 got disconnected

2015-11-24T16:16:29.600Z (486 sec) - Android LGE-LG-D722_PT6211 got disconnected

2015-11-24T16:16:37.785Z (495 sec) - Android LGE-Nexus 5_PT7505 got re-connected event

2015-11-24T16:17:22.442Z (539 sec) - Android LGE-Nexus 5_PT7505 got disconnected

2015-11-24T16:17:31.486Z (548 sec) - Android LGE-Nexus 5_PT7505 got re-connected event

2015-11-24T16:18:14.405Z (591 sec) - Android LGE-Nexus 5_PT7505 got re-connected event

2015-11-24T16:18:27.747Z (604 sec) - Android LGE-Nexus 5_PT7505 got disconnected

2015-11-24T16:19:05.981Z (643 sec) - Android samsung-SM-N910C_PT4262 got disconnected

2015-11-24T16:19:21.423Z (658 sec) - Android LGE-Nexus 5_PT7505 got disconnected

2015-11-24T16:19:49.403Z (686 sec) - Android LGE-Nexus 5_PT7505 got re-connected event

2015-11-24T16:20:29.434Z (726 sec) - Android LGE-Nexus 5_PT7505 got disconnected

2015-11-24T16:20:50.985Z (748 sec) - Android LGE-Nexus 5_PT7505 got re-connected event

2015-11-24T16:21:20.474Z (777 sec) - Android LGE-Nexus 5_PT7505 got re-connected event

2015-11-24T16:21:39.366Z (796 sec) - Android LGE-Nexus 5_PT7505 got disconnected

2015-11-24T16:22:15.987Z (833 sec) - Android LGE-Nexus 5_PT7505 got disconnected

2015-11-24T16:22:36.314Z (853 sec) - Android LGE-Nexus 5_PT7505 got re-connected event

2015-11-24T16:23:35.562Z (912 sec) - Android LGE-Nexus 5_PT7505 got disconnected

2015-11-24T16:23:54.564Z (931 sec) - Android LGE-Nexus 5_PT7505 got re-connected event

2015-11-24T16:24:01.315Z (938 sec) - Android LGE-Nexus 5_PT7505 got disconnected

2015-11-24T16:24:23.302Z (960 sec) - Android LGE-Nexus 5_PT7505 got re-connected event

2015-11-24T16:24:53.346Z (990 sec) - Android samsung-SM-N9005_PT1336 got disconnected

2015-11-24T16:25:19.567Z (1016 sec) - Android LGE-Nexus 5_PT7505 got disconnected

2015-11-24T16:25:48.309Z (1045 sec) - Android LGE-Nexus 5_PT7505 got disconnected

2015-11-24T16:25:59.104Z (1056 sec) - Android motorola-XT1039_PT1668 got disconnected

2015-11-24T16:26:02.047Z (1059 sec) - Android LGE-Nexus 5_PT7505 got re-connected event

2015-11-24T16:27:03.625Z (1120 sec) - Android HUAWEI-ALE-L21_PT5583 test took 1000269ms - results peers[0], reConnects[0], sendData[19]

2015-11-24T16:27:03.689Z (1120 sec) - Android HTC-HTC One_M8_PT4451 test took 1000329ms - results peers[0], reConnects[0], sendData[19]

2015-11-24T16:27:03.869Z (1121 sec) - Android LGE-LG-D855_PT6302 test took 1000515ms - results peers[0], reConnects[0], sendData[19]

2015-11-24T16:27:03.962Z (1121 sec) - Android samsung-SM-G900F_PT2346 test took 1000603ms - results peers[0], reConnects[0], sendData[19]

2015-11-24T16:27:03.966Z (1121 sec) - Android LGE-Nexus 5_PT474 test took 1000617ms - results peers[0], reConnects[0], sendData[19]

2015-11-24T16:27:04.041Z (1121 sec) - Android motorola-Nexus 6_PT5708 test took 1000684ms - results peers[0], reConnects[0], sendData[19]

2015-11-24T16:27:05.992Z (1123 sec) - Android LGE-LG-H815_PT7587 test took 1002648ms - results peers[0], reConnects[0], sendData[19]

2015-11-24T16:27:08.752Z (1126 sec) - Android HTC-HTC Desire 820_PT6452 test took 1005404ms - results peers[0], reConnects[0], sendData[19]

2015-11-24T16:27:10.346Z (1127 sec) - Android LGE-LG-D802_PT2047 test took 1006989ms - results peers[0], reConnects[0], sendData[19]

2015-11-24T16:27:10.873Z (1128 sec) - Android samsung-SM-A300FU_PT2521 test took 1007521ms - results peers[0], reConnects[0], sendData[19]

2015-11-24T16:27:11.011Z (1128 sec) - Android LGE-Nexus 5_PT7505 got re-connected event

2015-11-24T16:27:27.063Z (1144 sec) - Android LGE-Nexus 5_PT7505 got disconnected

2015-11-24T16:30:23.367Z (1320 sec) - Server timeout reached!

2015-11-24T16:30:23.370Z (1320 sec) - Send timeout to LGE-LG-D722_PT6211

2015-11-24T16:30:23.372Z (1320 sec) - Send timeout to LGE-Nexus 5_PT7505

2015-11-24T16:30:23.374Z (1320 sec) - Send timeout to motorola-XT1039_PT1668
2015-11-24T16:30:23.375Z (1320 sec) - Send timeout to HTC-HTC Desire 820_PT9043

2015-11-24T16:30:23.375Z (1320 sec) - Send timeout to samsung-SM-N9005_PT1336
2015-11-24T16:30:23.376Z (1320 sec) - Send timeout to samsung-SM-N910C_PT4262
2015-11-24T16:30:23.377Z (1320 sec) - Send timeout to samsung-SM-A300FU_PT5340
2015-11-24T16:30:23.378Z (1320 sec) - Send timeout to samsung-SM-G800F_PT6450
2015-11-24T16:30:23.378Z (1320 sec) - Send timeout to samsung-SM-A500FU_PT6662
2015-11-24T16:30:23.379Z (1320 sec) - Send timeout to motorola-XT1072_PT1910

2015-11-24T16:31:23.382Z (1380 sec) - Did not get reports from all devices, but forcing tests to finish!

LGE-LG-D722_PT6211 did not have results at the end of tests - check the device logs about why!!

LGE-Nexus 5_PT7505 did not have results at the end of tests - check the device logs about why!!

motorola-XT1039_PT1668 did not have results at the end of tests - check the device logs about why!!

HTC-HTC Desire 820_PT9043 did not have results at the end of tests - check the device logs about why!!
samsung-SM-N9005_PT1336 did not have results at the end of tests - check the device logs about why!!
samsung-SM-N910C_PT4262 did not have results at the end of tests - check the device logs about why!!

samsung-SM-A300FU_PT5340 did not have results at the end of tests - check the device logs about why!!
samsung-SM-G800F_PT6450 did not have results at the end of tests - check the device logs about why!!

samsung-SM-A500FU_PT6662 did not have results at the end of tests - check the device logs about why!!

motorola-XT1072_PT1910 did not have results at the end of tests - check the device logs about why!!

2015-11-24T16:31:23.405Z (1380 sec) - Android All tests are done, preparing test report

--------------- test report ---------------------
--------------- LGE-LG-H815_PT7587 --------------------- : 1
sendList : 100% : 60637 ms, 99% : 60637 ms, 95 : 42933 ms, 90% : 42933 ms.

Result count 11, range 4835 ms to  60637 ms.
sendList failed peers count : 8 [42.10526315789474 %]
- Peer ID : 44:80:EB:7B:5A:05, Tried : 2

- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 2
- Peer ID : 34:FC:EF:11:B1:66, Tried : 2

sendList never tried peers count : 0 [0 %]
--------------- HTC-HTC Desire 820_PT6452 --------------------- : 2
sendList : 100% : 159060 ms, 99% : 159060 ms, 95 : 31686 ms, 90% : 31686 ms.
Result count 12, range 4160 ms to  159060 ms.
sendList failed peers count : 7 [36.8421052631579 %]
- Peer ID : 34:FC:EF:11:AE:67, Tried : 2

- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 2
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 2
- Peer ID : 80:01:84:8A:B3:68, Tried : 2
- Peer ID : 44:80:EB:7B:5A:05, Tried : 2
- Peer ID : 34:FC:EF:11:B1:66, Tried : 2

sendList never tried peers count : 0 [0 %]
--------------- LGE-Nexus 5_PT474 --------------------- : 3
sendList : 100% : 104695 ms, 99% : 104695 ms, 95 : 104695 ms, 90% : 50345 ms.
Result count 6, range 3088 ms to  104695 ms.
sendList failed peers count : 11 [64.70588235294117 %]
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1

- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
sendList never tried peers count : 2 [10.526315789473685 %]
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 08:EC:A9:50:76:27
--------------- samsung-SM-A300FU_PT2521 --------------------- : 4
sendList : 100% : 77389 ms, 99% : 77389 ms, 95 : 31270 ms, 90% : 31270 ms.
Result count 15, range 2245 ms to  77389 ms.
sendList failed peers count : 4 [21.05263157894737 %]
- Peer ID : 44:80:EB:7B:5A:05, Tried : 4
- Peer ID : 80:01:84:8A:B3:68, Tried : 3
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 3
- Peer ID : 34:FC:EF:11:B1:66, Tried : 4
sendList never tried peers count : 0 [0 %]
--------------- LGE-LG-D855_PT6302 --------------------- : 5
sendList : 100% : 72366 ms, 99% : 72366 ms, 95 : 60257 ms, 90% : 60257 ms.
Result count 14, range 3550 ms to  72366 ms.
sendList failed peers count : 5 [26.31578947368421 %]
- Peer ID : 80:01:84:8A:B3:68, Tried : 3
- Peer ID : 34:FC:EF:11:B1:66, Tried : 2
- Peer ID : 34:FC:EF:11:AE:67, Tried : 2
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 2
- Peer ID : 08:EC:A9:50:75:41, Tried : 2
sendList never tried peers count : 0 [0 %]
--------------- HUAWEI-ALE-L21_PT5583 --------------------- : 6
sendList : 100% : 42308 ms, 99% : 42308 ms, 95 : 42308 ms, 90% : 26031 ms.
Result count 7, range 14353 ms to  42308 ms.
sendList failed peers count : 7 [50 %]
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
sendList never tried peers count : 5 [26.31578947368421 %]
- Peer ID : E0:DB:10:1F:C9:5E

- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 50:2E:6C:AC:21:50
--------------- motorola-Nexus 6_PT5708 --------------------- : 7
sendList : 100% : 66911 ms, 99% : 66911 ms, 95 : 51474 ms, 90% : 51474 ms.
Result count 15, range 2386 ms to  66911 ms.
sendList failed peers count : 4 [21.05263157894737 %]
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 3
- Peer ID : 34:FC:EF:11:B1:66, Tried : 3
- Peer ID : 80:01:84:8A:B3:68, Tried : 3
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 3
sendList never tried peers count : 0 [0 %]
--------------- LGE-LG-D802_PT2047 --------------------- : 8
sendList : 100% : 76601 ms, 99% : 76601 ms, 95 : 67259 ms, 90% : 67259 ms.

Result count 11, range 8479 ms to  76601 ms.
sendList failed peers count : 8 [42.10526315789474 %]
- Peer ID : 34:FC:EF:11:AE:67, Tried : 2
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1

- Peer ID : 80:01:84:8A:B3:68, Tried : 2
- Peer ID : 34:FC:EF:11:B1:66, Tried : 2
- Peer ID : F8:95:C7:87:85:54, Tried : 2
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 2
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-G900F_PT2346 --------------------- : 9

sendList : 100% : 50708 ms, 99% : 50708 ms, 95 : 26773 ms, 90% : 26773 ms.
Result count 11, range 4190 ms to  50708 ms.
sendList failed peers count : 8 [42.10526315789474 %]
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 2
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1

- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 2
- Peer ID : 44:80:EB:7B:5A:05, Tried : 2
- Peer ID : 34:FC:EF:11:AE:67, Tried : 2
- Peer ID : F8:95:C7:87:85:54, Tried : 2
sendList never tried peers count : 0 [0 %]

--------------- HTC-HTC One_M8_PT4451 --------------------- : 10
sendList : 100% : 47740 ms, 99% : 47740 ms, 95 : 47740 ms, 90% : 47740 ms.
Result count 3, range 4771 ms to  47740 ms.
sendList failed peers count : 1 [25 %]
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
sendList never tried peers count : 15 [78.94736842105263 %]

- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : F8:95:C7:87:85:54
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 44:80:EB:7B:5A:05

- Peer ID : E0:DB:10:1F:C9:5E
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 34:FC:EF:9D:93:0B

- Peer ID : 00:F4:6F:30:E0:6C
--------------- Combined ---------------------

sendList : 100% : 159060 ms, 99% : 104695 ms, 95 : 67259 ms, 90% : 51474 ms.

--------------- end of test report ---------------------


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


#### Test 5253548629578ed Logs

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

2015-12-03T14:03:02.585Z (0 sec) - Android tests will start after waiting for 120 seconds

Test ID 0 configuration: testSendData.js, server timeout: 1200000, data:

{ timeout: 1000000,
  rounds: 1,
  dataTimeout: 10000,
  dataAmount: 100000,
  conReTryTimeout: 5000,
  conReTryCount: 5 }

2015-12-03T14:03:02.591Z (0 sec) - iOS tests will start after waiting for 120 seconds

listening on *:3000

2015-12-03T14:03:03.332Z (1 sec) - Android samsung-SM-G900F_PT411 added (current device count 1)

2015-12-03T14:03:04.060Z (2 sec) - Android samsung-SM-A300FU_PT2951 added (current device count 2)

2015-12-03T14:03:04.198Z (2 sec) - Android LGE-LG-H815_PT3634 added (current device count 3)

2015-12-03T14:03:04.239Z (2 sec) - Android HTC-HTC Desire 820_PT2326 added (current device count 4)

2015-12-03T14:03:04.591Z (2 sec) - Android LGE-Nexus 5_PT1117 added (current device count 5)

2015-12-03T14:03:04.610Z (2 sec) - Android HTC-HTC Desire 820_PT9389 added (current device count 6)

2015-12-03T14:03:04.700Z (2 sec) - iOS Apple-Iphone6-1_PT7057 added (current device count 1)

2015-12-03T14:03:04.896Z (2 sec) - Android samsung-SM-A500FU_PT7439 added (current device count 7)

2015-12-03T14:03:05.591Z (3 sec) - Android LGE-LG-D802_PT9133 added (current device count 8)

2015-12-03T14:03:05.890Z (3 sec) - iOS Apple-Iphone5s-1_PT7727 added (current device count 2)

2015-12-03T14:03:06.169Z (4 sec) - iOS Apple-IpadAir2-1_PT7511 added (current device count 3)

2015-12-03T14:03:06.189Z (4 sec) - Android samsung-SM-N910C_PT7904 added (current device count 9)

2015-12-03T14:03:06.303Z (4 sec) - iOS Apple-Iphone5-1_PT2690 added (current device count 4)

2015-12-03T14:03:06.391Z (4 sec) - Android motorola-XT1072_PT4866 added (current device count 10)

2015-12-03T14:03:06.438Z (4 sec) - Android LGE-LG-D722_PT2226 added (current device count 11)

2015-12-03T14:03:06.456Z (4 sec) - Android LGE-LG-D855_PT6183 added (current device count 12)

2015-12-03T14:03:06.737Z (4 sec) - Android samsung-SM-A300FU_PT1913 added (current device count 13)

2015-12-03T14:03:07.210Z (5 sec) - Android samsung-SM-G900F_PT5769 added (current device count 14)

2015-12-03T14:03:07.508Z (5 sec) - Android HUAWEI-ALE-L21_PT7421 added (current device count 15)

2015-12-03T14:03:07.514Z (5 sec) - Android LGE-Nexus 5_PT1565 added (current device count 16)

2015-12-03T14:03:09.667Z (7 sec) - Android samsung-SM-G800F_PT5597 added (current device count 17)

2015-12-03T14:03:11.228Z (9 sec) - Android motorola-XT1039_PT7616 added (current device count 18)

-------------- We got wait done, now starting the testing process ------------------

2015-12-03T14:05:02.624Z (120 sec) - Android start testing now with 18 devices

2015-12-03T14:05:02.648Z (120 sec) - iOS start testing now with 4 devices

2015-12-03T14:05:41.802Z (159 sec) - Android HTC-HTC Desire 820_PT9389 got re-connected event

2015-12-03T14:06:09.355Z (187 sec) - Android HTC-HTC Desire 820_PT2326 got disconnected

2015-12-03T14:06:21.563Z (199 sec) - Android LGE-Nexus 5_PT1565 got re-connected event

2015-12-03T14:06:34.809Z (212 sec) - Android HTC-HTC Desire 820_PT9389 got disconnected

2015-12-03T14:06:37.739Z (215 sec) - Android LGE-Nexus 5_PT1565 got disconnected

2015-12-03T14:06:57.602Z (235 sec) - iOS Apple-Iphone6-1_PT7057 test took 114953ms - results peers[0], reConnects[0], sendData[3]

2015-12-03T14:07:46.564Z (284 sec) - Android LGE-Nexus 5_PT1565 got disconnected

2015-12-03T14:07:51.460Z (289 sec) - Android HTC-HTC Desire 820_PT2326 got re-connected event

2015-12-03T14:08:38.388Z (336 sec) - Android LGE-LG-D802_PT9133 got re-connected event

2015-12-03T14:08:39.280Z (337 sec) - iOS Apple-Iphone5s-1_PT7727 test took 216630ms - results peers[0], reConnects[0], sendData[3]

2015-12-03T14:08:44.330Z (342 sec) - iOS Apple-IpadAir2-1_PT7511 test took 221680ms - results peers[0], reConnects[0], sendData[3]

2015-12-03T14:08:47.068Z (345 sec) - iOS Apple-Iphone5-1_PT2690 test took 224418ms - results peers[0], reConnects[0], sendData[3]

2015-12-03T14:08:47.069Z (345 sec) - iOS test ID 0 done now

2015-12-03T14:08:47.076Z (345 sec) - iOS All tests are done, preparing test report

--------------- test report ---------------------

--------------- Apple-Iphone6-1_PT7057 --------------------- : 1

sendList : 100% : 4148 ms, 99% : 4148 ms, 95 : 4148 ms, 90% : 4148 ms.

Average data rate: 0.025 MB/s

Result count 2, range 3962 ms to  4148 ms.

sendList failed peers count : 1 [33.333333333333336 %]

- Peer ID : Apple-Iphone5s-1_PT7727.aEO4Zw==, Tried : 5

sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5s-1_PT7727 --------------------- : 2
sendList : 100% : 2832 ms, 99% : 2832 ms, 95 : 2832 ms, 90% : 2832 ms.
Average data rate: 0.035 MB/s
Result count 1, range 2832 ms to  2832 ms.

sendList failed peers count : 2 [66.66666666666667 %]
- Peer ID : Apple-Iphone5-1_PT2690.vOZHlg==, Tried : 5
- Peer ID : Apple-IpadAir2-1_PT7511.wgBJEg==, Tried : 5

sendList never tried peers count : 0 [0 %]
--------------- Apple-IpadAir2-1_PT7511 --------------------- : 3

sendList : 100% : 4062 ms, 99% : 4062 ms, 95 : 4062 ms, 90% : 4062 ms.
Average data rate: 0.025 MB/s
Result count 1, range 4062 ms to  4062 ms.

sendList failed peers count : 2 [66.66666666666667 %]
- Peer ID : Apple-Iphone6-1_PT7057.4CFLyQ==, Tried : 5
- Peer ID : Apple-Iphone5s-1_PT7727.aEO4Zw==, Tried : 5

sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5-1_PT2690 --------------------- : 4
sendList : 100% : 3762 ms, 99% : 3762 ms, 95 : 3762 ms, 90% : 3762 ms.

Average data rate: 0.027 MB/s
Result count 1, range 3762 ms to  3762 ms.
sendList failed peers count : 2 [66.66666666666667 %]

- Peer ID : Apple-IpadAir2-1_PT7511.wgBJEg==, Tried : 5
- Peer ID : Apple-Iphone6-1_PT7057.4CFLyQ==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Combined ---------------------
sendList : 100% : 4148 ms, 99% : 4148 ms, 95 : 4148 ms, 90% : 4148 ms.
Average data rate: 0.027 MB/s

--------------- end of test report ---------------------

2015-12-03T14:08:47.414Z (345 sec) - iOS Apple-Iphone6-1_PT7057 got disconnected

2015-12-03T14:08:47.473Z (345 sec) - iOS Apple-IpadAir2-1_PT7511 got disconnected

2015-12-03T14:08:47.606Z (345 sec) - iOS Apple-Iphone5s-1_PT7727 got disconnected

2015-12-03T14:08:56.784Z (354 sec) - iOS Apple-Iphone5-1_PT2690 got disconnected

2015-12-03T14:09:07.009Z (364 sec) - Android LGE-LG-D802_PT9133 got disconnected

2015-12-03T14:09:36.342Z (394 sec) - Android samsung-SM-G800F_PT5597 got disconnected

2015-12-03T14:11:03.707Z (481 sec) - Android HTC-HTC Desire 820_PT2326 got disconnected

2015-12-03T14:11:09.567Z (487 sec) - Android motorola-XT1039_PT7616 got re-connected event

2015-12-03T14:11:12.490Z (490 sec) - Android LGE-LG-H815_PT3634 got re-connected event

2015-12-03T14:11:48.025Z (525 sec) - Android motorola-XT1039_PT7616 got disconnected

2015-12-03T14:12:02.307Z (540 sec) - Android LGE-LG-H815_PT3634 got disconnected

2015-12-03T14:12:33.974Z (571 sec) - Android LGE-LG-D855_PT6183 got disconnected

2015-12-03T14:13:04.464Z (602 sec) - Android motorola-XT1072_PT4866 got disconnected

2015-12-03T14:13:11.774Z (609 sec) - Android motorola-XT1072_PT4866 got re-connected event

2015-12-03T14:16:02.096Z (780 sec) - Android HTC-HTC Desire 820_PT9389 got disconnected

2015-12-03T14:17:30.930Z (868 sec) - Android HTC-HTC Desire 820_PT9389 got re-connected event

2015-12-03T14:18:33.463Z (931 sec) - Android motorola-XT1039_PT7616 got re-connected event

2015-12-03T14:18:52.714Z (950 sec) - Android motorola-XT1039_PT7616 got disconnected

2015-12-03T14:21:42.911Z (1120 sec) - Android HUAWEI-ALE-L21_PT7421 test took 1000270ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T14:21:42.961Z (1120 sec) - Android samsung-SM-A500FU_PT7439 test took 1000326ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T14:21:43.019Z (1120 sec) - Android motorola-XT1039_PT7616 test took 1000376ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T14:21:43.027Z (1120 sec) - Android samsung-SM-N910C_PT7904 test took 1000389ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T14:21:43.040Z (1120 sec) - Android LGE-LG-D722_PT2226 test took 1000401ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T14:21:43.193Z (1121 sec) - Android LGE-LG-H815_PT3634 test took 1000560ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T14:21:43.200Z (1121 sec) - Android samsung-SM-A300FU_PT1913 test took 1000559ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T14:21:43.330Z (1121 sec) - Android samsung-SM-G900F_PT5769 test took 1000689ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T14:21:43.417Z (1121 sec) - Android samsung-SM-A300FU_PT2951 test took 1000785ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T14:21:43.459Z (1121 sec) - Android LGE-Nexus 5_PT1117 test took 1000825ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T14:21:43.510Z (1121 sec) - Android motorola-XT1072_PT4866 test took 1000872ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T14:21:43.552Z (1121 sec) - Android HTC-HTC Desire 820_PT9389 test took 1000917ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T14:21:43.592Z (1121 sec) - Android samsung-SM-G900F_PT411 test took 1000962ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T14:21:45.360Z (1123 sec) - Android LGE-LG-D802_PT9133 test took 1002724ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T14:25:02.646Z (1320 sec) - Server timeout reached!

2015-12-03T14:25:02.649Z (1320 sec) - Send timeout to HTC-HTC Desire 820_PT2326

2015-12-03T14:25:02.651Z (1320 sec) - Send timeout to LGE-LG-D855_PT6183

2015-12-03T14:25:02.653Z (1320 sec) - Send timeout to LGE-Nexus 5_PT1565

2015-12-03T14:25:02.654Z (1320 sec) - Send timeout to samsung-SM-G800F_PT5597

2015-12-03T14:26:02.659Z (1380 sec) - Did not get reports from all devices, but forcing tests to finish!

HTC-HTC Desire 820_PT2326 did not have results at the end of tests - check the device logs about why!!

LGE-LG-D855_PT6183 did not have results at the end of tests - check the device logs about why!!

LGE-Nexus 5_PT1565 did not have results at the end of tests - check the device logs about why!!

samsung-SM-G800F_PT5597 did not have results at the end of tests - check the device logs about why!!

2015-12-03T14:26:02.675Z (1380 sec) - Android All tests are done, preparing test report

--------------- test report ---------------------
--------------- samsung-SM-G900F_PT411 --------------------- : 1

sendList : 100% : 3468 ms, 99% : 3468 ms, 95 : 3468 ms, 90% : 3468 ms.
Average data rate: 0.029 MB/s
Result count 1, range 3468 ms to  3468 ms.
sendList failed peers count : 10 [90.9090909090909 %]

- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1

- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
sendList never tried peers count : 6 [35.294117647058826 %]

- Peer ID : F8:95:C7:87:85:54
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 34:FC:EF:11:B1:66

- Peer ID : 80:01:84:8A:B3:68
--------------- samsung-SM-A300FU_PT2951 --------------------- : 2
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 9 [100 %]
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
sendList never tried peers count : 8 [47.05882352941177 %]
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : B0:C5:59:3F:75:69
--------------- LGE-LG-H815_PT3634 --------------------- : 3
sendList : 100% : 64351 ms, 99% : 64351 ms, 95 : 64351 ms, 90% : 64351 ms.
Average data rate: 0.002 MB/s
Result count 2, range 40977 ms to  64351 ms.
sendList failed peers count : 8 [80 %]
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
sendList never tried peers count : 7 [41.1764705882353 %]
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : F8:95:C7:87:85:54
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 08:EC:A9:50:76:27
--------------- LGE-Nexus 5_PT1117 --------------------- : 4
sendList : 100% : 50697 ms, 99% : 50697 ms, 95 : 50697 ms, 90% : 50697 ms.
Average data rate: 0.004 MB/s
Result count 3, range 6111 ms to  50697 ms.
sendList failed peers count : 8 [72.72727272727273 %]
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
sendList never tried peers count : 6 [35.294117647058826 %]
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 58:3F:54:73:64:C0
--------------- HTC-HTC Desire 820_PT9389 --------------------- : 5
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 9 [100 %]
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
sendList never tried peers count : 8 [47.05882352941177 %]
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 34:FC:EF:11:B1:66
--------------- samsung-SM-A500FU_PT7439 --------------------- : 6
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 9 [100 %]
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
sendList never tried peers count : 8 [47.05882352941177 %]
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 58:2A:F7:ED:96:BE
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 00:F4:6F:30:E0:6C
--------------- LGE-LG-D802_PT9133 --------------------- : 7
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 8 [100 %]
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
sendList never tried peers count : 9 [52.94117647058823 %]
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : F8:95:C7:87:85:54
--------------- samsung-SM-N910C_PT7904 --------------------- : 8
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 9 [100 %]
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
sendList never tried peers count : 8 [47.05882352941177 %]
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 7C:F9:0E:34:8A:A0
--------------- motorola-XT1072_PT4866 --------------------- : 9
sendList : 100% : 10869 ms, 99% : 10869 ms, 95 : 10869 ms, 90% : 10869 ms.
Average data rate: 0.009 MB/s
Result count 1, range 10869 ms to  10869 ms.
sendList failed peers count : 9 [90 %]
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
sendList never tried peers count : 7 [41.1764705882353 %]
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 58:2A:F7:ED:96:BE
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 34:FC:EF:11:AE:67
--------------- LGE-LG-D722_PT2226 --------------------- : 10
sendList : 100% : 50317 ms, 99% : 50317 ms, 95 : 50317 ms, 90% : 50317 ms.
Average data rate: 0.005 MB/s
Result count 3, range 4825 ms to  50317 ms.
sendList failed peers count : 9 [75 %]
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1

- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
sendList never tried peers count : 5 [29.41176470588235 %]
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 58:2A:F7:ED:96:BE
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 7C:F9:0E:34:8A:A0
--------------- samsung-SM-A300FU_PT1913 --------------------- : 11
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 9 [100 %]
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
sendList never tried peers count : 8 [47.05882352941177 %]
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : E0:DB:10:14:E2:C0
--------------- samsung-SM-G900F_PT5769 --------------------- : 12
sendList : 100% : 24975 ms, 99% : 24975 ms, 95 : 24975 ms, 90% : 24975 ms.
Average data rate: 0.004 MB/s
Result count 1, range 24975 ms to  24975 ms.
sendList failed peers count : 9 [90 %]
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1

sendList never tried peers count : 7 [41.1764705882353 %]
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : F8:95:C7:87:85:54
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 7C:F9:0E:37:96:AB
--------------- HUAWEI-ALE-L21_PT7421 --------------------- : 13

sendList : 100% : 2182 ms, 99% : 2182 ms, 95 : 2182 ms, 90% : 2182 ms.

Average data rate: 0.046 MB/s

Result count 1, range 2182 ms to  2182 ms.
sendList failed peers count : 8 [88.88888888888889 %]
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
sendList never tried peers count : 8 [47.05882352941177 %]
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : F8:95:C7:87:85:54
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 00:F4:6F:30:E0:6C

- Peer ID : 08:EC:A9:50:75:41
- Peer ID : 58:3F:54:73:64:C0
--------------- motorola-XT1039_PT7616 --------------------- : 14
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 10 [100 %]
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
sendList never tried peers count : 7 [41.1764705882353 %]
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : F8:95:C7:87:85:54
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : F8:95:C7:87:3C:51
--------------- Combined ---------------------

sendList : 100% : 64351 ms, 99% : 64351 ms, 95 : 50697 ms, 90% : 50697 ms.
Average data rate: 0.004 MB/s
--------------- end of test report ---------------------

2015-12-03T14:26:02.982Z (1380 sec) - Android LGE-LG-D802_PT9133 got disconnected

2015-12-03T14:26:03.072Z (1381 sec) - Android samsung-SM-N910C_PT7904 got disconnected

2015-12-03T14:26:03.081Z (1381 sec) - Android samsung-SM-G900F_PT411 got disconnected

2015-12-03T14:26:03.086Z (1381 sec) - Android LGE-LG-D722_PT2226 got disconnected

2015-12-03T14:26:03.171Z (1381 sec) - Android samsung-SM-G900F_PT5769 got disconnected

2015-12-03T14:26:03.200Z (1381 sec) - Android LGE-LG-H815_PT3634 got disconnected

2015-12-03T14:26:03.214Z (1381 sec) - Android motorola-XT1072_PT4866 got disconnected

2015-12-03T14:26:04.095Z (1382 sec) - Android HTC-HTC Desire 820_PT9389 got disconnected

2015-12-03T14:26:04.249Z (1382 sec) - Android samsung-SM-A300FU_PT2951 got disconnected

2015-12-03T14:26:04.853Z (1382 sec) - Android samsung-SM-A300FU_PT1913 got disconnected

2015-12-03T14:26:09.229Z (1387 sec) - Android samsung-SM-A500FU_PT7439 got disconnected

2015-12-03T14:27:03.769Z (1441 sec) - Android LGE-Nexus 5_PT1117 got disconnected

2015-12-03T14:27:10.214Z (1448 sec) - Android HUAWEI-ALE-L21_PT7421 got disconnected

2015-12-03T14:27:13.236Z (1451 sec) - Android motorola-XT1039_PT7616 got disconnected


 
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
STOP log received from  f56ad48d Test has  SUCCEEDED
Device test finished on f56ad48d 
Android task is completed. [SUCCESS]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/5253548629578ed_Require_newer_Cordova_versions__vjrantal/thali01_LGE-LG-H815.md)

[HUAWEI-ALE-L21](https://github.com/ThaliTester/TestResults/blob/5253548629578ed_Require_newer_Cordova_versions__vjrantal/thali01_HUAWEI-ALE-L21.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/5253548629578ed_Require_newer_Cordova_versions__vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/5253548629578ed_Require_newer_Cordova_versions__vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/5253548629578ed_Require_newer_Cordova_versions__vjrantal/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
STOP log received from  TA4750HV7I Test has  SUCCEEDED
Device test finished on TA4750HV7I 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD8553bed2d08 app:com.test.thalitest code:0 
child process exited with code 0 on device LGD8553bed2d08 
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:null 
child process exited with code null on device 320414cd475f91e3 
Android task is completed. [FAILED]
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/5253548629578ed_Require_newer_Cordova_versions__vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/5253548629578ed_Require_newer_Cordova_versions__vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/5253548629578ed_Require_newer_Cordova_versions__vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
STOP log received from  0be0c6c6 Test has  SUCCEEDED
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Device test finished on ZX1C223JKW 
Device test finished on 0be0c6c6 
Android task is completed. [SUCCESS]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/5253548629578ed_Require_newer_Cordova_versions__vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/5253548629578ed_Require_newer_Cordova_versions__vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/5253548629578ed_Require_newer_Cordova_versions__vjrantal/thali04_samsung-SM-G900F.md)

####Node name: thali06
Console output:
```
STOP log received from  022678fb504e29b0 Test has  SUCCEEDED
STOP log received from  7970f88c Test has  SUCCEEDED
Device test finished on 022678fb504e29b0 
Device test finished on 7970f88c 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:null 
child process exited with code null on device FA55PYS00566 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/5253548629578ed_Require_newer_Cordova_versions__vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/5253548629578ed_Require_newer_Cordova_versions__vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/5253548629578ed_Require_newer_Cordova_versions__vjrantal/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/5253548629578ed_Require_newer_Cordova_versions__vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/5253548629578ed_Require_newer_Cordova_versions__vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
STOP log received from  HT574YC04723 Test has  SUCCEEDED
STOP log received from  4325e43f Test has  SUCCEEDED
Device test finished on 4325e43f 
Device test finished on HT574YC04723 
Android task is completed. [SUCCESS]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/5253548629578ed_Require_newer_Cordova_versions__vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/5253548629578ed_Require_newer_Cordova_versions__vjrantal/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/5253548629578ed_Require_newer_Cordova_versions__vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/5253548629578ed_Require_newer_Cordova_versions__vjrantal/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/5253548629578ed_Require_newer_Cordova_versions__vjrantal/iOS_Iphone5-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/5253548629578ed_Require_newer_Cordova_versions__vjrantal/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/5253548629578ed_Require_newer_Cordova_versions__vjrantal/iOS_Iphone6-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/5253548629578ed_Require_newer_Cordova_versions__vjrantal/iOS_IpadAir2-1.md)


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

2015-12-03T14:03:02.585Z (0 sec) - Android tests will start after waiting for 120 seconds

Test ID 0 configuration: testSendData.js, server timeout: 1200000, data:

{ timeout: 1000000,
  rounds: 1,
  dataTimeout: 10000,
  dataAmount: 100000,
  conReTryTimeout: 5000,
  conReTryCount: 5 }

2015-12-03T14:03:02.591Z (0 sec) - iOS tests will start after waiting for 120 seconds

listening on *:3000

2015-12-03T14:03:03.332Z (1 sec) - Android samsung-SM-G900F_PT411 added (current device count 1)

2015-12-03T14:03:04.060Z (2 sec) - Android samsung-SM-A300FU_PT2951 added (current device count 2)

2015-12-03T14:03:04.198Z (2 sec) - Android LGE-LG-H815_PT3634 added (current device count 3)

2015-12-03T14:03:04.239Z (2 sec) - Android HTC-HTC Desire 820_PT2326 added (current device count 4)

2015-12-03T14:03:04.591Z (2 sec) - Android LGE-Nexus 5_PT1117 added (current device count 5)

2015-12-03T14:03:04.610Z (2 sec) - Android HTC-HTC Desire 820_PT9389 added (current device count 6)

2015-12-03T14:03:04.700Z (2 sec) - iOS Apple-Iphone6-1_PT7057 added (current device count 1)

2015-12-03T14:03:04.896Z (2 sec) - Android samsung-SM-A500FU_PT7439 added (current device count 7)

2015-12-03T14:03:05.591Z (3 sec) - Android LGE-LG-D802_PT9133 added (current device count 8)

2015-12-03T14:03:05.890Z (3 sec) - iOS Apple-Iphone5s-1_PT7727 added (current device count 2)

2015-12-03T14:03:06.169Z (4 sec) - iOS Apple-IpadAir2-1_PT7511 added (current device count 3)

2015-12-03T14:03:06.189Z (4 sec) - Android samsung-SM-N910C_PT7904 added (current device count 9)

2015-12-03T14:03:06.303Z (4 sec) - iOS Apple-Iphone5-1_PT2690 added (current device count 4)

2015-12-03T14:03:06.391Z (4 sec) - Android motorola-XT1072_PT4866 added (current device count 10)

2015-12-03T14:03:06.438Z (4 sec) - Android LGE-LG-D722_PT2226 added (current device count 11)

2015-12-03T14:03:06.456Z (4 sec) - Android LGE-LG-D855_PT6183 added (current device count 12)

2015-12-03T14:03:06.737Z (4 sec) - Android samsung-SM-A300FU_PT1913 added (current device count 13)

2015-12-03T14:03:07.210Z (5 sec) - Android samsung-SM-G900F_PT5769 added (current device count 14)

2015-12-03T14:03:07.508Z (5 sec) - Android HUAWEI-ALE-L21_PT7421 added (current device count 15)

2015-12-03T14:03:07.514Z (5 sec) - Android LGE-Nexus 5_PT1565 added (current device count 16)

2015-12-03T14:03:09.667Z (7 sec) - Android samsung-SM-G800F_PT5597 added (current device count 17)

2015-12-03T14:03:11.228Z (9 sec) - Android motorola-XT1039_PT7616 added (current device count 18)

-------------- We got wait done, now starting the testing process ------------------

2015-12-03T14:05:02.624Z (120 sec) - Android start testing now with 18 devices

2015-12-03T14:05:02.648Z (120 sec) - iOS start testing now with 4 devices

2015-12-03T14:05:41.802Z (159 sec) - Android HTC-HTC Desire 820_PT9389 got re-connected event

2015-12-03T14:06:09.355Z (187 sec) - Android HTC-HTC Desire 820_PT2326 got disconnected

2015-12-03T14:06:21.563Z (199 sec) - Android LGE-Nexus 5_PT1565 got re-connected event

2015-12-03T14:06:34.809Z (212 sec) - Android HTC-HTC Desire 820_PT9389 got disconnected

2015-12-03T14:06:37.739Z (215 sec) - Android LGE-Nexus 5_PT1565 got disconnected

2015-12-03T14:06:57.602Z (235 sec) - iOS Apple-Iphone6-1_PT7057 test took 114953ms - results peers[0], reConnects[0], sendData[3]

2015-12-03T14:07:46.564Z (284 sec) - Android LGE-Nexus 5_PT1565 got disconnected

2015-12-03T14:07:51.460Z (289 sec) - Android HTC-HTC Desire 820_PT2326 got re-connected event

2015-12-03T14:08:38.388Z (336 sec) - Android LGE-LG-D802_PT9133 got re-connected event

2015-12-03T14:08:39.280Z (337 sec) - iOS Apple-Iphone5s-1_PT7727 test took 216630ms - results peers[0], reConnects[0], sendData[3]

2015-12-03T14:08:44.330Z (342 sec) - iOS Apple-IpadAir2-1_PT7511 test took 221680ms - results peers[0], reConnects[0], sendData[3]

2015-12-03T14:08:47.068Z (345 sec) - iOS Apple-Iphone5-1_PT2690 test took 224418ms - results peers[0], reConnects[0], sendData[3]

2015-12-03T14:08:47.069Z (345 sec) - iOS test ID 0 done now

2015-12-03T14:08:47.076Z (345 sec) - iOS All tests are done, preparing test report

--------------- test report ---------------------

--------------- Apple-Iphone6-1_PT7057 --------------------- : 1

sendList : 100% : 4148 ms, 99% : 4148 ms, 95 : 4148 ms, 90% : 4148 ms.

Average data rate: 0.025 MB/s

Result count 2, range 3962 ms to  4148 ms.

sendList failed peers count : 1 [33.333333333333336 %]

- Peer ID : Apple-Iphone5s-1_PT7727.aEO4Zw==, Tried : 5

sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5s-1_PT7727 --------------------- : 2
sendList : 100% : 2832 ms, 99% : 2832 ms, 95 : 2832 ms, 90% : 2832 ms.
Average data rate: 0.035 MB/s
Result count 1, range 2832 ms to  2832 ms.

sendList failed peers count : 2 [66.66666666666667 %]
- Peer ID : Apple-Iphone5-1_PT2690.vOZHlg==, Tried : 5
- Peer ID : Apple-IpadAir2-1_PT7511.wgBJEg==, Tried : 5

sendList never tried peers count : 0 [0 %]
--------------- Apple-IpadAir2-1_PT7511 --------------------- : 3

sendList : 100% : 4062 ms, 99% : 4062 ms, 95 : 4062 ms, 90% : 4062 ms.
Average data rate: 0.025 MB/s
Result count 1, range 4062 ms to  4062 ms.

sendList failed peers count : 2 [66.66666666666667 %]
- Peer ID : Apple-Iphone6-1_PT7057.4CFLyQ==, Tried : 5
- Peer ID : Apple-Iphone5s-1_PT7727.aEO4Zw==, Tried : 5

sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5-1_PT2690 --------------------- : 4
sendList : 100% : 3762 ms, 99% : 3762 ms, 95 : 3762 ms, 90% : 3762 ms.

Average data rate: 0.027 MB/s
Result count 1, range 3762 ms to  3762 ms.
sendList failed peers count : 2 [66.66666666666667 %]

- Peer ID : Apple-IpadAir2-1_PT7511.wgBJEg==, Tried : 5
- Peer ID : Apple-Iphone6-1_PT7057.4CFLyQ==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Combined ---------------------
sendList : 100% : 4148 ms, 99% : 4148 ms, 95 : 4148 ms, 90% : 4148 ms.
Average data rate: 0.027 MB/s

--------------- end of test report ---------------------

2015-12-03T14:08:47.414Z (345 sec) - iOS Apple-Iphone6-1_PT7057 got disconnected

2015-12-03T14:08:47.473Z (345 sec) - iOS Apple-IpadAir2-1_PT7511 got disconnected

2015-12-03T14:08:47.606Z (345 sec) - iOS Apple-Iphone5s-1_PT7727 got disconnected

2015-12-03T14:08:56.784Z (354 sec) - iOS Apple-Iphone5-1_PT2690 got disconnected

2015-12-03T14:09:07.009Z (364 sec) - Android LGE-LG-D802_PT9133 got disconnected

2015-12-03T14:09:36.342Z (394 sec) - Android samsung-SM-G800F_PT5597 got disconnected

2015-12-03T14:11:03.707Z (481 sec) - Android HTC-HTC Desire 820_PT2326 got disconnected

2015-12-03T14:11:09.567Z (487 sec) - Android motorola-XT1039_PT7616 got re-connected event

2015-12-03T14:11:12.490Z (490 sec) - Android LGE-LG-H815_PT3634 got re-connected event

2015-12-03T14:11:48.025Z (525 sec) - Android motorola-XT1039_PT7616 got disconnected

2015-12-03T14:12:02.307Z (540 sec) - Android LGE-LG-H815_PT3634 got disconnected

2015-12-03T14:12:33.974Z (571 sec) - Android LGE-LG-D855_PT6183 got disconnected

2015-12-03T14:13:04.464Z (602 sec) - Android motorola-XT1072_PT4866 got disconnected

2015-12-03T14:13:11.774Z (609 sec) - Android motorola-XT1072_PT4866 got re-connected event

2015-12-03T14:16:02.096Z (780 sec) - Android HTC-HTC Desire 820_PT9389 got disconnected

2015-12-03T14:17:30.930Z (868 sec) - Android HTC-HTC Desire 820_PT9389 got re-connected event

2015-12-03T14:18:33.463Z (931 sec) - Android motorola-XT1039_PT7616 got re-connected event

2015-12-03T14:18:52.714Z (950 sec) - Android motorola-XT1039_PT7616 got disconnected

2015-12-03T14:21:42.911Z (1120 sec) - Android HUAWEI-ALE-L21_PT7421 test took 1000270ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T14:21:42.961Z (1120 sec) - Android samsung-SM-A500FU_PT7439 test took 1000326ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T14:21:43.019Z (1120 sec) - Android motorola-XT1039_PT7616 test took 1000376ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T14:21:43.027Z (1120 sec) - Android samsung-SM-N910C_PT7904 test took 1000389ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T14:21:43.040Z (1120 sec) - Android LGE-LG-D722_PT2226 test took 1000401ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T14:21:43.193Z (1121 sec) - Android LGE-LG-H815_PT3634 test took 1000560ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T14:21:43.200Z (1121 sec) - Android samsung-SM-A300FU_PT1913 test took 1000559ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T14:21:43.330Z (1121 sec) - Android samsung-SM-G900F_PT5769 test took 1000689ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T14:21:43.417Z (1121 sec) - Android samsung-SM-A300FU_PT2951 test took 1000785ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T14:21:43.459Z (1121 sec) - Android LGE-Nexus 5_PT1117 test took 1000825ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T14:21:43.510Z (1121 sec) - Android motorola-XT1072_PT4866 test took 1000872ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T14:21:43.552Z (1121 sec) - Android HTC-HTC Desire 820_PT9389 test took 1000917ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T14:21:43.592Z (1121 sec) - Android samsung-SM-G900F_PT411 test took 1000962ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T14:21:45.360Z (1123 sec) - Android LGE-LG-D802_PT9133 test took 1002724ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T14:25:02.646Z (1320 sec) - Server timeout reached!

2015-12-03T14:25:02.649Z (1320 sec) - Send timeout to HTC-HTC Desire 820_PT2326

2015-12-03T14:25:02.651Z (1320 sec) - Send timeout to LGE-LG-D855_PT6183

2015-12-03T14:25:02.653Z (1320 sec) - Send timeout to LGE-Nexus 5_PT1565

2015-12-03T14:25:02.654Z (1320 sec) - Send timeout to samsung-SM-G800F_PT5597

2015-12-03T14:26:02.659Z (1380 sec) - Did not get reports from all devices, but forcing tests to finish!

HTC-HTC Desire 820_PT2326 did not have results at the end of tests - check the device logs about why!!

LGE-LG-D855_PT6183 did not have results at the end of tests - check the device logs about why!!

LGE-Nexus 5_PT1565 did not have results at the end of tests - check the device logs about why!!

samsung-SM-G800F_PT5597 did not have results at the end of tests - check the device logs about why!!

2015-12-03T14:26:02.675Z (1380 sec) - Android All tests are done, preparing test report

--------------- test report ---------------------
--------------- samsung-SM-G900F_PT411 --------------------- : 1

sendList : 100% : 3468 ms, 99% : 3468 ms, 95 : 3468 ms, 90% : 3468 ms.
Average data rate: 0.029 MB/s
Result count 1, range 3468 ms to  3468 ms.
sendList failed peers count : 10 [90.9090909090909 %]

- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1

- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
sendList never tried peers count : 6 [35.294117647058826 %]

- Peer ID : F8:95:C7:87:85:54
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 34:FC:EF:11:B1:66

- Peer ID : 80:01:84:8A:B3:68
--------------- samsung-SM-A300FU_PT2951 --------------------- : 2
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 9 [100 %]
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
sendList never tried peers count : 8 [47.05882352941177 %]
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : B0:C5:59:3F:75:69
--------------- LGE-LG-H815_PT3634 --------------------- : 3
sendList : 100% : 64351 ms, 99% : 64351 ms, 95 : 64351 ms, 90% : 64351 ms.
Average data rate: 0.002 MB/s
Result count 2, range 40977 ms to  64351 ms.
sendList failed peers count : 8 [80 %]
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
sendList never tried peers count : 7 [41.1764705882353 %]
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : F8:95:C7:87:85:54
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 08:EC:A9:50:76:27
--------------- LGE-Nexus 5_PT1117 --------------------- : 4
sendList : 100% : 50697 ms, 99% : 50697 ms, 95 : 50697 ms, 90% : 50697 ms.
Average data rate: 0.004 MB/s
Result count 3, range 6111 ms to  50697 ms.
sendList failed peers count : 8 [72.72727272727273 %]
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
sendList never tried peers count : 6 [35.294117647058826 %]
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 58:3F:54:73:64:C0
--------------- HTC-HTC Desire 820_PT9389 --------------------- : 5
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 9 [100 %]
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
sendList never tried peers count : 8 [47.05882352941177 %]
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 34:FC:EF:11:B1:66
--------------- samsung-SM-A500FU_PT7439 --------------------- : 6
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 9 [100 %]
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
sendList never tried peers count : 8 [47.05882352941177 %]
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 58:2A:F7:ED:96:BE
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 00:F4:6F:30:E0:6C
--------------- LGE-LG-D802_PT9133 --------------------- : 7
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 8 [100 %]
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
sendList never tried peers count : 9 [52.94117647058823 %]
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : F8:95:C7:87:85:54
--------------- samsung-SM-N910C_PT7904 --------------------- : 8
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 9 [100 %]
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
sendList never tried peers count : 8 [47.05882352941177 %]
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 7C:F9:0E:34:8A:A0
--------------- motorola-XT1072_PT4866 --------------------- : 9
sendList : 100% : 10869 ms, 99% : 10869 ms, 95 : 10869 ms, 90% : 10869 ms.
Average data rate: 0.009 MB/s
Result count 1, range 10869 ms to  10869 ms.
sendList failed peers count : 9 [90 %]
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
sendList never tried peers count : 7 [41.1764705882353 %]
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 58:2A:F7:ED:96:BE
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 34:FC:EF:11:AE:67
--------------- LGE-LG-D722_PT2226 --------------------- : 10
sendList : 100% : 50317 ms, 99% : 50317 ms, 95 : 50317 ms, 90% : 50317 ms.
Average data rate: 0.005 MB/s
Result count 3, range 4825 ms to  50317 ms.
sendList failed peers count : 9 [75 %]
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1

- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
sendList never tried peers count : 5 [29.41176470588235 %]
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 58:2A:F7:ED:96:BE
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 7C:F9:0E:34:8A:A0
--------------- samsung-SM-A300FU_PT1913 --------------------- : 11
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 9 [100 %]
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
sendList never tried peers count : 8 [47.05882352941177 %]
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : E0:DB:10:14:E2:C0
--------------- samsung-SM-G900F_PT5769 --------------------- : 12
sendList : 100% : 24975 ms, 99% : 24975 ms, 95 : 24975 ms, 90% : 24975 ms.
Average data rate: 0.004 MB/s
Result count 1, range 24975 ms to  24975 ms.
sendList failed peers count : 9 [90 %]
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1

sendList never tried peers count : 7 [41.1764705882353 %]
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : F8:95:C7:87:85:54
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 7C:F9:0E:37:96:AB
--------------- HUAWEI-ALE-L21_PT7421 --------------------- : 13

sendList : 100% : 2182 ms, 99% : 2182 ms, 95 : 2182 ms, 90% : 2182 ms.

Average data rate: 0.046 MB/s

Result count 1, range 2182 ms to  2182 ms.
sendList failed peers count : 8 [88.88888888888889 %]
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
sendList never tried peers count : 8 [47.05882352941177 %]
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : F8:95:C7:87:85:54
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 00:F4:6F:30:E0:6C

- Peer ID : 08:EC:A9:50:75:41
- Peer ID : 58:3F:54:73:64:C0
--------------- motorola-XT1039_PT7616 --------------------- : 14
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 10 [100 %]
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
sendList never tried peers count : 7 [41.1764705882353 %]
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : F8:95:C7:87:85:54
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : F8:95:C7:87:3C:51
--------------- Combined ---------------------

sendList : 100% : 64351 ms, 99% : 64351 ms, 95 : 50697 ms, 90% : 50697 ms.
Average data rate: 0.004 MB/s
--------------- end of test report ---------------------

2015-12-03T14:26:02.982Z (1380 sec) - Android LGE-LG-D802_PT9133 got disconnected

2015-12-03T14:26:03.072Z (1381 sec) - Android samsung-SM-N910C_PT7904 got disconnected

2015-12-03T14:26:03.081Z (1381 sec) - Android samsung-SM-G900F_PT411 got disconnected

2015-12-03T14:26:03.086Z (1381 sec) - Android LGE-LG-D722_PT2226 got disconnected

2015-12-03T14:26:03.171Z (1381 sec) - Android samsung-SM-G900F_PT5769 got disconnected

2015-12-03T14:26:03.200Z (1381 sec) - Android LGE-LG-H815_PT3634 got disconnected

2015-12-03T14:26:03.214Z (1381 sec) - Android motorola-XT1072_PT4866 got disconnected

2015-12-03T14:26:04.095Z (1382 sec) - Android HTC-HTC Desire 820_PT9389 got disconnected

2015-12-03T14:26:04.249Z (1382 sec) - Android samsung-SM-A300FU_PT2951 got disconnected

2015-12-03T14:26:04.853Z (1382 sec) - Android samsung-SM-A300FU_PT1913 got disconnected

2015-12-03T14:26:09.229Z (1387 sec) - Android samsung-SM-A500FU_PT7439 got disconnected

2015-12-03T14:27:03.769Z (1441 sec) - Android LGE-Nexus 5_PT1117 got disconnected

2015-12-03T14:27:10.214Z (1448 sec) - Android HUAWEI-ALE-L21_PT7421 got disconnected

2015-12-03T14:27:13.236Z (1451 sec) - Android motorola-XT1039_PT7616 got disconnected


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


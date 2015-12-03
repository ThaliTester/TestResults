#### Test 525393149f38b37 Logs

Status: 
```

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code 254 on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
ios: child process exited with code 254 on device 2a65f58f9902a701b5c9a55b2befb18672927474 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true


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

2015-12-03T15:24:43.022Z (0 sec) - Android tests will start after waiting for 120 seconds

Test ID 0 configuration: testSendData.js, server timeout: 1200000, data:

{ timeout: 1000000,
  rounds: 1,
  dataTimeout: 10000,
  dataAmount: 100000,
  conReTryTimeout: 5000,
  conReTryCount: 5 }

2015-12-03T15:24:43.027Z (0 sec) - iOS tests will start after waiting for 120 seconds

listening on *:3000

2015-12-03T15:24:43.414Z (0 sec) - Android LGE-Nexus 5_PT8949 added (current device count 1)

2015-12-03T15:24:43.579Z (1 sec) - Android samsung-SM-A500FU_PT9149 added (current device count 2)

2015-12-03T15:24:43.695Z (1 sec) - Android LGE-LG-D802_PT2424 added (current device count 3)

2015-12-03T15:24:43.842Z (1 sec) - Android HUAWEI-ALE-L21_PT4138 added (current device count 4)

2015-12-03T15:24:44.351Z (1 sec) - Android samsung-SM-G800F_PT5407 added (current device count 5)

2015-12-03T15:24:45.508Z (3 sec) - iOS Apple-IpadAir2-1_PT2877 added (current device count 1)

2015-12-03T15:24:45.595Z (3 sec) - Android LGE-Nexus 5_PT8412 added (current device count 6)

2015-12-03T15:24:46.563Z (4 sec) - Android samsung-SM-A300FU_PT9205 added (current device count 7)

2015-12-03T15:24:46.868Z (4 sec) - Android samsung-SM-A300FU_PT5175 added (current device count 8)

2015-12-03T15:24:46.971Z (4 sec) - iOS Apple-Iphone5-1_PT9874 added (current device count 2)

2015-12-03T15:24:47.135Z (4 sec) - Android samsung-SM-G900F_PT8445 added (current device count 9)

2015-12-03T15:24:47.152Z (4 sec) - Android HTC-HTC Desire 820_PT5486 added (current device count 10)

2015-12-03T15:24:47.314Z (4 sec) - Android HTC-HTC Desire 820_PT336 added (current device count 11)

2015-12-03T15:24:47.915Z (5 sec) - Android motorola-XT1039_PT5465 added (current device count 12)

2015-12-03T15:24:47.947Z (5 sec) - Android LGE-LG-D722_PT1540 added (current device count 13)

2015-12-03T15:24:47.964Z (5 sec) - Android LGE-LG-H815_PT6298 added (current device count 14)

2015-12-03T15:24:48.185Z (5 sec) - iOS Apple-Iphone6-1_PT4561 added (current device count 3)

2015-12-03T15:24:48.404Z (5 sec) - Android motorola-XT1072_PT5924 added (current device count 15)

2015-12-03T15:24:48.648Z (6 sec) - iOS Apple-Iphone5s-1_PT8182 added (current device count 4)

2015-12-03T15:24:49.988Z (7 sec) - Android samsung-SM-N910C_PT772 added (current device count 16)

2015-12-03T15:24:50.046Z (7 sec) - Android samsung-SM-G900F_PT7127 added (current device count 17)

-------------- We got wait done, now starting the testing process ------------------

2015-12-03T15:26:43.080Z (120 sec) - Android start testing now with 17 devices

2015-12-03T15:26:43.102Z (120 sec) - iOS start testing now with 4 devices

2015-12-03T15:26:56.930Z (134 sec) - Android LGE-Nexus 5_PT8412 got disconnected

2015-12-03T15:26:58.231Z (135 sec) - Android LGE-Nexus 5_PT8412 got re-connected event

2015-12-03T15:27:48.667Z (186 sec) - iOS Apple-Iphone5s-1_PT8182 got disconnected

2015-12-03T15:28:40.033Z (237 sec) - Android samsung-SM-A300FU_PT5175 got disconnected

2015-12-03T15:28:42.250Z (239 sec) - iOS Apple-IpadAir2-1_PT2877 test took 119147ms - results peers[0], reConnects[0], sendData[3]

2015-12-03T15:28:44.037Z (241 sec) - Android LGE-Nexus 5_PT8412 got re-connected event

2015-12-03T15:29:05.984Z (263 sec) - Android samsung-SM-G800F_PT5407 got disconnected

2015-12-03T15:29:13.213Z (270 sec) - Android LGE-Nexus 5_PT8412 got disconnected

2015-12-03T15:30:16.545Z (334 sec) - iOS Apple-Iphone6-1_PT4561 test took 213441ms - results peers[0], reConnects[0], sendData[3]

2015-12-03T15:30:19.638Z (337 sec) - iOS Apple-Iphone5-1_PT9874 test took 216534ms - results peers[0], reConnects[0], sendData[3]

2015-12-03T15:30:39.840Z (357 sec) - Android LGE-Nexus 5_PT8412 got re-connected event

2015-12-03T15:31:24.185Z (401 sec) - Android LGE-Nexus 5_PT8412 got disconnected

2015-12-03T15:31:26.137Z (403 sec) - Android LGE-Nexus 5_PT8412 got re-connected event

2015-12-03T15:31:26.220Z (403 sec) - Android motorola-XT1039_PT5465 got re-connected event

2015-12-03T15:32:03.652Z (441 sec) - Android motorola-XT1072_PT5924 got disconnected

2015-12-03T15:32:04.843Z (442 sec) - Android LGE-Nexus 5_PT8412 got disconnected

2015-12-03T15:32:05.773Z (443 sec) - Android motorola-XT1039_PT5465 got disconnected

2015-12-03T15:32:07.227Z (444 sec) - Android motorola-XT1072_PT5924 got re-connected event

2015-12-03T15:32:20.213Z (457 sec) - Android HTC-HTC Desire 820_PT5486 got disconnected

2015-12-03T15:32:44.921Z (482 sec) - Android LGE-Nexus 5_PT8412 got re-connected event

2015-12-03T15:33:41.197Z (538 sec) - Android LGE-Nexus 5_PT8412 got disconnected

2015-12-03T15:35:02.182Z (619 sec) - Android samsung-SM-N910C_PT772 got disconnected

2015-12-03T15:36:59.179Z (736 sec) - Android LGE-Nexus 5_PT8412 got re-connected event

2015-12-03T15:37:08.560Z (746 sec) - iOS Apple-Iphone6-1_PT4561 got disconnected

2015-12-03T15:37:41.774Z (779 sec) - Android LGE-Nexus 5_PT8412 got re-connected event

2015-12-03T15:37:55.458Z (792 sec) - Android LGE-Nexus 5_PT8412 got disconnected

2015-12-03T15:38:29.816Z (827 sec) - Android LGE-Nexus 5_PT8412 got re-connected event

2015-12-03T15:38:49.205Z (846 sec) - Android LGE-Nexus 5_PT8412 got disconnected

2015-12-03T15:39:06.776Z (864 sec) - Android LGE-Nexus 5_PT8412 got disconnected

2015-12-03T15:39:45.603Z (903 sec) - Android LGE-Nexus 5_PT8412 got re-connected event

2015-12-03T15:39:54.818Z (912 sec) - Android LGE-Nexus 5_PT8412 got disconnected

2015-12-03T15:41:10.604Z (988 sec) - Android LGE-Nexus 5_PT8412 got disconnected

2015-12-03T15:41:56.806Z (1034 sec) - Android LGE-Nexus 5_PT8412 got re-connected event

2015-12-03T15:42:47.474Z (1084 sec) - Android LGE-Nexus 5_PT8412 got re-connected event

2015-12-03T15:42:57.668Z (1095 sec) - Android LGE-Nexus 5_PT8412 got re-connected event

2015-12-03T15:43:23.693Z (1121 sec) - Android samsung-SM-G900F_PT7127 test took 1000596ms - results peers[0], reConnects[0], sendData[16]

2015-12-03T15:43:23.791Z (1121 sec) - Android motorola-XT1039_PT5465 test took 1000695ms - results peers[0], reConnects[0], sendData[16]

2015-12-03T15:43:23.834Z (1121 sec) - Android LGE-Nexus 5_PT8949 test took 1000749ms - results peers[0], reConnects[0], sendData[16]

2015-12-03T15:43:23.880Z (1121 sec) - Android LGE-LG-H815_PT6298 test took 1000784ms - results peers[0], reConnects[0], sendData[16]

2015-12-03T15:43:23.891Z (1121 sec) - Android LGE-LG-D722_PT1540 test took 1000795ms - results peers[0], reConnects[0], sendData[16]

2015-12-03T15:43:23.932Z (1121 sec) - Android samsung-SM-A300FU_PT9205 test took 1000842ms - results peers[0], reConnects[0], sendData[16]

2015-12-03T15:43:24.602Z (1122 sec) - Android samsung-SM-A500FU_PT9149 test took 1001515ms - results peers[0], reConnects[0], sendData[16]

2015-12-03T15:43:26.172Z (1123 sec) - Android HUAWEI-ALE-L21_PT4138 test took 1003082ms - results peers[0], reConnects[0], sendData[16]

2015-12-03T15:43:27.103Z (1124 sec) - Android HTC-HTC Desire 820_PT336 test took 1004009ms - results peers[0], reConnects[0], sendData[16]

2015-12-03T15:43:27.997Z (1125 sec) - Android samsung-SM-G900F_PT8445 test took 1004904ms - results peers[0], reConnects[0], sendData[16]

2015-12-03T15:43:29.246Z (1126 sec) - Android LGE-LG-D802_PT2424 test took 1006158ms - results peers[0], reConnects[0], sendData[16]

2015-12-03T15:43:46.822Z (1144 sec) - Android LGE-Nexus 5_PT8412 got disconnected

2015-12-03T15:44:12.479Z (1169 sec) - Android LGE-Nexus 5_PT8412 got disconnected

2015-12-03T15:44:16.327Z (1173 sec) - Android motorola-XT1072_PT5924 got disconnected

2015-12-03T15:44:20.106Z (1177 sec) - Android motorola-XT1072_PT5924 got re-connected event

2015-12-03T15:44:20.110Z (1177 sec) - Android motorola-XT1072_PT5924 test took 1057014ms - results peers[0], reConnects[0], sendData[16]

2015-12-03T15:46:43.098Z (1320 sec) - Server timeout reached!

2015-12-03T15:46:43.099Z (1320 sec) - Send timeout to samsung-SM-G800F_PT5407
2015-12-03T15:46:43.100Z (1320 sec) - Send timeout to LGE-Nexus 5_PT8412

2015-12-03T15:46:43.102Z (1320 sec) - Send timeout to samsung-SM-A300FU_PT5175

2015-12-03T15:46:43.103Z (1320 sec) - Send timeout to HTC-HTC Desire 820_PT5486

2015-12-03T15:46:43.104Z (1320 sec) - Send timeout to samsung-SM-N910C_PT772

2015-12-03T15:46:43.111Z (1320 sec) - Server timeout reached!

2015-12-03T15:46:43.112Z (1320 sec) - Send timeout to Apple-Iphone5s-1_PT8182

2015-12-03T15:47:35.868Z (1373 sec) - iOS Apple-IpadAir2-1_PT2877 got disconnected

2015-12-03T15:47:35.877Z (1373 sec) - iOS Apple-Iphone5-1_PT9874 got disconnected

2015-12-03T15:47:43.107Z (1380 sec) - Did not get reports from all devices, but forcing tests to finish!

samsung-SM-G800F_PT5407 did not have results at the end of tests - check the device logs about why!!

LGE-Nexus 5_PT8412 did not have results at the end of tests - check the device logs about why!!

samsung-SM-A300FU_PT5175 did not have results at the end of tests - check the device logs about why!!

HTC-HTC Desire 820_PT5486 did not have results at the end of tests - check the device logs about why!!

samsung-SM-N910C_PT772 did not have results at the end of tests - check the device logs about why!!

2015-12-03T15:47:43.127Z (1380 sec) - Android All tests are done, preparing test report

--------------- test report ---------------------

--------------- LGE-Nexus 5_PT8949 --------------------- : 1

sendList : 100% : 120504 ms, 99% : 120504 ms, 95 : 120504 ms, 90% : 120504 ms.

Average data rate: 0.001 MB/s

Result count 1, range 120504 ms to  120504 ms.

sendList failed peers count : 12 [92.3076923076923 %]

- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1

- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1

- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1

- Peer ID : 80:01:84:8A:B3:68, Tried : 1
sendList never tried peers count : 3 [18.75 %]

- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 7C:F9:0E:37:96:AB

--------------- samsung-SM-A500FU_PT9149 --------------------- : 2

sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s

Results list does not contain any items
sendList failed peers count : 8 [100 %]
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
sendList never tried peers count : 8 [50 %]
- Peer ID : F8:95:C7:87:85:54
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 58:2A:F7:ED:96:BE
--------------- LGE-LG-D802_PT2424 --------------------- : 3
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 10 [100 %]
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
sendList never tried peers count : 6 [37.5 %]
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 58:2A:F7:ED:96:BE
--------------- HUAWEI-ALE-L21_PT4138 --------------------- : 4
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 9 [100 %]
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
sendList never tried peers count : 7 [43.75 %]
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : F4:F1:E1:5C:3B:E2
--------------- samsung-SM-A300FU_PT9205 --------------------- : 5
sendList : 100% : 6306 ms, 99% : 6306 ms, 95 : 6306 ms, 90% : 6306 ms.
Average data rate: 0.023 MB/s
Result count 2, range 2534 ms to  6306 ms.
sendList failed peers count : 9 [81.81818181818181 %]
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
sendList never tried peers count : 5 [31.25 %]
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 7C:F9:0E:34:8A:A0
--------------- samsung-SM-G900F_PT8445 --------------------- : 6
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 11 [100 %]
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
sendList never tried peers count : 5 [31.25 %]
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 58:2A:F7:ED:96:BE
--------------- HTC-HTC Desire 820_PT336 --------------------- : 7
sendList : 100% : 135248 ms, 99% : 135248 ms, 95 : 135248 ms, 90% : 135248 ms.
Average data rate: 0.001 MB/s
Result count 1, range 135248 ms to  135248 ms.
sendList failed peers count : 10 [90.9090909090909 %]
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
sendList never tried peers count : 5 [31.25 %]
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 58:2A:F7:ED:96:BE
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : F8:95:C7:87:85:54
- Peer ID : 7C:F9:0E:34:8A:A0
--------------- motorola-XT1039_PT5465 --------------------- : 8
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 11 [100 %]
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
sendList never tried peers count : 5 [31.25 %]
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : E0:DB:10:14:E2:C0

- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : 08:EC:A9:50:75:41
--------------- LGE-LG-D722_PT1540 --------------------- : 9
sendList : 100% : 35069 ms, 99% : 35069 ms, 95 : 35069 ms, 90% : 35069 ms.
Average data rate: 0.003 MB/s
Result count 1, range 35069 ms to  35069 ms.
sendList failed peers count : 10 [90.9090909090909 %]
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
sendList never tried peers count : 5 [31.25 %]
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 80:01:84:8A:B3:68
--------------- LGE-LG-H815_PT6298 --------------------- : 10
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 6 [100 %]
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
sendList never tried peers count : 10 [62.5 %]
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 44:80:EB:7B:5A:05

- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : F4:F1:E1:5C:3B:E2

- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 7C:F9:0E:37:96:AB
--------------- motorola-XT1072_PT5924 --------------------- : 11
sendList : 100% : 3493 ms, 99% : 3493 ms, 95 : 3493 ms, 90% : 3493 ms.

Average data rate: 0.029 MB/s
Result count 1, range 3493 ms to  3493 ms.
sendList failed peers count : 11 [91.66666666666667 %]
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1

- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
sendList never tried peers count : 4 [25 %]
- Peer ID : F8:95:C7:87:85:54
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 34:FC:EF:11:B1:66

--------------- samsung-SM-G900F_PT7127 --------------------- : 12
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 8 [100 %]
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
sendList never tried peers count : 8 [50 %]
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : F8:95:C7:87:85:54
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : F4:F1:E1:5C:3B:E2

--------------- Combined ---------------------
sendList : 100% : 135248 ms, 99% : 135248 ms, 95 : 135248 ms, 90% : 120504 ms.
Average data rate: 0.002 MB/s
--------------- end of test report ---------------------

2015-12-03T15:47:43.249Z (1380 sec) - Did not get reports from all devices, but forcing tests to finish!

Apple-Iphone5s-1_PT8182 did not have results at the end of tests - check the device logs about why!!

2015-12-03T15:47:43.251Z (1380 sec) - iOS All tests are done, preparing test report

--------------- test report ---------------------
--------------- Apple-IpadAir2-1_PT2877 --------------------- : 1
sendList : 100% : 6743 ms, 99% : 6743 ms, 95 : 6743 ms, 90% : 6743 ms.
Average data rate: 0.019 MB/s
Result count 2, range 3595 ms to  6743 ms.
sendList failed peers count : 1 [33.333333333333336 %]
- Peer ID : Apple-Iphone6-1_PT4561.tcwUUA==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5-1_PT9874 --------------------- : 2
sendList : 100% : 4092 ms, 99% : 4092 ms, 95 : 4092 ms, 90% : 4092 ms.
Average data rate: 0.024 MB/s
Result count 1, range 4092 ms to  4092 ms.

sendList failed peers count : 2 [66.66666666666667 %]
- Peer ID : Apple-IpadAir2-1_PT2877.NAxVhQ==, Tried : 5
- Peer ID : Apple-Iphone6-1_PT4561.tcwUUA==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone6-1_PT4561 --------------------- : 3
sendList : 100% : 4179 ms, 99% : 4179 ms, 95 : 4179 ms, 90% : 4179 ms.
Average data rate: 0.028 MB/s
Result count 2, range 2859 ms to  4179 ms.

sendList failed peers count : 1 [33.333333333333336 %]
- Peer ID : Apple-Iphone6-1_PT7057.4CFLyQ==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------
sendList : 100% : 6743 ms, 99% : 6743 ms, 95 : 6743 ms, 90% : 6743 ms.
Average data rate: 0.023 MB/s
--------------- end of test report ---------------------

2015-12-03T15:47:43.563Z (1381 sec) - Android samsung-SM-G900F_PT8445 got disconnected

2015-12-03T15:47:43.762Z (1381 sec) - Android LGE-LG-D722_PT1540 got disconnected

2015-12-03T15:47:43.771Z (1381 sec) - Android LGE-LG-H815_PT6298 got disconnected

2015-12-03T15:47:43.786Z (1381 sec) - Android samsung-SM-A500FU_PT9149 got disconnected

2015-12-03T15:47:43.824Z (1381 sec) - Android LGE-LG-D802_PT2424 got disconnected

2015-12-03T15:47:44.020Z (1381 sec) - Android motorola-XT1072_PT5924 got disconnected

2015-12-03T15:47:44.029Z (1381 sec) - Android samsung-SM-G900F_PT7127 got disconnected

2015-12-03T15:47:44.059Z (1381 sec) - Android HUAWEI-ALE-L21_PT4138 got disconnected

2015-12-03T15:47:44.389Z (1381 sec) - Android motorola-XT1039_PT5465 got disconnected

2015-12-03T15:47:49.275Z (1386 sec) - Android samsung-SM-A300FU_PT9205 got disconnected

2015-12-03T15:49:06.602Z (1464 sec) - Android LGE-Nexus 5_PT8949 got disconnected

2015-12-03T15:49:08.587Z (1466 sec) - Android HTC-HTC Desire 820_PT336 got disconnected


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```
###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/525393149f38b37_Relax_the_installation_folder_requirement__vjrantal/iOS_Iphone5-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/525393149f38b37_Relax_the_installation_folder_requirement__vjrantal/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/525393149f38b37_Relax_the_installation_folder_requirement__vjrantal/iOS_Iphone6-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/525393149f38b37_Relax_the_installation_folder_requirement__vjrantal/iOS_IpadAir2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/525393149f38b37_Relax_the_installation_folder_requirement__vjrantal/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
STOP log received from  f56ad48d Test has  SUCCEEDED
STOP log received from  W3D7N15428022572 Test has  SUCCEEDED
Device test finished on f56ad48d 
Device test finished on LGH8153b36be34 
Device test finished on W3D7N15428022572 
Android task is completed. [SUCCESS]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/525393149f38b37_Relax_the_installation_folder_requirement__vjrantal/thali01_LGE-LG-H815.md)

[HUAWEI-ALE-L21](https://github.com/ThaliTester/TestResults/blob/525393149f38b37_Relax_the_installation_folder_requirement__vjrantal/thali01_HUAWEI-ALE-L21.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/525393149f38b37_Relax_the_installation_folder_requirement__vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/525393149f38b37_Relax_the_installation_folder_requirement__vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/525393149f38b37_Relax_the_installation_folder_requirement__vjrantal/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/525393149f38b37_Relax_the_installation_folder_requirement__vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/525393149f38b37_Relax_the_installation_folder_requirement__vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/525393149f38b37_Relax_the_installation_folder_requirement__vjrantal/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/525393149f38b37_Relax_the_installation_folder_requirement__vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/525393149f38b37_Relax_the_installation_folder_requirement__vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/525393149f38b37_Relax_the_installation_folder_requirement__vjrantal/thali04_samsung-SM-G900F.md)

####Node name: thali06
Console output:
```
STOP log received from  022678fb504e29b0 Test has  SUCCEEDED
Device test finished on 022678fb504e29b0 
STOP log received from  7970f88c Test has  SUCCEEDED
Device test finished on 7970f88c 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:0 
child process exited with code 0 on device FA55PYS00566 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/525393149f38b37_Relax_the_installation_folder_requirement__vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/525393149f38b37_Relax_the_installation_folder_requirement__vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/525393149f38b37_Relax_the_installation_folder_requirement__vjrantal/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/525393149f38b37_Relax_the_installation_folder_requirement__vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/525393149f38b37_Relax_the_installation_folder_requirement__vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device HT574YC04723 app:com.test.thalitest code:0 
child process exited with code 0 on device HT574YC04723 
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:null 
child process exited with code null on device 4325e43f 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/525393149f38b37_Relax_the_installation_folder_requirement__vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/525393149f38b37_Relax_the_installation_folder_requirement__vjrantal/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
STOP log received from  CC51WYC03425 Test has  SUCCEEDED
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
Device test finished on 0c6a0f3c0bdb4e77 
Device test finished on CC51WYC03425 
Android task is completed. [SUCCESS]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/525393149f38b37_Relax_the_installation_folder_requirement__vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/525393149f38b37_Relax_the_installation_folder_requirement__vjrantal/thali09_LGE-Nexus 5.md)




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

2015-12-03T15:24:43.022Z (0 sec) - Android tests will start after waiting for 120 seconds

Test ID 0 configuration: testSendData.js, server timeout: 1200000, data:

{ timeout: 1000000,
  rounds: 1,
  dataTimeout: 10000,
  dataAmount: 100000,
  conReTryTimeout: 5000,
  conReTryCount: 5 }

2015-12-03T15:24:43.027Z (0 sec) - iOS tests will start after waiting for 120 seconds

listening on *:3000

2015-12-03T15:24:43.414Z (0 sec) - Android LGE-Nexus 5_PT8949 added (current device count 1)

2015-12-03T15:24:43.579Z (1 sec) - Android samsung-SM-A500FU_PT9149 added (current device count 2)

2015-12-03T15:24:43.695Z (1 sec) - Android LGE-LG-D802_PT2424 added (current device count 3)

2015-12-03T15:24:43.842Z (1 sec) - Android HUAWEI-ALE-L21_PT4138 added (current device count 4)

2015-12-03T15:24:44.351Z (1 sec) - Android samsung-SM-G800F_PT5407 added (current device count 5)

2015-12-03T15:24:45.508Z (3 sec) - iOS Apple-IpadAir2-1_PT2877 added (current device count 1)

2015-12-03T15:24:45.595Z (3 sec) - Android LGE-Nexus 5_PT8412 added (current device count 6)

2015-12-03T15:24:46.563Z (4 sec) - Android samsung-SM-A300FU_PT9205 added (current device count 7)

2015-12-03T15:24:46.868Z (4 sec) - Android samsung-SM-A300FU_PT5175 added (current device count 8)

2015-12-03T15:24:46.971Z (4 sec) - iOS Apple-Iphone5-1_PT9874 added (current device count 2)

2015-12-03T15:24:47.135Z (4 sec) - Android samsung-SM-G900F_PT8445 added (current device count 9)

2015-12-03T15:24:47.152Z (4 sec) - Android HTC-HTC Desire 820_PT5486 added (current device count 10)

2015-12-03T15:24:47.314Z (4 sec) - Android HTC-HTC Desire 820_PT336 added (current device count 11)

2015-12-03T15:24:47.915Z (5 sec) - Android motorola-XT1039_PT5465 added (current device count 12)

2015-12-03T15:24:47.947Z (5 sec) - Android LGE-LG-D722_PT1540 added (current device count 13)

2015-12-03T15:24:47.964Z (5 sec) - Android LGE-LG-H815_PT6298 added (current device count 14)

2015-12-03T15:24:48.185Z (5 sec) - iOS Apple-Iphone6-1_PT4561 added (current device count 3)

2015-12-03T15:24:48.404Z (5 sec) - Android motorola-XT1072_PT5924 added (current device count 15)

2015-12-03T15:24:48.648Z (6 sec) - iOS Apple-Iphone5s-1_PT8182 added (current device count 4)

2015-12-03T15:24:49.988Z (7 sec) - Android samsung-SM-N910C_PT772 added (current device count 16)

2015-12-03T15:24:50.046Z (7 sec) - Android samsung-SM-G900F_PT7127 added (current device count 17)

-------------- We got wait done, now starting the testing process ------------------

2015-12-03T15:26:43.080Z (120 sec) - Android start testing now with 17 devices

2015-12-03T15:26:43.102Z (120 sec) - iOS start testing now with 4 devices

2015-12-03T15:26:56.930Z (134 sec) - Android LGE-Nexus 5_PT8412 got disconnected

2015-12-03T15:26:58.231Z (135 sec) - Android LGE-Nexus 5_PT8412 got re-connected event

2015-12-03T15:27:48.667Z (186 sec) - iOS Apple-Iphone5s-1_PT8182 got disconnected

2015-12-03T15:28:40.033Z (237 sec) - Android samsung-SM-A300FU_PT5175 got disconnected

2015-12-03T15:28:42.250Z (239 sec) - iOS Apple-IpadAir2-1_PT2877 test took 119147ms - results peers[0], reConnects[0], sendData[3]

2015-12-03T15:28:44.037Z (241 sec) - Android LGE-Nexus 5_PT8412 got re-connected event

2015-12-03T15:29:05.984Z (263 sec) - Android samsung-SM-G800F_PT5407 got disconnected

2015-12-03T15:29:13.213Z (270 sec) - Android LGE-Nexus 5_PT8412 got disconnected

2015-12-03T15:30:16.545Z (334 sec) - iOS Apple-Iphone6-1_PT4561 test took 213441ms - results peers[0], reConnects[0], sendData[3]

2015-12-03T15:30:19.638Z (337 sec) - iOS Apple-Iphone5-1_PT9874 test took 216534ms - results peers[0], reConnects[0], sendData[3]

2015-12-03T15:30:39.840Z (357 sec) - Android LGE-Nexus 5_PT8412 got re-connected event

2015-12-03T15:31:24.185Z (401 sec) - Android LGE-Nexus 5_PT8412 got disconnected

2015-12-03T15:31:26.137Z (403 sec) - Android LGE-Nexus 5_PT8412 got re-connected event

2015-12-03T15:31:26.220Z (403 sec) - Android motorola-XT1039_PT5465 got re-connected event

2015-12-03T15:32:03.652Z (441 sec) - Android motorola-XT1072_PT5924 got disconnected

2015-12-03T15:32:04.843Z (442 sec) - Android LGE-Nexus 5_PT8412 got disconnected

2015-12-03T15:32:05.773Z (443 sec) - Android motorola-XT1039_PT5465 got disconnected

2015-12-03T15:32:07.227Z (444 sec) - Android motorola-XT1072_PT5924 got re-connected event

2015-12-03T15:32:20.213Z (457 sec) - Android HTC-HTC Desire 820_PT5486 got disconnected

2015-12-03T15:32:44.921Z (482 sec) - Android LGE-Nexus 5_PT8412 got re-connected event

2015-12-03T15:33:41.197Z (538 sec) - Android LGE-Nexus 5_PT8412 got disconnected

2015-12-03T15:35:02.182Z (619 sec) - Android samsung-SM-N910C_PT772 got disconnected

2015-12-03T15:36:59.179Z (736 sec) - Android LGE-Nexus 5_PT8412 got re-connected event

2015-12-03T15:37:08.560Z (746 sec) - iOS Apple-Iphone6-1_PT4561 got disconnected

2015-12-03T15:37:41.774Z (779 sec) - Android LGE-Nexus 5_PT8412 got re-connected event

2015-12-03T15:37:55.458Z (792 sec) - Android LGE-Nexus 5_PT8412 got disconnected

2015-12-03T15:38:29.816Z (827 sec) - Android LGE-Nexus 5_PT8412 got re-connected event

2015-12-03T15:38:49.205Z (846 sec) - Android LGE-Nexus 5_PT8412 got disconnected

2015-12-03T15:39:06.776Z (864 sec) - Android LGE-Nexus 5_PT8412 got disconnected

2015-12-03T15:39:45.603Z (903 sec) - Android LGE-Nexus 5_PT8412 got re-connected event

2015-12-03T15:39:54.818Z (912 sec) - Android LGE-Nexus 5_PT8412 got disconnected

2015-12-03T15:41:10.604Z (988 sec) - Android LGE-Nexus 5_PT8412 got disconnected

2015-12-03T15:41:56.806Z (1034 sec) - Android LGE-Nexus 5_PT8412 got re-connected event

2015-12-03T15:42:47.474Z (1084 sec) - Android LGE-Nexus 5_PT8412 got re-connected event

2015-12-03T15:42:57.668Z (1095 sec) - Android LGE-Nexus 5_PT8412 got re-connected event

2015-12-03T15:43:23.693Z (1121 sec) - Android samsung-SM-G900F_PT7127 test took 1000596ms - results peers[0], reConnects[0], sendData[16]

2015-12-03T15:43:23.791Z (1121 sec) - Android motorola-XT1039_PT5465 test took 1000695ms - results peers[0], reConnects[0], sendData[16]

2015-12-03T15:43:23.834Z (1121 sec) - Android LGE-Nexus 5_PT8949 test took 1000749ms - results peers[0], reConnects[0], sendData[16]

2015-12-03T15:43:23.880Z (1121 sec) - Android LGE-LG-H815_PT6298 test took 1000784ms - results peers[0], reConnects[0], sendData[16]

2015-12-03T15:43:23.891Z (1121 sec) - Android LGE-LG-D722_PT1540 test took 1000795ms - results peers[0], reConnects[0], sendData[16]

2015-12-03T15:43:23.932Z (1121 sec) - Android samsung-SM-A300FU_PT9205 test took 1000842ms - results peers[0], reConnects[0], sendData[16]

2015-12-03T15:43:24.602Z (1122 sec) - Android samsung-SM-A500FU_PT9149 test took 1001515ms - results peers[0], reConnects[0], sendData[16]

2015-12-03T15:43:26.172Z (1123 sec) - Android HUAWEI-ALE-L21_PT4138 test took 1003082ms - results peers[0], reConnects[0], sendData[16]

2015-12-03T15:43:27.103Z (1124 sec) - Android HTC-HTC Desire 820_PT336 test took 1004009ms - results peers[0], reConnects[0], sendData[16]

2015-12-03T15:43:27.997Z (1125 sec) - Android samsung-SM-G900F_PT8445 test took 1004904ms - results peers[0], reConnects[0], sendData[16]

2015-12-03T15:43:29.246Z (1126 sec) - Android LGE-LG-D802_PT2424 test took 1006158ms - results peers[0], reConnects[0], sendData[16]

2015-12-03T15:43:46.822Z (1144 sec) - Android LGE-Nexus 5_PT8412 got disconnected

2015-12-03T15:44:12.479Z (1169 sec) - Android LGE-Nexus 5_PT8412 got disconnected

2015-12-03T15:44:16.327Z (1173 sec) - Android motorola-XT1072_PT5924 got disconnected

2015-12-03T15:44:20.106Z (1177 sec) - Android motorola-XT1072_PT5924 got re-connected event

2015-12-03T15:44:20.110Z (1177 sec) - Android motorola-XT1072_PT5924 test took 1057014ms - results peers[0], reConnects[0], sendData[16]

2015-12-03T15:46:43.098Z (1320 sec) - Server timeout reached!

2015-12-03T15:46:43.099Z (1320 sec) - Send timeout to samsung-SM-G800F_PT5407
2015-12-03T15:46:43.100Z (1320 sec) - Send timeout to LGE-Nexus 5_PT8412

2015-12-03T15:46:43.102Z (1320 sec) - Send timeout to samsung-SM-A300FU_PT5175

2015-12-03T15:46:43.103Z (1320 sec) - Send timeout to HTC-HTC Desire 820_PT5486

2015-12-03T15:46:43.104Z (1320 sec) - Send timeout to samsung-SM-N910C_PT772

2015-12-03T15:46:43.111Z (1320 sec) - Server timeout reached!

2015-12-03T15:46:43.112Z (1320 sec) - Send timeout to Apple-Iphone5s-1_PT8182

2015-12-03T15:47:35.868Z (1373 sec) - iOS Apple-IpadAir2-1_PT2877 got disconnected

2015-12-03T15:47:35.877Z (1373 sec) - iOS Apple-Iphone5-1_PT9874 got disconnected

2015-12-03T15:47:43.107Z (1380 sec) - Did not get reports from all devices, but forcing tests to finish!

samsung-SM-G800F_PT5407 did not have results at the end of tests - check the device logs about why!!

LGE-Nexus 5_PT8412 did not have results at the end of tests - check the device logs about why!!

samsung-SM-A300FU_PT5175 did not have results at the end of tests - check the device logs about why!!

HTC-HTC Desire 820_PT5486 did not have results at the end of tests - check the device logs about why!!

samsung-SM-N910C_PT772 did not have results at the end of tests - check the device logs about why!!

2015-12-03T15:47:43.127Z (1380 sec) - Android All tests are done, preparing test report

--------------- test report ---------------------

--------------- LGE-Nexus 5_PT8949 --------------------- : 1

sendList : 100% : 120504 ms, 99% : 120504 ms, 95 : 120504 ms, 90% : 120504 ms.

Average data rate: 0.001 MB/s

Result count 1, range 120504 ms to  120504 ms.

sendList failed peers count : 12 [92.3076923076923 %]

- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1

- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1

- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1

- Peer ID : 80:01:84:8A:B3:68, Tried : 1
sendList never tried peers count : 3 [18.75 %]

- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 7C:F9:0E:37:96:AB

--------------- samsung-SM-A500FU_PT9149 --------------------- : 2

sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s

Results list does not contain any items
sendList failed peers count : 8 [100 %]
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
sendList never tried peers count : 8 [50 %]
- Peer ID : F8:95:C7:87:85:54
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 58:2A:F7:ED:96:BE
--------------- LGE-LG-D802_PT2424 --------------------- : 3
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 10 [100 %]
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
sendList never tried peers count : 6 [37.5 %]
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 58:2A:F7:ED:96:BE
--------------- HUAWEI-ALE-L21_PT4138 --------------------- : 4
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 9 [100 %]
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
sendList never tried peers count : 7 [43.75 %]
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : F4:F1:E1:5C:3B:E2
--------------- samsung-SM-A300FU_PT9205 --------------------- : 5
sendList : 100% : 6306 ms, 99% : 6306 ms, 95 : 6306 ms, 90% : 6306 ms.
Average data rate: 0.023 MB/s
Result count 2, range 2534 ms to  6306 ms.
sendList failed peers count : 9 [81.81818181818181 %]
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
sendList never tried peers count : 5 [31.25 %]
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 7C:F9:0E:34:8A:A0
--------------- samsung-SM-G900F_PT8445 --------------------- : 6
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 11 [100 %]
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
sendList never tried peers count : 5 [31.25 %]
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 58:2A:F7:ED:96:BE
--------------- HTC-HTC Desire 820_PT336 --------------------- : 7
sendList : 100% : 135248 ms, 99% : 135248 ms, 95 : 135248 ms, 90% : 135248 ms.
Average data rate: 0.001 MB/s
Result count 1, range 135248 ms to  135248 ms.
sendList failed peers count : 10 [90.9090909090909 %]
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
sendList never tried peers count : 5 [31.25 %]
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 58:2A:F7:ED:96:BE
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : F8:95:C7:87:85:54
- Peer ID : 7C:F9:0E:34:8A:A0
--------------- motorola-XT1039_PT5465 --------------------- : 8
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 11 [100 %]
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
sendList never tried peers count : 5 [31.25 %]
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : E0:DB:10:14:E2:C0

- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : 08:EC:A9:50:75:41
--------------- LGE-LG-D722_PT1540 --------------------- : 9
sendList : 100% : 35069 ms, 99% : 35069 ms, 95 : 35069 ms, 90% : 35069 ms.
Average data rate: 0.003 MB/s
Result count 1, range 35069 ms to  35069 ms.
sendList failed peers count : 10 [90.9090909090909 %]
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
sendList never tried peers count : 5 [31.25 %]
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 80:01:84:8A:B3:68
--------------- LGE-LG-H815_PT6298 --------------------- : 10
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 6 [100 %]
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
sendList never tried peers count : 10 [62.5 %]
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 44:80:EB:7B:5A:05

- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : F4:F1:E1:5C:3B:E2

- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 7C:F9:0E:37:96:AB
--------------- motorola-XT1072_PT5924 --------------------- : 11
sendList : 100% : 3493 ms, 99% : 3493 ms, 95 : 3493 ms, 90% : 3493 ms.

Average data rate: 0.029 MB/s
Result count 1, range 3493 ms to  3493 ms.
sendList failed peers count : 11 [91.66666666666667 %]
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1

- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
sendList never tried peers count : 4 [25 %]
- Peer ID : F8:95:C7:87:85:54
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 34:FC:EF:11:B1:66

--------------- samsung-SM-G900F_PT7127 --------------------- : 12
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 8 [100 %]
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
sendList never tried peers count : 8 [50 %]
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : F8:95:C7:87:85:54
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : F4:F1:E1:5C:3B:E2

--------------- Combined ---------------------
sendList : 100% : 135248 ms, 99% : 135248 ms, 95 : 135248 ms, 90% : 120504 ms.
Average data rate: 0.002 MB/s
--------------- end of test report ---------------------

2015-12-03T15:47:43.249Z (1380 sec) - Did not get reports from all devices, but forcing tests to finish!

Apple-Iphone5s-1_PT8182 did not have results at the end of tests - check the device logs about why!!

2015-12-03T15:47:43.251Z (1380 sec) - iOS All tests are done, preparing test report

--------------- test report ---------------------
--------------- Apple-IpadAir2-1_PT2877 --------------------- : 1
sendList : 100% : 6743 ms, 99% : 6743 ms, 95 : 6743 ms, 90% : 6743 ms.
Average data rate: 0.019 MB/s
Result count 2, range 3595 ms to  6743 ms.
sendList failed peers count : 1 [33.333333333333336 %]
- Peer ID : Apple-Iphone6-1_PT4561.tcwUUA==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5-1_PT9874 --------------------- : 2
sendList : 100% : 4092 ms, 99% : 4092 ms, 95 : 4092 ms, 90% : 4092 ms.
Average data rate: 0.024 MB/s
Result count 1, range 4092 ms to  4092 ms.

sendList failed peers count : 2 [66.66666666666667 %]
- Peer ID : Apple-IpadAir2-1_PT2877.NAxVhQ==, Tried : 5
- Peer ID : Apple-Iphone6-1_PT4561.tcwUUA==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone6-1_PT4561 --------------------- : 3
sendList : 100% : 4179 ms, 99% : 4179 ms, 95 : 4179 ms, 90% : 4179 ms.
Average data rate: 0.028 MB/s
Result count 2, range 2859 ms to  4179 ms.

sendList failed peers count : 1 [33.333333333333336 %]
- Peer ID : Apple-Iphone6-1_PT7057.4CFLyQ==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------
sendList : 100% : 6743 ms, 99% : 6743 ms, 95 : 6743 ms, 90% : 6743 ms.
Average data rate: 0.023 MB/s
--------------- end of test report ---------------------

2015-12-03T15:47:43.563Z (1381 sec) - Android samsung-SM-G900F_PT8445 got disconnected

2015-12-03T15:47:43.762Z (1381 sec) - Android LGE-LG-D722_PT1540 got disconnected

2015-12-03T15:47:43.771Z (1381 sec) - Android LGE-LG-H815_PT6298 got disconnected

2015-12-03T15:47:43.786Z (1381 sec) - Android samsung-SM-A500FU_PT9149 got disconnected

2015-12-03T15:47:43.824Z (1381 sec) - Android LGE-LG-D802_PT2424 got disconnected

2015-12-03T15:47:44.020Z (1381 sec) - Android motorola-XT1072_PT5924 got disconnected

2015-12-03T15:47:44.029Z (1381 sec) - Android samsung-SM-G900F_PT7127 got disconnected

2015-12-03T15:47:44.059Z (1381 sec) - Android HUAWEI-ALE-L21_PT4138 got disconnected

2015-12-03T15:47:44.389Z (1381 sec) - Android motorola-XT1039_PT5465 got disconnected

2015-12-03T15:47:49.275Z (1386 sec) - Android samsung-SM-A300FU_PT9205 got disconnected

2015-12-03T15:49:06.602Z (1464 sec) - Android LGE-Nexus 5_PT8949 got disconnected

2015-12-03T15:49:08.587Z (1466 sec) - Android HTC-HTC Desire 820_PT336 got disconnected


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


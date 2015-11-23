#### Test 51335028e04ad51 Logs

Status: 
```

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code 254 on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
ios: child process exited with code 254 on device 2a65f58f9902a701b5c9a55b2befb18672927474 
true


server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":24}}
Test ID 0 configuration: testSendData.js, server timeout: 1200000, data:

{ timeout: '1000000',
  rounds: '1',
  dataTimeout: '10000',
  dataAmount: '100000',
  conReTryTimeout: '5000',
  conReTryCount: '5' }

2015-11-23T07:02:38.856Z (0 sec) - Android tests will start after waiting for 120 seconds

Test ID 0 configuration: testSendData.js, server timeout: 1200000, data:

{ timeout: '1000000',
  rounds: '1',
  dataTimeout: '10000',
  dataAmount: '100000',
  conReTryTimeout: '5000',
  conReTryCount: '5' }

2015-11-23T07:02:38.862Z (0 sec) - iOS tests will start after waiting for 120 seconds

listening on *:3000

2015-11-23T07:02:39.524Z (1 sec) - Android HUAWEI-ALE-L21_PT4320 added (current device count 1)

2015-11-23T07:02:39.548Z (1 sec) - Android LGE-LG-D855_PT9692 added (current device count 2)

2015-11-23T07:02:39.551Z (1 sec) - Android LGE-LG-D802_PT4132 added (current device count 3)

2015-11-23T07:02:39.591Z (1 sec) - Android HTC-HTC One_M8_PT144 added (current device count 4)

2015-11-23T07:02:39.594Z (1 sec) - Android motorola-XT1039_PT7324 added (current device count 5)

2015-11-23T07:02:39.645Z (1 sec) - Android LGE-Nexus 5_PT1183 added (current device count 6)

2015-11-23T07:02:39.681Z (1 sec) - Android samsung-SM-G900F_PT9133 added (current device count 7)

2015-11-23T07:02:39.790Z (1 sec) - Android LGE-Nexus 5_PT8310 added (current device count 8)

2015-11-23T07:02:39.992Z (1 sec) - Android samsung-SM-N910C_PT166 added (current device count 9)

2015-11-23T07:02:40.201Z (1 sec) - Android HTC-HTC Desire 820_PT2883 added (current device count 10)

2015-11-23T07:02:40.283Z (1 sec) - Android samsung-SM-A500FU_PT3692 added (current device count 11)

2015-11-23T07:02:40.549Z (2 sec) - Android HTC-HTC One M8s_PT5815 added (current device count 12)

2015-11-23T07:02:40.604Z (2 sec) - iOS Apple-Iphone5s-1_PT1828 added (current device count 1)

2015-11-23T07:02:40.717Z (2 sec) - Android HTC-HTC Desire 820_PT6261 added (current device count 13)

2015-11-23T07:02:41.107Z (2 sec) - Android LGE-LG-H815_PT8761 added (current device count 14)

2015-11-23T07:02:41.273Z (2 sec) - Android samsung-SM-A500FU_PT2202 added (current device count 15)

2015-11-23T07:02:41.285Z (2 sec) - iOS Apple-IpadAir2-1_PT2253 added (current device count 2)

2015-11-23T07:02:41.479Z (3 sec) - Android samsung-SM-G800F_PT592 added (current device count 16)

2015-11-23T07:02:41.661Z (3 sec) - Android samsung-SM-A300FU_PT8624 added (current device count 17)

2015-11-23T07:02:41.710Z (3 sec) - Android samsung-SM-N9005_PT8165 added (current device count 18)

2015-11-23T07:02:41.844Z (3 sec) - Android samsung-SM-A300FU_PT3299 added (current device count 19)

2015-11-23T07:02:42.623Z (4 sec) - iOS Apple-Iphone6-1_PT606 added (current device count 3)

2015-11-23T07:02:42.660Z (4 sec) - iOS Apple-Iphone5-1_PT8536 added (current device count 4)

2015-11-23T07:02:43.059Z (4 sec) - Android motorola-Nexus 6_PT6430 added (current device count 20)

2015-11-23T07:02:43.184Z (4 sec) - Android LGE-LG-D722_PT7432 added (current device count 21)

2015-11-23T07:02:43.500Z (5 sec) - Android motorola-XT1072_PT5723 added (current device count 22)

2015-11-23T07:02:44.937Z (6 sec) - Android samsung-SM-G900F_PT2658 added (current device count 23)

-------------- We got wait done, now starting the testing process ------------------

2015-11-23T07:04:38.910Z (120 sec) - Android start testing now with 23 devices

2015-11-23T07:04:38.943Z (120 sec) - iOS start testing now with 4 devices

2015-11-23T07:04:51.771Z (133 sec) - iOS Apple-IpadAir2-1_PT2253 test took 12826ms - results peers[0], reConnects[0], sendData[3]

2015-11-23T07:05:30.711Z (172 sec) - Android LGE-Nexus 5_PT1183 got re-connected event

2015-11-23T07:05:45.159Z (186 sec) - Android samsung-SM-N910C_PT166 got disconnected

2015-11-23T07:06:01.289Z (202 sec) - iOS Apple-Iphone6-1_PT606 test took 82344ms - results peers[0], reConnects[0], sendData[3]

2015-11-23T07:06:09.804Z (211 sec) - Android LGE-LG-D802_PT4132 got disconnected

2015-11-23T07:06:09.915Z (211 sec) - Android samsung-SM-G900F_PT9133 got disconnected

2015-11-23T07:06:09.984Z (211 sec) - Android LGE-Nexus 5_PT1183 got disconnected

2015-11-23T07:06:10.891Z (212 sec) - iOS Apple-Iphone5s-1_PT1828 got disconnected

2015-11-23T07:06:11.634Z (213 sec) - Android samsung-SM-G800F_PT592 got disconnected

2015-11-23T07:06:13.290Z (214 sec) - Android LGE-LG-D722_PT7432 got disconnected

2015-11-23T07:06:36.375Z (238 sec) - Android LGE-LG-H815_PT8761 got disconnected

2015-11-23T07:06:55.711Z (257 sec) - Android LGE-Nexus 5_PT1183 got disconnected

2015-11-23T07:07:02.746Z (264 sec) - Android samsung-SM-A300FU_PT8624 got disconnected

2015-11-23T07:07:07.765Z (269 sec) - Android HTC-HTC Desire 820_PT2883 got disconnected

2015-11-23T07:08:18.447Z (340 sec) - Android HTC-HTC One M8s_PT5815 got disconnected

2015-11-23T07:08:21.020Z (342 sec) - Android HTC-HTC Desire 820_PT6261 got disconnected

2015-11-23T07:08:25.665Z (347 sec) - Android samsung-SM-A300FU_PT3299 got disconnected

2015-11-23T07:08:38.100Z (359 sec) - iOS Apple-Iphone5-1_PT8536 test took 239153ms - results peers[0], reConnects[0], sendData[3]

2015-11-23T07:09:58.051Z (439 sec) - Android motorola-XT1039_PT7324 got disconnected

2015-11-23T07:10:05.115Z (446 sec) - iOS Apple-Iphone6-1_PT606 got disconnected

2015-11-23T07:10:27.998Z (469 sec) - iOS Apple-IpadAir2-1_PT2253 got re-connected event

2015-11-23T07:10:37.458Z (479 sec) - iOS Apple-IpadAir2-1_PT2253 got disconnected

2015-11-23T07:10:38.812Z (480 sec) - Android motorola-XT1039_PT7324 got re-connected event

2015-11-23T07:11:13.039Z (514 sec) - Android LGE-LG-D855_PT9692 got disconnected

2015-11-23T07:11:43.735Z (545 sec) - Android samsung-SM-A500FU_PT2202 got disconnected

2015-11-23T07:12:03.762Z (565 sec) - iOS Apple-Iphone6-1_PT606 got re-connected event

2015-11-23T07:12:21.172Z (582 sec) - iOS Apple-Iphone5-1_PT8536 got disconnected

2015-11-23T07:12:25.445Z (587 sec) - Android motorola-XT1072_PT5723 got disconnected

2015-11-23T07:12:43.113Z (604 sec) - iOS Apple-Iphone5-1_PT8536 got re-connected event

2015-11-23T07:13:28.391Z (650 sec) - iOS Apple-Iphone6-1_PT606 got disconnected

2015-11-23T07:13:30.072Z (651 sec) - iOS Apple-Iphone6-1_PT606 got re-connected event

2015-11-23T07:13:47.032Z (668 sec) - Android motorola-XT1039_PT7324 got disconnected

2015-11-23T07:13:58.434Z (680 sec) - iOS Apple-IpadAir2-1_PT2253 got disconnected

2015-11-23T07:14:36.881Z (718 sec) - iOS Apple-Iphone5-1_PT8536 got re-connected event

2015-11-23T07:14:37.466Z (719 sec) - iOS Apple-Iphone5-1_PT8536 got disconnected

2015-11-23T07:15:31.729Z (773 sec) - iOS Apple-IpadAir2-1_PT2253 got re-connected event

2015-11-23T07:15:45.115Z (786 sec) - iOS Apple-Iphone6-1_PT606 got disconnected

2015-11-23T07:16:02.304Z (803 sec) - iOS Apple-Iphone5-1_PT8536 got disconnected

2015-11-23T07:16:03.090Z (804 sec) - iOS Apple-Iphone5-1_PT8536 got re-connected event

2015-11-23T07:17:10.230Z (871 sec) - Android motorola-XT1039_PT7324 got re-connected event

2015-11-23T07:19:43.552Z (1025 sec) - iOS Apple-Iphone5-1_PT8536 got re-connected event

2015-11-23T07:19:50.690Z (1032 sec) - Android motorola-XT1039_PT7324 got disconnected

2015-11-23T07:20:01.760Z (1043 sec) - iOS Apple-Iphone5-1_PT8536 got disconnected

2015-11-23T07:20:17.410Z (1059 sec) - Android motorola-XT1072_PT5723 got re-connected event

2015-11-23T07:21:04.625Z (1106 sec) - Android LGE-LG-D802_PT4132 got re-connected event

2015-11-23T07:21:19.279Z (1120 sec) - Android samsung-SM-N9005_PT8165 test took 1000344ms - results peers[0], reConnects[0], sendData[22]

2015-11-23T07:21:19.346Z (1121 sec) - Android samsung-SM-A500FU_PT3692 test took 1000416ms - results peers[0], reConnects[0], sendData[22]

2015-11-23T07:21:19.436Z (1121 sec) - Android HTC-HTC One_M8_PT144 test took 1000512ms - results peers[0], reConnects[0], sendData[22]

2015-11-23T07:21:19.598Z (1121 sec) - Android HUAWEI-ALE-L21_PT4320 test took 1000679ms - results peers[0], reConnects[0], sendData[22]

2015-11-23T07:21:19.867Z (1121 sec) - Android LGE-Nexus 5_PT8310 test took 1000939ms - results peers[0], reConnects[0], sendData[22]

2015-11-23T07:21:20.305Z (1121 sec) - Android motorola-XT1072_PT5723 test took 1001368ms - results peers[0], reConnects[0], sendData[22]

2015-11-23T07:21:20.838Z (1122 sec) - Android samsung-SM-G900F_PT2658 test took 1001900ms - results peers[0], reConnects[0], sendData[22]

2015-11-23T07:21:22.468Z (1124 sec) - Android motorola-XT1039_PT7324 got re-connected event

2015-11-23T07:21:22.485Z (1124 sec) - Android motorola-XT1039_PT7324 test took 1003561ms - results peers[0], reConnects[0], sendData[22]

2015-11-23T07:21:25.403Z (1127 sec) - Android LGE-LG-D802_PT4132 test took 1006480ms - results peers[0], reConnects[0], sendData[22]

2015-11-23T07:21:29.842Z (1131 sec) - Android motorola-Nexus 6_PT6430 got re-connected event

2015-11-23T07:21:29.875Z (1131 sec) - Android motorola-Nexus 6_PT6430 test took 1010939ms - results peers[0], reConnects[0], sendData[22]

2015-11-23T07:22:30.800Z (1192 sec) - Android motorola-Nexus 6_PT6430 got disconnected

2015-11-23T07:24:38.942Z (1320 sec) - Server timeout reached!

2015-11-23T07:24:38.944Z (1320 sec) - Send timeout to LGE-LG-D855_PT9692

2015-11-23T07:24:38.945Z (1320 sec) - Send timeout to LGE-Nexus 5_PT1183

2015-11-23T07:24:38.946Z (1320 sec) - Send timeout to samsung-SM-G900F_PT9133
2015-11-23T07:24:38.947Z (1320 sec) - Send timeout to samsung-SM-N910C_PT166

2015-11-23T07:24:38.947Z (1320 sec) - Send timeout to HTC-HTC Desire 820_PT2883
2015-11-23T07:24:38.948Z (1320 sec) - Send timeout to HTC-HTC One M8s_PT5815

2015-11-23T07:24:38.949Z (1320 sec) - Send timeout to HTC-HTC Desire 820_PT6261
2015-11-23T07:24:38.949Z (1320 sec) - Send timeout to LGE-LG-H815_PT8761
2015-11-23T07:24:38.950Z (1320 sec) - Send timeout to samsung-SM-A500FU_PT2202

2015-11-23T07:24:38.950Z (1320 sec) - Send timeout to samsung-SM-G800F_PT592
2015-11-23T07:24:38.951Z (1320 sec) - Send timeout to samsung-SM-A300FU_PT8624

2015-11-23T07:24:38.952Z (1320 sec) - Send timeout to samsung-SM-A300FU_PT3299
2015-11-23T07:24:38.952Z (1320 sec) - Send timeout to LGE-LG-D722_PT7432

2015-11-23T07:24:38.959Z (1320 sec) - Server timeout reached!

2015-11-23T07:24:38.960Z (1320 sec) - Send timeout to Apple-Iphone5s-1_PT1828

2015-11-23T07:25:38.954Z (1380 sec) - Did not get reports from all devices, but forcing tests to finish!

LGE-LG-D855_PT9692 did not have results at the end of tests - check the device logs about why!!

LGE-Nexus 5_PT1183 did not have results at the end of tests - check the device logs about why!!

samsung-SM-G900F_PT9133 did not have results at the end of tests - check the device logs about why!!

samsung-SM-N910C_PT166 did not have results at the end of tests - check the device logs about why!!
HTC-HTC Desire 820_PT2883 did not have results at the end of tests - check the device logs about why!!
HTC-HTC One M8s_PT5815 did not have results at the end of tests - check the device logs about why!!
HTC-HTC Desire 820_PT6261 did not have results at the end of tests - check the device logs about why!!
LGE-LG-H815_PT8761 did not have results at the end of tests - check the device logs about why!!
samsung-SM-A500FU_PT2202 did not have results at the end of tests - check the device logs about why!!

samsung-SM-G800F_PT592 did not have results at the end of tests - check the device logs about why!!
samsung-SM-A300FU_PT8624 did not have results at the end of tests - check the device logs about why!!
samsung-SM-A300FU_PT3299 did not have results at the end of tests - check the device logs about why!!
LGE-LG-D722_PT7432 did not have results at the end of tests - check the device logs about why!!

2015-11-23T07:25:38.980Z (1380 sec) - Android All tests are done, preparing test report

--------------- test report ---------------------

--------------- HUAWEI-ALE-L21_PT4320 --------------------- : 1

sendList : 100% : 137053 ms, 99% : 137053 ms, 95 : 137053 ms, 90% : 87105 ms.

Result count 10, range 4616 ms to  137053 ms.

sendList failed peers count : 5 [33.333333333333336 %]
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 7C:F9:0E:51:18:22, Tried : 1
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
sendList never tried peers count : 7 [31.818181818181817 %]
- Peer ID : 50:2E:6C:AC:21:50
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : E0:DB:10:14:E2:C0

--------------- LGE-LG-D802_PT4132 --------------------- : 2
sendList : 100% : 65201 ms, 99% : 65201 ms, 95 : 65201 ms, 90% : 65201 ms.
Result count 3, range 6306 ms to  65201 ms.
sendList failed peers count : 4 [57.142857142857146 %]
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
sendList never tried peers count : 15 [68.18181818181819 %]
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 58:2A:F7:ED:96:BE
- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : E0:DB:10:1F:C9:5E
- Peer ID : F8:95:C7:87:85:54
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 90:E7:C4:F6:69:77
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 50:2E:6C:AC:21:50
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : 08:EC:A9:50:75:41
--------------- HTC-HTC One_M8_PT144 --------------------- : 3
sendList : 100% : 36799 ms, 99% : 36799 ms, 95 : 36799 ms, 90% : 34496 ms.
Result count 9, range 4183 ms to  36799 ms.
sendList failed peers count : 7 [43.75 %]
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
sendList never tried peers count : 6 [27.272727272727273 %]
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : F8:95:C7:87:85:54
- Peer ID : 08:EC:A9:50:75:41
--------------- motorola-XT1039_PT7324 --------------------- : 4
sendList : 100% : 77985 ms, 99% : 77985 ms, 95 : 63934 ms, 90% : 63059 ms.
Result count 17, range 5326 ms to  77985 ms.
sendList failed peers count : 5 [22.727272727272727 %]
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 2
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
sendList never tried peers count : 0 [0 %]
--------------- LGE-Nexus 5_PT8310 --------------------- : 5

sendList : 100% : 117839 ms, 99% : 117839 ms, 95 : 114496 ms, 90% : 114496 ms.
Result count 13, range 3445 ms to  117839 ms.
sendList failed peers count : 4 [23.529411764705884 %]

- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
sendList never tried peers count : 5 [22.727272727272727 %]
- Peer ID : 90:E7:C4:F6:69:77
- Peer ID : 58:2A:F7:ED:96:BE

- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 34:FC:EF:9D:93:0B
--------------- samsung-SM-A500FU_PT3692 --------------------- : 6
sendList : 100% : 175320 ms, 99% : 175320 ms, 95 : 44528 ms, 90% : 44149 ms.
Result count 16, range 5425 ms to  175320 ms.
sendList failed peers count : 6 [27.272727272727273 %]

- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-N9005_PT8165 --------------------- : 7
sendList : 100% : 107761 ms, 99% : 107761 ms, 95 : 69392 ms, 90% : 69392 ms.
Result count 15, range 2579 ms to  107761 ms.
sendList failed peers count : 5 [25 %]
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
sendList never tried peers count : 2 [9.090909090909092 %]
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 7C:F9:0E:51:18:22

--------------- motorola-Nexus 6_PT6430 --------------------- : 8
sendList : 100% : 165576 ms, 99% : 165576 ms, 95 : 165576 ms, 90% : 133912 ms.
Result count 10, range 11760 ms to  165576 ms.
sendList failed peers count : 6 [37.5 %]
- Peer ID : 7C:F9:0E:51:18:22, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1

- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
sendList never tried peers count : 6 [27.272727272727273 %]
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : B0:C5:59:3F:75:69

- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 44:80:EB:7B:5A:05
--------------- motorola-XT1072_PT5723 --------------------- : 9
sendList : 100% : 119103 ms, 99% : 119103 ms, 95 : 96417 ms, 90% : 96417 ms.
Result count 12, range 2496 ms to  119103 ms.
sendList failed peers count : 7 [36.8421052631579 %]

- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1

- Peer ID : 90:E7:C4:F6:69:77, Tried : 1
sendList never tried peers count : 3 [13.636363636363637 %]
- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 08:EC:A9:50:76:27

--------------- samsung-SM-G900F_PT2658 --------------------- : 10
sendList : 100% : 71528 ms, 99% : 71528 ms, 95 : 45321 ms, 90% : 27660 ms.
Result count 18, range 2924 ms to  71528 ms.
sendList failed peers count : 4 [18.181818181818183 %]
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 2
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1

- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 2
sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------

sendList : 100% : 175320 ms, 99% : 165576 ms, 95 : 114496 ms, 90% : 80144 ms.

--------------- end of test report ---------------------

2015-11-23T07:25:39.125Z (1380 sec) - Did not get reports from all devices, but forcing tests to finish!

Apple-Iphone5s-1_PT1828 did not have results at the end of tests - check the device logs about why!!
2015-11-23T07:25:39.128Z (1380 sec) - iOS All tests are done, preparing test report
--------------- test report ---------------------
--------------- Apple-IpadAir2-1_PT2253 --------------------- : 1
sendList : 100% : 4949 ms, 99% : 4949 ms, 95 : 4949 ms, 90% : 4949 ms.
Result count 3, range 2967 ms to  4949 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1_PT606 --------------------- : 2
sendList : 100% : 3327 ms, 99% : 3327 ms, 95 : 3327 ms, 90% : 3327 ms.
Result count 2, range 3054 ms to  3327 ms.
sendList failed peers count : 1 [33.333333333333336 %]
- Peer ID : Apple-Iphone5s-1_PT8264./5qd6Q==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5-1_PT8536 --------------------- : 3
sendList : 100% : 3663 ms, 99% : 3663 ms, 95 : 3663 ms, 90% : 3663 ms.
Result count 2, range 3538 ms to  3663 ms.
sendList failed peers count : 1 [33.333333333333336 %]
- Peer ID : Apple-Iphone5s-1_PT8264./5qd6Q==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------
sendList : 100% : 4949 ms, 99% : 4949 ms, 95 : 4949 ms, 90% : 3663 ms.

--------------- end of test report ---------------------


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!
```
###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/51335028e04ad51_Work_in_progress__vjrantal/iOS_Iphone5-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/51335028e04ad51_Work_in_progress__vjrantal/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/51335028e04ad51_Work_in_progress__vjrantal/iOS_Iphone6-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/51335028e04ad51_Work_in_progress__vjrantal/iOS_IpadAir2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/51335028e04ad51_Work_in_progress__vjrantal/iOS_server.md)


###Android Logs
####Node name: thali01
####Node name: thali02
####Node name: thali03
Console output:
```
Error! Unexpected exit on device LGD8553bed2d08 app:com.test.thalitest code:null 
child process exited with code null on device LGD8553bed2d08 
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:null 
child process exited with code null on device 320414cd475f91e3 
Android task is completed 
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/51335028e04ad51_Work_in_progress__vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/51335028e04ad51_Work_in_progress__vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/51335028e04ad51_Work_in_progress__vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed 
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/51335028e04ad51_Work_in_progress__vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/51335028e04ad51_Work_in_progress__vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/51335028e04ad51_Work_in_progress__vjrantal/thali04_samsung-SM-G900F.md)

####Node name: thali05
####Node name: thali06
####Node name: thali07
####Node name: thali08
####Node name: thali09



#### Integration Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":24}}
Test ID 0 configuration: testSendData.js, server timeout: 1200000, data:

{ timeout: '1000000',
  rounds: '1',
  dataTimeout: '10000',
  dataAmount: '100000',
  conReTryTimeout: '5000',
  conReTryCount: '5' }

2015-11-23T07:02:38.856Z (0 sec) - Android tests will start after waiting for 120 seconds

Test ID 0 configuration: testSendData.js, server timeout: 1200000, data:

{ timeout: '1000000',
  rounds: '1',
  dataTimeout: '10000',
  dataAmount: '100000',
  conReTryTimeout: '5000',
  conReTryCount: '5' }

2015-11-23T07:02:38.862Z (0 sec) - iOS tests will start after waiting for 120 seconds

listening on *:3000

2015-11-23T07:02:39.524Z (1 sec) - Android HUAWEI-ALE-L21_PT4320 added (current device count 1)

2015-11-23T07:02:39.548Z (1 sec) - Android LGE-LG-D855_PT9692 added (current device count 2)

2015-11-23T07:02:39.551Z (1 sec) - Android LGE-LG-D802_PT4132 added (current device count 3)

2015-11-23T07:02:39.591Z (1 sec) - Android HTC-HTC One_M8_PT144 added (current device count 4)

2015-11-23T07:02:39.594Z (1 sec) - Android motorola-XT1039_PT7324 added (current device count 5)

2015-11-23T07:02:39.645Z (1 sec) - Android LGE-Nexus 5_PT1183 added (current device count 6)

2015-11-23T07:02:39.681Z (1 sec) - Android samsung-SM-G900F_PT9133 added (current device count 7)

2015-11-23T07:02:39.790Z (1 sec) - Android LGE-Nexus 5_PT8310 added (current device count 8)

2015-11-23T07:02:39.992Z (1 sec) - Android samsung-SM-N910C_PT166 added (current device count 9)

2015-11-23T07:02:40.201Z (1 sec) - Android HTC-HTC Desire 820_PT2883 added (current device count 10)

2015-11-23T07:02:40.283Z (1 sec) - Android samsung-SM-A500FU_PT3692 added (current device count 11)

2015-11-23T07:02:40.549Z (2 sec) - Android HTC-HTC One M8s_PT5815 added (current device count 12)

2015-11-23T07:02:40.604Z (2 sec) - iOS Apple-Iphone5s-1_PT1828 added (current device count 1)

2015-11-23T07:02:40.717Z (2 sec) - Android HTC-HTC Desire 820_PT6261 added (current device count 13)

2015-11-23T07:02:41.107Z (2 sec) - Android LGE-LG-H815_PT8761 added (current device count 14)

2015-11-23T07:02:41.273Z (2 sec) - Android samsung-SM-A500FU_PT2202 added (current device count 15)

2015-11-23T07:02:41.285Z (2 sec) - iOS Apple-IpadAir2-1_PT2253 added (current device count 2)

2015-11-23T07:02:41.479Z (3 sec) - Android samsung-SM-G800F_PT592 added (current device count 16)

2015-11-23T07:02:41.661Z (3 sec) - Android samsung-SM-A300FU_PT8624 added (current device count 17)

2015-11-23T07:02:41.710Z (3 sec) - Android samsung-SM-N9005_PT8165 added (current device count 18)

2015-11-23T07:02:41.844Z (3 sec) - Android samsung-SM-A300FU_PT3299 added (current device count 19)

2015-11-23T07:02:42.623Z (4 sec) - iOS Apple-Iphone6-1_PT606 added (current device count 3)

2015-11-23T07:02:42.660Z (4 sec) - iOS Apple-Iphone5-1_PT8536 added (current device count 4)

2015-11-23T07:02:43.059Z (4 sec) - Android motorola-Nexus 6_PT6430 added (current device count 20)

2015-11-23T07:02:43.184Z (4 sec) - Android LGE-LG-D722_PT7432 added (current device count 21)

2015-11-23T07:02:43.500Z (5 sec) - Android motorola-XT1072_PT5723 added (current device count 22)

2015-11-23T07:02:44.937Z (6 sec) - Android samsung-SM-G900F_PT2658 added (current device count 23)

-------------- We got wait done, now starting the testing process ------------------

2015-11-23T07:04:38.910Z (120 sec) - Android start testing now with 23 devices

2015-11-23T07:04:38.943Z (120 sec) - iOS start testing now with 4 devices

2015-11-23T07:04:51.771Z (133 sec) - iOS Apple-IpadAir2-1_PT2253 test took 12826ms - results peers[0], reConnects[0], sendData[3]

2015-11-23T07:05:30.711Z (172 sec) - Android LGE-Nexus 5_PT1183 got re-connected event

2015-11-23T07:05:45.159Z (186 sec) - Android samsung-SM-N910C_PT166 got disconnected

2015-11-23T07:06:01.289Z (202 sec) - iOS Apple-Iphone6-1_PT606 test took 82344ms - results peers[0], reConnects[0], sendData[3]

2015-11-23T07:06:09.804Z (211 sec) - Android LGE-LG-D802_PT4132 got disconnected

2015-11-23T07:06:09.915Z (211 sec) - Android samsung-SM-G900F_PT9133 got disconnected

2015-11-23T07:06:09.984Z (211 sec) - Android LGE-Nexus 5_PT1183 got disconnected

2015-11-23T07:06:10.891Z (212 sec) - iOS Apple-Iphone5s-1_PT1828 got disconnected

2015-11-23T07:06:11.634Z (213 sec) - Android samsung-SM-G800F_PT592 got disconnected

2015-11-23T07:06:13.290Z (214 sec) - Android LGE-LG-D722_PT7432 got disconnected

2015-11-23T07:06:36.375Z (238 sec) - Android LGE-LG-H815_PT8761 got disconnected

2015-11-23T07:06:55.711Z (257 sec) - Android LGE-Nexus 5_PT1183 got disconnected

2015-11-23T07:07:02.746Z (264 sec) - Android samsung-SM-A300FU_PT8624 got disconnected

2015-11-23T07:07:07.765Z (269 sec) - Android HTC-HTC Desire 820_PT2883 got disconnected

2015-11-23T07:08:18.447Z (340 sec) - Android HTC-HTC One M8s_PT5815 got disconnected

2015-11-23T07:08:21.020Z (342 sec) - Android HTC-HTC Desire 820_PT6261 got disconnected

2015-11-23T07:08:25.665Z (347 sec) - Android samsung-SM-A300FU_PT3299 got disconnected

2015-11-23T07:08:38.100Z (359 sec) - iOS Apple-Iphone5-1_PT8536 test took 239153ms - results peers[0], reConnects[0], sendData[3]

2015-11-23T07:09:58.051Z (439 sec) - Android motorola-XT1039_PT7324 got disconnected

2015-11-23T07:10:05.115Z (446 sec) - iOS Apple-Iphone6-1_PT606 got disconnected

2015-11-23T07:10:27.998Z (469 sec) - iOS Apple-IpadAir2-1_PT2253 got re-connected event

2015-11-23T07:10:37.458Z (479 sec) - iOS Apple-IpadAir2-1_PT2253 got disconnected

2015-11-23T07:10:38.812Z (480 sec) - Android motorola-XT1039_PT7324 got re-connected event

2015-11-23T07:11:13.039Z (514 sec) - Android LGE-LG-D855_PT9692 got disconnected

2015-11-23T07:11:43.735Z (545 sec) - Android samsung-SM-A500FU_PT2202 got disconnected

2015-11-23T07:12:03.762Z (565 sec) - iOS Apple-Iphone6-1_PT606 got re-connected event

2015-11-23T07:12:21.172Z (582 sec) - iOS Apple-Iphone5-1_PT8536 got disconnected

2015-11-23T07:12:25.445Z (587 sec) - Android motorola-XT1072_PT5723 got disconnected

2015-11-23T07:12:43.113Z (604 sec) - iOS Apple-Iphone5-1_PT8536 got re-connected event

2015-11-23T07:13:28.391Z (650 sec) - iOS Apple-Iphone6-1_PT606 got disconnected

2015-11-23T07:13:30.072Z (651 sec) - iOS Apple-Iphone6-1_PT606 got re-connected event

2015-11-23T07:13:47.032Z (668 sec) - Android motorola-XT1039_PT7324 got disconnected

2015-11-23T07:13:58.434Z (680 sec) - iOS Apple-IpadAir2-1_PT2253 got disconnected

2015-11-23T07:14:36.881Z (718 sec) - iOS Apple-Iphone5-1_PT8536 got re-connected event

2015-11-23T07:14:37.466Z (719 sec) - iOS Apple-Iphone5-1_PT8536 got disconnected

2015-11-23T07:15:31.729Z (773 sec) - iOS Apple-IpadAir2-1_PT2253 got re-connected event

2015-11-23T07:15:45.115Z (786 sec) - iOS Apple-Iphone6-1_PT606 got disconnected

2015-11-23T07:16:02.304Z (803 sec) - iOS Apple-Iphone5-1_PT8536 got disconnected

2015-11-23T07:16:03.090Z (804 sec) - iOS Apple-Iphone5-1_PT8536 got re-connected event

2015-11-23T07:17:10.230Z (871 sec) - Android motorola-XT1039_PT7324 got re-connected event

2015-11-23T07:19:43.552Z (1025 sec) - iOS Apple-Iphone5-1_PT8536 got re-connected event

2015-11-23T07:19:50.690Z (1032 sec) - Android motorola-XT1039_PT7324 got disconnected

2015-11-23T07:20:01.760Z (1043 sec) - iOS Apple-Iphone5-1_PT8536 got disconnected

2015-11-23T07:20:17.410Z (1059 sec) - Android motorola-XT1072_PT5723 got re-connected event

2015-11-23T07:21:04.625Z (1106 sec) - Android LGE-LG-D802_PT4132 got re-connected event

2015-11-23T07:21:19.279Z (1120 sec) - Android samsung-SM-N9005_PT8165 test took 1000344ms - results peers[0], reConnects[0], sendData[22]

2015-11-23T07:21:19.346Z (1121 sec) - Android samsung-SM-A500FU_PT3692 test took 1000416ms - results peers[0], reConnects[0], sendData[22]

2015-11-23T07:21:19.436Z (1121 sec) - Android HTC-HTC One_M8_PT144 test took 1000512ms - results peers[0], reConnects[0], sendData[22]

2015-11-23T07:21:19.598Z (1121 sec) - Android HUAWEI-ALE-L21_PT4320 test took 1000679ms - results peers[0], reConnects[0], sendData[22]

2015-11-23T07:21:19.867Z (1121 sec) - Android LGE-Nexus 5_PT8310 test took 1000939ms - results peers[0], reConnects[0], sendData[22]

2015-11-23T07:21:20.305Z (1121 sec) - Android motorola-XT1072_PT5723 test took 1001368ms - results peers[0], reConnects[0], sendData[22]

2015-11-23T07:21:20.838Z (1122 sec) - Android samsung-SM-G900F_PT2658 test took 1001900ms - results peers[0], reConnects[0], sendData[22]

2015-11-23T07:21:22.468Z (1124 sec) - Android motorola-XT1039_PT7324 got re-connected event

2015-11-23T07:21:22.485Z (1124 sec) - Android motorola-XT1039_PT7324 test took 1003561ms - results peers[0], reConnects[0], sendData[22]

2015-11-23T07:21:25.403Z (1127 sec) - Android LGE-LG-D802_PT4132 test took 1006480ms - results peers[0], reConnects[0], sendData[22]

2015-11-23T07:21:29.842Z (1131 sec) - Android motorola-Nexus 6_PT6430 got re-connected event

2015-11-23T07:21:29.875Z (1131 sec) - Android motorola-Nexus 6_PT6430 test took 1010939ms - results peers[0], reConnects[0], sendData[22]

2015-11-23T07:22:30.800Z (1192 sec) - Android motorola-Nexus 6_PT6430 got disconnected

2015-11-23T07:24:38.942Z (1320 sec) - Server timeout reached!

2015-11-23T07:24:38.944Z (1320 sec) - Send timeout to LGE-LG-D855_PT9692

2015-11-23T07:24:38.945Z (1320 sec) - Send timeout to LGE-Nexus 5_PT1183

2015-11-23T07:24:38.946Z (1320 sec) - Send timeout to samsung-SM-G900F_PT9133
2015-11-23T07:24:38.947Z (1320 sec) - Send timeout to samsung-SM-N910C_PT166

2015-11-23T07:24:38.947Z (1320 sec) - Send timeout to HTC-HTC Desire 820_PT2883
2015-11-23T07:24:38.948Z (1320 sec) - Send timeout to HTC-HTC One M8s_PT5815

2015-11-23T07:24:38.949Z (1320 sec) - Send timeout to HTC-HTC Desire 820_PT6261
2015-11-23T07:24:38.949Z (1320 sec) - Send timeout to LGE-LG-H815_PT8761
2015-11-23T07:24:38.950Z (1320 sec) - Send timeout to samsung-SM-A500FU_PT2202

2015-11-23T07:24:38.950Z (1320 sec) - Send timeout to samsung-SM-G800F_PT592
2015-11-23T07:24:38.951Z (1320 sec) - Send timeout to samsung-SM-A300FU_PT8624

2015-11-23T07:24:38.952Z (1320 sec) - Send timeout to samsung-SM-A300FU_PT3299
2015-11-23T07:24:38.952Z (1320 sec) - Send timeout to LGE-LG-D722_PT7432

2015-11-23T07:24:38.959Z (1320 sec) - Server timeout reached!

2015-11-23T07:24:38.960Z (1320 sec) - Send timeout to Apple-Iphone5s-1_PT1828

2015-11-23T07:25:38.954Z (1380 sec) - Did not get reports from all devices, but forcing tests to finish!

LGE-LG-D855_PT9692 did not have results at the end of tests - check the device logs about why!!

LGE-Nexus 5_PT1183 did not have results at the end of tests - check the device logs about why!!

samsung-SM-G900F_PT9133 did not have results at the end of tests - check the device logs about why!!

samsung-SM-N910C_PT166 did not have results at the end of tests - check the device logs about why!!
HTC-HTC Desire 820_PT2883 did not have results at the end of tests - check the device logs about why!!
HTC-HTC One M8s_PT5815 did not have results at the end of tests - check the device logs about why!!
HTC-HTC Desire 820_PT6261 did not have results at the end of tests - check the device logs about why!!
LGE-LG-H815_PT8761 did not have results at the end of tests - check the device logs about why!!
samsung-SM-A500FU_PT2202 did not have results at the end of tests - check the device logs about why!!

samsung-SM-G800F_PT592 did not have results at the end of tests - check the device logs about why!!
samsung-SM-A300FU_PT8624 did not have results at the end of tests - check the device logs about why!!
samsung-SM-A300FU_PT3299 did not have results at the end of tests - check the device logs about why!!
LGE-LG-D722_PT7432 did not have results at the end of tests - check the device logs about why!!

2015-11-23T07:25:38.980Z (1380 sec) - Android All tests are done, preparing test report

--------------- test report ---------------------

--------------- HUAWEI-ALE-L21_PT4320 --------------------- : 1

sendList : 100% : 137053 ms, 99% : 137053 ms, 95 : 137053 ms, 90% : 87105 ms.

Result count 10, range 4616 ms to  137053 ms.

sendList failed peers count : 5 [33.333333333333336 %]
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 7C:F9:0E:51:18:22, Tried : 1
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
sendList never tried peers count : 7 [31.818181818181817 %]
- Peer ID : 50:2E:6C:AC:21:50
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : E0:DB:10:14:E2:C0

--------------- LGE-LG-D802_PT4132 --------------------- : 2
sendList : 100% : 65201 ms, 99% : 65201 ms, 95 : 65201 ms, 90% : 65201 ms.
Result count 3, range 6306 ms to  65201 ms.
sendList failed peers count : 4 [57.142857142857146 %]
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
sendList never tried peers count : 15 [68.18181818181819 %]
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 58:2A:F7:ED:96:BE
- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : E0:DB:10:1F:C9:5E
- Peer ID : F8:95:C7:87:85:54
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 90:E7:C4:F6:69:77
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 50:2E:6C:AC:21:50
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : 08:EC:A9:50:75:41
--------------- HTC-HTC One_M8_PT144 --------------------- : 3
sendList : 100% : 36799 ms, 99% : 36799 ms, 95 : 36799 ms, 90% : 34496 ms.
Result count 9, range 4183 ms to  36799 ms.
sendList failed peers count : 7 [43.75 %]
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
sendList never tried peers count : 6 [27.272727272727273 %]
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : F8:95:C7:87:85:54
- Peer ID : 08:EC:A9:50:75:41
--------------- motorola-XT1039_PT7324 --------------------- : 4
sendList : 100% : 77985 ms, 99% : 77985 ms, 95 : 63934 ms, 90% : 63059 ms.
Result count 17, range 5326 ms to  77985 ms.
sendList failed peers count : 5 [22.727272727272727 %]
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 2
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
sendList never tried peers count : 0 [0 %]
--------------- LGE-Nexus 5_PT8310 --------------------- : 5

sendList : 100% : 117839 ms, 99% : 117839 ms, 95 : 114496 ms, 90% : 114496 ms.
Result count 13, range 3445 ms to  117839 ms.
sendList failed peers count : 4 [23.529411764705884 %]

- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
sendList never tried peers count : 5 [22.727272727272727 %]
- Peer ID : 90:E7:C4:F6:69:77
- Peer ID : 58:2A:F7:ED:96:BE

- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 34:FC:EF:9D:93:0B
--------------- samsung-SM-A500FU_PT3692 --------------------- : 6
sendList : 100% : 175320 ms, 99% : 175320 ms, 95 : 44528 ms, 90% : 44149 ms.
Result count 16, range 5425 ms to  175320 ms.
sendList failed peers count : 6 [27.272727272727273 %]

- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-N9005_PT8165 --------------------- : 7
sendList : 100% : 107761 ms, 99% : 107761 ms, 95 : 69392 ms, 90% : 69392 ms.
Result count 15, range 2579 ms to  107761 ms.
sendList failed peers count : 5 [25 %]
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
sendList never tried peers count : 2 [9.090909090909092 %]
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 7C:F9:0E:51:18:22

--------------- motorola-Nexus 6_PT6430 --------------------- : 8
sendList : 100% : 165576 ms, 99% : 165576 ms, 95 : 165576 ms, 90% : 133912 ms.
Result count 10, range 11760 ms to  165576 ms.
sendList failed peers count : 6 [37.5 %]
- Peer ID : 7C:F9:0E:51:18:22, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1

- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
sendList never tried peers count : 6 [27.272727272727273 %]
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : B0:C5:59:3F:75:69

- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 44:80:EB:7B:5A:05
--------------- motorola-XT1072_PT5723 --------------------- : 9
sendList : 100% : 119103 ms, 99% : 119103 ms, 95 : 96417 ms, 90% : 96417 ms.
Result count 12, range 2496 ms to  119103 ms.
sendList failed peers count : 7 [36.8421052631579 %]

- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1

- Peer ID : 90:E7:C4:F6:69:77, Tried : 1
sendList never tried peers count : 3 [13.636363636363637 %]
- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 08:EC:A9:50:76:27

--------------- samsung-SM-G900F_PT2658 --------------------- : 10
sendList : 100% : 71528 ms, 99% : 71528 ms, 95 : 45321 ms, 90% : 27660 ms.
Result count 18, range 2924 ms to  71528 ms.
sendList failed peers count : 4 [18.181818181818183 %]
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 2
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1

- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 2
sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------

sendList : 100% : 175320 ms, 99% : 165576 ms, 95 : 114496 ms, 90% : 80144 ms.

--------------- end of test report ---------------------

2015-11-23T07:25:39.125Z (1380 sec) - Did not get reports from all devices, but forcing tests to finish!

Apple-Iphone5s-1_PT1828 did not have results at the end of tests - check the device logs about why!!
2015-11-23T07:25:39.128Z (1380 sec) - iOS All tests are done, preparing test report
--------------- test report ---------------------
--------------- Apple-IpadAir2-1_PT2253 --------------------- : 1
sendList : 100% : 4949 ms, 99% : 4949 ms, 95 : 4949 ms, 90% : 4949 ms.
Result count 3, range 2967 ms to  4949 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1_PT606 --------------------- : 2
sendList : 100% : 3327 ms, 99% : 3327 ms, 95 : 3327 ms, 90% : 3327 ms.
Result count 2, range 3054 ms to  3327 ms.
sendList failed peers count : 1 [33.333333333333336 %]
- Peer ID : Apple-Iphone5s-1_PT8264./5qd6Q==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5-1_PT8536 --------------------- : 3
sendList : 100% : 3663 ms, 99% : 3663 ms, 95 : 3663 ms, 90% : 3663 ms.
Result count 2, range 3538 ms to  3663 ms.
sendList failed peers count : 1 [33.333333333333336 %]
- Peer ID : Apple-Iphone5s-1_PT8264./5qd6Q==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------
sendList : 100% : 4949 ms, 99% : 4949 ms, 95 : 4949 ms, 90% : 3663 ms.

--------------- end of test report ---------------------


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


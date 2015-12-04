#### Test 52539314a265f91 Logs

Status: 
```

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code 254 on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
true


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

2015-12-04T08:07:27.497Z (0 sec) - Android tests will start after waiting for 120 seconds

Test ID 0 configuration: testSendData.js, server timeout: 1200000, data:

{ timeout: 1000000,
  rounds: 1,
  dataTimeout: 10000,
  dataAmount: 100000,
  conReTryTimeout: 5000,
  conReTryCount: 5 }

2015-12-04T08:07:27.503Z (0 sec) - iOS tests will start after waiting for 120 seconds

listening on *:3000

2015-12-04T08:07:28.085Z (1 sec) - Android LGE-Nexus 5_PT5146 added (current device count 1)

2015-12-04T08:07:28.091Z (1 sec) - Android LGE-LG-D802_PT5431 added (current device count 2)

2015-12-04T08:07:28.180Z (1 sec) - iOS Apple-Iphone5-1_PT1372 added (current device count 1)

2015-12-04T08:07:28.342Z (1 sec) - Android samsung-SM-G800H_PT5954 added (current device count 3)

2015-12-04T08:07:28.527Z (1 sec) - Android LGE-LG-H815_PT8707 added (current device count 4)

2015-12-04T08:07:28.546Z (1 sec) - iOS Apple-IpadAir2-1_PT2716 added (current device count 2)

2015-12-04T08:07:28.611Z (1 sec) - Android samsung-SM-N910C_PT2368 added (current device count 5)

2015-12-04T08:07:28.647Z (1 sec) - Android samsung-SM-N9005_PT5544 added (current device count 6)

2015-12-04T08:07:28.813Z (1 sec) - Android HTC-HTC Desire 820_PT3449 added (current device count 7)

2015-12-04T08:07:29.709Z (2 sec) - Android samsung-SM-A300FU_PT476 added (current device count 8)

2015-12-04T08:07:30.482Z (3 sec) - Android samsung-SM-A500FU_PT1688 added (current device count 9)

2015-12-04T08:07:30.653Z (3 sec) - Android samsung-SM-A300FU_PT2828 added (current device count 10)

2015-12-04T08:07:30.827Z (3 sec) - Android LGE-Nexus 5_PT5363 added (current device count 11)

2015-12-04T08:07:31.042Z (4 sec) - Android LGE-LG-D722_PT9142 added (current device count 12)

2015-12-04T08:07:31.333Z (4 sec) - Android samsung-SM-G900F_PT2753 added (current device count 13)

2015-12-04T08:07:31.500Z (4 sec) - Android HTC-HTC Desire 820_PT3559 added (current device count 14)

2015-12-04T08:07:31.513Z (4 sec) - Android HUAWEI-ALE-L21_PT7753 added (current device count 15)

2015-12-04T08:07:31.541Z (4 sec) - iOS Apple-Iphone6-1_PT9579 added (current device count 3)

2015-12-04T08:07:32.184Z (5 sec) - Android motorola-Nexus 6_PT8001 added (current device count 16)

2015-12-04T08:07:32.235Z (5 sec) - Android samsung-SM-G900F_PT807 added (current device count 17)

2015-12-04T08:07:32.244Z (5 sec) - Android motorola-XT1072_PT2491 added (current device count 18)

2015-12-04T08:07:32.340Z (5 sec) - Android LGE-LG-D855_PT6390 added (current device count 19)

2015-12-04T08:07:34.628Z (7 sec) - Android samsung-SM-G800F_PT4577 added (current device count 20)

2015-12-04T08:08:04.014Z (37 sec) - Android motorola-XT1039_PT8025 added (current device count 21)

-------------- We got wait done, now starting the testing process ------------------

2015-12-04T08:09:27.542Z (120 sec) - Android start testing now with 21 devices

2015-12-04T08:09:27.570Z (120 sec) - iOS start testing now with 3 devices

2015-12-04T08:09:35.608Z (128 sec) - iOS Apple-Iphone5-1_PT1372 test took 8037ms - results peers[0], reConnects[0], sendData[2]

2015-12-04T08:09:36.703Z (129 sec) - iOS Apple-Iphone6-1_PT9579 test took 9131ms - results peers[0], reConnects[0], sendData[2]

2015-12-04T08:10:36.012Z (189 sec) - Android LGE-Nexus 5_PT5363 got disconnected

2015-12-04T08:10:50.740Z (203 sec) - Android LGE-Nexus 5_PT5363 got re-connected event

2015-12-04T08:11:19.309Z (232 sec) - iOS Apple-Iphone6-1_PT9579 got re-connected event

2015-12-04T08:11:19.943Z (232 sec) - iOS Apple-IpadAir2-1_PT2716 test took 112372ms - results peers[0], reConnects[0], sendData[2]

2015-12-04T08:11:19.944Z (232 sec) - iOS test ID 0 done now

2015-12-04T08:11:19.951Z (232 sec) - iOS All tests are done, preparing test report

--------------- test report ---------------------

--------------- Apple-Iphone5-1_PT1372 --------------------- : 1

sendList : 100% : 3745 ms, 99% : 3745 ms, 95 : 3745 ms, 90% : 3745 ms.

Average data rate: 0.029 MB/s

Result count 2, range 3231 ms to  3745 ms.

sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- Apple-IpadAir2-1_PT2716 --------------------- : 2

sendList : 100% : 3216 ms, 99% : 3216 ms, 95 : 3216 ms, 90% : 3216 ms.
Average data rate: 0.031 MB/s
Result count 1, range 3216 ms to  3216 ms.

sendList failed peers count : 1 [50 %]

- Peer ID : Apple-Iphone6-1_PT9579.WOzdIQ==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone6-1_PT9579 --------------------- : 3
sendList : 100% : 3572 ms, 99% : 3572 ms, 95 : 3572 ms, 90% : 3572 ms.
Average data rate: 0.03 MB/s
Result count 2, range 3120 ms to  3572 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- Combined ---------------------
sendList : 100% : 3745 ms, 99% : 3745 ms, 95 : 3745 ms, 90% : 3745 ms.
Average data rate: 0.03 MB/s

--------------- end of test report ---------------------

2015-12-04T08:11:20.362Z (233 sec) - iOS Apple-Iphone6-1_PT9579 got disconnected

2015-12-04T08:11:20.440Z (233 sec) - iOS Apple-IpadAir2-1_PT2716 got disconnected

2015-12-04T08:11:22.630Z (235 sec) - iOS Apple-Iphone5-1_PT1372 got disconnected

2015-12-04T08:11:27.397Z (240 sec) - iOS Apple-Iphone6-1_PT9579 got disconnected

2015-12-04T08:11:27.527Z (240 sec) - Android motorola-Nexus 6_PT8001 got disconnected

2015-12-04T08:11:27.674Z (240 sec) - Android HTC-HTC Desire 820_PT3559 got disconnected

2015-12-04T08:12:15.740Z (288 sec) - Android LGE-Nexus 5_PT5363 got disconnected

2015-12-04T08:13:21.977Z (355 sec) - Android HTC-HTC Desire 820_PT3559 got re-connected event

2015-12-04T08:13:29.177Z (362 sec) - Android motorola-XT1072_PT2491 got re-connected event

2015-12-04T08:13:31.719Z (364 sec) - Android HTC-HTC Desire 820_PT3449 got disconnected

2015-12-04T08:13:36.317Z (369 sec) - Android HTC-HTC Desire 820_PT3449 got re-connected event

2015-12-04T08:13:44.558Z (377 sec) - Android samsung-SM-A300FU_PT476 got disconnected

2015-12-04T08:13:48.106Z (381 sec) - Android motorola-XT1072_PT2491 got disconnected

2015-12-04T08:15:19.153Z (472 sec) - Android motorola-XT1072_PT2491 got disconnected

2015-12-04T08:16:43.250Z (556 sec) - Android samsung-SM-A300FU_PT2828 got disconnected

2015-12-04T08:16:56.282Z (569 sec) - Android HTC-HTC Desire 820_PT3449 got re-connected event

2015-12-04T08:17:12.452Z (585 sec) - Android samsung-SM-G800F_PT4577 got disconnected

2015-12-04T08:17:35.033Z (608 sec) - Android HTC-HTC Desire 820_PT3449 got disconnected

2015-12-04T08:17:41.885Z (614 sec) - Android LGE-Nexus 5_PT5363 got re-connected event

2015-12-04T08:18:13.021Z (646 sec) - Android HTC-HTC Desire 820_PT3559 got re-connected event

2015-12-04T08:18:13.394Z (646 sec) - Android HTC-HTC Desire 820_PT3559 got disconnected

2015-12-04T08:18:26.545Z (659 sec) - Android LGE-LG-D855_PT6390 got disconnected

2015-12-04T08:18:28.987Z (662 sec) - Android LGE-LG-D855_PT6390 got re-connected event

2015-12-04T08:19:24.587Z (717 sec) - Android HTC-HTC Desire 820_PT3559 got re-connected event

2015-12-04T08:19:28.577Z (721 sec) - Android LGE-Nexus 5_PT5363 got re-connected event

2015-12-04T08:19:56.889Z (749 sec) - Android LGE-Nexus 5_PT5363 got disconnected

2015-12-04T08:20:25.586Z (778 sec) - Android samsung-SM-A500FU_PT1688 got disconnected

2015-12-04T08:20:27.982Z (781 sec) - Android HTC-HTC Desire 820_PT3559 got disconnected

2015-12-04T08:21:17.518Z (830 sec) - Android samsung-SM-N910C_PT2368 got disconnected

2015-12-04T08:21:30.131Z (843 sec) - Android LGE-LG-D855_PT6390 got re-connected event

2015-12-04T08:21:35.845Z (848 sec) - Android LGE-Nexus 5_PT5363 got re-connected event

2015-12-04T08:22:24.378Z (897 sec) - Android LGE-LG-D855_PT6390 got disconnected

2015-12-04T08:22:29.119Z (902 sec) - Android LGE-Nexus 5_PT5363 got re-connected event

2015-12-04T08:22:37.032Z (910 sec) - Android LGE-Nexus 5_PT5363 got disconnected

2015-12-04T08:23:25.657Z (958 sec) - Android LGE-Nexus 5_PT5363 got disconnected

2015-12-04T08:23:52.648Z (985 sec) - Android LGE-Nexus 5_PT5363 got re-connected event

2015-12-04T08:24:19.180Z (1012 sec) - Android motorola-XT1039_PT8025 got disconnected

2015-12-04T08:24:19.479Z (1012 sec) - Android LGE-Nexus 5_PT5363 got disconnected

2015-12-04T08:25:09.600Z (1062 sec) - Android HTC-HTC Desire 820_PT3449 got re-connected event

2015-12-04T08:25:42.390Z (1095 sec) - Android LGE-Nexus 5_PT5363 got disconnected

2015-12-04T08:25:57.282Z (1110 sec) - Android HTC-HTC Desire 820_PT3449 got disconnected

2015-12-04T08:26:07.827Z (1120 sec) - Android LGE-Nexus 5_PT5146 test took 1000278ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T08:26:07.927Z (1120 sec) - Android HTC-HTC Desire 820_PT3449 test took 1000373ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T08:26:07.975Z (1121 sec) - Android LGE-LG-D855_PT6390 test took 1000411ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T08:26:08.034Z (1121 sec) - Android samsung-SM-N9005_PT5544 test took 1000480ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T08:26:08.229Z (1121 sec) - Android samsung-SM-G900F_PT807 test took 1000666ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T08:26:08.510Z (1121 sec) - Android LGE-LG-D722_PT9142 test took 1000950ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T08:26:08.951Z (1121 sec) - Android HUAWEI-ALE-L21_PT7753 test took 1001390ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T08:26:09.261Z (1122 sec) - Android samsung-SM-G800H_PT5954 test took 1001709ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T08:26:10.064Z (1123 sec) - Android LGE-LG-H815_PT8707 test took 1002512ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T08:26:11.136Z (1124 sec) - Android samsung-SM-G900F_PT2753 test took 1003576ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T08:26:13.164Z (1126 sec) - Android HTC-HTC Desire 820_PT3559 test took 1005603ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T08:26:13.298Z (1126 sec) - Android LGE-LG-D802_PT5431 test took 1005747ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T08:27:08.309Z (1181 sec) - Android LGE-Nexus 5_PT5363 got re-connected event

2015-12-04T08:27:08.313Z (1181 sec) - Android LGE-Nexus 5_PT5363 test took 1060754ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T08:29:27.568Z (1320 sec) - Server timeout reached!

2015-12-04T08:29:27.569Z (1320 sec) - Send timeout to samsung-SM-N910C_PT2368

2015-12-04T08:29:27.570Z (1320 sec) - Send timeout to samsung-SM-A300FU_PT476

2015-12-04T08:29:27.571Z (1320 sec) - Send timeout to samsung-SM-A500FU_PT1688
2015-12-04T08:29:27.572Z (1320 sec) - Send timeout to samsung-SM-A300FU_PT2828

2015-12-04T08:29:27.573Z (1320 sec) - Send timeout to motorola-Nexus 6_PT8001
2015-12-04T08:29:27.574Z (1320 sec) - Send timeout to motorola-XT1072_PT2491
2015-12-04T08:29:27.575Z (1320 sec) - Send timeout to samsung-SM-G800F_PT4577
2015-12-04T08:29:27.575Z (1320 sec) - Send timeout to motorola-XT1039_PT8025

2015-12-04T08:30:27.578Z (1380 sec) - Did not get reports from all devices, but forcing tests to finish!

samsung-SM-N910C_PT2368 did not have results at the end of tests - check the device logs about why!!

samsung-SM-A300FU_PT476 did not have results at the end of tests - check the device logs about why!!
samsung-SM-A500FU_PT1688 did not have results at the end of tests - check the device logs about why!!
samsung-SM-A300FU_PT2828 did not have results at the end of tests - check the device logs about why!!
motorola-Nexus 6_PT8001 did not have results at the end of tests - check the device logs about why!!
motorola-XT1072_PT2491 did not have results at the end of tests - check the device logs about why!!

samsung-SM-G800F_PT4577 did not have results at the end of tests - check the device logs about why!!

motorola-XT1039_PT8025 did not have results at the end of tests - check the device logs about why!!

2015-12-04T08:30:27.601Z (1380 sec) - Android All tests are done, preparing test report

--------------- test report ---------------------
--------------- LGE-Nexus 5_PT5146 --------------------- : 1

sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 10 [100 %]

- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 38:94:96:B5:06:DC, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1

- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1

sendList never tried peers count : 10 [50 %]
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 58:2A:F7:ED:96:BE

- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 44:80:EB:7B:5A:05

- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : F8:CF:C5:D9:E5:61
- Peer ID : F4:F1:E1:5C:3B:E2
--------------- LGE-LG-D802_PT5431 --------------------- : 2

sendList : 100% : 58234 ms, 99% : 58234 ms, 95 : 58234 ms, 90% : 58234 ms.
Average data rate: 0.004 MB/s
Result count 3, range 10509 ms to  58234 ms.
sendList failed peers count : 9 [75 %]

- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 38:94:96:B5:06:DC, Tried : 1
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1

- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
sendList never tried peers count : 8 [40 %]

- Peer ID : 08:EC:A9:50:75:41
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 44:80:EB:7B:5A:05

- Peer ID : 58:2A:F7:ED:96:BE
- Peer ID : E0:DB:10:1F:C9:5E
--------------- samsung-SM-G800H_PT5954 --------------------- : 3

sendList : 100% : 7140 ms, 99% : 7140 ms, 95 : 7140 ms, 90% : 7140 ms.

Average data rate: 0.014 MB/s
Result count 1, range 7140 ms to  7140 ms.
sendList failed peers count : 9 [90 %]
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1

- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1

- Peer ID : 08:EC:A9:50:75:41, Tried : 1
sendList never tried peers count : 10 [50 %]
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : E0:DB:10:1F:C9:5E

- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : 58:2A:F7:ED:96:BE
- Peer ID : E0:DB:10:14:E2:C0

- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 7C:F9:0E:34:8A:A0
--------------- LGE-LG-H815_PT8707 --------------------- : 4
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s

Results list does not contain any items
sendList failed peers count : 8 [100 %]
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : 38:94:96:B5:06:DC, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1

- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1

sendList never tried peers count : 12 [60 %]
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : B0:C5:59:3F:75:69

- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : 58:2A:F7:ED:96:BE
- Peer ID : F8:95:C7:87:85:54
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 7C:F9:0E:34:8A:A0

- Peer ID : F8:CF:C5:D9:E5:61
- Peer ID : 08:EC:A9:50:76:27
--------------- samsung-SM-N9005_PT5544 --------------------- : 5
sendList : 100% : 6471 ms, 99% : 6471 ms, 95 : 6471 ms, 90% : 6471 ms.

Average data rate: 0.017 MB/s
Result count 2, range 5629 ms to  6471 ms.
sendList failed peers count : 11 [84.61538461538461 %]
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1

- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1

- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
sendList never tried peers count : 7 [35 %]

- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : 38:94:96:B5:06:DC
- Peer ID : 34:FC:EF:11:B1:66

- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 58:2A:F7:ED:96:BE
--------------- HTC-HTC Desire 820_PT3449 --------------------- : 6
sendList : 100% : 25774 ms, 99% : 25774 ms, 95 : 25774 ms, 90% : 25774 ms.

Average data rate: 0.006 MB/s
Result count 2, range 10376 ms to  25774 ms.
sendList failed peers count : 9 [81.81818181818181 %]
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1

- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : 38:94:96:B5:06:DC, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1

- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
sendList never tried peers count : 9 [45 %]
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : 00:F4:6F:30:E0:6C

- Peer ID : B0:C5:59:3F:75:69
- Peer ID : E0:DB:10:1F:C9:5E
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 58:2A:F7:ED:96:BE

- Peer ID : F8:95:C7:87:3C:51
--------------- LGE-Nexus 5_PT5363 --------------------- : 7
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items

sendList failed peers count : 12 [100 %]
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1

- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1

- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
sendList never tried peers count : 8 [40 %]
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : F8:CF:C5:D9:E5:61

- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : E0:DB:10:1F:C9:5E
- Peer ID : 38:94:96:B5:06:DC
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 58:2A:F7:ED:96:BE
--------------- LGE-LG-D722_PT9142 --------------------- : 8
sendList : 100% : 7145 ms, 99% : 7145 ms, 95 : 7145 ms, 90% : 7145 ms.
Average data rate: 0.015 MB/s
Result count 2, range 6463 ms to  7145 ms.
sendList failed peers count : 8 [80 %]
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : 38:94:96:B5:06:DC, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
sendList never tried peers count : 10 [50 %]
- Peer ID : F8:CF:C5:D9:E5:61
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : 58:2A:F7:ED:96:BE
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : E0:DB:10:1F:C9:5E
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 08:EC:A9:50:75:41
--------------- samsung-SM-G900F_PT2753 --------------------- : 9
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 11 [100 %]
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 38:94:96:B5:06:DC, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1

- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
sendList never tried peers count : 9 [45 %]
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : E0:DB:10:1F:C9:5E
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 34:FC:EF:9D:93:0B

- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 58:2A:F7:ED:96:BE
--------------- HTC-HTC Desire 820_PT3559 --------------------- : 10
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.

Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 9 [100 %]
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 38:94:96:B5:06:DC, Tried : 1

- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1

- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
sendList never tried peers count : 11 [55 %]
- Peer ID : E0:DB:10:1F:C9:5E
- Peer ID : 7C:F9:0E:34:8A:A0

- Peer ID : F8:CF:C5:D9:E5:61
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 34:FC:EF:11:AE:67

- Peer ID : F8:95:C7:87:85:54
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : E0:DB:10:14:E2:C0
--------------- HUAWEI-ALE-L21_PT7753 --------------------- : 11

sendList : 100% : 17439 ms, 99% : 17439 ms, 95 : 17439 ms, 90% : 17439 ms.

Average data rate: 0.008 MB/s

Result count 3, range 7437 ms to  17439 ms.
sendList failed peers count : 8 [72.72727272727273 %]
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : 38:94:96:B5:06:DC, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1

- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
sendList never tried peers count : 9 [45 %]

- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 08:EC:A9:50:75:41

- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : F8:95:C7:87:85:54
--------------- samsung-SM-G900F_PT807 --------------------- : 12

sendList : 100% : 37949 ms, 99% : 37949 ms, 95 : 37949 ms, 90% : 37949 ms.
Average data rate: 0.003 MB/s
Result count 1, range 37949 ms to  37949 ms.
sendList failed peers count : 10 [90.9090909090909 %]

- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1

- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
sendList never tried peers count : 9 [45 %]

- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : E0:DB:10:1F:C9:5E

- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 58:2A:F7:ED:96:BE
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 38:94:96:B5:06:DC
--------------- LGE-LG-D855_PT6390 --------------------- : 13

sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 10 [100 %]
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1

- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1

- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
sendList never tried peers count : 10 [50 %]
- Peer ID : 58:2A:F7:ED:96:BE
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 38:94:96:B5:06:DC
--------------- Combined ---------------------
sendList : 100% : 58234 ms, 99% : 58234 ms, 95 : 37949 ms, 90% : 37949 ms.
Average data rate: 0.006 MB/s
--------------- end of test report ---------------------

2015-12-04T08:30:27.945Z (1380 sec) - Android LGE-LG-D722_PT9142 got disconnected

2015-12-04T08:30:28.030Z (1381 sec) - Android LGE-Nexus 5_PT5146 got disconnected

2015-12-04T08:30:28.067Z (1381 sec) - Android LGE-Nexus 5_PT5363 got disconnected

2015-12-04T08:30:28.085Z (1381 sec) - Android samsung-SM-G900F_PT807 got disconnected

2015-12-04T08:30:28.091Z (1381 sec) - Android LGE-LG-D802_PT5431 got disconnected

2015-12-04T08:30:28.120Z (1381 sec) - Android LGE-LG-H815_PT8707 got disconnected

2015-12-04T08:30:28.147Z (1381 sec) - Android samsung-SM-N9005_PT5544 got disconnected

2015-12-04T08:30:28.662Z (1381 sec) - Android samsung-SM-G800H_PT5954 got disconnected

2015-12-04T08:30:29.062Z (1382 sec) - Android HUAWEI-ALE-L21_PT7753 got disconnected

2015-12-04T08:30:29.154Z (1382 sec) - Android samsung-SM-G900F_PT2753 got disconnected

2015-12-04T08:30:29.812Z (1382 sec) - Android HTC-HTC Desire 820_PT3449 got disconnected

2015-12-04T08:30:35.273Z (1388 sec) - Android LGE-LG-D855_PT6390 got disconnected

2015-12-04T08:31:48.505Z (1461 sec) - Android HTC-HTC Desire 820_PT3559 got disconnected


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```
###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/52539314a265f91_Relax_the_installation_folder_requirement__vjrantal/iOS_Iphone5-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/52539314a265f91_Relax_the_installation_folder_requirement__vjrantal/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/52539314a265f91_Relax_the_installation_folder_requirement__vjrantal/iOS_Iphone6-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/52539314a265f91_Relax_the_installation_folder_requirement__vjrantal/iOS_IpadAir2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/52539314a265f91_Relax_the_installation_folder_requirement__vjrantal/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/52539314a265f91_Relax_the_installation_folder_requirement__vjrantal/thali01_LGE-LG-H815.md)

[HUAWEI-ALE-L21](https://github.com/ThaliTester/TestResults/blob/52539314a265f91_Relax_the_installation_folder_requirement__vjrantal/thali01_HUAWEI-ALE-L21.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/52539314a265f91_Relax_the_installation_folder_requirement__vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/52539314a265f91_Relax_the_installation_folder_requirement__vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/52539314a265f91_Relax_the_installation_folder_requirement__vjrantal/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/52539314a265f91_Relax_the_installation_folder_requirement__vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/52539314a265f91_Relax_the_installation_folder_requirement__vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/52539314a265f91_Relax_the_installation_folder_requirement__vjrantal/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/52539314a265f91_Relax_the_installation_folder_requirement__vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/52539314a265f91_Relax_the_installation_folder_requirement__vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/52539314a265f91_Relax_the_installation_folder_requirement__vjrantal/thali04_samsung-SM-G900F.md)

####Node name: thali05
Console output:
```
STOP log received from  954a12ed Test has  SUCCEEDED
STOP log received from  1d6a772d Test has  SUCCEEDED
Device test finished on 1d6a772d 
Device test finished on 954a12ed 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:null 
child process exited with code null on device ZX1G429CRK 
Android task is completed. [FAILED]
```
[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/52539314a265f91_Relax_the_installation_folder_requirement__vjrantal/thali05_samsung-SM-N9005.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/52539314a265f91_Relax_the_installation_folder_requirement__vjrantal/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/52539314a265f91_Relax_the_installation_folder_requirement__vjrantal/thali05_samsung-SM-G800H.md)

####Node name: thali06
Console output:
```
STOP log received from  022678fb504e29b0 Test has  SUCCEEDED
Device test finished on 022678fb504e29b0 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:0 
child process exited with code 0 on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:0 
child process exited with code 0 on device FA55PYS00566 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/52539314a265f91_Relax_the_installation_folder_requirement__vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/52539314a265f91_Relax_the_installation_folder_requirement__vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/52539314a265f91_Relax_the_installation_folder_requirement__vjrantal/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/52539314a265f91_Relax_the_installation_folder_requirement__vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/52539314a265f91_Relax_the_installation_folder_requirement__vjrantal/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/52539314a265f91_Relax_the_installation_folder_requirement__vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/52539314a265f91_Relax_the_installation_folder_requirement__vjrantal/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
Device test finished on 0c6a0f3c0bdb4e77 
STOP log received from  CC51WYC03425 Test has  SUCCEEDED
Device test finished on CC51WYC03425 
Android task is completed. [SUCCESS]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/52539314a265f91_Relax_the_installation_folder_requirement__vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/52539314a265f91_Relax_the_installation_folder_requirement__vjrantal/thali09_LGE-Nexus 5.md)




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

2015-12-04T08:07:27.497Z (0 sec) - Android tests will start after waiting for 120 seconds

Test ID 0 configuration: testSendData.js, server timeout: 1200000, data:

{ timeout: 1000000,
  rounds: 1,
  dataTimeout: 10000,
  dataAmount: 100000,
  conReTryTimeout: 5000,
  conReTryCount: 5 }

2015-12-04T08:07:27.503Z (0 sec) - iOS tests will start after waiting for 120 seconds

listening on *:3000

2015-12-04T08:07:28.085Z (1 sec) - Android LGE-Nexus 5_PT5146 added (current device count 1)

2015-12-04T08:07:28.091Z (1 sec) - Android LGE-LG-D802_PT5431 added (current device count 2)

2015-12-04T08:07:28.180Z (1 sec) - iOS Apple-Iphone5-1_PT1372 added (current device count 1)

2015-12-04T08:07:28.342Z (1 sec) - Android samsung-SM-G800H_PT5954 added (current device count 3)

2015-12-04T08:07:28.527Z (1 sec) - Android LGE-LG-H815_PT8707 added (current device count 4)

2015-12-04T08:07:28.546Z (1 sec) - iOS Apple-IpadAir2-1_PT2716 added (current device count 2)

2015-12-04T08:07:28.611Z (1 sec) - Android samsung-SM-N910C_PT2368 added (current device count 5)

2015-12-04T08:07:28.647Z (1 sec) - Android samsung-SM-N9005_PT5544 added (current device count 6)

2015-12-04T08:07:28.813Z (1 sec) - Android HTC-HTC Desire 820_PT3449 added (current device count 7)

2015-12-04T08:07:29.709Z (2 sec) - Android samsung-SM-A300FU_PT476 added (current device count 8)

2015-12-04T08:07:30.482Z (3 sec) - Android samsung-SM-A500FU_PT1688 added (current device count 9)

2015-12-04T08:07:30.653Z (3 sec) - Android samsung-SM-A300FU_PT2828 added (current device count 10)

2015-12-04T08:07:30.827Z (3 sec) - Android LGE-Nexus 5_PT5363 added (current device count 11)

2015-12-04T08:07:31.042Z (4 sec) - Android LGE-LG-D722_PT9142 added (current device count 12)

2015-12-04T08:07:31.333Z (4 sec) - Android samsung-SM-G900F_PT2753 added (current device count 13)

2015-12-04T08:07:31.500Z (4 sec) - Android HTC-HTC Desire 820_PT3559 added (current device count 14)

2015-12-04T08:07:31.513Z (4 sec) - Android HUAWEI-ALE-L21_PT7753 added (current device count 15)

2015-12-04T08:07:31.541Z (4 sec) - iOS Apple-Iphone6-1_PT9579 added (current device count 3)

2015-12-04T08:07:32.184Z (5 sec) - Android motorola-Nexus 6_PT8001 added (current device count 16)

2015-12-04T08:07:32.235Z (5 sec) - Android samsung-SM-G900F_PT807 added (current device count 17)

2015-12-04T08:07:32.244Z (5 sec) - Android motorola-XT1072_PT2491 added (current device count 18)

2015-12-04T08:07:32.340Z (5 sec) - Android LGE-LG-D855_PT6390 added (current device count 19)

2015-12-04T08:07:34.628Z (7 sec) - Android samsung-SM-G800F_PT4577 added (current device count 20)

2015-12-04T08:08:04.014Z (37 sec) - Android motorola-XT1039_PT8025 added (current device count 21)

-------------- We got wait done, now starting the testing process ------------------

2015-12-04T08:09:27.542Z (120 sec) - Android start testing now with 21 devices

2015-12-04T08:09:27.570Z (120 sec) - iOS start testing now with 3 devices

2015-12-04T08:09:35.608Z (128 sec) - iOS Apple-Iphone5-1_PT1372 test took 8037ms - results peers[0], reConnects[0], sendData[2]

2015-12-04T08:09:36.703Z (129 sec) - iOS Apple-Iphone6-1_PT9579 test took 9131ms - results peers[0], reConnects[0], sendData[2]

2015-12-04T08:10:36.012Z (189 sec) - Android LGE-Nexus 5_PT5363 got disconnected

2015-12-04T08:10:50.740Z (203 sec) - Android LGE-Nexus 5_PT5363 got re-connected event

2015-12-04T08:11:19.309Z (232 sec) - iOS Apple-Iphone6-1_PT9579 got re-connected event

2015-12-04T08:11:19.943Z (232 sec) - iOS Apple-IpadAir2-1_PT2716 test took 112372ms - results peers[0], reConnects[0], sendData[2]

2015-12-04T08:11:19.944Z (232 sec) - iOS test ID 0 done now

2015-12-04T08:11:19.951Z (232 sec) - iOS All tests are done, preparing test report

--------------- test report ---------------------

--------------- Apple-Iphone5-1_PT1372 --------------------- : 1

sendList : 100% : 3745 ms, 99% : 3745 ms, 95 : 3745 ms, 90% : 3745 ms.

Average data rate: 0.029 MB/s

Result count 2, range 3231 ms to  3745 ms.

sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- Apple-IpadAir2-1_PT2716 --------------------- : 2

sendList : 100% : 3216 ms, 99% : 3216 ms, 95 : 3216 ms, 90% : 3216 ms.
Average data rate: 0.031 MB/s
Result count 1, range 3216 ms to  3216 ms.

sendList failed peers count : 1 [50 %]

- Peer ID : Apple-Iphone6-1_PT9579.WOzdIQ==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone6-1_PT9579 --------------------- : 3
sendList : 100% : 3572 ms, 99% : 3572 ms, 95 : 3572 ms, 90% : 3572 ms.
Average data rate: 0.03 MB/s
Result count 2, range 3120 ms to  3572 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- Combined ---------------------
sendList : 100% : 3745 ms, 99% : 3745 ms, 95 : 3745 ms, 90% : 3745 ms.
Average data rate: 0.03 MB/s

--------------- end of test report ---------------------

2015-12-04T08:11:20.362Z (233 sec) - iOS Apple-Iphone6-1_PT9579 got disconnected

2015-12-04T08:11:20.440Z (233 sec) - iOS Apple-IpadAir2-1_PT2716 got disconnected

2015-12-04T08:11:22.630Z (235 sec) - iOS Apple-Iphone5-1_PT1372 got disconnected

2015-12-04T08:11:27.397Z (240 sec) - iOS Apple-Iphone6-1_PT9579 got disconnected

2015-12-04T08:11:27.527Z (240 sec) - Android motorola-Nexus 6_PT8001 got disconnected

2015-12-04T08:11:27.674Z (240 sec) - Android HTC-HTC Desire 820_PT3559 got disconnected

2015-12-04T08:12:15.740Z (288 sec) - Android LGE-Nexus 5_PT5363 got disconnected

2015-12-04T08:13:21.977Z (355 sec) - Android HTC-HTC Desire 820_PT3559 got re-connected event

2015-12-04T08:13:29.177Z (362 sec) - Android motorola-XT1072_PT2491 got re-connected event

2015-12-04T08:13:31.719Z (364 sec) - Android HTC-HTC Desire 820_PT3449 got disconnected

2015-12-04T08:13:36.317Z (369 sec) - Android HTC-HTC Desire 820_PT3449 got re-connected event

2015-12-04T08:13:44.558Z (377 sec) - Android samsung-SM-A300FU_PT476 got disconnected

2015-12-04T08:13:48.106Z (381 sec) - Android motorola-XT1072_PT2491 got disconnected

2015-12-04T08:15:19.153Z (472 sec) - Android motorola-XT1072_PT2491 got disconnected

2015-12-04T08:16:43.250Z (556 sec) - Android samsung-SM-A300FU_PT2828 got disconnected

2015-12-04T08:16:56.282Z (569 sec) - Android HTC-HTC Desire 820_PT3449 got re-connected event

2015-12-04T08:17:12.452Z (585 sec) - Android samsung-SM-G800F_PT4577 got disconnected

2015-12-04T08:17:35.033Z (608 sec) - Android HTC-HTC Desire 820_PT3449 got disconnected

2015-12-04T08:17:41.885Z (614 sec) - Android LGE-Nexus 5_PT5363 got re-connected event

2015-12-04T08:18:13.021Z (646 sec) - Android HTC-HTC Desire 820_PT3559 got re-connected event

2015-12-04T08:18:13.394Z (646 sec) - Android HTC-HTC Desire 820_PT3559 got disconnected

2015-12-04T08:18:26.545Z (659 sec) - Android LGE-LG-D855_PT6390 got disconnected

2015-12-04T08:18:28.987Z (662 sec) - Android LGE-LG-D855_PT6390 got re-connected event

2015-12-04T08:19:24.587Z (717 sec) - Android HTC-HTC Desire 820_PT3559 got re-connected event

2015-12-04T08:19:28.577Z (721 sec) - Android LGE-Nexus 5_PT5363 got re-connected event

2015-12-04T08:19:56.889Z (749 sec) - Android LGE-Nexus 5_PT5363 got disconnected

2015-12-04T08:20:25.586Z (778 sec) - Android samsung-SM-A500FU_PT1688 got disconnected

2015-12-04T08:20:27.982Z (781 sec) - Android HTC-HTC Desire 820_PT3559 got disconnected

2015-12-04T08:21:17.518Z (830 sec) - Android samsung-SM-N910C_PT2368 got disconnected

2015-12-04T08:21:30.131Z (843 sec) - Android LGE-LG-D855_PT6390 got re-connected event

2015-12-04T08:21:35.845Z (848 sec) - Android LGE-Nexus 5_PT5363 got re-connected event

2015-12-04T08:22:24.378Z (897 sec) - Android LGE-LG-D855_PT6390 got disconnected

2015-12-04T08:22:29.119Z (902 sec) - Android LGE-Nexus 5_PT5363 got re-connected event

2015-12-04T08:22:37.032Z (910 sec) - Android LGE-Nexus 5_PT5363 got disconnected

2015-12-04T08:23:25.657Z (958 sec) - Android LGE-Nexus 5_PT5363 got disconnected

2015-12-04T08:23:52.648Z (985 sec) - Android LGE-Nexus 5_PT5363 got re-connected event

2015-12-04T08:24:19.180Z (1012 sec) - Android motorola-XT1039_PT8025 got disconnected

2015-12-04T08:24:19.479Z (1012 sec) - Android LGE-Nexus 5_PT5363 got disconnected

2015-12-04T08:25:09.600Z (1062 sec) - Android HTC-HTC Desire 820_PT3449 got re-connected event

2015-12-04T08:25:42.390Z (1095 sec) - Android LGE-Nexus 5_PT5363 got disconnected

2015-12-04T08:25:57.282Z (1110 sec) - Android HTC-HTC Desire 820_PT3449 got disconnected

2015-12-04T08:26:07.827Z (1120 sec) - Android LGE-Nexus 5_PT5146 test took 1000278ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T08:26:07.927Z (1120 sec) - Android HTC-HTC Desire 820_PT3449 test took 1000373ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T08:26:07.975Z (1121 sec) - Android LGE-LG-D855_PT6390 test took 1000411ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T08:26:08.034Z (1121 sec) - Android samsung-SM-N9005_PT5544 test took 1000480ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T08:26:08.229Z (1121 sec) - Android samsung-SM-G900F_PT807 test took 1000666ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T08:26:08.510Z (1121 sec) - Android LGE-LG-D722_PT9142 test took 1000950ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T08:26:08.951Z (1121 sec) - Android HUAWEI-ALE-L21_PT7753 test took 1001390ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T08:26:09.261Z (1122 sec) - Android samsung-SM-G800H_PT5954 test took 1001709ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T08:26:10.064Z (1123 sec) - Android LGE-LG-H815_PT8707 test took 1002512ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T08:26:11.136Z (1124 sec) - Android samsung-SM-G900F_PT2753 test took 1003576ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T08:26:13.164Z (1126 sec) - Android HTC-HTC Desire 820_PT3559 test took 1005603ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T08:26:13.298Z (1126 sec) - Android LGE-LG-D802_PT5431 test took 1005747ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T08:27:08.309Z (1181 sec) - Android LGE-Nexus 5_PT5363 got re-connected event

2015-12-04T08:27:08.313Z (1181 sec) - Android LGE-Nexus 5_PT5363 test took 1060754ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T08:29:27.568Z (1320 sec) - Server timeout reached!

2015-12-04T08:29:27.569Z (1320 sec) - Send timeout to samsung-SM-N910C_PT2368

2015-12-04T08:29:27.570Z (1320 sec) - Send timeout to samsung-SM-A300FU_PT476

2015-12-04T08:29:27.571Z (1320 sec) - Send timeout to samsung-SM-A500FU_PT1688
2015-12-04T08:29:27.572Z (1320 sec) - Send timeout to samsung-SM-A300FU_PT2828

2015-12-04T08:29:27.573Z (1320 sec) - Send timeout to motorola-Nexus 6_PT8001
2015-12-04T08:29:27.574Z (1320 sec) - Send timeout to motorola-XT1072_PT2491
2015-12-04T08:29:27.575Z (1320 sec) - Send timeout to samsung-SM-G800F_PT4577
2015-12-04T08:29:27.575Z (1320 sec) - Send timeout to motorola-XT1039_PT8025

2015-12-04T08:30:27.578Z (1380 sec) - Did not get reports from all devices, but forcing tests to finish!

samsung-SM-N910C_PT2368 did not have results at the end of tests - check the device logs about why!!

samsung-SM-A300FU_PT476 did not have results at the end of tests - check the device logs about why!!
samsung-SM-A500FU_PT1688 did not have results at the end of tests - check the device logs about why!!
samsung-SM-A300FU_PT2828 did not have results at the end of tests - check the device logs about why!!
motorola-Nexus 6_PT8001 did not have results at the end of tests - check the device logs about why!!
motorola-XT1072_PT2491 did not have results at the end of tests - check the device logs about why!!

samsung-SM-G800F_PT4577 did not have results at the end of tests - check the device logs about why!!

motorola-XT1039_PT8025 did not have results at the end of tests - check the device logs about why!!

2015-12-04T08:30:27.601Z (1380 sec) - Android All tests are done, preparing test report

--------------- test report ---------------------
--------------- LGE-Nexus 5_PT5146 --------------------- : 1

sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 10 [100 %]

- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 38:94:96:B5:06:DC, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1

- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1

sendList never tried peers count : 10 [50 %]
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 58:2A:F7:ED:96:BE

- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 44:80:EB:7B:5A:05

- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : F8:CF:C5:D9:E5:61
- Peer ID : F4:F1:E1:5C:3B:E2
--------------- LGE-LG-D802_PT5431 --------------------- : 2

sendList : 100% : 58234 ms, 99% : 58234 ms, 95 : 58234 ms, 90% : 58234 ms.
Average data rate: 0.004 MB/s
Result count 3, range 10509 ms to  58234 ms.
sendList failed peers count : 9 [75 %]

- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 38:94:96:B5:06:DC, Tried : 1
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1

- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
sendList never tried peers count : 8 [40 %]

- Peer ID : 08:EC:A9:50:75:41
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 44:80:EB:7B:5A:05

- Peer ID : 58:2A:F7:ED:96:BE
- Peer ID : E0:DB:10:1F:C9:5E
--------------- samsung-SM-G800H_PT5954 --------------------- : 3

sendList : 100% : 7140 ms, 99% : 7140 ms, 95 : 7140 ms, 90% : 7140 ms.

Average data rate: 0.014 MB/s
Result count 1, range 7140 ms to  7140 ms.
sendList failed peers count : 9 [90 %]
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1

- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1

- Peer ID : 08:EC:A9:50:75:41, Tried : 1
sendList never tried peers count : 10 [50 %]
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : E0:DB:10:1F:C9:5E

- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : 58:2A:F7:ED:96:BE
- Peer ID : E0:DB:10:14:E2:C0

- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 7C:F9:0E:34:8A:A0
--------------- LGE-LG-H815_PT8707 --------------------- : 4
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s

Results list does not contain any items
sendList failed peers count : 8 [100 %]
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : 38:94:96:B5:06:DC, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1

- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1

sendList never tried peers count : 12 [60 %]
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : B0:C5:59:3F:75:69

- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : 58:2A:F7:ED:96:BE
- Peer ID : F8:95:C7:87:85:54
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 7C:F9:0E:34:8A:A0

- Peer ID : F8:CF:C5:D9:E5:61
- Peer ID : 08:EC:A9:50:76:27
--------------- samsung-SM-N9005_PT5544 --------------------- : 5
sendList : 100% : 6471 ms, 99% : 6471 ms, 95 : 6471 ms, 90% : 6471 ms.

Average data rate: 0.017 MB/s
Result count 2, range 5629 ms to  6471 ms.
sendList failed peers count : 11 [84.61538461538461 %]
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1

- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1

- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
sendList never tried peers count : 7 [35 %]

- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : 38:94:96:B5:06:DC
- Peer ID : 34:FC:EF:11:B1:66

- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 58:2A:F7:ED:96:BE
--------------- HTC-HTC Desire 820_PT3449 --------------------- : 6
sendList : 100% : 25774 ms, 99% : 25774 ms, 95 : 25774 ms, 90% : 25774 ms.

Average data rate: 0.006 MB/s
Result count 2, range 10376 ms to  25774 ms.
sendList failed peers count : 9 [81.81818181818181 %]
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1

- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : 38:94:96:B5:06:DC, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1

- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
sendList never tried peers count : 9 [45 %]
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : 00:F4:6F:30:E0:6C

- Peer ID : B0:C5:59:3F:75:69
- Peer ID : E0:DB:10:1F:C9:5E
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 58:2A:F7:ED:96:BE

- Peer ID : F8:95:C7:87:3C:51
--------------- LGE-Nexus 5_PT5363 --------------------- : 7
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items

sendList failed peers count : 12 [100 %]
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1

- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1

- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
sendList never tried peers count : 8 [40 %]
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : F8:CF:C5:D9:E5:61

- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : E0:DB:10:1F:C9:5E
- Peer ID : 38:94:96:B5:06:DC
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 58:2A:F7:ED:96:BE
--------------- LGE-LG-D722_PT9142 --------------------- : 8
sendList : 100% : 7145 ms, 99% : 7145 ms, 95 : 7145 ms, 90% : 7145 ms.
Average data rate: 0.015 MB/s
Result count 2, range 6463 ms to  7145 ms.
sendList failed peers count : 8 [80 %]
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : 38:94:96:B5:06:DC, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
sendList never tried peers count : 10 [50 %]
- Peer ID : F8:CF:C5:D9:E5:61
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : 58:2A:F7:ED:96:BE
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : E0:DB:10:1F:C9:5E
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 08:EC:A9:50:75:41
--------------- samsung-SM-G900F_PT2753 --------------------- : 9
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 11 [100 %]
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 38:94:96:B5:06:DC, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1

- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
sendList never tried peers count : 9 [45 %]
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : E0:DB:10:1F:C9:5E
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 34:FC:EF:9D:93:0B

- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 58:2A:F7:ED:96:BE
--------------- HTC-HTC Desire 820_PT3559 --------------------- : 10
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.

Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 9 [100 %]
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 38:94:96:B5:06:DC, Tried : 1

- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1

- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
sendList never tried peers count : 11 [55 %]
- Peer ID : E0:DB:10:1F:C9:5E
- Peer ID : 7C:F9:0E:34:8A:A0

- Peer ID : F8:CF:C5:D9:E5:61
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 34:FC:EF:11:AE:67

- Peer ID : F8:95:C7:87:85:54
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : E0:DB:10:14:E2:C0
--------------- HUAWEI-ALE-L21_PT7753 --------------------- : 11

sendList : 100% : 17439 ms, 99% : 17439 ms, 95 : 17439 ms, 90% : 17439 ms.

Average data rate: 0.008 MB/s

Result count 3, range 7437 ms to  17439 ms.
sendList failed peers count : 8 [72.72727272727273 %]
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : 38:94:96:B5:06:DC, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1

- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
sendList never tried peers count : 9 [45 %]

- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 08:EC:A9:50:75:41

- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : F8:95:C7:87:85:54
--------------- samsung-SM-G900F_PT807 --------------------- : 12

sendList : 100% : 37949 ms, 99% : 37949 ms, 95 : 37949 ms, 90% : 37949 ms.
Average data rate: 0.003 MB/s
Result count 1, range 37949 ms to  37949 ms.
sendList failed peers count : 10 [90.9090909090909 %]

- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1

- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
sendList never tried peers count : 9 [45 %]

- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : E0:DB:10:1F:C9:5E

- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 58:2A:F7:ED:96:BE
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 38:94:96:B5:06:DC
--------------- LGE-LG-D855_PT6390 --------------------- : 13

sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 10 [100 %]
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1

- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1

- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
sendList never tried peers count : 10 [50 %]
- Peer ID : 58:2A:F7:ED:96:BE
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 38:94:96:B5:06:DC
--------------- Combined ---------------------
sendList : 100% : 58234 ms, 99% : 58234 ms, 95 : 37949 ms, 90% : 37949 ms.
Average data rate: 0.006 MB/s
--------------- end of test report ---------------------

2015-12-04T08:30:27.945Z (1380 sec) - Android LGE-LG-D722_PT9142 got disconnected

2015-12-04T08:30:28.030Z (1381 sec) - Android LGE-Nexus 5_PT5146 got disconnected

2015-12-04T08:30:28.067Z (1381 sec) - Android LGE-Nexus 5_PT5363 got disconnected

2015-12-04T08:30:28.085Z (1381 sec) - Android samsung-SM-G900F_PT807 got disconnected

2015-12-04T08:30:28.091Z (1381 sec) - Android LGE-LG-D802_PT5431 got disconnected

2015-12-04T08:30:28.120Z (1381 sec) - Android LGE-LG-H815_PT8707 got disconnected

2015-12-04T08:30:28.147Z (1381 sec) - Android samsung-SM-N9005_PT5544 got disconnected

2015-12-04T08:30:28.662Z (1381 sec) - Android samsung-SM-G800H_PT5954 got disconnected

2015-12-04T08:30:29.062Z (1382 sec) - Android HUAWEI-ALE-L21_PT7753 got disconnected

2015-12-04T08:30:29.154Z (1382 sec) - Android samsung-SM-G900F_PT2753 got disconnected

2015-12-04T08:30:29.812Z (1382 sec) - Android HTC-HTC Desire 820_PT3449 got disconnected

2015-12-04T08:30:35.273Z (1388 sec) - Android LGE-LG-D855_PT6390 got disconnected

2015-12-04T08:31:48.505Z (1461 sec) - Android HTC-HTC Desire 820_PT3559 got disconnected


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


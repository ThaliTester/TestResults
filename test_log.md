#### Test 525354860130a71 Logs

Status: 
```

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
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

2015-12-04T08:47:52.262Z (0 sec) - Android tests will start after waiting for 120 seconds

Test ID 0 configuration: testSendData.js, server timeout: 1200000, data:

{ timeout: 1000000,
  rounds: 1,
  dataTimeout: 10000,
  dataAmount: 100000,
  conReTryTimeout: 5000,
  conReTryCount: 5 }

2015-12-04T08:47:52.267Z (0 sec) - iOS tests will start after waiting for 120 seconds

listening on *:3000

2015-12-04T08:47:52.755Z (1 sec) - Android samsung-SM-G900F_PT2104 added (current device count 1)

2015-12-04T08:47:53.193Z (1 sec) - Android samsung-SM-A500FU_PT4244 added (current device count 2)

2015-12-04T08:47:53.436Z (1 sec) - Android LGE-LG-D722_PT5230 added (current device count 3)

2015-12-04T08:47:53.443Z (1 sec) - iOS Apple-IpadAir2-1_PT6975 added (current device count 1)

2015-12-04T08:47:53.780Z (2 sec) - Android motorola-Nexus 6_PT1135 added (current device count 4)

2015-12-04T08:47:53.890Z (2 sec) - Android LGE-LG-H815_PT1124 added (current device count 5)

2015-12-04T08:47:54.208Z (2 sec) - iOS Apple-Iphone5-1_PT9194 added (current device count 2)

2015-12-04T08:47:54.728Z (3 sec) - Android samsung-SM-A300FU_PT7300 added (current device count 6)

2015-12-04T08:47:54.759Z (3 sec) - iOS Apple-Iphone5s-1_PT7213 added (current device count 3)

2015-12-04T08:47:54.784Z (3 sec) - Android LGE-LG-D802_PT3722 added (current device count 7)

2015-12-04T08:47:54.806Z (3 sec) - Android samsung-SM-G900F_PT5092 added (current device count 8)

2015-12-04T08:47:54.910Z (3 sec) - Android samsung-SM-N9005_PT3940 added (current device count 9)

2015-12-04T08:47:55.082Z (3 sec) - Android samsung-SM-N910C_PT2124 added (current device count 10)

2015-12-04T08:47:55.168Z (3 sec) - Android LGE-LG-D855_PT3544 added (current device count 11)

2015-12-04T08:47:55.369Z (3 sec) - Android motorola-XT1039_PT5358 added (current device count 12)

2015-12-04T08:47:55.711Z (3 sec) - Android HUAWEI-ALE-L21_PT4512 added (current device count 13)

2015-12-04T08:47:55.854Z (4 sec) - Android LGE-Nexus 5_PT6585 added (current device count 14)

2015-12-04T08:47:56.359Z (4 sec) - Android HTC-HTC Desire 820_PT6559 added (current device count 15)

2015-12-04T08:47:56.428Z (4 sec) - Android HTC-HTC Desire 820_PT4869 added (current device count 16)

2015-12-04T08:47:56.570Z (4 sec) - Android motorola-XT1072_PT8558 added (current device count 17)

2015-12-04T08:47:56.575Z (4 sec) - iOS Apple-Iphone6-1_PT7135 added (current device count 4)

2015-12-04T08:47:56.598Z (4 sec) - Android samsung-SM-A300FU_PT8263 added (current device count 18)

2015-12-04T08:47:56.655Z (4 sec) - Android samsung-SM-G800H_PT8320 added (current device count 19)

2015-12-04T08:47:57.221Z (5 sec) - Android LGE-Nexus 5_PT74 added (current device count 20)

2015-12-04T08:48:00.379Z (8 sec) - Android samsung-SM-G800F_PT5039 added (current device count 21)

-------------- We got wait done, now starting the testing process ------------------

2015-12-04T08:49:52.313Z (120 sec) - Android start testing now with 21 devices

2015-12-04T08:49:52.339Z (120 sec) - iOS start testing now with 4 devices

2015-12-04T08:51:04.223Z (192 sec) - Android LGE-Nexus 5_PT6585 got re-connected event

2015-12-04T08:51:44.037Z (232 sec) - iOS Apple-Iphone6-1_PT7135 test took 111695ms - results peers[0], reConnects[0], sendData[3]

2015-12-04T08:51:46.187Z (234 sec) - iOS Apple-Iphone5s-1_PT7213 test took 113846ms - results peers[0], reConnects[0], sendData[3]

2015-12-04T08:51:49.853Z (238 sec) - iOS Apple-IpadAir2-1_PT6975 test took 117512ms - results peers[0], reConnects[0], sendData[3]

2015-12-04T08:51:51.433Z (239 sec) - iOS Apple-Iphone5-1_PT9194 test took 119092ms - results peers[0], reConnects[0], sendData[3]

2015-12-04T08:51:51.433Z (239 sec) - iOS test ID 0 done now

2015-12-04T08:51:51.440Z (239 sec) - iOS All tests are done, preparing test report

--------------- test report ---------------------

--------------- Apple-IpadAir2-1_PT6975 --------------------- : 1

sendList : 100% : 5503 ms, 99% : 5503 ms, 95 : 5503 ms, 90% : 5503 ms.

Average data rate: 0.018 MB/s

Result count 2, range 5321 ms to  5503 ms.

sendList failed peers count : 1 [33.333333333333336 %]
- Peer ID : Apple-Iphone5-1_PT9194.4xGkjQ==, Tried : 5

sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5-1_PT9194 --------------------- : 2

sendList : 100% : 3611 ms, 99% : 3611 ms, 95 : 3611 ms, 90% : 3611 ms.
Average data rate: 0.029 MB/s
Result count 2, range 3348 ms to  3611 ms.

sendList failed peers count : 1 [33.333333333333336 %]
- Peer ID : Apple-Iphone5s-1_PT7213.N3FSeg==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5s-1_PT7213 --------------------- : 3
sendList : 100% : 3719 ms, 99% : 3719 ms, 95 : 3719 ms, 90% : 3719 ms.
Average data rate: 0.028 MB/s

Result count 2, range 3355 ms to  3719 ms.
sendList failed peers count : 1 [33.333333333333336 %]
- Peer ID : Apple-Iphone6-1_PT7135.+FivAg==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1_PT7135 --------------------- : 4
sendList : 100% : 3571 ms, 99% : 3571 ms, 95 : 3571 ms, 90% : 3571 ms.
Average data rate: 0.03 MB/s
Result count 2, range 3198 ms to  3571 ms.
sendList failed peers count : 1 [33.333333333333336 %]
- Peer ID : Apple-Iphone5-1_PT9194.4xGkjQ==, Tried : 5

sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------
sendList : 100% : 5503 ms, 99% : 5503 ms, 95 : 5503 ms, 90% : 5321 ms.
Average data rate: 0.025 MB/s

--------------- end of test report ---------------------

2015-12-04T08:51:52.267Z (240 sec) - Android LGE-Nexus 5_PT6585 got disconnected

2015-12-04T08:51:52.553Z (240 sec) - iOS Apple-IpadAir2-1_PT6975 got disconnected

2015-12-04T08:51:52.691Z (240 sec) - iOS Apple-Iphone5s-1_PT7213 got disconnected

2015-12-04T08:51:53.330Z (241 sec) - iOS Apple-Iphone6-1_PT7135 got disconnected

2015-12-04T08:51:53.523Z (241 sec) - iOS Apple-Iphone5-1_PT9194 got disconnected

2015-12-04T08:52:35.964Z (284 sec) - Android motorola-XT1072_PT8558 got disconnected

2015-12-04T08:52:53.846Z (302 sec) - Android LGE-Nexus 5_PT6585 got disconnected

2015-12-04T08:53:36.992Z (345 sec) - Android samsung-SM-G800F_PT5039 got disconnected

2015-12-04T08:54:03.580Z (371 sec) - Android LGE-Nexus 5_PT6585 got re-connected event

2015-12-04T08:55:13.984Z (442 sec) - Android HTC-HTC Desire 820_PT6559 got disconnected

2015-12-04T08:56:10.511Z (498 sec) - Android LGE-Nexus 5_PT6585 got re-connected event

2015-12-04T08:56:43.642Z (531 sec) - Android LGE-Nexus 5_PT6585 got disconnected

2015-12-04T08:56:55.952Z (544 sec) - Android HTC-HTC Desire 820_PT4869 got disconnected

2015-12-04T08:57:41.153Z (589 sec) - Android motorola-XT1039_PT5358 got disconnected

2015-12-04T08:58:00.454Z (608 sec) - Android LGE-Nexus 5_PT6585 got disconnected

2015-12-04T08:58:00.839Z (609 sec) - Android LGE-LG-D855_PT3544 got disconnected

2015-12-04T08:58:42.393Z (650 sec) - Android motorola-XT1039_PT5358 got re-connected event

2015-12-04T08:59:13.395Z (681 sec) - Android LGE-Nexus 5_PT6585 got re-connected event

2015-12-04T08:59:43.609Z (711 sec) - Android samsung-SM-A300FU_PT8263 got disconnected

2015-12-04T09:00:35.231Z (763 sec) - Android motorola-XT1039_PT5358 got disconnected

2015-12-04T09:00:41.766Z (770 sec) - Android motorola-Nexus 6_PT1135 got re-connected event

2015-12-04T09:01:50.497Z (838 sec) - Android motorola-Nexus 6_PT1135 got disconnected

2015-12-04T09:02:19.054Z (867 sec) - Android LGE-Nexus 5_PT6585 got disconnected

2015-12-04T09:02:24.785Z (873 sec) - Android motorola-XT1039_PT5358 got re-connected event

2015-12-04T09:02:43.439Z (891 sec) - Android samsung-SM-N910C_PT2124 got disconnected

2015-12-04T09:02:47.922Z (896 sec) - Android LGE-Nexus 5_PT6585 got re-connected event

2015-12-04T09:03:49.868Z (958 sec) - Android motorola-Nexus 6_PT1135 got re-connected event

2015-12-04T09:05:02.369Z (1030 sec) - Android motorola-Nexus 6_PT1135 got disconnected

2015-12-04T09:05:15.295Z (1043 sec) - Android motorola-XT1039_PT5358 got re-connected event

2015-12-04T09:05:18.157Z (1046 sec) - Android motorola-XT1039_PT5358 got disconnected

2015-12-04T09:05:33.898Z (1062 sec) - Android LGE-Nexus 5_PT6585 got re-connected event

2015-12-04T09:05:44.334Z (1072 sec) - Android LGE-LG-H815_PT1124 got disconnected

2015-12-04T09:05:53.793Z (1082 sec) - Android LGE-Nexus 5_PT6585 got disconnected

2015-12-04T09:06:14.564Z (1102 sec) - Android samsung-SM-A300FU_PT7300 got disconnected

2015-12-04T09:06:32.567Z (1120 sec) - Android motorola-Nexus 6_PT1135 test took 1000244ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T09:06:32.697Z (1120 sec) - Android LGE-Nexus 5_PT74 test took 1000363ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T09:06:32.752Z (1121 sec) - Android samsung-SM-N9005_PT3940 test took 1000425ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T09:06:32.832Z (1121 sec) - Android samsung-SM-A500FU_PT4244 test took 1000512ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T09:06:32.877Z (1121 sec) - Android motorola-XT1039_PT5358 test took 1000548ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T09:06:33.283Z (1121 sec) - Android LGE-LG-D802_PT3722 test took 1000959ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T09:06:33.833Z (1122 sec) - Android HUAWEI-ALE-L21_PT4512 test took 1001504ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T09:06:34.059Z (1122 sec) - Android samsung-SM-G900F_PT2104 test took 1001741ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T09:06:34.171Z (1122 sec) - Android LGE-LG-D722_PT5230 test took 1001849ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T09:06:35.075Z (1123 sec) - Android samsung-SM-G800H_PT8320 test took 1002742ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T09:06:35.464Z (1123 sec) - Android samsung-SM-G900F_PT5092 test took 1003137ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T09:06:58.901Z (1147 sec) - Android LGE-Nexus 5_PT6585 got disconnected

2015-12-04T09:08:00.430Z (1208 sec) - Android LGE-Nexus 5_PT6585 got re-connected event

2015-12-04T09:08:00.434Z (1208 sec) - Android LGE-Nexus 5_PT6585 test took 1088103ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T09:09:52.336Z (1320 sec) - Server timeout reached!

2015-12-04T09:09:52.337Z (1320 sec) - Send timeout to LGE-LG-H815_PT1124
2015-12-04T09:09:52.338Z (1320 sec) - Send timeout to samsung-SM-A300FU_PT7300

2015-12-04T09:09:52.339Z (1320 sec) - Send timeout to samsung-SM-N910C_PT2124

2015-12-04T09:09:52.339Z (1320 sec) - Send timeout to LGE-LG-D855_PT3544
2015-12-04T09:09:52.340Z (1320 sec) - Send timeout to HTC-HTC Desire 820_PT6559

2015-12-04T09:09:52.341Z (1320 sec) - Send timeout to HTC-HTC Desire 820_PT4869

2015-12-04T09:09:52.342Z (1320 sec) - Send timeout to motorola-XT1072_PT8558
2015-12-04T09:09:52.343Z (1320 sec) - Send timeout to samsung-SM-A300FU_PT8263

2015-12-04T09:09:52.343Z (1320 sec) - Send timeout to samsung-SM-G800F_PT5039

2015-12-04T09:10:52.347Z (1380 sec) - Did not get reports from all devices, but forcing tests to finish!

LGE-LG-H815_PT1124 did not have results at the end of tests - check the device logs about why!!

samsung-SM-A300FU_PT7300 did not have results at the end of tests - check the device logs about why!!

samsung-SM-N910C_PT2124 did not have results at the end of tests - check the device logs about why!!

LGE-LG-D855_PT3544 did not have results at the end of tests - check the device logs about why!!

HTC-HTC Desire 820_PT6559 did not have results at the end of tests - check the device logs about why!!

HTC-HTC Desire 820_PT4869 did not have results at the end of tests - check the device logs about why!!
motorola-XT1072_PT8558 did not have results at the end of tests - check the device logs about why!!
samsung-SM-A300FU_PT8263 did not have results at the end of tests - check the device logs about why!!
samsung-SM-G800F_PT5039 did not have results at the end of tests - check the device logs about why!!

2015-12-04T09:10:52.369Z (1380 sec) - Android All tests are done, preparing test report
--------------- test report ---------------------
--------------- samsung-SM-G900F_PT2104 --------------------- : 1
sendList : 100% : 19693 ms, 99% : 19693 ms, 95 : 19693 ms, 90% : 19693 ms.
Average data rate: 0.005 MB/s
Result count 1, range 19693 ms to  19693 ms.
sendList failed peers count : 9 [90 %]
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 38:94:96:B5:06:DC, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
sendList never tried peers count : 10 [50 %]
- Peer ID : F8:95:C7:87:85:54
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : E0:DB:10:1F:C9:5E
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 58:2A:F7:ED:96:BE
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 00:F4:6F:30:E0:6C
--------------- samsung-SM-A500FU_PT4244 --------------------- : 2
sendList : 100% : 36501 ms, 99% : 36501 ms, 95 : 36501 ms, 90% : 36501 ms.
Average data rate: 0.003 MB/s

Result count 1, range 36501 ms to  36501 ms.
sendList failed peers count : 8 [88.88888888888889 %]
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 38:94:96:B5:06:DC, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1

- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
sendList never tried peers count : 11 [55 %]
- Peer ID : 58:2A:F7:ED:96:BE

- Peer ID : 80:01:84:8A:B3:68
- Peer ID : F8:CF:C5:D9:E5:61
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : B4:CE:F6:AB:A4:6A

- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : F4:F1:E1:5C:3B:E2
--------------- LGE-LG-D722_PT5230 --------------------- : 3
sendList : 100% : 6850 ms, 99% : 6850 ms, 95 : 6850 ms, 90% : 6850 ms.
Average data rate: 0.015 MB/s
Result count 1, range 6850 ms to  6850 ms.
sendList failed peers count : 11 [91.66666666666667 %]
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1

- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1

sendList never tried peers count : 8 [40 %]
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : F8:CF:C5:D9:E5:61
- Peer ID : 38:94:96:B5:06:DC

- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 00:F4:6F:30:E0:6C

- Peer ID : B4:CE:F6:AB:A4:6A
--------------- motorola-Nexus 6_PT1135 --------------------- : 4

sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items

sendList failed peers count : 11 [100 %]
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1

- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1

- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1

- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
sendList never tried peers count : 9 [45 %]
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 7C:F9:0E:34:8A:A0

- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 08:EC:A9:50:75:41

- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 38:94:96:B5:06:DC
--------------- LGE-LG-D802_PT3722 --------------------- : 5
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 7 [100 %]
- Peer ID : 38:94:96:B5:06:DC, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
sendList never tried peers count : 13 [65 %]
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : E0:DB:10:1F:C9:5E
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 58:2A:F7:ED:96:BE
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : B0:C5:59:3F:75:69
--------------- samsung-SM-G900F_PT5092 --------------------- : 6
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 9 [100 %]
- Peer ID : 38:94:96:B5:06:DC, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1

- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
sendList never tried peers count : 11 [55 %]

- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : E0:DB:10:14:E2:C0

- Peer ID : 08:EC:A9:50:75:41
- Peer ID : E0:DB:10:1F:C9:5E
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : 58:2A:F7:ED:96:BE

- Peer ID : F8:95:C7:87:3C:51
- Peer ID : F8:CF:C5:D9:E5:61
- Peer ID : 58:3F:54:73:64:C0

--------------- samsung-SM-N9005_PT3940 --------------------- : 7
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s

Results list does not contain any items
sendList failed peers count : 9 [100 %]
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1

- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1

- Peer ID : E0:DB:10:14:E2:C0, Tried : 1

- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
sendList never tried peers count : 11 [55 %]
- Peer ID : F8:95:C7:87:3C:51

- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 38:94:96:B5:06:DC
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : B0:C5:59:3F:75:69

- Peer ID : 58:2A:F7:ED:96:BE
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 00:F4:6F:30:E0:6C

- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : F8:CF:C5:D9:E5:61
--------------- motorola-XT1039_PT5358 --------------------- : 8

sendList : 100% : 16352 ms, 99% : 16352 ms, 95 : 16352 ms, 90% : 16352 ms.
Average data rate: 0.009 MB/s
Result count 3, range 6199 ms to  16352 ms.

sendList failed peers count : 10 [76.92307692307692 %]
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1

- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1

- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 38:94:96:B5:06:DC, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
sendList never tried peers count : 7 [35 %]

- Peer ID : 80:01:84:8A:B3:68
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 34:FC:EF:11:B1:66

- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : B4:CE:F6:AB:A4:6A
--------------- HUAWEI-ALE-L21_PT4512 --------------------- : 9

sendList : 100% : 34440 ms, 99% : 34440 ms, 95 : 34440 ms, 90% : 34440 ms.
Average data rate: 0.003 MB/s
Result count 1, range 34440 ms to  34440 ms.

sendList failed peers count : 19 [95 %]
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1

- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1

- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : 38:94:96:B5:06:DC, Tried : 1

- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
sendList never tried peers count : 0 [0 %]
--------------- LGE-Nexus 5_PT6585 --------------------- : 10
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 11 [100 %]
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
sendList never tried peers count : 9 [45 %]
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : F8:95:C7:87:85:54
- Peer ID : F8:CF:C5:D9:E5:61
- Peer ID : F8:95:C7:87:3C:51

- Peer ID : 38:94:96:B5:06:DC
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : B0:C5:59:3F:75:69

- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : F4:F1:E1:5C:3B:E2
--------------- samsung-SM-G800H_PT8320 --------------------- : 11

sendList : 100% : 9063 ms, 99% : 9063 ms, 95 : 9063 ms, 90% : 9063 ms.
Average data rate: 0.018 MB/s
Result count 3, range 3078 ms to  9063 ms.

sendList failed peers count : 8 [72.72727272727273 %]
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1

- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1

- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
sendList never tried peers count : 9 [45 %]
- Peer ID : E0:DB:10:14:E2:C0

- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : F8:95:C7:87:85:54
- Peer ID : B0:C5:59:3F:75:69

- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 08:EC:A9:50:75:41

- Peer ID : F8:CF:C5:D9:E5:61
--------------- LGE-Nexus 5_PT74 --------------------- : 12
sendList : 100% : 18096 ms, 99% : 18096 ms, 95 : 18096 ms, 90% : 18096 ms.

Average data rate: 0.008 MB/s
Result count 2, range 8124 ms to  18096 ms.
sendList failed peers count : 9 [81.81818181818181 %]
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1

- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1

- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1

- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
sendList never tried peers count : 9 [45 %]
- Peer ID : F8:95:C7:87:85:54
- Peer ID : 08:EC:A9:50:75:41

- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : B0:C5:59:3F:75:69

- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : F4:F1:E1:5C:3B:E2

--------------- Combined ---------------------

sendList : 100% : 36501 ms, 99% : 36501 ms, 95 : 34440 ms, 90% : 34440 ms.
Average data rate: 0.007 MB/s
--------------- end of test report ---------------------

2015-12-04T09:10:52.720Z (1380 sec) - Android HUAWEI-ALE-L21_PT4512 got disconnected

2015-12-04T09:10:52.726Z (1381 sec) - Android motorola-Nexus 6_PT1135 got disconnected

2015-12-04T09:10:52.778Z (1381 sec) - Android samsung-SM-G900F_PT5092 got disconnected

2015-12-04T09:10:52.882Z (1381 sec) - Android LGE-LG-D802_PT3722 got disconnected

2015-12-04T09:10:52.984Z (1381 sec) - Android samsung-SM-A500FU_PT4244 got disconnected

2015-12-04T09:10:53.060Z (1381 sec) - Android LGE-Nexus 5_PT74 got disconnected

2015-12-04T09:10:53.110Z (1381 sec) - Android LGE-LG-D722_PT5230 got disconnected

2015-12-04T09:10:53.425Z (1381 sec) - Android samsung-SM-G900F_PT2104 got disconnected

2015-12-04T09:11:52.857Z (1441 sec) - Android samsung-SM-N9005_PT3940 got disconnected

2015-12-04T09:11:56.039Z (1444 sec) - Android LGE-Nexus 5_PT6585 got disconnected

2015-12-04T09:12:08.481Z (1456 sec) - Android motorola-XT1039_PT5358 got disconnected

2015-12-04T09:12:08.900Z (1457 sec) - Android samsung-SM-G800H_PT8320 got disconnected


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```
###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/525354860130a71_Require_newer_Cordova_versions__vjrantal/iOS_Iphone5-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/525354860130a71_Require_newer_Cordova_versions__vjrantal/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/525354860130a71_Require_newer_Cordova_versions__vjrantal/iOS_Iphone6-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/525354860130a71_Require_newer_Cordova_versions__vjrantal/iOS_IpadAir2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/525354860130a71_Require_newer_Cordova_versions__vjrantal/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  W3D7N15428022572 Test has  SUCCEEDED
STOP log received from  f56ad48d Test has  SUCCEEDED
Device test finished on f56ad48d 
Device test finished on W3D7N15428022572 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:0 
child process exited with code 0 on device LGH8153b36be34 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/525354860130a71_Require_newer_Cordova_versions__vjrantal/thali01_LGE-LG-H815.md)

[HUAWEI-ALE-L21](https://github.com/ThaliTester/TestResults/blob/525354860130a71_Require_newer_Cordova_versions__vjrantal/thali01_HUAWEI-ALE-L21.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/525354860130a71_Require_newer_Cordova_versions__vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/525354860130a71_Require_newer_Cordova_versions__vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/525354860130a71_Require_newer_Cordova_versions__vjrantal/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/525354860130a71_Require_newer_Cordova_versions__vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/525354860130a71_Require_newer_Cordova_versions__vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/525354860130a71_Require_newer_Cordova_versions__vjrantal/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/525354860130a71_Require_newer_Cordova_versions__vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/525354860130a71_Require_newer_Cordova_versions__vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/525354860130a71_Require_newer_Cordova_versions__vjrantal/thali04_samsung-SM-G900F.md)

####Node name: thali05
Console output:
```
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
STOP log received from  1d6a772d Test has  SUCCEEDED
Device test finished on 1d6a772d 
STOP log received from  954a12ed Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
Device test finished on 954a12ed 
Android task is completed. [SUCCESS]
```
[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/525354860130a71_Require_newer_Cordova_versions__vjrantal/thali05_samsung-SM-N9005.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/525354860130a71_Require_newer_Cordova_versions__vjrantal/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/525354860130a71_Require_newer_Cordova_versions__vjrantal/thali05_samsung-SM-G800H.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/525354860130a71_Require_newer_Cordova_versions__vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/525354860130a71_Require_newer_Cordova_versions__vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/525354860130a71_Require_newer_Cordova_versions__vjrantal/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/525354860130a71_Require_newer_Cordova_versions__vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/525354860130a71_Require_newer_Cordova_versions__vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device HT574YC04723 app:com.test.thalitest code:null 
child process exited with code null on device HT574YC04723 
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:null 
child process exited with code null on device 4325e43f 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/525354860130a71_Require_newer_Cordova_versions__vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/525354860130a71_Require_newer_Cordova_versions__vjrantal/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
Device test finished on 0c6a0f3c0bdb4e77 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device CC51WYC03425 app:com.test.thalitest code:0 
child process exited with code 0 on device CC51WYC03425 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/525354860130a71_Require_newer_Cordova_versions__vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/525354860130a71_Require_newer_Cordova_versions__vjrantal/thali09_LGE-Nexus 5.md)




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

2015-12-04T08:47:52.262Z (0 sec) - Android tests will start after waiting for 120 seconds

Test ID 0 configuration: testSendData.js, server timeout: 1200000, data:

{ timeout: 1000000,
  rounds: 1,
  dataTimeout: 10000,
  dataAmount: 100000,
  conReTryTimeout: 5000,
  conReTryCount: 5 }

2015-12-04T08:47:52.267Z (0 sec) - iOS tests will start after waiting for 120 seconds

listening on *:3000

2015-12-04T08:47:52.755Z (1 sec) - Android samsung-SM-G900F_PT2104 added (current device count 1)

2015-12-04T08:47:53.193Z (1 sec) - Android samsung-SM-A500FU_PT4244 added (current device count 2)

2015-12-04T08:47:53.436Z (1 sec) - Android LGE-LG-D722_PT5230 added (current device count 3)

2015-12-04T08:47:53.443Z (1 sec) - iOS Apple-IpadAir2-1_PT6975 added (current device count 1)

2015-12-04T08:47:53.780Z (2 sec) - Android motorola-Nexus 6_PT1135 added (current device count 4)

2015-12-04T08:47:53.890Z (2 sec) - Android LGE-LG-H815_PT1124 added (current device count 5)

2015-12-04T08:47:54.208Z (2 sec) - iOS Apple-Iphone5-1_PT9194 added (current device count 2)

2015-12-04T08:47:54.728Z (3 sec) - Android samsung-SM-A300FU_PT7300 added (current device count 6)

2015-12-04T08:47:54.759Z (3 sec) - iOS Apple-Iphone5s-1_PT7213 added (current device count 3)

2015-12-04T08:47:54.784Z (3 sec) - Android LGE-LG-D802_PT3722 added (current device count 7)

2015-12-04T08:47:54.806Z (3 sec) - Android samsung-SM-G900F_PT5092 added (current device count 8)

2015-12-04T08:47:54.910Z (3 sec) - Android samsung-SM-N9005_PT3940 added (current device count 9)

2015-12-04T08:47:55.082Z (3 sec) - Android samsung-SM-N910C_PT2124 added (current device count 10)

2015-12-04T08:47:55.168Z (3 sec) - Android LGE-LG-D855_PT3544 added (current device count 11)

2015-12-04T08:47:55.369Z (3 sec) - Android motorola-XT1039_PT5358 added (current device count 12)

2015-12-04T08:47:55.711Z (3 sec) - Android HUAWEI-ALE-L21_PT4512 added (current device count 13)

2015-12-04T08:47:55.854Z (4 sec) - Android LGE-Nexus 5_PT6585 added (current device count 14)

2015-12-04T08:47:56.359Z (4 sec) - Android HTC-HTC Desire 820_PT6559 added (current device count 15)

2015-12-04T08:47:56.428Z (4 sec) - Android HTC-HTC Desire 820_PT4869 added (current device count 16)

2015-12-04T08:47:56.570Z (4 sec) - Android motorola-XT1072_PT8558 added (current device count 17)

2015-12-04T08:47:56.575Z (4 sec) - iOS Apple-Iphone6-1_PT7135 added (current device count 4)

2015-12-04T08:47:56.598Z (4 sec) - Android samsung-SM-A300FU_PT8263 added (current device count 18)

2015-12-04T08:47:56.655Z (4 sec) - Android samsung-SM-G800H_PT8320 added (current device count 19)

2015-12-04T08:47:57.221Z (5 sec) - Android LGE-Nexus 5_PT74 added (current device count 20)

2015-12-04T08:48:00.379Z (8 sec) - Android samsung-SM-G800F_PT5039 added (current device count 21)

-------------- We got wait done, now starting the testing process ------------------

2015-12-04T08:49:52.313Z (120 sec) - Android start testing now with 21 devices

2015-12-04T08:49:52.339Z (120 sec) - iOS start testing now with 4 devices

2015-12-04T08:51:04.223Z (192 sec) - Android LGE-Nexus 5_PT6585 got re-connected event

2015-12-04T08:51:44.037Z (232 sec) - iOS Apple-Iphone6-1_PT7135 test took 111695ms - results peers[0], reConnects[0], sendData[3]

2015-12-04T08:51:46.187Z (234 sec) - iOS Apple-Iphone5s-1_PT7213 test took 113846ms - results peers[0], reConnects[0], sendData[3]

2015-12-04T08:51:49.853Z (238 sec) - iOS Apple-IpadAir2-1_PT6975 test took 117512ms - results peers[0], reConnects[0], sendData[3]

2015-12-04T08:51:51.433Z (239 sec) - iOS Apple-Iphone5-1_PT9194 test took 119092ms - results peers[0], reConnects[0], sendData[3]

2015-12-04T08:51:51.433Z (239 sec) - iOS test ID 0 done now

2015-12-04T08:51:51.440Z (239 sec) - iOS All tests are done, preparing test report

--------------- test report ---------------------

--------------- Apple-IpadAir2-1_PT6975 --------------------- : 1

sendList : 100% : 5503 ms, 99% : 5503 ms, 95 : 5503 ms, 90% : 5503 ms.

Average data rate: 0.018 MB/s

Result count 2, range 5321 ms to  5503 ms.

sendList failed peers count : 1 [33.333333333333336 %]
- Peer ID : Apple-Iphone5-1_PT9194.4xGkjQ==, Tried : 5

sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5-1_PT9194 --------------------- : 2

sendList : 100% : 3611 ms, 99% : 3611 ms, 95 : 3611 ms, 90% : 3611 ms.
Average data rate: 0.029 MB/s
Result count 2, range 3348 ms to  3611 ms.

sendList failed peers count : 1 [33.333333333333336 %]
- Peer ID : Apple-Iphone5s-1_PT7213.N3FSeg==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5s-1_PT7213 --------------------- : 3
sendList : 100% : 3719 ms, 99% : 3719 ms, 95 : 3719 ms, 90% : 3719 ms.
Average data rate: 0.028 MB/s

Result count 2, range 3355 ms to  3719 ms.
sendList failed peers count : 1 [33.333333333333336 %]
- Peer ID : Apple-Iphone6-1_PT7135.+FivAg==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1_PT7135 --------------------- : 4
sendList : 100% : 3571 ms, 99% : 3571 ms, 95 : 3571 ms, 90% : 3571 ms.
Average data rate: 0.03 MB/s
Result count 2, range 3198 ms to  3571 ms.
sendList failed peers count : 1 [33.333333333333336 %]
- Peer ID : Apple-Iphone5-1_PT9194.4xGkjQ==, Tried : 5

sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------
sendList : 100% : 5503 ms, 99% : 5503 ms, 95 : 5503 ms, 90% : 5321 ms.
Average data rate: 0.025 MB/s

--------------- end of test report ---------------------

2015-12-04T08:51:52.267Z (240 sec) - Android LGE-Nexus 5_PT6585 got disconnected

2015-12-04T08:51:52.553Z (240 sec) - iOS Apple-IpadAir2-1_PT6975 got disconnected

2015-12-04T08:51:52.691Z (240 sec) - iOS Apple-Iphone5s-1_PT7213 got disconnected

2015-12-04T08:51:53.330Z (241 sec) - iOS Apple-Iphone6-1_PT7135 got disconnected

2015-12-04T08:51:53.523Z (241 sec) - iOS Apple-Iphone5-1_PT9194 got disconnected

2015-12-04T08:52:35.964Z (284 sec) - Android motorola-XT1072_PT8558 got disconnected

2015-12-04T08:52:53.846Z (302 sec) - Android LGE-Nexus 5_PT6585 got disconnected

2015-12-04T08:53:36.992Z (345 sec) - Android samsung-SM-G800F_PT5039 got disconnected

2015-12-04T08:54:03.580Z (371 sec) - Android LGE-Nexus 5_PT6585 got re-connected event

2015-12-04T08:55:13.984Z (442 sec) - Android HTC-HTC Desire 820_PT6559 got disconnected

2015-12-04T08:56:10.511Z (498 sec) - Android LGE-Nexus 5_PT6585 got re-connected event

2015-12-04T08:56:43.642Z (531 sec) - Android LGE-Nexus 5_PT6585 got disconnected

2015-12-04T08:56:55.952Z (544 sec) - Android HTC-HTC Desire 820_PT4869 got disconnected

2015-12-04T08:57:41.153Z (589 sec) - Android motorola-XT1039_PT5358 got disconnected

2015-12-04T08:58:00.454Z (608 sec) - Android LGE-Nexus 5_PT6585 got disconnected

2015-12-04T08:58:00.839Z (609 sec) - Android LGE-LG-D855_PT3544 got disconnected

2015-12-04T08:58:42.393Z (650 sec) - Android motorola-XT1039_PT5358 got re-connected event

2015-12-04T08:59:13.395Z (681 sec) - Android LGE-Nexus 5_PT6585 got re-connected event

2015-12-04T08:59:43.609Z (711 sec) - Android samsung-SM-A300FU_PT8263 got disconnected

2015-12-04T09:00:35.231Z (763 sec) - Android motorola-XT1039_PT5358 got disconnected

2015-12-04T09:00:41.766Z (770 sec) - Android motorola-Nexus 6_PT1135 got re-connected event

2015-12-04T09:01:50.497Z (838 sec) - Android motorola-Nexus 6_PT1135 got disconnected

2015-12-04T09:02:19.054Z (867 sec) - Android LGE-Nexus 5_PT6585 got disconnected

2015-12-04T09:02:24.785Z (873 sec) - Android motorola-XT1039_PT5358 got re-connected event

2015-12-04T09:02:43.439Z (891 sec) - Android samsung-SM-N910C_PT2124 got disconnected

2015-12-04T09:02:47.922Z (896 sec) - Android LGE-Nexus 5_PT6585 got re-connected event

2015-12-04T09:03:49.868Z (958 sec) - Android motorola-Nexus 6_PT1135 got re-connected event

2015-12-04T09:05:02.369Z (1030 sec) - Android motorola-Nexus 6_PT1135 got disconnected

2015-12-04T09:05:15.295Z (1043 sec) - Android motorola-XT1039_PT5358 got re-connected event

2015-12-04T09:05:18.157Z (1046 sec) - Android motorola-XT1039_PT5358 got disconnected

2015-12-04T09:05:33.898Z (1062 sec) - Android LGE-Nexus 5_PT6585 got re-connected event

2015-12-04T09:05:44.334Z (1072 sec) - Android LGE-LG-H815_PT1124 got disconnected

2015-12-04T09:05:53.793Z (1082 sec) - Android LGE-Nexus 5_PT6585 got disconnected

2015-12-04T09:06:14.564Z (1102 sec) - Android samsung-SM-A300FU_PT7300 got disconnected

2015-12-04T09:06:32.567Z (1120 sec) - Android motorola-Nexus 6_PT1135 test took 1000244ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T09:06:32.697Z (1120 sec) - Android LGE-Nexus 5_PT74 test took 1000363ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T09:06:32.752Z (1121 sec) - Android samsung-SM-N9005_PT3940 test took 1000425ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T09:06:32.832Z (1121 sec) - Android samsung-SM-A500FU_PT4244 test took 1000512ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T09:06:32.877Z (1121 sec) - Android motorola-XT1039_PT5358 test took 1000548ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T09:06:33.283Z (1121 sec) - Android LGE-LG-D802_PT3722 test took 1000959ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T09:06:33.833Z (1122 sec) - Android HUAWEI-ALE-L21_PT4512 test took 1001504ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T09:06:34.059Z (1122 sec) - Android samsung-SM-G900F_PT2104 test took 1001741ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T09:06:34.171Z (1122 sec) - Android LGE-LG-D722_PT5230 test took 1001849ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T09:06:35.075Z (1123 sec) - Android samsung-SM-G800H_PT8320 test took 1002742ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T09:06:35.464Z (1123 sec) - Android samsung-SM-G900F_PT5092 test took 1003137ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T09:06:58.901Z (1147 sec) - Android LGE-Nexus 5_PT6585 got disconnected

2015-12-04T09:08:00.430Z (1208 sec) - Android LGE-Nexus 5_PT6585 got re-connected event

2015-12-04T09:08:00.434Z (1208 sec) - Android LGE-Nexus 5_PT6585 test took 1088103ms - results peers[0], reConnects[0], sendData[20]

2015-12-04T09:09:52.336Z (1320 sec) - Server timeout reached!

2015-12-04T09:09:52.337Z (1320 sec) - Send timeout to LGE-LG-H815_PT1124
2015-12-04T09:09:52.338Z (1320 sec) - Send timeout to samsung-SM-A300FU_PT7300

2015-12-04T09:09:52.339Z (1320 sec) - Send timeout to samsung-SM-N910C_PT2124

2015-12-04T09:09:52.339Z (1320 sec) - Send timeout to LGE-LG-D855_PT3544
2015-12-04T09:09:52.340Z (1320 sec) - Send timeout to HTC-HTC Desire 820_PT6559

2015-12-04T09:09:52.341Z (1320 sec) - Send timeout to HTC-HTC Desire 820_PT4869

2015-12-04T09:09:52.342Z (1320 sec) - Send timeout to motorola-XT1072_PT8558
2015-12-04T09:09:52.343Z (1320 sec) - Send timeout to samsung-SM-A300FU_PT8263

2015-12-04T09:09:52.343Z (1320 sec) - Send timeout to samsung-SM-G800F_PT5039

2015-12-04T09:10:52.347Z (1380 sec) - Did not get reports from all devices, but forcing tests to finish!

LGE-LG-H815_PT1124 did not have results at the end of tests - check the device logs about why!!

samsung-SM-A300FU_PT7300 did not have results at the end of tests - check the device logs about why!!

samsung-SM-N910C_PT2124 did not have results at the end of tests - check the device logs about why!!

LGE-LG-D855_PT3544 did not have results at the end of tests - check the device logs about why!!

HTC-HTC Desire 820_PT6559 did not have results at the end of tests - check the device logs about why!!

HTC-HTC Desire 820_PT4869 did not have results at the end of tests - check the device logs about why!!
motorola-XT1072_PT8558 did not have results at the end of tests - check the device logs about why!!
samsung-SM-A300FU_PT8263 did not have results at the end of tests - check the device logs about why!!
samsung-SM-G800F_PT5039 did not have results at the end of tests - check the device logs about why!!

2015-12-04T09:10:52.369Z (1380 sec) - Android All tests are done, preparing test report
--------------- test report ---------------------
--------------- samsung-SM-G900F_PT2104 --------------------- : 1
sendList : 100% : 19693 ms, 99% : 19693 ms, 95 : 19693 ms, 90% : 19693 ms.
Average data rate: 0.005 MB/s
Result count 1, range 19693 ms to  19693 ms.
sendList failed peers count : 9 [90 %]
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 38:94:96:B5:06:DC, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
sendList never tried peers count : 10 [50 %]
- Peer ID : F8:95:C7:87:85:54
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : E0:DB:10:1F:C9:5E
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 58:2A:F7:ED:96:BE
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 00:F4:6F:30:E0:6C
--------------- samsung-SM-A500FU_PT4244 --------------------- : 2
sendList : 100% : 36501 ms, 99% : 36501 ms, 95 : 36501 ms, 90% : 36501 ms.
Average data rate: 0.003 MB/s

Result count 1, range 36501 ms to  36501 ms.
sendList failed peers count : 8 [88.88888888888889 %]
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 38:94:96:B5:06:DC, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1

- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
sendList never tried peers count : 11 [55 %]
- Peer ID : 58:2A:F7:ED:96:BE

- Peer ID : 80:01:84:8A:B3:68
- Peer ID : F8:CF:C5:D9:E5:61
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : B4:CE:F6:AB:A4:6A

- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : F4:F1:E1:5C:3B:E2
--------------- LGE-LG-D722_PT5230 --------------------- : 3
sendList : 100% : 6850 ms, 99% : 6850 ms, 95 : 6850 ms, 90% : 6850 ms.
Average data rate: 0.015 MB/s
Result count 1, range 6850 ms to  6850 ms.
sendList failed peers count : 11 [91.66666666666667 %]
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1

- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1

sendList never tried peers count : 8 [40 %]
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : F8:CF:C5:D9:E5:61
- Peer ID : 38:94:96:B5:06:DC

- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 00:F4:6F:30:E0:6C

- Peer ID : B4:CE:F6:AB:A4:6A
--------------- motorola-Nexus 6_PT1135 --------------------- : 4

sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items

sendList failed peers count : 11 [100 %]
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1

- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1

- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1

- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
sendList never tried peers count : 9 [45 %]
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 7C:F9:0E:34:8A:A0

- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 08:EC:A9:50:75:41

- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 38:94:96:B5:06:DC
--------------- LGE-LG-D802_PT3722 --------------------- : 5
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 7 [100 %]
- Peer ID : 38:94:96:B5:06:DC, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
sendList never tried peers count : 13 [65 %]
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : E0:DB:10:1F:C9:5E
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 58:2A:F7:ED:96:BE
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : B0:C5:59:3F:75:69
--------------- samsung-SM-G900F_PT5092 --------------------- : 6
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 9 [100 %]
- Peer ID : 38:94:96:B5:06:DC, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1

- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
sendList never tried peers count : 11 [55 %]

- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : E0:DB:10:14:E2:C0

- Peer ID : 08:EC:A9:50:75:41
- Peer ID : E0:DB:10:1F:C9:5E
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : 58:2A:F7:ED:96:BE

- Peer ID : F8:95:C7:87:3C:51
- Peer ID : F8:CF:C5:D9:E5:61
- Peer ID : 58:3F:54:73:64:C0

--------------- samsung-SM-N9005_PT3940 --------------------- : 7
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s

Results list does not contain any items
sendList failed peers count : 9 [100 %]
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1

- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1

- Peer ID : E0:DB:10:14:E2:C0, Tried : 1

- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
sendList never tried peers count : 11 [55 %]
- Peer ID : F8:95:C7:87:3C:51

- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 38:94:96:B5:06:DC
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : B0:C5:59:3F:75:69

- Peer ID : 58:2A:F7:ED:96:BE
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 00:F4:6F:30:E0:6C

- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : F8:CF:C5:D9:E5:61
--------------- motorola-XT1039_PT5358 --------------------- : 8

sendList : 100% : 16352 ms, 99% : 16352 ms, 95 : 16352 ms, 90% : 16352 ms.
Average data rate: 0.009 MB/s
Result count 3, range 6199 ms to  16352 ms.

sendList failed peers count : 10 [76.92307692307692 %]
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1

- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1

- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 38:94:96:B5:06:DC, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
sendList never tried peers count : 7 [35 %]

- Peer ID : 80:01:84:8A:B3:68
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 34:FC:EF:11:B1:66

- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : B4:CE:F6:AB:A4:6A
--------------- HUAWEI-ALE-L21_PT4512 --------------------- : 9

sendList : 100% : 34440 ms, 99% : 34440 ms, 95 : 34440 ms, 90% : 34440 ms.
Average data rate: 0.003 MB/s
Result count 1, range 34440 ms to  34440 ms.

sendList failed peers count : 19 [95 %]
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1

- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1

- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : 38:94:96:B5:06:DC, Tried : 1

- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
sendList never tried peers count : 0 [0 %]
--------------- LGE-Nexus 5_PT6585 --------------------- : 10
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 11 [100 %]
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
sendList never tried peers count : 9 [45 %]
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : F8:95:C7:87:85:54
- Peer ID : F8:CF:C5:D9:E5:61
- Peer ID : F8:95:C7:87:3C:51

- Peer ID : 38:94:96:B5:06:DC
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : B0:C5:59:3F:75:69

- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : F4:F1:E1:5C:3B:E2
--------------- samsung-SM-G800H_PT8320 --------------------- : 11

sendList : 100% : 9063 ms, 99% : 9063 ms, 95 : 9063 ms, 90% : 9063 ms.
Average data rate: 0.018 MB/s
Result count 3, range 3078 ms to  9063 ms.

sendList failed peers count : 8 [72.72727272727273 %]
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1

- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1

- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
sendList never tried peers count : 9 [45 %]
- Peer ID : E0:DB:10:14:E2:C0

- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : F8:95:C7:87:85:54
- Peer ID : B0:C5:59:3F:75:69

- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 08:EC:A9:50:75:41

- Peer ID : F8:CF:C5:D9:E5:61
--------------- LGE-Nexus 5_PT74 --------------------- : 12
sendList : 100% : 18096 ms, 99% : 18096 ms, 95 : 18096 ms, 90% : 18096 ms.

Average data rate: 0.008 MB/s
Result count 2, range 8124 ms to  18096 ms.
sendList failed peers count : 9 [81.81818181818181 %]
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1

- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1

- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1

- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
sendList never tried peers count : 9 [45 %]
- Peer ID : F8:95:C7:87:85:54
- Peer ID : 08:EC:A9:50:75:41

- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : B0:C5:59:3F:75:69

- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : F4:F1:E1:5C:3B:E2

--------------- Combined ---------------------

sendList : 100% : 36501 ms, 99% : 36501 ms, 95 : 34440 ms, 90% : 34440 ms.
Average data rate: 0.007 MB/s
--------------- end of test report ---------------------

2015-12-04T09:10:52.720Z (1380 sec) - Android HUAWEI-ALE-L21_PT4512 got disconnected

2015-12-04T09:10:52.726Z (1381 sec) - Android motorola-Nexus 6_PT1135 got disconnected

2015-12-04T09:10:52.778Z (1381 sec) - Android samsung-SM-G900F_PT5092 got disconnected

2015-12-04T09:10:52.882Z (1381 sec) - Android LGE-LG-D802_PT3722 got disconnected

2015-12-04T09:10:52.984Z (1381 sec) - Android samsung-SM-A500FU_PT4244 got disconnected

2015-12-04T09:10:53.060Z (1381 sec) - Android LGE-Nexus 5_PT74 got disconnected

2015-12-04T09:10:53.110Z (1381 sec) - Android LGE-LG-D722_PT5230 got disconnected

2015-12-04T09:10:53.425Z (1381 sec) - Android samsung-SM-G900F_PT2104 got disconnected

2015-12-04T09:11:52.857Z (1441 sec) - Android samsung-SM-N9005_PT3940 got disconnected

2015-12-04T09:11:56.039Z (1444 sec) - Android LGE-Nexus 5_PT6585 got disconnected

2015-12-04T09:12:08.481Z (1456 sec) - Android motorola-XT1039_PT5358 got disconnected

2015-12-04T09:12:08.900Z (1457 sec) - Android samsung-SM-G800H_PT8320 got disconnected


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


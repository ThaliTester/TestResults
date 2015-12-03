#### Test 52383621712b264 Logs

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

2015-12-03T14:43:46.129Z (0 sec) - Android tests will start after waiting for 120 seconds

Test ID 0 configuration: testSendData.js, server timeout: 1200000, data:

{ timeout: 1000000,
  rounds: 1,
  dataTimeout: 10000,
  dataAmount: 100000,
  conReTryTimeout: 5000,
  conReTryCount: 5 }

2015-12-03T14:43:46.135Z (0 sec) - iOS tests will start after waiting for 120 seconds

listening on *:3000

2015-12-03T14:43:47.711Z (2 sec) - Android HTC-HTC Desire 820_PT2572 added (current device count 1)

2015-12-03T14:43:47.727Z (2 sec) - iOS Apple-Iphone5-1_PT4165 added (current device count 1)

2015-12-03T14:43:47.794Z (2 sec) - Android samsung-SM-A300FU_PT2317 added (current device count 2)

2015-12-03T14:43:47.813Z (2 sec) - iOS Apple-Iphone5s-1_PT2374 added (current device count 2)

2015-12-03T14:43:47.816Z (2 sec) - Android samsung-SM-G900F_PT8216 added (current device count 3)

2015-12-03T14:43:47.857Z (2 sec) - Android LGE-LG-D855_PT7284 added (current device count 4)

2015-12-03T14:43:47.915Z (2 sec) - Android HUAWEI-ALE-L21_PT2479 added (current device count 5)

2015-12-03T14:43:48.134Z (2 sec) - Android samsung-SM-N910C_PT1345 added (current device count 6)

2015-12-03T14:43:48.296Z (2 sec) - Android samsung-SM-A300FU_PT6802 added (current device count 7)

2015-12-03T14:43:48.436Z (2 sec) - Android samsung-SM-G900F_PT9611 added (current device count 8)

2015-12-03T14:43:48.574Z (2 sec) - Android LGE-Nexus 5_PT3779 added (current device count 9)

2015-12-03T14:43:48.940Z (3 sec) - Android samsung-SM-A500FU_PT2273 added (current device count 10)

2015-12-03T14:43:49.335Z (3 sec) - iOS Apple-IpadAir2-1_PT6724 added (current device count 3)

2015-12-03T14:43:49.691Z (4 sec) - Android LGE-LG-H815_PT3573 added (current device count 11)

2015-12-03T14:43:49.713Z (4 sec) - iOS Apple-Iphone6-1_PT1068 added (current device count 4)

2015-12-03T14:43:49.858Z (4 sec) - Android HTC-HTC Desire 820_PT4731 added (current device count 12)

2015-12-03T14:43:50.012Z (4 sec) - Android motorola-XT1072_PT8266 added (current device count 13)

2015-12-03T14:43:50.509Z (4 sec) - Android LGE-LG-D722_PT6666 added (current device count 14)

2015-12-03T14:43:51.018Z (5 sec) - Android LGE-Nexus 5_PT4785 added (current device count 15)

2015-12-03T14:43:51.121Z (5 sec) - Android LGE-LG-D802_PT6494 added (current device count 16)

2015-12-03T14:43:56.777Z (11 sec) - Android samsung-SM-G800F_PT9166 added (current device count 17)

2015-12-03T14:44:11.769Z (26 sec) - Android motorola-XT1039_PT6584 added (current device count 18)

-------------- We got wait done, now starting the testing process ------------------

2015-12-03T14:45:46.179Z (120 sec) - Android start testing now with 18 devices

2015-12-03T14:45:46.203Z (120 sec) - iOS start testing now with 4 devices

2015-12-03T14:45:58.651Z (133 sec) - iOS Apple-IpadAir2-1_PT6724 test took 12445ms - results peers[0], reConnects[0], sendData[3]

2015-12-03T14:46:17.375Z (151 sec) - Android LGE-Nexus 5_PT4785 got re-connected event

2015-12-03T14:46:56.181Z (190 sec) - Android LGE-Nexus 5_PT4785 got disconnected

2015-12-03T14:47:27.007Z (221 sec) - Android samsung-SM-G800F_PT9166 got disconnected

2015-12-03T14:47:41.354Z (235 sec) - iOS Apple-Iphone5-1_PT4165 test took 115149ms - results peers[0], reConnects[0], sendData[3]

2015-12-03T14:47:47.601Z (242 sec) - iOS Apple-Iphone5s-1_PT2374 test took 121396ms - results peers[0], reConnects[0], sendData[3]

2015-12-03T14:48:07.449Z (261 sec) - Android LGE-Nexus 5_PT4785 got disconnected

2015-12-03T14:48:40.910Z (295 sec) - Android LGE-Nexus 5_PT4785 got re-connected event

2015-12-03T14:49:53.073Z (367 sec) - Android LGE-Nexus 5_PT4785 got re-connected event

2015-12-03T14:50:03.963Z (378 sec) - iOS Apple-Iphone6-1_PT1068 test took 257758ms - results peers[0], reConnects[0], sendData[3]

2015-12-03T14:50:03.965Z (378 sec) - iOS test ID 0 done now

2015-12-03T14:50:03.973Z (378 sec) - iOS All tests are done, preparing test report

--------------- test report ---------------------

--------------- Apple-Iphone5-1_PT4165 --------------------- : 1

sendList : 100% : 5029 ms, 99% : 5029 ms, 95 : 5029 ms, 90% : 5029 ms.

Average data rate: 0.024 MB/s

Result count 2, range 3351 ms to  5029 ms.

sendList failed peers count : 1 [33.333333333333336 %]

- Peer ID : Apple-Iphone5s-1_PT2374.Xv/DEA==, Tried : 5

sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5s-1_PT2374 --------------------- : 2

sendList : 100% : 8325 ms, 99% : 8325 ms, 95 : 8325 ms, 90% : 8325 ms.

Average data rate: 0.016 MB/s

Result count 2, range 4308 ms to  8325 ms.

sendList failed peers count : 1 [33.333333333333336 %]

- Peer ID : Apple-Iphone6-1_PT1068.V8ys1g==, Tried : 5

sendList never tried peers count : 0 [0 %]

--------------- Apple-IpadAir2-1_PT6724 --------------------- : 3

sendList : 100% : 3935 ms, 99% : 3935 ms, 95 : 3935 ms, 90% : 3935 ms.

Average data rate: 0.027 MB/s

Result count 3, range 3294 ms to  3935 ms.

sendList failed peers count : 0 [0 %]

sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone6-1_PT1068 --------------------- : 4

sendList : 100% : 47037 ms, 99% : 47037 ms, 95 : 47037 ms, 90% : 47037 ms.

Average data rate: 0.004 MB/s
Result count 2, range 4282 ms to  47037 ms.
sendList failed peers count : 1 [33.333333333333336 %]
- Peer ID : Apple-Iphone6-1_PT7057.4CFLyQ==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------
sendList : 100% : 47037 ms, 99% : 47037 ms, 95 : 47037 ms, 90% : 8325 ms.
Average data rate: 0.011 MB/s
--------------- end of test report ---------------------

2015-12-03T14:50:04.438Z (378 sec) - iOS Apple-IpadAir2-1_PT6724 got disconnected

2015-12-03T14:50:04.829Z (379 sec) - iOS Apple-Iphone5s-1_PT2374 got disconnected

2015-12-03T14:50:04.979Z (379 sec) - iOS Apple-Iphone6-1_PT1068 got disconnected

2015-12-03T14:50:05.910Z (380 sec) - Android LGE-Nexus 5_PT4785 got disconnected

2015-12-03T14:50:09.852Z (384 sec) - iOS Apple-Iphone5-1_PT4165 got disconnected

2015-12-03T14:51:53.400Z (487 sec) - Android LGE-Nexus 5_PT4785 got re-connected event

2015-12-03T14:52:33.712Z (528 sec) - Android LGE-Nexus 5_PT4785 got disconnected

2015-12-03T14:53:25.916Z (580 sec) - Android LGE-Nexus 5_PT4785 got re-connected event

2015-12-03T14:54:08.687Z (623 sec) - Android LGE-Nexus 5_PT4785 got disconnected

2015-12-03T14:54:22.835Z (637 sec) - Android LGE-Nexus 5_PT4785 got re-connected event

2015-12-03T14:55:15.843Z (690 sec) - Android LGE-Nexus 5_PT4785 got disconnected

2015-12-03T14:55:35.492Z (709 sec) - Android LGE-Nexus 5_PT4785 got re-connected event

2015-12-03T14:55:47.841Z (722 sec) - Android LGE-Nexus 5_PT4785 got disconnected

2015-12-03T14:56:57.812Z (792 sec) - Android LGE-Nexus 5_PT4785 got re-connected event

2015-12-03T14:57:25.270Z (819 sec) - Android LGE-Nexus 5_PT4785 got disconnected

2015-12-03T14:57:50.216Z (844 sec) - Android samsung-SM-A300FU_PT2317 got disconnected

2015-12-03T14:58:31.728Z (886 sec) - Android motorola-XT1039_PT6584 got re-connected event

2015-12-03T14:58:47.543Z (901 sec) - Android LGE-Nexus 5_PT4785 got disconnected

2015-12-03T14:58:49.040Z (903 sec) - Android HTC-HTC Desire 820_PT4731 got disconnected

2015-12-03T14:59:11.162Z (925 sec) - Android motorola-XT1039_PT6584 got disconnected

2015-12-03T14:59:59.552Z (973 sec) - Android HTC-HTC Desire 820_PT2572 got disconnected

2015-12-03T15:00:20.684Z (995 sec) - Android LGE-Nexus 5_PT4785 got re-connected event

2015-12-03T15:00:23.242Z (997 sec) - Android HTC-HTC Desire 820_PT4731 got re-connected event

2015-12-03T15:01:17.938Z (1052 sec) - Android motorola-XT1072_PT8266 got disconnected

2015-12-03T15:01:19.533Z (1053 sec) - Android motorola-XT1072_PT8266 got re-connected event

2015-12-03T15:02:26.505Z (1120 sec) - Android samsung-SM-N910C_PT1345 test took 1000315ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T15:02:26.577Z (1120 sec) - Android motorola-XT1039_PT6584 test took 1000377ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T15:02:26.584Z (1120 sec) - Android motorola-XT1072_PT8266 test took 1000389ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T15:02:26.592Z (1121 sec) - Android LGE-LG-D722_PT6666 test took 1000395ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T15:02:26.671Z (1121 sec) - Android LGE-Nexus 5_PT4785 test took 1000475ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T15:02:26.742Z (1121 sec) - Android LGE-Nexus 5_PT3779 test took 1000549ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T15:02:26.829Z (1121 sec) - Android samsung-SM-G900F_PT9611 test took 1000638ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T15:02:28.157Z (1122 sec) - Android LGE-LG-H815_PT3573 test took 1001963ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T15:02:28.632Z (1123 sec) - Android LGE-LG-D855_PT7284 test took 1002443ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T15:02:29.439Z (1123 sec) - Android samsung-SM-G900F_PT8216 test took 1003251ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T15:02:30.935Z (1125 sec) - Android LGE-LG-D802_PT6494 test took 1004738ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T15:02:31.527Z (1125 sec) - Android HUAWEI-ALE-L21_PT2479 test took 1005338ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T15:02:47.328Z (1141 sec) - Android samsung-SM-A300FU_PT6802 got disconnected

2015-12-03T15:03:30.035Z (1184 sec) - Android HTC-HTC Desire 820_PT4731 got disconnected

2015-12-03T15:03:40.617Z (1195 sec) - Android HTC-HTC Desire 820_PT4731 got re-connected event

2015-12-03T15:03:40.623Z (1195 sec) - Android HTC-HTC Desire 820_PT4731 test took 1074428ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T15:03:42.195Z (1196 sec) - Android samsung-SM-A500FU_PT2273 got disconnected

2015-12-03T15:04:52.518Z (1266 sec) - Android LGE-LG-D722_PT6666 got re-connected event

2015-12-03T15:05:45.497Z (1319 sec) - Android LGE-LG-D722_PT6666 got disconnected

2015-12-03T15:05:46.201Z (1320 sec) - Server timeout reached!

2015-12-03T15:05:46.203Z (1320 sec) - Send timeout to HTC-HTC Desire 820_PT2572

2015-12-03T15:05:46.205Z (1320 sec) - Send timeout to samsung-SM-A300FU_PT2317

2015-12-03T15:05:46.207Z (1320 sec) - Send timeout to samsung-SM-A300FU_PT6802

2015-12-03T15:05:46.211Z (1320 sec) - Send timeout to samsung-SM-A500FU_PT2273

2015-12-03T15:05:46.216Z (1320 sec) - Send timeout to samsung-SM-G800F_PT9166

2015-12-03T15:06:46.217Z (1380 sec) - Did not get reports from all devices, but forcing tests to finish!

HTC-HTC Desire 820_PT2572 did not have results at the end of tests - check the device logs about why!!

samsung-SM-A300FU_PT2317 did not have results at the end of tests - check the device logs about why!!

samsung-SM-A300FU_PT6802 did not have results at the end of tests - check the device logs about why!!

samsung-SM-A500FU_PT2273 did not have results at the end of tests - check the device logs about why!!

samsung-SM-G800F_PT9166 did not have results at the end of tests - check the device logs about why!!

2015-12-03T15:06:46.234Z (1380 sec) - Android All tests are done, preparing test report

--------------- test report ---------------------
--------------- samsung-SM-G900F_PT8216 --------------------- : 1
sendList : 100% : 43414 ms, 99% : 43414 ms, 95 : 43414 ms, 90% : 43414 ms.
Average data rate: 0.002 MB/s
Result count 1, range 43414 ms to  43414 ms.
sendList failed peers count : 8 [88.88888888888889 %]
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1

- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
sendList never tried peers count : 8 [47.05882352941177 %]

- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : B4:CE:F6:AB:A4:6A

- Peer ID : 7C:F9:0E:37:96:AB
--------------- LGE-LG-D855_PT7284 --------------------- : 2
sendList : 100% : 5956 ms, 99% : 5956 ms, 95 : 5956 ms, 90% : 5956 ms.
Average data rate: 0.017 MB/s
Result count 1, range 5956 ms to  5956 ms.
sendList failed peers count : 10 [90.9090909090909 %]

- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1

- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
sendList never tried peers count : 6 [35.294117647058826 %]
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 7C:F9:0E:34:8A:A0

--------------- HUAWEI-ALE-L21_PT2479 --------------------- : 3
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 9 [100 %]

- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
sendList never tried peers count : 8 [47.05882352941177 %]
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : F8:95:C7:87:85:54
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 34:FC:EF:11:AE:67
--------------- samsung-SM-N910C_PT1345 --------------------- : 4
sendList : 100% : 18670 ms, 99% : 18670 ms, 95 : 18670 ms, 90% : 18670 ms.
Average data rate: 0.005 MB/s
Result count 1, range 18670 ms to  18670 ms.
sendList failed peers count : 8 [88.88888888888889 %]
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
sendList never tried peers count : 8 [47.05882352941177 %]
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : 00:F4:6F:30:E0:6C

- Peer ID : 44:80:EB:7B:5A:05

--------------- samsung-SM-G900F_PT9611 --------------------- : 5
sendList : 100% : 4359 ms, 99% : 4359 ms, 95 : 4359 ms, 90% : 4359 ms.
Average data rate: 0.023 MB/s
Result count 1, range 4359 ms to  4359 ms.
sendList failed peers count : 9 [90 %]
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1

- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
sendList never tried peers count : 7 [41.1764705882353 %]
- Peer ID : 7C:F9:0E:37:96:AB

- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 08:EC:A9:50:75:41
--------------- LGE-Nexus 5_PT3779 --------------------- : 6

sendList : 100% : 20839 ms, 99% : 20839 ms, 95 : 20839 ms, 90% : 20839 ms.
Average data rate: 0.005 MB/s
Result count 1, range 20839 ms to  20839 ms.
sendList failed peers count : 10 [90.9090909090909 %]
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1

- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
sendList never tried peers count : 6 [35.294117647058826 %]
- Peer ID : 34:FC:EF:9D:93:0B

- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : F8:95:C7:87:85:54
--------------- LGE-LG-H815_PT3573 --------------------- : 7

sendList : 100% : 36822 ms, 99% : 36822 ms, 95 : 36822 ms, 90% : 36822 ms.
Average data rate: 0.005 MB/s
Result count 2, range 4653 ms to  36822 ms.
sendList failed peers count : 9 [81.81818181818181 %]
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1

- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
sendList never tried peers count : 6 [35.294117647058826 %]
- Peer ID : 58:3F:54:73:64:C0

- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 7C:F9:0E:37:96:AB
--------------- HTC-HTC Desire 820_PT4731 --------------------- : 8
sendList : 100% : 7029 ms, 99% : 7029 ms, 95 : 7029 ms, 90% : 7029 ms.

Average data rate: 0.014 MB/s
Result count 1, range 7029 ms to  7029 ms.
sendList failed peers count : 9 [90 %]
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1

- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
sendList never tried peers count : 7 [41.1764705882353 %]
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 08:EC:A9:50:76:27

- Peer ID : 58:2A:F7:ED:96:BE
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : F8:95:C7:87:3C:51
--------------- motorola-XT1072_PT8266 --------------------- : 9
sendList : 100% : 29315 ms, 99% : 29315 ms, 95 : 29315 ms, 90% : 29315 ms.

Average data rate: 0.003 MB/s
Result count 1, range 29315 ms to  29315 ms.
sendList failed peers count : 8 [88.88888888888889 %]
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1

- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
sendList never tried peers count : 8 [47.05882352941177 %]
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 34:FC:EF:9D:93:0B

- Peer ID : 80:01:84:8A:B3:68
- Peer ID : F8:95:C7:87:85:54
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 58:2A:F7:ED:96:BE
- Peer ID : B4:CE:F6:AB:A4:6A
--------------- LGE-LG-D722_PT6666 --------------------- : 10

sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 9 [100 %]
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1

- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
sendList never tried peers count : 8 [47.05882352941177 %]
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : 44:80:EB:7B:5A:05

- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 08:EC:A9:50:76:27
--------------- LGE-Nexus 5_PT4785 --------------------- : 11

sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 10 [100 %]
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1

- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1

sendList never tried peers count : 7 [41.1764705882353 %]
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : B4:CE:F6:AB:A4:6A

--------------- LGE-LG-D802_PT6494 --------------------- : 12
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 8 [100 %]
- Peer ID : F8:95:C7:87:85:54, Tried : 1

- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1

sendList never tried peers count : 9 [52.94117647058823 %]
- Peer ID : 7C:F9:0E:34:8A:A0

- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 34:FC:EF:11:AE:67

- Peer ID : B0:C5:59:3F:75:69
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 08:EC:A9:50:75:41
--------------- motorola-XT1039_PT6584 --------------------- : 13
sendList : 100% : 37891 ms, 99% : 37891 ms, 95 : 37891 ms, 90% : 37891 ms.
Average data rate: 0.003 MB/s
Result count 2, range 26259 ms to  37891 ms.
sendList failed peers count : 10 [83.33333333333333 %]
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
sendList never tried peers count : 5 [29.41176470588235 %]
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : F8:95:C7:87:85:54
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 34:FC:EF:11:B1:66
--------------- Combined ---------------------
sendList : 100% : 43414 ms, 99% : 43414 ms, 95 : 37891 ms, 90% : 37891 ms.
Average data rate: 0.005 MB/s
--------------- end of test report ---------------------

2015-12-03T15:06:46.509Z (1380 sec) - Android samsung-SM-N910C_PT1345 got disconnected

2015-12-03T15:06:46.599Z (1381 sec) - Android LGE-LG-H815_PT3573 got disconnected

2015-12-03T15:06:46.606Z (1381 sec) - Android LGE-LG-D802_PT6494 got disconnected

2015-12-03T15:06:46.614Z (1381 sec) - Android HUAWEI-ALE-L21_PT2479 got disconnected

2015-12-03T15:06:46.617Z (1381 sec) - Android LGE-LG-D722_PT6666 got disconnected

2015-12-03T15:06:46.630Z (1381 sec) - Android samsung-SM-G900F_PT9611 got disconnected

2015-12-03T15:06:46.893Z (1381 sec) - Android motorola-XT1072_PT8266 got disconnected

2015-12-03T15:06:46.980Z (1381 sec) - Android samsung-SM-G900F_PT8216 got disconnected

2015-12-03T15:06:47.140Z (1381 sec) - Android LGE-Nexus 5_PT3779 got disconnected

2015-12-03T15:07:57.626Z (1452 sec) - Android motorola-XT1039_PT6584 got disconnected

2015-12-03T15:08:01.686Z (1456 sec) - Android HTC-HTC Desire 820_PT4731 got disconnected

2015-12-03T15:08:02.819Z (1457 sec) - Android LGE-Nexus 5_PT4785 got disconnected

2015-12-03T15:08:09.084Z (1463 sec) - Android LGE-LG-D855_PT7284 got disconnected


 
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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/52383621712b264_Make_server_address_a_proper_node_module__vjrantal/thali01_LGE-LG-H815.md)

[HUAWEI-ALE-L21](https://github.com/ThaliTester/TestResults/blob/52383621712b264_Make_server_address_a_proper_node_module__vjrantal/thali01_HUAWEI-ALE-L21.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/52383621712b264_Make_server_address_a_proper_node_module__vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/52383621712b264_Make_server_address_a_proper_node_module__vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/52383621712b264_Make_server_address_a_proper_node_module__vjrantal/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/52383621712b264_Make_server_address_a_proper_node_module__vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/52383621712b264_Make_server_address_a_proper_node_module__vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/52383621712b264_Make_server_address_a_proper_node_module__vjrantal/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/52383621712b264_Make_server_address_a_proper_node_module__vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/52383621712b264_Make_server_address_a_proper_node_module__vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/52383621712b264_Make_server_address_a_proper_node_module__vjrantal/thali04_samsung-SM-G900F.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/52383621712b264_Make_server_address_a_proper_node_module__vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/52383621712b264_Make_server_address_a_proper_node_module__vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/52383621712b264_Make_server_address_a_proper_node_module__vjrantal/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/52383621712b264_Make_server_address_a_proper_node_module__vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/52383621712b264_Make_server_address_a_proper_node_module__vjrantal/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/52383621712b264_Make_server_address_a_proper_node_module__vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/52383621712b264_Make_server_address_a_proper_node_module__vjrantal/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
Device test finished on 0c6a0f3c0bdb4e77 
STOP log received from  CC51WYC03425 Test has  SUCCEEDED
Device test finished on CC51WYC03425 
Android task is completed. [SUCCESS]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/52383621712b264_Make_server_address_a_proper_node_module__vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/52383621712b264_Make_server_address_a_proper_node_module__vjrantal/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/52383621712b264_Make_server_address_a_proper_node_module__vjrantal/iOS_Iphone5-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/52383621712b264_Make_server_address_a_proper_node_module__vjrantal/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/52383621712b264_Make_server_address_a_proper_node_module__vjrantal/iOS_Iphone6-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/52383621712b264_Make_server_address_a_proper_node_module__vjrantal/iOS_IpadAir2-1.md)


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

2015-12-03T14:43:46.129Z (0 sec) - Android tests will start after waiting for 120 seconds

Test ID 0 configuration: testSendData.js, server timeout: 1200000, data:

{ timeout: 1000000,
  rounds: 1,
  dataTimeout: 10000,
  dataAmount: 100000,
  conReTryTimeout: 5000,
  conReTryCount: 5 }

2015-12-03T14:43:46.135Z (0 sec) - iOS tests will start after waiting for 120 seconds

listening on *:3000

2015-12-03T14:43:47.711Z (2 sec) - Android HTC-HTC Desire 820_PT2572 added (current device count 1)

2015-12-03T14:43:47.727Z (2 sec) - iOS Apple-Iphone5-1_PT4165 added (current device count 1)

2015-12-03T14:43:47.794Z (2 sec) - Android samsung-SM-A300FU_PT2317 added (current device count 2)

2015-12-03T14:43:47.813Z (2 sec) - iOS Apple-Iphone5s-1_PT2374 added (current device count 2)

2015-12-03T14:43:47.816Z (2 sec) - Android samsung-SM-G900F_PT8216 added (current device count 3)

2015-12-03T14:43:47.857Z (2 sec) - Android LGE-LG-D855_PT7284 added (current device count 4)

2015-12-03T14:43:47.915Z (2 sec) - Android HUAWEI-ALE-L21_PT2479 added (current device count 5)

2015-12-03T14:43:48.134Z (2 sec) - Android samsung-SM-N910C_PT1345 added (current device count 6)

2015-12-03T14:43:48.296Z (2 sec) - Android samsung-SM-A300FU_PT6802 added (current device count 7)

2015-12-03T14:43:48.436Z (2 sec) - Android samsung-SM-G900F_PT9611 added (current device count 8)

2015-12-03T14:43:48.574Z (2 sec) - Android LGE-Nexus 5_PT3779 added (current device count 9)

2015-12-03T14:43:48.940Z (3 sec) - Android samsung-SM-A500FU_PT2273 added (current device count 10)

2015-12-03T14:43:49.335Z (3 sec) - iOS Apple-IpadAir2-1_PT6724 added (current device count 3)

2015-12-03T14:43:49.691Z (4 sec) - Android LGE-LG-H815_PT3573 added (current device count 11)

2015-12-03T14:43:49.713Z (4 sec) - iOS Apple-Iphone6-1_PT1068 added (current device count 4)

2015-12-03T14:43:49.858Z (4 sec) - Android HTC-HTC Desire 820_PT4731 added (current device count 12)

2015-12-03T14:43:50.012Z (4 sec) - Android motorola-XT1072_PT8266 added (current device count 13)

2015-12-03T14:43:50.509Z (4 sec) - Android LGE-LG-D722_PT6666 added (current device count 14)

2015-12-03T14:43:51.018Z (5 sec) - Android LGE-Nexus 5_PT4785 added (current device count 15)

2015-12-03T14:43:51.121Z (5 sec) - Android LGE-LG-D802_PT6494 added (current device count 16)

2015-12-03T14:43:56.777Z (11 sec) - Android samsung-SM-G800F_PT9166 added (current device count 17)

2015-12-03T14:44:11.769Z (26 sec) - Android motorola-XT1039_PT6584 added (current device count 18)

-------------- We got wait done, now starting the testing process ------------------

2015-12-03T14:45:46.179Z (120 sec) - Android start testing now with 18 devices

2015-12-03T14:45:46.203Z (120 sec) - iOS start testing now with 4 devices

2015-12-03T14:45:58.651Z (133 sec) - iOS Apple-IpadAir2-1_PT6724 test took 12445ms - results peers[0], reConnects[0], sendData[3]

2015-12-03T14:46:17.375Z (151 sec) - Android LGE-Nexus 5_PT4785 got re-connected event

2015-12-03T14:46:56.181Z (190 sec) - Android LGE-Nexus 5_PT4785 got disconnected

2015-12-03T14:47:27.007Z (221 sec) - Android samsung-SM-G800F_PT9166 got disconnected

2015-12-03T14:47:41.354Z (235 sec) - iOS Apple-Iphone5-1_PT4165 test took 115149ms - results peers[0], reConnects[0], sendData[3]

2015-12-03T14:47:47.601Z (242 sec) - iOS Apple-Iphone5s-1_PT2374 test took 121396ms - results peers[0], reConnects[0], sendData[3]

2015-12-03T14:48:07.449Z (261 sec) - Android LGE-Nexus 5_PT4785 got disconnected

2015-12-03T14:48:40.910Z (295 sec) - Android LGE-Nexus 5_PT4785 got re-connected event

2015-12-03T14:49:53.073Z (367 sec) - Android LGE-Nexus 5_PT4785 got re-connected event

2015-12-03T14:50:03.963Z (378 sec) - iOS Apple-Iphone6-1_PT1068 test took 257758ms - results peers[0], reConnects[0], sendData[3]

2015-12-03T14:50:03.965Z (378 sec) - iOS test ID 0 done now

2015-12-03T14:50:03.973Z (378 sec) - iOS All tests are done, preparing test report

--------------- test report ---------------------

--------------- Apple-Iphone5-1_PT4165 --------------------- : 1

sendList : 100% : 5029 ms, 99% : 5029 ms, 95 : 5029 ms, 90% : 5029 ms.

Average data rate: 0.024 MB/s

Result count 2, range 3351 ms to  5029 ms.

sendList failed peers count : 1 [33.333333333333336 %]

- Peer ID : Apple-Iphone5s-1_PT2374.Xv/DEA==, Tried : 5

sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5s-1_PT2374 --------------------- : 2

sendList : 100% : 8325 ms, 99% : 8325 ms, 95 : 8325 ms, 90% : 8325 ms.

Average data rate: 0.016 MB/s

Result count 2, range 4308 ms to  8325 ms.

sendList failed peers count : 1 [33.333333333333336 %]

- Peer ID : Apple-Iphone6-1_PT1068.V8ys1g==, Tried : 5

sendList never tried peers count : 0 [0 %]

--------------- Apple-IpadAir2-1_PT6724 --------------------- : 3

sendList : 100% : 3935 ms, 99% : 3935 ms, 95 : 3935 ms, 90% : 3935 ms.

Average data rate: 0.027 MB/s

Result count 3, range 3294 ms to  3935 ms.

sendList failed peers count : 0 [0 %]

sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone6-1_PT1068 --------------------- : 4

sendList : 100% : 47037 ms, 99% : 47037 ms, 95 : 47037 ms, 90% : 47037 ms.

Average data rate: 0.004 MB/s
Result count 2, range 4282 ms to  47037 ms.
sendList failed peers count : 1 [33.333333333333336 %]
- Peer ID : Apple-Iphone6-1_PT7057.4CFLyQ==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------
sendList : 100% : 47037 ms, 99% : 47037 ms, 95 : 47037 ms, 90% : 8325 ms.
Average data rate: 0.011 MB/s
--------------- end of test report ---------------------

2015-12-03T14:50:04.438Z (378 sec) - iOS Apple-IpadAir2-1_PT6724 got disconnected

2015-12-03T14:50:04.829Z (379 sec) - iOS Apple-Iphone5s-1_PT2374 got disconnected

2015-12-03T14:50:04.979Z (379 sec) - iOS Apple-Iphone6-1_PT1068 got disconnected

2015-12-03T14:50:05.910Z (380 sec) - Android LGE-Nexus 5_PT4785 got disconnected

2015-12-03T14:50:09.852Z (384 sec) - iOS Apple-Iphone5-1_PT4165 got disconnected

2015-12-03T14:51:53.400Z (487 sec) - Android LGE-Nexus 5_PT4785 got re-connected event

2015-12-03T14:52:33.712Z (528 sec) - Android LGE-Nexus 5_PT4785 got disconnected

2015-12-03T14:53:25.916Z (580 sec) - Android LGE-Nexus 5_PT4785 got re-connected event

2015-12-03T14:54:08.687Z (623 sec) - Android LGE-Nexus 5_PT4785 got disconnected

2015-12-03T14:54:22.835Z (637 sec) - Android LGE-Nexus 5_PT4785 got re-connected event

2015-12-03T14:55:15.843Z (690 sec) - Android LGE-Nexus 5_PT4785 got disconnected

2015-12-03T14:55:35.492Z (709 sec) - Android LGE-Nexus 5_PT4785 got re-connected event

2015-12-03T14:55:47.841Z (722 sec) - Android LGE-Nexus 5_PT4785 got disconnected

2015-12-03T14:56:57.812Z (792 sec) - Android LGE-Nexus 5_PT4785 got re-connected event

2015-12-03T14:57:25.270Z (819 sec) - Android LGE-Nexus 5_PT4785 got disconnected

2015-12-03T14:57:50.216Z (844 sec) - Android samsung-SM-A300FU_PT2317 got disconnected

2015-12-03T14:58:31.728Z (886 sec) - Android motorola-XT1039_PT6584 got re-connected event

2015-12-03T14:58:47.543Z (901 sec) - Android LGE-Nexus 5_PT4785 got disconnected

2015-12-03T14:58:49.040Z (903 sec) - Android HTC-HTC Desire 820_PT4731 got disconnected

2015-12-03T14:59:11.162Z (925 sec) - Android motorola-XT1039_PT6584 got disconnected

2015-12-03T14:59:59.552Z (973 sec) - Android HTC-HTC Desire 820_PT2572 got disconnected

2015-12-03T15:00:20.684Z (995 sec) - Android LGE-Nexus 5_PT4785 got re-connected event

2015-12-03T15:00:23.242Z (997 sec) - Android HTC-HTC Desire 820_PT4731 got re-connected event

2015-12-03T15:01:17.938Z (1052 sec) - Android motorola-XT1072_PT8266 got disconnected

2015-12-03T15:01:19.533Z (1053 sec) - Android motorola-XT1072_PT8266 got re-connected event

2015-12-03T15:02:26.505Z (1120 sec) - Android samsung-SM-N910C_PT1345 test took 1000315ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T15:02:26.577Z (1120 sec) - Android motorola-XT1039_PT6584 test took 1000377ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T15:02:26.584Z (1120 sec) - Android motorola-XT1072_PT8266 test took 1000389ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T15:02:26.592Z (1121 sec) - Android LGE-LG-D722_PT6666 test took 1000395ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T15:02:26.671Z (1121 sec) - Android LGE-Nexus 5_PT4785 test took 1000475ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T15:02:26.742Z (1121 sec) - Android LGE-Nexus 5_PT3779 test took 1000549ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T15:02:26.829Z (1121 sec) - Android samsung-SM-G900F_PT9611 test took 1000638ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T15:02:28.157Z (1122 sec) - Android LGE-LG-H815_PT3573 test took 1001963ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T15:02:28.632Z (1123 sec) - Android LGE-LG-D855_PT7284 test took 1002443ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T15:02:29.439Z (1123 sec) - Android samsung-SM-G900F_PT8216 test took 1003251ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T15:02:30.935Z (1125 sec) - Android LGE-LG-D802_PT6494 test took 1004738ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T15:02:31.527Z (1125 sec) - Android HUAWEI-ALE-L21_PT2479 test took 1005338ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T15:02:47.328Z (1141 sec) - Android samsung-SM-A300FU_PT6802 got disconnected

2015-12-03T15:03:30.035Z (1184 sec) - Android HTC-HTC Desire 820_PT4731 got disconnected

2015-12-03T15:03:40.617Z (1195 sec) - Android HTC-HTC Desire 820_PT4731 got re-connected event

2015-12-03T15:03:40.623Z (1195 sec) - Android HTC-HTC Desire 820_PT4731 test took 1074428ms - results peers[0], reConnects[0], sendData[17]

2015-12-03T15:03:42.195Z (1196 sec) - Android samsung-SM-A500FU_PT2273 got disconnected

2015-12-03T15:04:52.518Z (1266 sec) - Android LGE-LG-D722_PT6666 got re-connected event

2015-12-03T15:05:45.497Z (1319 sec) - Android LGE-LG-D722_PT6666 got disconnected

2015-12-03T15:05:46.201Z (1320 sec) - Server timeout reached!

2015-12-03T15:05:46.203Z (1320 sec) - Send timeout to HTC-HTC Desire 820_PT2572

2015-12-03T15:05:46.205Z (1320 sec) - Send timeout to samsung-SM-A300FU_PT2317

2015-12-03T15:05:46.207Z (1320 sec) - Send timeout to samsung-SM-A300FU_PT6802

2015-12-03T15:05:46.211Z (1320 sec) - Send timeout to samsung-SM-A500FU_PT2273

2015-12-03T15:05:46.216Z (1320 sec) - Send timeout to samsung-SM-G800F_PT9166

2015-12-03T15:06:46.217Z (1380 sec) - Did not get reports from all devices, but forcing tests to finish!

HTC-HTC Desire 820_PT2572 did not have results at the end of tests - check the device logs about why!!

samsung-SM-A300FU_PT2317 did not have results at the end of tests - check the device logs about why!!

samsung-SM-A300FU_PT6802 did not have results at the end of tests - check the device logs about why!!

samsung-SM-A500FU_PT2273 did not have results at the end of tests - check the device logs about why!!

samsung-SM-G800F_PT9166 did not have results at the end of tests - check the device logs about why!!

2015-12-03T15:06:46.234Z (1380 sec) - Android All tests are done, preparing test report

--------------- test report ---------------------
--------------- samsung-SM-G900F_PT8216 --------------------- : 1
sendList : 100% : 43414 ms, 99% : 43414 ms, 95 : 43414 ms, 90% : 43414 ms.
Average data rate: 0.002 MB/s
Result count 1, range 43414 ms to  43414 ms.
sendList failed peers count : 8 [88.88888888888889 %]
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1

- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
sendList never tried peers count : 8 [47.05882352941177 %]

- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : B4:CE:F6:AB:A4:6A

- Peer ID : 7C:F9:0E:37:96:AB
--------------- LGE-LG-D855_PT7284 --------------------- : 2
sendList : 100% : 5956 ms, 99% : 5956 ms, 95 : 5956 ms, 90% : 5956 ms.
Average data rate: 0.017 MB/s
Result count 1, range 5956 ms to  5956 ms.
sendList failed peers count : 10 [90.9090909090909 %]

- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1

- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
sendList never tried peers count : 6 [35.294117647058826 %]
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 7C:F9:0E:34:8A:A0

--------------- HUAWEI-ALE-L21_PT2479 --------------------- : 3
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 9 [100 %]

- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
sendList never tried peers count : 8 [47.05882352941177 %]
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : F8:95:C7:87:85:54
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 34:FC:EF:11:AE:67
--------------- samsung-SM-N910C_PT1345 --------------------- : 4
sendList : 100% : 18670 ms, 99% : 18670 ms, 95 : 18670 ms, 90% : 18670 ms.
Average data rate: 0.005 MB/s
Result count 1, range 18670 ms to  18670 ms.
sendList failed peers count : 8 [88.88888888888889 %]
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
sendList never tried peers count : 8 [47.05882352941177 %]
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : 00:F4:6F:30:E0:6C

- Peer ID : 44:80:EB:7B:5A:05

--------------- samsung-SM-G900F_PT9611 --------------------- : 5
sendList : 100% : 4359 ms, 99% : 4359 ms, 95 : 4359 ms, 90% : 4359 ms.
Average data rate: 0.023 MB/s
Result count 1, range 4359 ms to  4359 ms.
sendList failed peers count : 9 [90 %]
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1

- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
sendList never tried peers count : 7 [41.1764705882353 %]
- Peer ID : 7C:F9:0E:37:96:AB

- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 08:EC:A9:50:75:41
--------------- LGE-Nexus 5_PT3779 --------------------- : 6

sendList : 100% : 20839 ms, 99% : 20839 ms, 95 : 20839 ms, 90% : 20839 ms.
Average data rate: 0.005 MB/s
Result count 1, range 20839 ms to  20839 ms.
sendList failed peers count : 10 [90.9090909090909 %]
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1

- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
sendList never tried peers count : 6 [35.294117647058826 %]
- Peer ID : 34:FC:EF:9D:93:0B

- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : F8:95:C7:87:85:54
--------------- LGE-LG-H815_PT3573 --------------------- : 7

sendList : 100% : 36822 ms, 99% : 36822 ms, 95 : 36822 ms, 90% : 36822 ms.
Average data rate: 0.005 MB/s
Result count 2, range 4653 ms to  36822 ms.
sendList failed peers count : 9 [81.81818181818181 %]
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1

- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
sendList never tried peers count : 6 [35.294117647058826 %]
- Peer ID : 58:3F:54:73:64:C0

- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 7C:F9:0E:37:96:AB
--------------- HTC-HTC Desire 820_PT4731 --------------------- : 8
sendList : 100% : 7029 ms, 99% : 7029 ms, 95 : 7029 ms, 90% : 7029 ms.

Average data rate: 0.014 MB/s
Result count 1, range 7029 ms to  7029 ms.
sendList failed peers count : 9 [90 %]
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1

- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
sendList never tried peers count : 7 [41.1764705882353 %]
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 08:EC:A9:50:76:27

- Peer ID : 58:2A:F7:ED:96:BE
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : F8:95:C7:87:3C:51
--------------- motorola-XT1072_PT8266 --------------------- : 9
sendList : 100% : 29315 ms, 99% : 29315 ms, 95 : 29315 ms, 90% : 29315 ms.

Average data rate: 0.003 MB/s
Result count 1, range 29315 ms to  29315 ms.
sendList failed peers count : 8 [88.88888888888889 %]
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1

- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
sendList never tried peers count : 8 [47.05882352941177 %]
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 34:FC:EF:9D:93:0B

- Peer ID : 80:01:84:8A:B3:68
- Peer ID : F8:95:C7:87:85:54
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 58:2A:F7:ED:96:BE
- Peer ID : B4:CE:F6:AB:A4:6A
--------------- LGE-LG-D722_PT6666 --------------------- : 10

sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 9 [100 %]
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1

- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
sendList never tried peers count : 8 [47.05882352941177 %]
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : 44:80:EB:7B:5A:05

- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 08:EC:A9:50:76:27
--------------- LGE-Nexus 5_PT4785 --------------------- : 11

sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 10 [100 %]
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1

- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1

sendList never tried peers count : 7 [41.1764705882353 %]
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : B4:CE:F6:AB:A4:6A

--------------- LGE-LG-D802_PT6494 --------------------- : 12
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 8 [100 %]
- Peer ID : F8:95:C7:87:85:54, Tried : 1

- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1

sendList never tried peers count : 9 [52.94117647058823 %]
- Peer ID : 7C:F9:0E:34:8A:A0

- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 34:FC:EF:11:AE:67

- Peer ID : B0:C5:59:3F:75:69
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 08:EC:A9:50:75:41
--------------- motorola-XT1039_PT6584 --------------------- : 13
sendList : 100% : 37891 ms, 99% : 37891 ms, 95 : 37891 ms, 90% : 37891 ms.
Average data rate: 0.003 MB/s
Result count 2, range 26259 ms to  37891 ms.
sendList failed peers count : 10 [83.33333333333333 %]
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
sendList never tried peers count : 5 [29.41176470588235 %]
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : F8:95:C7:87:85:54
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 34:FC:EF:11:B1:66
--------------- Combined ---------------------
sendList : 100% : 43414 ms, 99% : 43414 ms, 95 : 37891 ms, 90% : 37891 ms.
Average data rate: 0.005 MB/s
--------------- end of test report ---------------------

2015-12-03T15:06:46.509Z (1380 sec) - Android samsung-SM-N910C_PT1345 got disconnected

2015-12-03T15:06:46.599Z (1381 sec) - Android LGE-LG-H815_PT3573 got disconnected

2015-12-03T15:06:46.606Z (1381 sec) - Android LGE-LG-D802_PT6494 got disconnected

2015-12-03T15:06:46.614Z (1381 sec) - Android HUAWEI-ALE-L21_PT2479 got disconnected

2015-12-03T15:06:46.617Z (1381 sec) - Android LGE-LG-D722_PT6666 got disconnected

2015-12-03T15:06:46.630Z (1381 sec) - Android samsung-SM-G900F_PT9611 got disconnected

2015-12-03T15:06:46.893Z (1381 sec) - Android motorola-XT1072_PT8266 got disconnected

2015-12-03T15:06:46.980Z (1381 sec) - Android samsung-SM-G900F_PT8216 got disconnected

2015-12-03T15:06:47.140Z (1381 sec) - Android LGE-Nexus 5_PT3779 got disconnected

2015-12-03T15:07:57.626Z (1452 sec) - Android motorola-XT1039_PT6584 got disconnected

2015-12-03T15:08:01.686Z (1456 sec) - Android HTC-HTC Desire 820_PT4731 got disconnected

2015-12-03T15:08:02.819Z (1457 sec) - Android LGE-Nexus 5_PT4785 got disconnected

2015-12-03T15:08:09.084Z (1463 sec) - Android LGE-LG-D855_PT7284 got disconnected


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


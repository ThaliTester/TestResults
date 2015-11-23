#### Test 513350289b9c5d6 Logs

Status: 
```

ios : false

server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":18}}
Test ID 0 configuration: testSendData.js, server timeout: 1200000, data:

{ timeout: '1000000',
  rounds: '1',
  dataTimeout: '10000',
  dataAmount: '100000',
  conReTryTimeout: '5000',
  conReTryCount: '5' }

2015-11-23T11:34:41.787Z (0 sec) - Android tests will start after waiting for 120 seconds

Test ID 0 configuration: testSendData.js, server timeout: 1200000, data:

{ timeout: '1000000',
  rounds: '1',
  dataTimeout: '10000',
  dataAmount: '100000',
  conReTryTimeout: '5000',
  conReTryCount: '5' }

2015-11-23T11:34:41.793Z (0 sec) - iOS tests will start after waiting for 120 seconds

listening on *:3000

2015-11-23T11:34:42.295Z (1 sec) - Android samsung-SM-A500FU_PT3363 added (current device count 1)

2015-11-23T11:34:42.320Z (1 sec) - Android LGE-LG-H815_PT3952 added (current device count 2)

2015-11-23T11:34:42.336Z (1 sec) - Android LGE-LG-D855_PT626 added (current device count 3)

2015-11-23T11:34:42.494Z (1 sec) - Android motorola-Nexus 6_PT8557 added (current device count 4)

2015-11-23T11:34:43.039Z (1 sec) - Android samsung-SM-N9005_PT7498 added (current device count 5)

2015-11-23T11:34:43.085Z (1 sec) - Android LGE-Nexus 5_PT910 added (current device count 6)

2015-11-23T11:34:43.315Z (2 sec) - iOS Apple-Iphone6-1_PT7664 added (current device count 1)

2015-11-23T11:34:43.365Z (2 sec) - iOS Apple-Iphone5s-1_PT8005 added (current device count 2)

2015-11-23T11:34:43.615Z (2 sec) - Android samsung-SM-N910C_PT6816 added (current device count 7)

2015-11-23T11:34:43.792Z (2 sec) - Android motorola-XT1072_PT5877 added (current device count 8)

2015-11-23T11:34:44.433Z (3 sec) - Android samsung-SM-A300FU_PT5957 added (current device count 9)

2015-11-23T11:34:44.943Z (3 sec) - Android HTC-HTC One_M8_PT699 added (current device count 10)

2015-11-23T11:34:45.292Z (4 sec) - Android HTC-HTC Desire 820_PT9241 added (current device count 11)

2015-11-23T11:34:45.929Z (4 sec) - Android LGE-LG-D722_PT4588 added (current device count 12)

2015-11-23T11:34:46.162Z (4 sec) - iOS Apple-Iphone5-1_PT142 added (current device count 3)

2015-11-23T11:34:46.361Z (5 sec) - Android samsung-SM-G900F_PT3613 added (current device count 13)

2015-11-23T11:34:46.699Z (5 sec) - Android HUAWEI-ALE-L21_PT6669 added (current device count 14)

2015-11-23T11:34:46.702Z (5 sec) - Android samsung-SM-G800F_PT9160 added (current device count 15)

2015-11-23T11:34:46.763Z (5 sec) - iOS Apple-IpadAir2-1_PT6529 added (current device count 4)

2015-11-23T11:34:46.866Z (5 sec) - Android LGE-Nexus 5_PT3069 added (current device count 16)

2015-11-23T11:34:46.886Z (5 sec) - Android HTC-HTC Desire 820_PT5500 added (current device count 17)

2015-11-23T11:35:08.239Z (26 sec) - Android motorola-XT1039_PT6969 added (current device count 18)

-------------- We got wait done, now starting the testing process ------------------

2015-11-23T11:36:41.837Z (120 sec) - Android start testing now with 18 devices

2015-11-23T11:36:41.865Z (120 sec) - iOS start testing now with 4 devices

2015-11-23T11:36:53.674Z (132 sec) - iOS Apple-Iphone6-1_PT7664 test took 11808ms - results peers[0], reConnects[0], sendData[3]

2015-11-23T11:36:54.250Z (133 sec) - iOS Apple-Iphone5-1_PT142 test took 12384ms - results peers[0], reConnects[0], sendData[3]

2015-11-23T11:36:55.675Z (134 sec) - iOS Apple-Iphone5s-1_PT8005 test took 13809ms - results peers[0], reConnects[0], sendData[3]

2015-11-23T11:36:59.679Z (138 sec) - iOS Apple-IpadAir2-1_PT6529 test took 17811ms - results peers[0], reConnects[0], sendData[3]

2015-11-23T11:36:59.681Z (138 sec) - iOS test ID 0 done now

2015-11-23T11:36:59.702Z (138 sec) - iOS All tests are done, preparing test report

--------------- test report ---------------------

--------------- Apple-Iphone6-1_PT7664 --------------------- : 1

sendList : 100% : 4200 ms, 99% : 4200 ms, 95 : 4200 ms, 90% : 4200 ms.

Result count 3, range 2857 ms to  4200 ms.

sendList failed peers count : 0 [0 %]

sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5s-1_PT8005 --------------------- : 2
sendList : 100% : 4725 ms, 99% : 4725 ms, 95 : 4725 ms, 90% : 4725 ms.

Result count 3, range 3704 ms to  4725 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5-1_PT142 --------------------- : 3
sendList : 100% : 5067 ms, 99% : 5067 ms, 95 : 5067 ms, 90% : 5067 ms.
Result count 3, range 2877 ms to  5067 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- Apple-IpadAir2-1_PT6529 --------------------- : 4
sendList : 100% : 8751 ms, 99% : 8751 ms, 95 : 8751 ms, 90% : 8751 ms.
Result count 3, range 3192 ms to  8751 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------

sendList : 100% : 8751 ms, 99% : 8751 ms, 95 : 5174 ms, 90% : 5174 ms.

--------------- end of test report ---------------------

2015-11-23T11:37:52.116Z (190 sec) - Android LGE-Nexus 5_PT3069 got disconnected

2015-11-23T11:37:54.959Z (193 sec) - Android motorola-XT1072_PT5877 got re-connected event

2015-11-23T11:37:55.832Z (194 sec) - Android HTC-HTC Desire 820_PT5500 got disconnected

2015-11-23T11:38:13.807Z (212 sec) - Android samsung-SM-N910C_PT6816 got disconnected

2015-11-23T11:38:38.928Z (237 sec) - Android motorola-XT1039_PT6969 got disconnected

2015-11-23T11:38:39.411Z (238 sec) - Android motorola-XT1039_PT6969 got re-connected event

2015-11-23T11:38:51.133Z (249 sec) - Android motorola-XT1072_PT5877 got disconnected

2015-11-23T11:39:02.839Z (261 sec) - Android LGE-LG-H815_PT3952 got disconnected

2015-11-23T11:39:05.212Z (263 sec) - Android samsung-SM-A300FU_PT5957 got disconnected

2015-11-23T11:39:08.719Z (267 sec) - Android samsung-SM-G800F_PT9160 got disconnected

2015-11-23T11:39:20.907Z (279 sec) - Android motorola-Nexus 6_PT8557 got re-connected event

2015-11-23T11:39:44.837Z (303 sec) - Android motorola-XT1072_PT5877 got disconnected

2015-11-23T11:39:53.496Z (312 sec) - Android LGE-LG-D722_PT4588 got re-connected event

2015-11-23T11:40:18.596Z (337 sec) - Android motorola-Nexus 6_PT8557 got disconnected

2015-11-23T11:40:29.933Z (348 sec) - Android motorola-Nexus 6_PT8557 got re-connected event

2015-11-23T11:40:46.814Z (365 sec) - Android LGE-LG-D722_PT4588 got disconnected

2015-11-23T11:41:33.935Z (412 sec) - Android motorola-Nexus 6_PT8557 got disconnected

2015-11-23T11:41:35.956Z (414 sec) - Android LGE-LG-D855_PT626 got disconnected

2015-11-23T11:42:15.850Z (454 sec) - Android motorola-XT1039_PT6969 got disconnected

2015-11-23T11:42:34.214Z (472 sec) - Android LGE-LG-D722_PT4588 got disconnected

2015-11-23T11:43:57.961Z (556 sec) - Android HTC-HTC Desire 820_PT9241 got disconnected

2015-11-23T11:44:40.356Z (599 sec) - Android samsung-SM-A500FU_PT3363 got disconnected

2015-11-23T11:44:59.995Z (618 sec) - Android samsung-SM-G900F_PT3613 got disconnected

2015-11-23T11:48:54.397Z (853 sec) - Android HTC-HTC Desire 820_PT5500 got re-connected event

2015-11-23T11:53:22.146Z (1120 sec) - Android samsung-SM-N9005_PT7498 test took 1000295ms - results peers[0], reConnects[0], sendData[17]

2015-11-23T11:53:22.261Z (1121 sec) - Android HTC-HTC One_M8_PT699 test took 1000406ms - results peers[0], reConnects[0], sendData[17]

2015-11-23T11:53:22.745Z (1121 sec) - Android LGE-Nexus 5_PT910 test took 1000893ms - results peers[0], reConnects[0], sendData[17]

2015-11-23T11:53:23.636Z (1122 sec) - Android HUAWEI-ALE-L21_PT6669 test took 1001779ms - results peers[0], reConnects[0], sendData[17]

2015-11-23T11:53:34.291Z (1133 sec) - Android motorola-Nexus 6_PT8557 got re-connected event

2015-11-23T11:53:34.313Z (1133 sec) - Android motorola-Nexus 6_PT8557 test took 1012463ms - results peers[0], reConnects[0], sendData[17]

2015-11-23T11:54:07.191Z (1165 sec) - Android HTC-HTC Desire 820_PT5500 got disconnected

2015-11-23T11:54:26.915Z (1185 sec) - Android motorola-Nexus 6_PT8557 got disconnected

2015-11-23T11:55:00.157Z (1218 sec) - Android HTC-HTC Desire 820_PT5500 got re-connected event

2015-11-23T11:55:00.171Z (1218 sec) - Android HTC-HTC Desire 820_PT5500 test took 1098311ms - results peers[0], reConnects[0], sendData[17]

2015-11-23T11:56:41.869Z (1320 sec) - Server timeout reached!

2015-11-23T11:56:41.871Z (1320 sec) - Send timeout to samsung-SM-A500FU_PT3363

2015-11-23T11:56:41.872Z (1320 sec) - Send timeout to LGE-LG-H815_PT3952

2015-11-23T11:56:41.873Z (1320 sec) - Send timeout to LGE-LG-D855_PT626

2015-11-23T11:56:41.873Z (1320 sec) - Send timeout to samsung-SM-N910C_PT6816

2015-11-23T11:56:41.874Z (1320 sec) - Send timeout to motorola-XT1072_PT5877

2015-11-23T11:56:41.874Z (1320 sec) - Send timeout to samsung-SM-A300FU_PT5957

2015-11-23T11:56:41.875Z (1320 sec) - Send timeout to HTC-HTC Desire 820_PT9241

2015-11-23T11:56:41.875Z (1320 sec) - Send timeout to LGE-LG-D722_PT4588

2015-11-23T11:56:41.876Z (1320 sec) - Send timeout to samsung-SM-G900F_PT3613

2015-11-23T11:56:41.877Z (1320 sec) - Send timeout to samsung-SM-G800F_PT9160
2015-11-23T11:56:41.877Z (1320 sec) - Send timeout to LGE-Nexus 5_PT3069

2015-11-23T11:56:41.878Z (1320 sec) - Send timeout to motorola-XT1039_PT6969

2015-11-23T11:57:41.887Z (1380 sec) - Did not get reports from all devices, but forcing tests to finish!

samsung-SM-A500FU_PT3363 did not have results at the end of tests - check the device logs about why!!

LGE-LG-H815_PT3952 did not have results at the end of tests - check the device logs about why!!

LGE-LG-D855_PT626 did not have results at the end of tests - check the device logs about why!!

samsung-SM-N910C_PT6816 did not have results at the end of tests - check the device logs about why!!

motorola-XT1072_PT5877 did not have results at the end of tests - check the device logs about why!!
samsung-SM-A300FU_PT5957 did not have results at the end of tests - check the device logs about why!!

HTC-HTC Desire 820_PT9241 did not have results at the end of tests - check the device logs about why!!

LGE-LG-D722_PT4588 did not have results at the end of tests - check the device logs about why!!
samsung-SM-G900F_PT3613 did not have results at the end of tests - check the device logs about why!!

samsung-SM-G800F_PT9160 did not have results at the end of tests - check the device logs about why!!
LGE-Nexus 5_PT3069 did not have results at the end of tests - check the device logs about why!!

motorola-XT1039_PT6969 did not have results at the end of tests - check the device logs about why!!

2015-11-23T11:57:41.904Z (1380 sec) - Android All tests are done, preparing test report

--------------- test report ---------------------
--------------- motorola-Nexus 6_PT8557 --------------------- : 1

sendList : 100% : 70612 ms, 99% : 70612 ms, 95 : 32710 ms, 90% : 32710 ms.
Result count 11, range 4433 ms to  70612 ms.
sendList failed peers count : 6 [35.294117647058826 %]

- Peer ID : 44:80:EB:7B:5A:05, Tried : 2
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-N9005_PT7498 --------------------- : 2
sendList : 100% : 114004 ms, 99% : 114004 ms, 95 : 114004 ms, 90% : 114004 ms.
Result count 5, range 1826 ms to  114004 ms.
sendList failed peers count : 7 [58.333333333333336 %]
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1

- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
sendList never tried peers count : 5 [29.41176470588235 %]
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 00:F4:6F:30:E0:6C
--------------- LGE-Nexus 5_PT910 --------------------- : 3
sendList : 100% : 46975 ms, 99% : 46975 ms, 95 : 22734 ms, 90% : 22734 ms.
Result count 14, range 1818 ms to  46975 ms.
sendList failed peers count : 3 [17.647058823529413 %]
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 4
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 3
- Peer ID : 44:80:EB:7B:5A:05, Tried : 4
sendList never tried peers count : 0 [0 %]
--------------- HTC-HTC One_M8_PT699 --------------------- : 4
sendList : 100% : 137719 ms, 99% : 137719 ms, 95 : 93434 ms, 90% : 93434 ms.
Result count 15, range 2180 ms to  137719 ms.
sendList failed peers count : 2 [11.764705882352942 %]
- Peer ID : 44:80:EB:7B:5A:05, Tried : 6
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- HUAWEI-ALE-L21_PT6669 --------------------- : 5

sendList : 100% : 101010 ms, 99% : 101010 ms, 95 : 89495 ms, 90% : 89495 ms.
Result count 14, range 5017 ms to  101010 ms.
sendList failed peers count : 3 [17.647058823529413 %]
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 3
- Peer ID : F8:95:C7:87:85:54, Tried : 2
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 2

sendList never tried peers count : 0 [0 %]
--------------- HTC-HTC Desire 820_PT5500 --------------------- : 6
sendList : 100% : 142241 ms, 99% : 142241 ms, 95 : 82651 ms, 90% : 82651 ms.
Result count 11, range 3841 ms to  142241 ms.
sendList failed peers count : 6 [35.294117647058826 %]
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 2

- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 2
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 2
sendList never tried peers count : 0 [0 %]

--------------- Combined ---------------------

sendList : 100% : 142241 ms, 99% : 137719 ms, 95 : 101010 ms, 90% : 82602 ms.

--------------- end of test report ---------------------

too late arrival


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m


android : Error: Command failed: CopyLog Failed (thali02): scp: /home/pi/*.json: No such file or directory

CopyLog Failed (thali01): scp: /home/pi/*.json: No such file or directory

CopyLog Failed (thali09): scp: /home/pi/*.json: No such file or directory

CopyLog Failed (thali08): ssh: connect to host 192.168.1.57 port 22: Connection refused

CopyLog Failed (thali07): scp: /home/pi/*.json: No such file or directory

CopyLog Failed (thali05): scp: /home/pi/*.json: No such file or directory

CopyLog Failed (thali06): scp: /home/pi/*.json: No such file or directory

Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!CopyLog Failed (thali02): scp: /home/pi/*.json: No such file or directory

CopyLog Failed (thali01): scp: /home/pi/*.json: No such file or directory

CopyLog Failed (thali09): scp: /home/pi/*.json: No such file or directory

CopyLog Failed (thali08): ssh: connect to host 192.168.1.57 port 22: Connection refused

CopyLog Failed (thali07): scp: /home/pi/*.json: No such file or directory

CopyLog Failed (thali05): scp: /home/pi/*.json: No such file or directory

CopyLog Failed (thali06): scp: /home/pi/*.json: No such file or directory


```
###Android Logs
####Node name: thali01
####Node name: thali02
####Node name: thali03
Console output:
```
Error! Unexpected exit on device TA4750HV7I app:com.test.thalitest code:0 
child process exited with code 0 on device TA4750HV7I 
Error! Unexpected exit on device LGD8553bed2d08 app:com.test.thalitest code:0 
child process exited with code 0 on device LGD8553bed2d08 
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:0 
child process exited with code 0 on device 320414cd475f91e3 
Android task is completed 
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/513350289b9c5d6_Work_in_progress__vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/513350289b9c5d6_Work_in_progress__vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/513350289b9c5d6_Work_in_progress__vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:null 
child process exited with code null on device ZX1C223JKW 
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Error! Unexpected exit on device 0be0c6c6 app:com.test.thalitest code:null 
child process exited with code null on device 0be0c6c6 
Android task is completed 
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/513350289b9c5d6_Work_in_progress__vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/513350289b9c5d6_Work_in_progress__vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/513350289b9c5d6_Work_in_progress__vjrantal/thali04_samsung-SM-G900F.md)

####Node name: thali05
####Node name: thali06
####Node name: thali07
####Node name: thali08
####Node name: thali09



###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/513350289b9c5d6_Work_in_progress__vjrantal/iOS_Iphone5-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/513350289b9c5d6_Work_in_progress__vjrantal/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/513350289b9c5d6_Work_in_progress__vjrantal/iOS_Iphone6-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/513350289b9c5d6_Work_in_progress__vjrantal/iOS_IpadAir2-1.md)


#### Integration Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":18}}
Test ID 0 configuration: testSendData.js, server timeout: 1200000, data:

{ timeout: '1000000',
  rounds: '1',
  dataTimeout: '10000',
  dataAmount: '100000',
  conReTryTimeout: '5000',
  conReTryCount: '5' }

2015-11-23T11:34:41.787Z (0 sec) - Android tests will start after waiting for 120 seconds

Test ID 0 configuration: testSendData.js, server timeout: 1200000, data:

{ timeout: '1000000',
  rounds: '1',
  dataTimeout: '10000',
  dataAmount: '100000',
  conReTryTimeout: '5000',
  conReTryCount: '5' }

2015-11-23T11:34:41.793Z (0 sec) - iOS tests will start after waiting for 120 seconds

listening on *:3000

2015-11-23T11:34:42.295Z (1 sec) - Android samsung-SM-A500FU_PT3363 added (current device count 1)

2015-11-23T11:34:42.320Z (1 sec) - Android LGE-LG-H815_PT3952 added (current device count 2)

2015-11-23T11:34:42.336Z (1 sec) - Android LGE-LG-D855_PT626 added (current device count 3)

2015-11-23T11:34:42.494Z (1 sec) - Android motorola-Nexus 6_PT8557 added (current device count 4)

2015-11-23T11:34:43.039Z (1 sec) - Android samsung-SM-N9005_PT7498 added (current device count 5)

2015-11-23T11:34:43.085Z (1 sec) - Android LGE-Nexus 5_PT910 added (current device count 6)

2015-11-23T11:34:43.315Z (2 sec) - iOS Apple-Iphone6-1_PT7664 added (current device count 1)

2015-11-23T11:34:43.365Z (2 sec) - iOS Apple-Iphone5s-1_PT8005 added (current device count 2)

2015-11-23T11:34:43.615Z (2 sec) - Android samsung-SM-N910C_PT6816 added (current device count 7)

2015-11-23T11:34:43.792Z (2 sec) - Android motorola-XT1072_PT5877 added (current device count 8)

2015-11-23T11:34:44.433Z (3 sec) - Android samsung-SM-A300FU_PT5957 added (current device count 9)

2015-11-23T11:34:44.943Z (3 sec) - Android HTC-HTC One_M8_PT699 added (current device count 10)

2015-11-23T11:34:45.292Z (4 sec) - Android HTC-HTC Desire 820_PT9241 added (current device count 11)

2015-11-23T11:34:45.929Z (4 sec) - Android LGE-LG-D722_PT4588 added (current device count 12)

2015-11-23T11:34:46.162Z (4 sec) - iOS Apple-Iphone5-1_PT142 added (current device count 3)

2015-11-23T11:34:46.361Z (5 sec) - Android samsung-SM-G900F_PT3613 added (current device count 13)

2015-11-23T11:34:46.699Z (5 sec) - Android HUAWEI-ALE-L21_PT6669 added (current device count 14)

2015-11-23T11:34:46.702Z (5 sec) - Android samsung-SM-G800F_PT9160 added (current device count 15)

2015-11-23T11:34:46.763Z (5 sec) - iOS Apple-IpadAir2-1_PT6529 added (current device count 4)

2015-11-23T11:34:46.866Z (5 sec) - Android LGE-Nexus 5_PT3069 added (current device count 16)

2015-11-23T11:34:46.886Z (5 sec) - Android HTC-HTC Desire 820_PT5500 added (current device count 17)

2015-11-23T11:35:08.239Z (26 sec) - Android motorola-XT1039_PT6969 added (current device count 18)

-------------- We got wait done, now starting the testing process ------------------

2015-11-23T11:36:41.837Z (120 sec) - Android start testing now with 18 devices

2015-11-23T11:36:41.865Z (120 sec) - iOS start testing now with 4 devices

2015-11-23T11:36:53.674Z (132 sec) - iOS Apple-Iphone6-1_PT7664 test took 11808ms - results peers[0], reConnects[0], sendData[3]

2015-11-23T11:36:54.250Z (133 sec) - iOS Apple-Iphone5-1_PT142 test took 12384ms - results peers[0], reConnects[0], sendData[3]

2015-11-23T11:36:55.675Z (134 sec) - iOS Apple-Iphone5s-1_PT8005 test took 13809ms - results peers[0], reConnects[0], sendData[3]

2015-11-23T11:36:59.679Z (138 sec) - iOS Apple-IpadAir2-1_PT6529 test took 17811ms - results peers[0], reConnects[0], sendData[3]

2015-11-23T11:36:59.681Z (138 sec) - iOS test ID 0 done now

2015-11-23T11:36:59.702Z (138 sec) - iOS All tests are done, preparing test report

--------------- test report ---------------------

--------------- Apple-Iphone6-1_PT7664 --------------------- : 1

sendList : 100% : 4200 ms, 99% : 4200 ms, 95 : 4200 ms, 90% : 4200 ms.

Result count 3, range 2857 ms to  4200 ms.

sendList failed peers count : 0 [0 %]

sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5s-1_PT8005 --------------------- : 2
sendList : 100% : 4725 ms, 99% : 4725 ms, 95 : 4725 ms, 90% : 4725 ms.

Result count 3, range 3704 ms to  4725 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5-1_PT142 --------------------- : 3
sendList : 100% : 5067 ms, 99% : 5067 ms, 95 : 5067 ms, 90% : 5067 ms.
Result count 3, range 2877 ms to  5067 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- Apple-IpadAir2-1_PT6529 --------------------- : 4
sendList : 100% : 8751 ms, 99% : 8751 ms, 95 : 8751 ms, 90% : 8751 ms.
Result count 3, range 3192 ms to  8751 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------

sendList : 100% : 8751 ms, 99% : 8751 ms, 95 : 5174 ms, 90% : 5174 ms.

--------------- end of test report ---------------------

2015-11-23T11:37:52.116Z (190 sec) - Android LGE-Nexus 5_PT3069 got disconnected

2015-11-23T11:37:54.959Z (193 sec) - Android motorola-XT1072_PT5877 got re-connected event

2015-11-23T11:37:55.832Z (194 sec) - Android HTC-HTC Desire 820_PT5500 got disconnected

2015-11-23T11:38:13.807Z (212 sec) - Android samsung-SM-N910C_PT6816 got disconnected

2015-11-23T11:38:38.928Z (237 sec) - Android motorola-XT1039_PT6969 got disconnected

2015-11-23T11:38:39.411Z (238 sec) - Android motorola-XT1039_PT6969 got re-connected event

2015-11-23T11:38:51.133Z (249 sec) - Android motorola-XT1072_PT5877 got disconnected

2015-11-23T11:39:02.839Z (261 sec) - Android LGE-LG-H815_PT3952 got disconnected

2015-11-23T11:39:05.212Z (263 sec) - Android samsung-SM-A300FU_PT5957 got disconnected

2015-11-23T11:39:08.719Z (267 sec) - Android samsung-SM-G800F_PT9160 got disconnected

2015-11-23T11:39:20.907Z (279 sec) - Android motorola-Nexus 6_PT8557 got re-connected event

2015-11-23T11:39:44.837Z (303 sec) - Android motorola-XT1072_PT5877 got disconnected

2015-11-23T11:39:53.496Z (312 sec) - Android LGE-LG-D722_PT4588 got re-connected event

2015-11-23T11:40:18.596Z (337 sec) - Android motorola-Nexus 6_PT8557 got disconnected

2015-11-23T11:40:29.933Z (348 sec) - Android motorola-Nexus 6_PT8557 got re-connected event

2015-11-23T11:40:46.814Z (365 sec) - Android LGE-LG-D722_PT4588 got disconnected

2015-11-23T11:41:33.935Z (412 sec) - Android motorola-Nexus 6_PT8557 got disconnected

2015-11-23T11:41:35.956Z (414 sec) - Android LGE-LG-D855_PT626 got disconnected

2015-11-23T11:42:15.850Z (454 sec) - Android motorola-XT1039_PT6969 got disconnected

2015-11-23T11:42:34.214Z (472 sec) - Android LGE-LG-D722_PT4588 got disconnected

2015-11-23T11:43:57.961Z (556 sec) - Android HTC-HTC Desire 820_PT9241 got disconnected

2015-11-23T11:44:40.356Z (599 sec) - Android samsung-SM-A500FU_PT3363 got disconnected

2015-11-23T11:44:59.995Z (618 sec) - Android samsung-SM-G900F_PT3613 got disconnected

2015-11-23T11:48:54.397Z (853 sec) - Android HTC-HTC Desire 820_PT5500 got re-connected event

2015-11-23T11:53:22.146Z (1120 sec) - Android samsung-SM-N9005_PT7498 test took 1000295ms - results peers[0], reConnects[0], sendData[17]

2015-11-23T11:53:22.261Z (1121 sec) - Android HTC-HTC One_M8_PT699 test took 1000406ms - results peers[0], reConnects[0], sendData[17]

2015-11-23T11:53:22.745Z (1121 sec) - Android LGE-Nexus 5_PT910 test took 1000893ms - results peers[0], reConnects[0], sendData[17]

2015-11-23T11:53:23.636Z (1122 sec) - Android HUAWEI-ALE-L21_PT6669 test took 1001779ms - results peers[0], reConnects[0], sendData[17]

2015-11-23T11:53:34.291Z (1133 sec) - Android motorola-Nexus 6_PT8557 got re-connected event

2015-11-23T11:53:34.313Z (1133 sec) - Android motorola-Nexus 6_PT8557 test took 1012463ms - results peers[0], reConnects[0], sendData[17]

2015-11-23T11:54:07.191Z (1165 sec) - Android HTC-HTC Desire 820_PT5500 got disconnected

2015-11-23T11:54:26.915Z (1185 sec) - Android motorola-Nexus 6_PT8557 got disconnected

2015-11-23T11:55:00.157Z (1218 sec) - Android HTC-HTC Desire 820_PT5500 got re-connected event

2015-11-23T11:55:00.171Z (1218 sec) - Android HTC-HTC Desire 820_PT5500 test took 1098311ms - results peers[0], reConnects[0], sendData[17]

2015-11-23T11:56:41.869Z (1320 sec) - Server timeout reached!

2015-11-23T11:56:41.871Z (1320 sec) - Send timeout to samsung-SM-A500FU_PT3363

2015-11-23T11:56:41.872Z (1320 sec) - Send timeout to LGE-LG-H815_PT3952

2015-11-23T11:56:41.873Z (1320 sec) - Send timeout to LGE-LG-D855_PT626

2015-11-23T11:56:41.873Z (1320 sec) - Send timeout to samsung-SM-N910C_PT6816

2015-11-23T11:56:41.874Z (1320 sec) - Send timeout to motorola-XT1072_PT5877

2015-11-23T11:56:41.874Z (1320 sec) - Send timeout to samsung-SM-A300FU_PT5957

2015-11-23T11:56:41.875Z (1320 sec) - Send timeout to HTC-HTC Desire 820_PT9241

2015-11-23T11:56:41.875Z (1320 sec) - Send timeout to LGE-LG-D722_PT4588

2015-11-23T11:56:41.876Z (1320 sec) - Send timeout to samsung-SM-G900F_PT3613

2015-11-23T11:56:41.877Z (1320 sec) - Send timeout to samsung-SM-G800F_PT9160
2015-11-23T11:56:41.877Z (1320 sec) - Send timeout to LGE-Nexus 5_PT3069

2015-11-23T11:56:41.878Z (1320 sec) - Send timeout to motorola-XT1039_PT6969

2015-11-23T11:57:41.887Z (1380 sec) - Did not get reports from all devices, but forcing tests to finish!

samsung-SM-A500FU_PT3363 did not have results at the end of tests - check the device logs about why!!

LGE-LG-H815_PT3952 did not have results at the end of tests - check the device logs about why!!

LGE-LG-D855_PT626 did not have results at the end of tests - check the device logs about why!!

samsung-SM-N910C_PT6816 did not have results at the end of tests - check the device logs about why!!

motorola-XT1072_PT5877 did not have results at the end of tests - check the device logs about why!!
samsung-SM-A300FU_PT5957 did not have results at the end of tests - check the device logs about why!!

HTC-HTC Desire 820_PT9241 did not have results at the end of tests - check the device logs about why!!

LGE-LG-D722_PT4588 did not have results at the end of tests - check the device logs about why!!
samsung-SM-G900F_PT3613 did not have results at the end of tests - check the device logs about why!!

samsung-SM-G800F_PT9160 did not have results at the end of tests - check the device logs about why!!
LGE-Nexus 5_PT3069 did not have results at the end of tests - check the device logs about why!!

motorola-XT1039_PT6969 did not have results at the end of tests - check the device logs about why!!

2015-11-23T11:57:41.904Z (1380 sec) - Android All tests are done, preparing test report

--------------- test report ---------------------
--------------- motorola-Nexus 6_PT8557 --------------------- : 1

sendList : 100% : 70612 ms, 99% : 70612 ms, 95 : 32710 ms, 90% : 32710 ms.
Result count 11, range 4433 ms to  70612 ms.
sendList failed peers count : 6 [35.294117647058826 %]

- Peer ID : 44:80:EB:7B:5A:05, Tried : 2
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-N9005_PT7498 --------------------- : 2
sendList : 100% : 114004 ms, 99% : 114004 ms, 95 : 114004 ms, 90% : 114004 ms.
Result count 5, range 1826 ms to  114004 ms.
sendList failed peers count : 7 [58.333333333333336 %]
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 1

- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 1
sendList never tried peers count : 5 [29.41176470588235 %]
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 00:F4:6F:30:E0:6C
--------------- LGE-Nexus 5_PT910 --------------------- : 3
sendList : 100% : 46975 ms, 99% : 46975 ms, 95 : 22734 ms, 90% : 22734 ms.
Result count 14, range 1818 ms to  46975 ms.
sendList failed peers count : 3 [17.647058823529413 %]
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 4
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 3
- Peer ID : 44:80:EB:7B:5A:05, Tried : 4
sendList never tried peers count : 0 [0 %]
--------------- HTC-HTC One_M8_PT699 --------------------- : 4
sendList : 100% : 137719 ms, 99% : 137719 ms, 95 : 93434 ms, 90% : 93434 ms.
Result count 15, range 2180 ms to  137719 ms.
sendList failed peers count : 2 [11.764705882352942 %]
- Peer ID : 44:80:EB:7B:5A:05, Tried : 6
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- HUAWEI-ALE-L21_PT6669 --------------------- : 5

sendList : 100% : 101010 ms, 99% : 101010 ms, 95 : 89495 ms, 90% : 89495 ms.
Result count 14, range 5017 ms to  101010 ms.
sendList failed peers count : 3 [17.647058823529413 %]
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 3
- Peer ID : F8:95:C7:87:85:54, Tried : 2
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 2

sendList never tried peers count : 0 [0 %]
--------------- HTC-HTC Desire 820_PT5500 --------------------- : 6
sendList : 100% : 142241 ms, 99% : 142241 ms, 95 : 82651 ms, 90% : 82651 ms.
Result count 11, range 3841 ms to  142241 ms.
sendList failed peers count : 6 [35.294117647058826 %]
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 2

- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 2
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 2
sendList never tried peers count : 0 [0 %]

--------------- Combined ---------------------

sendList : 100% : 142241 ms, 99% : 137719 ms, 95 : 101010 ms, 90% : 82602 ms.

--------------- end of test report ---------------------

too late arrival


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


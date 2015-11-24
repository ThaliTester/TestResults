#### Test 5133502860beea6 Logs

Status: 
```

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
true


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

2015-11-24T10:39:34.122Z (0 sec) - Android tests will start after waiting for 120 seconds

Test ID 0 configuration: testSendData.js, server timeout: 1200000, data:

{ timeout: '1000000',
  rounds: '1',
  dataTimeout: '10000',
  dataAmount: '100000',
  conReTryTimeout: '5000',
  conReTryCount: '5' }

2015-11-24T10:39:34.128Z (0 sec) - iOS tests will start after waiting for 120 seconds

listening on *:3000

2015-11-24T10:39:34.506Z (0 sec) - Android samsung-SM-N910C_PT5955 added (current device count 1)

2015-11-24T10:39:34.541Z (0 sec) - Android LGE-LG-H815_PT8697 added (current device count 2)

2015-11-24T10:39:34.644Z (1 sec) - Android HTC-HTC One M8s_PT4125 added (current device count 3)

2015-11-24T10:39:34.722Z (1 sec) - Android samsung-SM-A300FU_PT2678 added (current device count 4)

2015-11-24T10:39:34.766Z (1 sec) - Android HTC-HTC One_M8_PT5312 added (current device count 5)

2015-11-24T10:39:34.977Z (1 sec) - Android LGE-Nexus 5_PT6925 added (current device count 6)

2015-11-24T10:39:35.412Z (1 sec) - Android samsung-SM-A500FU_PT3547 added (current device count 7)

2015-11-24T10:39:36.238Z (2 sec) - Android motorola-Nexus 6_PT1620 added (current device count 8)

2015-11-24T10:39:36.462Z (2 sec) - Android samsung-SM-N9005_PT6575 added (current device count 9)

2015-11-24T10:39:37.724Z (4 sec) - Android LGE-LG-D722_PT1372 added (current device count 10)

2015-11-24T10:39:38.082Z (4 sec) - Android samsung-SM-G900F_PT1757 added (current device count 11)

2015-11-24T10:39:38.607Z (5 sec) - Android motorola-XT1072_PT8689 added (current device count 12)

2015-11-24T10:39:38.814Z (5 sec) - Android HUAWEI-ALE-L21_PT1941 added (current device count 13)

2015-11-24T10:39:39.210Z (5 sec) - Android samsung-SM-A300FU_PT7769 added (current device count 14)

2015-11-24T10:39:39.319Z (5 sec) - Android samsung-SM-G800F_PT6835 added (current device count 15)

2015-11-24T10:39:41.001Z (7 sec) - Android HTC-HTC Desire 820_PT6481 added (current device count 16)

2015-11-24T10:39:46.769Z (13 sec) - Android motorola-XT1039_PT179 added (current device count 17)

-------------- We got wait done, now starting the testing process ------------------

2015-11-24T10:41:34.162Z (120 sec) - Android start testing now with 17 devices

2015-11-24T10:43:32.920Z (239 sec) - Android LGE-LG-D722_PT1372 got disconnected

2015-11-24T10:44:19.815Z (286 sec) - Android samsung-SM-N910C_PT5955 got disconnected

2015-11-24T10:44:31.565Z (297 sec) - Android HTC-HTC Desire 820_PT6481 got disconnected

2015-11-24T10:44:44.536Z (310 sec) - Android samsung-SM-N9005_PT6575 test took 190356ms - results peers[0], reConnects[0], sendData[16]

2015-11-24T10:45:00.114Z (326 sec) - Android HTC-HTC Desire 820_PT6481 got re-connected event

2015-11-24T10:46:08.417Z (394 sec) - Android samsung-SM-A300FU_PT7769 got disconnected

2015-11-24T10:46:52.095Z (438 sec) - Android samsung-SM-N9005_PT6575 got disconnected

2015-11-24T10:47:30.933Z (477 sec) - Android samsung-SM-G800F_PT6835 got disconnected

2015-11-24T10:51:18.602Z (705 sec) - Android HTC-HTC One M8s_PT4125 got disconnected

2015-11-24T10:56:46.077Z (1032 sec) - Android samsung-SM-A300FU_PT2678 got disconnected

2015-11-24T10:58:14.708Z (1121 sec) - Android LGE-Nexus 5_PT6925 test took 1000531ms - results peers[0], reConnects[0], sendData[16]

2015-11-24T10:58:14.744Z (1121 sec) - Android HTC-HTC One_M8_PT5312 test took 1000569ms - results peers[0], reConnects[0], sendData[16]

2015-11-24T10:58:14.787Z (1121 sec) - Android samsung-SM-G900F_PT1757 test took 1000607ms - results peers[0], reConnects[0], sendData[16]

2015-11-24T10:58:15.060Z (1121 sec) - Android motorola-Nexus 6_PT1620 test took 1000882ms - results peers[0], reConnects[0], sendData[16]

2015-11-24T10:58:15.062Z (1121 sec) - Android motorola-XT1039_PT179 test took 1000875ms - results peers[0], reConnects[0], sendData[16]

2015-11-24T10:58:15.227Z (1121 sec) - Android motorola-XT1072_PT8689 test took 1001046ms - results peers[0], reConnects[0], sendData[16]

2015-11-24T10:58:15.396Z (1121 sec) - Android samsung-SM-A500FU_PT3547 test took 1001220ms - results peers[0], reConnects[0], sendData[16]

2015-11-24T10:58:15.588Z (1122 sec) - Android LGE-LG-H815_PT8697 test took 1001415ms - results peers[0], reConnects[0], sendData[16]

2015-11-24T10:58:15.593Z (1122 sec) - Android HUAWEI-ALE-L21_PT1941 test took 1001412ms - results peers[0], reConnects[0], sendData[16]

2015-11-24T10:58:25.639Z (1132 sec) - Android HTC-HTC Desire 820_PT6481 test took 1011453ms - results peers[0], reConnects[0], sendData[16]

2015-11-24T11:01:34.194Z (1320 sec) - Server timeout reached!

2015-11-24T11:01:34.200Z (1320 sec) - Send timeout to samsung-SM-N910C_PT5955

2015-11-24T11:01:34.201Z (1320 sec) - Send timeout to HTC-HTC One M8s_PT4125
2015-11-24T11:01:34.202Z (1320 sec) - Send timeout to samsung-SM-A300FU_PT2678

2015-11-24T11:01:34.203Z (1320 sec) - Send timeout to LGE-LG-D722_PT1372

2015-11-24T11:01:34.204Z (1320 sec) - Send timeout to samsung-SM-A300FU_PT7769
2015-11-24T11:01:34.205Z (1320 sec) - Send timeout to samsung-SM-G800F_PT6835

2015-11-24T11:02:34.207Z (1380 sec) - Did not get reports from all devices, but forcing tests to finish!

samsung-SM-N910C_PT5955 did not have results at the end of tests - check the device logs about why!!

HTC-HTC One M8s_PT4125 did not have results at the end of tests - check the device logs about why!!

samsung-SM-A300FU_PT2678 did not have results at the end of tests - check the device logs about why!!

LGE-LG-D722_PT1372 did not have results at the end of tests - check the device logs about why!!

samsung-SM-A300FU_PT7769 did not have results at the end of tests - check the device logs about why!!

samsung-SM-G800F_PT6835 did not have results at the end of tests - check the device logs about why!!

2015-11-24T11:02:34.227Z (1380 sec) - Android All tests are done, preparing test report

--------------- test report ---------------------

--------------- LGE-LG-H815_PT8697 --------------------- : 1

sendList : 100% : 57551 ms, 99% : 57551 ms, 95 : 49613 ms, 90% : 49613 ms.

Result count 11, range 3048 ms to  57551 ms.

sendList failed peers count : 5 [31.25 %]

- Peer ID : 58:2A:F7:ED:96:BE, Tried : 2
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1

- Peer ID : E0:DB:10:14:E2:C0, Tried : 2
- Peer ID : F8:95:C7:87:85:54, Tried : 2
- Peer ID : 08:EC:A9:50:76:27, Tried : 2
sendList never tried peers count : 0 [0 %]

--------------- HTC-HTC One_M8_PT5312 --------------------- : 2

sendList : 100% : 106464 ms, 99% : 106464 ms, 95 : 106464 ms, 90% : 35540 ms.

Result count 10, range 4513 ms to  106464 ms.
sendList failed peers count : 6 [37.5 %]
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 2

- Peer ID : E0:DB:10:14:E2:C0, Tried : 2
- Peer ID : 08:EC:A9:50:76:27, Tried : 2
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 2
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 2

- Peer ID : F8:95:C7:87:85:54, Tried : 2
sendList never tried peers count : 0 [0 %]

--------------- LGE-Nexus 5_PT6925 --------------------- : 3
sendList : 100% : 104973 ms, 99% : 104973 ms, 95 : 68175 ms, 90% : 68175 ms.

Result count 11, range 4011 ms to  104973 ms.
sendList failed peers count : 5 [31.25 %]
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 3
- Peer ID : F8:95:C7:87:85:54, Tried : 2

- Peer ID : E0:DB:10:14:E2:C0, Tried : 2
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 2
- Peer ID : 08:EC:A9:50:76:27, Tried : 3
sendList never tried peers count : 0 [0 %]

--------------- samsung-SM-A500FU_PT3547 --------------------- : 4
sendList : 100% : 120638 ms, 99% : 120638 ms, 95 : 55949 ms, 90% : 55949 ms.

Result count 13, range 2117 ms to  120638 ms.
sendList failed peers count : 3 [18.75 %]
- Peer ID : 08:EC:A9:50:76:27, Tried : 4

- Peer ID : F8:95:C7:87:85:54, Tried : 3
- Peer ID : E0:DB:10:14:E2:C0, Tried : 3
sendList never tried peers count : 0 [0 %]

--------------- motorola-Nexus 6_PT1620 --------------------- : 5
sendList : 100% : 64727 ms, 99% : 64727 ms, 95 : 64727 ms, 90% : 29443 ms.
Result count 9, range 2107 ms to  64727 ms.
sendList failed peers count : 7 [43.75 %]

- Peer ID : 90:E7:C4:F6:69:77, Tried : 2
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1

- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1

sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-N9005_PT6575 --------------------- : 6
sendList : 100% : 37767 ms, 99% : 37767 ms, 95 : 20060 ms, 90% : 20011 ms.

Result count 16, range 2079 ms to  37767 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-G900F_PT1757 --------------------- : 7

sendList : 100% : 94022 ms, 99% : 94022 ms, 95 : 55069 ms, 90% : 55069 ms.
Result count 14, range 1884 ms to  94022 ms.

sendList failed peers count : 2 [12.5 %]
- Peer ID : E0:DB:10:14:E2:C0, Tried : 6
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- motorola-XT1072_PT8689 --------------------- : 8
sendList : 100% : 152534 ms, 99% : 152534 ms, 95 : 91545 ms, 90% : 91545 ms.
Result count 11, range 2756 ms to  152534 ms.

sendList failed peers count : 5 [31.25 %]
- Peer ID : 08:EC:A9:50:76:27, Tried : 2
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1

- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 2
- Peer ID : F8:95:C7:87:85:54, Tried : 2
sendList never tried peers count : 0 [0 %]

--------------- HUAWEI-ALE-L21_PT1941 --------------------- : 9
sendList : 100% : 65159 ms, 99% : 65159 ms, 95 : 65159 ms, 90% : 44913 ms.
Result count 9, range 2669 ms to  65159 ms.

sendList failed peers count : 5 [35.714285714285715 %]
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1

- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
sendList never tried peers count : 2 [12.5 %]

- Peer ID : F8:95:C7:87:85:54

- Peer ID : E0:DB:10:1F:C9:5E
--------------- HTC-HTC Desire 820_PT6481 --------------------- : 10
sendList : 100% : 89180 ms, 99% : 89180 ms, 95 : 89180 ms, 90% : 30755 ms.

Result count 10, range 1300 ms to  89180 ms.
sendList failed peers count : 6 [37.5 %]
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 2

- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 2
- Peer ID : 08:EC:A9:50:76:27, Tried : 2
- Peer ID : E0:DB:10:14:E2:C0, Tried : 2

- Peer ID : 00:F4:6F:30:E0:6C, Tried : 2
sendList never tried peers count : 0 [0 %]
--------------- motorola-XT1039_PT179 --------------------- : 11

sendList : 100% : 87294 ms, 99% : 87294 ms, 95 : 51774 ms, 90% : 51774 ms.

Result count 12, range 2767 ms to  87294 ms.
sendList failed peers count : 4 [25 %]
- Peer ID : F8:95:C7:87:85:54, Tried : 4
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 3
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 3

- Peer ID : E0:DB:10:14:E2:C0, Tried : 3
sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------

sendList : 100% : 152534 ms, 99% : 120638 ms, 95 : 89180 ms, 90% : 55949 ms.

--------------- end of test report ---------------------


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```
###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/5133502860beea6_Work_in_progress__vjrantal/iOS_Iphone5-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/5133502860beea6_Work_in_progress__vjrantal/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/5133502860beea6_Work_in_progress__vjrantal/iOS_Iphone6-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/5133502860beea6_Work_in_progress__vjrantal/iOS_IpadAir2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/5133502860beea6_Work_in_progress__vjrantal/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  f56ad48d Test has  SUCCEEDED
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
STOP log received from  W3D7N15428022572 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Device test finished on f56ad48d 
Device test finished on W3D7N15428022572 
Android task is completed. [SUCCESS]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/5133502860beea6_Work_in_progress__vjrantal/thali01_LGE-LG-H815.md)

[HUAWEI-ALE-L21](https://github.com/ThaliTester/TestResults/blob/5133502860beea6_Work_in_progress__vjrantal/thali01_HUAWEI-ALE-L21.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/5133502860beea6_Work_in_progress__vjrantal/thali01_samsung-SM-A500FU.md)

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
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/5133502860beea6_Work_in_progress__vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/5133502860beea6_Work_in_progress__vjrantal/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/5133502860beea6_Work_in_progress__vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/5133502860beea6_Work_in_progress__vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/5133502860beea6_Work_in_progress__vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  0be0c6c6 Test has  SUCCEEDED
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on ZX1C223JKW 
Device test finished on 0be0c6c6 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/5133502860beea6_Work_in_progress__vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/5133502860beea6_Work_in_progress__vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/5133502860beea6_Work_in_progress__vjrantal/thali04_samsung-SM-G900F.md)

####Node name: thali05
Console output:
```
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
STOP log received from  SH47FWM00508 Test has  SUCCEEDED
Device test finished on SH47FWM00508 
Device test finished on ZX1G429CRK 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 1d6a772d app:com.test.thalitest code:null 
child process exited with code null on device 1d6a772d 
Android task is completed. [FAILED]
```
[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/5133502860beea6_Work_in_progress__vjrantal/thali05_samsung-SM-N9005.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/5133502860beea6_Work_in_progress__vjrantal/thali05_motorola-Nexus 6.md)

[HTC-HTC One_M8](https://github.com/ThaliTester/TestResults/blob/5133502860beea6_Work_in_progress__vjrantal/thali05_HTC-HTC One_M8.md)

####Node name: thali06
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:0 
child process exited with code 0 on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:null 
child process exited with code null on device FA55PYS00566 
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:0 
child process exited with code 0 on device 022678fb504e29b0 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/5133502860beea6_Work_in_progress__vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/5133502860beea6_Work_in_progress__vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/5133502860beea6_Work_in_progress__vjrantal/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
Error: problem deploying Android apk(/home/pi/test/builder/builds/5133502860beea6/build_android/android_0_5133502860beea6.apk) to device 4db5c8cc protocol failure
- waiting for device -
rm: /data/local/tmp/android_0_5133502860beea6.apk: No such file or directory



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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/5133502860beea6_Work_in_progress__vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/5133502860beea6_Work_in_progress__vjrantal/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/5133502860beea6_Work_in_progress__vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/5133502860beea6_Work_in_progress__vjrantal/thali09_LGE-Nexus 5.md)




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

2015-11-24T10:39:34.122Z (0 sec) - Android tests will start after waiting for 120 seconds

Test ID 0 configuration: testSendData.js, server timeout: 1200000, data:

{ timeout: '1000000',
  rounds: '1',
  dataTimeout: '10000',
  dataAmount: '100000',
  conReTryTimeout: '5000',
  conReTryCount: '5' }

2015-11-24T10:39:34.128Z (0 sec) - iOS tests will start after waiting for 120 seconds

listening on *:3000

2015-11-24T10:39:34.506Z (0 sec) - Android samsung-SM-N910C_PT5955 added (current device count 1)

2015-11-24T10:39:34.541Z (0 sec) - Android LGE-LG-H815_PT8697 added (current device count 2)

2015-11-24T10:39:34.644Z (1 sec) - Android HTC-HTC One M8s_PT4125 added (current device count 3)

2015-11-24T10:39:34.722Z (1 sec) - Android samsung-SM-A300FU_PT2678 added (current device count 4)

2015-11-24T10:39:34.766Z (1 sec) - Android HTC-HTC One_M8_PT5312 added (current device count 5)

2015-11-24T10:39:34.977Z (1 sec) - Android LGE-Nexus 5_PT6925 added (current device count 6)

2015-11-24T10:39:35.412Z (1 sec) - Android samsung-SM-A500FU_PT3547 added (current device count 7)

2015-11-24T10:39:36.238Z (2 sec) - Android motorola-Nexus 6_PT1620 added (current device count 8)

2015-11-24T10:39:36.462Z (2 sec) - Android samsung-SM-N9005_PT6575 added (current device count 9)

2015-11-24T10:39:37.724Z (4 sec) - Android LGE-LG-D722_PT1372 added (current device count 10)

2015-11-24T10:39:38.082Z (4 sec) - Android samsung-SM-G900F_PT1757 added (current device count 11)

2015-11-24T10:39:38.607Z (5 sec) - Android motorola-XT1072_PT8689 added (current device count 12)

2015-11-24T10:39:38.814Z (5 sec) - Android HUAWEI-ALE-L21_PT1941 added (current device count 13)

2015-11-24T10:39:39.210Z (5 sec) - Android samsung-SM-A300FU_PT7769 added (current device count 14)

2015-11-24T10:39:39.319Z (5 sec) - Android samsung-SM-G800F_PT6835 added (current device count 15)

2015-11-24T10:39:41.001Z (7 sec) - Android HTC-HTC Desire 820_PT6481 added (current device count 16)

2015-11-24T10:39:46.769Z (13 sec) - Android motorola-XT1039_PT179 added (current device count 17)

-------------- We got wait done, now starting the testing process ------------------

2015-11-24T10:41:34.162Z (120 sec) - Android start testing now with 17 devices

2015-11-24T10:43:32.920Z (239 sec) - Android LGE-LG-D722_PT1372 got disconnected

2015-11-24T10:44:19.815Z (286 sec) - Android samsung-SM-N910C_PT5955 got disconnected

2015-11-24T10:44:31.565Z (297 sec) - Android HTC-HTC Desire 820_PT6481 got disconnected

2015-11-24T10:44:44.536Z (310 sec) - Android samsung-SM-N9005_PT6575 test took 190356ms - results peers[0], reConnects[0], sendData[16]

2015-11-24T10:45:00.114Z (326 sec) - Android HTC-HTC Desire 820_PT6481 got re-connected event

2015-11-24T10:46:08.417Z (394 sec) - Android samsung-SM-A300FU_PT7769 got disconnected

2015-11-24T10:46:52.095Z (438 sec) - Android samsung-SM-N9005_PT6575 got disconnected

2015-11-24T10:47:30.933Z (477 sec) - Android samsung-SM-G800F_PT6835 got disconnected

2015-11-24T10:51:18.602Z (705 sec) - Android HTC-HTC One M8s_PT4125 got disconnected

2015-11-24T10:56:46.077Z (1032 sec) - Android samsung-SM-A300FU_PT2678 got disconnected

2015-11-24T10:58:14.708Z (1121 sec) - Android LGE-Nexus 5_PT6925 test took 1000531ms - results peers[0], reConnects[0], sendData[16]

2015-11-24T10:58:14.744Z (1121 sec) - Android HTC-HTC One_M8_PT5312 test took 1000569ms - results peers[0], reConnects[0], sendData[16]

2015-11-24T10:58:14.787Z (1121 sec) - Android samsung-SM-G900F_PT1757 test took 1000607ms - results peers[0], reConnects[0], sendData[16]

2015-11-24T10:58:15.060Z (1121 sec) - Android motorola-Nexus 6_PT1620 test took 1000882ms - results peers[0], reConnects[0], sendData[16]

2015-11-24T10:58:15.062Z (1121 sec) - Android motorola-XT1039_PT179 test took 1000875ms - results peers[0], reConnects[0], sendData[16]

2015-11-24T10:58:15.227Z (1121 sec) - Android motorola-XT1072_PT8689 test took 1001046ms - results peers[0], reConnects[0], sendData[16]

2015-11-24T10:58:15.396Z (1121 sec) - Android samsung-SM-A500FU_PT3547 test took 1001220ms - results peers[0], reConnects[0], sendData[16]

2015-11-24T10:58:15.588Z (1122 sec) - Android LGE-LG-H815_PT8697 test took 1001415ms - results peers[0], reConnects[0], sendData[16]

2015-11-24T10:58:15.593Z (1122 sec) - Android HUAWEI-ALE-L21_PT1941 test took 1001412ms - results peers[0], reConnects[0], sendData[16]

2015-11-24T10:58:25.639Z (1132 sec) - Android HTC-HTC Desire 820_PT6481 test took 1011453ms - results peers[0], reConnects[0], sendData[16]

2015-11-24T11:01:34.194Z (1320 sec) - Server timeout reached!

2015-11-24T11:01:34.200Z (1320 sec) - Send timeout to samsung-SM-N910C_PT5955

2015-11-24T11:01:34.201Z (1320 sec) - Send timeout to HTC-HTC One M8s_PT4125
2015-11-24T11:01:34.202Z (1320 sec) - Send timeout to samsung-SM-A300FU_PT2678

2015-11-24T11:01:34.203Z (1320 sec) - Send timeout to LGE-LG-D722_PT1372

2015-11-24T11:01:34.204Z (1320 sec) - Send timeout to samsung-SM-A300FU_PT7769
2015-11-24T11:01:34.205Z (1320 sec) - Send timeout to samsung-SM-G800F_PT6835

2015-11-24T11:02:34.207Z (1380 sec) - Did not get reports from all devices, but forcing tests to finish!

samsung-SM-N910C_PT5955 did not have results at the end of tests - check the device logs about why!!

HTC-HTC One M8s_PT4125 did not have results at the end of tests - check the device logs about why!!

samsung-SM-A300FU_PT2678 did not have results at the end of tests - check the device logs about why!!

LGE-LG-D722_PT1372 did not have results at the end of tests - check the device logs about why!!

samsung-SM-A300FU_PT7769 did not have results at the end of tests - check the device logs about why!!

samsung-SM-G800F_PT6835 did not have results at the end of tests - check the device logs about why!!

2015-11-24T11:02:34.227Z (1380 sec) - Android All tests are done, preparing test report

--------------- test report ---------------------

--------------- LGE-LG-H815_PT8697 --------------------- : 1

sendList : 100% : 57551 ms, 99% : 57551 ms, 95 : 49613 ms, 90% : 49613 ms.

Result count 11, range 3048 ms to  57551 ms.

sendList failed peers count : 5 [31.25 %]

- Peer ID : 58:2A:F7:ED:96:BE, Tried : 2
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1

- Peer ID : E0:DB:10:14:E2:C0, Tried : 2
- Peer ID : F8:95:C7:87:85:54, Tried : 2
- Peer ID : 08:EC:A9:50:76:27, Tried : 2
sendList never tried peers count : 0 [0 %]

--------------- HTC-HTC One_M8_PT5312 --------------------- : 2

sendList : 100% : 106464 ms, 99% : 106464 ms, 95 : 106464 ms, 90% : 35540 ms.

Result count 10, range 4513 ms to  106464 ms.
sendList failed peers count : 6 [37.5 %]
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 2

- Peer ID : E0:DB:10:14:E2:C0, Tried : 2
- Peer ID : 08:EC:A9:50:76:27, Tried : 2
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 2
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 2

- Peer ID : F8:95:C7:87:85:54, Tried : 2
sendList never tried peers count : 0 [0 %]

--------------- LGE-Nexus 5_PT6925 --------------------- : 3
sendList : 100% : 104973 ms, 99% : 104973 ms, 95 : 68175 ms, 90% : 68175 ms.

Result count 11, range 4011 ms to  104973 ms.
sendList failed peers count : 5 [31.25 %]
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 3
- Peer ID : F8:95:C7:87:85:54, Tried : 2

- Peer ID : E0:DB:10:14:E2:C0, Tried : 2
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 2
- Peer ID : 08:EC:A9:50:76:27, Tried : 3
sendList never tried peers count : 0 [0 %]

--------------- samsung-SM-A500FU_PT3547 --------------------- : 4
sendList : 100% : 120638 ms, 99% : 120638 ms, 95 : 55949 ms, 90% : 55949 ms.

Result count 13, range 2117 ms to  120638 ms.
sendList failed peers count : 3 [18.75 %]
- Peer ID : 08:EC:A9:50:76:27, Tried : 4

- Peer ID : F8:95:C7:87:85:54, Tried : 3
- Peer ID : E0:DB:10:14:E2:C0, Tried : 3
sendList never tried peers count : 0 [0 %]

--------------- motorola-Nexus 6_PT1620 --------------------- : 5
sendList : 100% : 64727 ms, 99% : 64727 ms, 95 : 64727 ms, 90% : 29443 ms.
Result count 9, range 2107 ms to  64727 ms.
sendList failed peers count : 7 [43.75 %]

- Peer ID : 90:E7:C4:F6:69:77, Tried : 2
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1

- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1

sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-N9005_PT6575 --------------------- : 6
sendList : 100% : 37767 ms, 99% : 37767 ms, 95 : 20060 ms, 90% : 20011 ms.

Result count 16, range 2079 ms to  37767 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-G900F_PT1757 --------------------- : 7

sendList : 100% : 94022 ms, 99% : 94022 ms, 95 : 55069 ms, 90% : 55069 ms.
Result count 14, range 1884 ms to  94022 ms.

sendList failed peers count : 2 [12.5 %]
- Peer ID : E0:DB:10:14:E2:C0, Tried : 6
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- motorola-XT1072_PT8689 --------------------- : 8
sendList : 100% : 152534 ms, 99% : 152534 ms, 95 : 91545 ms, 90% : 91545 ms.
Result count 11, range 2756 ms to  152534 ms.

sendList failed peers count : 5 [31.25 %]
- Peer ID : 08:EC:A9:50:76:27, Tried : 2
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1

- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : E0:DB:10:14:E2:C0, Tried : 2
- Peer ID : F8:95:C7:87:85:54, Tried : 2
sendList never tried peers count : 0 [0 %]

--------------- HUAWEI-ALE-L21_PT1941 --------------------- : 9
sendList : 100% : 65159 ms, 99% : 65159 ms, 95 : 65159 ms, 90% : 44913 ms.
Result count 9, range 2669 ms to  65159 ms.

sendList failed peers count : 5 [35.714285714285715 %]
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1

- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
sendList never tried peers count : 2 [12.5 %]

- Peer ID : F8:95:C7:87:85:54

- Peer ID : E0:DB:10:1F:C9:5E
--------------- HTC-HTC Desire 820_PT6481 --------------------- : 10
sendList : 100% : 89180 ms, 99% : 89180 ms, 95 : 89180 ms, 90% : 30755 ms.

Result count 10, range 1300 ms to  89180 ms.
sendList failed peers count : 6 [37.5 %]
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 2

- Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
- Peer ID : F8:95:C7:87:85:54, Tried : 2
- Peer ID : 08:EC:A9:50:76:27, Tried : 2
- Peer ID : E0:DB:10:14:E2:C0, Tried : 2

- Peer ID : 00:F4:6F:30:E0:6C, Tried : 2
sendList never tried peers count : 0 [0 %]
--------------- motorola-XT1039_PT179 --------------------- : 11

sendList : 100% : 87294 ms, 99% : 87294 ms, 95 : 51774 ms, 90% : 51774 ms.

Result count 12, range 2767 ms to  87294 ms.
sendList failed peers count : 4 [25 %]
- Peer ID : F8:95:C7:87:85:54, Tried : 4
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 3
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 3

- Peer ID : E0:DB:10:14:E2:C0, Tried : 3
sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------

sendList : 100% : 152534 ms, 99% : 120638 ms, 95 : 89180 ms, 90% : 55949 ms.

--------------- end of test report ---------------------


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


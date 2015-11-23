#### Test 51517283acd5ddf Logs

Status: 
```

ios : false

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m



server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":21}}
Start Android tests : performance tests, start tests with timer

Test[0]: testSendData.js, timeout : 1100000, data : {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"4000","conReTryCount":"1"}
Start iOs tests : performance tests, start tests with timer
Test[0]: testSendData.js, timeout : 1100000, data : {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"4000","conReTryCount":"1"}

listening on *:3000

Android  motorola-XT1039_PT9468 added : 1 sec., device count 1

iOs  Apple-IpadAir2-1_PT4780 added : 1.044 sec., device count 1

iOs  Apple-Iphone5s-1_PT8579 added : 1.784 sec., device count 2

Android  HTC-HTC Desire 820_PT9217 added : 1.788 sec., device count 2

Android  LGE-LG-H815_PT1675 added : 1.845 sec., device count 3

Android  LGE-Nexus 5_PT1820 added : 1.89 sec., device count 4

iOs  Apple-Iphone6-1_PT7067 added : 2.143 sec., device count 3

Android  HTC-HTC Desire 820_PT2743 added : 2.196 sec., device count 5

Android  samsung-SM-N9005_PT6254 added : 2.298 sec., device count 6

Android  HTC-HTC One_M8_PT3699 added : 2.312 sec., device count 7

Android  samsung-SM-A300FU_PT7297 added : 2.435 sec., device count 8

Android  LGE-LG-D722_PT2795 added : 2.442 sec., device count 9

iOs  Apple-Iphone5-1_PT4760 added : 2.81 sec., device count 4

Android  samsung-SM-A500FU_PT5540 added : 3.075 sec., device count 10

Android  samsung-SM-A300FU_PT5861 added : 3.331 sec., device count 11

Android  LGE-LG-D855_PT3303 added : 4.016 sec., device count 12

Android  HUAWEI-ALE-L21_PT9956 added : 4.147 sec., device count 13

Android  LGE-Nexus 5_PT566 added : 4.544 sec., device count 14

Android  LGE-LG-D802_PT7492 added : 4.812 sec., device count 15

Android  samsung-SM-G800F_PT9628 added : 4.978 sec., device count 16

Android  motorola-Nexus 6_PT7032 added : 5.094 sec., device count 17

Android  samsung-SM-N910C_PT1968 added : 6.142 sec., device count 18

Android  motorola-XT1072_PT5629 added : 7.746 sec., device count 19

Android  samsung-SM-G900F_PT2552 added : 8.035 sec., device count 20

-------------- We got wait done, now starting the testing process ------------------

-----Android start testing now with 20 devices, time now: 300.073 sec.

start test[0] with 20 devices.

-----iOs start testing now with 4 devices, time now: 300.106 sec.

start test[0] with 4 devices.

Android LGE-Nexus 5_PT1820 got re-connected event  ####################################################

iOs with Apple-IpadAir2-1_PT4780 request took : 54365 ms. results peers[0], reConnects[0], sendData[3], time now: 354.474 sec.

iOs with Apple-Iphone6-1_PT7067 request took : 60176 ms. results peers[0], reConnects[0], sendData[3], time now: 360.285 sec.

iOs with Apple-Iphone5-1_PT4760 request took : 72579 ms. results peers[0], reConnects[0], sendData[3], time now: 372.688 sec.

Android LGE-Nexus 5_PT1820 got disconnected

Android LGE-LG-D802_PT7492 got disconnected

Android samsung-SM-N910C_PT1968 got disconnected

iOs with Apple-Iphone5s-1_PT8579 request took : 91691 ms. results peers[0], reConnects[0], sendData[3], time now: 391.8 sec.

------------------------------------------------------
iOs test[ 0] done now. , time now: 391.8 sec.

iOs All tests are done, preparing test report. , time now: 391.808 sec.

--------------- test report ---------------------

--------------- Apple-IpadAir2-1_PT4780 --------------------- : 1

sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.

Results list does not contain any items

sendList failed peers count : 3 [100 %]

- Peer ID : Apple-Iphone5s-1_PT8579.vXjqrg==, Tried : 1
- Peer ID : Apple-Iphone6-1_PT7067.RshDjw==, Tried : 1
- Peer ID : Apple-Iphone5-1_PT4760.Nm2EfQ==, Tried : 1
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5s-1_PT8579 --------------------- : 2

sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Results list does not contain any items

sendList failed peers count : 3 [100 %]

- Peer ID : 1448289589424.1345.nUzK5A==, Tried : 1
- Peer ID : 1448289584158.1345.7AijQA==, Tried : 1
- Peer ID : Apple-Iphone6-1_PT7067.RshDjw==, Tried : 1

sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1_PT7067 --------------------- : 3
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Results list does not contain any items
sendList failed peers count : 3 [100 %]
- Peer ID : 1448287198843.1386.IWfA6g==, Tried : 1

- Peer ID : Apple-Iphone5s-1_PT8579.vXjqrg==, Tried : 1
- Peer ID : Apple-IpadAir2-1_PT4780.nb956Q==, Tried : 1
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5-1_PT4760 --------------------- : 4
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.

Results list does not contain any items
sendList failed peers count : 3 [100 %]
- Peer ID : Apple-Iphone5s-1_PT8579.vXjqrg==, Tried : 1

- Peer ID : Apple-Iphone6-1_PT7067.RshDjw==, Tried : 1
- Peer ID : 1448287198843.1386.IWfA6g==, Tried : 1
sendList never tried peers count : 0 [0 %]

--------------- Combined ---------------------
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.

--------------- end of test report ---------------------

Android LGE-LG-D802_PT7492 got re-connected event  ####################################################

Android motorola-XT1072_PT5629 got disconnected

Android LGE-Nexus 5_PT1820 got disconnected

Android samsung-SM-G800F_PT9628 got disconnected

Android motorola-XT1072_PT5629 got re-connected event  ####################################################

Android HTC-HTC Desire 820_PT9217 got re-connected event  ####################################################

Android LGE-LG-D722_PT2795 got disconnected

Android motorola-XT1039_PT9468 got disconnected

Android HTC-HTC Desire 820_PT9217 got disconnected

Android motorola-XT1039_PT9468 got re-connected event  ####################################################

Android LGE-LG-D802_PT7492 got disconnected

Android motorola-XT1072_PT5629 got disconnected

Android motorola-XT1039_PT9468 got disconnected

Android HTC-HTC One_M8_PT3699 got re-connected event  ####################################################

Android HTC-HTC Desire 820_PT9217 got disconnected

Android motorola-XT1039_PT9468 got re-connected event  ####################################################

Android HTC-HTC One_M8_PT3699 got disconnected

Android LGE-LG-H815_PT1675 got re-connected event  ####################################################

Android LGE-LG-D855_PT3303 got disconnected

Android LGE-LG-H815_PT1675 got disconnected

Android samsung-SM-G900F_PT2552 got disconnected

Android motorola-Nexus 6_PT7032 got disconnected

Android samsung-SM-A300FU_PT5861 got disconnected

Android HTC-HTC Desire 820_PT2743 got re-connected event  ####################################################

Android HTC-HTC Desire 820_PT2743 got disconnected

Android with LGE-Nexus 5_PT566 request took : 790526 ms. results peers[0], reConnects[0], sendData[19], time now: 1090.623 sec.

Android LGE-LG-D802_PT7492 got re-connected event  ####################################################

Android with samsung-SM-N9005_PT6254 request took : 1000330 ms. results peers[0], reConnects[0], sendData[19], time now: 1300.42 sec.

Android with HTC-HTC One_M8_PT3699 request took : 1000385 ms. results peers[0], reConnects[0], sendData[19], time now: 1300.475 sec.

Android with LGE-LG-H815_PT1675 request took : 1000432 ms. results peers[0], reConnects[0], sendData[19], time now: 1300.52 sec.

Android with samsung-SM-A500FU_PT5540 request took : 1000824 ms. results peers[0], reConnects[0], sendData[19], time now: 1300.918 sec.

Android with samsung-SM-A300FU_PT7297 request took : 1001070 ms. results peers[0], reConnects[0], sendData[19], time now: 1301.163 sec.

Android with HTC-HTC Desire 820_PT2743 request took : 1001904 ms. results peers[0], reConnects[0], sendData[19], time now: 1301.993 sec.

Android with HUAWEI-ALE-L21_PT9956 request took : 1002144 ms. results peers[0], reConnects[0], sendData[19], time now: 1302.241 sec.

Android with motorola-XT1039_PT9468 request took : 1002486 ms. results peers[0], reConnects[0], sendData[19], time now: 1302.569 sec.

Android LGE-LG-D802_PT7492 got re-connected event  ####################################################

Android with LGE-LG-D802_PT7492 request took : 1028244 ms. results peers[0], reConnects[0], sendData[19], time now: 1328.342 sec.

Android LGE-LG-D802_PT7492 got disconnected

timeout now
Send timeout now to HTC-HTC Desire 820_PT9217

Send timeout now to LGE-Nexus 5_PT1820

Send timeout now to LGE-LG-D722_PT2795
Send timeout now to samsung-SM-A300FU_PT5861

Send timeout now to LGE-LG-D855_PT3303
Send timeout now to samsung-SM-G800F_PT9628
Send timeout now to motorola-Nexus 6_PT7032

Send timeout now to samsung-SM-N910C_PT1968
Send timeout now to motorola-XT1072_PT5629
Send timeout now to samsung-SM-G900F_PT2552

Second -- timeout now

Actual TIMEOUT now

HTC-HTC Desire 820_PT9217 removed from tests, new count : 20

LGE-Nexus 5_PT1820 removed from tests, new count : 19

LGE-LG-D722_PT2795 removed from tests, new count : 18

samsung-SM-A300FU_PT5861 removed from tests, new count : 17

LGE-LG-D855_PT3303 removed from tests, new count : 16

samsung-SM-G800F_PT9628 removed from tests, new count : 15

motorola-Nexus 6_PT7032 removed from tests, new count : 14

samsung-SM-N910C_PT1968 removed from tests, new count : 13

motorola-XT1072_PT5629 removed from tests, new count : 12

samsung-SM-G900F_PT2552 removed from tests, new count : 11

Android All tests are done, preparing test report. , time now: 1460.166 sec.

--------------- test report ---------------------

--------------- motorola-XT1039_PT9468 --------------------- : 1

sendList : 100% : 19154 ms, 99% : 19154 ms, 95 : 15595 ms, 90% : 15595 ms.
Result count 15, range 5678 ms to  19154 ms.
sendList failed peers count : 4 [21.05263157894737 %]
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 16
- Peer ID : 80:01:84:8A:B3:68, Tried : 16
- Peer ID : 34:FC:EF:11:B1:66, Tried : 16
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 16
sendList never tried peers count : 0 [0 %]
--------------- LGE-LG-H815_PT1675 --------------------- : 2
sendList : 100% : 31225 ms, 99% : 31225 ms, 95 : 26115 ms, 90% : 20407 ms.
Result count 16, range 5657 ms to  31225 ms.
sendList failed peers count : 3 [15.789473684210526 %]
- Peer ID : 80:01:84:8A:B3:68, Tried : 24
- Peer ID : 34:FC:EF:11:B1:66, Tried : 24
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 24
sendList never tried peers count : 0 [0 %]
--------------- HTC-HTC Desire 820_PT2743 --------------------- : 3
sendList : 100% : 20465 ms, 99% : 20465 ms, 95 : 16696 ms, 90% : 16696 ms.
Result count 13, range 6180 ms to  20465 ms.
sendList failed peers count : 6 [31.57894736842105 %]
- Peer ID : F8:95:C7:87:85:54, Tried : 11
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 11
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 11

- Peer ID : 34:FC:EF:11:B1:66, Tried : 11
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 11
- Peer ID : 80:01:84:8A:B3:68, Tried : 11
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-N9005_PT6254 --------------------- : 4
sendList : 100% : 39729 ms, 99% : 39729 ms, 95 : 29912 ms, 90% : 19082 ms.
Result count 18, range 6841 ms to  39729 ms.

sendList failed peers count : 1 [5.2631578947368425 %]
- Peer ID : 34:FC:EF:11:B1:66, Tried : 51
sendList never tried peers count : 0 [0 %]
--------------- HTC-HTC One_M8_PT3699 --------------------- : 5
sendList : 100% : 27683 ms, 99% : 27683 ms, 95 : 24405 ms, 90% : 19097 ms.

Result count 17, range 6278 ms to  27683 ms.
sendList failed peers count : 2 [10.526315789473685 %]
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 23
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 23
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-A300FU_PT7297 --------------------- : 6

sendList : 100% : 17727 ms, 99% : 17727 ms, 95 : 15411 ms, 90% : 15411 ms.
Result count 14, range 5737 ms to  17727 ms.
sendList failed peers count : 5 [26.31578947368421 %]
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 10
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 9
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 9
- Peer ID : 80:01:84:8A:B3:68, Tried : 9
- Peer ID : 34:FC:EF:11:B1:66, Tried : 10
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-A500FU_PT5540 --------------------- : 7
sendList : 100% : 18107 ms, 99% : 18107 ms, 95 : 17842 ms, 90% : 15939 ms.
Result count 17, range 5699 ms to  18107 ms.
sendList failed peers count : 2 [10.526315789473685 %]
- Peer ID : F8:95:C7:87:85:54, Tried : 14
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 13
sendList never tried peers count : 0 [0 %]
--------------- HUAWEI-ALE-L21_PT9956 --------------------- : 8

sendList : 100% : 55797 ms, 99% : 55797 ms, 95 : 25436 ms, 90% : 20729 ms.

Result count 16, range 1950 ms to  55797 ms.
sendList failed peers count : 3 [15.789473684210526 %]
- Peer ID : 34:FC:EF:11:B1:66, Tried : 7
- Peer ID : F8:95:C7:87:85:54, Tried : 6
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 6

sendList never tried peers count : 0 [0 %]
--------------- LGE-Nexus 5_PT566 --------------------- : 9
sendList : 100% : 27495 ms, 99% : 27495 ms, 95 : 19967 ms, 90% : 18038 ms.
Result count 19, range 5113 ms to  27495 ms.
sendList failed peers count : 0 [0 %]

sendList never tried peers count : 0 [0 %]
--------------- LGE-LG-D802_PT7492 --------------------- : 10
sendList : 100% : 19014 ms, 99% : 19014 ms, 95 : 19014 ms, 90% : 16340 ms.
Result count 7, range 6842 ms to  19014 ms.
sendList failed peers count : 12 [63.1578947368421 %]

- Peer ID : 58:3F:54:73:64:C0, Tried : 4
- Peer ID : 80:01:84:8A:B3:68, Tried : 3
- Peer ID : 44:80:EB:7B:5A:05, Tried : 3
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 3
- Peer ID : F8:95:C7:87:3C:51, Tried : 3
- Peer ID : 08:EC:A9:50:76:27, Tried : 3

- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 3
- Peer ID : 34:FC:EF:11:B1:66, Tried : 4
- Peer ID : 50:2E:6C:AC:21:50, Tried : 4
- Peer ID : 08:EC:A9:50:75:41, Tried : 4
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 4
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 4

sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------

sendList : 100% : 55797 ms, 99% : 31225 ms, 95 : 24405 ms, 90% : 19097 ms.

--------------- end of test report ---------------------

too late arrival


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```
###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  f56ad48d Test has  SUCCEEDED
STOP log received from  W3D7N15428022572 Test has  SUCCEEDED
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on f56ad48d 
Device test finished on W3D7N15428022572 
Device test finished on LGH8153b36be34 
Android task is completed. [SUCCESS]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/51517283acd5ddf_Update_to_jxcore-cordova_release_0_0_8__vjrantal/thali01_LGE-LG-H815.md)

[HUAWEI-ALE-L21](https://github.com/ThaliTester/TestResults/blob/51517283acd5ddf_Update_to_jxcore-cordova_release_0_0_8__vjrantal/thali01_HUAWEI-ALE-L21.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/51517283acd5ddf_Update_to_jxcore-cordova_release_0_0_8__vjrantal/thali01_samsung-SM-A500FU.md)

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
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/51517283acd5ddf_Update_to_jxcore-cordova_release_0_0_8__vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/51517283acd5ddf_Update_to_jxcore-cordova_release_0_0_8__vjrantal/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/51517283acd5ddf_Update_to_jxcore-cordova_release_0_0_8__vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/51517283acd5ddf_Update_to_jxcore-cordova_release_0_0_8__vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/51517283acd5ddf_Update_to_jxcore-cordova_release_0_0_8__vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  ZX1C223JKW Test has  FAILED
Device test finished on ZX1C223JKW 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Error! Unexpected exit on device 0be0c6c6 app:com.test.thalitest code:null 
child process exited with code null on device 0be0c6c6 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/51517283acd5ddf_Update_to_jxcore-cordova_release_0_0_8__vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/51517283acd5ddf_Update_to_jxcore-cordova_release_0_0_8__vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/51517283acd5ddf_Update_to_jxcore-cordova_release_0_0_8__vjrantal/thali04_samsung-SM-G900F.md)

####Node name: thali05
Console output:
```
STOP log received from  1d6a772d Test has  SUCCEEDED
Device test finished on 1d6a772d 
STOP log received from  SH47FWM00508 Test has  SUCCEEDED
Device test finished on SH47FWM00508 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1G429CRK 
Android task is completed. [FAILED]
```
[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/51517283acd5ddf_Update_to_jxcore-cordova_release_0_0_8__vjrantal/thali05_samsung-SM-N9005.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/51517283acd5ddf_Update_to_jxcore-cordova_release_0_0_8__vjrantal/thali05_motorola-Nexus 6.md)

[HTC-HTC One_M8](https://github.com/ThaliTester/TestResults/blob/51517283acd5ddf_Update_to_jxcore-cordova_release_0_0_8__vjrantal/thali05_HTC-HTC One_M8.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/51517283acd5ddf_Update_to_jxcore-cordova_release_0_0_8__vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/51517283acd5ddf_Update_to_jxcore-cordova_release_0_0_8__vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/51517283acd5ddf_Update_to_jxcore-cordova_release_0_0_8__vjrantal/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
Error: problem deploying Android apk(/home/pi/test/builder/builds/51517283acd5ddf/build_android/android_0_51517283acd5ddf.apk) to device 4db5c8cc protocol failure
- waiting for device -
rm: /data/local/tmp/android_0_51517283acd5ddf.apk: No such file or directory



Test on this node has failed but the reason wasn't the test application itself.
 Cancelling the test result on this node.

```
####Node name: thali08
Console output:
```
STOP log received from  4325e43f Test has  SUCCEEDED
Device test finished on 4325e43f 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device HT574YC04723 app:com.test.thalitest code:null 
child process exited with code null on device HT574YC04723 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/51517283acd5ddf_Update_to_jxcore-cordova_release_0_0_8__vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/51517283acd5ddf_Update_to_jxcore-cordova_release_0_0_8__vjrantal/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
Error! Unexpected exit on device 0c6a0f3c0bdb4e77 app:com.test.thalitest code:0 
child process exited with code 0 on device 0c6a0f3c0bdb4e77 
STOP log received from  CC51WYC03425 Test has  SUCCEEDED
Device test finished on CC51WYC03425 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/51517283acd5ddf_Update_to_jxcore-cordova_release_0_0_8__vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/51517283acd5ddf_Update_to_jxcore-cordova_release_0_0_8__vjrantal/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/51517283acd5ddf_Update_to_jxcore-cordova_release_0_0_8__vjrantal/iOS_Iphone5-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/51517283acd5ddf_Update_to_jxcore-cordova_release_0_0_8__vjrantal/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/51517283acd5ddf_Update_to_jxcore-cordova_release_0_0_8__vjrantal/iOS_Iphone6-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/51517283acd5ddf_Update_to_jxcore-cordova_release_0_0_8__vjrantal/iOS_IpadAir2-1.md)


#### Integration Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":21}}
Start Android tests : performance tests, start tests with timer

Test[0]: testSendData.js, timeout : 1100000, data : {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"4000","conReTryCount":"1"}
Start iOs tests : performance tests, start tests with timer
Test[0]: testSendData.js, timeout : 1100000, data : {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"4000","conReTryCount":"1"}

listening on *:3000

Android  motorola-XT1039_PT9468 added : 1 sec., device count 1

iOs  Apple-IpadAir2-1_PT4780 added : 1.044 sec., device count 1

iOs  Apple-Iphone5s-1_PT8579 added : 1.784 sec., device count 2

Android  HTC-HTC Desire 820_PT9217 added : 1.788 sec., device count 2

Android  LGE-LG-H815_PT1675 added : 1.845 sec., device count 3

Android  LGE-Nexus 5_PT1820 added : 1.89 sec., device count 4

iOs  Apple-Iphone6-1_PT7067 added : 2.143 sec., device count 3

Android  HTC-HTC Desire 820_PT2743 added : 2.196 sec., device count 5

Android  samsung-SM-N9005_PT6254 added : 2.298 sec., device count 6

Android  HTC-HTC One_M8_PT3699 added : 2.312 sec., device count 7

Android  samsung-SM-A300FU_PT7297 added : 2.435 sec., device count 8

Android  LGE-LG-D722_PT2795 added : 2.442 sec., device count 9

iOs  Apple-Iphone5-1_PT4760 added : 2.81 sec., device count 4

Android  samsung-SM-A500FU_PT5540 added : 3.075 sec., device count 10

Android  samsung-SM-A300FU_PT5861 added : 3.331 sec., device count 11

Android  LGE-LG-D855_PT3303 added : 4.016 sec., device count 12

Android  HUAWEI-ALE-L21_PT9956 added : 4.147 sec., device count 13

Android  LGE-Nexus 5_PT566 added : 4.544 sec., device count 14

Android  LGE-LG-D802_PT7492 added : 4.812 sec., device count 15

Android  samsung-SM-G800F_PT9628 added : 4.978 sec., device count 16

Android  motorola-Nexus 6_PT7032 added : 5.094 sec., device count 17

Android  samsung-SM-N910C_PT1968 added : 6.142 sec., device count 18

Android  motorola-XT1072_PT5629 added : 7.746 sec., device count 19

Android  samsung-SM-G900F_PT2552 added : 8.035 sec., device count 20

-------------- We got wait done, now starting the testing process ------------------

-----Android start testing now with 20 devices, time now: 300.073 sec.

start test[0] with 20 devices.

-----iOs start testing now with 4 devices, time now: 300.106 sec.

start test[0] with 4 devices.

Android LGE-Nexus 5_PT1820 got re-connected event  ####################################################

iOs with Apple-IpadAir2-1_PT4780 request took : 54365 ms. results peers[0], reConnects[0], sendData[3], time now: 354.474 sec.

iOs with Apple-Iphone6-1_PT7067 request took : 60176 ms. results peers[0], reConnects[0], sendData[3], time now: 360.285 sec.

iOs with Apple-Iphone5-1_PT4760 request took : 72579 ms. results peers[0], reConnects[0], sendData[3], time now: 372.688 sec.

Android LGE-Nexus 5_PT1820 got disconnected

Android LGE-LG-D802_PT7492 got disconnected

Android samsung-SM-N910C_PT1968 got disconnected

iOs with Apple-Iphone5s-1_PT8579 request took : 91691 ms. results peers[0], reConnects[0], sendData[3], time now: 391.8 sec.

------------------------------------------------------
iOs test[ 0] done now. , time now: 391.8 sec.

iOs All tests are done, preparing test report. , time now: 391.808 sec.

--------------- test report ---------------------

--------------- Apple-IpadAir2-1_PT4780 --------------------- : 1

sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.

Results list does not contain any items

sendList failed peers count : 3 [100 %]

- Peer ID : Apple-Iphone5s-1_PT8579.vXjqrg==, Tried : 1
- Peer ID : Apple-Iphone6-1_PT7067.RshDjw==, Tried : 1
- Peer ID : Apple-Iphone5-1_PT4760.Nm2EfQ==, Tried : 1
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5s-1_PT8579 --------------------- : 2

sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Results list does not contain any items

sendList failed peers count : 3 [100 %]

- Peer ID : 1448289589424.1345.nUzK5A==, Tried : 1
- Peer ID : 1448289584158.1345.7AijQA==, Tried : 1
- Peer ID : Apple-Iphone6-1_PT7067.RshDjw==, Tried : 1

sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1_PT7067 --------------------- : 3
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Results list does not contain any items
sendList failed peers count : 3 [100 %]
- Peer ID : 1448287198843.1386.IWfA6g==, Tried : 1

- Peer ID : Apple-Iphone5s-1_PT8579.vXjqrg==, Tried : 1
- Peer ID : Apple-IpadAir2-1_PT4780.nb956Q==, Tried : 1
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5-1_PT4760 --------------------- : 4
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.

Results list does not contain any items
sendList failed peers count : 3 [100 %]
- Peer ID : Apple-Iphone5s-1_PT8579.vXjqrg==, Tried : 1

- Peer ID : Apple-Iphone6-1_PT7067.RshDjw==, Tried : 1
- Peer ID : 1448287198843.1386.IWfA6g==, Tried : 1
sendList never tried peers count : 0 [0 %]

--------------- Combined ---------------------
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.

--------------- end of test report ---------------------

Android LGE-LG-D802_PT7492 got re-connected event  ####################################################

Android motorola-XT1072_PT5629 got disconnected

Android LGE-Nexus 5_PT1820 got disconnected

Android samsung-SM-G800F_PT9628 got disconnected

Android motorola-XT1072_PT5629 got re-connected event  ####################################################

Android HTC-HTC Desire 820_PT9217 got re-connected event  ####################################################

Android LGE-LG-D722_PT2795 got disconnected

Android motorola-XT1039_PT9468 got disconnected

Android HTC-HTC Desire 820_PT9217 got disconnected

Android motorola-XT1039_PT9468 got re-connected event  ####################################################

Android LGE-LG-D802_PT7492 got disconnected

Android motorola-XT1072_PT5629 got disconnected

Android motorola-XT1039_PT9468 got disconnected

Android HTC-HTC One_M8_PT3699 got re-connected event  ####################################################

Android HTC-HTC Desire 820_PT9217 got disconnected

Android motorola-XT1039_PT9468 got re-connected event  ####################################################

Android HTC-HTC One_M8_PT3699 got disconnected

Android LGE-LG-H815_PT1675 got re-connected event  ####################################################

Android LGE-LG-D855_PT3303 got disconnected

Android LGE-LG-H815_PT1675 got disconnected

Android samsung-SM-G900F_PT2552 got disconnected

Android motorola-Nexus 6_PT7032 got disconnected

Android samsung-SM-A300FU_PT5861 got disconnected

Android HTC-HTC Desire 820_PT2743 got re-connected event  ####################################################

Android HTC-HTC Desire 820_PT2743 got disconnected

Android with LGE-Nexus 5_PT566 request took : 790526 ms. results peers[0], reConnects[0], sendData[19], time now: 1090.623 sec.

Android LGE-LG-D802_PT7492 got re-connected event  ####################################################

Android with samsung-SM-N9005_PT6254 request took : 1000330 ms. results peers[0], reConnects[0], sendData[19], time now: 1300.42 sec.

Android with HTC-HTC One_M8_PT3699 request took : 1000385 ms. results peers[0], reConnects[0], sendData[19], time now: 1300.475 sec.

Android with LGE-LG-H815_PT1675 request took : 1000432 ms. results peers[0], reConnects[0], sendData[19], time now: 1300.52 sec.

Android with samsung-SM-A500FU_PT5540 request took : 1000824 ms. results peers[0], reConnects[0], sendData[19], time now: 1300.918 sec.

Android with samsung-SM-A300FU_PT7297 request took : 1001070 ms. results peers[0], reConnects[0], sendData[19], time now: 1301.163 sec.

Android with HTC-HTC Desire 820_PT2743 request took : 1001904 ms. results peers[0], reConnects[0], sendData[19], time now: 1301.993 sec.

Android with HUAWEI-ALE-L21_PT9956 request took : 1002144 ms. results peers[0], reConnects[0], sendData[19], time now: 1302.241 sec.

Android with motorola-XT1039_PT9468 request took : 1002486 ms. results peers[0], reConnects[0], sendData[19], time now: 1302.569 sec.

Android LGE-LG-D802_PT7492 got re-connected event  ####################################################

Android with LGE-LG-D802_PT7492 request took : 1028244 ms. results peers[0], reConnects[0], sendData[19], time now: 1328.342 sec.

Android LGE-LG-D802_PT7492 got disconnected

timeout now
Send timeout now to HTC-HTC Desire 820_PT9217

Send timeout now to LGE-Nexus 5_PT1820

Send timeout now to LGE-LG-D722_PT2795
Send timeout now to samsung-SM-A300FU_PT5861

Send timeout now to LGE-LG-D855_PT3303
Send timeout now to samsung-SM-G800F_PT9628
Send timeout now to motorola-Nexus 6_PT7032

Send timeout now to samsung-SM-N910C_PT1968
Send timeout now to motorola-XT1072_PT5629
Send timeout now to samsung-SM-G900F_PT2552

Second -- timeout now

Actual TIMEOUT now

HTC-HTC Desire 820_PT9217 removed from tests, new count : 20

LGE-Nexus 5_PT1820 removed from tests, new count : 19

LGE-LG-D722_PT2795 removed from tests, new count : 18

samsung-SM-A300FU_PT5861 removed from tests, new count : 17

LGE-LG-D855_PT3303 removed from tests, new count : 16

samsung-SM-G800F_PT9628 removed from tests, new count : 15

motorola-Nexus 6_PT7032 removed from tests, new count : 14

samsung-SM-N910C_PT1968 removed from tests, new count : 13

motorola-XT1072_PT5629 removed from tests, new count : 12

samsung-SM-G900F_PT2552 removed from tests, new count : 11

Android All tests are done, preparing test report. , time now: 1460.166 sec.

--------------- test report ---------------------

--------------- motorola-XT1039_PT9468 --------------------- : 1

sendList : 100% : 19154 ms, 99% : 19154 ms, 95 : 15595 ms, 90% : 15595 ms.
Result count 15, range 5678 ms to  19154 ms.
sendList failed peers count : 4 [21.05263157894737 %]
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 16
- Peer ID : 80:01:84:8A:B3:68, Tried : 16
- Peer ID : 34:FC:EF:11:B1:66, Tried : 16
- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 16
sendList never tried peers count : 0 [0 %]
--------------- LGE-LG-H815_PT1675 --------------------- : 2
sendList : 100% : 31225 ms, 99% : 31225 ms, 95 : 26115 ms, 90% : 20407 ms.
Result count 16, range 5657 ms to  31225 ms.
sendList failed peers count : 3 [15.789473684210526 %]
- Peer ID : 80:01:84:8A:B3:68, Tried : 24
- Peer ID : 34:FC:EF:11:B1:66, Tried : 24
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 24
sendList never tried peers count : 0 [0 %]
--------------- HTC-HTC Desire 820_PT2743 --------------------- : 3
sendList : 100% : 20465 ms, 99% : 20465 ms, 95 : 16696 ms, 90% : 16696 ms.
Result count 13, range 6180 ms to  20465 ms.
sendList failed peers count : 6 [31.57894736842105 %]
- Peer ID : F8:95:C7:87:85:54, Tried : 11
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 11
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 11

- Peer ID : 34:FC:EF:11:B1:66, Tried : 11
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 11
- Peer ID : 80:01:84:8A:B3:68, Tried : 11
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-N9005_PT6254 --------------------- : 4
sendList : 100% : 39729 ms, 99% : 39729 ms, 95 : 29912 ms, 90% : 19082 ms.
Result count 18, range 6841 ms to  39729 ms.

sendList failed peers count : 1 [5.2631578947368425 %]
- Peer ID : 34:FC:EF:11:B1:66, Tried : 51
sendList never tried peers count : 0 [0 %]
--------------- HTC-HTC One_M8_PT3699 --------------------- : 5
sendList : 100% : 27683 ms, 99% : 27683 ms, 95 : 24405 ms, 90% : 19097 ms.

Result count 17, range 6278 ms to  27683 ms.
sendList failed peers count : 2 [10.526315789473685 %]
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 23
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 23
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-A300FU_PT7297 --------------------- : 6

sendList : 100% : 17727 ms, 99% : 17727 ms, 95 : 15411 ms, 90% : 15411 ms.
Result count 14, range 5737 ms to  17727 ms.
sendList failed peers count : 5 [26.31578947368421 %]
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 10
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 9
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 9
- Peer ID : 80:01:84:8A:B3:68, Tried : 9
- Peer ID : 34:FC:EF:11:B1:66, Tried : 10
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-A500FU_PT5540 --------------------- : 7
sendList : 100% : 18107 ms, 99% : 18107 ms, 95 : 17842 ms, 90% : 15939 ms.
Result count 17, range 5699 ms to  18107 ms.
sendList failed peers count : 2 [10.526315789473685 %]
- Peer ID : F8:95:C7:87:85:54, Tried : 14
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 13
sendList never tried peers count : 0 [0 %]
--------------- HUAWEI-ALE-L21_PT9956 --------------------- : 8

sendList : 100% : 55797 ms, 99% : 55797 ms, 95 : 25436 ms, 90% : 20729 ms.

Result count 16, range 1950 ms to  55797 ms.
sendList failed peers count : 3 [15.789473684210526 %]
- Peer ID : 34:FC:EF:11:B1:66, Tried : 7
- Peer ID : F8:95:C7:87:85:54, Tried : 6
- Peer ID : F8:CF:C5:D9:E5:61, Tried : 6

sendList never tried peers count : 0 [0 %]
--------------- LGE-Nexus 5_PT566 --------------------- : 9
sendList : 100% : 27495 ms, 99% : 27495 ms, 95 : 19967 ms, 90% : 18038 ms.
Result count 19, range 5113 ms to  27495 ms.
sendList failed peers count : 0 [0 %]

sendList never tried peers count : 0 [0 %]
--------------- LGE-LG-D802_PT7492 --------------------- : 10
sendList : 100% : 19014 ms, 99% : 19014 ms, 95 : 19014 ms, 90% : 16340 ms.
Result count 7, range 6842 ms to  19014 ms.
sendList failed peers count : 12 [63.1578947368421 %]

- Peer ID : 58:3F:54:73:64:C0, Tried : 4
- Peer ID : 80:01:84:8A:B3:68, Tried : 3
- Peer ID : 44:80:EB:7B:5A:05, Tried : 3
- Peer ID : E0:DB:10:1F:C9:5E, Tried : 3
- Peer ID : F8:95:C7:87:3C:51, Tried : 3
- Peer ID : 08:EC:A9:50:76:27, Tried : 3

- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 3
- Peer ID : 34:FC:EF:11:B1:66, Tried : 4
- Peer ID : 50:2E:6C:AC:21:50, Tried : 4
- Peer ID : 08:EC:A9:50:75:41, Tried : 4
- Peer ID : 58:2A:F7:ED:96:BE, Tried : 4
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 4

sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------

sendList : 100% : 55797 ms, 99% : 31225 ms, 95 : 24405 ms, 90% : 19097 ms.

--------------- end of test report ---------------------

too late arrival


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


#### Test 50650278b28a87a Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":23}}
listening on *:3000

New perf test device: HUAWEI-ALE-L21_PT1149

New perf test device: samsung-SM-G900F_PT3984

New perf test device: LGE-LG-D802_PT310

New perf test device: LGE-LG-H815_PT3785

New perf test device: Apple-Iphone6-1_PT7748

New perf test device: samsung-SM-G900F_PT3490

New perf test device: HTC-HTC Desire 820_PT5376

New perf test device: samsung-SM-N910C_PT6613

New perf test device: motorola-Nexus 6_PT9776

New perf test device: Apple-IpadAir2-1_PT9197

New perf test device: samsung-SM-A500FU_PT359

New perf test device: LGE-LG-D855_PT2773

New perf test device: LGE-LG-D722_PT8558

New perf test device: Apple-Iphone5-1_PT9641

New perf test device: LGE-Nexus 5_PT3213

New perf test device: Apple-Iphone5s-1_PT3959

New perf test device: samsung-SM-A300FU_PT5174

New perf test device: HTC-HTC Desire 820_PT7076

New perf test device: samsung-SM-N9005_PT9416

New perf test device: samsung-SM-A500FU_PT9674

New perf test device: motorola-XT1072_PT8678

New perf test device: samsung-SM-A300FU_PT3064

New perf test device: samsung-SM-G800H_PT5250

2015-12-09T14:30:44.945Z (7 sec) - ios test ID testFindPeers.js done now

Continuing to next test: testSendData.js

New perf test device: samsung-SM-G800F_PT2809

New perf test device: motorola-XT1039_PT1917

2015-12-09T14:32:27.641Z (109 sec) - ios test ID testSendData.js done now

ALL DONE !!!

{ 'name:': 'Apple-Iphone6-1_PT7748',
  time: 1088,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5s-1_PT3959.Sz9P+A==',
       peerAvailable: true,
       time: 1087 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT9197',
  time: 1112,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5s-1_PT3959.Sz9P+A==',
       peerAvailable: true,
       time: 1111 } ] }

{ 'name:': 'Apple-Iphone5-1_PT9641',
  time: 1013,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5s-1_PT3959.Sz9P+A==',
       peerAvailable: true,
       time: 1011 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT3959',
  time: 1917,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1_PT9641.ucdqLA==',
       peerAvailable: true,
       time: 1916 } ] }

{ 'name:': 'Apple-Iphone6-1_PT7748',
  time: 97226,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT9197.sabYWA==',
       time: 41226,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1_PT3959.ieNWQg==',
       time: 44909,
       result: 'OK',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT9197.46F2bw==',
       time: 3330,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT9641.4z6eyA==',
       time: 7484,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT9197',
  time: 53590,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5s-1_PT3959.Sz9P+A==',
       time: 41246,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1_PT3959.ieNWQg==',
       time: 4077,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT7748.7slvbQ==',
       time: 3452,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT9641.4z6eyA==',
       time: 4668,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1_PT9641',
  time: 98817,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT9197.sabYWA==',
       time: 40734,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1_PT3959.ieNWQg==',
       time: 44991,
       result: 'OK',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT7748.7slvbQ==',
       time: 8435,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT9197.46F2bw==',
       time: 4037,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT3959',
  time: 54204,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT9197.sabYWA==',
       time: 41168,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT7748.7slvbQ==',
       time: 5041,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT9197.46F2bw==',
       time: 3678,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT9641.4z6eyA==',
       time: 4221,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

--------------- test report ---------------------
--------------- Apple-Iphone6-1_PT7748 --------------------- : 1

peersList : 100% : 1087 ms, 99% : 1087 ms, 95 : 1087 ms, 90% : 1087 ms.

Result count 1, range 1087 ms to  1087 ms.

sendList : 100% : 44909 ms, 99% : 44909 ms, 95 : 44909 ms, 90% : 44909 ms.

Average data rate: 0.005 MB/s

Result count 3, range 3330 ms to  44909 ms.

sendList failed peers count : 1 [25 %]

- Peer ID : Apple-IpadAir2-1_PT9197.sabYWA==, Tried : 5

sendList never tried peers count : 0 [0 %]
--------------- Apple-IpadAir2-1_PT9197 --------------------- : 2

peersList : 100% : 1111 ms, 99% : 1111 ms, 95 : 1111 ms, 90% : 1111 ms.
Result count 1, range 1111 ms to  1111 ms.
sendList : 100% : 4668 ms, 99% : 4668 ms, 95 : 4668 ms, 90% : 4668 ms.
Average data rate: 0.025 MB/s
Result count 3, range 3452 ms to  4668 ms.

sendList failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone5s-1_PT3959.Sz9P+A==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5-1_PT9641 --------------------- : 3
peersList : 100% : 1011 ms, 99% : 1011 ms, 95 : 1011 ms, 90% : 1011 ms.
Result count 1, range 1011 ms to  1011 ms.

sendList : 100% : 44991 ms, 99% : 44991 ms, 95 : 44991 ms, 90% : 44991 ms.
Average data rate: 0.005 MB/s
Result count 3, range 4037 ms to  44991 ms.

sendList failed peers count : 1 [25 %]
- Peer ID : Apple-IpadAir2-1_PT9197.sabYWA==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5s-1_PT3959 --------------------- : 4
peersList : 100% : 1916 ms, 99% : 1916 ms, 95 : 1916 ms, 90% : 1916 ms.
Result count 1, range 1916 ms to  1916 ms.
sendList : 100% : 5041 ms, 99% : 5041 ms, 95 : 5041 ms, 90% : 5041 ms.
Average data rate: 0.023 MB/s
Result count 3, range 3678 ms to  5041 ms.
sendList failed peers count : 1 [25 %]

- Peer ID : Apple-IpadAir2-1_PT9197.sabYWA==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------

peersList : 100% : 1916 ms, 99% : 1916 ms, 95 : 1916 ms, 90% : 1916 ms.

sendList : 100% : 44991 ms, 99% : 44991 ms, 95 : 44909 ms, 90% : 44909 ms.

Average data rate: 0.009 MB/s
--------------- end of test report ---------------------

{ 'Apple-Iphone6-1_PT7748': 
   { peersList: [ [Object] ],
     sendList: [ [Object], [Object], [Object] ],
     sendError: { failedPeer: [Object], notTriedList: [] } },
  'Apple-IpadAir2-1_PT9197': 
   { peersList: [ [Object] ],
     sendList: [ [Object], [Object], [Object] ],
     sendError: { failedPeer: [Object], notTriedList: [] } },
  'Apple-Iphone5-1_PT9641': 
   { peersList: [ [Object] ],
     sendList: [ [Object], [Object], [Object] ],
     sendError: { failedPeer: [Object], notTriedList: [] } },
  'Apple-Iphone5s-1_PT3959': 
   { peersList: [ [Object] ],
     sendList: [ [Object], [Object], [Object] ],
     sendError: { failedPeer: [Object], notTriedList: [] } } }


```


Logs for system : 
```

ios : false

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###Android Logs
####Node name: thali01
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:0 
child process exited with code 0 on device LGH8153b36be34 
Error! Unexpected exit on device W3D7N15428022572 app:com.test.thalitest code:0 
child process exited with code 0 on device W3D7N15428022572 
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:null 
child process exited with code null on device f56ad48d 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/50650278b28a87a_Enable_UnitTest_tobybrad/thali01_LGE-LG-H815.md)

[HUAWEI-ALE-L21](https://github.com/ThaliTester/TestResults/blob/50650278b28a87a_Enable_UnitTest_tobybrad/thali01_HUAWEI-ALE-L21.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/50650278b28a87a_Enable_UnitTest_tobybrad/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Error! Unexpected exit on device 09a9416e0297d102 app:com.test.thalitest code:0 
child process exited with code 0 on device 09a9416e0297d102 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/50650278b28a87a_Enable_UnitTest_tobybrad/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/50650278b28a87a_Enable_UnitTest_tobybrad/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device TA4750HV7I app:com.test.thalitest code:0 
child process exited with code 0 on device TA4750HV7I 
Error! Unexpected exit on device LGD8553bed2d08 app:com.test.thalitest code:0 
child process exited with code 0 on device LGD8553bed2d08 
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:null 
child process exited with code null on device 320414cd475f91e3 
Android task is completed. [FAILED]
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/50650278b28a87a_Enable_UnitTest_tobybrad/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/50650278b28a87a_Enable_UnitTest_tobybrad/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/50650278b28a87a_Enable_UnitTest_tobybrad/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Error! Unexpected exit on device 0be0c6c6 app:com.test.thalitest code:null 
child process exited with code null on device 0be0c6c6 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/50650278b28a87a_Enable_UnitTest_tobybrad/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/50650278b28a87a_Enable_UnitTest_tobybrad/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/50650278b28a87a_Enable_UnitTest_tobybrad/thali04_samsung-SM-G900F.md)

####Node name: thali05
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 1d6a772d app:com.test.thalitest code:null 
child process exited with code null on device 1d6a772d 
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1G429CRK 
Error! Unexpected exit on device 954a12ed app:com.test.thalitest code:0 
child process exited with code 0 on device 954a12ed 
Android task is completed. [FAILED]
```
[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/50650278b28a87a_Enable_UnitTest_tobybrad/thali05_samsung-SM-N9005.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/50650278b28a87a_Enable_UnitTest_tobybrad/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/50650278b28a87a_Enable_UnitTest_tobybrad/thali05_samsung-SM-G800H.md)

####Node name: thali06
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:0 
child process exited with code 0 on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:0 
child process exited with code 0 on device FA55PYS00566 
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:0 
child process exited with code 0 on device 022678fb504e29b0 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/50650278b28a87a_Enable_UnitTest_tobybrad/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/50650278b28a87a_Enable_UnitTest_tobybrad/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/50650278b28a87a_Enable_UnitTest_tobybrad/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device c5afcdcb app:com.test.thalitest code:null 
child process exited with code null on device c5afcdcb 
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:0 
child process exited with code 0 on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/50650278b28a87a_Enable_UnitTest_tobybrad/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/50650278b28a87a_Enable_UnitTest_tobybrad/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/50650278b28a87a_Enable_UnitTest_tobybrad/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/50650278b28a87a_Enable_UnitTest_tobybrad/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/50650278b28a87a_Enable_UnitTest_tobybrad/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/50650278b28a87a_Enable_UnitTest_tobybrad/thali09_LGE-Nexus 5.md)




###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/50650278b28a87a_Enable_UnitTest_tobybrad/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/50650278b28a87a_Enable_UnitTest_tobybrad/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/50650278b28a87a_Enable_UnitTest_tobybrad/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/50650278b28a87a_Enable_UnitTest_tobybrad/iOS_Iphone5-1.md)



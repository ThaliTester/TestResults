#### Test 50650278923ff9f Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":22}}
listening on *:3000

New device presented: LGE-Nexus 5_PT6351 (android) perftest

Setting start timeout to: 120000 (android)

New device presented: HTC-HTC Desire 820_PT2543 (android) perftest

New device presented: motorola-XT1039_PT7213 (android) perftest

New device presented: samsung-SM-G800F_PT2910 (android) perftest

New device presented: Apple-Iphone5-1_PT9225 (ios) perftest

Setting start timeout to: 120000 (ios)

New device presented: LGE-LG-D722_PT7919 (android) perftest

New device presented: samsung-SM-A500FU_PT5943 (android) perftest

New device presented: Apple-Iphone5s-1_PT1155 (ios) perftest

New device presented: HTC-HTC Desire 820_PT9623 (android) perftest

New device presented: samsung-SM-A300FU_PT7078 (android) perftest

New device presented: motorola-Nexus 6_PT5109 (android) perftest

New device presented: samsung-SM-N9005_PT2965 (android) perftest

New device presented: samsung-SM-G900F_PT8243 (android) perftest

New device presented: samsung-SM-N910C_PT567 (android) perftest

New device presented: Apple-Iphone6-1_PT3392 (ios) perftest

New device presented: LGE-LG-D855_PT1133 (android) perftest

New device presented: samsung-SM-G800H_PT9494 (android) perftest

New device presented: samsung-SM-A300FU_PT8374 (android) perftest

New device presented: Apple-IpadAir2-1_PT1077 (ios) perftest

Required number of devices presented

Starting perf test run for platform: ios

Using devices:
Apple-Iphone5-1_PT9225
Apple-Iphone5s-1_PT1155

Apple-Iphone6-1_PT3392
Apple-IpadAir2-1_PT1077

Setting: (ios) 4

New device presented: LGE-LG-H815_PT5083 (android) perftest

New device presented: LGE-Nexus 5_PT7888 (android) perftest

New device presented: LGE-LG-D802_PT1527 (android) perftest

New device presented: samsung-SM-A500FU_PT9515 (android) perftest

Received results for Apple-Iphone5-1_PT9225 ios (4 left)

Received results for Apple-Iphone5s-1_PT1155 ios (3 left)

Received results for Apple-IpadAir2-1_PT1077 ios (2 left)

Received results for Apple-Iphone6-1_PT3392 ios (1 left)

All test data retrieved for testFindPeers.js (ios)

Continuing to next test: testSendData.js

Setting: (ios) 4

New device presented: samsung-SM-G900F_PT6710 (android) perftest

New device presented: motorola-XT1072_PT1319 (android) perftest

Received results for Apple-Iphone6-1_PT3392 ios (4 left)

Received results for Apple-IpadAir2-1_PT1077 ios (3 left)

Received results for Apple-Iphone5-1_PT9225 ios (2 left)

Received results for Apple-Iphone5s-1_PT1155 ios (1 left)

All test data retrieved for testSendData.js (ios)

ALL DONE !!!

{ 'name:': 'Apple-Iphone5-1_PT9225',
  time: 850,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1_PT1077.nIXSkg==',
       peerAvailable: true,
       time: 849 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT1155',
  time: 834,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1_PT1077.nIXSkg==',
       peerAvailable: true,
       time: 832 } ] }

{ 'name:': 'Apple-Iphone6-1_PT3392',
  time: 1401,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1_PT1077.nIXSkg==',
       peerAvailable: true,
       time: 1400 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT1077',
  time: 1464,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT3392.Ts8/9g==',
       peerAvailable: true,
       time: 1463 } ] }

{ 'name:': 'Apple-Iphone5-1_PT9225',
  time: 53613,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5s-1_PT1155.WIj3og==',
       time: 42250,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT3392.EGNu6Q==',
       time: 3612,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT1077.khzDiQ==',
       time: 3470,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT1155.Bev+OQ==',
       time: 3577,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT1155',
  time: 53579,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5s-1_PT1155.WIj3og==',
       time: 40545,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1_PT9225.kJjMbg==',
       time: 6589,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT3392.EGNu6Q==',
       time: 2603,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT1077.khzDiQ==',
       time: 3115,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1_PT3392',
  time: 51648,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT1077.nIXSkg==',
       time: 41051,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1_PT9225.kJjMbg==',
       time: 3576,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT1155.Bev+OQ==',
       time: 3516,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT1077.khzDiQ==',
       time: 2967,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT1077',
  time: 52155,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT3392.Ts8/9g==',
       time: 40614,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT3392.EGNu6Q==',
       time: 4183,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT9225.kJjMbg==',
       time: 3335,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT1155.Bev+OQ==',
       time: 3166,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

--------------- test report ---------------------
--------------- Apple-Iphone5-1_PT9225 --------------------- : 1

peersList : 100% : 849 ms, 99% : 849 ms, 95 : 849 ms, 90% : 849 ms.

Result count 1, range 849 ms to  849 ms.

sendList : 100% : 3612 ms, 99% : 3612 ms, 95 : 3612 ms, 90% : 3612 ms.

Average data rate: 0.028 MB/s

Result count 3, range 3470 ms to  3612 ms.

sendList failed peers count : 1 [25 %]

- Peer ID : Apple-Iphone5s-1_PT1155.WIj3og==, Tried : 5

sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5s-1_PT1155 --------------------- : 2
peersList : 100% : 832 ms, 99% : 832 ms, 95 : 832 ms, 90% : 832 ms.

Result count 1, range 832 ms to  832 ms.

sendList : 100% : 6589 ms, 99% : 6589 ms, 95 : 6589 ms, 90% : 6589 ms.
Average data rate: 0.024 MB/s
Result count 3, range 2603 ms to  6589 ms.

sendList failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone5s-1_PT1155.WIj3og==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone6-1_PT3392 --------------------- : 3
peersList : 100% : 1400 ms, 99% : 1400 ms, 95 : 1400 ms, 90% : 1400 ms.

Result count 1, range 1400 ms to  1400 ms.
sendList : 100% : 3576 ms, 99% : 3576 ms, 95 : 3576 ms, 90% : 3576 ms.
Average data rate: 0.03 MB/s

Result count 3, range 2967 ms to  3576 ms.
sendList failed peers count : 1 [25 %]
- Peer ID : Apple-IpadAir2-1_PT1077.nIXSkg==, Tried : 5

sendList never tried peers count : 0 [0 %]
--------------- Apple-IpadAir2-1_PT1077 --------------------- : 4
peersList : 100% : 1463 ms, 99% : 1463 ms, 95 : 1463 ms, 90% : 1463 ms.

Result count 1, range 1463 ms to  1463 ms.
sendList : 100% : 4183 ms, 99% : 4183 ms, 95 : 4183 ms, 90% : 4183 ms.
Average data rate: 0.028 MB/s

Result count 3, range 3166 ms to  4183 ms.
sendList failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone6-1_PT3392.Ts8/9g==, Tried : 5

sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------

peersList : 100% : 1463 ms, 99% : 1463 ms, 95 : 1463 ms, 90% : 1463 ms.

sendList : 100% : 6589 ms, 99% : 6589 ms, 95 : 4183 ms, 90% : 4183 ms.
Average data rate: 0.027 MB/s

--------------- end of test report ---------------------

{ 'Apple-Iphone5-1_PT9225': 
   { peersList: [ [Object] ],
     sendList: [ [Object], [Object], [Object] ],
     sendError: { failedPeer: [Object], notTriedList: [] } },
  'Apple-Iphone5s-1_PT1155': 
   { peersList: [ [Object] ],
     sendList: [ [Object], [Object], [Object] ],
     sendError: { failedPeer: [Object], notTriedList: [] } },
  'Apple-Iphone6-1_PT3392': 
   { peersList: [ [Object] ],
     sendList: [ [Object], [Object], [Object] ],
     sendError: { failedPeer: [Object], notTriedList: [] } },
  'Apple-IpadAir2-1_PT1077': 
   { peersList: [ [Object] ],
     sendList: [ [Object], [Object], [Object] ],
     sendError: { failedPeer: [Object], notTriedList: [] } } }

Server terminating normally


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
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:null 
child process exited with code null on device f56ad48d 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/50650278923ff9f_Enable_UnitTest_tobybrad/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/50650278923ff9f_Enable_UnitTest_tobybrad/thali01_samsung-SM-A500FU.md)

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
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/50650278923ff9f_Enable_UnitTest_tobybrad/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/50650278923ff9f_Enable_UnitTest_tobybrad/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/50650278923ff9f_Enable_UnitTest_tobybrad/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/50650278923ff9f_Enable_UnitTest_tobybrad/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/50650278923ff9f_Enable_UnitTest_tobybrad/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/50650278923ff9f_Enable_UnitTest_tobybrad/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/50650278923ff9f_Enable_UnitTest_tobybrad/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/50650278923ff9f_Enable_UnitTest_tobybrad/thali04_samsung-SM-G900F.md)

####Node name: thali05
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 1d6a772d app:com.test.thalitest code:null 
child process exited with code null on device 1d6a772d 
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:null 
child process exited with code null on device ZX1G429CRK 
Error! Unexpected exit on device 954a12ed app:com.test.thalitest code:0 
child process exited with code 0 on device 954a12ed 
Android task is completed. [FAILED]
```
[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/50650278923ff9f_Enable_UnitTest_tobybrad/thali05_samsung-SM-N9005.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/50650278923ff9f_Enable_UnitTest_tobybrad/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/50650278923ff9f_Enable_UnitTest_tobybrad/thali05_samsung-SM-G800H.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/50650278923ff9f_Enable_UnitTest_tobybrad/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/50650278923ff9f_Enable_UnitTest_tobybrad/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/50650278923ff9f_Enable_UnitTest_tobybrad/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/50650278923ff9f_Enable_UnitTest_tobybrad/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/50650278923ff9f_Enable_UnitTest_tobybrad/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/50650278923ff9f_Enable_UnitTest_tobybrad/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/50650278923ff9f_Enable_UnitTest_tobybrad/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/50650278923ff9f_Enable_UnitTest_tobybrad/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/50650278923ff9f_Enable_UnitTest_tobybrad/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/50650278923ff9f_Enable_UnitTest_tobybrad/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/50650278923ff9f_Enable_UnitTest_tobybrad/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/50650278923ff9f_Enable_UnitTest_tobybrad/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/50650278923ff9f_Enable_UnitTest_tobybrad/iOS_Iphone5s-1.md)



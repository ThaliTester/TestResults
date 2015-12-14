#### Test 50650278e3ff7c2 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":23}}
listening on *:3000

Starting perf test run for platform: ios

Using devices:
Apple-Iphone5s-1_PT4136
Apple-Iphone6-1_PT4340
Apple-Iphone5-1_PT3867

Apple-IpadAir2-1_PT6041

2015-12-14T13:44:02.097Z (8 sec) - ios test ID testFindPeers.js done now

testFindPeers.js (ios) results from: undefined

testFindPeers.js (ios) results from: undefined

testFindPeers.js (ios) results from: undefined

testFindPeers.js (ios) results from: undefined

Continuing to next test: testSendData.js

2015-12-14T13:45:43.370Z (109 sec) - ios test ID testSendData.js done now

testSendData.js (ios) results from: undefined

testSendData.js (ios) results from: undefined

testSendData.js (ios) results from: undefined

testSendData.js (ios) results from: undefined

ALL DONE !!!

{ 'name:': 'Apple-Iphone5s-1_PT4136',
  time: 687,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1_PT3867.cSCWVA==',
       peerAvailable: true,
       time: 684 } ] }

{ 'name:': 'Apple-Iphone6-1_PT4340',
  time: 2646,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1_PT3867.cSCWVA==',
       peerAvailable: true,
       time: 2644 } ] }

{ 'name:': 'Apple-Iphone5-1_PT3867',
  time: 1064,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1_PT6041.yRvsxw==',
       peerAvailable: true,
       time: 1063 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT6041',
  time: 1337,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1_PT3867.cSCWVA==',
       peerAvailable: true,
       time: 1335 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT4136',
  time: 53109,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1_PT3867.cSCWVA==',
       time: 41199,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1_PT3867.0mupng==',
       time: 3965,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT6041.byADbw==',
       time: 3686,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT4340.nJo87Q==',
       time: 4145,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1_PT4340',
  time: 53153,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1_PT3867.cSCWVA==',
       time: 42305,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT6041.byADbw==',
       time: 3494,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT3867.0mupng==',
       time: 3192,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT4136.aZvv+w==',
       time: 4063,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1_PT3867',
  time: 100924,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1_PT3867.cSCWVA==',
       time: 40671,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT4340.nJo87Q==',
       time: 44447,
       result: 'OK',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT6041.byADbw==',
       time: 11407,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT4136.aZvv+w==',
       time: 3854,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT6041',
  time: 57834,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4340.mBVNng==',
       time: 47562,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1_PT3867.0mupng==',
       time: 3464,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT4340.nJo87Q==',
       time: 3246,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT4136.aZvv+w==',
       time: 3502,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

--------------- test report ---------------------
--------------- Apple-Iphone5s-1_PT4136 --------------------- : 1

peersList : 100% : 684 ms, 99% : 684 ms, 95 : 684 ms, 90% : 684 ms.

Result count 1, range 684 ms to  684 ms.

sendList : 100% : 4145 ms, 99% : 4145 ms, 95 : 4145 ms, 90% : 4145 ms.

Average data rate: 0.025 MB/s

Result count 3, range 3686 ms to  4145 ms.

sendList failed peers count : 1 [25 %]

- Peer ID : Apple-Iphone5-1_PT3867.cSCWVA==, Tried : 5

sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone6-1_PT4340 --------------------- : 2
peersList : 100% : 2644 ms, 99% : 2644 ms, 95 : 2644 ms, 90% : 2644 ms.

Result count 1, range 2644 ms to  2644 ms.

sendList : 100% : 4063 ms, 99% : 4063 ms, 95 : 4063 ms, 90% : 4063 ms.

Average data rate: 0.028 MB/s
Result count 3, range 3192 ms to  4063 ms.

sendList failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone5-1_PT3867.cSCWVA==, Tried : 5

sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5-1_PT3867 --------------------- : 3

peersList : 100% : 1063 ms, 99% : 1063 ms, 95 : 1063 ms, 90% : 1063 ms.
Result count 1, range 1063 ms to  1063 ms.

sendList : 100% : 44447 ms, 99% : 44447 ms, 95 : 44447 ms, 90% : 44447 ms.
Average data rate: 0.005 MB/s

Result count 3, range 3854 ms to  44447 ms.
sendList failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone5-1_PT3867.cSCWVA==, Tried : 5

sendList never tried peers count : 0 [0 %]
--------------- Apple-IpadAir2-1_PT6041 --------------------- : 4

peersList : 100% : 1335 ms, 99% : 1335 ms, 95 : 1335 ms, 90% : 1335 ms.
Result count 1, range 1335 ms to  1335 ms.

sendList : 100% : 3502 ms, 99% : 3502 ms, 95 : 3502 ms, 90% : 3502 ms.

Average data rate: 0.029 MB/s

Result count 3, range 3246 ms to  3502 ms.
sendList failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone6-1_PT4340.mBVNng==, Tried : 5

sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------
peersList : 100% : 2644 ms, 99% : 2644 ms, 95 : 2644 ms, 90% : 2644 ms.

sendList : 100% : 44447 ms, 99% : 44447 ms, 95 : 11407 ms, 90% : 11407 ms.
Average data rate: 0.013 MB/s

--------------- end of test report ---------------------

{ 'Apple-Iphone5s-1_PT4136': 
   { peersList: [ [Object] ],
     sendList: [ [Object], [Object], [Object] ],
     sendError: { failedPeer: [Object], notTriedList: [] } },
  'Apple-Iphone6-1_PT4340': 
   { peersList: [ [Object] ],
     sendList: [ [Object], [Object], [Object] ],
     sendError: { failedPeer: [Object], notTriedList: [] } },
  'Apple-Iphone5-1_PT3867': 
   { peersList: [ [Object] ],
     sendList: [ [Object], [Object], [Object] ],
     sendError: { failedPeer: [Object], notTriedList: [] } },
  'Apple-IpadAir2-1_PT6041': 
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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/50650278e3ff7c2_Enable_UnitTest_tobybrad/thali01_LGE-LG-H815.md)

[HUAWEI-ALE-L21](https://github.com/ThaliTester/TestResults/blob/50650278e3ff7c2_Enable_UnitTest_tobybrad/thali01_HUAWEI-ALE-L21.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/50650278e3ff7c2_Enable_UnitTest_tobybrad/thali01_samsung-SM-A500FU.md)

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
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/50650278e3ff7c2_Enable_UnitTest_tobybrad/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/50650278e3ff7c2_Enable_UnitTest_tobybrad/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/50650278e3ff7c2_Enable_UnitTest_tobybrad/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/50650278e3ff7c2_Enable_UnitTest_tobybrad/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/50650278e3ff7c2_Enable_UnitTest_tobybrad/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/50650278e3ff7c2_Enable_UnitTest_tobybrad/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/50650278e3ff7c2_Enable_UnitTest_tobybrad/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/50650278e3ff7c2_Enable_UnitTest_tobybrad/thali04_samsung-SM-G900F.md)

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
[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/50650278e3ff7c2_Enable_UnitTest_tobybrad/thali05_samsung-SM-N9005.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/50650278e3ff7c2_Enable_UnitTest_tobybrad/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/50650278e3ff7c2_Enable_UnitTest_tobybrad/thali05_samsung-SM-G800H.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/50650278e3ff7c2_Enable_UnitTest_tobybrad/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/50650278e3ff7c2_Enable_UnitTest_tobybrad/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/50650278e3ff7c2_Enable_UnitTest_tobybrad/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device c5afcdcb app:com.test.thalitest code:null 
child process exited with code null on device c5afcdcb 
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:null 
child process exited with code null on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/50650278e3ff7c2_Enable_UnitTest_tobybrad/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/50650278e3ff7c2_Enable_UnitTest_tobybrad/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/50650278e3ff7c2_Enable_UnitTest_tobybrad/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/50650278e3ff7c2_Enable_UnitTest_tobybrad/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/50650278e3ff7c2_Enable_UnitTest_tobybrad/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/50650278e3ff7c2_Enable_UnitTest_tobybrad/thali09_LGE-Nexus 5.md)




###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/50650278e3ff7c2_Enable_UnitTest_tobybrad/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/50650278e3ff7c2_Enable_UnitTest_tobybrad/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/50650278e3ff7c2_Enable_UnitTest_tobybrad/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/50650278e3ff7c2_Enable_UnitTest_tobybrad/iOS_Iphone5-1.md)



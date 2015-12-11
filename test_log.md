#### Test 50650278f6345ef Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":23}}
listening on *:3000

Starting perf test run for platform: ios

Using devices: [object Object],[object Object],[object Object],[object Object]

2015-12-11T12:17:52.666Z (7 sec) - ios test ID testFindPeers.js done now

testFindPeers.js (ios) results from: undefined

testFindPeers.js (ios) results from: undefined

testFindPeers.js (ios) results from: undefined

testFindPeers.js (ios) results from: undefined

Continuing to next test: testSendData.js

Starting perf test run for platform: android

Using devices: [object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object]

2015-12-11T12:34:34.241Z (1008 sec) - ios test ID testSendData.js done now

testSendData.js (ios) results from: undefined

testSendData.js (ios) results from: undefined

testSendData.js (ios) results from: undefined

testSendData.js (ios) results from: undefined

ALL DONE !!!

{ 'name:': 'Apple-IpadAir2-1_PT8639',
  time: 1113,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT7734.5CC0vg==',
       peerAvailable: true,
       time: 1111 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT1055',
  time: 720,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1_PT6904.k/CT+g==',
       peerAvailable: true,
       time: 718 } ] }

{ 'name:': 'Apple-Iphone6-1_PT7734',
  time: 1230,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1_PT8639.QAAa6w==',
       peerAvailable: true,
       time: 1227 } ] }

{ 'name:': 'Apple-Iphone5-1_PT6904',
  time: 1737,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT7734.5CC0vg==',
       peerAvailable: true,
       time: 1736 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT8639',
  time: 54377,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT7734.5CC0vg==',
       time: 41578,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1_PT1055.SsV7MA==',
       time: 6119,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT7734.oRkpZA==',
       time: 2773,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT6904.Jd0UjA==',
       time: 3059,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT1055',
  time: 57469,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1_PT6904.k/CT+g==',
       time: 42389,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT7734.oRkpZA==',
       time: 8667,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT8639.AH2xbQ==',
       time: 3075,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT6904.Jd0UjA==',
       time: 3190,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1_PT7734',
  time: 53752,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT7734.5CC0vg==',
       time: 40175,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1_PT1055.SsV7MA==',
       time: 6485,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT8639.AH2xbQ==',
       time: 2922,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT6904.Jd0UjA==',
       time: 3010,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1_PT6904',
  time: 1000042,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'Apple-Iphone5s-1_PT1055.SsV7MA==',
       time: 3511,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT7734.oRkpZA==',
       time: 3846,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT8639.AH2xbQ==',
       time: 4950,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

--------------- test report ---------------------
--------------- Apple-IpadAir2-1_PT8639 --------------------- : 1

peersList : 100% : 1111 ms, 99% : 1111 ms, 95 : 1111 ms, 90% : 1111 ms.

Result count 1, range 1111 ms to  1111 ms.

sendList : 100% : 6119 ms, 99% : 6119 ms, 95 : 6119 ms, 90% : 6119 ms.

Average data rate: 0.025 MB/s

Result count 3, range 2773 ms to  6119 ms.

sendList failed peers count : 1 [25 %]

- Peer ID : Apple-Iphone6-1_PT7734.5CC0vg==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5s-1_PT1055 --------------------- : 2
peersList : 100% : 718 ms, 99% : 718 ms, 95 : 718 ms, 90% : 718 ms.

Result count 1, range 718 ms to  718 ms.
sendList : 100% : 8667 ms, 99% : 8667 ms, 95 : 8667 ms, 90% : 8667 ms.

Average data rate: 0.02 MB/s
Result count 3, range 3075 ms to  8667 ms.
sendList failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone5-1_PT6904.k/CT+g==, Tried : 5

sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1_PT7734 --------------------- : 3

peersList : 100% : 1227 ms, 99% : 1227 ms, 95 : 1227 ms, 90% : 1227 ms.
Result count 1, range 1227 ms to  1227 ms.
sendList : 100% : 6485 ms, 99% : 6485 ms, 95 : 6485 ms, 90% : 6485 ms.
Average data rate: 0.024 MB/s

Result count 3, range 2922 ms to  6485 ms.
sendList failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone6-1_PT7734.5CC0vg==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5-1_PT6904 --------------------- : 4
peersList : 100% : 1736 ms, 99% : 1736 ms, 95 : 1736 ms, 90% : 1736 ms.
Result count 1, range 1736 ms to  1736 ms.

sendList : 100% : 4950 ms, 99% : 4950 ms, 95 : 4950 ms, 90% : 4950 ms.
Average data rate: 0.024 MB/s
Result count 3, range 3511 ms to  4950 ms.
sendList failed peers count : 0 [0 %]

sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------
peersList : 100% : 1736 ms, 99% : 1736 ms, 95 : 1736 ms, 90% : 1736 ms.

sendList : 100% : 8667 ms, 99% : 8667 ms, 95 : 6485 ms, 90% : 6485 ms.

Average data rate: 0.023 MB/s
--------------- end of test report ---------------------

{ 'Apple-IpadAir2-1_PT8639': 
   { peersList: [ [Object] ],
     sendList: [ [Object], [Object], [Object] ],
     sendError: { failedPeer: [Object], notTriedList: [] } },
  'Apple-Iphone5s-1_PT1055': 
   { peersList: [ [Object] ],
     sendList: [ [Object], [Object], [Object] ],
     sendError: { failedPeer: [Object], notTriedList: [] } },
  'Apple-Iphone6-1_PT7734': 
   { peersList: [ [Object] ],
     sendList: [ [Object], [Object], [Object] ],
     sendError: { failedPeer: [Object], notTriedList: [] } },
  'Apple-Iphone5-1_PT6904': 
   { peersList: [ [Object] ],
     sendList: [ [Object], [Object], [Object] ],
     sendError: { failedPeer: [], notTriedList: [] } } }

2015-12-11T12:34:36.892Z (1011 sec) - android test ID testFindPeers.js done now

testFindPeers.js (android) results from: undefined

testFindPeers.js (android) results from: undefined

testFindPeers.js (android) results from: undefined

testFindPeers.js (android) results from: undefined

testFindPeers.js (android) results from: undefined

testFindPeers.js (android) results from: undefined

testFindPeers.js (android) results from: undefined

testFindPeers.js (android) results from: undefined

testFindPeers.js (android) results from: undefined

testFindPeers.js (android) results from: undefined
testFindPeers.js (android) results from: undefined

testFindPeers.js (android) results from: undefined

testFindPeers.js (android) results from: undefined

testFindPeers.js (android) results from: undefined
testFindPeers.js (android) results from: undefined

testFindPeers.js (android) results from: undefined

testFindPeers.js (android) results from: undefined

testFindPeers.js (android) results from: undefined

testFindPeers.js (android) results from: undefined
testFindPeers.js (android) results from: undefined

testFindPeers.js (android) results from: undefined

testFindPeers.js (android) results from: undefined
testFindPeers.js (android) results from: undefined

Continuing to next test: testSendData.js

server timeout for test: testFindPeers.js

server timeout for test: testFindPeers.js

server timeout for test: testFindPeers.js

server timeout for test: testSendData.js

server timeout for test: testSendData.js

server timeout for test: testSendData.js

server timeout for test: testFindPeers.js

server timeout for test: testFindPeers.js

server timeout for test: testFindPeers.js

server timeout for test: testFindPeers.js
server timeout for test: testFindPeers.js

server timeout for test: testFindPeers.js

server timeout for test: testFindPeers.js
server timeout for test: testFindPeers.js

server timeout for test: testFindPeers.js

server timeout for test: testFindPeers.js
server timeout for test: testFindPeers.js
server timeout for test: testFindPeers.js

server timeout for test: testFindPeers.js
server timeout for test: testFindPeers.js

server timeout for test: testFindPeers.js

server timeout for test: testFindPeers.js

server timeout for test: testFindPeers.js
server timeout for test: testFindPeers.js

server timeout for test: testFindPeers.js
server timeout for test: testFindPeers.js

server timeout for test: testFindPeers.js
server timeout for test: testFindPeers.js


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/50650278f6345ef_Enable_UnitTest_tobybrad/thali01_LGE-LG-H815.md)

[HUAWEI-ALE-L21](https://github.com/ThaliTester/TestResults/blob/50650278f6345ef_Enable_UnitTest_tobybrad/thali01_HUAWEI-ALE-L21.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/50650278f6345ef_Enable_UnitTest_tobybrad/thali01_samsung-SM-A500FU.md)

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
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/50650278f6345ef_Enable_UnitTest_tobybrad/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/50650278f6345ef_Enable_UnitTest_tobybrad/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/50650278f6345ef_Enable_UnitTest_tobybrad/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/50650278f6345ef_Enable_UnitTest_tobybrad/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/50650278f6345ef_Enable_UnitTest_tobybrad/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/50650278f6345ef_Enable_UnitTest_tobybrad/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/50650278f6345ef_Enable_UnitTest_tobybrad/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/50650278f6345ef_Enable_UnitTest_tobybrad/thali04_samsung-SM-G900F.md)

####Node name: thali05
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 1d6a772d app:com.test.thalitest code:null 
child process exited with code null on device 1d6a772d 
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:null 
child process exited with code null on device ZX1G429CRK 
Error! Unexpected exit on device 954a12ed app:com.test.thalitest code:null 
child process exited with code null on device 954a12ed 
Android task is completed. [FAILED]
```
[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/50650278f6345ef_Enable_UnitTest_tobybrad/thali05_samsung-SM-N9005.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/50650278f6345ef_Enable_UnitTest_tobybrad/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/50650278f6345ef_Enable_UnitTest_tobybrad/thali05_samsung-SM-G800H.md)

####Node name: thali06
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:0 
child process exited with code 0 on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:null 
child process exited with code null on device FA55PYS00566 
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:null 
child process exited with code null on device 022678fb504e29b0 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/50650278f6345ef_Enable_UnitTest_tobybrad/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/50650278f6345ef_Enable_UnitTest_tobybrad/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/50650278f6345ef_Enable_UnitTest_tobybrad/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/50650278f6345ef_Enable_UnitTest_tobybrad/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/50650278f6345ef_Enable_UnitTest_tobybrad/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/50650278f6345ef_Enable_UnitTest_tobybrad/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/50650278f6345ef_Enable_UnitTest_tobybrad/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device CC51WYC03425 app:com.test.thalitest code:null 
child process exited with code null on device CC51WYC03425 
Error! Unexpected exit on device 0c6a0f3c0bdb4e77 app:com.test.thalitest code:0 
child process exited with code 0 on device 0c6a0f3c0bdb4e77 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/50650278f6345ef_Enable_UnitTest_tobybrad/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/50650278f6345ef_Enable_UnitTest_tobybrad/thali09_LGE-Nexus 5.md)




###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/50650278f6345ef_Enable_UnitTest_tobybrad/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/50650278f6345ef_Enable_UnitTest_tobybrad/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/50650278f6345ef_Enable_UnitTest_tobybrad/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/50650278f6345ef_Enable_UnitTest_tobybrad/iOS_Iphone5-1.md)



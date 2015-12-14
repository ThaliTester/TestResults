#### Test 50650278b2f31ec Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":23}}
listening on *:3000

New device presented: motorola-XT1072_PT9551 perftest

New device presented: LGE-LG-H815_PT3806 perftest

New device presented: LGE-Nexus 5_PT4491 perftest

New device presented: samsung-SM-G900F_PT8970 perftest

New device presented: LGE-LG-D802_PT5671 perftest

New device presented: samsung-SM-A300FU_PT8079 perftest

New device presented: samsung-SM-A500FU_PT3493 perftest

New device presented: HUAWEI-ALE-L21_PT7588 perftest

New device presented: HTC-HTC Desire 820_PT164 perftest

New device presented: samsung-SM-N9005_PT5861 perftest

New device presented: Apple-IpadAir2-1_PT4459 perftest

New device presented: HTC-HTC One M8s_PT3554 perftest

New device presented: motorola-Nexus 6_PT1651 perftest

New device presented: HTC-HTC Desire 820_PT7543 perftest

New device presented: samsung-SM-G900F_PT9177 perftest

New device presented: Apple-Iphone6-1_PT9995 perftest

New device presented: samsung-SM-A500FU_PT3578 perftest

New device presented: LGE-Nexus 5_PT1076 perftest

New device presented: samsung-SM-G800H_PT3132 perftest

New device presented: samsung-SM-A300FU_PT652 perftest

New device presented: Apple-Iphone5-1_PT9827 perftest

New device presented: LGE-LG-D722_PT9795 perftest

New device presented: Apple-Iphone5s-1_PT2942 perftest

Starting perf test run for platform: ios

Using devices:
Apple-IpadAir2-1_PT4459

Apple-Iphone6-1_PT9995
Apple-Iphone5-1_PT9827

Apple-Iphone5s-1_PT2942

New device presented: samsung-SM-N910C_PT3251 perftest

New device presented: samsung-SM-G800F_PT8535 perftest

New device presented: LGE-LG-D855_PT5184 perftest

2015-12-14T14:42:02.437Z (7 sec) - ios test ID testFindPeers.js done now

testFindPeers.js (ios) results from: Apple-IpadAir2-1_PT4459

testFindPeers.js (ios) results from: Apple-Iphone6-1_PT9995

testFindPeers.js (ios) results from: Apple-Iphone5-1_PT9827

testFindPeers.js (ios) results from: Apple-Iphone5s-1_PT2942

Continuing to next test: testSendData.js

New device presented: motorola-XT1039_PT5202 perftest

Starting perf test run for platform: android
Using devices:
motorola-XT1072_PT9551
LGE-LG-H815_PT3806
LGE-Nexus 5_PT4491
samsung-SM-G900F_PT8970
LGE-LG-D802_PT5671
samsung-SM-A300FU_PT8079
samsung-SM-A500FU_PT3493
HUAWEI-ALE-L21_PT7588
HTC-HTC Desire 820_PT164
samsung-SM-N9005_PT5861
HTC-HTC One M8s_PT3554
motorola-Nexus 6_PT1651
HTC-HTC Desire 820_PT7543
samsung-SM-G900F_PT9177
samsung-SM-A500FU_PT3578
LGE-Nexus 5_PT1076
samsung-SM-G800H_PT3132
samsung-SM-A300FU_PT652
LGE-LG-D722_PT9795
samsung-SM-N910C_PT3251

samsung-SM-G800F_PT8535
LGE-LG-D855_PT5184
motorola-XT1039_PT5202

2015-12-14T14:43:36.423Z (101 sec) - ios test ID testSendData.js done now

testSendData.js (ios) results from: Apple-IpadAir2-1_PT4459

testSendData.js (ios) results from: Apple-Iphone6-1_PT9995

testSendData.js (ios) results from: Apple-Iphone5-1_PT9827

testSendData.js (ios) results from: Apple-Iphone5s-1_PT2942

ALL DONE !!!

{ 'name:': 'Apple-IpadAir2-1_PT4459',
  time: 1056,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT9995.u0gQiQ==',
       peerAvailable: true,
       time: 1055 } ] }

{ 'name:': 'Apple-Iphone6-1_PT9995',
  time: 1637,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1_PT4459.Sbdxaw==',
       peerAvailable: true,
       time: 1635 } ] }

{ 'name:': 'Apple-Iphone5-1_PT9827',
  time: 1296,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1_PT4459.Sbdxaw==',
       peerAvailable: true,
       time: 1294 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT2942',
  time: 1812,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1_PT4459.Sbdxaw==',
       peerAvailable: true,
       time: 1810 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT4459',
  time: 53828,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1_PT9827.emG9ZA==',
       time: 40953,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT9995.Xv3OoQ==',
       time: 3431,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT9827.8xg46g==',
       time: 4836,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT2942.N5Uy6w==',
       time: 3589,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1_PT9995',
  time: 53222,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT9995.u0gQiQ==',
       time: 41222,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT4459.LRQ+wA==',
       time: 4120,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT9827.8xg46g==',
       time: 4425,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT2942.N5Uy6w==',
       time: 3245,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1_PT9827',
  time: 93475,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1_PT9827.emG9ZA==',
       time: 41144,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT9995.Xv3OoQ==',
       time: 44452,
       result: 'OK',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT4459.LRQ+wA==',
       time: 3903,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT2942.N5Uy6w==',
       time: 3802,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT2942',
  time: 54117,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT4459.Sbdxaw==',
       time: 41112,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT9995.Xv3OoQ==',
       time: 4684,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT9827.8xg46g==',
       time: 4381,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT4459.LRQ+wA==',
       time: 3630,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

--------------- test report ---------------------
--------------- Apple-IpadAir2-1_PT4459 --------------------- : 1

peersList : 100% : 1055 ms, 99% : 1055 ms, 95 : 1055 ms, 90% : 1055 ms.

Result count 1, range 1055 ms to  1055 ms.

sendList : 100% : 4836 ms, 99% : 4836 ms, 95 : 4836 ms, 90% : 4836 ms.

Average data rate: 0.025 MB/s

Result count 3, range 3431 ms to  4836 ms.

sendList failed peers count : 1 [25 %]

- Peer ID : Apple-Iphone5-1_PT9827.emG9ZA==, Tried : 5

sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1_PT9995 --------------------- : 2
peersList : 100% : 1635 ms, 99% : 1635 ms, 95 : 1635 ms, 90% : 1635 ms.

Result count 1, range 1635 ms to  1635 ms.
sendList : 100% : 4425 ms, 99% : 4425 ms, 95 : 4425 ms, 90% : 4425 ms.

Average data rate: 0.025 MB/s
Result count 3, range 3245 ms to  4425 ms.

sendList failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone6-1_PT9995.u0gQiQ==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5-1_PT9827 --------------------- : 3
peersList : 100% : 1294 ms, 99% : 1294 ms, 95 : 1294 ms, 90% : 1294 ms.

Result count 1, range 1294 ms to  1294 ms.
sendList : 100% : 44452 ms, 99% : 44452 ms, 95 : 44452 ms, 90% : 44452 ms.
Average data rate: 0.006 MB/s
Result count 3, range 3802 ms to  44452 ms.

sendList failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone5-1_PT9827.emG9ZA==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5s-1_PT2942 --------------------- : 4
peersList : 100% : 1810 ms, 99% : 1810 ms, 95 : 1810 ms, 90% : 1810 ms.
Result count 1, range 1810 ms to  1810 ms.

sendList : 100% : 4684 ms, 99% : 4684 ms, 95 : 4684 ms, 90% : 4684 ms.
Average data rate: 0.024 MB/s
Result count 3, range 3630 ms to  4684 ms.
sendList failed peers count : 1 [25 %]

- Peer ID : Apple-IpadAir2-1_PT4459.Sbdxaw==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------

peersList : 100% : 1810 ms, 99% : 1810 ms, 95 : 1810 ms, 90% : 1810 ms.

sendList : 100% : 44452 ms, 99% : 44452 ms, 95 : 4836 ms, 90% : 4836 ms.
Average data rate: 0.014 MB/s

--------------- end of test report ---------------------

{ 'Apple-IpadAir2-1_PT4459': 
   { peersList: [ [Object] ],
     sendList: [ [Object], [Object], [Object] ],
     sendError: { failedPeer: [Object], notTriedList: [] } },
  'Apple-Iphone6-1_PT9995': 
   { peersList: [ [Object] ],
     sendList: [ [Object], [Object], [Object] ],
     sendError: { failedPeer: [Object], notTriedList: [] } },
  'Apple-Iphone5-1_PT9827': 
   { peersList: [ [Object] ],
     sendList: [ [Object], [Object], [Object] ],
     sendError: { failedPeer: [Object], notTriedList: [] } },
  'Apple-Iphone5s-1_PT2942': 
   { peersList: [ [Object] ],
     sendList: [ [Object], [Object], [Object] ],
     sendError: { failedPeer: [Object], notTriedList: [] } } }

-------- Starting perf test for android (after timeout) --------

Starting perf test run for platform: android

Using devices:

motorola-XT1072_PT9551
LGE-LG-H815_PT3806
LGE-Nexus 5_PT4491
samsung-SM-G900F_PT8970
LGE-LG-D802_PT5671
samsung-SM-A300FU_PT8079

samsung-SM-A500FU_PT3493
HUAWEI-ALE-L21_PT7588
HTC-HTC Desire 820_PT164
samsung-SM-N9005_PT5861
HTC-HTC One M8s_PT3554
motorola-Nexus 6_PT1651

HTC-HTC Desire 820_PT7543
samsung-SM-G900F_PT9177
samsung-SM-A500FU_PT3578
LGE-Nexus 5_PT1076
samsung-SM-G800H_PT3132
samsung-SM-A300FU_PT652

LGE-LG-D722_PT9795
samsung-SM-N910C_PT3251
samsung-SM-G800F_PT8535
LGE-LG-D855_PT5184
motorola-XT1039_PT5202

2015-12-14T14:43:57.590Z (122 sec) - android test ID testFindPeers.js done now

testFindPeers.js (android) results from: motorola-XT1072_PT9551

testFindPeers.js (android) results from: LGE-LG-H815_PT3806

testFindPeers.js (android) results from: LGE-Nexus 5_PT4491
testFindPeers.js (android) results from: samsung-SM-G900F_PT8970

testFindPeers.js (android) results from: LGE-LG-D802_PT5671
testFindPeers.js (android) results from: samsung-SM-A300FU_PT8079

testFindPeers.js (android) results from: samsung-SM-A500FU_PT3493

testFindPeers.js (android) results from: HUAWEI-ALE-L21_PT7588
testFindPeers.js (android) results from: HTC-HTC Desire 820_PT164

testFindPeers.js (android) results from: samsung-SM-N9005_PT5861
testFindPeers.js (android) results from: HTC-HTC One M8s_PT3554

testFindPeers.js (android) results from: motorola-Nexus 6_PT1651
testFindPeers.js (android) results from: HTC-HTC Desire 820_PT7543

testFindPeers.js (android) results from: samsung-SM-G900F_PT9177
testFindPeers.js (android) results from: samsung-SM-A500FU_PT3578

testFindPeers.js (android) results from: LGE-Nexus 5_PT1076

testFindPeers.js (android) results from: samsung-SM-G800H_PT3132

testFindPeers.js (android) results from: samsung-SM-A300FU_PT652

testFindPeers.js (android) results from: LGE-LG-D722_PT9795
testFindPeers.js (android) results from: samsung-SM-N910C_PT3251

testFindPeers.js (android) results from: samsung-SM-G800F_PT8535

testFindPeers.js (android) results from: LGE-LG-D855_PT5184

testFindPeers.js (android) results from: motorola-XT1039_PT5202

Continuing to next test: testSendData.js

-------- Starting perf test for ios (after timeout) --------

Starting perf test run for platform: ios
Using devices:
Apple-IpadAir2-1_PT4459
Apple-Iphone6-1_PT9995

Apple-Iphone5-1_PT9827
Apple-Iphone5s-1_PT2942

2015-12-14T14:44:01.528Z (126 sec) - android test ID testFindPeers.js done now

testFindPeers.js (android) results from: motorola-XT1072_PT9551

testFindPeers.js (android) results from: LGE-LG-H815_PT3806

testFindPeers.js (android) results from: LGE-Nexus 5_PT4491

testFindPeers.js (android) results from: samsung-SM-G900F_PT8970

testFindPeers.js (android) results from: LGE-LG-D802_PT5671
testFindPeers.js (android) results from: samsung-SM-A300FU_PT8079

testFindPeers.js (android) results from: samsung-SM-A500FU_PT3493
testFindPeers.js (android) results from: HUAWEI-ALE-L21_PT7588
testFindPeers.js (android) results from: HTC-HTC Desire 820_PT164
testFindPeers.js (android) results from: samsung-SM-N9005_PT5861
testFindPeers.js (android) results from: HTC-HTC One M8s_PT3554

testFindPeers.js (android) results from: motorola-Nexus 6_PT1651

testFindPeers.js (android) results from: HTC-HTC Desire 820_PT7543

testFindPeers.js (android) results from: samsung-SM-G900F_PT9177

testFindPeers.js (android) results from: samsung-SM-A500FU_PT3578
testFindPeers.js (android) results from: LGE-Nexus 5_PT1076

testFindPeers.js (android) results from: samsung-SM-G800H_PT3132

testFindPeers.js (android) results from: samsung-SM-A300FU_PT652
testFindPeers.js (android) results from: LGE-LG-D722_PT9795
testFindPeers.js (android) results from: samsung-SM-N910C_PT3251

testFindPeers.js (android) results from: samsung-SM-G800F_PT8535
testFindPeers.js (android) results from: LGE-LG-D855_PT5184
testFindPeers.js (android) results from: motorola-XT1039_PT5202
Continuing to next test: testSendData.js

New device presented: motorola-XT1039_PT5202 perftest

New device presented: HTC-HTC Desire 820_PT164 perftest

New device presented: HTC-HTC Desire 820_PT7543 perftest

New device presented: LGE-LG-D722_PT9795 perftest

New device presented: HTC-HTC Desire 820_PT164 perftest

New device presented: HTC-HTC Desire 820_PT164 perftest

New device presented: LGE-Nexus 5_PT4491 perftest

New device presented: motorola-XT1072_PT9551 perftest

New device presented: samsung-SM-A300FU_PT652 perftest

New device presented: HTC-HTC Desire 820_PT164 perftest

New device presented: LGE-Nexus 5_PT1076 perftest

New device presented: motorola-Nexus 6_PT1651 perftest

New device presented: HTC-HTC Desire 820_PT7543 perftest

New device presented: LGE-Nexus 5_PT1076 perftest

New device presented: LGE-LG-D722_PT9795 perftest

New device presented: LGE-LG-D722_PT9795 perftest

New device presented: motorola-Nexus 6_PT1651 perftest

New device presented: LGE-LG-D855_PT5184 perftest

New device presented: LGE-LG-D802_PT5671 perftest

New device presented: LGE-Nexus 5_PT1076 perftest

New device presented: LGE-Nexus 5_PT1076 perftest

New device presented: HTC-HTC Desire 820_PT7543 perftest

New device presented: motorola-XT1039_PT5202 perftest

New device presented: HTC-HTC One M8s_PT3554 perftest

New device presented: LGE-Nexus 5_PT1076 perftest

New device presented: LGE-Nexus 5_PT1076 perftest

New device presented: HTC-HTC Desire 820_PT7543 perftest

New device presented: LGE-LG-D802_PT5671 perftest

New device presented: LGE-LG-D722_PT9795 perftest

New device presented: samsung-SM-G800F_PT8535 perftest

New device presented: LGE-Nexus 5_PT1076 perftest

New device presented: HTC-HTC Desire 820_PT7543 perftest

New device presented: motorola-XT1039_PT5202 perftest

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

New device presented: motorola-XT1072_PT9551 perftest

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

server timeout for test: testSendData.js
server timeout for test: testSendData.js

server timeout for test: testSendData.js

server timeout for test: testSendData.js
server timeout for test: testSendData.js

server timeout for test: testSendData.js

server timeout for test: testSendData.js
server timeout for test: testSendData.js
server timeout for test: testSendData.js
server timeout for test: testSendData.js
server timeout for test: testSendData.js

server timeout for test: testSendData.js

server timeout for test: testSendData.js

server timeout for test: testSendData.js
server timeout for test: testSendData.js
server timeout for test: testSendData.js

server timeout for test: testSendData.js
server timeout for test: testSendData.js

server timeout for test: testSendData.js
server timeout for test: testSendData.js
server timeout for test: testSendData.js

server timeout for test: testSendData.js

server timeout for test: testFindPeers.js

server timeout for test: testFindPeers.js
server timeout for test: testFindPeers.js

server timeout for test: testFindPeers.js

server timeout for test: testSendData.js

server timeout for test: testSendData.js

server timeout for test: testSendData.js
server timeout for test: testSendData.js

server timeout for test: testSendData.js
server timeout for test: testSendData.js
server timeout for test: testSendData.js

server timeout for test: testSendData.js

server timeout for test: testSendData.js

server timeout for test: testSendData.js
server timeout for test: testSendData.js

server timeout for test: testSendData.js

server timeout for test: testSendData.js
server timeout for test: testSendData.js

server timeout for test: testSendData.js
server timeout for test: testSendData.js

server timeout for test: testSendData.js

server timeout for test: testSendData.js

server timeout for test: testSendData.js

server timeout for test: testSendData.js
server timeout for test: testSendData.js
server timeout for test: testSendData.js

New device presented: motorola-Nexus 6_PT1651 perftest

New device presented: motorola-XT1072_PT9551 perftest

New device presented: HUAWEI-ALE-L21_PT7588 perftest

New device presented: LGE-LG-H815_PT3806 perftest

New device presented: samsung-SM-N9005_PT5861 perftest

New device presented: HTC-HTC One M8s_PT3554 perftest

New device presented: motorola-Nexus 6_PT1651 perftest


 
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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/50650278b2f31ec_Enable_UnitTest_tobybrad/thali01_LGE-LG-H815.md)

[HUAWEI-ALE-L21](https://github.com/ThaliTester/TestResults/blob/50650278b2f31ec_Enable_UnitTest_tobybrad/thali01_HUAWEI-ALE-L21.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/50650278b2f31ec_Enable_UnitTest_tobybrad/thali01_samsung-SM-A500FU.md)

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
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/50650278b2f31ec_Enable_UnitTest_tobybrad/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/50650278b2f31ec_Enable_UnitTest_tobybrad/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/50650278b2f31ec_Enable_UnitTest_tobybrad/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/50650278b2f31ec_Enable_UnitTest_tobybrad/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/50650278b2f31ec_Enable_UnitTest_tobybrad/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/50650278b2f31ec_Enable_UnitTest_tobybrad/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/50650278b2f31ec_Enable_UnitTest_tobybrad/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/50650278b2f31ec_Enable_UnitTest_tobybrad/thali04_samsung-SM-G900F.md)

####Node name: thali05
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 1d6a772d app:com.test.thalitest code:null 
child process exited with code null on device 1d6a772d 
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1G429CRK 
Error! Unexpected exit on device 954a12ed app:com.test.thalitest code:null 
child process exited with code null on device 954a12ed 
Android task is completed. [FAILED]
```
[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/50650278b2f31ec_Enable_UnitTest_tobybrad/thali05_samsung-SM-N9005.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/50650278b2f31ec_Enable_UnitTest_tobybrad/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/50650278b2f31ec_Enable_UnitTest_tobybrad/thali05_samsung-SM-G800H.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/50650278b2f31ec_Enable_UnitTest_tobybrad/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/50650278b2f31ec_Enable_UnitTest_tobybrad/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/50650278b2f31ec_Enable_UnitTest_tobybrad/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/50650278b2f31ec_Enable_UnitTest_tobybrad/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/50650278b2f31ec_Enable_UnitTest_tobybrad/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/50650278b2f31ec_Enable_UnitTest_tobybrad/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/50650278b2f31ec_Enable_UnitTest_tobybrad/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/50650278b2f31ec_Enable_UnitTest_tobybrad/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/50650278b2f31ec_Enable_UnitTest_tobybrad/thali09_LGE-Nexus 5.md)




###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/50650278b2f31ec_Enable_UnitTest_tobybrad/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/50650278b2f31ec_Enable_UnitTest_tobybrad/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/50650278b2f31ec_Enable_UnitTest_tobybrad/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/50650278b2f31ec_Enable_UnitTest_tobybrad/iOS_Iphone5-1.md)



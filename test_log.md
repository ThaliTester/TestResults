#### Test 50650278ee43ca0 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":23}}
listening on *:3000

New device presented: LGE-Nexus 5_PT5145 (android) perftest

1 android devices presented

New device presented: LGE-LG-D802_PT349 (android) perftest

2 android devices presented

New device presented: samsung-SM-A500FU_PT4039 (android) perftest

3 android devices presented

New device presented: samsung-SM-A300FU_PT6932 (android) perftest

4 android devices presented

New device presented: samsung-SM-A300FU_PT5619 (android) perftest

5 android devices presented

New device presented: motorola-XT1072_PT9222 (android) perftest

6 android devices presented

New device presented: LGE-Nexus 5_PT1299 (android) perftest

7 android devices presented

New device presented: LGE-LG-D722_PT6503 (android) perftest

8 android devices presented

New device presented: samsung-SM-G900F_PT5051 (android) perftest

9 android devices presented

New device presented: HTC-HTC One M8s_PT5468 (android) perftest

10 android devices presented

New device presented: HTC-HTC Desire 820_PT2765 (android) perftest

11 android devices presented

New device presented: samsung-SM-G900F_PT7800 (android) perftest

12 android devices presented

New device presented: Apple-IpadAir2-1_PT1010 (ios) perftest
1 ios devices presented

New device presented: HUAWEI-ALE-L21_PT6057 (android) perftest

13 android devices presented

New device presented: LGE-LG-H815_PT4197 (android) perftest

14 android devices presented

New device presented: motorola-Nexus 6_PT1658 (android) perftest

15 android devices presented

New device presented: samsung-SM-N9005_PT3106 (android) perftest
16 android devices presented

New device presented: Apple-Iphone5-1_PT2557 (ios) perftest

2 ios devices presented

New device presented: HTC-HTC Desire 820_PT1757 (android) perftest

17 android devices presented

New device presented: LGE-LG-D855_PT3010 (android) perftest

18 android devices presented

New device presented: Apple-Iphone6-1_PT9306 (ios) perftest

3 ios devices presented

New device presented: samsung-SM-G800H_PT1658 (android) perftest

19 android devices presented

New device presented: samsung-SM-N910C_PT6734 (android) perftest

20 android devices presented

New device presented: samsung-SM-A500FU_PT3932 (android) perftest

21 android devices presented

New device presented: Apple-Iphone5s-1_PT6308 (ios) perftest

4 ios devices presented

Starting perf test run for platform: ios

Using devices:

Apple-IpadAir2-1_PT1010
Apple-Iphone5-1_PT2557
Apple-Iphone6-1_PT9306

Apple-Iphone5s-1_PT6308

Setting: 4

4

3

New device presented: samsung-SM-G800F_PT9986 (android) perftest

22 android devices presented

2

1

All test data retrieved for testFindPeers.js (ios)

2015-12-15T04:06:34.252Z (8 sec) - ios test ID testFindPeers.js done now

testFindPeers.js (ios) results from: Apple-IpadAir2-1_PT1010

testFindPeers.js (ios) results from: Apple-Iphone5-1_PT2557

testFindPeers.js (ios) results from: Apple-Iphone6-1_PT9306

testFindPeers.js (ios) results from: Apple-Iphone5s-1_PT6308

Continuing to next test: testSendData.js

Setting: 4

Start timeout elapsed for platform: android

Starting perf test run for platform: android
Using devices:
LGE-Nexus 5_PT5145

LGE-LG-D802_PT349
samsung-SM-A500FU_PT4039

samsung-SM-A300FU_PT6932
samsung-SM-A300FU_PT5619
motorola-XT1072_PT9222
LGE-Nexus 5_PT1299

LGE-LG-D722_PT6503
samsung-SM-G900F_PT5051

HTC-HTC One M8s_PT5468

HTC-HTC Desire 820_PT2765

samsung-SM-G900F_PT7800
HUAWEI-ALE-L21_PT6057
LGE-LG-H815_PT4197

motorola-Nexus 6_PT1658
samsung-SM-N9005_PT3106
HTC-HTC Desire 820_PT1757

LGE-LG-D855_PT3010
samsung-SM-G800H_PT1658
samsung-SM-N910C_PT6734

samsung-SM-A500FU_PT3932
samsung-SM-G800F_PT9986

Setting: 22

22

21

20

19

18

17

16

15

14

13

12

11

10

9

8

7

6

5

4

3

2

4

3

2

1

All test data retrieved for testSendData.js (ios)

2015-12-15T04:07:28.482Z (62 sec) - ios test ID testSendData.js done now
testSendData.js (ios) results from: Apple-IpadAir2-1_PT1010

testSendData.js (ios) results from: Apple-Iphone5-1_PT2557

testSendData.js (ios) results from: Apple-Iphone6-1_PT9306

testSendData.js (ios) results from: Apple-Iphone5s-1_PT6308
ALL DONE !!!

{ 'name:': 'Apple-IpadAir2-1_PT1010',
  time: 1121,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT9306.6VQMVQ==',
       peerAvailable: true,
       time: 1118 } ] }

{ 'name:': 'Apple-Iphone5-1_PT2557',
  time: 1027,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1_PT1010.7Cf2mQ==',
       peerAvailable: true,
       time: 1025 } ] }

{ 'name:': 'Apple-Iphone6-1_PT9306',
  time: 1057,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1_PT1010.7Cf2mQ==',
       peerAvailable: true,
       time: 1055 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT6308',
  time: 2333,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1_PT2557.cLGdMA==',
       peerAvailable: true,
       time: 2330 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT1010',
  time: 53447,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT1010.7Cf2mQ==',
       time: 41129,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT9306.EdsImg==',
       time: 4541,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT6308.z27btQ==',
       time: 3547,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT2557.fyiFnQ==',
       time: 4014,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1_PT2557',
  time: 53220,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5s-1_PT6308.pQEQSw==',
       time: 41058,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT9306.EdsImg==',
       time: 3689,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT6308.z27btQ==',
       time: 4007,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT1010.g7hIzw==',
       time: 3431,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1_PT9306',
  time: 52177,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5s-1_PT6308.pQEQSw==',
       time: 42263,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1_PT6308.z27btQ==',
       time: 3369,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT1010.g7hIzw==',
       time: 3119,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT2557.fyiFnQ==',
       time: 3279,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT6308',
  time: 52900,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5s-1_PT6308.pQEQSw==',
       time: 40752,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT9306.EdsImg==',
       time: 4455,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT1010.g7hIzw==',
       time: 3552,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT2557.fyiFnQ==',
       time: 3390,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }
--------------- test report ---------------------
--------------- Apple-IpadAir2-1_PT1010 --------------------- : 1

peersList : 100% : 1118 ms, 99% : 1118 ms, 95 : 1118 ms, 90% : 1118 ms.

Result count 1, range 1118 ms to  1118 ms.

sendList : 100% : 4541 ms, 99% : 4541 ms, 95 : 4541 ms, 90% : 4541 ms.

Average data rate: 0.025 MB/s
Result count 3, range 3547 ms to  4541 ms.
sendList failed peers count : 1 [25 %]

- Peer ID : Apple-IpadAir2-1_PT1010.7Cf2mQ==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5-1_PT2557 --------------------- : 2

peersList : 100% : 1025 ms, 99% : 1025 ms, 95 : 1025 ms, 90% : 1025 ms.
Result count 1, range 1025 ms to  1025 ms.
sendList : 100% : 4007 ms, 99% : 4007 ms, 95 : 4007 ms, 90% : 4007 ms.

Average data rate: 0.027 MB/s
Result count 3, range 3431 ms to  4007 ms.
sendList failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone5s-1_PT6308.pQEQSw==, Tried : 5

sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1_PT9306 --------------------- : 3
peersList : 100% : 1055 ms, 99% : 1055 ms, 95 : 1055 ms, 90% : 1055 ms.

Result count 1, range 1055 ms to  1055 ms.
sendList : 100% : 3369 ms, 99% : 3369 ms, 95 : 3369 ms, 90% : 3369 ms.
Average data rate: 0.031 MB/s
Result count 3, range 3119 ms to  3369 ms.
sendList failed peers count : 1 [25 %]

- Peer ID : Apple-Iphone5s-1_PT6308.pQEQSw==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5s-1_PT6308 --------------------- : 4
peersList : 100% : 2330 ms, 99% : 2330 ms, 95 : 2330 ms, 90% : 2330 ms.
Result count 1, range 2330 ms to  2330 ms.

sendList : 100% : 4455 ms, 99% : 4455 ms, 95 : 4455 ms, 90% : 4455 ms.
Average data rate: 0.026 MB/s
Result count 3, range 3390 ms to  4455 ms.
sendList failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone5s-1_PT6308.pQEQSw==, Tried : 5

sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------
peersList : 100% : 2330 ms, 99% : 2330 ms, 95 : 2330 ms, 90% : 2330 ms.

sendList : 100% : 4541 ms, 99% : 4541 ms, 95 : 4455 ms, 90% : 4455 ms.
Average data rate: 0.027 MB/s

--------------- end of test report ---------------------

{ 'Apple-IpadAir2-1_PT1010': 
   { peersList: [ [Object] ],
     sendList: [ [Object], [Object], [Object] ],
     sendError: { failedPeer: [Object], notTriedList: [] } },
  'Apple-Iphone5-1_PT2557': 
   { peersList: [ [Object] ],
     sendList: [ [Object], [Object], [Object] ],
     sendError: { failedPeer: [Object], notTriedList: [] } },
  'Apple-Iphone6-1_PT9306': 
   { peersList: [ [Object] ],
     sendList: [ [Object], [Object], [Object] ],
     sendError: { failedPeer: [Object], notTriedList: [] } },
  'Apple-Iphone5s-1_PT6308': 
   { peersList: [ [Object] ],
     sendList: [ [Object], [Object], [Object] ],
     sendError: { failedPeer: [Object], notTriedList: [] } } }

New device presented: motorola-XT1039_PT3623 (android) perftest

23 android devices presented

Starting perf test run for platform: android
Using devices:

LGE-Nexus 5_PT5145
LGE-LG-D802_PT349
samsung-SM-A500FU_PT4039

samsung-SM-A300FU_PT6932

samsung-SM-A300FU_PT5619

motorola-XT1072_PT9222
LGE-Nexus 5_PT1299
LGE-LG-D722_PT6503
samsung-SM-G900F_PT5051

HTC-HTC One M8s_PT5468
HTC-HTC Desire 820_PT2765
samsung-SM-G900F_PT7800

HUAWEI-ALE-L21_PT6057
LGE-LG-H815_PT4197
motorola-Nexus 6_PT1658

samsung-SM-N9005_PT3106
HTC-HTC Desire 820_PT1757
LGE-LG-D855_PT3010
samsung-SM-G800H_PT1658

samsung-SM-N910C_PT6734
samsung-SM-A500FU_PT3932
samsung-SM-G800F_PT9986

motorola-XT1039_PT3623

Setting: 23

23

1

All test data retrieved for testFindPeers.js (android)
2015-12-15T04:07:51.127Z (85 sec) - android test ID testFindPeers.js done now

testFindPeers.js (android) results from: LGE-Nexus 5_PT5145

testFindPeers.js (android) results from: LGE-LG-D802_PT349

testFindPeers.js (android) results from: samsung-SM-A500FU_PT4039

testFindPeers.js (android) results from: samsung-SM-A300FU_PT6932

testFindPeers.js (android) results from: samsung-SM-A300FU_PT5619

testFindPeers.js (android) results from: motorola-XT1072_PT9222

testFindPeers.js (android) results from: LGE-Nexus 5_PT1299

testFindPeers.js (android) results from: LGE-LG-D722_PT6503

testFindPeers.js (android) results from: samsung-SM-G900F_PT5051

testFindPeers.js (android) results from: HTC-HTC One M8s_PT5468

testFindPeers.js (android) results from: HTC-HTC Desire 820_PT2765

testFindPeers.js (android) results from: samsung-SM-G900F_PT7800

testFindPeers.js (android) results from: HUAWEI-ALE-L21_PT6057

testFindPeers.js (android) results from: LGE-LG-H815_PT4197

testFindPeers.js (android) results from: motorola-Nexus 6_PT1658

testFindPeers.js (android) results from: samsung-SM-N9005_PT3106

testFindPeers.js (android) results from: HTC-HTC Desire 820_PT1757

testFindPeers.js (android) results from: LGE-LG-D855_PT3010

testFindPeers.js (android) results from: samsung-SM-G800H_PT1658
testFindPeers.js (android) results from: samsung-SM-N910C_PT6734
testFindPeers.js (android) results from: samsung-SM-A500FU_PT3932
testFindPeers.js (android) results from: samsung-SM-G800F_PT9986
22
Continuing to next test: testSendData.js
Setting: 22

22

21
21

20

20

19

19

18
18

17

17

16

16

15

15

14
14

13

13

12
12

11

11

10

10

9

9

8

8

7

7

6

6

5

5

4

4

3

3

2

2

1

All test data retrieved for testFindPeers.js (android)
2015-12-15T04:08:01.860Z (95 sec) - android test ID testFindPeers.js done now

testFindPeers.js (android) results from: LGE-Nexus 5_PT5145

testFindPeers.js (android) results from: LGE-LG-D802_PT349

testFindPeers.js (android) results from: samsung-SM-A500FU_PT4039

testFindPeers.js (android) results from: samsung-SM-A300FU_PT6932

testFindPeers.js (android) results from: samsung-SM-A300FU_PT5619

testFindPeers.js (android) results from: motorola-XT1072_PT9222

testFindPeers.js (android) results from: LGE-Nexus 5_PT1299

testFindPeers.js (android) results from: LGE-LG-D722_PT6503

testFindPeers.js (android) results from: samsung-SM-G900F_PT5051

testFindPeers.js (android) results from: HTC-HTC One M8s_PT5468

testFindPeers.js (android) results from: HTC-HTC Desire 820_PT2765

testFindPeers.js (android) results from: samsung-SM-G900F_PT7800

testFindPeers.js (android) results from: HUAWEI-ALE-L21_PT6057

testFindPeers.js (android) results from: LGE-LG-H815_PT4197

testFindPeers.js (android) results from: motorola-Nexus 6_PT1658

testFindPeers.js (android) results from: samsung-SM-N9005_PT3106

testFindPeers.js (android) results from: HTC-HTC Desire 820_PT1757

testFindPeers.js (android) results from: LGE-LG-D855_PT3010

testFindPeers.js (android) results from: samsung-SM-G800H_PT1658

testFindPeers.js (android) results from: samsung-SM-N910C_PT6734

testFindPeers.js (android) results from: samsung-SM-A500FU_PT3932

testFindPeers.js (android) results from: samsung-SM-G800F_PT9986

testFindPeers.js (android) results from: motorola-XT1039_PT3623

Continuing to next test: testSendData.js

Setting: 23

23

New device presented: samsung-SM-A500FU_PT3932 (android) perftest

24 android devices presented

New device presented: HTC-HTC One M8s_PT5468 (android) perftest

25 android devices presented

New device presented: LGE-LG-D855_PT3010 (android) perftest

26 android devices presented

New device presented: motorola-XT1072_PT9222 (android) perftest

27 android devices presented

New device presented: motorola-XT1072_PT9222 (android) perftest

28 android devices presented

New device presented: motorola-XT1072_PT9222 (android) perftest

29 android devices presented

New device presented: LGE-LG-D722_PT6503 (android) perftest

30 android devices presented

New device presented: HTC-HTC Desire 820_PT2765 (android) perftest

31 android devices presented

New device presented: LGE-LG-D855_PT3010 (android) perftest

32 android devices presented

New device presented: motorola-XT1072_PT9222 (android) perftest

33 android devices presented

New device presented: HTC-HTC Desire 820_PT1757 (android) perftest

34 android devices presented

New device presented: LGE-LG-H815_PT4197 (android) perftest

35 android devices presented

New device presented: LGE-LG-D722_PT6503 (android) perftest

36 android devices presented

New device presented: samsung-SM-G800F_PT9986 (android) perftest

37 android devices presented

New device presented: HTC-HTC Desire 820_PT1757 (android) perftest

38 android devices presented

New device presented: HTC-HTC Desire 820_PT2765 (android) perftest

39 android devices presented

New device presented: LGE-LG-D722_PT6503 (android) perftest

40 android devices presented

New device presented: HTC-HTC Desire 820_PT1757 (android) perftest

41 android devices presented

22

New device presented: HTC-HTC Desire 820_PT1757 (android) perftest

42 android devices presented

New device presented: HTC-HTC Desire 820_PT2765 (android) perftest

43 android devices presented

New device presented: samsung-SM-G800F_PT9986 (android) perftest

44 android devices presented

21

20

New device presented: motorola-XT1072_PT9222 (android) perftest

45 android devices presented

New device presented: motorola-Nexus 6_PT1658 (android) perftest

46 android devices presented

New device presented: motorola-XT1039_PT3623 (android) perftest

47 android devices presented

server timeout for test: testFindPeers.js (android)

New device presented: LGE-LG-D722_PT6503 (android) perftest

48 android devices presented

New device presented: samsung-SM-G800H_PT1658 (android) perftest

49 android devices presented

server timeout for test: testFindPeers.js (android)

server timeout for test: testFindPeers.js (android)

server timeout for test: testFindPeers.js (android)

server timeout for test: testFindPeers.js (android)

server timeout for test: testFindPeers.js (android)

server timeout for test: testFindPeers.js (android)
server timeout for test: testFindPeers.js (android)

server timeout for test: testFindPeers.js (android)

server timeout for test: testFindPeers.js (android)
server timeout for test: testFindPeers.js (android)

server timeout for test: testFindPeers.js (android)

server timeout for test: testFindPeers.js (android)
server timeout for test: testFindPeers.js (android)

server timeout for test: testFindPeers.js (android)

server timeout for test: testFindPeers.js (android)

server timeout for test: testFindPeers.js (android)
server timeout for test: testFindPeers.js (android)

server timeout for test: testFindPeers.js (android)

server timeout for test: testFindPeers.js (android)
server timeout for test: testFindPeers.js (android)

server timeout for test: testSendData.js (android)

server timeout for test: testSendData.js (android)
server timeout for test: testSendData.js (android)

server timeout for test: testSendData.js (android)
server timeout for test: testSendData.js (android)

server timeout for test: testSendData.js (android)

server timeout for test: testSendData.js (android)
server timeout for test: testSendData.js (android)

server timeout for test: testSendData.js (android)

server timeout for test: testSendData.js (android)
server timeout for test: testSendData.js (android)

server timeout for test: testSendData.js (android)

server timeout for test: testSendData.js (android)

server timeout for test: testSendData.js (android)
server timeout for test: testSendData.js (android)

server timeout for test: testSendData.js (android)

server timeout for test: testSendData.js (android)
server timeout for test: testSendData.js (android)

server timeout for test: testSendData.js (android)

server timeout for test: testSendData.js (android)

New device presented: motorola-Nexus 6_PT1658 (android) perftest

50 android devices presented


 
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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/50650278ee43ca0_Enable_UnitTest_tobybrad/thali01_LGE-LG-H815.md)

[HUAWEI-ALE-L21](https://github.com/ThaliTester/TestResults/blob/50650278ee43ca0_Enable_UnitTest_tobybrad/thali01_HUAWEI-ALE-L21.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/50650278ee43ca0_Enable_UnitTest_tobybrad/thali01_samsung-SM-A500FU.md)

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
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/50650278ee43ca0_Enable_UnitTest_tobybrad/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/50650278ee43ca0_Enable_UnitTest_tobybrad/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/50650278ee43ca0_Enable_UnitTest_tobybrad/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/50650278ee43ca0_Enable_UnitTest_tobybrad/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/50650278ee43ca0_Enable_UnitTest_tobybrad/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/50650278ee43ca0_Enable_UnitTest_tobybrad/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/50650278ee43ca0_Enable_UnitTest_tobybrad/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/50650278ee43ca0_Enable_UnitTest_tobybrad/thali04_samsung-SM-G900F.md)

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
[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/50650278ee43ca0_Enable_UnitTest_tobybrad/thali05_samsung-SM-N9005.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/50650278ee43ca0_Enable_UnitTest_tobybrad/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/50650278ee43ca0_Enable_UnitTest_tobybrad/thali05_samsung-SM-G800H.md)

####Node name: thali06
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:null 
child process exited with code null on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:0 
child process exited with code 0 on device FA55PYS00566 
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:null 
child process exited with code null on device 022678fb504e29b0 
```


Couldn't parse the device logs for thali06
````SyntaxError: Unexpected end of input```
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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/50650278ee43ca0_Enable_UnitTest_tobybrad/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/50650278ee43ca0_Enable_UnitTest_tobybrad/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/50650278ee43ca0_Enable_UnitTest_tobybrad/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/50650278ee43ca0_Enable_UnitTest_tobybrad/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
Error! Unexpected exit on device 0c6a0f3c0bdb4e77 app:com.test.thalitest code:0 
child process exited with code 0 on device 0c6a0f3c0bdb4e77 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device CC51WYC03425 app:com.test.thalitest code:null 
child process exited with code null on device CC51WYC03425 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/50650278ee43ca0_Enable_UnitTest_tobybrad/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/50650278ee43ca0_Enable_UnitTest_tobybrad/thali09_LGE-Nexus 5.md)




###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/50650278ee43ca0_Enable_UnitTest_tobybrad/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/50650278ee43ca0_Enable_UnitTest_tobybrad/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/50650278ee43ca0_Enable_UnitTest_tobybrad/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/50650278ee43ca0_Enable_UnitTest_tobybrad/iOS_Iphone5-1.md)



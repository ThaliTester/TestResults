#### Test 506502782ddd83f Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":23}}
listening on *:3000

New device presented: samsung-SM-A500FU_PT8781 (android) perftest

1 android devices presented

New device presented: LGE-Nexus 5_PT8470 (android) perftest

2 android devices presented

New device presented: LGE-LG-D722_PT8286 (android) perftest

3 android devices presented

New device presented: LGE-LG-H815_PT6724 (android) perftest

4 android devices presented

New device presented: motorola-XT1072_PT3132 (android) perftest

5 android devices presented

New device presented: LGE-LG-D802_PT6939 (android) perftest

6 android devices presented

New device presented: HUAWEI-ALE-L21_PT9 (android) perftest

7 android devices presented

New device presented: samsung-SM-G900F_PT3896 (android) perftest

8 android devices presented

New device presented: Apple-Iphone5s-1_PT4162 (ios) perftest

1 ios devices presented

New device presented: HTC-HTC Desire 820_PT7612 (android) perftest

9 android devices presented

New device presented: Apple-Iphone5-1_PT356 (ios) perftest

2 ios devices presented

New device presented: samsung-SM-G900F_PT6716 (android) perftest

10 android devices presented

New device presented: samsung-SM-A300FU_PT7729 (android) perftest

11 android devices presented

New device presented: motorola-Nexus 6_PT3219 (android) perftest

12 android devices presented

New device presented: samsung-SM-A300FU_PT5248 (android) perftest

13 android devices presented

New device presented: samsung-SM-G800H_PT2340 (android) perftest

14 android devices presented

New device presented: samsung-SM-A500FU_PT5226 (android) perftest

15 android devices presented

New device presented: Apple-IpadAir2-1_PT2678 (ios) perftest

3 ios devices presented

New device presented: samsung-SM-N9005_PT8854 (android) perftest

16 android devices presented

New device presented: HTC-HTC Desire 820_PT8943 (android) perftest

17 android devices presented

New device presented: samsung-SM-N910C_PT3307 (android) perftest

18 android devices presented

New device presented: LGE-Nexus 5_PT4753 (android) perftest

19 android devices presented

New device presented: Apple-Iphone6-1_PT7824 (ios) perftest

4 ios devices presented

Starting perf test run for platform: ios

Using devices:
Apple-Iphone5s-1_PT4162

Apple-Iphone5-1_PT356
Apple-IpadAir2-1_PT2678
Apple-Iphone6-1_PT7824

Setting: 4

New device presented: LGE-LG-D855_PT752 (android) perftest

20 android devices presented

4

3

2

New device presented: samsung-SM-G800F_PT4958 (android) perftest

21 android devices presented

1

All test data retrieved for testFindPeers.js (ios)

2015-12-15T04:46:58.811Z (9 sec) - ios test ID testFindPeers.js done now

testFindPeers.js (ios) results from: Apple-Iphone5s-1_PT4162

testFindPeers.js (ios) results from: Apple-Iphone5-1_PT356

testFindPeers.js (ios) results from: Apple-IpadAir2-1_PT2678

testFindPeers.js (ios) results from: Apple-Iphone6-1_PT7824

Continuing to next test: testSendData.js

Setting: 4

New device presented: motorola-XT1039_PT2605 (android) perftest

22 android devices presented

Start timeout elapsed for platform: android

Starting perf test run for platform: android
Using devices:
samsung-SM-A500FU_PT8781
LGE-Nexus 5_PT8470

LGE-LG-D722_PT8286
LGE-LG-H815_PT6724
motorola-XT1072_PT3132
LGE-LG-D802_PT6939

HUAWEI-ALE-L21_PT9
samsung-SM-G900F_PT3896
HTC-HTC Desire 820_PT7612
samsung-SM-G900F_PT6716

samsung-SM-A300FU_PT7729

motorola-Nexus 6_PT3219
samsung-SM-A300FU_PT5248
samsung-SM-G800H_PT2340
samsung-SM-A500FU_PT5226
samsung-SM-N9005_PT8854
HTC-HTC Desire 820_PT8943

samsung-SM-N910C_PT3307
LGE-Nexus 5_PT4753
LGE-LG-D855_PT752
samsung-SM-G800F_PT4958

motorola-XT1039_PT2605
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
2015-12-15T04:48:32.690Z (102 sec) - ios test ID testSendData.js done now

testSendData.js (ios) results from: Apple-Iphone5s-1_PT4162

testSendData.js (ios) results from: Apple-Iphone5-1_PT356

testSendData.js (ios) results from: Apple-IpadAir2-1_PT2678

testSendData.js (ios) results from: Apple-Iphone6-1_PT7824

ALL DONE !!!

{ 'name:': 'Apple-Iphone5s-1_PT4162',
  time: 603,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1_PT356.zzR6Ww==',
       peerAvailable: true,
       time: 600 } ] }

{ 'name:': 'Apple-Iphone5-1_PT356',
  time: 1005,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1_PT2678.RP+Etw==',
       peerAvailable: true,
       time: 1003 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT2678',
  time: 1117,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1_PT356.zzR6Ww==',
       peerAvailable: true,
       time: 1115 } ] }
{ 'name:': 'Apple-Iphone6-1_PT7824',
  time: 1190,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1_PT356.zzR6Ww==',
       peerAvailable: true,
       time: 1188 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT4162',
  time: 92814,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT2678.RP+Etw==',
       time: 42149,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1_PT356.aa89HA==',
       time: 43577,
       result: 'OK',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT2678.ad0lIQ==',
       time: 3659,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT7824.jNC0Kw==',
       time: 3201,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1_PT356',
  time: 54096,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT7824.Q97KpQ==',
       time: 41348,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT2678.ad0lIQ==',
       time: 3833,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT7824.jNC0Kw==',
       time: 4615,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT4162.hYB3TQ==',
       time: 3761,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT2678',
  time: 52640,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT2678.RP+Etw==',
       time: 42089,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1_PT4162.hYB3TQ==',
       time: 3680,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT7824.jNC0Kw==',
       time: 3517,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT356.aa89HA==',
       time: 3166,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1_PT7824',
  time: 93237,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1_PT356.zzR6Ww==',
       time: 41767,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1_PT356.aa89HA==',
       time: 43570,
       result: 'OK',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT4162.hYB3TQ==',
       time: 3132,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT2678.ad0lIQ==',
       time: 4500,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

--------------- test report ---------------------
--------------- Apple-Iphone5s-1_PT4162 --------------------- : 1

peersList : 100% : 600 ms, 99% : 600 ms, 95 : 600 ms, 90% : 600 ms.

Result count 1, range 600 ms to  600 ms.
sendList : 100% : 43577 ms, 99% : 43577 ms, 95 : 43577 ms, 90% : 43577 ms.
Average data rate: 0.006 MB/s
Result count 3, range 3201 ms to  43577 ms.
sendList failed peers count : 1 [25 %]
- Peer ID : Apple-IpadAir2-1_PT2678.RP+Etw==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5-1_PT356 --------------------- : 2
peersList : 100% : 1003 ms, 99% : 1003 ms, 95 : 1003 ms, 90% : 1003 ms.
Result count 1, range 1003 ms to  1003 ms.
sendList : 100% : 4615 ms, 99% : 4615 ms, 95 : 4615 ms, 90% : 4615 ms.
Average data rate: 0.025 MB/s
Result count 3, range 3761 ms to  4615 ms.

sendList failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone6-1_PT7824.Q97KpQ==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-IpadAir2-1_PT2678 --------------------- : 3

peersList : 100% : 1115 ms, 99% : 1115 ms, 95 : 1115 ms, 90% : 1115 ms.
Result count 1, range 1115 ms to  1115 ms.
sendList : 100% : 3680 ms, 99% : 3680 ms, 95 : 3680 ms, 90% : 3680 ms.
Average data rate: 0.029 MB/s

Result count 3, range 3166 ms to  3680 ms.
sendList failed peers count : 1 [25 %]
- Peer ID : Apple-IpadAir2-1_PT2678.RP+Etw==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone6-1_PT7824 --------------------- : 4
peersList : 100% : 1188 ms, 99% : 1188 ms, 95 : 1188 ms, 90% : 1188 ms.
Result count 1, range 1188 ms to  1188 ms.
sendList : 100% : 43570 ms, 99% : 43570 ms, 95 : 43570 ms, 90% : 43570 ms.
Average data rate: 0.006 MB/s
Result count 3, range 3132 ms to  43570 ms.
sendList failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone5-1_PT356.zzR6Ww==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------
peersList : 100% : 1188 ms, 99% : 1188 ms, 95 : 1188 ms, 90% : 1188 ms.
sendList : 100% : 43577 ms, 99% : 43577 ms, 95 : 43570 ms, 90% : 43570 ms.

Average data rate: 0.01 MB/s
--------------- end of test report ---------------------

{ 'Apple-Iphone5s-1_PT4162': 
   { peersList: [ [Object] ],
     sendList: [ [Object], [Object], [Object] ],
     sendError: { failedPeer: [Object], notTriedList: [] } },
  'Apple-Iphone5-1_PT356': 
   { peersList: [ [Object] ],
     sendList: [ [Object], [Object], [Object] ],
     sendError: { failedPeer: [Object], notTriedList: [] } },
  'Apple-IpadAir2-1_PT2678': 
   { peersList: [ [Object] ],
     sendList: [ [Object], [Object], [Object] ],
     sendError: { failedPeer: [Object], notTriedList: [] } },
  'Apple-Iphone6-1_PT7824': 
   { peersList: [ [Object] ],
     sendList: [ [Object], [Object], [Object] ],
     sendError: { failedPeer: [Object], notTriedList: [] } } }

New device presented: motorola-XT1072_PT3132 (android) perftest

23 android devices presented
Starting perf test run for platform: android
Using devices:

samsung-SM-A500FU_PT8781
LGE-Nexus 5_PT8470
LGE-LG-D722_PT8286
LGE-LG-H815_PT6724

motorola-XT1072_PT3132
LGE-LG-D802_PT6939
HUAWEI-ALE-L21_PT9
samsung-SM-G900F_PT3896
HTC-HTC Desire 820_PT7612

samsung-SM-G900F_PT6716
samsung-SM-A300FU_PT7729
motorola-Nexus 6_PT3219
samsung-SM-A300FU_PT5248

samsung-SM-G800H_PT2340
samsung-SM-A500FU_PT5226
samsung-SM-N9005_PT8854
HTC-HTC Desire 820_PT8943

samsung-SM-N910C_PT3307
LGE-Nexus 5_PT4753
LGE-LG-D855_PT752
samsung-SM-G800F_PT4958
motorola-XT1039_PT2605

motorola-XT1072_PT3132
Setting: 23

23

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

1

All test data retrieved for testFindPeers.js (android)
2015-12-15T04:55:34.419Z (524 sec) - android test ID testFindPeers.js done now
testFindPeers.js (android) results from: samsung-SM-A500FU_PT8781

testFindPeers.js (android) results from: LGE-Nexus 5_PT8470

testFindPeers.js (android) results from: LGE-LG-D722_PT8286

testFindPeers.js (android) results from: LGE-LG-H815_PT6724

testFindPeers.js (android) results from: motorola-XT1072_PT3132

testFindPeers.js (android) results from: LGE-LG-D802_PT6939

testFindPeers.js (android) results from: HUAWEI-ALE-L21_PT9

testFindPeers.js (android) results from: samsung-SM-G900F_PT3896

testFindPeers.js (android) results from: HTC-HTC Desire 820_PT7612

testFindPeers.js (android) results from: samsung-SM-G900F_PT6716

testFindPeers.js (android) results from: samsung-SM-A300FU_PT7729

testFindPeers.js (android) results from: motorola-Nexus 6_PT3219

testFindPeers.js (android) results from: samsung-SM-A300FU_PT5248

testFindPeers.js (android) results from: samsung-SM-G800H_PT2340

testFindPeers.js (android) results from: samsung-SM-A500FU_PT5226

testFindPeers.js (android) results from: samsung-SM-N9005_PT8854

testFindPeers.js (android) results from: HTC-HTC Desire 820_PT8943

testFindPeers.js (android) results from: samsung-SM-N910C_PT3307

testFindPeers.js (android) results from: LGE-Nexus 5_PT4753

testFindPeers.js (android) results from: LGE-LG-D855_PT752

testFindPeers.js (android) results from: samsung-SM-G800F_PT4958

testFindPeers.js (android) results from: motorola-XT1039_PT2605
9
Continuing to next test: testSendData.js
Setting: 22

22

8

21

7

20

6

19

5

18

4

17

3

16

2

15

New device presented: LGE-LG-D855_PT752 (android) perftest

24 android devices presented

New device presented: LGE-LG-D722_PT8286 (android) perftest

25 android devices presented

New device presented: HTC-HTC Desire 820_PT7612 (android) perftest

26 android devices presented

New device presented: LGE-Nexus 5_PT4753 (android) perftest

27 android devices presented

New device presented: LGE-LG-D802_PT6939 (android) perftest

28 android devices presented

New device presented: samsung-SM-G800H_PT2340 (android) perftest

29 android devices presented

New device presented: HTC-HTC Desire 820_PT7612 (android) perftest

30 android devices presented

New device presented: LGE-LG-D722_PT8286 (android) perftest

31 android devices presented

New device presented: LGE-Nexus 5_PT4753 (android) perftest

32 android devices presented

New device presented: LGE-LG-D802_PT6939 (android) perftest

33 android devices presented

New device presented: LGE-LG-D722_PT8286 (android) perftest

34 android devices presented

New device presented: LGE-Nexus 5_PT4753 (android) perftest

35 android devices presented

New device presented: samsung-SM-A500FU_PT8781 (android) perftest

36 android devices presented

New device presented: HTC-HTC Desire 820_PT7612 (android) perftest

37 android devices presented

New device presented: LGE-LG-D855_PT752 (android) perftest

38 android devices presented

New device presented: HTC-HTC Desire 820_PT8943 (android) perftest

39 android devices presented

New device presented: LGE-LG-D855_PT752 (android) perftest

40 android devices presented

server timeout for test: testFindPeers.js (android)

New device presented: samsung-SM-A300FU_PT7729 (android) perftest

41 android devices presented

New device presented: LGE-Nexus 5_PT4753 (android) perftest

42 android devices presented

New device presented: motorola-XT1072_PT3132 (android) perftest

43 android devices presented

New device presented: samsung-SM-G800H_PT2340 (android) perftest

44 android devices presented

New device presented: LGE-LG-D722_PT8286 (android) perftest

45 android devices presented

New device presented: motorola-XT1072_PT3132 (android) perftest

46 android devices presented

14

13

New device presented: LGE-Nexus 5_PT4753 (android) perftest

47 android devices presented

New device presented: HTC-HTC Desire 820_PT7612 (android) perftest

48 android devices presented

New device presented: LGE-LG-D855_PT752 (android) perftest

49 android devices presented

New device presented: LGE-LG-D802_PT6939 (android) perftest

50 android devices presented

New device presented: motorola-Nexus 6_PT3219 (android) perftest

51 android devices presented

New device presented: samsung-SM-G800F_PT4958 (android) perftest

52 android devices presented

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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/506502782ddd83f_Enable_UnitTest_tobybrad/thali01_LGE-LG-H815.md)

[HUAWEI-ALE-L21](https://github.com/ThaliTester/TestResults/blob/506502782ddd83f_Enable_UnitTest_tobybrad/thali01_HUAWEI-ALE-L21.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/506502782ddd83f_Enable_UnitTest_tobybrad/thali01_samsung-SM-A500FU.md)

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
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/506502782ddd83f_Enable_UnitTest_tobybrad/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/506502782ddd83f_Enable_UnitTest_tobybrad/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/506502782ddd83f_Enable_UnitTest_tobybrad/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/506502782ddd83f_Enable_UnitTest_tobybrad/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/506502782ddd83f_Enable_UnitTest_tobybrad/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/506502782ddd83f_Enable_UnitTest_tobybrad/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/506502782ddd83f_Enable_UnitTest_tobybrad/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/506502782ddd83f_Enable_UnitTest_tobybrad/thali04_samsung-SM-G900F.md)

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
[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/506502782ddd83f_Enable_UnitTest_tobybrad/thali05_samsung-SM-N9005.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/506502782ddd83f_Enable_UnitTest_tobybrad/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/506502782ddd83f_Enable_UnitTest_tobybrad/thali05_samsung-SM-G800H.md)

####Node name: thali06
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:0 
child process exited with code 0 on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:0 
child process exited with code 0 on device FA55PYS00566 
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:null 
child process exited with code null on device 022678fb504e29b0 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/506502782ddd83f_Enable_UnitTest_tobybrad/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/506502782ddd83f_Enable_UnitTest_tobybrad/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/506502782ddd83f_Enable_UnitTest_tobybrad/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/506502782ddd83f_Enable_UnitTest_tobybrad/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/506502782ddd83f_Enable_UnitTest_tobybrad/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/506502782ddd83f_Enable_UnitTest_tobybrad/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/506502782ddd83f_Enable_UnitTest_tobybrad/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/506502782ddd83f_Enable_UnitTest_tobybrad/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/506502782ddd83f_Enable_UnitTest_tobybrad/thali09_LGE-Nexus 5.md)




###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/506502782ddd83f_Enable_UnitTest_tobybrad/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/506502782ddd83f_Enable_UnitTest_tobybrad/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/506502782ddd83f_Enable_UnitTest_tobybrad/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/506502782ddd83f_Enable_UnitTest_tobybrad/iOS_Iphone5-1.md)



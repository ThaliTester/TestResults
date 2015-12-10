#### Test 50650278b86327b Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":23}}
listening on *:3000

New perf test device: HTC-HTC One M8s_PT8387

New perf test device: samsung-SM-N910C_PT9922

Starting perf test run for platform: android

New perf test device: motorola-XT1072_PT3150

New perf test device: LGE-LG-D722_PT557

New perf test device: LGE-Nexus 5_PT9357

New perf test device: HTC-HTC Desire 820_PT6571

New perf test device: HUAWEI-ALE-L21_PT5923

New perf test device: HTC-HTC Desire 820_PT6928

New perf test device: samsung-SM-N9005_PT7306

New perf test device: samsung-SM-G900F_PT2910

New perf test device: Apple-Iphone5-1_PT9189

New perf test device: samsung-SM-G900F_PT8928

New perf test device: LGE-LG-H815_PT2945

New perf test device: samsung-SM-G800H_PT7703

New perf test device: Apple-Iphone6-1_PT4262

Starting perf test run for platform: ios

New perf test device: samsung-SM-A300FU_PT498

New perf test device: Apple-IpadAir2-1_PT9933

New perf test device: motorola-Nexus 6_PT5137

New perf test device: samsung-SM-A300FU_PT2551

New perf test device: LGE-Nexus 5_PT7507

New perf test device: samsung-SM-A500FU_PT4743

New perf test device: LGE-LG-D802_PT8061

New perf test device: samsung-SM-A500FU_PT803

New perf test device: Apple-Iphone5s-1_PT6159

New perf test device: motorola-XT1039_PT1224

New perf test device: samsung-SM-G800F_PT6259

New perf test device: LGE-LG-D855_PT6699

2015-12-10T14:14:45.406Z (15 sec) - ios test ID testFindPeers.js done now

Continuing to next test: testSendData.js

2015-12-10T14:15:53.272Z (83 sec) - ios test ID testSendData.js done now

ALL DONE !!!

{ 'name:': 'Apple-Iphone5-1_PT9189',
  time: 1589,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT4262.KAmLlg==',
       peerAvailable: true,
       time: 1588 } ] }

{ 'name:': 'Apple-Iphone6-1_PT4262',
  time: 11991,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1_PT9189.I0Ha/w==',
       peerAvailable: true,
       time: 11989 } ] }

{ 'name:': 'Apple-Iphone5-1_PT9189',
  time: 67061,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1_PT9189.I0Ha/w==',
       time: 41086,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT4262.fxR5Pw==',
       time: 25902,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1_PT4262',
  time: 67253,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4262.KAmLlg==',
       time: 40593,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1_PT9189.dQfCuw==',
       time: 26100,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

--------------- test report ---------------------
--------------- Apple-Iphone5-1_PT9189 --------------------- : 1

peersList : 100% : 1588 ms, 99% : 1588 ms, 95 : 1588 ms, 90% : 1588 ms.

Result count 1, range 1588 ms to  1588 ms.

sendList : 100% : 25902 ms, 99% : 25902 ms, 95 : 25902 ms, 90% : 25902 ms.

Average data rate: 0.004 MB/s

Result count 1, range 25902 ms to  25902 ms.

sendList failed peers count : 1 [50 %]

- Peer ID : Apple-Iphone5-1_PT9189.I0Ha/w==, Tried : 5

sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1_PT4262 --------------------- : 2

peersList : 100% : 11989 ms, 99% : 11989 ms, 95 : 11989 ms, 90% : 11989 ms.
Result count 1, range 11989 ms to  11989 ms.
sendList : 100% : 26100 ms, 99% : 26100 ms, 95 : 26100 ms, 90% : 26100 ms.
Average data rate: 0.004 MB/s
Result count 1, range 26100 ms to  26100 ms.

sendList failed peers count : 1 [50 %]
- Peer ID : Apple-Iphone6-1_PT4262.KAmLlg==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------

peersList : 100% : 11989 ms, 99% : 11989 ms, 95 : 11989 ms, 90% : 11989 ms.

sendList : 100% : 26100 ms, 99% : 26100 ms, 95 : 26100 ms, 90% : 26100 ms.
Average data rate: 0.004 MB/s
--------------- end of test report ---------------------

{ 'Apple-Iphone5-1_PT9189': 
   { peersList: [ [Object] ],
     sendList: [ [Object] ],
     sendError: { failedPeer: [Object], notTriedList: [] } },
  'Apple-Iphone6-1_PT4262': 
   { peersList: [ [Object] ],
     sendList: [ [Object] ],
     sendError: { failedPeer: [Object], notTriedList: [] } } }

2015-12-10T14:18:14.212Z (224 sec) - android test ID testFindPeers.js done now

Continuing to next test: testSendData.js

server timeout for test: testFindPeers.js

server timeout for test: testFindPeers.js

server timeout for test: testSendData.js

2015-12-10T14:34:54.417Z (1224 sec) - android test ID testSendData.js done now

ALL DONE !!!

{ 'name:': 'HTC-HTC One M8s_PT8387',
  time: 199294,
  result: 'OK',
  peersList: 
   [ { peerName: 'samsung-SM-N910C_PT9922',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 199291 } ] }

{ 'name:': 'samsung-SM-N910C_PT9922',
  time: 223451,
  result: 'OK',
  peersList: 
   [ { peerName: 'HTC-HTC One M8s_PT8387',
       peerIdentifier: '90:E7:C4:F6:69:77',
       peerAvailable: true,
       time: 223449 } ] }

{ 'name:': 'HTC-HTC One M8s_PT8387',
  time: 976460,
  result: '',
  sendList: 
   [ { name: 'E0:DB:10:14:E2:C0',
       time: 8612,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'samsung-SM-N910C_PT9922',
  time: 1000113,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '90:E7:C4:F6:69:77',
       time: 9617,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

--------------- test report ---------------------
--------------- HTC-HTC One M8s_PT8387 --------------------- : 1
peersList : 100% : 199291 ms, 99% : 199291 ms, 95 : 199291 ms, 90% : 199291 ms.
Result count 1, range 199291 ms to  199291 ms.
sendList : 100% : 8612 ms, 99% : 8612 ms, 95 : 8612 ms, 90% : 8612 ms.
Average data rate: 0.012 MB/s

Result count 1, range 8612 ms to  8612 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-N910C_PT9922 --------------------- : 2
peersList : 100% : 223449 ms, 99% : 223449 ms, 95 : 223449 ms, 90% : 223449 ms.
Result count 1, range 223449 ms to  223449 ms.

sendList : 100% : 9617 ms, 99% : 9617 ms, 95 : 9617 ms, 90% : 9617 ms.
Average data rate: 0.01 MB/s
Result count 1, range 9617 ms to  9617 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- Combined ---------------------
peersList : 100% : 223449 ms, 99% : 223449 ms, 95 : 223449 ms, 90% : 223449 ms.
sendList : 100% : 9617 ms, 99% : 9617 ms, 95 : 9617 ms, 90% : 9617 ms.

Average data rate: 0.011 MB/s
--------------- end of test report ---------------------

{ 'HTC-HTC One M8s_PT8387': 
   { peersList: [ [Object] ],
     sendList: [ [Object] ],
     sendError: { failedPeer: [], notTriedList: [] } },
  'samsung-SM-N910C_PT9922': 
   { peersList: [ [Object] ],
     sendList: [ [Object] ],
     sendError: { failedPeer: [], notTriedList: [] } } }

New perf test device: HTC-HTC One M8s_PT8387

server timeout for test: testSendData.js
server timeout for test: testSendData.js


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/50650278b86327b_Enable_UnitTest_tobybrad/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/50650278b86327b_Enable_UnitTest_tobybrad/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/50650278b86327b_Enable_UnitTest_tobybrad/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/50650278b86327b_Enable_UnitTest_tobybrad/iOS_Iphone5-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/50650278b86327b_Enable_UnitTest_tobybrad/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/50650278b86327b_Enable_UnitTest_tobybrad/thali01_LGE-LG-H815.md)

[HUAWEI-ALE-L21](https://github.com/ThaliTester/TestResults/blob/50650278b86327b_Enable_UnitTest_tobybrad/thali01_HUAWEI-ALE-L21.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/50650278b86327b_Enable_UnitTest_tobybrad/thali01_samsung-SM-A500FU.md)

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
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/50650278b86327b_Enable_UnitTest_tobybrad/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/50650278b86327b_Enable_UnitTest_tobybrad/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/50650278b86327b_Enable_UnitTest_tobybrad/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/50650278b86327b_Enable_UnitTest_tobybrad/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/50650278b86327b_Enable_UnitTest_tobybrad/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Error! Unexpected exit on device 0be0c6c6 app:com.test.thalitest code:null 
child process exited with code null on device 0be0c6c6 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/50650278b86327b_Enable_UnitTest_tobybrad/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/50650278b86327b_Enable_UnitTest_tobybrad/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/50650278b86327b_Enable_UnitTest_tobybrad/thali04_samsung-SM-G900F.md)

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
[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/50650278b86327b_Enable_UnitTest_tobybrad/thali05_samsung-SM-N9005.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/50650278b86327b_Enable_UnitTest_tobybrad/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/50650278b86327b_Enable_UnitTest_tobybrad/thali05_samsung-SM-G800H.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/50650278b86327b_Enable_UnitTest_tobybrad/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/50650278b86327b_Enable_UnitTest_tobybrad/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/50650278b86327b_Enable_UnitTest_tobybrad/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device c5afcdcb app:com.test.thalitest code:0 
child process exited with code 0 on device c5afcdcb 
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:null 
child process exited with code null on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/50650278b86327b_Enable_UnitTest_tobybrad/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/50650278b86327b_Enable_UnitTest_tobybrad/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/50650278b86327b_Enable_UnitTest_tobybrad/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/50650278b86327b_Enable_UnitTest_tobybrad/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/50650278b86327b_Enable_UnitTest_tobybrad/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/50650278b86327b_Enable_UnitTest_tobybrad/thali09_LGE-Nexus 5.md)





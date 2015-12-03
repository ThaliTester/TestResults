#### Test 5065027835b6ad9 Logs

Status: 
```

server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4}}
listening on *:3000

New perf test device..

New perf test device..

New perf test device..

New perf test device..

starting:testFindPeers.js

{ servertimeout: 1200000,
  timeout: 1000000,
  rounds: 1,
  dataTimeout: 10000,
  dataAmount: 100000,
  conReTryTimeout: 5000,
  conReTryCount: 5 }

starting:testFindPeers.js

{ servertimeout: 1200000,
  timeout: 1000000,
  rounds: 1,
  dataTimeout: 10000,
  dataAmount: 100000,
  conReTryTimeout: 5000,
  conReTryCount: 5,
  peerCount: 4 }

starting:testFindPeers.js

{ servertimeout: 1200000,
  timeout: 1000000,
  rounds: 1,
  dataTimeout: 10000,
  dataAmount: 100000,
  conReTryTimeout: 5000,
  conReTryCount: 5,
  peerCount: 4 }

starting:testFindPeers.js

{ servertimeout: 1200000,
  timeout: 1000000,
  rounds: 1,
  dataTimeout: 10000,
  dataAmount: 100000,
  conReTryTimeout: 5000,
  conReTryCount: 5,
  peerCount: 4 }

2015-12-03T11:04:05.296Z (239 sec) - ios test ID testFindPeers.js done now

Continuing to next test: testSendData.js

starting:testSendData.js

{ servertimeout: 1200000,
  timeout: 1000000,
  rounds: 1,
  dataTimeout: 10000,
  dataAmount: 100000,
  conReTryTimeout: 5000,
  conReTryCount: 5 }

starting:testSendData.js

{ servertimeout: 1200000,
  timeout: 1000000,
  rounds: 1,
  dataTimeout: 10000,
  dataAmount: 100000,
  conReTryTimeout: 5000,
  conReTryCount: 5,
  peerCount: 4 }

starting:testSendData.js

{ servertimeout: 1200000,
  timeout: 1000000,
  rounds: 1,
  dataTimeout: 10000,
  dataAmount: 100000,
  conReTryTimeout: 5000,
  conReTryCount: 5,
  peerCount: 4 }

starting:testSendData.js

{ servertimeout: 1200000,
  timeout: 1000000,
  rounds: 1,
  dataTimeout: 10000,
  dataAmount: 100000,
  conReTryTimeout: 5000,
  conReTryCount: 5,
  peerCount: 4 }

2015-12-03T11:11:43.829Z (698 sec) - ios test ID testSendData.js done now

ALL DONE !!!

{ 'name:': 'Apple-IpadAir2-1_PT7777',
  time: 3675,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1_PT2098.2PCWSw==',
       peerAvailable: true,
       time: 3674 } ] }

{ 'name:': 'Apple-Iphone6-1_PT8234',
  time: 256,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5s-1_PT7153.3coM6g==',
       peerAvailable: true,
       time: 255 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT7153',
  time: 490,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1_PT2098.2PCWSw==',
       peerAvailable: true,
       time: 488 } ] }

{ 'name:': 'Apple-Iphone5-1_PT2098',
  time: 1226,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1_PT7777.VxBn0g==',
       peerAvailable: true,
       time: 1225 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT7777',
  time: 55866,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT7777.VxBn0g==',
       time: 40720,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1_PT2098.P4cq9w==',
       time: 3875,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT7153.jAFxCw==',
       time: 5245,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT8234.+Hw2qA==',
       time: 5456,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1_PT8234',
  time: 354382,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT7777.VxBn0g==',
       time: 42868,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1_PT7153.3coM6g==',
       time: 205110,
       result: 'Peer disconnected',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1_PT7153.jAFxCw==',
       time: 103111,
       result: 'DATA-TIMEOUT',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 90000 },
     { name: 'Apple-IpadAir2-1_PT7777.O0xngQ==',
       time: 3245,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT7153',
  time: 356448,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT8234.n7uNOA==',
       time: 42343,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1_PT7153.3coM6g==',
       time: 205176,
       result: 'Peer disconnected',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT8234.+Hw2qA==',
       time: 3207,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT7777.O0xngQ==',
       time: 105610,
       result: 'DATA-TIMEOUT',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 90000 } ] }

{ 'name:': 'Apple-Iphone5-1_PT2098',
  time: 458262,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT7777.VxBn0g==',
       time: 41202,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1_PT7153.3coM6g==',
       time: 205059,
       result: 'Peer disconnected',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1_PT7153.jAFxCw==',
       time: 104657,
       result: 'DATA-TIMEOUT',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 90000 },
     { name: 'Apple-Iphone6-1_PT8234.+Hw2qA==',
       time: 107286,
       result: 'DATA-TIMEOUT',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 90000 } ] }

--------------- test report ---------------------
--------------- Apple-IpadAir2-1_PT7777 --------------------- : 1

peersList : 100% : 3674 ms, 99% : 3674 ms, 95 : 3674 ms, 90% : 3674 ms.

Result count 1, range 3674 ms to  3674 ms.

sendList : 100% : 5456 ms, 99% : 5456 ms, 95 : 5456 ms, 90% : 5456 ms.

Average data rate: 0.021 MB/s

Result count 3, range 3875 ms to  5456 ms.

sendList failed peers count : 1 [25 %]
- Peer ID : Apple-IpadAir2-1_PT7777.VxBn0g==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1_PT8234 --------------------- : 2

peersList : 100% : 255 ms, 99% : 255 ms, 95 : 255 ms, 90% : 255 ms.
Result count 1, range 255 ms to  255 ms.
sendList : 100% : 3245 ms, 99% : 3245 ms, 95 : 3245 ms, 90% : 3245 ms.
Average data rate: 0.031 MB/s
Result count 1, range 3245 ms to  3245 ms.
sendList failed peers count : 3 [75 %]
- Peer ID : Apple-IpadAir2-1_PT7777.VxBn0g==, Tried : 5
- Peer ID : Apple-Iphone5s-1_PT7153.3coM6g==, Tried : 5
- Peer ID : Apple-Iphone5s-1_PT7153.jAFxCw==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5s-1_PT7153 --------------------- : 3
peersList : 100% : 488 ms, 99% : 488 ms, 95 : 488 ms, 90% : 488 ms.
Result count 1, range 488 ms to  488 ms.
sendList : 100% : 3207 ms, 99% : 3207 ms, 95 : 3207 ms, 90% : 3207 ms.
Average data rate: 0.031 MB/s
Result count 1, range 3207 ms to  3207 ms.
sendList failed peers count : 3 [75 %]
- Peer ID : Apple-Iphone6-1_PT8234.n7uNOA==, Tried : 5
- Peer ID : Apple-Iphone5s-1_PT7153.3coM6g==, Tried : 5
- Peer ID : Apple-IpadAir2-1_PT7777.O0xngQ==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5-1_PT2098 --------------------- : 4
peersList : 100% : 1225 ms, 99% : 1225 ms, 95 : 1225 ms, 90% : 1225 ms.
Result count 1, range 1225 ms to  1225 ms.
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 4 [100 %]
- Peer ID : Apple-IpadAir2-1_PT7777.VxBn0g==, Tried : 5
- Peer ID : Apple-Iphone5s-1_PT7153.3coM6g==, Tried : 5
- Peer ID : Apple-Iphone5s-1_PT7153.jAFxCw==, Tried : 5
- Peer ID : Apple-Iphone6-1_PT8234.+Hw2qA==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------
peersList : 100% : 3674 ms, 99% : 3674 ms, 95 : 3674 ms, 90% : 3674 ms.
sendList : 100% : 5456 ms, 99% : 5456 ms, 95 : 5456 ms, 90% : 5456 ms.
Average data rate: 0.024 MB/s
--------------- end of test report ---------------------
{ 'Apple-IpadAir2-1_PT7777': 
   { peersList: [ [Object] ],
     sendList: [ [Object], [Object], [Object] ],
     sendError: { failedPeer: [Object], notTriedList: [] } },
  'Apple-Iphone6-1_PT8234': 
   { peersList: [ [Object] ],
     sendList: [ [Object] ],
     sendError: { failedPeer: [Object], notTriedList: [] } },
  'Apple-Iphone5s-1_PT7153': 
   { peersList: [ [Object] ],
     sendList: [ [Object] ],
     sendError: { failedPeer: [Object], notTriedList: [] } },
  'Apple-Iphone5-1_PT2098': 
   { peersList: [ [Object] ],
     sendList: [],
     sendError: { failedPeer: [Object], notTriedList: [] } } }



ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code 254 on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
ios: child process exited with code 254 on device 2a65f58f9902a701b5c9a55b2befb18672927474 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
true

```
###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/5065027835b6ad9_Enable_UnitTest_tobybrad/iOS_Iphone5-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/5065027835b6ad9_Enable_UnitTest_tobybrad/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/5065027835b6ad9_Enable_UnitTest_tobybrad/iOS_Iphone6-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/5065027835b6ad9_Enable_UnitTest_tobybrad/iOS_IpadAir2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/5065027835b6ad9_Enable_UnitTest_tobybrad/iOS_server.md)




#### Integration Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4}}
listening on *:3000

New perf test device..

New perf test device..

New perf test device..

New perf test device..

starting:testFindPeers.js

{ servertimeout: 1200000,
  timeout: 1000000,
  rounds: 1,
  dataTimeout: 10000,
  dataAmount: 100000,
  conReTryTimeout: 5000,
  conReTryCount: 5 }

starting:testFindPeers.js

{ servertimeout: 1200000,
  timeout: 1000000,
  rounds: 1,
  dataTimeout: 10000,
  dataAmount: 100000,
  conReTryTimeout: 5000,
  conReTryCount: 5,
  peerCount: 4 }

starting:testFindPeers.js

{ servertimeout: 1200000,
  timeout: 1000000,
  rounds: 1,
  dataTimeout: 10000,
  dataAmount: 100000,
  conReTryTimeout: 5000,
  conReTryCount: 5,
  peerCount: 4 }

starting:testFindPeers.js

{ servertimeout: 1200000,
  timeout: 1000000,
  rounds: 1,
  dataTimeout: 10000,
  dataAmount: 100000,
  conReTryTimeout: 5000,
  conReTryCount: 5,
  peerCount: 4 }

2015-12-03T11:04:05.296Z (239 sec) - ios test ID testFindPeers.js done now

Continuing to next test: testSendData.js

starting:testSendData.js

{ servertimeout: 1200000,
  timeout: 1000000,
  rounds: 1,
  dataTimeout: 10000,
  dataAmount: 100000,
  conReTryTimeout: 5000,
  conReTryCount: 5 }

starting:testSendData.js

{ servertimeout: 1200000,
  timeout: 1000000,
  rounds: 1,
  dataTimeout: 10000,
  dataAmount: 100000,
  conReTryTimeout: 5000,
  conReTryCount: 5,
  peerCount: 4 }

starting:testSendData.js

{ servertimeout: 1200000,
  timeout: 1000000,
  rounds: 1,
  dataTimeout: 10000,
  dataAmount: 100000,
  conReTryTimeout: 5000,
  conReTryCount: 5,
  peerCount: 4 }

starting:testSendData.js

{ servertimeout: 1200000,
  timeout: 1000000,
  rounds: 1,
  dataTimeout: 10000,
  dataAmount: 100000,
  conReTryTimeout: 5000,
  conReTryCount: 5,
  peerCount: 4 }

2015-12-03T11:11:43.829Z (698 sec) - ios test ID testSendData.js done now

ALL DONE !!!

{ 'name:': 'Apple-IpadAir2-1_PT7777',
  time: 3675,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1_PT2098.2PCWSw==',
       peerAvailable: true,
       time: 3674 } ] }

{ 'name:': 'Apple-Iphone6-1_PT8234',
  time: 256,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5s-1_PT7153.3coM6g==',
       peerAvailable: true,
       time: 255 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT7153',
  time: 490,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1_PT2098.2PCWSw==',
       peerAvailable: true,
       time: 488 } ] }

{ 'name:': 'Apple-Iphone5-1_PT2098',
  time: 1226,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1_PT7777.VxBn0g==',
       peerAvailable: true,
       time: 1225 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT7777',
  time: 55866,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT7777.VxBn0g==',
       time: 40720,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1_PT2098.P4cq9w==',
       time: 3875,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT7153.jAFxCw==',
       time: 5245,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT8234.+Hw2qA==',
       time: 5456,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1_PT8234',
  time: 354382,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT7777.VxBn0g==',
       time: 42868,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1_PT7153.3coM6g==',
       time: 205110,
       result: 'Peer disconnected',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1_PT7153.jAFxCw==',
       time: 103111,
       result: 'DATA-TIMEOUT',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 90000 },
     { name: 'Apple-IpadAir2-1_PT7777.O0xngQ==',
       time: 3245,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT7153',
  time: 356448,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT8234.n7uNOA==',
       time: 42343,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1_PT7153.3coM6g==',
       time: 205176,
       result: 'Peer disconnected',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT8234.+Hw2qA==',
       time: 3207,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT7777.O0xngQ==',
       time: 105610,
       result: 'DATA-TIMEOUT',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 90000 } ] }

{ 'name:': 'Apple-Iphone5-1_PT2098',
  time: 458262,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT7777.VxBn0g==',
       time: 41202,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1_PT7153.3coM6g==',
       time: 205059,
       result: 'Peer disconnected',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1_PT7153.jAFxCw==',
       time: 104657,
       result: 'DATA-TIMEOUT',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 90000 },
     { name: 'Apple-Iphone6-1_PT8234.+Hw2qA==',
       time: 107286,
       result: 'DATA-TIMEOUT',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 90000 } ] }

--------------- test report ---------------------
--------------- Apple-IpadAir2-1_PT7777 --------------------- : 1

peersList : 100% : 3674 ms, 99% : 3674 ms, 95 : 3674 ms, 90% : 3674 ms.

Result count 1, range 3674 ms to  3674 ms.

sendList : 100% : 5456 ms, 99% : 5456 ms, 95 : 5456 ms, 90% : 5456 ms.

Average data rate: 0.021 MB/s

Result count 3, range 3875 ms to  5456 ms.

sendList failed peers count : 1 [25 %]
- Peer ID : Apple-IpadAir2-1_PT7777.VxBn0g==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1_PT8234 --------------------- : 2

peersList : 100% : 255 ms, 99% : 255 ms, 95 : 255 ms, 90% : 255 ms.
Result count 1, range 255 ms to  255 ms.
sendList : 100% : 3245 ms, 99% : 3245 ms, 95 : 3245 ms, 90% : 3245 ms.
Average data rate: 0.031 MB/s
Result count 1, range 3245 ms to  3245 ms.
sendList failed peers count : 3 [75 %]
- Peer ID : Apple-IpadAir2-1_PT7777.VxBn0g==, Tried : 5
- Peer ID : Apple-Iphone5s-1_PT7153.3coM6g==, Tried : 5
- Peer ID : Apple-Iphone5s-1_PT7153.jAFxCw==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5s-1_PT7153 --------------------- : 3
peersList : 100% : 488 ms, 99% : 488 ms, 95 : 488 ms, 90% : 488 ms.
Result count 1, range 488 ms to  488 ms.
sendList : 100% : 3207 ms, 99% : 3207 ms, 95 : 3207 ms, 90% : 3207 ms.
Average data rate: 0.031 MB/s
Result count 1, range 3207 ms to  3207 ms.
sendList failed peers count : 3 [75 %]
- Peer ID : Apple-Iphone6-1_PT8234.n7uNOA==, Tried : 5
- Peer ID : Apple-Iphone5s-1_PT7153.3coM6g==, Tried : 5
- Peer ID : Apple-IpadAir2-1_PT7777.O0xngQ==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5-1_PT2098 --------------------- : 4
peersList : 100% : 1225 ms, 99% : 1225 ms, 95 : 1225 ms, 90% : 1225 ms.
Result count 1, range 1225 ms to  1225 ms.
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 4 [100 %]
- Peer ID : Apple-IpadAir2-1_PT7777.VxBn0g==, Tried : 5
- Peer ID : Apple-Iphone5s-1_PT7153.3coM6g==, Tried : 5
- Peer ID : Apple-Iphone5s-1_PT7153.jAFxCw==, Tried : 5
- Peer ID : Apple-Iphone6-1_PT8234.+Hw2qA==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------
peersList : 100% : 3674 ms, 99% : 3674 ms, 95 : 3674 ms, 90% : 3674 ms.
sendList : 100% : 5456 ms, 99% : 5456 ms, 95 : 5456 ms, 90% : 5456 ms.
Average data rate: 0.024 MB/s
--------------- end of test report ---------------------
{ 'Apple-IpadAir2-1_PT7777': 
   { peersList: [ [Object] ],
     sendList: [ [Object], [Object], [Object] ],
     sendError: { failedPeer: [Object], notTriedList: [] } },
  'Apple-Iphone6-1_PT8234': 
   { peersList: [ [Object] ],
     sendList: [ [Object] ],
     sendError: { failedPeer: [Object], notTriedList: [] } },
  'Apple-Iphone5s-1_PT7153': 
   { peersList: [ [Object] ],
     sendList: [ [Object] ],
     sendError: { failedPeer: [Object], notTriedList: [] } },
  'Apple-Iphone5-1_PT2098': 
   { peersList: [ [Object] ],
     sendList: [],
     sendError: { failedPeer: [Object], notTriedList: [] } } }


```


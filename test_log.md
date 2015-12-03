#### Test 506502782b2305a Logs

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

2015-12-03T00:42:23.489Z (236 sec) - ios test ID testFindPeers.js done now

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

2015-12-03T00:48:22.604Z (595 sec) - ios test ID testSendData.js done now

ALL DONE !!!

{ 'name:': 'Apple-IpadAir2-1_PT7682',
  time: 223,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT2613.bcJOyQ==',
       peerAvailable: true,
       time: 222 } ] }

{ 'name:': 'Apple-Iphone6-1_PT2613',
  time: 465,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5s-1_PT5704.8qCfew==',
       peerAvailable: true,
       time: 462 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT5704',
  time: 206,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT2613.bcJOyQ==',
       peerAvailable: true,
       time: 204 } ] }

{ 'name:': 'Apple-Iphone5-1_PT8796',
  time: 472,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT2613.bcJOyQ==',
       peerAvailable: true,
       time: 471 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT7682',
  time: 265808,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT2613.bcJOyQ==',
       time: 43651,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1_PT8796.xJ9gmA==',
       time: 2682,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT2613.ais2pw==',
       time: 110010,
       result: 'Peer disconnected',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 90000 },
     { name: 'Apple-Iphone5s-1_PT5704.2nX0ig==',
       time: 109435,
       result: 'DATA-TIMEOUT',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 90000 } ] }

{ 'name:': 'Apple-Iphone6-1_PT2613',
  time: 358298,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5s-1_PT5704.8qCfew==',
       time: 44228,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1_PT8796.xJ9gmA==',
       time: 104361,
       result: 'DATA-TIMEOUT',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 90000 },
     { name: 'Apple-Iphone5s-1_PT5704.2nX0ig==',
       time: 104422,
       result: 'DATA-TIMEOUT',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 90000 },
     { name: 'Apple-IpadAir2-1_PT7682.INb6UQ==',
       time: 105148,
       result: 'DATA-TIMEOUT',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 90000 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT5704',
  time: 51954,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT2613.bcJOyQ==',
       time: 42256,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1_PT8796.xJ9gmA==',
       time: 3140,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT2613.ais2pw==',
       time: 3352,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT7682.INb6UQ==',
       time: 2925,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1_PT8796',
  time: 262425,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5s-1_PT5704.8qCfew==',
       time: 47742,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1_PT5704.2nX0ig==',
       time: 104621,
       result: 'DATA-TIMEOUT',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 90000 },
     { name: 'Apple-Iphone6-1_PT2613.ais2pw==',
       time: 106265,
       result: 'DATA-TIMEOUT',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 90000 },
     { name: 'Apple-IpadAir2-1_PT7682.INb6UQ==',
       time: 3739,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

--------------- test report ---------------------
--------------- Apple-IpadAir2-1_PT7682 --------------------- : 1

peersList : 100% : 222 ms, 99% : 222 ms, 95 : 222 ms, 90% : 222 ms.

Result count 1, range 222 ms to  222 ms.

sendList : 100% : 2682 ms, 99% : 2682 ms, 95 : 2682 ms, 90% : 2682 ms.

Average data rate: 0.037 MB/s

Result count 1, range 2682 ms to  2682 ms.

sendList failed peers count : 3 [75 %]

- Peer ID : Apple-Iphone6-1_PT2613.bcJOyQ==, Tried : 5
- Peer ID : Apple-Iphone6-1_PT2613.ais2pw==, Tried : 5
- Peer ID : Apple-Iphone5s-1_PT5704.2nX0ig==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1_PT2613 --------------------- : 2
peersList : 100% : 462 ms, 99% : 462 ms, 95 : 462 ms, 90% : 462 ms.
Result count 1, range 462 ms to  462 ms.
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 4 [100 %]
- Peer ID : Apple-Iphone5s-1_PT5704.8qCfew==, Tried : 5
- Peer ID : Apple-Iphone5-1_PT8796.xJ9gmA==, Tried : 5
- Peer ID : Apple-Iphone5s-1_PT5704.2nX0ig==, Tried : 5
- Peer ID : Apple-IpadAir2-1_PT7682.INb6UQ==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5s-1_PT5704 --------------------- : 3
peersList : 100% : 204 ms, 99% : 204 ms, 95 : 204 ms, 90% : 204 ms.
Result count 1, range 204 ms to  204 ms.
sendList : 100% : 3352 ms, 99% : 3352 ms, 95 : 3352 ms, 90% : 3352 ms.
Average data rate: 0.032 MB/s
Result count 3, range 2925 ms to  3352 ms.
sendList failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone6-1_PT2613.bcJOyQ==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5-1_PT8796 --------------------- : 4
peersList : 100% : 471 ms, 99% : 471 ms, 95 : 471 ms, 90% : 471 ms.
Result count 1, range 471 ms to  471 ms.
sendList : 100% : 3739 ms, 99% : 3739 ms, 95 : 3739 ms, 90% : 3739 ms.
Average data rate: 0.027 MB/s
Result count 1, range 3739 ms to  3739 ms.
sendList failed peers count : 3 [75 %]
- Peer ID : Apple-Iphone5s-1_PT5704.8qCfew==, Tried : 5
- Peer ID : Apple-Iphone5s-1_PT5704.2nX0ig==, Tried : 5
- Peer ID : Apple-Iphone6-1_PT2613.ais2pw==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------
peersList : 100% : 471 ms, 99% : 471 ms, 95 : 471 ms, 90% : 471 ms.
sendList : 100% : 3739 ms, 99% : 3739 ms, 95 : 3739 ms, 90% : 3739 ms.
Average data rate: 0.032 MB/s
--------------- end of test report ---------------------

{ 'Apple-IpadAir2-1_PT7682': 
   { peersList: [ [Object] ],
     sendList: [ [Object] ],
     sendError: { failedPeer: [Object], notTriedList: [] } },
  'Apple-Iphone6-1_PT2613': 
   { peersList: [ [Object] ],
     sendList: [],
     sendError: { failedPeer: [Object], notTriedList: [] } },
  'Apple-Iphone5s-1_PT5704': 
   { peersList: [ [Object] ],
     sendList: [ [Object], [Object], [Object] ],
     sendError: { failedPeer: [Object], notTriedList: [] } },
  'Apple-Iphone5-1_PT8796': 
   { peersList: [ [Object] ],
     sendList: [ [Object] ],
     sendError: { failedPeer: [Object], notTriedList: [] } } }



ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code 254 on device 2a65f58f9902a701b5c9a55b2befb18672927474 
ios: child process exited with code 254 on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
true

```
###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/506502782b2305a_Enable_UnitTest_tobybrad/iOS_Iphone5-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/506502782b2305a_Enable_UnitTest_tobybrad/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/506502782b2305a_Enable_UnitTest_tobybrad/iOS_Iphone6-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/506502782b2305a_Enable_UnitTest_tobybrad/iOS_IpadAir2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/506502782b2305a_Enable_UnitTest_tobybrad/iOS_server.md)




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

2015-12-03T00:42:23.489Z (236 sec) - ios test ID testFindPeers.js done now

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

2015-12-03T00:48:22.604Z (595 sec) - ios test ID testSendData.js done now

ALL DONE !!!

{ 'name:': 'Apple-IpadAir2-1_PT7682',
  time: 223,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT2613.bcJOyQ==',
       peerAvailable: true,
       time: 222 } ] }

{ 'name:': 'Apple-Iphone6-1_PT2613',
  time: 465,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5s-1_PT5704.8qCfew==',
       peerAvailable: true,
       time: 462 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT5704',
  time: 206,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT2613.bcJOyQ==',
       peerAvailable: true,
       time: 204 } ] }

{ 'name:': 'Apple-Iphone5-1_PT8796',
  time: 472,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT2613.bcJOyQ==',
       peerAvailable: true,
       time: 471 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT7682',
  time: 265808,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT2613.bcJOyQ==',
       time: 43651,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1_PT8796.xJ9gmA==',
       time: 2682,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT2613.ais2pw==',
       time: 110010,
       result: 'Peer disconnected',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 90000 },
     { name: 'Apple-Iphone5s-1_PT5704.2nX0ig==',
       time: 109435,
       result: 'DATA-TIMEOUT',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 90000 } ] }

{ 'name:': 'Apple-Iphone6-1_PT2613',
  time: 358298,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5s-1_PT5704.8qCfew==',
       time: 44228,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1_PT8796.xJ9gmA==',
       time: 104361,
       result: 'DATA-TIMEOUT',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 90000 },
     { name: 'Apple-Iphone5s-1_PT5704.2nX0ig==',
       time: 104422,
       result: 'DATA-TIMEOUT',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 90000 },
     { name: 'Apple-IpadAir2-1_PT7682.INb6UQ==',
       time: 105148,
       result: 'DATA-TIMEOUT',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 90000 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT5704',
  time: 51954,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT2613.bcJOyQ==',
       time: 42256,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1_PT8796.xJ9gmA==',
       time: 3140,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT2613.ais2pw==',
       time: 3352,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT7682.INb6UQ==',
       time: 2925,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1_PT8796',
  time: 262425,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5s-1_PT5704.8qCfew==',
       time: 47742,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1_PT5704.2nX0ig==',
       time: 104621,
       result: 'DATA-TIMEOUT',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 90000 },
     { name: 'Apple-Iphone6-1_PT2613.ais2pw==',
       time: 106265,
       result: 'DATA-TIMEOUT',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 90000 },
     { name: 'Apple-IpadAir2-1_PT7682.INb6UQ==',
       time: 3739,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

--------------- test report ---------------------
--------------- Apple-IpadAir2-1_PT7682 --------------------- : 1

peersList : 100% : 222 ms, 99% : 222 ms, 95 : 222 ms, 90% : 222 ms.

Result count 1, range 222 ms to  222 ms.

sendList : 100% : 2682 ms, 99% : 2682 ms, 95 : 2682 ms, 90% : 2682 ms.

Average data rate: 0.037 MB/s

Result count 1, range 2682 ms to  2682 ms.

sendList failed peers count : 3 [75 %]

- Peer ID : Apple-Iphone6-1_PT2613.bcJOyQ==, Tried : 5
- Peer ID : Apple-Iphone6-1_PT2613.ais2pw==, Tried : 5
- Peer ID : Apple-Iphone5s-1_PT5704.2nX0ig==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1_PT2613 --------------------- : 2
peersList : 100% : 462 ms, 99% : 462 ms, 95 : 462 ms, 90% : 462 ms.
Result count 1, range 462 ms to  462 ms.
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 4 [100 %]
- Peer ID : Apple-Iphone5s-1_PT5704.8qCfew==, Tried : 5
- Peer ID : Apple-Iphone5-1_PT8796.xJ9gmA==, Tried : 5
- Peer ID : Apple-Iphone5s-1_PT5704.2nX0ig==, Tried : 5
- Peer ID : Apple-IpadAir2-1_PT7682.INb6UQ==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5s-1_PT5704 --------------------- : 3
peersList : 100% : 204 ms, 99% : 204 ms, 95 : 204 ms, 90% : 204 ms.
Result count 1, range 204 ms to  204 ms.
sendList : 100% : 3352 ms, 99% : 3352 ms, 95 : 3352 ms, 90% : 3352 ms.
Average data rate: 0.032 MB/s
Result count 3, range 2925 ms to  3352 ms.
sendList failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone6-1_PT2613.bcJOyQ==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5-1_PT8796 --------------------- : 4
peersList : 100% : 471 ms, 99% : 471 ms, 95 : 471 ms, 90% : 471 ms.
Result count 1, range 471 ms to  471 ms.
sendList : 100% : 3739 ms, 99% : 3739 ms, 95 : 3739 ms, 90% : 3739 ms.
Average data rate: 0.027 MB/s
Result count 1, range 3739 ms to  3739 ms.
sendList failed peers count : 3 [75 %]
- Peer ID : Apple-Iphone5s-1_PT5704.8qCfew==, Tried : 5
- Peer ID : Apple-Iphone5s-1_PT5704.2nX0ig==, Tried : 5
- Peer ID : Apple-Iphone6-1_PT2613.ais2pw==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------
peersList : 100% : 471 ms, 99% : 471 ms, 95 : 471 ms, 90% : 471 ms.
sendList : 100% : 3739 ms, 99% : 3739 ms, 95 : 3739 ms, 90% : 3739 ms.
Average data rate: 0.032 MB/s
--------------- end of test report ---------------------

{ 'Apple-IpadAir2-1_PT7682': 
   { peersList: [ [Object] ],
     sendList: [ [Object] ],
     sendError: { failedPeer: [Object], notTriedList: [] } },
  'Apple-Iphone6-1_PT2613': 
   { peersList: [ [Object] ],
     sendList: [],
     sendError: { failedPeer: [Object], notTriedList: [] } },
  'Apple-Iphone5s-1_PT5704': 
   { peersList: [ [Object] ],
     sendList: [ [Object], [Object], [Object] ],
     sendError: { failedPeer: [Object], notTriedList: [] } },
  'Apple-Iphone5-1_PT8796': 
   { peersList: [ [Object] ],
     sendList: [ [Object] ],
     sendError: { failedPeer: [Object], notTriedList: [] } } }


```


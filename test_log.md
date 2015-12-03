#### Test 506502782cf4552 Logs

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
  conReTryCount: 5 }

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
  conReTryCount: 5 }

2015-12-02T23:48:23.626Z (235 sec) - ios test ID testFindPeers.js done now

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
  conReTryCount: 5 }

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
  conReTryCount: 5 }

2015-12-02T23:48:24.414Z (236 sec) - ios test ID testSendData.js done now

ALL DONE !!!

{ 'name:': 'Apple-IpadAir2-1_PT6410',
  time: 532,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT3207.li3uFQ==',
       peerAvailable: true,
       time: 531 } ] }

{ 'name:': 'Apple-Iphone6-1_PT3207',
  time: 1404,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5s-1_PT6234.wFQ0hQ==',
       peerAvailable: true,
       time: 1398 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT6234',
  time: 364,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT3207.li3uFQ==',
       peerAvailable: true,
       time: 360 } ] }

{ 'name:': 'Apple-Iphone5-1_PT1924',
  time: 298,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT3207.li3uFQ==',
       peerAvailable: true,
       time: 298 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT6410',
  time: 481,
  result: 'OK',
  sendList: [] }

{ 'name:': 'Apple-Iphone6-1_PT3207',
  time: 17,
  result: 'OK',
  sendList: [] }

{ 'name:': 'Apple-Iphone5s-1_PT6234',
  time: 62,
  result: 'OK',
  sendList: [] }

{ 'name:': 'Apple-Iphone5-1_PT1924',
  time: 31,
  result: 'OK',
  sendList: [] }

--------------- test report ---------------------
--------------- Apple-IpadAir2-1_PT6410 --------------------- : 1

peersList : 100% : 531 ms, 99% : 531 ms, 95 : 531 ms, 90% : 531 ms.

Result count 1, range 531 ms to  531 ms.
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.

Average data rate: NaN MB/s

Results list does not contain any items

--------------- Apple-Iphone6-1_PT3207 --------------------- : 2
peersList : 100% : 1398 ms, 99% : 1398 ms, 95 : 1398 ms, 90% : 1398 ms.
Result count 1, range 1398 ms to  1398 ms.

sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items

--------------- Apple-Iphone5s-1_PT6234 --------------------- : 3
peersList : 100% : 360 ms, 99% : 360 ms, 95 : 360 ms, 90% : 360 ms.
Result count 1, range 360 ms to  360 ms.

sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
--------------- Apple-Iphone5-1_PT1924 --------------------- : 4
peersList : 100% : 298 ms, 99% : 298 ms, 95 : 298 ms, 90% : 298 ms.
Result count 1, range 298 ms to  298 ms.
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
--------------- Combined ---------------------
peersList : 100% : 1398 ms, 99% : 1398 ms, 95 : 1398 ms, 90% : 1398 ms.
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
--------------- end of test report ---------------------
{ 'Apple-IpadAir2-1_PT6410': 
   { peersList: [ [Object] ],
     sendList: [],
     sendError: { failedPeer: [], notTriedList: [] } },
  'Apple-Iphone6-1_PT3207': 
   { peersList: [ [Object] ],
     sendList: [],
     sendError: { failedPeer: [], notTriedList: [] } },
  'Apple-Iphone5s-1_PT6234': 
   { peersList: [ [Object] ],
     sendList: [],
     sendError: { failedPeer: [], notTriedList: [] } },
  'Apple-Iphone5-1_PT1924': 
   { peersList: [ [Object] ],
     sendList: [],
     sendError: { failedPeer: [], notTriedList: [] } } }



ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code 254 on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
ios: child process exited with code 254 on device 2a65f58f9902a701b5c9a55b2befb18672927474 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true

```
###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/506502782cf4552_Enable_UnitTest_tobybrad/iOS_Iphone5-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/506502782cf4552_Enable_UnitTest_tobybrad/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/506502782cf4552_Enable_UnitTest_tobybrad/iOS_Iphone6-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/506502782cf4552_Enable_UnitTest_tobybrad/iOS_IpadAir2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/506502782cf4552_Enable_UnitTest_tobybrad/iOS_server.md)




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
  conReTryCount: 5 }

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
  conReTryCount: 5 }

2015-12-02T23:48:23.626Z (235 sec) - ios test ID testFindPeers.js done now

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
  conReTryCount: 5 }

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
  conReTryCount: 5 }

2015-12-02T23:48:24.414Z (236 sec) - ios test ID testSendData.js done now

ALL DONE !!!

{ 'name:': 'Apple-IpadAir2-1_PT6410',
  time: 532,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT3207.li3uFQ==',
       peerAvailable: true,
       time: 531 } ] }

{ 'name:': 'Apple-Iphone6-1_PT3207',
  time: 1404,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5s-1_PT6234.wFQ0hQ==',
       peerAvailable: true,
       time: 1398 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT6234',
  time: 364,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT3207.li3uFQ==',
       peerAvailable: true,
       time: 360 } ] }

{ 'name:': 'Apple-Iphone5-1_PT1924',
  time: 298,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT3207.li3uFQ==',
       peerAvailable: true,
       time: 298 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT6410',
  time: 481,
  result: 'OK',
  sendList: [] }

{ 'name:': 'Apple-Iphone6-1_PT3207',
  time: 17,
  result: 'OK',
  sendList: [] }

{ 'name:': 'Apple-Iphone5s-1_PT6234',
  time: 62,
  result: 'OK',
  sendList: [] }

{ 'name:': 'Apple-Iphone5-1_PT1924',
  time: 31,
  result: 'OK',
  sendList: [] }

--------------- test report ---------------------
--------------- Apple-IpadAir2-1_PT6410 --------------------- : 1

peersList : 100% : 531 ms, 99% : 531 ms, 95 : 531 ms, 90% : 531 ms.

Result count 1, range 531 ms to  531 ms.
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.

Average data rate: NaN MB/s

Results list does not contain any items

--------------- Apple-Iphone6-1_PT3207 --------------------- : 2
peersList : 100% : 1398 ms, 99% : 1398 ms, 95 : 1398 ms, 90% : 1398 ms.
Result count 1, range 1398 ms to  1398 ms.

sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items

--------------- Apple-Iphone5s-1_PT6234 --------------------- : 3
peersList : 100% : 360 ms, 99% : 360 ms, 95 : 360 ms, 90% : 360 ms.
Result count 1, range 360 ms to  360 ms.

sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
--------------- Apple-Iphone5-1_PT1924 --------------------- : 4
peersList : 100% : 298 ms, 99% : 298 ms, 95 : 298 ms, 90% : 298 ms.
Result count 1, range 298 ms to  298 ms.
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
--------------- Combined ---------------------
peersList : 100% : 1398 ms, 99% : 1398 ms, 95 : 1398 ms, 90% : 1398 ms.
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
--------------- end of test report ---------------------
{ 'Apple-IpadAir2-1_PT6410': 
   { peersList: [ [Object] ],
     sendList: [],
     sendError: { failedPeer: [], notTriedList: [] } },
  'Apple-Iphone6-1_PT3207': 
   { peersList: [ [Object] ],
     sendList: [],
     sendError: { failedPeer: [], notTriedList: [] } },
  'Apple-Iphone5s-1_PT6234': 
   { peersList: [ [Object] ],
     sendList: [],
     sendError: { failedPeer: [], notTriedList: [] } },
  'Apple-Iphone5-1_PT1924': 
   { peersList: [ [Object] ],
     sendList: [],
     sendError: { failedPeer: [], notTriedList: [] } } }


```


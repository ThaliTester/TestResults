#### Test 5546736337bcedb Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-08T14:53:10.010Z - info: listening on *:3000

2016-01-08T14:53:10.682Z - debug: Device presented: Apple-Iphone5-1 (ios) perftest socket:0

2016-01-08T14:53:10.688Z - info: Setting start timeout to: 120000 (ios)

2016-01-08T14:53:10.703Z - debug: Device presented: Thali Test (Galaxy A5) (android) perftest socket:1

2016-01-08T14:53:10.705Z - info: Setting start timeout to: 120000 (android)

2016-01-08T14:53:10.802Z - debug: Device presented: A3-1 (android) perftest socket:3

2016-01-08T14:53:10.839Z - debug: Device presented: Thali Test's G2 (android) perftest socket:2

2016-01-08T14:53:10.982Z - debug: Device presented: Apple-Iphone5s-1 (ios) perftest socket:4

2016-01-08T14:53:11.146Z - debug: Device presented: Note4-1 (android) perftest socket:5

2016-01-08T14:53:11.409Z - debug: Device presented: HTC Desire 820 (android) perftest socket:6

2016-01-08T14:53:11.623Z - debug: Device presented: G4-1 (android) perftest socket:7

2016-01-08T14:53:12.292Z - debug: Device presented: Apple-IpadAir2-1 (ios) perftest socket:9

2016-01-08T14:53:12.300Z - debug: Device presented: G3s-1 (android) perftest socket:8

2016-01-08T14:53:13.252Z - debug: Device presented: G3-1 (android) perftest socket:10

2016-01-08T14:53:13.506Z - debug: Device presented: XT1072 (android) perftest socket:11

2016-01-08T14:53:13.705Z - debug: Device presented: S5-1 (android) perftest socket:12

2016-01-08T14:53:14.057Z - debug: Device presented: Nexus 5 (android) perftest socket:13

2016-01-08T14:53:14.215Z - debug: Device presented: Thali Test (Galaxy A3) (android) perftest socket:14

2016-01-08T14:53:14.685Z - debug: Device presented: Nexus 5 (android) perftest socket:15

2016-01-08T14:53:14.727Z - debug: Device presented: A5-1 (android) perftest socket:16

2016-01-08T14:53:14.892Z - debug: Device presented: Thali Test (Galaxy S5) (android) perftest socket:18

2016-01-08T14:53:14.896Z - debug: Device presented: S5mini-1 (android) perftest socket:17

2016-01-08T14:53:14.973Z - debug: Device presented: Apple-Iphone6-1 (ios) perftest socket:19

2016-01-08T14:53:14.974Z - info: Required number of devices presented

2016-01-08T14:53:14.978Z - info: Starting perf test run for platform: ios

2016-01-08T14:53:14.979Z - info: Using devices:

2016-01-08T14:53:14.980Z - info: Apple-Iphone5-1

2016-01-08T14:53:14.984Z - info: Apple-Iphone5s-1

2016-01-08T14:53:14.984Z - info: Apple-IpadAir2-1

2016-01-08T14:53:14.985Z - info: Apple-Iphone6-1

2016-01-08T14:53:14.989Z - info: Starting test: with 4 devices (ios)

2016-01-08T14:53:15.395Z - debug: Device presented: HTC Desire 820 (android) perftest socket:20

2016-01-08T14:53:16.360Z - info: Received results for {"name:":"Apple-Iphone6-1","time":1216,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-IpadAir2-1.xmg6Nw==","peerAvailable":true,"time":1214}]} Apple-Iphone6-1 ios (3 left)

2016-01-08T14:53:17.085Z - info: Received results for {"name:":"Apple-Iphone5-1","time":1587,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone6-1.j1bF8Q==","peerAvailable":true,"time":1586}]} Apple-Iphone5-1 ios (2 left)

2016-01-08T14:53:17.553Z - info: Received results for {"name:":"Apple-IpadAir2-1","time":2198,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone5-1.oJtw2A==","peerAvailable":true,"time":2196}]} Apple-IpadAir2-1 ios (1 left)

2016-01-08T14:53:18.179Z - debug: Device presented: XT1039 (android) perftest socket:21

2016-01-08T14:53:18.982Z - info: Received results for {"name:":"Apple-Iphone5s-1","time":668,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone6-1.j1bF8Q==","peerAvailable":true,"time":665}]} Apple-Iphone5s-1 ios (0 left)

2016-01-08T14:53:18.986Z - info: All test data retrieved for testFindPeers.js (ios)

2016-01-08T14:53:18.996Z - info: Remaining tests: testSendData.js

2016-01-08T14:53:18.998Z - info: Continuing to next test: testSendData.js

2016-01-08T14:53:19.000Z - info: Starting test: with 4 devices (ios)

2016-01-08T14:54:16.220Z - info: Received results for {"name:":"Apple-Iphone6-1","time":56502,"result":"OK","sendList":[{"name":"Apple-Iphone6-1.j1bF8Q==","time":40561,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-IpadAir2-1.+bX+WA==","time":6909,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1.ziR9IQ==","time":3779,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1.zHt1vQ==","time":4566,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone6-1 ios (3 left)

2016-01-08T14:54:16.225Z - info: Received results for {"name:":"Apple-Iphone5s-1","time":56910,"result":"OK","sendList":[{"name":"Apple-Iphone6-1.j1bF8Q==","time":41721,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-IpadAir2-1.+bX+WA==","time":7478,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1.ziR9IQ==","time":3799,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1.bICwVA==","time":3705,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone5s-1 ios (2 left)

2016-01-08T14:54:18.319Z - info: Received results for {"name:":"Apple-IpadAir2-1","time":58886,"result":"OK","sendList":[{"name":"Apple-Iphone5-1.oJtw2A==","time":41276,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-Iphone5-1.ziR9IQ==","time":8834,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1.bICwVA==","time":4149,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1.zHt1vQ==","time":4463,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-IpadAir2-1 ios (1 left)

2016-01-08T14:54:18.416Z - info: Received results for {"name:":"Apple-Iphone5-1","time":58821,"result":"OK","sendList":[{"name":"Apple-Iphone5-1.oJtw2A==","time":41293,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-IpadAir2-1.+bX+WA==","time":9095,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1.zHt1vQ==","time":4346,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1.bICwVA==","time":3974,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone5-1 ios (0 left)

2016-01-08T14:54:18.417Z - info: All test data retrieved for testSendData.js (ios)

2016-01-08T14:54:18.423Z - info: ALL DONE !!!

{ 'name:': 'Apple-Iphone5-1',
  time: 1587,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1.j1bF8Q==',
       peerAvailable: true,
       time: 1586 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 668,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1.j1bF8Q==',
       peerAvailable: true,
       time: 665 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 2198,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1.oJtw2A==',
       peerAvailable: true,
       time: 2196 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 1216,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1.xmg6Nw==',
       peerAvailable: true,
       time: 1214 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 58821,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.oJtw2A==',
       time: 41293,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.+bX+WA==',
       time: 9095,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.zHt1vQ==',
       time: 4346,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.bICwVA==',
       time: 3974,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 56910,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1.j1bF8Q==',
       time: 41721,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.+bX+WA==',
       time: 7478,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.ziR9IQ==',
       time: 3799,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.bICwVA==',
       time: 3705,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 58886,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.oJtw2A==',
       time: 41276,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.ziR9IQ==',
       time: 8834,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.bICwVA==',
       time: 4149,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.zHt1vQ==',
       time: 4463,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 56502,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1.j1bF8Q==',
       time: 40561,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.+bX+WA==',
       time: 6909,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.ziR9IQ==',
       time: 3779,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.zHt1vQ==',
       time: 4566,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

--------------- test report ---------------------
--------------- Apple-Iphone5-1 --------------------- : 1

Find peers : 100% : 1586 ms, 99% : 1586 ms, 95 : 1586 ms, 90% : 1586 ms.

Result count 1, range 1586 ms to  1586 ms.

Send data : 100% : 9095 ms, 99% : 9095 ms, 95 : 9095 ms, 90% : 9095 ms.

Average data rate: 0.017 MB/s

Result count 3, range 3974 ms to  9095 ms.

Send data failed peers count : 1 [25 %]

- Peer ID : Apple-Iphone5-1.oJtw2A==, Tried : 5

Send data never tried peers count : 0 [0 %]
--------------- Apple-Iphone5s-1 --------------------- : 2

Find peers : 100% : 665 ms, 99% : 665 ms, 95 : 665 ms, 90% : 665 ms.
Result count 1, range 665 ms to  665 ms.

Send data : 100% : 7478 ms, 99% : 7478 ms, 95 : 7478 ms, 90% : 7478 ms.

Average data rate: 0.02 MB/s
Result count 3, range 3705 ms to  7478 ms.
Send data failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone6-1.j1bF8Q==, Tried : 5
Send data never tried peers count : 0 [0 %]
--------------- Apple-IpadAir2-1 --------------------- : 3

Find peers : 100% : 2196 ms, 99% : 2196 ms, 95 : 2196 ms, 90% : 2196 ms.
Result count 1, range 2196 ms to  2196 ms.
Send data : 100% : 8834 ms, 99% : 8834 ms, 95 : 8834 ms, 90% : 8834 ms.

Average data rate: 0.017 MB/s
Result count 3, range 4149 ms to  8834 ms.
Send data failed peers count : 1 [25 %]

- Peer ID : Apple-Iphone5-1.oJtw2A==, Tried : 5
Send data never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1 --------------------- : 4

Find peers : 100% : 1214 ms, 99% : 1214 ms, 95 : 1214 ms, 90% : 1214 ms.
Result count 1, range 1214 ms to  1214 ms.

Send data : 100% : 6909 ms, 99% : 6909 ms, 95 : 6909 ms, 90% : 6909 ms.
Average data rate: 0.02 MB/s
Result count 3, range 3779 ms to  6909 ms.

Send data failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone6-1.j1bF8Q==, Tried : 5
Send data never tried peers count : 0 [0 %]

--------------- Combined ---------------------

Find peers : 100% : 2196 ms, 99% : 2196 ms, 95 : 2196 ms, 90% : 2196 ms.

Send data : 100% : 9095 ms, 99% : 9095 ms, 95 : 8834 ms, 90% : 8834 ms.
Average data rate: 0.018 MB/s

--------------- end of test report ---------------------

2016-01-08T14:54:18.551Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1.j1bF8Q==, peerAvailable=true, time=1586], sendList=[name=Apple-Iphone6-1.bICwVA==, time=3974, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5s-1.zHt1vQ==, time=4346, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.+bX+WA==, time=9095, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone5-1.oJtw2A==, time=41293, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1.j1bF8Q==, peerAvailable=true, time=665], sendList=[name=Apple-Iphone6-1.bICwVA==, time=3705, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1.ziR9IQ==, time=3799, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.+bX+WA==, time=7478, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone6-1.j1bF8Q==, time=41721, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1.oJtw2A==, peerAvailable=true, time=2196], sendList=[name=Apple-Iphone6-1.bICwVA==, time=4149, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5s-1.zHt1vQ==, time=4463, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1.ziR9IQ==, time=8834, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone5-1.oJtw2A==, time=41276, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1.xmg6Nw==, peerAvailable=true, time=1214], sendList=[name=Apple-Iphone5-1.ziR9IQ==, time=3779, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5s-1.zHt1vQ==, time=4566, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.+bX+WA==, time=6909, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone6-1.j1bF8Q==, time=40561, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[]

2016-01-08T14:54:18.561Z - debug: end to Apple-Iphone5-1

2016-01-08T14:54:18.563Z - debug: end to Apple-Iphone5s-1

2016-01-08T14:54:18.564Z - debug: end to Apple-IpadAir2-1

2016-01-08T14:54:18.566Z - debug: end to Apple-Iphone6-1

2016-01-08T14:54:20.788Z - debug: state: ios completed
2016-01-08T14:54:20.789Z - debug: state: android waiting

2016-01-08T14:54:21.352Z - debug: Socket disconnected: transport close 4 (Apple-Iphone5s-1)

2016-01-08T14:54:21.376Z - debug: Socket disconnected: transport close 9 (Apple-IpadAir2-1)

2016-01-08T14:54:21.535Z - debug: Socket disconnected: transport close 19 (Apple-Iphone6-1)

2016-01-08T14:54:22.343Z - debug: Socket disconnected: transport close 0 (Apple-Iphone5-1)

2016-01-08T14:55:10.708Z - info: Start timeout elapsed for platform: android

2016-01-08T14:55:10.711Z - info: Starting perf test run for platform: android

2016-01-08T14:55:10.712Z - info: Using devices:
2016-01-08T14:55:10.712Z - info: Thali Test (Galaxy A5)

2016-01-08T14:55:10.713Z - info: A3-1
2016-01-08T14:55:10.714Z - info: Thali Test's G2

2016-01-08T14:55:10.718Z - info: Note4-1

2016-01-08T14:55:10.726Z - info: HTC Desire 820

2016-01-08T14:55:10.729Z - info: G4-1
2016-01-08T14:55:10.729Z - info: G3s-1

2016-01-08T14:55:10.730Z - info: G3-1
2016-01-08T14:55:10.731Z - info: XT1072

2016-01-08T14:55:10.732Z - info: S5-1
2016-01-08T14:55:10.732Z - info: Nexus 5

2016-01-08T14:55:10.733Z - info: Thali Test (Galaxy A3)
2016-01-08T14:55:10.734Z - info: Nexus 5

2016-01-08T14:55:10.735Z - info: A5-1
2016-01-08T14:55:10.735Z - info: Thali Test (Galaxy S5)

2016-01-08T14:55:10.736Z - info: S5mini-1
2016-01-08T14:55:10.737Z - info: HTC Desire 820

2016-01-08T14:55:10.737Z - info: XT1039

2016-01-08T14:55:10.739Z - info: Starting test: with 18 devices (android)

2016-01-08T14:56:15.951Z - debug: Socket disconnected: ping timeout 2 (Thali Test's G2)

2016-01-08T14:56:19.177Z - debug: Socket disconnected: ping timeout 13 (Nexus 5)

2016-01-08T14:56:19.939Z - debug: Socket disconnected: ping timeout 17 (S5mini-1)

2016-01-08T14:56:23.247Z - debug: Socket disconnected: ping timeout 21 (XT1039)

2016-01-08T14:56:41.550Z - debug: Socket disconnected: ping timeout 6 (HTC Desire 820)

2016-01-08T14:56:43.411Z - info: Received results for {"name:":"G4-1","time":91872,"result":"OK","peersList":[{"peerName":"<no peer name>","peerIdentifier":"44:80:EB:7B:5A:5","peerAvailable":true,"time":361},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:34:8A:A0","peerAvailable":true,"time":400},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:37:96:AB","peerAvailable":true,"time":586},{"peerName":"<no peer name>","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":643},{"peerName":"<no peer name>","peerIdentifier":"8:EC:A9:50:76:27","peerAvailable":true,"time":827},{"peerName":"<no peer name>","peerIdentifier":"8:EC:A9:50:75:41","peerAvailable":true,"time":949},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:51:18:22","peerAvailable":true,"time":5511},{"peerName":"<no peer name>","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":7370},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":7639},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":21945},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":31274},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":36897},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":45078},{"peerName":"Nexus 5","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":true,"time":45238},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":48579},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":91729},{"peerName":"XT1072","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true,"time":91871}]} G4-1 android (17 left)

2016-01-08T14:56:49.126Z - debug: Socket disconnected: ping timeout 20 (HTC Desire 820)

2016-01-08T14:56:51.183Z - info: Received results for {"name:":"S5-1","time":100237,"result":"TIMEOUT","peersList":[{"peerName":"<no peer name>","peerIdentifier":"44:80:EB:7B:5A:5","peerAvailable":true,"time":499},{"peerName":"<no peer name>","peerIdentifier":"8:EC:A9:50:75:41","peerAvailable":true,"time":796},{"peerName":"<no peer name>","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":1234},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:51:18:22","peerAvailable":true,"time":1421},{"peerName":"<no peer name>","peerIdentifier":"8:EC:A9:50:76:27","peerAvailable":true,"time":1424},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:37:96:AB","peerAvailable":true,"time":1428},{"peerName":"<no peer name>","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":1702},{"peerName":"<no peer name>","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":3343},{"peerName":"Nexus 5","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":true,"time":3880},{"peerName":"XT1072","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":false,"time":90525},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":false,"time":90545},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":30499},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":46108}]} S5-1 android (16 left)

2016-01-08T14:56:51.229Z - info: Received results for {"name:":"G3s-1","time":100144,"result":"TIMEOUT","peersList":[{"peerName":"Nexus 5","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":true,"time":2424},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":23951},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":28723}]} G3s-1 android (15 left)

2016-01-08T14:56:51.280Z - info: Received results for {"name:":"XT1072","time":100245,"result":"TIMEOUT","peersList":[{"peerName":"Nexus 5","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":true,"time":2941},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":3159},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:37:96:AB","peerAvailable":false,"time":92974},{"peerName":"<no peer name>","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":false,"time":92970},{"peerName":"<no peer name>","peerIdentifier":"8:EC:A9:50:75:41","peerAvailable":false,"time":92965},{"peerName":"<no peer name>","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":false,"time":92960},{"peerName":"<no peer name>","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":false,"time":92946},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:34:8A:A0","peerAvailable":false,"time":92945},{"peerName":"<no peer name>","peerIdentifier":"8:EC:A9:50:76:27","peerAvailable":false,"time":92941},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:51:18:22","peerAvailable":true,"time":6738},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":44289},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":48279},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":48482}]} XT1072 android (14 left)

2016-01-08T14:56:51.289Z - info: Received results for {"name:":"Thali Test (Galaxy A3)","time":100247,"result":"TIMEOUT","peersList":[{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:51:18:22","peerAvailable":true,"time":1265},{"peerName":"<no peer name>","peerIdentifier":"44:80:EB:7B:5A:5","peerAvailable":true,"time":1271},{"peerName":"<no peer name>","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":1343},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:34:8A:A0","peerAvailable":true,"time":1357},{"peerName":"<no peer name>","peerIdentifier":"8:EC:A9:50:75:41","peerAvailable":true,"time":1394},{"peerName":"<no peer name>","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":1555},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:37:96:AB","peerAvailable":true,"time":1557},{"peerName":"Nexus 5","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":true,"time":4267},{"peerName":"XT1072","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":false,"time":91265},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":5352},{"peerName":"<no peer name>","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":14239},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":65985},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":67639},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":77760}]} Thali Test (Galaxy A3) android (13 left)

2016-01-08T14:56:51.355Z - info: Received results for {"name:":"Nexus 5","time":100067,"result":"TIMEOUT","peersList":[{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":47029},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":59178},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":60187},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":62938},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":66038}]} Nexus 5 android (12 left)

2016-01-08T14:56:51.361Z - info: Received results for {"name:":"Note4-1","time":100289,"result":"TIMEOUT","peersList":[{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:34:8A:A0","peerAvailable":true,"time":312},{"peerName":"<no peer name>","peerIdentifier":"44:80:EB:7B:5A:5","peerAvailable":true,"time":314},{"peerName":"<no peer name>","peerIdentifier":"8:EC:A9:50:75:41","peerAvailable":true,"time":317},{"peerName":"<no peer name>","peerIdentifier":"8:EC:A9:50:76:27","peerAvailable":true,"time":492},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:37:96:AB","peerAvailable":true,"time":494},{"peerName":"<no peer name>","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":1028},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:51:18:22","peerAvailable":true,"time":1240},{"peerName":"<no peer name>","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":2888},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":6990},{"peerName":"XT1072","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true,"time":9130},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":15493},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":37181},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":37356},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":44774}]} Note4-1 android (11 left)

2016-01-08T14:56:51.365Z - info: Received results for {"name:":"A3-1","time":100224,"result":"TIMEOUT","peersList":[{"peerName":"<no peer name>","peerIdentifier":"44:80:EB:7B:5A:5","peerAvailable":true,"time":2281},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:34:8A:A0","peerAvailable":true,"time":2637},{"peerName":"XT1072","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":false,"time":92289},{"peerName":"Nexus 5","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":true,"time":4939},{"peerName":"<no peer name>","peerIdentifier":"8:EC:A9:50:76:27","peerAvailable":true,"time":5169},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":5461},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":false,"time":92286},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":5703},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:51:18:22","peerAvailable":true,"time":6474},{"peerName":"<no peer name>","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":6728},{"peerName":"<no peer name>","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":6992},{"peerName":"<no peer name>","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":7028},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:37:96:AB","peerAvailable":true,"time":12004},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":15968},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":16721},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":67812}]} A3-1 android (10 left)

2016-01-08T14:56:51.734Z - info: Received results for {"name:":"Thali Test (Galaxy A5)","time":100255,"result":"TIMEOUT","peersList":[{"peerName":"<no peer name>","peerIdentifier":"44:80:EB:7B:5A:5","peerAvailable":true,"time":2595},{"peerName":"<no peer name>","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":4026},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:37:96:AB","peerAvailable":true,"time":4027},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:34:8A:A0","peerAvailable":true,"time":4030},{"peerName":"<no peer name>","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":4041},{"peerName":"<no peer name>","peerIdentifier":"8:EC:A9:50:76:27","peerAvailable":true,"time":4244},{"peerName":"<no peer name>","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":4251},{"peerName":"<no peer name>","peerIdentifier":"8:EC:A9:50:75:41","peerAvailable":true,"time":4382},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":82545}]} Thali Test (Galaxy A5) android (9 left)

2016-01-08T14:56:51.858Z - info: Received results for {"name:":"A5-1","time":100266,"result":"TIMEOUT","peersList":[{"peerName":"<no peer name>","peerIdentifier":"44:80:EB:7B:5A:5","peerAvailable":true,"time":5630},{"peerName":"<no peer name>","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":5699},{"peerName":"<no peer name>","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":5752},{"peerName":"<no peer name>","peerIdentifier":"8:EC:A9:50:75:41","peerAvailable":true,"time":5837},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:51:18:22","peerAvailable":true,"time":5953},{"peerName":"<no peer name>","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":5959},{"peerName":"<no peer name>","peerIdentifier":"8:EC:A9:50:76:27","peerAvailable":true,"time":7537},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:34:8A:A0","peerAvailable":true,"time":16001},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":86282}]} A5-1 android (8 left)

2016-01-08T14:56:54.060Z - info: Received results for {"name:":"Thali Test (Galaxy S5)","time":100324,"result":"TIMEOUT","peersList":[{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:51:18:22","peerAvailable":true,"time":386},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:37:96:AB","peerAvailable":true,"time":416},{"peerName":"<no peer name>","peerIdentifier":"8:EC:A9:50:75:41","peerAvailable":true,"time":536},{"peerName":"<no peer name>","peerIdentifier":"44:80:EB:7B:5A:5","peerAvailable":true,"time":575},{"peerName":"<no peer name>","peerIdentifier":"8:EC:A9:50:76:27","peerAvailable":true,"time":737},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:34:8A:A0","peerAvailable":true,"time":1237},{"peerName":"<no peer name>","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":1740},{"peerName":"<no peer name>","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":5114},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":53638},{"peerName":"XT1072","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true,"time":62253},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":78164}]} Thali Test (Galaxy S5) android (7 left)

2016-01-08T14:56:55.276Z - info: Received results for {"name:":"G3-1","time":100085,"result":"TIMEOUT","peersList":[{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":false,"time":92197},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":8203},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":25012},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":false,"time":92201},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":25312},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":25394},{"peerName":"Note4-1","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":33181},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":43761},{"peerName":"XT1072","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true,"time":97081}]} G3-1 android (6 left)

2016-01-08T14:57:10.799Z - info: server timeout for test: testFindPeers.js (android)

2016-01-08T14:57:10.802Z - info: All test data retrieved for testFindPeers.js (android)

2016-01-08T14:57:10.807Z - info: No results from Thali Test's G2

2016-01-08T14:57:10.815Z - info: No results from HTC Desire 820

2016-01-08T14:57:10.821Z - info: No results from Nexus 5

2016-01-08T14:57:10.826Z - info: No results from S5mini-1

2016-01-08T14:57:10.827Z - info: No results from HTC Desire 820

2016-01-08T14:57:10.828Z - info: No results from XT1039

2016-01-08T14:57:10.829Z - info: Remaining tests: testSendData.js

2016-01-08T14:57:10.832Z - info: Continuing to next test: testSendData.js
2016-01-08T14:57:10.833Z - info: Starting test: with 18 devices (android)

2016-01-08T14:58:51.145Z - info: Received results for {"name:":"G3-1","time":100106,"result":"TIMEOUT","sendList":[{"name":"34:FC:EF:11:AE:67","time":46252,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":26741,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:37:96:AB","time":24500,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"34:FC:EF:11:B1:66","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"B4:CE:F6:AB:A4:6A","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:9D:93:0B","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"80:01:84:8A:B3:68","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"}]} G3-1 android (17 left)

2016-01-08T14:58:51.212Z - info: Received results for {"name:":"G4-1","time":100191,"result":"TIMEOUT","sendList":[{"name":"08:EC:A9:50:75:41","time":9185,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":14662,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:9D:93:0B","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:B1:66","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"B4:CE:F6:AB:A4:6A","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"80:01:84:8A:B3:68","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"}]} G4-1 android (16 left)

2016-01-08T14:58:51.306Z - info: Received results for {"name:":"Nexus 5","time":100053,"result":"TIMEOUT","sendList":[{"name":"7C:F9:0E:37:96:AB","time":8766,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:B1:66","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"B4:CE:F6:AB:A4:6A","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"80:01:84:8A:B3:68","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":1,"name":"34:FC:EF:9D:93:0B","time":0,"result":"Fail"}]} Nexus 5 android (15 left)

2016-01-08T14:58:51.339Z - info: Received results for {"name:":"A3-1","time":100220,"result":"TIMEOUT","sendList":[{"connections":1,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:B1:66","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:9D:93:0B","time":0,"result":"Fail"},{"connections":0,"name":"B4:CE:F6:AB:A4:6A","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"80:01:84:8A:B3:68","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"}]} A3-1 android (14 left)

2016-01-08T14:58:51.762Z - info: Received results for {"name:":"Note4-1","time":100246,"result":"TIMEOUT","sendList":[{"name":"58:3F:54:73:64:C0","time":18534,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"B4:CE:F6:AB:A4:6A","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:9D:93:0B","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:B1:66","time":0,"result":"Fail"},{"connections":1,"name":"80:01:84:8A:B3:68","time":0,"result":"Fail"}]} Note4-1 android (13 left)

2016-01-08T14:58:51.954Z - info: Received results for {"name:":"G3s-1","time":100137,"result":"TIMEOUT","sendList":[{"name":"B0:C5:59:3F:75:69","time":9694,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:9D:93:0B","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"80:01:84:8A:B3:68","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"},{"connections":0,"name":"B4:CE:F6:AB:A4:6A","time":0,"result":"Fail"},{"connections":1,"name":"34:FC:EF:11:B1:66","time":0,"result":"Fail"}]} G3s-1 android (12 left)

2016-01-08T14:58:52.631Z - info: Received results for {"name:":"Thali Test (Galaxy S5)","time":101533,"result":"TIMEOUT","sendList":[{"name":"F8:95:C7:87:3C:51","time":31423,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:B1:66","time":0,"result":"Fail"},{"connections":0,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"B4:CE:F6:AB:A4:6A","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:9D:93:0B","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"80:01:84:8A:B3:68","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"}]} Thali Test (Galaxy S5) android (11 left)

2016-01-08T14:58:52.652Z - info: Received results for {"name:":"A5-1","time":100236,"result":"TIMEOUT","sendList":[{"name":"7C:F9:0E:51:18:22","time":22046,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":23292,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"34:FC:EF:9D:93:0B","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:B1:66","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"B4:CE:F6:AB:A4:6A","time":0,"result":"Fail"},{"connections":0,"name":"80:01:84:8A:B3:68","time":0,"result":"Fail"},{"connections":0,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"}]} A5-1 android (10 left)

2016-01-08T14:58:52.692Z - info: Received results for {"name:":"S5-1","time":100379,"result":"TIMEOUT","sendList":[{"name":"B0:C5:59:3F:75:69","time":13968,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:9D:93:0B","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"80:01:84:8A:B3:68","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:B1:66","time":0,"result":"Fail"},{"connections":0,"name":"B4:CE:F6:AB:A4:6A","time":0,"result":"Fail"},{"connections":0,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":1,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"}]} S5-1 android (9 left)

2016-01-08T14:58:52.874Z - info: Received results for {"name:":"XT1072","time":100149,"result":"TIMEOUT","sendList":[{"name":"7C:F9:0E:37:96:AB","time":9633,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"34:FC:EF:11:B1:66","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"B4:CE:F6:AB:A4:6A","time":0,"result":"Fail"},{"connections":0,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:9D:93:0B","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"80:01:84:8A:B3:68","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":1,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"}]} XT1072 android (8 left)

2016-01-08T14:58:55.375Z - info: Received results for {"name:":"Thali Test (Galaxy A3)","time":100456,"result":"TIMEOUT","sendList":[{"name":"58:3F:54:73:64:C0","time":73621,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"34:FC:EF:9D:93:0B","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"B4:CE:F6:AB:A4:6A","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"80:01:84:8A:B3:68","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:B1:66","time":0,"result":"Fail"}]} Thali Test (Galaxy A3) android (7 left)

2016-01-08T14:58:57.504Z - info: Received results for {"name:":"Thali Test (Galaxy A5)","time":100252,"result":"TIMEOUT","sendList":[{"name":"7C:F9:0E:37:96:AB","time":16719,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":11686,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:9D:93:0B","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"80:01:84:8A:B3:68","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:B1:66","time":0,"result":"Fail"},{"connections":1,"name":"B4:CE:F6:AB:A4:6A","time":0,"result":"Fail"}]} Thali Test (Galaxy A5) android (6 left)

2016-01-08T14:59:10.836Z - info: server timeout for test: testSendData.js (android)

2016-01-08T14:59:10.839Z - info: All test data retrieved for testSendData.js (android)

2016-01-08T14:59:10.843Z - info: No results from Thali Test's G2

2016-01-08T14:59:10.845Z - info: No results from HTC Desire 820

2016-01-08T14:59:10.851Z - info: No results from Nexus 5

2016-01-08T14:59:10.855Z - info: No results from S5mini-1

2016-01-08T14:59:10.856Z - info: No results from HTC Desire 820

2016-01-08T14:59:10.857Z - info: No results from XT1039
2016-01-08T14:59:10.858Z - info: ALL DONE !!!

{ 'name:': 'Apple-Iphone5-1',
  time: 1587,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1.j1bF8Q==',
       peerAvailable: true,
       time: 1586 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 668,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1.j1bF8Q==',
       peerAvailable: true,
       time: 665 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 2198,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1.oJtw2A==',
       peerAvailable: true,
       time: 2196 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 1216,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1.xmg6Nw==',
       peerAvailable: true,
       time: 1214 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 58821,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.oJtw2A==',
       time: 41293,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.+bX+WA==',
       time: 9095,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.zHt1vQ==',
       time: 4346,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.bICwVA==',
       time: 3974,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 56910,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1.j1bF8Q==',
       time: 41721,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.+bX+WA==',
       time: 7478,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.ziR9IQ==',
       time: 3799,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.bICwVA==',
       time: 3705,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 58886,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.oJtw2A==',
       time: 41276,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.ziR9IQ==',
       time: 8834,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.bICwVA==',
       time: 4149,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.zHt1vQ==',
       time: 4463,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 56502,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1.j1bF8Q==',
       time: 40561,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.+bX+WA==',
       time: 6909,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.ziR9IQ==',
       time: 3779,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.zHt1vQ==',
       time: 4566,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Thali Test (Galaxy A5)',
  time: 100255,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: '<no peer name>',
       peerIdentifier: '44:80:EB:7B:5A:5',
       peerAvailable: true,
       time: 2595 },
     { peerName: '<no peer name>',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 4026 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:37:96:AB',
       peerAvailable: true,
       time: 4027 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:34:8A:A0',
       peerAvailable: true,
       time: 4030 },
     { peerName: '<no peer name>',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 4041 },
     { peerName: '<no peer name>',
       peerIdentifier: '8:EC:A9:50:76:27',
       peerAvailable: true,
       time: 4244 },
     { peerName: '<no peer name>',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 4251 },
     { peerName: '<no peer name>',
       peerIdentifier: '8:EC:A9:50:75:41',
       peerAvailable: true,
       time: 4382 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 82545 } ] }

{ 'name:': 'A3-1',
  time: 100224,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: '<no peer name>',
       peerIdentifier: '44:80:EB:7B:5A:5',
       peerAvailable: true,
       time: 2281 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:34:8A:A0',
       peerAvailable: true,
       time: 2637 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: false,
       time: 92289 },
     { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 4939 },
     { peerName: '<no peer name>',
       peerIdentifier: '8:EC:A9:50:76:27',
       peerAvailable: true,
       time: 5169 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 5461 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: false,
       time: 92286 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 5703 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:51:18:22',
       peerAvailable: true,
       time: 6474 },
     { peerName: '<no peer name>',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 6728 },
     { peerName: '<no peer name>',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 6992 },
     { peerName: '<no peer name>',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 7028 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:37:96:AB',
       peerAvailable: true,
       time: 12004 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 15968 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 16721 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 67812 } ] }

{ 'name:': 'Note4-1',
  time: 100289,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:34:8A:A0',
       peerAvailable: true,
       time: 312 },
     { peerName: '<no peer name>',
       peerIdentifier: '44:80:EB:7B:5A:5',
       peerAvailable: true,
       time: 314 },
     { peerName: '<no peer name>',
       peerIdentifier: '8:EC:A9:50:75:41',
       peerAvailable: true,
       time: 317 },
     { peerName: '<no peer name>',
       peerIdentifier: '8:EC:A9:50:76:27',
       peerAvailable: true,
       time: 492 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:37:96:AB',
       peerAvailable: true,
       time: 494 },
     { peerName: '<no peer name>',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 1028 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:51:18:22',
       peerAvailable: true,
       time: 1240 },
     { peerName: '<no peer name>',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 2888 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 6990 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 9130 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 15493 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 37181 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 37356 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 44774 } ] }

{ 'name:': 'G4-1',
  time: 91872,
  result: 'OK',
  peersList: 
   [ { peerName: '<no peer name>',
       peerIdentifier: '44:80:EB:7B:5A:5',
       peerAvailable: true,
       time: 361 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:34:8A:A0',
       peerAvailable: true,
       time: 400 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:37:96:AB',
       peerAvailable: true,
       time: 586 },
     { peerName: '<no peer name>',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 643 },
     { peerName: '<no peer name>',
       peerIdentifier: '8:EC:A9:50:76:27',
       peerAvailable: true,
       time: 827 },
     { peerName: '<no peer name>',
       peerIdentifier: '8:EC:A9:50:75:41',
       peerAvailable: true,
       time: 949 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:51:18:22',
       peerAvailable: true,
       time: 5511 },
     { peerName: '<no peer name>',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 7370 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 7639 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 21945 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 31274 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 36897 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 45078 },
     { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 45238 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 48579 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 91729 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 91871 } ] }

{ 'name:': 'G3s-1',
  time: 100144,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 2424 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 23951 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 28723 } ] }

{ 'name:': 'G3-1',
  time: 100085,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: false,
       time: 92197 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 8203 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 25012 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: false,
       time: 92201 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 25312 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 25394 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 33181 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 43761 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 97081 } ] }

{ 'name:': 'XT1072',
  time: 100245,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 2941 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 3159 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:37:96:AB',
       peerAvailable: false,
       time: 92974 },
     { peerName: '<no peer name>',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: false,
       time: 92970 },
     { peerName: '<no peer name>',
       peerIdentifier: '8:EC:A9:50:75:41',
       peerAvailable: false,
       time: 92965 },
     { peerName: '<no peer name>',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: false,
       time: 92960 },
     { peerName: '<no peer name>',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: false,
       time: 92946 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:34:8A:A0',
       peerAvailable: false,
       time: 92945 },
     { peerName: '<no peer name>',
       peerIdentifier: '8:EC:A9:50:76:27',
       peerAvailable: false,
       time: 92941 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:51:18:22',
       peerAvailable: true,
       time: 6738 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 44289 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 48279 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 48482 } ] }

{ 'name:': 'S5-1',
  time: 100237,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: '<no peer name>',
       peerIdentifier: '44:80:EB:7B:5A:5',
       peerAvailable: true,
       time: 499 },
     { peerName: '<no peer name>',
       peerIdentifier: '8:EC:A9:50:75:41',
       peerAvailable: true,
       time: 796 },
     { peerName: '<no peer name>',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 1234 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:51:18:22',
       peerAvailable: true,
       time: 1421 },
     { peerName: '<no peer name>',
       peerIdentifier: '8:EC:A9:50:76:27',
       peerAvailable: true,
       time: 1424 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:37:96:AB',
       peerAvailable: true,
       time: 1428 },
     { peerName: '<no peer name>',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 1702 },
     { peerName: '<no peer name>',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 3343 },
     { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 3880 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: false,
       time: 90525 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: false,
       time: 90545 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 30499 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 46108 } ] }

{ 'name:': 'Thali Test (Galaxy A3)',
  time: 100247,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:51:18:22',
       peerAvailable: true,
       time: 1265 },
     { peerName: '<no peer name>',
       peerIdentifier: '44:80:EB:7B:5A:5',
       peerAvailable: true,
       time: 1271 },
     { peerName: '<no peer name>',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 1343 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:34:8A:A0',
       peerAvailable: true,
       time: 1357 },
     { peerName: '<no peer name>',
       peerIdentifier: '8:EC:A9:50:75:41',
       peerAvailable: true,
       time: 1394 },
     { peerName: '<no peer name>',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 1555 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:37:96:AB',
       peerAvailable: true,
       time: 1557 },
     { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 4267 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: false,
       time: 91265 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 5352 },
     { peerName: '<no peer name>',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 14239 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 65985 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 67639 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 77760 } ] }

{ 'name:': 'Nexus 5',
  time: 100067,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 47029 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 59178 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 60187 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 62938 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 66038 } ] }

{ 'name:': 'A5-1',
  time: 100266,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: '<no peer name>',
       peerIdentifier: '44:80:EB:7B:5A:5',
       peerAvailable: true,
       time: 5630 },
     { peerName: '<no peer name>',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 5699 },
     { peerName: '<no peer name>',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 5752 },
     { peerName: '<no peer name>',
       peerIdentifier: '8:EC:A9:50:75:41',
       peerAvailable: true,
       time: 5837 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:51:18:22',
       peerAvailable: true,
       time: 5953 },
     { peerName: '<no peer name>',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 5959 },
     { peerName: '<no peer name>',
       peerIdentifier: '8:EC:A9:50:76:27',
       peerAvailable: true,
       time: 7537 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:34:8A:A0',
       peerAvailable: true,
       time: 16001 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 86282 } ] }

{ 'name:': 'Thali Test (Galaxy S5)',
  time: 100324,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:51:18:22',
       peerAvailable: true,
       time: 386 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:37:96:AB',
       peerAvailable: true,
       time: 416 },
     { peerName: '<no peer name>',
       peerIdentifier: '8:EC:A9:50:75:41',
       peerAvailable: true,
       time: 536 },
     { peerName: '<no peer name>',
       peerIdentifier: '44:80:EB:7B:5A:5',
       peerAvailable: true,
       time: 575 },
     { peerName: '<no peer name>',
       peerIdentifier: '8:EC:A9:50:76:27',
       peerAvailable: true,
       time: 737 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:34:8A:A0',
       peerAvailable: true,
       time: 1237 },
     { peerName: '<no peer name>',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 1740 },
     { peerName: '<no peer name>',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 5114 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 53638 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 62253 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 78164 } ] }

{ 'name:': 'Thali Test (Galaxy A5)',
  time: 100252,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '7C:F9:0E:37:96:AB',
       time: 16719,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:3C:51',
       time: 11686,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: '7C:F9:0E:34:8A:A0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'B0:C5:59:3F:75:69',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'E0:DB:10:14:E2:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:11:AE:67',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:75:41',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:9D:93:0B',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '00:F4:6F:30:E0:6C',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '58:3F:54:73:64:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F4:F1:E1:5C:3B:E2',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F8:95:C7:87:85:54',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:76:27',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '44:80:EB:7B:5A:05',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '80:01:84:8A:B3:68',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:11:B1:66',
       time: 0,
       result: 'Fail' },
     { connections: 1,
       name: 'B4:CE:F6:AB:A4:6A',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'A3-1',
  time: 100220,
  result: 'TIMEOUT',
  sendList: 
   [ { connections: 1,
       name: '34:FC:EF:11:AE:67',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:76:27',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:11:B1:66',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F8:95:C7:87:85:54',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:51:18:22',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '58:3F:54:73:64:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F4:F1:E1:5C:3B:E2',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'E0:DB:10:14:E2:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:9D:93:0B',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'B4:CE:F6:AB:A4:6A',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:34:8A:A0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '44:80:EB:7B:5A:05',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '80:01:84:8A:B3:68',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F8:95:C7:87:3C:51',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:37:96:AB',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'B0:C5:59:3F:75:69',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '00:F4:6F:30:E0:6C',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Note4-1',
  time: 100246,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '58:3F:54:73:64:C0',
       time: 18534,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: '34:FC:EF:11:AE:67',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:37:96:AB',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'B4:CE:F6:AB:A4:6A',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F8:95:C7:87:3C:51',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:51:18:22',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:76:27',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F8:95:C7:87:85:54',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F4:F1:E1:5C:3B:E2',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:75:41',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '44:80:EB:7B:5A:05',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:34:8A:A0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:9D:93:0B',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '00:F4:6F:30:E0:6C',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'B0:C5:59:3F:75:69',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:11:B1:66',
       time: 0,
       result: 'Fail' },
     { connections: 1,
       name: '80:01:84:8A:B3:68',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'G4-1',
  time: 100191,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '08:EC:A9:50:75:41',
       time: 9185,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'E0:DB:10:14:E2:C0',
       time: 14662,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: '08:EC:A9:50:76:27',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'B0:C5:59:3F:75:69',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:9D:93:0B',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:11:B1:66',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F8:95:C7:87:85:54',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:37:96:AB',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'B4:CE:F6:AB:A4:6A',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '44:80:EB:7B:5A:05',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:51:18:22',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '58:3F:54:73:64:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '00:F4:6F:30:E0:6C',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:11:AE:67',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '80:01:84:8A:B3:68',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:34:8A:A0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F4:F1:E1:5C:3B:E2',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'G3s-1',
  time: 100137,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'B0:C5:59:3F:75:69',
       time: 9694,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: '34:FC:EF:11:AE:67',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '58:3F:54:73:64:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:37:96:AB',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'E0:DB:10:14:E2:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:76:27',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:34:8A:A0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:9D:93:0B',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:51:18:22',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '00:F4:6F:30:E0:6C',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F8:95:C7:87:3C:51',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '80:01:84:8A:B3:68',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:75:41',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '44:80:EB:7B:5A:05',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F4:F1:E1:5C:3B:E2',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'B4:CE:F6:AB:A4:6A',
       time: 0,
       result: 'Fail' },
     { connections: 1,
       name: '34:FC:EF:11:B1:66',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'G3-1',
  time: 100106,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '34:FC:EF:11:AE:67',
       time: 46252,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:3C:51',
       time: 26741,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:37:96:AB',
       time: 24500,
       result: 'OK',
       connections: 2,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: '34:FC:EF:11:B1:66',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:75:41',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'B4:CE:F6:AB:A4:6A',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:34:8A:A0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '44:80:EB:7B:5A:05',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F4:F1:E1:5C:3B:E2',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '00:F4:6F:30:E0:6C',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:9D:93:0B',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F8:95:C7:87:85:54',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '80:01:84:8A:B3:68',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:76:27',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'E0:DB:10:14:E2:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:51:18:22',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'B0:C5:59:3F:75:69',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'XT1072',
  time: 100149,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '7C:F9:0E:37:96:AB',
       time: 9633,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: '34:FC:EF:11:B1:66',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F8:95:C7:87:3C:51',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:75:41',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '58:3F:54:73:64:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:76:27',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'B0:C5:59:3F:75:69',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'B4:CE:F6:AB:A4:6A',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F4:F1:E1:5C:3B:E2',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F8:95:C7:87:85:54',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:9D:93:0B',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:51:18:22',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'E0:DB:10:14:E2:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:34:8A:A0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '80:01:84:8A:B3:68',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:11:AE:67',
       time: 0,
       result: 'Fail' },
     { connections: 1,
       name: '00:F4:6F:30:E0:6C',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'S5-1',
  time: 100379,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'B0:C5:59:3F:75:69',
       time: 13968,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: '08:EC:A9:50:76:27',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F8:95:C7:87:3C:51',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'E0:DB:10:14:E2:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:75:41',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:9D:93:0B',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:37:96:AB',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '80:01:84:8A:B3:68',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F8:95:C7:87:85:54',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '58:3F:54:73:64:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:51:18:22',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '44:80:EB:7B:5A:05',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:11:B1:66',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'B4:CE:F6:AB:A4:6A',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F4:F1:E1:5C:3B:E2',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:11:AE:67',
       time: 0,
       result: 'Fail' },
     { connections: 1,
       name: '00:F4:6F:30:E0:6C',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Thali Test (Galaxy A3)',
  time: 100456,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '58:3F:54:73:64:C0',
       time: 73621,
       result: 'OK',
       connections: 2,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: '34:FC:EF:9D:93:0B',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:75:41',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F8:95:C7:87:85:54',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:37:96:AB',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '44:80:EB:7B:5A:05',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:11:AE:67',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:34:8A:A0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F8:95:C7:87:3C:51',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '00:F4:6F:30:E0:6C',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F4:F1:E1:5C:3B:E2',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'E0:DB:10:14:E2:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'B4:CE:F6:AB:A4:6A',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:51:18:22',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'B0:C5:59:3F:75:69',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '80:01:84:8A:B3:68',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:11:B1:66',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Nexus 5',
  time: 100053,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '7C:F9:0E:37:96:AB',
       time: 8766,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: '08:EC:A9:50:75:41',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:34:8A:A0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:76:27',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F8:95:C7:87:85:54',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F4:F1:E1:5C:3B:E2',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:11:B1:66',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:51:18:22',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '44:80:EB:7B:5A:05',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'B4:CE:F6:AB:A4:6A',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '00:F4:6F:30:E0:6C',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '80:01:84:8A:B3:68',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'B0:C5:59:3F:75:69',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F8:95:C7:87:3C:51',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '58:3F:54:73:64:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'E0:DB:10:14:E2:C0',
       time: 0,
       result: 'Fail' },
     { connections: 1,
       name: '34:FC:EF:9D:93:0B',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'A5-1',
  time: 100236,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '7C:F9:0E:51:18:22',
       time: 22046,
       result: 'OK',
       connections: 2,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'B0:C5:59:3F:75:69',
       time: 23292,
       result: 'OK',
       connections: 2,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: '34:FC:EF:9D:93:0B',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '44:80:EB:7B:5A:05',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '00:F4:6F:30:E0:6C',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:11:B1:66',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:75:41',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:34:8A:A0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F8:95:C7:87:3C:51',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F8:95:C7:87:85:54',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'B4:CE:F6:AB:A4:6A',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '80:01:84:8A:B3:68',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F4:F1:E1:5C:3B:E2',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'E0:DB:10:14:E2:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '58:3F:54:73:64:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:76:27',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:11:AE:67',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Thali Test (Galaxy S5)',
  time: 101533,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'F8:95:C7:87:3C:51',
       time: 31423,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: '00:F4:6F:30:E0:6C',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F8:95:C7:87:85:54',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:51:18:22',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:11:B1:66',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F4:F1:E1:5C:3B:E2',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'E0:DB:10:14:E2:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '44:80:EB:7B:5A:05',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'B4:CE:F6:AB:A4:6A',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:11:AE:67',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:9D:93:0B',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '58:3F:54:73:64:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:34:8A:A0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:75:41',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:37:96:AB',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '80:01:84:8A:B3:68',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:76:27',
       time: 0,
       result: 'Fail' } ] }

--------------- test report ---------------------
--------------- Apple-Iphone5-1 --------------------- : 1
Find peers : 100% : 1586 ms, 99% : 1586 ms, 95 : 1586 ms, 90% : 1586 ms.

Result count 1, range 1586 ms to  1586 ms.
Send data : 100% : 9095 ms, 99% : 9095 ms, 95 : 9095 ms, 90% : 9095 ms.

Average data rate: 0.017 MB/s
Result count 3, range 3974 ms to  9095 ms.
Send data failed peers count : 1 [25 %]

- Peer ID : Apple-Iphone5-1.oJtw2A==, Tried : 5
Send data never tried peers count : 0 [0 %]
--------------- Apple-Iphone5s-1 --------------------- : 2

Find peers : 100% : 665 ms, 99% : 665 ms, 95 : 665 ms, 90% : 665 ms.
Result count 1, range 665 ms to  665 ms.
Send data : 100% : 7478 ms, 99% : 7478 ms, 95 : 7478 ms, 90% : 7478 ms.
Average data rate: 0.02 MB/s
Result count 3, range 3705 ms to  7478 ms.
Send data failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone6-1.j1bF8Q==, Tried : 5
Send data never tried peers count : 0 [0 %]
--------------- Apple-IpadAir2-1 --------------------- : 3
Find peers : 100% : 2196 ms, 99% : 2196 ms, 95 : 2196 ms, 90% : 2196 ms.
Result count 1, range 2196 ms to  2196 ms.
Send data : 100% : 8834 ms, 99% : 8834 ms, 95 : 8834 ms, 90% : 8834 ms.
Average data rate: 0.017 MB/s
Result count 3, range 4149 ms to  8834 ms.
Send data failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone5-1.oJtw2A==, Tried : 5
Send data never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1 --------------------- : 4
Find peers : 100% : 1214 ms, 99% : 1214 ms, 95 : 1214 ms, 90% : 1214 ms.
Result count 1, range 1214 ms to  1214 ms.
Send data : 100% : 6909 ms, 99% : 6909 ms, 95 : 6909 ms, 90% : 6909 ms.
Average data rate: 0.02 MB/s
Result count 3, range 3779 ms to  6909 ms.

Send data failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone6-1.j1bF8Q==, Tried : 5
Send data never tried peers count : 0 [0 %]
--------------- Thali Test (Galaxy A5) --------------------- : 5

Find peers : 100% : 82545 ms, 99% : 82545 ms, 95 : 82545 ms, 90% : 4382 ms.
Result count 9, range 2595 ms to  82545 ms.

Send data : 100% : 16719 ms, 99% : 16719 ms, 95 : 16719 ms, 90% : 16719 ms.
Average data rate: 0.007 MB/s

Result count 2, range 11686 ms to  16719 ms.
Send data failed peers count : 2 [50 %]
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1

- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
Send data never tried peers count : 13 [76.47058823529412 %]

- Peer ID : B0:C5:59:3F:75:69
- Peer ID : E0:DB:10:14:E2:C0

- Peer ID : 34:FC:EF:11:AE:67

- Peer ID : 08:EC:A9:50:75:41
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : F4:F1:E1:5C:3B:E2

- Peer ID : F8:95:C7:87:85:54
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 80:01:84:8A:B3:68

- Peer ID : 34:FC:EF:11:B1:66
--------------- A3-1 --------------------- : 6
Find peers : 100% : 92289 ms, 99% : 92289 ms, 95 : 92286 ms, 90% : 67812 ms.
Result count 16, range 2281 ms to  92289 ms.
No send data results!
--------------- Note4-1 --------------------- : 7
Find peers : 100% : 44774 ms, 99% : 44774 ms, 95 : 37356 ms, 90% : 37356 ms.

Result count 14, range 312 ms to  44774 ms.
Send data : 100% : 18534 ms, 99% : 18534 ms, 95 : 18534 ms, 90% : 18534 ms.
Average data rate: 0.005 MB/s
Result count 1, range 18534 ms to  18534 ms.

Send data failed peers count : 2 [66.66666666666667 %]
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1

Send data never tried peers count : 14 [82.3529411764706 %]
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 7C:F9:0E:51:18:22

- Peer ID : 08:EC:A9:50:76:27
- Peer ID : F8:95:C7:87:85:54
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 08:EC:A9:50:75:41

- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : 00:F4:6F:30:E0:6C

- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 34:FC:EF:11:B1:66
--------------- G4-1 --------------------- : 8

Find peers : 100% : 91871 ms, 99% : 91871 ms, 95 : 91729 ms, 90% : 48579 ms.
Result count 17, range 361 ms to  91871 ms.
Send data : 100% : 14662 ms, 99% : 14662 ms, 95 : 14662 ms, 90% : 14662 ms.

Average data rate: 0.008 MB/s
Result count 2, range 9185 ms to  14662 ms.
Send data failed peers count : 1 [33.333333333333336 %]
- Peer ID : 08:EC:A9:50:76:27, Tried : 1

Send data never tried peers count : 14 [82.3529411764706 %]
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : 34:FC:EF:11:B1:66

- Peer ID : F8:95:C7:87:85:54
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 7C:F9:0E:51:18:22

- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 80:01:84:8A:B3:68

- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : F4:F1:E1:5C:3B:E2
--------------- G3s-1 --------------------- : 9

Find peers : 100% : 28723 ms, 99% : 28723 ms, 95 : 28723 ms, 90% : 28723 ms.
Result count 3, range 2424 ms to  28723 ms.
Send data : 100% : 9694 ms, 99% : 9694 ms, 95 : 9694 ms, 90% : 9694 ms.
Average data rate: 0.01 MB/s

Result count 1, range 9694 ms to  9694 ms.
Send data failed peers count : 2 [66.66666666666667 %]
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1

Send data never tried peers count : 14 [82.3529411764706 %]
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 7C:F9:0E:37:96:AB

- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 34:FC:EF:9D:93:0B

- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 08:EC:A9:50:75:41

- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : B4:CE:F6:AB:A4:6A

--------------- G3-1 --------------------- : 10
Find peers : 100% : 97081 ms, 99% : 97081 ms, 95 : 97081 ms, 90% : 92201 ms.
Result count 9, range 8203 ms to  97081 ms.

Send data : 100% : 46252 ms, 99% : 46252 ms, 95 : 46252 ms, 90% : 46252 ms.
Average data rate: 0.003 MB/s
Result count 3, range 24500 ms to  46252 ms.

Send data failed peers count : 1 [25 %]
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
Send data never tried peers count : 13 [76.47058823529412 %]
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : B4:CE:F6:AB:A4:6A

- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 00:F4:6F:30:E0:6C

- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : F8:95:C7:87:85:54
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 08:EC:A9:50:76:27

- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : B0:C5:59:3F:75:69
--------------- XT1072 --------------------- : 11

Find peers : 100% : 92974 ms, 99% : 92974 ms, 95 : 92970 ms, 90% : 92970 ms.
Result count 13, range 2941 ms to  92974 ms.
Send data : 100% : 9633 ms, 99% : 9633 ms, 95 : 9633 ms, 90% : 9633 ms.

Average data rate: 0.01 MB/s
Result count 1, range 9633 ms to  9633 ms.
Send data failed peers count : 2 [66.66666666666667 %]

- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
Send data never tried peers count : 14 [82.3529411764706 %]

- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 08:EC:A9:50:76:27

- Peer ID : B0:C5:59:3F:75:69
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : F8:95:C7:87:85:54

- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 7C:F9:0E:34:8A:A0

- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 34:FC:EF:11:AE:67
--------------- S5-1 --------------------- : 12

Find peers : 100% : 90545 ms, 99% : 90545 ms, 95 : 90525 ms, 90% : 90525 ms.
Result count 13, range 499 ms to  90545 ms.
Send data : 100% : 13968 ms, 99% : 13968 ms, 95 : 13968 ms, 90% : 13968 ms.

Average data rate: 0.007 MB/s
Result count 1, range 13968 ms to  13968 ms.
Send data failed peers count : 2 [66.66666666666667 %]

- Peer ID : 08:EC:A9:50:76:27, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
Send data never tried peers count : 14 [82.3529411764706 %]

- Peer ID : F8:95:C7:87:3C:51
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : 7C:F9:0E:37:96:AB

- Peer ID : 80:01:84:8A:B3:68
- Peer ID : F8:95:C7:87:85:54
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 7C:F9:0E:51:18:22

- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : F4:F1:E1:5C:3B:E2

- Peer ID : 34:FC:EF:11:AE:67
--------------- Thali Test (Galaxy A3) --------------------- : 13
Find peers : 100% : 91265 ms, 99% : 91265 ms, 95 : 77760 ms, 90% : 77760 ms.

Result count 14, range 1265 ms to  91265 ms.
Send data : 100% : 73621 ms, 99% : 73621 ms, 95 : 73621 ms, 90% : 73621 ms.
Average data rate: 0.001 MB/s

Result count 1, range 73621 ms to  73621 ms.
Send data failed peers count : 1 [50 %]
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
Send data never tried peers count : 15 [88.23529411764706 %]

- Peer ID : 08:EC:A9:50:75:41
- Peer ID : F8:95:C7:87:85:54
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 44:80:EB:7B:5A:05

- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 00:F4:6F:30:E0:6C

- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : B0:C5:59:3F:75:69

- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 34:FC:EF:11:B1:66
--------------- Nexus 5 --------------------- : 14
Find peers : 100% : 66038 ms, 99% : 66038 ms, 95 : 66038 ms, 90% : 66038 ms.
Result count 5, range 47029 ms to  66038 ms.
Send data : 100% : 8766 ms, 99% : 8766 ms, 95 : 8766 ms, 90% : 8766 ms.
Average data rate: 0.011 MB/s
Result count 1, range 8766 ms to  8766 ms.
Send data failed peers count : 2 [66.66666666666667 %]
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
Send data never tried peers count : 14 [82.3529411764706 %]
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : F8:95:C7:87:85:54

- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : B4:CE:F6:AB:A4:6A

- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : F8:95:C7:87:3C:51

- Peer ID : 58:3F:54:73:64:C0
- Peer ID : E0:DB:10:14:E2:C0
--------------- A5-1 --------------------- : 15
Find peers : 100% : 86282 ms, 99% : 86282 ms, 95 : 86282 ms, 90% : 16001 ms.

Result count 9, range 5630 ms to  86282 ms.
Send data : 100% : 23292 ms, 99% : 23292 ms, 95 : 23292 ms, 90% : 23292 ms.
Average data rate: 0.004 MB/s

Result count 2, range 22046 ms to  23292 ms.
Send data failed peers count : 1 [33.333333333333336 %]
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
Send data never tried peers count : 14 [82.3529411764706 %]

- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : 08:EC:A9:50:75:41

- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : F8:95:C7:87:85:54
- Peer ID : B4:CE:F6:AB:A4:6A

- Peer ID : 80:01:84:8A:B3:68
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 58:3F:54:73:64:C0

- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 34:FC:EF:11:AE:67
--------------- Thali Test (Galaxy S5) --------------------- : 16
Find peers : 100% : 78164 ms, 99% : 78164 ms, 95 : 62253 ms, 90% : 62253 ms.

Result count 11, range 386 ms to  78164 ms.
Send data : 100% : 31423 ms, 99% : 31423 ms, 95 : 31423 ms, 90% : 31423 ms.
Average data rate: 0.003 MB/s

Result count 1, range 31423 ms to  31423 ms.
Send data failed peers count : 1 [50 %]
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
Send data never tried peers count : 15 [88.23529411764706 %]

- Peer ID : F8:95:C7:87:85:54
- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : F4:F1:E1:5C:3B:E2

- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 34:FC:EF:11:AE:67

- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 80:01:84:8A:B3:68

- Peer ID : 08:EC:A9:50:76:27

--------------- Combined ---------------------

Find peers : 100% : 97081 ms, 99% : 92974 ms, 95 : 92941 ms, 90% : 91265 ms.

Send data : 100% : 73621 ms, 99% : 73621 ms, 95 : 46252 ms, 90% : 26741 ms.
Average data rate: 0.007 MB/s

--------------- end of test report ---------------------

2016-01-08T14:59:11.480Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1.j1bF8Q==, peerAvailable=true, time=1586], sendList=[name=Apple-Iphone6-1.bICwVA==, time=3974, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5s-1.zHt1vQ==, time=4346, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.+bX+WA==, time=9095, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone5-1.oJtw2A==, time=41293, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1.j1bF8Q==, peerAvailable=true, time=665], sendList=[name=Apple-Iphone6-1.bICwVA==, time=3705, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1.ziR9IQ==, time=3799, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.+bX+WA==, time=7478, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone6-1.j1bF8Q==, time=41721, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1.oJtw2A==, peerAvailable=true, time=2196], sendList=[name=Apple-Iphone6-1.bICwVA==, time=4149, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5s-1.zHt1vQ==, time=4463, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1.ziR9IQ==, time=8834, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone5-1.oJtw2A==, time=41276, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1.xmg6Nw==, peerAvailable=true, time=1214], sendList=[name=Apple-Iphone5-1.ziR9IQ==, time=3779, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5s-1.zHt1vQ==, time=4566, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.+bX+WA==, time=6909, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone6-1.j1bF8Q==, time=40561, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=<no peer name>, peerIdentifier=44:80:EB:7B:5A:5, peerAvailable=true, time=2595, peerName=<no peer name>, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=4026, peerName=<no peer name>, peerIdentifier=7C:F9:E:37:96:AB, peerAvailable=true, time=4027, peerName=<no peer name>, peerIdentifier=7C:F9:E:34:8A:A0, peerAvailable=true, time=4030, peerName=<no peer name>, peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=4041, peerName=<no peer name>, peerIdentifier=8:EC:A9:50:76:27, peerAvailable=true, time=4244, peerName=<no peer name>, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=4251, peerName=<no peer name>, peerIdentifier=8:EC:A9:50:75:41, peerAvailable=true, time=4382, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=82545], sendList=[name=F8:95:C7:87:3C:51, time=11686, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:37:96:AB, time=16719, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=1, name=B4:CE:F6:AB:A4:6A, time=0, result=Fail], notTriedList=[connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=34:FC:EF:9D:93:0B, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=80:01:84:8A:B3:68, time=0, result=Fail, connections=0, name=34:FC:EF:11:B1:66, time=0, result=Fail], peersList=[peerName=<no peer name>, peerIdentifier=44:80:EB:7B:5A:5, peerAvailable=true, time=2281, peerName=<no peer name>, peerIdentifier=7C:F9:E:34:8A:A0, peerAvailable=true, time=2637, peerName=Nexus 5, peerIdentifier=34:FC:EF:11:AE:67, peerAvailable=true, time=4939, peerName=<no peer name>, peerIdentifier=8:EC:A9:50:76:27, peerAvailable=true, time=5169, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=5461, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=5703, peerName=<no peer name>, peerIdentifier=7C:F9:E:51:18:22, peerAvailable=true, time=6474, peerName=<no peer name>, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=6728, peerName=<no peer name>, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=6992, peerName=<no peer name>, peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=7028, peerName=<no peer name>, peerIdentifier=7C:F9:E:37:96:AB, peerAvailable=true, time=12004, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=15968, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=16721, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=67812, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=false, time=92286, peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=false, time=92289], sendList=[], failedPeer=[connections=1, name=34:FC:EF:11:AE:67, time=0, result=Fail], notTriedList=[connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=34:FC:EF:11:B1:66, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=34:FC:EF:9D:93:0B, time=0, result=Fail, connections=0, name=B4:CE:F6:AB:A4:6A, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=80:01:84:8A:B3:68, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail], peersList=[peerName=<no peer name>, peerIdentifier=7C:F9:E:34:8A:A0, peerAvailable=true, time=312, peerName=<no peer name>, peerIdentifier=44:80:EB:7B:5A:5, peerAvailable=true, time=314, peerName=<no peer name>, peerIdentifier=8:EC:A9:50:75:41, peerAvailable=true, time=317, peerName=<no peer name>, peerIdentifier=8:EC:A9:50:76:27, peerAvailable=true, time=492, peerName=<no peer name>, peerIdentifier=7C:F9:E:37:96:AB, peerAvailable=true, time=494, peerName=<no peer name>, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=1028, peerName=<no peer name>, peerIdentifier=7C:F9:E:51:18:22, peerAvailable=true, time=1240, peerName=<no peer name>, peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=2888, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=6990, peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=9130, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=15493, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=37181, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=37356, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=44774], sendList=[name=58:3F:54:73:64:C0, time=18534, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=1, name=80:01:84:8A:B3:68, time=0, result=Fail], notTriedList=[connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=B4:CE:F6:AB:A4:6A, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=34:FC:EF:9D:93:0B, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=34:FC:EF:11:B1:66, time=0, result=Fail], peersList=[peerName=<no peer name>, peerIdentifier=44:80:EB:7B:5A:5, peerAvailable=true, time=361, peerName=<no peer name>, peerIdentifier=7C:F9:E:34:8A:A0, peerAvailable=true, time=400, peerName=<no peer name>, peerIdentifier=7C:F9:E:37:96:AB, peerAvailable=true, time=586, peerName=<no peer name>, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=643, peerName=<no peer name>, peerIdentifier=8:EC:A9:50:76:27, peerAvailable=true, time=827, peerName=<no peer name>, peerIdentifier=8:EC:A9:50:75:41, peerAvailable=true, time=949, peerName=<no peer name>, peerIdentifier=7C:F9:E:51:18:22, peerAvailable=true, time=5511, peerName=<no peer name>, peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=7370, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=7639, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=21945, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=31274, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=36897, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=45078, peerName=Nexus 5, peerIdentifier=34:FC:EF:11:AE:67, peerAvailable=true, time=45238, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=48579, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=91729, peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=91871], sendList=[name=08:EC:A9:50:75:41, time=9185, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=E0:DB:10:14:E2:C0, time=14662, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=08:EC:A9:50:76:27, time=0, result=Fail], notTriedList=[connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=34:FC:EF:9D:93:0B, time=0, result=Fail, connections=0, name=34:FC:EF:11:B1:66, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=B4:CE:F6:AB:A4:6A, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=80:01:84:8A:B3:68, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail], peersList=[peerName=Nexus 5, peerIdentifier=34:FC:EF:11:AE:67, peerAvailable=true, time=2424, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=23951, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=28723], sendList=[name=B0:C5:59:3F:75:69, time=9694, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=1, name=34:FC:EF:11:B1:66, time=0, result=Fail], notTriedList=[connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=34:FC:EF:9D:93:0B, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=80:01:84:8A:B3:68, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail, connections=0, name=B4:CE:F6:AB:A4:6A, time=0, result=Fail], peersList=[peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=8203, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=25012, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=25312, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=25394, peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=33181, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=43761, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=false, time=92197, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=false, time=92201, peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=97081], sendList=[name=7C:F9:0E:37:96:AB, time=24500, result=OK, connections=2, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=F8:95:C7:87:3C:51, time=26741, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=34:FC:EF:11:AE:67, time=46252, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=34:FC:EF:11:B1:66, time=0, result=Fail], notTriedList=[connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=B4:CE:F6:AB:A4:6A, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=34:FC:EF:9D:93:0B, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=80:01:84:8A:B3:68, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail], peersList=[peerName=Nexus 5, peerIdentifier=34:FC:EF:11:AE:67, peerAvailable=true, time=2941, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=3159, peerName=<no peer name>, peerIdentifier=7C:F9:E:51:18:22, peerAvailable=true, time=6738, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=44289, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=48279, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=48482, peerName=<no peer name>, peerIdentifier=8:EC:A9:50:76:27, peerAvailable=false, time=92941, peerName=<no peer name>, peerIdentifier=7C:F9:E:34:8A:A0, peerAvailable=false, time=92945, peerName=<no peer name>, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=false, time=92946, peerName=<no peer name>, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=false, time=92960, peerName=<no peer name>, peerIdentifier=8:EC:A9:50:75:41, peerAvailable=false, time=92965, peerName=<no peer name>, peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=false, time=92970, peerName=<no peer name>, peerIdentifier=7C:F9:E:37:96:AB, peerAvailable=false, time=92974], sendList=[name=7C:F9:0E:37:96:AB, time=9633, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=34:FC:EF:11:B1:66, time=0, result=Fail, connections=1, name=00:F4:6F:30:E0:6C, time=0, result=Fail], notTriedList=[connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=B4:CE:F6:AB:A4:6A, time=0, result=Fail, connections=0, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=34:FC:EF:9D:93:0B, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=80:01:84:8A:B3:68, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail], peersList=[peerName=<no peer name>, peerIdentifier=44:80:EB:7B:5A:5, peerAvailable=true, time=499, peerName=<no peer name>, peerIdentifier=8:EC:A9:50:75:41, peerAvailable=true, time=796, peerName=<no peer name>, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=1234, peerName=<no peer name>, peerIdentifier=7C:F9:E:51:18:22, peerAvailable=true, time=1421, peerName=<no peer name>, peerIdentifier=8:EC:A9:50:76:27, peerAvailable=true, time=1424, peerName=<no peer name>, peerIdentifier=7C:F9:E:37:96:AB, peerAvailable=true, time=1428, peerName=<no peer name>, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=1702, peerName=<no peer name>, peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=3343, peerName=Nexus 5, peerIdentifier=34:FC:EF:11:AE:67, peerAvailable=true, time=3880, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=30499, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=46108, peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=false, time=90525, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=false, time=90545], sendList=[name=B0:C5:59:3F:75:69, time=13968, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=1, name=00:F4:6F:30:E0:6C, time=0, result=Fail], notTriedList=[connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=34:FC:EF:9D:93:0B, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=80:01:84:8A:B3:68, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=34:FC:EF:11:B1:66, time=0, result=Fail, connections=0, name=B4:CE:F6:AB:A4:6A, time=0, result=Fail, connections=0, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail], peersList=[peerName=<no peer name>, peerIdentifier=7C:F9:E:51:18:22, peerAvailable=true, time=1265, peerName=<no peer name>, peerIdentifier=44:80:EB:7B:5A:5, peerAvailable=true, time=1271, peerName=<no peer name>, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=1343, peerName=<no peer name>, peerIdentifier=7C:F9:E:34:8A:A0, peerAvailable=true, time=1357, peerName=<no peer name>, peerIdentifier=8:EC:A9:50:75:41, peerAvailable=true, time=1394, peerName=<no peer name>, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=1555, peerName=<no peer name>, peerIdentifier=7C:F9:E:37:96:AB, peerAvailable=true, time=1557, peerName=Nexus 5, peerIdentifier=34:FC:EF:11:AE:67, peerAvailable=true, time=4267, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=5352, peerName=<no peer name>, peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=14239, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=65985, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=67639, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=77760, peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=false, time=91265], sendList=[name=58:3F:54:73:64:C0, time=73621, result=OK, connections=2, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=34:FC:EF:9D:93:0B, time=0, result=Fail], notTriedList=[connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=B4:CE:F6:AB:A4:6A, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=80:01:84:8A:B3:68, time=0, result=Fail, connections=0, name=34:FC:EF:11:B1:66, time=0, result=Fail], peersList=[peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=47029, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=59178, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=60187, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=62938, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=66038], sendList=[name=7C:F9:0E:37:96:AB, time=8766, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=1, name=34:FC:EF:9D:93:0B, time=0, result=Fail], notTriedList=[connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail, connections=0, name=34:FC:EF:11:B1:66, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=B4:CE:F6:AB:A4:6A, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=80:01:84:8A:B3:68, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail], peersList=[peerName=<no peer name>, peerIdentifier=44:80:EB:7B:5A:5, peerAvailable=true, time=5630, peerName=<no peer name>, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=5699, peerName=<no peer name>, peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=5752, peerName=<no peer name>, peerIdentifier=8:EC:A9:50:75:41, peerAvailable=true, time=5837, peerName=<no peer name>, peerIdentifier=7C:F9:E:51:18:22, peerAvailable=true, time=5953, peerName=<no peer name>, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=5959, peerName=<no peer name>, peerIdentifier=8:EC:A9:50:76:27, peerAvailable=true, time=7537, peerName=<no peer name>, peerIdentifier=7C:F9:E:34:8A:A0, peerAvailable=true, time=16001, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=86282], sendList=[name=7C:F9:0E:51:18:22, time=22046, result=OK, connections=2, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=B0:C5:59:3F:75:69, time=23292, result=OK, connections=2, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=34:FC:EF:9D:93:0B, time=0, result=Fail], notTriedList=[connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=34:FC:EF:11:B1:66, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=B4:CE:F6:AB:A4:6A, time=0, result=Fail, connections=0, name=80:01:84:8A:B3:68, time=0, result=Fail, connections=0, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail], peersList=[peerName=<no peer name>, peerIdentifier=7C:F9:E:51:18:22, peerAvailable=true, time=386, peerName=<no peer name>, peerIdentifier=7C:F9:E:37:96:AB, peerAvailable=true, time=416, peerName=<no peer name>, peerIdentifier=8:EC:A9:50:75:41, peerAvailable=true, time=536, peerName=<no peer name>, peerIdentifier=44:80:EB:7B:5A:5, peerAvailable=true, time=575, peerName=<no peer name>, peerIdentifier=8:EC:A9:50:76:27, peerAvailable=true, time=737, peerName=<no peer name>, peerIdentifier=7C:F9:E:34:8A:A0, peerAvailable=true, time=1237, peerName=<no peer name>, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=1740, peerName=<no peer name>, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=5114, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=53638, peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=62253, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=78164], sendList=[name=F8:95:C7:87:3C:51, time=31423, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=00:F4:6F:30:E0:6C, time=0, result=Fail], notTriedList=[connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=34:FC:EF:11:B1:66, time=0, result=Fail, connections=0, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=B4:CE:F6:AB:A4:6A, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=34:FC:EF:9D:93:0B, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=80:01:84:8A:B3:68, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail]

2016-01-08T14:59:11.552Z - debug: end to Thali Test (Galaxy A5)

2016-01-08T14:59:11.557Z - debug: end to A3-1

2016-01-08T14:59:11.559Z - debug: end to Thali Test's G2

2016-01-08T14:59:11.560Z - debug: end to Note4-1

2016-01-08T14:59:11.561Z - debug: end to HTC Desire 820

2016-01-08T14:59:11.563Z - debug: end to G4-1

2016-01-08T14:59:11.564Z - debug: end to G3s-1

2016-01-08T14:59:11.565Z - debug: end to G3-1

2016-01-08T14:59:11.568Z - debug: end to XT1072

2016-01-08T14:59:11.569Z - debug: end to S5-1

2016-01-08T14:59:11.571Z - debug: end to Nexus 5

2016-01-08T14:59:11.572Z - debug: end to Thali Test (Galaxy A3)

2016-01-08T14:59:11.573Z - debug: end to Nexus 5

2016-01-08T14:59:11.574Z - debug: end to A5-1

2016-01-08T14:59:11.575Z - debug: end to Thali Test (Galaxy S5)

2016-01-08T14:59:11.576Z - debug: end to S5mini-1

2016-01-08T14:59:11.577Z - debug: end to HTC Desire 820

2016-01-08T14:59:11.578Z - debug: end to XT1039

2016-01-08T14:59:12.221Z - debug: Socket disconnected: transport close 14 (Thali Test (Galaxy A3))

2016-01-08T14:59:12.268Z - debug: Socket disconnected: transport close 15 (Nexus 5)

2016-01-08T14:59:12.319Z - debug: Socket disconnected: transport close 3 (A3-1)

2016-01-08T14:59:12.325Z - debug: Socket disconnected: transport close 1 (Thali Test (Galaxy A5))

2016-01-08T14:59:12.433Z - debug: Socket disconnected: transport close 11 (XT1072)

2016-01-08T14:59:12.696Z - debug: Socket disconnected: transport close 18 (Thali Test (Galaxy S5))

2016-01-08T14:59:12.875Z - debug: Socket disconnected: transport close 16 (A5-1)

2016-01-08T14:59:13.487Z - debug: Socket disconnected: transport close 10 (G3-1)

2016-01-08T14:59:14.212Z - debug: Socket disconnected: transport close 8 (G3s-1)

2016-01-08T14:59:14.586Z - debug: Socket disconnected: transport close 12 (S5-1)

2016-01-08T14:59:15.204Z - debug: Socket disconnected: transport close 5 (Note4-1)

2016-01-08T14:59:15.652Z - debug: Socket disconnected: transport close 7 (G4-1)


 
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
STOP log received from  f56ad48d Test has  SUCCEEDED
Device test finished on f56ad48d 
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Android task is completed. [SUCCESS]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/5546736337bcedb_Story_001_tompaana_406_tompaana/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/5546736337bcedb_Story_001_tompaana_406_tompaana/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/5546736337bcedb_Story_001_tompaana_406_tompaana/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/5546736337bcedb_Story_001_tompaana_406_tompaana/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device TA4750HV7I app:com.test.thalitest code:0 
child process exited with code 0 on device TA4750HV7I 
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:null 
child process exited with code null on device 320414cd475f91e3 
Android task is completed. [FAILED]
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/5546736337bcedb_Story_001_tompaana_406_tompaana/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/5546736337bcedb_Story_001_tompaana_406_tompaana/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/5546736337bcedb_Story_001_tompaana_406_tompaana/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on ZX1C223JKW 
STOP log received from  0be0c6c6 Test has  SUCCEEDED
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 0be0c6c6 
Device test finished on 41006f95c8139173 
Android task is completed. [SUCCESS]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/5546736337bcedb_Story_001_tompaana_406_tompaana/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/5546736337bcedb_Story_001_tompaana_406_tompaana/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/5546736337bcedb_Story_001_tompaana_406_tompaana/thali04_samsung-SM-G900F.md)

####Node name: thali06
Console output:
```
STOP log received from  7970f88c Test has  SUCCEEDED
Device test finished on 7970f88c 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:null 
child process exited with code null on device FA55PYS00566 
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:0 
child process exited with code 0 on device 022678fb504e29b0 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/5546736337bcedb_Story_001_tompaana_406_tompaana/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/5546736337bcedb_Story_001_tompaana_406_tompaana/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/5546736337bcedb_Story_001_tompaana_406_tompaana/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
STOP log received from  4db5c8cc Test has  SUCCEEDED
STOP log received from  c5afcdcb Test has  SUCCEEDED
Device test finished on 4db5c8cc 
Device test finished on c5afcdcb 
Android task is completed. [SUCCESS]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/5546736337bcedb_Story_001_tompaana_406_tompaana/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/5546736337bcedb_Story_001_tompaana_406_tompaana/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
STOP log received from  4325e43f Test has  SUCCEEDED
Device test finished on 4325e43f 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device HT574YC04723 app:com.test.thalitest code:null 
child process exited with code null on device HT574YC04723 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/5546736337bcedb_Story_001_tompaana_406_tompaana/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/5546736337bcedb_Story_001_tompaana_406_tompaana/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/5546736337bcedb_Story_001_tompaana_406_tompaana/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/5546736337bcedb_Story_001_tompaana_406_tompaana/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/5546736337bcedb_Story_001_tompaana_406_tompaana/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/5546736337bcedb_Story_001_tompaana_406_tompaana/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/5546736337bcedb_Story_001_tompaana_406_tompaana/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/5546736337bcedb_Story_001_tompaana_406_tompaana/iOS_Iphone5s-1.md)



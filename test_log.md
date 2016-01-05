#### Test 5507315224df3aa Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-05T15:48:34.603Z - info: listening on *:3000

2016-01-05T15:48:36.166Z - debug: Device presented: Thali Test (Galaxy A3) (android) perftest socket:1

2016-01-05T15:48:36.172Z - info: Setting start timeout to: 120000 (android)

2016-01-05T15:48:36.178Z - debug: Device presented: A3-1 (android) perftest socket:2

2016-01-05T15:48:36.184Z - debug: Device presented: Thali Test (Galaxy A5) (android) perftest socket:3

2016-01-05T15:48:36.187Z - debug: Device presented: Apple-IpadAir2-1 (ios) perftest socket:0

2016-01-05T15:48:36.190Z - info: Setting start timeout to: 120000 (ios)

2016-01-05T15:48:36.983Z - debug: Device presented: XT1072 (android) perftest socket:4

2016-01-05T15:48:37.162Z - debug: Device presented: Apple-Iphone5s-1 (ios) perftest socket:5

2016-01-05T15:48:37.220Z - debug: Device presented: G3-1 (android) perftest socket:6

2016-01-05T15:48:37.439Z - debug: Device presented: Nexus 5 (android) perftest socket:7

2016-01-05T15:48:37.575Z - debug: Device presented: G3s-1 (android) perftest socket:8

2016-01-05T15:48:37.864Z - debug: Device presented: Apple-Iphone6-1 (ios) perftest socket:9

2016-01-05T15:48:37.930Z - debug: Device presented: Note4-1 (android) perftest socket:10

2016-01-05T15:48:38.155Z - debug: Device presented: S5-1 (android) perftest socket:11

2016-01-05T15:48:38.597Z - debug: Device presented: Apple-Iphone5-1 (ios) perftest socket:12

2016-01-05T15:48:38.598Z - info: Required number of devices presented

2016-01-05T15:48:38.603Z - info: Starting perf test run for platform: ios

2016-01-05T15:48:38.604Z - info: Using devices:

2016-01-05T15:48:38.605Z - info: Apple-IpadAir2-1

2016-01-05T15:48:38.607Z - info: Apple-Iphone5s-1

2016-01-05T15:48:38.608Z - info: Apple-Iphone6-1

2016-01-05T15:48:38.609Z - info: Apple-Iphone5-1

2016-01-05T15:48:38.613Z - info: Starting test: with 4 devices (ios)

2016-01-05T15:48:38.854Z - debug: Device presented: Thali Test (Galaxy S5) (android) perftest socket:13

2016-01-05T15:48:39.240Z - debug: Device presented: A5-1 (android) perftest socket:14

2016-01-05T15:48:39.248Z - debug: Device presented: G4-1 (android) perftest socket:15

2016-01-05T15:48:40.102Z - info: Received results for {"name:":"Apple-Iphone6-1","time":1065,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-IpadAir2-1.S4dItg==","peerAvailable":true,"time":1062}]} Apple-Iphone6-1 ios (4 left)

2016-01-05T15:48:40.106Z - info: Received results for {"name:":"Apple-Iphone5-1","time":1343,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-IpadAir2-1.S4dItg==","peerAvailable":true,"time":1342}]} Apple-Iphone5-1 ios (3 left)

2016-01-05T15:48:40.118Z - info: Received results for {"name:":"Apple-IpadAir2-1","time":1116,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone6-1.DocMgw==","peerAvailable":true,"time":1114}]} Apple-IpadAir2-1 ios (2 left)

2016-01-05T15:48:42.005Z - info: Received results for {"name:":"Apple-Iphone5s-1","time":270,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone5-1.uykjrA==","peerAvailable":true,"time":269}]} Apple-Iphone5s-1 ios (1 left)

2016-01-05T15:48:42.008Z - info: All test data retrieved for testFindPeers.js (ios)

2016-01-05T15:48:42.015Z - info: Remaining tests: %s ios=[testSendData.js]

2016-01-05T15:48:42.019Z - info: Continuing to next test: testSendData.js
2016-01-05T15:48:42.020Z - info: Starting test: with 4 devices (ios)

2016-01-05T15:49:03.703Z - debug: Device presented: XT1039 (android) perftest socket:16

2016-01-05T15:49:04.707Z - debug: Socket disconnected: transport close 16 (XT1039)

2016-01-05T15:49:35.791Z - info: Received results for {"name:":"Apple-Iphone5s-1","time":53259,"result":"OK","sendList":[{"name":"Apple-Iphone5-1.uykjrA==","time":40824,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-Iphone5-1.cnOsew==","time":3547,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1.xC8Jhw==","time":4171,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1.GJN/JA==","time":4056,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone5s-1 ios (4 left)

2016-01-05T15:49:38.939Z - info: Received results for {"name:":"Apple-IpadAir2-1","time":56322,"result":"OK","sendList":[{"name":"Apple-Iphone6-1.DocMgw==","time":42019,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-Iphone5s-1.lzdGtw==","time":4473,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1.GJN/JA==","time":5733,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1.cnOsew==","time":3567,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-IpadAir2-1 ios (3 left)

2016-01-05T15:50:05.114Z - debug: Socket disconnected: ping timeout 12 (Apple-Iphone5-1)

2016-01-05T15:50:14.575Z - info: Received results for {"name:":"Apple-Iphone6-1","time":90783,"result":"OK","sendList":[{"name":"Apple-Iphone6-1.DocMgw==","time":41050,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-IpadAir2-1.xC8Jhw==","time":43675,"result":"OK","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1.lzdGtw==","time":3237,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1.cnOsew==","time":2621,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone6-1 ios (2 left)

2016-01-05T15:50:36.191Z - info: Start timeout elapsed for platform: android

2016-01-05T15:50:36.193Z - info: Starting perf test run for platform: android

2016-01-05T15:50:36.194Z - info: Using devices:

2016-01-05T15:50:36.195Z - info: Thali Test (Galaxy A3)

2016-01-05T15:50:36.196Z - info: A3-1

2016-01-05T15:50:36.197Z - info: Thali Test (Galaxy A5)

2016-01-05T15:50:36.198Z - info: XT1072

2016-01-05T15:50:36.199Z - info: G3-1

2016-01-05T15:50:36.202Z - info: Nexus 5

2016-01-05T15:50:36.203Z - info: G3s-1
2016-01-05T15:50:36.204Z - info: Note4-1
2016-01-05T15:50:36.205Z - info: S5-1

2016-01-05T15:50:36.206Z - info: Thali Test (Galaxy S5)

2016-01-05T15:50:36.207Z - info: A5-1

2016-01-05T15:50:36.208Z - info: G4-1

2016-01-05T15:50:36.209Z - info: XT1039
2016-01-05T15:50:36.210Z - info: Starting test: with 13 devices (android)

2016-01-05T15:50:36.225Z - info: Start timeout elapsed for platform: ios

2016-01-05T15:50:36.226Z - info: Tests for ios already running or completed

2016-01-05T15:50:38.618Z - info: server timeout for test: testFindPeers.js (ios)

2016-01-05T15:50:38.619Z - info: All test data retrieved for testFindPeers.js (ios)

2016-01-05T15:50:38.622Z - info: No results from Apple-Iphone5-1

2016-01-05T15:50:38.624Z - info: Remaining tests: %s ios=[], android=[testFindPeers.js, testSendData.js]

2016-01-05T15:50:38.627Z - info: ALL DONE !!!

{ 'name:': 'Apple-IpadAir2-1',
  time: 1116,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1.DocMgw==',
       peerAvailable: true,
       time: 1114 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 270,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1.uykjrA==',
       peerAvailable: true,
       time: 269 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 1065,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1.S4dItg==',
       peerAvailable: true,
       time: 1062 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 1343,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1.S4dItg==',
       peerAvailable: true,
       time: 1342 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 56322,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1.DocMgw==',
       time: 42019,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1.lzdGtw==',
       time: 4473,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.GJN/JA==',
       time: 5733,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.cnOsew==',
       time: 3567,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 53259,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.uykjrA==',
       time: 40824,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.cnOsew==',
       time: 3547,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1.xC8Jhw==',
       time: 4171,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.GJN/JA==',
       time: 4056,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 90783,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1.DocMgw==',
       time: 41050,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.xC8Jhw==',
       time: 43675,
       result: 'OK',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.lzdGtw==',
       time: 3237,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.cnOsew==',
       time: 2621,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

--------------- test report ---------------------
--------------- Apple-IpadAir2-1 --------------------- : 1

peersList : 100% : 1114 ms, 99% : 1114 ms, 95 : 1114 ms, 90% : 1114 ms.

Result count 1, range 1114 ms to  1114 ms.

sendList : 100% : 5733 ms, 99% : 5733 ms, 95 : 5733 ms, 90% : 5733 ms.

Average data rate: 0.022 MB/s

Result count 3, range 3567 ms to  5733 ms.

sendList failed peers count : 1 [25 %]

- Peer ID : Apple-Iphone6-1.DocMgw==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5s-1 --------------------- : 2

peersList : 100% : 269 ms, 99% : 269 ms, 95 : 269 ms, 90% : 269 ms.
Result count 1, range 269 ms to  269 ms.

sendList : 100% : 4171 ms, 99% : 4171 ms, 95 : 4171 ms, 90% : 4171 ms.
Average data rate: 0.025 MB/s
Result count 3, range 3547 ms to  4171 ms.

sendList failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone5-1.uykjrA==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone6-1 --------------------- : 3
peersList : 100% : 1062 ms, 99% : 1062 ms, 95 : 1062 ms, 90% : 1062 ms.
Result count 1, range 1062 ms to  1062 ms.
sendList : 100% : 43675 ms, 99% : 43675 ms, 95 : 43675 ms, 90% : 43675 ms.

Average data rate: 0.006 MB/s
Result count 3, range 2621 ms to  43675 ms.
sendList failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone6-1.DocMgw==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5-1 --------------------- : 4
peersList : 100% : 1342 ms, 99% : 1342 ms, 95 : 1342 ms, 90% : 1342 ms.
Result count 1, range 1342 ms to  1342 ms.

--------------- Combined ---------------------
peersList : 100% : 1342 ms, 99% : 1342 ms, 95 : 1342 ms, 90% : 1342 ms.

sendList : 100% : 43675 ms, 99% : 43675 ms, 95 : 43675 ms, 90% : 5733 ms.
Average data rate: 0.012 MB/s
--------------- end of test report ---------------------

2016-01-05T15:50:38.718Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1.DocMgw==, peerAvailable=true, time=1114], sendList=[name=Apple-Iphone5-1.cnOsew==, time=3567, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5s-1.lzdGtw==, time=4473, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone6-1.GJN/JA==, time=5733, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone6-1.DocMgw==, time=42019, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1.uykjrA==, peerAvailable=true, time=269], sendList=[name=Apple-Iphone5-1.cnOsew==, time=3547, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone6-1.GJN/JA==, time=4056, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.xC8Jhw==, time=4171, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone5-1.uykjrA==, time=40824, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1.S4dItg==, peerAvailable=true, time=1062], sendList=[name=Apple-Iphone5-1.cnOsew==, time=2621, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5s-1.lzdGtw==, time=3237, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.xC8Jhw==, time=43675, result=OK, connections=5, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone6-1.DocMgw==, time=41050, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1.S4dItg==, peerAvailable=true, time=1342]

2016-01-05T15:50:38.725Z - debug: end to Apple-IpadAir2-1

2016-01-05T15:50:38.727Z - debug: end to Apple-Iphone5s-1

2016-01-05T15:50:38.738Z - debug: end to Apple-Iphone6-1

2016-01-05T15:50:38.739Z - debug: end to Apple-Iphone5-1

2016-01-05T15:50:38.869Z - info: Received results for {"name:":"XT1072","time":1856,"result":"OK","peersList":[{"peerName":"Nexus 5","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":true,"time":1854}]} XT1072 android (13 left)

2016-01-05T15:50:39.264Z - info: Received results for {"name:":"Thali Test (Galaxy A3)","time":2264,"result":"OK","peersList":[{"peerName":"Note4-1","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":2262}]} Thali Test (Galaxy A3) android (12 left)

2016-01-05T15:50:39.600Z - info: Received results for {"name:":"Thali Test (Galaxy A5)","time":2594,"result":"OK","peersList":[{"peerName":"Nexus 5","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":true,"time":2593}]} Thali Test (Galaxy A5) android (11 left)

2016-01-05T15:50:39.808Z - info: Received results for {"name:":"A5-1","time":2771,"result":"OK","peersList":[{"peerName":"Note4-1","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":2766}]} A5-1 android (10 left)

2016-01-05T15:50:40.287Z - info: Received results for {"name:":"Nexus 5","time":3788,"result":"OK","peersList":[{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":3783}]} Nexus 5 android (9 left)

2016-01-05T15:50:41.630Z - debug: Socket disconnected: transport close 5 (Apple-Iphone5s-1)

2016-01-05T15:50:41.728Z - info: Received results for {"name:":"Note4-1","time":4306,"result":"OK","peersList":[{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":4302}]} Note4-1 android (8 left)

2016-01-05T15:50:41.824Z - debug: Socket disconnected: transport close 0 (Apple-IpadAir2-1)

2016-01-05T15:50:42.022Z - info: server timeout for test: testSendData.js (ios)

2016-01-05T15:50:42.025Z - info: All test data retrieved for testSendData.js (ios)

2016-01-05T15:50:42.028Z - info: No results from Apple-Iphone5-1

2016-01-05T15:50:42.029Z - info: Remaining tests: %s ios=[], android=[testFindPeers.js, testSendData.js]

2016-01-05T15:50:42.031Z - info: ALL DONE !!!

{ 'name:': 'Apple-IpadAir2-1',
  time: 1116,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1.DocMgw==',
       peerAvailable: true,
       time: 1114 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 270,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1.uykjrA==',
       peerAvailable: true,
       time: 269 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 1065,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1.S4dItg==',
       peerAvailable: true,
       time: 1062 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 1343,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1.S4dItg==',
       peerAvailable: true,
       time: 1342 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 56322,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1.DocMgw==',
       time: 42019,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1.lzdGtw==',
       time: 4473,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.GJN/JA==',
       time: 5733,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.cnOsew==',
       time: 3567,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 53259,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.uykjrA==',
       time: 40824,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.cnOsew==',
       time: 3547,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1.xC8Jhw==',
       time: 4171,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.GJN/JA==',
       time: 4056,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 90783,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1.DocMgw==',
       time: 41050,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.xC8Jhw==',
       time: 43675,
       result: 'OK',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.lzdGtw==',
       time: 3237,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.cnOsew==',
       time: 2621,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 56322,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1.DocMgw==',
       time: 42019,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1.lzdGtw==',
       time: 4473,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.GJN/JA==',
       time: 5733,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.cnOsew==',
       time: 3567,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 53259,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.uykjrA==',
       time: 40824,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.cnOsew==',
       time: 3547,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1.xC8Jhw==',
       time: 4171,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.GJN/JA==',
       time: 4056,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 90783,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1.DocMgw==',
       time: 41050,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.xC8Jhw==',
       time: 43675,
       result: 'OK',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.lzdGtw==',
       time: 3237,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.cnOsew==',
       time: 2621,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

--------------- test report ---------------------
--------------- Apple-IpadAir2-1 --------------------- : 1
peersList : 100% : 1114 ms, 99% : 1114 ms, 95 : 1114 ms, 90% : 1114 ms.
Result count 1, range 1114 ms to  1114 ms.
sendList : 100% : 5733 ms, 99% : 5733 ms, 95 : 5733 ms, 90% : 5733 ms.
Average data rate: 0.022 MB/s
Result count 6, range 3567 ms to  5733 ms.
sendList failed peers count : 2 [25 %]
- Peer ID : Apple-Iphone6-1.DocMgw==, Tried : 5
- Peer ID : Apple-Iphone6-1.DocMgw==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5s-1 --------------------- : 2
peersList : 100% : 269 ms, 99% : 269 ms, 95 : 269 ms, 90% : 269 ms.
Result count 1, range 269 ms to  269 ms.
sendList : 100% : 4171 ms, 99% : 4171 ms, 95 : 4171 ms, 90% : 4171 ms.
Average data rate: 0.025 MB/s
Result count 6, range 3547 ms to  4171 ms.
sendList failed peers count : 2 [25 %]
- Peer ID : Apple-Iphone5-1.uykjrA==, Tried : 5
- Peer ID : Apple-Iphone5-1.uykjrA==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1 --------------------- : 3
peersList : 100% : 1062 ms, 99% : 1062 ms, 95 : 1062 ms, 90% : 1062 ms.

Result count 1, range 1062 ms to  1062 ms.

sendList : 100% : 43675 ms, 99% : 43675 ms, 95 : 43675 ms, 90% : 43675 ms.
Average data rate: 0.006 MB/s
Result count 6, range 2621 ms to  43675 ms.
sendList failed peers count : 2 [25 %]
- Peer ID : Apple-Iphone6-1.DocMgw==, Tried : 5

- Peer ID : Apple-Iphone6-1.DocMgw==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5-1 --------------------- : 4
peersList : 100% : 1342 ms, 99% : 1342 ms, 95 : 1342 ms, 90% : 1342 ms.

Result count 1, range 1342 ms to  1342 ms.
--------------- Combined ---------------------
peersList : 100% : 1342 ms, 99% : 1342 ms, 95 : 1342 ms, 90% : 1342 ms.
sendList : 100% : 43675 ms, 99% : 43675 ms, 95 : 43675 ms, 90% : 5733 ms.
Average data rate: 0.012 MB/s
--------------- end of test report ---------------------

2016-01-05T15:50:42.147Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1.DocMgw==, peerAvailable=true, time=1114], sendList=[name=Apple-Iphone5-1.cnOsew==, time=3567, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1"]["sendList"][0], name=Apple-Iphone5s-1.lzdGtw==, time=4473, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1"]["sendList"][2], name=Apple-Iphone6-1.GJN/JA==, time=5733, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1"]["sendList"][4]], failedPeer=[name=Apple-Iphone6-1.DocMgw==, time=42019, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-IpadAir2-1"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1.uykjrA==, peerAvailable=true, time=269], sendList=[name=Apple-Iphone5-1.cnOsew==, time=3547, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1"]["sendList"][0], name=Apple-Iphone6-1.GJN/JA==, time=4056, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1"]["sendList"][2], name=Apple-IpadAir2-1.xC8Jhw==, time=4171, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1"]["sendList"][4]], failedPeer=[name=Apple-Iphone5-1.uykjrA==, time=40824, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone5s-1"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1.S4dItg==, peerAvailable=true, time=1062], sendList=[name=Apple-Iphone5-1.cnOsew==, time=2621, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1"]["sendList"][0], name=Apple-Iphone5s-1.lzdGtw==, time=3237, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1"]["sendList"][2], name=Apple-IpadAir2-1.xC8Jhw==, time=43675, result=OK, connections=5, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1"]["sendList"][4]], failedPeer=[name=Apple-Iphone6-1.DocMgw==, time=41050, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone6-1"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1.S4dItg==, peerAvailable=true, time=1342]

2016-01-05T15:50:42.152Z - debug: end to Apple-IpadAir2-1
2016-01-05T15:50:42.153Z - debug: end to Apple-Iphone5s-1
2016-01-05T15:50:42.155Z - debug: end to Apple-Iphone6-1
2016-01-05T15:50:42.156Z - debug: end to Apple-Iphone5-1
2016-01-05T15:50:42.163Z - debug: Socket disconnected: transport close 9 (Apple-Iphone6-1)

2016-01-05T15:50:42.365Z - info: Received results for {"name:":"S5-1","time":4917,"result":"OK","peersList":[{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":4906}]} S5-1 android (7 left)

2016-01-05T15:50:43.678Z - info: Received results for {"name:":"A3-1","time":6494,"result":"OK","peersList":[{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":6492}]} A3-1 android (6 left)

2016-01-05T15:50:44.463Z - info: Received results for {"name:":"G3-1","time":2037,"result":"OK","peersList":[{"peerName":"Note4-1","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":2036}]} G3-1 android (5 left)

2016-01-05T15:50:46.725Z - info: Received results for {"name:":"Thali Test (Galaxy S5)","time":9266,"result":"OK","peersList":[{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":9261}]} Thali Test (Galaxy S5) android (4 left)

2016-01-05T15:50:57.648Z - info: Received results for {"name:":"G3s-1","time":20069,"result":"OK","peersList":[{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":20061}]} G3s-1 android (3 left)

2016-01-05T15:50:59.790Z - info: Received results for {"name:":"G4-1","time":23365,"result":"OK","peersList":[{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":23363}]} G4-1 android (2 left)

2016-01-05T15:52:34.334Z - debug: Socket disconnected: ping timeout 4 (XT1072)

2016-01-05T15:52:36.216Z - info: server timeout for test: testFindPeers.js (android)

2016-01-05T15:52:36.219Z - info: All test data retrieved for testFindPeers.js (android)

2016-01-05T15:52:36.226Z - info: No results from XT1039

2016-01-05T15:52:36.230Z - info: Remaining tests: %s ios=[], android=[testSendData.js]

2016-01-05T15:52:36.231Z - info: Continuing to next test: testSendData.js

2016-01-05T15:52:36.232Z - info: Starting test: with 13 devices (android)

2016-01-05T15:54:16.575Z - info: Received results for {"name:":"Thali Test (Galaxy S5)","time":100089,"result":"TIMEOUT","sendList":[{"name":"7C:F9:0E:34:8A:A0","time":3391,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:76:27","time":5533,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Thali Test (Galaxy S5) android (13 left)

2016-01-05T15:54:16.598Z - info: Received results for {"name:":"Nexus 5","time":100048,"result":"TIMEOUT","sendList":[]} Nexus 5 android (12 left)

2016-01-05T15:54:16.636Z - info: Received results for {"name:":"G4-1","time":100070,"result":"TIMEOUT","sendList":[]} G4-1 android (11 left)

2016-01-05T15:54:16.847Z - info: Received results for {"name:":"A3-1","time":100058,"result":"TIMEOUT","sendList":[]} A3-1 android (10 left)

2016-01-05T15:54:16.891Z - info: Received results for {"name:":"Note4-1","time":100053,"result":"TIMEOUT","sendList":[{"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"}]} Note4-1 android (9 left)

2016-01-05T15:54:16.900Z - info: Received results for {"name:":"S5-1","time":100065,"result":"TIMEOUT","sendList":[{"name":"08:EC:A9:50:76:27","time":4179,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} S5-1 android (8 left)

2016-01-05T15:54:16.934Z - info: Received results for {"name:":"G3s-1","time":100190,"result":"TIMEOUT","sendList":[]} G3s-1 android (7 left)

2016-01-05T15:54:17.188Z - info: Received results for {"name:":"Thali Test (Galaxy A3)","time":100049,"result":"TIMEOUT","sendList":[{"name":"7C:F9:0E:34:8A:A0","time":2290,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":2472,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Thali Test (Galaxy A3) android (6 left)

2016-01-05T15:54:17.798Z - info: Received results for {"name:":"A5-1","time":100051,"result":"TIMEOUT","sendList":[]} A5-1 android (5 left)

2016-01-05T15:54:17.872Z - info: Received results for {"name:":"Thali Test (Galaxy A5)","time":100057,"result":"TIMEOUT","sendList":[{"name":"F8:95:C7:87:3C:51","time":3256,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:34:8A:A0","time":3313,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Thali Test (Galaxy A5) android (4 left)

2016-01-05T15:54:21.733Z - info: Received results for {"name:":"G3-1","time":100060,"result":"TIMEOUT","sendList":[]} G3-1 android (3 left)

2016-01-05T15:54:36.241Z - info: server timeout for test: testSendData.js (android)

2016-01-05T15:54:36.243Z - info: All test data retrieved for testSendData.js (android)

2016-01-05T15:54:36.247Z - info: No results from XT1072

2016-01-05T15:54:36.261Z - info: No results from XT1039

2016-01-05T15:54:36.267Z - info: Remaining tests: %s ios=[], android=[]

2016-01-05T15:54:36.269Z - info: ALL DONE !!!

{ 'name:': 'Apple-IpadAir2-1',
  time: 1116,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1.DocMgw==',
       peerAvailable: true,
       time: 1114 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 270,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1.uykjrA==',
       peerAvailable: true,
       time: 269 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 1065,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1.S4dItg==',
       peerAvailable: true,
       time: 1062 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 1343,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1.S4dItg==',
       peerAvailable: true,
       time: 1342 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 56322,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1.DocMgw==',
       time: 42019,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1.lzdGtw==',
       time: 4473,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.GJN/JA==',
       time: 5733,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.cnOsew==',
       time: 3567,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 53259,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.uykjrA==',
       time: 40824,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.cnOsew==',
       time: 3547,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1.xC8Jhw==',
       time: 4171,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.GJN/JA==',
       time: 4056,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 90783,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1.DocMgw==',
       time: 41050,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.xC8Jhw==',
       time: 43675,
       result: 'OK',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.lzdGtw==',
       time: 3237,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.cnOsew==',
       time: 2621,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 56322,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1.DocMgw==',
       time: 42019,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1.lzdGtw==',
       time: 4473,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.GJN/JA==',
       time: 5733,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.cnOsew==',
       time: 3567,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 53259,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.uykjrA==',
       time: 40824,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.cnOsew==',
       time: 3547,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1.xC8Jhw==',
       time: 4171,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.GJN/JA==',
       time: 4056,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 90783,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1.DocMgw==',
       time: 41050,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.xC8Jhw==',
       time: 43675,
       result: 'OK',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.lzdGtw==',
       time: 3237,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.cnOsew==',
       time: 2621,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Thali Test (Galaxy A3)',
  time: 2264,
  result: 'OK',
  peersList: 
   [ { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 2262 } ] }

{ 'name:': 'A3-1',
  time: 6494,
  result: 'OK',
  peersList: 
   [ { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 6492 } ] }

{ 'name:': 'Thali Test (Galaxy A5)',
  time: 2594,
  result: 'OK',
  peersList: 
   [ { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 2593 } ] }

{ 'name:': 'XT1072',
  time: 1856,
  result: 'OK',
  peersList: 
   [ { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 1854 } ] }

{ 'name:': 'G3-1',
  time: 2037,
  result: 'OK',
  peersList: 
   [ { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 2036 } ] }

{ 'name:': 'Nexus 5',
  time: 3788,
  result: 'OK',
  peersList: 
   [ { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 3783 } ] }

{ 'name:': 'G3s-1',
  time: 20069,
  result: 'OK',
  peersList: 
   [ { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 20061 } ] }

{ 'name:': 'Note4-1',
  time: 4306,
  result: 'OK',
  peersList: 
   [ { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 4302 } ] }

{ 'name:': 'S5-1',
  time: 4917,
  result: 'OK',
  peersList: 
   [ { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 4906 } ] }

{ 'name:': 'Thali Test (Galaxy S5)',
  time: 9266,
  result: 'OK',
  peersList: 
   [ { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 9261 } ] }

{ 'name:': 'A5-1',
  time: 2771,
  result: 'OK',
  peersList: 
   [ { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 2766 } ] }

{ 'name:': 'G4-1',
  time: 23365,
  result: 'OK',
  peersList: 
   [ { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 23363 } ] }

{ 'name:': 'Thali Test (Galaxy A3)',
  time: 100049,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '7C:F9:0E:34:8A:A0',
       time: 2290,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'B0:C5:59:3F:75:69',
       time: 2472,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'A3-1', time: 100058, result: 'TIMEOUT', sendList: [] }

{ 'name:': 'Thali Test (Galaxy A5)',
  time: 100057,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'F8:95:C7:87:3C:51',
       time: 3256,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:34:8A:A0',
       time: 3313,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'G3-1', time: 100060, result: 'TIMEOUT', sendList: [] }

{ 'name:': 'Nexus 5',
  time: 100048,
  result: 'TIMEOUT',
  sendList: [] }

{ 'name:': 'G3s-1',
  time: 100190,
  result: 'TIMEOUT',
  sendList: [] }

{ 'name:': 'Note4-1',
  time: 100053,
  result: 'TIMEOUT',
  sendList: [ { name: '58:3F:54:73:64:C0', time: 0, result: 'Fail' } ] }

{ 'name:': 'S5-1',
  time: 100065,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '08:EC:A9:50:76:27',
       time: 4179,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Thali Test (Galaxy S5)',
  time: 100089,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '7C:F9:0E:34:8A:A0',
       time: 3391,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '08:EC:A9:50:76:27',
       time: 5533,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'A5-1', time: 100051, result: 'TIMEOUT', sendList: [] }
{ 'name:': 'G4-1', time: 100070, result: 'TIMEOUT', sendList: [] }
--------------- test report ---------------------
--------------- Apple-IpadAir2-1 --------------------- : 1
peersList : 100% : 1114 ms, 99% : 1114 ms, 95 : 1114 ms, 90% : 1114 ms.
Result count 1, range 1114 ms to  1114 ms.
sendList : 100% : 5733 ms, 99% : 5733 ms, 95 : 5733 ms, 90% : 5733 ms.
Average data rate: 0.022 MB/s
Result count 6, range 3567 ms to  5733 ms.
sendList failed peers count : 2 [25 %]
- Peer ID : Apple-Iphone6-1.DocMgw==, Tried : 5
- Peer ID : Apple-Iphone6-1.DocMgw==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5s-1 --------------------- : 2
peersList : 100% : 269 ms, 99% : 269 ms, 95 : 269 ms, 90% : 269 ms.
Result count 1, range 269 ms to  269 ms.
sendList : 100% : 4171 ms, 99% : 4171 ms, 95 : 4171 ms, 90% : 4171 ms.
Average data rate: 0.025 MB/s
Result count 6, range 3547 ms to  4171 ms.
sendList failed peers count : 2 [25 %]
- Peer ID : Apple-Iphone5-1.uykjrA==, Tried : 5
- Peer ID : Apple-Iphone5-1.uykjrA==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1 --------------------- : 3
peersList : 100% : 1062 ms, 99% : 1062 ms, 95 : 1062 ms, 90% : 1062 ms.
Result count 1, range 1062 ms to  1062 ms.
sendList : 100% : 43675 ms, 99% : 43675 ms, 95 : 43675 ms, 90% : 43675 ms.
Average data rate: 0.006 MB/s
Result count 6, range 2621 ms to  43675 ms.
sendList failed peers count : 2 [25 %]
- Peer ID : Apple-Iphone6-1.DocMgw==, Tried : 5
- Peer ID : Apple-Iphone6-1.DocMgw==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5-1 --------------------- : 4
peersList : 100% : 1342 ms, 99% : 1342 ms, 95 : 1342 ms, 90% : 1342 ms.
Result count 1, range 1342 ms to  1342 ms.
--------------- Thali Test (Galaxy A3) --------------------- : 5
peersList : 100% : 2262 ms, 99% : 2262 ms, 95 : 2262 ms, 90% : 2262 ms.
Result count 1, range 2262 ms to  2262 ms.
sendList : 100% : 2472 ms, 99% : 2472 ms, 95 : 2472 ms, 90% : 2472 ms.
Average data rate: 0.042 MB/s
Result count 2, range 2290 ms to  2472 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- A3-1 --------------------- : 6

peersList : 100% : 6492 ms, 99% : 6492 ms, 95 : 6492 ms, 90% : 6492 ms.
Result count 1, range 6492 ms to  6492 ms.
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.

Average data rate: NaN MB/s
Results list does not contain any items

--------------- Thali Test (Galaxy A5) --------------------- : 7
peersList : 100% : 2593 ms, 99% : 2593 ms, 95 : 2593 ms, 90% : 2593 ms.

Result count 1, range 2593 ms to  2593 ms.
sendList : 100% : 3313 ms, 99% : 3313 ms, 95 : 3313 ms, 90% : 3313 ms.
Average data rate: 0.03 MB/s
Result count 2, range 3256 ms to  3313 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- XT1072 --------------------- : 8
peersList : 100% : 1854 ms, 99% : 1854 ms, 95 : 1854 ms, 90% : 1854 ms.
Result count 1, range 1854 ms to  1854 ms.
--------------- G3-1 --------------------- : 9

peersList : 100% : 2036 ms, 99% : 2036 ms, 95 : 2036 ms, 90% : 2036 ms.
Result count 1, range 2036 ms to  2036 ms.
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
--------------- Nexus 5 --------------------- : 10
peersList : 100% : 3783 ms, 99% : 3783 ms, 95 : 3783 ms, 90% : 3783 ms.
Result count 1, range 3783 ms to  3783 ms.
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
--------------- G3s-1 --------------------- : 11
peersList : 100% : 20061 ms, 99% : 20061 ms, 95 : 20061 ms, 90% : 20061 ms.
Result count 1, range 20061 ms to  20061 ms.
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
--------------- Note4-1 --------------------- : 12
peersList : 100% : 4302 ms, 99% : 4302 ms, 95 : 4302 ms, 90% : 4302 ms.
Result count 1, range 4302 ms to  4302 ms.
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s

Results list does not contain any items
--------------- S5-1 --------------------- : 13

peersList : 100% : 4906 ms, 99% : 4906 ms, 95 : 4906 ms, 90% : 4906 ms.
Result count 1, range 4906 ms to  4906 ms.

sendList : 100% : 4179 ms, 99% : 4179 ms, 95 : 4179 ms, 90% : 4179 ms.
Average data rate: 0.024 MB/s

Result count 1, range 4179 ms to  4179 ms.
sendList failed peers count : 0 [0 %]

sendList never tried peers count : 0 [0 %]

--------------- Thali Test (Galaxy S5) --------------------- : 14

peersList : 100% : 9261 ms, 99% : 9261 ms, 95 : 9261 ms, 90% : 9261 ms.
Result count 1, range 9261 ms to  9261 ms.
sendList : 100% : 5533 ms, 99% : 5533 ms, 95 : 5533 ms, 90% : 5533 ms.
Average data rate: 0.022 MB/s
Result count 2, range 3391 ms to  5533 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- A5-1 --------------------- : 15
peersList : 100% : 2766 ms, 99% : 2766 ms, 95 : 2766 ms, 90% : 2766 ms.

Result count 1, range 2766 ms to  2766 ms.
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.

Average data rate: NaN MB/s
Results list does not contain any items
--------------- G4-1 --------------------- : 16
peersList : 100% : 23363 ms, 99% : 23363 ms, 95 : 23363 ms, 90% : 23363 ms.
Result count 1, range 23363 ms to  23363 ms.
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s

Results list does not contain any items
--------------- Combined ---------------------

peersList : 100% : 23363 ms, 99% : 23363 ms, 95 : 20061 ms, 90% : 9261 ms.

sendList : 100% : 43675 ms, 99% : 43675 ms, 95 : 43675 ms, 90% : 5733 ms.

Average data rate: 0.014 MB/s
--------------- end of test report ---------------------

2016-01-05T15:54:36.448Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1.DocMgw==, peerAvailable=true, time=1114], sendList=[name=Apple-Iphone5-1.cnOsew==, time=3567, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1"]["sendList"][0], name=Apple-Iphone5s-1.lzdGtw==, time=4473, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1"]["sendList"][2], name=Apple-Iphone6-1.GJN/JA==, time=5733, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1"]["sendList"][4]], failedPeer=[name=Apple-Iphone6-1.DocMgw==, time=42019, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-IpadAir2-1"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1.uykjrA==, peerAvailable=true, time=269], sendList=[name=Apple-Iphone5-1.cnOsew==, time=3547, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1"]["sendList"][0], name=Apple-Iphone6-1.GJN/JA==, time=4056, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1"]["sendList"][2], name=Apple-IpadAir2-1.xC8Jhw==, time=4171, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1"]["sendList"][4]], failedPeer=[name=Apple-Iphone5-1.uykjrA==, time=40824, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone5s-1"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1.S4dItg==, peerAvailable=true, time=1062], sendList=[name=Apple-Iphone5-1.cnOsew==, time=2621, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1"]["sendList"][0], name=Apple-Iphone5s-1.lzdGtw==, time=3237, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1"]["sendList"][2], name=Apple-IpadAir2-1.xC8Jhw==, time=43675, result=OK, connections=5, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1"]["sendList"][4]], failedPeer=[name=Apple-Iphone6-1.DocMgw==, time=41050, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone6-1"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1.S4dItg==, peerAvailable=true, time=1342], peersList=[peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=2262], sendList=[name=7C:F9:0E:34:8A:A0, time=2290, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=B0:C5:59:3F:75:69, time=2472, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], peersList=[peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=6492], sendList=[], failedPeer=[], notTriedList=[], peersList=[peerName=Nexus 5, peerIdentifier=34:FC:EF:11:AE:67, peerAvailable=true, time=2593], sendList=[name=F8:95:C7:87:3C:51, time=3256, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:34:8A:A0, time=3313, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], peersList=[peerName=Nexus 5, peerIdentifier=34:FC:EF:11:AE:67, peerAvailable=true, time=1854], peersList=[peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=2036], sendList=[], failedPeer=[], notTriedList=[], peersList=[peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=3783], sendList=[], failedPeer=[], notTriedList=[], peersList=[peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=20061], sendList=[], failedPeer=[], notTriedList=[], peersList=[peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=4302], sendList=[], failedPeer=[], notTriedList=[name=58:3F:54:73:64:C0, time=0, result=Fail], peersList=[peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=4906], sendList=[name=08:EC:A9:50:76:27, time=4179, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], peersList=[peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=9261], sendList=[name=7C:F9:0E:34:8A:A0, time=3391, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=08:EC:A9:50:76:27, time=5533, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], peersList=[peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=2766], sendList=[], failedPeer=[], notTriedList=[], peersList=[peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=23363], sendList=[], failedPeer=[], notTriedList=[]

2016-01-05T15:54:36.466Z - debug: end to Thali Test (Galaxy A3)

2016-01-05T15:54:36.469Z - debug: end to A3-1

2016-01-05T15:54:36.471Z - debug: end to Thali Test (Galaxy A5)

2016-01-05T15:54:36.472Z - debug: end to XT1072

2016-01-05T15:54:36.473Z - debug: end to G3-1

2016-01-05T15:54:36.475Z - debug: end to Nexus 5

2016-01-05T15:54:36.477Z - debug: end to G3s-1

2016-01-05T15:54:36.478Z - debug: end to Note4-1

2016-01-05T15:54:36.480Z - debug: end to S5-1

2016-01-05T15:54:36.481Z - debug: end to Thali Test (Galaxy S5)

2016-01-05T15:54:36.483Z - debug: end to A5-1

2016-01-05T15:54:36.486Z - debug: end to G4-1

2016-01-05T15:54:36.491Z - debug: end to XT1039

2016-01-05T15:54:37.425Z - debug: Socket disconnected: transport close 14 (A5-1)

2016-01-05T15:54:37.454Z - debug: Socket disconnected: transport close 10 (Note4-1)

2016-01-05T15:54:37.462Z - debug: Socket disconnected: transport close 1 (Thali Test (Galaxy A3))

2016-01-05T15:54:37.523Z - debug: Socket disconnected: transport close 2 (A3-1)

2016-01-05T15:54:37.542Z - debug: Socket disconnected: transport close 15 (G4-1)

2016-01-05T15:54:37.602Z - debug: Socket disconnected: transport close 6 (G3-1)

2016-01-05T15:54:37.623Z - debug: Socket disconnected: transport close 7 (Nexus 5)

2016-01-05T15:54:37.695Z - debug: Socket disconnected: transport close 13 (Thali Test (Galaxy S5))

2016-01-05T15:54:37.955Z - debug: Socket disconnected: transport close 8 (G3s-1)

2016-01-05T15:54:38.070Z - debug: Socket disconnected: transport close 11 (S5-1)

2016-01-05T15:54:38.885Z - debug: Socket disconnected: transport close 3 (Thali Test (Galaxy A5))


 
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
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/5507315224df3aa_Use_user-settable_device_name__vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/5507315224df3aa_Use_user-settable_device_name__vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/5507315224df3aa_Use_user-settable_device_name__vjrantal/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/5507315224df3aa_Use_user-settable_device_name__vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/5507315224df3aa_Use_user-settable_device_name__vjrantal/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
STOP log received from  f56ad48d Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Device test finished on f56ad48d 
Android task is completed. [SUCCESS]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/5507315224df3aa_Use_user-settable_device_name__vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/5507315224df3aa_Use_user-settable_device_name__vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/5507315224df3aa_Use_user-settable_device_name__vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/5507315224df3aa_Use_user-settable_device_name__vjrantal/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/5507315224df3aa_Use_user-settable_device_name__vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/5507315224df3aa_Use_user-settable_device_name__vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/5507315224df3aa_Use_user-settable_device_name__vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
STOP log received from  0be0c6c6 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Device test finished on 0be0c6c6 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/5507315224df3aa_Use_user-settable_device_name__vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/5507315224df3aa_Use_user-settable_device_name__vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/5507315224df3aa_Use_user-settable_device_name__vjrantal/thali04_samsung-SM-G900F.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/5507315224df3aa_Use_user-settable_device_name__vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/5507315224df3aa_Use_user-settable_device_name__vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/5507315224df3aa_Use_user-settable_device_name__vjrantal/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
STOP log received from  c5afcdcb Test has  SUCCEEDED
STOP log received from  4db5c8cc Test has  SUCCEEDED
Device test finished on c5afcdcb 
Device test finished on 4db5c8cc 
Android task is completed. [SUCCESS]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/5507315224df3aa_Use_user-settable_device_name__vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/5507315224df3aa_Use_user-settable_device_name__vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
STOP log received from  4325e43f Test has  SUCCEEDED
Device test finished on 4325e43f 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device HT574YC04723 app:com.test.thalitest code:0 
child process exited with code 0 on device HT574YC04723 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/5507315224df3aa_Use_user-settable_device_name__vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/5507315224df3aa_Use_user-settable_device_name__vjrantal/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/5507315224df3aa_Use_user-settable_device_name__vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/5507315224df3aa_Use_user-settable_device_name__vjrantal/thali09_LGE-Nexus 5.md)





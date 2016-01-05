#### Test 550731521dbc378 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-05T10:23:04.793Z - info: listening on *:3000

2016-01-05T10:23:05.546Z - debug: Device presented: A3-1 (android) perftest socket:1

2016-01-05T10:23:05.552Z - info: Setting start timeout to: 120000 (android)

2016-01-05T10:23:05.568Z - debug: Device presented: G4-1 (android) perftest socket:2

2016-01-05T10:23:05.657Z - debug: Device presented: Apple-Iphone5-1 (ios) perftest socket:3

2016-01-05T10:23:05.658Z - info: Setting start timeout to: 120000 (ios)

2016-01-05T10:23:05.674Z - debug: Device presented: Apple-Iphone6-1 (ios) perftest socket:0

2016-01-05T10:23:06.323Z - debug: Device presented: A5-1 (android) perftest socket:4

2016-01-05T10:23:06.487Z - debug: Device presented: Note4-1 (android) perftest socket:5

2016-01-05T10:23:07.228Z - debug: Device presented: Thali Test (Galaxy A5) (android) perftest socket:6

2016-01-05T10:23:07.911Z - debug: Device presented: Apple-IpadAir2-1 (ios) perftest socket:7

2016-01-05T10:23:07.993Z - debug: Device presented: Thali Test (Galaxy A3) (android) perftest socket:8

2016-01-05T10:23:08.476Z - debug: Device presented: Thali Test (Galaxy S5) (android) perftest socket:9

2016-01-05T10:23:09.402Z - debug: Device presented: G3-1 (android) perftest socket:11

2016-01-05T10:23:09.411Z - debug: Device presented: G3s-1 (android) perftest socket:10

2016-01-05T10:23:09.435Z - debug: Device presented: Nexus 5 (android) perftest socket:13

2016-01-05T10:23:09.545Z - debug: Device presented: Apple-Iphone5s-1 (ios) perftest socket:12

2016-01-05T10:23:09.546Z - info: Required number of devices presented

2016-01-05T10:23:09.550Z - info: Starting perf test run for platform: ios

2016-01-05T10:23:09.551Z - info: Using devices:

2016-01-05T10:23:09.553Z - info: Apple-Iphone5-1

2016-01-05T10:23:09.554Z - info: Apple-Iphone6-1

2016-01-05T10:23:09.555Z - info: Apple-IpadAir2-1

2016-01-05T10:23:09.556Z - info: Apple-Iphone5s-1

2016-01-05T10:23:09.562Z - info: Starting test: with 4 devices (ios)

2016-01-05T10:23:09.578Z - debug: Device presented: HTC One M8s (android) perftest socket:14

2016-01-05T10:23:11.128Z - info: Received results for {"name:":"Apple-Iphone5s-1","time":1310,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone5-1.+hwmKw==","peerAvailable":true,"time":1308}]} Apple-Iphone5s-1 ios (4 left)

2016-01-05T10:23:11.197Z - info: Received results for {"name:":"Apple-IpadAir2-1","time":1098,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone5-1.+hwmKw==","peerAvailable":true,"time":1096}]} Apple-IpadAir2-1 ios (3 left)

2016-01-05T10:23:11.754Z - info: Received results for {"name:":"Apple-Iphone5-1","time":1126,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-IpadAir2-1.o3kBVg==","peerAvailable":true,"time":1124}]} Apple-Iphone5-1 ios (2 left)

2016-01-05T10:23:12.090Z - info: Received results for {"name:":"Apple-Iphone6-1","time":2245,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone5s-1.Jzs4Xw==","peerAvailable":true,"time":2243}]} Apple-Iphone6-1 ios (1 left)

2016-01-05T10:23:12.094Z - info: All test data retrieved for testFindPeers.js (ios)

2016-01-05T10:23:12.098Z - info: Remaining tests: %s ios=[testSendData.js]

2016-01-05T10:23:12.102Z - info: Continuing to next test: testSendData.js
2016-01-05T10:23:12.103Z - info: Starting test: with 4 devices (ios)

2016-01-05T10:23:13.488Z - debug: Device presented: S5-1 (android) perftest socket:15

2016-01-05T10:23:16.726Z - debug: Device presented: XT1072 (android) perftest socket:16

2016-01-05T10:24:04.275Z - info: Received results for {"name:":"Apple-Iphone6-1","time":51625,"result":"OK","sendList":[{"name":"Apple-Iphone6-1.1MqlgA==","time":41101,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-Iphone5-1.GgrI3w==","time":3312,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1.C4KP1Q==","time":3870,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1.R3Z2qA==","time":3144,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone6-1 ios (4 left)

2016-01-05T10:24:06.362Z - info: Received results for {"name:":"Apple-IpadAir2-1","time":53806,"result":"OK","sendList":[{"name":"Apple-Iphone5-1.+hwmKw==","time":41346,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-Iphone5-1.GgrI3w==","time":4804,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1.DQd5Sw==","time":3605,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1.R3Z2qA==","time":3873,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-IpadAir2-1 ios (3 left)

2016-01-05T10:24:06.365Z - info: Received results for {"name:":"Apple-Iphone5-1","time":53569,"result":"OK","sendList":[{"name":"Apple-Iphone5-1.+hwmKw==","time":41328,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-IpadAir2-1.C4KP1Q==","time":4723,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1.DQd5Sw==","time":3555,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1.R3Z2qA==","time":3716,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone5-1 ios (2 left)

2016-01-05T10:24:49.364Z - info: Received results for {"name:":"Apple-Iphone5s-1","time":95953,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1.Jzs4Xw==","time":40287,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-IpadAir2-1.C4KP1Q==","time":44277,"result":"OK","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1.GgrI3w==","time":4568,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1.DQd5Sw==","time":5796,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone5s-1 ios (1 left)

2016-01-05T10:24:49.366Z - info: All test data retrieved for testSendData.js (ios)

2016-01-05T10:24:49.370Z - info: Remaining tests: %s ios=[]

2016-01-05T10:24:49.372Z - info: ALL DONE !!!

{ 'name:': 'Apple-Iphone5-1',
  time: 1126,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1.o3kBVg==',
       peerAvailable: true,
       time: 1124 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 2245,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5s-1.Jzs4Xw==',
       peerAvailable: true,
       time: 2243 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 1098,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1.+hwmKw==',
       peerAvailable: true,
       time: 1096 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 1310,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1.+hwmKw==',
       peerAvailable: true,
       time: 1308 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 53569,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.+hwmKw==',
       time: 41328,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.C4KP1Q==',
       time: 4723,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.DQd5Sw==',
       time: 3555,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.R3Z2qA==',
       time: 3716,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 51625,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1.1MqlgA==',
       time: 41101,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.GgrI3w==',
       time: 3312,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1.C4KP1Q==',
       time: 3870,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.R3Z2qA==',
       time: 3144,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 53806,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.+hwmKw==',
       time: 41346,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.GgrI3w==',
       time: 4804,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.DQd5Sw==',
       time: 3605,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.R3Z2qA==',
       time: 3873,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 95953,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5s-1.Jzs4Xw==',
       time: 40287,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.C4KP1Q==',
       time: 44277,
       result: 'OK',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.GgrI3w==',
       time: 4568,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.DQd5Sw==',
       time: 5796,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

--------------- test report ---------------------
--------------- Apple-Iphone5-1 --------------------- : 1

peersList : 100% : 1124 ms, 99% : 1124 ms, 95 : 1124 ms, 90% : 1124 ms.

Result count 1, range 1124 ms to  1124 ms.

sendList : 100% : 4723 ms, 99% : 4723 ms, 95 : 4723 ms, 90% : 4723 ms.

Average data rate: 0.025 MB/s

Result count 3, range 3555 ms to  4723 ms.

sendList failed peers count : 1 [25 %]

- Peer ID : Apple-Iphone5-1.+hwmKw==, Tried : 5

sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1 --------------------- : 2

peersList : 100% : 2243 ms, 99% : 2243 ms, 95 : 2243 ms, 90% : 2243 ms.
Result count 1, range 2243 ms to  2243 ms.

sendList : 100% : 3870 ms, 99% : 3870 ms, 95 : 3870 ms, 90% : 3870 ms.

Average data rate: 0.029 MB/s
Result count 3, range 3144 ms to  3870 ms.
sendList failed peers count : 1 [25 %]

- Peer ID : Apple-Iphone6-1.1MqlgA==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Apple-IpadAir2-1 --------------------- : 3
peersList : 100% : 1096 ms, 99% : 1096 ms, 95 : 1096 ms, 90% : 1096 ms.
Result count 1, range 1096 ms to  1096 ms.

sendList : 100% : 4804 ms, 99% : 4804 ms, 95 : 4804 ms, 90% : 4804 ms.
Average data rate: 0.024 MB/s

Result count 3, range 3605 ms to  4804 ms.
sendList failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone5-1.+hwmKw==, Tried : 5

sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5s-1 --------------------- : 4
peersList : 100% : 1308 ms, 99% : 1308 ms, 95 : 1308 ms, 90% : 1308 ms.
Result count 1, range 1308 ms to  1308 ms.

sendList : 100% : 44277 ms, 99% : 44277 ms, 95 : 44277 ms, 90% : 44277 ms.
Average data rate: 0.005 MB/s
Result count 3, range 4568 ms to  44277 ms.

sendList failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone5s-1.Jzs4Xw==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Combined ---------------------

peersList : 100% : 2243 ms, 99% : 2243 ms, 95 : 2243 ms, 90% : 2243 ms.

sendList : 100% : 44277 ms, 99% : 44277 ms, 95 : 5796 ms, 90% : 5796 ms.
Average data rate: 0.013 MB/s

--------------- end of test report ---------------------

2016-01-05T10:24:49.496Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1.o3kBVg==, peerAvailable=true, time=1124], sendList=[name=Apple-Iphone6-1.DQd5Sw==, time=3555, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5s-1.R3Z2qA==, time=3716, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.C4KP1Q==, time=4723, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone5-1.+hwmKw==, time=41328, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5s-1.Jzs4Xw==, peerAvailable=true, time=2243], sendList=[name=Apple-Iphone5s-1.R3Z2qA==, time=3144, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1.GgrI3w==, time=3312, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.C4KP1Q==, time=3870, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone6-1.1MqlgA==, time=41101, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1.+hwmKw==, peerAvailable=true, time=1096], sendList=[name=Apple-Iphone6-1.DQd5Sw==, time=3605, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5s-1.R3Z2qA==, time=3873, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1.GgrI3w==, time=4804, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone5-1.+hwmKw==, time=41346, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1.+hwmKw==, peerAvailable=true, time=1308], sendList=[name=Apple-Iphone5-1.GgrI3w==, time=4568, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone6-1.DQd5Sw==, time=5796, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.C4KP1Q==, time=44277, result=OK, connections=5, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone5s-1.Jzs4Xw==, time=40287, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[]

2016-01-05T10:24:49.506Z - debug: end to Apple-Iphone5-1

2016-01-05T10:24:49.508Z - debug: end to Apple-Iphone6-1

2016-01-05T10:24:49.509Z - debug: end to Apple-IpadAir2-1

2016-01-05T10:24:49.511Z - debug: end to Apple-Iphone5s-1

2016-01-05T10:24:52.471Z - debug: Socket disconnected: transport close 7 (Apple-IpadAir2-1)

2016-01-05T10:24:53.240Z - debug: Socket disconnected: transport close 12 (Apple-Iphone5s-1)

2016-01-05T10:24:53.632Z - debug: Socket disconnected: transport close 3 (Apple-Iphone5-1)

2016-01-05T10:25:05.563Z - info: Start timeout elapsed for platform: android
2016-01-05T10:25:05.565Z - info: Starting perf test run for platform: android
2016-01-05T10:25:05.565Z - info: Using devices:
2016-01-05T10:25:05.566Z - info: A3-1
2016-01-05T10:25:05.566Z - info: G4-1
2016-01-05T10:25:05.567Z - info: A5-1
2016-01-05T10:25:05.567Z - info: Note4-1
2016-01-05T10:25:05.568Z - info: Thali Test (Galaxy A5)
2016-01-05T10:25:05.568Z - info: Thali Test (Galaxy A3)
2016-01-05T10:25:05.569Z - info: Thali Test (Galaxy S5)
2016-01-05T10:25:05.569Z - info: G3-1
2016-01-05T10:25:05.570Z - info: G3s-1

2016-01-05T10:25:05.570Z - info: Nexus 5
2016-01-05T10:25:05.571Z - info: HTC One M8s

2016-01-05T10:25:05.572Z - info: S5-1

2016-01-05T10:25:05.573Z - info: XT1072

2016-01-05T10:25:05.574Z - info: Starting test: with 13 devices (android)

2016-01-05T10:25:07.834Z - info: Received results for {"name:":"XT1072","time":1983,"result":"OK","peersList":[{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":1979}]} XT1072 android (13 left)

2016-01-05T10:25:08.013Z - info: Received results for {"name:":"A3-1","time":2081,"result":"OK","peersList":[{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":2078}]} A3-1 android (12 left)

2016-01-05T10:25:08.183Z - debug: Socket disconnected: transport close 0 (Apple-Iphone6-1)

2016-01-05T10:25:08.251Z - info: Received results for {"name:":"G3s-1","time":2405,"result":"OK","peersList":[{"peerName":"Nexus 5","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":true,"time":2404}]} G3s-1 android (11 left)

2016-01-05T10:25:08.665Z - info: Received results for {"name:":"HTC One M8s","time":2855,"result":"OK","peersList":[{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":2853}]} HTC One M8s android (10 left)

2016-01-05T10:25:09.103Z - info: Received results for {"name:":"Thali Test (Galaxy A3)","time":3309,"result":"OK","peersList":[{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":3308}]} Thali Test (Galaxy A3) android (9 left)

2016-01-05T10:25:09.568Z - info: server timeout for test: testFindPeers.js (ios)

2016-01-05T10:25:09.569Z - info: All test data retrieved for testFindPeers.js (ios)

2016-01-05T10:25:09.571Z - info: Remaining tests: %s ios=[], android=[testFindPeers.js, testSendData.js]

2016-01-05T10:25:09.574Z - info: ALL DONE !!!

{ 'name:': 'Apple-Iphone5-1',
  time: 1126,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1.o3kBVg==',
       peerAvailable: true,
       time: 1124 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 2245,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5s-1.Jzs4Xw==',
       peerAvailable: true,
       time: 2243 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 1098,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1.+hwmKw==',
       peerAvailable: true,
       time: 1096 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 1310,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1.+hwmKw==',
       peerAvailable: true,
       time: 1308 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 53569,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.+hwmKw==',
       time: 41328,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.C4KP1Q==',
       time: 4723,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.DQd5Sw==',
       time: 3555,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.R3Z2qA==',
       time: 3716,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 51625,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1.1MqlgA==',
       time: 41101,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.GgrI3w==',
       time: 3312,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1.C4KP1Q==',
       time: 3870,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.R3Z2qA==',
       time: 3144,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 53806,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.+hwmKw==',
       time: 41346,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.GgrI3w==',
       time: 4804,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.DQd5Sw==',
       time: 3605,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.R3Z2qA==',
       time: 3873,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 95953,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5s-1.Jzs4Xw==',
       time: 40287,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.C4KP1Q==',
       time: 44277,
       result: 'OK',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.GgrI3w==',
       time: 4568,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.DQd5Sw==',
       time: 5796,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 53569,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.+hwmKw==',
       time: 41328,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.C4KP1Q==',
       time: 4723,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.DQd5Sw==',
       time: 3555,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.R3Z2qA==',
       time: 3716,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 51625,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1.1MqlgA==',
       time: 41101,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.GgrI3w==',
       time: 3312,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1.C4KP1Q==',
       time: 3870,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.R3Z2qA==',
       time: 3144,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 53806,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.+hwmKw==',
       time: 41346,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.GgrI3w==',
       time: 4804,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.DQd5Sw==',
       time: 3605,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.R3Z2qA==',
       time: 3873,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 95953,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5s-1.Jzs4Xw==',
       time: 40287,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.C4KP1Q==',
       time: 44277,
       result: 'OK',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.GgrI3w==',
       time: 4568,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.DQd5Sw==',
       time: 5796,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

--------------- test report ---------------------
--------------- Apple-Iphone5-1 --------------------- : 1
peersList : 100% : 1124 ms, 99% : 1124 ms, 95 : 1124 ms, 90% : 1124 ms.

Result count 1, range 1124 ms to  1124 ms.
sendList : 100% : 4723 ms, 99% : 4723 ms, 95 : 4723 ms, 90% : 4723 ms.
Average data rate: 0.025 MB/s

Result count 6, range 3555 ms to  4723 ms.
sendList failed peers count : 2 [25 %]
- Peer ID : Apple-Iphone5-1.+hwmKw==, Tried : 5
- Peer ID : Apple-Iphone5-1.+hwmKw==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1 --------------------- : 2
peersList : 100% : 2243 ms, 99% : 2243 ms, 95 : 2243 ms, 90% : 2243 ms.
Result count 1, range 2243 ms to  2243 ms.
sendList : 100% : 3870 ms, 99% : 3870 ms, 95 : 3870 ms, 90% : 3870 ms.
Average data rate: 0.029 MB/s
Result count 6, range 3144 ms to  3870 ms.
sendList failed peers count : 2 [25 %]
- Peer ID : Apple-Iphone6-1.1MqlgA==, Tried : 5
- Peer ID : Apple-Iphone6-1.1MqlgA==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-IpadAir2-1 --------------------- : 3
peersList : 100% : 1096 ms, 99% : 1096 ms, 95 : 1096 ms, 90% : 1096 ms.
Result count 1, range 1096 ms to  1096 ms.
sendList : 100% : 4804 ms, 99% : 4804 ms, 95 : 4804 ms, 90% : 4804 ms.
Average data rate: 0.024 MB/s
Result count 6, range 3605 ms to  4804 ms.
sendList failed peers count : 2 [25 %]
- Peer ID : Apple-Iphone5-1.+hwmKw==, Tried : 5
- Peer ID : Apple-Iphone5-1.+hwmKw==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5s-1 --------------------- : 4
peersList : 100% : 1308 ms, 99% : 1308 ms, 95 : 1308 ms, 90% : 1308 ms.
Result count 1, range 1308 ms to  1308 ms.
sendList : 100% : 44277 ms, 99% : 44277 ms, 95 : 44277 ms, 90% : 44277 ms.
Average data rate: 0.005 MB/s
Result count 6, range 4568 ms to  44277 ms.
sendList failed peers count : 2 [25 %]
- Peer ID : Apple-Iphone5s-1.Jzs4Xw==, Tried : 5
- Peer ID : Apple-Iphone5s-1.Jzs4Xw==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------
peersList : 100% : 2243 ms, 99% : 2243 ms, 95 : 2243 ms, 90% : 2243 ms.
sendList : 100% : 44277 ms, 99% : 44277 ms, 95 : 44277 ms, 90% : 5796 ms.
Average data rate: 0.013 MB/s
--------------- end of test report ---------------------
2016-01-05T10:25:09.703Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1.o3kBVg==, peerAvailable=true, time=1124], sendList=[name=Apple-Iphone6-1.DQd5Sw==, time=3555, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1"]["sendList"][0], name=Apple-Iphone5s-1.R3Z2qA==, time=3716, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1"]["sendList"][2], name=Apple-IpadAir2-1.C4KP1Q==, time=4723, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1"]["sendList"][4]], failedPeer=[name=Apple-Iphone5-1.+hwmKw==, time=41328, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone5-1"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5s-1.Jzs4Xw==, peerAvailable=true, time=2243], sendList=[name=Apple-Iphone5s-1.R3Z2qA==, time=3144, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1"]["sendList"][0], name=Apple-Iphone5-1.GgrI3w==, time=3312, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1"]["sendList"][2], name=Apple-IpadAir2-1.C4KP1Q==, time=3870, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1"]["sendList"][4]], failedPeer=[name=Apple-Iphone6-1.1MqlgA==, time=41101, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone6-1"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1.+hwmKw==, peerAvailable=true, time=1096], sendList=[name=Apple-Iphone6-1.DQd5Sw==, time=3605, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1"]["sendList"][0], name=Apple-Iphone5s-1.R3Z2qA==, time=3873, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1"]["sendList"][2], name=Apple-Iphone5-1.GgrI3w==, time=4804, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1"]["sendList"][4]], failedPeer=[name=Apple-Iphone5-1.+hwmKw==, time=41346, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-IpadAir2-1"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1.+hwmKw==, peerAvailable=true, time=1308], sendList=[name=Apple-Iphone5-1.GgrI3w==, time=4568, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1"]["sendList"][0], name=Apple-Iphone6-1.DQd5Sw==, time=5796, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1"]["sendList"][2], name=Apple-IpadAir2-1.C4KP1Q==, time=44277, result=OK, connections=5, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1"]["sendList"][4]], failedPeer=[name=Apple-Iphone5s-1.Jzs4Xw==, time=40287, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone5s-1"]["sendError"]["failedPeer"][0]], notTriedList=[]
2016-01-05T10:25:09.710Z - debug: end to Apple-Iphone5-1
2016-01-05T10:25:09.711Z - debug: end to Apple-Iphone6-1
2016-01-05T10:25:09.712Z - debug: end to Apple-IpadAir2-1
2016-01-05T10:25:09.713Z - debug: end to Apple-Iphone5s-1

2016-01-05T10:25:10.114Z - info: Received results for {"name:":"Thali Test (Galaxy A5)","time":4308,"result":"OK","peersList":[{"peerName":"Note4-1","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":4307}]} Thali Test (Galaxy A5) android (8 left)

2016-01-05T10:25:12.105Z - info: server timeout for test: testSendData.js (ios)
2016-01-05T10:25:12.106Z - info: All test data retrieved for testSendData.js (ios)

2016-01-05T10:25:12.107Z - info: Remaining tests: %s ios=[], android=[testFindPeers.js, testSendData.js]
2016-01-05T10:25:12.111Z - info: ALL DONE !!!

{ 'name:': 'Apple-Iphone5-1',
  time: 1126,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1.o3kBVg==',
       peerAvailable: true,
       time: 1124 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 2245,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5s-1.Jzs4Xw==',
       peerAvailable: true,
       time: 2243 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 1098,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1.+hwmKw==',
       peerAvailable: true,
       time: 1096 } ] }
{ 'name:': 'Apple-Iphone5s-1',
  time: 1310,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1.+hwmKw==',
       peerAvailable: true,
       time: 1308 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 53569,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.+hwmKw==',
       time: 41328,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.C4KP1Q==',
       time: 4723,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.DQd5Sw==',
       time: 3555,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.R3Z2qA==',
       time: 3716,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 51625,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1.1MqlgA==',
       time: 41101,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.GgrI3w==',
       time: 3312,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1.C4KP1Q==',
       time: 3870,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.R3Z2qA==',
       time: 3144,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 53806,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.+hwmKw==',
       time: 41346,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.GgrI3w==',
       time: 4804,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.DQd5Sw==',
       time: 3605,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.R3Z2qA==',
       time: 3873,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 95953,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5s-1.Jzs4Xw==',
       time: 40287,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.C4KP1Q==',
       time: 44277,
       result: 'OK',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.GgrI3w==',
       time: 4568,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.DQd5Sw==',
       time: 5796,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 53569,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.+hwmKw==',
       time: 41328,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.C4KP1Q==',
       time: 4723,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.DQd5Sw==',
       time: 3555,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.R3Z2qA==',
       time: 3716,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 51625,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1.1MqlgA==',
       time: 41101,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.GgrI3w==',
       time: 3312,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1.C4KP1Q==',
       time: 3870,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.R3Z2qA==',
       time: 3144,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 53806,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.+hwmKw==',
       time: 41346,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.GgrI3w==',
       time: 4804,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.DQd5Sw==',
       time: 3605,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.R3Z2qA==',
       time: 3873,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 95953,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5s-1.Jzs4Xw==',
       time: 40287,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.C4KP1Q==',
       time: 44277,
       result: 'OK',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.GgrI3w==',
       time: 4568,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.DQd5Sw==',
       time: 5796,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 53569,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.+hwmKw==',
       time: 41328,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.C4KP1Q==',
       time: 4723,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.DQd5Sw==',
       time: 3555,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.R3Z2qA==',
       time: 3716,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 51625,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1.1MqlgA==',
       time: 41101,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.GgrI3w==',
       time: 3312,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1.C4KP1Q==',
       time: 3870,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.R3Z2qA==',
       time: 3144,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 53806,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.+hwmKw==',
       time: 41346,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.GgrI3w==',
       time: 4804,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.DQd5Sw==',
       time: 3605,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.R3Z2qA==',
       time: 3873,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 95953,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5s-1.Jzs4Xw==',
       time: 40287,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.C4KP1Q==',
       time: 44277,
       result: 'OK',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.GgrI3w==',
       time: 4568,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.DQd5Sw==',
       time: 5796,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

--------------- test report ---------------------
--------------- Apple-Iphone5-1 --------------------- : 1
peersList : 100% : 1124 ms, 99% : 1124 ms, 95 : 1124 ms, 90% : 1124 ms.
Result count 1, range 1124 ms to  1124 ms.

sendList : 100% : 4723 ms, 99% : 4723 ms, 95 : 4723 ms, 90% : 4723 ms.
Average data rate: 0.025 MB/s
Result count 9, range 3555 ms to  4723 ms.

sendList failed peers count : 3 [25 %]
- Peer ID : Apple-Iphone5-1.+hwmKw==, Tried : 5
- Peer ID : Apple-Iphone5-1.+hwmKw==, Tried : 5
- Peer ID : Apple-Iphone5-1.+hwmKw==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1 --------------------- : 2
peersList : 100% : 2243 ms, 99% : 2243 ms, 95 : 2243 ms, 90% : 2243 ms.
Result count 1, range 2243 ms to  2243 ms.
sendList : 100% : 3870 ms, 99% : 3870 ms, 95 : 3870 ms, 90% : 3870 ms.
Average data rate: 0.029 MB/s
Result count 9, range 3144 ms to  3870 ms.
sendList failed peers count : 3 [25 %]
- Peer ID : Apple-Iphone6-1.1MqlgA==, Tried : 5
- Peer ID : Apple-Iphone6-1.1MqlgA==, Tried : 5
- Peer ID : Apple-Iphone6-1.1MqlgA==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-IpadAir2-1 --------------------- : 3
peersList : 100% : 1096 ms, 99% : 1096 ms, 95 : 1096 ms, 90% : 1096 ms.
Result count 1, range 1096 ms to  1096 ms.
sendList : 100% : 4804 ms, 99% : 4804 ms, 95 : 4804 ms, 90% : 4804 ms.

Average data rate: 0.024 MB/s

Result count 9, range 3605 ms to  4804 ms.
sendList failed peers count : 3 [25 %]
- Peer ID : Apple-Iphone5-1.+hwmKw==, Tried : 5
- Peer ID : Apple-Iphone5-1.+hwmKw==, Tried : 5

- Peer ID : Apple-Iphone5-1.+hwmKw==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5s-1 --------------------- : 4

peersList : 100% : 1308 ms, 99% : 1308 ms, 95 : 1308 ms, 90% : 1308 ms.
Result count 1, range 1308 ms to  1308 ms.
sendList : 100% : 44277 ms, 99% : 44277 ms, 95 : 44277 ms, 90% : 44277 ms.

Average data rate: 0.005 MB/s
Result count 9, range 4568 ms to  44277 ms.
sendList failed peers count : 3 [25 %]

- Peer ID : Apple-Iphone5s-1.Jzs4Xw==, Tried : 5
- Peer ID : Apple-Iphone5s-1.Jzs4Xw==, Tried : 5
- Peer ID : Apple-Iphone5s-1.Jzs4Xw==, Tried : 5

sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------

peersList : 100% : 2243 ms, 99% : 2243 ms, 95 : 2243 ms, 90% : 2243 ms.

sendList : 100% : 44277 ms, 99% : 44277 ms, 95 : 44277 ms, 90% : 5796 ms.

Average data rate: 0.013 MB/s
--------------- end of test report ---------------------

2016-01-05T10:25:12.251Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1.o3kBVg==, peerAvailable=true, time=1124], sendList=[name=Apple-Iphone6-1.DQd5Sw==, time=3555, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1"]["sendList"][0], $ref=$["Apple-Iphone5-1"]["sendList"][0], name=Apple-Iphone5s-1.R3Z2qA==, time=3716, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1"]["sendList"][3], $ref=$["Apple-Iphone5-1"]["sendList"][3], name=Apple-IpadAir2-1.C4KP1Q==, time=4723, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1"]["sendList"][6], $ref=$["Apple-Iphone5-1"]["sendList"][6]], failedPeer=[name=Apple-Iphone5-1.+hwmKw==, time=41328, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone5-1"]["sendError"]["failedPeer"][0], $ref=$["Apple-Iphone5-1"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5s-1.Jzs4Xw==, peerAvailable=true, time=2243], sendList=[name=Apple-Iphone5s-1.R3Z2qA==, time=3144, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1"]["sendList"][0], $ref=$["Apple-Iphone6-1"]["sendList"][0], name=Apple-Iphone5-1.GgrI3w==, time=3312, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1"]["sendList"][3], $ref=$["Apple-Iphone6-1"]["sendList"][3], name=Apple-IpadAir2-1.C4KP1Q==, time=3870, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1"]["sendList"][6], $ref=$["Apple-Iphone6-1"]["sendList"][6]], failedPeer=[name=Apple-Iphone6-1.1MqlgA==, time=41101, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone6-1"]["sendError"]["failedPeer"][0], $ref=$["Apple-Iphone6-1"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1.+hwmKw==, peerAvailable=true, time=1096], sendList=[name=Apple-Iphone6-1.DQd5Sw==, time=3605, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1"]["sendList"][0], $ref=$["Apple-IpadAir2-1"]["sendList"][0], name=Apple-Iphone5s-1.R3Z2qA==, time=3873, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1"]["sendList"][3], $ref=$["Apple-IpadAir2-1"]["sendList"][3], name=Apple-Iphone5-1.GgrI3w==, time=4804, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1"]["sendList"][6], $ref=$["Apple-IpadAir2-1"]["sendList"][6]], failedPeer=[name=Apple-Iphone5-1.+hwmKw==, time=41346, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-IpadAir2-1"]["sendError"]["failedPeer"][0], $ref=$["Apple-IpadAir2-1"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1.+hwmKw==, peerAvailable=true, time=1308], sendList=[name=Apple-Iphone5-1.GgrI3w==, time=4568, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1"]["sendList"][0], $ref=$["Apple-Iphone5s-1"]["sendList"][0], name=Apple-Iphone6-1.DQd5Sw==, time=5796, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1"]["sendList"][3], $ref=$["Apple-Iphone5s-1"]["sendList"][3], name=Apple-IpadAir2-1.C4KP1Q==, time=44277, result=OK, connections=5, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1"]["sendList"][6], $ref=$["Apple-Iphone5s-1"]["sendList"][6]], failedPeer=[name=Apple-Iphone5s-1.Jzs4Xw==, time=40287, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone5s-1"]["sendError"]["failedPeer"][0], $ref=$["Apple-Iphone5s-1"]["sendError"]["failedPeer"][0]], notTriedList=[]

2016-01-05T10:25:12.260Z - debug: end to Apple-Iphone5-1

2016-01-05T10:25:12.261Z - debug: end to Apple-Iphone6-1

2016-01-05T10:25:12.263Z - debug: end to Apple-IpadAir2-1

2016-01-05T10:25:12.264Z - debug: end to Apple-Iphone5s-1

2016-01-05T10:25:13.335Z - info: Received results for {"name:":"G3-1","time":2146,"result":"OK","peersList":[{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":2144}]} G3-1 android (7 left)

2016-01-05T10:25:18.610Z - info: Received results for {"name:":"G4-1","time":11653,"result":"OK","peersList":[{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":11649}]} G4-1 android (6 left)

2016-01-05T10:25:20.519Z - info: Received results for {"name:":"Thali Test (Galaxy S5)","time":14668,"result":"OK","peersList":[{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":14663}]} Thali Test (Galaxy S5) android (5 left)

2016-01-05T10:25:25.455Z - info: Received results for {"name:":"S5-1","time":19619,"result":"OK","peersList":[{"peerName":"Note4-1","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":19614}]} S5-1 android (4 left)

2016-01-05T10:25:38.304Z - info: Received results for {"name:":"Note4-1","time":29839,"result":"OK","peersList":[{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":29836}]} Note4-1 android (3 left)

2016-01-05T10:25:46.883Z - info: Received results for {"name:":"A5-1","time":41082,"result":"OK","peersList":[{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":41081}]} A5-1 android (2 left)

2016-01-05T10:26:46.044Z - info: Received results for {"name:":"Nexus 5","time":100052,"result":"TIMEOUT","peersList":[]} Nexus 5 android (1 left)

2016-01-05T10:26:46.045Z - info: All test data retrieved for testFindPeers.js (android)

2016-01-05T10:26:46.066Z - info: Remaining tests: %s ios=[], android=[testSendData.js]

2016-01-05T10:26:46.068Z - info: Continuing to next test: testSendData.js

2016-01-05T10:26:46.069Z - info: Starting test: with 13 devices (android)

2016-01-05T10:27:05.212Z - debug: Socket disconnected: ping timeout 14 (HTC One M8s)

2016-01-05T10:27:05.580Z - info: server timeout for test: testFindPeers.js (android)

2016-01-05T10:27:05.581Z - info: All test data retrieved for testFindPeers.js (android)

2016-01-05T10:27:05.583Z - info: No results from A3-1

2016-01-05T10:27:05.585Z - info: No results from G4-1

2016-01-05T10:27:05.587Z - info: No results from A5-1

2016-01-05T10:27:05.589Z - info: No results from Note4-1

2016-01-05T10:27:05.591Z - info: No results from Thali Test (Galaxy A5)

2016-01-05T10:27:05.598Z - info: No results from Thali Test (Galaxy A3)

2016-01-05T10:27:05.603Z - info: No results from Thali Test (Galaxy S5)

2016-01-05T10:27:05.605Z - info: No results from G3-1

2016-01-05T10:27:05.607Z - info: No results from G3s-1

2016-01-05T10:27:05.610Z - info: No results from Nexus 5

2016-01-05T10:27:05.615Z - info: No results from HTC One M8s

2016-01-05T10:27:05.616Z - info: No results from S5-1

2016-01-05T10:27:05.619Z - info: No results from XT1072

2016-01-05T10:27:05.621Z - info: Remaining tests: %s ios=[], android=[]

2016-01-05T10:27:05.622Z - info: ALL DONE !!!

{ 'name:': 'Apple-Iphone5-1',
  time: 1126,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1.o3kBVg==',
       peerAvailable: true,
       time: 1124 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 2245,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5s-1.Jzs4Xw==',
       peerAvailable: true,
       time: 2243 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 1098,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1.+hwmKw==',
       peerAvailable: true,
       time: 1096 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 1310,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1.+hwmKw==',
       peerAvailable: true,
       time: 1308 } ] }
{ 'name:': 'Apple-Iphone5-1',
  time: 53569,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.+hwmKw==',
       time: 41328,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.C4KP1Q==',
       time: 4723,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.DQd5Sw==',
       time: 3555,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.R3Z2qA==',
       time: 3716,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 51625,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1.1MqlgA==',
       time: 41101,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.GgrI3w==',
       time: 3312,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1.C4KP1Q==',
       time: 3870,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.R3Z2qA==',
       time: 3144,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 53806,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.+hwmKw==',
       time: 41346,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.GgrI3w==',
       time: 4804,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.DQd5Sw==',
       time: 3605,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.R3Z2qA==',
       time: 3873,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 95953,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5s-1.Jzs4Xw==',
       time: 40287,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.C4KP1Q==',
       time: 44277,
       result: 'OK',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.GgrI3w==',
       time: 4568,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.DQd5Sw==',
       time: 5796,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 53569,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.+hwmKw==',
       time: 41328,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.C4KP1Q==',
       time: 4723,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.DQd5Sw==',
       time: 3555,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.R3Z2qA==',
       time: 3716,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 51625,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1.1MqlgA==',
       time: 41101,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.GgrI3w==',
       time: 3312,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1.C4KP1Q==',
       time: 3870,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.R3Z2qA==',
       time: 3144,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 53806,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.+hwmKw==',
       time: 41346,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.GgrI3w==',
       time: 4804,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.DQd5Sw==',
       time: 3605,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.R3Z2qA==',
       time: 3873,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 95953,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5s-1.Jzs4Xw==',
       time: 40287,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.C4KP1Q==',
       time: 44277,
       result: 'OK',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.GgrI3w==',
       time: 4568,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.DQd5Sw==',
       time: 5796,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 53569,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.+hwmKw==',
       time: 41328,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.C4KP1Q==',
       time: 4723,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.DQd5Sw==',
       time: 3555,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.R3Z2qA==',
       time: 3716,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 51625,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1.1MqlgA==',
       time: 41101,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.GgrI3w==',
       time: 3312,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1.C4KP1Q==',
       time: 3870,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.R3Z2qA==',
       time: 3144,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 53806,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.+hwmKw==',
       time: 41346,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.GgrI3w==',
       time: 4804,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.DQd5Sw==',
       time: 3605,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.R3Z2qA==',
       time: 3873,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 95953,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5s-1.Jzs4Xw==',
       time: 40287,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.C4KP1Q==',
       time: 44277,
       result: 'OK',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.GgrI3w==',
       time: 4568,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.DQd5Sw==',
       time: 5796,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'A3-1',
  time: 2081,
  result: 'OK',
  peersList: 
   [ { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 2078 } ] }

{ 'name:': 'G4-1',
  time: 11653,
  result: 'OK',
  peersList: 
   [ { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 11649 } ] }

{ 'name:': 'A5-1',
  time: 41082,
  result: 'OK',
  peersList: 
   [ { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 41081 } ] }

{ 'name:': 'Note4-1',
  time: 29839,
  result: 'OK',
  peersList: 
   [ { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 29836 } ] }

{ 'name:': 'Thali Test (Galaxy A5)',
  time: 4308,
  result: 'OK',
  peersList: 
   [ { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 4307 } ] }

{ 'name:': 'Thali Test (Galaxy A3)',
  time: 3309,
  result: 'OK',
  peersList: 
   [ { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 3308 } ] }

{ 'name:': 'Thali Test (Galaxy S5)',
  time: 14668,
  result: 'OK',
  peersList: 
   [ { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 14663 } ] }

{ 'name:': 'G3-1',
  time: 2146,
  result: 'OK',
  peersList: 
   [ { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 2144 } ] }

{ 'name:': 'G3s-1',
  time: 2405,
  result: 'OK',
  peersList: 
   [ { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 2404 } ] }

{ 'name:': 'Nexus 5',
  time: 100052,
  result: 'TIMEOUT',
  peersList: [] }

{ 'name:': 'HTC One M8s',
  time: 2855,
  result: 'OK',
  peersList: 
   [ { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 2853 } ] }

{ 'name:': 'S5-1',
  time: 19619,
  result: 'OK',
  peersList: 
   [ { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 19614 } ] }

{ 'name:': 'XT1072',
  time: 1983,
  result: 'OK',
  peersList: 
   [ { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 1979 } ] }

--------------- test report ---------------------
--------------- Apple-Iphone5-1 --------------------- : 1
peersList : 100% : 1124 ms, 99% : 1124 ms, 95 : 1124 ms, 90% : 1124 ms.
Result count 1, range 1124 ms to  1124 ms.
sendList : 100% : 4723 ms, 99% : 4723 ms, 95 : 4723 ms, 90% : 4723 ms.

Average data rate: 0.025 MB/s
Result count 9, range 3555 ms to  4723 ms.
sendList failed peers count : 3 [25 %]

- Peer ID : Apple-Iphone5-1.+hwmKw==, Tried : 5
- Peer ID : Apple-Iphone5-1.+hwmKw==, Tried : 5

- Peer ID : Apple-Iphone5-1.+hwmKw==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1 --------------------- : 2

peersList : 100% : 2243 ms, 99% : 2243 ms, 95 : 2243 ms, 90% : 2243 ms.
Result count 1, range 2243 ms to  2243 ms.

sendList : 100% : 3870 ms, 99% : 3870 ms, 95 : 3870 ms, 90% : 3870 ms.
Average data rate: 0.029 MB/s
Result count 9, range 3144 ms to  3870 ms.

sendList failed peers count : 3 [25 %]
- Peer ID : Apple-Iphone6-1.1MqlgA==, Tried : 5
- Peer ID : Apple-Iphone6-1.1MqlgA==, Tried : 5

- Peer ID : Apple-Iphone6-1.1MqlgA==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Apple-IpadAir2-1 --------------------- : 3
peersList : 100% : 1096 ms, 99% : 1096 ms, 95 : 1096 ms, 90% : 1096 ms.
Result count 1, range 1096 ms to  1096 ms.

sendList : 100% : 4804 ms, 99% : 4804 ms, 95 : 4804 ms, 90% : 4804 ms.
Average data rate: 0.024 MB/s
Result count 9, range 3605 ms to  4804 ms.

sendList failed peers count : 3 [25 %]
- Peer ID : Apple-Iphone5-1.+hwmKw==, Tried : 5
- Peer ID : Apple-Iphone5-1.+hwmKw==, Tried : 5

- Peer ID : Apple-Iphone5-1.+hwmKw==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5s-1 --------------------- : 4

peersList : 100% : 1308 ms, 99% : 1308 ms, 95 : 1308 ms, 90% : 1308 ms.
Result count 1, range 1308 ms to  1308 ms.
sendList : 100% : 44277 ms, 99% : 44277 ms, 95 : 44277 ms, 90% : 44277 ms.

Average data rate: 0.005 MB/s
Result count 9, range 4568 ms to  44277 ms.
sendList failed peers count : 3 [25 %]

- Peer ID : Apple-Iphone5s-1.Jzs4Xw==, Tried : 5
- Peer ID : Apple-Iphone5s-1.Jzs4Xw==, Tried : 5
- Peer ID : Apple-Iphone5s-1.Jzs4Xw==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- A3-1 --------------------- : 5
peersList : 100% : 2078 ms, 99% : 2078 ms, 95 : 2078 ms, 90% : 2078 ms.

Result count 1, range 2078 ms to  2078 ms.
--------------- G4-1 --------------------- : 6
peersList : 100% : 11649 ms, 99% : 11649 ms, 95 : 11649 ms, 90% : 11649 ms.

Result count 1, range 11649 ms to  11649 ms.
--------------- A5-1 --------------------- : 7
peersList : 100% : 41081 ms, 99% : 41081 ms, 95 : 41081 ms, 90% : 41081 ms.

Result count 1, range 41081 ms to  41081 ms.
--------------- Note4-1 --------------------- : 8
peersList : 100% : 29836 ms, 99% : 29836 ms, 95 : 29836 ms, 90% : 29836 ms.

Result count 1, range 29836 ms to  29836 ms.
--------------- Thali Test (Galaxy A5) --------------------- : 9
peersList : 100% : 4307 ms, 99% : 4307 ms, 95 : 4307 ms, 90% : 4307 ms.
Result count 1, range 4307 ms to  4307 ms.

--------------- Thali Test (Galaxy A3) --------------------- : 10
peersList : 100% : 3308 ms, 99% : 3308 ms, 95 : 3308 ms, 90% : 3308 ms.
Result count 1, range 3308 ms to  3308 ms.

--------------- Thali Test (Galaxy S5) --------------------- : 11
peersList : 100% : 14663 ms, 99% : 14663 ms, 95 : 14663 ms, 90% : 14663 ms.
Result count 1, range 14663 ms to  14663 ms.

--------------- G3-1 --------------------- : 12
peersList : 100% : 2144 ms, 99% : 2144 ms, 95 : 2144 ms, 90% : 2144 ms.
Result count 1, range 2144 ms to  2144 ms.

--------------- G3s-1 --------------------- : 13
peersList : 100% : 2404 ms, 99% : 2404 ms, 95 : 2404 ms, 90% : 2404 ms.
Result count 1, range 2404 ms to  2404 ms.

--------------- Nexus 5 --------------------- : 14

peersList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Results list does not contain any items
--------------- HTC One M8s --------------------- : 15

peersList : 100% : 2853 ms, 99% : 2853 ms, 95 : 2853 ms, 90% : 2853 ms.
Result count 1, range 2853 ms to  2853 ms.

--------------- S5-1 --------------------- : 16
peersList : 100% : 19614 ms, 99% : 19614 ms, 95 : 19614 ms, 90% : 19614 ms.
Result count 1, range 19614 ms to  19614 ms.

--------------- XT1072 --------------------- : 17
peersList : 100% : 1979 ms, 99% : 1979 ms, 95 : 1979 ms, 90% : 1979 ms.
Result count 1, range 1979 ms to  1979 ms.
--------------- Combined ---------------------

peersList : 100% : 41081 ms, 99% : 41081 ms, 95 : 29836 ms, 90% : 19614 ms.

sendList : 100% : 44277 ms, 99% : 44277 ms, 95 : 44277 ms, 90% : 5796 ms.

Average data rate: 0.013 MB/s
--------------- end of test report ---------------------

2016-01-05T10:27:05.924Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1.o3kBVg==, peerAvailable=true, time=1124], sendList=[name=Apple-Iphone6-1.DQd5Sw==, time=3555, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1"]["sendList"][0], $ref=$["Apple-Iphone5-1"]["sendList"][0], name=Apple-Iphone5s-1.R3Z2qA==, time=3716, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1"]["sendList"][3], $ref=$["Apple-Iphone5-1"]["sendList"][3], name=Apple-IpadAir2-1.C4KP1Q==, time=4723, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1"]["sendList"][6], $ref=$["Apple-Iphone5-1"]["sendList"][6]], failedPeer=[name=Apple-Iphone5-1.+hwmKw==, time=41328, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone5-1"]["sendError"]["failedPeer"][0], $ref=$["Apple-Iphone5-1"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5s-1.Jzs4Xw==, peerAvailable=true, time=2243], sendList=[name=Apple-Iphone5s-1.R3Z2qA==, time=3144, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1"]["sendList"][0], $ref=$["Apple-Iphone6-1"]["sendList"][0], name=Apple-Iphone5-1.GgrI3w==, time=3312, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1"]["sendList"][3], $ref=$["Apple-Iphone6-1"]["sendList"][3], name=Apple-IpadAir2-1.C4KP1Q==, time=3870, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1"]["sendList"][6], $ref=$["Apple-Iphone6-1"]["sendList"][6]], failedPeer=[name=Apple-Iphone6-1.1MqlgA==, time=41101, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone6-1"]["sendError"]["failedPeer"][0], $ref=$["Apple-Iphone6-1"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1.+hwmKw==, peerAvailable=true, time=1096], sendList=[name=Apple-Iphone6-1.DQd5Sw==, time=3605, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1"]["sendList"][0], $ref=$["Apple-IpadAir2-1"]["sendList"][0], name=Apple-Iphone5s-1.R3Z2qA==, time=3873, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1"]["sendList"][3], $ref=$["Apple-IpadAir2-1"]["sendList"][3], name=Apple-Iphone5-1.GgrI3w==, time=4804, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1"]["sendList"][6], $ref=$["Apple-IpadAir2-1"]["sendList"][6]], failedPeer=[name=Apple-Iphone5-1.+hwmKw==, time=41346, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-IpadAir2-1"]["sendError"]["failedPeer"][0], $ref=$["Apple-IpadAir2-1"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1.+hwmKw==, peerAvailable=true, time=1308], sendList=[name=Apple-Iphone5-1.GgrI3w==, time=4568, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1"]["sendList"][0], $ref=$["Apple-Iphone5s-1"]["sendList"][0], name=Apple-Iphone6-1.DQd5Sw==, time=5796, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1"]["sendList"][3], $ref=$["Apple-Iphone5s-1"]["sendList"][3], name=Apple-IpadAir2-1.C4KP1Q==, time=44277, result=OK, connections=5, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1"]["sendList"][6], $ref=$["Apple-Iphone5s-1"]["sendList"][6]], failedPeer=[name=Apple-Iphone5s-1.Jzs4Xw==, time=40287, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone5s-1"]["sendError"]["failedPeer"][0], $ref=$["Apple-Iphone5s-1"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=2078], peersList=[peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=11649], peersList=[peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=41081], peersList=[peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=29836], peersList=[peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=4307], peersList=[peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=3308], peersList=[peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=14663], peersList=[peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=2144], peersList=[peerName=Nexus 5, peerIdentifier=34:FC:EF:11:AE:67, peerAvailable=true, time=2404], peersList=[], peersList=[peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=2853], peersList=[peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=19614], peersList=[peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=1979]

2016-01-05T10:27:05.934Z - debug: end to A3-1

2016-01-05T10:27:05.936Z - debug: end to G4-1

2016-01-05T10:27:05.938Z - debug: end to A5-1

2016-01-05T10:27:05.939Z - debug: end to Note4-1

2016-01-05T10:27:05.940Z - debug: end to Thali Test (Galaxy A5)

2016-01-05T10:27:05.942Z - debug: end to Thali Test (Galaxy A3)

2016-01-05T10:27:05.943Z - debug: end to Thali Test (Galaxy S5)

2016-01-05T10:27:05.944Z - debug: end to G3-1

2016-01-05T10:27:05.948Z - debug: end to G3s-1

2016-01-05T10:27:05.951Z - debug: end to Nexus 5

2016-01-05T10:27:05.953Z - debug: end to HTC One M8s

2016-01-05T10:27:05.954Z - debug: end to S5-1

2016-01-05T10:27:05.955Z - debug: end to XT1072

2016-01-05T10:27:06.881Z - debug: Socket disconnected: transport close 13 (Nexus 5)

2016-01-05T10:27:06.888Z - debug: Socket disconnected: transport close 5 (Note4-1)

2016-01-05T10:27:07.008Z - debug: Socket disconnected: transport close 16 (XT1072)

2016-01-05T10:27:07.067Z - debug: Socket disconnected: transport close 4 (A5-1)

2016-01-05T10:27:07.115Z - debug: Socket disconnected: transport close 8 (Thali Test (Galaxy A3))

2016-01-05T10:27:07.125Z - debug: Socket disconnected: transport close 15 (S5-1)

2016-01-05T10:27:07.136Z - debug: Socket disconnected: transport close 1 (A3-1)

2016-01-05T10:27:07.271Z - debug: Socket disconnected: transport close 2 (G4-1)

2016-01-05T10:27:07.353Z - debug: Socket disconnected: transport close 6 (Thali Test (Galaxy A5))

2016-01-05T10:27:07.531Z - debug: Socket disconnected: transport close 10 (G3s-1)

2016-01-05T10:27:07.654Z - debug: Socket disconnected: transport close 11 (G3-1)

2016-01-05T10:27:07.795Z - debug: Socket disconnected: transport close 9 (Thali Test (Galaxy S5))

2016-01-05T10:28:46.169Z - info: server timeout for test: testSendData.js (android)

2016-01-05T10:28:46.170Z - info: All test data retrieved for testSendData.js (android)
2016-01-05T10:28:46.170Z - info: No results from A3-1

2016-01-05T10:28:46.171Z - info: No results from G4-1
2016-01-05T10:28:46.172Z - info: No results from A5-1

2016-01-05T10:28:46.173Z - info: No results from Note4-1

2016-01-05T10:28:46.174Z - info: No results from Thali Test (Galaxy A5)

2016-01-05T10:28:46.175Z - info: No results from Thali Test (Galaxy A3)

2016-01-05T10:28:46.176Z - info: No results from Thali Test (Galaxy S5)

2016-01-05T10:28:46.177Z - info: No results from G3-1

2016-01-05T10:28:46.178Z - info: No results from G3s-1

2016-01-05T10:28:46.179Z - info: No results from Nexus 5

2016-01-05T10:28:46.180Z - info: No results from HTC One M8s

2016-01-05T10:28:46.181Z - info: No results from S5-1

2016-01-05T10:28:46.182Z - info: No results from XT1072

2016-01-05T10:28:46.183Z - info: Remaining tests: %s ios=[], android=[]

2016-01-05T10:28:46.184Z - info: ALL DONE !!!

{ 'name:': 'Apple-Iphone5-1',
  time: 1126,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1.o3kBVg==',
       peerAvailable: true,
       time: 1124 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 2245,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5s-1.Jzs4Xw==',
       peerAvailable: true,
       time: 2243 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 1098,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1.+hwmKw==',
       peerAvailable: true,
       time: 1096 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 1310,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1.+hwmKw==',
       peerAvailable: true,
       time: 1308 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 53569,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.+hwmKw==',
       time: 41328,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.C4KP1Q==',
       time: 4723,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.DQd5Sw==',
       time: 3555,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.R3Z2qA==',
       time: 3716,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 51625,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1.1MqlgA==',
       time: 41101,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.GgrI3w==',
       time: 3312,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1.C4KP1Q==',
       time: 3870,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.R3Z2qA==',
       time: 3144,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 53806,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.+hwmKw==',
       time: 41346,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.GgrI3w==',
       time: 4804,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.DQd5Sw==',
       time: 3605,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.R3Z2qA==',
       time: 3873,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 95953,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5s-1.Jzs4Xw==',
       time: 40287,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.C4KP1Q==',
       time: 44277,
       result: 'OK',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.GgrI3w==',
       time: 4568,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.DQd5Sw==',
       time: 5796,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 53569,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.+hwmKw==',
       time: 41328,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.C4KP1Q==',
       time: 4723,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.DQd5Sw==',
       time: 3555,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.R3Z2qA==',
       time: 3716,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 51625,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1.1MqlgA==',
       time: 41101,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.GgrI3w==',
       time: 3312,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1.C4KP1Q==',
       time: 3870,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.R3Z2qA==',
       time: 3144,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 53806,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.+hwmKw==',
       time: 41346,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.GgrI3w==',
       time: 4804,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.DQd5Sw==',
       time: 3605,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.R3Z2qA==',
       time: 3873,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 95953,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5s-1.Jzs4Xw==',
       time: 40287,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.C4KP1Q==',
       time: 44277,
       result: 'OK',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.GgrI3w==',
       time: 4568,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.DQd5Sw==',
       time: 5796,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 53569,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.+hwmKw==',
       time: 41328,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.C4KP1Q==',
       time: 4723,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.DQd5Sw==',
       time: 3555,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.R3Z2qA==',
       time: 3716,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 51625,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1.1MqlgA==',
       time: 41101,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.GgrI3w==',
       time: 3312,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1.C4KP1Q==',
       time: 3870,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.R3Z2qA==',
       time: 3144,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 53806,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.+hwmKw==',
       time: 41346,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.GgrI3w==',
       time: 4804,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.DQd5Sw==',
       time: 3605,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.R3Z2qA==',
       time: 3873,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 95953,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5s-1.Jzs4Xw==',
       time: 40287,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.C4KP1Q==',
       time: 44277,
       result: 'OK',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.GgrI3w==',
       time: 4568,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.DQd5Sw==',
       time: 5796,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'A3-1',
  time: 2081,
  result: 'OK',
  peersList: 
   [ { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 2078 } ] }

{ 'name:': 'G4-1',
  time: 11653,
  result: 'OK',
  peersList: 
   [ { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 11649 } ] }

{ 'name:': 'A5-1',
  time: 41082,
  result: 'OK',
  peersList: 
   [ { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 41081 } ] }

{ 'name:': 'Note4-1',
  time: 29839,
  result: 'OK',
  peersList: 
   [ { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 29836 } ] }

{ 'name:': 'Thali Test (Galaxy A5)',
  time: 4308,
  result: 'OK',
  peersList: 
   [ { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 4307 } ] }

{ 'name:': 'Thali Test (Galaxy A3)',
  time: 3309,
  result: 'OK',
  peersList: 
   [ { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 3308 } ] }

{ 'name:': 'Thali Test (Galaxy S5)',
  time: 14668,
  result: 'OK',
  peersList: 
   [ { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 14663 } ] }

{ 'name:': 'G3-1',
  time: 2146,
  result: 'OK',
  peersList: 
   [ { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 2144 } ] }

{ 'name:': 'G3s-1',
  time: 2405,
  result: 'OK',
  peersList: 
   [ { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 2404 } ] }

{ 'name:': 'Nexus 5',
  time: 100052,
  result: 'TIMEOUT',
  peersList: [] }

{ 'name:': 'HTC One M8s',
  time: 2855,
  result: 'OK',
  peersList: 
   [ { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 2853 } ] }

{ 'name:': 'S5-1',
  time: 19619,
  result: 'OK',
  peersList: 
   [ { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 19614 } ] }

{ 'name:': 'XT1072',
  time: 1983,
  result: 'OK',
  peersList: 
   [ { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 1979 } ] }

--------------- test report ---------------------
--------------- Apple-Iphone5-1 --------------------- : 1
peersList : 100% : 1124 ms, 99% : 1124 ms, 95 : 1124 ms, 90% : 1124 ms.

Result count 1, range 1124 ms to  1124 ms.
sendList : 100% : 4723 ms, 99% : 4723 ms, 95 : 4723 ms, 90% : 4723 ms.

Average data rate: 0.025 MB/s
Result count 9, range 3555 ms to  4723 ms.
sendList failed peers count : 3 [25 %]

- Peer ID : Apple-Iphone5-1.+hwmKw==, Tried : 5
- Peer ID : Apple-Iphone5-1.+hwmKw==, Tried : 5
- Peer ID : Apple-Iphone5-1.+hwmKw==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone6-1 --------------------- : 2
peersList : 100% : 2243 ms, 99% : 2243 ms, 95 : 2243 ms, 90% : 2243 ms.

Result count 1, range 2243 ms to  2243 ms.
sendList : 100% : 3870 ms, 99% : 3870 ms, 95 : 3870 ms, 90% : 3870 ms.
Average data rate: 0.029 MB/s
Result count 9, range 3144 ms to  3870 ms.

sendList failed peers count : 3 [25 %]
- Peer ID : Apple-Iphone6-1.1MqlgA==, Tried : 5
- Peer ID : Apple-Iphone6-1.1MqlgA==, Tried : 5

- Peer ID : Apple-Iphone6-1.1MqlgA==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-IpadAir2-1 --------------------- : 3

peersList : 100% : 1096 ms, 99% : 1096 ms, 95 : 1096 ms, 90% : 1096 ms.
Result count 1, range 1096 ms to  1096 ms.

sendList : 100% : 4804 ms, 99% : 4804 ms, 95 : 4804 ms, 90% : 4804 ms.
Average data rate: 0.024 MB/s
Result count 9, range 3605 ms to  4804 ms.
sendList failed peers count : 3 [25 %]

- Peer ID : Apple-Iphone5-1.+hwmKw==, Tried : 5
- Peer ID : Apple-Iphone5-1.+hwmKw==, Tried : 5
- Peer ID : Apple-Iphone5-1.+hwmKw==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5s-1 --------------------- : 4
peersList : 100% : 1308 ms, 99% : 1308 ms, 95 : 1308 ms, 90% : 1308 ms.
Result count 1, range 1308 ms to  1308 ms.

sendList : 100% : 44277 ms, 99% : 44277 ms, 95 : 44277 ms, 90% : 44277 ms.
Average data rate: 0.005 MB/s

Result count 9, range 4568 ms to  44277 ms.
sendList failed peers count : 3 [25 %]
- Peer ID : Apple-Iphone5s-1.Jzs4Xw==, Tried : 5
- Peer ID : Apple-Iphone5s-1.Jzs4Xw==, Tried : 5

- Peer ID : Apple-Iphone5s-1.Jzs4Xw==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- A3-1 --------------------- : 5

peersList : 100% : 2078 ms, 99% : 2078 ms, 95 : 2078 ms, 90% : 2078 ms.
Result count 1, range 2078 ms to  2078 ms.
--------------- G4-1 --------------------- : 6

peersList : 100% : 11649 ms, 99% : 11649 ms, 95 : 11649 ms, 90% : 11649 ms.
Result count 1, range 11649 ms to  11649 ms.
--------------- A5-1 --------------------- : 7
peersList : 100% : 41081 ms, 99% : 41081 ms, 95 : 41081 ms, 90% : 41081 ms.

Result count 1, range 41081 ms to  41081 ms.
--------------- Note4-1 --------------------- : 8
peersList : 100% : 29836 ms, 99% : 29836 ms, 95 : 29836 ms, 90% : 29836 ms.

Result count 1, range 29836 ms to  29836 ms.
--------------- Thali Test (Galaxy A5) --------------------- : 9
peersList : 100% : 4307 ms, 99% : 4307 ms, 95 : 4307 ms, 90% : 4307 ms.
Result count 1, range 4307 ms to  4307 ms.

--------------- Thali Test (Galaxy A3) --------------------- : 10
peersList : 100% : 3308 ms, 99% : 3308 ms, 95 : 3308 ms, 90% : 3308 ms.
Result count 1, range 3308 ms to  3308 ms.

--------------- Thali Test (Galaxy S5) --------------------- : 11
peersList : 100% : 14663 ms, 99% : 14663 ms, 95 : 14663 ms, 90% : 14663 ms.
Result count 1, range 14663 ms to  14663 ms.
--------------- G3-1 --------------------- : 12

peersList : 100% : 2144 ms, 99% : 2144 ms, 95 : 2144 ms, 90% : 2144 ms.
Result count 1, range 2144 ms to  2144 ms.

--------------- G3s-1 --------------------- : 13

peersList : 100% : 2404 ms, 99% : 2404 ms, 95 : 2404 ms, 90% : 2404 ms.
Result count 1, range 2404 ms to  2404 ms.

--------------- Nexus 5 --------------------- : 14

peersList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Results list does not contain any items
--------------- HTC One M8s --------------------- : 15

peersList : 100% : 2853 ms, 99% : 2853 ms, 95 : 2853 ms, 90% : 2853 ms.
Result count 1, range 2853 ms to  2853 ms.
--------------- S5-1 --------------------- : 16
peersList : 100% : 19614 ms, 99% : 19614 ms, 95 : 19614 ms, 90% : 19614 ms.

Result count 1, range 19614 ms to  19614 ms.
--------------- XT1072 --------------------- : 17
peersList : 100% : 1979 ms, 99% : 1979 ms, 95 : 1979 ms, 90% : 1979 ms.
Result count 1, range 1979 ms to  1979 ms.

--------------- Combined ---------------------

peersList : 100% : 41081 ms, 99% : 41081 ms, 95 : 29836 ms, 90% : 19614 ms.

sendList : 100% : 44277 ms, 99% : 44277 ms, 95 : 44277 ms, 90% : 5796 ms.
Average data rate: 0.013 MB/s
--------------- end of test report ---------------------

2016-01-05T10:28:46.327Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1.o3kBVg==, peerAvailable=true, time=1124], sendList=[name=Apple-Iphone6-1.DQd5Sw==, time=3555, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1"]["sendList"][0], $ref=$["Apple-Iphone5-1"]["sendList"][0], name=Apple-Iphone5s-1.R3Z2qA==, time=3716, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1"]["sendList"][3], $ref=$["Apple-Iphone5-1"]["sendList"][3], name=Apple-IpadAir2-1.C4KP1Q==, time=4723, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1"]["sendList"][6], $ref=$["Apple-Iphone5-1"]["sendList"][6]], failedPeer=[name=Apple-Iphone5-1.+hwmKw==, time=41328, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone5-1"]["sendError"]["failedPeer"][0], $ref=$["Apple-Iphone5-1"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5s-1.Jzs4Xw==, peerAvailable=true, time=2243], sendList=[name=Apple-Iphone5s-1.R3Z2qA==, time=3144, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1"]["sendList"][0], $ref=$["Apple-Iphone6-1"]["sendList"][0], name=Apple-Iphone5-1.GgrI3w==, time=3312, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1"]["sendList"][3], $ref=$["Apple-Iphone6-1"]["sendList"][3], name=Apple-IpadAir2-1.C4KP1Q==, time=3870, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1"]["sendList"][6], $ref=$["Apple-Iphone6-1"]["sendList"][6]], failedPeer=[name=Apple-Iphone6-1.1MqlgA==, time=41101, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone6-1"]["sendError"]["failedPeer"][0], $ref=$["Apple-Iphone6-1"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1.+hwmKw==, peerAvailable=true, time=1096], sendList=[name=Apple-Iphone6-1.DQd5Sw==, time=3605, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1"]["sendList"][0], $ref=$["Apple-IpadAir2-1"]["sendList"][0], name=Apple-Iphone5s-1.R3Z2qA==, time=3873, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1"]["sendList"][3], $ref=$["Apple-IpadAir2-1"]["sendList"][3], name=Apple-Iphone5-1.GgrI3w==, time=4804, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1"]["sendList"][6], $ref=$["Apple-IpadAir2-1"]["sendList"][6]], failedPeer=[name=Apple-Iphone5-1.+hwmKw==, time=41346, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-IpadAir2-1"]["sendError"]["failedPeer"][0], $ref=$["Apple-IpadAir2-1"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1.+hwmKw==, peerAvailable=true, time=1308], sendList=[name=Apple-Iphone5-1.GgrI3w==, time=4568, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1"]["sendList"][0], $ref=$["Apple-Iphone5s-1"]["sendList"][0], name=Apple-Iphone6-1.DQd5Sw==, time=5796, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1"]["sendList"][3], $ref=$["Apple-Iphone5s-1"]["sendList"][3], name=Apple-IpadAir2-1.C4KP1Q==, time=44277, result=OK, connections=5, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1"]["sendList"][6], $ref=$["Apple-Iphone5s-1"]["sendList"][6]], failedPeer=[name=Apple-Iphone5s-1.Jzs4Xw==, time=40287, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone5s-1"]["sendError"]["failedPeer"][0], $ref=$["Apple-Iphone5s-1"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=2078], peersList=[peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=11649], peersList=[peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=41081], peersList=[peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=29836], peersList=[peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=4307], peersList=[peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=3308], peersList=[peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=14663], peersList=[peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=2144], peersList=[peerName=Nexus 5, peerIdentifier=34:FC:EF:11:AE:67, peerAvailable=true, time=2404], peersList=[], peersList=[peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=2853], peersList=[peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=19614], peersList=[peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=1979]

2016-01-05T10:28:46.337Z - debug: end to A3-1
2016-01-05T10:28:46.338Z - debug: end to G4-1

2016-01-05T10:28:46.340Z - debug: end to A5-1

2016-01-05T10:28:46.341Z - debug: end to Note4-1

2016-01-05T10:28:46.342Z - debug: end to Thali Test (Galaxy A5)

2016-01-05T10:28:46.343Z - debug: end to Thali Test (Galaxy A3)

2016-01-05T10:28:46.345Z - debug: end to Thali Test (Galaxy S5)

2016-01-05T10:28:46.346Z - debug: end to G3-1

2016-01-05T10:28:46.347Z - debug: end to G3s-1

2016-01-05T10:28:46.348Z - debug: end to Nexus 5

2016-01-05T10:28:46.349Z - debug: end to HTC One M8s

2016-01-05T10:28:46.350Z - debug: end to S5-1

2016-01-05T10:28:46.351Z - debug: end to XT1072


 
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
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
STOP log received from  f56ad48d Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Device test finished on f56ad48d 
Android task is completed. [SUCCESS]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/550731521dbc378_Use_user-settable_device_name__vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/550731521dbc378_Use_user-settable_device_name__vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/550731521dbc378_Use_user-settable_device_name__vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/550731521dbc378_Use_user-settable_device_name__vjrantal/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/550731521dbc378_Use_user-settable_device_name__vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/550731521dbc378_Use_user-settable_device_name__vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/550731521dbc378_Use_user-settable_device_name__vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  0be0c6c6 Test has  SUCCEEDED
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on 0be0c6c6 
Device test finished on 41006f95c8139173 
Device test finished on ZX1C223JKW 
Android task is completed. [SUCCESS]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/550731521dbc378_Use_user-settable_device_name__vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/550731521dbc378_Use_user-settable_device_name__vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/550731521dbc378_Use_user-settable_device_name__vjrantal/thali04_samsung-SM-G900F.md)

####Node name: thali06
Console output:
```
STOP log received from  7970f88c Test has  SUCCEEDED
Device test finished on 7970f88c 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:0 
child process exited with code 0 on device FA55PYS00566 
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:0 
child process exited with code 0 on device 022678fb504e29b0 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/550731521dbc378_Use_user-settable_device_name__vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/550731521dbc378_Use_user-settable_device_name__vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/550731521dbc378_Use_user-settable_device_name__vjrantal/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
STOP log received from  c5afcdcb Test has  SUCCEEDED
STOP log received from  4db5c8cc Test has  SUCCEEDED
Device test finished on 4db5c8cc 
Device test finished on c5afcdcb 
Android task is completed. [SUCCESS]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/550731521dbc378_Use_user-settable_device_name__vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/550731521dbc378_Use_user-settable_device_name__vjrantal/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/550731521dbc378_Use_user-settable_device_name__vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/550731521dbc378_Use_user-settable_device_name__vjrantal/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/550731521dbc378_Use_user-settable_device_name__vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/550731521dbc378_Use_user-settable_device_name__vjrantal/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/550731521dbc378_Use_user-settable_device_name__vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/550731521dbc378_Use_user-settable_device_name__vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/550731521dbc378_Use_user-settable_device_name__vjrantal/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/550731521dbc378_Use_user-settable_device_name__vjrantal/iOS_Iphone5s-1.md)



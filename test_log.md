#### Test 55742142a5c2fdb Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-12T12:19:26.977Z - info: listening on *:3000

2016-01-12T12:19:27.365Z - debug: Device presented: Thali Test (Galaxy A5) (android) perftest socket:0

2016-01-12T12:19:27.371Z - info: Setting start timeout to: 120000 (android)

2016-01-12T12:19:27.441Z - debug: Device presented: Thali Test (Galaxy S5) (android) perftest socket:1

2016-01-12T12:19:27.728Z - debug: Device presented: G4-1 (android) perftest socket:2

2016-01-12T12:19:27.823Z - debug: Device presented: Nexus 5 (android) perftest socket:3

2016-01-12T12:19:28.285Z - debug: Device presented: Note4-1 (android) perftest socket:4

2016-01-12T12:19:28.300Z - debug: Device presented: Apple-Iphone5s-1 (ios) perftest socket:5

2016-01-12T12:19:28.302Z - info: Setting start timeout to: 120000 (ios)

2016-01-12T12:19:28.915Z - debug: Device presented: A5-1 (android) perftest socket:6

2016-01-12T12:19:30.375Z - debug: Device presented: Apple-Iphone5-1 (ios) perftest socket:7

2016-01-12T12:19:30.571Z - debug: Device presented: Apple-Iphone6-1 (ios) perftest socket:9

2016-01-12T12:19:30.603Z - debug: Device presented: XT1072 (android) perftest socket:8

2016-01-12T12:19:30.775Z - debug: Device presented: Thali Test (Galaxy A3) (android) perftest socket:10

2016-01-12T12:19:30.881Z - debug: Device presented: Apple-IpadAir2-1 (ios) perftest socket:11

2016-01-12T12:19:30.883Z - info: Required number of devices presented

2016-01-12T12:19:30.887Z - info: Starting perf test run for platform: ios

2016-01-12T12:19:30.888Z - info: Using devices:

2016-01-12T12:19:30.889Z - info: Apple-Iphone5s-1

2016-01-12T12:19:30.890Z - info: Apple-Iphone5-1

2016-01-12T12:19:30.891Z - info: Apple-Iphone6-1

2016-01-12T12:19:30.892Z - info: Apple-IpadAir2-1

2016-01-12T12:19:30.896Z - info: Starting test: with 4 devices (ios)

2016-01-12T12:19:31.576Z - debug: Device presented: A3-1 (android) perftest socket:12

2016-01-12T12:19:31.778Z - debug: Device presented: G3s-1 (android) perftest socket:13

2016-01-12T12:19:31.789Z - debug: Device presented: S5-1 (android) perftest socket:14

2016-01-12T12:19:32.402Z - info: Received results for {"name:":"Apple-Iphone5-1","time":1063,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone5s-1.+FhoNw==","peerAvailable":true,"time":1062}]} Apple-Iphone5-1 ios (3 left)

2016-01-12T12:19:32.480Z - info: Received results for {"name:":"Apple-IpadAir2-1","time":1394,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone5s-1.+FhoNw==","peerAvailable":true,"time":1394}]} Apple-IpadAir2-1 ios (2 left)

2016-01-12T12:19:32.584Z - info: Received results for {"name:":"Apple-Iphone5s-1","time":1054,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone6-1.vdOTuw==","peerAvailable":true,"time":1053}]} Apple-Iphone5s-1 ios (1 left)

2016-01-12T12:19:32.589Z - info: Received results for {"name:":"Apple-Iphone6-1","time":1152,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone5-1.IBb4nw==","peerAvailable":true,"time":1152}]} Apple-Iphone6-1 ios (0 left)

2016-01-12T12:19:32.594Z - info: All test data retrieved for testFindPeers.js (ios)

2016-01-12T12:19:32.601Z - info: Remaining tests: testSendData.js

2016-01-12T12:19:32.606Z - info: Continuing to next test: testSendData.js

2016-01-12T12:19:32.607Z - info: Starting test: with 4 devices (ios)

2016-01-12T12:19:33.259Z - debug: Device presented: S5mini-1 (android) perftest socket:15

2016-01-12T12:19:33.299Z - debug: Device presented: G3-1 (android) perftest socket:16

2016-01-12T12:19:34.565Z - debug: Socket disconnected: transport close 15 (S5mini-1)

2016-01-12T12:20:25.939Z - info: Received results for {"name:":"Apple-Iphone5s-1","time":52943,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1.+FhoNw==","time":41298,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-Iphone5-1.mOZnMg==","time":3992,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1.WKZK+A==","time":3750,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1.56+AEA==","time":3702,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone5s-1 ios (3 left)

2016-01-12T12:20:27.548Z - info: Received results for {"name:":"Apple-Iphone6-1","time":54582,"result":"OK","sendList":[{"name":"Apple-IpadAir2-1.hA+i5Q==","time":41827,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-Iphone5-1.mOZnMg==","time":5131,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1.WKZK+A==","time":4243,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1.8kws4w==","time":3310,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone6-1 ios (2 left)

2016-01-12T12:20:27.609Z - info: Received results for {"name:":"Apple-IpadAir2-1","time":54596,"result":"OK","sendList":[{"name":"Apple-IpadAir2-1.hA+i5Q==","time":41347,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-Iphone5s-1.8kws4w==","time":4908,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1.56+AEA==","time":4261,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1.mOZnMg==","time":3920,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-IpadAir2-1 ios (1 left)

2016-01-12T12:20:29.622Z - info: Received results for {"name:":"Apple-Iphone5-1","time":56342,"result":"OK","sendList":[{"name":"Apple-Iphone5-1.IBb4nw==","time":41358,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-IpadAir2-1.WKZK+A==","time":6001,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1.56+AEA==","time":4744,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1.8kws4w==","time":4031,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone5-1 ios (0 left)

2016-01-12T12:20:29.624Z - info: All test data retrieved for testSendData.js (ios)

2016-01-12T12:20:29.629Z - info: ALL DONE !!!

{ 'name:': 'Apple-Iphone5s-1',
  time: 1054,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1.vdOTuw==',
       peerAvailable: true,
       time: 1053 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 1063,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5s-1.+FhoNw==',
       peerAvailable: true,
       time: 1062 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 1152,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1.IBb4nw==',
       peerAvailable: true,
       time: 1152 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 1394,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5s-1.+FhoNw==',
       peerAvailable: true,
       time: 1394 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 52943,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5s-1.+FhoNw==',
       time: 41298,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.mOZnMg==',
       time: 3992,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1.WKZK+A==',
       time: 3750,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.56+AEA==',
       time: 3702,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 56342,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.IBb4nw==',
       time: 41358,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.WKZK+A==',
       time: 6001,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.56+AEA==',
       time: 4744,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.8kws4w==',
       time: 4031,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 54582,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1.hA+i5Q==',
       time: 41827,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.mOZnMg==',
       time: 5131,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1.WKZK+A==',
       time: 4243,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.8kws4w==',
       time: 3310,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 54596,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1.hA+i5Q==',
       time: 41347,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1.8kws4w==',
       time: 4908,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.56+AEA==',
       time: 4261,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.mOZnMg==',
       time: 3920,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

--------------- test report ---------------------
--------------- Apple-Iphone5s-1 --------------------- : 1

Find peers : 100% : 1053 ms, 99% : 1053 ms, 95 : 1053 ms, 90% : 1053 ms.

Result count 1, range 1053 ms to  1053 ms.

Send data : 100% : 3992 ms, 99% : 3992 ms, 95 : 3992 ms, 90% : 3992 ms.

Average data rate: 0.026 MB/s

Result count 3, range 3702 ms to  3992 ms.

Send data failed peers count : 1 [25 %]

- Peer ID : Apple-Iphone5s-1.+FhoNw==, Tried : 5

Send data never tried peers count : 0 [0 %]
--------------- Apple-Iphone5-1 --------------------- : 2

Find peers : 100% : 1062 ms, 99% : 1062 ms, 95 : 1062 ms, 90% : 1062 ms.
Result count 1, range 1062 ms to  1062 ms.

Send data : 100% : 6001 ms, 99% : 6001 ms, 95 : 6001 ms, 90% : 6001 ms.
Average data rate: 0.02 MB/s

Result count 3, range 4031 ms to  6001 ms.
Send data failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone5-1.IBb4nw==, Tried : 5

Send data never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1 --------------------- : 3

Find peers : 100% : 1152 ms, 99% : 1152 ms, 95 : 1152 ms, 90% : 1152 ms.
Result count 1, range 1152 ms to  1152 ms.
Send data : 100% : 5131 ms, 99% : 5131 ms, 95 : 5131 ms, 90% : 5131 ms.

Average data rate: 0.024 MB/s

Result count 3, range 3310 ms to  5131 ms.
Send data failed peers count : 1 [25 %]
- Peer ID : Apple-IpadAir2-1.hA+i5Q==, Tried : 5
Send data never tried peers count : 0 [0 %]
--------------- Apple-IpadAir2-1 --------------------- : 4
Find peers : 100% : 1394 ms, 99% : 1394 ms, 95 : 1394 ms, 90% : 1394 ms.
Result count 1, range 1394 ms to  1394 ms.

Send data : 100% : 4908 ms, 99% : 4908 ms, 95 : 4908 ms, 90% : 4908 ms.
Average data rate: 0.023 MB/s
Result count 3, range 3920 ms to  4908 ms.
Send data failed peers count : 1 [25 %]

- Peer ID : Apple-IpadAir2-1.hA+i5Q==, Tried : 5
Send data never tried peers count : 0 [0 %]
--------------- Combined ---------------------

Find peers : 100% : 1394 ms, 99% : 1394 ms, 95 : 1394 ms, 90% : 1394 ms.

Send data : 100% : 6001 ms, 99% : 6001 ms, 95 : 5131 ms, 90% : 5131 ms.
Average data rate: 0.023 MB/s

--------------- end of test report ---------------------

2016-01-12T12:20:29.757Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1.vdOTuw==, peerAvailable=true, time=1053], sendList=[name=Apple-Iphone6-1.56+AEA==, time=3702, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.WKZK+A==, time=3750, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1.mOZnMg==, time=3992, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone5s-1.+FhoNw==, time=41298, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5s-1.+FhoNw==, peerAvailable=true, time=1062], sendList=[name=Apple-Iphone5s-1.8kws4w==, time=4031, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone6-1.56+AEA==, time=4744, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.WKZK+A==, time=6001, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone5-1.IBb4nw==, time=41358, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1.IBb4nw==, peerAvailable=true, time=1152], sendList=[name=Apple-Iphone5s-1.8kws4w==, time=3310, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.WKZK+A==, time=4243, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1.mOZnMg==, time=5131, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-IpadAir2-1.hA+i5Q==, time=41827, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5s-1.+FhoNw==, peerAvailable=true, time=1394], sendList=[name=Apple-Iphone5-1.mOZnMg==, time=3920, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone6-1.56+AEA==, time=4261, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5s-1.8kws4w==, time=4908, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-IpadAir2-1.hA+i5Q==, time=41347, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[]

2016-01-12T12:20:29.769Z - debug: end to Apple-Iphone5s-1

2016-01-12T12:20:29.772Z - debug: end to Apple-Iphone5-1

2016-01-12T12:20:29.773Z - debug: end to Apple-Iphone6-1

2016-01-12T12:20:29.774Z - debug: end to Apple-IpadAir2-1

2016-01-12T12:20:31.118Z - debug: state: android waiting
2016-01-12T12:20:31.119Z - debug: state: ios completed

2016-01-12T12:20:32.565Z - debug: Socket disconnected: transport close 5 (Apple-Iphone5s-1)

2016-01-12T12:20:32.591Z - debug: Socket disconnected: transport close 9 (Apple-Iphone6-1)

2016-01-12T12:20:32.959Z - debug: Socket disconnected: transport close 11 (Apple-IpadAir2-1)

2016-01-12T12:20:33.218Z - debug: Socket disconnected: transport close 7 (Apple-Iphone5-1)

2016-01-12T12:21:27.387Z - info: Start timeout elapsed for platform: android

2016-01-12T12:21:27.390Z - info: Starting perf test run for platform: android

2016-01-12T12:21:27.393Z - info: Using devices:

2016-01-12T12:21:27.395Z - info: Thali Test (Galaxy A5)

2016-01-12T12:21:27.396Z - info: Thali Test (Galaxy S5)

2016-01-12T12:21:27.398Z - info: G4-1

2016-01-12T12:21:27.400Z - info: Nexus 5

2016-01-12T12:21:27.402Z - info: Note4-1

2016-01-12T12:21:27.404Z - info: A5-1

2016-01-12T12:21:27.405Z - info: XT1072

2016-01-12T12:21:27.407Z - info: Thali Test (Galaxy A3)

2016-01-12T12:21:27.409Z - info: A3-1

2016-01-12T12:21:27.411Z - info: G3s-1

2016-01-12T12:21:27.413Z - info: S5-1

2016-01-12T12:21:27.415Z - info: S5mini-1

2016-01-12T12:21:27.416Z - info: G3-1

2016-01-12T12:21:27.418Z - info: Starting test: with 13 devices (android)

2016-01-12T12:23:07.703Z - info: Received results for {"name:":"A5-1","time":100068,"result":"TIMEOUT","peersList":[{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":false,"time":94895},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":5293},{"peerName":"XT1072","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true,"time":5340},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":5628},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":18158},{"peerName":"Nexus 5","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":true,"time":18247},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":93134}]} A5-1 android (12 left)

2016-01-12T12:23:07.710Z - info: Received results for {"name:":"Thali Test (Galaxy A5)","time":100069,"result":"TIMEOUT","peersList":[{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":43468},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":43531},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":46338},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":46542},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":62530},{"peerName":"Note4-1","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":77071}]} Thali Test (Galaxy A5) android (11 left)

2016-01-12T12:23:07.732Z - info: Received results for {"name:":"Note4-1","time":100073,"result":"TIMEOUT","peersList":[{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":58886},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":58973},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":59010},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":59185},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":76690},{"peerName":"XT1072","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true,"time":85938},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":85974},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":86359}]} Note4-1 android (10 left)

2016-01-12T12:23:07.748Z - info: Received results for {"name:":"A3-1","time":100065,"result":"TIMEOUT","peersList":[{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":3523},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":3564},{"peerName":"XT1072","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true,"time":3600},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":3655},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":3760},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":3850},{"peerName":"Nexus 5","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":true,"time":3946},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":4673},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":9171},{"peerName":"Note4-1","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":40858}]} A3-1 android (9 left)

2016-01-12T12:23:07.798Z - info: Received results for {"name:":"XT1072","time":100156,"result":"TIMEOUT","peersList":[{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":3281},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":3325},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":3361},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":3455},{"peerName":"Note4-1","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":3695},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":76882},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":88623}]} XT1072 android (8 left)

2016-01-12T12:23:07.891Z - info: Received results for {"name:":"Thali Test (Galaxy A3)","time":100067,"result":"TIMEOUT","peersList":[{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":3655},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":3719},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":4330},{"peerName":"Nexus 5","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":true,"time":7421},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":11066},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":14048},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":14336},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":14367},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":41999},{"peerName":"XT1072","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true,"time":82795},{"peerName":"Note4-1","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":92952}]} Thali Test (Galaxy A3) android (7 left)

2016-01-12T12:23:07.990Z - info: Received results for {"name:":"Nexus 5","time":100132,"result":"TIMEOUT","peersList":[{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":8350},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":false,"time":98359},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":false,"time":98361},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":false,"time":98365},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":false,"time":98363}]} Nexus 5 android (6 left)

2016-01-12T12:23:08.451Z - info: Received results for {"name:":"Thali Test (Galaxy S5)","time":100120,"result":"TIMEOUT","peersList":[{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":15618},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":26730},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":26848},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":33648},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":38099},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":45245},{"peerName":"Note4-1","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":76157}]} Thali Test (Galaxy S5) android (5 left)

2016-01-12T12:23:09.078Z - info: Received results for {"name:":"G4-1","time":100070,"result":"TIMEOUT","peersList":[{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":6274},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":6283},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":6312},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":7199},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":14852},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":39781},{"peerName":"XT1072","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true,"time":49917},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":49961},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":75163}]} G4-1 android (4 left)

2016-01-12T12:23:09.162Z - info: Received results for {"name:":"G3s-1","time":100128,"result":"TIMEOUT","peersList":[{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":22316},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":29370},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":29689}]} G3s-1 android (3 left)

2016-01-12T12:23:09.782Z - info: Received results for {"name:":"S5-1","time":100226,"result":"TIMEOUT","peersList":[{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":4076},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":5729},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":15824},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":28317},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":82885},{"peerName":"XT1072","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true,"time":95267}]} S5-1 android (2 left)

2016-01-12T12:23:11.372Z - info: Received results for {"name:":"G3-1","time":100088,"result":"TIMEOUT","peersList":[{"peerName":"Nexus 5","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":true,"time":2544},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":2574},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":16093},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":16123},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":16191},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":57103},{"peerName":"Note4-1","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":66833},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":98763}]} G3-1 android (1 left)

2016-01-12T12:23:27.477Z - info: server timeout for test: testFindPeers.js (android)

2016-01-12T12:23:27.481Z - info: All test data retrieved for testFindPeers.js (android)

2016-01-12T12:23:27.496Z - info: No results from S5mini-1

2016-01-12T12:23:27.499Z - info: Remaining tests: testSendData.js

2016-01-12T12:23:27.501Z - info: Continuing to next test: testSendData.js

2016-01-12T12:23:27.503Z - info: Starting test: with 13 devices (android)

2016-01-12T12:25:07.755Z - info: Received results for {"name:":"Nexus 5","time":100050,"result":"TIMEOUT","sendList":[{"name":"F8:95:C7:87:85:54","time":5927,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"58:3F:54:73:64:C0","time":5764,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:34:8A:A0","time":12378,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":1,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"}]} Nexus 5 android (12 left)

2016-01-12T12:25:07.844Z - info: Received results for {"name:":"G4-1","time":100076,"result":"TIMEOUT","sendList":[{"connections":1,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":1,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"}]} G4-1 android (11 left)

2016-01-12T12:25:07.856Z - info: Received results for {"name:":"G3s-1","time":100177,"result":"TIMEOUT","sendList":[{"name":"7C:F9:0E:51:18:22","time":35497,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"}]} G3s-1 android (10 left)

2016-01-12T12:25:08.142Z - info: Received results for {"name:":"G3-1","time":100091,"result":"TIMEOUT","sendList":[{"name":"44:80:EB:7B:5A:05","time":10713,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"34:FC:EF:11:AE:67","time":9456,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":11150,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:37:96:AB","time":30907,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"}]} G3-1 android (9 left)

2016-01-12T12:25:08.155Z - info: Received results for {"name:":"Note4-1","time":100104,"result":"TIMEOUT","sendList":[{"name":"F8:95:C7:87:85:54","time":29986,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"44:80:EB:7B:5A:05","time":40580,"result":"OK","connections":3,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:76:27","time":27574,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"}]} Note4-1 android (8 left)

2016-01-12T12:25:08.203Z - info: Received results for {"name:":"Thali Test (Galaxy A3)","time":100095,"result":"TIMEOUT","sendList":[{"name":"34:FC:EF:11:AE:67","time":26407,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"}]} Thali Test (Galaxy A3) android (7 left)

2016-01-12T12:25:08.274Z - info: Received results for {"name:":"S5-1","time":100098,"result":"TIMEOUT","sendList":[{"name":"08:EC:A9:50:76:27","time":15435,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":29468,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"58:3F:54:73:64:C0","time":14202,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":9405,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"}]} S5-1 android (6 left)

2016-01-12T12:25:09.804Z - info: Received results for {"name:":"Thali Test (Galaxy S5)","time":100092,"result":"TIMEOUT","sendList":[{"name":"08:EC:A9:50:75:41","time":72993,"result":"OK","connections":4,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"}]} Thali Test (Galaxy S5) android (5 left)

2016-01-12T12:25:10.530Z - info: Received results for {"name:":"Thali Test (Galaxy A5)","time":100103,"result":"TIMEOUT","sendList":[{"name":"7C:F9:0E:34:8A:A0","time":41018,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"}]} Thali Test (Galaxy A5) android (4 left)

2016-01-12T12:25:10.797Z - info: Received results for {"name:":"A3-1","time":100071,"result":"TIMEOUT","sendList":[{"name":"E0:DB:10:14:E2:C0","time":25491,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:76:27","time":69485,"result":"OK","connections":4,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"}]} A3-1 android (3 left)

2016-01-12T12:25:27.505Z - info: server timeout for test: testSendData.js (android)

2016-01-12T12:25:27.510Z - info: All test data retrieved for testSendData.js (android)

2016-01-12T12:25:27.517Z - info: No results from A5-1

2016-01-12T12:25:27.521Z - info: No results from XT1072

2016-01-12T12:25:27.527Z - info: No results from S5mini-1

2016-01-12T12:25:27.532Z - info: ALL DONE !!!

{ 'name:': 'Apple-Iphone5s-1',
  time: 1054,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1.vdOTuw==',
       peerAvailable: true,
       time: 1053 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 1063,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5s-1.+FhoNw==',
       peerAvailable: true,
       time: 1062 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 1152,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1.IBb4nw==',
       peerAvailable: true,
       time: 1152 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 1394,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5s-1.+FhoNw==',
       peerAvailable: true,
       time: 1394 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 52943,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5s-1.+FhoNw==',
       time: 41298,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.mOZnMg==',
       time: 3992,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1.WKZK+A==',
       time: 3750,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.56+AEA==',
       time: 3702,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 56342,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.IBb4nw==',
       time: 41358,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.WKZK+A==',
       time: 6001,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.56+AEA==',
       time: 4744,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.8kws4w==',
       time: 4031,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 54582,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1.hA+i5Q==',
       time: 41827,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.mOZnMg==',
       time: 5131,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1.WKZK+A==',
       time: 4243,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.8kws4w==',
       time: 3310,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 54596,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1.hA+i5Q==',
       time: 41347,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1.8kws4w==',
       time: 4908,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.56+AEA==',
       time: 4261,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.mOZnMg==',
       time: 3920,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Thali Test (Galaxy A5)',
  time: 100069,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 43468 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 43531 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 46338 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 46542 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 62530 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 77071 } ] }

{ 'name:': 'Thali Test (Galaxy S5)',
  time: 100120,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 15618 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 26730 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 26848 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 33648 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 38099 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 45245 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 76157 } ] }

{ 'name:': 'G4-1',
  time: 100070,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 6274 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 6283 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 6312 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 7199 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 14852 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 39781 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 49917 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 49961 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 75163 } ] }

{ 'name:': 'Nexus 5',
  time: 100132,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 8350 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: false,
       time: 98359 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: false,
       time: 98361 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: false,
       time: 98365 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: false,
       time: 98363 } ] }

{ 'name:': 'Note4-1',
  time: 100073,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 58886 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 58973 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 59010 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 59185 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 76690 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 85938 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 85974 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 86359 } ] }

{ 'name:': 'A5-1',
  time: 100068,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: false,
       time: 94895 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 5293 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 5340 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 5628 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 18158 },
     { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 18247 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 93134 } ] }

{ 'name:': 'XT1072',
  time: 100156,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 3281 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 3325 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 3361 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 3455 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 3695 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 76882 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 88623 } ] }

{ 'name:': 'Thali Test (Galaxy A3)',
  time: 100067,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 3655 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 3719 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 4330 },
     { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 7421 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 11066 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 14048 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 14336 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 14367 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 41999 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 82795 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 92952 } ] }

{ 'name:': 'A3-1',
  time: 100065,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 3523 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 3564 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 3600 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 3655 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 3760 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 3850 },
     { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 3946 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 4673 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 9171 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 40858 } ] }

{ 'name:': 'G3s-1',
  time: 100128,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 22316 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 29370 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 29689 } ] }

{ 'name:': 'S5-1',
  time: 100226,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 4076 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 5729 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 15824 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 28317 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 82885 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 95267 } ] }

{ 'name:': 'G3-1',
  time: 100088,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 2544 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 2574 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 16093 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 16123 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 16191 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 57103 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 66833 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 98763 } ] }

{ 'name:': 'Thali Test (Galaxy A5)',
  time: 100103,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '7C:F9:0E:34:8A:A0',
       time: 41018,
       result: 'OK',
       connections: 2,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: 'F8:95:C7:87:3C:51',
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
       name: 'F8:95:C7:87:85:54',
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
       name: 'E0:DB:10:14:E2:C0',
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
       name: '08:EC:A9:50:76:27',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '58:3F:54:73:64:C0',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Thali Test (Galaxy S5)',
  time: 100092,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '08:EC:A9:50:75:41',
       time: 72993,
       result: 'OK',
       connections: 4,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: '00:F4:6F:30:E0:6C',
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
       name: '08:EC:A9:50:76:27',
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
       name: '34:FC:EF:11:AE:67',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F8:95:C7:87:85:54',
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
       name: '7C:F9:0E:34:8A:A0',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'G4-1',
  time: 100076,
  result: 'TIMEOUT',
  sendList: 
   [ { connections: 1,
       name: '7C:F9:0E:51:18:22',
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
       name: '58:3F:54:73:64:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:76:27',
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
       name: 'F8:95:C7:87:85:54',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'B0:C5:59:3F:75:69',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:34:8A:A0',
       time: 0,
       result: 'Fail' },
     { connections: 1,
       name: '00:F4:6F:30:E0:6C',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Nexus 5',
  time: 100050,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'F8:95:C7:87:85:54',
       time: 5927,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '58:3F:54:73:64:C0',
       time: 5764,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:34:8A:A0',
       time: 12378,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: '7C:F9:0E:37:96:AB',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:76:27',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:51:18:22',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:75:41',
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
       name: 'F8:95:C7:87:3C:51',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '44:80:EB:7B:5A:05',
       time: 0,
       result: 'Fail' },
     { connections: 1,
       name: '00:F4:6F:30:E0:6C',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Note4-1',
  time: 100104,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'F8:95:C7:87:85:54',
       time: 29986,
       result: 'OK',
       connections: 2,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '44:80:EB:7B:5A:05',
       time: 40580,
       result: 'OK',
       connections: 3,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '08:EC:A9:50:76:27',
       time: 27574,
       result: 'OK',
       connections: 2,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: '7C:F9:0E:34:8A:A0',
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
       name: '08:EC:A9:50:75:41',
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
       name: 'F8:95:C7:87:3C:51',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:37:96:AB',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:11:AE:67',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Thali Test (Galaxy A3)',
  time: 100095,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '34:FC:EF:11:AE:67',
       time: 26407,
       result: 'OK',
       connections: 2,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: 'F8:95:C7:87:3C:51',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '00:F4:6F:30:E0:6C',
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
       name: '44:80:EB:7B:5A:05',
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
       name: 'F8:95:C7:87:85:54',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:37:96:AB',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:34:8A:A0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'B0:C5:59:3F:75:69',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'A3-1',
  time: 100071,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'E0:DB:10:14:E2:C0',
       time: 25491,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '08:EC:A9:50:76:27',
       time: 69485,
       result: 'OK',
       connections: 4,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: '58:3F:54:73:64:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:51:18:22',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:11:AE:67',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:37:96:AB',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:34:8A:A0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F8:95:C7:87:85:54',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'B0:C5:59:3F:75:69',
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
       name: 'F8:95:C7:87:3C:51',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'G3s-1',
  time: 100177,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '7C:F9:0E:51:18:22',
       time: 35497,
       result: 'OK',
       connections: 2,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: '44:80:EB:7B:5A:05',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '00:F4:6F:30:E0:6C',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:76:27',
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
       name: '7C:F9:0E:37:96:AB',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:11:AE:67',
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
       name: '7C:F9:0E:34:8A:A0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'B0:C5:59:3F:75:69',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'S5-1',
  time: 100098,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '08:EC:A9:50:76:27',
       time: 15435,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'E0:DB:10:14:E2:C0',
       time: 29468,
       result: 'OK',
       connections: 2,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '58:3F:54:73:64:C0',
       time: 14202,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:85:54',
       time: 9405,
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
       name: '44:80:EB:7B:5A:05',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'B0:C5:59:3F:75:69',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:51:18:22',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:11:AE:67',
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
       name: '7C:F9:0E:37:96:AB',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'G3-1',
  time: 100091,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '44:80:EB:7B:5A:05',
       time: 10713,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '34:FC:EF:11:AE:67',
       time: 9456,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'B0:C5:59:3F:75:69',
       time: 11150,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:37:96:AB',
       time: 30907,
       result: 'OK',
       connections: 2,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: '00:F4:6F:30:E0:6C',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'E0:DB:10:14:E2:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F8:95:C7:87:3C:51',
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
       name: '08:EC:A9:50:76:27',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:51:18:22',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F8:95:C7:87:85:54',
       time: 0,
       result: 'Fail' } ] }

--------------- test report ---------------------
--------------- Apple-Iphone5s-1 --------------------- : 1

Find peers : 100% : 1053 ms, 99% : 1053 ms, 95 : 1053 ms, 90% : 1053 ms.
Result count 1, range 1053 ms to  1053 ms.

Send data : 100% : 3992 ms, 99% : 3992 ms, 95 : 3992 ms, 90% : 3992 ms.
Average data rate: 0.026 MB/s

Result count 3, range 3702 ms to  3992 ms.
Send data failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone5s-1.+FhoNw==, Tried : 5

Send data never tried peers count : 0 [0 %]
--------------- Apple-Iphone5-1 --------------------- : 2

Find peers : 100% : 1062 ms, 99% : 1062 ms, 95 : 1062 ms, 90% : 1062 ms.
Result count 1, range 1062 ms to  1062 ms.

Send data : 100% : 6001 ms, 99% : 6001 ms, 95 : 6001 ms, 90% : 6001 ms.
Average data rate: 0.02 MB/s
Result count 3, range 4031 ms to  6001 ms.

Send data failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone5-1.IBb4nw==, Tried : 5
Send data never tried peers count : 0 [0 %]

--------------- Apple-Iphone6-1 --------------------- : 3
Find peers : 100% : 1152 ms, 99% : 1152 ms, 95 : 1152 ms, 90% : 1152 ms.
Result count 1, range 1152 ms to  1152 ms.

Send data : 100% : 5131 ms, 99% : 5131 ms, 95 : 5131 ms, 90% : 5131 ms.
Average data rate: 0.024 MB/s
Result count 3, range 3310 ms to  5131 ms.

Send data failed peers count : 1 [25 %]
- Peer ID : Apple-IpadAir2-1.hA+i5Q==, Tried : 5
Send data never tried peers count : 0 [0 %]

--------------- Apple-IpadAir2-1 --------------------- : 4
Find peers : 100% : 1394 ms, 99% : 1394 ms, 95 : 1394 ms, 90% : 1394 ms.

Result count 1, range 1394 ms to  1394 ms.
Send data : 100% : 4908 ms, 99% : 4908 ms, 95 : 4908 ms, 90% : 4908 ms.
Average data rate: 0.023 MB/s

Result count 3, range 3920 ms to  4908 ms.
Send data failed peers count : 1 [25 %]
- Peer ID : Apple-IpadAir2-1.hA+i5Q==, Tried : 5

Send data never tried peers count : 0 [0 %]
--------------- Thali Test (Galaxy A5) --------------------- : 5

Find peers : 100% : 77071 ms, 99% : 77071 ms, 95 : 77071 ms, 90% : 62530 ms.
Result count 6, range 43468 ms to  77071 ms.

Send data : 100% : 41018 ms, 99% : 41018 ms, 95 : 41018 ms, 90% : 41018 ms.
Average data rate: 0.002 MB/s

Result count 1, range 41018 ms to  41018 ms.
Send data failed peers count : 1 [50 %]
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
Send data never tried peers count : 10 [83.33333333333333 %]
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : F8:95:C7:87:85:54
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 58:3F:54:73:64:C0
--------------- Thali Test (Galaxy S5) --------------------- : 6
Find peers : 100% : 76157 ms, 99% : 76157 ms, 95 : 76157 ms, 90% : 45245 ms.
Result count 7, range 15618 ms to  76157 ms.
Send data : 100% : 72993 ms, 99% : 72993 ms, 95 : 72993 ms, 90% : 72993 ms.
Average data rate: 0.001 MB/s
Result count 1, range 72993 ms to  72993 ms.
Send data failed peers count : 1 [50 %]
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
Send data never tried peers count : 10 [83.33333333333333 %]
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : F8:95:C7:87:85:54
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 7C:F9:0E:34:8A:A0
--------------- G4-1 --------------------- : 7
Find peers : 100% : 75163 ms, 99% : 75163 ms, 95 : 75163 ms, 90% : 49961 ms.
Result count 9, range 6274 ms to  75163 ms.
No send data results!
--------------- Nexus 5 --------------------- : 8
Find peers : 100% : 98365 ms, 99% : 98365 ms, 95 : 98365 ms, 90% : 98365 ms.
Result count 5, range 8350 ms to  98365 ms.
Send data : 100% : 12378 ms, 99% : 12378 ms, 95 : 12378 ms, 90% : 12378 ms.
Average data rate: 0.012 MB/s
Result count 3, range 5764 ms to  12378 ms.
Send data failed peers count : 2 [40 %]
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
Send data never tried peers count : 7 [58.333333333333336 %]
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : E0:DB:10:14:E2:C0

- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 44:80:EB:7B:5A:05
--------------- Note4-1 --------------------- : 9
Find peers : 100% : 86359 ms, 99% : 86359 ms, 95 : 86359 ms, 90% : 85974 ms.

Result count 8, range 58886 ms to  86359 ms.
Send data : 100% : 40580 ms, 99% : 40580 ms, 95 : 40580 ms, 90% : 40580 ms.
Average data rate: 0.003 MB/s

Result count 3, range 27574 ms to  40580 ms.
Send data failed peers count : 1 [25 %]
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1

Send data never tried peers count : 8 [66.66666666666667 %]
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : B0:C5:59:3F:75:69

- Peer ID : 08:EC:A9:50:75:41
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 34:FC:EF:11:AE:67
--------------- A5-1 --------------------- : 10
Find peers : 100% : 94895 ms, 99% : 94895 ms, 95 : 94895 ms, 90% : 93134 ms.
Result count 7, range 5293 ms to  94895 ms.

--------------- XT1072 --------------------- : 11

Find peers : 100% : 88623 ms, 99% : 88623 ms, 95 : 88623 ms, 90% : 76882 ms.
Result count 7, range 3281 ms to  88623 ms.

--------------- Thali Test (Galaxy A3) --------------------- : 12

Find peers : 100% : 92952 ms, 99% : 92952 ms, 95 : 82795 ms, 90% : 82795 ms.

Result count 11, range 3655 ms to  92952 ms.
Send data : 100% : 26407 ms, 99% : 26407 ms, 95 : 26407 ms, 90% : 26407 ms.

Average data rate: 0.004 MB/s
Result count 1, range 26407 ms to  26407 ms.
Send data failed peers count : 1 [50 %]
- Peer ID : F8:95:C7:87:3C:51, Tried : 1

Send data never tried peers count : 10 [83.33333333333333 %]
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 08:EC:A9:50:75:41

- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 7C:F9:0E:51:18:22

- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : F8:95:C7:87:85:54
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 7C:F9:0E:34:8A:A0

- Peer ID : B0:C5:59:3F:75:69
--------------- A3-1 --------------------- : 13
Find peers : 100% : 40858 ms, 99% : 40858 ms, 95 : 40858 ms, 90% : 9171 ms.
Result count 10, range 3523 ms to  40858 ms.
Send data : 100% : 69485 ms, 99% : 69485 ms, 95 : 69485 ms, 90% : 69485 ms.
Average data rate: 0.002 MB/s
Result count 2, range 25491 ms to  69485 ms.

Send data failed peers count : 1 [33.333333333333336 %]
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
Send data never tried peers count : 9 [75 %]

- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 7C:F9:0E:37:96:AB

- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : F8:95:C7:87:85:54
- Peer ID : B0:C5:59:3F:75:69

- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : F8:95:C7:87:3C:51

--------------- G3s-1 --------------------- : 14
Find peers : 100% : 29689 ms, 99% : 29689 ms, 95 : 29689 ms, 90% : 29689 ms.
Result count 3, range 22316 ms to  29689 ms.

Send data : 100% : 35497 ms, 99% : 35497 ms, 95 : 35497 ms, 90% : 35497 ms.
Average data rate: 0.003 MB/s
Result count 1, range 35497 ms to  35497 ms.

Send data failed peers count : 1 [50 %]
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1

Send data never tried peers count : 10 [83.33333333333333 %]
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 08:EC:A9:50:75:41

- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 34:FC:EF:11:AE:67

- Peer ID : F8:95:C7:87:3C:51
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : B0:C5:59:3F:75:69

--------------- S5-1 --------------------- : 15
Find peers : 100% : 95267 ms, 99% : 95267 ms, 95 : 95267 ms, 90% : 82885 ms.

Result count 6, range 4076 ms to  95267 ms.
Send data : 100% : 29468 ms, 99% : 29468 ms, 95 : 29468 ms, 90% : 29468 ms.

Average data rate: 0.006 MB/s
Result count 4, range 9405 ms to  29468 ms.
Send data failed peers count : 1 [20 %]

- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
Send data never tried peers count : 7 [58.333333333333336 %]
- Peer ID : 44:80:EB:7B:5A:05

- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : 34:FC:EF:11:AE:67

- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : 7C:F9:0E:37:96:AB

--------------- G3-1 --------------------- : 16

Find peers : 100% : 98763 ms, 99% : 98763 ms, 95 : 98763 ms, 90% : 66833 ms.

Result count 8, range 2544 ms to  98763 ms.
Send data : 100% : 30907 ms, 99% : 30907 ms, 95 : 30907 ms, 90% : 30907 ms.

Average data rate: 0.006 MB/s
Result count 4, range 9456 ms to  30907 ms.
Send data failed peers count : 1 [20 %]
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1

Send data never tried peers count : 7 [58.333333333333336 %]
- Peer ID : E0:DB:10:14:E2:C0

- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 08:EC:A9:50:75:41

- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : F8:95:C7:87:85:54

--------------- Combined ---------------------

Find peers : 100% : 98763 ms, 99% : 98365 ms, 95 : 95267 ms, 90% : 88623 ms.

Send data : 100% : 72993 ms, 99% : 72993 ms, 95 : 41018 ms, 90% : 40580 ms.
Average data rate: 0.006 MB/s

--------------- end of test report ---------------------

2016-01-12T12:25:27.976Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1.vdOTuw==, peerAvailable=true, time=1053], sendList=[name=Apple-Iphone6-1.56+AEA==, time=3702, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.WKZK+A==, time=3750, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1.mOZnMg==, time=3992, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone5s-1.+FhoNw==, time=41298, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5s-1.+FhoNw==, peerAvailable=true, time=1062], sendList=[name=Apple-Iphone5s-1.8kws4w==, time=4031, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone6-1.56+AEA==, time=4744, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.WKZK+A==, time=6001, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone5-1.IBb4nw==, time=41358, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1.IBb4nw==, peerAvailable=true, time=1152], sendList=[name=Apple-Iphone5s-1.8kws4w==, time=3310, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.WKZK+A==, time=4243, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1.mOZnMg==, time=5131, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-IpadAir2-1.hA+i5Q==, time=41827, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5s-1.+FhoNw==, peerAvailable=true, time=1394], sendList=[name=Apple-Iphone5-1.mOZnMg==, time=3920, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone6-1.56+AEA==, time=4261, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5s-1.8kws4w==, time=4908, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-IpadAir2-1.hA+i5Q==, time=41347, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=43468, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=43531, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=46338, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=46542, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=62530, peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=77071], sendList=[name=7C:F9:0E:34:8A:A0, time=41018, result=OK, connections=2, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=F8:95:C7:87:3C:51, time=0, result=Fail], notTriedList=[connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail], peersList=[peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=15618, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=26730, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=26848, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=33648, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=38099, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=45245, peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=76157], sendList=[name=08:EC:A9:50:75:41, time=72993, result=OK, connections=4, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=00:F4:6F:30:E0:6C, time=0, result=Fail], notTriedList=[connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail], peersList=[peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=6274, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=6283, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=6312, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=7199, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=14852, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=39781, peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=49917, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=49961, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=75163], sendList=[], failedPeer=[connections=1, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=1, name=00:F4:6F:30:E0:6C, time=0, result=Fail], notTriedList=[connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail], peersList=[peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=8350, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=false, time=98359, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=false, time=98361, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=false, time=98363, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=false, time=98365], sendList=[name=58:3F:54:73:64:C0, time=5764, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=F8:95:C7:87:85:54, time=5927, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:34:8A:A0, time=12378, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=1, name=00:F4:6F:30:E0:6C, time=0, result=Fail], notTriedList=[connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail], peersList=[peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=58886, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=58973, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=59010, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=59185, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=76690, peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=85938, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=85974, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=86359], sendList=[name=08:EC:A9:50:76:27, time=27574, result=OK, connections=2, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=F8:95:C7:87:85:54, time=29986, result=OK, connections=2, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=44:80:EB:7B:5A:05, time=40580, result=OK, connections=3, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=7C:F9:0E:34:8A:A0, time=0, result=Fail], notTriedList=[connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail], peersList=[peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=5293, peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=5340, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=5628, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=18158, peerName=Nexus 5, peerIdentifier=34:FC:EF:11:AE:67, peerAvailable=true, time=18247, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=93134, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=false, time=94895], peersList=[peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=3281, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=3325, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=3361, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=3455, peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=3695, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=76882, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=88623], peersList=[peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=3655, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=3719, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=4330, peerName=Nexus 5, peerIdentifier=34:FC:EF:11:AE:67, peerAvailable=true, time=7421, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=11066, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=14048, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=14336, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=14367, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=41999, peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=82795, peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=92952], sendList=[name=34:FC:EF:11:AE:67, time=26407, result=OK, connections=2, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=F8:95:C7:87:3C:51, time=0, result=Fail], notTriedList=[connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail], peersList=[peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=3523, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=3564, peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=3600, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=3655, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=3760, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=3850, peerName=Nexus 5, peerIdentifier=34:FC:EF:11:AE:67, peerAvailable=true, time=3946, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=4673, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=9171, peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=40858], sendList=[name=E0:DB:10:14:E2:C0, time=25491, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=08:EC:A9:50:76:27, time=69485, result=OK, connections=4, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=58:3F:54:73:64:C0, time=0, result=Fail], notTriedList=[connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail], peersList=[peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=22316, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=29370, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=29689], sendList=[name=7C:F9:0E:51:18:22, time=35497, result=OK, connections=2, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=44:80:EB:7B:5A:05, time=0, result=Fail], notTriedList=[connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail], peersList=[peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=4076, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=5729, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=15824, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=28317, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=82885, peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=95267], sendList=[name=F8:95:C7:87:85:54, time=9405, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=58:3F:54:73:64:C0, time=14202, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=08:EC:A9:50:76:27, time=15435, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=E0:DB:10:14:E2:C0, time=29468, result=OK, connections=2, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=00:F4:6F:30:E0:6C, time=0, result=Fail], notTriedList=[connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail], peersList=[peerName=Nexus 5, peerIdentifier=34:FC:EF:11:AE:67, peerAvailable=true, time=2544, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=2574, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=16093, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=16123, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=16191, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=57103, peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=66833, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=98763], sendList=[name=34:FC:EF:11:AE:67, time=9456, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=44:80:EB:7B:5A:05, time=10713, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=B0:C5:59:3F:75:69, time=11150, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:37:96:AB, time=30907, result=OK, connections=2, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=00:F4:6F:30:E0:6C, time=0, result=Fail], notTriedList=[connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail]

2016-01-12T12:25:28.136Z - debug: end to Thali Test (Galaxy A5)

2016-01-12T12:25:28.139Z - debug: end to Thali Test (Galaxy S5)

2016-01-12T12:25:28.141Z - debug: end to G4-1

2016-01-12T12:25:28.142Z - debug: end to Nexus 5

2016-01-12T12:25:28.144Z - debug: end to Note4-1

2016-01-12T12:25:28.145Z - debug: end to A5-1

2016-01-12T12:25:28.146Z - debug: end to XT1072

2016-01-12T12:25:28.147Z - debug: end to Thali Test (Galaxy A3)

2016-01-12T12:25:28.148Z - debug: end to A3-1

2016-01-12T12:25:28.150Z - debug: end to G3s-1

2016-01-12T12:25:28.151Z - debug: end to S5-1

2016-01-12T12:25:28.155Z - debug: end to S5mini-1

2016-01-12T12:25:28.157Z - debug: end to G3-1

2016-01-12T12:25:28.654Z - debug: Socket disconnected: transport close 3 (Nexus 5)

2016-01-12T12:25:28.925Z - debug: Socket disconnected: transport close 0 (Thali Test (Galaxy A5))

2016-01-12T12:25:29.096Z - debug: Socket disconnected: transport close 10 (Thali Test (Galaxy A3))

2016-01-12T12:25:29.298Z - debug: Socket disconnected: transport close 2 (G4-1)

2016-01-12T12:25:29.354Z - debug: Socket disconnected: transport close 12 (A3-1)

2016-01-12T12:25:30.028Z - debug: Socket disconnected: transport close 1 (Thali Test (Galaxy S5))

2016-01-12T12:25:30.837Z - debug: Socket disconnected: transport close 14 (S5-1)

2016-01-12T12:25:31.065Z - debug: Socket disconnected: transport close 16 (G3-1)

2016-01-12T12:25:31.169Z - debug: Socket disconnected: ping timeout 8 (XT1072)

2016-01-12T12:25:31.267Z - debug: Socket disconnected: transport close 4 (Note4-1)

2016-01-12T12:25:35.190Z - debug: Socket disconnected: transport close 13 (G3s-1)

2016-01-12T12:26:20.095Z - debug: Socket disconnected: ping timeout 6 (A5-1)


 
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
Device test finished on LGH8153b36be34 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:null 
child process exited with code null on device f56ad48d 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/55742142a5c2fdb_Temporary_test_for_install_reliability__vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/55742142a5c2fdb_Temporary_test_for_install_reliability__vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/55742142a5c2fdb_Temporary_test_for_install_reliability__vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/55742142a5c2fdb_Temporary_test_for_install_reliability__vjrantal/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/55742142a5c2fdb_Temporary_test_for_install_reliability__vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/55742142a5c2fdb_Temporary_test_for_install_reliability__vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/55742142a5c2fdb_Temporary_test_for_install_reliability__vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  0be0c6c6 Test has  SUCCEEDED
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 0be0c6c6 
Device test finished on 41006f95c8139173 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/55742142a5c2fdb_Temporary_test_for_install_reliability__vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/55742142a5c2fdb_Temporary_test_for_install_reliability__vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/55742142a5c2fdb_Temporary_test_for_install_reliability__vjrantal/thali04_samsung-SM-G900F.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/55742142a5c2fdb_Temporary_test_for_install_reliability__vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/55742142a5c2fdb_Temporary_test_for_install_reliability__vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/55742142a5c2fdb_Temporary_test_for_install_reliability__vjrantal/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
STOP log received from  4db5c8cc Test has  SUCCEEDED
STOP log received from  c5afcdcb Test has  SUCCEEDED
Device test finished on 4db5c8cc 
Device test finished on c5afcdcb 
Android task is completed. [SUCCESS]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/55742142a5c2fdb_Temporary_test_for_install_reliability__vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/55742142a5c2fdb_Temporary_test_for_install_reliability__vjrantal/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/55742142a5c2fdb_Temporary_test_for_install_reliability__vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/55742142a5c2fdb_Temporary_test_for_install_reliability__vjrantal/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/55742142a5c2fdb_Temporary_test_for_install_reliability__vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/55742142a5c2fdb_Temporary_test_for_install_reliability__vjrantal/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/55742142a5c2fdb_Temporary_test_for_install_reliability__vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/55742142a5c2fdb_Temporary_test_for_install_reliability__vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/55742142a5c2fdb_Temporary_test_for_install_reliability__vjrantal/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/55742142a5c2fdb_Temporary_test_for_install_reliability__vjrantal/iOS_Iphone5s-1.md)



#### Test 55431344148e3f8 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-08T09:51:30.328Z - info: listening on *:3000

2016-01-08T09:51:31.527Z - debug: Device presented: Note4-1 (android) perftest socket:0

2016-01-08T09:51:31.534Z - info: Setting start timeout to: 120000 (android)

2016-01-08T09:51:31.650Z - debug: Device presented: HTC One M8s (android) perftest socket:2

2016-01-08T09:51:31.676Z - debug: Device presented: Nexus 5 (android) perftest socket:3

2016-01-08T09:51:31.970Z - debug: Device presented: Thali Test (Galaxy A3) (android) perftest socket:4

2016-01-08T09:51:32.089Z - debug: Device presented: A3-1 (android) perftest socket:5

2016-01-08T09:51:32.476Z - debug: Device presented: Apple-IpadAir2-1 (ios) perftest socket:6

2016-01-08T09:51:32.478Z - info: Setting start timeout to: 120000 (ios)

2016-01-08T09:51:32.619Z - debug: Device presented: Apple-Iphone6-1 (ios) perftest socket:8

2016-01-08T09:51:32.636Z - debug: Device presented: Thali Test (Galaxy S5) (android) perftest socket:7

2016-01-08T09:51:32.661Z - debug: Device presented: Apple-Iphone5-1 (ios) perftest socket:9

2016-01-08T09:51:33.005Z - debug: Device presented: G3s-1 (android) perftest socket:10

2016-01-08T09:51:33.069Z - debug: Device presented: S5-1 (android) perftest socket:11

2016-01-08T09:51:33.231Z - debug: Device presented: Thali Test (Galaxy A5) (android) perftest socket:12

2016-01-08T09:51:33.320Z - debug: Device presented: G4-1 (android) perftest socket:13

2016-01-08T09:51:34.095Z - debug: Device presented: Apple-Iphone5s-1 (ios) perftest socket:1

2016-01-08T09:51:34.098Z - info: Required number of devices presented

2016-01-08T09:51:34.103Z - info: Starting perf test run for platform: ios

2016-01-08T09:51:34.104Z - info: Using devices:

2016-01-08T09:51:34.105Z - info: Apple-IpadAir2-1
2016-01-08T09:51:34.106Z - info: Apple-Iphone6-1

2016-01-08T09:51:34.107Z - info: Apple-Iphone5-1

2016-01-08T09:51:34.108Z - info: Apple-Iphone5s-1

2016-01-08T09:51:34.116Z - info: Starting test: with 4 devices (ios)

2016-01-08T09:51:34.967Z - debug: Device presented: XT1072 (android) perftest socket:14

2016-01-08T09:51:35.297Z - debug: Device presented: A5-1 (android) perftest socket:15

2016-01-08T09:51:35.579Z - info: Received results for {"name:":"Apple-Iphone5-1","time":1174,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone5s-1.1B6pGw==","peerAvailable":true,"time":1170}]} Apple-Iphone5-1 ios (3 left)

2016-01-08T09:51:35.598Z - info: Received results for {"name:":"Apple-Iphone6-1","time":1248,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone5s-1.1B6pGw==","peerAvailable":true,"time":1246}]} Apple-Iphone6-1 ios (2 left)

2016-01-08T09:51:35.603Z - info: Received results for {"name:":"Apple-Iphone5s-1","time":1351,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone6-1.hx3ANw==","peerAvailable":true,"time":1348}]} Apple-Iphone5s-1 ios (1 left)

2016-01-08T09:51:35.927Z - debug: Device presented: G3-1 (android) perftest socket:16

2016-01-08T09:51:36.088Z - info: Received results for {"name:":"Apple-IpadAir2-1","time":1192,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone5s-1.1B6pGw==","peerAvailable":true,"time":1191}]} Apple-IpadAir2-1 ios (0 left)

2016-01-08T09:51:36.091Z - info: All test data retrieved for testFindPeers.js (ios)

2016-01-08T09:51:36.098Z - info: Remaining tests: testSendData.js

2016-01-08T09:51:36.110Z - info: Continuing to next test: testSendData.js

2016-01-08T09:51:36.111Z - info: Starting test: with 4 devices (ios)

2016-01-08T09:51:36.690Z - debug: Device presented: S5mini-1 (android) perftest socket:17

2016-01-08T09:51:38.082Z - debug: Device presented: XT1039 (android) perftest socket:18

2016-01-08T09:51:38.926Z - debug: Socket disconnected: transport close 17 (S5mini-1)

2016-01-08T09:51:39.627Z - debug: Socket disconnected: transport close 18 (XT1039)

2016-01-08T09:52:32.808Z - info: Received results for {"name:":"Apple-Iphone6-1","time":56112,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1.1B6pGw==","time":40818,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-Iphone5-1.AdDQ5g==","time":5437,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1.7azU7Q==","time":5057,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1.KjG2gw==","time":3755,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone6-1 ios (3 left)

2016-01-08T09:52:37.530Z - info: Received results for {"name:":"Apple-IpadAir2-1","time":61208,"result":"OK","sendList":[{"name":"Apple-Iphone5-1.rHC9Aw==","time":47179,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-Iphone5-1.AdDQ5g==","time":5448,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1.KjG2gw==","time":4418,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1.0EeFvA==","time":4016,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-IpadAir2-1 ios (2 left)

2016-01-08T09:53:13.239Z - info: Received results for {"name:":"Apple-Iphone5-1","time":96987,"result":"OK","sendList":[{"name":"Apple-Iphone6-1.hx3ANw==","time":41249,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-IpadAir2-1.7azU7Q==","time":46018,"result":"OK","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1.KjG2gw==","time":4693,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1.0EeFvA==","time":4825,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone5-1 ios (1 left)

2016-01-08T09:53:31.550Z - info: Start timeout elapsed for platform: android

2016-01-08T09:53:31.552Z - info: Starting perf test run for platform: android

2016-01-08T09:53:31.553Z - info: Using devices:

2016-01-08T09:53:31.554Z - info: Note4-1

2016-01-08T09:53:31.555Z - info: HTC One M8s

2016-01-08T09:53:31.558Z - info: Nexus 5

2016-01-08T09:53:31.559Z - info: Thali Test (Galaxy A3)

2016-01-08T09:53:31.560Z - info: A3-1
2016-01-08T09:53:31.561Z - info: Thali Test (Galaxy S5)
2016-01-08T09:53:31.562Z - info: G3s-1

2016-01-08T09:53:31.563Z - info: S5-1

2016-01-08T09:53:31.565Z - info: Thali Test (Galaxy A5)

2016-01-08T09:53:31.566Z - info: G4-1

2016-01-08T09:53:31.567Z - info: XT1072
2016-01-08T09:53:31.568Z - info: A5-1
2016-01-08T09:53:31.569Z - info: G3-1
2016-01-08T09:53:31.570Z - info: S5mini-1
2016-01-08T09:53:31.571Z - info: XT1039

2016-01-08T09:53:31.572Z - info: Starting test: with 15 devices (android)

2016-01-08T09:53:32.531Z - info: Start timeout elapsed for platform: ios

2016-01-08T09:53:32.534Z - info: Tests for ios already running or completed

2016-01-08T09:53:34.073Z - info: Received results for {"name:":"Apple-Iphone5s-1","time":100021,"result":"OK","sendList":[{"name":"Apple-Iphone6-1.hx3ANw==","time":41146,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-Iphone5-1.AdDQ5g==","time":40148,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-IpadAir2-1.7azU7Q==","time":14747,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1.0EeFvA==","time":3659,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone5s-1 ios (0 left)

2016-01-08T09:53:34.074Z - info: All test data retrieved for testSendData.js (ios)

2016-01-08T09:53:34.083Z - info: ALL DONE !!!

{ 'name:': 'Apple-IpadAir2-1',
  time: 1192,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5s-1.1B6pGw==',
       peerAvailable: true,
       time: 1191 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 1248,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5s-1.1B6pGw==',
       peerAvailable: true,
       time: 1246 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 1174,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5s-1.1B6pGw==',
       peerAvailable: true,
       time: 1170 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 1351,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1.hx3ANw==',
       peerAvailable: true,
       time: 1348 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 61208,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.rHC9Aw==',
       time: 47179,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.AdDQ5g==',
       time: 5448,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.KjG2gw==',
       time: 4418,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.0EeFvA==',
       time: 4016,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 56112,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5s-1.1B6pGw==',
       time: 40818,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.AdDQ5g==',
       time: 5437,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1.7azU7Q==',
       time: 5057,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.KjG2gw==',
       time: 3755,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 96987,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1.hx3ANw==',
       time: 41249,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.7azU7Q==',
       time: 46018,
       result: 'OK',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.KjG2gw==',
       time: 4693,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.0EeFvA==',
       time: 4825,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 100021,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1.hx3ANw==',
       time: 41146,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.AdDQ5g==',
       time: 40148,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.7azU7Q==',
       time: 14747,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.0EeFvA==',
       time: 3659,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

--------------- test report ---------------------
--------------- Apple-IpadAir2-1 --------------------- : 1

Find peers : 100% : 1191 ms, 99% : 1191 ms, 95 : 1191 ms, 90% : 1191 ms.

Result count 1, range 1191 ms to  1191 ms.

Send data : 100% : 5448 ms, 99% : 5448 ms, 95 : 5448 ms, 90% : 5448 ms.

Average data rate: 0.022 MB/s

Result count 3, range 4016 ms to  5448 ms.

Send data failed peers count : 1 [25 %]

- Peer ID : Apple-Iphone5-1.rHC9Aw==, Tried : 5

Send data never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1 --------------------- : 2

Find peers : 100% : 1246 ms, 99% : 1246 ms, 95 : 1246 ms, 90% : 1246 ms.
Result count 1, range 1246 ms to  1246 ms.

Send data : 100% : 5437 ms, 99% : 5437 ms, 95 : 5437 ms, 90% : 5437 ms.
Average data rate: 0.021 MB/s

Result count 3, range 3755 ms to  5437 ms.
Send data failed peers count : 1 [25 %]

- Peer ID : Apple-Iphone5s-1.1B6pGw==, Tried : 5
Send data never tried peers count : 0 [0 %]

--------------- Apple-Iphone5-1 --------------------- : 3
Find peers : 100% : 1170 ms, 99% : 1170 ms, 95 : 1170 ms, 90% : 1170 ms.

Result count 1, range 1170 ms to  1170 ms.
Send data : 100% : 46018 ms, 99% : 46018 ms, 95 : 46018 ms, 90% : 46018 ms.

Average data rate: 0.005 MB/s
Result count 3, range 4693 ms to  46018 ms.
Send data failed peers count : 1 [25 %]

- Peer ID : Apple-Iphone6-1.hx3ANw==, Tried : 5
Send data never tried peers count : 0 [0 %]
--------------- Apple-Iphone5s-1 --------------------- : 4

Find peers : 100% : 1348 ms, 99% : 1348 ms, 95 : 1348 ms, 90% : 1348 ms.
Result count 1, range 1348 ms to  1348 ms.

Send data : 100% : 14747 ms, 99% : 14747 ms, 95 : 14747 ms, 90% : 14747 ms.
Average data rate: 0.011 MB/s

Result count 2, range 3659 ms to  14747 ms.
Send data failed peers count : 2 [50 %]

- Peer ID : Apple-Iphone6-1.hx3ANw==, Tried : 5
- Peer ID : Apple-Iphone5-1.AdDQ5g==, Tried : 5
Send data never tried peers count : 0 [0 %]

--------------- Combined ---------------------

Find peers : 100% : 1348 ms, 99% : 1348 ms, 95 : 1348 ms, 90% : 1348 ms.

Send data : 100% : 46018 ms, 99% : 46018 ms, 95 : 14747 ms, 90% : 14747 ms.

Average data rate: 0.011 MB/s
--------------- end of test report ---------------------

2016-01-08T09:53:34.214Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-Iphone5s-1.1B6pGw==, peerAvailable=true, time=1191], sendList=[name=Apple-Iphone6-1.0EeFvA==, time=4016, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5s-1.KjG2gw==, time=4418, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1.AdDQ5g==, time=5448, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone5-1.rHC9Aw==, time=47179, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5s-1.1B6pGw==, peerAvailable=true, time=1246], sendList=[name=Apple-Iphone5s-1.KjG2gw==, time=3755, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.7azU7Q==, time=5057, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1.AdDQ5g==, time=5437, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone5s-1.1B6pGw==, time=40818, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5s-1.1B6pGw==, peerAvailable=true, time=1170], sendList=[name=Apple-Iphone5s-1.KjG2gw==, time=4693, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone6-1.0EeFvA==, time=4825, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.7azU7Q==, time=46018, result=OK, connections=5, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone6-1.hx3ANw==, time=41249, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1.hx3ANw==, peerAvailable=true, time=1348], sendList=[name=Apple-Iphone6-1.0EeFvA==, time=3659, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.7azU7Q==, time=14747, result=OK, connections=2, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone6-1.hx3ANw==, time=41146, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, name=Apple-Iphone5-1.AdDQ5g==, time=40148, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[]

2016-01-08T09:53:34.228Z - debug: end to Apple-IpadAir2-1

2016-01-08T09:53:34.230Z - debug: end to Apple-Iphone6-1

2016-01-08T09:53:34.235Z - debug: end to Apple-Iphone5-1

2016-01-08T09:53:34.237Z - debug: end to Apple-Iphone5s-1

2016-01-08T09:53:36.986Z - debug: Socket disconnected: transport close 6 (Apple-IpadAir2-1)

2016-01-08T09:53:37.406Z - debug: Socket disconnected: transport close 9 (Apple-Iphone5-1)

2016-01-08T09:53:40.224Z - debug: Socket disconnected: transport close 1 (Apple-Iphone5s-1)

2016-01-08T09:54:10.182Z - debug: state: android running

2016-01-08T09:54:10.183Z - debug: state: ios completed

2016-01-08T09:54:12.828Z - debug: Socket disconnected: transport close 8 (Apple-Iphone6-1)

2016-01-08T09:55:11.770Z - info: Received results for {"name:":"Note4-1","time":100094,"result":"TIMEOUT","peersList":[{"peerName":"XT1072","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":false,"time":66642},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":12720},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":15557},{"peerName":"HTC One M8s","peerIdentifier":"90:E7:C4:F6:69:77","peerAvailable":true,"time":69445},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":90016},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":90101}]} Note4-1 android (14 left)

2016-01-08T09:55:11.775Z - info: Received results for {"name:":"G4-1","time":100074,"result":"TIMEOUT","peersList":[{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":59335},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":97805},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":97835}]} G4-1 android (13 left)

2016-01-08T09:55:11.789Z - info: Received results for {"name:":"Thali Test (Galaxy A5)","time":100069,"result":"TIMEOUT","peersList":[{"peerName":"Nexus 5","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":true,"time":3303},{"peerName":"HTC One M8s","peerIdentifier":"90:E7:C4:F6:69:77","peerAvailable":true,"time":3358},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":41555},{"peerName":"XT1072","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true,"time":41870},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":42834},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":44344},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":46717},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":54488},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":57052},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":65850}]} Thali Test (Galaxy A5) android (12 left)

2016-01-08T09:55:11.997Z - info: Received results for {"name:":"A5-1","time":100075,"result":"TIMEOUT","peersList":[{"peerName":"XT1072","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true,"time":40259},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":83758},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":85522},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":90006},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":93490}]} A5-1 android (11 left)

2016-01-08T09:55:12.003Z - info: Received results for {"name:":"Nexus 5","time":100061,"result":"TIMEOUT","peersList":[{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":46633},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":47361},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":48313},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":49076},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":59229},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":59762},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":71213}]} Nexus 5 android (10 left)

2016-01-08T09:55:12.009Z - info: Received results for {"name:":"HTC One M8s","time":100068,"result":"TIMEOUT","peersList":[{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":3683},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":5337},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":5467},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":9341},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":10260},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":10334},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":18641},{"peerName":"Note4-1","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":21674},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":29467},{"peerName":"Nexus 5","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":true,"time":40167}]} HTC One M8s android (9 left)

2016-01-08T09:55:12.045Z - info: Received results for {"name:":"XT1072","time":100159,"result":"TIMEOUT","peersList":[{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":3040},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":false,"time":93041},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":39867},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":76511},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":81369}]} XT1072 android (8 left)

2016-01-08T09:55:12.073Z - info: Received results for {"name:":"S5-1","time":100156,"result":"TIMEOUT","peersList":[{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":3795},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":85775},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":99358}]} S5-1 android (7 left)

2016-01-08T09:55:12.418Z - info: Received results for {"name:":"Thali Test (Galaxy A3)","time":100062,"result":"TIMEOUT","peersList":[{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":39939},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":44597},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":46017},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":53871},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":91821},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":94082}]} Thali Test (Galaxy A3) android (6 left)

2016-01-08T09:55:12.423Z - info: Received results for {"name:":"G3s-1","time":100125,"result":"TIMEOUT","peersList":[{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":3280},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":9437},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":73671},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":96621}]} G3s-1 android (5 left)

2016-01-08T09:55:12.439Z - info: Received results for {"name:":"G3-1","time":100085,"result":"TIMEOUT","peersList":[{"peerName":"Note4-1","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":1588},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":1629},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":1685},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":false,"time":91604},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":13057},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":13484},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":38405},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":38448},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":61113}]} G3-1 android (4 left)

2016-01-08T09:55:12.450Z - info: Received results for {"name:":"A3-1","time":100057,"result":"TIMEOUT","peersList":[{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":41170},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":41465},{"peerName":"HTC One M8s","peerIdentifier":"90:E7:C4:F6:69:77","peerAvailable":true,"time":41527},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":41597},{"peerName":"Nexus 5","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":true,"time":46663},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":53691},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":90928},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":91054}]} A3-1 android (3 left)

2016-01-08T09:55:18.231Z - info: Received results for {"name:":"Thali Test (Galaxy S5)","time":100128,"result":"TIMEOUT","peersList":[{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":5450},{"peerName":"Note4-1","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":22191},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":31514},{"peerName":"Nexus 5","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":true,"time":34013},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":50874},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":76316},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":91679},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":91684}]} Thali Test (Galaxy S5) android (2 left)

2016-01-08T09:55:31.579Z - info: server timeout for test: testFindPeers.js (android)

2016-01-08T09:55:31.582Z - info: All test data retrieved for testFindPeers.js (android)

2016-01-08T09:55:31.600Z - info: No results from S5mini-1

2016-01-08T09:55:31.601Z - info: No results from XT1039

2016-01-08T09:55:31.603Z - info: Remaining tests: testSendData.js

2016-01-08T09:55:31.605Z - info: Continuing to next test: testSendData.js

2016-01-08T09:55:31.629Z - info: Starting test: with 15 devices (android)

2016-01-08T09:55:45.197Z - debug: Socket disconnected: transport close 14 (XT1072)

2016-01-08T09:57:11.833Z - info: Received results for {"name:":"Nexus 5","time":100049,"result":"TIMEOUT","sendList":[{"name":"F8:95:C7:87:85:54","time":6802,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":1,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"}]} Nexus 5 android (14 left)

2016-01-08T09:57:11.864Z - info: Received results for {"name:":"G4-1","time":100079,"result":"TIMEOUT","sendList":[{"name":"F8:95:C7:87:85:54","time":17876,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:34:8A:A0","time":10550,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":8612,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":1,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"}]} G4-1 android (13 left)

2016-01-08T09:57:11.906Z - info: Received results for {"name:":"Thali Test (Galaxy A3)","time":100079,"result":"TIMEOUT","sendList":[{"name":"F8:95:C7:87:3C:51","time":8766,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":27699,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"90:E7:C4:F6:69:77","time":30803,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"}]} Thali Test (Galaxy A3) android (12 left)

2016-01-08T09:57:11.912Z - info: Received results for {"name:":"A5-1","time":100083,"result":"TIMEOUT","sendList":[{"name":"F8:95:C7:87:85:54","time":7675,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"}]} A5-1 android (11 left)

2016-01-08T09:57:11.921Z - info: Received results for {"name:":"A3-1","time":100105,"result":"TIMEOUT","sendList":[{"name":"B0:C5:59:3F:75:69","time":17146,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:34:8A:A0","time":3836,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"58:3F:54:73:64:C0","time":3857,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"}]} A3-1 android (10 left)

2016-01-08T09:57:12.081Z - info: Received results for {"name:":"S5-1","time":100098,"result":"TIMEOUT","sendList":[{"name":"58:3F:54:73:64:C0","time":48933,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":5142,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:37:96:AB","time":27851,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":12252,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"}]} S5-1 android (9 left)

2016-01-08T09:57:12.087Z - info: Received results for {"name:":"Thali Test (Galaxy S5)","time":100101,"result":"TIMEOUT","sendList":[{"connections":1,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":1,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"}]} Thali Test (Galaxy S5) android (8 left)

2016-01-08T09:57:16.059Z - info: Received results for {"name:":"Thali Test (Galaxy A5)","time":100094,"result":"TIMEOUT","sendList":[{"name":"B0:C5:59:3F:75:69","time":13923,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"}]} Thali Test (Galaxy A5) android (7 left)

2016-01-08T09:57:17.972Z - info: Received results for {"name:":"G3-1","time":100108,"result":"TIMEOUT","sendList":[{"name":"08:EC:A9:50:75:41","time":14607,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":1,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"}]} G3-1 android (6 left)

2016-01-08T09:57:31.634Z - info: server timeout for test: testSendData.js (android)
2016-01-08T09:57:31.635Z - info: All test data retrieved for testSendData.js (android)

2016-01-08T09:57:31.637Z - info: No results from Note4-1

2016-01-08T09:57:31.641Z - info: No results from HTC One M8s

2016-01-08T09:57:31.646Z - info: No results from G3s-1

2016-01-08T09:57:31.655Z - info: No results from XT1072

2016-01-08T09:57:31.658Z - info: No results from S5mini-1

2016-01-08T09:57:31.659Z - info: No results from XT1039

2016-01-08T09:57:31.661Z - info: ALL DONE !!!

{ 'name:': 'Apple-IpadAir2-1',
  time: 1192,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5s-1.1B6pGw==',
       peerAvailable: true,
       time: 1191 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 1248,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5s-1.1B6pGw==',
       peerAvailable: true,
       time: 1246 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 1174,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5s-1.1B6pGw==',
       peerAvailable: true,
       time: 1170 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 1351,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1.hx3ANw==',
       peerAvailable: true,
       time: 1348 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 61208,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.rHC9Aw==',
       time: 47179,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.AdDQ5g==',
       time: 5448,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.KjG2gw==',
       time: 4418,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.0EeFvA==',
       time: 4016,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 56112,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5s-1.1B6pGw==',
       time: 40818,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.AdDQ5g==',
       time: 5437,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1.7azU7Q==',
       time: 5057,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.KjG2gw==',
       time: 3755,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 96987,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1.hx3ANw==',
       time: 41249,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.7azU7Q==',
       time: 46018,
       result: 'OK',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.KjG2gw==',
       time: 4693,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.0EeFvA==',
       time: 4825,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 100021,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1.hx3ANw==',
       time: 41146,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.AdDQ5g==',
       time: 40148,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.7azU7Q==',
       time: 14747,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.0EeFvA==',
       time: 3659,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Note4-1',
  time: 100094,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: false,
       time: 66642 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 12720 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 15557 },
     { peerName: 'HTC One M8s',
       peerIdentifier: '90:E7:C4:F6:69:77',
       peerAvailable: true,
       time: 69445 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 90016 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 90101 } ] }

{ 'name:': 'HTC One M8s',
  time: 100068,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 3683 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 5337 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 5467 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 9341 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 10260 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 10334 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 18641 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 21674 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 29467 },
     { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 40167 } ] }

{ 'name:': 'Nexus 5',
  time: 100061,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 46633 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 47361 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 48313 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 49076 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 59229 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 59762 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 71213 } ] }

{ 'name:': 'Thali Test (Galaxy A3)',
  time: 100062,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 39939 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 44597 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 46017 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 53871 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 91821 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 94082 } ] }

{ 'name:': 'A3-1',
  time: 100057,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 41170 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 41465 },
     { peerName: 'HTC One M8s',
       peerIdentifier: '90:E7:C4:F6:69:77',
       peerAvailable: true,
       time: 41527 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 41597 },
     { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 46663 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 53691 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 90928 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 91054 } ] }

{ 'name:': 'Thali Test (Galaxy S5)',
  time: 100128,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 5450 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 22191 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 31514 },
     { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 34013 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 50874 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 76316 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 91679 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 91684 } ] }

{ 'name:': 'G3s-1',
  time: 100125,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 3280 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 9437 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 73671 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 96621 } ] }

{ 'name:': 'S5-1',
  time: 100156,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 3795 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 85775 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 99358 } ] }

{ 'name:': 'Thali Test (Galaxy A5)',
  time: 100069,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 3303 },
     { peerName: 'HTC One M8s',
       peerIdentifier: '90:E7:C4:F6:69:77',
       peerAvailable: true,
       time: 3358 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 41555 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 41870 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 42834 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 44344 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 46717 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 54488 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 57052 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 65850 } ] }

{ 'name:': 'G4-1',
  time: 100074,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 59335 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 97805 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 97835 } ] }

{ 'name:': 'XT1072',
  time: 100159,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 3040 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: false,
       time: 93041 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 39867 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 76511 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 81369 } ] }

{ 'name:': 'A5-1',
  time: 100075,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 40259 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 83758 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 85522 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 90006 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 93490 } ] }

{ 'name:': 'G3-1',
  time: 100085,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 1588 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 1629 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 1685 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: false,
       time: 91604 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 13057 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 13484 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 38405 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 38448 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 61113 } ] }

{ 'name:': 'Nexus 5',
  time: 100049,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'F8:95:C7:87:85:54',
       time: 6802,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: '58:3F:54:73:64:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '90:E7:C4:F6:69:77',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '00:F4:6F:30:E0:6C',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:37:96:AB',
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
       name: '7C:F9:0E:34:8A:A0',
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
       name: 'B0:C5:59:3F:75:69',
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
     { connections: 1,
       name: 'F4:F1:E1:5C:3B:E2',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Thali Test (Galaxy A3)',
  time: 100079,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'F8:95:C7:87:3C:51',
       time: 8766,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'B0:C5:59:3F:75:69',
       time: 27699,
       result: 'OK',
       connections: 2,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '90:E7:C4:F6:69:77',
       time: 30803,
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
       name: 'E0:DB:10:14:E2:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F4:F1:E1:5C:3B:E2',
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
       name: '58:3F:54:73:64:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '00:F4:6F:30:E0:6C',
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
       name: 'F8:95:C7:87:85:54',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'A3-1',
  time: 100105,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'B0:C5:59:3F:75:69',
       time: 17146,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:34:8A:A0',
       time: 3836,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '58:3F:54:73:64:C0',
       time: 3857,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: '7C:F9:0E:51:18:22',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F8:95:C7:87:3C:51',
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
       name: 'E0:DB:10:14:E2:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '90:E7:C4:F6:69:77',
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
       result: 'Fail' } ] }

{ 'name:': 'Thali Test (Galaxy S5)',
  time: 100101,
  result: 'TIMEOUT',
  sendList: 
   [ { connections: 1,
       name: '44:80:EB:7B:5A:05',
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
     { connections: 0,
       name: '7C:F9:0E:37:96:AB',
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
       name: '7C:F9:0E:51:18:22',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F8:95:C7:87:85:54',
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
       name: '7C:F9:0E:34:8A:A0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '90:E7:C4:F6:69:77',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:11:AE:67',
       time: 0,
       result: 'Fail' },
     { connections: 1,
       name: 'F4:F1:E1:5C:3B:E2',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'S5-1',
  time: 100098,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '58:3F:54:73:64:C0',
       time: 48933,
       result: 'OK',
       connections: 2,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'E0:DB:10:14:E2:C0',
       time: 5142,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:37:96:AB',
       time: 27851,
       result: 'OK',
       connections: 2,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:3C:51',
       time: 12252,
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
       name: '90:E7:C4:F6:69:77',
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
       name: 'F8:95:C7:87:85:54',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'B0:C5:59:3F:75:69',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:11:AE:67',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:51:18:22',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F4:F1:E1:5C:3B:E2',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '44:80:EB:7B:5A:05',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Thali Test (Galaxy A5)',
  time: 100094,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'B0:C5:59:3F:75:69',
       time: 13923,
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
       name: '08:EC:A9:50:75:41',
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
     { connections: 0,
       name: 'E0:DB:10:14:E2:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:76:27',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F4:F1:E1:5C:3B:E2',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:37:96:AB',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '90:E7:C4:F6:69:77',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '58:3F:54:73:64:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F8:95:C7:87:85:54',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:34:8A:A0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '00:F4:6F:30:E0:6C',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'G4-1',
  time: 100079,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'F8:95:C7:87:85:54',
       time: 17876,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:34:8A:A0',
       time: 10550,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'B0:C5:59:3F:75:69',
       time: 8612,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: '7C:F9:0E:51:18:22',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '44:80:EB:7B:5A:05',
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
       name: '08:EC:A9:50:76:27',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:75:41',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'E0:DB:10:14:E2:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '90:E7:C4:F6:69:77',
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
     { connections: 1,
       name: '00:F4:6F:30:E0:6C',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'A5-1',
  time: 100083,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'F8:95:C7:87:85:54',
       time: 7675,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: '7C:F9:0E:51:18:22',
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
       name: '08:EC:A9:50:75:41',
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
       name: '90:E7:C4:F6:69:77',
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
       name: '34:FC:EF:11:AE:67',
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
       name: 'B0:C5:59:3F:75:69',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'G3-1',
  time: 100108,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '08:EC:A9:50:75:41',
       time: 14607,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: '90:E7:C4:F6:69:77',
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
       name: '7C:F9:0E:51:18:22',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '44:80:EB:7B:5A:05',
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
       name: '7C:F9:0E:37:96:AB',
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
       name: '34:FC:EF:11:AE:67',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'B0:C5:59:3F:75:69',
       time: 0,
       result: 'Fail' },
     { connections: 1,
       name: 'F4:F1:E1:5C:3B:E2',
       time: 0,
       result: 'Fail' } ] }

--------------- test report ---------------------
--------------- Apple-IpadAir2-1 --------------------- : 1
Find peers : 100% : 1191 ms, 99% : 1191 ms, 95 : 1191 ms, 90% : 1191 ms.

Result count 1, range 1191 ms to  1191 ms.

Send data : 100% : 5448 ms, 99% : 5448 ms, 95 : 5448 ms, 90% : 5448 ms.

Average data rate: 0.022 MB/s
Result count 3, range 4016 ms to  5448 ms.

Send data failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone5-1.rHC9Aw==, Tried : 5

Send data never tried peers count : 0 [0 %]

--------------- Apple-Iphone6-1 --------------------- : 2
Find peers : 100% : 1246 ms, 99% : 1246 ms, 95 : 1246 ms, 90% : 1246 ms.

Result count 1, range 1246 ms to  1246 ms.

Send data : 100% : 5437 ms, 99% : 5437 ms, 95 : 5437 ms, 90% : 5437 ms.
Average data rate: 0.021 MB/s
Result count 3, range 3755 ms to  5437 ms.
Send data failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone5s-1.1B6pGw==, Tried : 5
Send data never tried peers count : 0 [0 %]
--------------- Apple-Iphone5-1 --------------------- : 3
Find peers : 100% : 1170 ms, 99% : 1170 ms, 95 : 1170 ms, 90% : 1170 ms.
Result count 1, range 1170 ms to  1170 ms.
Send data : 100% : 46018 ms, 99% : 46018 ms, 95 : 46018 ms, 90% : 46018 ms.
Average data rate: 0.005 MB/s
Result count 3, range 4693 ms to  46018 ms.
Send data failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone6-1.hx3ANw==, Tried : 5
Send data never tried peers count : 0 [0 %]
--------------- Apple-Iphone5s-1 --------------------- : 4
Find peers : 100% : 1348 ms, 99% : 1348 ms, 95 : 1348 ms, 90% : 1348 ms.
Result count 1, range 1348 ms to  1348 ms.
Send data : 100% : 14747 ms, 99% : 14747 ms, 95 : 14747 ms, 90% : 14747 ms.
Average data rate: 0.011 MB/s
Result count 2, range 3659 ms to  14747 ms.
Send data failed peers count : 2 [50 %]
- Peer ID : Apple-Iphone6-1.hx3ANw==, Tried : 5
- Peer ID : Apple-Iphone5-1.AdDQ5g==, Tried : 5
Send data never tried peers count : 0 [0 %]
--------------- Note4-1 --------------------- : 5
Find peers : 100% : 90101 ms, 99% : 90101 ms, 95 : 90101 ms, 90% : 90016 ms.
Result count 6, range 12720 ms to  90101 ms.
--------------- HTC One M8s --------------------- : 6
Find peers : 100% : 40167 ms, 99% : 40167 ms, 95 : 40167 ms, 90% : 29467 ms.
Result count 10, range 3683 ms to  40167 ms.
--------------- Nexus 5 --------------------- : 7
Find peers : 100% : 71213 ms, 99% : 71213 ms, 95 : 71213 ms, 90% : 59762 ms.
Result count 7, range 46633 ms to  71213 ms.
Send data : 100% : 6802 ms, 99% : 6802 ms, 95 : 6802 ms, 90% : 6802 ms.
Average data rate: 0.015 MB/s
Result count 1, range 6802 ms to  6802 ms.
Send data failed peers count : 2 [66.66666666666667 %]
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
Send data never tried peers count : 11 [78.57142857142857 %]
- Peer ID : 90:E7:C4:F6:69:77
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 08:EC:A9:50:75:41
--------------- Thali Test (Galaxy A3) --------------------- : 8
Find peers : 100% : 94082 ms, 99% : 94082 ms, 95 : 94082 ms, 90% : 91821 ms.
Result count 6, range 39939 ms to  94082 ms.
Send data : 100% : 30803 ms, 99% : 30803 ms, 95 : 30803 ms, 90% : 30803 ms.

Average data rate: 0.004 MB/s
Result count 3, range 8766 ms to  30803 ms.
Send data failed peers count : 1 [25 %]
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
Send data never tried peers count : 10 [71.42857142857143 %]
- Peer ID : E0:DB:10:14:E2:C0

- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 08:EC:A9:50:75:41

- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 7C:F9:0E:51:18:22

- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : F8:95:C7:87:85:54

--------------- A3-1 --------------------- : 9
Find peers : 100% : 91054 ms, 99% : 91054 ms, 95 : 91054 ms, 90% : 90928 ms.
Result count 8, range 41170 ms to  91054 ms.
Send data : 100% : 17146 ms, 99% : 17146 ms, 95 : 17146 ms, 90% : 17146 ms.
Average data rate: 0.012 MB/s
Result count 3, range 3836 ms to  17146 ms.
Send data failed peers count : 1 [25 %]
- Peer ID : 7C:F9:0E:51:18:22, Tried : 1
Send data never tried peers count : 10 [71.42857142857143 %]
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 90:E7:C4:F6:69:77
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : F8:95:C7:87:85:54
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 44:80:EB:7B:5A:05
--------------- Thali Test (Galaxy S5) --------------------- : 10
Find peers : 100% : 91684 ms, 99% : 91684 ms, 95 : 91684 ms, 90% : 91679 ms.
Result count 8, range 5450 ms to  91684 ms.
No send data results!
--------------- G3s-1 --------------------- : 11
Find peers : 100% : 96621 ms, 99% : 96621 ms, 95 : 96621 ms, 90% : 96621 ms.
Result count 4, range 3280 ms to  96621 ms.

--------------- S5-1 --------------------- : 12
Find peers : 100% : 99358 ms, 99% : 99358 ms, 95 : 99358 ms, 90% : 99358 ms.
Result count 3, range 3795 ms to  99358 ms.

Send data : 100% : 48933 ms, 99% : 48933 ms, 95 : 48933 ms, 90% : 48933 ms.
Average data rate: 0.004 MB/s
Result count 4, range 5142 ms to  48933 ms.

Send data failed peers count : 1 [20 %]

- Peer ID : 08:EC:A9:50:75:41, Tried : 1
Send data never tried peers count : 9 [64.28571428571429 %]
- Peer ID : 90:E7:C4:F6:69:77

- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 08:EC:A9:50:76:27

- Peer ID : F8:95:C7:87:85:54
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 34:FC:EF:11:AE:67

- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : F4:F1:E1:5C:3B:E2

- Peer ID : 44:80:EB:7B:5A:05
--------------- Thali Test (Galaxy A5) --------------------- : 13

Find peers : 100% : 65850 ms, 99% : 65850 ms, 95 : 65850 ms, 90% : 57052 ms.
Result count 10, range 3303 ms to  65850 ms.

Send data : 100% : 13923 ms, 99% : 13923 ms, 95 : 13923 ms, 90% : 13923 ms.

Average data rate: 0.007 MB/s
Result count 1, range 13923 ms to  13923 ms.
Send data failed peers count : 1 [50 %]

- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
Send data never tried peers count : 12 [85.71428571428571 %]

- Peer ID : 08:EC:A9:50:75:41
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 44:80:EB:7B:5A:05

- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : F4:F1:E1:5C:3B:E2

- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 90:E7:C4:F6:69:77
- Peer ID : 58:3F:54:73:64:C0

- Peer ID : F8:95:C7:87:85:54
- Peer ID : 7C:F9:0E:34:8A:A0

- Peer ID : 00:F4:6F:30:E0:6C
--------------- G4-1 --------------------- : 14

Find peers : 100% : 97835 ms, 99% : 97835 ms, 95 : 97835 ms, 90% : 97835 ms.
Result count 3, range 59335 ms to  97835 ms.
Send data : 100% : 17876 ms, 99% : 17876 ms, 95 : 17876 ms, 90% : 17876 ms.

Average data rate: 0.008 MB/s
Result count 3, range 8612 ms to  17876 ms.

Send data failed peers count : 2 [40 %]
- Peer ID : 7C:F9:0E:51:18:22, Tried : 1

- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
Send data never tried peers count : 9 [64.28571428571429 %]
- Peer ID : 44:80:EB:7B:5A:05

- Peer ID : 58:3F:54:73:64:C0
- Peer ID : F4:F1:E1:5C:3B:E2

- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : E0:DB:10:14:E2:C0

- Peer ID : 90:E7:C4:F6:69:77
- Peer ID : 7C:F9:0E:37:96:AB

- Peer ID : 34:FC:EF:11:AE:67
--------------- XT1072 --------------------- : 15

Find peers : 100% : 93041 ms, 99% : 93041 ms, 95 : 93041 ms, 90% : 93041 ms.
Result count 5, range 3040 ms to  93041 ms.

--------------- A5-1 --------------------- : 16
Find peers : 100% : 93490 ms, 99% : 93490 ms, 95 : 93490 ms, 90% : 93490 ms.
Result count 5, range 40259 ms to  93490 ms.

Send data : 100% : 7675 ms, 99% : 7675 ms, 95 : 7675 ms, 90% : 7675 ms.
Average data rate: 0.013 MB/s

Result count 1, range 7675 ms to  7675 ms.
Send data failed peers count : 1 [50 %]

- Peer ID : 7C:F9:0E:51:18:22, Tried : 1
Send data never tried peers count : 12 [85.71428571428571 %]
- Peer ID : 44:80:EB:7B:5A:05

- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 08:EC:A9:50:75:41

- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 90:E7:C4:F6:69:77

- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : F4:F1:E1:5C:3B:E2

- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 58:3F:54:73:64:C0

- Peer ID : B0:C5:59:3F:75:69
--------------- G3-1 --------------------- : 17

Find peers : 100% : 91604 ms, 99% : 91604 ms, 95 : 91604 ms, 90% : 61113 ms.
Result count 9, range 1588 ms to  91604 ms.

Send data : 100% : 14607 ms, 99% : 14607 ms, 95 : 14607 ms, 90% : 14607 ms.
Average data rate: 0.007 MB/s
Result count 1, range 14607 ms to  14607 ms.

Send data failed peers count : 2 [66.66666666666667 %]
- Peer ID : 90:E7:C4:F6:69:77, Tried : 1

- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
Send data never tried peers count : 11 [78.57142857142857 %]
- Peer ID : 08:EC:A9:50:76:27

- Peer ID : F8:95:C7:87:85:54
- Peer ID : 7C:F9:0E:51:18:22

- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 00:F4:6F:30:E0:6C

- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : E0:DB:10:14:E2:C0

- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : B0:C5:59:3F:75:69

--------------- Combined ---------------------

Find peers : 100% : 99358 ms, 99% : 97835 ms, 95 : 94082 ms, 90% : 91679 ms.

Send data : 100% : 48933 ms, 99% : 48933 ms, 95 : 46018 ms, 90% : 27851 ms.
Average data rate: 0.008 MB/s

--------------- end of test report ---------------------

2016-01-08T09:57:32.101Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-Iphone5s-1.1B6pGw==, peerAvailable=true, time=1191], sendList=[name=Apple-Iphone6-1.0EeFvA==, time=4016, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5s-1.KjG2gw==, time=4418, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1.AdDQ5g==, time=5448, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone5-1.rHC9Aw==, time=47179, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5s-1.1B6pGw==, peerAvailable=true, time=1246], sendList=[name=Apple-Iphone5s-1.KjG2gw==, time=3755, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.7azU7Q==, time=5057, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1.AdDQ5g==, time=5437, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone5s-1.1B6pGw==, time=40818, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5s-1.1B6pGw==, peerAvailable=true, time=1170], sendList=[name=Apple-Iphone5s-1.KjG2gw==, time=4693, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone6-1.0EeFvA==, time=4825, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.7azU7Q==, time=46018, result=OK, connections=5, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone6-1.hx3ANw==, time=41249, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1.hx3ANw==, peerAvailable=true, time=1348], sendList=[name=Apple-Iphone6-1.0EeFvA==, time=3659, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.7azU7Q==, time=14747, result=OK, connections=2, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone6-1.hx3ANw==, time=41146, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, name=Apple-Iphone5-1.AdDQ5g==, time=40148, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=12720, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=15557, peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=false, time=66642, peerName=HTC One M8s, peerIdentifier=90:E7:C4:F6:69:77, peerAvailable=true, time=69445, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=90016, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=90101], peersList=[peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=3683, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=5337, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=5467, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=9341, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=10260, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=10334, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=18641, peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=21674, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=29467, peerName=Nexus 5, peerIdentifier=34:FC:EF:11:AE:67, peerAvailable=true, time=40167], peersList=[peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=46633, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=47361, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=48313, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=49076, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=59229, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=59762, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=71213], sendList=[name=F8:95:C7:87:85:54, time=6802, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=1, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail], notTriedList=[connections=0, name=90:E7:C4:F6:69:77, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail], peersList=[peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=39939, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=44597, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=46017, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=53871, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=91821, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=94082], sendList=[name=F8:95:C7:87:3C:51, time=8766, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=B0:C5:59:3F:75:69, time=27699, result=OK, connections=2, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=90:E7:C4:F6:69:77, time=30803, result=OK, connections=2, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=44:80:EB:7B:5A:05, time=0, result=Fail], notTriedList=[connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail], peersList=[peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=41170, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=41465, peerName=HTC One M8s, peerIdentifier=90:E7:C4:F6:69:77, peerAvailable=true, time=41527, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=41597, peerName=Nexus 5, peerIdentifier=34:FC:EF:11:AE:67, peerAvailable=true, time=46663, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=53691, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=90928, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=91054], sendList=[name=7C:F9:0E:34:8A:A0, time=3836, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=58:3F:54:73:64:C0, time=3857, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=B0:C5:59:3F:75:69, time=17146, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=7C:F9:0E:51:18:22, time=0, result=Fail], notTriedList=[connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=90:E7:C4:F6:69:77, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail], peersList=[peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=5450, peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=22191, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=31514, peerName=Nexus 5, peerIdentifier=34:FC:EF:11:AE:67, peerAvailable=true, time=34013, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=50874, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=76316, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=91679, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=91684], sendList=[], failedPeer=[connections=1, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=1, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail], notTriedList=[connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=90:E7:C4:F6:69:77, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail], peersList=[peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=3280, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=9437, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=73671, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=96621], peersList=[peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=3795, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=85775, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=99358], sendList=[name=E0:DB:10:14:E2:C0, time=5142, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=F8:95:C7:87:3C:51, time=12252, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:37:96:AB, time=27851, result=OK, connections=2, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=58:3F:54:73:64:C0, time=48933, result=OK, connections=2, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=08:EC:A9:50:75:41, time=0, result=Fail], notTriedList=[connections=0, name=90:E7:C4:F6:69:77, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail], peersList=[peerName=Nexus 5, peerIdentifier=34:FC:EF:11:AE:67, peerAvailable=true, time=3303, peerName=HTC One M8s, peerIdentifier=90:E7:C4:F6:69:77, peerAvailable=true, time=3358, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=41555, peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=41870, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=42834, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=44344, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=46717, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=54488, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=57052, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=65850], sendList=[name=B0:C5:59:3F:75:69, time=13923, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=34:FC:EF:11:AE:67, time=0, result=Fail], notTriedList=[connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=90:E7:C4:F6:69:77, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail], peersList=[peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=59335, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=97805, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=97835], sendList=[name=B0:C5:59:3F:75:69, time=8612, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:34:8A:A0, time=10550, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=F8:95:C7:87:85:54, time=17876, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=1, name=00:F4:6F:30:E0:6C, time=0, result=Fail], notTriedList=[connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=90:E7:C4:F6:69:77, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail], peersList=[peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=3040, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=39867, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=76511, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=81369, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=false, time=93041], peersList=[peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=40259, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=83758, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=85522, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=90006, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=93490], sendList=[name=F8:95:C7:87:85:54, time=7675, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=7C:F9:0E:51:18:22, time=0, result=Fail], notTriedList=[connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=90:E7:C4:F6:69:77, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail], peersList=[peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=1588, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=1629, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=1685, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=13057, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=13484, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=38405, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=38448, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=61113, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=false, time=91604], sendList=[name=08:EC:A9:50:75:41, time=14607, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=90:E7:C4:F6:69:77, time=0, result=Fail, connections=1, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail], notTriedList=[connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail]

2016-01-08T09:57:32.246Z - debug: end to Note4-1

2016-01-08T09:57:32.249Z - debug: end to HTC One M8s

2016-01-08T09:57:32.252Z - debug: end to Nexus 5

2016-01-08T09:57:32.254Z - debug: end to Thali Test (Galaxy A3)

2016-01-08T09:57:32.255Z - debug: end to A3-1

2016-01-08T09:57:32.256Z - debug: end to Thali Test (Galaxy S5)
2016-01-08T09:57:32.258Z - debug: end to G3s-1

2016-01-08T09:57:32.259Z - debug: end to S5-1

2016-01-08T09:57:32.260Z - debug: end to Thali Test (Galaxy A5)

2016-01-08T09:57:32.261Z - debug: end to G4-1

2016-01-08T09:57:32.263Z - debug: end to XT1072

2016-01-08T09:57:32.264Z - debug: end to A5-1

2016-01-08T09:57:32.265Z - debug: end to G3-1

2016-01-08T09:57:32.269Z - debug: end to S5mini-1

2016-01-08T09:57:32.272Z - debug: end to XT1039

2016-01-08T09:57:33.111Z - debug: Socket disconnected: transport close 3 (Nexus 5)

2016-01-08T09:57:33.126Z - debug: Socket disconnected: transport close 5 (A3-1)

2016-01-08T09:57:33.237Z - debug: Socket disconnected: transport close 4 (Thali Test (Galaxy A3))

2016-01-08T09:57:33.372Z - debug: Socket disconnected: transport close 13 (G4-1)

2016-01-08T09:57:33.417Z - debug: Socket disconnected: transport close 7 (Thali Test (Galaxy S5))

2016-01-08T09:57:33.778Z - debug: Socket disconnected: transport close 11 (S5-1)

2016-01-08T09:57:37.816Z - debug: Socket disconnected: transport close 16 (G3-1)

2016-01-08T09:57:38.463Z - debug: Socket disconnected: transport close 12 (Thali Test (Galaxy A5))

2016-01-08T09:57:57.214Z - debug: Socket disconnected: ping timeout 0 (Note4-1)

2016-01-08T09:57:59.442Z - debug: Socket disconnected: ping timeout 10 (G3s-1)

2016-01-08T09:58:28.349Z - debug: Socket disconnected: ping timeout 2 (HTC One M8s)

2016-01-08T09:58:36.922Z - debug: Socket disconnected: ping timeout 15 (A5-1)

2016-01-08T09:59:37.244Z - debug: Device presented: G3s-1 (android) perftest socket:19

2016-01-08T09:59:37.245Z - info: Updating existing device: G3s-1 (57793165-907e-4458-ba5b-bb62c9ba9fd5)

2016-01-08T09:59:37.472Z - info: Received results for {"name:":"G3s-1","time":100137,"result":"TIMEOUT","sendList":[{"name":"B0:C5:59:3F:75:69","time":96547,"result":"OK","connections":5,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"}]} G3s-1 android (5 left)

2016-01-08T10:18:01.963Z - debug: Socket disconnected: transport close 19 (G3s-1)


 
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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/55431344148e3f8_Fix_an_issue_that_prevented_running_two_tests__vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/55431344148e3f8_Fix_an_issue_that_prevented_running_two_tests__vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/55431344148e3f8_Fix_an_issue_that_prevented_running_two_tests__vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/55431344148e3f8_Fix_an_issue_that_prevented_running_two_tests__vjrantal/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/55431344148e3f8_Fix_an_issue_that_prevented_running_two_tests__vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/55431344148e3f8_Fix_an_issue_that_prevented_running_two_tests__vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/55431344148e3f8_Fix_an_issue_that_prevented_running_two_tests__vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  0be0c6c6 Test has  SUCCEEDED
Device test finished on 0be0c6c6 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/55431344148e3f8_Fix_an_issue_that_prevented_running_two_tests__vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/55431344148e3f8_Fix_an_issue_that_prevented_running_two_tests__vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/55431344148e3f8_Fix_an_issue_that_prevented_running_two_tests__vjrantal/thali04_samsung-SM-G900F.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/55431344148e3f8_Fix_an_issue_that_prevented_running_two_tests__vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/55431344148e3f8_Fix_an_issue_that_prevented_running_two_tests__vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/55431344148e3f8_Fix_an_issue_that_prevented_running_two_tests__vjrantal/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
STOP log received from  c5afcdcb Test has  SUCCEEDED
Device test finished on c5afcdcb 
STOP log received from  4db5c8cc Test has  SUCCEEDED
Device test finished on 4db5c8cc 
Android task is completed. [SUCCESS]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/55431344148e3f8_Fix_an_issue_that_prevented_running_two_tests__vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/55431344148e3f8_Fix_an_issue_that_prevented_running_two_tests__vjrantal/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/55431344148e3f8_Fix_an_issue_that_prevented_running_two_tests__vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/55431344148e3f8_Fix_an_issue_that_prevented_running_two_tests__vjrantal/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/55431344148e3f8_Fix_an_issue_that_prevented_running_two_tests__vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/55431344148e3f8_Fix_an_issue_that_prevented_running_two_tests__vjrantal/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/55431344148e3f8_Fix_an_issue_that_prevented_running_two_tests__vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/55431344148e3f8_Fix_an_issue_that_prevented_running_two_tests__vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/55431344148e3f8_Fix_an_issue_that_prevented_running_two_tests__vjrantal/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/55431344148e3f8_Fix_an_issue_that_prevented_running_two_tests__vjrantal/iOS_Iphone5s-1.md)



#### Test 55613145e2b298d Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-11T14:43:37.123Z - info: listening on *:3000

2016-01-11T14:43:37.623Z - debug: Device presented: Apple-IpadAir2-1 (ios) perftest socket:0

2016-01-11T14:43:37.629Z - info: Setting start timeout to: 120000 (ios)

2016-01-11T14:43:38.167Z - debug: Device presented: Thali Test (Galaxy S5) (android) perftest socket:2

2016-01-11T14:43:38.169Z - info: Setting start timeout to: 120000 (android)

2016-01-11T14:43:38.783Z - debug: Device presented: G3s-1 (android) perftest socket:3

2016-01-11T14:43:38.952Z - debug: Device presented: A3-1 (android) perftest socket:4

2016-01-11T14:43:39.137Z - debug: Device presented: G4-1 (android) perftest socket:5

2016-01-11T14:43:39.761Z - debug: Device presented: Apple-Iphone6-1 (ios) perftest socket:1

2016-01-11T14:43:40.068Z - debug: Device presented: Thali Test (Galaxy A3) (android) perftest socket:6

2016-01-11T14:43:40.145Z - debug: Device presented: G3-1 (android) perftest socket:7

2016-01-11T14:43:40.232Z - debug: Device presented: A5-1 (android) perftest socket:8

2016-01-11T14:43:40.816Z - debug: Device presented: S5-1 (android) perftest socket:9

2016-01-11T14:43:41.174Z - debug: Device presented: Nexus 5 (android) perftest socket:10

2016-01-11T14:43:41.196Z - debug: Device presented: Apple-Iphone5s-1 (ios) perftest socket:11

2016-01-11T14:43:41.534Z - debug: Device presented: Apple-Iphone5-1 (ios) perftest socket:12

2016-01-11T14:43:41.535Z - info: Required number of devices presented

2016-01-11T14:43:41.539Z - info: Starting perf test run for platform: ios

2016-01-11T14:43:41.540Z - info: Using devices:

2016-01-11T14:43:41.541Z - info: Apple-IpadAir2-1

2016-01-11T14:43:41.544Z - info: Apple-Iphone6-1

2016-01-11T14:43:41.545Z - info: Apple-Iphone5s-1

2016-01-11T14:43:41.546Z - info: Apple-Iphone5-1

2016-01-11T14:43:41.550Z - info: Starting test: with 4 devices (ios)

2016-01-11T14:43:41.672Z - debug: Device presented: Thali Test (Galaxy A5) (android) perftest socket:13

2016-01-11T14:43:41.890Z - debug: Device presented: Note4-1 (android) perftest socket:14

2016-01-11T14:43:41.944Z - debug: Device presented: HTC One M8s (android) perftest socket:15

2016-01-11T14:43:42.115Z - debug: Device presented: XT1072 (android) perftest socket:16

2016-01-11T14:43:42.885Z - info: Received results for {"name:":"Apple-Iphone6-1","time":1041,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone5-1.oKqzPQ==","peerAvailable":true,"time":1041}]} Apple-Iphone6-1 ios (3 left)

2016-01-11T14:43:42.892Z - info: Received results for {"name:":"Apple-IpadAir2-1","time":1051,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone5-1.oKqzPQ==","peerAvailable":true,"time":1051}]} Apple-IpadAir2-1 ios (2 left)

2016-01-11T14:43:43.071Z - info: Received results for {"name:":"Apple-Iphone5-1","time":1070,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-IpadAir2-1.aUvv7Q==","peerAvailable":true,"time":1069}]} Apple-Iphone5-1 ios (1 left)

2016-01-11T14:43:43.146Z - debug: Device presented: XT1039 (android) perftest socket:17

2016-01-11T14:43:44.475Z - debug: Socket disconnected: transport close 17 (XT1039)

2016-01-11T14:43:46.218Z - info: Received results for {"name:":"Apple-Iphone5s-1","time":1116,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-IpadAir2-1.aUvv7Q==","peerAvailable":true,"time":1115}]} Apple-Iphone5s-1 ios (0 left)

2016-01-11T14:43:46.223Z - info: All test data retrieved for testFindPeers.js (ios)

2016-01-11T14:43:46.231Z - info: Remaining tests: testSendData.js

2016-01-11T14:43:46.234Z - info: Continuing to next test: testSendData.js

2016-01-11T14:43:46.235Z - info: Starting test: with 4 devices (ios)

2016-01-11T14:43:48.151Z - debug: Socket disconnected: transport close 18 (NOT YET SET)

2016-01-11T14:44:43.285Z - info: Received results for {"name:":"Apple-Iphone5s-1","time":54487,"result":"OK","sendList":[{"name":"Apple-Iphone5-1.oKqzPQ==","time":40599,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-IpadAir2-1.3/8jow==","time":5972,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1.FPpLTg==","time":3437,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1.wtwmkg==","time":3460,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone5s-1 ios (3 left)

2016-01-11T14:44:44.346Z - info: Received results for {"name:":"Apple-IpadAir2-1","time":56964,"result":"OK","sendList":[{"name":"Apple-Iphone5-1.oKqzPQ==","time":43023,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-Iphone5s-1./+n+RQ==","time":5881,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1.FPpLTg==","time":4043,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1.wtwmkg==","time":3800,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-IpadAir2-1 ios (2 left)

2016-01-11T14:44:46.368Z - info: Received results for {"name:":"Apple-Iphone5-1","time":57418,"result":"OK","sendList":[{"name":"Apple-Iphone6-1.UVBQ1A==","time":40608,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-IpadAir2-1.3/8jow==","time":7524,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1./+n+RQ==","time":4243,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1.wtwmkg==","time":3882,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone5-1 ios (1 left)

2016-01-11T14:45:29.362Z - info: Received results for {"name:":"Apple-Iphone6-1","time":100015,"result":"TIMEOUT","sendList":[{"name":"Apple-IpadAir2-1.3/8jow==","time":3971,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1.FPpLTg==","time":3986,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1./+n+RQ==","time":3598,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone6-1 ios (0 left)

2016-01-11T14:45:29.365Z - info: All test data retrieved for testSendData.js (ios)

2016-01-11T14:45:29.372Z - info: ALL DONE !!!

{ 'name:': 'Apple-IpadAir2-1',
  time: 1051,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1.oKqzPQ==',
       peerAvailable: true,
       time: 1051 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 1041,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1.oKqzPQ==',
       peerAvailable: true,
       time: 1041 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 1116,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1.aUvv7Q==',
       peerAvailable: true,
       time: 1115 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 1070,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1.aUvv7Q==',
       peerAvailable: true,
       time: 1069 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 56964,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.oKqzPQ==',
       time: 43023,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1./+n+RQ==',
       time: 5881,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.FPpLTg==',
       time: 4043,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.wtwmkg==',
       time: 3800,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 100015,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'Apple-IpadAir2-1.3/8jow==',
       time: 3971,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.FPpLTg==',
       time: 3986,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1./+n+RQ==',
       time: 3598,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 54487,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.oKqzPQ==',
       time: 40599,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.3/8jow==',
       time: 5972,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.FPpLTg==',
       time: 3437,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.wtwmkg==',
       time: 3460,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 57418,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1.UVBQ1A==',
       time: 40608,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.3/8jow==',
       time: 7524,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1./+n+RQ==',
       time: 4243,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.wtwmkg==',
       time: 3882,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

--------------- test report ---------------------
--------------- Apple-IpadAir2-1 --------------------- : 1

Find peers : 100% : 1051 ms, 99% : 1051 ms, 95 : 1051 ms, 90% : 1051 ms.

Result count 1, range 1051 ms to  1051 ms.

Send data : 100% : 5881 ms, 99% : 5881 ms, 95 : 5881 ms, 90% : 5881 ms.

Average data rate: 0.022 MB/s

Result count 3, range 3800 ms to  5881 ms.

Send data failed peers count : 1 [25 %]

- Peer ID : Apple-Iphone5-1.oKqzPQ==, Tried : 5
Send data never tried peers count : 0 [0 %]

--------------- Apple-Iphone6-1 --------------------- : 2
Find peers : 100% : 1041 ms, 99% : 1041 ms, 95 : 1041 ms, 90% : 1041 ms.

Result count 1, range 1041 ms to  1041 ms.
Send data : 100% : 3986 ms, 99% : 3986 ms, 95 : 3986 ms, 90% : 3986 ms.
Average data rate: 0.026 MB/s

Result count 3, range 3598 ms to  3986 ms.
Send data failed peers count : 0 [0 %]
Send data never tried peers count : 0 [0 %]

--------------- Apple-Iphone5s-1 --------------------- : 3
Find peers : 100% : 1115 ms, 99% : 1115 ms, 95 : 1115 ms, 90% : 1115 ms.
Result count 1, range 1115 ms to  1115 ms.

Send data : 100% : 5972 ms, 99% : 5972 ms, 95 : 5972 ms, 90% : 5972 ms.
Average data rate: 0.023 MB/s
Result count 3, range 3437 ms to  5972 ms.
Send data failed peers count : 1 [25 %]

- Peer ID : Apple-Iphone5-1.oKqzPQ==, Tried : 5
Send data never tried peers count : 0 [0 %]
--------------- Apple-Iphone5-1 --------------------- : 4
Find peers : 100% : 1069 ms, 99% : 1069 ms, 95 : 1069 ms, 90% : 1069 ms.
Result count 1, range 1069 ms to  1069 ms.
Send data : 100% : 7524 ms, 99% : 7524 ms, 95 : 7524 ms, 90% : 7524 ms.
Average data rate: 0.019 MB/s

Result count 3, range 3882 ms to  7524 ms.
Send data failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone6-1.UVBQ1A==, Tried : 5
Send data never tried peers count : 0 [0 %]

--------------- Combined ---------------------
Find peers : 100% : 1115 ms, 99% : 1115 ms, 95 : 1115 ms, 90% : 1115 ms.

Send data : 100% : 7524 ms, 99% : 7524 ms, 95 : 5972 ms, 90% : 5972 ms.

Average data rate: 0.022 MB/s
--------------- end of test report ---------------------

2016-01-11T14:45:29.509Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1.oKqzPQ==, peerAvailable=true, time=1051], sendList=[name=Apple-Iphone6-1.wtwmkg==, time=3800, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1.FPpLTg==, time=4043, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5s-1./+n+RQ==, time=5881, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone5-1.oKqzPQ==, time=43023, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1.oKqzPQ==, peerAvailable=true, time=1041], sendList=[name=Apple-Iphone5s-1./+n+RQ==, time=3598, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.3/8jow==, time=3971, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1.FPpLTg==, time=3986, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1.aUvv7Q==, peerAvailable=true, time=1115], sendList=[name=Apple-Iphone5-1.FPpLTg==, time=3437, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone6-1.wtwmkg==, time=3460, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.3/8jow==, time=5972, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone5-1.oKqzPQ==, time=40599, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1.aUvv7Q==, peerAvailable=true, time=1069], sendList=[name=Apple-Iphone6-1.wtwmkg==, time=3882, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5s-1./+n+RQ==, time=4243, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.3/8jow==, time=7524, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone6-1.UVBQ1A==, time=40608, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[]

2016-01-11T14:45:29.520Z - debug: end to Apple-IpadAir2-1

2016-01-11T14:45:29.522Z - debug: end to Apple-Iphone6-1

2016-01-11T14:45:29.524Z - debug: end to Apple-Iphone5s-1

2016-01-11T14:45:29.527Z - debug: end to Apple-Iphone5-1

2016-01-11T14:45:31.936Z - debug: Socket disconnected: transport close 0 (Apple-IpadAir2-1)

2016-01-11T14:45:32.501Z - debug: Socket disconnected: transport close 1 (Apple-Iphone6-1)

2016-01-11T14:45:33.223Z - debug: Socket disconnected: transport close 11 (Apple-Iphone5s-1)

2016-01-11T14:45:38.171Z - info: Start timeout elapsed for platform: android

2016-01-11T14:45:38.174Z - info: Starting perf test run for platform: android

2016-01-11T14:45:38.177Z - info: Using devices:

2016-01-11T14:45:38.178Z - info: Thali Test (Galaxy S5)

2016-01-11T14:45:38.179Z - info: G3s-1

2016-01-11T14:45:38.180Z - info: A3-1
2016-01-11T14:45:38.181Z - info: G4-1

2016-01-11T14:45:38.182Z - info: Thali Test (Galaxy A3)

2016-01-11T14:45:38.182Z - info: G3-1
2016-01-11T14:45:38.183Z - info: A5-1

2016-01-11T14:45:38.184Z - info: S5-1

2016-01-11T14:45:38.185Z - info: Nexus 5
2016-01-11T14:45:38.186Z - info: Thali Test (Galaxy A5)

2016-01-11T14:45:38.187Z - info: Note4-1

2016-01-11T14:45:38.188Z - info: HTC One M8s
2016-01-11T14:45:38.188Z - info: XT1072

2016-01-11T14:45:38.189Z - info: XT1039

2016-01-11T14:45:38.191Z - info: Starting test: with 14 devices (android)

2016-01-11T14:45:38.497Z - debug: state: ios completed

2016-01-11T14:45:38.500Z - debug: state: android running

2016-01-11T14:45:41.896Z - debug: Socket disconnected: transport close 12 (Apple-Iphone5-1)

2016-01-11T14:47:18.554Z - info: Received results for {"name:":"HTC One M8s","time":100064,"result":"TIMEOUT","peersList":[{"peerName":"Nexus 5","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":true,"time":2786},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":3083},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":3330},{"peerName":"Note4-1","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":3379},{"peerName":"XT1072","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true,"time":3936},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":4797},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":7328},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":7652},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":14667},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":51403},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":53704}]} HTC One M8s android (13 left)

2016-01-11T14:47:18.730Z - info: Received results for {"name:":"Note4-1","time":100092,"result":"TIMEOUT","peersList":[{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":43106}]} Note4-1 android (12 left)

2016-01-11T14:47:18.772Z - info: Received results for {"name:":"G3s-1","time":100122,"result":"TIMEOUT","peersList":[{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":2395},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":59617},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":72540},{"peerName":"XT1072","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true,"time":86107}]} G3s-1 android (11 left)

2016-01-11T14:47:18.787Z - info: Received results for {"name:":"A3-1","time":100071,"result":"TIMEOUT","peersList":[{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":3778},{"peerName":"XT1072","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":false,"time":93781},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":4185},{"peerName":"HTC One M8s","peerIdentifier":"90:E7:C4:F6:69:77","peerAvailable":true,"time":4693},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":10855},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":14564},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":52046},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":62325}]} A3-1 android (10 left)

2016-01-11T14:47:18.805Z - info: Received results for {"name:":"Thali Test (Galaxy A3)","time":100065,"result":"TIMEOUT","peersList":[{"peerName":"Nexus 5","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":true,"time":3426},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":3549},{"peerName":"XT1072","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true,"time":3688},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":3752},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":10807},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":51838},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":61613}]} Thali Test (Galaxy A3) android (9 left)

2016-01-11T14:47:18.816Z - info: Received results for {"name:":"XT1072","time":100162,"result":"TIMEOUT","peersList":[{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":1963},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":false,"time":91967},{"peerName":"Note4-1","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":false,"time":91966},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":2775},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":39751},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":40104},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":80869},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":89192}]} XT1072 android (8 left)

2016-01-11T14:47:18.881Z - info: Received results for {"name:":"Nexus 5","time":100138,"result":"TIMEOUT","peersList":[{"peerName":"Note4-1","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":41773},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":41774},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":41788},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":42534}]} Nexus 5 android (7 left)

2016-01-11T14:47:18.888Z - info: Received results for {"name:":"Thali Test (Galaxy S5)","time":100138,"result":"TIMEOUT","peersList":[{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":4579},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":33044},{"peerName":"XT1072","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true,"time":45411},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":56958},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":57041},{"peerName":"Note4-1","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":81714},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":82425},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":91978},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":92465}]} Thali Test (Galaxy S5) android (6 left)

2016-01-11T14:47:19.100Z - info: Received results for {"name:":"Thali Test (Galaxy A5)","time":100060,"result":"TIMEOUT","peersList":[{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":4415},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":4729},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":4888},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":22732},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":22765},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":23672},{"peerName":"XT1072","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true,"time":89912}]} Thali Test (Galaxy A5) android (5 left)

2016-01-11T14:47:19.239Z - info: Received results for {"name:":"G3-1","time":100076,"result":"TIMEOUT","peersList":[{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":2036},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":9189},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":11418},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":13065},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":13098},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":32585},{"peerName":"Note4-1","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":42844},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":53166},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":78842}]} G3-1 android (4 left)

2016-01-11T14:47:19.384Z - info: Received results for {"name:":"A5-1","time":100079,"result":"TIMEOUT","peersList":[{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":4733},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":4894},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":51417},{"peerName":"Nexus 5","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":true,"time":55153},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":59574},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":63841},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":97804}]} A5-1 android (3 left)

2016-01-11T14:47:20.069Z - info: Received results for {"name:":"G4-1","time":100080,"result":"TIMEOUT","peersList":[{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":11420},{"peerName":"HTC One M8s","peerIdentifier":"90:E7:C4:F6:69:77","peerAvailable":true,"time":47214},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":63088},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":63116},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":63810},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":88327}]} G4-1 android (2 left)

2016-01-11T14:47:20.644Z - info: Received results for {"name:":"S5-1","time":100154,"result":"TIMEOUT","peersList":[{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":42255},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":42928},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":43790},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":52492},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":53260},{"peerName":"Note4-1","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":80196},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":90758}]} S5-1 android (1 left)

2016-01-11T14:47:38.244Z - info: server timeout for test: testFindPeers.js (android)

2016-01-11T14:47:38.247Z - info: All test data retrieved for testFindPeers.js (android)

2016-01-11T14:47:38.264Z - info: No results from XT1039

2016-01-11T14:47:38.266Z - info: Remaining tests: testSendData.js
2016-01-11T14:47:38.270Z - info: Continuing to next test: testSendData.js
2016-01-11T14:47:38.271Z - info: Starting test: with 14 devices (android)

2016-01-11T14:48:43.560Z - debug: Socket disconnected: ping timeout 15 (HTC One M8s)

2016-01-11T14:48:54.069Z - debug: Socket disconnected: ping timeout 16 (XT1072)

2016-01-11T14:48:55.075Z - debug: Device presented: XT1072 (android) perftest socket:19

2016-01-11T14:48:55.077Z - info: Updating existing device: XT1072 (0e8859c5-a27b-4245-af20-493b226f0123)

2016-01-11T14:49:18.618Z - info: Received results for {"name:":"Note4-1","time":100080,"result":"TIMEOUT","sendList":[{"connections":1,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"}]} Note4-1 android (13 left)

2016-01-11T14:49:18.685Z - info: Received results for {"name:":"Thali Test (Galaxy A3)","time":100098,"result":"TIMEOUT","sendList":[{"name":"F8:95:C7:87:85:54","time":7311,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":13376,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"}]} Thali Test (Galaxy A3) android (12 left)

2016-01-11T14:49:18.688Z - info: Received results for {"name:":"Thali Test (Galaxy A5)","time":100103,"result":"TIMEOUT","sendList":[{"connections":1,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":1,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"}]} Thali Test (Galaxy A5) android (11 left)

2016-01-11T14:49:18.727Z - info: Received results for {"name:":"S5-1","time":100135,"result":"TIMEOUT","sendList":[{"name":"F8:95:C7:87:85:54","time":52678,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"}]} S5-1 android (10 left)

2016-01-11T14:49:18.798Z - info: Received results for {"name:":"XT1072","time":100163,"result":"TIMEOUT","sendList":[{"connections":1,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"}]} XT1072 android (9 left)

2016-01-11T14:49:18.974Z - info: Received results for {"name:":"Thali Test (Galaxy S5)","time":100107,"result":"TIMEOUT","sendList":[{"name":"58:3F:54:73:64:C0","time":6370,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:51:18:22","time":12417,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"34:FC:EF:11:AE:67","time":9903,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":6293,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:75:41","time":4225,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":1,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"}]} Thali Test (Galaxy S5) android (8 left)

2016-01-11T14:49:19.226Z - info: Received results for {"name:":"Nexus 5","time":100268,"result":"TIMEOUT","sendList":[{"name":"E0:DB:10:14:E2:C0","time":4136,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":5837,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"}]} Nexus 5 android (7 left)

2016-01-11T14:49:19.533Z - info: Received results for {"name:":"G4-1","time":100074,"result":"TIMEOUT","sendList":[{"name":"7C:F9:0E:37:96:AB","time":27240,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"}]} G4-1 android (6 left)

2016-01-11T14:49:19.709Z - info: Received results for {"name:":"A3-1","time":100091,"result":"TIMEOUT","sendList":[{"name":"7C:F9:0E:34:8A:A0","time":20762,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":5585,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"34:FC:EF:11:AE:67","time":6469,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":4866,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"58:3F:54:73:64:C0","time":13168,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":7211,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"}]} A3-1 android (5 left)

2016-01-11T14:49:19.753Z - info: Received results for {"name:":"G3-1","time":100109,"result":"TIMEOUT","sendList":[{"name":"E0:DB:10:14:E2:C0","time":11684,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:37:96:AB","time":8348,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":6619,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":9084,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:51:18:22","time":26899,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"}]} G3-1 android (4 left)

2016-01-11T14:49:21.711Z - info: Received results for {"name:":"G3s-1","time":100067,"result":"TIMEOUT","sendList":[{"name":"E0:DB:10:14:E2:C0","time":71821,"result":"OK","connections":3,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"}]} G3s-1 android (3 left)

2016-01-11T14:49:23.167Z - info: Received results for {"name:":"A5-1","time":100096,"result":"TIMEOUT","sendList":[{"name":"7C:F9:0E:51:18:22","time":6337,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":27601,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"}]} A5-1 android (2 left)

2016-01-11T14:49:38.276Z - info: server timeout for test: testSendData.js (android)

2016-01-11T14:49:38.279Z - info: All test data retrieved for testSendData.js (android)

2016-01-11T14:49:38.289Z - info: No results from HTC One M8s

2016-01-11T14:49:38.291Z - info: No results from XT1039
2016-01-11T14:49:38.292Z - info: ALL DONE !!!
{ 'name:': 'Apple-IpadAir2-1',
  time: 1051,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1.oKqzPQ==',
       peerAvailable: true,
       time: 1051 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 1041,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1.oKqzPQ==',
       peerAvailable: true,
       time: 1041 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 1116,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1.aUvv7Q==',
       peerAvailable: true,
       time: 1115 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 1070,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1.aUvv7Q==',
       peerAvailable: true,
       time: 1069 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 56964,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.oKqzPQ==',
       time: 43023,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1./+n+RQ==',
       time: 5881,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.FPpLTg==',
       time: 4043,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.wtwmkg==',
       time: 3800,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 100015,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'Apple-IpadAir2-1.3/8jow==',
       time: 3971,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.FPpLTg==',
       time: 3986,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1./+n+RQ==',
       time: 3598,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 54487,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.oKqzPQ==',
       time: 40599,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.3/8jow==',
       time: 5972,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.FPpLTg==',
       time: 3437,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.wtwmkg==',
       time: 3460,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 57418,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1.UVBQ1A==',
       time: 40608,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.3/8jow==',
       time: 7524,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1./+n+RQ==',
       time: 4243,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.wtwmkg==',
       time: 3882,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Thali Test (Galaxy S5)',
  time: 100138,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 4579 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 33044 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 45411 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 56958 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 57041 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 81714 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 82425 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 91978 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 92465 } ] }

{ 'name:': 'G3s-1',
  time: 100122,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 2395 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 59617 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 72540 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 86107 } ] }

{ 'name:': 'A3-1',
  time: 100071,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 3778 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: false,
       time: 93781 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 4185 },
     { peerName: 'HTC One M8s',
       peerIdentifier: '90:E7:C4:F6:69:77',
       peerAvailable: true,
       time: 4693 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 10855 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 14564 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 52046 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 62325 } ] }

{ 'name:': 'G4-1',
  time: 100080,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 11420 },
     { peerName: 'HTC One M8s',
       peerIdentifier: '90:E7:C4:F6:69:77',
       peerAvailable: true,
       time: 47214 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 63088 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 63116 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 63810 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 88327 } ] }

{ 'name:': 'Thali Test (Galaxy A3)',
  time: 100065,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 3426 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 3549 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 3688 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 3752 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 10807 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 51838 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 61613 } ] }

{ 'name:': 'G3-1',
  time: 100076,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 2036 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 9189 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 11418 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 13065 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 13098 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 32585 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 42844 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 53166 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 78842 } ] }

{ 'name:': 'A5-1',
  time: 100079,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 4733 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 4894 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 51417 },
     { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 55153 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 59574 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 63841 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 97804 } ] }

{ 'name:': 'S5-1',
  time: 100154,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 42255 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 42928 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 43790 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 52492 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 53260 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 80196 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 90758 } ] }

{ 'name:': 'Nexus 5',
  time: 100138,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 41773 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 41774 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 41788 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 42534 } ] }

{ 'name:': 'Thali Test (Galaxy A5)',
  time: 100060,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 4415 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 4729 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 4888 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 22732 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 22765 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 23672 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 89912 } ] }

{ 'name:': 'Note4-1',
  time: 100092,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 43106 } ] }

{ 'name:': 'HTC One M8s',
  time: 100064,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 2786 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 3083 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 3330 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 3379 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 3936 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 4797 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 7328 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 7652 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 14667 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 51403 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 53704 } ] }

{ 'name:': 'XT1072',
  time: 100162,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 1963 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: false,
       time: 91967 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: false,
       time: 91966 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 2775 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 39751 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 40104 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 80869 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 89192 } ] }

{ 'name:': 'Thali Test (Galaxy S5)',
  time: 100107,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '58:3F:54:73:64:C0',
       time: 6370,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:51:18:22',
       time: 12417,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '34:FC:EF:11:AE:67',
       time: 9903,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:3C:51',
       time: 6293,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '08:EC:A9:50:75:41',
       time: 4225,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: 'F8:95:C7:87:85:54',
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
       name: '44:80:EB:7B:5A:05',
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
       name: '90:E7:C4:F6:69:77',
       time: 0,
       result: 'Fail' },
     { connections: 1,
       name: 'F4:F1:E1:5C:3B:E2',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'G3s-1',
  time: 100067,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'E0:DB:10:14:E2:C0',
       time: 71821,
       result: 'OK',
       connections: 3,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: '7C:F9:0E:37:96:AB',
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
     { connections: 0,
       name: '7C:F9:0E:51:18:22',
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
       name: 'F8:95:C7:87:3C:51',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '58:3F:54:73:64:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:75:41',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'A3-1',
  time: 100091,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '7C:F9:0E:34:8A:A0',
       time: 20762,
       result: 'OK',
       connections: 2,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'E0:DB:10:14:E2:C0',
       time: 5585,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '34:FC:EF:11:AE:67',
       time: 6469,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:85:54',
       time: 4866,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '58:3F:54:73:64:C0',
       time: 13168,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'B0:C5:59:3F:75:69',
       time: 7211,
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
       name: 'F4:F1:E1:5C:3B:E2',
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
       name: '7C:F9:0E:37:96:AB',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F8:95:C7:87:3C:51',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:51:18:22',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'G4-1',
  time: 100074,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '7C:F9:0E:37:96:AB',
       time: 27240,
       result: 'OK',
       connections: 2,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: '90:E7:C4:F6:69:77',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F4:F1:E1:5C:3B:E2',
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
       name: '34:FC:EF:11:AE:67',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '58:3F:54:73:64:C0',
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
       name: 'E0:DB:10:14:E2:C0',
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
       name: '7C:F9:0E:34:8A:A0',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Thali Test (Galaxy A3)',
  time: 100098,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'F8:95:C7:87:85:54',
       time: 7311,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'E0:DB:10:14:E2:C0',
       time: 13376,
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
       name: '90:E7:C4:F6:69:77',
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
       name: 'F8:95:C7:87:3C:51',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'B0:C5:59:3F:75:69',
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
       name: '44:80:EB:7B:5A:05',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:75:41',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:51:18:22',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'G3-1',
  time: 100109,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'E0:DB:10:14:E2:C0',
       time: 11684,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:37:96:AB',
       time: 8348,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'B0:C5:59:3F:75:69',
       time: 6619,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:3C:51',
       time: 9084,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:51:18:22',
       time: 26899,
       result: 'OK',
       connections: 2,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: 'F4:F1:E1:5C:3B:E2',
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
       name: '7C:F9:0E:34:8A:A0',
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
       name: '90:E7:C4:F6:69:77',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F8:95:C7:87:85:54',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'A5-1',
  time: 100096,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '7C:F9:0E:51:18:22',
       time: 6337,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:3C:51',
       time: 27601,
       result: 'OK',
       connections: 2,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: 'F8:95:C7:87:85:54',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '90:E7:C4:F6:69:77',
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
       name: '08:EC:A9:50:75:41',
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
       name: '58:3F:54:73:64:C0',
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
       name: 'B0:C5:59:3F:75:69',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'S5-1',
  time: 100135,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'F8:95:C7:87:85:54',
       time: 52678,
       result: 'OK',
       connections: 2,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: '90:E7:C4:F6:69:77',
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
       name: '08:EC:A9:50:76:27',
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
       name: 'F8:95:C7:87:3C:51',
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
       name: 'B0:C5:59:3F:75:69',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:37:96:AB',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Nexus 5',
  time: 100268,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'E0:DB:10:14:E2:C0',
       time: 4136,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:3C:51',
       time: 5837,
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
       name: 'B0:C5:59:3F:75:69',
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
       name: 'F8:95:C7:87:85:54',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:34:8A:A0',
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
       name: '44:80:EB:7B:5A:05',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F4:F1:E1:5C:3B:E2',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:75:41',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Thali Test (Galaxy A5)',
  time: 100103,
  result: 'TIMEOUT',
  sendList: 
   [ { connections: 1,
       name: '7C:F9:0E:34:8A:A0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '58:3F:54:73:64:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'B0:C5:59:3F:75:69',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '90:E7:C4:F6:69:77',
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
       name: 'E0:DB:10:14:E2:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:11:AE:67',
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
       name: 'F8:95:C7:87:3C:51',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:37:96:AB',
       time: 0,
       result: 'Fail' },
     { connections: 1,
       name: 'F4:F1:E1:5C:3B:E2',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Note4-1',
  time: 100080,
  result: 'TIMEOUT',
  sendList: 
   [ { connections: 1,
       name: '90:E7:C4:F6:69:77',
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
     { connections: 0,
       name: 'F8:95:C7:87:3C:51',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:51:18:22',
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
       name: '08:EC:A9:50:75:41',
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
       name: 'F8:95:C7:87:85:54',
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

{ 'name:': 'XT1072',
  time: 100163,
  result: 'TIMEOUT',
  sendList: 
   [ { connections: 1,
       name: '7C:F9:0E:34:8A:A0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:51:18:22',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '90:E7:C4:F6:69:77',
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
       name: '7C:F9:0E:37:96:AB',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F4:F1:E1:5C:3B:E2',
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
       name: 'B0:C5:59:3F:75:69',
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
       name: 'E0:DB:10:14:E2:C0',
       time: 0,
       result: 'Fail' } ] }

--------------- test report ---------------------
--------------- Apple-IpadAir2-1 --------------------- : 1

Find peers : 100% : 1051 ms, 99% : 1051 ms, 95 : 1051 ms, 90% : 1051 ms.
Result count 1, range 1051 ms to  1051 ms.

Send data : 100% : 5881 ms, 99% : 5881 ms, 95 : 5881 ms, 90% : 5881 ms.
Average data rate: 0.022 MB/s
Result count 3, range 3800 ms to  5881 ms.

Send data failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone5-1.oKqzPQ==, Tried : 5
Send data never tried peers count : 0 [0 %]

--------------- Apple-Iphone6-1 --------------------- : 2
Find peers : 100% : 1041 ms, 99% : 1041 ms, 95 : 1041 ms, 90% : 1041 ms.

Result count 1, range 1041 ms to  1041 ms.
Send data : 100% : 3986 ms, 99% : 3986 ms, 95 : 3986 ms, 90% : 3986 ms.
Average data rate: 0.026 MB/s

Result count 3, range 3598 ms to  3986 ms.
Send data failed peers count : 0 [0 %]
Send data never tried peers count : 0 [0 %]

--------------- Apple-Iphone5s-1 --------------------- : 3
Find peers : 100% : 1115 ms, 99% : 1115 ms, 95 : 1115 ms, 90% : 1115 ms.
Result count 1, range 1115 ms to  1115 ms.

Send data : 100% : 5972 ms, 99% : 5972 ms, 95 : 5972 ms, 90% : 5972 ms.
Average data rate: 0.023 MB/s
Result count 3, range 3437 ms to  5972 ms.
Send data failed peers count : 1 [25 %]

- Peer ID : Apple-Iphone5-1.oKqzPQ==, Tried : 5
Send data never tried peers count : 0 [0 %]
--------------- Apple-Iphone5-1 --------------------- : 4

Find peers : 100% : 1069 ms, 99% : 1069 ms, 95 : 1069 ms, 90% : 1069 ms.
Result count 1, range 1069 ms to  1069 ms.

Send data : 100% : 7524 ms, 99% : 7524 ms, 95 : 7524 ms, 90% : 7524 ms.
Average data rate: 0.019 MB/s
Result count 3, range 3882 ms to  7524 ms.
Send data failed peers count : 1 [25 %]

- Peer ID : Apple-Iphone6-1.UVBQ1A==, Tried : 5
Send data never tried peers count : 0 [0 %]
--------------- Thali Test (Galaxy S5) --------------------- : 5

Find peers : 100% : 92465 ms, 99% : 92465 ms, 95 : 92465 ms, 90% : 91978 ms.
Result count 9, range 4579 ms to  92465 ms.

Send data : 100% : 12417 ms, 99% : 12417 ms, 95 : 12417 ms, 90% : 12417 ms.
Average data rate: 0.013 MB/s
Result count 5, range 4225 ms to  12417 ms.

Send data failed peers count : 2 [28.571428571428573 %]
- Peer ID : F8:95:C7:87:85:54, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
Send data never tried peers count : 6 [46.15384615384615 %]
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 90:E7:C4:F6:69:77
--------------- G3s-1 --------------------- : 6
Find peers : 100% : 86107 ms, 99% : 86107 ms, 95 : 86107 ms, 90% : 86107 ms.
Result count 4, range 2395 ms to  86107 ms.
Send data : 100% : 71821 ms, 99% : 71821 ms, 95 : 71821 ms, 90% : 71821 ms.
Average data rate: 0.001 MB/s
Result count 1, range 71821 ms to  71821 ms.
Send data failed peers count : 1 [50 %]
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
Send data never tried peers count : 11 [84.61538461538461 %]
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 90:E7:C4:F6:69:77
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 08:EC:A9:50:75:41
--------------- A3-1 --------------------- : 7
Find peers : 100% : 93781 ms, 99% : 93781 ms, 95 : 93781 ms, 90% : 62325 ms.
Result count 8, range 3778 ms to  93781 ms.
Send data : 100% : 20762 ms, 99% : 20762 ms, 95 : 20762 ms, 90% : 13168 ms.
Average data rate: 0.01 MB/s
Result count 6, range 4866 ms to  20762 ms.
Send data failed peers count : 1 [14.285714285714286 %]
- Peer ID : 90:E7:C4:F6:69:77, Tried : 1
Send data never tried peers count : 6 [46.15384615384615 %]
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 7C:F9:0E:51:18:22
--------------- G4-1 --------------------- : 8
Find peers : 100% : 88327 ms, 99% : 88327 ms, 95 : 88327 ms, 90% : 63810 ms.
Result count 6, range 11420 ms to  88327 ms.
Send data : 100% : 27240 ms, 99% : 27240 ms, 95 : 27240 ms, 90% : 27240 ms.
Average data rate: 0.004 MB/s
Result count 1, range 27240 ms to  27240 ms.
Send data failed peers count : 1 [50 %]
- Peer ID : 90:E7:C4:F6:69:77, Tried : 1
Send data never tried peers count : 11 [84.61538461538461 %]
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : F8:95:C7:87:85:54
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 7C:F9:0E:34:8A:A0
--------------- Thali Test (Galaxy A3) --------------------- : 9
Find peers : 100% : 61613 ms, 99% : 61613 ms, 95 : 61613 ms, 90% : 51838 ms.
Result count 7, range 3426 ms to  61613 ms.
Send data : 100% : 13376 ms, 99% : 13376 ms, 95 : 13376 ms, 90% : 13376 ms.
Average data rate: 0.01 MB/s
Result count 2, range 7311 ms to  13376 ms.
Send data failed peers count : 1 [33.333333333333336 %]
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
Send data never tried peers count : 10 [76.92307692307692 %]
- Peer ID : 90:E7:C4:F6:69:77
- Peer ID : 58:3F:54:73:64:C0

- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : 7C:F9:0E:51:18:22

--------------- G3-1 --------------------- : 10
Find peers : 100% : 78842 ms, 99% : 78842 ms, 95 : 78842 ms, 90% : 53166 ms.
Result count 9, range 2036 ms to  78842 ms.
Send data : 100% : 26899 ms, 99% : 26899 ms, 95 : 26899 ms, 90% : 26899 ms.

Average data rate: 0.008 MB/s
Result count 5, range 6619 ms to  26899 ms.
Send data failed peers count : 1 [16.666666666666668 %]

- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
Send data never tried peers count : 7 [53.84615384615385 %]
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 7C:F9:0E:34:8A:A0

- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : 90:E7:C4:F6:69:77
- Peer ID : F8:95:C7:87:85:54
--------------- A5-1 --------------------- : 11
Find peers : 100% : 97804 ms, 99% : 97804 ms, 95 : 97804 ms, 90% : 63841 ms.
Result count 7, range 4733 ms to  97804 ms.
Send data : 100% : 27601 ms, 99% : 27601 ms, 95 : 27601 ms, 90% : 27601 ms.
Average data rate: 0.006 MB/s
Result count 2, range 6337 ms to  27601 ms.
Send data failed peers count : 1 [33.333333333333336 %]
- Peer ID : F8:95:C7:87:85:54, Tried : 1
Send data never tried peers count : 10 [76.92307692307692 %]
- Peer ID : 90:E7:C4:F6:69:77
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : B0:C5:59:3F:75:69
--------------- S5-1 --------------------- : 12
Find peers : 100% : 90758 ms, 99% : 90758 ms, 95 : 90758 ms, 90% : 80196 ms.
Result count 7, range 42255 ms to  90758 ms.
Send data : 100% : 52678 ms, 99% : 52678 ms, 95 : 52678 ms, 90% : 52678 ms.
Average data rate: 0.002 MB/s
Result count 1, range 52678 ms to  52678 ms.
Send data failed peers count : 1 [50 %]
- Peer ID : 90:E7:C4:F6:69:77, Tried : 1

Send data never tried peers count : 11 [84.61538461538461 %]
- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : E0:DB:10:14:E2:C0

- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 44:80:EB:7B:5A:05

- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 7C:F9:0E:37:96:AB
--------------- Nexus 5 --------------------- : 13

Find peers : 100% : 42534 ms, 99% : 42534 ms, 95 : 42534 ms, 90% : 42534 ms.
Result count 4, range 41773 ms to  42534 ms.
Send data : 100% : 5837 ms, 99% : 5837 ms, 95 : 5837 ms, 90% : 5837 ms.
Average data rate: 0.02 MB/s

Result count 2, range 4136 ms to  5837 ms.
Send data failed peers count : 1 [33.333333333333336 %]
- Peer ID : 7C:F9:0E:51:18:22, Tried : 1
Send data never tried peers count : 10 [76.92307692307692 %]

- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 90:E7:C4:F6:69:77
- Peer ID : F8:95:C7:87:85:54

- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 44:80:EB:7B:5A:05

- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 08:EC:A9:50:75:41
--------------- Thali Test (Galaxy A5) --------------------- : 14
Find peers : 100% : 89912 ms, 99% : 89912 ms, 95 : 89912 ms, 90% : 23672 ms.

Result count 7, range 4415 ms to  89912 ms.
No send data results!
--------------- Note4-1 --------------------- : 15
Find peers : 100% : 43106 ms, 99% : 43106 ms, 95 : 43106 ms, 90% : 43106 ms.

Result count 1, range 43106 ms to  43106 ms.
No send data results!
--------------- HTC One M8s --------------------- : 16
Find peers : 100% : 53704 ms, 99% : 53704 ms, 95 : 51403 ms, 90% : 51403 ms.
Result count 11, range 2786 ms to  53704 ms.
--------------- XT1072 --------------------- : 17

Find peers : 100% : 91967 ms, 99% : 91967 ms, 95 : 91967 ms, 90% : 91966 ms.
Result count 8, range 1963 ms to  91967 ms.
No send data results!
--------------- Combined ---------------------

Find peers : 100% : 97804 ms, 99% : 93781 ms, 95 : 91966 ms, 90% : 88327 ms.

Send data : 100% : 71821 ms, 99% : 71821 ms, 95 : 27601 ms, 90% : 26899 ms.
Average data rate: 0.009 MB/s

--------------- end of test report ---------------------

2016-01-11T14:49:38.807Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1.oKqzPQ==, peerAvailable=true, time=1051], sendList=[name=Apple-Iphone6-1.wtwmkg==, time=3800, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1.FPpLTg==, time=4043, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5s-1./+n+RQ==, time=5881, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone5-1.oKqzPQ==, time=43023, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1.oKqzPQ==, peerAvailable=true, time=1041], sendList=[name=Apple-Iphone5s-1./+n+RQ==, time=3598, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.3/8jow==, time=3971, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1.FPpLTg==, time=3986, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1.aUvv7Q==, peerAvailable=true, time=1115], sendList=[name=Apple-Iphone5-1.FPpLTg==, time=3437, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone6-1.wtwmkg==, time=3460, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.3/8jow==, time=5972, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone5-1.oKqzPQ==, time=40599, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1.aUvv7Q==, peerAvailable=true, time=1069], sendList=[name=Apple-Iphone6-1.wtwmkg==, time=3882, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5s-1./+n+RQ==, time=4243, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.3/8jow==, time=7524, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone6-1.UVBQ1A==, time=40608, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=4579, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=33044, peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=45411, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=56958, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=57041, peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=81714, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=82425, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=91978, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=92465], sendList=[name=08:EC:A9:50:75:41, time=4225, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=F8:95:C7:87:3C:51, time=6293, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=58:3F:54:73:64:C0, time=6370, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=34:FC:EF:11:AE:67, time=9903, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:51:18:22, time=12417, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=1, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail], notTriedList=[connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=90:E7:C4:F6:69:77, time=0, result=Fail], peersList=[peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=2395, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=59617, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=72540, peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=86107], sendList=[name=E0:DB:10:14:E2:C0, time=71821, result=OK, connections=3, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=7C:F9:0E:37:96:AB, time=0, result=Fail], notTriedList=[connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=90:E7:C4:F6:69:77, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail], peersList=[peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=3778, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=4185, peerName=HTC One M8s, peerIdentifier=90:E7:C4:F6:69:77, peerAvailable=true, time=4693, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=10855, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=14564, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=52046, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=62325, peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=false, time=93781], sendList=[name=F8:95:C7:87:85:54, time=4866, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=E0:DB:10:14:E2:C0, time=5585, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=34:FC:EF:11:AE:67, time=6469, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=B0:C5:59:3F:75:69, time=7211, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=58:3F:54:73:64:C0, time=13168, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:34:8A:A0, time=20762, result=OK, connections=2, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=90:E7:C4:F6:69:77, time=0, result=Fail], notTriedList=[connections=0, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail], peersList=[peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=11420, peerName=HTC One M8s, peerIdentifier=90:E7:C4:F6:69:77, peerAvailable=true, time=47214, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=63088, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=63116, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=63810, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=88327], sendList=[name=7C:F9:0E:37:96:AB, time=27240, result=OK, connections=2, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=90:E7:C4:F6:69:77, time=0, result=Fail], notTriedList=[connections=0, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail], peersList=[peerName=Nexus 5, peerIdentifier=34:FC:EF:11:AE:67, peerAvailable=true, time=3426, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=3549, peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=3688, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=3752, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=10807, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=51838, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=61613], sendList=[name=F8:95:C7:87:85:54, time=7311, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=E0:DB:10:14:E2:C0, time=13376, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=7C:F9:0E:34:8A:A0, time=0, result=Fail], notTriedList=[connections=0, name=90:E7:C4:F6:69:77, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail], peersList=[peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=2036, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=9189, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=11418, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=13065, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=13098, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=32585, peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=42844, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=53166, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=78842], sendList=[name=B0:C5:59:3F:75:69, time=6619, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:37:96:AB, time=8348, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=F8:95:C7:87:3C:51, time=9084, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=E0:DB:10:14:E2:C0, time=11684, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:51:18:22, time=26899, result=OK, connections=2, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail], notTriedList=[connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=90:E7:C4:F6:69:77, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail], peersList=[peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=4733, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=4894, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=51417, peerName=Nexus 5, peerIdentifier=34:FC:EF:11:AE:67, peerAvailable=true, time=55153, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=59574, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=63841, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=97804], sendList=[name=7C:F9:0E:51:18:22, time=6337, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=F8:95:C7:87:3C:51, time=27601, result=OK, connections=2, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=F8:95:C7:87:85:54, time=0, result=Fail], notTriedList=[connections=0, name=90:E7:C4:F6:69:77, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail], peersList=[peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=42255, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=42928, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=43790, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=52492, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=53260, peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=80196, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=90758], sendList=[name=F8:95:C7:87:85:54, time=52678, result=OK, connections=2, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=90:E7:C4:F6:69:77, time=0, result=Fail], notTriedList=[connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail], peersList=[peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=41773, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=41774, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=41788, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=42534], sendList=[name=E0:DB:10:14:E2:C0, time=4136, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=F8:95:C7:87:3C:51, time=5837, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=7C:F9:0E:51:18:22, time=0, result=Fail], notTriedList=[connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=90:E7:C4:F6:69:77, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail], peersList=[peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=4415, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=4729, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=4888, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=22732, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=22765, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=23672, peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=89912], sendList=[], failedPeer=[connections=1, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=1, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail], notTriedList=[connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=90:E7:C4:F6:69:77, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail], peersList=[peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=43106], sendList=[], failedPeer=[connections=1, name=90:E7:C4:F6:69:77, time=0, result=Fail], notTriedList=[connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail], peersList=[peerName=Nexus 5, peerIdentifier=34:FC:EF:11:AE:67, peerAvailable=true, time=2786, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=3083, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=3330, peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=3379, peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=3936, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=4797, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=7328, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=7652, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=14667, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=51403, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=53704], peersList=[peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=1963, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=2775, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=39751, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=40104, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=80869, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=89192, peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=false, time=91966, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=false, time=91967], sendList=[], failedPeer=[connections=1, name=7C:F9:0E:34:8A:A0, time=0, result=Fail], notTriedList=[connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=90:E7:C4:F6:69:77, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail]

2016-01-11T14:49:38.862Z - debug: end to Thali Test (Galaxy S5)

2016-01-11T14:49:38.864Z - debug: end to G3s-1

2016-01-11T14:49:38.870Z - debug: end to A3-1

2016-01-11T14:49:38.871Z - debug: end to G4-1

2016-01-11T14:49:38.872Z - debug: end to Thali Test (Galaxy A3)

2016-01-11T14:49:38.873Z - debug: end to G3-1

2016-01-11T14:49:38.874Z - debug: end to A5-1

2016-01-11T14:49:38.876Z - debug: end to S5-1

2016-01-11T14:49:38.877Z - debug: end to Nexus 5

2016-01-11T14:49:38.878Z - debug: end to Thali Test (Galaxy A5)

2016-01-11T14:49:38.879Z - debug: end to Note4-1

2016-01-11T14:49:38.880Z - debug: end to HTC One M8s

2016-01-11T14:49:38.881Z - debug: end to XT1072

2016-01-11T14:49:38.882Z - debug: end to XT1039

2016-01-11T14:49:39.389Z - debug: Socket disconnected: transport close 10 (Nexus 5)

2016-01-11T14:49:39.508Z - debug: Socket disconnected: transport close 13 (Thali Test (Galaxy A5))

2016-01-11T14:49:39.645Z - debug: Socket disconnected: transport close 8 (A5-1)

2016-01-11T14:49:39.680Z - debug: Socket disconnected: transport close 14 (Note4-1)

2016-01-11T14:49:39.710Z - debug: Socket disconnected: transport close 7 (G3-1)

2016-01-11T14:49:39.735Z - debug: Socket disconnected: transport close 19 (XT1072)

2016-01-11T14:49:39.856Z - debug: Socket disconnected: transport close 9 (S5-1)

2016-01-11T14:49:40.225Z - debug: Socket disconnected: transport close 3 (G3s-1)

2016-01-11T14:49:40.888Z - debug: Socket disconnected: transport close 5 (G4-1)

2016-01-11T14:49:41.718Z - debug: Socket disconnected: transport close 2 (Thali Test (Galaxy S5))

2016-01-11T14:50:55.900Z - debug: Socket disconnected: ping timeout 6 (Thali Test (Galaxy A3))

2016-01-11T14:51:05.308Z - debug: Socket disconnected: ping timeout 4 (A3-1)


 
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
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on f56ad48d 
Device test finished on LGH8153b36be34 
Android task is completed. [SUCCESS]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/55613145e2b298d_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/55613145e2b298d_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/55613145e2b298d_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/55613145e2b298d_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/55613145e2b298d_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/55613145e2b298d_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/55613145e2b298d_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
STOP log received from  0be0c6c6 Test has  SUCCEEDED
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Device test finished on ZX1C223JKW 
Device test finished on 0be0c6c6 
Android task is completed. [SUCCESS]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/55613145e2b298d_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali04_samsung-SM-G900F.md)

[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/55613145e2b298d_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/55613145e2b298d_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali04_samsung-SM-N910C.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/55613145e2b298d_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/55613145e2b298d_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/55613145e2b298d_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
STOP log received from  4db5c8cc Test has  SUCCEEDED
Device test finished on 4db5c8cc 
STOP log received from  c5afcdcb Test has  SUCCEEDED
Device test finished on c5afcdcb 
Android task is completed. [SUCCESS]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/55613145e2b298d_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/55613145e2b298d_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device HT574YC04723 app:com.test.thalitest code:0 
child process exited with code 0 on device HT574YC04723 
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:null 
child process exited with code null on device 4325e43f 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/55613145e2b298d_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/55613145e2b298d_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/55613145e2b298d_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/55613145e2b298d_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/55613145e2b298d_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/55613145e2b298d_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/55613145e2b298d_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/55613145e2b298d_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/iOS_Iphone5s-1.md)



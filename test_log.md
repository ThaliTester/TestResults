#### Test 55431344e5dd625 Logs

#### Test Server Logs
```
Error: Command failed: 

node.js:927
            throw ee;
                  ^

Error: Missing or duplicate config for test %s
    at doTest (/home/pi/Test/server_55431344e5dd625/test/TestServer/PerfTestFramework.js:222:13)
    at /home/pi/Test/server_55431344e5dd625/test/TestServer/PerfTestFramework.js:234:11
    at process._tickCallback (node.js:917:13)

IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-08T07:30:16.301Z - info: listening on *:3000

2016-01-08T07:30:16.730Z - debug: Device presented: S5-1 (android) perftest socket:0

2016-01-08T07:30:16.736Z - info: Setting start timeout to: 120000 (android)

2016-01-08T07:30:16.772Z - debug: Device presented: Apple-IpadAir2-1 (ios) perftest socket:1

2016-01-08T07:30:16.773Z - info: Setting start timeout to: 120000 (ios)

2016-01-08T07:30:16.868Z - debug: Device presented: G3s-1 (android) perftest socket:2

2016-01-08T07:30:17.033Z - debug: Device presented: A5-1 (android) perftest socket:3

2016-01-08T07:30:17.422Z - debug: Device presented: Apple-Iphone5s-1 (ios) perftest socket:4

2016-01-08T07:30:17.428Z - debug: Device presented: Apple-Iphone6-1 (ios) perftest socket:5

2016-01-08T07:30:17.751Z - debug: Device presented: A3-1 (android) perftest socket:6

2016-01-08T07:30:18.531Z - debug: Device presented: HTC One M8s (android) perftest socket:7

2016-01-08T07:30:18.640Z - debug: Device presented: Apple-Iphone5-1 (ios) perftest socket:8

2016-01-08T07:30:18.641Z - info: Required number of devices presented

2016-01-08T07:30:18.644Z - info: Starting perf test run for platform: ios

2016-01-08T07:30:18.645Z - info: Using devices:

2016-01-08T07:30:18.646Z - info: Apple-IpadAir2-1

2016-01-08T07:30:18.647Z - info: Apple-Iphone5s-1
2016-01-08T07:30:18.648Z - info: Apple-Iphone6-1

2016-01-08T07:30:18.649Z - info: Apple-Iphone5-1

2016-01-08T07:30:18.652Z - info: Starting test: with 4 devices (ios)

2016-01-08T07:30:18.676Z - debug: Device presented: Thali Test (Galaxy S5) (android) perftest socket:9

2016-01-08T07:30:20.012Z - info: Received results for {"name:":"Apple-Iphone5-1","time":1123,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone6-1.DpDJvQ==","peerAvailable":true,"time":1122}]} Apple-Iphone5-1 ios (3 left)

2016-01-08T07:30:20.063Z - debug: Device presented: XT1072 (android) perftest socket:10

2016-01-08T07:30:20.069Z - info: Received results for {"name:":"Apple-Iphone6-1","time":1061,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone5-1.8yAUdA==","peerAvailable":true,"time":1059}]} Apple-Iphone6-1 ios (2 left)

2016-01-08T07:30:20.101Z - info: Received results for {"name:":"Apple-IpadAir2-1","time":1069,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone5-1.8yAUdA==","peerAvailable":true,"time":1067}]} Apple-IpadAir2-1 ios (1 left)

2016-01-08T07:30:20.389Z - debug: Device presented: G4-1 (android) perftest socket:11

2016-01-08T07:30:20.671Z - debug: Device presented: Thali Test (Galaxy A5) (android) perftest socket:12

2016-01-08T07:30:20.686Z - debug: Device presented: Nexus 5 (android) perftest socket:13

2016-01-08T07:30:20.698Z - info: Received results for {"name:":"Apple-Iphone5s-1","time":1062,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone6-1.DpDJvQ==","peerAvailable":true,"time":1060}]} Apple-Iphone5s-1 ios (0 left)

2016-01-08T07:30:20.701Z - info: All test data retrieved for testFindPeers.js (ios)

2016-01-08T07:30:20.709Z - info: Remaining tests: testSendData.js

2016-01-08T07:30:20.711Z - info: Continuing to next test: testSendData.js

2016-01-08T07:30:20.713Z - info: Starting test: with 4 devices (ios)

2016-01-08T07:30:21.055Z - debug: Device presented: Thali Test (Galaxy A3) (android) perftest socket:14

2016-01-08T07:30:21.083Z - debug: Device presented: Note4-1 (android) perftest socket:15

2016-01-08T07:30:21.720Z - debug: Device presented: S5mini-1 (android) perftest socket:16

2016-01-08T07:30:23.622Z - debug: Socket disconnected: transport close 16 (S5mini-1)

2016-01-08T07:30:24.957Z - debug: Device presented: G3-1 (android) perftest socket:17

2016-01-08T07:30:43.422Z - debug: Device presented: XT1039 (android) perftest socket:18

2016-01-08T07:30:44.985Z - debug: Socket disconnected: transport close 18 (XT1039)

2016-01-08T07:31:16.285Z - info: Received results for {"name:":"Apple-Iphone6-1","time":55416,"result":"OK","sendList":[{"name":"Apple-Iphone6-1.DpDJvQ==","time":41278,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-Iphone5-1.kpUZpA==","time":4533,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1.WrRjQQ==","time":4714,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1.5QwW9A==","time":4647,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone6-1 ios (3 left)

2016-01-08T07:31:17.263Z - info: Received results for {"name:":"Apple-Iphone5-1","time":56178,"result":"OK","sendList":[{"name":"Apple-Iphone6-1.DpDJvQ==","time":41658,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-IpadAir2-1.5QwW9A==","time":6062,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1.O1yvYA==","time":4264,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1.WrRjQQ==","time":4076,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone5-1 ios (2 left)

2016-01-08T07:31:17.267Z - info: Received results for {"name:":"Apple-Iphone5s-1","time":56235,"result":"OK","sendList":[{"name":"Apple-Iphone6-1.DpDJvQ==","time":42054,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-Iphone5-1.kpUZpA==","time":5571,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1.O1yvYA==","time":3716,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1.5QwW9A==","time":4660,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone5s-1 ios (1 left)

2016-01-08T07:31:17.271Z - info: Received results for {"name:":"Apple-IpadAir2-1","time":56290,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1.NE8BAA==","time":40787,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-Iphone5-1.kpUZpA==","time":6147,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1.O1yvYA==","time":4679,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1.WrRjQQ==","time":4094,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-IpadAir2-1 ios (0 left)

2016-01-08T07:31:17.272Z - info: All test data retrieved for testSendData.js (ios)

2016-01-08T07:31:17.280Z - info: ALL DONE !!!

{ 'name:': 'Apple-IpadAir2-1',
  time: 1069,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1.8yAUdA==',
       peerAvailable: true,
       time: 1067 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 1062,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1.DpDJvQ==',
       peerAvailable: true,
       time: 1060 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 1061,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1.8yAUdA==',
       peerAvailable: true,
       time: 1059 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 1123,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1.DpDJvQ==',
       peerAvailable: true,
       time: 1122 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 56290,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5s-1.NE8BAA==',
       time: 40787,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.kpUZpA==',
       time: 6147,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.O1yvYA==',
       time: 4679,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.WrRjQQ==',
       time: 4094,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 56235,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1.DpDJvQ==',
       time: 42054,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.kpUZpA==',
       time: 5571,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.O1yvYA==',
       time: 3716,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1.5QwW9A==',
       time: 4660,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 55416,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1.DpDJvQ==',
       time: 41278,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.kpUZpA==',
       time: 4533,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.WrRjQQ==',
       time: 4714,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1.5QwW9A==',
       time: 4647,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 56178,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1.DpDJvQ==',
       time: 41658,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.5QwW9A==',
       time: 6062,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.O1yvYA==',
       time: 4264,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.WrRjQQ==',
       time: 4076,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

--------------- test report ---------------------
--------------- Apple-IpadAir2-1 --------------------- : 1

Find peers : 100% : 1067 ms, 99% : 1067 ms, 95 : 1067 ms, 90% : 1067 ms.

Result count 1, range 1067 ms to  1067 ms.

Send data : 100% : 6147 ms, 99% : 6147 ms, 95 : 6147 ms, 90% : 6147 ms.

Average data rate: 0.02 MB/s

Result count 3, range 4094 ms to  6147 ms.

Send data failed peers count : 1 [25 %]

- Peer ID : Apple-Iphone5s-1.NE8BAA==, Tried : 5

Send data never tried peers count : 0 [0 %]

--------------- Apple-Iphone5s-1 --------------------- : 2
Find peers : 100% : 1060 ms, 99% : 1060 ms, 95 : 1060 ms, 90% : 1060 ms.

Result count 1, range 1060 ms to  1060 ms.
Send data : 100% : 5571 ms, 99% : 5571 ms, 95 : 5571 ms, 90% : 5571 ms.

Average data rate: 0.022 MB/s
Result count 3, range 3716 ms to  5571 ms.

Send data failed peers count : 1 [25 %]

- Peer ID : Apple-Iphone6-1.DpDJvQ==, Tried : 5
Send data never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1 --------------------- : 3
Find peers : 100% : 1059 ms, 99% : 1059 ms, 95 : 1059 ms, 90% : 1059 ms.
Result count 1, range 1059 ms to  1059 ms.
Send data : 100% : 4714 ms, 99% : 4714 ms, 95 : 4714 ms, 90% : 4714 ms.

Average data rate: 0.022 MB/s
Result count 3, range 4533 ms to  4714 ms.
Send data failed peers count : 1 [25 %]

- Peer ID : Apple-Iphone6-1.DpDJvQ==, Tried : 5

Send data never tried peers count : 0 [0 %]

--------------- Apple-Iphone5-1 --------------------- : 4
Find peers : 100% : 1122 ms, 99% : 1122 ms, 95 : 1122 ms, 90% : 1122 ms.
Result count 1, range 1122 ms to  1122 ms.

Send data : 100% : 6062 ms, 99% : 6062 ms, 95 : 6062 ms, 90% : 6062 ms.
Average data rate: 0.021 MB/s
Result count 3, range 4076 ms to  6062 ms.

Send data failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone6-1.DpDJvQ==, Tried : 5
Send data never tried peers count : 0 [0 %]
--------------- Combined ---------------------

Find peers : 100% : 1122 ms, 99% : 1122 ms, 95 : 1122 ms, 90% : 1122 ms.

Send data : 100% : 6147 ms, 99% : 6147 ms, 95 : 6062 ms, 90% : 6062 ms.

Average data rate: 0.021 MB/s
--------------- end of test report ---------------------

2016-01-08T07:31:17.410Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1.8yAUdA==, peerAvailable=true, time=1067], sendList=[name=Apple-Iphone5s-1.WrRjQQ==, time=4094, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone6-1.O1yvYA==, time=4679, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1.kpUZpA==, time=6147, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone5s-1.NE8BAA==, time=40787, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1.DpDJvQ==, peerAvailable=true, time=1060], sendList=[name=Apple-Iphone6-1.O1yvYA==, time=3716, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.5QwW9A==, time=4660, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1.kpUZpA==, time=5571, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone6-1.DpDJvQ==, time=42054, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1.8yAUdA==, peerAvailable=true, time=1059], sendList=[name=Apple-Iphone5-1.kpUZpA==, time=4533, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.5QwW9A==, time=4647, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5s-1.WrRjQQ==, time=4714, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone6-1.DpDJvQ==, time=41278, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1.DpDJvQ==, peerAvailable=true, time=1122], sendList=[name=Apple-Iphone5s-1.WrRjQQ==, time=4076, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone6-1.O1yvYA==, time=4264, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.5QwW9A==, time=6062, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone6-1.DpDJvQ==, time=41658, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[]

2016-01-08T07:31:17.423Z - debug: end to Apple-IpadAir2-1

2016-01-08T07:31:17.425Z - debug: end to Apple-Iphone5s-1

2016-01-08T07:31:17.427Z - debug: end to Apple-Iphone6-1

2016-01-08T07:31:17.428Z - debug: end to Apple-Iphone5-1

2016-01-08T07:31:18.316Z - debug: state: android waiting

2016-01-08T07:31:18.317Z - debug: state: ios completed

2016-01-08T07:31:20.220Z - debug: Socket disconnected: transport close 1 (Apple-IpadAir2-1)

2016-01-08T07:31:20.381Z - debug: Socket disconnected: transport close 5 (Apple-Iphone6-1)

2016-01-08T07:31:20.742Z - debug: Socket disconnected: transport close 4 (Apple-Iphone5s-1)

2016-01-08T07:31:20.794Z - debug: Socket disconnected: transport close 8 (Apple-Iphone5-1)

2016-01-08T07:32:16.751Z - info: Start timeout elapsed for platform: android

2016-01-08T07:32:16.755Z - info: Starting perf test run for platform: android

2016-01-08T07:32:16.757Z - info: Using devices:
2016-01-08T07:32:16.758Z - info: S5-1

2016-01-08T07:32:16.760Z - info: G3s-1

2016-01-08T07:32:16.761Z - info: A5-1
2016-01-08T07:32:16.762Z - info: A3-1

2016-01-08T07:32:16.762Z - info: HTC One M8s
2016-01-08T07:32:16.763Z - info: Thali Test (Galaxy S5)
2016-01-08T07:32:16.764Z - info: XT1072

2016-01-08T07:32:16.764Z - info: G4-1
2016-01-08T07:32:16.765Z - info: Thali Test (Galaxy A5)

2016-01-08T07:32:16.766Z - info: Nexus 5

2016-01-08T07:32:16.770Z - info: Thali Test (Galaxy A3)

2016-01-08T07:32:16.771Z - info: Note4-1
2016-01-08T07:32:16.771Z - info: S5mini-1

2016-01-08T07:32:16.774Z - info: G3-1

2016-01-08T07:32:16.774Z - info: XT1039

2016-01-08T07:32:16.775Z - info: Starting test: with 15 devices (android)

2016-01-08T07:33:57.043Z - info: Received results for {"name:":"S5-1","time":100105,"result":"TIMEOUT","peersList":[{"peerName":"Nexus 5","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":true,"time":3722},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":3753},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":24308},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":38169},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":90489},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":90539}]} S5-1 android (14 left)

2016-01-08T07:33:57.093Z - info: Received results for {"name:":"Thali Test (Galaxy A5)","time":100070,"result":"TIMEOUT","peersList":[{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":2802},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":2831},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":2934},{"peerName":"HTC One M8s","peerIdentifier":"90:E7:C4:F6:69:77","peerAvailable":true,"time":42399},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":44208}]} Thali Test (Galaxy A5) android (13 left)

2016-01-08T07:33:57.099Z - info: Received results for {"name:":"A5-1","time":100074,"result":"TIMEOUT","peersList":[{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":3499},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":4138},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":41220}]} A5-1 android (12 left)

2016-01-08T07:33:57.107Z - info: Received results for {"name:":"Thali Test (Galaxy S5)","time":100139,"result":"TIMEOUT","peersList":[{"peerName":"Nexus 5","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":true,"time":4042},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":13998},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":14646},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":26982},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":44932},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":73613},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":81453},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":84062}]} Thali Test (Galaxy S5) android (11 left)

2016-01-08T07:33:57.113Z - info: Received results for {"name:":"Thali Test (Galaxy A3)","time":100076,"result":"TIMEOUT","peersList":[{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":2552},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":2595},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":41409},{"peerName":"HTC One M8s","peerIdentifier":"90:E7:C4:F6:69:77","peerAvailable":true,"time":42260},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":43663},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":53316},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":89221},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":94193}]} Thali Test (Galaxy A3) android (10 left)

2016-01-08T07:33:57.118Z - info: Received results for {"name:":"Note4-1","time":100061,"result":"TIMEOUT","peersList":[{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":79550},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":79586},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":93822}]} Note4-1 android (9 left)

2016-01-08T07:33:57.124Z - info: Received results for {"name:":"G4-1","time":100218,"result":"TIMEOUT","peersList":[{"peerName":"Nexus 5","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":true,"time":4423},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":false,"time":94435},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":10093},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":40574},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":61867},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":61910}]} G4-1 android (8 left)

2016-01-08T07:33:57.165Z - info: Received results for {"name:":"HTC One M8s","time":100069,"result":"TIMEOUT","peersList":[{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":2944},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":3028},{"peerName":"Note4-1","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":3802},{"peerName":"Nexus 5","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":true,"time":3980},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":5931},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":40856},{"peerName":"XT1072","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true,"time":77676},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":77948},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":78657},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":83849}]} HTC One M8s android (7 left)

2016-01-08T07:33:57.168Z - info: Received results for {"name:":"XT1072","time":100112,"result":"TIMEOUT","peersList":[{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":2697},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":3937},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":4139},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":5002},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":9620},{"peerName":"Nexus 5","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":true,"time":19938},{"peerName":"Note4-1","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":28706},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":33797},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":34377},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":36084},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":70742},{"peerName":"HTC One M8s","peerIdentifier":"90:E7:C4:F6:69:77","peerAvailable":true,"time":76423}]} XT1072 android (6 left)

2016-01-08T07:33:57.313Z - info: Received results for {"name:":"A3-1","time":100083,"result":"TIMEOUT","peersList":[{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":41388},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":80217},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":80390},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":83745},{"peerName":"Note4-1","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":92538},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":92636},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":92986},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":93249}]} A3-1 android (5 left)

2016-01-08T07:33:57.335Z - info: Received results for {"name:":"Nexus 5","time":100059,"result":"TIMEOUT","peersList":[{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":39820},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":85639}]} Nexus 5 android (4 left)

2016-01-08T07:33:57.737Z - info: Received results for {"name:":"G3s-1","time":100247,"result":"TIMEOUT","peersList":[{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":30727},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":39096},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":63319}]} G3s-1 android (3 left)

2016-01-08T07:33:57.931Z - info: Received results for {"name:":"G3-1","time":100074,"result":"TIMEOUT","peersList":[{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":20519},{"peerName":"XT1072","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true,"time":36631},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":38249}]} G3-1 android (2 left)

2016-01-08T07:34:16.832Z - info: server timeout for test: testFindPeers.js (android)

2016-01-08T07:34:16.834Z - info: All test data retrieved for testFindPeers.js (android)

2016-01-08T07:34:16.849Z - info: No results from S5mini-1

2016-01-08T07:34:16.851Z - info: No results from XT1039
2016-01-08T07:34:16.853Z - info: Remaining tests: testSendData.js

2016-01-08T07:34:16.857Z - info: server timeout for test: testFindPeers.js (android)

2016-01-08T07:34:16.858Z - info: All test data retrieved for testFindPeers.js (android)
2016-01-08T07:34:16.862Z - info: No results from S5mini-1
2016-01-08T07:34:16.863Z - info: No results from XT1039
2016-01-08T07:34:16.864Z - info: ALL DONE !!!
{ 'name:': 'Apple-IpadAir2-1',
  time: 1069,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1.8yAUdA==',
       peerAvailable: true,
       time: 1067 } ] }
{ 'name:': 'Apple-Iphone5s-1',
  time: 1062,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1.DpDJvQ==',
       peerAvailable: true,
       time: 1060 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 1061,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1.8yAUdA==',
       peerAvailable: true,
       time: 1059 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 1123,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1.DpDJvQ==',
       peerAvailable: true,
       time: 1122 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 56290,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5s-1.NE8BAA==',
       time: 40787,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.kpUZpA==',
       time: 6147,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.O1yvYA==',
       time: 4679,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.WrRjQQ==',
       time: 4094,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 56235,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1.DpDJvQ==',
       time: 42054,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.kpUZpA==',
       time: 5571,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.O1yvYA==',
       time: 3716,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1.5QwW9A==',
       time: 4660,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 55416,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1.DpDJvQ==',
       time: 41278,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.kpUZpA==',
       time: 4533,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.WrRjQQ==',
       time: 4714,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1.5QwW9A==',
       time: 4647,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 56178,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1.DpDJvQ==',
       time: 41658,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.5QwW9A==',
       time: 6062,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.O1yvYA==',
       time: 4264,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.WrRjQQ==',
       time: 4076,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'S5-1',
  time: 100105,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 3722 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 3753 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 24308 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 38169 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 90489 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 90539 } ] }

{ 'name:': 'G3s-1',
  time: 100247,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 30727 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 39096 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 63319 } ] }

{ 'name:': 'A5-1',
  time: 100074,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 3499 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 4138 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 41220 } ] }

{ 'name:': 'A3-1',
  time: 100083,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 41388 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 80217 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 80390 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 83745 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 92538 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 92636 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 92986 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 93249 } ] }

{ 'name:': 'HTC One M8s',
  time: 100069,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 2944 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 3028 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 3802 },
     { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 3980 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 5931 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 40856 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 77676 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 77948 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 78657 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 83849 } ] }

{ 'name:': 'Thali Test (Galaxy S5)',
  time: 100139,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 4042 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 13998 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 14646 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 26982 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 44932 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 73613 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 81453 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 84062 } ] }

{ 'name:': 'XT1072',
  time: 100112,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 2697 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 3937 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 4139 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 5002 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 9620 },
     { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 19938 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 28706 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 33797 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 34377 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 36084 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 70742 },
     { peerName: 'HTC One M8s',
       peerIdentifier: '90:E7:C4:F6:69:77',
       peerAvailable: true,
       time: 76423 } ] }

{ 'name:': 'G4-1',
  time: 100218,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 4423 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: false,
       time: 94435 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 10093 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 40574 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 61867 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 61910 } ] }

{ 'name:': 'Thali Test (Galaxy A5)',
  time: 100070,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 2802 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 2831 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 2934 },
     { peerName: 'HTC One M8s',
       peerIdentifier: '90:E7:C4:F6:69:77',
       peerAvailable: true,
       time: 42399 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 44208 } ] }

{ 'name:': 'Nexus 5',
  time: 100059,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 39820 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 85639 } ] }

{ 'name:': 'Thali Test (Galaxy A3)',
  time: 100076,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 2552 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 2595 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 41409 },
     { peerName: 'HTC One M8s',
       peerIdentifier: '90:E7:C4:F6:69:77',
       peerAvailable: true,
       time: 42260 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 43663 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 53316 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 89221 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 94193 } ] }

{ 'name:': 'Note4-1',
  time: 100061,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 79550 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 79586 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 93822 } ] }

{ 'name:': 'G3-1',
  time: 100074,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 20519 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 36631 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 38249 } ] }

{ 'name:': 'S5-1',
  time: 100105,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 3722 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 3753 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 24308 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 38169 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 90489 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 90539 } ] }

{ 'name:': 'G3s-1',
  time: 100247,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 30727 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 39096 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 63319 } ] }

{ 'name:': 'A5-1',
  time: 100074,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 3499 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 4138 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 41220 } ] }

{ 'name:': 'A3-1',
  time: 100083,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 41388 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 80217 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 80390 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 83745 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 92538 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 92636 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 92986 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 93249 } ] }

{ 'name:': 'HTC One M8s',
  time: 100069,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 2944 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 3028 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 3802 },
     { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 3980 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 5931 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 40856 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 77676 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 77948 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 78657 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 83849 } ] }

{ 'name:': 'Thali Test (Galaxy S5)',
  time: 100139,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 4042 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 13998 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 14646 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 26982 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 44932 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 73613 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 81453 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 84062 } ] }

{ 'name:': 'XT1072',
  time: 100112,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 2697 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 3937 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 4139 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 5002 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 9620 },
     { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 19938 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 28706 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 33797 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 34377 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 36084 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 70742 },
     { peerName: 'HTC One M8s',
       peerIdentifier: '90:E7:C4:F6:69:77',
       peerAvailable: true,
       time: 76423 } ] }

{ 'name:': 'G4-1',
  time: 100218,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 4423 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: false,
       time: 94435 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 10093 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 40574 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 61867 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 61910 } ] }

{ 'name:': 'Thali Test (Galaxy A5)',
  time: 100070,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 2802 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 2831 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 2934 },
     { peerName: 'HTC One M8s',
       peerIdentifier: '90:E7:C4:F6:69:77',
       peerAvailable: true,
       time: 42399 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 44208 } ] }

{ 'name:': 'Nexus 5',
  time: 100059,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 39820 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 85639 } ] }

{ 'name:': 'Thali Test (Galaxy A3)',
  time: 100076,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 2552 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 2595 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 41409 },
     { peerName: 'HTC One M8s',
       peerIdentifier: '90:E7:C4:F6:69:77',
       peerAvailable: true,
       time: 42260 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 43663 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 53316 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 89221 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 94193 } ] }

{ 'name:': 'Note4-1',
  time: 100061,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 79550 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 79586 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 93822 } ] }

{ 'name:': 'G3-1',
  time: 100074,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 20519 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 36631 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 38249 } ] }

--------------- test report ---------------------
--------------- Apple-IpadAir2-1 --------------------- : 1
Find peers : 100% : 1067 ms, 99% : 1067 ms, 95 : 1067 ms, 90% : 1067 ms.

Result count 1, range 1067 ms to  1067 ms.
Send data : 100% : 6147 ms, 99% : 6147 ms, 95 : 6147 ms, 90% : 6147 ms.

Average data rate: 0.02 MB/s
Result count 3, range 4094 ms to  6147 ms.
Send data failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone5s-1.NE8BAA==, Tried : 5

Send data never tried peers count : 0 [0 %]
--------------- Apple-Iphone5s-1 --------------------- : 2
Find peers : 100% : 1060 ms, 99% : 1060 ms, 95 : 1060 ms, 90% : 1060 ms.
Result count 1, range 1060 ms to  1060 ms.
Send data : 100% : 5571 ms, 99% : 5571 ms, 95 : 5571 ms, 90% : 5571 ms.
Average data rate: 0.022 MB/s
Result count 3, range 3716 ms to  5571 ms.

Send data failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone6-1.DpDJvQ==, Tried : 5
Send data never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1 --------------------- : 3

Find peers : 100% : 1059 ms, 99% : 1059 ms, 95 : 1059 ms, 90% : 1059 ms.
Result count 1, range 1059 ms to  1059 ms.
Send data : 100% : 4714 ms, 99% : 4714 ms, 95 : 4714 ms, 90% : 4714 ms.

Average data rate: 0.022 MB/s
Result count 3, range 4533 ms to  4714 ms.
Send data failed peers count : 1 [25 %]

- Peer ID : Apple-Iphone6-1.DpDJvQ==, Tried : 5
Send data never tried peers count : 0 [0 %]
--------------- Apple-Iphone5-1 --------------------- : 4
Find peers : 100% : 1122 ms, 99% : 1122 ms, 95 : 1122 ms, 90% : 1122 ms.

Result count 1, range 1122 ms to  1122 ms.
Send data : 100% : 6062 ms, 99% : 6062 ms, 95 : 6062 ms, 90% : 6062 ms.
Average data rate: 0.021 MB/s

Result count 3, range 4076 ms to  6062 ms.
Send data failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone6-1.DpDJvQ==, Tried : 5
Send data never tried peers count : 0 [0 %]

--------------- S5-1 --------------------- : 5

Find peers : 100% : 90539 ms, 99% : 90539 ms, 95 : 90539 ms, 90% : 90539 ms.
Result count 12, range 3722 ms to  90539 ms.

--------------- G3s-1 --------------------- : 6
Find peers : 100% : 63319 ms, 99% : 63319 ms, 95 : 63319 ms, 90% : 63319 ms.
Result count 6, range 30727 ms to  63319 ms.

--------------- A5-1 --------------------- : 7
Find peers : 100% : 41220 ms, 99% : 41220 ms, 95 : 41220 ms, 90% : 41220 ms.
Result count 6, range 3499 ms to  41220 ms.

--------------- A3-1 --------------------- : 8

Find peers : 100% : 93249 ms, 99% : 93249 ms, 95 : 93249 ms, 90% : 92986 ms.

Result count 16, range 41388 ms to  93249 ms.
--------------- HTC One M8s --------------------- : 9
Find peers : 100% : 83849 ms, 99% : 83849 ms, 95 : 83849 ms, 90% : 78657 ms.

Result count 20, range 2944 ms to  83849 ms.
--------------- Thali Test (Galaxy S5) --------------------- : 10
Find peers : 100% : 84062 ms, 99% : 84062 ms, 95 : 84062 ms, 90% : 81453 ms.

Result count 16, range 4042 ms to  84062 ms.
--------------- XT1072 --------------------- : 11

Find peers : 100% : 76423 ms, 99% : 76423 ms, 95 : 76423 ms, 90% : 70742 ms.
Result count 24, range 2697 ms to  76423 ms.
--------------- G4-1 --------------------- : 12

Find peers : 100% : 94435 ms, 99% : 94435 ms, 95 : 94435 ms, 90% : 94435 ms.

Result count 12, range 4423 ms to  94435 ms.
--------------- Thali Test (Galaxy A5) --------------------- : 13
Find peers : 100% : 44208 ms, 99% : 44208 ms, 95 : 44208 ms, 90% : 44208 ms.
Result count 10, range 2802 ms to  44208 ms.

--------------- Nexus 5 --------------------- : 14
Find peers : 100% : 85639 ms, 99% : 85639 ms, 95 : 85639 ms, 90% : 85639 ms.
Result count 4, range 39820 ms to  85639 ms.

--------------- Thali Test (Galaxy A3) --------------------- : 15
Find peers : 100% : 94193 ms, 99% : 94193 ms, 95 : 94193 ms, 90% : 89221 ms.
Result count 16, range 2552 ms to  94193 ms.

--------------- Note4-1 --------------------- : 16
Find peers : 100% : 93822 ms, 99% : 93822 ms, 95 : 93822 ms, 90% : 93822 ms.
Result count 6, range 79550 ms to  93822 ms.
--------------- G3-1 --------------------- : 17

Find peers : 100% : 38249 ms, 99% : 38249 ms, 95 : 38249 ms, 90% : 38249 ms.
Result count 6, range 20519 ms to  38249 ms.
--------------- Combined ---------------------

Find peers : 100% : 94435 ms, 99% : 94193 ms, 95 : 92986 ms, 90% : 90489 ms.

Send data : 100% : 6147 ms, 99% : 6147 ms, 95 : 6062 ms, 90% : 6062 ms.

Average data rate: 0.021 MB/s
--------------- end of test report ---------------------

2016-01-08T07:34:17.245Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1.8yAUdA==, peerAvailable=true, time=1067], sendList=[name=Apple-Iphone5s-1.WrRjQQ==, time=4094, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone6-1.O1yvYA==, time=4679, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1.kpUZpA==, time=6147, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone5s-1.NE8BAA==, time=40787, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1.DpDJvQ==, peerAvailable=true, time=1060], sendList=[name=Apple-Iphone6-1.O1yvYA==, time=3716, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.5QwW9A==, time=4660, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1.kpUZpA==, time=5571, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone6-1.DpDJvQ==, time=42054, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1.8yAUdA==, peerAvailable=true, time=1059], sendList=[name=Apple-Iphone5-1.kpUZpA==, time=4533, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.5QwW9A==, time=4647, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5s-1.WrRjQQ==, time=4714, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone6-1.DpDJvQ==, time=41278, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1.DpDJvQ==, peerAvailable=true, time=1122], sendList=[name=Apple-Iphone5s-1.WrRjQQ==, time=4076, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone6-1.O1yvYA==, time=4264, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.5QwW9A==, time=6062, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone6-1.DpDJvQ==, time=41658, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=Nexus 5, peerIdentifier=34:FC:EF:11:AE:67, peerAvailable=true, time=3722, $ref=$["S5-1"]["peersList"][0], peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=3753, $ref=$["S5-1"]["peersList"][2], peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=24308, $ref=$["S5-1"]["peersList"][4], peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=38169, $ref=$["S5-1"]["peersList"][6], peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=90489, $ref=$["S5-1"]["peersList"][8], peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=90539, $ref=$["S5-1"]["peersList"][10]], peersList=[peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=30727, $ref=$["G3s-1"]["peersList"][0], peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=39096, $ref=$["G3s-1"]["peersList"][2], peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=63319, $ref=$["G3s-1"]["peersList"][4]], peersList=[peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=3499, $ref=$["A5-1"]["peersList"][0], peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=4138, $ref=$["A5-1"]["peersList"][2], peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=41220, $ref=$["A5-1"]["peersList"][4]], peersList=[peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=41388, $ref=$["A3-1"]["peersList"][0], peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=80217, $ref=$["A3-1"]["peersList"][2], peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=80390, $ref=$["A3-1"]["peersList"][4], peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=83745, $ref=$["A3-1"]["peersList"][6], peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=92538, $ref=$["A3-1"]["peersList"][8], peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=92636, $ref=$["A3-1"]["peersList"][10], peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=92986, $ref=$["A3-1"]["peersList"][12], peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=93249, $ref=$["A3-1"]["peersList"][14]], peersList=[peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=2944, $ref=$["HTC One M8s"]["peersList"][0], peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=3028, $ref=$["HTC One M8s"]["peersList"][2], peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=3802, $ref=$["HTC One M8s"]["peersList"][4], peerName=Nexus 5, peerIdentifier=34:FC:EF:11:AE:67, peerAvailable=true, time=3980, $ref=$["HTC One M8s"]["peersList"][6], peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=5931, $ref=$["HTC One M8s"]["peersList"][8], peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=40856, $ref=$["HTC One M8s"]["peersList"][10], peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=77676, $ref=$["HTC One M8s"]["peersList"][12], peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=77948, $ref=$["HTC One M8s"]["peersList"][14], peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=78657, $ref=$["HTC One M8s"]["peersList"][16], peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=83849, $ref=$["HTC One M8s"]["peersList"][18]], peersList=[peerName=Nexus 5, peerIdentifier=34:FC:EF:11:AE:67, peerAvailable=true, time=4042, $ref=$["Thali Test (Galaxy S5)"]["peersList"][0], peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=13998, $ref=$["Thali Test (Galaxy S5)"]["peersList"][2], peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=14646, $ref=$["Thali Test (Galaxy S5)"]["peersList"][4], peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=26982, $ref=$["Thali Test (Galaxy S5)"]["peersList"][6], peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=44932, $ref=$["Thali Test (Galaxy S5)"]["peersList"][8], peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=73613, $ref=$["Thali Test (Galaxy S5)"]["peersList"][10], peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=81453, $ref=$["Thali Test (Galaxy S5)"]["peersList"][12], peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=84062, $ref=$["Thali Test (Galaxy S5)"]["peersList"][14]], peersList=[peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=2697, $ref=$["XT1072"]["peersList"][0], peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=3937, $ref=$["XT1072"]["peersList"][2], peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=4139, $ref=$["XT1072"]["peersList"][4], peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=5002, $ref=$["XT1072"]["peersList"][6], peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=9620, $ref=$["XT1072"]["peersList"][8], peerName=Nexus 5, peerIdentifier=34:FC:EF:11:AE:67, peerAvailable=true, time=19938, $ref=$["XT1072"]["peersList"][10], peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=28706, $ref=$["XT1072"]["peersList"][12], peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=33797, $ref=$["XT1072"]["peersList"][14], peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=34377, $ref=$["XT1072"]["peersList"][16], peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=36084, $ref=$["XT1072"]["peersList"][18], peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=70742, $ref=$["XT1072"]["peersList"][20], peerName=HTC One M8s, peerIdentifier=90:E7:C4:F6:69:77, peerAvailable=true, time=76423, $ref=$["XT1072"]["peersList"][22]], peersList=[peerName=Nexus 5, peerIdentifier=34:FC:EF:11:AE:67, peerAvailable=true, time=4423, $ref=$["G4-1"]["peersList"][0], peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=10093, $ref=$["G4-1"]["peersList"][2], peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=40574, $ref=$["G4-1"]["peersList"][4], peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=61867, $ref=$["G4-1"]["peersList"][6], peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=61910, $ref=$["G4-1"]["peersList"][8], peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=false, time=94435, $ref=$["G4-1"]["peersList"][10]], peersList=[peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=2802, $ref=$["Thali Test (Galaxy A5)"]["peersList"][0], peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=2831, $ref=$["Thali Test (Galaxy A5)"]["peersList"][2], peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=2934, $ref=$["Thali Test (Galaxy A5)"]["peersList"][4], peerName=HTC One M8s, peerIdentifier=90:E7:C4:F6:69:77, peerAvailable=true, time=42399, $ref=$["Thali Test (Galaxy A5)"]["peersList"][6], peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=44208, $ref=$["Thali Test (Galaxy A5)"]["peersList"][8]], peersList=[peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=39820, $ref=$["Nexus 5"]["peersList"][0], peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=85639, $ref=$["Nexus 5"]["peersList"][2]], peersList=[peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=2552, $ref=$["Thali Test (Galaxy A3)"]["peersList"][0], peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=2595, $ref=$["Thali Test (Galaxy A3)"]["peersList"][2], peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=41409, $ref=$["Thali Test (Galaxy A3)"]["peersList"][4], peerName=HTC One M8s, peerIdentifier=90:E7:C4:F6:69:77, peerAvailable=true, time=42260, $ref=$["Thali Test (Galaxy A3)"]["peersList"][6], peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=43663, $ref=$["Thali Test (Galaxy A3)"]["peersList"][8], peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=53316, $ref=$["Thali Test (Galaxy A3)"]["peersList"][10], peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=89221, $ref=$["Thali Test (Galaxy A3)"]["peersList"][12], peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=94193, $ref=$["Thali Test (Galaxy A3)"]["peersList"][14]], peersList=[peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=79550, $ref=$["Note4-1"]["peersList"][0], peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=79586, $ref=$["Note4-1"]["peersList"][2], peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=93822, $ref=$["Note4-1"]["peersList"][4]], peersList=[peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=20519, $ref=$["G3-1"]["peersList"][0], peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=36631, $ref=$["G3-1"]["peersList"][2], peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=38249, $ref=$["G3-1"]["peersList"][4]]

2016-01-08T07:34:17.272Z - debug: end to S5-1

2016-01-08T07:34:17.273Z - debug: end to G3s-1

2016-01-08T07:34:17.275Z - debug: end to A5-1

2016-01-08T07:34:17.276Z - debug: end to A3-1

2016-01-08T07:34:17.277Z - debug: end to HTC One M8s
2016-01-08T07:34:17.278Z - debug: end to Thali Test (Galaxy S5)
2016-01-08T07:34:17.279Z - debug: end to XT1072
2016-01-08T07:34:17.281Z - debug: end to G4-1
2016-01-08T07:34:17.282Z - debug: end to Thali Test (Galaxy A5)

2016-01-08T07:34:17.283Z - debug: end to Nexus 5

2016-01-08T07:34:17.284Z - debug: end to Thali Test (Galaxy A3)

2016-01-08T07:34:17.286Z - debug: end to Note4-1

2016-01-08T07:34:17.287Z - debug: end to S5mini-1

2016-01-08T07:34:17.288Z - debug: end to G3-1

2016-01-08T07:34:17.289Z - debug: end to XT1039

2016-01-08T07:34:17.302Z - info: Continuing to next test: undefined

2016-01-08T07:34:17.303Z - info: Starting test: with 15 devices (android)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m


node.js:927
            throw ee;
                  ^

Error: Missing or duplicate config for test %s
    at doTest (/home/pi/Test/server_55431344e5dd625/test/TestServer/PerfTestFramework.js:222:13)
    at /home/pi/Test/server_55431344e5dd625/test/TestServer/PerfTestFramework.js:234:11
    at process._tickCallback (node.js:917:13)


```


Logs for system : 
```

ios : false

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!
```
###Android Logs
####Node name: thali01
Console output:
```
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:null 
child process exited with code null on device LGH8153b36be34 
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:null 
child process exited with code null on device f56ad48d 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/55431344e5dd625_Fix_an_issue_that_prevented_running_two_tests__vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/55431344e5dd625_Fix_an_issue_that_prevented_running_two_tests__vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:null 
child process exited with code null on device LGD7228ee9cf5b 
Error! Unexpected exit on device 09a9416e0297d102 app:com.test.thalitest code:null 
child process exited with code null on device 09a9416e0297d102 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/55431344e5dd625_Fix_an_issue_that_prevented_running_two_tests__vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/55431344e5dd625_Fix_an_issue_that_prevented_running_two_tests__vjrantal/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
Error! Unexpected exit on device TA4750HV7I app:com.test.thalitest code:null 
child process exited with code null on device TA4750HV7I 
Error! Unexpected exit on device LGD8553bed2d08 app:com.test.thalitest code:null 
child process exited with code null on device LGD8553bed2d08 
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:null 
child process exited with code null on device 320414cd475f91e3 
Android task is completed. [FAILED]
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/55431344e5dd625_Fix_an_issue_that_prevented_running_two_tests__vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/55431344e5dd625_Fix_an_issue_that_prevented_running_two_tests__vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/55431344e5dd625_Fix_an_issue_that_prevented_running_two_tests__vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:null 
child process exited with code null on device ZX1C223JKW 
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Error! Unexpected exit on device 0be0c6c6 app:com.test.thalitest code:null 
child process exited with code null on device 0be0c6c6 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/55431344e5dd625_Fix_an_issue_that_prevented_running_two_tests__vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/55431344e5dd625_Fix_an_issue_that_prevented_running_two_tests__vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/55431344e5dd625_Fix_an_issue_that_prevented_running_two_tests__vjrantal/thali04_samsung-SM-G900F.md)

####Node name: thali06
Console output:
```
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:null 
child process exited with code null on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:null 
child process exited with code null on device FA55PYS00566 
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:null 
child process exited with code null on device 022678fb504e29b0 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/55431344e5dd625_Fix_an_issue_that_prevented_running_two_tests__vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/55431344e5dd625_Fix_an_issue_that_prevented_running_two_tests__vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/55431344e5dd625_Fix_an_issue_that_prevented_running_two_tests__vjrantal/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
Error! Unexpected exit on device c5afcdcb app:com.test.thalitest code:null 
child process exited with code null on device c5afcdcb 
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:null 
child process exited with code null on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/55431344e5dd625_Fix_an_issue_that_prevented_running_two_tests__vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/55431344e5dd625_Fix_an_issue_that_prevented_running_two_tests__vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
Error! Unexpected exit on device HT574YC04723 app:com.test.thalitest code:null 
child process exited with code null on device HT574YC04723 
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:null 
child process exited with code null on device 4325e43f 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/55431344e5dd625_Fix_an_issue_that_prevented_running_two_tests__vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/55431344e5dd625_Fix_an_issue_that_prevented_running_two_tests__vjrantal/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
Error! Unexpected exit on device CC51WYC03425 app:com.test.thalitest code:null 
child process exited with code null on device CC51WYC03425 
Error! Unexpected exit on device 0c6a0f3c0bdb4e77 app:com.test.thalitest code:null 
child process exited with code null on device 0c6a0f3c0bdb4e77 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/55431344e5dd625_Fix_an_issue_that_prevented_running_two_tests__vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/55431344e5dd625_Fix_an_issue_that_prevented_running_two_tests__vjrantal/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/55431344e5dd625_Fix_an_issue_that_prevented_running_two_tests__vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/55431344e5dd625_Fix_an_issue_that_prevented_running_two_tests__vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/55431344e5dd625_Fix_an_issue_that_prevented_running_two_tests__vjrantal/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/55431344e5dd625_Fix_an_issue_that_prevented_running_two_tests__vjrantal/iOS_Iphone5s-1.md)



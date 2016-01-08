#### Test 55467363832a26e Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-08T16:56:59.806Z - info: listening on *:3000

2016-01-08T16:57:00.218Z - debug: Device presented: Nexus 5 (android) perftest socket:0

2016-01-08T16:57:00.224Z - info: Setting start timeout to: 120000 (android)

2016-01-08T16:57:00.366Z - debug: Device presented: HTC One M8s (android) perftest socket:1

2016-01-08T16:57:00.630Z - debug: Device presented: Apple-IpadAir2-1 (ios) perftest socket:2

2016-01-08T16:57:00.631Z - info: Setting start timeout to: 120000 (ios)

2016-01-08T16:57:01.017Z - debug: Device presented: A5-1 (android) perftest socket:3

2016-01-08T16:57:01.827Z - debug: Device presented: G4-1 (android) perftest socket:4

2016-01-08T16:57:02.266Z - debug: Device presented: Note4-1 (android) perftest socket:5

2016-01-08T16:57:02.570Z - debug: Device presented: Thali Test (Galaxy S5) (android) perftest socket:6

2016-01-08T16:57:02.653Z - debug: Device presented: G3-1 (android) perftest socket:7

2016-01-08T16:57:02.672Z - debug: Device presented: Apple-Iphone5s-1 (ios) perftest socket:8

2016-01-08T16:57:02.714Z - debug: Device presented: XT1072 (android) perftest socket:9

2016-01-08T16:57:02.770Z - debug: Device presented: Nexus 5 (android) perftest socket:10

2016-01-08T16:57:03.575Z - debug: Device presented: G3s-1 (android) perftest socket:11

2016-01-08T16:57:03.784Z - debug: Device presented: Thali Test's G2 (android) perftest socket:12

2016-01-08T16:57:03.934Z - debug: Device presented: Thali Test (Galaxy A5) (android) perftest socket:14

2016-01-08T16:57:03.939Z - debug: Device presented: S5-1 (android) perftest socket:13

2016-01-08T16:57:03.943Z - debug: Device presented: Apple-Iphone5-1 (ios) perftest socket:15

2016-01-08T16:57:03.982Z - debug: Device presented: A3-1 (android) perftest socket:16

2016-01-08T16:57:04.038Z - debug: Device presented: HTC Desire 820 (android) perftest socket:17

2016-01-08T16:57:04.205Z - debug: Device presented: HTC Desire 820 (android) perftest socket:18

2016-01-08T16:57:04.364Z - debug: Device presented: Thali Test (Galaxy A3) (android) perftest socket:19

2016-01-08T16:57:04.442Z - debug: Device presented: Apple-Iphone6-1 (ios) perftest socket:20

2016-01-08T16:57:04.445Z - info: Required number of devices presented

2016-01-08T16:57:04.449Z - info: Starting perf test run for platform: ios

2016-01-08T16:57:04.450Z - info: Using devices:

2016-01-08T16:57:04.452Z - info: Apple-IpadAir2-1

2016-01-08T16:57:04.453Z - info: Apple-Iphone5s-1

2016-01-08T16:57:04.454Z - info: Apple-Iphone5-1

2016-01-08T16:57:04.455Z - info: Apple-Iphone6-1

2016-01-08T16:57:04.459Z - info: Starting test: with 4 devices (ios)

2016-01-08T16:57:05.438Z - info: Received results for {"name:":"Apple-IpadAir2-1","time":692,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone6-1.3GMDyQ==","peerAvailable":true,"time":690}]} Apple-IpadAir2-1 ios (3 left)

2016-01-08T16:57:05.452Z - info: Received results for {"name:":"Apple-Iphone5-1","time":660,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone6-1.3GMDyQ==","peerAvailable":true,"time":659}]} Apple-Iphone5-1 ios (2 left)

2016-01-08T16:57:05.981Z - info: Received results for {"name:":"Apple-Iphone5s-1","time":643,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-IpadAir2-1.hiitZQ==","peerAvailable":true,"time":641}]} Apple-Iphone5s-1 ios (1 left)

2016-01-08T16:57:06.468Z - info: Received results for {"name:":"Apple-Iphone6-1","time":1723,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-IpadAir2-1.hiitZQ==","peerAvailable":true,"time":1721}]} Apple-Iphone6-1 ios (0 left)

2016-01-08T16:57:06.472Z - info: All test data retrieved for testFindPeers.js (ios)

2016-01-08T16:57:06.479Z - info: Remaining tests: testSendData.js

2016-01-08T16:57:06.481Z - info: Continuing to next test: testSendData.js

2016-01-08T16:57:06.482Z - info: Starting test: with 4 devices (ios)

2016-01-08T16:57:09.735Z - debug: Device presented: S5mini-1 (android) perftest socket:21

2016-01-08T16:57:11.145Z - debug: Device presented: XT1039 (android) perftest socket:22

2016-01-08T16:57:11.147Z - info: Required number of devices presented

2016-01-08T16:57:11.149Z - info: Starting perf test run for platform: android

2016-01-08T16:57:11.150Z - info: Using devices:

2016-01-08T16:57:11.151Z - info: Nexus 5
2016-01-08T16:57:11.152Z - info: HTC One M8s

2016-01-08T16:57:11.153Z - info: A5-1
2016-01-08T16:57:11.153Z - info: G4-1

2016-01-08T16:57:11.154Z - info: Note4-1

2016-01-08T16:57:11.155Z - info: Thali Test (Galaxy S5)

2016-01-08T16:57:11.164Z - info: G3-1

2016-01-08T16:57:11.165Z - info: XT1072
2016-01-08T16:57:11.166Z - info: Nexus 5

2016-01-08T16:57:11.176Z - info: G3s-1

2016-01-08T16:57:11.177Z - info: Thali Test's G2

2016-01-08T16:57:11.181Z - info: Thali Test (Galaxy A5)
2016-01-08T16:57:11.182Z - info: S5-1
2016-01-08T16:57:11.183Z - info: A3-1
2016-01-08T16:57:11.183Z - info: HTC Desire 820

2016-01-08T16:57:11.184Z - info: HTC Desire 820
2016-01-08T16:57:11.185Z - info: Thali Test (Galaxy A3)

2016-01-08T16:57:11.185Z - info: S5mini-1
2016-01-08T16:57:11.186Z - info: XT1039

2016-01-08T16:57:11.187Z - info: Starting test: with 19 devices (android)

2016-01-08T16:58:02.557Z - info: Received results for {"name:":"Apple-Iphone5s-1","time":55527,"result":"OK","sendList":[{"name":"Apple-Iphone6-1.3GMDyQ==","time":42248,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-Iphone5-1.kBkHjQ==","time":4536,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1.g6FFQA==","time":3660,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1.lYAIVQ==","time":4908,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone5s-1 ios (3 left)

2016-01-08T16:58:07.092Z - info: Received results for {"name:":"Apple-Iphone6-1","time":59327,"result":"OK","sendList":[{"name":"Apple-Iphone5-1.vqNzbw==","time":46778,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-IpadAir2-1.lYAIVQ==","time":4650,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1.PGcCxg==","time":3574,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1.kBkHjQ==","time":3609,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone6-1 ios (2 left)

2016-01-08T16:58:07.835Z - info: Received results for {"name:":"Apple-IpadAir2-1","time":61253,"result":"OK","sendList":[{"name":"Apple-Iphone5-1.vqNzbw==","time":46409,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-Iphone6-1.g6FFQA==","time":5506,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1.PGcCxg==","time":4894,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1.kBkHjQ==","time":4251,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-IpadAir2-1 ios (1 left)

2016-01-08T16:58:27.728Z - debug: Socket disconnected: ping timeout 9 (XT1072)

2016-01-08T16:58:27.794Z - debug: Socket disconnected: ping timeout 10 (Nexus 5)

2016-01-08T16:58:28.796Z - debug: Socket disconnected: ping timeout 12 (Thali Test's G2)

2016-01-08T16:58:29.045Z - debug: Socket disconnected: ping timeout 17 (HTC Desire 820)

2016-01-08T16:58:29.210Z - debug: Socket disconnected: ping timeout 18 (HTC Desire 820)

2016-01-08T16:58:34.752Z - debug: Socket disconnected: ping timeout 21 (S5mini-1)

2016-01-08T16:58:36.173Z - debug: Socket disconnected: ping timeout 22 (XT1039)

2016-01-08T16:58:37.367Z - info: Received results for {"name:":"Apple-Iphone5-1","time":57332,"result":"OK","sendList":[{"name":"Apple-IpadAir2-1.hiitZQ==","time":41211,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-Iphone6-1.g6FFQA==","time":5226,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1.lYAIVQ==","time":5391,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1.PGcCxg==","time":5201,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone5-1 ios (0 left)

2016-01-08T16:58:37.368Z - info: All test data retrieved for testSendData.js (ios)

2016-01-08T16:58:37.373Z - info: ALL DONE !!!

{ 'name:': 'Apple-IpadAir2-1',
  time: 692,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1.3GMDyQ==',
       peerAvailable: true,
       time: 690 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 643,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1.hiitZQ==',
       peerAvailable: true,
       time: 641 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 660,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1.3GMDyQ==',
       peerAvailable: true,
       time: 659 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 1723,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1.hiitZQ==',
       peerAvailable: true,
       time: 1721 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 61253,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.vqNzbw==',
       time: 46409,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1.g6FFQA==',
       time: 5506,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.PGcCxg==',
       time: 4894,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.kBkHjQ==',
       time: 4251,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 55527,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1.3GMDyQ==',
       time: 42248,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.kBkHjQ==',
       time: 4536,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.g6FFQA==',
       time: 3660,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1.lYAIVQ==',
       time: 4908,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 57332,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1.hiitZQ==',
       time: 41211,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1.g6FFQA==',
       time: 5226,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1.lYAIVQ==',
       time: 5391,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.PGcCxg==',
       time: 5201,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 59327,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.vqNzbw==',
       time: 46778,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.lYAIVQ==',
       time: 4650,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.PGcCxg==',
       time: 3574,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.kBkHjQ==',
       time: 3609,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

--------------- test report ---------------------
--------------- Apple-IpadAir2-1 --------------------- : 1

Find peers : 100% : 690 ms, 99% : 690 ms, 95 : 690 ms, 90% : 690 ms.

Result count 1, range 690 ms to  690 ms.

Send data : 100% : 5506 ms, 99% : 5506 ms, 95 : 5506 ms, 90% : 5506 ms.

Average data rate: 0.02 MB/s

Result count 3, range 4251 ms to  5506 ms.

Send data failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone5-1.vqNzbw==, Tried : 5

Send data never tried peers count : 0 [0 %]
--------------- Apple-Iphone5s-1 --------------------- : 2
Find peers : 100% : 641 ms, 99% : 641 ms, 95 : 641 ms, 90% : 641 ms.

Result count 1, range 641 ms to  641 ms.
Send data : 100% : 4908 ms, 99% : 4908 ms, 95 : 4908 ms, 90% : 4908 ms.
Average data rate: 0.023 MB/s
Result count 3, range 3660 ms to  4908 ms.

Send data failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone6-1.3GMDyQ==, Tried : 5
Send data never tried peers count : 0 [0 %]
--------------- Apple-Iphone5-1 --------------------- : 3

Find peers : 100% : 659 ms, 99% : 659 ms, 95 : 659 ms, 90% : 659 ms.
Result count 1, range 659 ms to  659 ms.
Send data : 100% : 5391 ms, 99% : 5391 ms, 95 : 5391 ms, 90% : 5391 ms.
Average data rate: 0.019 MB/s

Result count 3, range 5201 ms to  5391 ms.
Send data failed peers count : 1 [25 %]
- Peer ID : Apple-IpadAir2-1.hiitZQ==, Tried : 5
Send data never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1 --------------------- : 4

Find peers : 100% : 1721 ms, 99% : 1721 ms, 95 : 1721 ms, 90% : 1721 ms.
Result count 1, range 1721 ms to  1721 ms.
Send data : 100% : 4650 ms, 99% : 4650 ms, 95 : 4650 ms, 90% : 4650 ms.
Average data rate: 0.025 MB/s
Result count 3, range 3574 ms to  4650 ms.

Send data failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone5-1.vqNzbw==, Tried : 5
Send data never tried peers count : 0 [0 %]
--------------- Combined ---------------------

Find peers : 100% : 1721 ms, 99% : 1721 ms, 95 : 1721 ms, 90% : 1721 ms.
Send data : 100% : 5506 ms, 99% : 5506 ms, 95 : 5391 ms, 90% : 5391 ms.

Average data rate: 0.022 MB/s
--------------- end of test report ---------------------

2016-01-08T16:58:37.479Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1.3GMDyQ==, peerAvailable=true, time=690], sendList=[name=Apple-Iphone5-1.kBkHjQ==, time=4251, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5s-1.PGcCxg==, time=4894, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone6-1.g6FFQA==, time=5506, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone5-1.vqNzbw==, time=46409, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1.hiitZQ==, peerAvailable=true, time=641], sendList=[name=Apple-Iphone6-1.g6FFQA==, time=3660, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1.kBkHjQ==, time=4536, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.lYAIVQ==, time=4908, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone6-1.3GMDyQ==, time=42248, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1.3GMDyQ==, peerAvailable=true, time=659], sendList=[name=Apple-Iphone5s-1.PGcCxg==, time=5201, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone6-1.g6FFQA==, time=5226, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.lYAIVQ==, time=5391, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-IpadAir2-1.hiitZQ==, time=41211, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1.hiitZQ==, peerAvailable=true, time=1721], sendList=[name=Apple-Iphone5s-1.PGcCxg==, time=3574, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1.kBkHjQ==, time=3609, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.lYAIVQ==, time=4650, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone5-1.vqNzbw==, time=46778, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[]

2016-01-08T16:58:37.489Z - debug: end to Apple-IpadAir2-1

2016-01-08T16:58:37.491Z - debug: end to Apple-Iphone5s-1

2016-01-08T16:58:37.492Z - debug: end to Apple-Iphone5-1

2016-01-08T16:58:37.493Z - debug: end to Apple-Iphone6-1

2016-01-08T16:58:37.763Z - debug: state: android running

2016-01-08T16:58:37.766Z - debug: state: ios completed

2016-01-08T16:58:40.142Z - debug: Socket disconnected: transport close 8 (Apple-Iphone5s-1)

2016-01-08T16:58:40.247Z - debug: Socket disconnected: transport close 2 (Apple-IpadAir2-1)

2016-01-08T16:58:40.328Z - debug: Socket disconnected: transport close 20 (Apple-Iphone6-1)

2016-01-08T16:58:40.737Z - debug: Socket disconnected: transport close 15 (Apple-Iphone5-1)

2016-01-08T16:58:51.601Z - info: Received results for {"name:":"Nexus 5","time":100141,"result":"TIMEOUT","peersList":[{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":57902}]} Nexus 5 android (18 left)

2016-01-08T16:58:51.646Z - info: Received results for {"name:":"HTC One M8s","time":100202,"result":"TIMEOUT","peersList":[{"peerName":"<no peer name>","peerIdentifier":"44:80:EB:7B:5A:5","peerAvailable":false,"time":61111},{"peerName":"<no peer name>","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":false,"time":91121},{"peerName":"<no peer name>","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":false,"time":91119},{"peerName":"<no peer name>","peerIdentifier":"8:EC:A9:50:76:27","peerAvailable":false,"time":91117},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:51:18:22","peerAvailable":false,"time":91116},{"peerName":"<no peer name>","peerIdentifier":"8:EC:A9:50:75:41","peerAvailable":false,"time":91113},{"peerName":"<no peer name>","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":4041},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:37:96:AB","peerAvailable":true,"time":4141},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:34:8A:A0","peerAvailable":true,"time":4730},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":45272},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":85184},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":85689}]} HTC One M8s android (17 left)

2016-01-08T16:58:51.731Z - info: Received results for {"name:":"Note4-1","time":100278,"result":"TIMEOUT","peersList":[{"peerName":"<no peer name>","peerIdentifier":"44:80:EB:7B:5A:5","peerAvailable":false,"time":90488},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:34:8A:A0","peerAvailable":true,"time":499},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:37:96:AB","peerAvailable":true,"time":628},{"peerName":"<no peer name>","peerIdentifier":"8:EC:A9:50:75:41","peerAvailable":true,"time":726},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:51:18:22","peerAvailable":true,"time":729},{"peerName":"<no peer name>","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":1064},{"peerName":"<no peer name>","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":1201},{"peerName":"<no peer name>","peerIdentifier":"8:EC:A9:50:76:27","peerAvailable":true,"time":1307},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":12629},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":39056},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":49664},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":50683}]} Note4-1 android (16 left)

2016-01-08T16:58:51.741Z - info: Received results for {"name:":"G4-1","time":100129,"result":"TIMEOUT","peersList":[{"peerName":"<no peer name>","peerIdentifier":"44:80:EB:7B:5A:5","peerAvailable":false,"time":90204},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:37:96:AB","peerAvailable":true,"time":297},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:34:8A:A0","peerAvailable":true,"time":434},{"peerName":"<no peer name>","peerIdentifier":"8:EC:A9:50:76:27","peerAvailable":true,"time":509},{"peerName":"<no peer name>","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":754},{"peerName":"<no peer name>","peerIdentifier":"8:EC:A9:50:75:41","peerAvailable":true,"time":1230},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:51:18:22","peerAvailable":true,"time":3841},{"peerName":"<no peer name>","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":4367},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":false,"time":90196},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":32033},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":32111},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":39262},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":49352}]} G4-1 android (15 left)

2016-01-08T16:58:51.765Z - info: Received results for {"name:":"Thali Test (Galaxy A3)","time":100223,"result":"TIMEOUT","peersList":[{"peerName":"<no peer name>","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":285},{"peerName":"<no peer name>","peerIdentifier":"44:80:EB:7B:5A:5","peerAvailable":false,"time":90293},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:37:96:AB","peerAvailable":true,"time":323},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:34:8A:A0","peerAvailable":true,"time":459},{"peerName":"<no peer name>","peerIdentifier":"8:EC:A9:50:75:41","peerAvailable":true,"time":467},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:51:18:22","peerAvailable":true,"time":9868},{"peerName":"<no peer name>","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":12603},{"peerName":"<no peer name>","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":12870}]} Thali Test (Galaxy A3) android (14 left)

2016-01-08T16:58:51.774Z - info: Received results for {"name:":"A3-1","time":100219,"result":"TIMEOUT","peersList":[{"peerName":"<no peer name>","peerIdentifier":"44:80:EB:7B:5A:5","peerAvailable":false,"time":90941},{"peerName":"<no peer name>","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":1560},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":5249},{"peerName":"<no peer name>","peerIdentifier":"8:EC:A9:50:76:27","peerAvailable":true,"time":5494},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:37:96:AB","peerAvailable":true,"time":5545},{"peerName":"<no peer name>","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":5651},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:34:8A:A0","peerAvailable":true,"time":5841},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:51:18:22","peerAvailable":true,"time":11963},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":17524},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":22317},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":67385},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":67752}]} A3-1 android (13 left)

2016-01-08T16:58:51.855Z - info: Received results for {"name:":"S5-1","time":100196,"result":"TIMEOUT","peersList":[{"peerName":"<no peer name>","peerIdentifier":"44:80:EB:7B:5A:5","peerAvailable":false,"time":90237},{"peerName":"<no peer name>","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":226},{"peerName":"<no peer name>","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":541},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:37:96:AB","peerAvailable":true,"time":841},{"peerName":"<no peer name>","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":1172},{"peerName":"<no peer name>","peerIdentifier":"8:EC:A9:50:75:41","peerAvailable":true,"time":1244},{"peerName":"<no peer name>","peerIdentifier":"8:EC:A9:50:76:27","peerAvailable":true,"time":1829},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:51:18:22","peerAvailable":true,"time":5401},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":15014},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":42862},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":54992}]} S5-1 android (12 left)

2016-01-08T16:58:51.863Z - info: Received results for {"name:":"A5-1","time":100230,"result":"TIMEOUT","peersList":[{"peerName":"<no peer name>","peerIdentifier":"44:80:EB:7B:5A:5","peerAvailable":false,"time":91432},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:34:8A:A0","peerAvailable":true,"time":4050},{"peerName":"<no peer name>","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":4055},{"peerName":"<no peer name>","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":4110},{"peerName":"<no peer name>","peerIdentifier":"8:EC:A9:50:75:41","peerAvailable":true,"time":4124},{"peerName":"<no peer name>","peerIdentifier":"8:EC:A9:50:76:27","peerAvailable":true,"time":4187},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:51:18:22","peerAvailable":true,"time":4379},{"peerName":"<no peer name>","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":4388},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":10057},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":10112},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":17665},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":21591}]} A5-1 android (11 left)

2016-01-08T16:58:51.882Z - info: Received results for {"name:":"Thali Test (Galaxy A5)","time":100224,"result":"TIMEOUT","peersList":[{"peerName":"<no peer name>","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":1059},{"peerName":"<no peer name>","peerIdentifier":"44:80:EB:7B:5A:5","peerAvailable":false,"time":91059},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:37:96:AB","peerAvailable":true,"time":1116},{"peerName":"<no peer name>","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":1200},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:34:8A:A0","peerAvailable":true,"time":1218},{"peerName":"<no peer name>","peerIdentifier":"8:EC:A9:50:75:41","peerAvailable":true,"time":1244},{"peerName":"<no peer name>","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":1277},{"peerName":"<no peer name>","peerIdentifier":"8:EC:A9:50:76:27","peerAvailable":true,"time":1829},{"peerName":"HTC One M8s","peerIdentifier":"90:E7:C4:F6:69:77","peerAvailable":true,"time":91768},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":79043},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":83725}]} Thali Test (Galaxy A5) android (10 left)

2016-01-08T16:58:51.965Z - info: Received results for {"name:":"Thali Test (Galaxy S5)","time":100282,"result":"TIMEOUT","peersList":[{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:37:96:AB","peerAvailable":true,"time":316},{"peerName":"<no peer name>","peerIdentifier":"44:80:EB:7B:5A:5","peerAvailable":false,"time":90350},{"peerName":"<no peer name>","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":1298},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:51:18:22","peerAvailable":true,"time":1586},{"peerName":"<no peer name>","peerIdentifier":"8:EC:A9:50:76:27","peerAvailable":true,"time":1797},{"peerName":"<no peer name>","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":5652},{"peerName":"<no peer name>","peerIdentifier":"7C:F9:E:34:8A:A0","peerAvailable":true,"time":6359},{"peerName":"<no peer name>","peerIdentifier":"8:EC:A9:50:75:41","peerAvailable":true,"time":6455},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":61218},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":61819},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":84173}]} Thali Test (Galaxy S5) android (9 left)

2016-01-08T16:58:52.253Z - info: Received results for {"name:":"G3s-1","time":100101,"result":"TIMEOUT","peersList":[{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":76845}]} G3s-1 android (8 left)

2016-01-08T16:58:53.427Z - info: Received results for {"name:":"G3-1","time":100090,"result":"TIMEOUT","peersList":[{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":2203},{"peerName":"Nexus 5","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":true,"time":3261},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":11254},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":13915},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":13936},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":33625}]} G3-1 android (7 left)

2016-01-08T16:59:00.227Z - info: Start timeout elapsed for platform: android

2016-01-08T16:59:00.232Z - info: Tests for android already running or completed

2016-01-08T16:59:11.190Z - info: server timeout for test: testFindPeers.js (android)

2016-01-08T16:59:11.193Z - info: All test data retrieved for testFindPeers.js (android)

2016-01-08T16:59:11.202Z - info: No results from XT1072

2016-01-08T16:59:11.208Z - info: No results from Nexus 5

2016-01-08T16:59:11.211Z - info: No results from Thali Test's G2

2016-01-08T16:59:11.217Z - info: No results from HTC Desire 820

2016-01-08T16:59:11.219Z - info: No results from HTC Desire 820

2016-01-08T16:59:11.223Z - info: No results from S5mini-1

2016-01-08T16:59:11.225Z - info: No results from XT1039

2016-01-08T16:59:11.227Z - info: Remaining tests: testSendData.js

2016-01-08T16:59:11.229Z - info: Continuing to next test: testSendData.js

2016-01-08T16:59:11.230Z - info: Starting test: with 19 devices (android)

2016-01-08T17:00:51.618Z - info: Received results for {"name:":"Nexus 5","time":100052,"result":"TIMEOUT","sendList":[{"name":"F8:95:C7:87:3C:51","time":34486,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:B1:66","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:9D:93:0B","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"B4:CE:F6:AB:A4:6A","time":0,"result":"Fail"},{"connections":0,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"80:01:84:8A:B3:68","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"}]} Nexus 5 android (18 left)

2016-01-08T17:00:51.653Z - info: Received results for {"name:":"S5-1","time":100154,"result":"TIMEOUT","sendList":[{"name":"08:EC:A9:50:76:27","time":8206,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":8788,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:9D:93:0B","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:B1:66","time":0,"result":"Fail"},{"connections":0,"name":"B4:CE:F6:AB:A4:6A","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"80:01:84:8A:B3:68","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":1,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"}]} S5-1 android (17 left)

2016-01-08T17:00:51.699Z - info: Received results for {"name:":"A3-1","time":100242,"result":"TIMEOUT","sendList":[{"name":"F8:95:C7:87:3C:51","time":23366,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:9D:93:0B","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:B1:66","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"B4:CE:F6:AB:A4:6A","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"80:01:84:8A:B3:68","time":0,"result":"Fail"}]} A3-1 android (16 left)

2016-01-08T17:00:51.707Z - info: Received results for {"name:":"Thali Test (Galaxy S5)","time":100137,"result":"TIMEOUT","sendList":[{"name":"58:3F:54:73:64:C0","time":12842,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:37:96:AB","time":33565,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"80:01:84:8A:B3:68","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:B1:66","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"B4:CE:F6:AB:A4:6A","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:9D:93:0B","time":0,"result":"Fail"}]} Thali Test (Galaxy S5) android (15 left)

2016-01-08T17:00:51.805Z - info: Received results for {"name:":"A5-1","time":100234,"result":"TIMEOUT","sendList":[{"name":"58:3F:54:73:64:C0","time":10423,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"34:FC:EF:11:AE:67","time":11843,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"B4:CE:F6:AB:A4:6A","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:B1:66","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:9D:93:0B","time":0,"result":"Fail"},{"connections":1,"name":"80:01:84:8A:B3:68","time":0,"result":"Fail"}]} A5-1 android (14 left)

2016-01-08T17:00:51.906Z - info: Received results for {"name:":"G3s-1","time":100249,"result":"TIMEOUT","sendList":[{"name":"E0:DB:10:14:E2:C0","time":15908,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"34:FC:EF:11:AE:67","time":9702,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"90:E7:C4:F6:69:77","time":12431,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"34:FC:EF:11:B1:66","time":0,"result":"Fail"},{"connections":0,"name":"80:01:84:8A:B3:68","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"B4:CE:F6:AB:A4:6A","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:9D:93:0B","time":0,"result":"Fail"}]} G3s-1 android (13 left)

2016-01-08T17:00:52.254Z - info: Received results for {"name:":"Note4-1","time":100250,"result":"TIMEOUT","sendList":[{"name":"08:EC:A9:50:75:41","time":32992,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:B1:66","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"80:01:84:8A:B3:68","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:9D:93:0B","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"B4:CE:F6:AB:A4:6A","time":0,"result":"Fail"},{"connections":0,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"}]} Note4-1 android (12 left)

2016-01-08T17:00:52.295Z - info: Received results for {"name:":"Thali Test (Galaxy A5)","time":100241,"result":"TIMEOUT","sendList":[{"connections":1,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:B1:66","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:9D:93:0B","time":0,"result":"Fail"},{"connections":0,"name":"B4:CE:F6:AB:A4:6A","time":0,"result":"Fail"},{"connections":0,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"},{"connections":0,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"80:01:84:8A:B3:68","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"}]} Thali Test (Galaxy A5) android (11 left)

2016-01-08T17:00:52.510Z - info: Received results for {"name:":"G3-1","time":100115,"result":"TIMEOUT","sendList":[{"name":"7C:F9:0E:34:8A:A0","time":8810,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"34:FC:EF:9D:93:0B","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:B1:66","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"80:01:84:8A:B3:68","time":0,"result":"Fail"},{"connections":1,"name":"B4:CE:F6:AB:A4:6A","time":0,"result":"Fail"}]} G3-1 android (10 left)

2016-01-08T17:00:52.582Z - info: Received results for {"name:":"G4-1","time":100110,"result":"TIMEOUT","sendList":[{"name":"34:FC:EF:11:AE:67","time":70552,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"34:FC:EF:11:B1:66","time":0,"result":"Fail"},{"connections":0,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:9D:93:0B","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"80:01:84:8A:B3:68","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"B4:CE:F6:AB:A4:6A","time":0,"result":"Fail"},{"connections":0,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"}]} G4-1 android (9 left)

2016-01-08T17:00:53.430Z - info: Received results for {"name:":"Thali Test (Galaxy A3)","time":100209,"result":"TIMEOUT","sendList":[{"connections":1,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"80:01:84:8A:B3:68","time":0,"result":"Fail"},{"connections":0,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:B1:66","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"B4:CE:F6:AB:A4:6A","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:9D:93:0B","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"}]} Thali Test (Galaxy A3) android (8 left)

2016-01-08T17:01:11.232Z - info: server timeout for test: testSendData.js (android)

2016-01-08T17:01:11.233Z - info: All test data retrieved for testSendData.js (android)

2016-01-08T17:01:11.236Z - info: No results from HTC One M8s

2016-01-08T17:01:11.242Z - info: No results from XT1072

2016-01-08T17:01:11.243Z - info: No results from Nexus 5

2016-01-08T17:01:11.249Z - info: No results from Thali Test's G2

2016-01-08T17:01:11.256Z - info: No results from HTC Desire 820

2016-01-08T17:01:11.256Z - info: No results from HTC Desire 820

2016-01-08T17:01:11.259Z - info: No results from S5mini-1

2016-01-08T17:01:11.260Z - info: No results from XT1039

2016-01-08T17:01:11.261Z - info: ALL DONE !!!

{ 'name:': 'Apple-IpadAir2-1',
  time: 692,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1.3GMDyQ==',
       peerAvailable: true,
       time: 690 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 643,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1.hiitZQ==',
       peerAvailable: true,
       time: 641 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 660,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1.3GMDyQ==',
       peerAvailable: true,
       time: 659 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 1723,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1.hiitZQ==',
       peerAvailable: true,
       time: 1721 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 61253,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.vqNzbw==',
       time: 46409,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1.g6FFQA==',
       time: 5506,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.PGcCxg==',
       time: 4894,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.kBkHjQ==',
       time: 4251,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 55527,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1.3GMDyQ==',
       time: 42248,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.kBkHjQ==',
       time: 4536,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.g6FFQA==',
       time: 3660,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1.lYAIVQ==',
       time: 4908,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 57332,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1.hiitZQ==',
       time: 41211,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1.g6FFQA==',
       time: 5226,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1.lYAIVQ==',
       time: 5391,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.PGcCxg==',
       time: 5201,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 59327,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.vqNzbw==',
       time: 46778,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.lYAIVQ==',
       time: 4650,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.PGcCxg==',
       time: 3574,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.kBkHjQ==',
       time: 3609,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Nexus 5',
  time: 100141,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 57902 } ] }

{ 'name:': 'HTC One M8s',
  time: 100202,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: '<no peer name>',
       peerIdentifier: '44:80:EB:7B:5A:5',
       peerAvailable: false,
       time: 61111 },
     { peerName: '<no peer name>',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: false,
       time: 91121 },
     { peerName: '<no peer name>',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: false,
       time: 91119 },
     { peerName: '<no peer name>',
       peerIdentifier: '8:EC:A9:50:76:27',
       peerAvailable: false,
       time: 91117 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:51:18:22',
       peerAvailable: false,
       time: 91116 },
     { peerName: '<no peer name>',
       peerIdentifier: '8:EC:A9:50:75:41',
       peerAvailable: false,
       time: 91113 },
     { peerName: '<no peer name>',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 4041 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:37:96:AB',
       peerAvailable: true,
       time: 4141 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:34:8A:A0',
       peerAvailable: true,
       time: 4730 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 45272 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 85184 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 85689 } ] }

{ 'name:': 'A5-1',
  time: 100230,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: '<no peer name>',
       peerIdentifier: '44:80:EB:7B:5A:5',
       peerAvailable: false,
       time: 91432 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:34:8A:A0',
       peerAvailable: true,
       time: 4050 },
     { peerName: '<no peer name>',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 4055 },
     { peerName: '<no peer name>',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 4110 },
     { peerName: '<no peer name>',
       peerIdentifier: '8:EC:A9:50:75:41',
       peerAvailable: true,
       time: 4124 },
     { peerName: '<no peer name>',
       peerIdentifier: '8:EC:A9:50:76:27',
       peerAvailable: true,
       time: 4187 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:51:18:22',
       peerAvailable: true,
       time: 4379 },
     { peerName: '<no peer name>',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 4388 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 10057 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 10112 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 17665 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 21591 } ] }

{ 'name:': 'G4-1',
  time: 100129,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: '<no peer name>',
       peerIdentifier: '44:80:EB:7B:5A:5',
       peerAvailable: false,
       time: 90204 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:37:96:AB',
       peerAvailable: true,
       time: 297 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:34:8A:A0',
       peerAvailable: true,
       time: 434 },
     { peerName: '<no peer name>',
       peerIdentifier: '8:EC:A9:50:76:27',
       peerAvailable: true,
       time: 509 },
     { peerName: '<no peer name>',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 754 },
     { peerName: '<no peer name>',
       peerIdentifier: '8:EC:A9:50:75:41',
       peerAvailable: true,
       time: 1230 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:51:18:22',
       peerAvailable: true,
       time: 3841 },
     { peerName: '<no peer name>',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 4367 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: false,
       time: 90196 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 32033 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 32111 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 39262 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 49352 } ] }

{ 'name:': 'Note4-1',
  time: 100278,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: '<no peer name>',
       peerIdentifier: '44:80:EB:7B:5A:5',
       peerAvailable: false,
       time: 90488 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:34:8A:A0',
       peerAvailable: true,
       time: 499 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:37:96:AB',
       peerAvailable: true,
       time: 628 },
     { peerName: '<no peer name>',
       peerIdentifier: '8:EC:A9:50:75:41',
       peerAvailable: true,
       time: 726 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:51:18:22',
       peerAvailable: true,
       time: 729 },
     { peerName: '<no peer name>',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 1064 },
     { peerName: '<no peer name>',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 1201 },
     { peerName: '<no peer name>',
       peerIdentifier: '8:EC:A9:50:76:27',
       peerAvailable: true,
       time: 1307 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 12629 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 39056 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 49664 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 50683 } ] }

{ 'name:': 'Thali Test (Galaxy S5)',
  time: 100282,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:37:96:AB',
       peerAvailable: true,
       time: 316 },
     { peerName: '<no peer name>',
       peerIdentifier: '44:80:EB:7B:5A:5',
       peerAvailable: false,
       time: 90350 },
     { peerName: '<no peer name>',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 1298 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:51:18:22',
       peerAvailable: true,
       time: 1586 },
     { peerName: '<no peer name>',
       peerIdentifier: '8:EC:A9:50:76:27',
       peerAvailable: true,
       time: 1797 },
     { peerName: '<no peer name>',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 5652 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:34:8A:A0',
       peerAvailable: true,
       time: 6359 },
     { peerName: '<no peer name>',
       peerIdentifier: '8:EC:A9:50:75:41',
       peerAvailable: true,
       time: 6455 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 61218 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 61819 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 84173 } ] }

{ 'name:': 'G3-1',
  time: 100090,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 2203 },
     { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 3261 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 11254 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 13915 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 13936 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 33625 } ] }

{ 'name:': 'G3s-1',
  time: 100101,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 76845 } ] }

{ 'name:': 'Thali Test (Galaxy A5)',
  time: 100224,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: '<no peer name>',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 1059 },
     { peerName: '<no peer name>',
       peerIdentifier: '44:80:EB:7B:5A:5',
       peerAvailable: false,
       time: 91059 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:37:96:AB',
       peerAvailable: true,
       time: 1116 },
     { peerName: '<no peer name>',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 1200 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:34:8A:A0',
       peerAvailable: true,
       time: 1218 },
     { peerName: '<no peer name>',
       peerIdentifier: '8:EC:A9:50:75:41',
       peerAvailable: true,
       time: 1244 },
     { peerName: '<no peer name>',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 1277 },
     { peerName: '<no peer name>',
       peerIdentifier: '8:EC:A9:50:76:27',
       peerAvailable: true,
       time: 1829 },
     { peerName: 'HTC One M8s',
       peerIdentifier: '90:E7:C4:F6:69:77',
       peerAvailable: true,
       time: 91768 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 79043 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 83725 } ] }

{ 'name:': 'S5-1',
  time: 100196,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: '<no peer name>',
       peerIdentifier: '44:80:EB:7B:5A:5',
       peerAvailable: false,
       time: 90237 },
     { peerName: '<no peer name>',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 226 },
     { peerName: '<no peer name>',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 541 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:37:96:AB',
       peerAvailable: true,
       time: 841 },
     { peerName: '<no peer name>',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 1172 },
     { peerName: '<no peer name>',
       peerIdentifier: '8:EC:A9:50:75:41',
       peerAvailable: true,
       time: 1244 },
     { peerName: '<no peer name>',
       peerIdentifier: '8:EC:A9:50:76:27',
       peerAvailable: true,
       time: 1829 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:51:18:22',
       peerAvailable: true,
       time: 5401 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 15014 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 42862 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 54992 } ] }

{ 'name:': 'A3-1',
  time: 100219,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: '<no peer name>',
       peerIdentifier: '44:80:EB:7B:5A:5',
       peerAvailable: false,
       time: 90941 },
     { peerName: '<no peer name>',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 1560 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 5249 },
     { peerName: '<no peer name>',
       peerIdentifier: '8:EC:A9:50:76:27',
       peerAvailable: true,
       time: 5494 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:37:96:AB',
       peerAvailable: true,
       time: 5545 },
     { peerName: '<no peer name>',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 5651 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:34:8A:A0',
       peerAvailable: true,
       time: 5841 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:51:18:22',
       peerAvailable: true,
       time: 11963 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 17524 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 22317 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 67385 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 67752 } ] }

{ 'name:': 'Thali Test (Galaxy A3)',
  time: 100223,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: '<no peer name>',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 285 },
     { peerName: '<no peer name>',
       peerIdentifier: '44:80:EB:7B:5A:5',
       peerAvailable: false,
       time: 90293 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:37:96:AB',
       peerAvailable: true,
       time: 323 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:34:8A:A0',
       peerAvailable: true,
       time: 459 },
     { peerName: '<no peer name>',
       peerIdentifier: '8:EC:A9:50:75:41',
       peerAvailable: true,
       time: 467 },
     { peerName: '<no peer name>',
       peerIdentifier: '7C:F9:E:51:18:22',
       peerAvailable: true,
       time: 9868 },
     { peerName: '<no peer name>',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 12603 },
     { peerName: '<no peer name>',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 12870 } ] }

{ 'name:': 'Nexus 5',
  time: 100052,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'F8:95:C7:87:3C:51',
       time: 34486,
       result: 'OK',
       connections: 1,
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
       name: 'B0:C5:59:3F:75:69',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:11:B1:66',
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
       name: '7C:F9:0E:51:18:22',
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
       name: '7C:F9:0E:37:96:AB',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'B4:CE:F6:AB:A4:6A',
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
       name: '80:01:84:8A:B3:68',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '44:80:EB:7B:5A:05',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:34:8A:A0',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'A5-1',
  time: 100234,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '58:3F:54:73:64:C0',
       time: 10423,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '34:FC:EF:11:AE:67',
       time: 11843,
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
       name: '00:F4:6F:30:E0:6C',
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
       name: '7C:F9:0E:34:8A:A0',
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
       name: '7C:F9:0E:51:18:22',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'B4:CE:F6:AB:A4:6A',
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
       name: '90:E7:C4:F6:69:77',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '44:80:EB:7B:5A:05',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:9D:93:0B',
       time: 0,
       result: 'Fail' },
     { connections: 1,
       name: '80:01:84:8A:B3:68',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'G4-1',
  time: 100110,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '34:FC:EF:11:AE:67',
       time: 70552,
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
       name: '90:E7:C4:F6:69:77',
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
       name: 'E0:DB:10:14:E2:C0',
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
       name: '7C:F9:0E:51:18:22',
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
       name: '08:EC:A9:50:76:27',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '00:F4:6F:30:E0:6C',
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
       name: '7C:F9:0E:37:96:AB',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '44:80:EB:7B:5A:05',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Note4-1',
  time: 100250,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '08:EC:A9:50:75:41',
       time: 32992,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
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
       name: '34:FC:EF:11:AE:67',
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
       name: '34:FC:EF:9D:93:0B',
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
       name: '7C:F9:0E:34:8A:A0',
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
       name: 'B4:CE:F6:AB:A4:6A',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '90:E7:C4:F6:69:77',
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
       name: '00:F4:6F:30:E0:6C',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Thali Test (Galaxy S5)',
  time: 100137,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '58:3F:54:73:64:C0',
       time: 12842,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:37:96:AB',
       time: 33565,
       result: 'OK',
       connections: 2,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: '80:01:84:8A:B3:68',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:11:B1:66',
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
       name: '44:80:EB:7B:5A:05',
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
       name: '00:F4:6F:30:E0:6C',
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
       name: 'F4:F1:E1:5C:3B:E2',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:76:27',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:11:AE:67',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '90:E7:C4:F6:69:77',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'B4:CE:F6:AB:A4:6A',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:9D:93:0B',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'G3-1',
  time: 100115,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '7C:F9:0E:34:8A:A0',
       time: 8810,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: '34:FC:EF:9D:93:0B',
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
       name: '08:EC:A9:50:75:41',
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
       name: 'B0:C5:59:3F:75:69',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:76:27',
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
       name: '90:E7:C4:F6:69:77',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '80:01:84:8A:B3:68',
       time: 0,
       result: 'Fail' },
     { connections: 1,
       name: 'B4:CE:F6:AB:A4:6A',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'G3s-1',
  time: 100249,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'E0:DB:10:14:E2:C0',
       time: 15908,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '34:FC:EF:11:AE:67',
       time: 9702,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '90:E7:C4:F6:69:77',
       time: 12431,
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
       name: '80:01:84:8A:B3:68',
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
       name: '7C:F9:0E:37:96:AB',
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
       name: '7C:F9:0E:34:8A:A0',
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
       name: '34:FC:EF:9D:93:0B',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Thali Test (Galaxy A5)',
  time: 100241,
  result: 'TIMEOUT',
  sendList: 
   [ { connections: 1,
       name: '08:EC:A9:50:76:27',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '00:F4:6F:30:E0:6C',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F8:95:C7:87:85:54',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:11:AE:67',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:11:B1:66',
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
       name: 'F4:F1:E1:5C:3B:E2',
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
       name: '08:EC:A9:50:75:41',
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
       name: 'F8:95:C7:87:3C:51',
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
       name: 'E0:DB:10:14:E2:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '58:3F:54:73:64:C0',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'S5-1',
  time: 100154,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '08:EC:A9:50:76:27',
       time: 8206,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'E0:DB:10:14:E2:C0',
       time: 8788,
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
       name: 'F8:95:C7:87:3C:51',
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
       name: '7C:F9:0E:37:96:AB',
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
     { connections: 0,
       name: 'B4:CE:F6:AB:A4:6A',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:75:41',
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
       name: '44:80:EB:7B:5A:05',
       time: 0,
       result: 'Fail' },
     { connections: 1,
       name: 'F4:F1:E1:5C:3B:E2',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'A3-1',
  time: 100242,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'F8:95:C7:87:3C:51',
       time: 23366,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: '44:80:EB:7B:5A:05',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:37:96:AB',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:9D:93:0B',
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
       name: '34:FC:EF:11:AE:67',
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
       name: '34:FC:EF:11:B1:66',
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
       name: 'B4:CE:F6:AB:A4:6A',
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
       result: 'Fail' },
     { connections: 0,
       name: '90:E7:C4:F6:69:77',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '80:01:84:8A:B3:68',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Thali Test (Galaxy A3)',
  time: 100209,
  result: 'TIMEOUT',
  sendList: 
   [ { connections: 1,
       name: '44:80:EB:7B:5A:05',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'B0:C5:59:3F:75:69',
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
       name: '08:EC:A9:50:75:41',
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
       name: '7C:F9:0E:34:8A:A0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F8:95:C7:87:3C:51',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:9D:93:0B',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:11:AE:67',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '58:3F:54:73:64:C0',
       time: 0,
       result: 'Fail' } ] }

--------------- test report ---------------------
--------------- Apple-IpadAir2-1 --------------------- : 1
Find peers : 100% : 690 ms, 99% : 690 ms, 95 : 690 ms, 90% : 690 ms.
Result count 1, range 690 ms to  690 ms.

Send data : 100% : 5506 ms, 99% : 5506 ms, 95 : 5506 ms, 90% : 5506 ms.
Average data rate: 0.02 MB/s
Result count 3, range 4251 ms to  5506 ms.
Send data failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone5-1.vqNzbw==, Tried : 5
Send data never tried peers count : 0 [0 %]
--------------- Apple-Iphone5s-1 --------------------- : 2
Find peers : 100% : 641 ms, 99% : 641 ms, 95 : 641 ms, 90% : 641 ms.
Result count 1, range 641 ms to  641 ms.
Send data : 100% : 4908 ms, 99% : 4908 ms, 95 : 4908 ms, 90% : 4908 ms.
Average data rate: 0.023 MB/s
Result count 3, range 3660 ms to  4908 ms.
Send data failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone6-1.3GMDyQ==, Tried : 5
Send data never tried peers count : 0 [0 %]
--------------- Apple-Iphone5-1 --------------------- : 3
Find peers : 100% : 659 ms, 99% : 659 ms, 95 : 659 ms, 90% : 659 ms.
Result count 1, range 659 ms to  659 ms.
Send data : 100% : 5391 ms, 99% : 5391 ms, 95 : 5391 ms, 90% : 5391 ms.
Average data rate: 0.019 MB/s

Result count 3, range 5201 ms to  5391 ms.
Send data failed peers count : 1 [25 %]
- Peer ID : Apple-IpadAir2-1.hiitZQ==, Tried : 5
Send data never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1 --------------------- : 4

Find peers : 100% : 1721 ms, 99% : 1721 ms, 95 : 1721 ms, 90% : 1721 ms.
Result count 1, range 1721 ms to  1721 ms.
Send data : 100% : 4650 ms, 99% : 4650 ms, 95 : 4650 ms, 90% : 4650 ms.

Average data rate: 0.025 MB/s
Result count 3, range 3574 ms to  4650 ms.
Send data failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone5-1.vqNzbw==, Tried : 5

Send data never tried peers count : 0 [0 %]
--------------- Nexus 5 --------------------- : 5
Find peers : 100% : 57902 ms, 99% : 57902 ms, 95 : 57902 ms, 90% : 57902 ms.
Result count 1, range 57902 ms to  57902 ms.

Send data : 100% : 34486 ms, 99% : 34486 ms, 95 : 34486 ms, 90% : 34486 ms.
Average data rate: 0.003 MB/s

Result count 1, range 34486 ms to  34486 ms.
Send data failed peers count : 1 [50 %]
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
Send data never tried peers count : 16 [88.88888888888889 %]

- Peer ID : 08:EC:A9:50:76:27

- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : E0:DB:10:14:E2:C0

- Peer ID : 34:FC:EF:9D:93:0B

- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 90:E7:C4:F6:69:77
- Peer ID : F8:95:C7:87:85:54
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 7C:F9:0E:34:8A:A0
--------------- HTC One M8s --------------------- : 6

Find peers : 100% : 91121 ms, 99% : 91121 ms, 95 : 91119 ms, 90% : 91119 ms.

Result count 12, range 4041 ms to  91121 ms.
--------------- A5-1 --------------------- : 7
Find peers : 100% : 91432 ms, 99% : 91432 ms, 95 : 21591 ms, 90% : 21591 ms.

Result count 12, range 4050 ms to  91432 ms.
Send data : 100% : 11843 ms, 99% : 11843 ms, 95 : 11843 ms, 90% : 11843 ms.
Average data rate: 0.009 MB/s

Result count 2, range 10423 ms to  11843 ms.
Send data failed peers count : 2 [50 %]
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 80:01:84:8A:B3:68, Tried : 1

Send data never tried peers count : 14 [77.77777777777777 %]
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 7C:F9:0E:34:8A:A0

- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 7C:F9:0E:51:18:22

- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : F8:95:C7:87:85:54
- Peer ID : 90:E7:C4:F6:69:77
- Peer ID : 44:80:EB:7B:5A:05

- Peer ID : 34:FC:EF:9D:93:0B
--------------- G4-1 --------------------- : 8
Find peers : 100% : 90204 ms, 99% : 90204 ms, 95 : 90196 ms, 90% : 90196 ms.

Result count 13, range 297 ms to  90204 ms.
Send data : 100% : 70552 ms, 99% : 70552 ms, 95 : 70552 ms, 90% : 70552 ms.
Average data rate: 0.001 MB/s
Result count 1, range 70552 ms to  70552 ms.

Send data failed peers count : 1 [50 %]
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
Send data never tried peers count : 16 [88.88888888888889 %]
- Peer ID : 90:E7:C4:F6:69:77

- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : E0:DB:10:14:E2:C0

- Peer ID : F8:95:C7:87:85:54
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 08:EC:A9:50:75:41

- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : F4:F1:E1:5C:3B:E2

- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 44:80:EB:7B:5A:05
--------------- Note4-1 --------------------- : 9

Find peers : 100% : 90488 ms, 99% : 90488 ms, 95 : 50683 ms, 90% : 50683 ms.
Result count 12, range 499 ms to  90488 ms.
Send data : 100% : 32992 ms, 99% : 32992 ms, 95 : 32992 ms, 90% : 32992 ms.
Average data rate: 0.003 MB/s

Result count 1, range 32992 ms to  32992 ms.
Send data failed peers count : 1 [50 %]
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
Send data never tried peers count : 16 [88.88888888888889 %]

- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 80:01:84:8A:B3:68

- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 7C:F9:0E:34:8A:A0

- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 90:E7:C4:F6:69:77

- Peer ID : F8:95:C7:87:3C:51
- Peer ID : F8:95:C7:87:85:54
- Peer ID : 00:F4:6F:30:E0:6C
--------------- Thali Test (Galaxy S5) --------------------- : 10

Find peers : 100% : 90350 ms, 99% : 90350 ms, 95 : 84173 ms, 90% : 84173 ms.
Result count 11, range 316 ms to  90350 ms.
Send data : 100% : 33565 ms, 99% : 33565 ms, 95 : 33565 ms, 90% : 33565 ms.
Average data rate: 0.004 MB/s

Result count 2, range 12842 ms to  33565 ms.
Send data failed peers count : 1 [33.333333333333336 %]
- Peer ID : 80:01:84:8A:B3:68, Tried : 1

Send data never tried peers count : 15 [83.33333333333333 %]
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : F8:95:C7:87:85:54

- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : F8:95:C7:87:3C:51

- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : 7C:F9:0E:51:18:22

- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 34:FC:EF:11:AE:67

- Peer ID : 90:E7:C4:F6:69:77
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 34:FC:EF:9D:93:0B

--------------- G3-1 --------------------- : 11

Find peers : 100% : 33625 ms, 99% : 33625 ms, 95 : 33625 ms, 90% : 13936 ms.
Result count 6, range 2203 ms to  33625 ms.
Send data : 100% : 8810 ms, 99% : 8810 ms, 95 : 8810 ms, 90% : 8810 ms.

Average data rate: 0.011 MB/s
Result count 1, range 8810 ms to  8810 ms.

Send data failed peers count : 2 [66.66666666666667 %]
- Peer ID : 34:FC:EF:9D:93:0B, Tried : 1

- Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
Send data never tried peers count : 15 [83.33333333333333 %]
- Peer ID : 00:F4:6F:30:E0:6C

- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 44:80:EB:7B:5A:05

- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : 08:EC:A9:50:75:41

- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : F8:95:C7:87:85:54

- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 34:FC:EF:11:AE:67

- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 90:E7:C4:F6:69:77
- Peer ID : 80:01:84:8A:B3:68

--------------- G3s-1 --------------------- : 12
Find peers : 100% : 76845 ms, 99% : 76845 ms, 95 : 76845 ms, 90% : 76845 ms.

Result count 1, range 76845 ms to  76845 ms.
Send data : 100% : 15908 ms, 99% : 15908 ms, 95 : 15908 ms, 90% : 15908 ms.

Average data rate: 0.008 MB/s
Result count 3, range 9702 ms to  15908 ms.

Send data failed peers count : 1 [25 %]
- Peer ID : 34:FC:EF:11:B1:66, Tried : 1
Send data never tried peers count : 14 [77.77777777777777 %]

- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : 00:F4:6F:30:E0:6C

- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : B0:C5:59:3F:75:69

- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 34:FC:EF:9D:93:0B
--------------- Thali Test (Galaxy A5) --------------------- : 13
Find peers : 100% : 91768 ms, 99% : 91768 ms, 95 : 91059 ms, 90% : 91059 ms.
Result count 11, range 1059 ms to  91768 ms.

No send data results!
--------------- S5-1 --------------------- : 14
Find peers : 100% : 90237 ms, 99% : 90237 ms, 95 : 54992 ms, 90% : 54992 ms.
Result count 11, range 226 ms to  90237 ms.

Send data : 100% : 8788 ms, 99% : 8788 ms, 95 : 8788 ms, 90% : 8788 ms.
Average data rate: 0.012 MB/s

Result count 2, range 8206 ms to  8788 ms.
Send data failed peers count : 2 [50 %]

- Peer ID : 58:3F:54:73:64:C0, Tried : 1
- Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
Send data never tried peers count : 14 [77.77777777777777 %]

- Peer ID : 90:E7:C4:F6:69:77
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : F8:95:C7:87:85:54

- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : 7C:F9:0E:51:18:22

- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : B0:C5:59:3F:75:69

- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : B4:CE:F6:AB:A4:6A

- Peer ID : 08:EC:A9:50:75:41
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 80:01:84:8A:B3:68
- Peer ID : 44:80:EB:7B:5A:05

--------------- A3-1 --------------------- : 15
Find peers : 100% : 90941 ms, 99% : 90941 ms, 95 : 67752 ms, 90% : 67752 ms.

Result count 12, range 1560 ms to  90941 ms.
Send data : 100% : 23366 ms, 99% : 23366 ms, 95 : 23366 ms, 90% : 23366 ms.

Average data rate: 0.004 MB/s
Result count 1, range 23366 ms to  23366 ms.

Send data failed peers count : 1 [50 %]
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
Send data never tried peers count : 16 [88.88888888888889 %]

- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 34:FC:EF:9D:93:0B
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : F8:95:C7:87:85:54
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : F4:F1:E1:5C:3B:E2
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 34:FC:EF:11:B1:66
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : B4:CE:F6:AB:A4:6A
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 90:E7:C4:F6:69:77
- Peer ID : 80:01:84:8A:B3:68
--------------- Thali Test (Galaxy A3) --------------------- : 16
Find peers : 100% : 90293 ms, 99% : 90293 ms, 95 : 90293 ms, 90% : 12870 ms.
Result count 8, range 285 ms to  90293 ms.
No send data results!
--------------- Combined ---------------------
Find peers : 100% : 91768 ms, 99% : 91432 ms, 95 : 91113 ms, 90% : 90293 ms.
Send data : 100% : 70552 ms, 99% : 70552 ms, 95 : 34486 ms, 90% : 32992 ms.
Average data rate: 0.007 MB/s
--------------- end of test report ---------------------

2016-01-08T17:01:11.836Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1.3GMDyQ==, peerAvailable=true, time=690], sendList=[name=Apple-Iphone5-1.kBkHjQ==, time=4251, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5s-1.PGcCxg==, time=4894, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone6-1.g6FFQA==, time=5506, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone5-1.vqNzbw==, time=46409, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1.hiitZQ==, peerAvailable=true, time=641], sendList=[name=Apple-Iphone6-1.g6FFQA==, time=3660, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1.kBkHjQ==, time=4536, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.lYAIVQ==, time=4908, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone6-1.3GMDyQ==, time=42248, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1.3GMDyQ==, peerAvailable=true, time=659], sendList=[name=Apple-Iphone5s-1.PGcCxg==, time=5201, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone6-1.g6FFQA==, time=5226, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.lYAIVQ==, time=5391, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-IpadAir2-1.hiitZQ==, time=41211, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1.hiitZQ==, peerAvailable=true, time=1721], sendList=[name=Apple-Iphone5s-1.PGcCxg==, time=3574, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1.kBkHjQ==, time=3609, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.lYAIVQ==, time=4650, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone5-1.vqNzbw==, time=46778, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=57902], sendList=[name=F8:95:C7:87:3C:51, time=34486, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail], notTriedList=[connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=34:FC:EF:11:B1:66, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=34:FC:EF:9D:93:0B, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=B4:CE:F6:AB:A4:6A, time=0, result=Fail, connections=0, name=90:E7:C4:F6:69:77, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=80:01:84:8A:B3:68, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail], peersList=[peerName=<no peer name>, peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=4041, peerName=<no peer name>, peerIdentifier=7C:F9:E:37:96:AB, peerAvailable=true, time=4141, peerName=<no peer name>, peerIdentifier=7C:F9:E:34:8A:A0, peerAvailable=true, time=4730, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=45272, peerName=<no peer name>, peerIdentifier=44:80:EB:7B:5A:5, peerAvailable=false, time=61111, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=85184, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=85689, peerName=<no peer name>, peerIdentifier=8:EC:A9:50:75:41, peerAvailable=false, time=91113, peerName=<no peer name>, peerIdentifier=7C:F9:E:51:18:22, peerAvailable=false, time=91116, peerName=<no peer name>, peerIdentifier=8:EC:A9:50:76:27, peerAvailable=false, time=91117, peerName=<no peer name>, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=false, time=91119, peerName=<no peer name>, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=false, time=91121], peersList=[peerName=<no peer name>, peerIdentifier=7C:F9:E:34:8A:A0, peerAvailable=true, time=4050, peerName=<no peer name>, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=4055, peerName=<no peer name>, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=4110, peerName=<no peer name>, peerIdentifier=8:EC:A9:50:75:41, peerAvailable=true, time=4124, peerName=<no peer name>, peerIdentifier=8:EC:A9:50:76:27, peerAvailable=true, time=4187, peerName=<no peer name>, peerIdentifier=7C:F9:E:51:18:22, peerAvailable=true, time=4379, peerName=<no peer name>, peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=4388, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=10057, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=10112, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=17665, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=21591, peerName=<no peer name>, peerIdentifier=44:80:EB:7B:5A:5, peerAvailable=false, time=91432], sendList=[name=58:3F:54:73:64:C0, time=10423, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=34:FC:EF:11:AE:67, time=11843, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=1, name=80:01:84:8A:B3:68, time=0, result=Fail], notTriedList=[connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=B4:CE:F6:AB:A4:6A, time=0, result=Fail, connections=0, name=34:FC:EF:11:B1:66, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=90:E7:C4:F6:69:77, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=34:FC:EF:9D:93:0B, time=0, result=Fail], peersList=[peerName=<no peer name>, peerIdentifier=7C:F9:E:37:96:AB, peerAvailable=true, time=297, peerName=<no peer name>, peerIdentifier=7C:F9:E:34:8A:A0, peerAvailable=true, time=434, peerName=<no peer name>, peerIdentifier=8:EC:A9:50:76:27, peerAvailable=true, time=509, peerName=<no peer name>, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=754, peerName=<no peer name>, peerIdentifier=8:EC:A9:50:75:41, peerAvailable=true, time=1230, peerName=<no peer name>, peerIdentifier=7C:F9:E:51:18:22, peerAvailable=true, time=3841, peerName=<no peer name>, peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=4367, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=32033, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=32111, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=39262, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=49352, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=false, time=90196, peerName=<no peer name>, peerIdentifier=44:80:EB:7B:5A:5, peerAvailable=false, time=90204], sendList=[name=34:FC:EF:11:AE:67, time=70552, result=OK, connections=2, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=34:FC:EF:11:B1:66, time=0, result=Fail], notTriedList=[connections=0, name=90:E7:C4:F6:69:77, time=0, result=Fail, connections=0, name=34:FC:EF:9D:93:0B, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=80:01:84:8A:B3:68, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=B4:CE:F6:AB:A4:6A, time=0, result=Fail, connections=0, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail], peersList=[peerName=<no peer name>, peerIdentifier=7C:F9:E:34:8A:A0, peerAvailable=true, time=499, peerName=<no peer name>, peerIdentifier=7C:F9:E:37:96:AB, peerAvailable=true, time=628, peerName=<no peer name>, peerIdentifier=8:EC:A9:50:75:41, peerAvailable=true, time=726, peerName=<no peer name>, peerIdentifier=7C:F9:E:51:18:22, peerAvailable=true, time=729, peerName=<no peer name>, peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=1064, peerName=<no peer name>, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=1201, peerName=<no peer name>, peerIdentifier=8:EC:A9:50:76:27, peerAvailable=true, time=1307, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=12629, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=39056, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=49664, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=50683, peerName=<no peer name>, peerIdentifier=44:80:EB:7B:5A:5, peerAvailable=false, time=90488], sendList=[name=08:EC:A9:50:75:41, time=32992, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail], notTriedList=[connections=0, name=34:FC:EF:11:B1:66, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=80:01:84:8A:B3:68, time=0, result=Fail, connections=0, name=34:FC:EF:9D:93:0B, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=B4:CE:F6:AB:A4:6A, time=0, result=Fail, connections=0, name=90:E7:C4:F6:69:77, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail], peersList=[peerName=<no peer name>, peerIdentifier=7C:F9:E:37:96:AB, peerAvailable=true, time=316, peerName=<no peer name>, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=1298, peerName=<no peer name>, peerIdentifier=7C:F9:E:51:18:22, peerAvailable=true, time=1586, peerName=<no peer name>, peerIdentifier=8:EC:A9:50:76:27, peerAvailable=true, time=1797, peerName=<no peer name>, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=5652, peerName=<no peer name>, peerIdentifier=7C:F9:E:34:8A:A0, peerAvailable=true, time=6359, peerName=<no peer name>, peerIdentifier=8:EC:A9:50:75:41, peerAvailable=true, time=6455, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=61218, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=61819, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=84173, peerName=<no peer name>, peerIdentifier=44:80:EB:7B:5A:5, peerAvailable=false, time=90350], sendList=[name=58:3F:54:73:64:C0, time=12842, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:37:96:AB, time=33565, result=OK, connections=2, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=80:01:84:8A:B3:68, time=0, result=Fail], notTriedList=[connections=0, name=34:FC:EF:11:B1:66, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=90:E7:C4:F6:69:77, time=0, result=Fail, connections=0, name=B4:CE:F6:AB:A4:6A, time=0, result=Fail, connections=0, name=34:FC:EF:9D:93:0B, time=0, result=Fail], peersList=[peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=2203, peerName=Nexus 5, peerIdentifier=34:FC:EF:11:AE:67, peerAvailable=true, time=3261, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=11254, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=13915, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=13936, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=33625], sendList=[name=7C:F9:0E:34:8A:A0, time=8810, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=34:FC:EF:9D:93:0B, time=0, result=Fail, connections=1, name=B4:CE:F6:AB:A4:6A, time=0, result=Fail], notTriedList=[connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=34:FC:EF:11:B1:66, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=90:E7:C4:F6:69:77, time=0, result=Fail, connections=0, name=80:01:84:8A:B3:68, time=0, result=Fail], peersList=[peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=76845], sendList=[name=34:FC:EF:11:AE:67, time=9702, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=90:E7:C4:F6:69:77, time=12431, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=E0:DB:10:14:E2:C0, time=15908, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=34:FC:EF:11:B1:66, time=0, result=Fail], notTriedList=[connections=0, name=80:01:84:8A:B3:68, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=B4:CE:F6:AB:A4:6A, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=34:FC:EF:9D:93:0B, time=0, result=Fail], peersList=[peerName=<no peer name>, peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=1059, peerName=<no peer name>, peerIdentifier=7C:F9:E:37:96:AB, peerAvailable=true, time=1116, peerName=<no peer name>, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=1200, peerName=<no peer name>, peerIdentifier=7C:F9:E:34:8A:A0, peerAvailable=true, time=1218, peerName=<no peer name>, peerIdentifier=8:EC:A9:50:75:41, peerAvailable=true, time=1244, peerName=<no peer name>, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=1277, peerName=<no peer name>, peerIdentifier=8:EC:A9:50:76:27, peerAvailable=true, time=1829, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=79043, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=83725, peerName=<no peer name>, peerIdentifier=44:80:EB:7B:5A:5, peerAvailable=false, time=91059, peerName=HTC One M8s, peerIdentifier=90:E7:C4:F6:69:77, peerAvailable=true, time=91768], sendList=[], failedPeer=[connections=1, name=08:EC:A9:50:76:27, time=0, result=Fail], notTriedList=[connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=34:FC:EF:11:B1:66, time=0, result=Fail, connections=0, name=34:FC:EF:9D:93:0B, time=0, result=Fail, connections=0, name=B4:CE:F6:AB:A4:6A, time=0, result=Fail, connections=0, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail, connections=0, name=90:E7:C4:F6:69:77, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=80:01:84:8A:B3:68, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail], peersList=[peerName=<no peer name>, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=226, peerName=<no peer name>, peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=541, peerName=<no peer name>, peerIdentifier=7C:F9:E:37:96:AB, peerAvailable=true, time=841, peerName=<no peer name>, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=1172, peerName=<no peer name>, peerIdentifier=8:EC:A9:50:75:41, peerAvailable=true, time=1244, peerName=<no peer name>, peerIdentifier=8:EC:A9:50:76:27, peerAvailable=true, time=1829, peerName=<no peer name>, peerIdentifier=7C:F9:E:51:18:22, peerAvailable=true, time=5401, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=15014, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=42862, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=54992, peerName=<no peer name>, peerIdentifier=44:80:EB:7B:5A:5, peerAvailable=false, time=90237], sendList=[name=08:EC:A9:50:76:27, time=8206, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=E0:DB:10:14:E2:C0, time=8788, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=1, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail], notTriedList=[connections=0, name=90:E7:C4:F6:69:77, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=34:FC:EF:9D:93:0B, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=34:FC:EF:11:B1:66, time=0, result=Fail, connections=0, name=B4:CE:F6:AB:A4:6A, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=80:01:84:8A:B3:68, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail], peersList=[peerName=<no peer name>, peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=1560, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=5249, peerName=<no peer name>, peerIdentifier=8:EC:A9:50:76:27, peerAvailable=true, time=5494, peerName=<no peer name>, peerIdentifier=7C:F9:E:37:96:AB, peerAvailable=true, time=5545, peerName=<no peer name>, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=5651, peerName=<no peer name>, peerIdentifier=7C:F9:E:34:8A:A0, peerAvailable=true, time=5841, peerName=<no peer name>, peerIdentifier=7C:F9:E:51:18:22, peerAvailable=true, time=11963, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=17524, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=22317, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=67385, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=67752, peerName=<no peer name>, peerIdentifier=44:80:EB:7B:5A:5, peerAvailable=false, time=90941], sendList=[name=F8:95:C7:87:3C:51, time=23366, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=44:80:EB:7B:5A:05, time=0, result=Fail], notTriedList=[connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=34:FC:EF:9D:93:0B, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=34:FC:EF:11:B1:66, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=B4:CE:F6:AB:A4:6A, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=90:E7:C4:F6:69:77, time=0, result=Fail, connections=0, name=80:01:84:8A:B3:68, time=0, result=Fail], peersList=[peerName=<no peer name>, peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=285, peerName=<no peer name>, peerIdentifier=7C:F9:E:37:96:AB, peerAvailable=true, time=323, peerName=<no peer name>, peerIdentifier=7C:F9:E:34:8A:A0, peerAvailable=true, time=459, peerName=<no peer name>, peerIdentifier=8:EC:A9:50:75:41, peerAvailable=true, time=467, peerName=<no peer name>, peerIdentifier=7C:F9:E:51:18:22, peerAvailable=true, time=9868, peerName=<no peer name>, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=12603, peerName=<no peer name>, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=12870, peerName=<no peer name>, peerIdentifier=44:80:EB:7B:5A:5, peerAvailable=false, time=90293], sendList=[], failedPeer=[connections=1, name=44:80:EB:7B:5A:05, time=0, result=Fail], notTriedList=[connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=80:01:84:8A:B3:68, time=0, result=Fail, connections=0, name=F4:F1:E1:5C:3B:E2, time=0, result=Fail, connections=0, name=34:FC:EF:11:B1:66, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=90:E7:C4:F6:69:77, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=B4:CE:F6:AB:A4:6A, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=34:FC:EF:9D:93:0B, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail]

2016-01-08T17:01:11.901Z - debug: end to Nexus 5

2016-01-08T17:01:11.903Z - debug: end to HTC One M8s

2016-01-08T17:01:11.909Z - debug: end to A5-1

2016-01-08T17:01:11.910Z - debug: end to G4-1

2016-01-08T17:01:11.912Z - debug: end to Note4-1

2016-01-08T17:01:11.913Z - debug: end to Thali Test (Galaxy S5)

2016-01-08T17:01:11.915Z - debug: end to G3-1

2016-01-08T17:01:11.916Z - debug: end to XT1072

2016-01-08T17:01:11.917Z - debug: end to Nexus 5

2016-01-08T17:01:11.919Z - debug: end to G3s-1

2016-01-08T17:01:11.920Z - debug: end to Thali Test's G2

2016-01-08T17:01:11.921Z - debug: end to Thali Test (Galaxy A5)

2016-01-08T17:01:11.923Z - debug: end to S5-1

2016-01-08T17:01:11.924Z - debug: end to A3-1

2016-01-08T17:01:11.925Z - debug: end to HTC Desire 820

2016-01-08T17:01:11.926Z - debug: end to HTC Desire 820

2016-01-08T17:01:11.927Z - debug: end to Thali Test (Galaxy A3)

2016-01-08T17:01:11.929Z - debug: end to S5mini-1

2016-01-08T17:01:11.930Z - debug: end to XT1039

2016-01-08T17:01:12.493Z - debug: Socket disconnected: transport close 0 (Nexus 5)

2016-01-08T17:01:12.667Z - debug: Socket disconnected: transport close 5 (Note4-1)

2016-01-08T17:01:12.698Z - debug: Socket disconnected: transport close 19 (Thali Test (Galaxy A3))

2016-01-08T17:01:12.911Z - debug: Socket disconnected: transport close 3 (A5-1)

2016-01-08T17:01:13.104Z - debug: Socket disconnected: transport close 16 (A3-1)

2016-01-08T17:01:13.546Z - debug: Socket disconnected: transport close 4 (G4-1)

2016-01-08T17:01:13.600Z - debug: Socket disconnected: transport close 14 (Thali Test (Galaxy A5))

2016-01-08T17:01:14.237Z - debug: Socket disconnected: transport close 6 (Thali Test (Galaxy S5))

2016-01-08T17:01:14.710Z - debug: Socket disconnected: transport close 13 (S5-1)

2016-01-08T17:01:15.521Z - debug: Socket disconnected: transport close 7 (G3-1)

2016-01-08T17:01:15.972Z - debug: Socket disconnected: transport close 11 (G3s-1)

2016-01-08T17:01:22.423Z - debug: Socket disconnected: ping timeout 1 (HTC One M8s)


 
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
Device test finished on LGH8153b36be34 
Device test finished on f56ad48d 
Android task is completed. [SUCCESS]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/55467363832a26e_Story_001_tompaana_406_tompaana/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/55467363832a26e_Story_001_tompaana_406_tompaana/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/55467363832a26e_Story_001_tompaana_406_tompaana/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/55467363832a26e_Story_001_tompaana_406_tompaana/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:null 
child process exited with code null on device 320414cd475f91e3 
Error! Unexpected exit on device TA4750HV7I app:com.test.thalitest code:0 
child process exited with code 0 on device TA4750HV7I 
Android task is completed. [FAILED]
```
[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/55467363832a26e_Story_001_tompaana_406_tompaana/thali03_samsung-SM-G800F.md)

[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/55467363832a26e_Story_001_tompaana_406_tompaana/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/55467363832a26e_Story_001_tompaana_406_tompaana/thali03_LGE-LG-D855.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/55467363832a26e_Story_001_tompaana_406_tompaana/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/55467363832a26e_Story_001_tompaana_406_tompaana/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/55467363832a26e_Story_001_tompaana_406_tompaana/thali04_samsung-SM-G900F.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/55467363832a26e_Story_001_tompaana_406_tompaana/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/55467363832a26e_Story_001_tompaana_406_tompaana/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/55467363832a26e_Story_001_tompaana_406_tompaana/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
STOP log received from  4db5c8cc Test has  SUCCEEDED
STOP log received from  c5afcdcb Test has  SUCCEEDED
Device test finished on 4db5c8cc 
Device test finished on c5afcdcb 
Android task is completed. [SUCCESS]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/55467363832a26e_Story_001_tompaana_406_tompaana/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/55467363832a26e_Story_001_tompaana_406_tompaana/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/55467363832a26e_Story_001_tompaana_406_tompaana/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/55467363832a26e_Story_001_tompaana_406_tompaana/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/55467363832a26e_Story_001_tompaana_406_tompaana/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/55467363832a26e_Story_001_tompaana_406_tompaana/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/55467363832a26e_Story_001_tompaana_406_tompaana/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/55467363832a26e_Story_001_tompaana_406_tompaana/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/55467363832a26e_Story_001_tompaana_406_tompaana/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/55467363832a26e_Story_001_tompaana_406_tompaana/iOS_Iphone5s-1.md)



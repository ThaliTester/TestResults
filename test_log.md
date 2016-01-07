#### Test 5531115118861c0 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-07T09:47:26.703Z - info: listening on *:3000

2016-01-07T09:47:26.999Z - debug: Device presented: A5-1 (android) perftest socket:0

2016-01-07T09:47:27.009Z - info: Setting start timeout to: 120000 (android)

2016-01-07T09:47:27.412Z - debug: Device presented: Apple-Iphone5-1 (ios) perftest socket:2

2016-01-07T09:47:27.414Z - info: Setting start timeout to: 120000 (ios)

2016-01-07T09:47:27.431Z - debug: Device presented: S5-1 (android) perftest socket:1

2016-01-07T09:47:27.855Z - debug: Device presented: Thali Test (Galaxy A3) (android) perftest socket:3

2016-01-07T09:47:28.520Z - debug: Device presented: XT1072 (android) perftest socket:4

2016-01-07T09:47:28.795Z - debug: Device presented: G3s-1 (android) perftest socket:5

2016-01-07T09:47:29.165Z - debug: Device presented: Thali Test (Galaxy S5) (android) perftest socket:6

2016-01-07T09:47:29.169Z - debug: Device presented: Apple-IpadAir2-1 (ios) perftest socket:7

2016-01-07T09:47:29.189Z - debug: Device presented: Apple-Iphone5s-1 (ios) perftest socket:8

2016-01-07T09:47:29.347Z - debug: Device presented: Note4-1 (android) perftest socket:9

2016-01-07T09:47:29.622Z - debug: Device presented: Apple-Iphone6-1 (ios) perftest socket:10

2016-01-07T09:47:29.623Z - info: Required number of devices presented

2016-01-07T09:47:29.627Z - info: Starting perf test run for platform: ios

2016-01-07T09:47:29.628Z - info: Using devices:

2016-01-07T09:47:29.629Z - info: Apple-Iphone5-1

2016-01-07T09:47:29.630Z - info: Apple-IpadAir2-1

2016-01-07T09:47:29.631Z - info: Apple-Iphone5s-1
2016-01-07T09:47:29.632Z - info: Apple-Iphone6-1

2016-01-07T09:47:29.636Z - info: Starting test: with 4 devices (ios)

2016-01-07T09:47:29.711Z - info: Received results for {"name:":"Apple-Iphone6-1","time":36,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone6-1.qqPEfA==","peerAvailable":true,"time":35}]} Apple-Iphone6-1 ios (4 left)

2016-01-07T09:47:30.271Z - debug: Device presented: A3-1 (android) perftest socket:11

2016-01-07T09:47:30.608Z - info: Received results for {"name:":"Apple-IpadAir2-1","time":526,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-IpadAir2-1.LQugrg==","peerAvailable":true,"time":524}]} Apple-IpadAir2-1 ios (3 left)

2016-01-07T09:47:30.628Z - info: Received results for {"name:":"Apple-Iphone5-1","time":530,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone5-1.Xe0AvA==","peerAvailable":true,"time":529}]} Apple-Iphone5-1 ios (2 left)

2016-01-07T09:47:30.860Z - debug: Device presented: Thali Test (Galaxy A5) (android) perftest socket:12

2016-01-07T09:47:30.870Z - debug: Device presented: Nexus 5 (android) perftest socket:13

2016-01-07T09:47:31.154Z - debug: Device presented: G4-1 (android) perftest socket:14

2016-01-07T09:47:33.250Z - info: Received results for {"name:":"Apple-Iphone5s-1","time":654,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-IpadAir2-1.1I3u2A==","peerAvailable":true,"time":652}]} Apple-Iphone5s-1 ios (1 left)

2016-01-07T09:47:33.254Z - info: All test data retrieved for testFindPeers.js (ios)

2016-01-07T09:47:33.262Z - info: Remaining tests: %s ios=[testSendData.js]

2016-01-07T09:47:33.267Z - info: Continuing to next test: testSendData.js
2016-01-07T09:47:33.268Z - info: Starting test: with 4 devices (ios)

2016-01-07T09:47:34.596Z - debug: Device presented: S5mini-1 (android) perftest socket:15

2016-01-07T09:47:35.096Z - debug: Device presented: G3-1 (android) perftest socket:16

2016-01-07T09:47:35.923Z - debug: Socket disconnected: transport close 15 (S5mini-1)

2016-01-07T09:48:40.960Z - info: Received results for {"name:":"Apple-Iphone5-1","time":67170,"result":"OK","sendList":[{"name":"Apple-Iphone5-1.Xe0AvA==","time":51293,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-IpadAir2-1.CdHxkA==","time":5243,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1.Uf4Y7g==","time":4498,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1.Waegsg==","time":5163,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone5-1 ios (4 left)

2016-01-07T09:48:49.394Z - info: Received results for {"name:":"Apple-Iphone5s-1","time":76078,"result":"OK","sendList":[{"name":"Apple-IpadAir2-1.1I3u2A==","time":42328,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-IpadAir2-1.CdHxkA==","time":26132,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1.Uf4Y7g==","time":3696,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1.XzilZw==","time":3628,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone5s-1 ios (3 left)

2016-01-07T09:48:52.477Z - info: Received results for {"name:":"Apple-IpadAir2-1","time":79129,"result":"OK","sendList":[{"name":"Apple-IpadAir2-1.LQugrg==","time":51954,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-Iphone5s-1.Waegsg==","time":18924,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1.XzilZw==","time":4042,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1.Uf4Y7g==","time":4061,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-IpadAir2-1 ios (2 left)

2016-01-07T09:49:13.393Z - info: Received results for {"name:":"Apple-Iphone6-1","time":100034,"result":"TIMEOUT","sendList":[{"name":"Apple-IpadAir2-1.1I3u2A==","time":42352,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-Iphone6-1.qqPEfA==","time":40104,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-IpadAir2-1.CdHxkA==","time":0,"result":"Fail"}]} Apple-Iphone6-1 ios (1 left)

2016-01-07T09:49:13.394Z - info: All test data retrieved for testSendData.js (ios)

2016-01-07T09:49:13.400Z - info: Remaining tests: %s ios=[]

2016-01-07T09:49:13.401Z - info: ALL DONE !!!

{ 'name:': 'Apple-Iphone5-1',
  time: 530,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1.Xe0AvA==',
       peerAvailable: true,
       time: 529 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 526,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1.LQugrg==',
       peerAvailable: true,
       time: 524 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 654,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1.1I3u2A==',
       peerAvailable: true,
       time: 652 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 36,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1.qqPEfA==',
       peerAvailable: true,
       time: 35 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 67170,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.Xe0AvA==',
       time: 51293,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.CdHxkA==',
       time: 5243,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.Uf4Y7g==',
       time: 4498,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.Waegsg==',
       time: 5163,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 79129,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1.LQugrg==',
       time: 51954,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1.Waegsg==',
       time: 18924,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.XzilZw==',
       time: 4042,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.Uf4Y7g==',
       time: 4061,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 76078,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1.1I3u2A==',
       time: 42328,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.CdHxkA==',
       time: 26132,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.Uf4Y7g==',
       time: 3696,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.XzilZw==',
       time: 3628,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 100034,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'Apple-IpadAir2-1.1I3u2A==',
       time: 42352,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1.qqPEfA==',
       time: 40104,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.CdHxkA==', time: 0, result: 'Fail' } ] }

--------------- test report ---------------------
--------------- Apple-Iphone5-1 --------------------- : 1

Find peers : 100% : 529 ms, 99% : 529 ms, 95 : 529 ms, 90% : 529 ms.

Result count 1, range 529 ms to  529 ms.

Send data : 100% : 5243 ms, 99% : 5243 ms, 95 : 5243 ms, 90% : 5243 ms.

Average data rate: 0.02 MB/s

Result count 3, range 4498 ms to  5243 ms.

Send data failed peers count : 1 [25 %]

- Peer ID : Apple-Iphone5-1.Xe0AvA==, Tried : 5

Send data never tried peers count : 0 [0 %]
--------------- Apple-IpadAir2-1 --------------------- : 2

Find peers : 100% : 524 ms, 99% : 524 ms, 95 : 524 ms, 90% : 524 ms.
Result count 1, range 524 ms to  524 ms.

Send data : 100% : 18924 ms, 99% : 18924 ms, 95 : 18924 ms, 90% : 18924 ms.

Average data rate: 0.011 MB/s
Result count 3, range 4042 ms to  18924 ms.

Send data failed peers count : 1 [25 %]
- Peer ID : Apple-IpadAir2-1.LQugrg==, Tried : 5
Send data never tried peers count : 0 [0 %]

--------------- Apple-Iphone5s-1 --------------------- : 3
Find peers : 100% : 652 ms, 99% : 652 ms, 95 : 652 ms, 90% : 652 ms.
Result count 1, range 652 ms to  652 ms.

Send data : 100% : 26132 ms, 99% : 26132 ms, 95 : 26132 ms, 90% : 26132 ms.
Average data rate: 0.009 MB/s

Result count 3, range 3628 ms to  26132 ms.
Send data failed peers count : 1 [25 %]
- Peer ID : Apple-IpadAir2-1.1I3u2A==, Tried : 5

Send data never tried peers count : 0 [0 %]

--------------- Apple-Iphone6-1 --------------------- : 4
Find peers : 100% : 35 ms, 99% : 35 ms, 95 : 35 ms, 90% : 35 ms.
Result count 1, range 35 ms to  35 ms.

No send data results!
--------------- Combined ---------------------

Find peers : 100% : 652 ms, 99% : 652 ms, 95 : 652 ms, 90% : 652 ms.
Send data : 100% : 26132 ms, 99% : 26132 ms, 95 : 26132 ms, 90% : 18924 ms.

Average data rate: 0.012 MB/s
--------------- end of test report ---------------------

2016-01-07T09:49:13.534Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1.Xe0AvA==, peerAvailable=true, time=529], sendList=[name=Apple-Iphone6-1.Uf4Y7g==, time=4498, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5s-1.Waegsg==, time=5163, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.CdHxkA==, time=5243, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone5-1.Xe0AvA==, time=51293, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1.LQugrg==, peerAvailable=true, time=524], sendList=[name=Apple-Iphone5-1.XzilZw==, time=4042, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone6-1.Uf4Y7g==, time=4061, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5s-1.Waegsg==, time=18924, result=OK, connections=2, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-IpadAir2-1.LQugrg==, time=51954, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1.1I3u2A==, peerAvailable=true, time=652], sendList=[name=Apple-Iphone5-1.XzilZw==, time=3628, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone6-1.Uf4Y7g==, time=3696, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.CdHxkA==, time=26132, result=OK, connections=2, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-IpadAir2-1.1I3u2A==, time=42328, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1.qqPEfA==, peerAvailable=true, time=35], sendList=[], failedPeer=[name=Apple-IpadAir2-1.1I3u2A==, time=42352, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, name=Apple-Iphone6-1.qqPEfA==, time=40104, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[name=Apple-IpadAir2-1.CdHxkA==, time=0, result=Fail]

2016-01-07T09:49:13.543Z - debug: end to Apple-Iphone5-1

2016-01-07T09:49:13.545Z - debug: end to Apple-IpadAir2-1

2016-01-07T09:49:13.546Z - debug: end to Apple-Iphone5s-1

2016-01-07T09:49:13.548Z - debug: end to Apple-Iphone6-1

2016-01-07T09:49:14.079Z - debug: state: android waiting

2016-01-07T09:49:14.081Z - debug: state: ios completed

2016-01-07T09:49:16.194Z - debug: Socket disconnected: transport close 7 (Apple-IpadAir2-1)

2016-01-07T09:49:16.435Z - debug: Socket disconnected: transport close 8 (Apple-Iphone5s-1)

2016-01-07T09:49:16.679Z - debug: Socket disconnected: transport close 2 (Apple-Iphone5-1)

2016-01-07T09:49:16.689Z - debug: Socket disconnected: transport close 10 (Apple-Iphone6-1)

2016-01-07T09:49:27.021Z - info: Start timeout elapsed for platform: android

2016-01-07T09:49:27.023Z - info: Starting perf test run for platform: android

2016-01-07T09:49:27.024Z - info: Using devices:

2016-01-07T09:49:27.025Z - info: A5-1

2016-01-07T09:49:27.026Z - info: S5-1

2016-01-07T09:49:27.027Z - info: Thali Test (Galaxy A3)

2016-01-07T09:49:27.028Z - info: XT1072

2016-01-07T09:49:27.030Z - info: G3s-1

2016-01-07T09:49:27.031Z - info: Thali Test (Galaxy S5)

2016-01-07T09:49:27.032Z - info: Note4-1

2016-01-07T09:49:27.032Z - info: A3-1

2016-01-07T09:49:27.033Z - info: Thali Test (Galaxy A5)

2016-01-07T09:49:27.034Z - info: Nexus 5

2016-01-07T09:49:27.035Z - info: G4-1
2016-01-07T09:49:27.036Z - info: S5mini-1

2016-01-07T09:49:27.037Z - info: G3-1

2016-01-07T09:49:27.039Z - info: Starting test: with 13 devices (android)

2016-01-07T09:49:29.687Z - info: server timeout for test: testFindPeers.js (ios)

2016-01-07T09:49:29.689Z - info: All test data retrieved for testFindPeers.js (ios)

2016-01-07T09:49:29.691Z - info: Remaining tests: %s ios=[], android=[testFindPeers.js, testSendData.js]

2016-01-07T09:49:29.692Z - info: ALL DONE !!!

{ 'name:': 'Apple-Iphone5-1',
  time: 530,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1.Xe0AvA==',
       peerAvailable: true,
       time: 529 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 526,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1.LQugrg==',
       peerAvailable: true,
       time: 524 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 654,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1.1I3u2A==',
       peerAvailable: true,
       time: 652 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 36,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1.qqPEfA==',
       peerAvailable: true,
       time: 35 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 67170,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.Xe0AvA==',
       time: 51293,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.CdHxkA==',
       time: 5243,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.Uf4Y7g==',
       time: 4498,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.Waegsg==',
       time: 5163,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 79129,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1.LQugrg==',
       time: 51954,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1.Waegsg==',
       time: 18924,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.XzilZw==',
       time: 4042,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.Uf4Y7g==',
       time: 4061,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 76078,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1.1I3u2A==',
       time: 42328,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.CdHxkA==',
       time: 26132,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.Uf4Y7g==',
       time: 3696,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.XzilZw==',
       time: 3628,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 100034,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'Apple-IpadAir2-1.1I3u2A==',
       time: 42352,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1.qqPEfA==',
       time: 40104,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.CdHxkA==', time: 0, result: 'Fail' } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 67170,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.Xe0AvA==',
       time: 51293,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.CdHxkA==',
       time: 5243,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.Uf4Y7g==',
       time: 4498,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.Waegsg==',
       time: 5163,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 79129,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1.LQugrg==',
       time: 51954,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1.Waegsg==',
       time: 18924,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.XzilZw==',
       time: 4042,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.Uf4Y7g==',
       time: 4061,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 76078,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1.1I3u2A==',
       time: 42328,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.CdHxkA==',
       time: 26132,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.Uf4Y7g==',
       time: 3696,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.XzilZw==',
       time: 3628,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 100034,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'Apple-IpadAir2-1.1I3u2A==',
       time: 42352,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1.qqPEfA==',
       time: 40104,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.CdHxkA==', time: 0, result: 'Fail' } ] }

--------------- test report ---------------------
--------------- Apple-Iphone5-1 --------------------- : 1
Find peers : 100% : 529 ms, 99% : 529 ms, 95 : 529 ms, 90% : 529 ms.

Result count 1, range 529 ms to  529 ms.
Send data : 100% : 5243 ms, 99% : 5243 ms, 95 : 5243 ms, 90% : 5243 ms.

Average data rate: 0.02 MB/s
Result count 6, range 4498 ms to  5243 ms.
Send data failed peers count : 2 [25 %]
- Peer ID : Apple-Iphone5-1.Xe0AvA==, Tried : 5
- Peer ID : Apple-Iphone5-1.Xe0AvA==, Tried : 5
Send data never tried peers count : 0 [0 %]
--------------- Apple-IpadAir2-1 --------------------- : 2
Find peers : 100% : 524 ms, 99% : 524 ms, 95 : 524 ms, 90% : 524 ms.
Result count 1, range 524 ms to  524 ms.

Send data : 100% : 18924 ms, 99% : 18924 ms, 95 : 18924 ms, 90% : 18924 ms.
Average data rate: 0.011 MB/s
Result count 6, range 4042 ms to  18924 ms.
Send data failed peers count : 2 [25 %]
- Peer ID : Apple-IpadAir2-1.LQugrg==, Tried : 5
- Peer ID : Apple-IpadAir2-1.LQugrg==, Tried : 5
Send data never tried peers count : 0 [0 %]
--------------- Apple-Iphone5s-1 --------------------- : 3
Find peers : 100% : 652 ms, 99% : 652 ms, 95 : 652 ms, 90% : 652 ms.
Result count 1, range 652 ms to  652 ms.

Send data : 100% : 26132 ms, 99% : 26132 ms, 95 : 26132 ms, 90% : 26132 ms.
Average data rate: 0.009 MB/s
Result count 6, range 3628 ms to  26132 ms.
Send data failed peers count : 2 [25 %]
- Peer ID : Apple-IpadAir2-1.1I3u2A==, Tried : 5
- Peer ID : Apple-IpadAir2-1.1I3u2A==, Tried : 5
Send data never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1 --------------------- : 4
Find peers : 100% : 35 ms, 99% : 35 ms, 95 : 35 ms, 90% : 35 ms.
Result count 1, range 35 ms to  35 ms.
No send data results!
--------------- Combined ---------------------
Find peers : 100% : 652 ms, 99% : 652 ms, 95 : 652 ms, 90% : 652 ms.
Send data : 100% : 26132 ms, 99% : 26132 ms, 95 : 26132 ms, 90% : 18924 ms.
Average data rate: 0.012 MB/s
--------------- end of test report ---------------------

2016-01-07T09:49:29.812Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1.Xe0AvA==, peerAvailable=true, time=529], sendList=[name=Apple-Iphone6-1.Uf4Y7g==, time=4498, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1"]["sendList"][0], name=Apple-Iphone5s-1.Waegsg==, time=5163, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1"]["sendList"][2], name=Apple-IpadAir2-1.CdHxkA==, time=5243, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1"]["sendList"][4]], failedPeer=[name=Apple-Iphone5-1.Xe0AvA==, time=51293, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone5-1"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1.LQugrg==, peerAvailable=true, time=524], sendList=[name=Apple-Iphone5-1.XzilZw==, time=4042, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1"]["sendList"][0], name=Apple-Iphone6-1.Uf4Y7g==, time=4061, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1"]["sendList"][2], name=Apple-Iphone5s-1.Waegsg==, time=18924, result=OK, connections=2, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1"]["sendList"][4]], failedPeer=[name=Apple-IpadAir2-1.LQugrg==, time=51954, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-IpadAir2-1"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1.1I3u2A==, peerAvailable=true, time=652], sendList=[name=Apple-Iphone5-1.XzilZw==, time=3628, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1"]["sendList"][0], name=Apple-Iphone6-1.Uf4Y7g==, time=3696, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1"]["sendList"][2], name=Apple-IpadAir2-1.CdHxkA==, time=26132, result=OK, connections=2, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1"]["sendList"][4]], failedPeer=[name=Apple-IpadAir2-1.1I3u2A==, time=42328, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone5s-1"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1.qqPEfA==, peerAvailable=true, time=35], sendList=[], failedPeer=[name=Apple-IpadAir2-1.1I3u2A==, time=42352, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, name=Apple-Iphone6-1.qqPEfA==, time=40104, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone6-1"]["sendError"]["failedPeer"][0], $ref=$["Apple-Iphone6-1"]["sendError"]["failedPeer"][1]], notTriedList=[name=Apple-IpadAir2-1.CdHxkA==, time=0, result=Fail, $ref=$["Apple-Iphone6-1"]["sendError"]["notTriedList"][0]]

2016-01-07T09:49:29.823Z - debug: end to Apple-Iphone5-1
2016-01-07T09:49:29.825Z - debug: end to Apple-IpadAir2-1
2016-01-07T09:49:29.826Z - debug: end to Apple-Iphone5s-1
2016-01-07T09:49:29.827Z - debug: end to Apple-Iphone6-1

2016-01-07T09:49:33.271Z - info: server timeout for test: testSendData.js (ios)
2016-01-07T09:49:33.272Z - info: All test data retrieved for testSendData.js (ios)

2016-01-07T09:49:33.274Z - info: Remaining tests: %s ios=[], android=[testFindPeers.js, testSendData.js]
2016-01-07T09:49:33.277Z - info: ALL DONE !!!

{ 'name:': 'Apple-Iphone5-1',
  time: 530,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1.Xe0AvA==',
       peerAvailable: true,
       time: 529 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 526,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1.LQugrg==',
       peerAvailable: true,
       time: 524 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 654,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1.1I3u2A==',
       peerAvailable: true,
       time: 652 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 36,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1.qqPEfA==',
       peerAvailable: true,
       time: 35 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 67170,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.Xe0AvA==',
       time: 51293,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.CdHxkA==',
       time: 5243,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.Uf4Y7g==',
       time: 4498,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.Waegsg==',
       time: 5163,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 79129,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1.LQugrg==',
       time: 51954,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1.Waegsg==',
       time: 18924,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.XzilZw==',
       time: 4042,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.Uf4Y7g==',
       time: 4061,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 76078,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1.1I3u2A==',
       time: 42328,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.CdHxkA==',
       time: 26132,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.Uf4Y7g==',
       time: 3696,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.XzilZw==',
       time: 3628,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 100034,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'Apple-IpadAir2-1.1I3u2A==',
       time: 42352,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1.qqPEfA==',
       time: 40104,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.CdHxkA==', time: 0, result: 'Fail' } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 67170,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.Xe0AvA==',
       time: 51293,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.CdHxkA==',
       time: 5243,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.Uf4Y7g==',
       time: 4498,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.Waegsg==',
       time: 5163,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 79129,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1.LQugrg==',
       time: 51954,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1.Waegsg==',
       time: 18924,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.XzilZw==',
       time: 4042,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.Uf4Y7g==',
       time: 4061,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 76078,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1.1I3u2A==',
       time: 42328,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.CdHxkA==',
       time: 26132,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.Uf4Y7g==',
       time: 3696,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.XzilZw==',
       time: 3628,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 100034,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'Apple-IpadAir2-1.1I3u2A==',
       time: 42352,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1.qqPEfA==',
       time: 40104,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.CdHxkA==', time: 0, result: 'Fail' } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 67170,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.Xe0AvA==',
       time: 51293,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.CdHxkA==',
       time: 5243,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.Uf4Y7g==',
       time: 4498,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.Waegsg==',
       time: 5163,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 79129,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1.LQugrg==',
       time: 51954,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1.Waegsg==',
       time: 18924,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.XzilZw==',
       time: 4042,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.Uf4Y7g==',
       time: 4061,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 76078,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1.1I3u2A==',
       time: 42328,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.CdHxkA==',
       time: 26132,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.Uf4Y7g==',
       time: 3696,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.XzilZw==',
       time: 3628,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 100034,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'Apple-IpadAir2-1.1I3u2A==',
       time: 42352,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1.qqPEfA==',
       time: 40104,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.CdHxkA==', time: 0, result: 'Fail' } ] }

--------------- test report ---------------------
--------------- Apple-Iphone5-1 --------------------- : 1
Find peers : 100% : 529 ms, 99% : 529 ms, 95 : 529 ms, 90% : 529 ms.
Result count 1, range 529 ms to  529 ms.

Send data : 100% : 5243 ms, 99% : 5243 ms, 95 : 5243 ms, 90% : 5243 ms.
Average data rate: 0.02 MB/s
Result count 9, range 4498 ms to  5243 ms.

Send data failed peers count : 3 [25 %]
- Peer ID : Apple-Iphone5-1.Xe0AvA==, Tried : 5
- Peer ID : Apple-Iphone5-1.Xe0AvA==, Tried : 5

- Peer ID : Apple-Iphone5-1.Xe0AvA==, Tried : 5
Send data never tried peers count : 0 [0 %]
--------------- Apple-IpadAir2-1 --------------------- : 2

Find peers : 100% : 524 ms, 99% : 524 ms, 95 : 524 ms, 90% : 524 ms.
Result count 1, range 524 ms to  524 ms.

Send data : 100% : 18924 ms, 99% : 18924 ms, 95 : 18924 ms, 90% : 18924 ms.

Average data rate: 0.011 MB/s
Result count 9, range 4042 ms to  18924 ms.

Send data failed peers count : 3 [25 %]

- Peer ID : Apple-IpadAir2-1.LQugrg==, Tried : 5
- Peer ID : Apple-IpadAir2-1.LQugrg==, Tried : 5
- Peer ID : Apple-IpadAir2-1.LQugrg==, Tried : 5
Send data never tried peers count : 0 [0 %]

--------------- Apple-Iphone5s-1 --------------------- : 3
Find peers : 100% : 652 ms, 99% : 652 ms, 95 : 652 ms, 90% : 652 ms.
Result count 1, range 652 ms to  652 ms.

Send data : 100% : 26132 ms, 99% : 26132 ms, 95 : 26132 ms, 90% : 26132 ms.
Average data rate: 0.009 MB/s
Result count 9, range 3628 ms to  26132 ms.

Send data failed peers count : 3 [25 %]
- Peer ID : Apple-IpadAir2-1.1I3u2A==, Tried : 5
- Peer ID : Apple-IpadAir2-1.1I3u2A==, Tried : 5

- Peer ID : Apple-IpadAir2-1.1I3u2A==, Tried : 5
Send data never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1 --------------------- : 4

Find peers : 100% : 35 ms, 99% : 35 ms, 95 : 35 ms, 90% : 35 ms.
Result count 1, range 35 ms to  35 ms.
No send data results!

--------------- Combined ---------------------
Find peers : 100% : 652 ms, 99% : 652 ms, 95 : 652 ms, 90% : 652 ms.

Send data : 100% : 26132 ms, 99% : 26132 ms, 95 : 26132 ms, 90% : 18924 ms.
Average data rate: 0.012 MB/s
--------------- end of test report ---------------------

2016-01-07T09:49:33.420Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1.Xe0AvA==, peerAvailable=true, time=529], sendList=[name=Apple-Iphone6-1.Uf4Y7g==, time=4498, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1"]["sendList"][0], $ref=$["Apple-Iphone5-1"]["sendList"][0], name=Apple-Iphone5s-1.Waegsg==, time=5163, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1"]["sendList"][3], $ref=$["Apple-Iphone5-1"]["sendList"][3], name=Apple-IpadAir2-1.CdHxkA==, time=5243, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1"]["sendList"][6], $ref=$["Apple-Iphone5-1"]["sendList"][6]], failedPeer=[name=Apple-Iphone5-1.Xe0AvA==, time=51293, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone5-1"]["sendError"]["failedPeer"][0], $ref=$["Apple-Iphone5-1"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1.LQugrg==, peerAvailable=true, time=524], sendList=[name=Apple-Iphone5-1.XzilZw==, time=4042, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1"]["sendList"][0], $ref=$["Apple-IpadAir2-1"]["sendList"][0], name=Apple-Iphone6-1.Uf4Y7g==, time=4061, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1"]["sendList"][3], $ref=$["Apple-IpadAir2-1"]["sendList"][3], name=Apple-Iphone5s-1.Waegsg==, time=18924, result=OK, connections=2, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1"]["sendList"][6], $ref=$["Apple-IpadAir2-1"]["sendList"][6]], failedPeer=[name=Apple-IpadAir2-1.LQugrg==, time=51954, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-IpadAir2-1"]["sendError"]["failedPeer"][0], $ref=$["Apple-IpadAir2-1"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1.1I3u2A==, peerAvailable=true, time=652], sendList=[name=Apple-Iphone5-1.XzilZw==, time=3628, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1"]["sendList"][0], $ref=$["Apple-Iphone5s-1"]["sendList"][0], name=Apple-Iphone6-1.Uf4Y7g==, time=3696, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1"]["sendList"][3], $ref=$["Apple-Iphone5s-1"]["sendList"][3], name=Apple-IpadAir2-1.CdHxkA==, time=26132, result=OK, connections=2, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1"]["sendList"][6], $ref=$["Apple-Iphone5s-1"]["sendList"][6]], failedPeer=[name=Apple-IpadAir2-1.1I3u2A==, time=42328, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone5s-1"]["sendError"]["failedPeer"][0], $ref=$["Apple-Iphone5s-1"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1.qqPEfA==, peerAvailable=true, time=35], sendList=[], failedPeer=[name=Apple-IpadAir2-1.1I3u2A==, time=42352, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, name=Apple-Iphone6-1.qqPEfA==, time=40104, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone6-1"]["sendError"]["failedPeer"][0], $ref=$["Apple-Iphone6-1"]["sendError"]["failedPeer"][1], $ref=$["Apple-Iphone6-1"]["sendError"]["failedPeer"][0], $ref=$["Apple-Iphone6-1"]["sendError"]["failedPeer"][1]], notTriedList=[name=Apple-IpadAir2-1.CdHxkA==, time=0, result=Fail, $ref=$["Apple-Iphone6-1"]["sendError"]["notTriedList"][0], $ref=$["Apple-Iphone6-1"]["sendError"]["notTriedList"][0]]

2016-01-07T09:49:33.427Z - debug: end to Apple-Iphone5-1

2016-01-07T09:49:33.428Z - debug: end to Apple-IpadAir2-1

2016-01-07T09:49:33.430Z - debug: end to Apple-Iphone5s-1

2016-01-07T09:49:33.458Z - debug: end to Apple-Iphone6-1

2016-01-07T09:51:07.541Z - info: Received results for {"name:":"Note4-1","time":100095,"result":"TIMEOUT","peersList":[{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":4868},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":30522},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":43355},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":49665},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":61353},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":99669}]} Note4-1 android (13 left)

2016-01-07T09:51:07.549Z - info: Received results for {"name:":"Thali Test (Galaxy A5)","time":100070,"result":"TIMEOUT","peersList":[{"peerName":"XT1072","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true,"time":3814},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":3910},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":17824},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":18071},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":33514},{"peerName":"Note4-1","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":33793},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":34411},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":44700},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":45881},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":57643}]} Thali Test (Galaxy A5) android (12 left)

2016-01-07T09:51:07.553Z - info: Received results for {"name:":"A3-1","time":100064,"result":"TIMEOUT","peersList":[{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":3056},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":3096},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":3216},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":3254},{"peerName":"Note4-1","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":3288},{"peerName":"Nexus 5","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":true,"time":3391},{"peerName":"XT1072","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true,"time":52010},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":90006},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":90361}]} A3-1 android (11 left)

2016-01-07T09:51:07.594Z - info: Received results for {"name:":"A5-1","time":100071,"result":"TIMEOUT","peersList":[{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":3262},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":41899},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":42630},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":83296},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":84497},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":85907}]} A5-1 android (10 left)

2016-01-07T09:51:07.606Z - info: Received results for {"name:":"Nexus 5","time":100045,"result":"TIMEOUT","peersList":[{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":13389},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":25330},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":72299},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":72519}]} Nexus 5 android (9 left)

2016-01-07T09:51:07.686Z - info: Received results for {"name:":"Thali Test (Galaxy A3)","time":100059,"result":"TIMEOUT","peersList":[{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":81079},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":81511},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":83092},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":84486},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":92098}]} Thali Test (Galaxy A3) android (8 left)

2016-01-07T09:51:07.809Z - info: Received results for {"name:":"S5-1","time":100121,"result":"TIMEOUT","peersList":[{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":23333},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":23336},{"peerName":"Note4-1","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":23577},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":23584},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":49416},{"peerName":"Nexus 5","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":true,"time":61742},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":63894}]} S5-1 android (7 left)

2016-01-07T09:51:07.981Z - info: Received results for {"name:":"XT1072","time":100158,"result":"TIMEOUT","peersList":[{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":2829},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":2979},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":3035},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":3190},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":false,"time":92839},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":false,"time":92832},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":15164},{"peerName":"Note4-1","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":15745}]} XT1072 android (6 left)

2016-01-07T09:51:08.730Z - info: Received results for {"name:":"G4-1","time":100223,"result":"TIMEOUT","peersList":[{"peerName":"XT1072","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true,"time":6279},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":47457},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":47472},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":47536},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":57190},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":57220},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":63352},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":77993},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":96451},{"peerName":"Note4-1","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":96495}]} G4-1 android (5 left)

2016-01-07T09:51:08.800Z - info: Received results for {"name:":"G3s-1","time":100145,"result":"TIMEOUT","peersList":[{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":3669},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":20055},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":62780},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":77651},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":85090},{"peerName":"XT1072","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true,"time":86741},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":98958}]} G3s-1 android (4 left)

2016-01-07T09:51:09.171Z - info: Received results for {"name:":"G3-1","time":100075,"result":"TIMEOUT","peersList":[{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":55625},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":61971},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":62254},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":69309},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":97039},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":97060}]} G3-1 android (3 left)

2016-01-07T09:51:10.302Z - info: Received results for {"name:":"Thali Test (Galaxy S5)","time":100137,"result":"TIMEOUT","peersList":[{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":20716},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":63157},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":63207},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":73885},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":79864},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":85097},{"peerName":"XT1072","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true,"time":85926},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":87683},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":97457}]} Thali Test (Galaxy S5) android (2 left)

2016-01-07T09:51:27.044Z - info: server timeout for test: testFindPeers.js (android)

2016-01-07T09:51:27.046Z - info: All test data retrieved for testFindPeers.js (android)

2016-01-07T09:51:27.056Z - info: No results from S5mini-1

2016-01-07T09:51:27.058Z - info: Remaining tests: %s ios=[], android=[testSendData.js]

2016-01-07T09:51:27.065Z - info: Continuing to next test: testSendData.js

2016-01-07T09:51:27.066Z - info: Starting test: with 13 devices (android)

2016-01-07T09:53:07.360Z - info: Received results for {"name:":"Note4-1","time":100095,"result":"TIMEOUT","sendList":[{"name":"7C:F9:0E:37:96:AB","time":59251,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":9969,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"58:3F:54:73:64:C0","time":10096,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"}]} Note4-1 android (13 left)

2016-01-07T09:53:07.687Z - info: Received results for {"name:":"Thali Test (Galaxy S5)","time":100117,"result":"TIMEOUT","sendList":[{"name":"F8:95:C7:87:85:54","time":18419,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:51:18:22","time":27369,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":1,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"}]} Thali Test (Galaxy S5) android (12 left)

2016-01-07T09:53:07.761Z - info: Received results for {"name:":"Nexus 5","time":100074,"result":"TIMEOUT","sendList":[{"name":"08:EC:A9:50:76:27","time":27948,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"}]} Nexus 5 android (11 left)

2016-01-07T09:53:07.769Z - info: Received results for {"name:":"A3-1","time":100099,"result":"TIMEOUT","sendList":[{"connections":1,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"}]} A3-1 android (10 left)

2016-01-07T09:53:08.078Z - info: Received results for {"name:":"S5-1","time":100089,"result":"TIMEOUT","sendList":[{"connections":1,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":1,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"}]} S5-1 android (9 left)

2016-01-07T09:53:08.185Z - info: Received results for {"name:":"Thali Test (Galaxy A5)","time":100090,"result":"TIMEOUT","sendList":[{"name":"08:EC:A9:50:75:41","time":32449,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":3483,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":1,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"}]} Thali Test (Galaxy A5) android (8 left)

2016-01-07T09:53:08.395Z - info: Received results for {"name:":"G3s-1","time":100131,"result":"TIMEOUT","sendList":[{"name":"58:3F:54:73:64:C0","time":50392,"result":"OK","connections":3,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:37:96:AB","time":25172,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"}]} G3s-1 android (7 left)

2016-01-07T09:53:08.894Z - info: Received results for {"name:":"G4-1","time":100082,"result":"TIMEOUT","sendList":[{"name":"58:3F:54:73:64:C0","time":48948,"result":"OK","connections":3,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":1,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"}]} G4-1 android (6 left)

2016-01-07T09:53:11.606Z - info: Received results for {"name:":"A5-1","time":100087,"result":"TIMEOUT","sendList":[{"name":"34:FC:EF:11:AE:67","time":7741,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"}]} A5-1 android (5 left)

2016-01-07T09:53:11.648Z - info: Received results for {"name:":"G3-1","time":100100,"result":"TIMEOUT","sendList":[{"name":"34:FC:EF:11:AE:67","time":44995,"result":"OK","connections":3,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:75:41","time":14316,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:37:96:AB","time":15203,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":10086,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"}]} G3-1 android (4 left)

2016-01-07T09:53:27.071Z - info: server timeout for test: testSendData.js (android)

2016-01-07T09:53:27.074Z - info: All test data retrieved for testSendData.js (android)

2016-01-07T09:53:27.079Z - info: No results from Thali Test (Galaxy A3)

2016-01-07T09:53:27.082Z - info: No results from XT1072

2016-01-07T09:53:27.088Z - info: No results from S5mini-1

2016-01-07T09:53:27.090Z - info: Remaining tests: %s ios=[], android=[]

2016-01-07T09:53:27.091Z - info: ALL DONE !!!

{ 'name:': 'Apple-Iphone5-1',
  time: 530,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1.Xe0AvA==',
       peerAvailable: true,
       time: 529 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 526,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1.LQugrg==',
       peerAvailable: true,
       time: 524 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 654,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1.1I3u2A==',
       peerAvailable: true,
       time: 652 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 36,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1.qqPEfA==',
       peerAvailable: true,
       time: 35 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 67170,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.Xe0AvA==',
       time: 51293,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.CdHxkA==',
       time: 5243,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.Uf4Y7g==',
       time: 4498,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.Waegsg==',
       time: 5163,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 79129,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1.LQugrg==',
       time: 51954,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1.Waegsg==',
       time: 18924,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.XzilZw==',
       time: 4042,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.Uf4Y7g==',
       time: 4061,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 76078,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1.1I3u2A==',
       time: 42328,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.CdHxkA==',
       time: 26132,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.Uf4Y7g==',
       time: 3696,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.XzilZw==',
       time: 3628,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 100034,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'Apple-IpadAir2-1.1I3u2A==',
       time: 42352,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1.qqPEfA==',
       time: 40104,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.CdHxkA==', time: 0, result: 'Fail' } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 67170,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.Xe0AvA==',
       time: 51293,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.CdHxkA==',
       time: 5243,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.Uf4Y7g==',
       time: 4498,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.Waegsg==',
       time: 5163,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 79129,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1.LQugrg==',
       time: 51954,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1.Waegsg==',
       time: 18924,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.XzilZw==',
       time: 4042,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.Uf4Y7g==',
       time: 4061,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 76078,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1.1I3u2A==',
       time: 42328,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.CdHxkA==',
       time: 26132,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.Uf4Y7g==',
       time: 3696,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.XzilZw==',
       time: 3628,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 100034,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'Apple-IpadAir2-1.1I3u2A==',
       time: 42352,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1.qqPEfA==',
       time: 40104,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.CdHxkA==', time: 0, result: 'Fail' } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 67170,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.Xe0AvA==',
       time: 51293,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.CdHxkA==',
       time: 5243,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.Uf4Y7g==',
       time: 4498,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.Waegsg==',
       time: 5163,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 79129,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1.LQugrg==',
       time: 51954,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1.Waegsg==',
       time: 18924,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.XzilZw==',
       time: 4042,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.Uf4Y7g==',
       time: 4061,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 76078,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1.1I3u2A==',
       time: 42328,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.CdHxkA==',
       time: 26132,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.Uf4Y7g==',
       time: 3696,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.XzilZw==',
       time: 3628,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 100034,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'Apple-IpadAir2-1.1I3u2A==',
       time: 42352,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1.qqPEfA==',
       time: 40104,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.CdHxkA==', time: 0, result: 'Fail' } ] }

{ 'name:': 'A5-1',
  time: 100071,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 3262 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 41899 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 42630 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 83296 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 84497 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 85907 } ] }

{ 'name:': 'S5-1',
  time: 100121,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 23333 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 23336 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 23577 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 23584 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 49416 },
     { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 61742 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 63894 } ] }

{ 'name:': 'Thali Test (Galaxy A3)',
  time: 100059,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 81079 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 81511 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 83092 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 84486 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 92098 } ] }

{ 'name:': 'XT1072',
  time: 100158,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 2829 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 2979 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 3035 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 3190 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: false,
       time: 92839 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: false,
       time: 92832 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 15164 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 15745 } ] }

{ 'name:': 'G3s-1',
  time: 100145,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 3669 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 20055 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 62780 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 77651 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 85090 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 86741 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 98958 } ] }

{ 'name:': 'Thali Test (Galaxy S5)',
  time: 100137,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 20716 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 63157 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 63207 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 73885 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 79864 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 85097 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 85926 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 87683 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 97457 } ] }

{ 'name:': 'Note4-1',
  time: 100095,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 4868 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 30522 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 43355 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 49665 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 61353 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 99669 } ] }

{ 'name:': 'A3-1',
  time: 100064,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 3056 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 3096 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 3216 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 3254 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 3288 },
     { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 3391 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 52010 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 90006 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 90361 } ] }

{ 'name:': 'Thali Test (Galaxy A5)',
  time: 100070,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 3814 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 3910 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 17824 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 18071 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 33514 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 33793 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 34411 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 44700 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 45881 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 57643 } ] }

{ 'name:': 'Nexus 5',
  time: 100045,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 13389 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 25330 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 72299 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 72519 } ] }

{ 'name:': 'G4-1',
  time: 100223,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 6279 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 47457 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 47472 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 47536 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 57190 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 57220 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 63352 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 77993 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 96451 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 96495 } ] }

{ 'name:': 'G3-1',
  time: 100075,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 55625 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 61971 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 62254 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 69309 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 97039 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 97060 } ] }

{ 'name:': 'A5-1',
  time: 100087,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '34:FC:EF:11:AE:67',
       time: 7741,
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
       name: 'E0:DB:10:14:E2:C0',
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
       name: 'F8:95:C7:87:85:54',
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
       name: '7C:F9:0E:51:18:22',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'S5-1',
  time: 100089,
  result: 'TIMEOUT',
  sendList: 
   [ { connections: 1,
       name: '00:F4:6F:30:E0:6C',
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
       name: '58:3F:54:73:64:C0',
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
       name: 'F8:95:C7:87:85:54',
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
       name: 'B0:C5:59:3F:75:69',
       time: 0,
       result: 'Fail' },
     { connections: 1,
       name: '08:EC:A9:50:76:27',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'G3s-1',
  time: 100131,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '58:3F:54:73:64:C0',
       time: 50392,
       result: 'OK',
       connections: 3,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:37:96:AB',
       time: 25172,
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
       name: 'F8:95:C7:87:3C:51',
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
       name: '34:FC:EF:11:AE:67',
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
       name: '00:F4:6F:30:E0:6C',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:51:18:22',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Thali Test (Galaxy S5)',
  time: 100117,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'F8:95:C7:87:85:54',
       time: 18419,
       result: 'OK',
       connections: 2,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:51:18:22',
       time: 27369,
       result: 'OK',
       connections: 2,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: '08:EC:A9:50:75:41',
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
       name: '7C:F9:0E:37:96:AB',
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
     { connections: 0,
       name: '7C:F9:0E:34:8A:A0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:76:27',
       time: 0,
       result: 'Fail' },
     { connections: 1,
       name: '00:F4:6F:30:E0:6C',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Note4-1',
  time: 100095,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '7C:F9:0E:37:96:AB',
       time: 59251,
       result: 'OK',
       connections: 2,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:3C:51',
       time: 9969,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '58:3F:54:73:64:C0',
       time: 10096,
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
       name: 'F8:95:C7:87:85:54',
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
       name: '08:EC:A9:50:76:27',
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
       name: '7C:F9:0E:34:8A:A0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:51:18:22',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'A3-1',
  time: 100099,
  result: 'TIMEOUT',
  sendList: 
   [ { connections: 1,
       name: '08:EC:A9:50:76:27',
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
       name: 'B0:C5:59:3F:75:69',
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
       name: 'F8:95:C7:87:85:54',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:34:8A:A0',
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
       name: 'E0:DB:10:14:E2:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '58:3F:54:73:64:C0',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Thali Test (Galaxy A5)',
  time: 100090,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '08:EC:A9:50:75:41',
       time: 32449,
       result: 'OK',
       connections: 2,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'B0:C5:59:3F:75:69',
       time: 3483,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: 'E0:DB:10:14:E2:C0',
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
       name: 'F8:95:C7:87:3C:51',
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
       name: '7C:F9:0E:37:96:AB',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:76:27',
       time: 0,
       result: 'Fail' },
     { connections: 1,
       name: '00:F4:6F:30:E0:6C',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Nexus 5',
  time: 100074,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '08:EC:A9:50:76:27',
       time: 27948,
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
       name: '08:EC:A9:50:75:41',
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
       name: 'B0:C5:59:3F:75:69',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'E0:DB:10:14:E2:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '00:F4:6F:30:E0:6C',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:34:8A:A0',
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
       name: 'F8:95:C7:87:85:54',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'G4-1',
  time: 100082,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '58:3F:54:73:64:C0',
       time: 48948,
       result: 'OK',
       connections: 3,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: '34:FC:EF:11:AE:67',
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
       name: 'B0:C5:59:3F:75:69',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:37:96:AB',
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
       name: '08:EC:A9:50:76:27',
       time: 0,
       result: 'Fail' },
     { connections: 1,
       name: '00:F4:6F:30:E0:6C',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'G3-1',
  time: 100100,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '34:FC:EF:11:AE:67',
       time: 44995,
       result: 'OK',
       connections: 3,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '08:EC:A9:50:75:41',
       time: 14316,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:37:96:AB',
       time: 15203,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:85:54',
       time: 10086,
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
       name: '00:F4:6F:30:E0:6C',
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
       name: 'E0:DB:10:14:E2:C0',
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

--------------- test report ---------------------
--------------- Apple-Iphone5-1 --------------------- : 1
Find peers : 100% : 529 ms, 99% : 529 ms, 95 : 529 ms, 90% : 529 ms.
Result count 1, range 529 ms to  529 ms.
Send data : 100% : 5243 ms, 99% : 5243 ms, 95 : 5243 ms, 90% : 5243 ms.

Average data rate: 0.02 MB/s
Result count 9, range 4498 ms to  5243 ms.
Send data failed peers count : 3 [25 %]
- Peer ID : Apple-Iphone5-1.Xe0AvA==, Tried : 5
- Peer ID : Apple-Iphone5-1.Xe0AvA==, Tried : 5
- Peer ID : Apple-Iphone5-1.Xe0AvA==, Tried : 5
Send data never tried peers count : 0 [0 %]

--------------- Apple-IpadAir2-1 --------------------- : 2
Find peers : 100% : 524 ms, 99% : 524 ms, 95 : 524 ms, 90% : 524 ms.
Result count 1, range 524 ms to  524 ms.
Send data : 100% : 18924 ms, 99% : 18924 ms, 95 : 18924 ms, 90% : 18924 ms.
Average data rate: 0.011 MB/s
Result count 9, range 4042 ms to  18924 ms.
Send data failed peers count : 3 [25 %]
- Peer ID : Apple-IpadAir2-1.LQugrg==, Tried : 5
- Peer ID : Apple-IpadAir2-1.LQugrg==, Tried : 5

- Peer ID : Apple-IpadAir2-1.LQugrg==, Tried : 5
Send data never tried peers count : 0 [0 %]
--------------- Apple-Iphone5s-1 --------------------- : 3
Find peers : 100% : 652 ms, 99% : 652 ms, 95 : 652 ms, 90% : 652 ms.
Result count 1, range 652 ms to  652 ms.

Send data : 100% : 26132 ms, 99% : 26132 ms, 95 : 26132 ms, 90% : 26132 ms.
Average data rate: 0.009 MB/s
Result count 9, range 3628 ms to  26132 ms.
Send data failed peers count : 3 [25 %]
- Peer ID : Apple-IpadAir2-1.1I3u2A==, Tried : 5
- Peer ID : Apple-IpadAir2-1.1I3u2A==, Tried : 5
- Peer ID : Apple-IpadAir2-1.1I3u2A==, Tried : 5
Send data never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1 --------------------- : 4

Find peers : 100% : 35 ms, 99% : 35 ms, 95 : 35 ms, 90% : 35 ms.
Result count 1, range 35 ms to  35 ms.
No send data results!
--------------- A5-1 --------------------- : 5
Find peers : 100% : 85907 ms, 99% : 85907 ms, 95 : 85907 ms, 90% : 84497 ms.
Result count 6, range 3262 ms to  85907 ms.

Send data : 100% : 7741 ms, 99% : 7741 ms, 95 : 7741 ms, 90% : 7741 ms.
Average data rate: 0.013 MB/s
Result count 1, range 7741 ms to  7741 ms.
Send data failed peers count : 1 [50 %]
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1
Send data never tried peers count : 10 [83.33333333333333 %]
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : F8:95:C7:87:85:54
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 7C:F9:0E:51:18:22

--------------- S5-1 --------------------- : 6
Find peers : 100% : 63894 ms, 99% : 63894 ms, 95 : 63894 ms, 90% : 61742 ms.
Result count 7, range 23333 ms to  63894 ms.
No send data results!
--------------- Thali Test (Galaxy A3) --------------------- : 7
Find peers : 100% : 92098 ms, 99% : 92098 ms, 95 : 92098 ms, 90% : 92098 ms.
Result count 5, range 81079 ms to  92098 ms.
--------------- XT1072 --------------------- : 8

Find peers : 100% : 92839 ms, 99% : 92839 ms, 95 : 92839 ms, 90% : 92832 ms.
Result count 8, range 2829 ms to  92839 ms.
--------------- G3s-1 --------------------- : 9
Find peers : 100% : 98958 ms, 99% : 98958 ms, 95 : 98958 ms, 90% : 86741 ms.
Result count 7, range 3669 ms to  98958 ms.

Send data : 100% : 50392 ms, 99% : 50392 ms, 95 : 50392 ms, 90% : 50392 ms.
Average data rate: 0.003 MB/s
Result count 2, range 25172 ms to  50392 ms.
Send data failed peers count : 1 [33.333333333333336 %]
- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
Send data never tried peers count : 9 [75 %]
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : 34:FC:EF:11:AE:67

- Peer ID : B0:C5:59:3F:75:69
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 7C:F9:0E:51:18:22
--------------- Thali Test (Galaxy S5) --------------------- : 10
Find peers : 100% : 97457 ms, 99% : 97457 ms, 95 : 97457 ms, 90% : 87683 ms.
Result count 9, range 20716 ms to  97457 ms.

Send data : 100% : 27369 ms, 99% : 27369 ms, 95 : 27369 ms, 90% : 27369 ms.
Average data rate: 0.004 MB/s
Result count 2, range 18419 ms to  27369 ms.
Send data failed peers count : 2 [50 %]
- Peer ID : 08:EC:A9:50:75:41, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
Send data never tried peers count : 8 [66.66666666666667 %]
- Peer ID : 34:FC:EF:11:AE:67

- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 08:EC:A9:50:76:27
--------------- Note4-1 --------------------- : 11

Find peers : 100% : 99669 ms, 99% : 99669 ms, 95 : 99669 ms, 90% : 61353 ms.
Result count 6, range 4868 ms to  99669 ms.
Send data : 100% : 59251 ms, 99% : 59251 ms, 95 : 59251 ms, 90% : 59251 ms.
Average data rate: 0.004 MB/s
Result count 3, range 9969 ms to  59251 ms.
Send data failed peers count : 1 [25 %]
- Peer ID : 44:80:EB:7B:5A:05, Tried : 1

Send data never tried peers count : 8 [66.66666666666667 %]
- Peer ID : F8:95:C7:87:85:54
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 7C:F9:0E:34:8A:A0

- Peer ID : 7C:F9:0E:51:18:22
--------------- A3-1 --------------------- : 12
Find peers : 100% : 90361 ms, 99% : 90361 ms, 95 : 90361 ms, 90% : 90006 ms.
Result count 9, range 3056 ms to  90361 ms.
No send data results!
--------------- Thali Test (Galaxy A5) --------------------- : 13
Find peers : 100% : 57643 ms, 99% : 57643 ms, 95 : 57643 ms, 90% : 45881 ms.
Result count 10, range 3814 ms to  57643 ms.
Send data : 100% : 32449 ms, 99% : 32449 ms, 95 : 32449 ms, 90% : 32449 ms.

Average data rate: 0.006 MB/s
Result count 2, range 3483 ms to  32449 ms.
Send data failed peers count : 2 [50 %]
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
Send data never tried peers count : 8 [66.66666666666667 %]
- Peer ID : 58:3F:54:73:64:C0

- Peer ID : F8:95:C7:87:85:54
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 08:EC:A9:50:76:27
--------------- Nexus 5 --------------------- : 14
Find peers : 100% : 72519 ms, 99% : 72519 ms, 95 : 72519 ms, 90% : 72519 ms.
Result count 4, range 13389 ms to  72519 ms.

Send data : 100% : 27948 ms, 99% : 27948 ms, 95 : 27948 ms, 90% : 27948 ms.
Average data rate: 0.004 MB/s
Result count 1, range 27948 ms to  27948 ms.
Send data failed peers count : 1 [50 %]
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
Send data never tried peers count : 10 [83.33333333333333 %]
- Peer ID : 08:EC:A9:50:75:41

- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : F8:95:C7:87:85:54

--------------- G4-1 --------------------- : 15
Find peers : 100% : 96495 ms, 99% : 96495 ms, 95 : 96495 ms, 90% : 96451 ms.
Result count 10, range 6279 ms to  96495 ms.
Send data : 100% : 48948 ms, 99% : 48948 ms, 95 : 48948 ms, 90% : 48948 ms.
Average data rate: 0.002 MB/s
Result count 1, range 48948 ms to  48948 ms.
Send data failed peers count : 2 [66.66666666666667 %]
- Peer ID : 34:FC:EF:11:AE:67, Tried : 1
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
Send data never tried peers count : 9 [75 %]
- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : F8:95:C7:87:85:54
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 08:EC:A9:50:76:27
--------------- G3-1 --------------------- : 16
Find peers : 100% : 97060 ms, 99% : 97060 ms, 95 : 97060 ms, 90% : 97039 ms.
Result count 6, range 55625 ms to  97060 ms.
Send data : 100% : 44995 ms, 99% : 44995 ms, 95 : 44995 ms, 90% : 44995 ms.
Average data rate: 0.005 MB/s
Result count 4, range 10086 ms to  44995 ms.
Send data failed peers count : 1 [20 %]
- Peer ID : 7C:F9:0E:51:18:22, Tried : 1
Send data never tried peers count : 7 [58.333333333333336 %]
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 7C:F9:0E:34:8A:A0
--------------- Combined ---------------------
Find peers : 100% : 99669 ms, 99% : 98958 ms, 95 : 96495 ms, 90% : 92098 ms.
Send data : 100% : 59251 ms, 99% : 59251 ms, 95 : 48948 ms, 90% : 32449 ms.
Average data rate: 0.007 MB/s
--------------- end of test report ---------------------

2016-01-07T09:53:27.511Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1.Xe0AvA==, peerAvailable=true, time=529], sendList=[name=Apple-Iphone6-1.Uf4Y7g==, time=4498, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1"]["sendList"][0], $ref=$["Apple-Iphone5-1"]["sendList"][0], name=Apple-Iphone5s-1.Waegsg==, time=5163, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1"]["sendList"][3], $ref=$["Apple-Iphone5-1"]["sendList"][3], name=Apple-IpadAir2-1.CdHxkA==, time=5243, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1"]["sendList"][6], $ref=$["Apple-Iphone5-1"]["sendList"][6]], failedPeer=[name=Apple-Iphone5-1.Xe0AvA==, time=51293, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone5-1"]["sendError"]["failedPeer"][0], $ref=$["Apple-Iphone5-1"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1.LQugrg==, peerAvailable=true, time=524], sendList=[name=Apple-Iphone5-1.XzilZw==, time=4042, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1"]["sendList"][0], $ref=$["Apple-IpadAir2-1"]["sendList"][0], name=Apple-Iphone6-1.Uf4Y7g==, time=4061, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1"]["sendList"][3], $ref=$["Apple-IpadAir2-1"]["sendList"][3], name=Apple-Iphone5s-1.Waegsg==, time=18924, result=OK, connections=2, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1"]["sendList"][6], $ref=$["Apple-IpadAir2-1"]["sendList"][6]], failedPeer=[name=Apple-IpadAir2-1.LQugrg==, time=51954, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-IpadAir2-1"]["sendError"]["failedPeer"][0], $ref=$["Apple-IpadAir2-1"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1.1I3u2A==, peerAvailable=true, time=652], sendList=[name=Apple-Iphone5-1.XzilZw==, time=3628, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1"]["sendList"][0], $ref=$["Apple-Iphone5s-1"]["sendList"][0], name=Apple-Iphone6-1.Uf4Y7g==, time=3696, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1"]["sendList"][3], $ref=$["Apple-Iphone5s-1"]["sendList"][3], name=Apple-IpadAir2-1.CdHxkA==, time=26132, result=OK, connections=2, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1"]["sendList"][6], $ref=$["Apple-Iphone5s-1"]["sendList"][6]], failedPeer=[name=Apple-IpadAir2-1.1I3u2A==, time=42328, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone5s-1"]["sendError"]["failedPeer"][0], $ref=$["Apple-Iphone5s-1"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1.qqPEfA==, peerAvailable=true, time=35], sendList=[], failedPeer=[name=Apple-IpadAir2-1.1I3u2A==, time=42352, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, name=Apple-Iphone6-1.qqPEfA==, time=40104, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone6-1"]["sendError"]["failedPeer"][0], $ref=$["Apple-Iphone6-1"]["sendError"]["failedPeer"][1], $ref=$["Apple-Iphone6-1"]["sendError"]["failedPeer"][0], $ref=$["Apple-Iphone6-1"]["sendError"]["failedPeer"][1]], notTriedList=[name=Apple-IpadAir2-1.CdHxkA==, time=0, result=Fail, $ref=$["Apple-Iphone6-1"]["sendError"]["notTriedList"][0], $ref=$["Apple-Iphone6-1"]["sendError"]["notTriedList"][0]], peersList=[peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=3262, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=41899, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=42630, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=83296, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=84497, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=85907], sendList=[name=34:FC:EF:11:AE:67, time=7741, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=44:80:EB:7B:5A:05, time=0, result=Fail], notTriedList=[connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail], peersList=[peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=23333, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=23336, peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=23577, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=23584, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=49416, peerName=Nexus 5, peerIdentifier=34:FC:EF:11:AE:67, peerAvailable=true, time=61742, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=63894], sendList=[], failedPeer=[connections=1, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=1, name=08:EC:A9:50:76:27, time=0, result=Fail], notTriedList=[connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail], peersList=[peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=81079, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=81511, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=83092, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=84486, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=92098], peersList=[peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=2829, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=2979, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=3035, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=3190, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=15164, peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=15745, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=false, time=92832, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=false, time=92839], peersList=[peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=3669, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=20055, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=62780, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=77651, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=85090, peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=86741, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=98958], sendList=[name=7C:F9:0E:37:96:AB, time=25172, result=OK, connections=2, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=58:3F:54:73:64:C0, time=50392, result=OK, connections=3, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=7C:F9:0E:34:8A:A0, time=0, result=Fail], notTriedList=[connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail], peersList=[peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=20716, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=63157, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=63207, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=73885, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=79864, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=85097, peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=85926, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=87683, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=97457], sendList=[name=F8:95:C7:87:85:54, time=18419, result=OK, connections=2, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:51:18:22, time=27369, result=OK, connections=2, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=1, name=00:F4:6F:30:E0:6C, time=0, result=Fail], notTriedList=[connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail], peersList=[peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=4868, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=30522, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=43355, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=49665, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=61353, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=99669], sendList=[name=F8:95:C7:87:3C:51, time=9969, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=58:3F:54:73:64:C0, time=10096, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:37:96:AB, time=59251, result=OK, connections=2, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=44:80:EB:7B:5A:05, time=0, result=Fail], notTriedList=[connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail], peersList=[peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=3056, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=3096, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=3216, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=3254, peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=3288, peerName=Nexus 5, peerIdentifier=34:FC:EF:11:AE:67, peerAvailable=true, time=3391, peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=52010, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=90006, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=90361], sendList=[], failedPeer=[connections=1, name=08:EC:A9:50:76:27, time=0, result=Fail], notTriedList=[connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail], peersList=[peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=3814, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=3910, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=17824, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=18071, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=33514, peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=33793, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=34411, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=44700, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=45881, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=57643], sendList=[name=B0:C5:59:3F:75:69, time=3483, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=08:EC:A9:50:75:41, time=32449, result=OK, connections=2, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=1, name=00:F4:6F:30:E0:6C, time=0, result=Fail], notTriedList=[connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail], peersList=[peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=13389, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=25330, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=72299, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=72519], sendList=[name=08:EC:A9:50:76:27, time=27948, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=7C:F9:0E:37:96:AB, time=0, result=Fail], notTriedList=[connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail], peersList=[peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=6279, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=47457, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=47472, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=47536, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=57190, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=57220, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=63352, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=77993, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=96451, peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=96495], sendList=[name=58:3F:54:73:64:C0, time=48948, result=OK, connections=3, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=1, name=00:F4:6F:30:E0:6C, time=0, result=Fail], notTriedList=[connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail], peersList=[peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=55625, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=61971, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=62254, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=69309, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=97039, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=97060], sendList=[name=F8:95:C7:87:85:54, time=10086, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=08:EC:A9:50:75:41, time=14316, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:37:96:AB, time=15203, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=34:FC:EF:11:AE:67, time=44995, result=OK, connections=3, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=7C:F9:0E:51:18:22, time=0, result=Fail], notTriedList=[connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail]

2016-01-07T09:53:27.560Z - debug: end to A5-1
2016-01-07T09:53:27.562Z - debug: end to S5-1
2016-01-07T09:53:27.564Z - debug: end to Thali Test (Galaxy A3)
2016-01-07T09:53:27.565Z - debug: end to XT1072
2016-01-07T09:53:27.566Z - debug: end to G3s-1

2016-01-07T09:53:27.569Z - debug: end to Thali Test (Galaxy S5)

2016-01-07T09:53:27.573Z - debug: end to Note4-1

2016-01-07T09:53:27.574Z - debug: end to A3-1
2016-01-07T09:53:27.575Z - debug: end to Thali Test (Galaxy A5)

2016-01-07T09:53:27.576Z - debug: end to Nexus 5
2016-01-07T09:53:27.577Z - debug: end to G4-1

2016-01-07T09:53:27.578Z - debug: end to S5mini-1

2016-01-07T09:53:27.579Z - debug: end to G3-1

2016-01-07T09:53:28.053Z - debug: Socket disconnected: transport close 13 (Nexus 5)

2016-01-07T09:53:28.768Z - debug: Socket disconnected: transport close 9 (Note4-1)

2016-01-07T09:53:28.860Z - debug: Socket disconnected: transport close 6 (Thali Test (Galaxy S5))

2016-01-07T09:53:29.069Z - debug: Socket disconnected: transport close 5 (G3s-1)

2016-01-07T09:53:29.136Z - debug: Socket disconnected: transport close 0 (A5-1)

2016-01-07T09:53:29.141Z - debug: Socket disconnected: transport close 16 (G3-1)

2016-01-07T09:53:29.200Z - debug: Socket disconnected: transport close 12 (Thali Test (Galaxy A5))

2016-01-07T09:53:29.458Z - debug: Socket disconnected: transport close 14 (G4-1)

2016-01-07T09:53:29.490Z - debug: Socket disconnected: transport close 4 (XT1072)

2016-01-07T09:53:29.518Z - debug: Socket disconnected: ping timeout 3 (Thali Test (Galaxy A3))

2016-01-07T09:53:29.710Z - debug: Socket disconnected: transport close 11 (A3-1)

2016-01-07T09:53:29.799Z - debug: Socket disconnected: transport close 1 (S5-1)

2016-01-07T09:53:31.339Z - debug: Device presented: XT1072 (android) perftest socket:17

2016-01-07T09:53:31.341Z - info: Updating existing device: XT1072 (51b7401e-f81a-4e7e-83eb-e79ec06cdc3c)

2016-01-07T09:53:31.372Z - info: Received results for {"name:":"XT1072","time":100106,"result":"TIMEOUT","sendList":[{"connections":1,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":1,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"}]} XT1072 android (3 left)

2016-01-07T10:15:38.222Z - debug: Socket disconnected: transport close 17 (XT1072)


 
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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/5531115118861c0_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/5531115118861c0_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/5531115118861c0_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/5531115118861c0_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/5531115118861c0_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/5531115118861c0_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/5531115118861c0_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/5531115118861c0_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/5531115118861c0_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/5531115118861c0_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/thali04_samsung-SM-G900F.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/5531115118861c0_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/5531115118861c0_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/5531115118861c0_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
STOP log received from  c5afcdcb Test has  SUCCEEDED
STOP log received from  4db5c8cc Test has  SUCCEEDED
Device test finished on 4db5c8cc 
Device test finished on c5afcdcb 
Android task is completed. [SUCCESS]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/5531115118861c0_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/5531115118861c0_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device HT574YC04723 app:com.test.thalitest code:null 
child process exited with code null on device HT574YC04723 
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:null 
child process exited with code null on device 4325e43f 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/5531115118861c0_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/5531115118861c0_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/5531115118861c0_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/5531115118861c0_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/5531115118861c0_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/5531115118861c0_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/5531115118861c0_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/5531115118861c0_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/iOS_Iphone5s-1.md)



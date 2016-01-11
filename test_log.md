#### Test 55613145dd493c6 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-11T12:59:26.463Z - info: listening on *:3000

2016-01-11T12:59:26.809Z - debug: Device presented: Thali Test (Galaxy A3) (android) perftest socket:0

2016-01-11T12:59:26.815Z - info: Setting start timeout to: 120000 (android)

2016-01-11T12:59:26.828Z - debug: Device presented: A5-1 (android) perftest socket:1

2016-01-11T12:59:27.064Z - debug: Device presented: Note4-1 (android) perftest socket:2

2016-01-11T12:59:27.198Z - debug: Device presented: G3s-1 (android) perftest socket:3

2016-01-11T12:59:27.664Z - debug: Device presented: A3-1 (android) perftest socket:4

2016-01-11T12:59:28.008Z - debug: Device presented: Nexus 5 (android) perftest socket:5

2016-01-11T12:59:28.355Z - debug: Device presented: Thali Test (Galaxy S5) (android) perftest socket:6

2016-01-11T12:59:28.427Z - debug: Device presented: G4-1 (android) perftest socket:7

2016-01-11T12:59:28.479Z - debug: Device presented: XT1072 (android) perftest socket:8

2016-01-11T12:59:28.521Z - debug: Device presented: Apple-Iphone6-1 (ios) perftest socket:9

2016-01-11T12:59:28.523Z - info: Setting start timeout to: 120000 (ios)

2016-01-11T12:59:29.341Z - debug: Device presented: HTC One M8s (android) perftest socket:10

2016-01-11T12:59:29.643Z - debug: Device presented: G3-1 (android) perftest socket:11

2016-01-11T12:59:30.001Z - debug: Device presented: Apple-IpadAir2-1 (ios) perftest socket:12

2016-01-11T12:59:30.655Z - debug: Device presented: S5-1 (android) perftest socket:13

2016-01-11T12:59:30.967Z - debug: Device presented: Apple-Iphone5-1 (ios) perftest socket:14

2016-01-11T12:59:31.143Z - debug: Device presented: Thali Test (Galaxy A5) (android) perftest socket:15

2016-01-11T12:59:31.551Z - debug: Device presented: Apple-Iphone5s-1 (ios) perftest socket:16

2016-01-11T12:59:31.552Z - info: Required number of devices presented

2016-01-11T12:59:31.558Z - info: Starting perf test run for platform: ios

2016-01-11T12:59:31.559Z - info: Using devices:

2016-01-11T12:59:31.560Z - info: Apple-Iphone6-1

2016-01-11T12:59:31.562Z - info: Apple-IpadAir2-1

2016-01-11T12:59:31.563Z - info: Apple-Iphone5-1

2016-01-11T12:59:31.564Z - info: Apple-Iphone5s-1

2016-01-11T12:59:31.567Z - info: Starting test: with 4 devices (ios)

2016-01-11T12:59:32.993Z - info: Received results for {"name:":"Apple-Iphone6-1","time":1071,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone5s-1.hXPtug==","peerAvailable":true,"time":1070}]} Apple-Iphone6-1 ios (3 left)

2016-01-11T12:59:33.024Z - info: Received results for {"name:":"Apple-IpadAir2-1","time":1078,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone5s-1.hXPtug==","peerAvailable":true,"time":1077}]} Apple-IpadAir2-1 ios (2 left)

2016-01-11T12:59:33.040Z - info: Received results for {"name:":"Apple-Iphone5-1","time":1290,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone6-1.4vXNuA==","peerAvailable":true,"time":1289}]} Apple-Iphone5-1 ios (1 left)

2016-01-11T12:59:33.153Z - info: Received results for {"name:":"Apple-Iphone5s-1","time":1234,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone6-1.4vXNuA==","peerAvailable":true,"time":1234}]} Apple-Iphone5s-1 ios (0 left)

2016-01-11T12:59:33.157Z - info: All test data retrieved for testFindPeers.js (ios)

2016-01-11T12:59:33.164Z - info: Remaining tests: testSendData.js

2016-01-11T12:59:33.166Z - info: Continuing to next test: testSendData.js

2016-01-11T12:59:33.167Z - info: Starting test: with 4 devices (ios)

2016-01-11T12:59:33.796Z - debug: Device presented: S5mini-1 (android) perftest socket:17

2016-01-11T12:59:34.599Z - debug: Socket disconnected: transport close 17 (S5mini-1)

2016-01-11T13:00:29.745Z - info: Received results for {"name:":"Apple-IpadAir2-1","time":55806,"result":"OK","sendList":[{"name":"Apple-Iphone5-1.b8hDBw==","time":41303,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-Iphone5-1.03CIBg==","time":6750,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1.yPThEg==","time":3923,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1.zQytdg==","time":3734,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-IpadAir2-1 ios (3 left)

2016-01-11T13:00:31.717Z - info: Received results for {"name:":"Apple-Iphone6-1","time":56971,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1.hXPtug==","time":41910,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-IpadAir2-1.oW56/g==","time":5990,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1.03CIBg==","time":5153,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1.yPThEg==","time":3665,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone6-1 ios (2 left)

2016-01-11T13:00:31.911Z - info: Received results for {"name:":"Apple-Iphone5s-1","time":57951,"result":"OK","sendList":[{"name":"Apple-Iphone6-1.4vXNuA==","time":46278,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-IpadAir2-1.oW56/g==","time":3825,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1.03CIBg==","time":4129,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1.zQytdg==","time":3444,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone5s-1 ios (1 left)

2016-01-11T13:00:31.917Z - info: Received results for {"name:":"Apple-Iphone5-1","time":58067,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1.hXPtug==","time":41942,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-IpadAir2-1.oW56/g==","time":6617,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1.yPThEg==","time":4794,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1.zQytdg==","time":4448,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone5-1 ios (0 left)

2016-01-11T13:00:31.918Z - info: All test data retrieved for testSendData.js (ios)

2016-01-11T13:00:31.925Z - info: ALL DONE !!!

{ 'name:': 'Apple-Iphone6-1',
  time: 1071,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5s-1.hXPtug==',
       peerAvailable: true,
       time: 1070 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 1078,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5s-1.hXPtug==',
       peerAvailable: true,
       time: 1077 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 1290,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1.4vXNuA==',
       peerAvailable: true,
       time: 1289 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 1234,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1.4vXNuA==',
       peerAvailable: true,
       time: 1234 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 56971,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5s-1.hXPtug==',
       time: 41910,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.oW56/g==',
       time: 5990,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.03CIBg==',
       time: 5153,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.yPThEg==',
       time: 3665,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 55806,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.b8hDBw==',
       time: 41303,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.03CIBg==',
       time: 6750,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.yPThEg==',
       time: 3923,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.zQytdg==',
       time: 3734,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 58067,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5s-1.hXPtug==',
       time: 41942,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.oW56/g==',
       time: 6617,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.yPThEg==',
       time: 4794,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.zQytdg==',
       time: 4448,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 57951,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1.4vXNuA==',
       time: 46278,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.oW56/g==',
       time: 3825,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.03CIBg==',
       time: 4129,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.zQytdg==',
       time: 3444,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

--------------- test report ---------------------
--------------- Apple-Iphone6-1 --------------------- : 1

Find peers : 100% : 1070 ms, 99% : 1070 ms, 95 : 1070 ms, 90% : 1070 ms.

Result count 1, range 1070 ms to  1070 ms.

Send data : 100% : 5990 ms, 99% : 5990 ms, 95 : 5990 ms, 90% : 5990 ms.

Average data rate: 0.02 MB/s

Result count 3, range 3665 ms to  5990 ms.

Send data failed peers count : 1 [25 %]

- Peer ID : Apple-Iphone5s-1.hXPtug==, Tried : 5

Send data never tried peers count : 0 [0 %]
--------------- Apple-IpadAir2-1 --------------------- : 2

Find peers : 100% : 1077 ms, 99% : 1077 ms, 95 : 1077 ms, 90% : 1077 ms.

Result count 1, range 1077 ms to  1077 ms.
Send data : 100% : 6750 ms, 99% : 6750 ms, 95 : 6750 ms, 90% : 6750 ms.
Average data rate: 0.021 MB/s
Result count 3, range 3734 ms to  6750 ms.

Send data failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone5-1.b8hDBw==, Tried : 5
Send data never tried peers count : 0 [0 %]

--------------- Apple-Iphone5-1 --------------------- : 3

Find peers : 100% : 1289 ms, 99% : 1289 ms, 95 : 1289 ms, 90% : 1289 ms.
Result count 1, range 1289 ms to  1289 ms.

Send data : 100% : 6617 ms, 99% : 6617 ms, 95 : 6617 ms, 90% : 6617 ms.
Average data rate: 0.019 MB/s
Result count 3, range 4448 ms to  6617 ms.
Send data failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone5s-1.hXPtug==, Tried : 5
Send data never tried peers count : 0 [0 %]
--------------- Apple-Iphone5s-1 --------------------- : 4

Find peers : 100% : 1234 ms, 99% : 1234 ms, 95 : 1234 ms, 90% : 1234 ms.
Result count 1, range 1234 ms to  1234 ms.

Send data : 100% : 4129 ms, 99% : 4129 ms, 95 : 4129 ms, 90% : 4129 ms.
Average data rate: 0.026 MB/s
Result count 3, range 3444 ms to  4129 ms.

Send data failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone6-1.4vXNuA==, Tried : 5
Send data never tried peers count : 0 [0 %]

--------------- Combined ---------------------

Find peers : 100% : 1289 ms, 99% : 1289 ms, 95 : 1289 ms, 90% : 1289 ms.

Send data : 100% : 6750 ms, 99% : 6750 ms, 95 : 6617 ms, 90% : 6617 ms.
Average data rate: 0.021 MB/s
--------------- end of test report ---------------------

2016-01-11T13:00:32.058Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-Iphone5s-1.hXPtug==, peerAvailable=true, time=1070], sendList=[name=Apple-Iphone5s-1.yPThEg==, time=3665, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1.03CIBg==, time=5153, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.oW56/g==, time=5990, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone5s-1.hXPtug==, time=41910, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5s-1.hXPtug==, peerAvailable=true, time=1077], sendList=[name=Apple-Iphone6-1.zQytdg==, time=3734, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5s-1.yPThEg==, time=3923, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1.03CIBg==, time=6750, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone5-1.b8hDBw==, time=41303, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1.4vXNuA==, peerAvailable=true, time=1289], sendList=[name=Apple-Iphone6-1.zQytdg==, time=4448, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5s-1.yPThEg==, time=4794, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.oW56/g==, time=6617, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone5s-1.hXPtug==, time=41942, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1.4vXNuA==, peerAvailable=true, time=1234], sendList=[name=Apple-Iphone6-1.zQytdg==, time=3444, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.oW56/g==, time=3825, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1.03CIBg==, time=4129, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone6-1.4vXNuA==, time=46278, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[]

2016-01-11T13:00:32.071Z - debug: end to Apple-Iphone6-1

2016-01-11T13:00:32.073Z - debug: end to Apple-IpadAir2-1

2016-01-11T13:00:32.074Z - debug: end to Apple-Iphone5-1

2016-01-11T13:00:32.076Z - debug: end to Apple-Iphone5s-1

2016-01-11T13:00:33.171Z - debug: state: android waiting

2016-01-11T13:00:33.172Z - debug: state: ios completed

2016-01-11T13:00:34.799Z - debug: Socket disconnected: transport close 12 (Apple-IpadAir2-1)

2016-01-11T13:00:35.819Z - debug: Socket disconnected: transport close 16 (Apple-Iphone5s-1)

2016-01-11T13:00:36.376Z - debug: Socket disconnected: transport close 14 (Apple-Iphone5-1)

2016-01-11T13:00:36.382Z - debug: Socket disconnected: transport close 9 (Apple-Iphone6-1)

2016-01-11T13:01:26.833Z - info: Start timeout elapsed for platform: android

2016-01-11T13:01:26.836Z - info: Starting perf test run for platform: android

2016-01-11T13:01:26.837Z - info: Using devices:

2016-01-11T13:01:26.838Z - info: Thali Test (Galaxy A3)
2016-01-11T13:01:26.839Z - info: A5-1

2016-01-11T13:01:26.840Z - info: Note4-1
2016-01-11T13:01:26.841Z - info: G3s-1

2016-01-11T13:01:26.841Z - info: A3-1
2016-01-11T13:01:26.842Z - info: Nexus 5

2016-01-11T13:01:26.843Z - info: Thali Test (Galaxy S5)
2016-01-11T13:01:26.843Z - info: G4-1

2016-01-11T13:01:26.844Z - info: XT1072
2016-01-11T13:01:26.845Z - info: HTC One M8s

2016-01-11T13:01:26.846Z - info: G3-1
2016-01-11T13:01:26.847Z - info: S5-1

2016-01-11T13:01:26.847Z - info: Thali Test (Galaxy A5)
2016-01-11T13:01:26.848Z - info: S5mini-1

2016-01-11T13:01:26.855Z - info: Starting test: with 14 devices (android)

2016-01-11T13:03:07.278Z - info: Received results for {"name:":"Nexus 5","time":100045,"result":"TIMEOUT","peersList":[{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":41868},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":84307}]} Nexus 5 android (13 left)

2016-01-11T13:03:07.347Z - info: Received results for {"name:":"Note4-1","time":100064,"result":"TIMEOUT","peersList":[{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":4799},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":5493},{"peerName":"XT1072","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":false,"time":94830},{"peerName":"HTC One M8s","peerIdentifier":"90:E7:C4:F6:69:77","peerAvailable":true,"time":11897},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":false,"time":94823},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":15444},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":21839},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":52103}]} Note4-1 android (12 left)

2016-01-11T13:03:07.425Z - info: Received results for {"name:":"XT1072","time":100150,"result":"TIMEOUT","peersList":[{"peerName":"HTC One M8s","peerIdentifier":"90:E7:C4:F6:69:77","peerAvailable":false,"time":62266},{"peerName":"Nexus 5","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":true,"time":2478},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":false,"time":92265},{"peerName":"Note4-1","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":false,"time":92264},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":3480},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":false,"time":92262},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":40812},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":40874}]} XT1072 android (11 left)

2016-01-11T13:03:07.741Z - info: Received results for {"name:":"Thali Test (Galaxy A5)","time":100059,"result":"TIMEOUT","peersList":[{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":40717},{"peerName":"XT1072","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true,"time":40788},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":42818},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":48699},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":61149},{"peerName":"Note4-1","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":61378},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":62447},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":73668}]} Thali Test (Galaxy A5) android (10 left)

2016-01-11T13:03:07.751Z - info: Received results for {"name:":"A5-1","time":100072,"result":"TIMEOUT","peersList":[{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":4099},{"peerName":"Note4-1","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":4262},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":44186},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":44773},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":66962},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":76405},{"peerName":"XT1072","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true,"time":76470}]} A5-1 android (9 left)

2016-01-11T13:03:07.808Z - info: Received results for {"name:":"G4-1","time":100078,"result":"TIMEOUT","peersList":[{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":13983},{"peerName":"XT1072","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true,"time":38878},{"peerName":"Note4-1","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":52210},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":52220},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":62151},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":74580},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":87271},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":94777}]} G4-1 android (8 left)

2016-01-11T13:03:07.842Z - info: Received results for {"name:":"Thali Test (Galaxy A3)","time":100073,"result":"TIMEOUT","peersList":[{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":41178},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":78468},{"peerName":"XT1072","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true,"time":78529},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":79689},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":81324},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":81589},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":92609},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":92742}]} Thali Test (Galaxy A3) android (7 left)

2016-01-11T13:03:07.951Z - info: Received results for {"name:":"G3s-1","time":100130,"result":"TIMEOUT","peersList":[{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":21600},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":57245}]} G3s-1 android (6 left)

2016-01-11T13:03:07.961Z - info: Received results for {"name:":"A3-1","time":100071,"result":"TIMEOUT","peersList":[{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":3641},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":3694},{"peerName":"XT1072","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true,"time":4319},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":11510},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":14202},{"peerName":"Note4-1","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":27902},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":37738},{"peerName":"Nexus 5","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":true,"time":88529}]} A3-1 android (5 left)

2016-01-11T13:03:09.668Z - info: Received results for {"name:":"G3-1","time":100082,"result":"TIMEOUT","peersList":[{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":1737},{"peerName":"Nexus 5","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":true,"time":1762},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":55609},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":69034},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":80653},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":80688},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":96184}]} G3-1 android (4 left)

2016-01-11T13:03:09.772Z - info: Received results for {"name:":"Thali Test (Galaxy S5)","time":100137,"result":"TIMEOUT","peersList":[{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":3915},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":73899},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":94187}]} Thali Test (Galaxy S5) android (3 left)

2016-01-11T13:03:10.143Z - info: Received results for {"name:":"S5-1","time":100128,"result":"TIMEOUT","peersList":[{"peerName":"Note4-1","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":19261},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":19268},{"peerName":"G3s-1","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":19475},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":19649},{"peerName":"XT1072","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true,"time":35653},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":87027},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":98769}]} S5-1 android (2 left)

2016-01-11T13:03:26.902Z - info: server timeout for test: testFindPeers.js (android)

2016-01-11T13:03:26.905Z - info: All test data retrieved for testFindPeers.js (android)

2016-01-11T13:03:26.915Z - info: No results from HTC One M8s

2016-01-11T13:03:26.920Z - info: No results from S5mini-1

2016-01-11T13:03:26.921Z - info: Remaining tests: testSendData.js

2016-01-11T13:03:26.924Z - info: Continuing to next test: testSendData.js
2016-01-11T13:03:26.925Z - info: Starting test: with 14 devices (android)

2016-01-11T13:03:51.732Z - debug: Socket disconnected: ping timeout 10 (HTC One M8s)

2016-01-11T13:04:54.163Z - debug: Device presented: G3s-1 (android) perftest socket:18

2016-01-11T13:04:54.165Z - info: Updating existing device: G3s-1 (277dd2a4-7c78-4248-ada6-46744b8b658e)

2016-01-11T13:05:07.207Z - info: Received results for {"name:":"G3s-1","time":100126,"result":"TIMEOUT","sendList":[{"name":"08:EC:A9:50:76:27","time":59498,"result":"OK","connections":4,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":4186,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"34:FC:EF:11:AE:67","time":6295,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"}]} G3s-1 android (13 left)

2016-01-11T13:05:07.253Z - info: Received results for {"name:":"Nexus 5","time":100052,"result":"TIMEOUT","sendList":[{"name":"08:EC:A9:50:75:41","time":37438,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"}]} Nexus 5 android (12 left)

2016-01-11T13:05:07.299Z - info: Received results for {"name:":"Thali Test (Galaxy A5)","time":100089,"result":"TIMEOUT","sendList":[{"name":"34:FC:EF:11:AE:67","time":10536,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":11301,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"}]} Thali Test (Galaxy A5) android (11 left)

2016-01-11T13:05:07.306Z - info: Received results for {"name:":"G4-1","time":100071,"result":"TIMEOUT","sendList":[{"connections":1,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"}]} G4-1 android (10 left)

2016-01-11T13:05:07.420Z - info: Received results for {"name:":"Thali Test (Galaxy S5)","time":100141,"result":"TIMEOUT","sendList":[{"name":"F8:95:C7:87:85:54","time":5802,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":1,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"}]} Thali Test (Galaxy S5) android (9 left)

2016-01-11T13:05:07.536Z - info: Received results for {"name:":"Thali Test (Galaxy A3)","time":100087,"result":"TIMEOUT","sendList":[{"name":"F8:95:C7:87:3C:51","time":5228,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":1,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"}]} Thali Test (Galaxy A3) android (8 left)

2016-01-11T13:05:08.673Z - info: Received results for {"name:":"A3-1","time":100072,"result":"TIMEOUT","sendList":[{"name":"B0:C5:59:3F:75:69","time":18335,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":75384,"result":"OK","connections":4,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"}]} A3-1 android (7 left)

2016-01-11T13:05:10.971Z - info: Received results for {"name:":"S5-1","time":100106,"result":"TIMEOUT","sendList":[{"connections":1,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"}]} S5-1 android (6 left)

2016-01-11T13:05:11.875Z - info: Received results for {"name:":"G3-1","time":100104,"result":"TIMEOUT","sendList":[{"name":"34:FC:EF:11:AE:67","time":32190,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:75:41","time":10615,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":1,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"}]} G3-1 android (5 left)

2016-01-11T13:05:26.930Z - info: server timeout for test: testSendData.js (android)

2016-01-11T13:05:26.931Z - info: All test data retrieved for testSendData.js (android)

2016-01-11T13:05:26.936Z - info: No results from A5-1

2016-01-11T13:05:26.938Z - info: No results from Note4-1

2016-01-11T13:05:26.944Z - info: No results from XT1072

2016-01-11T13:05:26.946Z - info: No results from HTC One M8s

2016-01-11T13:05:26.950Z - info: No results from S5mini-1

2016-01-11T13:05:26.951Z - info: ALL DONE !!!
{ 'name:': 'Apple-Iphone6-1',
  time: 1071,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5s-1.hXPtug==',
       peerAvailable: true,
       time: 1070 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 1078,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5s-1.hXPtug==',
       peerAvailable: true,
       time: 1077 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 1290,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1.4vXNuA==',
       peerAvailable: true,
       time: 1289 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 1234,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1.4vXNuA==',
       peerAvailable: true,
       time: 1234 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 56971,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5s-1.hXPtug==',
       time: 41910,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.oW56/g==',
       time: 5990,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.03CIBg==',
       time: 5153,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.yPThEg==',
       time: 3665,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 55806,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1.b8hDBw==',
       time: 41303,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1.03CIBg==',
       time: 6750,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.yPThEg==',
       time: 3923,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.zQytdg==',
       time: 3734,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 58067,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5s-1.hXPtug==',
       time: 41942,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.oW56/g==',
       time: 6617,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1.yPThEg==',
       time: 4794,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.zQytdg==',
       time: 4448,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1',
  time: 57951,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1.4vXNuA==',
       time: 46278,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1.oW56/g==',
       time: 3825,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1.03CIBg==',
       time: 4129,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1.zQytdg==',
       time: 3444,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Thali Test (Galaxy A3)',
  time: 100073,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 41178 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 78468 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 78529 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 79689 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 81324 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 81589 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 92609 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 92742 } ] }

{ 'name:': 'A5-1',
  time: 100072,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 4099 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 4262 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 44186 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 44773 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 66962 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 76405 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 76470 } ] }

{ 'name:': 'Note4-1',
  time: 100064,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 4799 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 5493 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: false,
       time: 94830 },
     { peerName: 'HTC One M8s',
       peerIdentifier: '90:E7:C4:F6:69:77',
       peerAvailable: true,
       time: 11897 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: false,
       time: 94823 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 15444 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 21839 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 52103 } ] }

{ 'name:': 'G3s-1',
  time: 100130,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 21600 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 57245 } ] }

{ 'name:': 'A3-1',
  time: 100071,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 3641 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 3694 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 4319 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 11510 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 14202 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 27902 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 37738 },
     { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 88529 } ] }

{ 'name:': 'Nexus 5',
  time: 100045,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 41868 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 84307 } ] }

{ 'name:': 'Thali Test (Galaxy S5)',
  time: 100137,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 3915 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 73899 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 94187 } ] }

{ 'name:': 'G4-1',
  time: 100078,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 13983 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 38878 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 52210 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 52220 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 62151 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 74580 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 87271 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 94777 } ] }

{ 'name:': 'XT1072',
  time: 100150,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'HTC One M8s',
       peerIdentifier: '90:E7:C4:F6:69:77',
       peerAvailable: false,
       time: 62266 },
     { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 2478 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: false,
       time: 92265 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: false,
       time: 92264 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 3480 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: false,
       time: 92262 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 40812 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 40874 } ] }

{ 'name:': 'G3-1',
  time: 100082,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 1737 },
     { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 1762 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 55609 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 69034 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 80653 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 80688 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 96184 } ] }

{ 'name:': 'S5-1',
  time: 100128,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 19261 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 19268 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 19475 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 19649 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 35653 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 87027 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 98769 } ] }

{ 'name:': 'Thali Test (Galaxy A5)',
  time: 100059,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 40717 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 40788 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 42818 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 48699 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 61149 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 61378 },
     { peerName: 'G3s-1',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 62447 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 73668 } ] }

{ 'name:': 'Thali Test (Galaxy A3)',
  time: 100087,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'F8:95:C7:87:3C:51',
       time: 5228,
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
       name: '7C:F9:0E:37:96:AB',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:51:18:22',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:34:8A:A0',
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
       name: 'F8:95:C7:87:85:54',
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
       name: 'E0:DB:10:14:E2:C0',
       time: 0,
       result: 'Fail' },
     { connections: 1,
       name: 'B0:C5:59:3F:75:69',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'G3s-1',
  time: 100126,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '08:EC:A9:50:76:27',
       time: 59498,
       result: 'OK',
       connections: 4,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'E0:DB:10:14:E2:C0',
       time: 4186,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '34:FC:EF:11:AE:67',
       time: 6295,
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
       name: '90:E7:C4:F6:69:77',
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
       name: 'F8:95:C7:87:3C:51',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '44:80:EB:7B:5A:05',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'A3-1',
  time: 100072,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'B0:C5:59:3F:75:69',
       time: 18335,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:3C:51',
       time: 75384,
       result: 'OK',
       connections: 4,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
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
       name: '44:80:EB:7B:5A:05',
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
       name: '08:EC:A9:50:76:27',
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
       name: '34:FC:EF:11:AE:67',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Nexus 5',
  time: 100052,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '08:EC:A9:50:75:41',
       time: 37438,
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
       name: '90:E7:C4:F6:69:77',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '44:80:EB:7B:5A:05',
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
       name: 'F8:95:C7:87:3C:51',
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
       name: '7C:F9:0E:37:96:AB',
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
       name: 'E0:DB:10:14:E2:C0',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Thali Test (Galaxy S5)',
  time: 100141,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'F8:95:C7:87:85:54',
       time: 5802,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: 'F8:95:C7:87:3C:51',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '90:E7:C4:F6:69:77',
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
       name: '58:3F:54:73:64:C0',
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
       name: '00:F4:6F:30:E0:6C',
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
     { connections: 1,
       name: '7C:F9:0E:37:96:AB',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'G4-1',
  time: 100071,
  result: 'TIMEOUT',
  sendList: 
   [ { connections: 1,
       name: '90:E7:C4:F6:69:77',
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
       name: '34:FC:EF:11:AE:67',
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
       name: '00:F4:6F:30:E0:6C',
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
       name: 'E0:DB:10:14:E2:C0',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'G3-1',
  time: 100104,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '34:FC:EF:11:AE:67',
       time: 32190,
       result: 'OK',
       connections: 2,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '08:EC:A9:50:75:41',
       time: 10615,
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
       name: 'B0:C5:59:3F:75:69',
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
       name: '7C:F9:0E:34:8A:A0',
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
       name: 'F8:95:C7:87:3C:51',
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
     { connections: 1,
       name: '90:E7:C4:F6:69:77',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'S5-1',
  time: 100106,
  result: 'TIMEOUT',
  sendList: 
   [ { connections: 1,
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
       name: '44:80:EB:7B:5A:05',
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
       name: 'F8:95:C7:87:3C:51',
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
       name: 'F8:95:C7:87:85:54',
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
       name: '08:EC:A9:50:75:41',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Thali Test (Galaxy A5)',
  time: 100089,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '34:FC:EF:11:AE:67',
       time: 10536,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:85:54',
       time: 11301,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: 'B0:C5:59:3F:75:69',
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
       name: '58:3F:54:73:64:C0',
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
       name: '00:F4:6F:30:E0:6C',
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
       name: 'F8:95:C7:87:3C:51',
       time: 0,
       result: 'Fail' } ] }

--------------- test report ---------------------
--------------- Apple-Iphone6-1 --------------------- : 1
Find peers : 100% : 1070 ms, 99% : 1070 ms, 95 : 1070 ms, 90% : 1070 ms.
Result count 1, range 1070 ms to  1070 ms.

Send data : 100% : 5990 ms, 99% : 5990 ms, 95 : 5990 ms, 90% : 5990 ms.
Average data rate: 0.02 MB/s

Result count 3, range 3665 ms to  5990 ms.
Send data failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone5s-1.hXPtug==, Tried : 5
Send data never tried peers count : 0 [0 %]

--------------- Apple-IpadAir2-1 --------------------- : 2
Find peers : 100% : 1077 ms, 99% : 1077 ms, 95 : 1077 ms, 90% : 1077 ms.
Result count 1, range 1077 ms to  1077 ms.

Send data : 100% : 6750 ms, 99% : 6750 ms, 95 : 6750 ms, 90% : 6750 ms.
Average data rate: 0.021 MB/s
Result count 3, range 3734 ms to  6750 ms.

Send data failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone5-1.b8hDBw==, Tried : 5
Send data never tried peers count : 0 [0 %]

--------------- Apple-Iphone5-1 --------------------- : 3
Find peers : 100% : 1289 ms, 99% : 1289 ms, 95 : 1289 ms, 90% : 1289 ms.
Result count 1, range 1289 ms to  1289 ms.

Send data : 100% : 6617 ms, 99% : 6617 ms, 95 : 6617 ms, 90% : 6617 ms.
Average data rate: 0.019 MB/s
Result count 3, range 4448 ms to  6617 ms.
Send data failed peers count : 1 [25 %]

- Peer ID : Apple-Iphone5s-1.hXPtug==, Tried : 5
Send data never tried peers count : 0 [0 %]
--------------- Apple-Iphone5s-1 --------------------- : 4
Find peers : 100% : 1234 ms, 99% : 1234 ms, 95 : 1234 ms, 90% : 1234 ms.

Result count 1, range 1234 ms to  1234 ms.
Send data : 100% : 4129 ms, 99% : 4129 ms, 95 : 4129 ms, 90% : 4129 ms.
Average data rate: 0.026 MB/s
Result count 3, range 3444 ms to  4129 ms.

Send data failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone6-1.4vXNuA==, Tried : 5
Send data never tried peers count : 0 [0 %]
--------------- Thali Test (Galaxy A3) --------------------- : 5

Find peers : 100% : 92742 ms, 99% : 92742 ms, 95 : 92742 ms, 90% : 92609 ms.
Result count 8, range 41178 ms to  92742 ms.

Send data : 100% : 5228 ms, 99% : 5228 ms, 95 : 5228 ms, 90% : 5228 ms.
Average data rate: 0.019 MB/s

Result count 1, range 5228 ms to  5228 ms.

Send data failed peers count : 2 [66.66666666666667 %]
- Peer ID : 90:E7:C4:F6:69:77, Tried : 1
- Peer ID : B0:C5:59:3F:75:69, Tried : 1

Send data never tried peers count : 10 [76.92307692307692 %]
- Peer ID : 7C:F9:0E:37:96:AB

- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 58:3F:54:73:64:C0

- Peer ID : F8:95:C7:87:85:54

- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : E0:DB:10:14:E2:C0
--------------- A5-1 --------------------- : 6

Find peers : 100% : 76470 ms, 99% : 76470 ms, 95 : 76470 ms, 90% : 76405 ms.
Result count 7, range 4099 ms to  76470 ms.
--------------- Note4-1 --------------------- : 7
Find peers : 100% : 94830 ms, 99% : 94830 ms, 95 : 94830 ms, 90% : 94823 ms.
Result count 8, range 4799 ms to  94830 ms.
--------------- G3s-1 --------------------- : 8
Find peers : 100% : 57245 ms, 99% : 57245 ms, 95 : 57245 ms, 90% : 57245 ms.
Result count 2, range 21600 ms to  57245 ms.
Send data : 100% : 59498 ms, 99% : 59498 ms, 95 : 59498 ms, 90% : 59498 ms.
Average data rate: 0.004 MB/s
Result count 3, range 4186 ms to  59498 ms.
Send data failed peers count : 1 [25 %]
- Peer ID : 7C:F9:0E:51:18:22, Tried : 1
Send data never tried peers count : 9 [69.23076923076923 %]
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 90:E7:C4:F6:69:77
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 44:80:EB:7B:5A:05
--------------- A3-1 --------------------- : 9
Find peers : 100% : 88529 ms, 99% : 88529 ms, 95 : 88529 ms, 90% : 37738 ms.
Result count 8, range 3641 ms to  88529 ms.
Send data : 100% : 75384 ms, 99% : 75384 ms, 95 : 75384 ms, 90% : 75384 ms.
Average data rate: 0.002 MB/s
Result count 2, range 18335 ms to  75384 ms.
Send data failed peers count : 1 [33.333333333333336 %]
- Peer ID : 90:E7:C4:F6:69:77, Tried : 1
Send data never tried peers count : 10 [76.92307692307692 %]
- Peer ID : F8:95:C7:87:85:54
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 34:FC:EF:11:AE:67
--------------- Nexus 5 --------------------- : 10
Find peers : 100% : 84307 ms, 99% : 84307 ms, 95 : 84307 ms, 90% : 84307 ms.
Result count 2, range 41868 ms to  84307 ms.
Send data : 100% : 37438 ms, 99% : 37438 ms, 95 : 37438 ms, 90% : 37438 ms.
Average data rate: 0.003 MB/s
Result count 1, range 37438 ms to  37438 ms.
Send data failed peers count : 1 [50 %]
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
Send data never tried peers count : 11 [84.61538461538461 %]
- Peer ID : 90:E7:C4:F6:69:77
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : F8:95:C7:87:85:54
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : E0:DB:10:14:E2:C0
--------------- Thali Test (Galaxy S5) --------------------- : 11
Find peers : 100% : 94187 ms, 99% : 94187 ms, 95 : 94187 ms, 90% : 94187 ms.
Result count 3, range 3915 ms to  94187 ms.
Send data : 100% : 5802 ms, 99% : 5802 ms, 95 : 5802 ms, 90% : 5802 ms.
Average data rate: 0.017 MB/s
Result count 1, range 5802 ms to  5802 ms.
Send data failed peers count : 2 [66.66666666666667 %]
- Peer ID : F8:95:C7:87:3C:51, Tried : 1
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1

Send data never tried peers count : 10 [76.92307692307692 %]
- Peer ID : 90:E7:C4:F6:69:77
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 44:80:EB:7B:5A:05

--------------- G4-1 --------------------- : 12
Find peers : 100% : 94777 ms, 99% : 94777 ms, 95 : 94777 ms, 90% : 87271 ms.
Result count 8, range 13983 ms to  94777 ms.

No send data results!
--------------- XT1072 --------------------- : 13
Find peers : 100% : 92265 ms, 99% : 92265 ms, 95 : 92265 ms, 90% : 92264 ms.
Result count 8, range 2478 ms to  92265 ms.

--------------- G3-1 --------------------- : 14

Find peers : 100% : 96184 ms, 99% : 96184 ms, 95 : 96184 ms, 90% : 80688 ms.
Result count 7, range 1737 ms to  96184 ms.
Send data : 100% : 32190 ms, 99% : 32190 ms, 95 : 32190 ms, 90% : 32190 ms.
Average data rate: 0.005 MB/s
Result count 2, range 10615 ms to  32190 ms.
Send data failed peers count : 2 [50 %]
- Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
- Peer ID : 90:E7:C4:F6:69:77, Tried : 1
Send data never tried peers count : 9 [69.23076923076923 %]
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : F8:95:C7:87:85:54
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 08:EC:A9:50:76:27
--------------- S5-1 --------------------- : 15

Find peers : 100% : 98769 ms, 99% : 98769 ms, 95 : 98769 ms, 90% : 87027 ms.
Result count 7, range 19261 ms to  98769 ms.
No send data results!
--------------- Thali Test (Galaxy A5) --------------------- : 16
Find peers : 100% : 73668 ms, 99% : 73668 ms, 95 : 73668 ms, 90% : 62447 ms.
Result count 8, range 40717 ms to  73668 ms.

Send data : 100% : 11301 ms, 99% : 11301 ms, 95 : 11301 ms, 90% : 11301 ms.
Average data rate: 0.009 MB/s
Result count 2, range 10536 ms to  11301 ms.
Send data failed peers count : 1 [33.333333333333336 %]

- Peer ID : B0:C5:59:3F:75:69, Tried : 1
Send data never tried peers count : 10 [76.92307692307692 %]
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 58:3F:54:73:64:C0

- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 08:EC:A9:50:75:41

- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 90:E7:C4:F6:69:77
- Peer ID : F8:95:C7:87:3C:51
--------------- Combined ---------------------

Find peers : 100% : 98769 ms, 99% : 96184 ms, 95 : 94777 ms, 90% : 92265 ms.

Send data : 100% : 75384 ms, 99% : 75384 ms, 95 : 59498 ms, 90% : 37438 ms.

Average data rate: 0.007 MB/s

--------------- end of test report ---------------------

2016-01-11T13:05:27.342Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-Iphone5s-1.hXPtug==, peerAvailable=true, time=1070], sendList=[name=Apple-Iphone5s-1.yPThEg==, time=3665, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1.03CIBg==, time=5153, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.oW56/g==, time=5990, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone5s-1.hXPtug==, time=41910, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5s-1.hXPtug==, peerAvailable=true, time=1077], sendList=[name=Apple-Iphone6-1.zQytdg==, time=3734, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5s-1.yPThEg==, time=3923, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1.03CIBg==, time=6750, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone5-1.b8hDBw==, time=41303, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1.4vXNuA==, peerAvailable=true, time=1289], sendList=[name=Apple-Iphone6-1.zQytdg==, time=4448, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5s-1.yPThEg==, time=4794, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.oW56/g==, time=6617, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone5s-1.hXPtug==, time=41942, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1.4vXNuA==, peerAvailable=true, time=1234], sendList=[name=Apple-Iphone6-1.zQytdg==, time=3444, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1.oW56/g==, time=3825, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1.03CIBg==, time=4129, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone6-1.4vXNuA==, time=46278, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=41178, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=78468, peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=78529, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=79689, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=81324, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=81589, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=92609, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=92742], sendList=[name=F8:95:C7:87:3C:51, time=5228, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=90:E7:C4:F6:69:77, time=0, result=Fail, connections=1, name=B0:C5:59:3F:75:69, time=0, result=Fail], notTriedList=[connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail], peersList=[peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=4099, peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=4262, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=44186, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=44773, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=66962, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=76405, peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=76470], peersList=[peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=4799, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=5493, peerName=HTC One M8s, peerIdentifier=90:E7:C4:F6:69:77, peerAvailable=true, time=11897, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=15444, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=21839, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=52103, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=false, time=94823, peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=false, time=94830], peersList=[peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=21600, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=57245], sendList=[name=E0:DB:10:14:E2:C0, time=4186, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=34:FC:EF:11:AE:67, time=6295, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=08:EC:A9:50:76:27, time=59498, result=OK, connections=4, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=7C:F9:0E:51:18:22, time=0, result=Fail], notTriedList=[connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=90:E7:C4:F6:69:77, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail], peersList=[peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=3641, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=3694, peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=4319, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=11510, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=14202, peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=27902, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=37738, peerName=Nexus 5, peerIdentifier=34:FC:EF:11:AE:67, peerAvailable=true, time=88529], sendList=[name=B0:C5:59:3F:75:69, time=18335, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=F8:95:C7:87:3C:51, time=75384, result=OK, connections=4, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=90:E7:C4:F6:69:77, time=0, result=Fail], notTriedList=[connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail], peersList=[peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=41868, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=84307], sendList=[name=08:EC:A9:50:75:41, time=37438, result=OK, connections=2, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=00:F4:6F:30:E0:6C, time=0, result=Fail], notTriedList=[connections=0, name=90:E7:C4:F6:69:77, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail], peersList=[peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=3915, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=73899, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=94187], sendList=[name=F8:95:C7:87:85:54, time=5802, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=1, name=7C:F9:0E:37:96:AB, time=0, result=Fail], notTriedList=[connections=0, name=90:E7:C4:F6:69:77, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail], peersList=[peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=13983, peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=38878, peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=52210, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=52220, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=62151, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=74580, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=87271, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=94777], sendList=[], failedPeer=[connections=1, name=90:E7:C4:F6:69:77, time=0, result=Fail], notTriedList=[connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail], peersList=[peerName=Nexus 5, peerIdentifier=34:FC:EF:11:AE:67, peerAvailable=true, time=2478, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=3480, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=40812, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=40874, peerName=HTC One M8s, peerIdentifier=90:E7:C4:F6:69:77, peerAvailable=false, time=62266, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=false, time=92262, peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=false, time=92264, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=false, time=92265], peersList=[peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=1737, peerName=Nexus 5, peerIdentifier=34:FC:EF:11:AE:67, peerAvailable=true, time=1762, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=55609, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=69034, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=80653, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=80688, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=96184], sendList=[name=08:EC:A9:50:75:41, time=10615, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=34:FC:EF:11:AE:67, time=32190, result=OK, connections=2, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=1, name=90:E7:C4:F6:69:77, time=0, result=Fail], notTriedList=[connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail], peersList=[peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=19261, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=19268, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=19475, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=19649, peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=35653, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=87027, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=98769], sendList=[], failedPeer=[connections=1, name=00:F4:6F:30:E0:6C, time=0, result=Fail], notTriedList=[connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=90:E7:C4:F6:69:77, time=0, result=Fail, connections=0, name=F8:95:C7:87:85:54, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail], peersList=[peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=40717, peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=40788, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=42818, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=48699, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=61149, peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=61378, peerName=G3s-1, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=62447, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=73668], sendList=[name=34:FC:EF:11:AE:67, time=10536, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=F8:95:C7:87:85:54, time=11301, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=B0:C5:59:3F:75:69, time=0, result=Fail], notTriedList=[connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=90:E7:C4:F6:69:77, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail]

2016-01-11T13:05:27.486Z - debug: end to Thali Test (Galaxy A3)
2016-01-11T13:05:27.488Z - debug: end to A5-1

2016-01-11T13:05:27.490Z - debug: end to Note4-1

2016-01-11T13:05:27.493Z - debug: end to G3s-1

2016-01-11T13:05:27.498Z - debug: end to A3-1

2016-01-11T13:05:27.499Z - debug: end to Nexus 5

2016-01-11T13:05:27.500Z - debug: end to Thali Test (Galaxy S5)

2016-01-11T13:05:27.502Z - debug: end to G4-1

2016-01-11T13:05:27.503Z - debug: end to XT1072

2016-01-11T13:05:27.504Z - debug: end to HTC One M8s

2016-01-11T13:05:27.506Z - debug: end to G3-1

2016-01-11T13:05:27.507Z - debug: end to S5-1

2016-01-11T13:05:27.508Z - debug: end to Thali Test (Galaxy A5)

2016-01-11T13:05:27.510Z - debug: end to S5mini-1

2016-01-11T13:05:28.489Z - debug: Socket disconnected: ping timeout 1 (A5-1)

2016-01-11T13:05:28.494Z - debug: Socket disconnected: transport close 5 (Nexus 5)

2016-01-11T13:05:28.558Z - debug: Socket disconnected: transport close 0 (Thali Test (Galaxy A3))

2016-01-11T13:05:28.785Z - debug: Socket disconnected: ping timeout 8 (XT1072)

2016-01-11T13:05:28.897Z - debug: Socket disconnected: transport close 13 (S5-1)

2016-01-11T13:05:29.647Z - debug: Socket disconnected: transport close 4 (A3-1)

2016-01-11T13:05:30.201Z - debug: Socket disconnected: transport close 6 (Thali Test (Galaxy S5))

2016-01-11T13:05:31.047Z - debug: Socket disconnected: transport close 11 (G3-1)

2016-01-11T13:05:31.203Z - debug: Socket disconnected: transport close 18 (G3s-1)

2016-01-11T13:05:31.218Z - debug: Socket disconnected: transport close 15 (Thali Test (Galaxy A5))

2016-01-11T13:05:46.773Z - debug: Socket disconnected: transport close 7 (G4-1)

2016-01-11T13:05:49.191Z - debug: Device presented: G4-1 (android) perftest socket:19

2016-01-11T13:05:49.193Z - info: Updating existing device: G4-1 (14d04703-b68a-4e84-90ef-00713b924d2c)

2016-01-11T13:05:52.670Z - debug: Socket disconnected: ping timeout 3 (G3s-1)

2016-01-11T13:05:53.511Z - debug: Socket disconnected: ping timeout 2 (Note4-1)

2016-01-11T13:25:59.547Z - debug: Socket disconnected: transport close 19 (G4-1)


 
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
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:0 
child process exited with code 0 on device LGH8153b36be34 
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:null 
child process exited with code null on device f56ad48d 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/55613145dd493c6_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/55613145dd493c6_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/55613145dd493c6_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/55613145dd493c6_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/55613145dd493c6_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/55613145dd493c6_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/55613145dd493c6_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/55613145dd493c6_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/55613145dd493c6_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/55613145dd493c6_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali04_samsung-SM-G900F.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/55613145dd493c6_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/55613145dd493c6_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/55613145dd493c6_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
STOP log received from  c5afcdcb Test has  SUCCEEDED
STOP log received from  4db5c8cc Test has  SUCCEEDED
Device test finished on c5afcdcb 
Device test finished on 4db5c8cc 
Android task is completed. [SUCCESS]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/55613145dd493c6_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/55613145dd493c6_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/55613145dd493c6_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/55613145dd493c6_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device CC51WYC03425 app:com.test.thalitest code:0 
child process exited with code 0 on device CC51WYC03425 
Error! Unexpected exit on device 0c6a0f3c0bdb4e77 app:com.test.thalitest code:0 
child process exited with code 0 on device 0c6a0f3c0bdb4e77 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/55613145dd493c6_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/55613145dd493c6_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/55613145dd493c6_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/55613145dd493c6_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/55613145dd493c6_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/55613145dd493c6_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/iOS_Iphone5s-1.md)



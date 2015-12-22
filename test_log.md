#### Test 543122982543be8 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2015-12-22T00:54:44.646Z - info: listening on *:3000

2015-12-22T00:54:45.070Z - debug: Device presented: LGE-Nexus 5_PT1510 (android) perftest socket:0

2015-12-22T00:54:45.077Z - info: Setting start timeout to: 120000 (android)

2015-12-22T00:54:45.084Z - debug: Device presented: HTC-HTC One M8s_PT375 (android) perftest socket:1

2015-12-22T00:54:45.438Z - debug: Device presented: motorola-XT1072_PT3784 (android) perftest socket:2

2015-12-22T00:54:45.665Z - debug: Device presented: Apple-Iphone6-1_PT4682 (ios) perftest socket:3

2015-12-22T00:54:45.668Z - info: Setting start timeout to: 120000 (ios)

2015-12-22T00:54:45.963Z - debug: Device presented: LGE-LG-H815_PT8123 (android) perftest socket:5

2015-12-22T00:54:46.007Z - debug: Device presented: Apple-Iphone5s-1_PT9511 (ios) perftest socket:4

2015-12-22T00:54:46.525Z - debug: Device presented: Apple-IpadAir2-1_PT8764 (ios) perftest socket:6

2015-12-22T00:54:46.711Z - debug: Device presented: samsung-SM-A500FU_PT884 (android) perftest socket:7

2015-12-22T00:54:46.990Z - debug: Device presented: samsung-SM-A300FU_PT3792 (android) perftest socket:8

2015-12-22T00:54:47.012Z - debug: Device presented: samsung-SM-A500FU_PT2086 (android) perftest socket:9

2015-12-22T00:54:47.235Z - debug: Device presented: samsung-SM-A300FU_PT4323 (android) perftest socket:11

2015-12-22T00:54:47.267Z - debug: Device presented: LGE-LG-D855_PT3064 (android) perftest socket:10

2015-12-22T00:54:47.761Z - debug: Device presented: samsung-SM-G900F_PT1382 (android) perftest socket:12

2015-12-22T00:54:48.723Z - debug: Device presented: samsung-SM-N910C_PT1903 (android) perftest socket:13

2015-12-22T00:54:49.370Z - debug: Device presented: LGE-LG-D722_PT1947 (android) perftest socket:14

2015-12-22T00:54:49.719Z - debug: Device presented: samsung-SM-G900F_PT8784 (android) perftest socket:15

2015-12-22T00:54:49.912Z - debug: Device presented: Apple-Iphone5-1_PT5195 (ios) perftest socket:16

2015-12-22T00:54:49.913Z - info: Required number of devices presented

2015-12-22T00:54:49.917Z - info: Starting perf test run for platform: ios

2015-12-22T00:54:49.918Z - info: Using devices:

2015-12-22T00:54:49.920Z - info: Apple-Iphone6-1_PT4682

2015-12-22T00:54:49.921Z - info: Apple-Iphone5s-1_PT9511

2015-12-22T00:54:49.922Z - info: Apple-IpadAir2-1_PT8764

2015-12-22T00:54:49.923Z - info: Apple-Iphone5-1_PT5195

2015-12-22T00:54:49.927Z - info: Starting test: with 4 devices (ios)

2015-12-22T00:54:51.340Z - info: Received results for {"name:":"Apple-Iphone6-1_PT4682","time":1063,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-IpadAir2-1_PT8764.Y1JJAA==","peerAvailable":true,"time":1061}]} Apple-Iphone6-1_PT4682 ios (4 left)

2015-12-22T00:54:51.357Z - info: Received results for {"name:":"Apple-Iphone5-1_PT5195","time":1137,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-IpadAir2-1_PT8764.Y1JJAA==","peerAvailable":true,"time":1136}]} Apple-Iphone5-1_PT5195 ios (3 left)

2015-12-22T00:54:51.484Z - info: Received results for {"name:":"Apple-IpadAir2-1_PT8764","time":1125,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone6-1_PT4682.4oKZxQ==","peerAvailable":true,"time":1123}]} Apple-IpadAir2-1_PT8764 ios (2 left)

2015-12-22T00:54:52.330Z - info: Received results for {"name:":"Apple-Iphone5s-1_PT9511","time":663,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone6-1_PT4682.4oKZxQ==","peerAvailable":true,"time":661}]} Apple-Iphone5s-1_PT9511 ios (1 left)

2015-12-22T00:54:52.334Z - info: All test data retrieved for testFindPeers.js (ios)

2015-12-22T00:54:52.341Z - info: Remaining tests: %s ios=[testSendData.js]

2015-12-22T00:54:52.345Z - info: Continuing to next test: testSendData.js
2015-12-22T00:54:52.346Z - info: Starting test: with 4 devices (ios)

2015-12-22T00:54:58.948Z - debug: Device presented: motorola-XT1039_PT77 (android) perftest socket:17

2015-12-22T00:55:00.493Z - debug: Socket disconnected: transport close 17 (motorola-XT1039_PT77)

2015-12-22T00:56:16.348Z - debug: Socket disconnected: ping timeout 3 (Apple-Iphone6-1_PT4682)

2015-12-22T00:56:25.750Z - debug: Device presented: Apple-Iphone6-1_PT4682 (ios) perftest socket:18

2015-12-22T00:56:25.752Z - info: Updating existing device: Apple-Iphone6-1_PT4682 (c33928c1-47da-4a1f-aef0-3cdc40cf96b8)

2015-12-22T00:56:29.500Z - info: Received results for {"name:":"Apple-IpadAir2-1_PT8764","time":96629,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT4682.4oKZxQ==","time":42217,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-Iphone5-1_PT5195.x5+2Tg==","time":4653,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT9511.iUx4mA==","time":3540,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1_PT4682.uK405g==","time":46154,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-IpadAir2-1_PT8764 ios (4 left)

2015-12-22T00:56:30.047Z - info: Received results for {"name:":"Apple-Iphone5-1_PT5195","time":97314,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT4682.4oKZxQ==","time":41739,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-IpadAir2-1_PT8764.Ptw77g==","time":4760,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT9511.iUx4mA==","time":3598,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1_PT4682.uK405g==","time":46612,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone5-1_PT5195 ios (3 left)

2015-12-22T00:56:33.118Z - info: Received results for {"name:":"Apple-Iphone5s-1_PT9511","time":100047,"result":"TIMEOUT","sendList":[{"name":"Apple-IpadAir2-1_PT8764.Y1JJAA==","time":41879,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-Iphone6-1_PT4682.uK405g==","time":0,"result":"Fail"}]} Apple-Iphone5s-1_PT9511 ios (2 left)

2015-12-22T00:56:33.495Z - info: Received results for {"name:":"Apple-Iphone6-1_PT4682","time":100042,"result":"TIMEOUT","sendList":[{"name":"Apple-Iphone5-1_PT5195.3svwkg==","time":41253,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-Iphone5s-1_PT9511.iUx4mA==","time":56388,"result":"OK","connections":3,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_PT8764.Ptw77g==","time":0,"result":"Fail"}]} Apple-Iphone6-1_PT4682 ios (1 left)

2015-12-22T00:56:33.496Z - info: All test data retrieved for testSendData.js (ios)

2015-12-22T00:56:33.501Z - info: Remaining tests: %s ios=[]

2015-12-22T00:56:33.503Z - info: ALL DONE !!!

{ 'name:': 'Apple-Iphone6-1_PT4682',
  time: 1063,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1_PT8764.Y1JJAA==',
       peerAvailable: true,
       time: 1061 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT9511',
  time: 663,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT4682.4oKZxQ==',
       peerAvailable: true,
       time: 661 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT8764',
  time: 1125,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT4682.4oKZxQ==',
       peerAvailable: true,
       time: 1123 } ] }

{ 'name:': 'Apple-Iphone5-1_PT5195',
  time: 1137,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1_PT8764.Y1JJAA==',
       peerAvailable: true,
       time: 1136 } ] }

{ 'name:': 'Apple-Iphone6-1_PT4682',
  time: 100042,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'Apple-Iphone5-1_PT5195.3svwkg==',
       time: 41253,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1_PT9511.iUx4mA==',
       time: 56388,
       result: 'OK',
       connections: 3,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT8764.Ptw77g==',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Apple-Iphone5s-1_PT9511',
  time: 100047,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT8764.Y1JJAA==',
       time: 41879,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT4682.uK405g==',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Apple-IpadAir2-1_PT8764',
  time: 96629,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4682.4oKZxQ==',
       time: 42217,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1_PT5195.x5+2Tg==',
       time: 4653,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT9511.iUx4mA==',
       time: 3540,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT4682.uK405g==',
       time: 46154,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1_PT5195',
  time: 97314,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4682.4oKZxQ==',
       time: 41739,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT8764.Ptw77g==',
       time: 4760,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT9511.iUx4mA==',
       time: 3598,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT4682.uK405g==',
       time: 46612,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

--------------- test report ---------------------
--------------- Apple-Iphone6-1_PT4682 --------------------- : 1

peersList : 100% : 1061 ms, 99% : 1061 ms, 95 : 1061 ms, 90% : 1061 ms.

Result count 1, range 1061 ms to  1061 ms.

sendList : 100% : 56388 ms, 99% : 56388 ms, 95 : 56388 ms, 90% : 56388 ms.

Average data rate: 0.002 MB/s

Result count 1, range 56388 ms to  56388 ms.

sendList failed peers count : 1 [50 %]

- Peer ID : Apple-Iphone5-1_PT5195.3svwkg==, Tried : 5

sendList never tried peers count : 1 [33.333333333333336 %]

- Peer ID : Apple-IpadAir2-1_PT8764.Ptw77g==
--------------- Apple-Iphone5s-1_PT9511 --------------------- : 2

peersList : 100% : 661 ms, 99% : 661 ms, 95 : 661 ms, 90% : 661 ms.
Result count 1, range 661 ms to  661 ms.

sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.

Average data rate: NaN MB/s

Results list does not contain any items

sendList failed peers count : 1 [100 %]
- Peer ID : Apple-IpadAir2-1_PT8764.Y1JJAA==, Tried : 5
sendList never tried peers count : 1 [50 %]

- Peer ID : Apple-Iphone6-1_PT4682.uK405g==
--------------- Apple-IpadAir2-1_PT8764 --------------------- : 3

peersList : 100% : 1123 ms, 99% : 1123 ms, 95 : 1123 ms, 90% : 1123 ms.
Result count 1, range 1123 ms to  1123 ms.

sendList : 100% : 46154 ms, 99% : 46154 ms, 95 : 46154 ms, 90% : 46154 ms.

Average data rate: 0.006 MB/s
Result count 3, range 3540 ms to  46154 ms.
sendList failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone6-1_PT4682.4oKZxQ==, Tried : 5

sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5-1_PT5195 --------------------- : 4

peersList : 100% : 1136 ms, 99% : 1136 ms, 95 : 1136 ms, 90% : 1136 ms.

Result count 1, range 1136 ms to  1136 ms.
sendList : 100% : 46612 ms, 99% : 46612 ms, 95 : 46612 ms, 90% : 46612 ms.
Average data rate: 0.005 MB/s

Result count 3, range 3598 ms to  46612 ms.
sendList failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone6-1_PT4682.4oKZxQ==, Tried : 5

sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------

peersList : 100% : 1136 ms, 99% : 1136 ms, 95 : 1136 ms, 90% : 1136 ms.
sendList : 100% : 56388 ms, 99% : 56388 ms, 95 : 56388 ms, 90% : 46612 ms.

Average data rate: 0.004 MB/s
--------------- end of test report ---------------------

2015-12-22T00:56:33.628Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1_PT8764.Y1JJAA==, peerAvailable=true, time=1061], sendList=[name=Apple-Iphone5s-1_PT9511.iUx4mA==, time=56388, result=OK, connections=3, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone5-1_PT5195.3svwkg==, time=41253, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[name=Apple-IpadAir2-1_PT8764.Ptw77g==, time=0, result=Fail], peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1_PT4682.4oKZxQ==, peerAvailable=true, time=661], sendList=[], failedPeer=[name=Apple-IpadAir2-1_PT8764.Y1JJAA==, time=41879, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[name=Apple-Iphone6-1_PT4682.uK405g==, time=0, result=Fail], peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1_PT4682.4oKZxQ==, peerAvailable=true, time=1123], sendList=[name=Apple-Iphone5s-1_PT9511.iUx4mA==, time=3540, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1_PT5195.x5+2Tg==, time=4653, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone6-1_PT4682.uK405g==, time=46154, result=OK, connections=2, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone6-1_PT4682.4oKZxQ==, time=42217, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1_PT8764.Y1JJAA==, peerAvailable=true, time=1136], sendList=[name=Apple-Iphone5s-1_PT9511.iUx4mA==, time=3598, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1_PT8764.Ptw77g==, time=4760, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone6-1_PT4682.uK405g==, time=46612, result=OK, connections=2, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone6-1_PT4682.4oKZxQ==, time=41739, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[]

2015-12-22T00:56:33.635Z - debug: end to Apple-Iphone6-1_PT4682

2015-12-22T00:56:33.637Z - debug: end to Apple-Iphone5s-1_PT9511

2015-12-22T00:56:33.640Z - debug: end to Apple-IpadAir2-1_PT8764

2015-12-22T00:56:33.641Z - debug: end to Apple-Iphone5-1_PT5195

2015-12-22T00:56:40.131Z - debug: Socket disconnected: transport close 4 (Apple-Iphone5s-1_PT9511)

2015-12-22T00:56:40.390Z - debug: Socket disconnected: transport close 6 (Apple-IpadAir2-1_PT8764)

2015-12-22T00:56:40.914Z - debug: Socket disconnected: transport close 16 (Apple-Iphone5-1_PT5195)

2015-12-22T00:56:45.083Z - info: Start timeout elapsed for platform: android

2015-12-22T00:56:45.086Z - info: Starting perf test run for platform: android

2015-12-22T00:56:45.087Z - info: Using devices:

2015-12-22T00:56:45.088Z - info: LGE-Nexus 5_PT1510
2015-12-22T00:56:45.089Z - info: HTC-HTC One M8s_PT375

2015-12-22T00:56:45.089Z - info: motorola-XT1072_PT3784
2015-12-22T00:56:45.090Z - info: LGE-LG-H815_PT8123

2015-12-22T00:56:45.091Z - info: samsung-SM-A500FU_PT884
2015-12-22T00:56:45.092Z - info: samsung-SM-A300FU_PT3792

2015-12-22T00:56:45.093Z - info: samsung-SM-A500FU_PT2086
2015-12-22T00:56:45.093Z - info: samsung-SM-A300FU_PT4323

2015-12-22T00:56:45.094Z - info: LGE-LG-D855_PT3064
2015-12-22T00:56:45.095Z - info: samsung-SM-G900F_PT1382

2015-12-22T00:56:45.096Z - info: samsung-SM-N910C_PT1903

2015-12-22T00:56:45.099Z - info: LGE-LG-D722_PT1947

2015-12-22T00:56:45.100Z - info: samsung-SM-G900F_PT8784
2015-12-22T00:56:45.101Z - info: motorola-XT1039_PT77

2015-12-22T00:56:45.102Z - info: Starting test: with 14 devices (android)

2015-12-22T00:56:46.778Z - debug: state: android running

2015-12-22T00:56:46.781Z - debug: state: ios completed

2015-12-22T00:56:47.974Z - info: Received results for {"name:":"samsung-SM-A300FU_PT4323","time":2213,"result":"OK","peersList":[{"peerName":"samsung-SM-A300FU_PT3792","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":2211}]} samsung-SM-A300FU_PT4323 android (14 left)

2015-12-22T00:56:48.492Z - info: Received results for {"name:":"samsung-SM-A300FU_PT3792","time":2725,"result":"OK","peersList":[{"peerName":"samsung-SM-A300FU_PT4323","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":2724}]} samsung-SM-A300FU_PT3792 android (13 left)

2015-12-22T00:56:48.780Z - info: Received results for {"name:":"motorola-XT1072_PT3784","time":2873,"result":"OK","peersList":[{"peerName":"samsung-SM-A300FU_PT3792","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":2871}]} motorola-XT1072_PT3784 android (12 left)

2015-12-22T00:56:49.272Z - debug: Socket disconnected: transport close 18 (Apple-Iphone6-1_PT4682)

2015-12-22T00:56:49.387Z - info: Received results for {"name:":"HTC-HTC One M8s_PT375","time":3839,"result":"OK","peersList":[{"peerName":"samsung-SM-A500FU_PT884","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":3837}]} HTC-HTC One M8s_PT375 android (11 left)

2015-12-22T00:56:49.676Z - info: Received results for {"name:":"LGE-LG-D855_PT3064","time":3096,"result":"OK","peersList":[{"peerName":"LGE-LG-D722_PT1947","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":3090}]} LGE-LG-D855_PT3064 android (10 left)

2015-12-22T00:56:49.930Z - info: server timeout for test: testFindPeers.js (ios)

2015-12-22T00:56:49.933Z - info: All test data retrieved for testFindPeers.js (ios)

2015-12-22T00:56:49.934Z - info: Remaining tests: %s ios=[], android=[testFindPeers.js, testSendData.js]
2015-12-22T00:56:49.935Z - info: ALL DONE !!!
{ 'name:': 'Apple-Iphone6-1_PT4682',
  time: 1063,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1_PT8764.Y1JJAA==',
       peerAvailable: true,
       time: 1061 } ] }
{ 'name:': 'Apple-Iphone5s-1_PT9511',
  time: 663,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT4682.4oKZxQ==',
       peerAvailable: true,
       time: 661 } ] }
{ 'name:': 'Apple-IpadAir2-1_PT8764',
  time: 1125,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT4682.4oKZxQ==',
       peerAvailable: true,
       time: 1123 } ] }
{ 'name:': 'Apple-Iphone5-1_PT5195',
  time: 1137,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1_PT8764.Y1JJAA==',
       peerAvailable: true,
       time: 1136 } ] }
{ 'name:': 'Apple-Iphone6-1_PT4682',
  time: 100042,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'Apple-Iphone5-1_PT5195.3svwkg==',
       time: 41253,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1_PT9511.iUx4mA==',
       time: 56388,
       result: 'OK',
       connections: 3,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT8764.Ptw77g==',
       time: 0,
       result: 'Fail' } ] }
{ 'name:': 'Apple-Iphone5s-1_PT9511',
  time: 100047,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT8764.Y1JJAA==',
       time: 41879,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT4682.uK405g==',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Apple-IpadAir2-1_PT8764',
  time: 96629,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4682.4oKZxQ==',
       time: 42217,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1_PT5195.x5+2Tg==',
       time: 4653,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT9511.iUx4mA==',
       time: 3540,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT4682.uK405g==',
       time: 46154,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1_PT5195',
  time: 97314,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4682.4oKZxQ==',
       time: 41739,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT8764.Ptw77g==',
       time: 4760,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT9511.iUx4mA==',
       time: 3598,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT4682.uK405g==',
       time: 46612,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1_PT4682',
  time: 100042,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'Apple-Iphone5-1_PT5195.3svwkg==',
       time: 41253,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1_PT9511.iUx4mA==',
       time: 56388,
       result: 'OK',
       connections: 3,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT8764.Ptw77g==',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Apple-Iphone5s-1_PT9511',
  time: 100047,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT8764.Y1JJAA==',
       time: 41879,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT4682.uK405g==',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Apple-IpadAir2-1_PT8764',
  time: 96629,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4682.4oKZxQ==',
       time: 42217,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1_PT5195.x5+2Tg==',
       time: 4653,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT9511.iUx4mA==',
       time: 3540,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT4682.uK405g==',
       time: 46154,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1_PT5195',
  time: 97314,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4682.4oKZxQ==',
       time: 41739,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT8764.Ptw77g==',
       time: 4760,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT9511.iUx4mA==',
       time: 3598,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT4682.uK405g==',
       time: 46612,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

--------------- test report ---------------------
--------------- Apple-Iphone6-1_PT4682 --------------------- : 1
peersList : 100% : 1061 ms, 99% : 1061 ms, 95 : 1061 ms, 90% : 1061 ms.
Result count 1, range 1061 ms to  1061 ms.
sendList : 100% : 56388 ms, 99% : 56388 ms, 95 : 56388 ms, 90% : 56388 ms.
Average data rate: 0.002 MB/s
Result count 2, range 56388 ms to  56388 ms.
sendList failed peers count : 2 [50 %]
- Peer ID : Apple-Iphone5-1_PT5195.3svwkg==, Tried : 5
- Peer ID : Apple-Iphone5-1_PT5195.3svwkg==, Tried : 5
sendList never tried peers count : 2 [33.333333333333336 %]
- Peer ID : Apple-IpadAir2-1_PT8764.Ptw77g==
- Peer ID : Apple-IpadAir2-1_PT8764.Ptw77g==
--------------- Apple-Iphone5s-1_PT9511 --------------------- : 2
peersList : 100% : 661 ms, 99% : 661 ms, 95 : 661 ms, 90% : 661 ms.
Result count 1, range 661 ms to  661 ms.
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 2 [100 %]
- Peer ID : Apple-IpadAir2-1_PT8764.Y1JJAA==, Tried : 5
- Peer ID : Apple-IpadAir2-1_PT8764.Y1JJAA==, Tried : 5
sendList never tried peers count : 2 [50 %]
- Peer ID : Apple-Iphone6-1_PT4682.uK405g==
- Peer ID : Apple-Iphone6-1_PT4682.uK405g==
--------------- Apple-IpadAir2-1_PT8764 --------------------- : 3
peersList : 100% : 1123 ms, 99% : 1123 ms, 95 : 1123 ms, 90% : 1123 ms.
Result count 1, range 1123 ms to  1123 ms.
sendList : 100% : 46154 ms, 99% : 46154 ms, 95 : 46154 ms, 90% : 46154 ms.
Average data rate: 0.006 MB/s
Result count 6, range 3540 ms to  46154 ms.
sendList failed peers count : 2 [25 %]
- Peer ID : Apple-Iphone6-1_PT4682.4oKZxQ==, Tried : 5
- Peer ID : Apple-Iphone6-1_PT4682.4oKZxQ==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5-1_PT5195 --------------------- : 4
peersList : 100% : 1136 ms, 99% : 1136 ms, 95 : 1136 ms, 90% : 1136 ms.

Result count 1, range 1136 ms to  1136 ms.
sendList : 100% : 46612 ms, 99% : 46612 ms, 95 : 46612 ms, 90% : 46612 ms.
Average data rate: 0.005 MB/s
Result count 6, range 3598 ms to  46612 ms.
sendList failed peers count : 2 [25 %]
- Peer ID : Apple-Iphone6-1_PT4682.4oKZxQ==, Tried : 5
- Peer ID : Apple-Iphone6-1_PT4682.4oKZxQ==, Tried : 5

sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------
peersList : 100% : 1136 ms, 99% : 1136 ms, 95 : 1136 ms, 90% : 1136 ms.

sendList : 100% : 56388 ms, 99% : 56388 ms, 95 : 56388 ms, 90% : 56388 ms.
Average data rate: 0.004 MB/s
--------------- end of test report ---------------------

2015-12-22T00:56:50.051Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1_PT8764.Y1JJAA==, peerAvailable=true, time=1061], sendList=[name=Apple-Iphone5s-1_PT9511.iUx4mA==, time=56388, result=OK, connections=3, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1_PT4682"]["sendList"][0]], failedPeer=[name=Apple-Iphone5-1_PT5195.3svwkg==, time=41253, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone6-1_PT4682"]["sendError"]["failedPeer"][0]], notTriedList=[name=Apple-IpadAir2-1_PT8764.Ptw77g==, time=0, result=Fail, $ref=$["Apple-Iphone6-1_PT4682"]["sendError"]["notTriedList"][0]], peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1_PT4682.4oKZxQ==, peerAvailable=true, time=661], sendList=[], failedPeer=[name=Apple-IpadAir2-1_PT8764.Y1JJAA==, time=41879, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone5s-1_PT9511"]["sendError"]["failedPeer"][0]], notTriedList=[name=Apple-Iphone6-1_PT4682.uK405g==, time=0, result=Fail, $ref=$["Apple-Iphone5s-1_PT9511"]["sendError"]["notTriedList"][0]], peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1_PT4682.4oKZxQ==, peerAvailable=true, time=1123], sendList=[name=Apple-Iphone5s-1_PT9511.iUx4mA==, time=3540, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1_PT8764"]["sendList"][0], name=Apple-Iphone5-1_PT5195.x5+2Tg==, time=4653, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1_PT8764"]["sendList"][2], name=Apple-Iphone6-1_PT4682.uK405g==, time=46154, result=OK, connections=2, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1_PT8764"]["sendList"][4]], failedPeer=[name=Apple-Iphone6-1_PT4682.4oKZxQ==, time=42217, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-IpadAir2-1_PT8764"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1_PT8764.Y1JJAA==, peerAvailable=true, time=1136], sendList=[name=Apple-Iphone5s-1_PT9511.iUx4mA==, time=3598, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1_PT5195"]["sendList"][0], name=Apple-IpadAir2-1_PT8764.Ptw77g==, time=4760, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1_PT5195"]["sendList"][2], name=Apple-Iphone6-1_PT4682.uK405g==, time=46612, result=OK, connections=2, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1_PT5195"]["sendList"][4]], failedPeer=[name=Apple-Iphone6-1_PT4682.4oKZxQ==, time=41739, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone5-1_PT5195"]["sendError"]["failedPeer"][0]], notTriedList=[]

2015-12-22T00:56:50.059Z - debug: end to Apple-Iphone6-1_PT4682

2015-12-22T00:56:50.060Z - debug: end to Apple-Iphone5s-1_PT9511
2015-12-22T00:56:50.062Z - debug: end to Apple-IpadAir2-1_PT8764

2015-12-22T00:56:50.063Z - debug: end to Apple-Iphone5-1_PT5195

2015-12-22T00:56:50.078Z - info: Received results for {"name:":"samsung-SM-A500FU_PT2086","time":4207,"result":"OK","peersList":[{"peerName":"LGE-LG-D855_PT3064","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":4206}]} samsung-SM-A500FU_PT2086 android (9 left)

2015-12-22T00:56:50.263Z - info: Received results for {"name:":"samsung-SM-A500FU_PT884","time":4382,"result":"OK","peersList":[{"peerName":"samsung-SM-A500FU_PT2086","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":4380}]} samsung-SM-A500FU_PT884 android (8 left)

2015-12-22T00:56:52.348Z - info: server timeout for test: testSendData.js (ios)

2015-12-22T00:56:52.351Z - info: All test data retrieved for testSendData.js (ios)

2015-12-22T00:56:52.352Z - info: Remaining tests: %s ios=[], android=[testFindPeers.js, testSendData.js]

2015-12-22T00:56:52.355Z - info: ALL DONE !!!

{ 'name:': 'Apple-Iphone6-1_PT4682',
  time: 1063,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1_PT8764.Y1JJAA==',
       peerAvailable: true,
       time: 1061 } ] }
{ 'name:': 'Apple-Iphone5s-1_PT9511',
  time: 663,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT4682.4oKZxQ==',
       peerAvailable: true,
       time: 661 } ] }
{ 'name:': 'Apple-IpadAir2-1_PT8764',
  time: 1125,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT4682.4oKZxQ==',
       peerAvailable: true,
       time: 1123 } ] }
{ 'name:': 'Apple-Iphone5-1_PT5195',
  time: 1137,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1_PT8764.Y1JJAA==',
       peerAvailable: true,
       time: 1136 } ] }
{ 'name:': 'Apple-Iphone6-1_PT4682',
  time: 100042,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'Apple-Iphone5-1_PT5195.3svwkg==',
       time: 41253,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1_PT9511.iUx4mA==',
       time: 56388,
       result: 'OK',
       connections: 3,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT8764.Ptw77g==',
       time: 0,
       result: 'Fail' } ] }
{ 'name:': 'Apple-Iphone5s-1_PT9511',
  time: 100047,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT8764.Y1JJAA==',
       time: 41879,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT4682.uK405g==',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Apple-IpadAir2-1_PT8764',
  time: 96629,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4682.4oKZxQ==',
       time: 42217,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1_PT5195.x5+2Tg==',
       time: 4653,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT9511.iUx4mA==',
       time: 3540,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT4682.uK405g==',
       time: 46154,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1_PT5195',
  time: 97314,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4682.4oKZxQ==',
       time: 41739,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT8764.Ptw77g==',
       time: 4760,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT9511.iUx4mA==',
       time: 3598,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT4682.uK405g==',
       time: 46612,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1_PT4682',
  time: 100042,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'Apple-Iphone5-1_PT5195.3svwkg==',
       time: 41253,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1_PT9511.iUx4mA==',
       time: 56388,
       result: 'OK',
       connections: 3,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT8764.Ptw77g==',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Apple-Iphone5s-1_PT9511',
  time: 100047,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT8764.Y1JJAA==',
       time: 41879,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT4682.uK405g==',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Apple-IpadAir2-1_PT8764',
  time: 96629,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4682.4oKZxQ==',
       time: 42217,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1_PT5195.x5+2Tg==',
       time: 4653,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT9511.iUx4mA==',
       time: 3540,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT4682.uK405g==',
       time: 46154,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1_PT5195',
  time: 97314,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4682.4oKZxQ==',
       time: 41739,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT8764.Ptw77g==',
       time: 4760,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT9511.iUx4mA==',
       time: 3598,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT4682.uK405g==',
       time: 46612,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1_PT4682',
  time: 100042,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'Apple-Iphone5-1_PT5195.3svwkg==',
       time: 41253,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1_PT9511.iUx4mA==',
       time: 56388,
       result: 'OK',
       connections: 3,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT8764.Ptw77g==',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Apple-Iphone5s-1_PT9511',
  time: 100047,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT8764.Y1JJAA==',
       time: 41879,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT4682.uK405g==',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Apple-IpadAir2-1_PT8764',
  time: 96629,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4682.4oKZxQ==',
       time: 42217,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1_PT5195.x5+2Tg==',
       time: 4653,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT9511.iUx4mA==',
       time: 3540,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT4682.uK405g==',
       time: 46154,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1_PT5195',
  time: 97314,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4682.4oKZxQ==',
       time: 41739,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT8764.Ptw77g==',
       time: 4760,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT9511.iUx4mA==',
       time: 3598,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT4682.uK405g==',
       time: 46612,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

--------------- test report ---------------------
--------------- Apple-Iphone6-1_PT4682 --------------------- : 1
peersList : 100% : 1061 ms, 99% : 1061 ms, 95 : 1061 ms, 90% : 1061 ms.
Result count 1, range 1061 ms to  1061 ms.
sendList : 100% : 56388 ms, 99% : 56388 ms, 95 : 56388 ms, 90% : 56388 ms.

Average data rate: 0.002 MB/s

Result count 3, range 56388 ms to  56388 ms.

sendList failed peers count : 3 [50 %]
- Peer ID : Apple-Iphone5-1_PT5195.3svwkg==, Tried : 5
- Peer ID : Apple-Iphone5-1_PT5195.3svwkg==, Tried : 5
- Peer ID : Apple-Iphone5-1_PT5195.3svwkg==, Tried : 5
sendList never tried peers count : 3 [33.333333333333336 %]
- Peer ID : Apple-IpadAir2-1_PT8764.Ptw77g==

- Peer ID : Apple-IpadAir2-1_PT8764.Ptw77g==
- Peer ID : Apple-IpadAir2-1_PT8764.Ptw77g==
--------------- Apple-Iphone5s-1_PT9511 --------------------- : 2
peersList : 100% : 661 ms, 99% : 661 ms, 95 : 661 ms, 90% : 661 ms.
Result count 1, range 661 ms to  661 ms.

sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 3 [100 %]
- Peer ID : Apple-IpadAir2-1_PT8764.Y1JJAA==, Tried : 5

- Peer ID : Apple-IpadAir2-1_PT8764.Y1JJAA==, Tried : 5
- Peer ID : Apple-IpadAir2-1_PT8764.Y1JJAA==, Tried : 5
sendList never tried peers count : 3 [50 %]
- Peer ID : Apple-Iphone6-1_PT4682.uK405g==
- Peer ID : Apple-Iphone6-1_PT4682.uK405g==

- Peer ID : Apple-Iphone6-1_PT4682.uK405g==
--------------- Apple-IpadAir2-1_PT8764 --------------------- : 3
peersList : 100% : 1123 ms, 99% : 1123 ms, 95 : 1123 ms, 90% : 1123 ms.
Result count 1, range 1123 ms to  1123 ms.

sendList : 100% : 46154 ms, 99% : 46154 ms, 95 : 46154 ms, 90% : 46154 ms.
Average data rate: 0.006 MB/s
Result count 9, range 3540 ms to  46154 ms.
sendList failed peers count : 3 [25 %]
- Peer ID : Apple-Iphone6-1_PT4682.4oKZxQ==, Tried : 5

- Peer ID : Apple-Iphone6-1_PT4682.4oKZxQ==, Tried : 5
- Peer ID : Apple-Iphone6-1_PT4682.4oKZxQ==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5-1_PT5195 --------------------- : 4
peersList : 100% : 1136 ms, 99% : 1136 ms, 95 : 1136 ms, 90% : 1136 ms.

Result count 1, range 1136 ms to  1136 ms.
sendList : 100% : 46612 ms, 99% : 46612 ms, 95 : 46612 ms, 90% : 46612 ms.
Average data rate: 0.005 MB/s
Result count 9, range 3598 ms to  46612 ms.
sendList failed peers count : 3 [25 %]

- Peer ID : Apple-Iphone6-1_PT4682.4oKZxQ==, Tried : 5
- Peer ID : Apple-Iphone6-1_PT4682.4oKZxQ==, Tried : 5
- Peer ID : Apple-Iphone6-1_PT4682.4oKZxQ==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------

peersList : 100% : 1136 ms, 99% : 1136 ms, 95 : 1136 ms, 90% : 1136 ms.
sendList : 100% : 56388 ms, 99% : 56388 ms, 95 : 56388 ms, 90% : 56388 ms.

Average data rate: 0.004 MB/s
--------------- end of test report ---------------------

2015-12-22T00:56:52.476Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1_PT8764.Y1JJAA==, peerAvailable=true, time=1061], sendList=[name=Apple-Iphone5s-1_PT9511.iUx4mA==, time=56388, result=OK, connections=3, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1_PT4682"]["sendList"][0], $ref=$["Apple-Iphone6-1_PT4682"]["sendList"][0]], failedPeer=[name=Apple-Iphone5-1_PT5195.3svwkg==, time=41253, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone6-1_PT4682"]["sendError"]["failedPeer"][0], $ref=$["Apple-Iphone6-1_PT4682"]["sendError"]["failedPeer"][0]], notTriedList=[name=Apple-IpadAir2-1_PT8764.Ptw77g==, time=0, result=Fail, $ref=$["Apple-Iphone6-1_PT4682"]["sendError"]["notTriedList"][0], $ref=$["Apple-Iphone6-1_PT4682"]["sendError"]["notTriedList"][0]], peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1_PT4682.4oKZxQ==, peerAvailable=true, time=661], sendList=[], failedPeer=[name=Apple-IpadAir2-1_PT8764.Y1JJAA==, time=41879, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone5s-1_PT9511"]["sendError"]["failedPeer"][0], $ref=$["Apple-Iphone5s-1_PT9511"]["sendError"]["failedPeer"][0]], notTriedList=[name=Apple-Iphone6-1_PT4682.uK405g==, time=0, result=Fail, $ref=$["Apple-Iphone5s-1_PT9511"]["sendError"]["notTriedList"][0], $ref=$["Apple-Iphone5s-1_PT9511"]["sendError"]["notTriedList"][0]], peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1_PT4682.4oKZxQ==, peerAvailable=true, time=1123], sendList=[name=Apple-Iphone5s-1_PT9511.iUx4mA==, time=3540, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1_PT8764"]["sendList"][0], $ref=$["Apple-IpadAir2-1_PT8764"]["sendList"][0], name=Apple-Iphone5-1_PT5195.x5+2Tg==, time=4653, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1_PT8764"]["sendList"][3], $ref=$["Apple-IpadAir2-1_PT8764"]["sendList"][3], name=Apple-Iphone6-1_PT4682.uK405g==, time=46154, result=OK, connections=2, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1_PT8764"]["sendList"][6], $ref=$["Apple-IpadAir2-1_PT8764"]["sendList"][6]], failedPeer=[name=Apple-Iphone6-1_PT4682.4oKZxQ==, time=42217, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-IpadAir2-1_PT8764"]["sendError"]["failedPeer"][0], $ref=$["Apple-IpadAir2-1_PT8764"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1_PT8764.Y1JJAA==, peerAvailable=true, time=1136], sendList=[name=Apple-Iphone5s-1_PT9511.iUx4mA==, time=3598, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1_PT5195"]["sendList"][0], $ref=$["Apple-Iphone5-1_PT5195"]["sendList"][0], name=Apple-IpadAir2-1_PT8764.Ptw77g==, time=4760, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1_PT5195"]["sendList"][3], $ref=$["Apple-Iphone5-1_PT5195"]["sendList"][3], name=Apple-Iphone6-1_PT4682.uK405g==, time=46612, result=OK, connections=2, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1_PT5195"]["sendList"][6], $ref=$["Apple-Iphone5-1_PT5195"]["sendList"][6]], failedPeer=[name=Apple-Iphone6-1_PT4682.4oKZxQ==, time=41739, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone5-1_PT5195"]["sendError"]["failedPeer"][0], $ref=$["Apple-Iphone5-1_PT5195"]["sendError"]["failedPeer"][0]], notTriedList=[]

2015-12-22T00:56:52.484Z - debug: end to Apple-Iphone6-1_PT4682
2015-12-22T00:56:52.485Z - debug: end to Apple-Iphone5s-1_PT9511

2015-12-22T00:56:52.486Z - debug: end to Apple-IpadAir2-1_PT8764

2015-12-22T00:56:52.487Z - debug: end to Apple-Iphone5-1_PT5195

2015-12-22T00:57:05.428Z - info: Received results for {"name:":"LGE-LG-H815_PT8123","time":18532,"result":"OK","peersList":[{"peerName":"samsung-SM-A500FU_PT884","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":18526}]} LGE-LG-H815_PT8123 android (7 left)

2015-12-22T00:57:14.143Z - info: Received results for {"name:":"samsung-SM-G900F_PT1382","time":28469,"result":"OK","peersList":[{"peerName":"samsung-SM-A500FU_PT884","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":28459}]} samsung-SM-G900F_PT1382 android (6 left)

2015-12-22T00:57:22.011Z - info: Received results for {"name:":"samsung-SM-G900F_PT8784","time":36498,"result":"OK","peersList":[{"peerName":"LGE-LG-H815_PT8123","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":36491}]} samsung-SM-G900F_PT8784 android (5 left)

2015-12-22T00:57:28.820Z - info: Received results for {"name:":"samsung-SM-N910C_PT1903","time":43137,"result":"OK","peersList":[{"peerName":"HTC-HTC One M8s_PT375","peerIdentifier":"90:E7:C4:F6:69:77","peerAvailable":true,"time":43132}]} samsung-SM-N910C_PT1903 android (4 left)

2015-12-22T00:57:59.021Z - info: Received results for {"name:":"LGE-LG-D722_PT1947","time":73300,"result":"OK","peersList":[{"peerName":"samsung-SM-A500FU_PT2086","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":73299}]} LGE-LG-D722_PT1947 android (3 left)

2015-12-22T00:58:06.446Z - info: Received results for {"name:":"LGE-Nexus 5_PT1510","time":80995,"result":"OK","peersList":[{"peerName":"LGE-LG-D855_PT3064","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":80994}]} LGE-Nexus 5_PT1510 android (2 left)

2015-12-22T00:58:45.109Z - info: server timeout for test: testFindPeers.js (android)

2015-12-22T00:58:45.112Z - info: All test data retrieved for testFindPeers.js (android)

2015-12-22T00:58:45.133Z - info: No results from motorola-XT1039_PT77

2015-12-22T00:58:45.136Z - info: Remaining tests: %s ios=[], android=[testSendData.js]

2015-12-22T00:58:45.138Z - info: Continuing to next test: testSendData.js

2015-12-22T00:58:45.139Z - info: Starting test: with 14 devices (android)

2015-12-22T01:00:25.354Z - info: Received results for {"name:":"samsung-SM-N910C_PT1903","time":100043,"result":"TIMEOUT","sendList":[{"name":"7C:F9:0E:51:18:22","time":1439,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:34:8A:A0","time":4297,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"}]} samsung-SM-N910C_PT1903 android (14 left)

2015-12-22T01:00:25.444Z - info: Received results for {"name:":"LGE-LG-D722_PT1947","time":100193,"result":"TIMEOUT","sendList":[{"name":"34:FC:EF:11:AE:67","time":3459,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":8309,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:51:18:22","time":4439,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} LGE-LG-D722_PT1947 android (13 left)

2015-12-22T01:00:25.454Z - info: Received results for {"name:":"LGE-Nexus 5_PT1510","time":100034,"result":"TIMEOUT","sendList":[{"name":"F8:95:C7:87:85:54","time":1396,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":1520,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"44:80:EB:7B:5A:05","time":1434,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} LGE-Nexus 5_PT1510 android (12 left)

2015-12-22T01:00:25.470Z - info: Received results for {"name:":"samsung-SM-G900F_PT8784","time":100074,"result":"TIMEOUT","sendList":[{"name":"7C:F9:0E:51:18:22","time":2474,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"58:3F:54:73:64:C0","time":3434,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} samsung-SM-G900F_PT8784 android (11 left)

2015-12-22T01:00:25.556Z - info: Received results for {"name:":"LGE-LG-H815_PT8123","time":100056,"result":"TIMEOUT","sendList":[{"name":"7C:F9:0E:37:96:AB","time":3011,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":3616,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":8409,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"34:FC:EF:11:AE:67","time":2326,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":1789,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} LGE-LG-H815_PT8123 android (10 left)

2015-12-22T01:00:25.634Z - info: Received results for {"name:":"samsung-SM-A500FU_PT2086","time":100059,"result":"TIMEOUT","sendList":[{"name":"F8:95:C7:87:3C:51","time":3487,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} samsung-SM-A500FU_PT2086 android (9 left)

2015-12-22T01:00:25.728Z - info: Received results for {"name:":"samsung-SM-G900F_PT1382","time":100070,"result":"TIMEOUT","sendList":[{"name":"F8:95:C7:87:3C:51","time":6597,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} samsung-SM-G900F_PT1382 android (8 left)

2015-12-22T01:00:26.031Z - info: Received results for {"name:":"samsung-SM-A300FU_PT3792","time":100057,"result":"TIMEOUT","sendList":[{"name":"7C:F9:0E:51:18:22","time":1686,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} samsung-SM-A300FU_PT3792 android (7 left)

2015-12-22T01:00:26.073Z - info: Received results for {"name:":"motorola-XT1072_PT3784","time":100068,"result":"TIMEOUT","sendList":[{"name":"34:FC:EF:11:AE:67","time":2472,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} motorola-XT1072_PT3784 android (6 left)

2015-12-22T01:00:26.282Z - info: Received results for {"name:":"samsung-SM-A300FU_PT4323","time":100053,"result":"TIMEOUT","sendList":[{"name":"44:80:EB:7B:5A:05","time":2697,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} samsung-SM-A300FU_PT4323 android (5 left)

2015-12-22T01:00:26.855Z - info: Received results for {"name:":"samsung-SM-A500FU_PT884","time":100052,"result":"TIMEOUT","sendList":[{"name":"08:EC:A9:50:75:41","time":4536,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":5970,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":4573,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} samsung-SM-A500FU_PT884 android (4 left)

2015-12-22T01:00:26.882Z - info: Received results for {"name:":"HTC-HTC One M8s_PT375","time":100086,"result":"TIMEOUT","sendList":[]} HTC-HTC One M8s_PT375 android (3 left)

2015-12-22T01:00:44.850Z - info: Received results for {"name:":"LGE-LG-D855_PT3064","time":100072,"result":"TIMEOUT","sendList":[{"name":"44:80:EB:7B:5A:05","time":24004,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"90:E7:C4:F6:69:77","time":4432,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"34:FC:EF:11:AE:67","time":2728,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} LGE-LG-D855_PT3064 android (2 left)

2015-12-22T01:00:45.141Z - info: server timeout for test: testSendData.js (android)

2015-12-22T01:00:45.141Z - info: All test data retrieved for testSendData.js (android)

2015-12-22T01:00:45.153Z - info: No results from motorola-XT1039_PT77

2015-12-22T01:00:45.155Z - info: Remaining tests: %s ios=[], android=[]

2015-12-22T01:00:45.159Z - info: ALL DONE !!!

{ 'name:': 'Apple-Iphone6-1_PT4682',
  time: 1063,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1_PT8764.Y1JJAA==',
       peerAvailable: true,
       time: 1061 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT9511',
  time: 663,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT4682.4oKZxQ==',
       peerAvailable: true,
       time: 661 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT8764',
  time: 1125,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT4682.4oKZxQ==',
       peerAvailable: true,
       time: 1123 } ] }

{ 'name:': 'Apple-Iphone5-1_PT5195',
  time: 1137,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1_PT8764.Y1JJAA==',
       peerAvailable: true,
       time: 1136 } ] }

{ 'name:': 'Apple-Iphone6-1_PT4682',
  time: 100042,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'Apple-Iphone5-1_PT5195.3svwkg==',
       time: 41253,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1_PT9511.iUx4mA==',
       time: 56388,
       result: 'OK',
       connections: 3,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT8764.Ptw77g==',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Apple-Iphone5s-1_PT9511',
  time: 100047,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT8764.Y1JJAA==',
       time: 41879,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT4682.uK405g==',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Apple-IpadAir2-1_PT8764',
  time: 96629,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4682.4oKZxQ==',
       time: 42217,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1_PT5195.x5+2Tg==',
       time: 4653,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT9511.iUx4mA==',
       time: 3540,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT4682.uK405g==',
       time: 46154,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1_PT5195',
  time: 97314,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4682.4oKZxQ==',
       time: 41739,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT8764.Ptw77g==',
       time: 4760,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT9511.iUx4mA==',
       time: 3598,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT4682.uK405g==',
       time: 46612,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1_PT4682',
  time: 100042,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'Apple-Iphone5-1_PT5195.3svwkg==',
       time: 41253,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1_PT9511.iUx4mA==',
       time: 56388,
       result: 'OK',
       connections: 3,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT8764.Ptw77g==',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Apple-Iphone5s-1_PT9511',
  time: 100047,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT8764.Y1JJAA==',
       time: 41879,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT4682.uK405g==',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Apple-IpadAir2-1_PT8764',
  time: 96629,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4682.4oKZxQ==',
       time: 42217,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1_PT5195.x5+2Tg==',
       time: 4653,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT9511.iUx4mA==',
       time: 3540,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT4682.uK405g==',
       time: 46154,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1_PT5195',
  time: 97314,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4682.4oKZxQ==',
       time: 41739,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT8764.Ptw77g==',
       time: 4760,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT9511.iUx4mA==',
       time: 3598,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT4682.uK405g==',
       time: 46612,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1_PT4682',
  time: 100042,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'Apple-Iphone5-1_PT5195.3svwkg==',
       time: 41253,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1_PT9511.iUx4mA==',
       time: 56388,
       result: 'OK',
       connections: 3,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT8764.Ptw77g==',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Apple-Iphone5s-1_PT9511',
  time: 100047,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT8764.Y1JJAA==',
       time: 41879,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT4682.uK405g==',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Apple-IpadAir2-1_PT8764',
  time: 96629,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4682.4oKZxQ==',
       time: 42217,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5-1_PT5195.x5+2Tg==',
       time: 4653,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT9511.iUx4mA==',
       time: 3540,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT4682.uK405g==',
       time: 46154,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1_PT5195',
  time: 97314,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4682.4oKZxQ==',
       time: 41739,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT8764.Ptw77g==',
       time: 4760,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT9511.iUx4mA==',
       time: 3598,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT4682.uK405g==',
       time: 46612,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'LGE-Nexus 5_PT1510',
  time: 80995,
  result: 'OK',
  peersList: 
   [ { peerName: 'LGE-LG-D855_PT3064',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 80994 } ] }

{ 'name:': 'HTC-HTC One M8s_PT375',
  time: 3839,
  result: 'OK',
  peersList: 
   [ { peerName: 'samsung-SM-A500FU_PT884',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 3837 } ] }

{ 'name:': 'motorola-XT1072_PT3784',
  time: 2873,
  result: 'OK',
  peersList: 
   [ { peerName: 'samsung-SM-A300FU_PT3792',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 2871 } ] }

{ 'name:': 'LGE-LG-H815_PT8123',
  time: 18532,
  result: 'OK',
  peersList: 
   [ { peerName: 'samsung-SM-A500FU_PT884',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 18526 } ] }

{ 'name:': 'samsung-SM-A500FU_PT884',
  time: 4382,
  result: 'OK',
  peersList: 
   [ { peerName: 'samsung-SM-A500FU_PT2086',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 4380 } ] }

{ 'name:': 'samsung-SM-A300FU_PT3792',
  time: 2725,
  result: 'OK',
  peersList: 
   [ { peerName: 'samsung-SM-A300FU_PT4323',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 2724 } ] }

{ 'name:': 'samsung-SM-A500FU_PT2086',
  time: 4207,
  result: 'OK',
  peersList: 
   [ { peerName: 'LGE-LG-D855_PT3064',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 4206 } ] }

{ 'name:': 'samsung-SM-A300FU_PT4323',
  time: 2213,
  result: 'OK',
  peersList: 
   [ { peerName: 'samsung-SM-A300FU_PT3792',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 2211 } ] }

{ 'name:': 'LGE-LG-D855_PT3064',
  time: 3096,
  result: 'OK',
  peersList: 
   [ { peerName: 'LGE-LG-D722_PT1947',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 3090 } ] }

{ 'name:': 'samsung-SM-G900F_PT1382',
  time: 28469,
  result: 'OK',
  peersList: 
   [ { peerName: 'samsung-SM-A500FU_PT884',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 28459 } ] }

{ 'name:': 'samsung-SM-N910C_PT1903',
  time: 43137,
  result: 'OK',
  peersList: 
   [ { peerName: 'HTC-HTC One M8s_PT375',
       peerIdentifier: '90:E7:C4:F6:69:77',
       peerAvailable: true,
       time: 43132 } ] }

{ 'name:': 'LGE-LG-D722_PT1947',
  time: 73300,
  result: 'OK',
  peersList: 
   [ { peerName: 'samsung-SM-A500FU_PT2086',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 73299 } ] }

{ 'name:': 'samsung-SM-G900F_PT8784',
  time: 36498,
  result: 'OK',
  peersList: 
   [ { peerName: 'LGE-LG-H815_PT8123',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 36491 } ] }

{ 'name:': 'LGE-Nexus 5_PT1510',
  time: 100034,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'F8:95:C7:87:85:54',
       time: 1396,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:3C:51',
       time: 1520,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '44:80:EB:7B:5A:05',
       time: 1434,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'HTC-HTC One M8s_PT375',
  time: 100086,
  result: 'TIMEOUT',
  sendList: [] }

{ 'name:': 'motorola-XT1072_PT3784',
  time: 100068,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '34:FC:EF:11:AE:67',
       time: 2472,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'LGE-LG-H815_PT8123',
  time: 100056,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '7C:F9:0E:37:96:AB',
       time: 3011,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:85:54',
       time: 3616,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'B0:C5:59:3F:75:69',
       time: 8409,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '34:FC:EF:11:AE:67',
       time: 2326,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'E0:DB:10:14:E2:C0',
       time: 1789,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'samsung-SM-A500FU_PT884',
  time: 100052,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '08:EC:A9:50:75:41',
       time: 4536,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:85:54',
       time: 5970,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'E0:DB:10:14:E2:C0',
       time: 4573,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'samsung-SM-A300FU_PT3792',
  time: 100057,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '7C:F9:0E:51:18:22',
       time: 1686,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'samsung-SM-A500FU_PT2086',
  time: 100059,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'F8:95:C7:87:3C:51',
       time: 3487,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'samsung-SM-A300FU_PT4323',
  time: 100053,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '44:80:EB:7B:5A:05',
       time: 2697,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'LGE-LG-D855_PT3064',
  time: 100072,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '44:80:EB:7B:5A:05',
       time: 24004,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '90:E7:C4:F6:69:77',
       time: 4432,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '34:FC:EF:11:AE:67',
       time: 2728,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'samsung-SM-G900F_PT1382',
  time: 100070,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'F8:95:C7:87:3C:51',
       time: 6597,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'samsung-SM-N910C_PT1903',
  time: 100043,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '7C:F9:0E:51:18:22',
       time: 1439,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:34:8A:A0',
       time: 4297,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '34:FC:EF:11:AE:67', time: 0, result: 'Fail' } ] }

{ 'name:': 'LGE-LG-D722_PT1947',
  time: 100193,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '34:FC:EF:11:AE:67',
       time: 3459,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:3C:51',
       time: 8309,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:51:18:22',
       time: 4439,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'samsung-SM-G900F_PT8784',
  time: 100074,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '7C:F9:0E:51:18:22',
       time: 2474,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '58:3F:54:73:64:C0',
       time: 3434,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

--------------- test report ---------------------
--------------- Apple-Iphone6-1_PT4682 --------------------- : 1

peersList : 100% : 1061 ms, 99% : 1061 ms, 95 : 1061 ms, 90% : 1061 ms.
Result count 1, range 1061 ms to  1061 ms.

sendList : 100% : 56388 ms, 99% : 56388 ms, 95 : 56388 ms, 90% : 56388 ms.

Average data rate: 0.002 MB/s
Result count 3, range 56388 ms to  56388 ms.

sendList failed peers count : 3 [50 %]
- Peer ID : Apple-Iphone5-1_PT5195.3svwkg==, Tried : 5

- Peer ID : Apple-Iphone5-1_PT5195.3svwkg==, Tried : 5
- Peer ID : Apple-Iphone5-1_PT5195.3svwkg==, Tried : 5
sendList never tried peers count : 3 [33.333333333333336 %]

- Peer ID : Apple-IpadAir2-1_PT8764.Ptw77g==
- Peer ID : Apple-IpadAir2-1_PT8764.Ptw77g==
- Peer ID : Apple-IpadAir2-1_PT8764.Ptw77g==

--------------- Apple-Iphone5s-1_PT9511 --------------------- : 2
peersList : 100% : 661 ms, 99% : 661 ms, 95 : 661 ms, 90% : 661 ms.

Result count 1, range 661 ms to  661 ms.
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.

Average data rate: NaN MB/s
Results list does not contain any items
sendList failed peers count : 3 [100 %]

- Peer ID : Apple-IpadAir2-1_PT8764.Y1JJAA==, Tried : 5
- Peer ID : Apple-IpadAir2-1_PT8764.Y1JJAA==, Tried : 5
- Peer ID : Apple-IpadAir2-1_PT8764.Y1JJAA==, Tried : 5
sendList never tried peers count : 3 [50 %]

- Peer ID : Apple-Iphone6-1_PT4682.uK405g==
- Peer ID : Apple-Iphone6-1_PT4682.uK405g==
- Peer ID : Apple-Iphone6-1_PT4682.uK405g==

--------------- Apple-IpadAir2-1_PT8764 --------------------- : 3

peersList : 100% : 1123 ms, 99% : 1123 ms, 95 : 1123 ms, 90% : 1123 ms.
Result count 1, range 1123 ms to  1123 ms.
sendList : 100% : 46154 ms, 99% : 46154 ms, 95 : 46154 ms, 90% : 46154 ms.

Average data rate: 0.006 MB/s
Result count 9, range 3540 ms to  46154 ms.

sendList failed peers count : 3 [25 %]
- Peer ID : Apple-Iphone6-1_PT4682.4oKZxQ==, Tried : 5
- Peer ID : Apple-Iphone6-1_PT4682.4oKZxQ==, Tried : 5
- Peer ID : Apple-Iphone6-1_PT4682.4oKZxQ==, Tried : 5

sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5-1_PT5195 --------------------- : 4
peersList : 100% : 1136 ms, 99% : 1136 ms, 95 : 1136 ms, 90% : 1136 ms.

Result count 1, range 1136 ms to  1136 ms.
sendList : 100% : 46612 ms, 99% : 46612 ms, 95 : 46612 ms, 90% : 46612 ms.

Average data rate: 0.005 MB/s
Result count 9, range 3598 ms to  46612 ms.
sendList failed peers count : 3 [25 %]

- Peer ID : Apple-Iphone6-1_PT4682.4oKZxQ==, Tried : 5
- Peer ID : Apple-Iphone6-1_PT4682.4oKZxQ==, Tried : 5
- Peer ID : Apple-Iphone6-1_PT4682.4oKZxQ==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- LGE-Nexus 5_PT1510 --------------------- : 5
peersList : 100% : 80994 ms, 99% : 80994 ms, 95 : 80994 ms, 90% : 80994 ms.
Result count 1, range 80994 ms to  80994 ms.

sendList : 100% : 1520 ms, 99% : 1520 ms, 95 : 1520 ms, 90% : 1520 ms.
Average data rate: 0.069 MB/s
Result count 3, range 1396 ms to  1520 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- HTC-HTC One M8s_PT375 --------------------- : 6
peersList : 100% : 3837 ms, 99% : 3837 ms, 95 : 3837 ms, 90% : 3837 ms.
Result count 1, range 3837 ms to  3837 ms.
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
--------------- motorola-XT1072_PT3784 --------------------- : 7
peersList : 100% : 2871 ms, 99% : 2871 ms, 95 : 2871 ms, 90% : 2871 ms.
Result count 1, range 2871 ms to  2871 ms.
sendList : 100% : 2472 ms, 99% : 2472 ms, 95 : 2472 ms, 90% : 2472 ms.
Average data rate: 0.04 MB/s
Result count 1, range 2472 ms to  2472 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- LGE-LG-H815_PT8123 --------------------- : 8
peersList : 100% : 18526 ms, 99% : 18526 ms, 95 : 18526 ms, 90% : 18526 ms.
Result count 1, range 18526 ms to  18526 ms.
sendList : 100% : 8409 ms, 99% : 8409 ms, 95 : 8409 ms, 90% : 8409 ms.
Average data rate: 0.026 MB/s
Result count 5, range 1789 ms to  8409 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-A500FU_PT884 --------------------- : 9
peersList : 100% : 4380 ms, 99% : 4380 ms, 95 : 4380 ms, 90% : 4380 ms.
Result count 1, range 4380 ms to  4380 ms.
sendList : 100% : 5970 ms, 99% : 5970 ms, 95 : 5970 ms, 90% : 5970 ms.
Average data rate: 0.02 MB/s
Result count 3, range 4536 ms to  5970 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-A300FU_PT3792 --------------------- : 10
peersList : 100% : 2724 ms, 99% : 2724 ms, 95 : 2724 ms, 90% : 2724 ms.
Result count 1, range 2724 ms to  2724 ms.
sendList : 100% : 1686 ms, 99% : 1686 ms, 95 : 1686 ms, 90% : 1686 ms.
Average data rate: 0.059 MB/s
Result count 1, range 1686 ms to  1686 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-A500FU_PT2086 --------------------- : 11
peersList : 100% : 4206 ms, 99% : 4206 ms, 95 : 4206 ms, 90% : 4206 ms.
Result count 1, range 4206 ms to  4206 ms.
sendList : 100% : 3487 ms, 99% : 3487 ms, 95 : 3487 ms, 90% : 3487 ms.
Average data rate: 0.029 MB/s
Result count 1, range 3487 ms to  3487 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-A300FU_PT4323 --------------------- : 12
peersList : 100% : 2211 ms, 99% : 2211 ms, 95 : 2211 ms, 90% : 2211 ms.
Result count 1, range 2211 ms to  2211 ms.
sendList : 100% : 2697 ms, 99% : 2697 ms, 95 : 2697 ms, 90% : 2697 ms.
Average data rate: 0.037 MB/s
Result count 1, range 2697 ms to  2697 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- LGE-LG-D855_PT3064 --------------------- : 13
peersList : 100% : 3090 ms, 99% : 3090 ms, 95 : 3090 ms, 90% : 3090 ms.
Result count 1, range 3090 ms to  3090 ms.
sendList : 100% : 24004 ms, 99% : 24004 ms, 95 : 24004 ms, 90% : 24004 ms.
Average data rate: 0.01 MB/s
Result count 3, range 2728 ms to  24004 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-G900F_PT1382 --------------------- : 14
peersList : 100% : 28459 ms, 99% : 28459 ms, 95 : 28459 ms, 90% : 28459 ms.
Result count 1, range 28459 ms to  28459 ms.
sendList : 100% : 6597 ms, 99% : 6597 ms, 95 : 6597 ms, 90% : 6597 ms.

Average data rate: 0.015 MB/s
Result count 1, range 6597 ms to  6597 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-N910C_PT1903 --------------------- : 15

peersList : 100% : 43132 ms, 99% : 43132 ms, 95 : 43132 ms, 90% : 43132 ms.
Result count 1, range 43132 ms to  43132 ms.
sendList : 100% : 4297 ms, 99% : 4297 ms, 95 : 4297 ms, 90% : 4297 ms.

Average data rate: 0.035 MB/s
Result count 2, range 1439 ms to  4297 ms.
sendList failed peers count : 0 [0 %]

sendList never tried peers count : 1 [33.333333333333336 %]
- Peer ID : 34:FC:EF:11:AE:67
--------------- LGE-LG-D722_PT1947 --------------------- : 16

peersList : 100% : 73299 ms, 99% : 73299 ms, 95 : 73299 ms, 90% : 73299 ms.
Result count 1, range 73299 ms to  73299 ms.
sendList : 100% : 8309 ms, 99% : 8309 ms, 95 : 8309 ms, 90% : 8309 ms.

Average data rate: 0.019 MB/s
Result count 3, range 3459 ms to  8309 ms.
sendList failed peers count : 0 [0 %]

sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-G900F_PT8784 --------------------- : 17
peersList : 100% : 36491 ms, 99% : 36491 ms, 95 : 36491 ms, 90% : 36491 ms.

Result count 1, range 36491 ms to  36491 ms.
sendList : 100% : 3434 ms, 99% : 3434 ms, 95 : 3434 ms, 90% : 3434 ms.
Average data rate: 0.034 MB/s

Result count 2, range 2474 ms to  3434 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------

peersList : 100% : 80994 ms, 99% : 80994 ms, 95 : 73299 ms, 90% : 43132 ms.

sendList : 100% : 56388 ms, 99% : 56388 ms, 95 : 56388 ms, 90% : 46612 ms.

Average data rate: 0.008 MB/s
--------------- end of test report ---------------------

2015-12-22T01:00:45.456Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1_PT8764.Y1JJAA==, peerAvailable=true, time=1061], sendList=[name=Apple-Iphone5s-1_PT9511.iUx4mA==, time=56388, result=OK, connections=3, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1_PT4682"]["sendList"][0], $ref=$["Apple-Iphone6-1_PT4682"]["sendList"][0]], failedPeer=[name=Apple-Iphone5-1_PT5195.3svwkg==, time=41253, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone6-1_PT4682"]["sendError"]["failedPeer"][0], $ref=$["Apple-Iphone6-1_PT4682"]["sendError"]["failedPeer"][0]], notTriedList=[name=Apple-IpadAir2-1_PT8764.Ptw77g==, time=0, result=Fail, $ref=$["Apple-Iphone6-1_PT4682"]["sendError"]["notTriedList"][0], $ref=$["Apple-Iphone6-1_PT4682"]["sendError"]["notTriedList"][0]], peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1_PT4682.4oKZxQ==, peerAvailable=true, time=661], sendList=[], failedPeer=[name=Apple-IpadAir2-1_PT8764.Y1JJAA==, time=41879, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone5s-1_PT9511"]["sendError"]["failedPeer"][0], $ref=$["Apple-Iphone5s-1_PT9511"]["sendError"]["failedPeer"][0]], notTriedList=[name=Apple-Iphone6-1_PT4682.uK405g==, time=0, result=Fail, $ref=$["Apple-Iphone5s-1_PT9511"]["sendError"]["notTriedList"][0], $ref=$["Apple-Iphone5s-1_PT9511"]["sendError"]["notTriedList"][0]], peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1_PT4682.4oKZxQ==, peerAvailable=true, time=1123], sendList=[name=Apple-Iphone5s-1_PT9511.iUx4mA==, time=3540, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1_PT8764"]["sendList"][0], $ref=$["Apple-IpadAir2-1_PT8764"]["sendList"][0], name=Apple-Iphone5-1_PT5195.x5+2Tg==, time=4653, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1_PT8764"]["sendList"][3], $ref=$["Apple-IpadAir2-1_PT8764"]["sendList"][3], name=Apple-Iphone6-1_PT4682.uK405g==, time=46154, result=OK, connections=2, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1_PT8764"]["sendList"][6], $ref=$["Apple-IpadAir2-1_PT8764"]["sendList"][6]], failedPeer=[name=Apple-Iphone6-1_PT4682.4oKZxQ==, time=42217, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-IpadAir2-1_PT8764"]["sendError"]["failedPeer"][0], $ref=$["Apple-IpadAir2-1_PT8764"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1_PT8764.Y1JJAA==, peerAvailable=true, time=1136], sendList=[name=Apple-Iphone5s-1_PT9511.iUx4mA==, time=3598, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1_PT5195"]["sendList"][0], $ref=$["Apple-Iphone5-1_PT5195"]["sendList"][0], name=Apple-IpadAir2-1_PT8764.Ptw77g==, time=4760, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1_PT5195"]["sendList"][3], $ref=$["Apple-Iphone5-1_PT5195"]["sendList"][3], name=Apple-Iphone6-1_PT4682.uK405g==, time=46612, result=OK, connections=2, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1_PT5195"]["sendList"][6], $ref=$["Apple-Iphone5-1_PT5195"]["sendList"][6]], failedPeer=[name=Apple-Iphone6-1_PT4682.4oKZxQ==, time=41739, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone5-1_PT5195"]["sendError"]["failedPeer"][0], $ref=$["Apple-Iphone5-1_PT5195"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=LGE-LG-D855_PT3064, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=80994], sendList=[name=F8:95:C7:87:85:54, time=1396, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=44:80:EB:7B:5A:05, time=1434, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=F8:95:C7:87:3C:51, time=1520, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], peersList=[peerName=samsung-SM-A500FU_PT884, peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=3837], sendList=[], failedPeer=[], notTriedList=[], peersList=[peerName=samsung-SM-A300FU_PT3792, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=2871], sendList=[name=34:FC:EF:11:AE:67, time=2472, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], peersList=[peerName=samsung-SM-A500FU_PT884, peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=18526], sendList=[name=E0:DB:10:14:E2:C0, time=1789, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=34:FC:EF:11:AE:67, time=2326, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:37:96:AB, time=3011, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=F8:95:C7:87:85:54, time=3616, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=B0:C5:59:3F:75:69, time=8409, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], peersList=[peerName=samsung-SM-A500FU_PT2086, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=4380], sendList=[name=08:EC:A9:50:75:41, time=4536, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=E0:DB:10:14:E2:C0, time=4573, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=F8:95:C7:87:85:54, time=5970, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], peersList=[peerName=samsung-SM-A300FU_PT4323, peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=2724], sendList=[name=7C:F9:0E:51:18:22, time=1686, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], peersList=[peerName=LGE-LG-D855_PT3064, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=4206], sendList=[name=F8:95:C7:87:3C:51, time=3487, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], peersList=[peerName=samsung-SM-A300FU_PT3792, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=2211], sendList=[name=44:80:EB:7B:5A:05, time=2697, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], peersList=[peerName=LGE-LG-D722_PT1947, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=3090], sendList=[name=34:FC:EF:11:AE:67, time=2728, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=90:E7:C4:F6:69:77, time=4432, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=44:80:EB:7B:5A:05, time=24004, result=OK, connections=2, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], peersList=[peerName=samsung-SM-A500FU_PT884, peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=28459], sendList=[name=F8:95:C7:87:3C:51, time=6597, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], peersList=[peerName=HTC-HTC One M8s_PT375, peerIdentifier=90:E7:C4:F6:69:77, peerAvailable=true, time=43132], sendList=[name=7C:F9:0E:51:18:22, time=1439, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:34:8A:A0, time=4297, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[name=34:FC:EF:11:AE:67, time=0, result=Fail], peersList=[peerName=samsung-SM-A500FU_PT2086, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=73299], sendList=[name=34:FC:EF:11:AE:67, time=3459, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:51:18:22, time=4439, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=F8:95:C7:87:3C:51, time=8309, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], peersList=[peerName=LGE-LG-H815_PT8123, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=36491], sendList=[name=7C:F9:0E:51:18:22, time=2474, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=58:3F:54:73:64:C0, time=3434, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[]

2015-12-22T01:00:45.475Z - debug: end to LGE-Nexus 5_PT1510

2015-12-22T01:00:45.476Z - debug: end to HTC-HTC One M8s_PT375

2015-12-22T01:00:45.478Z - debug: end to motorola-XT1072_PT3784

2015-12-22T01:00:45.479Z - debug: end to LGE-LG-H815_PT8123

2015-12-22T01:00:45.481Z - debug: end to samsung-SM-A500FU_PT884

2015-12-22T01:00:45.482Z - debug: end to samsung-SM-A300FU_PT3792

2015-12-22T01:00:45.483Z - debug: end to samsung-SM-A500FU_PT2086

2015-12-22T01:00:45.484Z - debug: end to samsung-SM-A300FU_PT4323

2015-12-22T01:00:45.485Z - debug: end to LGE-LG-D855_PT3064

2015-12-22T01:00:45.486Z - debug: end to samsung-SM-G900F_PT1382

2015-12-22T01:00:45.487Z - debug: end to samsung-SM-N910C_PT1903

2015-12-22T01:00:45.488Z - debug: end to LGE-LG-D722_PT1947

2015-12-22T01:00:45.488Z - debug: end to samsung-SM-G900F_PT8784

2015-12-22T01:00:45.489Z - debug: end to motorola-XT1039_PT77

2015-12-22T01:00:46.400Z - debug: Socket disconnected: transport close 7 (samsung-SM-A500FU_PT884)

2015-12-22T01:00:46.506Z - debug: Socket disconnected: transport close 15 (samsung-SM-G900F_PT8784)

2015-12-22T01:00:46.520Z - debug: Socket disconnected: transport close 9 (samsung-SM-A500FU_PT2086)

2015-12-22T01:00:46.643Z - debug: Socket disconnected: transport close 13 (samsung-SM-N910C_PT1903)

2015-12-22T01:00:46.652Z - debug: Socket disconnected: transport close 0 (LGE-Nexus 5_PT1510)

2015-12-22T01:00:46.659Z - debug: Socket disconnected: transport close 2 (motorola-XT1072_PT3784)

2015-12-22T01:00:46.898Z - debug: Socket disconnected: transport close 11 (samsung-SM-A300FU_PT4323)

2015-12-22T01:00:46.928Z - debug: Socket disconnected: transport close 14 (LGE-LG-D722_PT1947)

2015-12-22T01:00:47.167Z - debug: Socket disconnected: transport close 5 (LGE-LG-H815_PT8123)

2015-12-22T01:00:47.366Z - debug: Socket disconnected: transport close 10 (LGE-LG-D855_PT3064)

2015-12-22T01:00:48.986Z - debug: Socket disconnected: transport close 12 (samsung-SM-G900F_PT1382)

2015-12-22T01:02:02.591Z - debug: Socket disconnected: ping timeout 8 (samsung-SM-A300FU_PT3792)

2015-12-22T01:21:44.691Z - debug: Socket disconnected: transport close 1 (HTC-HTC One M8s_PT375)


 
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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/543122982543be8_Add_dummy_file_to_trigger_CI_tobybrad/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/543122982543be8_Add_dummy_file_to_trigger_CI_tobybrad/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/543122982543be8_Add_dummy_file_to_trigger_CI_tobybrad/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/543122982543be8_Add_dummy_file_to_trigger_CI_tobybrad/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/543122982543be8_Add_dummy_file_to_trigger_CI_tobybrad/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/543122982543be8_Add_dummy_file_to_trigger_CI_tobybrad/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/543122982543be8_Add_dummy_file_to_trigger_CI_tobybrad/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on ZX1C223JKW 
STOP log received from  0be0c6c6 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Device test finished on 0be0c6c6 
Android task is completed. [SUCCESS]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/543122982543be8_Add_dummy_file_to_trigger_CI_tobybrad/thali04_samsung-SM-G900F.md)

[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/543122982543be8_Add_dummy_file_to_trigger_CI_tobybrad/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/543122982543be8_Add_dummy_file_to_trigger_CI_tobybrad/thali04_samsung-SM-N910C.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/543122982543be8_Add_dummy_file_to_trigger_CI_tobybrad/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/543122982543be8_Add_dummy_file_to_trigger_CI_tobybrad/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/543122982543be8_Add_dummy_file_to_trigger_CI_tobybrad/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
STOP log received from  c5afcdcb Test has  SUCCEEDED
STOP log received from  4db5c8cc Test has  SUCCEEDED
Device test finished on 4db5c8cc 
Device test finished on c5afcdcb 
Android task is completed. [SUCCESS]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/543122982543be8_Add_dummy_file_to_trigger_CI_tobybrad/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/543122982543be8_Add_dummy_file_to_trigger_CI_tobybrad/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/543122982543be8_Add_dummy_file_to_trigger_CI_tobybrad/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/543122982543be8_Add_dummy_file_to_trigger_CI_tobybrad/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/543122982543be8_Add_dummy_file_to_trigger_CI_tobybrad/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/543122982543be8_Add_dummy_file_to_trigger_CI_tobybrad/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/543122982543be8_Add_dummy_file_to_trigger_CI_tobybrad/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/543122982543be8_Add_dummy_file_to_trigger_CI_tobybrad/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/543122982543be8_Add_dummy_file_to_trigger_CI_tobybrad/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/543122982543be8_Add_dummy_file_to_trigger_CI_tobybrad/iOS_Iphone5s-1.md)



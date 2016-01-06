#### Test 552541413820a6d Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-06T19:56:57.715Z - info: listening on *:3000

2016-01-06T19:56:58.093Z - debug: Device presented: samsung-SM-A300FU_PT7648 (android) perftest socket:0

2016-01-06T19:56:58.103Z - info: Setting start timeout to: 120000 (android)

2016-01-06T19:56:59.326Z - debug: Device presented: motorola-XT1072_PT324 (android) perftest socket:1

2016-01-06T19:56:59.612Z - debug: Device presented: Apple-Iphone6-1_PT9564 (ios) perftest socket:2

2016-01-06T19:56:59.613Z - info: Setting start timeout to: 120000 (ios)

2016-01-06T19:56:59.627Z - debug: Device presented: samsung-SM-A500FU_PT7080 (android) perftest socket:3

2016-01-06T19:57:00.108Z - debug: Device presented: HTC-HTC One M8s_PT9723 (android) perftest socket:4

2016-01-06T19:57:00.251Z - debug: Device presented: Apple-Iphone5s-1_PT1776 (ios) perftest socket:5

2016-01-06T19:57:00.375Z - debug: Device presented: Apple-IpadAir2-1_PT6789 (ios) perftest socket:6

2016-01-06T19:57:00.427Z - debug: Device presented: samsung-SM-A300FU_PT4192 (android) perftest socket:7

2016-01-06T19:57:00.891Z - debug: Device presented: LGE-LG-H815_PT2321 (android) perftest socket:8

2016-01-06T19:57:01.084Z - debug: Device presented: LGE-Nexus 5_PT4461 (android) perftest socket:9

2016-01-06T19:57:01.369Z - debug: Device presented: samsung-SM-A500FU_PT1593 (android) perftest socket:10

2016-01-06T19:57:01.558Z - debug: Device presented: LGE-LG-D722_PT1155 (android) perftest socket:11

2016-01-06T19:57:02.059Z - debug: Device presented: samsung-SM-N910C_PT3301 (android) perftest socket:12

2016-01-06T19:57:02.093Z - debug: Device presented: samsung-SM-G900F_PT4782 (android) perftest socket:13

2016-01-06T19:57:02.116Z - debug: Device presented: LGE-LG-D855_PT6783 (android) perftest socket:14

2016-01-06T19:57:02.217Z - debug: Device presented: samsung-SM-G900F_PT8565 (android) perftest socket:15

2016-01-06T19:57:02.563Z - debug: Device presented: Apple-Iphone5-1_PT2360 (ios) perftest socket:16

2016-01-06T19:57:02.564Z - info: Required number of devices presented

2016-01-06T19:57:02.568Z - info: Starting perf test run for platform: ios

2016-01-06T19:57:02.569Z - info: Using devices:

2016-01-06T19:57:02.571Z - info: Apple-Iphone6-1_PT9564

2016-01-06T19:57:02.573Z - info: Apple-Iphone5s-1_PT1776

2016-01-06T19:57:02.579Z - info: Apple-IpadAir2-1_PT6789

2016-01-06T19:57:02.580Z - info: Apple-Iphone5-1_PT2360

2016-01-06T19:57:02.584Z - info: Starting test: with 4 devices (ios)

2016-01-06T19:57:03.876Z - debug: Device presented: samsung-SM-G800F_PT4303 (android) perftest socket:17

2016-01-06T19:57:04.010Z - info: Received results for {"name:":"Apple-Iphone6-1_PT9564","time":1052,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-IpadAir2-1_PT6789.T0JZzA==","peerAvailable":true,"time":1051}]} Apple-Iphone6-1_PT9564 ios (4 left)

2016-01-06T19:57:04.015Z - info: Received results for {"name:":"Apple-IpadAir2-1_PT6789","time":1056,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone6-1_PT9564.cvfn7A==","peerAvailable":true,"time":1055}]} Apple-IpadAir2-1_PT6789 ios (3 left)

2016-01-06T19:57:04.029Z - info: Received results for {"name:":"Apple-Iphone5-1_PT2360","time":1147,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-IpadAir2-1_PT6789.T0JZzA==","peerAvailable":true,"time":1146}]} Apple-Iphone5-1_PT2360 ios (2 left)

2016-01-06T19:57:05.048Z - debug: Socket disconnected: transport close 17 (samsung-SM-G800F_PT4303)

2016-01-06T19:57:11.085Z - debug: Device presented: motorola-XT1039_PT1374 (android) perftest socket:18

2016-01-06T19:57:11.429Z - info: Received results for {"name:":"Apple-Iphone5s-1_PT1776","time":8231,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone5-1_PT2360.KoeEnA==","peerAvailable":true,"time":8229}]} Apple-Iphone5s-1_PT1776 ios (1 left)

2016-01-06T19:57:11.433Z - info: All test data retrieved for testFindPeers.js (ios)

2016-01-06T19:57:11.440Z - info: Remaining tests: %s ios=[testSendData.js]

2016-01-06T19:57:11.444Z - info: Continuing to next test: testSendData.js
2016-01-06T19:57:11.445Z - info: Starting test: with 4 devices (ios)

2016-01-06T19:57:11.794Z - debug: Socket disconnected: transport close 18 (motorola-XT1039_PT1374)

2016-01-06T19:58:04.938Z - info: Received results for {"name:":"Apple-IpadAir2-1_PT6789","time":53151,"result":"OK","sendList":[{"name":"Apple-IpadAir2-1_PT6789.T0JZzA==","time":41366,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-Iphone6-1_PT9564.iuO8Uw==","time":4172,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT1776.mp8cwQ==","time":3382,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT2360.wZr66g==","time":4151,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-IpadAir2-1_PT6789 ios (4 left)

2016-01-06T19:58:44.344Z - info: Received results for {"name:":"Apple-Iphone6-1_PT9564","time":92165,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT9564.cvfn7A==","time":40209,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-IpadAir2-1_PT6789.hQhn/g==","time":44136,"result":"OK","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT1776.mp8cwQ==","time":3082,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT2360.wZr66g==","time":3679,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone6-1_PT9564 ios (3 left)

2016-01-06T19:58:50.233Z - debug: Socket disconnected: ping timeout 5 (Apple-Iphone5s-1_PT1776)

2016-01-06T19:58:54.586Z - debug: Device presented: Apple-Iphone5s-1_PT1776 (ios) perftest socket:19

2016-01-06T19:58:54.587Z - info: Updating existing device: Apple-Iphone5s-1_PT1776 (05e556c3-b603-4911-80c0-a1376e7013e2)

2016-01-06T19:58:55.194Z - info: Received results for {"name:":"Apple-Iphone5-1_PT2360","time":100028,"result":"TIMEOUT","sendList":[{"name":"Apple-Iphone6-1_PT9564.iuO8Uw==","time":3516,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_PT6789.hQhn/g==","time":4165,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT1776.mp8cwQ==","time":3702,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone5-1_PT2360 ios (2 left)

2016-01-06T19:58:58.107Z - info: Start timeout elapsed for platform: android

2016-01-06T19:58:58.110Z - info: Starting perf test run for platform: android

2016-01-06T19:58:58.111Z - info: Using devices:

2016-01-06T19:58:58.112Z - info: samsung-SM-A300FU_PT7648
2016-01-06T19:58:58.112Z - info: motorola-XT1072_PT324

2016-01-06T19:58:58.113Z - info: samsung-SM-A500FU_PT7080
2016-01-06T19:58:58.114Z - info: HTC-HTC One M8s_PT9723
2016-01-06T19:58:58.114Z - info: samsung-SM-A300FU_PT4192

2016-01-06T19:58:58.115Z - info: LGE-LG-H815_PT2321
2016-01-06T19:58:58.116Z - info: LGE-Nexus 5_PT4461

2016-01-06T19:58:58.116Z - info: samsung-SM-A500FU_PT1593

2016-01-06T19:58:58.117Z - info: LGE-LG-D722_PT1155

2016-01-06T19:58:58.118Z - info: samsung-SM-N910C_PT3301
2016-01-06T19:58:58.118Z - info: samsung-SM-G900F_PT4782
2016-01-06T19:58:58.119Z - info: LGE-LG-D855_PT6783
2016-01-06T19:58:58.120Z - info: samsung-SM-G900F_PT8565
2016-01-06T19:58:58.121Z - info: samsung-SM-G800F_PT4303
2016-01-06T19:58:58.122Z - info: motorola-XT1039_PT1374

2016-01-06T19:58:58.123Z - info: Starting test: with 15 devices (android)

2016-01-06T19:58:59.656Z - info: Start timeout elapsed for platform: ios

2016-01-06T19:58:59.657Z - info: Tests for ios already running or completed

2016-01-06T19:59:01.900Z - info: Received results for {"name:":"samsung-SM-A300FU_PT7648","time":2881,"result":"OK","peersList":[{"peerName":"samsung-SM-A500FU_PT1593","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":2878}]} samsung-SM-A300FU_PT7648 android (15 left)

2016-01-06T19:59:02.587Z - info: server timeout for test: testFindPeers.js (ios)

2016-01-06T19:59:02.590Z - info: All test data retrieved for testFindPeers.js (ios)

2016-01-06T19:59:02.592Z - info: No results from Apple-Iphone5s-1_PT1776

2016-01-06T19:59:02.600Z - info: Remaining tests: %s ios=[], android=[testFindPeers.js, testSendData.js]

2016-01-06T19:59:02.602Z - info: ALL DONE !!!

{ 'name:': 'Apple-Iphone6-1_PT9564',
  time: 1052,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1_PT6789.T0JZzA==',
       peerAvailable: true,
       time: 1051 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT1776',
  time: 8231,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1_PT2360.KoeEnA==',
       peerAvailable: true,
       time: 8229 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT6789',
  time: 1056,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT9564.cvfn7A==',
       peerAvailable: true,
       time: 1055 } ] }

{ 'name:': 'Apple-Iphone5-1_PT2360',
  time: 1147,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1_PT6789.T0JZzA==',
       peerAvailable: true,
       time: 1146 } ] }

{ 'name:': 'Apple-Iphone6-1_PT9564',
  time: 92165,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT9564.cvfn7A==',
       time: 40209,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT6789.hQhn/g==',
       time: 44136,
       result: 'OK',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT1776.mp8cwQ==',
       time: 3082,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT2360.wZr66g==',
       time: 3679,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT6789',
  time: 53151,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT6789.T0JZzA==',
       time: 41366,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT9564.iuO8Uw==',
       time: 4172,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT1776.mp8cwQ==',
       time: 3382,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT2360.wZr66g==',
       time: 4151,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1_PT2360',
  time: 100028,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT9564.iuO8Uw==',
       time: 3516,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT6789.hQhn/g==',
       time: 4165,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT1776.mp8cwQ==',
       time: 3702,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

--------------- test report ---------------------
--------------- Apple-Iphone6-1_PT9564 --------------------- : 1

peersList : 100% : 1051 ms, 99% : 1051 ms, 95 : 1051 ms, 90% : 1051 ms.

Result count 1, range 1051 ms to  1051 ms.

sendList : 100% : 44136 ms, 99% : 44136 ms, 95 : 44136 ms, 90% : 44136 ms.

Average data rate: 0.006 MB/s

Result count 3, range 3082 ms to  44136 ms.
sendList failed peers count : 1 [25 %]

- Peer ID : Apple-Iphone6-1_PT9564.cvfn7A==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5s-1_PT1776 --------------------- : 2

peersList : 100% : 8229 ms, 99% : 8229 ms, 95 : 8229 ms, 90% : 8229 ms.
Result count 1, range 8229 ms to  8229 ms.
--------------- Apple-IpadAir2-1_PT6789 --------------------- : 3
peersList : 100% : 1055 ms, 99% : 1055 ms, 95 : 1055 ms, 90% : 1055 ms.

Result count 1, range 1055 ms to  1055 ms.
sendList : 100% : 4172 ms, 99% : 4172 ms, 95 : 4172 ms, 90% : 4172 ms.
Average data rate: 0.026 MB/s
Result count 3, range 3382 ms to  4172 ms.

sendList failed peers count : 1 [25 %]
- Peer ID : Apple-IpadAir2-1_PT6789.T0JZzA==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5-1_PT2360 --------------------- : 4

peersList : 100% : 1146 ms, 99% : 1146 ms, 95 : 1146 ms, 90% : 1146 ms.
Result count 1, range 1146 ms to  1146 ms.
sendList : 100% : 4165 ms, 99% : 4165 ms, 95 : 4165 ms, 90% : 4165 ms.
Average data rate: 0.026 MB/s
Result count 3, range 3516 ms to  4165 ms.
sendList failed peers count : 0 [0 %]

sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------
peersList : 100% : 8229 ms, 99% : 8229 ms, 95 : 8229 ms, 90% : 8229 ms.
sendList : 100% : 44136 ms, 99% : 44136 ms, 95 : 44136 ms, 90% : 4172 ms.

Average data rate: 0.012 MB/s
--------------- end of test report ---------------------

2016-01-06T19:59:02.711Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1_PT6789.T0JZzA==, peerAvailable=true, time=1051], sendList=[name=Apple-Iphone5s-1_PT1776.mp8cwQ==, time=3082, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1_PT2360.wZr66g==, time=3679, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1_PT6789.hQhn/g==, time=44136, result=OK, connections=5, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone6-1_PT9564.cvfn7A==, time=40209, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1_PT2360.KoeEnA==, peerAvailable=true, time=8229], peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1_PT9564.cvfn7A==, peerAvailable=true, time=1055], sendList=[name=Apple-Iphone5s-1_PT1776.mp8cwQ==, time=3382, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1_PT2360.wZr66g==, time=4151, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone6-1_PT9564.iuO8Uw==, time=4172, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-IpadAir2-1_PT6789.T0JZzA==, time=41366, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1_PT6789.T0JZzA==, peerAvailable=true, time=1146], sendList=[name=Apple-Iphone6-1_PT9564.iuO8Uw==, time=3516, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5s-1_PT1776.mp8cwQ==, time=3702, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1_PT6789.hQhn/g==, time=4165, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[]

2016-01-06T19:59:02.719Z - debug: end to Apple-Iphone6-1_PT9564

2016-01-06T19:59:02.721Z - debug: end to Apple-Iphone5s-1_PT1776

2016-01-06T19:59:02.722Z - debug: end to Apple-IpadAir2-1_PT6789

2016-01-06T19:59:02.723Z - debug: end to Apple-Iphone5-1_PT2360

2016-01-06T19:59:02.783Z - info: Received results for {"name:":"samsung-SM-A300FU_PT4192","time":3870,"result":"OK","peersList":[{"peerName":"samsung-SM-A300FU_PT7648","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":3868}]} samsung-SM-A300FU_PT4192 android (14 left)

2016-01-06T19:59:02.942Z - info: Received results for {"name:":"LGE-LG-D722_PT1155","time":2777,"result":"OK","peersList":[{"peerName":"LGE-LG-D855_PT6783","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":2777}]} LGE-LG-D722_PT1155 android (13 left)

2016-01-06T19:59:03.201Z - info: Received results for {"name:":"samsung-SM-A500FU_PT1593","time":4179,"result":"OK","peersList":[{"peerName":"LGE-LG-D855_PT6783","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":4178}]} samsung-SM-A500FU_PT1593 android (12 left)

2016-01-06T19:59:03.726Z - info: Received results for {"name:":"samsung-SM-A500FU_PT7080","time":4809,"result":"OK","peersList":[{"peerName":"motorola-XT1072_PT324","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true,"time":4808}]} samsung-SM-A500FU_PT7080 android (11 left)

2016-01-06T19:59:04.553Z - debug: state: android running

2016-01-06T19:59:04.554Z - debug: state: ios completed

2016-01-06T19:59:04.929Z - info: Received results for {"name:":"samsung-SM-N910C_PT3301","time":6024,"result":"OK","peersList":[{"peerName":"samsung-SM-A500FU_PT1593","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":6021}]} samsung-SM-N910C_PT3301 android (10 left)

2016-01-06T19:59:05.401Z - debug: Socket disconnected: transport close 2 (Apple-Iphone6-1_PT9564)

2016-01-06T19:59:06.143Z - debug: Socket disconnected: transport close 16 (Apple-Iphone5-1_PT2360)

2016-01-06T19:59:06.610Z - debug: Socket disconnected: transport close 6 (Apple-IpadAir2-1_PT6789)

2016-01-06T19:59:06.857Z - debug: Socket disconnected: transport close 19 (Apple-Iphone5s-1_PT1776)

2016-01-06T19:59:07.691Z - info: Received results for {"name:":"samsung-SM-G900F_PT8565","time":9282,"result":"OK","peersList":[{"peerName":"samsung-SM-A300FU_PT7648","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":9277}]} samsung-SM-G900F_PT8565 android (9 left)

2016-01-06T19:59:08.173Z - info: Received results for {"name:":"motorola-XT1072_PT324","time":9227,"result":"OK","peersList":[{"peerName":"samsung-SM-A300FU_PT4192","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":9226}]} motorola-XT1072_PT324 android (8 left)

2016-01-06T19:59:08.849Z - info: Received results for {"name:":"HTC-HTC One M8s_PT9723","time":4667,"result":"OK","peersList":[{"peerName":"samsung-SM-A500FU_PT7080","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":4664}]} HTC-HTC One M8s_PT9723 android (7 left)

2016-01-06T19:59:09.120Z - info: Received results for {"name:":"LGE-LG-D855_PT6783","time":2083,"result":"OK","peersList":[{"peerName":"samsung-SM-A500FU_PT7080","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":2082}]} LGE-LG-D855_PT6783 android (6 left)

2016-01-06T19:59:11.449Z - info: server timeout for test: testSendData.js (ios)

2016-01-06T19:59:11.452Z - info: All test data retrieved for testSendData.js (ios)

2016-01-06T19:59:11.453Z - info: No results from Apple-Iphone5s-1_PT1776

2016-01-06T19:59:11.455Z - info: Remaining tests: %s ios=[], android=[testFindPeers.js, testSendData.js]

2016-01-06T19:59:11.456Z - info: ALL DONE !!!

{ 'name:': 'Apple-Iphone6-1_PT9564',
  time: 1052,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1_PT6789.T0JZzA==',
       peerAvailable: true,
       time: 1051 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT1776',
  time: 8231,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1_PT2360.KoeEnA==',
       peerAvailable: true,
       time: 8229 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT6789',
  time: 1056,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT9564.cvfn7A==',
       peerAvailable: true,
       time: 1055 } ] }

{ 'name:': 'Apple-Iphone5-1_PT2360',
  time: 1147,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1_PT6789.T0JZzA==',
       peerAvailable: true,
       time: 1146 } ] }

{ 'name:': 'Apple-Iphone6-1_PT9564',
  time: 92165,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT9564.cvfn7A==',
       time: 40209,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT6789.hQhn/g==',
       time: 44136,
       result: 'OK',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT1776.mp8cwQ==',
       time: 3082,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT2360.wZr66g==',
       time: 3679,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT6789',
  time: 53151,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT6789.T0JZzA==',
       time: 41366,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT9564.iuO8Uw==',
       time: 4172,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT1776.mp8cwQ==',
       time: 3382,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT2360.wZr66g==',
       time: 4151,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1_PT2360',
  time: 100028,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT9564.iuO8Uw==',
       time: 3516,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT6789.hQhn/g==',
       time: 4165,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT1776.mp8cwQ==',
       time: 3702,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1_PT9564',
  time: 92165,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT9564.cvfn7A==',
       time: 40209,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT6789.hQhn/g==',
       time: 44136,
       result: 'OK',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT1776.mp8cwQ==',
       time: 3082,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT2360.wZr66g==',
       time: 3679,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT6789',
  time: 53151,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT6789.T0JZzA==',
       time: 41366,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT9564.iuO8Uw==',
       time: 4172,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT1776.mp8cwQ==',
       time: 3382,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT2360.wZr66g==',
       time: 4151,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1_PT2360',
  time: 100028,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT9564.iuO8Uw==',
       time: 3516,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT6789.hQhn/g==',
       time: 4165,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT1776.mp8cwQ==',
       time: 3702,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

--------------- test report ---------------------
--------------- Apple-Iphone6-1_PT9564 --------------------- : 1
peersList : 100% : 1051 ms, 99% : 1051 ms, 95 : 1051 ms, 90% : 1051 ms.
Result count 1, range 1051 ms to  1051 ms.
sendList : 100% : 44136 ms, 99% : 44136 ms, 95 : 44136 ms, 90% : 44136 ms.
Average data rate: 0.006 MB/s
Result count 6, range 3082 ms to  44136 ms.
sendList failed peers count : 2 [25 %]
- Peer ID : Apple-Iphone6-1_PT9564.cvfn7A==, Tried : 5
- Peer ID : Apple-Iphone6-1_PT9564.cvfn7A==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5s-1_PT1776 --------------------- : 2
peersList : 100% : 8229 ms, 99% : 8229 ms, 95 : 8229 ms, 90% : 8229 ms.
Result count 1, range 8229 ms to  8229 ms.
--------------- Apple-IpadAir2-1_PT6789 --------------------- : 3
peersList : 100% : 1055 ms, 99% : 1055 ms, 95 : 1055 ms, 90% : 1055 ms.
Result count 1, range 1055 ms to  1055 ms.
sendList : 100% : 4172 ms, 99% : 4172 ms, 95 : 4172 ms, 90% : 4172 ms.
Average data rate: 0.026 MB/s
Result count 6, range 3382 ms to  4172 ms.
sendList failed peers count : 2 [25 %]
- Peer ID : Apple-IpadAir2-1_PT6789.T0JZzA==, Tried : 5
- Peer ID : Apple-IpadAir2-1_PT6789.T0JZzA==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5-1_PT2360 --------------------- : 4
peersList : 100% : 1146 ms, 99% : 1146 ms, 95 : 1146 ms, 90% : 1146 ms.
Result count 1, range 1146 ms to  1146 ms.
sendList : 100% : 4165 ms, 99% : 4165 ms, 95 : 4165 ms, 90% : 4165 ms.
Average data rate: 0.026 MB/s
Result count 6, range 3516 ms to  4165 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------
peersList : 100% : 8229 ms, 99% : 8229 ms, 95 : 8229 ms, 90% : 8229 ms.
sendList : 100% : 44136 ms, 99% : 44136 ms, 95 : 44136 ms, 90% : 4172 ms.
Average data rate: 0.012 MB/s
--------------- end of test report ---------------------
2016-01-06T19:59:11.534Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1_PT6789.T0JZzA==, peerAvailable=true, time=1051], sendList=[name=Apple-Iphone5s-1_PT1776.mp8cwQ==, time=3082, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1_PT9564"]["sendList"][0], name=Apple-Iphone5-1_PT2360.wZr66g==, time=3679, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1_PT9564"]["sendList"][2], name=Apple-IpadAir2-1_PT6789.hQhn/g==, time=44136, result=OK, connections=5, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1_PT9564"]["sendList"][4]], failedPeer=[name=Apple-Iphone6-1_PT9564.cvfn7A==, time=40209, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone6-1_PT9564"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1_PT2360.KoeEnA==, peerAvailable=true, time=8229], peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1_PT9564.cvfn7A==, peerAvailable=true, time=1055], sendList=[name=Apple-Iphone5s-1_PT1776.mp8cwQ==, time=3382, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1_PT6789"]["sendList"][0], name=Apple-Iphone5-1_PT2360.wZr66g==, time=4151, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1_PT6789"]["sendList"][2], name=Apple-Iphone6-1_PT9564.iuO8Uw==, time=4172, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1_PT6789"]["sendList"][4]], failedPeer=[name=Apple-IpadAir2-1_PT6789.T0JZzA==, time=41366, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-IpadAir2-1_PT6789"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1_PT6789.T0JZzA==, peerAvailable=true, time=1146], sendList=[name=Apple-Iphone6-1_PT9564.iuO8Uw==, time=3516, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1_PT2360"]["sendList"][0], name=Apple-Iphone5s-1_PT1776.mp8cwQ==, time=3702, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1_PT2360"]["sendList"][2], name=Apple-IpadAir2-1_PT6789.hQhn/g==, time=4165, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1_PT2360"]["sendList"][4]], failedPeer=[], notTriedList=[]
2016-01-06T19:59:11.544Z - debug: end to Apple-Iphone6-1_PT9564
2016-01-06T19:59:11.545Z - debug: end to Apple-Iphone5s-1_PT1776

2016-01-06T19:59:11.546Z - debug: end to Apple-IpadAir2-1_PT6789
2016-01-06T19:59:11.547Z - debug: end to Apple-Iphone5-1_PT2360

2016-01-06T19:59:13.715Z - info: Received results for {"name:":"samsung-SM-G900F_PT4782","time":14976,"result":"OK","peersList":[{"peerName":"samsung-SM-A500FU_PT7080","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":14972}]} samsung-SM-G900F_PT4782 android (5 left)

2016-01-06T19:59:22.487Z - info: Received results for {"name:":"LGE-LG-H815_PT2321","time":21203,"result":"OK","peersList":[{"peerName":"samsung-SM-G900F_PT8565","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":21200}]} LGE-LG-H815_PT2321 android (4 left)

2016-01-06T19:59:44.130Z - info: Received results for {"name:":"LGE-Nexus 5_PT4461","time":45785,"result":"OK","peersList":[{"peerName":"samsung-SM-A500FU_PT1593","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":45782}]} LGE-Nexus 5_PT4461 android (3 left)

2016-01-06T20:00:54.446Z - debug: Socket disconnected: ping timeout 1 (motorola-XT1072_PT324)

2016-01-06T20:00:58.128Z - info: server timeout for test: testFindPeers.js (android)

2016-01-06T20:00:58.131Z - info: All test data retrieved for testFindPeers.js (android)

2016-01-06T20:00:58.144Z - info: No results from samsung-SM-G800F_PT4303

2016-01-06T20:00:58.145Z - info: No results from motorola-XT1039_PT1374

2016-01-06T20:00:58.146Z - info: Remaining tests: %s ios=[], android=[testSendData.js]
2016-01-06T20:00:58.149Z - info: Continuing to next test: testSendData.js
2016-01-06T20:00:58.150Z - info: Starting test: with 15 devices (android)

2016-01-06T20:02:38.281Z - info: Received results for {"name:":"samsung-SM-A300FU_PT7648","time":100057,"result":"TIMEOUT","sendList":[{"name":"E0:DB:10:14:E2:C0","time":28214,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"34:FC:EF:11:AE:67","time":1996,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} samsung-SM-A300FU_PT7648 android (15 left)

2016-01-06T20:02:38.412Z - info: Received results for {"name:":"samsung-SM-G900F_PT8565","time":100064,"result":"TIMEOUT","sendList":[{"name":"F8:95:C7:87:3C:51","time":7724,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":2705,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} samsung-SM-G900F_PT8565 android (14 left)

2016-01-06T20:02:38.459Z - info: Received results for {"name:":"LGE-Nexus 5_PT4461","time":100033,"result":"TIMEOUT","sendList":[{"name":"90:E7:C4:F6:69:77","time":6818,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":6206,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:34:8A:A0","time":4050,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:75:41","time":2916,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} LGE-Nexus 5_PT4461 android (13 left)

2016-01-06T20:02:38.473Z - info: Received results for {"name:":"samsung-SM-A500FU_PT7080","time":100052,"result":"TIMEOUT","sendList":[]} samsung-SM-A500FU_PT7080 android (12 left)

2016-01-06T20:02:38.497Z - info: Received results for {"name:":"LGE-LG-D722_PT1155","time":100211,"result":"TIMEOUT","sendList":[]} LGE-LG-D722_PT1155 android (11 left)

2016-01-06T20:02:38.577Z - info: Received results for {"name:":"samsung-SM-N910C_PT3301","time":100075,"result":"TIMEOUT","sendList":[{"name":"34:FC:EF:11:AE:67","time":5645,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:76:27","time":2691,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} samsung-SM-N910C_PT3301 android (10 left)

2016-01-06T20:02:38.631Z - info: Received results for {"name:":"samsung-SM-G900F_PT4782","time":100070,"result":"TIMEOUT","sendList":[{"name":"58:3F:54:73:64:C0","time":6821,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":1897,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} samsung-SM-G900F_PT4782 android (9 left)

2016-01-06T20:02:39.083Z - debug: Socket disconnected: ping timeout 4 (HTC-HTC One M8s_PT9723)

2016-01-06T20:02:39.423Z - info: Received results for {"name:":"LGE-LG-H815_PT2321","time":100068,"result":"TIMEOUT","sendList":[{"name":"E0:DB:10:14:E2:C0","time":13184,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"58:3F:54:73:64:C0","time":6848,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:34:8A:A0","time":3318,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"90:E7:C4:F6:69:77","time":3880,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} LGE-LG-H815_PT2321 android (8 left)

2016-01-06T20:02:40.337Z - info: Received results for {"name:":"samsung-SM-A300FU_PT4192","time":100048,"result":"TIMEOUT","sendList":[]} samsung-SM-A300FU_PT4192 android (7 left)

2016-01-06T20:02:45.053Z - debug: Socket disconnected: ping timeout 10 (samsung-SM-A500FU_PT1593)

2016-01-06T20:02:49.307Z - info: Received results for {"name:":"LGE-LG-D855_PT6783","time":100079,"result":"TIMEOUT","sendList":[{"name":"F8:95:C7:87:3C:51","time":4390,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":6100,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} LGE-LG-D855_PT6783 android (6 left)

2016-01-06T20:02:58.155Z - info: server timeout for test: testSendData.js (android)

2016-01-06T20:02:58.157Z - info: All test data retrieved for testSendData.js (android)

2016-01-06T20:02:58.161Z - info: No results from motorola-XT1072_PT324

2016-01-06T20:02:58.163Z - info: No results from HTC-HTC One M8s_PT9723

2016-01-06T20:02:58.167Z - info: No results from samsung-SM-A500FU_PT1593

2016-01-06T20:02:58.174Z - info: No results from samsung-SM-G800F_PT4303

2016-01-06T20:02:58.178Z - info: No results from motorola-XT1039_PT1374

2016-01-06T20:02:58.179Z - info: Remaining tests: %s ios=[], android=[]

2016-01-06T20:02:58.180Z - info: ALL DONE !!!

{ 'name:': 'Apple-Iphone6-1_PT9564',
  time: 1052,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1_PT6789.T0JZzA==',
       peerAvailable: true,
       time: 1051 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT1776',
  time: 8231,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1_PT2360.KoeEnA==',
       peerAvailable: true,
       time: 8229 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT6789',
  time: 1056,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT9564.cvfn7A==',
       peerAvailable: true,
       time: 1055 } ] }

{ 'name:': 'Apple-Iphone5-1_PT2360',
  time: 1147,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1_PT6789.T0JZzA==',
       peerAvailable: true,
       time: 1146 } ] }

{ 'name:': 'Apple-Iphone6-1_PT9564',
  time: 92165,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT9564.cvfn7A==',
       time: 40209,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT6789.hQhn/g==',
       time: 44136,
       result: 'OK',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT1776.mp8cwQ==',
       time: 3082,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT2360.wZr66g==',
       time: 3679,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT6789',
  time: 53151,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT6789.T0JZzA==',
       time: 41366,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT9564.iuO8Uw==',
       time: 4172,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT1776.mp8cwQ==',
       time: 3382,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT2360.wZr66g==',
       time: 4151,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1_PT2360',
  time: 100028,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT9564.iuO8Uw==',
       time: 3516,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT6789.hQhn/g==',
       time: 4165,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT1776.mp8cwQ==',
       time: 3702,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1_PT9564',
  time: 92165,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT9564.cvfn7A==',
       time: 40209,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT6789.hQhn/g==',
       time: 44136,
       result: 'OK',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT1776.mp8cwQ==',
       time: 3082,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT2360.wZr66g==',
       time: 3679,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT6789',
  time: 53151,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT6789.T0JZzA==',
       time: 41366,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT9564.iuO8Uw==',
       time: 4172,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT1776.mp8cwQ==',
       time: 3382,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT2360.wZr66g==',
       time: 4151,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1_PT2360',
  time: 100028,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT9564.iuO8Uw==',
       time: 3516,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT6789.hQhn/g==',
       time: 4165,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT1776.mp8cwQ==',
       time: 3702,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'samsung-SM-A300FU_PT7648',
  time: 2881,
  result: 'OK',
  peersList: 
   [ { peerName: 'samsung-SM-A500FU_PT1593',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 2878 } ] }

{ 'name:': 'motorola-XT1072_PT324',
  time: 9227,
  result: 'OK',
  peersList: 
   [ { peerName: 'samsung-SM-A300FU_PT4192',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 9226 } ] }

{ 'name:': 'samsung-SM-A500FU_PT7080',
  time: 4809,
  result: 'OK',
  peersList: 
   [ { peerName: 'motorola-XT1072_PT324',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 4808 } ] }

{ 'name:': 'HTC-HTC One M8s_PT9723',
  time: 4667,
  result: 'OK',
  peersList: 
   [ { peerName: 'samsung-SM-A500FU_PT7080',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 4664 } ] }

{ 'name:': 'samsung-SM-A300FU_PT4192',
  time: 3870,
  result: 'OK',
  peersList: 
   [ { peerName: 'samsung-SM-A300FU_PT7648',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 3868 } ] }

{ 'name:': 'LGE-LG-H815_PT2321',
  time: 21203,
  result: 'OK',
  peersList: 
   [ { peerName: 'samsung-SM-G900F_PT8565',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 21200 } ] }

{ 'name:': 'LGE-Nexus 5_PT4461',
  time: 45785,
  result: 'OK',
  peersList: 
   [ { peerName: 'samsung-SM-A500FU_PT1593',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 45782 } ] }

{ 'name:': 'samsung-SM-A500FU_PT1593',
  time: 4179,
  result: 'OK',
  peersList: 
   [ { peerName: 'LGE-LG-D855_PT6783',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 4178 } ] }

{ 'name:': 'LGE-LG-D722_PT1155',
  time: 2777,
  result: 'OK',
  peersList: 
   [ { peerName: 'LGE-LG-D855_PT6783',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 2777 } ] }

{ 'name:': 'samsung-SM-N910C_PT3301',
  time: 6024,
  result: 'OK',
  peersList: 
   [ { peerName: 'samsung-SM-A500FU_PT1593',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 6021 } ] }

{ 'name:': 'samsung-SM-G900F_PT4782',
  time: 14976,
  result: 'OK',
  peersList: 
   [ { peerName: 'samsung-SM-A500FU_PT7080',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 14972 } ] }

{ 'name:': 'LGE-LG-D855_PT6783',
  time: 2083,
  result: 'OK',
  peersList: 
   [ { peerName: 'samsung-SM-A500FU_PT7080',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 2082 } ] }

{ 'name:': 'samsung-SM-G900F_PT8565',
  time: 9282,
  result: 'OK',
  peersList: 
   [ { peerName: 'samsung-SM-A300FU_PT7648',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 9277 } ] }

{ 'name:': 'samsung-SM-A300FU_PT7648',
  time: 100057,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'E0:DB:10:14:E2:C0',
       time: 28214,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '34:FC:EF:11:AE:67',
       time: 1996,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'samsung-SM-A500FU_PT7080',
  time: 100052,
  result: 'TIMEOUT',
  sendList: [] }

{ 'name:': 'samsung-SM-A300FU_PT4192',
  time: 100048,
  result: 'TIMEOUT',
  sendList: [] }

{ 'name:': 'LGE-LG-H815_PT2321',
  time: 100068,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'E0:DB:10:14:E2:C0',
       time: 13184,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '58:3F:54:73:64:C0',
       time: 6848,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:34:8A:A0',
       time: 3318,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '90:E7:C4:F6:69:77',
       time: 3880,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'LGE-Nexus 5_PT4461',
  time: 100033,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '90:E7:C4:F6:69:77',
       time: 6818,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'E0:DB:10:14:E2:C0',
       time: 6206,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:34:8A:A0',
       time: 4050,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '08:EC:A9:50:75:41',
       time: 2916,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'LGE-LG-D722_PT1155',
  time: 100211,
  result: 'TIMEOUT',
  sendList: [] }

{ 'name:': 'samsung-SM-N910C_PT3301',
  time: 100075,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '34:FC:EF:11:AE:67',
       time: 5645,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '08:EC:A9:50:76:27',
       time: 2691,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'samsung-SM-G900F_PT4782',
  time: 100070,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '58:3F:54:73:64:C0',
       time: 6821,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:3C:51',
       time: 1897,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }
{ 'name:': 'LGE-LG-D855_PT6783',
  time: 100079,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'F8:95:C7:87:3C:51',
       time: 4390,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:85:54',
       time: 6100,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }
{ 'name:': 'samsung-SM-G900F_PT8565',
  time: 100064,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'F8:95:C7:87:3C:51',
       time: 7724,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'E0:DB:10:14:E2:C0',
       time: 2705,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }
--------------- test report ---------------------
--------------- Apple-Iphone6-1_PT9564 --------------------- : 1
peersList : 100% : 1051 ms, 99% : 1051 ms, 95 : 1051 ms, 90% : 1051 ms.
Result count 1, range 1051 ms to  1051 ms.
sendList : 100% : 44136 ms, 99% : 44136 ms, 95 : 44136 ms, 90% : 44136 ms.

Average data rate: 0.006 MB/s
Result count 6, range 3082 ms to  44136 ms.
sendList failed peers count : 2 [25 %]
- Peer ID : Apple-Iphone6-1_PT9564.cvfn7A==, Tried : 5

- Peer ID : Apple-Iphone6-1_PT9564.cvfn7A==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5s-1_PT1776 --------------------- : 2
peersList : 100% : 8229 ms, 99% : 8229 ms, 95 : 8229 ms, 90% : 8229 ms.
Result count 1, range 8229 ms to  8229 ms.
--------------- Apple-IpadAir2-1_PT6789 --------------------- : 3
peersList : 100% : 1055 ms, 99% : 1055 ms, 95 : 1055 ms, 90% : 1055 ms.

Result count 1, range 1055 ms to  1055 ms.
sendList : 100% : 4172 ms, 99% : 4172 ms, 95 : 4172 ms, 90% : 4172 ms.
Average data rate: 0.026 MB/s
Result count 6, range 3382 ms to  4172 ms.
sendList failed peers count : 2 [25 %]

- Peer ID : Apple-IpadAir2-1_PT6789.T0JZzA==, Tried : 5
- Peer ID : Apple-IpadAir2-1_PT6789.T0JZzA==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5-1_PT2360 --------------------- : 4
peersList : 100% : 1146 ms, 99% : 1146 ms, 95 : 1146 ms, 90% : 1146 ms.
Result count 1, range 1146 ms to  1146 ms.
sendList : 100% : 4165 ms, 99% : 4165 ms, 95 : 4165 ms, 90% : 4165 ms.
Average data rate: 0.026 MB/s
Result count 6, range 3516 ms to  4165 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-A300FU_PT7648 --------------------- : 5
peersList : 100% : 2878 ms, 99% : 2878 ms, 95 : 2878 ms, 90% : 2878 ms.
Result count 1, range 2878 ms to  2878 ms.
sendList : 100% : 28214 ms, 99% : 28214 ms, 95 : 28214 ms, 90% : 28214 ms.
Average data rate: 0.007 MB/s
Result count 2, range 1996 ms to  28214 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- motorola-XT1072_PT324 --------------------- : 6
peersList : 100% : 9226 ms, 99% : 9226 ms, 95 : 9226 ms, 90% : 9226 ms.
Result count 1, range 9226 ms to  9226 ms.
--------------- samsung-SM-A500FU_PT7080 --------------------- : 7
peersList : 100% : 4808 ms, 99% : 4808 ms, 95 : 4808 ms, 90% : 4808 ms.

Result count 1, range 4808 ms to  4808 ms.
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items

--------------- HTC-HTC One M8s_PT9723 --------------------- : 8
peersList : 100% : 4664 ms, 99% : 4664 ms, 95 : 4664 ms, 90% : 4664 ms.
Result count 1, range 4664 ms to  4664 ms.
--------------- samsung-SM-A300FU_PT4192 --------------------- : 9
peersList : 100% : 3868 ms, 99% : 3868 ms, 95 : 3868 ms, 90% : 3868 ms.

Result count 1, range 3868 ms to  3868 ms.
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
--------------- LGE-LG-H815_PT2321 --------------------- : 10

peersList : 100% : 21200 ms, 99% : 21200 ms, 95 : 21200 ms, 90% : 21200 ms.
Result count 1, range 21200 ms to  21200 ms.
sendList : 100% : 13184 ms, 99% : 13184 ms, 95 : 13184 ms, 90% : 13184 ms.
Average data rate: 0.015 MB/s
Result count 4, range 3318 ms to  13184 ms.

sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- LGE-Nexus 5_PT4461 --------------------- : 11
peersList : 100% : 45782 ms, 99% : 45782 ms, 95 : 45782 ms, 90% : 45782 ms.
Result count 1, range 45782 ms to  45782 ms.

sendList : 100% : 6818 ms, 99% : 6818 ms, 95 : 6818 ms, 90% : 6818 ms.
Average data rate: 0.02 MB/s
Result count 4, range 2916 ms to  6818 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- samsung-SM-A500FU_PT1593 --------------------- : 12
peersList : 100% : 4178 ms, 99% : 4178 ms, 95 : 4178 ms, 90% : 4178 ms.
Result count 1, range 4178 ms to  4178 ms.
--------------- LGE-LG-D722_PT1155 --------------------- : 13
peersList : 100% : 2777 ms, 99% : 2777 ms, 95 : 2777 ms, 90% : 2777 ms.

Result count 1, range 2777 ms to  2777 ms.
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
--------------- samsung-SM-N910C_PT3301 --------------------- : 14

peersList : 100% : 6021 ms, 99% : 6021 ms, 95 : 6021 ms, 90% : 6021 ms.
Result count 1, range 6021 ms to  6021 ms.
sendList : 100% : 5645 ms, 99% : 5645 ms, 95 : 5645 ms, 90% : 5645 ms.
Average data rate: 0.024 MB/s
Result count 2, range 2691 ms to  5645 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-G900F_PT4782 --------------------- : 15
peersList : 100% : 14972 ms, 99% : 14972 ms, 95 : 14972 ms, 90% : 14972 ms.

Result count 1, range 14972 ms to  14972 ms.
sendList : 100% : 6821 ms, 99% : 6821 ms, 95 : 6821 ms, 90% : 6821 ms.
Average data rate: 0.023 MB/s
Result count 2, range 1897 ms to  6821 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- LGE-LG-D855_PT6783 --------------------- : 16
peersList : 100% : 2082 ms, 99% : 2082 ms, 95 : 2082 ms, 90% : 2082 ms.
Result count 1, range 2082 ms to  2082 ms.
sendList : 100% : 6100 ms, 99% : 6100 ms, 95 : 6100 ms, 90% : 6100 ms.

Average data rate: 0.019 MB/s
Result count 2, range 4390 ms to  6100 ms.

sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-G900F_PT8565 --------------------- : 17
peersList : 100% : 9277 ms, 99% : 9277 ms, 95 : 9277 ms, 90% : 9277 ms.

Result count 1, range 9277 ms to  9277 ms.
sendList : 100% : 7724 ms, 99% : 7724 ms, 95 : 7724 ms, 90% : 7724 ms.
Average data rate: 0.019 MB/s

Result count 2, range 2705 ms to  7724 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- Combined ---------------------
peersList : 100% : 45782 ms, 99% : 45782 ms, 95 : 21200 ms, 90% : 14972 ms.

sendList : 100% : 44136 ms, 99% : 44136 ms, 95 : 28214 ms, 90% : 7724 ms.

Average data rate: 0.014 MB/s
--------------- end of test report ---------------------

2016-01-06T20:02:58.387Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1_PT6789.T0JZzA==, peerAvailable=true, time=1051], sendList=[name=Apple-Iphone5s-1_PT1776.mp8cwQ==, time=3082, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1_PT9564"]["sendList"][0], name=Apple-Iphone5-1_PT2360.wZr66g==, time=3679, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1_PT9564"]["sendList"][2], name=Apple-IpadAir2-1_PT6789.hQhn/g==, time=44136, result=OK, connections=5, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1_PT9564"]["sendList"][4]], failedPeer=[name=Apple-Iphone6-1_PT9564.cvfn7A==, time=40209, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone6-1_PT9564"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1_PT2360.KoeEnA==, peerAvailable=true, time=8229], peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1_PT9564.cvfn7A==, peerAvailable=true, time=1055], sendList=[name=Apple-Iphone5s-1_PT1776.mp8cwQ==, time=3382, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1_PT6789"]["sendList"][0], name=Apple-Iphone5-1_PT2360.wZr66g==, time=4151, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1_PT6789"]["sendList"][2], name=Apple-Iphone6-1_PT9564.iuO8Uw==, time=4172, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1_PT6789"]["sendList"][4]], failedPeer=[name=Apple-IpadAir2-1_PT6789.T0JZzA==, time=41366, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-IpadAir2-1_PT6789"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1_PT6789.T0JZzA==, peerAvailable=true, time=1146], sendList=[name=Apple-Iphone6-1_PT9564.iuO8Uw==, time=3516, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1_PT2360"]["sendList"][0], name=Apple-Iphone5s-1_PT1776.mp8cwQ==, time=3702, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1_PT2360"]["sendList"][2], name=Apple-IpadAir2-1_PT6789.hQhn/g==, time=4165, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1_PT2360"]["sendList"][4]], failedPeer=[], notTriedList=[], peersList=[peerName=samsung-SM-A500FU_PT1593, peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=2878], sendList=[name=34:FC:EF:11:AE:67, time=1996, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=E0:DB:10:14:E2:C0, time=28214, result=OK, connections=2, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], peersList=[peerName=samsung-SM-A300FU_PT4192, peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=9226], peersList=[peerName=motorola-XT1072_PT324, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=4808], sendList=[], failedPeer=[], notTriedList=[], peersList=[peerName=samsung-SM-A500FU_PT7080, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=4664], peersList=[peerName=samsung-SM-A300FU_PT7648, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=3868], sendList=[], failedPeer=[], notTriedList=[], peersList=[peerName=samsung-SM-G900F_PT8565, peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=21200], sendList=[name=7C:F9:0E:34:8A:A0, time=3318, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=90:E7:C4:F6:69:77, time=3880, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=58:3F:54:73:64:C0, time=6848, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=E0:DB:10:14:E2:C0, time=13184, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], peersList=[peerName=samsung-SM-A500FU_PT1593, peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=45782], sendList=[name=08:EC:A9:50:75:41, time=2916, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:34:8A:A0, time=4050, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=E0:DB:10:14:E2:C0, time=6206, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=90:E7:C4:F6:69:77, time=6818, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], peersList=[peerName=LGE-LG-D855_PT6783, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=4178], peersList=[peerName=LGE-LG-D855_PT6783, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=2777], sendList=[], failedPeer=[], notTriedList=[], peersList=[peerName=samsung-SM-A500FU_PT1593, peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=6021], sendList=[name=08:EC:A9:50:76:27, time=2691, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=34:FC:EF:11:AE:67, time=5645, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], peersList=[peerName=samsung-SM-A500FU_PT7080, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=14972], sendList=[name=F8:95:C7:87:3C:51, time=1897, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=58:3F:54:73:64:C0, time=6821, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], peersList=[peerName=samsung-SM-A500FU_PT7080, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=2082], sendList=[name=F8:95:C7:87:3C:51, time=4390, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=F8:95:C7:87:85:54, time=6100, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], peersList=[peerName=samsung-SM-A300FU_PT7648, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=9277], sendList=[name=E0:DB:10:14:E2:C0, time=2705, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=F8:95:C7:87:3C:51, time=7724, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[]

2016-01-06T20:02:58.406Z - debug: end to samsung-SM-A300FU_PT7648

2016-01-06T20:02:58.408Z - debug: end to motorola-XT1072_PT324

2016-01-06T20:02:58.409Z - debug: end to samsung-SM-A500FU_PT7080

2016-01-06T20:02:58.411Z - debug: end to HTC-HTC One M8s_PT9723

2016-01-06T20:02:58.413Z - debug: end to samsung-SM-A300FU_PT4192

2016-01-06T20:02:58.415Z - debug: end to LGE-LG-H815_PT2321

2016-01-06T20:02:58.417Z - debug: end to LGE-Nexus 5_PT4461

2016-01-06T20:02:58.418Z - debug: end to samsung-SM-A500FU_PT1593

2016-01-06T20:02:58.419Z - debug: end to LGE-LG-D722_PT1155

2016-01-06T20:02:58.421Z - debug: end to samsung-SM-N910C_PT3301

2016-01-06T20:02:58.422Z - debug: end to samsung-SM-G900F_PT4782

2016-01-06T20:02:58.423Z - debug: end to LGE-LG-D855_PT6783

2016-01-06T20:02:58.425Z - debug: end to samsung-SM-G900F_PT8565

2016-01-06T20:02:58.426Z - debug: end to samsung-SM-G800F_PT4303

2016-01-06T20:02:58.431Z - debug: end to motorola-XT1039_PT1374

2016-01-06T20:02:58.979Z - debug: Socket disconnected: transport close 9 (LGE-Nexus 5_PT4461)

2016-01-06T20:02:59.114Z - debug: Socket disconnected: transport close 7 (samsung-SM-A300FU_PT4192)

2016-01-06T20:02:59.150Z - debug: Socket disconnected: transport close 0 (samsung-SM-A300FU_PT7648)

2016-01-06T20:02:59.313Z - debug: Socket disconnected: transport close 12 (samsung-SM-N910C_PT3301)

2016-01-06T20:02:59.443Z - debug: Socket disconnected: transport close 15 (samsung-SM-G900F_PT8565)

2016-01-06T20:02:59.533Z - debug: Socket disconnected: transport close 13 (samsung-SM-G900F_PT4782)

2016-01-06T20:02:59.901Z - debug: Socket disconnected: transport close 11 (LGE-LG-D722_PT1155)

2016-01-06T20:03:00.065Z - debug: Socket disconnected: transport close 8 (LGE-LG-H815_PT2321)

2016-01-06T20:03:02.851Z - debug: Socket disconnected: transport close 14 (LGE-LG-D855_PT6783)

2016-01-06T20:04:24.181Z - debug: Socket disconnected: ping timeout 3 (samsung-SM-A500FU_PT7080)


 
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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/552541413820a6d_Story_001_yarong_316_yaronyg/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/552541413820a6d_Story_001_yarong_316_yaronyg/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/552541413820a6d_Story_001_yarong_316_yaronyg/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/552541413820a6d_Story_001_yarong_316_yaronyg/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/552541413820a6d_Story_001_yarong_316_yaronyg/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/552541413820a6d_Story_001_yarong_316_yaronyg/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/552541413820a6d_Story_001_yarong_316_yaronyg/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  0be0c6c6 Test has  SUCCEEDED
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Device test finished on 0be0c6c6 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/552541413820a6d_Story_001_yarong_316_yaronyg/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/552541413820a6d_Story_001_yarong_316_yaronyg/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/552541413820a6d_Story_001_yarong_316_yaronyg/thali04_samsung-SM-G900F.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/552541413820a6d_Story_001_yarong_316_yaronyg/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/552541413820a6d_Story_001_yarong_316_yaronyg/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/552541413820a6d_Story_001_yarong_316_yaronyg/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
STOP log received from  c5afcdcb Test has  SUCCEEDED
Device test finished on c5afcdcb 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:null 
child process exited with code null on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/552541413820a6d_Story_001_yarong_316_yaronyg/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/552541413820a6d_Story_001_yarong_316_yaronyg/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/552541413820a6d_Story_001_yarong_316_yaronyg/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/552541413820a6d_Story_001_yarong_316_yaronyg/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/552541413820a6d_Story_001_yarong_316_yaronyg/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/552541413820a6d_Story_001_yarong_316_yaronyg/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/552541413820a6d_Story_001_yarong_316_yaronyg/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/552541413820a6d_Story_001_yarong_316_yaronyg/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/552541413820a6d_Story_001_yarong_316_yaronyg/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/552541413820a6d_Story_001_yarong_316_yaronyg/iOS_Iphone5s-1.md)



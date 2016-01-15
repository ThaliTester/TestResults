#### Test 56204092c98eeae Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-15T18:48:17.134Z - info: listening on *:3000

2016-01-15T18:48:17.477Z - debug: Device presented: LGE-LG-D722_PT3965 (android) perftest socket:0

2016-01-15T18:48:17.483Z - info: Setting start timeout to: 120000 (android)

2016-01-15T18:48:17.610Z - debug: Device presented: LGE-Nexus 5_PT4558 (android) perftest socket:1

2016-01-15T18:48:17.769Z - debug: Device presented: HTC-HTC One M8s_PT6746 (android) perftest socket:2

2016-01-15T18:48:18.016Z - debug: Device presented: Apple-Iphone5s-1_PT6477 (ios) perftest socket:3

2016-01-15T18:48:18.017Z - info: Setting start timeout to: 120000 (ios)

2016-01-15T18:48:18.099Z - debug: Device presented: samsung-SM-N910C_PT8999 (android) perftest socket:4

2016-01-15T18:48:18.425Z - debug: Device presented: samsung-SM-G900F_PT919 (android) perftest socket:5

2016-01-15T18:48:18.677Z - debug: Device presented: samsung-SM-A500FU_PT3714 (android) perftest socket:6

2016-01-15T18:48:18.755Z - debug: Device presented: LGE-LG-H815_PT4771 (android) perftest socket:7

2016-01-15T18:48:19.144Z - debug: Device presented: motorola-XT1072_PT858 (android) perftest socket:8

2016-01-15T18:48:19.661Z - debug: Device presented: LGE-LG-D855_PT8254 (android) perftest socket:9

2016-01-15T18:48:19.826Z - debug: Device presented: samsung-SM-A300FU_PT2033 (android) perftest socket:10

2016-01-15T18:48:20.774Z - debug: Device presented: Apple-Iphone5-1_PT5004 (ios) perftest socket:11

2016-01-15T18:48:20.953Z - debug: Device presented: samsung-SM-A500FU_PT4798 (android) perftest socket:12

2016-01-15T18:48:21.030Z - debug: Device presented: Apple-Iphone6-1_PT3224 (ios) perftest socket:13

2016-01-15T18:48:21.486Z - debug: Device presented: samsung-SM-A300FU_PT7121 (android) perftest socket:14

2016-01-15T18:48:21.906Z - debug: Device presented: Apple-IpadAir2-1_PT6810 (ios) perftest socket:15

2016-01-15T18:48:21.907Z - info: Required number of devices presented

2016-01-15T18:48:21.912Z - info: Starting perf test run for platform: ios

2016-01-15T18:48:21.913Z - info: Using devices:

2016-01-15T18:48:21.915Z - info: Apple-Iphone5s-1_PT6477

2016-01-15T18:48:21.916Z - info: Apple-Iphone5-1_PT5004

2016-01-15T18:48:21.917Z - info: Apple-Iphone6-1_PT3224

2016-01-15T18:48:21.918Z - info: Apple-IpadAir2-1_PT6810

2016-01-15T18:48:21.922Z - info: Starting test: with 4 devices (ios)

2016-01-15T18:48:22.285Z - debug: Device presented: samsung-SM-G900F_PT3213 (android) perftest socket:16

2016-01-15T18:48:22.810Z - debug: Device presented: motorola-XT1039_PT5310 (android) perftest socket:17

2016-01-15T18:48:23.014Z - info: Received results for {"name:":"Apple-Iphone5-1_PT5004","time":817,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-IpadAir2-1_PT6810.+fMbbA==","peerAvailable":true,"time":816}]} Apple-Iphone5-1_PT5004 ios (4 left)

2016-01-15T18:48:23.509Z - info: Received results for {"name:":"Apple-Iphone6-1_PT3224","time":1096,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone5-1_PT5004.158h0w==","peerAvailable":true,"time":1096}]} Apple-Iphone6-1_PT3224 ios (3 left)

2016-01-15T18:48:23.565Z - debug: Device presented: samsung-SM-G800F_PT4270 (android) perftest socket:18

2016-01-15T18:48:24.236Z - debug: Socket disconnected: transport close 17 (motorola-XT1039_PT5310)

2016-01-15T18:48:25.202Z - info: Received results for {"name:":"Apple-Iphone5s-1_PT6477","time":1034,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone6-1_PT3224.cXLr/Q==","peerAvailable":true,"time":1033}]} Apple-Iphone5s-1_PT6477 ios (2 left)

2016-01-15T18:48:25.298Z - debug: Socket disconnected: transport close 18 (samsung-SM-G800F_PT4270)

2016-01-15T18:48:29.487Z - info: Received results for {"name:":"Apple-IpadAir2-1_PT6810","time":7373,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone5s-1_PT6477.NhmDbg==","peerAvailable":true,"time":7373}]} Apple-IpadAir2-1_PT6810 ios (1 left)

2016-01-15T18:48:29.490Z - info: All test data retrieved for testFindPeers.js (ios)

2016-01-15T18:48:29.497Z - info: Remaining tests: %s ios=[testSendData.js]

2016-01-15T18:48:29.501Z - info: Continuing to next test: testSendData.js
2016-01-15T18:48:29.502Z - info: Starting test: with 4 devices (ios)

2016-01-15T18:49:22.015Z - info: Received results for {"name:":"Apple-Iphone6-1_PT3224","time":52320,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT3224.cXLr/Q==","time":41268,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-IpadAir2-1_PT6810.kDDcMw==","time":4656,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT5004.rhpQQw==","time":3117,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT6477.TN0Czw==","time":3224,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone6-1_PT3224 ios (4 left)

2016-01-15T18:49:22.614Z - info: Received results for {"name:":"Apple-Iphone5-1_PT5004","time":52936,"result":"OK","sendList":[{"name":"Apple-Iphone5-1_PT5004.158h0w==","time":41219,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-Iphone6-1_PT3224.81B+Sg==","time":3796,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT6477.TN0Czw==","time":3552,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_PT6810.kDDcMw==","time":4110,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone5-1_PT5004 ios (3 left)

2016-01-15T18:49:23.646Z - info: Received results for {"name:":"Apple-IpadAir2-1_PT6810","time":53982,"result":"OK","sendList":[{"name":"Apple-IpadAir2-1_PT6810.+fMbbA==","time":41259,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-Iphone6-1_PT3224.81B+Sg==","time":4610,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT5004.rhpQQw==","time":4029,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT6477.TN0Czw==","time":3927,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-IpadAir2-1_PT6810 ios (2 left)

2016-01-15T18:49:23.773Z - info: Received results for {"name:":"Apple-Iphone5s-1_PT6477","time":53389,"result":"OK","sendList":[{"name":"Apple-Iphone5-1_PT5004.158h0w==","time":42167,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-IpadAir2-1_PT6810.kDDcMw==","time":3790,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1_PT3224.81B+Sg==","time":3278,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT5004.rhpQQw==","time":3113,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone5s-1_PT6477 ios (1 left)

2016-01-15T18:49:23.775Z - info: All test data retrieved for testSendData.js (ios)

2016-01-15T18:49:23.782Z - info: Remaining tests: %s ios=[]

2016-01-15T18:49:23.783Z - info: ALL DONE !!!

{ 'name:': 'Apple-Iphone5s-1_PT6477',
  time: 1034,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT3224.cXLr/Q==',
       peerAvailable: true,
       time: 1033 } ] }

{ 'name:': 'Apple-Iphone5-1_PT5004',
  time: 817,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1_PT6810.+fMbbA==',
       peerAvailable: true,
       time: 816 } ] }

{ 'name:': 'Apple-Iphone6-1_PT3224',
  time: 1096,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1_PT5004.158h0w==',
       peerAvailable: true,
       time: 1096 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT6810',
  time: 7373,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5s-1_PT6477.NhmDbg==',
       peerAvailable: true,
       time: 7373 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT6477',
  time: 53389,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1_PT5004.158h0w==',
       time: 42167,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT6810.kDDcMw==',
       time: 3790,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT3224.81B+Sg==',
       time: 3278,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT5004.rhpQQw==',
       time: 3113,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1_PT5004',
  time: 52936,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1_PT5004.158h0w==',
       time: 41219,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT3224.81B+Sg==',
       time: 3796,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT6477.TN0Czw==',
       time: 3552,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT6810.kDDcMw==',
       time: 4110,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1_PT3224',
  time: 52320,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT3224.cXLr/Q==',
       time: 41268,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT6810.kDDcMw==',
       time: 4656,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT5004.rhpQQw==',
       time: 3117,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT6477.TN0Czw==',
       time: 3224,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT6810',
  time: 53982,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT6810.+fMbbA==',
       time: 41259,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT3224.81B+Sg==',
       time: 4610,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT5004.rhpQQw==',
       time: 4029,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT6477.TN0Czw==',
       time: 3927,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

--------------- test report ---------------------
--------------- Apple-Iphone5s-1_PT6477 --------------------- : 1

peersList : 100% : 1033 ms, 99% : 1033 ms, 95 : 1033 ms, 90% : 1033 ms.

Result count 1, range 1033 ms to  1033 ms.

sendList : 100% : 3790 ms, 99% : 3790 ms, 95 : 3790 ms, 90% : 3790 ms.

Average data rate: 0.029 MB/s

Result count 3, range 3113 ms to  3790 ms.

sendList failed peers count : 1 [25 %]

- Peer ID : Apple-Iphone5-1_PT5004.158h0w==, Tried : 5

sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5-1_PT5004 --------------------- : 2

peersList : 100% : 816 ms, 99% : 816 ms, 95 : 816 ms, 90% : 816 ms.
Result count 1, range 816 ms to  816 ms.

sendList : 100% : 4110 ms, 99% : 4110 ms, 95 : 4110 ms, 90% : 4110 ms.

Average data rate: 0.026 MB/s
Result count 3, range 3552 ms to  4110 ms.

sendList failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone5-1_PT5004.158h0w==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1_PT3224 --------------------- : 3
peersList : 100% : 1096 ms, 99% : 1096 ms, 95 : 1096 ms, 90% : 1096 ms.

Result count 1, range 1096 ms to  1096 ms.
sendList : 100% : 4656 ms, 99% : 4656 ms, 95 : 4656 ms, 90% : 4656 ms.
Average data rate: 0.027 MB/s

Result count 3, range 3117 ms to  4656 ms.

sendList failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone6-1_PT3224.cXLr/Q==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Apple-IpadAir2-1_PT6810 --------------------- : 4
peersList : 100% : 7373 ms, 99% : 7373 ms, 95 : 7373 ms, 90% : 7373 ms.
Result count 1, range 7373 ms to  7373 ms.

sendList : 100% : 4610 ms, 99% : 4610 ms, 95 : 4610 ms, 90% : 4610 ms.
Average data rate: 0.024 MB/s
Result count 3, range 3927 ms to  4610 ms.

sendList failed peers count : 1 [25 %]
- Peer ID : Apple-IpadAir2-1_PT6810.+fMbbA==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Combined ---------------------

peersList : 100% : 7373 ms, 99% : 7373 ms, 95 : 7373 ms, 90% : 7373 ms.

sendList : 100% : 4656 ms, 99% : 4656 ms, 95 : 4610 ms, 90% : 4610 ms.
Average data rate: 0.027 MB/s

--------------- end of test report ---------------------

2016-01-15T18:49:23.916Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1_PT3224.cXLr/Q==, peerAvailable=true, time=1033], sendList=[name=Apple-Iphone5-1_PT5004.rhpQQw==, time=3113, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone6-1_PT3224.81B+Sg==, time=3278, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1_PT6810.kDDcMw==, time=3790, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone5-1_PT5004.158h0w==, time=42167, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1_PT6810.+fMbbA==, peerAvailable=true, time=816], sendList=[name=Apple-Iphone5s-1_PT6477.TN0Czw==, time=3552, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone6-1_PT3224.81B+Sg==, time=3796, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1_PT6810.kDDcMw==, time=4110, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone5-1_PT5004.158h0w==, time=41219, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1_PT5004.158h0w==, peerAvailable=true, time=1096], sendList=[name=Apple-Iphone5-1_PT5004.rhpQQw==, time=3117, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5s-1_PT6477.TN0Czw==, time=3224, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1_PT6810.kDDcMw==, time=4656, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone6-1_PT3224.cXLr/Q==, time=41268, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5s-1_PT6477.NhmDbg==, peerAvailable=true, time=7373], sendList=[name=Apple-Iphone5s-1_PT6477.TN0Czw==, time=3927, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1_PT5004.rhpQQw==, time=4029, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone6-1_PT3224.81B+Sg==, time=4610, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-IpadAir2-1_PT6810.+fMbbA==, time=41259, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[]

2016-01-15T18:49:23.925Z - debug: end to Apple-Iphone5s-1_PT6477

2016-01-15T18:49:23.927Z - debug: end to Apple-Iphone5-1_PT5004

2016-01-15T18:49:23.929Z - debug: end to Apple-Iphone6-1_PT3224

2016-01-15T18:49:23.930Z - debug: end to Apple-IpadAir2-1_PT6810

2016-01-15T18:49:24.696Z - debug: state: android waiting

2016-01-15T18:49:24.697Z - debug: state: ios completed

2016-01-15T18:49:26.822Z - debug: Socket disconnected: transport close 13 (Apple-Iphone6-1_PT3224)

2016-01-15T18:49:27.260Z - debug: Socket disconnected: transport close 3 (Apple-Iphone5s-1_PT6477)

2016-01-15T18:49:27.648Z - debug: Socket disconnected: transport close 15 (Apple-IpadAir2-1_PT6810)

2016-01-15T18:49:27.732Z - debug: Socket disconnected: transport close 11 (Apple-Iphone5-1_PT5004)

2016-01-15T18:50:17.491Z - info: Start timeout elapsed for platform: android

2016-01-15T18:50:17.494Z - info: Starting perf test run for platform: android

2016-01-15T18:50:17.495Z - info: Using devices:
2016-01-15T18:50:17.496Z - info: LGE-LG-D722_PT3965

2016-01-15T18:50:17.497Z - info: LGE-Nexus 5_PT4558

2016-01-15T18:50:17.498Z - info: HTC-HTC One M8s_PT6746
2016-01-15T18:50:17.499Z - info: samsung-SM-N910C_PT8999

2016-01-15T18:50:17.500Z - info: samsung-SM-G900F_PT919

2016-01-15T18:50:17.501Z - info: samsung-SM-A500FU_PT3714
2016-01-15T18:50:17.502Z - info: LGE-LG-H815_PT4771

2016-01-15T18:50:17.502Z - info: motorola-XT1072_PT858
2016-01-15T18:50:17.503Z - info: LGE-LG-D855_PT8254

2016-01-15T18:50:17.507Z - info: samsung-SM-A300FU_PT2033

2016-01-15T18:50:17.508Z - info: samsung-SM-A500FU_PT4798

2016-01-15T18:50:17.509Z - info: samsung-SM-A300FU_PT7121

2016-01-15T18:50:17.512Z - info: samsung-SM-G900F_PT3213

2016-01-15T18:50:17.513Z - info: motorola-XT1039_PT5310
2016-01-15T18:50:17.514Z - info: samsung-SM-G800F_PT4270

2016-01-15T18:50:17.515Z - info: Starting test: with 15 devices (android)

2016-01-15T18:50:20.181Z - info: Received results for {"name:":"samsung-SM-A300FU_PT2033","time":2450,"result":"OK","peersList":[{"peerName":"samsung-SM-A500FU_PT4798","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":2447}]} samsung-SM-A300FU_PT2033 android (15 left)

2016-01-15T18:50:20.436Z - info: Received results for {"name:":"samsung-SM-A300FU_PT7121","time":2673,"result":"OK","peersList":[{"peerName":"LGE-LG-D722_PT3965","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":2671}]} samsung-SM-A300FU_PT7121 android (14 left)

2016-01-15T18:50:20.750Z - info: Received results for {"name:":"HTC-HTC One M8s_PT6746","time":3012,"result":"OK","peersList":[{"peerName":"samsung-SM-A500FU_PT3714","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":3010}]} HTC-HTC One M8s_PT6746 android (13 left)

2016-01-15T18:50:21.442Z - info: Received results for {"name:":"samsung-SM-A500FU_PT4798","time":3681,"result":"OK","peersList":[{"peerName":"motorola-XT1072_PT858","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true,"time":3679}]} samsung-SM-A500FU_PT4798 android (12 left)

2016-01-15T18:50:21.647Z - info: Received results for {"name:":"samsung-SM-N910C_PT8999","time":3903,"result":"OK","peersList":[{"peerName":"samsung-SM-A300FU_PT2033","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":3899}]} samsung-SM-N910C_PT8999 android (11 left)

2016-01-15T18:50:21.682Z - info: Received results for {"name:":"LGE-LG-D855_PT8254","time":1665,"result":"OK","peersList":[{"peerName":"samsung-SM-A500FU_PT3714","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":1664}]} LGE-LG-D855_PT8254 android (10 left)

2016-01-15T18:50:21.973Z - info: server timeout for test: testFindPeers.js (ios)

2016-01-15T18:50:21.977Z - info: All test data retrieved for testFindPeers.js (ios)

2016-01-15T18:50:21.980Z - info: Remaining tests: %s ios=[], android=[testFindPeers.js, testSendData.js]

2016-01-15T18:50:21.986Z - info: ALL DONE !!!

{ 'name:': 'Apple-Iphone5s-1_PT6477',
  time: 1034,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT3224.cXLr/Q==',
       peerAvailable: true,
       time: 1033 } ] }

{ 'name:': 'Apple-Iphone5-1_PT5004',
  time: 817,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1_PT6810.+fMbbA==',
       peerAvailable: true,
       time: 816 } ] }

{ 'name:': 'Apple-Iphone6-1_PT3224',
  time: 1096,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1_PT5004.158h0w==',
       peerAvailable: true,
       time: 1096 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT6810',
  time: 7373,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5s-1_PT6477.NhmDbg==',
       peerAvailable: true,
       time: 7373 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT6477',
  time: 53389,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1_PT5004.158h0w==',
       time: 42167,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT6810.kDDcMw==',
       time: 3790,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT3224.81B+Sg==',
       time: 3278,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT5004.rhpQQw==',
       time: 3113,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1_PT5004',
  time: 52936,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1_PT5004.158h0w==',
       time: 41219,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT3224.81B+Sg==',
       time: 3796,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT6477.TN0Czw==',
       time: 3552,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT6810.kDDcMw==',
       time: 4110,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1_PT3224',
  time: 52320,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT3224.cXLr/Q==',
       time: 41268,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT6810.kDDcMw==',
       time: 4656,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT5004.rhpQQw==',
       time: 3117,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT6477.TN0Czw==',
       time: 3224,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT6810',
  time: 53982,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT6810.+fMbbA==',
       time: 41259,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT3224.81B+Sg==',
       time: 4610,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT5004.rhpQQw==',
       time: 4029,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT6477.TN0Czw==',
       time: 3927,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT6477',
  time: 53389,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1_PT5004.158h0w==',
       time: 42167,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT6810.kDDcMw==',
       time: 3790,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT3224.81B+Sg==',
       time: 3278,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT5004.rhpQQw==',
       time: 3113,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1_PT5004',
  time: 52936,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1_PT5004.158h0w==',
       time: 41219,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT3224.81B+Sg==',
       time: 3796,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT6477.TN0Czw==',
       time: 3552,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT6810.kDDcMw==',
       time: 4110,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1_PT3224',
  time: 52320,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT3224.cXLr/Q==',
       time: 41268,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT6810.kDDcMw==',
       time: 4656,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT5004.rhpQQw==',
       time: 3117,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT6477.TN0Czw==',
       time: 3224,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT6810',
  time: 53982,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT6810.+fMbbA==',
       time: 41259,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT3224.81B+Sg==',
       time: 4610,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT5004.rhpQQw==',
       time: 4029,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT6477.TN0Czw==',
       time: 3927,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

--------------- test report ---------------------

--------------- Apple-Iphone5s-1_PT6477 --------------------- : 1

peersList : 100% : 1033 ms, 99% : 1033 ms, 95 : 1033 ms, 90% : 1033 ms.

Result count 1, range 1033 ms to  1033 ms.

sendList : 100% : 3790 ms, 99% : 3790 ms, 95 : 3790 ms, 90% : 3790 ms.
Average data rate: 0.029 MB/s
Result count 6, range 3113 ms to  3790 ms.
sendList failed peers count : 2 [25 %]
- Peer ID : Apple-Iphone5-1_PT5004.158h0w==, Tried : 5
- Peer ID : Apple-Iphone5-1_PT5004.158h0w==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5-1_PT5004 --------------------- : 2

peersList : 100% : 816 ms, 99% : 816 ms, 95 : 816 ms, 90% : 816 ms.

Result count 1, range 816 ms to  816 ms.

sendList : 100% : 4110 ms, 99% : 4110 ms, 95 : 4110 ms, 90% : 4110 ms.
Average data rate: 0.026 MB/s
Result count 6, range 3552 ms to  4110 ms.
sendList failed peers count : 2 [25 %]
- Peer ID : Apple-Iphone5-1_PT5004.158h0w==, Tried : 5
- Peer ID : Apple-Iphone5-1_PT5004.158h0w==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1_PT3224 --------------------- : 3
peersList : 100% : 1096 ms, 99% : 1096 ms, 95 : 1096 ms, 90% : 1096 ms.
Result count 1, range 1096 ms to  1096 ms.
sendList : 100% : 4656 ms, 99% : 4656 ms, 95 : 4656 ms, 90% : 4656 ms.
Average data rate: 0.027 MB/s
Result count 6, range 3117 ms to  4656 ms.
sendList failed peers count : 2 [25 %]
- Peer ID : Apple-Iphone6-1_PT3224.cXLr/Q==, Tried : 5
- Peer ID : Apple-Iphone6-1_PT3224.cXLr/Q==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-IpadAir2-1_PT6810 --------------------- : 4
peersList : 100% : 7373 ms, 99% : 7373 ms, 95 : 7373 ms, 90% : 7373 ms.
Result count 1, range 7373 ms to  7373 ms.
sendList : 100% : 4610 ms, 99% : 4610 ms, 95 : 4610 ms, 90% : 4610 ms.
Average data rate: 0.024 MB/s
Result count 6, range 3927 ms to  4610 ms.
sendList failed peers count : 2 [25 %]
- Peer ID : Apple-IpadAir2-1_PT6810.+fMbbA==, Tried : 5
- Peer ID : Apple-IpadAir2-1_PT6810.+fMbbA==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------
peersList : 100% : 7373 ms, 99% : 7373 ms, 95 : 7373 ms, 90% : 7373 ms.

sendList : 100% : 4656 ms, 99% : 4656 ms, 95 : 4656 ms, 90% : 4610 ms.

Average data rate: 0.027 MB/s

--------------- end of test report ---------------------

2016-01-15T18:50:22.123Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1_PT3224.cXLr/Q==, peerAvailable=true, time=1033], sendList=[name=Apple-Iphone5-1_PT5004.rhpQQw==, time=3113, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1_PT6477"]["sendList"][0], name=Apple-Iphone6-1_PT3224.81B+Sg==, time=3278, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1_PT6477"]["sendList"][2], name=Apple-IpadAir2-1_PT6810.kDDcMw==, time=3790, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1_PT6477"]["sendList"][4]], failedPeer=[name=Apple-Iphone5-1_PT5004.158h0w==, time=42167, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone5s-1_PT6477"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1_PT6810.+fMbbA==, peerAvailable=true, time=816], sendList=[name=Apple-Iphone5s-1_PT6477.TN0Czw==, time=3552, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1_PT5004"]["sendList"][0], name=Apple-Iphone6-1_PT3224.81B+Sg==, time=3796, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1_PT5004"]["sendList"][2], name=Apple-IpadAir2-1_PT6810.kDDcMw==, time=4110, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1_PT5004"]["sendList"][4]], failedPeer=[name=Apple-Iphone5-1_PT5004.158h0w==, time=41219, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone5-1_PT5004"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1_PT5004.158h0w==, peerAvailable=true, time=1096], sendList=[name=Apple-Iphone5-1_PT5004.rhpQQw==, time=3117, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1_PT3224"]["sendList"][0], name=Apple-Iphone5s-1_PT6477.TN0Czw==, time=3224, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1_PT3224"]["sendList"][2], name=Apple-IpadAir2-1_PT6810.kDDcMw==, time=4656, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1_PT3224"]["sendList"][4]], failedPeer=[name=Apple-Iphone6-1_PT3224.cXLr/Q==, time=41268, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone6-1_PT3224"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5s-1_PT6477.NhmDbg==, peerAvailable=true, time=7373], sendList=[name=Apple-Iphone5s-1_PT6477.TN0Czw==, time=3927, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1_PT6810"]["sendList"][0], name=Apple-Iphone5-1_PT5004.rhpQQw==, time=4029, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1_PT6810"]["sendList"][2], name=Apple-Iphone6-1_PT3224.81B+Sg==, time=4610, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1_PT6810"]["sendList"][4]], failedPeer=[name=Apple-IpadAir2-1_PT6810.+fMbbA==, time=41259, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-IpadAir2-1_PT6810"]["sendError"]["failedPeer"][0]], notTriedList=[]

2016-01-15T18:50:22.129Z - debug: end to Apple-Iphone5s-1_PT6477

2016-01-15T18:50:22.133Z - debug: end to Apple-Iphone5-1_PT5004

2016-01-15T18:50:22.134Z - debug: end to Apple-Iphone6-1_PT3224

2016-01-15T18:50:22.136Z - debug: end to Apple-IpadAir2-1_PT6810

2016-01-15T18:50:22.392Z - info: Received results for {"name:":"LGE-LG-D722_PT3965","time":3362,"result":"OK","peersList":[{"peerName":"samsung-SM-A300FU_PT2033","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":3358}]} LGE-LG-D722_PT3965 android (9 left)

2016-01-15T18:50:22.672Z - info: Received results for {"name:":"samsung-SM-A500FU_PT3714","time":4318,"result":"OK","peersList":[{"peerName":"samsung-SM-A300FU_PT2033","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":4317}]} samsung-SM-A500FU_PT3714 android (8 left)

2016-01-15T18:50:22.862Z - info: Received results for {"name:":"motorola-XT1072_PT858","time":4927,"result":"OK","peersList":[{"peerName":"LGE-LG-D722_PT3965","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":4926}]} motorola-XT1072_PT858 android (7 left)

2016-01-15T18:50:23.411Z - info: Received results for {"name:":"LGE-Nexus 5_PT4558","time":5350,"result":"OK","peersList":[{"peerName":"samsung-SM-A500FU_PT4798","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":5346}]} LGE-Nexus 5_PT4558 android (6 left)

2016-01-15T18:50:29.507Z - info: server timeout for test: testSendData.js (ios)

2016-01-15T18:50:29.508Z - info: All test data retrieved for testSendData.js (ios)

2016-01-15T18:50:29.511Z - info: Remaining tests: %s ios=[], android=[testFindPeers.js, testSendData.js]

2016-01-15T18:50:29.512Z - info: ALL DONE !!!

{ 'name:': 'Apple-Iphone5s-1_PT6477',
  time: 1034,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT3224.cXLr/Q==',
       peerAvailable: true,
       time: 1033 } ] }

{ 'name:': 'Apple-Iphone5-1_PT5004',
  time: 817,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1_PT6810.+fMbbA==',
       peerAvailable: true,
       time: 816 } ] }

{ 'name:': 'Apple-Iphone6-1_PT3224',
  time: 1096,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1_PT5004.158h0w==',
       peerAvailable: true,
       time: 1096 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT6810',
  time: 7373,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5s-1_PT6477.NhmDbg==',
       peerAvailable: true,
       time: 7373 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT6477',
  time: 53389,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1_PT5004.158h0w==',
       time: 42167,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT6810.kDDcMw==',
       time: 3790,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT3224.81B+Sg==',
       time: 3278,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT5004.rhpQQw==',
       time: 3113,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1_PT5004',
  time: 52936,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1_PT5004.158h0w==',
       time: 41219,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT3224.81B+Sg==',
       time: 3796,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT6477.TN0Czw==',
       time: 3552,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT6810.kDDcMw==',
       time: 4110,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1_PT3224',
  time: 52320,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT3224.cXLr/Q==',
       time: 41268,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT6810.kDDcMw==',
       time: 4656,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT5004.rhpQQw==',
       time: 3117,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT6477.TN0Czw==',
       time: 3224,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT6810',
  time: 53982,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT6810.+fMbbA==',
       time: 41259,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT3224.81B+Sg==',
       time: 4610,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT5004.rhpQQw==',
       time: 4029,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT6477.TN0Czw==',
       time: 3927,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT6477',
  time: 53389,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1_PT5004.158h0w==',
       time: 42167,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT6810.kDDcMw==',
       time: 3790,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT3224.81B+Sg==',
       time: 3278,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT5004.rhpQQw==',
       time: 3113,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1_PT5004',
  time: 52936,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1_PT5004.158h0w==',
       time: 41219,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT3224.81B+Sg==',
       time: 3796,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT6477.TN0Czw==',
       time: 3552,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT6810.kDDcMw==',
       time: 4110,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1_PT3224',
  time: 52320,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT3224.cXLr/Q==',
       time: 41268,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT6810.kDDcMw==',
       time: 4656,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT5004.rhpQQw==',
       time: 3117,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT6477.TN0Czw==',
       time: 3224,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT6810',
  time: 53982,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT6810.+fMbbA==',
       time: 41259,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT3224.81B+Sg==',
       time: 4610,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT5004.rhpQQw==',
       time: 4029,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT6477.TN0Czw==',
       time: 3927,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT6477',
  time: 53389,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1_PT5004.158h0w==',
       time: 42167,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT6810.kDDcMw==',
       time: 3790,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT3224.81B+Sg==',
       time: 3278,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT5004.rhpQQw==',
       time: 3113,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1_PT5004',
  time: 52936,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1_PT5004.158h0w==',
       time: 41219,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT3224.81B+Sg==',
       time: 3796,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT6477.TN0Czw==',
       time: 3552,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT6810.kDDcMw==',
       time: 4110,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1_PT3224',
  time: 52320,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT3224.cXLr/Q==',
       time: 41268,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT6810.kDDcMw==',
       time: 4656,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT5004.rhpQQw==',
       time: 3117,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT6477.TN0Czw==',
       time: 3224,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT6810',
  time: 53982,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT6810.+fMbbA==',
       time: 41259,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT3224.81B+Sg==',
       time: 4610,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT5004.rhpQQw==',
       time: 4029,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT6477.TN0Czw==',
       time: 3927,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

--------------- test report ---------------------
--------------- Apple-Iphone5s-1_PT6477 --------------------- : 1

peersList : 100% : 1033 ms, 99% : 1033 ms, 95 : 1033 ms, 90% : 1033 ms.

Result count 1, range 1033 ms to  1033 ms.

sendList : 100% : 3790 ms, 99% : 3790 ms, 95 : 3790 ms, 90% : 3790 ms.

Average data rate: 0.029 MB/s

Result count 9, range 3113 ms to  3790 ms.

sendList failed peers count : 3 [25 %]

- Peer ID : Apple-Iphone5-1_PT5004.158h0w==, Tried : 5

- Peer ID : Apple-Iphone5-1_PT5004.158h0w==, Tried : 5
- Peer ID : Apple-Iphone5-1_PT5004.158h0w==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5-1_PT5004 --------------------- : 2

peersList : 100% : 816 ms, 99% : 816 ms, 95 : 816 ms, 90% : 816 ms.

Result count 1, range 816 ms to  816 ms.

sendList : 100% : 4110 ms, 99% : 4110 ms, 95 : 4110 ms, 90% : 4110 ms.

Average data rate: 0.026 MB/s

Result count 9, range 3552 ms to  4110 ms.
sendList failed peers count : 3 [25 %]

- Peer ID : Apple-Iphone5-1_PT5004.158h0w==, Tried : 5
- Peer ID : Apple-Iphone5-1_PT5004.158h0w==, Tried : 5
- Peer ID : Apple-Iphone5-1_PT5004.158h0w==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1_PT3224 --------------------- : 3
peersList : 100% : 1096 ms, 99% : 1096 ms, 95 : 1096 ms, 90% : 1096 ms.
Result count 1, range 1096 ms to  1096 ms.
sendList : 100% : 4656 ms, 99% : 4656 ms, 95 : 4656 ms, 90% : 4656 ms.
Average data rate: 0.027 MB/s
Result count 9, range 3117 ms to  4656 ms.
sendList failed peers count : 3 [25 %]
- Peer ID : Apple-Iphone6-1_PT3224.cXLr/Q==, Tried : 5
- Peer ID : Apple-Iphone6-1_PT3224.cXLr/Q==, Tried : 5
- Peer ID : Apple-Iphone6-1_PT3224.cXLr/Q==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-IpadAir2-1_PT6810 --------------------- : 4
peersList : 100% : 7373 ms, 99% : 7373 ms, 95 : 7373 ms, 90% : 7373 ms.
Result count 1, range 7373 ms to  7373 ms.
sendList : 100% : 4610 ms, 99% : 4610 ms, 95 : 4610 ms, 90% : 4610 ms.
Average data rate: 0.024 MB/s
Result count 9, range 3927 ms to  4610 ms.
sendList failed peers count : 3 [25 %]
- Peer ID : Apple-IpadAir2-1_PT6810.+fMbbA==, Tried : 5
- Peer ID : Apple-IpadAir2-1_PT6810.+fMbbA==, Tried : 5
- Peer ID : Apple-IpadAir2-1_PT6810.+fMbbA==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------
peersList : 100% : 7373 ms, 99% : 7373 ms, 95 : 7373 ms, 90% : 7373 ms.
sendList : 100% : 4656 ms, 99% : 4656 ms, 95 : 4656 ms, 90% : 4610 ms.
Average data rate: 0.027 MB/s
--------------- end of test report ---------------------

2016-01-15T18:50:29.679Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1_PT3224.cXLr/Q==, peerAvailable=true, time=1033], sendList=[name=Apple-Iphone5-1_PT5004.rhpQQw==, time=3113, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1_PT6477"]["sendList"][0], $ref=$["Apple-Iphone5s-1_PT6477"]["sendList"][0], name=Apple-Iphone6-1_PT3224.81B+Sg==, time=3278, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1_PT6477"]["sendList"][3], $ref=$["Apple-Iphone5s-1_PT6477"]["sendList"][3], name=Apple-IpadAir2-1_PT6810.kDDcMw==, time=3790, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1_PT6477"]["sendList"][6], $ref=$["Apple-Iphone5s-1_PT6477"]["sendList"][6]], failedPeer=[name=Apple-Iphone5-1_PT5004.158h0w==, time=42167, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone5s-1_PT6477"]["sendError"]["failedPeer"][0], $ref=$["Apple-Iphone5s-1_PT6477"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1_PT6810.+fMbbA==, peerAvailable=true, time=816], sendList=[name=Apple-Iphone5s-1_PT6477.TN0Czw==, time=3552, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1_PT5004"]["sendList"][0], $ref=$["Apple-Iphone5-1_PT5004"]["sendList"][0], name=Apple-Iphone6-1_PT3224.81B+Sg==, time=3796, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1_PT5004"]["sendList"][3], $ref=$["Apple-Iphone5-1_PT5004"]["sendList"][3], name=Apple-IpadAir2-1_PT6810.kDDcMw==, time=4110, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1_PT5004"]["sendList"][6], $ref=$["Apple-Iphone5-1_PT5004"]["sendList"][6]], failedPeer=[name=Apple-Iphone5-1_PT5004.158h0w==, time=41219, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone5-1_PT5004"]["sendError"]["failedPeer"][0], $ref=$["Apple-Iphone5-1_PT5004"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1_PT5004.158h0w==, peerAvailable=true, time=1096], sendList=[name=Apple-Iphone5-1_PT5004.rhpQQw==, time=3117, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1_PT3224"]["sendList"][0], $ref=$["Apple-Iphone6-1_PT3224"]["sendList"][0], name=Apple-Iphone5s-1_PT6477.TN0Czw==, time=3224, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1_PT3224"]["sendList"][3], $ref=$["Apple-Iphone6-1_PT3224"]["sendList"][3], name=Apple-IpadAir2-1_PT6810.kDDcMw==, time=4656, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1_PT3224"]["sendList"][6], $ref=$["Apple-Iphone6-1_PT3224"]["sendList"][6]], failedPeer=[name=Apple-Iphone6-1_PT3224.cXLr/Q==, time=41268, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone6-1_PT3224"]["sendError"]["failedPeer"][0], $ref=$["Apple-Iphone6-1_PT3224"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5s-1_PT6477.NhmDbg==, peerAvailable=true, time=7373], sendList=[name=Apple-Iphone5s-1_PT6477.TN0Czw==, time=3927, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1_PT6810"]["sendList"][0], $ref=$["Apple-IpadAir2-1_PT6810"]["sendList"][0], name=Apple-Iphone5-1_PT5004.rhpQQw==, time=4029, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1_PT6810"]["sendList"][3], $ref=$["Apple-IpadAir2-1_PT6810"]["sendList"][3], name=Apple-Iphone6-1_PT3224.81B+Sg==, time=4610, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1_PT6810"]["sendList"][6], $ref=$["Apple-IpadAir2-1_PT6810"]["sendList"][6]], failedPeer=[name=Apple-IpadAir2-1_PT6810.+fMbbA==, time=41259, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-IpadAir2-1_PT6810"]["sendError"]["failedPeer"][0], $ref=$["Apple-IpadAir2-1_PT6810"]["sendError"]["failedPeer"][0]], notTriedList=[]

2016-01-15T18:50:29.690Z - debug: end to Apple-Iphone5s-1_PT6477

2016-01-15T18:50:29.692Z - debug: end to Apple-Iphone5-1_PT5004

2016-01-15T18:50:29.693Z - debug: end to Apple-Iphone6-1_PT3224

2016-01-15T18:50:29.694Z - debug: end to Apple-IpadAir2-1_PT6810

2016-01-15T18:50:32.630Z - info: Received results for {"name:":"samsung-SM-G900F_PT919","time":14255,"result":"OK","peersList":[{"peerName":"LGE-LG-D855_PT8254","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":14251}]} samsung-SM-G900F_PT919 android (5 left)

2016-01-15T18:50:34.765Z - info: Received results for {"name:":"samsung-SM-G900F_PT3213","time":14339,"result":"OK","peersList":[{"peerName":"motorola-XT1072_PT858","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true,"time":14329}]} samsung-SM-G900F_PT3213 android (4 left)

2016-01-15T18:51:00.625Z - info: Received results for {"name:":"LGE-LG-H815_PT4771","time":42526,"result":"OK","peersList":[{"peerName":"samsung-SM-G900F_PT919","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":42521}]} LGE-LG-H815_PT4771 android (3 left)

2016-01-15T18:52:17.522Z - info: server timeout for test: testFindPeers.js (android)

2016-01-15T18:52:17.524Z - info: All test data retrieved for testFindPeers.js (android)

2016-01-15T18:52:17.540Z - info: No results from motorola-XT1039_PT5310

2016-01-15T18:52:17.541Z - info: No results from samsung-SM-G800F_PT4270

2016-01-15T18:52:17.542Z - info: Remaining tests: %s ios=[], android=[testSendData.js]

2016-01-15T18:52:17.544Z - info: Continuing to next test: testSendData.js

2016-01-15T18:52:17.545Z - info: Starting test: with 15 devices (android)

2016-01-15T18:53:28.175Z - debug: Socket disconnected: ping timeout 2 (HTC-HTC One M8s_PT6746)

2016-01-15T18:53:57.737Z - info: Received results for {"name:":"LGE-Nexus 5_PT4558","time":100030,"result":"TIMEOUT","sendList":[{"name":"08:EC:A9:50:75:41","time":2936,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"}]} LGE-Nexus 5_PT4558 android (15 left)

2016-01-15T18:53:57.786Z - info: Received results for {"name:":"LGE-LG-H815_PT4771","time":100050,"result":"TIMEOUT","sendList":[{"name":"08:EC:A9:50:76:27","time":2667,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:51:18:22","time":22047,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:34:8A:A0","time":2141,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":5956,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} LGE-LG-H815_PT4771 android (14 left)

2016-01-15T18:53:57.808Z - info: Received results for {"name:":"samsung-SM-N910C_PT8999","time":100055,"result":"TIMEOUT","sendList":[{"name":"08:EC:A9:50:76:27","time":2775,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":3272,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:51:18:22","time":8564,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":1454,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} samsung-SM-N910C_PT8999 android (13 left)

2016-01-15T18:53:57.873Z - info: Received results for {"name:":"samsung-SM-G900F_PT919","time":100094,"result":"TIMEOUT","sendList":[{"name":"7C:F9:0E:51:18:22","time":10470,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":21777,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} samsung-SM-G900F_PT919 android (12 left)

2016-01-15T18:53:57.964Z - info: Received results for {"name:":"samsung-SM-A500FU_PT4798","time":100062,"result":"TIMEOUT","sendList":[{"name":"08:EC:A9:50:76:27","time":16373,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":1478,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:37:96:AB","time":4244,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"}]} samsung-SM-A500FU_PT4798 android (11 left)

2016-01-15T18:53:58.001Z - info: Received results for {"name:":"motorola-XT1072_PT858","time":100076,"result":"TIMEOUT","sendList":[]} motorola-XT1072_PT858 android (10 left)

2016-01-15T18:53:58.151Z - info: Received results for {"name:":"samsung-SM-A300FU_PT2033","time":100049,"result":"TIMEOUT","sendList":[{"name":"34:FC:EF:11:AE:67","time":4072,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":3524,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:76:27","time":9313,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} samsung-SM-A300FU_PT2033 android (9 left)

2016-01-15T18:53:58.206Z - info: Received results for {"name:":"LGE-LG-D722_PT3965","time":100074,"result":"TIMEOUT","sendList":[{"name":"E0:DB:10:14:E2:C0","time":2132,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":2881,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:37:96:AB","time":5281,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} LGE-LG-D722_PT3965 android (8 left)

2016-01-15T18:53:58.307Z - info: Received results for {"name:":"samsung-SM-A500FU_PT3714","time":100048,"result":"TIMEOUT","sendList":[]} samsung-SM-A500FU_PT3714 android (7 left)

2016-01-15T18:53:58.464Z - info: Received results for {"name:":"samsung-SM-A300FU_PT7121","time":100058,"result":"TIMEOUT","sendList":[{"name":"E0:DB:10:14:E2:C0","time":1293,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"44:80:EB:7B:5A:05","time":7507,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:34:8A:A0","time":9568,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":47661,"result":"OK","connections":3,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"}]} samsung-SM-A300FU_PT7121 android (6 left)

2016-01-15T18:53:59.051Z - info: Received results for {"name:":"LGE-LG-D855_PT8254","time":100067,"result":"TIMEOUT","sendList":[{"name":"B0:C5:59:3F:75:69","time":6083,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:34:8A:A0","time":8137,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} LGE-LG-D855_PT8254 android (5 left)

2016-01-15T18:54:00.398Z - info: Received results for {"name:":"samsung-SM-G900F_PT3213","time":100069,"result":"TIMEOUT","sendList":[{"name":"58:3F:54:73:64:C0","time":3989,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:34:8A:A0","time":6778,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":2928,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":8593,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":8226,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:37:96:AB","time":2656,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"34:FC:EF:11:AE:67","time":1774,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} samsung-SM-G900F_PT3213 android (4 left)

2016-01-15T18:54:17.548Z - info: server timeout for test: testSendData.js (android)

2016-01-15T18:54:17.551Z - info: All test data retrieved for testSendData.js (android)

2016-01-15T18:54:17.554Z - info: No results from HTC-HTC One M8s_PT6746

2016-01-15T18:54:17.564Z - info: No results from motorola-XT1039_PT5310

2016-01-15T18:54:17.568Z - info: No results from samsung-SM-G800F_PT4270

2016-01-15T18:54:17.570Z - info: Remaining tests: %s ios=[], android=[]

2016-01-15T18:54:17.571Z - info: ALL DONE !!!

{ 'name:': 'Apple-Iphone5s-1_PT6477',
  time: 1034,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT3224.cXLr/Q==',
       peerAvailable: true,
       time: 1033 } ] }

{ 'name:': 'Apple-Iphone5-1_PT5004',
  time: 817,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1_PT6810.+fMbbA==',
       peerAvailable: true,
       time: 816 } ] }

{ 'name:': 'Apple-Iphone6-1_PT3224',
  time: 1096,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1_PT5004.158h0w==',
       peerAvailable: true,
       time: 1096 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT6810',
  time: 7373,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5s-1_PT6477.NhmDbg==',
       peerAvailable: true,
       time: 7373 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT6477',
  time: 53389,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1_PT5004.158h0w==',
       time: 42167,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT6810.kDDcMw==',
       time: 3790,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT3224.81B+Sg==',
       time: 3278,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT5004.rhpQQw==',
       time: 3113,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1_PT5004',
  time: 52936,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1_PT5004.158h0w==',
       time: 41219,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT3224.81B+Sg==',
       time: 3796,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT6477.TN0Czw==',
       time: 3552,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT6810.kDDcMw==',
       time: 4110,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1_PT3224',
  time: 52320,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT3224.cXLr/Q==',
       time: 41268,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT6810.kDDcMw==',
       time: 4656,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT5004.rhpQQw==',
       time: 3117,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT6477.TN0Czw==',
       time: 3224,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT6810',
  time: 53982,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT6810.+fMbbA==',
       time: 41259,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT3224.81B+Sg==',
       time: 4610,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT5004.rhpQQw==',
       time: 4029,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT6477.TN0Czw==',
       time: 3927,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT6477',
  time: 53389,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1_PT5004.158h0w==',
       time: 42167,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT6810.kDDcMw==',
       time: 3790,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT3224.81B+Sg==',
       time: 3278,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT5004.rhpQQw==',
       time: 3113,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1_PT5004',
  time: 52936,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1_PT5004.158h0w==',
       time: 41219,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT3224.81B+Sg==',
       time: 3796,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT6477.TN0Czw==',
       time: 3552,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT6810.kDDcMw==',
       time: 4110,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1_PT3224',
  time: 52320,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT3224.cXLr/Q==',
       time: 41268,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT6810.kDDcMw==',
       time: 4656,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT5004.rhpQQw==',
       time: 3117,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT6477.TN0Czw==',
       time: 3224,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT6810',
  time: 53982,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT6810.+fMbbA==',
       time: 41259,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT3224.81B+Sg==',
       time: 4610,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT5004.rhpQQw==',
       time: 4029,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT6477.TN0Czw==',
       time: 3927,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT6477',
  time: 53389,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1_PT5004.158h0w==',
       time: 42167,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT6810.kDDcMw==',
       time: 3790,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT3224.81B+Sg==',
       time: 3278,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT5004.rhpQQw==',
       time: 3113,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1_PT5004',
  time: 52936,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone5-1_PT5004.158h0w==',
       time: 41219,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT3224.81B+Sg==',
       time: 3796,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT6477.TN0Czw==',
       time: 3552,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT6810.kDDcMw==',
       time: 4110,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1_PT3224',
  time: 52320,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT3224.cXLr/Q==',
       time: 41268,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT6810.kDDcMw==',
       time: 4656,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT5004.rhpQQw==',
       time: 3117,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT6477.TN0Czw==',
       time: 3224,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT6810',
  time: 53982,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT6810.+fMbbA==',
       time: 41259,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT3224.81B+Sg==',
       time: 4610,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT5004.rhpQQw==',
       time: 4029,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT6477.TN0Czw==',
       time: 3927,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'LGE-LG-D722_PT3965',
  time: 3362,
  result: 'OK',
  peersList: 
   [ { peerName: 'samsung-SM-A300FU_PT2033',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 3358 } ] }

{ 'name:': 'LGE-Nexus 5_PT4558',
  time: 5350,
  result: 'OK',
  peersList: 
   [ { peerName: 'samsung-SM-A500FU_PT4798',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 5346 } ] }

{ 'name:': 'HTC-HTC One M8s_PT6746',
  time: 3012,
  result: 'OK',
  peersList: 
   [ { peerName: 'samsung-SM-A500FU_PT3714',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 3010 } ] }

{ 'name:': 'samsung-SM-N910C_PT8999',
  time: 3903,
  result: 'OK',
  peersList: 
   [ { peerName: 'samsung-SM-A300FU_PT2033',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 3899 } ] }

{ 'name:': 'samsung-SM-G900F_PT919',
  time: 14255,
  result: 'OK',
  peersList: 
   [ { peerName: 'LGE-LG-D855_PT8254',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 14251 } ] }

{ 'name:': 'samsung-SM-A500FU_PT3714',
  time: 4318,
  result: 'OK',
  peersList: 
   [ { peerName: 'samsung-SM-A300FU_PT2033',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 4317 } ] }

{ 'name:': 'LGE-LG-H815_PT4771',
  time: 42526,
  result: 'OK',
  peersList: 
   [ { peerName: 'samsung-SM-G900F_PT919',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 42521 } ] }

{ 'name:': 'motorola-XT1072_PT858',
  time: 4927,
  result: 'OK',
  peersList: 
   [ { peerName: 'LGE-LG-D722_PT3965',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 4926 } ] }

{ 'name:': 'LGE-LG-D855_PT8254',
  time: 1665,
  result: 'OK',
  peersList: 
   [ { peerName: 'samsung-SM-A500FU_PT3714',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 1664 } ] }

{ 'name:': 'samsung-SM-A300FU_PT2033',
  time: 2450,
  result: 'OK',
  peersList: 
   [ { peerName: 'samsung-SM-A500FU_PT4798',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 2447 } ] }

{ 'name:': 'samsung-SM-A500FU_PT4798',
  time: 3681,
  result: 'OK',
  peersList: 
   [ { peerName: 'motorola-XT1072_PT858',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 3679 } ] }

{ 'name:': 'samsung-SM-A300FU_PT7121',
  time: 2673,
  result: 'OK',
  peersList: 
   [ { peerName: 'LGE-LG-D722_PT3965',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 2671 } ] }

{ 'name:': 'samsung-SM-G900F_PT3213',
  time: 14339,
  result: 'OK',
  peersList: 
   [ { peerName: 'motorola-XT1072_PT858',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 14329 } ] }

{ 'name:': 'LGE-LG-D722_PT3965',
  time: 100074,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'E0:DB:10:14:E2:C0',
       time: 2132,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'B0:C5:59:3F:75:69',
       time: 2881,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:37:96:AB',
       time: 5281,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'LGE-Nexus 5_PT4558',
  time: 100030,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '08:EC:A9:50:75:41',
       time: 2936,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'B0:C5:59:3F:75:69', time: 0, result: 'Fail' } ] }

{ 'name:': 'samsung-SM-N910C_PT8999',
  time: 100055,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '08:EC:A9:50:76:27',
       time: 2775,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:85:54',
       time: 3272,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:51:18:22',
       time: 8564,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'B0:C5:59:3F:75:69',
       time: 1454,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'samsung-SM-G900F_PT919',
  time: 100094,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '7C:F9:0E:51:18:22',
       time: 10470,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:3C:51',
       time: 21777,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'samsung-SM-A500FU_PT3714',
  time: 100048,
  result: 'TIMEOUT',
  sendList: [] }

{ 'name:': 'LGE-LG-H815_PT4771',
  time: 100050,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '08:EC:A9:50:76:27',
       time: 2667,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:51:18:22',
       time: 22047,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:34:8A:A0',
       time: 2141,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'B0:C5:59:3F:75:69',
       time: 5956,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'motorola-XT1072_PT858',
  time: 100076,
  result: 'TIMEOUT',
  sendList: [] }

{ 'name:': 'LGE-LG-D855_PT8254',
  time: 100067,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'B0:C5:59:3F:75:69',
       time: 6083,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:34:8A:A0',
       time: 8137,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'samsung-SM-A300FU_PT2033',
  time: 100049,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '34:FC:EF:11:AE:67',
       time: 4072,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:85:54',
       time: 3524,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '08:EC:A9:50:76:27',
       time: 9313,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }
{ 'name:': 'samsung-SM-A500FU_PT4798',
  time: 100062,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '08:EC:A9:50:76:27',
       time: 16373,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:3C:51',
       time: 1478,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:37:96:AB',
       time: 4244,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'B0:C5:59:3F:75:69', time: 0, result: 'Fail' } ] }
{ 'name:': 'samsung-SM-A300FU_PT7121',
  time: 100058,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'E0:DB:10:14:E2:C0',
       time: 1293,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '44:80:EB:7B:5A:05',
       time: 7507,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:34:8A:A0',
       time: 9568,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:3C:51',
       time: 47661,
       result: 'OK',
       connections: 3,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:85:54', time: 0, result: 'Fail' } ] }

{ 'name:': 'samsung-SM-G900F_PT3213',
  time: 100069,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '58:3F:54:73:64:C0',
       time: 3989,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:34:8A:A0',
       time: 6778,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'E0:DB:10:14:E2:C0',
       time: 2928,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:85:54',
       time: 8593,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:3C:51',
       time: 8226,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:37:96:AB',
       time: 2656,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '34:FC:EF:11:AE:67',
       time: 1774,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

--------------- test report ---------------------
--------------- Apple-Iphone5s-1_PT6477 --------------------- : 1
peersList : 100% : 1033 ms, 99% : 1033 ms, 95 : 1033 ms, 90% : 1033 ms.
Result count 1, range 1033 ms to  1033 ms.
sendList : 100% : 3790 ms, 99% : 3790 ms, 95 : 3790 ms, 90% : 3790 ms.

Average data rate: 0.029 MB/s
Result count 9, range 3113 ms to  3790 ms.
sendList failed peers count : 3 [25 %]
- Peer ID : Apple-Iphone5-1_PT5004.158h0w==, Tried : 5
- Peer ID : Apple-Iphone5-1_PT5004.158h0w==, Tried : 5
- Peer ID : Apple-Iphone5-1_PT5004.158h0w==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5-1_PT5004 --------------------- : 2

peersList : 100% : 816 ms, 99% : 816 ms, 95 : 816 ms, 90% : 816 ms.
Result count 1, range 816 ms to  816 ms.
sendList : 100% : 4110 ms, 99% : 4110 ms, 95 : 4110 ms, 90% : 4110 ms.
Average data rate: 0.026 MB/s
Result count 9, range 3552 ms to  4110 ms.
sendList failed peers count : 3 [25 %]

- Peer ID : Apple-Iphone5-1_PT5004.158h0w==, Tried : 5
- Peer ID : Apple-Iphone5-1_PT5004.158h0w==, Tried : 5
- Peer ID : Apple-Iphone5-1_PT5004.158h0w==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1_PT3224 --------------------- : 3
peersList : 100% : 1096 ms, 99% : 1096 ms, 95 : 1096 ms, 90% : 1096 ms.
Result count 1, range 1096 ms to  1096 ms.

sendList : 100% : 4656 ms, 99% : 4656 ms, 95 : 4656 ms, 90% : 4656 ms.
Average data rate: 0.027 MB/s
Result count 9, range 3117 ms to  4656 ms.
sendList failed peers count : 3 [25 %]
- Peer ID : Apple-Iphone6-1_PT3224.cXLr/Q==, Tried : 5
- Peer ID : Apple-Iphone6-1_PT3224.cXLr/Q==, Tried : 5
- Peer ID : Apple-Iphone6-1_PT3224.cXLr/Q==, Tried : 5

sendList never tried peers count : 0 [0 %]
--------------- Apple-IpadAir2-1_PT6810 --------------------- : 4
peersList : 100% : 7373 ms, 99% : 7373 ms, 95 : 7373 ms, 90% : 7373 ms.
Result count 1, range 7373 ms to  7373 ms.
sendList : 100% : 4610 ms, 99% : 4610 ms, 95 : 4610 ms, 90% : 4610 ms.
Average data rate: 0.024 MB/s
Result count 9, range 3927 ms to  4610 ms.
sendList failed peers count : 3 [25 %]

- Peer ID : Apple-IpadAir2-1_PT6810.+fMbbA==, Tried : 5
- Peer ID : Apple-IpadAir2-1_PT6810.+fMbbA==, Tried : 5
- Peer ID : Apple-IpadAir2-1_PT6810.+fMbbA==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- LGE-LG-D722_PT3965 --------------------- : 5
peersList : 100% : 3358 ms, 99% : 3358 ms, 95 : 3358 ms, 90% : 3358 ms.

Result count 1, range 3358 ms to  3358 ms.
sendList : 100% : 5281 ms, 99% : 5281 ms, 95 : 5281 ms, 90% : 5281 ms.
Average data rate: 0.029 MB/s
Result count 3, range 2132 ms to  5281 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- LGE-Nexus 5_PT4558 --------------------- : 6

peersList : 100% : 5346 ms, 99% : 5346 ms, 95 : 5346 ms, 90% : 5346 ms.
Result count 1, range 5346 ms to  5346 ms.
sendList : 100% : 2936 ms, 99% : 2936 ms, 95 : 2936 ms, 90% : 2936 ms.
Average data rate: 0.034 MB/s
Result count 1, range 2936 ms to  2936 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 1 [50 %]

- Peer ID : B0:C5:59:3F:75:69
--------------- HTC-HTC One M8s_PT6746 --------------------- : 7
peersList : 100% : 3010 ms, 99% : 3010 ms, 95 : 3010 ms, 90% : 3010 ms.

Result count 1, range 3010 ms to  3010 ms.
--------------- samsung-SM-N910C_PT8999 --------------------- : 8
peersList : 100% : 3899 ms, 99% : 3899 ms, 95 : 3899 ms, 90% : 3899 ms.
Result count 1, range 3899 ms to  3899 ms.
sendList : 100% : 8564 ms, 99% : 8564 ms, 95 : 8564 ms, 90% : 8564 ms.
Average data rate: 0.025 MB/s

Result count 4, range 1454 ms to  8564 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-G900F_PT919 --------------------- : 9
peersList : 100% : 14251 ms, 99% : 14251 ms, 95 : 14251 ms, 90% : 14251 ms.
Result count 1, range 14251 ms to  14251 ms.

sendList : 100% : 21777 ms, 99% : 21777 ms, 95 : 21777 ms, 90% : 21777 ms.
Average data rate: 0.006 MB/s
Result count 2, range 10470 ms to  21777 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-A500FU_PT3714 --------------------- : 10
peersList : 100% : 4317 ms, 99% : 4317 ms, 95 : 4317 ms, 90% : 4317 ms.

Result count 1, range 4317 ms to  4317 ms.
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
--------------- LGE-LG-H815_PT4771 --------------------- : 11
peersList : 100% : 42521 ms, 99% : 42521 ms, 95 : 42521 ms, 90% : 42521 ms.

Result count 1, range 42521 ms to  42521 ms.
sendList : 100% : 22047 ms, 99% : 22047 ms, 95 : 22047 ms, 90% : 22047 ms.
Average data rate: 0.012 MB/s
Result count 4, range 2141 ms to  22047 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- motorola-XT1072_PT858 --------------------- : 12
peersList : 100% : 4926 ms, 99% : 4926 ms, 95 : 4926 ms, 90% : 4926 ms.
Result count 1, range 4926 ms to  4926 ms.
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items

--------------- LGE-LG-D855_PT8254 --------------------- : 13
peersList : 100% : 1664 ms, 99% : 1664 ms, 95 : 1664 ms, 90% : 1664 ms.
Result count 1, range 1664 ms to  1664 ms.
sendList : 100% : 8137 ms, 99% : 8137 ms, 95 : 8137 ms, 90% : 8137 ms.
Average data rate: 0.014 MB/s
Result count 2, range 6083 ms to  8137 ms.

sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-A300FU_PT2033 --------------------- : 14
peersList : 100% : 2447 ms, 99% : 2447 ms, 95 : 2447 ms, 90% : 2447 ms.
Result count 1, range 2447 ms to  2447 ms.
sendList : 100% : 9313 ms, 99% : 9313 ms, 95 : 9313 ms, 90% : 9313 ms.
Average data rate: 0.018 MB/s

Result count 3, range 3524 ms to  9313 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-A500FU_PT4798 --------------------- : 15
peersList : 100% : 3679 ms, 99% : 3679 ms, 95 : 3679 ms, 90% : 3679 ms.
Result count 1, range 3679 ms to  3679 ms.

sendList : 100% : 16373 ms, 99% : 16373 ms, 95 : 16373 ms, 90% : 16373 ms.
Average data rate: 0.014 MB/s
Result count 3, range 1478 ms to  16373 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 1 [25 %]
- Peer ID : B0:C5:59:3F:75:69

--------------- samsung-SM-A300FU_PT7121 --------------------- : 16
peersList : 100% : 2671 ms, 99% : 2671 ms, 95 : 2671 ms, 90% : 2671 ms.
Result count 1, range 2671 ms to  2671 ms.
sendList : 100% : 47661 ms, 99% : 47661 ms, 95 : 47661 ms, 90% : 47661 ms.
Average data rate: 0.006 MB/s
Result count 4, range 1293 ms to  47661 ms.

sendList failed peers count : 0 [0 %]
sendList never tried peers count : 1 [20 %]
- Peer ID : F8:95:C7:87:85:54
--------------- samsung-SM-G900F_PT3213 --------------------- : 17
peersList : 100% : 14329 ms, 99% : 14329 ms, 95 : 14329 ms, 90% : 14329 ms.
Result count 1, range 14329 ms to  14329 ms.

sendList : 100% : 8593 ms, 99% : 8593 ms, 95 : 8593 ms, 90% : 8226 ms.
Average data rate: 0.02 MB/s
Result count 7, range 1774 ms to  8593 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------

peersList : 100% : 42521 ms, 99% : 42521 ms, 95 : 14329 ms, 90% : 14251 ms.
sendList : 100% : 47661 ms, 99% : 22047 ms, 95 : 16373 ms, 90% : 8593 ms.
Average data rate: 0.018 MB/s

--------------- end of test report ---------------------

2016-01-15T18:54:17.872Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1_PT3224.cXLr/Q==, peerAvailable=true, time=1033], sendList=[name=Apple-Iphone5-1_PT5004.rhpQQw==, time=3113, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1_PT6477"]["sendList"][0], $ref=$["Apple-Iphone5s-1_PT6477"]["sendList"][0], name=Apple-Iphone6-1_PT3224.81B+Sg==, time=3278, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1_PT6477"]["sendList"][3], $ref=$["Apple-Iphone5s-1_PT6477"]["sendList"][3], name=Apple-IpadAir2-1_PT6810.kDDcMw==, time=3790, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1_PT6477"]["sendList"][6], $ref=$["Apple-Iphone5s-1_PT6477"]["sendList"][6]], failedPeer=[name=Apple-Iphone5-1_PT5004.158h0w==, time=42167, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone5s-1_PT6477"]["sendError"]["failedPeer"][0], $ref=$["Apple-Iphone5s-1_PT6477"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1_PT6810.+fMbbA==, peerAvailable=true, time=816], sendList=[name=Apple-Iphone5s-1_PT6477.TN0Czw==, time=3552, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1_PT5004"]["sendList"][0], $ref=$["Apple-Iphone5-1_PT5004"]["sendList"][0], name=Apple-Iphone6-1_PT3224.81B+Sg==, time=3796, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1_PT5004"]["sendList"][3], $ref=$["Apple-Iphone5-1_PT5004"]["sendList"][3], name=Apple-IpadAir2-1_PT6810.kDDcMw==, time=4110, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1_PT5004"]["sendList"][6], $ref=$["Apple-Iphone5-1_PT5004"]["sendList"][6]], failedPeer=[name=Apple-Iphone5-1_PT5004.158h0w==, time=41219, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone5-1_PT5004"]["sendError"]["failedPeer"][0], $ref=$["Apple-Iphone5-1_PT5004"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1_PT5004.158h0w==, peerAvailable=true, time=1096], sendList=[name=Apple-Iphone5-1_PT5004.rhpQQw==, time=3117, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1_PT3224"]["sendList"][0], $ref=$["Apple-Iphone6-1_PT3224"]["sendList"][0], name=Apple-Iphone5s-1_PT6477.TN0Czw==, time=3224, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1_PT3224"]["sendList"][3], $ref=$["Apple-Iphone6-1_PT3224"]["sendList"][3], name=Apple-IpadAir2-1_PT6810.kDDcMw==, time=4656, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1_PT3224"]["sendList"][6], $ref=$["Apple-Iphone6-1_PT3224"]["sendList"][6]], failedPeer=[name=Apple-Iphone6-1_PT3224.cXLr/Q==, time=41268, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone6-1_PT3224"]["sendError"]["failedPeer"][0], $ref=$["Apple-Iphone6-1_PT3224"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5s-1_PT6477.NhmDbg==, peerAvailable=true, time=7373], sendList=[name=Apple-Iphone5s-1_PT6477.TN0Czw==, time=3927, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1_PT6810"]["sendList"][0], $ref=$["Apple-IpadAir2-1_PT6810"]["sendList"][0], name=Apple-Iphone5-1_PT5004.rhpQQw==, time=4029, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1_PT6810"]["sendList"][3], $ref=$["Apple-IpadAir2-1_PT6810"]["sendList"][3], name=Apple-Iphone6-1_PT3224.81B+Sg==, time=4610, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1_PT6810"]["sendList"][6], $ref=$["Apple-IpadAir2-1_PT6810"]["sendList"][6]], failedPeer=[name=Apple-IpadAir2-1_PT6810.+fMbbA==, time=41259, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-IpadAir2-1_PT6810"]["sendError"]["failedPeer"][0], $ref=$["Apple-IpadAir2-1_PT6810"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=samsung-SM-A300FU_PT2033, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=3358], sendList=[name=E0:DB:10:14:E2:C0, time=2132, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=B0:C5:59:3F:75:69, time=2881, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:37:96:AB, time=5281, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], peersList=[peerName=samsung-SM-A500FU_PT4798, peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=5346], sendList=[name=08:EC:A9:50:75:41, time=2936, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[name=B0:C5:59:3F:75:69, time=0, result=Fail], peersList=[peerName=samsung-SM-A500FU_PT3714, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=3010], peersList=[peerName=samsung-SM-A300FU_PT2033, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=3899], sendList=[name=B0:C5:59:3F:75:69, time=1454, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=08:EC:A9:50:76:27, time=2775, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=F8:95:C7:87:85:54, time=3272, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:51:18:22, time=8564, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], peersList=[peerName=LGE-LG-D855_PT8254, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=14251], sendList=[name=7C:F9:0E:51:18:22, time=10470, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=F8:95:C7:87:3C:51, time=21777, result=OK, connections=2, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], peersList=[peerName=samsung-SM-A300FU_PT2033, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=4317], sendList=[], failedPeer=[], notTriedList=[], peersList=[peerName=samsung-SM-G900F_PT919, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=42521], sendList=[name=7C:F9:0E:34:8A:A0, time=2141, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=08:EC:A9:50:76:27, time=2667, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=B0:C5:59:3F:75:69, time=5956, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:51:18:22, time=22047, result=OK, connections=2, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], peersList=[peerName=LGE-LG-D722_PT3965, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=4926], sendList=[], failedPeer=[], notTriedList=[], peersList=[peerName=samsung-SM-A500FU_PT3714, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=1664], sendList=[name=B0:C5:59:3F:75:69, time=6083, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:34:8A:A0, time=8137, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], peersList=[peerName=samsung-SM-A500FU_PT4798, peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=2447], sendList=[name=F8:95:C7:87:85:54, time=3524, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=34:FC:EF:11:AE:67, time=4072, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=08:EC:A9:50:76:27, time=9313, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], peersList=[peerName=motorola-XT1072_PT858, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=3679], sendList=[name=F8:95:C7:87:3C:51, time=1478, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:37:96:AB, time=4244, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=08:EC:A9:50:76:27, time=16373, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[name=B0:C5:59:3F:75:69, time=0, result=Fail], peersList=[peerName=LGE-LG-D722_PT3965, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=2671], sendList=[name=E0:DB:10:14:E2:C0, time=1293, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=44:80:EB:7B:5A:05, time=7507, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:34:8A:A0, time=9568, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=F8:95:C7:87:3C:51, time=47661, result=OK, connections=3, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[name=F8:95:C7:87:85:54, time=0, result=Fail], peersList=[peerName=motorola-XT1072_PT858, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=14329], sendList=[name=34:FC:EF:11:AE:67, time=1774, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:37:96:AB, time=2656, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=E0:DB:10:14:E2:C0, time=2928, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=58:3F:54:73:64:C0, time=3989, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:34:8A:A0, time=6778, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=F8:95:C7:87:3C:51, time=8226, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=F8:95:C7:87:85:54, time=8593, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[]

2016-01-15T18:54:17.892Z - debug: end to LGE-LG-D722_PT3965
2016-01-15T18:54:17.894Z - debug: end to LGE-Nexus 5_PT4558
2016-01-15T18:54:17.895Z - debug: end to HTC-HTC One M8s_PT6746

2016-01-15T18:54:17.896Z - debug: end to samsung-SM-N910C_PT8999

2016-01-15T18:54:17.898Z - debug: end to samsung-SM-G900F_PT919
2016-01-15T18:54:17.899Z - debug: end to samsung-SM-A500FU_PT3714

2016-01-15T18:54:17.900Z - debug: end to LGE-LG-H815_PT4771

2016-01-15T18:54:17.901Z - debug: end to motorola-XT1072_PT858

2016-01-15T18:54:17.902Z - debug: end to LGE-LG-D855_PT8254

2016-01-15T18:54:17.903Z - debug: end to samsung-SM-A300FU_PT2033

2016-01-15T18:54:17.907Z - debug: end to samsung-SM-A500FU_PT4798

2016-01-15T18:54:17.908Z - debug: end to samsung-SM-A300FU_PT7121

2016-01-15T18:54:17.909Z - debug: end to samsung-SM-G900F_PT3213

2016-01-15T18:54:17.910Z - debug: end to motorola-XT1039_PT5310
2016-01-15T18:54:17.911Z - debug: end to samsung-SM-G800F_PT4270

2016-01-15T18:54:18.395Z - debug: Socket disconnected: transport close 1 (LGE-Nexus 5_PT4558)

2016-01-15T18:54:18.582Z - debug: Socket disconnected: transport close 10 (samsung-SM-A300FU_PT2033)

2016-01-15T18:54:18.593Z - debug: Socket disconnected: transport close 6 (samsung-SM-A500FU_PT3714)

2016-01-15T18:54:18.659Z - debug: Socket disconnected: transport close 14 (samsung-SM-A300FU_PT7121)

2016-01-15T18:54:18.823Z - debug: Socket disconnected: transport close 4 (samsung-SM-N910C_PT8999)

2016-01-15T18:54:19.036Z - debug: Socket disconnected: transport close 16 (samsung-SM-G900F_PT3213)

2016-01-15T18:54:19.117Z - debug: Socket disconnected: transport close 9 (LGE-LG-D855_PT8254)

2016-01-15T18:54:19.178Z - debug: Socket disconnected: transport close 5 (samsung-SM-G900F_PT919)

2016-01-15T18:54:19.184Z - debug: Socket disconnected: transport close 12 (samsung-SM-A500FU_PT4798)

2016-01-15T18:54:19.373Z - debug: Socket disconnected: transport close 7 (LGE-LG-H815_PT4771)

2016-01-15T18:54:19.902Z - debug: Socket disconnected: transport close 8 (motorola-XT1072_PT858)

2016-01-15T18:54:22.347Z - debug: Socket disconnected: transport close 0 (LGE-LG-D722_PT3965)


 
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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/56204092c98eeae_Changes_that__tobybrad_and_I_agreed_to_yaronyg/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/56204092c98eeae_Changes_that__tobybrad_and_I_agreed_to_yaronyg/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/56204092c98eeae_Changes_that__tobybrad_and_I_agreed_to_yaronyg/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/56204092c98eeae_Changes_that__tobybrad_and_I_agreed_to_yaronyg/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/56204092c98eeae_Changes_that__tobybrad_and_I_agreed_to_yaronyg/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/56204092c98eeae_Changes_that__tobybrad_and_I_agreed_to_yaronyg/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/56204092c98eeae_Changes_that__tobybrad_and_I_agreed_to_yaronyg/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/56204092c98eeae_Changes_that__tobybrad_and_I_agreed_to_yaronyg/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/56204092c98eeae_Changes_that__tobybrad_and_I_agreed_to_yaronyg/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/56204092c98eeae_Changes_that__tobybrad_and_I_agreed_to_yaronyg/thali04_samsung-SM-G900F.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/56204092c98eeae_Changes_that__tobybrad_and_I_agreed_to_yaronyg/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/56204092c98eeae_Changes_that__tobybrad_and_I_agreed_to_yaronyg/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/56204092c98eeae_Changes_that__tobybrad_and_I_agreed_to_yaronyg/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
STOP log received from  c5afcdcb Test has  SUCCEEDED
STOP log received from  4db5c8cc Test has  SUCCEEDED
Device test finished on 4db5c8cc 
Device test finished on c5afcdcb 
Android task is completed. [SUCCESS]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/56204092c98eeae_Changes_that__tobybrad_and_I_agreed_to_yaronyg/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/56204092c98eeae_Changes_that__tobybrad_and_I_agreed_to_yaronyg/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/56204092c98eeae_Changes_that__tobybrad_and_I_agreed_to_yaronyg/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/56204092c98eeae_Changes_that__tobybrad_and_I_agreed_to_yaronyg/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/56204092c98eeae_Changes_that__tobybrad_and_I_agreed_to_yaronyg/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/56204092c98eeae_Changes_that__tobybrad_and_I_agreed_to_yaronyg/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/56204092c98eeae_Changes_that__tobybrad_and_I_agreed_to_yaronyg/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/56204092c98eeae_Changes_that__tobybrad_and_I_agreed_to_yaronyg/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/56204092c98eeae_Changes_that__tobybrad_and_I_agreed_to_yaronyg/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/56204092c98eeae_Changes_that__tobybrad_and_I_agreed_to_yaronyg/iOS_Iphone5s-1.md)



#### Test 54968200254eab2 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-05T00:43:21.953Z - info: listening on *:3000

2016-01-05T00:43:22.778Z - debug: Device presented: Apple-Iphone5-1_PT4002 (ios) perftest socket:0

2016-01-05T00:43:22.785Z - info: Setting start timeout to: 120000 (ios)

2016-01-05T00:43:23.382Z - debug: Device presented: Apple-Iphone5s-1_PT7515 (ios) perftest socket:1

2016-01-05T00:43:23.400Z - debug: Device presented: motorola-XT1072_PT4505 (android) perftest socket:2

2016-01-05T00:43:23.402Z - info: Setting start timeout to: 120000 (android)

2016-01-05T00:43:23.552Z - debug: Device presented: Apple-Iphone6-1_PT4820 (ios) perftest socket:3

2016-01-05T00:43:23.596Z - debug: Device presented: samsung-SM-G900F_PT6440 (android) perftest socket:4

2016-01-05T00:43:23.675Z - debug: Device presented: samsung-SM-A500FU_PT3690 (android) perftest socket:5

2016-01-05T00:43:24.320Z - debug: Device presented: LGE-LG-D722_PT1779 (android) perftest socket:6

2016-01-05T00:43:24.562Z - debug: Device presented: samsung-SM-A300FU_PT818 (android) perftest socket:7

2016-01-05T00:43:24.771Z - debug: Device presented: LGE-LG-D855_PT2787 (android) perftest socket:9

2016-01-05T00:43:24.783Z - debug: Device presented: HTC-HTC One M8s_PT8357 (android) perftest socket:8

2016-01-05T00:43:24.823Z - debug: Device presented: samsung-SM-N910C_PT706 (android) perftest socket:10

2016-01-05T00:43:25.231Z - debug: Device presented: samsung-SM-A500FU_PT9197 (android) perftest socket:11

2016-01-05T00:43:25.323Z - debug: Device presented: samsung-SM-A300FU_PT6753 (android) perftest socket:12

2016-01-05T00:43:25.409Z - debug: Device presented: LGE-LG-H815_PT177 (android) perftest socket:13

2016-01-05T00:43:26.087Z - debug: Device presented: samsung-SM-G900F_PT6172 (android) perftest socket:14

2016-01-05T00:43:27.010Z - debug: Device presented: LGE-Nexus 5_PT9383 (android) perftest socket:16

2016-01-05T00:43:27.074Z - debug: Device presented: Apple-IpadAir2-1_PT3239 (ios) perftest socket:15

2016-01-05T00:43:27.075Z - info: Required number of devices presented

2016-01-05T00:43:27.079Z - info: Starting perf test run for platform: ios

2016-01-05T00:43:27.080Z - info: Using devices:

2016-01-05T00:43:27.081Z - info: Apple-Iphone5-1_PT4002

2016-01-05T00:43:27.084Z - info: Apple-Iphone5s-1_PT7515

2016-01-05T00:43:27.085Z - info: Apple-Iphone6-1_PT4820
2016-01-05T00:43:27.086Z - info: Apple-IpadAir2-1_PT3239

2016-01-05T00:43:27.089Z - info: Starting test: with 4 devices (ios)

2016-01-05T00:43:28.327Z - debug: Device presented: samsung-SM-G800F_PT2118 (android) perftest socket:17

2016-01-05T00:43:28.492Z - info: Received results for {"name:":"Apple-IpadAir2-1_PT3239","time":1277,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone6-1_PT4820.GNbylA==","peerAvailable":true,"time":1276}]} Apple-IpadAir2-1_PT3239 ios (4 left)

2016-01-05T00:43:28.761Z - info: Received results for {"name:":"Apple-Iphone5-1_PT4002","time":1063,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone6-1_PT4820.GNbylA==","peerAvailable":true,"time":1061}]} Apple-Iphone5-1_PT4002 ios (3 left)

2016-01-05T00:43:28.815Z - info: Received results for {"name:":"Apple-Iphone6-1_PT4820","time":1126,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone5-1_PT4002.tre7Iw==","peerAvailable":true,"time":1124}]} Apple-Iphone6-1_PT4820 ios (2 left)

2016-01-05T00:43:29.454Z - debug: Socket disconnected: transport close 17 (samsung-SM-G800F_PT2118)

2016-01-05T00:43:30.146Z - info: Received results for {"name:":"Apple-Iphone5s-1_PT7515","time":352,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone6-1_PT4820.GNbylA==","peerAvailable":true,"time":349}]} Apple-Iphone5s-1_PT7515 ios (1 left)

2016-01-05T00:43:30.149Z - info: All test data retrieved for testFindPeers.js (ios)

2016-01-05T00:43:30.157Z - info: Remaining tests: %s ios=[testSendData.js]

2016-01-05T00:43:30.161Z - info: Continuing to next test: testSendData.js
2016-01-05T00:43:30.162Z - info: Starting test: with 4 devices (ios)

2016-01-05T00:44:24.864Z - info: Received results for {"name:":"Apple-Iphone5s-1_PT7515","time":54435,"result":"OK","sendList":[{"name":"Apple-IpadAir2-1_PT3239.C7DKtQ==","time":40752,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-IpadAir2-1_PT3239.85RfWg==","time":5590,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1_PT4820.TWfskw==","time":3863,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT4002.r/utkA==","time":3494,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone5s-1_PT7515 ios (4 left)

2016-01-05T00:44:25.441Z - info: Received results for {"name:":"Apple-Iphone5-1_PT4002","time":54146,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT4820.GNbylA==","time":40440,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-IpadAir2-1_PT3239.85RfWg==","time":4531,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1_PT4820.TWfskw==","time":4374,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT7515.viE/5Q==","time":3741,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone5-1_PT4002 ios (3 left)

2016-01-05T00:44:25.921Z - info: Received results for {"name:":"Apple-IpadAir2-1_PT3239","time":55514,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT4820.GNbylA==","time":42446,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-Iphone6-1_PT4820.TWfskw==","time":4498,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT7515.viE/5Q==","time":4061,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT4002.r/utkA==","time":3986,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-IpadAir2-1_PT3239 ios (2 left)

2016-01-05T00:45:08.889Z - info: Received results for {"name:":"Apple-Iphone6-1_PT4820","time":98259,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT4820.GNbylA==","time":42090,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-IpadAir2-1_PT3239.85RfWg==","time":44544,"result":"OK","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT7515.viE/5Q==","time":4204,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT4002.r/utkA==","time":7232,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone6-1_PT4820 ios (1 left)

2016-01-05T00:45:08.891Z - info: All test data retrieved for testSendData.js (ios)

2016-01-05T00:45:08.896Z - info: Remaining tests: %s ios=[]

2016-01-05T00:45:08.899Z - info: ALL DONE !!!

{ 'name:': 'Apple-Iphone5-1_PT4002',
  time: 1063,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT4820.GNbylA==',
       peerAvailable: true,
       time: 1061 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT7515',
  time: 352,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT4820.GNbylA==',
       peerAvailable: true,
       time: 349 } ] }

{ 'name:': 'Apple-Iphone6-1_PT4820',
  time: 1126,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1_PT4002.tre7Iw==',
       peerAvailable: true,
       time: 1124 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT3239',
  time: 1277,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT4820.GNbylA==',
       peerAvailable: true,
       time: 1276 } ] }

{ 'name:': 'Apple-Iphone5-1_PT4002',
  time: 54146,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4820.GNbylA==',
       time: 40440,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT3239.85RfWg==',
       time: 4531,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT4820.TWfskw==',
       time: 4374,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT7515.viE/5Q==',
       time: 3741,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT7515',
  time: 54435,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT3239.C7DKtQ==',
       time: 40752,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT3239.85RfWg==',
       time: 5590,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT4820.TWfskw==',
       time: 3863,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT4002.r/utkA==',
       time: 3494,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1_PT4820',
  time: 98259,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4820.GNbylA==',
       time: 42090,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT3239.85RfWg==',
       time: 44544,
       result: 'OK',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT7515.viE/5Q==',
       time: 4204,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT4002.r/utkA==',
       time: 7232,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT3239',
  time: 55514,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4820.GNbylA==',
       time: 42446,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT4820.TWfskw==',
       time: 4498,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT7515.viE/5Q==',
       time: 4061,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT4002.r/utkA==',
       time: 3986,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

--------------- test report ---------------------
--------------- Apple-Iphone5-1_PT4002 --------------------- : 1

peersList : 100% : 1061 ms, 99% : 1061 ms, 95 : 1061 ms, 90% : 1061 ms.

Result count 1, range 1061 ms to  1061 ms.

sendList : 100% : 4531 ms, 99% : 4531 ms, 95 : 4531 ms, 90% : 4531 ms.

Average data rate: 0.024 MB/s

Result count 3, range 3741 ms to  4531 ms.

sendList failed peers count : 1 [25 %]

- Peer ID : Apple-Iphone6-1_PT4820.GNbylA==, Tried : 5

sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5s-1_PT7515 --------------------- : 2
peersList : 100% : 349 ms, 99% : 349 ms, 95 : 349 ms, 90% : 349 ms.

Result count 1, range 349 ms to  349 ms.
sendList : 100% : 5590 ms, 99% : 5590 ms, 95 : 5590 ms, 90% : 5590 ms.

Average data rate: 0.023 MB/s
Result count 3, range 3494 ms to  5590 ms.

sendList failed peers count : 1 [25 %]
- Peer ID : Apple-IpadAir2-1_PT3239.C7DKtQ==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone6-1_PT4820 --------------------- : 3
peersList : 100% : 1124 ms, 99% : 1124 ms, 95 : 1124 ms, 90% : 1124 ms.
Result count 1, range 1124 ms to  1124 ms.

sendList : 100% : 44544 ms, 99% : 44544 ms, 95 : 44544 ms, 90% : 44544 ms.
Average data rate: 0.005 MB/s
Result count 3, range 4204 ms to  44544 ms.
sendList failed peers count : 1 [25 %]

- Peer ID : Apple-Iphone6-1_PT4820.GNbylA==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-IpadAir2-1_PT3239 --------------------- : 4

peersList : 100% : 1276 ms, 99% : 1276 ms, 95 : 1276 ms, 90% : 1276 ms.
Result count 1, range 1276 ms to  1276 ms.
sendList : 100% : 4498 ms, 99% : 4498 ms, 95 : 4498 ms, 90% : 4498 ms.

Average data rate: 0.024 MB/s
Result count 3, range 3986 ms to  4498 ms.
sendList failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone6-1_PT4820.GNbylA==, Tried : 5

sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------

peersList : 100% : 1276 ms, 99% : 1276 ms, 95 : 1276 ms, 90% : 1276 ms.

sendList : 100% : 44544 ms, 99% : 44544 ms, 95 : 7232 ms, 90% : 7232 ms.
Average data rate: 0.013 MB/s
--------------- end of test report ---------------------

2016-01-05T00:45:09.018Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1_PT4820.GNbylA==, peerAvailable=true, time=1061], sendList=[name=Apple-Iphone5s-1_PT7515.viE/5Q==, time=3741, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone6-1_PT4820.TWfskw==, time=4374, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1_PT3239.85RfWg==, time=4531, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone6-1_PT4820.GNbylA==, time=40440, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1_PT4820.GNbylA==, peerAvailable=true, time=349], sendList=[name=Apple-Iphone5-1_PT4002.r/utkA==, time=3494, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone6-1_PT4820.TWfskw==, time=3863, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1_PT3239.85RfWg==, time=5590, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-IpadAir2-1_PT3239.C7DKtQ==, time=40752, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1_PT4002.tre7Iw==, peerAvailable=true, time=1124], sendList=[name=Apple-Iphone5s-1_PT7515.viE/5Q==, time=4204, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1_PT4002.r/utkA==, time=7232, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1_PT3239.85RfWg==, time=44544, result=OK, connections=5, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone6-1_PT4820.GNbylA==, time=42090, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1_PT4820.GNbylA==, peerAvailable=true, time=1276], sendList=[name=Apple-Iphone5-1_PT4002.r/utkA==, time=3986, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5s-1_PT7515.viE/5Q==, time=4061, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone6-1_PT4820.TWfskw==, time=4498, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone6-1_PT4820.GNbylA==, time=42446, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[]

2016-01-05T00:45:09.029Z - debug: end to Apple-Iphone5-1_PT4002

2016-01-05T00:45:09.031Z - debug: end to Apple-Iphone5s-1_PT7515

2016-01-05T00:45:09.032Z - debug: end to Apple-Iphone6-1_PT4820

2016-01-05T00:45:09.034Z - debug: end to Apple-IpadAir2-1_PT3239

2016-01-05T00:45:12.635Z - debug: Socket disconnected: transport close 3 (Apple-Iphone6-1_PT4820)

2016-01-05T00:45:12.985Z - debug: Socket disconnected: transport close 15 (Apple-IpadAir2-1_PT3239)

2016-01-05T00:45:15.663Z - debug: Socket disconnected: transport close 1 (Apple-Iphone5s-1_PT7515)

2016-01-05T00:45:18.677Z - debug: state: ios completed

2016-01-05T00:45:18.678Z - debug: state: android waiting

2016-01-05T00:45:22.213Z - debug: Socket disconnected: transport close 0 (Apple-Iphone5-1_PT4002)

2016-01-05T00:45:23.405Z - info: Start timeout elapsed for platform: android

2016-01-05T00:45:23.408Z - info: Starting perf test run for platform: android

2016-01-05T00:45:23.409Z - info: Using devices:

2016-01-05T00:45:23.409Z - info: motorola-XT1072_PT4505
2016-01-05T00:45:23.410Z - info: samsung-SM-G900F_PT6440

2016-01-05T00:45:23.411Z - info: samsung-SM-A500FU_PT3690
2016-01-05T00:45:23.412Z - info: LGE-LG-D722_PT1779

2016-01-05T00:45:23.413Z - info: samsung-SM-A300FU_PT818
2016-01-05T00:45:23.414Z - info: LGE-LG-D855_PT2787

2016-01-05T00:45:23.414Z - info: HTC-HTC One M8s_PT8357

2016-01-05T00:45:23.415Z - info: samsung-SM-N910C_PT706
2016-01-05T00:45:23.416Z - info: samsung-SM-A500FU_PT9197

2016-01-05T00:45:23.417Z - info: samsung-SM-A300FU_PT6753
2016-01-05T00:45:23.417Z - info: LGE-LG-H815_PT177

2016-01-05T00:45:23.418Z - info: samsung-SM-G900F_PT6172

2016-01-05T00:45:23.419Z - info: LGE-Nexus 5_PT9383

2016-01-05T00:45:23.424Z - info: samsung-SM-G800F_PT2118

2016-01-05T00:45:23.425Z - info: Starting test: with 14 devices (android)

2016-01-05T00:45:26.388Z - info: Received results for {"name:":"samsung-SM-A500FU_PT3690","time":2688,"result":"OK","peersList":[{"peerName":"LGE-LG-D722_PT1779","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":2686}]} samsung-SM-A500FU_PT3690 android (14 left)

2016-01-05T00:45:26.780Z - info: Received results for {"name:":"samsung-SM-A300FU_PT818","time":3166,"result":"OK","peersList":[{"peerName":"LGE-Nexus 5_PT9383","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":true,"time":3165}]} samsung-SM-A300FU_PT818 android (13 left)

2016-01-05T00:45:27.072Z - info: Received results for {"name:":"HTC-HTC One M8s_PT8357","time":3232,"result":"OK","peersList":[{"peerName":"samsung-SM-A300FU_PT818","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":3229}]} HTC-HTC One M8s_PT8357 android (12 left)

2016-01-05T00:45:27.092Z - info: server timeout for test: testFindPeers.js (ios)

2016-01-05T00:45:27.095Z - info: All test data retrieved for testFindPeers.js (ios)

2016-01-05T00:45:27.096Z - info: Remaining tests: %s ios=[], android=[testFindPeers.js, testSendData.js]

2016-01-05T00:45:27.097Z - info: ALL DONE !!!

{ 'name:': 'Apple-Iphone5-1_PT4002',
  time: 1063,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT4820.GNbylA==',
       peerAvailable: true,
       time: 1061 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT7515',
  time: 352,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT4820.GNbylA==',
       peerAvailable: true,
       time: 349 } ] }

{ 'name:': 'Apple-Iphone6-1_PT4820',
  time: 1126,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1_PT4002.tre7Iw==',
       peerAvailable: true,
       time: 1124 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT3239',
  time: 1277,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT4820.GNbylA==',
       peerAvailable: true,
       time: 1276 } ] }

{ 'name:': 'Apple-Iphone5-1_PT4002',
  time: 54146,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4820.GNbylA==',
       time: 40440,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT3239.85RfWg==',
       time: 4531,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT4820.TWfskw==',
       time: 4374,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT7515.viE/5Q==',
       time: 3741,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT7515',
  time: 54435,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT3239.C7DKtQ==',
       time: 40752,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT3239.85RfWg==',
       time: 5590,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT4820.TWfskw==',
       time: 3863,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT4002.r/utkA==',
       time: 3494,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1_PT4820',
  time: 98259,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4820.GNbylA==',
       time: 42090,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT3239.85RfWg==',
       time: 44544,
       result: 'OK',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT7515.viE/5Q==',
       time: 4204,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT4002.r/utkA==',
       time: 7232,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT3239',
  time: 55514,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4820.GNbylA==',
       time: 42446,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT4820.TWfskw==',
       time: 4498,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT7515.viE/5Q==',
       time: 4061,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT4002.r/utkA==',
       time: 3986,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1_PT4002',
  time: 54146,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4820.GNbylA==',
       time: 40440,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT3239.85RfWg==',
       time: 4531,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT4820.TWfskw==',
       time: 4374,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT7515.viE/5Q==',
       time: 3741,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT7515',
  time: 54435,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT3239.C7DKtQ==',
       time: 40752,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT3239.85RfWg==',
       time: 5590,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT4820.TWfskw==',
       time: 3863,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT4002.r/utkA==',
       time: 3494,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }
{ 'name:': 'Apple-Iphone6-1_PT4820',
  time: 98259,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4820.GNbylA==',
       time: 42090,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT3239.85RfWg==',
       time: 44544,
       result: 'OK',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT7515.viE/5Q==',
       time: 4204,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT4002.r/utkA==',
       time: 7232,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }
{ 'name:': 'Apple-IpadAir2-1_PT3239',
  time: 55514,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4820.GNbylA==',
       time: 42446,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT4820.TWfskw==',
       time: 4498,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT7515.viE/5Q==',
       time: 4061,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT4002.r/utkA==',
       time: 3986,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }
--------------- test report ---------------------
--------------- Apple-Iphone5-1_PT4002 --------------------- : 1
peersList : 100% : 1061 ms, 99% : 1061 ms, 95 : 1061 ms, 90% : 1061 ms.
Result count 1, range 1061 ms to  1061 ms.
sendList : 100% : 4531 ms, 99% : 4531 ms, 95 : 4531 ms, 90% : 4531 ms.
Average data rate: 0.024 MB/s
Result count 6, range 3741 ms to  4531 ms.
sendList failed peers count : 2 [25 %]
- Peer ID : Apple-Iphone6-1_PT4820.GNbylA==, Tried : 5
- Peer ID : Apple-Iphone6-1_PT4820.GNbylA==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5s-1_PT7515 --------------------- : 2
peersList : 100% : 349 ms, 99% : 349 ms, 95 : 349 ms, 90% : 349 ms.
Result count 1, range 349 ms to  349 ms.
sendList : 100% : 5590 ms, 99% : 5590 ms, 95 : 5590 ms, 90% : 5590 ms.
Average data rate: 0.023 MB/s
Result count 6, range 3494 ms to  5590 ms.
sendList failed peers count : 2 [25 %]
- Peer ID : Apple-IpadAir2-1_PT3239.C7DKtQ==, Tried : 5
- Peer ID : Apple-IpadAir2-1_PT3239.C7DKtQ==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1_PT4820 --------------------- : 3
peersList : 100% : 1124 ms, 99% : 1124 ms, 95 : 1124 ms, 90% : 1124 ms.
Result count 1, range 1124 ms to  1124 ms.
sendList : 100% : 44544 ms, 99% : 44544 ms, 95 : 44544 ms, 90% : 44544 ms.
Average data rate: 0.005 MB/s
Result count 6, range 4204 ms to  44544 ms.
sendList failed peers count : 2 [25 %]
- Peer ID : Apple-Iphone6-1_PT4820.GNbylA==, Tried : 5
- Peer ID : Apple-Iphone6-1_PT4820.GNbylA==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Apple-IpadAir2-1_PT3239 --------------------- : 4
peersList : 100% : 1276 ms, 99% : 1276 ms, 95 : 1276 ms, 90% : 1276 ms.
Result count 1, range 1276 ms to  1276 ms.
sendList : 100% : 4498 ms, 99% : 4498 ms, 95 : 4498 ms, 90% : 4498 ms.
Average data rate: 0.024 MB/s
Result count 6, range 3986 ms to  4498 ms.
sendList failed peers count : 2 [25 %]

- Peer ID : Apple-Iphone6-1_PT4820.GNbylA==, Tried : 5
- Peer ID : Apple-Iphone6-1_PT4820.GNbylA==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------
peersList : 100% : 1276 ms, 99% : 1276 ms, 95 : 1276 ms, 90% : 1276 ms.
sendList : 100% : 44544 ms, 99% : 44544 ms, 95 : 44544 ms, 90% : 7232 ms.
Average data rate: 0.013 MB/s
--------------- end of test report ---------------------

2016-01-05T00:45:27.220Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1_PT4820.GNbylA==, peerAvailable=true, time=1061], sendList=[name=Apple-Iphone5s-1_PT7515.viE/5Q==, time=3741, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1_PT4002"]["sendList"][0], name=Apple-Iphone6-1_PT4820.TWfskw==, time=4374, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1_PT4002"]["sendList"][2], name=Apple-IpadAir2-1_PT3239.85RfWg==, time=4531, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1_PT4002"]["sendList"][4]], failedPeer=[name=Apple-Iphone6-1_PT4820.GNbylA==, time=40440, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone5-1_PT4002"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1_PT4820.GNbylA==, peerAvailable=true, time=349], sendList=[name=Apple-Iphone5-1_PT4002.r/utkA==, time=3494, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1_PT7515"]["sendList"][0], name=Apple-Iphone6-1_PT4820.TWfskw==, time=3863, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1_PT7515"]["sendList"][2], name=Apple-IpadAir2-1_PT3239.85RfWg==, time=5590, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1_PT7515"]["sendList"][4]], failedPeer=[name=Apple-IpadAir2-1_PT3239.C7DKtQ==, time=40752, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone5s-1_PT7515"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1_PT4002.tre7Iw==, peerAvailable=true, time=1124], sendList=[name=Apple-Iphone5s-1_PT7515.viE/5Q==, time=4204, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1_PT4820"]["sendList"][0], name=Apple-Iphone5-1_PT4002.r/utkA==, time=7232, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1_PT4820"]["sendList"][2], name=Apple-IpadAir2-1_PT3239.85RfWg==, time=44544, result=OK, connections=5, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1_PT4820"]["sendList"][4]], failedPeer=[name=Apple-Iphone6-1_PT4820.GNbylA==, time=42090, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone6-1_PT4820"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1_PT4820.GNbylA==, peerAvailable=true, time=1276], sendList=[name=Apple-Iphone5-1_PT4002.r/utkA==, time=3986, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1_PT3239"]["sendList"][0], name=Apple-Iphone5s-1_PT7515.viE/5Q==, time=4061, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1_PT3239"]["sendList"][2], name=Apple-Iphone6-1_PT4820.TWfskw==, time=4498, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1_PT3239"]["sendList"][4]], failedPeer=[name=Apple-Iphone6-1_PT4820.GNbylA==, time=42446, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-IpadAir2-1_PT3239"]["sendError"]["failedPeer"][0]], notTriedList=[]

2016-01-05T00:45:27.230Z - debug: end to Apple-Iphone5-1_PT4002

2016-01-05T00:45:27.232Z - debug: end to Apple-Iphone5s-1_PT7515

2016-01-05T00:45:27.233Z - debug: end to Apple-Iphone6-1_PT4820
2016-01-05T00:45:27.235Z - debug: end to Apple-IpadAir2-1_PT3239

2016-01-05T00:45:27.243Z - info: Received results for {"name:":"motorola-XT1072_PT4505","time":3274,"result":"OK","peersList":[{"peerName":"samsung-SM-A300FU_PT818","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":3273}]} motorola-XT1072_PT4505 android (11 left)

2016-01-05T00:45:27.246Z - info: Received results for {"name:":"samsung-SM-A300FU_PT6753","time":3129,"result":"OK","peersList":[{"peerName":"samsung-SM-A300FU_PT818","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":3128}]} samsung-SM-A300FU_PT6753 android (10 left)

2016-01-05T00:45:27.483Z - info: Received results for {"name:":"LGE-LG-H815_PT177","time":3851,"result":"OK","peersList":[{"peerName":"HTC-HTC One M8s_PT8357","peerIdentifier":"90:E7:C4:F6:69:77","peerAvailable":true,"time":3849}]} LGE-LG-H815_PT177 android (9 left)

2016-01-05T00:45:28.486Z - info: Received results for {"name:":"samsung-SM-A500FU_PT9197","time":4455,"result":"OK","peersList":[{"peerName":"LGE-LG-D722_PT1779","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":4453}]} samsung-SM-A500FU_PT9197 android (8 left)

2016-01-05T00:45:28.904Z - info: Received results for {"name:":"LGE-Nexus 5_PT9383","time":4785,"result":"OK","peersList":[{"peerName":"samsung-SM-A300FU_PT6753","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":4782}]} LGE-Nexus 5_PT9383 android (7 left)

2016-01-05T00:45:29.006Z - info: Received results for {"name:":"LGE-LG-D855_PT2787","time":2075,"result":"OK","peersList":[{"peerName":"samsung-SM-A300FU_PT6753","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":2074}]} LGE-LG-D855_PT2787 android (6 left)

2016-01-05T00:45:29.391Z - info: Received results for {"name:":"samsung-SM-G900F_PT6440","time":3877,"result":"OK","peersList":[{"peerName":"samsung-SM-A300FU_PT818","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":3873}]} samsung-SM-G900F_PT6440 android (5 left)

2016-01-05T00:45:30.164Z - info: server timeout for test: testSendData.js (ios)

2016-01-05T00:45:30.167Z - info: All test data retrieved for testSendData.js (ios)

2016-01-05T00:45:30.168Z - info: Remaining tests: %s ios=[], android=[testFindPeers.js, testSendData.js]
2016-01-05T00:45:30.170Z - info: ALL DONE !!!

{ 'name:': 'Apple-Iphone5-1_PT4002',
  time: 1063,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT4820.GNbylA==',
       peerAvailable: true,
       time: 1061 } ] }
{ 'name:': 'Apple-Iphone5s-1_PT7515',
  time: 352,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT4820.GNbylA==',
       peerAvailable: true,
       time: 349 } ] }
{ 'name:': 'Apple-Iphone6-1_PT4820',
  time: 1126,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1_PT4002.tre7Iw==',
       peerAvailable: true,
       time: 1124 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT3239',
  time: 1277,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT4820.GNbylA==',
       peerAvailable: true,
       time: 1276 } ] }

{ 'name:': 'Apple-Iphone5-1_PT4002',
  time: 54146,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4820.GNbylA==',
       time: 40440,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT3239.85RfWg==',
       time: 4531,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT4820.TWfskw==',
       time: 4374,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT7515.viE/5Q==',
       time: 3741,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT7515',
  time: 54435,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT3239.C7DKtQ==',
       time: 40752,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT3239.85RfWg==',
       time: 5590,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT4820.TWfskw==',
       time: 3863,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT4002.r/utkA==',
       time: 3494,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1_PT4820',
  time: 98259,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4820.GNbylA==',
       time: 42090,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT3239.85RfWg==',
       time: 44544,
       result: 'OK',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT7515.viE/5Q==',
       time: 4204,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT4002.r/utkA==',
       time: 7232,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT3239',
  time: 55514,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4820.GNbylA==',
       time: 42446,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT4820.TWfskw==',
       time: 4498,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT7515.viE/5Q==',
       time: 4061,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT4002.r/utkA==',
       time: 3986,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1_PT4002',
  time: 54146,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4820.GNbylA==',
       time: 40440,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT3239.85RfWg==',
       time: 4531,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT4820.TWfskw==',
       time: 4374,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT7515.viE/5Q==',
       time: 3741,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT7515',
  time: 54435,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT3239.C7DKtQ==',
       time: 40752,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT3239.85RfWg==',
       time: 5590,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT4820.TWfskw==',
       time: 3863,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT4002.r/utkA==',
       time: 3494,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1_PT4820',
  time: 98259,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4820.GNbylA==',
       time: 42090,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT3239.85RfWg==',
       time: 44544,
       result: 'OK',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT7515.viE/5Q==',
       time: 4204,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT4002.r/utkA==',
       time: 7232,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT3239',
  time: 55514,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4820.GNbylA==',
       time: 42446,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT4820.TWfskw==',
       time: 4498,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT7515.viE/5Q==',
       time: 4061,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT4002.r/utkA==',
       time: 3986,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1_PT4002',
  time: 54146,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4820.GNbylA==',
       time: 40440,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT3239.85RfWg==',
       time: 4531,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT4820.TWfskw==',
       time: 4374,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT7515.viE/5Q==',
       time: 3741,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT7515',
  time: 54435,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT3239.C7DKtQ==',
       time: 40752,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT3239.85RfWg==',
       time: 5590,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT4820.TWfskw==',
       time: 3863,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT4002.r/utkA==',
       time: 3494,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1_PT4820',
  time: 98259,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4820.GNbylA==',
       time: 42090,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT3239.85RfWg==',
       time: 44544,
       result: 'OK',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT7515.viE/5Q==',
       time: 4204,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT4002.r/utkA==',
       time: 7232,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT3239',
  time: 55514,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4820.GNbylA==',
       time: 42446,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT4820.TWfskw==',
       time: 4498,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT7515.viE/5Q==',
       time: 4061,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT4002.r/utkA==',
       time: 3986,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

--------------- test report ---------------------
--------------- Apple-Iphone5-1_PT4002 --------------------- : 1
peersList : 100% : 1061 ms, 99% : 1061 ms, 95 : 1061 ms, 90% : 1061 ms.
Result count 1, range 1061 ms to  1061 ms.

sendList : 100% : 4531 ms, 99% : 4531 ms, 95 : 4531 ms, 90% : 4531 ms.
Average data rate: 0.024 MB/s
Result count 9, range 3741 ms to  4531 ms.
sendList failed peers count : 3 [25 %]
- Peer ID : Apple-Iphone6-1_PT4820.GNbylA==, Tried : 5
- Peer ID : Apple-Iphone6-1_PT4820.GNbylA==, Tried : 5

- Peer ID : Apple-Iphone6-1_PT4820.GNbylA==, Tried : 5

sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5s-1_PT7515 --------------------- : 2
peersList : 100% : 349 ms, 99% : 349 ms, 95 : 349 ms, 90% : 349 ms.
Result count 1, range 349 ms to  349 ms.
sendList : 100% : 5590 ms, 99% : 5590 ms, 95 : 5590 ms, 90% : 5590 ms.

Average data rate: 0.023 MB/s
Result count 9, range 3494 ms to  5590 ms.
sendList failed peers count : 3 [25 %]
- Peer ID : Apple-IpadAir2-1_PT3239.C7DKtQ==, Tried : 5
- Peer ID : Apple-IpadAir2-1_PT3239.C7DKtQ==, Tried : 5
- Peer ID : Apple-IpadAir2-1_PT3239.C7DKtQ==, Tried : 5

sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone6-1_PT4820 --------------------- : 3
peersList : 100% : 1124 ms, 99% : 1124 ms, 95 : 1124 ms, 90% : 1124 ms.
Result count 1, range 1124 ms to  1124 ms.
sendList : 100% : 44544 ms, 99% : 44544 ms, 95 : 44544 ms, 90% : 44544 ms.

Average data rate: 0.005 MB/s
Result count 9, range 4204 ms to  44544 ms.
sendList failed peers count : 3 [25 %]
- Peer ID : Apple-Iphone6-1_PT4820.GNbylA==, Tried : 5
- Peer ID : Apple-Iphone6-1_PT4820.GNbylA==, Tried : 5
- Peer ID : Apple-Iphone6-1_PT4820.GNbylA==, Tried : 5

sendList never tried peers count : 0 [0 %]
--------------- Apple-IpadAir2-1_PT3239 --------------------- : 4

peersList : 100% : 1276 ms, 99% : 1276 ms, 95 : 1276 ms, 90% : 1276 ms.

Result count 1, range 1276 ms to  1276 ms.
sendList : 100% : 4498 ms, 99% : 4498 ms, 95 : 4498 ms, 90% : 4498 ms.
Average data rate: 0.024 MB/s
Result count 9, range 3986 ms to  4498 ms.
sendList failed peers count : 3 [25 %]

- Peer ID : Apple-Iphone6-1_PT4820.GNbylA==, Tried : 5
- Peer ID : Apple-Iphone6-1_PT4820.GNbylA==, Tried : 5
- Peer ID : Apple-Iphone6-1_PT4820.GNbylA==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------

peersList : 100% : 1276 ms, 99% : 1276 ms, 95 : 1276 ms, 90% : 1276 ms.

sendList : 100% : 44544 ms, 99% : 44544 ms, 95 : 44544 ms, 90% : 7232 ms.

Average data rate: 0.013 MB/s
--------------- end of test report ---------------------

2016-01-05T00:45:30.310Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1_PT4820.GNbylA==, peerAvailable=true, time=1061], sendList=[name=Apple-Iphone5s-1_PT7515.viE/5Q==, time=3741, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1_PT4002"]["sendList"][0], $ref=$["Apple-Iphone5-1_PT4002"]["sendList"][0], name=Apple-Iphone6-1_PT4820.TWfskw==, time=4374, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1_PT4002"]["sendList"][3], $ref=$["Apple-Iphone5-1_PT4002"]["sendList"][3], name=Apple-IpadAir2-1_PT3239.85RfWg==, time=4531, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1_PT4002"]["sendList"][6], $ref=$["Apple-Iphone5-1_PT4002"]["sendList"][6]], failedPeer=[name=Apple-Iphone6-1_PT4820.GNbylA==, time=40440, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone5-1_PT4002"]["sendError"]["failedPeer"][0], $ref=$["Apple-Iphone5-1_PT4002"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1_PT4820.GNbylA==, peerAvailable=true, time=349], sendList=[name=Apple-Iphone5-1_PT4002.r/utkA==, time=3494, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1_PT7515"]["sendList"][0], $ref=$["Apple-Iphone5s-1_PT7515"]["sendList"][0], name=Apple-Iphone6-1_PT4820.TWfskw==, time=3863, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1_PT7515"]["sendList"][3], $ref=$["Apple-Iphone5s-1_PT7515"]["sendList"][3], name=Apple-IpadAir2-1_PT3239.85RfWg==, time=5590, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1_PT7515"]["sendList"][6], $ref=$["Apple-Iphone5s-1_PT7515"]["sendList"][6]], failedPeer=[name=Apple-IpadAir2-1_PT3239.C7DKtQ==, time=40752, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone5s-1_PT7515"]["sendError"]["failedPeer"][0], $ref=$["Apple-Iphone5s-1_PT7515"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1_PT4002.tre7Iw==, peerAvailable=true, time=1124], sendList=[name=Apple-Iphone5s-1_PT7515.viE/5Q==, time=4204, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1_PT4820"]["sendList"][0], $ref=$["Apple-Iphone6-1_PT4820"]["sendList"][0], name=Apple-Iphone5-1_PT4002.r/utkA==, time=7232, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1_PT4820"]["sendList"][3], $ref=$["Apple-Iphone6-1_PT4820"]["sendList"][3], name=Apple-IpadAir2-1_PT3239.85RfWg==, time=44544, result=OK, connections=5, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1_PT4820"]["sendList"][6], $ref=$["Apple-Iphone6-1_PT4820"]["sendList"][6]], failedPeer=[name=Apple-Iphone6-1_PT4820.GNbylA==, time=42090, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone6-1_PT4820"]["sendError"]["failedPeer"][0], $ref=$["Apple-Iphone6-1_PT4820"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1_PT4820.GNbylA==, peerAvailable=true, time=1276], sendList=[name=Apple-Iphone5-1_PT4002.r/utkA==, time=3986, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1_PT3239"]["sendList"][0], $ref=$["Apple-IpadAir2-1_PT3239"]["sendList"][0], name=Apple-Iphone5s-1_PT7515.viE/5Q==, time=4061, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1_PT3239"]["sendList"][3], $ref=$["Apple-IpadAir2-1_PT3239"]["sendList"][3], name=Apple-Iphone6-1_PT4820.TWfskw==, time=4498, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1_PT3239"]["sendList"][6], $ref=$["Apple-IpadAir2-1_PT3239"]["sendList"][6]], failedPeer=[name=Apple-Iphone6-1_PT4820.GNbylA==, time=42446, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-IpadAir2-1_PT3239"]["sendError"]["failedPeer"][0], $ref=$["Apple-IpadAir2-1_PT3239"]["sendError"]["failedPeer"][0]], notTriedList=[]

2016-01-05T00:45:30.317Z - debug: end to Apple-Iphone5-1_PT4002
2016-01-05T00:45:30.318Z - debug: end to Apple-Iphone5s-1_PT7515

2016-01-05T00:45:30.319Z - debug: end to Apple-Iphone6-1_PT4820
2016-01-05T00:45:30.320Z - debug: end to Apple-IpadAir2-1_PT3239

2016-01-05T00:45:30.772Z - info: Received results for {"name:":"samsung-SM-G900F_PT6172","time":5280,"result":"OK","peersList":[{"peerName":"LGE-LG-D855_PT2787","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":5273}]} samsung-SM-G900F_PT6172 android (4 left)

2016-01-05T00:45:39.425Z - info: Received results for {"name:":"LGE-LG-D722_PT1779","time":15336,"result":"OK","peersList":[{"peerName":"samsung-SM-G900F_PT6440","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":15335}]} LGE-LG-D722_PT1779 android (3 left)

2016-01-05T00:46:04.821Z - info: Received results for {"name:":"samsung-SM-N910C_PT706","time":41197,"result":"OK","peersList":[{"peerName":"samsung-SM-A300FU_PT818","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":41194}]} samsung-SM-N910C_PT706 android (2 left)

2016-01-05T00:47:23.431Z - info: server timeout for test: testFindPeers.js (android)

2016-01-05T00:47:23.433Z - info: All test data retrieved for testFindPeers.js (android)

2016-01-05T00:47:23.442Z - info: No results from samsung-SM-G800F_PT2118

2016-01-05T00:47:23.443Z - info: Remaining tests: %s ios=[], android=[testSendData.js]

2016-01-05T00:47:23.445Z - info: Continuing to next test: testSendData.js

2016-01-05T00:47:23.446Z - info: Starting test: with 14 devices (android)

2016-01-05T00:49:03.645Z - info: Received results for {"name:":"samsung-SM-A500FU_PT3690","time":100067,"result":"TIMEOUT","sendList":[{"name":"34:FC:EF:11:AE:67","time":3604,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"90:E7:C4:F6:69:77","time":3183,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:75:41","time":4153,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"44:80:EB:7B:5A:05","time":4079,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} samsung-SM-A500FU_PT3690 android (14 left)

2016-01-05T00:49:03.673Z - info: Received results for {"name:":"LGE-LG-D722_PT1779","time":100078,"result":"TIMEOUT","sendList":[{"name":"58:3F:54:73:64:C0","time":2768,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":4759,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:75:41","time":3978,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} LGE-LG-D722_PT1779 android (13 left)

2016-01-05T00:49:03.708Z - info: Received results for {"name:":"samsung-SM-G900F_PT6440","time":100074,"result":"TIMEOUT","sendList":[{"name":"58:3F:54:73:64:C0","time":11260,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"34:FC:EF:11:AE:67","time":3209,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:37:96:AB","time":4237,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} samsung-SM-G900F_PT6440 android (12 left)

2016-01-05T00:49:03.795Z - info: Received results for {"name:":"LGE-Nexus 5_PT9383","time":100034,"result":"TIMEOUT","sendList":[{"name":"7C:F9:0E:51:18:22","time":3542,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":6957,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} LGE-Nexus 5_PT9383 android (11 left)

2016-01-05T00:49:03.797Z - info: Received results for {"name:":"samsung-SM-G900F_PT6172","time":100086,"result":"TIMEOUT","sendList":[{"name":"08:EC:A9:50:76:27","time":5354,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} samsung-SM-G900F_PT6172 android (10 left)

2016-01-05T00:49:03.959Z - info: Received results for {"name:":"samsung-SM-A300FU_PT818","time":100050,"result":"TIMEOUT","sendList":[{"name":"44:80:EB:7B:5A:05","time":2983,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:51:18:22","time":1520,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":8169,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:37:96:AB","time":3720,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} samsung-SM-A300FU_PT818 android (9 left)

2016-01-05T00:49:04.082Z - info: Received results for {"name:":"LGE-LG-H815_PT177","time":100064,"result":"TIMEOUT","sendList":[{"name":"08:EC:A9:50:75:41","time":8255,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} LGE-LG-H815_PT177 android (8 left)

2016-01-05T00:49:04.098Z - info: Received results for {"name:":"samsung-SM-N910C_PT706","time":100053,"result":"TIMEOUT","sendList":[]} samsung-SM-N910C_PT706 android (7 left)

2016-01-05T00:49:04.490Z - info: Received results for {"name:":"HTC-HTC One M8s_PT8357","time":100049,"result":"TIMEOUT","sendList":[]} HTC-HTC One M8s_PT8357 android (6 left)

2016-01-05T00:49:04.511Z - info: Received results for {"name:":"LGE-LG-D855_PT2787","time":100072,"result":"TIMEOUT","sendList":[{"name":"7C:F9:0E:37:96:AB","time":2648,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:51:18:22","time":5306,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":6157,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:75:41","time":5851,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"44:80:EB:7B:5A:05","time":2460,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} LGE-LG-D855_PT2787 android (5 left)

2016-01-05T00:49:05.260Z - info: Received results for {"name:":"samsung-SM-A500FU_PT9197","time":100045,"result":"TIMEOUT","sendList":[]} samsung-SM-A500FU_PT9197 android (4 left)

2016-01-05T00:49:07.302Z - info: Received results for {"name:":"samsung-SM-A300FU_PT6753","time":100060,"result":"TIMEOUT","sendList":[{"name":"F8:95:C7:87:3C:51","time":4301,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} samsung-SM-A300FU_PT6753 android (3 left)

2016-01-05T00:49:12.308Z - debug: Device presented: motorola-XT1072_PT4505 (android) perftest socket:18

2016-01-05T00:49:12.310Z - info: Updating existing device: motorola-XT1072_PT4505 (84c9e5dd-2d2b-4537-bccd-48af048b24d7)

2016-01-05T00:49:12.324Z - info: Received results for {"name:":"motorola-XT1072_PT4505","time":100073,"result":"TIMEOUT","sendList":[]} motorola-XT1072_PT4505 android (2 left)

2016-01-05T00:49:23.451Z - info: server timeout for test: testSendData.js (android)

2016-01-05T00:49:23.452Z - info: All test data retrieved for testSendData.js (android)

2016-01-05T00:49:23.464Z - info: No results from samsung-SM-G800F_PT2118

2016-01-05T00:49:23.465Z - info: Remaining tests: %s ios=[], android=[]
2016-01-05T00:49:23.466Z - info: ALL DONE !!!

{ 'name:': 'Apple-Iphone5-1_PT4002',
  time: 1063,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT4820.GNbylA==',
       peerAvailable: true,
       time: 1061 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT7515',
  time: 352,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT4820.GNbylA==',
       peerAvailable: true,
       time: 349 } ] }

{ 'name:': 'Apple-Iphone6-1_PT4820',
  time: 1126,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1_PT4002.tre7Iw==',
       peerAvailable: true,
       time: 1124 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT3239',
  time: 1277,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT4820.GNbylA==',
       peerAvailable: true,
       time: 1276 } ] }

{ 'name:': 'Apple-Iphone5-1_PT4002',
  time: 54146,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4820.GNbylA==',
       time: 40440,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT3239.85RfWg==',
       time: 4531,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT4820.TWfskw==',
       time: 4374,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT7515.viE/5Q==',
       time: 3741,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT7515',
  time: 54435,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT3239.C7DKtQ==',
       time: 40752,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT3239.85RfWg==',
       time: 5590,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT4820.TWfskw==',
       time: 3863,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT4002.r/utkA==',
       time: 3494,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1_PT4820',
  time: 98259,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4820.GNbylA==',
       time: 42090,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT3239.85RfWg==',
       time: 44544,
       result: 'OK',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT7515.viE/5Q==',
       time: 4204,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT4002.r/utkA==',
       time: 7232,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT3239',
  time: 55514,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4820.GNbylA==',
       time: 42446,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT4820.TWfskw==',
       time: 4498,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT7515.viE/5Q==',
       time: 4061,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT4002.r/utkA==',
       time: 3986,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1_PT4002',
  time: 54146,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4820.GNbylA==',
       time: 40440,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT3239.85RfWg==',
       time: 4531,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT4820.TWfskw==',
       time: 4374,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT7515.viE/5Q==',
       time: 3741,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT7515',
  time: 54435,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT3239.C7DKtQ==',
       time: 40752,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT3239.85RfWg==',
       time: 5590,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT4820.TWfskw==',
       time: 3863,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT4002.r/utkA==',
       time: 3494,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1_PT4820',
  time: 98259,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4820.GNbylA==',
       time: 42090,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT3239.85RfWg==',
       time: 44544,
       result: 'OK',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT7515.viE/5Q==',
       time: 4204,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT4002.r/utkA==',
       time: 7232,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT3239',
  time: 55514,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4820.GNbylA==',
       time: 42446,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT4820.TWfskw==',
       time: 4498,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT7515.viE/5Q==',
       time: 4061,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT4002.r/utkA==',
       time: 3986,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1_PT4002',
  time: 54146,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4820.GNbylA==',
       time: 40440,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT3239.85RfWg==',
       time: 4531,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT4820.TWfskw==',
       time: 4374,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT7515.viE/5Q==',
       time: 3741,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT7515',
  time: 54435,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT3239.C7DKtQ==',
       time: 40752,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT3239.85RfWg==',
       time: 5590,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT4820.TWfskw==',
       time: 3863,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT4002.r/utkA==',
       time: 3494,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1_PT4820',
  time: 98259,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4820.GNbylA==',
       time: 42090,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT3239.85RfWg==',
       time: 44544,
       result: 'OK',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT7515.viE/5Q==',
       time: 4204,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT4002.r/utkA==',
       time: 7232,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT3239',
  time: 55514,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT4820.GNbylA==',
       time: 42446,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT4820.TWfskw==',
       time: 4498,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT7515.viE/5Q==',
       time: 4061,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT4002.r/utkA==',
       time: 3986,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'motorola-XT1072_PT4505',
  time: 3274,
  result: 'OK',
  peersList: 
   [ { peerName: 'samsung-SM-A300FU_PT818',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 3273 } ] }

{ 'name:': 'samsung-SM-G900F_PT6440',
  time: 3877,
  result: 'OK',
  peersList: 
   [ { peerName: 'samsung-SM-A300FU_PT818',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 3873 } ] }

{ 'name:': 'samsung-SM-A500FU_PT3690',
  time: 2688,
  result: 'OK',
  peersList: 
   [ { peerName: 'LGE-LG-D722_PT1779',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 2686 } ] }

{ 'name:': 'LGE-LG-D722_PT1779',
  time: 15336,
  result: 'OK',
  peersList: 
   [ { peerName: 'samsung-SM-G900F_PT6440',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 15335 } ] }

{ 'name:': 'samsung-SM-A300FU_PT818',
  time: 3166,
  result: 'OK',
  peersList: 
   [ { peerName: 'LGE-Nexus 5_PT9383',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 3165 } ] }

{ 'name:': 'LGE-LG-D855_PT2787',
  time: 2075,
  result: 'OK',
  peersList: 
   [ { peerName: 'samsung-SM-A300FU_PT6753',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 2074 } ] }

{ 'name:': 'HTC-HTC One M8s_PT8357',
  time: 3232,
  result: 'OK',
  peersList: 
   [ { peerName: 'samsung-SM-A300FU_PT818',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 3229 } ] }

{ 'name:': 'samsung-SM-N910C_PT706',
  time: 41197,
  result: 'OK',
  peersList: 
   [ { peerName: 'samsung-SM-A300FU_PT818',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 41194 } ] }

{ 'name:': 'samsung-SM-A500FU_PT9197',
  time: 4455,
  result: 'OK',
  peersList: 
   [ { peerName: 'LGE-LG-D722_PT1779',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 4453 } ] }

{ 'name:': 'samsung-SM-A300FU_PT6753',
  time: 3129,
  result: 'OK',
  peersList: 
   [ { peerName: 'samsung-SM-A300FU_PT818',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 3128 } ] }

{ 'name:': 'LGE-LG-H815_PT177',
  time: 3851,
  result: 'OK',
  peersList: 
   [ { peerName: 'HTC-HTC One M8s_PT8357',
       peerIdentifier: '90:E7:C4:F6:69:77',
       peerAvailable: true,
       time: 3849 } ] }

{ 'name:': 'samsung-SM-G900F_PT6172',
  time: 5280,
  result: 'OK',
  peersList: 
   [ { peerName: 'LGE-LG-D855_PT2787',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 5273 } ] }

{ 'name:': 'LGE-Nexus 5_PT9383',
  time: 4785,
  result: 'OK',
  peersList: 
   [ { peerName: 'samsung-SM-A300FU_PT6753',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 4782 } ] }

{ 'name:': 'motorola-XT1072_PT4505',
  time: 100073,
  result: 'TIMEOUT',
  sendList: [] }

{ 'name:': 'samsung-SM-G900F_PT6440',
  time: 100074,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '58:3F:54:73:64:C0',
       time: 11260,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '34:FC:EF:11:AE:67',
       time: 3209,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:37:96:AB',
       time: 4237,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'samsung-SM-A500FU_PT3690',
  time: 100067,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '34:FC:EF:11:AE:67',
       time: 3604,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '90:E7:C4:F6:69:77',
       time: 3183,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '08:EC:A9:50:75:41',
       time: 4153,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '44:80:EB:7B:5A:05',
       time: 4079,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'LGE-LG-D722_PT1779',
  time: 100078,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '58:3F:54:73:64:C0',
       time: 2768,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:3C:51',
       time: 4759,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '08:EC:A9:50:75:41',
       time: 3978,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'samsung-SM-A300FU_PT818',
  time: 100050,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '44:80:EB:7B:5A:05',
       time: 2983,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:51:18:22',
       time: 1520,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:85:54',
       time: 8169,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:37:96:AB',
       time: 3720,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'LGE-LG-D855_PT2787',
  time: 100072,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '7C:F9:0E:37:96:AB',
       time: 2648,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:51:18:22',
       time: 5306,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'B0:C5:59:3F:75:69',
       time: 6157,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '08:EC:A9:50:75:41',
       time: 5851,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '44:80:EB:7B:5A:05',
       time: 2460,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'HTC-HTC One M8s_PT8357',
  time: 100049,
  result: 'TIMEOUT',
  sendList: [] }

{ 'name:': 'samsung-SM-N910C_PT706',
  time: 100053,
  result: 'TIMEOUT',
  sendList: [] }

{ 'name:': 'samsung-SM-A500FU_PT9197',
  time: 100045,
  result: 'TIMEOUT',
  sendList: [] }

{ 'name:': 'samsung-SM-A300FU_PT6753',
  time: 100060,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'F8:95:C7:87:3C:51',
       time: 4301,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'LGE-LG-H815_PT177',
  time: 100064,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '08:EC:A9:50:75:41',
       time: 8255,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'samsung-SM-G900F_PT6172',
  time: 100086,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '08:EC:A9:50:76:27',
       time: 5354,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'LGE-Nexus 5_PT9383',
  time: 100034,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '7C:F9:0E:51:18:22',
       time: 3542,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'B0:C5:59:3F:75:69',
       time: 6957,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

--------------- test report ---------------------
--------------- Apple-Iphone5-1_PT4002 --------------------- : 1
peersList : 100% : 1061 ms, 99% : 1061 ms, 95 : 1061 ms, 90% : 1061 ms.
Result count 1, range 1061 ms to  1061 ms.

sendList : 100% : 4531 ms, 99% : 4531 ms, 95 : 4531 ms, 90% : 4531 ms.
Average data rate: 0.024 MB/s

Result count 9, range 3741 ms to  4531 ms.
sendList failed peers count : 3 [25 %]

- Peer ID : Apple-Iphone6-1_PT4820.GNbylA==, Tried : 5
- Peer ID : Apple-Iphone6-1_PT4820.GNbylA==, Tried : 5
- Peer ID : Apple-Iphone6-1_PT4820.GNbylA==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5s-1_PT7515 --------------------- : 2
peersList : 100% : 349 ms, 99% : 349 ms, 95 : 349 ms, 90% : 349 ms.

Result count 1, range 349 ms to  349 ms.
sendList : 100% : 5590 ms, 99% : 5590 ms, 95 : 5590 ms, 90% : 5590 ms.

Average data rate: 0.023 MB/s
Result count 9, range 3494 ms to  5590 ms.
sendList failed peers count : 3 [25 %]

- Peer ID : Apple-IpadAir2-1_PT3239.C7DKtQ==, Tried : 5
- Peer ID : Apple-IpadAir2-1_PT3239.C7DKtQ==, Tried : 5
- Peer ID : Apple-IpadAir2-1_PT3239.C7DKtQ==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone6-1_PT4820 --------------------- : 3
peersList : 100% : 1124 ms, 99% : 1124 ms, 95 : 1124 ms, 90% : 1124 ms.

Result count 1, range 1124 ms to  1124 ms.
sendList : 100% : 44544 ms, 99% : 44544 ms, 95 : 44544 ms, 90% : 44544 ms.
Average data rate: 0.005 MB/s

Result count 9, range 4204 ms to  44544 ms.
sendList failed peers count : 3 [25 %]
- Peer ID : Apple-Iphone6-1_PT4820.GNbylA==, Tried : 5

- Peer ID : Apple-Iphone6-1_PT4820.GNbylA==, Tried : 5
- Peer ID : Apple-Iphone6-1_PT4820.GNbylA==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Apple-IpadAir2-1_PT3239 --------------------- : 4
peersList : 100% : 1276 ms, 99% : 1276 ms, 95 : 1276 ms, 90% : 1276 ms.
Result count 1, range 1276 ms to  1276 ms.

sendList : 100% : 4498 ms, 99% : 4498 ms, 95 : 4498 ms, 90% : 4498 ms.
Average data rate: 0.024 MB/s
Result count 9, range 3986 ms to  4498 ms.

sendList failed peers count : 3 [25 %]
- Peer ID : Apple-Iphone6-1_PT4820.GNbylA==, Tried : 5
- Peer ID : Apple-Iphone6-1_PT4820.GNbylA==, Tried : 5

- Peer ID : Apple-Iphone6-1_PT4820.GNbylA==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- motorola-XT1072_PT4505 --------------------- : 5

peersList : 100% : 3273 ms, 99% : 3273 ms, 95 : 3273 ms, 90% : 3273 ms.

Result count 1, range 3273 ms to  3273 ms.

sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.

Average data rate: NaN MB/s
Results list does not contain any items

--------------- samsung-SM-G900F_PT6440 --------------------- : 6

peersList : 100% : 3873 ms, 99% : 3873 ms, 95 : 3873 ms, 90% : 3873 ms.
Result count 1, range 3873 ms to  3873 ms.

sendList : 100% : 11260 ms, 99% : 11260 ms, 95 : 11260 ms, 90% : 11260 ms.

Average data rate: 0.016 MB/s
Result count 3, range 3209 ms to  11260 ms.

sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- samsung-SM-A500FU_PT3690 --------------------- : 7

peersList : 100% : 2686 ms, 99% : 2686 ms, 95 : 2686 ms, 90% : 2686 ms.
Result count 1, range 2686 ms to  2686 ms.
sendList : 100% : 4153 ms, 99% : 4153 ms, 95 : 4153 ms, 90% : 4153 ms.
Average data rate: 0.027 MB/s
Result count 4, range 3183 ms to  4153 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- LGE-LG-D722_PT1779 --------------------- : 8
peersList : 100% : 15335 ms, 99% : 15335 ms, 95 : 15335 ms, 90% : 15335 ms.
Result count 1, range 15335 ms to  15335 ms.
sendList : 100% : 4759 ms, 99% : 4759 ms, 95 : 4759 ms, 90% : 4759 ms.
Average data rate: 0.026 MB/s
Result count 3, range 2768 ms to  4759 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-A300FU_PT818 --------------------- : 9
peersList : 100% : 3165 ms, 99% : 3165 ms, 95 : 3165 ms, 90% : 3165 ms.
Result count 1, range 3165 ms to  3165 ms.
sendList : 100% : 8169 ms, 99% : 8169 ms, 95 : 8169 ms, 90% : 8169 ms.
Average data rate: 0.024 MB/s
Result count 4, range 1520 ms to  8169 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- LGE-LG-D855_PT2787 --------------------- : 10
peersList : 100% : 2074 ms, 99% : 2074 ms, 95 : 2074 ms, 90% : 2074 ms.
Result count 1, range 2074 ms to  2074 ms.
sendList : 100% : 6157 ms, 99% : 6157 ms, 95 : 6157 ms, 90% : 6157 ms.
Average data rate: 0.022 MB/s
Result count 5, range 2460 ms to  6157 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- HTC-HTC One M8s_PT8357 --------------------- : 11
peersList : 100% : 3229 ms, 99% : 3229 ms, 95 : 3229 ms, 90% : 3229 ms.
Result count 1, range 3229 ms to  3229 ms.
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
--------------- samsung-SM-N910C_PT706 --------------------- : 12
peersList : 100% : 41194 ms, 99% : 41194 ms, 95 : 41194 ms, 90% : 41194 ms.
Result count 1, range 41194 ms to  41194 ms.
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
--------------- samsung-SM-A500FU_PT9197 --------------------- : 13
peersList : 100% : 4453 ms, 99% : 4453 ms, 95 : 4453 ms, 90% : 4453 ms.
Result count 1, range 4453 ms to  4453 ms.
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
--------------- samsung-SM-A300FU_PT6753 --------------------- : 14
peersList : 100% : 3128 ms, 99% : 3128 ms, 95 : 3128 ms, 90% : 3128 ms.
Result count 1, range 3128 ms to  3128 ms.
sendList : 100% : 4301 ms, 99% : 4301 ms, 95 : 4301 ms, 90% : 4301 ms.
Average data rate: 0.023 MB/s
Result count 1, range 4301 ms to  4301 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- LGE-LG-H815_PT177 --------------------- : 15
peersList : 100% : 3849 ms, 99% : 3849 ms, 95 : 3849 ms, 90% : 3849 ms.
Result count 1, range 3849 ms to  3849 ms.
sendList : 100% : 8255 ms, 99% : 8255 ms, 95 : 8255 ms, 90% : 8255 ms.

Average data rate: 0.012 MB/s
Result count 1, range 8255 ms to  8255 ms.
sendList failed peers count : 0 [0 %]

sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-G900F_PT6172 --------------------- : 16

peersList : 100% : 5273 ms, 99% : 5273 ms, 95 : 5273 ms, 90% : 5273 ms.
Result count 1, range 5273 ms to  5273 ms.

sendList : 100% : 5354 ms, 99% : 5354 ms, 95 : 5354 ms, 90% : 5354 ms.

Average data rate: 0.019 MB/s
Result count 1, range 5354 ms to  5354 ms.

sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- LGE-Nexus 5_PT9383 --------------------- : 17

peersList : 100% : 4782 ms, 99% : 4782 ms, 95 : 4782 ms, 90% : 4782 ms.
Result count 1, range 4782 ms to  4782 ms.

sendList : 100% : 6957 ms, 99% : 6957 ms, 95 : 6957 ms, 90% : 6957 ms.
Average data rate: 0.019 MB/s

Result count 2, range 3542 ms to  6957 ms.

sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- Combined ---------------------

peersList : 100% : 41194 ms, 99% : 41194 ms, 95 : 15335 ms, 90% : 5273 ms.

sendList : 100% : 44544 ms, 99% : 44544 ms, 95 : 11260 ms, 90% : 7232 ms.

Average data rate: 0.015 MB/s
--------------- end of test report ---------------------

2016-01-05T00:49:23.806Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1_PT4820.GNbylA==, peerAvailable=true, time=1061], sendList=[name=Apple-Iphone5s-1_PT7515.viE/5Q==, time=3741, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1_PT4002"]["sendList"][0], $ref=$["Apple-Iphone5-1_PT4002"]["sendList"][0], name=Apple-Iphone6-1_PT4820.TWfskw==, time=4374, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1_PT4002"]["sendList"][3], $ref=$["Apple-Iphone5-1_PT4002"]["sendList"][3], name=Apple-IpadAir2-1_PT3239.85RfWg==, time=4531, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5-1_PT4002"]["sendList"][6], $ref=$["Apple-Iphone5-1_PT4002"]["sendList"][6]], failedPeer=[name=Apple-Iphone6-1_PT4820.GNbylA==, time=40440, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone5-1_PT4002"]["sendError"]["failedPeer"][0], $ref=$["Apple-Iphone5-1_PT4002"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1_PT4820.GNbylA==, peerAvailable=true, time=349], sendList=[name=Apple-Iphone5-1_PT4002.r/utkA==, time=3494, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1_PT7515"]["sendList"][0], $ref=$["Apple-Iphone5s-1_PT7515"]["sendList"][0], name=Apple-Iphone6-1_PT4820.TWfskw==, time=3863, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1_PT7515"]["sendList"][3], $ref=$["Apple-Iphone5s-1_PT7515"]["sendList"][3], name=Apple-IpadAir2-1_PT3239.85RfWg==, time=5590, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone5s-1_PT7515"]["sendList"][6], $ref=$["Apple-Iphone5s-1_PT7515"]["sendList"][6]], failedPeer=[name=Apple-IpadAir2-1_PT3239.C7DKtQ==, time=40752, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone5s-1_PT7515"]["sendError"]["failedPeer"][0], $ref=$["Apple-Iphone5s-1_PT7515"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1_PT4002.tre7Iw==, peerAvailable=true, time=1124], sendList=[name=Apple-Iphone5s-1_PT7515.viE/5Q==, time=4204, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1_PT4820"]["sendList"][0], $ref=$["Apple-Iphone6-1_PT4820"]["sendList"][0], name=Apple-Iphone5-1_PT4002.r/utkA==, time=7232, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1_PT4820"]["sendList"][3], $ref=$["Apple-Iphone6-1_PT4820"]["sendList"][3], name=Apple-IpadAir2-1_PT3239.85RfWg==, time=44544, result=OK, connections=5, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-Iphone6-1_PT4820"]["sendList"][6], $ref=$["Apple-Iphone6-1_PT4820"]["sendList"][6]], failedPeer=[name=Apple-Iphone6-1_PT4820.GNbylA==, time=42090, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-Iphone6-1_PT4820"]["sendError"]["failedPeer"][0], $ref=$["Apple-Iphone6-1_PT4820"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1_PT4820.GNbylA==, peerAvailable=true, time=1276], sendList=[name=Apple-Iphone5-1_PT4002.r/utkA==, time=3986, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1_PT3239"]["sendList"][0], $ref=$["Apple-IpadAir2-1_PT3239"]["sendList"][0], name=Apple-Iphone5s-1_PT7515.viE/5Q==, time=4061, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1_PT3239"]["sendList"][3], $ref=$["Apple-IpadAir2-1_PT3239"]["sendList"][3], name=Apple-Iphone6-1_PT4820.TWfskw==, time=4498, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, $ref=$["Apple-IpadAir2-1_PT3239"]["sendList"][6], $ref=$["Apple-IpadAir2-1_PT3239"]["sendList"][6]], failedPeer=[name=Apple-Iphone6-1_PT4820.GNbylA==, time=42446, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, $ref=$["Apple-IpadAir2-1_PT3239"]["sendError"]["failedPeer"][0], $ref=$["Apple-IpadAir2-1_PT3239"]["sendError"]["failedPeer"][0]], notTriedList=[], peersList=[peerName=samsung-SM-A300FU_PT818, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=3273], sendList=[], failedPeer=[], notTriedList=[], peersList=[peerName=samsung-SM-A300FU_PT818, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=3873], sendList=[name=34:FC:EF:11:AE:67, time=3209, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:37:96:AB, time=4237, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=58:3F:54:73:64:C0, time=11260, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], peersList=[peerName=LGE-LG-D722_PT1779, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=2686], sendList=[name=90:E7:C4:F6:69:77, time=3183, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=34:FC:EF:11:AE:67, time=3604, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=44:80:EB:7B:5A:05, time=4079, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=08:EC:A9:50:75:41, time=4153, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], peersList=[peerName=samsung-SM-G900F_PT6440, peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=15335], sendList=[name=58:3F:54:73:64:C0, time=2768, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=08:EC:A9:50:75:41, time=3978, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=F8:95:C7:87:3C:51, time=4759, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], peersList=[peerName=LGE-Nexus 5_PT9383, peerIdentifier=34:FC:EF:11:AE:67, peerAvailable=true, time=3165], sendList=[name=7C:F9:0E:51:18:22, time=1520, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=44:80:EB:7B:5A:05, time=2983, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:37:96:AB, time=3720, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=F8:95:C7:87:85:54, time=8169, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], peersList=[peerName=samsung-SM-A300FU_PT6753, peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=2074], sendList=[name=44:80:EB:7B:5A:05, time=2460, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:37:96:AB, time=2648, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:51:18:22, time=5306, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=08:EC:A9:50:75:41, time=5851, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=B0:C5:59:3F:75:69, time=6157, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], peersList=[peerName=samsung-SM-A300FU_PT818, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=3229], sendList=[], failedPeer=[], notTriedList=[], peersList=[peerName=samsung-SM-A300FU_PT818, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=41194], sendList=[], failedPeer=[], notTriedList=[], peersList=[peerName=LGE-LG-D722_PT1779, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=4453], sendList=[], failedPeer=[], notTriedList=[], peersList=[peerName=samsung-SM-A300FU_PT818, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=3128], sendList=[name=F8:95:C7:87:3C:51, time=4301, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], peersList=[peerName=HTC-HTC One M8s_PT8357, peerIdentifier=90:E7:C4:F6:69:77, peerAvailable=true, time=3849], sendList=[name=08:EC:A9:50:75:41, time=8255, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], peersList=[peerName=LGE-LG-D855_PT2787, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=5273], sendList=[name=08:EC:A9:50:76:27, time=5354, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], peersList=[peerName=samsung-SM-A300FU_PT6753, peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=4782], sendList=[name=7C:F9:0E:51:18:22, time=3542, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=B0:C5:59:3F:75:69, time=6957, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[]

2016-01-05T00:49:23.828Z - debug: end to motorola-XT1072_PT4505

2016-01-05T00:49:23.830Z - debug: end to samsung-SM-G900F_PT6440

2016-01-05T00:49:23.833Z - debug: end to samsung-SM-A500FU_PT3690

2016-01-05T00:49:23.834Z - debug: end to LGE-LG-D722_PT1779

2016-01-05T00:49:23.835Z - debug: end to samsung-SM-A300FU_PT818

2016-01-05T00:49:23.837Z - debug: end to LGE-LG-D855_PT2787

2016-01-05T00:49:23.838Z - debug: end to HTC-HTC One M8s_PT8357

2016-01-05T00:49:23.839Z - debug: end to samsung-SM-N910C_PT706

2016-01-05T00:49:23.840Z - debug: end to samsung-SM-A500FU_PT9197

2016-01-05T00:49:23.842Z - debug: end to samsung-SM-A300FU_PT6753

2016-01-05T00:49:23.843Z - debug: end to LGE-LG-H815_PT177

2016-01-05T00:49:23.844Z - debug: end to samsung-SM-G900F_PT6172

2016-01-05T00:49:23.845Z - debug: end to LGE-Nexus 5_PT9383

2016-01-05T00:49:23.847Z - debug: end to samsung-SM-G800F_PT2118

2016-01-05T00:49:24.589Z - debug: Socket disconnected: transport close 16 (LGE-Nexus 5_PT9383)

2016-01-05T00:49:24.821Z - debug: Socket disconnected: transport close 13 (LGE-LG-H815_PT177)

2016-01-05T00:49:24.882Z - debug: Socket disconnected: transport close 10 (samsung-SM-N910C_PT706)

2016-01-05T00:49:24.932Z - debug: Socket disconnected: transport close 11 (samsung-SM-A500FU_PT9197)

2016-01-05T00:49:24.961Z - debug: Socket disconnected: transport close 8 (HTC-HTC One M8s_PT8357)

2016-01-05T00:49:25.057Z - debug: Socket disconnected: transport close 4 (samsung-SM-G900F_PT6440)

2016-01-05T00:49:25.159Z - debug: Socket disconnected: transport close 18 (motorola-XT1072_PT4505)

2016-01-05T00:49:25.290Z - debug: Socket disconnected: transport close 5 (samsung-SM-A500FU_PT3690)

2016-01-05T00:49:25.474Z - debug: Socket disconnected: transport close 6 (LGE-LG-D722_PT1779)

2016-01-05T00:49:26.089Z - debug: Socket disconnected: transport close 12 (samsung-SM-A300FU_PT6753)

2016-01-05T00:49:26.784Z - debug: Socket disconnected: transport close 14 (samsung-SM-G900F_PT6172)

2016-01-05T00:49:27.778Z - debug: Socket disconnected: transport close 7 (samsung-SM-A300FU_PT818)

2016-01-05T00:49:45.810Z - debug: Socket disconnected: transport close 9 (LGE-LG-D855_PT2787)

2016-01-05T00:50:15.027Z - debug: Socket disconnected: ping timeout 2 (motorola-XT1072_PT4505)


 
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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/54968200254eab2_Correct_syntax_error_and_ensure_they_can_t_screw_things_up_again_tobybrad/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/54968200254eab2_Correct_syntax_error_and_ensure_they_can_t_screw_things_up_again_tobybrad/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/54968200254eab2_Correct_syntax_error_and_ensure_they_can_t_screw_things_up_again_tobybrad/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/54968200254eab2_Correct_syntax_error_and_ensure_they_can_t_screw_things_up_again_tobybrad/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/54968200254eab2_Correct_syntax_error_and_ensure_they_can_t_screw_things_up_again_tobybrad/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/54968200254eab2_Correct_syntax_error_and_ensure_they_can_t_screw_things_up_again_tobybrad/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/54968200254eab2_Correct_syntax_error_and_ensure_they_can_t_screw_things_up_again_tobybrad/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
STOP log received from  0be0c6c6 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Device test finished on ZX1C223JKW 
Device test finished on 0be0c6c6 
Android task is completed. [SUCCESS]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/54968200254eab2_Correct_syntax_error_and_ensure_they_can_t_screw_things_up_again_tobybrad/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/54968200254eab2_Correct_syntax_error_and_ensure_they_can_t_screw_things_up_again_tobybrad/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/54968200254eab2_Correct_syntax_error_and_ensure_they_can_t_screw_things_up_again_tobybrad/thali04_samsung-SM-G900F.md)

####Node name: thali06
Console output:
```
STOP log received from  FA55PYS00566 Test has  SUCCEEDED
Device test finished on FA55PYS00566 
STOP log received from  7970f88c Test has  SUCCEEDED
Device test finished on 7970f88c 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:0 
child process exited with code 0 on device 022678fb504e29b0 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/54968200254eab2_Correct_syntax_error_and_ensure_they_can_t_screw_things_up_again_tobybrad/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/54968200254eab2_Correct_syntax_error_and_ensure_they_can_t_screw_things_up_again_tobybrad/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/54968200254eab2_Correct_syntax_error_and_ensure_they_can_t_screw_things_up_again_tobybrad/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
STOP log received from  c5afcdcb Test has  SUCCEEDED
STOP log received from  4db5c8cc Test has  SUCCEEDED
Device test finished on 4db5c8cc 
Device test finished on c5afcdcb 
Android task is completed. [SUCCESS]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/54968200254eab2_Correct_syntax_error_and_ensure_they_can_t_screw_things_up_again_tobybrad/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/54968200254eab2_Correct_syntax_error_and_ensure_they_can_t_screw_things_up_again_tobybrad/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/54968200254eab2_Correct_syntax_error_and_ensure_they_can_t_screw_things_up_again_tobybrad/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/54968200254eab2_Correct_syntax_error_and_ensure_they_can_t_screw_things_up_again_tobybrad/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/54968200254eab2_Correct_syntax_error_and_ensure_they_can_t_screw_things_up_again_tobybrad/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/54968200254eab2_Correct_syntax_error_and_ensure_they_can_t_screw_things_up_again_tobybrad/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/54968200254eab2_Correct_syntax_error_and_ensure_they_can_t_screw_things_up_again_tobybrad/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/54968200254eab2_Correct_syntax_error_and_ensure_they_can_t_screw_things_up_again_tobybrad/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/54968200254eab2_Correct_syntax_error_and_ensure_they_can_t_screw_things_up_again_tobybrad/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/54968200254eab2_Correct_syntax_error_and_ensure_they_can_t_screw_things_up_again_tobybrad/iOS_Iphone5s-1.md)



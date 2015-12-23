#### Test 54312298af2c956 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2015-12-23T02:11:56.112Z - info: listening on *:3000

2015-12-23T02:11:56.713Z - debug: Device presented: samsung-SM-A300FU_PT4270 (android) perftest socket:1

2015-12-23T02:11:56.720Z - info: Setting start timeout to: 120000 (android)

2015-12-23T02:11:56.755Z - debug: Device presented: Apple-IpadAir2-1_PT8230 (ios) perftest socket:0

2015-12-23T02:11:56.757Z - info: Setting start timeout to: 120000 (ios)

2015-12-23T02:11:56.761Z - debug: Device presented: motorola-XT1072_PT4998 (android) perftest socket:2

2015-12-23T02:11:56.765Z - debug: Device presented: samsung-SM-A500FU_PT1715 (android) perftest socket:3

2015-12-23T02:11:56.851Z - debug: Device presented: Apple-Iphone5-1_PT4216 (ios) perftest socket:4

2015-12-23T02:11:56.996Z - debug: Device presented: samsung-SM-G900F_PT6068 (android) perftest socket:5

2015-12-23T02:11:57.575Z - debug: Device presented: samsung-SM-A500FU_PT6430 (android) perftest socket:6

2015-12-23T02:11:57.853Z - debug: Device presented: Apple-Iphone6-1_PT6053 (ios) perftest socket:7

2015-12-23T02:11:58.091Z - debug: Device presented: samsung-SM-N910C_PT1003 (android) perftest socket:8

2015-12-23T02:11:58.822Z - debug: Device presented: LGE-Nexus 5_PT8145 (android) perftest socket:10

2015-12-23T02:11:58.839Z - debug: Device presented: LGE-LG-D722_PT6438 (android) perftest socket:9

2015-12-23T02:11:59.582Z - debug: Device presented: HTC-HTC One M8s_PT1694 (android) perftest socket:11

2015-12-23T02:11:59.823Z - debug: Device presented: Apple-Iphone5s-1_PT4021 (ios) perftest socket:12

2015-12-23T02:11:59.824Z - info: Required number of devices presented

2015-12-23T02:11:59.828Z - info: Starting perf test run for platform: ios

2015-12-23T02:11:59.829Z - info: Using devices:

2015-12-23T02:11:59.830Z - info: Apple-IpadAir2-1_PT8230

2015-12-23T02:11:59.832Z - info: Apple-Iphone5-1_PT4216

2015-12-23T02:11:59.833Z - info: Apple-Iphone6-1_PT6053

2015-12-23T02:11:59.834Z - info: Apple-Iphone5s-1_PT4021

2015-12-23T02:11:59.838Z - info: Starting test: with 4 devices (ios)

2015-12-23T02:11:59.853Z - debug: Device presented: samsung-SM-G900F_PT6545 (android) perftest socket:13

2015-12-23T02:12:00.038Z - debug: Device presented: LGE-LG-D855_PT3911 (android) perftest socket:14

2015-12-23T02:12:00.897Z - debug: Device presented: samsung-SM-A300FU_PT7770 (android) perftest socket:15

2015-12-23T02:12:00.997Z - debug: Device presented: LGE-LG-H815_PT7855 (android) perftest socket:16

2015-12-23T02:12:01.245Z - info: Received results for {"name:":"Apple-Iphone6-1_PT6053","time":1160,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-IpadAir2-1_PT8230.LvlR6w==","peerAvailable":true,"time":1158}]} Apple-Iphone6-1_PT6053 ios (4 left)

2015-12-23T02:12:01.473Z - info: Received results for {"name:":"Apple-IpadAir2-1_PT8230","time":1049,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone6-1_PT6053.eofveg==","peerAvailable":true,"time":1047}]} Apple-IpadAir2-1_PT8230 ios (3 left)

2015-12-23T02:12:01.898Z - info: Received results for {"name:":"Apple-Iphone5-1_PT4216","time":1750,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone6-1_PT6053.eofveg==","peerAvailable":true,"time":1749}]} Apple-Iphone5-1_PT4216 ios (2 left)

2015-12-23T02:12:02.191Z - info: Received results for {"name:":"Apple-Iphone5s-1_PT4021","time":1069,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone6-1_PT6053.eofveg==","peerAvailable":true,"time":1067}]} Apple-Iphone5s-1_PT4021 ios (1 left)

2015-12-23T02:12:02.195Z - info: All test data retrieved for testFindPeers.js (ios)

2015-12-23T02:12:02.202Z - info: Remaining tests: %s ios=[testSendData.js]

2015-12-23T02:12:02.206Z - info: Continuing to next test: testSendData.js
2015-12-23T02:12:02.207Z - info: Starting test: with 4 devices (ios)

2015-12-23T02:12:03.262Z - debug: Device presented: samsung-SM-G800F_PT6810 (android) perftest socket:17

2015-12-23T02:12:03.554Z - debug: Socket disconnected: transport close 17 (samsung-SM-G800F_PT6810)

2015-12-23T02:12:55.824Z - info: Received results for {"name:":"Apple-Iphone6-1_PT6053","time":53221,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT6053.eofveg==","time":40665,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-IpadAir2-1_PT8230.FlW6Iw==","time":4106,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT4021.SE3R7g==","time":3725,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT4216.OABFDg==","time":4121,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone6-1_PT6053 ios (4 left)

2015-12-23T02:12:56.428Z - info: Received results for {"name:":"Apple-IpadAir2-1_PT8230","time":53529,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT6053.eofveg==","time":41093,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-Iphone5s-1_PT4021.SE3R7g==","time":4182,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT4216.OABFDg==","time":4694,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1_PT6053.vUErSg==","time":3474,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-IpadAir2-1_PT8230 ios (3 left)

2015-12-23T02:12:57.036Z - info: Received results for {"name:":"Apple-Iphone5s-1_PT4021","time":54547,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT6053.eofveg==","time":40791,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-Iphone6-1_PT6053.vUErSg==","time":6175,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_PT8230.FlW6Iw==","time":3412,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT4216.OABFDg==","time":3462,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone5s-1_PT4021 ios (2 left)

2015-12-23T02:12:57.926Z - info: Received results for {"name:":"Apple-Iphone5-1_PT4216","time":53926,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT6053.vUErSg==","time":3649,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1_PT6053.eofveg==","time":40368,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-IpadAir2-1_PT8230.FlW6Iw==","time":4760,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT4021.SE3R7g==","time":3979,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone5-1_PT4216 ios (1 left)

2015-12-23T02:12:57.928Z - info: All test data retrieved for testSendData.js (ios)

2015-12-23T02:12:57.932Z - info: Remaining tests: %s ios=[]

2015-12-23T02:12:57.934Z - info: ALL DONE !!!

{ 'name:': 'Apple-IpadAir2-1_PT8230',
  time: 1049,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT6053.eofveg==',
       peerAvailable: true,
       time: 1047 } ] }

{ 'name:': 'Apple-Iphone5-1_PT4216',
  time: 1750,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT6053.eofveg==',
       peerAvailable: true,
       time: 1749 } ] }

{ 'name:': 'Apple-Iphone6-1_PT6053',
  time: 1160,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1_PT8230.LvlR6w==',
       peerAvailable: true,
       time: 1158 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT4021',
  time: 1069,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT6053.eofveg==',
       peerAvailable: true,
       time: 1067 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT8230',
  time: 53529,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT6053.eofveg==',
       time: 41093,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1_PT4021.SE3R7g==',
       time: 4182,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT4216.OABFDg==',
       time: 4694,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT6053.vUErSg==',
       time: 3474,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1_PT4216',
  time: 53926,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT6053.vUErSg==',
       time: 3649,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT6053.eofveg==',
       time: 40368,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT8230.FlW6Iw==',
       time: 4760,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT4021.SE3R7g==',
       time: 3979,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1_PT6053',
  time: 53221,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT6053.eofveg==',
       time: 40665,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT8230.FlW6Iw==',
       time: 4106,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT4021.SE3R7g==',
       time: 3725,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT4216.OABFDg==',
       time: 4121,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT4021',
  time: 54547,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT6053.eofveg==',
       time: 40791,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT6053.vUErSg==',
       time: 6175,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT8230.FlW6Iw==',
       time: 3412,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT4216.OABFDg==',
       time: 3462,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

--------------- test report ---------------------
--------------- Apple-IpadAir2-1_PT8230 --------------------- : 1

peersList : 100% : 1047 ms, 99% : 1047 ms, 95 : 1047 ms, 90% : 1047 ms.

Result count 1, range 1047 ms to  1047 ms.

sendList : 100% : 4694 ms, 99% : 4694 ms, 95 : 4694 ms, 90% : 4694 ms.

Average data rate: 0.024 MB/s

Result count 3, range 3474 ms to  4694 ms.

sendList failed peers count : 1 [25 %]

- Peer ID : Apple-Iphone6-1_PT6053.eofveg==, Tried : 5

sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5-1_PT4216 --------------------- : 2

peersList : 100% : 1749 ms, 99% : 1749 ms, 95 : 1749 ms, 90% : 1749 ms.
Result count 1, range 1749 ms to  1749 ms.

sendList : 100% : 4760 ms, 99% : 4760 ms, 95 : 4760 ms, 90% : 4760 ms.
Average data rate: 0.024 MB/s

Result count 3, range 3649 ms to  4760 ms.
sendList failed peers count : 1 [25 %]

- Peer ID : Apple-Iphone6-1_PT6053.eofveg==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone6-1_PT6053 --------------------- : 3
peersList : 100% : 1158 ms, 99% : 1158 ms, 95 : 1158 ms, 90% : 1158 ms.
Result count 1, range 1158 ms to  1158 ms.

sendList : 100% : 4121 ms, 99% : 4121 ms, 95 : 4121 ms, 90% : 4121 ms.
Average data rate: 0.025 MB/s
Result count 3, range 3725 ms to  4121 ms.

sendList failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone6-1_PT6053.eofveg==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5s-1_PT4021 --------------------- : 4
peersList : 100% : 1067 ms, 99% : 1067 ms, 95 : 1067 ms, 90% : 1067 ms.
Result count 1, range 1067 ms to  1067 ms.

sendList : 100% : 6175 ms, 99% : 6175 ms, 95 : 6175 ms, 90% : 6175 ms.
Average data rate: 0.023 MB/s

Result count 3, range 3412 ms to  6175 ms.
sendList failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone6-1_PT6053.eofveg==, Tried : 5

sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------

peersList : 100% : 1749 ms, 99% : 1749 ms, 95 : 1749 ms, 90% : 1749 ms.

sendList : 100% : 6175 ms, 99% : 6175 ms, 95 : 4760 ms, 90% : 4760 ms.

Average data rate: 0.024 MB/s
--------------- end of test report ---------------------

2015-12-23T02:12:58.064Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1_PT6053.eofveg==, peerAvailable=true, time=1047], sendList=[name=Apple-Iphone6-1_PT6053.vUErSg==, time=3474, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5s-1_PT4021.SE3R7g==, time=4182, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1_PT4216.OABFDg==, time=4694, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone6-1_PT6053.eofveg==, time=41093, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1_PT6053.eofveg==, peerAvailable=true, time=1749], sendList=[name=Apple-Iphone6-1_PT6053.vUErSg==, time=3649, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5s-1_PT4021.SE3R7g==, time=3979, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1_PT8230.FlW6Iw==, time=4760, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone6-1_PT6053.eofveg==, time=40368, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1_PT8230.LvlR6w==, peerAvailable=true, time=1158], sendList=[name=Apple-Iphone5s-1_PT4021.SE3R7g==, time=3725, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1_PT8230.FlW6Iw==, time=4106, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1_PT4216.OABFDg==, time=4121, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone6-1_PT6053.eofveg==, time=40665, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1_PT6053.eofveg==, peerAvailable=true, time=1067], sendList=[name=Apple-IpadAir2-1_PT8230.FlW6Iw==, time=3412, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1_PT4216.OABFDg==, time=3462, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone6-1_PT6053.vUErSg==, time=6175, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone6-1_PT6053.eofveg==, time=40791, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[]

2015-12-23T02:13:01.126Z - debug: Socket disconnected: transport close 0 (Apple-IpadAir2-1_PT8230)

2015-12-23T02:13:01.198Z - debug: Socket disconnected: transport close 12 (Apple-Iphone5s-1_PT4021)

2015-12-23T02:13:01.463Z - debug: Socket disconnected: transport close 7 (Apple-Iphone6-1_PT6053)

2015-12-23T02:13:01.976Z - debug: state: android waiting

2015-12-23T02:13:01.977Z - debug: state: ios completed

2015-12-23T02:13:04.668Z - debug: Socket disconnected: transport close 4 (Apple-Iphone5-1_PT4216)

2015-12-23T02:13:56.731Z - info: Start timeout elapsed for platform: android

2015-12-23T02:13:56.733Z - info: Starting perf test run for platform: android

2015-12-23T02:13:56.734Z - info: Using devices:

2015-12-23T02:13:56.735Z - info: samsung-SM-A300FU_PT4270

2015-12-23T02:13:56.736Z - info: motorola-XT1072_PT4998

2015-12-23T02:13:56.738Z - info: samsung-SM-A500FU_PT1715

2015-12-23T02:13:56.739Z - info: samsung-SM-G900F_PT6068

2015-12-23T02:13:56.741Z - info: samsung-SM-A500FU_PT6430

2015-12-23T02:13:56.742Z - info: samsung-SM-N910C_PT1003

2015-12-23T02:13:56.743Z - info: LGE-Nexus 5_PT8145

2015-12-23T02:13:56.744Z - info: LGE-LG-D722_PT6438

2015-12-23T02:13:56.746Z - info: HTC-HTC One M8s_PT1694

2015-12-23T02:13:56.746Z - info: samsung-SM-G900F_PT6545

2015-12-23T02:13:56.748Z - info: LGE-LG-D855_PT3911

2015-12-23T02:13:56.749Z - info: samsung-SM-A300FU_PT7770

2015-12-23T02:13:56.750Z - info: LGE-LG-H815_PT7855

2015-12-23T02:13:56.751Z - info: samsung-SM-G800F_PT6810

2015-12-23T02:13:56.752Z - info: Starting test: with 14 devices (android)

2015-12-23T02:13:59.564Z - info: Received results for {"name:":"samsung-SM-A300FU_PT7770","time":2247,"result":"OK","peersList":[{"peerName":"LGE-LG-D722_PT6438","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":2246}]} samsung-SM-A300FU_PT7770 android (14 left)

2015-12-23T02:13:59.697Z - info: Received results for {"name:":"samsung-SM-A300FU_PT4270","time":2576,"result":"OK","peersList":[{"peerName":"LGE-LG-D855_PT3911","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":2575}]} samsung-SM-A300FU_PT4270 android (13 left)

2015-12-23T02:13:59.939Z - info: Received results for {"name:":"motorola-XT1072_PT4998","time":2807,"result":"OK","peersList":[{"peerName":"LGE-Nexus 5_PT8145","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":true,"time":2806}]} motorola-XT1072_PT4998 android (12 left)

2015-12-23T02:14:00.003Z - info: Received results for {"name:":"samsung-SM-A500FU_PT6430","time":2853,"result":"OK","peersList":[{"peerName":"samsung-SM-G900F_PT6068","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":2852}]} samsung-SM-A500FU_PT6430 android (11 left)

2015-12-23T02:14:00.785Z - info: Received results for {"name:":"HTC-HTC One M8s_PT1694","time":3851,"result":"OK","peersList":[{"peerName":"LGE-LG-H815_PT7855","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":3849}]} HTC-HTC One M8s_PT1694 android (10 left)

2015-12-23T02:14:01.812Z - info: Received results for {"name:":"LGE-Nexus 5_PT8145","time":4454,"result":"OK","peersList":[{"peerName":"samsung-SM-A500FU_PT6430","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":4445}]} LGE-Nexus 5_PT8145 android (9 left)

2015-12-23T02:14:01.884Z - info: Received results for {"name:":"LGE-LG-D722_PT6438","time":4188,"result":"OK","peersList":[{"peerName":"samsung-SM-A300FU_PT7770","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":4186}]} LGE-LG-D722_PT6438 android (8 left)

2015-12-23T02:14:02.139Z - info: Received results for {"name:":"samsung-SM-N910C_PT1003","time":4617,"result":"OK","peersList":[{"peerName":"LGE-LG-D722_PT6438","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true,"time":4614}]} samsung-SM-N910C_PT1003 android (7 left)

2015-12-23T02:14:03.013Z - info: Received results for {"name:":"samsung-SM-G900F_PT6068","time":4425,"result":"OK","peersList":[{"peerName":"samsung-SM-A300FU_PT7770","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":4423}]} samsung-SM-G900F_PT6068 android (6 left)

2015-12-23T02:14:05.965Z - info: Received results for {"name:":"LGE-LG-D855_PT3911","time":3016,"result":"OK","peersList":[{"peerName":"samsung-SM-A500FU_PT6430","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":3015}]} LGE-LG-D855_PT3911 android (5 left)

2015-12-23T02:14:06.162Z - info: Received results for {"name:":"samsung-SM-A500FU_PT1715","time":9032,"result":"OK","peersList":[{"peerName":"samsung-SM-A300FU_PT7770","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":9030}]} samsung-SM-A500FU_PT1715 android (4 left)

2015-12-23T02:14:09.424Z - info: Received results for {"name:":"LGE-LG-H815_PT7855","time":12099,"result":"OK","peersList":[{"peerName":"motorola-XT1072_PT4998","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true,"time":12097}]} LGE-LG-H815_PT7855 android (3 left)

2015-12-23T02:14:12.085Z - info: Received results for {"name:":"samsung-SM-G900F_PT6545","time":14736,"result":"OK","peersList":[{"peerName":"samsung-SM-G900F_PT6068","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":14729}]} samsung-SM-G900F_PT6545 android (2 left)

2015-12-23T02:15:45.354Z - debug: Device presented: motorola-XT1072_PT4998 (android) perftest socket:18

2015-12-23T02:15:45.355Z - info: Updating existing device: motorola-XT1072_PT4998 (822d16e2-3438-4fb3-9083-2cc2f0c8be6f)

2015-12-23T02:15:56.760Z - info: server timeout for test: testFindPeers.js (android)

2015-12-23T02:15:56.761Z - info: All test data retrieved for testFindPeers.js (android)

2015-12-23T02:15:56.778Z - info: No results from samsung-SM-G800F_PT6810

2015-12-23T02:15:56.780Z - info: Remaining tests: %s ios=[], android=[testSendData.js]
2015-12-23T02:15:56.782Z - info: Continuing to next test: testSendData.js
2015-12-23T02:15:56.784Z - info: Starting test: with 14 devices (android)

2015-12-23T02:16:49.725Z - debug: Socket disconnected: ping timeout 2 (motorola-XT1072_PT4998)

2015-12-23T02:17:37.032Z - info: Received results for {"name:":"LGE-Nexus 5_PT8145","time":100037,"result":"TIMEOUT","sendList":[{"name":"7C:F9:0E:37:96:AB","time":1349,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":4085,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} LGE-Nexus 5_PT8145 android (14 left)

2015-12-23T02:17:37.076Z - info: Received results for {"name:":"LGE-LG-H815_PT7855","time":100035,"result":"TIMEOUT","sendList":[{"name":"E0:DB:10:14:E2:C0","time":2475,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":4487,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:75:41","time":7078,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":8621,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} LGE-LG-H815_PT7855 android (13 left)

2015-12-23T02:17:37.127Z - info: Received results for {"name:":"samsung-SM-A300FU_PT7770","time":100055,"result":"TIMEOUT","sendList":[]} samsung-SM-A300FU_PT7770 android (12 left)

2015-12-23T02:17:37.132Z - info: Received results for {"name:":"samsung-SM-A300FU_PT4270","time":100060,"result":"TIMEOUT","sendList":[{"name":"44:80:EB:7B:5A:05","time":3880,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":6835,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":2637,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} samsung-SM-A300FU_PT4270 android (11 left)

2015-12-23T02:17:37.183Z - info: Received results for {"name:":"samsung-SM-N910C_PT1003","time":100067,"result":"TIMEOUT","sendList":[{"name":"7C:F9:0E:37:96:AB","time":6255,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} samsung-SM-N910C_PT1003 android (10 left)

2015-12-23T02:17:37.216Z - info: Received results for {"name:":"motorola-XT1072_PT4998","time":100080,"result":"TIMEOUT","sendList":[{"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"}]} motorola-XT1072_PT4998 android (9 left)

2015-12-23T02:17:37.271Z - info: Received results for {"name:":"samsung-SM-G900F_PT6068","time":100065,"result":"TIMEOUT","sendList":[{"name":"34:FC:EF:11:AE:67","time":6719,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":1695,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"44:80:EB:7B:5A:05","time":6397,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:75:41","time":9558,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"}]} samsung-SM-G900F_PT6068 android (8 left)

2015-12-23T02:17:37.295Z - info: Received results for {"name:":"samsung-SM-G900F_PT6545","time":100071,"result":"TIMEOUT","sendList":[{"name":"7C:F9:0E:51:18:22","time":5657,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":2487,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} samsung-SM-G900F_PT6545 android (7 left)

2015-12-23T02:17:37.578Z - info: Received results for {"name:":"LGE-LG-D722_PT6438","time":100087,"result":"TIMEOUT","sendList":[{"name":"90:E7:C4:F6:69:77","time":4244,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:75:41","time":7531,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"}]} LGE-LG-D722_PT6438 android (6 left)

2015-12-23T02:17:37.929Z - info: Received results for {"name:":"samsung-SM-A500FU_PT1715","time":100059,"result":"TIMEOUT","sendList":[{"name":"08:EC:A9:50:75:41","time":4987,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} samsung-SM-A500FU_PT1715 android (5 left)

2015-12-23T02:17:37.959Z - info: Received results for {"name:":"samsung-SM-A500FU_PT6430","time":100051,"result":"TIMEOUT","sendList":[{"name":"08:EC:A9:50:75:41","time":6290,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"34:FC:EF:11:AE:67","time":2787,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":2579,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} samsung-SM-A500FU_PT6430 android (4 left)

2015-12-23T02:17:39.482Z - info: Received results for {"name:":"LGE-LG-D855_PT3911","time":100080,"result":"TIMEOUT","sendList":[{"name":"08:EC:A9:50:75:41","time":4230,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":3096,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"}]} LGE-LG-D855_PT3911 android (3 left)

2015-12-23T02:17:56.788Z - info: server timeout for test: testSendData.js (android)

2015-12-23T02:17:56.789Z - info: All test data retrieved for testSendData.js (android)

2015-12-23T02:17:56.796Z - info: No results from HTC-HTC One M8s_PT1694

2015-12-23T02:17:56.801Z - info: No results from samsung-SM-G800F_PT6810

2015-12-23T02:17:56.802Z - info: Remaining tests: %s ios=[], android=[]

2015-12-23T02:17:56.803Z - info: ALL DONE !!!
{ 'name:': 'Apple-IpadAir2-1_PT8230',
  time: 1049,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT6053.eofveg==',
       peerAvailable: true,
       time: 1047 } ] }

{ 'name:': 'Apple-Iphone5-1_PT4216',
  time: 1750,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT6053.eofveg==',
       peerAvailable: true,
       time: 1749 } ] }

{ 'name:': 'Apple-Iphone6-1_PT6053',
  time: 1160,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1_PT8230.LvlR6w==',
       peerAvailable: true,
       time: 1158 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT4021',
  time: 1069,
  result: 'OK',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1_PT6053.eofveg==',
       peerAvailable: true,
       time: 1067 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT8230',
  time: 53529,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT6053.eofveg==',
       time: 41093,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone5s-1_PT4021.SE3R7g==',
       time: 4182,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT4216.OABFDg==',
       time: 4694,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT6053.vUErSg==',
       time: 3474,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5-1_PT4216',
  time: 53926,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT6053.vUErSg==',
       time: 3649,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT6053.eofveg==',
       time: 40368,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT8230.FlW6Iw==',
       time: 4760,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT4021.SE3R7g==',
       time: 3979,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone6-1_PT6053',
  time: 53221,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT6053.eofveg==',
       time: 40665,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-IpadAir2-1_PT8230.FlW6Iw==',
       time: 4106,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT4021.SE3R7g==',
       time: 3725,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT4216.OABFDg==',
       time: 4121,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-Iphone5s-1_PT4021',
  time: 54547,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT6053.eofveg==',
       time: 40791,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'Apple-Iphone6-1_PT6053.vUErSg==',
       time: 6175,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-IpadAir2-1_PT8230.FlW6Iw==',
       time: 3412,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5-1_PT4216.OABFDg==',
       time: 3462,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'samsung-SM-A300FU_PT4270',
  time: 2576,
  result: 'OK',
  peersList: 
   [ { peerName: 'LGE-LG-D855_PT3911',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 2575 } ] }

{ 'name:': 'motorola-XT1072_PT4998',
  time: 2807,
  result: 'OK',
  peersList: 
   [ { peerName: 'LGE-Nexus 5_PT8145',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 2806 } ] }

{ 'name:': 'samsung-SM-A500FU_PT1715',
  time: 9032,
  result: 'OK',
  peersList: 
   [ { peerName: 'samsung-SM-A300FU_PT7770',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 9030 } ] }

{ 'name:': 'samsung-SM-G900F_PT6068',
  time: 4425,
  result: 'OK',
  peersList: 
   [ { peerName: 'samsung-SM-A300FU_PT7770',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 4423 } ] }

{ 'name:': 'samsung-SM-A500FU_PT6430',
  time: 2853,
  result: 'OK',
  peersList: 
   [ { peerName: 'samsung-SM-G900F_PT6068',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 2852 } ] }

{ 'name:': 'samsung-SM-N910C_PT1003',
  time: 4617,
  result: 'OK',
  peersList: 
   [ { peerName: 'LGE-LG-D722_PT6438',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 4614 } ] }

{ 'name:': 'LGE-Nexus 5_PT8145',
  time: 4454,
  result: 'OK',
  peersList: 
   [ { peerName: 'samsung-SM-A500FU_PT6430',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 4445 } ] }

{ 'name:': 'LGE-LG-D722_PT6438',
  time: 4188,
  result: 'OK',
  peersList: 
   [ { peerName: 'samsung-SM-A300FU_PT7770',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 4186 } ] }

{ 'name:': 'HTC-HTC One M8s_PT1694',
  time: 3851,
  result: 'OK',
  peersList: 
   [ { peerName: 'LGE-LG-H815_PT7855',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 3849 } ] }

{ 'name:': 'samsung-SM-G900F_PT6545',
  time: 14736,
  result: 'OK',
  peersList: 
   [ { peerName: 'samsung-SM-G900F_PT6068',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 14729 } ] }

{ 'name:': 'LGE-LG-D855_PT3911',
  time: 3016,
  result: 'OK',
  peersList: 
   [ { peerName: 'samsung-SM-A500FU_PT6430',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 3015 } ] }

{ 'name:': 'samsung-SM-A300FU_PT7770',
  time: 2247,
  result: 'OK',
  peersList: 
   [ { peerName: 'LGE-LG-D722_PT6438',
       peerIdentifier: 'F8:95:C7:87:85:54',
       peerAvailable: true,
       time: 2246 } ] }

{ 'name:': 'LGE-LG-H815_PT7855',
  time: 12099,
  result: 'OK',
  peersList: 
   [ { peerName: 'motorola-XT1072_PT4998',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 12097 } ] }

{ 'name:': 'samsung-SM-A300FU_PT4270',
  time: 100060,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '44:80:EB:7B:5A:05',
       time: 3880,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:85:54',
       time: 6835,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'B0:C5:59:3F:75:69',
       time: 2637,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'motorola-XT1072_PT4998',
  time: 100080,
  result: 'TIMEOUT',
  sendList: [ { name: 'F8:95:C7:87:85:54', time: 0, result: 'Fail' } ] }

{ 'name:': 'samsung-SM-A500FU_PT1715',
  time: 100059,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '08:EC:A9:50:75:41',
       time: 4987,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'samsung-SM-G900F_PT6068',
  time: 100065,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '34:FC:EF:11:AE:67',
       time: 6719,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:3C:51',
       time: 1695,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '44:80:EB:7B:5A:05',
       time: 6397,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '08:EC:A9:50:75:41',
       time: 9558,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '58:3F:54:73:64:C0', time: 0, result: 'Fail' } ] }

{ 'name:': 'samsung-SM-A500FU_PT6430',
  time: 100051,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '08:EC:A9:50:75:41',
       time: 6290,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '34:FC:EF:11:AE:67',
       time: 2787,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'E0:DB:10:14:E2:C0',
       time: 2579,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'samsung-SM-N910C_PT1003',
  time: 100067,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '7C:F9:0E:37:96:AB',
       time: 6255,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'LGE-Nexus 5_PT8145',
  time: 100037,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '7C:F9:0E:37:96:AB',
       time: 1349,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'B0:C5:59:3F:75:69',
       time: 4085,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'LGE-LG-D722_PT6438',
  time: 100087,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '90:E7:C4:F6:69:77',
       time: 4244,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '08:EC:A9:50:75:41',
       time: 7531,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '44:80:EB:7B:5A:05', time: 0, result: 'Fail' } ] }

{ 'name:': 'samsung-SM-G900F_PT6545',
  time: 100071,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '7C:F9:0E:51:18:22',
       time: 5657,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'E0:DB:10:14:E2:C0',
       time: 2487,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'LGE-LG-D855_PT3911',
  time: 100080,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '08:EC:A9:50:75:41',
       time: 4230,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'E0:DB:10:14:E2:C0',
       time: 3096,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '44:80:EB:7B:5A:05', time: 0, result: 'Fail' } ] }

{ 'name:': 'samsung-SM-A300FU_PT7770',
  time: 100055,
  result: 'TIMEOUT',
  sendList: [] }

{ 'name:': 'LGE-LG-H815_PT7855',
  time: 100035,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'E0:DB:10:14:E2:C0',
       time: 2475,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'B0:C5:59:3F:75:69',
       time: 4487,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '08:EC:A9:50:75:41',
       time: 7078,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:85:54',
       time: 8621,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

--------------- test report ---------------------
--------------- Apple-IpadAir2-1_PT8230 --------------------- : 1
peersList : 100% : 1047 ms, 99% : 1047 ms, 95 : 1047 ms, 90% : 1047 ms.

Result count 1, range 1047 ms to  1047 ms.
sendList : 100% : 4694 ms, 99% : 4694 ms, 95 : 4694 ms, 90% : 4694 ms.

Average data rate: 0.024 MB/s
Result count 3, range 3474 ms to  4694 ms.
sendList failed peers count : 1 [25 %]

- Peer ID : Apple-Iphone6-1_PT6053.eofveg==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5-1_PT4216 --------------------- : 2
peersList : 100% : 1749 ms, 99% : 1749 ms, 95 : 1749 ms, 90% : 1749 ms.
Result count 1, range 1749 ms to  1749 ms.

sendList : 100% : 4760 ms, 99% : 4760 ms, 95 : 4760 ms, 90% : 4760 ms.
Average data rate: 0.024 MB/s
Result count 3, range 3649 ms to  4760 ms.

sendList failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone6-1_PT6053.eofveg==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone6-1_PT6053 --------------------- : 3
peersList : 100% : 1158 ms, 99% : 1158 ms, 95 : 1158 ms, 90% : 1158 ms.
Result count 1, range 1158 ms to  1158 ms.

sendList : 100% : 4121 ms, 99% : 4121 ms, 95 : 4121 ms, 90% : 4121 ms.
Average data rate: 0.025 MB/s
Result count 3, range 3725 ms to  4121 ms.

sendList failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone6-1_PT6053.eofveg==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5s-1_PT4021 --------------------- : 4
peersList : 100% : 1067 ms, 99% : 1067 ms, 95 : 1067 ms, 90% : 1067 ms.
Result count 1, range 1067 ms to  1067 ms.
sendList : 100% : 6175 ms, 99% : 6175 ms, 95 : 6175 ms, 90% : 6175 ms.
Average data rate: 0.023 MB/s
Result count 3, range 3412 ms to  6175 ms.
sendList failed peers count : 1 [25 %]
- Peer ID : Apple-Iphone6-1_PT6053.eofveg==, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-A300FU_PT4270 --------------------- : 5
peersList : 100% : 2575 ms, 99% : 2575 ms, 95 : 2575 ms, 90% : 2575 ms.
Result count 1, range 2575 ms to  2575 ms.
sendList : 100% : 6835 ms, 99% : 6835 ms, 95 : 6835 ms, 90% : 6835 ms.
Average data rate: 0.022 MB/s
Result count 3, range 2637 ms to  6835 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- motorola-XT1072_PT4998 --------------------- : 6
peersList : 100% : 2806 ms, 99% : 2806 ms, 95 : 2806 ms, 90% : 2806 ms.
Result count 1, range 2806 ms to  2806 ms.
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
--------------- samsung-SM-A500FU_PT1715 --------------------- : 7
peersList : 100% : 9030 ms, 99% : 9030 ms, 95 : 9030 ms, 90% : 9030 ms.
Result count 1, range 9030 ms to  9030 ms.
sendList : 100% : 4987 ms, 99% : 4987 ms, 95 : 4987 ms, 90% : 4987 ms.
Average data rate: 0.02 MB/s
Result count 1, range 4987 ms to  4987 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-G900F_PT6068 --------------------- : 8
peersList : 100% : 4423 ms, 99% : 4423 ms, 95 : 4423 ms, 90% : 4423 ms.
Result count 1, range 4423 ms to  4423 ms.
sendList : 100% : 9558 ms, 99% : 9558 ms, 95 : 9558 ms, 90% : 9558 ms.
Average data rate: 0.016 MB/s
Result count 4, range 1695 ms to  9558 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 1 [20 %]
- Peer ID : 58:3F:54:73:64:C0
--------------- samsung-SM-A500FU_PT6430 --------------------- : 9
peersList : 100% : 2852 ms, 99% : 2852 ms, 95 : 2852 ms, 90% : 2852 ms.
Result count 1, range 2852 ms to  2852 ms.
sendList : 100% : 6290 ms, 99% : 6290 ms, 95 : 6290 ms, 90% : 6290 ms.
Average data rate: 0.026 MB/s
Result count 3, range 2579 ms to  6290 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-N910C_PT1003 --------------------- : 10
peersList : 100% : 4614 ms, 99% : 4614 ms, 95 : 4614 ms, 90% : 4614 ms.
Result count 1, range 4614 ms to  4614 ms.
sendList : 100% : 6255 ms, 99% : 6255 ms, 95 : 6255 ms, 90% : 6255 ms.
Average data rate: 0.016 MB/s
Result count 1, range 6255 ms to  6255 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- LGE-Nexus 5_PT8145 --------------------- : 11
peersList : 100% : 4445 ms, 99% : 4445 ms, 95 : 4445 ms, 90% : 4445 ms.
Result count 1, range 4445 ms to  4445 ms.
sendList : 100% : 4085 ms, 99% : 4085 ms, 95 : 4085 ms, 90% : 4085 ms.
Average data rate: 0.037 MB/s
Result count 2, range 1349 ms to  4085 ms.
sendList failed peers count : 0 [0 %]

sendList never tried peers count : 0 [0 %]
--------------- LGE-LG-D722_PT6438 --------------------- : 12
peersList : 100% : 4186 ms, 99% : 4186 ms, 95 : 4186 ms, 90% : 4186 ms.
Result count 1, range 4186 ms to  4186 ms.
sendList : 100% : 7531 ms, 99% : 7531 ms, 95 : 7531 ms, 90% : 7531 ms.
Average data rate: 0.017 MB/s

Result count 2, range 4244 ms to  7531 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 1 [33.333333333333336 %]

- Peer ID : 44:80:EB:7B:5A:05
--------------- HTC-HTC One M8s_PT1694 --------------------- : 13

peersList : 100% : 3849 ms, 99% : 3849 ms, 95 : 3849 ms, 90% : 3849 ms.
Result count 1, range 3849 ms to  3849 ms.
--------------- samsung-SM-G900F_PT6545 --------------------- : 14
peersList : 100% : 14729 ms, 99% : 14729 ms, 95 : 14729 ms, 90% : 14729 ms.
Result count 1, range 14729 ms to  14729 ms.
sendList : 100% : 5657 ms, 99% : 5657 ms, 95 : 5657 ms, 90% : 5657 ms.
Average data rate: 0.025 MB/s
Result count 2, range 2487 ms to  5657 ms.
sendList failed peers count : 0 [0 %]

sendList never tried peers count : 0 [0 %]
--------------- LGE-LG-D855_PT3911 --------------------- : 15
peersList : 100% : 3015 ms, 99% : 3015 ms, 95 : 3015 ms, 90% : 3015 ms.
Result count 1, range 3015 ms to  3015 ms.
sendList : 100% : 4230 ms, 99% : 4230 ms, 95 : 4230 ms, 90% : 4230 ms.
Average data rate: 0.027 MB/s
Result count 2, range 3096 ms to  4230 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 1 [33.333333333333336 %]
- Peer ID : 44:80:EB:7B:5A:05
--------------- samsung-SM-A300FU_PT7770 --------------------- : 16
peersList : 100% : 2246 ms, 99% : 2246 ms, 95 : 2246 ms, 90% : 2246 ms.
Result count 1, range 2246 ms to  2246 ms.
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
Results list does not contain any items
--------------- LGE-LG-H815_PT7855 --------------------- : 17
peersList : 100% : 12097 ms, 99% : 12097 ms, 95 : 12097 ms, 90% : 12097 ms.

Result count 1, range 12097 ms to  12097 ms.

sendList : 100% : 8621 ms, 99% : 8621 ms, 95 : 8621 ms, 90% : 8621 ms.
Average data rate: 0.018 MB/s
Result count 4, range 2475 ms to  8621 ms.

sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------

peersList : 100% : 14729 ms, 99% : 14729 ms, 95 : 12097 ms, 90% : 9030 ms.

sendList : 100% : 9558 ms, 99% : 9558 ms, 95 : 7531 ms, 90% : 6835 ms.

Average data rate: 0.022 MB/s
--------------- end of test report ---------------------

2015-12-23T02:17:57.027Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1_PT6053.eofveg==, peerAvailable=true, time=1047], sendList=[name=Apple-Iphone6-1_PT6053.vUErSg==, time=3474, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5s-1_PT4021.SE3R7g==, time=4182, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1_PT4216.OABFDg==, time=4694, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone6-1_PT6053.eofveg==, time=41093, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1_PT6053.eofveg==, peerAvailable=true, time=1749], sendList=[name=Apple-Iphone6-1_PT6053.vUErSg==, time=3649, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5s-1_PT4021.SE3R7g==, time=3979, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1_PT8230.FlW6Iw==, time=4760, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone6-1_PT6053.eofveg==, time=40368, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1_PT8230.LvlR6w==, peerAvailable=true, time=1158], sendList=[name=Apple-Iphone5s-1_PT4021.SE3R7g==, time=3725, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1_PT8230.FlW6Iw==, time=4106, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1_PT4216.OABFDg==, time=4121, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone6-1_PT6053.eofveg==, time=40665, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=(null), peerIdentifier=Apple-Iphone6-1_PT6053.eofveg==, peerAvailable=true, time=1067], sendList=[name=Apple-IpadAir2-1_PT8230.FlW6Iw==, time=3412, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1_PT4216.OABFDg==, time=3462, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone6-1_PT6053.vUErSg==, time=6175, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=Apple-Iphone6-1_PT6053.eofveg==, time=40791, result=Peer unreachable, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], peersList=[peerName=LGE-LG-D855_PT3911, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=2575], sendList=[name=B0:C5:59:3F:75:69, time=2637, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=44:80:EB:7B:5A:05, time=3880, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=F8:95:C7:87:85:54, time=6835, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], peersList=[peerName=LGE-Nexus 5_PT8145, peerIdentifier=34:FC:EF:11:AE:67, peerAvailable=true, time=2806], sendList=[], failedPeer=[], notTriedList=[name=F8:95:C7:87:85:54, time=0, result=Fail], peersList=[peerName=samsung-SM-A300FU_PT7770, peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=9030], sendList=[name=08:EC:A9:50:75:41, time=4987, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], peersList=[peerName=samsung-SM-A300FU_PT7770, peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=4423], sendList=[name=F8:95:C7:87:3C:51, time=1695, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=44:80:EB:7B:5A:05, time=6397, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=34:FC:EF:11:AE:67, time=6719, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=08:EC:A9:50:75:41, time=9558, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[name=58:3F:54:73:64:C0, time=0, result=Fail], peersList=[peerName=samsung-SM-G900F_PT6068, peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=2852], sendList=[name=E0:DB:10:14:E2:C0, time=2579, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=34:FC:EF:11:AE:67, time=2787, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=08:EC:A9:50:75:41, time=6290, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], peersList=[peerName=LGE-LG-D722_PT6438, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=4614], sendList=[name=7C:F9:0E:37:96:AB, time=6255, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], peersList=[peerName=samsung-SM-A500FU_PT6430, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=4445], sendList=[name=7C:F9:0E:37:96:AB, time=1349, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=B0:C5:59:3F:75:69, time=4085, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], peersList=[peerName=samsung-SM-A300FU_PT7770, peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=4186], sendList=[name=90:E7:C4:F6:69:77, time=4244, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=08:EC:A9:50:75:41, time=7531, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[name=44:80:EB:7B:5A:05, time=0, result=Fail], peersList=[peerName=LGE-LG-H815_PT7855, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=3849], peersList=[peerName=samsung-SM-G900F_PT6068, peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=14729], sendList=[name=E0:DB:10:14:E2:C0, time=2487, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:51:18:22, time=5657, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], peersList=[peerName=samsung-SM-A500FU_PT6430, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=3015], sendList=[name=E0:DB:10:14:E2:C0, time=3096, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=08:EC:A9:50:75:41, time=4230, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[name=44:80:EB:7B:5A:05, time=0, result=Fail], peersList=[peerName=LGE-LG-D722_PT6438, peerIdentifier=F8:95:C7:87:85:54, peerAvailable=true, time=2246], sendList=[], failedPeer=[], notTriedList=[], peersList=[peerName=motorola-XT1072_PT4998, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=12097], sendList=[name=E0:DB:10:14:E2:C0, time=2475, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=B0:C5:59:3F:75:69, time=4487, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=08:EC:A9:50:75:41, time=7078, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=F8:95:C7:87:85:54, time=8621, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[]

2015-12-23T02:17:57.801Z - debug: Socket disconnected: transport close 15 (samsung-SM-A300FU_PT7770)

2015-12-23T02:17:57.813Z - debug: Socket disconnected: transport close 3 (samsung-SM-A500FU_PT1715)

2015-12-23T02:17:57.936Z - debug: Socket disconnected: transport close 18 (motorola-XT1072_PT4998)

2015-12-23T02:17:57.968Z - debug: Socket disconnected: transport close 8 (samsung-SM-N910C_PT1003)

2015-12-23T02:17:58.014Z - debug: Socket disconnected: transport close 10 (LGE-Nexus 5_PT8145)

2015-12-23T02:17:58.193Z - debug: Socket disconnected: transport close 9 (LGE-LG-D722_PT6438)

2015-12-23T02:17:58.245Z - debug: Socket disconnected: transport close 5 (samsung-SM-G900F_PT6068)

2015-12-23T02:17:58.363Z - debug: Socket disconnected: transport close 13 (samsung-SM-G900F_PT6545)

2015-12-23T02:17:58.859Z - debug: Socket disconnected: transport close 1 (samsung-SM-A300FU_PT4270)

2015-12-23T02:17:58.934Z - debug: Socket disconnected: transport close 16 (LGE-LG-H815_PT7855)

2015-12-23T02:17:58.975Z - debug: Socket disconnected: transport close 6 (samsung-SM-A500FU_PT6430)

2015-12-23T02:18:07.285Z - debug: Socket disconnected: transport close 14 (LGE-LG-D855_PT3911)

2015-12-23T02:18:27.023Z - debug: Socket disconnected: ping timeout 11 (HTC-HTC One M8s_PT1694)


 
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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/54312298af2c956_Add_dummy_file_to_trigger_CI_tobybrad/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/54312298af2c956_Add_dummy_file_to_trigger_CI_tobybrad/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/54312298af2c956_Add_dummy_file_to_trigger_CI_tobybrad/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/54312298af2c956_Add_dummy_file_to_trigger_CI_tobybrad/thali02_LGE-Nexus 5.md)

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
[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/54312298af2c956_Add_dummy_file_to_trigger_CI_tobybrad/thali03_samsung-SM-G800F.md)

[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/54312298af2c956_Add_dummy_file_to_trigger_CI_tobybrad/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/54312298af2c956_Add_dummy_file_to_trigger_CI_tobybrad/thali03_LGE-LG-D855.md)

####Node name: thali04
Console output:
```
STOP log received from  0be0c6c6 Test has  SUCCEEDED
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on ZX1C223JKW 
Device test finished on 41006f95c8139173 
Device test finished on 0be0c6c6 
Android task is completed. [SUCCESS]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/54312298af2c956_Add_dummy_file_to_trigger_CI_tobybrad/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/54312298af2c956_Add_dummy_file_to_trigger_CI_tobybrad/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/54312298af2c956_Add_dummy_file_to_trigger_CI_tobybrad/thali04_samsung-SM-G900F.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/54312298af2c956_Add_dummy_file_to_trigger_CI_tobybrad/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/54312298af2c956_Add_dummy_file_to_trigger_CI_tobybrad/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/54312298af2c956_Add_dummy_file_to_trigger_CI_tobybrad/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
STOP log received from  4db5c8cc Test has  SUCCEEDED
STOP log received from  c5afcdcb Test has  SUCCEEDED
Device test finished on 4db5c8cc 
Device test finished on c5afcdcb 
Android task is completed. [SUCCESS]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/54312298af2c956_Add_dummy_file_to_trigger_CI_tobybrad/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/54312298af2c956_Add_dummy_file_to_trigger_CI_tobybrad/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/54312298af2c956_Add_dummy_file_to_trigger_CI_tobybrad/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/54312298af2c956_Add_dummy_file_to_trigger_CI_tobybrad/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/54312298af2c956_Add_dummy_file_to_trigger_CI_tobybrad/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/54312298af2c956_Add_dummy_file_to_trigger_CI_tobybrad/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/54312298af2c956_Add_dummy_file_to_trigger_CI_tobybrad/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/54312298af2c956_Add_dummy_file_to_trigger_CI_tobybrad/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/54312298af2c956_Add_dummy_file_to_trigger_CI_tobybrad/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/54312298af2c956_Add_dummy_file_to_trigger_CI_tobybrad/iOS_Iphone5s-1.md)



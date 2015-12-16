#### Test 506502789b39735 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":22}}
listening on *:3000

New device presented: motorola-XT1072_PT7347 (android) perftest

Setting start timeout to: 3000

New device presented: LGE-LG-D722_PT470 (android) perftest

Socket disconnected

New device presented: samsung-SM-G800H_PT5304 (android) perftest

Socket disconnected

New device presented: samsung-SM-A300FU_PT2285 (android) perftest

Socket disconnected

New device presented: LGE-Nexus 5_PT3017 (android) perftest

Socket disconnected

New device presented: LGE-LG-D855_PT2405 (android) perftest

Socket disconnected

New device presented: Apple-Iphone6-1_PT3762 (ios) perftest

Setting start timeout to: 3000

New device presented: samsung-SM-N9005_PT7616 (android) perftest

Socket disconnected

New device presented: HTC-HTC One M8s_PT2430 (android) perftest

Socket disconnected

New device presented: LGE-LG-D802_PT7404 (android) perftest

Socket disconnected

New device presented: HTC-HTC Desire 820_PT989 (android) perftest

Socket disconnected

New device presented: samsung-SM-A500FU_PT1059 (android) perftest

Socket disconnected

New device presented: HTC-HTC Desire 820_PT6438 (android) perftest

Socket disconnected

New device presented: LGE-Nexus 5_PT4069 (android) perftest

Socket disconnected

Start timeout elapsed for platform: android

Starting perf test run for platform: android

Using devices:
motorola-XT1072_PT7347

Setting: (android) 1

New device presented: samsung-SM-G900F_PT9528 (android) perftest

Socket disconnected

New device presented: samsung-SM-G900F_PT4097 (android) perftest

Socket disconnected

New device presented: samsung-SM-A500FU_PT5185 (android) perftest

Socket disconnected

New device presented: samsung-SM-N910C_PT3837 (android) perftest

Socket disconnected

New device presented: Apple-IpadAir2-1_PT9167 (ios) perftest

Socket disconnected

New device presented: Apple-Iphone5s-1_PT3724 (ios) perftest

Socket disconnected

New device presented: motorola-Nexus 6_PT6390 (android) perftest

Socket disconnected

Start timeout elapsed for platform: ios

Starting perf test run for platform: ios
Using devices:

Apple-Iphone6-1_PT3762
Setting: (ios) 1

New device presented: samsung-SM-G800F_PT6791 (android) perftest

Socket disconnected

New device presented: samsung-SM-A300FU_PT1274 (android) perftest

Socket disconnected

New device presented: LGE-LG-H815_PT7133 (android) perftest

Socket disconnected

New device presented: motorola-XT1039_PT3833 (android) perftest

Socket disconnected

Received results for motorola-XT1072_PT7347 android

toComplete: 1 android

All test data retrieved for testFindPeers.js (android)

Continuing to next test: testSendData.js

Setting: (android) 1

Received results for Apple-Iphone6-1_PT3762 ios

toComplete: 1 ios

All test data retrieved for testFindPeers.js (ios)

Continuing to next test: testSendData.js

Setting: (ios) 1

Received results for Apple-Iphone6-1_PT3762 ios

toComplete: 1 ios
All test data retrieved for testSendData.js (ios)

ALL DONE !!!

{ 'name:': 'Apple-Iphone6-1_PT3762',
  time: 999978,
  result: 'TIMEOUT',
  peersList: [] }

{ 'name:': 'Apple-Iphone6-1_PT3762',
  time: 41163,
  result: 'OK',
  sendList: 
   [ { name: 'Apple-Iphone6-1_PT3762.d2shgQ==',
       time: 41105,
       result: 'Peer unreachable',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 } ] }

--------------- test report ---------------------

--------------- Apple-Iphone6-1_PT3762 --------------------- : 1

peersList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.

Results list does not contain any items

sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.

Average data rate: NaN MB/s

Results list does not contain any items

sendList failed peers count : 1 [100 %]

- Peer ID : Apple-Iphone6-1_PT3762.d2shgQ==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Combined ---------------------
peersList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.

sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Average data rate: NaN MB/s
--------------- end of test report ---------------------

{ 'Apple-Iphone6-1_PT3762': 
   { peersList: [],
     sendList: [],
     sendError: { failedPeer: [Object], notTriedList: [] } } }

Socket disconnected

Socket disconnected


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m
Missing error handler on `socket`.

ReferenceError: d is not defined
    at PerfTestFramework.TestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/TestFramework.js:54:80)
    at PerfTestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/PerfTestFramework.js:65:48)
    at Socket.<anonymous> (/home/pi/Test/server_506502789b39735/test/TestServer/index.js:77:25)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:330:8)
    at Socket.onpacket (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:290:12)
    at Client.ondecoded (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:175:18)

Missing error handler on `socket`.

ReferenceError: d is not defined
    at PerfTestFramework.TestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/TestFramework.js:54:80)
    at PerfTestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/PerfTestFramework.js:65:48)
    at Socket.<anonymous> (/home/pi/Test/server_506502789b39735/test/TestServer/index.js:77:25)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:330:8)
    at Socket.onpacket (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:290:12)
    at Client.ondecoded (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:175:18)

Missing error handler on `socket`.

ReferenceError: d is not defined
    at PerfTestFramework.TestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/TestFramework.js:54:80)
    at PerfTestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/PerfTestFramework.js:65:48)
    at Socket.<anonymous> (/home/pi/Test/server_506502789b39735/test/TestServer/index.js:77:25)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:330:8)
    at Socket.onpacket (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:290:12)
    at Client.ondecoded (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:175:18)

Missing error handler on `socket`.

ReferenceError: d is not defined
    at PerfTestFramework.TestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/TestFramework.js:54:80)
    at PerfTestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/PerfTestFramework.js:65:48)
    at Socket.<anonymous> (/home/pi/Test/server_506502789b39735/test/TestServer/index.js:77:25)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:330:8)
    at Socket.onpacket (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:290:12)
    at Client.ondecoded (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:175:18)

Missing error handler on `socket`.

ReferenceError: d is not defined
    at PerfTestFramework.TestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/TestFramework.js:54:80)
    at PerfTestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/PerfTestFramework.js:65:48)
    at Socket.<anonymous> (/home/pi/Test/server_506502789b39735/test/TestServer/index.js:77:25)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:330:8)
    at Socket.onpacket (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:290:12)
    at Client.ondecoded (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:175:18)

Missing error handler on `socket`.

ReferenceError: d is not defined
    at PerfTestFramework.TestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/TestFramework.js:54:80)
    at PerfTestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/PerfTestFramework.js:65:48)
    at Socket.<anonymous> (/home/pi/Test/server_506502789b39735/test/TestServer/index.js:77:25)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:330:8)
    at Socket.onpacket (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:290:12)
    at Client.ondecoded (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:175:18)

Missing error handler on `socket`.

ReferenceError: d is not defined
    at PerfTestFramework.TestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/TestFramework.js:54:80)
    at PerfTestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/PerfTestFramework.js:65:48)
    at Socket.<anonymous> (/home/pi/Test/server_506502789b39735/test/TestServer/index.js:77:25)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:330:8)
    at Socket.onpacket (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:290:12)
    at Client.ondecoded (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:175:18)

Missing error handler on `socket`.

ReferenceError: d is not defined
    at PerfTestFramework.TestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/TestFramework.js:54:80)
    at PerfTestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/PerfTestFramework.js:65:48)
    at Socket.<anonymous> (/home/pi/Test/server_506502789b39735/test/TestServer/index.js:77:25)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:330:8)
    at Socket.onpacket (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:290:12)
    at Client.ondecoded (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:175:18)

Missing error handler on `socket`.

ReferenceError: d is not defined
    at PerfTestFramework.TestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/TestFramework.js:54:80)
    at PerfTestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/PerfTestFramework.js:65:48)
    at Socket.<anonymous> (/home/pi/Test/server_506502789b39735/test/TestServer/index.js:77:25)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:330:8)
    at Socket.onpacket (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:290:12)
    at Client.ondecoded (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:175:18)

Missing error handler on `socket`.

ReferenceError: d is not defined
    at PerfTestFramework.TestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/TestFramework.js:54:80)
    at PerfTestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/PerfTestFramework.js:65:48)
    at Socket.<anonymous> (/home/pi/Test/server_506502789b39735/test/TestServer/index.js:77:25)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:330:8)
    at Socket.onpacket (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:290:12)
    at Client.ondecoded (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:175:18)

Missing error handler on `socket`.

ReferenceError: d is not defined
    at PerfTestFramework.TestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/TestFramework.js:54:80)
    at PerfTestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/PerfTestFramework.js:65:48)
    at Socket.<anonymous> (/home/pi/Test/server_506502789b39735/test/TestServer/index.js:77:25)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:330:8)
    at Socket.onpacket (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:290:12)
    at Client.ondecoded (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:175:18)

Missing error handler on `socket`.

ReferenceError: d is not defined
    at PerfTestFramework.TestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/TestFramework.js:54:80)
    at PerfTestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/PerfTestFramework.js:65:48)
    at Socket.<anonymous> (/home/pi/Test/server_506502789b39735/test/TestServer/index.js:77:25)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:330:8)
    at Socket.onpacket (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:290:12)
    at Client.ondecoded (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:175:18)

Missing error handler on `socket`.

ReferenceError: d is not defined
    at PerfTestFramework.TestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/TestFramework.js:54:80)
    at PerfTestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/PerfTestFramework.js:65:48)
    at Socket.<anonymous> (/home/pi/Test/server_506502789b39735/test/TestServer/index.js:77:25)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:330:8)
    at Socket.onpacket (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:290:12)
    at Client.ondecoded (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:175:18)

Missing error handler on `socket`.

ReferenceError: d is not defined
    at PerfTestFramework.TestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/TestFramework.js:54:80)
    at PerfTestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/PerfTestFramework.js:65:48)
    at Socket.<anonymous> (/home/pi/Test/server_506502789b39735/test/TestServer/index.js:77:25)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:330:8)
    at Socket.onpacket (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:290:12)
    at Client.ondecoded (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:175:18)

Missing error handler on `socket`.

ReferenceError: d is not defined
    at PerfTestFramework.TestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/TestFramework.js:54:80)
    at PerfTestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/PerfTestFramework.js:65:48)
    at Socket.<anonymous> (/home/pi/Test/server_506502789b39735/test/TestServer/index.js:77:25)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:330:8)
    at Socket.onpacket (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:290:12)
    at Client.ondecoded (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:175:18)

Missing error handler on `socket`.

ReferenceError: d is not defined
    at PerfTestFramework.TestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/TestFramework.js:54:80)
    at PerfTestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/PerfTestFramework.js:65:48)
    at Socket.<anonymous> (/home/pi/Test/server_506502789b39735/test/TestServer/index.js:77:25)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:330:8)
    at Socket.onpacket (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:290:12)
    at Client.ondecoded (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:175:18)

Missing error handler on `socket`.

ReferenceError: d is not defined
    at PerfTestFramework.TestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/TestFramework.js:54:80)
    at PerfTestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/PerfTestFramework.js:65:48)
    at Socket.<anonymous> (/home/pi/Test/server_506502789b39735/test/TestServer/index.js:77:25)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:330:8)
    at Socket.onpacket (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:290:12)
    at Client.ondecoded (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:175:18)

Missing error handler on `socket`.

ReferenceError: d is not defined
    at PerfTestFramework.TestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/TestFramework.js:54:80)
    at PerfTestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/PerfTestFramework.js:65:48)
    at Socket.<anonymous> (/home/pi/Test/server_506502789b39735/test/TestServer/index.js:77:25)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:330:8)
    at Socket.onpacket (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:290:12)
    at Client.ondecoded (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:175:18)

Missing error handler on `socket`.

ReferenceError: d is not defined
    at PerfTestFramework.TestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/TestFramework.js:54:80)
    at PerfTestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/PerfTestFramework.js:65:48)
    at Socket.<anonymous> (/home/pi/Test/server_506502789b39735/test/TestServer/index.js:77:25)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:330:8)
    at Socket.onpacket (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:290:12)
    at Client.ondecoded (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:175:18)

Missing error handler on `socket`.

ReferenceError: d is not defined
    at PerfTestFramework.TestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/TestFramework.js:54:80)
    at PerfTestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/PerfTestFramework.js:65:48)
    at Socket.<anonymous> (/home/pi/Test/server_506502789b39735/test/TestServer/index.js:77:25)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:330:8)
    at Socket.onpacket (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:290:12)
    at Client.ondecoded (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:175:18)

Missing error handler on `socket`.

ReferenceError: d is not defined
    at PerfTestFramework.TestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/TestFramework.js:54:80)
    at PerfTestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/PerfTestFramework.js:65:48)
    at Socket.<anonymous> (/home/pi/Test/server_506502789b39735/test/TestServer/index.js:77:25)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:330:8)
    at Socket.onpacket (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:290:12)
    at Client.ondecoded (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:175:18)

Missing error handler on `socket`.

ReferenceError: d is not defined
    at PerfTestFramework.TestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/TestFramework.js:54:80)
    at PerfTestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/PerfTestFramework.js:65:48)
    at Socket.<anonymous> (/home/pi/Test/server_506502789b39735/test/TestServer/index.js:77:25)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:330:8)
    at Socket.onpacket (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:290:12)
    at Client.ondecoded (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:175:18)

Missing error handler on `socket`.

ReferenceError: d is not defined
    at PerfTestFramework.TestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/TestFramework.js:54:80)
    at PerfTestFramework.addDevice (/home/pi/Test/server_506502789b39735/test/TestServer/PerfTestFramework.js:65:48)
    at Socket.<anonymous> (/home/pi/Test/server_506502789b39735/test/TestServer/index.js:77:25)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:330:8)
    at Socket.onpacket (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/socket.js:290:12)
    at Client.ondecoded (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_506502789b39735/test/TestServer/node_modules/socket.io/lib/client.js:175:18)


```


Logs for system : 
```

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/506502789b39735_Enable_UnitTest_tobybrad/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/506502789b39735_Enable_UnitTest_tobybrad/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/506502789b39735_Enable_UnitTest_tobybrad/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/506502789b39735_Enable_UnitTest_tobybrad/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/506502789b39735_Enable_UnitTest_tobybrad/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/506502789b39735_Enable_UnitTest_tobybrad/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/506502789b39735_Enable_UnitTest_tobybrad/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Error! Unexpected exit on device 09a9416e0297d102 app:com.test.thalitest code:0 
child process exited with code 0 on device 09a9416e0297d102 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/506502789b39735_Enable_UnitTest_tobybrad/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/506502789b39735_Enable_UnitTest_tobybrad/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device TA4750HV7I app:com.test.thalitest code:0 
child process exited with code 0 on device TA4750HV7I 
Error! Unexpected exit on device LGD8553bed2d08 app:com.test.thalitest code:0 
child process exited with code 0 on device LGD8553bed2d08 
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:null 
child process exited with code null on device 320414cd475f91e3 
Android task is completed. [FAILED]
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/506502789b39735_Enable_UnitTest_tobybrad/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/506502789b39735_Enable_UnitTest_tobybrad/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/506502789b39735_Enable_UnitTest_tobybrad/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Error! Unexpected exit on device 0be0c6c6 app:com.test.thalitest code:null 
child process exited with code null on device 0be0c6c6 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/506502789b39735_Enable_UnitTest_tobybrad/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/506502789b39735_Enable_UnitTest_tobybrad/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/506502789b39735_Enable_UnitTest_tobybrad/thali04_samsung-SM-G900F.md)

####Node name: thali05
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 1d6a772d app:com.test.thalitest code:null 
child process exited with code null on device 1d6a772d 
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:null 
child process exited with code null on device ZX1G429CRK 
Error! Unexpected exit on device 954a12ed app:com.test.thalitest code:0 
child process exited with code 0 on device 954a12ed 
Android task is completed. [FAILED]
```
[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/506502789b39735_Enable_UnitTest_tobybrad/thali05_samsung-SM-N9005.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/506502789b39735_Enable_UnitTest_tobybrad/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/506502789b39735_Enable_UnitTest_tobybrad/thali05_samsung-SM-G800H.md)

####Node name: thali06
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:0 
child process exited with code 0 on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:0 
child process exited with code 0 on device FA55PYS00566 
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:0 
child process exited with code 0 on device 022678fb504e29b0 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/506502789b39735_Enable_UnitTest_tobybrad/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/506502789b39735_Enable_UnitTest_tobybrad/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/506502789b39735_Enable_UnitTest_tobybrad/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device c5afcdcb app:com.test.thalitest code:null 
child process exited with code null on device c5afcdcb 
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:null 
child process exited with code null on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/506502789b39735_Enable_UnitTest_tobybrad/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/506502789b39735_Enable_UnitTest_tobybrad/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/506502789b39735_Enable_UnitTest_tobybrad/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/506502789b39735_Enable_UnitTest_tobybrad/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/506502789b39735_Enable_UnitTest_tobybrad/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/506502789b39735_Enable_UnitTest_tobybrad/thali09_LGE-Nexus 5.md)





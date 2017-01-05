#### Test 100139766aeece48 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":5,"android":3}}
2017-01-05 16:01:29 - INFO HttpServer: 'listening on *:3000'

2017-01-05 16:03:10 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '499b5fff-6c0c-40af-8af6-0641c1c88bd1', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-01-05 16:03:10 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-01-05 16:03:12 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '2c8e06ba-1dd5-4b1e-9741-264a8f2fcca1', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-01-05 16:03:12 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-01-05 16:04:33 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '89d5ffd8-3e99-434f-99e0-1adf231d811b', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-01-05 16:04:33 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-01-05 16:04:33 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-01-05 16:04:33 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-01-05 16:04:33 - DEBUG UnitTestFramework: 'scheduling tests'

2017-01-05 16:04:34 - DEBUG UnitTestFramework: 'tests scheduled'

2017-01-05 16:04:34 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-01-05 16:04:34 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-01-05 16:04:34 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-01-05 16:04:34 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-01-05 16:04:34 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-01-05 16:04:34 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-01-05 16:04:34 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-01-05 16:04:34 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-01-05 16:04:34 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-01-05 16:04:34 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-01-05 16:04:34 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-01-05 16:04:35 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-01-05 16:04:35 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-01-05 16:04:35 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-01-05 16:04:35 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-01-05 16:04:35 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-01-05 16:04:35 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-01-05 16:04:35 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-01-05 16:04:35 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-01-05 16:04:35 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-01-05 16:04:35 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-01-05 16:04:35 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-01-05 16:04:35 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-01-05 16:04:35 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-01-05 16:04:35 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-01-05 16:04:35 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-01-05 16:04:35 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-01-05 16:04:35 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-01-05 16:04:36 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-01-05 16:04:36 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-01-05 16:04:36 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-01-05 16:04:36 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-01-05 16:04:36 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-01-05 16:04:36 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-01-05 16:04:36 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-01-05 16:04:36 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-01-05 16:04:36 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-01-05 16:04:36 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-01-05 16:04:36 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-01-05 16:04:38 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-01-05 16:04:38 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-01-05 16:04:38 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-01-05 16:04:38 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-01-05 16:04:38 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-01-05 16:04:38 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-01-05 16:04:39 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-01-05 16:04:39 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-01-05 16:04:39 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-01-05 16:04:39 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-01-05 16:04:39 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-01-05 16:04:39 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-01-05 16:04:39 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-01-05 16:04:39 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-01-05 16:04:39 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-01-05 16:04:39 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-01-05 16:04:39 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-01-05 16:04:39 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-01-05 16:04:39 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-01-05 16:04:39 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-01-05 16:04:39 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-01-05 16:04:39 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-01-05 16:04:39 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-01-05 16:04:39 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-01-05 16:04:39 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-01-05 16:04:39 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-01-05 16:04:39 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-01-05 16:04:39 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-01-05 16:04:39 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-01-05 16:04:39 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-01-05 16:04:39 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-01-05 16:04:39 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-01-05 16:04:39 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-01-05 16:04:39 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-01-05 16:04:40 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-01-05 16:04:40 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-01-05 16:04:40 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-01-05 16:04:40 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-01-05 16:04:40 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-01-05 16:04:40 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-01-05 16:04:40 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-01-05 16:04:40 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-01-05 16:04:40 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-01-05 16:04:40 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-01-05 16:04:40 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-01-05 16:04:40 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-01-05 16:04:40 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-01-05 16:04:40 - DEBUG UnitTestFramework: '#run: 'basic''

2017-01-05 16:04:40 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-01-05 16:04:40 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-01-05 16:04:40 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-01-05 16:04:40 - DEBUG UnitTestFramework: '#setup: 'another''

2017-01-05 16:04:40 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-01-05 16:04:40 - DEBUG UnitTestFramework: '#run: 'another''

2017-01-05 16:04:41 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-01-05 16:04:41 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-01-05 16:04:41 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-01-05 16:04:41 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-01-05 16:04:41 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-01-05 16:04:41 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-01-05 16:04:42 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-01-05 16:04:42 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-01-05 16:04:42 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-01-05 16:04:42 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-01-05 16:04:42 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-01-05 16:04:42 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-01-05 16:04:42 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-01-05 16:04:42 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-01-05 16:04:42 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-01-05 16:04:42 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-01-05 16:04:42 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-01-05 16:04:42 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-01-05 16:04:42 - ERROR UnitTestFramework: '#run failed: 'onPeerLost calls jxcore', error: 'Error: run failed, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore', sent data: '[{"uuid":"499b5fff-6c0c-40af-8af6-0641c1c88bd1"},{"uuid":"2c8e06ba-1dd5-4b1e-9741-264a8f2fcca1"},{"uuid":"89d5ffd8-3e99-434f-99e0-1adf231d811b"}]', received data: '{"success":false}'', stack: 'Error: run failed, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore', sent data: '[{"uuid":"499b5fff-6c0c-40af-8af6-0641c1c88bd1"},{"uuid":"2c8e06ba-1dd5-4b1e-9741-264a8f2fcca1"},{"uuid":"89d5ffd8-3e99-434f-99e0-1adf231d811b"}]', received data: '{"success":false}'
    at finishedHandler (/home/pi/Test/server_100139766aeece48/test/TestServer/Socket.js:205:15)
    at Socket.<anonymous> (/home/pi/Test/server_100139766aeece48/test/TestServer/Socket.js:238:9)
    at Socket.g (events.js:160:16)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_100139766aeece48/test/TestServer/node_modules/socket.io/lib/socket.js:335:8)
    at Socket.onpacket (/home/pi/Test/server_100139766aeece48/test/TestServer/node_modules/socket.io/lib/socket.js:295:12)
    at Client.ondecoded (/home/pi/Test/server_100139766aeece48/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_100139766aeece48/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_100139766aeece48/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_100139766aeece48/test/TestServer/node_modules/socket.io/lib/client.js:175:18)
    at Socket.emit (events.js:82:17)
    at Socket.onPacket (/home/pi/Test/server_100139766aeece48/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/socket.js:101:14)
    at WebSocket.emit (events.js:82:17)
    at WebSocket.Transport.onPacket (/home/pi/Test/server_100139766aeece48/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:104:8)
    at WebSocket.Transport.onData (/home/pi/Test/server_100139766aeece48/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:115:8)
    at WebSocket.onData (/home/pi/Test/server_100139766aeece48/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transports/websocket.js:76:30)
    at WebSocket.emit (events.js:85:17)''

2017-01-05 16:04:42 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'android', error: 'Error: run failed, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore', sent data: '[{"uuid":"499b5fff-6c0c-40af-8af6-0641c1c88bd1"},{"uuid":"2c8e06ba-1dd5-4b1e-9741-264a8f2fcca1"},{"uuid":"89d5ffd8-3e99-434f-99e0-1adf231d811b"}]', received data: '{"success":false}'', stack: 'Error: run failed, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore', sent data: '[{"uuid":"499b5fff-6c0c-40af-8af6-0641c1c88bd1"},{"uuid":"2c8e06ba-1dd5-4b1e-9741-264a8f2fcca1"},{"uuid":"89d5ffd8-3e99-434f-99e0-1adf231d811b"}]', received data: '{"success":false}'
    at finishedHandler (/home/pi/Test/server_100139766aeece48/test/TestServer/Socket.js:205:15)
    at Socket.<anonymous> (/home/pi/Test/server_100139766aeece48/test/TestServer/Socket.js:238:9)
    at Socket.g (events.js:160:16)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_100139766aeece48/test/TestServer/node_modules/socket.io/lib/socket.js:335:8)
    at Socket.onpacket (/home/pi/Test/server_100139766aeece48/test/TestServer/node_modules/socket.io/lib/socket.js:295:12)
    at Client.ondecoded (/home/pi/Test/server_100139766aeece48/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_100139766aeece48/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_100139766aeece48/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_100139766aeece48/test/TestServer/node_modules/socket.io/lib/client.js:175:18)
    at Socket.emit (events.js:82:17)
    at Socket.onPacket (/home/pi/Test/server_100139766aeece48/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/socket.js:101:14)
    at WebSocket.emit (events.js:82:17)
    at WebSocket.Transport.onPacket (/home/pi/Test/server_100139766aeece48/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:104:8)
    at WebSocket.Transport.onData (/home/pi/Test/server_100139766aeece48/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:115:8)
    at WebSocket.onData (/home/pi/Test/server_100139766aeece48/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transports/websocket.js:76:30)
    at WebSocket.emit (events.js:85:17)''
2017-01-05 16:04:42 - ERROR HttpServer: 'unexpected server error: 'Error: run failed, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore', sent data: '[{"uuid":"499b5fff-6c0c-40af-8af6-0641c1c88bd1"},{"uuid":"2c8e06ba-1dd5-4b1e-9741-264a8f2fcca1"},{"uuid":"89d5ffd8-3e99-434f-99e0-1adf231d811b"}]', received data: '{"success":false}'''

2017-01-05 16:04:42 - ERROR HttpServer: 'unexpected server error: 'Error: run failed, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore', sent data: '[{"uuid":"499b5fff-6c0c-40af-8af6-0641c1c88bd1"},{"uuid":"2c8e06ba-1dd5-4b1e-9741-264a8f2fcca1"},{"uuid":"89d5ffd8-3e99-434f-99e0-1adf231d811b"}]', received data: '{"success":false}'''

2017-01-05 16:04:42 - ERROR HttpServer: 'unexpected server error: 'Error: run failed, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore', sent data: '[{"uuid":"499b5fff-6c0c-40af-8af6-0641c1c88bd1"},{"uuid":"2c8e06ba-1dd5-4b1e-9741-264a8f2fcca1"},{"uuid":"89d5ffd8-3e99-434f-99e0-1adf231d811b"}]', received data: '{"success":false}'''

2017-01-05 16:04:42 - ERROR UnitTestFramework: 'unexpected error: 'Error: Error: run failed, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore', sent data: '[{"uuid":"499b5fff-6c0c-40af-8af6-0641c1c88bd1"},{"uuid":"2c8e06ba-1dd5-4b1e-9741-264a8f2fcca1"},{"uuid":"89d5ffd8-3e99-434f-99e0-1adf231d811b"}]', received data: '{"success":false}'', stack: 'Error: Error: run failed, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore', sent data: '[{"uuid":"499b5fff-6c0c-40af-8af6-0641c1c88bd1"},{"uuid":"2c8e06ba-1dd5-4b1e-9741-264a8f2fcca1"},{"uuid":"89d5ffd8-3e99-434f-99e0-1adf231d811b"}]', received data: '{"success":false}'
    at Server._error (/home/pi/Test/server_100139766aeece48/test/TestServer/HttpServer.js:78:9)
    at Socket.emit (events.js:82:17)
    at Socket.emit (/home/pi/Test/server_100139766aeece48/test/TestServer/node_modules/socket.io/lib/socket.js:128:10)
    at updatedHandler (/home/pi/Test/server_100139766aeece48/test/TestServer/Socket.js:105:29)
    at Socket._apply (/home/pi/Test/server_100139766aeece48/test/TestServer/Socket.js:108:3)
    at emit (/home/pi/Test/server_100139766aeece48/test/TestServer/Socket.js:167:22)
    at /home/pi/Test/server_100139766aeece48/test/TestServer/Socket.js:171:5
    at Promise._execute (/home/pi/Test/server_100139766aeece48/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_100139766aeece48/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_100139766aeece48/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Socket.emitData (/home/pi/Test/server_100139766aeece48/test/TestServer/Socket.js:136:10)
    at TestDevice.error (/home/pi/Test/server_100139766aeece48/test/TestServer/TestDevice.js:137:23)
    at /home/pi/Test/server_100139766aeece48/test/TestServer/UnitTestFramework.js:87:23
    at Array.map (native)
    at /home/pi/Test/server_100139766aeece48/test/TestServer/UnitTestFramework.js:86:15
    at tryCatcher (/home/pi/Test/server_100139766aeece48/test/TestServer/node_modules/bluebird/js/release/util.js:16:23)''

2017-01-05 16:04:42 - ERROR UnitTestFramework: 'unexpected error: 'Error: Error: run failed, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore', sent data: '[{"uuid":"499b5fff-6c0c-40af-8af6-0641c1c88bd1"},{"uuid":"2c8e06ba-1dd5-4b1e-9741-264a8f2fcca1"},{"uuid":"89d5ffd8-3e99-434f-99e0-1adf231d811b"}]', received data: '{"success":false}'', stack: 'Error: Error: run failed, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore', sent data: '[{"uuid":"499b5fff-6c0c-40af-8af6-0641c1c88bd1"},{"uuid":"2c8e06ba-1dd5-4b1e-9741-264a8f2fcca1"},{"uuid":"89d5ffd8-3e99-434f-99e0-1adf231d811b"}]', received data: '{"success":false}'
    at Server._error (/home/pi/Test/server_100139766aeece48/test/TestServer/HttpServer.js:78:9)
    at Socket.emit (events.js:82:17)
    at Socket.emit (/home/pi/Test/server_100139766aeece48/test/TestServer/node_modules/socket.io/lib/socket.js:128:10)
    at updatedHandler (/home/pi/Test/server_100139766aeece48/test/TestServer/Socket.js:105:29)
    at Socket._apply (/home/pi/Test/server_100139766aeece48/test/TestServer/Socket.js:108:3)
    at emit (/home/pi/Test/server_100139766aeece48/test/TestServer/Socket.js:167:22)
    at /home/pi/Test/server_100139766aeece48/test/TestServer/Socket.js:171:5
    at Promise._execute (/home/pi/Test/server_100139766aeece48/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_100139766aeece48/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_100139766aeece48/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Socket.emitData (/home/pi/Test/server_100139766aeece48/test/TestServer/Socket.js:136:10)
    at TestDevice.error (/home/pi/Test/server_100139766aeece48/test/TestServer/TestDevice.js:137:23)
    at /home/pi/Test/server_100139766aeece48/test/TestServer/UnitTestFramework.js:87:23
    at Array.map (native)
    at /home/pi/Test/server_100139766aeece48/test/TestServer/UnitTestFramework.js:86:15
    at tryCatcher (/home/pi/Test/server_100139766aeece48/test/TestServer/node_modules/bluebird/js/release/util.js:16:23)''

2017-01-05 16:04:42 - ERROR UnitTestFramework: 'unexpected error: 'Error: Error: run failed, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore', sent data: '[{"uuid":"499b5fff-6c0c-40af-8af6-0641c1c88bd1"},{"uuid":"2c8e06ba-1dd5-4b1e-9741-264a8f2fcca1"},{"uuid":"89d5ffd8-3e99-434f-99e0-1adf231d811b"}]', received data: '{"success":false}'', stack: 'Error: Error: run failed, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore', sent data: '[{"uuid":"499b5fff-6c0c-40af-8af6-0641c1c88bd1"},{"uuid":"2c8e06ba-1dd5-4b1e-9741-264a8f2fcca1"},{"uuid":"89d5ffd8-3e99-434f-99e0-1adf231d811b"}]', received data: '{"success":false}'
    at Server._error (/home/pi/Test/server_100139766aeece48/test/TestServer/HttpServer.js:78:9)
    at Socket.emit (events.js:82:17)
    at Socket.emit (/home/pi/Test/server_100139766aeece48/test/TestServer/node_modules/socket.io/lib/socket.js:128:10)
    at updatedHandler (/home/pi/Test/server_100139766aeece48/test/TestServer/Socket.js:105:29)
    at Socket._apply (/home/pi/Test/server_100139766aeece48/test/TestServer/Socket.js:108:3)
    at emit (/home/pi/Test/server_100139766aeece48/test/TestServer/Socket.js:167:22)
    at /home/pi/Test/server_100139766aeece48/test/TestServer/Socket.js:171:5
    at Promise._execute (/home/pi/Test/server_100139766aeece48/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_100139766aeece48/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_100139766aeece48/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Socket.emitData (/home/pi/Test/server_100139766aeece48/test/TestServer/Socket.js:136:10)
    at TestDevice.error (/home/pi/Test/server_100139766aeece48/test/TestServer/TestDevice.js:137:23)
    at /home/pi/Test/server_100139766aeece48/test/TestServer/UnitTestFramework.js:87:23
    at Array.map (native)
    at /home/pi/Test/server_100139766aeece48/test/TestServer/UnitTestFramework.js:86:15
    at tryCatcher (/home/pi/Test/server_100139766aeece48/test/TestServer/node_modules/bluebird/js/release/util.js:16:23)''

2017-01-05 16:04:42 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'client namespace disconnect''

2017-01-05 16:04:42 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'client namespace disconnect''

2017-01-05 16:04:42 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'client namespace disconnect''

[0;31merror: command 'sudo jx ______.js all' failed with code 1, file 'bash' on line 30[0m
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
####Node name: thali02
Console output:
```
Stopping app on  ce0616068b9f212302
Uninstalling app on  ce0616068b9f212302

All devices are ready!

Deploying to ce0616068b9f212302
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce0616068b9f212302

Starting application ThaliTest on ce0616068b9f212302

App was succesfully started on ce0616068b9f212302

STOP log received from ce0616068b9f212302
Test has FAILED

Device test finished on ce0616068b9f212302 
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/100139766aeece48_Fixed_reconnect_after_close_andrew-aladev/thali02_samsung-SM-G930F.md)

####Node name: thali03
Console output:
```
Stopping app on  ce061606c181d71003
Uninstalling app on  ce061606c181d71003

All devices are ready!

Deploying to ce061606c181d71003
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
Deploying to ce061606c181d71003
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce061606c181d71003

Starting application ThaliTest on ce061606c181d71003

App was succesfully started on ce061606c181d71003

STOP log received from ce061606c181d71003
Test has FAILED

Device test finished on ce061606c181d71003 
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/100139766aeece48_Fixed_reconnect_after_close_andrew-aladev/thali03_samsung-SM-G930F.md)

####Node name: thali04
Console output:
```
Stopping app on  ce061606e320561102
Uninstalling app on  ce061606e320561102

All devices are ready!

Deploying to ce061606e320561102
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
Deploying to ce061606e320561102
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce061606e320561102

Starting application ThaliTest on ce061606e320561102

App was succesfully started on ce061606e320561102

STOP log received from ce061606e320561102
Test has FAILED

Device test finished on ce061606e320561102 
Android task is completed. [FAILED]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/100139766aeece48_Fixed_reconnect_after_close_andrew-aladev/thali04_samsung-SM-G935F.md)




###iOS Logs
[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/100139766aeece48_Fixed_reconnect_after_close_andrew-aladev/iOS_ipad-air-2-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/100139766aeece48_Fixed_reconnect_after_close_andrew-aladev/iOS_iphone-5s-mfts.md)

[iphone-6-2](https://github.com/ThaliTester/TestResults/blob/100139766aeece48_Fixed_reconnect_after_close_andrew-aladev/iOS_iphone-6-2.md)

[ipad-mini-mfts](https://github.com/ThaliTester/TestResults/blob/100139766aeece48_Fixed_reconnect_after_close_andrew-aladev/iOS_ipad-mini-mfts.md)

[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/100139766aeece48_Fixed_reconnect_after_close_andrew-aladev/iOS_iphone-5s-1.md)



#### Test 9004993954b94ec Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-10-19 17:16:03 - INFO HttpServer: 'listening on *:3000'

2016-10-19 17:17:41 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '499c4e0c-5390-4528-a4bb-3c9feb9cafa0', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-19 17:17:41 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2016-10-19 17:17:41 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '53685234-4b55-42c6-9749-635e72fd198d', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-19 17:17:41 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2016-10-19 17:17:54 - DEBUG HttpServer: 'device presented, name: 'Huawei-Nexus 6P', uuid: 'd731ab26-fdbf-40ff-aa2c-3608fdff3bde', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-19 17:17:54 - DEBUG TestFramework: 'device added, name: 'Huawei-Nexus 6P''

2016-10-19 17:17:54 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2016-10-19 17:17:54 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2016-10-19 17:17:54 - DEBUG UnitTestFramework: 'scheduling tests'

2016-10-19 17:17:55 - DEBUG UnitTestFramework: 'tests scheduled'

2016-10-19 17:17:55 - DEBUG UnitTestFramework: '#setup: 'calling createNativeListener directly rejects''

2016-10-19 17:17:55 - DEBUG UnitTestFramework: '#setup ok: 'calling createNativeListener directly rejects''

2016-10-19 17:17:55 - DEBUG UnitTestFramework: '#run: 'calling createNativeListener directly rejects''

2016-10-19 17:17:55 - DEBUG UnitTestFramework: '#run ok: 'calling createNativeListener directly rejects''

2016-10-19 17:17:55 - DEBUG UnitTestFramework: '#teardown: 'calling createNativeListener directly rejects''

2016-10-19 17:17:56 - DEBUG UnitTestFramework: '#teardown ok: 'calling createNativeListener directly rejects''

2016-10-19 17:17:56 - DEBUG UnitTestFramework: '#setup: 'emits incomingConnectionState''

2016-10-19 17:17:57 - DEBUG UnitTestFramework: '#setup ok: 'emits incomingConnectionState''

2016-10-19 17:17:57 - DEBUG UnitTestFramework: '#run: 'emits incomingConnectionState''

2016-10-19 17:17:57 - DEBUG UnitTestFramework: '#run ok: 'emits incomingConnectionState''

2016-10-19 17:17:57 - DEBUG UnitTestFramework: '#teardown: 'emits incomingConnectionState''

2016-10-19 17:17:58 - DEBUG UnitTestFramework: '#teardown ok: 'emits incomingConnectionState''

2016-10-19 17:17:58 - DEBUG UnitTestFramework: '#setup: 'emits routerPortConnectionFailed''

2016-10-19 17:17:58 - DEBUG UnitTestFramework: '#setup ok: 'emits routerPortConnectionFailed''

2016-10-19 17:17:58 - DEBUG UnitTestFramework: '#run: 'emits routerPortConnectionFailed''

2016-10-19 17:17:59 - DEBUG UnitTestFramework: '#run ok: 'emits routerPortConnectionFailed''

2016-10-19 17:17:59 - DEBUG UnitTestFramework: '#teardown: 'emits routerPortConnectionFailed''

2016-10-19 17:18:00 - DEBUG UnitTestFramework: '#teardown ok: 'emits routerPortConnectionFailed''

2016-10-19 17:18:00 - DEBUG UnitTestFramework: '#setup: 'native server connections all up''

2016-10-19 17:18:00 - DEBUG UnitTestFramework: '#setup ok: 'native server connections all up''

2016-10-19 17:18:00 - DEBUG UnitTestFramework: '#run: 'native server connections all up''

2016-10-19 17:18:01 - DEBUG UnitTestFramework: '#run ok: 'native server connections all up''

2016-10-19 17:18:01 - DEBUG UnitTestFramework: '#teardown: 'native server connections all up''

2016-10-19 17:18:01 - DEBUG UnitTestFramework: '#teardown ok: 'native server connections all up''

2016-10-19 17:18:01 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming stream cleans outgoing socket''

2016-10-19 17:18:02 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming stream cleans outgoing socket''

2016-10-19 17:18:02 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming stream cleans outgoing socket''

2016-10-19 17:18:03 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming stream cleans outgoing socket''

2016-10-19 17:18:03 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming stream cleans outgoing socket''

2016-10-19 17:18:03 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming stream cleans outgoing socket''

2016-10-19 17:18:03 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming connection cleans outgoing socket''

2016-10-19 17:18:04 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming connection cleans outgoing socket''

2016-10-19 17:18:04 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming connection cleans outgoing socket''

2016-10-19 17:18:05 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming connection cleans outgoing socket''

2016-10-19 17:18:05 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming connection cleans outgoing socket''

2016-10-19 17:18:05 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming connection cleans outgoing socket''

2016-10-19 17:18:05 - DEBUG UnitTestFramework: '#setup: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-19 17:18:06 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-19 17:18:06 - DEBUG UnitTestFramework: '#run: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-19 17:18:06 - DEBUG UnitTestFramework: '#run ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-19 17:18:06 - DEBUG UnitTestFramework: '#teardown: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-19 17:18:07 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-19 17:18:07 - DEBUG UnitTestFramework: '#setup: 'native server - closing the whole server cleans everything up''

2016-10-19 17:18:08 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing the whole server cleans everything up''

2016-10-19 17:18:08 - DEBUG UnitTestFramework: '#run: 'native server - closing the whole server cleans everything up''

2016-10-19 17:18:09 - DEBUG UnitTestFramework: '#run ok: 'native server - closing the whole server cleans everything up''

2016-10-19 17:18:09 - DEBUG UnitTestFramework: '#teardown: 'native server - closing the whole server cleans everything up''

2016-10-19 17:18:09 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing the whole server cleans everything up''

2016-10-19 17:18:09 - DEBUG UnitTestFramework: '#setup: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-19 17:18:10 - DEBUG UnitTestFramework: '#setup ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-19 17:18:10 - DEBUG UnitTestFramework: '#run: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-19 17:18:11 - DEBUG UnitTestFramework: '#run ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-19 17:18:11 - DEBUG UnitTestFramework: '#teardown: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-19 17:18:12 - DEBUG UnitTestFramework: '#teardown ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-19 17:18:12 - DEBUG UnitTestFramework: '#setup: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-10-19 17:18:13 - DEBUG UnitTestFramework: '#setup ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-10-19 17:18:13 - DEBUG UnitTestFramework: '#run: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-10-19 17:18:14 - DEBUG UnitTestFramework: '#run ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-10-19 17:18:14 - DEBUG UnitTestFramework: '#teardown: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-10-19 17:18:14 - DEBUG UnitTestFramework: '#teardown ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-10-19 17:18:14 - DEBUG UnitTestFramework: '#setup: 'native server - timing out the incoming connection cleans everything up''

2016-10-19 17:18:15 - DEBUG UnitTestFramework: '#setup ok: 'native server - timing out the incoming connection cleans everything up''

2016-10-19 17:18:15 - DEBUG UnitTestFramework: '#run: 'native server - timing out the incoming connection cleans everything up''

2016-10-19 17:18:15 - DEBUG UnitTestFramework: '#run ok: 'native server - timing out the incoming connection cleans everything up''

2016-10-19 17:18:15 - DEBUG UnitTestFramework: '#teardown: 'native server - timing out the incoming connection cleans everything up''

2016-10-19 17:18:16 - DEBUG UnitTestFramework: '#teardown ok: 'native server - timing out the incoming connection cleans everything up''

2016-10-19 17:18:16 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server is not there''

2016-10-19 17:18:17 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server is not there''

2016-10-19 17:18:17 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server is not there''

2016-10-19 17:18:18 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server is not there''

2016-10-19 17:18:18 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server is not there''

2016-10-19 17:18:18 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server is not there''

2016-10-19 17:18:18 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-19 17:18:19 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-19 17:18:19 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-19 17:18:19 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-19 17:18:19 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-19 17:18:20 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-19 17:18:20 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-19 17:18:20 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-19 17:18:20 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-19 17:18:21 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-19 17:18:21 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-19 17:18:22 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-19 17:18:22 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-19 17:18:22 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-19 17:18:22 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-19 17:18:25 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-19 17:18:25 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-19 17:18:26 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-19 17:18:26 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-19 17:18:26 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-19 17:18:26 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-19 17:18:27 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-19 17:18:27 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-19 17:18:27 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-19 17:18:27 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - update seq three times''

2016-10-19 17:18:27 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - update seq three times''

2016-10-19 17:18:27 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - update seq three times''

2016-10-19 17:18:28 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - update seq three times''

2016-10-19 17:18:28 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - update seq three times''

2016-10-19 17:18:28 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - update seq three times''

2016-10-19 17:18:28 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-19 17:18:28 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-19 17:18:28 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-19 17:18:28 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-19 17:18:28 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-19 17:18:29 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-19 17:18:29 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-19 17:18:29 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-19 17:18:29 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-19 17:18:29 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-19 17:18:29 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-19 17:18:29 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-19 17:18:29 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-19 17:18:29 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-19 17:18:29 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-19 17:18:29 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-19 17:18:29 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-19 17:18:29 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-19 17:18:29 - DEBUG UnitTestFramework: '#setup: '#update - fail if stop is called''

2016-10-19 17:18:29 - DEBUG UnitTestFramework: '#setup ok: '#update - fail if stop is called''

2016-10-19 17:18:29 - DEBUG UnitTestFramework: '#run: '#update - fail if stop is called''

2016-10-19 17:18:29 - DEBUG UnitTestFramework: '#run ok: '#update - fail if stop is called''

2016-10-19 17:18:29 - DEBUG UnitTestFramework: '#teardown: '#update - fail if stop is called''

2016-10-19 17:18:30 - DEBUG UnitTestFramework: '#teardown ok: '#update - fail if stop is called''

2016-10-19 17:18:30 - DEBUG UnitTestFramework: '#setup: '#update - set seq for first time''

2016-10-19 17:18:30 - DEBUG UnitTestFramework: '#setup ok: '#update - set seq for first time''

2016-10-19 17:18:30 - DEBUG UnitTestFramework: '#run: '#update - set seq for first time''

2016-10-19 17:18:30 - DEBUG UnitTestFramework: '#run ok: '#update - set seq for first time''

2016-10-19 17:18:30 - DEBUG UnitTestFramework: '#teardown: '#update - set seq for first time''

2016-10-19 17:18:30 - DEBUG UnitTestFramework: '#teardown ok: '#update - set seq for first time''

2016-10-19 17:18:30 - DEBUG UnitTestFramework: '#setup: '#update - Fail on bad seq value''

2016-10-19 17:18:30 - DEBUG UnitTestFramework: '#setup ok: '#update - Fail on bad seq value''

2016-10-19 17:18:30 - DEBUG UnitTestFramework: '#run: '#update - Fail on bad seq value''

2016-10-19 17:18:31 - DEBUG UnitTestFramework: '#run ok: '#update - Fail on bad seq value''

2016-10-19 17:18:31 - DEBUG UnitTestFramework: '#teardown: '#update - Fail on bad seq value''

2016-10-19 17:18:32 - DEBUG UnitTestFramework: '#teardown ok: '#update - Fail on bad seq value''

2016-10-19 17:18:32 - DEBUG UnitTestFramework: '#setup: '#update - do we cancel timer properly on an immediate?''

2016-10-19 17:18:33 - DEBUG UnitTestFramework: '#setup ok: '#update - do we cancel timer properly on an immediate?''

2016-10-19 17:18:33 - DEBUG UnitTestFramework: '#run: '#update - do we cancel timer properly on an immediate?''

2016-10-19 17:18:33 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'transport close''

2016-10-19 17:19:34 - INFO HttpServer: 'Socket to device name: 'Huawei-Nexus 6P' disconnected, reason: 'client namespace disconnect''

2016-10-19 17:19:35 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'client namespace disconnect''

2016-10-19 17:20:15 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '34a60376-3489-41c8-9e86-6d312b7e8d8c', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-19 17:20:15 - INFO TestFramework: 'we have enough devices; discarding device, name: 'samsung-SM-G930F', platformName: 'android''

2016-10-19 17:21:33 - ERROR UnitTestFramework: '#run failed: '#update - do we cancel timer properly on an immediate?', error: 'TimeoutError: timeout exceeded, event: 'run_#update - do we cancel timer properly on an immediate?_finished', test: '#update - do we cancel timer properly on an immediate?'', stack: 'TimeoutError: timeout exceeded, event: 'run_#update - do we cancel timer properly on an immediate?_finished', test: '#update - do we cancel timer properly on an immediate?'
    at afterTimeout (/home/pi/Test/server_9004993954b94ec/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_9004993954b94ec/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-19 17:21:33 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'android', error: 'TimeoutError: timeout exceeded, event: 'run_#update - do we cancel timer properly on an immediate?_finished', test: '#update - do we cancel timer properly on an immediate?'', stack: 'TimeoutError: timeout exceeded, event: 'run_#update - do we cancel timer properly on an immediate?_finished', test: '#update - do we cancel timer properly on an immediate?'
    at afterTimeout (/home/pi/Test/server_9004993954b94ec/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_9004993954b94ec/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-19 17:21:33 - ERROR HttpServer: 'unexpected server error: 'TimeoutError: timeout exceeded, event: 'run_#update - do we cancel timer properly on an immediate?_finished', test: '#update - do we cancel timer properly on an immediate?'''

2016-10-19 17:21:33 - ERROR HttpServer: 'unexpected server error: 'TimeoutError: timeout exceeded, event: 'run_#update - do we cancel timer properly on an immediate?_finished', test: '#update - do we cancel timer properly on an immediate?'''

2016-10-19 17:21:33 - ERROR HttpServer: 'unexpected server error: 'TimeoutError: timeout exceeded, event: 'run_#update - do we cancel timer properly on an immediate?_finished', test: '#update - do we cancel timer properly on an immediate?'''

2016-10-19 17:21:33 - ERROR UnitTestFramework: 'unexpected error: 'Error: TimeoutError: timeout exceeded, event: 'run_#update - do we cancel timer properly on an immediate?_finished', test: '#update - do we cancel timer properly on an immediate?'', stack: 'Error: TimeoutError: timeout exceeded, event: 'run_#update - do we cancel timer properly on an immediate?_finished', test: '#update - do we cancel timer properly on an immediate?'
    at Server._error (/home/pi/Test/server_9004993954b94ec/test/TestServer/HttpServer.js:77:9)
    at Socket.emit (events.js:82:17)
    at Socket.emit (/home/pi/Test/server_9004993954b94ec/test/TestServer/node_modules/socket.io/lib/socket.js:128:10)
    at updatedHandler (/home/pi/Test/server_9004993954b94ec/test/TestServer/Socket.js:103:29)
    at Socket._apply (/home/pi/Test/server_9004993954b94ec/test/TestServer/Socket.js:106:3)
    at emit (/home/pi/Test/server_9004993954b94ec/test/TestServer/Socket.js:165:22)
    at /home/pi/Test/server_9004993954b94ec/test/TestServer/Socket.js:169:5
    at Promise._execute (/home/pi/Test/server_9004993954b94ec/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_9004993954b94ec/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_9004993954b94ec/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Socket.emitData (/home/pi/Test/server_9004993954b94ec/test/TestServer/Socket.js:134:10)
    at TestDevice.error (/home/pi/Test/server_9004993954b94ec/test/TestServer/TestDevice.js:134:23)
    at /home/pi/Test/server_9004993954b94ec/test/TestServer/UnitTestFramework.js:89:23
    at Array.map (native)
    at /home/pi/Test/server_9004993954b94ec/test/TestServer/UnitTestFramework.js:88:15
    at tryCatcher (/home/pi/Test/server_9004993954b94ec/test/TestServer/node_modules/bluebird/js/release/util.js:16:23)''

2016-10-19 17:21:33 - ERROR UnitTestFramework: 'unexpected error: 'Error: TimeoutError: timeout exceeded, event: 'run_#update - do we cancel timer properly on an immediate?_finished', test: '#update - do we cancel timer properly on an immediate?'', stack: 'Error: TimeoutError: timeout exceeded, event: 'run_#update - do we cancel timer properly on an immediate?_finished', test: '#update - do we cancel timer properly on an immediate?'
    at Server._error (/home/pi/Test/server_9004993954b94ec/test/TestServer/HttpServer.js:77:9)
    at Socket.emit (events.js:82:17)
    at Socket.emit (/home/pi/Test/server_9004993954b94ec/test/TestServer/node_modules/socket.io/lib/socket.js:128:10)
    at updatedHandler (/home/pi/Test/server_9004993954b94ec/test/TestServer/Socket.js:103:29)
    at Socket._apply (/home/pi/Test/server_9004993954b94ec/test/TestServer/Socket.js:106:3)
    at emit (/home/pi/Test/server_9004993954b94ec/test/TestServer/Socket.js:165:22)
    at /home/pi/Test/server_9004993954b94ec/test/TestServer/Socket.js:169:5
    at Promise._execute (/home/pi/Test/server_9004993954b94ec/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_9004993954b94ec/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_9004993954b94ec/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Socket.emitData (/home/pi/Test/server_9004993954b94ec/test/TestServer/Socket.js:134:10)
    at TestDevice.error (/home/pi/Test/server_9004993954b94ec/test/TestServer/TestDevice.js:134:23)
    at /home/pi/Test/server_9004993954b94ec/test/TestServer/UnitTestFramework.js:89:23
    at Array.map (native)
    at /home/pi/Test/server_9004993954b94ec/test/TestServer/UnitTestFramework.js:88:15
    at tryCatcher (/home/pi/Test/server_9004993954b94ec/test/TestServer/node_modules/bluebird/js/release/util.js:16:23)''

2016-10-19 17:21:33 - ERROR UnitTestFramework: 'unexpected error: 'Error: TimeoutError: timeout exceeded, event: 'run_#update - do we cancel timer properly on an immediate?_finished', test: '#update - do we cancel timer properly on an immediate?'', stack: 'Error: TimeoutError: timeout exceeded, event: 'run_#update - do we cancel timer properly on an immediate?_finished', test: '#update - do we cancel timer properly on an immediate?'
    at Server._error (/home/pi/Test/server_9004993954b94ec/test/TestServer/HttpServer.js:77:9)
    at Socket.emit (events.js:82:17)
    at Socket.emit (/home/pi/Test/server_9004993954b94ec/test/TestServer/node_modules/socket.io/lib/socket.js:128:10)
    at updatedHandler (/home/pi/Test/server_9004993954b94ec/test/TestServer/Socket.js:103:29)
    at Socket._apply (/home/pi/Test/server_9004993954b94ec/test/TestServer/Socket.js:106:3)
    at emit (/home/pi/Test/server_9004993954b94ec/test/TestServer/Socket.js:165:22)
    at /home/pi/Test/server_9004993954b94ec/test/TestServer/Socket.js:169:5
    at Promise._execute (/home/pi/Test/server_9004993954b94ec/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_9004993954b94ec/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_9004993954b94ec/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Socket.emitData (/home/pi/Test/server_9004993954b94ec/test/TestServer/Socket.js:134:10)
    at TestDevice.error (/home/pi/Test/server_9004993954b94ec/test/TestServer/TestDevice.js:134:23)
    at /home/pi/Test/server_9004993954b94ec/test/TestServer/UnitTestFramework.js:89:23
    at Array.map (native)
    at /home/pi/Test/server_9004993954b94ec/test/TestServer/UnitTestFramework.js:88:15
    at tryCatcher (/home/pi/Test/server_9004993954b94ec/test/TestServer/node_modules/bluebird/js/release/util.js:16:23)''

2016-10-19 17:23:33 - DEBUG TestServer: 'completed'

2016-10-19 17:23:33 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!
```
###Android Logs
####Node name: thali05
Console output:
```
Stopping app on  ce0616068b9f212302
Uninstalling app on  ce0616068b9f212302
Stopping app on  ce061606e320561102
Uninstalling app on  ce061606e320561102
Stopping app on  ENU7N16516000107
Uninstalling app on  ENU7N16516000107

All devices are ready!

Deploying to ce0616068b9f212302
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce0616068b9f212302

Deploying to ce061606e320561102
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce061606e320561102

Deploying to ENU7N16516000107
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ENU7N16516000107

Starting application ThaliTest on ce0616068b9f212302

Starting application ThaliTest on ce061606e320561102

Starting application ThaliTest on ENU7N16516000107

App was succesfully started on ce0616068b9f212302

App was succesfully started on ce061606e320561102

App was succesfully started on ENU7N16516000107

STOP log received from ENU7N16516000107
Test has FAILED

STOP log received from ce061606e320561102
Test has FAILED

Device test finished on ENU7N16516000107 
Device test finished on ce061606e320561102 
STOP log received from ce0616068b9f212302
Test has SUCCEED

Device test finished on ce0616068b9f212302 
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/9004993954b94ec_Disable_not_local_installation_and_throw_an_error_in_other_case_larryonoff/thali05_samsung-SM-G930F.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/9004993954b94ec_Disable_not_local_installation_and_throw_an_error_in_other_case_larryonoff/thali05_samsung-SM-G935F.md)

[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/9004993954b94ec_Disable_not_local_installation_and_throw_an_error_in_other_case_larryonoff/thali05_Huawei-Nexus 6P.md)





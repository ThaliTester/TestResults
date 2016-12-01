#### Test 96008345c2441a7 Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-12-01 20:54:32 - INFO HttpServer: 'listening on *:3000'

2016-12-01 20:54:46 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '9c3be9b3-dfc6-46d4-9dc3-cd891584a94a', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-12-01 20:54:46 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2016-12-01 20:54:58 - DEBUG HttpServer: 'device presented, name: 'Huawei-Nexus 6P', uuid: 'f59521ed-6418-47fc-8a0c-c83fa6ac389e', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-12-01 20:54:58 - DEBUG TestFramework: 'device added, name: 'Huawei-Nexus 6P''

2016-12-01 20:56:16 - DEBUG HttpServer: 'device presented, name: 'Huawei-Nexus 6P', uuid: 'fa4f5248-66fc-4e10-b808-d4a95053fe70', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-12-01 20:56:16 - DEBUG TestFramework: 'device added, name: 'Huawei-Nexus 6P''

2016-12-01 20:56:16 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2016-12-01 20:56:16 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2016-12-01 20:56:16 - DEBUG UnitTestFramework: 'scheduling tests'

2016-12-01 20:56:17 - DEBUG UnitTestFramework: 'tests scheduled'

2016-12-01 20:56:17 - DEBUG UnitTestFramework: '#setup: 'calling createNativeListener directly rejects''

2016-12-01 20:56:17 - DEBUG UnitTestFramework: '#setup ok: 'calling createNativeListener directly rejects''

2016-12-01 20:56:17 - DEBUG UnitTestFramework: '#run: 'calling createNativeListener directly rejects''

2016-12-01 20:56:18 - DEBUG UnitTestFramework: '#run ok: 'calling createNativeListener directly rejects''

2016-12-01 20:56:18 - DEBUG UnitTestFramework: '#teardown: 'calling createNativeListener directly rejects''

2016-12-01 20:56:18 - DEBUG UnitTestFramework: '#teardown ok: 'calling createNativeListener directly rejects''

2016-12-01 20:56:18 - DEBUG UnitTestFramework: '#setup: 'emits incomingConnectionState''

2016-12-01 20:56:18 - DEBUG UnitTestFramework: '#setup ok: 'emits incomingConnectionState''

2016-12-01 20:56:18 - DEBUG UnitTestFramework: '#run: 'emits incomingConnectionState''

2016-12-01 20:56:18 - DEBUG UnitTestFramework: '#run ok: 'emits incomingConnectionState''

2016-12-01 20:56:18 - DEBUG UnitTestFramework: '#teardown: 'emits incomingConnectionState''

2016-12-01 20:56:18 - DEBUG UnitTestFramework: '#teardown ok: 'emits incomingConnectionState''

2016-12-01 20:56:18 - DEBUG UnitTestFramework: '#setup: 'emits routerPortConnectionFailed''

2016-12-01 20:56:18 - DEBUG UnitTestFramework: '#setup ok: 'emits routerPortConnectionFailed''

2016-12-01 20:56:18 - DEBUG UnitTestFramework: '#run: 'emits routerPortConnectionFailed''

2016-12-01 20:56:18 - DEBUG UnitTestFramework: '#run ok: 'emits routerPortConnectionFailed''

2016-12-01 20:56:18 - DEBUG UnitTestFramework: '#teardown: 'emits routerPortConnectionFailed''

2016-12-01 20:56:19 - DEBUG UnitTestFramework: '#teardown ok: 'emits routerPortConnectionFailed''

2016-12-01 20:56:19 - DEBUG UnitTestFramework: '#setup: 'native server connections all up''

2016-12-01 20:56:19 - DEBUG UnitTestFramework: '#setup ok: 'native server connections all up''

2016-12-01 20:56:19 - DEBUG UnitTestFramework: '#run: 'native server connections all up''

2016-12-01 20:56:19 - DEBUG UnitTestFramework: '#run ok: 'native server connections all up''

2016-12-01 20:56:19 - DEBUG UnitTestFramework: '#teardown: 'native server connections all up''

2016-12-01 20:56:19 - DEBUG UnitTestFramework: '#teardown ok: 'native server connections all up''

2016-12-01 20:56:19 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming stream cleans outgoing socket''

2016-12-01 20:56:19 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming stream cleans outgoing socket''

2016-12-01 20:56:19 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming stream cleans outgoing socket''

2016-12-01 20:56:19 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming stream cleans outgoing socket''

2016-12-01 20:56:19 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming stream cleans outgoing socket''

2016-12-01 20:56:19 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming stream cleans outgoing socket''

2016-12-01 20:56:19 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming connection cleans outgoing socket''

2016-12-01 20:56:19 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming connection cleans outgoing socket''

2016-12-01 20:56:19 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming connection cleans outgoing socket''

2016-12-01 20:56:19 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming connection cleans outgoing socket''

2016-12-01 20:56:19 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming connection cleans outgoing socket''

2016-12-01 20:56:19 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming connection cleans outgoing socket''

2016-12-01 20:56:19 - DEBUG UnitTestFramework: '#setup: 'native server - closing outgoing socket cleans associated mux stream''

2016-12-01 20:56:20 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-12-01 20:56:20 - DEBUG UnitTestFramework: '#run: 'native server - closing outgoing socket cleans associated mux stream''

2016-12-01 20:56:20 - DEBUG UnitTestFramework: '#run ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-12-01 20:56:20 - DEBUG UnitTestFramework: '#teardown: 'native server - closing outgoing socket cleans associated mux stream''

2016-12-01 20:56:20 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-12-01 20:56:20 - DEBUG UnitTestFramework: '#setup: 'native server - closing the whole server cleans everything up''

2016-12-01 20:56:20 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing the whole server cleans everything up''

2016-12-01 20:56:20 - DEBUG UnitTestFramework: '#run: 'native server - closing the whole server cleans everything up''

2016-12-01 20:56:20 - DEBUG UnitTestFramework: '#run ok: 'native server - closing the whole server cleans everything up''

2016-12-01 20:56:20 - DEBUG UnitTestFramework: '#teardown: 'native server - closing the whole server cleans everything up''

2016-12-01 20:56:20 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing the whole server cleans everything up''
2016-12-01 20:56:20 - DEBUG UnitTestFramework: '#setup: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-12-01 20:56:20 - DEBUG UnitTestFramework: '#setup ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-12-01 20:56:20 - DEBUG UnitTestFramework: '#run: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-12-01 20:56:20 - DEBUG UnitTestFramework: '#run ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-12-01 20:56:20 - DEBUG UnitTestFramework: '#teardown: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-12-01 20:56:22 - DEBUG UnitTestFramework: '#teardown ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-12-01 20:56:22 - DEBUG UnitTestFramework: '#setup: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-12-01 20:56:22 - DEBUG UnitTestFramework: '#setup ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-12-01 20:56:22 - DEBUG UnitTestFramework: '#run: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-12-01 20:56:22 - DEBUG UnitTestFramework: '#run ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-12-01 20:56:22 - DEBUG UnitTestFramework: '#teardown: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-12-01 20:56:22 - DEBUG UnitTestFramework: '#teardown ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-12-01 20:56:22 - DEBUG UnitTestFramework: '#setup: 'native server - timing out the incoming connection cleans everything up''

2016-12-01 20:56:23 - DEBUG UnitTestFramework: '#setup ok: 'native server - timing out the incoming connection cleans everything up''

2016-12-01 20:56:23 - DEBUG UnitTestFramework: '#run: 'native server - timing out the incoming connection cleans everything up''

2016-12-01 20:56:23 - DEBUG UnitTestFramework: '#run ok: 'native server - timing out the incoming connection cleans everything up''

2016-12-01 20:56:23 - DEBUG UnitTestFramework: '#teardown: 'native server - timing out the incoming connection cleans everything up''

2016-12-01 20:56:23 - DEBUG UnitTestFramework: '#teardown ok: 'native server - timing out the incoming connection cleans everything up''

2016-12-01 20:56:23 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server is not there''

2016-12-01 20:56:23 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server is not there''

2016-12-01 20:56:23 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server is not there''

2016-12-01 20:56:23 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server is not there''

2016-12-01 20:56:23 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server is not there''

2016-12-01 20:56:23 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server is not there''

2016-12-01 20:56:23 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-12-01 20:56:23 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-12-01 20:56:23 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-12-01 20:56:23 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-12-01 20:56:23 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-12-01 20:56:23 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-12-01 20:56:23 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server always returns 500''

2016-12-01 20:56:23 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-12-01 20:56:23 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server always returns 500''

2016-12-01 20:56:23 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-12-01 20:56:23 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server always returns 500''

2016-12-01 20:56:23 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-12-01 20:56:23 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - create new seq doc''

2016-12-01 20:56:24 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-12-01 20:56:24 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - create new seq doc''

2016-12-01 20:56:25 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-12-01 20:56:25 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - create new seq doc''

2016-12-01 20:56:26 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-12-01 20:56:26 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-12-01 20:56:26 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-12-01 20:56:26 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-12-01 20:56:27 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-12-01 20:56:27 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-12-01 20:56:27 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-12-01 20:56:27 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - update seq three times''

2016-12-01 20:56:27 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - update seq three times''

2016-12-01 20:56:27 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - update seq three times''

2016-12-01 20:56:28 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - update seq three times''

2016-12-01 20:56:28 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - update seq three times''

2016-12-01 20:56:29 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - update seq three times''

2016-12-01 20:56:29 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - rev got changed under us''

2016-12-01 20:56:29 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-12-01 20:56:29 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - rev got changed under us''

2016-12-01 20:56:30 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-12-01 20:56:30 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - rev got changed under us''

2016-12-01 20:56:30 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-12-01 20:56:30 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - fail if stop is called''

2016-12-01 20:56:30 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-12-01 20:56:30 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - fail if stop is called''

2016-12-01 20:56:30 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-12-01 20:56:30 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - fail if stop is called''

2016-12-01 20:56:30 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-12-01 20:56:30 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-12-01 20:56:30 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-12-01 20:56:30 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-12-01 20:56:30 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-12-01 20:56:30 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-12-01 20:56:30 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-12-01 20:56:30 - DEBUG UnitTestFramework: '#setup: '#update - fail if stop is called''

2016-12-01 20:56:30 - DEBUG UnitTestFramework: '#setup ok: '#update - fail if stop is called''

2016-12-01 20:56:30 - DEBUG UnitTestFramework: '#run: '#update - fail if stop is called''

2016-12-01 20:56:31 - DEBUG UnitTestFramework: '#run ok: '#update - fail if stop is called''

2016-12-01 20:56:31 - DEBUG UnitTestFramework: '#teardown: '#update - fail if stop is called''

2016-12-01 20:56:31 - DEBUG UnitTestFramework: '#teardown ok: '#update - fail if stop is called''

2016-12-01 20:56:31 - DEBUG UnitTestFramework: '#setup: '#update - set seq for first time''

2016-12-01 20:56:31 - DEBUG UnitTestFramework: '#setup ok: '#update - set seq for first time''

2016-12-01 20:56:31 - DEBUG UnitTestFramework: '#run: '#update - set seq for first time''

2016-12-01 20:56:31 - DEBUG UnitTestFramework: '#run ok: '#update - set seq for first time''

2016-12-01 20:56:31 - DEBUG UnitTestFramework: '#teardown: '#update - set seq for first time''

2016-12-01 20:56:31 - DEBUG UnitTestFramework: '#teardown ok: '#update - set seq for first time''

2016-12-01 20:56:31 - DEBUG UnitTestFramework: '#setup: '#update - Fail on bad seq value''

2016-12-01 20:56:31 - DEBUG UnitTestFramework: '#setup ok: '#update - Fail on bad seq value''

2016-12-01 20:56:31 - DEBUG UnitTestFramework: '#run: '#update - Fail on bad seq value''

2016-12-01 20:56:32 - DEBUG UnitTestFramework: '#run ok: '#update - Fail on bad seq value''

2016-12-01 20:56:32 - DEBUG UnitTestFramework: '#teardown: '#update - Fail on bad seq value''

2016-12-01 20:56:32 - DEBUG UnitTestFramework: '#teardown ok: '#update - Fail on bad seq value''

2016-12-01 20:56:32 - DEBUG UnitTestFramework: '#setup: '#update - do we cancel timer properly on an immediate?''

2016-12-01 20:56:32 - DEBUG UnitTestFramework: '#setup ok: '#update - do we cancel timer properly on an immediate?''

2016-12-01 20:56:32 - DEBUG UnitTestFramework: '#run: '#update - do we cancel timer properly on an immediate?''

2016-12-01 20:56:33 - DEBUG UnitTestFramework: '#run ok: '#update - do we cancel timer properly on an immediate?''

2016-12-01 20:56:33 - DEBUG UnitTestFramework: '#teardown: '#update - do we cancel timer properly on an immediate?''

2016-12-01 20:56:33 - DEBUG UnitTestFramework: '#teardown ok: '#update - do we cancel timer properly on an immediate?''

2016-12-01 20:56:33 - DEBUG UnitTestFramework: '#setup: '#update - do we wait for blocked update''

2016-12-01 20:56:33 - DEBUG UnitTestFramework: '#setup ok: '#update - do we wait for blocked update''

2016-12-01 20:56:33 - DEBUG UnitTestFramework: '#run: '#update - do we wait for blocked update''

2016-12-01 20:56:34 - DEBUG UnitTestFramework: '#run ok: '#update - do we wait for blocked update''

2016-12-01 20:56:34 - DEBUG UnitTestFramework: '#teardown: '#update - do we wait for blocked update''

2016-12-01 20:56:35 - DEBUG UnitTestFramework: '#teardown ok: '#update - do we wait for blocked update''

2016-12-01 20:56:35 - DEBUG UnitTestFramework: '#setup: '#update - test that we wait long enough''

2016-12-01 20:56:36 - DEBUG UnitTestFramework: '#setup ok: '#update - test that we wait long enough''

2016-12-01 20:56:36 - DEBUG UnitTestFramework: '#run: '#update - test that we wait long enough''

2016-12-01 20:56:37 - DEBUG UnitTestFramework: '#run ok: '#update - test that we wait long enough''

2016-12-01 20:56:37 - DEBUG UnitTestFramework: '#teardown: '#update - test that we wait long enough''

2016-12-01 20:56:37 - DEBUG UnitTestFramework: '#teardown ok: '#update - test that we wait long enough''

2016-12-01 20:56:37 - DEBUG UnitTestFramework: '#setup: '#update - test that we pick up new sequences while we wait''

2016-12-01 20:56:37 - DEBUG UnitTestFramework: '#setup ok: '#update - test that we pick up new sequences while we wait''

2016-12-01 20:56:37 - DEBUG UnitTestFramework: '#run: '#update - test that we pick up new sequences while we wait''

2016-12-01 20:56:39 - DEBUG UnitTestFramework: '#run ok: '#update - test that we pick up new sequences while we wait''

2016-12-01 20:56:39 - DEBUG UnitTestFramework: '#teardown: '#update - test that we pick up new sequences while we wait''

2016-12-01 20:56:40 - DEBUG UnitTestFramework: '#teardown ok: '#update - test that we pick up new sequences while we wait''

2016-12-01 20:56:40 - DEBUG UnitTestFramework: '#setup: 'Coordinated seq test''

2016-12-01 20:56:40 - DEBUG UnitTestFramework: '#setup ok: 'Coordinated seq test''

2016-12-01 20:56:40 - DEBUG UnitTestFramework: '#run: 'Coordinated seq test''

2016-12-01 20:57:43 - INFO HttpServer: 'Socket to device name: 'Huawei-Nexus 6P' disconnected, reason: 'client namespace disconnect''

2016-12-01 20:57:43 - INFO HttpServer: 'Socket to device name: 'Huawei-Nexus 6P' disconnected, reason: 'client namespace disconnect''

2016-12-01 20:59:40 - ERROR UnitTestFramework: '#run failed: 'Coordinated seq test', error: 'TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'', stack: 'TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'
    at afterTimeout (/home/pi/Test/server_96008345c2441a7/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_96008345c2441a7/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-12-01 20:59:40 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'android', error: 'TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'', stack: 'TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'
    at afterTimeout (/home/pi/Test/server_96008345c2441a7/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_96008345c2441a7/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-12-01 20:59:40 - ERROR HttpServer: 'unexpected server error: 'TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'''
2016-12-01 20:59:40 - ERROR HttpServer: 'unexpected server error: 'TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'''

2016-12-01 20:59:40 - ERROR HttpServer: 'unexpected server error: 'TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'''

2016-12-01 20:59:40 - ERROR UnitTestFramework: 'unexpected error: 'Error: TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'', stack: 'Error: TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'
    at Server._error (/home/pi/Test/server_96008345c2441a7/test/TestServer/HttpServer.js:77:9)
    at Socket.emit (events.js:82:17)
    at Socket.emit (/home/pi/Test/server_96008345c2441a7/test/TestServer/node_modules/socket.io/lib/socket.js:128:10)
    at updatedHandler (/home/pi/Test/server_96008345c2441a7/test/TestServer/Socket.js:103:29)
    at Socket._apply (/home/pi/Test/server_96008345c2441a7/test/TestServer/Socket.js:106:3)
    at emit (/home/pi/Test/server_96008345c2441a7/test/TestServer/Socket.js:165:22)
    at /home/pi/Test/server_96008345c2441a7/test/TestServer/Socket.js:169:5
    at Promise._execute (/home/pi/Test/server_96008345c2441a7/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_96008345c2441a7/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_96008345c2441a7/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Socket.emitData (/home/pi/Test/server_96008345c2441a7/test/TestServer/Socket.js:134:10)
    at TestDevice.error (/home/pi/Test/server_96008345c2441a7/test/TestServer/TestDevice.js:134:23)
    at /home/pi/Test/server_96008345c2441a7/test/TestServer/UnitTestFramework.js:87:23
    at Array.map (native)
    at /home/pi/Test/server_96008345c2441a7/test/TestServer/UnitTestFramework.js:86:15
    at tryCatcher (/home/pi/Test/server_96008345c2441a7/test/TestServer/node_modules/bluebird/js/release/util.js:16:23)''

2016-12-01 20:59:40 - ERROR UnitTestFramework: 'unexpected error: 'Error: TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'', stack: 'Error: TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'
    at Server._error (/home/pi/Test/server_96008345c2441a7/test/TestServer/HttpServer.js:77:9)
    at Socket.emit (events.js:82:17)
    at Socket.emit (/home/pi/Test/server_96008345c2441a7/test/TestServer/node_modules/socket.io/lib/socket.js:128:10)
    at updatedHandler (/home/pi/Test/server_96008345c2441a7/test/TestServer/Socket.js:103:29)
    at Socket._apply (/home/pi/Test/server_96008345c2441a7/test/TestServer/Socket.js:106:3)
    at emit (/home/pi/Test/server_96008345c2441a7/test/TestServer/Socket.js:165:22)
    at /home/pi/Test/server_96008345c2441a7/test/TestServer/Socket.js:169:5
    at Promise._execute (/home/pi/Test/server_96008345c2441a7/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_96008345c2441a7/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_96008345c2441a7/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Socket.emitData (/home/pi/Test/server_96008345c2441a7/test/TestServer/Socket.js:134:10)
    at TestDevice.error (/home/pi/Test/server_96008345c2441a7/test/TestServer/TestDevice.js:134:23)
    at /home/pi/Test/server_96008345c2441a7/test/TestServer/UnitTestFramework.js:87:23
    at Array.map (native)
    at /home/pi/Test/server_96008345c2441a7/test/TestServer/UnitTestFramework.js:86:15
    at tryCatcher (/home/pi/Test/server_96008345c2441a7/test/TestServer/node_modules/bluebird/js/release/util.js:16:23)''

2016-12-01 20:59:40 - ERROR UnitTestFramework: 'unexpected error: 'Error: TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'', stack: 'Error: TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'
    at Server._error (/home/pi/Test/server_96008345c2441a7/test/TestServer/HttpServer.js:77:9)
    at Socket.emit (events.js:82:17)
    at Socket.emit (/home/pi/Test/server_96008345c2441a7/test/TestServer/node_modules/socket.io/lib/socket.js:128:10)
    at updatedHandler (/home/pi/Test/server_96008345c2441a7/test/TestServer/Socket.js:103:29)
    at Socket._apply (/home/pi/Test/server_96008345c2441a7/test/TestServer/Socket.js:106:3)
    at emit (/home/pi/Test/server_96008345c2441a7/test/TestServer/Socket.js:165:22)
    at /home/pi/Test/server_96008345c2441a7/test/TestServer/Socket.js:169:5
    at Promise._execute (/home/pi/Test/server_96008345c2441a7/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_96008345c2441a7/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_96008345c2441a7/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Socket.emitData (/home/pi/Test/server_96008345c2441a7/test/TestServer/Socket.js:134:10)
    at TestDevice.error (/home/pi/Test/server_96008345c2441a7/test/TestServer/TestDevice.js:134:23)
    at /home/pi/Test/server_96008345c2441a7/test/TestServer/UnitTestFramework.js:87:23
    at Array.map (native)
    at /home/pi/Test/server_96008345c2441a7/test/TestServer/UnitTestFramework.js:86:15
    at tryCatcher (/home/pi/Test/server_96008345c2441a7/test/TestServer/node_modules/bluebird/js/release/util.js:16:23)''

2016-12-01 21:01:41 - DEBUG TestServer: 'completed'

2016-12-01 21:01:41 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''


 
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
Stopping app on  ce061606e320561102
Uninstalling app on  ce061606e320561102

All devices are ready!

Deploying to ce061606e320561102
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce061606e320561102

Starting application ThaliTest on ce061606e320561102

App was succesfully started on ce061606e320561102

STOP log received from ce061606e320561102
Test has SUCCEED

Device test finished on ce061606e320561102 
Android task is completed. [SUCCESS]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/96008345c2441a7__1588_Fixing_up_Android_buffer_problem_and_failing_tests_yaronyg/thali05_samsung-SM-G935F.md)

####Node name: thali06
Console output:
```
Stopping app on  ENU7N16516000107
Uninstalling app on  ENU7N16516000107

All devices are ready!

Deploying to ENU7N16516000107
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ENU7N16516000107

Starting application ThaliTest on ENU7N16516000107

App was succesfully started on ENU7N16516000107

STOP log received from ENU7N16516000107
Test has FAILED

Device test finished on ENU7N16516000107 
Android task is completed. [FAILED]
```
[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/96008345c2441a7__1588_Fixing_up_Android_buffer_problem_and_failing_tests_yaronyg/thali06_Huawei-Nexus 6P.md)

####Node name: thali07
Console output:
```
Stopping app on  ENU7N16516000121
Uninstalling app on  ENU7N16516000121

All devices are ready!

Deploying to ENU7N16516000121
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ENU7N16516000121

Starting application ThaliTest on ENU7N16516000121

App was succesfully started on ENU7N16516000121

STOP log received from ENU7N16516000121
Test has FAILED

Device test finished on ENU7N16516000121 
Android task is completed. [FAILED]
```
[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/96008345c2441a7__1588_Fixing_up_Android_buffer_problem_and_failing_tests_yaronyg/thali07_Huawei-Nexus 6P.md)





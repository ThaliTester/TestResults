#### Test 871194040e26dea Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-10-12 11:04:20 - INFO HttpServer: 'listening on *:3000'

2016-10-12 11:05:53 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '85e506a8-8b18-4857-8ab9-f921cc9ccf70', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-12 11:05:53 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2016-10-12 11:05:54 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '68b71745-b6cf-4151-80c1-f4f2ac3e7e78', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-12 11:05:54 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2016-10-12 11:06:13 - DEBUG HttpServer: 'device presented, name: 'Huawei-Nexus 6P', uuid: '9fd81b55-551a-4dc2-a3e1-8c6d053185bc', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-12 11:06:13 - DEBUG TestFramework: 'device added, name: 'Huawei-Nexus 6P''

2016-10-12 11:06:13 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2016-10-12 11:06:13 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2016-10-12 11:06:13 - DEBUG UnitTestFramework: 'scheduling tests'

2016-10-12 11:06:14 - DEBUG UnitTestFramework: 'tests scheduled'

2016-10-12 11:06:14 - DEBUG UnitTestFramework: '#setup: 'calling createNativeListener directly rejects''

2016-10-12 11:06:15 - DEBUG UnitTestFramework: '#setup ok: 'calling createNativeListener directly rejects''

2016-10-12 11:06:15 - DEBUG UnitTestFramework: '#run: 'calling createNativeListener directly rejects''

2016-10-12 11:06:15 - DEBUG UnitTestFramework: '#run ok: 'calling createNativeListener directly rejects''

2016-10-12 11:06:15 - DEBUG UnitTestFramework: '#teardown: 'calling createNativeListener directly rejects''

2016-10-12 11:06:15 - DEBUG UnitTestFramework: '#teardown ok: 'calling createNativeListener directly rejects''

2016-10-12 11:06:15 - DEBUG UnitTestFramework: '#setup: 'emits incomingConnectionState''

2016-10-12 11:06:15 - DEBUG UnitTestFramework: '#setup ok: 'emits incomingConnectionState''

2016-10-12 11:06:15 - DEBUG UnitTestFramework: '#run: 'emits incomingConnectionState''

2016-10-12 11:06:16 - DEBUG UnitTestFramework: '#run ok: 'emits incomingConnectionState''

2016-10-12 11:06:16 - DEBUG UnitTestFramework: '#teardown: 'emits incomingConnectionState''

2016-10-12 11:06:16 - DEBUG UnitTestFramework: '#teardown ok: 'emits incomingConnectionState''

2016-10-12 11:06:16 - DEBUG UnitTestFramework: '#setup: 'emits routerPortConnectionFailed''

2016-10-12 11:06:16 - DEBUG UnitTestFramework: '#setup ok: 'emits routerPortConnectionFailed''

2016-10-12 11:06:16 - DEBUG UnitTestFramework: '#run: 'emits routerPortConnectionFailed''

2016-10-12 11:06:17 - DEBUG UnitTestFramework: '#run ok: 'emits routerPortConnectionFailed''

2016-10-12 11:06:17 - DEBUG UnitTestFramework: '#teardown: 'emits routerPortConnectionFailed''

2016-10-12 11:06:17 - DEBUG UnitTestFramework: '#teardown ok: 'emits routerPortConnectionFailed''

2016-10-12 11:06:17 - DEBUG UnitTestFramework: '#setup: 'native server connections all up''

2016-10-12 11:06:17 - DEBUG UnitTestFramework: '#setup ok: 'native server connections all up''

2016-10-12 11:06:17 - DEBUG UnitTestFramework: '#run: 'native server connections all up''

2016-10-12 11:06:17 - DEBUG UnitTestFramework: '#run ok: 'native server connections all up''

2016-10-12 11:06:17 - DEBUG UnitTestFramework: '#teardown: 'native server connections all up''

2016-10-12 11:06:17 - DEBUG UnitTestFramework: '#teardown ok: 'native server connections all up''

2016-10-12 11:06:17 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming stream cleans outgoing socket''

2016-10-12 11:06:17 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming stream cleans outgoing socket''

2016-10-12 11:06:17 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming stream cleans outgoing socket''

2016-10-12 11:06:17 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming stream cleans outgoing socket''

2016-10-12 11:06:17 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming stream cleans outgoing socket''

2016-10-12 11:06:17 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming stream cleans outgoing socket''

2016-10-12 11:06:17 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming connection cleans outgoing socket''

2016-10-12 11:06:17 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming connection cleans outgoing socket''

2016-10-12 11:06:17 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming connection cleans outgoing socket''

2016-10-12 11:06:18 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming connection cleans outgoing socket''

2016-10-12 11:06:18 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming connection cleans outgoing socket''

2016-10-12 11:06:18 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming connection cleans outgoing socket''

2016-10-12 11:06:18 - DEBUG UnitTestFramework: '#setup: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-12 11:06:18 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-12 11:06:18 - DEBUG UnitTestFramework: '#run: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-12 11:06:18 - DEBUG UnitTestFramework: '#run ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-12 11:06:18 - DEBUG UnitTestFramework: '#teardown: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-12 11:06:18 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-12 11:06:18 - DEBUG UnitTestFramework: '#setup: 'native server - closing the whole server cleans everything up''

2016-10-12 11:06:18 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing the whole server cleans everything up''

2016-10-12 11:06:18 - DEBUG UnitTestFramework: '#run: 'native server - closing the whole server cleans everything up''

2016-10-12 11:06:18 - DEBUG UnitTestFramework: '#run ok: 'native server - closing the whole server cleans everything up''

2016-10-12 11:06:18 - DEBUG UnitTestFramework: '#teardown: 'native server - closing the whole server cleans everything up''

2016-10-12 11:06:18 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing the whole server cleans everything up''

2016-10-12 11:06:18 - DEBUG UnitTestFramework: '#setup: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-12 11:06:18 - DEBUG UnitTestFramework: '#setup ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-12 11:06:18 - DEBUG UnitTestFramework: '#run: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-12 11:06:19 - DEBUG UnitTestFramework: '#run ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-12 11:06:19 - DEBUG UnitTestFramework: '#teardown: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-12 11:06:20 - DEBUG UnitTestFramework: '#teardown ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-12 11:06:20 - DEBUG UnitTestFramework: '#setup: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-10-12 11:06:21 - DEBUG UnitTestFramework: '#setup ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-10-12 11:06:21 - DEBUG UnitTestFramework: '#run: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-10-12 11:06:22 - DEBUG UnitTestFramework: '#run ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-10-12 11:06:22 - DEBUG UnitTestFramework: '#teardown: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-10-12 11:06:22 - DEBUG UnitTestFramework: '#teardown ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-10-12 11:06:22 - DEBUG UnitTestFramework: '#setup: 'native server - timing out the incoming connection cleans everything up''

2016-10-12 11:06:23 - DEBUG UnitTestFramework: '#setup ok: 'native server - timing out the incoming connection cleans everything up''

2016-10-12 11:06:23 - DEBUG UnitTestFramework: '#run: 'native server - timing out the incoming connection cleans everything up''

2016-10-12 11:06:24 - DEBUG UnitTestFramework: '#run ok: 'native server - timing out the incoming connection cleans everything up''

2016-10-12 11:06:24 - DEBUG UnitTestFramework: '#teardown: 'native server - timing out the incoming connection cleans everything up''

2016-10-12 11:06:25 - DEBUG UnitTestFramework: '#teardown ok: 'native server - timing out the incoming connection cleans everything up''

2016-10-12 11:06:25 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server is not there''

2016-10-12 11:06:25 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server is not there''

2016-10-12 11:06:25 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server is not there''

2016-10-12 11:06:26 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server is not there''

2016-10-12 11:06:26 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server is not there''

2016-10-12 11:06:26 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server is not there''

2016-10-12 11:06:26 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-12 11:06:27 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-12 11:06:27 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-12 11:06:27 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-12 11:06:27 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-12 11:06:27 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-12 11:06:27 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-12 11:06:27 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-12 11:06:27 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-12 11:06:28 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-12 11:06:28 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-12 11:06:28 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-12 11:06:28 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-12 11:06:28 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-12 11:06:28 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-12 11:06:29 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-12 11:06:29 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-12 11:06:30 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-12 11:06:30 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-12 11:06:31 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-12 11:06:31 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-12 11:06:32 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-12 11:06:32 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-12 11:06:33 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-12 11:06:33 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - update seq three times''

2016-10-12 11:06:33 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - update seq three times''

2016-10-12 11:06:33 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - update seq three times''

2016-10-12 11:06:35 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - update seq three times''

2016-10-12 11:06:35 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - update seq three times''

2016-10-12 11:06:35 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - update seq three times''

2016-10-12 11:06:35 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-12 11:06:36 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-12 11:06:36 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-12 11:06:37 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-12 11:06:37 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-12 11:06:37 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-12 11:06:37 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-12 11:06:37 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-12 11:06:37 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-12 11:06:38 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-12 11:06:38 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-12 11:06:38 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-12 11:06:38 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-12 11:06:38 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-12 11:06:38 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-12 11:06:38 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-12 11:06:38 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-12 11:06:38 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-12 11:06:38 - DEBUG UnitTestFramework: '#setup: '#update - fail if stop is called''

2016-10-12 11:06:38 - DEBUG UnitTestFramework: '#setup ok: '#update - fail if stop is called''

2016-10-12 11:06:38 - DEBUG UnitTestFramework: '#run: '#update - fail if stop is called''

2016-10-12 11:06:38 - DEBUG UnitTestFramework: '#run ok: '#update - fail if stop is called''

2016-10-12 11:06:38 - DEBUG UnitTestFramework: '#teardown: '#update - fail if stop is called''

2016-10-12 11:06:38 - DEBUG UnitTestFramework: '#teardown ok: '#update - fail if stop is called''

2016-10-12 11:06:38 - DEBUG UnitTestFramework: '#setup: '#update - set seq for first time''

2016-10-12 11:06:38 - DEBUG UnitTestFramework: '#setup ok: '#update - set seq for first time''

2016-10-12 11:06:38 - DEBUG UnitTestFramework: '#run: '#update - set seq for first time''

2016-10-12 11:06:39 - DEBUG UnitTestFramework: '#run ok: '#update - set seq for first time''

2016-10-12 11:06:39 - DEBUG UnitTestFramework: '#teardown: '#update - set seq for first time''

2016-10-12 11:06:39 - DEBUG UnitTestFramework: '#teardown ok: '#update - set seq for first time''

2016-10-12 11:06:39 - DEBUG UnitTestFramework: '#setup: '#update - Fail on bad seq value''

2016-10-12 11:06:39 - DEBUG UnitTestFramework: '#setup ok: '#update - Fail on bad seq value''

2016-10-12 11:06:39 - DEBUG UnitTestFramework: '#run: '#update - Fail on bad seq value''

2016-10-12 11:06:40 - DEBUG UnitTestFramework: '#run ok: '#update - Fail on bad seq value''

2016-10-12 11:06:40 - DEBUG UnitTestFramework: '#teardown: '#update - Fail on bad seq value''

2016-10-12 11:06:40 - DEBUG UnitTestFramework: '#teardown ok: '#update - Fail on bad seq value''

2016-10-12 11:06:40 - DEBUG UnitTestFramework: '#setup: '#update - do we cancel timer properly on an immediate?''

2016-10-12 11:06:40 - DEBUG UnitTestFramework: '#setup ok: '#update - do we cancel timer properly on an immediate?''

2016-10-12 11:06:40 - DEBUG UnitTestFramework: '#run: '#update - do we cancel timer properly on an immediate?''

2016-10-12 11:06:42 - DEBUG UnitTestFramework: '#run ok: '#update - do we cancel timer properly on an immediate?''

2016-10-12 11:06:42 - DEBUG UnitTestFramework: '#teardown: '#update - do we cancel timer properly on an immediate?''

2016-10-12 11:06:44 - DEBUG UnitTestFramework: '#teardown ok: '#update - do we cancel timer properly on an immediate?''

2016-10-12 11:06:44 - DEBUG UnitTestFramework: '#setup: '#update - do we wait for blocked update''

2016-10-12 11:06:44 - DEBUG UnitTestFramework: '#setup ok: '#update - do we wait for blocked update''

2016-10-12 11:06:44 - DEBUG UnitTestFramework: '#run: '#update - do we wait for blocked update''

2016-10-12 11:06:45 - DEBUG UnitTestFramework: '#run ok: '#update - do we wait for blocked update''

2016-10-12 11:06:45 - DEBUG UnitTestFramework: '#teardown: '#update - do we wait for blocked update''

2016-10-12 11:06:46 - DEBUG UnitTestFramework: '#teardown ok: '#update - do we wait for blocked update''

2016-10-12 11:06:46 - DEBUG UnitTestFramework: '#setup: '#update - test that we wait long enough''

2016-10-12 11:06:47 - DEBUG UnitTestFramework: '#setup ok: '#update - test that we wait long enough''

2016-10-12 11:06:47 - DEBUG UnitTestFramework: '#run: '#update - test that we wait long enough''

2016-10-12 11:06:49 - DEBUG UnitTestFramework: '#run ok: '#update - test that we wait long enough''

2016-10-12 11:06:49 - DEBUG UnitTestFramework: '#teardown: '#update - test that we wait long enough''

2016-10-12 11:06:50 - DEBUG UnitTestFramework: '#teardown ok: '#update - test that we wait long enough''

2016-10-12 11:06:50 - DEBUG UnitTestFramework: '#setup: '#update - test that we pick up new sequences while we wait''

2016-10-12 11:06:51 - DEBUG UnitTestFramework: '#setup ok: '#update - test that we pick up new sequences while we wait''

2016-10-12 11:06:51 - DEBUG UnitTestFramework: '#run: '#update - test that we pick up new sequences while we wait''

2016-10-12 11:06:52 - DEBUG UnitTestFramework: '#run ok: '#update - test that we pick up new sequences while we wait''

2016-10-12 11:06:52 - DEBUG UnitTestFramework: '#teardown: '#update - test that we pick up new sequences while we wait''

2016-10-12 11:06:54 - DEBUG UnitTestFramework: '#teardown ok: '#update - test that we pick up new sequences while we wait''

2016-10-12 11:06:54 - DEBUG UnitTestFramework: '#setup: 'Coordinated seq test''

2016-10-12 11:06:55 - DEBUG UnitTestFramework: '#setup ok: 'Coordinated seq test''

2016-10-12 11:06:55 - DEBUG UnitTestFramework: '#run: 'Coordinated seq test''

2016-10-12 11:08:02 - INFO HttpServer: 'Socket to device name: 'Huawei-Nexus 6P' disconnected, reason: 'client namespace disconnect''

2016-10-12 11:09:55 - ERROR UnitTestFramework: '#run failed: 'Coordinated seq test', error: 'TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'', stack: 'TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'
    at afterTimeout (/home/pi/Test/server_871194040e26dea/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_871194040e26dea/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-12 11:09:55 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'android', error: 'TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'', stack: 'TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'
    at afterTimeout (/home/pi/Test/server_871194040e26dea/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_871194040e26dea/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-12 11:09:55 - ERROR HttpServer: 'unexpected server error: 'TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'''

2016-10-12 11:09:55 - ERROR HttpServer: 'unexpected server error: 'TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'''

2016-10-12 11:09:55 - ERROR HttpServer: 'unexpected server error: 'TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'''

2016-10-12 11:09:55 - ERROR UnitTestFramework: 'unexpected error: 'Error: TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'', stack: 'Error: TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'
    at Server._error (/home/pi/Test/server_871194040e26dea/test/TestServer/HttpServer.js:77:9)
    at Socket.emit (events.js:82:17)
    at Socket.emit (/home/pi/Test/server_871194040e26dea/test/TestServer/node_modules/socket.io/lib/socket.js:128:10)
    at updatedHandler (/home/pi/Test/server_871194040e26dea/test/TestServer/Socket.js:103:29)
    at Socket._apply (/home/pi/Test/server_871194040e26dea/test/TestServer/Socket.js:106:3)
    at emit (/home/pi/Test/server_871194040e26dea/test/TestServer/Socket.js:165:22)
    at /home/pi/Test/server_871194040e26dea/test/TestServer/Socket.js:169:5
    at Promise._execute (/home/pi/Test/server_871194040e26dea/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_871194040e26dea/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_871194040e26dea/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Socket.emitData (/home/pi/Test/server_871194040e26dea/test/TestServer/Socket.js:134:10)
    at TestDevice.error (/home/pi/Test/server_871194040e26dea/test/TestServer/TestDevice.js:134:23)
    at /home/pi/Test/server_871194040e26dea/test/TestServer/UnitTestFramework.js:89:23
    at Array.map (native)
    at /home/pi/Test/server_871194040e26dea/test/TestServer/UnitTestFramework.js:88:15
    at tryCatcher (/home/pi/Test/server_871194040e26dea/test/TestServer/node_modules/bluebird/js/release/util.js:16:23)''

2016-10-12 11:09:55 - ERROR UnitTestFramework: 'unexpected error: 'Error: TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'', stack: 'Error: TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'
    at Server._error (/home/pi/Test/server_871194040e26dea/test/TestServer/HttpServer.js:77:9)
    at Socket.emit (events.js:82:17)
    at Socket.emit (/home/pi/Test/server_871194040e26dea/test/TestServer/node_modules/socket.io/lib/socket.js:128:10)
    at updatedHandler (/home/pi/Test/server_871194040e26dea/test/TestServer/Socket.js:103:29)
    at Socket._apply (/home/pi/Test/server_871194040e26dea/test/TestServer/Socket.js:106:3)
    at emit (/home/pi/Test/server_871194040e26dea/test/TestServer/Socket.js:165:22)
    at /home/pi/Test/server_871194040e26dea/test/TestServer/Socket.js:169:5
    at Promise._execute (/home/pi/Test/server_871194040e26dea/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_871194040e26dea/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_871194040e26dea/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Socket.emitData (/home/pi/Test/server_871194040e26dea/test/TestServer/Socket.js:134:10)
    at TestDevice.error (/home/pi/Test/server_871194040e26dea/test/TestServer/TestDevice.js:134:23)
    at /home/pi/Test/server_871194040e26dea/test/TestServer/UnitTestFramework.js:89:23
    at Array.map (native)
    at /home/pi/Test/server_871194040e26dea/test/TestServer/UnitTestFramework.js:88:15
    at tryCatcher (/home/pi/Test/server_871194040e26dea/test/TestServer/node_modules/bluebird/js/release/util.js:16:23)''

2016-10-12 11:09:55 - ERROR UnitTestFramework: 'unexpected error: 'Error: TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'', stack: 'Error: TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'
    at Server._error (/home/pi/Test/server_871194040e26dea/test/TestServer/HttpServer.js:77:9)
    at Socket.emit (events.js:82:17)
    at Socket.emit (/home/pi/Test/server_871194040e26dea/test/TestServer/node_modules/socket.io/lib/socket.js:128:10)
    at updatedHandler (/home/pi/Test/server_871194040e26dea/test/TestServer/Socket.js:103:29)
    at Socket._apply (/home/pi/Test/server_871194040e26dea/test/TestServer/Socket.js:106:3)
    at emit (/home/pi/Test/server_871194040e26dea/test/TestServer/Socket.js:165:22)
    at /home/pi/Test/server_871194040e26dea/test/TestServer/Socket.js:169:5
    at Promise._execute (/home/pi/Test/server_871194040e26dea/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_871194040e26dea/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_871194040e26dea/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Socket.emitData (/home/pi/Test/server_871194040e26dea/test/TestServer/Socket.js:134:10)
    at TestDevice.error (/home/pi/Test/server_871194040e26dea/test/TestServer/TestDevice.js:134:23)
    at /home/pi/Test/server_871194040e26dea/test/TestServer/UnitTestFramework.js:89:23
    at Array.map (native)
    at /home/pi/Test/server_871194040e26dea/test/TestServer/UnitTestFramework.js:88:15
    at tryCatcher (/home/pi/Test/server_871194040e26dea/test/TestServer/node_modules/bluebird/js/release/util.js:16:23)''

2016-10-12 11:11:55 - DEBUG TestServer: 'completed'

2016-10-12 11:11:55 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2016-10-12 11:11:55 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''


 
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

Device test finished on ENU7N16516000107 
STOP log received from ce0616068b9f212302
Test has SUCCEED

STOP log received from ce061606e320561102
Test has SUCCEED

Device test finished on ce0616068b9f212302 
Device test finished on ce061606e320561102 
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/871194040e26dea_Move_off_JXcore_where_we_can_larryonoff/thali05_samsung-SM-G930F.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/871194040e26dea_Move_off_JXcore_where_we_can_larryonoff/thali05_samsung-SM-G935F.md)

[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/871194040e26dea_Move_off_JXcore_where_we_can_larryonoff/thali05_Huawei-Nexus 6P.md)





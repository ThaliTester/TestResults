#### Test 98694118426366f Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
10:35:51 Starting copy 1 [0m
10:35:52 Starting copy 2 [0m
10:35:52 Starting remote server [0m
09:35:52  start run remote
09:35:52  change tp server location
09:35:52  pkill
09:35:52  start js script
Thu Jan 05 2017 09:40:30 GMT+0000 (UTC) IS Running:
Thu Jan 05 2017 09:40:30 GMT+0000 (UTC) Running 'jx install'
Skipping the log for NPM since the exitCode was 0
Thu Jan 05 2017 09:41:55 GMT+0000 (UTC) > jx index.js {"devices":{"android":3}}
Thu Jan 05 2017 09:41:56 GMT+0000 (UTC) Run index.js
2017-01-05 09:42:01 - INFO HttpServer: 'listening on *:3000'

2017-01-05 09:42:07 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'f818203a-d80f-4774-b9e8-91e1afff21f1', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-01-05 09:42:07 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-01-05 09:42:08 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '55d2a696-bddd-400b-8bd7-768725aec4ae', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-01-05 09:42:08 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-01-05 09:43:37 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '6dbcfe13-616c-489d-8999-fe513520c4b6', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-01-05 09:43:37 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-01-05 09:43:37 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-01-05 09:43:37 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-01-05 09:43:37 - DEBUG UnitTestFramework: 'scheduling tests'

2017-01-05 09:43:38 - DEBUG UnitTestFramework: 'tests scheduled'

2017-01-05 09:43:38 - DEBUG UnitTestFramework: '#setup: 'calling createNativeListener directly rejects''

2017-01-05 09:43:38 - DEBUG UnitTestFramework: '#setup ok: 'calling createNativeListener directly rejects''

2017-01-05 09:43:38 - DEBUG UnitTestFramework: '#run: 'calling createNativeListener directly rejects''

2017-01-05 09:43:38 - DEBUG UnitTestFramework: '#run ok: 'calling createNativeListener directly rejects''

2017-01-05 09:43:38 - DEBUG UnitTestFramework: '#teardown: 'calling createNativeListener directly rejects''

2017-01-05 09:43:38 - DEBUG UnitTestFramework: '#teardown ok: 'calling createNativeListener directly rejects''

2017-01-05 09:43:38 - DEBUG UnitTestFramework: '#setup: 'emits incomingConnectionState''

2017-01-05 09:43:38 - DEBUG UnitTestFramework: '#setup ok: 'emits incomingConnectionState''

2017-01-05 09:43:38 - DEBUG UnitTestFramework: '#run: 'emits incomingConnectionState''

2017-01-05 09:43:38 - DEBUG UnitTestFramework: '#run ok: 'emits incomingConnectionState''

2017-01-05 09:43:38 - DEBUG UnitTestFramework: '#teardown: 'emits incomingConnectionState''

2017-01-05 09:43:38 - DEBUG UnitTestFramework: '#teardown ok: 'emits incomingConnectionState''

2017-01-05 09:43:38 - DEBUG UnitTestFramework: '#setup: 'emits routerPortConnectionFailed''

2017-01-05 09:43:38 - DEBUG UnitTestFramework: '#setup ok: 'emits routerPortConnectionFailed''

2017-01-05 09:43:38 - DEBUG UnitTestFramework: '#run: 'emits routerPortConnectionFailed''

2017-01-05 09:43:38 - DEBUG UnitTestFramework: '#run ok: 'emits routerPortConnectionFailed''

2017-01-05 09:43:38 - DEBUG UnitTestFramework: '#teardown: 'emits routerPortConnectionFailed''

2017-01-05 09:43:38 - DEBUG UnitTestFramework: '#teardown ok: 'emits routerPortConnectionFailed''

2017-01-05 09:43:38 - DEBUG UnitTestFramework: '#setup: 'native server connections all up''

2017-01-05 09:43:38 - DEBUG UnitTestFramework: '#setup ok: 'native server connections all up''

2017-01-05 09:43:38 - DEBUG UnitTestFramework: '#run: 'native server connections all up''

2017-01-05 09:43:39 - DEBUG UnitTestFramework: '#run ok: 'native server connections all up''

2017-01-05 09:43:39 - DEBUG UnitTestFramework: '#teardown: 'native server connections all up''

2017-01-05 09:43:39 - DEBUG UnitTestFramework: '#teardown ok: 'native server connections all up''

2017-01-05 09:43:39 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming stream cleans outgoing socket''

2017-01-05 09:43:39 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming stream cleans outgoing socket''

2017-01-05 09:43:39 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming stream cleans outgoing socket''

2017-01-05 09:43:39 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming stream cleans outgoing socket''

2017-01-05 09:43:39 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming stream cleans outgoing socket''

2017-01-05 09:43:39 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming stream cleans outgoing socket''

2017-01-05 09:43:39 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming connection cleans outgoing socket''

2017-01-05 09:43:39 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming connection cleans outgoing socket''

2017-01-05 09:43:39 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming connection cleans outgoing socket''

2017-01-05 09:43:39 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming connection cleans outgoing socket''

2017-01-05 09:43:39 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming connection cleans outgoing socket''

2017-01-05 09:43:39 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming connection cleans outgoing socket''

2017-01-05 09:43:39 - DEBUG UnitTestFramework: '#setup: 'native server - closing outgoing socket cleans associated mux stream''

2017-01-05 09:43:39 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing outgoing socket cleans associated mux stream''

2017-01-05 09:43:39 - DEBUG UnitTestFramework: '#run: 'native server - closing outgoing socket cleans associated mux stream''

2017-01-05 09:43:39 - DEBUG UnitTestFramework: '#run ok: 'native server - closing outgoing socket cleans associated mux stream''

2017-01-05 09:43:39 - DEBUG UnitTestFramework: '#teardown: 'native server - closing outgoing socket cleans associated mux stream''

2017-01-05 09:43:39 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing outgoing socket cleans associated mux stream''

2017-01-05 09:43:39 - DEBUG UnitTestFramework: '#setup: 'native server - closing the whole server cleans everything up''

2017-01-05 09:43:39 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing the whole server cleans everything up''

2017-01-05 09:43:39 - DEBUG UnitTestFramework: '#run: 'native server - closing the whole server cleans everything up''

2017-01-05 09:43:39 - DEBUG UnitTestFramework: '#run ok: 'native server - closing the whole server cleans everything up''

2017-01-05 09:43:39 - DEBUG UnitTestFramework: '#teardown: 'native server - closing the whole server cleans everything up''

2017-01-05 09:43:39 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing the whole server cleans everything up''

2017-01-05 09:43:39 - DEBUG UnitTestFramework: '#setup: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-01-05 09:43:40 - DEBUG UnitTestFramework: '#setup ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-01-05 09:43:40 - DEBUG UnitTestFramework: '#run: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-01-05 09:43:40 - DEBUG UnitTestFramework: '#run ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-01-05 09:43:40 - DEBUG UnitTestFramework: '#teardown: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-01-05 09:43:42 - DEBUG UnitTestFramework: '#teardown ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-01-05 09:43:42 - DEBUG UnitTestFramework: '#setup: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-01-05 09:43:42 - DEBUG UnitTestFramework: '#setup ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-01-05 09:43:42 - DEBUG UnitTestFramework: '#run: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-01-05 09:43:42 - DEBUG UnitTestFramework: '#run ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-01-05 09:43:42 - DEBUG UnitTestFramework: '#teardown: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-01-05 09:43:42 - DEBUG UnitTestFramework: '#teardown ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-01-05 09:43:42 - DEBUG UnitTestFramework: '#setup: 'native server - timing out the incoming connection cleans everything up''

2017-01-05 09:43:42 - DEBUG UnitTestFramework: '#setup ok: 'native server - timing out the incoming connection cleans everything up''

2017-01-05 09:43:42 - DEBUG UnitTestFramework: '#run: 'native server - timing out the incoming connection cleans everything up''

2017-01-05 09:43:42 - DEBUG UnitTestFramework: '#run ok: 'native server - timing out the incoming connection cleans everything up''

2017-01-05 09:43:42 - DEBUG UnitTestFramework: '#teardown: 'native server - timing out the incoming connection cleans everything up''

2017-01-05 09:43:42 - DEBUG UnitTestFramework: '#teardown ok: 'native server - timing out the incoming connection cleans everything up''

2017-01-05 09:43:42 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server is not there''

2017-01-05 09:43:42 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server is not there''

2017-01-05 09:43:42 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server is not there''

2017-01-05 09:43:42 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server is not there''

2017-01-05 09:43:42 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server is not there''

2017-01-05 09:43:42 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server is not there''

2017-01-05 09:43:42 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server accepts & closes connection''

2017-01-05 09:43:42 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2017-01-05 09:43:42 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server accepts & closes connection''

2017-01-05 09:43:42 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2017-01-05 09:43:42 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server accepts & closes connection''

2017-01-05 09:43:43 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2017-01-05 09:43:43 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server always returns 500''

2017-01-05 09:43:43 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server always returns 500''

2017-01-05 09:43:43 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server always returns 500''

2017-01-05 09:43:43 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server always returns 500''

2017-01-05 09:43:43 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server always returns 500''

2017-01-05 09:43:43 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server always returns 500''

2017-01-05 09:43:43 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - create new seq doc''

2017-01-05 09:43:43 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - create new seq doc''

2017-01-05 09:43:43 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - create new seq doc''

2017-01-05 09:43:45 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - create new seq doc''

2017-01-05 09:43:45 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - create new seq doc''

2017-01-05 09:43:45 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - create new seq doc''

2017-01-05 09:43:45 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2017-01-05 09:43:45 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2017-01-05 09:43:45 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2017-01-05 09:43:45 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2017-01-05 09:43:45 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2017-01-05 09:43:45 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2017-01-05 09:43:46 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - update seq three times''

2017-01-05 09:43:46 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - update seq three times''

2017-01-05 09:43:46 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - update seq three times''

2017-01-05 09:43:46 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - update seq three times''

2017-01-05 09:43:46 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - update seq three times''

2017-01-05 09:43:46 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - update seq three times''

2017-01-05 09:43:46 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - rev got changed under us''

2017-01-05 09:43:46 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - rev got changed under us''

2017-01-05 09:43:46 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - rev got changed under us''

2017-01-05 09:43:48 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - rev got changed under us''

2017-01-05 09:43:48 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - rev got changed under us''

2017-01-05 09:43:48 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - rev got changed under us''

2017-01-05 09:43:48 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - fail if stop is called''

2017-01-05 09:43:48 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - fail if stop is called''

2017-01-05 09:43:48 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - fail if stop is called''

2017-01-05 09:43:48 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - fail if stop is called''

2017-01-05 09:43:48 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - fail if stop is called''

2017-01-05 09:43:48 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - fail if stop is called''

2017-01-05 09:43:48 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2017-01-05 09:43:48 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2017-01-05 09:43:48 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2017-01-05 09:43:48 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2017-01-05 09:43:48 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2017-01-05 09:43:48 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2017-01-05 09:43:48 - DEBUG UnitTestFramework: '#setup: '#update - fail if stop is called''

2017-01-05 09:43:48 - DEBUG UnitTestFramework: '#setup ok: '#update - fail if stop is called''

2017-01-05 09:43:48 - DEBUG UnitTestFramework: '#run: '#update - fail if stop is called''

2017-01-05 09:43:49 - DEBUG UnitTestFramework: '#run ok: '#update - fail if stop is called''

2017-01-05 09:43:49 - DEBUG UnitTestFramework: '#teardown: '#update - fail if stop is called''

2017-01-05 09:43:49 - DEBUG UnitTestFramework: '#teardown ok: '#update - fail if stop is called''

2017-01-05 09:43:49 - DEBUG UnitTestFramework: '#setup: '#update - set seq for first time''

2017-01-05 09:43:49 - DEBUG UnitTestFramework: '#setup ok: '#update - set seq for first time''

2017-01-05 09:43:49 - DEBUG UnitTestFramework: '#run: '#update - set seq for first time''

2017-01-05 09:43:49 - DEBUG UnitTestFramework: '#run ok: '#update - set seq for first time''

2017-01-05 09:43:49 - DEBUG UnitTestFramework: '#teardown: '#update - set seq for first time''

2017-01-05 09:43:50 - DEBUG UnitTestFramework: '#teardown ok: '#update - set seq for first time''

2017-01-05 09:43:50 - DEBUG UnitTestFramework: '#setup: '#update - Fail on bad seq value''

2017-01-05 09:43:50 - DEBUG UnitTestFramework: '#setup ok: '#update - Fail on bad seq value''

2017-01-05 09:43:50 - DEBUG UnitTestFramework: '#run: '#update - Fail on bad seq value''

2017-01-05 09:43:50 - DEBUG UnitTestFramework: '#run ok: '#update - Fail on bad seq value''

2017-01-05 09:43:50 - DEBUG UnitTestFramework: '#teardown: '#update - Fail on bad seq value''

2017-01-05 09:43:50 - DEBUG UnitTestFramework: '#teardown ok: '#update - Fail on bad seq value''

2017-01-05 09:43:50 - DEBUG UnitTestFramework: '#setup: '#update - do we cancel timer properly on an immediate?''

2017-01-05 09:43:50 - DEBUG UnitTestFramework: '#setup ok: '#update - do we cancel timer properly on an immediate?''

2017-01-05 09:43:50 - DEBUG UnitTestFramework: '#run: '#update - do we cancel timer properly on an immediate?''

2017-01-05 09:43:51 - DEBUG UnitTestFramework: '#run ok: '#update - do we cancel timer properly on an immediate?''

2017-01-05 09:43:51 - DEBUG UnitTestFramework: '#teardown: '#update - do we cancel timer properly on an immediate?''

2017-01-05 09:43:52 - DEBUG UnitTestFramework: '#teardown ok: '#update - do we cancel timer properly on an immediate?''

2017-01-05 09:43:52 - DEBUG UnitTestFramework: '#setup: '#update - do we wait for blocked update''

2017-01-05 09:43:52 - DEBUG UnitTestFramework: '#setup ok: '#update - do we wait for blocked update''

2017-01-05 09:43:52 - DEBUG UnitTestFramework: '#run: '#update - do we wait for blocked update''

2017-01-05 09:43:53 - DEBUG UnitTestFramework: '#run ok: '#update - do we wait for blocked update''

2017-01-05 09:43:53 - DEBUG UnitTestFramework: '#teardown: '#update - do we wait for blocked update''

2017-01-05 09:43:53 - DEBUG UnitTestFramework: '#teardown ok: '#update - do we wait for blocked update''

2017-01-05 09:43:53 - DEBUG UnitTestFramework: '#setup: '#update - test that we wait long enough''

2017-01-05 09:43:53 - DEBUG UnitTestFramework: '#setup ok: '#update - test that we wait long enough''

2017-01-05 09:43:53 - DEBUG UnitTestFramework: '#run: '#update - test that we wait long enough''

2017-01-05 09:43:55 - DEBUG UnitTestFramework: '#run ok: '#update - test that we wait long enough''

2017-01-05 09:43:55 - DEBUG UnitTestFramework: '#teardown: '#update - test that we wait long enough''

2017-01-05 09:43:56 - DEBUG UnitTestFramework: '#teardown ok: '#update - test that we wait long enough''

2017-01-05 09:43:56 - DEBUG UnitTestFramework: '#setup: '#update - test that we pick up new sequences while we wait''

2017-01-05 09:43:56 - DEBUG UnitTestFramework: '#setup ok: '#update - test that we pick up new sequences while we wait''

2017-01-05 09:43:56 - DEBUG UnitTestFramework: '#run: '#update - test that we pick up new sequences while we wait''

2017-01-05 09:43:58 - DEBUG UnitTestFramework: '#run ok: '#update - test that we pick up new sequences while we wait''

2017-01-05 09:43:58 - DEBUG UnitTestFramework: '#teardown: '#update - test that we pick up new sequences while we wait''

2017-01-05 09:43:58 - DEBUG UnitTestFramework: '#teardown ok: '#update - test that we pick up new sequences while we wait''

2017-01-05 09:43:58 - DEBUG UnitTestFramework: '#setup: 'Coordinated seq test''

2017-01-05 09:43:58 - DEBUG UnitTestFramework: '#setup ok: 'Coordinated seq test''

2017-01-05 09:43:58 - DEBUG UnitTestFramework: '#run: 'Coordinated seq test''

2017-01-05 09:46:58 - ERROR UnitTestFramework: '#run failed: 'Coordinated seq test', error: 'TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'', stack: 'TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'
    at afterTimeout (/home/pi/Test/server_98694118426366f/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_98694118426366f/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-01-05 09:46:58 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'android', error: 'TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'', stack: 'TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'
    at afterTimeout (/home/pi/Test/server_98694118426366f/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_98694118426366f/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-01-05 09:46:58 - ERROR HttpServer: 'unexpected server error: 'TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'''

2017-01-05 09:46:58 - ERROR HttpServer: 'unexpected server error: 'TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'''

2017-01-05 09:46:58 - ERROR HttpServer: 'unexpected server error: 'TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'''

2017-01-05 09:46:58 - ERROR UnitTestFramework: 'unexpected error: 'Error: TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'', stack: 'Error: TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'
    at Server._error (/home/pi/Test/server_98694118426366f/test/TestServer/HttpServer.js:77:9)
    at Socket.emit (events.js:82:17)
    at Socket.emit (/home/pi/Test/server_98694118426366f/test/TestServer/node_modules/socket.io/lib/socket.js:128:10)
    at updatedHandler (/home/pi/Test/server_98694118426366f/test/TestServer/Socket.js:103:29)
    at Socket._apply (/home/pi/Test/server_98694118426366f/test/TestServer/Socket.js:106:3)
    at emit (/home/pi/Test/server_98694118426366f/test/TestServer/Socket.js:165:22)
    at /home/pi/Test/server_98694118426366f/test/TestServer/Socket.js:169:5
    at Promise._execute (/home/pi/Test/server_98694118426366f/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_98694118426366f/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_98694118426366f/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Socket.emitData (/home/pi/Test/server_98694118426366f/test/TestServer/Socket.js:134:10)
    at TestDevice.error (/home/pi/Test/server_98694118426366f/test/TestServer/TestDevice.js:134:23)
    at /home/pi/Test/server_98694118426366f/test/TestServer/UnitTestFramework.js:87:23
    at Array.map (native)
    at /home/pi/Test/server_98694118426366f/test/TestServer/UnitTestFramework.js:86:15
    at tryCatcher (/home/pi/Test/server_98694118426366f/test/TestServer/node_modules/bluebird/js/release/util.js:16:23)''

2017-01-05 09:46:58 - ERROR UnitTestFramework: 'unexpected error: 'Error: TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'', stack: 'Error: TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'
    at Server._error (/home/pi/Test/server_98694118426366f/test/TestServer/HttpServer.js:77:9)
    at Socket.emit (events.js:82:17)
    at Socket.emit (/home/pi/Test/server_98694118426366f/test/TestServer/node_modules/socket.io/lib/socket.js:128:10)
    at updatedHandler (/home/pi/Test/server_98694118426366f/test/TestServer/Socket.js:103:29)
    at Socket._apply (/home/pi/Test/server_98694118426366f/test/TestServer/Socket.js:106:3)
    at emit (/home/pi/Test/server_98694118426366f/test/TestServer/Socket.js:165:22)
    at /home/pi/Test/server_98694118426366f/test/TestServer/Socket.js:169:5
    at Promise._execute (/home/pi/Test/server_98694118426366f/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_98694118426366f/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_98694118426366f/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Socket.emitData (/home/pi/Test/server_98694118426366f/test/TestServer/Socket.js:134:10)
    at TestDevice.error (/home/pi/Test/server_98694118426366f/test/TestServer/TestDevice.js:134:23)
    at /home/pi/Test/server_98694118426366f/test/TestServer/UnitTestFramework.js:87:23
    at Array.map (native)
    at /home/pi/Test/server_98694118426366f/test/TestServer/UnitTestFramework.js:86:15
    at tryCatcher (/home/pi/Test/server_98694118426366f/test/TestServer/node_modules/bluebird/js/release/util.js:16:23)''

2017-01-05 09:46:58 - ERROR UnitTestFramework: 'unexpected error: 'Error: TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'', stack: 'Error: TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'
    at Server._error (/home/pi/Test/server_98694118426366f/test/TestServer/HttpServer.js:77:9)
    at Socket.emit (events.js:82:17)
    at Socket.emit (/home/pi/Test/server_98694118426366f/test/TestServer/node_modules/socket.io/lib/socket.js:128:10)
    at updatedHandler (/home/pi/Test/server_98694118426366f/test/TestServer/Socket.js:103:29)
    at Socket._apply (/home/pi/Test/server_98694118426366f/test/TestServer/Socket.js:106:3)
    at emit (/home/pi/Test/server_98694118426366f/test/TestServer/Socket.js:165:22)
    at /home/pi/Test/server_98694118426366f/test/TestServer/Socket.js:169:5
    at Promise._execute (/home/pi/Test/server_98694118426366f/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_98694118426366f/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_98694118426366f/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Socket.emitData (/home/pi/Test/server_98694118426366f/test/TestServer/Socket.js:134:10)
    at TestDevice.error (/home/pi/Test/server_98694118426366f/test/TestServer/TestDevice.js:134:23)
    at /home/pi/Test/server_98694118426366f/test/TestServer/UnitTestFramework.js:87:23
    at Array.map (native)
    at /home/pi/Test/server_98694118426366f/test/TestServer/UnitTestFramework.js:86:15
    at tryCatcher (/home/pi/Test/server_98694118426366f/test/TestServer/node_modules/bluebird/js/release/util.js:16:23)''

2017-01-05 09:46:58 - DEBUG TestServer: 'completed'

2017-01-05 09:46:58 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-01-05 09:46:58 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-01-05 09:46:58 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''

[0;31merror: command 'sudo jx ______.js android' failed with code 1, file 'bash' on line 35[0m
One or more Android tests are failed.
 [0m
index.js failed [ 1 ]

```


Logs for system : 
```

android : No Error
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
Test has SUCCEED

Device test finished on ce0616068b9f212302 
Android task is completed. [SUCCESS]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/98694118426366f_CI_sanity_check_czyzm/thali02_samsung-SM-G930F.md)

####Node name: thali03
Console output:
```
Stopping app on  ce061606c181d71003
Uninstalling app on  ce061606c181d71003

All devices are ready!

Deploying to ce061606c181d71003
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce061606c181d71003

Starting application ThaliTest on ce061606c181d71003

App was succesfully started on ce061606c181d71003

STOP log received from ce061606c181d71003
Test has SUCCEED

Device test finished on ce061606c181d71003 
Android task is completed. [SUCCESS]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/98694118426366f_CI_sanity_check_czyzm/thali03_samsung-SM-G930F.md)

####Node name: thali04
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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/98694118426366f_CI_sanity_check_czyzm/thali04_samsung-SM-G935F.md)



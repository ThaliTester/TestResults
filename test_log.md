#### Test 986941187d5d37b Logs

#### Test Server Logs
```
Error: Command failed: jx install failed [ 1 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-12-22 08:03:26 - INFO HttpServer: 'listening on *:3000'

2016-12-22 08:03:42 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '5af90bf2-fae9-4f81-b274-18e9efa6ee3c', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-12-22 08:03:42 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2016-12-22 08:03:44 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'eea0df94-e4bf-4108-8283-5930434e841c', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-12-22 08:03:44 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2016-12-22 08:05:03 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '94266e09-f3ac-4cb1-998a-83e69ff319f1', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-12-22 08:05:03 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2016-12-22 08:05:03 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2016-12-22 08:05:03 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2016-12-22 08:05:03 - DEBUG UnitTestFramework: 'scheduling tests'

2016-12-22 08:05:03 - DEBUG UnitTestFramework: 'tests scheduled'

2016-12-22 08:05:03 - DEBUG UnitTestFramework: '#setup: 'calling createNativeListener directly rejects''

2016-12-22 08:05:04 - DEBUG UnitTestFramework: '#setup ok: 'calling createNativeListener directly rejects''

2016-12-22 08:05:04 - DEBUG UnitTestFramework: '#run: 'calling createNativeListener directly rejects''

2016-12-22 08:05:04 - DEBUG UnitTestFramework: '#run ok: 'calling createNativeListener directly rejects''

2016-12-22 08:05:04 - DEBUG UnitTestFramework: '#teardown: 'calling createNativeListener directly rejects''

2016-12-22 08:05:04 - DEBUG UnitTestFramework: '#teardown ok: 'calling createNativeListener directly rejects''

2016-12-22 08:05:04 - DEBUG UnitTestFramework: '#setup: 'emits incomingConnectionState''

2016-12-22 08:05:04 - DEBUG UnitTestFramework: '#setup ok: 'emits incomingConnectionState''

2016-12-22 08:05:04 - DEBUG UnitTestFramework: '#run: 'emits incomingConnectionState''

2016-12-22 08:05:04 - DEBUG UnitTestFramework: '#run ok: 'emits incomingConnectionState''

2016-12-22 08:05:04 - DEBUG UnitTestFramework: '#teardown: 'emits incomingConnectionState''

2016-12-22 08:05:04 - DEBUG UnitTestFramework: '#teardown ok: 'emits incomingConnectionState''

2016-12-22 08:05:04 - DEBUG UnitTestFramework: '#setup: 'emits routerPortConnectionFailed''

2016-12-22 08:05:04 - DEBUG UnitTestFramework: '#setup ok: 'emits routerPortConnectionFailed''

2016-12-22 08:05:04 - DEBUG UnitTestFramework: '#run: 'emits routerPortConnectionFailed''

2016-12-22 08:05:04 - DEBUG UnitTestFramework: '#run ok: 'emits routerPortConnectionFailed''

2016-12-22 08:05:04 - DEBUG UnitTestFramework: '#teardown: 'emits routerPortConnectionFailed''

2016-12-22 08:05:04 - DEBUG UnitTestFramework: '#teardown ok: 'emits routerPortConnectionFailed''

2016-12-22 08:05:04 - DEBUG UnitTestFramework: '#setup: 'native server connections all up''

2016-12-22 08:05:04 - DEBUG UnitTestFramework: '#setup ok: 'native server connections all up''

2016-12-22 08:05:04 - DEBUG UnitTestFramework: '#run: 'native server connections all up''

2016-12-22 08:05:04 - DEBUG UnitTestFramework: '#run ok: 'native server connections all up''

2016-12-22 08:05:04 - DEBUG UnitTestFramework: '#teardown: 'native server connections all up''

2016-12-22 08:05:04 - DEBUG UnitTestFramework: '#teardown ok: 'native server connections all up''

2016-12-22 08:05:04 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming stream cleans outgoing socket''

2016-12-22 08:05:04 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming stream cleans outgoing socket''

2016-12-22 08:05:04 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming stream cleans outgoing socket''

2016-12-22 08:05:05 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming stream cleans outgoing socket''

2016-12-22 08:05:05 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming stream cleans outgoing socket''

2016-12-22 08:05:05 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming stream cleans outgoing socket''

2016-12-22 08:05:05 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming connection cleans outgoing socket''

2016-12-22 08:05:05 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming connection cleans outgoing socket''

2016-12-22 08:05:05 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming connection cleans outgoing socket''

2016-12-22 08:05:05 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming connection cleans outgoing socket''

2016-12-22 08:05:05 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming connection cleans outgoing socket''

2016-12-22 08:05:05 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming connection cleans outgoing socket''

2016-12-22 08:05:05 - DEBUG UnitTestFramework: '#setup: 'native server - closing outgoing socket cleans associated mux stream''

2016-12-22 08:05:05 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-12-22 08:05:05 - DEBUG UnitTestFramework: '#run: 'native server - closing outgoing socket cleans associated mux stream''

2016-12-22 08:05:05 - DEBUG UnitTestFramework: '#run ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-12-22 08:05:05 - DEBUG UnitTestFramework: '#teardown: 'native server - closing outgoing socket cleans associated mux stream''

2016-12-22 08:05:05 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-12-22 08:05:05 - DEBUG UnitTestFramework: '#setup: 'native server - closing the whole server cleans everything up''

2016-12-22 08:05:05 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing the whole server cleans everything up''

2016-12-22 08:05:05 - DEBUG UnitTestFramework: '#run: 'native server - closing the whole server cleans everything up''

2016-12-22 08:05:05 - DEBUG UnitTestFramework: '#run ok: 'native server - closing the whole server cleans everything up''

2016-12-22 08:05:05 - DEBUG UnitTestFramework: '#teardown: 'native server - closing the whole server cleans everything up''

2016-12-22 08:05:05 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing the whole server cleans everything up''
2016-12-22 08:05:05 - DEBUG UnitTestFramework: '#setup: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-12-22 08:05:05 - DEBUG UnitTestFramework: '#setup ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-12-22 08:05:05 - DEBUG UnitTestFramework: '#run: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-12-22 08:05:06 - DEBUG UnitTestFramework: '#run ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-12-22 08:05:06 - DEBUG UnitTestFramework: '#teardown: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-12-22 08:05:07 - DEBUG UnitTestFramework: '#teardown ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-12-22 08:05:07 - DEBUG UnitTestFramework: '#setup: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-12-22 08:05:07 - DEBUG UnitTestFramework: '#setup ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-12-22 08:05:07 - DEBUG UnitTestFramework: '#run: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-12-22 08:05:07 - DEBUG UnitTestFramework: '#run ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-12-22 08:05:07 - DEBUG UnitTestFramework: '#teardown: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-12-22 08:05:07 - DEBUG UnitTestFramework: '#teardown ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-12-22 08:05:07 - DEBUG UnitTestFramework: '#setup: 'native server - timing out the incoming connection cleans everything up''

2016-12-22 08:05:07 - DEBUG UnitTestFramework: '#setup ok: 'native server - timing out the incoming connection cleans everything up''

2016-12-22 08:05:07 - DEBUG UnitTestFramework: '#run: 'native server - timing out the incoming connection cleans everything up''

2016-12-22 08:05:07 - DEBUG UnitTestFramework: '#run ok: 'native server - timing out the incoming connection cleans everything up''

2016-12-22 08:05:07 - DEBUG UnitTestFramework: '#teardown: 'native server - timing out the incoming connection cleans everything up''

2016-12-22 08:05:07 - DEBUG UnitTestFramework: '#teardown ok: 'native server - timing out the incoming connection cleans everything up''

2016-12-22 08:05:07 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server is not there''

2016-12-22 08:05:07 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server is not there''

2016-12-22 08:05:07 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server is not there''

2016-12-22 08:05:07 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server is not there''

2016-12-22 08:05:07 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server is not there''

2016-12-22 08:05:07 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server is not there''

2016-12-22 08:05:07 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-12-22 08:05:08 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-12-22 08:05:08 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-12-22 08:05:08 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-12-22 08:05:08 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-12-22 08:05:08 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-12-22 08:05:08 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server always returns 500''

2016-12-22 08:05:08 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-12-22 08:05:08 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server always returns 500''

2016-12-22 08:05:08 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-12-22 08:05:08 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server always returns 500''

2016-12-22 08:05:08 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-12-22 08:05:08 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - create new seq doc''

2016-12-22 08:05:08 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-12-22 08:05:08 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - create new seq doc''

2016-12-22 08:05:10 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-12-22 08:05:10 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - create new seq doc''

2016-12-22 08:05:10 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-12-22 08:05:10 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-12-22 08:05:10 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-12-22 08:05:10 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-12-22 08:05:10 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-12-22 08:05:10 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-12-22 08:05:10 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-12-22 08:05:10 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - update seq three times''

2016-12-22 08:05:10 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - update seq three times''

2016-12-22 08:05:10 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - update seq three times''

2016-12-22 08:05:11 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - update seq three times''

2016-12-22 08:05:11 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - update seq three times''

2016-12-22 08:05:12 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - update seq three times''

2016-12-22 08:05:12 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - rev got changed under us''

2016-12-22 08:05:12 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-12-22 08:05:12 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - rev got changed under us''

2016-12-22 08:05:12 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-12-22 08:05:12 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - rev got changed under us''

2016-12-22 08:05:12 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-12-22 08:05:12 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - fail if stop is called''

2016-12-22 08:05:13 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-12-22 08:05:13 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - fail if stop is called''

2016-12-22 08:05:13 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-12-22 08:05:13 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - fail if stop is called''

2016-12-22 08:05:13 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-12-22 08:05:13 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-12-22 08:05:13 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-12-22 08:05:13 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-12-22 08:05:13 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-12-22 08:05:13 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-12-22 08:05:13 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-12-22 08:05:13 - DEBUG UnitTestFramework: '#setup: '#update - fail if stop is called''

2016-12-22 08:05:13 - DEBUG UnitTestFramework: '#setup ok: '#update - fail if stop is called''

2016-12-22 08:05:13 - DEBUG UnitTestFramework: '#run: '#update - fail if stop is called''

2016-12-22 08:05:13 - DEBUG UnitTestFramework: '#run ok: '#update - fail if stop is called''

2016-12-22 08:05:13 - DEBUG UnitTestFramework: '#teardown: '#update - fail if stop is called''

2016-12-22 08:05:13 - DEBUG UnitTestFramework: '#teardown ok: '#update - fail if stop is called''

2016-12-22 08:05:13 - DEBUG UnitTestFramework: '#setup: '#update - set seq for first time''

2016-12-22 08:05:13 - DEBUG UnitTestFramework: '#setup ok: '#update - set seq for first time''

2016-12-22 08:05:13 - DEBUG UnitTestFramework: '#run: '#update - set seq for first time''

2016-12-22 08:05:14 - DEBUG UnitTestFramework: '#run ok: '#update - set seq for first time''

2016-12-22 08:05:14 - DEBUG UnitTestFramework: '#teardown: '#update - set seq for first time''

2016-12-22 08:05:14 - DEBUG UnitTestFramework: '#teardown ok: '#update - set seq for first time''

2016-12-22 08:05:14 - DEBUG UnitTestFramework: '#setup: '#update - Fail on bad seq value''

2016-12-22 08:05:14 - DEBUG UnitTestFramework: '#setup ok: '#update - Fail on bad seq value''

2016-12-22 08:05:14 - DEBUG UnitTestFramework: '#run: '#update - Fail on bad seq value''

2016-12-22 08:05:15 - DEBUG UnitTestFramework: '#run ok: '#update - Fail on bad seq value''

2016-12-22 08:05:15 - DEBUG UnitTestFramework: '#teardown: '#update - Fail on bad seq value''

2016-12-22 08:05:15 - DEBUG UnitTestFramework: '#teardown ok: '#update - Fail on bad seq value''

2016-12-22 08:05:15 - DEBUG UnitTestFramework: '#setup: '#update - do we cancel timer properly on an immediate?''

2016-12-22 08:05:15 - DEBUG UnitTestFramework: '#setup ok: '#update - do we cancel timer properly on an immediate?''

2016-12-22 08:05:15 - DEBUG UnitTestFramework: '#run: '#update - do we cancel timer properly on an immediate?''

2016-12-22 08:05:16 - DEBUG UnitTestFramework: '#run ok: '#update - do we cancel timer properly on an immediate?''

2016-12-22 08:05:16 - DEBUG UnitTestFramework: '#teardown: '#update - do we cancel timer properly on an immediate?''

2016-12-22 08:05:16 - DEBUG UnitTestFramework: '#teardown ok: '#update - do we cancel timer properly on an immediate?''

2016-12-22 08:05:16 - DEBUG UnitTestFramework: '#setup: '#update - do we wait for blocked update''

2016-12-22 08:05:16 - DEBUG UnitTestFramework: '#setup ok: '#update - do we wait for blocked update''

2016-12-22 08:05:16 - DEBUG UnitTestFramework: '#run: '#update - do we wait for blocked update''

2016-12-22 08:05:17 - DEBUG UnitTestFramework: '#run ok: '#update - do we wait for blocked update''

2016-12-22 08:05:17 - DEBUG UnitTestFramework: '#teardown: '#update - do we wait for blocked update''

2016-12-22 08:05:17 - DEBUG UnitTestFramework: '#teardown ok: '#update - do we wait for blocked update''

2016-12-22 08:05:17 - DEBUG UnitTestFramework: '#setup: '#update - test that we wait long enough''

2016-12-22 08:05:17 - DEBUG UnitTestFramework: '#setup ok: '#update - test that we wait long enough''

2016-12-22 08:05:17 - DEBUG UnitTestFramework: '#run: '#update - test that we wait long enough''

2016-12-22 08:05:18 - DEBUG UnitTestFramework: '#run ok: '#update - test that we wait long enough''

2016-12-22 08:05:18 - DEBUG UnitTestFramework: '#teardown: '#update - test that we wait long enough''

2016-12-22 08:05:18 - DEBUG UnitTestFramework: '#teardown ok: '#update - test that we wait long enough''

2016-12-22 08:05:18 - DEBUG UnitTestFramework: '#setup: '#update - test that we pick up new sequences while we wait''

2016-12-22 08:05:18 - DEBUG UnitTestFramework: '#setup ok: '#update - test that we pick up new sequences while we wait''

2016-12-22 08:05:18 - DEBUG UnitTestFramework: '#run: '#update - test that we pick up new sequences while we wait''

2016-12-22 08:05:20 - DEBUG UnitTestFramework: '#run ok: '#update - test that we pick up new sequences while we wait''

2016-12-22 08:05:20 - DEBUG UnitTestFramework: '#teardown: '#update - test that we pick up new sequences while we wait''

2016-12-22 08:05:21 - DEBUG UnitTestFramework: '#teardown ok: '#update - test that we pick up new sequences while we wait''

2016-12-22 08:05:21 - DEBUG UnitTestFramework: '#setup: 'Coordinated seq test''

2016-12-22 08:05:22 - DEBUG UnitTestFramework: '#setup ok: 'Coordinated seq test''

2016-12-22 08:05:22 - DEBUG UnitTestFramework: '#run: 'Coordinated seq test''

2016-12-22 08:05:24 - DEBUG UnitTestFramework: '#run ok: 'Coordinated seq test''

2016-12-22 08:05:24 - DEBUG UnitTestFramework: '#teardown: 'Coordinated seq test''

2016-12-22 08:05:24 - DEBUG UnitTestFramework: '#teardown ok: 'Coordinated seq test''

2016-12-22 08:05:24 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2016-12-22 08:05:24 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2016-12-22 08:05:24 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2016-12-22 08:05:25 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2016-12-22 08:05:25 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2016-12-22 08:05:25 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2016-12-22 08:05:25 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2016-12-22 08:05:25 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2016-12-22 08:05:25 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2016-12-22 08:05:25 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2016-12-22 08:05:25 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2016-12-22 08:05:25 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2016-12-22 08:05:25 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2016-12-22 08:05:25 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2016-12-22 08:05:25 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2016-12-22 08:05:25 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2016-12-22 08:05:25 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2016-12-22 08:05:25 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2016-12-22 08:05:25 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2016-12-22 08:05:25 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2016-12-22 08:05:25 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2016-12-22 08:05:25 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2016-12-22 08:05:25 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2016-12-22 08:05:25 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2016-12-22 08:05:25 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2016-12-22 08:05:25 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2016-12-22 08:05:25 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2016-12-22 08:05:25 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2016-12-22 08:05:25 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2016-12-22 08:05:28 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2016-12-22 08:05:28 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2016-12-22 08:05:28 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2016-12-22 08:05:28 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2016-12-22 08:05:28 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2016-12-22 08:05:28 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2016-12-22 08:05:31 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2016-12-22 08:05:31 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2016-12-22 08:05:31 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2016-12-22 08:05:31 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2016-12-22 08:05:31 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2016-12-22 08:05:31 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2016-12-22 08:05:31 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2016-12-22 08:05:31 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2016-12-22 08:05:32 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2016-12-22 08:05:32 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2016-12-22 08:05:32 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2016-12-22 08:05:32 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2016-12-22 08:05:32 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2016-12-22 08:05:32 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2016-12-22 08:05:33 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2016-12-22 08:05:33 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2016-12-22 08:05:35 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2016-12-22 08:05:35 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2016-12-22 08:05:35 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2016-12-22 08:05:35 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2016-12-22 08:05:35 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2016-12-22 08:05:35 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2016-12-22 08:05:37 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2016-12-22 08:05:37 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2016-12-22 08:05:37 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2016-12-22 08:05:37 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2016-12-22 08:05:38 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2016-12-22 08:05:38 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2016-12-22 08:05:38 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2016-12-22 08:05:38 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2016-12-22 08:05:38 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2016-12-22 08:05:38 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2016-12-22 08:05:38 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2016-12-22 08:05:38 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2016-12-22 08:05:38 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2016-12-22 08:05:38 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2016-12-22 08:05:38 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2016-12-22 08:05:38 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2016-12-22 08:05:39 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2016-12-22 08:05:39 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2016-12-22 08:05:40 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2016-12-22 08:05:40 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2016-12-22 08:05:40 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2016-12-22 08:05:40 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2016-12-22 08:05:40 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2016-12-22 08:05:40 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2016-12-22 08:05:40 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2016-12-22 08:05:40 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2016-12-22 08:05:40 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2016-12-22 08:05:40 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2016-12-22 08:05:40 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2016-12-22 08:05:40 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2016-12-22 08:05:40 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2016-12-22 08:05:40 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2016-12-22 08:05:40 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2016-12-22 08:05:40 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2016-12-22 08:05:40 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2016-12-22 08:05:40 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2016-12-22 08:05:40 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2016-12-22 08:05:40 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2016-12-22 08:05:41 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2016-12-22 08:05:41 - DEBUG UnitTestFramework: '#setup: 'ssdp server should be restarted when wifi toggled''

2016-12-22 08:05:41 - DEBUG UnitTestFramework: '#setup ok: 'ssdp server should be restarted when wifi toggled''

2016-12-22 08:05:41 - DEBUG UnitTestFramework: '#run: 'ssdp server should be restarted when wifi toggled''

2016-12-22 08:05:41 - DEBUG UnitTestFramework: '#run ok: 'ssdp server should be restarted when wifi toggled''

2016-12-22 08:05:41 - DEBUG UnitTestFramework: '#teardown: 'ssdp server should be restarted when wifi toggled''

2016-12-22 08:05:41 - DEBUG UnitTestFramework: '#teardown ok: 'ssdp server should be restarted when wifi toggled''

2016-12-22 08:05:41 - DEBUG UnitTestFramework: '#setup: 'basic''

2016-12-22 08:05:41 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2016-12-22 08:05:41 - DEBUG UnitTestFramework: '#run: 'basic''

2016-12-22 08:05:41 - DEBUG UnitTestFramework: '#run ok: 'basic''

2016-12-22 08:05:41 - DEBUG UnitTestFramework: '#teardown: 'basic''

2016-12-22 08:05:41 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2016-12-22 08:05:41 - DEBUG UnitTestFramework: '#setup: 'another''

2016-12-22 08:05:41 - DEBUG UnitTestFramework: '#setup ok: 'another''

2016-12-22 08:05:41 - DEBUG UnitTestFramework: '#run: 'another''

2016-12-22 08:05:41 - DEBUG UnitTestFramework: '#run ok: 'another''

2016-12-22 08:05:41 - DEBUG UnitTestFramework: '#teardown: 'another''

2016-12-22 08:05:41 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2016-12-22 08:05:41 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2016-12-22 08:05:41 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2016-12-22 08:05:41 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2016-12-22 08:05:41 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2016-12-22 08:05:41 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2016-12-22 08:05:41 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2016-12-22 08:05:41 - DEBUG UnitTestFramework: '#setup: 'test thali manager spies''

2016-12-22 08:05:41 - DEBUG UnitTestFramework: '#setup ok: 'test thali manager spies''

2016-12-22 08:05:41 - DEBUG UnitTestFramework: '#run: 'test thali manager spies''

2016-12-22 08:05:42 - DEBUG UnitTestFramework: '#run ok: 'test thali manager spies''

2016-12-22 08:05:42 - DEBUG UnitTestFramework: '#teardown: 'test thali manager spies''

2016-12-22 08:05:43 - DEBUG UnitTestFramework: '#teardown ok: 'test thali manager spies''

2016-12-22 08:05:43 - DEBUG UnitTestFramework: '#setup: 'test thali manager multiple starts and stops''

2016-12-22 08:05:43 - DEBUG UnitTestFramework: '#setup ok: 'test thali manager multiple starts and stops''

2016-12-22 08:05:43 - DEBUG UnitTestFramework: '#run: 'test thali manager multiple starts and stops''

2016-12-22 08:05:44 - DEBUG UnitTestFramework: '#run ok: 'test thali manager multiple starts and stops''

2016-12-22 08:05:44 - DEBUG UnitTestFramework: '#teardown: 'test thali manager multiple starts and stops''

2016-12-22 08:05:44 - DEBUG UnitTestFramework: '#teardown ok: 'test thali manager multiple starts and stops''

2016-12-22 08:05:44 - DEBUG UnitTestFramework: '#setup: 'test write''

2016-12-22 08:05:44 - DEBUG UnitTestFramework: '#setup ok: 'test write''

2016-12-22 08:05:44 - DEBUG UnitTestFramework: '#run: 'test write''

2016-12-22 08:05:47 - DEBUG UnitTestFramework: '#run ok: 'test write''

2016-12-22 08:05:47 - DEBUG UnitTestFramework: '#teardown: 'test write''

2016-12-22 08:05:51 - DEBUG UnitTestFramework: '#teardown ok: 'test write''

2016-12-22 08:05:51 - DEBUG UnitTestFramework: '#setup: 'test repeat write 1''

2016-12-22 08:05:52 - DEBUG UnitTestFramework: '#setup ok: 'test repeat write 1''

2016-12-22 08:05:52 - DEBUG UnitTestFramework: '#run: 'test repeat write 1''

2016-12-22 08:05:54 - DEBUG UnitTestFramework: '#run ok: 'test repeat write 1''

2016-12-22 08:05:54 - DEBUG UnitTestFramework: '#teardown: 'test repeat write 1''

2016-12-22 08:05:55 - DEBUG UnitTestFramework: '#teardown ok: 'test repeat write 1''

2016-12-22 08:05:55 - DEBUG UnitTestFramework: '#setup: 'test repeat write 2''

2016-12-22 08:05:56 - DEBUG UnitTestFramework: '#setup ok: 'test repeat write 2''

2016-12-22 08:05:56 - DEBUG UnitTestFramework: '#run: 'test repeat write 2''

2016-12-22 08:06:00 - DEBUG UnitTestFramework: '#run ok: 'test repeat write 2''

2016-12-22 08:06:00 - DEBUG UnitTestFramework: '#teardown: 'test repeat write 2''

2016-12-22 08:06:01 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'transport close''

2016-12-22 08:07:00 - ERROR UnitTestFramework: '#run failed: 'test repeat write 2', error: 'TimeoutError: timeout exceeded, event: 'teardown_test repeat write 2_finished', test: 'test repeat write 2'', stack: 'TimeoutError: timeout exceeded, event: 'teardown_test repeat write 2_finished', test: 'test repeat write 2'
    at afterTimeout (/home/pi/Test/server_986941187d5d37b/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_986941187d5d37b/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-12-22 08:07:00 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'android', error: 'TimeoutError: timeout exceeded, event: 'teardown_test repeat write 2_finished', test: 'test repeat write 2'', stack: 'TimeoutError: timeout exceeded, event: 'teardown_test repeat write 2_finished', test: 'test repeat write 2'
    at afterTimeout (/home/pi/Test/server_986941187d5d37b/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_986941187d5d37b/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-12-22 08:07:00 - ERROR HttpServer: 'unexpected server error: 'TimeoutError: timeout exceeded, event: 'teardown_test repeat write 2_finished', test: 'test repeat write 2'''

2016-12-22 08:07:00 - ERROR HttpServer: 'unexpected server error: 'TimeoutError: timeout exceeded, event: 'teardown_test repeat write 2_finished', test: 'test repeat write 2'''

2016-12-22 08:07:00 - ERROR HttpServer: 'unexpected server error: 'TimeoutError: timeout exceeded, event: 'teardown_test repeat write 2_finished', test: 'test repeat write 2'''

2016-12-22 08:07:00 - ERROR UnitTestFramework: 'unexpected error: 'Error: TimeoutError: timeout exceeded, event: 'teardown_test repeat write 2_finished', test: 'test repeat write 2'', stack: 'Error: TimeoutError: timeout exceeded, event: 'teardown_test repeat write 2_finished', test: 'test repeat write 2'
    at Server._error (/home/pi/Test/server_986941187d5d37b/test/TestServer/HttpServer.js:77:9)
    at Socket.emit (events.js:82:17)
    at Socket.emit (/home/pi/Test/server_986941187d5d37b/test/TestServer/node_modules/socket.io/lib/socket.js:128:10)
    at updatedHandler (/home/pi/Test/server_986941187d5d37b/test/TestServer/Socket.js:103:29)
    at Socket._apply (/home/pi/Test/server_986941187d5d37b/test/TestServer/Socket.js:106:3)
    at emit (/home/pi/Test/server_986941187d5d37b/test/TestServer/Socket.js:165:22)
    at /home/pi/Test/server_986941187d5d37b/test/TestServer/Socket.js:169:5
    at Promise._execute (/home/pi/Test/server_986941187d5d37b/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_986941187d5d37b/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_986941187d5d37b/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Socket.emitData (/home/pi/Test/server_986941187d5d37b/test/TestServer/Socket.js:134:10)
    at TestDevice.error (/home/pi/Test/server_986941187d5d37b/test/TestServer/TestDevice.js:134:23)
    at /home/pi/Test/server_986941187d5d37b/test/TestServer/UnitTestFramework.js:87:23
    at Array.map (native)
    at /home/pi/Test/server_986941187d5d37b/test/TestServer/UnitTestFramework.js:86:15
    at tryCatcher (/home/pi/Test/server_986941187d5d37b/test/TestServer/node_modules/bluebird/js/release/util.js:16:23)''

2016-12-22 08:07:00 - ERROR UnitTestFramework: 'unexpected error: 'Error: TimeoutError: timeout exceeded, event: 'teardown_test repeat write 2_finished', test: 'test repeat write 2'', stack: 'Error: TimeoutError: timeout exceeded, event: 'teardown_test repeat write 2_finished', test: 'test repeat write 2'
    at Server._error (/home/pi/Test/server_986941187d5d37b/test/TestServer/HttpServer.js:77:9)
    at Socket.emit (events.js:82:17)
    at Socket.emit (/home/pi/Test/server_986941187d5d37b/test/TestServer/node_modules/socket.io/lib/socket.js:128:10)
    at updatedHandler (/home/pi/Test/server_986941187d5d37b/test/TestServer/Socket.js:103:29)
    at Socket._apply (/home/pi/Test/server_986941187d5d37b/test/TestServer/Socket.js:106:3)
    at emit (/home/pi/Test/server_986941187d5d37b/test/TestServer/Socket.js:165:22)
    at /home/pi/Test/server_986941187d5d37b/test/TestServer/Socket.js:169:5
    at Promise._execute (/home/pi/Test/server_986941187d5d37b/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_986941187d5d37b/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_986941187d5d37b/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Socket.emitData (/home/pi/Test/server_986941187d5d37b/test/TestServer/Socket.js:134:10)
    at TestDevice.error (/home/pi/Test/server_986941187d5d37b/test/TestServer/TestDevice.js:134:23)
    at /home/pi/Test/server_986941187d5d37b/test/TestServer/UnitTestFramework.js:87:23
    at Array.map (native)
    at /home/pi/Test/server_986941187d5d37b/test/TestServer/UnitTestFramework.js:86:15
    at tryCatcher (/home/pi/Test/server_986941187d5d37b/test/TestServer/node_modules/bluebird/js/release/util.js:16:23)''

2016-12-22 08:07:00 - ERROR UnitTestFramework: 'unexpected error: 'Error: TimeoutError: timeout exceeded, event: 'teardown_test repeat write 2_finished', test: 'test repeat write 2'', stack: 'Error: TimeoutError: timeout exceeded, event: 'teardown_test repeat write 2_finished', test: 'test repeat write 2'
    at Server._error (/home/pi/Test/server_986941187d5d37b/test/TestServer/HttpServer.js:77:9)
    at Socket.emit (events.js:82:17)
    at Socket.emit (/home/pi/Test/server_986941187d5d37b/test/TestServer/node_modules/socket.io/lib/socket.js:128:10)
    at updatedHandler (/home/pi/Test/server_986941187d5d37b/test/TestServer/Socket.js:103:29)
    at Socket._apply (/home/pi/Test/server_986941187d5d37b/test/TestServer/Socket.js:106:3)
    at emit (/home/pi/Test/server_986941187d5d37b/test/TestServer/Socket.js:165:22)
    at /home/pi/Test/server_986941187d5d37b/test/TestServer/Socket.js:169:5
    at Promise._execute (/home/pi/Test/server_986941187d5d37b/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_986941187d5d37b/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_986941187d5d37b/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Socket.emitData (/home/pi/Test/server_986941187d5d37b/test/TestServer/Socket.js:134:10)
    at TestDevice.error (/home/pi/Test/server_986941187d5d37b/test/TestServer/TestDevice.js:134:23)
    at /home/pi/Test/server_986941187d5d37b/test/TestServer/UnitTestFramework.js:87:23
    at Array.map (native)
    at /home/pi/Test/server_986941187d5d37b/test/TestServer/UnitTestFramework.js:86:15
    at tryCatcher (/home/pi/Test/server_986941187d5d37b/test/TestServer/node_modules/bluebird/js/release/util.js:16:23)''

2016-12-22 08:07:00 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'client namespace disconnect''

2016-12-22 08:07:01 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'client namespace disconnect''

2016-12-22 08:08:00 - ERROR Socket: 'unexpected error: 'Error: retry count exceed', stack: 'Error: retry count exceed
    at emit (/home/pi/Test/server_986941187d5d37b/test/TestServer/Socket.js:155:16)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-12-22 08:09:00 - DEBUG TestServer: 'completed'

[0;31merror: command 'sudo jx ______.js android' failed with code 1, file 'bash' on line 30[0m
One or more Android tests are failed.
 [0m
jx install failed [ 1 ]

```


Logs for system : 
```

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!
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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/986941187d5d37b_CI_sanity_check_czyzm/thali02_samsung-SM-G930F.md)

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
Test has SUCCEED

Device test finished on ce061606c181d71003 
Android task is completed. [SUCCESS]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/986941187d5d37b_CI_sanity_check_czyzm/thali03_samsung-SM-G930F.md)

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

Error! Unexpected exit on device ce061606e320561102 app:com.test.thalitest code:null 
Child process exited with code null on device ce061606e320561102
Android task is completed. [FAILED]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/986941187d5d37b_CI_sanity_check_czyzm/thali04_samsung-SM-G935F.md)





#### Test 8728295445538d6 Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-09-29 10:30:20 - INFO HttpServer: 'listening on *:3000'

2016-09-29 10:32:05 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'a4de3463-be17-4bda-888c-58506c6c10d4', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true''

2016-09-29 10:32:05 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2016-09-29 10:32:06 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '4cc69b62-c568-4638-9796-2891809145ae', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true''

2016-09-29 10:32:06 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2016-09-29 10:32:14 - DEBUG HttpServer: 'device presented, name: 'Huawei-Nexus 6P', uuid: 'f3233d06-e5c3-4ef9-9332-aa681193cbef', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true''

2016-09-29 10:32:14 - DEBUG TestFramework: 'device added, name: 'Huawei-Nexus 6P''

2016-09-29 10:32:14 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2016-09-29 10:32:14 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2016-09-29 10:32:14 - DEBUG UnitTestFramework: 'scheduling tests'

2016-09-29 10:32:15 - DEBUG UnitTestFramework: 'tests scheduled'

2016-09-29 10:32:15 - DEBUG UnitTestFramework: '#setup: 'calling createNativeListener directly rejects''

2016-09-29 10:32:15 - DEBUG UnitTestFramework: '#setup ok: 'calling createNativeListener directly rejects''

2016-09-29 10:32:15 - DEBUG UnitTestFramework: '#run: 'calling createNativeListener directly rejects''

2016-09-29 10:32:15 - DEBUG UnitTestFramework: '#run ok: 'calling createNativeListener directly rejects''

2016-09-29 10:32:15 - DEBUG UnitTestFramework: '#teardown: 'calling createNativeListener directly rejects''

2016-09-29 10:32:15 - DEBUG UnitTestFramework: '#teardown ok: 'calling createNativeListener directly rejects''

2016-09-29 10:32:15 - DEBUG UnitTestFramework: '#setup: 'emits incomingConnectionState''

2016-09-29 10:32:15 - DEBUG UnitTestFramework: '#setup ok: 'emits incomingConnectionState''

2016-09-29 10:32:15 - DEBUG UnitTestFramework: '#run: 'emits incomingConnectionState''

2016-09-29 10:32:15 - DEBUG UnitTestFramework: '#run ok: 'emits incomingConnectionState''

2016-09-29 10:32:15 - DEBUG UnitTestFramework: '#teardown: 'emits incomingConnectionState''

2016-09-29 10:32:16 - DEBUG UnitTestFramework: '#teardown ok: 'emits incomingConnectionState''

2016-09-29 10:32:16 - DEBUG UnitTestFramework: '#setup: 'emits routerPortConnectionFailed''

2016-09-29 10:32:16 - DEBUG UnitTestFramework: '#setup ok: 'emits routerPortConnectionFailed''

2016-09-29 10:32:16 - DEBUG UnitTestFramework: '#run: 'emits routerPortConnectionFailed''

2016-09-29 10:32:16 - DEBUG UnitTestFramework: '#run ok: 'emits routerPortConnectionFailed''

2016-09-29 10:32:16 - DEBUG UnitTestFramework: '#teardown: 'emits routerPortConnectionFailed''

2016-09-29 10:32:16 - DEBUG UnitTestFramework: '#teardown ok: 'emits routerPortConnectionFailed''

2016-09-29 10:32:16 - DEBUG UnitTestFramework: '#setup: 'native server connections all up''

2016-09-29 10:32:16 - DEBUG UnitTestFramework: '#setup ok: 'native server connections all up''

2016-09-29 10:32:16 - DEBUG UnitTestFramework: '#run: 'native server connections all up''

2016-09-29 10:32:16 - DEBUG UnitTestFramework: '#run ok: 'native server connections all up''

2016-09-29 10:32:16 - DEBUG UnitTestFramework: '#teardown: 'native server connections all up''

2016-09-29 10:32:16 - DEBUG UnitTestFramework: '#teardown ok: 'native server connections all up''

2016-09-29 10:32:16 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming stream cleans outgoing socket''

2016-09-29 10:32:16 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming stream cleans outgoing socket''

2016-09-29 10:32:16 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming stream cleans outgoing socket''

2016-09-29 10:32:16 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming stream cleans outgoing socket''

2016-09-29 10:32:16 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming stream cleans outgoing socket''

2016-09-29 10:32:16 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming stream cleans outgoing socket''

2016-09-29 10:32:16 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming connection cleans outgoing socket''

2016-09-29 10:32:17 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming connection cleans outgoing socket''

2016-09-29 10:32:17 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming connection cleans outgoing socket''

2016-09-29 10:32:17 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming connection cleans outgoing socket''

2016-09-29 10:32:17 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming connection cleans outgoing socket''

2016-09-29 10:32:17 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming connection cleans outgoing socket''

2016-09-29 10:32:17 - DEBUG UnitTestFramework: '#setup: 'native server - closing outgoing socket cleans associated mux stream''

2016-09-29 10:32:17 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-09-29 10:32:17 - DEBUG UnitTestFramework: '#run: 'native server - closing outgoing socket cleans associated mux stream''

2016-09-29 10:32:17 - DEBUG UnitTestFramework: '#run ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-09-29 10:32:17 - DEBUG UnitTestFramework: '#teardown: 'native server - closing outgoing socket cleans associated mux stream''

2016-09-29 10:32:17 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-09-29 10:32:17 - DEBUG UnitTestFramework: '#setup: 'native server - closing the whole server cleans everything up''

2016-09-29 10:32:17 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing the whole server cleans everything up''

2016-09-29 10:32:17 - DEBUG UnitTestFramework: '#run: 'native server - closing the whole server cleans everything up''

2016-09-29 10:32:17 - DEBUG UnitTestFramework: '#run ok: 'native server - closing the whole server cleans everything up''

2016-09-29 10:32:17 - DEBUG UnitTestFramework: '#teardown: 'native server - closing the whole server cleans everything up''

2016-09-29 10:32:17 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing the whole server cleans everything up''

2016-09-29 10:32:17 - DEBUG UnitTestFramework: '#setup: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-09-29 10:32:17 - DEBUG UnitTestFramework: '#setup ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-09-29 10:32:17 - DEBUG UnitTestFramework: '#run: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-09-29 10:32:18 - DEBUG UnitTestFramework: '#run ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-09-29 10:32:18 - DEBUG UnitTestFramework: '#teardown: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-09-29 10:32:19 - DEBUG UnitTestFramework: '#teardown ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-09-29 10:32:19 - DEBUG UnitTestFramework: '#setup: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-09-29 10:32:20 - DEBUG UnitTestFramework: '#setup ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-09-29 10:32:20 - DEBUG UnitTestFramework: '#run: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-09-29 10:32:20 - DEBUG UnitTestFramework: '#run ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-09-29 10:32:20 - DEBUG UnitTestFramework: '#teardown: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-09-29 10:32:20 - DEBUG UnitTestFramework: '#teardown ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-09-29 10:32:20 - DEBUG UnitTestFramework: '#setup: 'native server - timing out the incoming connection cleans everything up''

2016-09-29 10:32:20 - DEBUG UnitTestFramework: '#setup ok: 'native server - timing out the incoming connection cleans everything up''

2016-09-29 10:32:20 - DEBUG UnitTestFramework: '#run: 'native server - timing out the incoming connection cleans everything up''

2016-09-29 10:32:20 - DEBUG UnitTestFramework: '#run ok: 'native server - timing out the incoming connection cleans everything up''

2016-09-29 10:32:20 - DEBUG UnitTestFramework: '#teardown: 'native server - timing out the incoming connection cleans everything up''

2016-09-29 10:32:20 - DEBUG UnitTestFramework: '#teardown ok: 'native server - timing out the incoming connection cleans everything up''

2016-09-29 10:32:20 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server is not there''

2016-09-29 10:32:20 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server is not there''

2016-09-29 10:32:20 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server is not there''

2016-09-29 10:32:20 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server is not there''

2016-09-29 10:32:20 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server is not there''

2016-09-29 10:32:20 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server is not there''

2016-09-29 10:32:20 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-09-29 10:32:20 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-09-29 10:32:20 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-09-29 10:32:20 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-09-29 10:32:20 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-09-29 10:32:20 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-09-29 10:32:20 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server always returns 500''

2016-09-29 10:32:20 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-09-29 10:32:20 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server always returns 500''

2016-09-29 10:32:21 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-09-29 10:32:21 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server always returns 500''

2016-09-29 10:32:21 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-09-29 10:32:21 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - create new seq doc''

2016-09-29 10:32:21 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-09-29 10:32:21 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - create new seq doc''

2016-09-29 10:32:22 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-09-29 10:32:22 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - create new seq doc''

2016-09-29 10:32:23 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-09-29 10:32:23 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-09-29 10:32:23 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-09-29 10:32:23 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-09-29 10:32:24 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-09-29 10:32:24 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-09-29 10:32:24 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-09-29 10:32:24 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - update seq three times''

2016-09-29 10:32:24 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - update seq three times''

2016-09-29 10:32:24 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - update seq three times''

2016-09-29 10:32:25 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - update seq three times''

2016-09-29 10:32:25 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - update seq three times''

2016-09-29 10:32:25 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - update seq three times''

2016-09-29 10:32:25 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - rev got changed under us''

2016-09-29 10:32:25 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-09-29 10:32:25 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - rev got changed under us''

2016-09-29 10:32:25 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-09-29 10:32:25 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - rev got changed under us''

2016-09-29 10:32:25 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-09-29 10:32:25 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - fail if stop is called''

2016-09-29 10:32:26 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-09-29 10:32:26 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - fail if stop is called''

2016-09-29 10:32:26 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-09-29 10:32:26 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - fail if stop is called''

2016-09-29 10:32:26 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-09-29 10:32:26 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-09-29 10:32:26 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-09-29 10:32:26 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-09-29 10:32:26 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-09-29 10:32:26 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-09-29 10:32:26 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-09-29 10:32:26 - DEBUG UnitTestFramework: '#setup: '#update - fail if stop is called''

2016-09-29 10:32:26 - DEBUG UnitTestFramework: '#setup ok: '#update - fail if stop is called''

2016-09-29 10:32:26 - DEBUG UnitTestFramework: '#run: '#update - fail if stop is called''

2016-09-29 10:32:26 - DEBUG UnitTestFramework: '#run ok: '#update - fail if stop is called''

2016-09-29 10:32:26 - DEBUG UnitTestFramework: '#teardown: '#update - fail if stop is called''

2016-09-29 10:32:26 - DEBUG UnitTestFramework: '#teardown ok: '#update - fail if stop is called''

2016-09-29 10:32:26 - DEBUG UnitTestFramework: '#setup: '#update - set seq for first time''

2016-09-29 10:32:27 - DEBUG UnitTestFramework: '#setup ok: '#update - set seq for first time''

2016-09-29 10:32:27 - DEBUG UnitTestFramework: '#run: '#update - set seq for first time''

2016-09-29 10:32:27 - DEBUG UnitTestFramework: '#run ok: '#update - set seq for first time''

2016-09-29 10:32:27 - DEBUG UnitTestFramework: '#teardown: '#update - set seq for first time''

2016-09-29 10:32:27 - DEBUG UnitTestFramework: '#teardown ok: '#update - set seq for first time''

2016-09-29 10:32:27 - DEBUG UnitTestFramework: '#setup: '#update - Fail on bad seq value''

2016-09-29 10:32:29 - DEBUG UnitTestFramework: '#setup ok: '#update - Fail on bad seq value''

2016-09-29 10:32:29 - DEBUG UnitTestFramework: '#run: '#update - Fail on bad seq value''

2016-09-29 10:32:29 - DEBUG UnitTestFramework: '#run ok: '#update - Fail on bad seq value''

2016-09-29 10:32:29 - DEBUG UnitTestFramework: '#teardown: '#update - Fail on bad seq value''

2016-09-29 10:32:30 - DEBUG UnitTestFramework: '#teardown ok: '#update - Fail on bad seq value''

2016-09-29 10:32:30 - DEBUG UnitTestFramework: '#setup: '#update - do we cancel timer properly on an immediate?''

2016-09-29 10:32:31 - DEBUG UnitTestFramework: '#setup ok: '#update - do we cancel timer properly on an immediate?''

2016-09-29 10:32:31 - DEBUG UnitTestFramework: '#run: '#update - do we cancel timer properly on an immediate?''

2016-09-29 10:32:32 - DEBUG UnitTestFramework: '#run ok: '#update - do we cancel timer properly on an immediate?''

2016-09-29 10:32:32 - DEBUG UnitTestFramework: '#teardown: '#update - do we cancel timer properly on an immediate?''

2016-09-29 10:32:33 - DEBUG UnitTestFramework: '#teardown ok: '#update - do we cancel timer properly on an immediate?''

2016-09-29 10:32:33 - DEBUG UnitTestFramework: '#setup: '#update - do we wait for blocked update''

2016-09-29 10:32:33 - DEBUG UnitTestFramework: '#setup ok: '#update - do we wait for blocked update''

2016-09-29 10:32:33 - DEBUG UnitTestFramework: '#run: '#update - do we wait for blocked update''

2016-09-29 10:32:34 - DEBUG UnitTestFramework: '#run ok: '#update - do we wait for blocked update''

2016-09-29 10:32:34 - DEBUG UnitTestFramework: '#teardown: '#update - do we wait for blocked update''

2016-09-29 10:32:34 - DEBUG UnitTestFramework: '#teardown ok: '#update - do we wait for blocked update''

2016-09-29 10:32:34 - DEBUG UnitTestFramework: '#setup: '#update - test that we wait long enough''

2016-09-29 10:32:35 - DEBUG UnitTestFramework: '#setup ok: '#update - test that we wait long enough''

2016-09-29 10:32:35 - DEBUG UnitTestFramework: '#run: '#update - test that we wait long enough''

2016-09-29 10:32:37 - DEBUG UnitTestFramework: '#run ok: '#update - test that we wait long enough''

2016-09-29 10:32:37 - DEBUG UnitTestFramework: '#teardown: '#update - test that we wait long enough''

2016-09-29 10:32:37 - DEBUG UnitTestFramework: '#teardown ok: '#update - test that we wait long enough''

2016-09-29 10:32:37 - DEBUG UnitTestFramework: '#setup: '#update - test that we pick up new sequences while we wait''

2016-09-29 10:32:37 - DEBUG UnitTestFramework: '#setup ok: '#update - test that we pick up new sequences while we wait''

2016-09-29 10:32:37 - DEBUG UnitTestFramework: '#run: '#update - test that we pick up new sequences while we wait''

2016-09-29 10:32:38 - DEBUG UnitTestFramework: '#run ok: '#update - test that we pick up new sequences while we wait''

2016-09-29 10:32:38 - DEBUG UnitTestFramework: '#teardown: '#update - test that we pick up new sequences while we wait''

2016-09-29 10:32:38 - DEBUG UnitTestFramework: '#teardown ok: '#update - test that we pick up new sequences while we wait''

2016-09-29 10:32:38 - DEBUG UnitTestFramework: '#setup: 'Coordinated seq test''

2016-09-29 10:32:39 - DEBUG UnitTestFramework: '#setup ok: 'Coordinated seq test''

2016-09-29 10:32:39 - DEBUG UnitTestFramework: '#run: 'Coordinated seq test''

2016-09-29 10:32:39 - INFO Socket: 'run skipped, test: 'Coordinated seq test', event: 'run_Coordinated seq test''

2016-09-29 10:32:39 - INFO Socket: 'run skipped, test: 'Coordinated seq test', event: 'run_Coordinated seq test''

2016-09-29 10:32:39 - INFO Socket: 'run skipped, test: 'Coordinated seq test', event: 'run_Coordinated seq test''

2016-09-29 10:32:39 - DEBUG UnitTestFramework: '#run ok: 'Coordinated seq test''

2016-09-29 10:32:39 - DEBUG UnitTestFramework: '#teardown: 'Coordinated seq test''

2016-09-29 10:32:39 - DEBUG UnitTestFramework: '#teardown ok: 'Coordinated seq test''

2016-09-29 10:32:39 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2016-09-29 10:32:39 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2016-09-29 10:32:39 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2016-09-29 10:32:39 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2016-09-29 10:32:39 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2016-09-29 10:32:39 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2016-09-29 10:32:39 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2016-09-29 10:32:39 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2016-09-29 10:32:39 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2016-09-29 10:32:39 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2016-09-29 10:32:39 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2016-09-29 10:32:39 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2016-09-29 10:32:39 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2016-09-29 10:32:39 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2016-09-29 10:32:39 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2016-09-29 10:32:39 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2016-09-29 10:32:39 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2016-09-29 10:32:39 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2016-09-29 10:32:39 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2016-09-29 10:32:40 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2016-09-29 10:32:40 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2016-09-29 10:32:40 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2016-09-29 10:32:40 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2016-09-29 10:32:40 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2016-09-29 10:32:40 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2016-09-29 10:32:40 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2016-09-29 10:32:40 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2016-09-29 10:32:40 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2016-09-29 10:32:40 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2016-09-29 10:32:44 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2016-09-29 10:32:44 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2016-09-29 10:32:44 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2016-09-29 10:32:44 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2016-09-29 10:32:45 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2016-09-29 10:32:45 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2016-09-29 10:32:47 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2016-09-29 10:32:47 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2016-09-29 10:32:47 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2016-09-29 10:32:47 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2016-09-29 10:32:48 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2016-09-29 10:32:48 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2016-09-29 10:32:48 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2016-09-29 10:32:48 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2016-09-29 10:32:48 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2016-09-29 10:32:48 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2016-09-29 10:32:48 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2016-09-29 10:32:48 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2016-09-29 10:32:48 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2016-09-29 10:32:48 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2016-09-29 10:32:49 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2016-09-29 10:32:49 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2016-09-29 10:32:50 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2016-09-29 10:32:50 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2016-09-29 10:32:50 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2016-09-29 10:32:50 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2016-09-29 10:32:50 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2016-09-29 10:32:50 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2016-09-29 10:32:51 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2016-09-29 10:32:51 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2016-09-29 10:32:51 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2016-09-29 10:32:51 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2016-09-29 10:32:51 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2016-09-29 10:32:51 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2016-09-29 10:32:51 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2016-09-29 10:32:51 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2016-09-29 10:32:51 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2016-09-29 10:32:51 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2016-09-29 10:32:51 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2016-09-29 10:32:51 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2016-09-29 10:32:51 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2016-09-29 10:32:51 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2016-09-29 10:32:51 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2016-09-29 10:32:51 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2016-09-29 10:32:51 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2016-09-29 10:32:51 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2016-09-29 10:32:51 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2016-09-29 10:32:51 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2016-09-29 10:32:52 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2016-09-29 10:32:52 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2016-09-29 10:32:53 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2016-09-29 10:32:53 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2016-09-29 10:32:53 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2016-09-29 10:32:53 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2016-09-29 10:32:54 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2016-09-29 10:32:54 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2016-09-29 10:32:55 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2016-09-29 10:32:55 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2016-09-29 10:32:55 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2016-09-29 10:32:55 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2016-09-29 10:32:56 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2016-09-29 10:32:56 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2016-09-29 10:32:56 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2016-09-29 10:32:56 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2016-09-29 10:32:56 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2016-09-29 10:32:56 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2016-09-29 10:32:56 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2016-09-29 10:32:56 - DEBUG UnitTestFramework: '#setup: 'basic''

2016-09-29 10:32:56 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2016-09-29 10:32:56 - DEBUG UnitTestFramework: '#run: 'basic''

2016-09-29 10:32:56 - DEBUG UnitTestFramework: '#run ok: 'basic''

2016-09-29 10:32:56 - DEBUG UnitTestFramework: '#teardown: 'basic''

2016-09-29 10:32:56 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2016-09-29 10:32:56 - DEBUG UnitTestFramework: '#setup: 'another''

2016-09-29 10:32:56 - DEBUG UnitTestFramework: '#setup ok: 'another''

2016-09-29 10:32:56 - DEBUG UnitTestFramework: '#run: 'another''

2016-09-29 10:32:57 - DEBUG UnitTestFramework: '#run ok: 'another''

2016-09-29 10:32:57 - DEBUG UnitTestFramework: '#teardown: 'another''

2016-09-29 10:32:57 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2016-09-29 10:32:57 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2016-09-29 10:32:57 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2016-09-29 10:32:57 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2016-09-29 10:32:57 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2016-09-29 10:32:57 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2016-09-29 10:32:57 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2016-09-29 10:32:57 - DEBUG UnitTestFramework: '#setup: 'test thali manager spies''

2016-09-29 10:32:57 - DEBUG UnitTestFramework: '#setup ok: 'test thali manager spies''

2016-09-29 10:32:57 - DEBUG UnitTestFramework: '#run: 'test thali manager spies''

2016-09-29 10:32:57 - DEBUG UnitTestFramework: '#run ok: 'test thali manager spies''

2016-09-29 10:32:57 - DEBUG UnitTestFramework: '#teardown: 'test thali manager spies''

2016-09-29 10:32:57 - DEBUG UnitTestFramework: '#teardown ok: 'test thali manager spies''

2016-09-29 10:32:57 - DEBUG UnitTestFramework: '#setup: 'test thali manager multiple starts and stops''

2016-09-29 10:32:57 - DEBUG UnitTestFramework: '#setup ok: 'test thali manager multiple starts and stops''

2016-09-29 10:32:57 - DEBUG UnitTestFramework: '#run: 'test thali manager multiple starts and stops''

2016-09-29 10:32:58 - DEBUG UnitTestFramework: '#run ok: 'test thali manager multiple starts and stops''

2016-09-29 10:32:58 - DEBUG UnitTestFramework: '#teardown: 'test thali manager multiple starts and stops''

2016-09-29 10:32:58 - DEBUG UnitTestFramework: '#teardown ok: 'test thali manager multiple starts and stops''

2016-09-29 10:32:58 - DEBUG UnitTestFramework: '#setup: 'test write''

2016-09-29 10:32:58 - DEBUG UnitTestFramework: '#setup ok: 'test write''

2016-09-29 10:32:58 - DEBUG UnitTestFramework: '#run: 'test write''

2016-09-29 10:33:00 - INFO HttpServer: 'Socket to device name: 'Huawei-Nexus 6P' disconnected, reason: 'transport close''

2016-09-29 10:35:58 - ERROR UnitTestFramework: '#run failed: 'test write', error: 'TimeoutError: timeout exceeded, event: 'run_test write_finished', test: 'test write'', stack: 'TimeoutError: timeout exceeded, event: 'run_test write_finished', test: 'test write'
    at afterTimeout (/home/pi/Test/server_8728295445538d6/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_8728295445538d6/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-09-29 10:35:58 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'android', error: 'TimeoutError: timeout exceeded, event: 'run_test write_finished', test: 'test write'', stack: 'TimeoutError: timeout exceeded, event: 'run_test write_finished', test: 'test write'
    at afterTimeout (/home/pi/Test/server_8728295445538d6/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_8728295445538d6/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-09-29 10:37:58 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'client namespace disconnect''

2016-09-29 10:37:58 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'client namespace disconnect''

2016-09-29 10:37:58 - DEBUG TestServer: 'completed'


 
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

Device test finished on ce061606e320561102 
Device test finished on ce0616068b9f212302 
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/8728295445538d6_Workaround_for_pouchdb_error_handlers_andrew-aladev/thali05_samsung-SM-G930F.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/8728295445538d6_Workaround_for_pouchdb_error_handlers_andrew-aladev/thali05_samsung-SM-G935F.md)

[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/8728295445538d6_Workaround_for_pouchdb_error_handlers_andrew-aladev/thali05_Huawei-Nexus 6P.md)





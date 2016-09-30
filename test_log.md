#### Test 87460634d91a0a5 Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-09-30 15:21:52 - INFO HttpServer: 'listening on *:3000'

2016-09-30 15:23:37 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '9825afce-c9b9-474c-8683-392c5e05a651', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true''

2016-09-30 15:23:37 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2016-09-30 15:23:37 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '5bfc65c7-11df-4f97-b8ab-a49f784ed974', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true''

2016-09-30 15:23:37 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2016-09-30 15:23:45 - DEBUG HttpServer: 'device presented, name: 'Huawei-Nexus 6P', uuid: '499cdee2-3799-4ce4-84cc-9ededb3542d1', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true''

2016-09-30 15:23:45 - DEBUG TestFramework: 'device added, name: 'Huawei-Nexus 6P''

2016-09-30 15:23:45 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2016-09-30 15:23:45 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2016-09-30 15:23:45 - DEBUG UnitTestFramework: 'scheduling tests'

2016-09-30 15:23:46 - DEBUG UnitTestFramework: 'tests scheduled'

2016-09-30 15:23:46 - DEBUG UnitTestFramework: '#setup: 'calling createNativeListener directly rejects''

2016-09-30 15:23:46 - DEBUG UnitTestFramework: '#setup ok: 'calling createNativeListener directly rejects''

2016-09-30 15:23:46 - DEBUG UnitTestFramework: '#run: 'calling createNativeListener directly rejects''

2016-09-30 15:23:46 - DEBUG UnitTestFramework: '#run ok: 'calling createNativeListener directly rejects''

2016-09-30 15:23:46 - DEBUG UnitTestFramework: '#teardown: 'calling createNativeListener directly rejects''

2016-09-30 15:23:47 - DEBUG UnitTestFramework: '#teardown ok: 'calling createNativeListener directly rejects''

2016-09-30 15:23:47 - DEBUG UnitTestFramework: '#setup: 'emits incomingConnectionState''

2016-09-30 15:23:48 - DEBUG UnitTestFramework: '#setup ok: 'emits incomingConnectionState''

2016-09-30 15:23:48 - DEBUG UnitTestFramework: '#run: 'emits incomingConnectionState''

2016-09-30 15:23:49 - DEBUG UnitTestFramework: '#run ok: 'emits incomingConnectionState''

2016-09-30 15:23:49 - DEBUG UnitTestFramework: '#teardown: 'emits incomingConnectionState''

2016-09-30 15:23:49 - DEBUG UnitTestFramework: '#teardown ok: 'emits incomingConnectionState''

2016-09-30 15:23:49 - DEBUG UnitTestFramework: '#setup: 'emits routerPortConnectionFailed''

2016-09-30 15:23:50 - DEBUG UnitTestFramework: '#setup ok: 'emits routerPortConnectionFailed''

2016-09-30 15:23:50 - DEBUG UnitTestFramework: '#run: 'emits routerPortConnectionFailed''

2016-09-30 15:23:50 - DEBUG UnitTestFramework: '#run ok: 'emits routerPortConnectionFailed''

2016-09-30 15:23:50 - DEBUG UnitTestFramework: '#teardown: 'emits routerPortConnectionFailed''

2016-09-30 15:23:51 - DEBUG UnitTestFramework: '#teardown ok: 'emits routerPortConnectionFailed''

2016-09-30 15:23:51 - DEBUG UnitTestFramework: '#setup: 'native server connections all up''

2016-09-30 15:23:51 - DEBUG UnitTestFramework: '#setup ok: 'native server connections all up''

2016-09-30 15:23:51 - DEBUG UnitTestFramework: '#run: 'native server connections all up''

2016-09-30 15:23:52 - DEBUG UnitTestFramework: '#run ok: 'native server connections all up''
2016-09-30 15:23:52 - DEBUG UnitTestFramework: '#teardown: 'native server connections all up''

2016-09-30 15:23:53 - DEBUG UnitTestFramework: '#teardown ok: 'native server connections all up''

2016-09-30 15:23:53 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming stream cleans outgoing socket''

2016-09-30 15:23:53 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming stream cleans outgoing socket''

2016-09-30 15:23:53 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming stream cleans outgoing socket''

2016-09-30 15:23:53 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming stream cleans outgoing socket''

2016-09-30 15:23:53 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming stream cleans outgoing socket''

2016-09-30 15:23:53 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming stream cleans outgoing socket''

2016-09-30 15:23:53 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming connection cleans outgoing socket''

2016-09-30 15:23:53 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming connection cleans outgoing socket''

2016-09-30 15:23:53 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming connection cleans outgoing socket''

2016-09-30 15:23:53 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming connection cleans outgoing socket''

2016-09-30 15:23:53 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming connection cleans outgoing socket''

2016-09-30 15:23:53 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming connection cleans outgoing socket''

2016-09-30 15:23:53 - DEBUG UnitTestFramework: '#setup: 'native server - closing outgoing socket cleans associated mux stream''

2016-09-30 15:23:53 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-09-30 15:23:53 - DEBUG UnitTestFramework: '#run: 'native server - closing outgoing socket cleans associated mux stream''

2016-09-30 15:23:53 - DEBUG UnitTestFramework: '#run ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-09-30 15:23:53 - DEBUG UnitTestFramework: '#teardown: 'native server - closing outgoing socket cleans associated mux stream''

2016-09-30 15:23:53 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-09-30 15:23:53 - DEBUG UnitTestFramework: '#setup: 'native server - closing the whole server cleans everything up''

2016-09-30 15:23:53 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing the whole server cleans everything up''

2016-09-30 15:23:53 - DEBUG UnitTestFramework: '#run: 'native server - closing the whole server cleans everything up''

2016-09-30 15:23:53 - DEBUG UnitTestFramework: '#run ok: 'native server - closing the whole server cleans everything up''

2016-09-30 15:23:53 - DEBUG UnitTestFramework: '#teardown: 'native server - closing the whole server cleans everything up''

2016-09-30 15:23:53 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing the whole server cleans everything up''

2016-09-30 15:23:53 - DEBUG UnitTestFramework: '#setup: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-09-30 15:23:53 - DEBUG UnitTestFramework: '#setup ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-09-30 15:23:53 - DEBUG UnitTestFramework: '#run: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-09-30 15:23:54 - DEBUG UnitTestFramework: '#run ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-09-30 15:23:54 - DEBUG UnitTestFramework: '#teardown: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-09-30 15:23:56 - DEBUG UnitTestFramework: '#teardown ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-09-30 15:23:56 - DEBUG UnitTestFramework: '#setup: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-09-30 15:23:56 - DEBUG UnitTestFramework: '#setup ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-09-30 15:23:56 - DEBUG UnitTestFramework: '#run: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-09-30 15:23:56 - DEBUG UnitTestFramework: '#run ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-09-30 15:23:56 - DEBUG UnitTestFramework: '#teardown: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-09-30 15:23:57 - DEBUG UnitTestFramework: '#teardown ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-09-30 15:23:57 - DEBUG UnitTestFramework: '#setup: 'native server - timing out the incoming connection cleans everything up''

2016-09-30 15:23:58 - DEBUG UnitTestFramework: '#setup ok: 'native server - timing out the incoming connection cleans everything up''

2016-09-30 15:23:58 - DEBUG UnitTestFramework: '#run: 'native server - timing out the incoming connection cleans everything up''

2016-09-30 15:23:58 - DEBUG UnitTestFramework: '#run ok: 'native server - timing out the incoming connection cleans everything up''

2016-09-30 15:23:58 - DEBUG UnitTestFramework: '#teardown: 'native server - timing out the incoming connection cleans everything up''

2016-09-30 15:23:59 - DEBUG UnitTestFramework: '#teardown ok: 'native server - timing out the incoming connection cleans everything up''

2016-09-30 15:23:59 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server is not there''

2016-09-30 15:23:59 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server is not there''

2016-09-30 15:23:59 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server is not there''

2016-09-30 15:24:00 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server is not there''
2016-09-30 15:24:00 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server is not there''

2016-09-30 15:24:01 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server is not there''

2016-09-30 15:24:01 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-09-30 15:24:02 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-09-30 15:24:02 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-09-30 15:24:03 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-09-30 15:24:03 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-09-30 15:24:03 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-09-30 15:24:03 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server always returns 500''

2016-09-30 15:24:04 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-09-30 15:24:04 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server always returns 500''

2016-09-30 15:24:05 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-09-30 15:24:05 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server always returns 500''

2016-09-30 15:24:05 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-09-30 15:24:05 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - create new seq doc''

2016-09-30 15:24:06 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-09-30 15:24:06 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - create new seq doc''

2016-09-30 15:24:07 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-09-30 15:24:07 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - create new seq doc''

2016-09-30 15:24:08 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-09-30 15:24:08 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-09-30 15:24:08 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-09-30 15:24:08 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-09-30 15:24:09 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-09-30 15:24:09 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-09-30 15:24:10 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-09-30 15:24:10 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - update seq three times''

2016-09-30 15:24:11 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - update seq three times''

2016-09-30 15:24:11 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - update seq three times''

2016-09-30 15:24:12 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - update seq three times''

2016-09-30 15:24:12 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - update seq three times''

2016-09-30 15:24:13 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - update seq three times''

2016-09-30 15:24:13 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - rev got changed under us''

2016-09-30 15:24:14 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-09-30 15:24:14 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - rev got changed under us''

2016-09-30 15:24:15 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-09-30 15:24:15 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - rev got changed under us''

2016-09-30 15:24:16 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-09-30 15:24:16 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - fail if stop is called''

2016-09-30 15:24:16 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-09-30 15:24:16 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - fail if stop is called''

2016-09-30 15:24:17 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-09-30 15:24:17 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - fail if stop is called''

2016-09-30 15:24:17 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-09-30 15:24:17 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-09-30 15:24:17 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-09-30 15:24:17 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-09-30 15:24:18 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-09-30 15:24:18 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-09-30 15:24:18 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-09-30 15:24:18 - DEBUG UnitTestFramework: '#setup: '#update - fail if stop is called''

2016-09-30 15:24:19 - DEBUG UnitTestFramework: '#setup ok: '#update - fail if stop is called''

2016-09-30 15:24:19 - DEBUG UnitTestFramework: '#run: '#update - fail if stop is called''

2016-09-30 15:24:19 - DEBUG UnitTestFramework: '#run ok: '#update - fail if stop is called''

2016-09-30 15:24:19 - DEBUG UnitTestFramework: '#teardown: '#update - fail if stop is called''

2016-09-30 15:24:20 - DEBUG UnitTestFramework: '#teardown ok: '#update - fail if stop is called''

2016-09-30 15:24:20 - DEBUG UnitTestFramework: '#setup: '#update - set seq for first time''

2016-09-30 15:24:21 - DEBUG UnitTestFramework: '#setup ok: '#update - set seq for first time''

2016-09-30 15:24:21 - DEBUG UnitTestFramework: '#run: '#update - set seq for first time''

2016-09-30 15:24:22 - DEBUG UnitTestFramework: '#run ok: '#update - set seq for first time''

2016-09-30 15:24:22 - DEBUG UnitTestFramework: '#teardown: '#update - set seq for first time''

2016-09-30 15:24:23 - DEBUG UnitTestFramework: '#teardown ok: '#update - set seq for first time''

2016-09-30 15:24:23 - DEBUG UnitTestFramework: '#setup: '#update - Fail on bad seq value''

2016-09-30 15:24:23 - DEBUG UnitTestFramework: '#setup ok: '#update - Fail on bad seq value''

2016-09-30 15:24:23 - DEBUG UnitTestFramework: '#run: '#update - Fail on bad seq value''

2016-09-30 15:24:24 - DEBUG UnitTestFramework: '#run ok: '#update - Fail on bad seq value''

2016-09-30 15:24:24 - DEBUG UnitTestFramework: '#teardown: '#update - Fail on bad seq value''

2016-09-30 15:24:25 - DEBUG UnitTestFramework: '#teardown ok: '#update - Fail on bad seq value''

2016-09-30 15:24:25 - DEBUG UnitTestFramework: '#setup: '#update - do we cancel timer properly on an immediate?''

2016-09-30 15:24:26 - DEBUG UnitTestFramework: '#setup ok: '#update - do we cancel timer properly on an immediate?''

2016-09-30 15:24:26 - DEBUG UnitTestFramework: '#run: '#update - do we cancel timer properly on an immediate?''

2016-09-30 15:24:27 - DEBUG UnitTestFramework: '#run ok: '#update - do we cancel timer properly on an immediate?''

2016-09-30 15:24:27 - DEBUG UnitTestFramework: '#teardown: '#update - do we cancel timer properly on an immediate?''

2016-09-30 15:24:27 - DEBUG UnitTestFramework: '#teardown ok: '#update - do we cancel timer properly on an immediate?''

2016-09-30 15:24:27 - DEBUG UnitTestFramework: '#setup: '#update - do we wait for blocked update''

2016-09-30 15:24:27 - DEBUG UnitTestFramework: '#setup ok: '#update - do we wait for blocked update''

2016-09-30 15:24:27 - DEBUG UnitTestFramework: '#run: '#update - do we wait for blocked update''

2016-09-30 15:24:28 - DEBUG UnitTestFramework: '#run ok: '#update - do we wait for blocked update''

2016-09-30 15:24:28 - DEBUG UnitTestFramework: '#teardown: '#update - do we wait for blocked update''

2016-09-30 15:24:28 - DEBUG UnitTestFramework: '#teardown ok: '#update - do we wait for blocked update''

2016-09-30 15:24:28 - DEBUG UnitTestFramework: '#setup: '#update - test that we wait long enough''

2016-09-30 15:24:28 - DEBUG UnitTestFramework: '#setup ok: '#update - test that we wait long enough''

2016-09-30 15:24:28 - DEBUG UnitTestFramework: '#run: '#update - test that we wait long enough''

2016-09-30 15:24:29 - DEBUG UnitTestFramework: '#run ok: '#update - test that we wait long enough''

2016-09-30 15:24:29 - DEBUG UnitTestFramework: '#teardown: '#update - test that we wait long enough''

2016-09-30 15:24:29 - DEBUG UnitTestFramework: '#teardown ok: '#update - test that we wait long enough''

2016-09-30 15:24:29 - DEBUG UnitTestFramework: '#setup: '#update - test that we pick up new sequences while we wait''

2016-09-30 15:24:29 - DEBUG UnitTestFramework: '#setup ok: '#update - test that we pick up new sequences while we wait''

2016-09-30 15:24:29 - DEBUG UnitTestFramework: '#run: '#update - test that we pick up new sequences while we wait''

2016-09-30 15:24:30 - DEBUG UnitTestFramework: '#run ok: '#update - test that we pick up new sequences while we wait''

2016-09-30 15:24:30 - DEBUG UnitTestFramework: '#teardown: '#update - test that we pick up new sequences while we wait''

2016-09-30 15:24:30 - DEBUG UnitTestFramework: '#teardown ok: '#update - test that we pick up new sequences while we wait''

2016-09-30 15:24:30 - DEBUG UnitTestFramework: '#setup: 'Coordinated seq test''

2016-09-30 15:24:30 - DEBUG UnitTestFramework: '#setup ok: 'Coordinated seq test''

2016-09-30 15:24:30 - DEBUG UnitTestFramework: '#run: 'Coordinated seq test''

2016-09-30 15:25:40 - INFO HttpServer: 'Socket to device name: 'Huawei-Nexus 6P' disconnected, reason: 'client namespace disconnect''

2016-09-30 15:27:31 - ERROR UnitTestFramework: '#run failed: 'Coordinated seq test', error: 'TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'', stack: 'TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'
    at afterTimeout (/home/pi/Test/server_87460634d91a0a5/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_87460634d91a0a5/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-09-30 15:27:31 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'android', error: 'TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'', stack: 'TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'
    at afterTimeout (/home/pi/Test/server_87460634d91a0a5/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_87460634d91a0a5/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-09-30 15:29:31 - DEBUG TestServer: 'completed'

2016-09-30 15:29:31 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2016-09-30 15:29:31 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''


 
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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/87460634d91a0a5_switch_jxcore-cordova_plugin_into_v8_version_larryonoff/thali05_samsung-SM-G930F.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/87460634d91a0a5_switch_jxcore-cordova_plugin_into_v8_version_larryonoff/thali05_samsung-SM-G935F.md)

[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/87460634d91a0a5_switch_jxcore-cordova_plugin_into_v8_version_larryonoff/thali05_Huawei-Nexus 6P.md)





#### Test 87119404f514987 Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-09-28 14:19:13 - INFO HttpServer: 'listening on *:3000'

2016-09-28 14:20:49 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '2288885b-74f2-40c1-b3f6-14407c424a4e', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true''

2016-09-28 14:20:49 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2016-09-28 14:20:50 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '0037749f-c7a0-40e8-a982-9e96136e2a82', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true''

2016-09-28 14:20:50 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2016-09-28 14:21:08 - DEBUG HttpServer: 'device presented, name: 'Huawei-Nexus 6P', uuid: '0fe91a03-216c-4be8-9fb5-0bffc32c1d95', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true''

2016-09-28 14:21:08 - DEBUG TestFramework: 'device added, name: 'Huawei-Nexus 6P''

2016-09-28 14:21:08 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2016-09-28 14:21:08 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2016-09-28 14:21:08 - DEBUG UnitTestFramework: 'scheduling tests'

2016-09-28 14:21:09 - DEBUG UnitTestFramework: 'tests scheduled'

2016-09-28 14:21:09 - DEBUG UnitTestFramework: '#setup: 'calling createNativeListener directly rejects''

2016-09-28 14:21:10 - DEBUG UnitTestFramework: '#setup ok: 'calling createNativeListener directly rejects''

2016-09-28 14:21:10 - DEBUG UnitTestFramework: '#run: 'calling createNativeListener directly rejects''

2016-09-28 14:21:10 - DEBUG UnitTestFramework: '#run ok: 'calling createNativeListener directly rejects''

2016-09-28 14:21:10 - DEBUG UnitTestFramework: '#teardown: 'calling createNativeListener directly rejects''

2016-09-28 14:21:10 - DEBUG UnitTestFramework: '#teardown ok: 'calling createNativeListener directly rejects''

2016-09-28 14:21:10 - DEBUG UnitTestFramework: '#setup: 'emits incomingConnectionState''

2016-09-28 14:21:10 - DEBUG UnitTestFramework: '#setup ok: 'emits incomingConnectionState''

2016-09-28 14:21:10 - DEBUG UnitTestFramework: '#run: 'emits incomingConnectionState''

2016-09-28 14:21:10 - DEBUG UnitTestFramework: '#run ok: 'emits incomingConnectionState''

2016-09-28 14:21:10 - DEBUG UnitTestFramework: '#teardown: 'emits incomingConnectionState''

2016-09-28 14:21:10 - DEBUG UnitTestFramework: '#teardown ok: 'emits incomingConnectionState''

2016-09-28 14:21:10 - DEBUG UnitTestFramework: '#setup: 'emits routerPortConnectionFailed''

2016-09-28 14:21:10 - DEBUG UnitTestFramework: '#setup ok: 'emits routerPortConnectionFailed''

2016-09-28 14:21:10 - DEBUG UnitTestFramework: '#run: 'emits routerPortConnectionFailed''

2016-09-28 14:21:10 - DEBUG UnitTestFramework: '#run ok: 'emits routerPortConnectionFailed''

2016-09-28 14:21:10 - DEBUG UnitTestFramework: '#teardown: 'emits routerPortConnectionFailed''

2016-09-28 14:21:11 - DEBUG UnitTestFramework: '#teardown ok: 'emits routerPortConnectionFailed''

2016-09-28 14:21:11 - DEBUG UnitTestFramework: '#setup: 'native server connections all up''

2016-09-28 14:21:12 - DEBUG UnitTestFramework: '#setup ok: 'native server connections all up''

2016-09-28 14:21:12 - DEBUG UnitTestFramework: '#run: 'native server connections all up''

2016-09-28 14:21:13 - DEBUG UnitTestFramework: '#run ok: 'native server connections all up''

2016-09-28 14:21:13 - DEBUG UnitTestFramework: '#teardown: 'native server connections all up''

2016-09-28 14:21:13 - DEBUG UnitTestFramework: '#teardown ok: 'native server connections all up''

2016-09-28 14:21:13 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming stream cleans outgoing socket''

2016-09-28 14:21:13 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming stream cleans outgoing socket''

2016-09-28 14:21:13 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming stream cleans outgoing socket''

2016-09-28 14:21:13 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming stream cleans outgoing socket''

2016-09-28 14:21:13 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming stream cleans outgoing socket''

2016-09-28 14:21:13 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming stream cleans outgoing socket''

2016-09-28 14:21:13 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming connection cleans outgoing socket''

2016-09-28 14:21:13 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming connection cleans outgoing socket''

2016-09-28 14:21:13 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming connection cleans outgoing socket''

2016-09-28 14:21:13 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming connection cleans outgoing socket''

2016-09-28 14:21:13 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming connection cleans outgoing socket''

2016-09-28 14:21:14 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming connection cleans outgoing socket''

2016-09-28 14:21:14 - DEBUG UnitTestFramework: '#setup: 'native server - closing outgoing socket cleans associated mux stream''

2016-09-28 14:21:14 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-09-28 14:21:14 - DEBUG UnitTestFramework: '#run: 'native server - closing outgoing socket cleans associated mux stream''

2016-09-28 14:21:14 - DEBUG UnitTestFramework: '#run ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-09-28 14:21:14 - DEBUG UnitTestFramework: '#teardown: 'native server - closing outgoing socket cleans associated mux stream''

2016-09-28 14:21:14 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-09-28 14:21:14 - DEBUG UnitTestFramework: '#setup: 'native server - closing the whole server cleans everything up''

2016-09-28 14:21:14 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing the whole server cleans everything up''

2016-09-28 14:21:14 - DEBUG UnitTestFramework: '#run: 'native server - closing the whole server cleans everything up''

2016-09-28 14:21:14 - DEBUG UnitTestFramework: '#run ok: 'native server - closing the whole server cleans everything up''

2016-09-28 14:21:14 - DEBUG UnitTestFramework: '#teardown: 'native server - closing the whole server cleans everything up''

2016-09-28 14:21:14 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing the whole server cleans everything up''

2016-09-28 14:21:14 - DEBUG UnitTestFramework: '#setup: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-09-28 14:21:14 - DEBUG UnitTestFramework: '#setup ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-09-28 14:21:14 - DEBUG UnitTestFramework: '#run: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-09-28 14:21:15 - DEBUG UnitTestFramework: '#run ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-09-28 14:21:15 - DEBUG UnitTestFramework: '#teardown: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-09-28 14:21:17 - DEBUG UnitTestFramework: '#teardown ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-09-28 14:21:17 - DEBUG UnitTestFramework: '#setup: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-09-28 14:21:17 - DEBUG UnitTestFramework: '#setup ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-09-28 14:21:17 - DEBUG UnitTestFramework: '#run: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-09-28 14:21:18 - DEBUG UnitTestFramework: '#run ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-09-28 14:21:18 - DEBUG UnitTestFramework: '#teardown: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-09-28 14:21:18 - DEBUG UnitTestFramework: '#teardown ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-09-28 14:21:18 - DEBUG UnitTestFramework: '#setup: 'native server - timing out the incoming connection cleans everything up''

2016-09-28 14:21:18 - DEBUG UnitTestFramework: '#setup ok: 'native server - timing out the incoming connection cleans everything up''

2016-09-28 14:21:18 - DEBUG UnitTestFramework: '#run: 'native server - timing out the incoming connection cleans everything up''

2016-09-28 14:21:18 - DEBUG UnitTestFramework: '#run ok: 'native server - timing out the incoming connection cleans everything up''

2016-09-28 14:21:18 - DEBUG UnitTestFramework: '#teardown: 'native server - timing out the incoming connection cleans everything up''

2016-09-28 14:21:18 - DEBUG UnitTestFramework: '#teardown ok: 'native server - timing out the incoming connection cleans everything up''

2016-09-28 14:21:18 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server is not there''

2016-09-28 14:21:18 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server is not there''

2016-09-28 14:21:18 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server is not there''

2016-09-28 14:21:19 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server is not there''

2016-09-28 14:21:19 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server is not there''

2016-09-28 14:21:19 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server is not there''

2016-09-28 14:21:19 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-09-28 14:21:19 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-09-28 14:21:19 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-09-28 14:21:19 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-09-28 14:21:19 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-09-28 14:21:19 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-09-28 14:21:19 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server always returns 500''

2016-09-28 14:21:19 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-09-28 14:21:19 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server always returns 500''

2016-09-28 14:21:19 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-09-28 14:21:19 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server always returns 500''

2016-09-28 14:21:19 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-09-28 14:21:19 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - create new seq doc''

2016-09-28 14:21:19 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-09-28 14:21:19 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - create new seq doc''

2016-09-28 14:21:21 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-09-28 14:21:21 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - create new seq doc''

2016-09-28 14:21:22 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-09-28 14:21:22 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-09-28 14:21:22 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-09-28 14:21:22 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-09-28 14:21:23 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-09-28 14:21:23 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-09-28 14:21:23 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-09-28 14:21:23 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - update seq three times''

2016-09-28 14:21:23 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - update seq three times''

2016-09-28 14:21:23 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - update seq three times''

2016-09-28 14:21:28 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - update seq three times''

2016-09-28 14:21:28 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - update seq three times''

2016-09-28 14:21:28 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - update seq three times''

2016-09-28 14:21:28 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - rev got changed under us''

2016-09-28 14:21:28 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-09-28 14:21:28 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - rev got changed under us''

2016-09-28 14:21:28 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-09-28 14:21:28 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - rev got changed under us''

2016-09-28 14:21:28 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-09-28 14:21:28 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - fail if stop is called''

2016-09-28 14:21:28 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-09-28 14:21:28 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - fail if stop is called''

2016-09-28 14:21:29 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-09-28 14:21:29 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - fail if stop is called''

2016-09-28 14:21:29 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-09-28 14:21:29 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-09-28 14:21:29 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-09-28 14:21:29 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-09-28 14:21:29 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-09-28 14:21:29 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-09-28 14:21:29 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-09-28 14:21:29 - DEBUG UnitTestFramework: '#setup: '#update - fail if stop is called''

2016-09-28 14:21:29 - DEBUG UnitTestFramework: '#setup ok: '#update - fail if stop is called''

2016-09-28 14:21:29 - DEBUG UnitTestFramework: '#run: '#update - fail if stop is called''

2016-09-28 14:21:29 - DEBUG UnitTestFramework: '#run ok: '#update - fail if stop is called''

2016-09-28 14:21:29 - DEBUG UnitTestFramework: '#teardown: '#update - fail if stop is called''

2016-09-28 14:21:29 - DEBUG UnitTestFramework: '#teardown ok: '#update - fail if stop is called''

2016-09-28 14:21:29 - DEBUG UnitTestFramework: '#setup: '#update - set seq for first time''

2016-09-28 14:21:30 - DEBUG UnitTestFramework: '#setup ok: '#update - set seq for first time''

2016-09-28 14:21:30 - DEBUG UnitTestFramework: '#run: '#update - set seq for first time''

2016-09-28 14:21:30 - DEBUG UnitTestFramework: '#run ok: '#update - set seq for first time''

2016-09-28 14:21:30 - DEBUG UnitTestFramework: '#teardown: '#update - set seq for first time''

2016-09-28 14:21:30 - DEBUG UnitTestFramework: '#teardown ok: '#update - set seq for first time''

2016-09-28 14:21:30 - DEBUG UnitTestFramework: '#setup: '#update - Fail on bad seq value''

2016-09-28 14:21:30 - DEBUG UnitTestFramework: '#setup ok: '#update - Fail on bad seq value''

2016-09-28 14:21:30 - DEBUG UnitTestFramework: '#run: '#update - Fail on bad seq value''

2016-09-28 14:21:31 - DEBUG UnitTestFramework: '#run ok: '#update - Fail on bad seq value''

2016-09-28 14:21:31 - DEBUG UnitTestFramework: '#teardown: '#update - Fail on bad seq value''

2016-09-28 14:21:31 - DEBUG UnitTestFramework: '#teardown ok: '#update - Fail on bad seq value''

2016-09-28 14:21:31 - DEBUG UnitTestFramework: '#setup: '#update - do we cancel timer properly on an immediate?''

2016-09-28 14:21:31 - DEBUG UnitTestFramework: '#setup ok: '#update - do we cancel timer properly on an immediate?''

2016-09-28 14:21:31 - DEBUG UnitTestFramework: '#run: '#update - do we cancel timer properly on an immediate?''

2016-09-28 14:21:33 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'transport close''

2016-09-28 14:22:32 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'client namespace disconnect''

2016-09-28 14:22:32 - INFO HttpServer: 'Socket to device name: 'Huawei-Nexus 6P' disconnected, reason: 'client namespace disconnect''

2016-09-28 14:24:31 - ERROR UnitTestFramework: '#run failed: '#update - do we cancel timer properly on an immediate?', error: 'TimeoutError: timeout exceeded, event: 'run_#update - do we cancel timer properly on an immediate?_finished', test: '#update - do we cancel timer properly on an immediate?'', stack: 'TimeoutError: timeout exceeded, event: 'run_#update - do we cancel timer properly on an immediate?_finished', test: '#update - do we cancel timer properly on an immediate?'
    at afterTimeout (/home/pi/Test/server_87119404f514987/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_87119404f514987/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-09-28 14:24:31 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'android', error: 'TimeoutError: timeout exceeded, event: 'run_#update - do we cancel timer properly on an immediate?_finished', test: '#update - do we cancel timer properly on an immediate?'', stack: 'TimeoutError: timeout exceeded, event: 'run_#update - do we cancel timer properly on an immediate?_finished', test: '#update - do we cancel timer properly on an immediate?'
    at afterTimeout (/home/pi/Test/server_87119404f514987/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_87119404f514987/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-09-28 14:26:31 - DEBUG TestServer: 'completed'


 
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

STOP log received from ce061606e320561102
Test has FAILED

STOP log received from ENU7N16516000107
Test has FAILED

Device test finished on ce061606e320561102 
Device test finished on ENU7N16516000107 
Error! Unexpected exit on device ce0616068b9f212302 app:com.test.thalitest code:null 
Child process exited with code null on device ce0616068b9f212302
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/87119404f514987_Move_off_JXcore_where_we_can_larryonoff/thali05_samsung-SM-G930F.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/87119404f514987_Move_off_JXcore_where_we_can_larryonoff/thali05_samsung-SM-G935F.md)

[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/87119404f514987_Move_off_JXcore_where_we_can_larryonoff/thali05_Huawei-Nexus 6P.md)





#### Test 87335608979c2c6 Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-09-29 18:38:08 - INFO HttpServer: 'listening on *:3000'

2016-09-29 18:39:53 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'd706b8a4-4b00-4bc7-b758-58d71b75376f', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true''

2016-09-29 18:39:53 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2016-09-29 18:39:53 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '0c307a56-efef-4ea3-8420-347aef571931', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true''

2016-09-29 18:39:53 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2016-09-29 18:40:08 - DEBUG HttpServer: 'device presented, name: 'Huawei-Nexus 6P', uuid: '4193500f-5969-4bfe-8f03-2838737b1616', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true''

2016-09-29 18:40:08 - DEBUG TestFramework: 'device added, name: 'Huawei-Nexus 6P''

2016-09-29 18:40:08 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2016-09-29 18:40:08 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2016-09-29 18:40:08 - DEBUG UnitTestFramework: 'scheduling tests'

2016-09-29 18:40:10 - DEBUG UnitTestFramework: 'tests scheduled'

2016-09-29 18:40:10 - DEBUG UnitTestFramework: '#setup: 'calling createNativeListener directly rejects''

2016-09-29 18:40:10 - DEBUG UnitTestFramework: '#setup ok: 'calling createNativeListener directly rejects''

2016-09-29 18:40:10 - DEBUG UnitTestFramework: '#run: 'calling createNativeListener directly rejects''

2016-09-29 18:40:10 - DEBUG UnitTestFramework: '#run ok: 'calling createNativeListener directly rejects''

2016-09-29 18:40:10 - DEBUG UnitTestFramework: '#teardown: 'calling createNativeListener directly rejects''

2016-09-29 18:40:10 - DEBUG UnitTestFramework: '#teardown ok: 'calling createNativeListener directly rejects''

2016-09-29 18:40:10 - DEBUG UnitTestFramework: '#setup: 'emits incomingConnectionState''

2016-09-29 18:40:10 - DEBUG UnitTestFramework: '#setup ok: 'emits incomingConnectionState''

2016-09-29 18:40:10 - DEBUG UnitTestFramework: '#run: 'emits incomingConnectionState''

2016-09-29 18:40:10 - DEBUG UnitTestFramework: '#run ok: 'emits incomingConnectionState''

2016-09-29 18:40:10 - DEBUG UnitTestFramework: '#teardown: 'emits incomingConnectionState''

2016-09-29 18:40:10 - DEBUG UnitTestFramework: '#teardown ok: 'emits incomingConnectionState''

2016-09-29 18:40:10 - DEBUG UnitTestFramework: '#setup: 'emits routerPortConnectionFailed''

2016-09-29 18:40:10 - DEBUG UnitTestFramework: '#setup ok: 'emits routerPortConnectionFailed''

2016-09-29 18:40:10 - DEBUG UnitTestFramework: '#run: 'emits routerPortConnectionFailed''

2016-09-29 18:40:10 - DEBUG UnitTestFramework: '#run ok: 'emits routerPortConnectionFailed''

2016-09-29 18:40:10 - DEBUG UnitTestFramework: '#teardown: 'emits routerPortConnectionFailed''

2016-09-29 18:40:11 - DEBUG UnitTestFramework: '#teardown ok: 'emits routerPortConnectionFailed''

2016-09-29 18:40:11 - DEBUG UnitTestFramework: '#setup: 'native server connections all up''

2016-09-29 18:40:11 - DEBUG UnitTestFramework: '#setup ok: 'native server connections all up''

2016-09-29 18:40:11 - DEBUG UnitTestFramework: '#run: 'native server connections all up''

2016-09-29 18:40:11 - DEBUG UnitTestFramework: '#run ok: 'native server connections all up''

2016-09-29 18:40:11 - DEBUG UnitTestFramework: '#teardown: 'native server connections all up''

2016-09-29 18:40:11 - DEBUG UnitTestFramework: '#teardown ok: 'native server connections all up''

2016-09-29 18:40:11 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming stream cleans outgoing socket''

2016-09-29 18:40:11 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming stream cleans outgoing socket''

2016-09-29 18:40:11 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming stream cleans outgoing socket''

2016-09-29 18:40:11 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming stream cleans outgoing socket''

2016-09-29 18:40:11 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming stream cleans outgoing socket''

2016-09-29 18:40:11 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming stream cleans outgoing socket''

2016-09-29 18:40:11 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming connection cleans outgoing socket''

2016-09-29 18:40:11 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming connection cleans outgoing socket''

2016-09-29 18:40:11 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming connection cleans outgoing socket''

2016-09-29 18:40:11 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming connection cleans outgoing socket''

2016-09-29 18:40:11 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming connection cleans outgoing socket''

2016-09-29 18:40:11 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming connection cleans outgoing socket''

2016-09-29 18:40:11 - DEBUG UnitTestFramework: '#setup: 'native server - closing outgoing socket cleans associated mux stream''

2016-09-29 18:40:11 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-09-29 18:40:11 - DEBUG UnitTestFramework: '#run: 'native server - closing outgoing socket cleans associated mux stream''

2016-09-29 18:40:11 - DEBUG UnitTestFramework: '#run ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-09-29 18:40:11 - DEBUG UnitTestFramework: '#teardown: 'native server - closing outgoing socket cleans associated mux stream''

2016-09-29 18:40:11 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-09-29 18:40:11 - DEBUG UnitTestFramework: '#setup: 'native server - closing the whole server cleans everything up''

2016-09-29 18:40:12 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing the whole server cleans everything up''

2016-09-29 18:40:12 - DEBUG UnitTestFramework: '#run: 'native server - closing the whole server cleans everything up''

2016-09-29 18:40:12 - DEBUG UnitTestFramework: '#run ok: 'native server - closing the whole server cleans everything up''

2016-09-29 18:40:12 - DEBUG UnitTestFramework: '#teardown: 'native server - closing the whole server cleans everything up''

2016-09-29 18:40:12 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing the whole server cleans everything up''

2016-09-29 18:40:12 - DEBUG UnitTestFramework: '#setup: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-09-29 18:40:12 - DEBUG UnitTestFramework: '#setup ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-09-29 18:40:12 - DEBUG UnitTestFramework: '#run: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-09-29 18:40:12 - DEBUG UnitTestFramework: '#run ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-09-29 18:40:12 - DEBUG UnitTestFramework: '#teardown: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-09-29 18:40:14 - DEBUG UnitTestFramework: '#teardown ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-09-29 18:40:14 - DEBUG UnitTestFramework: '#setup: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-09-29 18:40:14 - DEBUG UnitTestFramework: '#setup ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-09-29 18:40:14 - DEBUG UnitTestFramework: '#run: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-09-29 18:40:14 - DEBUG UnitTestFramework: '#run ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-09-29 18:40:14 - DEBUG UnitTestFramework: '#teardown: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-09-29 18:40:14 - DEBUG UnitTestFramework: '#teardown ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-09-29 18:40:14 - DEBUG UnitTestFramework: '#setup: 'native server - timing out the incoming connection cleans everything up''

2016-09-29 18:40:14 - DEBUG UnitTestFramework: '#setup ok: 'native server - timing out the incoming connection cleans everything up''

2016-09-29 18:40:14 - DEBUG UnitTestFramework: '#run: 'native server - timing out the incoming connection cleans everything up''

2016-09-29 18:40:14 - DEBUG UnitTestFramework: '#run ok: 'native server - timing out the incoming connection cleans everything up''

2016-09-29 18:40:14 - DEBUG UnitTestFramework: '#teardown: 'native server - timing out the incoming connection cleans everything up''

2016-09-29 18:40:14 - DEBUG UnitTestFramework: '#teardown ok: 'native server - timing out the incoming connection cleans everything up''

2016-09-29 18:40:14 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server is not there''

2016-09-29 18:40:14 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server is not there''

2016-09-29 18:40:14 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server is not there''

2016-09-29 18:40:15 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server is not there''

2016-09-29 18:40:15 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server is not there''

2016-09-29 18:40:15 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server is not there''

2016-09-29 18:40:15 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-09-29 18:40:15 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-09-29 18:40:15 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-09-29 18:40:15 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-09-29 18:40:15 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-09-29 18:40:15 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-09-29 18:40:15 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server always returns 500''

2016-09-29 18:40:15 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-09-29 18:40:15 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server always returns 500''

2016-09-29 18:40:15 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-09-29 18:40:15 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server always returns 500''

2016-09-29 18:40:15 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-09-29 18:40:15 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - create new seq doc''

2016-09-29 18:40:15 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-09-29 18:40:15 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - create new seq doc''

2016-09-29 18:40:17 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-09-29 18:40:17 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - create new seq doc''

2016-09-29 18:40:17 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-09-29 18:40:17 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-09-29 18:40:17 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-09-29 18:40:17 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-09-29 18:40:18 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-09-29 18:40:18 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-09-29 18:40:18 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-09-29 18:40:18 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - update seq three times''

2016-09-29 18:40:18 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - update seq three times''

2016-09-29 18:40:18 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - update seq three times''

2016-09-29 18:40:19 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - update seq three times''

2016-09-29 18:40:19 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - update seq three times''

2016-09-29 18:40:20 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - update seq three times''

2016-09-29 18:40:20 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - rev got changed under us''

2016-09-29 18:40:21 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-09-29 18:40:21 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - rev got changed under us''

2016-09-29 18:40:21 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-09-29 18:40:21 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - rev got changed under us''

2016-09-29 18:40:22 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-09-29 18:40:22 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - fail if stop is called''

2016-09-29 18:40:22 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-09-29 18:40:22 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - fail if stop is called''

2016-09-29 18:40:22 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-09-29 18:40:22 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - fail if stop is called''

2016-09-29 18:40:22 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-09-29 18:40:22 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-09-29 18:40:22 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-09-29 18:40:22 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-09-29 18:40:22 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-09-29 18:40:22 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-09-29 18:40:23 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-09-29 18:40:23 - DEBUG UnitTestFramework: '#setup: '#update - fail if stop is called''

2016-09-29 18:40:23 - DEBUG UnitTestFramework: '#setup ok: '#update - fail if stop is called''

2016-09-29 18:40:23 - DEBUG UnitTestFramework: '#run: '#update - fail if stop is called''

2016-09-29 18:40:23 - DEBUG UnitTestFramework: '#run ok: '#update - fail if stop is called''

2016-09-29 18:40:23 - DEBUG UnitTestFramework: '#teardown: '#update - fail if stop is called''

2016-09-29 18:40:23 - DEBUG UnitTestFramework: '#teardown ok: '#update - fail if stop is called''

2016-09-29 18:40:23 - DEBUG UnitTestFramework: '#setup: '#update - set seq for first time''

2016-09-29 18:40:23 - DEBUG UnitTestFramework: '#setup ok: '#update - set seq for first time''

2016-09-29 18:40:23 - DEBUG UnitTestFramework: '#run: '#update - set seq for first time''

2016-09-29 18:40:23 - DEBUG UnitTestFramework: '#run ok: '#update - set seq for first time''

2016-09-29 18:40:23 - DEBUG UnitTestFramework: '#teardown: '#update - set seq for first time''

2016-09-29 18:40:23 - DEBUG UnitTestFramework: '#teardown ok: '#update - set seq for first time''

2016-09-29 18:40:23 - DEBUG UnitTestFramework: '#setup: '#update - Fail on bad seq value''

2016-09-29 18:40:23 - DEBUG UnitTestFramework: '#setup ok: '#update - Fail on bad seq value''

2016-09-29 18:40:23 - DEBUG UnitTestFramework: '#run: '#update - Fail on bad seq value''

2016-09-29 18:40:24 - DEBUG UnitTestFramework: '#run ok: '#update - Fail on bad seq value''

2016-09-29 18:40:24 - DEBUG UnitTestFramework: '#teardown: '#update - Fail on bad seq value''

2016-09-29 18:40:24 - DEBUG UnitTestFramework: '#teardown ok: '#update - Fail on bad seq value''

2016-09-29 18:40:24 - DEBUG UnitTestFramework: '#setup: '#update - do we cancel timer properly on an immediate?''

2016-09-29 18:40:24 - DEBUG UnitTestFramework: '#setup ok: '#update - do we cancel timer properly on an immediate?''

2016-09-29 18:40:24 - DEBUG UnitTestFramework: '#run: '#update - do we cancel timer properly on an immediate?''

2016-09-29 18:40:26 - DEBUG UnitTestFramework: '#run ok: '#update - do we cancel timer properly on an immediate?''

2016-09-29 18:40:26 - DEBUG UnitTestFramework: '#teardown: '#update - do we cancel timer properly on an immediate?''

2016-09-29 18:40:26 - DEBUG UnitTestFramework: '#teardown ok: '#update - do we cancel timer properly on an immediate?''

2016-09-29 18:40:26 - DEBUG UnitTestFramework: '#setup: '#update - do we wait for blocked update''

2016-09-29 18:40:27 - DEBUG UnitTestFramework: '#setup ok: '#update - do we wait for blocked update''

2016-09-29 18:40:27 - DEBUG UnitTestFramework: '#run: '#update - do we wait for blocked update''

2016-09-29 18:40:28 - DEBUG UnitTestFramework: '#run ok: '#update - do we wait for blocked update''

2016-09-29 18:40:28 - DEBUG UnitTestFramework: '#teardown: '#update - do we wait for blocked update''

2016-09-29 18:40:28 - DEBUG UnitTestFramework: '#teardown ok: '#update - do we wait for blocked update''

2016-09-29 18:40:28 - DEBUG UnitTestFramework: '#setup: '#update - test that we wait long enough''

2016-09-29 18:40:28 - DEBUG UnitTestFramework: '#setup ok: '#update - test that we wait long enough''

2016-09-29 18:40:28 - DEBUG UnitTestFramework: '#run: '#update - test that we wait long enough''

2016-09-29 18:40:32 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'transport close''

2016-09-29 18:41:30 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'client namespace disconnect''

2016-09-29 18:41:30 - INFO HttpServer: 'Socket to device name: 'Huawei-Nexus 6P' disconnected, reason: 'client namespace disconnect''

2016-09-29 18:43:29 - ERROR UnitTestFramework: '#run failed: '#update - test that we wait long enough', error: 'TimeoutError: timeout exceeded, event: 'run_#update - test that we wait long enough_finished', test: '#update - test that we wait long enough'', stack: 'TimeoutError: timeout exceeded, event: 'run_#update - test that we wait long enough_finished', test: '#update - test that we wait long enough'
    at afterTimeout (/home/pi/Test/server_87335608979c2c6/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_87335608979c2c6/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-09-29 18:43:29 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'android', error: 'TimeoutError: timeout exceeded, event: 'run_#update - test that we wait long enough_finished', test: '#update - test that we wait long enough'', stack: 'TimeoutError: timeout exceeded, event: 'run_#update - test that we wait long enough_finished', test: '#update - test that we wait long enough'
    at afterTimeout (/home/pi/Test/server_87335608979c2c6/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_87335608979c2c6/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-09-29 18:45:29 - DEBUG TestServer: 'completed'


 
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

STOP log received from ce0616068b9f212302
Test has FAILED

STOP log received from ENU7N16516000107
Test has FAILED

Device test finished on ce0616068b9f212302 
Device test finished on ENU7N16516000107 
Error! Unexpected exit on device ce061606e320561102 app:com.test.thalitest code:null 
Child process exited with code null on device ce061606e320561102
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/87335608979c2c6__1165_Possible_workaround_artemjackson/thali05_samsung-SM-G930F.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/87335608979c2c6__1165_Possible_workaround_artemjackson/thali05_samsung-SM-G935F.md)

[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/87335608979c2c6__1165_Possible_workaround_artemjackson/thali05_Huawei-Nexus 6P.md)





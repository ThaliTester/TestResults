#### Test 899757342c9a24d Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-11-25 11:43:05 - INFO HttpServer: 'listening on *:3000'

2016-11-25 11:43:08 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '155fe22e-c819-44f8-bfdf-e965efb978bf', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-11-25 11:43:08 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2016-11-25 11:43:29 - DEBUG HttpServer: 'device presented, name: 'Huawei-Nexus 6P', uuid: '707db114-ff3d-4dad-9ca4-d4a7acbba33f', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-11-25 11:43:29 - DEBUG TestFramework: 'device added, name: 'Huawei-Nexus 6P''

2016-11-25 11:44:51 - DEBUG HttpServer: 'device presented, name: 'Huawei-Nexus 6P', uuid: '752f26e0-2749-49d2-88fa-9c51ddc0bacb', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-11-25 11:44:51 - DEBUG TestFramework: 'device added, name: 'Huawei-Nexus 6P''

2016-11-25 11:44:51 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2016-11-25 11:44:51 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2016-11-25 11:44:51 - DEBUG UnitTestFramework: 'scheduling tests'

2016-11-25 11:44:52 - DEBUG UnitTestFramework: 'tests scheduled'

2016-11-25 11:44:52 - DEBUG UnitTestFramework: '#setup: 'calling createNativeListener directly rejects''

2016-11-25 11:44:53 - DEBUG UnitTestFramework: '#setup ok: 'calling createNativeListener directly rejects''

2016-11-25 11:44:53 - DEBUG UnitTestFramework: '#run: 'calling createNativeListener directly rejects''

2016-11-25 11:44:53 - DEBUG UnitTestFramework: '#run ok: 'calling createNativeListener directly rejects''

2016-11-25 11:44:53 - DEBUG UnitTestFramework: '#teardown: 'calling createNativeListener directly rejects''

2016-11-25 11:44:53 - DEBUG UnitTestFramework: '#teardown ok: 'calling createNativeListener directly rejects''

2016-11-25 11:44:53 - DEBUG UnitTestFramework: '#setup: 'emits incomingConnectionState''

2016-11-25 11:44:53 - DEBUG UnitTestFramework: '#setup ok: 'emits incomingConnectionState''

2016-11-25 11:44:53 - DEBUG UnitTestFramework: '#run: 'emits incomingConnectionState''

2016-11-25 11:44:53 - DEBUG UnitTestFramework: '#run ok: 'emits incomingConnectionState''

2016-11-25 11:44:53 - DEBUG UnitTestFramework: '#teardown: 'emits incomingConnectionState''

2016-11-25 11:44:53 - DEBUG UnitTestFramework: '#teardown ok: 'emits incomingConnectionState''

2016-11-25 11:44:53 - DEBUG UnitTestFramework: '#setup: 'emits routerPortConnectionFailed''

2016-11-25 11:44:53 - DEBUG UnitTestFramework: '#setup ok: 'emits routerPortConnectionFailed''

2016-11-25 11:44:53 - DEBUG UnitTestFramework: '#run: 'emits routerPortConnectionFailed''

2016-11-25 11:44:54 - DEBUG UnitTestFramework: '#run ok: 'emits routerPortConnectionFailed''

2016-11-25 11:44:54 - DEBUG UnitTestFramework: '#teardown: 'emits routerPortConnectionFailed''

2016-11-25 11:44:54 - DEBUG UnitTestFramework: '#teardown ok: 'emits routerPortConnectionFailed''

2016-11-25 11:44:54 - DEBUG UnitTestFramework: '#setup: 'native server connections all up''

2016-11-25 11:44:54 - DEBUG UnitTestFramework: '#setup ok: 'native server connections all up''

2016-11-25 11:44:54 - DEBUG UnitTestFramework: '#run: 'native server connections all up''

2016-11-25 11:44:54 - DEBUG UnitTestFramework: '#run ok: 'native server connections all up''

2016-11-25 11:44:54 - DEBUG UnitTestFramework: '#teardown: 'native server connections all up''

2016-11-25 11:44:54 - DEBUG UnitTestFramework: '#teardown ok: 'native server connections all up''

2016-11-25 11:44:54 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming stream cleans outgoing socket''

2016-11-25 11:44:54 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming stream cleans outgoing socket''

2016-11-25 11:44:54 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming stream cleans outgoing socket''

2016-11-25 11:44:54 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming stream cleans outgoing socket''

2016-11-25 11:44:54 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming stream cleans outgoing socket''

2016-11-25 11:44:54 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming stream cleans outgoing socket''

2016-11-25 11:44:54 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming connection cleans outgoing socket''

2016-11-25 11:44:54 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming connection cleans outgoing socket''

2016-11-25 11:44:54 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming connection cleans outgoing socket''

2016-11-25 11:44:54 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming connection cleans outgoing socket''

2016-11-25 11:44:54 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming connection cleans outgoing socket''

2016-11-25 11:44:54 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming connection cleans outgoing socket''

2016-11-25 11:44:54 - DEBUG UnitTestFramework: '#setup: 'native server - closing outgoing socket cleans associated mux stream''

2016-11-25 11:44:54 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-11-25 11:44:54 - DEBUG UnitTestFramework: '#run: 'native server - closing outgoing socket cleans associated mux stream''

2016-11-25 11:44:54 - DEBUG UnitTestFramework: '#run ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-11-25 11:44:54 - DEBUG UnitTestFramework: '#teardown: 'native server - closing outgoing socket cleans associated mux stream''

2016-11-25 11:44:54 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-11-25 11:44:54 - DEBUG UnitTestFramework: '#setup: 'native server - closing the whole server cleans everything up''

2016-11-25 11:44:54 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing the whole server cleans everything up''

2016-11-25 11:44:54 - DEBUG UnitTestFramework: '#run: 'native server - closing the whole server cleans everything up''

2016-11-25 11:44:55 - DEBUG UnitTestFramework: '#run ok: 'native server - closing the whole server cleans everything up''

2016-11-25 11:44:55 - DEBUG UnitTestFramework: '#teardown: 'native server - closing the whole server cleans everything up''

2016-11-25 11:44:55 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing the whole server cleans everything up''

2016-11-25 11:44:55 - DEBUG UnitTestFramework: '#setup: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-11-25 11:44:55 - DEBUG UnitTestFramework: '#setup ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-11-25 11:44:55 - DEBUG UnitTestFramework: '#run: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-11-25 11:44:55 - DEBUG UnitTestFramework: '#run ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-11-25 11:44:55 - DEBUG UnitTestFramework: '#teardown: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-11-25 11:44:57 - DEBUG UnitTestFramework: '#teardown ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-11-25 11:44:57 - DEBUG UnitTestFramework: '#setup: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-11-25 11:44:57 - DEBUG UnitTestFramework: '#setup ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-11-25 11:44:57 - DEBUG UnitTestFramework: '#run: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-11-25 11:44:57 - DEBUG UnitTestFramework: '#run ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-11-25 11:44:57 - DEBUG UnitTestFramework: '#teardown: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-11-25 11:44:57 - DEBUG UnitTestFramework: '#teardown ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-11-25 11:44:57 - DEBUG UnitTestFramework: '#setup: 'native server - timing out the incoming connection cleans everything up''

2016-11-25 11:44:57 - DEBUG UnitTestFramework: '#setup ok: 'native server - timing out the incoming connection cleans everything up''

2016-11-25 11:44:57 - DEBUG UnitTestFramework: '#run: 'native server - timing out the incoming connection cleans everything up''

2016-11-25 11:44:57 - DEBUG UnitTestFramework: '#run ok: 'native server - timing out the incoming connection cleans everything up''

2016-11-25 11:44:57 - DEBUG UnitTestFramework: '#teardown: 'native server - timing out the incoming connection cleans everything up''

2016-11-25 11:44:57 - DEBUG UnitTestFramework: '#teardown ok: 'native server - timing out the incoming connection cleans everything up''

2016-11-25 11:44:57 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server is not there''

2016-11-25 11:44:57 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server is not there''

2016-11-25 11:44:57 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server is not there''

2016-11-25 11:44:58 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server is not there''

2016-11-25 11:44:58 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server is not there''

2016-11-25 11:44:58 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server is not there''

2016-11-25 11:44:58 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-11-25 11:44:58 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-11-25 11:44:58 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-11-25 11:44:58 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-11-25 11:44:58 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-11-25 11:44:58 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-11-25 11:44:58 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server always returns 500''

2016-11-25 11:44:58 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-11-25 11:44:58 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server always returns 500''

2016-11-25 11:44:58 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-11-25 11:44:58 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server always returns 500''

2016-11-25 11:44:58 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-11-25 11:44:58 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - create new seq doc''

2016-11-25 11:44:58 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-11-25 11:44:58 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - create new seq doc''

2016-11-25 11:45:00 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'transport close''

2016-11-25 11:46:00 - INFO HttpServer: 'Socket to device name: 'Huawei-Nexus 6P' disconnected, reason: 'client namespace disconnect''

2016-11-25 11:46:00 - INFO HttpServer: 'Socket to device name: 'Huawei-Nexus 6P' disconnected, reason: 'client namespace disconnect''

2016-11-25 11:47:58 - ERROR UnitTestFramework: '#run failed: '#_doImmediateSeqUpdate - create new seq doc', error: 'TimeoutError: timeout exceeded, event: 'run_#_doImmediateSeqUpdate - create new seq doc_finished', test: '#_doImmediateSeqUpdate - create new seq doc'', stack: 'TimeoutError: timeout exceeded, event: 'run_#_doImmediateSeqUpdate - create new seq doc_finished', test: '#_doImmediateSeqUpdate - create new seq doc'
    at afterTimeout (/home/pi/Test/server_899757342c9a24d/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_899757342c9a24d/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-11-25 11:47:58 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'android', error: 'TimeoutError: timeout exceeded, event: 'run_#_doImmediateSeqUpdate - create new seq doc_finished', test: '#_doImmediateSeqUpdate - create new seq doc'', stack: 'TimeoutError: timeout exceeded, event: 'run_#_doImmediateSeqUpdate - create new seq doc_finished', test: '#_doImmediateSeqUpdate - create new seq doc'
    at afterTimeout (/home/pi/Test/server_899757342c9a24d/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_899757342c9a24d/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-11-25 11:47:58 - ERROR HttpServer: 'unexpected server error: 'TimeoutError: timeout exceeded, event: 'run_#_doImmediateSeqUpdate - create new seq doc_finished', test: '#_doImmediateSeqUpdate - create new seq doc'''

2016-11-25 11:47:58 - ERROR HttpServer: 'unexpected server error: 'TimeoutError: timeout exceeded, event: 'run_#_doImmediateSeqUpdate - create new seq doc_finished', test: '#_doImmediateSeqUpdate - create new seq doc'''

2016-11-25 11:47:58 - ERROR HttpServer: 'unexpected server error: 'TimeoutError: timeout exceeded, event: 'run_#_doImmediateSeqUpdate - create new seq doc_finished', test: '#_doImmediateSeqUpdate - create new seq doc'''

2016-11-25 11:47:58 - ERROR UnitTestFramework: 'unexpected error: 'Error: TimeoutError: timeout exceeded, event: 'run_#_doImmediateSeqUpdate - create new seq doc_finished', test: '#_doImmediateSeqUpdate - create new seq doc'', stack: 'Error: TimeoutError: timeout exceeded, event: 'run_#_doImmediateSeqUpdate - create new seq doc_finished', test: '#_doImmediateSeqUpdate - create new seq doc'
    at Server._error (/home/pi/Test/server_899757342c9a24d/test/TestServer/HttpServer.js:77:9)
    at Socket.emit (events.js:82:17)
    at Socket.emit (/home/pi/Test/server_899757342c9a24d/test/TestServer/node_modules/socket.io/lib/socket.js:128:10)
    at updatedHandler (/home/pi/Test/server_899757342c9a24d/test/TestServer/Socket.js:103:29)
    at Socket._apply (/home/pi/Test/server_899757342c9a24d/test/TestServer/Socket.js:106:3)
    at emit (/home/pi/Test/server_899757342c9a24d/test/TestServer/Socket.js:165:22)
    at /home/pi/Test/server_899757342c9a24d/test/TestServer/Socket.js:169:5
    at Promise._execute (/home/pi/Test/server_899757342c9a24d/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_899757342c9a24d/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_899757342c9a24d/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Socket.emitData (/home/pi/Test/server_899757342c9a24d/test/TestServer/Socket.js:134:10)
    at TestDevice.error (/home/pi/Test/server_899757342c9a24d/test/TestServer/TestDevice.js:134:23)
    at /home/pi/Test/server_899757342c9a24d/test/TestServer/UnitTestFramework.js:87:23
    at Array.map (native)
    at /home/pi/Test/server_899757342c9a24d/test/TestServer/UnitTestFramework.js:86:15
    at tryCatcher (/home/pi/Test/server_899757342c9a24d/test/TestServer/node_modules/bluebird/js/release/util.js:16:23)''

2016-11-25 11:47:58 - ERROR UnitTestFramework: 'unexpected error: 'Error: TimeoutError: timeout exceeded, event: 'run_#_doImmediateSeqUpdate - create new seq doc_finished', test: '#_doImmediateSeqUpdate - create new seq doc'', stack: 'Error: TimeoutError: timeout exceeded, event: 'run_#_doImmediateSeqUpdate - create new seq doc_finished', test: '#_doImmediateSeqUpdate - create new seq doc'
    at Server._error (/home/pi/Test/server_899757342c9a24d/test/TestServer/HttpServer.js:77:9)
    at Socket.emit (events.js:82:17)
    at Socket.emit (/home/pi/Test/server_899757342c9a24d/test/TestServer/node_modules/socket.io/lib/socket.js:128:10)
    at updatedHandler (/home/pi/Test/server_899757342c9a24d/test/TestServer/Socket.js:103:29)
    at Socket._apply (/home/pi/Test/server_899757342c9a24d/test/TestServer/Socket.js:106:3)
    at emit (/home/pi/Test/server_899757342c9a24d/test/TestServer/Socket.js:165:22)
    at /home/pi/Test/server_899757342c9a24d/test/TestServer/Socket.js:169:5
    at Promise._execute (/home/pi/Test/server_899757342c9a24d/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_899757342c9a24d/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_899757342c9a24d/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Socket.emitData (/home/pi/Test/server_899757342c9a24d/test/TestServer/Socket.js:134:10)
    at TestDevice.error (/home/pi/Test/server_899757342c9a24d/test/TestServer/TestDevice.js:134:23)
    at /home/pi/Test/server_899757342c9a24d/test/TestServer/UnitTestFramework.js:87:23
    at Array.map (native)
    at /home/pi/Test/server_899757342c9a24d/test/TestServer/UnitTestFramework.js:86:15
    at tryCatcher (/home/pi/Test/server_899757342c9a24d/test/TestServer/node_modules/bluebird/js/release/util.js:16:23)''

2016-11-25 11:47:58 - ERROR UnitTestFramework: 'unexpected error: 'Error: TimeoutError: timeout exceeded, event: 'run_#_doImmediateSeqUpdate - create new seq doc_finished', test: '#_doImmediateSeqUpdate - create new seq doc'', stack: 'Error: TimeoutError: timeout exceeded, event: 'run_#_doImmediateSeqUpdate - create new seq doc_finished', test: '#_doImmediateSeqUpdate - create new seq doc'
    at Server._error (/home/pi/Test/server_899757342c9a24d/test/TestServer/HttpServer.js:77:9)
    at Socket.emit (events.js:82:17)
    at Socket.emit (/home/pi/Test/server_899757342c9a24d/test/TestServer/node_modules/socket.io/lib/socket.js:128:10)
    at updatedHandler (/home/pi/Test/server_899757342c9a24d/test/TestServer/Socket.js:103:29)
    at Socket._apply (/home/pi/Test/server_899757342c9a24d/test/TestServer/Socket.js:106:3)
    at emit (/home/pi/Test/server_899757342c9a24d/test/TestServer/Socket.js:165:22)
    at /home/pi/Test/server_899757342c9a24d/test/TestServer/Socket.js:169:5
    at Promise._execute (/home/pi/Test/server_899757342c9a24d/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_899757342c9a24d/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_899757342c9a24d/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Socket.emitData (/home/pi/Test/server_899757342c9a24d/test/TestServer/Socket.js:134:10)
    at TestDevice.error (/home/pi/Test/server_899757342c9a24d/test/TestServer/TestDevice.js:134:23)
    at /home/pi/Test/server_899757342c9a24d/test/TestServer/UnitTestFramework.js:87:23
    at Array.map (native)
    at /home/pi/Test/server_899757342c9a24d/test/TestServer/UnitTestFramework.js:86:15
    at tryCatcher (/home/pi/Test/server_899757342c9a24d/test/TestServer/node_modules/bluebird/js/release/util.js:16:23)''

2016-11-25 11:49:59 - DEBUG TestServer: 'completed'


 
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

Error! Unexpected exit on device ce061606e320561102 app:com.test.thalitest code:null 
Child process exited with code null on device ce061606e320561102
Android task is completed. [FAILED]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/899757342c9a24d_Implemented_mobile_test_andrew-aladev/thali05_samsung-SM-G935F.md)

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
[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/899757342c9a24d_Implemented_mobile_test_andrew-aladev/thali06_Huawei-Nexus 6P.md)

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
[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/899757342c9a24d_Implemented_mobile_test_andrew-aladev/thali07_Huawei-Nexus 6P.md)





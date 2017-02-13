#### Test 9869411810654b3 Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2017-02-13 14:01:42 - INFO HttpServer: 'listening on *:3000'

2017-02-13 14:03:48 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'efbf8598-259a-4ddd-beac-84df6eb3c86c', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-13 14:03:48 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-02-13 14:03:52 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '80fee05c-7f05-4f6a-b7b3-4a8ad98997fa', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-13 14:03:52 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-02-13 14:05:18 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: 'a1b1d01c-328d-49af-a669-3370d6d5ef74', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-13 14:05:18 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-02-13 14:05:18 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-02-13 14:05:18 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-02-13 14:05:18 - DEBUG UnitTestFramework: 'scheduling tests'

2017-02-13 14:05:19 - DEBUG UnitTestFramework: 'tests scheduled'

2017-02-13 14:05:19 - DEBUG UnitTestFramework: '#setup: 'calling createNativeListener directly rejects''

2017-02-13 14:05:19 - DEBUG UnitTestFramework: '#setup ok: 'calling createNativeListener directly rejects''

2017-02-13 14:05:19 - DEBUG UnitTestFramework: '#run: 'calling createNativeListener directly rejects''

2017-02-13 14:05:19 - DEBUG UnitTestFramework: '#run ok: 'calling createNativeListener directly rejects''

2017-02-13 14:05:19 - DEBUG UnitTestFramework: '#teardown: 'calling createNativeListener directly rejects''

2017-02-13 14:05:19 - DEBUG UnitTestFramework: '#teardown ok: 'calling createNativeListener directly rejects''

2017-02-13 14:05:19 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server is not there''

2017-02-13 14:05:19 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server is not there''

2017-02-13 14:05:19 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server is not there''

2017-02-13 14:05:19 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server is not there''

2017-02-13 14:05:19 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server is not there''

2017-02-13 14:05:19 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server is not there''

2017-02-13 14:05:19 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server accepts & closes connection''

2017-02-13 14:05:19 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2017-02-13 14:05:19 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server accepts & closes connection''

2017-02-13 14:05:19 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2017-02-13 14:05:19 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server accepts & closes connection''

2017-02-13 14:05:19 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2017-02-13 14:05:19 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server always returns 500''

2017-02-13 14:05:19 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server always returns 500''

2017-02-13 14:05:19 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server always returns 500''

2017-02-13 14:05:20 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server always returns 500''

2017-02-13 14:05:20 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server always returns 500''

2017-02-13 14:05:20 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server always returns 500''

2017-02-13 14:05:20 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - create new seq doc''

2017-02-13 14:05:20 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - create new seq doc''

2017-02-13 14:05:20 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - create new seq doc''

2017-02-13 14:05:21 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - create new seq doc''

2017-02-13 14:05:21 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - create new seq doc''

2017-02-13 14:05:21 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - create new seq doc''

2017-02-13 14:05:21 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2017-02-13 14:05:21 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2017-02-13 14:05:21 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2017-02-13 14:05:22 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2017-02-13 14:05:22 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2017-02-13 14:05:22 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2017-02-13 14:05:22 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - update seq three times''

2017-02-13 14:05:22 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - update seq three times''

2017-02-13 14:05:22 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - update seq three times''

2017-02-13 14:05:24 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'transport close''

2017-02-13 14:06:26 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'client namespace disconnect''

2017-02-13 14:06:26 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'client namespace disconnect''

2017-02-13 14:08:22 - ERROR UnitTestFramework: '#run failed: '#_doImmediateSeqUpdate - update seq three times', error: 'TimeoutError: timeout exceeded, event: 'run_#_doImmediateSeqUpdate - update seq three times_finished', test: '#_doImmediateSeqUpdate - update seq three times'', stack: 'TimeoutError: timeout exceeded, event: 'run_#_doImmediateSeqUpdate - update seq three times_finished', test: '#_doImmediateSeqUpdate - update seq three times'
    at afterTimeout (/home/pi/Test/server_9869411810654b3/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_9869411810654b3/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-02-13 14:08:22 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'android', error: 'TimeoutError: timeout exceeded, event: 'run_#_doImmediateSeqUpdate - update seq three times_finished', test: '#_doImmediateSeqUpdate - update seq three times'', stack: 'TimeoutError: timeout exceeded, event: 'run_#_doImmediateSeqUpdate - update seq three times_finished', test: '#_doImmediateSeqUpdate - update seq three times'
    at afterTimeout (/home/pi/Test/server_9869411810654b3/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_9869411810654b3/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-02-13 14:08:22 - ERROR HttpServer: 'unexpected server error: 'TimeoutError: timeout exceeded, event: 'run_#_doImmediateSeqUpdate - update seq three times_finished', test: '#_doImmediateSeqUpdate - update seq three times'''

2017-02-13 14:08:22 - ERROR HttpServer: 'unexpected server error: 'TimeoutError: timeout exceeded, event: 'run_#_doImmediateSeqUpdate - update seq three times_finished', test: '#_doImmediateSeqUpdate - update seq three times'''

2017-02-13 14:08:22 - ERROR HttpServer: 'unexpected server error: 'TimeoutError: timeout exceeded, event: 'run_#_doImmediateSeqUpdate - update seq three times_finished', test: '#_doImmediateSeqUpdate - update seq three times'''

2017-02-13 14:08:22 - ERROR UnitTestFramework: 'unexpected error: 'Error: TimeoutError: timeout exceeded, event: 'run_#_doImmediateSeqUpdate - update seq three times_finished', test: '#_doImmediateSeqUpdate - update seq three times'', stack: 'Error: TimeoutError: timeout exceeded, event: 'run_#_doImmediateSeqUpdate - update seq three times_finished', test: '#_doImmediateSeqUpdate - update seq three times'
    at Server._error (/home/pi/Test/server_9869411810654b3/test/TestServer/HttpServer.js:77:9)
    at Socket.emit (events.js:82:17)
    at Socket.emit (/home/pi/Test/server_9869411810654b3/test/TestServer/node_modules/socket.io/lib/socket.js:128:10)
    at updatedHandler (/home/pi/Test/server_9869411810654b3/test/TestServer/Socket.js:103:29)
    at Socket._apply (/home/pi/Test/server_9869411810654b3/test/TestServer/Socket.js:106:3)
    at emit (/home/pi/Test/server_9869411810654b3/test/TestServer/Socket.js:165:22)
    at /home/pi/Test/server_9869411810654b3/test/TestServer/Socket.js:169:5
    at Promise._execute (/home/pi/Test/server_9869411810654b3/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_9869411810654b3/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_9869411810654b3/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Socket.emitData (/home/pi/Test/server_9869411810654b3/test/TestServer/Socket.js:134:10)
    at TestDevice.error (/home/pi/Test/server_9869411810654b3/test/TestServer/TestDevice.js:134:23)
    at /home/pi/Test/server_9869411810654b3/test/TestServer/UnitTestFramework.js:87:23
    at Array.map (native)
    at /home/pi/Test/server_9869411810654b3/test/TestServer/UnitTestFramework.js:86:15
    at tryCatcher (/home/pi/Test/server_9869411810654b3/test/TestServer/node_modules/bluebird/js/release/util.js:16:23)''
2017-02-13 14:08:22 - ERROR UnitTestFramework: 'unexpected error: 'Error: TimeoutError: timeout exceeded, event: 'run_#_doImmediateSeqUpdate - update seq three times_finished', test: '#_doImmediateSeqUpdate - update seq three times'', stack: 'Error: TimeoutError: timeout exceeded, event: 'run_#_doImmediateSeqUpdate - update seq three times_finished', test: '#_doImmediateSeqUpdate - update seq three times'
    at Server._error (/home/pi/Test/server_9869411810654b3/test/TestServer/HttpServer.js:77:9)
    at Socket.emit (events.js:82:17)
    at Socket.emit (/home/pi/Test/server_9869411810654b3/test/TestServer/node_modules/socket.io/lib/socket.js:128:10)
    at updatedHandler (/home/pi/Test/server_9869411810654b3/test/TestServer/Socket.js:103:29)
    at Socket._apply (/home/pi/Test/server_9869411810654b3/test/TestServer/Socket.js:106:3)
    at emit (/home/pi/Test/server_9869411810654b3/test/TestServer/Socket.js:165:22)
    at /home/pi/Test/server_9869411810654b3/test/TestServer/Socket.js:169:5
    at Promise._execute (/home/pi/Test/server_9869411810654b3/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_9869411810654b3/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_9869411810654b3/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Socket.emitData (/home/pi/Test/server_9869411810654b3/test/TestServer/Socket.js:134:10)
    at TestDevice.error (/home/pi/Test/server_9869411810654b3/test/TestServer/TestDevice.js:134:23)
    at /home/pi/Test/server_9869411810654b3/test/TestServer/UnitTestFramework.js:87:23
    at Array.map (native)
    at /home/pi/Test/server_9869411810654b3/test/TestServer/UnitTestFramework.js:86:15
    at tryCatcher (/home/pi/Test/server_9869411810654b3/test/TestServer/node_modules/bluebird/js/release/util.js:16:23)''

2017-02-13 14:08:22 - ERROR UnitTestFramework: 'unexpected error: 'Error: TimeoutError: timeout exceeded, event: 'run_#_doImmediateSeqUpdate - update seq three times_finished', test: '#_doImmediateSeqUpdate - update seq three times'', stack: 'Error: TimeoutError: timeout exceeded, event: 'run_#_doImmediateSeqUpdate - update seq three times_finished', test: '#_doImmediateSeqUpdate - update seq three times'
    at Server._error (/home/pi/Test/server_9869411810654b3/test/TestServer/HttpServer.js:77:9)
    at Socket.emit (events.js:82:17)
    at Socket.emit (/home/pi/Test/server_9869411810654b3/test/TestServer/node_modules/socket.io/lib/socket.js:128:10)
    at updatedHandler (/home/pi/Test/server_9869411810654b3/test/TestServer/Socket.js:103:29)
    at Socket._apply (/home/pi/Test/server_9869411810654b3/test/TestServer/Socket.js:106:3)
    at emit (/home/pi/Test/server_9869411810654b3/test/TestServer/Socket.js:165:22)
    at /home/pi/Test/server_9869411810654b3/test/TestServer/Socket.js:169:5
    at Promise._execute (/home/pi/Test/server_9869411810654b3/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_9869411810654b3/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_9869411810654b3/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Socket.emitData (/home/pi/Test/server_9869411810654b3/test/TestServer/Socket.js:134:10)
    at TestDevice.error (/home/pi/Test/server_9869411810654b3/test/TestServer/TestDevice.js:134:23)
    at /home/pi/Test/server_9869411810654b3/test/TestServer/UnitTestFramework.js:87:23
    at Array.map (native)
    at /home/pi/Test/server_9869411810654b3/test/TestServer/UnitTestFramework.js:86:15
    at tryCatcher (/home/pi/Test/server_9869411810654b3/test/TestServer/node_modules/bluebird/js/release/util.js:16:23)''

2017-02-13 14:10:22 - DEBUG TestServer: 'completed'

[0;31merror: command 'sudo jx ______.js android' failed with code 1, file 'bash' on line 30[0m
One or more Android tests are failed.
 [0m
index.js failed [ 1 ]

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/9869411810654b3_CI_sanity_check_czyzm/thali02_samsung-SM-G930F.md)

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
Test has FAILED

Device test finished on ce061606c181d71003 
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/9869411810654b3_CI_sanity_check_czyzm/thali03_samsung-SM-G930F.md)

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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/9869411810654b3_CI_sanity_check_czyzm/thali04_samsung-SM-G935F.md)





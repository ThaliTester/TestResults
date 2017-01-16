#### Test 98694118b530362 Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2017-01-16 14:16:32 - INFO HttpServer: 'listening on *:3000'

2017-01-16 14:18:11 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '0a04afe8-2545-4cad-87aa-8936e0a9b8a4', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-01-16 14:18:11 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-01-16 14:18:18 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '1847a9b4-8391-40f1-9fcb-c11a07d5fa36', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-01-16 14:18:18 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-01-16 14:20:09 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '981edb3b-e279-4808-9986-a390d2f092c2', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-01-16 14:20:09 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-01-16 14:20:09 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-01-16 14:20:09 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-01-16 14:20:09 - DEBUG UnitTestFramework: 'scheduling tests'

2017-01-16 14:20:10 - DEBUG UnitTestFramework: 'tests scheduled'

2017-01-16 14:20:10 - DEBUG UnitTestFramework: '#setup: 'calling createNativeListener directly rejects''

2017-01-16 14:20:10 - DEBUG UnitTestFramework: '#setup ok: 'calling createNativeListener directly rejects''

2017-01-16 14:20:10 - DEBUG UnitTestFramework: '#run: 'calling createNativeListener directly rejects''

2017-01-16 14:20:10 - DEBUG UnitTestFramework: '#run ok: 'calling createNativeListener directly rejects''

2017-01-16 14:20:10 - DEBUG UnitTestFramework: '#teardown: 'calling createNativeListener directly rejects''

2017-01-16 14:20:10 - DEBUG UnitTestFramework: '#teardown ok: 'calling createNativeListener directly rejects''

2017-01-16 14:20:10 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server is not there''

2017-01-16 14:20:10 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server is not there''

2017-01-16 14:20:10 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server is not there''

2017-01-16 14:20:11 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server is not there''

2017-01-16 14:20:11 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server is not there''

2017-01-16 14:20:11 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server is not there''

2017-01-16 14:20:11 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server accepts & closes connection''

2017-01-16 14:20:11 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2017-01-16 14:20:11 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server accepts & closes connection''

2017-01-16 14:20:11 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2017-01-16 14:20:11 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server accepts & closes connection''

2017-01-16 14:20:11 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2017-01-16 14:20:11 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server always returns 500''

2017-01-16 14:20:11 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server always returns 500''

2017-01-16 14:20:11 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server always returns 500''

2017-01-16 14:20:11 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server always returns 500''

2017-01-16 14:20:11 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server always returns 500''

2017-01-16 14:20:11 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server always returns 500''

2017-01-16 14:20:11 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - create new seq doc''

2017-01-16 14:20:11 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - create new seq doc''

2017-01-16 14:20:11 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - create new seq doc''

2017-01-16 14:20:12 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - create new seq doc''

2017-01-16 14:20:12 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - create new seq doc''

2017-01-16 14:20:12 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - create new seq doc''

2017-01-16 14:20:12 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2017-01-16 14:20:12 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2017-01-16 14:20:12 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2017-01-16 14:20:13 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2017-01-16 14:20:13 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2017-01-16 14:20:13 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2017-01-16 14:20:13 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - update seq three times''

2017-01-16 14:20:13 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - update seq three times''

2017-01-16 14:20:13 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - update seq three times''

2017-01-16 14:20:15 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'transport close''

2017-01-16 14:21:14 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'client namespace disconnect''

2017-01-16 14:21:14 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'client namespace disconnect''

2017-01-16 14:23:13 - ERROR UnitTestFramework: '#run failed: '#_doImmediateSeqUpdate - update seq three times', error: 'TimeoutError: timeout exceeded, event: 'run_#_doImmediateSeqUpdate - update seq three times_finished', test: '#_doImmediateSeqUpdate - update seq three times'', stack: 'TimeoutError: timeout exceeded, event: 'run_#_doImmediateSeqUpdate - update seq three times_finished', test: '#_doImmediateSeqUpdate - update seq three times'
    at afterTimeout (/home/pi/Test/server_98694118b530362/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_98694118b530362/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-01-16 14:23:13 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'android', error: 'TimeoutError: timeout exceeded, event: 'run_#_doImmediateSeqUpdate - update seq three times_finished', test: '#_doImmediateSeqUpdate - update seq three times'', stack: 'TimeoutError: timeout exceeded, event: 'run_#_doImmediateSeqUpdate - update seq three times_finished', test: '#_doImmediateSeqUpdate - update seq three times'
    at afterTimeout (/home/pi/Test/server_98694118b530362/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_98694118b530362/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-01-16 14:23:13 - ERROR HttpServer: 'unexpected server error: 'TimeoutError: timeout exceeded, event: 'run_#_doImmediateSeqUpdate - update seq three times_finished', test: '#_doImmediateSeqUpdate - update seq three times'''

2017-01-16 14:23:13 - ERROR HttpServer: 'unexpected server error: 'TimeoutError: timeout exceeded, event: 'run_#_doImmediateSeqUpdate - update seq three times_finished', test: '#_doImmediateSeqUpdate - update seq three times'''

2017-01-16 14:23:13 - ERROR HttpServer: 'unexpected server error: 'TimeoutError: timeout exceeded, event: 'run_#_doImmediateSeqUpdate - update seq three times_finished', test: '#_doImmediateSeqUpdate - update seq three times'''

2017-01-16 14:23:13 - ERROR UnitTestFramework: 'unexpected error: 'Error: TimeoutError: timeout exceeded, event: 'run_#_doImmediateSeqUpdate - update seq three times_finished', test: '#_doImmediateSeqUpdate - update seq three times'', stack: 'Error: TimeoutError: timeout exceeded, event: 'run_#_doImmediateSeqUpdate - update seq three times_finished', test: '#_doImmediateSeqUpdate - update seq three times'
    at Server._error (/home/pi/Test/server_98694118b530362/test/TestServer/HttpServer.js:77:9)
    at Socket.emit (events.js:82:17)
    at Socket.emit (/home/pi/Test/server_98694118b530362/test/TestServer/node_modules/socket.io/lib/socket.js:128:10)
    at updatedHandler (/home/pi/Test/server_98694118b530362/test/TestServer/Socket.js:103:29)
    at Socket._apply (/home/pi/Test/server_98694118b530362/test/TestServer/Socket.js:106:3)
    at emit (/home/pi/Test/server_98694118b530362/test/TestServer/Socket.js:165:22)
    at /home/pi/Test/server_98694118b530362/test/TestServer/Socket.js:169:5
    at Promise._execute (/home/pi/Test/server_98694118b530362/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_98694118b530362/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_98694118b530362/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Socket.emitData (/home/pi/Test/server_98694118b530362/test/TestServer/Socket.js:134:10)
    at TestDevice.error (/home/pi/Test/server_98694118b530362/test/TestServer/TestDevice.js:134:23)
    at /home/pi/Test/server_98694118b530362/test/TestServer/UnitTestFramework.js:87:23
    at Array.map (native)
    at /home/pi/Test/server_98694118b530362/test/TestServer/UnitTestFramework.js:86:15
    at tryCatcher (/home/pi/Test/server_98694118b530362/test/TestServer/node_modules/bluebird/js/release/util.js:16:23)''
2017-01-16 14:23:13 - ERROR UnitTestFramework: 'unexpected error: 'Error: TimeoutError: timeout exceeded, event: 'run_#_doImmediateSeqUpdate - update seq three times_finished', test: '#_doImmediateSeqUpdate - update seq three times'', stack: 'Error: TimeoutError: timeout exceeded, event: 'run_#_doImmediateSeqUpdate - update seq three times_finished', test: '#_doImmediateSeqUpdate - update seq three times'
    at Server._error (/home/pi/Test/server_98694118b530362/test/TestServer/HttpServer.js:77:9)
    at Socket.emit (events.js:82:17)
    at Socket.emit (/home/pi/Test/server_98694118b530362/test/TestServer/node_modules/socket.io/lib/socket.js:128:10)
    at updatedHandler (/home/pi/Test/server_98694118b530362/test/TestServer/Socket.js:103:29)
    at Socket._apply (/home/pi/Test/server_98694118b530362/test/TestServer/Socket.js:106:3)
    at emit (/home/pi/Test/server_98694118b530362/test/TestServer/Socket.js:165:22)
    at /home/pi/Test/server_98694118b530362/test/TestServer/Socket.js:169:5
    at Promise._execute (/home/pi/Test/server_98694118b530362/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_98694118b530362/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_98694118b530362/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Socket.emitData (/home/pi/Test/server_98694118b530362/test/TestServer/Socket.js:134:10)
    at TestDevice.error (/home/pi/Test/server_98694118b530362/test/TestServer/TestDevice.js:134:23)
    at /home/pi/Test/server_98694118b530362/test/TestServer/UnitTestFramework.js:87:23
    at Array.map (native)
    at /home/pi/Test/server_98694118b530362/test/TestServer/UnitTestFramework.js:86:15
    at tryCatcher (/home/pi/Test/server_98694118b530362/test/TestServer/node_modules/bluebird/js/release/util.js:16:23)''

2017-01-16 14:23:13 - ERROR UnitTestFramework: 'unexpected error: 'Error: TimeoutError: timeout exceeded, event: 'run_#_doImmediateSeqUpdate - update seq three times_finished', test: '#_doImmediateSeqUpdate - update seq three times'', stack: 'Error: TimeoutError: timeout exceeded, event: 'run_#_doImmediateSeqUpdate - update seq three times_finished', test: '#_doImmediateSeqUpdate - update seq three times'
    at Server._error (/home/pi/Test/server_98694118b530362/test/TestServer/HttpServer.js:77:9)
    at Socket.emit (events.js:82:17)
    at Socket.emit (/home/pi/Test/server_98694118b530362/test/TestServer/node_modules/socket.io/lib/socket.js:128:10)
    at updatedHandler (/home/pi/Test/server_98694118b530362/test/TestServer/Socket.js:103:29)
    at Socket._apply (/home/pi/Test/server_98694118b530362/test/TestServer/Socket.js:106:3)
    at emit (/home/pi/Test/server_98694118b530362/test/TestServer/Socket.js:165:22)
    at /home/pi/Test/server_98694118b530362/test/TestServer/Socket.js:169:5
    at Promise._execute (/home/pi/Test/server_98694118b530362/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_98694118b530362/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_98694118b530362/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Socket.emitData (/home/pi/Test/server_98694118b530362/test/TestServer/Socket.js:134:10)
    at TestDevice.error (/home/pi/Test/server_98694118b530362/test/TestServer/TestDevice.js:134:23)
    at /home/pi/Test/server_98694118b530362/test/TestServer/UnitTestFramework.js:87:23
    at Array.map (native)
    at /home/pi/Test/server_98694118b530362/test/TestServer/UnitTestFramework.js:86:15
    at tryCatcher (/home/pi/Test/server_98694118b530362/test/TestServer/node_modules/bluebird/js/release/util.js:16:23)''

2017-01-16 14:25:14 - DEBUG TestServer: 'completed'

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/98694118b530362_CI_sanity_check_czyzm/thali02_samsung-SM-G930F.md)

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

Error! Unexpected exit on device ce061606c181d71003 app:com.test.thalitest code:null 
Child process exited with code null on device ce061606c181d71003
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/98694118b530362_CI_sanity_check_czyzm/thali03_samsung-SM-G930F.md)

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

STOP log received from ce061606e320561102
Test has FAILED

Device test finished on ce061606e320561102 
Android task is completed. [FAILED]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/98694118b530362_CI_sanity_check_czyzm/thali04_samsung-SM-G935F.md)





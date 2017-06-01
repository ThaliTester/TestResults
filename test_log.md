#### Test 113351851adc4b69 Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":3}}
2017-06-01 06:59:17 - INFO HttpServer: 'listening on *:3000'

2017-06-01 06:59:20 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: '66b84f7e-abf8-484a-8490-c0ad1bf607cf', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-01 06:59:20 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-mfts''

2017-06-01 06:59:21 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '1f48b40e-efa2-4b27-8479-709e7f7c9e95', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-01 06:59:21 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-air-2-1''

2017-06-01 06:59:23 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '1f48b40e-efa2-4b27-8479-709e7f7c9e95', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-01 06:59:23 - INFO TestFramework: 'updating existing device, name: 'Apple-ipad-air-2-1', uuid: '1f48b40e-efa2-4b27-8479-709e7f7c9e95', platformName: 'ios''

2017-06-01 06:59:24 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: '34be58dd-61e1-46c9-8d2d-59d0cb425446', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-01 06:59:24 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-1''

2017-06-01 06:59:24 - INFO TestFramework: 'all required 3 devices are present for platformName: 'ios''

2017-06-01 06:59:24 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'ios''

2017-06-01 06:59:24 - DEBUG UnitTestFramework: 'scheduling tests'

2017-06-01 06:59:29 - DEBUG UnitTestFramework: 'tests scheduled'

2017-06-01 06:59:29 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-06-01 06:59:49 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-06-01 06:59:49 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-06-01 06:59:52 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-06-01 06:59:52 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-06-01 06:59:55 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-06-01 06:59:55 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-06-01 07:00:07 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-06-01 07:00:07 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-06-01 07:00:08 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-06-01 07:00:08 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-06-01 07:00:08 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-06-01 07:00:08 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-01 07:00:09 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-01 07:00:09 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-01 07:00:11 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-01 07:00:11 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-01 07:00:17 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-01 07:00:17 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-01 07:00:17 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-01 07:00:17 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-01 07:00:17 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-01 07:00:17 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-01 07:00:25 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-01 07:00:25 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-06-01 07:00:34 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-01 07:00:34 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-06-01 07:00:34 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-01 07:00:35 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-01 07:00:38 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-01 07:00:38 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-01 07:00:38 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-06-01 07:00:39 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-01 07:00:39 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 07:00:40 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 07:00:40 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 07:00:40 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 07:00:40 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 07:00:41 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 07:00:41 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 07:00:41 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 07:00:42 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 07:00:42 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 07:00:43 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 07:00:43 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 07:00:43 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 07:00:44 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 07:00:44 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 07:00:44 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 07:00:44 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 07:00:45 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 07:00:45 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 07:00:47 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 07:00:47 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 07:00:47 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 07:00:49 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 07:00:50 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 07:00:50 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 07:00:50 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 07:00:50 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: 'ce4361bd-46ed-486f-81dc-aa99a974bccd', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-01 07:00:50 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-06-01 07:00:50 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 07:00:50 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-06-01 07:00:51 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-06-01 07:00:51 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-06-01 07:00:53 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-06-01 07:00:53 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-06-01 07:00:55 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-06-01 07:00:55 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-06-01 07:01:02 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'c529a63b-f727-427d-94be-4747c1cb5dbd', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-01 07:01:02 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-06-01 07:01:03 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-06-01 07:01:03 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-06-01 07:01:04 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-06-01 07:01:04 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-06-01 07:01:05 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-06-01 07:01:05 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-06-01 07:01:05 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-06-01 07:01:05 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-06-01 07:01:05 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-06-01 07:01:05 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-06-01 07:01:06 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-06-01 07:01:06 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-06-01 07:01:12 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-06-01 07:01:12 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-06-01 07:01:14 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-06-01 07:01:14 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-06-01 07:01:15 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-06-01 07:01:15 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-06-01 07:01:19 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-06-01 07:01:19 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-06-01 07:01:25 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-06-01 07:01:25 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-06-01 07:01:27 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-06-01 07:01:27 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-06-01 07:01:29 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-06-01 07:01:29 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-06-01 07:01:29 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-06-01 07:01:29 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-06-01 07:01:29 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-06-01 07:01:29 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-06-01 07:01:33 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-06-01 07:01:33 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-06-01 07:01:34 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-06-01 07:01:34 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-06-01 07:01:34 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-06-01 07:01:34 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-06-01 07:01:38 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-06-01 07:01:38 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-06-01 07:02:17 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-06-01 07:02:17 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-06-01 07:02:25 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'cb3ddb7f-7cae-4f7b-b895-64582b756a0a', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-01 07:02:25 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''
2017-06-01 07:02:25 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-06-01 07:02:25 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-06-01 07:02:25 - DEBUG UnitTestFramework: 'scheduling tests'

2017-06-01 07:03:17 - ERROR UnitTestFramework: '#run failed: 'exceptions in the executor are properly handled', error: 'TimeoutError: timeout exceeded, event: 'teardown_exceptions in the executor are properly handled_finished', test: 'exceptions in the executor are properly handled'', stack: 'TimeoutError: timeout exceeded, event: 'teardown_exceptions in the executor are properly handled_finished', test: 'exceptions in the executor are properly handled'
    at afterTimeout (/home/pi/Test/server_113351851adc4b69/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_113351851adc4b69/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-06-01 07:03:17 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'ios', error: 'TimeoutError: timeout exceeded, event: 'teardown_exceptions in the executor are properly handled_finished', test: 'exceptions in the executor are properly handled'', stack: 'TimeoutError: timeout exceeded, event: 'teardown_exceptions in the executor are properly handled_finished', test: 'exceptions in the executor are properly handled'
    at afterTimeout (/home/pi/Test/server_113351851adc4b69/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_113351851adc4b69/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-06-01 07:03:39 - DEBUG UnitTestFramework: 'tests scheduled'

2017-06-01 07:03:39 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-06-01 07:03:42 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-air-2-1' disconnected, reason: 'ping timeout''

2017-06-01 07:04:10 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-1' disconnected, reason: 'ping timeout''

2017-06-01 07:04:18 - ERROR Socket: 'unexpected error: 'Error: retry count exceed', stack: 'Error: retry count exceed
    at emit (/home/pi/Test/server_113351851adc4b69/test/TestServer/Socket.js:157:16)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-06-01 07:04:29 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '1f48b40e-efa2-4b27-8479-709e7f7c9e95', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-01 07:04:29 - INFO TestFramework: 'updating existing device, name: 'Apple-ipad-air-2-1', uuid: '1f48b40e-efa2-4b27-8479-709e7f7c9e95', platformName: 'ios''

2017-06-01 07:04:31 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '1f48b40e-efa2-4b27-8479-709e7f7c9e95', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-01 07:04:31 - INFO TestFramework: 'updating existing device, name: 'Apple-ipad-air-2-1', uuid: '1f48b40e-efa2-4b27-8479-709e7f7c9e95', platformName: 'ios''

2017-06-01 07:04:39 - ERROR UnitTestFramework: '#run failed: 'closeAll can close even when connections open', error: 'TimeoutError: timeout exceeded, event: 'setup_closeAll can close even when connections open_finished', test: 'closeAll can close even when connections open'', stack: 'TimeoutError: timeout exceeded, event: 'setup_closeAll can close even when connections open_finished', test: 'closeAll can close even when connections open'
    at afterTimeout (/home/pi/Test/server_113351851adc4b69/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_113351851adc4b69/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-06-01 07:04:39 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'android', error: 'TimeoutError: timeout exceeded, event: 'setup_closeAll can close even when connections open_finished', test: 'closeAll can close even when connections open'', stack: 'TimeoutError: timeout exceeded, event: 'setup_closeAll can close even when connections open_finished', test: 'closeAll can close even when connections open'
    at afterTimeout (/home/pi/Test/server_113351851adc4b69/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_113351851adc4b69/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-06-01 07:04:42 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: '34be58dd-61e1-46c9-8d2d-59d0cb425446', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-01 07:04:42 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-1', uuid: '34be58dd-61e1-46c9-8d2d-59d0cb425446', platformName: 'ios''

2017-06-01 07:04:42 - DEBUG TestServer: 'completed'

2017-06-01 07:04:42 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-mfts' disconnected, reason: 'undefined''
2017-06-01 07:04:42 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''
2017-06-01 07:04:42 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-06-01 07:04:42 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-06-01 07:04:42 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-air-2-1' disconnected, reason: 'undefined''

2017-06-01 07:04:42 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-1' disconnected, reason: 'undefined''

[0;31merror: command 'sudo jx ______.js all' failed with code 1, file 'bash' on line 30[0m
One or more Android tests are failed.
 [0m
index.js failed [ 1 ]

```


Logs for system : 
```

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!

ios : Error: Command failed: true
1/6/2017@08:56:02 Getting the list of iOS devices 
1/6/2017@08:56:03 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
1/6/2017@08:56:03 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
1/6/2017@08:56:03 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
1/6/2017@08:56:03 Deploying iOS test app 
1/6/2017@08:56:03 uninstalling the application 
1/6/2017@08:56:03 installing the application 
1/6/2017@09:19:22 ios: child process exited with code null on device bffa901fefdea07f59339a6737776943349f5077 
1/6/2017@09:19:22 ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
1/6/2017@09:19:22 ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
true

```
###Android Logs
####Node name: thali03
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

Error! Unexpected exit on device ce061606e320561102 app:com.thaliproject.thalitest code:null 
Child process exited with code null on device ce061606e320561102
Android task is completed. [FAILED]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/113351851adc4b69_CI_sanity_check_jareksl/thali03_samsung-SM-G935F.md)

####Node name: thali04
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

Error! Unexpected exit on device ce0616068b9f212302 app:com.thaliproject.thalitest code:null 
Child process exited with code null on device ce0616068b9f212302
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/113351851adc4b69_CI_sanity_check_jareksl/thali04_samsung-SM-G930F.md)

####Node name: thali05
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

Error! Unexpected exit on device ce061606c181d71003 app:com.thaliproject.thalitest code:null 
Child process exited with code null on device ce061606c181d71003
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/113351851adc4b69_CI_sanity_check_jareksl/thali05_samsung-SM-G930F.md)


###iOS Logs
[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/113351851adc4b69_CI_sanity_check_jareksl/iOS_iphone-5s-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/113351851adc4b69_CI_sanity_check_jareksl/iOS_iphone-5s-mfts.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/113351851adc4b69_CI_sanity_check_jareksl/iOS_ipad-air-2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/113351851adc4b69_CI_sanity_check_jareksl/iOS_server.md)





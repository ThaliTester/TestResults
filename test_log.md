#### Test 127198710fdd070d Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 2 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":3}}
2017-06-23 13:10:21 - INFO HttpServer: 'listening on *:3000'

2017-06-23 13:10:26 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: 'd5c095ca-f435-4f60-a651-34d6c8afb5ba', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-23 13:10:26 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-air-2-1''

2017-06-23 13:10:28 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: 'd5c095ca-f435-4f60-a651-34d6c8afb5ba', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-23 13:10:28 - INFO TestFramework: 'updating existing device, name: 'Apple-ipad-air-2-1', uuid: 'd5c095ca-f435-4f60-a651-34d6c8afb5ba', platformName: 'ios''

2017-06-23 13:10:29 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: 'dc199187-c564-42d5-80b8-d6a77c4c982e', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-23 13:10:29 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-1''

2017-06-23 13:10:32 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: 'dc199187-c564-42d5-80b8-d6a77c4c982e', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-23 13:10:32 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-1', uuid: 'dc199187-c564-42d5-80b8-d6a77c4c982e', platformName: 'ios''

2017-06-23 13:10:40 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: 'ce8b7047-53dd-4683-833e-70d84987d6a8', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-23 13:10:40 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-mfts''

2017-06-23 13:10:40 - INFO TestFramework: 'all required 3 devices are present for platformName: 'ios''

2017-06-23 13:10:40 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'ios''

2017-06-23 13:10:40 - DEBUG UnitTestFramework: 'scheduling tests'

2017-06-23 13:10:42 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: 'ce8b7047-53dd-4683-833e-70d84987d6a8', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-23 13:10:42 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-mfts', uuid: 'ce8b7047-53dd-4683-833e-70d84987d6a8', platformName: 'ios''

2017-06-23 13:10:47 - DEBUG UnitTestFramework: 'tests scheduled'

2017-06-23 13:10:47 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-06-23 13:11:07 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-06-23 13:11:07 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-06-23 13:11:07 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-06-23 13:11:07 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-06-23 13:11:07 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-06-23 13:11:07 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-06-23 13:11:08 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-06-23 13:11:08 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-06-23 13:11:28 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-06-23 13:11:28 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-06-23 13:11:32 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-06-23 13:11:32 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-23 13:11:33 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-23 13:11:33 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-23 13:11:33 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-23 13:11:33 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-23 13:11:39 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-23 13:11:39 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-23 13:11:41 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-23 13:11:41 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-23 13:11:42 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-23 13:11:42 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-23 13:11:44 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-23 13:11:44 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-06-23 13:11:48 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-23 13:11:48 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-06-23 13:11:49 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-23 13:11:49 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-23 13:11:50 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-23 13:11:50 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-23 13:11:50 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-06-23 13:11:50 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '619b3506-f7db-475d-a7c8-d380730f0019', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-23 13:11:50 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-06-23 13:11:53 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-23 13:11:53 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-23 13:11:54 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '60bd506c-88f4-4c25-a3ed-87bf8f55cd7b', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-23 13:11:54 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-06-23 13:11:56 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-23 13:11:56 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-23 13:11:56 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-23 13:11:57 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-23 13:11:57 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-23 13:11:57 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-23 13:11:57 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-23 13:12:07 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-23 13:12:07 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-23 13:12:13 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-23 13:12:13 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-23 13:12:13 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-23 13:12:13 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-23 13:12:17 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-23 13:12:17 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-23 13:12:17 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-23 13:12:21 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-23 13:12:21 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-23 13:12:22 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-23 13:12:22 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-23 13:12:22 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-23 13:12:22 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-23 13:12:22 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-23 13:12:22 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-23 13:12:22 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-23 13:12:25 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-23 13:12:25 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-06-23 13:12:27 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-06-23 13:12:27 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-06-23 13:12:30 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-06-23 13:12:30 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-06-23 13:12:32 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-06-23 13:12:32 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-06-23 13:12:37 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-06-23 13:12:37 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-06-23 13:12:37 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-06-23 13:12:37 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-06-23 13:12:39 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-06-23 13:12:39 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-06-23 13:12:41 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-06-23 13:12:41 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-06-23 13:12:47 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-06-23 13:12:47 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-06-23 13:12:49 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-06-23 13:12:49 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-06-23 13:12:56 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-06-23 13:12:56 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-06-23 13:13:01 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-06-23 13:13:01 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-06-23 13:13:05 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-06-23 13:13:05 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-06-23 13:13:17 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-06-23 13:13:17 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-06-23 13:13:25 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '3ca0261c-6388-48f7-a890-7fa8471d044a', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-23 13:13:25 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-06-23 13:13:25 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-06-23 13:13:25 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-06-23 13:13:25 - DEBUG UnitTestFramework: 'scheduling tests'

2017-06-23 13:13:25 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-06-23 13:13:25 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-06-23 13:13:28 - DEBUG UnitTestFramework: 'tests scheduled'

2017-06-23 13:13:28 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-06-23 13:13:28 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-06-23 13:13:28 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-06-23 13:13:30 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-06-23 13:13:30 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-06-23 13:13:32 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-06-23 13:13:32 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-06-23 13:13:37 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-06-23 13:13:37 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-06-23 13:13:41 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-06-23 13:13:41 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-06-23 13:13:49 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-06-23 13:13:49 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-23 13:13:49 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-23 13:13:49 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-23 13:13:49 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-23 13:13:49 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-23 13:13:50 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-23 13:13:50 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-23 13:13:52 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-23 13:13:52 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-23 13:14:13 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-23 13:14:13 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-23 13:14:24 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-23 13:14:24 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-06-23 13:14:25 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-23 13:14:25 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-06-23 13:14:25 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-23 13:14:25 - ERROR UnitTestFramework: '#run failed: 'mix enqueue and enqueueAtTop', error: 'TimeoutError: timeout exceeded, event: 'teardown_mix enqueue and enqueueAtTop_finished', test: 'mix enqueue and enqueueAtTop'', stack: 'TimeoutError: timeout exceeded, event: 'teardown_mix enqueue and enqueueAtTop_finished', test: 'mix enqueue and enqueueAtTop'
    at afterTimeout (/home/pi/Test/server_127198710fdd070d/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_127198710fdd070d/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-06-23 13:14:25 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'ios', error: 'TimeoutError: timeout exceeded, event: 'teardown_mix enqueue and enqueueAtTop_finished', test: 'mix enqueue and enqueueAtTop'', stack: 'TimeoutError: timeout exceeded, event: 'teardown_mix enqueue and enqueueAtTop_finished', test: 'mix enqueue and enqueueAtTop'
    at afterTimeout (/home/pi/Test/server_127198710fdd070d/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_127198710fdd070d/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-06-23 13:14:26 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-23 13:14:28 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-23 13:14:28 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-23 13:14:28 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-06-23 13:14:34 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-air-2-1' disconnected, reason: 'transport error''

2017-06-23 13:14:43 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-23 13:14:43 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-23 13:15:15 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-23 13:15:15 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-23 13:15:16 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-23 13:15:16 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-23 13:15:26 - ERROR Socket: 'unexpected error: 'Error: retry count exceed', stack: 'Error: retry count exceed
    at emit (/home/pi/Test/server_127198710fdd070d/test/TestServer/Socket.js:157:16)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-06-23 13:15:27 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-23 13:15:27 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-23 13:15:27 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-23 13:15:31 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-23 13:15:31 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-23 13:15:33 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-23 13:15:33 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-23 13:15:35 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-23 13:15:36 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-23 13:15:38 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-23 13:15:38 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-23 13:15:38 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-23 13:15:40 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-23 13:15:40 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-23 13:16:11 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-23 13:16:11 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-23 13:16:12 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-23 13:16:12 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-23 13:16:12 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-23 13:16:12 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-23 13:16:12 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-23 13:16:12 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-23 13:16:12 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-06-23 13:16:17 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-06-23 13:16:17 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-06-23 13:16:17 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-06-23 13:16:17 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-06-23 13:16:19 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-06-23 13:16:19 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-06-23 13:16:21 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-06-23 13:16:21 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-06-23 13:16:26 - ERROR UnitTestFramework: 'unexpected error: 'Error: retry count exceed', stack: 'Error: retry count exceed
    at emit (/home/pi/Test/server_127198710fdd070d/test/TestServer/Socket.js:157:16)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-06-23 13:16:26 - ERROR TestServerProcess: 'uncaught promise rejection, error: 'AssertionError: equals arrays expected, received array 1: '[object Object],[object Object],[object Object]', array 2: '[object Object],[object Object],[object Object]'', stack: 'AssertionError: equals arrays expected, received array 1: '[object Object],[object Object],[object Object]', array 2: '[object Object],[object Object],[object Object]'
    at Object.module.exports.arrayEquals (/home/pi/Test/server_127198710fdd070d/test/TestServer/utils/asserts.js:69:3)
    at UnitTestFramework.unbindSync (/home/pi/Test/server_127198710fdd070d/test/TestServer/UnitTestFramework.js:233:11)
    at /home/pi/Test/server_127198710fdd070d/test/TestServer/UnitTestFramework.js:100:10
    at PassThroughHandlerContext.finallyHandler (/home/pi/Test/server_127198710fdd070d/test/TestServer/node_modules/bluebird/js/release/finally.js:55:23)
    at PassThroughHandlerContext.tryCatcher (/home/pi/Test/server_127198710fdd070d/test/TestServer/node_modules/bluebird/js/release/util.js:16:23)
    at Promise._settlePromiseFromHandler (/home/pi/Test/server_127198710fdd070d/test/TestServer/node_modules/bluebird/js/release/promise.js:510:31)
    at Promise._settlePromise (/home/pi/Test/server_127198710fdd070d/test/TestServer/node_modules/bluebird/js/release/promise.js:567:18)
    at Promise._settlePromise0 (/home/pi/Test/server_127198710fdd070d/test/TestServer/node_modules/bluebird/js/release/promise.js:612:10)
    at Promise._settlePromises (/home/pi/Test/server_127198710fdd070d/test/TestServer/node_modules/bluebird/js/release/promise.js:691:18)
    at Promise._fulfill (/home/pi/Test/server_127198710fdd070d/test/TestServer/node_modules/bluebird/js/release/promise.js:636:18)
    at PromiseArray._resolve (/home/pi/Test/server_127198710fdd070d/test/TestServer/node_modules/bluebird/js/release/promise_array.js:125:19)
    at PromiseArray._promiseFulfilled (/home/pi/Test/server_127198710fdd070d/test/TestServer/node_modules/bluebird/js/release/promise_array.js:143:14)
    at Promise._settlePromise (/home/pi/Test/server_127198710fdd070d/test/TestServer/node_modules/bluebird/js/release/promise.js:572:26)
    at Promise._settlePromise0 (/home/pi/Test/server_127198710fdd070d/test/TestServer/node_modules/bluebird/js/release/promise.js:612:10)
    at Promise._settlePromises (/home/pi/Test/server_127198710fdd070d/test/TestServer/node_modules/bluebird/js/release/promise.js:691:18)
    at Async._drainQueue (/home/pi/Test/server_127198710fdd070d/test/TestServer/node_modules/bluebird/js/release/async.js:138:16)
    at Async._drainQueues (/home/pi/Test/server_127198710fdd070d/test/TestServer/node_modules/bluebird/js/release/async.js:148:10)
    at Async.drainQueues (/home/pi/Test/server_127198710fdd070d/test/TestServer/node_modules/bluebird/js/release/async.js:17:14)
    at process._tickCallback (node.js:917:13)''

2017-06-23 13:16:26 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-mfts' disconnected, reason: 'undefined''

2017-06-23 13:16:26 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-1' disconnected, reason: 'undefined''

2017-06-23 13:16:26 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-06-23 13:16:26 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-06-23 13:16:26 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''

[0;31merror: command 'sudo jx ______.js all' failed with code 1, file 'bash' on line 30[0m
One or more Android tests are failed.
 [0m
index.js failed [ 2 ]

```


Logs for system : 
```

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!

ios : Error: Command failed: true
23/6/2017@15:06:53 Getting the list of iOS devices 
23/6/2017@15:06:54 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
23/6/2017@15:06:54 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
23/6/2017@15:06:54 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
23/6/2017@15:06:54 Deploying iOS test app 
23/6/2017@15:06:54 uninstalling the application 
23/6/2017@15:06:54 installing the application 
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
App was succesfully deployed to ce061606e320561102

Starting application ThaliTest on ce061606e320561102

App was succesfully started on ce061606e320561102

Error! Unexpected exit on device ce061606e320561102 app:com.thaliproject.thalitest code:null 
Child process exited with code null on device ce061606e320561102
Android task is completed. [FAILED]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/127198710fdd070d_Fix_iOS_native_tests_mlesnic/thali03_samsung-SM-G935F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/127198710fdd070d_Fix_iOS_native_tests_mlesnic/thali04_samsung-SM-G930F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/127198710fdd070d_Fix_iOS_native_tests_mlesnic/thali05_samsung-SM-G930F.md)


###iOS Logs
[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/127198710fdd070d_Fix_iOS_native_tests_mlesnic/iOS_iphone-5s-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/127198710fdd070d_Fix_iOS_native_tests_mlesnic/iOS_iphone-5s-mfts.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/127198710fdd070d_Fix_iOS_native_tests_mlesnic/iOS_ipad-air-2-1.md)





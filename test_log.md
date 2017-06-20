#### Test 1265037342651392 Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":3}}
2017-06-20 19:40:28 - INFO HttpServer: 'listening on *:3000'

2017-06-20 19:40:31 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: 'f9967e61-ce59-4c80-8523-d14fddeba23d', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-20 19:40:31 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-air-2-1''

2017-06-20 19:40:33 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: 'f9967e61-ce59-4c80-8523-d14fddeba23d', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-20 19:40:33 - INFO TestFramework: 'updating existing device, name: 'Apple-ipad-air-2-1', uuid: 'f9967e61-ce59-4c80-8523-d14fddeba23d', platformName: 'ios''

2017-06-20 19:40:37 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: '88b32e2c-9630-4d78-af6a-5d5c9c919293', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-20 19:40:37 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-mfts''

2017-06-20 19:40:37 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: 'f23e9dcc-0234-4c24-9c0e-fa9e7c9e8a01', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-20 19:40:37 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-1''

2017-06-20 19:40:37 - INFO TestFramework: 'all required 3 devices are present for platformName: 'ios''

2017-06-20 19:40:37 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'ios''

2017-06-20 19:40:37 - DEBUG UnitTestFramework: 'scheduling tests'

2017-06-20 19:40:39 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: '88b32e2c-9630-4d78-af6a-5d5c9c919293', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-20 19:40:39 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-mfts', uuid: '88b32e2c-9630-4d78-af6a-5d5c9c919293', platformName: 'ios''

2017-06-20 19:40:39 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: 'f23e9dcc-0234-4c24-9c0e-fa9e7c9e8a01', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-20 19:40:39 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-1', uuid: 'f23e9dcc-0234-4c24-9c0e-fa9e7c9e8a01', platformName: 'ios''

2017-06-20 19:40:41 - DEBUG UnitTestFramework: 'tests scheduled'

2017-06-20 19:40:41 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-06-20 19:40:43 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-06-20 19:40:43 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-06-20 19:40:44 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-06-20 19:40:44 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-06-20 19:40:46 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-06-20 19:40:46 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-06-20 19:40:48 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-06-20 19:40:48 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-06-20 19:40:48 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-06-20 19:40:48 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-06-20 19:41:02 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-06-20 19:41:02 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-20 19:41:02 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-20 19:41:02 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-20 19:41:05 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-20 19:41:05 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-20 19:41:07 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-20 19:41:07 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-20 19:41:17 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-20 19:41:17 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-20 19:41:17 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-20 19:41:17 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-20 19:41:20 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-20 19:41:20 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-06-20 19:41:23 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-20 19:41:23 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-06-20 19:41:23 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-20 19:41:23 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-20 19:41:25 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-20 19:41:25 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-20 19:41:25 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-06-20 19:41:26 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-20 19:41:26 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 19:41:28 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 19:41:28 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 19:41:28 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 19:41:30 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 19:41:41 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'ba6ab9ab-7ce3-45fd-b1bc-5ee2e91b3133', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-20 19:41:41 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-06-20 19:41:47 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '5692515b-0def-4913-89b6-9f9458acb4f6', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-20 19:41:47 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-06-20 19:42:01 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 19:42:01 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 19:42:01 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 19:42:01 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 19:42:01 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 19:42:10 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 19:42:10 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 19:42:10 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 19:42:10 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 19:42:10 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 19:42:10 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 19:42:10 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 19:42:10 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 19:42:10 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 19:42:11 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 19:42:11 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 19:42:11 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 19:42:11 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 19:42:11 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 19:42:11 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 19:42:11 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 19:42:12 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 19:42:12 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-06-20 19:42:15 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-06-20 19:42:15 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-06-20 19:42:16 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-06-20 19:42:16 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-06-20 19:42:16 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-06-20 19:42:16 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-06-20 19:42:18 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-06-20 19:42:18 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-06-20 19:42:20 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-06-20 19:42:20 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-06-20 19:42:26 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-06-20 19:42:26 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-06-20 19:42:29 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-06-20 19:42:29 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-06-20 19:42:46 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-06-20 19:42:46 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-06-20 19:43:24 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-06-20 19:43:24 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-06-20 19:43:27 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-06-20 19:43:27 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-06-20 19:43:28 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-06-20 19:43:28 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-06-20 19:43:28 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-06-20 19:43:28 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-06-20 19:43:28 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-06-20 19:43:28 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-06-20 19:43:29 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-06-20 19:43:29 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-06-20 19:43:32 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-06-20 19:43:32 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-06-20 19:43:33 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-06-20 19:43:33 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-06-20 19:43:33 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-06-20 19:43:33 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-06-20 19:43:34 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-06-20 19:43:34 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-06-20 19:43:42 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-06-20 19:43:42 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-06-20 19:43:43 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '80600799-5b54-4d68-a330-5dd45e5ffc98', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-20 19:43:43 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-06-20 19:43:43 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-06-20 19:43:43 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''
2017-06-20 19:43:43 - DEBUG UnitTestFramework: 'scheduling tests'

2017-06-20 19:43:46 - DEBUG UnitTestFramework: 'tests scheduled'

2017-06-20 19:43:46 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-06-20 19:43:46 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-06-20 19:43:46 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-06-20 19:43:46 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-06-20 19:43:46 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-06-20 19:43:47 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-06-20 19:43:47 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-06-20 19:43:49 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-06-20 19:43:49 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-06-20 19:43:54 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-06-20 19:43:54 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-06-20 19:43:55 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-06-20 19:43:55 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-20 19:43:55 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-20 19:43:55 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-20 19:43:55 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-06-20 19:43:55 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-06-20 19:43:56 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-20 19:43:56 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-20 19:43:57 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-20 19:43:57 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-20 19:44:01 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-20 19:44:01 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-20 19:44:09 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-20 19:44:09 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-20 19:44:10 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-20 19:44:10 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-06-20 19:44:11 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-20 19:44:11 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-06-20 19:44:11 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-20 19:44:11 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-20 19:44:11 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-20 19:44:11 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-20 19:44:11 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-06-20 19:44:11 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-20 19:44:11 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 19:44:14 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 19:44:14 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 19:44:14 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 19:44:14 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 19:44:14 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 19:44:14 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 19:44:14 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 19:44:15 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 19:44:15 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 19:44:16 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 19:44:16 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 19:44:17 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 19:44:17 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 19:44:17 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 19:44:17 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 19:44:17 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 19:44:19 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 19:44:19 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 19:44:19 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 19:44:19 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 19:44:19 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 19:44:19 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 19:44:19 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 19:44:19 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 19:44:19 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 19:44:19 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 19:44:19 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-06-20 19:44:19 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-06-20 19:44:19 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-06-20 19:44:20 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-06-20 19:44:20 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-06-20 19:44:21 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-06-20 19:44:21 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-06-20 19:44:22 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-06-20 19:44:22 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-06-20 19:44:23 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-06-20 19:44:23 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-06-20 19:44:24 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-06-20 19:44:24 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-06-20 19:44:25 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-06-20 19:44:25 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-06-20 19:44:25 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-06-20 19:44:25 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-06-20 19:44:25 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-06-20 19:44:25 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-06-20 19:44:25 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-06-20 19:44:25 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-06-20 19:44:25 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-06-20 19:44:25 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-06-20 19:44:25 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-06-20 19:44:25 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-06-20 19:44:26 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-06-20 19:44:26 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-06-20 19:44:26 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-06-20 19:44:26 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-06-20 19:44:26 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-06-20 19:44:26 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-06-20 19:44:26 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-06-20 19:44:26 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-06-20 19:44:26 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-06-20 19:44:26 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-06-20 19:44:26 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-06-20 19:44:26 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-06-20 19:44:26 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-06-20 19:44:26 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-06-20 19:44:26 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-06-20 19:44:26 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-06-20 19:44:26 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-06-20 19:44:26 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-06-20 19:44:26 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-06-20 19:44:26 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-06-20 19:44:26 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-06-20 19:44:26 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-06-20 19:44:26 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-06-20 19:44:26 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-06-20 19:44:26 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-06-20 19:44:26 - DEBUG UnitTestFramework: '#run: 'basic''

2017-06-20 19:44:26 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-06-20 19:44:26 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-06-20 19:44:26 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-06-20 19:44:26 - DEBUG UnitTestFramework: '#setup: 'another''

2017-06-20 19:44:26 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-06-20 19:44:26 - DEBUG UnitTestFramework: '#run: 'another''

2017-06-20 19:44:26 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-06-20 19:44:26 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-06-20 19:44:26 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-06-20 19:44:26 - DEBUG UnitTestFramework: '#setup: 'skip''

2017-06-20 19:44:27 - DEBUG UnitTestFramework: '#setup ok: 'skip''

2017-06-20 19:44:27 - DEBUG UnitTestFramework: '#run: 'skip''

2017-06-20 19:44:27 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-06-20 19:44:27 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-06-20 19:44:27 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-06-20 19:44:27 - DEBUG UnitTestFramework: '#run ok: 'skip''

2017-06-20 19:44:27 - DEBUG UnitTestFramework: '#teardown: 'skip''

2017-06-20 19:44:27 - DEBUG UnitTestFramework: '#teardown ok: 'skip''

2017-06-20 19:44:27 - DEBUG UnitTestFramework: '#setup: 'another skip''

2017-06-20 19:44:27 - DEBUG UnitTestFramework: '#setup ok: 'another skip''

2017-06-20 19:44:27 - DEBUG UnitTestFramework: '#run: 'another skip''

2017-06-20 19:44:27 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-06-20 19:44:27 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-06-20 19:44:27 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-06-20 19:44:27 - DEBUG UnitTestFramework: '#run ok: 'another skip''

2017-06-20 19:44:27 - DEBUG UnitTestFramework: '#teardown: 'another skip''

2017-06-20 19:44:27 - DEBUG UnitTestFramework: '#teardown ok: 'another skip''

2017-06-20 19:44:27 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox spy''

2017-06-20 19:44:27 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox spy''

2017-06-20 19:44:27 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox spy''

2017-06-20 19:44:27 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox spy''

2017-06-20 19:44:27 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox spy''

2017-06-20 19:44:27 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox spy''

2017-06-20 19:44:27 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub''

2017-06-20 19:44:27 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub''

2017-06-20 19:44:27 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub''

2017-06-20 19:44:27 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub''

2017-06-20 19:44:27 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub''

2017-06-20 19:44:27 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub''

2017-06-20 19:44:27 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub override''

2017-06-20 19:44:27 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub override''

2017-06-20 19:44:27 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub override''

2017-06-20 19:44:27 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub override''

2017-06-20 19:44:27 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub override''

2017-06-20 19:44:28 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub override''

2017-06-20 19:44:28 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox mock''

2017-06-20 19:44:28 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox mock''

2017-06-20 19:44:28 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox mock''

2017-06-20 19:44:28 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox mock''

2017-06-20 19:44:28 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox mock''

2017-06-20 19:44:28 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox mock''

2017-06-20 19:44:28 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox restore after test end''

2017-06-20 19:44:28 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox restore after test end''

2017-06-20 19:44:28 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox restore after test end''

2017-06-20 19:44:28 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox restore after test end''

2017-06-20 19:44:28 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox restore after test end''

2017-06-20 19:44:28 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox restore after test end''

2017-06-20 19:44:28 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-06-20 19:44:28 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-06-20 19:44:28 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-06-20 19:44:28 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-06-20 19:44:28 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-06-20 19:44:28 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-06-20 19:44:28 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-06-20 19:44:28 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-06-20 19:44:28 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-06-20 19:44:28 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-06-20 19:44:28 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-06-20 19:44:28 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-06-20 19:44:28 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-06-20 19:44:28 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-06-20 19:44:28 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-06-20 19:44:28 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-06-20 19:44:28 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-06-20 19:44:28 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-06-20 19:44:28 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-06-20 19:44:29 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-06-20 19:44:29 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-06-20 19:44:29 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-06-20 19:44:29 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-06-20 19:44:29 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-06-20 19:44:29 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-06-20 19:44:29 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-06-20 19:44:29 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-06-20 19:44:30 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-06-20 19:44:30 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-06-20 19:44:30 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-06-20 19:44:30 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-20 19:44:30 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-20 19:44:30 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-20 19:44:31 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-20 19:44:31 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-20 19:44:32 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-20 19:44:32 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-20 19:44:32 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-20 19:44:32 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-20 19:44:32 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-20 19:44:32 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-20 19:44:32 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-20 19:44:32 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-20 19:44:32 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-20 19:44:32 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-20 19:44:33 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-20 19:44:33 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-20 19:44:33 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-20 19:44:33 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-20 19:44:33 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-20 19:44:33 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-20 19:44:34 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-20 19:44:34 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-20 19:44:34 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-20 19:44:34 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-20 19:44:34 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-20 19:44:34 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-20 19:44:35 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-20 19:44:35 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-20 19:44:35 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-20 19:44:35 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-06-20 19:44:35 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-06-20 19:44:35 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-06-20 19:44:37 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-06-20 19:44:37 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-06-20 19:44:38 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-06-20 19:44:38 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-06-20 19:44:38 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-06-20 19:44:38 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-06-20 19:44:40 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-06-20 19:44:40 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-06-20 19:44:41 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-06-20 19:44:41 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-06-20 19:44:44 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-06-20 19:44:44 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-06-20 19:44:47 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-06-20 19:44:47 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-06-20 19:44:50 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-06-20 19:44:50 - DEBUG UnitTestFramework: '#run: 'basic''

2017-06-20 19:44:51 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-06-20 19:44:51 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-06-20 19:44:51 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-06-20 19:44:51 - DEBUG UnitTestFramework: '#setup: 'another''

2017-06-20 19:44:56 - DEBUG UnitTestFramework: '#run ok: 'Can connect to a remote peer''

2017-06-20 19:44:56 - DEBUG UnitTestFramework: '#teardown: 'Can connect to a remote peer''

2017-06-20 19:44:57 - DEBUG UnitTestFramework: '#teardown ok: 'Can connect to a remote peer''

2017-06-20 19:44:57 - DEBUG UnitTestFramework: '#setup: 'Can shift data''

2017-06-20 19:44:57 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data''

2017-06-20 19:44:57 - DEBUG UnitTestFramework: '#run: 'Can shift data''

2017-06-20 19:44:59 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-06-20 19:44:59 - DEBUG UnitTestFramework: '#run: 'another''

2017-06-20 19:45:05 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-06-20 19:45:05 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-06-20 19:45:06 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-06-20 19:45:06 - DEBUG UnitTestFramework: '#setup: 'skip''

2017-06-20 19:45:06 - DEBUG UnitTestFramework: '#run ok: 'Can shift data''

2017-06-20 19:45:06 - DEBUG UnitTestFramework: '#teardown: 'Can shift data''

2017-06-20 19:45:07 - DEBUG UnitTestFramework: '#setup ok: 'skip''

2017-06-20 19:45:07 - DEBUG UnitTestFramework: '#run: 'skip''

2017-06-20 19:45:07 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-06-20 19:45:08 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data''

2017-06-20 19:45:08 - DEBUG UnitTestFramework: '#setup: 'Can shift data via parallel connections''

2017-06-20 19:45:08 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data via parallel connections''

2017-06-20 19:45:08 - DEBUG UnitTestFramework: '#run: 'Can shift data via parallel connections''

2017-06-20 19:45:09 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-06-20 19:45:09 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-06-20 19:45:11 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-06-20 19:45:12 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-06-20 19:45:12 - DEBUG UnitTestFramework: '#run ok: 'Can shift data via parallel connections''

2017-06-20 19:45:12 - DEBUG UnitTestFramework: '#teardown: 'Can shift data via parallel connections''

2017-06-20 19:45:13 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data via parallel connections''

2017-06-20 19:45:13 - DEBUG UnitTestFramework: '#setup: 'Can shift data securely''

2017-06-20 19:45:14 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-06-20 19:45:14 - DEBUG UnitTestFramework: '#run ok: 'skip''

2017-06-20 19:45:14 - DEBUG UnitTestFramework: '#teardown: 'skip''

2017-06-20 19:45:15 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data securely''

2017-06-20 19:45:15 - DEBUG UnitTestFramework: '#run: 'Can shift data securely''

2017-06-20 19:45:23 - DEBUG UnitTestFramework: '#run ok: 'Can shift data securely''

2017-06-20 19:45:23 - DEBUG UnitTestFramework: '#teardown: 'Can shift data securely''

2017-06-20 19:45:27 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data securely''

2017-06-20 19:45:27 - DEBUG UnitTestFramework: '#setup: 'Can shift large amounts of data''

2017-06-20 19:45:35 - DEBUG UnitTestFramework: '#setup ok: 'Can shift large amounts of data''

2017-06-20 19:45:35 - DEBUG UnitTestFramework: '#run: 'Can shift large amounts of data''

2017-06-20 19:45:40 - DEBUG UnitTestFramework: '#teardown ok: 'skip''

2017-06-20 19:45:40 - DEBUG UnitTestFramework: '#setup: 'another skip''

2017-06-20 19:45:44 - DEBUG UnitTestFramework: '#setup ok: 'another skip''

2017-06-20 19:45:44 - DEBUG UnitTestFramework: '#run: 'another skip''

2017-06-20 19:45:44 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-06-20 19:45:44 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-06-20 19:45:48 - DEBUG UnitTestFramework: '#run ok: 'Can shift large amounts of data''

2017-06-20 19:45:48 - DEBUG UnitTestFramework: '#teardown: 'Can shift large amounts of data''

2017-06-20 19:45:49 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift large amounts of data''

2017-06-20 19:45:49 - DEBUG UnitTestFramework: '#setup: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-06-20 19:45:49 - DEBUG UnitTestFramework: '#setup ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-06-20 19:45:49 - DEBUG UnitTestFramework: '#run: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-06-20 19:45:56 - DEBUG UnitTestFramework: '#run ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-06-20 19:45:56 - DEBUG UnitTestFramework: '#teardown: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-06-20 19:45:57 - DEBUG UnitTestFramework: '#teardown ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-06-20 19:45:57 - DEBUG UnitTestFramework: '#setup: 'Test updating advertising and parallel data transfer''

2017-06-20 19:45:57 - DEBUG UnitTestFramework: '#setup ok: 'Test updating advertising and parallel data transfer''

2017-06-20 19:45:57 - DEBUG UnitTestFramework: '#run: 'Test updating advertising and parallel data transfer''

2017-06-20 19:45:57 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-06-20 19:45:58 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-06-20 19:45:58 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-06-20 19:45:58 - DEBUG UnitTestFramework: '#run ok: 'Test updating advertising and parallel data transfer''

2017-06-20 19:45:58 - DEBUG UnitTestFramework: '#teardown: 'Test updating advertising and parallel data transfer''

2017-06-20 19:45:58 - DEBUG UnitTestFramework: '#teardown ok: 'Test updating advertising and parallel data transfer''

2017-06-20 19:45:58 - DEBUG UnitTestFramework: '#setup: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-06-20 19:45:58 - DEBUG UnitTestFramework: '#setup ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-06-20 19:45:58 - DEBUG UnitTestFramework: '#run: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-06-20 19:46:00 - DEBUG UnitTestFramework: '#run ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-06-20 19:46:00 - DEBUG UnitTestFramework: '#teardown: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-06-20 19:46:00 - DEBUG UnitTestFramework: '#teardown ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-06-20 19:46:00 - DEBUG UnitTestFramework: '#setup: 'cannot call connect when start listening for advertisements is not active''

2017-06-20 19:46:00 - DEBUG UnitTestFramework: '#setup ok: 'cannot call connect when start listening for advertisements is not active''

2017-06-20 19:46:00 - DEBUG UnitTestFramework: '#run: 'cannot call connect when start listening for advertisements is not active''

2017-06-20 19:46:01 - DEBUG UnitTestFramework: '#run ok: 'cannot call connect when start listening for advertisements is not active''

2017-06-20 19:46:01 - DEBUG UnitTestFramework: '#teardown: 'cannot call connect when start listening for advertisements is not active''

2017-06-20 19:46:01 - DEBUG UnitTestFramework: '#teardown ok: 'cannot call connect when start listening for advertisements is not active''

2017-06-20 19:46:01 - DEBUG UnitTestFramework: '#setup: 'Get error when trying to double connect to a peer on Android''

2017-06-20 19:46:01 - DEBUG UnitTestFramework: '#setup ok: 'Get error when trying to double connect to a peer on Android''

2017-06-20 19:46:01 - DEBUG UnitTestFramework: '#run: 'Get error when trying to double connect to a peer on Android''

2017-06-20 19:46:06 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-06-20 19:46:06 - DEBUG UnitTestFramework: '#run ok: 'another skip''

2017-06-20 19:46:06 - DEBUG UnitTestFramework: '#teardown: 'another skip''

2017-06-20 19:46:08 - DEBUG UnitTestFramework: '#teardown ok: 'another skip''

2017-06-20 19:46:08 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox spy''

2017-06-20 19:46:09 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox spy''

2017-06-20 19:46:09 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox spy''

2017-06-20 19:46:09 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox spy''

2017-06-20 19:46:09 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox spy''

2017-06-20 19:46:09 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox spy''

2017-06-20 19:46:09 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub''

2017-06-20 19:46:09 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub''

2017-06-20 19:46:09 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub''

2017-06-20 19:46:11 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub''

2017-06-20 19:46:11 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub''

2017-06-20 19:46:12 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub''

2017-06-20 19:46:12 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub override''

2017-06-20 19:46:13 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub override''

2017-06-20 19:46:13 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub override''

2017-06-20 19:46:13 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub override''

2017-06-20 19:46:13 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub override''

2017-06-20 19:46:13 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub override''

2017-06-20 19:46:13 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox mock''

2017-06-20 19:46:14 - DEBUG UnitTestFramework: '#run ok: 'Get error when trying to double connect to a peer on Android''

2017-06-20 19:46:14 - DEBUG UnitTestFramework: '#teardown: 'Get error when trying to double connect to a peer on Android''

2017-06-20 19:46:14 - DEBUG UnitTestFramework: '#teardown ok: 'Get error when trying to double connect to a peer on Android''

2017-06-20 19:46:14 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-06-20 19:46:16 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-06-20 19:46:16 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-06-20 19:46:26 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox mock''

2017-06-20 19:46:26 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox mock''

2017-06-20 19:46:41 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox mock''

2017-06-20 19:46:41 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox mock''

2017-06-20 19:46:42 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox mock''

2017-06-20 19:46:42 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox restore after test end''

2017-06-20 19:46:43 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox restore after test end''

2017-06-20 19:46:43 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox restore after test end''

2017-06-20 19:46:43 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-06-20 19:46:43 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-06-20 19:46:43 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox restore after test end''

2017-06-20 19:46:43 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox restore after test end''

2017-06-20 19:46:47 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-06-20 19:46:47 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-06-20 19:46:48 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox restore after test end''

2017-06-20 19:46:48 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-06-20 19:46:50 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-06-20 19:46:50 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-06-20 19:46:58 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-06-20 19:46:58 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-06-20 19:46:58 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-06-20 19:46:58 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-06-20 19:47:00 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-06-20 19:47:00 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-06-20 19:47:01 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-06-20 19:47:01 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-06-20 19:47:02 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-06-20 19:47:02 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-06-20 19:47:08 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-06-20 19:47:08 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-06-20 19:47:09 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-06-20 19:47:09 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-06-20 19:47:09 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-06-20 19:47:09 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-06-20 19:47:14 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-06-20 19:47:14 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-06-20 19:47:15 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-06-20 19:47:15 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-06-20 19:47:16 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-06-20 19:47:16 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-06-20 19:47:16 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-06-20 19:47:16 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-06-20 19:47:17 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-06-20 19:47:17 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-06-20 19:47:18 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-06-20 19:47:18 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-06-20 19:47:19 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-06-20 19:47:19 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-06-20 19:47:20 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-06-20 19:47:20 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-06-20 19:47:20 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-06-20 19:47:21 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-06-20 19:47:21 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-06-20 19:47:21 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-06-20 19:47:21 - DEBUG UnitTestFramework: '#setup: 'initial peer discovery''

2017-06-20 19:47:21 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-06-20 19:47:21 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-06-20 19:47:21 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-06-20 19:47:21 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-06-20 19:47:21 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-06-20 19:47:21 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-06-20 19:47:21 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-06-20 19:47:21 - DEBUG UnitTestFramework: '#setup ok: 'initial peer discovery''

2017-06-20 19:47:21 - DEBUG UnitTestFramework: '#run: 'initial peer discovery''

2017-06-20 19:47:21 - INFO Socket: 'run skipped, test: 'initial peer discovery', event: 'run_initial peer discovery''

2017-06-20 19:47:21 - INFO Socket: 'run skipped, test: 'initial peer discovery', event: 'run_initial peer discovery''

2017-06-20 19:47:21 - INFO Socket: 'run skipped, test: 'initial peer discovery', event: 'run_initial peer discovery''

2017-06-20 19:47:21 - DEBUG UnitTestFramework: '#run ok: 'initial peer discovery''

2017-06-20 19:47:21 - DEBUG UnitTestFramework: '#teardown: 'initial peer discovery''

2017-06-20 19:47:21 - DEBUG UnitTestFramework: '#teardown ok: 'initial peer discovery''

2017-06-20 19:47:21 - DEBUG UnitTestFramework: '#setup: 'update peer discovery 1''

2017-06-20 19:47:21 - DEBUG UnitTestFramework: '#setup ok: 'update peer discovery 1''

2017-06-20 19:47:21 - DEBUG UnitTestFramework: '#run: 'update peer discovery 1''

2017-06-20 19:47:21 - INFO Socket: 'run skipped, test: 'update peer discovery 1', event: 'run_update peer discovery 1''

2017-06-20 19:47:21 - INFO Socket: 'run skipped, test: 'update peer discovery 1', event: 'run_update peer discovery 1''

2017-06-20 19:47:21 - INFO Socket: 'run skipped, test: 'update peer discovery 1', event: 'run_update peer discovery 1''

2017-06-20 19:47:21 - DEBUG UnitTestFramework: '#run ok: 'update peer discovery 1''

2017-06-20 19:47:21 - DEBUG UnitTestFramework: '#teardown: 'update peer discovery 1''

2017-06-20 19:47:21 - DEBUG UnitTestFramework: '#teardown ok: 'update peer discovery 1''

2017-06-20 19:47:21 - DEBUG UnitTestFramework: '#setup: 'update peer discovery 2''

2017-06-20 19:47:21 - DEBUG UnitTestFramework: '#setup ok: 'update peer discovery 2''

2017-06-20 19:47:21 - DEBUG UnitTestFramework: '#run: 'update peer discovery 2''

2017-06-20 19:47:21 - INFO Socket: 'run skipped, test: 'update peer discovery 2', event: 'run_update peer discovery 2''

2017-06-20 19:47:22 - INFO Socket: 'run skipped, test: 'update peer discovery 2', event: 'run_update peer discovery 2''

2017-06-20 19:47:22 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-06-20 19:47:22 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-06-20 19:47:22 - INFO Socket: 'run skipped, test: 'update peer discovery 2', event: 'run_update peer discovery 2''

2017-06-20 19:47:22 - DEBUG UnitTestFramework: '#run ok: 'update peer discovery 2''

2017-06-20 19:47:22 - DEBUG UnitTestFramework: '#teardown: 'update peer discovery 2''

2017-06-20 19:47:22 - DEBUG UnitTestFramework: '#teardown ok: 'update peer discovery 2''

2017-06-20 19:47:22 - DEBUG UnitTestFramework: '#setup: 'check latest peer discovery''

2017-06-20 19:47:22 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-06-20 19:47:22 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-06-20 19:47:22 - DEBUG UnitTestFramework: '#setup ok: 'check latest peer discovery''

2017-06-20 19:47:22 - DEBUG UnitTestFramework: '#run: 'check latest peer discovery''

2017-06-20 19:47:22 - INFO Socket: 'run skipped, test: 'check latest peer discovery', event: 'run_check latest peer discovery''

2017-06-20 19:47:22 - INFO Socket: 'run skipped, test: 'check latest peer discovery', event: 'run_check latest peer discovery''

2017-06-20 19:47:22 - INFO Socket: 'run skipped, test: 'check latest peer discovery', event: 'run_check latest peer discovery''

2017-06-20 19:47:22 - DEBUG UnitTestFramework: '#run ok: 'check latest peer discovery''

2017-06-20 19:47:22 - DEBUG UnitTestFramework: '#teardown: 'check latest peer discovery''

2017-06-20 19:47:23 - DEBUG UnitTestFramework: '#teardown ok: 'check latest peer discovery''

2017-06-20 19:47:23 - DEBUG UnitTestFramework: '#setup: 'Set up for no peer discovery test''

2017-06-20 19:47:24 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-06-20 19:47:24 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-06-20 19:47:24 - DEBUG UnitTestFramework: '#setup ok: 'Set up for no peer discovery test''

2017-06-20 19:47:24 - DEBUG UnitTestFramework: '#run: 'Set up for no peer discovery test''

2017-06-20 19:47:25 - INFO Socket: 'run skipped, test: 'Set up for no peer discovery test', event: 'run_Set up for no peer discovery test''

2017-06-20 19:47:25 - INFO Socket: 'run skipped, test: 'Set up for no peer discovery test', event: 'run_Set up for no peer discovery test''

2017-06-20 19:47:25 - INFO Socket: 'run skipped, test: 'Set up for no peer discovery test', event: 'run_Set up for no peer discovery test''

2017-06-20 19:47:25 - DEBUG UnitTestFramework: '#run ok: 'Set up for no peer discovery test''

2017-06-20 19:47:25 - DEBUG UnitTestFramework: '#teardown: 'Set up for no peer discovery test''

2017-06-20 19:47:26 - DEBUG UnitTestFramework: '#teardown ok: 'Set up for no peer discovery test''

2017-06-20 19:47:26 - DEBUG UnitTestFramework: '#setup: 'no peer discovery''

2017-06-20 19:47:27 - DEBUG UnitTestFramework: '#setup ok: 'no peer discovery''

2017-06-20 19:47:27 - DEBUG UnitTestFramework: '#run: 'no peer discovery''

2017-06-20 19:47:28 - INFO Socket: 'run skipped, test: 'no peer discovery', event: 'run_no peer discovery''

2017-06-20 19:47:28 - INFO Socket: 'run skipped, test: 'no peer discovery', event: 'run_no peer discovery''

2017-06-20 19:47:28 - INFO Socket: 'run skipped, test: 'no peer discovery', event: 'run_no peer discovery''

2017-06-20 19:47:28 - DEBUG UnitTestFramework: '#run ok: 'no peer discovery''

2017-06-20 19:47:28 - DEBUG UnitTestFramework: '#teardown: 'no peer discovery''

2017-06-20 19:47:36 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-06-20 19:47:36 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-20 19:47:39 - DEBUG UnitTestFramework: '#teardown ok: 'no peer discovery''

2017-06-20 19:47:39 - DEBUG UnitTestFramework: '#setup: 'calling createNativeListener directly rejects''

2017-06-20 19:47:40 - DEBUG UnitTestFramework: '#setup ok: 'calling createNativeListener directly rejects''

2017-06-20 19:47:40 - DEBUG UnitTestFramework: '#run: 'calling createNativeListener directly rejects''

2017-06-20 19:47:40 - DEBUG UnitTestFramework: '#run ok: 'calling createNativeListener directly rejects''

2017-06-20 19:47:40 - DEBUG UnitTestFramework: '#teardown: 'calling createNativeListener directly rejects''

2017-06-20 19:47:40 - DEBUG UnitTestFramework: '#teardown ok: 'calling createNativeListener directly rejects''

2017-06-20 19:47:40 - DEBUG UnitTestFramework: '#setup: 'emits incomingConnectionState''

2017-06-20 19:47:41 - DEBUG UnitTestFramework: '#setup ok: 'emits incomingConnectionState''

2017-06-20 19:47:41 - DEBUG UnitTestFramework: '#run: 'emits incomingConnectionState''

2017-06-20 19:47:47 - DEBUG UnitTestFramework: '#run ok: 'emits incomingConnectionState''

2017-06-20 19:47:47 - DEBUG UnitTestFramework: '#teardown: 'emits incomingConnectionState''

2017-06-20 19:47:49 - DEBUG UnitTestFramework: '#teardown ok: 'emits incomingConnectionState''

2017-06-20 19:47:49 - DEBUG UnitTestFramework: '#setup: 'emits routerPortConnectionFailed''

2017-06-20 19:47:52 - DEBUG UnitTestFramework: '#setup ok: 'emits routerPortConnectionFailed''

2017-06-20 19:47:52 - DEBUG UnitTestFramework: '#run: 'emits routerPortConnectionFailed''

2017-06-20 19:47:54 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-20 19:47:54 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-20 19:47:59 - DEBUG UnitTestFramework: '#run ok: 'emits routerPortConnectionFailed''

2017-06-20 19:47:59 - DEBUG UnitTestFramework: '#teardown: 'emits routerPortConnectionFailed''

2017-06-20 19:48:05 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-20 19:48:05 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-20 19:48:06 - DEBUG UnitTestFramework: '#teardown ok: 'emits routerPortConnectionFailed''

2017-06-20 19:48:06 - DEBUG UnitTestFramework: '#setup: 'native server connections all up''

2017-06-20 19:48:07 - DEBUG UnitTestFramework: '#setup ok: 'native server connections all up''

2017-06-20 19:48:07 - DEBUG UnitTestFramework: '#run: 'native server connections all up''

2017-06-20 19:48:07 - DEBUG UnitTestFramework: '#run ok: 'native server connections all up''

2017-06-20 19:48:07 - DEBUG UnitTestFramework: '#teardown: 'native server connections all up''

2017-06-20 19:48:09 - DEBUG UnitTestFramework: '#teardown ok: 'native server connections all up''

2017-06-20 19:48:09 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming stream cleans outgoing socket''

2017-06-20 19:48:09 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming stream cleans outgoing socket''

2017-06-20 19:48:09 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming stream cleans outgoing socket''

2017-06-20 19:48:16 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming stream cleans outgoing socket''

2017-06-20 19:48:16 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming stream cleans outgoing socket''

2017-06-20 19:48:18 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming stream cleans outgoing socket''

2017-06-20 19:48:18 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming connection cleans outgoing socket''

2017-06-20 19:48:22 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming connection cleans outgoing socket''

2017-06-20 19:48:22 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming connection cleans outgoing socket''

2017-06-20 19:48:24 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming connection cleans outgoing socket''

2017-06-20 19:48:24 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming connection cleans outgoing socket''

2017-06-20 19:48:25 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming connection cleans outgoing socket''

2017-06-20 19:48:25 - DEBUG UnitTestFramework: '#setup: 'native server - closing outgoing socket cleans associated mux stream''

2017-06-20 19:48:27 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing outgoing socket cleans associated mux stream''

2017-06-20 19:48:27 - DEBUG UnitTestFramework: '#run: 'native server - closing outgoing socket cleans associated mux stream''

2017-06-20 19:48:27 - DEBUG UnitTestFramework: '#run ok: 'native server - closing outgoing socket cleans associated mux stream''

2017-06-20 19:48:27 - DEBUG UnitTestFramework: '#teardown: 'native server - closing outgoing socket cleans associated mux stream''

2017-06-20 19:48:27 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing outgoing socket cleans associated mux stream''

2017-06-20 19:48:27 - DEBUG UnitTestFramework: '#setup: 'native server - closing the whole server cleans everything up''

2017-06-20 19:48:27 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing the whole server cleans everything up''

2017-06-20 19:48:27 - DEBUG UnitTestFramework: '#run: 'native server - closing the whole server cleans everything up''

2017-06-20 19:48:28 - DEBUG UnitTestFramework: '#run ok: 'native server - closing the whole server cleans everything up''

2017-06-20 19:48:28 - DEBUG UnitTestFramework: '#teardown: 'native server - closing the whole server cleans everything up''

2017-06-20 19:48:28 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-20 19:48:28 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-20 19:48:28 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing the whole server cleans everything up''

2017-06-20 19:48:28 - DEBUG UnitTestFramework: '#setup: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-06-20 19:48:29 - DEBUG UnitTestFramework: '#setup ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-06-20 19:48:29 - DEBUG UnitTestFramework: '#run: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-06-20 19:48:29 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-20 19:48:29 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-20 19:48:30 - DEBUG UnitTestFramework: '#run ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-06-20 19:48:30 - DEBUG UnitTestFramework: '#teardown: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-06-20 19:48:33 - DEBUG UnitTestFramework: '#teardown ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-06-20 19:48:33 - DEBUG UnitTestFramework: '#setup: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-06-20 19:48:33 - DEBUG UnitTestFramework: '#setup ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-06-20 19:48:33 - DEBUG UnitTestFramework: '#run: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-06-20 19:48:34 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-20 19:48:34 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-20 19:48:34 - DEBUG UnitTestFramework: '#run ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-06-20 19:48:34 - DEBUG UnitTestFramework: '#teardown: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-06-20 19:48:34 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-20 19:48:34 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-20 19:48:34 - DEBUG UnitTestFramework: '#teardown ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-06-20 19:48:34 - DEBUG UnitTestFramework: '#setup: 'native server - timing out the incoming connection cleans everything up''

2017-06-20 19:48:34 - DEBUG UnitTestFramework: '#setup ok: 'native server - timing out the incoming connection cleans everything up''

2017-06-20 19:48:34 - DEBUG UnitTestFramework: '#run: 'native server - timing out the incoming connection cleans everything up''

2017-06-20 19:48:34 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-20 19:48:34 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-20 19:48:34 - DEBUG UnitTestFramework: '#run ok: 'native server - timing out the incoming connection cleans everything up''

2017-06-20 19:48:34 - DEBUG UnitTestFramework: '#teardown: 'native server - timing out the incoming connection cleans everything up''

2017-06-20 19:48:34 - DEBUG UnitTestFramework: '#teardown ok: 'native server - timing out the incoming connection cleans everything up''

2017-06-20 19:48:34 - DEBUG UnitTestFramework: '#setup: 'can create servers manager''

2017-06-20 19:48:34 - DEBUG UnitTestFramework: '#setup ok: 'can create servers manager''

2017-06-20 19:48:34 - DEBUG UnitTestFramework: '#run: 'can create servers manager''

2017-06-20 19:48:34 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-20 19:48:34 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-20 19:48:34 - DEBUG UnitTestFramework: '#run ok: 'can create servers manager''

2017-06-20 19:48:34 - DEBUG UnitTestFramework: '#teardown: 'can create servers manager''

2017-06-20 19:48:35 - DEBUG UnitTestFramework: '#teardown ok: 'can create servers manager''

2017-06-20 19:48:35 - DEBUG UnitTestFramework: '#setup: 'calling stop without start causes error''

2017-06-20 19:48:38 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-20 19:48:38 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-20 19:48:39 - DEBUG UnitTestFramework: '#setup ok: 'calling stop without start causes error''

2017-06-20 19:48:39 - DEBUG UnitTestFramework: '#run: 'calling stop without start causes error''

2017-06-20 19:48:39 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-20 19:48:39 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-20 19:48:51 - DEBUG UnitTestFramework: '#run ok: 'calling stop without start causes error''

2017-06-20 19:48:51 - DEBUG UnitTestFramework: '#teardown: 'calling stop without start causes error''

2017-06-20 19:48:58 - DEBUG UnitTestFramework: '#teardown ok: 'calling stop without start causes error''

2017-06-20 19:48:58 - DEBUG UnitTestFramework: '#setup: 'can start/stop servers manager''

2017-06-20 19:49:13 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-20 19:49:13 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-20 19:49:19 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-20 19:49:19 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-20 19:49:24 - DEBUG UnitTestFramework: '#setup ok: 'can start/stop servers manager''

2017-06-20 19:49:24 - DEBUG UnitTestFramework: '#run: 'can start/stop servers manager''

2017-06-20 19:49:29 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-20 19:49:29 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-20 19:49:33 - DEBUG UnitTestFramework: '#run ok: 'can start/stop servers manager''

2017-06-20 19:49:33 - DEBUG UnitTestFramework: '#teardown: 'can start/stop servers manager''

2017-06-20 19:49:34 - DEBUG UnitTestFramework: '#teardown ok: 'can start/stop servers manager''

2017-06-20 19:49:34 - DEBUG UnitTestFramework: '#setup: 'starting twice resolves with listening port''

2017-06-20 19:49:34 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-20 19:49:34 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-20 19:49:37 - DEBUG UnitTestFramework: '#setup ok: 'starting twice resolves with listening port''

2017-06-20 19:49:37 - DEBUG UnitTestFramework: '#run: 'starting twice resolves with listening port''

2017-06-20 19:49:51 - DEBUG UnitTestFramework: '#run ok: 'starting twice resolves with listening port''

2017-06-20 19:49:51 - DEBUG UnitTestFramework: '#teardown: 'starting twice resolves with listening port''

2017-06-20 19:49:53 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-20 19:49:53 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-06-20 19:49:58 - DEBUG UnitTestFramework: '#teardown ok: 'starting twice resolves with listening port''

2017-06-20 19:49:58 - DEBUG UnitTestFramework: '#setup: 'terminateIncomingConnection will terminate a connection''

2017-06-20 19:50:00 - DEBUG UnitTestFramework: '#setup ok: 'terminateIncomingConnection will terminate a connection''

2017-06-20 19:50:00 - DEBUG UnitTestFramework: '#run: 'terminateIncomingConnection will terminate a connection''

2017-06-20 19:50:01 - DEBUG UnitTestFramework: '#run ok: 'terminateIncomingConnection will terminate a connection''

2017-06-20 19:50:01 - DEBUG UnitTestFramework: '#teardown: 'terminateIncomingConnection will terminate a connection''

2017-06-20 19:50:01 - DEBUG UnitTestFramework: '#teardown ok: 'terminateIncomingConnection will terminate a connection''

2017-06-20 19:50:01 - DEBUG UnitTestFramework: '#setup: 'terminate an Outgoing connection''

2017-06-20 19:50:01 - DEBUG UnitTestFramework: '#setup ok: 'terminate an Outgoing connection''

2017-06-20 19:50:01 - DEBUG UnitTestFramework: '#run: 'terminate an Outgoing connection''

2017-06-20 19:50:01 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-06-20 19:50:01 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-06-20 19:50:01 - DEBUG UnitTestFramework: '#run ok: 'terminate an Outgoing connection''

2017-06-20 19:50:01 - DEBUG UnitTestFramework: '#teardown: 'terminate an Outgoing connection''

2017-06-20 19:50:01 - DEBUG UnitTestFramework: '#teardown ok: 'terminate an Outgoing connection''

2017-06-20 19:50:01 - DEBUG UnitTestFramework: '#setup: '#startListeningForAdvertisements should fail if start not called''

2017-06-20 19:50:03 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-06-20 19:50:03 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-06-20 19:50:04 - DEBUG UnitTestFramework: '#setup ok: '#startListeningForAdvertisements should fail if start not called''

2017-06-20 19:50:04 - DEBUG UnitTestFramework: '#run: '#startListeningForAdvertisements should fail if start not called''

2017-06-20 19:50:09 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-06-20 19:50:09 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-06-20 19:50:09 - DEBUG UnitTestFramework: '#run ok: '#startListeningForAdvertisements should fail if start not called''

2017-06-20 19:50:09 - DEBUG UnitTestFramework: '#teardown: '#startListeningForAdvertisements should fail if start not called''

2017-06-20 19:50:32 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-06-20 19:50:32 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-06-20 19:51:09 - DEBUG UnitTestFramework: '#teardown ok: '#startListeningForAdvertisements should fail if start not called''

2017-06-20 19:51:09 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-06-20 19:52:09 - ERROR UnitTestFramework: '#run failed: '#startUpdateAdvertisingAndListening should fail if start not called', error: 'TimeoutError: timeout exceeded, event: 'setup_#startUpdateAdvertisingAndListening should fail if start not called_finished', test: '#startUpdateAdvertisingAndListening should fail if start not called'', stack: 'TimeoutError: timeout exceeded, event: 'setup_#startUpdateAdvertisingAndListening should fail if start not called_finished', test: '#startUpdateAdvertisingAndListening should fail if start not called'
    at afterTimeout (/home/pi/Test/server_1265037342651392/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_1265037342651392/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-06-20 19:52:09 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'android', error: 'TimeoutError: timeout exceeded, event: 'setup_#startUpdateAdvertisingAndListening should fail if start not called_finished', test: '#startUpdateAdvertisingAndListening should fail if start not called'', stack: 'TimeoutError: timeout exceeded, event: 'setup_#startUpdateAdvertisingAndListening should fail if start not called_finished', test: '#startUpdateAdvertisingAndListening should fail if start not called'
    at afterTimeout (/home/pi/Test/server_1265037342651392/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_1265037342651392/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-06-20 19:53:32 - ERROR UnitTestFramework: '#run failed: 'Can connect to a remote peer', error: 'TimeoutError: timeout exceeded, event: 'run_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'', stack: 'TimeoutError: timeout exceeded, event: 'run_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'
    at afterTimeout (/home/pi/Test/server_1265037342651392/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_1265037342651392/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-06-20 19:53:32 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'ios', error: 'TimeoutError: timeout exceeded, event: 'run_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'', stack: 'TimeoutError: timeout exceeded, event: 'run_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'
    at afterTimeout (/home/pi/Test/server_1265037342651392/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_1265037342651392/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-06-20 19:53:32 - DEBUG TestServer: 'completed'

2017-06-20 19:53:32 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-air-2-1' disconnected, reason: 'undefined''

2017-06-20 19:53:32 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-mfts' disconnected, reason: 'undefined''

2017-06-20 19:53:32 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-1' disconnected, reason: 'undefined''

2017-06-20 19:53:32 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-06-20 19:53:32 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-06-20 19:53:32 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''

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
20/6/2017@21:36:52 Getting the list of iOS devices 
20/6/2017@21:36:53 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
20/6/2017@21:36:53 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
20/6/2017@21:36:53 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
20/6/2017@21:36:53 Deploying iOS test app 
20/6/2017@21:36:53 uninstalling the application 
20/6/2017@21:36:53 installing the application 
20/6/2017@22:00:12 ios: child process exited with code null on device bffa901fefdea07f59339a6737776943349f5077 
20/6/2017@22:00:12 ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
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

STOP log received from ce061606e320561102
Test has FAILED

Device test finished on ce061606e320561102 
Android task is completed. [FAILED]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/1265037342651392_Added_skip_function_to_allow_a_test_to_be_skipped_over_jareksl/thali03_samsung-SM-G935F.md)

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

STOP log received from ce0616068b9f212302
Test has FAILED

Device test finished on ce0616068b9f212302 
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/1265037342651392_Added_skip_function_to_allow_a_test_to_be_skipped_over_jareksl/thali04_samsung-SM-G930F.md)

####Node name: thali05
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
Test has FAILED

Device test finished on ce061606c181d71003 
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/1265037342651392_Added_skip_function_to_allow_a_test_to_be_skipped_over_jareksl/thali05_samsung-SM-G930F.md)


###iOS Logs
[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/1265037342651392_Added_skip_function_to_allow_a_test_to_be_skipped_over_jareksl/iOS_iphone-5s-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/1265037342651392_Added_skip_function_to_allow_a_test_to_be_skipped_over_jareksl/iOS_iphone-5s-mfts.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/1265037342651392_Added_skip_function_to_allow_a_test_to_be_skipped_over_jareksl/iOS_ipad-air-2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/1265037342651392_Added_skip_function_to_allow_a_test_to_be_skipped_over_jareksl/iOS_server.md)





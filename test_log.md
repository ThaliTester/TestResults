#### Test 127148139fecb998 Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 2 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":3}}
2017-06-23 09:33:29 - INFO HttpServer: 'listening on *:3000'

2017-06-23 09:33:33 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '920cc9fb-4c42-4a05-98b8-ed8d45a0bc44', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-23 09:33:33 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-air-2-1''

2017-06-23 09:33:41 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: '2ea3e3ef-44ce-4742-86d5-d501c8083b02', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-23 09:33:41 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-1''

2017-06-23 09:33:43 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: '1269d55d-5c45-474e-b0e3-12cd47edf7a8', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-23 09:33:43 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-mfts''

2017-06-23 09:33:43 - INFO TestFramework: 'all required 3 devices are present for platformName: 'ios''

2017-06-23 09:33:43 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'ios''

2017-06-23 09:33:43 - DEBUG UnitTestFramework: 'scheduling tests'

2017-06-23 09:33:44 - DEBUG UnitTestFramework: 'tests scheduled'

2017-06-23 09:33:44 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-06-23 09:33:45 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-06-23 09:33:45 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-06-23 09:33:47 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-06-23 09:33:47 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-06-23 09:33:48 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-06-23 09:33:48 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-06-23 09:33:48 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-06-23 09:33:48 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-06-23 09:33:48 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-06-23 09:33:48 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-06-23 09:33:50 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-06-23 09:33:50 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-23 09:33:52 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-23 09:33:52 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-23 09:33:58 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-23 09:33:58 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-23 09:33:58 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-23 09:33:58 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-23 09:33:58 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-23 09:33:58 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-23 09:33:59 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-23 09:33:59 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-23 09:34:00 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-23 09:34:00 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-06-23 09:34:08 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-23 09:34:08 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-06-23 09:34:08 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-23 09:34:08 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-23 09:34:08 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-23 09:34:08 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-23 09:34:08 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-06-23 09:34:09 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-23 09:34:09 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-23 09:34:09 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-23 09:34:09 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-23 09:34:09 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-23 09:34:09 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-23 09:34:09 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-23 09:34:09 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-23 09:34:09 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-23 09:34:10 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-23 09:34:10 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-23 09:34:12 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-23 09:34:12 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-23 09:34:12 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-23 09:34:12 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-23 09:34:12 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-23 09:34:12 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-23 09:34:12 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-23 09:34:12 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-23 09:34:12 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-23 09:34:13 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-23 09:34:13 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-23 09:34:13 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-23 09:34:13 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-23 09:34:13 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-23 09:34:13 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-23 09:34:13 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-23 09:34:13 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-23 09:34:13 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-06-23 09:34:13 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-06-23 09:34:13 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-06-23 09:34:13 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-06-23 09:34:13 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-06-23 09:34:15 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-06-23 09:34:15 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-06-23 09:34:17 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-06-23 09:34:17 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-06-23 09:34:24 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-06-23 09:34:24 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-06-23 09:34:29 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-06-23 09:34:29 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-06-23 09:34:32 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-06-23 09:34:32 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-06-23 09:34:33 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-06-23 09:34:33 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-06-23 09:34:38 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-06-23 09:34:38 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-06-23 09:34:53 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-06-23 09:34:53 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-06-23 09:34:53 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-06-23 09:34:53 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-06-23 09:34:54 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-06-23 09:34:54 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-06-23 09:34:55 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-06-23 09:34:55 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-06-23 09:34:56 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-06-23 09:34:56 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-06-23 09:34:58 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-06-23 09:34:58 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-06-23 09:34:58 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-06-23 09:34:58 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-06-23 09:34:58 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-06-23 09:34:58 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-06-23 09:34:59 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-06-23 09:34:59 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-06-23 09:35:00 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '2ab13bce-e0af-4bfc-8578-9897972fc463', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-23 09:35:00 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-06-23 09:35:05 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '7c74c484-5fe7-44a5-8339-9f7154a065f6', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-23 09:35:05 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-06-23 09:35:05 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-06-23 09:35:05 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-06-23 09:35:06 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-06-23 09:35:06 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-06-23 09:35:07 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-06-23 09:35:07 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-06-23 09:35:07 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-06-23 09:35:07 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-06-23 09:35:08 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-06-23 09:35:08 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-06-23 09:35:08 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-06-23 09:35:08 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-06-23 09:35:09 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-06-23 09:35:09 - DEBUG UnitTestFramework: '#run: 'basic''

2017-06-23 09:35:10 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-06-23 09:35:10 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-06-23 09:35:10 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-06-23 09:35:10 - DEBUG UnitTestFramework: '#setup: 'another''

2017-06-23 09:35:10 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-06-23 09:35:10 - DEBUG UnitTestFramework: '#run: 'another''

2017-06-23 09:35:11 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-06-23 09:35:11 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-06-23 09:35:12 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-06-23 09:35:12 - DEBUG UnitTestFramework: '#setup: 'skip''

2017-06-23 09:35:12 - DEBUG UnitTestFramework: '#setup ok: 'skip''

2017-06-23 09:35:12 - DEBUG UnitTestFramework: '#run: 'skip''

2017-06-23 09:35:12 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-06-23 09:35:12 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-06-23 09:35:13 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-06-23 09:35:13 - DEBUG UnitTestFramework: '#run ok: 'skip''

2017-06-23 09:35:13 - DEBUG UnitTestFramework: '#teardown: 'skip''

2017-06-23 09:35:14 - DEBUG UnitTestFramework: '#teardown ok: 'skip''

2017-06-23 09:35:14 - DEBUG UnitTestFramework: '#setup: 'another skip''

2017-06-23 09:35:15 - DEBUG UnitTestFramework: '#setup ok: 'another skip''

2017-06-23 09:35:15 - DEBUG UnitTestFramework: '#run: 'another skip''

2017-06-23 09:35:15 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-06-23 09:35:15 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-06-23 09:35:15 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-06-23 09:35:15 - DEBUG UnitTestFramework: '#run ok: 'another skip''

2017-06-23 09:35:15 - DEBUG UnitTestFramework: '#teardown: 'another skip''

2017-06-23 09:35:15 - DEBUG UnitTestFramework: '#teardown ok: 'another skip''

2017-06-23 09:35:15 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox spy''

2017-06-23 09:35:16 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox spy''

2017-06-23 09:35:16 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox spy''

2017-06-23 09:35:16 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox spy''

2017-06-23 09:35:16 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox spy''

2017-06-23 09:35:16 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox spy''

2017-06-23 09:35:16 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub''

2017-06-23 09:35:17 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub''

2017-06-23 09:35:17 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub''

2017-06-23 09:35:19 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub''

2017-06-23 09:35:19 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub''

2017-06-23 09:35:23 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub''

2017-06-23 09:35:23 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub override''

2017-06-23 09:35:41 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub override''

2017-06-23 09:35:41 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub override''

2017-06-23 09:35:46 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub override''

2017-06-23 09:35:46 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub override''

2017-06-23 09:35:49 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub override''

2017-06-23 09:35:49 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox mock''

2017-06-23 09:35:50 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox mock''

2017-06-23 09:35:50 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox mock''

2017-06-23 09:35:58 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox mock''

2017-06-23 09:35:58 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox mock''

2017-06-23 09:36:03 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox mock''

2017-06-23 09:36:03 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox restore after test end''

2017-06-23 09:36:12 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox restore after test end''

2017-06-23 09:36:12 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox restore after test end''

2017-06-23 09:36:15 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox restore after test end''

2017-06-23 09:36:15 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox restore after test end''

2017-06-23 09:36:19 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox restore after test end''

2017-06-23 09:36:19 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-06-23 09:36:19 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-06-23 09:36:19 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-06-23 09:36:19 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-06-23 09:36:19 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-06-23 09:36:20 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-06-23 09:36:20 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-06-23 09:36:20 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-06-23 09:36:20 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-06-23 09:36:21 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-06-23 09:36:21 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-06-23 09:36:21 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-06-23 09:36:21 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-06-23 09:36:21 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-06-23 09:36:21 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-06-23 09:36:21 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-06-23 09:36:21 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-06-23 09:36:22 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-06-23 09:36:22 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-06-23 09:36:22 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-06-23 09:36:23 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-06-23 09:36:23 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-06-23 09:36:23 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-06-23 09:36:23 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-06-23 09:36:23 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-06-23 09:36:23 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-06-23 09:36:23 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-06-23 09:36:23 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-06-23 09:36:23 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-06-23 09:36:24 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-06-23 09:36:24 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-06-23 09:36:24 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-06-23 09:36:24 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-06-23 09:36:24 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-06-23 09:36:24 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-06-23 09:36:24 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-06-23 09:36:24 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-23 09:36:28 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-23 09:36:28 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-23 09:36:29 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-23 09:36:29 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-23 09:36:31 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-23 09:36:31 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-23 09:36:32 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-23 09:36:32 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-23 09:36:34 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-23 09:36:34 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-23 09:36:38 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-23 09:36:38 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-23 09:36:39 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'd90db230-9672-4fe0-b80e-f79a609dc657', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-23 09:36:39 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-06-23 09:36:39 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-06-23 09:36:39 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-06-23 09:36:39 - DEBUG UnitTestFramework: 'scheduling tests'

2017-06-23 09:36:39 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-23 09:36:39 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-23 09:36:39 - DEBUG UnitTestFramework: 'tests scheduled'

2017-06-23 09:36:39 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-06-23 09:36:39 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-23 09:36:39 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-23 09:36:39 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-06-23 09:36:39 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-06-23 09:36:41 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-06-23 09:36:41 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-06-23 09:36:41 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-06-23 09:36:41 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-06-23 09:36:41 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-23 09:36:41 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-23 09:36:41 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-06-23 09:36:41 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-06-23 09:36:42 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-06-23 09:36:42 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-06-23 09:36:42 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-06-23 09:36:42 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-23 09:36:43 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-23 09:36:43 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-23 09:36:45 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-23 09:36:45 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-23 09:36:46 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-23 09:36:46 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-23 09:36:47 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-23 09:36:47 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-23 09:36:49 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-23 09:36:49 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-23 09:36:50 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-23 09:36:50 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-23 09:36:59 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-23 09:36:59 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-06-23 09:36:59 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-23 09:36:59 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-06-23 09:37:01 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-23 09:37:03 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-23 09:37:03 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-23 09:37:03 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-23 09:37:03 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-06-23 09:37:07 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-23 09:37:07 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-23 09:37:11 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-23 09:37:11 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-23 09:37:13 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-23 09:37:22 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-23 09:37:22 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-23 09:37:39 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-23 09:37:40 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-23 09:37:40 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-23 09:37:40 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-23 09:38:22 - ERROR UnitTestFramework: '#run failed: 'Calling startUpdateAdvertisingAndListening twice is NOT an error', error: 'TimeoutError: timeout exceeded, event: 'teardown_Calling startUpdateAdvertisingAndListening twice is NOT an error_finished', test: 'Calling startUpdateAdvertisingAndListening twice is NOT an error'', stack: 'TimeoutError: timeout exceeded, event: 'teardown_Calling startUpdateAdvertisingAndListening twice is NOT an error_finished', test: 'Calling startUpdateAdvertisingAndListening twice is NOT an error'
    at afterTimeout (/home/pi/Test/server_127148139fecb998/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_127148139fecb998/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-06-23 09:38:22 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'ios', error: 'TimeoutError: timeout exceeded, event: 'teardown_Calling startUpdateAdvertisingAndListening twice is NOT an error_finished', test: 'Calling startUpdateAdvertisingAndListening twice is NOT an error'', stack: 'TimeoutError: timeout exceeded, event: 'teardown_Calling startUpdateAdvertisingAndListening twice is NOT an error_finished', test: 'Calling startUpdateAdvertisingAndListening twice is NOT an error'
    at afterTimeout (/home/pi/Test/server_127148139fecb998/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_127148139fecb998/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-06-23 09:38:37 - ERROR TestServerProcess: 'uncaught promise rejection, error: 'AssertionError: equals arrays expected, received array 1: '[object Object],[object Object],[object Object]', array 2: '[object Object],[object Object],[object Object]'', stack: 'AssertionError: equals arrays expected, received array 1: '[object Object],[object Object],[object Object]', array 2: '[object Object],[object Object],[object Object]'
    at Object.module.exports.arrayEquals (/home/pi/Test/server_127148139fecb998/test/TestServer/utils/asserts.js:69:3)
    at UnitTestFramework.unbindSync (/home/pi/Test/server_127148139fecb998/test/TestServer/UnitTestFramework.js:233:11)
    at /home/pi/Test/server_127148139fecb998/test/TestServer/UnitTestFramework.js:100:10
    at PassThroughHandlerContext.finallyHandler (/home/pi/Test/server_127148139fecb998/test/TestServer/node_modules/bluebird/js/release/finally.js:55:23)
    at PassThroughHandlerContext.tryCatcher (/home/pi/Test/server_127148139fecb998/test/TestServer/node_modules/bluebird/js/release/util.js:16:23)
    at Promise._settlePromiseFromHandler (/home/pi/Test/server_127148139fecb998/test/TestServer/node_modules/bluebird/js/release/promise.js:510:31)
    at Promise._settlePromise (/home/pi/Test/server_127148139fecb998/test/TestServer/node_modules/bluebird/js/release/promise.js:567:18)
    at Promise._settlePromise0 (/home/pi/Test/server_127148139fecb998/test/TestServer/node_modules/bluebird/js/release/promise.js:612:10)
    at Promise._settlePromises (/home/pi/Test/server_127148139fecb998/test/TestServer/node_modules/bluebird/js/release/promise.js:691:18)
    at Promise._fulfill (/home/pi/Test/server_127148139fecb998/test/TestServer/node_modules/bluebird/js/release/promise.js:636:18)
    at PromiseArray._resolve (/home/pi/Test/server_127148139fecb998/test/TestServer/node_modules/bluebird/js/release/promise_array.js:125:19)
    at PromiseArray._promiseFulfilled (/home/pi/Test/server_127148139fecb998/test/TestServer/node_modules/bluebird/js/release/promise_array.js:143:14)
    at Promise._settlePromise (/home/pi/Test/server_127148139fecb998/test/TestServer/node_modules/bluebird/js/release/promise.js:572:26)
    at Promise._settlePromise0 (/home/pi/Test/server_127148139fecb998/test/TestServer/node_modules/bluebird/js/release/promise.js:612:10)
    at Promise._settlePromises (/home/pi/Test/server_127148139fecb998/test/TestServer/node_modules/bluebird/js/release/promise.js:691:18)
    at Async._drainQueue (/home/pi/Test/server_127148139fecb998/test/TestServer/node_modules/bluebird/js/release/async.js:138:16)
    at Async._drainQueues (/home/pi/Test/server_127148139fecb998/test/TestServer/node_modules/bluebird/js/release/async.js:148:10)
    at Async.drainQueues (/home/pi/Test/server_127148139fecb998/test/TestServer/node_modules/bluebird/js/release/async.js:17:14)
    at process._tickCallback (node.js:917:13)''

2017-06-23 09:38:37 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-air-2-1' disconnected, reason: 'undefined''

2017-06-23 09:38:37 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-1' disconnected, reason: 'undefined''

2017-06-23 09:38:37 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-mfts' disconnected, reason: 'undefined''

2017-06-23 09:38:37 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-06-23 09:38:37 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''

2017-06-23 09:38:37 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

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
23/6/2017@11:30:17 Getting the list of iOS devices 
23/6/2017@11:30:18 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
23/6/2017@11:30:18 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
23/6/2017@11:30:18 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
23/6/2017@11:30:18 Deploying iOS test app 
23/6/2017@11:30:18 uninstalling the application 
23/6/2017@11:30:18 installing the application 
23/6/2017@11:53:37 ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
23/6/2017@11:53:37 ios: child process exited with code null on device bffa901fefdea07f59339a6737776943349f5077 
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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/127148139fecb998_Fix_calling_t_end_before_assertion_in_testThaliMobileNative_mlesnic/thali03_samsung-SM-G935F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/127148139fecb998_Fix_calling_t_end_before_assertion_in_testThaliMobileNative_mlesnic/thali04_samsung-SM-G930F.md)

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

Error! Unexpected exit on device ce061606c181d71003 app:com.thaliproject.thalitest code:null 
Child process exited with code null on device ce061606c181d71003
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/127148139fecb998_Fix_calling_t_end_before_assertion_in_testThaliMobileNative_mlesnic/thali05_samsung-SM-G930F.md)


###iOS Logs
[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/127148139fecb998_Fix_calling_t_end_before_assertion_in_testThaliMobileNative_mlesnic/iOS_iphone-5s-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/127148139fecb998_Fix_calling_t_end_before_assertion_in_testThaliMobileNative_mlesnic/iOS_iphone-5s-mfts.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/127148139fecb998_Fix_calling_t_end_before_assertion_in_testThaliMobileNative_mlesnic/iOS_ipad-air-2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/127148139fecb998_Fix_calling_t_end_before_assertion_in_testThaliMobileNative_mlesnic/iOS_server.md)





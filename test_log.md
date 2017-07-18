#### Test 113351851c2b4e9a Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2017-07-18 10:36:21 - INFO HttpServer: 'listening on *:3000'

2017-07-18 10:37:45 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '0d36d4a6-44db-4048-9f05-4a1efe06524d', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-18 10:37:45 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-07-18 10:37:50 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: 'abcd0d61-9367-4c68-8c62-37d9ca07dbbf', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-18 10:37:50 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-07-18 10:39:42 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '38c22df8-3dfc-4034-ad92-0f86abe5861b', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-18 10:39:42 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-07-18 10:39:42 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-07-18 10:39:42 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-07-18 10:39:42 - DEBUG UnitTestFramework: 'scheduling tests'

2017-07-18 10:39:45 - DEBUG UnitTestFramework: 'tests scheduled'

2017-07-18 10:39:45 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-07-18 10:39:46 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-07-18 10:39:46 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-07-18 10:39:49 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-07-18 10:39:49 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-07-18 10:39:51 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-07-18 10:39:51 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-07-18 10:39:52 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-07-18 10:39:52 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-07-18 10:39:56 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-07-18 10:39:56 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-07-18 10:39:59 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-07-18 10:39:59 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-18 10:40:02 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-18 10:40:02 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-18 10:40:05 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-18 10:40:05 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-18 10:40:08 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-18 10:40:08 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-18 10:40:10 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-18 10:40:10 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-18 10:40:12 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-18 10:40:12 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-18 10:40:13 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-18 10:40:13 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-07-18 10:40:16 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-18 10:40:16 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-07-18 10:40:16 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-18 10:40:17 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-18 10:40:18 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-18 10:40:18 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-18 10:40:18 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-07-18 10:40:21 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-18 10:40:21 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-18 10:40:22 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-18 10:40:22 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-18 10:40:22 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-18 10:40:23 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-18 10:40:24 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-18 10:40:24 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-18 10:40:24 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-18 10:40:25 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-18 10:40:25 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-18 10:40:27 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-18 10:40:27 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-18 10:40:27 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-18 10:40:29 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-18 10:40:29 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-18 10:40:29 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-18 10:40:29 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-18 10:40:32 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-18 10:40:32 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-18 10:40:33 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-18 10:40:33 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-18 10:40:33 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-18 10:40:33 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-18 10:40:35 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-18 10:40:35 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-18 10:40:35 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-18 10:40:37 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-18 10:40:37 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-07-18 10:40:39 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-07-18 10:40:39 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-07-18 10:40:41 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-07-18 10:40:41 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-07-18 10:40:43 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-07-18 10:40:43 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-07-18 10:40:45 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-07-18 10:40:45 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-07-18 10:40:47 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-07-18 10:40:47 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-07-18 10:40:49 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-07-18 10:40:49 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-07-18 10:40:50 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-07-18 10:40:50 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-07-18 10:40:53 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-07-18 10:40:53 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-07-18 10:40:55 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-07-18 10:40:55 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-07-18 10:40:56 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-07-18 10:40:56 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-07-18 10:40:59 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-07-18 10:40:59 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-07-18 10:41:01 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-07-18 10:41:01 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-07-18 10:41:04 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-07-18 10:41:04 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-07-18 10:41:04 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-07-18 10:41:04 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-07-18 10:41:04 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-07-18 10:41:04 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-07-18 10:41:04 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-07-18 10:41:04 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-07-18 10:41:04 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-07-18 10:41:04 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-07-18 10:41:04 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-07-18 10:41:04 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-07-18 10:41:04 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-07-18 10:41:04 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-07-18 10:41:04 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-07-18 10:41:04 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-07-18 10:41:04 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-07-18 10:41:04 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-07-18 10:41:04 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-07-18 10:41:04 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-07-18 10:41:04 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-07-18 10:41:04 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-07-18 10:41:04 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-07-18 10:41:04 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-07-18 10:41:04 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-07-18 10:41:04 - DEBUG UnitTestFramework: '#run: 'basic''

2017-07-18 10:41:05 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-07-18 10:41:05 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-07-18 10:41:05 - DEBUG UnitTestFramework: '#teardown ok: 'basic''
2017-07-18 10:41:05 - DEBUG UnitTestFramework: '#setup: 'another''

2017-07-18 10:41:05 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-07-18 10:41:05 - DEBUG UnitTestFramework: '#run: 'another''

2017-07-18 10:41:05 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-07-18 10:41:05 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-07-18 10:41:05 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-07-18 10:41:05 - DEBUG UnitTestFramework: '#setup: 'skip''

2017-07-18 10:41:05 - DEBUG UnitTestFramework: '#setup ok: 'skip''

2017-07-18 10:41:05 - DEBUG UnitTestFramework: '#run: 'skip''

2017-07-18 10:41:05 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-07-18 10:41:05 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-07-18 10:41:05 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-07-18 10:41:05 - DEBUG UnitTestFramework: '#run ok: 'skip''

2017-07-18 10:41:05 - DEBUG UnitTestFramework: '#teardown: 'skip''

2017-07-18 10:41:05 - DEBUG UnitTestFramework: '#teardown ok: 'skip''

2017-07-18 10:41:05 - DEBUG UnitTestFramework: '#setup: 'another skip''

2017-07-18 10:41:05 - DEBUG UnitTestFramework: '#setup ok: 'another skip''

2017-07-18 10:41:05 - DEBUG UnitTestFramework: '#run: 'another skip''

2017-07-18 10:41:05 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-07-18 10:41:05 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-07-18 10:41:05 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-07-18 10:41:05 - DEBUG UnitTestFramework: '#run ok: 'another skip''

2017-07-18 10:41:05 - DEBUG UnitTestFramework: '#teardown: 'another skip''

2017-07-18 10:41:05 - DEBUG UnitTestFramework: '#teardown ok: 'another skip''

2017-07-18 10:41:05 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox spy''

2017-07-18 10:41:05 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox spy''

2017-07-18 10:41:05 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox spy''

2017-07-18 10:41:05 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox spy''

2017-07-18 10:41:05 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox spy''

2017-07-18 10:41:05 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox spy''

2017-07-18 10:41:05 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub''

2017-07-18 10:41:05 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub''

2017-07-18 10:41:05 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub''

2017-07-18 10:41:05 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub''

2017-07-18 10:41:05 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub''

2017-07-18 10:41:05 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub''

2017-07-18 10:41:05 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub override''

2017-07-18 10:41:05 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub override''

2017-07-18 10:41:05 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub override''

2017-07-18 10:41:06 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub override''

2017-07-18 10:41:06 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub override''

2017-07-18 10:41:06 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub override''

2017-07-18 10:41:06 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox mock''

2017-07-18 10:41:06 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox mock''

2017-07-18 10:41:06 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox mock''

2017-07-18 10:41:06 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox mock''

2017-07-18 10:41:06 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox mock''

2017-07-18 10:41:06 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox mock''

2017-07-18 10:41:06 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox restore after test end''

2017-07-18 10:41:06 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox restore after test end''

2017-07-18 10:41:06 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox restore after test end''

2017-07-18 10:41:06 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox restore after test end''

2017-07-18 10:41:06 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox restore after test end''

2017-07-18 10:41:06 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox restore after test end''

2017-07-18 10:41:06 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-07-18 10:41:06 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-07-18 10:41:06 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-07-18 10:41:06 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-07-18 10:41:06 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-07-18 10:41:06 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-07-18 10:41:06 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-07-18 10:41:06 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-07-18 10:41:06 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-07-18 10:41:06 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-07-18 10:41:06 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-07-18 10:41:06 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-07-18 10:41:06 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-07-18 10:41:06 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-07-18 10:41:06 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-07-18 10:41:06 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-07-18 10:41:06 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-07-18 10:41:06 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-07-18 10:41:06 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-07-18 10:41:06 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-07-18 10:41:06 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-07-18 10:41:06 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-07-18 10:41:06 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-07-18 10:41:06 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-07-18 10:41:06 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-07-18 10:41:06 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-07-18 10:41:06 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-07-18 10:41:08 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-07-18 10:41:08 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-07-18 10:41:08 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-07-18 10:41:08 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-18 10:41:08 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-18 10:41:08 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-18 10:41:09 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-18 10:41:09 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-18 10:41:09 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-18 10:41:09 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-18 10:41:10 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-18 10:41:10 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-18 10:41:10 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-18 10:41:10 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-18 10:41:10 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-18 10:41:10 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-18 10:41:10 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-18 10:41:10 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-18 10:41:11 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-18 10:41:11 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-18 10:41:11 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-18 10:41:11 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-18 10:41:11 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-18 10:41:11 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-18 10:41:12 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-18 10:41:12 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-18 10:41:15 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-18 10:41:15 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-18 10:41:18 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-18 10:41:18 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-18 10:41:18 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-18 10:41:18 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-18 10:41:18 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-18 10:41:18 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-07-18 10:41:18 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-07-18 10:41:18 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-07-18 10:41:20 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-07-18 10:41:20 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-07-18 10:41:23 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-07-18 10:41:23 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-07-18 10:41:23 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-07-18 10:41:23 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-07-18 10:41:32 - DEBUG UnitTestFramework: '#run ok: 'Can connect to a remote peer''

2017-07-18 10:41:32 - DEBUG UnitTestFramework: '#teardown: 'Can connect to a remote peer''

2017-07-18 10:41:35 - DEBUG UnitTestFramework: '#teardown ok: 'Can connect to a remote peer''

2017-07-18 10:41:35 - DEBUG UnitTestFramework: '#setup: 'Can shift data''

2017-07-18 10:41:37 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data''

2017-07-18 10:41:37 - DEBUG UnitTestFramework: '#run: 'Can shift data''

2017-07-18 10:41:49 - DEBUG UnitTestFramework: '#run ok: 'Can shift data''

2017-07-18 10:41:49 - DEBUG UnitTestFramework: '#teardown: 'Can shift data''

2017-07-18 10:41:52 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data''

2017-07-18 10:41:52 - DEBUG UnitTestFramework: '#setup: 'Can shift data via parallel connections''

2017-07-18 10:41:54 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data via parallel connections''

2017-07-18 10:41:54 - DEBUG UnitTestFramework: '#run: 'Can shift data via parallel connections''

2017-07-18 10:41:54 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-07-18 10:41:56 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-07-18 10:41:56 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-07-18 10:41:56 - DEBUG UnitTestFramework: '#run ok: 'Can shift data via parallel connections''

2017-07-18 10:41:56 - DEBUG UnitTestFramework: '#teardown: 'Can shift data via parallel connections''

2017-07-18 10:41:56 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data via parallel connections''

2017-07-18 10:41:56 - DEBUG UnitTestFramework: '#setup: 'Can shift data securely''

2017-07-18 10:41:56 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data securely''

2017-07-18 10:41:56 - DEBUG UnitTestFramework: '#run: 'Can shift data securely''

2017-07-18 10:42:11 - DEBUG UnitTestFramework: '#run ok: 'Can shift data securely''

2017-07-18 10:42:11 - DEBUG UnitTestFramework: '#teardown: 'Can shift data securely''

2017-07-18 10:42:12 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data securely''

2017-07-18 10:42:12 - DEBUG UnitTestFramework: '#setup: 'Can shift large amounts of data''

2017-07-18 10:42:14 - DEBUG UnitTestFramework: '#setup ok: 'Can shift large amounts of data''

2017-07-18 10:42:14 - DEBUG UnitTestFramework: '#run: 'Can shift large amounts of data''

2017-07-18 10:42:30 - DEBUG UnitTestFramework: '#run ok: 'Can shift large amounts of data''

2017-07-18 10:42:30 - DEBUG UnitTestFramework: '#teardown: 'Can shift large amounts of data''

2017-07-18 10:42:34 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift large amounts of data''

2017-07-18 10:42:34 - DEBUG UnitTestFramework: '#setup: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-18 10:42:34 - DEBUG UnitTestFramework: '#setup ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-18 10:42:34 - DEBUG UnitTestFramework: '#run: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-18 10:42:42 - DEBUG UnitTestFramework: '#run ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-18 10:42:42 - DEBUG UnitTestFramework: '#teardown: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-18 10:42:45 - DEBUG UnitTestFramework: '#teardown ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-18 10:42:45 - DEBUG UnitTestFramework: '#setup: 'Test updating advertising and parallel data transfer''

2017-07-18 10:42:46 - DEBUG UnitTestFramework: '#setup ok: 'Test updating advertising and parallel data transfer''

2017-07-18 10:42:46 - DEBUG UnitTestFramework: '#run: 'Test updating advertising and parallel data transfer''

2017-07-18 10:42:46 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-07-18 10:42:47 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-07-18 10:42:48 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-07-18 10:42:48 - DEBUG UnitTestFramework: '#run ok: 'Test updating advertising and parallel data transfer''

2017-07-18 10:42:48 - DEBUG UnitTestFramework: '#teardown: 'Test updating advertising and parallel data transfer''

2017-07-18 10:42:50 - DEBUG UnitTestFramework: '#teardown ok: 'Test updating advertising and parallel data transfer''

2017-07-18 10:42:50 - DEBUG UnitTestFramework: '#setup: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-18 10:42:51 - DEBUG UnitTestFramework: '#setup ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-18 10:42:51 - DEBUG UnitTestFramework: '#run: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-18 10:42:56 - DEBUG UnitTestFramework: '#run ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-18 10:42:56 - DEBUG UnitTestFramework: '#teardown: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-18 10:42:59 - DEBUG UnitTestFramework: '#teardown ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-18 10:42:59 - DEBUG UnitTestFramework: '#setup: 'cannot call connect when start listening for advertisements is not active''

2017-07-18 10:43:00 - DEBUG UnitTestFramework: '#setup ok: 'cannot call connect when start listening for advertisements is not active''

2017-07-18 10:43:00 - DEBUG UnitTestFramework: '#run: 'cannot call connect when start listening for advertisements is not active''

2017-07-18 10:43:02 - DEBUG UnitTestFramework: '#run ok: 'cannot call connect when start listening for advertisements is not active''

2017-07-18 10:43:02 - DEBUG UnitTestFramework: '#teardown: 'cannot call connect when start listening for advertisements is not active''

2017-07-18 10:43:03 - DEBUG UnitTestFramework: '#teardown ok: 'cannot call connect when start listening for advertisements is not active''

2017-07-18 10:43:03 - DEBUG UnitTestFramework: '#setup: 'Get error when trying to double connect to a peer on Android''

2017-07-18 10:43:03 - DEBUG UnitTestFramework: '#setup ok: 'Get error when trying to double connect to a peer on Android''

2017-07-18 10:43:03 - DEBUG UnitTestFramework: '#run: 'Get error when trying to double connect to a peer on Android''

2017-07-18 10:43:14 - DEBUG UnitTestFramework: '#run ok: 'Get error when trying to double connect to a peer on Android''

2017-07-18 10:43:14 - DEBUG UnitTestFramework: '#teardown: 'Get error when trying to double connect to a peer on Android''

2017-07-18 10:43:17 - DEBUG UnitTestFramework: '#teardown ok: 'Get error when trying to double connect to a peer on Android''

2017-07-18 10:43:17 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-18 10:43:20 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-18 10:43:20 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-18 10:43:56 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-18 10:43:56 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-18 10:43:57 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-18 10:43:57 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-18 10:43:59 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-18 10:43:59 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-18 10:44:09 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-18 10:44:09 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-18 10:44:13 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-18 10:44:13 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-18 10:44:13 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-18 10:44:13 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-18 10:44:23 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-18 10:44:23 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-18 10:44:27 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-18 10:44:27 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-18 10:44:29 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-18 10:44:29 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-18 10:45:05 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-18 10:45:05 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-18 10:45:09 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-18 10:45:09 - DEBUG UnitTestFramework: '#setup: 'initial peer discovery''

2017-07-18 10:45:12 - DEBUG UnitTestFramework: '#setup ok: 'initial peer discovery''

2017-07-18 10:45:12 - DEBUG UnitTestFramework: '#run: 'initial peer discovery''

2017-07-18 10:45:12 - INFO Socket: 'run skipped, test: 'initial peer discovery', event: 'run_initial peer discovery''

2017-07-18 10:45:12 - INFO Socket: 'run skipped, test: 'initial peer discovery', event: 'run_initial peer discovery''

2017-07-18 10:45:13 - INFO Socket: 'run skipped, test: 'initial peer discovery', event: 'run_initial peer discovery''

2017-07-18 10:45:13 - DEBUG UnitTestFramework: '#run ok: 'initial peer discovery''

2017-07-18 10:45:13 - DEBUG UnitTestFramework: '#teardown: 'initial peer discovery''

2017-07-18 10:45:15 - DEBUG UnitTestFramework: '#teardown ok: 'initial peer discovery''

2017-07-18 10:45:15 - DEBUG UnitTestFramework: '#setup: 'update peer discovery 1''

2017-07-18 10:45:18 - DEBUG UnitTestFramework: '#setup ok: 'update peer discovery 1''

2017-07-18 10:45:18 - DEBUG UnitTestFramework: '#run: 'update peer discovery 1''

2017-07-18 10:45:18 - INFO Socket: 'run skipped, test: 'update peer discovery 1', event: 'run_update peer discovery 1''

2017-07-18 10:45:18 - INFO Socket: 'run skipped, test: 'update peer discovery 1', event: 'run_update peer discovery 1''

2017-07-18 10:45:19 - INFO Socket: 'run skipped, test: 'update peer discovery 1', event: 'run_update peer discovery 1''

2017-07-18 10:45:19 - DEBUG UnitTestFramework: '#run ok: 'update peer discovery 1''

2017-07-18 10:45:19 - DEBUG UnitTestFramework: '#teardown: 'update peer discovery 1''

2017-07-18 10:45:21 - DEBUG UnitTestFramework: '#teardown ok: 'update peer discovery 1''

2017-07-18 10:45:21 - DEBUG UnitTestFramework: '#setup: 'update peer discovery 2''

2017-07-18 10:45:22 - DEBUG UnitTestFramework: '#setup ok: 'update peer discovery 2''

2017-07-18 10:45:22 - DEBUG UnitTestFramework: '#run: 'update peer discovery 2''

2017-07-18 10:45:22 - INFO Socket: 'run skipped, test: 'update peer discovery 2', event: 'run_update peer discovery 2''

2017-07-18 10:45:24 - INFO Socket: 'run skipped, test: 'update peer discovery 2', event: 'run_update peer discovery 2''

2017-07-18 10:45:24 - INFO Socket: 'run skipped, test: 'update peer discovery 2', event: 'run_update peer discovery 2''

2017-07-18 10:45:24 - DEBUG UnitTestFramework: '#run ok: 'update peer discovery 2''

2017-07-18 10:45:24 - DEBUG UnitTestFramework: '#teardown: 'update peer discovery 2''

2017-07-18 10:45:27 - DEBUG UnitTestFramework: '#teardown ok: 'update peer discovery 2''

2017-07-18 10:45:27 - DEBUG UnitTestFramework: '#setup: 'check latest peer discovery''

2017-07-18 10:45:30 - DEBUG UnitTestFramework: '#setup ok: 'check latest peer discovery''

2017-07-18 10:45:30 - DEBUG UnitTestFramework: '#run: 'check latest peer discovery''

2017-07-18 10:45:30 - INFO Socket: 'run skipped, test: 'check latest peer discovery', event: 'run_check latest peer discovery''

2017-07-18 10:45:32 - INFO Socket: 'run skipped, test: 'check latest peer discovery', event: 'run_check latest peer discovery''

2017-07-18 10:45:33 - INFO Socket: 'run skipped, test: 'check latest peer discovery', event: 'run_check latest peer discovery''

2017-07-18 10:45:33 - DEBUG UnitTestFramework: '#run ok: 'check latest peer discovery''

2017-07-18 10:45:33 - DEBUG UnitTestFramework: '#teardown: 'check latest peer discovery''

2017-07-18 10:45:33 - DEBUG UnitTestFramework: '#teardown ok: 'check latest peer discovery''

2017-07-18 10:45:33 - DEBUG UnitTestFramework: '#setup: 'Set up for no peer discovery test''

2017-07-18 10:45:37 - DEBUG UnitTestFramework: '#setup ok: 'Set up for no peer discovery test''

2017-07-18 10:45:37 - DEBUG UnitTestFramework: '#run: 'Set up for no peer discovery test''

2017-07-18 10:45:37 - INFO Socket: 'run skipped, test: 'Set up for no peer discovery test', event: 'run_Set up for no peer discovery test''

2017-07-18 10:45:39 - INFO Socket: 'run skipped, test: 'Set up for no peer discovery test', event: 'run_Set up for no peer discovery test''

2017-07-18 10:45:39 - INFO Socket: 'run skipped, test: 'Set up for no peer discovery test', event: 'run_Set up for no peer discovery test''

2017-07-18 10:45:39 - DEBUG UnitTestFramework: '#run ok: 'Set up for no peer discovery test''

2017-07-18 10:45:39 - DEBUG UnitTestFramework: '#teardown: 'Set up for no peer discovery test''

2017-07-18 10:45:42 - DEBUG UnitTestFramework: '#teardown ok: 'Set up for no peer discovery test''

2017-07-18 10:45:42 - DEBUG UnitTestFramework: '#setup: 'no peer discovery''

2017-07-18 10:45:44 - DEBUG UnitTestFramework: '#setup ok: 'no peer discovery''

2017-07-18 10:45:44 - DEBUG UnitTestFramework: '#run: 'no peer discovery''

2017-07-18 10:45:44 - INFO Socket: 'run skipped, test: 'no peer discovery', event: 'run_no peer discovery''

2017-07-18 10:45:45 - INFO Socket: 'run skipped, test: 'no peer discovery', event: 'run_no peer discovery''

2017-07-18 10:45:45 - INFO Socket: 'run skipped, test: 'no peer discovery', event: 'run_no peer discovery''

2017-07-18 10:45:45 - DEBUG UnitTestFramework: '#run ok: 'no peer discovery''
2017-07-18 10:45:45 - DEBUG UnitTestFramework: '#teardown: 'no peer discovery''

2017-07-18 10:45:47 - DEBUG UnitTestFramework: '#teardown ok: 'no peer discovery''

2017-07-18 10:45:47 - DEBUG UnitTestFramework: '#setup: 'calling createNativeListener directly rejects''

2017-07-18 10:45:49 - DEBUG UnitTestFramework: '#setup ok: 'calling createNativeListener directly rejects''

2017-07-18 10:45:49 - DEBUG UnitTestFramework: '#run: 'calling createNativeListener directly rejects''

2017-07-18 10:45:51 - DEBUG UnitTestFramework: '#run ok: 'calling createNativeListener directly rejects''

2017-07-18 10:45:51 - DEBUG UnitTestFramework: '#teardown: 'calling createNativeListener directly rejects''

2017-07-18 10:45:53 - DEBUG UnitTestFramework: '#teardown ok: 'calling createNativeListener directly rejects''

2017-07-18 10:45:53 - DEBUG UnitTestFramework: '#setup: 'emits incomingConnectionState''

2017-07-18 10:45:55 - DEBUG UnitTestFramework: '#setup ok: 'emits incomingConnectionState''

2017-07-18 10:45:55 - DEBUG UnitTestFramework: '#run: 'emits incomingConnectionState''

2017-07-18 10:45:58 - DEBUG UnitTestFramework: '#run ok: 'emits incomingConnectionState''

2017-07-18 10:45:58 - DEBUG UnitTestFramework: '#teardown: 'emits incomingConnectionState''

2017-07-18 10:46:01 - DEBUG UnitTestFramework: '#teardown ok: 'emits incomingConnectionState''

2017-07-18 10:46:01 - DEBUG UnitTestFramework: '#setup: 'emits routerPortConnectionFailed''

2017-07-18 10:46:02 - DEBUG UnitTestFramework: '#setup ok: 'emits routerPortConnectionFailed''

2017-07-18 10:46:02 - DEBUG UnitTestFramework: '#run: 'emits routerPortConnectionFailed''

2017-07-18 10:46:04 - DEBUG UnitTestFramework: '#run ok: 'emits routerPortConnectionFailed''

2017-07-18 10:46:04 - DEBUG UnitTestFramework: '#teardown: 'emits routerPortConnectionFailed''

2017-07-18 10:46:07 - DEBUG UnitTestFramework: '#teardown ok: 'emits routerPortConnectionFailed''

2017-07-18 10:46:07 - DEBUG UnitTestFramework: '#setup: 'native server connections all up''

2017-07-18 10:46:08 - DEBUG UnitTestFramework: '#setup ok: 'native server connections all up''

2017-07-18 10:46:08 - DEBUG UnitTestFramework: '#run: 'native server connections all up''

2017-07-18 10:46:11 - DEBUG UnitTestFramework: '#run ok: 'native server connections all up''

2017-07-18 10:46:11 - DEBUG UnitTestFramework: '#teardown: 'native server connections all up''

2017-07-18 10:46:14 - DEBUG UnitTestFramework: '#teardown ok: 'native server connections all up''

2017-07-18 10:46:14 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming stream cleans outgoing socket''

2017-07-18 10:46:15 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming stream cleans outgoing socket''

2017-07-18 10:46:15 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming stream cleans outgoing socket''

2017-07-18 10:46:17 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming stream cleans outgoing socket''

2017-07-18 10:46:17 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming stream cleans outgoing socket''

2017-07-18 10:46:18 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming stream cleans outgoing socket''

2017-07-18 10:46:18 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming connection cleans outgoing socket''

2017-07-18 10:46:20 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming connection cleans outgoing socket''

2017-07-18 10:46:20 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming connection cleans outgoing socket''

2017-07-18 10:46:21 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming connection cleans outgoing socket''

2017-07-18 10:46:21 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming connection cleans outgoing socket''

2017-07-18 10:46:23 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming connection cleans outgoing socket''

2017-07-18 10:46:23 - DEBUG UnitTestFramework: '#setup: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-18 10:46:24 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-18 10:46:24 - DEBUG UnitTestFramework: '#run: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-18 10:46:24 - DEBUG UnitTestFramework: '#run ok: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-18 10:46:24 - DEBUG UnitTestFramework: '#teardown: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-18 10:46:24 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-18 10:46:24 - DEBUG UnitTestFramework: '#setup: 'native server - closing the whole server cleans everything up''

2017-07-18 10:46:24 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing the whole server cleans everything up''

2017-07-18 10:46:24 - DEBUG UnitTestFramework: '#run: 'native server - closing the whole server cleans everything up''

2017-07-18 10:46:24 - DEBUG UnitTestFramework: '#run ok: 'native server - closing the whole server cleans everything up''

2017-07-18 10:46:24 - DEBUG UnitTestFramework: '#teardown: 'native server - closing the whole server cleans everything up''

2017-07-18 10:46:24 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing the whole server cleans everything up''

2017-07-18 10:46:24 - DEBUG UnitTestFramework: '#setup: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-18 10:46:24 - DEBUG UnitTestFramework: '#setup ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-18 10:46:24 - DEBUG UnitTestFramework: '#run: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-18 10:46:25 - DEBUG UnitTestFramework: '#run ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-18 10:46:25 - DEBUG UnitTestFramework: '#teardown: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-18 10:46:28 - DEBUG UnitTestFramework: '#teardown ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-18 10:46:28 - DEBUG UnitTestFramework: '#setup: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-18 10:46:29 - DEBUG UnitTestFramework: '#setup ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-18 10:46:29 - DEBUG UnitTestFramework: '#run: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-18 10:46:31 - DEBUG UnitTestFramework: '#run ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-18 10:46:31 - DEBUG UnitTestFramework: '#teardown: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-18 10:46:32 - DEBUG UnitTestFramework: '#teardown ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-18 10:46:32 - DEBUG UnitTestFramework: '#setup: 'native server - timing out the incoming connection cleans everything up''

2017-07-18 10:46:34 - DEBUG UnitTestFramework: '#setup ok: 'native server - timing out the incoming connection cleans everything up''

2017-07-18 10:46:34 - DEBUG UnitTestFramework: '#run: 'native server - timing out the incoming connection cleans everything up''

2017-07-18 10:46:35 - DEBUG UnitTestFramework: '#run ok: 'native server - timing out the incoming connection cleans everything up''

2017-07-18 10:46:35 - DEBUG UnitTestFramework: '#teardown: 'native server - timing out the incoming connection cleans everything up''

2017-07-18 10:46:37 - DEBUG UnitTestFramework: '#teardown ok: 'native server - timing out the incoming connection cleans everything up''

2017-07-18 10:46:37 - DEBUG UnitTestFramework: '#setup: 'can create servers manager''

2017-07-18 10:46:42 - DEBUG UnitTestFramework: '#setup ok: 'can create servers manager''

2017-07-18 10:46:42 - DEBUG UnitTestFramework: '#run: 'can create servers manager''

2017-07-18 10:46:44 - DEBUG UnitTestFramework: '#run ok: 'can create servers manager''

2017-07-18 10:46:44 - DEBUG UnitTestFramework: '#teardown: 'can create servers manager''

2017-07-18 10:46:47 - DEBUG UnitTestFramework: '#teardown ok: 'can create servers manager''

2017-07-18 10:46:47 - DEBUG UnitTestFramework: '#setup: 'calling stop without start causes error''

2017-07-18 10:46:50 - DEBUG UnitTestFramework: '#setup ok: 'calling stop without start causes error''

2017-07-18 10:46:50 - DEBUG UnitTestFramework: '#run: 'calling stop without start causes error''

2017-07-18 10:46:51 - DEBUG UnitTestFramework: '#run ok: 'calling stop without start causes error''

2017-07-18 10:46:51 - DEBUG UnitTestFramework: '#teardown: 'calling stop without start causes error''

2017-07-18 10:46:53 - DEBUG UnitTestFramework: '#teardown ok: 'calling stop without start causes error''

2017-07-18 10:46:53 - DEBUG UnitTestFramework: '#setup: 'can start/stop servers manager''

2017-07-18 10:46:56 - DEBUG UnitTestFramework: '#setup ok: 'can start/stop servers manager''

2017-07-18 10:46:56 - DEBUG UnitTestFramework: '#run: 'can start/stop servers manager''

2017-07-18 10:46:59 - DEBUG UnitTestFramework: '#run ok: 'can start/stop servers manager''

2017-07-18 10:46:59 - DEBUG UnitTestFramework: '#teardown: 'can start/stop servers manager''

2017-07-18 10:47:02 - DEBUG UnitTestFramework: '#teardown ok: 'can start/stop servers manager''

2017-07-18 10:47:02 - DEBUG UnitTestFramework: '#setup: 'starting twice resolves with listening port''

2017-07-18 10:47:05 - DEBUG UnitTestFramework: '#setup ok: 'starting twice resolves with listening port''

2017-07-18 10:47:05 - DEBUG UnitTestFramework: '#run: 'starting twice resolves with listening port''

2017-07-18 10:47:07 - DEBUG UnitTestFramework: '#run ok: 'starting twice resolves with listening port''

2017-07-18 10:47:07 - DEBUG UnitTestFramework: '#teardown: 'starting twice resolves with listening port''

2017-07-18 10:47:08 - DEBUG UnitTestFramework: '#teardown ok: 'starting twice resolves with listening port''

2017-07-18 10:47:08 - DEBUG UnitTestFramework: '#setup: 'terminateIncomingConnection will terminate a connection''

2017-07-18 10:47:12 - DEBUG UnitTestFramework: '#setup ok: 'terminateIncomingConnection will terminate a connection''

2017-07-18 10:47:12 - DEBUG UnitTestFramework: '#run: 'terminateIncomingConnection will terminate a connection''

2017-07-18 10:47:14 - DEBUG UnitTestFramework: '#run ok: 'terminateIncomingConnection will terminate a connection''

2017-07-18 10:47:14 - DEBUG UnitTestFramework: '#teardown: 'terminateIncomingConnection will terminate a connection''

2017-07-18 10:47:15 - DEBUG UnitTestFramework: '#teardown ok: 'terminateIncomingConnection will terminate a connection''

2017-07-18 10:47:15 - DEBUG UnitTestFramework: '#setup: 'terminate an Outgoing connection''

2017-07-18 10:47:18 - DEBUG UnitTestFramework: '#setup ok: 'terminate an Outgoing connection''

2017-07-18 10:47:18 - DEBUG UnitTestFramework: '#run: 'terminate an Outgoing connection''

2017-07-18 10:47:20 - DEBUG UnitTestFramework: '#run ok: 'terminate an Outgoing connection''

2017-07-18 10:47:20 - DEBUG UnitTestFramework: '#teardown: 'terminate an Outgoing connection''

2017-07-18 10:47:21 - DEBUG UnitTestFramework: '#teardown ok: 'terminate an Outgoing connection''

2017-07-18 10:47:21 - DEBUG UnitTestFramework: '#setup: 'Single local http request''

2017-07-18 10:47:23 - DEBUG UnitTestFramework: '#setup ok: 'Single local http request''

2017-07-18 10:47:23 - DEBUG UnitTestFramework: '#run: 'Single local http request''

2017-07-18 10:47:24 - DEBUG UnitTestFramework: '#run ok: 'Single local http request''

2017-07-18 10:47:24 - DEBUG UnitTestFramework: '#teardown: 'Single local http request''

2017-07-18 10:47:26 - DEBUG UnitTestFramework: '#teardown ok: 'Single local http request''

2017-07-18 10:47:26 - DEBUG UnitTestFramework: '#setup: 'Single coordinated request ios native''

2017-07-18 10:47:27 - DEBUG UnitTestFramework: '#setup ok: 'Single coordinated request ios native''

2017-07-18 10:47:27 - DEBUG UnitTestFramework: '#run: 'Single coordinated request ios native''

2017-07-18 10:47:27 - INFO Socket: 'run skipped, test: 'Single coordinated request ios native', event: 'run_Single coordinated request ios native''

2017-07-18 10:47:29 - INFO Socket: 'run skipped, test: 'Single coordinated request ios native', event: 'run_Single coordinated request ios native''

2017-07-18 10:47:30 - INFO Socket: 'run skipped, test: 'Single coordinated request ios native', event: 'run_Single coordinated request ios native''

2017-07-18 10:47:30 - DEBUG UnitTestFramework: '#run ok: 'Single coordinated request ios native''

2017-07-18 10:47:30 - DEBUG UnitTestFramework: '#teardown: 'Single coordinated request ios native''

2017-07-18 10:47:33 - DEBUG UnitTestFramework: '#teardown ok: 'Single coordinated request ios native''

2017-07-18 10:47:33 - DEBUG UnitTestFramework: '#setup: 'Multiple local http requests''

2017-07-18 10:47:36 - DEBUG UnitTestFramework: '#setup ok: 'Multiple local http requests''

2017-07-18 10:47:36 - DEBUG UnitTestFramework: '#run: 'Multiple local http requests''

2017-07-18 10:47:38 - DEBUG UnitTestFramework: '#run ok: 'Multiple local http requests''

2017-07-18 10:47:38 - DEBUG UnitTestFramework: '#teardown: 'Multiple local http requests''

2017-07-18 10:47:39 - DEBUG UnitTestFramework: '#teardown ok: 'Multiple local http requests''

2017-07-18 10:47:39 - DEBUG UnitTestFramework: '#setup: 'Multiple coordinated request ios native''

2017-07-18 10:47:39 - DEBUG UnitTestFramework: '#setup ok: 'Multiple coordinated request ios native''

2017-07-18 10:47:39 - DEBUG UnitTestFramework: '#run: 'Multiple coordinated request ios native''

2017-07-18 10:47:39 - INFO Socket: 'run skipped, test: 'Multiple coordinated request ios native', event: 'run_Multiple coordinated request ios native''

2017-07-18 10:47:39 - INFO Socket: 'run skipped, test: 'Multiple coordinated request ios native', event: 'run_Multiple coordinated request ios native''

2017-07-18 10:47:39 - INFO Socket: 'run skipped, test: 'Multiple coordinated request ios native', event: 'run_Multiple coordinated request ios native''

2017-07-18 10:47:39 - DEBUG UnitTestFramework: '#run ok: 'Multiple coordinated request ios native''

2017-07-18 10:47:39 - DEBUG UnitTestFramework: '#teardown: 'Multiple coordinated request ios native''

2017-07-18 10:47:39 - DEBUG UnitTestFramework: '#teardown ok: 'Multiple coordinated request ios native''

2017-07-18 10:47:39 - DEBUG UnitTestFramework: '#setup: '#startListeningForAdvertisements should fail if start not called''

2017-07-18 10:47:39 - DEBUG UnitTestFramework: '#setup ok: '#startListeningForAdvertisements should fail if start not called''

2017-07-18 10:47:39 - DEBUG UnitTestFramework: '#run: '#startListeningForAdvertisements should fail if start not called''

2017-07-18 10:47:39 - DEBUG UnitTestFramework: '#run ok: '#startListeningForAdvertisements should fail if start not called''

2017-07-18 10:47:39 - DEBUG UnitTestFramework: '#teardown: '#startListeningForAdvertisements should fail if start not called''

2017-07-18 10:47:39 - DEBUG UnitTestFramework: '#teardown ok: '#startListeningForAdvertisements should fail if start not called''

2017-07-18 10:47:39 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-18 10:47:39 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-18 10:47:39 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-18 10:47:39 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-18 10:47:39 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-18 10:47:39 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-18 10:47:39 - DEBUG UnitTestFramework: '#setup: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-18 10:47:39 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-18 10:47:39 - DEBUG UnitTestFramework: '#run: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-18 10:47:39 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-18 10:47:39 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-18 10:47:40 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-18 10:47:40 - DEBUG UnitTestFramework: '#setup: 'should be able to call #startListeningForAdvertisements many times''

2017-07-18 10:47:40 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #startListeningForAdvertisements many times''

2017-07-18 10:47:40 - DEBUG UnitTestFramework: '#run: 'should be able to call #startListeningForAdvertisements many times''

2017-07-18 10:47:40 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #startListeningForAdvertisements many times''

2017-07-18 10:47:40 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #startListeningForAdvertisements many times''

2017-07-18 10:47:41 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #startListeningForAdvertisements many times''

2017-07-18 10:47:41 - DEBUG UnitTestFramework: '#setup: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-18 10:47:41 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-18 10:47:41 - DEBUG UnitTestFramework: '#run: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-18 10:47:42 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-18 10:47:42 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-18 10:47:45 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-18 10:47:45 - DEBUG UnitTestFramework: '#setup: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-18 10:47:48 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-18 10:47:48 - DEBUG UnitTestFramework: '#run: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-18 10:47:49 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-18 10:47:49 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-18 10:47:51 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-18 10:47:51 - DEBUG UnitTestFramework: '#setup: 'can get the network status before starting''

2017-07-18 10:47:52 - DEBUG UnitTestFramework: '#setup ok: 'can get the network status before starting''

2017-07-18 10:47:52 - DEBUG UnitTestFramework: '#run: 'can get the network status before starting''

2017-07-18 10:47:54 - DEBUG UnitTestFramework: '#run ok: 'can get the network status before starting''

2017-07-18 10:47:54 - DEBUG UnitTestFramework: '#teardown: 'can get the network status before starting''

2017-07-18 10:47:55 - DEBUG UnitTestFramework: '#teardown ok: 'can get the network status before starting''

2017-07-18 10:47:55 - DEBUG UnitTestFramework: '#setup: 'error returned with bad router''

2017-07-18 10:47:59 - DEBUG UnitTestFramework: '#setup ok: 'error returned with bad router''

2017-07-18 10:47:59 - DEBUG UnitTestFramework: '#run: 'error returned with bad router''

2017-07-18 10:48:01 - DEBUG UnitTestFramework: '#run ok: 'error returned with bad router''

2017-07-18 10:48:01 - DEBUG UnitTestFramework: '#teardown: 'error returned with bad router''

2017-07-18 10:48:02 - DEBUG UnitTestFramework: '#teardown ok: 'error returned with bad router''

2017-07-18 10:48:02 - DEBUG UnitTestFramework: '#setup: 'all services are started when we call start''

2017-07-18 10:48:04 - DEBUG UnitTestFramework: '#setup ok: 'all services are started when we call start''

2017-07-18 10:48:04 - DEBUG UnitTestFramework: '#run: 'all services are started when we call start''

2017-07-18 10:48:05 - DEBUG UnitTestFramework: '#run ok: 'all services are started when we call start''

2017-07-18 10:48:05 - DEBUG UnitTestFramework: '#teardown: 'all services are started when we call start''

2017-07-18 10:48:06 - DEBUG UnitTestFramework: '#teardown ok: 'all services are started when we call start''

2017-07-18 10:48:06 - DEBUG UnitTestFramework: '#setup: 'TCP Servers Manager should be null when we call start on iOS''

2017-07-18 10:48:06 - DEBUG UnitTestFramework: '#setup ok: 'TCP Servers Manager should be null when we call start on iOS''

2017-07-18 10:48:06 - DEBUG UnitTestFramework: '#run: 'TCP Servers Manager should be null when we call start on iOS''

2017-07-18 10:48:06 - INFO Socket: 'run skipped, test: 'TCP Servers Manager should be null when we call start on iOS', event: 'run_TCP Servers Manager should be null when we call start on iOS''

2017-07-18 10:48:06 - INFO Socket: 'run skipped, test: 'TCP Servers Manager should be null when we call start on iOS', event: 'run_TCP Servers Manager should be null when we call start on iOS''

2017-07-18 10:48:06 - INFO Socket: 'run skipped, test: 'TCP Servers Manager should be null when we call start on iOS', event: 'run_TCP Servers Manager should be null when we call start on iOS''

2017-07-18 10:48:06 - DEBUG UnitTestFramework: '#run ok: 'TCP Servers Manager should be null when we call start on iOS''

2017-07-18 10:48:06 - DEBUG UnitTestFramework: '#teardown: 'TCP Servers Manager should be null when we call start on iOS''

2017-07-18 10:48:06 - DEBUG UnitTestFramework: '#teardown ok: 'TCP Servers Manager should be null when we call start on iOS''

2017-07-18 10:48:06 - DEBUG UnitTestFramework: '#setup: 'all services are stopped when we call stop''

2017-07-18 10:48:06 - DEBUG UnitTestFramework: '#setup ok: 'all services are stopped when we call stop''

2017-07-18 10:48:06 - DEBUG UnitTestFramework: '#run: 'all services are stopped when we call stop''

2017-07-18 10:48:09 - DEBUG UnitTestFramework: '#run ok: 'all services are stopped when we call stop''

2017-07-18 10:48:09 - DEBUG UnitTestFramework: '#teardown: 'all services are stopped when we call stop''

2017-07-18 10:48:11 - DEBUG UnitTestFramework: '#teardown ok: 'all services are stopped when we call stop''

2017-07-18 10:48:11 - DEBUG UnitTestFramework: '#setup: 'make sure terminateConnection is properly hooked up''

2017-07-18 10:48:14 - DEBUG UnitTestFramework: '#setup ok: 'make sure terminateConnection is properly hooked up''

2017-07-18 10:48:14 - DEBUG UnitTestFramework: '#run: 'make sure terminateConnection is properly hooked up''

2017-07-18 10:48:15 - DEBUG UnitTestFramework: '#run ok: 'make sure terminateConnection is properly hooked up''

2017-07-18 10:48:15 - DEBUG UnitTestFramework: '#teardown: 'make sure terminateConnection is properly hooked up''

2017-07-18 10:48:17 - DEBUG UnitTestFramework: '#teardown ok: 'make sure terminateConnection is properly hooked up''

2017-07-18 10:48:17 - DEBUG UnitTestFramework: '#setup: 'make sure terminateConnection is return error if we get called on iOS''

2017-07-18 10:48:20 - DEBUG UnitTestFramework: '#setup ok: 'make sure terminateConnection is return error if we get called on iOS''

2017-07-18 10:48:20 - DEBUG UnitTestFramework: '#run: 'make sure terminateConnection is return error if we get called on iOS''

2017-07-18 10:48:20 - INFO Socket: 'run skipped, test: 'make sure terminateConnection is return error if we get called on iOS', event: 'run_make sure terminateConnection is return error if we get called on iOS''

2017-07-18 10:48:20 - INFO Socket: 'run skipped, test: 'make sure terminateConnection is return error if we get called on iOS', event: 'run_make sure terminateConnection is return error if we get called on iOS''

2017-07-18 10:48:21 - INFO Socket: 'run skipped, test: 'make sure terminateConnection is return error if we get called on iOS', event: 'run_make sure terminateConnection is return error if we get called on iOS''

2017-07-18 10:48:21 - DEBUG UnitTestFramework: '#run ok: 'make sure terminateConnection is return error if we get called on iOS''

2017-07-18 10:48:21 - DEBUG UnitTestFramework: '#teardown: 'make sure terminateConnection is return error if we get called on iOS''

2017-07-18 10:48:23 - DEBUG UnitTestFramework: '#teardown ok: 'make sure terminateConnection is return error if we get called on iOS''

2017-07-18 10:48:23 - DEBUG UnitTestFramework: '#setup: 'make sure terminateListener is properly hooked up''

2017-07-18 10:48:26 - DEBUG UnitTestFramework: '#setup ok: 'make sure terminateListener is properly hooked up''

2017-07-18 10:48:26 - DEBUG UnitTestFramework: '#run: 'make sure terminateListener is properly hooked up''

2017-07-18 10:48:27 - DEBUG UnitTestFramework: '#run ok: 'make sure terminateListener is properly hooked up''

2017-07-18 10:48:27 - DEBUG UnitTestFramework: '#teardown: 'make sure terminateListener is properly hooked up''

2017-07-18 10:48:29 - DEBUG UnitTestFramework: '#teardown ok: 'make sure terminateListener is properly hooked up''

2017-07-18 10:48:29 - DEBUG UnitTestFramework: '#setup: 'make sure terminateListener is return error if we get called on iOS''

2017-07-18 10:48:32 - DEBUG UnitTestFramework: '#setup ok: 'make sure terminateListener is return error if we get called on iOS''

2017-07-18 10:48:32 - DEBUG UnitTestFramework: '#run: 'make sure terminateListener is return error if we get called on iOS''

2017-07-18 10:48:32 - INFO Socket: 'run skipped, test: 'make sure terminateListener is return error if we get called on iOS', event: 'run_make sure terminateListener is return error if we get called on iOS''

2017-07-18 10:48:32 - INFO Socket: 'run skipped, test: 'make sure terminateListener is return error if we get called on iOS', event: 'run_make sure terminateListener is return error if we get called on iOS''

2017-07-18 10:48:33 - INFO Socket: 'run skipped, test: 'make sure terminateListener is return error if we get called on iOS', event: 'run_make sure terminateListener is return error if we get called on iOS''

2017-07-18 10:48:33 - DEBUG UnitTestFramework: '#run ok: 'make sure terminateListener is return error if we get called on iOS''

2017-07-18 10:48:33 - DEBUG UnitTestFramework: '#teardown: 'make sure terminateListener is return error if we get called on iOS''

2017-07-18 10:48:35 - DEBUG UnitTestFramework: '#teardown ok: 'make sure terminateListener is return error if we get called on iOS''

2017-07-18 10:48:35 - DEBUG UnitTestFramework: '#setup: 'make sure we actually call kill connections properly''

2017-07-18 10:48:38 - DEBUG UnitTestFramework: '#setup ok: 'make sure we actually call kill connections properly''

2017-07-18 10:48:38 - DEBUG UnitTestFramework: '#run: 'make sure we actually call kill connections properly''

2017-07-18 10:48:39 - DEBUG UnitTestFramework: '#run ok: 'make sure we actually call kill connections properly''

2017-07-18 10:48:39 - DEBUG UnitTestFramework: '#teardown: 'make sure we actually call kill connections properly''

2017-07-18 10:48:42 - DEBUG UnitTestFramework: '#teardown ok: 'make sure we actually call kill connections properly''

2017-07-18 10:48:42 - DEBUG UnitTestFramework: '#setup: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-07-18 10:48:44 - DEBUG UnitTestFramework: '#setup ok: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-07-18 10:48:44 - DEBUG UnitTestFramework: '#run: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-07-18 10:48:45 - DEBUG UnitTestFramework: '#run ok: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-07-18 10:48:45 - DEBUG UnitTestFramework: '#teardown: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-07-18 10:48:47 - DEBUG UnitTestFramework: '#teardown ok: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-07-18 10:48:47 - DEBUG UnitTestFramework: '#setup: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-07-18 10:48:50 - DEBUG UnitTestFramework: '#setup ok: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-07-18 10:48:50 - DEBUG UnitTestFramework: '#run: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-07-18 10:48:51 - DEBUG UnitTestFramework: '#run ok: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-07-18 10:48:51 - DEBUG UnitTestFramework: '#teardown: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-07-18 10:48:53 - DEBUG UnitTestFramework: '#teardown ok: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-07-18 10:48:53 - DEBUG UnitTestFramework: '#setup: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-18 10:48:56 - DEBUG UnitTestFramework: '#setup ok: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-18 10:48:56 - DEBUG UnitTestFramework: '#run: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-18 10:48:56 - INFO Socket: 'run skipped, test: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection', event: 'run_We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-18 10:48:57 - INFO Socket: 'run skipped, test: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection', event: 'run_We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-18 10:48:59 - INFO Socket: 'run skipped, test: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection', event: 'run_We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-18 10:48:59 - DEBUG UnitTestFramework: '#run ok: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-18 10:48:59 - DEBUG UnitTestFramework: '#teardown: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-18 10:49:01 - DEBUG UnitTestFramework: '#teardown ok: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-18 10:49:01 - DEBUG UnitTestFramework: '#setup: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-18 10:49:03 - DEBUG UnitTestFramework: '#setup ok: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-18 10:49:03 - DEBUG UnitTestFramework: '#run: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-18 10:49:03 - INFO Socket: 'run skipped, test: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection', event: 'run_We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-18 10:49:04 - INFO Socket: 'run skipped, test: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection', event: 'run_We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-18 10:49:05 - INFO Socket: 'run skipped, test: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection', event: 'run_We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-18 10:49:05 - DEBUG UnitTestFramework: '#run ok: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-18 10:49:05 - DEBUG UnitTestFramework: '#teardown: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-18 10:49:07 - DEBUG UnitTestFramework: '#teardown ok: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-18 10:49:07 - DEBUG UnitTestFramework: '#setup: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved''

2017-07-18 10:49:08 - DEBUG UnitTestFramework: '#setup ok: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved''

2017-07-18 10:49:08 - DEBUG UnitTestFramework: '#run: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved''

2017-07-18 10:49:12 - DEBUG UnitTestFramework: '#run ok: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved''

2017-07-18 10:49:12 - DEBUG UnitTestFramework: '#teardown: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved''

2017-07-18 10:49:14 - DEBUG UnitTestFramework: '#teardown ok: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved''

2017-07-18 10:49:14 - DEBUG UnitTestFramework: '#setup: 'make sure bad PSK connections fail''

2017-07-18 10:49:15 - DEBUG UnitTestFramework: '#setup ok: 'make sure bad PSK connections fail''

2017-07-18 10:49:15 - DEBUG UnitTestFramework: '#run: 'make sure bad PSK connections fail''

2017-07-18 10:49:15 - INFO Socket: 'run skipped, test: 'make sure bad PSK connections fail', event: 'run_make sure bad PSK connections fail''

2017-07-18 10:49:16 - INFO Socket: 'run skipped, test: 'make sure bad PSK connections fail', event: 'run_make sure bad PSK connections fail''

2017-07-18 10:49:17 - INFO Socket: 'run skipped, test: 'make sure bad PSK connections fail', event: 'run_make sure bad PSK connections fail''

2017-07-18 10:49:17 - DEBUG UnitTestFramework: '#run ok: 'make sure bad PSK connections fail''

2017-07-18 10:49:17 - DEBUG UnitTestFramework: '#teardown: 'make sure bad PSK connections fail''

2017-07-18 10:49:19 - DEBUG UnitTestFramework: '#teardown ok: 'make sure bad PSK connections fail''

2017-07-18 10:49:19 - DEBUG UnitTestFramework: '#setup: 'peer changes handled from a queue''

2017-07-18 10:49:21 - DEBUG UnitTestFramework: '#setup ok: 'peer changes handled from a queue''

2017-07-18 10:49:21 - DEBUG UnitTestFramework: '#run: 'peer changes handled from a queue''

2017-07-18 10:49:21 - INFO Socket: 'run skipped, test: 'peer changes handled from a queue', event: 'run_peer changes handled from a queue''

2017-07-18 10:49:22 - INFO Socket: 'run skipped, test: 'peer changes handled from a queue', event: 'run_peer changes handled from a queue''

2017-07-18 10:49:23 - INFO Socket: 'run skipped, test: 'peer changes handled from a queue', event: 'run_peer changes handled from a queue''

2017-07-18 10:49:23 - DEBUG UnitTestFramework: '#run ok: 'peer changes handled from a queue''

2017-07-18 10:49:23 - DEBUG UnitTestFramework: '#teardown: 'peer changes handled from a queue''

2017-07-18 10:49:25 - DEBUG UnitTestFramework: '#teardown ok: 'peer changes handled from a queue''

2017-07-18 10:49:25 - DEBUG UnitTestFramework: '#setup: 'relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-18 10:49:27 - DEBUG UnitTestFramework: '#setup ok: 'relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-18 10:49:27 - DEBUG UnitTestFramework: '#run: 'relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-18 10:49:27 - INFO Socket: 'run skipped, test: 'relaying discoveryAdvertisingStateUpdateNonTCP', event: 'run_relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-18 10:49:28 - INFO Socket: 'run skipped, test: 'relaying discoveryAdvertisingStateUpdateNonTCP', event: 'run_relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-18 10:49:29 - INFO Socket: 'run skipped, test: 'relaying discoveryAdvertisingStateUpdateNonTCP', event: 'run_relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-18 10:49:29 - DEBUG UnitTestFramework: '#run ok: 'relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-18 10:49:29 - DEBUG UnitTestFramework: '#teardown: 'relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-18 10:49:31 - DEBUG UnitTestFramework: '#teardown ok: 'relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-18 10:49:31 - DEBUG UnitTestFramework: '#setup: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-18 10:49:32 - DEBUG UnitTestFramework: '#setup ok: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-18 10:49:32 - DEBUG UnitTestFramework: '#run: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-18 10:49:32 - INFO Socket: 'run skipped, test: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received', event: 'run_thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-18 10:49:32 - INFO Socket: 'run skipped, test: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received', event: 'run_thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-18 10:49:34 - INFO Socket: 'run skipped, test: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received', event: 'run_thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-18 10:49:34 - DEBUG UnitTestFramework: '#run ok: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-18 10:49:34 - DEBUG UnitTestFramework: '#teardown: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-18 10:49:37 - DEBUG UnitTestFramework: '#teardown ok: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-18 10:49:37 - DEBUG UnitTestFramework: '#setup: 'we successfully receive and replay discoveryAdvertisingStateUpdate''

2017-07-18 10:49:39 - DEBUG UnitTestFramework: '#setup ok: 'we successfully receive and replay discoveryAdvertisingStateUpdate''

2017-07-18 10:49:39 - DEBUG UnitTestFramework: '#run: 'we successfully receive and replay discoveryAdvertisingStateUpdate''

2017-07-18 10:49:43 - DEBUG UnitTestFramework: '#run ok: 'we successfully receive and replay discoveryAdvertisingStateUpdate''

2017-07-18 10:49:43 - DEBUG UnitTestFramework: '#teardown: 'we successfully receive and replay discoveryAdvertisingStateUpdate''

2017-07-18 10:49:43 - DEBUG UnitTestFramework: '#teardown ok: 'we successfully receive and replay discoveryAdvertisingStateUpdate''

2017-07-18 10:49:43 - DEBUG UnitTestFramework: '#setup: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-07-18 10:49:44 - DEBUG UnitTestFramework: '#setup ok: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-07-18 10:49:44 - DEBUG UnitTestFramework: '#run: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-07-18 10:49:44 - INFO Socket: 'run skipped, test: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS', event: 'run_nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-07-18 10:49:44 - INFO Socket: 'run skipped, test: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS', event: 'run_nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-07-18 10:49:47 - INFO Socket: 'run skipped, test: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS', event: 'run_nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-07-18 10:49:47 - DEBUG UnitTestFramework: '#run ok: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-07-18 10:49:47 - DEBUG UnitTestFramework: '#teardown: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-07-18 10:49:47 - DEBUG UnitTestFramework: '#teardown ok: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-07-18 10:49:47 - DEBUG UnitTestFramework: '#setup: 'can do HTTP requests between peers''

2017-07-18 10:49:50 - DEBUG UnitTestFramework: '#setup ok: 'can do HTTP requests between peers''

2017-07-18 10:49:50 - DEBUG UnitTestFramework: '#run: 'can do HTTP requests between peers''

2017-07-18 10:50:00 - DEBUG UnitTestFramework: '#run ok: 'can do HTTP requests between peers''

2017-07-18 10:50:00 - DEBUG UnitTestFramework: '#teardown: 'can do HTTP requests between peers''

2017-07-18 10:50:00 - DEBUG UnitTestFramework: '#teardown ok: 'can do HTTP requests between peers''

2017-07-18 10:50:00 - DEBUG UnitTestFramework: '#setup: 'can still do HTTP requests between peers with coordinator''

2017-07-18 10:50:03 - DEBUG UnitTestFramework: '#setup ok: 'can still do HTTP requests between peers with coordinator''

2017-07-18 10:50:03 - DEBUG UnitTestFramework: '#run: 'can still do HTTP requests between peers with coordinator''

2017-07-18 10:51:04 - ERROR UnitTestFramework: '#run failed: 'can still do HTTP requests between peers with coordinator', error: 'Error: run failed, test: 'can still do HTTP requests between peers with coordinator', event: 'run_can still do HTTP requests between peers with coordinator', sent data: '[{"uuid":"0d36d4a6-44db-4048-9f05-4a1efe06524d"},{"uuid":"abcd0d61-9367-4c68-8c62-37d9ca07dbbf"},{"uuid":"38c22df8-3dfc-4034-ad92-0f86abe5861b"}]', received data: '{"success":false}'', stack: 'Error: run failed, test: 'can still do HTTP requests between peers with coordinator', event: 'run_can still do HTTP requests between peers with coordinator', sent data: '[{"uuid":"0d36d4a6-44db-4048-9f05-4a1efe06524d"},{"uuid":"abcd0d61-9367-4c68-8c62-37d9ca07dbbf"},{"uuid":"38c22df8-3dfc-4034-ad92-0f86abe5861b"}]', received data: '{"success":false}'
    at finishedHandler (/home/pi/Test/server_113351851c2b4e9a/test/TestServer/Socket.js:205:15)
    at Socket.<anonymous> (/home/pi/Test/server_113351851c2b4e9a/test/TestServer/Socket.js:238:9)
    at Socket.g (events.js:160:16)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_113351851c2b4e9a/test/TestServer/node_modules/socket.io/lib/socket.js:335:8)
    at Socket.onpacket (/home/pi/Test/server_113351851c2b4e9a/test/TestServer/node_modules/socket.io/lib/socket.js:295:12)
    at Client.ondecoded (/home/pi/Test/server_113351851c2b4e9a/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_113351851c2b4e9a/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_113351851c2b4e9a/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_113351851c2b4e9a/test/TestServer/node_modules/socket.io/lib/client.js:175:18)
    at Socket.emit (events.js:82:17)
    at Socket.onPacket (/home/pi/Test/server_113351851c2b4e9a/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/socket.js:101:14)
    at WebSocket.emit (events.js:82:17)
    at WebSocket.Transport.onPacket (/home/pi/Test/server_113351851c2b4e9a/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:104:8)
    at WebSocket.Transport.onData (/home/pi/Test/server_113351851c2b4e9a/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:115:8)
    at WebSocket.onData (/home/pi/Test/server_113351851c2b4e9a/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transports/websocket.js:76:30)
    at WebSocket.emit (events.js:85:17)''

2017-07-18 10:51:04 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'android', error: 'Error: run failed, test: 'can still do HTTP requests between peers with coordinator', event: 'run_can still do HTTP requests between peers with coordinator', sent data: '[{"uuid":"0d36d4a6-44db-4048-9f05-4a1efe06524d"},{"uuid":"abcd0d61-9367-4c68-8c62-37d9ca07dbbf"},{"uuid":"38c22df8-3dfc-4034-ad92-0f86abe5861b"}]', received data: '{"success":false}'', stack: 'Error: run failed, test: 'can still do HTTP requests between peers with coordinator', event: 'run_can still do HTTP requests between peers with coordinator', sent data: '[{"uuid":"0d36d4a6-44db-4048-9f05-4a1efe06524d"},{"uuid":"abcd0d61-9367-4c68-8c62-37d9ca07dbbf"},{"uuid":"38c22df8-3dfc-4034-ad92-0f86abe5861b"}]', received data: '{"success":false}'
    at finishedHandler (/home/pi/Test/server_113351851c2b4e9a/test/TestServer/Socket.js:205:15)
    at Socket.<anonymous> (/home/pi/Test/server_113351851c2b4e9a/test/TestServer/Socket.js:238:9)
    at Socket.g (events.js:160:16)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_113351851c2b4e9a/test/TestServer/node_modules/socket.io/lib/socket.js:335:8)
    at Socket.onpacket (/home/pi/Test/server_113351851c2b4e9a/test/TestServer/node_modules/socket.io/lib/socket.js:295:12)
    at Client.ondecoded (/home/pi/Test/server_113351851c2b4e9a/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_113351851c2b4e9a/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_113351851c2b4e9a/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_113351851c2b4e9a/test/TestServer/node_modules/socket.io/lib/client.js:175:18)
    at Socket.emit (events.js:82:17)
    at Socket.onPacket (/home/pi/Test/server_113351851c2b4e9a/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/socket.js:101:14)
    at WebSocket.emit (events.js:82:17)
    at WebSocket.Transport.onPacket (/home/pi/Test/server_113351851c2b4e9a/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:104:8)
    at WebSocket.Transport.onData (/home/pi/Test/server_113351851c2b4e9a/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:115:8)
    at WebSocket.onData (/home/pi/Test/server_113351851c2b4e9a/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transports/websocket.js:76:30)
    at WebSocket.emit (events.js:85:17)''

2017-07-18 10:51:06 - DEBUG TestServer: 'completed'

2017-07-18 10:51:06 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-07-18 10:51:06 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''

2017-07-18 10:51:06 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

[0;31merror: command 'sudo jx ______.js android' failed with code 1, file 'bash' on line 30[0m
One or more Android tests are failed.
 [0m
index.js failed [ 1 ]

```


Logs for system : 
```

android : Error: Command failed: copying android script192.168.1.52
copying android script192.168.1.50
copying android script192.168.1.53
Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!
```
###Android Logs
####Node name: thali01
Console output:
```
Stopping app on  ce061606e320561102
Stopping App:com.thaliproject.thalitest ce061606e320561102 green
Uninstalling app on  ce061606e320561102
Uninstalling App:com.thaliproject.thalitest ce061606e320561102 green
is Device booted ce061606e320561102 0 green
Checking:  adb -s ce061606e320561102 shell getprop sys.boot_completed green
is Device booted ce061606e320561102 10000 green
Checking:  adb -s ce061606e320561102 shell getprop sys.boot_completed green

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

Stopping App:com.thaliproject.thalitest ce061606e320561102 green
Device test finished on ce061606e320561102 
Android task is completed. [FAILED]
Stopping App:com.thaliproject.thalitest ce061606e320561102 green
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/113351851c2b4e9a_CI_sanity_check_jareksl/thali01_samsung-SM-G935F.md)

####Node name: thali03
Console output:
```
Stopping app on  ce061606c181d71003
Stopping App:com.thaliproject.thalitest ce061606c181d71003 green
Uninstalling app on  ce061606c181d71003
Uninstalling App:com.thaliproject.thalitest ce061606c181d71003 green
is Device booted ce061606c181d71003 0 green
Checking:  adb -s ce061606c181d71003 shell getprop sys.boot_completed green
is Device booted ce061606c181d71003 10000 green
Checking:  adb -s ce061606c181d71003 shell getprop sys.boot_completed green

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

Stopping App:com.thaliproject.thalitest ce061606c181d71003 green
Device test finished on ce061606c181d71003 
Android task is completed. [FAILED]
Stopping App:com.thaliproject.thalitest ce061606c181d71003 green
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/113351851c2b4e9a_CI_sanity_check_jareksl/thali03_samsung-SM-G930F.md)

####Node name: thali04
Console output:
```
Stopping app on  ce0616068b9f212302
Stopping App:com.thaliproject.thalitest ce0616068b9f212302 green
Uninstalling app on  ce0616068b9f212302
Uninstalling App:com.thaliproject.thalitest ce0616068b9f212302 green
is Device booted ce0616068b9f212302 0 green
Checking:  adb -s ce0616068b9f212302 shell getprop sys.boot_completed green
is Device booted ce0616068b9f212302 10000 green
Checking:  adb -s ce0616068b9f212302 shell getprop sys.boot_completed green

All devices are ready!

Deploying to ce0616068b9f212302
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce0616068b9f212302

Starting application ThaliTest on ce0616068b9f212302

App was succesfully started on ce0616068b9f212302

STOP log received from ce0616068b9f212302
Test has FAILED

Stopping App:com.thaliproject.thalitest ce0616068b9f212302 green
Device test finished on ce0616068b9f212302 
Android task is completed. [FAILED]
Stopping App:com.thaliproject.thalitest ce0616068b9f212302 green
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/113351851c2b4e9a_CI_sanity_check_jareksl/thali04_samsung-SM-G930F.md)





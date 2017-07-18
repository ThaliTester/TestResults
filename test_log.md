#### Test 113351851f433a54 Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2017-07-18 11:55:23 - INFO HttpServer: 'listening on *:3000'

2017-07-18 11:56:49 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '6814a713-249d-4049-8241-8bd839a5e75d', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-18 11:56:49 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-07-18 11:56:59 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: 'be37db3a-ca48-4f5a-a5f1-9c4f547608e1', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-18 11:56:59 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-07-18 11:58:30 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'b2d5aedb-d219-4eee-ac67-5098c02258b6', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-18 11:58:30 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-07-18 11:58:30 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-07-18 11:58:30 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-07-18 11:58:30 - DEBUG UnitTestFramework: 'scheduling tests'

2017-07-18 11:58:32 - DEBUG UnitTestFramework: 'tests scheduled'

2017-07-18 11:58:32 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-07-18 11:58:34 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-07-18 11:58:34 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-07-18 11:58:36 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-07-18 11:58:36 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-07-18 11:58:37 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-07-18 11:58:37 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-07-18 11:58:39 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-07-18 11:58:39 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-07-18 11:58:45 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-07-18 11:58:45 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-07-18 11:58:45 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-07-18 11:58:45 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-18 11:58:48 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-18 11:58:48 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-18 11:58:49 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-18 11:58:49 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-18 11:58:51 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-18 11:58:51 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-18 11:58:51 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-18 11:58:51 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-18 11:58:54 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-18 11:58:54 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-18 11:58:55 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-18 11:58:55 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-07-18 11:58:57 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-18 11:58:57 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-07-18 11:58:57 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-18 11:58:57 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-18 11:58:58 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-18 11:58:58 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-18 11:58:58 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-07-18 11:59:00 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-18 11:59:00 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-18 11:59:03 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-18 11:59:03 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-18 11:59:03 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-18 11:59:03 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-18 11:59:07 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-18 11:59:07 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-18 11:59:07 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-18 11:59:09 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-18 11:59:09 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-18 11:59:11 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-18 11:59:11 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-18 11:59:11 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-18 11:59:13 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-18 11:59:14 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-18 11:59:14 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-18 11:59:14 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-18 11:59:16 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-18 11:59:16 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-18 11:59:18 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-18 11:59:18 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-18 11:59:18 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-18 11:59:18 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-18 11:59:19 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-18 11:59:19 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-18 11:59:19 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-18 11:59:21 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-18 11:59:21 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-07-18 11:59:25 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-07-18 11:59:25 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-07-18 11:59:27 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-07-18 11:59:28 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-07-18 11:59:29 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-07-18 11:59:29 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-07-18 11:59:31 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-07-18 11:59:31 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-07-18 11:59:34 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-07-18 11:59:34 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-07-18 11:59:36 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-07-18 11:59:36 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-07-18 11:59:37 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-07-18 11:59:37 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-07-18 11:59:39 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-07-18 11:59:39 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-07-18 11:59:40 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-07-18 11:59:40 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-07-18 11:59:43 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-07-18 11:59:43 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-07-18 11:59:45 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-07-18 11:59:45 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-07-18 11:59:46 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-07-18 11:59:46 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-07-18 11:59:48 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-07-18 11:59:48 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-07-18 11:59:49 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-07-18 11:59:49 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-07-18 11:59:51 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-07-18 11:59:51 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-07-18 11:59:54 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-07-18 11:59:54 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-07-18 11:59:55 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-07-18 11:59:55 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-07-18 11:59:55 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-07-18 11:59:55 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-07-18 11:59:55 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-07-18 11:59:55 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-07-18 11:59:55 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-07-18 11:59:55 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-07-18 11:59:55 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-07-18 11:59:55 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-07-18 11:59:55 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-07-18 11:59:55 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-07-18 11:59:55 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-07-18 11:59:55 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-07-18 11:59:55 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-07-18 11:59:55 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-07-18 11:59:55 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-07-18 11:59:55 - DEBUG UnitTestFramework: '#run: 'basic''

2017-07-18 11:59:56 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-07-18 11:59:56 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-07-18 11:59:56 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-07-18 11:59:56 - DEBUG UnitTestFramework: '#setup: 'another''

2017-07-18 11:59:56 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-07-18 11:59:56 - DEBUG UnitTestFramework: '#run: 'another''

2017-07-18 11:59:56 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-07-18 11:59:56 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-07-18 11:59:56 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-07-18 11:59:56 - DEBUG UnitTestFramework: '#setup: 'skip''

2017-07-18 11:59:56 - DEBUG UnitTestFramework: '#setup ok: 'skip''

2017-07-18 11:59:56 - DEBUG UnitTestFramework: '#run: 'skip''

2017-07-18 11:59:56 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-07-18 11:59:56 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-07-18 11:59:56 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-07-18 11:59:56 - DEBUG UnitTestFramework: '#run ok: 'skip''

2017-07-18 11:59:56 - DEBUG UnitTestFramework: '#teardown: 'skip''

2017-07-18 11:59:56 - DEBUG UnitTestFramework: '#teardown ok: 'skip''

2017-07-18 11:59:56 - DEBUG UnitTestFramework: '#setup: 'another skip''

2017-07-18 11:59:56 - DEBUG UnitTestFramework: '#setup ok: 'another skip''

2017-07-18 11:59:56 - DEBUG UnitTestFramework: '#run: 'another skip''

2017-07-18 11:59:56 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-07-18 11:59:56 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-07-18 11:59:56 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-07-18 11:59:56 - DEBUG UnitTestFramework: '#run ok: 'another skip''

2017-07-18 11:59:56 - DEBUG UnitTestFramework: '#teardown: 'another skip''

2017-07-18 11:59:56 - DEBUG UnitTestFramework: '#teardown ok: 'another skip''

2017-07-18 11:59:56 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox spy''

2017-07-18 11:59:56 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox spy''

2017-07-18 11:59:56 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox spy''

2017-07-18 11:59:56 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox spy''

2017-07-18 11:59:56 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox spy''

2017-07-18 11:59:56 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox spy''

2017-07-18 11:59:56 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub''

2017-07-18 11:59:56 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub''

2017-07-18 11:59:56 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub''

2017-07-18 11:59:56 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub''

2017-07-18 11:59:56 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub''

2017-07-18 11:59:56 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub''

2017-07-18 11:59:56 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub override''

2017-07-18 11:59:56 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub override''

2017-07-18 11:59:56 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub override''

2017-07-18 11:59:57 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub override''

2017-07-18 11:59:57 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub override''

2017-07-18 11:59:57 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub override''

2017-07-18 11:59:57 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox mock''

2017-07-18 11:59:57 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox mock''

2017-07-18 11:59:57 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox mock''

2017-07-18 11:59:57 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox mock''

2017-07-18 11:59:57 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox mock''

2017-07-18 11:59:57 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox mock''

2017-07-18 11:59:57 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox restore after test end''

2017-07-18 11:59:57 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox restore after test end''

2017-07-18 11:59:57 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox restore after test end''

2017-07-18 11:59:57 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox restore after test end''

2017-07-18 11:59:57 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox restore after test end''

2017-07-18 11:59:57 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox restore after test end''

2017-07-18 11:59:57 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-07-18 11:59:57 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-07-18 11:59:57 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-07-18 11:59:57 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-07-18 11:59:57 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-07-18 11:59:57 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-07-18 11:59:57 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-07-18 11:59:57 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-07-18 11:59:57 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-07-18 11:59:57 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-07-18 11:59:57 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-07-18 11:59:57 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-07-18 11:59:57 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-07-18 11:59:57 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-07-18 11:59:57 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-07-18 11:59:57 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-07-18 11:59:57 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-07-18 11:59:57 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-07-18 11:59:57 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-07-18 11:59:57 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-07-18 11:59:57 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-07-18 11:59:57 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-07-18 11:59:57 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-07-18 11:59:57 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-07-18 11:59:57 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-07-18 11:59:57 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-07-18 11:59:57 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-07-18 11:59:59 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-07-18 11:59:59 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-07-18 11:59:59 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-07-18 11:59:59 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-18 11:59:59 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-18 11:59:59 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-18 12:00:00 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-18 12:00:00 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-18 12:00:00 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-18 12:00:00 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-18 12:00:00 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-18 12:00:00 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-18 12:00:00 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-18 12:00:00 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-18 12:00:00 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-18 12:00:00 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-18 12:00:01 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-18 12:00:01 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-18 12:00:01 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-18 12:00:01 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-18 12:00:02 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-18 12:00:02 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-18 12:00:02 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-18 12:00:02 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-18 12:00:03 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-18 12:00:03 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-18 12:00:06 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-18 12:00:06 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-18 12:00:08 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-18 12:00:08 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-18 12:00:12 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-18 12:00:12 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-18 12:00:13 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-18 12:00:13 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-07-18 12:00:15 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-07-18 12:00:15 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-07-18 12:00:18 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-07-18 12:00:18 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-07-18 12:00:21 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-07-18 12:00:21 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-07-18 12:00:22 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-07-18 12:00:22 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-07-18 12:00:35 - DEBUG UnitTestFramework: '#run ok: 'Can connect to a remote peer''

2017-07-18 12:00:35 - DEBUG UnitTestFramework: '#teardown: 'Can connect to a remote peer''

2017-07-18 12:00:38 - DEBUG UnitTestFramework: '#teardown ok: 'Can connect to a remote peer''

2017-07-18 12:00:38 - DEBUG UnitTestFramework: '#setup: 'Can shift data''

2017-07-18 12:00:41 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data''

2017-07-18 12:00:41 - DEBUG UnitTestFramework: '#run: 'Can shift data''

2017-07-18 12:00:51 - DEBUG UnitTestFramework: '#run ok: 'Can shift data''

2017-07-18 12:00:51 - DEBUG UnitTestFramework: '#teardown: 'Can shift data''

2017-07-18 12:00:53 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data''

2017-07-18 12:00:53 - DEBUG UnitTestFramework: '#setup: 'Can shift data via parallel connections''

2017-07-18 12:00:55 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data via parallel connections''

2017-07-18 12:00:55 - DEBUG UnitTestFramework: '#run: 'Can shift data via parallel connections''

2017-07-18 12:00:55 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-07-18 12:00:55 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-07-18 12:00:58 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-07-18 12:00:58 - DEBUG UnitTestFramework: '#run ok: 'Can shift data via parallel connections''

2017-07-18 12:00:58 - DEBUG UnitTestFramework: '#teardown: 'Can shift data via parallel connections''

2017-07-18 12:00:59 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data via parallel connections''

2017-07-18 12:00:59 - DEBUG UnitTestFramework: '#setup: 'Can shift data securely''

2017-07-18 12:01:01 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data securely''

2017-07-18 12:01:01 - DEBUG UnitTestFramework: '#run: 'Can shift data securely''

2017-07-18 12:01:09 - DEBUG UnitTestFramework: '#run ok: 'Can shift data securely''

2017-07-18 12:01:09 - DEBUG UnitTestFramework: '#teardown: 'Can shift data securely''

2017-07-18 12:01:12 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data securely''

2017-07-18 12:01:12 - DEBUG UnitTestFramework: '#setup: 'Can shift large amounts of data''

2017-07-18 12:01:14 - DEBUG UnitTestFramework: '#setup ok: 'Can shift large amounts of data''

2017-07-18 12:01:14 - DEBUG UnitTestFramework: '#run: 'Can shift large amounts of data''

2017-07-18 12:01:27 - DEBUG UnitTestFramework: '#run ok: 'Can shift large amounts of data''

2017-07-18 12:01:27 - DEBUG UnitTestFramework: '#teardown: 'Can shift large amounts of data''

2017-07-18 12:01:29 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift large amounts of data''

2017-07-18 12:01:29 - DEBUG UnitTestFramework: '#setup: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-18 12:01:31 - DEBUG UnitTestFramework: '#setup ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-18 12:01:31 - DEBUG UnitTestFramework: '#run: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-18 12:01:40 - DEBUG UnitTestFramework: '#run ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-18 12:01:40 - DEBUG UnitTestFramework: '#teardown: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-18 12:01:42 - DEBUG UnitTestFramework: '#teardown ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-18 12:01:42 - DEBUG UnitTestFramework: '#setup: 'Test updating advertising and parallel data transfer''

2017-07-18 12:01:45 - DEBUG UnitTestFramework: '#setup ok: 'Test updating advertising and parallel data transfer''

2017-07-18 12:01:45 - DEBUG UnitTestFramework: '#run: 'Test updating advertising and parallel data transfer''

2017-07-18 12:01:45 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-07-18 12:01:45 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-07-18 12:01:46 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-07-18 12:01:46 - DEBUG UnitTestFramework: '#run ok: 'Test updating advertising and parallel data transfer''

2017-07-18 12:01:46 - DEBUG UnitTestFramework: '#teardown: 'Test updating advertising and parallel data transfer''

2017-07-18 12:01:48 - DEBUG UnitTestFramework: '#teardown ok: 'Test updating advertising and parallel data transfer''

2017-07-18 12:01:48 - DEBUG UnitTestFramework: '#setup: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-18 12:01:51 - DEBUG UnitTestFramework: '#setup ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-18 12:01:51 - DEBUG UnitTestFramework: '#run: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-18 12:01:54 - DEBUG UnitTestFramework: '#run ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-18 12:01:54 - DEBUG UnitTestFramework: '#teardown: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-18 12:01:56 - DEBUG UnitTestFramework: '#teardown ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-18 12:01:56 - DEBUG UnitTestFramework: '#setup: 'cannot call connect when start listening for advertisements is not active''

2017-07-18 12:01:59 - DEBUG UnitTestFramework: '#setup ok: 'cannot call connect when start listening for advertisements is not active''

2017-07-18 12:01:59 - DEBUG UnitTestFramework: '#run: 'cannot call connect when start listening for advertisements is not active''

2017-07-18 12:02:00 - DEBUG UnitTestFramework: '#run ok: 'cannot call connect when start listening for advertisements is not active''

2017-07-18 12:02:00 - DEBUG UnitTestFramework: '#teardown: 'cannot call connect when start listening for advertisements is not active''

2017-07-18 12:02:03 - DEBUG UnitTestFramework: '#teardown ok: 'cannot call connect when start listening for advertisements is not active''

2017-07-18 12:02:03 - DEBUG UnitTestFramework: '#setup: 'Get error when trying to double connect to a peer on Android''

2017-07-18 12:02:05 - DEBUG UnitTestFramework: '#setup ok: 'Get error when trying to double connect to a peer on Android''

2017-07-18 12:02:05 - DEBUG UnitTestFramework: '#run: 'Get error when trying to double connect to a peer on Android''

2017-07-18 12:02:11 - DEBUG UnitTestFramework: '#run ok: 'Get error when trying to double connect to a peer on Android''

2017-07-18 12:02:11 - DEBUG UnitTestFramework: '#teardown: 'Get error when trying to double connect to a peer on Android''

2017-07-18 12:02:15 - DEBUG UnitTestFramework: '#teardown ok: 'Get error when trying to double connect to a peer on Android''

2017-07-18 12:02:15 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-18 12:02:16 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-18 12:02:16 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-18 12:02:29 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-18 12:02:29 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-18 12:02:31 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-18 12:02:31 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-18 12:02:32 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-18 12:02:32 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-18 12:03:01 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-18 12:03:01 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-18 12:03:02 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-18 12:03:02 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-18 12:03:04 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-18 12:03:04 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-18 12:03:11 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-18 12:03:11 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-18 12:03:13 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-18 12:03:13 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-18 12:03:15 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-18 12:03:15 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-18 12:03:23 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-18 12:03:23 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-18 12:03:26 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-18 12:03:26 - DEBUG UnitTestFramework: '#setup: 'initial peer discovery''

2017-07-18 12:03:27 - DEBUG UnitTestFramework: '#setup ok: 'initial peer discovery''

2017-07-18 12:03:27 - DEBUG UnitTestFramework: '#run: 'initial peer discovery''

2017-07-18 12:03:27 - INFO Socket: 'run skipped, test: 'initial peer discovery', event: 'run_initial peer discovery''

2017-07-18 12:03:28 - INFO Socket: 'run skipped, test: 'initial peer discovery', event: 'run_initial peer discovery''

2017-07-18 12:03:30 - INFO Socket: 'run skipped, test: 'initial peer discovery', event: 'run_initial peer discovery''

2017-07-18 12:03:30 - DEBUG UnitTestFramework: '#run ok: 'initial peer discovery''

2017-07-18 12:03:30 - DEBUG UnitTestFramework: '#teardown: 'initial peer discovery''

2017-07-18 12:03:31 - DEBUG UnitTestFramework: '#teardown ok: 'initial peer discovery''

2017-07-18 12:03:31 - DEBUG UnitTestFramework: '#setup: 'update peer discovery 1''

2017-07-18 12:03:33 - DEBUG UnitTestFramework: '#setup ok: 'update peer discovery 1''

2017-07-18 12:03:33 - DEBUG UnitTestFramework: '#run: 'update peer discovery 1''

2017-07-18 12:03:33 - INFO Socket: 'run skipped, test: 'update peer discovery 1', event: 'run_update peer discovery 1''

2017-07-18 12:03:34 - INFO Socket: 'run skipped, test: 'update peer discovery 1', event: 'run_update peer discovery 1''

2017-07-18 12:03:36 - INFO Socket: 'run skipped, test: 'update peer discovery 1', event: 'run_update peer discovery 1''

2017-07-18 12:03:36 - DEBUG UnitTestFramework: '#run ok: 'update peer discovery 1''

2017-07-18 12:03:36 - DEBUG UnitTestFramework: '#teardown: 'update peer discovery 1''

2017-07-18 12:03:37 - DEBUG UnitTestFramework: '#teardown ok: 'update peer discovery 1''

2017-07-18 12:03:37 - DEBUG UnitTestFramework: '#setup: 'update peer discovery 2''

2017-07-18 12:03:39 - DEBUG UnitTestFramework: '#setup ok: 'update peer discovery 2''

2017-07-18 12:03:39 - DEBUG UnitTestFramework: '#run: 'update peer discovery 2''

2017-07-18 12:03:39 - INFO Socket: 'run skipped, test: 'update peer discovery 2', event: 'run_update peer discovery 2''

2017-07-18 12:03:40 - INFO Socket: 'run skipped, test: 'update peer discovery 2', event: 'run_update peer discovery 2''

2017-07-18 12:03:40 - INFO Socket: 'run skipped, test: 'update peer discovery 2', event: 'run_update peer discovery 2''

2017-07-18 12:03:40 - DEBUG UnitTestFramework: '#run ok: 'update peer discovery 2''

2017-07-18 12:03:40 - DEBUG UnitTestFramework: '#teardown: 'update peer discovery 2''

2017-07-18 12:03:45 - DEBUG UnitTestFramework: '#teardown ok: 'update peer discovery 2''

2017-07-18 12:03:45 - DEBUG UnitTestFramework: '#setup: 'check latest peer discovery''

2017-07-18 12:03:46 - DEBUG UnitTestFramework: '#setup ok: 'check latest peer discovery''

2017-07-18 12:03:46 - DEBUG UnitTestFramework: '#run: 'check latest peer discovery''

2017-07-18 12:03:46 - INFO Socket: 'run skipped, test: 'check latest peer discovery', event: 'run_check latest peer discovery''

2017-07-18 12:03:48 - INFO Socket: 'run skipped, test: 'check latest peer discovery', event: 'run_check latest peer discovery''

2017-07-18 12:03:49 - INFO Socket: 'run skipped, test: 'check latest peer discovery', event: 'run_check latest peer discovery''

2017-07-18 12:03:49 - DEBUG UnitTestFramework: '#run ok: 'check latest peer discovery''

2017-07-18 12:03:49 - DEBUG UnitTestFramework: '#teardown: 'check latest peer discovery''

2017-07-18 12:03:51 - DEBUG UnitTestFramework: '#teardown ok: 'check latest peer discovery''

2017-07-18 12:03:51 - DEBUG UnitTestFramework: '#setup: 'Set up for no peer discovery test''

2017-07-18 12:03:52 - DEBUG UnitTestFramework: '#setup ok: 'Set up for no peer discovery test''

2017-07-18 12:03:52 - DEBUG UnitTestFramework: '#run: 'Set up for no peer discovery test''

2017-07-18 12:03:52 - INFO Socket: 'run skipped, test: 'Set up for no peer discovery test', event: 'run_Set up for no peer discovery test''

2017-07-18 12:03:54 - INFO Socket: 'run skipped, test: 'Set up for no peer discovery test', event: 'run_Set up for no peer discovery test''

2017-07-18 12:03:55 - INFO Socket: 'run skipped, test: 'Set up for no peer discovery test', event: 'run_Set up for no peer discovery test''

2017-07-18 12:03:55 - DEBUG UnitTestFramework: '#run ok: 'Set up for no peer discovery test''

2017-07-18 12:03:55 - DEBUG UnitTestFramework: '#teardown: 'Set up for no peer discovery test''

2017-07-18 12:03:57 - DEBUG UnitTestFramework: '#teardown ok: 'Set up for no peer discovery test''

2017-07-18 12:03:57 - DEBUG UnitTestFramework: '#setup: 'no peer discovery''

2017-07-18 12:04:00 - DEBUG UnitTestFramework: '#setup ok: 'no peer discovery''

2017-07-18 12:04:00 - DEBUG UnitTestFramework: '#run: 'no peer discovery''

2017-07-18 12:04:00 - INFO Socket: 'run skipped, test: 'no peer discovery', event: 'run_no peer discovery''

2017-07-18 12:04:00 - INFO Socket: 'run skipped, test: 'no peer discovery', event: 'run_no peer discovery''

2017-07-18 12:04:02 - INFO Socket: 'run skipped, test: 'no peer discovery', event: 'run_no peer discovery''

2017-07-18 12:04:02 - DEBUG UnitTestFramework: '#run ok: 'no peer discovery''
2017-07-18 12:04:02 - DEBUG UnitTestFramework: '#teardown: 'no peer discovery''

2017-07-18 12:04:03 - DEBUG UnitTestFramework: '#teardown ok: 'no peer discovery''

2017-07-18 12:04:03 - DEBUG UnitTestFramework: '#setup: 'calling createNativeListener directly rejects''

2017-07-18 12:04:05 - DEBUG UnitTestFramework: '#setup ok: 'calling createNativeListener directly rejects''

2017-07-18 12:04:05 - DEBUG UnitTestFramework: '#run: 'calling createNativeListener directly rejects''

2017-07-18 12:04:06 - DEBUG UnitTestFramework: '#run ok: 'calling createNativeListener directly rejects''

2017-07-18 12:04:06 - DEBUG UnitTestFramework: '#teardown: 'calling createNativeListener directly rejects''

2017-07-18 12:04:08 - DEBUG UnitTestFramework: '#teardown ok: 'calling createNativeListener directly rejects''

2017-07-18 12:04:08 - DEBUG UnitTestFramework: '#setup: 'emits incomingConnectionState''

2017-07-18 12:04:11 - DEBUG UnitTestFramework: '#setup ok: 'emits incomingConnectionState''

2017-07-18 12:04:11 - DEBUG UnitTestFramework: '#run: 'emits incomingConnectionState''

2017-07-18 12:04:14 - DEBUG UnitTestFramework: '#run ok: 'emits incomingConnectionState''

2017-07-18 12:04:14 - DEBUG UnitTestFramework: '#teardown: 'emits incomingConnectionState''

2017-07-18 12:04:17 - DEBUG UnitTestFramework: '#teardown ok: 'emits incomingConnectionState''

2017-07-18 12:04:17 - DEBUG UnitTestFramework: '#setup: 'emits routerPortConnectionFailed''

2017-07-18 12:04:18 - DEBUG UnitTestFramework: '#setup ok: 'emits routerPortConnectionFailed''

2017-07-18 12:04:18 - DEBUG UnitTestFramework: '#run: 'emits routerPortConnectionFailed''

2017-07-18 12:04:20 - DEBUG UnitTestFramework: '#run ok: 'emits routerPortConnectionFailed''

2017-07-18 12:04:20 - DEBUG UnitTestFramework: '#teardown: 'emits routerPortConnectionFailed''

2017-07-18 12:04:22 - DEBUG UnitTestFramework: '#teardown ok: 'emits routerPortConnectionFailed''

2017-07-18 12:04:22 - DEBUG UnitTestFramework: '#setup: 'native server connections all up''

2017-07-18 12:04:24 - DEBUG UnitTestFramework: '#setup ok: 'native server connections all up''

2017-07-18 12:04:24 - DEBUG UnitTestFramework: '#run: 'native server connections all up''

2017-07-18 12:04:27 - DEBUG UnitTestFramework: '#run ok: 'native server connections all up''

2017-07-18 12:04:27 - DEBUG UnitTestFramework: '#teardown: 'native server connections all up''

2017-07-18 12:04:29 - DEBUG UnitTestFramework: '#teardown ok: 'native server connections all up''

2017-07-18 12:04:29 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming stream cleans outgoing socket''

2017-07-18 12:04:31 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming stream cleans outgoing socket''

2017-07-18 12:04:31 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming stream cleans outgoing socket''

2017-07-18 12:04:33 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming stream cleans outgoing socket''

2017-07-18 12:04:33 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming stream cleans outgoing socket''

2017-07-18 12:04:35 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming stream cleans outgoing socket''

2017-07-18 12:04:35 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming connection cleans outgoing socket''

2017-07-18 12:04:37 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming connection cleans outgoing socket''

2017-07-18 12:04:37 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming connection cleans outgoing socket''

2017-07-18 12:04:39 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming connection cleans outgoing socket''

2017-07-18 12:04:39 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming connection cleans outgoing socket''

2017-07-18 12:04:41 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming connection cleans outgoing socket''

2017-07-18 12:04:41 - DEBUG UnitTestFramework: '#setup: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-18 12:04:44 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-18 12:04:44 - DEBUG UnitTestFramework: '#run: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-18 12:04:46 - DEBUG UnitTestFramework: '#run ok: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-18 12:04:46 - DEBUG UnitTestFramework: '#teardown: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-18 12:04:48 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-18 12:04:48 - DEBUG UnitTestFramework: '#setup: 'native server - closing the whole server cleans everything up''

2017-07-18 12:04:49 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing the whole server cleans everything up''

2017-07-18 12:04:49 - DEBUG UnitTestFramework: '#run: 'native server - closing the whole server cleans everything up''

2017-07-18 12:04:52 - DEBUG UnitTestFramework: '#run ok: 'native server - closing the whole server cleans everything up''

2017-07-18 12:04:52 - DEBUG UnitTestFramework: '#teardown: 'native server - closing the whole server cleans everything up''

2017-07-18 12:04:54 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing the whole server cleans everything up''

2017-07-18 12:04:54 - DEBUG UnitTestFramework: '#setup: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-18 12:04:55 - DEBUG UnitTestFramework: '#setup ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-18 12:04:55 - DEBUG UnitTestFramework: '#run: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-18 12:04:56 - DEBUG UnitTestFramework: '#run ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-18 12:04:56 - DEBUG UnitTestFramework: '#teardown: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-18 12:04:59 - DEBUG UnitTestFramework: '#teardown ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-18 12:04:59 - DEBUG UnitTestFramework: '#setup: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-18 12:05:02 - DEBUG UnitTestFramework: '#setup ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-18 12:05:02 - DEBUG UnitTestFramework: '#run: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-18 12:05:03 - DEBUG UnitTestFramework: '#run ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-18 12:05:03 - DEBUG UnitTestFramework: '#teardown: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-18 12:05:05 - DEBUG UnitTestFramework: '#teardown ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-18 12:05:05 - DEBUG UnitTestFramework: '#setup: 'native server - timing out the incoming connection cleans everything up''

2017-07-18 12:05:08 - DEBUG UnitTestFramework: '#setup ok: 'native server - timing out the incoming connection cleans everything up''

2017-07-18 12:05:08 - DEBUG UnitTestFramework: '#run: 'native server - timing out the incoming connection cleans everything up''

2017-07-18 12:05:09 - DEBUG UnitTestFramework: '#run ok: 'native server - timing out the incoming connection cleans everything up''

2017-07-18 12:05:09 - DEBUG UnitTestFramework: '#teardown: 'native server - timing out the incoming connection cleans everything up''

2017-07-18 12:05:11 - DEBUG UnitTestFramework: '#teardown ok: 'native server - timing out the incoming connection cleans everything up''

2017-07-18 12:05:11 - DEBUG UnitTestFramework: '#setup: 'can create servers manager''

2017-07-18 12:05:15 - DEBUG UnitTestFramework: '#setup ok: 'can create servers manager''

2017-07-18 12:05:15 - DEBUG UnitTestFramework: '#run: 'can create servers manager''

2017-07-18 12:05:17 - DEBUG UnitTestFramework: '#run ok: 'can create servers manager''

2017-07-18 12:05:17 - DEBUG UnitTestFramework: '#teardown: 'can create servers manager''

2017-07-18 12:05:18 - DEBUG UnitTestFramework: '#teardown ok: 'can create servers manager''

2017-07-18 12:05:18 - DEBUG UnitTestFramework: '#setup: 'calling stop without start causes error''

2017-07-18 12:05:20 - DEBUG UnitTestFramework: '#setup ok: 'calling stop without start causes error''

2017-07-18 12:05:20 - DEBUG UnitTestFramework: '#run: 'calling stop without start causes error''

2017-07-18 12:05:20 - DEBUG UnitTestFramework: '#run ok: 'calling stop without start causes error''

2017-07-18 12:05:20 - DEBUG UnitTestFramework: '#teardown: 'calling stop without start causes error''

2017-07-18 12:05:20 - DEBUG UnitTestFramework: '#teardown ok: 'calling stop without start causes error''

2017-07-18 12:05:20 - DEBUG UnitTestFramework: '#setup: 'can start/stop servers manager''

2017-07-18 12:05:20 - DEBUG UnitTestFramework: '#setup ok: 'can start/stop servers manager''

2017-07-18 12:05:20 - DEBUG UnitTestFramework: '#run: 'can start/stop servers manager''

2017-07-18 12:05:20 - DEBUG UnitTestFramework: '#run ok: 'can start/stop servers manager''

2017-07-18 12:05:20 - DEBUG UnitTestFramework: '#teardown: 'can start/stop servers manager''

2017-07-18 12:05:21 - DEBUG UnitTestFramework: '#teardown ok: 'can start/stop servers manager''

2017-07-18 12:05:21 - DEBUG UnitTestFramework: '#setup: 'starting twice resolves with listening port''

2017-07-18 12:05:21 - DEBUG UnitTestFramework: '#setup ok: 'starting twice resolves with listening port''

2017-07-18 12:05:21 - DEBUG UnitTestFramework: '#run: 'starting twice resolves with listening port''

2017-07-18 12:05:21 - DEBUG UnitTestFramework: '#run ok: 'starting twice resolves with listening port''

2017-07-18 12:05:21 - DEBUG UnitTestFramework: '#teardown: 'starting twice resolves with listening port''

2017-07-18 12:05:21 - DEBUG UnitTestFramework: '#teardown ok: 'starting twice resolves with listening port''

2017-07-18 12:05:21 - DEBUG UnitTestFramework: '#setup: 'terminateIncomingConnection will terminate a connection''

2017-07-18 12:05:21 - DEBUG UnitTestFramework: '#setup ok: 'terminateIncomingConnection will terminate a connection''

2017-07-18 12:05:21 - DEBUG UnitTestFramework: '#run: 'terminateIncomingConnection will terminate a connection''

2017-07-18 12:05:21 - DEBUG UnitTestFramework: '#run ok: 'terminateIncomingConnection will terminate a connection''

2017-07-18 12:05:21 - DEBUG UnitTestFramework: '#teardown: 'terminateIncomingConnection will terminate a connection''

2017-07-18 12:05:21 - DEBUG UnitTestFramework: '#teardown ok: 'terminateIncomingConnection will terminate a connection''

2017-07-18 12:05:21 - DEBUG UnitTestFramework: '#setup: 'terminate an Outgoing connection''

2017-07-18 12:05:21 - DEBUG UnitTestFramework: '#setup ok: 'terminate an Outgoing connection''

2017-07-18 12:05:21 - DEBUG UnitTestFramework: '#run: 'terminate an Outgoing connection''

2017-07-18 12:05:21 - DEBUG UnitTestFramework: '#run ok: 'terminate an Outgoing connection''

2017-07-18 12:05:21 - DEBUG UnitTestFramework: '#teardown: 'terminate an Outgoing connection''

2017-07-18 12:05:21 - DEBUG UnitTestFramework: '#teardown ok: 'terminate an Outgoing connection''

2017-07-18 12:05:21 - DEBUG UnitTestFramework: '#setup: 'Single local http request''

2017-07-18 12:05:21 - DEBUG UnitTestFramework: '#setup ok: 'Single local http request''

2017-07-18 12:05:21 - DEBUG UnitTestFramework: '#run: 'Single local http request''

2017-07-18 12:05:21 - DEBUG UnitTestFramework: '#run ok: 'Single local http request''

2017-07-18 12:05:21 - DEBUG UnitTestFramework: '#teardown: 'Single local http request''

2017-07-18 12:05:21 - DEBUG UnitTestFramework: '#teardown ok: 'Single local http request''

2017-07-18 12:05:21 - DEBUG UnitTestFramework: '#setup: 'Single coordinated request ios native''

2017-07-18 12:05:21 - DEBUG UnitTestFramework: '#setup ok: 'Single coordinated request ios native''

2017-07-18 12:05:21 - DEBUG UnitTestFramework: '#run: 'Single coordinated request ios native''

2017-07-18 12:05:21 - INFO Socket: 'run skipped, test: 'Single coordinated request ios native', event: 'run_Single coordinated request ios native''

2017-07-18 12:05:21 - INFO Socket: 'run skipped, test: 'Single coordinated request ios native', event: 'run_Single coordinated request ios native''

2017-07-18 12:05:21 - INFO Socket: 'run skipped, test: 'Single coordinated request ios native', event: 'run_Single coordinated request ios native''

2017-07-18 12:05:21 - DEBUG UnitTestFramework: '#run ok: 'Single coordinated request ios native''

2017-07-18 12:05:21 - DEBUG UnitTestFramework: '#teardown: 'Single coordinated request ios native''

2017-07-18 12:05:21 - DEBUG UnitTestFramework: '#teardown ok: 'Single coordinated request ios native''

2017-07-18 12:05:21 - DEBUG UnitTestFramework: '#setup: 'Multiple local http requests''

2017-07-18 12:05:21 - DEBUG UnitTestFramework: '#setup ok: 'Multiple local http requests''

2017-07-18 12:05:21 - DEBUG UnitTestFramework: '#run: 'Multiple local http requests''

2017-07-18 12:05:22 - DEBUG UnitTestFramework: '#run ok: 'Multiple local http requests''

2017-07-18 12:05:22 - DEBUG UnitTestFramework: '#teardown: 'Multiple local http requests''

2017-07-18 12:05:22 - DEBUG UnitTestFramework: '#teardown ok: 'Multiple local http requests''

2017-07-18 12:05:22 - DEBUG UnitTestFramework: '#setup: 'Multiple coordinated request ios native''

2017-07-18 12:05:22 - DEBUG UnitTestFramework: '#setup ok: 'Multiple coordinated request ios native''

2017-07-18 12:05:22 - DEBUG UnitTestFramework: '#run: 'Multiple coordinated request ios native''

2017-07-18 12:05:22 - INFO Socket: 'run skipped, test: 'Multiple coordinated request ios native', event: 'run_Multiple coordinated request ios native''

2017-07-18 12:05:22 - INFO Socket: 'run skipped, test: 'Multiple coordinated request ios native', event: 'run_Multiple coordinated request ios native''

2017-07-18 12:05:22 - INFO Socket: 'run skipped, test: 'Multiple coordinated request ios native', event: 'run_Multiple coordinated request ios native''

2017-07-18 12:05:22 - DEBUG UnitTestFramework: '#run ok: 'Multiple coordinated request ios native''

2017-07-18 12:05:22 - DEBUG UnitTestFramework: '#teardown: 'Multiple coordinated request ios native''

2017-07-18 12:05:22 - DEBUG UnitTestFramework: '#teardown ok: 'Multiple coordinated request ios native''

2017-07-18 12:05:22 - DEBUG UnitTestFramework: '#setup: '#startListeningForAdvertisements should fail if start not called''

2017-07-18 12:05:22 - DEBUG UnitTestFramework: '#setup ok: '#startListeningForAdvertisements should fail if start not called''

2017-07-18 12:05:22 - DEBUG UnitTestFramework: '#run: '#startListeningForAdvertisements should fail if start not called''

2017-07-18 12:05:22 - DEBUG UnitTestFramework: '#run ok: '#startListeningForAdvertisements should fail if start not called''

2017-07-18 12:05:22 - DEBUG UnitTestFramework: '#teardown: '#startListeningForAdvertisements should fail if start not called''

2017-07-18 12:05:22 - DEBUG UnitTestFramework: '#teardown ok: '#startListeningForAdvertisements should fail if start not called''

2017-07-18 12:05:22 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-18 12:05:22 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-18 12:05:22 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-18 12:05:22 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-18 12:05:22 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-18 12:05:22 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-18 12:05:22 - DEBUG UnitTestFramework: '#setup: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-18 12:05:22 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-18 12:05:22 - DEBUG UnitTestFramework: '#run: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-18 12:05:22 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-18 12:05:22 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-18 12:05:22 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-18 12:05:22 - DEBUG UnitTestFramework: '#setup: 'should be able to call #startListeningForAdvertisements many times''

2017-07-18 12:05:22 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #startListeningForAdvertisements many times''

2017-07-18 12:05:22 - DEBUG UnitTestFramework: '#run: 'should be able to call #startListeningForAdvertisements many times''

2017-07-18 12:05:23 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #startListeningForAdvertisements many times''

2017-07-18 12:05:23 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #startListeningForAdvertisements many times''

2017-07-18 12:05:27 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #startListeningForAdvertisements many times''

2017-07-18 12:05:27 - DEBUG UnitTestFramework: '#setup: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-18 12:05:29 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-18 12:05:29 - DEBUG UnitTestFramework: '#run: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-18 12:05:34 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-18 12:05:34 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-18 12:05:36 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-18 12:05:36 - DEBUG UnitTestFramework: '#setup: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-18 12:05:39 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-18 12:05:39 - DEBUG UnitTestFramework: '#run: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-18 12:05:40 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-18 12:05:40 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-18 12:05:42 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-18 12:05:42 - DEBUG UnitTestFramework: '#setup: 'can get the network status before starting''

2017-07-18 12:05:44 - DEBUG UnitTestFramework: '#setup ok: 'can get the network status before starting''

2017-07-18 12:05:44 - DEBUG UnitTestFramework: '#run: 'can get the network status before starting''

2017-07-18 12:05:47 - DEBUG UnitTestFramework: '#run ok: 'can get the network status before starting''

2017-07-18 12:05:47 - DEBUG UnitTestFramework: '#teardown: 'can get the network status before starting''

2017-07-18 12:05:48 - DEBUG UnitTestFramework: '#teardown ok: 'can get the network status before starting''

2017-07-18 12:05:48 - DEBUG UnitTestFramework: '#setup: 'error returned with bad router''

2017-07-18 12:05:51 - DEBUG UnitTestFramework: '#setup ok: 'error returned with bad router''

2017-07-18 12:05:51 - DEBUG UnitTestFramework: '#run: 'error returned with bad router''

2017-07-18 12:05:52 - DEBUG UnitTestFramework: '#run ok: 'error returned with bad router''

2017-07-18 12:05:52 - DEBUG UnitTestFramework: '#teardown: 'error returned with bad router''

2017-07-18 12:05:55 - DEBUG UnitTestFramework: '#teardown ok: 'error returned with bad router''

2017-07-18 12:05:55 - DEBUG UnitTestFramework: '#setup: 'all services are started when we call start''

2017-07-18 12:05:57 - DEBUG UnitTestFramework: '#setup ok: 'all services are started when we call start''

2017-07-18 12:05:57 - DEBUG UnitTestFramework: '#run: 'all services are started when we call start''

2017-07-18 12:06:00 - DEBUG UnitTestFramework: '#run ok: 'all services are started when we call start''

2017-07-18 12:06:00 - DEBUG UnitTestFramework: '#teardown: 'all services are started when we call start''

2017-07-18 12:06:01 - DEBUG UnitTestFramework: '#teardown ok: 'all services are started when we call start''

2017-07-18 12:06:01 - DEBUG UnitTestFramework: '#setup: 'TCP Servers Manager should be null when we call start on iOS''

2017-07-18 12:06:02 - DEBUG UnitTestFramework: '#setup ok: 'TCP Servers Manager should be null when we call start on iOS''

2017-07-18 12:06:02 - DEBUG UnitTestFramework: '#run: 'TCP Servers Manager should be null when we call start on iOS''

2017-07-18 12:06:02 - INFO Socket: 'run skipped, test: 'TCP Servers Manager should be null when we call start on iOS', event: 'run_TCP Servers Manager should be null when we call start on iOS''

2017-07-18 12:06:04 - INFO Socket: 'run skipped, test: 'TCP Servers Manager should be null when we call start on iOS', event: 'run_TCP Servers Manager should be null when we call start on iOS''

2017-07-18 12:06:04 - INFO Socket: 'run skipped, test: 'TCP Servers Manager should be null when we call start on iOS', event: 'run_TCP Servers Manager should be null when we call start on iOS''

2017-07-18 12:06:04 - DEBUG UnitTestFramework: '#run ok: 'TCP Servers Manager should be null when we call start on iOS''

2017-07-18 12:06:04 - DEBUG UnitTestFramework: '#teardown: 'TCP Servers Manager should be null when we call start on iOS''

2017-07-18 12:06:05 - DEBUG UnitTestFramework: '#teardown ok: 'TCP Servers Manager should be null when we call start on iOS''

2017-07-18 12:06:05 - DEBUG UnitTestFramework: '#setup: 'all services are stopped when we call stop''

2017-07-18 12:06:07 - DEBUG UnitTestFramework: '#setup ok: 'all services are stopped when we call stop''

2017-07-18 12:06:07 - DEBUG UnitTestFramework: '#run: 'all services are stopped when we call stop''

2017-07-18 12:06:12 - DEBUG UnitTestFramework: '#run ok: 'all services are stopped when we call stop''

2017-07-18 12:06:12 - DEBUG UnitTestFramework: '#teardown: 'all services are stopped when we call stop''

2017-07-18 12:06:14 - DEBUG UnitTestFramework: '#teardown ok: 'all services are stopped when we call stop''

2017-07-18 12:06:14 - DEBUG UnitTestFramework: '#setup: 'make sure terminateConnection is properly hooked up''

2017-07-18 12:06:15 - DEBUG UnitTestFramework: '#setup ok: 'make sure terminateConnection is properly hooked up''

2017-07-18 12:06:15 - DEBUG UnitTestFramework: '#run: 'make sure terminateConnection is properly hooked up''

2017-07-18 12:06:18 - DEBUG UnitTestFramework: '#run ok: 'make sure terminateConnection is properly hooked up''

2017-07-18 12:06:18 - DEBUG UnitTestFramework: '#teardown: 'make sure terminateConnection is properly hooked up''

2017-07-18 12:06:18 - DEBUG UnitTestFramework: '#teardown ok: 'make sure terminateConnection is properly hooked up''

2017-07-18 12:06:18 - DEBUG UnitTestFramework: '#setup: 'make sure terminateConnection is return error if we get called on iOS''

2017-07-18 12:06:18 - DEBUG UnitTestFramework: '#setup ok: 'make sure terminateConnection is return error if we get called on iOS''

2017-07-18 12:06:18 - DEBUG UnitTestFramework: '#run: 'make sure terminateConnection is return error if we get called on iOS''

2017-07-18 12:06:18 - INFO Socket: 'run skipped, test: 'make sure terminateConnection is return error if we get called on iOS', event: 'run_make sure terminateConnection is return error if we get called on iOS''

2017-07-18 12:06:18 - INFO Socket: 'run skipped, test: 'make sure terminateConnection is return error if we get called on iOS', event: 'run_make sure terminateConnection is return error if we get called on iOS''

2017-07-18 12:06:18 - INFO Socket: 'run skipped, test: 'make sure terminateConnection is return error if we get called on iOS', event: 'run_make sure terminateConnection is return error if we get called on iOS''

2017-07-18 12:06:18 - DEBUG UnitTestFramework: '#run ok: 'make sure terminateConnection is return error if we get called on iOS''

2017-07-18 12:06:18 - DEBUG UnitTestFramework: '#teardown: 'make sure terminateConnection is return error if we get called on iOS''

2017-07-18 12:06:18 - DEBUG UnitTestFramework: '#teardown ok: 'make sure terminateConnection is return error if we get called on iOS''

2017-07-18 12:06:18 - DEBUG UnitTestFramework: '#setup: 'make sure terminateListener is properly hooked up''

2017-07-18 12:06:18 - DEBUG UnitTestFramework: '#setup ok: 'make sure terminateListener is properly hooked up''

2017-07-18 12:06:18 - DEBUG UnitTestFramework: '#run: 'make sure terminateListener is properly hooked up''

2017-07-18 12:06:18 - DEBUG UnitTestFramework: '#run ok: 'make sure terminateListener is properly hooked up''

2017-07-18 12:06:18 - DEBUG UnitTestFramework: '#teardown: 'make sure terminateListener is properly hooked up''

2017-07-18 12:06:18 - DEBUG UnitTestFramework: '#teardown ok: 'make sure terminateListener is properly hooked up''

2017-07-18 12:06:18 - DEBUG UnitTestFramework: '#setup: 'make sure terminateListener is return error if we get called on iOS''

2017-07-18 12:06:18 - DEBUG UnitTestFramework: '#setup ok: 'make sure terminateListener is return error if we get called on iOS''

2017-07-18 12:06:18 - DEBUG UnitTestFramework: '#run: 'make sure terminateListener is return error if we get called on iOS''

2017-07-18 12:06:18 - INFO Socket: 'run skipped, test: 'make sure terminateListener is return error if we get called on iOS', event: 'run_make sure terminateListener is return error if we get called on iOS''

2017-07-18 12:06:18 - INFO Socket: 'run skipped, test: 'make sure terminateListener is return error if we get called on iOS', event: 'run_make sure terminateListener is return error if we get called on iOS''

2017-07-18 12:06:18 - INFO Socket: 'run skipped, test: 'make sure terminateListener is return error if we get called on iOS', event: 'run_make sure terminateListener is return error if we get called on iOS''

2017-07-18 12:06:18 - DEBUG UnitTestFramework: '#run ok: 'make sure terminateListener is return error if we get called on iOS''

2017-07-18 12:06:18 - DEBUG UnitTestFramework: '#teardown: 'make sure terminateListener is return error if we get called on iOS''

2017-07-18 12:06:19 - DEBUG UnitTestFramework: '#teardown ok: 'make sure terminateListener is return error if we get called on iOS''

2017-07-18 12:06:19 - DEBUG UnitTestFramework: '#setup: 'make sure we actually call kill connections properly''

2017-07-18 12:06:19 - DEBUG UnitTestFramework: '#setup ok: 'make sure we actually call kill connections properly''

2017-07-18 12:06:19 - DEBUG UnitTestFramework: '#run: 'make sure we actually call kill connections properly''

2017-07-18 12:06:19 - DEBUG UnitTestFramework: '#run ok: 'make sure we actually call kill connections properly''

2017-07-18 12:06:19 - DEBUG UnitTestFramework: '#teardown: 'make sure we actually call kill connections properly''

2017-07-18 12:06:19 - DEBUG UnitTestFramework: '#teardown ok: 'make sure we actually call kill connections properly''

2017-07-18 12:06:19 - DEBUG UnitTestFramework: '#setup: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-07-18 12:06:19 - DEBUG UnitTestFramework: '#setup ok: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-07-18 12:06:19 - DEBUG UnitTestFramework: '#run: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-07-18 12:06:19 - DEBUG UnitTestFramework: '#run ok: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-07-18 12:06:19 - DEBUG UnitTestFramework: '#teardown: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-07-18 12:06:19 - DEBUG UnitTestFramework: '#teardown ok: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-07-18 12:06:19 - DEBUG UnitTestFramework: '#setup: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-07-18 12:06:19 - DEBUG UnitTestFramework: '#setup ok: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-07-18 12:06:19 - DEBUG UnitTestFramework: '#run: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-07-18 12:06:19 - DEBUG UnitTestFramework: '#run ok: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-07-18 12:06:19 - DEBUG UnitTestFramework: '#teardown: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-07-18 12:06:19 - DEBUG UnitTestFramework: '#teardown ok: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-07-18 12:06:19 - DEBUG UnitTestFramework: '#setup: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-18 12:06:19 - DEBUG UnitTestFramework: '#setup ok: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-18 12:06:19 - DEBUG UnitTestFramework: '#run: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-18 12:06:19 - INFO Socket: 'run skipped, test: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection', event: 'run_We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-18 12:06:19 - INFO Socket: 'run skipped, test: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection', event: 'run_We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-18 12:06:19 - INFO Socket: 'run skipped, test: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection', event: 'run_We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-18 12:06:19 - DEBUG UnitTestFramework: '#run ok: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-18 12:06:19 - DEBUG UnitTestFramework: '#teardown: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-18 12:06:19 - DEBUG UnitTestFramework: '#teardown ok: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-18 12:06:19 - DEBUG UnitTestFramework: '#setup: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-18 12:06:19 - DEBUG UnitTestFramework: '#setup ok: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-18 12:06:19 - DEBUG UnitTestFramework: '#run: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-18 12:06:19 - INFO Socket: 'run skipped, test: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection', event: 'run_We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-18 12:06:19 - INFO Socket: 'run skipped, test: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection', event: 'run_We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-18 12:06:19 - INFO Socket: 'run skipped, test: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection', event: 'run_We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-18 12:06:19 - DEBUG UnitTestFramework: '#run ok: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-18 12:06:19 - DEBUG UnitTestFramework: '#teardown: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-18 12:06:19 - DEBUG UnitTestFramework: '#teardown ok: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-18 12:06:19 - DEBUG UnitTestFramework: '#setup: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved''

2017-07-18 12:06:19 - DEBUG UnitTestFramework: '#setup ok: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved''

2017-07-18 12:06:19 - DEBUG UnitTestFramework: '#run: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved''

2017-07-18 12:06:22 - DEBUG UnitTestFramework: '#run ok: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved''

2017-07-18 12:06:22 - DEBUG UnitTestFramework: '#teardown: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved''

2017-07-18 12:06:25 - DEBUG UnitTestFramework: '#teardown ok: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved''

2017-07-18 12:06:25 - DEBUG UnitTestFramework: '#setup: 'make sure bad PSK connections fail''

2017-07-18 12:06:27 - DEBUG UnitTestFramework: '#setup ok: 'make sure bad PSK connections fail''

2017-07-18 12:06:27 - DEBUG UnitTestFramework: '#run: 'make sure bad PSK connections fail''

2017-07-18 12:06:28 - INFO Socket: 'run skipped, test: 'make sure bad PSK connections fail', event: 'run_make sure bad PSK connections fail''

2017-07-18 12:06:29 - INFO Socket: 'run skipped, test: 'make sure bad PSK connections fail', event: 'run_make sure bad PSK connections fail''

2017-07-18 12:06:30 - INFO Socket: 'run skipped, test: 'make sure bad PSK connections fail', event: 'run_make sure bad PSK connections fail''

2017-07-18 12:06:30 - DEBUG UnitTestFramework: '#run ok: 'make sure bad PSK connections fail''

2017-07-18 12:06:30 - DEBUG UnitTestFramework: '#teardown: 'make sure bad PSK connections fail''

2017-07-18 12:06:32 - DEBUG UnitTestFramework: '#teardown ok: 'make sure bad PSK connections fail''

2017-07-18 12:06:32 - DEBUG UnitTestFramework: '#setup: 'peer changes handled from a queue''

2017-07-18 12:06:34 - DEBUG UnitTestFramework: '#setup ok: 'peer changes handled from a queue''

2017-07-18 12:06:34 - DEBUG UnitTestFramework: '#run: 'peer changes handled from a queue''

2017-07-18 12:06:34 - INFO Socket: 'run skipped, test: 'peer changes handled from a queue', event: 'run_peer changes handled from a queue''

2017-07-18 12:06:34 - INFO Socket: 'run skipped, test: 'peer changes handled from a queue', event: 'run_peer changes handled from a queue''

2017-07-18 12:06:35 - INFO Socket: 'run skipped, test: 'peer changes handled from a queue', event: 'run_peer changes handled from a queue''

2017-07-18 12:06:35 - DEBUG UnitTestFramework: '#run ok: 'peer changes handled from a queue''

2017-07-18 12:06:35 - DEBUG UnitTestFramework: '#teardown: 'peer changes handled from a queue''

2017-07-18 12:06:37 - DEBUG UnitTestFramework: '#teardown ok: 'peer changes handled from a queue''

2017-07-18 12:06:37 - DEBUG UnitTestFramework: '#setup: 'relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-18 12:06:38 - DEBUG UnitTestFramework: '#setup ok: 'relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-18 12:06:38 - DEBUG UnitTestFramework: '#run: 'relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-18 12:06:38 - INFO Socket: 'run skipped, test: 'relaying discoveryAdvertisingStateUpdateNonTCP', event: 'run_relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-18 12:06:39 - INFO Socket: 'run skipped, test: 'relaying discoveryAdvertisingStateUpdateNonTCP', event: 'run_relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-18 12:06:41 - INFO Socket: 'run skipped, test: 'relaying discoveryAdvertisingStateUpdateNonTCP', event: 'run_relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-18 12:06:41 - DEBUG UnitTestFramework: '#run ok: 'relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-18 12:06:41 - DEBUG UnitTestFramework: '#teardown: 'relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-18 12:06:41 - DEBUG UnitTestFramework: '#teardown ok: 'relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-18 12:06:41 - DEBUG UnitTestFramework: '#setup: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-18 12:06:45 - DEBUG UnitTestFramework: '#setup ok: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-18 12:06:45 - DEBUG UnitTestFramework: '#run: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-18 12:06:45 - INFO Socket: 'run skipped, test: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received', event: 'run_thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-18 12:06:47 - INFO Socket: 'run skipped, test: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received', event: 'run_thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-18 12:06:47 - INFO Socket: 'run skipped, test: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received', event: 'run_thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-18 12:06:47 - DEBUG UnitTestFramework: '#run ok: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-18 12:06:47 - DEBUG UnitTestFramework: '#teardown: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-18 12:06:48 - DEBUG UnitTestFramework: '#teardown ok: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-18 12:06:48 - DEBUG UnitTestFramework: '#setup: 'we successfully receive and replay discoveryAdvertisingStateUpdate''

2017-07-18 12:06:50 - DEBUG UnitTestFramework: '#setup ok: 'we successfully receive and replay discoveryAdvertisingStateUpdate''

2017-07-18 12:06:50 - DEBUG UnitTestFramework: '#run: 'we successfully receive and replay discoveryAdvertisingStateUpdate''

2017-07-18 12:06:55 - DEBUG UnitTestFramework: '#run ok: 'we successfully receive and replay discoveryAdvertisingStateUpdate''

2017-07-18 12:06:55 - DEBUG UnitTestFramework: '#teardown: 'we successfully receive and replay discoveryAdvertisingStateUpdate''

2017-07-18 12:06:58 - DEBUG UnitTestFramework: '#teardown ok: 'we successfully receive and replay discoveryAdvertisingStateUpdate''

2017-07-18 12:06:58 - DEBUG UnitTestFramework: '#setup: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-07-18 12:07:00 - DEBUG UnitTestFramework: '#setup ok: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-07-18 12:07:00 - DEBUG UnitTestFramework: '#run: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-07-18 12:07:00 - INFO Socket: 'run skipped, test: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS', event: 'run_nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-07-18 12:07:00 - INFO Socket: 'run skipped, test: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS', event: 'run_nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-07-18 12:07:01 - INFO Socket: 'run skipped, test: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS', event: 'run_nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-07-18 12:07:01 - DEBUG UnitTestFramework: '#run ok: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-07-18 12:07:01 - DEBUG UnitTestFramework: '#teardown: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-07-18 12:07:03 - DEBUG UnitTestFramework: '#teardown ok: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-07-18 12:07:03 - DEBUG UnitTestFramework: '#setup: 'can do HTTP requests between peers''

2017-07-18 12:07:06 - DEBUG UnitTestFramework: '#setup ok: 'can do HTTP requests between peers''

2017-07-18 12:07:06 - DEBUG UnitTestFramework: '#run: 'can do HTTP requests between peers''

2017-07-18 12:07:13 - DEBUG UnitTestFramework: '#run ok: 'can do HTTP requests between peers''

2017-07-18 12:07:13 - DEBUG UnitTestFramework: '#teardown: 'can do HTTP requests between peers''

2017-07-18 12:07:15 - DEBUG UnitTestFramework: '#teardown ok: 'can do HTTP requests between peers''

2017-07-18 12:07:15 - DEBUG UnitTestFramework: '#setup: 'can still do HTTP requests between peers with coordinator''

2017-07-18 12:07:17 - DEBUG UnitTestFramework: '#setup ok: 'can still do HTTP requests between peers with coordinator''

2017-07-18 12:07:17 - DEBUG UnitTestFramework: '#run: 'can still do HTTP requests between peers with coordinator''

2017-07-18 12:07:17 - INFO Socket: 'run skipped, test: 'can still do HTTP requests between peers with coordinator', event: 'run_can still do HTTP requests between peers with coordinator''

2017-07-18 12:07:17 - INFO Socket: 'run skipped, test: 'can still do HTTP requests between peers with coordinator', event: 'run_can still do HTTP requests between peers with coordinator''

2017-07-18 12:07:19 - INFO Socket: 'run skipped, test: 'can still do HTTP requests between peers with coordinator', event: 'run_can still do HTTP requests between peers with coordinator''

2017-07-18 12:07:19 - DEBUG UnitTestFramework: '#run ok: 'can still do HTTP requests between peers with coordinator''

2017-07-18 12:07:19 - DEBUG UnitTestFramework: '#teardown: 'can still do HTTP requests between peers with coordinator''

2017-07-18 12:07:21 - DEBUG UnitTestFramework: '#teardown ok: 'can still do HTTP requests between peers with coordinator''

2017-07-18 12:07:21 - DEBUG UnitTestFramework: '#setup: 'calls correct starts when network changes''

2017-07-18 12:07:23 - DEBUG UnitTestFramework: '#setup ok: 'calls correct starts when network changes''

2017-07-18 12:07:23 - DEBUG UnitTestFramework: '#run: 'calls correct starts when network changes''

2017-07-18 12:10:23 - ERROR UnitTestFramework: '#run failed: 'calls correct starts when network changes', error: 'TimeoutError: timeout exceeded, event: 'run_calls correct starts when network changes_finished', test: 'calls correct starts when network changes'', stack: 'TimeoutError: timeout exceeded, event: 'run_calls correct starts when network changes_finished', test: 'calls correct starts when network changes'
    at afterTimeout (/home/pi/Test/server_113351851f433a54/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_113351851f433a54/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-07-18 12:10:23 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'android', error: 'TimeoutError: timeout exceeded, event: 'run_calls correct starts when network changes_finished', test: 'calls correct starts when network changes'', stack: 'TimeoutError: timeout exceeded, event: 'run_calls correct starts when network changes_finished', test: 'calls correct starts when network changes'
    at afterTimeout (/home/pi/Test/server_113351851f433a54/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_113351851f433a54/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-07-18 12:10:27 - DEBUG TestServer: 'completed'

2017-07-18 12:10:27 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-07-18 12:10:27 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''

2017-07-18 12:10:27 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/113351851f433a54_CI_sanity_check_jareksl/thali01_samsung-SM-G935F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/113351851f433a54_CI_sanity_check_jareksl/thali03_samsung-SM-G930F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/113351851f433a54_CI_sanity_check_jareksl/thali04_samsung-SM-G930F.md)





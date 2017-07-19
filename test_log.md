#### Test 113351851018c210 Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2017-07-19 09:12:39 - INFO HttpServer: 'listening on *:3000'

2017-07-19 09:14:17 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'ca12863e-4673-47b1-9cb5-e0167f946322', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-19 09:14:17 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-07-19 09:14:30 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: 'b11af97e-e2e2-49d8-81c0-0c74b506fa70', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-19 09:14:30 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-07-19 09:15:47 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'c2b65844-e9a0-4175-a109-d024e9bf992e', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-19 09:15:47 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-07-19 09:15:47 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-07-19 09:15:47 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-07-19 09:15:47 - DEBUG UnitTestFramework: 'scheduling tests'

2017-07-19 09:15:49 - DEBUG UnitTestFramework: 'tests scheduled'

2017-07-19 09:15:49 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-07-19 09:15:51 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-07-19 09:15:51 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-07-19 09:15:53 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-07-19 09:15:53 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-07-19 09:15:54 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-07-19 09:15:54 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-07-19 09:15:56 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-07-19 09:15:56 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-07-19 09:15:57 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-07-19 09:15:57 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-07-19 09:16:00 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-07-19 09:16:00 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-19 09:16:02 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-19 09:16:02 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-19 09:16:03 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-19 09:16:03 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-19 09:16:06 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-19 09:16:06 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-19 09:16:08 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-19 09:16:08 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-19 09:16:09 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-19 09:16:09 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-19 09:16:12 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-19 09:16:12 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-07-19 09:16:13 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-19 09:16:13 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-07-19 09:16:13 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-19 09:16:15 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-19 09:16:16 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-19 09:16:16 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-19 09:16:16 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-07-19 09:16:18 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-19 09:16:18 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-19 09:16:19 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-19 09:16:19 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-19 09:16:19 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-19 09:16:21 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-19 09:16:21 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-19 09:16:21 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-19 09:16:21 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-19 09:16:22 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-19 09:16:22 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-19 09:16:24 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-19 09:16:24 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-19 09:16:24 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-19 09:16:25 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-19 09:16:25 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-19 09:16:25 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-19 09:16:25 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-19 09:16:28 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-19 09:16:28 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-19 09:16:30 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-19 09:16:30 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-19 09:16:30 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-19 09:16:30 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-19 09:16:31 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-19 09:16:31 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-19 09:16:31 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-19 09:16:33 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-19 09:16:33 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-07-19 09:16:36 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-07-19 09:16:36 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-07-19 09:16:38 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-07-19 09:16:38 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-07-19 09:16:40 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-07-19 09:16:40 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-07-19 09:16:42 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-07-19 09:16:42 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-07-19 09:16:46 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-07-19 09:16:46 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-07-19 09:16:49 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-07-19 09:16:49 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-07-19 09:16:49 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-07-19 09:16:49 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-07-19 09:16:52 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-07-19 09:16:52 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-07-19 09:16:52 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-07-19 09:16:52 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-07-19 09:16:52 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-07-19 09:16:52 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-07-19 09:16:52 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-07-19 09:16:52 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-07-19 09:16:52 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-07-19 09:16:52 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-07-19 09:16:52 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-07-19 09:16:52 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-07-19 09:16:52 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-07-19 09:16:52 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-07-19 09:16:52 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-07-19 09:16:52 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-07-19 09:16:53 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-07-19 09:16:53 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-07-19 09:16:53 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-07-19 09:16:53 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-07-19 09:16:53 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-07-19 09:16:53 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-07-19 09:16:53 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-07-19 09:16:53 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-07-19 09:16:53 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-07-19 09:16:53 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-07-19 09:16:53 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-07-19 09:16:53 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-07-19 09:16:53 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-07-19 09:16:53 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-07-19 09:16:53 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-07-19 09:16:53 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-07-19 09:16:53 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-07-19 09:16:53 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-07-19 09:16:53 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-07-19 09:16:53 - DEBUG UnitTestFramework: '#run: 'basic''

2017-07-19 09:16:53 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-07-19 09:16:53 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-07-19 09:16:53 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-07-19 09:16:53 - DEBUG UnitTestFramework: '#setup: 'another''

2017-07-19 09:16:53 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-07-19 09:16:53 - DEBUG UnitTestFramework: '#run: 'another''

2017-07-19 09:16:53 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-07-19 09:16:53 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-07-19 09:16:53 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-07-19 09:16:53 - DEBUG UnitTestFramework: '#setup: 'skip''

2017-07-19 09:16:53 - DEBUG UnitTestFramework: '#setup ok: 'skip''

2017-07-19 09:16:53 - DEBUG UnitTestFramework: '#run: 'skip''

2017-07-19 09:16:53 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-07-19 09:16:53 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-07-19 09:16:53 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-07-19 09:16:53 - DEBUG UnitTestFramework: '#run ok: 'skip''

2017-07-19 09:16:53 - DEBUG UnitTestFramework: '#teardown: 'skip''

2017-07-19 09:16:53 - DEBUG UnitTestFramework: '#teardown ok: 'skip''

2017-07-19 09:16:53 - DEBUG UnitTestFramework: '#setup: 'another skip''

2017-07-19 09:16:53 - DEBUG UnitTestFramework: '#setup ok: 'another skip''

2017-07-19 09:16:53 - DEBUG UnitTestFramework: '#run: 'another skip''

2017-07-19 09:16:53 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-07-19 09:16:53 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-07-19 09:16:53 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-07-19 09:16:53 - DEBUG UnitTestFramework: '#run ok: 'another skip''

2017-07-19 09:16:53 - DEBUG UnitTestFramework: '#teardown: 'another skip''

2017-07-19 09:16:53 - DEBUG UnitTestFramework: '#teardown ok: 'another skip''

2017-07-19 09:16:53 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox spy''

2017-07-19 09:16:54 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox spy''

2017-07-19 09:16:54 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox spy''

2017-07-19 09:16:54 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox spy''

2017-07-19 09:16:54 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox spy''

2017-07-19 09:16:54 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox spy''

2017-07-19 09:16:54 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub''

2017-07-19 09:16:54 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub''

2017-07-19 09:16:54 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub''

2017-07-19 09:16:54 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub''

2017-07-19 09:16:54 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub''

2017-07-19 09:16:54 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub''

2017-07-19 09:16:54 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub override''

2017-07-19 09:16:54 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub override''

2017-07-19 09:16:54 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub override''

2017-07-19 09:16:54 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub override''

2017-07-19 09:16:54 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub override''

2017-07-19 09:16:54 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub override''

2017-07-19 09:16:54 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox mock''

2017-07-19 09:16:54 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox mock''

2017-07-19 09:16:54 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox mock''

2017-07-19 09:16:54 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox mock''

2017-07-19 09:16:54 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox mock''

2017-07-19 09:16:54 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox mock''

2017-07-19 09:16:54 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox restore after test end''

2017-07-19 09:16:54 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox restore after test end''

2017-07-19 09:16:54 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox restore after test end''

2017-07-19 09:16:54 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox restore after test end''

2017-07-19 09:16:54 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox restore after test end''

2017-07-19 09:16:54 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox restore after test end''

2017-07-19 09:16:54 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-07-19 09:16:54 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-07-19 09:16:54 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-07-19 09:16:54 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-07-19 09:16:54 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-07-19 09:16:54 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-07-19 09:16:54 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-07-19 09:16:54 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-07-19 09:16:55 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-07-19 09:16:55 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-07-19 09:16:55 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-07-19 09:16:55 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-07-19 09:16:55 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-07-19 09:16:55 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-07-19 09:16:55 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-07-19 09:16:55 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-07-19 09:16:55 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-07-19 09:16:55 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-07-19 09:16:55 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-07-19 09:16:55 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-07-19 09:16:55 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-07-19 09:16:55 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-07-19 09:16:55 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-07-19 09:16:55 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-07-19 09:16:55 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-07-19 09:16:55 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-07-19 09:16:55 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-07-19 09:16:56 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-07-19 09:16:56 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-07-19 09:16:57 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-07-19 09:16:57 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-19 09:16:57 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-19 09:16:57 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-19 09:16:57 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-19 09:16:57 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-19 09:16:58 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-19 09:16:58 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-19 09:16:58 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-19 09:16:58 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-19 09:16:58 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-19 09:16:58 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-19 09:16:58 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-19 09:16:58 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-19 09:16:58 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-19 09:16:58 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-19 09:16:59 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-19 09:16:59 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-19 09:16:59 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-19 09:16:59 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-19 09:16:59 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-19 09:16:59 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-19 09:17:00 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-19 09:17:00 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-19 09:17:02 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-19 09:17:02 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-19 09:17:03 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-19 09:17:03 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-19 09:17:06 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-19 09:17:06 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-19 09:17:08 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-19 09:17:08 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-07-19 09:17:09 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-07-19 09:17:09 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-07-19 09:17:15 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-07-19 09:17:15 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-07-19 09:17:17 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-07-19 09:17:17 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-07-19 09:17:19 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-07-19 09:17:19 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-07-19 09:17:28 - DEBUG UnitTestFramework: '#run ok: 'Can connect to a remote peer''

2017-07-19 09:17:28 - DEBUG UnitTestFramework: '#teardown: 'Can connect to a remote peer''

2017-07-19 09:17:31 - DEBUG UnitTestFramework: '#teardown ok: 'Can connect to a remote peer''

2017-07-19 09:17:31 - DEBUG UnitTestFramework: '#setup: 'Can shift data''

2017-07-19 09:17:32 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data''

2017-07-19 09:17:32 - DEBUG UnitTestFramework: '#run: 'Can shift data''

2017-07-19 09:17:39 - DEBUG UnitTestFramework: '#run ok: 'Can shift data''

2017-07-19 09:17:39 - DEBUG UnitTestFramework: '#teardown: 'Can shift data''

2017-07-19 09:17:42 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data''

2017-07-19 09:17:42 - DEBUG UnitTestFramework: '#setup: 'Can shift data via parallel connections''

2017-07-19 09:17:43 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data via parallel connections''

2017-07-19 09:17:43 - DEBUG UnitTestFramework: '#run: 'Can shift data via parallel connections''

2017-07-19 09:17:43 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-07-19 09:17:43 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-07-19 09:17:46 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-07-19 09:17:46 - DEBUG UnitTestFramework: '#run ok: 'Can shift data via parallel connections''

2017-07-19 09:17:46 - DEBUG UnitTestFramework: '#teardown: 'Can shift data via parallel connections''

2017-07-19 09:17:49 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data via parallel connections''

2017-07-19 09:17:49 - DEBUG UnitTestFramework: '#setup: 'Can shift data securely''

2017-07-19 09:17:49 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data securely''

2017-07-19 09:17:49 - DEBUG UnitTestFramework: '#run: 'Can shift data securely''

2017-07-19 09:17:58 - DEBUG UnitTestFramework: '#run ok: 'Can shift data securely''

2017-07-19 09:17:58 - DEBUG UnitTestFramework: '#teardown: 'Can shift data securely''

2017-07-19 09:18:00 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data securely''

2017-07-19 09:18:00 - DEBUG UnitTestFramework: '#setup: 'Can shift large amounts of data''

2017-07-19 09:18:02 - DEBUG UnitTestFramework: '#setup ok: 'Can shift large amounts of data''

2017-07-19 09:18:02 - DEBUG UnitTestFramework: '#run: 'Can shift large amounts of data''

2017-07-19 09:18:16 - DEBUG UnitTestFramework: '#run ok: 'Can shift large amounts of data''

2017-07-19 09:18:16 - DEBUG UnitTestFramework: '#teardown: 'Can shift large amounts of data''

2017-07-19 09:18:19 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift large amounts of data''

2017-07-19 09:18:19 - DEBUG UnitTestFramework: '#setup: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-19 09:18:20 - DEBUG UnitTestFramework: '#setup ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-19 09:18:20 - DEBUG UnitTestFramework: '#run: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-19 09:18:28 - DEBUG UnitTestFramework: '#run ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-19 09:18:28 - DEBUG UnitTestFramework: '#teardown: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-19 09:18:30 - DEBUG UnitTestFramework: '#teardown ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-19 09:18:30 - DEBUG UnitTestFramework: '#setup: 'Test updating advertising and parallel data transfer''

2017-07-19 09:18:31 - DEBUG UnitTestFramework: '#setup ok: 'Test updating advertising and parallel data transfer''

2017-07-19 09:18:31 - DEBUG UnitTestFramework: '#run: 'Test updating advertising and parallel data transfer''

2017-07-19 09:18:31 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-07-19 09:18:33 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-07-19 09:18:33 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-07-19 09:18:33 - DEBUG UnitTestFramework: '#run ok: 'Test updating advertising and parallel data transfer''

2017-07-19 09:18:33 - DEBUG UnitTestFramework: '#teardown: 'Test updating advertising and parallel data transfer''

2017-07-19 09:18:34 - DEBUG UnitTestFramework: '#teardown ok: 'Test updating advertising and parallel data transfer''

2017-07-19 09:18:34 - DEBUG UnitTestFramework: '#setup: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-19 09:18:36 - DEBUG UnitTestFramework: '#setup ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-19 09:18:36 - DEBUG UnitTestFramework: '#run: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-19 09:18:41 - DEBUG UnitTestFramework: '#run ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-19 09:18:41 - DEBUG UnitTestFramework: '#teardown: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-19 09:18:43 - DEBUG UnitTestFramework: '#teardown ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-19 09:18:43 - DEBUG UnitTestFramework: '#setup: 'cannot call connect when start listening for advertisements is not active''

2017-07-19 09:18:46 - DEBUG UnitTestFramework: '#setup ok: 'cannot call connect when start listening for advertisements is not active''

2017-07-19 09:18:46 - DEBUG UnitTestFramework: '#run: 'cannot call connect when start listening for advertisements is not active''

2017-07-19 09:18:48 - DEBUG UnitTestFramework: '#run ok: 'cannot call connect when start listening for advertisements is not active''

2017-07-19 09:18:48 - DEBUG UnitTestFramework: '#teardown: 'cannot call connect when start listening for advertisements is not active''

2017-07-19 09:18:48 - DEBUG UnitTestFramework: '#teardown ok: 'cannot call connect when start listening for advertisements is not active''

2017-07-19 09:18:48 - DEBUG UnitTestFramework: '#setup: 'Get error when trying to double connect to a peer on Android''

2017-07-19 09:18:51 - DEBUG UnitTestFramework: '#setup ok: 'Get error when trying to double connect to a peer on Android''

2017-07-19 09:18:51 - DEBUG UnitTestFramework: '#run: 'Get error when trying to double connect to a peer on Android''

2017-07-19 09:18:51 - INFO Socket: 'run skipped, test: 'Get error when trying to double connect to a peer on Android', event: 'run_Get error when trying to double connect to a peer on Android''

2017-07-19 09:18:51 - INFO Socket: 'run skipped, test: 'Get error when trying to double connect to a peer on Android', event: 'run_Get error when trying to double connect to a peer on Android''

2017-07-19 09:18:52 - INFO Socket: 'run skipped, test: 'Get error when trying to double connect to a peer on Android', event: 'run_Get error when trying to double connect to a peer on Android''

2017-07-19 09:18:52 - DEBUG UnitTestFramework: '#run ok: 'Get error when trying to double connect to a peer on Android''

2017-07-19 09:18:52 - DEBUG UnitTestFramework: '#teardown: 'Get error when trying to double connect to a peer on Android''

2017-07-19 09:18:54 - DEBUG UnitTestFramework: '#teardown ok: 'Get error when trying to double connect to a peer on Android''

2017-07-19 09:18:54 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-19 09:18:56 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-19 09:18:56 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-19 09:19:11 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-19 09:19:11 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-19 09:19:17 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-19 09:19:17 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-19 09:19:18 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-19 09:19:18 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-19 09:19:18 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection', event: 'run_#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-19 09:19:19 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection', event: 'run_#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-19 09:19:21 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection', event: 'run_#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-19 09:19:21 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-19 09:19:21 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-19 09:19:22 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-19 09:19:22 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-19 09:19:25 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-19 09:19:25 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-19 09:19:34 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-19 09:19:34 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-19 09:19:39 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-19 09:19:39 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-19 09:19:41 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-19 09:19:41 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-19 09:20:33 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-19 09:20:33 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-19 09:20:36 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-19 09:20:36 - DEBUG UnitTestFramework: '#setup: 'initial peer discovery''

2017-07-19 09:20:39 - DEBUG UnitTestFramework: '#setup ok: 'initial peer discovery''

2017-07-19 09:20:39 - DEBUG UnitTestFramework: '#run: 'initial peer discovery''

2017-07-19 09:20:39 - INFO Socket: 'run skipped, test: 'initial peer discovery', event: 'run_initial peer discovery''

2017-07-19 09:20:39 - INFO Socket: 'run skipped, test: 'initial peer discovery', event: 'run_initial peer discovery''

2017-07-19 09:20:41 - INFO Socket: 'run skipped, test: 'initial peer discovery', event: 'run_initial peer discovery''

2017-07-19 09:20:41 - DEBUG UnitTestFramework: '#run ok: 'initial peer discovery''

2017-07-19 09:20:41 - DEBUG UnitTestFramework: '#teardown: 'initial peer discovery''

2017-07-19 09:20:43 - DEBUG UnitTestFramework: '#teardown ok: 'initial peer discovery''

2017-07-19 09:20:43 - DEBUG UnitTestFramework: '#setup: 'update peer discovery 1''

2017-07-19 09:20:46 - DEBUG UnitTestFramework: '#setup ok: 'update peer discovery 1''

2017-07-19 09:20:46 - DEBUG UnitTestFramework: '#run: 'update peer discovery 1''

2017-07-19 09:20:47 - INFO Socket: 'run skipped, test: 'update peer discovery 1', event: 'run_update peer discovery 1''

2017-07-19 09:20:47 - INFO Socket: 'run skipped, test: 'update peer discovery 1', event: 'run_update peer discovery 1''

2017-07-19 09:20:48 - INFO Socket: 'run skipped, test: 'update peer discovery 1', event: 'run_update peer discovery 1''

2017-07-19 09:20:48 - DEBUG UnitTestFramework: '#run ok: 'update peer discovery 1''

2017-07-19 09:20:48 - DEBUG UnitTestFramework: '#teardown: 'update peer discovery 1''

2017-07-19 09:20:50 - DEBUG UnitTestFramework: '#teardown ok: 'update peer discovery 1''

2017-07-19 09:20:50 - DEBUG UnitTestFramework: '#setup: 'update peer discovery 2''

2017-07-19 09:20:51 - DEBUG UnitTestFramework: '#setup ok: 'update peer discovery 2''

2017-07-19 09:20:51 - DEBUG UnitTestFramework: '#run: 'update peer discovery 2''

2017-07-19 09:20:51 - INFO Socket: 'run skipped, test: 'update peer discovery 2', event: 'run_update peer discovery 2''

2017-07-19 09:20:52 - INFO Socket: 'run skipped, test: 'update peer discovery 2', event: 'run_update peer discovery 2''

2017-07-19 09:20:53 - INFO Socket: 'run skipped, test: 'update peer discovery 2', event: 'run_update peer discovery 2''

2017-07-19 09:20:53 - DEBUG UnitTestFramework: '#run ok: 'update peer discovery 2''

2017-07-19 09:20:53 - DEBUG UnitTestFramework: '#teardown: 'update peer discovery 2''

2017-07-19 09:20:55 - DEBUG UnitTestFramework: '#teardown ok: 'update peer discovery 2''

2017-07-19 09:20:55 - DEBUG UnitTestFramework: '#setup: 'check latest peer discovery''

2017-07-19 09:20:57 - DEBUG UnitTestFramework: '#setup ok: 'check latest peer discovery''

2017-07-19 09:20:57 - DEBUG UnitTestFramework: '#run: 'check latest peer discovery''

2017-07-19 09:20:57 - INFO Socket: 'run skipped, test: 'check latest peer discovery', event: 'run_check latest peer discovery''

2017-07-19 09:20:57 - INFO Socket: 'run skipped, test: 'check latest peer discovery', event: 'run_check latest peer discovery''

2017-07-19 09:20:58 - INFO Socket: 'run skipped, test: 'check latest peer discovery', event: 'run_check latest peer discovery''

2017-07-19 09:20:58 - DEBUG UnitTestFramework: '#run ok: 'check latest peer discovery''

2017-07-19 09:20:58 - DEBUG UnitTestFramework: '#teardown: 'check latest peer discovery''

2017-07-19 09:21:00 - DEBUG UnitTestFramework: '#teardown ok: 'check latest peer discovery''

2017-07-19 09:21:00 - DEBUG UnitTestFramework: '#setup: 'Set up for no peer discovery test''

2017-07-19 09:21:01 - DEBUG UnitTestFramework: '#setup ok: 'Set up for no peer discovery test''

2017-07-19 09:21:01 - DEBUG UnitTestFramework: '#run: 'Set up for no peer discovery test''

2017-07-19 09:21:01 - INFO Socket: 'run skipped, test: 'Set up for no peer discovery test', event: 'run_Set up for no peer discovery test''

2017-07-19 09:21:03 - INFO Socket: 'run skipped, test: 'Set up for no peer discovery test', event: 'run_Set up for no peer discovery test''

2017-07-19 09:21:03 - INFO Socket: 'run skipped, test: 'Set up for no peer discovery test', event: 'run_Set up for no peer discovery test''

2017-07-19 09:21:03 - DEBUG UnitTestFramework: '#run ok: 'Set up for no peer discovery test''

2017-07-19 09:21:03 - DEBUG UnitTestFramework: '#teardown: 'Set up for no peer discovery test''

2017-07-19 09:21:06 - DEBUG UnitTestFramework: '#teardown ok: 'Set up for no peer discovery test''

2017-07-19 09:21:06 - DEBUG UnitTestFramework: '#setup: 'no peer discovery''

2017-07-19 09:21:07 - DEBUG UnitTestFramework: '#setup ok: 'no peer discovery''

2017-07-19 09:21:07 - DEBUG UnitTestFramework: '#run: 'no peer discovery''

2017-07-19 09:21:07 - INFO Socket: 'run skipped, test: 'no peer discovery', event: 'run_no peer discovery''

2017-07-19 09:21:09 - INFO Socket: 'run skipped, test: 'no peer discovery', event: 'run_no peer discovery''

2017-07-19 09:21:09 - INFO Socket: 'run skipped, test: 'no peer discovery', event: 'run_no peer discovery''

2017-07-19 09:21:09 - DEBUG UnitTestFramework: '#run ok: 'no peer discovery''

2017-07-19 09:21:09 - DEBUG UnitTestFramework: '#teardown: 'no peer discovery''

2017-07-19 09:21:12 - DEBUG UnitTestFramework: '#teardown ok: 'no peer discovery''

2017-07-19 09:21:12 - DEBUG UnitTestFramework: '#setup: 'calling createNativeListener directly rejects''

2017-07-19 09:21:16 - DEBUG UnitTestFramework: '#setup ok: 'calling createNativeListener directly rejects''

2017-07-19 09:21:16 - DEBUG UnitTestFramework: '#run: 'calling createNativeListener directly rejects''

2017-07-19 09:21:19 - DEBUG UnitTestFramework: '#run ok: 'calling createNativeListener directly rejects''

2017-07-19 09:21:19 - DEBUG UnitTestFramework: '#teardown: 'calling createNativeListener directly rejects''

2017-07-19 09:21:19 - DEBUG UnitTestFramework: '#teardown ok: 'calling createNativeListener directly rejects''

2017-07-19 09:21:19 - DEBUG UnitTestFramework: '#setup: 'emits incomingConnectionState''

2017-07-19 09:21:22 - DEBUG UnitTestFramework: '#setup ok: 'emits incomingConnectionState''

2017-07-19 09:21:22 - DEBUG UnitTestFramework: '#run: 'emits incomingConnectionState''

2017-07-19 09:21:22 - DEBUG UnitTestFramework: '#run ok: 'emits incomingConnectionState''

2017-07-19 09:21:22 - DEBUG UnitTestFramework: '#teardown: 'emits incomingConnectionState''

2017-07-19 09:21:25 - DEBUG UnitTestFramework: '#teardown ok: 'emits incomingConnectionState''

2017-07-19 09:21:25 - DEBUG UnitTestFramework: '#setup: 'emits routerPortConnectionFailed''

2017-07-19 09:21:26 - DEBUG UnitTestFramework: '#setup ok: 'emits routerPortConnectionFailed''

2017-07-19 09:21:26 - DEBUG UnitTestFramework: '#run: 'emits routerPortConnectionFailed''

2017-07-19 09:21:28 - DEBUG UnitTestFramework: '#run ok: 'emits routerPortConnectionFailed''

2017-07-19 09:21:28 - DEBUG UnitTestFramework: '#teardown: 'emits routerPortConnectionFailed''

2017-07-19 09:21:31 - DEBUG UnitTestFramework: '#teardown ok: 'emits routerPortConnectionFailed''

2017-07-19 09:21:31 - DEBUG UnitTestFramework: '#setup: 'native server connections all up''

2017-07-19 09:21:32 - DEBUG UnitTestFramework: '#setup ok: 'native server connections all up''

2017-07-19 09:21:32 - DEBUG UnitTestFramework: '#run: 'native server connections all up''

2017-07-19 09:21:34 - DEBUG UnitTestFramework: '#run ok: 'native server connections all up''

2017-07-19 09:21:34 - DEBUG UnitTestFramework: '#teardown: 'native server connections all up''

2017-07-19 09:21:35 - DEBUG UnitTestFramework: '#teardown ok: 'native server connections all up''

2017-07-19 09:21:35 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming stream cleans outgoing socket''

2017-07-19 09:21:38 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming stream cleans outgoing socket''

2017-07-19 09:21:38 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming stream cleans outgoing socket''

2017-07-19 09:21:43 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming stream cleans outgoing socket''

2017-07-19 09:21:43 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming stream cleans outgoing socket''

2017-07-19 09:21:46 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming stream cleans outgoing socket''

2017-07-19 09:21:46 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming connection cleans outgoing socket''

2017-07-19 09:21:49 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming connection cleans outgoing socket''

2017-07-19 09:21:49 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming connection cleans outgoing socket''

2017-07-19 09:21:49 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming connection cleans outgoing socket''

2017-07-19 09:21:49 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming connection cleans outgoing socket''

2017-07-19 09:21:52 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming connection cleans outgoing socket''

2017-07-19 09:21:52 - DEBUG UnitTestFramework: '#setup: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-19 09:21:54 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-19 09:21:54 - DEBUG UnitTestFramework: '#run: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-19 09:21:55 - DEBUG UnitTestFramework: '#run ok: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-19 09:21:55 - DEBUG UnitTestFramework: '#teardown: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-19 09:21:58 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-19 09:21:58 - DEBUG UnitTestFramework: '#setup: 'native server - closing the whole server cleans everything up''

2017-07-19 09:22:00 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing the whole server cleans everything up''

2017-07-19 09:22:00 - DEBUG UnitTestFramework: '#run: 'native server - closing the whole server cleans everything up''

2017-07-19 09:22:01 - DEBUG UnitTestFramework: '#run ok: 'native server - closing the whole server cleans everything up''

2017-07-19 09:22:01 - DEBUG UnitTestFramework: '#teardown: 'native server - closing the whole server cleans everything up''

2017-07-19 09:22:03 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing the whole server cleans everything up''

2017-07-19 09:22:03 - DEBUG UnitTestFramework: '#setup: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-19 09:22:06 - DEBUG UnitTestFramework: '#setup ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-19 09:22:06 - DEBUG UnitTestFramework: '#run: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-19 09:22:07 - DEBUG UnitTestFramework: '#run ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-19 09:22:07 - DEBUG UnitTestFramework: '#teardown: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-19 09:22:10 - DEBUG UnitTestFramework: '#teardown ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-19 09:22:10 - DEBUG UnitTestFramework: '#setup: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-19 09:22:13 - DEBUG UnitTestFramework: '#setup ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-19 09:22:13 - DEBUG UnitTestFramework: '#run: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-19 09:22:14 - DEBUG UnitTestFramework: '#run ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-19 09:22:14 - DEBUG UnitTestFramework: '#teardown: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-19 09:22:16 - DEBUG UnitTestFramework: '#teardown ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-19 09:22:16 - DEBUG UnitTestFramework: '#setup: 'native server - timing out the incoming connection cleans everything up''

2017-07-19 09:22:19 - DEBUG UnitTestFramework: '#setup ok: 'native server - timing out the incoming connection cleans everything up''

2017-07-19 09:22:19 - DEBUG UnitTestFramework: '#run: 'native server - timing out the incoming connection cleans everything up''

2017-07-19 09:22:20 - DEBUG UnitTestFramework: '#run ok: 'native server - timing out the incoming connection cleans everything up''

2017-07-19 09:22:20 - DEBUG UnitTestFramework: '#teardown: 'native server - timing out the incoming connection cleans everything up''

2017-07-19 09:22:22 - DEBUG UnitTestFramework: '#teardown ok: 'native server - timing out the incoming connection cleans everything up''

2017-07-19 09:22:22 - DEBUG UnitTestFramework: '#setup: 'can create servers manager''

2017-07-19 09:22:25 - DEBUG UnitTestFramework: '#setup ok: 'can create servers manager''

2017-07-19 09:22:25 - DEBUG UnitTestFramework: '#run: 'can create servers manager''

2017-07-19 09:22:26 - DEBUG UnitTestFramework: '#run ok: 'can create servers manager''

2017-07-19 09:22:26 - DEBUG UnitTestFramework: '#teardown: 'can create servers manager''

2017-07-19 09:22:28 - DEBUG UnitTestFramework: '#teardown ok: 'can create servers manager''

2017-07-19 09:22:28 - DEBUG UnitTestFramework: '#setup: 'calling stop without start causes error''

2017-07-19 09:22:29 - DEBUG UnitTestFramework: '#setup ok: 'calling stop without start causes error''

2017-07-19 09:22:29 - DEBUG UnitTestFramework: '#run: 'calling stop without start causes error''

2017-07-19 09:22:31 - DEBUG UnitTestFramework: '#run ok: 'calling stop without start causes error''

2017-07-19 09:22:31 - DEBUG UnitTestFramework: '#teardown: 'calling stop without start causes error''

2017-07-19 09:22:32 - DEBUG UnitTestFramework: '#teardown ok: 'calling stop without start causes error''

2017-07-19 09:22:32 - DEBUG UnitTestFramework: '#setup: 'can start/stop servers manager''

2017-07-19 09:22:34 - DEBUG UnitTestFramework: '#setup ok: 'can start/stop servers manager''

2017-07-19 09:22:34 - DEBUG UnitTestFramework: '#run: 'can start/stop servers manager''

2017-07-19 09:22:35 - DEBUG UnitTestFramework: '#run ok: 'can start/stop servers manager''

2017-07-19 09:22:35 - DEBUG UnitTestFramework: '#teardown: 'can start/stop servers manager''

2017-07-19 09:22:37 - DEBUG UnitTestFramework: '#teardown ok: 'can start/stop servers manager''

2017-07-19 09:22:37 - DEBUG UnitTestFramework: '#setup: 'starting twice resolves with listening port''

2017-07-19 09:22:40 - DEBUG UnitTestFramework: '#setup ok: 'starting twice resolves with listening port''

2017-07-19 09:22:40 - DEBUG UnitTestFramework: '#run: 'starting twice resolves with listening port''

2017-07-19 09:22:43 - DEBUG UnitTestFramework: '#run ok: 'starting twice resolves with listening port''

2017-07-19 09:22:43 - DEBUG UnitTestFramework: '#teardown: 'starting twice resolves with listening port''

2017-07-19 09:22:46 - DEBUG UnitTestFramework: '#teardown ok: 'starting twice resolves with listening port''

2017-07-19 09:22:46 - DEBUG UnitTestFramework: '#setup: 'terminateIncomingConnection will terminate a connection''

2017-07-19 09:22:49 - DEBUG UnitTestFramework: '#setup ok: 'terminateIncomingConnection will terminate a connection''

2017-07-19 09:22:49 - DEBUG UnitTestFramework: '#run: 'terminateIncomingConnection will terminate a connection''

2017-07-19 09:22:52 - DEBUG UnitTestFramework: '#run ok: 'terminateIncomingConnection will terminate a connection''

2017-07-19 09:22:52 - DEBUG UnitTestFramework: '#teardown: 'terminateIncomingConnection will terminate a connection''

2017-07-19 09:22:54 - DEBUG UnitTestFramework: '#teardown ok: 'terminateIncomingConnection will terminate a connection''

2017-07-19 09:22:54 - DEBUG UnitTestFramework: '#setup: 'terminate an Outgoing connection''

2017-07-19 09:22:55 - DEBUG UnitTestFramework: '#setup ok: 'terminate an Outgoing connection''

2017-07-19 09:22:55 - DEBUG UnitTestFramework: '#run: 'terminate an Outgoing connection''

2017-07-19 09:22:57 - DEBUG UnitTestFramework: '#run ok: 'terminate an Outgoing connection''

2017-07-19 09:22:57 - DEBUG UnitTestFramework: '#teardown: 'terminate an Outgoing connection''

2017-07-19 09:23:00 - DEBUG UnitTestFramework: '#teardown ok: 'terminate an Outgoing connection''

2017-07-19 09:23:00 - DEBUG UnitTestFramework: '#setup: 'Single local http request''

2017-07-19 09:23:02 - DEBUG UnitTestFramework: '#setup ok: 'Single local http request''

2017-07-19 09:23:02 - DEBUG UnitTestFramework: '#run: 'Single local http request''

2017-07-19 09:23:03 - DEBUG UnitTestFramework: '#run ok: 'Single local http request''

2017-07-19 09:23:03 - DEBUG UnitTestFramework: '#teardown: 'Single local http request''

2017-07-19 09:23:05 - DEBUG UnitTestFramework: '#teardown ok: 'Single local http request''

2017-07-19 09:23:05 - DEBUG UnitTestFramework: '#setup: 'Single coordinated request ios native''

2017-07-19 09:23:07 - DEBUG UnitTestFramework: '#setup ok: 'Single coordinated request ios native''

2017-07-19 09:23:07 - DEBUG UnitTestFramework: '#run: 'Single coordinated request ios native''

2017-07-19 09:23:07 - INFO Socket: 'run skipped, test: 'Single coordinated request ios native', event: 'run_Single coordinated request ios native''

2017-07-19 09:23:08 - INFO Socket: 'run skipped, test: 'Single coordinated request ios native', event: 'run_Single coordinated request ios native''

2017-07-19 09:23:09 - INFO Socket: 'run skipped, test: 'Single coordinated request ios native', event: 'run_Single coordinated request ios native''

2017-07-19 09:23:09 - DEBUG UnitTestFramework: '#run ok: 'Single coordinated request ios native''

2017-07-19 09:23:09 - DEBUG UnitTestFramework: '#teardown: 'Single coordinated request ios native''

2017-07-19 09:23:13 - DEBUG UnitTestFramework: '#teardown ok: 'Single coordinated request ios native''

2017-07-19 09:23:13 - DEBUG UnitTestFramework: '#setup: 'Multiple local http requests''

2017-07-19 09:23:16 - DEBUG UnitTestFramework: '#setup ok: 'Multiple local http requests''

2017-07-19 09:23:16 - DEBUG UnitTestFramework: '#run: 'Multiple local http requests''

2017-07-19 09:23:19 - DEBUG UnitTestFramework: '#run ok: 'Multiple local http requests''

2017-07-19 09:23:19 - DEBUG UnitTestFramework: '#teardown: 'Multiple local http requests''

2017-07-19 09:23:21 - DEBUG UnitTestFramework: '#teardown ok: 'Multiple local http requests''

2017-07-19 09:23:21 - DEBUG UnitTestFramework: '#setup: 'Multiple coordinated request ios native''

2017-07-19 09:23:23 - DEBUG UnitTestFramework: '#setup ok: 'Multiple coordinated request ios native''

2017-07-19 09:23:23 - DEBUG UnitTestFramework: '#run: 'Multiple coordinated request ios native''

2017-07-19 09:23:23 - INFO Socket: 'run skipped, test: 'Multiple coordinated request ios native', event: 'run_Multiple coordinated request ios native''

2017-07-19 09:23:24 - INFO Socket: 'run skipped, test: 'Multiple coordinated request ios native', event: 'run_Multiple coordinated request ios native''

2017-07-19 09:23:25 - INFO Socket: 'run skipped, test: 'Multiple coordinated request ios native', event: 'run_Multiple coordinated request ios native''

2017-07-19 09:23:25 - DEBUG UnitTestFramework: '#run ok: 'Multiple coordinated request ios native''

2017-07-19 09:23:25 - DEBUG UnitTestFramework: '#teardown: 'Multiple coordinated request ios native''

2017-07-19 09:23:27 - DEBUG UnitTestFramework: '#teardown ok: 'Multiple coordinated request ios native''

2017-07-19 09:23:27 - DEBUG UnitTestFramework: '#setup: '#startListeningForAdvertisements should fail if start not called''

2017-07-19 09:23:29 - DEBUG UnitTestFramework: '#setup ok: '#startListeningForAdvertisements should fail if start not called''

2017-07-19 09:23:29 - DEBUG UnitTestFramework: '#run: '#startListeningForAdvertisements should fail if start not called''

2017-07-19 09:23:31 - DEBUG UnitTestFramework: '#run ok: '#startListeningForAdvertisements should fail if start not called''

2017-07-19 09:23:31 - DEBUG UnitTestFramework: '#teardown: '#startListeningForAdvertisements should fail if start not called''

2017-07-19 09:23:33 - DEBUG UnitTestFramework: '#teardown ok: '#startListeningForAdvertisements should fail if start not called''

2017-07-19 09:23:33 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-19 09:23:34 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-19 09:23:34 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-19 09:23:37 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-19 09:23:37 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-19 09:23:39 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-19 09:23:39 - DEBUG UnitTestFramework: '#setup: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-19 09:23:40 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-19 09:23:40 - DEBUG UnitTestFramework: '#run: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-19 09:23:43 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-19 09:23:43 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-19 09:23:46 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-19 09:23:46 - DEBUG UnitTestFramework: '#setup: 'should be able to call #startListeningForAdvertisements many times''

2017-07-19 09:23:49 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #startListeningForAdvertisements many times''

2017-07-19 09:23:49 - DEBUG UnitTestFramework: '#run: 'should be able to call #startListeningForAdvertisements many times''

2017-07-19 09:23:52 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #startListeningForAdvertisements many times''

2017-07-19 09:23:52 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #startListeningForAdvertisements many times''

2017-07-19 09:23:54 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #startListeningForAdvertisements many times''

2017-07-19 09:23:54 - DEBUG UnitTestFramework: '#setup: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-19 09:23:56 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-19 09:23:56 - DEBUG UnitTestFramework: '#run: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-19 09:23:58 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-19 09:23:58 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-19 09:24:00 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-19 09:24:00 - DEBUG UnitTestFramework: '#setup: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-19 09:24:03 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-19 09:24:03 - DEBUG UnitTestFramework: '#run: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-19 09:24:04 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-19 09:24:04 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-19 09:24:06 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-19 09:24:06 - DEBUG UnitTestFramework: '#setup: 'can get the network status before starting''

2017-07-19 09:24:08 - DEBUG UnitTestFramework: '#setup ok: 'can get the network status before starting''

2017-07-19 09:24:08 - DEBUG UnitTestFramework: '#run: 'can get the network status before starting''

2017-07-19 09:24:10 - DEBUG UnitTestFramework: '#run ok: 'can get the network status before starting''

2017-07-19 09:24:10 - DEBUG UnitTestFramework: '#teardown: 'can get the network status before starting''

2017-07-19 09:24:13 - DEBUG UnitTestFramework: '#teardown ok: 'can get the network status before starting''

2017-07-19 09:24:13 - DEBUG UnitTestFramework: '#setup: 'error returned with bad router''

2017-07-19 09:24:16 - DEBUG UnitTestFramework: '#setup ok: 'error returned with bad router''

2017-07-19 09:24:16 - DEBUG UnitTestFramework: '#run: 'error returned with bad router''

2017-07-19 09:24:19 - DEBUG UnitTestFramework: '#run ok: 'error returned with bad router''

2017-07-19 09:24:19 - DEBUG UnitTestFramework: '#teardown: 'error returned with bad router''

2017-07-19 09:24:19 - DEBUG UnitTestFramework: '#teardown ok: 'error returned with bad router''

2017-07-19 09:24:19 - DEBUG UnitTestFramework: '#setup: 'all services are started when we call start''

2017-07-19 09:24:19 - DEBUG UnitTestFramework: '#setup ok: 'all services are started when we call start''

2017-07-19 09:24:19 - DEBUG UnitTestFramework: '#run: 'all services are started when we call start''

2017-07-19 09:24:21 - DEBUG UnitTestFramework: '#run ok: 'all services are started when we call start''

2017-07-19 09:24:21 - DEBUG UnitTestFramework: '#teardown: 'all services are started when we call start''

2017-07-19 09:24:24 - DEBUG UnitTestFramework: '#teardown ok: 'all services are started when we call start''

2017-07-19 09:24:24 - DEBUG UnitTestFramework: '#setup: 'TCP Servers Manager should be null when we call start on iOS''

2017-07-19 09:24:26 - DEBUG UnitTestFramework: '#setup ok: 'TCP Servers Manager should be null when we call start on iOS''

2017-07-19 09:24:26 - DEBUG UnitTestFramework: '#run: 'TCP Servers Manager should be null when we call start on iOS''

2017-07-19 09:24:26 - INFO Socket: 'run skipped, test: 'TCP Servers Manager should be null when we call start on iOS', event: 'run_TCP Servers Manager should be null when we call start on iOS''

2017-07-19 09:24:27 - INFO Socket: 'run skipped, test: 'TCP Servers Manager should be null when we call start on iOS', event: 'run_TCP Servers Manager should be null when we call start on iOS''

2017-07-19 09:24:27 - INFO Socket: 'run skipped, test: 'TCP Servers Manager should be null when we call start on iOS', event: 'run_TCP Servers Manager should be null when we call start on iOS''

2017-07-19 09:24:27 - DEBUG UnitTestFramework: '#run ok: 'TCP Servers Manager should be null when we call start on iOS''

2017-07-19 09:24:27 - DEBUG UnitTestFramework: '#teardown: 'TCP Servers Manager should be null when we call start on iOS''

2017-07-19 09:24:30 - DEBUG UnitTestFramework: '#teardown ok: 'TCP Servers Manager should be null when we call start on iOS''

2017-07-19 09:24:30 - DEBUG UnitTestFramework: '#setup: 'all services are stopped when we call stop''

2017-07-19 09:24:31 - DEBUG UnitTestFramework: '#setup ok: 'all services are stopped when we call stop''

2017-07-19 09:24:31 - DEBUG UnitTestFramework: '#run: 'all services are stopped when we call stop''

2017-07-19 09:24:35 - DEBUG UnitTestFramework: '#run ok: 'all services are stopped when we call stop''

2017-07-19 09:24:35 - DEBUG UnitTestFramework: '#teardown: 'all services are stopped when we call stop''

2017-07-19 09:24:37 - DEBUG UnitTestFramework: '#teardown ok: 'all services are stopped when we call stop''

2017-07-19 09:24:37 - DEBUG UnitTestFramework: '#setup: 'make sure terminateConnection is properly hooked up''

2017-07-19 09:24:39 - DEBUG UnitTestFramework: '#setup ok: 'make sure terminateConnection is properly hooked up''

2017-07-19 09:24:39 - DEBUG UnitTestFramework: '#run: 'make sure terminateConnection is properly hooked up''

2017-07-19 09:24:43 - DEBUG UnitTestFramework: '#run ok: 'make sure terminateConnection is properly hooked up''

2017-07-19 09:24:43 - DEBUG UnitTestFramework: '#teardown: 'make sure terminateConnection is properly hooked up''

2017-07-19 09:24:46 - DEBUG UnitTestFramework: '#teardown ok: 'make sure terminateConnection is properly hooked up''

2017-07-19 09:24:46 - DEBUG UnitTestFramework: '#setup: 'make sure terminateConnection is return error if we get called on iOS''

2017-07-19 09:24:49 - DEBUG UnitTestFramework: '#setup ok: 'make sure terminateConnection is return error if we get called on iOS''

2017-07-19 09:24:49 - DEBUG UnitTestFramework: '#run: 'make sure terminateConnection is return error if we get called on iOS''

2017-07-19 09:24:49 - INFO Socket: 'run skipped, test: 'make sure terminateConnection is return error if we get called on iOS', event: 'run_make sure terminateConnection is return error if we get called on iOS''

2017-07-19 09:24:49 - INFO Socket: 'run skipped, test: 'make sure terminateConnection is return error if we get called on iOS', event: 'run_make sure terminateConnection is return error if we get called on iOS''

2017-07-19 09:24:50 - INFO Socket: 'run skipped, test: 'make sure terminateConnection is return error if we get called on iOS', event: 'run_make sure terminateConnection is return error if we get called on iOS''

2017-07-19 09:24:50 - DEBUG UnitTestFramework: '#run ok: 'make sure terminateConnection is return error if we get called on iOS''

2017-07-19 09:24:50 - DEBUG UnitTestFramework: '#teardown: 'make sure terminateConnection is return error if we get called on iOS''

2017-07-19 09:24:52 - DEBUG UnitTestFramework: '#teardown ok: 'make sure terminateConnection is return error if we get called on iOS''

2017-07-19 09:24:52 - DEBUG UnitTestFramework: '#setup: 'make sure terminateListener is properly hooked up''

2017-07-19 09:24:55 - DEBUG UnitTestFramework: '#setup ok: 'make sure terminateListener is properly hooked up''

2017-07-19 09:24:55 - DEBUG UnitTestFramework: '#run: 'make sure terminateListener is properly hooked up''

2017-07-19 09:24:57 - DEBUG UnitTestFramework: '#run ok: 'make sure terminateListener is properly hooked up''

2017-07-19 09:24:57 - DEBUG UnitTestFramework: '#teardown: 'make sure terminateListener is properly hooked up''

2017-07-19 09:24:59 - DEBUG UnitTestFramework: '#teardown ok: 'make sure terminateListener is properly hooked up''

2017-07-19 09:24:59 - DEBUG UnitTestFramework: '#setup: 'make sure terminateListener is return error if we get called on iOS''

2017-07-19 09:25:01 - DEBUG UnitTestFramework: '#setup ok: 'make sure terminateListener is return error if we get called on iOS''

2017-07-19 09:25:01 - DEBUG UnitTestFramework: '#run: 'make sure terminateListener is return error if we get called on iOS''

2017-07-19 09:25:01 - INFO Socket: 'run skipped, test: 'make sure terminateListener is return error if we get called on iOS', event: 'run_make sure terminateListener is return error if we get called on iOS''

2017-07-19 09:25:02 - INFO Socket: 'run skipped, test: 'make sure terminateListener is return error if we get called on iOS', event: 'run_make sure terminateListener is return error if we get called on iOS''

2017-07-19 09:25:03 - INFO Socket: 'run skipped, test: 'make sure terminateListener is return error if we get called on iOS', event: 'run_make sure terminateListener is return error if we get called on iOS''

2017-07-19 09:25:03 - DEBUG UnitTestFramework: '#run ok: 'make sure terminateListener is return error if we get called on iOS''

2017-07-19 09:25:03 - DEBUG UnitTestFramework: '#teardown: 'make sure terminateListener is return error if we get called on iOS''

2017-07-19 09:25:05 - DEBUG UnitTestFramework: '#teardown ok: 'make sure terminateListener is return error if we get called on iOS''

2017-07-19 09:25:05 - DEBUG UnitTestFramework: '#setup: 'make sure we actually call kill connections properly''

2017-07-19 09:25:06 - DEBUG UnitTestFramework: '#setup ok: 'make sure we actually call kill connections properly''

2017-07-19 09:25:06 - DEBUG UnitTestFramework: '#run: 'make sure we actually call kill connections properly''

2017-07-19 09:25:09 - DEBUG UnitTestFramework: '#run ok: 'make sure we actually call kill connections properly''

2017-07-19 09:25:09 - DEBUG UnitTestFramework: '#teardown: 'make sure we actually call kill connections properly''

2017-07-19 09:25:11 - DEBUG UnitTestFramework: '#teardown ok: 'make sure we actually call kill connections properly''

2017-07-19 09:25:11 - DEBUG UnitTestFramework: '#setup: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-07-19 09:25:13 - DEBUG UnitTestFramework: '#setup ok: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-07-19 09:25:13 - DEBUG UnitTestFramework: '#run: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-07-19 09:25:16 - DEBUG UnitTestFramework: '#run ok: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-07-19 09:25:16 - DEBUG UnitTestFramework: '#teardown: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-07-19 09:25:19 - DEBUG UnitTestFramework: '#teardown ok: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-07-19 09:25:19 - DEBUG UnitTestFramework: '#setup: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-07-19 09:25:22 - DEBUG UnitTestFramework: '#setup ok: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-07-19 09:25:22 - DEBUG UnitTestFramework: '#run: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-07-19 09:25:24 - DEBUG UnitTestFramework: '#run ok: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-07-19 09:25:24 - DEBUG UnitTestFramework: '#teardown: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-07-19 09:25:26 - DEBUG UnitTestFramework: '#teardown ok: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-07-19 09:25:26 - DEBUG UnitTestFramework: '#setup: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-19 09:25:29 - DEBUG UnitTestFramework: '#setup ok: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-19 09:25:29 - DEBUG UnitTestFramework: '#run: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-19 09:25:29 - INFO Socket: 'run skipped, test: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection', event: 'run_We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-19 09:25:29 - INFO Socket: 'run skipped, test: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection', event: 'run_We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-19 09:25:30 - INFO Socket: 'run skipped, test: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection', event: 'run_We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-19 09:25:30 - DEBUG UnitTestFramework: '#run ok: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-19 09:25:30 - DEBUG UnitTestFramework: '#teardown: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-19 09:25:32 - DEBUG UnitTestFramework: '#teardown ok: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-19 09:25:32 - DEBUG UnitTestFramework: '#setup: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-19 09:25:34 - DEBUG UnitTestFramework: '#setup ok: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-19 09:25:34 - DEBUG UnitTestFramework: '#run: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-19 09:25:34 - INFO Socket: 'run skipped, test: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection', event: 'run_We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-19 09:25:35 - INFO Socket: 'run skipped, test: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection', event: 'run_We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-19 09:25:36 - INFO Socket: 'run skipped, test: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection', event: 'run_We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-19 09:25:36 - DEBUG UnitTestFramework: '#run ok: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-19 09:25:36 - DEBUG UnitTestFramework: '#teardown: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-19 09:25:38 - DEBUG UnitTestFramework: '#teardown ok: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-19 09:25:38 - DEBUG UnitTestFramework: '#setup: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved''

2017-07-19 09:25:40 - DEBUG UnitTestFramework: '#setup ok: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved''

2017-07-19 09:25:40 - DEBUG UnitTestFramework: '#run: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved''

2017-07-19 09:25:43 - DEBUG UnitTestFramework: '#run ok: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved''

2017-07-19 09:25:43 - DEBUG UnitTestFramework: '#teardown: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved''

2017-07-19 09:25:46 - DEBUG UnitTestFramework: '#teardown ok: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved''

2017-07-19 09:25:46 - DEBUG UnitTestFramework: '#setup: 'make sure bad PSK connections fail''

2017-07-19 09:25:49 - DEBUG UnitTestFramework: '#setup ok: 'make sure bad PSK connections fail''

2017-07-19 09:25:49 - DEBUG UnitTestFramework: '#run: 'make sure bad PSK connections fail''

2017-07-19 09:25:49 - INFO Socket: 'run skipped, test: 'make sure bad PSK connections fail', event: 'run_make sure bad PSK connections fail''

2017-07-19 09:25:49 - INFO Socket: 'run skipped, test: 'make sure bad PSK connections fail', event: 'run_make sure bad PSK connections fail''

2017-07-19 09:25:51 - INFO Socket: 'run skipped, test: 'make sure bad PSK connections fail', event: 'run_make sure bad PSK connections fail''

2017-07-19 09:25:51 - DEBUG UnitTestFramework: '#run ok: 'make sure bad PSK connections fail''

2017-07-19 09:25:51 - DEBUG UnitTestFramework: '#teardown: 'make sure bad PSK connections fail''

2017-07-19 09:25:52 - DEBUG UnitTestFramework: '#teardown ok: 'make sure bad PSK connections fail''

2017-07-19 09:25:52 - DEBUG UnitTestFramework: '#setup: 'peer changes handled from a queue''

2017-07-19 09:25:54 - DEBUG UnitTestFramework: '#setup ok: 'peer changes handled from a queue''

2017-07-19 09:25:54 - DEBUG UnitTestFramework: '#run: 'peer changes handled from a queue''

2017-07-19 09:25:55 - INFO Socket: 'run skipped, test: 'peer changes handled from a queue', event: 'run_peer changes handled from a queue''

2017-07-19 09:25:57 - INFO Socket: 'run skipped, test: 'peer changes handled from a queue', event: 'run_peer changes handled from a queue''

2017-07-19 09:25:57 - INFO Socket: 'run skipped, test: 'peer changes handled from a queue', event: 'run_peer changes handled from a queue''

2017-07-19 09:25:57 - DEBUG UnitTestFramework: '#run ok: 'peer changes handled from a queue''

2017-07-19 09:25:57 - DEBUG UnitTestFramework: '#teardown: 'peer changes handled from a queue''

2017-07-19 09:25:58 - DEBUG UnitTestFramework: '#teardown ok: 'peer changes handled from a queue''

2017-07-19 09:25:58 - DEBUG UnitTestFramework: '#setup: 'relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-19 09:26:00 - DEBUG UnitTestFramework: '#setup ok: 'relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-19 09:26:00 - DEBUG UnitTestFramework: '#run: 'relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-19 09:26:00 - INFO Socket: 'run skipped, test: 'relaying discoveryAdvertisingStateUpdateNonTCP', event: 'run_relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-19 09:26:01 - INFO Socket: 'run skipped, test: 'relaying discoveryAdvertisingStateUpdateNonTCP', event: 'run_relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-19 09:26:02 - INFO Socket: 'run skipped, test: 'relaying discoveryAdvertisingStateUpdateNonTCP', event: 'run_relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-19 09:26:02 - DEBUG UnitTestFramework: '#run ok: 'relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-19 09:26:02 - DEBUG UnitTestFramework: '#teardown: 'relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-19 09:26:04 - DEBUG UnitTestFramework: '#teardown ok: 'relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-19 09:26:04 - DEBUG UnitTestFramework: '#setup: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-19 09:26:05 - DEBUG UnitTestFramework: '#setup ok: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-19 09:26:05 - DEBUG UnitTestFramework: '#run: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-19 09:26:06 - INFO Socket: 'run skipped, test: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received', event: 'run_thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-19 09:26:07 - INFO Socket: 'run skipped, test: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received', event: 'run_thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-19 09:26:08 - INFO Socket: 'run skipped, test: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received', event: 'run_thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-19 09:26:08 - DEBUG UnitTestFramework: '#run ok: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-19 09:26:08 - DEBUG UnitTestFramework: '#teardown: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-19 09:26:10 - DEBUG UnitTestFramework: '#teardown ok: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-19 09:26:10 - DEBUG UnitTestFramework: '#setup: 'we successfully receive and replay discoveryAdvertisingStateUpdate''

2017-07-19 09:26:13 - DEBUG UnitTestFramework: '#setup ok: 'we successfully receive and replay discoveryAdvertisingStateUpdate''

2017-07-19 09:26:13 - DEBUG UnitTestFramework: '#run: 'we successfully receive and replay discoveryAdvertisingStateUpdate''

2017-07-19 09:26:19 - DEBUG UnitTestFramework: '#run ok: 'we successfully receive and replay discoveryAdvertisingStateUpdate''

2017-07-19 09:26:19 - DEBUG UnitTestFramework: '#teardown: 'we successfully receive and replay discoveryAdvertisingStateUpdate''

2017-07-19 09:26:21 - DEBUG UnitTestFramework: '#teardown ok: 'we successfully receive and replay discoveryAdvertisingStateUpdate''

2017-07-19 09:26:21 - DEBUG UnitTestFramework: '#setup: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-07-19 09:26:21 - DEBUG UnitTestFramework: '#setup ok: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-07-19 09:26:21 - DEBUG UnitTestFramework: '#run: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-07-19 09:26:21 - INFO Socket: 'run skipped, test: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS', event: 'run_nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-07-19 09:26:24 - INFO Socket: 'run skipped, test: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS', event: 'run_nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-07-19 09:26:24 - INFO Socket: 'run skipped, test: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS', event: 'run_nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-07-19 09:26:24 - DEBUG UnitTestFramework: '#run ok: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-07-19 09:26:24 - DEBUG UnitTestFramework: '#teardown: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-07-19 09:26:24 - DEBUG UnitTestFramework: '#teardown ok: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-07-19 09:26:24 - DEBUG UnitTestFramework: '#setup: 'can do HTTP requests between peers''

2017-07-19 09:26:24 - DEBUG UnitTestFramework: '#setup ok: 'can do HTTP requests between peers''

2017-07-19 09:26:24 - DEBUG UnitTestFramework: '#run: 'can do HTTP requests between peers''

2017-07-19 09:26:24 - INFO Socket: 'run skipped, test: 'can do HTTP requests between peers', event: 'run_can do HTTP requests between peers''

2017-07-19 09:26:24 - INFO Socket: 'run skipped, test: 'can do HTTP requests between peers', event: 'run_can do HTTP requests between peers''

2017-07-19 09:26:24 - INFO Socket: 'run skipped, test: 'can do HTTP requests between peers', event: 'run_can do HTTP requests between peers''

2017-07-19 09:26:24 - DEBUG UnitTestFramework: '#run ok: 'can do HTTP requests between peers''

2017-07-19 09:26:24 - DEBUG UnitTestFramework: '#teardown: 'can do HTTP requests between peers''

2017-07-19 09:26:24 - DEBUG UnitTestFramework: '#teardown ok: 'can do HTTP requests between peers''

2017-07-19 09:26:24 - DEBUG UnitTestFramework: '#setup: 'can still do HTTP requests between peers with coordinator''

2017-07-19 09:26:24 - DEBUG UnitTestFramework: '#setup ok: 'can still do HTTP requests between peers with coordinator''

2017-07-19 09:26:24 - DEBUG UnitTestFramework: '#run: 'can still do HTTP requests between peers with coordinator''

2017-07-19 09:26:24 - INFO Socket: 'run skipped, test: 'can still do HTTP requests between peers with coordinator', event: 'run_can still do HTTP requests between peers with coordinator''

2017-07-19 09:26:24 - INFO Socket: 'run skipped, test: 'can still do HTTP requests between peers with coordinator', event: 'run_can still do HTTP requests between peers with coordinator''

2017-07-19 09:26:24 - INFO Socket: 'run skipped, test: 'can still do HTTP requests between peers with coordinator', event: 'run_can still do HTTP requests between peers with coordinator''

2017-07-19 09:26:24 - DEBUG UnitTestFramework: '#run ok: 'can still do HTTP requests between peers with coordinator''

2017-07-19 09:26:24 - DEBUG UnitTestFramework: '#teardown: 'can still do HTTP requests between peers with coordinator''

2017-07-19 09:26:24 - DEBUG UnitTestFramework: '#teardown ok: 'can still do HTTP requests between peers with coordinator''

2017-07-19 09:26:24 - DEBUG UnitTestFramework: '#setup: 'calls correct starts when network changes''

2017-07-19 09:26:24 - DEBUG UnitTestFramework: '#setup ok: 'calls correct starts when network changes''

2017-07-19 09:26:24 - DEBUG UnitTestFramework: '#run: 'calls correct starts when network changes''

2017-07-19 09:26:24 - INFO Socket: 'run skipped, test: 'calls correct starts when network changes', event: 'run_calls correct starts when network changes''

2017-07-19 09:26:24 - INFO Socket: 'run skipped, test: 'calls correct starts when network changes', event: 'run_calls correct starts when network changes''

2017-07-19 09:26:24 - INFO Socket: 'run skipped, test: 'calls correct starts when network changes', event: 'run_calls correct starts when network changes''

2017-07-19 09:26:24 - DEBUG UnitTestFramework: '#run ok: 'calls correct starts when network changes''

2017-07-19 09:26:24 - DEBUG UnitTestFramework: '#teardown: 'calls correct starts when network changes''

2017-07-19 09:26:24 - DEBUG UnitTestFramework: '#teardown ok: 'calls correct starts when network changes''

2017-07-19 09:26:24 - DEBUG UnitTestFramework: '#setup: 'test to coordinate connection cut''

2017-07-19 09:26:24 - DEBUG UnitTestFramework: '#setup ok: 'test to coordinate connection cut''

2017-07-19 09:26:24 - DEBUG UnitTestFramework: '#run: 'test to coordinate connection cut''

2017-07-19 09:26:25 - DEBUG UnitTestFramework: '#run ok: 'test to coordinate connection cut''

2017-07-19 09:26:25 - DEBUG UnitTestFramework: '#teardown: 'test to coordinate connection cut''

2017-07-19 09:26:25 - DEBUG UnitTestFramework: '#teardown ok: 'test to coordinate connection cut''

2017-07-19 09:26:25 - DEBUG UnitTestFramework: '#setup: 'can do HTTP requests after connections are cut''

2017-07-19 09:26:25 - DEBUG UnitTestFramework: '#setup ok: 'can do HTTP requests after connections are cut''

2017-07-19 09:26:25 - DEBUG UnitTestFramework: '#run: 'can do HTTP requests after connections are cut''

2017-07-19 09:29:25 - ERROR UnitTestFramework: '#run failed: 'can do HTTP requests after connections are cut', error: 'TimeoutError: timeout exceeded, event: 'run_can do HTTP requests after connections are cut_finished', test: 'can do HTTP requests after connections are cut'', stack: 'TimeoutError: timeout exceeded, event: 'run_can do HTTP requests after connections are cut_finished', test: 'can do HTTP requests after connections are cut'
    at afterTimeout (/home/pi/Test/server_113351851018c210/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_113351851018c210/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-07-19 09:29:25 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'android', error: 'TimeoutError: timeout exceeded, event: 'run_can do HTTP requests after connections are cut_finished', test: 'can do HTTP requests after connections are cut'', stack: 'TimeoutError: timeout exceeded, event: 'run_can do HTTP requests after connections are cut_finished', test: 'can do HTTP requests after connections are cut'
    at afterTimeout (/home/pi/Test/server_113351851018c210/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_113351851018c210/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-07-19 09:29:30 - DEBUG TestServer: 'completed'

2017-07-19 09:29:30 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-07-19 09:29:30 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''

2017-07-19 09:29:30 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

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

Error! Unexpected exit on device ce061606e320561102 app:com.thaliproject.thalitest code:0 
Child process exited with code 0 on device ce061606e320561102
Android task is completed. [FAILED]
Stopping App:com.thaliproject.thalitest ce061606e320561102 green
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/113351851018c210_CI_sanity_check_jareksl/thali01_samsung-SM-G935F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/113351851018c210_CI_sanity_check_jareksl/thali03_samsung-SM-G930F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/113351851018c210_CI_sanity_check_jareksl/thali04_samsung-SM-G930F.md)





#### Test 1133518512e0667f Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2017-07-20 07:48:46 - INFO HttpServer: 'listening on *:3000'

2017-07-20 07:50:17 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '6b4a7213-4599-4d8d-a319-6b934caa4fb6', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-20 07:50:17 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-07-20 07:50:31 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '786298ac-43d5-4fee-89aa-bcd9592bf7e2', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-20 07:50:31 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-07-20 07:51:57 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: 'd7adf07d-6db9-4c3f-ba91-250ed0086113', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-20 07:51:57 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-07-20 07:51:57 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-07-20 07:51:57 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-07-20 07:51:57 - DEBUG UnitTestFramework: 'scheduling tests'

2017-07-20 07:51:58 - DEBUG UnitTestFramework: 'tests scheduled'

2017-07-20 07:51:58 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-07-20 07:52:00 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-07-20 07:52:00 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-07-20 07:52:03 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-07-20 07:52:03 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-07-20 07:52:03 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-07-20 07:52:03 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-07-20 07:52:06 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-07-20 07:52:06 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-07-20 07:52:11 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-07-20 07:52:11 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-07-20 07:52:12 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-07-20 07:52:12 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-20 07:52:14 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-20 07:52:14 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-20 07:52:15 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-20 07:52:15 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-20 07:52:17 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-20 07:52:17 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-20 07:52:18 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-20 07:52:18 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-20 07:52:20 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-20 07:52:20 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-20 07:52:22 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-20 07:52:22 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-07-20 07:52:23 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-20 07:52:23 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-07-20 07:52:23 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-20 07:52:23 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-20 07:52:25 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-20 07:52:25 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-20 07:52:25 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-07-20 07:52:26 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-20 07:52:26 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-20 07:52:28 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-20 07:52:28 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-20 07:52:28 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-20 07:52:29 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-20 07:52:29 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-20 07:52:29 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-20 07:52:29 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-20 07:52:31 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-20 07:52:31 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-20 07:52:32 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-20 07:52:32 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-20 07:52:32 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-20 07:52:32 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-20 07:52:34 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-20 07:52:34 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-20 07:52:34 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-20 07:52:35 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-20 07:52:35 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-20 07:52:37 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-20 07:52:37 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-20 07:52:37 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-20 07:52:38 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-20 07:52:39 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-20 07:52:39 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-20 07:52:39 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-20 07:52:41 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-20 07:52:41 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-07-20 07:52:43 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-07-20 07:52:43 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-07-20 07:52:47 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-07-20 07:52:47 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-07-20 07:52:50 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-07-20 07:52:50 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-07-20 07:52:51 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-07-20 07:52:51 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-07-20 07:52:53 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-07-20 07:52:53 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-07-20 07:52:56 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-07-20 07:52:56 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-07-20 07:52:57 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-07-20 07:52:57 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-07-20 07:53:00 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-07-20 07:53:00 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-07-20 07:53:02 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-07-20 07:53:02 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-07-20 07:53:04 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-07-20 07:53:04 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-07-20 07:53:06 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-07-20 07:53:06 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-07-20 07:53:08 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-07-20 07:53:08 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-07-20 07:53:11 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-07-20 07:53:11 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-07-20 07:53:13 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-07-20 07:53:13 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-07-20 07:53:16 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-07-20 07:53:16 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-07-20 07:53:18 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-07-20 07:53:18 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-07-20 07:53:20 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-07-20 07:53:20 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-07-20 07:53:23 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-07-20 07:53:23 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-07-20 07:53:24 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-07-20 07:53:24 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-07-20 07:53:26 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-07-20 07:53:26 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-07-20 07:53:29 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-07-20 07:53:29 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-07-20 07:53:32 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-07-20 07:53:32 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-07-20 07:53:32 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-07-20 07:53:32 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-07-20 07:53:35 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-07-20 07:53:35 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-07-20 07:53:35 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-07-20 07:53:35 - DEBUG UnitTestFramework: '#run: 'basic''

2017-07-20 07:53:35 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-07-20 07:53:35 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-07-20 07:53:35 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-07-20 07:53:35 - DEBUG UnitTestFramework: '#setup: 'another''

2017-07-20 07:53:35 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-07-20 07:53:35 - DEBUG UnitTestFramework: '#run: 'another''

2017-07-20 07:53:35 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-07-20 07:53:35 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-07-20 07:53:35 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-07-20 07:53:35 - DEBUG UnitTestFramework: '#setup: 'skip''

2017-07-20 07:53:35 - DEBUG UnitTestFramework: '#setup ok: 'skip''

2017-07-20 07:53:35 - DEBUG UnitTestFramework: '#run: 'skip''

2017-07-20 07:53:35 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-07-20 07:53:35 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-07-20 07:53:35 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-07-20 07:53:35 - DEBUG UnitTestFramework: '#run ok: 'skip''

2017-07-20 07:53:35 - DEBUG UnitTestFramework: '#teardown: 'skip''

2017-07-20 07:53:35 - DEBUG UnitTestFramework: '#teardown ok: 'skip''

2017-07-20 07:53:35 - DEBUG UnitTestFramework: '#setup: 'another skip''

2017-07-20 07:53:35 - DEBUG UnitTestFramework: '#setup ok: 'another skip''

2017-07-20 07:53:35 - DEBUG UnitTestFramework: '#run: 'another skip''

2017-07-20 07:53:35 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-07-20 07:53:35 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-07-20 07:53:35 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-07-20 07:53:35 - DEBUG UnitTestFramework: '#run ok: 'another skip''

2017-07-20 07:53:35 - DEBUG UnitTestFramework: '#teardown: 'another skip''

2017-07-20 07:53:35 - DEBUG UnitTestFramework: '#teardown ok: 'another skip''

2017-07-20 07:53:35 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox spy''

2017-07-20 07:53:35 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox spy''

2017-07-20 07:53:35 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox spy''

2017-07-20 07:53:36 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox spy''

2017-07-20 07:53:36 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox spy''

2017-07-20 07:53:36 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox spy''

2017-07-20 07:53:36 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub''

2017-07-20 07:53:36 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub''

2017-07-20 07:53:36 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub''

2017-07-20 07:53:36 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub''

2017-07-20 07:53:36 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub''

2017-07-20 07:53:36 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub''

2017-07-20 07:53:36 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub override''

2017-07-20 07:53:36 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub override''

2017-07-20 07:53:36 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub override''

2017-07-20 07:53:36 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub override''

2017-07-20 07:53:36 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub override''

2017-07-20 07:53:36 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub override''

2017-07-20 07:53:36 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox mock''

2017-07-20 07:53:36 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox mock''

2017-07-20 07:53:36 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox mock''

2017-07-20 07:53:36 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox mock''

2017-07-20 07:53:36 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox mock''

2017-07-20 07:53:36 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox mock''

2017-07-20 07:53:36 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox restore after test end''

2017-07-20 07:53:36 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox restore after test end''

2017-07-20 07:53:36 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox restore after test end''

2017-07-20 07:53:36 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox restore after test end''

2017-07-20 07:53:36 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox restore after test end''

2017-07-20 07:53:36 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox restore after test end''

2017-07-20 07:53:36 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-07-20 07:53:36 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-07-20 07:53:36 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-07-20 07:53:36 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-07-20 07:53:36 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-07-20 07:53:36 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-07-20 07:53:36 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-07-20 07:53:36 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-07-20 07:53:36 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-07-20 07:53:36 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-07-20 07:53:36 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-07-20 07:53:37 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-07-20 07:53:37 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-07-20 07:53:37 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-07-20 07:53:37 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-07-20 07:53:37 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-07-20 07:53:37 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-07-20 07:53:37 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-07-20 07:53:37 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-07-20 07:53:37 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-07-20 07:53:37 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-07-20 07:53:37 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-07-20 07:53:37 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-07-20 07:53:37 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-07-20 07:53:37 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-07-20 07:53:37 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-07-20 07:53:37 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-07-20 07:53:38 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-07-20 07:53:38 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-07-20 07:53:38 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-07-20 07:53:38 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-20 07:53:38 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-20 07:53:38 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-20 07:53:39 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-20 07:53:39 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-20 07:53:41 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-20 07:53:41 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-20 07:53:43 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-20 07:53:43 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-20 07:53:44 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-20 07:53:44 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-20 07:53:47 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-20 07:53:47 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-20 07:53:50 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-20 07:53:50 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-20 07:53:51 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-20 07:53:51 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-20 07:53:51 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-20 07:53:51 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-20 07:53:51 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-20 07:53:51 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-20 07:53:52 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-20 07:53:52 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-20 07:53:55 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-20 07:53:55 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-20 07:53:55 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-20 07:53:55 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-20 07:53:58 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-20 07:53:58 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-20 07:53:59 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-20 07:53:59 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-07-20 07:54:01 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-07-20 07:54:01 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-07-20 07:54:04 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-07-20 07:54:04 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-07-20 07:54:07 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-07-20 07:54:07 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-07-20 07:54:11 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-07-20 07:54:11 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-07-20 07:54:19 - DEBUG UnitTestFramework: '#run ok: 'Can connect to a remote peer''

2017-07-20 07:54:19 - DEBUG UnitTestFramework: '#teardown: 'Can connect to a remote peer''

2017-07-20 07:54:23 - DEBUG UnitTestFramework: '#teardown ok: 'Can connect to a remote peer''

2017-07-20 07:54:23 - DEBUG UnitTestFramework: '#setup: 'Can shift data''

2017-07-20 07:54:26 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data''

2017-07-20 07:54:26 - DEBUG UnitTestFramework: '#run: 'Can shift data''

2017-07-20 07:54:35 - DEBUG UnitTestFramework: '#run ok: 'Can shift data''

2017-07-20 07:54:35 - DEBUG UnitTestFramework: '#teardown: 'Can shift data''

2017-07-20 07:54:38 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data''

2017-07-20 07:54:38 - DEBUG UnitTestFramework: '#setup: 'Can shift data via parallel connections''

2017-07-20 07:54:39 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data via parallel connections''

2017-07-20 07:54:39 - DEBUG UnitTestFramework: '#run: 'Can shift data via parallel connections''

2017-07-20 07:54:39 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-07-20 07:54:41 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-07-20 07:54:41 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-07-20 07:54:41 - DEBUG UnitTestFramework: '#run ok: 'Can shift data via parallel connections''

2017-07-20 07:54:41 - DEBUG UnitTestFramework: '#teardown: 'Can shift data via parallel connections''

2017-07-20 07:54:44 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data via parallel connections''

2017-07-20 07:54:44 - DEBUG UnitTestFramework: '#setup: 'Can shift data securely''

2017-07-20 07:54:44 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data securely''

2017-07-20 07:54:44 - DEBUG UnitTestFramework: '#run: 'Can shift data securely''

2017-07-20 07:54:57 - DEBUG UnitTestFramework: '#run ok: 'Can shift data securely''

2017-07-20 07:54:57 - DEBUG UnitTestFramework: '#teardown: 'Can shift data securely''

2017-07-20 07:55:00 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data securely''

2017-07-20 07:55:00 - DEBUG UnitTestFramework: '#setup: 'Can shift large amounts of data''

2017-07-20 07:55:02 - DEBUG UnitTestFramework: '#setup ok: 'Can shift large amounts of data''

2017-07-20 07:55:02 - DEBUG UnitTestFramework: '#run: 'Can shift large amounts of data''

2017-07-20 07:55:11 - DEBUG UnitTestFramework: '#run ok: 'Can shift large amounts of data''

2017-07-20 07:55:11 - DEBUG UnitTestFramework: '#teardown: 'Can shift large amounts of data''

2017-07-20 07:55:13 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift large amounts of data''

2017-07-20 07:55:13 - DEBUG UnitTestFramework: '#setup: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-20 07:55:14 - DEBUG UnitTestFramework: '#setup ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-20 07:55:14 - DEBUG UnitTestFramework: '#run: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-20 07:55:23 - DEBUG UnitTestFramework: '#run ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-20 07:55:23 - DEBUG UnitTestFramework: '#teardown: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-20 07:55:25 - DEBUG UnitTestFramework: '#teardown ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-20 07:55:25 - DEBUG UnitTestFramework: '#setup: 'Test updating advertising and parallel data transfer''

2017-07-20 07:55:26 - DEBUG UnitTestFramework: '#setup ok: 'Test updating advertising and parallel data transfer''

2017-07-20 07:55:26 - DEBUG UnitTestFramework: '#run: 'Test updating advertising and parallel data transfer''

2017-07-20 07:55:26 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-07-20 07:55:27 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-07-20 07:55:29 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-07-20 07:55:29 - DEBUG UnitTestFramework: '#run ok: 'Test updating advertising and parallel data transfer''

2017-07-20 07:55:29 - DEBUG UnitTestFramework: '#teardown: 'Test updating advertising and parallel data transfer''

2017-07-20 07:55:30 - DEBUG UnitTestFramework: '#teardown ok: 'Test updating advertising and parallel data transfer''

2017-07-20 07:55:30 - DEBUG UnitTestFramework: '#setup: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-20 07:55:32 - DEBUG UnitTestFramework: '#setup ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-20 07:55:32 - DEBUG UnitTestFramework: '#run: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-20 07:55:37 - DEBUG UnitTestFramework: '#run ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-20 07:55:37 - DEBUG UnitTestFramework: '#teardown: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-20 07:55:39 - DEBUG UnitTestFramework: '#teardown ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-20 07:55:39 - DEBUG UnitTestFramework: '#setup: 'cannot call connect when start listening for advertisements is not active''

2017-07-20 07:55:41 - DEBUG UnitTestFramework: '#setup ok: 'cannot call connect when start listening for advertisements is not active''

2017-07-20 07:55:41 - DEBUG UnitTestFramework: '#run: 'cannot call connect when start listening for advertisements is not active''

2017-07-20 07:55:43 - DEBUG UnitTestFramework: '#run ok: 'cannot call connect when start listening for advertisements is not active''

2017-07-20 07:55:43 - DEBUG UnitTestFramework: '#teardown: 'cannot call connect when start listening for advertisements is not active''

2017-07-20 07:55:47 - DEBUG UnitTestFramework: '#teardown ok: 'cannot call connect when start listening for advertisements is not active''

2017-07-20 07:55:47 - DEBUG UnitTestFramework: '#setup: 'Get error when trying to double connect to a peer on Android''

2017-07-20 07:55:49 - DEBUG UnitTestFramework: '#setup ok: 'Get error when trying to double connect to a peer on Android''

2017-07-20 07:55:49 - DEBUG UnitTestFramework: '#run: 'Get error when trying to double connect to a peer on Android''

2017-07-20 07:55:49 - INFO Socket: 'run skipped, test: 'Get error when trying to double connect to a peer on Android', event: 'run_Get error when trying to double connect to a peer on Android''

2017-07-20 07:55:50 - INFO Socket: 'run skipped, test: 'Get error when trying to double connect to a peer on Android', event: 'run_Get error when trying to double connect to a peer on Android''

2017-07-20 07:55:53 - INFO Socket: 'run skipped, test: 'Get error when trying to double connect to a peer on Android', event: 'run_Get error when trying to double connect to a peer on Android''

2017-07-20 07:55:53 - DEBUG UnitTestFramework: '#run ok: 'Get error when trying to double connect to a peer on Android''

2017-07-20 07:55:53 - DEBUG UnitTestFramework: '#teardown: 'Get error when trying to double connect to a peer on Android''

2017-07-20 07:55:55 - DEBUG UnitTestFramework: '#teardown ok: 'Get error when trying to double connect to a peer on Android''

2017-07-20 07:55:55 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-20 07:55:56 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-20 07:55:56 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-20 07:56:02 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-20 07:56:02 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-20 07:56:05 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-20 07:56:05 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-20 07:56:07 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-20 07:56:07 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-20 07:56:07 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection', event: 'run_#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-20 07:56:08 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection', event: 'run_#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-20 07:56:10 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection', event: 'run_#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-20 07:56:10 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-20 07:56:10 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-20 07:56:11 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-20 07:56:11 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-20 07:56:14 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-20 07:56:14 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-20 07:56:22 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-20 07:56:22 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-20 07:56:24 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-20 07:56:24 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-20 07:56:25 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-20 07:56:25 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-20 07:56:38 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-20 07:56:38 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-20 07:56:42 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-20 07:56:42 - DEBUG UnitTestFramework: '#setup: 'initial peer discovery''

2017-07-20 07:56:44 - DEBUG UnitTestFramework: '#setup ok: 'initial peer discovery''

2017-07-20 07:56:44 - DEBUG UnitTestFramework: '#run: 'initial peer discovery''

2017-07-20 07:56:44 - INFO Socket: 'run skipped, test: 'initial peer discovery', event: 'run_initial peer discovery''

2017-07-20 07:56:44 - INFO Socket: 'run skipped, test: 'initial peer discovery', event: 'run_initial peer discovery''

2017-07-20 07:56:44 - INFO Socket: 'run skipped, test: 'initial peer discovery', event: 'run_initial peer discovery''

2017-07-20 07:56:44 - DEBUG UnitTestFramework: '#run ok: 'initial peer discovery''

2017-07-20 07:56:44 - DEBUG UnitTestFramework: '#teardown: 'initial peer discovery''

2017-07-20 07:56:47 - DEBUG UnitTestFramework: '#teardown ok: 'initial peer discovery''

2017-07-20 07:56:47 - DEBUG UnitTestFramework: '#setup: 'update peer discovery 1''

2017-07-20 07:56:49 - DEBUG UnitTestFramework: '#setup ok: 'update peer discovery 1''

2017-07-20 07:56:49 - DEBUG UnitTestFramework: '#run: 'update peer discovery 1''

2017-07-20 07:56:50 - INFO Socket: 'run skipped, test: 'update peer discovery 1', event: 'run_update peer discovery 1''

2017-07-20 07:56:51 - INFO Socket: 'run skipped, test: 'update peer discovery 1', event: 'run_update peer discovery 1''

2017-07-20 07:56:51 - INFO Socket: 'run skipped, test: 'update peer discovery 1', event: 'run_update peer discovery 1''

2017-07-20 07:56:51 - DEBUG UnitTestFramework: '#run ok: 'update peer discovery 1''

2017-07-20 07:56:51 - DEBUG UnitTestFramework: '#teardown: 'update peer discovery 1''

2017-07-20 07:56:53 - DEBUG UnitTestFramework: '#teardown ok: 'update peer discovery 1''

2017-07-20 07:56:53 - DEBUG UnitTestFramework: '#setup: 'update peer discovery 2''

2017-07-20 07:56:55 - DEBUG UnitTestFramework: '#setup ok: 'update peer discovery 2''

2017-07-20 07:56:55 - DEBUG UnitTestFramework: '#run: 'update peer discovery 2''

2017-07-20 07:56:55 - INFO Socket: 'run skipped, test: 'update peer discovery 2', event: 'run_update peer discovery 2''

2017-07-20 07:56:56 - INFO Socket: 'run skipped, test: 'update peer discovery 2', event: 'run_update peer discovery 2''

2017-07-20 07:56:57 - INFO Socket: 'run skipped, test: 'update peer discovery 2', event: 'run_update peer discovery 2''

2017-07-20 07:56:57 - DEBUG UnitTestFramework: '#run ok: 'update peer discovery 2''

2017-07-20 07:56:57 - DEBUG UnitTestFramework: '#teardown: 'update peer discovery 2''

2017-07-20 07:56:58 - DEBUG UnitTestFramework: '#teardown ok: 'update peer discovery 2''

2017-07-20 07:56:58 - DEBUG UnitTestFramework: '#setup: 'check latest peer discovery''

2017-07-20 07:57:00 - DEBUG UnitTestFramework: '#setup ok: 'check latest peer discovery''

2017-07-20 07:57:00 - DEBUG UnitTestFramework: '#run: 'check latest peer discovery''

2017-07-20 07:57:00 - INFO Socket: 'run skipped, test: 'check latest peer discovery', event: 'run_check latest peer discovery''

2017-07-20 07:57:01 - INFO Socket: 'run skipped, test: 'check latest peer discovery', event: 'run_check latest peer discovery''

2017-07-20 07:57:01 - INFO Socket: 'run skipped, test: 'check latest peer discovery', event: 'run_check latest peer discovery''

2017-07-20 07:57:01 - DEBUG UnitTestFramework: '#run ok: 'check latest peer discovery''

2017-07-20 07:57:01 - DEBUG UnitTestFramework: '#teardown: 'check latest peer discovery''

2017-07-20 07:57:04 - DEBUG UnitTestFramework: '#teardown ok: 'check latest peer discovery''

2017-07-20 07:57:04 - DEBUG UnitTestFramework: '#setup: 'Set up for no peer discovery test''

2017-07-20 07:57:06 - DEBUG UnitTestFramework: '#setup ok: 'Set up for no peer discovery test''

2017-07-20 07:57:06 - DEBUG UnitTestFramework: '#run: 'Set up for no peer discovery test''

2017-07-20 07:57:06 - INFO Socket: 'run skipped, test: 'Set up for no peer discovery test', event: 'run_Set up for no peer discovery test''

2017-07-20 07:57:07 - INFO Socket: 'run skipped, test: 'Set up for no peer discovery test', event: 'run_Set up for no peer discovery test''

2017-07-20 07:57:11 - INFO Socket: 'run skipped, test: 'Set up for no peer discovery test', event: 'run_Set up for no peer discovery test''

2017-07-20 07:57:11 - DEBUG UnitTestFramework: '#run ok: 'Set up for no peer discovery test''

2017-07-20 07:57:11 - DEBUG UnitTestFramework: '#teardown: 'Set up for no peer discovery test''

2017-07-20 07:57:13 - DEBUG UnitTestFramework: '#teardown ok: 'Set up for no peer discovery test''

2017-07-20 07:57:13 - DEBUG UnitTestFramework: '#setup: 'no peer discovery''

2017-07-20 07:57:14 - DEBUG UnitTestFramework: '#setup ok: 'no peer discovery''

2017-07-20 07:57:14 - DEBUG UnitTestFramework: '#run: 'no peer discovery''

2017-07-20 07:57:14 - INFO Socket: 'run skipped, test: 'no peer discovery', event: 'run_no peer discovery''

2017-07-20 07:57:15 - INFO Socket: 'run skipped, test: 'no peer discovery', event: 'run_no peer discovery''

2017-07-20 07:57:16 - INFO Socket: 'run skipped, test: 'no peer discovery', event: 'run_no peer discovery''

2017-07-20 07:57:16 - DEBUG UnitTestFramework: '#run ok: 'no peer discovery''

2017-07-20 07:57:16 - DEBUG UnitTestFramework: '#teardown: 'no peer discovery''

2017-07-20 07:57:18 - DEBUG UnitTestFramework: '#teardown ok: 'no peer discovery''

2017-07-20 07:57:18 - DEBUG UnitTestFramework: '#setup: 'calling createNativeListener directly rejects''

2017-07-20 07:57:20 - DEBUG UnitTestFramework: '#setup ok: 'calling createNativeListener directly rejects''

2017-07-20 07:57:20 - DEBUG UnitTestFramework: '#run: 'calling createNativeListener directly rejects''

2017-07-20 07:57:23 - DEBUG UnitTestFramework: '#run ok: 'calling createNativeListener directly rejects''

2017-07-20 07:57:23 - DEBUG UnitTestFramework: '#teardown: 'calling createNativeListener directly rejects''

2017-07-20 07:57:23 - DEBUG UnitTestFramework: '#teardown ok: 'calling createNativeListener directly rejects''

2017-07-20 07:57:23 - DEBUG UnitTestFramework: '#setup: 'emits incomingConnectionState''

2017-07-20 07:57:26 - DEBUG UnitTestFramework: '#setup ok: 'emits incomingConnectionState''

2017-07-20 07:57:26 - DEBUG UnitTestFramework: '#run: 'emits incomingConnectionState''

2017-07-20 07:57:29 - DEBUG UnitTestFramework: '#run ok: 'emits incomingConnectionState''

2017-07-20 07:57:29 - DEBUG UnitTestFramework: '#teardown: 'emits incomingConnectionState''

2017-07-20 07:57:29 - DEBUG UnitTestFramework: '#teardown ok: 'emits incomingConnectionState''

2017-07-20 07:57:29 - DEBUG UnitTestFramework: '#setup: 'emits routerPortConnectionFailed''

2017-07-20 07:57:32 - DEBUG UnitTestFramework: '#setup ok: 'emits routerPortConnectionFailed''

2017-07-20 07:57:32 - DEBUG UnitTestFramework: '#run: 'emits routerPortConnectionFailed''

2017-07-20 07:57:32 - DEBUG UnitTestFramework: '#run ok: 'emits routerPortConnectionFailed''

2017-07-20 07:57:32 - DEBUG UnitTestFramework: '#teardown: 'emits routerPortConnectionFailed''

2017-07-20 07:57:35 - DEBUG UnitTestFramework: '#teardown ok: 'emits routerPortConnectionFailed''

2017-07-20 07:57:35 - DEBUG UnitTestFramework: '#setup: 'native server connections all up''

2017-07-20 07:57:35 - DEBUG UnitTestFramework: '#setup ok: 'native server connections all up''

2017-07-20 07:57:35 - DEBUG UnitTestFramework: '#run: 'native server connections all up''

2017-07-20 07:57:38 - DEBUG UnitTestFramework: '#run ok: 'native server connections all up''

2017-07-20 07:57:38 - DEBUG UnitTestFramework: '#teardown: 'native server connections all up''

2017-07-20 07:57:39 - DEBUG UnitTestFramework: '#teardown ok: 'native server connections all up''

2017-07-20 07:57:39 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming stream cleans outgoing socket''

2017-07-20 07:57:41 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming stream cleans outgoing socket''

2017-07-20 07:57:41 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming stream cleans outgoing socket''

2017-07-20 07:57:44 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming stream cleans outgoing socket''

2017-07-20 07:57:44 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming stream cleans outgoing socket''

2017-07-20 07:57:47 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming stream cleans outgoing socket''

2017-07-20 07:57:47 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming connection cleans outgoing socket''

2017-07-20 07:57:48 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming connection cleans outgoing socket''

2017-07-20 07:57:48 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming connection cleans outgoing socket''

2017-07-20 07:57:50 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming connection cleans outgoing socket''

2017-07-20 07:57:50 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming connection cleans outgoing socket''

2017-07-20 07:57:53 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming connection cleans outgoing socket''

2017-07-20 07:57:53 - DEBUG UnitTestFramework: '#setup: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-20 07:57:55 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-20 07:57:55 - DEBUG UnitTestFramework: '#run: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-20 07:57:56 - DEBUG UnitTestFramework: '#run ok: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-20 07:57:56 - DEBUG UnitTestFramework: '#teardown: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-20 07:57:59 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-20 07:57:59 - DEBUG UnitTestFramework: '#setup: 'native server - closing the whole server cleans everything up''

2017-07-20 07:58:01 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing the whole server cleans everything up''

2017-07-20 07:58:01 - DEBUG UnitTestFramework: '#run: 'native server - closing the whole server cleans everything up''

2017-07-20 07:58:02 - DEBUG UnitTestFramework: '#run ok: 'native server - closing the whole server cleans everything up''

2017-07-20 07:58:02 - DEBUG UnitTestFramework: '#teardown: 'native server - closing the whole server cleans everything up''

2017-07-20 07:58:04 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing the whole server cleans everything up''

2017-07-20 07:58:04 - DEBUG UnitTestFramework: '#setup: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-20 07:58:05 - DEBUG UnitTestFramework: '#setup ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-20 07:58:05 - DEBUG UnitTestFramework: '#run: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-20 07:58:08 - DEBUG UnitTestFramework: '#run ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-20 07:58:08 - DEBUG UnitTestFramework: '#teardown: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-20 07:58:11 - DEBUG UnitTestFramework: '#teardown ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-20 07:58:11 - DEBUG UnitTestFramework: '#setup: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-20 07:58:13 - DEBUG UnitTestFramework: '#setup ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-20 07:58:13 - DEBUG UnitTestFramework: '#run: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-20 07:58:14 - DEBUG UnitTestFramework: '#run ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-20 07:58:14 - DEBUG UnitTestFramework: '#teardown: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-20 07:58:17 - DEBUG UnitTestFramework: '#teardown ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-20 07:58:17 - DEBUG UnitTestFramework: '#setup: 'native server - timing out the incoming connection cleans everything up''

2017-07-20 07:58:19 - DEBUG UnitTestFramework: '#setup ok: 'native server - timing out the incoming connection cleans everything up''

2017-07-20 07:58:19 - DEBUG UnitTestFramework: '#run: 'native server - timing out the incoming connection cleans everything up''

2017-07-20 07:58:20 - DEBUG UnitTestFramework: '#run ok: 'native server - timing out the incoming connection cleans everything up''

2017-07-20 07:58:20 - DEBUG UnitTestFramework: '#teardown: 'native server - timing out the incoming connection cleans everything up''

2017-07-20 07:58:23 - DEBUG UnitTestFramework: '#teardown ok: 'native server - timing out the incoming connection cleans everything up''

2017-07-20 07:58:23 - DEBUG UnitTestFramework: '#setup: 'can create servers manager''

2017-07-20 07:58:24 - DEBUG UnitTestFramework: '#setup ok: 'can create servers manager''

2017-07-20 07:58:24 - DEBUG UnitTestFramework: '#run: 'can create servers manager''

2017-07-20 07:58:26 - DEBUG UnitTestFramework: '#run ok: 'can create servers manager''

2017-07-20 07:58:26 - DEBUG UnitTestFramework: '#teardown: 'can create servers manager''

2017-07-20 07:58:29 - DEBUG UnitTestFramework: '#teardown ok: 'can create servers manager''

2017-07-20 07:58:29 - DEBUG UnitTestFramework: '#setup: 'calling stop without start causes error''

2017-07-20 07:58:30 - DEBUG UnitTestFramework: '#setup ok: 'calling stop without start causes error''

2017-07-20 07:58:30 - DEBUG UnitTestFramework: '#run: 'calling stop without start causes error''

2017-07-20 07:58:32 - DEBUG UnitTestFramework: '#run ok: 'calling stop without start causes error''

2017-07-20 07:58:32 - DEBUG UnitTestFramework: '#teardown: 'calling stop without start causes error''

2017-07-20 07:58:35 - DEBUG UnitTestFramework: '#teardown ok: 'calling stop without start causes error''

2017-07-20 07:58:35 - DEBUG UnitTestFramework: '#setup: 'can start/stop servers manager''

2017-07-20 07:58:36 - DEBUG UnitTestFramework: '#setup ok: 'can start/stop servers manager''

2017-07-20 07:58:36 - DEBUG UnitTestFramework: '#run: 'can start/stop servers manager''

2017-07-20 07:58:38 - DEBUG UnitTestFramework: '#run ok: 'can start/stop servers manager''

2017-07-20 07:58:38 - DEBUG UnitTestFramework: '#teardown: 'can start/stop servers manager''

2017-07-20 07:58:38 - DEBUG UnitTestFramework: '#teardown ok: 'can start/stop servers manager''

2017-07-20 07:58:38 - DEBUG UnitTestFramework: '#setup: 'starting twice resolves with listening port''

2017-07-20 07:58:41 - DEBUG UnitTestFramework: '#setup ok: 'starting twice resolves with listening port''

2017-07-20 07:58:41 - DEBUG UnitTestFramework: '#run: 'starting twice resolves with listening port''

2017-07-20 07:58:44 - DEBUG UnitTestFramework: '#run ok: 'starting twice resolves with listening port''

2017-07-20 07:58:44 - DEBUG UnitTestFramework: '#teardown: 'starting twice resolves with listening port''

2017-07-20 07:58:45 - DEBUG UnitTestFramework: '#teardown ok: 'starting twice resolves with listening port''

2017-07-20 07:58:45 - DEBUG UnitTestFramework: '#setup: 'terminateIncomingConnection will terminate a connection''

2017-07-20 07:58:47 - DEBUG UnitTestFramework: '#setup ok: 'terminateIncomingConnection will terminate a connection''

2017-07-20 07:58:47 - DEBUG UnitTestFramework: '#run: 'terminateIncomingConnection will terminate a connection''

2017-07-20 07:58:48 - DEBUG UnitTestFramework: '#run ok: 'terminateIncomingConnection will terminate a connection''

2017-07-20 07:58:48 - DEBUG UnitTestFramework: '#teardown: 'terminateIncomingConnection will terminate a connection''

2017-07-20 07:58:50 - DEBUG UnitTestFramework: '#teardown ok: 'terminateIncomingConnection will terminate a connection''

2017-07-20 07:58:50 - DEBUG UnitTestFramework: '#setup: 'terminate an Outgoing connection''

2017-07-20 07:58:53 - DEBUG UnitTestFramework: '#setup ok: 'terminate an Outgoing connection''

2017-07-20 07:58:53 - DEBUG UnitTestFramework: '#run: 'terminate an Outgoing connection''

2017-07-20 07:58:54 - DEBUG UnitTestFramework: '#run ok: 'terminate an Outgoing connection''

2017-07-20 07:58:54 - DEBUG UnitTestFramework: '#teardown: 'terminate an Outgoing connection''

2017-07-20 07:58:56 - DEBUG UnitTestFramework: '#teardown ok: 'terminate an Outgoing connection''

2017-07-20 07:58:56 - DEBUG UnitTestFramework: '#setup: 'Single local http request''

2017-07-20 07:58:57 - DEBUG UnitTestFramework: '#setup ok: 'Single local http request''

2017-07-20 07:58:57 - DEBUG UnitTestFramework: '#run: 'Single local http request''

2017-07-20 07:59:00 - DEBUG UnitTestFramework: '#run ok: 'Single local http request''

2017-07-20 07:59:00 - DEBUG UnitTestFramework: '#teardown: 'Single local http request''

2017-07-20 07:59:02 - DEBUG UnitTestFramework: '#teardown ok: 'Single local http request''

2017-07-20 07:59:02 - DEBUG UnitTestFramework: '#setup: 'Single coordinated request ios native''

2017-07-20 07:59:03 - DEBUG UnitTestFramework: '#setup ok: 'Single coordinated request ios native''

2017-07-20 07:59:03 - DEBUG UnitTestFramework: '#run: 'Single coordinated request ios native''

2017-07-20 07:59:03 - INFO Socket: 'run skipped, test: 'Single coordinated request ios native', event: 'run_Single coordinated request ios native''

2017-07-20 07:59:03 - INFO Socket: 'run skipped, test: 'Single coordinated request ios native', event: 'run_Single coordinated request ios native''

2017-07-20 07:59:04 - INFO Socket: 'run skipped, test: 'Single coordinated request ios native', event: 'run_Single coordinated request ios native''

2017-07-20 07:59:04 - DEBUG UnitTestFramework: '#run ok: 'Single coordinated request ios native''

2017-07-20 07:59:04 - DEBUG UnitTestFramework: '#teardown: 'Single coordinated request ios native''

2017-07-20 07:59:06 - DEBUG UnitTestFramework: '#teardown ok: 'Single coordinated request ios native''

2017-07-20 07:59:06 - DEBUG UnitTestFramework: '#setup: 'Multiple local http requests''

2017-07-20 07:59:07 - DEBUG UnitTestFramework: '#setup ok: 'Multiple local http requests''

2017-07-20 07:59:07 - DEBUG UnitTestFramework: '#run: 'Multiple local http requests''

2017-07-20 07:59:09 - DEBUG UnitTestFramework: '#run ok: 'Multiple local http requests''

2017-07-20 07:59:09 - DEBUG UnitTestFramework: '#teardown: 'Multiple local http requests''

2017-07-20 07:59:11 - DEBUG UnitTestFramework: '#teardown ok: 'Multiple local http requests''

2017-07-20 07:59:11 - DEBUG UnitTestFramework: '#setup: 'Multiple coordinated request ios native''

2017-07-20 07:59:14 - DEBUG UnitTestFramework: '#setup ok: 'Multiple coordinated request ios native''

2017-07-20 07:59:14 - DEBUG UnitTestFramework: '#run: 'Multiple coordinated request ios native''

2017-07-20 07:59:14 - INFO Socket: 'run skipped, test: 'Multiple coordinated request ios native', event: 'run_Multiple coordinated request ios native''

2017-07-20 07:59:14 - INFO Socket: 'run skipped, test: 'Multiple coordinated request ios native', event: 'run_Multiple coordinated request ios native''

2017-07-20 07:59:16 - INFO Socket: 'run skipped, test: 'Multiple coordinated request ios native', event: 'run_Multiple coordinated request ios native''

2017-07-20 07:59:16 - DEBUG UnitTestFramework: '#run ok: 'Multiple coordinated request ios native''

2017-07-20 07:59:16 - DEBUG UnitTestFramework: '#teardown: 'Multiple coordinated request ios native''

2017-07-20 07:59:17 - DEBUG UnitTestFramework: '#teardown ok: 'Multiple coordinated request ios native''

2017-07-20 07:59:17 - DEBUG UnitTestFramework: '#setup: '#startListeningForAdvertisements should fail if start not called''

2017-07-20 07:59:19 - DEBUG UnitTestFramework: '#setup ok: '#startListeningForAdvertisements should fail if start not called''

2017-07-20 07:59:19 - DEBUG UnitTestFramework: '#run: '#startListeningForAdvertisements should fail if start not called''

2017-07-20 07:59:23 - DEBUG UnitTestFramework: '#run ok: '#startListeningForAdvertisements should fail if start not called''

2017-07-20 07:59:23 - DEBUG UnitTestFramework: '#teardown: '#startListeningForAdvertisements should fail if start not called''

2017-07-20 07:59:25 - DEBUG UnitTestFramework: '#teardown ok: '#startListeningForAdvertisements should fail if start not called''

2017-07-20 07:59:25 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-20 07:59:27 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-20 07:59:27 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-20 07:59:29 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-20 07:59:29 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-20 07:59:31 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-20 07:59:31 - DEBUG UnitTestFramework: '#setup: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-20 07:59:32 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-20 07:59:32 - DEBUG UnitTestFramework: '#run: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-20 07:59:34 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-20 07:59:34 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-20 07:59:37 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-20 07:59:37 - DEBUG UnitTestFramework: '#setup: 'should be able to call #startListeningForAdvertisements many times''

2017-07-20 07:59:38 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #startListeningForAdvertisements many times''

2017-07-20 07:59:38 - DEBUG UnitTestFramework: '#run: 'should be able to call #startListeningForAdvertisements many times''

2017-07-20 07:59:42 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #startListeningForAdvertisements many times''

2017-07-20 07:59:42 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #startListeningForAdvertisements many times''

2017-07-20 07:59:45 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #startListeningForAdvertisements many times''

2017-07-20 07:59:45 - DEBUG UnitTestFramework: '#setup: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-20 07:59:47 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-20 07:59:47 - DEBUG UnitTestFramework: '#run: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-20 07:59:48 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-20 07:59:48 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-20 07:59:51 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-20 07:59:51 - DEBUG UnitTestFramework: '#setup: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-20 07:59:53 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-20 07:59:53 - DEBUG UnitTestFramework: '#run: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-20 07:59:54 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-20 07:59:54 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-20 07:59:57 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-20 07:59:57 - DEBUG UnitTestFramework: '#setup: '#start - Causing native or wifi to fail will cause a promise reject ''

2017-07-20 07:59:57 - DEBUG UnitTestFramework: '#setup ok: '#start - Causing native or wifi to fail will cause a promise reject ''

2017-07-20 07:59:57 - DEBUG UnitTestFramework: '#run: '#start - Causing native or wifi to fail will cause a promise reject ''

2017-07-20 08:00:00 - DEBUG UnitTestFramework: '#run ok: '#start - Causing native or wifi to fail will cause a promise reject ''

2017-07-20 08:00:00 - DEBUG UnitTestFramework: '#teardown: '#start - Causing native or wifi to fail will cause a promise reject ''

2017-07-20 08:00:00 - DEBUG UnitTestFramework: '#teardown ok: '#start - Causing native or wifi to fail will cause a promise reject ''

2017-07-20 08:00:00 - DEBUG UnitTestFramework: '#setup: '#start should fail if called twice in a row''

2017-07-20 08:00:03 - DEBUG UnitTestFramework: '#setup ok: '#start should fail if called twice in a row''

2017-07-20 08:00:03 - DEBUG UnitTestFramework: '#run: '#start should fail if called twice in a row''

2017-07-20 08:00:03 - DEBUG UnitTestFramework: '#run ok: '#start should fail if called twice in a row''

2017-07-20 08:00:03 - DEBUG UnitTestFramework: '#teardown: '#start should fail if called twice in a row''

2017-07-20 08:00:06 - DEBUG UnitTestFramework: '#teardown ok: '#start should fail if called twice in a row''

2017-07-20 08:00:06 - DEBUG UnitTestFramework: '#setup: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-07-20 08:00:07 - DEBUG UnitTestFramework: '#setup ok: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-07-20 08:00:07 - DEBUG UnitTestFramework: '#run: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-07-20 08:00:07 - INFO Socket: 'run skipped, test: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)', event: 'run_#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-07-20 08:00:09 - INFO Socket: 'run skipped, test: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)', event: 'run_#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-07-20 08:00:10 - INFO Socket: 'run skipped, test: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)', event: 'run_#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-07-20 08:00:10 - DEBUG UnitTestFramework: '#run ok: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-07-20 08:00:10 - DEBUG UnitTestFramework: '#teardown: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-07-20 08:00:12 - DEBUG UnitTestFramework: '#teardown ok: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-07-20 08:00:12 - DEBUG UnitTestFramework: '#setup: 'does not emit duplicate discoveryAdvertisingStateUpdate''

2017-07-20 08:00:13 - DEBUG UnitTestFramework: '#setup ok: 'does not emit duplicate discoveryAdvertisingStateUpdate''

2017-07-20 08:00:13 - DEBUG UnitTestFramework: '#run: 'does not emit duplicate discoveryAdvertisingStateUpdate''

2017-07-20 08:00:13 - INFO Socket: 'run skipped, test: 'does not emit duplicate discoveryAdvertisingStateUpdate', event: 'run_does not emit duplicate discoveryAdvertisingStateUpdate''

2017-07-20 08:00:15 - INFO Socket: 'run skipped, test: 'does not emit duplicate discoveryAdvertisingStateUpdate', event: 'run_does not emit duplicate discoveryAdvertisingStateUpdate''

2017-07-20 08:00:17 - INFO Socket: 'run skipped, test: 'does not emit duplicate discoveryAdvertisingStateUpdate', event: 'run_does not emit duplicate discoveryAdvertisingStateUpdate''

2017-07-20 08:00:17 - DEBUG UnitTestFramework: '#run ok: 'does not emit duplicate discoveryAdvertisingStateUpdate''

2017-07-20 08:00:17 - DEBUG UnitTestFramework: '#teardown: 'does not emit duplicate discoveryAdvertisingStateUpdate''

2017-07-20 08:00:19 - DEBUG UnitTestFramework: '#teardown ok: 'does not emit duplicate discoveryAdvertisingStateUpdate''

2017-07-20 08:00:19 - DEBUG UnitTestFramework: '#setup: 'does not send duplicate availability changes''

2017-07-20 08:00:20 - DEBUG UnitTestFramework: '#setup ok: 'does not send duplicate availability changes''

2017-07-20 08:00:20 - DEBUG UnitTestFramework: '#run: 'does not send duplicate availability changes''

2017-07-20 08:00:23 - DEBUG UnitTestFramework: '#run ok: 'does not send duplicate availability changes''

2017-07-20 08:00:23 - DEBUG UnitTestFramework: '#teardown: 'does not send duplicate availability changes''

2017-07-20 08:00:24 - DEBUG UnitTestFramework: '#teardown ok: 'does not send duplicate availability changes''

2017-07-20 08:00:24 - DEBUG UnitTestFramework: '#setup: 'can get the network status''

2017-07-20 08:00:26 - DEBUG UnitTestFramework: '#setup ok: 'can get the network status''

2017-07-20 08:00:26 - DEBUG UnitTestFramework: '#run: 'can get the network status''

2017-07-20 08:00:29 - DEBUG UnitTestFramework: '#run ok: 'can get the network status''

2017-07-20 08:00:29 - DEBUG UnitTestFramework: '#teardown: 'can get the network status''

2017-07-20 08:00:30 - DEBUG UnitTestFramework: '#teardown ok: 'can get the network status''

2017-07-20 08:00:30 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChanged - peer added/removed to/from cache (native)''

2017-07-20 08:00:32 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChanged - peer added/removed to/from cache (native)''

2017-07-20 08:00:32 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChanged - peer added/removed to/from cache (native)''

2017-07-20 08:00:33 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChanged - peer added/removed to/from cache (native)''

2017-07-20 08:00:33 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChanged - peer added/removed to/from cache (native)''

2017-07-20 08:00:35 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChanged - peer added/removed to/from cache (native)''

2017-07-20 08:00:35 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChanged - peer added/removed to/from cache (wifi)''

2017-07-20 08:00:38 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChanged - peer added/removed to/from cache (wifi)''

2017-07-20 08:00:38 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChanged - peer added/removed to/from cache (wifi)''

2017-07-20 08:00:41 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChanged - peer added/removed to/from cache (wifi)''

2017-07-20 08:00:41 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChanged - peer added/removed to/from cache (wifi)''

2017-07-20 08:00:44 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChanged - peer added/removed to/from cache (wifi)''

2017-07-20 08:00:44 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored''

2017-07-20 08:00:44 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored''

2017-07-20 08:00:44 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored''

2017-07-20 08:00:44 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored''

2017-07-20 08:00:44 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored''

2017-07-20 08:00:44 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored''

2017-07-20 08:00:44 - DEBUG UnitTestFramework: '#setup: 'native available - new peer is cached''

2017-07-20 08:00:44 - DEBUG UnitTestFramework: '#setup ok: 'native available - new peer is cached''

2017-07-20 08:00:44 - DEBUG UnitTestFramework: '#run: 'native available - new peer is cached''

2017-07-20 08:00:44 - DEBUG UnitTestFramework: '#run ok: 'native available - new peer is cached''

2017-07-20 08:00:44 - DEBUG UnitTestFramework: '#teardown: 'native available - new peer is cached''

2017-07-20 08:00:44 - DEBUG UnitTestFramework: '#teardown ok: 'native available - new peer is cached''

2017-07-20 08:00:44 - DEBUG UnitTestFramework: '#setup: 'native available - peer with same port and different generation is cached (BLUETOOTH)''

2017-07-20 08:00:44 - DEBUG UnitTestFramework: '#setup ok: 'native available - peer with same port and different generation is cached (BLUETOOTH)''

2017-07-20 08:00:44 - DEBUG UnitTestFramework: '#run: 'native available - peer with same port and different generation is cached (BLUETOOTH)''

2017-07-20 08:00:44 - DEBUG UnitTestFramework: '#run ok: 'native available - peer with same port and different generation is cached (BLUETOOTH)''

2017-07-20 08:00:44 - DEBUG UnitTestFramework: '#teardown: 'native available - peer with same port and different generation is cached (BLUETOOTH)''

2017-07-20 08:00:45 - DEBUG UnitTestFramework: '#teardown ok: 'native available - peer with same port and different generation is cached (BLUETOOTH)''

2017-07-20 08:00:45 - DEBUG UnitTestFramework: '#setup: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''

2017-07-20 08:00:45 - DEBUG UnitTestFramework: '#setup ok: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''

2017-07-20 08:00:45 - DEBUG UnitTestFramework: '#run: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''

2017-07-20 08:00:47 - DEBUG UnitTestFramework: '#run ok: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''

2017-07-20 08:00:47 - DEBUG UnitTestFramework: '#teardown: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''

2017-07-20 08:00:50 - DEBUG UnitTestFramework: '#teardown ok: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''

2017-07-20 08:00:50 - DEBUG UnitTestFramework: '#setup: 'native available - peer with greater generation is cached (MPCF)''

2017-07-20 08:00:53 - DEBUG UnitTestFramework: '#setup ok: 'native available - peer with greater generation is cached (MPCF)''

2017-07-20 08:00:53 - DEBUG UnitTestFramework: '#run: 'native available - peer with greater generation is cached (MPCF)''

2017-07-20 08:00:53 - INFO Socket: 'run skipped, test: 'native available - peer with greater generation is cached (MPCF)', event: 'run_native available - peer with greater generation is cached (MPCF)''

2017-07-20 08:00:53 - INFO Socket: 'run skipped, test: 'native available - peer with greater generation is cached (MPCF)', event: 'run_native available - peer with greater generation is cached (MPCF)''

2017-07-20 08:00:53 - INFO Socket: 'run skipped, test: 'native available - peer with greater generation is cached (MPCF)', event: 'run_native available - peer with greater generation is cached (MPCF)''

2017-07-20 08:00:53 - DEBUG UnitTestFramework: '#run ok: 'native available - peer with greater generation is cached (MPCF)''

2017-07-20 08:00:53 - DEBUG UnitTestFramework: '#teardown: 'native available - peer with greater generation is cached (MPCF)''

2017-07-20 08:00:56 - DEBUG UnitTestFramework: '#teardown ok: 'native available - peer with greater generation is cached (MPCF)''

2017-07-20 08:00:56 - DEBUG UnitTestFramework: '#setup: 'native available - peer with same or older generation is ignored (MPCF)''

2017-07-20 08:00:59 - DEBUG UnitTestFramework: '#setup ok: 'native available - peer with same or older generation is ignored (MPCF)''

2017-07-20 08:00:59 - DEBUG UnitTestFramework: '#run: 'native available - peer with same or older generation is ignored (MPCF)''

2017-07-20 08:00:59 - INFO Socket: 'run skipped, test: 'native available - peer with same or older generation is ignored (MPCF)', event: 'run_native available - peer with same or older generation is ignored (MPCF)''

2017-07-20 08:00:59 - INFO Socket: 'run skipped, test: 'native available - peer with same or older generation is ignored (MPCF)', event: 'run_native available - peer with same or older generation is ignored (MPCF)''

2017-07-20 08:01:00 - INFO Socket: 'run skipped, test: 'native available - peer with same or older generation is ignored (MPCF)', event: 'run_native available - peer with same or older generation is ignored (MPCF)''

2017-07-20 08:01:00 - DEBUG UnitTestFramework: '#run ok: 'native available - peer with same or older generation is ignored (MPCF)''

2017-07-20 08:01:00 - DEBUG UnitTestFramework: '#teardown: 'native available - peer with same or older generation is ignored (MPCF)''

2017-07-20 08:01:02 - DEBUG UnitTestFramework: '#teardown ok: 'native available - peer with same or older generation is ignored (MPCF)''

2017-07-20 08:01:02 - DEBUG UnitTestFramework: '#setup: 'native unavailable - new peer is ignored''

2017-07-20 08:01:05 - DEBUG UnitTestFramework: '#setup ok: 'native unavailable - new peer is ignored''

2017-07-20 08:01:05 - DEBUG UnitTestFramework: '#run: 'native unavailable - new peer is ignored''

2017-07-20 08:01:07 - DEBUG UnitTestFramework: '#run ok: 'native unavailable - new peer is ignored''

2017-07-20 08:01:07 - DEBUG UnitTestFramework: '#teardown: 'native unavailable - new peer is ignored''

2017-07-20 08:01:09 - DEBUG UnitTestFramework: '#teardown ok: 'native unavailable - new peer is ignored''

2017-07-20 08:01:09 - DEBUG UnitTestFramework: '#setup: 'native unavailable - cached peer is removed''

2017-07-20 08:01:11 - DEBUG UnitTestFramework: '#setup ok: 'native unavailable - cached peer is removed''

2017-07-20 08:01:11 - DEBUG UnitTestFramework: '#run: 'native unavailable - cached peer is removed''

2017-07-20 08:01:13 - DEBUG UnitTestFramework: '#run ok: 'native unavailable - cached peer is removed''

2017-07-20 08:01:13 - DEBUG UnitTestFramework: '#teardown: 'native unavailable - cached peer is removed''

2017-07-20 08:01:17 - DEBUG UnitTestFramework: '#teardown ok: 'native unavailable - cached peer is removed''

2017-07-20 08:01:17 - DEBUG UnitTestFramework: '#setup: 'networkChanged - fires peerAvailabilityChanged event for wifi peers''

2017-07-20 08:01:19 - DEBUG UnitTestFramework: '#setup ok: 'networkChanged - fires peerAvailabilityChanged event for wifi peers''

2017-07-20 08:01:19 - DEBUG UnitTestFramework: '#run: 'networkChanged - fires peerAvailabilityChanged event for wifi peers''

2017-07-20 08:01:23 - DEBUG UnitTestFramework: '#run ok: 'networkChanged - fires peerAvailabilityChanged event for wifi peers''

2017-07-20 08:01:23 - DEBUG UnitTestFramework: '#teardown: 'networkChanged - fires peerAvailabilityChanged event for wifi peers''

2017-07-20 08:01:25 - DEBUG UnitTestFramework: '#teardown ok: 'networkChanged - fires peerAvailabilityChanged event for wifi peers''

2017-07-20 08:01:25 - DEBUG UnitTestFramework: '#setup: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''

2017-07-20 08:01:27 - DEBUG UnitTestFramework: '#setup ok: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''

2017-07-20 08:01:27 - DEBUG UnitTestFramework: '#run: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''

2017-07-20 08:01:29 - DEBUG UnitTestFramework: '#run ok: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''

2017-07-20 08:01:29 - DEBUG UnitTestFramework: '#teardown: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''

2017-07-20 08:01:31 - DEBUG UnitTestFramework: '#teardown ok: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''

2017-07-20 08:01:31 - DEBUG UnitTestFramework: '#setup: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''

2017-07-20 08:01:33 - DEBUG UnitTestFramework: '#setup ok: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''

2017-07-20 08:01:33 - DEBUG UnitTestFramework: '#run: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''

2017-07-20 08:01:33 - INFO Socket: 'run skipped, test: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)', event: 'run_networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''

2017-07-20 08:01:34 - INFO Socket: 'run skipped, test: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)', event: 'run_networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''

2017-07-20 08:01:34 - INFO Socket: 'run skipped, test: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)', event: 'run_networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''

2017-07-20 08:01:34 - DEBUG UnitTestFramework: '#run ok: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''

2017-07-20 08:01:34 - DEBUG UnitTestFramework: '#teardown: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''

2017-07-20 08:01:36 - DEBUG UnitTestFramework: '#teardown ok: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''

2017-07-20 08:01:36 - DEBUG UnitTestFramework: '#setup: 'multiconnect failure - new peer is ignored (MPCF)''

2017-07-20 08:01:37 - DEBUG UnitTestFramework: '#setup ok: 'multiconnect failure - new peer is ignored (MPCF)''

2017-07-20 08:01:37 - DEBUG UnitTestFramework: '#run: 'multiconnect failure - new peer is ignored (MPCF)''

2017-07-20 08:01:37 - INFO Socket: 'run skipped, test: 'multiconnect failure - new peer is ignored (MPCF)', event: 'run_multiconnect failure - new peer is ignored (MPCF)''

2017-07-20 08:01:40 - INFO Socket: 'run skipped, test: 'multiconnect failure - new peer is ignored (MPCF)', event: 'run_multiconnect failure - new peer is ignored (MPCF)''

2017-07-20 08:01:41 - INFO Socket: 'run skipped, test: 'multiconnect failure - new peer is ignored (MPCF)', event: 'run_multiconnect failure - new peer is ignored (MPCF)''

2017-07-20 08:01:41 - DEBUG UnitTestFramework: '#run ok: 'multiconnect failure - new peer is ignored (MPCF)''

2017-07-20 08:01:41 - DEBUG UnitTestFramework: '#teardown: 'multiconnect failure - new peer is ignored (MPCF)''

2017-07-20 08:01:43 - DEBUG UnitTestFramework: '#teardown ok: 'multiconnect failure - new peer is ignored (MPCF)''

2017-07-20 08:01:43 - DEBUG UnitTestFramework: '#setup: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-07-20 08:01:46 - DEBUG UnitTestFramework: '#setup ok: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-07-20 08:01:46 - DEBUG UnitTestFramework: '#run: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-07-20 08:01:46 - INFO Socket: 'run skipped, test: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)', event: 'run_multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-07-20 08:01:47 - INFO Socket: 'run skipped, test: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)', event: 'run_multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-07-20 08:01:47 - INFO Socket: 'run skipped, test: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)', event: 'run_multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-07-20 08:01:47 - DEBUG UnitTestFramework: '#run ok: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-07-20 08:01:47 - DEBUG UnitTestFramework: '#teardown: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-07-20 08:01:50 - DEBUG UnitTestFramework: '#teardown ok: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-07-20 08:01:50 - DEBUG UnitTestFramework: '#setup: 'newAddressPort field (TCP_NATIVE)''

2017-07-20 08:01:53 - DEBUG UnitTestFramework: '#setup ok: 'newAddressPort field (TCP_NATIVE)''

2017-07-20 08:01:53 - DEBUG UnitTestFramework: '#run: 'newAddressPort field (TCP_NATIVE)''

2017-07-20 08:01:53 - DEBUG UnitTestFramework: '#run ok: 'newAddressPort field (TCP_NATIVE)''

2017-07-20 08:01:53 - DEBUG UnitTestFramework: '#teardown: 'newAddressPort field (TCP_NATIVE)''

2017-07-20 08:01:56 - DEBUG UnitTestFramework: '#teardown ok: 'newAddressPort field (TCP_NATIVE)''

2017-07-20 08:01:56 - DEBUG UnitTestFramework: '#setup: 'newAddressPort field (BLUETOOTH)''

2017-07-20 08:01:59 - DEBUG UnitTestFramework: '#setup ok: 'newAddressPort field (BLUETOOTH)''

2017-07-20 08:01:59 - DEBUG UnitTestFramework: '#run: 'newAddressPort field (BLUETOOTH)''

2017-07-20 08:01:59 - DEBUG UnitTestFramework: '#run ok: 'newAddressPort field (BLUETOOTH)''

2017-07-20 08:01:59 - DEBUG UnitTestFramework: '#teardown: 'newAddressPort field (BLUETOOTH)''

2017-07-20 08:01:59 - DEBUG UnitTestFramework: '#teardown ok: 'newAddressPort field (BLUETOOTH)''

2017-07-20 08:01:59 - DEBUG UnitTestFramework: '#setup: 'newAddressPort field (MPCF)''

2017-07-20 08:01:59 - DEBUG UnitTestFramework: '#setup ok: 'newAddressPort field (MPCF)''

2017-07-20 08:01:59 - DEBUG UnitTestFramework: '#run: 'newAddressPort field (MPCF)''

2017-07-20 08:01:59 - INFO Socket: 'run skipped, test: 'newAddressPort field (MPCF)', event: 'run_newAddressPort field (MPCF)''

2017-07-20 08:01:59 - INFO Socket: 'run skipped, test: 'newAddressPort field (MPCF)', event: 'run_newAddressPort field (MPCF)''

2017-07-20 08:01:59 - INFO Socket: 'run skipped, test: 'newAddressPort field (MPCF)', event: 'run_newAddressPort field (MPCF)''

2017-07-20 08:01:59 - DEBUG UnitTestFramework: '#run ok: 'newAddressPort field (MPCF)''

2017-07-20 08:01:59 - DEBUG UnitTestFramework: '#teardown: 'newAddressPort field (MPCF)''

2017-07-20 08:01:59 - DEBUG UnitTestFramework: '#teardown ok: 'newAddressPort field (MPCF)''

2017-07-20 08:01:59 - DEBUG UnitTestFramework: '#setup: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''

2017-07-20 08:01:59 - DEBUG UnitTestFramework: '#setup ok: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''

2017-07-20 08:01:59 - DEBUG UnitTestFramework: '#run: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''

2017-07-20 08:01:59 - DEBUG UnitTestFramework: '#run ok: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''

2017-07-20 08:01:59 - DEBUG UnitTestFramework: '#teardown: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''

2017-07-20 08:01:59 - DEBUG UnitTestFramework: '#teardown ok: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''

2017-07-20 08:01:59 - DEBUG UnitTestFramework: '#setup: '#getPeerHostInfo - error when peer has not been discovered yet''

2017-07-20 08:01:59 - DEBUG UnitTestFramework: '#setup ok: '#getPeerHostInfo - error when peer has not been discovered yet''

2017-07-20 08:01:59 - DEBUG UnitTestFramework: '#run: '#getPeerHostInfo - error when peer has not been discovered yet''

2017-07-20 08:01:59 - DEBUG UnitTestFramework: '#run ok: '#getPeerHostInfo - error when peer has not been discovered yet''

2017-07-20 08:01:59 - DEBUG UnitTestFramework: '#teardown: '#getPeerHostInfo - error when peer has not been discovered yet''

2017-07-20 08:01:59 - DEBUG UnitTestFramework: '#teardown ok: '#getPeerHostInfo - error when peer has not been discovered yet''

2017-07-20 08:01:59 - DEBUG UnitTestFramework: '#setup: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''

2017-07-20 08:01:59 - DEBUG UnitTestFramework: '#setup ok: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''

2017-07-20 08:01:59 - DEBUG UnitTestFramework: '#run: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''

2017-07-20 08:01:59 - DEBUG UnitTestFramework: '#run ok: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''

2017-07-20 08:01:59 - DEBUG UnitTestFramework: '#teardown: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''

2017-07-20 08:01:59 - DEBUG UnitTestFramework: '#teardown ok: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''

2017-07-20 08:01:59 - DEBUG UnitTestFramework: '#setup: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''

2017-07-20 08:01:59 - DEBUG UnitTestFramework: '#setup ok: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''

2017-07-20 08:01:59 - DEBUG UnitTestFramework: '#run: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''

2017-07-20 08:01:59 - INFO Socket: 'run skipped, test: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)', event: 'run_#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''

2017-07-20 08:01:59 - INFO Socket: 'run skipped, test: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)', event: 'run_#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''

2017-07-20 08:01:59 - INFO Socket: 'run skipped, test: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)', event: 'run_#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''

2017-07-20 08:01:59 - DEBUG UnitTestFramework: '#run ok: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''

2017-07-20 08:01:59 - DEBUG UnitTestFramework: '#teardown: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''

2017-07-20 08:01:59 - DEBUG UnitTestFramework: '#teardown ok: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''

2017-07-20 08:01:59 - DEBUG UnitTestFramework: '#setup: '#getPeerHostInfo - returns discovered cached wifi peer''

2017-07-20 08:02:00 - DEBUG UnitTestFramework: '#setup ok: '#getPeerHostInfo - returns discovered cached wifi peer''

2017-07-20 08:02:00 - DEBUG UnitTestFramework: '#run: '#getPeerHostInfo - returns discovered cached wifi peer''

2017-07-20 08:02:00 - DEBUG UnitTestFramework: '#run ok: '#getPeerHostInfo - returns discovered cached wifi peer''

2017-07-20 08:02:00 - DEBUG UnitTestFramework: '#teardown: '#getPeerHostInfo - returns discovered cached wifi peer''

2017-07-20 08:02:00 - DEBUG UnitTestFramework: '#teardown ok: '#getPeerHostInfo - returns discovered cached wifi peer''

2017-07-20 08:02:00 - DEBUG UnitTestFramework: '#setup: '#disconnect fails on wifi peers''

2017-07-20 08:02:00 - DEBUG UnitTestFramework: '#setup ok: '#disconnect fails on wifi peers''

2017-07-20 08:02:00 - DEBUG UnitTestFramework: '#run: '#disconnect fails on wifi peers''

2017-07-20 08:02:00 - DEBUG UnitTestFramework: '#run ok: '#disconnect fails on wifi peers''

2017-07-20 08:02:00 - DEBUG UnitTestFramework: '#teardown: '#disconnect fails on wifi peers''

2017-07-20 08:02:00 - DEBUG UnitTestFramework: '#teardown ok: '#disconnect fails on wifi peers''

2017-07-20 08:02:00 - DEBUG UnitTestFramework: '#setup: '#disconnect delegates native peers to the native wrapper''

2017-07-20 08:02:00 - DEBUG UnitTestFramework: '#setup ok: '#disconnect delegates native peers to the native wrapper''

2017-07-20 08:02:00 - DEBUG UnitTestFramework: '#run: '#disconnect delegates native peers to the native wrapper''

2017-07-20 08:02:00 - DEBUG UnitTestFramework: '#run ok: '#disconnect delegates native peers to the native wrapper''

2017-07-20 08:02:00 - DEBUG UnitTestFramework: '#teardown: '#disconnect delegates native peers to the native wrapper''

2017-07-20 08:02:00 - DEBUG UnitTestFramework: '#teardown ok: '#disconnect delegates native peers to the native wrapper''

2017-07-20 08:02:00 - DEBUG UnitTestFramework: '#setup: 'network changes emitted correctly''

2017-07-20 08:02:00 - DEBUG UnitTestFramework: '#setup ok: 'network changes emitted correctly''

2017-07-20 08:02:00 - DEBUG UnitTestFramework: '#run: 'network changes emitted correctly''

2017-07-20 08:02:00 - INFO Socket: 'run skipped, test: 'network changes emitted correctly', event: 'run_network changes emitted correctly''

2017-07-20 08:02:00 - INFO Socket: 'run skipped, test: 'network changes emitted correctly', event: 'run_network changes emitted correctly''

2017-07-20 08:02:00 - INFO Socket: 'run skipped, test: 'network changes emitted correctly', event: 'run_network changes emitted correctly''

2017-07-20 08:02:00 - DEBUG UnitTestFramework: '#run ok: 'network changes emitted correctly''

2017-07-20 08:02:00 - DEBUG UnitTestFramework: '#teardown: 'network changes emitted correctly''

2017-07-20 08:02:00 - DEBUG UnitTestFramework: '#teardown ok: 'network changes emitted correctly''

2017-07-20 08:02:00 - DEBUG UnitTestFramework: '#setup: 'network changes not emitted in started state''

2017-07-20 08:02:00 - DEBUG UnitTestFramework: '#setup ok: 'network changes not emitted in started state''

2017-07-20 08:02:00 - DEBUG UnitTestFramework: '#run: 'network changes not emitted in started state''

2017-07-20 08:02:00 - INFO Socket: 'run skipped, test: 'network changes not emitted in started state', event: 'run_network changes not emitted in started state''

2017-07-20 08:02:00 - INFO Socket: 'run skipped, test: 'network changes not emitted in started state', event: 'run_network changes not emitted in started state''

2017-07-20 08:02:00 - INFO Socket: 'run skipped, test: 'network changes not emitted in started state', event: 'run_network changes not emitted in started state''

2017-07-20 08:02:00 - DEBUG UnitTestFramework: '#run ok: 'network changes not emitted in started state''

2017-07-20 08:02:00 - DEBUG UnitTestFramework: '#teardown: 'network changes not emitted in started state''

2017-07-20 08:02:00 - DEBUG UnitTestFramework: '#teardown ok: 'network changes not emitted in started state''

2017-07-20 08:02:00 - DEBUG UnitTestFramework: '#setup: 'network changes not emitted in stopped state''

2017-07-20 08:02:00 - DEBUG UnitTestFramework: '#setup ok: 'network changes not emitted in stopped state''

2017-07-20 08:02:00 - DEBUG UnitTestFramework: '#run: 'network changes not emitted in stopped state''

2017-07-20 08:02:00 - INFO Socket: 'run skipped, test: 'network changes not emitted in stopped state', event: 'run_network changes not emitted in stopped state''

2017-07-20 08:02:00 - INFO Socket: 'run skipped, test: 'network changes not emitted in stopped state', event: 'run_network changes not emitted in stopped state''

2017-07-20 08:02:00 - INFO Socket: 'run skipped, test: 'network changes not emitted in stopped state', event: 'run_network changes not emitted in stopped state''

2017-07-20 08:02:00 - DEBUG UnitTestFramework: '#run ok: 'network changes not emitted in stopped state''

2017-07-20 08:02:00 - DEBUG UnitTestFramework: '#teardown: 'network changes not emitted in stopped state''

2017-07-20 08:02:00 - DEBUG UnitTestFramework: '#teardown ok: 'network changes not emitted in stopped state''

2017-07-20 08:02:00 - DEBUG UnitTestFramework: '#setup: 'We properly fire peer unavailable and then available when connection fails on Android''

2017-07-20 08:02:00 - DEBUG UnitTestFramework: '#setup ok: 'We properly fire peer unavailable and then available when connection fails on Android''

2017-07-20 08:02:00 - DEBUG UnitTestFramework: '#run: 'We properly fire peer unavailable and then available when connection fails on Android''

2017-07-20 08:02:01 - DEBUG UnitTestFramework: '#run ok: 'We properly fire peer unavailable and then available when connection fails on Android''

2017-07-20 08:02:01 - DEBUG UnitTestFramework: '#teardown: 'We properly fire peer unavailable and then available when connection fails on Android''

2017-07-20 08:02:02 - DEBUG UnitTestFramework: '#teardown ok: 'We properly fire peer unavailable and then available when connection fails on Android''

2017-07-20 08:02:02 - DEBUG UnitTestFramework: '#setup: 'We properly fire peer unavailable and then available when connection fails on iOS''

2017-07-20 08:02:02 - DEBUG UnitTestFramework: '#setup ok: 'We properly fire peer unavailable and then available when connection fails on iOS''

2017-07-20 08:02:02 - DEBUG UnitTestFramework: '#run: 'We properly fire peer unavailable and then available when connection fails on iOS''

2017-07-20 08:02:02 - INFO Socket: 'run skipped, test: 'We properly fire peer unavailable and then available when connection fails on iOS', event: 'run_We properly fire peer unavailable and then available when connection fails on iOS''

2017-07-20 08:02:02 - INFO Socket: 'run skipped, test: 'We properly fire peer unavailable and then available when connection fails on iOS', event: 'run_We properly fire peer unavailable and then available when connection fails on iOS''

2017-07-20 08:02:02 - INFO Socket: 'run skipped, test: 'We properly fire peer unavailable and then available when connection fails on iOS', event: 'run_We properly fire peer unavailable and then available when connection fails on iOS''

2017-07-20 08:02:02 - DEBUG UnitTestFramework: '#run ok: 'We properly fire peer unavailable and then available when connection fails on iOS''

2017-07-20 08:02:02 - DEBUG UnitTestFramework: '#teardown: 'We properly fire peer unavailable and then available when connection fails on iOS''

2017-07-20 08:02:02 - DEBUG UnitTestFramework: '#teardown ok: 'We properly fire peer unavailable and then available when connection fails on iOS''

2017-07-20 08:02:02 - DEBUG UnitTestFramework: '#setup: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''

2017-07-20 08:02:02 - DEBUG UnitTestFramework: '#setup ok: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''

2017-07-20 08:02:02 - DEBUG UnitTestFramework: '#run: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''

2017-07-20 08:02:03 - DEBUG UnitTestFramework: '#run ok: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''

2017-07-20 08:02:03 - DEBUG UnitTestFramework: '#teardown: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''

2017-07-20 08:02:04 - DEBUG UnitTestFramework: '#teardown ok: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''

2017-07-20 08:02:04 - DEBUG UnitTestFramework: '#setup: 'does not fire duplicate events after peer listener recreation''

2017-07-20 08:02:04 - DEBUG UnitTestFramework: '#setup ok: 'does not fire duplicate events after peer listener recreation''

2017-07-20 08:02:04 - DEBUG UnitTestFramework: '#run: 'does not fire duplicate events after peer listener recreation''

2017-07-20 08:02:07 - DEBUG UnitTestFramework: '#run ok: 'does not fire duplicate events after peer listener recreation''

2017-07-20 08:02:07 - DEBUG UnitTestFramework: '#teardown: 'does not fire duplicate events after peer listener recreation''

2017-07-20 08:02:10 - DEBUG UnitTestFramework: '#teardown ok: 'does not fire duplicate events after peer listener recreation''

2017-07-20 08:02:10 - DEBUG UnitTestFramework: '#setup: '#stop should change peers''

2017-07-20 08:02:13 - DEBUG UnitTestFramework: '#setup ok: '#stop should change peers''

2017-07-20 08:02:13 - DEBUG UnitTestFramework: '#run: '#stop should change peers''

2017-07-20 08:02:16 - DEBUG UnitTestFramework: '#run ok: '#stop should change peers''

2017-07-20 08:02:16 - DEBUG UnitTestFramework: '#teardown: '#stop should change peers''

2017-07-20 08:02:18 - DEBUG UnitTestFramework: '#teardown ok: '#stop should change peers''

2017-07-20 08:02:18 - DEBUG UnitTestFramework: '#setup: 'If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted''

2017-07-20 08:02:20 - DEBUG UnitTestFramework: '#setup ok: 'If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted''

2017-07-20 08:02:20 - DEBUG UnitTestFramework: '#run: 'If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted''

2017-07-20 08:02:22 - DEBUG UnitTestFramework: '#run ok: 'If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted''

2017-07-20 08:02:22 - DEBUG UnitTestFramework: '#teardown: 'If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted''

2017-07-20 08:02:24 - DEBUG UnitTestFramework: '#teardown ok: 'If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted''

2017-07-20 08:02:24 - DEBUG UnitTestFramework: '#setup: 'peer should be found once after listening and discovery started''

2017-07-20 08:02:25 - DEBUG UnitTestFramework: '#setup ok: 'peer should be found once after listening and discovery started''

2017-07-20 08:02:25 - DEBUG UnitTestFramework: '#run: 'peer should be found once after listening and discovery started''

2017-07-20 08:02:25 - INFO Socket: 'run skipped, test: 'peer should be found once after listening and discovery started', event: 'run_peer should be found once after listening and discovery started''

2017-07-20 08:02:27 - INFO Socket: 'run skipped, test: 'peer should be found once after listening and discovery started', event: 'run_peer should be found once after listening and discovery started''

2017-07-20 08:02:27 - INFO Socket: 'run skipped, test: 'peer should be found once after listening and discovery started', event: 'run_peer should be found once after listening and discovery started''

2017-07-20 08:02:27 - DEBUG UnitTestFramework: '#run ok: 'peer should be found once after listening and discovery started''

2017-07-20 08:02:27 - DEBUG UnitTestFramework: '#teardown: 'peer should be found once after listening and discovery started''

2017-07-20 08:02:30 - DEBUG UnitTestFramework: '#teardown ok: 'peer should be found once after listening and discovery started''

2017-07-20 08:02:30 - DEBUG UnitTestFramework: '#setup: 'can get data from all participants''

2017-07-20 08:02:31 - DEBUG UnitTestFramework: '#setup ok: 'can get data from all participants''

2017-07-20 08:02:31 - DEBUG UnitTestFramework: '#run: 'can get data from all participants''

2017-07-20 08:02:46 - DEBUG UnitTestFramework: '#run ok: 'can get data from all participants''

2017-07-20 08:02:46 - DEBUG UnitTestFramework: '#teardown: 'can get data from all participants''

2017-07-20 08:02:49 - DEBUG UnitTestFramework: '#teardown ok: 'can get data from all participants''

2017-07-20 08:02:49 - DEBUG UnitTestFramework: '#setup: 'test for data corruption''

2017-07-20 08:02:49 - DEBUG UnitTestFramework: '#setup ok: 'test for data corruption''

2017-07-20 08:02:49 - DEBUG UnitTestFramework: '#run: 'test for data corruption''

2017-07-20 08:02:49 - INFO Socket: 'run skipped, test: 'test for data corruption', event: 'run_test for data corruption''

2017-07-20 08:02:49 - INFO Socket: 'run skipped, test: 'test for data corruption', event: 'run_test for data corruption''

2017-07-20 08:02:49 - INFO Socket: 'run skipped, test: 'test for data corruption', event: 'run_test for data corruption''

2017-07-20 08:02:49 - DEBUG UnitTestFramework: '#run ok: 'test for data corruption''

2017-07-20 08:02:49 - DEBUG UnitTestFramework: '#teardown: 'test for data corruption''

2017-07-20 08:02:49 - DEBUG UnitTestFramework: '#teardown ok: 'test for data corruption''

2017-07-20 08:02:49 - DEBUG UnitTestFramework: '#setup: '#testThaliPeerAction - test getters''

2017-07-20 08:02:49 - DEBUG UnitTestFramework: '#setup ok: '#testThaliPeerAction - test getters''

2017-07-20 08:02:49 - DEBUG UnitTestFramework: '#run: '#testThaliPeerAction - test getters''

2017-07-20 08:02:49 - DEBUG UnitTestFramework: '#run ok: '#testThaliPeerAction - test getters''

2017-07-20 08:02:49 - DEBUG UnitTestFramework: '#teardown: '#testThaliPeerAction - test getters''

2017-07-20 08:02:49 - DEBUG UnitTestFramework: '#teardown ok: '#testThaliPeerAction - test getters''

2017-07-20 08:02:49 - DEBUG UnitTestFramework: '#setup: '#testThaliPeerAction - start and kill''

2017-07-20 08:02:49 - DEBUG UnitTestFramework: '#setup ok: '#testThaliPeerAction - start and kill''

2017-07-20 08:02:49 - DEBUG UnitTestFramework: '#run: '#testThaliPeerAction - start and kill''

2017-07-20 08:02:49 - DEBUG UnitTestFramework: '#run ok: '#testThaliPeerAction - start and kill''

2017-07-20 08:02:49 - DEBUG UnitTestFramework: '#teardown: '#testThaliPeerAction - start and kill''

2017-07-20 08:02:49 - DEBUG UnitTestFramework: '#teardown ok: '#testThaliPeerAction - start and kill''

2017-07-20 08:02:49 - DEBUG UnitTestFramework: '#setup: '#testThaliPeerAction - double start''

2017-07-20 08:02:49 - DEBUG UnitTestFramework: '#setup ok: '#testThaliPeerAction - double start''

2017-07-20 08:02:49 - DEBUG UnitTestFramework: '#run: '#testThaliPeerAction - double start''

2017-07-20 08:02:50 - DEBUG UnitTestFramework: '#run ok: '#testThaliPeerAction - double start''

2017-07-20 08:02:50 - DEBUG UnitTestFramework: '#teardown: '#testThaliPeerAction - double start''

2017-07-20 08:02:50 - DEBUG UnitTestFramework: '#teardown ok: '#testThaliPeerAction - double start''

2017-07-20 08:02:50 - DEBUG UnitTestFramework: '#setup: '#testThaliPeerAction - start after kill''

2017-07-20 08:02:50 - DEBUG UnitTestFramework: '#setup ok: '#testThaliPeerAction - start after kill''

2017-07-20 08:02:50 - DEBUG UnitTestFramework: '#run: '#testThaliPeerAction - start after kill''

2017-07-20 08:02:50 - DEBUG UnitTestFramework: '#run ok: '#testThaliPeerAction - start after kill''

2017-07-20 08:02:50 - DEBUG UnitTestFramework: '#teardown: '#testThaliPeerAction - start after kill''

2017-07-20 08:02:50 - DEBUG UnitTestFramework: '#teardown ok: '#testThaliPeerAction - start after kill''

2017-07-20 08:02:50 - DEBUG UnitTestFramework: '#setup: '#testThaliPeerAction - make sure ids are unique''

2017-07-20 08:02:50 - DEBUG UnitTestFramework: '#setup ok: '#testThaliPeerAction - make sure ids are unique''

2017-07-20 08:02:50 - DEBUG UnitTestFramework: '#run: '#testThaliPeerAction - make sure ids are unique''

2017-07-20 08:02:50 - DEBUG UnitTestFramework: '#run ok: '#testThaliPeerAction - make sure ids are unique''

2017-07-20 08:02:50 - DEBUG UnitTestFramework: '#teardown: '#testThaliPeerAction - make sure ids are unique''

2017-07-20 08:02:50 - DEBUG UnitTestFramework: '#teardown ok: '#testThaliPeerAction - make sure ids are unique''

2017-07-20 08:02:50 - DEBUG UnitTestFramework: '#setup: '#testThaliPeerAction - check that forever agent can be destroyed''

2017-07-20 08:02:50 - DEBUG UnitTestFramework: '#setup ok: '#testThaliPeerAction - check that forever agent can be destroyed''

2017-07-20 08:02:50 - DEBUG UnitTestFramework: '#run: '#testThaliPeerAction - check that forever agent can be destroyed''

2017-07-20 08:02:50 - DEBUG UnitTestFramework: '#run ok: '#testThaliPeerAction - check that forever agent can be destroyed''

2017-07-20 08:02:50 - DEBUG UnitTestFramework: '#teardown: '#testThaliPeerAction - check that forever agent can be destroyed''

2017-07-20 08:02:50 - DEBUG UnitTestFramework: '#teardown ok: '#testThaliPeerAction - check that forever agent can be destroyed''

2017-07-20 08:02:50 - DEBUG UnitTestFramework: '#setup: 'Test PeerDictionary basic functionality''

2017-07-20 08:02:50 - DEBUG UnitTestFramework: '#setup ok: 'Test PeerDictionary basic functionality''

2017-07-20 08:02:50 - DEBUG UnitTestFramework: '#run: 'Test PeerDictionary basic functionality''

2017-07-20 08:02:50 - DEBUG UnitTestFramework: '#run ok: 'Test PeerDictionary basic functionality''

2017-07-20 08:02:50 - DEBUG UnitTestFramework: '#teardown: 'Test PeerDictionary basic functionality''

2017-07-20 08:02:50 - DEBUG UnitTestFramework: '#teardown ok: 'Test PeerDictionary basic functionality''

2017-07-20 08:02:50 - DEBUG UnitTestFramework: '#setup: 'Test PeerDictionary with multiple entries.''

2017-07-20 08:02:50 - DEBUG UnitTestFramework: '#setup ok: 'Test PeerDictionary with multiple entries.''

2017-07-20 08:02:50 - DEBUG UnitTestFramework: '#run: 'Test PeerDictionary with multiple entries.''

2017-07-20 08:02:51 - DEBUG UnitTestFramework: '#run ok: 'Test PeerDictionary with multiple entries.''

2017-07-20 08:02:51 - DEBUG UnitTestFramework: '#teardown: 'Test PeerDictionary with multiple entries.''

2017-07-20 08:02:51 - DEBUG UnitTestFramework: '#teardown ok: 'Test PeerDictionary with multiple entries.''

2017-07-20 08:02:51 - DEBUG UnitTestFramework: '#setup: 'RESOLVED entries are removed before WAITING state entry.''

2017-07-20 08:02:51 - DEBUG UnitTestFramework: '#setup ok: 'RESOLVED entries are removed before WAITING state entry.''

2017-07-20 08:02:51 - DEBUG UnitTestFramework: '#run: 'RESOLVED entries are removed before WAITING state entry.''

2017-07-20 08:02:52 - DEBUG UnitTestFramework: '#run ok: 'RESOLVED entries are removed before WAITING state entry.''

2017-07-20 08:02:52 - DEBUG UnitTestFramework: '#teardown: 'RESOLVED entries are removed before WAITING state entry.''

2017-07-20 08:02:52 - DEBUG UnitTestFramework: '#teardown ok: 'RESOLVED entries are removed before WAITING state entry.''

2017-07-20 08:02:52 - DEBUG UnitTestFramework: '#setup: 'WAITING entries are removed before CONTROLLED_BY_POOL state entry.''

2017-07-20 08:02:52 - DEBUG UnitTestFramework: '#setup ok: 'WAITING entries are removed before CONTROLLED_BY_POOL state entry.''

2017-07-20 08:02:52 - DEBUG UnitTestFramework: '#run: 'WAITING entries are removed before CONTROLLED_BY_POOL state entry.''

2017-07-20 08:02:53 - DEBUG UnitTestFramework: '#run ok: 'WAITING entries are removed before CONTROLLED_BY_POOL state entry.''

2017-07-20 08:02:53 - DEBUG UnitTestFramework: '#teardown: 'WAITING entries are removed before CONTROLLED_BY_POOL state entry.''

2017-07-20 08:02:53 - DEBUG UnitTestFramework: '#teardown ok: 'WAITING entries are removed before CONTROLLED_BY_POOL state entry.''

2017-07-20 08:02:53 - DEBUG UnitTestFramework: '#setup: 'When CONTROLLED_BY_POOL entry is removed and kill is called.''

2017-07-20 08:02:53 - DEBUG UnitTestFramework: '#setup ok: 'When CONTROLLED_BY_POOL entry is removed and kill is called.''

2017-07-20 08:02:53 - DEBUG UnitTestFramework: '#run: 'When CONTROLLED_BY_POOL entry is removed and kill is called.''

2017-07-20 08:02:53 - DEBUG UnitTestFramework: '#run ok: 'When CONTROLLED_BY_POOL entry is removed and kill is called.''

2017-07-20 08:02:53 - DEBUG UnitTestFramework: '#teardown: 'When CONTROLLED_BY_POOL entry is removed and kill is called.''

2017-07-20 08:02:56 - DEBUG UnitTestFramework: '#teardown ok: 'When CONTROLLED_BY_POOL entry is removed and kill is called.''

2017-07-20 08:02:56 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolDefault - single action''

2017-07-20 08:02:59 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolDefault - single action''

2017-07-20 08:02:59 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolDefault - single action''

2017-07-20 08:03:00 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolDefault - single action''

2017-07-20 08:03:00 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolDefault - single action''

2017-07-20 08:03:02 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolDefault - single action''

2017-07-20 08:03:02 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolDefault - multiple actions''

2017-07-20 08:03:05 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolDefault - multiple actions''

2017-07-20 08:03:05 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolDefault - multiple actions''

2017-07-20 08:03:07 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolDefault - multiple actions''

2017-07-20 08:03:07 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolDefault - multiple actions''

2017-07-20 08:03:08 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolDefault - multiple actions''

2017-07-20 08:03:08 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolDefault - PSK Pool works''

2017-07-20 08:03:11 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolDefault - PSK Pool works''

2017-07-20 08:03:11 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolDefault - PSK Pool works''

2017-07-20 08:03:14 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolDefault - PSK Pool works''

2017-07-20 08:03:14 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolDefault - PSK Pool works''

2017-07-20 08:03:14 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolDefault - PSK Pool works''

2017-07-20 08:03:14 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolDefault - stop''

2017-07-20 08:03:14 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolDefault - stop''

2017-07-20 08:03:14 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolDefault - stop''

2017-07-20 08:03:14 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolDefault - stop''

2017-07-20 08:03:14 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolDefault - stop''

2017-07-20 08:03:14 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolDefault - stop''

2017-07-20 08:03:14 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolInterface - make sure that start verifies queue length''

2017-07-20 08:03:14 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolInterface - make sure that start verifies queue length''

2017-07-20 08:03:14 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolInterface - make sure that start verifies queue length''

2017-07-20 08:03:15 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolInterface - make sure that start verifies queue length''

2017-07-20 08:03:15 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolInterface - make sure that start verifies queue length''

2017-07-20 08:03:15 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolInterface - make sure that start verifies queue length''

2017-07-20 08:03:15 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolInterface - bad enqueues''

2017-07-20 08:03:15 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolInterface - bad enqueues''

2017-07-20 08:03:15 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolInterface - bad enqueues''

2017-07-20 08:03:15 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolInterface - bad enqueues''

2017-07-20 08:03:15 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolInterface - bad enqueues''

2017-07-20 08:03:15 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolInterface - bad enqueues''

2017-07-20 08:03:15 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolInterface - do not allow same object type''

2017-07-20 08:03:15 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolInterface - do not allow same object type''

2017-07-20 08:03:15 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolInterface - do not allow same object type''

2017-07-20 08:03:15 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolInterface - do not allow same object type''

2017-07-20 08:03:15 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolInterface - do not allow same object type''

2017-07-20 08:03:15 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolInterface - do not allow same object type''

2017-07-20 08:03:15 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolInterface - make sure we catch kill and dequeue''

2017-07-20 08:03:15 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolInterface - make sure we catch kill and dequeue''

2017-07-20 08:03:15 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolInterface - make sure we catch kill and dequeue''

2017-07-20 08:03:16 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolInterface - make sure we catch kill and dequeue''

2017-07-20 08:03:16 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolInterface - make sure we catch kill and dequeue''

2017-07-20 08:03:18 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolInterface - make sure we catch kill and dequeue''

2017-07-20 08:03:18 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent''

2017-07-20 08:03:23 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent''

2017-07-20 08:03:23 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent''

2017-07-20 08:03:25 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent''

2017-07-20 08:03:25 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent''

2017-07-20 08:03:27 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent''

2017-07-20 08:03:27 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolInterface - make sure that stop removes all actions''

2017-07-20 08:03:29 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolInterface - make sure that stop removes all actions''

2017-07-20 08:03:29 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolInterface - make sure that stop removes all actions''

2017-07-20 08:03:30 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolInterface - make sure that stop removes all actions''

2017-07-20 08:03:30 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolInterface - make sure that stop removes all actions''

2017-07-20 08:03:33 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolInterface - make sure that stop removes all actions''

2017-07-20 08:03:33 - DEBUG UnitTestFramework: '#setup: 'We reject unrecognized connection type''

2017-07-20 08:03:35 - DEBUG UnitTestFramework: '#setup ok: 'We reject unrecognized connection type''

2017-07-20 08:03:35 - DEBUG UnitTestFramework: '#run: 'We reject unrecognized connection type''

2017-07-20 08:03:36 - DEBUG UnitTestFramework: '#run ok: 'We reject unrecognized connection type''

2017-07-20 08:03:36 - DEBUG UnitTestFramework: '#teardown: 'We reject unrecognized connection type''

2017-07-20 08:03:39 - DEBUG UnitTestFramework: '#teardown ok: 'We reject unrecognized connection type''

2017-07-20 08:03:39 - DEBUG UnitTestFramework: '#setup: 'We reject unrecognized action type''

2017-07-20 08:03:41 - DEBUG UnitTestFramework: '#setup ok: 'We reject unrecognized action type''

2017-07-20 08:03:41 - DEBUG UnitTestFramework: '#run: 'We reject unrecognized action type''

2017-07-20 08:03:44 - DEBUG UnitTestFramework: '#run ok: 'We reject unrecognized action type''

2017-07-20 08:03:44 - DEBUG UnitTestFramework: '#teardown: 'We reject unrecognized action type''

2017-07-20 08:03:47 - DEBUG UnitTestFramework: '#teardown ok: 'We reject unrecognized action type''

2017-07-20 08:03:47 - DEBUG UnitTestFramework: '#setup: 'One action on bluetooth''

2017-07-20 08:03:48 - DEBUG UnitTestFramework: '#setup ok: 'One action on bluetooth''

2017-07-20 08:03:48 - DEBUG UnitTestFramework: '#run: 'One action on bluetooth''

2017-07-20 08:03:50 - DEBUG UnitTestFramework: '#run ok: 'One action on bluetooth''

2017-07-20 08:03:50 - DEBUG UnitTestFramework: '#teardown: 'One action on bluetooth''

2017-07-20 08:03:53 - DEBUG UnitTestFramework: '#teardown ok: 'One action on bluetooth''

2017-07-20 08:03:53 - DEBUG UnitTestFramework: '#setup: 'Two notification actions''

2017-07-20 08:03:55 - DEBUG UnitTestFramework: '#setup ok: 'Two notification actions''

2017-07-20 08:03:55 - DEBUG UnitTestFramework: '#run: 'Two notification actions''

2017-07-20 08:03:56 - DEBUG UnitTestFramework: '#run ok: 'Two notification actions''

2017-07-20 08:03:56 - DEBUG UnitTestFramework: '#teardown: 'Two notification actions''

2017-07-20 08:03:59 - DEBUG UnitTestFramework: '#teardown ok: 'Two notification actions''

2017-07-20 08:03:59 - DEBUG UnitTestFramework: '#setup: 'replicateThroughProblems''

2017-07-20 08:04:01 - DEBUG UnitTestFramework: '#setup ok: 'replicateThroughProblems''

2017-07-20 08:04:01 - DEBUG UnitTestFramework: '#run: 'replicateThroughProblems''

2017-07-20 08:04:02 - DEBUG UnitTestFramework: '#run ok: 'replicateThroughProblems''

2017-07-20 08:04:02 - DEBUG UnitTestFramework: '#teardown: 'replicateThroughProblems''

2017-07-20 08:04:05 - DEBUG UnitTestFramework: '#teardown ok: 'replicateThroughProblems''

2017-07-20 08:04:05 - DEBUG UnitTestFramework: '#setup: 'Replication goes first''

2017-07-20 08:04:07 - DEBUG UnitTestFramework: '#setup ok: 'Replication goes first''

2017-07-20 08:04:07 - DEBUG UnitTestFramework: '#run: 'Replication goes first''

2017-07-20 08:04:10 - DEBUG UnitTestFramework: '#run ok: 'Replication goes first''

2017-07-20 08:04:10 - DEBUG UnitTestFramework: '#teardown: 'Replication goes first''

2017-07-20 08:04:11 - DEBUG UnitTestFramework: '#teardown ok: 'Replication goes first''

2017-07-20 08:04:11 - DEBUG UnitTestFramework: '#setup: 'wifi allows many parallel non-replication actions''

2017-07-20 08:04:14 - DEBUG UnitTestFramework: '#setup ok: 'wifi allows many parallel non-replication actions''

2017-07-20 08:04:14 - DEBUG UnitTestFramework: '#run: 'wifi allows many parallel non-replication actions''

2017-07-20 08:04:17 - DEBUG UnitTestFramework: '#run ok: 'wifi allows many parallel non-replication actions''

2017-07-20 08:04:17 - DEBUG UnitTestFramework: '#teardown: 'wifi allows many parallel non-replication actions''

2017-07-20 08:04:20 - DEBUG UnitTestFramework: '#teardown ok: 'wifi allows many parallel non-replication actions''

2017-07-20 08:04:20 - DEBUG UnitTestFramework: '#setup: 'wifi allows no more than 2 simultaneous replication actions for same peerID''

2017-07-20 08:04:20 - DEBUG UnitTestFramework: '#setup ok: 'wifi allows no more than 2 simultaneous replication actions for same peerID''

2017-07-20 08:04:20 - DEBUG UnitTestFramework: '#run: 'wifi allows no more than 2 simultaneous replication actions for same peerID''

2017-07-20 08:04:23 - DEBUG UnitTestFramework: '#run ok: 'wifi allows no more than 2 simultaneous replication actions for same peerID''

2017-07-20 08:04:23 - DEBUG UnitTestFramework: '#teardown: 'wifi allows no more than 2 simultaneous replication actions for same peerID''

2017-07-20 08:04:26 - DEBUG UnitTestFramework: '#teardown ok: 'wifi allows no more than 2 simultaneous replication actions for same peerID''

2017-07-20 08:04:26 - DEBUG UnitTestFramework: '#setup: 'Client to server request coordinated''

2017-07-20 08:04:27 - DEBUG UnitTestFramework: '#setup ok: 'Client to server request coordinated''

2017-07-20 08:04:27 - DEBUG UnitTestFramework: '#run: 'Client to server request coordinated''

2017-07-20 08:04:27 - INFO Socket: 'run skipped, test: 'Client to server request coordinated', event: 'run_Client to server request coordinated''

2017-07-20 08:04:29 - INFO Socket: 'run skipped, test: 'Client to server request coordinated', event: 'run_Client to server request coordinated''

2017-07-20 08:04:29 - INFO Socket: 'run skipped, test: 'Client to server request coordinated', event: 'run_Client to server request coordinated''

2017-07-20 08:04:29 - DEBUG UnitTestFramework: '#run ok: 'Client to server request coordinated''

2017-07-20 08:04:29 - DEBUG UnitTestFramework: '#teardown: 'Client to server request coordinated''

2017-07-20 08:04:30 - DEBUG UnitTestFramework: '#teardown ok: 'Client to server request coordinated''

2017-07-20 08:04:30 - DEBUG UnitTestFramework: '#setup: 'Test BEACONS_RETRIEVED_AND_PARSED locally''

2017-07-20 08:04:32 - DEBUG UnitTestFramework: '#setup ok: 'Test BEACONS_RETRIEVED_AND_PARSED locally''

2017-07-20 08:04:32 - DEBUG UnitTestFramework: '#run: 'Test BEACONS_RETRIEVED_AND_PARSED locally''

2017-07-20 08:04:35 - DEBUG UnitTestFramework: '#run ok: 'Test BEACONS_RETRIEVED_AND_PARSED locally''

2017-07-20 08:04:35 - DEBUG UnitTestFramework: '#teardown: 'Test BEACONS_RETRIEVED_AND_PARSED locally''

2017-07-20 08:04:36 - DEBUG UnitTestFramework: '#teardown ok: 'Test BEACONS_RETRIEVED_AND_PARSED locally''

2017-07-20 08:04:36 - DEBUG UnitTestFramework: '#setup: 'Test HTTP_BAD_RESPONSE locally''

2017-07-20 08:04:38 - DEBUG UnitTestFramework: '#setup ok: 'Test HTTP_BAD_RESPONSE locally''

2017-07-20 08:04:38 - DEBUG UnitTestFramework: '#run: 'Test HTTP_BAD_RESPONSE locally''

2017-07-20 08:04:38 - INFO Socket: 'run skipped, test: 'Test HTTP_BAD_RESPONSE locally', event: 'run_Test HTTP_BAD_RESPONSE locally''

2017-07-20 08:04:39 - INFO Socket: 'run skipped, test: 'Test HTTP_BAD_RESPONSE locally', event: 'run_Test HTTP_BAD_RESPONSE locally''

2017-07-20 08:04:41 - INFO Socket: 'run skipped, test: 'Test HTTP_BAD_RESPONSE locally', event: 'run_Test HTTP_BAD_RESPONSE locally''

2017-07-20 08:04:41 - DEBUG UnitTestFramework: '#run ok: 'Test HTTP_BAD_RESPONSE locally''

2017-07-20 08:04:41 - DEBUG UnitTestFramework: '#teardown: 'Test HTTP_BAD_RESPONSE locally''

2017-07-20 08:04:42 - DEBUG UnitTestFramework: '#teardown ok: 'Test HTTP_BAD_RESPONSE locally''

2017-07-20 08:04:42 - DEBUG UnitTestFramework: '#setup: 'Test NETWORK_PROBLEM locally''

2017-07-20 08:04:44 - DEBUG UnitTestFramework: '#setup ok: 'Test NETWORK_PROBLEM locally''

2017-07-20 08:04:44 - DEBUG UnitTestFramework: '#run: 'Test NETWORK_PROBLEM locally''

2017-07-20 08:04:45 - DEBUG UnitTestFramework: '#run ok: 'Test NETWORK_PROBLEM locally''

2017-07-20 08:04:45 - DEBUG UnitTestFramework: '#teardown: 'Test NETWORK_PROBLEM locally''

2017-07-20 08:04:48 - DEBUG UnitTestFramework: '#teardown ok: 'Test NETWORK_PROBLEM locally''

2017-07-20 08:04:48 - DEBUG UnitTestFramework: '#setup: 'Action fails when getPeerHostInfo fails''

2017-07-20 08:04:50 - DEBUG UnitTestFramework: '#setup ok: 'Action fails when getPeerHostInfo fails''

2017-07-20 08:04:50 - DEBUG UnitTestFramework: '#run: 'Action fails when getPeerHostInfo fails''

2017-07-20 08:04:53 - DEBUG UnitTestFramework: '#run ok: 'Action fails when getPeerHostInfo fails''

2017-07-20 08:04:53 - DEBUG UnitTestFramework: '#teardown: 'Action fails when getPeerHostInfo fails''

2017-07-20 08:04:54 - DEBUG UnitTestFramework: '#teardown ok: 'Action fails when getPeerHostInfo fails''

2017-07-20 08:04:54 - DEBUG UnitTestFramework: '#setup: 'Call the start two times''

2017-07-20 08:04:55 - DEBUG UnitTestFramework: '#setup ok: 'Call the start two times''

2017-07-20 08:04:55 - DEBUG UnitTestFramework: '#run: 'Call the start two times''

2017-07-20 08:04:57 - DEBUG UnitTestFramework: '#run ok: 'Call the start two times''

2017-07-20 08:04:57 - DEBUG UnitTestFramework: '#teardown: 'Call the start two times''

2017-07-20 08:05:00 - DEBUG UnitTestFramework: '#teardown ok: 'Call the start two times''

2017-07-20 08:05:00 - DEBUG UnitTestFramework: '#setup: 'Call the kill before calling the start''

2017-07-20 08:05:01 - DEBUG UnitTestFramework: '#setup ok: 'Call the kill before calling the start''

2017-07-20 08:05:01 - DEBUG UnitTestFramework: '#run: 'Call the kill before calling the start''

2017-07-20 08:05:03 - DEBUG UnitTestFramework: '#run ok: 'Call the kill before calling the start''

2017-07-20 08:05:03 - DEBUG UnitTestFramework: '#teardown: 'Call the kill before calling the start''

2017-07-20 08:05:04 - DEBUG UnitTestFramework: '#teardown ok: 'Call the kill before calling the start''

2017-07-20 08:05:04 - DEBUG UnitTestFramework: '#setup: 'Call the kill immediately after the start''

2017-07-20 08:05:07 - DEBUG UnitTestFramework: '#setup ok: 'Call the kill immediately after the start''

2017-07-20 08:05:07 - DEBUG UnitTestFramework: '#run: 'Call the kill immediately after the start''

2017-07-20 08:05:07 - DEBUG UnitTestFramework: '#run ok: 'Call the kill immediately after the start''

2017-07-20 08:05:07 - DEBUG UnitTestFramework: '#teardown: 'Call the kill immediately after the start''

2017-07-20 08:05:10 - DEBUG UnitTestFramework: '#teardown ok: 'Call the kill immediately after the start''

2017-07-20 08:05:10 - DEBUG UnitTestFramework: '#setup: 'Call the kill while waiting a response from the server''

2017-07-20 08:05:11 - DEBUG UnitTestFramework: '#setup ok: 'Call the kill while waiting a response from the server''

2017-07-20 08:05:11 - DEBUG UnitTestFramework: '#run: 'Call the kill while waiting a response from the server''

2017-07-20 08:05:15 - DEBUG UnitTestFramework: '#run ok: 'Call the kill while waiting a response from the server''

2017-07-20 08:05:15 - DEBUG UnitTestFramework: '#teardown: 'Call the kill while waiting a response from the server''

2017-07-20 08:05:18 - DEBUG UnitTestFramework: '#teardown ok: 'Call the kill while waiting a response from the server''

2017-07-20 08:05:18 - DEBUG UnitTestFramework: '#setup: 'Test to exceed the max content size locally''

2017-07-20 08:05:19 - DEBUG UnitTestFramework: '#setup ok: 'Test to exceed the max content size locally''

2017-07-20 08:05:19 - DEBUG UnitTestFramework: '#run: 'Test to exceed the max content size locally''

2017-07-20 08:05:21 - DEBUG UnitTestFramework: '#run ok: 'Test to exceed the max content size locally''

2017-07-20 08:05:21 - DEBUG UnitTestFramework: '#teardown: 'Test to exceed the max content size locally''

2017-07-20 08:05:23 - DEBUG UnitTestFramework: '#teardown ok: 'Test to exceed the max content size locally''

2017-07-20 08:05:23 - DEBUG UnitTestFramework: '#setup: 'Close the server socket while the client is waiting a response from the server. Local test.''

2017-07-20 08:05:24 - DEBUG UnitTestFramework: '#setup ok: 'Close the server socket while the client is waiting a response from the server. Local test.''

2017-07-20 08:05:24 - DEBUG UnitTestFramework: '#run: 'Close the server socket while the client is waiting a response from the server. Local test.''

2017-07-20 08:05:29 - DEBUG UnitTestFramework: '#run ok: 'Close the server socket while the client is waiting a response from the server. Local test.''

2017-07-20 08:05:29 - DEBUG UnitTestFramework: '#teardown: 'Close the server socket while the client is waiting a response from the server. Local test.''

2017-07-20 08:05:31 - DEBUG UnitTestFramework: '#teardown ok: 'Close the server socket while the client is waiting a response from the server. Local test.''

2017-07-20 08:05:31 - DEBUG UnitTestFramework: '#setup: 'Close the client socket while the client is waiting a response from the server. Local test.''

2017-07-20 08:05:32 - DEBUG UnitTestFramework: '#setup ok: 'Close the client socket while the client is waiting a response from the server. Local test.''

2017-07-20 08:05:32 - DEBUG UnitTestFramework: '#run: 'Close the client socket while the client is waiting a response from the server. Local test.''

2017-07-20 08:05:36 - DEBUG UnitTestFramework: '#run ok: 'Close the client socket while the client is waiting a response from the server. Local test.''

2017-07-20 08:05:36 - DEBUG UnitTestFramework: '#teardown: 'Close the client socket while the client is waiting a response from the server. Local test.''

2017-07-20 08:05:37 - DEBUG UnitTestFramework: '#teardown ok: 'Close the client socket while the client is waiting a response from the server. Local test.''

2017-07-20 08:05:37 - DEBUG UnitTestFramework: '#setup: '#generatePreambleAndBeacons bad args''

2017-07-20 08:05:40 - DEBUG UnitTestFramework: '#setup ok: '#generatePreambleAndBeacons bad args''

2017-07-20 08:05:40 - DEBUG UnitTestFramework: '#run: '#generatePreambleAndBeacons bad args''

2017-07-20 08:05:42 - DEBUG UnitTestFramework: '#run ok: '#generatePreambleAndBeacons bad args''

2017-07-20 08:05:42 - DEBUG UnitTestFramework: '#teardown: '#generatePreambleAndBeacons bad args''

2017-07-20 08:05:44 - DEBUG UnitTestFramework: '#teardown ok: '#generatePreambleAndBeacons bad args''

2017-07-20 08:05:44 - DEBUG UnitTestFramework: '#setup: '#generatePreambleAndBeacons empty keys to notify''

2017-07-20 08:05:47 - DEBUG UnitTestFramework: '#setup ok: '#generatePreambleAndBeacons empty keys to notify''

2017-07-20 08:05:47 - DEBUG UnitTestFramework: '#run: '#generatePreambleAndBeacons empty keys to notify''

2017-07-20 08:05:48 - DEBUG UnitTestFramework: '#run ok: '#generatePreambleAndBeacons empty keys to notify''

2017-07-20 08:05:48 - DEBUG UnitTestFramework: '#teardown: '#generatePreambleAndBeacons empty keys to notify''

2017-07-20 08:05:50 - DEBUG UnitTestFramework: '#teardown ok: '#generatePreambleAndBeacons empty keys to notify''

2017-07-20 08:05:50 - DEBUG UnitTestFramework: '#setup: '#generatePreambleAndBeacons multiple keys to notify''

2017-07-20 08:05:53 - DEBUG UnitTestFramework: '#setup ok: '#generatePreambleAndBeacons multiple keys to notify''

2017-07-20 08:05:53 - DEBUG UnitTestFramework: '#run: '#generatePreambleAndBeacons multiple keys to notify''

2017-07-20 08:05:56 - DEBUG UnitTestFramework: '#run ok: '#generatePreambleAndBeacons multiple keys to notify''

2017-07-20 08:05:56 - DEBUG UnitTestFramework: '#teardown: '#generatePreambleAndBeacons multiple keys to notify''

2017-07-20 08:05:56 - DEBUG UnitTestFramework: '#teardown ok: '#generatePreambleAndBeacons multiple keys to notify''

2017-07-20 08:05:56 - DEBUG UnitTestFramework: '#setup: '#parseBeacons invalid ECDH public key in beaconStreamWithPreAmble''

2017-07-20 08:05:59 - DEBUG UnitTestFramework: '#setup ok: '#parseBeacons invalid ECDH public key in beaconStreamWithPreAmble''

2017-07-20 08:05:59 - DEBUG UnitTestFramework: '#run: '#parseBeacons invalid ECDH public key in beaconStreamWithPreAmble''

2017-07-20 08:06:00 - DEBUG UnitTestFramework: '#run ok: '#parseBeacons invalid ECDH public key in beaconStreamWithPreAmble''

2017-07-20 08:06:00 - DEBUG UnitTestFramework: '#teardown: '#parseBeacons invalid ECDH public key in beaconStreamWithPreAmble''

2017-07-20 08:06:02 - DEBUG UnitTestFramework: '#teardown ok: '#parseBeacons invalid ECDH public key in beaconStreamWithPreAmble''

2017-07-20 08:06:02 - DEBUG UnitTestFramework: '#setup: '#parseBeacons invalid expiration in beaconStreamWithPreAmble''

2017-07-20 08:06:05 - DEBUG UnitTestFramework: '#setup ok: '#parseBeacons invalid expiration in beaconStreamWithPreAmble''

2017-07-20 08:06:05 - DEBUG UnitTestFramework: '#run: '#parseBeacons invalid expiration in beaconStreamWithPreAmble''

2017-07-20 08:06:07 - DEBUG UnitTestFramework: '#run ok: '#parseBeacons invalid expiration in beaconStreamWithPreAmble''

2017-07-20 08:06:07 - DEBUG UnitTestFramework: '#teardown: '#parseBeacons invalid expiration in beaconStreamWithPreAmble''

2017-07-20 08:06:09 - DEBUG UnitTestFramework: '#teardown ok: '#parseBeacons invalid expiration in beaconStreamWithPreAmble''

2017-07-20 08:06:09 - DEBUG UnitTestFramework: '#setup: '#parseBeacons expiration out of range lower''

2017-07-20 08:06:10 - DEBUG UnitTestFramework: '#setup ok: '#parseBeacons expiration out of range lower''

2017-07-20 08:06:10 - DEBUG UnitTestFramework: '#run: '#parseBeacons expiration out of range lower''

2017-07-20 08:06:12 - DEBUG UnitTestFramework: '#run ok: '#parseBeacons expiration out of range lower''

2017-07-20 08:06:12 - DEBUG UnitTestFramework: '#teardown: '#parseBeacons expiration out of range lower''

2017-07-20 08:06:14 - DEBUG UnitTestFramework: '#teardown ok: '#parseBeacons expiration out of range lower''

2017-07-20 08:06:14 - DEBUG UnitTestFramework: '#setup: '#parseBeacons expiration out of range lower''

2017-07-20 08:06:17 - DEBUG UnitTestFramework: '#setup ok: '#parseBeacons expiration out of range lower''

2017-07-20 08:06:17 - DEBUG UnitTestFramework: '#run: '#parseBeacons expiration out of range lower''

2017-07-20 08:06:19 - DEBUG UnitTestFramework: '#run ok: '#parseBeacons expiration out of range lower''

2017-07-20 08:06:19 - DEBUG UnitTestFramework: '#teardown: '#parseBeacons expiration out of range lower''

2017-07-20 08:06:20 - DEBUG UnitTestFramework: '#teardown ok: '#parseBeacons expiration out of range lower''

2017-07-20 08:06:20 - DEBUG UnitTestFramework: '#setup: '#parseBeacons no beacons returns null''

2017-07-20 08:06:23 - DEBUG UnitTestFramework: '#setup ok: '#parseBeacons no beacons returns null''

2017-07-20 08:06:23 - DEBUG UnitTestFramework: '#run: '#parseBeacons no beacons returns null''

2017-07-20 08:06:23 - DEBUG UnitTestFramework: '#run ok: '#parseBeacons no beacons returns null''

2017-07-20 08:06:23 - DEBUG UnitTestFramework: '#teardown: '#parseBeacons no beacons returns null''

2017-07-20 08:06:26 - DEBUG UnitTestFramework: '#teardown ok: '#parseBeacons no beacons returns null''

2017-07-20 08:06:26 - DEBUG UnitTestFramework: '#setup: '#parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble''

2017-07-20 08:06:29 - DEBUG UnitTestFramework: '#setup ok: '#parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble''

2017-07-20 08:06:29 - DEBUG UnitTestFramework: '#run: '#parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble''

2017-07-20 08:06:30 - DEBUG UnitTestFramework: '#run ok: '#parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble''

2017-07-20 08:06:30 - DEBUG UnitTestFramework: '#teardown: '#parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble''

2017-07-20 08:06:32 - DEBUG UnitTestFramework: '#teardown ok: '#parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble''

2017-07-20 08:06:32 - DEBUG UnitTestFramework: '#setup: '#parseBeacons addressBookCallback fails decrypt''

2017-07-20 08:06:34 - DEBUG UnitTestFramework: '#setup ok: '#parseBeacons addressBookCallback fails decrypt''

2017-07-20 08:06:34 - DEBUG UnitTestFramework: '#run: '#parseBeacons addressBookCallback fails decrypt''

2017-07-20 08:06:35 - DEBUG UnitTestFramework: '#run ok: '#parseBeacons addressBookCallback fails decrypt''

2017-07-20 08:06:35 - DEBUG UnitTestFramework: '#teardown: '#parseBeacons addressBookCallback fails decrypt''

2017-07-20 08:06:37 - DEBUG UnitTestFramework: '#teardown ok: '#parseBeacons addressBookCallback fails decrypt''

2017-07-20 08:06:37 - DEBUG UnitTestFramework: '#setup: '#parseBeacons addressBookCallback returns no matches''

2017-07-20 08:06:38 - DEBUG UnitTestFramework: '#setup ok: '#parseBeacons addressBookCallback returns no matches''

2017-07-20 08:06:38 - DEBUG UnitTestFramework: '#run: '#parseBeacons addressBookCallback returns no matches''

2017-07-20 08:06:38 - INFO Socket: 'run skipped, test: '#parseBeacons addressBookCallback returns no matches', event: 'run_#parseBeacons addressBookCallback returns no matches''

2017-07-20 08:06:38 - INFO Socket: 'run skipped, test: '#parseBeacons addressBookCallback returns no matches', event: 'run_#parseBeacons addressBookCallback returns no matches''

2017-07-20 08:06:41 - INFO Socket: 'run skipped, test: '#parseBeacons addressBookCallback returns no matches', event: 'run_#parseBeacons addressBookCallback returns no matches''

2017-07-20 08:06:41 - DEBUG UnitTestFramework: '#run ok: '#parseBeacons addressBookCallback returns no matches''

2017-07-20 08:06:41 - DEBUG UnitTestFramework: '#teardown: '#parseBeacons addressBookCallback returns no matches''

2017-07-20 08:06:44 - DEBUG UnitTestFramework: '#teardown ok: '#parseBeacons addressBookCallback returns no matches''

2017-07-20 08:06:44 - DEBUG UnitTestFramework: '#setup: '#parseBeacons addressBookCallback returns spurious match''

2017-07-20 08:06:47 - DEBUG UnitTestFramework: '#setup ok: '#parseBeacons addressBookCallback returns spurious match''

2017-07-20 08:06:47 - DEBUG UnitTestFramework: '#run: '#parseBeacons addressBookCallback returns spurious match''

2017-07-20 08:06:47 - DEBUG UnitTestFramework: '#run ok: '#parseBeacons addressBookCallback returns spurious match''

2017-07-20 08:06:47 - DEBUG UnitTestFramework: '#teardown: '#parseBeacons addressBookCallback returns spurious match''

2017-07-20 08:06:50 - DEBUG UnitTestFramework: '#teardown ok: '#parseBeacons addressBookCallback returns spurious match''

2017-07-20 08:06:50 - DEBUG UnitTestFramework: '#setup: '#parseBeacons addressBookCallback returns public key''

2017-07-20 08:06:50 - DEBUG UnitTestFramework: '#setup ok: '#parseBeacons addressBookCallback returns public key''

2017-07-20 08:06:50 - DEBUG UnitTestFramework: '#run: '#parseBeacons addressBookCallback returns public key''

2017-07-20 08:06:53 - DEBUG UnitTestFramework: '#run ok: '#parseBeacons addressBookCallback returns public key''

2017-07-20 08:06:53 - DEBUG UnitTestFramework: '#teardown: '#parseBeacons addressBookCallback returns public key''

2017-07-20 08:06:55 - DEBUG UnitTestFramework: '#teardown ok: '#parseBeacons addressBookCallback returns public key''

2017-07-20 08:06:55 - DEBUG UnitTestFramework: '#setup: 'validate generatePskIdentityField''

2017-07-20 08:06:56 - DEBUG UnitTestFramework: '#setup ok: 'validate generatePskIdentityField''

2017-07-20 08:06:56 - DEBUG UnitTestFramework: '#run: 'validate generatePskIdentityField''

2017-07-20 08:06:59 - DEBUG UnitTestFramework: '#run ok: 'validate generatePskIdentityField''

2017-07-20 08:06:59 - DEBUG UnitTestFramework: '#teardown: 'validate generatePskIdentityField''

2017-07-20 08:07:00 - DEBUG UnitTestFramework: '#teardown ok: 'validate generatePskIdentityField''

2017-07-20 08:07:00 - DEBUG UnitTestFramework: '#setup: 'validate generatePskSecret''

2017-07-20 08:07:02 - DEBUG UnitTestFramework: '#setup ok: 'validate generatePskSecret''

2017-07-20 08:07:02 - DEBUG UnitTestFramework: '#run: 'validate generatePskSecret''

2017-07-20 08:07:05 - DEBUG UnitTestFramework: '#run ok: 'validate generatePskSecret''

2017-07-20 08:07:05 - DEBUG UnitTestFramework: '#teardown: 'validate generatePskSecret''

2017-07-20 08:07:06 - DEBUG UnitTestFramework: '#teardown ok: 'validate generatePskSecret''

2017-07-20 08:07:06 - DEBUG UnitTestFramework: '#setup: 'validate generatePskSecrets''

2017-07-20 08:07:08 - DEBUG UnitTestFramework: '#setup ok: 'validate generatePskSecrets''

2017-07-20 08:07:08 - DEBUG UnitTestFramework: '#run: 'validate generatePskSecrets''

2017-07-20 08:07:10 - DEBUG UnitTestFramework: '#run ok: 'validate generatePskSecrets''

2017-07-20 08:07:10 - DEBUG UnitTestFramework: '#teardown: 'validate generatePskSecrets''

2017-07-20 08:07:11 - DEBUG UnitTestFramework: '#teardown ok: 'validate generatePskSecrets''

2017-07-20 08:07:11 - DEBUG UnitTestFramework: '#setup: 'validate generateBeaconStreamAndSecrets''

2017-07-20 08:07:13 - DEBUG UnitTestFramework: '#setup ok: 'validate generateBeaconStreamAndSecrets''

2017-07-20 08:07:13 - DEBUG UnitTestFramework: '#run: 'validate generateBeaconStreamAndSecrets''

2017-07-20 08:07:17 - DEBUG UnitTestFramework: '#run ok: 'validate generateBeaconStreamAndSecrets''

2017-07-20 08:07:17 - DEBUG UnitTestFramework: '#teardown: 'validate generateBeaconStreamAndSecrets''

2017-07-20 08:07:19 - DEBUG UnitTestFramework: '#teardown ok: 'validate generateBeaconStreamAndSecrets''

2017-07-20 08:07:19 - DEBUG UnitTestFramework: '#setup: 'Client to server request locally''

2017-07-20 08:07:20 - DEBUG UnitTestFramework: '#setup ok: 'Client to server request locally''

2017-07-20 08:07:20 - DEBUG UnitTestFramework: '#run: 'Client to server request locally''

2017-07-20 08:07:23 - DEBUG UnitTestFramework: '#run ok: 'Client to server request locally''

2017-07-20 08:07:23 - DEBUG UnitTestFramework: '#teardown: 'Client to server request locally''

2017-07-20 08:07:25 - DEBUG UnitTestFramework: '#teardown ok: 'Client to server request locally''

2017-07-20 08:07:25 - DEBUG UnitTestFramework: '#setup: 'Coordinated pull replication from notification test''

2017-07-20 08:07:27 - DEBUG UnitTestFramework: '#setup ok: 'Coordinated pull replication from notification test''

2017-07-20 08:07:27 - DEBUG UnitTestFramework: '#run: 'Coordinated pull replication from notification test''

2017-07-20 08:07:27 - INFO Socket: 'run skipped, test: 'Coordinated pull replication from notification test', event: 'run_Coordinated pull replication from notification test''

2017-07-20 08:07:28 - INFO Socket: 'run skipped, test: 'Coordinated pull replication from notification test', event: 'run_Coordinated pull replication from notification test''

2017-07-20 08:07:29 - INFO Socket: 'run skipped, test: 'Coordinated pull replication from notification test', event: 'run_Coordinated pull replication from notification test''

2017-07-20 08:07:29 - DEBUG UnitTestFramework: '#run ok: 'Coordinated pull replication from notification test''

2017-07-20 08:07:29 - DEBUG UnitTestFramework: '#teardown: 'Coordinated pull replication from notification test''

2017-07-20 08:07:31 - DEBUG UnitTestFramework: '#teardown ok: 'Coordinated pull replication from notification test''

2017-07-20 08:07:31 - DEBUG UnitTestFramework: '#setup: 'Server is not there''

2017-07-20 08:07:33 - DEBUG UnitTestFramework: '#setup ok: 'Server is not there''

2017-07-20 08:07:33 - DEBUG UnitTestFramework: '#run: 'Server is not there''

2017-07-20 08:07:35 - DEBUG UnitTestFramework: '#run ok: 'Server is not there''

2017-07-20 08:07:35 - DEBUG UnitTestFramework: '#teardown: 'Server is not there''

2017-07-20 08:07:37 - DEBUG UnitTestFramework: '#teardown ok: 'Server is not there''

2017-07-20 08:07:37 - DEBUG UnitTestFramework: '#setup: 'Server accepts & closes connection''

2017-07-20 08:07:41 - DEBUG UnitTestFramework: '#setup ok: 'Server accepts & closes connection''

2017-07-20 08:07:41 - DEBUG UnitTestFramework: '#run: 'Server accepts & closes connection''

2017-07-20 08:07:44 - DEBUG UnitTestFramework: '#run ok: 'Server accepts & closes connection''

2017-07-20 08:07:44 - DEBUG UnitTestFramework: '#teardown: 'Server accepts & closes connection''

2017-07-20 08:07:47 - DEBUG UnitTestFramework: '#teardown ok: 'Server accepts & closes connection''

2017-07-20 08:07:47 - DEBUG UnitTestFramework: '#setup: 'Server always returns 500''

2017-07-20 08:07:48 - DEBUG UnitTestFramework: '#setup ok: 'Server always returns 500''

2017-07-20 08:07:48 - DEBUG UnitTestFramework: '#run: 'Server always returns 500''

2017-07-20 08:07:50 - DEBUG UnitTestFramework: '#run ok: 'Server always returns 500''

2017-07-20 08:07:50 - DEBUG UnitTestFramework: '#teardown: 'Server always returns 500''

2017-07-20 08:07:52 - DEBUG UnitTestFramework: '#teardown ok: 'Server always returns 500''

2017-07-20 08:07:52 - DEBUG UnitTestFramework: '#setup: 'Server always returns 401''

2017-07-20 08:07:53 - DEBUG UnitTestFramework: '#setup ok: 'Server always returns 401''

2017-07-20 08:07:53 - DEBUG UnitTestFramework: '#run: 'Server always returns 401''

2017-07-20 08:07:56 - DEBUG UnitTestFramework: '#run ok: 'Server always returns 401''

2017-07-20 08:07:56 - DEBUG UnitTestFramework: '#teardown: 'Server always returns 401''

2017-07-20 08:07:56 - DEBUG UnitTestFramework: '#teardown ok: 'Server always returns 401''

2017-07-20 08:07:56 - DEBUG UnitTestFramework: '#setup: 'Server always returns 403''

2017-07-20 08:07:59 - DEBUG UnitTestFramework: '#setup ok: 'Server always returns 403''

2017-07-20 08:07:59 - DEBUG UnitTestFramework: '#run: 'Server always returns 403''

2017-07-20 08:08:02 - DEBUG UnitTestFramework: '#run ok: 'Server always returns 403''

2017-07-20 08:08:02 - DEBUG UnitTestFramework: '#teardown: 'Server always returns 403''

2017-07-20 08:08:02 - DEBUG UnitTestFramework: '#teardown ok: 'Server always returns 403''

2017-07-20 08:08:02 - DEBUG UnitTestFramework: '#setup: 'Make sure docs replicate with remote db with same name as local db''

2017-07-20 08:08:05 - DEBUG UnitTestFramework: '#setup ok: 'Make sure docs replicate with remote db with same name as local db''

2017-07-20 08:08:05 - DEBUG UnitTestFramework: '#run: 'Make sure docs replicate with remote db with same name as local db''

2017-07-20 08:08:10 - DEBUG UnitTestFramework: '#run ok: 'Make sure docs replicate with remote db with same name as local db''

2017-07-20 08:08:10 - DEBUG UnitTestFramework: '#teardown: 'Make sure docs replicate with remote db with same name as local db''

2017-07-20 08:08:12 - DEBUG UnitTestFramework: '#teardown ok: 'Make sure docs replicate with remote db with same name as local db''

2017-07-20 08:08:12 - DEBUG UnitTestFramework: '#setup: 'Make sure docs replicate with remote db with different name than local db''

2017-07-20 08:08:14 - DEBUG UnitTestFramework: '#setup ok: 'Make sure docs replicate with remote db with different name than local db''

2017-07-20 08:08:14 - DEBUG UnitTestFramework: '#run: 'Make sure docs replicate with remote db with different name than local db''

2017-07-20 08:08:21 - DEBUG UnitTestFramework: '#run ok: 'Make sure docs replicate with remote db with different name than local db''

2017-07-20 08:08:21 - DEBUG UnitTestFramework: '#teardown: 'Make sure docs replicate with remote db with different name than local db''

2017-07-20 08:08:24 - DEBUG UnitTestFramework: '#teardown ok: 'Make sure docs replicate with remote db with different name than local db''

2017-07-20 08:08:24 - DEBUG UnitTestFramework: '#setup: 'Do nothing and make sure we time out''

2017-07-20 08:08:24 - DEBUG UnitTestFramework: '#setup ok: 'Do nothing and make sure we time out''

2017-07-20 08:08:24 - DEBUG UnitTestFramework: '#run: 'Do nothing and make sure we time out''

2017-07-20 08:08:29 - DEBUG UnitTestFramework: '#run ok: 'Do nothing and make sure we time out''

2017-07-20 08:08:29 - DEBUG UnitTestFramework: '#teardown: 'Do nothing and make sure we time out''

2017-07-20 08:08:31 - DEBUG UnitTestFramework: '#teardown ok: 'Do nothing and make sure we time out''

2017-07-20 08:08:31 - DEBUG UnitTestFramework: '#setup: 'Do something and make sure we time out''

2017-07-20 08:08:32 - DEBUG UnitTestFramework: '#setup ok: 'Do something and make sure we time out''

2017-07-20 08:08:32 - DEBUG UnitTestFramework: '#run: 'Do something and make sure we time out''

2017-07-20 08:08:38 - DEBUG UnitTestFramework: '#run ok: 'Do something and make sure we time out''

2017-07-20 08:08:38 - DEBUG UnitTestFramework: '#teardown: 'Do something and make sure we time out''

2017-07-20 08:08:40 - DEBUG UnitTestFramework: '#teardown ok: 'Do something and make sure we time out''

2017-07-20 08:08:40 - DEBUG UnitTestFramework: '#setup: 'Start replicating and then catch error when server goes''

2017-07-20 08:08:42 - DEBUG UnitTestFramework: '#setup ok: 'Start replicating and then catch error when server goes''

2017-07-20 08:08:42 - DEBUG UnitTestFramework: '#run: 'Start replicating and then catch error when server goes''

2017-07-20 08:08:43 - DEBUG UnitTestFramework: '#run ok: 'Start replicating and then catch error when server goes''

2017-07-20 08:08:43 - DEBUG UnitTestFramework: '#teardown: 'Start replicating and then catch error when server goes''

2017-07-20 08:08:46 - DEBUG UnitTestFramework: '#teardown ok: 'Start replicating and then catch error when server goes''

2017-07-20 08:08:46 - DEBUG UnitTestFramework: '#setup: 'Make sure clone works''

2017-07-20 08:08:47 - DEBUG UnitTestFramework: '#setup ok: 'Make sure clone works''

2017-07-20 08:08:47 - DEBUG UnitTestFramework: '#run: 'Make sure clone works''

2017-07-20 08:08:50 - DEBUG UnitTestFramework: '#run ok: 'Make sure clone works''

2017-07-20 08:08:50 - DEBUG UnitTestFramework: '#teardown: 'Make sure clone works''

2017-07-20 08:08:53 - DEBUG UnitTestFramework: '#teardown ok: 'Make sure clone works''

2017-07-20 08:08:53 - DEBUG UnitTestFramework: '#setup: 'compareBufferArrays''

2017-07-20 08:08:53 - DEBUG UnitTestFramework: '#setup ok: 'compareBufferArrays''

2017-07-20 08:08:53 - DEBUG UnitTestFramework: '#run: 'compareBufferArrays''

2017-07-20 08:08:56 - DEBUG UnitTestFramework: '#run ok: 'compareBufferArrays''

2017-07-20 08:08:56 - DEBUG UnitTestFramework: '#teardown: 'compareBufferArrays''

2017-07-20 08:08:59 - DEBUG UnitTestFramework: '#teardown ok: 'compareBufferArrays''

2017-07-20 08:08:59 - DEBUG UnitTestFramework: '#setup: 'Call start twice and get error''

2017-07-20 08:08:59 - DEBUG UnitTestFramework: '#setup ok: 'Call start twice and get error''

2017-07-20 08:08:59 - DEBUG UnitTestFramework: '#run: 'Call start twice and get error''

2017-07-20 08:09:02 - DEBUG UnitTestFramework: '#run ok: 'Call start twice and get error''

2017-07-20 08:09:02 - DEBUG UnitTestFramework: '#teardown: 'Call start twice and get error''

2017-07-20 08:09:05 - DEBUG UnitTestFramework: '#teardown ok: 'Call start twice and get error''

2017-07-20 08:09:05 - DEBUG UnitTestFramework: '#setup: 'Start and make sure it runs''

2017-07-20 08:09:05 - DEBUG UnitTestFramework: '#setup ok: 'Start and make sure it runs''

2017-07-20 08:09:05 - DEBUG UnitTestFramework: '#run: 'Start and make sure it runs''

2017-07-20 08:09:07 - DEBUG UnitTestFramework: '#run ok: 'Start and make sure it runs''

2017-07-20 08:09:07 - DEBUG UnitTestFramework: '#teardown: 'Start and make sure it runs''

2017-07-20 08:09:08 - DEBUG UnitTestFramework: '#teardown ok: 'Start and make sure it runs''

2017-07-20 08:09:08 - DEBUG UnitTestFramework: '#setup: 'Make sure getTimeWhenRun is right after start''

2017-07-20 08:09:11 - DEBUG UnitTestFramework: '#setup ok: 'Make sure getTimeWhenRun is right after start''

2017-07-20 08:09:11 - DEBUG UnitTestFramework: '#run: 'Make sure getTimeWhenRun is right after start''

2017-07-20 08:09:11 - DEBUG UnitTestFramework: '#run ok: 'Make sure getTimeWhenRun is right after start''

2017-07-20 08:09:11 - DEBUG UnitTestFramework: '#teardown: 'Make sure getTimeWhenRun is right after start''

2017-07-20 08:09:14 - DEBUG UnitTestFramework: '#teardown ok: 'Make sure getTimeWhenRun is right after start''

2017-07-20 08:09:14 - DEBUG UnitTestFramework: '#setup: 'Make sure getTimeWhenRun is -1 after function is called''

2017-07-20 08:09:17 - DEBUG UnitTestFramework: '#setup ok: 'Make sure getTimeWhenRun is -1 after function is called''

2017-07-20 08:09:17 - DEBUG UnitTestFramework: '#run: 'Make sure getTimeWhenRun is -1 after function is called''

2017-07-20 08:09:18 - DEBUG UnitTestFramework: '#run ok: 'Make sure getTimeWhenRun is -1 after function is called''

2017-07-20 08:09:18 - DEBUG UnitTestFramework: '#teardown: 'Make sure getTimeWhenRun is -1 after function is called''

2017-07-20 08:09:21 - DEBUG UnitTestFramework: '#teardown ok: 'Make sure getTimeWhenRun is -1 after function is called''

2017-07-20 08:09:21 - DEBUG UnitTestFramework: '#setup: 'Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running''

2017-07-20 08:09:24 - DEBUG UnitTestFramework: '#setup ok: 'Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running''

2017-07-20 08:09:24 - DEBUG UnitTestFramework: '#run: 'Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running''

2017-07-20 08:09:26 - DEBUG UnitTestFramework: '#run ok: 'Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running''

2017-07-20 08:09:26 - DEBUG UnitTestFramework: '#teardown: 'Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running''

2017-07-20 08:09:28 - DEBUG UnitTestFramework: '#teardown ok: 'Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running''

2017-07-20 08:09:28 - DEBUG UnitTestFramework: '#setup: 'Test TransientState''

2017-07-20 08:09:30 - DEBUG UnitTestFramework: '#setup ok: 'Test TransientState''

2017-07-20 08:09:30 - DEBUG UnitTestFramework: '#run: 'Test TransientState''

2017-07-20 08:09:32 - DEBUG UnitTestFramework: '#run ok: 'Test TransientState''

2017-07-20 08:09:32 - DEBUG UnitTestFramework: '#teardown: 'Test TransientState''

2017-07-20 08:09:34 - DEBUG UnitTestFramework: '#teardown ok: 'Test TransientState''

2017-07-20 08:09:34 - DEBUG UnitTestFramework: '#setup: 'No peers and empty database''

2017-07-20 08:09:36 - DEBUG UnitTestFramework: '#setup ok: 'No peers and empty database''

2017-07-20 08:09:36 - DEBUG UnitTestFramework: '#run: 'No peers and empty database''

2017-07-20 08:09:38 - DEBUG UnitTestFramework: '#run ok: 'No peers and empty database''

2017-07-20 08:09:38 - DEBUG UnitTestFramework: '#teardown: 'No peers and empty database''

2017-07-20 08:09:40 - DEBUG UnitTestFramework: '#teardown ok: 'No peers and empty database''

2017-07-20 08:09:40 - DEBUG UnitTestFramework: '#setup: 'One peer and empty DB''

2017-07-20 08:09:42 - DEBUG UnitTestFramework: '#setup ok: 'One peer and empty DB''

2017-07-20 08:09:42 - DEBUG UnitTestFramework: '#run: 'One peer and empty DB''

2017-07-20 08:09:45 - DEBUG UnitTestFramework: '#run ok: 'One peer and empty DB''

2017-07-20 08:09:45 - DEBUG UnitTestFramework: '#teardown: 'One peer and empty DB''

2017-07-20 08:09:48 - DEBUG UnitTestFramework: '#teardown ok: 'One peer and empty DB''

2017-07-20 08:09:48 - DEBUG UnitTestFramework: '#setup: 'One peer with _Local set behind current seq''

2017-07-20 08:09:50 - DEBUG UnitTestFramework: '#setup ok: 'One peer with _Local set behind current seq''

2017-07-20 08:09:50 - DEBUG UnitTestFramework: '#run: 'One peer with _Local set behind current seq''

2017-07-20 08:09:53 - DEBUG UnitTestFramework: '#run ok: 'One peer with _Local set behind current seq''

2017-07-20 08:09:53 - DEBUG UnitTestFramework: '#teardown: 'One peer with _Local set behind current seq''

2017-07-20 08:09:56 - DEBUG UnitTestFramework: '#teardown ok: 'One peer with _Local set behind current seq''

2017-07-20 08:09:56 - DEBUG UnitTestFramework: '#setup: 'One peer with _Local set equal to current seq''

2017-07-20 08:09:57 - DEBUG UnitTestFramework: '#setup ok: 'One peer with _Local set equal to current seq''

2017-07-20 08:09:57 - DEBUG UnitTestFramework: '#run: 'One peer with _Local set equal to current seq''

2017-07-20 08:09:59 - DEBUG UnitTestFramework: '#run ok: 'One peer with _Local set equal to current seq''

2017-07-20 08:09:59 - DEBUG UnitTestFramework: '#teardown: 'One peer with _Local set equal to current seq''

2017-07-20 08:10:02 - DEBUG UnitTestFramework: '#teardown ok: 'One peer with _Local set equal to current seq''

2017-07-20 08:10:02 - DEBUG UnitTestFramework: '#setup: 'One peer with _Local set ahead of current seq (and no this should not happen)''

2017-07-20 08:10:05 - DEBUG UnitTestFramework: '#setup ok: 'One peer with _Local set ahead of current seq (and no this should not happen)''

2017-07-20 08:10:05 - DEBUG UnitTestFramework: '#run: 'One peer with _Local set ahead of current seq (and no this should not happen)''

2017-07-20 08:10:05 - DEBUG UnitTestFramework: '#run ok: 'One peer with _Local set ahead of current seq (and no this should not happen)''

2017-07-20 08:10:05 - DEBUG UnitTestFramework: '#teardown: 'One peer with _Local set ahead of current seq (and no this should not happen)''

2017-07-20 08:10:08 - DEBUG UnitTestFramework: '#teardown ok: 'One peer with _Local set ahead of current seq (and no this should not happen)''

2017-07-20 08:10:08 - DEBUG UnitTestFramework: '#setup: 'Three peers, one not in DB, one behind and one ahead''

2017-07-20 08:10:11 - DEBUG UnitTestFramework: '#setup ok: 'Three peers, one not in DB, one behind and one ahead''

2017-07-20 08:10:11 - DEBUG UnitTestFramework: '#run: 'Three peers, one not in DB, one behind and one ahead''

2017-07-20 08:10:14 - DEBUG UnitTestFramework: '#run ok: 'Three peers, one not in DB, one behind and one ahead''

2017-07-20 08:10:14 - DEBUG UnitTestFramework: '#teardown: 'Three peers, one not in DB, one behind and one ahead''

2017-07-20 08:10:17 - DEBUG UnitTestFramework: '#teardown ok: 'Three peers, one not in DB, one behind and one ahead''

2017-07-20 08:10:17 - DEBUG UnitTestFramework: '#setup: 'More than maximum peers, make sure we only send maximum allowed''

2017-07-20 08:10:20 - DEBUG UnitTestFramework: '#setup ok: 'More than maximum peers, make sure we only send maximum allowed''

2017-07-20 08:10:20 - DEBUG UnitTestFramework: '#run: 'More than maximum peers, make sure we only send maximum allowed''

2017-07-20 08:10:20 - DEBUG UnitTestFramework: '#run ok: 'More than maximum peers, make sure we only send maximum allowed''

2017-07-20 08:10:20 - DEBUG UnitTestFramework: '#teardown: 'More than maximum peers, make sure we only send maximum allowed''

2017-07-20 08:10:22 - DEBUG UnitTestFramework: '#teardown ok: 'More than maximum peers, make sure we only send maximum allowed''

2017-07-20 08:10:22 - DEBUG UnitTestFramework: '#setup: 'two peers with empty DB, update the doc''

2017-07-20 08:10:24 - DEBUG UnitTestFramework: '#setup ok: 'two peers with empty DB, update the doc''

2017-07-20 08:10:24 - DEBUG UnitTestFramework: '#run: 'two peers with empty DB, update the doc''

2017-07-20 08:10:26 - DEBUG UnitTestFramework: '#run ok: 'two peers with empty DB, update the doc''

2017-07-20 08:10:26 - DEBUG UnitTestFramework: '#teardown: 'two peers with empty DB, update the doc''

2017-07-20 08:10:27 - DEBUG UnitTestFramework: '#teardown ok: 'two peers with empty DB, update the doc''

2017-07-20 08:10:27 - DEBUG UnitTestFramework: '#setup: 'add doc and make sure tokens refresh when they expire''

2017-07-20 08:10:30 - DEBUG UnitTestFramework: '#setup ok: 'add doc and make sure tokens refresh when they expire''

2017-07-20 08:10:30 - DEBUG UnitTestFramework: '#run: 'add doc and make sure tokens refresh when they expire''

2017-07-20 08:10:32 - DEBUG UnitTestFramework: '#run ok: 'add doc and make sure tokens refresh when they expire''

2017-07-20 08:10:32 - DEBUG UnitTestFramework: '#teardown: 'add doc and make sure tokens refresh when they expire''

2017-07-20 08:10:34 - DEBUG UnitTestFramework: '#teardown ok: 'add doc and make sure tokens refresh when they expire''

2017-07-20 08:10:34 - DEBUG UnitTestFramework: '#setup: 'start and stop and start and stop''

2017-07-20 08:10:36 - DEBUG UnitTestFramework: '#setup ok: 'start and stop and start and stop''

2017-07-20 08:10:36 - DEBUG UnitTestFramework: '#run: 'start and stop and start and stop''

2017-07-20 08:10:37 - DEBUG UnitTestFramework: '#run ok: 'start and stop and start and stop''

2017-07-20 08:10:37 - DEBUG UnitTestFramework: '#teardown: 'start and stop and start and stop''

2017-07-20 08:10:39 - DEBUG UnitTestFramework: '#teardown ok: 'start and stop and start and stop''

2017-07-20 08:10:39 - DEBUG UnitTestFramework: '#setup: 'two identical starts in a row''

2017-07-20 08:10:42 - DEBUG UnitTestFramework: '#setup ok: 'two identical starts in a row''

2017-07-20 08:10:42 - DEBUG UnitTestFramework: '#run: 'two identical starts in a row''

2017-07-20 08:10:44 - DEBUG UnitTestFramework: '#run ok: 'two identical starts in a row''

2017-07-20 08:10:44 - DEBUG UnitTestFramework: '#teardown: 'two identical starts in a row''

2017-07-20 08:10:47 - DEBUG UnitTestFramework: '#teardown ok: 'two identical starts in a row''

2017-07-20 08:10:47 - DEBUG UnitTestFramework: '#setup: 'two different starts in a row''

2017-07-20 08:10:48 - DEBUG UnitTestFramework: '#setup ok: 'two different starts in a row''

2017-07-20 08:10:49 - DEBUG UnitTestFramework: '#run: 'two different starts in a row''

2017-07-20 08:10:50 - DEBUG UnitTestFramework: '#run ok: 'two different starts in a row''

2017-07-20 08:10:50 - DEBUG UnitTestFramework: '#teardown: 'two different starts in a row''

2017-07-20 08:10:53 - DEBUG UnitTestFramework: '#teardown ok: 'two different starts in a row''

2017-07-20 08:10:53 - DEBUG UnitTestFramework: '#setup: 'two stops and a start and two stops''

2017-07-20 08:10:56 - DEBUG UnitTestFramework: '#setup ok: 'two stops and a start and two stops''

2017-07-20 08:10:56 - DEBUG UnitTestFramework: '#run: 'two stops and a start and two stops''

2017-07-20 08:10:58 - DEBUG UnitTestFramework: '#run ok: 'two stops and a start and two stops''

2017-07-20 08:10:58 - DEBUG UnitTestFramework: '#teardown: 'two stops and a start and two stops''

2017-07-20 08:10:59 - DEBUG UnitTestFramework: '#teardown ok: 'two stops and a start and two stops''

2017-07-20 08:10:59 - DEBUG UnitTestFramework: '#setup: 'we properly enqueue requests so no then needed''

2017-07-20 08:11:01 - DEBUG UnitTestFramework: '#setup ok: 'we properly enqueue requests so no then needed''

2017-07-20 08:11:01 - DEBUG UnitTestFramework: '#run: 'we properly enqueue requests so no then needed''

2017-07-20 08:11:03 - DEBUG UnitTestFramework: '#run ok: 'we properly enqueue requests so no then needed''

2017-07-20 08:11:03 - DEBUG UnitTestFramework: '#teardown: 'we properly enqueue requests so no then needed''

2017-07-20 08:11:06 - DEBUG UnitTestFramework: '#teardown ok: 'we properly enqueue requests so no then needed''

2017-07-20 08:11:06 - DEBUG UnitTestFramework: '#setup: 'test calculateSeqPointKeyId''

2017-07-20 08:11:08 - DEBUG UnitTestFramework: '#setup ok: 'test calculateSeqPointKeyId''

2017-07-20 08:11:08 - DEBUG UnitTestFramework: '#run: 'test calculateSeqPointKeyId''

2017-07-20 08:11:09 - DEBUG UnitTestFramework: '#run ok: 'test calculateSeqPointKeyId''

2017-07-20 08:11:09 - DEBUG UnitTestFramework: '#teardown: 'test calculateSeqPointKeyId''

2017-07-20 08:11:11 - DEBUG UnitTestFramework: '#teardown ok: 'test calculateSeqPointKeyId''

2017-07-20 08:11:11 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server is not there''

2017-07-20 08:11:12 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server is not there''

2017-07-20 08:11:12 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server is not there''

2017-07-20 08:11:17 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server is not there''

2017-07-20 08:11:17 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server is not there''

2017-07-20 08:11:20 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server is not there''

2017-07-20 08:11:20 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server accepts & closes connection''

2017-07-20 08:11:21 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2017-07-20 08:11:21 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server accepts & closes connection''

2017-07-20 08:11:23 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2017-07-20 08:11:23 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server accepts & closes connection''

2017-07-20 08:11:26 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2017-07-20 08:11:26 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server always returns 500''

2017-07-20 08:11:27 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server always returns 500''

2017-07-20 08:11:27 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server always returns 500''

2017-07-20 08:11:31 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server always returns 500''

2017-07-20 08:11:31 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server always returns 500''

2017-07-20 08:11:32 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server always returns 500''

2017-07-20 08:11:32 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - create new seq doc''

2017-07-20 08:11:34 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - create new seq doc''

2017-07-20 08:11:34 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - create new seq doc''

2017-07-20 08:11:35 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - create new seq doc''

2017-07-20 08:11:35 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - create new seq doc''

2017-07-20 08:11:38 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - create new seq doc''

2017-07-20 08:11:38 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2017-07-20 08:11:41 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2017-07-20 08:11:41 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2017-07-20 08:11:45 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2017-07-20 08:11:45 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2017-07-20 08:11:47 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2017-07-20 08:11:47 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - update seq three times''

2017-07-20 08:11:49 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - update seq three times''

2017-07-20 08:11:49 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - update seq three times''

2017-07-20 08:11:52 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - update seq three times''

2017-07-20 08:11:52 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - update seq three times''

2017-07-20 08:11:53 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - update seq three times''

2017-07-20 08:11:53 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - rev got changed under us''

2017-07-20 08:11:55 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - rev got changed under us''

2017-07-20 08:11:55 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - rev got changed under us''

2017-07-20 08:11:56 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - rev got changed under us''

2017-07-20 08:11:56 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - rev got changed under us''

2017-07-20 08:11:59 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - rev got changed under us''

2017-07-20 08:11:59 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - fail if stop is called''

2017-07-20 08:12:02 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - fail if stop is called''

2017-07-20 08:12:02 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - fail if stop is called''

2017-07-20 08:12:04 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - fail if stop is called''

2017-07-20 08:12:04 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - fail if stop is called''

2017-07-20 08:12:05 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - fail if stop is called''

2017-07-20 08:12:05 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2017-07-20 08:12:07 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2017-07-20 08:12:07 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2017-07-20 08:12:08 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2017-07-20 08:12:08 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2017-07-20 08:12:11 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2017-07-20 08:12:11 - DEBUG UnitTestFramework: '#setup: '#update - fail if stop is called''

2017-07-20 08:12:13 - DEBUG UnitTestFramework: '#setup ok: '#update - fail if stop is called''

2017-07-20 08:12:13 - DEBUG UnitTestFramework: '#run: '#update - fail if stop is called''

2017-07-20 08:12:17 - DEBUG UnitTestFramework: '#run ok: '#update - fail if stop is called''

2017-07-20 08:12:17 - DEBUG UnitTestFramework: '#teardown: '#update - fail if stop is called''

2017-07-20 08:12:19 - DEBUG UnitTestFramework: '#teardown ok: '#update - fail if stop is called''

2017-07-20 08:12:19 - DEBUG UnitTestFramework: '#setup: '#update - set seq for first time''

2017-07-20 08:12:20 - DEBUG UnitTestFramework: '#setup ok: '#update - set seq for first time''

2017-07-20 08:12:20 - DEBUG UnitTestFramework: '#run: '#update - set seq for first time''

2017-07-20 08:12:23 - DEBUG UnitTestFramework: '#run ok: '#update - set seq for first time''

2017-07-20 08:12:23 - DEBUG UnitTestFramework: '#teardown: '#update - set seq for first time''

2017-07-20 08:12:24 - DEBUG UnitTestFramework: '#teardown ok: '#update - set seq for first time''

2017-07-20 08:12:24 - DEBUG UnitTestFramework: '#setup: '#update - Fail on bad seq value''

2017-07-20 08:12:27 - DEBUG UnitTestFramework: '#setup ok: '#update - Fail on bad seq value''

2017-07-20 08:12:27 - DEBUG UnitTestFramework: '#run: '#update - Fail on bad seq value''

2017-07-20 08:12:29 - DEBUG UnitTestFramework: '#run ok: '#update - Fail on bad seq value''

2017-07-20 08:12:29 - DEBUG UnitTestFramework: '#teardown: '#update - Fail on bad seq value''

2017-07-20 08:12:31 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'transport close''

2017-07-20 08:12:32 - DEBUG UnitTestFramework: '#teardown ok: '#update - Fail on bad seq value''

2017-07-20 08:12:32 - DEBUG UnitTestFramework: '#setup: '#update - do we cancel timer properly on an immediate?''

2017-07-20 08:12:41 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'transport close''

2017-07-20 08:13:32 - ERROR UnitTestFramework: '#run failed: '#update - do we cancel timer properly on an immediate?', error: 'TimeoutError: timeout exceeded, event: 'setup_#update - do we cancel timer properly on an immediate?_finished', test: '#update - do we cancel timer properly on an immediate?'', stack: 'TimeoutError: timeout exceeded, event: 'setup_#update - do we cancel timer properly on an immediate?_finished', test: '#update - do we cancel timer properly on an immediate?'
    at afterTimeout (/home/pi/Test/server_1133518512e0667f/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_1133518512e0667f/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-07-20 08:13:32 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'android', error: 'TimeoutError: timeout exceeded, event: 'setup_#update - do we cancel timer properly on an immediate?_finished', test: '#update - do we cancel timer properly on an immediate?'', stack: 'TimeoutError: timeout exceeded, event: 'setup_#update - do we cancel timer properly on an immediate?_finished', test: '#update - do we cancel timer properly on an immediate?'
    at afterTimeout (/home/pi/Test/server_1133518512e0667f/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_1133518512e0667f/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-07-20 08:14:17 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'transport close''

[0;31merror: command 'sudo jx ______.js android' failed with code 1, file 'bash' on line 30[0m
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

android : Error: Command failed: copying android script192.168.1.50
copying android script192.168.1.52
copying android script192.168.1.53
Error: Command failed: Android testing process has failed
 [0m


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

TIMEOUT REACHED. KILLING the APPS
Stopping App:com.thaliproject.thalitest ce061606e320561102 green
Error! Unexpected exit on device ce061606e320561102 app:com.thaliproject.thalitest code:null 
Child process exited with code null on device ce061606e320561102
Android task is completed. [FAILED]
Stopping App:com.thaliproject.thalitest ce061606e320561102 green
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/1133518512e0667f_CI_sanity_check_jareksl/thali01_samsung-SM-G935F.md)

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

TIMEOUT REACHED. KILLING the APPS
Stopping App:com.thaliproject.thalitest ce061606c181d71003 green
Error! Unexpected exit on device ce061606c181d71003 app:com.thaliproject.thalitest code:null 
Child process exited with code null on device ce061606c181d71003
Android task is completed. [FAILED]
Stopping App:com.thaliproject.thalitest ce061606c181d71003 green
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/1133518512e0667f_CI_sanity_check_jareksl/thali03_samsung-SM-G930F.md)

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

TIMEOUT REACHED. KILLING the APPS
Stopping App:com.thaliproject.thalitest ce0616068b9f212302 green
Error! Unexpected exit on device ce0616068b9f212302 app:com.thaliproject.thalitest code:null 
Child process exited with code null on device ce0616068b9f212302
Android task is completed. [FAILED]
Stopping App:com.thaliproject.thalitest ce0616068b9f212302 green
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/1133518512e0667f_CI_sanity_check_jareksl/thali04_samsung-SM-G930F.md)





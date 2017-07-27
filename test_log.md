#### Test 1133518519b464b1 Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 0 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2017-07-27 08:14:48 - INFO HttpServer: 'listening on *:3000'

2017-07-27 08:16:29 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '32d89227-e4c5-4f0a-ab71-1a530ea25c9b', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-27 08:16:29 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-07-27 08:16:43 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: 'f87eaa25-94db-43b0-a816-5397d0dd769d', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-27 08:16:43 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-07-27 08:18:10 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '1f0df06a-24ed-4412-a6ee-4a7c23237896', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-27 08:18:10 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-07-27 08:18:10 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-07-27 08:18:10 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-07-27 08:18:10 - DEBUG UnitTestFramework: 'scheduling tests'

2017-07-27 08:18:12 - DEBUG UnitTestFramework: 'tests scheduled'

2017-07-27 08:18:12 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-07-27 08:18:14 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-07-27 08:18:14 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-07-27 08:18:16 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-07-27 08:18:16 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-07-27 08:18:17 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-07-27 08:18:17 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-07-27 08:18:21 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-07-27 08:18:21 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-07-27 08:18:23 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-07-27 08:18:23 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-07-27 08:18:24 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-07-27 08:18:24 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-27 08:18:26 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-27 08:18:26 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-27 08:18:28 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-27 08:18:28 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-27 08:18:30 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-27 08:18:30 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-27 08:18:32 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-27 08:18:32 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-27 08:18:34 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-27 08:18:34 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-27 08:18:35 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-27 08:18:35 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-07-27 08:18:38 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-27 08:18:38 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-07-27 08:18:38 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-27 08:18:38 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-27 08:18:40 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-27 08:18:40 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-27 08:18:40 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-07-27 08:18:42 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-27 08:18:42 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-27 08:18:44 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-27 08:18:44 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-27 08:18:44 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-27 08:18:44 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-27 08:18:46 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-27 08:18:46 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-27 08:18:46 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-27 08:18:47 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-27 08:18:47 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-27 08:18:51 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-27 08:18:51 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-27 08:18:51 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-27 08:18:51 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-27 08:18:52 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-27 08:18:52 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-27 08:18:52 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-27 08:18:54 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-27 08:18:54 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-27 08:18:57 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-27 08:18:57 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-27 08:18:57 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-27 08:18:57 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-27 08:18:57 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-27 08:18:57 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-27 08:18:57 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-27 08:19:00 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-27 08:19:00 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-07-27 08:19:02 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-07-27 08:19:02 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-07-27 08:19:03 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-07-27 08:19:03 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-07-27 08:19:06 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-07-27 08:19:06 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-07-27 08:19:08 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-07-27 08:19:08 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-07-27 08:19:09 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-07-27 08:19:09 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-07-27 08:19:12 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-07-27 08:19:12 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-07-27 08:19:14 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-07-27 08:19:14 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-07-27 08:19:17 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-07-27 08:19:17 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-07-27 08:19:18 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-07-27 08:19:18 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-07-27 08:19:20 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-07-27 08:19:20 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-07-27 08:19:25 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-07-27 08:19:25 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-07-27 08:19:26 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-07-27 08:19:26 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-07-27 08:19:28 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-07-27 08:19:28 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-07-27 08:19:31 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-07-27 08:19:31 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-07-27 08:19:31 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-07-27 08:19:31 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-07-27 08:19:34 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-07-27 08:19:34 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-07-27 08:19:37 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-07-27 08:19:37 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-07-27 08:19:37 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-07-27 08:19:37 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-07-27 08:19:40 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-07-27 08:19:40 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-07-27 08:19:42 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-07-27 08:19:42 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-07-27 08:19:43 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-07-27 08:19:43 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-07-27 08:19:46 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-07-27 08:19:46 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-07-27 08:19:47 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-07-27 08:19:47 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-07-27 08:19:50 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-07-27 08:19:50 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-07-27 08:19:52 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-07-27 08:19:52 - DEBUG UnitTestFramework: '#run: 'basic''

2017-07-27 08:19:55 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-07-27 08:19:55 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-07-27 08:19:56 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-07-27 08:19:56 - DEBUG UnitTestFramework: '#setup: 'another''

2017-07-27 08:19:57 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-07-27 08:19:57 - DEBUG UnitTestFramework: '#run: 'another''

2017-07-27 08:19:59 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-07-27 08:19:59 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-07-27 08:20:00 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-07-27 08:20:00 - DEBUG UnitTestFramework: '#setup: 'skip''

2017-07-27 08:20:02 - DEBUG UnitTestFramework: '#setup ok: 'skip''

2017-07-27 08:20:02 - DEBUG UnitTestFramework: '#run: 'skip''

2017-07-27 08:20:02 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-07-27 08:20:03 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-07-27 08:20:04 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-07-27 08:20:04 - DEBUG UnitTestFramework: '#run ok: 'skip''

2017-07-27 08:20:04 - DEBUG UnitTestFramework: '#teardown: 'skip''

2017-07-27 08:20:06 - DEBUG UnitTestFramework: '#teardown ok: 'skip''

2017-07-27 08:20:06 - DEBUG UnitTestFramework: '#setup: 'another skip''

2017-07-27 08:20:08 - DEBUG UnitTestFramework: '#setup ok: 'another skip''

2017-07-27 08:20:08 - DEBUG UnitTestFramework: '#run: 'another skip''

2017-07-27 08:20:08 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-07-27 08:20:08 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-07-27 08:20:09 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-07-27 08:20:09 - DEBUG UnitTestFramework: '#run ok: 'another skip''

2017-07-27 08:20:09 - DEBUG UnitTestFramework: '#teardown: 'another skip''

2017-07-27 08:20:11 - DEBUG UnitTestFramework: '#teardown ok: 'another skip''

2017-07-27 08:20:11 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox spy''

2017-07-27 08:20:13 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox spy''

2017-07-27 08:20:13 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox spy''

2017-07-27 08:20:14 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox spy''

2017-07-27 08:20:14 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox spy''

2017-07-27 08:20:15 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox spy''

2017-07-27 08:20:15 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub''

2017-07-27 08:20:17 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub''

2017-07-27 08:20:17 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub''

2017-07-27 08:20:18 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub''

2017-07-27 08:20:18 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub''

2017-07-27 08:20:21 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub''

2017-07-27 08:20:21 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub override''

2017-07-27 08:20:23 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub override''

2017-07-27 08:20:23 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub override''

2017-07-27 08:20:25 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub override''

2017-07-27 08:20:25 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub override''

2017-07-27 08:20:27 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub override''

2017-07-27 08:20:27 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox mock''

2017-07-27 08:20:28 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox mock''

2017-07-27 08:20:28 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox mock''

2017-07-27 08:20:30 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox mock''

2017-07-27 08:20:30 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox mock''

2017-07-27 08:20:31 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox mock''

2017-07-27 08:20:31 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox restore after test end''

2017-07-27 08:20:34 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox restore after test end''

2017-07-27 08:20:34 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox restore after test end''

2017-07-27 08:20:36 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox restore after test end''

2017-07-27 08:20:36 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox restore after test end''

2017-07-27 08:20:37 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox restore after test end''

2017-07-27 08:20:37 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-07-27 08:20:39 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-07-27 08:20:39 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-07-27 08:20:42 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-07-27 08:20:42 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-07-27 08:20:43 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-07-27 08:20:43 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-07-27 08:20:46 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-07-27 08:20:46 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-07-27 08:20:48 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-07-27 08:20:48 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-07-27 08:20:51 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-07-27 08:20:51 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-07-27 08:20:54 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-07-27 08:20:54 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-07-27 08:20:55 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-07-27 08:20:55 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-07-27 08:20:58 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-07-27 08:20:58 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-07-27 08:21:00 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-07-27 08:21:00 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-07-27 08:21:00 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-07-27 08:21:00 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-07-27 08:21:03 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-07-27 08:21:03 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-07-27 08:21:04 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-07-27 08:21:04 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-07-27 08:21:08 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-07-27 08:21:08 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-07-27 08:21:10 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-07-27 08:21:10 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-27 08:21:11 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-27 08:21:11 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-27 08:21:15 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-27 08:21:15 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-27 08:21:18 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-27 08:21:18 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-27 08:21:21 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-27 08:21:21 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-27 08:21:23 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-27 08:21:23 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-27 08:21:25 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-27 08:21:25 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-27 08:21:27 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-27 08:21:27 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-27 08:21:30 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-27 08:21:30 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-27 08:21:32 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-27 08:21:32 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-27 08:21:34 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-27 08:21:34 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-27 08:21:37 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-27 08:21:37 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-27 08:21:39 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-27 08:21:39 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-27 08:21:41 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-27 08:21:41 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-27 08:21:43 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-27 08:21:43 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-27 08:21:44 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-27 08:21:44 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-07-27 08:21:47 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-07-27 08:21:47 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-07-27 08:21:52 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-07-27 08:21:52 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-07-27 08:21:55 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-07-27 08:21:55 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-07-27 08:21:56 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-07-27 08:21:56 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-07-27 08:22:10 - DEBUG UnitTestFramework: '#run ok: 'Can connect to a remote peer''

2017-07-27 08:22:10 - DEBUG UnitTestFramework: '#teardown: 'Can connect to a remote peer''

2017-07-27 08:22:13 - DEBUG UnitTestFramework: '#teardown ok: 'Can connect to a remote peer''

2017-07-27 08:22:13 - DEBUG UnitTestFramework: '#setup: 'Can shift data''

2017-07-27 08:22:16 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data''

2017-07-27 08:22:16 - DEBUG UnitTestFramework: '#run: 'Can shift data''

2017-07-27 08:22:25 - DEBUG UnitTestFramework: '#run ok: 'Can shift data''

2017-07-27 08:22:25 - DEBUG UnitTestFramework: '#teardown: 'Can shift data''

2017-07-27 08:22:27 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data''
2017-07-27 08:22:27 - DEBUG UnitTestFramework: '#setup: 'Can shift data via parallel connections''

2017-07-27 08:22:29 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data via parallel connections''

2017-07-27 08:22:29 - DEBUG UnitTestFramework: '#run: 'Can shift data via parallel connections''

2017-07-27 08:22:29 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-07-27 08:22:30 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-07-27 08:22:32 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-07-27 08:22:32 - DEBUG UnitTestFramework: '#run ok: 'Can shift data via parallel connections''

2017-07-27 08:22:32 - DEBUG UnitTestFramework: '#teardown: 'Can shift data via parallel connections''

2017-07-27 08:22:33 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data via parallel connections''

2017-07-27 08:22:33 - DEBUG UnitTestFramework: '#setup: 'Can shift data securely''

2017-07-27 08:22:35 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data securely''

2017-07-27 08:22:35 - DEBUG UnitTestFramework: '#run: 'Can shift data securely''

2017-07-27 08:22:47 - DEBUG UnitTestFramework: '#run ok: 'Can shift data securely''

2017-07-27 08:22:47 - DEBUG UnitTestFramework: '#teardown: 'Can shift data securely''

2017-07-27 08:22:52 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data securely''

2017-07-27 08:22:52 - DEBUG UnitTestFramework: '#setup: 'Can shift large amounts of data''

2017-07-27 08:22:55 - DEBUG UnitTestFramework: '#setup ok: 'Can shift large amounts of data''

2017-07-27 08:22:55 - DEBUG UnitTestFramework: '#run: 'Can shift large amounts of data''

2017-07-27 08:23:03 - DEBUG UnitTestFramework: '#run ok: 'Can shift large amounts of data''

2017-07-27 08:23:03 - DEBUG UnitTestFramework: '#teardown: 'Can shift large amounts of data''

2017-07-27 08:23:06 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift large amounts of data''

2017-07-27 08:23:06 - DEBUG UnitTestFramework: '#setup: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-27 08:23:07 - DEBUG UnitTestFramework: '#setup ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-27 08:23:07 - DEBUG UnitTestFramework: '#run: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-27 08:23:15 - DEBUG UnitTestFramework: '#run ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-27 08:23:15 - DEBUG UnitTestFramework: '#teardown: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-27 08:23:17 - DEBUG UnitTestFramework: '#teardown ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-27 08:23:17 - DEBUG UnitTestFramework: '#setup: 'Test updating advertising and parallel data transfer''

2017-07-27 08:23:18 - DEBUG UnitTestFramework: '#setup ok: 'Test updating advertising and parallel data transfer''

2017-07-27 08:23:18 - DEBUG UnitTestFramework: '#run: 'Test updating advertising and parallel data transfer''

2017-07-27 08:23:18 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-07-27 08:23:20 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-07-27 08:23:20 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-07-27 08:23:20 - DEBUG UnitTestFramework: '#run ok: 'Test updating advertising and parallel data transfer''

2017-07-27 08:23:20 - DEBUG UnitTestFramework: '#teardown: 'Test updating advertising and parallel data transfer''

2017-07-27 08:23:24 - DEBUG UnitTestFramework: '#teardown ok: 'Test updating advertising and parallel data transfer''

2017-07-27 08:23:24 - DEBUG UnitTestFramework: '#setup: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-27 08:23:27 - DEBUG UnitTestFramework: '#setup ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-27 08:23:27 - DEBUG UnitTestFramework: '#run: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-27 08:23:32 - DEBUG UnitTestFramework: '#run ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-27 08:23:32 - DEBUG UnitTestFramework: '#teardown: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-27 08:23:35 - DEBUG UnitTestFramework: '#teardown ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-27 08:23:35 - DEBUG UnitTestFramework: '#setup: 'cannot call connect when start listening for advertisements is not active''

2017-07-27 08:23:37 - DEBUG UnitTestFramework: '#setup ok: 'cannot call connect when start listening for advertisements is not active''

2017-07-27 08:23:37 - DEBUG UnitTestFramework: '#run: 'cannot call connect when start listening for advertisements is not active''

2017-07-27 08:23:40 - DEBUG UnitTestFramework: '#run ok: 'cannot call connect when start listening for advertisements is not active''

2017-07-27 08:23:40 - DEBUG UnitTestFramework: '#teardown: 'cannot call connect when start listening for advertisements is not active''

2017-07-27 08:23:42 - DEBUG UnitTestFramework: '#teardown ok: 'cannot call connect when start listening for advertisements is not active''

2017-07-27 08:23:42 - DEBUG UnitTestFramework: '#setup: 'Get error when trying to double connect to a peer on Android''

2017-07-27 08:23:45 - DEBUG UnitTestFramework: '#setup ok: 'Get error when trying to double connect to a peer on Android''

2017-07-27 08:23:45 - DEBUG UnitTestFramework: '#run: 'Get error when trying to double connect to a peer on Android''

2017-07-27 08:23:45 - INFO Socket: 'run skipped, test: 'Get error when trying to double connect to a peer on Android', event: 'run_Get error when trying to double connect to a peer on Android''

2017-07-27 08:23:45 - INFO Socket: 'run skipped, test: 'Get error when trying to double connect to a peer on Android', event: 'run_Get error when trying to double connect to a peer on Android''

2017-07-27 08:23:46 - INFO Socket: 'run skipped, test: 'Get error when trying to double connect to a peer on Android', event: 'run_Get error when trying to double connect to a peer on Android''

2017-07-27 08:23:46 - DEBUG UnitTestFramework: '#run ok: 'Get error when trying to double connect to a peer on Android''

2017-07-27 08:23:46 - DEBUG UnitTestFramework: '#teardown: 'Get error when trying to double connect to a peer on Android''

2017-07-27 08:23:48 - DEBUG UnitTestFramework: '#teardown ok: 'Get error when trying to double connect to a peer on Android''

2017-07-27 08:23:48 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-27 08:23:49 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-27 08:23:49 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-27 08:24:05 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-27 08:24:05 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-27 08:24:07 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-27 08:24:07 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-27 08:24:08 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-27 08:24:08 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-27 08:24:08 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection', event: 'run_#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-27 08:24:10 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection', event: 'run_#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-27 08:24:11 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection', event: 'run_#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-27 08:24:11 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-27 08:24:11 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-27 08:24:14 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-27 08:24:14 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-27 08:24:14 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-27 08:24:14 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-27 08:24:14 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer', event: 'run_#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-27 08:24:17 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer', event: 'run_#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-27 08:24:17 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer', event: 'run_#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-27 08:24:17 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-27 08:24:17 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-27 08:24:20 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-27 08:24:20 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-27 08:24:22 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-27 08:24:22 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-27 08:24:28 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-27 08:24:28 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-27 08:24:31 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-27 08:24:31 - DEBUG UnitTestFramework: '#setup: 'initial peer discovery''

2017-07-27 08:24:33 - DEBUG UnitTestFramework: '#setup ok: 'initial peer discovery''

2017-07-27 08:24:33 - DEBUG UnitTestFramework: '#run: 'initial peer discovery''

2017-07-27 08:24:33 - INFO Socket: 'run skipped, test: 'initial peer discovery', event: 'run_initial peer discovery''

2017-07-27 08:24:33 - INFO Socket: 'run skipped, test: 'initial peer discovery', event: 'run_initial peer discovery''

2017-07-27 08:24:35 - INFO Socket: 'run skipped, test: 'initial peer discovery', event: 'run_initial peer discovery''

2017-07-27 08:24:35 - DEBUG UnitTestFramework: '#run ok: 'initial peer discovery''

2017-07-27 08:24:35 - DEBUG UnitTestFramework: '#teardown: 'initial peer discovery''

2017-07-27 08:24:36 - DEBUG UnitTestFramework: '#teardown ok: 'initial peer discovery''

2017-07-27 08:24:36 - DEBUG UnitTestFramework: '#setup: 'update peer discovery 1''

2017-07-27 08:24:38 - DEBUG UnitTestFramework: '#setup ok: 'update peer discovery 1''

2017-07-27 08:24:38 - DEBUG UnitTestFramework: '#run: 'update peer discovery 1''

2017-07-27 08:24:38 - INFO Socket: 'run skipped, test: 'update peer discovery 1', event: 'run_update peer discovery 1''

2017-07-27 08:24:38 - INFO Socket: 'run skipped, test: 'update peer discovery 1', event: 'run_update peer discovery 1''

2017-07-27 08:24:39 - INFO Socket: 'run skipped, test: 'update peer discovery 1', event: 'run_update peer discovery 1''

2017-07-27 08:24:39 - DEBUG UnitTestFramework: '#run ok: 'update peer discovery 1''

2017-07-27 08:24:39 - DEBUG UnitTestFramework: '#teardown: 'update peer discovery 1''

2017-07-27 08:24:40 - DEBUG UnitTestFramework: '#teardown ok: 'update peer discovery 1''

2017-07-27 08:24:40 - DEBUG UnitTestFramework: '#setup: 'update peer discovery 2''

2017-07-27 08:24:42 - DEBUG UnitTestFramework: '#setup ok: 'update peer discovery 2''

2017-07-27 08:24:42 - DEBUG UnitTestFramework: '#run: 'update peer discovery 2''

2017-07-27 08:24:42 - INFO Socket: 'run skipped, test: 'update peer discovery 2', event: 'run_update peer discovery 2''

2017-07-27 08:24:43 - INFO Socket: 'run skipped, test: 'update peer discovery 2', event: 'run_update peer discovery 2''

2017-07-27 08:24:45 - INFO Socket: 'run skipped, test: 'update peer discovery 2', event: 'run_update peer discovery 2''

2017-07-27 08:24:45 - DEBUG UnitTestFramework: '#run ok: 'update peer discovery 2''

2017-07-27 08:24:45 - DEBUG UnitTestFramework: '#teardown: 'update peer discovery 2''

2017-07-27 08:24:46 - DEBUG UnitTestFramework: '#teardown ok: 'update peer discovery 2''

2017-07-27 08:24:46 - DEBUG UnitTestFramework: '#setup: 'check latest peer discovery''

2017-07-27 08:24:48 - DEBUG UnitTestFramework: '#setup ok: 'check latest peer discovery''

2017-07-27 08:24:48 - DEBUG UnitTestFramework: '#run: 'check latest peer discovery''

2017-07-27 08:24:48 - INFO Socket: 'run skipped, test: 'check latest peer discovery', event: 'run_check latest peer discovery''

2017-07-27 08:24:49 - INFO Socket: 'run skipped, test: 'check latest peer discovery', event: 'run_check latest peer discovery''

2017-07-27 08:24:51 - INFO Socket: 'run skipped, test: 'check latest peer discovery', event: 'run_check latest peer discovery''

2017-07-27 08:24:51 - DEBUG UnitTestFramework: '#run ok: 'check latest peer discovery''

2017-07-27 08:24:51 - DEBUG UnitTestFramework: '#teardown: 'check latest peer discovery''

2017-07-27 08:24:52 - DEBUG UnitTestFramework: '#teardown ok: 'check latest peer discovery''

2017-07-27 08:24:52 - DEBUG UnitTestFramework: '#setup: 'Set up for no peer discovery test''

2017-07-27 08:24:55 - DEBUG UnitTestFramework: '#setup ok: 'Set up for no peer discovery test''

2017-07-27 08:24:55 - DEBUG UnitTestFramework: '#run: 'Set up for no peer discovery test''

2017-07-27 08:24:55 - INFO Socket: 'run skipped, test: 'Set up for no peer discovery test', event: 'run_Set up for no peer discovery test''

2017-07-27 08:24:56 - INFO Socket: 'run skipped, test: 'Set up for no peer discovery test', event: 'run_Set up for no peer discovery test''

2017-07-27 08:24:57 - INFO Socket: 'run skipped, test: 'Set up for no peer discovery test', event: 'run_Set up for no peer discovery test''

2017-07-27 08:24:57 - DEBUG UnitTestFramework: '#run ok: 'Set up for no peer discovery test''
2017-07-27 08:24:57 - DEBUG UnitTestFramework: '#teardown: 'Set up for no peer discovery test''

2017-07-27 08:24:58 - DEBUG UnitTestFramework: '#teardown ok: 'Set up for no peer discovery test''

2017-07-27 08:24:58 - DEBUG UnitTestFramework: '#setup: 'no peer discovery''

2017-07-27 08:25:00 - DEBUG UnitTestFramework: '#setup ok: 'no peer discovery''

2017-07-27 08:25:00 - DEBUG UnitTestFramework: '#run: 'no peer discovery''

2017-07-27 08:25:00 - INFO Socket: 'run skipped, test: 'no peer discovery', event: 'run_no peer discovery''

2017-07-27 08:25:00 - INFO Socket: 'run skipped, test: 'no peer discovery', event: 'run_no peer discovery''

2017-07-27 08:25:01 - INFO Socket: 'run skipped, test: 'no peer discovery', event: 'run_no peer discovery''

2017-07-27 08:25:01 - DEBUG UnitTestFramework: '#run ok: 'no peer discovery''

2017-07-27 08:25:01 - DEBUG UnitTestFramework: '#teardown: 'no peer discovery''

2017-07-27 08:25:03 - DEBUG UnitTestFramework: '#teardown ok: 'no peer discovery''

2017-07-27 08:25:03 - DEBUG UnitTestFramework: '#setup: 'calling createNativeListener directly rejects''

2017-07-27 08:25:06 - DEBUG UnitTestFramework: '#setup ok: 'calling createNativeListener directly rejects''

2017-07-27 08:25:06 - DEBUG UnitTestFramework: '#run: 'calling createNativeListener directly rejects''

2017-07-27 08:25:07 - DEBUG UnitTestFramework: '#run ok: 'calling createNativeListener directly rejects''

2017-07-27 08:25:07 - DEBUG UnitTestFramework: '#teardown: 'calling createNativeListener directly rejects''

2017-07-27 08:25:09 - DEBUG UnitTestFramework: '#teardown ok: 'calling createNativeListener directly rejects''

2017-07-27 08:25:09 - DEBUG UnitTestFramework: '#setup: 'emits incomingConnectionState''

2017-07-27 08:25:10 - DEBUG UnitTestFramework: '#setup ok: 'emits incomingConnectionState''

2017-07-27 08:25:10 - DEBUG UnitTestFramework: '#run: 'emits incomingConnectionState''

2017-07-27 08:25:12 - DEBUG UnitTestFramework: '#run ok: 'emits incomingConnectionState''

2017-07-27 08:25:12 - DEBUG UnitTestFramework: '#teardown: 'emits incomingConnectionState''

2017-07-27 08:25:15 - DEBUG UnitTestFramework: '#teardown ok: 'emits incomingConnectionState''

2017-07-27 08:25:15 - DEBUG UnitTestFramework: '#setup: 'emits routerPortConnectionFailed''

2017-07-27 08:25:17 - DEBUG UnitTestFramework: '#setup ok: 'emits routerPortConnectionFailed''

2017-07-27 08:25:17 - DEBUG UnitTestFramework: '#run: 'emits routerPortConnectionFailed''

2017-07-27 08:25:21 - DEBUG UnitTestFramework: '#run ok: 'emits routerPortConnectionFailed''

2017-07-27 08:25:21 - DEBUG UnitTestFramework: '#teardown: 'emits routerPortConnectionFailed''

2017-07-27 08:25:23 - DEBUG UnitTestFramework: '#teardown ok: 'emits routerPortConnectionFailed''

2017-07-27 08:25:23 - DEBUG UnitTestFramework: '#setup: 'native server connections all up''

2017-07-27 08:25:25 - DEBUG UnitTestFramework: '#setup ok: 'native server connections all up''

2017-07-27 08:25:25 - DEBUG UnitTestFramework: '#run: 'native server connections all up''

2017-07-27 08:25:27 - DEBUG UnitTestFramework: '#run ok: 'native server connections all up''

2017-07-27 08:25:27 - DEBUG UnitTestFramework: '#teardown: 'native server connections all up''

2017-07-27 08:25:28 - DEBUG UnitTestFramework: '#teardown ok: 'native server connections all up''

2017-07-27 08:25:28 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming stream cleans outgoing socket''

2017-07-27 08:25:30 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming stream cleans outgoing socket''

2017-07-27 08:25:30 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming stream cleans outgoing socket''

2017-07-27 08:25:33 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming stream cleans outgoing socket''

2017-07-27 08:25:33 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming stream cleans outgoing socket''

2017-07-27 08:25:35 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming stream cleans outgoing socket''

2017-07-27 08:25:35 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming connection cleans outgoing socket''

2017-07-27 08:25:36 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming connection cleans outgoing socket''

2017-07-27 08:25:36 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming connection cleans outgoing socket''

2017-07-27 08:25:38 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming connection cleans outgoing socket''

2017-07-27 08:25:38 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming connection cleans outgoing socket''

2017-07-27 08:25:39 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming connection cleans outgoing socket''

2017-07-27 08:25:39 - DEBUG UnitTestFramework: '#setup: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-27 08:25:41 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-27 08:25:41 - DEBUG UnitTestFramework: '#run: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-27 08:25:42 - DEBUG UnitTestFramework: '#run ok: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-27 08:25:42 - DEBUG UnitTestFramework: '#teardown: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-27 08:25:44 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-27 08:25:44 - DEBUG UnitTestFramework: '#setup: 'native server - closing the whole server cleans everything up''

2017-07-27 08:25:47 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing the whole server cleans everything up''

2017-07-27 08:25:47 - DEBUG UnitTestFramework: '#run: 'native server - closing the whole server cleans everything up''

2017-07-27 08:25:48 - DEBUG UnitTestFramework: '#run ok: 'native server - closing the whole server cleans everything up''

2017-07-27 08:25:48 - DEBUG UnitTestFramework: '#teardown: 'native server - closing the whole server cleans everything up''

2017-07-27 08:25:51 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing the whole server cleans everything up''

2017-07-27 08:25:51 - DEBUG UnitTestFramework: '#setup: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-27 08:25:54 - DEBUG UnitTestFramework: '#setup ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-27 08:25:54 - DEBUG UnitTestFramework: '#run: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-27 08:25:57 - DEBUG UnitTestFramework: '#run ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-27 08:25:57 - DEBUG UnitTestFramework: '#teardown: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-27 08:26:00 - DEBUG UnitTestFramework: '#teardown ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-27 08:26:00 - DEBUG UnitTestFramework: '#setup: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-27 08:26:01 - DEBUG UnitTestFramework: '#setup ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-27 08:26:01 - DEBUG UnitTestFramework: '#run: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-27 08:26:03 - DEBUG UnitTestFramework: '#run ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-27 08:26:03 - DEBUG UnitTestFramework: '#teardown: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-27 08:26:06 - DEBUG UnitTestFramework: '#teardown ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-27 08:26:06 - DEBUG UnitTestFramework: '#setup: 'native server - timing out the incoming connection cleans everything up''

2017-07-27 08:26:07 - DEBUG UnitTestFramework: '#setup ok: 'native server - timing out the incoming connection cleans everything up''

2017-07-27 08:26:07 - DEBUG UnitTestFramework: '#run: 'native server - timing out the incoming connection cleans everything up''

2017-07-27 08:26:10 - DEBUG UnitTestFramework: '#run ok: 'native server - timing out the incoming connection cleans everything up''

2017-07-27 08:26:10 - DEBUG UnitTestFramework: '#teardown: 'native server - timing out the incoming connection cleans everything up''

2017-07-27 08:26:12 - DEBUG UnitTestFramework: '#teardown ok: 'native server - timing out the incoming connection cleans everything up''

2017-07-27 08:26:12 - DEBUG UnitTestFramework: '#setup: 'can create servers manager''

2017-07-27 08:26:13 - DEBUG UnitTestFramework: '#setup ok: 'can create servers manager''

2017-07-27 08:26:13 - DEBUG UnitTestFramework: '#run: 'can create servers manager''

2017-07-27 08:26:16 - DEBUG UnitTestFramework: '#run ok: 'can create servers manager''

2017-07-27 08:26:16 - DEBUG UnitTestFramework: '#teardown: 'can create servers manager''

2017-07-27 08:26:18 - DEBUG UnitTestFramework: '#teardown ok: 'can create servers manager''

2017-07-27 08:26:18 - DEBUG UnitTestFramework: '#setup: 'calling stop without start causes error''

2017-07-27 08:26:19 - DEBUG UnitTestFramework: '#setup ok: 'calling stop without start causes error''

2017-07-27 08:26:19 - DEBUG UnitTestFramework: '#run: 'calling stop without start causes error''

2017-07-27 08:26:21 - DEBUG UnitTestFramework: '#run ok: 'calling stop without start causes error''

2017-07-27 08:26:21 - DEBUG UnitTestFramework: '#teardown: 'calling stop without start causes error''

2017-07-27 08:26:24 - DEBUG UnitTestFramework: '#teardown ok: 'calling stop without start causes error''

2017-07-27 08:26:24 - DEBUG UnitTestFramework: '#setup: 'can start/stop servers manager''

2017-07-27 08:26:25 - DEBUG UnitTestFramework: '#setup ok: 'can start/stop servers manager''

2017-07-27 08:26:25 - DEBUG UnitTestFramework: '#run: 'can start/stop servers manager''

2017-07-27 08:26:27 - DEBUG UnitTestFramework: '#run ok: 'can start/stop servers manager''

2017-07-27 08:26:27 - DEBUG UnitTestFramework: '#teardown: 'can start/stop servers manager''

2017-07-27 08:26:30 - DEBUG UnitTestFramework: '#teardown ok: 'can start/stop servers manager''

2017-07-27 08:26:30 - DEBUG UnitTestFramework: '#setup: 'starting twice resolves with listening port''

2017-07-27 08:26:31 - DEBUG UnitTestFramework: '#setup ok: 'starting twice resolves with listening port''

2017-07-27 08:26:31 - DEBUG UnitTestFramework: '#run: 'starting twice resolves with listening port''

2017-07-27 08:26:33 - DEBUG UnitTestFramework: '#run ok: 'starting twice resolves with listening port''

2017-07-27 08:26:33 - DEBUG UnitTestFramework: '#teardown: 'starting twice resolves with listening port''

2017-07-27 08:26:34 - DEBUG UnitTestFramework: '#teardown ok: 'starting twice resolves with listening port''

2017-07-27 08:26:34 - DEBUG UnitTestFramework: '#setup: 'terminateIncomingConnection will terminate a connection''

2017-07-27 08:26:36 - DEBUG UnitTestFramework: '#setup ok: 'terminateIncomingConnection will terminate a connection''

2017-07-27 08:26:36 - DEBUG UnitTestFramework: '#run: 'terminateIncomingConnection will terminate a connection''

2017-07-27 08:26:37 - DEBUG UnitTestFramework: '#run ok: 'terminateIncomingConnection will terminate a connection''

2017-07-27 08:26:37 - DEBUG UnitTestFramework: '#teardown: 'terminateIncomingConnection will terminate a connection''

2017-07-27 08:26:38 - DEBUG UnitTestFramework: '#teardown ok: 'terminateIncomingConnection will terminate a connection''

2017-07-27 08:26:38 - DEBUG UnitTestFramework: '#setup: 'terminate an Outgoing connection''

2017-07-27 08:26:40 - DEBUG UnitTestFramework: '#setup ok: 'terminate an Outgoing connection''

2017-07-27 08:26:40 - DEBUG UnitTestFramework: '#run: 'terminate an Outgoing connection''

2017-07-27 08:26:43 - DEBUG UnitTestFramework: '#run ok: 'terminate an Outgoing connection''

2017-07-27 08:26:43 - DEBUG UnitTestFramework: '#teardown: 'terminate an Outgoing connection''

2017-07-27 08:26:43 - DEBUG UnitTestFramework: '#teardown ok: 'terminate an Outgoing connection''

2017-07-27 08:26:43 - DEBUG UnitTestFramework: '#setup: 'Single local http request''

2017-07-27 08:26:44 - DEBUG UnitTestFramework: '#setup ok: 'Single local http request''

2017-07-27 08:26:44 - DEBUG UnitTestFramework: '#run: 'Single local http request''

2017-07-27 08:26:46 - DEBUG UnitTestFramework: '#run ok: 'Single local http request''

2017-07-27 08:26:46 - DEBUG UnitTestFramework: '#teardown: 'Single local http request''

2017-07-27 08:26:51 - DEBUG UnitTestFramework: '#teardown ok: 'Single local http request''

2017-07-27 08:26:51 - DEBUG UnitTestFramework: '#setup: 'Single coordinated request ios native''

2017-07-27 08:26:55 - DEBUG UnitTestFramework: '#setup ok: 'Single coordinated request ios native''

2017-07-27 08:26:55 - DEBUG UnitTestFramework: '#run: 'Single coordinated request ios native''

2017-07-27 08:26:55 - INFO Socket: 'run skipped, test: 'Single coordinated request ios native', event: 'run_Single coordinated request ios native''

2017-07-27 08:26:55 - INFO Socket: 'run skipped, test: 'Single coordinated request ios native', event: 'run_Single coordinated request ios native''

2017-07-27 08:26:56 - INFO Socket: 'run skipped, test: 'Single coordinated request ios native', event: 'run_Single coordinated request ios native''

2017-07-27 08:26:56 - DEBUG UnitTestFramework: '#run ok: 'Single coordinated request ios native''

2017-07-27 08:26:56 - DEBUG UnitTestFramework: '#teardown: 'Single coordinated request ios native''

2017-07-27 08:26:58 - DEBUG UnitTestFramework: '#teardown ok: 'Single coordinated request ios native''

2017-07-27 08:26:58 - DEBUG UnitTestFramework: '#setup: 'Multiple local http requests''

2017-07-27 08:26:59 - DEBUG UnitTestFramework: '#setup ok: 'Multiple local http requests''

2017-07-27 08:26:59 - DEBUG UnitTestFramework: '#run: 'Multiple local http requests''

2017-07-27 08:27:01 - DEBUG UnitTestFramework: '#run ok: 'Multiple local http requests''

2017-07-27 08:27:01 - DEBUG UnitTestFramework: '#teardown: 'Multiple local http requests''

2017-07-27 08:27:03 - DEBUG UnitTestFramework: '#teardown ok: 'Multiple local http requests''

2017-07-27 08:27:03 - DEBUG UnitTestFramework: '#setup: 'Multiple coordinated request ios native''

2017-07-27 08:27:05 - DEBUG UnitTestFramework: '#setup ok: 'Multiple coordinated request ios native''

2017-07-27 08:27:05 - DEBUG UnitTestFramework: '#run: 'Multiple coordinated request ios native''

2017-07-27 08:27:05 - INFO Socket: 'run skipped, test: 'Multiple coordinated request ios native', event: 'run_Multiple coordinated request ios native''

2017-07-27 08:27:06 - INFO Socket: 'run skipped, test: 'Multiple coordinated request ios native', event: 'run_Multiple coordinated request ios native''

2017-07-27 08:27:07 - INFO Socket: 'run skipped, test: 'Multiple coordinated request ios native', event: 'run_Multiple coordinated request ios native''

2017-07-27 08:27:07 - DEBUG UnitTestFramework: '#run ok: 'Multiple coordinated request ios native''

2017-07-27 08:27:07 - DEBUG UnitTestFramework: '#teardown: 'Multiple coordinated request ios native''

2017-07-27 08:27:09 - DEBUG UnitTestFramework: '#teardown ok: 'Multiple coordinated request ios native''

2017-07-27 08:27:09 - DEBUG UnitTestFramework: '#setup: '#startListeningForAdvertisements should fail if start not called''

2017-07-27 08:27:11 - DEBUG UnitTestFramework: '#setup ok: '#startListeningForAdvertisements should fail if start not called''

2017-07-27 08:27:11 - DEBUG UnitTestFramework: '#run: '#startListeningForAdvertisements should fail if start not called''

2017-07-27 08:27:13 - DEBUG UnitTestFramework: '#run ok: '#startListeningForAdvertisements should fail if start not called''

2017-07-27 08:27:13 - DEBUG UnitTestFramework: '#teardown: '#startListeningForAdvertisements should fail if start not called''

2017-07-27 08:27:15 - DEBUG UnitTestFramework: '#teardown ok: '#startListeningForAdvertisements should fail if start not called''

2017-07-27 08:27:15 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-27 08:27:17 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-27 08:27:17 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-27 08:27:18 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-27 08:27:18 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-27 08:27:21 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-27 08:27:21 - DEBUG UnitTestFramework: '#setup: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-27 08:27:25 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-27 08:27:25 - DEBUG UnitTestFramework: '#run: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-27 08:27:27 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-27 08:27:27 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-27 08:27:28 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-27 08:27:28 - DEBUG UnitTestFramework: '#setup: 'should be able to call #startListeningForAdvertisements many times''

2017-07-27 08:27:30 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #startListeningForAdvertisements many times''

2017-07-27 08:27:30 - DEBUG UnitTestFramework: '#run: 'should be able to call #startListeningForAdvertisements many times''

2017-07-27 08:27:31 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #startListeningForAdvertisements many times''

2017-07-27 08:27:31 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #startListeningForAdvertisements many times''

2017-07-27 08:27:33 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #startListeningForAdvertisements many times''

2017-07-27 08:27:33 - DEBUG UnitTestFramework: '#setup: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-27 08:27:34 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-27 08:27:34 - DEBUG UnitTestFramework: '#run: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-27 08:27:37 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-27 08:27:37 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-27 08:27:40 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-27 08:27:40 - DEBUG UnitTestFramework: '#setup: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-27 08:27:41 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-27 08:27:41 - DEBUG UnitTestFramework: '#run: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-27 08:27:44 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-27 08:27:44 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-27 08:27:46 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-27 08:27:46 - DEBUG UnitTestFramework: '#setup: '#start - Causing native or wifi to fail will cause a promise reject ''

2017-07-27 08:27:48 - DEBUG UnitTestFramework: '#setup ok: '#start - Causing native or wifi to fail will cause a promise reject ''

2017-07-27 08:27:48 - DEBUG UnitTestFramework: '#run: '#start - Causing native or wifi to fail will cause a promise reject ''

2017-07-27 08:27:51 - DEBUG UnitTestFramework: '#run ok: '#start - Causing native or wifi to fail will cause a promise reject ''

2017-07-27 08:27:51 - DEBUG UnitTestFramework: '#teardown: '#start - Causing native or wifi to fail will cause a promise reject ''

2017-07-27 08:27:55 - DEBUG UnitTestFramework: '#teardown ok: '#start - Causing native or wifi to fail will cause a promise reject ''

2017-07-27 08:27:55 - DEBUG UnitTestFramework: '#setup: '#start should fail if called twice in a row''

2017-07-27 08:27:57 - DEBUG UnitTestFramework: '#setup ok: '#start should fail if called twice in a row''

2017-07-27 08:27:57 - DEBUG UnitTestFramework: '#run: '#start should fail if called twice in a row''

2017-07-27 08:27:58 - DEBUG UnitTestFramework: '#run ok: '#start should fail if called twice in a row''

2017-07-27 08:27:58 - DEBUG UnitTestFramework: '#teardown: '#start should fail if called twice in a row''

2017-07-27 08:28:00 - DEBUG UnitTestFramework: '#teardown ok: '#start should fail if called twice in a row''

2017-07-27 08:28:00 - DEBUG UnitTestFramework: '#setup: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-07-27 08:28:02 - DEBUG UnitTestFramework: '#setup ok: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-07-27 08:28:02 - DEBUG UnitTestFramework: '#run: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-07-27 08:28:02 - INFO Socket: 'run skipped, test: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)', event: 'run_#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-07-27 08:28:03 - INFO Socket: 'run skipped, test: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)', event: 'run_#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-07-27 08:28:03 - INFO Socket: 'run skipped, test: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)', event: 'run_#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-07-27 08:28:03 - DEBUG UnitTestFramework: '#run ok: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-07-27 08:28:03 - DEBUG UnitTestFramework: '#teardown: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-07-27 08:28:06 - DEBUG UnitTestFramework: '#teardown ok: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-07-27 08:28:06 - DEBUG UnitTestFramework: '#setup: 'does not emit duplicate discoveryAdvertisingStateUpdate''

2017-07-27 08:28:08 - DEBUG UnitTestFramework: '#setup ok: 'does not emit duplicate discoveryAdvertisingStateUpdate''

2017-07-27 08:28:08 - DEBUG UnitTestFramework: '#run: 'does not emit duplicate discoveryAdvertisingStateUpdate''

2017-07-27 08:28:08 - INFO Socket: 'run skipped, test: 'does not emit duplicate discoveryAdvertisingStateUpdate', event: 'run_does not emit duplicate discoveryAdvertisingStateUpdate''

2017-07-27 08:28:09 - INFO Socket: 'run skipped, test: 'does not emit duplicate discoveryAdvertisingStateUpdate', event: 'run_does not emit duplicate discoveryAdvertisingStateUpdate''

2017-07-27 08:28:09 - INFO Socket: 'run skipped, test: 'does not emit duplicate discoveryAdvertisingStateUpdate', event: 'run_does not emit duplicate discoveryAdvertisingStateUpdate''

2017-07-27 08:28:09 - DEBUG UnitTestFramework: '#run ok: 'does not emit duplicate discoveryAdvertisingStateUpdate''

2017-07-27 08:28:09 - DEBUG UnitTestFramework: '#teardown: 'does not emit duplicate discoveryAdvertisingStateUpdate''

2017-07-27 08:28:11 - DEBUG UnitTestFramework: '#teardown ok: 'does not emit duplicate discoveryAdvertisingStateUpdate''

2017-07-27 08:28:12 - DEBUG UnitTestFramework: '#setup: 'does not send duplicate availability changes''

2017-07-27 08:28:14 - DEBUG UnitTestFramework: '#setup ok: 'does not send duplicate availability changes''

2017-07-27 08:28:14 - DEBUG UnitTestFramework: '#run: 'does not send duplicate availability changes''

2017-07-27 08:28:16 - DEBUG UnitTestFramework: '#run ok: 'does not send duplicate availability changes''

2017-07-27 08:28:16 - DEBUG UnitTestFramework: '#teardown: 'does not send duplicate availability changes''

2017-07-27 08:28:17 - DEBUG UnitTestFramework: '#teardown ok: 'does not send duplicate availability changes''

2017-07-27 08:28:17 - DEBUG UnitTestFramework: '#setup: 'can get the network status''

2017-07-27 08:28:18 - DEBUG UnitTestFramework: '#setup ok: 'can get the network status''

2017-07-27 08:28:18 - DEBUG UnitTestFramework: '#run: 'can get the network status''

2017-07-27 08:28:21 - DEBUG UnitTestFramework: '#run ok: 'can get the network status''

2017-07-27 08:28:21 - DEBUG UnitTestFramework: '#teardown: 'can get the network status''

2017-07-27 08:28:24 - DEBUG UnitTestFramework: '#teardown ok: 'can get the network status''

2017-07-27 08:28:24 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChanged - peer added/removed to/from cache (native)''

2017-07-27 08:28:27 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChanged - peer added/removed to/from cache (native)''

2017-07-27 08:28:27 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChanged - peer added/removed to/from cache (native)''

2017-07-27 08:28:30 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChanged - peer added/removed to/from cache (native)''

2017-07-27 08:28:30 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChanged - peer added/removed to/from cache (native)''

2017-07-27 08:28:30 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChanged - peer added/removed to/from cache (native)''

2017-07-27 08:28:30 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChanged - peer added/removed to/from cache (wifi)''

2017-07-27 08:28:30 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChanged - peer added/removed to/from cache (wifi)''

2017-07-27 08:28:30 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChanged - peer added/removed to/from cache (wifi)''

2017-07-27 08:28:30 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChanged - peer added/removed to/from cache (wifi)''

2017-07-27 08:28:30 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChanged - peer added/removed to/from cache (wifi)''

2017-07-27 08:28:30 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChanged - peer added/removed to/from cache (wifi)''

2017-07-27 08:28:30 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored''

2017-07-27 08:28:30 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored''

2017-07-27 08:28:30 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored''

2017-07-27 08:28:30 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored''

2017-07-27 08:28:30 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored''

2017-07-27 08:28:30 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored''

2017-07-27 08:28:30 - DEBUG UnitTestFramework: '#setup: 'native available - new peer is cached''

2017-07-27 08:28:30 - DEBUG UnitTestFramework: '#setup ok: 'native available - new peer is cached''

2017-07-27 08:28:30 - DEBUG UnitTestFramework: '#run: 'native available - new peer is cached''

2017-07-27 08:28:30 - DEBUG UnitTestFramework: '#run ok: 'native available - new peer is cached''

2017-07-27 08:28:30 - DEBUG UnitTestFramework: '#teardown: 'native available - new peer is cached''

2017-07-27 08:28:30 - DEBUG UnitTestFramework: '#teardown ok: 'native available - new peer is cached''

2017-07-27 08:28:30 - DEBUG UnitTestFramework: '#setup: 'native available - peer with same port and different generation is cached (BLUETOOTH)''

2017-07-27 08:28:30 - DEBUG UnitTestFramework: '#setup ok: 'native available - peer with same port and different generation is cached (BLUETOOTH)''

2017-07-27 08:28:30 - DEBUG UnitTestFramework: '#run: 'native available - peer with same port and different generation is cached (BLUETOOTH)''

2017-07-27 08:28:30 - DEBUG UnitTestFramework: '#run ok: 'native available - peer with same port and different generation is cached (BLUETOOTH)''

2017-07-27 08:28:30 - DEBUG UnitTestFramework: '#teardown: 'native available - peer with same port and different generation is cached (BLUETOOTH)''

2017-07-27 08:28:31 - DEBUG UnitTestFramework: '#teardown ok: 'native available - peer with same port and different generation is cached (BLUETOOTH)''

2017-07-27 08:28:31 - DEBUG UnitTestFramework: '#setup: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''

2017-07-27 08:28:31 - DEBUG UnitTestFramework: '#setup ok: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''

2017-07-27 08:28:31 - DEBUG UnitTestFramework: '#run: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''

2017-07-27 08:28:31 - DEBUG UnitTestFramework: '#run ok: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''

2017-07-27 08:28:31 - DEBUG UnitTestFramework: '#teardown: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''

2017-07-27 08:28:31 - DEBUG UnitTestFramework: '#teardown ok: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''

2017-07-27 08:28:31 - DEBUG UnitTestFramework: '#setup: 'native available - peer with greater generation is cached (MPCF)''

2017-07-27 08:28:31 - DEBUG UnitTestFramework: '#setup ok: 'native available - peer with greater generation is cached (MPCF)''

2017-07-27 08:28:31 - DEBUG UnitTestFramework: '#run: 'native available - peer with greater generation is cached (MPCF)''

2017-07-27 08:28:31 - INFO Socket: 'run skipped, test: 'native available - peer with greater generation is cached (MPCF)', event: 'run_native available - peer with greater generation is cached (MPCF)''

2017-07-27 08:28:31 - INFO Socket: 'run skipped, test: 'native available - peer with greater generation is cached (MPCF)', event: 'run_native available - peer with greater generation is cached (MPCF)''

2017-07-27 08:28:31 - INFO Socket: 'run skipped, test: 'native available - peer with greater generation is cached (MPCF)', event: 'run_native available - peer with greater generation is cached (MPCF)''

2017-07-27 08:28:31 - DEBUG UnitTestFramework: '#run ok: 'native available - peer with greater generation is cached (MPCF)''

2017-07-27 08:28:31 - DEBUG UnitTestFramework: '#teardown: 'native available - peer with greater generation is cached (MPCF)''

2017-07-27 08:28:31 - DEBUG UnitTestFramework: '#teardown ok: 'native available - peer with greater generation is cached (MPCF)''

2017-07-27 08:28:31 - DEBUG UnitTestFramework: '#setup: 'native available - peer with same or older generation is ignored (MPCF)''

2017-07-27 08:28:31 - DEBUG UnitTestFramework: '#setup ok: 'native available - peer with same or older generation is ignored (MPCF)''

2017-07-27 08:28:31 - DEBUG UnitTestFramework: '#run: 'native available - peer with same or older generation is ignored (MPCF)''

2017-07-27 08:28:31 - INFO Socket: 'run skipped, test: 'native available - peer with same or older generation is ignored (MPCF)', event: 'run_native available - peer with same or older generation is ignored (MPCF)''

2017-07-27 08:28:31 - INFO Socket: 'run skipped, test: 'native available - peer with same or older generation is ignored (MPCF)', event: 'run_native available - peer with same or older generation is ignored (MPCF)''

2017-07-27 08:28:31 - INFO Socket: 'run skipped, test: 'native available - peer with same or older generation is ignored (MPCF)', event: 'run_native available - peer with same or older generation is ignored (MPCF)''

2017-07-27 08:28:31 - DEBUG UnitTestFramework: '#run ok: 'native available - peer with same or older generation is ignored (MPCF)''

2017-07-27 08:28:31 - DEBUG UnitTestFramework: '#teardown: 'native available - peer with same or older generation is ignored (MPCF)''

2017-07-27 08:28:31 - DEBUG UnitTestFramework: '#teardown ok: 'native available - peer with same or older generation is ignored (MPCF)''

2017-07-27 08:28:31 - DEBUG UnitTestFramework: '#setup: 'native unavailable - new peer is ignored''

2017-07-27 08:28:31 - DEBUG UnitTestFramework: '#setup ok: 'native unavailable - new peer is ignored''

2017-07-27 08:28:31 - DEBUG UnitTestFramework: '#run: 'native unavailable - new peer is ignored''

2017-07-27 08:28:31 - DEBUG UnitTestFramework: '#run ok: 'native unavailable - new peer is ignored''

2017-07-27 08:28:31 - DEBUG UnitTestFramework: '#teardown: 'native unavailable - new peer is ignored''

2017-07-27 08:28:31 - DEBUG UnitTestFramework: '#teardown ok: 'native unavailable - new peer is ignored''

2017-07-27 08:28:31 - DEBUG UnitTestFramework: '#setup: 'native unavailable - cached peer is removed''

2017-07-27 08:28:31 - DEBUG UnitTestFramework: '#setup ok: 'native unavailable - cached peer is removed''

2017-07-27 08:28:31 - DEBUG UnitTestFramework: '#run: 'native unavailable - cached peer is removed''

2017-07-27 08:28:31 - DEBUG UnitTestFramework: '#run ok: 'native unavailable - cached peer is removed''

2017-07-27 08:28:31 - DEBUG UnitTestFramework: '#teardown: 'native unavailable - cached peer is removed''

2017-07-27 08:28:31 - DEBUG UnitTestFramework: '#teardown ok: 'native unavailable - cached peer is removed''

2017-07-27 08:28:31 - DEBUG UnitTestFramework: '#setup: 'networkChanged - fires peerAvailabilityChanged event for wifi peers''

2017-07-27 08:28:31 - DEBUG UnitTestFramework: '#setup ok: 'networkChanged - fires peerAvailabilityChanged event for wifi peers''

2017-07-27 08:28:31 - DEBUG UnitTestFramework: '#run: 'networkChanged - fires peerAvailabilityChanged event for wifi peers''

2017-07-27 08:28:31 - DEBUG UnitTestFramework: '#run ok: 'networkChanged - fires peerAvailabilityChanged event for wifi peers''

2017-07-27 08:28:31 - DEBUG UnitTestFramework: '#teardown: 'networkChanged - fires peerAvailabilityChanged event for wifi peers''

2017-07-27 08:28:31 - DEBUG UnitTestFramework: '#teardown ok: 'networkChanged - fires peerAvailabilityChanged event for wifi peers''

2017-07-27 08:28:31 - DEBUG UnitTestFramework: '#setup: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#setup ok: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#run: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#run ok: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#teardown: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#teardown ok: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#setup: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#setup ok: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#run: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''

2017-07-27 08:28:32 - INFO Socket: 'run skipped, test: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)', event: 'run_networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''

2017-07-27 08:28:32 - INFO Socket: 'run skipped, test: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)', event: 'run_networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''

2017-07-27 08:28:32 - INFO Socket: 'run skipped, test: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)', event: 'run_networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#run ok: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#teardown: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#teardown ok: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#setup: 'multiconnect failure - new peer is ignored (MPCF)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#setup ok: 'multiconnect failure - new peer is ignored (MPCF)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#run: 'multiconnect failure - new peer is ignored (MPCF)''

2017-07-27 08:28:32 - INFO Socket: 'run skipped, test: 'multiconnect failure - new peer is ignored (MPCF)', event: 'run_multiconnect failure - new peer is ignored (MPCF)''

2017-07-27 08:28:32 - INFO Socket: 'run skipped, test: 'multiconnect failure - new peer is ignored (MPCF)', event: 'run_multiconnect failure - new peer is ignored (MPCF)''

2017-07-27 08:28:32 - INFO Socket: 'run skipped, test: 'multiconnect failure - new peer is ignored (MPCF)', event: 'run_multiconnect failure - new peer is ignored (MPCF)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#run ok: 'multiconnect failure - new peer is ignored (MPCF)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#teardown: 'multiconnect failure - new peer is ignored (MPCF)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#teardown ok: 'multiconnect failure - new peer is ignored (MPCF)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#setup: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#setup ok: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#run: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-07-27 08:28:32 - INFO Socket: 'run skipped, test: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)', event: 'run_multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-07-27 08:28:32 - INFO Socket: 'run skipped, test: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)', event: 'run_multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-07-27 08:28:32 - INFO Socket: 'run skipped, test: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)', event: 'run_multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#run ok: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#teardown: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#teardown ok: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#setup: 'newAddressPort field (TCP_NATIVE)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#setup ok: 'newAddressPort field (TCP_NATIVE)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#run: 'newAddressPort field (TCP_NATIVE)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#run ok: 'newAddressPort field (TCP_NATIVE)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#teardown: 'newAddressPort field (TCP_NATIVE)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#teardown ok: 'newAddressPort field (TCP_NATIVE)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#setup: 'newAddressPort field (BLUETOOTH)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#setup ok: 'newAddressPort field (BLUETOOTH)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#run: 'newAddressPort field (BLUETOOTH)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#run ok: 'newAddressPort field (BLUETOOTH)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#teardown: 'newAddressPort field (BLUETOOTH)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#teardown ok: 'newAddressPort field (BLUETOOTH)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#setup: 'newAddressPort field (MPCF)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#setup ok: 'newAddressPort field (MPCF)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#run: 'newAddressPort field (MPCF)''

2017-07-27 08:28:32 - INFO Socket: 'run skipped, test: 'newAddressPort field (MPCF)', event: 'run_newAddressPort field (MPCF)''

2017-07-27 08:28:32 - INFO Socket: 'run skipped, test: 'newAddressPort field (MPCF)', event: 'run_newAddressPort field (MPCF)''

2017-07-27 08:28:32 - INFO Socket: 'run skipped, test: 'newAddressPort field (MPCF)', event: 'run_newAddressPort field (MPCF)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#run ok: 'newAddressPort field (MPCF)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#teardown: 'newAddressPort field (MPCF)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#teardown ok: 'newAddressPort field (MPCF)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#setup: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#setup ok: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#run: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#run ok: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#teardown: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#teardown ok: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#setup: '#getPeerHostInfo - error when peer has not been discovered yet''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#setup ok: '#getPeerHostInfo - error when peer has not been discovered yet''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#run: '#getPeerHostInfo - error when peer has not been discovered yet''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#run ok: '#getPeerHostInfo - error when peer has not been discovered yet''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#teardown: '#getPeerHostInfo - error when peer has not been discovered yet''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#teardown ok: '#getPeerHostInfo - error when peer has not been discovered yet''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#setup: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#setup ok: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#run: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#run ok: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''

2017-07-27 08:28:32 - DEBUG UnitTestFramework: '#teardown: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#teardown ok: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#setup: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#setup ok: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#run: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''

2017-07-27 08:28:33 - INFO Socket: 'run skipped, test: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)', event: 'run_#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''

2017-07-27 08:28:33 - INFO Socket: 'run skipped, test: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)', event: 'run_#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''

2017-07-27 08:28:33 - INFO Socket: 'run skipped, test: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)', event: 'run_#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#run ok: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#teardown: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#teardown ok: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#setup: '#getPeerHostInfo - returns discovered cached wifi peer''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#setup ok: '#getPeerHostInfo - returns discovered cached wifi peer''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#run: '#getPeerHostInfo - returns discovered cached wifi peer''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#run ok: '#getPeerHostInfo - returns discovered cached wifi peer''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#teardown: '#getPeerHostInfo - returns discovered cached wifi peer''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#teardown ok: '#getPeerHostInfo - returns discovered cached wifi peer''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#setup: '#disconnect fails on wifi peers''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#setup ok: '#disconnect fails on wifi peers''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#run: '#disconnect fails on wifi peers''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#run ok: '#disconnect fails on wifi peers''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#teardown: '#disconnect fails on wifi peers''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#teardown ok: '#disconnect fails on wifi peers''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#setup: '#disconnect delegates native peers to the native wrapper''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#setup ok: '#disconnect delegates native peers to the native wrapper''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#run: '#disconnect delegates native peers to the native wrapper''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#run ok: '#disconnect delegates native peers to the native wrapper''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#teardown: '#disconnect delegates native peers to the native wrapper''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#teardown ok: '#disconnect delegates native peers to the native wrapper''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#setup: 'network changes emitted correctly''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#setup ok: 'network changes emitted correctly''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#run: 'network changes emitted correctly''

2017-07-27 08:28:33 - INFO Socket: 'run skipped, test: 'network changes emitted correctly', event: 'run_network changes emitted correctly''

2017-07-27 08:28:33 - INFO Socket: 'run skipped, test: 'network changes emitted correctly', event: 'run_network changes emitted correctly''

2017-07-27 08:28:33 - INFO Socket: 'run skipped, test: 'network changes emitted correctly', event: 'run_network changes emitted correctly''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#run ok: 'network changes emitted correctly''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#teardown: 'network changes emitted correctly''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#teardown ok: 'network changes emitted correctly''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#setup: 'network changes not emitted in started state''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#setup ok: 'network changes not emitted in started state''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#run: 'network changes not emitted in started state''

2017-07-27 08:28:33 - INFO Socket: 'run skipped, test: 'network changes not emitted in started state', event: 'run_network changes not emitted in started state''

2017-07-27 08:28:33 - INFO Socket: 'run skipped, test: 'network changes not emitted in started state', event: 'run_network changes not emitted in started state''

2017-07-27 08:28:33 - INFO Socket: 'run skipped, test: 'network changes not emitted in started state', event: 'run_network changes not emitted in started state''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#run ok: 'network changes not emitted in started state''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#teardown: 'network changes not emitted in started state''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#teardown ok: 'network changes not emitted in started state''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#setup: 'network changes not emitted in stopped state''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#setup ok: 'network changes not emitted in stopped state''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#run: 'network changes not emitted in stopped state''

2017-07-27 08:28:33 - INFO Socket: 'run skipped, test: 'network changes not emitted in stopped state', event: 'run_network changes not emitted in stopped state''

2017-07-27 08:28:33 - INFO Socket: 'run skipped, test: 'network changes not emitted in stopped state', event: 'run_network changes not emitted in stopped state''

2017-07-27 08:28:33 - INFO Socket: 'run skipped, test: 'network changes not emitted in stopped state', event: 'run_network changes not emitted in stopped state''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#run ok: 'network changes not emitted in stopped state''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#teardown: 'network changes not emitted in stopped state''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#teardown ok: 'network changes not emitted in stopped state''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#setup: 'We properly fire peer unavailable and then available when connection fails on Android''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#setup ok: 'We properly fire peer unavailable and then available when connection fails on Android''

2017-07-27 08:28:33 - DEBUG UnitTestFramework: '#run: 'We properly fire peer unavailable and then available when connection fails on Android''

2017-07-27 08:28:34 - DEBUG UnitTestFramework: '#run ok: 'We properly fire peer unavailable and then available when connection fails on Android''

2017-07-27 08:28:34 - DEBUG UnitTestFramework: '#teardown: 'We properly fire peer unavailable and then available when connection fails on Android''

2017-07-27 08:28:35 - DEBUG UnitTestFramework: '#teardown ok: 'We properly fire peer unavailable and then available when connection fails on Android''

2017-07-27 08:28:35 - DEBUG UnitTestFramework: '#setup: 'We properly fire peer unavailable and then available when connection fails on iOS''

2017-07-27 08:28:35 - DEBUG UnitTestFramework: '#setup ok: 'We properly fire peer unavailable and then available when connection fails on iOS''

2017-07-27 08:28:35 - DEBUG UnitTestFramework: '#run: 'We properly fire peer unavailable and then available when connection fails on iOS''

2017-07-27 08:28:35 - INFO Socket: 'run skipped, test: 'We properly fire peer unavailable and then available when connection fails on iOS', event: 'run_We properly fire peer unavailable and then available when connection fails on iOS''

2017-07-27 08:28:35 - INFO Socket: 'run skipped, test: 'We properly fire peer unavailable and then available when connection fails on iOS', event: 'run_We properly fire peer unavailable and then available when connection fails on iOS''

2017-07-27 08:28:35 - INFO Socket: 'run skipped, test: 'We properly fire peer unavailable and then available when connection fails on iOS', event: 'run_We properly fire peer unavailable and then available when connection fails on iOS''

2017-07-27 08:28:35 - DEBUG UnitTestFramework: '#run ok: 'We properly fire peer unavailable and then available when connection fails on iOS''

2017-07-27 08:28:35 - DEBUG UnitTestFramework: '#teardown: 'We properly fire peer unavailable and then available when connection fails on iOS''

2017-07-27 08:28:35 - DEBUG UnitTestFramework: '#teardown ok: 'We properly fire peer unavailable and then available when connection fails on iOS''

2017-07-27 08:28:35 - DEBUG UnitTestFramework: '#setup: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''

2017-07-27 08:28:35 - DEBUG UnitTestFramework: '#setup ok: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''

2017-07-27 08:28:35 - DEBUG UnitTestFramework: '#run: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''

2017-07-27 08:28:36 - DEBUG UnitTestFramework: '#run ok: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''

2017-07-27 08:28:36 - DEBUG UnitTestFramework: '#teardown: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''

2017-07-27 08:28:37 - DEBUG UnitTestFramework: '#teardown ok: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''

2017-07-27 08:28:37 - DEBUG UnitTestFramework: '#setup: 'does not fire duplicate events after peer listener recreation''

2017-07-27 08:28:37 - DEBUG UnitTestFramework: '#setup ok: 'does not fire duplicate events after peer listener recreation''

2017-07-27 08:28:37 - DEBUG UnitTestFramework: '#run: 'does not fire duplicate events after peer listener recreation''

2017-07-27 08:28:37 - DEBUG UnitTestFramework: '#run ok: 'does not fire duplicate events after peer listener recreation''

2017-07-27 08:28:37 - DEBUG UnitTestFramework: '#teardown: 'does not fire duplicate events after peer listener recreation''

2017-07-27 08:28:37 - DEBUG UnitTestFramework: '#teardown ok: 'does not fire duplicate events after peer listener recreation''

2017-07-27 08:28:37 - DEBUG UnitTestFramework: '#setup: '#stop should change peers''

2017-07-27 08:28:37 - DEBUG UnitTestFramework: '#setup ok: '#stop should change peers''

2017-07-27 08:28:37 - DEBUG UnitTestFramework: '#run: '#stop should change peers''

2017-07-27 08:28:41 - DEBUG UnitTestFramework: '#run ok: '#stop should change peers''

2017-07-27 08:28:41 - DEBUG UnitTestFramework: '#teardown: '#stop should change peers''

2017-07-27 08:28:44 - DEBUG UnitTestFramework: '#teardown ok: '#stop should change peers''

2017-07-27 08:28:44 - DEBUG UnitTestFramework: '#setup: 'If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted''

2017-07-27 08:28:47 - DEBUG UnitTestFramework: '#setup ok: 'If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted''

2017-07-27 08:28:47 - DEBUG UnitTestFramework: '#run: 'If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted''

2017-07-27 08:28:47 - DEBUG UnitTestFramework: '#run ok: 'If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted''

2017-07-27 08:28:47 - DEBUG UnitTestFramework: '#teardown: 'If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted''

2017-07-27 08:28:50 - DEBUG UnitTestFramework: '#teardown ok: 'If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted''

2017-07-27 08:28:50 - DEBUG UnitTestFramework: '#setup: 'peer should be found once after listening and discovery started''

2017-07-27 08:28:52 - DEBUG UnitTestFramework: '#setup ok: 'peer should be found once after listening and discovery started''

2017-07-27 08:28:52 - DEBUG UnitTestFramework: '#run: 'peer should be found once after listening and discovery started''

2017-07-27 08:28:52 - INFO Socket: 'run skipped, test: 'peer should be found once after listening and discovery started', event: 'run_peer should be found once after listening and discovery started''

2017-07-27 08:28:53 - INFO Socket: 'run skipped, test: 'peer should be found once after listening and discovery started', event: 'run_peer should be found once after listening and discovery started''

2017-07-27 08:28:54 - INFO Socket: 'run skipped, test: 'peer should be found once after listening and discovery started', event: 'run_peer should be found once after listening and discovery started''

2017-07-27 08:28:54 - DEBUG UnitTestFramework: '#run ok: 'peer should be found once after listening and discovery started''

2017-07-27 08:28:54 - DEBUG UnitTestFramework: '#teardown: 'peer should be found once after listening and discovery started''

2017-07-27 08:28:56 - DEBUG UnitTestFramework: '#teardown ok: 'peer should be found once after listening and discovery started''

2017-07-27 08:28:56 - DEBUG UnitTestFramework: '#setup: 'can get data from all participants''

2017-07-27 08:28:58 - DEBUG UnitTestFramework: '#setup ok: 'can get data from all participants''

2017-07-27 08:28:58 - DEBUG UnitTestFramework: '#run: 'can get data from all participants''

2017-07-27 08:29:19 - DEBUG UnitTestFramework: '#run ok: 'can get data from all participants''

2017-07-27 08:29:19 - DEBUG UnitTestFramework: '#teardown: 'can get data from all participants''

2017-07-27 08:29:23 - DEBUG UnitTestFramework: '#teardown ok: 'can get data from all participants''

2017-07-27 08:29:23 - DEBUG UnitTestFramework: '#setup: 'test for data corruption''

2017-07-27 08:29:25 - DEBUG UnitTestFramework: '#setup ok: 'test for data corruption''

2017-07-27 08:29:25 - DEBUG UnitTestFramework: '#run: 'test for data corruption''

2017-07-27 08:29:25 - INFO Socket: 'run skipped, test: 'test for data corruption', event: 'run_test for data corruption''

2017-07-27 08:29:25 - INFO Socket: 'run skipped, test: 'test for data corruption', event: 'run_test for data corruption''

2017-07-27 08:29:25 - INFO Socket: 'run skipped, test: 'test for data corruption', event: 'run_test for data corruption''

2017-07-27 08:29:25 - DEBUG UnitTestFramework: '#run ok: 'test for data corruption''

2017-07-27 08:29:25 - DEBUG UnitTestFramework: '#teardown: 'test for data corruption''

2017-07-27 08:29:25 - DEBUG UnitTestFramework: '#teardown ok: 'test for data corruption''

2017-07-27 08:29:25 - DEBUG UnitTestFramework: '#setup: '#testThaliPeerAction - test getters''

2017-07-27 08:29:25 - DEBUG UnitTestFramework: '#setup ok: '#testThaliPeerAction - test getters''

2017-07-27 08:29:25 - DEBUG UnitTestFramework: '#run: '#testThaliPeerAction - test getters''

2017-07-27 08:29:25 - DEBUG UnitTestFramework: '#run ok: '#testThaliPeerAction - test getters''

2017-07-27 08:29:25 - DEBUG UnitTestFramework: '#teardown: '#testThaliPeerAction - test getters''

2017-07-27 08:29:25 - DEBUG UnitTestFramework: '#teardown ok: '#testThaliPeerAction - test getters''

2017-07-27 08:29:25 - DEBUG UnitTestFramework: '#setup: '#testThaliPeerAction - start and kill''

2017-07-27 08:29:25 - DEBUG UnitTestFramework: '#setup ok: '#testThaliPeerAction - start and kill''

2017-07-27 08:29:25 - DEBUG UnitTestFramework: '#run: '#testThaliPeerAction - start and kill''

2017-07-27 08:29:25 - DEBUG UnitTestFramework: '#run ok: '#testThaliPeerAction - start and kill''

2017-07-27 08:29:25 - DEBUG UnitTestFramework: '#teardown: '#testThaliPeerAction - start and kill''

2017-07-27 08:29:25 - DEBUG UnitTestFramework: '#teardown ok: '#testThaliPeerAction - start and kill''

2017-07-27 08:29:25 - DEBUG UnitTestFramework: '#setup: '#testThaliPeerAction - double start''

2017-07-27 08:29:25 - DEBUG UnitTestFramework: '#setup ok: '#testThaliPeerAction - double start''

2017-07-27 08:29:25 - DEBUG UnitTestFramework: '#run: '#testThaliPeerAction - double start''

2017-07-27 08:29:25 - DEBUG UnitTestFramework: '#run ok: '#testThaliPeerAction - double start''

2017-07-27 08:29:25 - DEBUG UnitTestFramework: '#teardown: '#testThaliPeerAction - double start''

2017-07-27 08:29:26 - DEBUG UnitTestFramework: '#teardown ok: '#testThaliPeerAction - double start''

2017-07-27 08:29:26 - DEBUG UnitTestFramework: '#setup: '#testThaliPeerAction - start after kill''

2017-07-27 08:29:26 - DEBUG UnitTestFramework: '#setup ok: '#testThaliPeerAction - start after kill''

2017-07-27 08:29:26 - DEBUG UnitTestFramework: '#run: '#testThaliPeerAction - start after kill''

2017-07-27 08:29:26 - DEBUG UnitTestFramework: '#run ok: '#testThaliPeerAction - start after kill''

2017-07-27 08:29:26 - DEBUG UnitTestFramework: '#teardown: '#testThaliPeerAction - start after kill''

2017-07-27 08:29:26 - DEBUG UnitTestFramework: '#teardown ok: '#testThaliPeerAction - start after kill''

2017-07-27 08:29:26 - DEBUG UnitTestFramework: '#setup: '#testThaliPeerAction - make sure ids are unique''

2017-07-27 08:29:26 - DEBUG UnitTestFramework: '#setup ok: '#testThaliPeerAction - make sure ids are unique''

2017-07-27 08:29:26 - DEBUG UnitTestFramework: '#run: '#testThaliPeerAction - make sure ids are unique''

2017-07-27 08:29:26 - DEBUG UnitTestFramework: '#run ok: '#testThaliPeerAction - make sure ids are unique''

2017-07-27 08:29:26 - DEBUG UnitTestFramework: '#teardown: '#testThaliPeerAction - make sure ids are unique''

2017-07-27 08:29:26 - DEBUG UnitTestFramework: '#teardown ok: '#testThaliPeerAction - make sure ids are unique''

2017-07-27 08:29:26 - DEBUG UnitTestFramework: '#setup: '#testThaliPeerAction - check that forever agent can be destroyed''

2017-07-27 08:29:26 - DEBUG UnitTestFramework: '#setup ok: '#testThaliPeerAction - check that forever agent can be destroyed''

2017-07-27 08:29:26 - DEBUG UnitTestFramework: '#run: '#testThaliPeerAction - check that forever agent can be destroyed''

2017-07-27 08:29:26 - DEBUG UnitTestFramework: '#run ok: '#testThaliPeerAction - check that forever agent can be destroyed''

2017-07-27 08:29:26 - DEBUG UnitTestFramework: '#teardown: '#testThaliPeerAction - check that forever agent can be destroyed''

2017-07-27 08:29:26 - DEBUG UnitTestFramework: '#teardown ok: '#testThaliPeerAction - check that forever agent can be destroyed''

2017-07-27 08:29:26 - DEBUG UnitTestFramework: '#setup: 'Test PeerDictionary basic functionality''

2017-07-27 08:29:26 - DEBUG UnitTestFramework: '#setup ok: 'Test PeerDictionary basic functionality''

2017-07-27 08:29:26 - DEBUG UnitTestFramework: '#run: 'Test PeerDictionary basic functionality''

2017-07-27 08:29:26 - DEBUG UnitTestFramework: '#run ok: 'Test PeerDictionary basic functionality''

2017-07-27 08:29:26 - DEBUG UnitTestFramework: '#teardown: 'Test PeerDictionary basic functionality''

2017-07-27 08:29:26 - DEBUG UnitTestFramework: '#teardown ok: 'Test PeerDictionary basic functionality''

2017-07-27 08:29:26 - DEBUG UnitTestFramework: '#setup: 'Test PeerDictionary with multiple entries.''

2017-07-27 08:29:26 - DEBUG UnitTestFramework: '#setup ok: 'Test PeerDictionary with multiple entries.''

2017-07-27 08:29:26 - DEBUG UnitTestFramework: '#run: 'Test PeerDictionary with multiple entries.''

2017-07-27 08:29:27 - DEBUG UnitTestFramework: '#run ok: 'Test PeerDictionary with multiple entries.''

2017-07-27 08:29:27 - DEBUG UnitTestFramework: '#teardown: 'Test PeerDictionary with multiple entries.''

2017-07-27 08:29:27 - DEBUG UnitTestFramework: '#teardown ok: 'Test PeerDictionary with multiple entries.''

2017-07-27 08:29:27 - DEBUG UnitTestFramework: '#setup: 'RESOLVED entries are removed before WAITING state entry.''

2017-07-27 08:29:27 - DEBUG UnitTestFramework: '#setup ok: 'RESOLVED entries are removed before WAITING state entry.''

2017-07-27 08:29:27 - DEBUG UnitTestFramework: '#run: 'RESOLVED entries are removed before WAITING state entry.''

2017-07-27 08:29:28 - DEBUG UnitTestFramework: '#run ok: 'RESOLVED entries are removed before WAITING state entry.''

2017-07-27 08:29:28 - DEBUG UnitTestFramework: '#teardown: 'RESOLVED entries are removed before WAITING state entry.''

2017-07-27 08:29:28 - DEBUG UnitTestFramework: '#teardown ok: 'RESOLVED entries are removed before WAITING state entry.''

2017-07-27 08:29:28 - DEBUG UnitTestFramework: '#setup: 'WAITING entries are removed before CONTROLLED_BY_POOL state entry.''

2017-07-27 08:29:28 - DEBUG UnitTestFramework: '#setup ok: 'WAITING entries are removed before CONTROLLED_BY_POOL state entry.''

2017-07-27 08:29:28 - DEBUG UnitTestFramework: '#run: 'WAITING entries are removed before CONTROLLED_BY_POOL state entry.''

2017-07-27 08:29:28 - DEBUG UnitTestFramework: '#run ok: 'WAITING entries are removed before CONTROLLED_BY_POOL state entry.''

2017-07-27 08:29:28 - DEBUG UnitTestFramework: '#teardown: 'WAITING entries are removed before CONTROLLED_BY_POOL state entry.''

2017-07-27 08:29:28 - DEBUG UnitTestFramework: '#teardown ok: 'WAITING entries are removed before CONTROLLED_BY_POOL state entry.''

2017-07-27 08:29:28 - DEBUG UnitTestFramework: '#setup: 'When CONTROLLED_BY_POOL entry is removed and kill is called.''

2017-07-27 08:29:29 - DEBUG UnitTestFramework: '#setup ok: 'When CONTROLLED_BY_POOL entry is removed and kill is called.''

2017-07-27 08:29:29 - DEBUG UnitTestFramework: '#run: 'When CONTROLLED_BY_POOL entry is removed and kill is called.''

2017-07-27 08:29:29 - DEBUG UnitTestFramework: '#run ok: 'When CONTROLLED_BY_POOL entry is removed and kill is called.''

2017-07-27 08:29:29 - DEBUG UnitTestFramework: '#teardown: 'When CONTROLLED_BY_POOL entry is removed and kill is called.''

2017-07-27 08:29:29 - DEBUG UnitTestFramework: '#teardown ok: 'When CONTROLLED_BY_POOL entry is removed and kill is called.''

2017-07-27 08:29:29 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolDefault - single action''

2017-07-27 08:29:29 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolDefault - single action''

2017-07-27 08:29:29 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolDefault - single action''

2017-07-27 08:29:29 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolDefault - single action''

2017-07-27 08:29:29 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolDefault - single action''

2017-07-27 08:29:29 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolDefault - single action''

2017-07-27 08:29:29 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolDefault - multiple actions''

2017-07-27 08:29:29 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolDefault - multiple actions''

2017-07-27 08:29:29 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolDefault - multiple actions''

2017-07-27 08:29:29 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolDefault - multiple actions''

2017-07-27 08:29:29 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolDefault - multiple actions''

2017-07-27 08:29:29 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolDefault - multiple actions''

2017-07-27 08:29:29 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolDefault - PSK Pool works''

2017-07-27 08:29:29 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolDefault - PSK Pool works''

2017-07-27 08:29:29 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolDefault - PSK Pool works''

2017-07-27 08:29:30 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolDefault - PSK Pool works''

2017-07-27 08:29:30 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolDefault - PSK Pool works''

2017-07-27 08:29:30 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolDefault - PSK Pool works''

2017-07-27 08:29:30 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolDefault - stop''

2017-07-27 08:29:30 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolDefault - stop''

2017-07-27 08:29:30 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolDefault - stop''

2017-07-27 08:29:30 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolDefault - stop''

2017-07-27 08:29:30 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolDefault - stop''

2017-07-27 08:29:30 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolDefault - stop''

2017-07-27 08:29:30 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolInterface - make sure that start verifies queue length''

2017-07-27 08:29:30 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolInterface - make sure that start verifies queue length''

2017-07-27 08:29:30 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolInterface - make sure that start verifies queue length''

2017-07-27 08:29:30 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolInterface - make sure that start verifies queue length''

2017-07-27 08:29:30 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolInterface - make sure that start verifies queue length''

2017-07-27 08:29:30 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolInterface - make sure that start verifies queue length''

2017-07-27 08:29:30 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolInterface - bad enqueues''

2017-07-27 08:29:33 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolInterface - bad enqueues''

2017-07-27 08:29:33 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolInterface - bad enqueues''

2017-07-27 08:29:36 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolInterface - bad enqueues''

2017-07-27 08:29:36 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolInterface - bad enqueues''

2017-07-27 08:29:39 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolInterface - bad enqueues''

2017-07-27 08:29:39 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolInterface - do not allow same object type''

2017-07-27 08:29:41 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolInterface - do not allow same object type''

2017-07-27 08:29:41 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolInterface - do not allow same object type''

2017-07-27 08:29:42 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolInterface - do not allow same object type''

2017-07-27 08:29:42 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolInterface - do not allow same object type''

2017-07-27 08:29:44 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolInterface - do not allow same object type''

2017-07-27 08:29:44 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolInterface - make sure we catch kill and dequeue''

2017-07-27 08:29:45 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolInterface - make sure we catch kill and dequeue''

2017-07-27 08:29:45 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolInterface - make sure we catch kill and dequeue''

2017-07-27 08:29:47 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolInterface - make sure we catch kill and dequeue''

2017-07-27 08:29:47 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolInterface - make sure we catch kill and dequeue''

2017-07-27 08:29:48 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolInterface - make sure we catch kill and dequeue''

2017-07-27 08:29:48 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent''

2017-07-27 08:29:50 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent''

2017-07-27 08:29:50 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent''

2017-07-27 08:29:53 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent''

2017-07-27 08:29:53 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent''

2017-07-27 08:29:55 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent''

2017-07-27 08:29:55 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolInterface - make sure that stop removes all actions''

2017-07-27 08:29:56 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolInterface - make sure that stop removes all actions''

2017-07-27 08:29:56 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolInterface - make sure that stop removes all actions''

2017-07-27 08:29:58 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolInterface - make sure that stop removes all actions''

2017-07-27 08:29:58 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolInterface - make sure that stop removes all actions''

2017-07-27 08:29:58 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolInterface - make sure that stop removes all actions''

2017-07-27 08:29:58 - DEBUG UnitTestFramework: '#setup: 'We reject unrecognized connection type''

2017-07-27 08:29:58 - DEBUG UnitTestFramework: '#setup ok: 'We reject unrecognized connection type''

2017-07-27 08:29:58 - DEBUG UnitTestFramework: '#run: 'We reject unrecognized connection type''

2017-07-27 08:30:01 - DEBUG UnitTestFramework: '#run ok: 'We reject unrecognized connection type''

2017-07-27 08:30:01 - DEBUG UnitTestFramework: '#teardown: 'We reject unrecognized connection type''

2017-07-27 08:30:02 - DEBUG UnitTestFramework: '#teardown ok: 'We reject unrecognized connection type''

2017-07-27 08:30:02 - DEBUG UnitTestFramework: '#setup: 'We reject unrecognized action type''

2017-07-27 08:30:04 - DEBUG UnitTestFramework: '#setup ok: 'We reject unrecognized action type''

2017-07-27 08:30:04 - DEBUG UnitTestFramework: '#run: 'We reject unrecognized action type''

2017-07-27 08:30:05 - DEBUG UnitTestFramework: '#run ok: 'We reject unrecognized action type''

2017-07-27 08:30:05 - DEBUG UnitTestFramework: '#teardown: 'We reject unrecognized action type''

2017-07-27 08:30:08 - DEBUG UnitTestFramework: '#teardown ok: 'We reject unrecognized action type''

2017-07-27 08:30:08 - DEBUG UnitTestFramework: '#setup: 'One action on bluetooth''

2017-07-27 08:30:11 - DEBUG UnitTestFramework: '#setup ok: 'One action on bluetooth''

2017-07-27 08:30:11 - DEBUG UnitTestFramework: '#run: 'One action on bluetooth''

2017-07-27 08:30:14 - DEBUG UnitTestFramework: '#run ok: 'One action on bluetooth''

2017-07-27 08:30:14 - DEBUG UnitTestFramework: '#teardown: 'One action on bluetooth''

2017-07-27 08:30:17 - DEBUG UnitTestFramework: '#teardown ok: 'One action on bluetooth''

2017-07-27 08:30:17 - DEBUG UnitTestFramework: '#setup: 'Two notification actions''

2017-07-27 08:30:20 - DEBUG UnitTestFramework: '#setup ok: 'Two notification actions''

2017-07-27 08:30:20 - DEBUG UnitTestFramework: '#run: 'Two notification actions''

2017-07-27 08:30:22 - DEBUG UnitTestFramework: '#run ok: 'Two notification actions''

2017-07-27 08:30:22 - DEBUG UnitTestFramework: '#teardown: 'Two notification actions''

2017-07-27 08:30:25 - DEBUG UnitTestFramework: '#teardown ok: 'Two notification actions''

2017-07-27 08:30:25 - DEBUG UnitTestFramework: '#setup: 'replicateThroughProblems''

2017-07-27 08:30:26 - DEBUG UnitTestFramework: '#setup ok: 'replicateThroughProblems''

2017-07-27 08:30:26 - DEBUG UnitTestFramework: '#run: 'replicateThroughProblems''

2017-07-27 08:30:28 - DEBUG UnitTestFramework: '#run ok: 'replicateThroughProblems''

2017-07-27 08:30:28 - DEBUG UnitTestFramework: '#teardown: 'replicateThroughProblems''

2017-07-27 08:30:29 - DEBUG UnitTestFramework: '#teardown ok: 'replicateThroughProblems''

2017-07-27 08:30:29 - DEBUG UnitTestFramework: '#setup: 'Replication goes first''

2017-07-27 08:30:31 - DEBUG UnitTestFramework: '#setup ok: 'Replication goes first''

2017-07-27 08:30:31 - DEBUG UnitTestFramework: '#run: 'Replication goes first''

2017-07-27 08:30:33 - DEBUG UnitTestFramework: '#run ok: 'Replication goes first''

2017-07-27 08:30:33 - DEBUG UnitTestFramework: '#teardown: 'Replication goes first''

2017-07-27 08:30:34 - DEBUG UnitTestFramework: '#teardown ok: 'Replication goes first''

2017-07-27 08:30:34 - DEBUG UnitTestFramework: '#setup: 'wifi allows many parallel non-replication actions''

2017-07-27 08:30:37 - DEBUG UnitTestFramework: '#setup ok: 'wifi allows many parallel non-replication actions''

2017-07-27 08:30:37 - DEBUG UnitTestFramework: '#run: 'wifi allows many parallel non-replication actions''

2017-07-27 08:30:39 - DEBUG UnitTestFramework: '#run ok: 'wifi allows many parallel non-replication actions''

2017-07-27 08:30:39 - DEBUG UnitTestFramework: '#teardown: 'wifi allows many parallel non-replication actions''

2017-07-27 08:30:40 - DEBUG UnitTestFramework: '#teardown ok: 'wifi allows many parallel non-replication actions''

2017-07-27 08:30:40 - DEBUG UnitTestFramework: '#setup: 'wifi allows no more than 2 simultaneous replication actions for same peerID''

2017-07-27 08:30:42 - DEBUG UnitTestFramework: '#setup ok: 'wifi allows no more than 2 simultaneous replication actions for same peerID''

2017-07-27 08:30:42 - DEBUG UnitTestFramework: '#run: 'wifi allows no more than 2 simultaneous replication actions for same peerID''

2017-07-27 08:30:45 - DEBUG UnitTestFramework: '#run ok: 'wifi allows no more than 2 simultaneous replication actions for same peerID''

2017-07-27 08:30:45 - DEBUG UnitTestFramework: '#teardown: 'wifi allows no more than 2 simultaneous replication actions for same peerID''

2017-07-27 08:30:46 - DEBUG UnitTestFramework: '#teardown ok: 'wifi allows no more than 2 simultaneous replication actions for same peerID''

2017-07-27 08:30:46 - DEBUG UnitTestFramework: '#setup: 'Client to server request coordinated''

2017-07-27 08:30:51 - DEBUG UnitTestFramework: '#setup ok: 'Client to server request coordinated''

2017-07-27 08:30:51 - DEBUG UnitTestFramework: '#run: 'Client to server request coordinated''

2017-07-27 08:30:51 - INFO Socket: 'run skipped, test: 'Client to server request coordinated', event: 'run_Client to server request coordinated''

2017-07-27 08:30:52 - INFO Socket: 'run skipped, test: 'Client to server request coordinated', event: 'run_Client to server request coordinated''

2017-07-27 08:30:55 - INFO Socket: 'run skipped, test: 'Client to server request coordinated', event: 'run_Client to server request coordinated''

2017-07-27 08:30:55 - DEBUG UnitTestFramework: '#run ok: 'Client to server request coordinated''

2017-07-27 08:30:55 - DEBUG UnitTestFramework: '#teardown: 'Client to server request coordinated''

2017-07-27 08:30:57 - DEBUG UnitTestFramework: '#teardown ok: 'Client to server request coordinated''

2017-07-27 08:30:57 - DEBUG UnitTestFramework: '#setup: 'Test BEACONS_RETRIEVED_AND_PARSED locally''

2017-07-27 08:30:58 - DEBUG UnitTestFramework: '#setup ok: 'Test BEACONS_RETRIEVED_AND_PARSED locally''

2017-07-27 08:30:58 - DEBUG UnitTestFramework: '#run: 'Test BEACONS_RETRIEVED_AND_PARSED locally''

2017-07-27 08:31:01 - DEBUG UnitTestFramework: '#run ok: 'Test BEACONS_RETRIEVED_AND_PARSED locally''

2017-07-27 08:31:01 - DEBUG UnitTestFramework: '#teardown: 'Test BEACONS_RETRIEVED_AND_PARSED locally''

2017-07-27 08:31:04 - DEBUG UnitTestFramework: '#teardown ok: 'Test BEACONS_RETRIEVED_AND_PARSED locally''

2017-07-27 08:31:04 - DEBUG UnitTestFramework: '#setup: 'Test HTTP_BAD_RESPONSE locally''

2017-07-27 08:31:07 - DEBUG UnitTestFramework: '#setup ok: 'Test HTTP_BAD_RESPONSE locally''

2017-07-27 08:31:07 - DEBUG UnitTestFramework: '#run: 'Test HTTP_BAD_RESPONSE locally''

2017-07-27 08:31:07 - INFO Socket: 'run skipped, test: 'Test HTTP_BAD_RESPONSE locally', event: 'run_Test HTTP_BAD_RESPONSE locally''

2017-07-27 08:31:07 - INFO Socket: 'run skipped, test: 'Test HTTP_BAD_RESPONSE locally', event: 'run_Test HTTP_BAD_RESPONSE locally''

2017-07-27 08:31:08 - INFO Socket: 'run skipped, test: 'Test HTTP_BAD_RESPONSE locally', event: 'run_Test HTTP_BAD_RESPONSE locally''

2017-07-27 08:31:08 - DEBUG UnitTestFramework: '#run ok: 'Test HTTP_BAD_RESPONSE locally''

2017-07-27 08:31:08 - DEBUG UnitTestFramework: '#teardown: 'Test HTTP_BAD_RESPONSE locally''

2017-07-27 08:31:10 - DEBUG UnitTestFramework: '#teardown ok: 'Test HTTP_BAD_RESPONSE locally''

2017-07-27 08:31:10 - DEBUG UnitTestFramework: '#setup: 'Test NETWORK_PROBLEM locally''

2017-07-27 08:31:11 - DEBUG UnitTestFramework: '#setup ok: 'Test NETWORK_PROBLEM locally''

2017-07-27 08:31:11 - DEBUG UnitTestFramework: '#run: 'Test NETWORK_PROBLEM locally''

2017-07-27 08:31:13 - DEBUG UnitTestFramework: '#run ok: 'Test NETWORK_PROBLEM locally''

2017-07-27 08:31:13 - DEBUG UnitTestFramework: '#teardown: 'Test NETWORK_PROBLEM locally''

2017-07-27 08:31:14 - DEBUG UnitTestFramework: '#teardown ok: 'Test NETWORK_PROBLEM locally''

2017-07-27 08:31:14 - DEBUG UnitTestFramework: '#setup: 'Action fails when getPeerHostInfo fails''

2017-07-27 08:31:16 - DEBUG UnitTestFramework: '#setup ok: 'Action fails when getPeerHostInfo fails''

2017-07-27 08:31:16 - DEBUG UnitTestFramework: '#run: 'Action fails when getPeerHostInfo fails''

2017-07-27 08:31:17 - DEBUG UnitTestFramework: '#run ok: 'Action fails when getPeerHostInfo fails''
2017-07-27 08:31:17 - DEBUG UnitTestFramework: '#teardown: 'Action fails when getPeerHostInfo fails''

2017-07-27 08:31:21 - DEBUG UnitTestFramework: '#teardown ok: 'Action fails when getPeerHostInfo fails''

2017-07-27 08:31:21 - DEBUG UnitTestFramework: '#setup: 'Call the start two times''

2017-07-27 08:31:25 - DEBUG UnitTestFramework: '#setup ok: 'Call the start two times''

2017-07-27 08:31:25 - DEBUG UnitTestFramework: '#run: 'Call the start two times''

2017-07-27 08:31:27 - DEBUG UnitTestFramework: '#run ok: 'Call the start two times''

2017-07-27 08:31:27 - DEBUG UnitTestFramework: '#teardown: 'Call the start two times''

2017-07-27 08:31:28 - DEBUG UnitTestFramework: '#teardown ok: 'Call the start two times''

2017-07-27 08:31:28 - DEBUG UnitTestFramework: '#setup: 'Call the kill before calling the start''

2017-07-27 08:31:31 - DEBUG UnitTestFramework: '#setup ok: 'Call the kill before calling the start''

2017-07-27 08:31:31 - DEBUG UnitTestFramework: '#run: 'Call the kill before calling the start''

2017-07-27 08:31:33 - DEBUG UnitTestFramework: '#run ok: 'Call the kill before calling the start''

2017-07-27 08:31:33 - DEBUG UnitTestFramework: '#teardown: 'Call the kill before calling the start''

2017-07-27 08:31:36 - DEBUG UnitTestFramework: '#teardown ok: 'Call the kill before calling the start''

2017-07-27 08:31:36 - DEBUG UnitTestFramework: '#setup: 'Call the kill immediately after the start''

2017-07-27 08:31:37 - DEBUG UnitTestFramework: '#setup ok: 'Call the kill immediately after the start''

2017-07-27 08:31:37 - DEBUG UnitTestFramework: '#run: 'Call the kill immediately after the start''

2017-07-27 08:31:39 - DEBUG UnitTestFramework: '#run ok: 'Call the kill immediately after the start''

2017-07-27 08:31:39 - DEBUG UnitTestFramework: '#teardown: 'Call the kill immediately after the start''

2017-07-27 08:31:41 - DEBUG UnitTestFramework: '#teardown ok: 'Call the kill immediately after the start''

2017-07-27 08:31:41 - DEBUG UnitTestFramework: '#setup: 'Call the kill while waiting a response from the server''

2017-07-27 08:31:43 - DEBUG UnitTestFramework: '#setup ok: 'Call the kill while waiting a response from the server''

2017-07-27 08:31:43 - DEBUG UnitTestFramework: '#run: 'Call the kill while waiting a response from the server''

2017-07-27 08:31:47 - DEBUG UnitTestFramework: '#run ok: 'Call the kill while waiting a response from the server''

2017-07-27 08:31:47 - DEBUG UnitTestFramework: '#teardown: 'Call the kill while waiting a response from the server''

2017-07-27 08:31:49 - DEBUG UnitTestFramework: '#teardown ok: 'Call the kill while waiting a response from the server''

2017-07-27 08:31:49 - DEBUG UnitTestFramework: '#setup: 'Test to exceed the max content size locally''

2017-07-27 08:31:51 - DEBUG UnitTestFramework: '#setup ok: 'Test to exceed the max content size locally''

2017-07-27 08:31:51 - DEBUG UnitTestFramework: '#run: 'Test to exceed the max content size locally''

2017-07-27 08:31:52 - DEBUG UnitTestFramework: '#run ok: 'Test to exceed the max content size locally''

2017-07-27 08:31:52 - DEBUG UnitTestFramework: '#teardown: 'Test to exceed the max content size locally''

2017-07-27 08:31:55 - DEBUG UnitTestFramework: '#teardown ok: 'Test to exceed the max content size locally''

2017-07-27 08:31:55 - DEBUG UnitTestFramework: '#setup: 'Close the server socket while the client is waiting a response from the server. Local test.''

2017-07-27 08:31:57 - DEBUG UnitTestFramework: '#setup ok: 'Close the server socket while the client is waiting a response from the server. Local test.''

2017-07-27 08:31:57 - DEBUG UnitTestFramework: '#run: 'Close the server socket while the client is waiting a response from the server. Local test.''

2017-07-27 08:32:00 - DEBUG UnitTestFramework: '#run ok: 'Close the server socket while the client is waiting a response from the server. Local test.''

2017-07-27 08:32:00 - DEBUG UnitTestFramework: '#teardown: 'Close the server socket while the client is waiting a response from the server. Local test.''

2017-07-27 08:32:02 - DEBUG UnitTestFramework: '#teardown ok: 'Close the server socket while the client is waiting a response from the server. Local test.''

2017-07-27 08:32:02 - DEBUG UnitTestFramework: '#setup: 'Close the client socket while the client is waiting a response from the server. Local test.''

2017-07-27 08:32:03 - DEBUG UnitTestFramework: '#setup ok: 'Close the client socket while the client is waiting a response from the server. Local test.''

2017-07-27 08:32:03 - DEBUG UnitTestFramework: '#run: 'Close the client socket while the client is waiting a response from the server. Local test.''

2017-07-27 08:32:08 - DEBUG UnitTestFramework: '#run ok: 'Close the client socket while the client is waiting a response from the server. Local test.''

2017-07-27 08:32:08 - DEBUG UnitTestFramework: '#teardown: 'Close the client socket while the client is waiting a response from the server. Local test.''

2017-07-27 08:32:10 - DEBUG UnitTestFramework: '#teardown ok: 'Close the client socket while the client is waiting a response from the server. Local test.''

2017-07-27 08:32:10 - DEBUG UnitTestFramework: '#setup: '#generatePreambleAndBeacons bad args''

2017-07-27 08:32:11 - DEBUG UnitTestFramework: '#setup ok: '#generatePreambleAndBeacons bad args''

2017-07-27 08:32:11 - DEBUG UnitTestFramework: '#run: '#generatePreambleAndBeacons bad args''

2017-07-27 08:32:13 - DEBUG UnitTestFramework: '#run ok: '#generatePreambleAndBeacons bad args''

2017-07-27 08:32:13 - DEBUG UnitTestFramework: '#teardown: '#generatePreambleAndBeacons bad args''

2017-07-27 08:32:14 - DEBUG UnitTestFramework: '#teardown ok: '#generatePreambleAndBeacons bad args''

2017-07-27 08:32:14 - DEBUG UnitTestFramework: '#setup: '#generatePreambleAndBeacons empty keys to notify''

2017-07-27 08:32:16 - DEBUG UnitTestFramework: '#setup ok: '#generatePreambleAndBeacons empty keys to notify''

2017-07-27 08:32:16 - DEBUG UnitTestFramework: '#run: '#generatePreambleAndBeacons empty keys to notify''

2017-07-27 08:32:17 - DEBUG UnitTestFramework: '#run ok: '#generatePreambleAndBeacons empty keys to notify''

2017-07-27 08:32:17 - DEBUG UnitTestFramework: '#teardown: '#generatePreambleAndBeacons empty keys to notify''

2017-07-27 08:32:21 - DEBUG UnitTestFramework: '#teardown ok: '#generatePreambleAndBeacons empty keys to notify''

2017-07-27 08:32:21 - DEBUG UnitTestFramework: '#setup: '#generatePreambleAndBeacons multiple keys to notify''

2017-07-27 08:32:23 - DEBUG UnitTestFramework: '#setup ok: '#generatePreambleAndBeacons multiple keys to notify''

2017-07-27 08:32:23 - DEBUG UnitTestFramework: '#run: '#generatePreambleAndBeacons multiple keys to notify''

2017-07-27 08:32:26 - DEBUG UnitTestFramework: '#run ok: '#generatePreambleAndBeacons multiple keys to notify''

2017-07-27 08:32:26 - DEBUG UnitTestFramework: '#teardown: '#generatePreambleAndBeacons multiple keys to notify''

2017-07-27 08:32:29 - DEBUG UnitTestFramework: '#teardown ok: '#generatePreambleAndBeacons multiple keys to notify''

2017-07-27 08:32:29 - DEBUG UnitTestFramework: '#setup: '#parseBeacons invalid ECDH public key in beaconStreamWithPreAmble''

2017-07-27 08:32:31 - DEBUG UnitTestFramework: '#setup ok: '#parseBeacons invalid ECDH public key in beaconStreamWithPreAmble''

2017-07-27 08:32:31 - DEBUG UnitTestFramework: '#run: '#parseBeacons invalid ECDH public key in beaconStreamWithPreAmble''

2017-07-27 08:32:32 - DEBUG UnitTestFramework: '#run ok: '#parseBeacons invalid ECDH public key in beaconStreamWithPreAmble''

2017-07-27 08:32:32 - DEBUG UnitTestFramework: '#teardown: '#parseBeacons invalid ECDH public key in beaconStreamWithPreAmble''

2017-07-27 08:32:34 - DEBUG UnitTestFramework: '#teardown ok: '#parseBeacons invalid ECDH public key in beaconStreamWithPreAmble''

2017-07-27 08:32:34 - DEBUG UnitTestFramework: '#setup: '#parseBeacons invalid expiration in beaconStreamWithPreAmble''

2017-07-27 08:32:35 - DEBUG UnitTestFramework: '#setup ok: '#parseBeacons invalid expiration in beaconStreamWithPreAmble''

2017-07-27 08:32:35 - DEBUG UnitTestFramework: '#run: '#parseBeacons invalid expiration in beaconStreamWithPreAmble''

2017-07-27 08:32:37 - DEBUG UnitTestFramework: '#run ok: '#parseBeacons invalid expiration in beaconStreamWithPreAmble''

2017-07-27 08:32:37 - DEBUG UnitTestFramework: '#teardown: '#parseBeacons invalid expiration in beaconStreamWithPreAmble''

2017-07-27 08:32:38 - DEBUG UnitTestFramework: '#teardown ok: '#parseBeacons invalid expiration in beaconStreamWithPreAmble''

2017-07-27 08:32:38 - DEBUG UnitTestFramework: '#setup: '#parseBeacons expiration out of range lower''

2017-07-27 08:32:38 - DEBUG UnitTestFramework: '#setup ok: '#parseBeacons expiration out of range lower''

2017-07-27 08:32:38 - DEBUG UnitTestFramework: '#run: '#parseBeacons expiration out of range lower''

2017-07-27 08:32:41 - DEBUG UnitTestFramework: '#run ok: '#parseBeacons expiration out of range lower''

2017-07-27 08:32:41 - DEBUG UnitTestFramework: '#teardown: '#parseBeacons expiration out of range lower''

2017-07-27 08:32:41 - DEBUG UnitTestFramework: '#teardown ok: '#parseBeacons expiration out of range lower''

2017-07-27 08:32:41 - DEBUG UnitTestFramework: '#setup: '#parseBeacons expiration out of range lower''

2017-07-27 08:32:41 - DEBUG UnitTestFramework: '#setup ok: '#parseBeacons expiration out of range lower''

2017-07-27 08:32:41 - DEBUG UnitTestFramework: '#run: '#parseBeacons expiration out of range lower''

2017-07-27 08:32:41 - DEBUG UnitTestFramework: '#run ok: '#parseBeacons expiration out of range lower''

2017-07-27 08:32:41 - DEBUG UnitTestFramework: '#teardown: '#parseBeacons expiration out of range lower''

2017-07-27 08:32:41 - DEBUG UnitTestFramework: '#teardown ok: '#parseBeacons expiration out of range lower''

2017-07-27 08:32:41 - DEBUG UnitTestFramework: '#setup: '#parseBeacons no beacons returns null''

2017-07-27 08:32:41 - DEBUG UnitTestFramework: '#setup ok: '#parseBeacons no beacons returns null''

2017-07-27 08:32:41 - DEBUG UnitTestFramework: '#run: '#parseBeacons no beacons returns null''

2017-07-27 08:32:41 - DEBUG UnitTestFramework: '#run ok: '#parseBeacons no beacons returns null''

2017-07-27 08:32:41 - DEBUG UnitTestFramework: '#teardown: '#parseBeacons no beacons returns null''

2017-07-27 08:32:41 - DEBUG UnitTestFramework: '#teardown ok: '#parseBeacons no beacons returns null''

2017-07-27 08:32:41 - DEBUG UnitTestFramework: '#setup: '#parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble''

2017-07-27 08:32:41 - DEBUG UnitTestFramework: '#setup ok: '#parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble''

2017-07-27 08:32:41 - DEBUG UnitTestFramework: '#run: '#parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble''

2017-07-27 08:32:41 - DEBUG UnitTestFramework: '#run ok: '#parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble''

2017-07-27 08:32:41 - DEBUG UnitTestFramework: '#teardown: '#parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble''

2017-07-27 08:32:41 - DEBUG UnitTestFramework: '#teardown ok: '#parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble''

2017-07-27 08:32:41 - DEBUG UnitTestFramework: '#setup: '#parseBeacons addressBookCallback fails decrypt''

2017-07-27 08:32:41 - DEBUG UnitTestFramework: '#setup ok: '#parseBeacons addressBookCallback fails decrypt''

2017-07-27 08:32:41 - DEBUG UnitTestFramework: '#run: '#parseBeacons addressBookCallback fails decrypt''

2017-07-27 08:32:42 - DEBUG UnitTestFramework: '#run ok: '#parseBeacons addressBookCallback fails decrypt''

2017-07-27 08:32:42 - DEBUG UnitTestFramework: '#teardown: '#parseBeacons addressBookCallback fails decrypt''

2017-07-27 08:32:42 - DEBUG UnitTestFramework: '#teardown ok: '#parseBeacons addressBookCallback fails decrypt''

2017-07-27 08:32:42 - DEBUG UnitTestFramework: '#setup: '#parseBeacons addressBookCallback returns no matches''

2017-07-27 08:32:42 - DEBUG UnitTestFramework: '#setup ok: '#parseBeacons addressBookCallback returns no matches''

2017-07-27 08:32:42 - DEBUG UnitTestFramework: '#run: '#parseBeacons addressBookCallback returns no matches''

2017-07-27 08:32:42 - INFO Socket: 'run skipped, test: '#parseBeacons addressBookCallback returns no matches', event: 'run_#parseBeacons addressBookCallback returns no matches''

2017-07-27 08:32:42 - INFO Socket: 'run skipped, test: '#parseBeacons addressBookCallback returns no matches', event: 'run_#parseBeacons addressBookCallback returns no matches''

2017-07-27 08:32:42 - INFO Socket: 'run skipped, test: '#parseBeacons addressBookCallback returns no matches', event: 'run_#parseBeacons addressBookCallback returns no matches''

2017-07-27 08:32:42 - DEBUG UnitTestFramework: '#run ok: '#parseBeacons addressBookCallback returns no matches''

2017-07-27 08:32:42 - DEBUG UnitTestFramework: '#teardown: '#parseBeacons addressBookCallback returns no matches''

2017-07-27 08:32:42 - DEBUG UnitTestFramework: '#teardown ok: '#parseBeacons addressBookCallback returns no matches''

2017-07-27 08:32:42 - DEBUG UnitTestFramework: '#setup: '#parseBeacons addressBookCallback returns spurious match''

2017-07-27 08:32:42 - DEBUG UnitTestFramework: '#setup ok: '#parseBeacons addressBookCallback returns spurious match''

2017-07-27 08:32:42 - DEBUG UnitTestFramework: '#run: '#parseBeacons addressBookCallback returns spurious match''

2017-07-27 08:32:42 - DEBUG UnitTestFramework: '#run ok: '#parseBeacons addressBookCallback returns spurious match''

2017-07-27 08:32:42 - DEBUG UnitTestFramework: '#teardown: '#parseBeacons addressBookCallback returns spurious match''

2017-07-27 08:32:42 - DEBUG UnitTestFramework: '#teardown ok: '#parseBeacons addressBookCallback returns spurious match''

2017-07-27 08:32:42 - DEBUG UnitTestFramework: '#setup: '#parseBeacons addressBookCallback returns public key''

2017-07-27 08:32:42 - DEBUG UnitTestFramework: '#setup ok: '#parseBeacons addressBookCallback returns public key''

2017-07-27 08:32:42 - DEBUG UnitTestFramework: '#run: '#parseBeacons addressBookCallback returns public key''

2017-07-27 08:32:42 - DEBUG UnitTestFramework: '#run ok: '#parseBeacons addressBookCallback returns public key''

2017-07-27 08:32:42 - DEBUG UnitTestFramework: '#teardown: '#parseBeacons addressBookCallback returns public key''

2017-07-27 08:32:42 - DEBUG UnitTestFramework: '#teardown ok: '#parseBeacons addressBookCallback returns public key''

2017-07-27 08:32:42 - DEBUG UnitTestFramework: '#setup: 'validate generatePskIdentityField''

2017-07-27 08:32:42 - DEBUG UnitTestFramework: '#setup ok: 'validate generatePskIdentityField''

2017-07-27 08:32:42 - DEBUG UnitTestFramework: '#run: 'validate generatePskIdentityField''

2017-07-27 08:32:42 - DEBUG UnitTestFramework: '#run ok: 'validate generatePskIdentityField''

2017-07-27 08:32:42 - DEBUG UnitTestFramework: '#teardown: 'validate generatePskIdentityField''

2017-07-27 08:32:42 - DEBUG UnitTestFramework: '#teardown ok: 'validate generatePskIdentityField''

2017-07-27 08:32:42 - DEBUG UnitTestFramework: '#setup: 'validate generatePskSecret''

2017-07-27 08:32:42 - DEBUG UnitTestFramework: '#setup ok: 'validate generatePskSecret''

2017-07-27 08:32:42 - DEBUG UnitTestFramework: '#run: 'validate generatePskSecret''

2017-07-27 08:32:42 - DEBUG UnitTestFramework: '#run ok: 'validate generatePskSecret''

2017-07-27 08:32:42 - DEBUG UnitTestFramework: '#teardown: 'validate generatePskSecret''

2017-07-27 08:32:42 - DEBUG UnitTestFramework: '#teardown ok: 'validate generatePskSecret''

2017-07-27 08:32:42 - DEBUG UnitTestFramework: '#setup: 'validate generatePskSecrets''

2017-07-27 08:32:42 - DEBUG UnitTestFramework: '#setup ok: 'validate generatePskSecrets''

2017-07-27 08:32:42 - DEBUG UnitTestFramework: '#run: 'validate generatePskSecrets''

2017-07-27 08:32:43 - DEBUG UnitTestFramework: '#run ok: 'validate generatePskSecrets''

2017-07-27 08:32:43 - DEBUG UnitTestFramework: '#teardown: 'validate generatePskSecrets''

2017-07-27 08:32:43 - DEBUG UnitTestFramework: '#teardown ok: 'validate generatePskSecrets''

2017-07-27 08:32:43 - DEBUG UnitTestFramework: '#setup: 'validate generateBeaconStreamAndSecrets''

2017-07-27 08:32:43 - DEBUG UnitTestFramework: '#setup ok: 'validate generateBeaconStreamAndSecrets''

2017-07-27 08:32:43 - DEBUG UnitTestFramework: '#run: 'validate generateBeaconStreamAndSecrets''

2017-07-27 08:32:43 - DEBUG UnitTestFramework: '#run ok: 'validate generateBeaconStreamAndSecrets''

2017-07-27 08:32:43 - DEBUG UnitTestFramework: '#teardown: 'validate generateBeaconStreamAndSecrets''

2017-07-27 08:32:43 - DEBUG UnitTestFramework: '#teardown ok: 'validate generateBeaconStreamAndSecrets''

2017-07-27 08:32:43 - DEBUG UnitTestFramework: '#setup: 'Client to server request locally''

2017-07-27 08:32:43 - DEBUG UnitTestFramework: '#setup ok: 'Client to server request locally''

2017-07-27 08:32:43 - DEBUG UnitTestFramework: '#run: 'Client to server request locally''

2017-07-27 08:32:43 - DEBUG UnitTestFramework: '#run ok: 'Client to server request locally''

2017-07-27 08:32:43 - DEBUG UnitTestFramework: '#teardown: 'Client to server request locally''

2017-07-27 08:32:43 - DEBUG UnitTestFramework: '#teardown ok: 'Client to server request locally''

2017-07-27 08:32:43 - DEBUG UnitTestFramework: '#setup: 'Coordinated pull replication from notification test''

2017-07-27 08:32:43 - DEBUG UnitTestFramework: '#setup ok: 'Coordinated pull replication from notification test''

2017-07-27 08:32:43 - DEBUG UnitTestFramework: '#run: 'Coordinated pull replication from notification test''

2017-07-27 08:32:43 - INFO Socket: 'run skipped, test: 'Coordinated pull replication from notification test', event: 'run_Coordinated pull replication from notification test''

2017-07-27 08:32:43 - INFO Socket: 'run skipped, test: 'Coordinated pull replication from notification test', event: 'run_Coordinated pull replication from notification test''

2017-07-27 08:32:43 - INFO Socket: 'run skipped, test: 'Coordinated pull replication from notification test', event: 'run_Coordinated pull replication from notification test''

2017-07-27 08:32:43 - DEBUG UnitTestFramework: '#run ok: 'Coordinated pull replication from notification test''

2017-07-27 08:32:43 - DEBUG UnitTestFramework: '#teardown: 'Coordinated pull replication from notification test''

2017-07-27 08:32:43 - DEBUG UnitTestFramework: '#teardown ok: 'Coordinated pull replication from notification test''

2017-07-27 08:32:43 - DEBUG UnitTestFramework: '#setup: 'Server is not there''

2017-07-27 08:32:43 - DEBUG UnitTestFramework: '#setup ok: 'Server is not there''

2017-07-27 08:32:43 - DEBUG UnitTestFramework: '#run: 'Server is not there''

2017-07-27 08:32:43 - DEBUG UnitTestFramework: '#run ok: 'Server is not there''

2017-07-27 08:32:43 - DEBUG UnitTestFramework: '#teardown: 'Server is not there''

2017-07-27 08:32:43 - DEBUG UnitTestFramework: '#teardown ok: 'Server is not there''

2017-07-27 08:32:43 - DEBUG UnitTestFramework: '#setup: 'Server accepts & closes connection''

2017-07-27 08:32:43 - DEBUG UnitTestFramework: '#setup ok: 'Server accepts & closes connection''

2017-07-27 08:32:43 - DEBUG UnitTestFramework: '#run: 'Server accepts & closes connection''

2017-07-27 08:32:43 - DEBUG UnitTestFramework: '#run ok: 'Server accepts & closes connection''

2017-07-27 08:32:43 - DEBUG UnitTestFramework: '#teardown: 'Server accepts & closes connection''

2017-07-27 08:32:43 - DEBUG UnitTestFramework: '#teardown ok: 'Server accepts & closes connection''

2017-07-27 08:32:43 - DEBUG UnitTestFramework: '#setup: 'Server always returns 500''

2017-07-27 08:32:43 - DEBUG UnitTestFramework: '#setup ok: 'Server always returns 500''

2017-07-27 08:32:43 - DEBUG UnitTestFramework: '#run: 'Server always returns 500''

2017-07-27 08:32:44 - DEBUG UnitTestFramework: '#run ok: 'Server always returns 500''

2017-07-27 08:32:44 - DEBUG UnitTestFramework: '#teardown: 'Server always returns 500''

2017-07-27 08:32:44 - DEBUG UnitTestFramework: '#teardown ok: 'Server always returns 500''

2017-07-27 08:32:44 - DEBUG UnitTestFramework: '#setup: 'Server always returns 401''

2017-07-27 08:32:44 - DEBUG UnitTestFramework: '#setup ok: 'Server always returns 401''

2017-07-27 08:32:44 - DEBUG UnitTestFramework: '#run: 'Server always returns 401''

2017-07-27 08:32:44 - DEBUG UnitTestFramework: '#run ok: 'Server always returns 401''

2017-07-27 08:32:44 - DEBUG UnitTestFramework: '#teardown: 'Server always returns 401''

2017-07-27 08:32:44 - DEBUG UnitTestFramework: '#teardown ok: 'Server always returns 401''

2017-07-27 08:32:44 - DEBUG UnitTestFramework: '#setup: 'Server always returns 403''

2017-07-27 08:32:44 - DEBUG UnitTestFramework: '#setup ok: 'Server always returns 403''

2017-07-27 08:32:44 - DEBUG UnitTestFramework: '#run: 'Server always returns 403''

2017-07-27 08:32:44 - DEBUG UnitTestFramework: '#run ok: 'Server always returns 403''

2017-07-27 08:32:44 - DEBUG UnitTestFramework: '#teardown: 'Server always returns 403''

2017-07-27 08:32:44 - DEBUG UnitTestFramework: '#teardown ok: 'Server always returns 403''

2017-07-27 08:32:44 - DEBUG UnitTestFramework: '#setup: 'Make sure docs replicate with remote db with same name as local db''

2017-07-27 08:32:44 - DEBUG UnitTestFramework: '#setup ok: 'Make sure docs replicate with remote db with same name as local db''

2017-07-27 08:32:44 - DEBUG UnitTestFramework: '#run: 'Make sure docs replicate with remote db with same name as local db''

2017-07-27 08:32:48 - DEBUG UnitTestFramework: '#run ok: 'Make sure docs replicate with remote db with same name as local db''

2017-07-27 08:32:48 - DEBUG UnitTestFramework: '#teardown: 'Make sure docs replicate with remote db with same name as local db''

2017-07-27 08:32:49 - DEBUG UnitTestFramework: '#teardown ok: 'Make sure docs replicate with remote db with same name as local db''

2017-07-27 08:32:49 - DEBUG UnitTestFramework: '#setup: 'Make sure docs replicate with remote db with different name than local db''

2017-07-27 08:32:49 - DEBUG UnitTestFramework: '#setup ok: 'Make sure docs replicate with remote db with different name than local db''

2017-07-27 08:32:49 - DEBUG UnitTestFramework: '#run: 'Make sure docs replicate with remote db with different name than local db''

2017-07-27 08:32:53 - DEBUG UnitTestFramework: '#run ok: 'Make sure docs replicate with remote db with different name than local db''

2017-07-27 08:32:53 - DEBUG UnitTestFramework: '#teardown: 'Make sure docs replicate with remote db with different name than local db''

2017-07-27 08:32:53 - DEBUG UnitTestFramework: '#teardown ok: 'Make sure docs replicate with remote db with different name than local db''

2017-07-27 08:32:53 - DEBUG UnitTestFramework: '#setup: 'Do nothing and make sure we time out''

2017-07-27 08:32:53 - DEBUG UnitTestFramework: '#setup ok: 'Do nothing and make sure we time out''

2017-07-27 08:32:53 - DEBUG UnitTestFramework: '#run: 'Do nothing and make sure we time out''

2017-07-27 08:32:55 - DEBUG UnitTestFramework: '#run ok: 'Do nothing and make sure we time out''

2017-07-27 08:32:55 - DEBUG UnitTestFramework: '#teardown: 'Do nothing and make sure we time out''

2017-07-27 08:32:55 - DEBUG UnitTestFramework: '#teardown ok: 'Do nothing and make sure we time out''

2017-07-27 08:32:55 - DEBUG UnitTestFramework: '#setup: 'Do something and make sure we time out''

2017-07-27 08:32:55 - DEBUG UnitTestFramework: '#setup ok: 'Do something and make sure we time out''

2017-07-27 08:32:55 - DEBUG UnitTestFramework: '#run: 'Do something and make sure we time out''

2017-07-27 08:32:58 - DEBUG UnitTestFramework: '#run ok: 'Do something and make sure we time out''

2017-07-27 08:32:58 - DEBUG UnitTestFramework: '#teardown: 'Do something and make sure we time out''

2017-07-27 08:32:58 - DEBUG UnitTestFramework: '#teardown ok: 'Do something and make sure we time out''

2017-07-27 08:32:58 - DEBUG UnitTestFramework: '#setup: 'Start replicating and then catch error when server goes''

2017-07-27 08:32:58 - DEBUG UnitTestFramework: '#setup ok: 'Start replicating and then catch error when server goes''

2017-07-27 08:32:58 - DEBUG UnitTestFramework: '#run: 'Start replicating and then catch error when server goes''

2017-07-27 08:32:59 - DEBUG UnitTestFramework: '#run ok: 'Start replicating and then catch error when server goes''

2017-07-27 08:32:59 - DEBUG UnitTestFramework: '#teardown: 'Start replicating and then catch error when server goes''

2017-07-27 08:32:59 - DEBUG UnitTestFramework: '#teardown ok: 'Start replicating and then catch error when server goes''

2017-07-27 08:32:59 - DEBUG UnitTestFramework: '#setup: 'Make sure clone works''

2017-07-27 08:33:00 - DEBUG UnitTestFramework: '#setup ok: 'Make sure clone works''

2017-07-27 08:33:00 - DEBUG UnitTestFramework: '#run: 'Make sure clone works''

2017-07-27 08:33:02 - DEBUG UnitTestFramework: '#run ok: 'Make sure clone works''

2017-07-27 08:33:02 - DEBUG UnitTestFramework: '#teardown: 'Make sure clone works''

2017-07-27 08:33:03 - DEBUG UnitTestFramework: '#teardown ok: 'Make sure clone works''

2017-07-27 08:33:03 - DEBUG UnitTestFramework: '#setup: 'compareBufferArrays''

2017-07-27 08:33:05 - DEBUG UnitTestFramework: '#setup ok: 'compareBufferArrays''

2017-07-27 08:33:05 - DEBUG UnitTestFramework: '#run: 'compareBufferArrays''

2017-07-27 08:33:06 - DEBUG UnitTestFramework: '#run ok: 'compareBufferArrays''

2017-07-27 08:33:06 - DEBUG UnitTestFramework: '#teardown: 'compareBufferArrays''

2017-07-27 08:33:08 - DEBUG UnitTestFramework: '#teardown ok: 'compareBufferArrays''

2017-07-27 08:33:08 - DEBUG UnitTestFramework: '#setup: 'Call start twice and get error''

2017-07-27 08:33:09 - DEBUG UnitTestFramework: '#setup ok: 'Call start twice and get error''

2017-07-27 08:33:09 - DEBUG UnitTestFramework: '#run: 'Call start twice and get error''

2017-07-27 08:33:11 - DEBUG UnitTestFramework: '#run ok: 'Call start twice and get error''

2017-07-27 08:33:11 - DEBUG UnitTestFramework: '#teardown: 'Call start twice and get error''

2017-07-27 08:33:13 - DEBUG UnitTestFramework: '#teardown ok: 'Call start twice and get error''

2017-07-27 08:33:13 - DEBUG UnitTestFramework: '#setup: 'Start and make sure it runs''

2017-07-27 08:33:16 - DEBUG UnitTestFramework: '#setup ok: 'Start and make sure it runs''

2017-07-27 08:33:16 - DEBUG UnitTestFramework: '#run: 'Start and make sure it runs''

2017-07-27 08:33:18 - DEBUG UnitTestFramework: '#run ok: 'Start and make sure it runs''

2017-07-27 08:33:18 - DEBUG UnitTestFramework: '#teardown: 'Start and make sure it runs''

2017-07-27 08:33:21 - DEBUG UnitTestFramework: '#teardown ok: 'Start and make sure it runs''

2017-07-27 08:33:21 - DEBUG UnitTestFramework: '#setup: 'Make sure getTimeWhenRun is right after start''

2017-07-27 08:33:22 - DEBUG UnitTestFramework: '#setup ok: 'Make sure getTimeWhenRun is right after start''

2017-07-27 08:33:22 - DEBUG UnitTestFramework: '#run: 'Make sure getTimeWhenRun is right after start''

2017-07-27 08:33:25 - DEBUG UnitTestFramework: '#run ok: 'Make sure getTimeWhenRun is right after start''

2017-07-27 08:33:25 - DEBUG UnitTestFramework: '#teardown: 'Make sure getTimeWhenRun is right after start''

2017-07-27 08:33:27 - DEBUG UnitTestFramework: '#teardown ok: 'Make sure getTimeWhenRun is right after start''

2017-07-27 08:33:27 - DEBUG UnitTestFramework: '#setup: 'Make sure getTimeWhenRun is -1 after function is called''

2017-07-27 08:33:29 - DEBUG UnitTestFramework: '#setup ok: 'Make sure getTimeWhenRun is -1 after function is called''

2017-07-27 08:33:29 - DEBUG UnitTestFramework: '#run: 'Make sure getTimeWhenRun is -1 after function is called''

2017-07-27 08:33:32 - DEBUG UnitTestFramework: '#run ok: 'Make sure getTimeWhenRun is -1 after function is called''

2017-07-27 08:33:32 - DEBUG UnitTestFramework: '#teardown: 'Make sure getTimeWhenRun is -1 after function is called''

2017-07-27 08:33:34 - DEBUG UnitTestFramework: '#teardown ok: 'Make sure getTimeWhenRun is -1 after function is called''

2017-07-27 08:33:34 - DEBUG UnitTestFramework: '#setup: 'Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running''

2017-07-27 08:33:36 - DEBUG UnitTestFramework: '#setup ok: 'Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running''

2017-07-27 08:33:36 - DEBUG UnitTestFramework: '#run: 'Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running''

2017-07-27 08:33:38 - DEBUG UnitTestFramework: '#run ok: 'Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running''

2017-07-27 08:33:38 - DEBUG UnitTestFramework: '#teardown: 'Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running''

2017-07-27 08:33:41 - DEBUG UnitTestFramework: '#teardown ok: 'Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running''

2017-07-27 08:33:41 - DEBUG UnitTestFramework: '#setup: 'Test TransientState''

2017-07-27 08:33:44 - DEBUG UnitTestFramework: '#setup ok: 'Test TransientState''

2017-07-27 08:33:44 - DEBUG UnitTestFramework: '#run: 'Test TransientState''

2017-07-27 08:33:46 - DEBUG UnitTestFramework: '#run ok: 'Test TransientState''

2017-07-27 08:33:46 - DEBUG UnitTestFramework: '#teardown: 'Test TransientState''

2017-07-27 08:33:47 - DEBUG UnitTestFramework: '#teardown ok: 'Test TransientState''

2017-07-27 08:33:47 - DEBUG UnitTestFramework: '#setup: 'Coordinated seq test''

2017-07-27 08:33:49 - DEBUG UnitTestFramework: '#setup ok: 'Coordinated seq test''

2017-07-27 08:33:49 - DEBUG UnitTestFramework: '#run: 'Coordinated seq test''

2017-07-27 08:33:49 - INFO Socket: 'run skipped, test: 'Coordinated seq test', event: 'run_Coordinated seq test''

2017-07-27 08:33:50 - INFO Socket: 'run skipped, test: 'Coordinated seq test', event: 'run_Coordinated seq test''

2017-07-27 08:33:51 - INFO Socket: 'run skipped, test: 'Coordinated seq test', event: 'run_Coordinated seq test''

2017-07-27 08:33:51 - DEBUG UnitTestFramework: '#run ok: 'Coordinated seq test''

2017-07-27 08:33:51 - DEBUG UnitTestFramework: '#teardown: 'Coordinated seq test''

2017-07-27 08:33:55 - DEBUG UnitTestFramework: '#teardown ok: 'Coordinated seq test''

2017-07-27 08:33:55 - DEBUG UnitTestFramework: '#setup: 'test thali manager spies''

2017-07-27 08:33:57 - DEBUG UnitTestFramework: '#setup ok: 'test thali manager spies''

2017-07-27 08:33:57 - DEBUG UnitTestFramework: '#run: 'test thali manager spies''

2017-07-27 08:34:00 - DEBUG UnitTestFramework: '#run ok: 'test thali manager spies''

2017-07-27 08:34:00 - DEBUG UnitTestFramework: '#teardown: 'test thali manager spies''

2017-07-27 08:34:03 - DEBUG UnitTestFramework: '#teardown ok: 'test thali manager spies''

2017-07-27 08:34:03 - DEBUG UnitTestFramework: '#setup: 'test thali manager multiple starts and stops''

2017-07-27 08:34:06 - DEBUG UnitTestFramework: '#setup ok: 'test thali manager multiple starts and stops''

2017-07-27 08:34:06 - DEBUG UnitTestFramework: '#run: 'test thali manager multiple starts and stops''

2017-07-27 08:34:16 - DEBUG UnitTestFramework: '#run ok: 'test thali manager multiple starts and stops''

2017-07-27 08:34:16 - DEBUG UnitTestFramework: '#teardown: 'test thali manager multiple starts and stops''

2017-07-27 08:34:18 - DEBUG UnitTestFramework: '#teardown ok: 'test thali manager multiple starts and stops''

2017-07-27 08:34:18 - DEBUG UnitTestFramework: '#setup: 'ssdp server and client should be restarted when wifi toggled''

2017-07-27 08:34:19 - DEBUG UnitTestFramework: '#setup ok: 'ssdp server and client should be restarted when wifi toggled''

2017-07-27 08:34:19 - DEBUG UnitTestFramework: '#run: 'ssdp server and client should be restarted when wifi toggled''

2017-07-27 08:34:19 - INFO Socket: 'run skipped, test: 'ssdp server and client should be restarted when wifi toggled', event: 'run_ssdp server and client should be restarted when wifi toggled''

2017-07-27 08:34:21 - INFO Socket: 'run skipped, test: 'ssdp server and client should be restarted when wifi toggled', event: 'run_ssdp server and client should be restarted when wifi toggled''

2017-07-27 08:34:21 - INFO Socket: 'run skipped, test: 'ssdp server and client should be restarted when wifi toggled', event: 'run_ssdp server and client should be restarted when wifi toggled''

2017-07-27 08:34:21 - DEBUG UnitTestFramework: '#run ok: 'ssdp server and client should be restarted when wifi toggled''

2017-07-27 08:34:21 - DEBUG UnitTestFramework: '#teardown: 'ssdp server and client should be restarted when wifi toggled''

2017-07-27 08:34:22 - DEBUG UnitTestFramework: '#teardown ok: 'ssdp server and client should be restarted when wifi toggled''

2017-07-27 08:34:22 - DEBUG UnitTestFramework: '#setup: 'ssdp server and client should be restarted when bssid changed''

2017-07-27 08:34:24 - DEBUG UnitTestFramework: '#setup ok: 'ssdp server and client should be restarted when bssid changed''

2017-07-27 08:34:24 - DEBUG UnitTestFramework: '#run: 'ssdp server and client should be restarted when bssid changed''

2017-07-27 08:34:24 - INFO Socket: 'run skipped, test: 'ssdp server and client should be restarted when bssid changed', event: 'run_ssdp server and client should be restarted when bssid changed''

2017-07-27 08:34:24 - INFO Socket: 'run skipped, test: 'ssdp server and client should be restarted when bssid changed', event: 'run_ssdp server and client should be restarted when bssid changed''

2017-07-27 08:34:25 - INFO Socket: 'run skipped, test: 'ssdp server and client should be restarted when bssid changed', event: 'run_ssdp server and client should be restarted when bssid changed''

2017-07-27 08:34:25 - DEBUG UnitTestFramework: '#run ok: 'ssdp server and client should be restarted when bssid changed''

2017-07-27 08:34:25 - DEBUG UnitTestFramework: '#teardown: 'ssdp server and client should be restarted when bssid changed''

2017-07-27 08:34:27 - DEBUG UnitTestFramework: '#teardown ok: 'ssdp server and client should be restarted when bssid changed''

2017-07-27 08:34:27 - DEBUG UnitTestFramework: '#setup: 'ssdp server and client should be restarted only when advertising/listening is active''

2017-07-27 08:34:28 - DEBUG UnitTestFramework: '#setup ok: 'ssdp server and client should be restarted only when advertising/listening is active''

2017-07-27 08:34:28 - DEBUG UnitTestFramework: '#run: 'ssdp server and client should be restarted only when advertising/listening is active''

2017-07-27 08:34:28 - INFO Socket: 'run skipped, test: 'ssdp server and client should be restarted only when advertising/listening is active', event: 'run_ssdp server and client should be restarted only when advertising/listening is active''

2017-07-27 08:34:29 - INFO Socket: 'run skipped, test: 'ssdp server and client should be restarted only when advertising/listening is active', event: 'run_ssdp server and client should be restarted only when advertising/listening is active''

2017-07-27 08:34:31 - INFO Socket: 'run skipped, test: 'ssdp server and client should be restarted only when advertising/listening is active', event: 'run_ssdp server and client should be restarted only when advertising/listening is active''

2017-07-27 08:34:31 - DEBUG UnitTestFramework: '#run ok: 'ssdp server and client should be restarted only when advertising/listening is active''

2017-07-27 08:34:31 - DEBUG UnitTestFramework: '#teardown: 'ssdp server and client should be restarted only when advertising/listening is active''

2017-07-27 08:34:32 - DEBUG UnitTestFramework: '#teardown ok: 'ssdp server and client should be restarted only when advertising/listening is active''

2017-07-27 08:34:32 - DEBUG UnitTestFramework: 'all unit tests succeeded, platformName: 'android''

2017-07-27 08:34:32 - DEBUG UnitTestFramework: 'skipped tests: '["Call of onCheckpointReached handler on a single db change","Call of multiple onCheckpointReached handlers on a single db change","Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval","Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval","skip","another skip","Can shift data via parallel connections","Test updating advertising and parallel data transfer","Get error when trying to double connect to a peer on Android","#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection","#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer","initial peer discovery","update peer discovery 1","update peer discovery 2","check latest peer discovery","Set up for no peer discovery test","no peer discovery","Single coordinated request ios native","Multiple coordinated request ios native","#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)","does not emit duplicate discoveryAdvertisingStateUpdate","native available - peer with greater generation is cached (MPCF)","native available - peer with same or older generation is ignored (MPCF)","networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)","multiconnect failure - new peer is ignored (MPCF)","multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)","newAddressPort field (MPCF)","#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)","network changes emitted correctly","network changes not emitted in started state","network changes not emitted in stopped state","We properly fire peer unavailable and then available when connection fails on iOS","peer should be found once after listening and discovery started","test for data corruption","Client to server request coordinated","Test HTTP_BAD_RESPONSE locally","#parseBeacons addressBookCallback returns no matches","Coordinated pull replication from notification test","Coordinated seq test","ssdp server and client should be restarted when wifi toggled","ssdp server and client should be restarted when bssid changed","ssdp server and client should be restarted only when advertising/listening is active"]''

2017-07-27 08:34:34 - DEBUG TestServer: 'completed'

2017-07-27 08:34:34 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-07-27 08:34:34 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''

2017-07-27 08:34:34 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

[0;31merror: command 'sudo jx ______.js android' failed with code 1, file 'bash' on line 30[0m
One or more Android tests are failed.
 [0m
index.js failed [ 0 ]

```


Logs for system : 
```

android : No Error
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
Test has SUCCEED

Stopping App:com.thaliproject.thalitest ce061606e320561102 green
Device test finished on ce061606e320561102 
Android task is completed. [SUCCESS]
Stopping App:com.thaliproject.thalitest ce061606e320561102 green
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/1133518519b464b1_CI_sanity_check_jareksl/thali01_samsung-SM-G935F.md)

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
is Device booted ce061606c181d71003 10000 green
Checking:  adb -s ce061606c181d71003 shell getprop sys.boot_completed green

All devices are ready!

Deploying to ce061606c181d71003
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce061606c181d71003

Starting application ThaliTest on ce061606c181d71003

App was succesfully started on ce061606c181d71003

STOP log received from ce061606c181d71003
Test has SUCCEED

Stopping App:com.thaliproject.thalitest ce061606c181d71003 green
Device test finished on ce061606c181d71003 
Android task is completed. [SUCCESS]
Stopping App:com.thaliproject.thalitest ce061606c181d71003 green
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/1133518519b464b1_CI_sanity_check_jareksl/thali03_samsung-SM-G930F.md)

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
Test has SUCCEED

Stopping App:com.thaliproject.thalitest ce0616068b9f212302 green
Device test finished on ce0616068b9f212302 
Android task is completed. [SUCCESS]
Stopping App:com.thaliproject.thalitest ce0616068b9f212302 green
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/1133518519b464b1_CI_sanity_check_jareksl/thali04_samsung-SM-G930F.md)



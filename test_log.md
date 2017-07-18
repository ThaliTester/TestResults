#### Test 1133518512a72c5b Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2017-07-18 20:42:06 - INFO HttpServer: 'listening on *:3000'

2017-07-18 20:43:44 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'e114ab8b-ef51-4353-9777-37b1d743ca3a', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-18 20:43:44 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-07-18 20:44:02 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'a4e3812e-78aa-49f2-8f42-452cc7da8fcc', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-18 20:44:02 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-07-18 20:45:17 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '737cb3c4-b03b-43c2-bac1-24ceca3705f7', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-18 20:45:17 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-07-18 20:45:17 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-07-18 20:45:17 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-07-18 20:45:17 - DEBUG UnitTestFramework: 'scheduling tests'

2017-07-18 20:45:19 - DEBUG UnitTestFramework: 'tests scheduled'

2017-07-18 20:45:19 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-07-18 20:45:19 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-07-18 20:45:19 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-07-18 20:45:19 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-07-18 20:45:19 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-07-18 20:45:19 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-07-18 20:45:19 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-07-18 20:45:19 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-07-18 20:45:19 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-07-18 20:45:20 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-07-18 20:45:20 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-07-18 20:45:20 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-07-18 20:45:20 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-18 20:45:20 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-18 20:45:20 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-18 20:45:20 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-18 20:45:20 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-18 20:45:20 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-18 20:45:20 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-18 20:45:20 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-18 20:45:20 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-18 20:45:20 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-18 20:45:20 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-18 20:45:20 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-18 20:45:20 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-07-18 20:45:20 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-18 20:45:20 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-07-18 20:45:20 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-18 20:45:20 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-18 20:45:20 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-18 20:45:20 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-18 20:45:20 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-07-18 20:45:20 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-18 20:45:20 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-18 20:45:20 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-18 20:45:20 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-18 20:45:20 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-18 20:45:20 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-18 20:45:20 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-18 20:45:20 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-18 20:45:20 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-18 20:45:20 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-18 20:45:20 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-18 20:45:20 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-18 20:45:20 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-18 20:45:20 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-18 20:45:20 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-18 20:45:20 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
2017-07-18 20:45:20 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
2017-07-18 20:45:20 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-18 20:45:21 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-18 20:45:21 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-18 20:45:21 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-18 20:45:21 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-18 20:45:21 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-18 20:45:21 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-18 20:45:21 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-18 20:45:21 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-18 20:45:21 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-18 20:45:21 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-18 20:45:21 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-07-18 20:45:21 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-07-18 20:45:21 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-07-18 20:45:21 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-07-18 20:45:21 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-07-18 20:45:21 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-07-18 20:45:21 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-07-18 20:45:21 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-07-18 20:45:21 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-07-18 20:45:24 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-07-18 20:45:24 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-07-18 20:45:26 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-07-18 20:45:26 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-07-18 20:45:27 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-07-18 20:45:27 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-07-18 20:45:30 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-07-18 20:45:30 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-07-18 20:45:32 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-07-18 20:45:32 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-07-18 20:45:33 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-07-18 20:45:33 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-07-18 20:45:35 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-07-18 20:45:35 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-07-18 20:45:37 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-07-18 20:45:37 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-07-18 20:45:40 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-07-18 20:45:40 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-07-18 20:45:43 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-07-18 20:45:43 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-07-18 20:45:45 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-07-18 20:45:45 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-07-18 20:45:46 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-07-18 20:45:46 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-07-18 20:45:46 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-07-18 20:45:46 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-07-18 20:45:46 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-07-18 20:45:46 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-07-18 20:45:46 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-07-18 20:45:46 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-07-18 20:45:46 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-07-18 20:45:46 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-07-18 20:45:46 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-07-18 20:45:46 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-07-18 20:45:46 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-07-18 20:45:46 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-07-18 20:45:46 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-07-18 20:45:46 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-07-18 20:45:46 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-07-18 20:45:46 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-07-18 20:45:46 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-07-18 20:45:46 - DEBUG UnitTestFramework: '#run: 'basic''

2017-07-18 20:45:46 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-07-18 20:45:46 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-07-18 20:45:46 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-07-18 20:45:46 - DEBUG UnitTestFramework: '#setup: 'another''

2017-07-18 20:45:46 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-07-18 20:45:46 - DEBUG UnitTestFramework: '#run: 'another''

2017-07-18 20:45:46 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-07-18 20:45:46 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-07-18 20:45:46 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-07-18 20:45:46 - DEBUG UnitTestFramework: '#setup: 'skip''

2017-07-18 20:45:46 - DEBUG UnitTestFramework: '#setup ok: 'skip''

2017-07-18 20:45:46 - DEBUG UnitTestFramework: '#run: 'skip''

2017-07-18 20:45:46 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-07-18 20:45:46 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-07-18 20:45:46 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-07-18 20:45:46 - DEBUG UnitTestFramework: '#run ok: 'skip''

2017-07-18 20:45:46 - DEBUG UnitTestFramework: '#teardown: 'skip''

2017-07-18 20:45:46 - DEBUG UnitTestFramework: '#teardown ok: 'skip''

2017-07-18 20:45:46 - DEBUG UnitTestFramework: '#setup: 'another skip''

2017-07-18 20:45:46 - DEBUG UnitTestFramework: '#setup ok: 'another skip''

2017-07-18 20:45:46 - DEBUG UnitTestFramework: '#run: 'another skip''

2017-07-18 20:45:46 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-07-18 20:45:47 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-07-18 20:45:47 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-07-18 20:45:47 - DEBUG UnitTestFramework: '#run ok: 'another skip''

2017-07-18 20:45:47 - DEBUG UnitTestFramework: '#teardown: 'another skip''

2017-07-18 20:45:47 - DEBUG UnitTestFramework: '#teardown ok: 'another skip''

2017-07-18 20:45:47 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox spy''

2017-07-18 20:45:47 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox spy''

2017-07-18 20:45:47 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox spy''

2017-07-18 20:45:47 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox spy''

2017-07-18 20:45:47 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox spy''

2017-07-18 20:45:47 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox spy''

2017-07-18 20:45:47 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub''

2017-07-18 20:45:49 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub''

2017-07-18 20:45:49 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub''

2017-07-18 20:45:50 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub''

2017-07-18 20:45:50 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub''

2017-07-18 20:45:53 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub''

2017-07-18 20:45:53 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub override''

2017-07-18 20:45:55 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub override''

2017-07-18 20:45:55 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub override''

2017-07-18 20:45:56 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub override''

2017-07-18 20:45:56 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub override''

2017-07-18 20:45:58 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub override''

2017-07-18 20:45:58 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox mock''

2017-07-18 20:46:00 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox mock''

2017-07-18 20:46:00 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox mock''

2017-07-18 20:46:03 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox mock''

2017-07-18 20:46:03 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox mock''

2017-07-18 20:46:05 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox mock''

2017-07-18 20:46:05 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox restore after test end''

2017-07-18 20:46:07 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox restore after test end''

2017-07-18 20:46:07 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox restore after test end''

2017-07-18 20:46:10 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox restore after test end''

2017-07-18 20:46:10 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox restore after test end''

2017-07-18 20:46:12 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox restore after test end''

2017-07-18 20:46:12 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-07-18 20:46:13 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-07-18 20:46:13 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-07-18 20:46:14 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-07-18 20:46:14 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-07-18 20:46:16 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-07-18 20:46:16 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-07-18 20:46:19 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-07-18 20:46:19 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-07-18 20:46:21 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-07-18 20:46:21 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-07-18 20:46:22 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-07-18 20:46:22 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-07-18 20:46:24 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-07-18 20:46:24 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-07-18 20:46:26 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-07-18 20:46:26 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-07-18 20:46:28 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-07-18 20:46:28 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-07-18 20:46:30 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-07-18 20:46:30 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-07-18 20:46:33 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-07-18 20:46:33 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-07-18 20:46:35 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-07-18 20:46:35 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-07-18 20:46:36 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-07-18 20:46:36 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-07-18 20:46:41 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-07-18 20:46:41 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-07-18 20:46:44 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-07-18 20:46:44 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-18 20:46:46 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-18 20:46:46 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-18 20:46:47 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-18 20:46:47 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-18 20:46:51 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-18 20:46:51 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-18 20:46:54 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-18 20:46:54 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-18 20:46:56 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-18 20:46:56 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-18 20:46:57 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-18 20:46:57 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-18 20:46:57 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-18 20:46:57 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-18 20:46:58 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-18 20:46:58 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-18 20:46:58 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-18 20:46:58 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-18 20:46:58 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-18 20:46:58 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-18 20:46:59 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-18 20:46:59 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-18 20:47:02 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-18 20:47:02 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-18 20:47:05 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-18 20:47:05 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-18 20:47:10 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-18 20:47:10 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-18 20:47:13 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-18 20:47:13 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-07-18 20:47:16 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-07-18 20:47:16 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-07-18 20:47:20 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-07-18 20:47:20 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-07-18 20:47:22 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-07-18 20:47:22 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-07-18 20:47:25 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-07-18 20:47:25 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-07-18 20:48:04 - DEBUG UnitTestFramework: '#run ok: 'Can connect to a remote peer''

2017-07-18 20:48:04 - DEBUG UnitTestFramework: '#teardown: 'Can connect to a remote peer''

2017-07-18 20:48:06 - DEBUG UnitTestFramework: '#teardown ok: 'Can connect to a remote peer''

2017-07-18 20:48:06 - DEBUG UnitTestFramework: '#setup: 'Can shift data''

2017-07-18 20:48:07 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data''

2017-07-18 20:48:07 - DEBUG UnitTestFramework: '#run: 'Can shift data''

2017-07-18 20:48:16 - DEBUG UnitTestFramework: '#run ok: 'Can shift data''

2017-07-18 20:48:16 - DEBUG UnitTestFramework: '#teardown: 'Can shift data''

2017-07-18 20:48:19 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data''

2017-07-18 20:48:19 - DEBUG UnitTestFramework: '#setup: 'Can shift data via parallel connections''

2017-07-18 20:48:20 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data via parallel connections''

2017-07-18 20:48:20 - DEBUG UnitTestFramework: '#run: 'Can shift data via parallel connections''

2017-07-18 20:48:20 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-07-18 20:48:20 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-07-18 20:48:22 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-07-18 20:48:22 - DEBUG UnitTestFramework: '#run ok: 'Can shift data via parallel connections''

2017-07-18 20:48:22 - DEBUG UnitTestFramework: '#teardown: 'Can shift data via parallel connections''

2017-07-18 20:48:23 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data via parallel connections''

2017-07-18 20:48:23 - DEBUG UnitTestFramework: '#setup: 'Can shift data securely''

2017-07-18 20:48:25 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data securely''

2017-07-18 20:48:25 - DEBUG UnitTestFramework: '#run: 'Can shift data securely''

2017-07-18 20:48:38 - DEBUG UnitTestFramework: '#run ok: 'Can shift data securely''

2017-07-18 20:48:38 - DEBUG UnitTestFramework: '#teardown: 'Can shift data securely''

2017-07-18 20:48:40 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data securely''

2017-07-18 20:48:40 - DEBUG UnitTestFramework: '#setup: 'Can shift large amounts of data''

2017-07-18 20:48:43 - DEBUG UnitTestFramework: '#setup ok: 'Can shift large amounts of data''

2017-07-18 20:48:43 - DEBUG UnitTestFramework: '#run: 'Can shift large amounts of data''

2017-07-18 20:49:00 - DEBUG UnitTestFramework: '#run ok: 'Can shift large amounts of data''

2017-07-18 20:49:00 - DEBUG UnitTestFramework: '#teardown: 'Can shift large amounts of data''

2017-07-18 20:49:03 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift large amounts of data''

2017-07-18 20:49:03 - DEBUG UnitTestFramework: '#setup: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-18 20:49:03 - DEBUG UnitTestFramework: '#setup ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-18 20:49:03 - DEBUG UnitTestFramework: '#run: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-18 20:49:11 - DEBUG UnitTestFramework: '#run ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-18 20:49:11 - DEBUG UnitTestFramework: '#teardown: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-18 20:49:13 - DEBUG UnitTestFramework: '#teardown ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-18 20:49:13 - DEBUG UnitTestFramework: '#setup: 'Test updating advertising and parallel data transfer''

2017-07-18 20:49:16 - DEBUG UnitTestFramework: '#setup ok: 'Test updating advertising and parallel data transfer''

2017-07-18 20:49:16 - DEBUG UnitTestFramework: '#run: 'Test updating advertising and parallel data transfer''

2017-07-18 20:49:16 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-07-18 20:49:17 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-07-18 20:49:18 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-07-18 20:49:18 - DEBUG UnitTestFramework: '#run ok: 'Test updating advertising and parallel data transfer''

2017-07-18 20:49:19 - DEBUG UnitTestFramework: '#teardown: 'Test updating advertising and parallel data transfer''

2017-07-18 20:49:20 - DEBUG UnitTestFramework: '#teardown ok: 'Test updating advertising and parallel data transfer''

2017-07-18 20:49:20 - DEBUG UnitTestFramework: '#setup: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-18 20:49:22 - DEBUG UnitTestFramework: '#setup ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-18 20:49:22 - DEBUG UnitTestFramework: '#run: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-18 20:49:27 - DEBUG UnitTestFramework: '#run ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-18 20:49:27 - DEBUG UnitTestFramework: '#teardown: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-18 20:49:28 - DEBUG UnitTestFramework: '#teardown ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-18 20:49:28 - DEBUG UnitTestFramework: '#setup: 'cannot call connect when start listening for advertisements is not active''

2017-07-18 20:49:31 - DEBUG UnitTestFramework: '#setup ok: 'cannot call connect when start listening for advertisements is not active''

2017-07-18 20:49:31 - DEBUG UnitTestFramework: '#run: 'cannot call connect when start listening for advertisements is not active''

2017-07-18 20:49:34 - DEBUG UnitTestFramework: '#run ok: 'cannot call connect when start listening for advertisements is not active''

2017-07-18 20:49:34 - DEBUG UnitTestFramework: '#teardown: 'cannot call connect when start listening for advertisements is not active''

2017-07-18 20:49:36 - DEBUG UnitTestFramework: '#teardown ok: 'cannot call connect when start listening for advertisements is not active''

2017-07-18 20:49:36 - DEBUG UnitTestFramework: '#setup: 'Get error when trying to double connect to a peer on Android''

2017-07-18 20:49:39 - DEBUG UnitTestFramework: '#setup ok: 'Get error when trying to double connect to a peer on Android''

2017-07-18 20:49:39 - DEBUG UnitTestFramework: '#run: 'Get error when trying to double connect to a peer on Android''

2017-07-18 20:49:40 - INFO Socket: 'run skipped, test: 'Get error when trying to double connect to a peer on Android', event: 'run_Get error when trying to double connect to a peer on Android''

2017-07-18 20:49:42 - INFO Socket: 'run skipped, test: 'Get error when trying to double connect to a peer on Android', event: 'run_Get error when trying to double connect to a peer on Android''

2017-07-18 20:49:43 - INFO Socket: 'run skipped, test: 'Get error when trying to double connect to a peer on Android', event: 'run_Get error when trying to double connect to a peer on Android''

2017-07-18 20:49:43 - DEBUG UnitTestFramework: '#run ok: 'Get error when trying to double connect to a peer on Android''

2017-07-18 20:49:43 - DEBUG UnitTestFramework: '#teardown: 'Get error when trying to double connect to a peer on Android''

2017-07-18 20:49:46 - DEBUG UnitTestFramework: '#teardown ok: 'Get error when trying to double connect to a peer on Android''

2017-07-18 20:49:46 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-18 20:49:46 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-18 20:49:46 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-18 20:49:49 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-18 20:49:49 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-18 20:49:51 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-18 20:49:51 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-18 20:49:53 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-18 20:49:53 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-18 20:49:53 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection', event: 'run_#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-18 20:49:53 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection', event: 'run_#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-18 20:49:54 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection', event: 'run_#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-18 20:49:54 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-18 20:49:54 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-18 20:49:56 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-18 20:49:56 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-18 20:49:58 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-18 20:49:58 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-18 20:50:13 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-18 20:50:13 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-18 20:50:16 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-18 20:50:16 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-18 20:50:18 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-18 20:50:18 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-18 20:50:25 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-18 20:50:25 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-18 20:50:27 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-18 20:50:27 - DEBUG UnitTestFramework: '#setup: 'initial peer discovery''

2017-07-18 20:50:29 - DEBUG UnitTestFramework: '#setup ok: 'initial peer discovery''

2017-07-18 20:50:29 - DEBUG UnitTestFramework: '#run: 'initial peer discovery''

2017-07-18 20:50:29 - INFO Socket: 'run skipped, test: 'initial peer discovery', event: 'run_initial peer discovery''

2017-07-18 20:50:30 - INFO Socket: 'run skipped, test: 'initial peer discovery', event: 'run_initial peer discovery''

2017-07-18 20:50:31 - INFO Socket: 'run skipped, test: 'initial peer discovery', event: 'run_initial peer discovery''

2017-07-18 20:50:31 - DEBUG UnitTestFramework: '#run ok: 'initial peer discovery''

2017-07-18 20:50:31 - DEBUG UnitTestFramework: '#teardown: 'initial peer discovery''

2017-07-18 20:50:32 - DEBUG UnitTestFramework: '#teardown ok: 'initial peer discovery''

2017-07-18 20:50:32 - DEBUG UnitTestFramework: '#setup: 'update peer discovery 1''

2017-07-18 20:50:34 - DEBUG UnitTestFramework: '#setup ok: 'update peer discovery 1''

2017-07-18 20:50:34 - DEBUG UnitTestFramework: '#run: 'update peer discovery 1''

2017-07-18 20:50:34 - INFO Socket: 'run skipped, test: 'update peer discovery 1', event: 'run_update peer discovery 1''

2017-07-18 20:50:34 - INFO Socket: 'run skipped, test: 'update peer discovery 1', event: 'run_update peer discovery 1''

2017-07-18 20:50:34 - INFO Socket: 'run skipped, test: 'update peer discovery 1', event: 'run_update peer discovery 1''

2017-07-18 20:50:34 - DEBUG UnitTestFramework: '#run ok: 'update peer discovery 1''

2017-07-18 20:50:34 - DEBUG UnitTestFramework: '#teardown: 'update peer discovery 1''

2017-07-18 20:50:37 - DEBUG UnitTestFramework: '#teardown ok: 'update peer discovery 1''

2017-07-18 20:50:37 - DEBUG UnitTestFramework: '#setup: 'update peer discovery 2''

2017-07-18 20:50:42 - DEBUG UnitTestFramework: '#setup ok: 'update peer discovery 2''

2017-07-18 20:50:42 - DEBUG UnitTestFramework: '#run: 'update peer discovery 2''

2017-07-18 20:50:42 - INFO Socket: 'run skipped, test: 'update peer discovery 2', event: 'run_update peer discovery 2''

2017-07-18 20:50:43 - INFO Socket: 'run skipped, test: 'update peer discovery 2', event: 'run_update peer discovery 2''

2017-07-18 20:50:43 - INFO Socket: 'run skipped, test: 'update peer discovery 2', event: 'run_update peer discovery 2''

2017-07-18 20:50:43 - DEBUG UnitTestFramework: '#run ok: 'update peer discovery 2''

2017-07-18 20:50:43 - DEBUG UnitTestFramework: '#teardown: 'update peer discovery 2''

2017-07-18 20:50:43 - DEBUG UnitTestFramework: '#teardown ok: 'update peer discovery 2''

2017-07-18 20:50:43 - DEBUG UnitTestFramework: '#setup: 'check latest peer discovery''

2017-07-18 20:50:46 - DEBUG UnitTestFramework: '#setup ok: 'check latest peer discovery''

2017-07-18 20:50:46 - DEBUG UnitTestFramework: '#run: 'check latest peer discovery''

2017-07-18 20:50:46 - INFO Socket: 'run skipped, test: 'check latest peer discovery', event: 'run_check latest peer discovery''

2017-07-18 20:50:48 - INFO Socket: 'run skipped, test: 'check latest peer discovery', event: 'run_check latest peer discovery''

2017-07-18 20:50:49 - INFO Socket: 'run skipped, test: 'check latest peer discovery', event: 'run_check latest peer discovery''

2017-07-18 20:50:49 - DEBUG UnitTestFramework: '#run ok: 'check latest peer discovery''

2017-07-18 20:50:49 - DEBUG UnitTestFramework: '#teardown: 'check latest peer discovery''

2017-07-18 20:50:51 - DEBUG UnitTestFramework: '#teardown ok: 'check latest peer discovery''

2017-07-18 20:50:51 - DEBUG UnitTestFramework: '#setup: 'Set up for no peer discovery test''

2017-07-18 20:50:54 - DEBUG UnitTestFramework: '#setup ok: 'Set up for no peer discovery test''

2017-07-18 20:50:54 - DEBUG UnitTestFramework: '#run: 'Set up for no peer discovery test''

2017-07-18 20:50:54 - INFO Socket: 'run skipped, test: 'Set up for no peer discovery test', event: 'run_Set up for no peer discovery test''

2017-07-18 20:50:54 - INFO Socket: 'run skipped, test: 'Set up for no peer discovery test', event: 'run_Set up for no peer discovery test''

2017-07-18 20:50:54 - INFO Socket: 'run skipped, test: 'Set up for no peer discovery test', event: 'run_Set up for no peer discovery test''

2017-07-18 20:50:54 - DEBUG UnitTestFramework: '#run ok: 'Set up for no peer discovery test''

2017-07-18 20:50:54 - DEBUG UnitTestFramework: '#teardown: 'Set up for no peer discovery test''

2017-07-18 20:50:57 - DEBUG UnitTestFramework: '#teardown ok: 'Set up for no peer discovery test''

2017-07-18 20:50:57 - DEBUG UnitTestFramework: '#setup: 'no peer discovery''

2017-07-18 20:50:58 - DEBUG UnitTestFramework: '#setup ok: 'no peer discovery''

2017-07-18 20:50:58 - DEBUG UnitTestFramework: '#run: 'no peer discovery''
2017-07-18 20:50:58 - INFO Socket: 'run skipped, test: 'no peer discovery', event: 'run_no peer discovery''

2017-07-18 20:50:59 - INFO Socket: 'run skipped, test: 'no peer discovery', event: 'run_no peer discovery''

2017-07-18 20:51:00 - INFO Socket: 'run skipped, test: 'no peer discovery', event: 'run_no peer discovery''

2017-07-18 20:51:00 - DEBUG UnitTestFramework: '#run ok: 'no peer discovery''

2017-07-18 20:51:00 - DEBUG UnitTestFramework: '#teardown: 'no peer discovery''

2017-07-18 20:51:03 - DEBUG UnitTestFramework: '#teardown ok: 'no peer discovery''

2017-07-18 20:51:03 - DEBUG UnitTestFramework: '#setup: 'calling createNativeListener directly rejects''

2017-07-18 20:51:04 - DEBUG UnitTestFramework: '#setup ok: 'calling createNativeListener directly rejects''

2017-07-18 20:51:04 - DEBUG UnitTestFramework: '#run: 'calling createNativeListener directly rejects''

2017-07-18 20:51:06 - DEBUG UnitTestFramework: '#run ok: 'calling createNativeListener directly rejects''

2017-07-18 20:51:06 - DEBUG UnitTestFramework: '#teardown: 'calling createNativeListener directly rejects''

2017-07-18 20:51:10 - DEBUG UnitTestFramework: '#teardown ok: 'calling createNativeListener directly rejects''

2017-07-18 20:51:10 - DEBUG UnitTestFramework: '#setup: 'emits incomingConnectionState''

2017-07-18 20:51:13 - DEBUG UnitTestFramework: '#setup ok: 'emits incomingConnectionState''

2017-07-18 20:51:13 - DEBUG UnitTestFramework: '#run: 'emits incomingConnectionState''

2017-07-18 20:51:16 - DEBUG UnitTestFramework: '#run ok: 'emits incomingConnectionState''

2017-07-18 20:51:16 - DEBUG UnitTestFramework: '#teardown: 'emits incomingConnectionState''

2017-07-18 20:51:17 - DEBUG UnitTestFramework: '#teardown ok: 'emits incomingConnectionState''

2017-07-18 20:51:17 - DEBUG UnitTestFramework: '#setup: 'emits routerPortConnectionFailed''

2017-07-18 20:51:19 - DEBUG UnitTestFramework: '#setup ok: 'emits routerPortConnectionFailed''

2017-07-18 20:51:19 - DEBUG UnitTestFramework: '#run: 'emits routerPortConnectionFailed''

2017-07-18 20:51:22 - DEBUG UnitTestFramework: '#run ok: 'emits routerPortConnectionFailed''

2017-07-18 20:51:22 - DEBUG UnitTestFramework: '#teardown: 'emits routerPortConnectionFailed''

2017-07-18 20:51:23 - DEBUG UnitTestFramework: '#teardown ok: 'emits routerPortConnectionFailed''

2017-07-18 20:51:23 - DEBUG UnitTestFramework: '#setup: 'native server connections all up''

2017-07-18 20:51:25 - DEBUG UnitTestFramework: '#setup ok: 'native server connections all up''

2017-07-18 20:51:25 - DEBUG UnitTestFramework: '#run: 'native server connections all up''

2017-07-18 20:51:28 - DEBUG UnitTestFramework: '#run ok: 'native server connections all up''

2017-07-18 20:51:28 - DEBUG UnitTestFramework: '#teardown: 'native server connections all up''

2017-07-18 20:51:29 - DEBUG UnitTestFramework: '#teardown ok: 'native server connections all up''

2017-07-18 20:51:29 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming stream cleans outgoing socket''

2017-07-18 20:51:31 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming stream cleans outgoing socket''

2017-07-18 20:51:31 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming stream cleans outgoing socket''

2017-07-18 20:51:34 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming stream cleans outgoing socket''

2017-07-18 20:51:34 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming stream cleans outgoing socket''

2017-07-18 20:51:35 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming stream cleans outgoing socket''

2017-07-18 20:51:35 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming connection cleans outgoing socket''

2017-07-18 20:51:38 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming connection cleans outgoing socket''

2017-07-18 20:51:38 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming connection cleans outgoing socket''

2017-07-18 20:51:40 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming connection cleans outgoing socket''

2017-07-18 20:51:40 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming connection cleans outgoing socket''

2017-07-18 20:51:43 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming connection cleans outgoing socket''

2017-07-18 20:51:43 - DEBUG UnitTestFramework: '#setup: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-18 20:51:44 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-18 20:51:44 - DEBUG UnitTestFramework: '#run: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-18 20:51:46 - DEBUG UnitTestFramework: '#run ok: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-18 20:51:46 - DEBUG UnitTestFramework: '#teardown: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-18 20:51:49 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-18 20:51:49 - DEBUG UnitTestFramework: '#setup: 'native server - closing the whole server cleans everything up''

2017-07-18 20:51:50 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing the whole server cleans everything up''

2017-07-18 20:51:50 - DEBUG UnitTestFramework: '#run: 'native server - closing the whole server cleans everything up''

2017-07-18 20:51:52 - DEBUG UnitTestFramework: '#run ok: 'native server - closing the whole server cleans everything up''

2017-07-18 20:51:52 - DEBUG UnitTestFramework: '#teardown: 'native server - closing the whole server cleans everything up''

2017-07-18 20:51:54 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing the whole server cleans everything up''

2017-07-18 20:51:54 - DEBUG UnitTestFramework: '#setup: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-18 20:51:56 - DEBUG UnitTestFramework: '#setup ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-18 20:51:56 - DEBUG UnitTestFramework: '#run: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-18 20:51:59 - DEBUG UnitTestFramework: '#run ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-18 20:51:59 - DEBUG UnitTestFramework: '#teardown: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-18 20:52:02 - DEBUG UnitTestFramework: '#teardown ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-18 20:52:02 - DEBUG UnitTestFramework: '#setup: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-18 20:52:04 - DEBUG UnitTestFramework: '#setup ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-18 20:52:04 - DEBUG UnitTestFramework: '#run: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-18 20:52:07 - DEBUG UnitTestFramework: '#run ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-18 20:52:07 - DEBUG UnitTestFramework: '#teardown: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-18 20:52:10 - DEBUG UnitTestFramework: '#teardown ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-18 20:52:10 - DEBUG UnitTestFramework: '#setup: 'native server - timing out the incoming connection cleans everything up''

2017-07-18 20:52:10 - DEBUG UnitTestFramework: '#setup ok: 'native server - timing out the incoming connection cleans everything up''

2017-07-18 20:52:10 - DEBUG UnitTestFramework: '#run: 'native server - timing out the incoming connection cleans everything up''

2017-07-18 20:52:13 - DEBUG UnitTestFramework: '#run ok: 'native server - timing out the incoming connection cleans everything up''

2017-07-18 20:52:13 - DEBUG UnitTestFramework: '#teardown: 'native server - timing out the incoming connection cleans everything up''

2017-07-18 20:52:13 - DEBUG UnitTestFramework: '#teardown ok: 'native server - timing out the incoming connection cleans everything up''

2017-07-18 20:52:13 - DEBUG UnitTestFramework: '#setup: 'can create servers manager''

2017-07-18 20:52:16 - DEBUG UnitTestFramework: '#setup ok: 'can create servers manager''

2017-07-18 20:52:16 - DEBUG UnitTestFramework: '#run: 'can create servers manager''

2017-07-18 20:52:17 - DEBUG UnitTestFramework: '#run ok: 'can create servers manager''

2017-07-18 20:52:17 - DEBUG UnitTestFramework: '#teardown: 'can create servers manager''

2017-07-18 20:52:19 - DEBUG UnitTestFramework: '#teardown ok: 'can create servers manager''

2017-07-18 20:52:19 - DEBUG UnitTestFramework: '#setup: 'calling stop without start causes error''

2017-07-18 20:52:22 - DEBUG UnitTestFramework: '#setup ok: 'calling stop without start causes error''

2017-07-18 20:52:22 - DEBUG UnitTestFramework: '#run: 'calling stop without start causes error''

2017-07-18 20:52:23 - DEBUG UnitTestFramework: '#run ok: 'calling stop without start causes error''

2017-07-18 20:52:23 - DEBUG UnitTestFramework: '#teardown: 'calling stop without start causes error''

2017-07-18 20:52:24 - DEBUG UnitTestFramework: '#teardown ok: 'calling stop without start causes error''

2017-07-18 20:52:24 - DEBUG UnitTestFramework: '#setup: 'can start/stop servers manager''

2017-07-18 20:52:26 - DEBUG UnitTestFramework: '#setup ok: 'can start/stop servers manager''

2017-07-18 20:52:26 - DEBUG UnitTestFramework: '#run: 'can start/stop servers manager''

2017-07-18 20:52:29 - DEBUG UnitTestFramework: '#run ok: 'can start/stop servers manager''

2017-07-18 20:52:29 - DEBUG UnitTestFramework: '#teardown: 'can start/stop servers manager''

2017-07-18 20:52:31 - DEBUG UnitTestFramework: '#teardown ok: 'can start/stop servers manager''

2017-07-18 20:52:31 - DEBUG UnitTestFramework: '#setup: 'starting twice resolves with listening port''

2017-07-18 20:52:32 - DEBUG UnitTestFramework: '#setup ok: 'starting twice resolves with listening port''

2017-07-18 20:52:32 - DEBUG UnitTestFramework: '#run: 'starting twice resolves with listening port''

2017-07-18 20:52:34 - DEBUG UnitTestFramework: '#run ok: 'starting twice resolves with listening port''

2017-07-18 20:52:34 - DEBUG UnitTestFramework: '#teardown: 'starting twice resolves with listening port''

2017-07-18 20:52:36 - DEBUG UnitTestFramework: '#teardown ok: 'starting twice resolves with listening port''

2017-07-18 20:52:36 - DEBUG UnitTestFramework: '#setup: 'terminateIncomingConnection will terminate a connection''

2017-07-18 20:52:38 - DEBUG UnitTestFramework: '#setup ok: 'terminateIncomingConnection will terminate a connection''

2017-07-18 20:52:38 - DEBUG UnitTestFramework: '#run: 'terminateIncomingConnection will terminate a connection''

2017-07-18 20:52:41 - DEBUG UnitTestFramework: '#run ok: 'terminateIncomingConnection will terminate a connection''

2017-07-18 20:52:41 - DEBUG UnitTestFramework: '#teardown: 'terminateIncomingConnection will terminate a connection''

2017-07-18 20:52:43 - DEBUG UnitTestFramework: '#teardown ok: 'terminateIncomingConnection will terminate a connection''

2017-07-18 20:52:43 - DEBUG UnitTestFramework: '#setup: 'terminate an Outgoing connection''

2017-07-18 20:52:45 - DEBUG UnitTestFramework: '#setup ok: 'terminate an Outgoing connection''

2017-07-18 20:52:45 - DEBUG UnitTestFramework: '#run: 'terminate an Outgoing connection''

2017-07-18 20:52:47 - DEBUG UnitTestFramework: '#run ok: 'terminate an Outgoing connection''

2017-07-18 20:52:47 - DEBUG UnitTestFramework: '#teardown: 'terminate an Outgoing connection''

2017-07-18 20:52:49 - DEBUG UnitTestFramework: '#teardown ok: 'terminate an Outgoing connection''

2017-07-18 20:52:49 - DEBUG UnitTestFramework: '#setup: 'Single local http request''

2017-07-18 20:52:51 - DEBUG UnitTestFramework: '#setup ok: 'Single local http request''

2017-07-18 20:52:51 - DEBUG UnitTestFramework: '#run: 'Single local http request''

2017-07-18 20:52:54 - DEBUG UnitTestFramework: '#run ok: 'Single local http request''

2017-07-18 20:52:54 - DEBUG UnitTestFramework: '#teardown: 'Single local http request''

2017-07-18 20:52:54 - DEBUG UnitTestFramework: '#teardown ok: 'Single local http request''

2017-07-18 20:52:54 - DEBUG UnitTestFramework: '#setup: 'Single coordinated request ios native''

2017-07-18 20:52:57 - DEBUG UnitTestFramework: '#setup ok: 'Single coordinated request ios native''

2017-07-18 20:52:57 - DEBUG UnitTestFramework: '#run: 'Single coordinated request ios native''

2017-07-18 20:52:57 - INFO Socket: 'run skipped, test: 'Single coordinated request ios native', event: 'run_Single coordinated request ios native''

2017-07-18 20:52:58 - INFO Socket: 'run skipped, test: 'Single coordinated request ios native', event: 'run_Single coordinated request ios native''

2017-07-18 20:52:58 - INFO Socket: 'run skipped, test: 'Single coordinated request ios native', event: 'run_Single coordinated request ios native''

2017-07-18 20:52:58 - DEBUG UnitTestFramework: '#run ok: 'Single coordinated request ios native''

2017-07-18 20:52:58 - DEBUG UnitTestFramework: '#teardown: 'Single coordinated request ios native''

2017-07-18 20:53:01 - DEBUG UnitTestFramework: '#teardown ok: 'Single coordinated request ios native''

2017-07-18 20:53:01 - DEBUG UnitTestFramework: '#setup: 'Multiple local http requests''

2017-07-18 20:53:03 - DEBUG UnitTestFramework: '#setup ok: 'Multiple local http requests''

2017-07-18 20:53:03 - DEBUG UnitTestFramework: '#run: 'Multiple local http requests''

2017-07-18 20:53:05 - DEBUG UnitTestFramework: '#run ok: 'Multiple local http requests''

2017-07-18 20:53:05 - DEBUG UnitTestFramework: '#teardown: 'Multiple local http requests''

2017-07-18 20:53:07 - DEBUG UnitTestFramework: '#teardown ok: 'Multiple local http requests''

2017-07-18 20:53:07 - DEBUG UnitTestFramework: '#setup: 'Multiple coordinated request ios native''

2017-07-18 20:53:10 - DEBUG UnitTestFramework: '#setup ok: 'Multiple coordinated request ios native''

2017-07-18 20:53:10 - DEBUG UnitTestFramework: '#run: 'Multiple coordinated request ios native''

2017-07-18 20:53:10 - INFO Socket: 'run skipped, test: 'Multiple coordinated request ios native', event: 'run_Multiple coordinated request ios native''

2017-07-18 20:53:13 - INFO Socket: 'run skipped, test: 'Multiple coordinated request ios native', event: 'run_Multiple coordinated request ios native''

2017-07-18 20:53:13 - INFO Socket: 'run skipped, test: 'Multiple coordinated request ios native', event: 'run_Multiple coordinated request ios native''

2017-07-18 20:53:13 - DEBUG UnitTestFramework: '#run ok: 'Multiple coordinated request ios native''

2017-07-18 20:53:13 - DEBUG UnitTestFramework: '#teardown: 'Multiple coordinated request ios native''

2017-07-18 20:53:15 - DEBUG UnitTestFramework: '#teardown ok: 'Multiple coordinated request ios native''

2017-07-18 20:53:15 - DEBUG UnitTestFramework: '#setup: '#startListeningForAdvertisements should fail if start not called''

2017-07-18 20:53:18 - DEBUG UnitTestFramework: '#setup ok: '#startListeningForAdvertisements should fail if start not called''

2017-07-18 20:53:18 - DEBUG UnitTestFramework: '#run: '#startListeningForAdvertisements should fail if start not called''

2017-07-18 20:53:19 - DEBUG UnitTestFramework: '#run ok: '#startListeningForAdvertisements should fail if start not called''

2017-07-18 20:53:19 - DEBUG UnitTestFramework: '#teardown: '#startListeningForAdvertisements should fail if start not called''

2017-07-18 20:53:21 - DEBUG UnitTestFramework: '#teardown ok: '#startListeningForAdvertisements should fail if start not called''

2017-07-18 20:53:21 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-18 20:53:22 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-18 20:53:22 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-18 20:53:24 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-18 20:53:24 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-18 20:53:25 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-18 20:53:25 - DEBUG UnitTestFramework: '#setup: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-18 20:53:27 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-18 20:53:27 - DEBUG UnitTestFramework: '#run: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-18 20:53:28 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-18 20:53:28 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-18 20:53:30 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-18 20:53:30 - DEBUG UnitTestFramework: '#setup: 'should be able to call #startListeningForAdvertisements many times''

2017-07-18 20:53:32 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #startListeningForAdvertisements many times''

2017-07-18 20:53:32 - DEBUG UnitTestFramework: '#run: 'should be able to call #startListeningForAdvertisements many times''

2017-07-18 20:53:36 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #startListeningForAdvertisements many times''

2017-07-18 20:53:36 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #startListeningForAdvertisements many times''

2017-07-18 20:53:39 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #startListeningForAdvertisements many times''

2017-07-18 20:53:39 - DEBUG UnitTestFramework: '#setup: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-18 20:53:43 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-18 20:53:43 - DEBUG UnitTestFramework: '#run: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-18 20:53:44 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-18 20:53:44 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-18 20:53:47 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-18 20:53:47 - DEBUG UnitTestFramework: '#setup: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-18 20:53:50 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-18 20:53:50 - DEBUG UnitTestFramework: '#run: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-18 20:53:52 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-18 20:53:52 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-18 20:53:53 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-18 20:53:53 - DEBUG UnitTestFramework: '#setup: 'can get the network status before starting''

2017-07-18 20:53:55 - DEBUG UnitTestFramework: '#setup ok: 'can get the network status before starting''

2017-07-18 20:53:55 - DEBUG UnitTestFramework: '#run: 'can get the network status before starting''

2017-07-18 20:53:56 - DEBUG UnitTestFramework: '#run ok: 'can get the network status before starting''

2017-07-18 20:53:56 - DEBUG UnitTestFramework: '#teardown: 'can get the network status before starting''

2017-07-18 20:53:58 - DEBUG UnitTestFramework: '#teardown ok: 'can get the network status before starting''

2017-07-18 20:53:58 - DEBUG UnitTestFramework: '#setup: 'error returned with bad router''

2017-07-18 20:54:01 - DEBUG UnitTestFramework: '#setup ok: 'error returned with bad router''

2017-07-18 20:54:01 - DEBUG UnitTestFramework: '#run: 'error returned with bad router''

2017-07-18 20:54:02 - DEBUG UnitTestFramework: '#run ok: 'error returned with bad router''

2017-07-18 20:54:02 - DEBUG UnitTestFramework: '#teardown: 'error returned with bad router''

2017-07-18 20:54:04 - DEBUG UnitTestFramework: '#teardown ok: 'error returned with bad router''

2017-07-18 20:54:04 - DEBUG UnitTestFramework: '#setup: 'all services are started when we call start''

2017-07-18 20:54:06 - DEBUG UnitTestFramework: '#setup ok: 'all services are started when we call start''

2017-07-18 20:54:06 - DEBUG UnitTestFramework: '#run: 'all services are started when we call start''

2017-07-18 20:54:11 - DEBUG UnitTestFramework: '#run ok: 'all services are started when we call start''

2017-07-18 20:54:11 - DEBUG UnitTestFramework: '#teardown: 'all services are started when we call start''

2017-07-18 20:54:13 - DEBUG UnitTestFramework: '#teardown ok: 'all services are started when we call start''

2017-07-18 20:54:13 - DEBUG UnitTestFramework: '#setup: 'TCP Servers Manager should be null when we call start on iOS''

2017-07-18 20:54:14 - DEBUG UnitTestFramework: '#setup ok: 'TCP Servers Manager should be null when we call start on iOS''

2017-07-18 20:54:14 - DEBUG UnitTestFramework: '#run: 'TCP Servers Manager should be null when we call start on iOS''

2017-07-18 20:54:14 - INFO Socket: 'run skipped, test: 'TCP Servers Manager should be null when we call start on iOS', event: 'run_TCP Servers Manager should be null when we call start on iOS''

2017-07-18 20:54:16 - INFO Socket: 'run skipped, test: 'TCP Servers Manager should be null when we call start on iOS', event: 'run_TCP Servers Manager should be null when we call start on iOS''

2017-07-18 20:54:17 - INFO Socket: 'run skipped, test: 'TCP Servers Manager should be null when we call start on iOS', event: 'run_TCP Servers Manager should be null when we call start on iOS''

2017-07-18 20:54:17 - DEBUG UnitTestFramework: '#run ok: 'TCP Servers Manager should be null when we call start on iOS''

2017-07-18 20:54:17 - DEBUG UnitTestFramework: '#teardown: 'TCP Servers Manager should be null when we call start on iOS''

2017-07-18 20:54:19 - DEBUG UnitTestFramework: '#teardown ok: 'TCP Servers Manager should be null when we call start on iOS''

2017-07-18 20:54:19 - DEBUG UnitTestFramework: '#setup: 'all services are stopped when we call stop''

2017-07-18 20:54:21 - DEBUG UnitTestFramework: '#setup ok: 'all services are stopped when we call stop''

2017-07-18 20:54:21 - DEBUG UnitTestFramework: '#run: 'all services are stopped when we call stop''

2017-07-18 20:54:25 - DEBUG UnitTestFramework: '#run ok: 'all services are stopped when we call stop''

2017-07-18 20:54:25 - DEBUG UnitTestFramework: '#teardown: 'all services are stopped when we call stop''

2017-07-18 20:54:27 - DEBUG UnitTestFramework: '#teardown ok: 'all services are stopped when we call stop''

2017-07-18 20:54:27 - DEBUG UnitTestFramework: '#setup: 'make sure terminateConnection is properly hooked up''

2017-07-18 20:54:28 - DEBUG UnitTestFramework: '#setup ok: 'make sure terminateConnection is properly hooked up''

2017-07-18 20:54:28 - DEBUG UnitTestFramework: '#run: 'make sure terminateConnection is properly hooked up''

2017-07-18 20:54:30 - DEBUG UnitTestFramework: '#run ok: 'make sure terminateConnection is properly hooked up''

2017-07-18 20:54:30 - DEBUG UnitTestFramework: '#teardown: 'make sure terminateConnection is properly hooked up''

2017-07-18 20:54:31 - DEBUG UnitTestFramework: '#teardown ok: 'make sure terminateConnection is properly hooked up''

2017-07-18 20:54:31 - DEBUG UnitTestFramework: '#setup: 'make sure terminateConnection is return error if we get called on iOS''

2017-07-18 20:54:34 - DEBUG UnitTestFramework: '#setup ok: 'make sure terminateConnection is return error if we get called on iOS''

2017-07-18 20:54:34 - DEBUG UnitTestFramework: '#run: 'make sure terminateConnection is return error if we get called on iOS''

2017-07-18 20:54:34 - INFO Socket: 'run skipped, test: 'make sure terminateConnection is return error if we get called on iOS', event: 'run_make sure terminateConnection is return error if we get called on iOS''

2017-07-18 20:54:34 - INFO Socket: 'run skipped, test: 'make sure terminateConnection is return error if we get called on iOS', event: 'run_make sure terminateConnection is return error if we get called on iOS''

2017-07-18 20:54:36 - INFO Socket: 'run skipped, test: 'make sure terminateConnection is return error if we get called on iOS', event: 'run_make sure terminateConnection is return error if we get called on iOS''

2017-07-18 20:54:36 - DEBUG UnitTestFramework: '#run ok: 'make sure terminateConnection is return error if we get called on iOS''

2017-07-18 20:54:36 - DEBUG UnitTestFramework: '#teardown: 'make sure terminateConnection is return error if we get called on iOS''

2017-07-18 20:54:38 - DEBUG UnitTestFramework: '#teardown ok: 'make sure terminateConnection is return error if we get called on iOS''

2017-07-18 20:54:38 - DEBUG UnitTestFramework: '#setup: 'make sure terminateListener is properly hooked up''

2017-07-18 20:54:40 - DEBUG UnitTestFramework: '#setup ok: 'make sure terminateListener is properly hooked up''

2017-07-18 20:54:40 - DEBUG UnitTestFramework: '#run: 'make sure terminateListener is properly hooked up''

2017-07-18 20:54:43 - DEBUG UnitTestFramework: '#run ok: 'make sure terminateListener is properly hooked up''

2017-07-18 20:54:43 - DEBUG UnitTestFramework: '#teardown: 'make sure terminateListener is properly hooked up''

2017-07-18 20:54:46 - DEBUG UnitTestFramework: '#teardown ok: 'make sure terminateListener is properly hooked up''

2017-07-18 20:54:46 - DEBUG UnitTestFramework: '#setup: 'make sure terminateListener is return error if we get called on iOS''

2017-07-18 20:54:47 - DEBUG UnitTestFramework: '#setup ok: 'make sure terminateListener is return error if we get called on iOS''

2017-07-18 20:54:47 - DEBUG UnitTestFramework: '#run: 'make sure terminateListener is return error if we get called on iOS''

2017-07-18 20:54:47 - INFO Socket: 'run skipped, test: 'make sure terminateListener is return error if we get called on iOS', event: 'run_make sure terminateListener is return error if we get called on iOS''

2017-07-18 20:54:48 - INFO Socket: 'run skipped, test: 'make sure terminateListener is return error if we get called on iOS', event: 'run_make sure terminateListener is return error if we get called on iOS''

2017-07-18 20:54:49 - INFO Socket: 'run skipped, test: 'make sure terminateListener is return error if we get called on iOS', event: 'run_make sure terminateListener is return error if we get called on iOS''

2017-07-18 20:54:49 - DEBUG UnitTestFramework: '#run ok: 'make sure terminateListener is return error if we get called on iOS''

2017-07-18 20:54:49 - DEBUG UnitTestFramework: '#teardown: 'make sure terminateListener is return error if we get called on iOS''

2017-07-18 20:54:51 - DEBUG UnitTestFramework: '#teardown ok: 'make sure terminateListener is return error if we get called on iOS''

2017-07-18 20:54:51 - DEBUG UnitTestFramework: '#setup: 'make sure we actually call kill connections properly''

2017-07-18 20:54:53 - DEBUG UnitTestFramework: '#setup ok: 'make sure we actually call kill connections properly''

2017-07-18 20:54:53 - DEBUG UnitTestFramework: '#run: 'make sure we actually call kill connections properly''

2017-07-18 20:54:54 - DEBUG UnitTestFramework: '#run ok: 'make sure we actually call kill connections properly''

2017-07-18 20:54:54 - DEBUG UnitTestFramework: '#teardown: 'make sure we actually call kill connections properly''

2017-07-18 20:54:56 - DEBUG UnitTestFramework: '#teardown ok: 'make sure we actually call kill connections properly''

2017-07-18 20:54:56 - DEBUG UnitTestFramework: '#setup: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-07-18 20:54:58 - DEBUG UnitTestFramework: '#setup ok: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-07-18 20:54:58 - DEBUG UnitTestFramework: '#run: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-07-18 20:54:59 - DEBUG UnitTestFramework: '#run ok: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-07-18 20:54:59 - DEBUG UnitTestFramework: '#teardown: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-07-18 20:55:01 - DEBUG UnitTestFramework: '#teardown ok: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-07-18 20:55:01 - DEBUG UnitTestFramework: '#setup: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-07-18 20:55:02 - DEBUG UnitTestFramework: '#setup ok: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-07-18 20:55:02 - DEBUG UnitTestFramework: '#run: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-07-18 20:55:04 - DEBUG UnitTestFramework: '#run ok: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-07-18 20:55:04 - DEBUG UnitTestFramework: '#teardown: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-07-18 20:55:05 - DEBUG UnitTestFramework: '#teardown ok: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-07-18 20:55:05 - DEBUG UnitTestFramework: '#setup: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-18 20:55:07 - DEBUG UnitTestFramework: '#setup ok: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-18 20:55:07 - DEBUG UnitTestFramework: '#run: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-18 20:55:07 - INFO Socket: 'run skipped, test: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection', event: 'run_We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-18 20:55:08 - INFO Socket: 'run skipped, test: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection', event: 'run_We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-18 20:55:09 - INFO Socket: 'run skipped, test: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection', event: 'run_We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-18 20:55:09 - DEBUG UnitTestFramework: '#run ok: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-18 20:55:09 - DEBUG UnitTestFramework: '#teardown: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-18 20:55:13 - DEBUG UnitTestFramework: '#teardown ok: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-18 20:55:13 - DEBUG UnitTestFramework: '#setup: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-18 20:55:15 - DEBUG UnitTestFramework: '#setup ok: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-18 20:55:15 - DEBUG UnitTestFramework: '#run: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-18 20:55:16 - INFO Socket: 'run skipped, test: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection', event: 'run_We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-18 20:55:16 - INFO Socket: 'run skipped, test: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection', event: 'run_We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-18 20:55:18 - INFO Socket: 'run skipped, test: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection', event: 'run_We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-18 20:55:18 - DEBUG UnitTestFramework: '#run ok: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-18 20:55:18 - DEBUG UnitTestFramework: '#teardown: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-18 20:55:18 - DEBUG UnitTestFramework: '#teardown ok: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-18 20:55:18 - DEBUG UnitTestFramework: '#setup: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved''

2017-07-18 20:55:21 - DEBUG UnitTestFramework: '#setup ok: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved''

2017-07-18 20:55:21 - DEBUG UnitTestFramework: '#run: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved''

2017-07-18 20:55:21 - DEBUG UnitTestFramework: '#run ok: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved''

2017-07-18 20:55:21 - DEBUG UnitTestFramework: '#teardown: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved''

2017-07-18 20:55:24 - DEBUG UnitTestFramework: '#teardown ok: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved''

2017-07-18 20:55:24 - DEBUG UnitTestFramework: '#setup: 'make sure bad PSK connections fail''

2017-07-18 20:55:27 - DEBUG UnitTestFramework: '#setup ok: 'make sure bad PSK connections fail''

2017-07-18 20:55:27 - DEBUG UnitTestFramework: '#run: 'make sure bad PSK connections fail''

2017-07-18 20:55:27 - INFO Socket: 'run skipped, test: 'make sure bad PSK connections fail', event: 'run_make sure bad PSK connections fail''

2017-07-18 20:55:27 - INFO Socket: 'run skipped, test: 'make sure bad PSK connections fail', event: 'run_make sure bad PSK connections fail''

2017-07-18 20:55:28 - INFO Socket: 'run skipped, test: 'make sure bad PSK connections fail', event: 'run_make sure bad PSK connections fail''

2017-07-18 20:55:28 - DEBUG UnitTestFramework: '#run ok: 'make sure bad PSK connections fail''

2017-07-18 20:55:28 - DEBUG UnitTestFramework: '#teardown: 'make sure bad PSK connections fail''

2017-07-18 20:55:30 - DEBUG UnitTestFramework: '#teardown ok: 'make sure bad PSK connections fail''

2017-07-18 20:55:30 - DEBUG UnitTestFramework: '#setup: 'peer changes handled from a queue''

2017-07-18 20:55:33 - DEBUG UnitTestFramework: '#setup ok: 'peer changes handled from a queue''

2017-07-18 20:55:33 - DEBUG UnitTestFramework: '#run: 'peer changes handled from a queue''

2017-07-18 20:55:33 - INFO Socket: 'run skipped, test: 'peer changes handled from a queue', event: 'run_peer changes handled from a queue''

2017-07-18 20:55:33 - INFO Socket: 'run skipped, test: 'peer changes handled from a queue', event: 'run_peer changes handled from a queue''

2017-07-18 20:55:34 - INFO Socket: 'run skipped, test: 'peer changes handled from a queue', event: 'run_peer changes handled from a queue''

2017-07-18 20:55:34 - DEBUG UnitTestFramework: '#run ok: 'peer changes handled from a queue''

2017-07-18 20:55:34 - DEBUG UnitTestFramework: '#teardown: 'peer changes handled from a queue''

2017-07-18 20:55:36 - DEBUG UnitTestFramework: '#teardown ok: 'peer changes handled from a queue''

2017-07-18 20:55:36 - DEBUG UnitTestFramework: '#setup: 'relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-18 20:55:39 - DEBUG UnitTestFramework: '#setup ok: 'relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-18 20:55:39 - DEBUG UnitTestFramework: '#run: 'relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-18 20:55:40 - INFO Socket: 'run skipped, test: 'relaying discoveryAdvertisingStateUpdateNonTCP', event: 'run_relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-18 20:55:43 - INFO Socket: 'run skipped, test: 'relaying discoveryAdvertisingStateUpdateNonTCP', event: 'run_relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-18 20:55:43 - INFO Socket: 'run skipped, test: 'relaying discoveryAdvertisingStateUpdateNonTCP', event: 'run_relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-18 20:55:43 - DEBUG UnitTestFramework: '#run ok: 'relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-18 20:55:43 - DEBUG UnitTestFramework: '#teardown: 'relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-18 20:55:46 - DEBUG UnitTestFramework: '#teardown ok: 'relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-18 20:55:46 - DEBUG UnitTestFramework: '#setup: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-18 20:55:47 - DEBUG UnitTestFramework: '#setup ok: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-18 20:55:47 - DEBUG UnitTestFramework: '#run: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-18 20:55:47 - INFO Socket: 'run skipped, test: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received', event: 'run_thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-18 20:55:48 - INFO Socket: 'run skipped, test: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received', event: 'run_thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-18 20:55:49 - INFO Socket: 'run skipped, test: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received', event: 'run_thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-18 20:55:49 - DEBUG UnitTestFramework: '#run ok: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-18 20:55:49 - DEBUG UnitTestFramework: '#teardown: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-18 20:55:51 - DEBUG UnitTestFramework: '#teardown ok: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-18 20:55:51 - DEBUG UnitTestFramework: '#setup: 'we successfully receive and replay discoveryAdvertisingStateUpdate''

2017-07-18 20:55:53 - DEBUG UnitTestFramework: '#setup ok: 'we successfully receive and replay discoveryAdvertisingStateUpdate''

2017-07-18 20:55:53 - DEBUG UnitTestFramework: '#run: 'we successfully receive and replay discoveryAdvertisingStateUpdate''

2017-07-18 20:55:58 - DEBUG UnitTestFramework: '#run ok: 'we successfully receive and replay discoveryAdvertisingStateUpdate''

2017-07-18 20:55:58 - DEBUG UnitTestFramework: '#teardown: 'we successfully receive and replay discoveryAdvertisingStateUpdate''

2017-07-18 20:55:59 - DEBUG UnitTestFramework: '#teardown ok: 'we successfully receive and replay discoveryAdvertisingStateUpdate''

2017-07-18 20:55:59 - DEBUG UnitTestFramework: '#setup: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-07-18 20:56:02 - DEBUG UnitTestFramework: '#setup ok: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-07-18 20:56:02 - DEBUG UnitTestFramework: '#run: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-07-18 20:56:02 - INFO Socket: 'run skipped, test: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS', event: 'run_nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-07-18 20:56:02 - INFO Socket: 'run skipped, test: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS', event: 'run_nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-07-18 20:56:03 - INFO Socket: 'run skipped, test: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS', event: 'run_nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-07-18 20:56:03 - DEBUG UnitTestFramework: '#run ok: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''
2017-07-18 20:56:03 - DEBUG UnitTestFramework: '#teardown: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-07-18 20:56:06 - DEBUG UnitTestFramework: '#teardown ok: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-07-18 20:56:06 - DEBUG UnitTestFramework: '#setup: 'can do HTTP requests between peers''

2017-07-18 20:56:08 - DEBUG UnitTestFramework: '#setup ok: 'can do HTTP requests between peers''

2017-07-18 20:56:08 - DEBUG UnitTestFramework: '#run: 'can do HTTP requests between peers''

2017-07-18 20:56:08 - INFO Socket: 'run skipped, test: 'can do HTTP requests between peers', event: 'run_can do HTTP requests between peers''

2017-07-18 20:56:08 - INFO Socket: 'run skipped, test: 'can do HTTP requests between peers', event: 'run_can do HTTP requests between peers''

2017-07-18 20:56:09 - INFO Socket: 'run skipped, test: 'can do HTTP requests between peers', event: 'run_can do HTTP requests between peers''

2017-07-18 20:56:09 - DEBUG UnitTestFramework: '#run ok: 'can do HTTP requests between peers''

2017-07-18 20:56:09 - DEBUG UnitTestFramework: '#teardown: 'can do HTTP requests between peers''

2017-07-18 20:56:13 - DEBUG UnitTestFramework: '#teardown ok: 'can do HTTP requests between peers''

2017-07-18 20:56:13 - DEBUG UnitTestFramework: '#setup: 'can still do HTTP requests between peers with coordinator''

2017-07-18 20:56:15 - DEBUG UnitTestFramework: '#setup ok: 'can still do HTTP requests between peers with coordinator''

2017-07-18 20:56:15 - DEBUG UnitTestFramework: '#run: 'can still do HTTP requests between peers with coordinator''

2017-07-18 20:56:16 - INFO Socket: 'run skipped, test: 'can still do HTTP requests between peers with coordinator', event: 'run_can still do HTTP requests between peers with coordinator''

2017-07-18 20:56:16 - INFO Socket: 'run skipped, test: 'can still do HTTP requests between peers with coordinator', event: 'run_can still do HTTP requests between peers with coordinator''

2017-07-18 20:56:18 - INFO Socket: 'run skipped, test: 'can still do HTTP requests between peers with coordinator', event: 'run_can still do HTTP requests between peers with coordinator''

2017-07-18 20:56:18 - DEBUG UnitTestFramework: '#run ok: 'can still do HTTP requests between peers with coordinator''

2017-07-18 20:56:18 - DEBUG UnitTestFramework: '#teardown: 'can still do HTTP requests between peers with coordinator''

2017-07-18 20:56:20 - DEBUG UnitTestFramework: '#teardown ok: 'can still do HTTP requests between peers with coordinator''

2017-07-18 20:56:20 - DEBUG UnitTestFramework: '#setup: 'calls correct starts when network changes''

2017-07-18 20:56:22 - DEBUG UnitTestFramework: '#setup ok: 'calls correct starts when network changes''

2017-07-18 20:56:22 - DEBUG UnitTestFramework: '#run: 'calls correct starts when network changes''

2017-07-18 20:56:22 - INFO Socket: 'run skipped, test: 'calls correct starts when network changes', event: 'run_calls correct starts when network changes''

2017-07-18 20:56:22 - INFO Socket: 'run skipped, test: 'calls correct starts when network changes', event: 'run_calls correct starts when network changes''

2017-07-18 20:56:24 - INFO Socket: 'run skipped, test: 'calls correct starts when network changes', event: 'run_calls correct starts when network changes''

2017-07-18 20:56:24 - DEBUG UnitTestFramework: '#run ok: 'calls correct starts when network changes''

2017-07-18 20:56:24 - DEBUG UnitTestFramework: '#teardown: 'calls correct starts when network changes''

2017-07-18 20:56:25 - DEBUG UnitTestFramework: '#teardown ok: 'calls correct starts when network changes''

2017-07-18 20:56:25 - DEBUG UnitTestFramework: '#setup: 'test to coordinate connection cut''

2017-07-18 20:56:28 - DEBUG UnitTestFramework: '#setup ok: 'test to coordinate connection cut''

2017-07-18 20:56:28 - DEBUG UnitTestFramework: '#run: 'test to coordinate connection cut''

2017-07-18 20:56:30 - DEBUG UnitTestFramework: '#run ok: 'test to coordinate connection cut''

2017-07-18 20:56:30 - DEBUG UnitTestFramework: '#teardown: 'test to coordinate connection cut''

2017-07-18 20:56:31 - DEBUG UnitTestFramework: '#teardown ok: 'test to coordinate connection cut''

2017-07-18 20:56:31 - DEBUG UnitTestFramework: '#setup: 'can do HTTP requests after connections are cut''

2017-07-18 20:56:34 - DEBUG UnitTestFramework: '#setup ok: 'can do HTTP requests after connections are cut''

2017-07-18 20:56:34 - DEBUG UnitTestFramework: '#run: 'can do HTTP requests after connections are cut''

2017-07-18 20:56:45 - DEBUG UnitTestFramework: '#run ok: 'can do HTTP requests after connections are cut''

2017-07-18 20:56:45 - DEBUG UnitTestFramework: '#teardown: 'can do HTTP requests after connections are cut''

2017-07-18 20:56:48 - DEBUG UnitTestFramework: '#teardown ok: 'can do HTTP requests after connections are cut''

2017-07-18 20:56:48 - DEBUG UnitTestFramework: '#setup: 'will fail bad PSK connection between peers''

2017-07-18 20:56:50 - DEBUG UnitTestFramework: '#setup ok: 'will fail bad PSK connection between peers''

2017-07-18 20:56:50 - DEBUG UnitTestFramework: '#run: 'will fail bad PSK connection between peers''

2017-07-18 20:56:52 - DEBUG UnitTestFramework: '#run ok: 'will fail bad PSK connection between peers''

2017-07-18 20:56:52 - DEBUG UnitTestFramework: '#teardown: 'will fail bad PSK connection between peers''

2017-07-18 20:56:54 - DEBUG UnitTestFramework: '#teardown ok: 'will fail bad PSK connection between peers''

2017-07-18 20:56:54 - DEBUG UnitTestFramework: '#setup: 'We provide notification when a listener dies and we recreate it''

2017-07-18 20:56:56 - DEBUG UnitTestFramework: '#setup ok: 'We provide notification when a listener dies and we recreate it''

2017-07-18 20:56:56 - DEBUG UnitTestFramework: '#run: 'We provide notification when a listener dies and we recreate it''

2017-07-18 20:56:56 - INFO Socket: 'run skipped, test: 'We provide notification when a listener dies and we recreate it', event: 'run_We provide notification when a listener dies and we recreate it''

2017-07-18 20:56:56 - INFO Socket: 'run skipped, test: 'We provide notification when a listener dies and we recreate it', event: 'run_We provide notification when a listener dies and we recreate it''

2017-07-18 20:56:58 - INFO Socket: 'run skipped, test: 'We provide notification when a listener dies and we recreate it', event: 'run_We provide notification when a listener dies and we recreate it''

2017-07-18 20:56:58 - DEBUG UnitTestFramework: '#run ok: 'We provide notification when a listener dies and we recreate it''

2017-07-18 20:56:58 - DEBUG UnitTestFramework: '#teardown: 'We provide notification when a listener dies and we recreate it''

2017-07-18 20:56:59 - DEBUG UnitTestFramework: '#teardown ok: 'We provide notification when a listener dies and we recreate it''

2017-07-18 20:56:59 - DEBUG UnitTestFramework: '#setup: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''

2017-07-18 20:57:01 - DEBUG UnitTestFramework: '#setup ok: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''

2017-07-18 20:57:01 - DEBUG UnitTestFramework: '#run: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''

2017-07-18 20:57:01 - INFO Socket: 'run skipped, test: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated', event: 'run_We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''

2017-07-18 20:57:02 - INFO Socket: 'run skipped, test: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated', event: 'run_We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''

2017-07-18 20:57:04 - INFO Socket: 'run skipped, test: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated', event: 'run_We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''

2017-07-18 20:57:04 - DEBUG UnitTestFramework: '#run ok: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''

2017-07-18 20:57:04 - DEBUG UnitTestFramework: '#teardown: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''

2017-07-18 20:57:05 - DEBUG UnitTestFramework: '#teardown ok: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''

2017-07-18 20:57:05 - DEBUG UnitTestFramework: '#setup: '#startListeningForAdvertisements should fail if start not called''

2017-07-18 20:57:07 - DEBUG UnitTestFramework: '#setup ok: '#startListeningForAdvertisements should fail if start not called''

2017-07-18 20:57:07 - DEBUG UnitTestFramework: '#run: '#startListeningForAdvertisements should fail if start not called''

2017-07-18 20:57:10 - DEBUG UnitTestFramework: '#run ok: '#startListeningForAdvertisements should fail if start not called''

2017-07-18 20:57:10 - DEBUG UnitTestFramework: '#teardown: '#startListeningForAdvertisements should fail if start not called''

2017-07-18 20:57:12 - DEBUG UnitTestFramework: '#teardown ok: '#startListeningForAdvertisements should fail if start not called''

2017-07-18 20:57:12 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-18 20:57:14 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-18 20:57:14 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-18 20:57:15 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-18 20:57:15 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-18 20:57:17 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-18 20:57:17 - DEBUG UnitTestFramework: '#setup: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-18 20:57:20 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-18 20:57:20 - DEBUG UnitTestFramework: '#run: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-18 20:57:22 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-18 20:57:22 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-18 20:57:23 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-18 20:57:23 - DEBUG UnitTestFramework: '#setup: 'should be able to call #startListeningForAdvertisements many times''

2017-07-18 20:57:24 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #startListeningForAdvertisements many times''

2017-07-18 20:57:24 - DEBUG UnitTestFramework: '#run: 'should be able to call #startListeningForAdvertisements many times''

2017-07-18 20:57:27 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #startListeningForAdvertisements many times''

2017-07-18 20:57:27 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #startListeningForAdvertisements many times''

2017-07-18 20:57:28 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #startListeningForAdvertisements many times''

2017-07-18 20:57:28 - DEBUG UnitTestFramework: '#setup: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-18 20:57:30 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #startUpdateAdvertisingAndListening many times''
2017-07-18 20:57:30 - DEBUG UnitTestFramework: '#run: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-18 20:57:34 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-18 20:57:34 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-18 20:57:35 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-18 20:57:35 - DEBUG UnitTestFramework: '#setup: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-18 20:57:37 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-18 20:57:37 - DEBUG UnitTestFramework: '#run: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-18 20:57:39 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-18 20:57:39 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-18 20:57:43 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-18 20:57:43 - DEBUG UnitTestFramework: '#setup: '#start - Causing native or wifi to fail will cause a promise reject ''

2017-07-18 20:57:45 - DEBUG UnitTestFramework: '#setup ok: '#start - Causing native or wifi to fail will cause a promise reject ''

2017-07-18 20:57:45 - DEBUG UnitTestFramework: '#run: '#start - Causing native or wifi to fail will cause a promise reject ''

2017-07-18 20:57:48 - DEBUG UnitTestFramework: '#run ok: '#start - Causing native or wifi to fail will cause a promise reject ''

2017-07-18 20:57:48 - DEBUG UnitTestFramework: '#teardown: '#start - Causing native or wifi to fail will cause a promise reject ''

2017-07-18 20:57:49 - DEBUG UnitTestFramework: '#teardown ok: '#start - Causing native or wifi to fail will cause a promise reject ''

2017-07-18 20:57:49 - DEBUG UnitTestFramework: '#setup: '#start should fail if called twice in a row''

2017-07-18 20:57:51 - DEBUG UnitTestFramework: '#setup ok: '#start should fail if called twice in a row''

2017-07-18 20:57:51 - DEBUG UnitTestFramework: '#run: '#start should fail if called twice in a row''

2017-07-18 20:57:54 - DEBUG UnitTestFramework: '#run ok: '#start should fail if called twice in a row''

2017-07-18 20:57:54 - DEBUG UnitTestFramework: '#teardown: '#start should fail if called twice in a row''

2017-07-18 20:57:55 - DEBUG UnitTestFramework: '#teardown ok: '#start should fail if called twice in a row''

2017-07-18 20:57:55 - DEBUG UnitTestFramework: '#setup: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-07-18 20:57:57 - DEBUG UnitTestFramework: '#setup ok: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-07-18 20:57:57 - DEBUG UnitTestFramework: '#run: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-07-18 20:57:57 - INFO Socket: 'run skipped, test: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)', event: 'run_#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-07-18 20:57:58 - INFO Socket: 'run skipped, test: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)', event: 'run_#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-07-18 20:57:59 - INFO Socket: 'run skipped, test: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)', event: 'run_#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-07-18 20:57:59 - DEBUG UnitTestFramework: '#run ok: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-07-18 20:57:59 - DEBUG UnitTestFramework: '#teardown: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-07-18 20:58:01 - DEBUG UnitTestFramework: '#teardown ok: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-07-18 20:58:01 - DEBUG UnitTestFramework: '#setup: 'does not emit duplicate discoveryAdvertisingStateUpdate''

2017-07-18 20:58:03 - DEBUG UnitTestFramework: '#setup ok: 'does not emit duplicate discoveryAdvertisingStateUpdate''

2017-07-18 20:58:03 - DEBUG UnitTestFramework: '#run: 'does not emit duplicate discoveryAdvertisingStateUpdate''

2017-07-18 20:58:03 - INFO Socket: 'run skipped, test: 'does not emit duplicate discoveryAdvertisingStateUpdate', event: 'run_does not emit duplicate discoveryAdvertisingStateUpdate''

2017-07-18 20:58:04 - INFO Socket: 'run skipped, test: 'does not emit duplicate discoveryAdvertisingStateUpdate', event: 'run_does not emit duplicate discoveryAdvertisingStateUpdate''

2017-07-18 20:58:05 - INFO Socket: 'run skipped, test: 'does not emit duplicate discoveryAdvertisingStateUpdate', event: 'run_does not emit duplicate discoveryAdvertisingStateUpdate''

2017-07-18 20:58:05 - DEBUG UnitTestFramework: '#run ok: 'does not emit duplicate discoveryAdvertisingStateUpdate''

2017-07-18 20:58:05 - DEBUG UnitTestFramework: '#teardown: 'does not emit duplicate discoveryAdvertisingStateUpdate''

2017-07-18 20:58:07 - DEBUG UnitTestFramework: '#teardown ok: 'does not emit duplicate discoveryAdvertisingStateUpdate''

2017-07-18 20:58:07 - DEBUG UnitTestFramework: '#setup: 'does not send duplicate availability changes''

2017-07-18 20:58:09 - DEBUG UnitTestFramework: '#setup ok: 'does not send duplicate availability changes''

2017-07-18 20:58:09 - DEBUG UnitTestFramework: '#run: 'does not send duplicate availability changes''

2017-07-18 20:58:11 - DEBUG UnitTestFramework: '#run ok: 'does not send duplicate availability changes''

2017-07-18 20:58:11 - DEBUG UnitTestFramework: '#teardown: 'does not send duplicate availability changes''

2017-07-18 20:58:13 - DEBUG UnitTestFramework: '#teardown ok: 'does not send duplicate availability changes''

2017-07-18 20:58:13 - DEBUG UnitTestFramework: '#setup: 'can get the network status''

2017-07-18 20:58:15 - DEBUG UnitTestFramework: '#setup ok: 'can get the network status''

2017-07-18 20:58:15 - DEBUG UnitTestFramework: '#run: 'can get the network status''

2017-07-18 20:58:16 - DEBUG UnitTestFramework: '#run ok: 'can get the network status''

2017-07-18 20:58:16 - DEBUG UnitTestFramework: '#teardown: 'can get the network status''

2017-07-18 20:58:18 - DEBUG UnitTestFramework: '#teardown ok: 'can get the network status''

2017-07-18 20:58:18 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChanged - peer added/removed to/from cache (native)''

2017-07-18 20:58:19 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChanged - peer added/removed to/from cache (native)''

2017-07-18 20:58:19 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChanged - peer added/removed to/from cache (native)''

2017-07-18 20:58:21 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChanged - peer added/removed to/from cache (native)''

2017-07-18 20:58:21 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChanged - peer added/removed to/from cache (native)''

2017-07-18 20:58:24 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChanged - peer added/removed to/from cache (native)''

2017-07-18 20:58:24 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChanged - peer added/removed to/from cache (wifi)''

2017-07-18 20:58:25 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChanged - peer added/removed to/from cache (wifi)''

2017-07-18 20:58:25 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChanged - peer added/removed to/from cache (wifi)''

2017-07-18 20:58:27 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChanged - peer added/removed to/from cache (wifi)''

2017-07-18 20:58:27 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChanged - peer added/removed to/from cache (wifi)''

2017-07-18 20:58:30 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChanged - peer added/removed to/from cache (wifi)''

2017-07-18 20:58:30 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored''

2017-07-18 20:58:31 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored''

2017-07-18 20:58:31 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored''

2017-07-18 20:58:33 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored''

2017-07-18 20:58:33 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored''

2017-07-18 20:58:35 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored''

2017-07-18 20:58:35 - DEBUG UnitTestFramework: '#setup: 'native available - new peer is cached''

2017-07-18 20:58:37 - DEBUG UnitTestFramework: '#setup ok: 'native available - new peer is cached''

2017-07-18 20:58:37 - DEBUG UnitTestFramework: '#run: 'native available - new peer is cached''

2017-07-18 20:58:39 - DEBUG UnitTestFramework: '#run ok: 'native available - new peer is cached''

2017-07-18 20:58:39 - DEBUG UnitTestFramework: '#teardown: 'native available - new peer is cached''

2017-07-18 20:58:43 - DEBUG UnitTestFramework: '#teardown ok: 'native available - new peer is cached''

2017-07-18 20:58:43 - DEBUG UnitTestFramework: '#setup: 'native available - peer with same port and different generation is cached (BLUETOOTH)''

2017-07-18 20:58:45 - DEBUG UnitTestFramework: '#setup ok: 'native available - peer with same port and different generation is cached (BLUETOOTH)''

2017-07-18 20:58:45 - DEBUG UnitTestFramework: '#run: 'native available - peer with same port and different generation is cached (BLUETOOTH)''

2017-07-18 20:58:48 - DEBUG UnitTestFramework: '#run ok: 'native available - peer with same port and different generation is cached (BLUETOOTH)''

2017-07-18 20:58:48 - DEBUG UnitTestFramework: '#teardown: 'native available - peer with same port and different generation is cached (BLUETOOTH)''

2017-07-18 20:58:49 - DEBUG UnitTestFramework: '#teardown ok: 'native available - peer with same port and different generation is cached (BLUETOOTH)''

2017-07-18 20:58:49 - DEBUG UnitTestFramework: '#setup: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''

2017-07-18 20:58:52 - DEBUG UnitTestFramework: '#setup ok: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''

2017-07-18 20:58:52 - DEBUG UnitTestFramework: '#run: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''

2017-07-18 20:58:54 - DEBUG UnitTestFramework: '#run ok: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''

2017-07-18 20:58:54 - DEBUG UnitTestFramework: '#teardown: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''

2017-07-18 20:58:55 - DEBUG UnitTestFramework: '#teardown ok: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''

2017-07-18 20:58:55 - DEBUG UnitTestFramework: '#setup: 'native available - peer with greater generation is cached (MPCF)''

2017-07-18 20:58:58 - DEBUG UnitTestFramework: '#setup ok: 'native available - peer with greater generation is cached (MPCF)''

2017-07-18 20:58:58 - DEBUG UnitTestFramework: '#run: 'native available - peer with greater generation is cached (MPCF)''

2017-07-18 20:58:58 - INFO Socket: 'run skipped, test: 'native available - peer with greater generation is cached (MPCF)', event: 'run_native available - peer with greater generation is cached (MPCF)''

2017-07-18 20:58:58 - INFO Socket: 'run skipped, test: 'native available - peer with greater generation is cached (MPCF)', event: 'run_native available - peer with greater generation is cached (MPCF)''

2017-07-18 20:59:00 - INFO Socket: 'run skipped, test: 'native available - peer with greater generation is cached (MPCF)', event: 'run_native available - peer with greater generation is cached (MPCF)''

2017-07-18 20:59:00 - DEBUG UnitTestFramework: '#run ok: 'native available - peer with greater generation is cached (MPCF)''

2017-07-18 20:59:00 - DEBUG UnitTestFramework: '#teardown: 'native available - peer with greater generation is cached (MPCF)''

2017-07-18 20:59:01 - DEBUG UnitTestFramework: '#teardown ok: 'native available - peer with greater generation is cached (MPCF)''

2017-07-18 20:59:01 - DEBUG UnitTestFramework: '#setup: 'native available - peer with same or older generation is ignored (MPCF)''

2017-07-18 20:59:04 - DEBUG UnitTestFramework: '#setup ok: 'native available - peer with same or older generation is ignored (MPCF)''

2017-07-18 20:59:04 - DEBUG UnitTestFramework: '#run: 'native available - peer with same or older generation is ignored (MPCF)''

2017-07-18 20:59:04 - INFO Socket: 'run skipped, test: 'native available - peer with same or older generation is ignored (MPCF)', event: 'run_native available - peer with same or older generation is ignored (MPCF)''

2017-07-18 20:59:04 - INFO Socket: 'run skipped, test: 'native available - peer with same or older generation is ignored (MPCF)', event: 'run_native available - peer with same or older generation is ignored (MPCF)''

2017-07-18 20:59:06 - INFO Socket: 'run skipped, test: 'native available - peer with same or older generation is ignored (MPCF)', event: 'run_native available - peer with same or older generation is ignored (MPCF)''

2017-07-18 20:59:06 - DEBUG UnitTestFramework: '#run ok: 'native available - peer with same or older generation is ignored (MPCF)''

2017-07-18 20:59:06 - DEBUG UnitTestFramework: '#teardown: 'native available - peer with same or older generation is ignored (MPCF)''

2017-07-18 20:59:09 - DEBUG UnitTestFramework: '#teardown ok: 'native available - peer with same or older generation is ignored (MPCF)''

2017-07-18 20:59:09 - DEBUG UnitTestFramework: '#setup: 'native unavailable - new peer is ignored''

2017-07-18 20:59:13 - DEBUG UnitTestFramework: '#setup ok: 'native unavailable - new peer is ignored''

2017-07-18 20:59:13 - DEBUG UnitTestFramework: '#run: 'native unavailable - new peer is ignored''

2017-07-18 20:59:14 - DEBUG UnitTestFramework: '#run ok: 'native unavailable - new peer is ignored''

2017-07-18 20:59:14 - DEBUG UnitTestFramework: '#teardown: 'native unavailable - new peer is ignored''

2017-07-18 20:59:16 - DEBUG UnitTestFramework: '#teardown ok: 'native unavailable - new peer is ignored''

2017-07-18 20:59:16 - DEBUG UnitTestFramework: '#setup: 'native unavailable - cached peer is removed''

2017-07-18 20:59:18 - DEBUG UnitTestFramework: '#setup ok: 'native unavailable - cached peer is removed''

2017-07-18 20:59:18 - DEBUG UnitTestFramework: '#run: 'native unavailable - cached peer is removed''

2017-07-18 20:59:20 - DEBUG UnitTestFramework: '#run ok: 'native unavailable - cached peer is removed''

2017-07-18 20:59:20 - DEBUG UnitTestFramework: '#teardown: 'native unavailable - cached peer is removed''

2017-07-18 20:59:22 - DEBUG UnitTestFramework: '#teardown ok: 'native unavailable - cached peer is removed''

2017-07-18 20:59:22 - DEBUG UnitTestFramework: '#setup: 'networkChanged - fires peerAvailabilityChanged event for wifi peers''

2017-07-18 20:59:24 - DEBUG UnitTestFramework: '#setup ok: 'networkChanged - fires peerAvailabilityChanged event for wifi peers''

2017-07-18 20:59:24 - DEBUG UnitTestFramework: '#run: 'networkChanged - fires peerAvailabilityChanged event for wifi peers''

2017-07-18 20:59:26 - DEBUG UnitTestFramework: '#run ok: 'networkChanged - fires peerAvailabilityChanged event for wifi peers''

2017-07-18 20:59:26 - DEBUG UnitTestFramework: '#teardown: 'networkChanged - fires peerAvailabilityChanged event for wifi peers''

2017-07-18 20:59:28 - DEBUG UnitTestFramework: '#teardown ok: 'networkChanged - fires peerAvailabilityChanged event for wifi peers''

2017-07-18 20:59:28 - DEBUG UnitTestFramework: '#setup: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''

2017-07-18 20:59:29 - DEBUG UnitTestFramework: '#setup ok: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''

2017-07-18 20:59:29 - DEBUG UnitTestFramework: '#run: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''

2017-07-18 20:59:32 - DEBUG UnitTestFramework: '#run ok: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''

2017-07-18 20:59:32 - DEBUG UnitTestFramework: '#teardown: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''

2017-07-18 20:59:34 - DEBUG UnitTestFramework: '#teardown ok: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''

2017-07-18 20:59:34 - DEBUG UnitTestFramework: '#setup: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''

2017-07-18 20:59:35 - DEBUG UnitTestFramework: '#setup ok: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''

2017-07-18 20:59:35 - DEBUG UnitTestFramework: '#run: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''

2017-07-18 20:59:35 - INFO Socket: 'run skipped, test: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)', event: 'run_networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''

2017-07-18 20:59:38 - INFO Socket: 'run skipped, test: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)', event: 'run_networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''

2017-07-18 20:59:38 - INFO Socket: 'run skipped, test: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)', event: 'run_networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''

2017-07-18 20:59:38 - DEBUG UnitTestFramework: '#run ok: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''

2017-07-18 20:59:38 - DEBUG UnitTestFramework: '#teardown: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''

2017-07-18 20:59:43 - DEBUG UnitTestFramework: '#teardown ok: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''

2017-07-18 20:59:43 - DEBUG UnitTestFramework: '#setup: 'multiconnect failure - new peer is ignored (MPCF)''

2017-07-18 20:59:45 - DEBUG UnitTestFramework: '#setup ok: 'multiconnect failure - new peer is ignored (MPCF)''

2017-07-18 20:59:45 - DEBUG UnitTestFramework: '#run: 'multiconnect failure - new peer is ignored (MPCF)''

2017-07-18 20:59:45 - INFO Socket: 'run skipped, test: 'multiconnect failure - new peer is ignored (MPCF)', event: 'run_multiconnect failure - new peer is ignored (MPCF)''

2017-07-18 20:59:46 - INFO Socket: 'run skipped, test: 'multiconnect failure - new peer is ignored (MPCF)', event: 'run_multiconnect failure - new peer is ignored (MPCF)''

2017-07-18 20:59:48 - INFO Socket: 'run skipped, test: 'multiconnect failure - new peer is ignored (MPCF)', event: 'run_multiconnect failure - new peer is ignored (MPCF)''

2017-07-18 20:59:48 - DEBUG UnitTestFramework: '#run ok: 'multiconnect failure - new peer is ignored (MPCF)''

2017-07-18 20:59:48 - DEBUG UnitTestFramework: '#teardown: 'multiconnect failure - new peer is ignored (MPCF)''

2017-07-18 20:59:49 - DEBUG UnitTestFramework: '#teardown ok: 'multiconnect failure - new peer is ignored (MPCF)''

2017-07-18 20:59:49 - DEBUG UnitTestFramework: '#setup: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-07-18 20:59:51 - DEBUG UnitTestFramework: '#setup ok: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-07-18 20:59:51 - DEBUG UnitTestFramework: '#run: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-07-18 20:59:51 - INFO Socket: 'run skipped, test: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)', event: 'run_multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-07-18 20:59:52 - INFO Socket: 'run skipped, test: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)', event: 'run_multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-07-18 20:59:53 - INFO Socket: 'run skipped, test: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)', event: 'run_multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-07-18 20:59:53 - DEBUG UnitTestFramework: '#run ok: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-07-18 20:59:53 - DEBUG UnitTestFramework: '#teardown: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-07-18 20:59:54 - DEBUG UnitTestFramework: '#teardown ok: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-07-18 20:59:54 - DEBUG UnitTestFramework: '#setup: 'newAddressPort field (TCP_NATIVE)''

2017-07-18 20:59:57 - DEBUG UnitTestFramework: '#setup ok: 'newAddressPort field (TCP_NATIVE)''

2017-07-18 20:59:57 - DEBUG UnitTestFramework: '#run: 'newAddressPort field (TCP_NATIVE)''

2017-07-18 20:59:58 - DEBUG UnitTestFramework: '#run ok: 'newAddressPort field (TCP_NATIVE)''

2017-07-18 20:59:58 - DEBUG UnitTestFramework: '#teardown: 'newAddressPort field (TCP_NATIVE)''

2017-07-18 21:00:00 - DEBUG UnitTestFramework: '#teardown ok: 'newAddressPort field (TCP_NATIVE)''

2017-07-18 21:00:00 - DEBUG UnitTestFramework: '#setup: 'newAddressPort field (BLUETOOTH)''

2017-07-18 21:00:03 - DEBUG UnitTestFramework: '#setup ok: 'newAddressPort field (BLUETOOTH)''

2017-07-18 21:00:03 - DEBUG UnitTestFramework: '#run: 'newAddressPort field (BLUETOOTH)''

2017-07-18 21:00:04 - DEBUG UnitTestFramework: '#run ok: 'newAddressPort field (BLUETOOTH)''

2017-07-18 21:00:04 - DEBUG UnitTestFramework: '#teardown: 'newAddressPort field (BLUETOOTH)''

2017-07-18 21:00:07 - DEBUG UnitTestFramework: '#teardown ok: 'newAddressPort field (BLUETOOTH)''

2017-07-18 21:00:07 - DEBUG UnitTestFramework: '#setup: 'newAddressPort field (MPCF)''

2017-07-18 21:00:09 - DEBUG UnitTestFramework: '#setup ok: 'newAddressPort field (MPCF)''

2017-07-18 21:00:09 - DEBUG UnitTestFramework: '#run: 'newAddressPort field (MPCF)''

2017-07-18 21:00:09 - INFO Socket: 'run skipped, test: 'newAddressPort field (MPCF)', event: 'run_newAddressPort field (MPCF)''

2017-07-18 21:00:10 - INFO Socket: 'run skipped, test: 'newAddressPort field (MPCF)', event: 'run_newAddressPort field (MPCF)''

2017-07-18 21:00:13 - INFO Socket: 'run skipped, test: 'newAddressPort field (MPCF)', event: 'run_newAddressPort field (MPCF)''

2017-07-18 21:00:13 - DEBUG UnitTestFramework: '#run ok: 'newAddressPort field (MPCF)''

2017-07-18 21:00:13 - DEBUG UnitTestFramework: '#teardown: 'newAddressPort field (MPCF)''

2017-07-18 21:00:15 - DEBUG UnitTestFramework: '#teardown ok: 'newAddressPort field (MPCF)''

2017-07-18 21:00:15 - DEBUG UnitTestFramework: '#setup: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''

2017-07-18 21:00:16 - DEBUG UnitTestFramework: '#setup ok: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''

2017-07-18 21:00:16 - DEBUG UnitTestFramework: '#run: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''

2017-07-18 21:00:18 - DEBUG UnitTestFramework: '#run ok: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''

2017-07-18 21:00:18 - DEBUG UnitTestFramework: '#teardown: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''

2017-07-18 21:00:19 - DEBUG UnitTestFramework: '#teardown ok: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''

2017-07-18 21:00:19 - DEBUG UnitTestFramework: '#setup: '#getPeerHostInfo - error when peer has not been discovered yet''

2017-07-18 21:00:22 - DEBUG UnitTestFramework: '#setup ok: '#getPeerHostInfo - error when peer has not been discovered yet''

2017-07-18 21:00:22 - DEBUG UnitTestFramework: '#run: '#getPeerHostInfo - error when peer has not been discovered yet''

2017-07-18 21:00:24 - DEBUG UnitTestFramework: '#run ok: '#getPeerHostInfo - error when peer has not been discovered yet''

2017-07-18 21:00:24 - DEBUG UnitTestFramework: '#teardown: '#getPeerHostInfo - error when peer has not been discovered yet''

2017-07-18 21:00:25 - DEBUG UnitTestFramework: '#teardown ok: '#getPeerHostInfo - error when peer has not been discovered yet''

2017-07-18 21:00:25 - DEBUG UnitTestFramework: '#setup: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''

2017-07-18 21:00:27 - DEBUG UnitTestFramework: '#setup ok: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''

2017-07-18 21:00:27 - DEBUG UnitTestFramework: '#run: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''

2017-07-18 21:00:29 - DEBUG UnitTestFramework: '#run ok: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''

2017-07-18 21:00:29 - DEBUG UnitTestFramework: '#teardown: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''

2017-07-18 21:00:31 - DEBUG UnitTestFramework: '#teardown ok: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''

2017-07-18 21:00:31 - DEBUG UnitTestFramework: '#setup: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''

2017-07-18 21:00:32 - DEBUG UnitTestFramework: '#setup ok: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''

2017-07-18 21:00:32 - DEBUG UnitTestFramework: '#run: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''

2017-07-18 21:00:32 - INFO Socket: 'run skipped, test: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)', event: 'run_#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''

2017-07-18 21:00:34 - INFO Socket: 'run skipped, test: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)', event: 'run_#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''

2017-07-18 21:00:34 - INFO Socket: 'run skipped, test: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)', event: 'run_#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''

2017-07-18 21:00:34 - DEBUG UnitTestFramework: '#run ok: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''

2017-07-18 21:00:34 - DEBUG UnitTestFramework: '#teardown: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''

2017-07-18 21:00:35 - DEBUG UnitTestFramework: '#teardown ok: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''

2017-07-18 21:00:35 - DEBUG UnitTestFramework: '#setup: '#getPeerHostInfo - returns discovered cached wifi peer''

2017-07-18 21:00:37 - DEBUG UnitTestFramework: '#setup ok: '#getPeerHostInfo - returns discovered cached wifi peer''

2017-07-18 21:00:37 - DEBUG UnitTestFramework: '#run: '#getPeerHostInfo - returns discovered cached wifi peer''

2017-07-18 21:00:39 - DEBUG UnitTestFramework: '#run ok: '#getPeerHostInfo - returns discovered cached wifi peer''

2017-07-18 21:00:39 - DEBUG UnitTestFramework: '#teardown: '#getPeerHostInfo - returns discovered cached wifi peer''

2017-07-18 21:00:43 - DEBUG UnitTestFramework: '#teardown ok: '#getPeerHostInfo - returns discovered cached wifi peer''

2017-07-18 21:00:43 - DEBUG UnitTestFramework: '#setup: '#disconnect fails on wifi peers''

2017-07-18 21:00:45 - DEBUG UnitTestFramework: '#setup ok: '#disconnect fails on wifi peers''

2017-07-18 21:00:45 - DEBUG UnitTestFramework: '#run: '#disconnect fails on wifi peers''

2017-07-18 21:00:47 - DEBUG UnitTestFramework: '#run ok: '#disconnect fails on wifi peers''

2017-07-18 21:00:47 - DEBUG UnitTestFramework: '#teardown: '#disconnect fails on wifi peers''

2017-07-18 21:00:48 - DEBUG UnitTestFramework: '#teardown ok: '#disconnect fails on wifi peers''

2017-07-18 21:00:48 - DEBUG UnitTestFramework: '#setup: '#disconnect delegates native peers to the native wrapper''

2017-07-18 21:00:51 - DEBUG UnitTestFramework: '#setup ok: '#disconnect delegates native peers to the native wrapper''

2017-07-18 21:00:51 - DEBUG UnitTestFramework: '#run: '#disconnect delegates native peers to the native wrapper''

2017-07-18 21:00:53 - DEBUG UnitTestFramework: '#run ok: '#disconnect delegates native peers to the native wrapper''

2017-07-18 21:00:53 - DEBUG UnitTestFramework: '#teardown: '#disconnect delegates native peers to the native wrapper''

2017-07-18 21:00:54 - DEBUG UnitTestFramework: '#teardown ok: '#disconnect delegates native peers to the native wrapper''

2017-07-18 21:00:54 - DEBUG UnitTestFramework: '#setup: 'network changes emitted correctly''

2017-07-18 21:00:56 - DEBUG UnitTestFramework: '#setup ok: 'network changes emitted correctly''

2017-07-18 21:00:56 - DEBUG UnitTestFramework: '#run: 'network changes emitted correctly''

2017-07-18 21:00:56 - INFO Socket: 'run skipped, test: 'network changes emitted correctly', event: 'run_network changes emitted correctly''

2017-07-18 21:00:57 - INFO Socket: 'run skipped, test: 'network changes emitted correctly', event: 'run_network changes emitted correctly''

2017-07-18 21:00:58 - INFO Socket: 'run skipped, test: 'network changes emitted correctly', event: 'run_network changes emitted correctly''

2017-07-18 21:00:58 - DEBUG UnitTestFramework: '#run ok: 'network changes emitted correctly''

2017-07-18 21:00:58 - DEBUG UnitTestFramework: '#teardown: 'network changes emitted correctly''

2017-07-18 21:01:00 - DEBUG UnitTestFramework: '#teardown ok: 'network changes emitted correctly''

2017-07-18 21:01:00 - DEBUG UnitTestFramework: '#setup: 'network changes not emitted in started state''

2017-07-18 21:01:02 - DEBUG UnitTestFramework: '#setup ok: 'network changes not emitted in started state''

2017-07-18 21:01:02 - DEBUG UnitTestFramework: '#run: 'network changes not emitted in started state''

2017-07-18 21:01:02 - INFO Socket: 'run skipped, test: 'network changes not emitted in started state', event: 'run_network changes not emitted in started state''

2017-07-18 21:01:03 - INFO Socket: 'run skipped, test: 'network changes not emitted in started state', event: 'run_network changes not emitted in started state''

2017-07-18 21:01:04 - INFO Socket: 'run skipped, test: 'network changes not emitted in started state', event: 'run_network changes not emitted in started state''

2017-07-18 21:01:04 - DEBUG UnitTestFramework: '#run ok: 'network changes not emitted in started state''

2017-07-18 21:01:04 - DEBUG UnitTestFramework: '#teardown: 'network changes not emitted in started state''

2017-07-18 21:01:06 - DEBUG UnitTestFramework: '#teardown ok: 'network changes not emitted in started state''

2017-07-18 21:01:06 - DEBUG UnitTestFramework: '#setup: 'network changes not emitted in stopped state''

2017-07-18 21:01:08 - DEBUG UnitTestFramework: '#setup ok: 'network changes not emitted in stopped state''

2017-07-18 21:01:08 - DEBUG UnitTestFramework: '#run: 'network changes not emitted in stopped state''

2017-07-18 21:01:08 - INFO Socket: 'run skipped, test: 'network changes not emitted in stopped state', event: 'run_network changes not emitted in stopped state''

2017-07-18 21:01:08 - INFO Socket: 'run skipped, test: 'network changes not emitted in stopped state', event: 'run_network changes not emitted in stopped state''

2017-07-18 21:01:09 - INFO Socket: 'run skipped, test: 'network changes not emitted in stopped state', event: 'run_network changes not emitted in stopped state''

2017-07-18 21:01:09 - DEBUG UnitTestFramework: '#run ok: 'network changes not emitted in stopped state''

2017-07-18 21:01:09 - DEBUG UnitTestFramework: '#teardown: 'network changes not emitted in stopped state''

2017-07-18 21:01:13 - DEBUG UnitTestFramework: '#teardown ok: 'network changes not emitted in stopped state''

2017-07-18 21:01:13 - DEBUG UnitTestFramework: '#setup: 'We properly fire peer unavailable and then available when connection fails on Android''

2017-07-18 21:01:15 - DEBUG UnitTestFramework: '#setup ok: 'We properly fire peer unavailable and then available when connection fails on Android''

2017-07-18 21:01:15 - DEBUG UnitTestFramework: '#run: 'We properly fire peer unavailable and then available when connection fails on Android''

2017-07-18 21:01:17 - DEBUG UnitTestFramework: '#run ok: 'We properly fire peer unavailable and then available when connection fails on Android''

2017-07-18 21:01:17 - DEBUG UnitTestFramework: '#teardown: 'We properly fire peer unavailable and then available when connection fails on Android''

2017-07-18 21:01:18 - DEBUG UnitTestFramework: '#teardown ok: 'We properly fire peer unavailable and then available when connection fails on Android''

2017-07-18 21:01:18 - DEBUG UnitTestFramework: '#setup: 'We properly fire peer unavailable and then available when connection fails on iOS''

2017-07-18 21:01:20 - DEBUG UnitTestFramework: '#setup ok: 'We properly fire peer unavailable and then available when connection fails on iOS''

2017-07-18 21:01:20 - DEBUG UnitTestFramework: '#run: 'We properly fire peer unavailable and then available when connection fails on iOS''

2017-07-18 21:01:20 - INFO Socket: 'run skipped, test: 'We properly fire peer unavailable and then available when connection fails on iOS', event: 'run_We properly fire peer unavailable and then available when connection fails on iOS''

2017-07-18 21:01:22 - INFO Socket: 'run skipped, test: 'We properly fire peer unavailable and then available when connection fails on iOS', event: 'run_We properly fire peer unavailable and then available when connection fails on iOS''

2017-07-18 21:01:23 - INFO Socket: 'run skipped, test: 'We properly fire peer unavailable and then available when connection fails on iOS', event: 'run_We properly fire peer unavailable and then available when connection fails on iOS''

2017-07-18 21:01:23 - DEBUG UnitTestFramework: '#run ok: 'We properly fire peer unavailable and then available when connection fails on iOS''

2017-07-18 21:01:23 - DEBUG UnitTestFramework: '#teardown: 'We properly fire peer unavailable and then available when connection fails on iOS''

2017-07-18 21:01:26 - DEBUG UnitTestFramework: '#teardown ok: 'We properly fire peer unavailable and then available when connection fails on iOS''

2017-07-18 21:01:26 - DEBUG UnitTestFramework: '#setup: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''

2017-07-18 21:01:29 - DEBUG UnitTestFramework: '#setup ok: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''

2017-07-18 21:01:29 - DEBUG UnitTestFramework: '#run: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''

2017-07-18 21:01:33 - DEBUG UnitTestFramework: '#run ok: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''

2017-07-18 21:01:33 - DEBUG UnitTestFramework: '#teardown: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''

2017-07-18 21:01:36 - DEBUG UnitTestFramework: '#teardown ok: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''

2017-07-18 21:01:36 - DEBUG UnitTestFramework: '#setup: 'does not fire duplicate events after peer listener recreation''

2017-07-18 21:01:38 - DEBUG UnitTestFramework: '#setup ok: 'does not fire duplicate events after peer listener recreation''

2017-07-18 21:01:38 - DEBUG UnitTestFramework: '#run: 'does not fire duplicate events after peer listener recreation''

2017-07-18 21:01:39 - DEBUG UnitTestFramework: '#run ok: 'does not fire duplicate events after peer listener recreation''

2017-07-18 21:01:39 - DEBUG UnitTestFramework: '#teardown: 'does not fire duplicate events after peer listener recreation''

2017-07-18 21:01:43 - DEBUG UnitTestFramework: '#teardown ok: 'does not fire duplicate events after peer listener recreation''

2017-07-18 21:01:43 - DEBUG UnitTestFramework: '#setup: '#stop should change peers''

2017-07-18 21:01:44 - DEBUG UnitTestFramework: '#setup ok: '#stop should change peers''

2017-07-18 21:01:44 - DEBUG UnitTestFramework: '#run: '#stop should change peers''

2017-07-18 21:01:48 - DEBUG UnitTestFramework: '#run ok: '#stop should change peers''

2017-07-18 21:01:48 - DEBUG UnitTestFramework: '#teardown: '#stop should change peers''

2017-07-18 21:01:50 - DEBUG UnitTestFramework: '#teardown ok: '#stop should change peers''

2017-07-18 21:01:50 - DEBUG UnitTestFramework: '#setup: 'If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted''

2017-07-18 21:01:51 - DEBUG UnitTestFramework: '#setup ok: 'If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted''

2017-07-18 21:01:51 - DEBUG UnitTestFramework: '#run: 'If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted''

2017-07-18 21:01:54 - DEBUG UnitTestFramework: '#run ok: 'If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted''

2017-07-18 21:01:54 - DEBUG UnitTestFramework: '#teardown: 'If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted''

2017-07-18 21:01:55 - DEBUG UnitTestFramework: '#teardown ok: 'If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted''

2017-07-18 21:01:55 - DEBUG UnitTestFramework: '#setup: 'peer should be found once after listening and discovery started''

2017-07-18 21:01:57 - DEBUG UnitTestFramework: '#setup ok: 'peer should be found once after listening and discovery started''

2017-07-18 21:01:57 - DEBUG UnitTestFramework: '#run: 'peer should be found once after listening and discovery started''

2017-07-18 21:01:57 - INFO Socket: 'run skipped, test: 'peer should be found once after listening and discovery started', event: 'run_peer should be found once after listening and discovery started''

2017-07-18 21:01:58 - INFO Socket: 'run skipped, test: 'peer should be found once after listening and discovery started', event: 'run_peer should be found once after listening and discovery started''

2017-07-18 21:01:59 - INFO Socket: 'run skipped, test: 'peer should be found once after listening and discovery started', event: 'run_peer should be found once after listening and discovery started''

2017-07-18 21:01:59 - DEBUG UnitTestFramework: '#run ok: 'peer should be found once after listening and discovery started''

2017-07-18 21:01:59 - DEBUG UnitTestFramework: '#teardown: 'peer should be found once after listening and discovery started''

2017-07-18 21:02:01 - DEBUG UnitTestFramework: '#teardown ok: 'peer should be found once after listening and discovery started''

2017-07-18 21:02:01 - DEBUG UnitTestFramework: '#setup: 'can get data from all participants''

2017-07-18 21:02:03 - DEBUG UnitTestFramework: '#setup ok: 'can get data from all participants''

2017-07-18 21:02:03 - DEBUG UnitTestFramework: '#run: 'can get data from all participants''

2017-07-18 21:03:11 - DEBUG UnitTestFramework: '#run ok: 'can get data from all participants''

2017-07-18 21:03:11 - DEBUG UnitTestFramework: '#teardown: 'can get data from all participants''

2017-07-18 21:03:12 - DEBUG UnitTestFramework: '#teardown ok: 'can get data from all participants''

2017-07-18 21:03:12 - DEBUG UnitTestFramework: '#setup: 'test for data corruption''

2017-07-18 21:03:14 - DEBUG UnitTestFramework: '#setup ok: 'test for data corruption''

2017-07-18 21:03:14 - DEBUG UnitTestFramework: '#run: 'test for data corruption''

2017-07-18 21:03:14 - INFO Socket: 'run skipped, test: 'test for data corruption', event: 'run_test for data corruption''

2017-07-18 21:03:15 - INFO Socket: 'run skipped, test: 'test for data corruption', event: 'run_test for data corruption''

2017-07-18 21:03:15 - INFO Socket: 'run skipped, test: 'test for data corruption', event: 'run_test for data corruption''

2017-07-18 21:03:15 - DEBUG UnitTestFramework: '#run ok: 'test for data corruption''

2017-07-18 21:03:15 - DEBUG UnitTestFramework: '#teardown: 'test for data corruption''

2017-07-18 21:03:17 - DEBUG UnitTestFramework: '#teardown ok: 'test for data corruption''

2017-07-18 21:03:17 - DEBUG UnitTestFramework: '#setup: '#testThaliPeerAction - test getters''

2017-07-18 21:03:19 - DEBUG UnitTestFramework: '#setup ok: '#testThaliPeerAction - test getters''

2017-07-18 21:03:19 - DEBUG UnitTestFramework: '#run: '#testThaliPeerAction - test getters''

2017-07-18 21:03:21 - DEBUG UnitTestFramework: '#run ok: '#testThaliPeerAction - test getters''

2017-07-18 21:03:21 - DEBUG UnitTestFramework: '#teardown: '#testThaliPeerAction - test getters''

2017-07-18 21:03:23 - DEBUG UnitTestFramework: '#teardown ok: '#testThaliPeerAction - test getters''

2017-07-18 21:03:23 - DEBUG UnitTestFramework: '#setup: '#testThaliPeerAction - start and kill''

2017-07-18 21:03:25 - DEBUG UnitTestFramework: '#setup ok: '#testThaliPeerAction - start and kill''

2017-07-18 21:03:25 - DEBUG UnitTestFramework: '#run: '#testThaliPeerAction - start and kill''

2017-07-18 21:03:26 - DEBUG UnitTestFramework: '#run ok: '#testThaliPeerAction - start and kill''

2017-07-18 21:03:26 - DEBUG UnitTestFramework: '#teardown: '#testThaliPeerAction - start and kill''

2017-07-18 21:03:28 - DEBUG UnitTestFramework: '#teardown ok: '#testThaliPeerAction - start and kill''

2017-07-18 21:03:28 - DEBUG UnitTestFramework: '#setup: '#testThaliPeerAction - double start''

2017-07-18 21:03:31 - DEBUG UnitTestFramework: '#setup ok: '#testThaliPeerAction - double start''

2017-07-18 21:03:31 - DEBUG UnitTestFramework: '#run: '#testThaliPeerAction - double start''

2017-07-18 21:03:32 - DEBUG UnitTestFramework: '#run ok: '#testThaliPeerAction - double start''

2017-07-18 21:03:32 - DEBUG UnitTestFramework: '#teardown: '#testThaliPeerAction - double start''

2017-07-18 21:03:34 - DEBUG UnitTestFramework: '#teardown ok: '#testThaliPeerAction - double start''

2017-07-18 21:03:34 - DEBUG UnitTestFramework: '#setup: '#testThaliPeerAction - start after kill''

2017-07-18 21:03:35 - DEBUG UnitTestFramework: '#setup ok: '#testThaliPeerAction - start after kill''

2017-07-18 21:03:35 - DEBUG UnitTestFramework: '#run: '#testThaliPeerAction - start after kill''

2017-07-18 21:03:39 - DEBUG UnitTestFramework: '#run ok: '#testThaliPeerAction - start after kill''

2017-07-18 21:03:39 - DEBUG UnitTestFramework: '#teardown: '#testThaliPeerAction - start after kill''

2017-07-18 21:03:43 - DEBUG UnitTestFramework: '#teardown ok: '#testThaliPeerAction - start after kill''

2017-07-18 21:03:43 - DEBUG UnitTestFramework: '#setup: '#testThaliPeerAction - make sure ids are unique''

2017-07-18 21:03:46 - DEBUG UnitTestFramework: '#setup ok: '#testThaliPeerAction - make sure ids are unique''

2017-07-18 21:03:46 - DEBUG UnitTestFramework: '#run: '#testThaliPeerAction - make sure ids are unique''

2017-07-18 21:03:49 - DEBUG UnitTestFramework: '#run ok: '#testThaliPeerAction - make sure ids are unique''

2017-07-18 21:03:49 - DEBUG UnitTestFramework: '#teardown: '#testThaliPeerAction - make sure ids are unique''

2017-07-18 21:03:52 - DEBUG UnitTestFramework: '#teardown ok: '#testThaliPeerAction - make sure ids are unique''

2017-07-18 21:03:52 - DEBUG UnitTestFramework: '#setup: '#testThaliPeerAction - check that forever agent can be destroyed''

2017-07-18 21:03:55 - DEBUG UnitTestFramework: '#setup ok: '#testThaliPeerAction - check that forever agent can be destroyed''

2017-07-18 21:03:55 - DEBUG UnitTestFramework: '#run: '#testThaliPeerAction - check that forever agent can be destroyed''

2017-07-18 21:03:58 - DEBUG UnitTestFramework: '#run ok: '#testThaliPeerAction - check that forever agent can be destroyed''

2017-07-18 21:03:58 - DEBUG UnitTestFramework: '#teardown: '#testThaliPeerAction - check that forever agent can be destroyed''

2017-07-18 21:04:01 - DEBUG UnitTestFramework: '#teardown ok: '#testThaliPeerAction - check that forever agent can be destroyed''

2017-07-18 21:04:01 - DEBUG UnitTestFramework: '#setup: 'Test PeerDictionary basic functionality''

2017-07-18 21:04:04 - DEBUG UnitTestFramework: '#setup ok: 'Test PeerDictionary basic functionality''

2017-07-18 21:04:04 - DEBUG UnitTestFramework: '#run: 'Test PeerDictionary basic functionality''

2017-07-18 21:04:06 - DEBUG UnitTestFramework: '#run ok: 'Test PeerDictionary basic functionality''

2017-07-18 21:04:06 - DEBUG UnitTestFramework: '#teardown: 'Test PeerDictionary basic functionality''

2017-07-18 21:04:09 - DEBUG UnitTestFramework: '#teardown ok: 'Test PeerDictionary basic functionality''

2017-07-18 21:04:09 - DEBUG UnitTestFramework: '#setup: 'Test PeerDictionary with multiple entries.''

2017-07-18 21:04:13 - DEBUG UnitTestFramework: '#setup ok: 'Test PeerDictionary with multiple entries.''

2017-07-18 21:04:13 - DEBUG UnitTestFramework: '#run: 'Test PeerDictionary with multiple entries.''

2017-07-18 21:04:17 - DEBUG UnitTestFramework: '#run ok: 'Test PeerDictionary with multiple entries.''

2017-07-18 21:04:17 - DEBUG UnitTestFramework: '#teardown: 'Test PeerDictionary with multiple entries.''

2017-07-18 21:04:19 - DEBUG UnitTestFramework: '#teardown ok: 'Test PeerDictionary with multiple entries.''

2017-07-18 21:04:19 - DEBUG UnitTestFramework: '#setup: 'RESOLVED entries are removed before WAITING state entry.''

2017-07-18 21:04:22 - DEBUG UnitTestFramework: '#setup ok: 'RESOLVED entries are removed before WAITING state entry.''

2017-07-18 21:04:22 - DEBUG UnitTestFramework: '#run: 'RESOLVED entries are removed before WAITING state entry.''

2017-07-18 21:04:23 - DEBUG UnitTestFramework: '#run ok: 'RESOLVED entries are removed before WAITING state entry.''

2017-07-18 21:04:23 - DEBUG UnitTestFramework: '#teardown: 'RESOLVED entries are removed before WAITING state entry.''

2017-07-18 21:04:25 - DEBUG UnitTestFramework: '#teardown ok: 'RESOLVED entries are removed before WAITING state entry.''

2017-07-18 21:04:25 - DEBUG UnitTestFramework: '#setup: 'WAITING entries are removed before CONTROLLED_BY_POOL state entry.''

2017-07-18 21:04:26 - DEBUG UnitTestFramework: '#setup ok: 'WAITING entries are removed before CONTROLLED_BY_POOL state entry.''

2017-07-18 21:04:26 - DEBUG UnitTestFramework: '#run: 'WAITING entries are removed before CONTROLLED_BY_POOL state entry.''

2017-07-18 21:04:29 - DEBUG UnitTestFramework: '#run ok: 'WAITING entries are removed before CONTROLLED_BY_POOL state entry.''

2017-07-18 21:04:29 - DEBUG UnitTestFramework: '#teardown: 'WAITING entries are removed before CONTROLLED_BY_POOL state entry.''

2017-07-18 21:04:31 - DEBUG UnitTestFramework: '#teardown ok: 'WAITING entries are removed before CONTROLLED_BY_POOL state entry.''

2017-07-18 21:04:31 - DEBUG UnitTestFramework: '#setup: 'When CONTROLLED_BY_POOL entry is removed and kill is called.''

2017-07-18 21:04:32 - DEBUG UnitTestFramework: '#setup ok: 'When CONTROLLED_BY_POOL entry is removed and kill is called.''

2017-07-18 21:04:32 - DEBUG UnitTestFramework: '#run: 'When CONTROLLED_BY_POOL entry is removed and kill is called.''

2017-07-18 21:04:35 - DEBUG UnitTestFramework: '#run ok: 'When CONTROLLED_BY_POOL entry is removed and kill is called.''

2017-07-18 21:04:35 - DEBUG UnitTestFramework: '#teardown: 'When CONTROLLED_BY_POOL entry is removed and kill is called.''

2017-07-18 21:04:35 - DEBUG UnitTestFramework: '#teardown ok: 'When CONTROLLED_BY_POOL entry is removed and kill is called.''

2017-07-18 21:04:35 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolDefault - single action''

2017-07-18 21:04:38 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolDefault - single action''

2017-07-18 21:04:38 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolDefault - single action''

2017-07-18 21:04:40 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolDefault - single action''

2017-07-18 21:04:40 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolDefault - single action''

2017-07-18 21:04:43 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolDefault - single action''

2017-07-18 21:04:43 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolDefault - multiple actions''

2017-07-18 21:04:43 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolDefault - multiple actions''

2017-07-18 21:04:43 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolDefault - multiple actions''

2017-07-18 21:04:46 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolDefault - multiple actions''

2017-07-18 21:04:46 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolDefault - multiple actions''

2017-07-18 21:04:46 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolDefault - multiple actions''

2017-07-18 21:04:46 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolDefault - PSK Pool works''

2017-07-18 21:04:49 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolDefault - PSK Pool works''

2017-07-18 21:04:49 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolDefault - PSK Pool works''

2017-07-18 21:04:49 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolDefault - PSK Pool works''

2017-07-18 21:04:49 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolDefault - PSK Pool works''

2017-07-18 21:04:52 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolDefault - PSK Pool works''

2017-07-18 21:04:52 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolDefault - stop''

2017-07-18 21:04:52 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolDefault - stop''

2017-07-18 21:04:52 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolDefault - stop''

2017-07-18 21:04:54 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolDefault - stop''

2017-07-18 21:04:54 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolDefault - stop''

2017-07-18 21:04:55 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolDefault - stop''

2017-07-18 21:04:55 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolInterface - make sure that start verifies queue length''

2017-07-18 21:04:57 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolInterface - make sure that start verifies queue length''

2017-07-18 21:04:57 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolInterface - make sure that start verifies queue length''

2017-07-18 21:04:58 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolInterface - make sure that start verifies queue length''

2017-07-18 21:04:58 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolInterface - make sure that start verifies queue length''

2017-07-18 21:05:01 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolInterface - make sure that start verifies queue length''

2017-07-18 21:05:01 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolInterface - bad enqueues''

2017-07-18 21:05:03 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolInterface - bad enqueues''

2017-07-18 21:05:03 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolInterface - bad enqueues''

2017-07-18 21:05:06 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolInterface - bad enqueues''

2017-07-18 21:05:06 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolInterface - bad enqueues''

2017-07-18 21:05:09 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolInterface - bad enqueues''

2017-07-18 21:05:09 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolInterface - do not allow same object type''

2017-07-18 21:05:13 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolInterface - do not allow same object type''

2017-07-18 21:05:13 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolInterface - do not allow same object type''

2017-07-18 21:05:15 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolInterface - do not allow same object type''

2017-07-18 21:05:15 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolInterface - do not allow same object type''

2017-07-18 21:05:16 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolInterface - do not allow same object type''

2017-07-18 21:05:16 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolInterface - make sure we catch kill and dequeue''

2017-07-18 21:05:18 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolInterface - make sure we catch kill and dequeue''

2017-07-18 21:05:18 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolInterface - make sure we catch kill and dequeue''

2017-07-18 21:05:19 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolInterface - make sure we catch kill and dequeue''

2017-07-18 21:05:19 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolInterface - make sure we catch kill and dequeue''

2017-07-18 21:05:21 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolInterface - make sure we catch kill and dequeue''

2017-07-18 21:05:21 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent''

2017-07-18 21:05:24 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent''

2017-07-18 21:05:24 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent''

2017-07-18 21:05:25 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent''

2017-07-18 21:05:25 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent''

2017-07-18 21:05:27 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent''

2017-07-18 21:05:27 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolInterface - make sure that stop removes all actions''

2017-07-18 21:05:28 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolInterface - make sure that stop removes all actions''

2017-07-18 21:05:28 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolInterface - make sure that stop removes all actions''

2017-07-18 21:05:30 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolInterface - make sure that stop removes all actions''

2017-07-18 21:05:30 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolInterface - make sure that stop removes all actions''

2017-07-18 21:05:31 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolInterface - make sure that stop removes all actions''

2017-07-18 21:05:31 - DEBUG UnitTestFramework: '#setup: 'We reject unrecognized connection type''

2017-07-18 21:05:33 - DEBUG UnitTestFramework: '#setup ok: 'We reject unrecognized connection type''

2017-07-18 21:05:33 - DEBUG UnitTestFramework: '#run: 'We reject unrecognized connection type''

2017-07-18 21:05:34 - DEBUG UnitTestFramework: '#run ok: 'We reject unrecognized connection type''

2017-07-18 21:05:34 - DEBUG UnitTestFramework: '#teardown: 'We reject unrecognized connection type''

2017-07-18 21:05:37 - DEBUG UnitTestFramework: '#teardown ok: 'We reject unrecognized connection type''

2017-07-18 21:05:37 - DEBUG UnitTestFramework: '#setup: 'We reject unrecognized action type''

2017-07-18 21:05:39 - DEBUG UnitTestFramework: '#setup ok: 'We reject unrecognized action type''

2017-07-18 21:05:39 - DEBUG UnitTestFramework: '#run: 'We reject unrecognized action type''

2017-07-18 21:05:43 - DEBUG UnitTestFramework: '#run ok: 'We reject unrecognized action type''

2017-07-18 21:05:43 - DEBUG UnitTestFramework: '#teardown: 'We reject unrecognized action type''

2017-07-18 21:05:45 - DEBUG UnitTestFramework: '#teardown ok: 'We reject unrecognized action type''

2017-07-18 21:05:45 - DEBUG UnitTestFramework: '#setup: 'One action on bluetooth''

2017-07-18 21:05:47 - DEBUG UnitTestFramework: '#setup ok: 'One action on bluetooth''

2017-07-18 21:05:47 - DEBUG UnitTestFramework: '#run: 'One action on bluetooth''

2017-07-18 21:05:49 - DEBUG UnitTestFramework: '#run ok: 'One action on bluetooth''

2017-07-18 21:05:49 - DEBUG UnitTestFramework: '#teardown: 'One action on bluetooth''

2017-07-18 21:05:51 - DEBUG UnitTestFramework: '#teardown ok: 'One action on bluetooth''

2017-07-18 21:05:51 - DEBUG UnitTestFramework: '#setup: 'Two notification actions''

2017-07-18 21:05:53 - DEBUG UnitTestFramework: '#setup ok: 'Two notification actions''

2017-07-18 21:05:53 - DEBUG UnitTestFramework: '#run: 'Two notification actions''

2017-07-18 21:05:55 - DEBUG UnitTestFramework: '#run ok: 'Two notification actions''

2017-07-18 21:05:55 - DEBUG UnitTestFramework: '#teardown: 'Two notification actions''

2017-07-18 21:05:56 - DEBUG UnitTestFramework: '#teardown ok: 'Two notification actions''

2017-07-18 21:05:56 - DEBUG UnitTestFramework: '#setup: 'replicateThroughProblems''

2017-07-18 21:05:58 - DEBUG UnitTestFramework: '#setup ok: 'replicateThroughProblems''

2017-07-18 21:05:58 - DEBUG UnitTestFramework: '#run: 'replicateThroughProblems''

2017-07-18 21:06:01 - DEBUG UnitTestFramework: '#run ok: 'replicateThroughProblems''

2017-07-18 21:06:01 - DEBUG UnitTestFramework: '#teardown: 'replicateThroughProblems''

2017-07-18 21:06:02 - DEBUG UnitTestFramework: '#teardown ok: 'replicateThroughProblems''

2017-07-18 21:06:02 - DEBUG UnitTestFramework: '#setup: 'Replication goes first''

2017-07-18 21:06:02 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'transport close''

2017-07-18 21:06:05 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'transport close''

2017-07-18 21:07:02 - ERROR UnitTestFramework: '#run failed: 'Replication goes first', error: 'TimeoutError: timeout exceeded, event: 'setup_Replication goes first_finished', test: 'Replication goes first'', stack: 'TimeoutError: timeout exceeded, event: 'setup_Replication goes first_finished', test: 'Replication goes first'
    at afterTimeout (/home/pi/Test/server_1133518512a72c5b/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_1133518512a72c5b/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-07-18 21:07:02 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'android', error: 'TimeoutError: timeout exceeded, event: 'setup_Replication goes first_finished', test: 'Replication goes first'', stack: 'TimeoutError: timeout exceeded, event: 'setup_Replication goes first_finished', test: 'Replication goes first'
    at afterTimeout (/home/pi/Test/server_1133518512a72c5b/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_1133518512a72c5b/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-07-18 21:07:38 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'transport close''

[0;31merror: command 'sudo jx ______.js android' failed with code 1, file 'bash' on line 30[0m
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

android : Error: Command failed: copying android script192.168.1.52
copying android script192.168.1.50
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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/1133518512a72c5b_CI_sanity_check_jareksl/thali01_samsung-SM-G935F.md)

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
Error! Unexpected exit on device ce061606c181d71003 app:com.thaliproject.thalitest code:0 
Child process exited with code 0 on device ce061606c181d71003
Android task is completed. [FAILED]
Stopping App:com.thaliproject.thalitest ce061606c181d71003 green
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/1133518512a72c5b_CI_sanity_check_jareksl/thali03_samsung-SM-G930F.md)

####Node name: thali04
Console output:
```
Stopping app on  ce0616068b9f212302
Stopping App:com.thaliproject.thalitest ce0616068b9f212302 green
Uninstalling app on  ce0616068b9f212302
Uninstalling App:com.thaliproject.thalitest ce0616068b9f212302 green
is Device booted ce0616068b9f212302 0 green
Checking:  adb -s ce0616068b9f212302 shell getprop sys.boot_completed green

All devices are ready!

Deploying to ce0616068b9f212302
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/1133518512a72c5b_CI_sanity_check_jareksl/thali04_samsung-SM-G930F.md)





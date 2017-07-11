#### Test 113351851fe156cf Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":4}}
2017-07-11 13:29:57 - INFO HttpServer: 'listening on *:3000'

2017-07-11 13:30:58 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'de738b71-8a4d-494a-a29e-8d3fa93e9827', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-11 13:30:58 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-07-11 13:31:03 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '6117f5b3-c5c2-4d3b-b9c2-e5a1a9d0d489', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-11 13:31:03 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-07-11 13:33:09 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '83cde4aa-82ae-4ae4-b100-c4aef94edcc0', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-11 13:33:09 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-07-11 13:33:11 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '5d19a28e-234e-4dc4-82c7-58d36904554d', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-11 13:33:11 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-07-11 13:33:11 - INFO TestFramework: 'all required 4 devices are present for platformName: 'android''

2017-07-11 13:33:11 - DEBUG UnitTestFramework: 'starting unit tests on 4 devices, platformName: 'android''

2017-07-11 13:33:11 - DEBUG UnitTestFramework: 'scheduling tests'

2017-07-11 13:33:12 - DEBUG UnitTestFramework: 'tests scheduled'

2017-07-11 13:33:12 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-07-11 13:33:12 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-07-11 13:33:12 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-07-11 13:33:12 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-07-11 13:33:12 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-07-11 13:33:12 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-07-11 13:33:12 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-07-11 13:33:12 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-07-11 13:33:12 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-07-11 13:33:14 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-07-11 13:33:14 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-07-11 13:33:14 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-07-11 13:33:14 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-11 13:33:14 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-11 13:33:14 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-11 13:33:15 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-11 13:33:15 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-11 13:33:15 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-11 13:33:15 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-11 13:33:15 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-11 13:33:15 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-11 13:33:15 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-11 13:33:15 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-11 13:33:15 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-11 13:33:15 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-07-11 13:33:15 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-11 13:33:15 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-07-11 13:33:15 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-11 13:33:15 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-11 13:33:15 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-11 13:33:15 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-11 13:33:15 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-11 13:33:15 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-07-11 13:33:15 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-11 13:33:15 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-11 13:33:15 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-11 13:33:15 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-11 13:33:15 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-11 13:33:15 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-11 13:33:15 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-11 13:33:15 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-11 13:33:15 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''
2017-07-11 13:33:15 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-11 13:33:15 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-11 13:33:15 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-11 13:33:15 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-11 13:33:15 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-11 13:33:15 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-11 13:33:15 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-11 13:33:16 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-11 13:33:16 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-11 13:33:16 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-11 13:33:16 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-11 13:33:16 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-11 13:33:16 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-11 13:33:16 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-11 13:33:16 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-11 13:33:16 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-11 13:33:16 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-11 13:33:16 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-11 13:33:16 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-11 13:33:16 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-11 13:33:16 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-11 13:33:16 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-11 13:33:16 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-07-11 13:33:16 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-07-11 13:33:16 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-07-11 13:33:16 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-07-11 13:33:16 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-07-11 13:33:16 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-07-11 13:33:16 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-07-11 13:33:16 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-07-11 13:33:16 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-07-11 13:33:16 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-07-11 13:33:16 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-07-11 13:33:16 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-07-11 13:33:16 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-07-11 13:33:16 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-07-11 13:33:16 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-07-11 13:33:16 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-07-11 13:33:16 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-07-11 13:33:16 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-07-11 13:33:16 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-07-11 13:33:16 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-07-11 13:33:16 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-07-11 13:33:16 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-07-11 13:33:16 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-07-11 13:33:17 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-07-11 13:33:17 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-07-11 13:33:17 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-07-11 13:33:17 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-07-11 13:33:17 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-07-11 13:33:17 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-07-11 13:33:17 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-07-11 13:33:17 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-07-11 13:33:17 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-07-11 13:33:17 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-07-11 13:33:17 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-07-11 13:33:17 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-07-11 13:33:17 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-07-11 13:33:17 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-07-11 13:33:17 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-07-11 13:33:17 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-07-11 13:33:17 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-07-11 13:33:17 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-07-11 13:33:17 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-07-11 13:33:17 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-07-11 13:33:17 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-07-11 13:33:17 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-07-11 13:33:17 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-07-11 13:33:17 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-07-11 13:33:17 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-07-11 13:33:17 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-07-11 13:33:17 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-07-11 13:33:17 - DEBUG UnitTestFramework: '#run: 'basic''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#setup: 'another''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#run: 'another''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#setup: 'skip''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#setup ok: 'skip''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#run: 'skip''

2017-07-11 13:33:18 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-07-11 13:33:18 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-07-11 13:33:18 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-07-11 13:33:18 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#run ok: 'skip''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#teardown: 'skip''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#teardown ok: 'skip''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#setup: 'another skip''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#setup ok: 'another skip''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#run: 'another skip''

2017-07-11 13:33:18 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-07-11 13:33:18 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''
2017-07-11 13:33:18 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-07-11 13:33:18 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#run ok: 'another skip''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#teardown: 'another skip''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#teardown ok: 'another skip''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox spy''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox spy''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox spy''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox spy''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox spy''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox spy''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub override''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub override''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub override''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub override''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub override''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub override''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox mock''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox mock''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox mock''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox mock''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox mock''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox mock''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox restore after test end''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox restore after test end''

2017-07-11 13:33:18 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox restore after test end''

2017-07-11 13:33:19 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox restore after test end''

2017-07-11 13:33:19 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox restore after test end''

2017-07-11 13:33:19 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox restore after test end''

2017-07-11 13:33:19 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-07-11 13:33:19 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-07-11 13:33:19 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-07-11 13:33:19 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-07-11 13:33:19 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-07-11 13:33:19 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-07-11 13:33:19 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-07-11 13:33:19 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-07-11 13:33:19 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-07-11 13:33:19 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-07-11 13:33:19 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-07-11 13:33:19 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-07-11 13:33:19 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-07-11 13:33:19 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-07-11 13:33:19 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-07-11 13:33:19 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-07-11 13:33:19 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-07-11 13:33:19 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-07-11 13:33:19 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-07-11 13:33:19 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-07-11 13:33:19 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-07-11 13:33:19 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-07-11 13:33:19 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-07-11 13:33:19 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-07-11 13:33:19 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-07-11 13:33:19 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-07-11 13:33:19 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-07-11 13:33:21 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-07-11 13:33:21 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-07-11 13:33:21 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-07-11 13:33:21 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-11 13:33:21 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-11 13:33:21 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-11 13:33:22 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-11 13:33:22 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-11 13:33:22 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-11 13:33:22 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-11 13:33:22 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-11 13:33:22 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-11 13:33:22 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-11 13:33:22 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-11 13:33:22 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-11 13:33:22 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-11 13:33:23 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-11 13:33:23 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-11 13:33:24 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-11 13:33:24 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-11 13:33:25 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-11 13:33:25 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-11 13:33:25 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-11 13:33:25 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-11 13:33:26 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-11 13:33:26 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-11 13:33:26 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-11 13:33:26 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-11 13:33:26 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-11 13:33:26 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-11 13:33:26 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-11 13:33:26 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-11 13:33:26 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-11 13:33:26 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-07-11 13:33:26 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-07-11 13:33:26 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-07-11 13:33:28 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-07-11 13:33:28 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-07-11 13:33:29 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-07-11 13:33:29 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-07-11 13:33:29 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-07-11 13:33:29 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-07-11 13:34:05 - DEBUG UnitTestFramework: '#run ok: 'Can connect to a remote peer''

2017-07-11 13:34:05 - DEBUG UnitTestFramework: '#teardown: 'Can connect to a remote peer''

2017-07-11 13:34:07 - DEBUG UnitTestFramework: '#teardown ok: 'Can connect to a remote peer''

2017-07-11 13:34:07 - DEBUG UnitTestFramework: '#setup: 'Can shift data''

2017-07-11 13:34:08 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data''

2017-07-11 13:34:08 - DEBUG UnitTestFramework: '#run: 'Can shift data''

2017-07-11 13:34:13 - DEBUG UnitTestFramework: '#run ok: 'Can shift data''

2017-07-11 13:34:13 - DEBUG UnitTestFramework: '#teardown: 'Can shift data''

2017-07-11 13:34:16 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data''

2017-07-11 13:34:16 - DEBUG UnitTestFramework: '#setup: 'Can shift data via parallel connections''

2017-07-11 13:34:16 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data via parallel connections''

2017-07-11 13:34:16 - DEBUG UnitTestFramework: '#run: 'Can shift data via parallel connections''

2017-07-11 13:34:16 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-07-11 13:34:17 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-07-11 13:34:17 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-07-11 13:34:17 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-07-11 13:34:17 - DEBUG UnitTestFramework: '#run ok: 'Can shift data via parallel connections''

2017-07-11 13:34:17 - DEBUG UnitTestFramework: '#teardown: 'Can shift data via parallel connections''

2017-07-11 13:34:17 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data via parallel connections''

2017-07-11 13:34:17 - DEBUG UnitTestFramework: '#setup: 'Can shift data securely''

2017-07-11 13:34:18 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data securely''

2017-07-11 13:34:18 - DEBUG UnitTestFramework: '#run: 'Can shift data securely''

2017-07-11 13:34:25 - DEBUG UnitTestFramework: '#run ok: 'Can shift data securely''

2017-07-11 13:34:25 - DEBUG UnitTestFramework: '#teardown: 'Can shift data securely''

2017-07-11 13:34:27 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data securely''

2017-07-11 13:34:27 - DEBUG UnitTestFramework: '#setup: 'Can shift large amounts of data''

2017-07-11 13:34:28 - DEBUG UnitTestFramework: '#setup ok: 'Can shift large amounts of data''

2017-07-11 13:34:28 - DEBUG UnitTestFramework: '#run: 'Can shift large amounts of data''

2017-07-11 13:34:44 - DEBUG UnitTestFramework: '#run ok: 'Can shift large amounts of data''

2017-07-11 13:34:44 - DEBUG UnitTestFramework: '#teardown: 'Can shift large amounts of data''

2017-07-11 13:34:45 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift large amounts of data''

2017-07-11 13:34:45 - DEBUG UnitTestFramework: '#setup: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-11 13:34:46 - DEBUG UnitTestFramework: '#setup ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-11 13:34:46 - DEBUG UnitTestFramework: '#run: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-11 13:34:53 - DEBUG UnitTestFramework: '#run ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-11 13:34:53 - DEBUG UnitTestFramework: '#teardown: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-11 13:34:54 - DEBUG UnitTestFramework: '#teardown ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-11 13:34:54 - DEBUG UnitTestFramework: '#setup: 'Test updating advertising and parallel data transfer''

2017-07-11 13:34:54 - DEBUG UnitTestFramework: '#setup ok: 'Test updating advertising and parallel data transfer''

2017-07-11 13:34:54 - DEBUG UnitTestFramework: '#run: 'Test updating advertising and parallel data transfer''

2017-07-11 13:34:54 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-07-11 13:34:54 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-07-11 13:34:54 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-07-11 13:34:54 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-07-11 13:34:54 - DEBUG UnitTestFramework: '#run ok: 'Test updating advertising and parallel data transfer''

2017-07-11 13:34:54 - DEBUG UnitTestFramework: '#teardown: 'Test updating advertising and parallel data transfer''

2017-07-11 13:34:54 - DEBUG UnitTestFramework: '#teardown ok: 'Test updating advertising and parallel data transfer''

2017-07-11 13:34:54 - DEBUG UnitTestFramework: '#setup: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-11 13:34:54 - DEBUG UnitTestFramework: '#setup ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-11 13:34:54 - DEBUG UnitTestFramework: '#run: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-11 13:34:56 - ERROR UnitTestFramework: '#run failed: 'discoveryAdvertisingStateUpdateNonTCP is called', error: 'Error: run failed, test: 'discoveryAdvertisingStateUpdateNonTCP is called', event: 'run_discoveryAdvertisingStateUpdateNonTCP is called', sent data: '[{"uuid":"de738b71-8a4d-494a-a29e-8d3fa93e9827"},{"uuid":"6117f5b3-c5c2-4d3b-b9c2-e5a1a9d0d489"},{"uuid":"83cde4aa-82ae-4ae4-b100-c4aef94edcc0"},{"uuid":"5d19a28e-234e-4dc4-82c7-58d36904554d"}]', received data: '{"success":false}'', stack: 'Error: run failed, test: 'discoveryAdvertisingStateUpdateNonTCP is called', event: 'run_discoveryAdvertisingStateUpdateNonTCP is called', sent data: '[{"uuid":"de738b71-8a4d-494a-a29e-8d3fa93e9827"},{"uuid":"6117f5b3-c5c2-4d3b-b9c2-e5a1a9d0d489"},{"uuid":"83cde4aa-82ae-4ae4-b100-c4aef94edcc0"},{"uuid":"5d19a28e-234e-4dc4-82c7-58d36904554d"}]', received data: '{"success":false}'
    at finishedHandler (/home/pi/Test/server_113351851fe156cf/test/TestServer/Socket.js:205:15)
    at Socket.<anonymous> (/home/pi/Test/server_113351851fe156cf/test/TestServer/Socket.js:238:9)
    at Socket.g (events.js:160:16)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_113351851fe156cf/test/TestServer/node_modules/socket.io/lib/socket.js:335:8)
    at Socket.onpacket (/home/pi/Test/server_113351851fe156cf/test/TestServer/node_modules/socket.io/lib/socket.js:295:12)
    at Client.ondecoded (/home/pi/Test/server_113351851fe156cf/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_113351851fe156cf/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_113351851fe156cf/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_113351851fe156cf/test/TestServer/node_modules/socket.io/lib/client.js:175:18)
    at Socket.emit (events.js:82:17)
    at Socket.onPacket (/home/pi/Test/server_113351851fe156cf/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/socket.js:101:14)
    at WebSocket.emit (events.js:82:17)
    at WebSocket.Transport.onPacket (/home/pi/Test/server_113351851fe156cf/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:104:8)
    at WebSocket.Transport.onData (/home/pi/Test/server_113351851fe156cf/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:115:8)
    at WebSocket.onData (/home/pi/Test/server_113351851fe156cf/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transports/websocket.js:76:30)
    at WebSocket.emit (events.js:85:17)''

2017-07-11 13:34:56 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'android', error: 'Error: run failed, test: 'discoveryAdvertisingStateUpdateNonTCP is called', event: 'run_discoveryAdvertisingStateUpdateNonTCP is called', sent data: '[{"uuid":"de738b71-8a4d-494a-a29e-8d3fa93e9827"},{"uuid":"6117f5b3-c5c2-4d3b-b9c2-e5a1a9d0d489"},{"uuid":"83cde4aa-82ae-4ae4-b100-c4aef94edcc0"},{"uuid":"5d19a28e-234e-4dc4-82c7-58d36904554d"}]', received data: '{"success":false}'', stack: 'Error: run failed, test: 'discoveryAdvertisingStateUpdateNonTCP is called', event: 'run_discoveryAdvertisingStateUpdateNonTCP is called', sent data: '[{"uuid":"de738b71-8a4d-494a-a29e-8d3fa93e9827"},{"uuid":"6117f5b3-c5c2-4d3b-b9c2-e5a1a9d0d489"},{"uuid":"83cde4aa-82ae-4ae4-b100-c4aef94edcc0"},{"uuid":"5d19a28e-234e-4dc4-82c7-58d36904554d"}]', received data: '{"success":false}'
    at finishedHandler (/home/pi/Test/server_113351851fe156cf/test/TestServer/Socket.js:205:15)
    at Socket.<anonymous> (/home/pi/Test/server_113351851fe156cf/test/TestServer/Socket.js:238:9)
    at Socket.g (events.js:160:16)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_113351851fe156cf/test/TestServer/node_modules/socket.io/lib/socket.js:335:8)
    at Socket.onpacket (/home/pi/Test/server_113351851fe156cf/test/TestServer/node_modules/socket.io/lib/socket.js:295:12)
    at Client.ondecoded (/home/pi/Test/server_113351851fe156cf/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_113351851fe156cf/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_113351851fe156cf/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_113351851fe156cf/test/TestServer/node_modules/socket.io/lib/client.js:175:18)
    at Socket.emit (events.js:82:17)
    at Socket.onPacket (/home/pi/Test/server_113351851fe156cf/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/socket.js:101:14)
    at WebSocket.emit (events.js:82:17)
    at WebSocket.Transport.onPacket (/home/pi/Test/server_113351851fe156cf/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:104:8)
    at WebSocket.Transport.onData (/home/pi/Test/server_113351851fe156cf/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:115:8)
    at WebSocket.onData (/home/pi/Test/server_113351851fe156cf/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transports/websocket.js:76:30)
    at WebSocket.emit (events.js:85:17)''

2017-07-11 13:34:57 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_113351851fe156cf/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-07-11 13:34:57 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-07-11 13:34:57 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''

2017-07-11 13:34:57 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-07-11 13:34:57 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

[0;31merror: command 'sudo jx ______.js all' failed with code 1, file 'bash' on line 30[0m
One or more Android tests are failed.
 [0m
index.js failed [ 1 ]

```


Logs for system : 
```

ios : Error: Command failed: true
11/7/2017@15:25:44 Getting the list of iOS devices 
11/7/2017@15:25:45 ios: device name: Thali56 , device identifier:  8effff55cdeae82604a08043752b940f94063299
11/7/2017@15:25:45 ios: device name: Thali55 , device identifier:  d7a40d176e510e468af45ed03d4ca45fd18dbe43
11/7/2017@15:25:45 ios: device name: Thali54 , device identifier:  5f598c405d20d04b836dd4c89356e94737c1c2d2
11/7/2017@15:25:45 Deploying iOS test app 
11/7/2017@15:25:45 uninstalling the application 
11/7/2017@15:25:45 installing the application 
11/7/2017@15:26:26 ios: child process exited with code 253 on device d7a40d176e510e468af45ed03d4ca45fd18dbe43 
11/7/2017@15:26:27 ios: child process exited with code 253 on device 8effff55cdeae82604a08043752b940f94063299 
11/7/2017@15:26:31 ios: child process exited with code 253 on device 5f598c405d20d04b836dd4c89356e94737c1c2d2 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!
```
###iOS Logs
[Thali56](https://github.com/ThaliTester/TestResults/blob/113351851fe156cf_CI_sanity_check_jareksl/iOS_Thali56.md)

[Thali55](https://github.com/ThaliTester/TestResults/blob/113351851fe156cf_CI_sanity_check_jareksl/iOS_Thali55.md)

[Thali54](https://github.com/ThaliTester/TestResults/blob/113351851fe156cf_CI_sanity_check_jareksl/iOS_Thali54.md)

[server](https://github.com/ThaliTester/TestResults/blob/113351851fe156cf_CI_sanity_check_jareksl/iOS_server.md)


###Android Logs
####Node name: thali01
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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/113351851fe156cf_CI_sanity_check_jareksl/thali01_samsung-SM-G935F.md)

####Node name: thali03
Console output:
```
Stopping app on  ad081603480f209327
Uninstalling app on  ad081603480f209327

All devices are ready!

Deploying to ad081603480f209327
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
Deploying to ad081603480f209327
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ad081603480f209327

Starting application ThaliTest on ad081603480f209327

App was succesfully started on ad081603480f209327

Error! Unexpected exit on device ad081603480f209327 app:com.thaliproject.thalitest code:null 
Child process exited with code null on device ad081603480f209327
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/113351851fe156cf_CI_sanity_check_jareksl/thali03_samsung-SM-G930F.md)

####Node name: thali04
Console output:
```
Stopping app on  ce061606c181d71003
Uninstalling app on  ce061606c181d71003
Stopping app on  ce0616068b9f212302
Uninstalling app on  ce0616068b9f212302

All devices are ready!

Deploying to ce061606c181d71003
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce061606c181d71003

Deploying to ce0616068b9f212302
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce0616068b9f212302

Starting application ThaliTest on ce061606c181d71003

Starting application ThaliTest on ce0616068b9f212302

App was succesfully started on ce061606c181d71003

App was succesfully started on ce0616068b9f212302

Error! Unexpected exit on device ce061606c181d71003 app:com.thaliproject.thalitest code:null 
Child process exited with code null on device ce061606c181d71003
Error! Unexpected exit on device ce0616068b9f212302 app:com.thaliproject.thalitest code:null 
Child process exited with code null on device ce0616068b9f212302
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/113351851fe156cf_CI_sanity_check_jareksl/thali04_samsung-SM-G930F.md)





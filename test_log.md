#### Test 113351851ae9ffea Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":3}}
2017-07-21 14:00:45 - INFO HttpServer: 'listening on *:3000'

2017-07-21 14:00:51 - DEBUG HttpServer: 'device presented, name: 'Apple-Iphone6sPlus-1', uuid: 'cca4344b-5a54-415a-8424-de1d34107ec9', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-21 14:00:51 - DEBUG TestFramework: 'device added, name: 'Apple-Iphone6sPlus-1''

2017-07-21 14:00:52 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: 'c182453d-e8e4-408a-b900-603ab052bb06', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-21 14:00:52 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-1''

2017-07-21 14:00:53 - DEBUG HttpServer: 'device presented, name: 'Apple-Iphone6sPlus-1', uuid: 'cca4344b-5a54-415a-8424-de1d34107ec9', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-21 14:00:53 - INFO TestFramework: 'updating existing device, name: 'Apple-Iphone6sPlus-1', uuid: 'cca4344b-5a54-415a-8424-de1d34107ec9', platformName: 'ios''

2017-07-21 14:00:53 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: '486f6622-6bd3-4211-a93e-1fdd68eadece', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-21 14:00:53 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-mfts''

2017-07-21 14:00:53 - INFO TestFramework: 'all required 3 devices are present for platformName: 'ios''

2017-07-21 14:00:53 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'ios''

2017-07-21 14:00:53 - DEBUG UnitTestFramework: 'scheduling tests'

2017-07-21 14:00:54 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: '486f6622-6bd3-4211-a93e-1fdd68eadece', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-21 14:00:54 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-mfts', uuid: '486f6622-6bd3-4211-a93e-1fdd68eadece', platformName: 'ios''

2017-07-21 14:00:54 - DEBUG UnitTestFramework: 'tests scheduled'

2017-07-21 14:00:54 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-07-21 14:00:54 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: 'c182453d-e8e4-408a-b900-603ab052bb06', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-21 14:00:54 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-1', uuid: 'c182453d-e8e4-408a-b900-603ab052bb06', platformName: 'ios''

2017-07-21 14:00:55 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-07-21 14:00:55 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-07-21 14:00:55 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-07-21 14:00:55 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-07-21 14:00:55 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-07-21 14:00:55 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-07-21 14:00:56 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-07-21 14:00:56 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-07-21 14:00:56 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-07-21 14:00:56 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-07-21 14:00:56 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-07-21 14:00:56 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-21 14:00:57 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-21 14:00:57 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-21 14:00:57 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-21 14:00:57 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-21 14:00:57 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-21 14:00:57 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-21 14:00:58 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-21 14:00:58 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-21 14:00:58 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-21 14:00:58 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-21 14:00:58 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-21 14:00:58 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-07-21 14:00:58 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-21 14:00:58 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-07-21 14:00:58 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-21 14:00:58 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-21 14:00:58 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-21 14:00:58 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-21 14:00:58 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-07-21 14:00:58 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-21 14:00:58 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-21 14:00:59 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-21 14:00:59 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-21 14:00:59 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-21 14:00:59 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-21 14:00:59 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-21 14:00:59 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-21 14:00:59 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-21 14:00:59 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-21 14:00:59 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-21 14:00:59 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-21 14:00:59 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-21 14:00:59 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-21 14:00:59 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-21 14:00:59 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-21 14:00:59 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-21 14:00:59 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-21 14:00:59 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-21 14:00:59 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-21 14:00:59 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-21 14:00:59 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-21 14:01:00 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-21 14:01:00 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-21 14:01:00 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-21 14:01:00 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-21 14:01:00 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-21 14:01:00 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-21 14:01:00 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-07-21 14:01:00 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-07-21 14:01:00 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-07-21 14:01:00 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-07-21 14:01:00 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-07-21 14:01:02 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''
2017-07-21 14:01:02 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-07-21 14:01:02 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-07-21 14:01:02 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-07-21 14:01:02 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-07-21 14:01:02 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-07-21 14:01:02 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-07-21 14:01:02 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-07-21 14:01:03 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-07-21 14:01:03 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-07-21 14:01:03 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-07-21 14:01:03 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-07-21 14:01:03 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-07-21 14:01:03 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-07-21 14:01:03 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-07-21 14:01:03 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-07-21 14:01:04 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-07-21 14:01:04 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-07-21 14:01:04 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-07-21 14:01:04 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-07-21 14:01:04 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-07-21 14:01:04 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-07-21 14:01:04 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-07-21 14:01:04 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-07-21 14:01:04 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-07-21 14:01:04 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-07-21 14:01:05 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-07-21 14:01:05 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-07-21 14:01:05 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-07-21 14:01:05 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-07-21 14:01:05 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-07-21 14:01:05 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-07-21 14:01:05 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-07-21 14:01:05 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-07-21 14:01:05 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-07-21 14:01:05 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-07-21 14:01:06 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-07-21 14:01:06 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-07-21 14:01:06 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-07-21 14:01:06 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-07-21 14:01:07 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-07-21 14:01:07 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-07-21 14:01:07 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-07-21 14:01:07 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-07-21 14:01:07 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-07-21 14:01:07 - DEBUG UnitTestFramework: '#run: 'basic''

2017-07-21 14:01:07 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-07-21 14:01:07 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-07-21 14:01:07 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-07-21 14:01:07 - DEBUG UnitTestFramework: '#setup: 'another''

2017-07-21 14:01:07 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-07-21 14:01:07 - DEBUG UnitTestFramework: '#run: 'another''

2017-07-21 14:01:07 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-07-21 14:01:07 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-07-21 14:01:08 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-07-21 14:01:08 - DEBUG UnitTestFramework: '#setup: 'skip''

2017-07-21 14:01:08 - DEBUG UnitTestFramework: '#setup ok: 'skip''

2017-07-21 14:01:08 - DEBUG UnitTestFramework: '#run: 'skip''

2017-07-21 14:01:08 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-07-21 14:01:08 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-07-21 14:01:08 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-07-21 14:01:08 - DEBUG UnitTestFramework: '#run ok: 'skip''

2017-07-21 14:01:08 - DEBUG UnitTestFramework: '#teardown: 'skip''

2017-07-21 14:01:08 - DEBUG UnitTestFramework: '#teardown ok: 'skip''

2017-07-21 14:01:08 - DEBUG UnitTestFramework: '#setup: 'another skip''

2017-07-21 14:01:08 - DEBUG UnitTestFramework: '#setup ok: 'another skip''

2017-07-21 14:01:08 - DEBUG UnitTestFramework: '#run: 'another skip''

2017-07-21 14:01:08 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-07-21 14:01:08 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-07-21 14:01:08 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-07-21 14:01:08 - DEBUG UnitTestFramework: '#run ok: 'another skip''
2017-07-21 14:01:08 - DEBUG UnitTestFramework: '#teardown: 'another skip''

2017-07-21 14:01:08 - DEBUG UnitTestFramework: '#teardown ok: 'another skip''

2017-07-21 14:01:08 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox spy''

2017-07-21 14:01:08 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox spy''

2017-07-21 14:01:08 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox spy''

2017-07-21 14:01:08 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox spy''

2017-07-21 14:01:08 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox spy''

2017-07-21 14:01:09 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox spy''

2017-07-21 14:01:09 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub''

2017-07-21 14:01:09 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub''

2017-07-21 14:01:09 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub''

2017-07-21 14:01:09 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub''

2017-07-21 14:01:09 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub''

2017-07-21 14:01:09 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub''

2017-07-21 14:01:09 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub override''

2017-07-21 14:01:10 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub override''

2017-07-21 14:01:10 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub override''

2017-07-21 14:01:10 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub override''

2017-07-21 14:01:10 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub override''

2017-07-21 14:01:10 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub override''

2017-07-21 14:01:10 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox mock''

2017-07-21 14:01:11 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox mock''

2017-07-21 14:01:11 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox mock''

2017-07-21 14:01:11 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox mock''

2017-07-21 14:01:11 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox mock''

2017-07-21 14:01:15 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox mock''

2017-07-21 14:01:15 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox restore after test end''

2017-07-21 14:01:17 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox restore after test end''

2017-07-21 14:01:17 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox restore after test end''

2017-07-21 14:01:17 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox restore after test end''

2017-07-21 14:01:17 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox restore after test end''

2017-07-21 14:01:17 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox restore after test end''

2017-07-21 14:01:17 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-07-21 14:01:18 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-07-21 14:01:18 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-07-21 14:01:18 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-07-21 14:01:18 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-07-21 14:01:18 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-07-21 14:01:18 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-07-21 14:01:18 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-07-21 14:01:18 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-07-21 14:01:18 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-07-21 14:01:18 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-07-21 14:01:18 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-07-21 14:01:18 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-07-21 14:01:18 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-07-21 14:01:18 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-07-21 14:01:18 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-07-21 14:01:18 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-07-21 14:01:19 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-07-21 14:01:19 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-07-21 14:01:19 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-07-21 14:01:22 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-07-21 14:01:22 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-07-21 14:01:22 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-07-21 14:01:22 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-07-21 14:01:22 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-07-21 14:01:22 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-07-21 14:01:22 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-07-21 14:01:22 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-07-21 14:01:22 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-07-21 14:01:23 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-07-21 14:01:23 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-07-21 14:01:23 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-07-21 14:01:23 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-07-21 14:01:23 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-07-21 14:01:23 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-07-21 14:01:24 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-07-21 14:01:24 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-21 14:01:24 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-21 14:01:24 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-21 14:01:25 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-21 14:01:25 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-21 14:01:26 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-21 14:01:26 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-21 14:01:26 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-21 14:01:26 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-21 14:01:26 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-21 14:01:26 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-21 14:01:27 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-21 14:01:27 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-21 14:01:27 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-21 14:01:27 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-21 14:01:30 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-21 14:01:30 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-21 14:01:30 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-21 14:01:30 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-21 14:01:30 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-21 14:01:30 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-21 14:01:32 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-21 14:01:32 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-21 14:01:33 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-21 14:01:33 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-21 14:01:33 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-21 14:01:33 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-21 14:01:33 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-21 14:01:33 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-21 14:01:33 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-21 14:01:33 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-07-21 14:01:33 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-07-21 14:01:33 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-07-21 14:01:34 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-07-21 14:01:34 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-07-21 14:01:36 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-07-21 14:01:36 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-07-21 14:02:31 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'b5d07763-b01c-4db4-b14c-dc456c115749', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-21 14:02:31 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-07-21 14:02:34 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: 'bc2e4b30-67bc-4b96-9dd4-a9c5e5fb1880', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-21 14:02:34 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-07-21 14:02:36 - ERROR UnitTestFramework: '#run failed: 'Can connect to a remote peer', error: 'TimeoutError: timeout exceeded, event: 'setup_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'', stack: 'TimeoutError: timeout exceeded, event: 'setup_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'
    at afterTimeout (/home/pi/Test/server_113351851ae9ffea/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_113351851ae9ffea/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-07-21 14:02:36 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'ios', error: 'TimeoutError: timeout exceeded, event: 'setup_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'', stack: 'TimeoutError: timeout exceeded, event: 'setup_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'
    at afterTimeout (/home/pi/Test/server_113351851ae9ffea/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_113351851ae9ffea/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-07-21 14:02:59 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-1' disconnected, reason: 'ping timeout''

2017-07-21 14:03:18 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: 'c182453d-e8e4-408a-b900-603ab052bb06', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-21 14:03:18 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-1', uuid: 'c182453d-e8e4-408a-b900-603ab052bb06', platformName: 'ios''

2017-07-21 14:03:25 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: 'c182453d-e8e4-408a-b900-603ab052bb06', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-21 14:03:25 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-1', uuid: 'c182453d-e8e4-408a-b900-603ab052bb06', platformName: 'ios''

2017-07-21 14:03:36 - ERROR Socket: 'unexpected error: 'Error: retry count exceed', stack: 'Error: retry count exceed
    at emit (/home/pi/Test/server_113351851ae9ffea/test/TestServer/Socket.js:157:16)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-07-21 14:04:06 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'ef16a921-01e9-42f8-b9ce-ed3657feb1ba', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-21 14:04:06 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-07-21 14:04:06 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-07-21 14:04:06 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-07-21 14:04:06 - DEBUG UnitTestFramework: 'scheduling tests'

2017-07-21 14:04:09 - DEBUG UnitTestFramework: 'tests scheduled'

2017-07-21 14:04:09 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-07-21 14:04:09 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-07-21 14:04:09 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-07-21 14:04:12 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-07-21 14:04:12 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-07-21 14:04:12 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-07-21 14:04:12 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-07-21 14:04:14 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-07-21 14:04:14 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-07-21 14:04:18 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-07-21 14:04:18 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-07-21 14:04:19 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-07-21 14:04:19 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-21 14:04:22 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-21 14:04:22 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-21 14:04:23 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-21 14:04:23 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-21 14:04:25 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-21 14:04:25 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-21 14:04:28 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-21 14:04:28 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-21 14:04:30 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-21 14:04:30 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-21 14:04:32 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-21 14:04:32 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-07-21 14:04:35 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-21 14:04:35 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-07-21 14:04:35 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-21 14:04:36 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-21 14:04:37 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-21 14:04:37 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-21 14:04:37 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-07-21 14:04:40 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-21 14:04:40 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-21 14:04:42 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-21 14:04:42 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-21 14:04:42 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-21 14:04:43 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-21 14:04:43 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-21 14:04:43 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-21 14:04:43 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-21 14:04:46 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-21 14:04:46 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-21 14:04:47 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-21 14:04:47 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-21 14:04:47 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-21 14:04:48 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-21 14:04:49 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-21 14:04:49 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-21 14:04:49 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-21 14:04:50 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-21 14:04:50 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-21 14:04:52 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-21 14:04:52 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-21 14:04:52 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-21 14:04:53 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-21 14:04:55 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-21 14:04:55 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-21 14:04:55 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-21 14:04:56 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-21 14:04:56 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-07-21 14:04:58 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-07-21 14:04:58 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-07-21 14:04:59 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-07-21 14:04:59 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-07-21 14:05:01 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-07-21 14:05:01 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-07-21 14:05:02 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-07-21 14:05:02 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-07-21 14:05:04 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-07-21 14:05:04 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-07-21 14:05:05 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-07-21 14:05:05 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-07-21 14:05:07 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-07-21 14:05:07 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-07-21 14:05:10 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-07-21 14:05:10 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-07-21 14:05:12 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-07-21 14:05:12 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-07-21 14:05:14 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-07-21 14:05:14 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-07-21 14:05:16 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-07-21 14:05:16 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-07-21 14:05:18 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-07-21 14:05:18 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-07-21 14:05:20 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-07-21 14:05:20 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-07-21 14:05:22 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-07-21 14:05:22 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-07-21 14:05:24 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-07-21 14:05:24 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-07-21 14:05:24 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-07-21 14:05:24 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-07-21 14:05:26 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-07-21 14:05:26 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-07-21 14:05:27 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-07-21 14:05:27 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-07-21 14:05:29 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-07-21 14:05:29 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-07-21 14:05:30 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-07-21 14:05:30 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-07-21 14:05:32 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-07-21 14:05:32 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-07-21 14:05:35 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-07-21 14:05:35 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-07-21 14:05:37 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-07-21 14:05:37 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-07-21 14:05:39 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-07-21 14:05:39 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-07-21 14:05:41 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-07-21 14:05:41 - DEBUG UnitTestFramework: '#run: 'basic''

2017-07-21 14:05:43 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-07-21 14:05:43 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-07-21 14:05:45 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_113351851ae9ffea/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-07-21 14:05:45 - INFO HttpServer: 'Socket to device name: 'Apple-Iphone6sPlus-1' disconnected, reason: 'undefined''

2017-07-21 14:05:45 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-mfts' disconnected, reason: 'undefined''

2017-07-21 14:05:45 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-07-21 14:05:45 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''

2017-07-21 14:05:45 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-1' disconnected, reason: 'undefined''

2017-07-21 14:05:45 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

[0;31merror: command 'sudo jx ______.js all' failed with code 1, file 'bash' on line 30[0m
One or more Android tests are failed.
 [0m
index.js failed [ 1 ]

```


Logs for system : 
```

ios : Error: Command failed: true
21/7/2017@15:57:21 Getting the list of iOS devices 
21/7/2017@15:57:26 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
21/7/2017@15:57:26 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
21/7/2017@15:57:26 ios: device name: Iphone6sPlus-1 , device identifier:  f70cda60583ea0f895d05ea355cd125983c27594
21/7/2017@15:57:26 Deploying iOS test app 
21/7/2017@15:57:26 uninstalling the application 
21/7/2017@15:57:27 installing the application 
21/7/2017@15:57:27 ios.run: bffa901fefdea07f59339a6737776943349f5077 /Users/thali/Github/CI/builder/builds/113351851ae9ffea/build_ios/ThaliTest.app
21/7/2017@15:57:27 ios.run: 00b2e2c1b30013159b62125fe7f097bdcc055c10 /Users/thali/Github/CI/builder/builds/113351851ae9ffea/build_ios/ThaliTest.app
21/7/2017@15:57:27 ios.run: f70cda60583ea0f895d05ea355cd125983c27594 /Users/thali/Github/CI/builder/builds/113351851ae9ffea/build_ios/ThaliTest.app
true


android : Error: Command failed: copying android script192.168.1.52
copying android script192.168.1.50
copying android script192.168.1.53
Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!
```
###iOS Logs
[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/113351851ae9ffea_CI_sanity_check_jareksl/iOS_iphone-5s-mfts.md)

[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/113351851ae9ffea_CI_sanity_check_jareksl/iOS_iphone-5s-1.md)

[Iphone6sPlus-1](https://github.com/ThaliTester/TestResults/blob/113351851ae9ffea_CI_sanity_check_jareksl/iOS_Iphone6sPlus-1.md)


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

Error! Unexpected exit on device ce061606e320561102 app:com.thaliproject.thalitest code:null 
Child process exited with code null on device ce061606e320561102
Android task is completed. [FAILED]
Stopping App:com.thaliproject.thalitest ce061606e320561102 green
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/113351851ae9ffea_CI_sanity_check_jareksl/thali01_samsung-SM-G935F.md)

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

Error! Unexpected exit on device ce061606c181d71003 app:com.thaliproject.thalitest code:null 
Child process exited with code null on device ce061606c181d71003
Android task is completed. [FAILED]
Stopping App:com.thaliproject.thalitest ce061606c181d71003 green
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/113351851ae9ffea_CI_sanity_check_jareksl/thali03_samsung-SM-G930F.md)

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
is Device booted ce0616068b9f212302 10000 green
Checking:  adb -s ce0616068b9f212302 shell getprop sys.boot_completed green

All devices are ready!

Deploying to ce0616068b9f212302
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce0616068b9f212302

Starting application ThaliTest on ce0616068b9f212302

App was succesfully started on ce0616068b9f212302

Error! Unexpected exit on device ce0616068b9f212302 app:com.thaliproject.thalitest code:null 
Child process exited with code null on device ce0616068b9f212302
Android task is completed. [FAILED]
Stopping App:com.thaliproject.thalitest ce0616068b9f212302 green
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/113351851ae9ffea_CI_sanity_check_jareksl/thali04_samsung-SM-G930F.md)





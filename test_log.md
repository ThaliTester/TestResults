#### Test 11335185196ab692 Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":3}}
2017-07-13 08:31:41 - INFO HttpServer: 'listening on *:3000'

2017-07-13 08:31:43 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: 'd07274b3-2294-4f2e-9b38-e14869561fb8', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-13 08:31:43 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-1''

2017-07-13 08:31:45 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: 'd07274b3-2294-4f2e-9b38-e14869561fb8', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-13 08:31:45 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-1', uuid: 'd07274b3-2294-4f2e-9b38-e14869561fb8', platformName: 'ios''

2017-07-13 08:31:50 - DEBUG HttpServer: 'device presented, name: 'Apple-Iphone6sPlus-1', uuid: '2e4e2245-ee90-4904-94d9-3bf7348c53ea', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-13 08:31:50 - DEBUG TestFramework: 'device added, name: 'Apple-Iphone6sPlus-1''

2017-07-13 08:31:50 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: 'd3c978f2-16c2-4405-ac70-2305e0d7fe9b', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-13 08:31:50 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-mfts''

2017-07-13 08:31:50 - INFO TestFramework: 'all required 3 devices are present for platformName: 'ios''

2017-07-13 08:31:50 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'ios''

2017-07-13 08:31:50 - DEBUG UnitTestFramework: 'scheduling tests'

2017-07-13 08:31:51 - DEBUG UnitTestFramework: 'tests scheduled'

2017-07-13 08:31:51 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-07-13 08:31:51 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-07-13 08:31:51 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-07-13 08:31:52 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: 'd3c978f2-16c2-4405-ac70-2305e0d7fe9b', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-13 08:31:52 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-mfts', uuid: 'd3c978f2-16c2-4405-ac70-2305e0d7fe9b', platformName: 'ios''

2017-07-13 08:31:52 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-07-13 08:31:52 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-07-13 08:31:52 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-07-13 08:31:52 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-07-13 08:31:52 - DEBUG HttpServer: 'device presented, name: 'Apple-Iphone6sPlus-1', uuid: '2e4e2245-ee90-4904-94d9-3bf7348c53ea', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-13 08:31:52 - INFO TestFramework: 'updating existing device, name: 'Apple-Iphone6sPlus-1', uuid: '2e4e2245-ee90-4904-94d9-3bf7348c53ea', platformName: 'ios''

2017-07-13 08:31:52 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-07-13 08:31:52 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-07-13 08:31:52 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-07-13 08:31:52 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-07-13 08:31:52 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-07-13 08:31:52 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-13 08:31:52 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-13 08:31:52 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-13 08:31:53 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-13 08:31:53 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-13 08:31:53 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-13 08:31:53 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-13 08:31:53 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-13 08:31:53 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-13 08:31:53 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-13 08:31:53 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-13 08:31:53 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-13 08:31:53 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-07-13 08:31:53 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-13 08:31:53 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-07-13 08:31:53 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-13 08:31:53 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-13 08:31:54 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-13 08:31:54 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-13 08:31:54 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-07-13 08:31:54 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-13 08:31:54 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-13 08:31:54 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-13 08:31:54 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-13 08:31:55 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-13 08:31:55 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-13 08:31:55 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-13 08:31:55 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-13 08:31:55 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-13 08:31:55 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-13 08:31:55 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-13 08:31:55 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-13 08:31:55 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-13 08:31:55 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-13 08:31:55 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-13 08:31:55 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-13 08:31:55 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-13 08:31:55 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-13 08:31:55 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-13 08:31:55 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-13 08:31:56 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-13 08:31:56 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-13 08:31:56 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-13 08:31:56 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-13 08:31:56 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-13 08:31:56 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-13 08:31:56 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-13 08:31:56 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-13 08:31:56 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-07-13 08:31:56 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-07-13 08:31:56 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-07-13 08:31:56 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-07-13 08:31:56 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-07-13 08:31:56 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-07-13 08:31:56 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-07-13 08:31:57 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-07-13 08:31:57 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-07-13 08:31:57 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-07-13 08:31:57 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-07-13 08:31:57 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-07-13 08:31:57 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-07-13 08:31:57 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-07-13 08:31:57 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-07-13 08:31:57 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-07-13 08:31:57 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-07-13 08:31:58 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-07-13 08:31:58 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-07-13 08:31:58 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-07-13 08:31:58 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-07-13 08:31:58 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-07-13 08:31:58 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-07-13 08:31:58 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-07-13 08:31:58 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-07-13 08:31:58 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-07-13 08:31:58 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-07-13 08:31:58 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-07-13 08:31:58 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-07-13 08:31:59 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-07-13 08:31:59 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-07-13 08:31:59 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''
2017-07-13 08:31:59 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-07-13 08:32:00 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-07-13 08:32:00 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-07-13 08:32:00 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-07-13 08:32:00 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-07-13 08:32:00 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-07-13 08:32:00 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-07-13 08:32:00 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-07-13 08:32:00 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-07-13 08:32:00 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-07-13 08:32:00 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-07-13 08:32:00 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-07-13 08:32:00 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-07-13 08:32:01 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-07-13 08:32:01 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-07-13 08:32:01 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-07-13 08:32:01 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-07-13 08:32:01 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-07-13 08:32:01 - DEBUG UnitTestFramework: '#run: 'basic''

2017-07-13 08:32:01 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-07-13 08:32:01 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-07-13 08:32:01 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-07-13 08:32:01 - DEBUG UnitTestFramework: '#setup: 'another''

2017-07-13 08:32:01 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-07-13 08:32:01 - DEBUG UnitTestFramework: '#run: 'another''

2017-07-13 08:32:01 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-07-13 08:32:01 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-07-13 08:32:01 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-07-13 08:32:01 - DEBUG UnitTestFramework: '#setup: 'skip''

2017-07-13 08:32:02 - DEBUG UnitTestFramework: '#setup ok: 'skip''

2017-07-13 08:32:02 - DEBUG UnitTestFramework: '#run: 'skip''

2017-07-13 08:32:02 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-07-13 08:32:02 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-07-13 08:32:02 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-07-13 08:32:02 - DEBUG UnitTestFramework: '#run ok: 'skip''

2017-07-13 08:32:02 - DEBUG UnitTestFramework: '#teardown: 'skip''

2017-07-13 08:32:02 - DEBUG UnitTestFramework: '#teardown ok: 'skip''

2017-07-13 08:32:02 - DEBUG UnitTestFramework: '#setup: 'another skip''

2017-07-13 08:32:02 - DEBUG UnitTestFramework: '#setup ok: 'another skip''

2017-07-13 08:32:02 - DEBUG UnitTestFramework: '#run: 'another skip''

2017-07-13 08:32:02 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-07-13 08:32:02 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-07-13 08:32:02 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-07-13 08:32:02 - DEBUG UnitTestFramework: '#run ok: 'another skip''
2017-07-13 08:32:02 - DEBUG UnitTestFramework: '#teardown: 'another skip''

2017-07-13 08:32:02 - DEBUG UnitTestFramework: '#teardown ok: 'another skip''

2017-07-13 08:32:02 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox spy''

2017-07-13 08:32:02 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox spy''

2017-07-13 08:32:02 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox spy''

2017-07-13 08:32:02 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox spy''

2017-07-13 08:32:02 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox spy''

2017-07-13 08:32:03 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox spy''

2017-07-13 08:32:03 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub''

2017-07-13 08:32:03 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub''

2017-07-13 08:32:03 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub''

2017-07-13 08:32:03 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub''

2017-07-13 08:32:03 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub''

2017-07-13 08:32:03 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub''

2017-07-13 08:32:03 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub override''

2017-07-13 08:32:03 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub override''

2017-07-13 08:32:03 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub override''

2017-07-13 08:32:03 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub override''

2017-07-13 08:32:03 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub override''

2017-07-13 08:32:03 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub override''

2017-07-13 08:32:03 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox mock''

2017-07-13 08:32:04 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox mock''

2017-07-13 08:32:04 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox mock''

2017-07-13 08:32:04 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox mock''

2017-07-13 08:32:04 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox mock''

2017-07-13 08:32:04 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox mock''

2017-07-13 08:32:04 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox restore after test end''

2017-07-13 08:32:04 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox restore after test end''

2017-07-13 08:32:04 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox restore after test end''

2017-07-13 08:32:04 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox restore after test end''

2017-07-13 08:32:04 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox restore after test end''

2017-07-13 08:32:05 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox restore after test end''

2017-07-13 08:32:05 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-07-13 08:32:05 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-07-13 08:32:05 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-07-13 08:32:05 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-07-13 08:32:05 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-07-13 08:32:05 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-07-13 08:32:05 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-07-13 08:32:05 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-07-13 08:32:05 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-07-13 08:32:06 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-07-13 08:32:06 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-07-13 08:32:06 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-07-13 08:32:06 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-07-13 08:32:06 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-07-13 08:32:06 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-07-13 08:32:06 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-07-13 08:32:06 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-07-13 08:32:06 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-07-13 08:32:06 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-07-13 08:32:06 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-07-13 08:32:06 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-07-13 08:32:06 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-07-13 08:32:06 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-07-13 08:32:06 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-07-13 08:32:06 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-07-13 08:32:06 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-07-13 08:32:06 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-07-13 08:32:06 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-07-13 08:32:06 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-07-13 08:32:07 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-07-13 08:32:07 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-07-13 08:32:07 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-07-13 08:32:07 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-07-13 08:32:07 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-07-13 08:32:07 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-07-13 08:32:07 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-07-13 08:32:07 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-13 08:32:07 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-13 08:32:07 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-13 08:32:08 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-13 08:32:08 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-13 08:32:08 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-13 08:32:08 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-13 08:32:08 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-13 08:32:08 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-13 08:32:09 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-13 08:32:09 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-13 08:32:09 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-13 08:32:09 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-13 08:32:10 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-13 08:32:10 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-13 08:32:12 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-13 08:32:12 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-13 08:32:15 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-13 08:32:15 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-13 08:32:16 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-13 08:32:16 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-13 08:32:17 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-13 08:32:17 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-13 08:32:17 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-13 08:32:17 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-13 08:32:17 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-13 08:32:17 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-13 08:32:21 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-13 08:32:21 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-13 08:32:26 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-13 08:32:26 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-07-13 08:32:33 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-07-13 08:32:33 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-07-13 08:32:35 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-07-13 08:32:35 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-07-13 08:32:35 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-07-13 08:32:35 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-07-13 08:32:35 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-07-13 08:32:35 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-07-13 08:32:46 - DEBUG UnitTestFramework: '#run ok: 'Can connect to a remote peer''

2017-07-13 08:32:46 - DEBUG UnitTestFramework: '#teardown: 'Can connect to a remote peer''

2017-07-13 08:32:46 - DEBUG UnitTestFramework: '#teardown ok: 'Can connect to a remote peer''

2017-07-13 08:32:46 - DEBUG UnitTestFramework: '#setup: 'Can shift data''

2017-07-13 08:32:48 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data''

2017-07-13 08:32:48 - DEBUG UnitTestFramework: '#run: 'Can shift data''

2017-07-13 08:33:03 - DEBUG UnitTestFramework: '#run ok: 'Can shift data''

2017-07-13 08:33:03 - DEBUG UnitTestFramework: '#teardown: 'Can shift data''

2017-07-13 08:33:03 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data''

2017-07-13 08:33:03 - DEBUG UnitTestFramework: '#setup: 'Can shift data via parallel connections''

2017-07-13 08:33:03 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data via parallel connections''

2017-07-13 08:33:03 - DEBUG UnitTestFramework: '#run: 'Can shift data via parallel connections''

2017-07-13 08:33:20 - DEBUG UnitTestFramework: '#run ok: 'Can shift data via parallel connections''

2017-07-13 08:33:20 - DEBUG UnitTestFramework: '#teardown: 'Can shift data via parallel connections''

2017-07-13 08:33:21 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data via parallel connections''

2017-07-13 08:33:21 - DEBUG UnitTestFramework: '#setup: 'Can shift data securely''

2017-07-13 08:33:21 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data securely''

2017-07-13 08:33:21 - DEBUG UnitTestFramework: '#run: 'Can shift data securely''

2017-07-13 08:33:31 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '33db3b42-3bf4-4ee4-bb1f-44c90f3b9d49', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-13 08:33:31 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-07-13 08:33:31 - DEBUG UnitTestFramework: '#run ok: 'Can shift data securely''

2017-07-13 08:33:31 - DEBUG UnitTestFramework: '#teardown: 'Can shift data securely''

2017-07-13 08:33:31 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data securely''

2017-07-13 08:33:31 - DEBUG UnitTestFramework: '#setup: 'Can shift large amounts of data''

2017-07-13 08:33:32 - DEBUG UnitTestFramework: '#setup ok: 'Can shift large amounts of data''

2017-07-13 08:33:32 - DEBUG UnitTestFramework: '#run: 'Can shift large amounts of data''

2017-07-13 08:33:34 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'eb38cc7b-a39f-4305-83cd-adf86a724bcd', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-13 08:33:34 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-07-13 08:33:44 - DEBUG UnitTestFramework: '#run ok: 'Can shift large amounts of data''

2017-07-13 08:33:44 - DEBUG UnitTestFramework: '#teardown: 'Can shift large amounts of data''

2017-07-13 08:33:45 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift large amounts of data''

2017-07-13 08:33:45 - DEBUG UnitTestFramework: '#setup: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-13 08:33:45 - DEBUG UnitTestFramework: '#setup ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-13 08:33:45 - DEBUG UnitTestFramework: '#run: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-13 08:33:50 - DEBUG UnitTestFramework: '#run ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-13 08:33:50 - DEBUG UnitTestFramework: '#teardown: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-13 08:33:50 - DEBUG UnitTestFramework: '#teardown ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-13 08:33:50 - DEBUG UnitTestFramework: '#setup: 'Test updating advertising and parallel data transfer''

2017-07-13 08:33:50 - DEBUG UnitTestFramework: '#setup ok: 'Test updating advertising and parallel data transfer''

2017-07-13 08:33:50 - DEBUG UnitTestFramework: '#run: 'Test updating advertising and parallel data transfer''

2017-07-13 08:33:50 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-07-13 08:33:50 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-07-13 08:33:50 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-07-13 08:33:50 - DEBUG UnitTestFramework: '#run ok: 'Test updating advertising and parallel data transfer''

2017-07-13 08:33:50 - DEBUG UnitTestFramework: '#teardown: 'Test updating advertising and parallel data transfer''

2017-07-13 08:33:51 - DEBUG UnitTestFramework: '#teardown ok: 'Test updating advertising and parallel data transfer''

2017-07-13 08:33:51 - DEBUG UnitTestFramework: '#setup: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-13 08:33:51 - DEBUG UnitTestFramework: '#setup ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-13 08:33:51 - DEBUG UnitTestFramework: '#run: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-13 08:33:51 - DEBUG UnitTestFramework: '#run ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-13 08:33:51 - DEBUG UnitTestFramework: '#teardown: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-13 08:33:51 - DEBUG UnitTestFramework: '#teardown ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-13 08:33:51 - DEBUG UnitTestFramework: '#setup: 'cannot call connect when start listening for advertisements is not active''

2017-07-13 08:33:51 - DEBUG UnitTestFramework: '#setup ok: 'cannot call connect when start listening for advertisements is not active''

2017-07-13 08:33:51 - DEBUG UnitTestFramework: '#run: 'cannot call connect when start listening for advertisements is not active''

2017-07-13 08:33:51 - INFO Socket: 'run skipped, test: 'cannot call connect when start listening for advertisements is not active', event: 'run_cannot call connect when start listening for advertisements is not active''

2017-07-13 08:33:51 - INFO Socket: 'run skipped, test: 'cannot call connect when start listening for advertisements is not active', event: 'run_cannot call connect when start listening for advertisements is not active''

2017-07-13 08:33:51 - INFO Socket: 'run skipped, test: 'cannot call connect when start listening for advertisements is not active', event: 'run_cannot call connect when start listening for advertisements is not active''

2017-07-13 08:33:51 - DEBUG UnitTestFramework: '#run ok: 'cannot call connect when start listening for advertisements is not active''

2017-07-13 08:33:51 - DEBUG UnitTestFramework: '#teardown: 'cannot call connect when start listening for advertisements is not active''

2017-07-13 08:33:52 - DEBUG UnitTestFramework: '#teardown ok: 'cannot call connect when start listening for advertisements is not active''

2017-07-13 08:33:52 - DEBUG UnitTestFramework: '#setup: 'Get error when trying to double connect to a peer on Android''

2017-07-13 08:33:52 - DEBUG UnitTestFramework: '#setup ok: 'Get error when trying to double connect to a peer on Android''

2017-07-13 08:33:52 - DEBUG UnitTestFramework: '#run: 'Get error when trying to double connect to a peer on Android''

2017-07-13 08:33:52 - INFO Socket: 'run skipped, test: 'Get error when trying to double connect to a peer on Android', event: 'run_Get error when trying to double connect to a peer on Android''

2017-07-13 08:33:52 - INFO Socket: 'run skipped, test: 'Get error when trying to double connect to a peer on Android', event: 'run_Get error when trying to double connect to a peer on Android''

2017-07-13 08:33:52 - INFO Socket: 'run skipped, test: 'Get error when trying to double connect to a peer on Android', event: 'run_Get error when trying to double connect to a peer on Android''

2017-07-13 08:33:52 - DEBUG UnitTestFramework: '#run ok: 'Get error when trying to double connect to a peer on Android''

2017-07-13 08:33:52 - DEBUG UnitTestFramework: '#teardown: 'Get error when trying to double connect to a peer on Android''

2017-07-13 08:33:52 - DEBUG UnitTestFramework: '#teardown ok: 'Get error when trying to double connect to a peer on Android''

2017-07-13 08:33:52 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-13 08:33:53 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-13 08:33:53 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-13 08:33:53 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection', event: 'run_#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-13 08:33:53 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection', event: 'run_#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-13 08:33:53 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection', event: 'run_#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-13 08:33:53 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-13 08:33:53 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-13 08:33:53 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-13 08:33:53 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-13 08:33:54 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-13 08:33:54 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-13 08:33:54 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection', event: 'run_#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-13 08:33:54 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection', event: 'run_#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-13 08:33:54 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection', event: 'run_#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-13 08:33:54 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-13 08:33:54 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-13 08:33:54 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-13 08:33:54 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-13 08:33:54 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-13 08:33:54 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-13 08:33:54 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer', event: 'run_#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-13 08:33:54 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer', event: 'run_#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-13 08:33:55 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer', event: 'run_#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-13 08:33:55 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-13 08:33:55 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-13 08:33:55 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-13 08:33:55 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-13 08:33:55 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-13 08:33:55 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-13 08:33:55 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer', event: 'run_#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-13 08:33:55 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer', event: 'run_#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-13 08:33:55 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer', event: 'run_#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-13 08:33:55 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-13 08:33:55 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-13 08:33:55 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-13 08:33:55 - DEBUG UnitTestFramework: '#setup: 'cannot call multiConnect when start listening for advertisements is not active''

2017-07-13 08:33:55 - DEBUG UnitTestFramework: '#setup ok: 'cannot call multiConnect when start listening for advertisements is not active''

2017-07-13 08:33:55 - DEBUG UnitTestFramework: '#run: 'cannot call multiConnect when start listening for advertisements is not active''

2017-07-13 08:33:55 - DEBUG UnitTestFramework: '#run ok: 'cannot call multiConnect when start listening for advertisements is not active''

2017-07-13 08:33:55 - DEBUG UnitTestFramework: '#teardown: 'cannot call multiConnect when start listening for advertisements is not active''

2017-07-13 08:33:55 - DEBUG UnitTestFramework: '#teardown ok: 'cannot call multiConnect when start listening for advertisements is not active''

2017-07-13 08:33:55 - DEBUG UnitTestFramework: '#setup: 'cannot call multiConnect with illegal peerID''

2017-07-13 08:33:56 - DEBUG UnitTestFramework: '#setup ok: 'cannot call multiConnect with illegal peerID''

2017-07-13 08:33:56 - DEBUG UnitTestFramework: '#run: 'cannot call multiConnect with illegal peerID''

2017-07-13 08:33:56 - DEBUG UnitTestFramework: '#run ok: 'cannot call multiConnect with illegal peerID''

2017-07-13 08:33:56 - DEBUG UnitTestFramework: '#teardown: 'cannot call multiConnect with illegal peerID''

2017-07-13 08:33:56 - DEBUG UnitTestFramework: '#teardown ok: 'cannot call multiConnect with illegal peerID''

2017-07-13 08:33:56 - DEBUG UnitTestFramework: '#setup: 'multiConnect properly fails on legal but non-existent peerID''

2017-07-13 08:33:56 - DEBUG UnitTestFramework: '#setup ok: 'multiConnect properly fails on legal but non-existent peerID''

2017-07-13 08:33:56 - DEBUG UnitTestFramework: '#run: 'multiConnect properly fails on legal but non-existent peerID''

2017-07-13 08:33:56 - ERROR UnitTestFramework: '#run failed: 'multiConnect properly fails on legal but non-existent peerID', error: 'Error: run failed, test: 'multiConnect properly fails on legal but non-existent peerID', event: 'run_multiConnect properly fails on legal but non-existent peerID', sent data: '[{"uuid":"d07274b3-2294-4f2e-9b38-e14869561fb8"},{"uuid":"2e4e2245-ee90-4904-94d9-3bf7348c53ea"},{"uuid":"d3c978f2-16c2-4405-ac70-2305e0d7fe9b"}]', received data: '{"success":false}'', stack: 'Error: run failed, test: 'multiConnect properly fails on legal but non-existent peerID', event: 'run_multiConnect properly fails on legal but non-existent peerID', sent data: '[{"uuid":"d07274b3-2294-4f2e-9b38-e14869561fb8"},{"uuid":"2e4e2245-ee90-4904-94d9-3bf7348c53ea"},{"uuid":"d3c978f2-16c2-4405-ac70-2305e0d7fe9b"}]', received data: '{"success":false}'
    at finishedHandler (/home/pi/Test/server_11335185196ab692/test/TestServer/Socket.js:205:15)
    at Socket.<anonymous> (/home/pi/Test/server_11335185196ab692/test/TestServer/Socket.js:238:9)
    at Socket.g (events.js:160:16)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_11335185196ab692/test/TestServer/node_modules/socket.io/lib/socket.js:335:8)
    at Socket.onpacket (/home/pi/Test/server_11335185196ab692/test/TestServer/node_modules/socket.io/lib/socket.js:295:12)
    at Client.ondecoded (/home/pi/Test/server_11335185196ab692/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_11335185196ab692/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_11335185196ab692/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_11335185196ab692/test/TestServer/node_modules/socket.io/lib/client.js:175:18)
    at Socket.emit (events.js:82:17)
    at Socket.onPacket (/home/pi/Test/server_11335185196ab692/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/socket.js:101:14)
    at WebSocket.emit (events.js:82:17)
    at WebSocket.Transport.onPacket (/home/pi/Test/server_11335185196ab692/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:104:8)
    at WebSocket.Transport.onData (/home/pi/Test/server_11335185196ab692/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:115:8)
    at WebSocket.onData (/home/pi/Test/server_11335185196ab692/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transports/websocket.js:76:30)
    at WebSocket.emit (events.js:85:17)''

2017-07-13 08:33:56 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'ios', error: 'Error: run failed, test: 'multiConnect properly fails on legal but non-existent peerID', event: 'run_multiConnect properly fails on legal but non-existent peerID', sent data: '[{"uuid":"d07274b3-2294-4f2e-9b38-e14869561fb8"},{"uuid":"2e4e2245-ee90-4904-94d9-3bf7348c53ea"},{"uuid":"d3c978f2-16c2-4405-ac70-2305e0d7fe9b"}]', received data: '{"success":false}'', stack: 'Error: run failed, test: 'multiConnect properly fails on legal but non-existent peerID', event: 'run_multiConnect properly fails on legal but non-existent peerID', sent data: '[{"uuid":"d07274b3-2294-4f2e-9b38-e14869561fb8"},{"uuid":"2e4e2245-ee90-4904-94d9-3bf7348c53ea"},{"uuid":"d3c978f2-16c2-4405-ac70-2305e0d7fe9b"}]', received data: '{"success":false}'
    at finishedHandler (/home/pi/Test/server_11335185196ab692/test/TestServer/Socket.js:205:15)
    at Socket.<anonymous> (/home/pi/Test/server_11335185196ab692/test/TestServer/Socket.js:238:9)
    at Socket.g (events.js:160:16)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_11335185196ab692/test/TestServer/node_modules/socket.io/lib/socket.js:335:8)
    at Socket.onpacket (/home/pi/Test/server_11335185196ab692/test/TestServer/node_modules/socket.io/lib/socket.js:295:12)
    at Client.ondecoded (/home/pi/Test/server_11335185196ab692/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_11335185196ab692/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_11335185196ab692/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_11335185196ab692/test/TestServer/node_modules/socket.io/lib/client.js:175:18)
    at Socket.emit (events.js:82:17)
    at Socket.onPacket (/home/pi/Test/server_11335185196ab692/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/socket.js:101:14)
    at WebSocket.emit (events.js:82:17)
    at WebSocket.Transport.onPacket (/home/pi/Test/server_11335185196ab692/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:104:8)
    at WebSocket.Transport.onData (/home/pi/Test/server_11335185196ab692/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:115:8)
    at WebSocket.onData (/home/pi/Test/server_11335185196ab692/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transports/websocket.js:76:30)
    at WebSocket.emit (events.js:85:17)''

2017-07-13 08:34:47 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '8c66eae7-258c-46ba-b72b-1132c4879e5e', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-13 08:34:47 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-07-13 08:34:47 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-07-13 08:34:47 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''
2017-07-13 08:34:47 - DEBUG UnitTestFramework: 'scheduling tests'

2017-07-13 08:34:49 - DEBUG UnitTestFramework: 'tests scheduled'

2017-07-13 08:34:49 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-07-13 08:34:51 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-07-13 08:34:51 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-07-13 08:34:54 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-07-13 08:34:54 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-07-13 08:34:55 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-07-13 08:34:55 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-07-13 08:34:57 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-07-13 08:34:57 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-07-13 08:35:00 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-07-13 08:35:00 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-07-13 08:35:01 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-07-13 08:35:01 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-13 08:35:03 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-13 08:35:03 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-13 08:35:06 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-13 08:35:06 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-13 08:35:08 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-13 08:35:08 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-13 08:35:09 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-13 08:35:09 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-13 08:35:12 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-13 08:35:12 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-13 08:35:16 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-13 08:35:16 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-07-13 08:35:18 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-13 08:35:18 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-07-13 08:35:18 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-13 08:35:19 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-13 08:35:20 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-13 08:35:20 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-13 08:35:20 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-07-13 08:35:22 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-13 08:35:22 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-13 08:35:24 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-13 08:35:24 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-13 08:35:24 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-13 08:35:25 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-13 08:35:26 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-13 08:35:26 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-13 08:35:26 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-13 08:35:28 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-13 08:35:28 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-13 08:35:30 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-13 08:35:30 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-13 08:35:30 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-13 08:35:31 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-13 08:35:32 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-13 08:35:32 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-13 08:35:32 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-13 08:35:34 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-13 08:35:34 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-13 08:35:37 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-13 08:35:37 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-13 08:35:37 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-13 08:35:38 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-13 08:35:38 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-13 08:35:38 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-13 08:35:38 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-13 08:35:42 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-13 08:35:42 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-07-13 08:35:46 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-07-13 08:35:46 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-07-13 08:35:48 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-07-13 08:35:48 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-07-13 08:35:51 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-07-13 08:35:51 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-07-13 08:35:51 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-07-13 08:35:51 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-07-13 08:35:54 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-07-13 08:35:54 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-07-13 08:35:54 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-07-13 08:35:54 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-07-13 08:35:57 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-07-13 08:35:57 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-07-13 08:36:00 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-07-13 08:36:00 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-07-13 08:36:00 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-07-13 08:36:00 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-07-13 08:36:02 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-07-13 08:36:02 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-07-13 08:36:05 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-07-13 08:36:05 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-07-13 08:36:06 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-07-13 08:36:06 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-07-13 08:36:07 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-07-13 08:36:07 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-07-13 08:36:11 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-07-13 08:36:11 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-07-13 08:36:13 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-07-13 08:36:13 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-07-13 08:36:16 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-07-13 08:36:16 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-07-13 08:36:19 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-07-13 08:36:19 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-07-13 08:36:21 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-07-13 08:36:21 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-07-13 08:36:22 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-07-13 08:36:22 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-07-13 08:36:25 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-07-13 08:36:25 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-07-13 08:36:27 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-07-13 08:36:27 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-07-13 08:36:28 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-07-13 08:36:28 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-07-13 08:36:30 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-07-13 08:36:30 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-07-13 08:36:35 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-07-13 08:36:35 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-07-13 08:36:37 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-07-13 08:36:37 - DEBUG UnitTestFramework: '#run: 'basic''

2017-07-13 08:36:39 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-07-13 08:36:39 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-07-13 08:36:40 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-07-13 08:36:40 - DEBUG UnitTestFramework: '#setup: 'another''

2017-07-13 08:36:41 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_11335185196ab692/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-07-13 08:36:41 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-1' disconnected, reason: 'undefined''

2017-07-13 08:36:41 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-mfts' disconnected, reason: 'undefined''

2017-07-13 08:36:41 - INFO HttpServer: 'Socket to device name: 'Apple-Iphone6sPlus-1' disconnected, reason: 'undefined''

2017-07-13 08:36:41 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-07-13 08:36:41 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-07-13 08:36:41 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''

[0;31merror: command 'sudo jx ______.js all' failed with code 1, file 'bash' on line 30[0m
One or more Android tests are failed.
 [0m
index.js failed [ 1 ]

```


Logs for system : 
```

ios : Error: Command failed: true
13/7/2017@10:28:12 Getting the list of iOS devices 
13/7/2017@10:28:13 ios: device name: Iphone6sPlus-1 , device identifier:  f70cda60583ea0f895d05ea355cd125983c27594
13/7/2017@10:28:13 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
13/7/2017@10:28:13 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
13/7/2017@10:28:13 Deploying iOS test app 
13/7/2017@10:28:13 uninstalling the application 
13/7/2017@10:28:13 installing the application 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!
```
###iOS Logs
[Iphone6sPlus-1](https://github.com/ThaliTester/TestResults/blob/11335185196ab692_CI_sanity_check_jareksl/iOS_Iphone6sPlus-1.md)

[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/11335185196ab692_CI_sanity_check_jareksl/iOS_iphone-5s-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/11335185196ab692_CI_sanity_check_jareksl/iOS_iphone-5s-mfts.md)


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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/11335185196ab692_CI_sanity_check_jareksl/thali01_samsung-SM-G935F.md)

####Node name: thali03
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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/11335185196ab692_CI_sanity_check_jareksl/thali03_samsung-SM-G930F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/11335185196ab692_CI_sanity_check_jareksl/thali04_samsung-SM-G930F.md)





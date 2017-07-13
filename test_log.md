#### Test 11335185196ab692 Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":3}}
2017-07-13 07:38:51 - INFO HttpServer: 'listening on *:3000'

2017-07-13 07:38:52 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: '7429bd2a-7ddd-4480-9dee-bcb66c6ea3bf', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-13 07:38:52 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-1''

2017-07-13 07:38:54 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: '7429bd2a-7ddd-4480-9dee-bcb66c6ea3bf', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-13 07:38:54 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-1', uuid: '7429bd2a-7ddd-4480-9dee-bcb66c6ea3bf', platformName: 'ios''

2017-07-13 07:38:58 - DEBUG HttpServer: 'device presented, name: 'Apple-Iphone6sPlus-1', uuid: 'ac0e4d72-52ca-4ad2-9509-e84c7cd40172', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-13 07:38:58 - DEBUG TestFramework: 'device added, name: 'Apple-Iphone6sPlus-1''

2017-07-13 07:38:59 - DEBUG HttpServer: 'device presented, name: 'Apple-Iphone6sPlus-1', uuid: 'ac0e4d72-52ca-4ad2-9509-e84c7cd40172', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-13 07:38:59 - INFO TestFramework: 'updating existing device, name: 'Apple-Iphone6sPlus-1', uuid: 'ac0e4d72-52ca-4ad2-9509-e84c7cd40172', platformName: 'ios''

2017-07-13 07:39:00 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: '26bb0a9c-78ae-475d-ae1e-25e4e9f16cba', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-13 07:39:00 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-mfts''

2017-07-13 07:39:00 - INFO TestFramework: 'all required 3 devices are present for platformName: 'ios''

2017-07-13 07:39:00 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'ios''

2017-07-13 07:39:00 - DEBUG UnitTestFramework: 'scheduling tests'

2017-07-13 07:39:02 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: '26bb0a9c-78ae-475d-ae1e-25e4e9f16cba', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-13 07:39:02 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-mfts', uuid: '26bb0a9c-78ae-475d-ae1e-25e4e9f16cba', platformName: 'ios''

2017-07-13 07:39:05 - DEBUG UnitTestFramework: 'tests scheduled'

2017-07-13 07:39:05 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-07-13 07:39:08 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-07-13 07:39:08 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-07-13 07:39:09 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-07-13 07:39:09 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-07-13 07:39:09 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-07-13 07:39:09 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-07-13 07:39:09 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-07-13 07:39:09 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-07-13 07:39:10 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-07-13 07:39:10 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-07-13 07:39:10 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-07-13 07:39:10 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-13 07:39:10 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-13 07:39:10 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-13 07:39:11 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-13 07:39:11 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-13 07:39:13 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-13 07:39:13 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-13 07:39:14 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-13 07:39:14 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-13 07:39:14 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-13 07:39:14 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-13 07:39:17 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-13 07:39:17 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-07-13 07:39:18 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-13 07:39:18 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-07-13 07:39:18 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-13 07:39:18 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-13 07:39:19 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-13 07:39:19 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-13 07:39:19 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-07-13 07:39:19 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-13 07:39:19 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-13 07:39:22 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-13 07:39:22 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-13 07:39:22 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-13 07:39:22 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-13 07:39:23 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-13 07:39:23 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-13 07:39:23 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-13 07:39:23 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-13 07:39:23 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-13 07:39:23 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-13 07:39:23 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-13 07:39:23 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-13 07:39:23 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-13 07:39:23 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-13 07:39:23 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-13 07:39:23 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-13 07:39:23 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-13 07:39:23 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-13 07:39:23 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-13 07:39:23 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-13 07:39:23 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-13 07:39:23 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-13 07:39:23 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-13 07:39:24 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-13 07:39:24 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-13 07:39:24 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-13 07:39:24 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-07-13 07:39:24 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-07-13 07:39:24 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-07-13 07:39:24 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-07-13 07:39:24 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-07-13 07:39:24 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-07-13 07:39:24 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-07-13 07:39:25 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-07-13 07:39:25 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-07-13 07:39:25 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-07-13 07:39:25 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-07-13 07:39:25 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-07-13 07:39:25 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-07-13 07:39:26 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-07-13 07:39:26 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-07-13 07:39:26 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-07-13 07:39:26 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-07-13 07:39:26 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-07-13 07:39:26 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-07-13 07:39:27 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-07-13 07:39:27 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-07-13 07:39:27 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-07-13 07:39:27 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-07-13 07:39:27 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-07-13 07:39:27 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-07-13 07:39:27 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-07-13 07:39:27 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-07-13 07:39:27 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-07-13 07:39:27 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-07-13 07:39:28 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-07-13 07:39:28 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-07-13 07:39:28 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-07-13 07:39:28 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-07-13 07:39:28 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-07-13 07:39:28 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-07-13 07:39:28 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-07-13 07:39:28 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-07-13 07:39:28 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-07-13 07:39:28 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-07-13 07:39:28 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-07-13 07:39:28 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-07-13 07:39:28 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-07-13 07:39:28 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-07-13 07:39:28 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-07-13 07:39:28 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-07-13 07:39:28 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-07-13 07:39:28 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-07-13 07:39:29 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-07-13 07:39:29 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-07-13 07:39:29 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-07-13 07:39:29 - DEBUG UnitTestFramework: '#run: 'basic''

2017-07-13 07:39:29 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-07-13 07:39:29 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-07-13 07:39:29 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-07-13 07:39:29 - DEBUG UnitTestFramework: '#setup: 'another''

2017-07-13 07:39:29 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-07-13 07:39:29 - DEBUG UnitTestFramework: '#run: 'another''

2017-07-13 07:39:29 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-07-13 07:39:29 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-07-13 07:39:30 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-07-13 07:39:30 - DEBUG UnitTestFramework: '#setup: 'skip''

2017-07-13 07:39:30 - DEBUG UnitTestFramework: '#setup ok: 'skip''

2017-07-13 07:39:30 - DEBUG UnitTestFramework: '#run: 'skip''

2017-07-13 07:39:30 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-07-13 07:39:30 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-07-13 07:39:31 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-07-13 07:39:31 - DEBUG UnitTestFramework: '#run ok: 'skip''

2017-07-13 07:39:31 - DEBUG UnitTestFramework: '#teardown: 'skip''

2017-07-13 07:39:31 - DEBUG UnitTestFramework: '#teardown ok: 'skip''

2017-07-13 07:39:31 - DEBUG UnitTestFramework: '#setup: 'another skip''

2017-07-13 07:39:31 - DEBUG UnitTestFramework: '#setup ok: 'another skip''

2017-07-13 07:39:31 - DEBUG UnitTestFramework: '#run: 'another skip''

2017-07-13 07:39:31 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-07-13 07:39:31 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-07-13 07:39:31 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-07-13 07:39:31 - DEBUG UnitTestFramework: '#run ok: 'another skip''

2017-07-13 07:39:31 - DEBUG UnitTestFramework: '#teardown: 'another skip''

2017-07-13 07:39:32 - DEBUG UnitTestFramework: '#teardown ok: 'another skip''

2017-07-13 07:39:32 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox spy''

2017-07-13 07:39:33 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox spy''

2017-07-13 07:39:33 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox spy''

2017-07-13 07:39:36 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox spy''

2017-07-13 07:39:36 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox spy''

2017-07-13 07:39:37 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox spy''

2017-07-13 07:39:37 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub''

2017-07-13 07:39:37 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub''

2017-07-13 07:39:37 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub''

2017-07-13 07:39:37 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub''

2017-07-13 07:39:37 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub''

2017-07-13 07:39:38 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub''

2017-07-13 07:39:38 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub override''

2017-07-13 07:39:38 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub override''

2017-07-13 07:39:38 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub override''

2017-07-13 07:39:38 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub override''

2017-07-13 07:39:38 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub override''

2017-07-13 07:39:39 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub override''

2017-07-13 07:39:39 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox mock''

2017-07-13 07:39:40 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox mock''

2017-07-13 07:39:40 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox mock''

2017-07-13 07:39:42 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox mock''

2017-07-13 07:39:42 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox mock''

2017-07-13 07:39:42 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox mock''

2017-07-13 07:39:42 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox restore after test end''

2017-07-13 07:39:43 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox restore after test end''

2017-07-13 07:39:43 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox restore after test end''

2017-07-13 07:39:43 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox restore after test end''

2017-07-13 07:39:43 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox restore after test end''

2017-07-13 07:39:43 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox restore after test end''

2017-07-13 07:39:43 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-07-13 07:39:43 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-07-13 07:39:43 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-07-13 07:39:43 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-07-13 07:39:43 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-07-13 07:39:44 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-07-13 07:39:44 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-07-13 07:39:44 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-07-13 07:39:44 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-07-13 07:39:45 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-07-13 07:39:45 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-07-13 07:39:45 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-07-13 07:39:45 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-07-13 07:39:46 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-07-13 07:39:46 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-07-13 07:39:46 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-07-13 07:39:46 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-07-13 07:39:46 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-07-13 07:39:46 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-07-13 07:39:46 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-07-13 07:39:47 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-07-13 07:39:47 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-07-13 07:39:47 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-07-13 07:39:47 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-07-13 07:39:47 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-07-13 07:39:47 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-07-13 07:39:47 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-07-13 07:39:47 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-07-13 07:39:47 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-07-13 07:39:48 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-07-13 07:39:48 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-07-13 07:39:48 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-07-13 07:39:48 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-07-13 07:39:48 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-07-13 07:39:48 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-07-13 07:39:49 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-07-13 07:39:49 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-13 07:39:49 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-13 07:39:49 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-13 07:39:49 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-13 07:39:49 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-13 07:39:49 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-13 07:39:49 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-13 07:39:50 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-13 07:39:50 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-13 07:39:50 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-13 07:39:50 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-13 07:39:51 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-13 07:39:51 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-13 07:39:51 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-13 07:39:51 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-13 07:39:51 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-13 07:39:51 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-13 07:39:51 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-13 07:39:51 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-13 07:39:52 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-13 07:39:52 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-13 07:39:52 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-13 07:39:52 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-13 07:39:52 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-13 07:39:52 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-13 07:39:52 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-13 07:39:52 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-13 07:39:52 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-13 07:39:52 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-13 07:39:53 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-13 07:39:53 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-07-13 07:39:53 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-07-13 07:39:53 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-07-13 07:39:54 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-07-13 07:39:54 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-07-13 07:39:54 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-07-13 07:39:54 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-07-13 07:39:54 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-07-13 07:39:54 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-07-13 07:40:06 - DEBUG UnitTestFramework: '#run ok: 'Can connect to a remote peer''

2017-07-13 07:40:06 - DEBUG UnitTestFramework: '#teardown: 'Can connect to a remote peer''

2017-07-13 07:40:07 - DEBUG UnitTestFramework: '#teardown ok: 'Can connect to a remote peer''

2017-07-13 07:40:07 - DEBUG UnitTestFramework: '#setup: 'Can shift data''

2017-07-13 07:40:07 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data''

2017-07-13 07:40:07 - DEBUG UnitTestFramework: '#run: 'Can shift data''

2017-07-13 07:40:22 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'e0057761-8e67-4a43-9e8f-890fc329982f', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-13 07:40:22 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-07-13 07:40:23 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '6d8e0cea-3f31-4b47-bf5f-2c8e52663cde', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-13 07:40:23 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-07-13 07:40:23 - DEBUG UnitTestFramework: '#run ok: 'Can shift data''

2017-07-13 07:40:23 - DEBUG UnitTestFramework: '#teardown: 'Can shift data''

2017-07-13 07:40:23 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data''

2017-07-13 07:40:23 - DEBUG UnitTestFramework: '#setup: 'Can shift data via parallel connections''

2017-07-13 07:40:24 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data via parallel connections''

2017-07-13 07:40:24 - DEBUG UnitTestFramework: '#run: 'Can shift data via parallel connections''

2017-07-13 07:40:40 - DEBUG UnitTestFramework: '#run ok: 'Can shift data via parallel connections''

2017-07-13 07:40:40 - DEBUG UnitTestFramework: '#teardown: 'Can shift data via parallel connections''

2017-07-13 07:40:41 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data via parallel connections''

2017-07-13 07:40:41 - DEBUG UnitTestFramework: '#setup: 'Can shift data securely''

2017-07-13 07:40:42 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data securely''

2017-07-13 07:40:42 - DEBUG UnitTestFramework: '#run: 'Can shift data securely''

2017-07-13 07:40:57 - ERROR UnitTestFramework: '#run failed: 'Can shift data securely', error: 'Error: run failed, test: 'Can shift data securely', event: 'run_Can shift data securely', sent data: '[{"uuid":"7429bd2a-7ddd-4480-9dee-bcb66c6ea3bf"},{"uuid":"ac0e4d72-52ca-4ad2-9509-e84c7cd40172"},{"uuid":"26bb0a9c-78ae-475d-ae1e-25e4e9f16cba"}]', received data: '{"success":false}'', stack: 'Error: run failed, test: 'Can shift data securely', event: 'run_Can shift data securely', sent data: '[{"uuid":"7429bd2a-7ddd-4480-9dee-bcb66c6ea3bf"},{"uuid":"ac0e4d72-52ca-4ad2-9509-e84c7cd40172"},{"uuid":"26bb0a9c-78ae-475d-ae1e-25e4e9f16cba"}]', received data: '{"success":false}'
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

2017-07-13 07:40:57 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'ios', error: 'Error: run failed, test: 'Can shift data securely', event: 'run_Can shift data securely', sent data: '[{"uuid":"7429bd2a-7ddd-4480-9dee-bcb66c6ea3bf"},{"uuid":"ac0e4d72-52ca-4ad2-9509-e84c7cd40172"},{"uuid":"26bb0a9c-78ae-475d-ae1e-25e4e9f16cba"}]', received data: '{"success":false}'', stack: 'Error: run failed, test: 'Can shift data securely', event: 'run_Can shift data securely', sent data: '[{"uuid":"7429bd2a-7ddd-4480-9dee-bcb66c6ea3bf"},{"uuid":"ac0e4d72-52ca-4ad2-9509-e84c7cd40172"},{"uuid":"26bb0a9c-78ae-475d-ae1e-25e4e9f16cba"}]', received data: '{"success":false}'
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

2017-07-13 07:42:11 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '513b9c6e-6054-44ae-87ff-6b3b282030d2', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-13 07:42:11 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-07-13 07:42:11 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-07-13 07:42:11 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-07-13 07:42:11 - DEBUG UnitTestFramework: 'scheduling tests'

2017-07-13 07:42:15 - DEBUG UnitTestFramework: 'tests scheduled'

2017-07-13 07:42:15 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-07-13 07:42:18 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-07-13 07:42:18 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-07-13 07:42:22 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-07-13 07:42:22 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-07-13 07:42:23 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-07-13 07:42:23 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-07-13 07:42:26 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-07-13 07:42:26 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-07-13 07:42:30 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-07-13 07:42:30 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-07-13 07:42:30 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-07-13 07:42:30 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-13 07:42:33 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-13 07:42:33 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-13 07:42:34 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-13 07:42:34 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-13 07:42:36 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-13 07:42:36 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-13 07:42:39 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-13 07:42:39 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-13 07:42:39 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-13 07:42:39 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-13 07:42:40 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-13 07:42:40 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-07-13 07:42:40 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-13 07:42:40 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-07-13 07:42:40 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-13 07:42:40 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-13 07:42:40 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-13 07:42:40 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-13 07:42:40 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-07-13 07:42:40 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-13 07:42:40 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-13 07:42:40 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-13 07:42:40 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-13 07:42:40 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-13 07:42:40 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-13 07:42:40 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-13 07:42:40 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-13 07:42:40 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-13 07:42:40 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-13 07:42:40 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-13 07:42:40 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-13 07:42:40 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-13 07:42:40 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-13 07:42:40 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-13 07:42:40 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-13 07:42:40 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-13 07:42:40 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-13 07:42:40 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-13 07:42:40 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-13 07:42:40 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-13 07:42:40 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-13 07:42:40 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-13 07:42:40 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-13 07:42:40 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-13 07:42:40 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-13 07:42:40 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-13 07:42:40 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-13 07:42:40 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-07-13 07:42:40 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-07-13 07:42:40 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-07-13 07:42:40 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-07-13 07:42:40 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-07-13 07:42:40 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-07-13 07:42:40 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-07-13 07:42:40 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-07-13 07:42:40 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-07-13 07:42:40 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-07-13 07:42:40 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-07-13 07:42:40 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-07-13 07:42:40 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-07-13 07:42:41 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-07-13 07:42:41 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-07-13 07:42:41 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-07-13 07:42:41 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-07-13 07:42:41 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-07-13 07:42:41 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-07-13 07:42:41 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-07-13 07:42:41 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-07-13 07:42:41 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-07-13 07:42:41 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-07-13 07:42:41 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-07-13 07:42:41 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-07-13 07:42:41 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-07-13 07:42:41 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-07-13 07:42:41 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-07-13 07:42:41 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-07-13 07:42:41 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-07-13 07:42:41 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-07-13 07:42:41 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-07-13 07:42:41 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-07-13 07:42:41 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-07-13 07:42:41 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-07-13 07:42:41 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''
2017-07-13 07:42:41 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-07-13 07:42:42 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''
2017-07-13 07:42:42 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-07-13 07:42:42 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-07-13 07:42:42 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-07-13 07:42:42 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-07-13 07:42:42 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-07-13 07:42:42 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-07-13 07:42:42 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-07-13 07:42:42 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-07-13 07:42:42 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-07-13 07:42:42 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-07-13 07:42:42 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-07-13 07:42:42 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-07-13 07:42:42 - DEBUG UnitTestFramework: '#run: 'basic''

2017-07-13 07:42:42 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-07-13 07:42:42 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-07-13 07:42:42 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-07-13 07:42:42 - DEBUG UnitTestFramework: '#setup: 'another''

2017-07-13 07:42:42 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-07-13 07:42:42 - DEBUG UnitTestFramework: '#run: 'another''

2017-07-13 07:42:42 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-07-13 07:42:42 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-07-13 07:42:42 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-07-13 07:42:42 - DEBUG UnitTestFramework: '#setup: 'skip''

2017-07-13 07:42:42 - DEBUG UnitTestFramework: '#setup ok: 'skip''

2017-07-13 07:42:42 - DEBUG UnitTestFramework: '#run: 'skip''

2017-07-13 07:42:42 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-07-13 07:42:42 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-07-13 07:42:42 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-07-13 07:42:42 - DEBUG UnitTestFramework: '#run ok: 'skip''

2017-07-13 07:42:42 - DEBUG UnitTestFramework: '#teardown: 'skip''

2017-07-13 07:42:42 - DEBUG UnitTestFramework: '#teardown ok: 'skip''

2017-07-13 07:42:42 - DEBUG UnitTestFramework: '#setup: 'another skip''

2017-07-13 07:42:42 - DEBUG UnitTestFramework: '#setup ok: 'another skip''

2017-07-13 07:42:42 - DEBUG UnitTestFramework: '#run: 'another skip''

2017-07-13 07:42:42 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-07-13 07:42:42 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-07-13 07:42:42 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-07-13 07:42:42 - DEBUG UnitTestFramework: '#run ok: 'another skip''

2017-07-13 07:42:42 - DEBUG UnitTestFramework: '#teardown: 'another skip''

2017-07-13 07:42:42 - DEBUG UnitTestFramework: '#teardown ok: 'another skip''

2017-07-13 07:42:42 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox spy''

2017-07-13 07:42:42 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox spy''

2017-07-13 07:42:42 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox spy''

2017-07-13 07:42:42 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox spy''

2017-07-13 07:42:42 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox spy''

2017-07-13 07:42:42 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox spy''

2017-07-13 07:42:42 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub''

2017-07-13 07:42:43 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub''

2017-07-13 07:42:43 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub''

2017-07-13 07:42:43 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub''

2017-07-13 07:42:43 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub''

2017-07-13 07:42:43 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub''

2017-07-13 07:42:43 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub override''

2017-07-13 07:42:43 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub override''

2017-07-13 07:42:43 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub override''

2017-07-13 07:42:43 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub override''

2017-07-13 07:42:43 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub override''

2017-07-13 07:42:43 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub override''

2017-07-13 07:42:43 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox mock''

2017-07-13 07:42:43 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox mock''

2017-07-13 07:42:43 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox mock''

2017-07-13 07:42:43 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox mock''

2017-07-13 07:42:43 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox mock''

2017-07-13 07:42:43 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox mock''

2017-07-13 07:42:43 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox restore after test end''

2017-07-13 07:42:43 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox restore after test end''

2017-07-13 07:42:43 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox restore after test end''

2017-07-13 07:42:43 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox restore after test end''

2017-07-13 07:42:43 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox restore after test end''

2017-07-13 07:42:43 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox restore after test end''

2017-07-13 07:42:43 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-07-13 07:42:43 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-07-13 07:42:43 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-07-13 07:42:43 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-07-13 07:42:43 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-07-13 07:42:43 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-07-13 07:42:43 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-07-13 07:42:43 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-07-13 07:42:43 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-07-13 07:42:43 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-07-13 07:42:43 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-07-13 07:42:43 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-07-13 07:42:43 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-07-13 07:42:43 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-07-13 07:42:43 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-07-13 07:42:44 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-07-13 07:42:44 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-07-13 07:42:44 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-07-13 07:42:44 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-07-13 07:42:44 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-07-13 07:42:44 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-07-13 07:42:44 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-07-13 07:42:44 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-07-13 07:42:44 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-07-13 07:42:44 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-07-13 07:42:44 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-07-13 07:42:44 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-07-13 07:42:45 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-07-13 07:42:45 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-07-13 07:42:45 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-07-13 07:42:45 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-13 07:42:45 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-13 07:42:45 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-13 07:42:46 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-13 07:42:46 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-13 07:42:47 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-13 07:42:47 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-13 07:42:47 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-13 07:42:47 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-13 07:42:47 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-13 07:42:47 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-13 07:42:47 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-13 07:42:47 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-13 07:42:47 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-13 07:42:47 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-13 07:42:48 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-13 07:42:48 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-13 07:42:51 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-13 07:42:51 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-13 07:42:53 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-13 07:42:53 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-13 07:42:56 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-13 07:42:56 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-13 07:42:57 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-13 07:42:57 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-13 07:42:59 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-13 07:42:59 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-13 07:43:00 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-13 07:43:00 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-13 07:43:03 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-13 07:43:03 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-07-13 07:43:04 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-07-13 07:43:04 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-07-13 07:43:08 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-07-13 07:43:08 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-07-13 07:43:12 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-07-13 07:43:12 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-07-13 07:43:12 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-07-13 07:43:12 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-07-13 07:43:20 - DEBUG UnitTestFramework: '#run ok: 'Can connect to a remote peer''

2017-07-13 07:43:20 - DEBUG UnitTestFramework: '#teardown: 'Can connect to a remote peer''

2017-07-13 07:43:21 - DEBUG UnitTestFramework: '#teardown ok: 'Can connect to a remote peer''

2017-07-13 07:43:21 - DEBUG UnitTestFramework: '#setup: 'Can shift data''

2017-07-13 07:43:23 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data''

2017-07-13 07:43:23 - DEBUG UnitTestFramework: '#run: 'Can shift data''

2017-07-13 07:43:28 - DEBUG UnitTestFramework: '#run ok: 'Can shift data''

2017-07-13 07:43:28 - DEBUG UnitTestFramework: '#teardown: 'Can shift data''

2017-07-13 07:43:31 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data''

2017-07-13 07:43:31 - DEBUG UnitTestFramework: '#setup: 'Can shift data via parallel connections''

2017-07-13 07:43:31 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data via parallel connections''

2017-07-13 07:43:31 - DEBUG UnitTestFramework: '#run: 'Can shift data via parallel connections''

2017-07-13 07:43:32 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-07-13 07:43:32 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-07-13 07:43:33 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-07-13 07:43:33 - DEBUG UnitTestFramework: '#run ok: 'Can shift data via parallel connections''

2017-07-13 07:43:33 - DEBUG UnitTestFramework: '#teardown: 'Can shift data via parallel connections''

2017-07-13 07:43:34 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data via parallel connections''

2017-07-13 07:43:34 - DEBUG UnitTestFramework: '#setup: 'Can shift data securely''

2017-07-13 07:43:36 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data securely''

2017-07-13 07:43:36 - DEBUG UnitTestFramework: '#run: 'Can shift data securely''

2017-07-13 07:43:43 - DEBUG UnitTestFramework: '#run ok: 'Can shift data securely''

2017-07-13 07:43:43 - DEBUG UnitTestFramework: '#teardown: 'Can shift data securely''

2017-07-13 07:43:46 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data securely''

2017-07-13 07:43:46 - DEBUG UnitTestFramework: '#setup: 'Can shift large amounts of data''

2017-07-13 07:43:48 - DEBUG UnitTestFramework: '#setup ok: 'Can shift large amounts of data''

2017-07-13 07:43:48 - DEBUG UnitTestFramework: '#run: 'Can shift large amounts of data''

2017-07-13 07:43:51 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_11335185196ab692/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-07-13 07:43:51 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-1' disconnected, reason: 'undefined''

2017-07-13 07:43:51 - INFO HttpServer: 'Socket to device name: 'Apple-Iphone6sPlus-1' disconnected, reason: 'undefined''

2017-07-13 07:43:51 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-mfts' disconnected, reason: 'undefined''

2017-07-13 07:43:51 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-07-13 07:43:51 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''

2017-07-13 07:43:51 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

[0;31merror: command 'sudo jx ______.js all' failed with code 1, file 'bash' on line 30[0m
One or more Android tests are failed.
 [0m
index.js failed [ 1 ]

```


Logs for system : 
```

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!

ios : Error: Command failed: true
13/7/2017@09:35:24 Getting the list of iOS devices 
13/7/2017@09:35:25 ios: device name: Iphone6sPlus-1 , device identifier:  f70cda60583ea0f895d05ea355cd125983c27594
13/7/2017@09:35:25 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
13/7/2017@09:35:25 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
13/7/2017@09:35:25 Deploying iOS test app 
13/7/2017@09:35:25 uninstalling the application 
13/7/2017@09:35:27 installing the application 
true

```
###Android Logs
####Node name: thali01
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


###iOS Logs
[Iphone6sPlus-1](https://github.com/ThaliTester/TestResults/blob/11335185196ab692_CI_sanity_check_jareksl/iOS_Iphone6sPlus-1.md)

[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/11335185196ab692_CI_sanity_check_jareksl/iOS_iphone-5s-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/11335185196ab692_CI_sanity_check_jareksl/iOS_iphone-5s-mfts.md)




